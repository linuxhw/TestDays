Pop!_OS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS/Desktop/README.md) and [notebooks](/Dist/Pop!_OS/Notebook/README.md).

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

Total: 11510

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
| Dell          | Inspiron 7720               | Notebook    | [a75b9a21f9](https://linux-hardware.org/?probe=a75b9a21f9) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [ae4fc56cb3](https://linux-hardware.org/?probe=ae4fc56cb3) | Nov 23, 2022 |
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
| MSI           | 2AE0                        | Desktop     | [cfb41eba48](https://linux-hardware.org/?probe=cfb41eba48) | Nov 19, 2022 |
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
| Positivo      | POS-EIH61CR POSITIVO        | Desktop     | [81bd40e949](https://linux-hardware.org/?probe=81bd40e949) | Nov 10, 2022 |
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
| System76      | Galago Pro                  | Notebook    | [8728b448e9](https://linux-hardware.org/?probe=8728b448e9) | Nov 05, 2022 |
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
| Colorful T... | A320M-K PRO YV14            | Desktop     | [cf54f0dbf3](https://linux-hardware.org/?probe=cf54f0dbf3) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [5059f2f52e](https://linux-hardware.org/?probe=5059f2f52e) | Nov 03, 2022 |
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
| Acer          | Predator PH317-52           | Notebook    | [379aad9180](https://linux-hardware.org/?probe=379aad9180) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | Notebook    | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [84fa1dd520](https://linux-hardware.org/?probe=84fa1dd520) | Oct 10, 2022 |
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
| Dell          | G7 7500                     | Notebook    | [e50429ccfa](https://linux-hardware.org/?probe=e50429ccfa) | Oct 08, 2022 |
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
| Dell          | Precision M4800             | Notebook    | [d4142adadc](https://linux-hardware.org/?probe=d4142adadc) | Sep 29, 2022 |
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
| MSI           | GS73 Stealth 8RF            | Notebook    | [37d9172163](https://linux-hardware.org/?probe=37d9172163) | Sep 26, 2022 |
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
| System76      | Oryx Pro                    | Notebook    | [3cf39a6993](https://linux-hardware.org/?probe=3cf39a6993) | Sep 24, 2022 |
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
| ASUSTek       | E402NA                      | Notebook    | [9d97fe89bb](https://linux-hardware.org/?probe=9d97fe89bb) | Sep 16, 2022 |
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
| HP            | Laptop 15s-fq1xxx           | Notebook    | [dc870b4e8a](https://linux-hardware.org/?probe=dc870b4e8a) | Sep 15, 2022 |
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
| Dell          | Precision 3551              | Notebook    | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
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
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
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
| Dell          | Latitude E6400              | Notebook    | [714643ef93](https://linux-hardware.org/?probe=714643ef93) | Aug 25, 2022 |
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
| System76      | Thelio thelio-r2            | Desktop     | [6eb968883d](https://linux-hardware.org/?probe=6eb968883d) | Aug 22, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [33ff4e4962](https://linux-hardware.org/?probe=33ff4e4962) | Aug 22, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Dell          | 02P9X9 A00                  | Server      | [b7d9a0c4a2](https://linux-hardware.org/?probe=b7d9a0c4a2) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [6b5ced2971](https://linux-hardware.org/?probe=6b5ced2971) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| Unknown       | GSUO H61V10C                | Desktop     | [1e7ccd0999](https://linux-hardware.org/?probe=1e7ccd0999) | Aug 22, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pop!_OS 20.04 | 2116      | 25.44%  |
| Pop!_OS 21.04 | 1798      | 21.62%  |
| Pop!_OS 20.10 | 1649      | 19.83%  |
| Pop!_OS 22.04 | 1569      | 18.86%  |
| Pop!_OS 21.10 | 1110      | 13.35%  |
| Pop!_OS 19.10 | 47        | 0.57%   |
| Pop!_OS 19.04 | 12        | 0.14%   |
| Pop!_OS 18.04 | 11        | 0.13%   |
| Pop!_OS 18.10 | 5         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Pop!_OS | 7851      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 837       | 9.45%   |
| 5.8.0-7630-generic       | 741       | 8.36%   |
| 5.4.0-7634-generic       | 666       | 7.52%   |
| 5.13.0-7614-generic      | 496       | 5.6%    |
| 5.8.0-7642-generic       | 481       | 5.43%   |
| 5.4.0-7642-generic       | 465       | 5.25%   |
| 5.17.5-76051705-generic  | 447       | 5.05%   |
| 5.11.0-7614-generic      | 437       | 4.93%   |
| 5.19.0-76051900-generic  | 434       | 4.9%    |
| 5.13.0-7620-generic      | 412       | 4.65%   |
| 5.15.15-76051515-generic | 280       | 3.16%   |
| 5.16.11-76051611-generic | 262       | 2.96%   |
| 5.15.5-76051505-generic  | 236       | 2.66%   |
| 5.11.0-7612-generic      | 226       | 2.55%   |
| 5.18.10-76051810-generic | 205       | 2.31%   |
| 5.8.0-7625-generic       | 195       | 2.2%    |
| 5.17.15-76051715-generic | 188       | 2.12%   |
| 5.11.0-7633-generic      | 180       | 2.03%   |
| 5.16.19-76051619-generic | 177       | 2%      |
| 5.15.8-76051508-generic  | 171       | 1.93%   |
| 5.16.15-76051615-generic | 150       | 1.69%   |
| 5.4.0-7626-generic       | 144       | 1.63%   |
| 6.0.6-76060006-generic   | 129       | 1.46%   |
| 5.15.11-76051511-generic | 112       | 1.26%   |
| 5.15.23-76051523-generic | 91        | 1.03%   |
| 6.0.2-76060002-generic   | 82        | 0.93%   |
| 5.4.0-7625-generic       | 74        | 0.84%   |
| 5.4.0-7629-generic       | 62        | 0.7%    |
| 5.19.16-76051916-generic | 42        | 0.47%   |
| 6.0.3-76060003-generic   | 38        | 0.43%   |
| 5.3.0-7625-generic       | 16        | 0.18%   |
| 5.3.0-7629-generic       | 10        | 0.11%   |
| 5.3.0-7648-generic       | 9         | 0.1%    |
| 5.11.0-051100-generic    | 9         | 0.1%    |
| 5.4.0-7624-generic       | 6         | 0.07%   |
| 5.13.0-1011-raspi        | 6         | 0.07%   |
| 5.3.0-22-generic         | 5         | 0.06%   |
| 5.15.0-76051500-generic  | 5         | 0.06%   |
| 5.8.5-xanmod1            | 4         | 0.05%   |
| 5.8.5-050805-generic     | 4         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 1624      | 18.77%  |
| 5.4.0   | 1370      | 15.83%  |
| 5.8.0   | 1357      | 15.68%  |
| 5.13.0  | 910       | 10.52%  |
| 5.17.5  | 450       | 5.2%    |
| 5.19.0  | 437       | 5.05%   |
| 5.15.15 | 281       | 3.25%   |
| 5.16.11 | 262       | 3.03%   |
| 5.15.5  | 236       | 2.73%   |
| 5.18.10 | 205       | 2.37%   |
| 5.17.15 | 188       | 2.17%   |
| 5.16.19 | 177       | 2.05%   |
| 5.15.8  | 171       | 1.98%   |
| 5.16.15 | 150       | 1.73%   |
| 6.0.6   | 130       | 1.5%    |
| 5.15.11 | 112       | 1.29%   |
| 5.15.23 | 91        | 1.05%   |
| 6.0.2   | 85        | 0.98%   |
| 5.3.0   | 51        | 0.59%   |
| 5.19.16 | 42        | 0.49%   |
| 6.0.3   | 38        | 0.44%   |
| 5.0.0   | 12        | 0.14%   |
| 5.8.5   | 8         | 0.09%   |
| 5.7.0   | 8         | 0.09%   |
| 5.15.0  | 8         | 0.09%   |
| 5.8.12  | 7         | 0.08%   |
| 4.18.0  | 7         | 0.08%   |
| 5.13.12 | 6         | 0.07%   |
| 5.10.0  | 6         | 0.07%   |
| 5.8.6   | 5         | 0.06%   |
| 5.6.16  | 5         | 0.06%   |
| 5.7.8   | 4         | 0.05%   |
| 5.7.1   | 4         | 0.05%   |
| 5.14.0  | 4         | 0.05%   |
| 5.12.14 | 4         | 0.05%   |
| 6.0.9   | 3         | 0.03%   |
| 5.9.1   | 3         | 0.03%   |
| 5.8.9   | 3         | 0.03%   |
| 5.8.11  | 3         | 0.03%   |
| 5.7.15  | 3         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 1633      | 19.03%  |
| 5.8     | 1394      | 16.24%  |
| 5.4     | 1374      | 16.01%  |
| 5.13    | 929       | 10.82%  |
| 5.15    | 894       | 10.42%  |
| 5.17    | 637       | 7.42%   |
| 5.16    | 578       | 6.74%   |
| 5.19    | 480       | 5.59%   |
| 6.0     | 256       | 2.98%   |
| 5.18    | 212       | 2.47%   |
| 5.3     | 51        | 0.59%   |
| 5.10    | 28        | 0.33%   |
| 5.7     | 27        | 0.31%   |
| 5.12    | 18        | 0.21%   |
| 5.14    | 16        | 0.19%   |
| 5.9     | 15        | 0.17%   |
| 5.6     | 15        | 0.17%   |
| 5.0     | 12        | 0.14%   |
| 4.18    | 8         | 0.09%   |
| 4.15    | 3         | 0.03%   |
| 5.1     | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7835      | 99.8%   |
| aarch64 | 16        | 0.2%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 7596      | 96.15%  |
| KDE5            | 65        | 0.82%   |
| KDE             | 59        | 0.75%   |
| Unknown         | 54        | 0.68%   |
| X-Cinnamon      | 35        | 0.44%   |
| MATE            | 19        | 0.24%   |
| XFCE            | 16        | 0.2%    |
| GNOME Flashback | 15        | 0.19%   |
| Cinnamon        | 13        | 0.16%   |
| LXQt            | 10        | 0.13%   |
| Budgie          | 6         | 0.08%   |
| Unity           | 5         | 0.06%   |
| i3              | 3         | 0.04%   |
| pop             | 1         | 0.01%   |
| Pantheon        | 1         | 0.01%   |
| Deepin          | 1         | 0.01%   |
| awesome         | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 7646      | 96.93%  |
| Wayland | 206       | 2.61%   |
| Unknown | 23        | 0.29%   |
| Tty     | 13        | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6317      | 79.74%  |
| GDM     | 1198      | 15.12%  |
| GDM3    | 383       | 4.83%   |
| SDDM    | 13        | 0.16%   |
| TDM     | 8         | 0.1%    |
| LightDM | 3         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4482      | 56.71%  |
| en_GB   | 602       | 7.62%   |
| pt_BR   | 576       | 7.29%   |
| de_DE   | 374       | 4.73%   |
| C       | 235       | 2.97%   |
| en_AU   | 206       | 2.61%   |
| en_CA   | 179       | 2.26%   |
| fr_FR   | 160       | 2.02%   |
| it_IT   | 139       | 1.76%   |
| es_ES   | 132       | 1.67%   |
| ru_RU   | 102       | 1.29%   |
| pl_PL   | 71        | 0.9%    |
| Unknown | 71        | 0.9%    |
| sv_SE   | 53        | 0.67%   |
| pt_PT   | 52        | 0.66%   |
| nl_NL   | 49        | 0.62%   |
| en_IN   | 31        | 0.39%   |
| fi_FI   | 29        | 0.37%   |
| nb_NO   | 21        | 0.27%   |
| en_ZA   | 21        | 0.27%   |
| es_MX   | 20        | 0.25%   |
| fr_CA   | 19        | 0.24%   |
| es_AR   | 19        | 0.24%   |
| en_DK   | 16        | 0.2%    |
| tr_TR   | 15        | 0.19%   |
| en_NZ   | 15        | 0.19%   |
| es_CL   | 13        | 0.16%   |
| hr_HR   | 12        | 0.15%   |
| da_DK   | 12        | 0.15%   |
| sk_SK   | 11        | 0.14%   |
| nl_BE   | 11        | 0.14%   |
| hu_HU   | 11        | 0.14%   |
| cs_CZ   | 11        | 0.14%   |
| zh_TW   | 10        | 0.13%   |
| ja_JP   | 9         | 0.11%   |
| en_IE   | 9         | 0.11%   |
| ro_RO   | 8         | 0.1%    |
| de_AT   | 8         | 0.1%    |
| zh_CN   | 7         | 0.09%   |
| de_CH   | 7         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 5840      | 73.36%  |
| EFI  | 2121      | 26.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 7535      | 95.69%  |
| Btrfs   | 172       | 2.18%   |
| Overlay | 125       | 1.59%   |
| Xfs     | 24        | 0.3%    |
| Unknown | 12        | 0.15%   |
| Zfs     | 5         | 0.06%   |
| Ext2    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6275      | 79.32%  |
| GPT     | 1464      | 18.51%  |
| MBR     | 172       | 2.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7659      | 97.23%  |
| Yes       | 218       | 2.77%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7188      | 91.1%   |
| Yes       | 702       | 8.9%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1368      | 17.42%  |
| Dell                    | 1057      | 13.46%  |
| Lenovo                  | 1019      | 12.98%  |
| Hewlett-Packard         | 827       | 10.53%  |
| Gigabyte Technology     | 614       | 7.82%   |
| MSI                     | 599       | 7.63%   |
| Acer                    | 380       | 4.84%   |
| Apple                   | 323       | 4.11%   |
| ASRock                  | 311       | 3.96%   |
| System76                | 190       | 2.42%   |
| Intel                   | 110       | 1.4%    |
| Toshiba                 | 89        | 1.13%   |
| Samsung Electronics     | 84        | 1.07%   |
| HUAWEI                  | 53        | 0.68%   |
| Alienware               | 49        | 0.62%   |
| Sony                    | 46        | 0.59%   |
| Notebook                | 41        | 0.52%   |
| Microsoft               | 40        | 0.51%   |
| Fujitsu                 | 38        | 0.48%   |
| Google                  | 35        | 0.45%   |
| Positivo                | 34        | 0.43%   |
| Unknown                 | 30        | 0.38%   |
| Pegatron                | 27        | 0.34%   |
| Medion                  | 21        | 0.27%   |
| Razer                   | 20        | 0.25%   |
| Raspberry Pi Foundation | 16        | 0.2%    |
| PC Specialist           | 16        | 0.2%    |
| Foxconn                 | 16        | 0.2%    |
| Biostar                 | 16        | 0.2%    |
| ECS                     | 15        | 0.19%   |
| Timi                    | 14        | 0.18%   |
| Supermicro              | 14        | 0.18%   |
| LG Electronics          | 13        | 0.17%   |
| Gateway                 | 12        | 0.15%   |
| TUXEDO                  | 11        | 0.14%   |
| Packard Bell            | 11        | 0.14%   |
| Framework               | 10        | 0.13%   |
| Huanan                  | 9         | 0.11%   |
| GPU Company             | 9         | 0.11%   |
| PCWare                  | 8         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUS All Series                | 79        | 1.01%   |
| Unknown                        | 42        | 0.53%   |
| System76 Oryx Pro              | 41        | 0.52%   |
| ASUS TUF Gaming X570-PLUS      | 35        | 0.45%   |
| System76 Lemur Pro             | 34        | 0.43%   |
| Gigabyte B450M DS3H            | 33        | 0.42%   |
| MSI MS-7C02                    | 29        | 0.37%   |
| Dell XPS 15 7590               | 29        | 0.37%   |
| MSI MS-7C37                    | 26        | 0.33%   |
| MSI MS-7B86                    | 25        | 0.32%   |
| ASUS ROG STRIX B450-F GAMING   | 25        | 0.32%   |
| Apple MacBookPro9,2            | 22        | 0.28%   |
| ASUS PRIME B450M-A             | 21        | 0.27%   |
| System76 Galago Pro            | 20        | 0.25%   |
| Dell OptiPlex 9020             | 20        | 0.25%   |
| ASUS ROG STRIX B550-F GAMING   | 20        | 0.25%   |
| System76 Thelio                | 19        | 0.24%   |
| HP Pavilion Notebook           | 19        | 0.24%   |
| Dell XPS 15 9500               | 19        | 0.24%   |
| System76 Gazelle               | 18        | 0.23%   |
| Gigabyte X570 AORUS ELITE      | 18        | 0.23%   |
| System76 Darter Pro            | 16        | 0.2%    |
| ASRock B450M Pro4              | 16        | 0.2%    |
| Apple MacBookPro8,1            | 16        | 0.2%    |
| HP Pavilion 15                 | 15        | 0.19%   |
| Dell OptiPlex 7010             | 15        | 0.19%   |
| ASRock B450M Steel Legend      | 15        | 0.19%   |
| HP Notebook                    | 14        | 0.18%   |
| Dell XPS 15 9560               | 14        | 0.18%   |
| Apple MacBookPro12,1           | 14        | 0.18%   |
| Apple MacBookAir7,2            | 14        | 0.18%   |
| Apple MacBookAir6,2            | 14        | 0.18%   |
| HP Pavilion dv6                | 13        | 0.17%   |
| Gigabyte B450 I AORUS PRO WIFI | 13        | 0.17%   |
| Dell Latitude E6420            | 13        | 0.17%   |
| RPi Raspberry Pi               | 12        | 0.15%   |
| MSI MS-7C91                    | 12        | 0.15%   |
| Lenovo IdeaPad S145-15API 81V7 | 12        | 0.15%   |
| Gigabyte X570 AORUS MASTER     | 12        | 0.15%   |
| Gigabyte B450 AORUS M          | 12        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 429       | 5.46%   |
| Dell Inspiron      | 305       | 3.88%   |
| Acer Aspire        | 261       | 3.32%   |
| ASUS ROG           | 258       | 3.29%   |
| Lenovo IdeaPad     | 236       | 3.01%   |
| Dell Latitude      | 194       | 2.47%   |
| Dell XPS           | 192       | 2.45%   |
| HP Pavilion        | 160       | 2.04%   |
| ASUS PRIME         | 160       | 2.04%   |
| ASUS TUF           | 136       | 1.73%   |
| Dell OptiPlex      | 133       | 1.69%   |
| HP EliteBook       | 93        | 1.18%   |
| Dell Precision     | 93        | 1.18%   |
| HP Laptop          | 85        | 1.08%   |
| ASUS All           | 79        | 1.01%   |
| Toshiba Satellite  | 77        | 0.98%   |
| ASUS VivoBook      | 74        | 0.94%   |
| HP ProBook         | 70        | 0.89%   |
| HP ENVY            | 68        | 0.87%   |
| HP Compaq          | 67        | 0.85%   |
| Gigabyte X570      | 66        | 0.84%   |
| Lenovo Legion      | 64        | 0.82%   |
| Lenovo Yoga        | 56        | 0.71%   |
| Dell Vostro        | 55        | 0.7%    |
| Lenovo ThinkCentre | 49        | 0.62%   |
| Gigabyte B450      | 46        | 0.59%   |
| Gigabyte B450M     | 45        | 0.57%   |
| Acer Nitro         | 45        | 0.57%   |
| Unknown            | 42        | 0.53%   |
| System76 Oryx      | 41        | 0.52%   |
| Microsoft Surface  | 40        | 0.51%   |
| System76 Lemur     | 37        | 0.47%   |
| ASUS ASUS          | 37        | 0.47%   |
| ASRock B450M       | 37        | 0.47%   |
| HP OMEN            | 33        | 0.42%   |
| ASUS ZenBook       | 33        | 0.42%   |
| ASRock X570        | 31        | 0.39%   |
| System76 Thelio    | 29        | 0.37%   |
| MSI MS-7C02        | 29        | 0.37%   |
| Apple MacBookPro9  | 29        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1049      | 13.36%  |
| 2018    | 961       | 12.24%  |
| 2020    | 944       | 12.02%  |
| 2012    | 587       | 7.48%   |
| 2021    | 586       | 7.46%   |
| 2017    | 560       | 7.13%   |
| 2013    | 487       | 6.2%    |
| 2011    | 465       | 5.92%   |
| 2015    | 423       | 5.39%   |
| 2014    | 416       | 5.3%    |
| 2016    | 409       | 5.21%   |
| 2010    | 309       | 3.94%   |
| 2009    | 227       | 2.89%   |
| 2008    | 171       | 2.18%   |
| 2022    | 129       | 1.64%   |
| 2007    | 89        | 1.13%   |
| 2006    | 21        | 0.27%   |
| Unknown | 16        | 0.2%    |
| 2005    | 1         | 0.01%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4295      | 54.71%  |
| Desktop        | 3022      | 38.49%  |
| Convertible    | 212       | 2.7%    |
| Tablet         | 94        | 1.2%    |
| All in one     | 94        | 1.2%    |
| Mini pc        | 93        | 1.18%   |
| Server         | 23        | 0.29%   |
| System on chip | 17        | 0.22%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7846      | 99.94%  |
| Enabled  | 5         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7718      | 98.31%  |
| Yes  | 133       | 1.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 2092      | 26.31%  |
| 4.01-8.0        | 1729      | 21.75%  |
| 8.01-16.0       | 1472      | 18.52%  |
| 32.01-64.0      | 1054      | 13.26%  |
| 3.01-4.0        | 1010      | 12.7%   |
| 64.01-256.0     | 280       | 3.52%   |
| 24.01-32.0      | 148       | 1.86%   |
| 1.01-2.0        | 111       | 1.4%    |
| 2.01-3.0        | 43        | 0.54%   |
| More than 256.0 | 10        | 0.13%   |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 2672      | 31.19%  |
| 1.01-2.0    | 2316      | 27.03%  |
| 4.01-8.0    | 1567      | 18.29%  |
| 3.01-4.0    | 1556      | 18.16%  |
| 8.01-16.0   | 355       | 4.14%   |
| 16.01-24.0  | 51        | 0.6%    |
| 0.51-1.0    | 18        | 0.21%   |
| 24.01-32.0  | 17        | 0.2%    |
| 32.01-64.0  | 12        | 0.14%   |
| 64.01-256.0 | 3         | 0.04%   |
| 0.01-0.5    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 4451      | 55.44%  |
| 2      | 2181      | 27.16%  |
| 3      | 725       | 9.03%   |
| 4      | 360       | 4.48%   |
| 5      | 147       | 1.83%   |
| 6      | 64        | 0.8%    |
| 0      | 43        | 0.54%   |
| 7      | 25        | 0.31%   |
| 8      | 9         | 0.11%   |
| 11     | 8         | 0.1%    |
| 9      | 7         | 0.09%   |
| 10     | 3         | 0.04%   |
| 23     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |
| 13     | 1         | 0.01%   |
| 12     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5536      | 70.16%  |
| Yes       | 2355      | 29.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6710      | 85.14%  |
| No        | 1171      | 14.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6329      | 80.24%  |
| No        | 1559      | 19.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5264      | 66.4%   |
| No        | 2664      | 33.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2374      | 30.1%   |
| Brazil       | 773       | 9.8%    |
| Germany      | 515       | 6.53%   |
| UK           | 400       | 5.07%   |
| Canada       | 337       | 4.27%   |
| India        | 229       | 2.9%    |
| Australia    | 229       | 2.9%    |
| Italy        | 225       | 2.85%   |
| France       | 204       | 2.59%   |
| Netherlands  | 176       | 2.23%   |
| Sweden       | 138       | 1.75%   |
| Russia       | 129       | 1.64%   |
| Poland       | 119       | 1.51%   |
| Spain        | 107       | 1.36%   |
| Portugal     | 89        | 1.13%   |
| Mexico       | 88        | 1.12%   |
| Switzerland  | 81        | 1.03%   |
| South Africa | 81        | 1.03%   |
| Romania      | 79        | 1%      |
| Finland      | 72        | 0.91%   |
| Norway       | 71        | 0.9%    |
| Austria      | 58        | 0.74%   |
| Argentina    | 57        | 0.72%   |
| Belgium      | 56        | 0.71%   |
| Philippines  | 55        | 0.7%    |
| Greece       | 55        | 0.7%    |
| New Zealand  | 53        | 0.67%   |
| Denmark      | 50        | 0.63%   |
| Turkey       | 47        | 0.6%    |
| Indonesia    | 44        | 0.56%   |
| Chile        | 40        | 0.51%   |
| Japan        | 35        | 0.44%   |
| Czechia      | 35        | 0.44%   |
| Ireland      | 34        | 0.43%   |
| Croatia      | 32        | 0.41%   |
| Bulgaria     | 31        | 0.39%   |
| Ukraine      | 30        | 0.38%   |
| Malaysia     | 30        | 0.38%   |
| Hungary      | 30        | 0.38%   |
| Israel       | 26        | 0.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 91        | 1.11%   |
| Sydney         | 61        | 0.74%   |
| Rio de Janeiro | 46        | 0.56%   |
| Melbourne      | 46        | 0.56%   |
| Berlin         | 46        | 0.56%   |
| Brisbane       | 44        | 0.54%   |
| Milan          | 43        | 0.52%   |
| Vienna         | 37        | 0.45%   |
| Dallas         | 36        | 0.44%   |
| Moscow         | 35        | 0.43%   |
| London         | 35        | 0.43%   |
| Helsinki       | 35        | 0.43%   |
| Warsaw         | 33        | 0.4%    |
| Bengaluru      | 32        | 0.39%   |
| Paris          | 31        | 0.38%   |
| Rome           | 30        | 0.37%   |
| Athens         | 30        | 0.37%   |
| Amsterdam      | 30        | 0.37%   |
| New York       | 29        | 0.35%   |
| Toronto        | 28        | 0.34%   |
| Bucharest      | 28        | 0.34%   |
| Zurich         | 27        | 0.33%   |
| Miami          | 27        | 0.33%   |
| Chicago        | 27        | 0.33%   |
| Denver         | 26        | 0.32%   |
| Auckland       | 26        | 0.32%   |
| Montreal       | 25        | 0.31%   |
| Madrid         | 25        | 0.31%   |
| Los Angeles    | 24        | 0.29%   |
| Johannesburg   | 24        | 0.29%   |
| Istanbul       | 23        | 0.28%   |
| Edmonton       | 23        | 0.28%   |
| Zagreb         | 22        | 0.27%   |
| Sofia          | 22        | 0.27%   |
| Singapore      | 22        | 0.27%   |
| Calgary        | 22        | 0.27%   |
| Brasília      | 22        | 0.27%   |
| Stockholm      | 21        | 0.26%   |
| Seattle        | 21        | 0.26%   |
| Lisbon         | 21        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 2157      | 3246   | 17.82%  |
| WDC                       | 1660      | 2296   | 13.71%  |
| Seagate                   | 1660      | 2369   | 13.71%  |
| SanDisk                   | 794       | 1039   | 6.56%   |
| Kingston                  | 690       | 865    | 5.7%    |
| Toshiba                   | 660       | 804    | 5.45%   |
| Crucial                   | 475       | 621    | 3.92%   |
| Unknown                   | 398       | 508    | 3.29%   |
| Intel                     | 339       | 449    | 2.8%    |
| SK hynix                  | 331       | 422    | 2.73%   |
| Hitachi                   | 250       | 313    | 2.07%   |
| Phison                    | 225       | 316    | 1.86%   |
| HGST                      | 214       | 255    | 1.77%   |
| A-DATA Technology         | 184       | 230    | 1.52%   |
| Micron Technology         | 178       | 208    | 1.47%   |
| Apple                     | 149       | 172    | 1.23%   |
| PNY                       | 116       | 145    | 0.96%   |
| Silicon Motion            | 108       | 146    | 0.89%   |
| China                     | 108       | 145    | 0.89%   |
| Micron/Crucial Technology | 98        | 128    | 0.81%   |
| LITEON                    | 54        | 64     | 0.45%   |
| OCZ                       | 53        | 68     | 0.44%   |
| SPCC                      | 52        | 67     | 0.43%   |
| KIOXIA                    | 49        | 58     | 0.4%    |
| XPG                       | 45        | 59     | 0.37%   |
| Corsair                   | 42        | 53     | 0.35%   |
| Transcend                 | 41        | 47     | 0.34%   |
| Team                      | 41        | 49     | 0.34%   |
| Patriot                   | 40        | 52     | 0.33%   |
| Realtek Semiconductor     | 35        | 39     | 0.29%   |
| Maxtor                    | 34        | 35     | 0.28%   |
| LITEONIT                  | 34        | 43     | 0.28%   |
| JMicron Technology        | 30        | 46     | 0.25%   |
| Phison Electronics        | 26        | 35     | 0.21%   |
| ADATA Technology          | 26        | 35     | 0.21%   |
| KingSpec                  | 25        | 30     | 0.21%   |
| Hewlett-Packard           | 25        | 32     | 0.21%   |
| Lexar                     | 24        | 25     | 0.2%    |
| Intenso                   | 24        | 26     | 0.2%    |
| Fujitsu                   | 24        | 26     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB             | 197       | 1.47%   |
| Kingston SA400S37240G 240GB SSD        | 182       | 1.36%   |
| Samsung NVMe SSD Drive 500GB           | 178       | 1.33%   |
| Samsung NVMe SSD Drive 512GB           | 118       | 0.88%   |
| Seagate ST1000LM035-1RK172 1TB         | 115       | 0.86%   |
| Samsung SSD 850 EVO 250GB              | 110       | 0.82%   |
| SanDisk NVMe SSD Drive 1TB             | 104       | 0.78%   |
| Samsung SSD 860 EVO 500GB              | 101       | 0.75%   |
| Unknown MMC Card  64GB                 | 100       | 0.75%   |
| Samsung SSD 850 EVO 500GB              | 99        | 0.74%   |
| SanDisk NVMe SSD Drive 500GB           | 95        | 0.71%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 91        | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB         | 90        | 0.67%   |
| Samsung SSD 860 EVO 1TB                | 90        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB         | 87        | 0.65%   |
| Kingston SA400S37120G 120GB SSD        | 84        | 0.63%   |
| HGST HTS721010A9E630 1TB               | 79        | 0.59%   |
| Seagate ST500DM002-1BD142 500GB        | 74        | 0.55%   |
| Samsung NVMe SSD Drive 250GB           | 74        | 0.55%   |
| Kingston SA400S37480G 480GB SSD        | 74        | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 73        | 0.55%   |
| Toshiba MQ01ABD100 1TB                 | 71        | 0.53%   |
| SanDisk NVMe SSD Drive 512GB           | 70        | 0.52%   |
| Intel NVMe SSD Drive 512GB             | 69        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB            | 68        | 0.51%   |
| Unknown MMC Card  32GB                 | 66        | 0.49%   |
| WDC WD10EZEX-08WN4A0 1TB               | 65        | 0.49%   |
| Crucial CT500MX500SSD1 500GB           | 64        | 0.48%   |
| SK hynix NVMe SSD Drive 512GB          | 61        | 0.46%   |
| Samsung NVMe SSD Drive 2TB             | 59        | 0.44%   |
| Samsung NVMe SSD Drive 1024GB          | 58        | 0.43%   |
| Crucial CT240BX500SSD1 240GB           | 54        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB           | 52        | 0.39%   |
| Intel NVMe SSD Drive 1024GB            | 52        | 0.39%   |
| Unknown MMC Card  128GB                | 49        | 0.37%   |
| Samsung SSD 860 EVO 250GB              | 49        | 0.37%   |
| Phison NVMe SSD Drive 1TB              | 49        | 0.37%   |
| Micron/Crucial NVMe SSD Drive 1TB      | 49        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD       | 49        | 0.37%   |
| Seagate Expansion 1TB                  | 48        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1605      | 2247   | 38.82%  |
| WDC                 | 1281      | 1757   | 30.99%  |
| Toshiba             | 467       | 559    | 11.3%   |
| Hitachi             | 250       | 313    | 6.05%   |
| HGST                | 214       | 255    | 5.18%   |
| Samsung Electronics | 131       | 153    | 3.17%   |
| Unknown             | 47        | 58     | 1.14%   |
| Apple               | 43        | 51     | 1.04%   |
| Maxtor              | 26        | 27     | 0.63%   |
| Fujitsu             | 23        | 25     | 0.56%   |
| ASMT                | 13        | 16     | 0.31%   |
| JMicron Technology  | 5         | 13     | 0.12%   |
| USB                 | 3         | 4      | 0.07%   |
| Hewlett-Packard     | 3         | 5      | 0.07%   |
| ExcelStor           | 3         | 3      | 0.07%   |
| SABRENT             | 2         | 3      | 0.05%   |
| Magnetic Data       | 2         | 2      | 0.05%   |
| Intenso             | 2         | 2      | 0.05%   |
| RSH-339             | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| OEM                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| LaCie               | 1         | 1      | 0.02%   |
| Inateck             | 1         | 1      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| HGST HDN            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Glyph               | 1         | 2      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| ASMT109x            | 1         | 1      | 0.02%   |
| Asm                 | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1037      | 1496   | 24.36%  |
| Kingston            | 561       | 687    | 13.18%  |
| Crucial             | 443       | 580    | 10.41%  |
| SanDisk             | 399       | 505    | 9.37%   |
| WDC                 | 290       | 362    | 6.81%   |
| A-DATA Technology   | 147       | 185    | 3.45%   |
| PNY                 | 113       | 142    | 2.65%   |
| China               | 106       | 143    | 2.49%   |
| Intel               | 99        | 117    | 2.33%   |
| Apple               | 90        | 96     | 2.11%   |
| SK hynix            | 80        | 100    | 1.88%   |
| Micron Technology   | 69        | 76     | 1.62%   |
| Toshiba             | 66        | 77     | 1.55%   |
| OCZ                 | 52        | 64     | 1.22%   |
| LITEON              | 50        | 60     | 1.17%   |
| SPCC                | 47        | 58     | 1.1%    |
| Transcend           | 40        | 46     | 0.94%   |
| Patriot             | 40        | 52     | 0.94%   |
| Team                | 34        | 42     | 0.8%    |
| LITEONIT            | 34        | 43     | 0.8%    |
| Corsair             | 32        | 39     | 0.75%   |
| Seagate             | 31        | 45     | 0.73%   |
| KingSpec            | 24        | 29     | 0.56%   |
| Lexar               | 21        | 22     | 0.49%   |
| Netac               | 19        | 20     | 0.45%   |
| Hewlett-Packard     | 18        | 23     | 0.42%   |
| Intenso             | 15        | 17     | 0.35%   |
| Apacer              | 15        | 20     | 0.35%   |
| JMicron Technology  | 14        | 15     | 0.33%   |
| GOODRAM             | 14        | 15     | 0.33%   |
| KingDian            | 13        | 16     | 0.31%   |
| Plextor             | 12        | 16     | 0.28%   |
| Gigabyte Technology | 12        | 14     | 0.28%   |
| TO Exter            | 11        | 14     | 0.26%   |
| Mushkin             | 10        | 12     | 0.23%   |
| Dogfish             | 9         | 11     | 0.21%   |
| Maxtor              | 8         | 8      | 0.19%   |
| OWC                 | 7         | 16     | 0.16%   |
| PNY USB             | 6         | 13     | 0.14%   |
| FORESEE             | 6         | 8      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 3696      | 5488   | 34.04%  |
| HDD     | 3528      | 5512   | 32.5%   |
| NVMe    | 3123      | 4621   | 28.76%  |
| MMC     | 307       | 381    | 2.83%   |
| Unknown | 203       | 280    | 1.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5726      | 10631  | 59.61%  |
| NVMe | 3114      | 4585   | 32.42%  |
| SAS  | 458       | 685    | 4.77%   |
| MMC  | 307       | 381    | 3.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4187      | 6217   | 55.54%  |
| 0.51-1.0   | 2295      | 3163   | 30.44%  |
| 1.01-2.0   | 606       | 856    | 8.04%   |
| 3.01-4.0   | 174       | 282    | 2.31%   |
| 2.01-3.0   | 132       | 194    | 1.75%   |
| 4.01-10.0  | 124       | 239    | 1.64%   |
| 10.01-20.0 | 21        | 49     | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2449      | 30.03%  |
| 251-500        | 2026      | 24.85%  |
| 501-1000       | 1490      | 18.27%  |
| 1001-2000      | 760       | 9.32%   |
| 51-100         | 379       | 4.65%   |
| More than 3000 | 374       | 4.59%   |
| 2001-3000      | 246       | 3.02%   |
| 21-50          | 191       | 2.34%   |
| 1-20           | 186       | 2.28%   |
| Unknown        | 53        | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3236      | 37.99%  |
| 21-50          | 1683      | 19.76%  |
| 101-250        | 1048      | 12.3%   |
| 51-100         | 1000      | 11.74%  |
| 251-500        | 621       | 7.29%   |
| 501-1000       | 414       | 4.86%   |
| 1001-2000      | 248       | 2.91%   |
| More than 3000 | 137       | 1.61%   |
| 2001-3000      | 77        | 0.9%    |
| Unknown        | 53        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 7         | 7      | 2.92%   |
| HGST HTS725050A7E630 500GB            | 6         | 9      | 2.5%    |
| HGST HTS721010A9E630 1TB              | 5         | 5      | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 1.67%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 1.67%   |
| WDC WD10JPCX-24UE4T0 1TB              | 3         | 3      | 1.25%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 4      | 1.25%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 1.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 1.25%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 3      | 1.25%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3         | 3      | 1.25%   |
| Seagate ST1000LX015-1U7172 1TB        | 3         | 3      | 1.25%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 3      | 1.25%   |
| Samsung Electronics HD502HI 500GB     | 3         | 3      | 1.25%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 5      | 1.25%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 5      | 1.25%   |
| Crucial CT525MX300SSD1 528GB          | 3         | 3      | 1.25%   |
| Crucial CT1000P1SSD8 1TB              | 3         | 3      | 1.25%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2         | 2      | 0.83%   |
| WDC WD10EZEX-60WN4A0 1TB              | 2         | 2      | 0.83%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.83%   |
| Toshiba HDWD110 1TB                   | 2         | 2      | 0.83%   |
| Seagate ST9750420AS 752GB             | 2         | 2      | 0.83%   |
| Seagate ST9500325AS 500GB             | 2         | 3      | 0.83%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 0.83%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 0.83%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 2         | 2      | 0.83%   |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.83%   |
| Samsung Electronics HD103SJ 1TB       | 2         | 2      | 0.83%   |
| Kingston SUV400S37120G 120GB SSD      | 2         | 2      | 0.83%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 3      | 0.83%   |
| Hitachi HDP725050GLA360 500GB         | 2         | 2      | 0.83%   |
| A-DATA Technology SU800 512GB SSD     | 2         | 2      | 0.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.42%   |
| WDC WD7500BPVT-60HXZT1 752GB          | 1         | 1      | 0.42%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.42%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.42%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 1      | 0.42%   |
| WDC WD5001AALS-00J7B1 500GB           | 1         | 1      | 0.42%   |
| WDC WD5000LPLX-00ZNTT0 500GB          | 1         | 2      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 69     | 26.27%  |
| WDC                 | 47        | 54     | 19.92%  |
| Samsung Electronics | 23        | 27     | 9.75%   |
| HGST                | 17        | 20     | 7.2%    |
| Toshiba             | 15        | 16     | 6.36%   |
| Kingston            | 11        | 14     | 4.66%   |
| Hitachi             | 11        | 14     | 4.66%   |
| Crucial             | 8         | 8      | 3.39%   |
| SK hynix            | 7         | 8      | 2.97%   |
| Intel               | 7         | 7      | 2.97%   |
| Micron Technology   | 5         | 5      | 2.12%   |
| A-DATA Technology   | 5         | 5      | 2.12%   |
| SanDisk             | 3         | 3      | 1.27%   |
| China               | 2         | 2      | 0.85%   |
| Team                | 1         | 1      | 0.42%   |
| SPCC                | 1         | 1      | 0.42%   |
| SABRENT             | 1         | 1      | 0.42%   |
| S3+                 | 1         | 1      | 0.42%   |
| Plextor             | 1         | 1      | 0.42%   |
| Maxtor              | 1         | 1      | 0.42%   |
| LITEON              | 1         | 1      | 0.42%   |
| Lexar               | 1         | 1      | 0.42%   |
| Leven               | 1         | 1      | 0.42%   |
| Intenso             | 1         | 1      | 0.42%   |
| BAITITON            | 1         | 1      | 0.42%   |
| ASMT                | 1         | 1      | 0.42%   |
| Apple               | 1         | 1      | 0.42%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 69     | 38.27%  |
| WDC                 | 46        | 53     | 28.4%   |
| HGST                | 17        | 20     | 10.49%  |
| Toshiba             | 13        | 13     | 8.02%   |
| Hitachi             | 11        | 14     | 6.79%   |
| Samsung Electronics | 10        | 10     | 6.17%   |
| Maxtor              | 1         | 1      | 0.62%   |
| ASMT                | 1         | 1      | 0.62%   |
| Apple               | 1         | 1      | 0.62%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 151       | 182    | 67.11%  |
| SSD  | 57        | 66     | 25.33%  |
| NVMe | 17        | 17     | 7.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500418ASQ 500GB        | 1         | 1      | 33.33%  |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 33.33%  |
| Patriot Pyro SSD 120GB            | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Patriot             | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 6368      | 13330  | 77.45%  |
| Works    | 1633      | 2682   | 19.86%  |
| Malfunc  | 217       | 265    | 2.64%   |
| Failed   | 3         | 4      | 0.04%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4883      | 45.74%  |
| AMD                              | 1932      | 18.1%   |
| Samsung Electronics              | 1248      | 11.69%  |
| SanDisk                          | 520       | 4.87%   |
| Phison Electronics               | 263       | 2.46%   |
| SK hynix                         | 250       | 2.34%   |
| ASMedia Technology               | 183       | 1.71%   |
| Nvidia                           | 145       | 1.36%   |
| Toshiba America Info Systems     | 141       | 1.32%   |
| Kingston Technology Company      | 138       | 1.29%   |
| Micron/Crucial Technology        | 125       | 1.17%   |
| Silicon Motion                   | 121       | 1.13%   |
| Micron Technology                | 111       | 1.04%   |
| Marvell Technology Group         | 99        | 0.93%   |
| ADATA Technology                 | 96        | 0.9%    |
| JMicron Technology               | 79        | 0.74%   |
| KIOXIA                           | 54        | 0.51%   |
| Realtek Semiconductor            | 48        | 0.45%   |
| Union Memory (Shenzhen)          | 32        | 0.3%    |
| Solid State Storage Technology   | 30        | 0.28%   |
| Seagate Technology               | 24        | 0.22%   |
| Broadcom / LSI                   | 23        | 0.22%   |
| LSI Logic / Symbios Logic        | 19        | 0.18%   |
| Apple                            | 18        | 0.17%   |
| Lite-On Technology               | 16        | 0.15%   |
| Shenzhen Longsys Electronics     | 11        | 0.1%    |
| VIA Technologies                 | 10        | 0.09%   |
| Silicon Integrated Systems [SiS] | 10        | 0.09%   |
| Silicon Image                    | 7         | 0.07%   |
| Lenovo                           | 7         | 0.07%   |
| INNOGRIT                         | 6         | 0.06%   |
| Hewlett-Packard                  | 5         | 0.05%   |
| Adaptec                          | 5         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.04%   |
| HighPoint Technologies           | 3         | 0.03%   |
| OCZ Technology Group             | 2         | 0.02%   |
| Yangtze Memory Technologies      | 1         | 0.01%   |
| Transcend                        | 1         | 0.01%   |
| O2 Micro                         | 1         | 0.01%   |
| Integrated Technology Express    | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1460      | 12.09%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 728       | 6.03%   |
| AMD 400 Series Chipset SATA Controller                                         | 416       | 3.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 394       | 3.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 329       | 2.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 314       | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 302       | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 245       | 2.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 226       | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 208       | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 178       | 1.47%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 175       | 1.45%   |
| AMD 500 Series Chipset SATA Controller                                         | 173       | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 160       | 1.32%   |
| Samsung NVMe SSD Controller 980                                                | 157       | 1.3%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 153       | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 151       | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 148       | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 147       | 1.22%   |
| Intel SATA Controller [RAID mode]                                              | 146       | 1.21%   |
| Phison E12 NVMe Controller                                                     | 141       | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 139       | 1.15%   |
| Intel SSD 660P Series                                                          | 133       | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 131       | 1.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 125       | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 124       | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 118       | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 118       | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 115       | 0.95%   |
| Micron Non-Volatile memory controller                                          | 109       | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 108       | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 105       | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 98        | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 94        | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 93        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 92        | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 89        | 0.74%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 86        | 0.71%   |
| SanDisk Non-Volatile memory controller                                         | 77        | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 75        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5950      | 56.77%  |
| NVMe | 3115      | 29.72%  |
| IDE  | 687       | 6.55%   |
| RAID | 680       | 6.49%   |
| SAS  | 35        | 0.33%   |
| SCSI | 14        | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 5579      | 71.06%  |
| AMD    | 2256      | 28.74%  |
| ARM    | 16        | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 138       | 1.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 112       | 1.42%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 109       | 1.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 93        | 1.18%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 93        | 1.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 87        | 1.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 87        | 1.11%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 75        | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 73        | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 70        | 0.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 69        | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 66        | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 65        | 0.83%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 65        | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 64        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 64        | 0.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 60        | 0.76%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 57        | 0.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 52        | 0.66%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 50        | 0.64%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 50        | 0.64%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 48        | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 47        | 0.6%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 47        | 0.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 46        | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 45        | 0.57%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 45        | 0.57%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 43        | 0.55%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 43        | 0.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 41        | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 40        | 0.51%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 40        | 0.51%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 40        | 0.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 39        | 0.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 39        | 0.5%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 39        | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 38        | 0.48%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 38        | 0.48%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 38        | 0.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1908      | 24.26%  |
| Intel Core i5           | 1756      | 22.33%  |
| AMD Ryzen 5             | 735       | 9.35%   |
| AMD Ryzen 7             | 542       | 6.89%   |
| Intel Core i3           | 445       | 5.66%   |
| Other                   | 415       | 5.28%   |
| Intel Core 2 Duo        | 231       | 2.94%   |
| AMD Ryzen 9             | 208       | 2.64%   |
| Intel Celeron           | 203       | 2.58%   |
| Intel Xeon              | 167       | 2.12%   |
| AMD Ryzen 3             | 118       | 1.5%    |
| AMD FX                  | 115       | 1.46%   |
| Intel Pentium           | 102       | 1.3%    |
| Intel Core i9           | 102       | 1.3%    |
| AMD A6                  | 62        | 0.79%   |
| Intel Pentium Dual-Core | 60        | 0.76%   |
| Intel Atom              | 60        | 0.76%   |
| AMD A8                  | 57        | 0.72%   |
| AMD A10                 | 52        | 0.66%   |
| Intel Core 2 Quad       | 47        | 0.6%    |
| AMD Ryzen Threadripper  | 45        | 0.57%   |
| AMD A4                  | 36        | 0.46%   |
| Intel Core 2            | 32        | 0.41%   |
| AMD Phenom II X4        | 31        | 0.39%   |
| AMD Ryzen 7 PRO         | 26        | 0.33%   |
| AMD Athlon              | 26        | 0.33%   |
| Intel Pentium Dual      | 21        | 0.27%   |
| AMD Athlon II X2        | 19        | 0.24%   |
| Intel Core m3           | 16        | 0.2%    |
| AMD Ryzen 5 PRO         | 16        | 0.2%    |
| Intel Genuine           | 15        | 0.19%   |
| AMD Phenom II X6        | 12        | 0.15%   |
| AMD Athlon II X4        | 12        | 0.15%   |
| AMD Athlon 64 X2        | 12        | 0.15%   |
| AMD E1                  | 11        | 0.14%   |
| AMD E                   | 11        | 0.14%   |
| Intel Pentium Gold      | 9         | 0.11%   |
| AMD Phenom              | 9         | 0.11%   |
| AMD E2                  | 9         | 0.11%   |
| Intel Pentium Silver    | 8         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2947      | 37.48%  |
| 2       | 2518      | 32.02%  |
| 6       | 1117      | 14.21%  |
| 8       | 833       | 10.59%  |
| 12      | 159       | 2.02%   |
| 16      | 71        | 0.9%    |
| 1       | 53        | 0.67%   |
| 3       | 47        | 0.6%    |
| 10      | 42        | 0.53%   |
| 14      | 29        | 0.37%   |
| 24      | 17        | 0.22%   |
| 32      | 16        | 0.2%    |
| 64      | 4         | 0.05%   |
| Unknown | 4         | 0.05%   |
| 40      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 7       | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7804      | 99.4%   |
| 2       | 43        | 0.55%   |
| Unknown | 4         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5971      | 75.97%  |
| 1       | 1885      | 23.98%  |
| Unknown | 4         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7827      | 99.69%  |
| 64-bit         | 13        | 0.17%   |
| Unknown        | 11        | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5216      | 64.84%  |
| 0x906ea    | 186       | 2.31%   |
| 0x306a9    | 163       | 2.03%   |
| 0x206a7    | 143       | 1.78%   |
| 0x306c3    | 129       | 1.6%    |
| 0x806ec    | 119       | 1.48%   |
| 0x806ea    | 116       | 1.44%   |
| 0x806c1    | 101       | 1.26%   |
| 0x08701021 | 97        | 1.21%   |
| 0x406e3    | 91        | 1.13%   |
| 0x906e9    | 87        | 1.08%   |
| 0x40651    | 84        | 1.04%   |
| 0x806e9    | 76        | 0.94%   |
| 0x506e3    | 75        | 0.93%   |
| 0x08701013 | 75        | 0.93%   |
| 0x0800820d | 70        | 0.87%   |
| 0xa0652    | 68        | 0.85%   |
| 0x1067a    | 59        | 0.73%   |
| 0x08108109 | 49        | 0.61%   |
| 0x0a50000c | 46        | 0.57%   |
| 0x08108102 | 46        | 0.57%   |
| 0x906ed    | 43        | 0.53%   |
| 0x306d4    | 41        | 0.51%   |
| 0x806eb    | 36        | 0.45%   |
| 0x08600106 | 36        | 0.45%   |
| 0x806d1    | 34        | 0.42%   |
| 0x20655    | 29        | 0.36%   |
| 0x08001138 | 27        | 0.34%   |
| 0x706e5    | 26        | 0.32%   |
| 0x406c4    | 26        | 0.32%   |
| 0x08600104 | 25        | 0.31%   |
| 0x0810100b | 25        | 0.31%   |
| 0x06000852 | 23        | 0.29%   |
| 0x08608103 | 21        | 0.26%   |
| 0x0a201016 | 19        | 0.24%   |
| 0x06006705 | 19        | 0.24%   |
| 0x06001119 | 19        | 0.24%   |
| 0x906a3    | 18        | 0.22%   |
| 0x706a1    | 18        | 0.22%   |
| 0x08600103 | 17        | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1468      | 18.67%  |
| Haswell          | 737       | 9.37%   |
| Zen 2            | 653       | 8.3%    |
| IvyBridge        | 557       | 7.08%   |
| SandyBridge      | 536       | 6.82%   |
| Skylake          | 447       | 5.68%   |
| Zen+             | 429       | 5.46%   |
| Zen 3            | 327       | 4.16%   |
| Penryn           | 297       | 3.78%   |
| CometLake        | 262       | 3.33%   |
| Unknown          | 227       | 2.89%   |
| TigerLake        | 217       | 2.76%   |
| Zen              | 211       | 2.68%   |
| Westmere         | 193       | 2.45%   |
| Broadwell        | 167       | 2.12%   |
| Piledriver       | 165       | 2.1%    |
| Silvermont       | 136       | 1.73%   |
| Core             | 131       | 1.67%   |
| K10              | 104       | 1.32%   |
| IceLake          | 103       | 1.31%   |
| Nehalem          | 86        | 1.09%   |
| Excavator        | 82        | 1.04%   |
| Goldmont plus    | 63        | 0.8%    |
| Puma             | 39        | 0.5%    |
| Steamroller      | 35        | 0.45%   |
| Goldmont         | 31        | 0.39%   |
| K8 Hammer        | 29        | 0.37%   |
| Alderlake Hybrid | 27        | 0.34%   |
| Bobcat           | 26        | 0.33%   |
| K10 Llano        | 25        | 0.32%   |
| Jaguar           | 18        | 0.23%   |
| Bulldozer        | 13        | 0.17%   |
| NetBurst         | 8         | 0.1%    |
| K8 & K10 hybrid  | 7         | 0.09%   |
| Bonnell          | 6         | 0.08%   |
| Tremont          | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4121      | 43.08%  |
| Nvidia                           | 3208      | 33.54%  |
| AMD                              | 2211      | 23.12%  |
| Matrox Electronics Systems       | 13        | 0.14%   |
| Silicon Integrated Systems [SiS] | 8         | 0.08%   |
| ASPEED Technology                | 3         | 0.03%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 374       | 3.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 303       | 3.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 302       | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 243       | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 242       | 2.47%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 234       | 2.39%   |
| Intel UHD Graphics 620                                                                   | 210       | 2.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 204       | 2.08%   |
| AMD Renoir                                                                               | 192       | 1.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 172       | 1.75%   |
| Intel HD Graphics 620                                                                    | 157       | 1.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 155       | 1.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 144       | 1.47%   |
| Intel HD Graphics 630                                                                    | 140       | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 138       | 1.41%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 131       | 1.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 124       | 1.26%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 115       | 1.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 113       | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 112       | 1.14%   |
| Intel HD Graphics 5500                                                                   | 111       | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 108       | 1.1%    |
| Intel HD Graphics 530                                                                    | 107       | 1.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 100       | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 90        | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 83        | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 80        | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 80        | 0.82%   |
| AMD Lucienne                                                                             | 74        | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 72        | 0.73%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 71        | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 64        | 0.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 62        | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 61        | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 61        | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 59        | 0.6%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 59        | 0.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 56        | 0.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 55        | 0.56%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 53        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2687      | 33.89%  |
| 1 x Nvidia              | 1786      | 22.53%  |
| 1 x AMD                 | 1689      | 21.3%   |
| Intel + Nvidia          | 1151      | 14.52%  |
| AMD + Nvidia            | 206       | 2.6%    |
| Intel + AMD             | 193       | 2.43%   |
| 2 x AMD                 | 126       | 1.59%   |
| 2 x Nvidia              | 41        | 0.52%   |
| Other                   | 17        | 0.21%   |
| 1 x SiS                 | 8         | 0.1%    |
| 1 x Matrox              | 7         | 0.09%   |
| Nvidia + Matrox         | 3         | 0.04%   |
| Nvidia + ASPEED         | 3         | 0.04%   |
| Intel + 2 x Nvidia      | 2         | 0.03%   |
| AMD + Matrox            | 2         | 0.03%   |
| 5 x Nvidia              | 1         | 0.01%   |
| 4 x Nvidia              | 1         | 0.01%   |
| 3 x Nvidia              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5016      | 63.2%   |
| Proprietary | 2575      | 32.44%  |
| Unknown     | 346       | 4.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5214      | 65.15%  |
| 1.01-2.0   | 619       | 7.73%   |
| 3.01-4.0   | 583       | 7.28%   |
| 7.01-8.0   | 530       | 6.62%   |
| 5.01-6.0   | 405       | 5.06%   |
| 0.01-0.5   | 239       | 2.99%   |
| 0.51-1.0   | 177       | 2.21%   |
| 8.01-16.0  | 134       | 1.67%   |
| 2.01-3.0   | 80        | 1%      |
| 16.01-24.0 | 17        | 0.21%   |
| 4.01-5.0   | 3         | 0.04%   |
| 32.01-64.0 | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1089      | 12.23%  |
| AU Optronics            | 974       | 10.94%  |
| LG Display              | 763       | 8.57%   |
| Chimei Innolux          | 763       | 8.57%   |
| BOE                     | 674       | 7.57%   |
| Goldstar                | 588       | 6.6%    |
| Dell                    | 549       | 6.17%   |
| Acer                    | 361       | 4.05%   |
| Hewlett-Packard         | 276       | 3.1%    |
| Apple                   | 254       | 2.85%   |
| AOC                     | 252       | 2.83%   |
| Sharp                   | 210       | 2.36%   |
| Ancor Communications    | 209       | 2.35%   |
| BenQ                    | 202       | 2.27%   |
| Philips                 | 142       | 1.59%   |
| ASUSTek Computer        | 136       | 1.53%   |
| Lenovo                  | 127       | 1.43%   |
| PANDA                   | 124       | 1.39%   |
| ViewSonic               | 82        | 0.92%   |
| Chi Mei Optoelectronics | 79        | 0.89%   |
| Sony                    | 64        | 0.72%   |
| Iiyama                  | 63        | 0.71%   |
| InfoVision              | 50        | 0.56%   |
| MSI                     | 49        | 0.55%   |
| Sceptre Tech            | 45        | 0.51%   |
| Vizio                   | 41        | 0.46%   |
| Panasonic               | 38        | 0.43%   |
| Toshiba                 | 30        | 0.34%   |
| CSO                     | 25        | 0.28%   |
| Unknown                 | 23        | 0.26%   |
| Gigabyte Technology     | 23        | 0.26%   |
| Insignia                | 18        | 0.2%    |
| Eizo                    | 18        | 0.2%    |
| Fujitsu Siemens         | 17        | 0.19%   |
| LG Electronics          | 16        | 0.18%   |
| Vestel Elektronik       | 15        | 0.17%   |
| NEC Computers           | 15        | 0.17%   |
| MStar                   | 15        | 0.17%   |
| Hitachi                 | 15        | 0.17%   |
| LG Philips              | 14        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 66        | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 59        | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 55        | 0.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 42        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 40        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 39        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 39        | 0.43%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 34        | 0.37%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 34        | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 33        | 0.36%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 27        | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 27        | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 25        | 0.27%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch         | 25        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 24        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 24        | 0.26%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch            | 23        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 23        | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 22        | 0.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 22        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 22        | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 21        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 21        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 21        | 0.23%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 20        | 0.22%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 20        | 0.22%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 19        | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch          | 19        | 0.21%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 19        | 0.21%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch            | 18        | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 18        | 0.2%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                      | 18        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch       | 18        | 0.2%    |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch               | 17        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 17        | 0.19%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 16        | 0.17%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 15        | 0.16%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                | 15        | 0.16%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 15        | 0.16%   |
| MSI PRO 22X 10M MSI1462 1920x1080 595x336mm 26.9-inch                  | 15        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3968      | 47.31%  |
| 1366x768 (WXGA)    | 1345      | 16.03%  |
| 3840x2160 (4K)     | 712       | 8.49%   |
| 2560x1440 (QHD)    | 492       | 5.87%   |
| 1600x900 (HD+)     | 278       | 3.31%   |
| 1920x1200 (WUXGA)  | 180       | 2.15%   |
| 1680x1050 (WSXGA+) | 167       | 1.99%   |
| 1440x900 (WXGA+)   | 165       | 1.97%   |
| 2560x1080          | 157       | 1.87%   |
| 3440x1440          | 148       | 1.76%   |
| 1280x1024 (SXGA)   | 141       | 1.68%   |
| 1280x800 (WXGA)    | 115       | 1.37%   |
| 2560x1600          | 67        | 0.8%    |
| 1360x768           | 58        | 0.69%   |
| 2880x1800          | 49        | 0.58%   |
| 1920x540           | 41        | 0.49%   |
| 3840x1080          | 37        | 0.44%   |
| Unknown            | 30        | 0.36%   |
| 3840x2400          | 28        | 0.33%   |
| 2160x1440          | 28        | 0.33%   |
| 3200x1800 (QHD+)   | 15        | 0.18%   |
| 2736x1824          | 15        | 0.18%   |
| 3840x1600          | 13        | 0.15%   |
| 3000x2000          | 13        | 0.15%   |
| 2256x1504          | 13        | 0.15%   |
| 1024x768 (XGA)     | 13        | 0.15%   |
| 1280x720 (HD)      | 12        | 0.14%   |
| 1600x1200          | 10        | 0.12%   |
| 3456x2160          | 6         | 0.07%   |
| 2048x1152          | 5         | 0.06%   |
| 3840x1200          | 4         | 0.05%   |
| 3200x2000          | 4         | 0.05%   |
| 1920x1280          | 4         | 0.05%   |
| 3840x1100          | 3         | 0.04%   |
| 3072x1920          | 3         | 0.04%   |
| 2288x1287          | 3         | 0.04%   |
| 800x1280           | 2         | 0.02%   |
| 7680x2160          | 2         | 0.02%   |
| 5120x1440          | 2         | 0.02%   |
| 4480x1440          | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2256      | 25.41%  |
| 13      | 864       | 9.73%   |
| 27      | 812       | 9.15%   |
| 24      | 692       | 7.79%   |
| 14      | 606       | 6.83%   |
| 23      | 565       | 6.36%   |
| 21      | 463       | 5.21%   |
| 17      | 450       | 5.07%   |
| 31      | 285       | 3.21%   |
| 34      | 257       | 2.89%   |
| 19      | 165       | 1.86%   |
| Unknown | 158       | 1.78%   |
| 18      | 148       | 1.67%   |
| 12      | 131       | 1.48%   |
| 22      | 114       | 1.28%   |
| 20      | 104       | 1.17%   |
| 84      | 86        | 0.97%   |
| 32      | 79        | 0.89%   |
| 11      | 74        | 0.83%   |
| 72      | 66        | 0.74%   |
| 16      | 56        | 0.63%   |
| 54      | 41        | 0.46%   |
| 26      | 37        | 0.42%   |
| 25      | 34        | 0.38%   |
| 48      | 31        | 0.35%   |
| 40      | 29        | 0.33%   |
| 49      | 23        | 0.26%   |
| 35      | 23        | 0.26%   |
| 52      | 22        | 0.25%   |
| 28      | 21        | 0.24%   |
| 65      | 20        | 0.23%   |
| 46      | 17        | 0.19%   |
| 37      | 15        | 0.17%   |
| 29      | 15        | 0.17%   |
| 47      | 12        | 0.14%   |
| 33      | 12        | 0.14%   |
| 43      | 9         | 0.1%    |
| 42      | 9         | 0.1%    |
| 10      | 8         | 0.09%   |
| 55      | 7         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3325      | 38.25%  |
| 501-600        | 1864      | 21.45%  |
| 401-500        | 899       | 10.34%  |
| 201-300        | 648       | 7.46%   |
| 351-400        | 551       | 6.34%   |
| 601-700        | 434       | 4.99%   |
| 701-800        | 347       | 3.99%   |
| 1001-1500      | 192       | 2.21%   |
| 1501-2000      | 165       | 1.9%    |
| Unknown        | 158       | 1.82%   |
| 801-900        | 81        | 0.93%   |
| 901-1000       | 24        | 0.28%   |
| More than 2000 | 2         | 0.02%   |
| 101-200        | 1         | 0.01%   |
| 1-100          | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 6235      | 80.04%  |
| 16/10   | 828       | 10.63%  |
| 21/9    | 309       | 3.97%   |
| 5/4     | 137       | 1.76%   |
| Unknown | 92        | 1.18%   |
| 3/2     | 83        | 1.07%   |
| 32/9    | 41        | 0.53%   |
| 4/3     | 39        | 0.5%    |
| 6/5     | 9         | 0.12%   |
| 1.96    | 5         | 0.06%   |
| 3.40    | 3         | 0.04%   |
| 3.20    | 3         | 0.04%   |
| 3.73    | 2         | 0.03%   |
| 0.62    | 2         | 0.03%   |
| 1.00    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2258      | 25.73%  |
| 201-250        | 1450      | 16.52%  |
| 81-90          | 1154      | 13.15%  |
| 301-350        | 834       | 9.5%    |
| 351-500        | 658       | 7.5%    |
| 151-200        | 412       | 4.7%    |
| 121-130        | 362       | 4.13%   |
| 71-80          | 323       | 3.68%   |
| More than 1000 | 289       | 3.29%   |
| 251-300        | 255       | 2.91%   |
| 141-150        | 183       | 2.09%   |
| Unknown        | 158       | 1.8%    |
| 501-1000       | 154       | 1.75%   |
| 61-70          | 114       | 1.3%    |
| 51-60          | 77        | 0.88%   |
| 111-120        | 42        | 0.48%   |
| 131-140        | 28        | 0.32%   |
| 91-100         | 14        | 0.16%   |
| 41-50          | 8         | 0.09%   |
| 1-40           | 2         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2673      | 31.63%  |
| 121-160       | 2459      | 29.1%   |
| 101-120       | 2144      | 25.37%  |
| 161-240       | 512       | 6.06%   |
| More than 240 | 257       | 3.04%   |
| 1-50          | 247       | 2.92%   |
| Unknown       | 158       | 1.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5990      | 74.55%  |
| 2     | 1457      | 18.13%  |
| 0     | 402       | 5%      |
| 3     | 169       | 2.1%    |
| 4     | 15        | 0.19%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4279      | 35.28%  |
| Intel                             | 4036      | 33.28%  |
| Qualcomm Atheros                  | 1315      | 10.84%  |
| Broadcom                          | 716       | 5.9%    |
| Broadcom Limited                  | 162       | 1.34%   |
| TP-Link                           | 137       | 1.13%   |
| Ralink Technology                 | 134       | 1.1%    |
| MediaTek                          | 125       | 1.03%   |
| Marvell Technology Group          | 120       | 0.99%   |
| Nvidia                            | 111       | 0.92%   |
| Ralink                            | 93        | 0.77%   |
| Samsung Electronics               | 73        | 0.6%    |
| Microsoft                         | 70        | 0.58%   |
| ASIX Electronics                  | 54        | 0.45%   |
| NetGear                           | 46        | 0.38%   |
| Qualcomm Atheros Communications   | 37        | 0.31%   |
| Xiaomi                            | 36        | 0.3%    |
| DisplayLink                       | 35        | 0.29%   |
| Google                            | 32        | 0.26%   |
| Aquantia                          | 32        | 0.26%   |
| InterBiometrics                   | 31        | 0.26%   |
| Huawei Technologies               | 27        | 0.22%   |
| D-Link                            | 27        | 0.22%   |
| ASUSTek Computer                  | 27        | 0.22%   |
| Dell                              | 26        | 0.21%   |
| Lenovo                            | 24        | 0.2%    |
| Sierra Wireless                   | 22        | 0.18%   |
| Ericsson Business Mobile Networks | 20        | 0.16%   |
| Linksys                           | 19        | 0.16%   |
| Qualcomm                          | 18        | 0.15%   |
| OnePlus Technology (Shenzhen)     | 16        | 0.13%   |
| JMicron Technology                | 16        | 0.13%   |
| Motorola PCS                      | 14        | 0.12%   |
| Edimax Technology                 | 14        | 0.12%   |
| Hewlett-Packard                   | 12        | 0.1%    |
| OPPO Electronics                  | 11        | 0.09%   |
| D-Link System                     | 10        | 0.08%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.07%   |
| Belkin Components                 | 9         | 0.07%   |
| Apple                             | 8         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2987      | 21.04%  |
| Intel Wi-Fi 6 AX200                                               | 612       | 4.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 434       | 3.06%   |
| Intel I211 Gigabit Network Connection                             | 367       | 2.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 282       | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 248       | 1.75%   |
| Intel Wireless 8265 / 8275                                        | 237       | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 234       | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 206       | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 198       | 1.39%   |
| Intel Wireless 7265                                               | 179       | 1.26%   |
| Intel Wireless 7260                                               | 169       | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 167       | 1.18%   |
| Intel Wi-Fi 6 AX201                                               | 166       | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 163       | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 159       | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 150       | 1.06%   |
| Intel Wireless 8260                                               | 146       | 1.03%   |
| Intel Wireless-AC 9260                                            | 145       | 1.02%   |
| Intel Ethernet Connection (2) I219-V                              | 143       | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 131       | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 129       | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 125       | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 122       | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 111       | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 106       | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 104       | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 102       | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 102       | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 97        | 0.68%   |
| Intel Wireless 3165                                               | 94        | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 78        | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                     | 77        | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 76        | 0.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 75        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 70        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 68        | 0.48%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 68        | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 67        | 0.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 66        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3168      | 47.16%  |
| Qualcomm Atheros                      | 1016      | 15.12%  |
| Realtek Semiconductor                 | 1006      | 14.97%  |
| Broadcom                              | 545       | 8.11%   |
| Ralink Technology                     | 134       | 1.99%   |
| TP-Link                               | 126       | 1.88%   |
| Broadcom Limited                      | 124       | 1.85%   |
| MediaTek                              | 116       | 1.73%   |
| Ralink                                | 93        | 1.38%   |
| Microsoft                             | 65        | 0.97%   |
| NetGear                               | 44        | 0.65%   |
| Qualcomm Atheros Communications       | 37        | 0.55%   |
| Marvell Technology Group              | 32        | 0.48%   |
| D-Link                                | 26        | 0.39%   |
| ASUSTek Computer                      | 25        | 0.37%   |
| Dell                                  | 23        | 0.34%   |
| Sierra Wireless                       | 22        | 0.33%   |
| Linksys                               | 15        | 0.22%   |
| Edimax Technology                     | 14        | 0.21%   |
| Qualcomm                              | 12        | 0.18%   |
| Belkin Components                     | 9         | 0.13%   |
| AVM                                   | 7         | 0.1%    |
| Sitecom Europe                        | 6         | 0.09%   |
| Hewlett-Packard                       | 6         | 0.09%   |
| Fibocom                               | 6         | 0.09%   |
| D-Link System                         | 6         | 0.09%   |
| Gemtek                                | 5         | 0.07%   |
| Mercucys                              | 4         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.06%   |
| IMC Networks                          | 3         | 0.04%   |
| Accton Technology                     | 3         | 0.04%   |
| Wilocity                              | 2         | 0.03%   |
| Samsung Electronics                   | 2         | 0.03%   |
| Ovislink                              | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| ZyDAS                                 | 1         | 0.01%   |
| Wacom                                 | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 612       | 9.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 248       | 3.66%   |
| Intel Wireless 8265 / 8275                                     | 237       | 3.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 198       | 2.92%   |
| Intel Wireless 7265                                            | 179       | 2.64%   |
| Intel Wireless 7260                                            | 169       | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 167       | 2.47%   |
| Intel Wi-Fi 6 AX201                                            | 166       | 2.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 163       | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 159       | 2.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 150       | 2.22%   |
| Intel Wireless 8260                                            | 146       | 2.16%   |
| Intel Wireless-AC 9260                                         | 145       | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 131       | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 129       | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 125       | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 122       | 1.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 106       | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 102       | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 97        | 1.43%   |
| Intel Wireless 3165                                            | 94        | 1.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 78        | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                  | 77        | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 76        | 1.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 75        | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 70        | 1.03%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 68        | 1%      |
| Broadcom BCM4331 802.11a/b/g/n                                 | 66        | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 65        | 0.96%   |
| Realtek 802.11ac NIC                                           | 61        | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 60        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 59        | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 59        | 0.87%   |
| Intel Wireless 3160                                            | 55        | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 54        | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 51        | 0.75%   |
| Ralink MT7601U Wireless Adapter                                | 49        | 0.72%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 47        | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 45        | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 44        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3877      | 54%     |
| Intel                            | 1907      | 26.56%  |
| Qualcomm Atheros                 | 404       | 5.63%   |
| Broadcom                         | 296       | 4.12%   |
| Nvidia                           | 111       | 1.55%   |
| Marvell Technology Group         | 88        | 1.23%   |
| Samsung Electronics              | 71        | 0.99%   |
| ASIX Electronics                 | 54        | 0.75%   |
| Broadcom Limited                 | 42        | 0.59%   |
| Xiaomi                           | 36        | 0.5%    |
| DisplayLink                      | 35        | 0.49%   |
| Google                           | 32        | 0.45%   |
| Aquantia                         | 32        | 0.45%   |
| Huawei Technologies              | 24        | 0.33%   |
| Lenovo                           | 23        | 0.32%   |
| JMicron Technology               | 16        | 0.22%   |
| OnePlus Technology (Shenzhen)    | 13        | 0.18%   |
| TP-Link                          | 11        | 0.15%   |
| OPPO Electronics                 | 11        | 0.15%   |
| Motorola PCS                     | 10        | 0.14%   |
| Silicon Integrated Systems [SiS] | 9         | 0.13%   |
| MediaTek                         | 8         | 0.11%   |
| Qualcomm                         | 6         | 0.08%   |
| Apple                            | 6         | 0.08%   |
| Microsoft                        | 5         | 0.07%   |
| ICS Advent                       | 5         | 0.07%   |
| VIA Technologies                 | 4         | 0.06%   |
| Linksys                          | 4         | 0.06%   |
| D-Link System                    | 4         | 0.06%   |
| Mellanox Technologies            | 3         | 0.04%   |
| LG Electronics                   | 3         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.03%   |
| T & A Mobile Phones              | 2         | 0.03%   |
| NetGear                          | 2         | 0.03%   |
| LSI                              | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| 3Com                             | 2         | 0.03%   |
| Tehuti Networks                  | 1         | 0.01%   |
| Solarflare Communications        | 1         | 0.01%   |
| Research In Motion               | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2987      | 40.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 434       | 5.93%   |
| Intel I211 Gigabit Network Connection                             | 367       | 5.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 282       | 3.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 234       | 3.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 206       | 2.82%   |
| Intel Ethernet Connection (2) I219-V                              | 143       | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 111       | 1.52%   |
| Intel Ethernet Controller I225-V                                  | 104       | 1.42%   |
| Intel Ethernet Connection (7) I219-V                              | 102       | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 68        | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 67        | 0.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 65        | 0.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 54        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 53        | 0.72%   |
| Nvidia MCP79 Ethernet                                             | 51        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 50        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 50        | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 50        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 44        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                              | 43        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 42        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 42        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 40        | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 40        | 0.55%   |
| Nvidia MCP61 Ethernet                                             | 35        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 35        | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 34        | 0.46%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 34        | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 34        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 33        | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 31        | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 30        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 29        | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 29        | 0.4%    |
| Intel I210 Gigabit Network Connection                             | 27        | 0.37%   |
| Google Nexus/Pixel Device (tether)                                | 26        | 0.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 25        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6700      | 50.95%  |
| WiFi     | 6336      | 48.18%  |
| Modem    | 89        | 0.68%   |
| Unknown  | 25        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4908      | 59.05%  |
| Ethernet | 3400      | 40.9%   |
| Unknown  | 4         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4381      | 55.63%  |
| 1     | 3170      | 40.25%  |
| 3     | 187       | 2.37%   |
| 0     | 100       | 1.27%   |
| 4     | 28        | 0.36%   |
| 5     | 5         | 0.06%   |
| 10    | 2         | 0.03%   |
| 6     | 2         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6365      | 79.96%  |
| Yes  | 1595      | 20.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2746      | 51.63%  |
| Qualcomm Atheros Communications | 425       | 7.99%   |
| Realtek Semiconductor           | 406       | 7.63%   |
| Apple                           | 307       | 5.77%   |
| Cambridge Silicon Radio         | 304       | 5.72%   |
| Broadcom                        | 241       | 4.53%   |
| IMC Networks                    | 211       | 3.97%   |
| Lite-On Technology              | 186       | 3.5%    |
| Foxconn / Hon Hai               | 112       | 2.11%   |
| ASUSTek Computer                | 93        | 1.75%   |
| Dell                            | 62        | 1.17%   |
| Marvell Semiconductor           | 34        | 0.64%   |
| Ralink                          | 30        | 0.56%   |
| Realtek                         | 28        | 0.53%   |
| Hewlett-Packard                 | 28        | 0.53%   |
| Toshiba                         | 26        | 0.49%   |
| Foxconn International           | 10        | 0.19%   |
| MediaTek                        | 8         | 0.15%   |
| Ralink Technology               | 7         | 0.13%   |
| Alps Electric                   | 7         | 0.13%   |
| TP-Link                         | 6         | 0.11%   |
| HTC (High Tech Computer)        | 4         | 0.08%   |
| Dynex                           | 4         | 0.08%   |
| Askey Computer                  | 4         | 0.08%   |
| USI                             | 3         | 0.06%   |
| Taiyo Yuden                     | 3         | 0.06%   |
| Qcom                            | 3         | 0.06%   |
| Creative Technology             | 3         | 0.06%   |
| Unknown                         | 2         | 0.04%   |
| SINO WEALTH                     | 2         | 0.04%   |
| Opticis                         | 2         | 0.04%   |
| Micro Star International        | 2         | 0.04%   |
| Integrated System Solution      | 2         | 0.04%   |
| Conwise Technology              | 2         | 0.04%   |
| Belkin Components               | 2         | 0.04%   |
| Primax Electronics              | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 855       | 16.06%  |
| Intel AX200 Bluetooth                               | 586       | 11.01%  |
| Intel AX201 Bluetooth                               | 446       | 8.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 397       | 7.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 304       | 5.71%   |
| Realtek Bluetooth Radio                             | 265       | 4.98%   |
| Qualcomm Atheros  Bluetooth Device                  | 231       | 4.34%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 135       | 2.54%   |
| Apple Bluetooth Host Controller                     | 131       | 2.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 121       | 2.27%   |
| Apple Bluetooth USB Host Controller                 | 111       | 2.08%   |
| Realtek  Bluetooth 4.2 Adapter                      | 110       | 2.07%   |
| Intel AX210 Bluetooth                               | 73        | 1.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 71        | 1.33%   |
| IMC Networks Bluetooth Radio                        | 69        | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 65        | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 54        | 1.01%   |
| IMC Networks Wireless_Device                        | 52        | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                  | 50        | 0.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 50        | 0.94%   |
| IMC Networks Bluetooth Device                       | 47        | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 45        | 0.85%   |
| Lite-On Bluetooth Device                            | 43        | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 42        | 0.79%   |
| Intel Bluetooth Device                              | 38        | 0.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 37        | 0.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 36        | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 35        | 0.66%   |
| Ralink RT3290 Bluetooth                             | 30        | 0.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 29        | 0.54%   |
| Apple Bluetooth HCI                                 | 29        | 0.54%   |
| Realtek Bluetooth Radio                             | 28        | 0.53%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.45%   |
| Foxconn / Hon Hai Wireless_Device                   | 23        | 0.43%   |
| Marvell Bluetooth and Wireless LAN Composite        | 22        | 0.41%   |
| Dell DW375 Bluetooth Module                         | 22        | 0.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 0.39%   |
| ASUS Bluetooth Radio                                | 20        | 0.38%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 19        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 5343      | 44.72%  |
| AMD                                             | 2631      | 22.02%  |
| Nvidia                                          | 2539      | 21.25%  |
| C-Media Electronics                             | 211       | 1.77%   |
| Logitech                                        | 119       | 1%      |
| JMTek                                           | 64        | 0.54%   |
| Creative Labs                                   | 61        | 0.51%   |
| Kingston Technology                             | 57        | 0.48%   |
| Razer USA                                       | 54        | 0.45%   |
| Corsair                                         | 54        | 0.45%   |
| Texas Instruments                               | 52        | 0.44%   |
| Realtek Semiconductor                           | 47        | 0.39%   |
| SteelSeries ApS                                 | 41        | 0.34%   |
| Focusrite-Novation                              | 37        | 0.31%   |
| GN Netcom                                       | 32        | 0.27%   |
| ASUSTek Computer                                | 30        | 0.25%   |
| Creative Technology                             | 29        | 0.24%   |
| Blue Microphones                                | 28        | 0.23%   |
| Generalplus Technology                          | 27        | 0.23%   |
| Lenovo                                          | 24        | 0.2%    |
| Sony                                            | 20        | 0.17%   |
| Plantronics                                     | 19        | 0.16%   |
| Apple                                           | 17        | 0.14%   |
| Astro Gaming                                    | 16        | 0.13%   |
| Sennheiser Communications                       | 14        | 0.12%   |
| Samson Technologies                             | 14        | 0.12%   |
| Giga-Byte Technology                            | 14        | 0.12%   |
| Turtle Beach                                    | 12        | 0.1%    |
| Tenx Technology                                 | 12        | 0.1%    |
| Yamaha                                          | 11        | 0.09%   |
| SAVITECH                                        | 11        | 0.09%   |
| Hewlett-Packard                                 | 11        | 0.09%   |
| Thesycon Systemsoftware & Consulting            | 10        | 0.08%   |
| Silicon Integrated Systems [SiS]                | 10        | 0.08%   |
| M-Audio                                         | 10        | 0.08%   |
| Valve Software                                  | 9         | 0.08%   |
| Micro Star International                        | 9         | 0.08%   |
| Licensed by Sony Computer Entertainment America | 9         | 0.08%   |
| FiiO Electronics Technology                     | 9         | 0.08%   |
| Audio-Technica                                  | 8         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 788       | 5.56%   |
| AMD Starship/Matisse HD Audio Controller                                   | 613       | 4.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 594       | 4.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 530       | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 496       | 3.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 449       | 3.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 380       | 2.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 347       | 2.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 298       | 2.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 277       | 1.95%   |
| Intel 8 Series HD Audio Controller                                         | 245       | 1.73%   |
| Intel Haswell-ULT HD Audio Controller                                      | 241       | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 240       | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 239       | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 234       | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 219       | 1.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 217       | 1.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 217       | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 199       | 1.4%    |
| AMD FCH Azalia Controller                                                  | 197       | 1.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 195       | 1.38%   |
| Intel Comet Lake PCH cAVS                                                  | 193       | 1.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 189       | 1.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 176       | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                              | 174       | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 169       | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                              | 168       | 1.19%   |
| Intel 200 Series PCH HD Audio                                              | 164       | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 161       | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 161       | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 152       | 1.07%   |
| AMD Navi 10 HDMI Audio                                                     | 143       | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 140       | 0.99%   |
| Intel CM238 HD Audio Controller                                            | 129       | 0.91%   |
| Nvidia TU104 HD Audio Controller                                           | 125       | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 118       | 0.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 109       | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 108       | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 93        | 0.66%   |
| Nvidia GA106 High Definition Audio Controller                              | 91        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 480       | 22.9%   |
| SK hynix            | 367       | 17.51%  |
| Kingston            | 226       | 10.78%  |
| Micron Technology   | 224       | 10.69%  |
| Corsair             | 150       | 7.16%   |
| Crucial             | 147       | 7.01%   |
| Unknown             | 104       | 4.96%   |
| G.Skill             | 98        | 4.68%   |
| A-DATA Technology   | 49        | 2.34%   |
| Smart               | 29        | 1.38%   |
| Ramaxel Technology  | 27        | 1.29%   |
| Team                | 26        | 1.24%   |
| Elpida              | 21        | 1%      |
| Goldkey             | 18        | 0.86%   |
| Neo Forza           | 17        | 0.81%   |
| Unknown             | 12        | 0.57%   |
| Unknown (ABCD)      | 11        | 0.52%   |
| Patriot             | 11        | 0.52%   |
| Smart Brazil        | 9         | 0.43%   |
| Teikon              | 7         | 0.33%   |
| Nanya Technology    | 6         | 0.29%   |
| Apacer              | 6         | 0.29%   |
| Avant               | 5         | 0.24%   |
| Silicon Power       | 3         | 0.14%   |
| High Bridge         | 3         | 0.14%   |
| GOODRAM             | 3         | 0.14%   |
| Transcend           | 2         | 0.1%    |
| Timetec             | 2         | 0.1%    |
| PNY                 | 2         | 0.1%    |
| Patriot Memory      | 2         | 0.1%    |
| OLOY                | 2         | 0.1%    |
| GSkill              | 2         | 0.1%    |
| Gold Key            | 2         | 0.1%    |
| CSX                 | 2         | 0.1%    |
| ChangXin Memory     | 2         | 0.1%    |
| AMD                 | 2         | 0.1%    |
| Unknown (8A02)      | 1         | 0.05%   |
| Unknown (898F)      | 1         | 0.05%   |
| Unifosa             | 1         | 0.05%   |
| Toshiba             | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 1.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 29        | 1.31%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 27        | 1.22%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 1%      |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 19        | 0.86%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 19        | 0.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.68%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 15        | 0.68%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.63%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.54%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 12        | 0.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.54%   |
| Unknown                                                          | 12        | 0.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.5%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 11        | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.45%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.45%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 9         | 0.41%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.41%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 9         | 0.41%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.41%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 9         | 0.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.41%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 9         | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.36%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.36%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 8         | 0.36%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 8         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1221      | 67.72%  |
| DDR3    | 362       | 20.08%  |
| LPDDR4  | 73        | 4.05%   |
| LPDDR3  | 65        | 3.61%   |
| DDR2    | 22        | 1.22%   |
| Unknown | 22        | 1.22%   |
| DDR5    | 13        | 0.72%   |
| LPDDR5  | 12        | 0.67%   |
| SDRAM   | 11        | 0.61%   |
| DDR     | 2         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1116      | 61.29%  |
| DIMM         | 505       | 27.73%  |
| Row Of Chips | 186       | 10.21%  |
| Chip         | 12        | 0.66%   |
| RIMM         | 1         | 0.05%   |
| Unknown      | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 897       | 45.88%  |
| 4096  | 452       | 23.12%  |
| 16384 | 382       | 19.54%  |
| 2048  | 105       | 5.37%   |
| 32768 | 100       | 5.12%   |
| 1024  | 17        | 0.87%   |
| 512   | 2         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 432       | 22.09%  |
| 3200    | 391       | 19.99%  |
| 1600    | 258       | 13.19%  |
| 2400    | 177       | 9.05%   |
| 2133    | 110       | 5.62%   |
| 3600    | 101       | 5.16%   |
| 1333    | 71        | 3.63%   |
| 4267    | 37        | 1.89%   |
| 1867    | 37        | 1.89%   |
| 3266    | 27        | 1.38%   |
| 3000    | 26        | 1.33%   |
| 1334    | 26        | 1.33%   |
| 8400    | 19        | 0.97%   |
| 3400    | 19        | 0.97%   |
| 800     | 18        | 0.92%   |
| 4800    | 15        | 0.77%   |
| 3733    | 15        | 0.77%   |
| 3866    | 14        | 0.72%   |
| 3466    | 14        | 0.72%   |
| 6400    | 13        | 0.66%   |
| 4266    | 11        | 0.56%   |
| 3800    | 11        | 0.56%   |
| 2933    | 11        | 0.56%   |
| 1866    | 11        | 0.56%   |
| 667     | 11        | 0.56%   |
| 2666    | 9         | 0.46%   |
| 2800    | 8         | 0.41%   |
| 1067    | 8         | 0.41%   |
| Unknown | 8         | 0.41%   |
| 3333    | 4         | 0.2%    |
| 1800    | 4         | 0.2%    |
| 4400    | 3         | 0.15%   |
| 4000    | 3         | 0.15%   |
| 3666    | 3         | 0.15%   |
| 1066    | 3         | 0.15%   |
| 4199    | 2         | 0.1%    |
| 3533    | 2         | 0.1%    |
| 3334    | 2         | 0.1%    |
| 3151    | 2         | 0.1%    |
| 3100    | 2         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 48        | 30%     |
| Brother Industries    | 32        | 20%     |
| Canon                 | 25        | 15.63%  |
| Seiko Epson           | 18        | 11.25%  |
| Samsung Electronics   | 18        | 11.25%  |
| Dymo-CoStar           | 4         | 2.5%    |
| Fuji Xerox            | 3         | 1.88%   |
| Xerox                 | 2         | 1.25%   |
| QinHeng Electronics   | 2         | 1.25%   |
| STMicroelectronics    | 1         | 0.63%   |
| Prolific Technology   | 1         | 0.63%   |
| Oki Data              | 1         | 0.63%   |
| MIIIW                 | 1         | 0.63%   |
| Lexmark International | 1         | 0.63%   |
| Kyocera               | 1         | 0.63%   |
| ICS Advent            | 1         | 0.63%   |
| Apple                 | 1         | 0.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| HP Deskjet 3050 J610 series                                | 5         | 3.11%   |
| Seiko Epson L4150 Series                                   | 3         | 1.86%   |
| Samsung SCX-3400 Series                                    | 3         | 1.86%   |
| Samsung ML-1640 Series Laser Printer                       | 3         | 1.86%   |
| Samsung M2020 Series                                       | 3         | 1.86%   |
| Canon PIXMA MX920 Series                                   | 3         | 1.86%   |
| Brother Printer                                            | 3         | 1.86%   |
| Brother HL-2270DW Laser Printer                            | 3         | 1.86%   |
| Brother HL-2130 series                                     | 3         | 1.86%   |
| Seiko Epson WF-3520 Series                                 | 2         | 1.24%   |
| Seiko Epson L355 Series                                    | 2         | 1.24%   |
| Seiko Epson L3110 Series                                   | 2         | 1.24%   |
| Seiko Epson ET-2600 Series                                 | 2         | 1.24%   |
| Samsung M2070 Series                                       | 2         | 1.24%   |
| QinHeng CH340S                                             | 2         | 1.24%   |
| HP LaserJet Professional P 1102w                           | 2         | 1.24%   |
| HP ENVY Photo 6200 series                                  | 2         | 1.24%   |
| HP ENVY 4520 series                                        | 2         | 1.24%   |
| HP ENVY 4500 series                                        | 2         | 1.24%   |
| HP DeskJet F4100 Printer series                            | 2         | 1.24%   |
| HP Deskjet 2540 series                                     | 2         | 1.24%   |
| HP Deskjet 1000 J110 series                                | 2         | 1.24%   |
| Fuji Xerox DocuPrint CM315/318 z                           | 2         | 1.24%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2         | 1.24%   |
| Canon PIXMA MG2500 Series                                  | 2         | 1.24%   |
| Brother HL-L3230CDW series                                 | 2         | 1.24%   |
| Brother HL-1110 series                                     | 2         | 1.24%   |
| Xerox Phaser 6000B                                         | 1         | 0.62%   |
| Xerox B215                                                 | 1         | 0.62%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1         | 0.62%   |
| Seiko Epson WF-4830 Series                                 | 1         | 0.62%   |
| Seiko Epson L365 Series                                    | 1         | 0.62%   |
| Seiko Epson L132 Series                                    | 1         | 0.62%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 0.62%   |
| Seiko Epson ET-3760 Series                                 | 1         | 0.62%   |
| Seiko Epson ET-3750 Series                                 | 1         | 0.62%   |
| Seiko Epson ET-2800 Series                                 | 1         | 0.62%   |
| Samsung SCX-4200 series                                    | 1         | 0.62%   |
| Samsung ML-2540 Series Laser Printer                       | 1         | 0.62%   |
| Samsung ML-191x/ML-252x Laser Printer                      | 1         | 0.62%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 10        | 62.5%   |
| Seiko Epson     | 3         | 18.75%  |
| Hewlett-Packard | 2         | 12.5%   |
| Mustek Systems  | 1         | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson Scanner                    | 2         | 12.5%   |
| Canon CanoScan N1240U/LiDE 30          | 2         | 12.5%   |
| Canon CanoScan LiDE 210                | 2         | 12.5%   |
| Seiko Epson GT-X700 [Perfection 4870]  | 1         | 6.25%   |
| Mustek Systems ScanExpress 1200 UB     | 1         | 6.25%   |
| HP Scanjet 300                         | 1         | 6.25%   |
| HP ScanJet 2400c                       | 1         | 6.25%   |
| Canon CanoScan N650U/N656U             | 1         | 6.25%   |
| Canon CanoScan LiDE 60                 | 1         | 6.25%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 6.25%   |
| Canon CanoScan LiDE 220                | 1         | 6.25%   |
| Canon CanoScan LiDE 200                | 1         | 6.25%   |
| Canon CanoScan LiDE 110                | 1         | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 996       | 21.06%  |
| IMC Networks                           | 448       | 9.47%   |
| Microdia                               | 447       | 9.45%   |
| Acer                                   | 418       | 8.84%   |
| Realtek Semiconductor                  | 351       | 7.42%   |
| Logitech                               | 319       | 6.74%   |
| Sunplus Innovation Technology          | 243       | 5.14%   |
| Apple                                  | 239       | 5.05%   |
| Quanta                                 | 204       | 4.31%   |
| Cheng Uei Precision Industry (Foxlink) | 148       | 3.13%   |
| Suyin                                  | 122       | 2.58%   |
| Syntek                                 | 110       | 2.33%   |
| Lite-On Technology                     | 87        | 1.84%   |
| Silicon Motion                         | 59        | 1.25%   |
| Microsoft                              | 58        | 1.23%   |
| Luxvisions Innotech Limited            | 41        | 0.87%   |
| Samsung Electronics                    | 37        | 0.78%   |
| Ricoh                                  | 36        | 0.76%   |
| Alcor Micro                            | 30        | 0.63%   |
| Generalplus Technology                 | 22        | 0.47%   |
| Z-Star Microelectronics                | 18        | 0.38%   |
| Sonix Technology                       | 13        | 0.27%   |
| Razer USA                              | 13        | 0.27%   |
| MacroSilicon                           | 13        | 0.27%   |
| ARC International                      | 13        | 0.27%   |
| DJKANA19IDX53W                         | 12        | 0.25%   |
| ALi                                    | 11        | 0.23%   |
| Unknown                                | 10        | 0.21%   |
| SunplusIT                              | 10        | 0.21%   |
| KYE Systems (Mouse Systems)            | 10        | 0.21%   |
| DigiTech                               | 10        | 0.21%   |
| Valve Software                         | 9         | 0.19%   |
| Primax Electronics                     | 9         | 0.19%   |
| Jieli Technology                       | 9         | 0.19%   |
| Intel                                  | 9         | 0.19%   |
| Importek                               | 9         | 0.19%   |
| Lenovo                                 | 8         | 0.17%   |
| AVerMedia Technologies                 | 8         | 0.17%   |
| OmniVision Technologies                | 6         | 0.13%   |
| LG Electronics                         | 6         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 214       | 4.48%   |
| Chicony Integrated Camera               | 183       | 3.83%   |
| IMC Networks USB2.0 HD UVC WebCam       | 143       | 2.99%   |
| IMC Networks Integrated Camera          | 134       | 2.81%   |
| Realtek Integrated_Webcam_HD            | 133       | 2.79%   |
| Chicony HD WebCam                       | 133       | 2.79%   |
| Chicony USB2.0 Camera                   | 90        | 1.88%   |
| Acer Integrated Camera                  | 89        | 1.86%   |
| Acer BisonCam,NB Pro                    | 86        | 1.8%    |
| Apple Built-in iSight                   | 79        | 1.65%   |
| Syntek Integrated Camera                | 70        | 1.47%   |
| Logitech HD Pro Webcam C920             | 70        | 1.47%   |
| Sunplus Integrated_Webcam_HD            | 66        | 1.38%   |
| Logitech Webcam C270                    | 61        | 1.28%   |
| Apple iPhone 5/5C/5S/6/SE               | 53        | 1.11%   |
| Apple FaceTime HD Camera                | 53        | 1.11%   |
| Acer HD Webcam                          | 51        | 1.07%   |
| Quanta HD User Facing                   | 46        | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 45        | 0.94%   |
| Apple FaceTime HD Camera (Built-in)     | 43        | 0.9%    |
| Acer BisonCam, NB Pro                   | 40        | 0.84%   |
| Chicony USB 2.0 Camera                  | 39        | 0.82%   |
| Realtek USB Camera                      | 36        | 0.75%   |
| Samsung Galaxy series, misc. (MTP mode) | 34        | 0.71%   |
| Microdia Laptop_Integrated_Webcam_HD    | 33        | 0.69%   |
| Lite-On Integrated Camera               | 33        | 0.69%   |
| Quanta HD Webcam                        | 31        | 0.65%   |
| Chicony TOSHIBA Web Camera - HD         | 31        | 0.65%   |
| Chicony Integrated Camera (1280x720@30) | 31        | 0.65%   |
| Chicony HP Wide Vision HD Camera        | 31        | 0.65%   |
| Sunplus HD WebCam                       | 30        | 0.63%   |
| Microdia Integrated Webcam              | 29        | 0.61%   |
| Logitech C922 Pro Stream Webcam         | 29        | 0.61%   |
| Microdia Webcam Vitade AF               | 28        | 0.59%   |
| Chicony USB2.0 HD UVC WebCam            | 28        | 0.59%   |
| Sunplus ASUS Webcam                     | 27        | 0.57%   |
| Chicony HD User Facing                  | 27        | 0.57%   |
| Chicony HP HD Camera                    | 26        | 0.54%   |
| Acer SunplusIT Integrated Camera        | 26        | 0.54%   |
| Acer EasyCamera                         | 25        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 280       | 32.9%   |
| Validity Sensors                   | 242       | 28.44%  |
| Shenzhen Goodix Technology         | 163       | 19.15%  |
| Elan Microelectronics              | 46        | 5.41%   |
| Upek                               | 41        | 4.82%   |
| LighTuning Technology              | 36        | 4.23%   |
| AuthenTec                          | 27        | 3.17%   |
| STMicroelectronics                 | 7         | 0.82%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.35%   |
| Samsung Electronics                | 2         | 0.24%   |
| HOLTEK                             | 2         | 0.24%   |
| DigitalPersona                     | 2         | 0.24%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 102       | 11.99%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 69        | 8.11%   |
| Shenzhen Goodix  Fingerprint Device                                        | 64        | 7.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 56        | 6.58%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 53        | 6.23%   |
| Shenzhen Goodix FingerPrint                                                | 43        | 5.05%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 42        | 4.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 4.47%   |
| Elan ELAN:Fingerprint                                                      | 34        | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 31        | 3.64%   |
| Synaptics  WBDI                                                            | 23        | 2.7%    |
| Validity Sensors Synaptics WBDI                                            | 20        | 2.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 19        | 2.23%   |
| Validity Sensors VFS491                                                    | 18        | 2.12%   |
| Synaptics WBDI Device                                                      | 18        | 2.12%   |
| Validity Sensors Fingerprint scanner                                       | 17        | 2%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 1.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.65%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.53%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 12        | 1.41%   |
| Elan ELAN:ARM-M4                                                           | 11        | 1.29%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.06%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 0.94%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 0.94%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 7         | 0.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 0.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 0.82%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.82%   |
| AuthenTec AES2810                                                          | 7         | 0.82%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.71%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.71%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.35%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.35%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.35%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.35%   |
| AuthenTec AES1600                                                          | 3         | 0.35%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.24%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 138       | 44.37%  |
| Alcor Micro               | 83        | 26.69%  |
| Upek                      | 28        | 9%      |
| O2 Micro                  | 22        | 7.07%   |
| Lenovo                    | 18        | 5.79%   |
| SCM Microsystems          | 7         | 2.25%   |
| OmniKey                   | 5         | 1.61%   |
| Realtek Semiconductor     | 2         | 0.64%   |
| Aladdin Knowledge Systems | 2         | 0.64%   |
| Advanced Card Systems     | 2         | 0.64%   |
| Giesecke & Devrient       | 1         | 0.32%   |
| Gemalto (was Gemplus)     | 1         | 0.32%   |
| Clay Logic                | 1         | 0.32%   |
| Chicony Electronics       | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 82        | 26.37%  |
| Broadcom BCM5880 Secure Applications Processor                               | 44        | 14.15%  |
| Broadcom 5880                                                                | 38        | 12.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 11.25%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 9%      |
| Broadcom 58200                                                               | 19        | 6.11%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 5.79%   |
| Lenovo Integrated Smart Card Reader                                          | 18        | 5.79%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 5         | 1.61%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.29%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.64%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.64%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.64%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.32%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.32%   |
| OmniKey CardMan 4321                                                         | 1         | 0.32%   |
| OmniKey CardMan 1021                                                         | 1         | 0.32%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.32%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.32%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.32%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.32%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.32%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.32%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.32%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5547      | 69.39%  |
| 1     | 2001      | 25.03%  |
| 2     | 381       | 4.77%   |
| 3     | 55        | 0.69%   |
| 4     | 7         | 0.09%   |
| 5     | 2         | 0.03%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 834       | 29.1%   |
| Net/wireless             | 516       | 18%     |
| Graphics card            | 465       | 16.22%  |
| Multimedia controller    | 325       | 11.34%  |
| Chipcard                 | 300       | 10.47%  |
| Bluetooth                | 82        | 2.86%   |
| Communication controller | 53        | 1.85%   |
| Sound                    | 45        | 1.57%   |
| Unassigned class         | 44        | 1.54%   |
| Camera                   | 44        | 1.54%   |
| Net/ethernet             | 40        | 1.4%    |
| Storage                  | 37        | 1.29%   |
| Network                  | 19        | 0.66%   |
| Card reader              | 18        | 0.63%   |
| Storage/raid             | 11        | 0.38%   |
| Storage/ide              | 11        | 0.38%   |
| Modem                    | 9         | 0.31%   |
| Firewire controller      | 4         | 0.14%   |
| Storage/nvme             | 3         | 0.1%    |
| Flash memory             | 2         | 0.07%   |
| Dvb card                 | 2         | 0.07%   |
| Wireless                 | 1         | 0.03%   |
| Unclassified device      | 1         | 0.03%   |

