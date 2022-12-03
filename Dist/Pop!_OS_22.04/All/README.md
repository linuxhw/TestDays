Pop!_OS 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS_22.04/Desktop/README.md) and [notebooks](/Dist/Pop!_OS_22.04/Notebook/README.md).

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

Total: 2108

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [562e1f4b92](https://linux-hardware.org/?probe=562e1f4b92) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [c8d4cd1faf](https://linux-hardware.org/?probe=c8d4cd1faf) | Dec 01, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [866e8151d7](https://linux-hardware.org/?probe=866e8151d7) | Dec 01, 2022 |
| HP            | Pavilion dv7                | Notebook    | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| Dell          | 07JJ74 A01                  | Server      | [7096492ea2](https://linux-hardware.org/?probe=7096492ea2) | Dec 01, 2022 |
| Dell          | 07JJ74 A01                  | Server      | [cb373247ed](https://linux-hardware.org/?probe=cb373247ed) | Dec 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [62ae8cb7dc](https://linux-hardware.org/?probe=62ae8cb7dc) | Dec 01, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [a7ae37f43e](https://linux-hardware.org/?probe=a7ae37f43e) | Dec 01, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ce6f6fcaad](https://linux-hardware.org/?probe=ce6f6fcaad) | Dec 01, 2022 |
| Unknown       | 1.0                         | Desktop     | [c8cfeaf2be](https://linux-hardware.org/?probe=c8cfeaf2be) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | Notebook    | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [aadf1c39a0](https://linux-hardware.org/?probe=aadf1c39a0) | Dec 01, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [b840a0d02e](https://linux-hardware.org/?probe=b840a0d02e) | Dec 01, 2022 |
| Google        | Cyan                        | Notebook    | [4aa7125981](https://linux-hardware.org/?probe=4aa7125981) | Nov 30, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [b2bba919b2](https://linux-hardware.org/?probe=b2bba919b2) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [66b6e49eb5](https://linux-hardware.org/?probe=66b6e49eb5) | Nov 30, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [b315e85bda](https://linux-hardware.org/?probe=b315e85bda) | Nov 30, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9ad34fe6e2](https://linux-hardware.org/?probe=9ad34fe6e2) | Nov 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [99e23cf04d](https://linux-hardware.org/?probe=99e23cf04d) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [b12534f13d](https://linux-hardware.org/?probe=b12534f13d) | Nov 30, 2022 |
| ASRock        | H77M                        | Desktop     | [ffa3496b0d](https://linux-hardware.org/?probe=ffa3496b0d) | Nov 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a42a4d6080](https://linux-hardware.org/?probe=a42a4d6080) | Nov 29, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [48319e6f46](https://linux-hardware.org/?probe=48319e6f46) | Nov 29, 2022 |
| Dell          | Latitude E7240              | Notebook    | [8b0b984870](https://linux-hardware.org/?probe=8b0b984870) | Nov 29, 2022 |
| HP            | ProBook 450 G8              | Notebook    | [eec30c7857](https://linux-hardware.org/?probe=eec30c7857) | Nov 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [cee0622b1f](https://linux-hardware.org/?probe=cee0622b1f) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | Notebook    | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | Notebook    | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Dell          | Latitude 5411               | Notebook    | [122facad78](https://linux-hardware.org/?probe=122facad78) | Nov 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [151f18b424](https://linux-hardware.org/?probe=151f18b424) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [c0c2f77cdb](https://linux-hardware.org/?probe=c0c2f77cdb) | Nov 28, 2022 |
| Lenovo        | IdeaPad Y560                | Notebook    | [4918810cd1](https://linux-hardware.org/?probe=4918810cd1) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [dee60b9f35](https://linux-hardware.org/?probe=dee60b9f35) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1651962e5a](https://linux-hardware.org/?probe=1651962e5a) | Nov 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [16705fe86c](https://linux-hardware.org/?probe=16705fe86c) | Nov 28, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Clevo         | W55xEU                      | Notebook    | [5ed799ba64](https://linux-hardware.org/?probe=5ed799ba64) | Nov 28, 2022 |
| MSI           | GP72 7RDX                   | Notebook    | [648eb6d88a](https://linux-hardware.org/?probe=648eb6d88a) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [7837242848](https://linux-hardware.org/?probe=7837242848) | Nov 27, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [bf6fc6fd49](https://linux-hardware.org/?probe=bf6fc6fd49) | Nov 27, 2022 |
| Dell          | Latitude E6230              | Notebook    | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | Notebook    | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [1a50d26810](https://linux-hardware.org/?probe=1a50d26810) | Nov 27, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [b924b1fdd6](https://linux-hardware.org/?probe=b924b1fdd6) | Nov 27, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [409c3edc19](https://linux-hardware.org/?probe=409c3edc19) | Nov 27, 2022 |
| HP            | 872E                        | Mini pc     | [9d8a2595d7](https://linux-hardware.org/?probe=9d8a2595d7) | Nov 27, 2022 |
| Alienware     | 17                          | Notebook    | [08ebf1e9a2](https://linux-hardware.org/?probe=08ebf1e9a2) | Nov 27, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [49dc64dc76](https://linux-hardware.org/?probe=49dc64dc76) | Nov 27, 2022 |
| MSI           | Z97A GAMING 7               | Desktop     | [74341c948b](https://linux-hardware.org/?probe=74341c948b) | Nov 27, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [1e016dcb9b](https://linux-hardware.org/?probe=1e016dcb9b) | Nov 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [015854e59a](https://linux-hardware.org/?probe=015854e59a) | Nov 26, 2022 |
| Dell          | 04MFRM A02                  | Desktop     | [43239e45b1](https://linux-hardware.org/?probe=43239e45b1) | Nov 26, 2022 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [a8a722921c](https://linux-hardware.org/?probe=a8a722921c) | Nov 26, 2022 |
| HP            | ZBook 15                    | Notebook    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | Notebook    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Gigabyte      | AORUS 5 SE                  | Notebook    | [d9e1ceb3c1](https://linux-hardware.org/?probe=d9e1ceb3c1) | Nov 26, 2022 |
| HP            | 872E                        | Mini pc     | [c7ff015966](https://linux-hardware.org/?probe=c7ff015966) | Nov 26, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [3afe7122f3](https://linux-hardware.org/?probe=3afe7122f3) | Nov 26, 2022 |
| HUAWEI        | MRGF-XX                     | Notebook    | [f60090b407](https://linux-hardware.org/?probe=f60090b407) | Nov 26, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [8268fc2c12](https://linux-hardware.org/?probe=8268fc2c12) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| Gigabyte      | Z77-HD3                     | Desktop     | [e3b7bbc736](https://linux-hardware.org/?probe=e3b7bbc736) | Nov 25, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [ecfe0cfab0](https://linux-hardware.org/?probe=ecfe0cfab0) | Nov 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [32ab0a36a4](https://linux-hardware.org/?probe=32ab0a36a4) | Nov 25, 2022 |
| Pegatron      | 2A9A                        | Desktop     | [ee74398a78](https://linux-hardware.org/?probe=ee74398a78) | Nov 25, 2022 |
| ASRock        | Z170 Gaming K6              | Desktop     | [de7addf17b](https://linux-hardware.org/?probe=de7addf17b) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [bb91371617](https://linux-hardware.org/?probe=bb91371617) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [770e9d413e](https://linux-hardware.org/?probe=770e9d413e) | Nov 24, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c72c157583](https://linux-hardware.org/?probe=c72c157583) | Nov 24, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [bd50429870](https://linux-hardware.org/?probe=bd50429870) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Lenovo        | IdeaPad Y560                | Notebook    | [154702cbc6](https://linux-hardware.org/?probe=154702cbc6) | Nov 23, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [880f8b9c45](https://linux-hardware.org/?probe=880f8b9c45) | Nov 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| HP            | G62                         | Notebook    | [754a471519](https://linux-hardware.org/?probe=754a471519) | Nov 23, 2022 |
| HP            | 8309                        | Desktop     | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | Notebook    | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Dell          | Latitude E7470              | Notebook    | [03725ebee3](https://linux-hardware.org/?probe=03725ebee3) | Nov 22, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [dc74022dc5](https://linux-hardware.org/?probe=dc74022dc5) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9a3ff03cbb](https://linux-hardware.org/?probe=9a3ff03cbb) | Nov 22, 2022 |
| Gigabyte      | AORUS 5 SE                  | Notebook    | [c88614e7f3](https://linux-hardware.org/?probe=c88614e7f3) | Nov 22, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [e29dda268c](https://linux-hardware.org/?probe=e29dda268c) | Nov 21, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [9627a23b1f](https://linux-hardware.org/?probe=9627a23b1f) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| ASRock        | H310CM-HG4                  | Desktop     | [d4f3608765](https://linux-hardware.org/?probe=d4f3608765) | Nov 21, 2022 |
| Dell          | Precision 7670              | Notebook    | [93f14c8b55](https://linux-hardware.org/?probe=93f14c8b55) | Nov 21, 2022 |
| Alienware     | 17                          | Notebook    | [16b37ce649](https://linux-hardware.org/?probe=16b37ce649) | Nov 21, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [5ec428f8b3](https://linux-hardware.org/?probe=5ec428f8b3) | Nov 21, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d24d3cbf1f](https://linux-hardware.org/?probe=d24d3cbf1f) | Nov 21, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [eed1e72aba](https://linux-hardware.org/?probe=eed1e72aba) | Nov 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | Notebook    | [6355251bd6](https://linux-hardware.org/?probe=6355251bd6) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [cba7abe277](https://linux-hardware.org/?probe=cba7abe277) | Nov 20, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | Notebook    | [6eb57e34de](https://linux-hardware.org/?probe=6eb57e34de) | Nov 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a1b9357fc6](https://linux-hardware.org/?probe=a1b9357fc6) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [d4bb2f3867](https://linux-hardware.org/?probe=d4bb2f3867) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | Notebook    | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| HP            | ProBook 6450b               | Notebook    | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [41ffb4e75f](https://linux-hardware.org/?probe=41ffb4e75f) | Nov 19, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [afdcde154a](https://linux-hardware.org/?probe=afdcde154a) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [ceac47decc](https://linux-hardware.org/?probe=ceac47decc) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [5abeec1752](https://linux-hardware.org/?probe=5abeec1752) | Nov 18, 2022 |
| Dell          | Precision M4400             | Notebook    | [715efc61ae](https://linux-hardware.org/?probe=715efc61ae) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [884474637c](https://linux-hardware.org/?probe=884474637c) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0b7bd42177](https://linux-hardware.org/?probe=0b7bd42177) | Nov 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | Notebook    | [8f4df3bbda](https://linux-hardware.org/?probe=8f4df3bbda) | Nov 18, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [4498bc64bc](https://linux-hardware.org/?probe=4498bc64bc) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | Notebook    | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Lenovo        | ThinkPad T550 20CJS18S00    | Notebook    | [ba94994594](https://linux-hardware.org/?probe=ba94994594) | Nov 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [078e04eb73](https://linux-hardware.org/?probe=078e04eb73) | Nov 17, 2022 |
| Dell          | G15 5515                    | Notebook    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [33f2716179](https://linux-hardware.org/?probe=33f2716179) | Nov 17, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [478fa166bd](https://linux-hardware.org/?probe=478fa166bd) | Nov 17, 2022 |
| HP            | 805D                        | Desktop     | [cb811984e0](https://linux-hardware.org/?probe=cb811984e0) | Nov 17, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [b696d9eae7](https://linux-hardware.org/?probe=b696d9eae7) | Nov 16, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [0a623c060a](https://linux-hardware.org/?probe=0a623c060a) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [5c49c7037b](https://linux-hardware.org/?probe=5c49c7037b) | Nov 16, 2022 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [b7fff356a7](https://linux-hardware.org/?probe=b7fff356a7) | Nov 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c6f5c91413](https://linux-hardware.org/?probe=c6f5c91413) | Nov 16, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [8ce9402aad](https://linux-hardware.org/?probe=8ce9402aad) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | Notebook    | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| Dell          | 04MFRM A02                  | Desktop     | [677ab8eb16](https://linux-hardware.org/?probe=677ab8eb16) | Nov 16, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [9b870d8287](https://linux-hardware.org/?probe=9b870d8287) | Nov 16, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [5a76aee400](https://linux-hardware.org/?probe=5a76aee400) | Nov 16, 2022 |
| ATOPNUC       | MA90                        | Mini pc     | [e48bf6df91](https://linux-hardware.org/?probe=e48bf6df91) | Nov 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [2f6204153a](https://linux-hardware.org/?probe=2f6204153a) | Nov 15, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [bc5218c5da](https://linux-hardware.org/?probe=bc5218c5da) | Nov 15, 2022 |
| OEGStone      | NOTCHA-322                  | Notebook    | [a5f28e095e](https://linux-hardware.org/?probe=a5f28e095e) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| System76      | Oryx Pro                    | Notebook    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | Notebook    | [426dec8739](https://linux-hardware.org/?probe=426dec8739) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | Notebook    | [f55f35c2fe](https://linux-hardware.org/?probe=f55f35c2fe) | Nov 15, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [965a35d0b0](https://linux-hardware.org/?probe=965a35d0b0) | Nov 15, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| HP            | 1998                        | Desktop     | [ddcba37929](https://linux-hardware.org/?probe=ddcba37929) | Nov 14, 2022 |
| HP            | 1998                        | Desktop     | [5249f1cdd7](https://linux-hardware.org/?probe=5249f1cdd7) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [43214de971](https://linux-hardware.org/?probe=43214de971) | Nov 13, 2022 |
| Timi          | TM1613                      | Notebook    | [d038ff5636](https://linux-hardware.org/?probe=d038ff5636) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [7de064ae3a](https://linux-hardware.org/?probe=7de064ae3a) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | Notebook    | [25b89592e0](https://linux-hardware.org/?probe=25b89592e0) | Nov 13, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [092c39d271](https://linux-hardware.org/?probe=092c39d271) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [1e4f22395f](https://linux-hardware.org/?probe=1e4f22395f) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [7325cce71f](https://linux-hardware.org/?probe=7325cce71f) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | Notebook    | [86b0a359fa](https://linux-hardware.org/?probe=86b0a359fa) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [bf79743ff5](https://linux-hardware.org/?probe=bf79743ff5) | Nov 13, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d433817b4f](https://linux-hardware.org/?probe=d433817b4f) | Nov 13, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [8104152607](https://linux-hardware.org/?probe=8104152607) | Nov 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3e75f5aa87](https://linux-hardware.org/?probe=3e75f5aa87) | Nov 12, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [94e5dec391](https://linux-hardware.org/?probe=94e5dec391) | Nov 12, 2022 |
| Dell          | Latitude E7270              | Notebook    | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | 0P4T42 A01                  | All in one  | [c6cc7b7785](https://linux-hardware.org/?probe=c6cc7b7785) | Nov 12, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [c6b54c443e](https://linux-hardware.org/?probe=c6b54c443e) | Nov 12, 2022 |
| Google        | Shyvana                     | Notebook    | [2df69a0782](https://linux-hardware.org/?probe=2df69a0782) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [aec286073d](https://linux-hardware.org/?probe=aec286073d) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [3884507df6](https://linux-hardware.org/?probe=3884507df6) | Nov 11, 2022 |
| Dell          | Precision M4700             | Notebook    | [4fc304d429](https://linux-hardware.org/?probe=4fc304d429) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [8472557f0d](https://linux-hardware.org/?probe=8472557f0d) | Nov 11, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [4ed347e186](https://linux-hardware.org/?probe=4ed347e186) | Nov 11, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [1ce532916f](https://linux-hardware.org/?probe=1ce532916f) | Nov 11, 2022 |
| System76      | Lemur Pro                   | Notebook    | [7df985e36a](https://linux-hardware.org/?probe=7df985e36a) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [a06fb78621](https://linux-hardware.org/?probe=a06fb78621) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b4aa454d9a](https://linux-hardware.org/?probe=b4aa454d9a) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [933683bc04](https://linux-hardware.org/?probe=933683bc04) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [d2e25c9c4e](https://linux-hardware.org/?probe=d2e25c9c4e) | Nov 10, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [4ff6488cb2](https://linux-hardware.org/?probe=4ff6488cb2) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [89aa240b37](https://linux-hardware.org/?probe=89aa240b37) | Nov 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [de9c1a6f3e](https://linux-hardware.org/?probe=de9c1a6f3e) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [12c406f96b](https://linux-hardware.org/?probe=12c406f96b) | Nov 09, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fcd0449df8](https://linux-hardware.org/?probe=fcd0449df8) | Nov 09, 2022 |
| MSI           | MS-1688                     | Notebook    | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [e7fb74c85e](https://linux-hardware.org/?probe=e7fb74c85e) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [0c282237ab](https://linux-hardware.org/?probe=0c282237ab) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [fa94f8afc5](https://linux-hardware.org/?probe=fa94f8afc5) | Nov 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [c4afe62f3b](https://linux-hardware.org/?probe=c4afe62f3b) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [43db111de5](https://linux-hardware.org/?probe=43db111de5) | Nov 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [ba3abf3883](https://linux-hardware.org/?probe=ba3abf3883) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | Notebook    | [ca4bb217ab](https://linux-hardware.org/?probe=ca4bb217ab) | Nov 07, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [29c3e37808](https://linux-hardware.org/?probe=29c3e37808) | Nov 06, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [cb778b5593](https://linux-hardware.org/?probe=cb778b5593) | Nov 06, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2db569e056](https://linux-hardware.org/?probe=2db569e056) | Nov 06, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [f28061e4da](https://linux-hardware.org/?probe=f28061e4da) | Nov 06, 2022 |
| Dell          | G7 7700                     | Notebook    | [ba3a89822a](https://linux-hardware.org/?probe=ba3a89822a) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [2a2464e0a3](https://linux-hardware.org/?probe=2a2464e0a3) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [eded2f5469](https://linux-hardware.org/?probe=eded2f5469) | Nov 06, 2022 |
| Intel         | P61A-D3                     | Desktop     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [1f4a1244b3](https://linux-hardware.org/?probe=1f4a1244b3) | Nov 06, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [ba76e04444](https://linux-hardware.org/?probe=ba76e04444) | Nov 06, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [cd2a716a60](https://linux-hardware.org/?probe=cd2a716a60) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [1cc6297ab8](https://linux-hardware.org/?probe=1cc6297ab8) | Nov 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bad7b9a014](https://linux-hardware.org/?probe=bad7b9a014) | Nov 05, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | Notebook    | [d10e0ce942](https://linux-hardware.org/?probe=d10e0ce942) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [4abe56ea2e](https://linux-hardware.org/?probe=4abe56ea2e) | Nov 05, 2022 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [f4b9627a4a](https://linux-hardware.org/?probe=f4b9627a4a) | Nov 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [b0600fe299](https://linux-hardware.org/?probe=b0600fe299) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [5b939b71c7](https://linux-hardware.org/?probe=5b939b71c7) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [2eb5db395b](https://linux-hardware.org/?probe=2eb5db395b) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518RS8    | Desktop     | [00fc5e3a1b](https://linux-hardware.org/?probe=00fc5e3a1b) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | Notebook    | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [99f51ff157](https://linux-hardware.org/?probe=99f51ff157) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [58989ea140](https://linux-hardware.org/?probe=58989ea140) | Nov 04, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [17157970ee](https://linux-hardware.org/?probe=17157970ee) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [7479ad8a79](https://linux-hardware.org/?probe=7479ad8a79) | Nov 04, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4be0967ca1](https://linux-hardware.org/?probe=4be0967ca1) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | Notebook    | [0622b6fa8f](https://linux-hardware.org/?probe=0622b6fa8f) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | Notebook    | [bec7082d7a](https://linux-hardware.org/?probe=bec7082d7a) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [fa19e49b0a](https://linux-hardware.org/?probe=fa19e49b0a) | Nov 04, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [9fec26118c](https://linux-hardware.org/?probe=9fec26118c) | Nov 04, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [d63435720c](https://linux-hardware.org/?probe=d63435720c) | Nov 04, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [c868e47483](https://linux-hardware.org/?probe=c868e47483) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f391e8dce8](https://linux-hardware.org/?probe=f391e8dce8) | Nov 03, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [a43927efff](https://linux-hardware.org/?probe=a43927efff) | Nov 03, 2022 |
| Dell          | Precision 14 5470           | Notebook    | [dab29b7f5b](https://linux-hardware.org/?probe=dab29b7f5b) | Nov 03, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [2394d00673](https://linux-hardware.org/?probe=2394d00673) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [39e7abb29a](https://linux-hardware.org/?probe=39e7abb29a) | Nov 03, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [42edcc018a](https://linux-hardware.org/?probe=42edcc018a) | Nov 03, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [77f847ca29](https://linux-hardware.org/?probe=77f847ca29) | Nov 02, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [d9de10d93e](https://linux-hardware.org/?probe=d9de10d93e) | Nov 02, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [4191ce8788](https://linux-hardware.org/?probe=4191ce8788) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| Microsoft     | Surface Book                | Tablet      | [e4a7690a77](https://linux-hardware.org/?probe=e4a7690a77) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4e97493141](https://linux-hardware.org/?probe=4e97493141) | Nov 02, 2022 |
| HP            | 212A                        | Desktop     | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | Notebook    | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [d4af3b0745](https://linux-hardware.org/?probe=d4af3b0745) | Nov 01, 2022 |
| Intel Clie... | CMCN1CC                     | Notebook    | [719731b244](https://linux-hardware.org/?probe=719731b244) | Nov 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e08326bc94](https://linux-hardware.org/?probe=e08326bc94) | Nov 01, 2022 |
| Dell          | G5 5587                     | Notebook    | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | Notebook    | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6db184e152](https://linux-hardware.org/?probe=6db184e152) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [60cfb7dcc6](https://linux-hardware.org/?probe=60cfb7dcc6) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [11de150949](https://linux-hardware.org/?probe=11de150949) | Nov 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| ASUSTek       | H97-PRO                     | Desktop     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d284b1709a](https://linux-hardware.org/?probe=d284b1709a) | Oct 31, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [87187c0e23](https://linux-hardware.org/?probe=87187c0e23) | Oct 31, 2022 |
| Sony          | VAIO                        | All in one  | [cefad415d0](https://linux-hardware.org/?probe=cefad415d0) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4c3ae53c16](https://linux-hardware.org/?probe=4c3ae53c16) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | Notebook    | [c6a13e1ab3](https://linux-hardware.org/?probe=c6a13e1ab3) | Oct 31, 2022 |
| Dell          | 02P9X9 A00                  | Server      | [4fa081a282](https://linux-hardware.org/?probe=4fa081a282) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | Precision M6700             | Notebook    | [e5952f6f57](https://linux-hardware.org/?probe=e5952f6f57) | Oct 31, 2022 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [f2893aaedf](https://linux-hardware.org/?probe=f2893aaedf) | Oct 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [56ee27b737](https://linux-hardware.org/?probe=56ee27b737) | Oct 31, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [64d1c159aa](https://linux-hardware.org/?probe=64d1c159aa) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e638ed7bd3](https://linux-hardware.org/?probe=e638ed7bd3) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| HP            | 3048h                       | Desktop     | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [189fca8ab3](https://linux-hardware.org/?probe=189fca8ab3) | Oct 30, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [71f32a229a](https://linux-hardware.org/?probe=71f32a229a) | Oct 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4bc0220a01](https://linux-hardware.org/?probe=4bc0220a01) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bd18c2b33d](https://linux-hardware.org/?probe=bd18c2b33d) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| Apple         | MacBookPro3,1               | Notebook    | [27a5553057](https://linux-hardware.org/?probe=27a5553057) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [8f48ae7586](https://linux-hardware.org/?probe=8f48ae7586) | Oct 29, 2022 |
| MSI           | GE60 0NC\0ND                | Notebook    | [79bd38da8f](https://linux-hardware.org/?probe=79bd38da8f) | Oct 29, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [8f1f41f3b0](https://linux-hardware.org/?probe=8f1f41f3b0) | Oct 29, 2022 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [f8bae249b9](https://linux-hardware.org/?probe=f8bae249b9) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [cc0f34a2fa](https://linux-hardware.org/?probe=cc0f34a2fa) | Oct 29, 2022 |
| Intel         | B75                         | Desktop     | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| MSI           | Prestige 15 A12UC           | Notebook    | [3d4c4364f1](https://linux-hardware.org/?probe=3d4c4364f1) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | Notebook    | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9dcb685f5e](https://linux-hardware.org/?probe=9dcb685f5e) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [df9ef8c115](https://linux-hardware.org/?probe=df9ef8c115) | Oct 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c9cd061f05](https://linux-hardware.org/?probe=c9cd061f05) | Oct 28, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [2fdc53f0f3](https://linux-hardware.org/?probe=2fdc53f0f3) | Oct 28, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [04d54cb9c8](https://linux-hardware.org/?probe=04d54cb9c8) | Oct 28, 2022 |
| Dell          | Precision 5530              | Notebook    | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [d04e962e56](https://linux-hardware.org/?probe=d04e962e56) | Oct 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0957761dea](https://linux-hardware.org/?probe=0957761dea) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | Notebook    | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | Desktop     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b82aebb005](https://linux-hardware.org/?probe=b82aebb005) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [f27c4e1041](https://linux-hardware.org/?probe=f27c4e1041) | Oct 27, 2022 |
| System76      | Oryx Pro                    | Notebook    | [ff42b6e74a](https://linux-hardware.org/?probe=ff42b6e74a) | Oct 27, 2022 |
| Novatech      | NLx0MU                      | Notebook    | [41c5d984a0](https://linux-hardware.org/?probe=41c5d984a0) | Oct 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [e7db99be75](https://linux-hardware.org/?probe=e7db99be75) | Oct 27, 2022 |
| MSI           | B85-G43                     | Desktop     | [48ac016cd9](https://linux-hardware.org/?probe=48ac016cd9) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [9f7121381b](https://linux-hardware.org/?probe=9f7121381b) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [022cfe6707](https://linux-hardware.org/?probe=022cfe6707) | Oct 26, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [cb657f604d](https://linux-hardware.org/?probe=cb657f604d) | Oct 26, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [81371581d1](https://linux-hardware.org/?probe=81371581d1) | Oct 26, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [1ede815931](https://linux-hardware.org/?probe=1ede815931) | Oct 26, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9deeea3723](https://linux-hardware.org/?probe=9deeea3723) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [58af9b9a77](https://linux-hardware.org/?probe=58af9b9a77) | Oct 26, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [2b6b8d3854](https://linux-hardware.org/?probe=2b6b8d3854) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | Notebook    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | Notebook    | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [3375318388](https://linux-hardware.org/?probe=3375318388) | Oct 25, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [7f9028d036](https://linux-hardware.org/?probe=7f9028d036) | Oct 25, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a26efdcfb5](https://linux-hardware.org/?probe=a26efdcfb5) | Oct 25, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| HP            | ZBook 15                    | Notebook    | [b2d2352668](https://linux-hardware.org/?probe=b2d2352668) | Oct 25, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [b31fec75e1](https://linux-hardware.org/?probe=b31fec75e1) | Oct 25, 2022 |
| Dell          | G15 5511                    | Notebook    | [0f47c64bab](https://linux-hardware.org/?probe=0f47c64bab) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [3cd266dbbb](https://linux-hardware.org/?probe=3cd266dbbb) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [d03f6896eb](https://linux-hardware.org/?probe=d03f6896eb) | Oct 25, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6966cfc71f](https://linux-hardware.org/?probe=6966cfc71f) | Oct 25, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [7c4edd1a6d](https://linux-hardware.org/?probe=7c4edd1a6d) | Oct 24, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [d76c41ef1b](https://linux-hardware.org/?probe=d76c41ef1b) | Oct 24, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [47a3e2b5f6](https://linux-hardware.org/?probe=47a3e2b5f6) | Oct 24, 2022 |
| Lenovo        | ThinkPad L380 Yoga 20M7C... | Convertible | [c9577d0d5a](https://linux-hardware.org/?probe=c9577d0d5a) | Oct 24, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [2510215a0b](https://linux-hardware.org/?probe=2510215a0b) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [c271de3628](https://linux-hardware.org/?probe=c271de3628) | Oct 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3749438ef1](https://linux-hardware.org/?probe=3749438ef1) | Oct 24, 2022 |
| MSI           | 970A-G46                    | Desktop     | [38541ac772](https://linux-hardware.org/?probe=38541ac772) | Oct 24, 2022 |
| System76      | Gazelle                     | Notebook    | [77686d0854](https://linux-hardware.org/?probe=77686d0854) | Oct 24, 2022 |
| HP            | Laptop 15s-gy0xxx           | Notebook    | [d1219c1387](https://linux-hardware.org/?probe=d1219c1387) | Oct 23, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [c70d6b90b6](https://linux-hardware.org/?probe=c70d6b90b6) | Oct 23, 2022 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [7435d326b7](https://linux-hardware.org/?probe=7435d326b7) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [bd25fa1073](https://linux-hardware.org/?probe=bd25fa1073) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [9380dfc8b7](https://linux-hardware.org/?probe=9380dfc8b7) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5d14f79724](https://linux-hardware.org/?probe=5d14f79724) | Oct 23, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [4884be1a24](https://linux-hardware.org/?probe=4884be1a24) | Oct 22, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c0867dfce4](https://linux-hardware.org/?probe=c0867dfce4) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6199e2daaa](https://linux-hardware.org/?probe=6199e2daaa) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [dc48a995c4](https://linux-hardware.org/?probe=dc48a995c4) | Oct 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [32a9b1de4f](https://linux-hardware.org/?probe=32a9b1de4f) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [079a05485d](https://linux-hardware.org/?probe=079a05485d) | Oct 22, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7de5d55c99](https://linux-hardware.org/?probe=7de5d55c99) | Oct 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [32cd9cd246](https://linux-hardware.org/?probe=32cd9cd246) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| Intel         | Montevina CRB               | Notebook    | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [15c764f6fa](https://linux-hardware.org/?probe=15c764f6fa) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [fb86c213ca](https://linux-hardware.org/?probe=fb86c213ca) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [27cae45787](https://linux-hardware.org/?probe=27cae45787) | Oct 20, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [504036a2f6](https://linux-hardware.org/?probe=504036a2f6) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| System76      | Lemur Pro                   | Notebook    | [df61411c9d](https://linux-hardware.org/?probe=df61411c9d) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | Desktop     | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | Desktop     | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [8a872b5819](https://linux-hardware.org/?probe=8a872b5819) | Oct 19, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [b4afec070e](https://linux-hardware.org/?probe=b4afec070e) | Oct 19, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [d565cdf4a5](https://linux-hardware.org/?probe=d565cdf4a5) | Oct 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c14937070e](https://linux-hardware.org/?probe=c14937070e) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [ca39605260](https://linux-hardware.org/?probe=ca39605260) | Oct 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [08327d561d](https://linux-hardware.org/?probe=08327d561d) | Oct 18, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [2a51555c53](https://linux-hardware.org/?probe=2a51555c53) | Oct 18, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [c84509fb21](https://linux-hardware.org/?probe=c84509fb21) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [e3ce426450](https://linux-hardware.org/?probe=e3ce426450) | Oct 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [ed64a103f1](https://linux-hardware.org/?probe=ed64a103f1) | Oct 18, 2022 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [2d1482e433](https://linux-hardware.org/?probe=2d1482e433) | Oct 18, 2022 |
| HP            | 339A                        | Desktop     | [e168e3b75b](https://linux-hardware.org/?probe=e168e3b75b) | Oct 18, 2022 |
| System76      | Lemur Pro                   | Notebook    | [53226822f5](https://linux-hardware.org/?probe=53226822f5) | Oct 18, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [d522208941](https://linux-hardware.org/?probe=d522208941) | Oct 17, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| Lenovo        | Legion Y740-17IRH 81UG      | Notebook    | [67aec6ad33](https://linux-hardware.org/?probe=67aec6ad33) | Oct 17, 2022 |
| MSI           | GP72VR 7RF                  | Notebook    | [86a4902866](https://linux-hardware.org/?probe=86a4902866) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [e8e5ae4784](https://linux-hardware.org/?probe=e8e5ae4784) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [ca202dddd6](https://linux-hardware.org/?probe=ca202dddd6) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [0a30a79788](https://linux-hardware.org/?probe=0a30a79788) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [a4f5a5b0be](https://linux-hardware.org/?probe=a4f5a5b0be) | Oct 17, 2022 |
| HP            | G62                         | Notebook    | [839b09744e](https://linux-hardware.org/?probe=839b09744e) | Oct 17, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [e2991c4619](https://linux-hardware.org/?probe=e2991c4619) | Oct 17, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0ec570b33c](https://linux-hardware.org/?probe=0ec570b33c) | Oct 16, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [bf7cebc10e](https://linux-hardware.org/?probe=bf7cebc10e) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0e0a3b9cf0](https://linux-hardware.org/?probe=0e0a3b9cf0) | Oct 16, 2022 |
| HP            | ENVY 17                     | Notebook    | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [502f19e8b3](https://linux-hardware.org/?probe=502f19e8b3) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | Desktop     | [d91f9fb542](https://linux-hardware.org/?probe=d91f9fb542) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [daaa9d8dcc](https://linux-hardware.org/?probe=daaa9d8dcc) | Oct 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b7ebef4e11](https://linux-hardware.org/?probe=b7ebef4e11) | Oct 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [beb41f73d2](https://linux-hardware.org/?probe=beb41f73d2) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M90 5536A76     | Desktop     | [d6f13cdb14](https://linux-hardware.org/?probe=d6f13cdb14) | Oct 15, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| HP            | Pavilion g6                 | Notebook    | [2729d4b101](https://linux-hardware.org/?probe=2729d4b101) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [2ba7e8c424](https://linux-hardware.org/?probe=2ba7e8c424) | Oct 14, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [6b78ca11b4](https://linux-hardware.org/?probe=6b78ca11b4) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [128cccafa6](https://linux-hardware.org/?probe=128cccafa6) | Oct 14, 2022 |
| HP            | Pavilion g6                 | Notebook    | [4fbce46637](https://linux-hardware.org/?probe=4fbce46637) | Oct 14, 2022 |
| System76      | Galago Pro                  | Notebook    | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [e2db064195](https://linux-hardware.org/?probe=e2db064195) | Oct 13, 2022 |
| Google        | Kefka                       | Notebook    | [4775b995dd](https://linux-hardware.org/?probe=4775b995dd) | Oct 13, 2022 |
| System76      | Lemur Pro                   | Notebook    | [ec569ddc8f](https://linux-hardware.org/?probe=ec569ddc8f) | Oct 13, 2022 |
| Dell          | Latitude 7420               | Convertible | [dade6a2b21](https://linux-hardware.org/?probe=dade6a2b21) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [3c11d61a58](https://linux-hardware.org/?probe=3c11d61a58) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [236e24530f](https://linux-hardware.org/?probe=236e24530f) | Oct 12, 2022 |
| Dell          | Precision M6700             | Notebook    | [4c867e9075](https://linux-hardware.org/?probe=4c867e9075) | Oct 12, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [86c8fabb2d](https://linux-hardware.org/?probe=86c8fabb2d) | Oct 12, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [273721cef2](https://linux-hardware.org/?probe=273721cef2) | Oct 12, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [c82722f056](https://linux-hardware.org/?probe=c82722f056) | Oct 12, 2022 |
| Razer         | Blade                       | Notebook    | [c7386df23f](https://linux-hardware.org/?probe=c7386df23f) | Oct 12, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [2d102e0f1e](https://linux-hardware.org/?probe=2d102e0f1e) | Oct 12, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| HP            | Pavilion 15                 | Notebook    | [8b93ec27f4](https://linux-hardware.org/?probe=8b93ec27f4) | Oct 12, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [1feb5d7501](https://linux-hardware.org/?probe=1feb5d7501) | Oct 12, 2022 |
| Alienware     | 15 R3                       | Notebook    | [bfdbf12cbb](https://linux-hardware.org/?probe=bfdbf12cbb) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [93ca81946a](https://linux-hardware.org/?probe=93ca81946a) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [921c4a26d1](https://linux-hardware.org/?probe=921c4a26d1) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [1b31cf42bb](https://linux-hardware.org/?probe=1b31cf42bb) | Oct 11, 2022 |
| MSI           | MS-7A34                     | Notebook    | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [f4a46537c2](https://linux-hardware.org/?probe=f4a46537c2) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | Notebook    | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [a6eb228e33](https://linux-hardware.org/?probe=a6eb228e33) | Oct 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3462676a1d](https://linux-hardware.org/?probe=3462676a1d) | Oct 10, 2022 |
| Dell          | 0GM819                      | Desktop     | [e0266a8468](https://linux-hardware.org/?probe=e0266a8468) | Oct 09, 2022 |
| Dell          | Latitude 5501               | Notebook    | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | Notebook    | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [7231761ea1](https://linux-hardware.org/?probe=7231761ea1) | Oct 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e26fca4929](https://linux-hardware.org/?probe=e26fca4929) | Oct 09, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [8902a355f4](https://linux-hardware.org/?probe=8902a355f4) | Oct 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [1f013f181d](https://linux-hardware.org/?probe=1f013f181d) | Oct 09, 2022 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [4f74ee653c](https://linux-hardware.org/?probe=4f74ee653c) | Oct 09, 2022 |
| Dell          | 0J3C2F A01                  | Desktop     | [d1001275c6](https://linux-hardware.org/?probe=d1001275c6) | Oct 09, 2022 |
| Sony          | VPCEB46FG                   | Notebook    | [71e2273974](https://linux-hardware.org/?probe=71e2273974) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | Desktop     | [324f177fa7](https://linux-hardware.org/?probe=324f177fa7) | Oct 08, 2022 |
| HP            | ProBook 640 G3              | Notebook    | [03112f2830](https://linux-hardware.org/?probe=03112f2830) | Oct 08, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [d6742b3ec0](https://linux-hardware.org/?probe=d6742b3ec0) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | Notebook    | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| Lenovo        | V155-15API 81V5             | Notebook    | [c08e4bed15](https://linux-hardware.org/?probe=c08e4bed15) | Oct 07, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [8ad48ccaec](https://linux-hardware.org/?probe=8ad48ccaec) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9525ea0de3](https://linux-hardware.org/?probe=9525ea0de3) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Sony          | VPCEH3LFX                   | Notebook    | [fbb59e09fc](https://linux-hardware.org/?probe=fbb59e09fc) | Oct 07, 2022 |
| Alienware     | 17 R4                       | Notebook    | [cac06d6050](https://linux-hardware.org/?probe=cac06d6050) | Oct 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [f26e597436](https://linux-hardware.org/?probe=f26e597436) | Oct 06, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [83a49e76b9](https://linux-hardware.org/?probe=83a49e76b9) | Oct 06, 2022 |
| MSI           | GP66 Leopard 10UG           | Notebook    | [c2082a042d](https://linux-hardware.org/?probe=c2082a042d) | Oct 06, 2022 |
| ASRock        | B450M/ac                    | Desktop     | [af66fef71a](https://linux-hardware.org/?probe=af66fef71a) | Oct 06, 2022 |
| HP            | 3398                        | Desktop     | [c70e10b68b](https://linux-hardware.org/?probe=c70e10b68b) | Oct 06, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [05e6a5cb26](https://linux-hardware.org/?probe=05e6a5cb26) | Oct 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [512c095e83](https://linux-hardware.org/?probe=512c095e83) | Oct 06, 2022 |
| Lenovo        | IdeaPad Y560                | Notebook    | [15e2c8994f](https://linux-hardware.org/?probe=15e2c8994f) | Oct 06, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d4a282a4b8](https://linux-hardware.org/?probe=d4a282a4b8) | Oct 06, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [9232451f1a](https://linux-hardware.org/?probe=9232451f1a) | Oct 06, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [5f5a6947ab](https://linux-hardware.org/?probe=5f5a6947ab) | Oct 06, 2022 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [fa7e7d106e](https://linux-hardware.org/?probe=fa7e7d106e) | Oct 06, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [ed969ece24](https://linux-hardware.org/?probe=ed969ece24) | Oct 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [2fda8270f0](https://linux-hardware.org/?probe=2fda8270f0) | Oct 05, 2022 |
| HP            | 3398                        | Desktop     | [7dd62dded1](https://linux-hardware.org/?probe=7dd62dded1) | Oct 05, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [c0f42e7ac4](https://linux-hardware.org/?probe=c0f42e7ac4) | Oct 05, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [8e7d366723](https://linux-hardware.org/?probe=8e7d366723) | Oct 05, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [48901aff3f](https://linux-hardware.org/?probe=48901aff3f) | Oct 04, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [736ded7422](https://linux-hardware.org/?probe=736ded7422) | Oct 04, 2022 |
| Intel         | DQ35JO AAD82085-801         | Desktop     | [4056c37c50](https://linux-hardware.org/?probe=4056c37c50) | Oct 04, 2022 |
| Dell          | Latitude E7240              | Notebook    | [0a41ea4b4c](https://linux-hardware.org/?probe=0a41ea4b4c) | Oct 04, 2022 |
| HP            | EliteBook 1040 G4           | Notebook    | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| Microsoft     | Surface Book                | Tablet      | [85c4f341f3](https://linux-hardware.org/?probe=85c4f341f3) | Oct 04, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [b8237b1bd7](https://linux-hardware.org/?probe=b8237b1bd7) | Oct 04, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [eb1ee8ad1f](https://linux-hardware.org/?probe=eb1ee8ad1f) | Oct 04, 2022 |
| System76      | Lemur Pro                   | Notebook    | [8842585a92](https://linux-hardware.org/?probe=8842585a92) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [652b18aabe](https://linux-hardware.org/?probe=652b18aabe) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| Google        | Banon                       | Notebook    | [269a819905](https://linux-hardware.org/?probe=269a819905) | Oct 03, 2022 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [2637a452d0](https://linux-hardware.org/?probe=2637a452d0) | Oct 03, 2022 |
| Samsung       | 550XDA                      | Notebook    | [418d32112e](https://linux-hardware.org/?probe=418d32112e) | Oct 03, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [b3a9474c83](https://linux-hardware.org/?probe=b3a9474c83) | Oct 03, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [7fbccd3f20](https://linux-hardware.org/?probe=7fbccd3f20) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0382d1ec36](https://linux-hardware.org/?probe=0382d1ec36) | Oct 02, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Dell          | XPS L421X                   | Notebook    | [aedcc42b0a](https://linux-hardware.org/?probe=aedcc42b0a) | Oct 02, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [b0a6dc4162](https://linux-hardware.org/?probe=b0a6dc4162) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| Alienware     | 15 R3                       | Notebook    | [28e4e84fb1](https://linux-hardware.org/?probe=28e4e84fb1) | Oct 02, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [54c3aa5cc5](https://linux-hardware.org/?probe=54c3aa5cc5) | Oct 02, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Notebook    | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| ASUSTek       | GL502VM                     | Notebook    | [1d1616405d](https://linux-hardware.org/?probe=1d1616405d) | Oct 02, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [ae706e478d](https://linux-hardware.org/?probe=ae706e478d) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [32dba0444e](https://linux-hardware.org/?probe=32dba0444e) | Oct 02, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [49595ef8f4](https://linux-hardware.org/?probe=49595ef8f4) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46d6046fce](https://linux-hardware.org/?probe=46d6046fce) | Oct 02, 2022 |
| Micro Elec... | Element                     | Notebook    | [9cee0f76c1](https://linux-hardware.org/?probe=9cee0f76c1) | Oct 02, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [42113dd7e3](https://linux-hardware.org/?probe=42113dd7e3) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FE00... | Convertible | [4eaeb1d5ad](https://linux-hardware.org/?probe=4eaeb1d5ad) | Oct 01, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4168f641b5](https://linux-hardware.org/?probe=4168f641b5) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [b2d146f923](https://linux-hardware.org/?probe=b2d146f923) | Oct 01, 2022 |
| HP            | Pavilion                    | Notebook    | [124e8b760a](https://linux-hardware.org/?probe=124e8b760a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| System76      | Darter Pro                  | Notebook    | [2829e72506](https://linux-hardware.org/?probe=2829e72506) | Oct 01, 2022 |
| System76      | Darter Pro                  | Notebook    | [c142cf370a](https://linux-hardware.org/?probe=c142cf370a) | Oct 01, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [692b59019a](https://linux-hardware.org/?probe=692b59019a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [6f6704ea90](https://linux-hardware.org/?probe=6f6704ea90) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [5e9a9b60e6](https://linux-hardware.org/?probe=5e9a9b60e6) | Oct 01, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | Notebook    | [bde2b36c88](https://linux-hardware.org/?probe=bde2b36c88) | Oct 01, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [2e9261e2a7](https://linux-hardware.org/?probe=2e9261e2a7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T480 20L5001FUS    | Notebook    | [a7e0da7aa4](https://linux-hardware.org/?probe=a7e0da7aa4) | Sep 30, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [8856e3bf98](https://linux-hardware.org/?probe=8856e3bf98) | Sep 30, 2022 |
| Dell          | Latitude 5400               | Notebook    | [66a5bc26f0](https://linux-hardware.org/?probe=66a5bc26f0) | Sep 30, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [3f01bbaa12](https://linux-hardware.org/?probe=3f01bbaa12) | Sep 30, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | Notebook    | [81653ba834](https://linux-hardware.org/?probe=81653ba834) | Sep 30, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [1669dae0a6](https://linux-hardware.org/?probe=1669dae0a6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | Notebook    | [d31b97630d](https://linux-hardware.org/?probe=d31b97630d) | Sep 29, 2022 |
| Dell          | Latitude 5400               | Notebook    | [4536a4b473](https://linux-hardware.org/?probe=4536a4b473) | Sep 29, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [7a2f334861](https://linux-hardware.org/?probe=7a2f334861) | Sep 29, 2022 |
| Dell          | Latitude 5400               | Notebook    | [972e4ab3fa](https://linux-hardware.org/?probe=972e4ab3fa) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| Dell          | Inspiron 7405 2n1           | Convertible | [8196b8f736](https://linux-hardware.org/?probe=8196b8f736) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [f758c22d98](https://linux-hardware.org/?probe=f758c22d98) | Sep 28, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | Notebook    | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [b08fc47990](https://linux-hardware.org/?probe=b08fc47990) | Sep 28, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [46cba6613f](https://linux-hardware.org/?probe=46cba6613f) | Sep 28, 2022 |
| Dell          | 0NDYHG A01                  | Desktop     | [7a5df20f28](https://linux-hardware.org/?probe=7a5df20f28) | Sep 28, 2022 |
| Dell          | Latitude E7450              | Notebook    | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [5ce350f38b](https://linux-hardware.org/?probe=5ce350f38b) | Sep 28, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [f129c4da4a](https://linux-hardware.org/?probe=f129c4da4a) | Sep 28, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [a3c4032d28](https://linux-hardware.org/?probe=a3c4032d28) | Sep 27, 2022 |
| HP            | 83E9                        | Desktop     | [c24faa3c5b](https://linux-hardware.org/?probe=c24faa3c5b) | Sep 27, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [99b6a53bd2](https://linux-hardware.org/?probe=99b6a53bd2) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| ASUSTek       | GL702VSK                    | Notebook    | [3b69ddb263](https://linux-hardware.org/?probe=3b69ddb263) | Sep 27, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [8579eba471](https://linux-hardware.org/?probe=8579eba471) | Sep 26, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [fbc760a09c](https://linux-hardware.org/?probe=fbc760a09c) | Sep 26, 2022 |
| ASUSTek       | GL702VSK                    | Notebook    | [e91056ceab](https://linux-hardware.org/?probe=e91056ceab) | Sep 26, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [eff6424aa4](https://linux-hardware.org/?probe=eff6424aa4) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| System76      | Galago Pro                  | Notebook    | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [1b4db0c30c](https://linux-hardware.org/?probe=1b4db0c30c) | Sep 26, 2022 |
| ASUSTek       | K52N                        | Notebook    | [8d7b00011f](https://linux-hardware.org/?probe=8d7b00011f) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [e9de38d8eb](https://linux-hardware.org/?probe=e9de38d8eb) | Sep 25, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [05dc7a54c7](https://linux-hardware.org/?probe=05dc7a54c7) | Sep 25, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [5c39bdf4ab](https://linux-hardware.org/?probe=5c39bdf4ab) | Sep 24, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [029c059963](https://linux-hardware.org/?probe=029c059963) | Sep 24, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d2327ba5d4](https://linux-hardware.org/?probe=d2327ba5d4) | Sep 24, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b3f2c4694c](https://linux-hardware.org/?probe=b3f2c4694c) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [61dd74082f](https://linux-hardware.org/?probe=61dd74082f) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d07b0cb7a0](https://linux-hardware.org/?probe=d07b0cb7a0) | Sep 24, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [2bc6e102ef](https://linux-hardware.org/?probe=2bc6e102ef) | Sep 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [fac56b0962](https://linux-hardware.org/?probe=fac56b0962) | Sep 24, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [214a55ad3e](https://linux-hardware.org/?probe=214a55ad3e) | Sep 24, 2022 |
| MSI           | Z97-G55 SLI                 | Desktop     | [dc60d66502](https://linux-hardware.org/?probe=dc60d66502) | Sep 24, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [86b6d46191](https://linux-hardware.org/?probe=86b6d46191) | Sep 24, 2022 |
| System76      | Thelio Mira                 | Desktop     | [2e9601d2a2](https://linux-hardware.org/?probe=2e9601d2a2) | Sep 24, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [9e8207dfb7](https://linux-hardware.org/?probe=9e8207dfb7) | Sep 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [59c4a7e761](https://linux-hardware.org/?probe=59c4a7e761) | Sep 23, 2022 |
| MSI           | Z97-G55 SLI                 | Desktop     | [27b47d5592](https://linux-hardware.org/?probe=27b47d5592) | Sep 23, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [609225524a](https://linux-hardware.org/?probe=609225524a) | Sep 23, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [cda6d76f04](https://linux-hardware.org/?probe=cda6d76f04) | Sep 22, 2022 |
| Dell          | Latitude 7275               | Tablet      | [3ce0ab7672](https://linux-hardware.org/?probe=3ce0ab7672) | Sep 22, 2022 |
| System76      | Darter Pro                  | Notebook    | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| ASRock        | 4X4-V1000                   | Desktop     | [e73062fe01](https://linux-hardware.org/?probe=e73062fe01) | Sep 22, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [074a9f8433](https://linux-hardware.org/?probe=074a9f8433) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| System76      | Darter Pro                  | Notebook    | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [032bbec1e3](https://linux-hardware.org/?probe=032bbec1e3) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [3c93753c6c](https://linux-hardware.org/?probe=3c93753c6c) | Sep 22, 2022 |
| Dell          | Latitude 3490               | Notebook    | [de749eeeb8](https://linux-hardware.org/?probe=de749eeeb8) | Sep 21, 2022 |
| Dell          | Precision 3561              | Notebook    | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Nitro AN715-51              | Notebook    | [36fb85e6cb](https://linux-hardware.org/?probe=36fb85e6cb) | Sep 21, 2022 |
| HP            | 829A                        | Mini pc     | [9fbbfa249d](https://linux-hardware.org/?probe=9fbbfa249d) | Sep 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [facc4c1755](https://linux-hardware.org/?probe=facc4c1755) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [07dd388834](https://linux-hardware.org/?probe=07dd388834) | Sep 21, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [8116705a81](https://linux-hardware.org/?probe=8116705a81) | Sep 21, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [7fa417e9a6](https://linux-hardware.org/?probe=7fa417e9a6) | Sep 21, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7fc6799a48](https://linux-hardware.org/?probe=7fc6799a48) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2c7466119d](https://linux-hardware.org/?probe=2c7466119d) | Sep 21, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [c6f4124e49](https://linux-hardware.org/?probe=c6f4124e49) | Sep 21, 2022 |
| HP            | 1589                        | Desktop     | [da376a40a1](https://linux-hardware.org/?probe=da376a40a1) | Sep 20, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| Itronix       | GD8200                      | Notebook    | [d9f515b935](https://linux-hardware.org/?probe=d9f515b935) | Sep 20, 2022 |
| Lenovo        | Legion 5-15ACH6H 82JU       | Notebook    | [1f48647e32](https://linux-hardware.org/?probe=1f48647e32) | Sep 20, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [61a4ab7c20](https://linux-hardware.org/?probe=61a4ab7c20) | Sep 20, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [6d43012457](https://linux-hardware.org/?probe=6d43012457) | Sep 20, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [df0348739e](https://linux-hardware.org/?probe=df0348739e) | Sep 20, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [dd2687098a](https://linux-hardware.org/?probe=dd2687098a) | Sep 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a0d6f208fb](https://linux-hardware.org/?probe=a0d6f208fb) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | Notebook    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| Sony          | VAIO                        | All in one  | [0e3271f88f](https://linux-hardware.org/?probe=0e3271f88f) | Sep 19, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [060f3bd895](https://linux-hardware.org/?probe=060f3bd895) | Sep 19, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| Dell          | Latitude 9420               | Convertible | [1c6c42624d](https://linux-hardware.org/?probe=1c6c42624d) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| HP            | OMEN by Laptop 15z-en100    | Notebook    | [47b0aed151](https://linux-hardware.org/?probe=47b0aed151) | Sep 19, 2022 |
| Framework     | Laptop                      | Notebook    | [8dbbe54af9](https://linux-hardware.org/?probe=8dbbe54af9) | Sep 18, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [83b0a59729](https://linux-hardware.org/?probe=83b0a59729) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [37b4da9922](https://linux-hardware.org/?probe=37b4da9922) | Sep 18, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [31e3939680](https://linux-hardware.org/?probe=31e3939680) | Sep 18, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [f207769c14](https://linux-hardware.org/?probe=f207769c14) | Sep 18, 2022 |
| Gateway       | NV55C                       | Notebook    | [e00587af22](https://linux-hardware.org/?probe=e00587af22) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [fa4082533e](https://linux-hardware.org/?probe=fa4082533e) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [a418c3e997](https://linux-hardware.org/?probe=a418c3e997) | Sep 18, 2022 |
| Dell          | Latitude E7470              | Notebook    | [ceed7544ab](https://linux-hardware.org/?probe=ceed7544ab) | Sep 18, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [f40cc0db8a](https://linux-hardware.org/?probe=f40cc0db8a) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Dell          | Precision 5530              | Notebook    | [8fc00af945](https://linux-hardware.org/?probe=8fc00af945) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50da0a8acf](https://linux-hardware.org/?probe=50da0a8acf) | Sep 18, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [e749154c3d](https://linux-hardware.org/?probe=e749154c3d) | Sep 18, 2022 |
| Dell          | Latitude E6330              | Notebook    | [5a1085f939](https://linux-hardware.org/?probe=5a1085f939) | Sep 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bd7ddbf9f7](https://linux-hardware.org/?probe=bd7ddbf9f7) | Sep 18, 2022 |
| Alienware     | 0CPDXD A00                  | Desktop     | [f65bdb053d](https://linux-hardware.org/?probe=f65bdb053d) | Sep 18, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| MSI           | Prestige 15 A12UC           | Notebook    | [48437ccf94](https://linux-hardware.org/?probe=48437ccf94) | Sep 17, 2022 |
| OriginPC      | NT17-PRO                    | Notebook    | [962138caa9](https://linux-hardware.org/?probe=962138caa9) | Sep 17, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [4c919169ea](https://linux-hardware.org/?probe=4c919169ea) | Sep 17, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [0bec316a0b](https://linux-hardware.org/?probe=0bec316a0b) | Sep 17, 2022 |
| System76      | Darter Pro                  | Notebook    | [5d1e0ddc1a](https://linux-hardware.org/?probe=5d1e0ddc1a) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [d66cbae64b](https://linux-hardware.org/?probe=d66cbae64b) | Sep 16, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [545552c43e](https://linux-hardware.org/?probe=545552c43e) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [b0e6601fbf](https://linux-hardware.org/?probe=b0e6601fbf) | Sep 16, 2022 |
| ASUSTek       | N550LF                      | Notebook    | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [9cc24963d4](https://linux-hardware.org/?probe=9cc24963d4) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [6d28bb81ce](https://linux-hardware.org/?probe=6d28bb81ce) | Sep 16, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [9c45d5a042](https://linux-hardware.org/?probe=9c45d5a042) | Sep 16, 2022 |
| NZXT          | N7 B550                     | Desktop     | [7deb3849db](https://linux-hardware.org/?probe=7deb3849db) | Sep 16, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [2c90f58ae4](https://linux-hardware.org/?probe=2c90f58ae4) | Sep 16, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [6d94f648e4](https://linux-hardware.org/?probe=6d94f648e4) | Sep 16, 2022 |
| GPD           | MicroPC                     | Notebook    | [dadac68a23](https://linux-hardware.org/?probe=dadac68a23) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3196144640](https://linux-hardware.org/?probe=3196144640) | Sep 15, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| MACHINIST     | X99-RS9 V3.0                | Desktop     | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| Dell          | Precision 3561              | Notebook    | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [2d33f80fbd](https://linux-hardware.org/?probe=2d33f80fbd) | Sep 15, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5c00a1875c](https://linux-hardware.org/?probe=5c00a1875c) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [750bf03293](https://linux-hardware.org/?probe=750bf03293) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | Notebook    | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [64b85307ec](https://linux-hardware.org/?probe=64b85307ec) | Sep 14, 2022 |
| ASUSTek       | X405UA                      | Notebook    | [3b098addea](https://linux-hardware.org/?probe=3b098addea) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | Notebook    | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| MACHINIST     | X99-RS9 V3.0                | Desktop     | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [a27c60fbde](https://linux-hardware.org/?probe=a27c60fbde) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [81b9b18da4](https://linux-hardware.org/?probe=81b9b18da4) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cacc85ca2e](https://linux-hardware.org/?probe=cacc85ca2e) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0c6d5b57dd](https://linux-hardware.org/?probe=0c6d5b57dd) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [b502b7938d](https://linux-hardware.org/?probe=b502b7938d) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [89fb49d843](https://linux-hardware.org/?probe=89fb49d843) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [a385e1220b](https://linux-hardware.org/?probe=a385e1220b) | Sep 13, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [2548dada71](https://linux-hardware.org/?probe=2548dada71) | Sep 13, 2022 |
| Dell          | Studio 1555                 | Notebook    | [0d0f3de3b4](https://linux-hardware.org/?probe=0d0f3de3b4) | Sep 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [8bdaf4361b](https://linux-hardware.org/?probe=8bdaf4361b) | Sep 12, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4fbc7a765f](https://linux-hardware.org/?probe=4fbc7a765f) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e1d128b56a](https://linux-hardware.org/?probe=e1d128b56a) | Sep 12, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Notebook    | [1889334e1f](https://linux-hardware.org/?probe=1889334e1f) | Sep 12, 2022 |
| ECS           | Nettle3                     | Desktop     | [23f7f8708c](https://linux-hardware.org/?probe=23f7f8708c) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [f9add8f93d](https://linux-hardware.org/?probe=f9add8f93d) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [2f6745bad5](https://linux-hardware.org/?probe=2f6745bad5) | Sep 11, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [34964d8e2d](https://linux-hardware.org/?probe=34964d8e2d) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ce4fc6576c](https://linux-hardware.org/?probe=ce4fc6576c) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | Notebook    | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c0adc468b3](https://linux-hardware.org/?probe=c0adc468b3) | Sep 10, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [5ae1f0d923](https://linux-hardware.org/?probe=5ae1f0d923) | Sep 10, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| Dell          | 0P4T42 A01                  | All in one  | [21db941a5b](https://linux-hardware.org/?probe=21db941a5b) | Sep 10, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [bb72f0c2f4](https://linux-hardware.org/?probe=bb72f0c2f4) | Sep 10, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2e9e331465](https://linux-hardware.org/?probe=2e9e331465) | Sep 10, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [29da7835e4](https://linux-hardware.org/?probe=29da7835e4) | Sep 10, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5811e17863](https://linux-hardware.org/?probe=5811e17863) | Sep 09, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4d3543d03f](https://linux-hardware.org/?probe=4d3543d03f) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b3aa7bd9ca](https://linux-hardware.org/?probe=b3aa7bd9ca) | Sep 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [87f754ac29](https://linux-hardware.org/?probe=87f754ac29) | Sep 09, 2022 |
| System76      | Galago Pro                  | Notebook    | [8d52d900f2](https://linux-hardware.org/?probe=8d52d900f2) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [1be1b9b040](https://linux-hardware.org/?probe=1be1b9b040) | Sep 09, 2022 |
| HP            | ZBook Studio x360 G5        | Convertible | [5fe757d559](https://linux-hardware.org/?probe=5fe757d559) | Sep 09, 2022 |
| Intel         | X99                         | Desktop     | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | Desktop     | [dbfdcae895](https://linux-hardware.org/?probe=dbfdcae895) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | Desktop     | [4167167e38](https://linux-hardware.org/?probe=4167167e38) | Sep 08, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| Dell          | Inspiron 5457               | Notebook    | [e44e9d3a85](https://linux-hardware.org/?probe=e44e9d3a85) | Sep 08, 2022 |
| AZW           | SEi                         | Notebook    | [d3531738fa](https://linux-hardware.org/?probe=d3531738fa) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | Notebook    | [6108c677a2](https://linux-hardware.org/?probe=6108c677a2) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | Notebook    | [0f8da1f0c8](https://linux-hardware.org/?probe=0f8da1f0c8) | Sep 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [bb2d82813c](https://linux-hardware.org/?probe=bb2d82813c) | Sep 08, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [e757b79169](https://linux-hardware.org/?probe=e757b79169) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [09e8283762](https://linux-hardware.org/?probe=09e8283762) | Sep 08, 2022 |
| HP            | 245 G6                      | Notebook    | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| ASRock        | B450M/ac                    | Desktop     | [efb78c5d25](https://linux-hardware.org/?probe=efb78c5d25) | Sep 07, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [e73c83b5c7](https://linux-hardware.org/?probe=e73c83b5c7) | Sep 07, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [483a414289](https://linux-hardware.org/?probe=483a414289) | Sep 07, 2022 |
| Acer          | Aspire S3                   | Notebook    | [cb62300974](https://linux-hardware.org/?probe=cb62300974) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0efcfb2037](https://linux-hardware.org/?probe=0efcfb2037) | Sep 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGA039U... | Notebook    | [43c002ad40](https://linux-hardware.org/?probe=43c002ad40) | Sep 07, 2022 |
| Acer          | 1.0                         | Desktop     | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [47d065ed5c](https://linux-hardware.org/?probe=47d065ed5c) | Sep 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480s 20L8SC160... | Notebook    | [b860019cf4](https://linux-hardware.org/?probe=b860019cf4) | Sep 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [40d6a47565](https://linux-hardware.org/?probe=40d6a47565) | Sep 05, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [c17c4d475f](https://linux-hardware.org/?probe=c17c4d475f) | Sep 05, 2022 |
| Clevo         | P65_P67SE                   | Notebook    | [9a38027b73](https://linux-hardware.org/?probe=9a38027b73) | Sep 05, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [cb787086fa](https://linux-hardware.org/?probe=cb787086fa) | Sep 05, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [f6e3690dd8](https://linux-hardware.org/?probe=f6e3690dd8) | Sep 04, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [61e1164988](https://linux-hardware.org/?probe=61e1164988) | Sep 04, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [ea5f9662d7](https://linux-hardware.org/?probe=ea5f9662d7) | Sep 04, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [8f5998a9e4](https://linux-hardware.org/?probe=8f5998a9e4) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8b964572d7](https://linux-hardware.org/?probe=8b964572d7) | Sep 04, 2022 |
| Alienware     | 0NWN7M A00                  | Desktop     | [e254b049c3](https://linux-hardware.org/?probe=e254b049c3) | Sep 04, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [c40b757ca3](https://linux-hardware.org/?probe=c40b757ca3) | Sep 04, 2022 |
| MSI           | GP72 7RDX                   | Notebook    | [5d4efc6589](https://linux-hardware.org/?probe=5d4efc6589) | Sep 04, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [70de682c06](https://linux-hardware.org/?probe=70de682c06) | Sep 03, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | Notebook    | [b75636bf8b](https://linux-hardware.org/?probe=b75636bf8b) | Sep 03, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [bd0c518002](https://linux-hardware.org/?probe=bd0c518002) | Sep 03, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [81eb6e9f4e](https://linux-hardware.org/?probe=81eb6e9f4e) | Sep 03, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [0ab8b4e169](https://linux-hardware.org/?probe=0ab8b4e169) | Sep 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [39e1d43301](https://linux-hardware.org/?probe=39e1d43301) | Sep 03, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [db5a53a31c](https://linux-hardware.org/?probe=db5a53a31c) | Sep 03, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [de7dc826b0](https://linux-hardware.org/?probe=de7dc826b0) | Sep 03, 2022 |
| Intel         | DX58SO AAE29331-702         | Desktop     | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [cfb4e75518](https://linux-hardware.org/?probe=cfb4e75518) | Sep 03, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [7b914b0347](https://linux-hardware.org/?probe=7b914b0347) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [5472c45d04](https://linux-hardware.org/?probe=5472c45d04) | Sep 03, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [6e45ea1408](https://linux-hardware.org/?probe=6e45ea1408) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| Lenovo        | IdeaPad Flex-15IWL 81SR     | Convertible | [6723781de1](https://linux-hardware.org/?probe=6723781de1) | Sep 03, 2022 |
| Dell          | 0FGCC7 A01                  | Server      | [4689cac5c7](https://linux-hardware.org/?probe=4689cac5c7) | Sep 03, 2022 |
| HP            | 1497                        | Desktop     | [a8566c45a9](https://linux-hardware.org/?probe=a8566c45a9) | Sep 03, 2022 |
| MSI           | MEG Z390 ACE                | Desktop     | [1f702cfc06](https://linux-hardware.org/?probe=1f702cfc06) | Sep 03, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [39cb364d6f](https://linux-hardware.org/?probe=39cb364d6f) | Sep 03, 2022 |
| Dell          | Latitude E5570              | Notebook    | [20350411cf](https://linux-hardware.org/?probe=20350411cf) | Sep 03, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [2e3f16bc80](https://linux-hardware.org/?probe=2e3f16bc80) | Sep 02, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S80G00    | Notebook    | [bd599c876c](https://linux-hardware.org/?probe=bd599c876c) | Sep 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d664029076](https://linux-hardware.org/?probe=d664029076) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [d8505e212b](https://linux-hardware.org/?probe=d8505e212b) | Sep 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [9b42566191](https://linux-hardware.org/?probe=9b42566191) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [8e366d7e21](https://linux-hardware.org/?probe=8e366d7e21) | Sep 02, 2022 |
| HP            | 87D6 SMVB                   | Desktop     | [8efd1ba4e0](https://linux-hardware.org/?probe=8efd1ba4e0) | Sep 02, 2022 |
| Dell          | Precision 5530              | Notebook    | [0151d15e28](https://linux-hardware.org/?probe=0151d15e28) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [4f4717cb85](https://linux-hardware.org/?probe=4f4717cb85) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b6e6d0a261](https://linux-hardware.org/?probe=b6e6d0a261) | Sep 02, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [7ef3570396](https://linux-hardware.org/?probe=7ef3570396) | Sep 02, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [1746053c5b](https://linux-hardware.org/?probe=1746053c5b) | Sep 01, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [fb12fe29dd](https://linux-hardware.org/?probe=fb12fe29dd) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Dell          | G3 3590                     | Notebook    | [cbe6c26276](https://linux-hardware.org/?probe=cbe6c26276) | Sep 01, 2022 |
| ASUSTek       | N552VW                      | Notebook    | [99d4a9be86](https://linux-hardware.org/?probe=99d4a9be86) | Sep 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [55073b08dc](https://linux-hardware.org/?probe=55073b08dc) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [e311938d4a](https://linux-hardware.org/?probe=e311938d4a) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| Apple         | MacBookAir9,1               | Notebook    | [51c4002c97](https://linux-hardware.org/?probe=51c4002c97) | Sep 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [d96b24b7f3](https://linux-hardware.org/?probe=d96b24b7f3) | Sep 01, 2022 |
| ASRock        | B450M/ac                    | Desktop     | [393a08345e](https://linux-hardware.org/?probe=393a08345e) | Sep 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [838e09c9cf](https://linux-hardware.org/?probe=838e09c9cf) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| Acer          | Aspire X3400                | Desktop     | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [d6e9455a63](https://linux-hardware.org/?probe=d6e9455a63) | Aug 31, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [1dd7a06125](https://linux-hardware.org/?probe=1dd7a06125) | Aug 31, 2022 |
| Dell          | Latitude 7275               | Tablet      | [fce77a6b4b](https://linux-hardware.org/?probe=fce77a6b4b) | Aug 31, 2022 |
| Dell          | Latitude 7275               | Tablet      | [896ceefe29](https://linux-hardware.org/?probe=896ceefe29) | Aug 31, 2022 |
| Acer          | Aspire X3400                | Desktop     | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | Desktop     | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [42666a5460](https://linux-hardware.org/?probe=42666a5460) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [6eeadaf886](https://linux-hardware.org/?probe=6eeadaf886) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [56e8f54a3e](https://linux-hardware.org/?probe=56e8f54a3e) | Aug 31, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4db54180a8](https://linux-hardware.org/?probe=4db54180a8) | Aug 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [6d04d534fa](https://linux-hardware.org/?probe=6d04d534fa) | Aug 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [988032b933](https://linux-hardware.org/?probe=988032b933) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [dc23941a16](https://linux-hardware.org/?probe=dc23941a16) | Aug 31, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | Notebook    | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | Notebook    | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e5545fc36a](https://linux-hardware.org/?probe=e5545fc36a) | Aug 30, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [d0ca11a18a](https://linux-hardware.org/?probe=d0ca11a18a) | Aug 29, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [fb155ef3bd](https://linux-hardware.org/?probe=fb155ef3bd) | Aug 29, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [58d3152512](https://linux-hardware.org/?probe=58d3152512) | Aug 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [b91ce43523](https://linux-hardware.org/?probe=b91ce43523) | Aug 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [289c5dc0b6](https://linux-hardware.org/?probe=289c5dc0b6) | Aug 29, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [059ab7e21e](https://linux-hardware.org/?probe=059ab7e21e) | Aug 29, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [907d5f36e6](https://linux-hardware.org/?probe=907d5f36e6) | Aug 29, 2022 |
| HP            | 1497                        | Desktop     | [625185d1db](https://linux-hardware.org/?probe=625185d1db) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [aa5f4a0207](https://linux-hardware.org/?probe=aa5f4a0207) | Aug 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [281360b58a](https://linux-hardware.org/?probe=281360b58a) | Aug 29, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [065da8ca1e](https://linux-hardware.org/?probe=065da8ca1e) | Aug 29, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [13fdf5ef5e](https://linux-hardware.org/?probe=13fdf5ef5e) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [2d89536f80](https://linux-hardware.org/?probe=2d89536f80) | Aug 28, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [d8bd3d6fc6](https://linux-hardware.org/?probe=d8bd3d6fc6) | Aug 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a328df0016](https://linux-hardware.org/?probe=a328df0016) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [f07bd2b99b](https://linux-hardware.org/?probe=f07bd2b99b) | Aug 28, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [d0c37f7188](https://linux-hardware.org/?probe=d0c37f7188) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | Notebook    | [c4be3fe1b6](https://linux-hardware.org/?probe=c4be3fe1b6) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | Notebook    | [568802fb43](https://linux-hardware.org/?probe=568802fb43) | Aug 28, 2022 |
| HP            | ENVY dv7                    | Notebook    | [cbd3824347](https://linux-hardware.org/?probe=cbd3824347) | Aug 28, 2022 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [b04fc1333e](https://linux-hardware.org/?probe=b04fc1333e) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [a90735a9e9](https://linux-hardware.org/?probe=a90735a9e9) | Aug 27, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [2e085a419b](https://linux-hardware.org/?probe=2e085a419b) | Aug 27, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c47cd7c7ed](https://linux-hardware.org/?probe=c47cd7c7ed) | Aug 27, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [262ff7d08a](https://linux-hardware.org/?probe=262ff7d08a) | Aug 27, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [1746f3874c](https://linux-hardware.org/?probe=1746f3874c) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [704ce84e6a](https://linux-hardware.org/?probe=704ce84e6a) | Aug 27, 2022 |
| Lenovo        | ThinkPad 20M8S1K100         | Convertible | [4e77e4b1a0](https://linux-hardware.org/?probe=4e77e4b1a0) | Aug 27, 2022 |
| Dell          | XPS 9315                    | Notebook    | [6ab1d7417d](https://linux-hardware.org/?probe=6ab1d7417d) | Aug 27, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [fdb7c715b3](https://linux-hardware.org/?probe=fdb7c715b3) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | Notebook    | [a45848f10f](https://linux-hardware.org/?probe=a45848f10f) | Aug 26, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [88467a99ae](https://linux-hardware.org/?probe=88467a99ae) | Aug 26, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [55ebdff357](https://linux-hardware.org/?probe=55ebdff357) | Aug 26, 2022 |
| Dell          | Precision M4600             | Notebook    | [de9a03d9be](https://linux-hardware.org/?probe=de9a03d9be) | Aug 26, 2022 |
| HP            | 1850                        | Desktop     | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [8aa6fdef16](https://linux-hardware.org/?probe=8aa6fdef16) | Aug 26, 2022 |
| ASRock        | X570 Creator                | Desktop     | [612ada6405](https://linux-hardware.org/?probe=612ada6405) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | Notebook    | [0ec106ca31](https://linux-hardware.org/?probe=0ec106ca31) | Aug 26, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [d988a14a82](https://linux-hardware.org/?probe=d988a14a82) | Aug 26, 2022 |
| Dell          | Precision M4600             | Notebook    | [83c727c6db](https://linux-hardware.org/?probe=83c727c6db) | Aug 26, 2022 |
| Acer          | Aspire X3400                | Desktop     | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [edac754e93](https://linux-hardware.org/?probe=edac754e93) | Aug 25, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [8d1cad5e52](https://linux-hardware.org/?probe=8d1cad5e52) | Aug 25, 2022 |
| Dell          | Latitude 7275               | Tablet      | [41f2262c86](https://linux-hardware.org/?probe=41f2262c86) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | Notebook    | [5237518074](https://linux-hardware.org/?probe=5237518074) | Aug 25, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [7e2c842043](https://linux-hardware.org/?probe=7e2c842043) | Aug 25, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [b502ab922f](https://linux-hardware.org/?probe=b502ab922f) | Aug 25, 2022 |
| Dell          | Latitude 7275               | Tablet      | [43d764b91f](https://linux-hardware.org/?probe=43d764b91f) | Aug 24, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [b008775e13](https://linux-hardware.org/?probe=b008775e13) | Aug 24, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [5e20db2905](https://linux-hardware.org/?probe=5e20db2905) | Aug 24, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [f0c2f3a689](https://linux-hardware.org/?probe=f0c2f3a689) | Aug 24, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [967ff51388](https://linux-hardware.org/?probe=967ff51388) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [4263165650](https://linux-hardware.org/?probe=4263165650) | Aug 24, 2022 |
| ASRock        | B660-ITX                    | Desktop     | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| HP            | 3647h                       | Desktop     | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [35ffc8d54b](https://linux-hardware.org/?probe=35ffc8d54b) | Aug 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [6cb194ca87](https://linux-hardware.org/?probe=6cb194ca87) | Aug 23, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [beb3c92510](https://linux-hardware.org/?probe=beb3c92510) | Aug 23, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [92b070c9be](https://linux-hardware.org/?probe=92b070c9be) | Aug 23, 2022 |
| Positivo      | W942SV_SV1                  | Notebook    | [24ad2b387d](https://linux-hardware.org/?probe=24ad2b387d) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [62dbb0625f](https://linux-hardware.org/?probe=62dbb0625f) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [e5442dd2d4](https://linux-hardware.org/?probe=e5442dd2d4) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [8e57e188c9](https://linux-hardware.org/?probe=8e57e188c9) | Aug 23, 2022 |
| ASUSTek       | P9X79 LE                    | Desktop     | [1fbde15177](https://linux-hardware.org/?probe=1fbde15177) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [33a1092c01](https://linux-hardware.org/?probe=33a1092c01) | Aug 22, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [33ff4e4962](https://linux-hardware.org/?probe=33ff4e4962) | Aug 22, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Dell          | 02P9X9 A00                  | Server      | [b7d9a0c4a2](https://linux-hardware.org/?probe=b7d9a0c4a2) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [6b5ced2971](https://linux-hardware.org/?probe=6b5ced2971) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [52a1f16ef3](https://linux-hardware.org/?probe=52a1f16ef3) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [ae19610f33](https://linux-hardware.org/?probe=ae19610f33) | Aug 21, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7c763e43c6](https://linux-hardware.org/?probe=7c763e43c6) | Aug 21, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [f67221bd42](https://linux-hardware.org/?probe=f67221bd42) | Aug 21, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [fac0116bf7](https://linux-hardware.org/?probe=fac0116bf7) | Aug 21, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [19158f2e35](https://linux-hardware.org/?probe=19158f2e35) | Aug 21, 2022 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [314250b1d7](https://linux-hardware.org/?probe=314250b1d7) | Aug 21, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [256a057752](https://linux-hardware.org/?probe=256a057752) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [c717f7c6d5](https://linux-hardware.org/?probe=c717f7c6d5) | Aug 21, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [3f12b83029](https://linux-hardware.org/?probe=3f12b83029) | Aug 20, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [8df71394cd](https://linux-hardware.org/?probe=8df71394cd) | Aug 20, 2022 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [d7d2cfb261](https://linux-hardware.org/?probe=d7d2cfb261) | Aug 20, 2022 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [d9b92f7c2c](https://linux-hardware.org/?probe=d9b92f7c2c) | Aug 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [0cef35b44a](https://linux-hardware.org/?probe=0cef35b44a) | Aug 20, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [b6df5aec25](https://linux-hardware.org/?probe=b6df5aec25) | Aug 20, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [774796ffbd](https://linux-hardware.org/?probe=774796ffbd) | Aug 20, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                              | Computers | Percent |
|--------------------------------------|-----------|---------|
| 5.19.0-76051900-generic              | 434       | 25.82%  |
| 5.17.5-76051705-generic              | 408       | 24.27%  |
| 5.18.10-76051810-generic             | 201       | 11.96%  |
| 5.17.15-76051715-generic             | 184       | 10.95%  |
| 6.0.6-76060006-generic               | 129       | 7.67%   |
| 5.16.19-76051619-generic             | 119       | 7.08%   |
| 6.0.2-76060002-generic               | 82        | 4.88%   |
| 5.19.16-76051916-generic             | 42        | 2.5%    |
| 6.0.3-76060003-generic               | 38        | 2.26%   |
| 5.16.15-76051615-generic             | 3         | 0.18%   |
| 6.0.9-060009-generic                 | 2         | 0.12%   |
| 6.0.2-x64v1-xanmod1                  | 2         | 0.12%   |
| 5.19.12-xanmod1                      | 2         | 0.12%   |
| 5.17.7-051707-generic                | 2         | 0.12%   |
| 5.17.5-051705-generic                | 2         | 0.12%   |
| 6.0.9-x64v1-xanmod1                  | 1         | 0.06%   |
| 6.0.8-x64v1-xanmod1                  | 1         | 0.06%   |
| 6.0.7-x64v1-xanmod1                  | 1         | 0.06%   |
| 6.0.6-060006-generic                 | 1         | 0.06%   |
| 6.0.2-x64v2-xanmod1                  | 1         | 0.06%   |
| 6.0.0-060000rc1daily20220820-generic | 1         | 0.06%   |
| 6.0.0-060000-generic                 | 1         | 0.06%   |
| 5.4.210-whitehax0r                   | 1         | 0.06%   |
| 5.19.6-xanmod1-x64v2                 | 1         | 0.06%   |
| 5.19.3-051903-generic                | 1         | 0.06%   |
| 5.19.14-xanmod1                      | 1         | 0.06%   |
| 5.19.0-xanmod1-x64v2                 | 1         | 0.06%   |
| 5.19.0-rc1+                          | 1         | 0.06%   |
| 5.19.0-051900-generic                | 1         | 0.06%   |
| 5.18.6-xanmod1                       | 1         | 0.06%   |
| 5.18.4-xanmod1                       | 1         | 0.06%   |
| 5.18.16-xanmod1                      | 1         | 0.06%   |
| 5.18.11-051811-generic               | 1         | 0.06%   |
| 5.18.0-9.1-liquorix-amd64            | 1         | 0.06%   |
| 5.18.0-051800rc1-generic             | 1         | 0.06%   |
| 5.17.9-051709-generic                | 1         | 0.06%   |
| 5.17.6-051706-generic                | 1         | 0.06%   |
| 5.17.5-tkg-bmq                       | 1         | 0.06%   |
| 5.17.4-051704-generic                | 1         | 0.06%   |
| 5.17.2-xanmod1                       | 1         | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 437       | 26%     |
| 5.17.5  | 411       | 24.45%  |
| 5.18.10 | 201       | 11.96%  |
| 5.17.15 | 184       | 10.95%  |
| 6.0.6   | 130       | 7.73%   |
| 5.16.19 | 119       | 7.08%   |
| 6.0.2   | 85        | 5.06%   |
| 5.19.16 | 42        | 2.5%    |
| 6.0.3   | 38        | 2.26%   |
| 6.0.9   | 3         | 0.18%   |
| 5.16.15 | 3         | 0.18%   |
| 6.0.0   | 2         | 0.12%   |
| 5.19.12 | 2         | 0.12%   |
| 5.18.0  | 2         | 0.12%   |
| 5.17.7  | 2         | 0.12%   |
| 5.15.0  | 2         | 0.12%   |
| 6.0.8   | 1         | 0.06%   |
| 6.0.7   | 1         | 0.06%   |
| 5.4.210 | 1         | 0.06%   |
| 5.19.6  | 1         | 0.06%   |
| 5.19.3  | 1         | 0.06%   |
| 5.19.14 | 1         | 0.06%   |
| 5.18.6  | 1         | 0.06%   |
| 5.18.4  | 1         | 0.06%   |
| 5.18.16 | 1         | 0.06%   |
| 5.18.11 | 1         | 0.06%   |
| 5.17.9  | 1         | 0.06%   |
| 5.17.6  | 1         | 0.06%   |
| 5.17.4  | 1         | 0.06%   |
| 5.17.2  | 1         | 0.06%   |
| 5.17.14 | 1         | 0.06%   |
| 5.17.0  | 1         | 0.06%   |
| 5.16.11 | 1         | 0.06%   |
| 5.15.15 | 1         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17    | 590       | 35.54%  |
| 5.19    | 480       | 28.92%  |
| 6.0     | 256       | 15.42%  |
| 5.18    | 207       | 12.47%  |
| 5.16    | 123       | 7.41%   |
| 5.15    | 3         | 0.18%   |
| 5.4     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1568      | 99.94%  |
| aarch64 | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1525      | 96.89%  |
| KDE5            | 23        | 1.46%   |
| Unknown         | 10        | 0.64%   |
| X-Cinnamon      | 7         | 0.44%   |
| GNOME Flashback | 3         | 0.19%   |
| LXQt            | 2         | 0.13%   |
| Cinnamon        | 2         | 0.13%   |
| XFCE            | 1         | 0.06%   |
| Unity           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1501      | 95.18%  |
| Wayland | 65        | 4.12%   |
| Unknown | 8         | 0.51%   |
| Tty     | 3         | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1196      | 75.84%  |
| GDM3    | 371       | 23.53%  |
| GDM     | 5         | 0.32%   |
| SDDM    | 4         | 0.25%   |
| LightDM | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 941       | 59.67%  |
| en_GB   | 112       | 7.1%    |
| pt_BR   | 89        | 5.64%   |
| de_DE   | 64        | 4.06%   |
| en_AU   | 42        | 2.66%   |
| C       | 40        | 2.54%   |
| it_IT   | 38        | 2.41%   |
| en_CA   | 33        | 2.09%   |
| fr_FR   | 30        | 1.9%    |
| es_ES   | 20        | 1.27%   |
| pl_PL   | 17        | 1.08%   |
| ru_RU   | 12        | 0.76%   |
| sv_SE   | 10        | 0.63%   |
| fi_FI   | 10        | 0.63%   |
| Unknown | 10        | 0.63%   |
| nb_NO   | 9         | 0.57%   |
| nl_NL   | 7         | 0.44%   |
| es_CL   | 7         | 0.44%   |
| en_IE   | 7         | 0.44%   |
| pt_PT   | 6         | 0.38%   |
| en_IN   | 6         | 0.38%   |
| fr_CA   | 5         | 0.32%   |
| es_AR   | 5         | 0.32%   |
| ja_JP   | 4         | 0.25%   |
| es_MX   | 4         | 0.25%   |
| en_DK   | 4         | 0.25%   |
| de_CH   | 4         | 0.25%   |
| de_AT   | 4         | 0.25%   |
| es_CO   | 3         | 0.19%   |
| en_NZ   | 3         | 0.19%   |
| da_DK   | 3         | 0.19%   |
| zh_TW   | 2         | 0.13%   |
| ro_RO   | 2         | 0.13%   |
| fr_CH   | 2         | 0.13%   |
| fr_BE   | 2         | 0.13%   |
| es_UY   | 2         | 0.13%   |
| en_ZA   | 2         | 0.13%   |
| en_SG   | 2         | 0.13%   |
| cs_CZ   | 2         | 0.13%   |
| tr_TR   | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1217      | 77.22%  |
| EFI  | 359       | 22.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1488      | 94.66%  |
| Btrfs   | 52        | 3.31%   |
| Overlay | 27        | 1.72%   |
| Xfs     | 4         | 0.25%   |
| Zfs     | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1186      | 75.21%  |
| GPT     | 369       | 23.4%   |
| MBR     | 22        | 1.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1519      | 96.63%  |
| Yes       | 53        | 3.37%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1418      | 90.2%   |
| Yes       | 154       | 9.8%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 289       | 18.42%  |
| Lenovo              | 215       | 13.7%   |
| Dell                | 207       | 13.19%  |
| Hewlett-Packard     | 169       | 10.77%  |
| MSI                 | 119       | 7.58%   |
| Gigabyte Technology | 102       | 6.5%    |
| Apple               | 79        | 5.04%   |
| Acer                | 76        | 4.84%   |
| ASRock              | 49        | 3.12%   |
| System76            | 37        | 2.36%   |
| Intel               | 22        | 1.4%    |
| Toshiba             | 21        | 1.34%   |
| Samsung Electronics | 19        | 1.21%   |
| HUAWEI              | 15        | 0.96%   |
| Alienware           | 11        | 0.7%    |
| Microsoft           | 9         | 0.57%   |
| Fujitsu             | 9         | 0.57%   |
| Google              | 8         | 0.51%   |
| Unknown             | 7         | 0.45%   |
| Sony                | 6         | 0.38%   |
| GPU Company         | 6         | 0.38%   |
| Notebook            | 5         | 0.32%   |
| Razer               | 4         | 0.25%   |
| Pegatron            | 4         | 0.25%   |
| Framework           | 4         | 0.25%   |
| Timi                | 3         | 0.19%   |
| Positivo            | 3         | 0.19%   |
| PC Specialist       | 3         | 0.19%   |
| Medion              | 3         | 0.19%   |
| MACHINIST           | 3         | 0.19%   |
| Foxconn             | 3         | 0.19%   |
| BESSTAR Tech        | 3         | 0.19%   |
| AZW                 | 3         | 0.19%   |
| Valve               | 2         | 0.13%   |
| TUXEDO              | 2         | 0.13%   |
| Panasonic           | 2         | 0.13%   |
| NZXT                | 2         | 0.13%   |
| IP3 Tech            | 2         | 0.13%   |
| HONOR               | 2         | 0.13%   |
| EVGA                | 2         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| System76 Oryx Pro                    | 12        | 0.76%   |
| ASUS All Series                      | 11        | 0.7%    |
| Unknown                              | 10        | 0.64%   |
| System76 Lemur Pro                   | 8         | 0.51%   |
| ASUS TUF Gaming B550-PLUS            | 7         | 0.45%   |
| Apple MacBookAir7,2                  | 7         | 0.45%   |
| Apple MacBookAir6,2                  | 7         | 0.45%   |
| Gigabyte B450 AORUS M                | 6         | 0.38%   |
| Dell XPS 15 9520                     | 6         | 0.38%   |
| ASUS ROG STRIX B550-F GAMING         | 6         | 0.38%   |
| Lenovo IdeaPad S145-15API 81V7       | 5         | 0.32%   |
| Gigabyte X570 AORUS ELITE            | 5         | 0.32%   |
| ASUS ROG STRIX B550-I GAMING         | 5         | 0.32%   |
| ASUS ROG STRIX B450-F GAMING         | 5         | 0.32%   |
| Apple MacBookPro9,2                  | 5         | 0.32%   |
| System76 Thelio                      | 4         | 0.25%   |
| MSI MS-7B86                          | 4         | 0.25%   |
| Gigabyte B450M DS3H                  | 4         | 0.25%   |
| Dell XPS 13 9310                     | 4         | 0.25%   |
| ASUS ROG CROSSHAIR VIII DARK HERO    | 4         | 0.25%   |
| ASUS PRIME B450M-A                   | 4         | 0.25%   |
| Apple MacBookPro7,1                  | 4         | 0.25%   |
| Acer Aspire A515-45                  | 4         | 0.25%   |
| System76 Galago Pro                  | 3         | 0.19%   |
| System76 Darter Pro                  | 3         | 0.19%   |
| MSI Prestige 15 A10SC                | 3         | 0.19%   |
| MSI MS-7D54                          | 3         | 0.19%   |
| MSI MS-7D25                          | 3         | 0.19%   |
| MSI MS-7C56                          | 3         | 0.19%   |
| MSI MS-7C37                          | 3         | 0.19%   |
| MSI MS-7C35                          | 3         | 0.19%   |
| MSI MS-7C02                          | 3         | 0.19%   |
| MSI MS-7A34                          | 3         | 0.19%   |
| MSI MS-7693                          | 3         | 0.19%   |
| Lenovo Legion Y530-15ICH 81FV        | 3         | 0.19%   |
| Lenovo IdeaPad 3 15ALC6 82MF         | 3         | 0.19%   |
| HP Pavilion Notebook                 | 3         | 0.19%   |
| HP Pavilion 15                       | 3         | 0.19%   |
| HP OMEN Laptop 15-en0xxx             | 3         | 0.19%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx | 3         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 80        | 5.1%    |
| ASUS ROG           | 79        | 5.04%   |
| Dell Inspiron      | 57        | 3.63%   |
| Acer Aspire        | 50        | 3.19%   |
| Lenovo IdeaPad     | 47        | 3%      |
| Dell Latitude      | 42        | 2.68%   |
| Dell XPS           | 39        | 2.49%   |
| ASUS TUF           | 29        | 1.85%   |
| Dell Precision     | 28        | 1.78%   |
| HP Pavilion        | 26        | 1.66%   |
| ASUS PRIME         | 26        | 1.66%   |
| Lenovo Legion      | 23        | 1.47%   |
| HP Laptop          | 22        | 1.4%    |
| HP EliteBook       | 21        | 1.34%   |
| ASUS VivoBook      | 20        | 1.27%   |
| Toshiba Satellite  | 18        | 1.15%   |
| HP ProBook         | 18        | 1.15%   |
| HP ENVY            | 18        | 1.15%   |
| Lenovo Yoga        | 14        | 0.89%   |
| Lenovo ThinkCentre | 14        | 0.89%   |
| Dell OptiPlex      | 14        | 0.89%   |
| ASUS ZenBook       | 14        | 0.89%   |
| Dell Vostro        | 13        | 0.83%   |
| ASUS ASUS          | 13        | 0.83%   |
| System76 Oryx      | 12        | 0.76%   |
| Gigabyte X570      | 12        | 0.76%   |
| HP Compaq          | 11        | 0.7%    |
| ASUS All           | 11        | 0.7%    |
| Acer Nitro         | 10        | 0.64%   |
| Unknown            | 10        | 0.64%   |
| Microsoft Surface  | 9         | 0.57%   |
| HP OMEN            | 9         | 0.57%   |
| Gigabyte B450      | 9         | 0.57%   |
| Acer Swift         | 9         | 0.57%   |
| System76 Lemur     | 8         | 0.51%   |
| Lenovo ThinkBook   | 8         | 0.51%   |
| HP ZBook           | 8         | 0.51%   |
| HP EliteDesk       | 8         | 0.51%   |
| Apple MacBookPro11 | 8         | 0.51%   |
| Apple MacBookAir7  | 7         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 233       | 14.85%  |
| 2020    | 215       | 13.7%   |
| 2019    | 166       | 10.58%  |
| 2018    | 152       | 9.69%   |
| 2022    | 121       | 7.71%   |
| 2016    | 90        | 5.74%   |
| 2013    | 87        | 5.54%   |
| 2012    | 87        | 5.54%   |
| 2017    | 86        | 5.48%   |
| 2014    | 76        | 4.84%   |
| 2015    | 72        | 4.59%   |
| 2011    | 63        | 4.02%   |
| 2010    | 52        | 3.31%   |
| 2009    | 44        | 2.8%    |
| 2008    | 15        | 0.96%   |
| 2007    | 8         | 0.51%   |
| 2006    | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 922       | 58.76%  |
| Desktop        | 526       | 33.52%  |
| Convertible    | 62        | 3.95%   |
| Mini pc        | 23        | 1.47%   |
| All in one     | 16        | 1.02%   |
| Tablet         | 14        | 0.89%   |
| Server         | 4         | 0.25%   |
| System on chip | 2         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1568      | 99.94%  |
| Enabled  | 1         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1538      | 98.02%  |
| Yes  | 31        | 1.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 441       | 27.93%  |
| 4.01-8.0        | 360       | 22.8%   |
| 8.01-16.0       | 277       | 17.54%  |
| 32.01-64.0      | 253       | 16.02%  |
| 3.01-4.0        | 144       | 9.12%   |
| 64.01-256.0     | 70        | 4.43%   |
| 24.01-32.0      | 24        | 1.52%   |
| 1.01-2.0        | 4         | 0.25%   |
| More than 256.0 | 3         | 0.19%   |
| 2.01-3.0        | 3         | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 545       | 32.56%  |
| 4.01-8.0    | 406       | 24.25%  |
| 3.01-4.0    | 400       | 23.89%  |
| 1.01-2.0    | 199       | 11.89%  |
| 8.01-16.0   | 99        | 5.91%   |
| 16.01-24.0  | 18        | 1.08%   |
| 32.01-64.0  | 4         | 0.24%   |
| 24.01-32.0  | 2         | 0.12%   |
| 64.01-256.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 920       | 58.23%  |
| 2      | 408       | 25.82%  |
| 3      | 142       | 8.99%   |
| 4      | 53        | 3.35%   |
| 5      | 25        | 1.58%   |
| 6      | 15        | 0.95%   |
| 7      | 7         | 0.44%   |
| 9      | 3         | 0.19%   |
| 0      | 3         | 0.19%   |
| 10     | 2         | 0.13%   |
| 19     | 1         | 0.06%   |
| 11     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1201      | 76.45%  |
| Yes       | 370       | 23.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1277      | 81.03%  |
| No        | 299       | 18.97%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1328      | 84.48%  |
| No        | 244       | 15.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1144      | 72.63%  |
| No        | 431       | 27.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 486       | 30.82%  |
| Brazil       | 123       | 7.8%    |
| Germany      | 93        | 5.9%    |
| UK           | 74        | 4.69%   |
| Italy        | 74        | 4.69%   |
| Canada       | 67        | 4.25%   |
| Australia    | 50        | 3.17%   |
| India        | 46        | 2.92%   |
| France       | 44        | 2.79%   |
| Netherlands  | 30        | 1.9%    |
| Norway       | 26        | 1.65%   |
| Russia       | 25        | 1.59%   |
| Sweden       | 23        | 1.46%   |
| Poland       | 23        | 1.46%   |
| Spain        | 22        | 1.4%    |
| Finland      | 20        | 1.27%   |
| Switzerland  | 18        | 1.14%   |
| Mexico       | 17        | 1.08%   |
| Portugal     | 16        | 1.01%   |
| Greece       | 15        | 0.95%   |
| Argentina    | 14        | 0.89%   |
| Austria      | 13        | 0.82%   |
| Romania      | 12        | 0.76%   |
| Chile        | 12        | 0.76%   |
| Turkey       | 11        | 0.7%    |
| Indonesia    | 11        | 0.7%    |
| Belgium      | 11        | 0.7%    |
| Philippines  | 10        | 0.63%   |
| Japan        | 10        | 0.63%   |
| New Zealand  | 9         | 0.57%   |
| Ireland      | 9         | 0.57%   |
| Denmark      | 9         | 0.57%   |
| Thailand     | 8         | 0.51%   |
| South Africa | 7         | 0.44%   |
| Hungary      | 7         | 0.44%   |
| Egypt        | 7         | 0.44%   |
| Colombia     | 7         | 0.44%   |
| Singapore    | 6         | 0.38%   |
| Serbia       | 6         | 0.38%   |
| Hong Kong    | 6         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Milan          | 16        | 1%      |
| Berlin         | 14        | 0.87%   |
| Brisbane       | 13        | 0.81%   |
| Melbourne      | 12        | 0.75%   |
| Rome           | 11        | 0.69%   |
| Rio de Janeiro | 11        | 0.69%   |
| Helsinki       | 11        | 0.69%   |
| Sao Paulo      | 10        | 0.62%   |
| Zurich         | 9         | 0.56%   |
| Oslo           | 9         | 0.56%   |
| Istanbul       | 9         | 0.56%   |
| Vienna         | 8         | 0.5%    |
| Sydney         | 8         | 0.5%    |
| Seattle        | 8         | 0.5%    |
| Moscow         | 8         | 0.5%    |
| Bengaluru      | 8         | 0.5%    |
| Paris          | 7         | 0.44%   |
| Madrid         | 7         | 0.44%   |
| London         | 7         | 0.44%   |
| Dallas         | 7         | 0.44%   |
| Toronto        | 6         | 0.37%   |
| Singapore      | 6         | 0.37%   |
| San Francisco  | 6         | 0.37%   |
| Mannheim       | 6         | 0.37%   |
| Lincoln        | 6         | 0.37%   |
| Jakarta        | 6         | 0.37%   |
| Edmonton       | 6         | 0.37%   |
| Athens         | 6         | 0.37%   |
| Stockholm      | 5         | 0.31%   |
| St Petersburg  | 5         | 0.31%   |
| Munich         | 5         | 0.31%   |
| Mumbai         | 5         | 0.31%   |
| Lisbon         | 5         | 0.31%   |
| Hamburg        | 5         | 0.31%   |
| Denver         | 5         | 0.31%   |
| Chicago        | 5         | 0.31%   |
| Amsterdam      | 5         | 0.31%   |
| Warsaw         | 4         | 0.25%   |
| Virginia Beach | 4         | 0.25%   |
| Tucson         | 4         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 452       | 608    | 18.87%  |
| WDC                            | 276       | 367    | 11.52%  |
| Seagate                        | 261       | 354    | 10.9%   |
| SanDisk                        | 181       | 217    | 7.56%   |
| Toshiba                        | 127       | 143    | 5.3%    |
| Kingston                       | 125       | 146    | 5.22%   |
| Crucial                        | 107       | 144    | 4.47%   |
| SK hynix                       | 86        | 96     | 3.59%   |
| Intel                          | 64        | 76     | 2.67%   |
| Unknown                        | 59        | 80     | 2.46%   |
| Micron Technology              | 56        | 62     | 2.34%   |
| Apple                          | 45        | 50     | 1.88%   |
| Phison                         | 41        | 52     | 1.71%   |
| HGST                           | 38        | 41     | 1.59%   |
| Hitachi                        | 36        | 49     | 1.5%    |
| A-DATA Technology              | 35        | 37     | 1.46%   |
| PNY                            | 25        | 33     | 1.04%   |
| Micron/Crucial Technology      | 25        | 29     | 1.04%   |
| Silicon Motion                 | 23        | 29     | 0.96%   |
| Phison Electronics             | 20        | 29     | 0.84%   |
| China                          | 20        | 24     | 0.84%   |
| KIOXIA                         | 17        | 18     | 0.71%   |
| SPCC                           | 16        | 20     | 0.67%   |
| Netac                          | 13        | 14     | 0.54%   |
| Intenso                        | 10        | 10     | 0.42%   |
| Unknown                        | 10        | 11     | 0.42%   |
| Team                           | 9         | 11     | 0.38%   |
| LITEON                         | 9         | 11     | 0.38%   |
| Patriot                        | 8         | 9      | 0.33%   |
| ADATA Technology               | 8         | 8      | 0.33%   |
| OCZ                            | 7         | 9      | 0.29%   |
| Lexar                          | 7         | 7      | 0.29%   |
| KingSpec                       | 7         | 8      | 0.29%   |
| XPG                            | 6         | 7      | 0.25%   |
| Union Memory (Shenzhen)        | 6         | 8      | 0.25%   |
| LITEONIT                       | 6         | 9      | 0.25%   |
| JMicron Technology             | 6         | 15     | 0.25%   |
| Corsair                        | 6         | 8      | 0.25%   |
| Solid State Storage Technology | 5         | 5      | 0.21%   |
| Kingston Technology Company    | 5         | 5      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB                           | 36        | 1.35%   |
| Kingston SA400S37240G 240GB SSD                      | 32        | 1.2%    |
| Samsung NVMe SSD Drive 500GB                         | 29        | 1.09%   |
| SanDisk NVMe SSD Drive 1TB                           | 28        | 1.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 24        | 0.9%    |
| Samsung SSD 850 EVO 500GB                            | 22        | 0.83%   |
| Samsung NVMe SSD Drive 512GB                         | 22        | 0.83%   |
| Seagate ST2000DM008-2FR102 2TB                       | 21        | 0.79%   |
| Samsung NVMe SSD Drive 2TB                           | 20        | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                       | 19        | 0.71%   |
| Crucial CT1000MX500SSD1 1TB                          | 18        | 0.68%   |
| Samsung SSD 860 EVO 1TB                              | 17        | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                         | 16        | 0.6%    |
| SK hynix NVMe SSD Drive 512GB                        | 15        | 0.56%   |
| Samsung SSD 850 EVO 250GB                            | 15        | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB                       | 14        | 0.53%   |
| Samsung SSD 860 EVO 500GB                            | 14        | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 14        | 0.53%   |
| Kingston SA400S37480G 480GB SSD                      | 14        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                      | 14        | 0.53%   |
| SanDisk NVMe SSD Drive 500GB                         | 13        | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB                         | 13        | 0.49%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 13        | 0.49%   |
| HGST HTS721010A9E630 1TB                             | 13        | 0.49%   |
| Crucial CT240BX500SSD1 240GB                         | 13        | 0.49%   |
| Toshiba MQ01ABD100 1TB                               | 12        | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 12        | 0.45%   |
| Crucial CT1000BX500SSD1 1TB                          | 12        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 11        | 0.41%   |
| Unknown MMC Card  64GB                               | 11        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB                       | 11        | 0.41%   |
| Seagate Expansion 1TB                                | 11        | 0.41%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 11        | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                         | 11        | 0.41%   |
| Phison E12 NVMe Controller 2TB                       | 11        | 0.41%   |
| Crucial CT500MX500SSD1 500GB                         | 11        | 0.41%   |
| Samsung SSD 980 PRO 1TB                              | 10        | 0.38%   |
| Samsung NVMe SSD Drive 250GB                         | 10        | 0.38%   |
| Samsung NVMe SSD Drive 1024GB                        | 10        | 0.38%   |
| Kingston NVMe SSD Drive 512GB                        | 10        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 251       | 337    | 38.2%   |
| WDC                 | 197       | 263    | 29.98%  |
| Toshiba             | 85        | 96     | 12.94%  |
| HGST                | 38        | 41     | 5.78%   |
| Hitachi             | 36        | 49     | 5.48%   |
| Samsung Electronics | 19        | 24     | 2.89%   |
| Apple               | 12        | 12     | 1.83%   |
| Unknown             | 6         | 10     | 0.91%   |
| Fujitsu             | 4         | 5      | 0.61%   |
| Maxtor              | 2         | 2      | 0.3%    |
| JMicron Technology  | 2         | 7      | 0.3%    |
| ASMT                | 2         | 3      | 0.3%    |
| Intenso             | 1         | 1      | 0.15%   |
| HGST HDN            | 1         | 1      | 0.15%   |
| Asm                 | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 175       | 228    | 22.32%  |
| Crucial             | 97        | 129    | 12.37%  |
| Kingston            | 95        | 106    | 12.12%  |
| SanDisk             | 67        | 76     | 8.55%   |
| WDC                 | 52        | 61     | 6.63%   |
| Apple               | 29        | 31     | 3.7%    |
| A-DATA Technology   | 25        | 27     | 3.19%   |
| PNY                 | 24        | 32     | 3.06%   |
| China               | 19        | 23     | 2.42%   |
| Intel               | 17        | 17     | 2.17%   |
| Toshiba             | 12        | 12     | 1.53%   |
| SPCC                | 12        | 13     | 1.53%   |
| SK hynix            | 12        | 14     | 1.53%   |
| Netac               | 12        | 13     | 1.53%   |
| Micron Technology   | 10        | 10     | 1.28%   |
| Patriot             | 8         | 9      | 1.02%   |
| LITEON              | 8         | 10     | 1.02%   |
| OCZ                 | 7         | 9      | 0.89%   |
| KingSpec            | 7         | 8      | 0.89%   |
| LITEONIT            | 6         | 9      | 0.77%   |
| Intenso             | 6         | 6      | 0.77%   |
| Team                | 5         | 7      | 0.64%   |
| Lexar               | 4         | 4      | 0.51%   |
| MyDigitalSSD        | 3         | 3      | 0.38%   |
| KingDian            | 3         | 4      | 0.38%   |
| JMicron Technology  | 3         | 3      | 0.38%   |
| Hewlett-Packard     | 3         | 3      | 0.38%   |
| GOODRAM             | 3         | 3      | 0.38%   |
| Apacer              | 3         | 5      | 0.38%   |
| Transcend           | 2         | 3      | 0.26%   |
| Seagate             | 2         | 2      | 0.26%   |
| PNY USB             | 2         | 2      | 0.26%   |
| Mushkin             | 2         | 3      | 0.26%   |
| FORESEE             | 2         | 3      | 0.26%   |
| Corsair             | 2         | 3      | 0.26%   |
| BAITITON            | 2         | 2      | 0.26%   |
| AFOX                | 2         | 2      | 0.26%   |
| Unknown             | 2         | 2      | 0.26%   |
| Yeyian              | 1         | 1      | 0.13%   |
| W800S               | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 792       | 1088   | 36.97%  |
| SSD     | 688       | 939    | 32.12%  |
| HDD     | 557       | 852    | 26%     |
| MMC     | 53        | 61     | 2.47%   |
| Unknown | 52        | 75     | 2.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1002      | 1730   | 51.62%  |
| NVMe | 791       | 1081   | 40.75%  |
| SAS  | 95        | 143    | 4.89%   |
| MMC  | 53        | 61     | 2.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 686       | 944    | 52.13%  |
| 0.51-1.0   | 418       | 546    | 31.76%  |
| 1.01-2.0   | 123       | 159    | 9.35%   |
| 3.01-4.0   | 35        | 50     | 2.66%   |
| 4.01-10.0  | 29        | 50     | 2.2%    |
| 2.01-3.0   | 21        | 30     | 1.6%    |
| 10.01-20.0 | 4         | 12     | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 454       | 28.36%  |
| 251-500        | 404       | 25.23%  |
| 501-1000       | 338       | 21.11%  |
| 1001-2000      | 158       | 9.87%   |
| More than 3000 | 78        | 4.87%   |
| 2001-3000      | 56        | 3.5%    |
| 51-100         | 40        | 2.5%    |
| 1-20           | 32        | 2%      |
| 21-50          | 31        | 1.94%   |
| Unknown        | 10        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 495       | 29.96%  |
| 21-50          | 355       | 21.49%  |
| 101-250        | 258       | 15.62%  |
| 51-100         | 206       | 12.47%  |
| 251-500        | 151       | 9.14%   |
| 501-1000       | 85        | 5.15%   |
| 1001-2000      | 50        | 3.03%   |
| More than 3000 | 29        | 1.76%   |
| 2001-3000      | 13        | 0.79%   |
| Unknown        | 10        | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                          | 3         | 4      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2      | 4.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1      | 2.22%   |
| WDC WD60EFRX-68L0BN1 6TB                            | 1         | 1      | 2.22%   |
| WDC WD5001AALS-00J7B1 500GB                         | 1         | 1      | 2.22%   |
| WDC WD5000AADS-00S9B0 500GB                         | 1         | 1      | 2.22%   |
| WDC WD20EFRX-68AX9N0 2TB                            | 1         | 3      | 2.22%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 2.22%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 1         | 1      | 2.22%   |
| WDC WD1001FALS-00E8B0 1TB                           | 1         | 1      | 2.22%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 1      | 2.22%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 2.22%   |
| Team TM8FP4004T 4TB                                 | 1         | 1      | 2.22%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB               | 1         | 1      | 2.22%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 1      | 2.22%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.22%   |
| Seagate ST500LM030-2E717D 500GB                     | 1         | 1      | 2.22%   |
| Seagate ST5000LM000-2AN170 5TB                      | 1         | 1      | 2.22%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 2.22%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1         | 1      | 2.22%   |
| Seagate ST2000DM006-2DM164 2TB                      | 1         | 1      | 2.22%   |
| Seagate ST1000LX015-1U7172 1TB                      | 1         | 1      | 2.22%   |
| Seagate Expansion Desk 8TB                          | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 850 PRO 256GB               | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 850 EVO 500GB               | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 850 EVO 250GB               | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 840 PRO Series 512GB        | 1         | 1      | 2.22%   |
| Samsung Electronics HD103SI 1TB                     | 1         | 1      | 2.22%   |
| SABRENT Disk 500GB                                  | 1         | 1      | 2.22%   |
| Plextor PX-128M6M 128GB SSD                         | 1         | 1      | 2.22%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 2.22%   |
| Lexar 1TB SSD                                       | 1         | 1      | 2.22%   |
| Leven JAJS600M256C 256GB                            | 1         | 1      | 2.22%   |
| Kingston SV300S37A240G 240GB SSD                    | 1         | 1      | 2.22%   |
| Intel SSDSCKKF240H6L 240GB                          | 1         | 1      | 2.22%   |
| Intel SSDPEKNW010T8 1TB                             | 1         | 1      | 2.22%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 3      | 2.22%   |
| Hitachi HDP725050GLA360 500GB                       | 1         | 1      | 2.22%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.22%   |
| Crucial CT525MX300SSD1 528GB                        | 1         | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 20.45%  |
| WDC                 | 8         | 10     | 18.18%  |
| Samsung Electronics | 5         | 5      | 11.36%  |
| HGST                | 4         | 5      | 9.09%   |
| Toshiba             | 2         | 2      | 4.55%   |
| SK hynix            | 2         | 2      | 4.55%   |
| Intel               | 2         | 2      | 4.55%   |
| Hitachi             | 2         | 4      | 4.55%   |
| Team                | 1         | 1      | 2.27%   |
| SABRENT             | 1         | 1      | 2.27%   |
| Plextor             | 1         | 1      | 2.27%   |
| Micron Technology   | 1         | 1      | 2.27%   |
| Lexar               | 1         | 1      | 2.27%   |
| Leven               | 1         | 1      | 2.27%   |
| Kingston            | 1         | 1      | 2.27%   |
| Crucial             | 1         | 1      | 2.27%   |
| BAITITON            | 1         | 1      | 2.27%   |
| A-DATA Technology   | 1         | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 37.5%   |
| WDC                 | 7         | 9      | 29.17%  |
| HGST                | 4         | 5      | 16.67%  |
| Hitachi             | 2         | 4      | 8.33%   |
| Toshiba             | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 30     | 54.55%  |
| SSD  | 14        | 14     | 31.82%  |
| NVMe | 6         | 6      | 13.64%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1223      | 2356   | 73.45%  |
| Works    | 400       | 608    | 24.02%  |
| Malfunc  | 41        | 50     | 2.46%   |
| Failed   | 1         | 1      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 892       | 39.75%  |
| AMD                            | 391       | 17.42%  |
| Samsung Electronics            | 314       | 13.99%  |
| SanDisk                        | 147       | 6.55%   |
| SK hynix                       | 74        | 3.3%    |
| Phison Electronics             | 66        | 2.94%   |
| Micron Technology              | 45        | 2.01%   |
| Micron/Crucial Technology      | 35        | 1.56%   |
| Kingston Technology Company    | 35        | 1.56%   |
| Toshiba America Info Systems   | 31        | 1.38%   |
| ASMedia Technology             | 31        | 1.38%   |
| Nvidia                         | 28        | 1.25%   |
| Silicon Motion                 | 27        | 1.2%    |
| Marvell Technology Group       | 21        | 0.94%   |
| KIOXIA                         | 19        | 0.85%   |
| ADATA Technology               | 19        | 0.85%   |
| Solid State Storage Technology | 9         | 0.4%    |
| Union Memory (Shenzhen)        | 8         | 0.36%   |
| Realtek Semiconductor          | 8         | 0.36%   |
| Seagate Technology             | 7         | 0.31%   |
| JMicron Technology             | 6         | 0.27%   |
| Apple                          | 5         | 0.22%   |
| Shenzhen Longsys Electronics   | 4         | 0.18%   |
| LSI Logic / Symbios Logic      | 4         | 0.18%   |
| INNOGRIT                       | 4         | 0.18%   |
| Lite-On Technology             | 3         | 0.13%   |
| Broadcom / LSI                 | 3         | 0.13%   |
| Silicon Image                  | 2         | 0.09%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.09%   |
| Yangtze Memory Technologies    | 1         | 0.04%   |
| VIA Technologies               | 1         | 0.04%   |
| O2 Micro                       | 1         | 0.04%   |
| Hewlett-Packard                | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 289       | 11.67%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 139       | 5.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 71        | 2.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 68        | 2.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 65        | 2.63%   |
| Samsung NVMe SSD Controller 980                                                | 64        | 2.58%   |
| Intel Volume Management Device NVMe RAID Controller                            | 61        | 2.46%   |
| AMD 500 Series Chipset SATA Controller                                         | 58        | 2.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 55        | 2.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 55        | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 49        | 1.98%   |
| Micron Non-Volatile memory controller                                          | 44        | 1.78%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 41        | 1.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 41        | 1.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 38        | 1.53%   |
| Phison E12 NVMe Controller                                                     | 35        | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 33        | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 33        | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 33        | 1.33%   |
| SanDisk Non-Volatile memory controller                                         | 32        | 1.29%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 30        | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 29        | 1.17%   |
| Intel SSD 660P Series                                                          | 27        | 1.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 26        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 26        | 1.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 25        | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 23        | 0.93%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 21        | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 20        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 20        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 20        | 0.81%   |
| Kingston Company Company Non-Volatile memory controller                        | 19        | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 19        | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 19        | 0.77%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 18        | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 18        | 0.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 18        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 18        | 0.73%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 17        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1133      | 52.07%  |
| NVMe | 789       | 36.26%  |
| RAID | 147       | 6.76%   |
| IDE  | 100       | 4.6%    |
| SAS  | 7         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1066      | 67.94%  |
| AMD    | 502       | 31.99%  |
| ARM    | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 28        | 1.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 27        | 1.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 24        | 1.53%   |
| AMD Ryzen 5 3600 6-Core Processor             | 23        | 1.46%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 21        | 1.34%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 20        | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 17        | 1.08%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 17        | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 16        | 1.02%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 16        | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 15        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 0.95%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 15        | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 14        | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 0.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 0.89%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 0.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 0.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.76%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 12        | 0.76%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 12        | 0.76%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 12        | 0.76%   |
| Intel 12th Gen Core i7-12700H                 | 11        | 0.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 11        | 0.7%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 10        | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 10        | 0.64%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.57%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 9         | 0.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 9         | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 8         | 0.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.51%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 8         | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.51%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 8         | 0.51%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 8         | 0.51%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 7         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 344       | 21.91%  |
| Intel Core i5           | 310       | 19.75%  |
| Other                   | 181       | 11.53%  |
| AMD Ryzen 5             | 166       | 10.57%  |
| AMD Ryzen 7             | 144       | 9.17%   |
| Intel Core i3           | 69        | 4.39%   |
| AMD Ryzen 9             | 59        | 3.76%   |
| Intel Core 2 Duo        | 39        | 2.48%   |
| Intel Celeron           | 39        | 2.48%   |
| Intel Xeon              | 26        | 1.66%   |
| AMD Ryzen 3             | 21        | 1.34%   |
| AMD FX                  | 17        | 1.08%   |
| Intel Pentium           | 16        | 1.02%   |
| Intel Core i9           | 15        | 0.96%   |
| AMD A8                  | 12        | 0.76%   |
| AMD A10                 | 10        | 0.64%   |
| AMD A6                  | 9         | 0.57%   |
| AMD Ryzen 7 PRO         | 8         | 0.51%   |
| Intel Core 2 Quad       | 7         | 0.45%   |
| AMD Ryzen Threadripper  | 7         | 0.45%   |
| Intel Pentium Gold      | 6         | 0.38%   |
| Intel Pentium Dual-Core | 6         | 0.38%   |
| AMD A4                  | 6         | 0.38%   |
| AMD Ryzen 5 PRO         | 5         | 0.32%   |
| AMD Athlon              | 4         | 0.25%   |
| Intel Core 2            | 3         | 0.19%   |
| Intel Atom              | 3         | 0.19%   |
| AMD Ryzen 3 PRO         | 3         | 0.19%   |
| AMD Phenom              | 3         | 0.19%   |
| Intel Pentium Silver    | 2         | 0.13%   |
| Intel Pentium Dual      | 2         | 0.13%   |
| Intel Pentium D         | 2         | 0.13%   |
| Intel Core m5           | 2         | 0.13%   |
| AMD Phenom II X6        | 2         | 0.13%   |
| AMD Phenom II X4        | 2         | 0.13%   |
| AMD Athlon II X4        | 2         | 0.13%   |
| AMD Athlon II X2        | 2         | 0.13%   |
| Intel Xeon Gold         | 1         | 0.06%   |
| Intel Genuine           | 1         | 0.06%   |
| Intel Core m3           | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 549       | 34.97%  |
| 2       | 428       | 27.26%  |
| 6       | 232       | 14.78%  |
| 8       | 229       | 14.59%  |
| 12      | 43        | 2.74%   |
| 16      | 26        | 1.66%   |
| 14      | 23        | 1.46%   |
| 10      | 16        | 1.02%   |
| 3       | 8         | 0.51%   |
| 1       | 7         | 0.45%   |
| 24      | 3         | 0.19%   |
| 32      | 2         | 0.13%   |
| 64      | 1         | 0.06%   |
| 40      | 1         | 0.06%   |
| 18      | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1563      | 99.62%  |
| 2       | 5         | 0.32%   |
| Unknown | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1284      | 81.84%  |
| 1       | 284       | 18.1%   |
| Unknown | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1568      | 99.94%  |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1170      | 73.77%  |
| 0x806c1    | 34        | 2.14%   |
| 0x0a50000c | 24        | 1.51%   |
| 0x806ec    | 21        | 1.32%   |
| 0x806d1    | 20        | 1.26%   |
| 0x306a9    | 18        | 1.13%   |
| 0x906a3    | 16        | 1.01%   |
| 0x906ea    | 14        | 0.88%   |
| 0x806ea    | 14        | 0.88%   |
| 0xa0652    | 13        | 0.82%   |
| 0x08701021 | 13        | 0.82%   |
| 0x08608103 | 11        | 0.69%   |
| 0x906e9    | 10        | 0.63%   |
| 0x506e3    | 10        | 0.63%   |
| 0x406e3    | 10        | 0.63%   |
| 0x40651    | 10        | 0.63%   |
| 0x206a7    | 10        | 0.63%   |
| 0x0a404101 | 10        | 0.63%   |
| 0x08600106 | 9         | 0.57%   |
| 0x08108109 | 9         | 0.57%   |
| 0x806e9    | 8         | 0.5%    |
| 0x306c3    | 8         | 0.5%    |
| 0x08600104 | 8         | 0.5%    |
| 0x706e5    | 7         | 0.44%   |
| 0x0a201016 | 7         | 0.44%   |
| 0x0800820d | 7         | 0.44%   |
| 0x906a4    | 6         | 0.38%   |
| 0x306d4    | 6         | 0.38%   |
| 0x906ec    | 5         | 0.32%   |
| 0x706a8    | 5         | 0.32%   |
| 0x90672    | 4         | 0.25%   |
| 0x806eb    | 4         | 0.25%   |
| 0x1067a    | 4         | 0.25%   |
| 0x08701013 | 4         | 0.25%   |
| 0x906ed    | 3         | 0.19%   |
| 0x806c2    | 3         | 0.19%   |
| 0x08600103 | 3         | 0.19%   |
| 0x0810100b | 3         | 0.19%   |
| 0x08001138 | 3         | 0.19%   |
| 0x06003106 | 3         | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 248       | 15.79%  |
| Zen 3            | 147       | 9.36%   |
| Haswell          | 135       | 8.59%   |
| Unknown          | 125       | 7.96%   |
| Zen 2            | 111       | 7.07%   |
| IvyBridge        | 91        | 5.79%   |
| Skylake          | 83        | 5.28%   |
| TigerLake        | 75        | 4.77%   |
| SandyBridge      | 74        | 4.71%   |
| Zen+             | 71        | 4.52%   |
| CometLake        | 50        | 3.18%   |
| Penryn           | 49        | 3.12%   |
| Broadwell        | 43        | 2.74%   |
| IceLake          | 39        | 2.48%   |
| Zen              | 30        | 1.91%   |
| Westmere         | 30        | 1.91%   |
| Piledriver       | 27        | 1.72%   |
| Alderlake Hybrid | 24        | 1.53%   |
| Silvermont       | 18        | 1.15%   |
| Nehalem          | 15        | 0.95%   |
| Goldmont plus    | 15        | 0.95%   |
| Excavator        | 15        | 0.95%   |
| K10              | 14        | 0.89%   |
| Core             | 9         | 0.57%   |
| Puma             | 8         | 0.51%   |
| Steamroller      | 7         | 0.45%   |
| K10 Llano        | 6         | 0.38%   |
| Goldmont         | 4         | 0.25%   |
| K8 Hammer        | 3         | 0.19%   |
| NetBurst         | 2         | 0.13%   |
| Tremont          | 1         | 0.06%   |
| Jaguar           | 1         | 0.06%   |
| Bobcat           | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 815       | 42.45%  |
| Nvidia                     | 624       | 32.5%   |
| AMD                        | 478       | 24.9%   |
| Matrox Electronics Systems | 3         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 69        | 3.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 58        | 2.96%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 54        | 2.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 52        | 2.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 49        | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 47        | 2.4%    |
| AMD Renoir                                                                  | 42        | 2.14%   |
| Intel UHD Graphics 620                                                      | 38        | 1.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 38        | 1.94%   |
| AMD Lucienne                                                                | 36        | 1.84%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 34        | 1.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 33        | 1.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 33        | 1.68%   |
| Intel HD Graphics 620                                                       | 32        | 1.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 30        | 1.53%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 27        | 1.38%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 26        | 1.33%   |
| Intel HD Graphics 5500                                                      | 26        | 1.33%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 25        | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 24        | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 23        | 1.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 23        | 1.17%   |
| Intel HD Graphics 630                                                       | 22        | 1.12%   |
| Intel HD Graphics 530                                                       | 20        | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                         | 20        | 1.02%   |
| AMD Rembrandt [Radeon 680M]                                                 | 18        | 0.92%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 18        | 0.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 17        | 0.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 17        | 0.87%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 17        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 16        | 0.82%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 15        | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 14        | 0.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 14        | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 14        | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 13        | 0.66%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 13        | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 12        | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 12        | 0.61%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 12        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 538       | 34.05%  |
| 1 x AMD              | 357       | 22.59%  |
| 1 x Nvidia           | 319       | 20.19%  |
| Intel + Nvidia       | 229       | 14.49%  |
| AMD + Nvidia         | 65        | 4.11%   |
| Intel + AMD          | 30        | 1.9%    |
| 2 x AMD              | 26        | 1.65%   |
| 2 x Nvidia           | 8         | 0.51%   |
| 1 x Matrox           | 3         | 0.19%   |
| Other                | 2         | 0.13%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.06%   |
| Intel + 2 x Nvidia   | 1         | 0.06%   |
| AMD + 2 x Nvidia     | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1028      | 65.02%  |
| Proprietary | 512       | 32.38%  |
| Unknown     | 41        | 2.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1246      | 78.46%  |
| 7.01-8.0   | 71        | 4.47%   |
| 1.01-2.0   | 62        | 3.9%    |
| 3.01-4.0   | 54        | 3.4%    |
| 5.01-6.0   | 47        | 2.96%   |
| 0.01-0.5   | 47        | 2.96%   |
| 8.01-16.0  | 35        | 2.2%    |
| 0.51-1.0   | 13        | 0.82%   |
| 2.01-3.0   | 10        | 0.63%   |
| 16.01-24.0 | 2         | 0.13%   |
| 32.01-64.0 | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 235       | 12.93%  |
| Samsung Electronics     | 210       | 11.55%  |
| BOE                     | 175       | 9.63%   |
| Chimei Innolux          | 161       | 8.86%   |
| LG Display              | 157       | 8.64%   |
| Goldstar                | 120       | 6.6%    |
| Dell                    | 109       | 6%      |
| Apple                   | 63        | 3.47%   |
| Hewlett-Packard         | 55        | 3.03%   |
| Acer                    | 48        | 2.64%   |
| Sharp                   | 44        | 2.42%   |
| AOC                     | 42        | 2.31%   |
| ASUSTek Computer        | 39        | 2.15%   |
| Ancor Communications    | 37        | 2.04%   |
| BenQ                    | 32        | 1.76%   |
| PANDA                   | 28        | 1.54%   |
| Lenovo                  | 27        | 1.49%   |
| Philips                 | 18        | 0.99%   |
| MSI                     | 14        | 0.77%   |
| InfoVision              | 13        | 0.72%   |
| Iiyama                  | 12        | 0.66%   |
| CSO                     | 12        | 0.66%   |
| ViewSonic               | 10        | 0.55%   |
| Sony                    | 9         | 0.5%    |
| Sceptre Tech            | 8         | 0.44%   |
| Chi Mei Optoelectronics | 8         | 0.44%   |
| Gigabyte Technology     | 7         | 0.39%   |
| Vizio                   | 6         | 0.33%   |
| Unknown                 | 6         | 0.33%   |
| Panasonic               | 6         | 0.33%   |
| NEC Computers           | 6         | 0.33%   |
| Vestel Elektronik       | 4         | 0.22%   |
| TMX                     | 4         | 0.22%   |
| Viotek                  | 3         | 0.17%   |
| Valve                   | 3         | 0.17%   |
| Toshiba                 | 3         | 0.17%   |
| Pioneer                 | 3         | 0.17%   |
| LG Electronics          | 3         | 0.17%   |
| Eizo                    | 3         | 0.17%   |
| ___                     | 2         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 13        | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 12        | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 10        | 0.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 9         | 0.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 9         | 0.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 9         | 0.48%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 8         | 0.43%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch         | 8         | 0.43%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                   | 8         | 0.43%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 7         | 0.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 7         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 7         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 6         | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 5         | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch       | 5         | 0.27%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                  | 5         | 0.27%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                  | 5         | 0.27%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                  | 5         | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch         | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch          | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch         | 5         | 0.27%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 5         | 0.27%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 4         | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 4         | 0.21%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 4         | 0.21%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch  | 4         | 0.21%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 4         | 0.21%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 4         | 0.21%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch            | 4         | 0.21%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 4         | 0.21%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 4         | 0.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 4         | 0.21%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch               | 4         | 0.21%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 4         | 0.21%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch            | 4         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 836       | 48.86%  |
| 1366x768 (WXGA)    | 244       | 14.26%  |
| 3840x2160 (4K)     | 138       | 8.07%   |
| 2560x1440 (QHD)    | 103       | 6.02%   |
| 1920x1200 (WUXGA)  | 53        | 3.1%    |
| 1600x900 (HD+)     | 53        | 3.1%    |
| 3440x1440          | 38        | 2.22%   |
| 2560x1080          | 31        | 1.81%   |
| 1440x900 (WXGA+)   | 29        | 1.69%   |
| 2560x1600          | 27        | 1.58%   |
| 1680x1050 (WSXGA+) | 20        | 1.17%   |
| 2880x1800          | 19        | 1.11%   |
| 1280x1024 (SXGA)   | 19        | 1.11%   |
| 1280x800 (WXGA)    | 17        | 0.99%   |
| 3840x1080          | 9         | 0.53%   |
| 1360x768           | 9         | 0.53%   |
| 1920x540           | 8         | 0.47%   |
| 2160x1440          | 6         | 0.35%   |
| 3840x2400          | 5         | 0.29%   |
| 2256x1504          | 5         | 0.29%   |
| 3840x1600          | 4         | 0.23%   |
| 3456x2160          | 4         | 0.23%   |
| Unknown            | 4         | 0.23%   |
| 3000x2000          | 3         | 0.18%   |
| 1280x720 (HD)      | 3         | 0.18%   |
| 1024x768 (XGA)     | 3         | 0.18%   |
| 800x1280           | 2         | 0.12%   |
| 3840x1100          | 2         | 0.12%   |
| 3200x2000          | 2         | 0.12%   |
| 2736x1824          | 2         | 0.12%   |
| 1920x1280          | 2         | 0.12%   |
| 3840x1200          | 1         | 0.06%   |
| 3280x1080          | 1         | 0.06%   |
| 3200x1800 (QHD+)   | 1         | 0.06%   |
| 3120x2080          | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |
| 3040x900           | 1         | 0.06%   |
| 2880x1600          | 1         | 0.06%   |
| 1920x515           | 1         | 0.06%   |
| 1600x1200          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 470       | 25.95%  |
| 13      | 222       | 12.26%  |
| 27      | 148       | 8.17%   |
| 24      | 138       | 7.62%   |
| 14      | 136       | 7.51%   |
| 23      | 108       | 5.96%   |
| 17      | 86        | 4.75%   |
| 21      | 76        | 4.2%    |
| 31      | 69        | 3.81%   |
| 34      | 62        | 3.42%   |
| Unknown | 32        | 1.77%   |
| 12      | 28        | 1.55%   |
| 16      | 23        | 1.27%   |
| 32      | 22        | 1.21%   |
| 18      | 22        | 1.21%   |
| 19      | 20        | 1.1%    |
| 22      | 17        | 0.94%   |
| 84      | 13        | 0.72%   |
| 72      | 12        | 0.66%   |
| 20      | 12        | 0.66%   |
| 11      | 12        | 0.66%   |
| 48      | 10        | 0.55%   |
| 28      | 7         | 0.39%   |
| 25      | 7         | 0.39%   |
| 54      | 6         | 0.33%   |
| 37      | 6         | 0.33%   |
| 35      | 5         | 0.28%   |
| 26      | 5         | 0.28%   |
| 47      | 4         | 0.22%   |
| 49      | 3         | 0.17%   |
| 46      | 3         | 0.17%   |
| 40      | 3         | 0.17%   |
| 29      | 3         | 0.17%   |
| 75      | 2         | 0.11%   |
| 65      | 2         | 0.11%   |
| 52      | 2         | 0.11%   |
| 44      | 2         | 0.11%   |
| 42      | 2         | 0.11%   |
| 33      | 2         | 0.11%   |
| 89      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 736       | 41.39%  |
| 501-600     | 356       | 20.02%  |
| 201-300     | 154       | 8.66%   |
| 401-500     | 135       | 7.59%   |
| 601-700     | 103       | 5.79%   |
| 351-400     | 94        | 5.29%   |
| 701-800     | 85        | 4.78%   |
| 1001-1500   | 33        | 1.86%   |
| Unknown     | 32        | 1.8%    |
| 1501-2000   | 29        | 1.63%   |
| 801-900     | 16        | 0.9%    |
| 901-1000    | 4         | 0.22%   |
| 1-100       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1273      | 79.12%  |
| 16/10   | 185       | 11.5%   |
| 21/9    | 75        | 4.66%   |
| 5/4     | 19        | 1.18%   |
| 3/2     | 18        | 1.12%   |
| Unknown | 14        | 0.87%   |
| 32/9    | 12        | 0.75%   |
| 4/3     | 6         | 0.37%   |
| 3.40    | 2         | 0.12%   |
| 6/5     | 1         | 0.06%   |
| 3.73    | 1         | 0.06%   |
| 3.20    | 1         | 0.06%   |
| 0.67    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 470       | 26.3%   |
| 81-90          | 274       | 15.33%  |
| 201-250        | 265       | 14.83%  |
| 351-500        | 163       | 9.12%   |
| 301-350        | 153       | 8.56%   |
| 71-80          | 82        | 4.59%   |
| 121-130        | 71        | 3.97%   |
| 151-200        | 54        | 3.02%   |
| 251-300        | 48        | 2.69%   |
| More than 1000 | 44        | 2.46%   |
| Unknown        | 32        | 1.79%   |
| 141-150        | 31        | 1.73%   |
| 501-1000       | 31        | 1.73%   |
| 61-70          | 25        | 1.4%    |
| 111-120        | 20        | 1.12%   |
| 51-60          | 14        | 0.78%   |
| 91-100         | 5         | 0.28%   |
| 131-140        | 4         | 0.22%   |
| 1-40           | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 572       | 33.06%  |
| 51-100        | 490       | 28.32%  |
| 101-120       | 400       | 23.12%  |
| 161-240       | 144       | 8.32%   |
| More than 240 | 52        | 3.01%   |
| 1-50          | 40        | 2.31%   |
| Unknown       | 32        | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1203      | 75.66%  |
| 2     | 286       | 17.99%  |
| 0     | 53        | 3.33%   |
| 3     | 43        | 2.7%    |
| 4     | 4         | 0.25%   |
| 6     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 845       | 35.08%  |
| Intel                             | 832       | 34.54%  |
| Qualcomm Atheros                  | 246       | 10.21%  |
| Broadcom                          | 127       | 5.27%   |
| MediaTek                          | 65        | 2.7%    |
| Broadcom Limited                  | 44        | 1.83%   |
| TP-Link                           | 25        | 1.04%   |
| Nvidia                            | 20        | 0.83%   |
| Marvell Technology Group          | 18        | 0.75%   |
| Samsung Electronics               | 15        | 0.62%   |
| Ralink Technology                 | 14        | 0.58%   |
| ASIX Electronics                  | 14        | 0.58%   |
| NetGear                           | 13        | 0.54%   |
| DisplayLink                       | 12        | 0.5%    |
| Ralink                            | 11        | 0.46%   |
| Aquantia                          | 8         | 0.33%   |
| Xiaomi                            | 7         | 0.29%   |
| Microsoft                         | 7         | 0.29%   |
| Dell                              | 7         | 0.29%   |
| InterBiometrics                   | 6         | 0.25%   |
| D-Link                            | 6         | 0.25%   |
| Sierra Wireless                   | 5         | 0.21%   |
| ASUSTek Computer                  | 5         | 0.21%   |
| Qualcomm Atheros Communications   | 4         | 0.17%   |
| Qualcomm                          | 4         | 0.17%   |
| Lenovo                            | 4         | 0.17%   |
| Huawei Technologies               | 4         | 0.17%   |
| OPPO Electronics                  | 3         | 0.12%   |
| JMicron Technology                | 3         | 0.12%   |
| Hewlett-Packard                   | 3         | 0.12%   |
| Google                            | 3         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.08%   |
| Mellanox Technologies             | 2         | 0.08%   |
| Ericsson Business Mobile Networks | 2         | 0.08%   |
| D-Link System                     | 2         | 0.08%   |
| Apple                             | 2         | 0.08%   |
| Accton Technology                 | 2         | 0.08%   |
| U-Blox                            | 1         | 0.04%   |
| STMicroelectronics                | 1         | 0.04%   |
| Sitecom Europe                    | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 548       | 19.4%   |
| Intel Wi-Fi 6 AX200                                               | 135       | 4.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 74        | 2.62%   |
| Intel I211 Gigabit Network Connection                             | 72        | 2.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 64        | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 61        | 2.16%   |
| Intel Wi-Fi 6 AX201                                               | 55        | 1.95%   |
| Intel Wireless 8265 / 8275                                        | 49        | 1.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 47        | 1.66%   |
| Intel Ethernet Controller I225-V                                  | 45        | 1.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 40        | 1.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 38        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 37        | 1.31%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 37        | 1.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 35        | 1.24%   |
| Intel Wireless 7265                                               | 35        | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 35        | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 33        | 1.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 33        | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 30        | 1.06%   |
| Intel Wireless 8260                                               | 29        | 1.03%   |
| Intel Wireless 7260                                               | 28        | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 27        | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 26        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 25        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 25        | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 25        | 0.88%   |
| Intel Wireless-AC 9260                                            | 24        | 0.85%   |
| Intel Ethernet Connection (2) I219-V                              | 22        | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 20        | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 20        | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 20        | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 19        | 0.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 19        | 0.67%   |
| Realtek 802.11ac NIC                                              | 16        | 0.57%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 15        | 0.53%   |
| Broadcom BCM43142 802.11b/g/n                                     | 15        | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 12        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 683       | 48.72%  |
| Realtek Semiconductor                 | 211       | 15.05%  |
| Qualcomm Atheros                      | 194       | 13.84%  |
| Broadcom                              | 98        | 6.99%   |
| MediaTek                              | 64        | 4.56%   |
| Broadcom Limited                      | 37        | 2.64%   |
| TP-Link                               | 21        | 1.5%    |
| Ralink Technology                     | 14        | 1%      |
| NetGear                               | 13        | 0.93%   |
| Ralink                                | 11        | 0.78%   |
| Microsoft                             | 7         | 0.5%    |
| Dell                                  | 7         | 0.5%    |
| Marvell Technology Group              | 6         | 0.43%   |
| Sierra Wireless                       | 5         | 0.36%   |
| D-Link                                | 5         | 0.36%   |
| Qualcomm Atheros Communications       | 4         | 0.29%   |
| ASUSTek Computer                      | 4         | 0.29%   |
| Qualcomm                              | 3         | 0.21%   |
| Hewlett-Packard                       | 2         | 0.14%   |
| D-Link System                         | 2         | 0.14%   |
| Accton Technology                     | 2         | 0.14%   |
| Sitecom Europe                        | 1         | 0.07%   |
| Micro Star International              | 1         | 0.07%   |
| IMC Networks                          | 1         | 0.07%   |
| Gemtek                                | 1         | 0.07%   |
| Fibocom                               | 1         | 0.07%   |
| Belkin Components                     | 1         | 0.07%   |
| AVM                                   | 1         | 0.07%   |
| Arduino SA                            | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 135       | 9.55%   |
| Intel Wi-Fi 6 AX201                                            | 55        | 3.89%   |
| Intel Wireless 8265 / 8275                                     | 49        | 3.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 40        | 2.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 38        | 2.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 37        | 2.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 37        | 2.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 35        | 2.48%   |
| Intel Wireless 7265                                            | 35        | 2.48%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 35        | 2.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 33        | 2.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 33        | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 31        | 2.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 30        | 2.12%   |
| Intel Wireless 8260                                            | 29        | 2.05%   |
| Intel Wireless 7260                                            | 28        | 1.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 27        | 1.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 25        | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 25        | 1.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 25        | 1.77%   |
| Intel Wireless-AC 9260                                         | 24        | 1.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 20        | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 20        | 1.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 20        | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 19        | 1.34%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 19        | 1.34%   |
| Realtek 802.11ac NIC                                           | 16        | 1.13%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 15        | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                  | 15        | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 12        | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 12        | 0.85%   |
| Intel Centrino Advanced-N 6235                                 | 12        | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 0.78%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 11        | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 11        | 0.78%   |
| Realtek Realtek Network controller                             | 10        | 0.71%   |
| MediaTek WLAN controller                                       | 10        | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 742       | 54.4%   |
| Intel                         | 376       | 27.57%  |
| Qualcomm Atheros              | 68        | 4.99%   |
| Broadcom                      | 53        | 3.89%   |
| Nvidia                        | 20        | 1.47%   |
| Samsung Electronics           | 15        | 1.1%    |
| ASIX Electronics              | 14        | 1.03%   |
| Marvell Technology Group      | 12        | 0.88%   |
| DisplayLink                   | 12        | 0.88%   |
| Aquantia                      | 8         | 0.59%   |
| Xiaomi                        | 7         | 0.51%   |
| Broadcom Limited              | 7         | 0.51%   |
| TP-Link                       | 4         | 0.29%   |
| Lenovo                        | 4         | 0.29%   |
| OPPO Electronics              | 3         | 0.22%   |
| JMicron Technology            | 3         | 0.22%   |
| Huawei Technologies           | 3         | 0.22%   |
| Google                        | 3         | 0.22%   |
| OnePlus Technology (Shenzhen) | 2         | 0.15%   |
| Mellanox Technologies         | 2         | 0.15%   |
| Apple                         | 2         | 0.15%   |
| Qualcomm                      | 1         | 0.07%   |
| Motorola PCS                  | 1         | 0.07%   |
| D-Link                        | 1         | 0.07%   |
| ASUSTek Computer              | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 548       | 39.4%   |
| Realtek RTL8125 2.5GbE Controller                                 | 74        | 5.32%   |
| Intel I211 Gigabit Network Connection                             | 72        | 5.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 64        | 4.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 61        | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 47        | 3.38%   |
| Intel Ethernet Controller I225-V                                  | 45        | 3.24%   |
| Intel Ethernet Connection I217-LM                                 | 26        | 1.87%   |
| Intel Ethernet Connection (2) I219-V                              | 22        | 1.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.86%   |
| Nvidia MCP79 Ethernet                                             | 12        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.65%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 0.58%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 8         | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 7         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.43%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.43%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.36%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.36%   |
| DisplayLink Dell Universal Dock D6000                             | 5         | 0.36%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 5         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1330      | 50.71%  |
| Ethernet | 1273      | 48.53%  |
| Modem    | 15        | 0.57%   |
| Unknown  | 5         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1027      | 62.28%  |
| Ethernet | 622       | 37.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 865       | 55.06%  |
| 1     | 639       | 40.67%  |
| 3     | 48        | 3.06%   |
| 0     | 16        | 1.02%   |
| 4     | 3         | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1109      | 70.19%  |
| Yes  | 471       | 29.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 619       | 53.69%  |
| Realtek Semiconductor           | 88        | 7.63%   |
| Qualcomm Atheros Communications | 85        | 7.37%   |
| Apple                           | 75        | 6.5%    |
| IMC Networks                    | 59        | 5.12%   |
| Cambridge Silicon Radio         | 54        | 4.68%   |
| Lite-On Technology              | 37        | 3.21%   |
| Foxconn / Hon Hai               | 34        | 2.95%   |
| Broadcom                        | 30        | 2.6%    |
| ASUSTek Computer                | 14        | 1.21%   |
| Dell                            | 8         | 0.69%   |
| MediaTek                        | 7         | 0.61%   |
| Toshiba                         | 6         | 0.52%   |
| Realtek                         | 6         | 0.52%   |
| Marvell Semiconductor           | 6         | 0.52%   |
| Hewlett-Packard                 | 5         | 0.43%   |
| TP-Link                         | 3         | 0.26%   |
| Taiyo Yuden                     | 2         | 0.17%   |
| Ralink                          | 2         | 0.17%   |
| Opticis                         | 2         | 0.17%   |
| Micro Star International        | 2         | 0.17%   |
| Foxconn International           | 2         | 0.17%   |
| USI                             | 1         | 0.09%   |
| Ralink Technology               | 1         | 0.09%   |
| HTC (High Tech Computer)        | 1         | 0.09%   |
| Fujitsu                         | 1         | 0.09%   |
| Edimax Technology               | 1         | 0.09%   |
| Dynex                           | 1         | 0.09%   |
| Belkin Components               | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 150       | 13%     |
| Intel AX201 Bluetooth                               | 133       | 11.53%  |
| Intel AX200 Bluetooth                               | 127       | 11.01%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 82        | 7.11%   |
| Realtek Bluetooth Radio                             | 67        | 5.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 54        | 4.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 45        | 3.9%    |
| Apple Bluetooth USB Host Controller                 | 34        | 2.95%   |
| Intel Bluetooth Device                              | 33        | 2.86%   |
| Intel AX210 Bluetooth                               | 30        | 2.6%    |
| Apple Bluetooth Host Controller                     | 30        | 2.6%    |
| IMC Networks Wireless_Device                        | 26        | 2.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 24        | 2.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 22        | 1.91%   |
| Realtek  Bluetooth 4.2 Adapter                      | 19        | 1.65%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 14        | 1.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 1.13%   |
| IMC Networks Bluetooth Device                       | 13        | 1.13%   |
| IMC Networks Bluetooth Radio                        | 11        | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 10        | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.69%   |
| Lite-On Wireless_Device                             | 8         | 0.69%   |
| MediaTek Wireless_Device                            | 7         | 0.61%   |
| Lite-On Bluetooth Device                            | 7         | 0.61%   |
| Realtek Bluetooth Radio                             | 6         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 6         | 0.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.43%   |
| Marvell Bluetooth and Wireless LAN Composite        | 5         | 0.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.43%   |
| ASUS ASUS USB-BT500                                 | 5         | 0.43%   |
| Apple Bluetooth HCI                                 | 5         | 0.43%   |
| Lite-On Bluetooth Radio                             | 4         | 0.35%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.35%   |
| ASUS Bluetooth Radio                                | 4         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1029      | 42.75%  |
| AMD                                  | 567       | 23.56%  |
| Nvidia                               | 491       | 20.4%   |
| C-Media Electronics                  | 36        | 1.5%    |
| Logitech                             | 27        | 1.12%   |
| Kingston Technology                  | 18        | 0.75%   |
| Razer USA                            | 15        | 0.62%   |
| JMTek                                | 14        | 0.58%   |
| Focusrite-Novation                   | 13        | 0.54%   |
| GN Netcom                            | 11        | 0.46%   |
| Creative Labs                        | 11        | 0.46%   |
| ASUSTek Computer                     | 11        | 0.46%   |
| Texas Instruments                    | 9         | 0.37%   |
| Generalplus Technology               | 9         | 0.37%   |
| Lenovo                               | 8         | 0.33%   |
| SteelSeries ApS                      | 7         | 0.29%   |
| Blue Microphones                     | 7         | 0.29%   |
| Realtek Semiconductor                | 6         | 0.25%   |
| Micro Star International             | 6         | 0.25%   |
| Corsair                              | 6         | 0.25%   |
| Sony                                 | 5         | 0.21%   |
| Hewlett-Packard                      | 5         | 0.21%   |
| Creative Technology                  | 5         | 0.21%   |
| Apple                                | 5         | 0.21%   |
| Plantronics                          | 4         | 0.17%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.12%   |
| Astro Gaming                         | 3         | 0.12%   |
| Antlion Audio                        | 3         | 0.12%   |
| WL80                                 | 2         | 0.08%   |
| Valve Software                       | 2         | 0.08%   |
| Turtle Beach                         | 2         | 0.08%   |
| Trust                                | 2         | 0.08%   |
| Tenx Technology                      | 2         | 0.08%   |
| Sennheiser Communications            | 2         | 0.08%   |
| SAVITECH                             | 2         | 0.08%   |
| Samsung Electronics                  | 2         | 0.08%   |
| Samson Technologies                  | 2         | 0.08%   |
| Nordic Semiconductor ASA             | 2         | 0.08%   |
| Mackie Designs                       | 2         | 0.08%   |
| M-Audio                              | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 233       | 8.02%   |
| AMD Starship/Matisse HD Audio Controller                                   | 135       | 4.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 134       | 4.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 108       | 3.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 91        | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 75        | 2.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 66        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 66        | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 65        | 2.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 59        | 2.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 55        | 1.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 49        | 1.69%   |
| Intel 8 Series HD Audio Controller                                         | 48        | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 44        | 1.51%   |
| Nvidia GA104 High Definition Audio Controller                              | 42        | 1.45%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 42        | 1.45%   |
| Nvidia GA106 High Definition Audio Controller                              | 41        | 1.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 41        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 41        | 1.41%   |
| Intel Comet Lake PCH cAVS                                                  | 40        | 1.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 40        | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 39        | 1.34%   |
| Intel Broadwell-U Audio Controller                                         | 39        | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 38        | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                              | 37        | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 36        | 1.24%   |
| Nvidia TU106 High Definition Audio Controller                              | 35        | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 33        | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 33        | 1.14%   |
| AMD FCH Azalia Controller                                                  | 33        | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                              | 32        | 1.1%    |
| Nvidia GP104 High Definition Audio Controller                              | 32        | 1.1%    |
| Nvidia TU104 HD Audio Controller                                           | 27        | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 26        | 0.89%   |
| Intel 200 Series PCH HD Audio                                              | 25        | 0.86%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 24        | 0.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 23        | 0.79%   |
| Nvidia GA102 High Definition Audio Controller                              | 22        | 0.76%   |
| Nvidia Audio device                                                        | 21        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 130       | 26.32%  |
| SK hynix                     | 88        | 17.81%  |
| Micron Technology            | 65        | 13.16%  |
| Kingston                     | 36        | 7.29%   |
| Corsair                      | 36        | 7.29%   |
| Crucial                      | 30        | 6.07%   |
| G.Skill                      | 21        | 4.25%   |
| Unknown                      | 13        | 2.63%   |
| Team                         | 12        | 2.43%   |
| Unknown                      | 11        | 2.23%   |
| A-DATA Technology            | 8         | 1.62%   |
| Smart                        | 6         | 1.21%   |
| Neo Forza                    | 5         | 1.01%   |
| Elpida                       | 4         | 0.81%   |
| Ramaxel Technology           | 3         | 0.61%   |
| Goldkey                      | 3         | 0.61%   |
| Avant                        | 3         | 0.61%   |
| Unknown (ABCD)               | 2         | 0.4%    |
| Teikon                       | 2         | 0.4%    |
| PNY                          | 2         | 0.4%    |
| Nanya Technology             | 2         | 0.4%    |
| GSkill                       | 2         | 0.4%    |
| Gold Key                     | 2         | 0.4%    |
| Unknown (8A02)               | 1         | 0.2%    |
| Timetec                      | 1         | 0.2%    |
| Smart Brazil                 | 1         | 0.2%    |
| Patriot Memory (PDP Systems) | 1         | 0.2%    |
| Patriot Memory               | 1         | 0.2%    |
| Patriot                      | 1         | 0.2%    |
| ChangXin Memory              | 1         | 0.2%    |
| Apacer                       | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 12        | 2.31%   |
| Unknown                                                      | 11        | 2.12%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 8         | 1.54%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 7         | 1.35%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 7         | 1.35%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 6         | 1.15%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 6         | 1.15%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 0.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 5         | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 5         | 0.96%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 5         | 0.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s  | 5         | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 5         | 0.96%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 5         | 0.96%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s          | 4         | 0.77%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s         | 4         | 0.77%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 4         | 0.77%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s     | 4         | 0.77%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 4         | 0.77%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 4         | 0.77%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 4         | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 4         | 0.77%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s           | 4         | 0.77%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s         | 4         | 0.77%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s        | 4         | 0.77%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 4         | 0.77%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 4         | 0.77%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 3         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 3         | 0.58%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 3         | 0.58%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 3         | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 3         | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 3         | 0.58%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s     | 3         | 0.58%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.58%   |
| Neo Forza RAM NMSO416E82-3200E 16GB SODIMM DDR4 3200MT/s     | 3         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 3         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 3         | 0.58%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s       | 3         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 291       | 67.99%  |
| DDR3    | 61        | 14.25%  |
| LPDDR4  | 28        | 6.54%   |
| LPDDR3  | 13        | 3.04%   |
| LPDDR5  | 12        | 2.8%    |
| DDR5    | 11        | 2.57%   |
| Unknown | 5         | 1.17%   |
| DDR2    | 4         | 0.93%   |
| SDRAM   | 3         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 273       | 62.47%  |
| DIMM         | 92        | 21.05%  |
| Row Of Chips | 69        | 15.79%  |
| Chip         | 3         | 0.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 214       | 46.52%  |
| 4096  | 101       | 21.96%  |
| 16384 | 89        | 19.35%  |
| 32768 | 31        | 6.74%   |
| 2048  | 24        | 5.22%   |
| 1024  | 1         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 141       | 30.72%  |
| 2667  | 78        | 16.99%  |
| 1600  | 47        | 10.24%  |
| 2400  | 28        | 6.1%    |
| 3600  | 25        | 5.45%   |
| 2133  | 21        | 4.58%   |
| 4267  | 17        | 3.7%    |
| 6400  | 13        | 2.83%   |
| 4800  | 13        | 2.83%   |
| 1333  | 11        | 2.4%    |
| 8400  | 6         | 1.31%   |
| 3800  | 5         | 1.09%   |
| 3733  | 5         | 1.09%   |
| 3266  | 5         | 1.09%   |
| 3466  | 4         | 0.87%   |
| 3000  | 4         | 0.87%   |
| 1867  | 4         | 0.87%   |
| 1334  | 4         | 0.87%   |
| 800   | 4         | 0.87%   |
| 4266  | 3         | 0.65%   |
| 2933  | 3         | 0.65%   |
| 2800  | 2         | 0.44%   |
| 2666  | 2         | 0.44%   |
| 2048  | 2         | 0.44%   |
| 1067  | 2         | 0.44%   |
| 4199  | 1         | 0.22%   |
| 4000  | 1         | 0.22%   |
| 3866  | 1         | 0.22%   |
| 3666  | 1         | 0.22%   |
| 3400  | 1         | 0.22%   |
| 3333  | 1         | 0.22%   |
| 3100  | 1         | 0.22%   |
| 2733  | 1         | 0.22%   |
| 1866  | 1         | 0.22%   |
| 1200  | 1         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 7         | 24.14%  |
| Hewlett-Packard     | 6         | 20.69%  |
| Canon               | 6         | 20.69%  |
| Samsung Electronics | 3         | 10.34%  |
| Seiko Epson         | 2         | 6.9%    |
| Xerox               | 1         | 3.45%   |
| QinHeng Electronics | 1         | 3.45%   |
| Prolific Technology | 1         | 3.45%   |
| ICS Advent          | 1         | 3.45%   |
| Dymo-CoStar         | 1         | 3.45%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Brother HL-2130 series                 | 3         | 10%     |
| Xerox B215                             | 1         | 3.33%   |
| Seiko Epson WF-4830 Series             | 1         | 3.33%   |
| Seiko Epson ET-2800 Series             | 1         | 3.33%   |
| Samsung SCX-3400 Series                | 1         | 3.33%   |
| Samsung ML-191x/ML-252x Laser Printer  | 1         | 3.33%   |
| Samsung M2070 Series                   | 1         | 3.33%   |
| QinHeng CH340S                         | 1         | 3.33%   |
| Prolific PL2305 Parallel Port          | 1         | 3.33%   |
| ICS Advent Parallel Adapter            | 1         | 3.33%   |
| HP PSC-1315/PSC-1317                   | 1         | 3.33%   |
| HP LaserJet P2035                      | 1         | 3.33%   |
| HP LaserJet 1010                       | 1         | 3.33%   |
| HP Ink Tank Wireless 410 series        | 1         | 3.33%   |
| HP ENVY Pro 6400 series                | 1         | 3.33%   |
| HP ENVY 5000 series                    | 1         | 3.33%   |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1         | 3.33%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 3.33%   |
| Canon TR8500 series                    | 1         | 3.33%   |
| Canon Pro9000II series                 | 1         | 3.33%   |
| Canon PIXMA MX920 Series               | 1         | 3.33%   |
| Canon PIXMA MP240                      | 1         | 3.33%   |
| Canon PIXMA MG2500 Series              | 1         | 3.33%   |
| Canon E400 series                      | 1         | 3.33%   |
| Brother MFC-L2700DW                    | 1         | 3.33%   |
| Brother MFC-5440CN                     | 1         | 3.33%   |
| Brother HL-3140CW series               | 1         | 3.33%   |
| Brother HL-2270DW Laser Printer        | 1         | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 3         | 75%     |
| Mustek Systems | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 25%     |
| Canon CanoScan N650U/N656U         | 1         | 25%     |
| Canon CanoScan LiDE 60             | 1         | 25%     |
| Canon CanoScan LiDE 200            | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 207       | 19.53%  |
| Acer                                   | 104       | 9.81%   |
| Microdia                               | 103       | 9.72%   |
| IMC Networks                           | 102       | 9.62%   |
| Realtek Semiconductor                  | 73        | 6.89%   |
| Logitech                               | 65        | 6.13%   |
| Quanta                                 | 57        | 5.38%   |
| Apple                                  | 56        | 5.28%   |
| Sunplus Innovation Technology          | 49        | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 2.45%   |
| Syntek                                 | 25        | 2.36%   |
| Suyin                                  | 19        | 1.79%   |
| Luxvisions Innotech Limited            | 19        | 1.79%   |
| Lite-On Technology                     | 16        | 1.51%   |
| Microsoft                              | 15        | 1.42%   |
| Samsung Electronics                    | 12        | 1.13%   |
| Silicon Motion                         | 10        | 0.94%   |
| Sonix Technology                       | 9         | 0.85%   |
| SunplusIT                              | 8         | 0.75%   |
| Razer USA                              | 7         | 0.66%   |
| Z-Star Microelectronics                | 6         | 0.57%   |
| Generalplus Technology                 | 5         | 0.47%   |
| MacroSilicon                           | 4         | 0.38%   |
| Jieli Technology                       | 4         | 0.38%   |
| DJKANA19IDX53W                         | 4         | 0.38%   |
| LG Electronics                         | 3         | 0.28%   |
| Cubeternet                             | 3         | 0.28%   |
| AVerMedia Technologies                 | 3         | 0.28%   |
| ARC International                      | 3         | 0.28%   |
| Alcor Micro                            | 3         | 0.28%   |
| Valve Software                         | 2         | 0.19%   |
| Unknown                                | 2         | 0.19%   |
| Sunplus IT                             | 2         | 0.19%   |
| Ricoh                                  | 2         | 0.19%   |
| Primax Electronics                     | 2         | 0.19%   |
| KYE Systems (Mouse Systems)            | 2         | 0.19%   |
| Creative Technology                    | 2         | 0.19%   |
| YGTek                                  | 1         | 0.09%   |
| XHT-210518                             | 1         | 0.09%   |
| WaveRider Communications               | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 46        | 4.29%   |
| IMC Networks USB2.0 HD UVC WebCam        | 41        | 3.82%   |
| Chicony Integrated Camera                | 41        | 3.82%   |
| Realtek Integrated_Webcam_HD             | 29        | 2.71%   |
| IMC Networks Integrated Camera           | 26        | 2.43%   |
| Syntek Integrated Camera                 | 22        | 2.05%   |
| Chicony HD WebCam                        | 22        | 2.05%   |
| Acer Integrated Camera                   | 21        | 1.96%   |
| Acer HD Webcam                           | 19        | 1.77%   |
| Apple Built-in iSight                    | 18        | 1.68%   |
| Acer BisonCam,NB Pro                     | 18        | 1.68%   |
| Logitech Webcam C270                     | 17        | 1.59%   |
| Chicony USB2.0 Camera                    | 15        | 1.4%    |
| Apple iPhone 5/5C/5S/6/SE                | 15        | 1.4%    |
| Apple FaceTime HD Camera (Built-in)      | 13        | 1.21%   |
| Samsung Galaxy series, misc. (MTP mode)  | 12        | 1.12%   |
| Quanta HD User Facing                    | 12        | 1.12%   |
| Sunplus Integrated_Webcam_HD             | 11        | 1.03%   |
| Quanta HP HD Camera                      | 11        | 1.03%   |
| Logitech HD Pro Webcam C920              | 11        | 1.03%   |
| Realtek USB Camera                       | 9         | 0.84%   |
| Chicony USB2.0 VGA UVC WebCam            | 9         | 0.84%   |
| Chicony Integrated Camera (1280x720@30)  | 9         | 0.84%   |
| Chicony HD User Facing                   | 9         | 0.84%   |
| Apple FaceTime HD Camera                 | 9         | 0.84%   |
| Microdia Integrated Webcam               | 8         | 0.75%   |
| Chicony HP HD Camera                     | 8         | 0.75%   |
| Microdia USB 2.0 Camera                  | 7         | 0.65%   |
| Luxvisions Innotech Limited HP HD Camera | 7         | 0.65%   |
| Logitech C922 Pro Stream Webcam          | 7         | 0.65%   |
| Lite-On Integrated Camera                | 7         | 0.65%   |
| Chicony USB 2.0 Camera                   | 7         | 0.65%   |
| Chicony TOSHIBA Web Camera - HD          | 7         | 0.65%   |
| Acer SunplusIT Integrated Camera         | 7         | 0.65%   |
| Sonix USB2.0 HD UVC WebCam               | 6         | 0.56%   |
| Razer USA Gaming Webcam [Kiyo]           | 6         | 0.56%   |
| Quanta HP Wide Vision HD Camera          | 6         | 0.56%   |
| Microdia Integrated_Webcam_FHD           | 6         | 0.56%   |
| Microdia Integrated Webcam HD            | 6         | 0.56%   |
| Microdia Hy-HD-Camera                    | 6         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 67        | 36.81%  |
| Validity Sensors                   | 44        | 24.18%  |
| Shenzhen Goodix Technology         | 37        | 20.33%  |
| LighTuning Technology              | 10        | 5.49%   |
| Elan Microelectronics              | 9         | 4.95%   |
| AuthenTec                          | 5         | 2.75%   |
| Upek                               | 3         | 1.65%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.65%   |
| HOLTEK                             | 2         | 1.1%    |
| Samsung Electronics                | 1         | 0.55%   |
| DigitalPersona                     | 1         | 0.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 24        | 13.19%  |
| Shenzhen Goodix  Fingerprint Device                                        | 18        | 9.89%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 8.79%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 6.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 6.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 3.85%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 3.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 3.85%   |
| Elan ELAN:ARM-M4                                                           | 7         | 3.85%   |
| Synaptics WBDI Device                                                      | 5         | 2.75%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.2%    |
| Synaptics  WBDI                                                            | 4         | 2.2%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.65%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.65%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.65%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 1.65%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.65%   |
| Validity Sensors VFS491                                                    | 2         | 1.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 1.1%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.1%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.1%    |
| HOLTEK FocalTech Fingerprint Device                                        | 2         | 1.1%    |
| Elan ELAN:Fingerprint                                                      | 2         | 1.1%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.1%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.55%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.55%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.55%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.55%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.55%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.55%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.55%   |
| AuthenTec AES2810                                                          | 1         | 0.55%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 33        | 50%     |
| Alcor Micro           | 20        | 30.3%   |
| O2 Micro              | 4         | 6.06%   |
| Upek                  | 2         | 3.03%   |
| OmniKey               | 2         | 3.03%   |
| Lenovo                | 2         | 3.03%   |
| SCM Microsystems      | 1         | 1.52%   |
| Clay Logic            | 1         | 1.52%   |
| Advanced Card Systems | 1         | 1.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 30.3%   |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 15.15%  |
| Broadcom 58200                                                               | 10        | 15.15%  |
| Broadcom 5880                                                                | 9         | 13.64%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 6.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 4.55%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.03%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.03%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.52%   |
| OmniKey CardMan 4321                                                         | 1         | 1.52%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 1.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.52%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.52%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 1.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1064      | 67.21%  |
| 1     | 420       | 26.53%  |
| 2     | 81        | 5.12%   |
| 3     | 17        | 1.07%   |
| 4     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 175       | 28.41%  |
| Net/wireless             | 92        | 14.94%  |
| Multimedia controller    | 89        | 14.45%  |
| Graphics card            | 77        | 12.5%   |
| Chipcard                 | 62        | 10.06%  |
| Bluetooth                | 39        | 6.33%   |
| Camera                   | 18        | 2.92%   |
| Sound                    | 13        | 2.11%   |
| Net/ethernet             | 11        | 1.79%   |
| Unassigned class         | 9         | 1.46%   |
| Communication controller | 8         | 1.3%    |
| Storage                  | 6         | 0.97%   |
| Network                  | 6         | 0.97%   |
| Storage/ide              | 4         | 0.65%   |
| Modem                    | 4         | 0.65%   |
| Card reader              | 2         | 0.32%   |
| Wireless                 | 1         | 0.16%   |

