Linux in Russia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

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

Total: 18193

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | [09f9cbd392](https://linux-hardware.org/?probe=09f9cbd392) | May 01, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8f8a912636](https://linux-hardware.org/?probe=8f8a912636) | May 01, 2023 |
| Apple         | MacBookAir7,2               | [1a343a4622](https://linux-hardware.org/?probe=1a343a4622) | Apr 30, 2023 |
| Notebook      | W250EGQ / W270EGQ           | [e523dbbf78](https://linux-hardware.org/?probe=e523dbbf78) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [43a167afad](https://linux-hardware.org/?probe=43a167afad) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0ae3fb5506](https://linux-hardware.org/?probe=0ae3fb5506) | Apr 30, 2023 |
| Thomson       | NEO14A-4WH128               | [be47cb81e5](https://linux-hardware.org/?probe=be47cb81e5) | Apr 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4470195d38](https://linux-hardware.org/?probe=4470195d38) | Apr 30, 2023 |
| Dell          | Inspiron N5110              | [9f932190c4](https://linux-hardware.org/?probe=9f932190c4) | Apr 30, 2023 |
| Maibenben     | MaiBook X series            | [5f97e34b20](https://linux-hardware.org/?probe=5f97e34b20) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [cc7ea9df99](https://linux-hardware.org/?probe=cc7ea9df99) | Apr 30, 2023 |
| Dell          | Vostro 15 3515              | [8f07407e1a](https://linux-hardware.org/?probe=8f07407e1a) | Apr 29, 2023 |
| HP            | Pavilion g6                 | [6d3e51b808](https://linux-hardware.org/?probe=6d3e51b808) | Apr 29, 2023 |
| ASUSTek       | GL702VMK                    | [a3c0cb6515](https://linux-hardware.org/?probe=a3c0cb6515) | Apr 29, 2023 |
| ASUSTek       | G56JR                       | [b7eb868ec4](https://linux-hardware.org/?probe=b7eb868ec4) | Apr 29, 2023 |
| HONOR         | HYM-WXX                     | [6923c4c1ce](https://linux-hardware.org/?probe=6923c4c1ce) | Apr 29, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [e6257e3e50](https://linux-hardware.org/?probe=e6257e3e50) | Apr 29, 2023 |
| Lenovo        | Unknown                     | [33a55a2347](https://linux-hardware.org/?probe=33a55a2347) | Apr 29, 2023 |
| Clevo         | E512xQ/E4129                | [7499c233c9](https://linux-hardware.org/?probe=7499c233c9) | Apr 29, 2023 |
| Dell          | Inspiron N5110              | [04da6f1db9](https://linux-hardware.org/?probe=04da6f1db9) | Apr 29, 2023 |
| HUAWEI        | BOM-WXX9                    | [b09f495645](https://linux-hardware.org/?probe=b09f495645) | Apr 29, 2023 |
| HUAWEI        | BOM-WXX9                    | [a69dab4a99](https://linux-hardware.org/?probe=a69dab4a99) | Apr 29, 2023 |
| Notebook      | W250EGQ / W270EGQ           | [f25ef6f165](https://linux-hardware.org/?probe=f25ef6f165) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | [a27eb72e94](https://linux-hardware.org/?probe=a27eb72e94) | Apr 29, 2023 |
| Notebook      | W250EGQ / W270EGQ           | [e4ab273aac](https://linux-hardware.org/?probe=e4ab273aac) | Apr 29, 2023 |
| HP            | 250 G7 Notebook PC          | [e5fe9aa407](https://linux-hardware.org/?probe=e5fe9aa407) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | [f2f50094ba](https://linux-hardware.org/?probe=f2f50094ba) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | [f089770d02](https://linux-hardware.org/?probe=f089770d02) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | [89f52ca147](https://linux-hardware.org/?probe=89f52ca147) | Apr 28, 2023 |
| Aquarius      | NS585                       | [b23696ca41](https://linux-hardware.org/?probe=b23696ca41) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3059eade71](https://linux-hardware.org/?probe=3059eade71) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e665e9d318](https://linux-hardware.org/?probe=e665e9d318) | Apr 28, 2023 |
| Valve         | Jupiter                     | [583e105bbf](https://linux-hardware.org/?probe=583e105bbf) | Apr 28, 2023 |
| MSI           | Katana GF66 12UGS           | [3607ee704e](https://linux-hardware.org/?probe=3607ee704e) | Apr 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [e0ef7894af](https://linux-hardware.org/?probe=e0ef7894af) | Apr 28, 2023 |
| Acer          | Aspire 5935                 | [9dfeeff104](https://linux-hardware.org/?probe=9dfeeff104) | Apr 28, 2023 |
| ASUSTek       | GL702VMK                    | [5df53b9f76](https://linux-hardware.org/?probe=5df53b9f76) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [539369db0e](https://linux-hardware.org/?probe=539369db0e) | Apr 28, 2023 |
| Valve         | Jupiter                     | [37534616d7](https://linux-hardware.org/?probe=37534616d7) | Apr 27, 2023 |
| Acer          | Swift SF314-43              | [9ca9aedf16](https://linux-hardware.org/?probe=9ca9aedf16) | Apr 27, 2023 |
| Dell          | Latitude D531               | [a6f2e7170f](https://linux-hardware.org/?probe=a6f2e7170f) | Apr 27, 2023 |
| Dell          | Inspiron N5110              | [2a40d09c1a](https://linux-hardware.org/?probe=2a40d09c1a) | Apr 27, 2023 |
| Lenovo        | B590 20208                  | [912acd510d](https://linux-hardware.org/?probe=912acd510d) | Apr 27, 2023 |
| HP            | Laptop 15-bw0xx             | [387eecc18e](https://linux-hardware.org/?probe=387eecc18e) | Apr 27, 2023 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [e207848340](https://linux-hardware.org/?probe=e207848340) | Apr 27, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [dcc8c22535](https://linux-hardware.org/?probe=dcc8c22535) | Apr 27, 2023 |
| Dell          | Inspiron N5010              | [78b4f0cd2f](https://linux-hardware.org/?probe=78b4f0cd2f) | Apr 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [a6845d78e4](https://linux-hardware.org/?probe=a6845d78e4) | Apr 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [640a71aea3](https://linux-hardware.org/?probe=640a71aea3) | Apr 27, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [e61f528ba5](https://linux-hardware.org/?probe=e61f528ba5) | Apr 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [2093399e21](https://linux-hardware.org/?probe=2093399e21) | Apr 27, 2023 |
| Acer          | Aspire 5720G                | [f566395f99](https://linux-hardware.org/?probe=f566395f99) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [67288f740c](https://linux-hardware.org/?probe=67288f740c) | Apr 27, 2023 |
| ASUSTek       | N750JV                      | [3ec3c7aa7b](https://linux-hardware.org/?probe=3ec3c7aa7b) | Apr 26, 2023 |
| ASUSTek       | N750JV                      | [53c0f79af9](https://linux-hardware.org/?probe=53c0f79af9) | Apr 26, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [cec3a72c8a](https://linux-hardware.org/?probe=cec3a72c8a) | Apr 26, 2023 |
| ASUSTek       | K501UX                      | [3f46fa9a68](https://linux-hardware.org/?probe=3f46fa9a68) | Apr 26, 2023 |
| Timi          | RedmiBook Pro 15S           | [7153e7fbe0](https://linux-hardware.org/?probe=7153e7fbe0) | Apr 26, 2023 |
| Clevo         | NL41MU2                     | [4f2ffb4273](https://linux-hardware.org/?probe=4f2ffb4273) | Apr 26, 2023 |
| Acer          | Aspire 5935                 | [0430d21b33](https://linux-hardware.org/?probe=0430d21b33) | Apr 26, 2023 |
| Fujitsu Si... | AMILO Pro V2085             | [d577e7c1e8](https://linux-hardware.org/?probe=d577e7c1e8) | Apr 26, 2023 |
| Sony          | SVE1512K1RW                 | [521db31dfc](https://linux-hardware.org/?probe=521db31dfc) | Apr 26, 2023 |
| HP            | Pavilion g6                 | [e1b7d44502](https://linux-hardware.org/?probe=e1b7d44502) | Apr 26, 2023 |
| Unknown       | Unknown                     | [208f6823ed](https://linux-hardware.org/?probe=208f6823ed) | Apr 26, 2023 |
| Dell          | Inspiron 5748               | [dd4d50839d](https://linux-hardware.org/?probe=dd4d50839d) | Apr 25, 2023 |
| Lenovo        | IdeaPad S110 20126          | [4defb36760](https://linux-hardware.org/?probe=4defb36760) | Apr 25, 2023 |
| Dell          | XPS 13 9310                 | [b9bc4703a8](https://linux-hardware.org/?probe=b9bc4703a8) | Apr 25, 2023 |
| Aquarius      | NS585                       | [a0983c89d8](https://linux-hardware.org/?probe=a0983c89d8) | Apr 25, 2023 |
| Aquarius      | NS585                       | [5d9edb6ed4](https://linux-hardware.org/?probe=5d9edb6ed4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [972d7f6e4a](https://linux-hardware.org/?probe=972d7f6e4a) | Apr 25, 2023 |
| Aquarius      | NS585                       | [c89bbd8bc0](https://linux-hardware.org/?probe=c89bbd8bc0) | Apr 25, 2023 |
| Aquarius      | NS585                       | [a6e5a5f3d1](https://linux-hardware.org/?probe=a6e5a5f3d1) | Apr 25, 2023 |
| Aquarius      | NS585                       | [b6dac5b058](https://linux-hardware.org/?probe=b6dac5b058) | Apr 25, 2023 |
| Aquarius      | NS585                       | [1563889dac](https://linux-hardware.org/?probe=1563889dac) | Apr 25, 2023 |
| Aquarius      | NS585                       | [9bdbad2ab7](https://linux-hardware.org/?probe=9bdbad2ab7) | Apr 25, 2023 |
| Aquarius      | NS585                       | [e30d7dde7b](https://linux-hardware.org/?probe=e30d7dde7b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [68527a900f](https://linux-hardware.org/?probe=68527a900f) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ce99b27fb4](https://linux-hardware.org/?probe=ce99b27fb4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [fc377acae2](https://linux-hardware.org/?probe=fc377acae2) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ed32f24d6e](https://linux-hardware.org/?probe=ed32f24d6e) | Apr 25, 2023 |
| HUAWEI        | CREM-WXX9                   | [fe2d361db9](https://linux-hardware.org/?probe=fe2d361db9) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ea60267a5b](https://linux-hardware.org/?probe=ea60267a5b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [f71897bf76](https://linux-hardware.org/?probe=f71897bf76) | Apr 25, 2023 |
| Aquarius      | NS585                       | [7aa4561ca5](https://linux-hardware.org/?probe=7aa4561ca5) | Apr 25, 2023 |
| Aquarius      | NS585                       | [385ce8cd93](https://linux-hardware.org/?probe=385ce8cd93) | Apr 25, 2023 |
| Aquarius      | NS585                       | [3fc8926a1a](https://linux-hardware.org/?probe=3fc8926a1a) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [3a7c24a13f](https://linux-hardware.org/?probe=3a7c24a13f) | Apr 25, 2023 |
| Lenovo        | IdeaPad Z580                | [ad5a6d474b](https://linux-hardware.org/?probe=ad5a6d474b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [58306d0266](https://linux-hardware.org/?probe=58306d0266) | Apr 25, 2023 |
| ICL           | RAYbook Si1512              | [6aa907fd2e](https://linux-hardware.org/?probe=6aa907fd2e) | Apr 25, 2023 |
| Notebook      | W650EH                      | [8e848e589e](https://linux-hardware.org/?probe=8e848e589e) | Apr 25, 2023 |
| ICL           | RAYbook Si1512              | [4e960cbe90](https://linux-hardware.org/?probe=4e960cbe90) | Apr 24, 2023 |
| HP            | ProBook 4520s               | [b680525b61](https://linux-hardware.org/?probe=b680525b61) | Apr 24, 2023 |
| HP            | ProBook 4520s               | [e4ce7aed55](https://linux-hardware.org/?probe=e4ce7aed55) | Apr 24, 2023 |
| Lenovo        | G560 20042                  | [af88bff29f](https://linux-hardware.org/?probe=af88bff29f) | Apr 24, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [52086c894a](https://linux-hardware.org/?probe=52086c894a) | Apr 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS16G0... | [b019f5af89](https://linux-hardware.org/?probe=b019f5af89) | Apr 24, 2023 |
| Panasonic     | CF-19RHSC8FN                | [cef5165f9c](https://linux-hardware.org/?probe=cef5165f9c) | Apr 23, 2023 |
| HP            | Pavilion g6                 | [1ca41a3608](https://linux-hardware.org/?probe=1ca41a3608) | Apr 23, 2023 |
| Acer          | Aspire A515-57              | [23f076b6d3](https://linux-hardware.org/?probe=23f076b6d3) | Apr 23, 2023 |
| HUAWEI        | KLVC-WXX9                   | [911f7932cc](https://linux-hardware.org/?probe=911f7932cc) | Apr 23, 2023 |
| Acer          | Aspire A315-56              | [5efcb6cf5d](https://linux-hardware.org/?probe=5efcb6cf5d) | Apr 23, 2023 |
| ASUSTek       | UX310UA                     | [a7b628ab1c](https://linux-hardware.org/?probe=a7b628ab1c) | Apr 23, 2023 |
| ASUSTek       | X550CC                      | [f51db9e4de](https://linux-hardware.org/?probe=f51db9e4de) | Apr 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [803d0798f1](https://linux-hardware.org/?probe=803d0798f1) | Apr 22, 2023 |
| ASUSTek       | X551CAP                     | [96dc0b9b7c](https://linux-hardware.org/?probe=96dc0b9b7c) | Apr 22, 2023 |
| Lenovo        | G560 20042                  | [29bfcf59fa](https://linux-hardware.org/?probe=29bfcf59fa) | Apr 22, 2023 |
| MSI           | GP60 2OD                    | [3504850973](https://linux-hardware.org/?probe=3504850973) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [dae63185d5](https://linux-hardware.org/?probe=dae63185d5) | Apr 21, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [40aaf19667](https://linux-hardware.org/?probe=40aaf19667) | Apr 21, 2023 |
| Valve         | Jupiter                     | [9091e5efc9](https://linux-hardware.org/?probe=9091e5efc9) | Apr 21, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [8a1e6b7f32](https://linux-hardware.org/?probe=8a1e6b7f32) | Apr 21, 2023 |
| Clevo         | NL41MU2                     | [2f1b310ca2](https://linux-hardware.org/?probe=2f1b310ca2) | Apr 21, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [3fd583ee9b](https://linux-hardware.org/?probe=3fd583ee9b) | Apr 21, 2023 |
| HP            | Compaq 6720s                | [b980c3c57d](https://linux-hardware.org/?probe=b980c3c57d) | Apr 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0658934d69](https://linux-hardware.org/?probe=0658934d69) | Apr 21, 2023 |
| MSI           | Katana GF66 12UE            | [77725a70a4](https://linux-hardware.org/?probe=77725a70a4) | Apr 21, 2023 |
| Infinix       | INBOOK X2 GEN11             | [cac51ecb89](https://linux-hardware.org/?probe=cac51ecb89) | Apr 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ce992e6160](https://linux-hardware.org/?probe=ce992e6160) | Apr 20, 2023 |
| Infinix       | INBOOK X2 GEN11             | [7fea1a73bc](https://linux-hardware.org/?probe=7fea1a73bc) | Apr 20, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [832f9d1bcf](https://linux-hardware.org/?probe=832f9d1bcf) | Apr 20, 2023 |
| Acer          | Aspire One 721              | [672386bd50](https://linux-hardware.org/?probe=672386bd50) | Apr 20, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [9c780361aa](https://linux-hardware.org/?probe=9c780361aa) | Apr 20, 2023 |
| Toshiba       | Satellite X200              | [15035835d0](https://linux-hardware.org/?probe=15035835d0) | Apr 20, 2023 |
| Dell          | Latitude E7470              | [5695d0ab66](https://linux-hardware.org/?probe=5695d0ab66) | Apr 20, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [3d88744f22](https://linux-hardware.org/?probe=3d88744f22) | Apr 20, 2023 |
| HP            | Notebook                    | [7174065ed3](https://linux-hardware.org/?probe=7174065ed3) | Apr 20, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [30caba94a4](https://linux-hardware.org/?probe=30caba94a4) | Apr 20, 2023 |
| Aquarius      | NS585                       | [753222f54f](https://linux-hardware.org/?probe=753222f54f) | Apr 20, 2023 |
| Aquarius      | NS585                       | [be0bc2be01](https://linux-hardware.org/?probe=be0bc2be01) | Apr 20, 2023 |
| Aquarius      | NS585                       | [f7f0464c39](https://linux-hardware.org/?probe=f7f0464c39) | Apr 20, 2023 |
| Aquarius      | NS585                       | [8393642230](https://linux-hardware.org/?probe=8393642230) | Apr 20, 2023 |
| Aquarius      | NS585                       | [a5b9a09e63](https://linux-hardware.org/?probe=a5b9a09e63) | Apr 20, 2023 |
| Lenovo        | ThinkPad T500 2055WAB       | [4e293261bb](https://linux-hardware.org/?probe=4e293261bb) | Apr 19, 2023 |
| ASUSTek       | A8Le                        | [3e4df24741](https://linux-hardware.org/?probe=3e4df24741) | Apr 19, 2023 |
| Valve         | Jupiter                     | [a1a3404a4d](https://linux-hardware.org/?probe=a1a3404a4d) | Apr 19, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [017d095061](https://linux-hardware.org/?probe=017d095061) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d669bcc680](https://linux-hardware.org/?probe=d669bcc680) | Apr 19, 2023 |
| Acer          | Aspire 5930                 | [0bca303d94](https://linux-hardware.org/?probe=0bca303d94) | Apr 19, 2023 |
| Acer          | Aspire 5930                 | [af833465b4](https://linux-hardware.org/?probe=af833465b4) | Apr 19, 2023 |
| ASUSTek       | X75VC                       | [68e8f66056](https://linux-hardware.org/?probe=68e8f66056) | Apr 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [cb5a9be901](https://linux-hardware.org/?probe=cb5a9be901) | Apr 19, 2023 |
| Lenovo        | ThinkPad P70 20ESS0TW00     | [42b45f646d](https://linux-hardware.org/?probe=42b45f646d) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| HUAWEI        | NBD-WXX9                    | [a55a03e648](https://linux-hardware.org/?probe=a55a03e648) | Apr 19, 2023 |
| Clevo         | M7x0K                       | [70cb3d8a2a](https://linux-hardware.org/?probe=70cb3d8a2a) | Apr 19, 2023 |
| HP            | 255 G8 Notebook PC          | [699e2a2a80](https://linux-hardware.org/?probe=699e2a2a80) | Apr 18, 2023 |
| Lenovo        | IdeaPad Y570 20091          | [14e15479a1](https://linux-hardware.org/?probe=14e15479a1) | Apr 18, 2023 |
| Acer          | Aspire E5-575G              | [26bce7ac33](https://linux-hardware.org/?probe=26bce7ac33) | Apr 18, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [7f0be1868e](https://linux-hardware.org/?probe=7f0be1868e) | Apr 18, 2023 |
| ASUSTek       | K40AF                       | [f3e1d56dbc](https://linux-hardware.org/?probe=f3e1d56dbc) | Apr 18, 2023 |
| HP            | Pavilion 15                 | [ae147077b1](https://linux-hardware.org/?probe=ae147077b1) | Apr 18, 2023 |
| Lenovo        | B50-30 20382                | [d8995dacdc](https://linux-hardware.org/?probe=d8995dacdc) | Apr 18, 2023 |
| Acer          | Aspire A315-42G             | [aff8d7f5d9](https://linux-hardware.org/?probe=aff8d7f5d9) | Apr 18, 2023 |
| Acer          | Aspire A315-34              | [06332b53b1](https://linux-hardware.org/?probe=06332b53b1) | Apr 18, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [65a5b3f43d](https://linux-hardware.org/?probe=65a5b3f43d) | Apr 17, 2023 |
| Lenovo        | G580                        | [e291c2c0aa](https://linux-hardware.org/?probe=e291c2c0aa) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [909a9c8c45](https://linux-hardware.org/?probe=909a9c8c45) | Apr 17, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [5e265fd8e1](https://linux-hardware.org/?probe=5e265fd8e1) | Apr 16, 2023 |
| Acer          | Extensa 4220                | [65c0e4f901](https://linux-hardware.org/?probe=65c0e4f901) | Apr 16, 2023 |
| Digma         | EVE 11 C422 ES1068EW        | [8f62352864](https://linux-hardware.org/?probe=8f62352864) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2fcbae14f2](https://linux-hardware.org/?probe=2fcbae14f2) | Apr 16, 2023 |
| Acer          | Nitro AN515-46              | [502263c435](https://linux-hardware.org/?probe=502263c435) | Apr 15, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [a08b6e5824](https://linux-hardware.org/?probe=a08b6e5824) | Apr 15, 2023 |
| Dell          | Inspiron N5110              | [4f65d649d9](https://linux-hardware.org/?probe=4f65d649d9) | Apr 15, 2023 |
| Dell          | Inspiron MM061              | [b825c609a9](https://linux-hardware.org/?probe=b825c609a9) | Apr 15, 2023 |
| Acer          | Aspire A515-57              | [ecc22845f7](https://linux-hardware.org/?probe=ecc22845f7) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [162ef2f577](https://linux-hardware.org/?probe=162ef2f577) | Apr 15, 2023 |
| HP            | Stream Laptop 11-aj0xxx     | [47521a22ef](https://linux-hardware.org/?probe=47521a22ef) | Apr 15, 2023 |
| 3Logic Gro... | Graviton N15i               | [12b7711444](https://linux-hardware.org/?probe=12b7711444) | Apr 15, 2023 |
| HP            | EliteBook 8470p             | [69cb1a0781](https://linux-hardware.org/?probe=69cb1a0781) | Apr 15, 2023 |
| 3Logic Gro... | Graviton N15i               | [a61925937f](https://linux-hardware.org/?probe=a61925937f) | Apr 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | [6bb9c3439d](https://linux-hardware.org/?probe=6bb9c3439d) | Apr 15, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [510bfe2f94](https://linux-hardware.org/?probe=510bfe2f94) | Apr 15, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [0a63354640](https://linux-hardware.org/?probe=0a63354640) | Apr 15, 2023 |
| ASUSTek       | M51Vr                       | [27d265c73d](https://linux-hardware.org/?probe=27d265c73d) | Apr 15, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [1ed54f4477](https://linux-hardware.org/?probe=1ed54f4477) | Apr 15, 2023 |
| HP            | EliteBook 2540p             | [de07820409](https://linux-hardware.org/?probe=de07820409) | Apr 15, 2023 |
| HONOR         | HYM-WXX                     | [109b28f217](https://linux-hardware.org/?probe=109b28f217) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ca241d00f8](https://linux-hardware.org/?probe=ca241d00f8) | Apr 15, 2023 |
| Acer          | Aspire A515-55              | [18414177a2](https://linux-hardware.org/?probe=18414177a2) | Apr 15, 2023 |
| Digma         | EVE 11 C422 ES1068EW        | [a5cce02e71](https://linux-hardware.org/?probe=a5cce02e71) | Apr 14, 2023 |
| Notebook      | W65_67SH                    | [d84563301e](https://linux-hardware.org/?probe=d84563301e) | Apr 14, 2023 |
| Acer          | Swift SF114-34              | [45d963eb7c](https://linux-hardware.org/?probe=45d963eb7c) | Apr 14, 2023 |
| Haier         | U1520HD                     | [3084c84bb6](https://linux-hardware.org/?probe=3084c84bb6) | Apr 14, 2023 |
| HUAWEI        | BOM-WXX9                    | [04eead074d](https://linux-hardware.org/?probe=04eead074d) | Apr 14, 2023 |
| HUAWEI        | HLY-WX9XX                   | [d0742654bb](https://linux-hardware.org/?probe=d0742654bb) | Apr 14, 2023 |
| HP            | ProBook 430 G6              | [9a4bce918e](https://linux-hardware.org/?probe=9a4bce918e) | Apr 14, 2023 |
| Lenovo        | G505 20240                  | [62bdfa97bd](https://linux-hardware.org/?probe=62bdfa97bd) | Apr 14, 2023 |
| Dell          | Latitude E7250              | [a6f30c1df5](https://linux-hardware.org/?probe=a6f30c1df5) | Apr 13, 2023 |
| Unchartevi... | 6540                        | [b2acb1d64c](https://linux-hardware.org/?probe=b2acb1d64c) | Apr 13, 2023 |
| Sony          | VGN-NW24MR                  | [3325bb2781](https://linux-hardware.org/?probe=3325bb2781) | Apr 13, 2023 |
| ASUSTek       | K73TA                       | [34319e673a](https://linux-hardware.org/?probe=34319e673a) | Apr 13, 2023 |
| 3Logic Gro... | Graviton N15i-K2            | [7b75b7b08e](https://linux-hardware.org/?probe=7b75b7b08e) | Apr 13, 2023 |
| HUAWEI        | HN-WX9X                     | [20c6c9b49a](https://linux-hardware.org/?probe=20c6c9b49a) | Apr 13, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [fa8b03b686](https://linux-hardware.org/?probe=fa8b03b686) | Apr 13, 2023 |
| Acer          | Extensa 2519                | [8a555b0d7b](https://linux-hardware.org/?probe=8a555b0d7b) | Apr 13, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | [ea97cd752d](https://linux-hardware.org/?probe=ea97cd752d) | Apr 13, 2023 |
| Acer          | Aspire E5-771G              | [504d600530](https://linux-hardware.org/?probe=504d600530) | Apr 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [da97aa7885](https://linux-hardware.org/?probe=da97aa7885) | Apr 13, 2023 |
| HONOR         | HYM-WXX                     | [ab8722ddde](https://linux-hardware.org/?probe=ab8722ddde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [5f9d78ce70](https://linux-hardware.org/?probe=5f9d78ce70) | Apr 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [2ecd45a19e](https://linux-hardware.org/?probe=2ecd45a19e) | Apr 13, 2023 |
| Unknown       | Unknown                     | [3637a41ac7](https://linux-hardware.org/?probe=3637a41ac7) | Apr 13, 2023 |
| Acer          | Aspire A515-57G             | [73893f31b6](https://linux-hardware.org/?probe=73893f31b6) | Apr 12, 2023 |
| HUAWEI        | HLYL-WXX9                   | [db51c5a1f3](https://linux-hardware.org/?probe=db51c5a1f3) | Apr 12, 2023 |
| MSI           | Prestige 14Evo B13M         | [8ded60277f](https://linux-hardware.org/?probe=8ded60277f) | Apr 12, 2023 |
| Acer          | Aspire E1-572G              | [6321e44a81](https://linux-hardware.org/?probe=6321e44a81) | Apr 12, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [49101ad22b](https://linux-hardware.org/?probe=49101ad22b) | Apr 12, 2023 |
| Dell          | Inspiron N5110              | [38bace81f3](https://linux-hardware.org/?probe=38bace81f3) | Apr 12, 2023 |
| Toshiba       | Satellite A100              | [064df21bd6](https://linux-hardware.org/?probe=064df21bd6) | Apr 12, 2023 |
| MSI           | Prestige 14Evo B13M         | [f1cafa77dd](https://linux-hardware.org/?probe=f1cafa77dd) | Apr 12, 2023 |
| ASUSTek       | UX31E                       | [ef65b0b616](https://linux-hardware.org/?probe=ef65b0b616) | Apr 12, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [80c85e1b7c](https://linux-hardware.org/?probe=80c85e1b7c) | Apr 11, 2023 |
| Samsung       | R460                        | [9908964d4a](https://linux-hardware.org/?probe=9908964d4a) | Apr 11, 2023 |
| ASUSTek       | X555LJ                      | [a2ac7579a9](https://linux-hardware.org/?probe=a2ac7579a9) | Apr 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS16G0... | [220a0048d6](https://linux-hardware.org/?probe=220a0048d6) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [10da0191c4](https://linux-hardware.org/?probe=10da0191c4) | Apr 11, 2023 |
| Lenovo        | IdeaPad Z470                | [2348aee3d4](https://linux-hardware.org/?probe=2348aee3d4) | Apr 11, 2023 |
| ASUSTek       | K50IJ                       | [3d7c179225](https://linux-hardware.org/?probe=3d7c179225) | Apr 11, 2023 |
| Sony          | VPCSB2A7R                   | [1620c38937](https://linux-hardware.org/?probe=1620c38937) | Apr 11, 2023 |
| Dell          | Inspiron ME051              | [ea73cc4553](https://linux-hardware.org/?probe=ea73cc4553) | Apr 11, 2023 |
| ASUSTek       | X51RL                       | [ca3fb7f6d5](https://linux-hardware.org/?probe=ca3fb7f6d5) | Apr 11, 2023 |
| Clevo         | NL41MU2                     | [322f62ae77](https://linux-hardware.org/?probe=322f62ae77) | Apr 11, 2023 |
| Aquarius      | NS585                       | [6f4b987640](https://linux-hardware.org/?probe=6f4b987640) | Apr 11, 2023 |
| MACHENIKE     | S16                         | [29c566f7b3](https://linux-hardware.org/?probe=29c566f7b3) | Apr 11, 2023 |
| Lenovo        | B590 20206                  | [5aad144224](https://linux-hardware.org/?probe=5aad144224) | Apr 11, 2023 |
| Dell          | Latitude 5511               | [fa30633c71](https://linux-hardware.org/?probe=fa30633c71) | Apr 11, 2023 |
| ASUSTek       | 1011PX                      | [77bd102d23](https://linux-hardware.org/?probe=77bd102d23) | Apr 11, 2023 |
| ASUSTek       | ZenBook UX481FL_UX481FL     | [4a7c0965bd](https://linux-hardware.org/?probe=4a7c0965bd) | Apr 11, 2023 |
| Acer          | Aspire V3-571G              | [bd013771db](https://linux-hardware.org/?probe=bd013771db) | Apr 10, 2023 |
| Intel         | Unknown                     | [2f7f544903](https://linux-hardware.org/?probe=2f7f544903) | Apr 10, 2023 |
| Clevo         | NL41MU2                     | [720eed31f6](https://linux-hardware.org/?probe=720eed31f6) | Apr 10, 2023 |
| ASUSTek       | UX303UB                     | [f94b0ee950](https://linux-hardware.org/?probe=f94b0ee950) | Apr 10, 2023 |
| Lenovo        | B590 20206                  | [527adf79f4](https://linux-hardware.org/?probe=527adf79f4) | Apr 10, 2023 |
| Unknown       | Unknown                     | [c959a62e36](https://linux-hardware.org/?probe=c959a62e36) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| Acer          | Extensa 2519                | [cd402c5753](https://linux-hardware.org/?probe=cd402c5753) | Apr 09, 2023 |
| Acer          | Extensa 4220                | [32504ab636](https://linux-hardware.org/?probe=32504ab636) | Apr 09, 2023 |
| ASUSTek       | K50IJ                       | [b829712e0d](https://linux-hardware.org/?probe=b829712e0d) | Apr 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | [3ef5fb8adc](https://linux-hardware.org/?probe=3ef5fb8adc) | Apr 09, 2023 |
| Lenovo        | ThinkPad T440s 20ARS16G0... | [5e9063a3a3](https://linux-hardware.org/?probe=5e9063a3a3) | Apr 09, 2023 |
| DEXP          | Aquilon C15                 | [3f921dc410](https://linux-hardware.org/?probe=3f921dc410) | Apr 09, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [05a8a1a4c7](https://linux-hardware.org/?probe=05a8a1a4c7) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [5a4d307476](https://linux-hardware.org/?probe=5a4d307476) | Apr 09, 2023 |
| Lenovo        | ThinkPad T440s 20ARS16G0... | [50ecb24abc](https://linux-hardware.org/?probe=50ecb24abc) | Apr 08, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [a334fb8e82](https://linux-hardware.org/?probe=a334fb8e82) | Apr 08, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [c06058447c](https://linux-hardware.org/?probe=c06058447c) | Apr 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [47b0256864](https://linux-hardware.org/?probe=47b0256864) | Apr 08, 2023 |
| ASUSTek       | K53TA                       | [94ce67f7d9](https://linux-hardware.org/?probe=94ce67f7d9) | Apr 08, 2023 |
| MSI           | GL65 Leopard 10SCSR         | [3063414a8c](https://linux-hardware.org/?probe=3063414a8c) | Apr 08, 2023 |
| HONOR         | BMH-WCX9                    | [2082d3c772](https://linux-hardware.org/?probe=2082d3c772) | Apr 08, 2023 |
| ICL           | RAYbook Si1512              | [1dd919f7ff](https://linux-hardware.org/?probe=1dd919f7ff) | Apr 08, 2023 |
| HP            | Pavilion dv6                | [5fddb7053d](https://linux-hardware.org/?probe=5fddb7053d) | Apr 07, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [426fcd7ee1](https://linux-hardware.org/?probe=426fcd7ee1) | Apr 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [0477a89130](https://linux-hardware.org/?probe=0477a89130) | Apr 07, 2023 |
| ASUSTek       | A8Le                        | [c00ff94698](https://linux-hardware.org/?probe=c00ff94698) | Apr 07, 2023 |
| HP            | Pavilion 17                 | [43d7593dd5](https://linux-hardware.org/?probe=43d7593dd5) | Apr 07, 2023 |
| HP            | ProBook 450 G6              | [08eb1670cd](https://linux-hardware.org/?probe=08eb1670cd) | Apr 07, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [8c1127cfab](https://linux-hardware.org/?probe=8c1127cfab) | Apr 07, 2023 |
| Dell          | Vostro 5391                 | [aaa8e31af8](https://linux-hardware.org/?probe=aaa8e31af8) | Apr 07, 2023 |
| Unknown       | Unknown                     | [70ff15284b](https://linux-hardware.org/?probe=70ff15284b) | Apr 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [ce99d19d7c](https://linux-hardware.org/?probe=ce99d19d7c) | Apr 07, 2023 |
| Acer          | Swift SF314-41G             | [9906ab0e8b](https://linux-hardware.org/?probe=9906ab0e8b) | Apr 07, 2023 |
| HP            | ProBook 6450b               | [f3c04ce75f](https://linux-hardware.org/?probe=f3c04ce75f) | Apr 06, 2023 |
| Clevo         | M815P                       | [e5194b9fea](https://linux-hardware.org/?probe=e5194b9fea) | Apr 06, 2023 |
| Unknown       | Unknown                     | [9a068872f6](https://linux-hardware.org/?probe=9a068872f6) | Apr 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | [e9b2a1fa5d](https://linux-hardware.org/?probe=e9b2a1fa5d) | Apr 05, 2023 |
| HP            | Pavilion dv6                | [67615ec9ff](https://linux-hardware.org/?probe=67615ec9ff) | Apr 05, 2023 |
| Acer          | Nitro AN515-46              | [6611343c84](https://linux-hardware.org/?probe=6611343c84) | Apr 05, 2023 |
| Acer          | Nitro AN515-46              | [1dcee27dff](https://linux-hardware.org/?probe=1dcee27dff) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a02839d653](https://linux-hardware.org/?probe=a02839d653) | Apr 05, 2023 |
| MSI           | Katana GF66 12UE            | [5114a5bd7a](https://linux-hardware.org/?probe=5114a5bd7a) | Apr 05, 2023 |
| eMachines     | eME728                      | [aff08e7f2d](https://linux-hardware.org/?probe=aff08e7f2d) | Apr 05, 2023 |
| HUAWEI        | NDZ-WXX9                    | [707d59612f](https://linux-hardware.org/?probe=707d59612f) | Apr 05, 2023 |
| HUAWEI        | NDZ-WXX9                    | [058290755b](https://linux-hardware.org/?probe=058290755b) | Apr 05, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9d621102fd](https://linux-hardware.org/?probe=9d621102fd) | Apr 05, 2023 |
| Acer          | Aspire A114-33              | [ad4bc7aa94](https://linux-hardware.org/?probe=ad4bc7aa94) | Apr 05, 2023 |
| Dell          | Vostro 5481                 | [3754935440](https://linux-hardware.org/?probe=3754935440) | Apr 05, 2023 |
| Acer          | Acadia V1.45                | [8aa933f692](https://linux-hardware.org/?probe=8aa933f692) | Apr 05, 2023 |
| Sony          | VGN-CS31MR_P                | [c97f0353d0](https://linux-hardware.org/?probe=c97f0353d0) | Apr 05, 2023 |
| MSI           | Creator Z16 A12UET          | [240fb67b93](https://linux-hardware.org/?probe=240fb67b93) | Apr 05, 2023 |
| TPS           | C48P                        | [df8a2ac617](https://linux-hardware.org/?probe=df8a2ac617) | Apr 04, 2023 |
| Timi          | TM1701                      | [5fc6e30961](https://linux-hardware.org/?probe=5fc6e30961) | Apr 04, 2023 |
| Acer          | AO756                       | [4e33479949](https://linux-hardware.org/?probe=4e33479949) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7d54e77534](https://linux-hardware.org/?probe=7d54e77534) | Apr 04, 2023 |
| HP            | ProBook 4525s               | [164d8993b4](https://linux-hardware.org/?probe=164d8993b4) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | [858597558c](https://linux-hardware.org/?probe=858597558c) | Apr 03, 2023 |
| HUAWEI        | CREM-WXX9                   | [dd3c0ff2e5](https://linux-hardware.org/?probe=dd3c0ff2e5) | Apr 03, 2023 |
| HUAWEI        | HVY-WXX9                    | [7b761dc41f](https://linux-hardware.org/?probe=7b761dc41f) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [28652ebe9b](https://linux-hardware.org/?probe=28652ebe9b) | Apr 03, 2023 |
| MSI           | GE72 6QC                    | [b697e393ac](https://linux-hardware.org/?probe=b697e393ac) | Apr 03, 2023 |
| ASUSTek       | A7U                         | [3828d5841d](https://linux-hardware.org/?probe=3828d5841d) | Apr 03, 2023 |
| Irbis         | NB283                       | [420a997036](https://linux-hardware.org/?probe=420a997036) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [0f4881cccf](https://linux-hardware.org/?probe=0f4881cccf) | Apr 03, 2023 |
| Lenovo        | B590 20208                  | [b48930da93](https://linux-hardware.org/?probe=b48930da93) | Apr 03, 2023 |
| Prestigio     | PSB133S01ZFH                | [ba6746febf](https://linux-hardware.org/?probe=ba6746febf) | Apr 03, 2023 |
| Lenovo        | ThinkPad Edge 0578A21       | [52a6bcc2f4](https://linux-hardware.org/?probe=52a6bcc2f4) | Apr 03, 2023 |
| Lenovo        | ThinkPad Edge 0578A21       | [26803a939c](https://linux-hardware.org/?probe=26803a939c) | Apr 03, 2023 |
| ASUSTek       | UX303UB                     | [9b46784fd5](https://linux-hardware.org/?probe=9b46784fd5) | Apr 02, 2023 |
| HP            | ProBook 4540s               | [9ace929040](https://linux-hardware.org/?probe=9ace929040) | Apr 02, 2023 |
| HP            | OMEN by Laptop              | [647c427d7b](https://linux-hardware.org/?probe=647c427d7b) | Apr 02, 2023 |
| ASUSTek       | X551CAP                     | [d197f4a99c](https://linux-hardware.org/?probe=d197f4a99c) | Apr 02, 2023 |
| HP            | ProBook 470 G0              | [64e05fac23](https://linux-hardware.org/?probe=64e05fac23) | Apr 01, 2023 |
| HUAWEI        | BOM-WXX9                    | [1113516797](https://linux-hardware.org/?probe=1113516797) | Apr 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [eb7bbd9b91](https://linux-hardware.org/?probe=eb7bbd9b91) | Apr 01, 2023 |
| HUAWEI        | HKD-WXX                     | [c0827316e3](https://linux-hardware.org/?probe=c0827316e3) | Apr 01, 2023 |
| HUAWEI        | HN-WX9X                     | [0769a4d107](https://linux-hardware.org/?probe=0769a4d107) | Apr 01, 2023 |
| MSI           | Sword 15 A12UE              | [3389b32105](https://linux-hardware.org/?probe=3389b32105) | Apr 01, 2023 |
| Haier         | A1410EM                     | [f772f1b9eb](https://linux-hardware.org/?probe=f772f1b9eb) | Apr 01, 2023 |
| Haier         | A1410EM                     | [709a07dd3c](https://linux-hardware.org/?probe=709a07dd3c) | Apr 01, 2023 |
| HP            | ProBook 6475b               | [680348d948](https://linux-hardware.org/?probe=680348d948) | Apr 01, 2023 |
| Acer          | Aspire V5-121               | [d6cc7a67ab](https://linux-hardware.org/?probe=d6cc7a67ab) | Apr 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [96c53eccb0](https://linux-hardware.org/?probe=96c53eccb0) | Apr 01, 2023 |
| Unknown       | X133                        | [950572f119](https://linux-hardware.org/?probe=950572f119) | Apr 01, 2023 |
| ASUSTek       | F3JP                        | [e561213582](https://linux-hardware.org/?probe=e561213582) | Apr 01, 2023 |
| ASUSTek       | X550LB                      | [3d35ff8b68](https://linux-hardware.org/?probe=3d35ff8b68) | Apr 01, 2023 |
| Toshiba       | Satellite S50-A-K7M         | [af163d8ec3](https://linux-hardware.org/?probe=af163d8ec3) | Apr 01, 2023 |
| Sony          | VPCEH1S1R                   | [12100cdd4b](https://linux-hardware.org/?probe=12100cdd4b) | Apr 01, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [9db0830268](https://linux-hardware.org/?probe=9db0830268) | Apr 01, 2023 |
| HUAWEI        | NBD-WXX9                    | [d4c718bdab](https://linux-hardware.org/?probe=d4c718bdab) | Apr 01, 2023 |
| Lenovo        | ThinkPad X201s 514328U      | [011c475758](https://linux-hardware.org/?probe=011c475758) | Apr 01, 2023 |
| HP            | Pavilion dv7                | [00bbec023a](https://linux-hardware.org/?probe=00bbec023a) | Apr 01, 2023 |
| Dell          | XPS 17 9700                 | [5d0a908832](https://linux-hardware.org/?probe=5d0a908832) | Mar 31, 2023 |
| ASUSTek       | X202E                       | [cdcccb09e7](https://linux-hardware.org/?probe=cdcccb09e7) | Mar 31, 2023 |
| ASUSTek       | X202E                       | [ac12ec53a3](https://linux-hardware.org/?probe=ac12ec53a3) | Mar 31, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [66a1075056](https://linux-hardware.org/?probe=66a1075056) | Mar 31, 2023 |
| Fujitsu       | LIFEBOOK NH532              | [68a8171c0a](https://linux-hardware.org/?probe=68a8171c0a) | Mar 31, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [ad92e27c90](https://linux-hardware.org/?probe=ad92e27c90) | Mar 31, 2023 |
| ASUSTek       | K53SD                       | [81d03c3707](https://linux-hardware.org/?probe=81d03c3707) | Mar 31, 2023 |
| Chuwi         | CoreBook XPro               | [85ad17d246](https://linux-hardware.org/?probe=85ad17d246) | Mar 31, 2023 |
| HUAWEI        | HN-WX9X                     | [b10ed7894c](https://linux-hardware.org/?probe=b10ed7894c) | Mar 31, 2023 |
| ASUSTek       | GL502VMK                    | [fe7f43d2db](https://linux-hardware.org/?probe=fe7f43d2db) | Mar 31, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [36c0a38885](https://linux-hardware.org/?probe=36c0a38885) | Mar 31, 2023 |
| Dell          | Inspiron N5010              | [4d3e61950f](https://linux-hardware.org/?probe=4d3e61950f) | Mar 31, 2023 |
| ASUSTek       | X751LD                      | [2ef82331de](https://linux-hardware.org/?probe=2ef82331de) | Mar 31, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [54f8c5082d](https://linux-hardware.org/?probe=54f8c5082d) | Mar 31, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [36b3103f3f](https://linux-hardware.org/?probe=36b3103f3f) | Mar 31, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8228733171](https://linux-hardware.org/?probe=8228733171) | Mar 31, 2023 |
| ASUSTek       | K54C                        | [a2a91e2071](https://linux-hardware.org/?probe=a2a91e2071) | Mar 30, 2023 |
| HP            | Pavilion dv6                | [c91e4d9c5a](https://linux-hardware.org/?probe=c91e4d9c5a) | Mar 30, 2023 |
| ASUSTek       | X101H                       | [a8a30f0050](https://linux-hardware.org/?probe=a8a30f0050) | Mar 30, 2023 |
| HUAWEI        | KLVL-WXXW                   | [ab31f6f63d](https://linux-hardware.org/?probe=ab31f6f63d) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | [3844e429b1](https://linux-hardware.org/?probe=3844e429b1) | Mar 30, 2023 |
| ASUSTek       | K52JB                       | [45162c9123](https://linux-hardware.org/?probe=45162c9123) | Mar 30, 2023 |
| ASUSTek       | K52JB                       | [c19cd604b3](https://linux-hardware.org/?probe=c19cd604b3) | Mar 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8e7a5551df](https://linux-hardware.org/?probe=8e7a5551df) | Mar 30, 2023 |
| Acer          | Aspire E5-573G              | [d68a126b9b](https://linux-hardware.org/?probe=d68a126b9b) | Mar 30, 2023 |
| Toshiba       | Satellite Pro L300          | [04b9e48603](https://linux-hardware.org/?probe=04b9e48603) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | [fc942702db](https://linux-hardware.org/?probe=fc942702db) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | [ab5d4b339b](https://linux-hardware.org/?probe=ab5d4b339b) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | [d3eafe4568](https://linux-hardware.org/?probe=d3eafe4568) | Mar 30, 2023 |
| Dell          | Vostro 5468                 | [4ad7375ed0](https://linux-hardware.org/?probe=4ad7375ed0) | Mar 30, 2023 |
| Valve         | Jupiter                     | [cf4ac240c4](https://linux-hardware.org/?probe=cf4ac240c4) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7fedcc338](https://linux-hardware.org/?probe=d7fedcc338) | Mar 29, 2023 |
| Acer          | Aspire 5050                 | [689cd48886](https://linux-hardware.org/?probe=689cd48886) | Mar 29, 2023 |
| Dell          | Latitude 5420               | [aee5c648e7](https://linux-hardware.org/?probe=aee5c648e7) | Mar 29, 2023 |
| Clevo         | NL41MU2                     | [69abc76758](https://linux-hardware.org/?probe=69abc76758) | Mar 29, 2023 |
| Dell          | System Inspiron N7110       | [cc23cb7065](https://linux-hardware.org/?probe=cc23cb7065) | Mar 29, 2023 |
| Lenovo        | ThinkPad X201s 514328U      | [a6dbe138a5](https://linux-hardware.org/?probe=a6dbe138a5) | Mar 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [695a074faf](https://linux-hardware.org/?probe=695a074faf) | Mar 29, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | [607219699e](https://linux-hardware.org/?probe=607219699e) | Mar 29, 2023 |
| Timi          | TM1701                      | [16ca4bcb7f](https://linux-hardware.org/?probe=16ca4bcb7f) | Mar 29, 2023 |
| HONOR         | NBR-WAX9                    | [c0eeee7caf](https://linux-hardware.org/?probe=c0eeee7caf) | Mar 29, 2023 |
| Acer          | Aspire E1-571G              | [574f00dff5](https://linux-hardware.org/?probe=574f00dff5) | Mar 29, 2023 |
| Clevo         | M815P                       | [ac4eae2a0b](https://linux-hardware.org/?probe=ac4eae2a0b) | Mar 29, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [e9b1759970](https://linux-hardware.org/?probe=e9b1759970) | Mar 29, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6c61111706](https://linux-hardware.org/?probe=6c61111706) | Mar 28, 2023 |
| HP            | Pavilion Notebook           | [9cb1834208](https://linux-hardware.org/?probe=9cb1834208) | Mar 28, 2023 |
| Gateway       | LT27                        | [4697cead5f](https://linux-hardware.org/?probe=4697cead5f) | Mar 28, 2023 |
| THUNDEROBO... | 911 Plus                    | [6617ad47b7](https://linux-hardware.org/?probe=6617ad47b7) | Mar 28, 2023 |
| Pegatron      | H36QR                       | [a9f1036ba5](https://linux-hardware.org/?probe=a9f1036ba5) | Mar 28, 2023 |
| Pegatron      | H36QR                       | [c3cf444e89](https://linux-hardware.org/?probe=c3cf444e89) | Mar 28, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | [6e3a79c8b3](https://linux-hardware.org/?probe=6e3a79c8b3) | Mar 28, 2023 |
| MSI           | GE72 6QC                    | [6e593cf965](https://linux-hardware.org/?probe=6e593cf965) | Mar 28, 2023 |
| ASUSTek       | X751LD                      | [61382d0bd8](https://linux-hardware.org/?probe=61382d0bd8) | Mar 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d97a249a99](https://linux-hardware.org/?probe=d97a249a99) | Mar 28, 2023 |
| Aquarius      | NS685U R11                  | [ecd08ca6d1](https://linux-hardware.org/?probe=ecd08ca6d1) | Mar 28, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [b8a7f41c86](https://linux-hardware.org/?probe=b8a7f41c86) | Mar 28, 2023 |
| HP            | Compaq 6720s                | [9998cb9bfb](https://linux-hardware.org/?probe=9998cb9bfb) | Mar 27, 2023 |
| Acer          | Extensa 2530                | [e39fe56d67](https://linux-hardware.org/?probe=e39fe56d67) | Mar 27, 2023 |
| Acer          | NB-EX2510G-53DE             | [d331242786](https://linux-hardware.org/?probe=d331242786) | Mar 27, 2023 |
| HUAWEI        | NBD-WXX9                    | [e7788fd2a4](https://linux-hardware.org/?probe=e7788fd2a4) | Mar 27, 2023 |
| Haier         | P1510SD                     | [8bba4e9b5f](https://linux-hardware.org/?probe=8bba4e9b5f) | Mar 27, 2023 |
| HUAWEI        | NBD-WXX9                    | [d723ff0fa9](https://linux-hardware.org/?probe=d723ff0fa9) | Mar 27, 2023 |
| Pegatron      | A15                         | [2a0a6bdafc](https://linux-hardware.org/?probe=2a0a6bdafc) | Mar 27, 2023 |
| Dell          | Inspiron 5570               | [696a8c86bf](https://linux-hardware.org/?probe=696a8c86bf) | Mar 27, 2023 |
| MSI           | GE72 6QC                    | [e7c328a9f5](https://linux-hardware.org/?probe=e7c328a9f5) | Mar 27, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [580e3a1237](https://linux-hardware.org/?probe=580e3a1237) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [deb6990c19](https://linux-hardware.org/?probe=deb6990c19) | Mar 27, 2023 |
| Acer          | Aspire 5050                 | [8490dcc481](https://linux-hardware.org/?probe=8490dcc481) | Mar 27, 2023 |
| HONOR         | NBR-WAX9                    | [ef91ef3645](https://linux-hardware.org/?probe=ef91ef3645) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | [eded7b36b1](https://linux-hardware.org/?probe=eded7b36b1) | Mar 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [f5274197b8](https://linux-hardware.org/?probe=f5274197b8) | Mar 27, 2023 |
| Haier         | S15                         | [a75654fe8a](https://linux-hardware.org/?probe=a75654fe8a) | Mar 27, 2023 |
| Lenovo        | B460e                       | [1c79a13a61](https://linux-hardware.org/?probe=1c79a13a61) | Mar 27, 2023 |
| Clevo         | NL41MU2                     | [60191a33b8](https://linux-hardware.org/?probe=60191a33b8) | Mar 27, 2023 |
| MSI           | Katana GF76 11UE            | [b82e15f498](https://linux-hardware.org/?probe=b82e15f498) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | [9ee3ca41c8](https://linux-hardware.org/?probe=9ee3ca41c8) | Mar 27, 2023 |
| Sony          | VPCF13E8R                   | [a9c7f1d8bc](https://linux-hardware.org/?probe=a9c7f1d8bc) | Mar 27, 2023 |
| Dell          | Latitude E6430              | [ec464ade9c](https://linux-hardware.org/?probe=ec464ade9c) | Mar 27, 2023 |
| Acer          | Aspire V3-551               | [48409a7222](https://linux-hardware.org/?probe=48409a7222) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [85a8b8b452](https://linux-hardware.org/?probe=85a8b8b452) | Mar 26, 2023 |
| Packard Be... | EasyNote TE11HC             | [6c942c5a39](https://linux-hardware.org/?probe=6c942c5a39) | Mar 26, 2023 |
| MSI           | GE72 6QC                    | [83793f19c1](https://linux-hardware.org/?probe=83793f19c1) | Mar 26, 2023 |
| Acer          | Aspire E1-570G              | [9d123ef87d](https://linux-hardware.org/?probe=9d123ef87d) | Mar 26, 2023 |
| Gigabyte      | G5 KF                       | [5275b7d43a](https://linux-hardware.org/?probe=5275b7d43a) | Mar 26, 2023 |
| Dell          | Inspiron 3576               | [18352c181a](https://linux-hardware.org/?probe=18352c181a) | Mar 26, 2023 |
| Gigabyte      | G5 KF                       | [9dd2faffb3](https://linux-hardware.org/?probe=9dd2faffb3) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a7ff24abc4](https://linux-hardware.org/?probe=a7ff24abc4) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [8d5a135264](https://linux-hardware.org/?probe=8d5a135264) | Mar 26, 2023 |
| HUAWEI        | HN-WX9X                     | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| Samsung       | RV408/RV508                 | [5f5efa7edc](https://linux-hardware.org/?probe=5f5efa7edc) | Mar 25, 2023 |
| HP            | ProBook 430 G6              | [cd14b86548](https://linux-hardware.org/?probe=cd14b86548) | Mar 25, 2023 |
| Samsung       | RV408/RV508                 | [cce3fdd054](https://linux-hardware.org/?probe=cce3fdd054) | Mar 25, 2023 |
| Timi          | TM1701                      | [f5dfd4628e](https://linux-hardware.org/?probe=f5dfd4628e) | Mar 25, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [9c21fe4228](https://linux-hardware.org/?probe=9c21fe4228) | Mar 25, 2023 |
| Timi          | TM1701                      | [17e055a118](https://linux-hardware.org/?probe=17e055a118) | Mar 25, 2023 |
| Toshiba       | Satellite A500              | [cd79c573c6](https://linux-hardware.org/?probe=cd79c573c6) | Mar 25, 2023 |
| Haier         | S15                         | [083feb0355](https://linux-hardware.org/?probe=083feb0355) | Mar 25, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [f692116967](https://linux-hardware.org/?probe=f692116967) | Mar 25, 2023 |
| Samsung       | NC10                        | [96a0efc869](https://linux-hardware.org/?probe=96a0efc869) | Mar 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e9d97f4745](https://linux-hardware.org/?probe=e9d97f4745) | Mar 25, 2023 |
| ASUSTek       | N53SN                       | [4150c3835d](https://linux-hardware.org/?probe=4150c3835d) | Mar 24, 2023 |
| ASUSTek       | N550JK                      | [b63ec78860](https://linux-hardware.org/?probe=b63ec78860) | Mar 24, 2023 |
| Lenovo        | QIWG5                       | [3136edbf1d](https://linux-hardware.org/?probe=3136edbf1d) | Mar 24, 2023 |
| Packard Be... | EasyNote TE11HC             | [dbea63ed43](https://linux-hardware.org/?probe=dbea63ed43) | Mar 24, 2023 |
| HP            | Laptop 17-ak0xx             | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Unknown       | Unknown                     | [17cc340907](https://linux-hardware.org/?probe=17cc340907) | Mar 24, 2023 |
| Unknown       | Unknown                     | [359168b631](https://linux-hardware.org/?probe=359168b631) | Mar 24, 2023 |
| Lenovo        | B50-45 20388                | [5bd617a430](https://linux-hardware.org/?probe=5bd617a430) | Mar 24, 2023 |
| ASUSTek       | ZenBook UX433FN_BX433FN     | [d8e67b032e](https://linux-hardware.org/?probe=d8e67b032e) | Mar 24, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a021e21c5f](https://linux-hardware.org/?probe=a021e21c5f) | Mar 24, 2023 |
| Lenovo        | IdeaPad Y560                | [18071acd7e](https://linux-hardware.org/?probe=18071acd7e) | Mar 24, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [cba22e109f](https://linux-hardware.org/?probe=cba22e109f) | Mar 23, 2023 |
| Packard Be... | EasyNote TS11HR             | [f03dde8b73](https://linux-hardware.org/?probe=f03dde8b73) | Mar 23, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [750933836b](https://linux-hardware.org/?probe=750933836b) | Mar 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2d44e8f5c2](https://linux-hardware.org/?probe=2d44e8f5c2) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d956770153](https://linux-hardware.org/?probe=d956770153) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | [b56bf816d5](https://linux-hardware.org/?probe=b56bf816d5) | Mar 23, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [950e4b69e8](https://linux-hardware.org/?probe=950e4b69e8) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | [88a5d2eb30](https://linux-hardware.org/?probe=88a5d2eb30) | Mar 23, 2023 |
| Lenovo        | Y520-15IKBA 80WY            | [e32f728881](https://linux-hardware.org/?probe=e32f728881) | Mar 23, 2023 |
| ASUSTek       | X556UB                      | [97a85936b2](https://linux-hardware.org/?probe=97a85936b2) | Mar 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [fe3c64d71e](https://linux-hardware.org/?probe=fe3c64d71e) | Mar 23, 2023 |
| ASUSTek       | K61IC                       | [b16fb0d3c8](https://linux-hardware.org/?probe=b16fb0d3c8) | Mar 23, 2023 |
| Teclast       | F15Plus 2                   | [70a7bfb366](https://linux-hardware.org/?probe=70a7bfb366) | Mar 23, 2023 |
| realme        | CloudProXXXX                | [aaafa41631](https://linux-hardware.org/?probe=aaafa41631) | Mar 23, 2023 |
| Lenovo        | G560 20042                  | [2df8b64f07](https://linux-hardware.org/?probe=2df8b64f07) | Mar 22, 2023 |
| Toshiba       | T20                         | [a0757b47d7](https://linux-hardware.org/?probe=a0757b47d7) | Mar 22, 2023 |
| HP            | 635                         | [fef3dd1785](https://linux-hardware.org/?probe=fef3dd1785) | Mar 22, 2023 |
| Clevo         | NL41MU2                     | [430f11129e](https://linux-hardware.org/?probe=430f11129e) | Mar 22, 2023 |
| ASUSTek       | X550CC                      | [55d3d0217c](https://linux-hardware.org/?probe=55d3d0217c) | Mar 22, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [1f5d2a057c](https://linux-hardware.org/?probe=1f5d2a057c) | Mar 22, 2023 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [f97f90f7ce](https://linux-hardware.org/?probe=f97f90f7ce) | Mar 22, 2023 |
| ASUSTek       | X550CC                      | [957e5f5f8d](https://linux-hardware.org/?probe=957e5f5f8d) | Mar 22, 2023 |
| Dell          | Latitude 5521               | [ff25b78796](https://linux-hardware.org/?probe=ff25b78796) | Mar 21, 2023 |
| HP            | Pavilion g7                 | [9fbef1354b](https://linux-hardware.org/?probe=9fbef1354b) | Mar 21, 2023 |
| HUAWEI        | CREM-WXX9                   | [64a63f42bf](https://linux-hardware.org/?probe=64a63f42bf) | Mar 21, 2023 |
| MSI           | Sword 15 A12UE              | [f4341a491a](https://linux-hardware.org/?probe=f4341a491a) | Mar 21, 2023 |
| HONOR         | HYM-WXX                     | [df318ed208](https://linux-hardware.org/?probe=df318ed208) | Mar 21, 2023 |
| MSI           | Bravo 15 B5DD               | [a320127e2e](https://linux-hardware.org/?probe=a320127e2e) | Mar 21, 2023 |
| New IT Pro... | C156EP-C8RVTH               | [556d5020f8](https://linux-hardware.org/?probe=556d5020f8) | Mar 21, 2023 |
| New IT Pro... | C156EP-C8RVTH               | [96e84a3c49](https://linux-hardware.org/?probe=96e84a3c49) | Mar 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a526417aaf](https://linux-hardware.org/?probe=a526417aaf) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [e96b4f9ca9](https://linux-hardware.org/?probe=e96b4f9ca9) | Mar 21, 2023 |
| MSI           | Modern 14 A10M              | [7d9620fdd3](https://linux-hardware.org/?probe=7d9620fdd3) | Mar 21, 2023 |
| Acer          | Aspire A515-44              | [923686eb97](https://linux-hardware.org/?probe=923686eb97) | Mar 21, 2023 |
| Acer          | Swift SF315-52G             | [f6042580d0](https://linux-hardware.org/?probe=f6042580d0) | Mar 20, 2023 |
| Lenovo        | ThinkPad T530 2429LT7       | [ebb127610b](https://linux-hardware.org/?probe=ebb127610b) | Mar 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7bc035af43](https://linux-hardware.org/?probe=7bc035af43) | Mar 20, 2023 |
| Acer          | Swift SF114-34              | [0648d2d9c3](https://linux-hardware.org/?probe=0648d2d9c3) | Mar 20, 2023 |
| Acer          | Extensa 2509                | [8e0efd63c5](https://linux-hardware.org/?probe=8e0efd63c5) | Mar 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [be9b767d92](https://linux-hardware.org/?probe=be9b767d92) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5b1bccd269](https://linux-hardware.org/?probe=5b1bccd269) | Mar 20, 2023 |
| ASUSTek       | X751NV                      | [934e232587](https://linux-hardware.org/?probe=934e232587) | Mar 20, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [470a7a9123](https://linux-hardware.org/?probe=470a7a9123) | Mar 20, 2023 |
| Acer          | TravelMate 5760             | [712e36569d](https://linux-hardware.org/?probe=712e36569d) | Mar 20, 2023 |
| Prestigio     | PSB141C01BFH                | [9190e0a0e7](https://linux-hardware.org/?probe=9190e0a0e7) | Mar 19, 2023 |
| Teclast       | F15Plus 2                   | [17558890e2](https://linux-hardware.org/?probe=17558890e2) | Mar 19, 2023 |
| HP            | Laptop 15-rb0xx             | [d7ed5ce80d](https://linux-hardware.org/?probe=d7ed5ce80d) | Mar 19, 2023 |
| Toshiba       | Satellite Pro L300          | [82e7cb9669](https://linux-hardware.org/?probe=82e7cb9669) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [74b67b2037](https://linux-hardware.org/?probe=74b67b2037) | Mar 19, 2023 |
| HONOR         | GLO-FX6P                    | [0fb3ebc365](https://linux-hardware.org/?probe=0fb3ebc365) | Mar 19, 2023 |
| ASUSTek       | X205TA                      | [9727a94199](https://linux-hardware.org/?probe=9727a94199) | Mar 18, 2023 |
| ASUSTek       | UX301LAA                    | [882d4d095b](https://linux-hardware.org/?probe=882d4d095b) | Mar 18, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [90ef6ca2b7](https://linux-hardware.org/?probe=90ef6ca2b7) | Mar 18, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [b769745990](https://linux-hardware.org/?probe=b769745990) | Mar 18, 2023 |
| HONOR         | HYM-WXX                     | [bdb5c6a4ee](https://linux-hardware.org/?probe=bdb5c6a4ee) | Mar 18, 2023 |
| MSI           | GP60 2OD                    | [a3ffd8113f](https://linux-hardware.org/?probe=a3ffd8113f) | Mar 18, 2023 |
| HONOR         | NBR-WAX9                    | [19fd2af680](https://linux-hardware.org/?probe=19fd2af680) | Mar 18, 2023 |
| Acer          | Aspire A315-55G             | [badcc52c19](https://linux-hardware.org/?probe=badcc52c19) | Mar 18, 2023 |
| HP            | Laptop 15-db1xxx            | [08df29b00e](https://linux-hardware.org/?probe=08df29b00e) | Mar 18, 2023 |
| Positivo      | N6440                       | [98323051b5](https://linux-hardware.org/?probe=98323051b5) | Mar 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [233610a033](https://linux-hardware.org/?probe=233610a033) | Mar 18, 2023 |
| ASUSTek       | X551CAP                     | [e45da01a7e](https://linux-hardware.org/?probe=e45da01a7e) | Mar 18, 2023 |
| Acer          | Aspire 5310                 | [132691cbda](https://linux-hardware.org/?probe=132691cbda) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc76a5003](https://linux-hardware.org/?probe=ecc76a5003) | Mar 17, 2023 |
| HONOR         | NBR-WAX9                    | [09541b3bdd](https://linux-hardware.org/?probe=09541b3bdd) | Mar 17, 2023 |
| HONOR         | HYM-WXX                     | [279e932275](https://linux-hardware.org/?probe=279e932275) | Mar 17, 2023 |
| Aquarius      | NS585                       | [cd1e92458f](https://linux-hardware.org/?probe=cd1e92458f) | Mar 17, 2023 |
| HP            | EliteBook 840 G4            | [bb6be61738](https://linux-hardware.org/?probe=bb6be61738) | Mar 17, 2023 |
| Lenovo        | B590 20208                  | [e151d5d899](https://linux-hardware.org/?probe=e151d5d899) | Mar 17, 2023 |
| HIPER         | WORKBOOK                    | [ed14fd6e80](https://linux-hardware.org/?probe=ed14fd6e80) | Mar 17, 2023 |
| Unknown       | Unknown                     | [d2af864fbb](https://linux-hardware.org/?probe=d2af864fbb) | Mar 17, 2023 |
| Acer          | Nitro AN515-52              | [6ad4034797](https://linux-hardware.org/?probe=6ad4034797) | Mar 17, 2023 |
| ASUSTek       | X580VD                      | [8c4023bd5d](https://linux-hardware.org/?probe=8c4023bd5d) | Mar 16, 2023 |
| HONOR         | BMH-WCX9                    | [47a9ec2aa1](https://linux-hardware.org/?probe=47a9ec2aa1) | Mar 16, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [421f6945e6](https://linux-hardware.org/?probe=421f6945e6) | Mar 16, 2023 |
| Acer          | Aspire 5820TZG              | [9f08995104](https://linux-hardware.org/?probe=9f08995104) | Mar 16, 2023 |
| ASUSTek       | X75VCP                      | [f154cf28db](https://linux-hardware.org/?probe=f154cf28db) | Mar 16, 2023 |
| ASUSTek       | X55A                        | [5cf7c3643d](https://linux-hardware.org/?probe=5cf7c3643d) | Mar 16, 2023 |
| ASUSTek       | X55A                        | [743d04e5fc](https://linux-hardware.org/?probe=743d04e5fc) | Mar 16, 2023 |
| ASUSTek       | X580VD                      | [26b62abfc9](https://linux-hardware.org/?probe=26b62abfc9) | Mar 16, 2023 |
| HUAWEI        | NDZ-WXX9                    | [82687f32c9](https://linux-hardware.org/?probe=82687f32c9) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [a99c892744](https://linux-hardware.org/?probe=a99c892744) | Mar 16, 2023 |
| HUAWEI        | BOD-WXX9                    | [ef98a330e6](https://linux-hardware.org/?probe=ef98a330e6) | Mar 16, 2023 |
| Dell          | Latitude 7520               | [09c8e699d3](https://linux-hardware.org/?probe=09c8e699d3) | Mar 16, 2023 |
| Lenovo        | ThinkPad X230 23245C8       | [7015f3b169](https://linux-hardware.org/?probe=7015f3b169) | Mar 16, 2023 |
| ASUSTek       | N76VB                       | [20afa1889d](https://linux-hardware.org/?probe=20afa1889d) | Mar 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [46d1e1d803](https://linux-hardware.org/?probe=46d1e1d803) | Mar 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b110af35d5](https://linux-hardware.org/?probe=b110af35d5) | Mar 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | [03e5d43f27](https://linux-hardware.org/?probe=03e5d43f27) | Mar 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | [4c49d73583](https://linux-hardware.org/?probe=4c49d73583) | Mar 15, 2023 |
| Acer          | Aspire A315-42G             | [727c7d3b7b](https://linux-hardware.org/?probe=727c7d3b7b) | Mar 15, 2023 |
| HP            | Laptop 15s-eq1xxx           | [59a304e790](https://linux-hardware.org/?probe=59a304e790) | Mar 15, 2023 |
| Toshiba       | Satellite L850D-BJS         | [95fcbd0967](https://linux-hardware.org/?probe=95fcbd0967) | Mar 15, 2023 |
| HIPER         | WORKBOOK                    | [3d1c928bcb](https://linux-hardware.org/?probe=3d1c928bcb) | Mar 15, 2023 |
| Acer          | Aspire 7720                 | [0f040d8292](https://linux-hardware.org/?probe=0f040d8292) | Mar 15, 2023 |
| Valve         | Jupiter                     | [686a9db96f](https://linux-hardware.org/?probe=686a9db96f) | Mar 15, 2023 |
| HP            | Pavilion g6                 | [ee8ba66ff4](https://linux-hardware.org/?probe=ee8ba66ff4) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [112d979fc6](https://linux-hardware.org/?probe=112d979fc6) | Mar 14, 2023 |
| Acer          | Aspire 7110                 | [ec44273fd3](https://linux-hardware.org/?probe=ec44273fd3) | Mar 14, 2023 |
| ASUSTek       | 1215P                       | [7cfe211e09](https://linux-hardware.org/?probe=7cfe211e09) | Mar 14, 2023 |
| Lenovo        | ThinkPad X230 23245C8       | [5aaf852168](https://linux-hardware.org/?probe=5aaf852168) | Mar 14, 2023 |
| Sony          | VPCZ12V9R                   | [28be5f7f2b](https://linux-hardware.org/?probe=28be5f7f2b) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [9f3f315f73](https://linux-hardware.org/?probe=9f3f315f73) | Mar 14, 2023 |
| Lenovo        | V110-15AST 80TD             | [a574807ec1](https://linux-hardware.org/?probe=a574807ec1) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [42653f8c2a](https://linux-hardware.org/?probe=42653f8c2a) | Mar 14, 2023 |
| Acer          | Aspire 7739G                | [aeff2df11c](https://linux-hardware.org/?probe=aeff2df11c) | Mar 14, 2023 |
| HP            | Laptop 15-bs1xx             | [3d98403721](https://linux-hardware.org/?probe=3d98403721) | Mar 14, 2023 |
| Acer          | Aspire 7720                 | [b80fa5f7ff](https://linux-hardware.org/?probe=b80fa5f7ff) | Mar 14, 2023 |
| HUAWEI        | KPRC-WX0                    | [580758b277](https://linux-hardware.org/?probe=580758b277) | Mar 14, 2023 |
| HONOR         | BMH-WCX9                    | [d53fa296bf](https://linux-hardware.org/?probe=d53fa296bf) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [e6792912bf](https://linux-hardware.org/?probe=e6792912bf) | Mar 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [088325b0d3](https://linux-hardware.org/?probe=088325b0d3) | Mar 14, 2023 |
| eMachines     | eME730G                     | [ef96ec0313](https://linux-hardware.org/?probe=ef96ec0313) | Mar 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cc878090ee](https://linux-hardware.org/?probe=cc878090ee) | Mar 13, 2023 |
| ASUSTek       | K53Z                        | [5ec3f96a8e](https://linux-hardware.org/?probe=5ec3f96a8e) | Mar 13, 2023 |
| Acer          | Aspire one                  | [60c75cc14d](https://linux-hardware.org/?probe=60c75cc14d) | Mar 13, 2023 |
| Dell          | Vostro 3400                 | [01bfc3e026](https://linux-hardware.org/?probe=01bfc3e026) | Mar 13, 2023 |
| Acer          | Aspire A315-21G             | [84b199bf8b](https://linux-hardware.org/?probe=84b199bf8b) | Mar 13, 2023 |
| Acer          | Aspire R7-371T              | [b6aef449b6](https://linux-hardware.org/?probe=b6aef449b6) | Mar 13, 2023 |
| Lenovo        | ThinkPad 11e 3rd Gen 20G... | [1e037723cc](https://linux-hardware.org/?probe=1e037723cc) | Mar 12, 2023 |
| TECNO         | MEGABOOK T1                 | [000c3e4761](https://linux-hardware.org/?probe=000c3e4761) | Mar 12, 2023 |
| Acer          | Aspire one                  | [c3d7bc326a](https://linux-hardware.org/?probe=c3d7bc326a) | Mar 12, 2023 |
| HONOR         | HYM-WXX                     | [366d00f0a7](https://linux-hardware.org/?probe=366d00f0a7) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge 13IAL# 019... | [1d91216d1b](https://linux-hardware.org/?probe=1d91216d1b) | Mar 12, 2023 |
| Pegatron      | C15B                        | [539f4fbf7a](https://linux-hardware.org/?probe=539f4fbf7a) | Mar 12, 2023 |
| ASUSTek       | GL702VM                     | [62a45a1b6d](https://linux-hardware.org/?probe=62a45a1b6d) | Mar 12, 2023 |
| ASUSTek       | GL702VM                     | [ae185a2005](https://linux-hardware.org/?probe=ae185a2005) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [062687b226](https://linux-hardware.org/?probe=062687b226) | Mar 11, 2023 |
| Sony          | SVE1713P1RB                 | [efa148ef67](https://linux-hardware.org/?probe=efa148ef67) | Mar 11, 2023 |
| LTD Delovo... | EVE 14 C414 NA9144BXW01     | [f7bda1bf30](https://linux-hardware.org/?probe=f7bda1bf30) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | [d8cf10f11d](https://linux-hardware.org/?probe=d8cf10f11d) | Mar 11, 2023 |
| ASUSTek       | N53SV                       | [816307ec8e](https://linux-hardware.org/?probe=816307ec8e) | Mar 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [06814e6afa](https://linux-hardware.org/?probe=06814e6afa) | Mar 11, 2023 |
| HP            | Laptop 15-bw0xx             | [d479ffc245](https://linux-hardware.org/?probe=d479ffc245) | Mar 11, 2023 |
| ASUSTek       | K46CM                       | [e0cce23d86](https://linux-hardware.org/?probe=e0cce23d86) | Mar 11, 2023 |
| Gigabyte      | GB-BSi7A-6500               | [b24842e6f1](https://linux-hardware.org/?probe=b24842e6f1) | Mar 11, 2023 |
| Acer          | Aspire E5-771G              | [c9c401bdb5](https://linux-hardware.org/?probe=c9c401bdb5) | Mar 11, 2023 |
| Acer          | Aspire E5-771G              | [849ea0e3dc](https://linux-hardware.org/?probe=849ea0e3dc) | Mar 11, 2023 |
| ASUSTek       | K53SM                       | [aa3efc3683](https://linux-hardware.org/?probe=aa3efc3683) | Mar 11, 2023 |
| Unknown       | Unknown                     | [5d585fb91b](https://linux-hardware.org/?probe=5d585fb91b) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [bd2a89f7c1](https://linux-hardware.org/?probe=bd2a89f7c1) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z480                | [eb63a9a0d3](https://linux-hardware.org/?probe=eb63a9a0d3) | Mar 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [a6dc5e13d0](https://linux-hardware.org/?probe=a6dc5e13d0) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | [ed7724b921](https://linux-hardware.org/?probe=ed7724b921) | Mar 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [b473b68faf](https://linux-hardware.org/?probe=b473b68faf) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | [6605d9e257](https://linux-hardware.org/?probe=6605d9e257) | Mar 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [4a8589fbdf](https://linux-hardware.org/?probe=4a8589fbdf) | Mar 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [801cf42ac7](https://linux-hardware.org/?probe=801cf42ac7) | Mar 10, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [a62abba552](https://linux-hardware.org/?probe=a62abba552) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | [6ef05d9cbb](https://linux-hardware.org/?probe=6ef05d9cbb) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | [4f916d30c4](https://linux-hardware.org/?probe=4f916d30c4) | Mar 10, 2023 |
| Dell          | Vostro 5581                 | [72b648b75c](https://linux-hardware.org/?probe=72b648b75c) | Mar 10, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [87aa621d6a](https://linux-hardware.org/?probe=87aa621d6a) | Mar 10, 2023 |
| Dell          | Vostro 5581                 | [c7a13194c8](https://linux-hardware.org/?probe=c7a13194c8) | Mar 10, 2023 |
| ASUSTek       | 1001PX                      | [b38727d178](https://linux-hardware.org/?probe=b38727d178) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [d64a783d3a](https://linux-hardware.org/?probe=d64a783d3a) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1b0ea7bf68](https://linux-hardware.org/?probe=1b0ea7bf68) | Mar 10, 2023 |
| MSI           | S12T 3M/S12 3M              | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| ASUSTek       | X580VD                      | [8cb2ac6f38](https://linux-hardware.org/?probe=8cb2ac6f38) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9e620a10f2](https://linux-hardware.org/?probe=9e620a10f2) | Mar 09, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [c7519d4c79](https://linux-hardware.org/?probe=c7519d4c79) | Mar 09, 2023 |
| Lenovo        | IdeaPad Z480                | [bc5f204a78](https://linux-hardware.org/?probe=bc5f204a78) | Mar 08, 2023 |
| Acer          | Swift SF114-32              | [6bc8cc9c28](https://linux-hardware.org/?probe=6bc8cc9c28) | Mar 08, 2023 |
| Toshiba       | Satellite A200              | [3b83e42348](https://linux-hardware.org/?probe=3b83e42348) | Mar 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d01b6ad50c](https://linux-hardware.org/?probe=d01b6ad50c) | Mar 08, 2023 |
| HONOR         | BMH-WCX9                    | [9ec3d187fd](https://linux-hardware.org/?probe=9ec3d187fd) | Mar 08, 2023 |
| Maibenben     | JinMai6 series              | [ace44d9872](https://linux-hardware.org/?probe=ace44d9872) | Mar 08, 2023 |
| Dell          | Latitude 5521               | [550860917e](https://linux-hardware.org/?probe=550860917e) | Mar 08, 2023 |
| Valve         | Jupiter                     | [258d1635a3](https://linux-hardware.org/?probe=258d1635a3) | Mar 08, 2023 |
| Infinix       | INBOOK X2 GEN11             | [3d14886d4c](https://linux-hardware.org/?probe=3d14886d4c) | Mar 07, 2023 |
| HP            | ProBook 440 G7              | [7f4678dcf1](https://linux-hardware.org/?probe=7f4678dcf1) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | [124b1af920](https://linux-hardware.org/?probe=124b1af920) | Mar 07, 2023 |
| Valve         | Jupiter                     | [00cb6a869a](https://linux-hardware.org/?probe=00cb6a869a) | Mar 07, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [9ff521edc3](https://linux-hardware.org/?probe=9ff521edc3) | Mar 07, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [070c644d4f](https://linux-hardware.org/?probe=070c644d4f) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [efe5bcec0b](https://linux-hardware.org/?probe=efe5bcec0b) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [c6737dc34b](https://linux-hardware.org/?probe=c6737dc34b) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [c517071efd](https://linux-hardware.org/?probe=c517071efd) | Mar 06, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [00b928f630](https://linux-hardware.org/?probe=00b928f630) | Mar 06, 2023 |
| Sony          | SVT1313X9RS                 | [c2766f4ac5](https://linux-hardware.org/?probe=c2766f4ac5) | Mar 06, 2023 |
| Lenovo        | ThinkPad Edge 03014EG       | [e3186561ef](https://linux-hardware.org/?probe=e3186561ef) | Mar 06, 2023 |
| HP            | Pavilion dv6                | [6485870687](https://linux-hardware.org/?probe=6485870687) | Mar 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [119a07048d](https://linux-hardware.org/?probe=119a07048d) | Mar 06, 2023 |
| Infinix       | INBOOK X2 GEN11             | [6faa586824](https://linux-hardware.org/?probe=6faa586824) | Mar 06, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [91db409270](https://linux-hardware.org/?probe=91db409270) | Mar 06, 2023 |
| Acer          | Aspire 4253G                | [80228255b2](https://linux-hardware.org/?probe=80228255b2) | Mar 06, 2023 |
| Unknown       | Unknown                     | [8b7f7b9440](https://linux-hardware.org/?probe=8b7f7b9440) | Mar 05, 2023 |
| Toshiba       | Satellite U300              | [6e33105e71](https://linux-hardware.org/?probe=6e33105e71) | Mar 05, 2023 |
| ASUSTek       | X102BA                      | [6c425f0640](https://linux-hardware.org/?probe=6c425f0640) | Mar 05, 2023 |
| ASUSTek       | V6J                         | [10819a91fd](https://linux-hardware.org/?probe=10819a91fd) | Mar 05, 2023 |
| ASUSTek       | M51Tr                       | [3d4d35a9a7](https://linux-hardware.org/?probe=3d4d35a9a7) | Mar 05, 2023 |
| Dell          | G5 5500                     | [7da5494dea](https://linux-hardware.org/?probe=7da5494dea) | Mar 05, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [fe903be37c](https://linux-hardware.org/?probe=fe903be37c) | Mar 04, 2023 |
| Dell          | Inspiron 11-3162            | [243db51836](https://linux-hardware.org/?probe=243db51836) | Mar 04, 2023 |
| Acer          | Aspire V3-551G              | [ae3684f7c7](https://linux-hardware.org/?probe=ae3684f7c7) | Mar 04, 2023 |
| Samsung       | R530/R730                   | [277c940c6b](https://linux-hardware.org/?probe=277c940c6b) | Mar 04, 2023 |
| Sony          | VPCZ12S9R                   | [bbc4c5d9ae](https://linux-hardware.org/?probe=bbc4c5d9ae) | Mar 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [737ed0a45d](https://linux-hardware.org/?probe=737ed0a45d) | Mar 04, 2023 |
| ASUSTek       | K53TA                       | [5bfd8132fb](https://linux-hardware.org/?probe=5bfd8132fb) | Mar 04, 2023 |
| HP            | 255 G3                      | [9ccab85062](https://linux-hardware.org/?probe=9ccab85062) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c4def038d9](https://linux-hardware.org/?probe=c4def038d9) | Mar 04, 2023 |
| ASUSTek       | G750JS                      | [43c8398586](https://linux-hardware.org/?probe=43c8398586) | Mar 04, 2023 |
| HP            | Laptop 14s-dq1xxx           | [29fa7c0b23](https://linux-hardware.org/?probe=29fa7c0b23) | Mar 04, 2023 |
| Prestigio     | B10T                        | [140230a6ad](https://linux-hardware.org/?probe=140230a6ad) | Mar 04, 2023 |
| ASUSTek       | G750JS                      | [a75616082d](https://linux-hardware.org/?probe=a75616082d) | Mar 03, 2023 |
| DEXP          | Aquilon C15                 | [9ae006e12a](https://linux-hardware.org/?probe=9ae006e12a) | Mar 03, 2023 |
| Acer          | Aspire A317-53              | [f097b7866e](https://linux-hardware.org/?probe=f097b7866e) | Mar 03, 2023 |
| eMachines     | eM355                       | [a882cab474](https://linux-hardware.org/?probe=a882cab474) | Mar 03, 2023 |
| Acer          | Aspire E1-522               | [f102669f1f](https://linux-hardware.org/?probe=f102669f1f) | Mar 03, 2023 |
| Unknown       | Unknown                     | [7afe06d070](https://linux-hardware.org/?probe=7afe06d070) | Mar 03, 2023 |
| Lenovo        | G500 20236                  | [89a9f53a7e](https://linux-hardware.org/?probe=89a9f53a7e) | Mar 03, 2023 |
| ASUSTek       | F5SL                        | [c959885e6f](https://linux-hardware.org/?probe=c959885e6f) | Mar 03, 2023 |
| HP            | ProBook 6450b               | [3def91ca84](https://linux-hardware.org/?probe=3def91ca84) | Mar 02, 2023 |
| MSI           | Modern 14 C12M              | [ac7eea2ecc](https://linux-hardware.org/?probe=ac7eea2ecc) | Mar 02, 2023 |
| Dell          | Vostro1710                  | [c24eab7e3d](https://linux-hardware.org/?probe=c24eab7e3d) | Mar 02, 2023 |
| HUAWEI        | HVY-WXX9                    | [dcc115a880](https://linux-hardware.org/?probe=dcc115a880) | Mar 02, 2023 |
| Acer          | Aspire 3690                 | [6f2794495c](https://linux-hardware.org/?probe=6f2794495c) | Mar 02, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [c11c045673](https://linux-hardware.org/?probe=c11c045673) | Mar 02, 2023 |
| Kraftway      | ACCORD                      | [0c2d63ec1c](https://linux-hardware.org/?probe=0c2d63ec1c) | Mar 02, 2023 |
| HP            | Pavilion g6                 | [ee48e03827](https://linux-hardware.org/?probe=ee48e03827) | Mar 02, 2023 |
| Kraftway      | ACCORD                      | [458c33576f](https://linux-hardware.org/?probe=458c33576f) | Mar 02, 2023 |
| Irbis         | 15NBC1000                   | [c10f6c3c00](https://linux-hardware.org/?probe=c10f6c3c00) | Mar 02, 2023 |
| ASUSTek       | K40AF                       | [09472e2548](https://linux-hardware.org/?probe=09472e2548) | Mar 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [ad513cea88](https://linux-hardware.org/?probe=ad513cea88) | Mar 02, 2023 |
| Acer          | Aspire 3690                 | [36266c4a83](https://linux-hardware.org/?probe=36266c4a83) | Mar 02, 2023 |
| Maibenben     | XiaoMai5                    | [f4f5217397](https://linux-hardware.org/?probe=f4f5217397) | Mar 02, 2023 |
| HP            | 255 G3                      | [78c4cd0a9c](https://linux-hardware.org/?probe=78c4cd0a9c) | Mar 01, 2023 |
| Valve         | Jupiter                     | [2a2e923df8](https://linux-hardware.org/?probe=2a2e923df8) | Mar 01, 2023 |
| Dell          | Vostro 5402                 | [0befe28d1b](https://linux-hardware.org/?probe=0befe28d1b) | Mar 01, 2023 |
| Valve         | Jupiter                     | [4204e99885](https://linux-hardware.org/?probe=4204e99885) | Mar 01, 2023 |
| ASUSTek       | X751LD                      | [46eecb2678](https://linux-hardware.org/?probe=46eecb2678) | Mar 01, 2023 |
| Dell          | Inspiron 1501               | [e137d431d2](https://linux-hardware.org/?probe=e137d431d2) | Mar 01, 2023 |
| ASUSTek       | K53TK                       | [09398155fc](https://linux-hardware.org/?probe=09398155fc) | Mar 01, 2023 |
| HIPER         | WORKBOOK                    | [85085220c9](https://linux-hardware.org/?probe=85085220c9) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [165c0356a5](https://linux-hardware.org/?probe=165c0356a5) | Mar 01, 2023 |
| Unknown       | X133                        | [36f455c1af](https://linux-hardware.org/?probe=36f455c1af) | Mar 01, 2023 |
| ASUSTek       | K40AF                       | [71ec4e0527](https://linux-hardware.org/?probe=71ec4e0527) | Mar 01, 2023 |
| Acer          | AOHAPPY2                    | [9bbd271b36](https://linux-hardware.org/?probe=9bbd271b36) | Feb 28, 2023 |
| Dell          | G15 5511                    | [1859d13517](https://linux-hardware.org/?probe=1859d13517) | Feb 28, 2023 |
| Clevo         | NL41MU2                     | [29df87f87f](https://linux-hardware.org/?probe=29df87f87f) | Feb 28, 2023 |
| HP            | 255 G2                      | [10397efd1b](https://linux-hardware.org/?probe=10397efd1b) | Feb 28, 2023 |
| Acer          | Aspire A315-59              | [9a897f5d7c](https://linux-hardware.org/?probe=9a897f5d7c) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | [3d003c6d17](https://linux-hardware.org/?probe=3d003c6d17) | Feb 28, 2023 |
| Sony          | VPCZ21Z9R                   | [4d3f0c27cd](https://linux-hardware.org/?probe=4d3f0c27cd) | Feb 28, 2023 |
| Acer          | Aspire A515-45G             | [5f8c1e2d90](https://linux-hardware.org/?probe=5f8c1e2d90) | Feb 28, 2023 |
| HP            | ProBook 430 G1              | [fa75658ee0](https://linux-hardware.org/?probe=fa75658ee0) | Feb 28, 2023 |
| Fujitsu       | LIFEBOOK E744               | [e331c5e257](https://linux-hardware.org/?probe=e331c5e257) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | [e888e1330d](https://linux-hardware.org/?probe=e888e1330d) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | [18fdb45ec1](https://linux-hardware.org/?probe=18fdb45ec1) | Feb 27, 2023 |
| HUAWEI        | BOM-WXX9                    | [43a5dbf393](https://linux-hardware.org/?probe=43a5dbf393) | Feb 27, 2023 |
| Clevo         | NL41MU2                     | [b91dfc602e](https://linux-hardware.org/?probe=b91dfc602e) | Feb 27, 2023 |
| Timi          | RedmiBook Pro 15S           | [109a8e15c4](https://linux-hardware.org/?probe=109a8e15c4) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b116afe451](https://linux-hardware.org/?probe=b116afe451) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7e55bb97e](https://linux-hardware.org/?probe=d7e55bb97e) | Feb 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7936e7db49](https://linux-hardware.org/?probe=7936e7db49) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| Acer          | Aspire 3690                 | [c93af7d4eb](https://linux-hardware.org/?probe=c93af7d4eb) | Feb 27, 2023 |
| Acer          | Aspire 3690                 | [b119bda1a6](https://linux-hardware.org/?probe=b119bda1a6) | Feb 27, 2023 |
| Sony          | VPCSB2L1R                   | [6ed9bd210d](https://linux-hardware.org/?probe=6ed9bd210d) | Feb 26, 2023 |
| Apple         | MacBookAir7,1               | [2986fb12e2](https://linux-hardware.org/?probe=2986fb12e2) | Feb 26, 2023 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [4c9bfc239a](https://linux-hardware.org/?probe=4c9bfc239a) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [8d8e5bc41d](https://linux-hardware.org/?probe=8d8e5bc41d) | Feb 26, 2023 |
| HP            | 255 G3                      | [49dccf5753](https://linux-hardware.org/?probe=49dccf5753) | Feb 26, 2023 |
| HP            | ProBook 430 G1              | [1354e0b47e](https://linux-hardware.org/?probe=1354e0b47e) | Feb 26, 2023 |
| Acer          | AOHAPPY2                    | [830a1212b7](https://linux-hardware.org/?probe=830a1212b7) | Feb 26, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [da19f23a14](https://linux-hardware.org/?probe=da19f23a14) | Feb 26, 2023 |
| Apple         | MacBookAir7,1               | [05c92ac080](https://linux-hardware.org/?probe=05c92ac080) | Feb 26, 2023 |
| Acer          | Extensa 2519                | [b80f0bc182](https://linux-hardware.org/?probe=b80f0bc182) | Feb 26, 2023 |
| Acer          | Extensa 2519                | [3ee3fea5eb](https://linux-hardware.org/?probe=3ee3fea5eb) | Feb 26, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [848e43f7c3](https://linux-hardware.org/?probe=848e43f7c3) | Feb 26, 2023 |
| Lenovo        | ThinkPad E490 20N8000XRT    | [b9e64d9f86](https://linux-hardware.org/?probe=b9e64d9f86) | Feb 26, 2023 |
| eMachines     | Rhine V1.42                 | [c0c7b48991](https://linux-hardware.org/?probe=c0c7b48991) | Feb 26, 2023 |
| eMachines     | eME728                      | [2331984fc8](https://linux-hardware.org/?probe=2331984fc8) | Feb 26, 2023 |
| Sony          | VPCZ12V9R                   | [3014067c24](https://linux-hardware.org/?probe=3014067c24) | Feb 26, 2023 |
| realme        | RMNBXXXX                    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7d7953a826](https://linux-hardware.org/?probe=7d7953a826) | Feb 26, 2023 |
| Acer          | Aspire A715-42G             | [c7ef2b6e58](https://linux-hardware.org/?probe=c7ef2b6e58) | Feb 25, 2023 |
| Dell          | Vostro 3501                 | [ed459712f6](https://linux-hardware.org/?probe=ed459712f6) | Feb 25, 2023 |
| Dell          | Latitude 5511               | [4402838fb3](https://linux-hardware.org/?probe=4402838fb3) | Feb 25, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [c5cdb97c5b](https://linux-hardware.org/?probe=c5cdb97c5b) | Feb 25, 2023 |
| HUAWEI        | MACH-WX9                    | [52924074db](https://linux-hardware.org/?probe=52924074db) | Feb 25, 2023 |
| ASUSTek       | N53SM                       | [6606121f31](https://linux-hardware.org/?probe=6606121f31) | Feb 25, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [976a29944a](https://linux-hardware.org/?probe=976a29944a) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a8a2fc9d83](https://linux-hardware.org/?probe=a8a2fc9d83) | Feb 24, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [5ad40efe5c](https://linux-hardware.org/?probe=5ad40efe5c) | Feb 24, 2023 |
| Lenovo        | G50-70 20351                | [8fa16a1dec](https://linux-hardware.org/?probe=8fa16a1dec) | Feb 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | [8a573735cb](https://linux-hardware.org/?probe=8a573735cb) | Feb 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9c0b9ff47a](https://linux-hardware.org/?probe=9c0b9ff47a) | Feb 24, 2023 |
| Samsung       | N150P                       | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| Toshiba       | Satellite U300              | [d5973ad69a](https://linux-hardware.org/?probe=d5973ad69a) | Feb 24, 2023 |
| Dell          | G5 5587                     | [1f43871064](https://linux-hardware.org/?probe=1f43871064) | Feb 24, 2023 |
| HP            | ProBook 4545s               | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| HUAWEI        | MACH-WX9                    | [fd61d34d74](https://linux-hardware.org/?probe=fd61d34d74) | Feb 23, 2023 |
| Acer          | Aspire ES1-132              | [386da062e2](https://linux-hardware.org/?probe=386da062e2) | Feb 23, 2023 |
| Acer          | AOHAPPY2                    | [a7a5e4b46c](https://linux-hardware.org/?probe=a7a5e4b46c) | Feb 23, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e76bd912f8](https://linux-hardware.org/?probe=e76bd912f8) | Feb 23, 2023 |
| HP            | ProBook 440 G7              | [224a9e7278](https://linux-hardware.org/?probe=224a9e7278) | Feb 23, 2023 |
| HP            | ProBook 440 G7              | [618e46eb82](https://linux-hardware.org/?probe=618e46eb82) | Feb 23, 2023 |
| Dell          | Latitude 7410               | [dfa449b870](https://linux-hardware.org/?probe=dfa449b870) | Feb 23, 2023 |
| ASUSTek       | X541SA                      | [59a1b07ad5](https://linux-hardware.org/?probe=59a1b07ad5) | Feb 23, 2023 |
| Valve         | Jupiter                     | [ed92b67969](https://linux-hardware.org/?probe=ed92b67969) | Feb 22, 2023 |
| 3Logic Gro... | Graviton N15i-K2            | [564ecd80d9](https://linux-hardware.org/?probe=564ecd80d9) | Feb 22, 2023 |
| MSI           | GF63 Thin 9RCX              | [87a9510543](https://linux-hardware.org/?probe=87a9510543) | Feb 22, 2023 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [25c5125cd9](https://linux-hardware.org/?probe=25c5125cd9) | Feb 22, 2023 |
| Acer          | Aspire V3-771               | [c56e36cd0e](https://linux-hardware.org/?probe=c56e36cd0e) | Feb 22, 2023 |
| HP            | ProBook 640 G5              | [e90b71c2fd](https://linux-hardware.org/?probe=e90b71c2fd) | Feb 22, 2023 |
| Kraftway      | ACCORD                      | [8fe15f2f2b](https://linux-hardware.org/?probe=8fe15f2f2b) | Feb 22, 2023 |
| Lenovo        | ThinkPad T520 4242NS9       | [6e2e5c8285](https://linux-hardware.org/?probe=6e2e5c8285) | Feb 22, 2023 |
| Acer          | Aspire ES1-533              | [4a7563bd8e](https://linux-hardware.org/?probe=4a7563bd8e) | Feb 22, 2023 |
| Toshiba       | Satellite A300D             | [fd0d9d5ba1](https://linux-hardware.org/?probe=fd0d9d5ba1) | Feb 22, 2023 |
| Chuwi         | CoreBook XPro               | [c1f8c947d4](https://linux-hardware.org/?probe=c1f8c947d4) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [0e9172bdd5](https://linux-hardware.org/?probe=0e9172bdd5) | Feb 21, 2023 |
| HUAWEI        | CREM-WXX9                   | [643d79fd46](https://linux-hardware.org/?probe=643d79fd46) | Feb 21, 2023 |
| ASUSTek       | X551CAP                     | [1ed860d561](https://linux-hardware.org/?probe=1ed860d561) | Feb 21, 2023 |
| ASUSTek       | X556UQ                      | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [adc356a0a8](https://linux-hardware.org/?probe=adc356a0a8) | Feb 21, 2023 |
| Acer          | Aspire 7736                 | [479496a645](https://linux-hardware.org/?probe=479496a645) | Feb 21, 2023 |
| Acer          | Aspire V5-552PG             | [6030cc4d8a](https://linux-hardware.org/?probe=6030cc4d8a) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [21c2630c57](https://linux-hardware.org/?probe=21c2630c57) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a0faf74325](https://linux-hardware.org/?probe=a0faf74325) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d51436d679](https://linux-hardware.org/?probe=d51436d679) | Feb 21, 2023 |
| Gigabyte      | AORUS 17 XE4                | [b674e3e1e0](https://linux-hardware.org/?probe=b674e3e1e0) | Feb 21, 2023 |
| HUAWEI        | MRGF-XX                     | [1c61370063](https://linux-hardware.org/?probe=1c61370063) | Feb 21, 2023 |
| HP            | ProBook 430 G1              | [1505165a73](https://linux-hardware.org/?probe=1505165a73) | Feb 20, 2023 |
| ASUSTek       | TP300UA                     | [22ff7f5827](https://linux-hardware.org/?probe=22ff7f5827) | Feb 20, 2023 |
| HP            | Pavilion Notebook           | [caff81fa5f](https://linux-hardware.org/?probe=caff81fa5f) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| Samsung       | N102                        | [736977f523](https://linux-hardware.org/?probe=736977f523) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| ASUSTek       | GL703VD                     | [5b0cf6bef1](https://linux-hardware.org/?probe=5b0cf6bef1) | Feb 20, 2023 |
| Haier         | A1410ED                     | [0188ad4a9b](https://linux-hardware.org/?probe=0188ad4a9b) | Feb 20, 2023 |
| Haier         | A1410ED                     | [0551c42cf8](https://linux-hardware.org/?probe=0551c42cf8) | Feb 20, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [e008fd489b](https://linux-hardware.org/?probe=e008fd489b) | Feb 20, 2023 |
| Alienware     | 17                          | [848d5cd7e9](https://linux-hardware.org/?probe=848d5cd7e9) | Feb 20, 2023 |
| DNS           | MB40IA1                     | [9aaf027f52](https://linux-hardware.org/?probe=9aaf027f52) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [c0032d4f0b](https://linux-hardware.org/?probe=c0032d4f0b) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [b1d168b6ce](https://linux-hardware.org/?probe=b1d168b6ce) | Feb 19, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [aa5d23bc20](https://linux-hardware.org/?probe=aa5d23bc20) | Feb 19, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [28e6263489](https://linux-hardware.org/?probe=28e6263489) | Feb 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b27447bfa3](https://linux-hardware.org/?probe=b27447bfa3) | Feb 19, 2023 |
| HP            | Laptop 15s-eq1xxx           | [188489240c](https://linux-hardware.org/?probe=188489240c) | Feb 19, 2023 |
| ASUSTek       | M51Sn                       | [999f32a65f](https://linux-hardware.org/?probe=999f32a65f) | Feb 18, 2023 |
| Lenovo        | B590 20208                  | [59810216a8](https://linux-hardware.org/?probe=59810216a8) | Feb 18, 2023 |
| Lenovo        | Flex 2-14 20404             | [1fc2c6c2f5](https://linux-hardware.org/?probe=1fc2c6c2f5) | Feb 18, 2023 |
| HP            | Notebook                    | [3eff638ead](https://linux-hardware.org/?probe=3eff638ead) | Feb 18, 2023 |
| HUAWEI        | BOM-WXX9                    | [6234395029](https://linux-hardware.org/?probe=6234395029) | Feb 18, 2023 |
| Samsung       | R519/R719                   | [17524cf177](https://linux-hardware.org/?probe=17524cf177) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [f8dd8a7ee9](https://linux-hardware.org/?probe=f8dd8a7ee9) | Feb 18, 2023 |
| Acer          | TravelMate B118-M           | [f70df82711](https://linux-hardware.org/?probe=f70df82711) | Feb 18, 2023 |
| Acer          | Aspire A315-21              | [fe42379585](https://linux-hardware.org/?probe=fe42379585) | Feb 18, 2023 |
| Acer          | AOHAPPY2                    | [1f71a1ad75](https://linux-hardware.org/?probe=1f71a1ad75) | Feb 18, 2023 |
| Unknown       | Unknown                     | [ec840e7d97](https://linux-hardware.org/?probe=ec840e7d97) | Feb 18, 2023 |
| itel Mobil... | SPIRIT 2                    | [8c370ddf38](https://linux-hardware.org/?probe=8c370ddf38) | Feb 17, 2023 |
| Acer          | Aspire 5920G                | [f9000d049e](https://linux-hardware.org/?probe=f9000d049e) | Feb 17, 2023 |
| MSI           | Modern 14 B5M               | [d951f389f3](https://linux-hardware.org/?probe=d951f389f3) | Feb 17, 2023 |
| ASUSTek       | K53SC                       | [df5351b94d](https://linux-hardware.org/?probe=df5351b94d) | Feb 17, 2023 |
| Dell          | Inspiron 5555               | [2051d9e516](https://linux-hardware.org/?probe=2051d9e516) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | [10e9491ee4](https://linux-hardware.org/?probe=10e9491ee4) | Feb 17, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9187251796](https://linux-hardware.org/?probe=9187251796) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | [a3b352975c](https://linux-hardware.org/?probe=a3b352975c) | Feb 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [4d9144193f](https://linux-hardware.org/?probe=4d9144193f) | Feb 17, 2023 |
| Samsung       | R519/R719                   | [1dc4bc1b72](https://linux-hardware.org/?probe=1dc4bc1b72) | Feb 17, 2023 |
| ASUSTek       | X555QG                      | [75924d49a1](https://linux-hardware.org/?probe=75924d49a1) | Feb 16, 2023 |
| HONOR         | BMH-WCX9                    | [c113bd50f3](https://linux-hardware.org/?probe=c113bd50f3) | Feb 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [650a873a5a](https://linux-hardware.org/?probe=650a873a5a) | Feb 16, 2023 |
| Unknown       | Unknown                     | [7d36f8eee5](https://linux-hardware.org/?probe=7d36f8eee5) | Feb 16, 2023 |
| Timi          | RedmiBook Pro 14S           | [5c807c8516](https://linux-hardware.org/?probe=5c807c8516) | Feb 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4b78132251](https://linux-hardware.org/?probe=4b78132251) | Feb 16, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [9de0373acc](https://linux-hardware.org/?probe=9de0373acc) | Feb 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [b30708ce75](https://linux-hardware.org/?probe=b30708ce75) | Feb 15, 2023 |
| ASUSTek       | 1011PX                      | [f0f2625313](https://linux-hardware.org/?probe=f0f2625313) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [13866e78a2](https://linux-hardware.org/?probe=13866e78a2) | Feb 15, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [b3d3904cef](https://linux-hardware.org/?probe=b3d3904cef) | Feb 15, 2023 |
| Clevo         | NL41MU2                     | [d15806c6c2](https://linux-hardware.org/?probe=d15806c6c2) | Feb 15, 2023 |
| Toshiba       | Satellite U300              | [3925a92635](https://linux-hardware.org/?probe=3925a92635) | Feb 15, 2023 |
| ASUSTek       | K53U                        | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [138839541a](https://linux-hardware.org/?probe=138839541a) | Feb 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [9606f5546e](https://linux-hardware.org/?probe=9606f5546e) | Feb 15, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [e2720c14b7](https://linux-hardware.org/?probe=e2720c14b7) | Feb 15, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [c6166b4ae7](https://linux-hardware.org/?probe=c6166b4ae7) | Feb 15, 2023 |
| HP            | Laptop 15-dw3xxx            | [5dbb939c28](https://linux-hardware.org/?probe=5dbb939c28) | Feb 15, 2023 |
| MSI           | Katana GF66 11SC            | [58fc28f34c](https://linux-hardware.org/?probe=58fc28f34c) | Feb 15, 2023 |
| ASUSTek       | UL30A                       | [90114a4fe4](https://linux-hardware.org/?probe=90114a4fe4) | Feb 14, 2023 |
| HP            | ProBook 440 G7              | [bc4811db07](https://linux-hardware.org/?probe=bc4811db07) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| Valve         | Jupiter                     | [0c496bbe9d](https://linux-hardware.org/?probe=0c496bbe9d) | Feb 14, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [1ebc6ae882](https://linux-hardware.org/?probe=1ebc6ae882) | Feb 14, 2023 |
| Dell          | G3 3579                     | [35c8b69b8c](https://linux-hardware.org/?probe=35c8b69b8c) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | [516a173dcb](https://linux-hardware.org/?probe=516a173dcb) | Feb 14, 2023 |
| ICL           | RAYbook Si1512              | [d1565e917f](https://linux-hardware.org/?probe=d1565e917f) | Feb 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a3b0220b10](https://linux-hardware.org/?probe=a3b0220b10) | Feb 14, 2023 |
| ICL           | RAYbook Si1512              | [aba6ac482b](https://linux-hardware.org/?probe=aba6ac482b) | Feb 14, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [488e3928c6](https://linux-hardware.org/?probe=488e3928c6) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [ac71e5b8ef](https://linux-hardware.org/?probe=ac71e5b8ef) | Feb 14, 2023 |
| Fujitsu       | LIFEBOOK A512               | [92cac1a802](https://linux-hardware.org/?probe=92cac1a802) | Feb 13, 2023 |
| ASUSTek       | GL703VD                     | [409d6e3cb3](https://linux-hardware.org/?probe=409d6e3cb3) | Feb 13, 2023 |
| Unknown       | X133                        | [537237c180](https://linux-hardware.org/?probe=537237c180) | Feb 13, 2023 |
| Acer          | Aspire E5-771G              | [d1abb191dd](https://linux-hardware.org/?probe=d1abb191dd) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [2809288f6f](https://linux-hardware.org/?probe=2809288f6f) | Feb 13, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [c72c5cf640](https://linux-hardware.org/?probe=c72c5cf640) | Feb 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f701208fd4](https://linux-hardware.org/?probe=f701208fd4) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [56ecf82de8](https://linux-hardware.org/?probe=56ecf82de8) | Feb 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [55a63c3dce](https://linux-hardware.org/?probe=55a63c3dce) | Feb 13, 2023 |
| Dell          | Latitude 7490               | [c3f07cbb13](https://linux-hardware.org/?probe=c3f07cbb13) | Feb 13, 2023 |
| ASUSTek       | X556UQ                      | [b2f1a951a1](https://linux-hardware.org/?probe=b2f1a951a1) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [95af064bd1](https://linux-hardware.org/?probe=95af064bd1) | Feb 13, 2023 |
| ASUSTek       | 1011PX                      | [570fd77e58](https://linux-hardware.org/?probe=570fd77e58) | Feb 13, 2023 |
| HP            | ProBook 6470b               | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [3f25b64868](https://linux-hardware.org/?probe=3f25b64868) | Feb 13, 2023 |
| ASUSTek       | X205TA                      | [dfc9ada1af](https://linux-hardware.org/?probe=dfc9ada1af) | Feb 13, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0560a363b8](https://linux-hardware.org/?probe=0560a363b8) | Feb 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [cde8e637d2](https://linux-hardware.org/?probe=cde8e637d2) | Feb 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [a3ac4db738](https://linux-hardware.org/?probe=a3ac4db738) | Feb 12, 2023 |
| Sony          | VPCX11Z6R                   | [ad87a45a26](https://linux-hardware.org/?probe=ad87a45a26) | Feb 12, 2023 |
| HUAWEI        | MRGF-XX                     | [eb1a1cd25b](https://linux-hardware.org/?probe=eb1a1cd25b) | Feb 12, 2023 |
| Haier         | A1410ED                     | [5c90c9c566](https://linux-hardware.org/?probe=5c90c9c566) | Feb 12, 2023 |
| HP            | ProBook 430 G1              | [8d414de313](https://linux-hardware.org/?probe=8d414de313) | Feb 12, 2023 |
| ASUSTek       | N61Jv                       | [4b94eea923](https://linux-hardware.org/?probe=4b94eea923) | Feb 12, 2023 |
| ASUSTek       | N61Jv                       | [15b41bf352](https://linux-hardware.org/?probe=15b41bf352) | Feb 12, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [8f74caf33e](https://linux-hardware.org/?probe=8f74caf33e) | Feb 12, 2023 |
| Lenovo        | G505 20240                  | [eeda09fb13](https://linux-hardware.org/?probe=eeda09fb13) | Feb 12, 2023 |
| ASUSTek       | UX31LA                      | [289ceedf30](https://linux-hardware.org/?probe=289ceedf30) | Feb 12, 2023 |
| ASUSTek       | UX31LA                      | [2c6fb8e625](https://linux-hardware.org/?probe=2c6fb8e625) | Feb 12, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [da4802f871](https://linux-hardware.org/?probe=da4802f871) | Feb 12, 2023 |
| Sony          | SVE14A2V1RWI                | [09509862be](https://linux-hardware.org/?probe=09509862be) | Feb 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [b54b603772](https://linux-hardware.org/?probe=b54b603772) | Feb 12, 2023 |
| Chuwi         | CoreBook X                  | [faf97ec5ac](https://linux-hardware.org/?probe=faf97ec5ac) | Feb 12, 2023 |
| MSI           | Modern 14 B11MOU            | [547c8e5750](https://linux-hardware.org/?probe=547c8e5750) | Feb 12, 2023 |
| Unknown       | Unknown                     | [e28dc371df](https://linux-hardware.org/?probe=e28dc371df) | Feb 12, 2023 |
| Haier         | GG1500A                     | [4c4598157f](https://linux-hardware.org/?probe=4c4598157f) | Feb 12, 2023 |
| Acer          | Aspire 5742G                | [b090683ed1](https://linux-hardware.org/?probe=b090683ed1) | Feb 12, 2023 |
| ASUSTek       | 1025C                       | [a5ae0e6be9](https://linux-hardware.org/?probe=a5ae0e6be9) | Feb 11, 2023 |
| Unknown       | Unknown                     | [e0fd4c1db9](https://linux-hardware.org/?probe=e0fd4c1db9) | Feb 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [b8e6f8a4a9](https://linux-hardware.org/?probe=b8e6f8a4a9) | Feb 11, 2023 |
| HP            | Laptop 15-dw3xxx            | [04f66764c7](https://linux-hardware.org/?probe=04f66764c7) | Feb 11, 2023 |
| HP            | Laptop 14s-dq0xxx           | [2a6b583e08](https://linux-hardware.org/?probe=2a6b583e08) | Feb 11, 2023 |
| MSI           | Alpha 15 A3DDK              | [fc04f9445d](https://linux-hardware.org/?probe=fc04f9445d) | Feb 11, 2023 |
| HP            | Pavilion dv7                | [2f694f36cc](https://linux-hardware.org/?probe=2f694f36cc) | Feb 10, 2023 |
| IBM           | ThinkPad T41 23731HG        | [3f4c1d8c96](https://linux-hardware.org/?probe=3f4c1d8c96) | Feb 10, 2023 |
| ASUSTek       | X75VC                       | [7ae38b7947](https://linux-hardware.org/?probe=7ae38b7947) | Feb 10, 2023 |
| Lenovo        | G70-80 80FF                 | [ade67f432f](https://linux-hardware.org/?probe=ade67f432f) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [09073fcfc8](https://linux-hardware.org/?probe=09073fcfc8) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e2661330b8](https://linux-hardware.org/?probe=e2661330b8) | Feb 10, 2023 |
| HP            | G62                         | [8bc9454fb1](https://linux-hardware.org/?probe=8bc9454fb1) | Feb 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5e82ed12a7](https://linux-hardware.org/?probe=5e82ed12a7) | Feb 10, 2023 |
| Valve         | Jupiter                     | [96e636e3b3](https://linux-hardware.org/?probe=96e636e3b3) | Feb 09, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [5da4717c82](https://linux-hardware.org/?probe=5da4717c82) | Feb 09, 2023 |
| Acer          | Aspire V3-771               | [5e29ff0071](https://linux-hardware.org/?probe=5e29ff0071) | Feb 09, 2023 |
| Apple         | MacBook10,1                 | [1d29cd0c56](https://linux-hardware.org/?probe=1d29cd0c56) | Feb 09, 2023 |
| HP            | ENVY 15                     | [ff7562cd96](https://linux-hardware.org/?probe=ff7562cd96) | Feb 09, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [d0f9bc7752](https://linux-hardware.org/?probe=d0f9bc7752) | Feb 09, 2023 |
| Valve         | Jupiter                     | [ce0bad32f4](https://linux-hardware.org/?probe=ce0bad32f4) | Feb 09, 2023 |
| Acer          | Aspire A315-59              | [78d55087bb](https://linux-hardware.org/?probe=78d55087bb) | Feb 08, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [95f88cc4d8](https://linux-hardware.org/?probe=95f88cc4d8) | Feb 08, 2023 |
| HP            | Laptop 15-dw3xxx            | [6a29b69b32](https://linux-hardware.org/?probe=6a29b69b32) | Feb 08, 2023 |
| Notebook      | W65_67SJ                    | [6f4b26218a](https://linux-hardware.org/?probe=6f4b26218a) | Feb 08, 2023 |
| Lenovo        | G50-80 80E5                 | [ea138517da](https://linux-hardware.org/?probe=ea138517da) | Feb 08, 2023 |
| Notebook      | W65_67SJ                    | [1736d50901](https://linux-hardware.org/?probe=1736d50901) | Feb 08, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [3e0851346e](https://linux-hardware.org/?probe=3e0851346e) | Feb 08, 2023 |
| Samsung       | R519/R719                   | [b67d6600ae](https://linux-hardware.org/?probe=b67d6600ae) | Feb 08, 2023 |
| Infinix       | INBOOK X2 GEN11             | [afcd0ead29](https://linux-hardware.org/?probe=afcd0ead29) | Feb 08, 2023 |
| Infinix       | INBOOK X2 GEN11             | [45686da556](https://linux-hardware.org/?probe=45686da556) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [bc2ea675c8](https://linux-hardware.org/?probe=bc2ea675c8) | Feb 08, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [cd84a3ed54](https://linux-hardware.org/?probe=cd84a3ed54) | Feb 08, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [5872694b2c](https://linux-hardware.org/?probe=5872694b2c) | Feb 08, 2023 |
| Toshiba       | Satellite L450              | [5a16ded274](https://linux-hardware.org/?probe=5a16ded274) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c3fd4be797](https://linux-hardware.org/?probe=c3fd4be797) | Feb 08, 2023 |
| Acer          | Aspire A517-51              | [ab27353a60](https://linux-hardware.org/?probe=ab27353a60) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [e58b6f75be](https://linux-hardware.org/?probe=e58b6f75be) | Feb 07, 2023 |
| Dell          | Inspiron 5575               | [1620065d9c](https://linux-hardware.org/?probe=1620065d9c) | Feb 07, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2a21f87922](https://linux-hardware.org/?probe=2a21f87922) | Feb 07, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d3b63de821](https://linux-hardware.org/?probe=d3b63de821) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | [325806b7cc](https://linux-hardware.org/?probe=325806b7cc) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | [870a2912c9](https://linux-hardware.org/?probe=870a2912c9) | Feb 07, 2023 |
| THUNDEROBO... | 911 Plus                    | [63fe672aa8](https://linux-hardware.org/?probe=63fe672aa8) | Feb 07, 2023 |
| Acer          | Aspire E1-570G              | [079f741109](https://linux-hardware.org/?probe=079f741109) | Feb 07, 2023 |
| ASUSTek       | X556UQ                      | [8521058f7c](https://linux-hardware.org/?probe=8521058f7c) | Feb 07, 2023 |
| ASUSTek       | X75VC                       | [d383aec031](https://linux-hardware.org/?probe=d383aec031) | Feb 06, 2023 |
| HUAWEI        | KLVD-WXX9                   | [83d8c56a17](https://linux-hardware.org/?probe=83d8c56a17) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a2172caf56](https://linux-hardware.org/?probe=a2172caf56) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [77faeb6b52](https://linux-hardware.org/?probe=77faeb6b52) | Feb 06, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | [8fb9d5ae65](https://linux-hardware.org/?probe=8fb9d5ae65) | Feb 06, 2023 |
| HONOR         | NBR-WAX9                    | [89ff251118](https://linux-hardware.org/?probe=89ff251118) | Feb 06, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | [ced0a536d0](https://linux-hardware.org/?probe=ced0a536d0) | Feb 06, 2023 |
| Acer          | Aspire E5-573G              | [b0c2be9f04](https://linux-hardware.org/?probe=b0c2be9f04) | Feb 06, 2023 |
| Irbis         | NB143                       | [ab3b895f6e](https://linux-hardware.org/?probe=ab3b895f6e) | Feb 06, 2023 |
| HONOR         | NBR-WAX9                    | [b045a54f0b](https://linux-hardware.org/?probe=b045a54f0b) | Feb 06, 2023 |
| Machcreato... | 14                          | [2fd1f39db5](https://linux-hardware.org/?probe=2fd1f39db5) | Feb 06, 2023 |
| MSI           | Alpha 15 B5EEK              | [47f300cd75](https://linux-hardware.org/?probe=47f300cd75) | Feb 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ebbbcf807a](https://linux-hardware.org/?probe=ebbbcf807a) | Feb 06, 2023 |
| ASUSTek       | X751LD                      | [12d5592082](https://linux-hardware.org/?probe=12d5592082) | Feb 06, 2023 |
| HP            | Pavilion 15                 | [eb37d7677c](https://linux-hardware.org/?probe=eb37d7677c) | Feb 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [bb0481d7a8](https://linux-hardware.org/?probe=bb0481d7a8) | Feb 06, 2023 |
| Aquarius      | NS585                       | [e9deef3f9e](https://linux-hardware.org/?probe=e9deef3f9e) | Feb 06, 2023 |
| HP            | Laptop 17-by3xxx            | [07ea9d3c2f](https://linux-hardware.org/?probe=07ea9d3c2f) | Feb 06, 2023 |
| Dell          | Inspiron N5110              | [9d66ef100a](https://linux-hardware.org/?probe=9d66ef100a) | Feb 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [24a06b8c0c](https://linux-hardware.org/?probe=24a06b8c0c) | Feb 05, 2023 |
| THUNDEROBO... | 911 Plus                    | [bae8523a8a](https://linux-hardware.org/?probe=bae8523a8a) | Feb 05, 2023 |
| Sony          | VPCY11M1R                   | [2de520036a](https://linux-hardware.org/?probe=2de520036a) | Feb 05, 2023 |
| Toshiba       | Satellite A300              | [d9e6b637ca](https://linux-hardware.org/?probe=d9e6b637ca) | Feb 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [69b76f313e](https://linux-hardware.org/?probe=69b76f313e) | Feb 05, 2023 |
| Unknown       | Unknown                     | [a1d5804885](https://linux-hardware.org/?probe=a1d5804885) | Feb 05, 2023 |
| Unknown       | Unknown                     | [73ace1ae6c](https://linux-hardware.org/?probe=73ace1ae6c) | Feb 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5829f2d4a3](https://linux-hardware.org/?probe=5829f2d4a3) | Feb 05, 2023 |
| ASUSTek       | X751LD                      | [13948b75ae](https://linux-hardware.org/?probe=13948b75ae) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [01d18f739c](https://linux-hardware.org/?probe=01d18f739c) | Feb 04, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [3301121a5c](https://linux-hardware.org/?probe=3301121a5c) | Feb 04, 2023 |
| Timi          | A34S                        | [97aed45fe2](https://linux-hardware.org/?probe=97aed45fe2) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | [38cdc2564e](https://linux-hardware.org/?probe=38cdc2564e) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | [8c2a91c204](https://linux-hardware.org/?probe=8c2a91c204) | Feb 04, 2023 |
| Apple         | MacBookPro8,2               | [b5cf758a2a](https://linux-hardware.org/?probe=b5cf758a2a) | Feb 04, 2023 |
| MSI           | Alpha 15 B5EEK              | [b95575866c](https://linux-hardware.org/?probe=b95575866c) | Feb 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b71a6e4da9](https://linux-hardware.org/?probe=b71a6e4da9) | Feb 04, 2023 |
| Timi          | A34S                        | [55208c4210](https://linux-hardware.org/?probe=55208c4210) | Feb 04, 2023 |
| Lenovo        | ThinkPad E490 20N8005TRT    | [d9aca3e679](https://linux-hardware.org/?probe=d9aca3e679) | Feb 04, 2023 |
| ASUSTek       | K52JT                       | [fa36e91793](https://linux-hardware.org/?probe=fa36e91793) | Feb 04, 2023 |
| Acer          | AO756                       | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| Dell          | Inspiron N5040              | [fc65b60f9b](https://linux-hardware.org/?probe=fc65b60f9b) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [fa1e255519](https://linux-hardware.org/?probe=fa1e255519) | Feb 03, 2023 |
| Haier         | GG1500A                     | [b54ce000d3](https://linux-hardware.org/?probe=b54ce000d3) | Feb 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [d7fff6982b](https://linux-hardware.org/?probe=d7fff6982b) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [ada6dd2b76](https://linux-hardware.org/?probe=ada6dd2b76) | Feb 03, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [4608209d2d](https://linux-hardware.org/?probe=4608209d2d) | Feb 03, 2023 |
| MSI           | GP60 2OD                    | [5c91f4e591](https://linux-hardware.org/?probe=5c91f4e591) | Feb 03, 2023 |
| Acer          | Aspire A715-42G             | [0a29f42fab](https://linux-hardware.org/?probe=0a29f42fab) | Feb 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [c26575b761](https://linux-hardware.org/?probe=c26575b761) | Feb 03, 2023 |
| ASUSTek       | UL30A                       | [11885376b2](https://linux-hardware.org/?probe=11885376b2) | Feb 03, 2023 |
| MSI           | GP60 2OD                    | [6820f98769](https://linux-hardware.org/?probe=6820f98769) | Feb 03, 2023 |
| Aquarius      | NS585                       | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| Acer          | Aspire 8935G                | [44ab3ebac0](https://linux-hardware.org/?probe=44ab3ebac0) | Feb 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2f2c8adb0c](https://linux-hardware.org/?probe=2f2c8adb0c) | Feb 02, 2023 |
| GPD           | G1619-04                    | [958fa49a0e](https://linux-hardware.org/?probe=958fa49a0e) | Feb 02, 2023 |
| Unknown       | Unknown                     | [473e2a88ed](https://linux-hardware.org/?probe=473e2a88ed) | Feb 02, 2023 |
| Unknown       | Unknown                     | [fcf96d41f6](https://linux-hardware.org/?probe=fcf96d41f6) | Feb 02, 2023 |
| Acer          | Swift SF314-52              | [62ead89718](https://linux-hardware.org/?probe=62ead89718) | Feb 02, 2023 |
| Lenovo        | B590 20206                  | [13608ab0e1](https://linux-hardware.org/?probe=13608ab0e1) | Feb 02, 2023 |
| Lenovo        | G700 20251                  | [2eb468b1b9](https://linux-hardware.org/?probe=2eb468b1b9) | Feb 02, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e49b22de8a](https://linux-hardware.org/?probe=e49b22de8a) | Feb 02, 2023 |
| Acer          | TravelMate P633-M           | [b9bb5f3746](https://linux-hardware.org/?probe=b9bb5f3746) | Feb 02, 2023 |
| ASUSTek       | K50IJ                       | [044d301912](https://linux-hardware.org/?probe=044d301912) | Feb 02, 2023 |
| Unknown       | Unknown                     | [477c99e664](https://linux-hardware.org/?probe=477c99e664) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [159a453649](https://linux-hardware.org/?probe=159a453649) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0538afb301](https://linux-hardware.org/?probe=0538afb301) | Feb 02, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [81e773eade](https://linux-hardware.org/?probe=81e773eade) | Feb 02, 2023 |
| MSI           | MS-N0E1 Ver                 | [9c4dcef9c6](https://linux-hardware.org/?probe=9c4dcef9c6) | Feb 01, 2023 |
| Lenovo        | ThinkPad T490 20N2000LRT    | [aaaf227faf](https://linux-hardware.org/?probe=aaaf227faf) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [eaaf15f3f6](https://linux-hardware.org/?probe=eaaf15f3f6) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ee219f2f82](https://linux-hardware.org/?probe=ee219f2f82) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [af2f6edc6f](https://linux-hardware.org/?probe=af2f6edc6f) | Feb 01, 2023 |
| ASUSTek       | N552VW                      | [1ebeeec517](https://linux-hardware.org/?probe=1ebeeec517) | Feb 01, 2023 |
| Dell          | Inspiron 5748               | [7ee6505f8d](https://linux-hardware.org/?probe=7ee6505f8d) | Feb 01, 2023 |
| Acer          | Nitro AN515-52              | [86156a3b50](https://linux-hardware.org/?probe=86156a3b50) | Jan 31, 2023 |
| Acer          | Aspire E1-522               | [af61a3d9c8](https://linux-hardware.org/?probe=af61a3d9c8) | Jan 31, 2023 |
| Dell          | Inspiron 5748               | [ecbd4ac8b6](https://linux-hardware.org/?probe=ecbd4ac8b6) | Jan 31, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [7758d7c535](https://linux-hardware.org/?probe=7758d7c535) | Jan 31, 2023 |
| Aquarius      | Cmp NS685U                  | [b067e76e64](https://linux-hardware.org/?probe=b067e76e64) | Jan 31, 2023 |
| Clevo         | NL41MU2                     | [95dac05397](https://linux-hardware.org/?probe=95dac05397) | Jan 31, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [396877a008](https://linux-hardware.org/?probe=396877a008) | Jan 31, 2023 |
| Lenovo        | ThinkPad T410 2518BPG       | [011f53deaa](https://linux-hardware.org/?probe=011f53deaa) | Jan 31, 2023 |
| ASUSTek       | N53Ta                       | [30131c7409](https://linux-hardware.org/?probe=30131c7409) | Jan 31, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ROSA R10         | 1493      | 11.11%  |
| ROSA R11         | 1442      | 10.73%  |
| ROSA R8.1        | 1042      | 7.76%   |
| ROSA R8          | 919       | 6.84%   |
| ROSA R9          | 845       | 6.29%   |
| ROSA 12.2        | 778       | 5.79%   |
| ROSA R11.1       | 777       | 5.78%   |
| Ubuntu 20.04     | 482       | 3.59%   |
| ROSA 12.3        | 341       | 2.54%   |
| Debian 11        | 269       | 2%      |
| Ubuntu 18.04     | 256       | 1.91%   |
| Ubuntu 22.04     | 190       | 1.41%   |
| OpenMandriva 4.2 | 160       | 1.19%   |
| ROSA 12.1        | 111       | 0.83%   |
| Arch Rolling     | 110       | 0.82%   |
| KDE neon 20.04   | 104       | 0.77%   |
| OpenMandriva 4.3 | 100       | 0.74%   |
| Arch             | 98        | 0.73%   |
| Fedora 37        | 97        | 0.72%   |
| Fedora 36        | 93        | 0.69%   |
| Manjaro          | 85        | 0.63%   |
| Linux Mint 19.3  | 84        | 0.63%   |
| Linux Mint 20.3  | 71        | 0.53%   |
| Fedora 35        | 71        | 0.53%   |
| ROSA 12.4        | 70        | 0.52%   |
| Linux Mint 20.1  | 69        | 0.51%   |
| Kubuntu 20.04    | 60        | 0.45%   |
| Debian 10        | 60        | 0.45%   |
| Linux Mint 19.1  | 59        | 0.44%   |
| Linux Mint 18.3  | 59        | 0.44%   |
| Linux Mint 20    | 57        | 0.42%   |
| Fedora 34        | 57        | 0.42%   |
| Linux Mint 19.2  | 55        | 0.41%   |
| Kometa P10       | 54        | 0.4%    |
| Ubuntu 21.10     | 52        | 0.39%   |
| Linux Mint 20.2  | 49        | 0.36%   |
| Xubuntu 18.04    | 48        | 0.36%   |
| Linux Mint 21    | 47        | 0.35%   |
| Ubuntu 19.10     | 46        | 0.34%   |
| Xubuntu 20.04    | 45        | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| ROSA          | 6779      | 56.7%   |
| Ubuntu        | 1182      | 9.89%   |
| Linux Mint    | 609       | 5.09%   |
| Fedora        | 402       | 3.36%   |
| Debian        | 380       | 3.18%   |
| OpenMandriva  | 355       | 2.97%   |
| Manjaro       | 333       | 2.79%   |
| Endless       | 214       | 1.79%   |
| ALT Linux     | 209       | 1.75%   |
| Arch          | 197       | 1.65%   |
| Kubuntu       | 145       | 1.21%   |
| KDE neon      | 138       | 1.15%   |
| Xubuntu       | 121       | 1.01%   |
| Red OS        | 86        | 0.72%   |
| Pop!_OS       | 86        | 0.72%   |
| Kali          | 63        | 0.53%   |
| Gentoo        | 56        | 0.47%   |
| Elementary    | 54        | 0.45%   |
| RED           | 46        | 0.38%   |
| openSUSE      | 45        | 0.38%   |
| Lubuntu       | 41        | 0.34%   |
| LMDE          | 39        | 0.33%   |
| Zorin         | 35        | 0.29%   |
| Ubuntu MATE   | 31        | 0.26%   |
| Clear Linux   | 31        | 0.26%   |
| Ubuntu Unity  | 25        | 0.21%   |
| ArcoLinux     | 20        | 0.17%   |
| SteamOS       | 19        | 0.16%   |
| EndeavourOS   | 13        | 0.11%   |
| CentOS        | 13        | 0.11%   |
| Astra Linux   | 13        | 0.11%   |
| Artix         | 13        | 0.11%   |
| Ubuntu Budgie | 12        | 0.1%    |
| MX            | 12        | 0.1%    |
| RELS          | 11        | 0.09%   |
| Parrot        | 11        | 0.09%   |
| Void Linux    | 8         | 0.07%   |
| Calculate     | 8         | 0.07%   |
| antiX         | 7         | 0.06%   |
| Nobara        | 6         | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 656       | 4.54%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 621       | 4.3%    |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 620       | 4.29%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 585       | 4.05%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 349       | 2.42%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 278       | 1.92%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 275       | 1.9%    |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 236       | 1.63%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 218       | 1.51%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 200       | 1.38%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 175       | 1.21%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 175       | 1.21%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 174       | 1.2%    |
| 4.15.0-desktop-45.1rosa-i586        | 172       | 1.19%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 169       | 1.17%   |
| 5.10.14-desktop-1omv4002            | 155       | 1.07%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 147       | 1.02%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 147       | 1.02%   |
| 5.4.32-generic-2rosa-x86_64         | 146       | 1.01%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 146       | 1.01%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 138       | 0.96%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 137       | 0.95%   |
| 5.4.83-generic-2rosa-x86_64         | 132       | 0.91%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 116       | 0.8%    |
| 5.10.0-7-amd64                      | 110       | 0.76%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 107       | 0.74%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 106       | 0.73%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 96        | 0.66%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 96        | 0.66%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 94        | 0.65%   |
| 5.16.7-desktop-1omv4003             | 90        | 0.62%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 90        | 0.62%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 78        | 0.54%   |
| 5.4.0-42-generic                    | 71        | 0.49%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 69        | 0.48%   |
| 5.4.32-generic-2rosa-i586           | 62        | 0.43%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 59        | 0.41%   |
| 4.9.41-nrj-desktop-1rosa-i586       | 58        | 0.4%    |
| 5.15.0-56-generic                   | 56        | 0.39%   |
| 4.1.38-nrj-desktop-1rosa-x86_64     | 56        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 1887      | 13.49%  |
| 4.9.60   | 820       | 5.86%   |
| 4.9.20   | 762       | 5.45%   |
| 5.4.0    | 712       | 5.09%   |
| 5.10.74  | 689       | 4.93%   |
| 4.1.34   | 497       | 3.55%   |
| 4.1.38   | 394       | 2.82%   |
| 4.9.9    | 374       | 2.67%   |
| 5.15.0   | 369       | 2.64%   |
| 4.9.124  | 357       | 2.55%   |
| 4.1.25   | 327       | 2.34%   |
| 5.10.0   | 318       | 2.27%   |
| 5.3.0    | 251       | 1.79%   |
| 4.9.41   | 235       | 1.68%   |
| 4.9.76   | 230       | 1.64%   |
| 5.11.0   | 209       | 1.49%   |
| 5.4.32   | 208       | 1.49%   |
| 4.9.155  | 207       | 1.48%   |
| 5.8.0    | 204       | 1.46%   |
| 5.13.0   | 196       | 1.4%    |
| 5.4.83   | 175       | 1.25%   |
| 5.0.0    | 170       | 1.22%   |
| 5.10.14  | 158       | 1.13%   |
| 5.10.118 | 154       | 1.1%    |
| 5.15.75  | 144       | 1.03%   |
| 4.9.95   | 124       | 0.89%   |
| 5.19.0   | 109       | 0.78%   |
| 5.15.79  | 98        | 0.7%    |
| 4.18.0   | 95        | 0.68%   |
| 4.13.0   | 93        | 0.67%   |
| 5.16.7   | 92        | 0.66%   |
| 4.9.111  | 81        | 0.58%   |
| 4.19.0   | 73        | 0.52%   |
| 6.1.0    | 61        | 0.44%   |
| 4.9.87   | 58        | 0.41%   |
| 6.1.20   | 57        | 0.41%   |
| 6.1.1    | 45        | 0.32%   |
| 4.9.14   | 44        | 0.31%   |
| 5.17.11  | 43        | 0.31%   |
| 5.10.71  | 43        | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 2896      | 22%     |
| 4.15    | 1902      | 14.45%  |
| 5.10    | 1593      | 12.1%   |
| 5.4     | 1225      | 9.31%   |
| 4.1     | 1200      | 9.12%   |
| 5.15    | 934       | 7.1%    |
| 5.3     | 291       | 2.21%   |
| 5.11    | 277       | 2.1%    |
| 5.8     | 264       | 2.01%   |
| 6.1     | 263       | 2%      |
| 5.13    | 256       | 1.95%   |
| 5.0     | 178       | 1.35%   |
| 5.19    | 169       | 1.28%   |
| 5.16    | 166       | 1.26%   |
| 6.0     | 142       | 1.08%   |
| 5.17    | 129       | 0.98%   |
| 5.18    | 118       | 0.9%    |
| 4.19    | 113       | 0.86%   |
| 4.18    | 110       | 0.84%   |
| 4.13    | 109       | 0.83%   |
| 6.2     | 105       | 0.8%    |
| 5.14    | 92        | 0.7%    |
| 5.6     | 88        | 0.67%   |
| 5.9     | 69        | 0.52%   |
| 4.4     | 50        | 0.38%   |
| 4.16    | 50        | 0.38%   |
| 5.7     | 49        | 0.37%   |
| 5.12    | 48        | 0.36%   |
| 5.5     | 41        | 0.31%   |
| 4.8     | 37        | 0.28%   |
| 4.10    | 35        | 0.27%   |
| 3.14    | 20        | 0.15%   |
| 4.14    | 19        | 0.14%   |
| 5.2     | 18        | 0.14%   |
| 3.10    | 16        | 0.12%   |
| 4.17    | 14        | 0.11%   |
| 4.12    | 13        | 0.1%    |
| 5.1     | 12        | 0.09%   |
| 4.11    | 12        | 0.09%   |
| 4.7     | 9         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 10122     | 85.84%  |
| i686    | 1664      | 14.11%  |
| armv7l  | 4         | 0.03%   |
| ppc     | 1         | 0.01%   |
| aarch64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| KDE4               | 4148      | 33.26%  |
| KDE5               | 3168      | 25.4%   |
| GNOME              | 2312      | 18.54%  |
| Unknown            | 707       | 5.67%   |
| XFCE               | 480       | 3.85%   |
| LXQt               | 418       | 3.35%   |
| MATE               | 326       | 2.61%   |
| X-Cinnamon         | 257       | 2.06%   |
| Cinnamon           | 251       | 2.01%   |
| KDE                | 165       | 1.32%   |
| Pantheon           | 51        | 0.41%   |
| i3                 | 35        | 0.28%   |
| LXDE               | 29        | 0.23%   |
| Unity              | 25        | 0.2%    |
| Budgie             | 21        | 0.17%   |
| GNOME Flashback    | 16        | 0.13%   |
| sway               | 12        | 0.1%    |
| fly                | 9         | 0.07%   |
| Deepin             | 6         | 0.05%   |
| icewm              | 4         | 0.03%   |
| DWM                | 4         | 0.03%   |
| awesome            | 4         | 0.03%   |
| Trinity            | 3         | 0.02%   |
| Openbox            | 3         | 0.02%   |
| GNOME Classic      | 3         | 0.02%   |
| fluxbox            | 3         | 0.02%   |
| xmonad             | 2         | 0.02%   |
| bspwm              | 2         | 0.02%   |
| qtile              | 1         | 0.01%   |
| pantheon-non-gnome | 1         | 0.01%   |
| none+i3            | 1         | 0.01%   |
| Lumina             | 1         | 0.01%   |
| Lubuntu            | 1         | 0.01%   |
| lightdm-xsession   | 1         | 0.01%   |
| Enlightenment      | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 9652      | 80.68%  |
| Wayland | 1819      | 15.21%  |
| Unknown | 411       | 3.44%   |
| Tty     | 80        | 0.67%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDM     | 4167      | 33.52%  |
| SDDM    | 3257      | 26.2%   |
| Unknown | 2097      | 16.87%  |
| GDM     | 1446      | 11.63%  |
| LightDM | 620       | 4.99%   |
| TDM     | 433       | 3.48%   |
| GDM3    | 348       | 2.8%    |
| MDM     | 21        | 0.17%   |
| XDM     | 17        | 0.14%   |
| SLiM    | 8         | 0.06%   |
| FLY-DM  | 5         | 0.04%   |
| NODM    | 3         | 0.02%   |
| Ly      | 3         | 0.02%   |
| GREETD  | 3         | 0.02%   |
| LXDM    | 2         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 5801      | 47.89%  |
| ru_RU       | 4875      | 40.24%  |
| en_US       | 1243      | 10.26%  |
| C           | 67        | 0.55%   |
| en_GB       | 53        | 0.44%   |
| ru_RU.UTF_8 | 19        | 0.16%   |
| ru_UA       | 8         | 0.07%   |
| zh_CN       | 4         | 0.03%   |
| POSIX       | 4         | 0.03%   |
| en_AG       | 4         | 0.03%   |
| C.UTF8      | 4         | 0.03%   |
| en_CA       | 3         | 0.02%   |
| de_DE       | 3         | 0.02%   |
| ba_RU       | 3         | 0.02%   |
| uk_UA       | 2         | 0.02%   |
| tr_TR       | 2         | 0.02%   |
| it_IT       | 2         | 0.02%   |
| fr_FR       | 2         | 0.02%   |
| es_ES       | 2         | 0.02%   |
| cv_RU       | 2         | 0.02%   |
| tt_RU       | 1         | 0.01%   |
| ru_RU.UTF8  | 1         | 0.01%   |
| pt_BR       | 1         | 0.01%   |
| myv_RU      | 1         | 0.01%   |
| ja_JP       | 1         | 0.01%   |
| en_NZ       | 1         | 0.01%   |
| en_IL       | 1         | 0.01%   |
| en_GB.utf-8 | 1         | 0.01%   |
| en_DK       | 1         | 0.01%   |
| en_AU       | 1         | 0.01%   |
| en-US       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 6862      | 57.7%   |
| EFI  | 5031      | 42.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 7330      | 59.51%  |
| Unknown  | 3579      | 29.06%  |
| Btrfs    | 704       | 5.72%   |
| Overlay  | 535       | 4.34%   |
| Xfs      | 58        | 0.47%   |
| Zfs      | 25        | 0.2%    |
| Ext3     | 21        | 0.17%   |
| Ext2     | 20        | 0.16%   |
| Aufs     | 16        | 0.13%   |
| Tmpfs    | 10        | 0.08%   |
| F2fs     | 9         | 0.07%   |
| Rootfs   | 3         | 0.02%   |
| Reiserfs | 3         | 0.02%   |
| XXXXXXX  | 1         | 0.01%   |
| XXXXX    | 1         | 0.01%   |
| Ufs      | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 4596      | 37.39%  |
| GPT     | 4186      | 34.05%  |
| Unknown | 3511      | 28.56%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10634     | 88.68%  |
| Yes       | 1357      | 11.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 8759      | 72.35%  |
| Yes       | 3348      | 27.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 2139      | 18.34%  |
| ASUSTek Computer    | 2071      | 17.76%  |
| Hewlett-Packard     | 1690      | 14.49%  |
| Acer                | 1614      | 13.84%  |
| Dell                | 829       | 7.11%   |
| Samsung Electronics | 647       | 5.55%   |
| Toshiba             | 291       | 2.49%   |
| MSI                 | 290       | 2.49%   |
| Sony                | 266       | 2.28%   |
| HUAWEI              | 196       | 1.68%   |
| Packard Bell        | 172       | 1.47%   |
| eMachines           | 115       | 0.99%   |
| Unknown             | 99        | 0.85%   |
| Clevo               | 96        | 0.82%   |
| Apple               | 88        | 0.75%   |
| Timi                | 84        | 0.72%   |
| Aquarius            | 78        | 0.67%   |
| Notebook            | 75        | 0.64%   |
| Pegatron            | 61        | 0.52%   |
| Fujitsu Siemens     | 44        | 0.38%   |
| HONOR               | 43        | 0.37%   |
| Digma               | 42        | 0.36%   |
| Fujitsu             | 39        | 0.33%   |
| DNS                 | 39        | 0.33%   |
| Intel               | 36        | 0.31%   |
| Irbis               | 31        | 0.27%   |
| DEXP                | 30        | 0.26%   |
| Prestigio           | 28        | 0.24%   |
| Quanta              | 27        | 0.23%   |
| ICL                 | 26        | 0.22%   |
| Chuwi               | 20        | 0.17%   |
| Valve               | 19        | 0.16%   |
| Maibenben           | 19        | 0.16%   |
| Gigabyte Technology | 19        | 0.16%   |
| Haier               | 17        | 0.15%   |
| 3Logic Group        | 15        | 0.13%   |
| Insyde              | 13        | 0.11%   |
| Panasonic           | 11        | 0.09%   |
| Kraftway            | 10        | 0.09%   |
| Infomash            | 10        | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 169       | 1.45%   |
| HP Pavilion g6                             | 124       | 1.06%   |
| HP Notebook                                | 80        | 0.69%   |
| HP Pavilion dv6                            | 79        | 0.68%   |
| HP Laptop 15-bw0xx                         | 76        | 0.65%   |
| Acer Aspire V3-571G                        | 58        | 0.5%    |
| Lenovo G570 20079                          | 52        | 0.45%   |
| Aquarius NS585                             | 50        | 0.43%   |
| Lenovo B570e HuronRiver Platform           | 47        | 0.4%    |
| Lenovo B590 20206                          | 42        | 0.36%   |
| HP Pavilion dv7                            | 42        | 0.36%   |
| Packard Bell EasyNote TE11HC               | 39        | 0.33%   |
| HP Pavilion 15                             | 38        | 0.33%   |
| Lenovo B590 20208                          | 37        | 0.32%   |
| Lenovo G50-45 80E3                         | 36        | 0.31%   |
| HUAWEI NBLK-WAX9X                          | 34        | 0.29%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 33        | 0.28%   |
| Lenovo G500 20236                          | 33        | 0.28%   |
| Lenovo G50-30 80G0                         | 32        | 0.27%   |
| HP Pavilion g7                             | 32        | 0.27%   |
| Dell Inspiron N5110                        | 32        | 0.27%   |
| Toshiba Satellite C660                     | 31        | 0.27%   |
| Lenovo B560                                | 31        | 0.27%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 31        | 0.27%   |
| ASUS K50IJ                                 | 30        | 0.26%   |
| Acer Aspire 5750G                          | 30        | 0.26%   |
| Lenovo G580 20150                          | 29        | 0.25%   |
| Lenovo G580 20157                          | 28        | 0.24%   |
| Acer Aspire E1-571G                        | 28        | 0.24%   |
| Acer Aspire 5742G                          | 28        | 0.24%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 27        | 0.23%   |
| Samsung 300E4C/300E5C/300E7C               | 27        | 0.23%   |
| Clevo NL41MU2                              | 27        | 0.23%   |
| ASUS X550CC                                | 27        | 0.23%   |
| Dell Inspiron 3521                         | 26        | 0.22%   |
| HP Pavilion Notebook                       | 25        | 0.21%   |
| Acer Extensa 2519                          | 25        | 0.21%   |
| Lenovo IdeaPad 110-15ACL 80TJ              | 24        | 0.21%   |
| ASUS X101CH                                | 24        | 0.21%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 23        | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1106      | 9.48%   |
| Lenovo IdeaPad        | 635       | 5.44%   |
| HP Pavilion           | 496       | 4.25%   |
| Lenovo ThinkPad       | 463       | 3.97%   |
| Dell Inspiron         | 411       | 3.52%   |
| ASUS VivoBook         | 293       | 2.51%   |
| HP Laptop             | 289       | 2.48%   |
| Toshiba Satellite     | 270       | 2.31%   |
| HP ProBook            | 254       | 2.18%   |
| Unknown               | 169       | 1.45%   |
| Dell Latitude         | 166       | 1.42%   |
| Packard Bell EasyNote | 151       | 1.29%   |
| Acer Extensa          | 150       | 1.29%   |
| Dell Vostro           | 111       | 0.95%   |
| HP Compaq             | 99        | 0.85%   |
| Acer TravelMate       | 89        | 0.76%   |
| HP EliteBook          | 84        | 0.72%   |
| HP Notebook           | 81        | 0.69%   |
| Lenovo B590           | 79        | 0.68%   |
| Lenovo G580           | 77        | 0.66%   |
| Lenovo ThinkBook      | 68        | 0.58%   |
| Lenovo G570           | 53        | 0.45%   |
| HP 250                | 53        | 0.45%   |
| Acer Swift            | 53        | 0.45%   |
| Acer Nitro            | 53        | 0.45%   |
| Aquarius NS585        | 50        | 0.43%   |
| Lenovo B570e          | 47        | 0.4%    |
| HP ENVY               | 45        | 0.39%   |
| Samsung 300V3A        | 44        | 0.38%   |
| Dell XPS              | 44        | 0.38%   |
| Lenovo Legion         | 43        | 0.37%   |
| Samsung 355V4C        | 42        | 0.36%   |
| ASUS ZenBook          | 42        | 0.36%   |
| Notebook W65          | 41        | 0.35%   |
| ASUS ROG              | 40        | 0.34%   |
| Lenovo G50-45         | 38        | 0.33%   |
| Fujitsu LIFEBOOK      | 38        | 0.33%   |
| HP 255                | 36        | 0.31%   |
| ASUS TUF              | 36        | 0.31%   |
| ASUS ASUS             | 35        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 1472      | 12.62%  |
| 2012    | 1351      | 11.58%  |
| 2010    | 1000      | 8.57%   |
| 2013    | 842       | 7.22%   |
| 2019    | 777       | 6.66%   |
| 2018    | 672       | 5.76%   |
| 2017    | 644       | 5.52%   |
| 2009    | 611       | 5.24%   |
| 2020    | 608       | 5.21%   |
| 2008    | 603       | 5.17%   |
| 2021    | 570       | 4.89%   |
| 2014    | 566       | 4.85%   |
| 2015    | 501       | 4.3%    |
| 2016    | 496       | 4.25%   |
| 2007    | 444       | 3.81%   |
| 2022    | 232       | 1.99%   |
| 2006    | 195       | 1.67%   |
| 2005    | 51        | 0.44%   |
| Unknown | 13        | 0.11%   |
| 2004    | 11        | 0.09%   |
| 2023    | 2         | 0.02%   |
| 2003    | 2         | 0.02%   |
| 2001    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 11664     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 11186     | 95.39%  |
| Enabled  | 540       | 4.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 11648     | 99.86%  |
| Yes  | 16        | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 3431      | 28.65%  |
| 4.01-8.0    | 3247      | 27.11%  |
| 8.01-16.0   | 1628      | 13.59%  |
| 1.01-2.0    | 1435      | 11.98%  |
| 16.01-24.0  | 911       | 7.61%   |
| 2.01-3.0    | 779       | 6.5%    |
| 0.51-1.0    | 263       | 2.2%    |
| 32.01-64.0  | 199       | 1.66%   |
| 24.01-32.0  | 52        | 0.43%   |
| 64.01-256.0 | 17        | 0.14%   |
| 0.01-0.5    | 12        | 0.1%    |
| Unknown     | 3         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 5067      | 38.55%  |
| 0.51-1.0   | 3934      | 29.93%  |
| 2.01-3.0   | 1951      | 14.84%  |
| 3.01-4.0   | 863       | 6.57%   |
| 4.01-8.0   | 814       | 6.19%   |
| 0.01-0.5   | 294       | 2.24%   |
| 8.01-16.0  | 189       | 1.44%   |
| 16.01-24.0 | 14        | 0.11%   |
| Unknown    | 9         | 0.07%   |
| 24.01-32.0 | 7         | 0.05%   |
| 32.01-64.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 9240      | 77.03%  |
| 2       | 2406      | 20.06%  |
| 3       | 247       | 2.06%   |
| 0       | 83        | 0.69%   |
| 4       | 13        | 0.11%   |
| 5       | 5         | 0.04%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6314      | 53.45%  |
| Yes       | 5498      | 46.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10073     | 86.2%   |
| No        | 1612      | 13.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 11449     | 98.05%  |
| No        | 228       | 1.95%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8288      | 70.05%  |
| No        | 3543      | 29.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 11664     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 2549      | 20.31%  |
| St Petersburg    | 1144      | 9.11%   |
| Novosibirsk      | 380       | 3.03%   |
| Krasnodar        | 380       | 3.03%   |
| Voronezh         | 342       | 2.72%   |
| Pecherskoye      | 337       | 2.68%   |
| Yekaterinburg    | 329       | 2.62%   |
| Nizhniy Novgorod | 243       | 1.94%   |
| Samara           | 226       | 1.8%    |
| Perm             | 209       | 1.66%   |
| Chelyabinsk      | 203       | 1.62%   |
| Rostov-on-Don    | 193       | 1.54%   |
| Kazan’         | 154       | 1.23%   |
| Krasnoyarsk      | 146       | 1.16%   |
| Ufa              | 135       | 1.08%   |
| Saratov          | 135       | 1.08%   |
| Omsk             | 114       | 0.91%   |
| Khabarovsk       | 106       | 0.84%   |
| Vladivostok      | 100       | 0.8%    |
| Volgograd        | 99        | 0.79%   |
| Tyumen           | 99        | 0.79%   |
| Barnaul          | 97        | 0.77%   |
| Yaroslavl        | 90        | 0.72%   |
| Irkutsk          | 89        | 0.71%   |
| Kaliningrad      | 87        | 0.69%   |
| Stavropol        | 80        | 0.64%   |
| Kirov            | 76        | 0.61%   |
| Tula             | 71        | 0.57%   |
| Ryazan           | 68        | 0.54%   |
| Ulyanovsk        | 67        | 0.53%   |
| Kemerovo         | 67        | 0.53%   |
| Belgorod         | 67        | 0.53%   |
| Tver             | 66        | 0.53%   |
| Tomsk            | 64        | 0.51%   |
| Surgut           | 64        | 0.51%   |
| Penza            | 56        | 0.45%   |
| Ivanovo          | 56        | 0.45%   |
| Astrakhan        | 55        | 0.44%   |
| Izhevsk          | 54        | 0.43%   |
| Orenburg         | 53        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2597      | 3463   | 18.17%  |
| Seagate             | 2204      | 2882   | 15.42%  |
| Toshiba             | 1398      | 1786   | 9.78%   |
| Samsung Electronics | 1317      | 1767   | 9.21%   |
| Hitachi             | 950       | 1236   | 6.65%   |
| Kingston            | 727       | 892    | 5.09%   |
| Unknown             | 587       | 749    | 4.11%   |
| HGST                | 548       | 766    | 3.83%   |
| SanDisk             | 440       | 568    | 3.08%   |
| SK hynix            | 376       | 480    | 2.63%   |
| Intel               | 310       | 399    | 2.17%   |
| A-DATA Technology   | 250       | 408    | 1.75%   |
| China               | 215       | 281    | 1.5%    |
| Micron Technology   | 159       | 202    | 1.11%   |
| Fujitsu             | 139       | 167    | 0.97%   |
| SPCC                | 123       | 173    | 0.86%   |
| Crucial             | 119       | 148    | 0.83%   |
| KIOXIA              | 94        | 115    | 0.66%   |
| Smartbuy            | 92        | 106    | 0.64%   |
| Apacer              | 90        | 108    | 0.63%   |
| OCZ                 | 87        | 103    | 0.61%   |
| Transcend           | 83        | 107    | 0.58%   |
| Plextor             | 82        | 104    | 0.57%   |
| KingSpec            | 82        | 102    | 0.57%   |
| HUAWEI              | 69        | 77     | 0.48%   |
| Phison              | 59        | 65     | 0.41%   |
| AMD                 | 45        | 51     | 0.31%   |
| Patriot             | 43        | 50     | 0.3%    |
| Apple               | 43        | 55     | 0.3%    |
| Netac               | 41        | 54     | 0.29%   |
| Silicon Motion      | 38        | 48     | 0.27%   |
| Unknown             | 38        | 41     | 0.27%   |
| BIWIN               | 35        | 36     | 0.24%   |
| GOODRAM             | 34        | 37     | 0.24%   |
| KingDian            | 31        | 44     | 0.22%   |
| JMicron Technology  | 31        | 32     | 0.22%   |
| Gigabyte Technology | 31        | 35     | 0.22%   |
| Corsair             | 31        | 39     | 0.22%   |
| Phison Electronics  | 29        | 33     | 0.2%    |
| LITEON              | 25        | 31     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB            | 255       | 1.74%   |
| Seagate ST500LT012-1DG142 500GB     | 254       | 1.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 245       | 1.67%   |
| Seagate ST9500325AS 500GB           | 204       | 1.39%   |
| Seagate ST1000LM035-1RK172 970GB    | 172       | 1.17%   |
| Seagate ST9320325AS 320GB           | 163       | 1.11%   |
| HGST HTS545050A7E680 500GB          | 147       | 1%      |
| Toshiba MQ01ABD100 1TB              | 131       | 0.89%   |
| Toshiba MQ04ABF100 1TB              | 111       | 0.76%   |
| Hitachi HTS543232A7A384 320GB       | 103       | 0.7%    |
| Seagate ST500LT012-9WS142 500GB     | 100       | 0.68%   |
| Seagate ST9250315AS 250GB           | 95        | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 92        | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 90        | 0.61%   |
| Kingston SA400S37240G 240GB SSD     | 90        | 0.61%   |
| HGST HTS545050A7E380 500GB          | 90        | 0.61%   |
| Seagate ST320LT020-9YG142 320GB     | 89        | 0.61%   |
| Kingston SA400S37120G 120GB SSD     | 89        | 0.61%   |
| Hitachi HTS545025B9A300 250GB       | 86        | 0.59%   |
| HGST HTS541010A9E680 1TB            | 85        | 0.58%   |
| Hitachi HTS547550A9E384 500GB       | 84        | 0.57%   |
| HGST HTS721010A9E630 1TB            | 81        | 0.55%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 78        | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB            | 76        | 0.52%   |
| Hitachi HTS547575A9E384 752GB       | 74        | 0.5%    |
| WDC WD5000LPCX-21VHAT0 500GB        | 72        | 0.49%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 69        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 68        | 0.46%   |
| Kingston SV300S37A120G 120GB SSD    | 68        | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 59        | 0.4%    |
| Toshiba MQ01ABD075 752GB            | 59        | 0.4%    |
| Toshiba MQ01ABD050 500GB            | 58        | 0.4%    |
| Samsung NVMe SSD Drive 256GB        | 55        | 0.38%   |
| Samsung HM321HI 320GB               | 55        | 0.38%   |
| A-DATA SU800 512GB SSD              | 54        | 0.37%   |
| Hitachi HTS545050A7E380 500GB       | 53        | 0.36%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 52        | 0.35%   |
| Samsung SSD 860 EVO 250GB           | 52        | 0.35%   |
| Hitachi HTS545032B9A300 320GB       | 51        | 0.35%   |
| Seagate ST1000LM048-2E7172 1TB      | 50        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2193      | 2865   | 29.17%  |
| WDC                 | 2160      | 2893   | 28.73%  |
| Toshiba             | 1234      | 1578   | 16.41%  |
| Hitachi             | 950       | 1236   | 12.63%  |
| HGST                | 548       | 766    | 7.29%   |
| Samsung Electronics | 231       | 277    | 3.07%   |
| Fujitsu             | 138       | 166    | 1.84%   |
| Unknown             | 21        | 27     | 0.28%   |
| JMicron Technology  | 19        | 20     | 0.25%   |
| IBM/Hitachi         | 6         | 6      | 0.08%   |
| Apple               | 4         | 4      | 0.05%   |
| HGST HTS            | 3         | 3      | 0.04%   |
| KESU                | 2         | 2      | 0.03%   |
| ZALMAN              | 1         | 1      | 0.01%   |
| WD MediaMax         | 1         | 2      | 0.01%   |
| SILICONMOTION       | 1         | 1      | 0.01%   |
| QNAP                | 1         | 2      | 0.01%   |
| PHD 3.0             | 1         | 1      | 0.01%   |
| OEM                 | 1         | 2      | 0.01%   |
| MARSHAL             | 1         | 1      | 0.01%   |
| IBM                 | 1         | 1      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 576       | 706    | 15.26%  |
| Samsung Electronics | 550       | 737    | 14.57%  |
| SanDisk             | 270       | 359    | 7.15%   |
| WDC                 | 259       | 300    | 6.86%   |
| A-DATA Technology   | 220       | 369    | 5.83%   |
| China               | 214       | 280    | 5.67%   |
| SPCC                | 119       | 169    | 3.15%   |
| Crucial             | 114       | 142    | 3.02%   |
| Intel               | 113       | 146    | 2.99%   |
| Smartbuy            | 89        | 103    | 2.36%   |
| OCZ                 | 87        | 103    | 2.3%    |
| SK hynix            | 82        | 101    | 2.17%   |
| Plextor             | 82        | 104    | 2.17%   |
| KingSpec            | 82        | 102    | 2.17%   |
| Transcend           | 80        | 101    | 2.12%   |
| Apacer              | 78        | 94     | 2.07%   |
| Toshiba             | 70        | 89     | 1.85%   |
| Micron Technology   | 59        | 87     | 1.56%   |
| Patriot             | 43        | 50     | 1.14%   |
| AMD                 | 43        | 48     | 1.14%   |
| GOODRAM             | 34        | 37     | 0.9%    |
| Netac               | 33        | 42     | 0.87%   |
| Apple               | 32        | 38     | 0.85%   |
| KingDian            | 30        | 43     | 0.79%   |
| Corsair             | 29        | 37     | 0.77%   |
| LITEON              | 21        | 27     | 0.56%   |
| LITEONIT            | 20        | 34     | 0.53%   |
| Unknown             | 17        | 19     | 0.45%   |
| XrayDisk            | 15        | 19     | 0.4%    |
| Gigabyte Technology | 15        | 17     | 0.4%    |
| Londisk             | 13        | 16     | 0.34%   |
| Kingmax             | 12        | 24     | 0.32%   |
| TO Exter            | 11        | 14     | 0.29%   |
| KingFast            | 11        | 13     | 0.29%   |
| Hewlett-Packard     | 10        | 15     | 0.26%   |
| Zheino              | 9         | 11     | 0.24%   |
| External            | 9         | 11     | 0.24%   |
| Team                | 8         | 10     | 0.21%   |
| ShiJi               | 8         | 8      | 0.21%   |
| FORESEE             | 8         | 8      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 7231      | 9856   | 52.79%  |
| SSD     | 3539      | 4877   | 25.84%  |
| NVMe    | 2147      | 2869   | 15.67%  |
| MMC     | 600       | 780    | 4.38%   |
| Unknown | 180       | 196    | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 9578      | 14555  | 75.78%  |
| NVMe | 2145      | 2864   | 16.97%  |
| MMC  | 600       | 780    | 4.75%   |
| SAS  | 317       | 379    | 2.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7938      | 11409  | 77.17%  |
| 0.51-1.0   | 2233      | 3160   | 21.71%  |
| 1.01-2.0   | 77        | 104    | 0.75%   |
| 3.01-4.0   | 28        | 41     | 0.27%   |
| 4.01-10.0  | 8         | 16     | 0.08%   |
| 2.01-3.0   | 1         | 1      | 0.01%   |
| 10.01-20.0 | 1         | 1      | 0.01%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 3761      | 29.51%  |
| 251-500        | 3330      | 26.13%  |
| 1-20           | 1427      | 11.2%   |
| 501-1000       | 1352      | 10.61%  |
| 51-100         | 1165      | 9.14%   |
| 21-50          | 899       | 7.05%   |
| 1001-2000      | 422       | 3.31%   |
| Unknown        | 273       | 2.14%   |
| 2001-3000      | 79        | 0.62%   |
| More than 3000 | 37        | 0.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 7440      | 57.09%  |
| 21-50          | 1784      | 13.69%  |
| 101-250        | 1257      | 9.64%   |
| 51-100         | 1178      | 9.04%   |
| 251-500        | 683       | 5.24%   |
| 501-1000       | 306       | 2.35%   |
| Unknown        | 273       | 2.09%   |
| 1001-2000      | 87        | 0.67%   |
| 2001-3000      | 13        | 0.1%    |
| More than 3000 | 11        | 0.08%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 138       | 190    | 4.62%   |
| Seagate ST500LT012-9WS142 500GB     | 91        | 109    | 3.04%   |
| Seagate ST9320325AS 320GB           | 89        | 113    | 2.98%   |
| HGST HTS545050A7E680 500GB          | 73        | 110    | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 70        | 84     | 2.34%   |
| Seagate ST9250315AS 250GB           | 66        | 82     | 2.21%   |
| Seagate ST500LT012-1DG142 500GB     | 66        | 81     | 2.21%   |
| Seagate ST320LT020-9YG142 320GB     | 54        | 79     | 1.81%   |
| HGST HTS545050A7E380 500GB          | 45        | 72     | 1.51%   |
| Hitachi HTS545025B9A300 250GB       | 43        | 51     | 1.44%   |
| Hitachi HTS543232A7A384 320GB       | 40        | 46     | 1.34%   |
| Seagate ST320LT012-9WS14C 320GB     | 38        | 51     | 1.27%   |
| Hitachi HTS547550A9E384 500GB       | 35        | 48     | 1.17%   |
| Hitachi HTS547575A9E384 752GB       | 34        | 47     | 1.14%   |
| Toshiba MQ01ABD050 500GB            | 30        | 37     | 1%      |
| Hitachi HTS541612J9SA00 120GB       | 29        | 39     | 0.97%   |
| Toshiba MQ01ABF050 500GB            | 28        | 39     | 0.94%   |
| Hitachi HTS541680J9SA00 80GB        | 26        | 30     | 0.87%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 25        | 29     | 0.84%   |
| Toshiba MK3265GSX 320GB             | 24        | 30     | 0.8%    |
| Seagate ST9500420AS 500GB           | 23        | 36     | 0.77%   |
| Samsung Electronics HM160HI 160GB   | 23        | 25     | 0.77%   |
| Hitachi HTS545032B9A300 320GB       | 23        | 29     | 0.77%   |
| HGST HTS541010A9E680 1TB            | 23        | 37     | 0.77%   |
| Hitachi HTS545050A7E380 500GB       | 21        | 31     | 0.7%    |
| Toshiba MQ01ABD100 1TB              | 20        | 27     | 0.67%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 19        | 25     | 0.64%   |
| Hitachi HTS545050B9A300 500GB       | 19        | 26     | 0.64%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 18        | 21     | 0.6%    |
| Hitachi HTS542512K9SA00 120GB       | 18        | 23     | 0.6%    |
| Samsung Electronics HM321HI 320GB   | 17        | 22     | 0.57%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 16        | 19     | 0.54%   |
| Hitachi HTS542516K9SA00 160GB       | 16        | 27     | 0.54%   |
| WDC WD2500BEVT-22A23T0 250GB        | 15        | 18     | 0.5%    |
| Toshiba MQ01ABD075 752GB            | 15        | 20     | 0.5%    |
| Toshiba MK3259GSXP 320GB            | 15        | 25     | 0.5%    |
| Seagate ST9160821AS 160GB           | 15        | 17     | 0.5%    |
| Samsung Electronics HM250HI 250GB   | 15        | 17     | 0.5%    |
| Hitachi HTS542525K9SA00 250GB       | 15        | 21     | 0.5%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 14        | 15     | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 902       | 1149   | 30.33%  |
| Hitachi                      | 511       | 647    | 17.18%  |
| WDC                          | 475       | 624    | 15.97%  |
| Toshiba                      | 423       | 545    | 14.22%  |
| HGST                         | 183       | 276    | 6.15%   |
| Samsung Electronics          | 121       | 142    | 4.07%   |
| Kingston                     | 46        | 56     | 1.55%   |
| SanDisk                      | 42        | 51     | 1.41%   |
| Fujitsu                      | 42        | 58     | 1.41%   |
| SK hynix                     | 24        | 32     | 0.81%   |
| Intel                        | 22        | 34     | 0.74%   |
| A-DATA Technology            | 20        | 27     | 0.67%   |
| OCZ                          | 15        | 15     | 0.5%    |
| China                        | 14        | 20     | 0.47%   |
| KingSpec                     | 13        | 15     | 0.44%   |
| SPCC                         | 10        | 11     | 0.34%   |
| Crucial                      | 10        | 13     | 0.34%   |
| Plextor                      | 9         | 11     | 0.3%    |
| LITEON                       | 9         | 10     | 0.3%    |
| Micron Technology            | 8         | 14     | 0.27%   |
| Corsair                      | 8         | 8      | 0.27%   |
| LITEONIT                     | 6         | 12     | 0.2%    |
| IBM/Hitachi                  | 5         | 5      | 0.17%   |
| AMD                          | 5         | 7      | 0.17%   |
| Transcend                    | 3         | 3      | 0.1%    |
| Smartbuy                     | 3         | 3      | 0.1%    |
| Netac                        | 3         | 4      | 0.1%    |
| Kingmax                      | 3         | 3      | 0.1%    |
| KingDian                     | 3         | 6      | 0.1%    |
| Apple                        | 3         | 3      | 0.1%    |
| Unknown                      | 3         | 4      | 0.1%    |
| Team                         | 2         | 2      | 0.07%   |
| SSSTC                        | 2         | 2      | 0.07%   |
| OCZ-VERTEX3                  | 2         | 2      | 0.07%   |
| Mushkin                      | 2         | 2      | 0.07%   |
| HGST HTS                     | 2         | 2      | 0.07%   |
| Zheino                       | 1         | 1      | 0.03%   |
| XrayDisk                     | 1         | 1      | 0.03%   |
| Unknown                      | 1         | 1      | 0.03%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 902       | 1149   | 34.45%  |
| Hitachi             | 511       | 647    | 19.52%  |
| WDC                 | 452       | 601    | 17.27%  |
| Toshiba             | 419       | 541    | 16%     |
| HGST                | 183       | 276    | 6.99%   |
| Samsung Electronics | 101       | 121    | 3.86%   |
| Fujitsu             | 42        | 58     | 1.6%    |
| IBM/Hitachi         | 5         | 5      | 0.19%   |
| HGST HTS            | 2         | 2      | 0.08%   |
| MARSHAL             | 1         | 1      | 0.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2584      | 3401   | 87.98%  |
| SSD  | 337       | 420    | 11.47%  |
| NVMe | 16        | 19     | 0.54%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-22ZCT0 160GB        | 4         | 5      | 4.26%   |
| Seagate ST9500325AS 500GB          | 4         | 4      | 4.26%   |
| Samsung Electronics HM321HI 320GB  | 4         | 5      | 4.26%   |
| HGST HTS721010A9E630 1TB           | 4         | 5      | 4.26%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 3.19%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 3.19%   |
| HGST HTS545050A7E680 500GB         | 3         | 3      | 3.19%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 2         | 2      | 2.13%   |
| WDC WD1600BEVS-22RST0 160GB        | 2         | 2      | 2.13%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 2.13%   |
| Toshiba MK6465GSX 640GB            | 2         | 2      | 2.13%   |
| Toshiba MK3259GSXP 320GB           | 2         | 2      | 2.13%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 2.13%   |
| Samsung Electronics HM160HI 160GB  | 2         | 2      | 2.13%   |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 2.13%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 3      | 2.13%   |
| Hitachi HTS543225A7A384 250GB      | 2         | 3      | 2.13%   |
| HGST HTS541010A9E680 1TB           | 2         | 2      | 2.13%   |
| WDC WD800BEVS-22RST0 80GB          | 1         | 1      | 1.06%   |
| WDC WD7500BPVT-22HXZT3 752GB       | 1         | 1      | 1.06%   |
| WDC WD7500BPVT-22HXZT1 752GB       | 1         | 1      | 1.06%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB   | 1         | 1      | 1.06%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BPVT-80HXZT1 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BPVT-24HXZT3 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BEVT-35ZAT0 500GB        | 1         | 1      | 1.06%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 1      | 1.06%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 1.06%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 1.06%   |
| WDC WD3200BEVS-0 320GB             | 1         | 1      | 1.06%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-35A23T0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-22ZCT0 250GB        | 1         | 1      | 1.06%   |
| WDC WD1600BEVT-75ZCT2 160GB        | 1         | 1      | 1.06%   |
| WDC WD1200BEVS-07LAT0 120GB        | 1         | 1      | 1.06%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 1.06%   |
| Toshiba MK8037GSX 80GB             | 1         | 1      | 1.06%   |
| Toshiba MK8025GAL 80GB             | 1         | 2      | 1.06%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 28     | 28.72%  |
| Toshiba             | 16        | 18     | 17.02%  |
| Seagate             | 16        | 18     | 17.02%  |
| Samsung Electronics | 14        | 15     | 14.89%  |
| HGST                | 11        | 13     | 11.7%   |
| Hitachi             | 8         | 10     | 8.51%   |
| Fujitsu             | 1         | 1      | 1.06%   |
| Apple               | 1         | 2      | 1.06%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 6988      | 10461  | 54.43%  |
| Malfunc  | 2898      | 3840   | 22.57%  |
| Detected | 2857      | 4171   | 22.25%  |
| Failed   | 94        | 105    | 0.73%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8358      | 65.14%  |
| AMD                              | 2126      | 16.57%  |
| Samsung Electronics              | 584       | 4.55%   |
| SanDisk                          | 332       | 2.59%   |
| SK hynix                         | 280       | 2.18%   |
| Kingston Technology Company      | 157       | 1.22%   |
| Phison Electronics               | 127       | 0.99%   |
| Nvidia                           | 120       | 0.94%   |
| KIOXIA                           | 104       | 0.81%   |
| Micron Technology                | 100       | 0.78%   |
| Toshiba America Info Systems     | 99        | 0.77%   |
| Silicon Integrated Systems [SiS] | 76        | 0.59%   |
| Union Memory (Shenzhen)          | 57        | 0.44%   |
| Silicon Motion                   | 55        | 0.43%   |
| Solid State Storage Technology   | 40        | 0.31%   |
| JMicron Technology               | 33        | 0.26%   |
| INNOGRIT                         | 28        | 0.22%   |
| ADATA Technology                 | 28        | 0.22%   |
| Realtek Semiconductor            | 26        | 0.2%    |
| Shenzhen Longsys Electronics     | 20        | 0.16%   |
| VIA Technologies                 | 12        | 0.09%   |
| Yangtze Memory Technologies      | 7         | 0.05%   |
| Micron/Crucial Technology        | 7         | 0.05%   |
| Lite-On Technology               | 7         | 0.05%   |
| Netac Technology                 | 6         | 0.05%   |
| Lenovo                           | 6         | 0.05%   |
| Apple                            | 6         | 0.05%   |
| ASMedia Technology               | 5         | 0.04%   |
| O2 Micro                         | 4         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.03%   |
| Marvell Technology Group         | 3         | 0.02%   |
| Unknown                          | 3         | 0.02%   |
| Zhaoxin                          | 2         | 0.02%   |
| Silicon Image                    | 2         | 0.02%   |
| Seagate Technology               | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |
| Transcend                        | 1         | 0.01%   |
| ShenZhen TIGO Semiconductor      | 1         | 0.01%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 1458      | 10.29%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1327      | 9.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 923       | 6.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 656       | 4.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 525       | 3.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 509       | 3.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 425       | 3%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 400       | 2.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 378       | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 318       | 2.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 317       | 2.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 305       | 2.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 253       | 1.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 251       | 1.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 235       | 1.66%   |
| Samsung NVMe SSD Controller 980                                                  | 227       | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 198       | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 175       | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 175       | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 168       | 1.19%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 167       | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 155       | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                            | 131       | 0.92%   |
| Intel Tiger Lake-LP SATA Controller                                              | 120       | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 120       | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                              | 117       | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 116       | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 115       | 0.81%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 115       | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 114       | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 112       | 0.79%   |
| AMD SB600 IDE                                                                    | 112       | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 108       | 0.76%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 98        | 0.69%   |
| Micron NVMe Storage Controller                                                   | 96        | 0.68%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 95        | 0.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 94        | 0.66%   |
| Phison PS5013 E13 NVMe Controller                                                | 94        | 0.66%   |
| Intel SSD 660P Series                                                            | 91        | 0.64%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 88        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 9391      | 69.22%  |
| NVMe | 2167      | 15.97%  |
| IDE  | 1565      | 11.54%  |
| RAID | 444       | 3.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 9098      | 77.99%  |
| AMD          | 2556      | 21.91%  |
| CentaurHauls | 5         | 0.04%   |
| ARM          | 4         | 0.03%   |
| Unknown      | 2         | 0.02%   |
| PowerBook5,6 | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 160       | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 148       | 1.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 146       | 1.25%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 143       | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 134       | 1.15%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 129       | 1.1%    |
| Intel Pentium CPU B960 @ 2.20GHz              | 123       | 1.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 123       | 1.05%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 115       | 0.98%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 111       | 0.95%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 108       | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 105       | 0.9%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 101       | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 99        | 0.85%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 99        | 0.85%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 98        | 0.84%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 98        | 0.84%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 93        | 0.79%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 90        | 0.77%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 90        | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 89        | 0.76%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 87        | 0.74%   |
| AMD E-450 APU with Radeon HD Graphics         | 86        | 0.73%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 83        | 0.71%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 78        | 0.67%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 78        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 77        | 0.66%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 77        | 0.66%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 73        | 0.62%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 71        | 0.61%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 71        | 0.61%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 69        | 0.59%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 66        | 0.56%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 66        | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 66        | 0.56%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 64        | 0.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 63        | 0.54%   |
| Intel Atom CPU N570 @ 1.66GHz                 | 62        | 0.53%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 62        | 0.53%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 61        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2228      | 19.05%  |
| Intel Core i3                  | 1511      | 12.92%  |
| Intel Core i7                  | 1129      | 9.65%   |
| Intel Celeron                  | 875       | 7.48%   |
| Intel Pentium                  | 827       | 7.07%   |
| Intel Atom                     | 707       | 6.04%   |
| Intel Core 2 Duo               | 626       | 5.35%   |
| AMD Ryzen 5                    | 452       | 3.86%   |
| Other                          | 440       | 3.76%   |
| AMD A6                         | 244       | 2.09%   |
| AMD Ryzen 7                    | 217       | 1.86%   |
| Intel Pentium Dual-Core        | 203       | 1.74%   |
| AMD A4                         | 168       | 1.44%   |
| AMD A8                         | 163       | 1.39%   |
| AMD A10                        | 154       | 1.32%   |
| AMD E                          | 149       | 1.27%   |
| AMD Ryzen 3                    | 126       | 1.08%   |
| AMD E1                         | 120       | 1.03%   |
| Intel Genuine                  | 104       | 0.89%   |
| Intel Pentium Dual             | 99        | 0.85%   |
| AMD E2                         | 98        | 0.84%   |
| Intel Core 2                   | 96        | 0.82%   |
| Intel Celeron M                | 74        | 0.63%   |
| Intel Celeron Dual-Core        | 74        | 0.63%   |
| AMD Phenom II                  | 71        | 0.61%   |
| Intel Pentium Silver           | 70        | 0.6%    |
| AMD Turion 64 X2 Mobile        | 68        | 0.58%   |
| Intel Pentium M                | 58        | 0.5%    |
| AMD Athlon                     | 41        | 0.35%   |
| AMD C-60                       | 36        | 0.31%   |
| AMD Athlon II                  | 34        | 0.29%   |
| AMD Ryzen 9                    | 29        | 0.25%   |
| AMD Athlon 64 X2               | 28        | 0.24%   |
| AMD Athlon X2                  | 27        | 0.23%   |
| AMD Turion II Dual-Core        | 25        | 0.21%   |
| AMD Turion X2 Dual-Core Mobile | 24        | 0.21%   |
| AMD C-50                       | 21        | 0.18%   |
| Intel Core Duo                 | 20        | 0.17%   |
| AMD Ryzen 7 PRO                | 20        | 0.17%   |
| AMD Athlon II Dual-Core        | 19        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 7093      | 60.43%  |
| 4       | 2888      | 24.6%   |
| 1       | 704       | 6%      |
| 6       | 426       | 3.63%   |
| Unknown | 287       | 2.45%   |
| 8       | 267       | 2.27%   |
| 3       | 25        | 0.21%   |
| 14      | 21        | 0.18%   |
| 12      | 17        | 0.14%   |
| 10      | 9         | 0.08%   |
| 192     | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 11650     | 99.82%  |
| Unknown | 15        | 0.13%   |
| 2       | 4         | 0.03%   |
| 4       | 2         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6696      | 56.94%  |
| 1       | 4776      | 40.61%  |
| Unknown | 287       | 2.44%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 11179     | 95.68%  |
| 32-bit         | 374       | 3.2%    |
| Unknown        | 129       | 1.1%    |
| 64-bit         | 2         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 1289      | 10.82%  |
| Unknown    | 1155      | 9.7%    |
| 0x306a9    | 1042      | 8.75%   |
| 0x1067a    | 476       | 4%      |
| 0x20655    | 457       | 3.84%   |
| 0x6fd      | 339       | 2.85%   |
| 0x106ca    | 309       | 2.59%   |
| 0x806ec    | 302       | 2.54%   |
| 0x40651    | 302       | 2.54%   |
| 0x806ea    | 283       | 2.38%   |
| 0x30678    | 269       | 2.26%   |
| 0x406e3    | 243       | 2.04%   |
| 0x306c3    | 240       | 2.01%   |
| 0x806c1    | 221       | 1.86%   |
| 0x806e9    | 215       | 1.8%    |
| 0x906ea    | 187       | 1.57%   |
| 0x306d4    | 178       | 1.49%   |
| 0x06001119 | 176       | 1.48%   |
| 0x406c4    | 173       | 1.45%   |
| 0x05000119 | 170       | 1.43%   |
| 0x08108109 | 166       | 1.39%   |
| 0x10676    | 159       | 1.33%   |
| 0x07030105 | 153       | 1.28%   |
| 0x20652    | 149       | 1.25%   |
| 0x06006705 | 143       | 1.2%    |
| 0x03000027 | 142       | 1.19%   |
| 0x010000c8 | 131       | 1.1%    |
| 0x30661    | 121       | 1.02%   |
| 0x08108102 | 118       | 0.99%   |
| 0x106c2    | 116       | 0.97%   |
| 0x0a50000c | 110       | 0.92%   |
| 0x406c3    | 108       | 0.91%   |
| 0x10661    | 104       | 0.87%   |
| 0x506c9    | 97        | 0.81%   |
| 0x706a1    | 93        | 0.78%   |
| 0x08600106 | 93        | 0.78%   |
| 0x706e5    | 87        | 0.73%   |
| 0x906e9    | 79        | 0.66%   |
| 0x6e8      | 79        | 0.66%   |
| 0x6f6      | 78        | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 1358      | 11.61%  |
| KabyLake         | 1357      | 11.61%  |
| IvyBridge        | 1100      | 9.41%   |
| Penryn           | 650       | 5.56%   |
| Core             | 638       | 5.46%   |
| Westmere         | 637       | 5.45%   |
| Silvermont       | 606       | 5.18%   |
| Haswell          | 601       | 5.14%   |
| Bonnell          | 528       | 4.52%   |
| Skylake          | 319       | 2.73%   |
| Zen+             | 302       | 2.58%   |
| Unknown          | 301       | 2.57%   |
| Excavator        | 276       | 2.36%   |
| TigerLake        | 271       | 2.32%   |
| Bobcat           | 254       | 2.17%   |
| Zen 2            | 218       | 1.86%   |
| Piledriver       | 206       | 1.76%   |
| Puma             | 198       | 1.69%   |
| Broadwell        | 196       | 1.68%   |
| K10              | 191       | 1.63%   |
| P6               | 182       | 1.56%   |
| Goldmont plus    | 171       | 1.46%   |
| K10 Llano        | 162       | 1.39%   |
| Zen 3            | 151       | 1.29%   |
| K8 Hammer        | 148       | 1.27%   |
| IceLake          | 127       | 1.09%   |
| Goldmont         | 116       | 0.99%   |
| Jaguar           | 96        | 0.82%   |
| CometLake        | 85        | 0.73%   |
| Zen              | 71        | 0.61%   |
| K8 & K10 hybrid  | 70        | 0.6%    |
| Alderlake Hybrid | 42        | 0.36%   |
| Nehalem          | 24        | 0.21%   |
| Tremont          | 20        | 0.17%   |
| Steamroller      | 15        | 0.13%   |
| NetBurst         | 5         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7826      | 52.07%  |
| AMD                              | 3709      | 24.68%  |
| Nvidia                           | 3449      | 22.95%  |
| Silicon Integrated Systems [SiS] | 33        | 0.22%   |
| VIA Technologies                 | 9         | 0.06%   |
| Zhaoxin                          | 2         | 0.01%   |
| ATI Technologies                 | 2         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1220      | 7.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1068      | 6.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 352       | 2.19%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 340       | 2.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 330       | 2.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 326       | 2.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 312       | 1.94%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 309       | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 308       | 1.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 298       | 1.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 252       | 1.57%   |
| Intel UHD Graphics 620                                                                   | 241       | 1.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 239       | 1.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 239       | 1.48%   |
| Intel HD Graphics 620                                                                    | 231       | 1.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 228       | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 225       | 1.4%    |
| AMD Renoir                                                                               | 216       | 1.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 214       | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 210       | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 210       | 1.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 206       | 1.28%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 206       | 1.28%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 189       | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 187       | 1.16%   |
| Intel HD Graphics 5500                                                                   | 159       | 0.99%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 154       | 0.96%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 153       | 0.95%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 141       | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 137       | 0.85%   |
| AMD Lucienne                                                                             | 136       | 0.84%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 124       | 0.77%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 122       | 0.76%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 113       | 0.7%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 111       | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 111       | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 109       | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                             | 105       | 0.65%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 105       | 0.65%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 104       | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 4638      | 39.61%  |
| Intel + Nvidia     | 2628      | 22.44%  |
| 1 x AMD            | 2368      | 20.22%  |
| 1 x Nvidia         | 654       | 5.59%   |
| 2 x AMD            | 606       | 5.18%   |
| Intel + AMD        | 572       | 4.89%   |
| AMD + Nvidia       | 170       | 1.45%   |
| 1 x SiS            | 33        | 0.28%   |
| Other              | 15        | 0.13%   |
| 2 x Intel          | 10        | 0.09%   |
| 1 x VIA            | 9         | 0.08%   |
| 2 x Nvidia         | 3         | 0.03%   |
| 1 x Zhaoxin        | 2         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 10315     | 86.53%  |
| Proprietary | 1033      | 8.67%   |
| Unknown     | 573       | 4.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4213      | 34.65%  |
| 1.01-2.0   | 3299      | 27.13%  |
| 0.01-0.5   | 2908      | 23.92%  |
| 0.51-1.0   | 932       | 7.67%   |
| 3.01-4.0   | 691       | 5.68%   |
| 5.01-6.0   | 67        | 0.55%   |
| 7.01-8.0   | 23        | 0.19%   |
| 2.01-3.0   | 21        | 0.17%   |
| 8.01-16.0  | 4         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 2461      | 20.78%  |
| LG Display              | 1835      | 15.5%   |
| Samsung Electronics     | 1584      | 13.38%  |
| BOE                     | 1391      | 11.75%  |
| Chimei Innolux          | 1387      | 11.71%  |
| Chi Mei Optoelectronics | 803       | 6.78%   |
| LG Philips              | 226       | 1.91%   |
| Lenovo                  | 199       | 1.68%   |
| HannStar                | 181       | 1.53%   |
| PANDA                   | 142       | 1.2%    |
| Goldstar                | 122       | 1.03%   |
| CPT                     | 117       | 0.99%   |
| Dell                    | 116       | 0.98%   |
| InfoVision              | 113       | 0.95%   |
| Sharp                   | 98        | 0.83%   |
| BenQ                    | 98        | 0.83%   |
| Apple                   | 95        | 0.8%    |
| Acer                    | 86        | 0.73%   |
| Philips                 | 71        | 0.6%    |
| Sony                    | 63        | 0.53%   |
| AOC                     | 60        | 0.51%   |
| Hewlett-Packard         | 51        | 0.43%   |
| Ancor Communications    | 45        | 0.38%   |
| ViewSonic               | 41        | 0.35%   |
| CSO                     | 35        | 0.3%    |
| InnoLux Display         | 31        | 0.26%   |
| Iiyama                  | 31        | 0.26%   |
| TMX                     | 29        | 0.24%   |
| Quanta Display          | 26        | 0.22%   |
| Toshiba                 | 25        | 0.21%   |
| NEC Computers           | 24        | 0.2%    |
| Valve                   | 14        | 0.12%   |
| Unknown                 | 13        | 0.11%   |
| Panasonic               | 12        | 0.1%    |
| Nvidia                  | 11        | 0.09%   |
| ASUSTek Computer        | 11        | 0.09%   |
| HKC                     | 9         | 0.08%   |
| S2-Tek                  | 8         | 0.07%   |
| Mi                      | 8         | 0.07%   |
| JDI                     | 8         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 227       | 1.91%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 200       | 1.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 171       | 1.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 154       | 1.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 154       | 1.29%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 107       | 0.9%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 102       | 0.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 100       | 0.84%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 92        | 0.77%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 92        | 0.77%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 91        | 0.76%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 84        | 0.7%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 76        | 0.64%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 74        | 0.62%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 73        | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 71        | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 71        | 0.6%    |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 71        | 0.6%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 68        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 67        | 0.56%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 64        | 0.54%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 64        | 0.54%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 60        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 59        | 0.5%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 59        | 0.5%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 55        | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 54        | 0.45%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 52        | 0.44%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 52        | 0.44%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 50        | 0.42%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 49        | 0.41%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch               | 49        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 49        | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 46        | 0.39%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 44        | 0.37%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 43        | 0.36%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 43        | 0.36%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 42        | 0.35%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 42        | 0.35%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch      | 40        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4857      | 42.12%  |
| 1920x1080 (FHD)    | 3532      | 30.63%  |
| 1600x900 (HD+)     | 774       | 6.71%   |
| 1280x800 (WXGA)    | 772       | 6.7%    |
| 1024x600           | 383       | 3.32%   |
| 1440x900 (WXGA+)   | 182       | 1.58%   |
| 3840x2160 (4K)     | 164       | 1.42%   |
| 1280x1024 (SXGA)   | 124       | 1.08%   |
| 1920x1200 (WUXGA)  | 118       | 1.02%   |
| 2560x1440 (QHD)    | 114       | 0.99%   |
| 1680x1050 (WSXGA+) | 84        | 0.73%   |
| 2560x1600          | 56        | 0.49%   |
| 2160x1440          | 53        | 0.46%   |
| 1024x768 (XGA)     | 35        | 0.3%    |
| 2880x1800          | 29        | 0.25%   |
| 1360x768           | 19        | 0.16%   |
| 1280x720 (HD)      | 19        | 0.16%   |
| 800x1280           | 18        | 0.16%   |
| 2288x1287          | 18        | 0.16%   |
| 3200x2000          | 17        | 0.15%   |
| 3440x1440          | 16        | 0.14%   |
| 2560x1080          | 16        | 0.14%   |
| 1680x945           | 14        | 0.12%   |
| 3000x2000          | 11        | 0.1%    |
| 2520x1680          | 11        | 0.1%    |
| 1400x1050          | 10        | 0.09%   |
| 3840x2400          | 7         | 0.06%   |
| 3200x1800 (QHD+)   | 7         | 0.06%   |
| 1920x540           | 7         | 0.06%   |
| 1600x1200          | 7         | 0.06%   |
| Unknown            | 6         | 0.05%   |
| 3456x2160          | 5         | 0.04%   |
| 2240x1400          | 5         | 0.04%   |
| 1024x576           | 5         | 0.04%   |
| 2880x1620          | 4         | 0.03%   |
| 2256x1504          | 4         | 0.03%   |
| 3120x2080          | 3         | 0.03%   |
| 2736x1824          | 3         | 0.03%   |
| 3840x1080          | 2         | 0.02%   |
| 1920x515           | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 6687      | 56.51%  |
| 17      | 1056      | 8.92%   |
| 13      | 984       | 8.32%   |
| 14      | 932       | 7.88%   |
| 10      | 390       | 3.3%    |
| 11      | 246       | 2.08%   |
| 12      | 209       | 1.77%   |
| 24      | 201       | 1.7%    |
| 23      | 174       | 1.47%   |
| 21      | 148       | 1.25%   |
| 27      | 138       | 1.17%   |
| 16      | 109       | 0.92%   |
| 19      | 92        | 0.78%   |
| 18      | 82        | 0.69%   |
| Unknown | 57        | 0.48%   |
| 31      | 35        | 0.3%    |
| 20      | 34        | 0.29%   |
| 34      | 31        | 0.26%   |
| 22      | 31        | 0.26%   |
| 8       | 23        | 0.19%   |
| 40      | 19        | 0.16%   |
| 32      | 18        | 0.15%   |
| 52      | 16        | 0.14%   |
| 54      | 14        | 0.12%   |
| 7       | 14        | 0.12%   |
| 26      | 13        | 0.11%   |
| 72      | 11        | 0.09%   |
| 42      | 9         | 0.08%   |
| 142     | 8         | 0.07%   |
| 84      | 8         | 0.07%   |
| 25      | 7         | 0.06%   |
| 48      | 4         | 0.03%   |
| 46      | 4         | 0.03%   |
| 28      | 4         | 0.03%   |
| 50      | 3         | 0.03%   |
| 36      | 3         | 0.03%   |
| 9       | 3         | 0.03%   |
| 65      | 2         | 0.02%   |
| 37      | 2         | 0.02%   |
| 35      | 2         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 7978      | 67.78%  |
| 201-300        | 1388      | 11.79%  |
| 351-400        | 1270      | 10.79%  |
| 501-600        | 508       | 4.32%   |
| 401-500        | 321       | 2.73%   |
| Unknown        | 57        | 0.48%   |
| 701-800        | 53        | 0.45%   |
| 601-700        | 48        | 0.41%   |
| 1001-1500      | 46        | 0.39%   |
| 101-200        | 23        | 0.2%    |
| 801-900        | 22        | 0.19%   |
| 1501-2000      | 21        | 0.18%   |
| 1-100          | 14        | 0.12%   |
| 901-1000       | 12        | 0.1%    |
| More than 2000 | 9         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 9483      | 85.04%  |
| 16/10   | 1282      | 11.5%   |
| 5/4     | 108       | 0.97%   |
| 3/2     | 108       | 0.97%   |
| 4/3     | 76        | 0.68%   |
| 21/9    | 36        | 0.32%   |
| Unknown | 24        | 0.22%   |
| 0.67    | 14        | 0.13%   |
| 1.00    | 8         | 0.07%   |
| 6/5     | 5         | 0.04%   |
| 0.62    | 4         | 0.04%   |
| 3.73    | 2         | 0.02%   |
| 1.96    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 6692      | 56.55%  |
| 81-90          | 1470      | 12.42%  |
| 121-130        | 820       | 6.93%   |
| 201-250        | 469       | 3.96%   |
| 71-80          | 435       | 3.68%   |
| 41-50          | 393       | 3.32%   |
| 51-60          | 246       | 2.08%   |
| 131-140        | 192       | 1.62%   |
| 61-70          | 190       | 1.61%   |
| 151-200        | 166       | 1.4%    |
| 301-350        | 147       | 1.24%   |
| 141-150        | 119       | 1.01%   |
| 351-500        | 92        | 0.78%   |
| 91-100         | 90        | 0.76%   |
| More than 1000 | 71        | 0.6%    |
| 251-300        | 58        | 0.49%   |
| Unknown        | 57        | 0.48%   |
| 111-120        | 50        | 0.42%   |
| 501-1000       | 39        | 0.33%   |
| 1-40           | 37        | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 5284      | 45.24%  |
| 121-160       | 3538      | 30.29%  |
| 51-100        | 2166      | 18.54%  |
| 161-240       | 429       | 3.67%   |
| More than 240 | 129       | 1.1%    |
| 1-50          | 78        | 0.67%   |
| Unknown       | 57        | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 10499     | 88.46%  |
| 2     | 966       | 8.14%   |
| 0     | 358       | 3.02%   |
| 3     | 46        | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 6817      | 34.77%  |
| Qualcomm Atheros                       | 4726      | 24.1%   |
| Intel                                  | 3497      | 17.84%  |
| Broadcom                               | 1822      | 9.29%   |
| Marvell Technology Group               | 470       | 2.4%    |
| Broadcom Limited                       | 437       | 2.23%   |
| Ralink                                 | 342       | 1.74%   |
| Huawei Technologies                    | 211       | 1.08%   |
| MediaTek                               | 193       | 0.98%   |
| JMicron Technology                     | 115       | 0.59%   |
| Attansic Technology                    | 108       | 0.55%   |
| TP-Link                                | 83        | 0.42%   |
| Xiaomi                                 | 77        | 0.39%   |
| Ralink Technology                      | 76        | 0.39%   |
| Nvidia                                 | 65        | 0.33%   |
| Silicon Integrated Systems [SiS]       | 49        | 0.25%   |
| Samsung Electronics                    | 45        | 0.23%   |
| Qualcomm                               | 38        | 0.19%   |
| ZTE WCDMA Technologies MSM             | 34        | 0.17%   |
| D-Link                                 | 32        | 0.16%   |
| ASUSTek Computer                       | 28        | 0.14%   |
| ASIX Electronics                       | 28        | 0.14%   |
| Ericsson Business Mobile Networks      | 24        | 0.12%   |
| Qualcomm Atheros Communications        | 23        | 0.12%   |
| Hewlett-Packard                        | 22        | 0.11%   |
| Sierra Wireless                        | 21        | 0.11%   |
| Gemtek                                 | 20        | 0.1%    |
| Lenovo                                 | 17        | 0.09%   |
| Dell                                   | 17        | 0.09%   |
| Vimtron Electronics                    | 14        | 0.07%   |
| Fibocom                                | 12        | 0.06%   |
| VIA Technologies                       | 8         | 0.04%   |
| HTC (High Tech Computer)               | 7         | 0.04%   |
| HMD Global                             | 7         | 0.04%   |
| D-Link System                          | 7         | 0.04%   |
| T & A Mobile Phones                    | 6         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 6         | 0.03%   |
| ICS Advent                             | 6         | 0.03%   |
| Apple                                  | 6         | 0.03%   |
| NTmore                                 | 5         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 4085      | 18.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1628      | 7.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1378      | 6.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 761       | 3.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 613       | 2.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 567       | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 487       | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 403       | 1.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 341       | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 334       | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 322       | 1.42%   |
| Broadcom BCM43142 802.11b/g/n                                           | 302       | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 269       | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 264       | 1.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 236       | 1.04%   |
| Intel Wi-Fi 6 AX201                                                     | 216       | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 209       | 0.92%   |
| Intel Wireless 8265 / 8275                                              | 208       | 0.92%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 192       | 0.85%   |
| Intel Wireless 7265                                                     | 189       | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 188       | 0.83%   |
| Intel Wi-Fi 6 AX200                                                     | 188       | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 184       | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 177       | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 159       | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 154       | 0.68%   |
| Intel WiFi Link 5100                                                    | 150       | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 141       | 0.62%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 141       | 0.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 137       | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 135       | 0.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 133       | 0.59%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 132       | 0.58%   |
| Intel Wireless 3165                                                     | 132       | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 128       | 0.57%   |
| Intel Wireless 7260                                                     | 125       | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 123       | 0.54%   |
| Intel Centrino Wireless-N 130                                           | 123       | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 121       | 0.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 119       | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 4076      | 34.59%  |
| Intel                           | 3371      | 28.61%  |
| Realtek Semiconductor           | 2016      | 17.11%  |
| Broadcom                        | 1304      | 11.07%  |
| Ralink                          | 342       | 2.9%    |
| Broadcom Limited                | 233       | 1.98%   |
| MediaTek                        | 155       | 1.32%   |
| Ralink Technology               | 76        | 0.64%   |
| TP-Link                         | 54        | 0.46%   |
| ASUSTek Computer                | 26        | 0.22%   |
| Qualcomm Atheros Communications | 23        | 0.2%    |
| Sierra Wireless                 | 20        | 0.17%   |
| Qualcomm                        | 16        | 0.14%   |
| D-Link                          | 16        | 0.14%   |
| Fibocom                         | 12        | 0.1%    |
| Dell                            | 9         | 0.08%   |
| D-Link System                   | 7         | 0.06%   |
| Tenda                           | 3         | 0.03%   |
| Micro Star International        | 3         | 0.03%   |
| Mercucys                        | 3         | 0.03%   |
| Hewlett-Packard                 | 3         | 0.03%   |
| Edimax Technology               | 3         | 0.03%   |
| Xiaomi                          | 2         | 0.02%   |
| Fujitsu Siemens Computers       | 2         | 0.02%   |
| ZyXEL Communications            | 1         | 0.01%   |
| Wacom                           | 1         | 0.01%   |
| Quectel Wireless Solutions      | 1         | 0.01%   |
| Qcom                            | 1         | 0.01%   |
| NetGear                         | 1         | 0.01%   |
| Microsoft                       | 1         | 0.01%   |
| Linksys                         | 1         | 0.01%   |
| ASUSTek Computer (wrong ID)     | 1         | 0.01%   |
| Askey Computer                  | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1378      | 11.6%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 761       | 6.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 613       | 5.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 567       | 4.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 487       | 4.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 403       | 3.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 341       | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 334       | 2.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 322       | 2.71%   |
| Broadcom BCM43142 802.11b/g/n                                           | 302       | 2.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 269       | 2.27%   |
| Intel Wi-Fi 6 AX201                                                     | 216       | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 209       | 1.76%   |
| Intel Wireless 8265 / 8275                                              | 208       | 1.75%   |
| Intel Wireless 7265                                                     | 189       | 1.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 188       | 1.58%   |
| Intel Wi-Fi 6 AX200                                                     | 188       | 1.58%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 184       | 1.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 177       | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 154       | 1.3%    |
| Intel WiFi Link 5100                                                    | 150       | 1.26%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 141       | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 133       | 1.12%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 132       | 1.11%   |
| Intel Wireless 3165                                                     | 132       | 1.11%   |
| Intel Wireless 7260                                                     | 125       | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 123       | 1.04%   |
| Intel Centrino Wireless-N 130                                           | 123       | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 104       | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 104       | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 100       | 0.84%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 97        | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 95        | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 88        | 0.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 88        | 0.74%   |
| Intel Centrino Wireless-N 2230                                          | 83        | 0.7%    |
| Intel WiMAX/WiFi Link 5150                                              | 81        | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 79        | 0.67%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 77        | 0.65%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 76        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 6027      | 57.72%  |
| Qualcomm Atheros                       | 1389      | 13.3%   |
| Intel                                  | 828       | 7.93%   |
| Broadcom                               | 687       | 6.58%   |
| Marvell Technology Group               | 470       | 4.5%    |
| Broadcom Limited                       | 214       | 2.05%   |
| JMicron Technology                     | 115       | 1.1%    |
| Attansic Technology                    | 108       | 1.03%   |
| Xiaomi                                 | 75        | 0.72%   |
| Huawei Technologies                    | 65        | 0.62%   |
| Nvidia                                 | 64        | 0.61%   |
| Silicon Integrated Systems [SiS]       | 48        | 0.46%   |
| Samsung Electronics                    | 39        | 0.37%   |
| MediaTek                               | 36        | 0.34%   |
| ZTE WCDMA Technologies MSM             | 34        | 0.33%   |
| TP-Link                                | 29        | 0.28%   |
| ASIX Electronics                       | 28        | 0.27%   |
| Qualcomm                               | 22        | 0.21%   |
| Gemtek                                 | 20        | 0.19%   |
| Lenovo                                 | 17        | 0.16%   |
| D-Link                                 | 16        | 0.15%   |
| Vimtron Electronics                    | 14        | 0.13%   |
| VIA Technologies                       | 8         | 0.08%   |
| HTC (High Tech Computer)               | 7         | 0.07%   |
| HMD Global                             | 7         | 0.07%   |
| Hewlett-Packard                        | 7         | 0.07%   |
| ICS Advent                             | 6         | 0.06%   |
| Apple                                  | 6         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.05%   |
| NTmore                                 | 5         | 0.05%   |
| T & A Mobile Phones                    | 4         | 0.04%   |
| OPPO Electronics                       | 4         | 0.04%   |
| GCT Semiconductor                      | 4         | 0.04%   |
| DisplayLink                            | 4         | 0.04%   |
| LG Electronics                         | 3         | 0.03%   |
| ASUSTek Computer                       | 3         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.02%   |
| Motorola PCS                           | 2         | 0.02%   |
| LeEco                                  | 2         | 0.02%   |
| Google                                 | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 4085      | 38.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1628      | 15.53%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 264       | 2.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 236       | 2.25%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 192       | 1.83%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 159       | 1.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 141       | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 137       | 1.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 135       | 1.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 128       | 1.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 121       | 1.15%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 119       | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 110       | 1.05%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 108       | 1.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 104       | 0.99%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 95        | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 94        | 0.9%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 80        | 0.76%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 79        | 0.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 78        | 0.74%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 69        | 0.66%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 62        | 0.59%   |
| Intel Ethernet Connection (6) I219-V                                           | 61        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 59        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 59        | 0.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 58        | 0.55%   |
| Intel Ethernet Connection (13) I219-V                                          | 55        | 0.52%   |
| Intel WiMAX Connection 2400m                                                   | 53        | 0.51%   |
| Intel 82577LM Gigabit Network Connection                                       | 53        | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 52        | 0.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 48        | 0.46%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 47        | 0.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 46        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 45        | 0.43%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 43        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 39        | 0.37%   |
| Intel Ethernet Connection (4) I219-V                                           | 38        | 0.36%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 37        | 0.35%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 36        | 0.34%   |
| Intel Ethernet Connection (10) I219-V                                          | 35        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 11445     | 52.57%  |
| Ethernet | 10046     | 46.15%  |
| Modem    | 268       | 1.23%   |
| Unknown  | 10        | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 9355      | 77.59%  |
| Ethernet | 2698      | 22.38%  |
| Modem    | 4         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 9599      | 82.16%  |
| 1     | 1829      | 15.65%  |
| 0     | 236       | 2.02%   |
| 3     | 20        | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 11483     | 98.01%  |
| Yes  | 233       | 1.99%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2257      | 26.95%  |
| Qualcomm Atheros Communications | 1177      | 14.06%  |
| Realtek Semiconductor           | 1062      | 12.68%  |
| IMC Networks                    | 686       | 8.19%   |
| Broadcom                        | 618       | 7.38%   |
| Lite-On Technology              | 611       | 7.3%    |
| Foxconn / Hon Hai               | 526       | 6.28%   |
| Ralink                          | 188       | 2.25%   |
| ASUSTek Computer                | 183       | 2.19%   |
| Foxconn International           | 149       | 1.78%   |
| Toshiba                         | 148       | 1.77%   |
| Realtek                         | 134       | 1.6%    |
| Hewlett-Packard                 | 120       | 1.43%   |
| Cambridge Silicon Radio         | 118       | 1.41%   |
| Dell                            | 109       | 1.3%    |
| Apple                           | 82        | 0.98%   |
| Alps Electric                   | 65        | 0.78%   |
| Ralink Technology               | 37        | 0.44%   |
| MediaTek                        | 23        | 0.27%   |
| Chicony Electronics             | 23        | 0.27%   |
| Opticis                         | 19        | 0.23%   |
| Micro Star International        | 10        | 0.12%   |
| Askey Computer                  | 7         | 0.08%   |
| USI                             | 5         | 0.06%   |
| Taiyo Yuden                     | 5         | 0.06%   |
| Integrated System Solution      | 3         | 0.04%   |
| TP-Link                         | 2         | 0.02%   |
| Samsung Electronics             | 2         | 0.02%   |
| Qcom                            | 2         | 0.02%   |
| Syntek                          | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| Unknown                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 751       | 8.96%   |
| Realtek Bluetooth Radio                                                             | 574       | 6.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 457       | 5.45%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 397       | 4.74%   |
| Intel AX201 Bluetooth                                                               | 381       | 4.55%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 356       | 4.25%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 266       | 3.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 249       | 2.97%   |
| IMC Networks Bluetooth Radio                                                        | 209       | 2.49%   |
| Ralink RT3290 Bluetooth                                                             | 188       | 2.24%   |
| Intel AX200 Bluetooth                                                               | 188       | 2.24%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 176       | 2.1%    |
| IMC Networks Bluetooth Device                                                       | 166       | 1.98%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 159       | 1.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 153       | 1.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 149       | 1.78%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 147       | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 144       | 1.72%   |
| Lite-On Bluetooth Device                                                            | 143       | 1.71%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 130       | 1.55%   |
| Realtek 802.11ac WLAN Adapter                                                       | 128       | 1.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 118       | 1.41%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 107       | 1.28%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 104       | 1.24%   |
| Realtek RTL8723B Bluetooth                                                          | 102       | 1.22%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 101       | 1.21%   |
| Broadcom BCM2045 Bluetooth                                                          | 80        | 0.95%   |
| Qualcomm Atheros Bluetooth                                                          | 72        | 0.86%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 68        | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 63        | 0.75%   |
| Broadcom HP Portable Valentine                                                      | 62        | 0.74%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 62        | 0.74%   |
| Toshiba Integrated Bluetooth HCI                                                    | 57        | 0.68%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 57        | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 57        | 0.68%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 54        | 0.64%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 54        | 0.64%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 52        | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 51        | 0.61%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 51        | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 8724      | 65.57%  |
| AMD                                          | 3033      | 22.8%   |
| Nvidia                                       | 1120      | 8.42%   |
| C-Media Electronics                          | 78        | 0.59%   |
| Silicon Integrated Systems [SiS]             | 76        | 0.57%   |
| Logitech                                     | 23        | 0.17%   |
| Creative Technology                          | 21        | 0.16%   |
| Realtek Semiconductor                        | 16        | 0.12%   |
| JMTek                                        | 14        | 0.11%   |
| VIA Technologies                             | 12        | 0.09%   |
| Lenovo                                       | 12        | 0.09%   |
| Texas Instruments                            | 11        | 0.08%   |
| Plantronics                                  | 10        | 0.08%   |
| Generalplus Technology                       | 10        | 0.08%   |
| GN Netcom                                    | 9         | 0.07%   |
| Promethean Limited                           | 7         | 0.05%   |
| ASUSTek Computer                             | 7         | 0.05%   |
| Samson Technologies                          | 6         | 0.05%   |
| Focusrite-Novation                           | 6         | 0.05%   |
| Yamaha                                       | 5         | 0.04%   |
| SteelSeries ApS                              | 5         | 0.04%   |
| Sennheiser Communications                    | 5         | 0.04%   |
| A4Tech                                       | 5         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 4         | 0.03%   |
| Razer USA                                    | 4         | 0.03%   |
| Hewlett-Packard                              | 4         | 0.03%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.02%   |
| GYROCOM C&C                                  | 3         | 0.02%   |
| Zhaoxin                                      | 2         | 0.02%   |
| XMOS                                         | 2         | 0.02%   |
| TTGK Technology                              | 2         | 0.02%   |
| SAVITECH                                     | 2         | 0.02%   |
| Samsung Electronics                          | 2         | 0.02%   |
| Roland                                       | 2         | 0.02%   |
| Nordic Semiconductor ASA                     | 2         | 0.02%   |
| Microsoft                                    | 2         | 0.02%   |
| M-Audio                                      | 2         | 0.02%   |
| Kingston Technology                          | 2         | 0.02%   |
| Harman                                       | 2         | 0.02%   |
| Google                                       | 2         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1459      | 8.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 993       | 6.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 840       | 5.15%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 807       | 4.95%   |
| AMD FCH Azalia Controller                                                                         | 744       | 4.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 718       | 4.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 659       | 4.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 586       | 3.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 586       | 3.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 437       | 2.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 425       | 2.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 356       | 2.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 347       | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 331       | 2.03%   |
| Intel 8 Series HD Audio Controller                                                                | 331       | 2.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 278       | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 274       | 1.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 272       | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 271       | 1.66%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 264       | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 256       | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 247       | 1.52%   |
| AMD High Definition Audio Controller                                                              | 225       | 1.38%   |
| AMD Wrestler HDMI Audio                                                                           | 219       | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 215       | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 213       | 1.31%   |
| AMD Trinity HDMI Audio Controller                                                                 | 208       | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 204       | 1.25%   |
| Intel Broadwell-U Audio Controller                                                                | 196       | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 193       | 1.18%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 170       | 1.04%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 167       | 1.02%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 162       | 0.99%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 138       | 0.85%   |
| Nvidia High Definition Audio Controller                                                           | 134       | 0.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 120       | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 116       | 0.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 97        | 0.6%    |
| Intel CM238 HD Audio Controller                                                                   | 95        | 0.58%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 91        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung Electronics                | 2730      | 23.17%  |
| SK hynix                           | 2254      | 19.13%  |
| Unknown                            | 1495      | 12.69%  |
| Kingston                           | 1324      | 11.24%  |
| Micron Technology                  | 982       | 8.34%   |
| Elpida                             | 458       | 3.89%   |
| Nanya Technology                   | 377       | 3.2%    |
| Ramaxel Technology                 | 349       | 2.96%   |
| Crucial                            | 314       | 2.67%   |
| A-DATA Technology                  | 314       | 2.67%   |
| AMD                                | 140       | 1.19%   |
| ASint Technology                   | 121       | 1.03%   |
| Patriot                            | 92        | 0.78%   |
| Corsair                            | 92        | 0.78%   |
| Unknown (ABCD)                     | 89        | 0.76%   |
| Goldkey                            | 76        | 0.65%   |
| 48spaces                           | 76        | 0.65%   |
| SHARETRONIC                        | 53        | 0.45%   |
| Foxline                            | 44        | 0.37%   |
| Transcend                          | 35        | 0.3%    |
| Goodram                            | 32        | 0.27%   |
| Apacer                             | 32        | 0.27%   |
| Qimonda                            | 28        | 0.24%   |
| ACPI Digital                       | 28        | 0.24%   |
| Unknown                            | 26        | 0.22%   |
| Kllisre                            | 24        | 0.2%    |
| Unifosa                            | 23        | 0.2%    |
| Qumo                               | 17        | 0.14%   |
| Toshiba                            | 16        | 0.14%   |
| Silicon Power                      | 13        | 0.11%   |
| ChangXin Memory                    | 9         | 0.08%   |
| Kingmax                            | 8         | 0.07%   |
| Kingmax Semiconductor              | 7         | 0.06%   |
| Unknown (8AD6)                     | 3         | 0.03%   |
| Unknown (08AE)                     | 3         | 0.03%   |
| SGS/Thomson                        | 3         | 0.03%   |
| MLLSE                              | 3         | 0.03%   |
| KingTiger                          | 3         | 0.03%   |
| Kimtigo Semiconductor (HK) Limited | 3         | 0.03%   |
| Kembona                            | 3         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 221       | 1.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 150       | 1.18%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 144       | 1.13%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 134       | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 133       | 1.04%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 132       | 1.03%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 123       | 0.96%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 121       | 0.95%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 121       | 0.95%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 109       | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 108       | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 103       | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 96        | 0.75%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 94        | 0.74%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 92        | 0.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 90        | 0.71%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 89        | 0.7%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                     | 89        | 0.7%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 80        | 0.63%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s          | 78        | 0.61%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                         | 77        | 0.6%    |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 75        | 0.59%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                     | 71        | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 70        | 0.55%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                     | 65        | 0.51%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 64        | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 63        | 0.49%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                    | 61        | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                             | 59        | 0.46%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 59        | 0.46%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 57        | 0.45%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 56        | 0.44%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 55        | 0.43%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 54        | 0.42%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 54        | 0.42%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 53        | 0.42%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s                   | 52        | 0.41%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s                     | 51        | 0.4%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 50        | 0.39%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s                      | 50        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 5134      | 52%     |
| DDR4    | 2414      | 24.45%  |
| DDR2    | 1093      | 11.07%  |
| SDRAM   | 508       | 5.15%   |
| LPDDR4  | 253       | 2.56%   |
| Unknown | 132       | 1.34%   |
| DDR     | 131       | 1.33%   |
| DRAM    | 98        | 0.99%   |
| LPDDR3  | 83        | 0.84%   |
| LPDDR5  | 15        | 0.15%   |
| DDR5    | 11        | 0.11%   |
| SRAM    | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 9151      | 94.59%  |
| Row Of Chips | 400       | 4.13%   |
| DIMM         | 92        | 0.95%   |
| Chip         | 23        | 0.24%   |
| Unknown      | 8         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 4352      | 38.47%  |
| 2048    | 3124      | 27.62%  |
| 8192    | 2220      | 19.63%  |
| 1024    | 1022      | 9.03%   |
| 16384   | 393       | 3.47%   |
| 512     | 137       | 1.21%   |
| 32768   | 41        | 0.36%   |
| 256     | 15        | 0.13%   |
| Unknown | 5         | 0.04%   |
| 1536    | 3         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 3101      | 28.23%  |
| 1334    | 1305      | 11.88%  |
| 2667    | 1189      | 10.82%  |
| 3200    | 846       | 7.7%    |
| 1333    | 813       | 7.4%    |
| 667     | 672       | 6.12%   |
| Unknown | 635       | 5.78%   |
| 2400    | 543       | 4.94%   |
| 4199    | 278       | 2.53%   |
| 800     | 255       | 2.32%   |
| 1067    | 249       | 2.27%   |
| 2133    | 233       | 2.12%   |
| 533     | 153       | 1.39%   |
| 3266    | 133       | 1.21%   |
| 2048    | 104       | 0.95%   |
| 1066    | 99        | 0.9%    |
| 975     | 61        | 0.56%   |
| 1867    | 59        | 0.54%   |
| 333     | 46        | 0.42%   |
| 4267    | 31        | 0.28%   |
| 400     | 26        | 0.24%   |
| 1639    | 20        | 0.18%   |
| 3733    | 19        | 0.17%   |
| 4266    | 18        | 0.16%   |
| 1866    | 18        | 0.16%   |
| 8400    | 16        | 0.15%   |
| 6400    | 15        | 0.14%   |
| 4800    | 13        | 0.12%   |
| 2933    | 9         | 0.08%   |
| 65535   | 3         | 0.03%   |
| 2666    | 3         | 0.03%   |
| 1776    | 3         | 0.03%   |
| 266     | 3         | 0.03%   |
| 200     | 3         | 0.03%   |
| 100     | 3         | 0.03%   |
| 1       | 3         | 0.03%   |
| 2800    | 2         | 0.02%   |
| 2267    | 2         | 0.02%   |
| 1596    | 1         | 0.01%   |
| 166     | 1         | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 60        | 26.55%  |
| Canon                  | 45        | 19.91%  |
| Samsung Electronics    | 37        | 16.37%  |
| Seiko Epson            | 21        | 9.29%   |
| Brother Industries     | 16        | 7.08%   |
| Xerox                  | 13        | 5.75%   |
| Panasonic (Matsushita) | 12        | 5.31%   |
| Ricoh                  | 8         | 3.54%   |
| Pantum                 | 6         | 2.65%   |
| Kyocera                | 3         | 1.33%   |
| Xiaomi                 | 2         | 0.88%   |
| Prolific Technology    | 1         | 0.44%   |
| NXP Semiconductors     | 1         | 0.44%   |
| Lexmark International  | 1         | 0.44%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                             | 9         | 3.96%   |
| Samsung SCX-4200 series                                      | 6         | 2.64%   |
| Samsung SCX-3400 Series                                      | 6         | 2.64%   |
| Panasonic (Matsushita) KX-MB1500RU                           | 6         | 2.64%   |
| Samsung SCX-3200 Series                                      | 5         | 2.2%    |
| Panasonic (Matsushita) KX-MB2030 Multifunction Laser Printer | 5         | 2.2%    |
| HP LaserJet P1102                                            | 5         | 2.2%    |
| Xerox B205                                                   | 4         | 1.76%   |
| Samsung ML-1210 Printer                                      | 4         | 1.76%   |
| Samsung M2020 Series                                         | 4         | 1.76%   |
| HP LaserJet 1200                                             | 4         | 1.76%   |
| Canon PIXMA MG2500 Series                                    | 4         | 1.76%   |
| Brother HL-1110 series                                       | 4         | 1.76%   |
| Seiko Epson L210 Series                                      | 3         | 1.32%   |
| Seiko Epson L200 Series                                      | 3         | 1.32%   |
| HP LaserJet 1018                                             | 3         | 1.32%   |
| Canon MF4010 series                                          | 3         | 1.32%   |
| Canon LBP7010C/7018C                                         | 3         | 1.32%   |
| Canon LBP6020                                                | 3         | 1.32%   |
| Canon LBP3010/LBP3018/LBP3050                                | 3         | 1.32%   |
| Canon LaserShot LBP-1120 Printer                             | 3         | 1.32%   |
| Canon G1000 series                                           | 3         | 1.32%   |
| Xiaomi MiMouse 2                                             | 2         | 0.88%   |
| Xerox Phaser 3020                                            | 2         | 0.88%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                        | 2         | 0.88%   |
| Seiko Epson Printer                                          | 2         | 0.88%   |
| Seiko Epson L132 Series                                      | 2         | 0.88%   |
| Seiko Epson L120 Series                                      | 2         | 0.88%   |
| Samsung ML-1865                                              | 2         | 0.88%   |
| Samsung ML-1640 Series Laser Printer                         | 2         | 0.88%   |
| Samsung M2070 Series                                         | 2         | 0.88%   |
| Ricoh SP 150SUw                                              | 2         | 0.88%   |
| Pantum P2200 series                                          | 2         | 0.88%   |
| Pantum M6500 series                                          | 2         | 0.88%   |
| Kyocera FS-1120MFP                                           | 2         | 0.88%   |
| HP LaserJet Professional P1102w                              | 2         | 0.88%   |
| HP LaserJet 1320                                             | 2         | 0.88%   |
| HP LaserJet 1022                                             | 2         | 0.88%   |
| HP DeskJet 5440                                              | 2         | 0.88%   |
| HP DeskJet 4530 series                                       | 2         | 0.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Seiko Epson                 | 14        | 33.33%  |
| Canon                       | 10        | 23.81%  |
| Hewlett-Packard             | 8         | 19.05%  |
| Mustek Systems              | 4         | 9.52%   |
| Ultima Electronics          | 2         | 4.76%   |
| KYE Systems (Mouse Systems) | 2         | 4.76%   |
| Acer Peripherals (now BenQ) | 2         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 5         | 11.9%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 4.76%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 2         | 4.76%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2         | 4.76%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 4.76%   |
| HP ScanJet 3770                                                                       | 2         | 4.76%   |
| HP ScanJet 2400c                                                                      | 2         | 4.76%   |
| HP Scanjet 200                                                                        | 2         | 4.76%   |
| Canon CanoScan LIDE 25                                                                | 2         | 4.76%   |
| Canon CanoScan LiDE 120                                                               | 2         | 4.76%   |
| Canon CanoScan LiDE 110                                                               | 2         | 4.76%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 2.38%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.38%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 2.38%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 1         | 2.38%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 1         | 2.38%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 1         | 2.38%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 1         | 2.38%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4                                          | 1         | 2.38%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE                                   | 1         | 2.38%   |
| HP ScanJet G4010                                                                      | 1         | 2.38%   |
| HP Scanjet 300                                                                        | 1         | 2.38%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 2.38%   |
| Canon CanoScan LiDE 70                                                                | 1         | 2.38%   |
| Canon CanoScan LiDE 220                                                               | 1         | 2.38%   |
| Canon CanoScan 4400F                                                                  | 1         | 2.38%   |
| Acer Peripherals (now BenQ) Benq 5150/5250                                            | 1         | 2.38%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 1         | 2.38%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2628      | 25.65%  |
| IMC Networks                           | 1249      | 12.19%  |
| Realtek Semiconductor                  | 707       | 6.9%    |
| Suyin                                  | 634       | 6.19%   |
| Acer                                   | 610       | 5.95%   |
| Microdia                               | 532       | 5.19%   |
| Sunplus Innovation Technology          | 476       | 4.65%   |
| Quanta                                 | 415       | 4.05%   |
| Silicon Motion                         | 402       | 3.92%   |
| Bison Electronics                      | 375       | 3.66%   |
| Cheng Uei Precision Industry (Foxlink) | 374       | 3.65%   |
| Syntek                                 | 315       | 3.07%   |
| Alcor Micro                            | 287       | 2.8%    |
| Z-Star Microelectronics                | 157       | 1.53%   |
| Lite-On Technology                     | 119       | 1.16%   |
| Ricoh                                  | 117       | 1.14%   |
| ALi                                    | 104       | 1.02%   |
| Apple                                  | 98        | 0.96%   |
| Luxvisions Innotech Limited            | 96        | 0.94%   |
| DigiTech                               | 82        | 0.8%    |
| Logitech                               | 60        | 0.59%   |
| Lenovo                                 | 40        | 0.39%   |
| Samsung Electronics                    | 35        | 0.34%   |
| Sonix Technology                       | 33        | 0.32%   |
| Primax Electronics                     | 32        | 0.31%   |
| icSpring                               | 24        | 0.23%   |
| SunplusIT                              | 23        | 0.22%   |
| Importek                               | 21        | 0.2%    |
| Y Media                                | 19        | 0.19%   |
| Sunplus Technology                     | 17        | 0.17%   |
| Unknown                                | 16        | 0.16%   |
| OmniVision Technologies                | 14        | 0.14%   |
| GEMBIRD                                | 13        | 0.13%   |
| USB Camera CS                          | 9         | 0.09%   |
| Image Processor                        | 9         | 0.09%   |
| Genesys Logic                          | 8         | 0.08%   |
| Pixart Imaging                         | 7         | 0.07%   |
| Nebraska Furniture Mart                | 6         | 0.06%   |
| Microsoft                              | 5         | 0.05%   |
| KYE Systems (Mouse Systems)            | 5         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                | 288       | 2.81%   |
| Chicony Integrated Camera                        | 252       | 2.46%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 243       | 2.37%   |
| Chicony Lenovo EasyCamera                        | 220       | 2.14%   |
| IMC Networks USB2.0 HD UVC WebCam                | 179       | 1.74%   |
| Sunplus HD Webcam                                | 155       | 1.51%   |
| Acer Lenovo Integrated Webcam                    | 153       | 1.49%   |
| Microdia Integrated_Webcam_HD                    | 151       | 1.47%   |
| IMC Networks Integrated Camera                   | 143       | 1.39%   |
| Acer BisonCam, NB Pro                            | 143       | 1.39%   |
| IMC Networks UVC VGA Webcam                      | 140       | 1.36%   |
| Chicony USB2.0 HD UVC WebCam                     | 136       | 1.33%   |
| Chicony USB 2.0 Camera                           | 120       | 1.17%   |
| Realtek Integrated_Webcam_HD                     | 107       | 1.04%   |
| Chicony HP Webcam                                | 103       | 1%      |
| Realtek Lenovo EasyCamera                        | 98        | 0.96%   |
| Chicony VGA WebCam                               | 96        | 0.94%   |
| Quanta VGA WebCam                                | 93        | 0.91%   |
| Chicony USB2.0 VGA UVC WebCam                    | 89        | 0.87%   |
| Syntek Integrated Camera                         | 86        | 0.84%   |
| Alcor Micro Asus Integrated Webcam               | 86        | 0.84%   |
| Silicon Motion WebCam SC-0311139N                | 84        | 0.82%   |
| Syntek Lenovo EasyCamera                         | 79        | 0.77%   |
| IMC Networks Integrated Webcam                   | 79        | 0.77%   |
| Realtek USB Camera                               | 77        | 0.75%   |
| Acer Lenovo EasyCamera                           | 77        | 0.75%   |
| Acer Integrated Camera                           | 77        | 0.75%   |
| IMC Networks HD Camera                           | 76        | 0.74%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 76        | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 74        | 0.72%   |
| DigiTech USB 2.0 PC Camera                       | 74        | 0.72%   |
| Chicony HP Truevision HD                         | 72        | 0.7%    |
| ALi Gateway Webcam                               | 71        | 0.69%   |
| Sunplus Integrated_Webcam_HD                     | 69        | 0.67%   |
| Alcor Micro SHUNCCM2MP                           | 69        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 67        | 0.65%   |
| Chicony EasyCamera                               | 63        | 0.61%   |
| Bison Lenovo EasyCamera                          | 63        | 0.61%   |
| Silicon Motion WebCam SCB-1100N                  | 62        | 0.6%    |
| Suyin 1.3M HD WebCam                             | 60        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 434       | 32.24%  |
| Shenzhen Goodix Technology         | 253       | 18.8%   |
| Synaptics                          | 187       | 13.89%  |
| AuthenTec                          | 134       | 9.96%   |
| Upek                               | 110       | 8.17%   |
| LighTuning Technology              | 94        | 6.98%   |
| Elan Microelectronics              | 85        | 6.32%   |
| STMicroelectronics                 | 34        | 2.53%   |
| Focal-systems.Corp                 | 10        | 0.74%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.3%    |
| Samsung Electronics                | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 200       | 14.86%  |
| Validity Sensors Fingerprint scanner                                       | 99        | 7.36%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 92        | 6.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 88        | 6.54%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 72        | 5.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 60        | 4.46%   |
| Elan ELAN:Fingerprint                                                      | 56        | 4.16%   |
| Shenzhen Goodix Fingerprint Reader                                         | 46        | 3.42%   |
| LighTuning Fingerprint Reader                                              | 44        | 3.27%   |
| AuthenTec AES1600                                                          | 42        | 3.12%   |
| STMicroelectronics Fingerprint Reader                                      | 34        | 2.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 32        | 2.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 32        | 2.38%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 32        | 2.38%   |
| AuthenTec AES2810                                                          | 28        | 2.08%   |
| Validity Sensors VFS491                                                    | 27        | 2.01%   |
| Elan ELAN:ARM-M4                                                           | 26        | 1.93%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 25        | 1.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 24        | 1.78%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 20        | 1.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 19        | 1.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 1.41%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 19        | 1.41%   |
| Upek TCS5B Fingerprint sensor                                              | 18        | 1.34%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 18        | 1.34%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 15        | 1.11%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 14        | 1.04%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 0.97%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 13        | 0.97%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 0.89%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 0.74%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 10        | 0.74%   |
| Synaptics  WBDI                                                            | 10        | 0.74%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 10        | 0.74%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 0.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 0.67%   |
| Synaptics UWP WBDI Device                                                  | 8         | 0.59%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 8         | 0.59%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 0.52%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 97        | 36.88%  |
| Broadcom                  | 85        | 32.32%  |
| Upek                      | 26        | 9.89%   |
| O2 Micro                  | 21        | 7.98%   |
| Lenovo                    | 16        | 6.08%   |
| Yubico.com                | 4         | 1.52%   |
| Gemalto (was Gemplus)     | 4         | 1.52%   |
| Aladdin Knowledge Systems | 4         | 1.52%   |
| Aktiv                     | 3         | 1.14%   |
| Aladdin R.D.              | 2         | 0.76%   |
| Microchip Technology      | 1         | 0.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 95        | 36.12%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 12.93%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 9.89%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 6.84%   |
| Broadcom 5880                                                                | 18        | 6.84%   |
| Broadcom 58200                                                               | 18        | 6.84%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.08%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 5.7%    |
| Yubico.com Yubikey 4 U2F+CCID                                                | 4         | 1.52%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 1.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.14%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.14%   |
| Aktiv Rutoken lite                                                           | 3         | 1.14%   |
| Aladdin R.D. JaCarta                                                         | 2         | 0.76%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.38%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.38%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.38%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 8098      | 66.81%  |
| 1     | 3185      | 26.28%  |
| 2     | 702       | 5.79%   |
| 3     | 112       | 0.92%   |
| 4     | 17        | 0.14%   |
| 5     | 4         | 0.03%   |
| 6     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1731      | 37.5%   |
| Fingerprint reader       | 1341      | 29.05%  |
| Net/wireless             | 426       | 9.23%   |
| Bluetooth                | 255       | 5.52%   |
| Chipcard                 | 231       | 5%      |
| Multimedia controller    | 219       | 4.74%   |
| Camera                   | 114       | 2.47%   |
| Communication controller | 80        | 1.73%   |
| Flash memory             | 62        | 1.34%   |
| Storage                  | 61        | 1.32%   |
| Card reader              | 27        | 0.58%   |
| Sound                    | 21        | 0.45%   |
| Net/ethernet             | 16        | 0.35%   |
| Modem                    | 13        | 0.28%   |
| Network                  | 5         | 0.11%   |
| Dvb card                 | 5         | 0.11%   |
| Storage/ide              | 3         | 0.06%   |
| Firewire controller      | 2         | 0.04%   |
| Wireless                 | 1         | 0.02%   |
| Unclassified device      | 1         | 0.02%   |
| Tv card                  | 1         | 0.02%   |
| Storage/raid             | 1         | 0.02%   |

