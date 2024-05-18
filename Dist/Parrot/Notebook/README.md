Parrot - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Parrot.

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

Total: 595

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite E55-A             | [b77667e33a](https://linux-hardware.org/?probe=b77667e33a) | May 08, 2024 |
| HP            | 2000                        | [71d3942f81](https://linux-hardware.org/?probe=71d3942f81) | May 06, 2024 |
| Acer          | Aspire E1-522               | [b1c41ef5a0](https://linux-hardware.org/?probe=b1c41ef5a0) | May 04, 2024 |
| Dell          | Latitude E6430              | [3ea51c9416](https://linux-hardware.org/?probe=3ea51c9416) | May 04, 2024 |
| Dell          | Latitude E6430              | [0e3b2e7c55](https://linux-hardware.org/?probe=0e3b2e7c55) | May 04, 2024 |
| Toshiba       | Satellite E55-A             | [66fc7bf95a](https://linux-hardware.org/?probe=66fc7bf95a) | Apr 30, 2024 |
| Acidanther... | MacBookAir9,1               | [ba60edeb99](https://linux-hardware.org/?probe=ba60edeb99) | Apr 25, 2024 |
| MSI           | GL75 9SEK                   | [3d679e4ec2](https://linux-hardware.org/?probe=3d679e4ec2) | Apr 17, 2024 |
| MSI           | GL75 9SEK                   | [b2d528d9b4](https://linux-hardware.org/?probe=b2d528d9b4) | Apr 16, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [6291093e82](https://linux-hardware.org/?probe=6291093e82) | Apr 16, 2024 |
| Lenovo        | E41-25 81FS                 | [ee47604b55](https://linux-hardware.org/?probe=ee47604b55) | Apr 13, 2024 |
| HP            | Laptop 14-cf2xxx            | [bc17e5113b](https://linux-hardware.org/?probe=bc17e5113b) | Apr 13, 2024 |
| HP            | Laptop 14-cf2xxx            | [bef6cb8975](https://linux-hardware.org/?probe=bef6cb8975) | Apr 13, 2024 |
| Lenovo        | Z50-70 20354                | [4469cb6e76](https://linux-hardware.org/?probe=4469cb6e76) | Apr 10, 2024 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [2c23a28e81](https://linux-hardware.org/?probe=2c23a28e81) | Apr 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c737a816f3](https://linux-hardware.org/?probe=c737a816f3) | Apr 04, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [d0eac00952](https://linux-hardware.org/?probe=d0eac00952) | Apr 02, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [c498cd96d4](https://linux-hardware.org/?probe=c498cd96d4) | Mar 31, 2024 |
| Razer         | Blade 15 - RZ09-0485        | [24980909b2](https://linux-hardware.org/?probe=24980909b2) | Mar 26, 2024 |
| HP            | EliteBook 830 G6            | [955e65cc0f](https://linux-hardware.org/?probe=955e65cc0f) | Mar 22, 2024 |
| HP            | EliteBook 830 G6            | [c5ada253ab](https://linux-hardware.org/?probe=c5ada253ab) | Mar 22, 2024 |
| HP            | EliteBook 830 G6            | [2ab6329c32](https://linux-hardware.org/?probe=2ab6329c32) | Mar 22, 2024 |
| Acer          | Extensa 5230                | [790672cb92](https://linux-hardware.org/?probe=790672cb92) | Mar 22, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | [700d8c6016](https://linux-hardware.org/?probe=700d8c6016) | Mar 18, 2024 |
| Lenovo        | ThinkPad T480 20L6S69X08    | [63c84de71e](https://linux-hardware.org/?probe=63c84de71e) | Mar 15, 2024 |
| Dell          | Latitude 5420 Rugged        | [f9c7c915c9](https://linux-hardware.org/?probe=f9c7c915c9) | Mar 08, 2024 |
| Apple         | MacBookAir7,2               | [58e64cec89](https://linux-hardware.org/?probe=58e64cec89) | Mar 06, 2024 |
| Apple         | MacBookAir7,2               | [74faba00a3](https://linux-hardware.org/?probe=74faba00a3) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480 20L6S69X08    | [16326b521f](https://linux-hardware.org/?probe=16326b521f) | Mar 01, 2024 |
| Dell          | XPS 13 9370                 | [086a1782c7](https://linux-hardware.org/?probe=086a1782c7) | Feb 22, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | [da65aaff1d](https://linux-hardware.org/?probe=da65aaff1d) | Feb 20, 2024 |
| Samsung       | 750XDA                      | [0aed547d08](https://linux-hardware.org/?probe=0aed547d08) | Feb 18, 2024 |
| HP            | Pavilion dv4                | [20e9de9ad8](https://linux-hardware.org/?probe=20e9de9ad8) | Feb 08, 2024 |
| ASUSTek       | UX430UAR                    | [cc89a20253](https://linux-hardware.org/?probe=cc89a20253) | Feb 04, 2024 |
| Apple         | MacBookPro11,1              | [fcabd4a1f4](https://linux-hardware.org/?probe=fcabd4a1f4) | Feb 01, 2024 |
| Apple         | MacBookPro11,1              | [b31d7d9323](https://linux-hardware.org/?probe=b31d7d9323) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480s 20L70028U... | [7acd38748f](https://linux-hardware.org/?probe=7acd38748f) | Jan 30, 2024 |
| Apple         | MacBookPro11,1              | [7c4514376b](https://linux-hardware.org/?probe=7c4514376b) | Jan 27, 2024 |
| Apple         | MacBookPro11,1              | [f1117537a5](https://linux-hardware.org/?probe=f1117537a5) | Jan 27, 2024 |
| Acer          | Aspire A715-51G             | [fad23c2b03](https://linux-hardware.org/?probe=fad23c2b03) | Jan 27, 2024 |
| Dell          | XPS 13 9350                 | [fb1c7c4cab](https://linux-hardware.org/?probe=fb1c7c4cab) | Jan 26, 2024 |
| Lenovo        | ThinkPad T460s 20FAS2JW0... | [59d637113b](https://linux-hardware.org/?probe=59d637113b) | Jan 26, 2024 |
| Acer          | Aspire E1-522               | [a43c97b66c](https://linux-hardware.org/?probe=a43c97b66c) | Jan 26, 2024 |
| HP            | ProBook 455 G4              | [6490d02d72](https://linux-hardware.org/?probe=6490d02d72) | Jan 22, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [bb5610a4f5](https://linux-hardware.org/?probe=bb5610a4f5) | Jan 17, 2024 |
| Acer          | Aspire E1-522               | [538c5ee96f](https://linux-hardware.org/?probe=538c5ee96f) | Jan 16, 2024 |
| HP            | Victus by Gaming Laptop ... | [feaf3edd58](https://linux-hardware.org/?probe=feaf3edd58) | Jan 10, 2024 |
| Acer          | Aspire A715-51G             | [2a3ea77b7a](https://linux-hardware.org/?probe=2a3ea77b7a) | Jan 10, 2024 |
| Lenovo        | ThinkPad T490 20N20023US    | [ce82358c06](https://linux-hardware.org/?probe=ce82358c06) | Jan 04, 2024 |
| Lenovo        | ThinkPad T490 20N20023US    | [ffe96991b4](https://linux-hardware.org/?probe=ffe96991b4) | Jan 04, 2024 |
| HP            | ProBook 450 G5              | [b80a7c9287](https://linux-hardware.org/?probe=b80a7c9287) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [1f44330bcf](https://linux-hardware.org/?probe=1f44330bcf) | Dec 31, 2023 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | [0afd47e9fc](https://linux-hardware.org/?probe=0afd47e9fc) | Dec 31, 2023 |
| Google        | Blorb                       | [4e0c068a82](https://linux-hardware.org/?probe=4e0c068a82) | Dec 30, 2023 |
| HP            | Pavilion g6                 | [62a002d063](https://linux-hardware.org/?probe=62a002d063) | Dec 26, 2023 |
| Apple         | MacBookAir5,1               | [5c7029f981](https://linux-hardware.org/?probe=5c7029f981) | Dec 23, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [980280224f](https://linux-hardware.org/?probe=980280224f) | Dec 18, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [41f03f0699](https://linux-hardware.org/?probe=41f03f0699) | Dec 18, 2023 |
| Toshiba       | PORTEGE R930                | [e341599417](https://linux-hardware.org/?probe=e341599417) | Dec 14, 2023 |
| HP            | EliteBook 850 G3            | [baf21dcbce](https://linux-hardware.org/?probe=baf21dcbce) | Dec 06, 2023 |
| ASUSTek       | X540SAA                     | [86295630b8](https://linux-hardware.org/?probe=86295630b8) | Dec 06, 2023 |
| Alienware     | 17 R5                       | [e0fdc679e3](https://linux-hardware.org/?probe=e0fdc679e3) | Dec 04, 2023 |
| Alienware     | 17 R5                       | [1e44992982](https://linux-hardware.org/?probe=1e44992982) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [30c19ab13f](https://linux-hardware.org/?probe=30c19ab13f) | Dec 04, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [d416d62cf1](https://linux-hardware.org/?probe=d416d62cf1) | Nov 29, 2023 |
| Acer          | Nitro AN517-55              | [91df918363](https://linux-hardware.org/?probe=91df918363) | Nov 28, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [a54c387b5f](https://linux-hardware.org/?probe=a54c387b5f) | Nov 27, 2023 |
| Apple         | MacBookAir6,1               | [e22c72e9d4](https://linux-hardware.org/?probe=e22c72e9d4) | Nov 26, 2023 |
| Apple         | MacBookAir6,1               | [dfa296fd96](https://linux-hardware.org/?probe=dfa296fd96) | Nov 25, 2023 |
| Lenovo        | Flex 2-15 20405             | [8ad2369936](https://linux-hardware.org/?probe=8ad2369936) | Nov 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a8e951e3b6](https://linux-hardware.org/?probe=a8e951e3b6) | Nov 20, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B30... | [5685f17122](https://linux-hardware.org/?probe=5685f17122) | Nov 19, 2023 |
| Acer          | TravelMate 5760             | [f90be838c9](https://linux-hardware.org/?probe=f90be838c9) | Nov 18, 2023 |
| Acer          | TravelMate 5760             | [db234d226d](https://linux-hardware.org/?probe=db234d226d) | Nov 18, 2023 |
| Dell          | Latitude E6530              | [f43bd72db4](https://linux-hardware.org/?probe=f43bd72db4) | Nov 16, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [20394838bd](https://linux-hardware.org/?probe=20394838bd) | Nov 11, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [e7b5bfa0b4](https://linux-hardware.org/?probe=e7b5bfa0b4) | Nov 06, 2023 |
| Unknown       | Unknown                     | [2c2d291f54](https://linux-hardware.org/?probe=2c2d291f54) | Nov 05, 2023 |
| MSI           | Prestige 14Evo A12M         | [98e32e98bf](https://linux-hardware.org/?probe=98e32e98bf) | Oct 31, 2023 |
| HP            | EliteBook 850 G3            | [be57c0ce22](https://linux-hardware.org/?probe=be57c0ce22) | Oct 29, 2023 |
| Google        | Reef                        | [819e00dd76](https://linux-hardware.org/?probe=819e00dd76) | Oct 22, 2023 |
| Acer          | Extensa 215-54              | [4e2a3f7606](https://linux-hardware.org/?probe=4e2a3f7606) | Oct 15, 2023 |
| Acer          | Extensa 215-54              | [94d47a3e29](https://linux-hardware.org/?probe=94d47a3e29) | Oct 15, 2023 |
| HP            | ENVY m6 Notebook            | [fb0b3ea9e7](https://linux-hardware.org/?probe=fb0b3ea9e7) | Oct 12, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [30b0879baa](https://linux-hardware.org/?probe=30b0879baa) | Oct 07, 2023 |
| Dell          | XPS 15 9500                 | [ee251b10d4](https://linux-hardware.org/?probe=ee251b10d4) | Oct 07, 2023 |
| Samsung       | 550XBE/350XBE               | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | [3185dde146](https://linux-hardware.org/?probe=3185dde146) | Oct 04, 2023 |
| HP            | ENVY m6 Notebook            | [5ef983c393](https://linux-hardware.org/?probe=5ef983c393) | Oct 01, 2023 |
| Lenovo        | Z51-70 80K6                 | [167d2e893e](https://linux-hardware.org/?probe=167d2e893e) | Sep 27, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [37ecdee3d3](https://linux-hardware.org/?probe=37ecdee3d3) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [ecc0e92fb0](https://linux-hardware.org/?probe=ecc0e92fb0) | Sep 24, 2023 |
| HP            | Laptop 15-dy2xxx            | [faa9a71ce1](https://linux-hardware.org/?probe=faa9a71ce1) | Sep 17, 2023 |
| MSI           | Stealth 15M B12UE           | [2f99528572](https://linux-hardware.org/?probe=2f99528572) | Sep 16, 2023 |
| HP            | Laptop 17-cn0xxx            | [6495df6735](https://linux-hardware.org/?probe=6495df6735) | Sep 15, 2023 |
| ASUSTek       | S550CB                      | [dbf2770e09](https://linux-hardware.org/?probe=dbf2770e09) | Sep 10, 2023 |
| Toshiba       | Satellite L775D             | [681dab0969](https://linux-hardware.org/?probe=681dab0969) | Sep 09, 2023 |
| Dell          | Latitude 7280               | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| HP            | EliteBook 840 14 inch G9... | [ec33c11aa1](https://linux-hardware.org/?probe=ec33c11aa1) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [101a39c37a](https://linux-hardware.org/?probe=101a39c37a) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [da3ab01b3a](https://linux-hardware.org/?probe=da3ab01b3a) | Aug 25, 2023 |
| MSI           | Katana 15 B13VGK            | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [30c7051967](https://linux-hardware.org/?probe=30c7051967) | Aug 11, 2023 |
| MSI           | Summit E14Evo A12M          | [b83d821361](https://linux-hardware.org/?probe=b83d821361) | Aug 11, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [324819c88d](https://linux-hardware.org/?probe=324819c88d) | Aug 08, 2023 |
| Acer          | Aspire 4810T                | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [d3999a626a](https://linux-hardware.org/?probe=d3999a626a) | Aug 07, 2023 |
| Dell          | Precision 7730              | [1ed1a60e50](https://linux-hardware.org/?probe=1ed1a60e50) | Aug 06, 2023 |
| HP            | EliteBook 850 G3            | [ad4e7cf4ad](https://linux-hardware.org/?probe=ad4e7cf4ad) | Aug 01, 2023 |
| HP            | EliteBook 850 G3            | [36d9df3244](https://linux-hardware.org/?probe=36d9df3244) | Jul 31, 2023 |
| MSI           | Katana 17 B13VFK            | [8bc597da6e](https://linux-hardware.org/?probe=8bc597da6e) | Jul 29, 2023 |
| MSI           | Katana GF66 11UE            | [78e12df29a](https://linux-hardware.org/?probe=78e12df29a) | Jul 28, 2023 |
| HP            | ProBook 650 G2              | [cea811cc5f](https://linux-hardware.org/?probe=cea811cc5f) | Jul 25, 2023 |
| HP            | Laptop 15-dy2xxx            | [d047b35269](https://linux-hardware.org/?probe=d047b35269) | Jul 25, 2023 |
| HP            | ProBook 650 G2              | [affdd0a6f9](https://linux-hardware.org/?probe=affdd0a6f9) | Jul 25, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [af539103c5](https://linux-hardware.org/?probe=af539103c5) | Jul 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [58882ecdfe](https://linux-hardware.org/?probe=58882ecdfe) | Jul 20, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8abec746f7](https://linux-hardware.org/?probe=8abec746f7) | Jul 19, 2023 |
| HP            | Laptop 15-dy2xxx            | [3e6412c30b](https://linux-hardware.org/?probe=3e6412c30b) | Jul 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8e533f69a9](https://linux-hardware.org/?probe=8e533f69a9) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [c4b019ee7f](https://linux-hardware.org/?probe=c4b019ee7f) | Jul 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d7c21e7889](https://linux-hardware.org/?probe=d7c21e7889) | Jul 13, 2023 |
| Acer          | Aspire A515-47              | [10d3da2824](https://linux-hardware.org/?probe=10d3da2824) | Jul 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [37bc760339](https://linux-hardware.org/?probe=37bc760339) | Jul 11, 2023 |
| Acer          | Aspire A315-23              | [b5a021ae8a](https://linux-hardware.org/?probe=b5a021ae8a) | Jul 10, 2023 |
| Samsung       | 750XED                      | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| Dell          | Latitude 3410               | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| HP            | EliteBook 860 16 inch G9... | [4a4b49a909](https://linux-hardware.org/?probe=4a4b49a909) | Jul 03, 2023 |
| HP            | Laptop 15-dy2xxx            | [12871de62d](https://linux-hardware.org/?probe=12871de62d) | Jun 30, 2023 |
| HP            | Laptop 15-dy2xxx            | [ea4a5ccb1a](https://linux-hardware.org/?probe=ea4a5ccb1a) | Jun 29, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [a4b38b88cc](https://linux-hardware.org/?probe=a4b38b88cc) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [e28a0d43ed](https://linux-hardware.org/?probe=e28a0d43ed) | Jun 27, 2023 |
| HP            | ENVY m6 Notebook            | [ee31bf4efe](https://linux-hardware.org/?probe=ee31bf4efe) | Jun 26, 2023 |
| Unknown       | Unknown                     | [9c8513ff31](https://linux-hardware.org/?probe=9c8513ff31) | Jun 25, 2023 |
| HONOR         | BMH-WCX9                    | [f40cb826de](https://linux-hardware.org/?probe=f40cb826de) | Jun 25, 2023 |
| Samsung       | 530XBB                      | [51007aebd3](https://linux-hardware.org/?probe=51007aebd3) | Jun 24, 2023 |
| HP            | EliteBook 850 G3            | [3055046330](https://linux-hardware.org/?probe=3055046330) | Jun 20, 2023 |
| Lenovo        | ThinkPad L490 20Q5001YMX    | [c04ebf8de3](https://linux-hardware.org/?probe=c04ebf8de3) | Jun 20, 2023 |
| HP            | EliteBook 850 G3            | [2102fc8523](https://linux-hardware.org/?probe=2102fc8523) | Jun 19, 2023 |
| HP            | ENVY m6 Notebook            | [464db6c1df](https://linux-hardware.org/?probe=464db6c1df) | Jun 18, 2023 |
| Lenovo        | ThinkPad L520 78595GJ       | [52faa96ad0](https://linux-hardware.org/?probe=52faa96ad0) | Jun 17, 2023 |
| Dell          | Latitude 7430               | [e25ec87b40](https://linux-hardware.org/?probe=e25ec87b40) | Jun 17, 2023 |
| Dell          | Latitude 7430               | [35c6e2b80e](https://linux-hardware.org/?probe=35c6e2b80e) | Jun 17, 2023 |
| ASUSTek       | X550CL                      | [20a66afa75](https://linux-hardware.org/?probe=20a66afa75) | Jun 14, 2023 |
| Dell          | Vostro 3550                 | [3d8862fe69](https://linux-hardware.org/?probe=3d8862fe69) | Jun 13, 2023 |
| HP            | ENVY m6 Notebook            | [dbf4a1d57c](https://linux-hardware.org/?probe=dbf4a1d57c) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Onda TLC      | ONDA Oliver                 | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| HP            | ENVY m6 Notebook            | [f72410be27](https://linux-hardware.org/?probe=f72410be27) | Jun 08, 2023 |
| HP            | Laptop 15-dy2xxx            | [f0e52437a7](https://linux-hardware.org/?probe=f0e52437a7) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | [c359b173f6](https://linux-hardware.org/?probe=c359b173f6) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | [a0efed7ee2](https://linux-hardware.org/?probe=a0efed7ee2) | Jun 04, 2023 |
| Acer          | Nitro AN515-42              | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | Laptop 15s-fq1xxx           | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| Lenovo        | ThinkPad X230 2325UYW       | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [76a373f9dd](https://linux-hardware.org/?probe=76a373f9dd) | May 26, 2023 |
| Dell          | Latitude 7370               | [4c3bfe7a9d](https://linux-hardware.org/?probe=4c3bfe7a9d) | May 26, 2023 |
| Dell          | Latitude 7280               | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell          | Latitude 7280               | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| ASUSTek       | X551MA                      | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASUSTek       | X551MA                      | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| HP            | ProBook 4540s               | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| HP            | EliteBook 8760w             | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| Lenovo        | ThinkPad E14 20RA0059VA     | [72280fb1c5](https://linux-hardware.org/?probe=72280fb1c5) | May 14, 2023 |
| Dell          | Latitude 7370               | [78654593c7](https://linux-hardware.org/?probe=78654593c7) | May 10, 2023 |
| Acer          | Extensa 215-54              | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Acer          | Extensa 215-54              | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| Dell          | Latitude 7370               | [4ea44288b5](https://linux-hardware.org/?probe=4ea44288b5) | May 08, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [4ad69aea88](https://linux-hardware.org/?probe=4ad69aea88) | May 05, 2023 |
| Dell          | Precision 7720              | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| HP            | Notebook                    | [a34031954a](https://linux-hardware.org/?probe=a34031954a) | May 05, 2023 |
| ASUSTek       | K42Jc                       | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| MSI           | GF63 Thin 11UC              | [e9c446ce66](https://linux-hardware.org/?probe=e9c446ce66) | May 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [f3b5a181df](https://linux-hardware.org/?probe=f3b5a181df) | May 02, 2023 |
| Dell          | Inspiron N5110              | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Dell          | XPS 13 9350                 | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Acer          | Nitro AN515-57              | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| HP            | ProBook 4540s               | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Dell          | Inspiron 14 5410            | [89017780fa](https://linux-hardware.org/?probe=89017780fa) | Apr 25, 2023 |
| HP            | ProBook 4540s               | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| Gigabyte      | AORUS 15P KD                | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [04c16989b3](https://linux-hardware.org/?probe=04c16989b3) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [b307524661](https://linux-hardware.org/?probe=b307524661) | Apr 06, 2023 |
| Acer          | Extensa 215-54              | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| Google        | Lillipup                    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek       | X510UAR                     | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI           | Katana GF66 12UC            | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer          | Aspire E5-575               | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP            | Pavilion 15                 | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 23253Z5       | [1237b75ae4](https://linux-hardware.org/?probe=1237b75ae4) | Feb 24, 2023 |
| Dell          | Inspiron 3421               | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware     | 17 R5                       | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware     | 17 R5                       | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| Google        | Robo360                     | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |
| Apple         | MacBookPro9,2               | [725e7248ee](https://linux-hardware.org/?probe=725e7248ee) | Feb 04, 2023 |
| Acer          | Swift SFX14-51G             | [9f67df0760](https://linux-hardware.org/?probe=9f67df0760) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS2J300    | [741b347456](https://linux-hardware.org/?probe=741b347456) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| Apple         | MacBookAir7,2               | [91e33f05ed](https://linux-hardware.org/?probe=91e33f05ed) | Jan 24, 2023 |
| MSI           | Katana GF66 12UC            | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Quanta        | TW9/SW9                     | [4a196739f5](https://linux-hardware.org/?probe=4a196739f5) | Jan 18, 2023 |
| Lenovo        | ThinkPad E590 20NB0003AD    | [fe3de007e1](https://linux-hardware.org/?probe=fe3de007e1) | Jan 16, 2023 |
| Intel Clie... | LAPBC510                    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Dell          | Latitude E6520              | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| Acer          | Aspire A315-58              | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Unknown       | Unknown                     | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [aaac67afbe](https://linux-hardware.org/?probe=aaac67afbe) | Dec 23, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| HUAWEI        | BOD-WXX9                    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Dell          | G3 3500                     | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Intel Clie... | LAPBC510                    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| MSI           | GT60                        | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Quanta        | TW9/SW9                     | [5bfeb648aa](https://linux-hardware.org/?probe=5bfeb648aa) | Nov 28, 2022 |
| Quanta        | TW9/SW9                     | [ba75780c3e](https://linux-hardware.org/?probe=ba75780c3e) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| HP            | Laptop 15-bs0xx             | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Dell          | Latitude 3350               | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [afd2f21c66](https://linux-hardware.org/?probe=afd2f21c66) | Oct 26, 2022 |
| Acer          | Aspire ES1-111M             | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Dell          | Latitude E5500              | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Dell          | Inspiron 13-7378            | [fbd3c71f34](https://linux-hardware.org/?probe=fbd3c71f34) | Oct 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6a85eb0ff4](https://linux-hardware.org/?probe=6a85eb0ff4) | Oct 14, 2022 |
| Clevo         | W25xHPx                     | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| Irbis         | NB121                       | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Toshiba       | Satellite C75D-B            | [7ba818df9e](https://linux-hardware.org/?probe=7ba818df9e) | Oct 11, 2022 |
| Alienware     | m15 R7                      | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Lenovo        | LEGIONC7 82EH               | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | [5b3df02ed5](https://linux-hardware.org/?probe=5b3df02ed5) | Oct 03, 2022 |
| HP            | Unknown                     | [0a6433c4fe](https://linux-hardware.org/?probe=0a6433c4fe) | Oct 03, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | [70451644fc](https://linux-hardware.org/?probe=70451644fc) | Oct 03, 2022 |
| BANGHO        | GAMER GM-X 15s              | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| HP            | Presario CQ58               | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| MSI           | Katana GF66 12UD            | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| HUAWEI        | BOHB-WAX9                   | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Toshiba       | Satellite C855D             | [bae94a45be](https://linux-hardware.org/?probe=bae94a45be) | Sep 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410            | [315af016c7](https://linux-hardware.org/?probe=315af016c7) | Sep 09, 2022 |
| Dell          | Latitude E6400              | [1de889aa64](https://linux-hardware.org/?probe=1de889aa64) | Sep 05, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| Acer          | Predator PT516-51s          | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Acer          | Aspire A517-52              | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Panasonic     | CF-31JBGNNDM                | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| Dell          | Inspiron 13-7359            | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| HP            | EliteBook 850 G6            | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Dell          | Latitude E6420              | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| HP            | 250 G2                      | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Acer          | Nitro AN515-57              | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| HP            | Laptop 15-dy2xxx            | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| Unknown       | Unknown                     | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell          | Inspiron MM061              | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo        | ThinkPad L430 2465C32       | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Acer          | Predator PT516-51s          | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| HP            | Pavilion dv6                | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| HP            | ProBook 440 G5              | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Dell          | Latitude E6410              | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | GE62 6QE                    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| Lenovo        | V330-15IKB 81AX             | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| MSI           | Modern 15 A5M               | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ASUSTek       | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Toshiba       | Satellite L775D             | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | X75VC                       | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple         | MacBookPro11,4              | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| Dell          | Latitude XT2                | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Jumper        | EZbook                      | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Samsung       | 550P5C/550P7C               | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Toshiba       | Satellite C75D-B            | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Dell          | Inspiron N5110              | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Dell          | Latitude 7480               | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| HP            | EliteBook 8470p             | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo        | IdeaPad Y580                | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Toshiba       | Satellite L655              | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| HP            | EliteBook 840 G3            | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| HP            | Pavilion dv6700             | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| HP            | Pavilion dv7                | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ASUSTek       | G74Sx                       | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| Dell          | Latitude E7440              | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| MSI           | GE73 Raider RGB 8RE         | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Apple         | MacBookPro11,1              | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| HP            | HDX PREMIUM SERIES          | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| Acer          | Aspire E1-571G              | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Dell          | Inspiron 5420               | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| HP            | ENVY 15                     | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Dell          | Latitude 7390               | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| Acer          | Aspire 5250                 | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | X540YA                      | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| Toshiba       | Satellite L750              | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Alienware     | 17 R4                       | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Dell          | Latitude 3400               | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Dell          | G7 7790                     | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Google        | Celes                       | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| Dell          | Inspiron MM061              | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| ASUSTek       | N56VZ                       | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| ASUSTek       | X442URR                     | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | Latitude E6420              | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| Dell          | Latitude E6420              | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Dell          | XPS 12-9Q33                 | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| Acer          | Aspire 5250                 | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | Inspiron 5721               | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| HP            | Laptop 17-by0xxx            | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Notebook      | W510TU                      | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| HUAWEI        | WRT-WX9                     | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| Apple         | MacBookAir7,2               | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Parrot/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Parrot 5.3   | 82        | 18.59%  |
| Parrot 5.0   | 82        | 18.59%  |
| Parrot 4.11  | 70        | 15.87%  |
| Parrot 5.1   | 52        | 11.79%  |
| Parrot 4.10  | 45        | 10.2%   |
| Parrot 6.0   | 38        | 8.62%   |
| Parrot 5.2   | 26        | 5.9%    |
| Parrot 4.8   | 15        | 3.4%    |
| Parrot 4.9   | 13        | 2.95%   |
| Parrot 4.7   | 10        | 2.27%   |
| Parrot 6.1   | 2         | 0.45%   |
| Parrot 4.6   | 2         | 0.45%   |
| Parrot 4.5   | 1         | 0.23%   |
| Parrot 4.4   | 1         | 0.23%   |
| Parrot 4.2.2 | 1         | 0.23%   |
| Parrot 3.10  | 1         | 0.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Parrot | 418       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 6.1.0-1parrot1-amd64      | 82        | 18.39%  |
| 5.14.0-9parrot1-amd64     | 37        | 8.3%    |
| 5.16.0-12parrot1-amd64    | 35        | 7.85%   |
| 6.0.0-12parrot1-amd64     | 33        | 7.4%    |
| 6.5.0-13parrot1-amd64     | 32        | 7.17%   |
| 5.18.0-14parrot1-amd64    | 28        | 6.28%   |
| 5.7.0-2parrot2-amd64      | 26        | 5.83%   |
| 5.10.0-6parrot1-amd64     | 26        | 5.83%   |
| 6.0.0-2parrot1-amd64      | 22        | 4.93%   |
| 5.18.0-1parrot1-amd64     | 14        | 3.14%   |
| 5.10.0-8parrot1-amd64     | 14        | 3.14%   |
| 5.5.0-1parrot1-amd64      | 12        | 2.69%   |
| 5.4.0-4parrot1-amd64      | 11        | 2.47%   |
| 5.6.0-2parrot1-amd64      | 9         | 2.02%   |
| 5.14.0-2parrot1-amd64     | 9         | 2.02%   |
| 5.9.0-2parrot1-amd64      | 7         | 1.57%   |
| 6.5.0-3parrot1-amd64      | 5         | 1.12%   |
| 5.15.0-15parrot1-amd64    | 5         | 1.12%   |
| 5.8.0-2parrot1-amd64      | 3         | 0.67%   |
| 5.4.0-2parrot1-amd64      | 3         | 0.67%   |
| 5.2.0-2parrot1-amd64      | 3         | 0.67%   |
| 5.10.0-5parrot1-amd64     | 3         | 0.67%   |
| 5.10.0-3parrot1-amd64     | 3         | 0.67%   |
| 4.19.0-parrot4-28t-amd64  | 3         | 0.67%   |
| 5.8.0-1parrot1-amd64      | 2         | 0.45%   |
| 5.4.0-3parrot1-amd64      | 2         | 0.45%   |
| 4.18.0-parrot10-amd64     | 2         | 0.45%   |
| 6.1.27chrultrabook-fixups | 1         | 0.22%   |
| 6.1.0-0.deb11.5-amd64     | 1         | 0.22%   |
| 5.7.0-rc6-galliumos       | 1         | 0.22%   |
| 5.4.0-2parrot1-686-pae    | 1         | 0.22%   |
| 5.4.0-1parrot1-amd64      | 1         | 0.22%   |
| 5.3.0-3parrot3-amd64      | 1         | 0.22%   |
| 5.3.0-3parrot3-686-pae    | 1         | 0.22%   |
| 5.3.0-1parrot1-amd64      | 1         | 0.22%   |
| 5.15.0-5parrot1-amd64     | 1         | 0.22%   |
| 5.10.0-kali6-amd64        | 1         | 0.22%   |
| 5.10.0-6parrot1-rt-amd64  | 1         | 0.22%   |
| 5.1.0-parrot1-3t-amd64    | 1         | 0.22%   |
| 4.19.0-parrot1-13t-amd64  | 1         | 0.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 83        | 18.69%  |
| 6.0.0   | 55        | 12.39%  |
| 5.10.0  | 48        | 10.81%  |
| 5.14.0  | 45        | 10.14%  |
| 5.18.0  | 41        | 9.23%   |
| 6.5.0   | 37        | 8.33%   |
| 5.16.0  | 35        | 7.88%   |
| 5.7.0   | 27        | 6.08%   |
| 5.4.0   | 18        | 4.05%   |
| 5.5.0   | 12        | 2.7%    |
| 5.6.0   | 9         | 2.03%   |
| 5.9.0   | 7         | 1.58%   |
| 5.15.0  | 6         | 1.35%   |
| 5.8.0   | 5         | 1.13%   |
| 4.19.0  | 4         | 0.9%    |
| 5.3.0   | 3         | 0.68%   |
| 5.2.0   | 3         | 0.68%   |
| 4.18.0  | 2         | 0.45%   |
| 6.1.27  | 1         | 0.23%   |
| 5.1.0   | 1         | 0.23%   |
| 4.14.0  | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 84        | 18.92%  |
| 6.0     | 55        | 12.39%  |
| 5.10    | 48        | 10.81%  |
| 5.14    | 45        | 10.14%  |
| 5.18    | 41        | 9.23%   |
| 6.5     | 37        | 8.33%   |
| 5.16    | 35        | 7.88%   |
| 5.7     | 27        | 6.08%   |
| 5.4     | 18        | 4.05%   |
| 5.5     | 12        | 2.7%    |
| 5.6     | 9         | 2.03%   |
| 5.9     | 7         | 1.58%   |
| 5.15    | 6         | 1.35%   |
| 5.8     | 5         | 1.13%   |
| 4.19    | 4         | 0.9%    |
| 5.3     | 3         | 0.68%   |
| 5.2     | 3         | 0.68%   |
| 4.18    | 2         | 0.45%   |
| 5.1     | 1         | 0.23%   |
| 4.14    | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 417       | 99.76%  |
| i686   | 1         | 0.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| MATE          | 317       | 74.41%  |
| KDE5          | 65        | 15.26%  |
| Unknown       | 18        | 4.23%   |
| KDE           | 13        | 3.05%   |
| XFCE          | 8         | 1.88%   |
| X-Cinnamon    | 3         | 0.7%    |
| LXDE          | 1         | 0.23%   |
| GNOME Classic | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 411       | 98.33%  |
| Wayland | 4         | 0.96%   |
| Tty     | 2         | 0.48%   |
| Unknown | 1         | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 230       | 53.86%  |
| Unknown | 132       | 30.91%  |
| TDM     | 50        | 11.71%  |
| SDDM    | 10        | 2.34%   |
| GDM     | 5         | 1.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 231       | 55%     |
| en_GB   | 32        | 7.62%   |
| fr_FR   | 19        | 4.52%   |
| Unknown | 14        | 3.33%   |
| de_DE   | 12        | 2.86%   |
| ru_RU   | 11        | 2.62%   |
| es_ES   | 11        | 2.62%   |
| en_IN   | 10        | 2.38%   |
| pt_BR   | 9         | 2.14%   |
| pl_PL   | 9         | 2.14%   |
| it_IT   | 9         | 2.14%   |
| en_AU   | 8         | 1.9%    |
| en_CA   | 6         | 1.43%   |
| es_MX   | 4         | 0.95%   |
| tr_TR   | 3         | 0.71%   |
| es_CO   | 3         | 0.71%   |
| es_AR   | 3         | 0.71%   |
| es_PE   | 2         | 0.48%   |
| en_IE   | 2         | 0.48%   |
| cs_CZ   | 2         | 0.48%   |
| sk_SK   | 1         | 0.24%   |
| pt_PT   | 1         | 0.24%   |
| nl_NL   | 1         | 0.24%   |
| nl_BE   | 1         | 0.24%   |
| nb_NO   | 1         | 0.24%   |
| lt_LT   | 1         | 0.24%   |
| id_ID   | 1         | 0.24%   |
| fr_CH   | 1         | 0.24%   |
| fr_CA   | 1         | 0.24%   |
| fi_FI   | 1         | 0.24%   |
| es_CL   | 1         | 0.24%   |
| en_ZW   | 1         | 0.24%   |
| en_ZM   | 1         | 0.24%   |
| en_ZA   | 1         | 0.24%   |
| en_NZ   | 1         | 0.24%   |
| en_NG   | 1         | 0.24%   |
| en_DK   | 1         | 0.24%   |
| de_CH   | 1         | 0.24%   |
| C       | 1         | 0.24%   |
| arn_CL  | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 227       | 53.41%  |
| EFI  | 198       | 46.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 323       | 76.36%  |
| Ext4    | 54        | 12.77%  |
| Overlay | 17        | 4.02%   |
| Tmpfs   | 12        | 2.84%   |
| Xfs     | 10        | 2.36%   |
| Unknown | 7         | 1.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 206       | 48.36%  |
| Unknown | 147       | 34.51%  |
| MBR     | 73        | 17.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 369       | 87.44%  |
| Yes       | 53        | 12.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 275       | 65.17%  |
| Yes       | 147       | 34.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 93        | 22.25%  |
| Hewlett-Packard       | 77        | 18.42%  |
| Dell                  | 62        | 14.83%  |
| ASUSTek Computer      | 43        | 10.29%  |
| Acer                  | 32        | 7.66%   |
| MSI                   | 21        | 5.02%   |
| Apple                 | 15        | 3.59%   |
| Toshiba               | 12        | 2.87%   |
| Samsung Electronics   | 8         | 1.91%   |
| HUAWEI                | 5         | 1.2%    |
| Google                | 4         | 0.96%   |
| Alienware             | 4         | 0.96%   |
| Unknown               | 4         | 0.96%   |
| Sony                  | 3         | 0.72%   |
| Razer                 | 3         | 0.72%   |
| Fujitsu               | 3         | 0.72%   |
| Quanta                | 2         | 0.48%   |
| Notebook              | 2         | 0.48%   |
| Gateway               | 2         | 0.48%   |
| Wortmann AG           | 1         | 0.24%   |
| Toxic                 | 1         | 0.24%   |
| Timi                  | 1         | 0.24%   |
| System76              | 1         | 0.24%   |
| Standard              | 1         | 0.24%   |
| Positivo Bahia - VAIO | 1         | 0.24%   |
| Positivo              | 1         | 0.24%   |
| Panasonic             | 1         | 0.24%   |
| Onda TLC              | 1         | 0.24%   |
| Metabox               | 1         | 0.24%   |
| Jumper                | 1         | 0.24%   |
| Irbis                 | 1         | 0.24%   |
| Intel Client Systems  | 1         | 0.24%   |
| HONOR                 | 1         | 0.24%   |
| GPU Company           | 1         | 0.24%   |
| Gigabyte Technology   | 1         | 0.24%   |
| eMachines             | 1         | 0.24%   |
| Eluktronics           | 1         | 0.24%   |
| Digma                 | 1         | 0.24%   |
| Clevo                 | 1         | 0.24%   |
| Chuwi                 | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 6         | 1.44%   |
| HP Notebook                      | 4         | 0.96%   |
| HP Laptop 15-dy2xxx              | 4         | 0.96%   |
| MSI Modern 15 A5M                | 3         | 0.72%   |
| Lenovo IdeaPad 3 15IIL05 81WE    | 3         | 0.72%   |
| HP Pavilion 15                   | 3         | 0.72%   |
| HP EliteBook 8470p               | 3         | 0.72%   |
| Dell Latitude E6420              | 3         | 0.72%   |
| Dell Inspiron MM061              | 3         | 0.72%   |
| Apple MacBookAir7,2              | 3         | 0.72%   |
| Toshiba Satellite L775D          | 2         | 0.48%   |
| Quanta TW9/SW9                   | 2         | 0.48%   |
| MSI Katana GF66 12UC             | 2         | 0.48%   |
| Lenovo E41-25 81FS               | 2         | 0.48%   |
| HP ProBook 650 G1                | 2         | 0.48%   |
| HP Pavilion g6                   | 2         | 0.48%   |
| HP Pavilion dv6                  | 2         | 0.48%   |
| HP Pavilion dv4                  | 2         | 0.48%   |
| Dell XPS 13 9350                 | 2         | 0.48%   |
| Dell Latitude E7440              | 2         | 0.48%   |
| Dell Latitude E6410              | 2         | 0.48%   |
| Dell Latitude 7280               | 2         | 0.48%   |
| Dell Inspiron N5110              | 2         | 0.48%   |
| ASUS ROG Strix G513QR_G513QR     | 2         | 0.48%   |
| ASUS Q524UQ                      | 2         | 0.48%   |
| Apple MacBookPro8,1              | 2         | 0.48%   |
| Apple MacBookPro11,1             | 2         | 0.48%   |
| Acer Nitro AN515-57              | 2         | 0.48%   |
| Acer Nitro AN515-54              | 2         | 0.48%   |
| Acer Extensa 215-54              | 2         | 0.48%   |
| Acer Aspire ES1-111M             | 2         | 0.48%   |
| Wortmann AG TERRA_MOBILE_1542    | 1         | 0.24%   |
| Toxic GM7MQ8P                    | 1         | 0.24%   |
| Toshiba Satellite-L845           | 1         | 0.24%   |
| Toshiba Satellite L750           | 1         | 0.24%   |
| Toshiba Satellite L655           | 1         | 0.24%   |
| Toshiba Satellite L50-A-1DL      | 1         | 0.24%   |
| Toshiba Satellite L300D          | 1         | 0.24%   |
| Toshiba Satellite E55-A          | 1         | 0.24%   |
| Toshiba Satellite Click 2 L35W-B | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 49        | 11.72%  |
| Dell Latitude      | 27        | 6.46%   |
| Lenovo IdeaPad     | 24        | 5.74%   |
| Dell Inspiron      | 19        | 4.55%   |
| HP Pavilion        | 18        | 4.31%   |
| HP Laptop          | 15        | 3.59%   |
| Acer Aspire        | 15        | 3.59%   |
| HP EliteBook       | 14        | 3.35%   |
| Toshiba Satellite  | 10        | 2.39%   |
| HP ProBook         | 9         | 2.15%   |
| Acer Nitro         | 7         | 1.67%   |
| MSI Katana         | 6         | 1.44%   |
| Dell XPS           | 6         | 1.44%   |
| ASUS VivoBook      | 6         | 1.44%   |
| ASUS ROG           | 6         | 1.44%   |
| ASUS ASUS          | 6         | 1.44%   |
| Unknown            | 6         | 1.44%   |
| Lenovo Legion      | 5         | 1.2%    |
| HP ZBook           | 4         | 0.96%   |
| HP Notebook        | 4         | 0.96%   |
| Dell Precision     | 4         | 0.96%   |
| ASUS Zenbook       | 4         | 0.96%   |
| Razer Blade        | 3         | 0.72%   |
| MSI Modern         | 3         | 0.72%   |
| HP Victus          | 3         | 0.72%   |
| Fujitsu LIFEBOOK   | 3         | 0.72%   |
| Dell Vostro        | 3         | 0.72%   |
| Apple MacBookPro11 | 3         | 0.72%   |
| Apple MacBookAir7  | 3         | 0.72%   |
| Acer Swift         | 3         | 0.72%   |
| Acer Extensa       | 3         | 0.72%   |
| Quanta TW9         | 2         | 0.48%   |
| MSI GT60           | 2         | 0.48%   |
| Lenovo E41-25      | 2         | 0.48%   |
| HP ENVY            | 2         | 0.48%   |
| HP 250             | 2         | 0.48%   |
| ASUS TUF           | 2         | 0.48%   |
| ASUS Q524UQ        | 2         | 0.48%   |
| Apple MacBookPro8  | 2         | 0.48%   |
| Alienware m15      | 2         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 50        | 11.96%  |
| 2021 | 48        | 11.48%  |
| 2020 | 40        | 9.57%   |
| 2011 | 39        | 9.33%   |
| 2022 | 31        | 7.42%   |
| 2012 | 30        | 7.18%   |
| 2018 | 29        | 6.94%   |
| 2016 | 26        | 6.22%   |
| 2013 | 26        | 6.22%   |
| 2017 | 20        | 4.78%   |
| 2014 | 20        | 4.78%   |
| 2015 | 12        | 2.87%   |
| 2008 | 12        | 2.87%   |
| 2023 | 11        | 2.63%   |
| 2010 | 11        | 2.63%   |
| 2007 | 6         | 1.44%   |
| 2006 | 4         | 0.96%   |
| 2009 | 3         | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 418       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 418       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 414       | 99.04%  |
| Yes  | 4         | 0.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 124       | 29.52%  |
| 8.01-16.0   | 89        | 21.19%  |
| 16.01-24.0  | 87        | 20.71%  |
| 3.01-4.0    | 68        | 16.19%  |
| 32.01-64.0  | 28        | 6.67%   |
| 1.01-2.0    | 9         | 2.14%   |
| 24.01-32.0  | 6         | 1.43%   |
| 64.01-256.0 | 6         | 1.43%   |
| 2.01-3.0    | 3         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 151       | 33.93%  |
| 2.01-3.0   | 142       | 31.91%  |
| 3.01-4.0   | 65        | 14.61%  |
| 4.01-8.0   | 62        | 13.93%  |
| 0.51-1.0   | 16        | 3.6%    |
| 8.01-16.0  | 7         | 1.57%   |
| 16.01-24.0 | 1         | 0.22%   |
| 0.01-0.5   | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 301       | 70.82%  |
| 2      | 113       | 26.59%  |
| 3      | 10        | 2.35%   |
| 0      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 304       | 72.55%  |
| Yes       | 115       | 27.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 333       | 79.29%  |
| No        | 87        | 20.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 414       | 99.04%  |
| No        | 4         | 0.96%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 343       | 81.09%  |
| No        | 80        | 18.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 123       | 29.15%  |
| Germany      | 23        | 5.45%   |
| France       | 20        | 4.74%   |
| UK           | 17        | 4.03%   |
| Spain        | 14        | 3.32%   |
| Russia       | 14        | 3.32%   |
| Italy        | 14        | 3.32%   |
| Netherlands  | 13        | 3.08%   |
| India        | 13        | 3.08%   |
| Brazil       | 12        | 2.84%   |
| Canada       | 11        | 2.61%   |
| Kenya        | 8         | 1.9%    |
| Australia    | 8         | 1.9%    |
| Sweden       | 7         | 1.66%   |
| Mexico       | 6         | 1.42%   |
| Indonesia    | 6         | 1.42%   |
| Poland       | 5         | 1.18%   |
| Czechia      | 5         | 1.18%   |
| Turkey       | 4         | 0.95%   |
| Switzerland  | 4         | 0.95%   |
| Denmark      | 4         | 0.95%   |
| UAE          | 3         | 0.71%   |
| South Africa | 3         | 0.71%   |
| Portugal     | 3         | 0.71%   |
| Peru         | 3         | 0.71%   |
| Nepal        | 3         | 0.71%   |
| Iraq         | 3         | 0.71%   |
| Finland      | 3         | 0.71%   |
| Egypt        | 3         | 0.71%   |
| Colombia     | 3         | 0.71%   |
| Bangladesh   | 3         | 0.71%   |
| Argentina    | 3         | 0.71%   |
| Algeria      | 3         | 0.71%   |
| Slovakia     | 2         | 0.47%   |
| Puerto Rico  | 2         | 0.47%   |
| Pakistan     | 2         | 0.47%   |
| Norway       | 2         | 0.47%   |
| Namibia      | 2         | 0.47%   |
| Myanmar      | 2         | 0.47%   |
| Mongolia     | 2         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Nairobi           | 7         | 1.58%   |
| Amsterdam         | 7         | 1.58%   |
| Seattle           | 5         | 1.13%   |
| Moscow            | 5         | 1.13%   |
| Houston           | 5         | 1.13%   |
| Dallas            | 5         | 1.13%   |
| Saint Paul        | 4         | 0.9%    |
| Rome              | 4         | 0.9%    |
| Paris             | 4         | 0.9%    |
| Melbourne         | 4         | 0.9%    |
| London            | 4         | 0.9%    |
| Dublin            | 4         | 0.9%    |
| Toronto           | 3         | 0.68%   |
| Sydney            | 3         | 0.68%   |
| Stockholm         | 3         | 0.68%   |
| Prague            | 3         | 0.68%   |
| Lyon              | 3         | 0.68%   |
| Los Angeles       | 3         | 0.68%   |
| Frankfurt am Main | 3         | 0.68%   |
| Dhaka             | 3         | 0.68%   |
| Chicago           | 3         | 0.68%   |
| Berlin            | 3         | 0.68%   |
| Barcelona         | 3         | 0.68%   |
| Zurich            | 2         | 0.45%   |
| Warsaw            | 2         | 0.45%   |
| Visalia           | 2         | 0.45%   |
| Ulan Bator        | 2         | 0.45%   |
| St Petersburg     | 2         | 0.45%   |
| San Juan          | 2         | 0.45%   |
| San José         | 2         | 0.45%   |
| San Antonio       | 2         | 0.45%   |
| Ruskin            | 2         | 0.45%   |
| Rho               | 2         | 0.45%   |
| Reading           | 2         | 0.45%   |
| Pretoria          | 2         | 0.45%   |
| Oslo              | 2         | 0.45%   |
| New York          | 2         | 0.45%   |
| Munich            | 2         | 0.45%   |
| Mostoles          | 2         | 0.45%   |
| Minneapolis       | 2         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 86        | 110    | 16.32%  |
| WDC                         | 61        | 73     | 11.57%  |
| Toshiba                     | 55        | 62     | 10.44%  |
| Unknown                     | 38        | 41     | 7.21%   |
| Seagate                     | 35        | 36     | 6.64%   |
| Kingston                    | 30        | 30     | 5.69%   |
| SanDisk                     | 26        | 31     | 4.93%   |
| SK hynix                    | 22        | 26     | 4.17%   |
| Micron Technology           | 22        | 22     | 4.17%   |
| Crucial                     | 16        | 21     | 3.04%   |
| Hitachi                     | 14        | 16     | 2.66%   |
| HGST                        | 13        | 16     | 2.47%   |
| Intel                       | 12        | 19     | 2.28%   |
| A-DATA Technology           | 10        | 10     | 1.9%    |
| Apple                       | 9         | 9      | 1.71%   |
| KIOXIA                      | 7         | 8      | 1.33%   |
| China                       | 7         | 7      | 1.33%   |
| Team                        | 5         | 6      | 0.95%   |
| LITEON                      | 4         | 4      | 0.76%   |
| YMTC                        | 3         | 3      | 0.57%   |
| KingFast                    | 3         | 4      | 0.57%   |
| Unknown                     | 3         | 3      | 0.57%   |
| PNY                         | 2         | 2      | 0.38%   |
| Phison                      | 2         | 2      | 0.38%   |
| Lexar                       | 2         | 2      | 0.38%   |
| Kingston Technology Company | 2         | 3      | 0.38%   |
| HUAWEI                      | 2         | 2      | 0.38%   |
| Corsair                     | 2         | 3      | 0.38%   |
| BR                          | 2         | 2      | 0.38%   |
| Zheino                      | 1         | 1      | 0.19%   |
| Wdxsky                      | 1         | 1      | 0.19%   |
| W800SH                      | 1         | 1      | 0.19%   |
| Unknown (583)               | 1         | 1      | 0.19%   |
| TSA 256G                    | 1         | 1      | 0.19%   |
| Transcend                   | 1         | 1      | 0.19%   |
| TO Exter                    | 1         | 1      | 0.19%   |
| Teclast                     | 1         | 1      | 0.19%   |
| SSSTC                       | 1         | 1      | 0.19%   |
| SPCC                        | 1         | 1      | 0.19%   |
| Silicon Motion              | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                            | 10        | 1.8%    |
| Toshiba MQ01ABF050 500GB                          | 8         | 1.44%   |
| Toshiba MQ01ABD100 1TB                            | 7         | 1.26%   |
| Unknown MMC Card  64GB                            | 5         | 0.9%    |
| Unknown MMC Card  32GB                            | 5         | 0.9%    |
| Toshiba MQ01ABD075 752GB                          | 5         | 0.9%    |
| Samsung SSD 860 EVO 500GB                         | 5         | 0.9%    |
| Kingston SA400S37240G 240GB SSD                   | 5         | 0.9%    |
| Kingston NVMe SSD Drive 512GB                     | 5         | 0.9%    |
| Unknown SD/MMC/MS PRO 128GB                       | 4         | 0.72%   |
| Seagate ST1000LM035-1RK172 1TB                    | 4         | 0.72%   |
| SanDisk NVMe SSD Drive 1TB                        | 4         | 0.72%   |
| HGST HTS721010A9E630 1TB                          | 4         | 0.72%   |
| HGST HTS541010A9E680 1TB                          | 4         | 0.72%   |
| WDC WD10SPZX-75Z10T2 1TB                          | 3         | 0.54%   |
| Toshiba KXG6AZNV256G 256GB                        | 3         | 0.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 3         | 0.54%   |
| Seagate ST320LT007-9ZV142 320GB                   | 3         | 0.54%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 3         | 0.54%   |
| SanDisk SSD PLUS 1000GB                           | 3         | 0.54%   |
| SanDisk NVMe SSD Drive 256GB                      | 3         | 0.54%   |
| Samsung SSD 980 1TB                               | 3         | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB                      | 3         | 0.54%   |
| Samsung SSD 850 EVO 250GB                         | 3         | 0.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 0.54%   |
| Micron 2400_MTFDKBA512QFM 512GB                   | 3         | 0.54%   |
| Kingston OM8PCP3512F-AB 512GB                     | 3         | 0.54%   |
| Intel SSDPEKNU512GZ 512GB                         | 3         | 0.54%   |
| Crucial CT500MX500SSD1 500GB                      | 3         | 0.54%   |
| Apple SSD SM0128G 121GB                           | 3         | 0.54%   |
| Unknown                                           | 3         | 0.54%   |
| YMTC PC005 256GB                                  | 2         | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 2         | 0.36%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 2         | 0.36%   |
| WDC WD5000LPCX-24C6HT0 500GB                      | 2         | 0.36%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 2         | 0.36%   |
| WDC WD10SPZX-24Z10 1TB                            | 2         | 0.36%   |
| WDC WD10SPZX-08Z10 1TB                            | 2         | 0.36%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                | 2         | 0.36%   |
| Unknown MMC Card  128GB                           | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 41        | 46     | 26.62%  |
| WDC                 | 40        | 46     | 25.97%  |
| Seagate             | 34        | 35     | 22.08%  |
| Hitachi             | 14        | 16     | 9.09%   |
| HGST                | 13        | 16     | 8.44%   |
| Samsung Electronics | 5         | 5      | 3.25%   |
| Unknown             | 4         | 5      | 2.6%    |
| TO Exter            | 1         | 1      | 0.65%   |
| Fujitsu             | 1         | 1      | 0.65%   |
| ASMedia             | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 33     | 16.56%  |
| Kingston            | 15        | 15     | 9.93%   |
| SanDisk             | 14        | 15     | 9.27%   |
| Crucial             | 13        | 18     | 8.61%   |
| WDC                 | 9         | 11     | 5.96%   |
| Apple               | 8         | 8      | 5.3%    |
| China               | 7         | 7      | 4.64%   |
| Toshiba             | 5         | 6      | 3.31%   |
| Micron Technology   | 4         | 4      | 2.65%   |
| LITEON              | 4         | 4      | 2.65%   |
| Team                | 3         | 4      | 1.99%   |
| SK hynix            | 3         | 3      | 1.99%   |
| KingFast            | 3         | 3      | 1.99%   |
| A-DATA Technology   | 3         | 3      | 1.99%   |
| PNY                 | 2         | 2      | 1.32%   |
| Intel               | 2         | 2      | 1.32%   |
| BR                  | 2         | 2      | 1.32%   |
| Unknown             | 2         | 2      | 1.32%   |
| Zheino              | 1         | 1      | 0.66%   |
| Wdxsky              | 1         | 1      | 0.66%   |
| W800SH              | 1         | 1      | 0.66%   |
| Unknown             | 1         | 1      | 0.66%   |
| TSA 256G            | 1         | 1      | 0.66%   |
| Transcend           | 1         | 1      | 0.66%   |
| Teclast             | 1         | 1      | 0.66%   |
| Seagate             | 1         | 1      | 0.66%   |
| SCY                 | 1         | 1      | 0.66%   |
| S3+                 | 1         | 1      | 0.66%   |
| RZX                 | 1         | 1      | 0.66%   |
| Patriot             | 1         | 1      | 0.66%   |
| Netac               | 1         | 1      | 0.66%   |
| LITEONIT            | 1         | 1      | 0.66%   |
| Lexar               | 1         | 1      | 0.66%   |
| KingSpec            | 1         | 2      | 0.66%   |
| Kingmax             | 1         | 1      | 0.66%   |
| Intenso             | 1         | 2      | 0.66%   |
| HS-SSD-C100         | 1         | 1      | 0.66%   |
| Hewlett-Packard     | 1         | 1      | 0.66%   |
| GOODRAM             | 1         | 1      | 0.66%   |
| Gigabyte Technology | 1         | 1      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 174       | 223    | 34.8%   |
| HDD     | 150       | 172    | 30%     |
| SSD     | 140       | 173    | 28%     |
| MMC     | 31        | 35     | 6.2%    |
| Unknown | 5         | 5      | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 260       | 329    | 53.5%   |
| NVMe | 174       | 222    | 35.8%   |
| MMC  | 31        | 35     | 6.38%   |
| SAS  | 21        | 22     | 4.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 187       | 230    | 65.16%  |
| 0.51-1.0   | 90        | 104    | 31.36%  |
| 1.01-2.0   | 8         | 9      | 2.79%   |
| 3.01-4.0   | 2         | 2      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 105       | 24.65%  |
| 101-250        | 89        | 20.89%  |
| 501-1000       | 79        | 18.54%  |
| Unknown        | 43        | 10.09%  |
| 1001-2000      | 41        | 9.62%   |
| 51-100         | 27        | 6.34%   |
| 21-50          | 17        | 3.99%   |
| 1-20           | 14        | 3.29%   |
| More than 3000 | 7         | 1.64%   |
| 2001-3000      | 4         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 139       | 31.88%  |
| 51-100         | 86        | 19.72%  |
| 1-20           | 64        | 14.68%  |
| 101-250        | 50        | 11.47%  |
| Unknown        | 43        | 9.86%   |
| 251-500        | 35        | 8.03%   |
| 501-1000       | 11        | 2.52%   |
| 1001-2000      | 4         | 0.92%   |
| 0              | 2         | 0.46%   |
| More than 3000 | 1         | 0.23%   |
| 2001-3000      | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 4.88%   |
| Samsung Electronics HM500JI 500GB                   | 2         | 2      | 4.88%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 2         | 2      | 4.88%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 2.44%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 2.44%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.44%   |
| Toshiba MK6475GSX 640GB                             | 1         | 1      | 2.44%   |
| Toshiba MK5059GSXP 500GB                            | 1         | 1      | 2.44%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 2.44%   |
| Toshiba MK3261GSYN 320GB                            | 1         | 1      | 2.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.44%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 2.44%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.44%   |
| SanDisk SSD U100 24GB                               | 1         | 1      | 2.44%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                 | 1         | 1      | 2.44%   |
| SanDisk SD8SBAT256G1122 256GB SSD                   | 1         | 1      | 2.44%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 2.44%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 2.44%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.44%   |
| Kingston SUV400S37480G 480GB SSD                    | 1         | 1      | 2.44%   |
| Intel HBRPEKNX0202AHO 32GB                          | 1         | 1      | 2.44%   |
| Hitachi HTS725050A9A364 500GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS723216L9SA60 160GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 2.44%   |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 2.44%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.44%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.44%   |
| Hewlett-Packard SSD S700 Pro 1TB                    | 1         | 1      | 2.44%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 2.44%   |
| Crucial CT525MX300SSD1 528GB                        | 1         | 1      | 2.44%   |
| China SSD 120GB                                     | 1         | 1      | 2.44%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 2.44%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 2.44%   |
| Unknown                                             | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 17.07%  |
| Hitachi             | 5         | 5      | 12.2%   |
| Seagate             | 4         | 4      | 9.76%   |
| Samsung Electronics | 4         | 4      | 9.76%   |
| WDC                 | 3         | 3      | 7.32%   |
| SanDisk             | 3         | 3      | 7.32%   |
| HGST                | 3         | 3      | 7.32%   |
| LITEON              | 2         | 2      | 4.88%   |
| A-DATA Technology   | 2         | 2      | 4.88%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| Kingston            | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| Hewlett-Packard     | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 1      | 2.44%   |
| Crucial             | 1         | 1      | 2.44%   |
| China               | 1         | 1      | 2.44%   |
| Unknown             | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 26.92%  |
| Hitachi             | 5         | 5      | 19.23%  |
| Seagate             | 4         | 4      | 15.38%  |
| WDC                 | 3         | 3      | 11.54%  |
| Samsung Electronics | 3         | 3      | 11.54%  |
| HGST                | 3         | 3      | 11.54%  |
| Fujitsu             | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 26     | 63.41%  |
| SSD  | 13        | 13     | 31.71%  |
| NVMe | 2         | 2      | 4.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba MK2565GSXN 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 228       | 289    | 49.57%  |
| Detected | 191       | 277    | 41.52%  |
| Malfunc  | 40        | 41     | 8.7%    |
| Failed   | 1         | 1      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 286       | 55.53%  |
| Samsung Electronics            | 63        | 12.23%  |
| AMD                            | 41        | 7.96%   |
| SanDisk                        | 26        | 5.05%   |
| SK hynix                       | 19        | 3.69%   |
| Micron Technology              | 18        | 3.5%    |
| Kingston Technology Company    | 17        | 3.3%    |
| Toshiba America Info Systems   | 9         | 1.75%   |
| KIOXIA                         | 7         | 1.36%   |
| ADATA Technology               | 6         | 1.17%   |
| Silicon Motion                 | 4         | 0.78%   |
| Phison Electronics             | 4         | 0.78%   |
| Yangtze Memory Technologies    | 3         | 0.58%   |
| Nvidia                         | 3         | 0.58%   |
| Micron/Crucial Technology      | 3         | 0.58%   |
| Realtek Semiconductor          | 2         | 0.39%   |
| Solidigm                       | 1         | 0.19%   |
| Solid State Storage Technology | 1         | 0.19%   |
| Marvell Technology Group       | 1         | 0.19%   |
| Apple                          | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 40        | 7.16%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 35        | 6.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 28        | 5.01%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 27        | 4.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 26        | 4.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 25        | 4.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 23        | 4.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 14        | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 13        | 2.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 13        | 2.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 12        | 2.15%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 11        | 1.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 11        | 1.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 11        | 1.97%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 10        | 1.79%   |
| Intel Alder Lake-P SATA AHCI Controller                                                | 8         | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 7         | 1.25%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 7         | 1.25%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 7         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 7         | 1.25%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 7         | 1.25%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                            | 6         | 1.07%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                          | 6         | 1.07%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 6         | 1.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 6         | 1.07%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 5         | 0.89%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                             | 5         | 0.89%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 5         | 0.89%   |
| Intel Tiger Lake SATA AHCI Controller                                                  | 5         | 0.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 4         | 0.72%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                   | 4         | 0.72%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 4         | 0.72%   |
| Micron 2210 NVMe SSD [Cobain]                                                          | 4         | 0.72%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 4         | 0.72%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 4         | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 0.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 4         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 265       | 50.48%  |
| NVMe | 174       | 33.14%  |
| RAID | 56        | 10.67%  |
| IDE  | 30        | 5.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 355       | 84.93%  |
| AMD    | 63        | 15.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 2.39%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 2.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 1.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 1.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 1.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 1.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 1.44%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 1.2%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 1.2%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 1.2%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 1.2%    |
| Intel 12th Gen Core i7-12700H                 | 5         | 1.2%    |
| Intel 12th Gen Core i5-1235U                  | 5         | 1.2%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 1.2%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 1.2%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 0.96%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.96%   |
| Intel 12th Gen Core i5-12500H                 | 4         | 0.96%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 4         | 0.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 0.96%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.96%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 0.72%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 3         | 0.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.72%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 3         | 0.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.72%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.72%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.72%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.72%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 3         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 112       | 26.79%  |
| Intel Core i7           | 87        | 20.81%  |
| Other                   | 71        | 16.99%  |
| Intel Core i3           | 35        | 8.37%   |
| Intel Celeron           | 23        | 5.5%    |
| AMD Ryzen 7             | 21        | 5.02%   |
| AMD Ryzen 5             | 13        | 3.11%   |
| Intel Core 2 Duo        | 11        | 2.63%   |
| AMD A6                  | 8         | 1.91%   |
| Intel Pentium           | 4         | 0.96%   |
| Intel Core 2            | 4         | 0.96%   |
| AMD A4                  | 4         | 0.96%   |
| Intel Pentium Silver    | 3         | 0.72%   |
| AMD Ryzen 3             | 3         | 0.72%   |
| AMD E1                  | 3         | 0.72%   |
| Intel Atom              | 2         | 0.48%   |
| AMD E                   | 2         | 0.48%   |
| Intel Pentium Dual-Core | 1         | 0.24%   |
| Intel Genuine           | 1         | 0.24%   |
| Intel Core m5           | 1         | 0.24%   |
| Intel Core i9           | 1         | 0.24%   |
| Intel Core 2 Quad       | 1         | 0.24%   |
| Intel Core 2 Extreme    | 1         | 0.24%   |
| AMD Ryzen 9             | 1         | 0.24%   |
| AMD FX                  | 1         | 0.24%   |
| AMD E2                  | 1         | 0.24%   |
| AMD C-50                | 1         | 0.24%   |
| AMD Athlon X2           | 1         | 0.24%   |
| AMD Athlon              | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 201       | 48.09%  |
| 4      | 119       | 28.47%  |
| 6      | 35        | 8.37%   |
| 8      | 25        | 5.98%   |
| 10     | 14        | 3.35%   |
| 14     | 10        | 2.39%   |
| 12     | 9         | 2.15%   |
| 1      | 4         | 0.96%   |
| 16     | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 418       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 310       | 73.99%  |
| 1      | 108       | 25.78%  |
| 8      | 1         | 0.24%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 413       | 98.8%   |
| Unknown        | 5         | 1.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 190       | 44.29%  |
| 0x206a7    | 23        | 5.36%   |
| 0x906a3    | 18        | 4.2%    |
| 0x306a9    | 17        | 3.96%   |
| 0x806ec    | 16        | 3.73%   |
| 0x806c1    | 13        | 3.03%   |
| 0x406e3    | 13        | 3.03%   |
| 0xa0652    | 10        | 2.33%   |
| 0x906ea    | 9         | 2.1%    |
| 0x806e9    | 9         | 2.1%    |
| 0x906a4    | 8         | 1.86%   |
| 0x806ea    | 7         | 1.63%   |
| 0x706a8    | 7         | 1.63%   |
| 0x806d1    | 6         | 1.4%    |
| 0x706e5    | 5         | 1.17%   |
| 0x40651    | 5         | 1.17%   |
| 0x6f6      | 4         | 0.93%   |
| 0x306d4    | 4         | 0.93%   |
| 0x306c3    | 4         | 0.93%   |
| 0x1067a    | 4         | 0.93%   |
| 0x0a50000c | 4         | 0.93%   |
| 0x08608103 | 4         | 0.93%   |
| 0x08600106 | 4         | 0.93%   |
| 0x06006705 | 4         | 0.93%   |
| 0x08108109 | 3         | 0.7%    |
| 0x07030105 | 3         | 0.7%    |
| 0x03000027 | 3         | 0.7%    |
| 0xb06a2    | 2         | 0.47%   |
| 0x906e9    | 2         | 0.47%   |
| 0x806eb    | 2         | 0.47%   |
| 0x806c2    | 2         | 0.47%   |
| 0x706a1    | 2         | 0.47%   |
| 0x6fd      | 2         | 0.47%   |
| 0x506c9    | 2         | 0.47%   |
| 0x406c4    | 2         | 0.47%   |
| 0x30678    | 2         | 0.47%   |
| 0x08108102 | 2         | 0.47%   |
| 0xb06f2    | 1         | 0.23%   |
| 0xa0660    | 1         | 0.23%   |
| 0x906ed    | 1         | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 78        | 18.66%  |
| SandyBridge      | 38        | 9.09%   |
| IvyBridge        | 32        | 7.66%   |
| Alderlake Hybrid | 30        | 7.18%   |
| Haswell          | 26        | 6.22%   |
| TigerLake        | 25        | 5.98%   |
| Skylake          | 25        | 5.98%   |
| Unknown          | 18        | 4.31%   |
| Broadwell        | 15        | 3.59%   |
| Goldmont plus    | 13        | 3.11%   |
| CometLake        | 13        | 3.11%   |
| Penryn           | 12        | 2.87%   |
| IceLake          | 12        | 2.87%   |
| Zen 3            | 10        | 2.39%   |
| Silvermont       | 10        | 2.39%   |
| Zen+             | 8         | 1.91%   |
| Zen 2            | 8         | 1.91%   |
| Excavator        | 8         | 1.91%   |
| Core             | 8         | 1.91%   |
| Westmere         | 6         | 1.44%   |
| Jaguar           | 4         | 0.96%   |
| Zen              | 3         | 0.72%   |
| Puma             | 3         | 0.72%   |
| K10 Llano        | 3         | 0.72%   |
| Goldmont         | 3         | 0.72%   |
| Bobcat           | 3         | 0.72%   |
| Piledriver       | 2         | 0.48%   |
| Nehalem          | 1         | 0.24%   |
| K8 & K10 hybrid  | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 336       | 60.54%  |
| Nvidia | 131       | 23.6%   |
| AMD    | 88        | 15.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 34        | 6.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 30        | 5.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 3.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 3.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 3.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 3.38%   |
| Intel UHD Graphics 620                                                                   | 17        | 3.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 2.67%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 15        | 2.67%   |
| Intel HD Graphics 5500                                                                   | 12        | 2.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 2.14%   |
| Intel HD Graphics 620                                                                    | 11        | 1.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 1.6%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 1.6%    |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 8         | 1.42%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 8         | 1.42%   |
| AMD Lucienne                                                                             | 8         | 1.42%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 7         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.25%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 1.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 1.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.07%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 6         | 1.07%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.07%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 6         | 1.07%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 1.07%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.07%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.89%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 5         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.89%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.89%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 4         | 0.71%   |
| Intel HD Graphics 630                                                                    | 4         | 0.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 211       | 50.24%  |
| Intel + Nvidia | 106       | 25.24%  |
| 1 x AMD        | 55        | 13.1%   |
| Intel + AMD    | 17        | 4.05%   |
| AMD + Nvidia   | 14        | 3.33%   |
| 1 x Nvidia     | 12        | 2.86%   |
| 2 x AMD        | 2         | 0.48%   |
| Other          | 1         | 0.24%   |
| 2 x Nvidia     | 1         | 0.24%   |
| 2 x Intel      | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 373       | 89.02%  |
| Proprietary | 41        | 9.79%   |
| Unknown     | 5         | 1.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 331       | 78.62%  |
| 0.01-0.5   | 22        | 5.23%   |
| 1.01-2.0   | 20        | 4.75%   |
| 3.01-4.0   | 18        | 4.28%   |
| 0.51-1.0   | 17        | 4.04%   |
| 5.01-6.0   | 7         | 1.66%   |
| 7.01-8.0   | 4         | 0.95%   |
| 2.01-3.0   | 2         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 97        | 20.82%  |
| BOE                     | 78        | 16.74%  |
| LG Display              | 71        | 15.24%  |
| Chimei Innolux          | 66        | 14.16%  |
| Samsung Electronics     | 36        | 7.73%   |
| Apple                   | 16        | 3.43%   |
| Sharp                   | 14        | 3%      |
| Chi Mei Optoelectronics | 12        | 2.58%   |
| PANDA                   | 8         | 1.72%   |
| Dell                    | 8         | 1.72%   |
| Lenovo                  | 4         | 0.86%   |
| InfoVision              | 4         | 0.86%   |
| CSO                     | 4         | 0.86%   |
| Sony                    | 3         | 0.64%   |
| Hewlett-Packard         | 3         | 0.64%   |
| Goldstar                | 3         | 0.64%   |
| Acer                    | 3         | 0.64%   |
| Sceptre Tech            | 2         | 0.43%   |
| Philips                 | 2         | 0.43%   |
| Eizo                    | 2         | 0.43%   |
| BenQ                    | 2         | 0.43%   |
| Ancor Communications    | 2         | 0.43%   |
| Unknown                 | 2         | 0.43%   |
| ___                     | 1         | 0.21%   |
| Vizio                   | 1         | 0.21%   |
| VIZ                     | 1         | 0.21%   |
| ViewSonic               | 1         | 0.21%   |
| Unknown (AAA)           | 1         | 0.21%   |
| Unknown                 | 1         | 0.21%   |
| TMX                     | 1         | 0.21%   |
| STD                     | 1         | 0.21%   |
| STA                     | 1         | 0.21%   |
| SANYO                   | 1         | 0.21%   |
| Planar                  | 1         | 0.21%   |
| Pixio                   | 1         | 0.21%   |
| Panasonic               | 1         | 0.21%   |
| ONN                     | 1         | 0.21%   |
| Olidata                 | 1         | 0.21%   |
| NEC Computers           | 1         | 0.21%   |
| LG Philips              | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 6         | 1.28%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 1.07%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 4         | 0.86%   |
| Sony TV SNYF301 1920x1080                                                | 3         | 0.64%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 3         | 0.64%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 3         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.64%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 3         | 0.64%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 3         | 0.64%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 3         | 0.64%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 3         | 0.64%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.64%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 3         | 0.64%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 3         | 0.64%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                  | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch     | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 2         | 0.43%   |
| LG Display LCD Monitor LGD06E4 1920x1080 344x194mm 15.5-inch             | 2         | 0.43%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch              | 2         | 0.43%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch              | 2         | 0.43%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 2         | 0.43%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 2         | 0.43%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 2         | 0.43%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch             | 2         | 0.43%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 2         | 0.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.43%   |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                    | 2         | 0.43%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 2         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 200       | 44.94%  |
| 1366x768 (WXGA)    | 143       | 32.13%  |
| 1600x900 (HD+)     | 20        | 4.49%   |
| 1280x800 (WXGA)    | 14        | 3.15%   |
| 3840x2160 (4K)     | 11        | 2.47%   |
| 1920x1200 (WUXGA)  | 10        | 2.25%   |
| 1440x900 (WXGA+)   | 9         | 2.02%   |
| 2560x1440 (QHD)    | 7         | 1.57%   |
| 2560x1600          | 6         | 1.35%   |
| 2880x1800          | 4         | 0.9%    |
| 1680x1050 (WSXGA+) | 4         | 0.9%    |
| 1024x768 (XGA)     | 3         | 0.67%   |
| 2160x1440          | 2         | 0.45%   |
| 1920x540           | 2         | 0.45%   |
| 3840x2400          | 1         | 0.22%   |
| 3200x1800 (QHD+)   | 1         | 0.22%   |
| 3200x1080          | 1         | 0.22%   |
| 2944x1080          | 1         | 0.22%   |
| 2560x1080          | 1         | 0.22%   |
| 2240x1400          | 1         | 0.22%   |
| 1920x515           | 1         | 0.22%   |
| 1360x768           | 1         | 0.22%   |
| 1280x1024 (SXGA)   | 1         | 0.22%   |
| Unknown            | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 203       | 43.84%  |
| 13      | 63        | 13.61%  |
| 14      | 62        | 13.39%  |
| 17      | 36        | 7.78%   |
| 12      | 16        | 3.46%   |
| 11      | 12        | 2.59%   |
| 27      | 10        | 2.16%   |
| 24      | 9         | 1.94%   |
| 16      | 7         | 1.51%   |
| 31      | 6         | 1.3%    |
| 23      | 6         | 1.3%    |
| Unknown | 6         | 1.3%    |
| 21      | 5         | 1.08%   |
| 72      | 4         | 0.86%   |
| 22      | 3         | 0.65%   |
| 19      | 3         | 0.65%   |
| 40      | 2         | 0.43%   |
| 32      | 2         | 0.43%   |
| 18      | 2         | 0.43%   |
| 84      | 1         | 0.22%   |
| 69      | 1         | 0.22%   |
| 54      | 1         | 0.22%   |
| 48      | 1         | 0.22%   |
| 29      | 1         | 0.22%   |
| 26      | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 305       | 65.87%  |
| 201-300     | 53        | 11.45%  |
| 351-400     | 43        | 9.29%   |
| 501-600     | 26        | 5.62%   |
| 401-500     | 11        | 2.38%   |
| 601-700     | 7         | 1.51%   |
| 1501-2000   | 6         | 1.3%    |
| Unknown     | 6         | 1.3%    |
| 801-900     | 2         | 0.43%   |
| 701-800     | 2         | 0.43%   |
| 1001-1500   | 2         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 362       | 85.78%  |
| 16/10   | 48        | 11.37%  |
| 4/3     | 3         | 0.71%   |
| Unknown | 3         | 0.71%   |
| 3/2     | 2         | 0.47%   |
| 6/5     | 1         | 0.24%   |
| 32/9    | 1         | 0.24%   |
| 3.73    | 1         | 0.24%   |
| 21/9    | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 205       | 44.37%  |
| 81-90          | 103       | 22.29%  |
| 121-130        | 33        | 7.14%   |
| 71-80          | 22        | 4.76%   |
| 201-250        | 20        | 4.33%   |
| 61-70          | 16        | 3.46%   |
| 51-60          | 12        | 2.6%    |
| 301-350        | 12        | 2.6%    |
| More than 1000 | 8         | 1.73%   |
| 351-500        | 8         | 1.73%   |
| Unknown        | 6         | 1.3%    |
| 111-120        | 5         | 1.08%   |
| 151-200        | 3         | 0.65%   |
| 131-140        | 3         | 0.65%   |
| 251-300        | 2         | 0.43%   |
| 141-150        | 2         | 0.43%   |
| 501-1000       | 2         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 208       | 45.32%  |
| 101-120       | 133       | 28.98%  |
| 51-100        | 60        | 13.07%  |
| 161-240       | 34        | 7.41%   |
| More than 240 | 10        | 2.18%   |
| 1-50          | 8         | 1.74%   |
| Unknown       | 6         | 1.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 362       | 85.38%  |
| 2     | 51        | 12.03%  |
| 3     | 7         | 1.65%   |
| 0     | 4         | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 239       | 34.14%  |
| Realtek Semiconductor                  | 230       | 32.86%  |
| Qualcomm Atheros                       | 80        | 11.43%  |
| Broadcom                               | 33        | 4.71%   |
| MediaTek                               | 18        | 2.57%   |
| Broadcom Limited                       | 13        | 1.86%   |
| TP-Link                                | 12        | 1.71%   |
| Samsung Electronics                    | 9         | 1.29%   |
| Xiaomi                                 | 8         | 1.14%   |
| Ralink Technology                      | 6         | 0.86%   |
| Qualcomm Atheros Communications        | 4         | 0.57%   |
| NetGear                                | 4         | 0.57%   |
| Huawei Technologies                    | 4         | 0.57%   |
| ASIX Electronics                       | 4         | 0.57%   |
| Ralink                                 | 3         | 0.43%   |
| Qualcomm                               | 3         | 0.43%   |
| OPPO Electronics                       | 3         | 0.43%   |
| ASUSTek Computer                       | 3         | 0.43%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.29%   |
| Nvidia                                 | 2         | 0.29%   |
| Linksys                                | 2         | 0.29%   |
| Lenovo                                 | 2         | 0.29%   |
| JMicron Technology                     | 2         | 0.29%   |
| Google                                 | 2         | 0.29%   |
| Ericsson Business Mobile Networks      | 2         | 0.29%   |
| Apple                                  | 2         | 0.29%   |
| ZyXEL Communications                   | 1         | 0.14%   |
| Sagem                                  | 1         | 0.14%   |
| Mercucys                               | 1         | 0.14%   |
| DisplayLink                            | 1         | 0.14%   |
| Dell                                   | 1         | 0.14%   |
| D-Link                                 | 1         | 0.14%   |
| Belkin Components                      | 1         | 0.14%   |
| Arduino SA                             | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 124       | 14.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 4.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 26        | 3.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23        | 2.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 2.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 19        | 2.26%   |
| Intel Wireless 8265 / 8275                                             | 17        | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 1.9%    |
| Intel Wi-Fi 6 AX201                                                    | 16        | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 15        | 1.79%   |
| Intel Wi-Fi 6 AX200                                                    | 15        | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 11        | 1.31%   |
| Intel Wireless 7260                                                    | 11        | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 11        | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 11        | 1.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 10        | 1.19%   |
| Intel Wireless 7265                                                    | 10        | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 9         | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 0.95%   |
| Intel Wireless 8260                                                    | 8         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 0.95%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 7         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 7         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6         | 0.71%   |
| Realtek 802.11ac NIC                                                   | 6         | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 0.71%   |
| Intel Wireless 3165                                                    | 6         | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 6         | 0.71%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 6         | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.6%    |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.6%    |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.6%    |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 234       | 49.26%  |
| Realtek Semiconductor           | 81        | 17.05%  |
| Qualcomm Atheros                | 64        | 13.47%  |
| Broadcom                        | 28        | 5.89%   |
| MediaTek                        | 16        | 3.37%   |
| TP-Link                         | 12        | 2.53%   |
| Broadcom Limited                | 11        | 2.32%   |
| Ralink Technology               | 6         | 1.26%   |
| Qualcomm Atheros Communications | 4         | 0.84%   |
| NetGear                         | 4         | 0.84%   |
| Ralink                          | 3         | 0.63%   |
| ASUSTek Computer                | 3         | 0.63%   |
| Linksys                         | 2         | 0.42%   |
| ZyXEL Communications            | 1         | 0.21%   |
| Sagem                           | 1         | 0.21%   |
| Qualcomm                        | 1         | 0.21%   |
| Mercucys                        | 1         | 0.21%   |
| Dell                            | 1         | 0.21%   |
| D-Link                          | 1         | 0.21%   |
| Belkin Components               | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                     | 26        | 5.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 19        | 3.98%   |
| Intel Wireless 8265 / 8275                                           | 17        | 3.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 16        | 3.35%   |
| Intel Wi-Fi 6 AX201                                                  | 16        | 3.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 15        | 3.14%   |
| Intel Wi-Fi 6 AX200                                                  | 15        | 3.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 14        | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 11        | 2.31%   |
| Intel Wireless 7260                                                  | 11        | 2.31%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 11        | 2.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 11        | 2.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 10        | 2.1%    |
| Intel Wireless 7265                                                  | 10        | 2.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 10        | 2.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 9         | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 8         | 1.68%   |
| Intel Wireless 8260                                                  | 8         | 1.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 7         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 7         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 1.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 6         | 1.26%   |
| Realtek 802.11ac NIC                                                 | 6         | 1.26%   |
| Intel Wireless 3165                                                  | 6         | 1.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 6         | 1.26%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 6         | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                        | 6         | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 5         | 1.05%   |
| Intel Centrino Advanced-N 6235                                       | 5         | 1.05%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 4         | 0.84%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 4         | 0.84%   |
| Qualcomm Atheros AR9271 802.11n                                      | 4         | 0.84%   |
| Intel Wireless 3160                                                  | 4         | 0.84%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 4         | 0.84%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 4         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4         | 0.84%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 4         | 0.84%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 4         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 196       | 55.84%  |
| Intel                                  | 74        | 21.08%  |
| Qualcomm Atheros                       | 28        | 7.98%   |
| Broadcom                               | 10        | 2.85%   |
| Samsung Electronics                    | 9         | 2.56%   |
| Xiaomi                                 | 8         | 2.28%   |
| ASIX Electronics                       | 4         | 1.14%   |
| OPPO Electronics                       | 3         | 0.85%   |
| Qualcomm                               | 2         | 0.57%   |
| Nvidia                                 | 2         | 0.57%   |
| MediaTek                               | 2         | 0.57%   |
| Lenovo                                 | 2         | 0.57%   |
| JMicron Technology                     | 2         | 0.57%   |
| Google                                 | 2         | 0.57%   |
| Broadcom Limited                       | 2         | 0.57%   |
| Apple                                  | 2         | 0.57%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.28%   |
| Huawei Technologies                    | 1         | 0.28%   |
| DisplayLink                            | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 124       | 34.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 10.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23        | 6.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 6.18%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 2.25%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 1.97%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 1.69%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 1.4%    |
| Realtek Killer E2600 GbE Controller                                    | 5         | 1.4%    |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.4%    |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 1.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 1.12%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 1.12%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.84%   |
| Intel Ethernet Connection (16) I219-V                                  | 3         | 0.84%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.84%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 3         | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.84%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.56%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.56%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 2         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.56%   |
| OPPO CPH2591                                                           | 2         | 0.56%   |
| MediaTek RMX3085                                                       | 2         | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 0.56%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.56%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.56%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.56%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 0.56%   |
| Google Pixel 7 Pro                                                     | 2         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 415       | 55.11%  |
| Ethernet | 331       | 43.96%  |
| Modem    | 6         | 0.8%    |
| Unknown  | 1         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 334       | 77.67%  |
| Ethernet | 95        | 22.09%  |
| Unknown  | 1         | 0.23%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 287       | 68.5%   |
| 1     | 120       | 28.64%  |
| 0     | 8         | 1.91%   |
| 3     | 4         | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 332       | 78.3%   |
| Yes     | 91        | 21.46%  |
| Unknown | 1         | 0.24%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 176       | 50.87%  |
| Realtek Semiconductor           | 37        | 10.69%  |
| Qualcomm Atheros Communications | 35        | 10.12%  |
| Broadcom                        | 21        | 6.07%   |
| IMC Networks                    | 15        | 4.34%   |
| Lite-On Technology              | 13        | 3.76%   |
| Foxconn / Hon Hai               | 13        | 3.76%   |
| Apple                           | 13        | 3.76%   |
| Dell                            | 4         | 1.16%   |
| Cambridge Silicon Radio         | 4         | 1.16%   |
| MediaTek                        | 3         | 0.87%   |
| Toshiba                         | 2         | 0.58%   |
| Ralink                          | 2         | 0.58%   |
| ASUSTek Computer                | 2         | 0.58%   |
| TP-Link                         | 1         | 0.29%   |
| Realtek                         | 1         | 0.29%   |
| Hewlett-Packard                 | 1         | 0.29%   |
| Dynex                           | 1         | 0.29%   |
| Alps Electric                   | 1         | 0.29%   |
| Unknown                         | 1         | 0.29%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 46        | 13.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 9.25%   |
| Intel Bluetooth wireless interface                  | 31        | 8.96%   |
| Intel Bluetooth Device                              | 24        | 6.94%   |
| Realtek Bluetooth Radio                             | 21        | 6.07%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 4.91%   |
| Intel AX200 Bluetooth                               | 14        | 4.05%   |
| Intel AX211 Bluetooth                               | 12        | 3.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 2.31%   |
| IMC Networks Wireless_Device                        | 7         | 2.02%   |
| Apple Bluetooth USB Host Controller                 | 6         | 1.73%   |
| Apple Bluetooth Host Controller                     | 6         | 1.73%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.45%   |
| IMC Networks Bluetooth Radio                        | 5         | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.16%   |
| Dell DW375 Bluetooth Module                         | 4         | 1.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.16%   |
| Broadcom HP Portable SoftSailing                    | 4         | 1.16%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.87%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 0.87%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.87%   |
| Qualcomm Atheros Bluetooth                          | 3         | 0.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.87%   |
| MediaTek Wireless_Device                            | 3         | 0.87%   |
| Lite-On Wireless_Device                             | 3         | 0.87%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.87%   |
| Intel AX210 Bluetooth                               | 3         | 0.87%   |
| IMC Networks Bluetooth Device                       | 3         | 0.87%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.87%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.87%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.58%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.58%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.58%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.58%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 349       | 68.3%   |
| Nvidia                 | 81        | 15.85%  |
| AMD                    | 68        | 13.31%  |
| JMTek                  | 3         | 0.59%   |
| Realtek Semiconductor  | 2         | 0.39%   |
| GN Netcom              | 2         | 0.39%   |
| Razer USA              | 1         | 0.2%    |
| Lenovo                 | 1         | 0.2%    |
| Guillemot              | 1         | 0.2%    |
| Generalplus Technology | 1         | 0.2%    |
| Conexant Systems       | 1         | 0.2%    |
| Apple                  | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 51        | 8.37%   |
| AMD Family 17h/19h HD Audio Controller                                     | 38        | 6.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 37        | 6.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 33        | 5.42%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 30        | 4.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 25        | 4.11%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 22        | 3.61%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 3.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 3.12%   |
| Intel 8 Series HD Audio Controller                                         | 19        | 3.12%   |
| Intel Cannon Lake PCH cAVS                                                 | 16        | 2.63%   |
| Nvidia Audio device                                                        | 15        | 2.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 2.46%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 2.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 13        | 2.13%   |
| Intel Comet Lake PCH cAVS                                                  | 12        | 1.97%   |
| AMD FCH Azalia Controller                                                  | 12        | 1.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 1.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 1.81%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 1.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 1.64%   |
| Nvidia GA106 High Definition Audio Controller                              | 9         | 1.48%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9         | 1.48%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 1.31%   |
| AMD Kabini HDMI/DP Audio                                                   | 8         | 1.31%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 1.31%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 1.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 1.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 1.15%   |
| AMD High Definition Audio Controller                                       | 7         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.66%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 0.66%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 0.66%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.66%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 0.66%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 0.66%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 100       | 29.94%  |
| SK hynix            | 63        | 18.86%  |
| Micron Technology   | 58        | 17.37%  |
| Kingston            | 20        | 5.99%   |
| Crucial             | 20        | 5.99%   |
| Unknown             | 11        | 3.29%   |
| Elpida              | 11        | 3.29%   |
| Ramaxel Technology  | 9         | 2.69%   |
| A-DATA Technology   | 8         | 2.4%    |
| Unknown (ABCD)      | 7         | 2.1%    |
| Nanya Technology    | 5         | 1.5%    |
| Team                | 4         | 1.2%    |
| Smart               | 3         | 0.9%    |
| Corsair             | 3         | 0.9%    |
| Transcend           | 2         | 0.6%    |
| G.Skill             | 2         | 0.6%    |
| Unknown             | 2         | 0.6%    |
| Timetec             | 1         | 0.3%    |
| Teikon              | 1         | 0.3%    |
| Saikano             | 1         | 0.3%    |
| PNY                 | 1         | 0.3%    |
| fef5                | 1         | 0.3%    |
| ChangXin Memory     | 1         | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 8         | 2.29%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 2.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 2.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 2.01%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.15%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.15%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.15%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.15%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.15%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.15%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.15%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 1.15%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.86%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.86%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.86%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.86%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.86%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.86%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 0.86%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.86%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.57%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 2         | 0.57%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.57%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.57%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.57%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.57%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.57%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.57%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.57%   |
| Samsung RAM M425R1GB4BB0-CWMOD 8GB SODIMM DDR5 5600MT/s          | 2         | 0.57%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 2         | 0.57%   |
| Samsung RAM M4 70T2953CZ3-CE6 1GB SODIMM DDR2 667MT/s            | 2         | 0.57%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 2         | 0.57%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 134       | 47.35%  |
| DDR3    | 89        | 31.45%  |
| LPDDR4  | 23        | 8.13%   |
| LPDDR3  | 11        | 3.89%   |
| DDR5    | 8         | 2.83%   |
| DDR2    | 6         | 2.12%   |
| LPDDR5  | 5         | 1.77%   |
| Unknown | 5         | 1.77%   |
| SDRAM   | 1         | 0.35%   |
| DDR     | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 244       | 86.52%  |
| Row Of Chips | 34        | 12.06%  |
| Unknown      | 3         | 1.06%   |
| Chip         | 1         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 130       | 41.27%  |
| 4096  | 90        | 28.57%  |
| 16384 | 47        | 14.92%  |
| 2048  | 27        | 8.57%   |
| 1024  | 11        | 3.49%   |
| 32768 | 10        | 3.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 65        | 21.17%  |
| 1600    | 62        | 20.2%   |
| 2667    | 60        | 19.54%  |
| 2400    | 23        | 7.49%   |
| 1334    | 19        | 6.19%   |
| 2133    | 15        | 4.89%   |
| 4800    | 9         | 2.93%   |
| 1333    | 9         | 2.93%   |
| 4267    | 6         | 1.95%   |
| 6400    | 5         | 1.63%   |
| 1867    | 5         | 1.63%   |
| 1067    | 4         | 1.3%    |
| 1066    | 4         | 1.3%    |
| 5600    | 3         | 0.98%   |
| 3266    | 3         | 0.98%   |
| 667     | 3         | 0.98%   |
| 3733    | 2         | 0.65%   |
| 975     | 2         | 0.65%   |
| Unknown | 2         | 0.65%   |
| 8400    | 1         | 0.33%   |
| 4266    | 1         | 0.33%   |
| 2048    | 1         | 0.33%   |
| 1866    | 1         | 0.33%   |
| 800     | 1         | 0.33%   |
| 533     | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP Deskjet 2050 J510    | 1         | 50%     |
| Brother HL-1210W series | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 94        | 25.34%  |
| IMC Networks                           | 43        | 11.59%  |
| Bison Electronics                      | 31        | 8.36%   |
| Microdia                               | 29        | 7.82%   |
| Quanta                                 | 22        | 5.93%   |
| Sunplus Innovation Technology          | 20        | 5.39%   |
| Realtek Semiconductor                  | 20        | 5.39%   |
| Syntek                                 | 12        | 3.23%   |
| Luxvisions Innotech Limited            | 12        | 3.23%   |
| Apple                                  | 12        | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 2.96%   |
| Lite-On Technology                     | 8         | 2.16%   |
| Suyin                                  | 7         | 1.89%   |
| Ricoh                                  | 6         | 1.62%   |
| Acer                                   | 6         | 1.62%   |
| Sonix Technology                       | 5         | 1.35%   |
| Silicon Motion                         | 5         | 1.35%   |
| Samsung Electronics                    | 5         | 1.35%   |
| icSpring                               | 4         | 1.08%   |
| Alcor Micro                            | 4         | 1.08%   |
| SunplusIT                              | 2         | 0.54%   |
| Primax Electronics                     | 2         | 0.54%   |
| Logitech                               | 2         | 0.54%   |
| Importek                               | 2         | 0.54%   |
| USB Camera CS                          | 1         | 0.27%   |
| Tobii Technology AB                    | 1         | 0.27%   |
| LG Electronics                         | 1         | 0.27%   |
| Goertek Electronics                    | 1         | 0.27%   |
| Genesys Logic                          | 1         | 0.27%   |
| AVerMedia Technologies                 | 1         | 0.27%   |
| ALi                                    | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 20        | 5.38%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 13        | 3.49%   |
| IMC Networks Integrated Camera                       | 11        | 2.96%   |
| Bison HD Webcam                                      | 11        | 2.96%   |
| Syntek Integrated Camera                             | 8         | 2.15%   |
| Realtek Integrated_Webcam_HD                         | 8         | 2.15%   |
| Microdia Integrated_Webcam_HD                        | 8         | 2.15%   |
| Chicony HD User Facing                               | 7         | 1.88%   |
| Quanta HD User Facing                                | 6         | 1.61%   |
| Chicony HP Truevision HD                             | 6         | 1.61%   |
| Chicony HP HD Camera                                 | 6         | 1.61%   |
| Chicony HD Webcam                                    | 6         | 1.61%   |
| Sunplus Integrated_Webcam_HD                         | 5         | 1.34%   |
| Samsung Galaxy series, misc. (MTP mode)              | 5         | 1.34%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 5         | 1.34%   |
| Chicony USB2.0 Camera                                | 5         | 1.34%   |
| Bison SunplusIT Integrated Camera                    | 5         | 1.34%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 5         | 1.34%   |
| Realtek Integrated Webcam HD                         | 4         | 1.08%   |
| Quanta HP TrueVision HD Camera                       | 4         | 1.08%   |
| icSpring camera                                      | 4         | 1.08%   |
| Chicony USB2.0 HD UVC WebCam                         | 4         | 1.08%   |
| Chicony Integrated Camera (1280x720@30)              | 4         | 1.08%   |
| Bison Integrated Camera                              | 4         | 1.08%   |
| Bison EasyCamera                                     | 4         | 1.08%   |
| Acer Integrated Camera                               | 4         | 1.08%   |
| Syntek Lenovo EasyCamera                             | 3         | 0.81%   |
| Sonix USB2.0 FHD UVC WebCam                          | 3         | 0.81%   |
| Quanta VGA WebCam                                    | 3         | 0.81%   |
| Quanta ACER HD User Facing                           | 3         | 0.81%   |
| Microdia Webcam Vitade AF                            | 3         | 0.81%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 0.81%   |
| Microdia Integrated Webcam HD                        | 3         | 0.81%   |
| Microdia Integrated Webcam                           | 3         | 0.81%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 0.81%   |
| IMC Networks HD Camera                               | 3         | 0.81%   |
| Chicony EasyCamera                                   | 3         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 3         | 0.81%   |
| Apple FaceTime HD Camera                             | 3         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 29        | 38.16%  |
| Validity Sensors           | 23        | 30.26%  |
| Shenzhen Goodix Technology | 8         | 10.53%  |
| Elan Microelectronics      | 6         | 7.89%   |
| Upek                       | 3         | 3.95%   |
| AuthenTec                  | 3         | 3.95%   |
| LighTuning Technology      | 2         | 2.63%   |
| Samsung Electronics        | 1         | 1.32%   |
| HOLTEK                     | 1         | 1.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 11.84%  |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 7.89%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 6.58%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 6.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.26%   |
| Synaptics UWP WBDI Device                                                  | 4         | 5.26%   |
| Elan ELAN:Fingerprint                                                      | 4         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.95%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.95%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 3.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.95%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.63%   |
| Validity Sensors VFS491                                                    | 2         | 2.63%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.63%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.63%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.63%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.63%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.32%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.32%   |
| Synaptics WBDI                                                             | 1         | 1.32%   |
| Synaptics  WBDI                                                            | 1         | 1.32%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.32%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.32%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.32%   |
| Samsung Fingerprint Device                                                 | 1         | 1.32%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.32%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.32%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 1.32%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 16        | 61.54%  |
| Alcor Micro | 7         | 26.92%  |
| Upek        | 1         | 3.85%   |
| OmniKey     | 1         | 3.85%   |
| O2 Micro    | 1         | 3.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 26.92%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 26.92%  |
| Broadcom 5880                                                                | 5         | 19.23%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 15.38%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.85%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 3.85%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 244       | 57.01%  |
| 1     | 145       | 33.88%  |
| 2     | 36        | 8.41%   |
| 3     | 3         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 77        | 35.48%  |
| Graphics card         | 36        | 16.59%  |
| Chipcard              | 25        | 11.52%  |
| Multimedia controller | 21        | 9.68%   |
| Net/wireless          | 20        | 9.22%   |
| Camera                | 11        | 5.07%   |
| Net/ethernet          | 9         | 4.15%   |
| Storage               | 6         | 2.76%   |
| Network               | 4         | 1.84%   |
| Bluetooth             | 4         | 1.84%   |
| Sound                 | 2         | 0.92%   |
| Modem                 | 1         | 0.46%   |
| Card reader           | 1         | 0.46%   |

