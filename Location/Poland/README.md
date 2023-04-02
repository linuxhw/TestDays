Linux in Poland - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 7129

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | DG41RQ AAE54511-203         | Desktop     | [383835a445](https://linux-hardware.org/?probe=383835a445) | Apr 01, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [c5a4783dfb](https://linux-hardware.org/?probe=c5a4783dfb) | Apr 01, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [5d6606235d](https://linux-hardware.org/?probe=5d6606235d) | Apr 01, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [dff9959cd7](https://linux-hardware.org/?probe=dff9959cd7) | Mar 31, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [e5a729243d](https://linux-hardware.org/?probe=e5a729243d) | Mar 31, 2023 |
| Samsung       | 950XED                      | Notebook    | [c3b37a213a](https://linux-hardware.org/?probe=c3b37a213a) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [4d69417ed0](https://linux-hardware.org/?probe=4d69417ed0) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [6e93ca4159](https://linux-hardware.org/?probe=6e93ca4159) | Mar 31, 2023 |
| Acer          | TravelMate 8172Z            | Notebook    | [10cc090653](https://linux-hardware.org/?probe=10cc090653) | Mar 31, 2023 |
| Dell          | Latitude D620               | Notebook    | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| Acer          | WG43M                       | Desktop     | [3b626d2ff9](https://linux-hardware.org/?probe=3b626d2ff9) | Mar 31, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [aa9a729217](https://linux-hardware.org/?probe=aa9a729217) | Mar 30, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [6b9737a62f](https://linux-hardware.org/?probe=6b9737a62f) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f78b6ab8c5](https://linux-hardware.org/?probe=f78b6ab8c5) | Mar 30, 2023 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [b593e25f2a](https://linux-hardware.org/?probe=b593e25f2a) | Mar 30, 2023 |
| Intel         | DQ45CB E30148-207           | Desktop     | [e47e1626c3](https://linux-hardware.org/?probe=e47e1626c3) | Mar 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [eb7392d1ae](https://linux-hardware.org/?probe=eb7392d1ae) | Mar 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [680c7a04ed](https://linux-hardware.org/?probe=680c7a04ed) | Mar 29, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [e7b163ea80](https://linux-hardware.org/?probe=e7b163ea80) | Mar 29, 2023 |
| GPD           | G1621-02                    | Notebook    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fa1a582da6](https://linux-hardware.org/?probe=fa1a582da6) | Mar 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [94cdfc44d1](https://linux-hardware.org/?probe=94cdfc44d1) | Mar 28, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [ea2013b347](https://linux-hardware.org/?probe=ea2013b347) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Notebook    | [856b789461](https://linux-hardware.org/?probe=856b789461) | Mar 28, 2023 |
| Dell          | Latitude 7490               | Notebook    | [41d01ead49](https://linux-hardware.org/?probe=41d01ead49) | Mar 28, 2023 |
| Dell          | 0G261D A00                  | Desktop     | [f63f67f28f](https://linux-hardware.org/?probe=f63f67f28f) | Mar 28, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [365cc196f2](https://linux-hardware.org/?probe=365cc196f2) | Mar 27, 2023 |
| Dell          | Inspiron 5735               | Notebook    | [823a6ece98](https://linux-hardware.org/?probe=823a6ece98) | Mar 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS47P00    | Notebook    | [e287203572](https://linux-hardware.org/?probe=e287203572) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [16ba0fa199](https://linux-hardware.org/?probe=16ba0fa199) | Mar 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [aaeb6059a2](https://linux-hardware.org/?probe=aaeb6059a2) | Mar 27, 2023 |
| HP            | 895D                        | Desktop     | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| Dell          | Precision 7670              | Notebook    | [eece926391](https://linux-hardware.org/?probe=eece926391) | Mar 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| HP            | 1998                        | Desktop     | [2d5e0737e5](https://linux-hardware.org/?probe=2d5e0737e5) | Mar 27, 2023 |
| Dell          | Precision 7670              | Notebook    | [5b8f0590ec](https://linux-hardware.org/?probe=5b8f0590ec) | Mar 27, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [1c37ecb6c7](https://linux-hardware.org/?probe=1c37ecb6c7) | Mar 26, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [4e4f63c868](https://linux-hardware.org/?probe=4e4f63c868) | Mar 26, 2023 |
| Acer          | WG43M                       | Desktop     | [74320e2d13](https://linux-hardware.org/?probe=74320e2d13) | Mar 26, 2023 |
| Lenovo        | ThinkPad T520 4243RP3       | Notebook    | [38fa314d2f](https://linux-hardware.org/?probe=38fa314d2f) | Mar 26, 2023 |
| MSI           | Creator Z16 A11UET          | Notebook    | [0133ab37af](https://linux-hardware.org/?probe=0133ab37af) | Mar 26, 2023 |
| Sony          | VGN-BX61VN                  | Notebook    | [76f62cf9c1](https://linux-hardware.org/?probe=76f62cf9c1) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [45abc5547d](https://linux-hardware.org/?probe=45abc5547d) | Mar 26, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [f406bad420](https://linux-hardware.org/?probe=f406bad420) | Mar 26, 2023 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [4fcf740ee9](https://linux-hardware.org/?probe=4fcf740ee9) | Mar 25, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [71fc8dc05c](https://linux-hardware.org/?probe=71fc8dc05c) | Mar 25, 2023 |
| Lenovo        | ThinkPad W520 4282PQ7       | Notebook    | [ff42aa158f](https://linux-hardware.org/?probe=ff42aa158f) | Mar 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [1301dd9965](https://linux-hardware.org/?probe=1301dd9965) | Mar 25, 2023 |
| HP            | Notebook                    | Notebook    | [7c4088912e](https://linux-hardware.org/?probe=7c4088912e) | Mar 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [eaf933f33a](https://linux-hardware.org/?probe=eaf933f33a) | Mar 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [caa720b95b](https://linux-hardware.org/?probe=caa720b95b) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | Notebook    | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [6a7628c31d](https://linux-hardware.org/?probe=6a7628c31d) | Mar 25, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [c7bf2c9968](https://linux-hardware.org/?probe=c7bf2c9968) | Mar 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [29a94d3d9e](https://linux-hardware.org/?probe=29a94d3d9e) | Mar 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c3a6c3f669](https://linux-hardware.org/?probe=c3a6c3f669) | Mar 25, 2023 |
| Samsung       | 950QED                      | Convertible | [14fa80f70c](https://linux-hardware.org/?probe=14fa80f70c) | Mar 25, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7f32708bde](https://linux-hardware.org/?probe=7f32708bde) | Mar 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [446c510c65](https://linux-hardware.org/?probe=446c510c65) | Mar 24, 2023 |
| Toshiba       | Satellite C855-12N          | Notebook    | [cb9692876c](https://linux-hardware.org/?probe=cb9692876c) | Mar 24, 2023 |
| HP            | 304Ah                       | Desktop     | [43990fede2](https://linux-hardware.org/?probe=43990fede2) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [47814b01b6](https://linux-hardware.org/?probe=47814b01b6) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | Notebook    | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [d18034c36c](https://linux-hardware.org/?probe=d18034c36c) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| Dell          | Latitude E7450              | Notebook    | [c1e43b6a40](https://linux-hardware.org/?probe=c1e43b6a40) | Mar 23, 2023 |
| Lenovo        | G580                        | Notebook    | [367ed9241a](https://linux-hardware.org/?probe=367ed9241a) | Mar 23, 2023 |
| Dell          | 0DPRKF A01                  | Server      | [fdc74a5707](https://linux-hardware.org/?probe=fdc74a5707) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d32ee19009](https://linux-hardware.org/?probe=d32ee19009) | Mar 23, 2023 |
| Lenovo        | G580                        | Notebook    | [6ee526d77a](https://linux-hardware.org/?probe=6ee526d77a) | Mar 22, 2023 |
| Acer          | Aspire VN7-791              | Notebook    | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [f6ad6626ff](https://linux-hardware.org/?probe=f6ad6626ff) | Mar 22, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [0ae6ab3ff6](https://linux-hardware.org/?probe=0ae6ab3ff6) | Mar 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [31ee1d66d8](https://linux-hardware.org/?probe=31ee1d66d8) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | Desktop     | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [a9e094374a](https://linux-hardware.org/?probe=a9e094374a) | Mar 20, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [a03658793c](https://linux-hardware.org/?probe=a03658793c) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [6df656c198](https://linux-hardware.org/?probe=6df656c198) | Mar 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1bad88b80e](https://linux-hardware.org/?probe=1bad88b80e) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [cd708d0e58](https://linux-hardware.org/?probe=cd708d0e58) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [888ec192b4](https://linux-hardware.org/?probe=888ec192b4) | Mar 19, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [efbab00e4b](https://linux-hardware.org/?probe=efbab00e4b) | Mar 19, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [919ccc204b](https://linux-hardware.org/?probe=919ccc204b) | Mar 19, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [703ea3d03c](https://linux-hardware.org/?probe=703ea3d03c) | Mar 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c89c2e1369](https://linux-hardware.org/?probe=c89c2e1369) | Mar 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [31299394e0](https://linux-hardware.org/?probe=31299394e0) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [2d7a146140](https://linux-hardware.org/?probe=2d7a146140) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [a5775c7491](https://linux-hardware.org/?probe=a5775c7491) | Mar 17, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [2a17e297a2](https://linux-hardware.org/?probe=2a17e297a2) | Mar 17, 2023 |
| Toshiba       | QOSMIO X500                 | Notebook    | [2ce878e92e](https://linux-hardware.org/?probe=2ce878e92e) | Mar 17, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [96742a0cb2](https://linux-hardware.org/?probe=96742a0cb2) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| Dell          | G5 5590                     | Notebook    | [9686d438e6](https://linux-hardware.org/?probe=9686d438e6) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [593bd6b3ac](https://linux-hardware.org/?probe=593bd6b3ac) | Mar 17, 2023 |
| Dell          | Latitude E7440              | Notebook    | [8a6e751b61](https://linux-hardware.org/?probe=8a6e751b61) | Mar 16, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f53eccbbe9](https://linux-hardware.org/?probe=f53eccbbe9) | Mar 16, 2023 |
| Dell          | Latitude 5511               | Notebook    | [7444a8c723](https://linux-hardware.org/?probe=7444a8c723) | Mar 16, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [e75695c0ea](https://linux-hardware.org/?probe=e75695c0ea) | Mar 16, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [d8bdd6ff7c](https://linux-hardware.org/?probe=d8bdd6ff7c) | Mar 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [1731735e10](https://linux-hardware.org/?probe=1731735e10) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [eb0beb38eb](https://linux-hardware.org/?probe=eb0beb38eb) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [c54f2ca880](https://linux-hardware.org/?probe=c54f2ca880) | Mar 16, 2023 |
| Sony          | VPCEH1S1E                   | Notebook    | [9e8a96156c](https://linux-hardware.org/?probe=9e8a96156c) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [b5281b4ba4](https://linux-hardware.org/?probe=b5281b4ba4) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [59d7fa9a34](https://linux-hardware.org/?probe=59d7fa9a34) | Mar 15, 2023 |
| Dell          | Latitude 7390               | Notebook    | [7cc6b3a278](https://linux-hardware.org/?probe=7cc6b3a278) | Mar 15, 2023 |
| MSI           | B85-G43                     | Desktop     | [d8334d09fa](https://linux-hardware.org/?probe=d8334d09fa) | Mar 15, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [320dab99e7](https://linux-hardware.org/?probe=320dab99e7) | Mar 15, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [97fe8661ed](https://linux-hardware.org/?probe=97fe8661ed) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | Desktop     | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | Desktop     | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [f9ed050c6a](https://linux-hardware.org/?probe=f9ed050c6a) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [d422d0d291](https://linux-hardware.org/?probe=d422d0d291) | Mar 14, 2023 |
| Lenovo        | ThinkPad X301 2776LEG       | Notebook    | [7b0df25d34](https://linux-hardware.org/?probe=7b0df25d34) | Mar 14, 2023 |
| Lenovo        | ThinkPad X301 2776LEG       | Notebook    | [65fe38f62e](https://linux-hardware.org/?probe=65fe38f62e) | Mar 14, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [bfc73429bb](https://linux-hardware.org/?probe=bfc73429bb) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [b9cfb4b900](https://linux-hardware.org/?probe=b9cfb4b900) | Mar 13, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [fba21e619d](https://linux-hardware.org/?probe=fba21e619d) | Mar 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [e270b5804a](https://linux-hardware.org/?probe=e270b5804a) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [bc375a2ddd](https://linux-hardware.org/?probe=bc375a2ddd) | Mar 13, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a0590e6829](https://linux-hardware.org/?probe=a0590e6829) | Mar 13, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [73d5ba11c5](https://linux-hardware.org/?probe=73d5ba11c5) | Mar 13, 2023 |
| Dell          | Latitude 3190               | Notebook    | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [0b0840b785](https://linux-hardware.org/?probe=0b0840b785) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [37b002e8ec](https://linux-hardware.org/?probe=37b002e8ec) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | Notebook    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [bb5d069d90](https://linux-hardware.org/?probe=bb5d069d90) | Mar 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [afe81d4bfa](https://linux-hardware.org/?probe=afe81d4bfa) | Mar 12, 2023 |
| HP            | 213D A01                    | Desktop     | [8c6054a4f7](https://linux-hardware.org/?probe=8c6054a4f7) | Mar 12, 2023 |
| Google        | Electro                     | Notebook    | [86cbc9d907](https://linux-hardware.org/?probe=86cbc9d907) | Mar 12, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [566beba012](https://linux-hardware.org/?probe=566beba012) | Mar 12, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [d173735b81](https://linux-hardware.org/?probe=d173735b81) | Mar 11, 2023 |
| Dell          | Precision M6600             | Notebook    | [9d5e2f1e01](https://linux-hardware.org/?probe=9d5e2f1e01) | Mar 11, 2023 |
| Acer          | Extensa 5620                | Notebook    | [f95239bf35](https://linux-hardware.org/?probe=f95239bf35) | Mar 11, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [5714b30108](https://linux-hardware.org/?probe=5714b30108) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| MSI           | Z170-A PRO                  | Desktop     | [a83243223a](https://linux-hardware.org/?probe=a83243223a) | Mar 10, 2023 |
| HP            | 0AA0h                       | Desktop     | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| Dell          | Latitude E6530              | Notebook    | [70b72984bc](https://linux-hardware.org/?probe=70b72984bc) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [bfd26d4727](https://linux-hardware.org/?probe=bfd26d4727) | Mar 10, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [2d99e047c9](https://linux-hardware.org/?probe=2d99e047c9) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [7a7e8bc855](https://linux-hardware.org/?probe=7a7e8bc855) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cc2d7d8a95](https://linux-hardware.org/?probe=cc2d7d8a95) | Mar 09, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b00f44cd46](https://linux-hardware.org/?probe=b00f44cd46) | Mar 09, 2023 |
| Dell          | Latitude E6440              | Notebook    | [3b9229e07a](https://linux-hardware.org/?probe=3b9229e07a) | Mar 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c50daaf3b9](https://linux-hardware.org/?probe=c50daaf3b9) | Mar 09, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [670e89da85](https://linux-hardware.org/?probe=670e89da85) | Mar 09, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [fdc32a6871](https://linux-hardware.org/?probe=fdc32a6871) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [12fa2455f7](https://linux-hardware.org/?probe=12fa2455f7) | Mar 08, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [dfd9b7a9b9](https://linux-hardware.org/?probe=dfd9b7a9b9) | Mar 08, 2023 |
| HP            | ENVY 6                      | Notebook    | [4873f7b85f](https://linux-hardware.org/?probe=4873f7b85f) | Mar 08, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [c756678fad](https://linux-hardware.org/?probe=c756678fad) | Mar 08, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | Notebook    | [daf29f1a82](https://linux-hardware.org/?probe=daf29f1a82) | Mar 08, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [34696138fe](https://linux-hardware.org/?probe=34696138fe) | Mar 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [233722f0e1](https://linux-hardware.org/?probe=233722f0e1) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [43a939870d](https://linux-hardware.org/?probe=43a939870d) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [f64ba0ea72](https://linux-hardware.org/?probe=f64ba0ea72) | Mar 07, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [397eb062bf](https://linux-hardware.org/?probe=397eb062bf) | Mar 07, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [ef67915ff3](https://linux-hardware.org/?probe=ef67915ff3) | Mar 07, 2023 |
| Dell          | Latitude 7290               | Notebook    | [38f12088b2](https://linux-hardware.org/?probe=38f12088b2) | Mar 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [59cb6854e5](https://linux-hardware.org/?probe=59cb6854e5) | Mar 07, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [b809f137cd](https://linux-hardware.org/?probe=b809f137cd) | Mar 07, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [838825a42b](https://linux-hardware.org/?probe=838825a42b) | Mar 06, 2023 |
| Microsoft     | Surface Laptop Go 2         | Tablet      | [f5a1ceaa74](https://linux-hardware.org/?probe=f5a1ceaa74) | Mar 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0cda9f83b1](https://linux-hardware.org/?probe=0cda9f83b1) | Mar 06, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [31a734c56b](https://linux-hardware.org/?probe=31a734c56b) | Mar 06, 2023 |
| Biostar       | TA780G M2+                  | Desktop     | [f5ddb4d21a](https://linux-hardware.org/?probe=f5ddb4d21a) | Mar 05, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| MSI           | B550M PRO                   | Desktop     | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [91fc2d53f8](https://linux-hardware.org/?probe=91fc2d53f8) | Mar 05, 2023 |
| HP            | 18E5                        | Desktop     | [969462a8a0](https://linux-hardware.org/?probe=969462a8a0) | Mar 05, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [80e769b994](https://linux-hardware.org/?probe=80e769b994) | Mar 05, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [b77e06361b](https://linux-hardware.org/?probe=b77e06361b) | Mar 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | Notebook    | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | Notebook    | [3619b3fcee](https://linux-hardware.org/?probe=3619b3fcee) | Mar 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [92b81bb3a1](https://linux-hardware.org/?probe=92b81bb3a1) | Mar 05, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [ea145a8349](https://linux-hardware.org/?probe=ea145a8349) | Mar 05, 2023 |
| ASUSTek       | N71Vg                       | Notebook    | [4d83fda5ba](https://linux-hardware.org/?probe=4d83fda5ba) | Mar 05, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Notebook    | [8b36c984f8](https://linux-hardware.org/?probe=8b36c984f8) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [65006682e6](https://linux-hardware.org/?probe=65006682e6) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [d9a9f6b904](https://linux-hardware.org/?probe=d9a9f6b904) | Mar 05, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [773ac5157e](https://linux-hardware.org/?probe=773ac5157e) | Mar 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [cf87d901a9](https://linux-hardware.org/?probe=cf87d901a9) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5eb43b511f](https://linux-hardware.org/?probe=5eb43b511f) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8db9ca3a4b](https://linux-hardware.org/?probe=8db9ca3a4b) | Mar 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [789ca3b7bd](https://linux-hardware.org/?probe=789ca3b7bd) | Mar 05, 2023 |
| HP            | 15                          | Notebook    | [0efd9be7ae](https://linux-hardware.org/?probe=0efd9be7ae) | Mar 04, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [241283977d](https://linux-hardware.org/?probe=241283977d) | Mar 04, 2023 |
| HP            | 15                          | Notebook    | [b8a33a3d73](https://linux-hardware.org/?probe=b8a33a3d73) | Mar 04, 2023 |
| Lenovo        | ThinkPad T420 4177R3U       | Notebook    | [525dd38cf1](https://linux-hardware.org/?probe=525dd38cf1) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [bd108fcfba](https://linux-hardware.org/?probe=bd108fcfba) | Mar 04, 2023 |
| HP            | Notebook                    | Notebook    | [229fbff95c](https://linux-hardware.org/?probe=229fbff95c) | Mar 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [afe8ef7318](https://linux-hardware.org/?probe=afe8ef7318) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [0b0c5a6895](https://linux-hardware.org/?probe=0b0c5a6895) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| IGEL Techn... | H830C                       | Notebook    | [4625dc0660](https://linux-hardware.org/?probe=4625dc0660) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [e3f1423c39](https://linux-hardware.org/?probe=e3f1423c39) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [0228fd4ab1](https://linux-hardware.org/?probe=0228fd4ab1) | Mar 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [4679c9328e](https://linux-hardware.org/?probe=4679c9328e) | Mar 03, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [9186971572](https://linux-hardware.org/?probe=9186971572) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [0e8d1a9e75](https://linux-hardware.org/?probe=0e8d1a9e75) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [25f45efbc1](https://linux-hardware.org/?probe=25f45efbc1) | Mar 03, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [608c8a42da](https://linux-hardware.org/?probe=608c8a42da) | Mar 03, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [fa55d9fb5c](https://linux-hardware.org/?probe=fa55d9fb5c) | Mar 03, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2B50... | Notebook    | [8268a3bbf3](https://linux-hardware.org/?probe=8268a3bbf3) | Mar 03, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Supermicro    | X11SCL-F                    | Server      | [ef92c1fc32](https://linux-hardware.org/?probe=ef92c1fc32) | Mar 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a40e18910c](https://linux-hardware.org/?probe=a40e18910c) | Mar 03, 2023 |
| ASUSTek       | N61Vn                       | Notebook    | [9528e36d7b](https://linux-hardware.org/?probe=9528e36d7b) | Mar 03, 2023 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [726752f23a](https://linux-hardware.org/?probe=726752f23a) | Mar 02, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [b53826c91c](https://linux-hardware.org/?probe=b53826c91c) | Mar 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a5288ab43b](https://linux-hardware.org/?probe=a5288ab43b) | Mar 02, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [e87ce2454c](https://linux-hardware.org/?probe=e87ce2454c) | Mar 02, 2023 |
| Dell          | Latitude D830               | Notebook    | [83415c82ac](https://linux-hardware.org/?probe=83415c82ac) | Mar 02, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [a79b4ff73c](https://linux-hardware.org/?probe=a79b4ff73c) | Mar 02, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [e943ab2cde](https://linux-hardware.org/?probe=e943ab2cde) | Mar 01, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | Desktop     | [ada9b78c86](https://linux-hardware.org/?probe=ada9b78c86) | Mar 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [9b0d952fa9](https://linux-hardware.org/?probe=9b0d952fa9) | Mar 01, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [18ff6f22a6](https://linux-hardware.org/?probe=18ff6f22a6) | Mar 01, 2023 |
| Dell          | Latitude 7330               | Convertible | [0ad2e974ba](https://linux-hardware.org/?probe=0ad2e974ba) | Mar 01, 2023 |
| Dell          | Latitude 5420               | Notebook    | [0596aff5c4](https://linux-hardware.org/?probe=0596aff5c4) | Feb 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [52522a762d](https://linux-hardware.org/?probe=52522a762d) | Feb 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [07bb534dc9](https://linux-hardware.org/?probe=07bb534dc9) | Feb 28, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [756e003316](https://linux-hardware.org/?probe=756e003316) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [260ece1650](https://linux-hardware.org/?probe=260ece1650) | Feb 28, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [7060b60651](https://linux-hardware.org/?probe=7060b60651) | Feb 27, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [a184aa7141](https://linux-hardware.org/?probe=a184aa7141) | Feb 27, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| ASUSTek       | K75VJ                       | Notebook    | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a2167ae72b](https://linux-hardware.org/?probe=a2167ae72b) | Feb 27, 2023 |
| Schenker      | VISION (E22)                | Notebook    | [498444ca02](https://linux-hardware.org/?probe=498444ca02) | Feb 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [a1180ad479](https://linux-hardware.org/?probe=a1180ad479) | Feb 27, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [409bb06e5e](https://linux-hardware.org/?probe=409bb06e5e) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [ee2645efa8](https://linux-hardware.org/?probe=ee2645efa8) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [d57bb59dee](https://linux-hardware.org/?probe=d57bb59dee) | Feb 27, 2023 |
| ASUSTek       | K52F                        | Notebook    | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [0d838134b7](https://linux-hardware.org/?probe=0d838134b7) | Feb 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [aa86292f52](https://linux-hardware.org/?probe=aa86292f52) | Feb 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f8d42c3767](https://linux-hardware.org/?probe=f8d42c3767) | Feb 27, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [589b06afc1](https://linux-hardware.org/?probe=589b06afc1) | Feb 26, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [8e397cc54f](https://linux-hardware.org/?probe=8e397cc54f) | Feb 26, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [df54545112](https://linux-hardware.org/?probe=df54545112) | Feb 26, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [9357168131](https://linux-hardware.org/?probe=9357168131) | Feb 26, 2023 |
| Gigabyte      | MMLP5AP-00                  | Notebook    | [eb5ca5bb8d](https://linux-hardware.org/?probe=eb5ca5bb8d) | Feb 26, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [f09bf9b926](https://linux-hardware.org/?probe=f09bf9b926) | Feb 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [cf1d88a388](https://linux-hardware.org/?probe=cf1d88a388) | Feb 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [f7289abeb1](https://linux-hardware.org/?probe=f7289abeb1) | Feb 26, 2023 |
| Dell          | Latitude D630               | Notebook    | [cfdc009ff1](https://linux-hardware.org/?probe=cfdc009ff1) | Feb 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [782598981d](https://linux-hardware.org/?probe=782598981d) | Feb 25, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [6a75456290](https://linux-hardware.org/?probe=6a75456290) | Feb 25, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [73caef7b95](https://linux-hardware.org/?probe=73caef7b95) | Feb 25, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [07fe4333eb](https://linux-hardware.org/?probe=07fe4333eb) | Feb 25, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [563101d2b2](https://linux-hardware.org/?probe=563101d2b2) | Feb 25, 2023 |
| Sony          | VGN-FZ31M                   | Notebook    | [6b830e36f1](https://linux-hardware.org/?probe=6b830e36f1) | Feb 25, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [6a7ac3b38b](https://linux-hardware.org/?probe=6a7ac3b38b) | Feb 24, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [b2681528bd](https://linux-hardware.org/?probe=b2681528bd) | Feb 24, 2023 |
| ASUSTek       | B150M-A D3                  | Desktop     | [01caadaee0](https://linux-hardware.org/?probe=01caadaee0) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [f1fa3164f9](https://linux-hardware.org/?probe=f1fa3164f9) | Feb 24, 2023 |
| Gigabyte      | B85M-HD3 R4                 | Desktop     | [db83755f3f](https://linux-hardware.org/?probe=db83755f3f) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [a85b9d1452](https://linux-hardware.org/?probe=a85b9d1452) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Notebook    | [e2cdf5625c](https://linux-hardware.org/?probe=e2cdf5625c) | Feb 23, 2023 |
| Dell          | XPS 9320                    | Notebook    | [94e7c2d282](https://linux-hardware.org/?probe=94e7c2d282) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Notebook    | [bfbb3aab2c](https://linux-hardware.org/?probe=bfbb3aab2c) | Feb 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [821d952d15](https://linux-hardware.org/?probe=821d952d15) | Feb 23, 2023 |
| ASUSTek       | 1215B                       | Notebook    | [970d77d150](https://linux-hardware.org/?probe=970d77d150) | Feb 22, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [a213ec0ba4](https://linux-hardware.org/?probe=a213ec0ba4) | Feb 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b7071da133](https://linux-hardware.org/?probe=b7071da133) | Feb 22, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [39e6d492c4](https://linux-hardware.org/?probe=39e6d492c4) | Feb 22, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [40bc5397ea](https://linux-hardware.org/?probe=40bc5397ea) | Feb 22, 2023 |
| ASRock        | Z690 Extreme                | Desktop     | [16e67a28e4](https://linux-hardware.org/?probe=16e67a28e4) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [cb79c0ad47](https://linux-hardware.org/?probe=cb79c0ad47) | Feb 22, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [f2049b8af1](https://linux-hardware.org/?probe=f2049b8af1) | Feb 21, 2023 |
| Dell          | Latitude 5491               | Notebook    | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [ec5a8efdcd](https://linux-hardware.org/?probe=ec5a8efdcd) | Feb 21, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [c3ddf6d592](https://linux-hardware.org/?probe=c3ddf6d592) | Feb 21, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [bdcee122d3](https://linux-hardware.org/?probe=bdcee122d3) | Feb 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [88be67bbc1](https://linux-hardware.org/?probe=88be67bbc1) | Feb 21, 2023 |
| Lenovo        | ThinkPad R61 8933W4S        | Notebook    | [fec1a43d91](https://linux-hardware.org/?probe=fec1a43d91) | Feb 21, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [cc8628ae2c](https://linux-hardware.org/?probe=cc8628ae2c) | Feb 20, 2023 |
| Dell          | System XPS L502X            | Notebook    | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410s 2924W3S      | Notebook    | [24081de7f1](https://linux-hardware.org/?probe=24081de7f1) | Feb 20, 2023 |
| HP            | 620                         | Notebook    | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [5fc82de1e4](https://linux-hardware.org/?probe=5fc82de1e4) | Feb 20, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [a691e5fdbb](https://linux-hardware.org/?probe=a691e5fdbb) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | Notebook    | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [3ddfaa902f](https://linux-hardware.org/?probe=3ddfaa902f) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [14e85e829f](https://linux-hardware.org/?probe=14e85e829f) | Feb 20, 2023 |
| Dell          | Latitude E7270              | Notebook    | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cc8a99e630](https://linux-hardware.org/?probe=cc8a99e630) | Feb 20, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [7bc24845b3](https://linux-hardware.org/?probe=7bc24845b3) | Feb 20, 2023 |
| Dell          | 0NHNHP A01                  | Server      | [da74244bff](https://linux-hardware.org/?probe=da74244bff) | Feb 19, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [d6f20de9d5](https://linux-hardware.org/?probe=d6f20de9d5) | Feb 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b0fb49186](https://linux-hardware.org/?probe=7b0fb49186) | Feb 19, 2023 |
| Dell          | Vostro 5502                 | Notebook    | [49252b4695](https://linux-hardware.org/?probe=49252b4695) | Feb 19, 2023 |
| HP            | Unknown                     | Notebook    | [69b276cb01](https://linux-hardware.org/?probe=69b276cb01) | Feb 19, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [fe04dfeaac](https://linux-hardware.org/?probe=fe04dfeaac) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9d2009fd11](https://linux-hardware.org/?probe=9d2009fd11) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [238f636180](https://linux-hardware.org/?probe=238f636180) | Feb 18, 2023 |
| Dell          | 0PU052                      | Desktop     | [a460806b91](https://linux-hardware.org/?probe=a460806b91) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [28965259ad](https://linux-hardware.org/?probe=28965259ad) | Feb 18, 2023 |
| Dell          | Latitude 3520               | Notebook    | [8df8f4c6fc](https://linux-hardware.org/?probe=8df8f4c6fc) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [27958da7cc](https://linux-hardware.org/?probe=27958da7cc) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| MSI           | GL65 9SD                    | Notebook    | [a702514760](https://linux-hardware.org/?probe=a702514760) | Feb 17, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [be29883368](https://linux-hardware.org/?probe=be29883368) | Feb 17, 2023 |
| Dell          | Latitude 5491               | Notebook    | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| Dell          | Latitude 5511               | Notebook    | [5c3a80271b](https://linux-hardware.org/?probe=5c3a80271b) | Feb 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4a5c7432ae](https://linux-hardware.org/?probe=4a5c7432ae) | Feb 17, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [5201547dce](https://linux-hardware.org/?probe=5201547dce) | Feb 17, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a77d2c8a54](https://linux-hardware.org/?probe=a77d2c8a54) | Feb 17, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [8efdbecd75](https://linux-hardware.org/?probe=8efdbecd75) | Feb 17, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [af86e6cb72](https://linux-hardware.org/?probe=af86e6cb72) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | Notebook    | [c829d5ed74](https://linux-hardware.org/?probe=c829d5ed74) | Feb 16, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [c96e404e3f](https://linux-hardware.org/?probe=c96e404e3f) | Feb 16, 2023 |
| ASRock        | J3355M                      | Desktop     | [9118f960dd](https://linux-hardware.org/?probe=9118f960dd) | Feb 16, 2023 |
| Acer          | One S1003                   | Tablet      | [2d5943e055](https://linux-hardware.org/?probe=2d5943e055) | Feb 16, 2023 |
| Gigabyte      | EP35-DS4                    | Desktop     | [00d960f926](https://linux-hardware.org/?probe=00d960f926) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | Notebook    | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [a70040c510](https://linux-hardware.org/?probe=a70040c510) | Feb 16, 2023 |
| RTD Embedd... | CMA34CR                     | Notebook    | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ee1b786fd9](https://linux-hardware.org/?probe=ee1b786fd9) | Feb 15, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [5a6d751e4b](https://linux-hardware.org/?probe=5a6d751e4b) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [2be1a08ef2](https://linux-hardware.org/?probe=2be1a08ef2) | Feb 15, 2023 |
| MSI           | MS-7235                     | Desktop     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [ae4f47209a](https://linux-hardware.org/?probe=ae4f47209a) | Feb 15, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [59f88fb4d0](https://linux-hardware.org/?probe=59f88fb4d0) | Feb 15, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [f1c6e21bfb](https://linux-hardware.org/?probe=f1c6e21bfb) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [2c0799202c](https://linux-hardware.org/?probe=2c0799202c) | Feb 15, 2023 |
| GPU Compan... | GWTN141-4                   | Notebook    | [1492f5c475](https://linux-hardware.org/?probe=1492f5c475) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [1161e39e43](https://linux-hardware.org/?probe=1161e39e43) | Feb 15, 2023 |
| Dell          | System XPS L502X            | Notebook    | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [08b959d9ec](https://linux-hardware.org/?probe=08b959d9ec) | Feb 14, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [971fa91888](https://linux-hardware.org/?probe=971fa91888) | Feb 14, 2023 |
| Google        | Lillipup                    | Notebook    | [af7451beff](https://linux-hardware.org/?probe=af7451beff) | Feb 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [ec6afad108](https://linux-hardware.org/?probe=ec6afad108) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e474459ee0](https://linux-hardware.org/?probe=e474459ee0) | Feb 13, 2023 |
| Timi          | TM1613                      | Notebook    | [ce33c5c02e](https://linux-hardware.org/?probe=ce33c5c02e) | Feb 13, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [d132553080](https://linux-hardware.org/?probe=d132553080) | Feb 13, 2023 |
| Dell          | Latitude 5511               | Notebook    | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [f43f606f80](https://linux-hardware.org/?probe=f43f606f80) | Feb 13, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7eb2b7e26f](https://linux-hardware.org/?probe=7eb2b7e26f) | Feb 13, 2023 |
| HP            | 3397                        | Desktop     | [83dc4a9ea0](https://linux-hardware.org/?probe=83dc4a9ea0) | Feb 13, 2023 |
| HP            | 3397                        | Desktop     | [cc7019baaa](https://linux-hardware.org/?probe=cc7019baaa) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [36a0d5221f](https://linux-hardware.org/?probe=36a0d5221f) | Feb 13, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1LM0... | Notebook    | [8ee6dd00d1](https://linux-hardware.org/?probe=8ee6dd00d1) | Feb 12, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [5120a4cdb5](https://linux-hardware.org/?probe=5120a4cdb5) | Feb 12, 2023 |
| HP            | 3397                        | Desktop     | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| HP            | 3397                        | Desktop     | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | Notebook    | [682be07637](https://linux-hardware.org/?probe=682be07637) | Feb 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [081d9e5294](https://linux-hardware.org/?probe=081d9e5294) | Feb 11, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d8a854baec](https://linux-hardware.org/?probe=d8a854baec) | Feb 11, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6c1d31a394](https://linux-hardware.org/?probe=6c1d31a394) | Feb 10, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [e995a466a1](https://linux-hardware.org/?probe=e995a466a1) | Feb 10, 2023 |
| Dell          | 04YJ19 A00                  | Desktop     | [972fb9a299](https://linux-hardware.org/?probe=972fb9a299) | Feb 10, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [b6239c152e](https://linux-hardware.org/?probe=b6239c152e) | Feb 10, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad T530 2429MY2       | Notebook    | [9b5ffc7c58](https://linux-hardware.org/?probe=9b5ffc7c58) | Feb 09, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [38f4064394](https://linux-hardware.org/?probe=38f4064394) | Feb 09, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [8885828bb8](https://linux-hardware.org/?probe=8885828bb8) | Feb 09, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f669c49cf5](https://linux-hardware.org/?probe=f669c49cf5) | Feb 09, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [ddaad5aa0d](https://linux-hardware.org/?probe=ddaad5aa0d) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | Desktop     | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| Intel         | DG31PR AAD97573-301         | Desktop     | [665f8e7d81](https://linux-hardware.org/?probe=665f8e7d81) | Feb 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [26cb195bab](https://linux-hardware.org/?probe=26cb195bab) | Feb 08, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [c71dba27f2](https://linux-hardware.org/?probe=c71dba27f2) | Feb 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [2b4bc22652](https://linux-hardware.org/?probe=2b4bc22652) | Feb 08, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [842956e023](https://linux-hardware.org/?probe=842956e023) | Feb 08, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [086ea7a0e6](https://linux-hardware.org/?probe=086ea7a0e6) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| Dell          | 0DR845                      | Desktop     | [537252420b](https://linux-hardware.org/?probe=537252420b) | Feb 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [c9c89084e8](https://linux-hardware.org/?probe=c9c89084e8) | Feb 07, 2023 |
| Dell          | Latitude E4300              | Notebook    | [aaad0477e4](https://linux-hardware.org/?probe=aaad0477e4) | Feb 07, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [307d491fc8](https://linux-hardware.org/?probe=307d491fc8) | Feb 07, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | Desktop     | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | DG31PR AAD97573-301         | Desktop     | [2080f0edf4](https://linux-hardware.org/?probe=2080f0edf4) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | Latitude 3520               | Notebook    | [d7569fa081](https://linux-hardware.org/?probe=d7569fa081) | Feb 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [edc8beac1f](https://linux-hardware.org/?probe=edc8beac1f) | Feb 06, 2023 |
| Dell          | Latitude 5511               | Notebook    | [57e8ce4f20](https://linux-hardware.org/?probe=57e8ce4f20) | Feb 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| Huanan        | X99-T8D V1.2                | Desktop     | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [e8c0f3b7de](https://linux-hardware.org/?probe=e8c0f3b7de) | Feb 05, 2023 |
| MSI           | H410M-A PRO                 | Desktop     | [6ac747c27e](https://linux-hardware.org/?probe=6ac747c27e) | Feb 05, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [eb5a23a73b](https://linux-hardware.org/?probe=eb5a23a73b) | Feb 05, 2023 |
| Dell          | 02P9X9 A05                  | Server      | [fb8900f061](https://linux-hardware.org/?probe=fb8900f061) | Feb 05, 2023 |
| Dell          | 0PM2CW A02                  | Server      | [9c7291ae7e](https://linux-hardware.org/?probe=9c7291ae7e) | Feb 05, 2023 |
| HP            | 3397                        | Desktop     | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | Desktop     | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| HP            | 8054                        | Desktop     | [c709653825](https://linux-hardware.org/?probe=c709653825) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [dbef2c679a](https://linux-hardware.org/?probe=dbef2c679a) | Feb 05, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0837ce8a0f](https://linux-hardware.org/?probe=0837ce8a0f) | Feb 05, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [eb399b4ffa](https://linux-hardware.org/?probe=eb399b4ffa) | Feb 05, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [403785d1ec](https://linux-hardware.org/?probe=403785d1ec) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [14fb68ece0](https://linux-hardware.org/?probe=14fb68ece0) | Feb 05, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [854b52f85c](https://linux-hardware.org/?probe=854b52f85c) | Feb 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d6adca1255](https://linux-hardware.org/?probe=d6adca1255) | Feb 04, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [6e8ab1a5cb](https://linux-hardware.org/?probe=6e8ab1a5cb) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [4f1125bc93](https://linux-hardware.org/?probe=4f1125bc93) | Feb 04, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [a385ff6f36](https://linux-hardware.org/?probe=a385ff6f36) | Feb 04, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [54a305f83e](https://linux-hardware.org/?probe=54a305f83e) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [c6dae92093](https://linux-hardware.org/?probe=c6dae92093) | Feb 03, 2023 |
| ASUSTek       | 1101HA                      | Notebook    | [28cb433eb0](https://linux-hardware.org/?probe=28cb433eb0) | Feb 03, 2023 |
| Dell          | Latitude 5480               | Notebook    | [da9f98059c](https://linux-hardware.org/?probe=da9f98059c) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [9c5cfbc1a1](https://linux-hardware.org/?probe=9c5cfbc1a1) | Feb 03, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [203d5736d7](https://linux-hardware.org/?probe=203d5736d7) | Feb 03, 2023 |
| HP            | 212B                        | Desktop     | [f27b5c4aa0](https://linux-hardware.org/?probe=f27b5c4aa0) | Feb 03, 2023 |
| HP            | Unknown                     | Notebook    | [4b28efe30c](https://linux-hardware.org/?probe=4b28efe30c) | Feb 03, 2023 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [a4a3ea0e4e](https://linux-hardware.org/?probe=a4a3ea0e4e) | Feb 02, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [4b1dc3d64b](https://linux-hardware.org/?probe=4b1dc3d64b) | Feb 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [5ab474163a](https://linux-hardware.org/?probe=5ab474163a) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [1c6ed7ede6](https://linux-hardware.org/?probe=1c6ed7ede6) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [6b007d74de](https://linux-hardware.org/?probe=6b007d74de) | Feb 02, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [f04d195965](https://linux-hardware.org/?probe=f04d195965) | Feb 02, 2023 |
| MSI           | GV62 7RD                    | Notebook    | [c22fffb4e9](https://linux-hardware.org/?probe=c22fffb4e9) | Feb 02, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [c8ee9be68c](https://linux-hardware.org/?probe=c8ee9be68c) | Feb 02, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [ac6a930ffc](https://linux-hardware.org/?probe=ac6a930ffc) | Feb 02, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [de152b340c](https://linux-hardware.org/?probe=de152b340c) | Feb 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d515d5d9f7](https://linux-hardware.org/?probe=d515d5d9f7) | Feb 01, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [62f941075c](https://linux-hardware.org/?probe=62f941075c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [c936c07925](https://linux-hardware.org/?probe=c936c07925) | Jan 31, 2023 |
| Dell          | Latitude 5410               | Notebook    | [717012530d](https://linux-hardware.org/?probe=717012530d) | Jan 31, 2023 |
| Unknown       | Unknown                     | Notebook    | [e6c824b966](https://linux-hardware.org/?probe=e6c824b966) | Jan 31, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [360dc83e04](https://linux-hardware.org/?probe=360dc83e04) | Jan 31, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [aaaa563786](https://linux-hardware.org/?probe=aaaa563786) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [e335e7282d](https://linux-hardware.org/?probe=e335e7282d) | Jan 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [d1e99e3f04](https://linux-hardware.org/?probe=d1e99e3f04) | Jan 30, 2023 |
| Toshiba       | Satellite P750              | Notebook    | [1cc0f342b5](https://linux-hardware.org/?probe=1cc0f342b5) | Jan 30, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [4cb11c2a78](https://linux-hardware.org/?probe=4cb11c2a78) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | Notebook    | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Inspiron 5758               | Notebook    | [de58233dca](https://linux-hardware.org/?probe=de58233dca) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ee87ac218f](https://linux-hardware.org/?probe=ee87ac218f) | Jan 30, 2023 |
| Dell          | Latitude 5480               | Notebook    | [3cbac640e1](https://linux-hardware.org/?probe=3cbac640e1) | Jan 30, 2023 |
| HP            | 8054                        | Desktop     | [f2367fdcda](https://linux-hardware.org/?probe=f2367fdcda) | Jan 30, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [81717ed3df](https://linux-hardware.org/?probe=81717ed3df) | Jan 30, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a2c721748](https://linux-hardware.org/?probe=5a2c721748) | Jan 30, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [56622f5d6c](https://linux-hardware.org/?probe=56622f5d6c) | Jan 29, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [e5af375b93](https://linux-hardware.org/?probe=e5af375b93) | Jan 29, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [41d67fcba8](https://linux-hardware.org/?probe=41d67fcba8) | Jan 29, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [1a2fb44fac](https://linux-hardware.org/?probe=1a2fb44fac) | Jan 29, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| ASUSTek       | 1215B                       | Notebook    | [8d26a8d157](https://linux-hardware.org/?probe=8d26a8d157) | Jan 28, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f4aefcd670](https://linux-hardware.org/?probe=f4aefcd670) | Jan 28, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [cf4086f3e4](https://linux-hardware.org/?probe=cf4086f3e4) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [f6d7ba9d48](https://linux-hardware.org/?probe=f6d7ba9d48) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ff5e2b673e](https://linux-hardware.org/?probe=ff5e2b673e) | Jan 27, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| ASUSTek       | X540SA                      | Notebook    | [93aed28230](https://linux-hardware.org/?probe=93aed28230) | Jan 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9001ac4e36](https://linux-hardware.org/?probe=9001ac4e36) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| HP            | x2 210 G2                   | Tablet      | [863136882e](https://linux-hardware.org/?probe=863136882e) | Jan 26, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [af3748a4f0](https://linux-hardware.org/?probe=af3748a4f0) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| HP            | 8054                        | Desktop     | [864f5f225e](https://linux-hardware.org/?probe=864f5f225e) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | Notebook    | [e4ddea6092](https://linux-hardware.org/?probe=e4ddea6092) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [4811286faf](https://linux-hardware.org/?probe=4811286faf) | Jan 26, 2023 |
| Dell          | XPS 9320                    | Notebook    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [baae797a05](https://linux-hardware.org/?probe=baae797a05) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [427a7fa0cb](https://linux-hardware.org/?probe=427a7fa0cb) | Jan 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [7fcc3fb992](https://linux-hardware.org/?probe=7fcc3fb992) | Jan 25, 2023 |
| HP            | 3048h                       | Desktop     | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| Samsung       | R710                        | Notebook    | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| Dell          | Latitude E6520              | Notebook    | [baf618d1a1](https://linux-hardware.org/?probe=baf618d1a1) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | Desktop     | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| Dell          | Latitude E6520              | Notebook    | [615879d5e9](https://linux-hardware.org/?probe=615879d5e9) | Jan 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | Notebook    | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [5ddcb9f78b](https://linux-hardware.org/?probe=5ddcb9f78b) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [9fcf89ea7c](https://linux-hardware.org/?probe=9fcf89ea7c) | Jan 23, 2023 |
| Dell          | Latitude E6500              | Notebook    | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [c5da4a997d](https://linux-hardware.org/?probe=c5da4a997d) | Jan 23, 2023 |
| MSI           | B150 PC MATE                | Desktop     | [741901eb8f](https://linux-hardware.org/?probe=741901eb8f) | Jan 23, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [ffe1ffc80e](https://linux-hardware.org/?probe=ffe1ffc80e) | Jan 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c2f89a9e58](https://linux-hardware.org/?probe=c2f89a9e58) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [076a3479fa](https://linux-hardware.org/?probe=076a3479fa) | Jan 22, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [f3d47cfb62](https://linux-hardware.org/?probe=f3d47cfb62) | Jan 22, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [d251029940](https://linux-hardware.org/?probe=d251029940) | Jan 22, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [d3686f2fc3](https://linux-hardware.org/?probe=d3686f2fc3) | Jan 21, 2023 |
| Dell          | Latitude 9420               | Notebook    | [4b847961df](https://linux-hardware.org/?probe=4b847961df) | Jan 21, 2023 |
| Dell          | Latitude 5501               | Notebook    | [72581be7e7](https://linux-hardware.org/?probe=72581be7e7) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| HP            | Pavilion dv5                | Notebook    | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [b341182acd](https://linux-hardware.org/?probe=b341182acd) | Jan 20, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [9b4b20b28d](https://linux-hardware.org/?probe=9b4b20b28d) | Jan 20, 2023 |
| Lenovo        | ThinkPad P51 20HJS1EJ1B     | Notebook    | [2ac4b56c2f](https://linux-hardware.org/?probe=2ac4b56c2f) | Jan 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [6c55213012](https://linux-hardware.org/?probe=6c55213012) | Jan 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f935f0c7b](https://linux-hardware.org/?probe=1f935f0c7b) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| Dell          | Precision M6600             | Notebook    | [4d697ebfd5](https://linux-hardware.org/?probe=4d697ebfd5) | Jan 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6b5c46a680](https://linux-hardware.org/?probe=6b5c46a680) | Jan 19, 2023 |
| Huanan        | X99-TF V2.0                 | Desktop     | [3fa0103359](https://linux-hardware.org/?probe=3fa0103359) | Jan 19, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [a993e95dde](https://linux-hardware.org/?probe=a993e95dde) | Jan 19, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [1fd7f0acb7](https://linux-hardware.org/?probe=1fd7f0acb7) | Jan 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [16f5041f1d](https://linux-hardware.org/?probe=16f5041f1d) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | Desktop     | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [30698dacda](https://linux-hardware.org/?probe=30698dacda) | Jan 19, 2023 |
| Dell          | Latitude 9420               | Notebook    | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Alienware     | M17xR4                      | Notebook    | [5cce1e5932](https://linux-hardware.org/?probe=5cce1e5932) | Jan 18, 2023 |
| Dell          | 0Y3R3K A00                  | Desktop     | [f2164a9c60](https://linux-hardware.org/?probe=f2164a9c60) | Jan 18, 2023 |
| Dell          | Precision 5750              | Notebook    | [592f9624d3](https://linux-hardware.org/?probe=592f9624d3) | Jan 18, 2023 |
| MSI           | GP65 Leopard 10SFK          | Notebook    | [3c09479564](https://linux-hardware.org/?probe=3c09479564) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [2ad3913a19](https://linux-hardware.org/?probe=2ad3913a19) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [6f463ee96b](https://linux-hardware.org/?probe=6f463ee96b) | Jan 18, 2023 |
| Dell          | Latitude D630               | Notebook    | [0d267a0217](https://linux-hardware.org/?probe=0d267a0217) | Jan 17, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [03a01ae5f7](https://linux-hardware.org/?probe=03a01ae5f7) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | Notebook    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | Notebook    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [aa6ca0d358](https://linux-hardware.org/?probe=aa6ca0d358) | Jan 17, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [267ce15a0c](https://linux-hardware.org/?probe=267ce15a0c) | Jan 17, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [79b74ef79b](https://linux-hardware.org/?probe=79b74ef79b) | Jan 16, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [11ca9b863c](https://linux-hardware.org/?probe=11ca9b863c) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [c159b4d65b](https://linux-hardware.org/?probe=c159b4d65b) | Jan 16, 2023 |
| Dell          | Latitude 3190               | Notebook    | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [94ba7a4ca6](https://linux-hardware.org/?probe=94ba7a4ca6) | Jan 16, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [be77d8e20d](https://linux-hardware.org/?probe=be77d8e20d) | Jan 15, 2023 |
| Lenovo        | ThinkPad T510 4384FF3       | Notebook    | [b62dac21bd](https://linux-hardware.org/?probe=b62dac21bd) | Jan 15, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [a1c627f81a](https://linux-hardware.org/?probe=a1c627f81a) | Jan 15, 2023 |
| Chuwi         | AeroBook Pro                | Notebook    | [13da35b0f7](https://linux-hardware.org/?probe=13da35b0f7) | Jan 15, 2023 |
| ASUSTek       | X510UQR                     | Notebook    | [2fb1d0a04c](https://linux-hardware.org/?probe=2fb1d0a04c) | Jan 14, 2023 |
| Acer          | AO725                       | Notebook    | [739986d5fa](https://linux-hardware.org/?probe=739986d5fa) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [f5499bf32a](https://linux-hardware.org/?probe=f5499bf32a) | Jan 14, 2023 |
| Gigabyte      | Z97M-D3H                    | Desktop     | [305ff29dad](https://linux-hardware.org/?probe=305ff29dad) | Jan 14, 2023 |
| Lenovo        | G585                        | Notebook    | [c7453a5e19](https://linux-hardware.org/?probe=c7453a5e19) | Jan 14, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [5e408d7d3d](https://linux-hardware.org/?probe=5e408d7d3d) | Jan 14, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3f68ef3681](https://linux-hardware.org/?probe=3f68ef3681) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [6cc45bde0b](https://linux-hardware.org/?probe=6cc45bde0b) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Samsung       | SR700                       | Notebook    | [329a7864c0](https://linux-hardware.org/?probe=329a7864c0) | Jan 13, 2023 |
| HP            | Notebook                    | Notebook    | [3fc38fa55e](https://linux-hardware.org/?probe=3fc38fa55e) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eeeb041ca6](https://linux-hardware.org/?probe=eeeb041ca6) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | Notebook    | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [3dcb242fd6](https://linux-hardware.org/?probe=3dcb242fd6) | Jan 12, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [8dce1e9fdd](https://linux-hardware.org/?probe=8dce1e9fdd) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| Lenovo        | Legion Y740S-15IMH 81YX     | Notebook    | [b61eb04be5](https://linux-hardware.org/?probe=b61eb04be5) | Jan 11, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [366e5b92d7](https://linux-hardware.org/?probe=366e5b92d7) | Jan 11, 2023 |
| Sony          | VPCEJ2S1E                   | Notebook    | [f387a3dcf6](https://linux-hardware.org/?probe=f387a3dcf6) | Jan 11, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [e3478b20bd](https://linux-hardware.org/?probe=e3478b20bd) | Jan 11, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [78153a929d](https://linux-hardware.org/?probe=78153a929d) | Jan 11, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [f3fe7611d3](https://linux-hardware.org/?probe=f3fe7611d3) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [140d48870a](https://linux-hardware.org/?probe=140d48870a) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [f6588e6319](https://linux-hardware.org/?probe=f6588e6319) | Jan 11, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [c6ffd59fb2](https://linux-hardware.org/?probe=c6ffd59fb2) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b828defe64](https://linux-hardware.org/?probe=b828defe64) | Jan 11, 2023 |
| Dell          | Latitude D630               | Notebook    | [64877fdf78](https://linux-hardware.org/?probe=64877fdf78) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [2aa757ef35](https://linux-hardware.org/?probe=2aa757ef35) | Jan 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [eefd133e1f](https://linux-hardware.org/?probe=eefd133e1f) | Jan 10, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [33529c6c45](https://linux-hardware.org/?probe=33529c6c45) | Jan 10, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6bddd00c3f](https://linux-hardware.org/?probe=6bddd00c3f) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| Dell          | Latitude E4310              | Notebook    | [1cd2d3300a](https://linux-hardware.org/?probe=1cd2d3300a) | Jan 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [41c1a02ca6](https://linux-hardware.org/?probe=41c1a02ca6) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| Lenovo        | ThinkPad X201 3626D15       | Notebook    | [3d615a1b12](https://linux-hardware.org/?probe=3d615a1b12) | Jan 09, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [045695f1d5](https://linux-hardware.org/?probe=045695f1d5) | Jan 09, 2023 |
| Dell          | 088DT1 A00                  | Desktop     | [f7632cc6ba](https://linux-hardware.org/?probe=f7632cc6ba) | Jan 09, 2023 |
| Dell          | Latitude 3190               | Notebook    | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| Dell          | Latitude 7330               | Convertible | [02cef1bed5](https://linux-hardware.org/?probe=02cef1bed5) | Jan 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [aac6fb4537](https://linux-hardware.org/?probe=aac6fb4537) | Jan 09, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| Samsung       | R780/R778                   | Notebook    | [e26d6dd084](https://linux-hardware.org/?probe=e26d6dd084) | Jan 08, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| Lenovo        | G51-35 80M8                 | Notebook    | [fe19098e1d](https://linux-hardware.org/?probe=fe19098e1d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS0BX0T    | Notebook    | [e05bd2254f](https://linux-hardware.org/?probe=e05bd2254f) | Jan 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [de3c61df29](https://linux-hardware.org/?probe=de3c61df29) | Jan 08, 2023 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [9bbe57d371](https://linux-hardware.org/?probe=9bbe57d371) | Jan 08, 2023 |
| HP            | 655                         | Notebook    | [4c7544d7ad](https://linux-hardware.org/?probe=4c7544d7ad) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [c0c15dd0d0](https://linux-hardware.org/?probe=c0c15dd0d0) | Jan 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [459862f611](https://linux-hardware.org/?probe=459862f611) | Jan 08, 2023 |
| ZOTAC         | ZBOX-MI623/MI643 Rev.00     | Mini pc     | [9750302f80](https://linux-hardware.org/?probe=9750302f80) | Jan 07, 2023 |
| HP            | ENVY m6                     | Notebook    | [b5089c7b29](https://linux-hardware.org/?probe=b5089c7b29) | Jan 07, 2023 |
| MSI           | MS-AC7B1 100                | All in one  | [7df138e48a](https://linux-hardware.org/?probe=7df138e48a) | Jan 07, 2023 |
| HP            | ProBook 5330m               | Notebook    | [37416931cd](https://linux-hardware.org/?probe=37416931cd) | Jan 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0f51a2d7d5](https://linux-hardware.org/?probe=0f51a2d7d5) | Jan 07, 2023 |
| Gigabyte      | Z97X-UD5H-BK                | Desktop     | [531eaa88b5](https://linux-hardware.org/?probe=531eaa88b5) | Jan 07, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| MSI           | Z590 PRO WIFI               | Desktop     | [98af54429b](https://linux-hardware.org/?probe=98af54429b) | Jan 07, 2023 |
| Lenovo        | S145-15API 81UT             | Notebook    | [fafc9e3fb7](https://linux-hardware.org/?probe=fafc9e3fb7) | Jan 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [fd20c9e982](https://linux-hardware.org/?probe=fd20c9e982) | Jan 07, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | Desktop     | [e59b16e379](https://linux-hardware.org/?probe=e59b16e379) | Jan 06, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e0e6ab58b6](https://linux-hardware.org/?probe=e0e6ab58b6) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Dell          | Latitude E6520              | Notebook    | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [d0299b2518](https://linux-hardware.org/?probe=d0299b2518) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [bb78c165c7](https://linux-hardware.org/?probe=bb78c165c7) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [117e9ffed7](https://linux-hardware.org/?probe=117e9ffed7) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [cacdaaf5c5](https://linux-hardware.org/?probe=cacdaaf5c5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | Notebook    | [bbedda14e5](https://linux-hardware.org/?probe=bbedda14e5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | Notebook    | [d2c2a681a2](https://linux-hardware.org/?probe=d2c2a681a2) | Jan 05, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [e0cf0ea368](https://linux-hardware.org/?probe=e0cf0ea368) | Jan 05, 2023 |
| Dell          | 0Y3R3K A00                  | Desktop     | [8337b0691c](https://linux-hardware.org/?probe=8337b0691c) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| ASUSTek       | K55VM                       | Notebook    | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [307c51149d](https://linux-hardware.org/?probe=307c51149d) | Jan 03, 2023 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [96150fc8a5](https://linux-hardware.org/?probe=96150fc8a5) | Jan 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1a3964dd30](https://linux-hardware.org/?probe=1a3964dd30) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [bd3d76fa53](https://linux-hardware.org/?probe=bd3d76fa53) | Jan 03, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [b45f76c172](https://linux-hardware.org/?probe=b45f76c172) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| HP            | 304Bh                       | Desktop     | [cfe1407faf](https://linux-hardware.org/?probe=cfe1407faf) | Jan 02, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [eb3f1a0f5f](https://linux-hardware.org/?probe=eb3f1a0f5f) | Jan 02, 2023 |
| Dell          | Latitude 3190               | Notebook    | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | Notebook    | [c331237e28](https://linux-hardware.org/?probe=c331237e28) | Jan 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [92052e9c47](https://linux-hardware.org/?probe=92052e9c47) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | Notebook    | [1ce680cb4d](https://linux-hardware.org/?probe=1ce680cb4d) | Jan 01, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [24d32a2b05](https://linux-hardware.org/?probe=24d32a2b05) | Jan 01, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [8c4c07c555](https://linux-hardware.org/?probe=8c4c07c555) | Jan 01, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [0a4b320a9e](https://linux-hardware.org/?probe=0a4b320a9e) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9a05e8c413](https://linux-hardware.org/?probe=9a05e8c413) | Dec 30, 2022 |
| HP            | EliteBook 745 G5            | Notebook    | [d819dbd901](https://linux-hardware.org/?probe=d819dbd901) | Dec 30, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [ca7468f975](https://linux-hardware.org/?probe=ca7468f975) | Dec 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9b264f00f0](https://linux-hardware.org/?probe=9b264f00f0) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [fdb09844e9](https://linux-hardware.org/?probe=fdb09844e9) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [9ff3461c31](https://linux-hardware.org/?probe=9ff3461c31) | Dec 29, 2022 |
| Dell          | Latitude E6420              | Notebook    | [9733c425b6](https://linux-hardware.org/?probe=9733c425b6) | Dec 29, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [e232c2de6d](https://linux-hardware.org/?probe=e232c2de6d) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [95555948a2](https://linux-hardware.org/?probe=95555948a2) | Dec 27, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [06cba3f478](https://linux-hardware.org/?probe=06cba3f478) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [031a62faa8](https://linux-hardware.org/?probe=031a62faa8) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [02f55ff55b](https://linux-hardware.org/?probe=02f55ff55b) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [e0a09344e0](https://linux-hardware.org/?probe=e0a09344e0) | Dec 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5d2498f405](https://linux-hardware.org/?probe=5d2498f405) | Dec 26, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [05163a2fb9](https://linux-hardware.org/?probe=05163a2fb9) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [d6948e7207](https://linux-hardware.org/?probe=d6948e7207) | Dec 26, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [315cef73cd](https://linux-hardware.org/?probe=315cef73cd) | Dec 25, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [249f50d430](https://linux-hardware.org/?probe=249f50d430) | Dec 25, 2022 |
| Lenovo        | ThinkPad T430 23472Y0       | Notebook    | [4a2d13391c](https://linux-hardware.org/?probe=4a2d13391c) | Dec 25, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [5ca8ddb512](https://linux-hardware.org/?probe=5ca8ddb512) | Dec 24, 2022 |
| Xiaomi        | Pocophone F1 (Tianma)       | Soc         | [85b5b184bb](https://linux-hardware.org/?probe=85b5b184bb) | Dec 24, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [38ed4755c3](https://linux-hardware.org/?probe=38ed4755c3) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [0836c3b800](https://linux-hardware.org/?probe=0836c3b800) | Dec 23, 2022 |
| MSI           | Z270 TOMAHAWK               | Desktop     | [b721ac26e2](https://linux-hardware.org/?probe=b721ac26e2) | Dec 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c17fe8cbe0](https://linux-hardware.org/?probe=c17fe8cbe0) | Dec 23, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0277928378](https://linux-hardware.org/?probe=0277928378) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [bf600b6f1c](https://linux-hardware.org/?probe=bf600b6f1c) | Dec 22, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [0cb3ccf545](https://linux-hardware.org/?probe=0cb3ccf545) | Dec 21, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9ada5592f6](https://linux-hardware.org/?probe=9ada5592f6) | Dec 21, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [06d78a17c1](https://linux-hardware.org/?probe=06d78a17c1) | Dec 21, 2022 |
| Dell          | Precision 3520              | Notebook    | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | Notebook    | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | 8266                        | Desktop     | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [b1d6a6a73d](https://linux-hardware.org/?probe=b1d6a6a73d) | Dec 21, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [243fccb6fa](https://linux-hardware.org/?probe=243fccb6fa) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [bbec56fa90](https://linux-hardware.org/?probe=bbec56fa90) | Dec 21, 2022 |
| Dell          | G15 5510                    | Notebook    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming FX505GE          | Notebook    | [094e72dc22](https://linux-hardware.org/?probe=094e72dc22) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [37513092d6](https://linux-hardware.org/?probe=37513092d6) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [70a0e2a296](https://linux-hardware.org/?probe=70a0e2a296) | Dec 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [44a96b54b6](https://linux-hardware.org/?probe=44a96b54b6) | Dec 18, 2022 |
| HP            | ProLiant ML350 G6           | Desktop     | [58113862ee](https://linux-hardware.org/?probe=58113862ee) | Dec 18, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [8c0c2353ab](https://linux-hardware.org/?probe=8c0c2353ab) | Dec 18, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [85d6221160](https://linux-hardware.org/?probe=85d6221160) | Dec 18, 2022 |
| Foxconn       | A76GMV                      | Desktop     | [722a9911f8](https://linux-hardware.org/?probe=722a9911f8) | Dec 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [72f897b9d3](https://linux-hardware.org/?probe=72f897b9d3) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| Dell          | Latitude E5570              | Notebook    | [cc58177561](https://linux-hardware.org/?probe=cc58177561) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| POSIFLEX      | KK-3703 D0                  | Desktop     | [8ce9910b00](https://linux-hardware.org/?probe=8ce9910b00) | Dec 16, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1860105d14](https://linux-hardware.org/?probe=1860105d14) | Dec 16, 2022 |
| Dell          | Latitude E6410              | Notebook    | [173f8a8dc8](https://linux-hardware.org/?probe=173f8a8dc8) | Dec 16, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| Dell          | Latitude 7330               | Convertible | [b3956235ae](https://linux-hardware.org/?probe=b3956235ae) | Dec 15, 2022 |
| Dell          | Latitude 5420               | Notebook    | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | Notebook    | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [f0e99676be](https://linux-hardware.org/?probe=f0e99676be) | Dec 14, 2022 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [6b53aab624](https://linux-hardware.org/?probe=6b53aab624) | Dec 14, 2022 |
| Google        | Ultima                      | Notebook    | [867abc2b8f](https://linux-hardware.org/?probe=867abc2b8f) | Dec 14, 2022 |
| ASUSTek       | M3N                         | Notebook    | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [de7f9d5e33](https://linux-hardware.org/?probe=de7f9d5e33) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [a607679697](https://linux-hardware.org/?probe=a607679697) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [9bd8fecf82](https://linux-hardware.org/?probe=9bd8fecf82) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | Desktop     | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| Dell          | XPS L501X                   | Notebook    | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | Notebook    | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| ASUSTek       | M3N                         | Notebook    | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [37284f659a](https://linux-hardware.org/?probe=37284f659a) | Dec 13, 2022 |
| Dell          | Latitude 7330               | Convertible | [95aea2b219](https://linux-hardware.org/?probe=95aea2b219) | Dec 12, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [61685b4f1a](https://linux-hardware.org/?probe=61685b4f1a) | Dec 12, 2022 |
| Dell          | Latitude 5411               | Notebook    | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Dell          | Latitude 5411               | Notebook    | [334ca886a4](https://linux-hardware.org/?probe=334ca886a4) | Dec 12, 2022 |
| HP            | Pavilion dv7                | Notebook    | [1e10e0306f](https://linux-hardware.org/?probe=1e10e0306f) | Dec 12, 2022 |
| Dell          | Latitude 7330               | Convertible | [3bd7f5734d](https://linux-hardware.org/?probe=3bd7f5734d) | Dec 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [177dded9e0](https://linux-hardware.org/?probe=177dded9e0) | Dec 12, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [c94af57999](https://linux-hardware.org/?probe=c94af57999) | Dec 11, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [cea4c76b9d](https://linux-hardware.org/?probe=cea4c76b9d) | Dec 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [ffb030fbbf](https://linux-hardware.org/?probe=ffb030fbbf) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [50ccab1267](https://linux-hardware.org/?probe=50ccab1267) | Dec 10, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [fe9424a1f0](https://linux-hardware.org/?probe=fe9424a1f0) | Dec 09, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Dell          | Latitude 7330               | Convertible | [67bbcec9fd](https://linux-hardware.org/?probe=67bbcec9fd) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | Desktop     | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [b9e3c45caa](https://linux-hardware.org/?probe=b9e3c45caa) | Dec 09, 2022 |
| Dell          | 0PM2CW A02                  | Server      | [460791d797](https://linux-hardware.org/?probe=460791d797) | Dec 08, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [93075de512](https://linux-hardware.org/?probe=93075de512) | Dec 08, 2022 |
| MSI           | Vector GP76 12UGS           | Notebook    | [d6c55a874f](https://linux-hardware.org/?probe=d6c55a874f) | Dec 08, 2022 |
| Google        | Glimmer                     | Notebook    | [ad4b3f5575](https://linux-hardware.org/?probe=ad4b3f5575) | Dec 08, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e15b555b1a](https://linux-hardware.org/?probe=e15b555b1a) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Dell          | Latitude 5480               | Notebook    | [0cd7d6e4c0](https://linux-hardware.org/?probe=0cd7d6e4c0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | Notebook    | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude E7440              | Notebook    | [9a859c9a5d](https://linux-hardware.org/?probe=9a859c9a5d) | Dec 06, 2022 |
| Dell          | Latitude 5310               | Notebook    | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| Dell          | Latitude E7440              | Notebook    | [63b84a9439](https://linux-hardware.org/?probe=63b84a9439) | Dec 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e64c5d7bdc](https://linux-hardware.org/?probe=e64c5d7bdc) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [798cf690c5](https://linux-hardware.org/?probe=798cf690c5) | Dec 06, 2022 |
| Dell          | Latitude 5411               | Notebook    | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | Notebook    | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | Notebook    | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [091b8a3a8a](https://linux-hardware.org/?probe=091b8a3a8a) | Dec 05, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [aadffecf5b](https://linux-hardware.org/?probe=aadffecf5b) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [119ec75a5f](https://linux-hardware.org/?probe=119ec75a5f) | Dec 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | Desktop     | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [a849daba2b](https://linux-hardware.org/?probe=a849daba2b) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [6c726b6eb7](https://linux-hardware.org/?probe=6c726b6eb7) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [99b35ee6a3](https://linux-hardware.org/?probe=99b35ee6a3) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7a47529fdc](https://linux-hardware.org/?probe=7a47529fdc) | Dec 04, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | Notebook    | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [afbbf473b9](https://linux-hardware.org/?probe=afbbf473b9) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | Desktop     | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| pine64,roc... | RockPro64 v2.1              | Soc         | [9973baf711](https://linux-hardware.org/?probe=9973baf711) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | Desktop     | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| HP            | Pavilion dv7                | Notebook    | [90c7688386](https://linux-hardware.org/?probe=90c7688386) | Dec 04, 2022 |
| Google        | Lars                        | Notebook    | [efe9cef4b9](https://linux-hardware.org/?probe=efe9cef4b9) | Dec 04, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0455f2c685](https://linux-hardware.org/?probe=0455f2c685) | Dec 04, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [84a50cd483](https://linux-hardware.org/?probe=84a50cd483) | Dec 03, 2022 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [10315500be](https://linux-hardware.org/?probe=10315500be) | Dec 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f8dacfeca3](https://linux-hardware.org/?probe=f8dacfeca3) | Dec 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [ec5047129a](https://linux-hardware.org/?probe=ec5047129a) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Google        | Lars                        | Notebook    | [ad022bfd93](https://linux-hardware.org/?probe=ad022bfd93) | Dec 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6578471259](https://linux-hardware.org/?probe=6578471259) | Dec 03, 2022 |
| Dell          | G15 5515                    | Notebook    | [218e5c2825](https://linux-hardware.org/?probe=218e5c2825) | Dec 03, 2022 |
| Dell          | Latitude 5480               | Notebook    | [4eba5810d7](https://linux-hardware.org/?probe=4eba5810d7) | Dec 03, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [bf8f5e2683](https://linux-hardware.org/?probe=bf8f5e2683) | Dec 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9990900d63](https://linux-hardware.org/?probe=9990900d63) | Dec 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7177c55be0](https://linux-hardware.org/?probe=7177c55be0) | Dec 02, 2022 |
| Dell          | Vostro 5502                 | Notebook    | [86341e8306](https://linux-hardware.org/?probe=86341e8306) | Dec 02, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| HP            | 0A98h                       | Desktop     | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4d33c2ab30](https://linux-hardware.org/?probe=4d33c2ab30) | Dec 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [8a25bf4545](https://linux-hardware.org/?probe=8a25bf4545) | Dec 01, 2022 |
| HP            | 0A98h                       | Desktop     | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| HP            | Pavilion dv7                | Notebook    | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [dd124e3579](https://linux-hardware.org/?probe=dd124e3579) | Nov 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [a5b34b67f2](https://linux-hardware.org/?probe=a5b34b67f2) | Nov 30, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [3aa3302b92](https://linux-hardware.org/?probe=3aa3302b92) | Nov 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c3d55f501c](https://linux-hardware.org/?probe=c3d55f501c) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | Desktop     | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f0dfa48048](https://linux-hardware.org/?probe=f0dfa48048) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [802af80043](https://linux-hardware.org/?probe=802af80043) | Nov 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| Dell          | Latitude E6540              | Notebook    | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [56ceffe338](https://linux-hardware.org/?probe=56ceffe338) | Nov 28, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| HUAWEI        | MRC-WX0                     | Notebook    | [98f550465b](https://linux-hardware.org/?probe=98f550465b) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6bf87b9885](https://linux-hardware.org/?probe=6bf87b9885) | Nov 28, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [1a316a1239](https://linux-hardware.org/?probe=1a316a1239) | Nov 27, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [87ef485975](https://linux-hardware.org/?probe=87ef485975) | Nov 27, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| HP            | ProBook 6470b               | Notebook    | [c8da54315e](https://linux-hardware.org/?probe=c8da54315e) | Nov 26, 2022 |
| Dell          | Latitude E6220              | Notebook    | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | Notebook    | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | Notebook    | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [7412d8b03b](https://linux-hardware.org/?probe=7412d8b03b) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [24d078fe91](https://linux-hardware.org/?probe=24d078fe91) | Nov 26, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1bd15590c9](https://linux-hardware.org/?probe=1bd15590c9) | Nov 25, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [a17a108297](https://linux-hardware.org/?probe=a17a108297) | Nov 25, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [2b7bb89689](https://linux-hardware.org/?probe=2b7bb89689) | Nov 25, 2022 |
| HP            | 2215                        | Desktop     | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |
| HP            | 213D A01                    | Desktop     | [b0c45fb200](https://linux-hardware.org/?probe=b0c45fb200) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Dell          | Latitude 5310               | Notebook    | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Dell          | Latitude 5310               | Notebook    | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| Unknown       | HX90                        | Desktop     | [e1bd045aaa](https://linux-hardware.org/?probe=e1bd045aaa) | Nov 24, 2022 |
| ASUSTek       | K51AC                       | Notebook    | [0b2413e13c](https://linux-hardware.org/?probe=0b2413e13c) | Nov 24, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ca7045ed57](https://linux-hardware.org/?probe=ca7045ed57) | Nov 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [d2d484b35b](https://linux-hardware.org/?probe=d2d484b35b) | Nov 24, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [e7717a62cb](https://linux-hardware.org/?probe=e7717a62cb) | Nov 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [ac72570183](https://linux-hardware.org/?probe=ac72570183) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [57dfd88985](https://linux-hardware.org/?probe=57dfd88985) | Nov 23, 2022 |
| HP            | Pavilion dv6                | Notebook    | [e3921e4da9](https://linux-hardware.org/?probe=e3921e4da9) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [51ca9fa048](https://linux-hardware.org/?probe=51ca9fa048) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [0ca1ce1d74](https://linux-hardware.org/?probe=0ca1ce1d74) | Nov 23, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6d217fbd52](https://linux-hardware.org/?probe=6d217fbd52) | Nov 23, 2022 |
| ASRock        | H410M-HVS R2.0              | Desktop     | [3f381f9fa3](https://linux-hardware.org/?probe=3f381f9fa3) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17b880ceb9](https://linux-hardware.org/?probe=17b880ceb9) | Nov 23, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 580       | 11.64%  |
| OpenMandriva 4.2   | 317       | 6.36%   |
| Ubuntu 18.04       | 280       | 5.62%   |
| OpenMandriva 4.3   | 222       | 4.46%   |
| Ubuntu 22.04       | 202       | 4.05%   |
| Debian 11          | 137       | 2.75%   |
| Arch Rolling       | 118       | 2.37%   |
| ROSA R10           | 98        | 1.97%   |
| OpenMandriva 23.01 | 82        | 1.65%   |
| ROSA R9            | 70        | 1.41%   |
| Linux Mint 20.3    | 70        | 1.41%   |
| ROSA R11           | 69        | 1.38%   |
| Arch               | 68        | 1.36%   |
| Manjaro            | 67        | 1.34%   |
| Linux Mint 20.1    | 66        | 1.32%   |
| Zorin 16           | 65        | 1.3%    |
| KDE neon 20.04     | 64        | 1.28%   |
| ROSA R11.1         | 63        | 1.26%   |
| Fedora 37          | 62        | 1.24%   |
| Fedora 36          | 60        | 1.2%    |
| Ubuntu 20.10       | 56        | 1.12%   |
| Linux Mint 20.2    | 52        | 1.04%   |
| Ubuntu 21.04       | 50        | 1%      |
| Linux Mint 20      | 49        | 0.98%   |
| Ubuntu 19.10       | 48        | 0.96%   |
| Linux Mint 19.3    | 48        | 0.96%   |
| Ubuntu 21.10       | 44        | 0.88%   |
| Linux Mint 21.1    | 44        | 0.88%   |
| Fedora 35          | 43        | 0.86%   |
| ROSA R8            | 42        | 0.84%   |
| Fedora 33          | 41        | 0.82%   |
| Ubuntu 22.10       | 40        | 0.8%    |
| Fedora 34          | 39        | 0.78%   |
| Debian 10          | 39        | 0.78%   |
| Xubuntu 20.04      | 38        | 0.76%   |
| Fedora 32          | 38        | 0.76%   |
| Pop!_OS 20.04      | 37        | 0.74%   |
| Linux Mint 21      | 37        | 0.74%   |
| ROSA R8.1          | 36        | 0.72%   |
| Pop!_OS 22.04      | 36        | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1292      | 27.94%  |
| OpenMandriva  | 664       | 14.36%  |
| Linux Mint    | 378       | 8.17%   |
| ROSA          | 330       | 7.14%   |
| Fedora        | 296       | 6.4%    |
| Debian        | 213       | 4.61%   |
| Manjaro       | 186       | 4.02%   |
| Arch          | 178       | 3.85%   |
| Pop!_OS       | 133       | 2.88%   |
| Zorin         | 104       | 2.25%   |
| Kubuntu       | 90        | 1.95%   |
| KDE neon      | 86        | 1.86%   |
| Xubuntu       | 70        | 1.51%   |
| Gentoo        | 43        | 0.93%   |
| Kali          | 42        | 0.91%   |
| openSUSE      | 39        | 0.84%   |
| Endless       | 36        | 0.78%   |
| Lubuntu       | 35        | 0.76%   |
| Elementary    | 32        | 0.69%   |
| ArcoLinux     | 31        | 0.67%   |
| LMDE          | 25        | 0.54%   |
| EndeavourOS   | 22        | 0.48%   |
| Clear Linux   | 21        | 0.45%   |
| Ubuntu Unity  | 19        | 0.41%   |
| BlackPanther  | 18        | 0.39%   |
| Ubuntu MATE   | 16        | 0.35%   |
| SteamOS       | 16        | 0.35%   |
| MX            | 16        | 0.35%   |
| CentOS        | 14        | 0.3%    |
| Nobara        | 12        | 0.26%   |
| Ubuntu Budgie | 11        | 0.24%   |
| LinuxFX       | 10        | 0.22%   |
| Garuda Linux  | 10        | 0.22%   |
| Raspbian      | 8         | 0.17%   |
| Peppermint    | 8         | 0.17%   |
| NixOS         | 8         | 0.17%   |
| Xero          | 6         | 0.13%   |
| Parrot        | 6         | 0.13%   |
| Linux Lite    | 6         | 0.13%   |
| RHEL          | 5         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 303       | 5.46%   |
| 5.16.7-desktop-1omv4003         | 207       | 3.73%   |
| 5.4.0-42-generic                | 78        | 1.41%   |
| 6.1.1-desktop-1omv2290          | 73        | 1.32%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 54        | 0.97%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 53        | 0.96%   |
| 5.15.0-56-generic               | 49        | 0.88%   |
| 5.15.0-43-generic               | 41        | 0.74%   |
| 5.4.0-26-generic                | 40        | 0.72%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 39        | 0.7%    |
| 5.4.0-52-generic                | 38        | 0.69%   |
| 5.15.0-58-generic               | 37        | 0.67%   |
| 5.4.0-48-generic                | 36        | 0.65%   |
| 5.15.0-52-generic               | 36        | 0.65%   |
| 5.4.0-58-generic                | 33        | 0.59%   |
| 5.19.0-35-generic               | 32        | 0.58%   |
| 5.4.0-29-generic                | 30        | 0.54%   |
| 5.3.0-46-generic                | 30        | 0.54%   |
| 5.4.0-54-generic                | 28        | 0.5%    |
| 5.13.0-39-generic               | 27        | 0.49%   |
| 5.11.0-37-generic               | 27        | 0.49%   |
| 5.8.0-43-generic                | 26        | 0.47%   |
| 5.4.0-40-generic                | 26        | 0.47%   |
| 5.4.0-37-generic                | 25        | 0.45%   |
| 5.15.0-48-generic               | 25        | 0.45%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 24        | 0.43%   |
| 5.4.0-33-generic                | 23        | 0.41%   |
| 5.13.0-27-generic               | 23        | 0.41%   |
| 5.4.0-66-generic                | 22        | 0.4%    |
| 5.3.0-42-generic                | 22        | 0.4%    |
| 5.11.0-27-generic               | 22        | 0.4%    |
| 5.0.0-37-generic                | 22        | 0.4%    |
| 5.19.0-32-generic               | 21        | 0.38%   |
| 5.15.0-60-generic               | 21        | 0.38%   |
| 5.8.0-48-generic                | 20        | 0.36%   |
| 5.4.0-65-generic                | 20        | 0.36%   |
| 5.4.0-56-generic                | 20        | 0.36%   |
| 5.13.0-40-generic               | 20        | 0.36%   |
| 5.4.0-91-generic                | 19        | 0.34%   |
| 5.15.0-53-generic               | 19        | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 752       | 14.4%   |
| 5.15.0  | 356       | 6.81%   |
| 5.10.14 | 305       | 5.84%   |
| 4.15.0  | 284       | 5.44%   |
| 5.11.0  | 223       | 4.27%   |
| 5.8.0   | 220       | 4.21%   |
| 5.16.7  | 210       | 4.02%   |
| 5.13.0  | 196       | 3.75%   |
| 5.3.0   | 166       | 3.18%   |
| 5.10.0  | 145       | 2.78%   |
| 5.0.0   | 101       | 1.93%   |
| 5.19.0  | 100       | 1.91%   |
| 4.18.0  | 90        | 1.72%   |
| 6.1.1   | 74        | 1.42%   |
| 4.9.60  | 66        | 1.26%   |
| 4.9.20  | 62        | 1.19%   |
| 4.19.0  | 51        | 0.98%   |
| 4.1.34  | 32        | 0.61%   |
| 5.14.0  | 30        | 0.57%   |
| 4.1.38  | 28        | 0.54%   |
| 6.0.0   | 25        | 0.48%   |
| 6.2.6   | 20        | 0.38%   |
| 5.17.5  | 20        | 0.38%   |
| 5.16.13 | 19        | 0.36%   |
| 5.11.12 | 19        | 0.36%   |
| 5.9.0   | 18        | 0.34%   |
| 5.4.32  | 17        | 0.33%   |
| 6.0.12  | 16        | 0.31%   |
| 4.9.76  | 16        | 0.31%   |
| 4.9.155 | 16        | 0.31%   |
| 4.9.124 | 16        | 0.31%   |
| 6.1.0   | 15        | 0.29%   |
| 6.0.7   | 15        | 0.29%   |
| 5.17.0  | 15        | 0.29%   |
| 6.0.8   | 14        | 0.27%   |
| 6.1.12  | 13        | 0.25%   |
| 5.6.0   | 13        | 0.25%   |
| 5.4.83  | 13        | 0.25%   |
| 5.15.12 | 13        | 0.25%   |
| 5.12.4  | 12        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 851       | 16.78%  |
| 5.10    | 561       | 11.06%  |
| 5.15    | 496       | 9.78%   |
| 5.16    | 300       | 5.92%   |
| 5.11    | 289       | 5.7%    |
| 4.15    | 284       | 5.6%    |
| 5.8     | 278       | 5.48%   |
| 5.13    | 226       | 4.46%   |
| 5.3     | 186       | 3.67%   |
| 4.9     | 182       | 3.59%   |
| 6.1     | 174       | 3.43%   |
| 5.19    | 158       | 3.12%   |
| 6.0     | 128       | 2.52%   |
| 5.0     | 111       | 2.19%   |
| 4.18    | 102       | 2.01%   |
| 5.14    | 84        | 1.66%   |
| 5.17    | 79        | 1.56%   |
| 5.9     | 74        | 1.46%   |
| 5.6     | 70        | 1.38%   |
| 5.18    | 69        | 1.36%   |
| 4.19    | 64        | 1.26%   |
| 4.1     | 63        | 1.24%   |
| 5.12    | 60        | 1.18%   |
| 6.2     | 44        | 0.87%   |
| 5.5     | 39        | 0.77%   |
| 5.7     | 35        | 0.69%   |
| 4.4     | 17        | 0.34%   |
| 5.1     | 8         | 0.16%   |
| 3.10    | 7         | 0.14%   |
| 5.2     | 5         | 0.1%    |
| 4.20    | 4         | 0.08%   |
| 4.16    | 3         | 0.06%   |
| 4.13    | 3         | 0.06%   |
| 4.8     | 2         | 0.04%   |
| 4.7     | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 4.10    | 2         | 0.04%   |
| 3.18    | 2         | 0.04%   |
| 4.17    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4262      | 95.67%  |
| i686    | 147       | 3.3%    |
| aarch64 | 24        | 0.54%   |
| armv7l  | 15        | 0.34%   |
| armv8l  | 3         | 0.07%   |
| armv6l  | 2         | 0.04%   |
| ppc64   | 1         | 0.02%   |
| ppc     | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1686      | 35.96%  |
| KDE5            | 1192      | 25.42%  |
| Unknown         | 481       | 10.26%  |
| XFCE            | 320       | 6.82%   |
| X-Cinnamon      | 258       | 5.5%    |
| KDE4            | 176       | 3.75%   |
| KDE             | 126       | 2.69%   |
| MATE            | 113       | 2.41%   |
| Cinnamon        | 65        | 1.39%   |
| LXQt            | 57        | 1.22%   |
| LXDE            | 46        | 0.98%   |
| Pantheon        | 31        | 0.66%   |
| i3              | 31        | 0.66%   |
| Unity           | 22        | 0.47%   |
| Budgie          | 19        | 0.41%   |
| Deepin          | 16        | 0.34%   |
| GNOME Flashback | 10        | 0.21%   |
| GNOME Classic   | 6         | 0.13%   |
| awesome         | 5         | 0.11%   |
| qtile           | 4         | 0.09%   |
| sway            | 3         | 0.06%   |
| Openbox         | 3         | 0.06%   |
| Hyprland        | 3         | 0.06%   |
| fluxbox         | 3         | 0.06%   |
| DWM             | 3         | 0.06%   |
| Trinity         | 2         | 0.04%   |
| icewm           | 2         | 0.04%   |
| xmonad          | 1         | 0.02%   |
| stumpwm         | 1         | 0.02%   |
| qt5ct           | 1         | 0.02%   |
| jwm             | 1         | 0.02%   |
| GNUstep         | 1         | 0.02%   |
| gnome-xorg      | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3671      | 79.91%  |
| Wayland | 600       | 13.06%  |
| Unknown | 232       | 5.05%   |
| Tty     | 91        | 1.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1946      | 41.73%  |
| SDDM    | 1126      | 24.15%  |
| GDM     | 509       | 10.92%  |
| GDM3    | 360       | 7.72%   |
| LightDM | 359       | 7.7%    |
| KDM     | 186       | 3.99%   |
| TDM     | 152       | 3.26%   |
| XDM     | 10        | 0.21%   |
| SLiM    | 3         | 0.06%   |
| Ly      | 3         | 0.06%   |
| LXDM    | 3         | 0.06%   |
| SLIMSKI | 2         | 0.04%   |
| NODM    | 2         | 0.04%   |
| MDM     | 2         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pl_PL       | 2495      | 53.89%  |
| en_US       | 1172      | 25.31%  |
| Unknown     | 647       | 13.97%  |
| en_GB       | 131       | 2.83%   |
| C           | 78        | 1.68%   |
| ru_RU       | 26        | 0.56%   |
| szl_PL      | 12        | 0.26%   |
| en_CA       | 8         | 0.17%   |
| de_DE       | 8         | 0.17%   |
| uk_UA       | 7         | 0.15%   |
| ru_UA       | 5         | 0.11%   |
| fr_FR       | 5         | 0.11%   |
| en_IE       | 5         | 0.11%   |
| en_AG       | 4         | 0.09%   |
| it_IT       | 3         | 0.06%   |
| en_DK       | 3         | 0.06%   |
| C.UTF8      | 3         | 0.06%   |
| nl_NL       | 2         | 0.04%   |
| hu_HU       | 2         | 0.04%   |
| en_IN       | 2         | 0.04%   |
| sv_SE       | 1         | 0.02%   |
| sk_SK       | 1         | 0.02%   |
| POSIX       | 1         | 0.02%   |
| es_ES       | 1         | 0.02%   |
| es_AR       | 1         | 0.02%   |
| en_US.UTF8  | 1         | 0.02%   |
| en_US.utf-8 | 1         | 0.02%   |
| en_SE       | 1         | 0.02%   |
| en_AU       | 1         | 0.02%   |
| el_GR       | 1         | 0.02%   |
| af_ZA       | 1         | 0.02%   |
| aa_DJ       | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2525      | 55.43%  |
| EFI  | 2030      | 44.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3148      | 68.21%  |
| Overlay  | 650       | 14.08%  |
| Btrfs    | 381       | 8.26%   |
| Unknown  | 298       | 6.46%   |
| Xfs      | 62        | 1.34%   |
| Zfs      | 29        | 0.63%   |
| F2fs     | 19        | 0.41%   |
| Ext2     | 7         | 0.15%   |
| Tmpfs    | 6         | 0.13%   |
| Ext3     | 6         | 0.13%   |
| Rootfs   | 3         | 0.07%   |
| Jfs      | 2         | 0.04%   |
| XXXXX    | 1         | 0.02%   |
| SquXshfs | 1         | 0.02%   |
| Bcachefs | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2168      | 47.08%  |
| GPT     | 1625      | 35.29%  |
| MBR     | 812       | 17.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3712      | 81.31%  |
| Yes       | 853       | 18.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2965      | 65.16%  |
| Yes       | 1585      | 34.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 784       | 17.63%  |
| Dell                    | 721       | 16.22%  |
| ASUSTek Computer        | 685       | 15.41%  |
| Hewlett-Packard         | 534       | 12.01%  |
| Gigabyte Technology     | 395       | 8.88%   |
| MSI                     | 334       | 7.51%   |
| Acer                    | 189       | 4.25%   |
| ASRock                  | 157       | 3.53%   |
| Samsung Electronics     | 75        | 1.69%   |
| Toshiba                 | 72        | 1.62%   |
| Fujitsu                 | 49        | 1.1%    |
| Apple                   | 40        | 0.9%    |
| Sony                    | 37        | 0.83%   |
| Fujitsu Siemens         | 31        | 0.7%    |
| HUAWEI                  | 28        | 0.63%   |
| Intel                   | 27        | 0.61%   |
| Raspberry Pi Foundation | 22        | 0.49%   |
| Unknown                 | 19        | 0.43%   |
| Valve                   | 13        | 0.29%   |
| Notebook                | 13        | 0.29%   |
| Medion                  | 13        | 0.29%   |
| Google                  | 13        | 0.29%   |
| Foxconn                 | 13        | 0.29%   |
| Packard Bell            | 12        | 0.27%   |
| Kiano                   | 10        | 0.22%   |
| eMachines               | 9         | 0.2%    |
| Timi                    | 7         | 0.16%   |
| AMI                     | 7         | 0.16%   |
| Inventec                | 6         | 0.13%   |
| Huanan                  | 5         | 0.11%   |
| ZOTAC                   | 4         | 0.09%   |
| Supermicro              | 4         | 0.09%   |
| mPTech                  | 4         | 0.09%   |
| Kruger&Matz             | 4         | 0.09%   |
| Gateway                 | 4         | 0.09%   |
| ECS                     | 4         | 0.09%   |
| Alienware               | 4         | 0.09%   |
| sunxi                   | 3         | 0.07%   |
| Nvidia                  | 3         | 0.07%   |
| Hardkernel              | 3         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 42        | 0.94%   |
| Dell Inspiron 3451                  | 31        | 0.7%    |
| ASUS All Series                     | 30        | 0.67%   |
| Gigabyte B450M DS3H                 | 18        | 0.4%    |
| ASUS SABERTOOTH Z77                 | 18        | 0.4%    |
| MSI MS-7B86                         | 16        | 0.36%   |
| MSI MS-7817                         | 16        | 0.36%   |
| Dell OptiPlex 780                   | 15        | 0.34%   |
| Dell Latitude E6400                 | 15        | 0.34%   |
| Dell Latitude E6540                 | 14        | 0.31%   |
| Valve Jupiter                       | 13        | 0.29%   |
| MSI MS-7C02                         | 12        | 0.27%   |
| Lenovo G50-30 80G0                  | 12        | 0.27%   |
| Dell Latitude 5480                  | 12        | 0.27%   |
| Dell Latitude E6430                 | 11        | 0.25%   |
| Dell Latitude D630                  | 11        | 0.25%   |
| HP Pavilion dv7                     | 10        | 0.22%   |
| Gigabyte B450 AORUS ELITE           | 10        | 0.22%   |
| Dell OptiPlex 7010                  | 10        | 0.22%   |
| Dell Latitude 5490                  | 10        | 0.22%   |
| MSI MS-7721                         | 9         | 0.2%    |
| Dell OptiPlex 755                   | 9         | 0.2%    |
| Dell Latitude E7440                 | 9         | 0.2%    |
| Dell Latitude E6420                 | 9         | 0.2%    |
| ASUS X555LJ                         | 9         | 0.2%    |
| ASUS TUF Gaming X570-PLUS           | 9         | 0.2%    |
| MSI MS-7C37                         | 8         | 0.18%   |
| MSI MS-7B79                         | 8         | 0.18%   |
| MSI MS-7A38                         | 8         | 0.18%   |
| Lenovo Legion Y530-15ICH 81FV       | 8         | 0.18%   |
| Lenovo G580 20150                   | 8         | 0.18%   |
| Lenovo G510 20238                   | 8         | 0.18%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 8         | 0.18%   |
| HP Pavilion dv6                     | 8         | 0.18%   |
| HP Notebook                         | 8         | 0.18%   |
| HP 15                               | 8         | 0.18%   |
| Gigabyte B85M-D3H                   | 8         | 0.18%   |
| Gigabyte B550 AORUS ELITE V2        | 8         | 0.18%   |
| Dell Latitude 5420                  | 8         | 0.18%   |
| ASUS PRIME B450M-A                  | 8         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 324       | 7.29%   |
| Dell Latitude      | 298       | 6.7%    |
| Dell Inspiron      | 150       | 3.37%   |
| Lenovo IdeaPad     | 141       | 3.17%   |
| Acer Aspire        | 113       | 2.54%   |
| Dell OptiPlex      | 98        | 2.2%    |
| HP EliteBook       | 90        | 2.02%   |
| HP Pavilion        | 88        | 1.98%   |
| HP ProBook         | 64        | 1.44%   |
| ASUS PRIME         | 63        | 1.42%   |
| HP Compaq          | 61        | 1.37%   |
| Toshiba Satellite  | 58        | 1.3%    |
| Dell Precision     | 58        | 1.3%    |
| ASUS TUF           | 50        | 1.12%   |
| Lenovo Legion      | 48        | 1.08%   |
| Unknown            | 42        | 0.94%   |
| Dell Vostro        | 41        | 0.92%   |
| ASUS ROG           | 41        | 0.92%   |
| Lenovo ThinkCentre | 39        | 0.88%   |
| ASUS VivoBook      | 36        | 0.81%   |
| HP Laptop          | 32        | 0.72%   |
| ASUS All           | 30        | 0.67%   |
| Dell XPS           | 29        | 0.65%   |
| Gigabyte B450M     | 25        | 0.56%   |
| RPi Raspberry      | 22        | 0.49%   |
| Fujitsu LIFEBOOK   | 20        | 0.45%   |
| ASUS SABERTOOTH    | 20        | 0.45%   |
| ASUS ASUS          | 20        | 0.45%   |
| HP EliteDesk       | 19        | 0.43%   |
| HP 250             | 19        | 0.43%   |
| Lenovo Yoga        | 17        | 0.38%   |
| Fujitsu ESPRIMO    | 17        | 0.38%   |
| MSI MS-7B86        | 16        | 0.36%   |
| MSI MS-7817        | 16        | 0.36%   |
| HP ZBook           | 16        | 0.36%   |
| Acer Extensa       | 15        | 0.34%   |
| Lenovo ThinkBook   | 14        | 0.31%   |
| Gigabyte X570      | 14        | 0.31%   |
| Gigabyte B550      | 14        | 0.31%   |
| Gigabyte B450      | 14        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 384       | 8.64%   |
| 2018    | 381       | 8.57%   |
| 2013    | 367       | 8.25%   |
| 2019    | 358       | 8.05%   |
| 2011    | 331       | 7.44%   |
| 2020    | 327       | 7.35%   |
| 2014    | 289       | 6.5%    |
| 2017    | 267       | 6.01%   |
| 2015    | 250       | 5.62%   |
| 2008    | 249       | 5.6%    |
| 2010    | 233       | 5.24%   |
| 2021    | 210       | 4.72%   |
| 2009    | 204       | 4.59%   |
| 2016    | 197       | 4.43%   |
| 2007    | 191       | 4.3%    |
| 2022    | 78        | 1.75%   |
| 2006    | 74        | 1.66%   |
| Unknown | 35        | 0.79%   |
| 2005    | 10        | 0.22%   |
| 2004    | 6         | 0.13%   |
| 2023    | 4         | 0.09%   |
| 2001    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2638      | 59.33%  |
| Desktop        | 1629      | 36.64%  |
| Convertible    | 50        | 1.12%   |
| System on chip | 37        | 0.83%   |
| Mini pc        | 29        | 0.65%   |
| Server         | 25        | 0.56%   |
| All in one     | 18        | 0.4%    |
| Tablet         | 15        | 0.34%   |
| Phone          | 5         | 0.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4216      | 94.23%  |
| Enabled  | 258       | 5.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4430      | 99.64%  |
| Yes  | 16        | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 977       | 21.56%  |
| 4.01-8.0        | 922       | 20.35%  |
| 8.01-16.0       | 835       | 18.43%  |
| 16.01-24.0      | 817       | 18.03%  |
| 32.01-64.0      | 462       | 10.2%   |
| 1.01-2.0        | 189       | 4.17%   |
| 2.01-3.0        | 116       | 2.56%   |
| 64.01-256.0     | 96        | 2.12%   |
| 24.01-32.0      | 73        | 1.61%   |
| 0.51-1.0        | 37        | 0.82%   |
| 0.01-0.5        | 4         | 0.09%   |
| More than 256.0 | 3         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1893      | 37.46%  |
| 2.01-3.0    | 1068      | 21.14%  |
| 4.01-8.0    | 672       | 13.3%   |
| 3.01-4.0    | 573       | 11.34%  |
| 0.51-1.0    | 470       | 9.3%    |
| 8.01-16.0   | 219       | 4.33%   |
| 0.01-0.5    | 92        | 1.82%   |
| 16.01-24.0  | 43        | 0.85%   |
| 24.01-32.0  | 13        | 0.26%   |
| 32.01-64.0  | 4         | 0.08%   |
| Unknown     | 4         | 0.08%   |
| 64.01-256.0 | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2719      | 58.8%   |
| 2       | 1162      | 25.13%  |
| 3       | 385       | 8.33%   |
| 4       | 159       | 3.44%   |
| 5       | 70        | 1.51%   |
| 0       | 69        | 1.49%   |
| 6       | 28        | 0.61%   |
| 7       | 15        | 0.32%   |
| 8       | 7         | 0.15%   |
| 9       | 3         | 0.06%   |
| 11      | 2         | 0.04%   |
| 10      | 2         | 0.04%   |
| 13      | 1         | 0.02%   |
| 12      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2531      | 56.14%  |
| Yes       | 1977      | 43.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4025      | 90.31%  |
| No        | 432       | 9.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3357      | 74.8%   |
| No        | 1131      | 25.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2515      | 55.62%  |
| No        | 2007      | 44.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 4446      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 996       | 20.54%  |
| Krakow                 | 359       | 7.41%   |
| Wroclaw                | 288       | 5.94%   |
| Poznan                 | 235       | 4.85%   |
| Gdansk                 | 148       | 3.05%   |
| Lodz                   | 145       | 2.99%   |
| Katowice               | 128       | 2.64%   |
| Lublin                 | 64        | 1.32%   |
| Gdynia                 | 56        | 1.16%   |
| Szczecin               | 49        | 1.01%   |
| Bialystok              | 46        | 0.95%   |
| Gliwice                | 40        | 0.83%   |
| Częstochowa           | 40        | 0.83%   |
| Rzeszów               | 39        | 0.8%    |
| Torun                  | 36        | 0.74%   |
| Bydgoszcz              | 34        | 0.7%    |
| Bytom                  | 33        | 0.68%   |
| Ruda Śląska          | 31        | 0.64%   |
| Płock                 | 25        | 0.52%   |
| Elblag                 | 25        | 0.52%   |
| Sosnowiec              | 24        | 0.5%    |
| Kielce                 | 23        | 0.47%   |
| Olsztyn                | 21        | 0.43%   |
| Bielsko-Biala          | 21        | 0.43%   |
| Strzyzow               | 20        | 0.41%   |
| Tarnów                | 19        | 0.39%   |
| Rybnik                 | 19        | 0.39%   |
| Chorzów               | 19        | 0.39%   |
| Radom                  | 18        | 0.37%   |
| Zabrze                 | 17        | 0.35%   |
| Siemianowice Śląskie | 17        | 0.35%   |
| Opole                  | 17        | 0.35%   |
| Tychy                  | 16        | 0.33%   |
| Jaworzno               | 14        | 0.29%   |
| Debica                 | 13        | 0.27%   |
| Cieszyn                | 13        | 0.27%   |
| Blizniew               | 13        | 0.27%   |
| Zielona Góra          | 12        | 0.25%   |
| Słupsk                | 12        | 0.25%   |
| Piaseczno              | 12        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 949       | 1463   | 14.4%   |
| WDC                       | 904       | 1377   | 13.71%  |
| Samsung Electronics       | 896       | 1379   | 13.59%  |
| GOODRAM                   | 444       | 648    | 6.74%   |
| Toshiba                   | 409       | 612    | 6.2%    |
| Kingston                  | 254       | 360    | 3.85%   |
| Crucial                   | 251       | 407    | 3.81%   |
| A-DATA Technology         | 243       | 334    | 3.69%   |
| Unknown                   | 239       | 343    | 3.63%   |
| SanDisk                   | 239       | 329    | 3.63%   |
| Hitachi                   | 221       | 314    | 3.35%   |
| Intel                     | 163       | 218    | 2.47%   |
| SK hynix                  | 138       | 181    | 2.09%   |
| HGST                      | 104       | 136    | 1.58%   |
| Micron Technology         | 90        | 118    | 1.37%   |
| Patriot                   | 80        | 104    | 1.21%   |
| SPCC                      | 68        | 102    | 1.03%   |
| Plextor                   | 57        | 75     | 0.86%   |
| PNY                       | 49        | 53     | 0.74%   |
| KIOXIA                    | 44        | 49     | 0.67%   |
| XPG                       | 42        | 60     | 0.64%   |
| Phison                    | 38        | 52     | 0.58%   |
| Fujitsu                   | 37        | 41     | 0.56%   |
| Apacer                    | 36        | 59     | 0.55%   |
| OCZ                       | 29        | 32     | 0.44%   |
| China                     | 26        | 30     | 0.39%   |
| LITEON                    | 25        | 34     | 0.38%   |
| Corsair                   | 25        | 34     | 0.38%   |
| Transcend                 | 23        | 24     | 0.35%   |
| Maxtor                    | 22        | 22     | 0.33%   |
| Phison Electronics        | 21        | 31     | 0.32%   |
| Silicon Motion            | 20        | 24     | 0.3%    |
| KIOXIA-EXCERIA            | 19        | 25     | 0.29%   |
| ASMT                      | 19        | 20     | 0.29%   |
| Realtek Semiconductor     | 18        | 29     | 0.27%   |
| JMicron Technology        | 18        | 19     | 0.27%   |
| Apple                     | 18        | 22     | 0.27%   |
| Lite-On                   | 17        | 20     | 0.26%   |
| Micron/Crucial Technology | 15        | 15     | 0.23%   |
| LITEONIT                  | 15        | 17     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                     | 63        | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB                      | 57        | 0.79%   |
| Crucial CT500MX500SSD1 500GB                        | 56        | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 54        | 0.75%   |
| Toshiba HDWD110 1TB                                 | 52        | 0.72%   |
| Samsung SSD 850 EVO 250GB                           | 50        | 0.69%   |
| GOODRAM SSD 120GB                                   | 50        | 0.69%   |
| Crucial CT1000MX500SSD1 1TB                         | 43        | 0.6%    |
| GOODRAM SSDPR-CX400-256-G2 256GB                    | 41        | 0.57%   |
| Seagate ST500DM002-1BD142 500GB                     | 39        | 0.54%   |
| Unknown MMC Card  32GB                              | 37        | 0.51%   |
| Samsung SSD 860 EVO 500GB                           | 37        | 0.51%   |
| GOODRAM SSD 240GB                                   | 35        | 0.48%   |
| Kingston SA400S37240G 240GB SSD                     | 34        | 0.47%   |
| GOODRAM SSDPR-CX400-512 512GB                       | 34        | 0.47%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                    | 33        | 0.46%   |
| Seagate ST9500325AS 500GB                           | 32        | 0.44%   |
| Samsung SSD 860 EVO 250GB                           | 32        | 0.44%   |
| Samsung NVMe SSD Drive 500GB                        | 32        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 32        | 0.44%   |
| Unknown MMC Card  64GB                              | 31        | 0.43%   |
| Toshiba MQ01ABD100 1TB                              | 31        | 0.43%   |
| A-DATA SU800 256GB SSD                              | 30        | 0.42%   |
| Seagate ST3500418AS 500GB                           | 28        | 0.39%   |
| Seagate ST1000DM010-2EP102 1TB                      | 28        | 0.39%   |
| Seagate ST1000DM003-1ER162 1TB                      | 28        | 0.39%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.39%   |
| Crucial CT240BX500SSD1 240GB                        | 28        | 0.39%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 27        | 0.37%   |
| Patriot Burst 120GB SSD                             | 27        | 0.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 26        | 0.36%   |
| Intel NVMe SSD Drive 512GB                          | 26        | 0.36%   |
| GOODRAM SSDPR-CX400-256 256GB                       | 26        | 0.36%   |
| Samsung HD502HJ 500GB                               | 25        | 0.35%   |
| HGST HTS721010A9E630 1TB                            | 25        | 0.35%   |
| Seagate Expansion+ 2TB                              | 24        | 0.33%   |
| GOODRAM SSDPR-CX400-128 128GB                       | 24        | 0.33%   |
| Toshiba MQ01ABF050 500GB                            | 23        | 0.32%   |
| SanDisk SDSSDA240G 240GB                            | 23        | 0.32%   |
| Kingston SA400S37480G 480GB SSD                     | 23        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 945       | 1455   | 36%     |
| WDC                 | 757       | 1168   | 28.84%  |
| Toshiba             | 317       | 496    | 12.08%  |
| Hitachi             | 221       | 314    | 8.42%   |
| Samsung Electronics | 165       | 233    | 6.29%   |
| HGST                | 104       | 136    | 3.96%   |
| Fujitsu             | 37        | 41     | 1.41%   |
| Maxtor              | 20        | 20     | 0.76%   |
| ASMT                | 19        | 20     | 0.72%   |
| Unknown             | 9         | 9      | 0.34%   |
| Apple               | 6         | 6      | 0.23%   |
| ASMedia             | 5         | 6      | 0.19%   |
| USB3.0              | 3         | 3      | 0.11%   |
| PHD 3.0             | 2         | 2      | 0.08%   |
| IBM/Hitachi         | 2         | 2      | 0.08%   |
| Unknown             | 2         | 2      | 0.08%   |
| WD MediaMax         | 1         | 2      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| StoreJet            | 1         | 1      | 0.04%   |
| SAGE                | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 2      | 0.04%   |
| HPE                 | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| GOODRAM             | 434       | 626    | 18.14%  |
| Samsung Electronics | 400       | 561    | 16.72%  |
| Crucial             | 242       | 396    | 10.12%  |
| A-DATA Technology   | 200       | 272    | 8.36%   |
| Kingston            | 184       | 254    | 7.69%   |
| SanDisk             | 159       | 224    | 6.65%   |
| WDC                 | 81        | 95     | 3.39%   |
| Patriot             | 71        | 95     | 2.97%   |
| SPCC                | 61        | 93     | 2.55%   |
| Intel               | 53        | 64     | 2.22%   |
| Plextor             | 48        | 66     | 2.01%   |
| Micron Technology   | 47        | 62     | 1.96%   |
| Toshiba             | 42        | 47     | 1.76%   |
| SK hynix            | 36        | 45     | 1.51%   |
| PNY                 | 36        | 40     | 1.51%   |
| Apacer              | 33        | 56     | 1.38%   |
| OCZ                 | 29        | 32     | 1.21%   |
| LITEON              | 25        | 34     | 1.05%   |
| China               | 25        | 29     | 1.05%   |
| Transcend           | 22        | 23     | 0.92%   |
| LITEONIT            | 15        | 17     | 0.63%   |
| KIOXIA-EXCERIA      | 15        | 20     | 0.63%   |
| JMicron Technology  | 12        | 12     | 0.5%    |
| Apple               | 11        | 11     | 0.46%   |
| Corsair             | 10        | 11     | 0.42%   |
| KingSpec            | 7         | 8      | 0.29%   |
| Intenso             | 6         | 11     | 0.25%   |
| BIWIN               | 5         | 5      | 0.21%   |
| Team                | 4         | 4      | 0.17%   |
| Lexar               | 4         | 4      | 0.17%   |
| Argon               | 4         | 6      | 0.17%   |
| WDC WDS2            | 3         | 3      | 0.13%   |
| Gigabyte Technology | 3         | 4      | 0.13%   |
| 2-Power             | 3         | 3      | 0.13%   |
| Unknown             | 3         | 3      | 0.13%   |
| Union Memory        | 2         | 3      | 0.08%   |
| Ramaxel Technology  | 2         | 3      | 0.08%   |
| POLION              | 2         | 2      | 0.08%   |
| Phison              | 2         | 2      | 0.08%   |
| Netac               | 2         | 3      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2225      | 3926   | 38%     |
| SSD     | 2095      | 3302   | 35.78%  |
| NVMe    | 1240      | 1891   | 21.18%  |
| MMC     | 217       | 308    | 3.71%   |
| Unknown | 78        | 114    | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3480      | 7054   | 67.52%  |
| NVMe | 1239      | 1885   | 24.04%  |
| SAS  | 218       | 294    | 4.23%   |
| MMC  | 217       | 308    | 4.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2851      | 4692   | 65.26%  |
| 0.51-1.0        | 1100      | 1750   | 25.18%  |
| 1.01-2.0        | 237       | 380    | 5.42%   |
| 3.01-4.0        | 63        | 126    | 1.44%   |
| 2.01-3.0        | 59        | 149    | 1.35%   |
| 4.01-10.0       | 41        | 85     | 0.94%   |
| 10.01-20.0      | 15        | 28     | 0.34%   |
| More than 100.0 | 3         | 18     | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1331      | 27.6%   |
| 251-500        | 910       | 18.87%  |
| 1-20           | 592       | 12.28%  |
| 501-1000       | 554       | 11.49%  |
| 51-100         | 406       | 8.42%   |
| 1001-2000      | 321       | 6.66%   |
| 21-50          | 241       | 5%      |
| Unknown        | 215       | 4.46%   |
| More than 3000 | 145       | 3.01%   |
| 2001-3000      | 107       | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2073      | 41.7%   |
| 21-50          | 737       | 14.83%  |
| 101-250        | 593       | 11.93%  |
| 51-100         | 549       | 11.04%  |
| 251-500        | 310       | 6.24%   |
| 501-1000       | 257       | 5.17%   |
| Unknown        | 215       | 4.33%   |
| 1001-2000      | 138       | 2.78%   |
| 2001-3000      | 51        | 1.03%   |
| More than 3000 | 48        | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 14        | 17     | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 10        | 12     | 1.52%   |
| Seagate ST500LT012-9WS142 500GB      | 9         | 28     | 1.37%   |
| Seagate ST500LT012-1DG142 500GB      | 8         | 11     | 1.22%   |
| Seagate ST3500418AS 500GB            | 8         | 11     | 1.22%   |
| Seagate ST500DM002-1BD142 500GB      | 7         | 7      | 1.07%   |
| Seagate ST1000DM003-9YN162 1TB       | 6         | 6      | 0.91%   |
| HGST HTS545050A7E680 500GB           | 6         | 6      | 0.91%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 5      | 0.76%   |
| GOODRAM SSD 120GB                    | 5         | 5      | 0.76%   |
| ASMT 2135 12TB                       | 5         | 5      | 0.76%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 4         | 4      | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 4      | 0.61%   |
| Toshiba MQ01ABD100 1TB               | 4         | 5      | 0.61%   |
| Seagate ST9500420AS 500GB            | 4         | 4      | 0.61%   |
| Seagate ST9320325AS 320GB            | 4         | 4      | 0.61%   |
| Seagate ST92505610AS 250GB           | 4         | 4      | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 4      | 0.61%   |
| Seagate ST3320613AS 320GB            | 4         | 4      | 0.61%   |
| Seagate ST1000DX001-1CM162 1TB       | 4         | 7      | 0.61%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 4      | 0.61%   |
| Hitachi HTS541612J9SA00 120GB        | 4         | 5      | 0.61%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 3         | 3      | 0.46%   |
| Toshiba MK3265GSX 320GB              | 3         | 3      | 0.46%   |
| Toshiba MK1637GSX 160GB              | 3         | 3      | 0.46%   |
| Toshiba MK1246GSX 120GB              | 3         | 3      | 0.46%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 3      | 0.46%   |
| Seagate ST9250827AS 250GB            | 3         | 3      | 0.46%   |
| Seagate ST9250410AS 250GB            | 3         | 3      | 0.46%   |
| Seagate ST9250315AS 250GB            | 3         | 3      | 0.46%   |
| Seagate ST9160821AS 160GB            | 3         | 4      | 0.46%   |
| Seagate ST3500312CS 500GB            | 3         | 3      | 0.46%   |
| Seagate ST3320418AS 320GB            | 3         | 3      | 0.46%   |
| Seagate ST3250410AS 250GB            | 3         | 3      | 0.46%   |
| Seagate ST320LT020-9YG142 320GB      | 3         | 3      | 0.46%   |
| Seagate ST31500341AS 1TB             | 3         | 4      | 0.46%   |
| Seagate ST2000DX002-2DV164 2TB       | 3         | 5      | 0.46%   |
| Seagate ST1000LM014-1EJ164 1TB       | 3         | 4      | 0.46%   |
| Samsung Electronics HD502HJ 500GB    | 3         | 3      | 0.46%   |
| Samsung Electronics HD321KJ 320GB    | 3         | 3      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 187       | 252    | 29.73%  |
| WDC                   | 120       | 175    | 19.08%  |
| Hitachi               | 52        | 67     | 8.27%   |
| Samsung Electronics   | 50        | 57     | 7.95%   |
| Toshiba               | 48        | 59     | 7.63%   |
| A-DATA Technology     | 28        | 31     | 4.45%   |
| SanDisk               | 17        | 20     | 2.7%    |
| HGST                  | 17        | 18     | 2.7%    |
| Kingston              | 14        | 14     | 2.23%   |
| SK hynix              | 8         | 8      | 1.27%   |
| GOODRAM               | 8         | 8      | 1.27%   |
| Fujitsu               | 8         | 10     | 1.27%   |
| Intel                 | 7         | 7      | 1.11%   |
| ASMT                  | 6         | 7      | 0.95%   |
| Micron Technology     | 5         | 5      | 0.79%   |
| Maxtor                | 5         | 5      | 0.79%   |
| LITEON                | 5         | 5      | 0.79%   |
| Crucial               | 5         | 9      | 0.79%   |
| LITEONIT              | 4         | 4      | 0.64%   |
| Apacer                | 4         | 7      | 0.64%   |
| SPCC                  | 3         | 3      | 0.48%   |
| OCZ                   | 3         | 3      | 0.48%   |
| Hewlett-Packard       | 3         | 3      | 0.48%   |
| ASMedia               | 3         | 3      | 0.48%   |
| Patriot               | 2         | 4      | 0.32%   |
| China                 | 2         | 2      | 0.32%   |
| XPG                   | 1         | 1      | 0.16%   |
| WDC WDS2              | 1         | 1      | 0.16%   |
| WD MediaMax           | 1         | 2      | 0.16%   |
| SSSTC                 | 1         | 1      | 0.16%   |
| RENICE                | 1         | 1      | 0.16%   |
| Realtek Semiconductor | 1         | 1      | 0.16%   |
| Plextor               | 1         | 1      | 0.16%   |
| Platinet              | 1         | 1      | 0.16%   |
| Lexar                 | 1         | 1      | 0.16%   |
| Lenovo                | 1         | 1      | 0.16%   |
| KingSpec              | 1         | 1      | 0.16%   |
| KingFast              | 1         | 1      | 0.16%   |
| Corsair               | 1         | 2      | 0.16%   |
| Apple                 | 1         | 1      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 187       | 252    | 38.88%  |
| WDC                 | 117       | 171    | 24.32%  |
| Hitachi             | 52        | 67     | 10.81%  |
| Toshiba             | 45        | 56     | 9.36%   |
| Samsung Electronics | 38        | 44     | 7.9%    |
| HGST                | 17        | 18     | 3.53%   |
| Fujitsu             | 8         | 10     | 1.66%   |
| ASMT                | 6         | 7      | 1.25%   |
| Maxtor              | 5         | 5      | 1.04%   |
| ASMedia             | 3         | 3      | 0.62%   |
| WD MediaMax         | 1         | 2      | 0.21%   |
| Hewlett-Packard     | 1         | 1      | 0.21%   |
| Unknown             | 1         | 1      | 0.21%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 449       | 637    | 75.46%  |
| SSD  | 126       | 144    | 21.18%  |
| NVMe | 20        | 22     | 3.36%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB         | 1         | 1      | 8.33%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 8.33%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 8.33%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 8.33%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 8.33%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 8.33%   |
| Toshiba DT01ACA100 1TB            | 1         | 2      | 8.33%   |
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 8.33%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 8.33%   |
| Samsung Electronics HD250HJ 250GB | 1         | 1      | 8.33%   |
| OCZ-AGIL ITY3 64GB SSD            | 1         | 1      | 8.33%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 41.67%  |
| Toshiba             | 2         | 3      | 16.67%  |
| Seagate             | 2         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 8.33%   |
| OCZ-AGIL            | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2297      | 4822   | 46.95%  |
| Works    | 2003      | 3903   | 40.94%  |
| Malfunc  | 580       | 803    | 11.86%  |
| Failed   | 12        | 13     | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3105      | 55.54%  |
| AMD                              | 811       | 14.51%  |
| Samsung Electronics              | 405       | 7.24%   |
| SanDisk                          | 154       | 2.75%   |
| Phison Electronics               | 106       | 1.9%    |
| SK hynix                         | 98        | 1.75%   |
| ASMedia Technology               | 95        | 1.7%    |
| JMicron Technology               | 94        | 1.68%   |
| ADATA Technology                 | 89        | 1.59%   |
| Nvidia                           | 88        | 1.57%   |
| Kingston Technology Company      | 81        | 1.45%   |
| Toshiba America Info Systems     | 53        | 0.95%   |
| KIOXIA                           | 52        | 0.93%   |
| Marvell Technology Group         | 45        | 0.8%    |
| Micron Technology                | 44        | 0.79%   |
| Silicon Motion                   | 42        | 0.75%   |
| Realtek Semiconductor            | 31        | 0.55%   |
| Lite-On Technology               | 27        | 0.48%   |
| Micron/Crucial Technology        | 23        | 0.41%   |
| VIA Technologies                 | 21        | 0.38%   |
| LSI Logic / Symbios Logic        | 19        | 0.34%   |
| Union Memory (Shenzhen)          | 16        | 0.29%   |
| Shenzhen Longsys Electronics     | 13        | 0.23%   |
| Silicon Integrated Systems [SiS] | 11        | 0.2%    |
| Solid State Storage Technology   | 9         | 0.16%   |
| Hewlett-Packard                  | 9         | 0.16%   |
| Silicon Image                    | 8         | 0.14%   |
| Broadcom / LSI                   | 8         | 0.14%   |
| Lenovo                           | 7         | 0.13%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.07%   |
| INNOGRIT                         | 3         | 0.05%   |
| Apple                            | 3         | 0.05%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| ULi Electronics                  | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Tekram Technology                | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 527       | 7.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 226       | 3.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 218       | 3.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 215       | 3.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 187       | 2.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 163       | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 161       | 2.43%   |
| AMD 400 Series Chipset SATA Controller                                         | 154       | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 129       | 1.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 116       | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 112       | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 107       | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 106       | 1.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 103       | 1.56%   |
| Samsung NVMe SSD Controller 980                                                | 98        | 1.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 98        | 1.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 95        | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 91        | 1.37%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 91        | 1.37%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 84        | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 81        | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller                            | 79        | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 79        | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 77        | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 77        | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 77        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 75        | 1.13%   |
| Intel SSD 660P Series                                                          | 69        | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 68        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 68        | 1.03%   |
| JMicron JMB363 SATA/IDE Controller                                             | 65        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 65        | 0.98%   |
| Intel SATA Controller [RAID mode]                                              | 58        | 0.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 58        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 53        | 0.8%    |
| Phison E12 NVMe Controller                                                     | 52        | 0.79%   |
| AMD 500 Series Chipset SATA Controller                                         | 51        | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 45        | 0.68%   |
| Micron NVMe Storage Controller                                                 | 43        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 43        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3224      | 56.62%  |
| NVMe | 1256      | 22.06%  |
| IDE  | 833       | 14.63%  |
| RAID | 352       | 6.18%   |
| SAS  | 15        | 0.26%   |
| SCSI | 14        | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3366      | 75.71%  |
| AMD          | 1033      | 23.23%  |
| ARM          | 40        | 0.9%    |
| Qualcomm     | 3         | 0.07%   |
| PowerMac11,2 | 1         | 0.02%   |
| PowerBook6,7 | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |
| AppliedMicro | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 49        | 1.1%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 43        | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 40        | 0.9%    |
| AMD Ryzen 5 3600 6-Core Processor             | 40        | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 38        | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 36        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 35        | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 34        | 0.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 34        | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 34        | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 0.76%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 33        | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 31        | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 0.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 29        | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 28        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 0.58%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 26        | 0.58%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 26        | 0.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.54%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 23        | 0.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 0.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 22        | 0.49%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 22        | 0.49%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 22        | 0.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 22        | 0.49%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 21        | 0.47%   |
| ARM Processor                                 | 21        | 0.47%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 20        | 0.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 20        | 0.45%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 20        | 0.45%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 20        | 0.45%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 20        | 0.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 19        | 0.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 19        | 0.43%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 19        | 0.43%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 19        | 0.43%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1083      | 24.29%  |
| Intel Core i7           | 690       | 15.47%  |
| Intel Core i3           | 321       | 7.2%    |
| Intel Core 2 Duo        | 301       | 6.75%   |
| AMD Ryzen 5             | 283       | 6.35%   |
| Other                   | 208       | 4.66%   |
| Intel Celeron           | 192       | 4.31%   |
| AMD Ryzen 7             | 177       | 3.97%   |
| Intel Pentium           | 128       | 2.87%   |
| Intel Xeon              | 114       | 2.56%   |
| Intel Atom              | 77        | 1.73%   |
| Intel Pentium Dual-Core | 68        | 1.53%   |
| Intel Core 2 Quad       | 61        | 1.37%   |
| AMD Ryzen 9             | 51        | 1.14%   |
| AMD FX                  | 48        | 1.08%   |
| Intel Core 2            | 40        | 0.9%    |
| AMD Phenom II X4        | 37        | 0.83%   |
| AMD Ryzen 3             | 35        | 0.78%   |
| AMD A6                  | 35        | 0.78%   |
| Intel Pentium Dual      | 32        | 0.72%   |
| AMD Athlon 64 X2        | 32        | 0.72%   |
| AMD A8                  | 32        | 0.72%   |
| AMD A10                 | 31        | 0.7%    |
| AMD Athlon II X2        | 27        | 0.61%   |
| AMD Athlon II X4        | 18        | 0.4%    |
| AMD A4                  | 18        | 0.4%    |
| Intel Genuine           | 17        | 0.38%   |
| AMD Ryzen 7 PRO         | 17        | 0.38%   |
| AMD E                   | 16        | 0.36%   |
| Intel Core i9           | 15        | 0.34%   |
| AMD E1                  | 12        | 0.27%   |
| Intel Celeron M         | 11        | 0.25%   |
| ARM BCM                 | 11        | 0.25%   |
| AMD Ryzen Threadripper  | 11        | 0.25%   |
| AMD Athlon              | 10        | 0.22%   |
| AMD Ryzen 5 PRO         | 9         | 0.2%    |
| AMD GX                  | 9         | 0.2%    |
| Intel Pentium M         | 8         | 0.18%   |
| Intel Pentium D         | 8         | 0.18%   |
| AMD Turion 64 X2 Mobile | 8         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1947      | 43.52%  |
| 4       | 1518      | 33.93%  |
| 6       | 428       | 9.57%   |
| 8       | 262       | 5.86%   |
| 1       | 105       | 2.35%   |
| Unknown | 69        | 1.54%   |
| 12      | 63        | 1.41%   |
| 16      | 23        | 0.51%   |
| 3       | 23        | 0.51%   |
| 10      | 13        | 0.29%   |
| 14      | 10        | 0.22%   |
| 32      | 3         | 0.07%   |
| 24      | 2         | 0.04%   |
| 20      | 2         | 0.04%   |
| 192     | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4402      | 98.94%  |
| 2       | 41        | 0.92%   |
| Unknown | 5         | 0.11%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2703      | 60.43%  |
| 1       | 1700      | 38.01%  |
| Unknown | 69        | 1.54%   |
| 8       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4322      | 96.99%  |
| Unknown        | 81        | 1.82%   |
| 32-bit         | 51        | 1.14%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 923       | 20.01%  |
| 0x306a9    | 280       | 6.07%   |
| 0x206a7    | 275       | 5.96%   |
| 0x306c3    | 236       | 5.12%   |
| 0x1067a    | 214       | 4.64%   |
| 0x906ea    | 127       | 2.75%   |
| 0x506e3    | 110       | 2.38%   |
| 0x40651    | 104       | 2.25%   |
| 0x20655    | 90        | 1.95%   |
| 0x30678    | 88        | 1.91%   |
| 0x906e9    | 87        | 1.89%   |
| 0x806ec    | 87        | 1.89%   |
| 0x6fd      | 87        | 1.89%   |
| 0x306d4    | 81        | 1.76%   |
| 0x806c1    | 78        | 1.69%   |
| 0x806ea    | 76        | 1.65%   |
| 0x406e3    | 76        | 1.65%   |
| 0x10676    | 76        | 1.65%   |
| 0x806e9    | 63        | 1.37%   |
| 0x0800820d | 62        | 1.34%   |
| 0x010000c8 | 58        | 1.26%   |
| 0x08701021 | 56        | 1.21%   |
| 0x0a50000c | 50        | 1.08%   |
| 0x6fb      | 45        | 0.98%   |
| 0x06001119 | 40        | 0.87%   |
| 0x08108109 | 36        | 0.78%   |
| 0x20652    | 34        | 0.74%   |
| 0x6f6      | 31        | 0.67%   |
| 0xa0652    | 30        | 0.65%   |
| 0x08600106 | 30        | 0.65%   |
| 0x806eb    | 27        | 0.59%   |
| 0x08701013 | 27        | 0.59%   |
| 0x906ed    | 25        | 0.54%   |
| 0x08108102 | 25        | 0.54%   |
| 0xa0653    | 24        | 0.52%   |
| 0x406c4    | 23        | 0.5%    |
| 0x06000852 | 22        | 0.48%   |
| 0x706e5    | 21        | 0.46%   |
| 0x406c3    | 21        | 0.46%   |
| 0x106e5    | 21        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 623       | 13.97%  |
| Haswell          | 416       | 9.33%   |
| IvyBridge        | 337       | 7.56%   |
| SandyBridge      | 332       | 7.44%   |
| Penryn           | 332       | 7.44%   |
| Skylake          | 233       | 5.22%   |
| Core             | 223       | 5%      |
| Zen 2            | 204       | 4.57%   |
| Westmere         | 160       | 3.59%   |
| Zen+             | 158       | 3.54%   |
| Silvermont       | 156       | 3.5%    |
| Unknown          | 125       | 2.8%    |
| K10              | 119       | 2.67%   |
| Broadwell        | 116       | 2.6%    |
| Zen 3            | 106       | 2.38%   |
| TigerLake        | 92        | 2.06%   |
| Zen              | 89        | 2%      |
| Piledriver       | 82        | 1.84%   |
| CometLake        | 81        | 1.82%   |
| K8 Hammer        | 63        | 1.41%   |
| IceLake          | 47        | 1.05%   |
| Bobcat           | 40        | 0.9%    |
| Nehalem          | 38        | 0.85%   |
| Bonnell          | 34        | 0.76%   |
| Alderlake Hybrid | 31        | 0.7%    |
| P6               | 30        | 0.67%   |
| Jaguar           | 25        | 0.56%   |
| Goldmont plus    | 25        | 0.56%   |
| Steamroller      | 22        | 0.49%   |
| Excavator        | 22        | 0.49%   |
| Goldmont         | 21        | 0.47%   |
| NetBurst         | 19        | 0.43%   |
| Puma             | 16        | 0.36%   |
| K10 Llano        | 16        | 0.36%   |
| K8 & K10 hybrid  | 14        | 0.31%   |
| Bulldozer        | 12        | 0.27%   |
| Tremont          | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2510      | 47.3%   |
| Nvidia                           | 1600      | 30.15%  |
| AMD                              | 1163      | 21.92%  |
| Matrox Electronics Systems       | 14        | 0.26%   |
| ASPEED Technology                | 7         | 0.13%   |
| Silicon Integrated Systems [SiS] | 6         | 0.11%   |
| VIA Technologies                 | 5         | 0.09%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 266       | 4.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 213       | 3.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 124       | 2.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 102       | 1.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 102       | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 99        | 1.79%   |
| Intel UHD Graphics 620                                                                   | 96        | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 96        | 1.74%   |
| Intel HD Graphics 5500                                                                   | 95        | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 92        | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 92        | 1.67%   |
| AMD Renoir                                                                               | 87        | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 86        | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 85        | 1.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 84        | 1.52%   |
| Intel HD Graphics 530                                                                    | 84        | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 78        | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 78        | 1.41%   |
| Intel HD Graphics 620                                                                    | 74        | 1.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 71        | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 71        | 1.29%   |
| Intel HD Graphics 630                                                                    | 70        | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 56        | 1.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 55        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 50        | 0.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 50        | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 40        | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 40        | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 40        | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 39        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 39        | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 38        | 0.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 37        | 0.67%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 36        | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 35        | 0.63%   |
| Nvidia GT218 [GeForce 210]                                                               | 29        | 0.52%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 29        | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 28        | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 28        | 0.51%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 28        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1719      | 38.3%   |
| 1 x Nvidia               | 918       | 20.45%  |
| 1 x AMD                  | 852       | 18.98%  |
| Intel + Nvidia           | 590       | 13.15%  |
| Intel + AMD              | 163       | 3.63%   |
| AMD + Nvidia             | 84        | 1.87%   |
| 2 x AMD                  | 65        | 1.45%   |
| Other                    | 47        | 1.05%   |
| 1 x Matrox               | 14        | 0.31%   |
| 2 x Intel                | 9         | 0.2%    |
| 1 x SiS                  | 6         | 0.13%   |
| 2 x Nvidia               | 5         | 0.11%   |
| 1 x VIA                  | 5         | 0.11%   |
| 1 x ASPEED               | 4         | 0.09%   |
| Nvidia + ASPEED          | 3         | 0.07%   |
| 3 x AMD                  | 2         | 0.04%   |
| 1 x S3 Graphics          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3556      | 78.31%  |
| Proprietary | 784       | 17.26%  |
| Unknown     | 201       | 4.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2336      | 50.6%   |
| 1.01-2.0   | 627       | 13.58%  |
| 0.01-0.5   | 588       | 12.74%  |
| 0.51-1.0   | 411       | 8.9%    |
| 3.01-4.0   | 307       | 6.65%   |
| 7.01-8.0   | 176       | 3.81%   |
| 5.01-6.0   | 115       | 2.49%   |
| 8.01-16.0  | 37        | 0.8%    |
| 2.01-3.0   | 16        | 0.35%   |
| 16.01-24.0 | 4         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 697       | 14.21%  |
| AU Optronics            | 562       | 11.46%  |
| LG Display              | 480       | 9.79%   |
| BOE                     | 359       | 7.32%   |
| Chimei Innolux          | 330       | 6.73%   |
| Dell                    | 299       | 6.1%    |
| Goldstar                | 269       | 5.48%   |
| Iiyama                  | 162       | 3.3%    |
| Philips                 | 159       | 3.24%   |
| Lenovo                  | 124       | 2.53%   |
| Hewlett-Packard         | 122       | 2.49%   |
| BenQ                    | 122       | 2.49%   |
| Acer                    | 118       | 2.41%   |
| Chi Mei Optoelectronics | 108       | 2.2%    |
| AOC                     | 105       | 2.14%   |
| NEC Computers           | 78        | 1.59%   |
| Eizo                    | 77        | 1.57%   |
| Ancor Communications    | 64        | 1.3%    |
| Sharp                   | 48        | 0.98%   |
| LG Philips              | 40        | 0.82%   |
| Sony                    | 34        | 0.69%   |
| PANDA                   | 34        | 0.69%   |
| Fujitsu Siemens         | 33        | 0.67%   |
| LG Electronics          | 32        | 0.65%   |
| Apple                   | 28        | 0.57%   |
| InfoVision              | 27        | 0.55%   |
| ASUSTek Computer        | 24        | 0.49%   |
| Unknown                 | 17        | 0.35%   |
| Toshiba                 | 17        | 0.35%   |
| HannStar                | 16        | 0.33%   |
| MSI                     | 15        | 0.31%   |
| Idek Iiyama             | 15        | 0.31%   |
| ViewSonic               | 14        | 0.29%   |
| Panasonic               | 14        | 0.29%   |
| CPT                     | 14        | 0.29%   |
| Gateway                 | 13        | 0.27%   |
| Belinea                 | 12        | 0.24%   |
| CSO                     | 11        | 0.22%   |
| IBM                     | 10        | 0.2%    |
| Mi                      | 9         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 28        | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 23        | 0.45%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 22        | 0.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 22        | 0.43%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 19        | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 18        | 0.35%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 17        | 0.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 17        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.33%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 16        | 0.31%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 16        | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 16        | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.29%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 13        | 0.25%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 13        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 13        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 13        | 0.25%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 13        | 0.25%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.25%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.23%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 12        | 0.23%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 12        | 0.23%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 11        | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 11        | 0.22%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 11        | 0.22%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 11        | 0.22%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 10        | 0.2%    |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 344x194mm 15.5-inch    | 10        | 0.2%    |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                 | 10        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 10        | 0.2%    |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 10        | 0.2%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 9         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1982      | 42.64%  |
| 1366x768 (WXGA)    | 799       | 17.19%  |
| 1280x1024 (SXGA)   | 216       | 4.65%   |
| 1600x900 (HD+)     | 209       | 4.5%    |
| 3840x2160 (4K)     | 201       | 4.32%   |
| 2560x1440 (QHD)    | 199       | 4.28%   |
| 1280x800 (WXGA)    | 179       | 3.85%   |
| 1680x1050 (WSXGA+) | 172       | 3.7%    |
| 1920x1200 (WUXGA)  | 163       | 3.51%   |
| 1440x900 (WXGA+)   | 135       | 2.9%    |
| 3440x1440          | 47        | 1.01%   |
| Unknown            | 47        | 1.01%   |
| 2560x1080          | 39        | 0.84%   |
| 1024x600           | 26        | 0.56%   |
| 2560x1600          | 24        | 0.52%   |
| 1360x768           | 22        | 0.47%   |
| 1024x768 (XGA)     | 21        | 0.45%   |
| 1600x1200          | 18        | 0.39%   |
| 3840x1080          | 14        | 0.3%    |
| 1920x540           | 11        | 0.24%   |
| 800x1280           | 9         | 0.19%   |
| 2160x1440          | 9         | 0.19%   |
| 3840x2400          | 8         | 0.17%   |
| 2880x1800          | 8         | 0.17%   |
| 3200x1800 (QHD+)   | 7         | 0.15%   |
| 1280x720 (HD)      | 7         | 0.15%   |
| 2048x1152          | 5         | 0.11%   |
| 2288x1287          | 4         | 0.09%   |
| 1680x945           | 4         | 0.09%   |
| 1400x1050          | 4         | 0.09%   |
| 5120x1440          | 3         | 0.06%   |
| 3840x1600          | 3         | 0.06%   |
| 3286x1080          | 3         | 0.06%   |
| 3200x1080          | 3         | 0.06%   |
| 1280x960           | 3         | 0.06%   |
| 1280x768           | 3         | 0.06%   |
| 5760x1080          | 2         | 0.04%   |
| 4480x1440          | 2         | 0.04%   |
| 3840x1200          | 2         | 0.04%   |
| 3600x1080          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1331      | 27.09%  |
| 24      | 387       | 7.88%   |
| 13      | 378       | 7.69%   |
| 14      | 349       | 7.1%    |
| 23      | 337       | 6.86%   |
| 17      | 316       | 6.43%   |
| 21      | 295       | 6%      |
| 27      | 289       | 5.88%   |
| Unknown | 255       | 5.19%   |
| 19      | 177       | 3.6%    |
| 22      | 102       | 2.08%   |
| 12      | 96        | 1.95%   |
| 34      | 78        | 1.59%   |
| 18      | 74        | 1.51%   |
| 31      | 55        | 1.12%   |
| 20      | 47        | 0.96%   |
| 11      | 40        | 0.81%   |
| 25      | 32        | 0.65%   |
| 10      | 30        | 0.61%   |
| 84      | 28        | 0.57%   |
| 72      | 26        | 0.53%   |
| 16      | 26        | 0.53%   |
| 32      | 22        | 0.45%   |
| 40      | 21        | 0.43%   |
| 54      | 15        | 0.31%   |
| 48      | 13        | 0.26%   |
| 33      | 10        | 0.2%    |
| 65      | 9         | 0.18%   |
| 42      | 8         | 0.16%   |
| 28      | 8         | 0.16%   |
| 46      | 6         | 0.12%   |
| 26      | 6         | 0.12%   |
| 7       | 6         | 0.12%   |
| 43      | 5         | 0.1%    |
| 37      | 5         | 0.1%    |
| 49      | 4         | 0.08%   |
| 39      | 4         | 0.08%   |
| 142     | 3         | 0.06%   |
| 55      | 3         | 0.06%   |
| 35      | 3         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1939      | 40.24%  |
| 501-600        | 965       | 20.02%  |
| 401-500        | 572       | 11.87%  |
| 351-400        | 393       | 8.16%   |
| 201-300        | 332       | 6.89%   |
| Unknown        | 255       | 5.29%   |
| 701-800        | 111       | 2.3%    |
| 601-700        | 84        | 1.74%   |
| 1001-1500      | 56        | 1.16%   |
| 1501-2000      | 54        | 1.12%   |
| 801-900        | 34        | 0.71%   |
| 901-1000       | 13        | 0.27%   |
| 1-100          | 7         | 0.15%   |
| More than 2000 | 3         | 0.06%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3128      | 70.87%  |
| 16/10   | 653       | 14.79%  |
| Unknown | 222       | 5.03%   |
| 5/4     | 202       | 4.58%   |
| 21/9    | 85        | 1.93%   |
| 4/3     | 49        | 1.11%   |
| 3/2     | 47        | 1.06%   |
| 32/9    | 9         | 0.2%    |
| 0.67    | 6         | 0.14%   |
| 6/5     | 5         | 0.11%   |
| 0.62    | 4         | 0.09%   |
| 1.00    | 3         | 0.07%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1325      | 27.22%  |
| 201-250        | 863       | 17.73%  |
| 81-90          | 577       | 11.86%  |
| 151-200        | 298       | 6.12%   |
| 301-350        | 293       | 6.02%   |
| Unknown        | 255       | 5.24%   |
| 251-300        | 198       | 4.07%   |
| 121-130        | 181       | 3.72%   |
| 351-500        | 174       | 3.58%   |
| 141-150        | 150       | 3.08%   |
| 71-80          | 141       | 2.9%    |
| More than 1000 | 103       | 2.12%   |
| 61-70          | 93        | 1.91%   |
| 501-1000       | 55        | 1.13%   |
| 131-140        | 43        | 0.88%   |
| 51-60          | 40        | 0.82%   |
| 41-50          | 30        | 0.62%   |
| 111-120        | 20        | 0.41%   |
| 91-100         | 20        | 0.41%   |
| 1-40           | 8         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1660      | 35.17%  |
| 121-160       | 1270      | 26.91%  |
| 101-120       | 1207      | 25.57%  |
| Unknown       | 255       | 5.4%    |
| 161-240       | 177       | 3.75%   |
| 1-50          | 86        | 1.82%   |
| More than 240 | 65        | 1.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3593      | 78.59%  |
| 2     | 678       | 14.83%  |
| 0     | 185       | 4.05%   |
| 3     | 100       | 2.19%   |
| 4     | 14        | 0.31%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2263      | 32.9%   |
| Intel                                  | 2186      | 31.78%  |
| Qualcomm Atheros                       | 830       | 12.07%  |
| Broadcom                               | 401       | 5.83%   |
| Broadcom Limited                       | 117       | 1.7%    |
| TP-Link                                | 98        | 1.42%   |
| Marvell Technology Group               | 89        | 1.29%   |
| Huawei Technologies                    | 87        | 1.26%   |
| Dell                                   | 75        | 1.09%   |
| Ralink                                 | 67        | 0.97%   |
| Ralink Technology                      | 66        | 0.96%   |
| Nvidia                                 | 62        | 0.9%    |
| MediaTek                               | 61        | 0.89%   |
| Qualcomm Atheros Communications        | 48        | 0.7%    |
| Samsung Electronics                    | 39        | 0.57%   |
| Xiaomi                                 | 33        | 0.48%   |
| Microsoft                              | 29        | 0.42%   |
| Ericsson Business Mobile Networks      | 25        | 0.36%   |
| ASUSTek Computer                       | 25        | 0.36%   |
| Hewlett-Packard                        | 22        | 0.32%   |
| JMicron Technology                     | 17        | 0.25%   |
| Sierra Wireless                        | 16        | 0.23%   |
| ASIX Electronics                       | 14        | 0.2%    |
| Lenovo                                 | 13        | 0.19%   |
| NetGear                                | 11        | 0.16%   |
| Motorola PCS                           | 11        | 0.16%   |
| Edimax Technology                      | 11        | 0.16%   |
| VIA Technologies                       | 10        | 0.15%   |
| DisplayLink                            | 10        | 0.15%   |
| Aquantia                               | 10        | 0.15%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.13%   |
| D-Link                                 | 9         | 0.13%   |
| Qualcomm                               | 8         | 0.12%   |
| Fibocom                                | 8         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 5         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.07%   |
| Microchip Technology                   | 5         | 0.07%   |
| HTC (High Tech Computer)               | 5         | 0.07%   |
| Sagem                                  | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1640      | 20.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 248       | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 223       | 2.77%   |
| Intel Wi-Fi 6 AX200                                               | 160       | 1.99%   |
| Intel Wireless 8265 / 8275                                        | 126       | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 125       | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 113       | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 109       | 1.35%   |
| Intel Wireless 7260                                               | 108       | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 93        | 1.15%   |
| Intel Wireless 8260                                               | 93        | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 88        | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 82        | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 81        | 1.01%   |
| Intel I211 Gigabit Network Connection                             | 75        | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 75        | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 74        | 0.92%   |
| Intel Wi-Fi 6 AX201                                               | 73        | 0.91%   |
| Intel Ethernet Connection I217-LM                                 | 72        | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 71        | 0.88%   |
| Intel Wireless 7265                                               | 70        | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 67        | 0.83%   |
| Intel Wireless 3160                                               | 62        | 0.77%   |
| Intel Wireless 3165                                               | 58        | 0.72%   |
| Intel Ethernet Connection (2) I219-V                              | 56        | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 53        | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 52        | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 51        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 50        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 50        | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 50        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 49        | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 47        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 47        | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 47        | 0.58%   |
| Huawei E353/E3131                                                 | 47        | 0.58%   |
| Intel Centrino Ultimate-N 6300                                    | 45        | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 45        | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 43        | 0.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 43        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1682      | 47.15%  |
| Qualcomm Atheros                | 633       | 17.75%  |
| Realtek Semiconductor           | 440       | 12.34%  |
| Broadcom                        | 237       | 6.64%   |
| TP-Link                         | 93        | 2.61%   |
| Ralink                          | 67        | 1.88%   |
| Ralink Technology               | 66        | 1.85%   |
| MediaTek                        | 57        | 1.6%    |
| Broadcom Limited                | 57        | 1.6%    |
| Qualcomm Atheros Communications | 48        | 1.35%   |
| Dell                            | 47        | 1.32%   |
| Microsoft                       | 29        | 0.81%   |
| ASUSTek Computer                | 25        | 0.7%    |
| Sierra Wireless                 | 16        | 0.45%   |
| Edimax Technology               | 11        | 0.31%   |
| D-Link                          | 9         | 0.25%   |
| Fibocom                         | 8         | 0.22%   |
| NetGear                         | 7         | 0.2%    |
| Hewlett-Packard                 | 6         | 0.17%   |
| Qualcomm                        | 5         | 0.14%   |
| Sagem                           | 4         | 0.11%   |
| D-Link System                   | 3         | 0.08%   |
| Belkin Components               | 3         | 0.08%   |
| ZyXEL Communications            | 2         | 0.06%   |
| ZyDAS                           | 2         | 0.06%   |
| Linksys                         | 2         | 0.06%   |
| Z-Com                           | 1         | 0.03%   |
| Wacom                           | 1         | 0.03%   |
| Tenda                           | 1         | 0.03%   |
| Sweex                           | 1         | 0.03%   |
| Marvell Technology Group        | 1         | 0.03%   |
| IMC Networks                    | 1         | 0.03%   |
| AVM                             | 1         | 0.03%   |
| Accton Technology               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 160       | 4.47%   |
| Intel Wireless 8265 / 8275                                              | 126       | 3.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 125       | 3.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 113       | 3.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 109       | 3.05%   |
| Intel Wireless 7260                                                     | 108       | 3.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 93        | 2.6%    |
| Intel Wireless 8260                                                     | 93        | 2.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 88        | 2.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 81        | 2.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 75        | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 74        | 2.07%   |
| Intel Wi-Fi 6 AX201                                                     | 73        | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 71        | 1.98%   |
| Intel Wireless 7265                                                     | 70        | 1.96%   |
| Intel Wireless 3160                                                     | 62        | 1.73%   |
| Intel Wireless 3165                                                     | 58        | 1.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 53        | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 52        | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 50        | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 50        | 1.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 49        | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 47        | 1.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 47        | 1.31%   |
| Intel Centrino Ultimate-N 6300                                          | 45        | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 45        | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 43        | 1.2%    |
| Intel WiFi Link 5100                                                    | 42        | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 1.09%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 38        | 1.06%   |
| Qualcomm Atheros AR9271 802.11n                                         | 37        | 1.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 35        | 0.98%   |
| Intel Wireless-AC 9260                                                  | 35        | 0.98%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 0.92%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 32        | 0.89%   |
| Intel Centrino Advanced-N 6235                                          | 32        | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 31        | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 0.87%   |
| Ralink MT7601U Wireless Adapter                                         | 30        | 0.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 29        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2085      | 48.74%  |
| Intel                                  | 1200      | 28.05%  |
| Qualcomm Atheros                       | 287       | 6.71%   |
| Broadcom                               | 204       | 4.77%   |
| Marvell Technology Group               | 89        | 2.08%   |
| Nvidia                                 | 62        | 1.45%   |
| Broadcom Limited                       | 61        | 1.43%   |
| Huawei Technologies                    | 58        | 1.36%   |
| Samsung Electronics                    | 37        | 0.86%   |
| Xiaomi                                 | 32        | 0.75%   |
| JMicron Technology                     | 17        | 0.4%    |
| ASIX Electronics                       | 14        | 0.33%   |
| Lenovo                                 | 13        | 0.3%    |
| VIA Technologies                       | 10        | 0.23%   |
| Motorola PCS                           | 10        | 0.23%   |
| DisplayLink                            | 10        | 0.23%   |
| Aquantia                               | 10        | 0.23%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.21%   |
| TP-Link                                | 6         | 0.14%   |
| Microchip Technology                   | 5         | 0.12%   |
| HTC (High Tech Computer)               | 5         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.09%   |
| NetGear                                | 4         | 0.09%   |
| Qualcomm                               | 3         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.07%   |
| MediaTek                               | 3         | 0.07%   |
| ICS Advent                             | 3         | 0.07%   |
| Hewlett-Packard                        | 3         | 0.07%   |
| Attansic Technology                    | 3         | 0.07%   |
| Apple                                  | 3         | 0.07%   |
| Research In Motion                     | 2         | 0.05%   |
| QLogic                                 | 2         | 0.05%   |
| OPPO Electronics                       | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| 3Com                                   | 2         | 0.05%   |
| QinHeng Electronics                    | 1         | 0.02%   |
| NetXen Incorporated                    | 1         | 0.02%   |
| Mellanox Technologies                  | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1640      | 37.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 248       | 5.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 223       | 5.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 82        | 1.89%   |
| Intel I211 Gigabit Network Connection                             | 75        | 1.73%   |
| Intel Ethernet Connection I217-LM                                 | 72        | 1.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 67        | 1.54%   |
| Intel Ethernet Connection (2) I219-V                              | 56        | 1.29%   |
| Intel 82579V Gigabit Network Connection                           | 51        | 1.17%   |
| Intel 82567LM Gigabit Network Connection                          | 50        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 47        | 1.08%   |
| Huawei E353/E3131                                                 | 47        | 1.08%   |
| Intel Ethernet Connection I218-LM                                 | 43        | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 40        | 0.92%   |
| Intel 82577LM Gigabit Network Connection                          | 40        | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 39        | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 38        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 32        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 32        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 32        | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 31        | 0.71%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 30        | 0.69%   |
| Intel Ethernet Connection (6) I219-V                              | 29        | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 28        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 25        | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 25        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 24        | 0.55%   |
| Intel Ethernet Controller I225-V                                  | 24        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 23        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 23        | 0.53%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 22        | 0.51%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.51%   |
| Intel Ethernet Connection (2) I218-V                              | 20        | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 20        | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 19        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 19        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4015      | 53.53%  |
| WiFi     | 3354      | 44.71%  |
| Modem    | 119       | 1.59%   |
| Unknown  | 13        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2574      | 56.8%   |
| Ethernet | 1957      | 43.18%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2619      | 58.67%  |
| 1     | 1670      | 37.41%  |
| 0     | 94        | 2.11%   |
| 3     | 58        | 1.3%    |
| 4     | 13        | 0.29%   |
| 5     | 4         | 0.09%   |
| 6     | 2         | 0.04%   |
| 17    | 1         | 0.02%   |
| 10    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4181      | 93.24%  |
| Yes  | 303       | 6.76%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1169      | 45.92%  |
| Qualcomm Atheros Communications | 238       | 9.35%   |
| Broadcom                        | 178       | 6.99%   |
| Realtek Semiconductor           | 163       | 6.4%    |
| Cambridge Silicon Radio         | 156       | 6.13%   |
| IMC Networks                    | 106       | 4.16%   |
| ASUSTek Computer                | 91        | 3.57%   |
| Dell                            | 83        | 3.26%   |
| Foxconn / Hon Hai               | 70        | 2.75%   |
| Lite-On Technology              | 61        | 2.4%    |
| Hewlett-Packard                 | 59        | 2.32%   |
| Apple                           | 37        | 1.45%   |
| Toshiba                         | 26        | 1.02%   |
| Ralink                          | 18        | 0.71%   |
| Foxconn International           | 15        | 0.59%   |
| Realtek                         | 11        | 0.43%   |
| MediaTek                        | 8         | 0.31%   |
| TP-Link                         | 7         | 0.27%   |
| Integrated System Solution      | 7         | 0.27%   |
| Alps Electric                   | 7         | 0.27%   |
| Chicony Electronics             | 6         | 0.24%   |
| Taiyo Yuden                     | 5         | 0.2%    |
| Edimax Technology               | 5         | 0.2%    |
| Ralink Technology               | 3         | 0.12%   |
| Conwise Technology              | 3         | 0.12%   |
| USI                             | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| Askey Computer                  | 2         | 0.08%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 508       | 19.94%  |
| Intel AX201 Bluetooth                               | 164       | 6.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 156       | 6.12%   |
| Intel AX200 Bluetooth                               | 153       | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 152       | 5.97%   |
| Realtek Bluetooth Radio                             | 104       | 4.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 102       | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 56        | 2.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 52        | 2.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 50        | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 49        | 1.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 45        | 1.77%   |
| IMC Networks Bluetooth Radio                        | 42        | 1.65%   |
| Broadcom BCM2045B (BDC-2.1)                         | 38        | 1.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 33        | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 31        | 1.22%   |
| Dell BCM20702A0 Bluetooth Module                    | 26        | 1.02%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 25        | 0.98%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.94%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 0.9%    |
| Dell DW375 Bluetooth Module                         | 22        | 0.86%   |
| IMC Networks Wireless_Device                        | 20        | 0.78%   |
| IMC Networks Bluetooth Device                       | 19        | 0.75%   |
| Ralink RT3290 Bluetooth                             | 18        | 0.71%   |
| Intel AX210 Bluetooth                               | 18        | 0.71%   |
| Apple Bluetooth Host Controller                     | 18        | 0.71%   |
| Realtek RTL8723B Bluetooth                          | 17        | 0.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 0.67%   |
| Lite-On Bluetooth Device                            | 17        | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.67%   |
| Broadcom BCM2070 Bluetooth Device                   | 17        | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.59%   |
| Foxconn International BCM43142A0 Bluetooth module   | 15        | 0.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.55%   |
| Intel Bluetooth Device                              | 14        | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.51%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.51%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 12        | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3229      | 52.86%  |
| AMD                                  | 1203      | 19.69%  |
| Nvidia                               | 1087      | 17.79%  |
| C-Media Electronics                  | 84        | 1.38%   |
| Creative Labs                        | 80        | 1.31%   |
| Creative Technology                  | 45        | 0.74%   |
| Logitech                             | 25        | 0.41%   |
| Realtek Semiconductor                | 22        | 0.36%   |
| VIA Technologies                     | 20        | 0.33%   |
| Texas Instruments                    | 19        | 0.31%   |
| JMTek                                | 19        | 0.31%   |
| Plantronics                          | 17        | 0.28%   |
| Lenovo                               | 15        | 0.25%   |
| SteelSeries ApS                      | 14        | 0.23%   |
| Kingston Technology                  | 14        | 0.23%   |
| GN Netcom                            | 12        | 0.2%    |
| Silicon Integrated Systems [SiS]     | 11        | 0.18%   |
| GYROCOM C&C                          | 11        | 0.18%   |
| Generalplus Technology               | 11        | 0.18%   |
| Dell                                 | 11        | 0.18%   |
| SAVITECH                             | 7         | 0.11%   |
| Hewlett-Packard                      | 7         | 0.11%   |
| Focusrite-Novation                   | 7         | 0.11%   |
| Razer USA                            | 6         | 0.1%    |
| BEHRINGER International              | 6         | 0.1%    |
| ASUSTek Computer                     | 6         | 0.1%    |
| Sony                                 | 5         | 0.08%   |
| Samson Technologies                  | 5         | 0.08%   |
| AudioQuest                           | 5         | 0.08%   |
| Valve Software                       | 4         | 0.07%   |
| Sennheiser Communications            | 4         | 0.07%   |
| RODE Microphones                     | 4         | 0.07%   |
| M-Audio                              | 4         | 0.07%   |
| USB MICROPHONE                       | 3         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.05%   |
| PreSonus Audio Electronics           | 3         | 0.05%   |
| DCMT Technology                      | 3         | 0.05%   |
| Corsair                              | 3         | 0.05%   |
| Cambridge Audio                      | 3         | 0.05%   |
| AOKEO                                | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 359       | 4.99%   |
| AMD Family 17h/19h HD Audio Controller                                     | 301       | 4.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 286       | 3.97%   |
| Intel Sunrise Point-LP HD Audio                                            | 273       | 3.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 230       | 3.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 212       | 2.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 190       | 2.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 183       | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 178       | 2.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 163       | 2.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 156       | 2.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 151       | 2.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 145       | 2.02%   |
| AMD FCH Azalia Controller                                                  | 138       | 1.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 133       | 1.85%   |
| Intel 8 Series HD Audio Controller                                         | 129       | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                      | 127       | 1.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 124       | 1.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 117       | 1.63%   |
| Intel Broadwell-U Audio Controller                                         | 109       | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                            | 107       | 1.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 107       | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 105       | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 93        | 1.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 92        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                              | 90        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 86        | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 79        | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 70        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 67        | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 64        | 0.89%   |
| Intel 200 Series PCH HD Audio                                              | 63        | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 59        | 0.82%   |
| Intel CM238 HD Audio Controller                                            | 58        | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 55        | 0.76%   |
| Nvidia High Definition Audio Controller                                    | 53        | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                              | 53        | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 52        | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 50        | 0.69%   |
| Intel Comet Lake PCH cAVS                                                  | 49        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 687       | 20.96%  |
| SK hynix                     | 544       | 16.6%   |
| Kingston                     | 436       | 13.3%   |
| Unknown                      | 393       | 11.99%  |
| Micron Technology            | 268       | 8.18%   |
| GOODRAM                      | 201       | 6.13%   |
| Crucial                      | 147       | 4.49%   |
| G.Skill                      | 91        | 2.78%   |
| Corsair                      | 76        | 2.32%   |
| A-DATA Technology            | 72        | 2.2%    |
| Ramaxel Technology           | 57        | 1.74%   |
| Patriot                      | 53        | 1.62%   |
| Nanya Technology             | 51        | 1.56%   |
| Elpida                       | 46        | 1.4%    |
| Unknown                      | 22        | 0.67%   |
| Wilk                         | 17        | 0.52%   |
| Unknown (ABCD)               | 13        | 0.4%    |
| Qimonda                      | 13        | 0.4%    |
| Apacer                       | 11        | 0.34%   |
| Wilk Elektronik              | 9         | 0.27%   |
| GeIL                         | 9         | 0.27%   |
| ASint Technology             | 9         | 0.27%   |
| Unifosa                      | 4         | 0.12%   |
| Patriot Memory (PDP Systems) | 4         | 0.12%   |
| 48spaces                     | 4         | 0.12%   |
| Silicon Power                | 3         | 0.09%   |
| OCZ                          | 3         | 0.09%   |
| Transcend                    | 2         | 0.06%   |
| Toshiba                      | 2         | 0.06%   |
| Team                         | 2         | 0.06%   |
| SHARETRONIC                  | 2         | 0.06%   |
| PNY                          | 2         | 0.06%   |
| fef5                         | 2         | 0.06%   |
| AMD                          | 2         | 0.06%   |
| Aeneon                       | 2         | 0.06%   |
| Unknown (8A02)               | 1         | 0.03%   |
| Unknown (768A)               | 1         | 0.03%   |
| Unknown (0x7FFF)             | 1         | 0.03%   |
| Unknown (0x0702)             | 1         | 0.03%   |
| tigo                         | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s   | 36        | 1.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 32        | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 31        | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s  | 27        | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 26        | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 26        | 0.73%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 25        | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 24        | 0.67%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s | 23        | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 22        | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 22        | 0.61%   |
| Unknown                                                 | 22        | 0.61%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 21        | 0.59%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s   | 20        | 0.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s   | 20        | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 19        | 0.53%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s   | 19        | 0.53%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 18        | 0.5%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s  | 17        | 0.47%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s     | 16        | 0.45%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s   | 16        | 0.45%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s    | 15        | 0.42%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s   | 15        | 0.42%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s | 15        | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 14        | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 14        | 0.39%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 14        | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 13        | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s  | 13        | 0.36%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 13        | 0.36%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 13        | 0.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s   | 13        | 0.36%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s | 13        | 0.36%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 12        | 0.34%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 12        | 0.34%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 12        | 0.34%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s   | 12        | 0.34%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s   | 12        | 0.34%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s    | 12        | 0.34%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s      | 12        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1102      | 39.65%  |
| DDR3    | 1025      | 36.88%  |
| DDR2    | 226       | 8.13%   |
| Unknown | 135       | 4.86%   |
| SDRAM   | 128       | 4.61%   |
| LPDDR4  | 59        | 2.12%   |
| LPDDR3  | 40        | 1.44%   |
| DDR     | 31        | 1.12%   |
| DDR5    | 19        | 0.68%   |
| LPDDR5  | 8         | 0.29%   |
| DRAM    | 6         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1640      | 60.07%  |
| DIMM            | 972       | 35.6%   |
| Row Of Chips    | 94        | 3.44%   |
| Chip            | 12        | 0.44%   |
| Unknown         | 8         | 0.29%   |
| RIMM            | 2         | 0.07%   |
| Proprietary Car | 1         | 0.04%   |
| FB-DIMM         | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 934       | 30.57%  |
| 4096    | 853       | 27.92%  |
| 2048    | 537       | 17.58%  |
| 16384   | 413       | 13.52%  |
| 1024    | 192       | 6.28%   |
| 32768   | 90        | 2.95%   |
| 512     | 26        | 0.85%   |
| Unknown | 4         | 0.13%   |
| 1536    | 2         | 0.07%   |
| 256     | 2         | 0.07%   |
| 131072  | 1         | 0.03%   |
| 64      | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 692       | 22.7%   |
| 2667    | 391       | 12.82%  |
| 3200    | 351       | 11.51%  |
| 1333    | 205       | 6.72%   |
| 2400    | 182       | 5.97%   |
| 1334    | 128       | 4.2%    |
| 667     | 125       | 4.1%    |
| 2133    | 123       | 4.03%   |
| 800     | 115       | 3.77%   |
| Unknown | 78        | 2.56%   |
| 3600    | 71        | 2.33%   |
| 1067    | 53        | 1.74%   |
| 4199    | 42        | 1.38%   |
| 1867    | 37        | 1.21%   |
| 3266    | 36        | 1.18%   |
| 533     | 31        | 1.02%   |
| 3000    | 26        | 0.85%   |
| 2048    | 26        | 0.85%   |
| 1066    | 26        | 0.85%   |
| 975     | 25        | 0.82%   |
| 3400    | 20        | 0.66%   |
| 400     | 19        | 0.62%   |
| 4800    | 18        | 0.59%   |
| 4267    | 18        | 0.59%   |
| 1866    | 17        | 0.56%   |
| 3466    | 16        | 0.52%   |
| 3866    | 15        | 0.49%   |
| 2933    | 15        | 0.49%   |
| 3733    | 14        | 0.46%   |
| 1800    | 13        | 0.43%   |
| 2666    | 12        | 0.39%   |
| 8400    | 11        | 0.36%   |
| 333     | 10        | 0.33%   |
| 6400    | 9         | 0.3%    |
| 3800    | 8         | 0.26%   |
| 2866    | 7         | 0.23%   |
| 49926   | 5         | 0.16%   |
| 4266    | 5         | 0.16%   |
| 2800    | 5         | 0.16%   |
| 2000    | 4         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 48        | 45.28%  |
| Samsung Electronics   | 15        | 14.15%  |
| Brother Industries    | 12        | 11.32%  |
| Canon                 | 10        | 9.43%   |
| Seiko Epson           | 7         | 6.6%    |
| Prolific Technology   | 5         | 4.72%   |
| Zebra                 | 3         | 2.83%   |
| Xerox                 | 2         | 1.89%   |
| Lexmark International | 2         | 1.89%   |
| MIIIW                 | 1         | 0.94%   |
| Datamax-O'Neil        | 1         | 0.94%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port           | 5         | 4.63%   |
| HP LaserJet 1020                        | 4         | 3.7%    |
| Samsung M2020 Series                    | 3         | 2.78%   |
| HP LaserJet P2015 series                | 3         | 2.78%   |
| Canon iP7200 series                     | 3         | 2.78%   |
| Seiko Epson AL-M310DN                   | 2         | 1.85%   |
| Samsung SCX-3400 Series                 | 2         | 1.85%   |
| Samsung ML-216x Series Laser Printer    | 2         | 1.85%   |
| Samsung ML-2010P Mono Laser Printer     | 2         | 1.85%   |
| HP LaserJet P1102                       | 2         | 1.85%   |
| HP LaserJet M14-M17                     | 2         | 1.85%   |
| HP Deskjet F4500 series                 | 2         | 1.85%   |
| HP DeskJet F4100 Printer series         | 2         | 1.85%   |
| HP Deskjet F2280 series                 | 2         | 1.85%   |
| HP DeskJet 845c                         | 2         | 1.85%   |
| HP DeskJet 840c                         | 2         | 1.85%   |
| HP DeskJet 3700 series                  | 2         | 1.85%   |
| HP DeskJet 2600 series                  | 2         | 1.85%   |
| HP Deskjet 2540 series                  | 2         | 1.85%   |
| HP Deskjet 1050 J410                    | 2         | 1.85%   |
| Canon MG5600 series                     | 2         | 1.85%   |
| Canon LiDE 400                          | 2         | 1.85%   |
| Brother DCP-J105                        | 2         | 1.85%   |
| Brother DCP-1610W                       | 2         | 1.85%   |
| Zebra ZTC GX420t                        | 1         | 0.93%   |
| Zebra LP2844 Printer                    | 1         | 0.93%   |
| Zebra LP2824                            | 1         | 0.93%   |
| Xerox WorkCentre PE16                   | 1         | 0.93%   |
| Xerox Phaser 6000B                      | 1         | 0.93%   |
| Seiko Epson Stylus NX230/SX235W Series  | 1         | 0.93%   |
| Seiko Epson L405 Series                 | 1         | 0.93%   |
| Seiko Epson L396 Series                 | 1         | 0.93%   |
| Seiko Epson L1110 Series                | 1         | 0.93%   |
| Seiko Epson ET-2710 Series              | 1         | 0.93%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 0.93%   |
| Samsung SCX-6545 Series                 | 1         | 0.93%   |
| Samsung SCX-4300 Series                 | 1         | 0.93%   |
| Samsung SCX-4200 series                 | 1         | 0.93%   |
| Samsung ML-3050/ML-3051 Laser Printer   | 1         | 0.93%   |
| Samsung ML-2540 Series Laser Printer    | 1         | 0.93%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 11        | 61.11%  |
| Seiko Epson                 | 2         | 11.11%  |
| Plustek                     | 2         | 11.11%  |
| Ultima Electronics          | 1         | 5.56%   |
| Microtek International      | 1         | 5.56%   |
| Acer Peripherals (now BenQ) | 1         | 5.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 3         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 11.11%  |
| Canon CanoScan LiDE 120                                  | 2         | 11.11%  |
| Canon CanoScan LiDE 110                                  | 2         | 11.11%  |
| Ultima Artec E+ 48U                                      | 1         | 5.56%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 5.56%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 5.56%   |
| Plustek OpticSlim 1200 Scanner                           | 1         | 5.56%   |
| Plustek OpticPro 1248U Scanner #2                        | 1         | 5.56%   |
| Microtek International USB1200 Scanner                   | 1         | 5.56%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                   | 1         | 5.56%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 564       | 22.02%  |
| Microdia                               | 263       | 10.27%  |
| IMC Networks                           | 246       | 9.61%   |
| Realtek Semiconductor                  | 216       | 8.43%   |
| Acer                                   | 157       | 6.13%   |
| Sunplus Innovation Technology          | 130       | 5.08%   |
| Quanta                                 | 114       | 4.45%   |
| Suyin                                  | 107       | 4.18%   |
| Logitech                               | 98        | 3.83%   |
| Cheng Uei Precision Industry (Foxlink) | 86        | 3.36%   |
| Syntek                                 | 76        | 2.97%   |
| Lite-On Technology                     | 58        | 2.26%   |
| Silicon Motion                         | 52        | 2.03%   |
| Apple                                  | 35        | 1.37%   |
| Creative Technology                    | 34        | 1.33%   |
| Bison Electronics                      | 33        | 1.29%   |
| Ricoh                                  | 29        | 1.13%   |
| Alcor Micro                            | 28        | 1.09%   |
| Lenovo                                 | 26        | 1.02%   |
| Luxvisions Innotech Limited            | 23        | 0.9%    |
| Z-Star Microelectronics                | 22        | 0.86%   |
| Samsung Electronics                    | 19        | 0.74%   |
| Microsoft                              | 17        | 0.66%   |
| DigiTech                               | 11        | 0.43%   |
| Primax Electronics                     | 9         | 0.35%   |
| Intel                                  | 9         | 0.35%   |
| Generalplus Technology                 | 8         | 0.31%   |
| Cubeternet                             | 8         | 0.31%   |
| ALi                                    | 8         | 0.31%   |
| Sonix Technology                       | 7         | 0.27%   |
| Hewlett-Packard                        | 7         | 0.27%   |
| LG Electronics                         | 4         | 0.16%   |
| Jieli Technology                       | 4         | 0.16%   |
| Importek                               | 4         | 0.16%   |
| GEMBIRD                                | 4         | 0.16%   |
| Aveo Technology                        | 4         | 0.16%   |
| Xiongmai                               | 3         | 0.12%   |
| Trust                                  | 3         | 0.12%   |
| Sunplus Technology                     | 3         | 0.12%   |
| Razer USA                              | 3         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 116       | 4.52%   |
| Microdia Integrated_Webcam_HD            | 84        | 3.27%   |
| Realtek Integrated_Webcam_HD             | 75        | 2.92%   |
| IMC Networks Integrated Camera           | 66        | 2.57%   |
| IMC Networks USB2.0 HD UVC WebCam        | 60        | 2.34%   |
| Sunplus Integrated_Webcam_HD             | 53        | 2.06%   |
| Chicony Lenovo EasyCamera                | 44        | 1.71%   |
| Microdia Integrated Webcam               | 38        | 1.48%   |
| Chicony HD WebCam                        | 38        | 1.48%   |
| Acer Lenovo EasyCamera                   | 37        | 1.44%   |
| Suyin Integrated_Webcam_HD               | 35        | 1.36%   |
| Syntek Lenovo EasyCamera                 | 29        | 1.13%   |
| Syntek Integrated Camera                 | 27        | 1.05%   |
| Realtek Lenovo EasyCamera                | 27        | 1.05%   |
| Lite-On Integrated Camera                | 24        | 0.93%   |
| Logitech Webcam C270                     | 23        | 0.9%    |
| Chicony USB2.0 HD UVC WebCam             | 23        | 0.9%    |
| Quanta HP TrueVision HD Camera           | 22        | 0.86%   |
| Acer Integrated Camera                   | 22        | 0.86%   |
| Realtek USB Camera                       | 21        | 0.82%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 20        | 0.78%   |
| Chicony HP HD Camera                     | 20        | 0.78%   |
| Acer Lenovo Integrated Webcam            | 20        | 0.78%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 18        | 0.7%    |
| Quanta HD User Facing                    | 18        | 0.7%    |
| Creative Live! Cam Sync HD [VF0770]      | 18        | 0.7%    |
| Acer SunplusIT Integrated Camera         | 18        | 0.7%    |
| Samsung Galaxy A5 (MTP)                  | 17        | 0.66%   |
| Microdia USB 2.0 Camera                  | 17        | 0.66%   |
| Microdia Laptop_Integrated_Webcam_HD     | 17        | 0.66%   |
| IMC Networks Integrated Webcam           | 17        | 0.66%   |
| Bison Integrated Camera                  | 17        | 0.66%   |
| Chicony USB 2.0 Camera                   | 16        | 0.62%   |
| Realtek Integrated Webcam                | 15        | 0.58%   |
| Chicony USB2.0 VGA UVC WebCam            | 15        | 0.58%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 15        | 0.58%   |
| Chicony Integrated Camera (1280x720@30)  | 15        | 0.58%   |
| Logitech HD Pro Webcam C920              | 14        | 0.54%   |
| Lite-On HP HD Camera                     | 14        | 0.54%   |
| Chicony VGA Webcam                       | 14        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 186       | 36.76%  |
| Synaptics                          | 121       | 23.91%  |
| Shenzhen Goodix Technology         | 60        | 11.86%  |
| AuthenTec                          | 57        | 11.26%  |
| Upek                               | 36        | 7.11%   |
| Elan Microelectronics              | 16        | 3.16%   |
| LighTuning Technology              | 15        | 2.96%   |
| STMicroelectronics                 | 14        | 2.77%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 40        | 7.91%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 38        | 7.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 35        | 6.92%   |
| Shenzhen Goodix  FingerPrint Device                                        | 31        | 6.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 24        | 4.74%   |
| Shenzhen Goodix Fingerprint Reader                                         | 24        | 4.74%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 4.55%   |
| AuthenTec AES2810                                                          | 23        | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 3.95%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 3.36%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.77%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 2.77%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 13        | 2.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 2.37%   |
| Validity Sensors VFS491                                                    | 12        | 2.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 2.17%   |
| Elan ELAN:Fingerprint                                                      | 11        | 2.17%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.78%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 1.78%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.78%   |
| Synaptics  WBDI                                                            | 9         | 1.78%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 1.58%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 1.58%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 1.38%   |
| AuthenTec AES1600                                                          | 7         | 1.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.19%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.99%   |
| Synaptics WBDI                                                             | 5         | 0.99%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 0.99%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.99%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.79%   |
| Synaptics UWP WBDI                                                         | 4         | 0.79%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.79%   |
| Elan ELAN:ARM-M4                                                           | 4         | 0.79%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.79%   |
| Synaptics WBDI Device                                                      | 3         | 0.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 211       | 55.24%  |
| Alcor Micro               | 76        | 19.9%   |
| O2 Micro                  | 41        | 10.73%  |
| Lenovo                    | 20        | 5.24%   |
| Upek                      | 19        | 4.97%   |
| Gemalto (was Gemplus)     | 5         | 1.31%   |
| Advanced Card Systems     | 3         | 0.79%   |
| OmniKey                   | 2         | 0.52%   |
| SCM Microsystems          | 1         | 0.26%   |
| Reiner SCT Kartensysteme  | 1         | 0.26%   |
| Clay Logic                | 1         | 0.26%   |
| Cherry                    | 1         | 0.26%   |
| Aladdin Knowledge Systems | 1         | 0.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 73        | 19.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 66        | 17.28%  |
| Broadcom 5880                                                                | 53        | 13.87%  |
| Broadcom 58200                                                               | 53        | 13.87%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 38        | 9.95%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 34        | 8.9%    |
| Lenovo Integrated Smart Card Reader                                          | 20        | 5.24%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 4.97%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.83%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.79%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.52%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.52%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.52%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.52%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.26%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.26%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.26%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.26%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.26%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.26%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3093      | 67.68%  |
| 1     | 1151      | 25.19%  |
| 2     | 274       | 6%      |
| 3     | 41        | 0.9%    |
| 4     | 5         | 0.11%   |
| 7     | 3         | 0.07%   |
| 5     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 501       | 27.88%  |
| Graphics card            | 443       | 24.65%  |
| Chipcard                 | 342       | 19.03%  |
| Net/wireless             | 154       | 8.57%   |
| Multimedia controller    | 60        | 3.34%   |
| Storage                  | 49        | 2.73%   |
| Communication controller | 49        | 2.73%   |
| Bluetooth                | 47        | 2.62%   |
| Camera                   | 36        | 2%      |
| Unassigned class         | 26        | 1.45%   |
| Sound                    | 22        | 1.22%   |
| Card reader              | 17        | 0.95%   |
| Modem                    | 9         | 0.5%    |
| Net/ethernet             | 8         | 0.45%   |
| Network                  | 7         | 0.39%   |
| Firewire controller      | 7         | 0.39%   |
| Dvb card                 | 6         | 0.33%   |
| Storage/raid             | 4         | 0.22%   |
| Storage/ide              | 4         | 0.22%   |
| Flash memory             | 3         | 0.17%   |
| Wireless                 | 1         | 0.06%   |
| Unclassified device      | 1         | 0.06%   |
| Tv card                  | 1         | 0.06%   |

