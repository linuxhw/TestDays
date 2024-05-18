EndeavourOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

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

Total: 1268

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [eb9d3c539c](https://linux-hardware.org/?probe=eb9d3c539c) | May 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [0ef70379ee](https://linux-hardware.org/?probe=0ef70379ee) | May 07, 2024 |
| HUAWEI        | HLYL-WXX9                   | [71d1f5cdfb](https://linux-hardware.org/?probe=71d1f5cdfb) | May 07, 2024 |
| MSI           | Creator Z16 A12UET          | [edf6b45103](https://linux-hardware.org/?probe=edf6b45103) | May 06, 2024 |
| MSI           | Creator Z16 A12UET          | [2aea1cacac](https://linux-hardware.org/?probe=2aea1cacac) | May 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [c082a264d6](https://linux-hardware.org/?probe=c082a264d6) | May 06, 2024 |
| HP            | ZBook 15 G3                 | [486b46ac77](https://linux-hardware.org/?probe=486b46ac77) | May 05, 2024 |
| HP            | ZBook 15 G3                 | [74576596b1](https://linux-hardware.org/?probe=74576596b1) | May 05, 2024 |
| Unknown       | Unknown                     | [53c592f858](https://linux-hardware.org/?probe=53c592f858) | May 04, 2024 |
| Unknown       | Unknown                     | [3f7e899e58](https://linux-hardware.org/?probe=3f7e899e58) | May 04, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [9ea4c7559c](https://linux-hardware.org/?probe=9ea4c7559c) | May 04, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [d22fed35ce](https://linux-hardware.org/?probe=d22fed35ce) | May 03, 2024 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [6fb2e2c6d4](https://linux-hardware.org/?probe=6fb2e2c6d4) | May 03, 2024 |
| MSI           | GF63 Thin 10SCSR            | [ab0eadc507](https://linux-hardware.org/?probe=ab0eadc507) | May 02, 2024 |
| Dell          | Latitude E5550              | [5388266587](https://linux-hardware.org/?probe=5388266587) | May 02, 2024 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [0656624c78](https://linux-hardware.org/?probe=0656624c78) | May 02, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | [459594827a](https://linux-hardware.org/?probe=459594827a) | Apr 30, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [c1bfbd0de5](https://linux-hardware.org/?probe=c1bfbd0de5) | Apr 28, 2024 |
| ASUSTek       | ExpertBook B9450FAV         | [ea600fc105](https://linux-hardware.org/?probe=ea600fc105) | Apr 27, 2024 |
| HP            | Victus by Gaming Laptop ... | [00f2fc6455](https://linux-hardware.org/?probe=00f2fc6455) | Apr 27, 2024 |
| Lenovo        | ThinkPad L580 20LW000UPB    | [ed17d0c6d4](https://linux-hardware.org/?probe=ed17d0c6d4) | Apr 24, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21HK... | [5e014cccd3](https://linux-hardware.org/?probe=5e014cccd3) | Apr 24, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [a06bcc63e8](https://linux-hardware.org/?probe=a06bcc63e8) | Apr 24, 2024 |
| Acer          | Aspire A315-59G             | [0a16aa62ad](https://linux-hardware.org/?probe=0a16aa62ad) | Apr 23, 2024 |
| Dell          | XPS 15 9520                 | [359a02a8cb](https://linux-hardware.org/?probe=359a02a8cb) | Apr 23, 2024 |
| Lenovo        | Yoga Slim 7 14IMH9 83CV     | [c316cac3ed](https://linux-hardware.org/?probe=c316cac3ed) | Apr 22, 2024 |
| HP            | Laptop 15-dw0xxx            | [b69baa13a6](https://linux-hardware.org/?probe=b69baa13a6) | Apr 22, 2024 |
| Chuwi         | CoreBook X                  | [deafd4078a](https://linux-hardware.org/?probe=deafd4078a) | Apr 20, 2024 |
| Dell          | Latitude 7390 2-in-1        | [08a2cf2960](https://linux-hardware.org/?probe=08a2cf2960) | Apr 20, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a5bdfd5d15](https://linux-hardware.org/?probe=a5bdfd5d15) | Apr 20, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1a7bf4158b](https://linux-hardware.org/?probe=1a7bf4158b) | Apr 20, 2024 |
| Alienware     | m15 R7                      | [e3f2c4e9c3](https://linux-hardware.org/?probe=e3f2c4e9c3) | Apr 19, 2024 |
| HP            | 250 G7 Notebook PC          | [a52eb532e3](https://linux-hardware.org/?probe=a52eb532e3) | Apr 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4cec985734](https://linux-hardware.org/?probe=4cec985734) | Apr 18, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [88a4e369a9](https://linux-hardware.org/?probe=88a4e369a9) | Apr 17, 2024 |
| HP            | Laptop 15-dw0xxx            | [f30fb8d67e](https://linux-hardware.org/?probe=f30fb8d67e) | Apr 16, 2024 |
| HP            | 250 G3                      | [954137cff4](https://linux-hardware.org/?probe=954137cff4) | Apr 15, 2024 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [9826a53ffb](https://linux-hardware.org/?probe=9826a53ffb) | Apr 15, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [0f31e777c7](https://linux-hardware.org/?probe=0f31e777c7) | Apr 15, 2024 |
| Alienware     | m15                         | [477ee79b04](https://linux-hardware.org/?probe=477ee79b04) | Apr 13, 2024 |
| Alienware     | m15                         | [9feac0d1be](https://linux-hardware.org/?probe=9feac0d1be) | Apr 13, 2024 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | [4623f15133](https://linux-hardware.org/?probe=4623f15133) | Apr 13, 2024 |
| Dell          | Latitude E6440              | [2474a0cb33](https://linux-hardware.org/?probe=2474a0cb33) | Apr 12, 2024 |
| HP            | ProBook 650 G1              | [aa6dfe532c](https://linux-hardware.org/?probe=aa6dfe532c) | Apr 12, 2024 |
| Acer          | Aspire 5920                 | [fc886ce6a0](https://linux-hardware.org/?probe=fc886ce6a0) | Apr 11, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [d1322ccf2d](https://linux-hardware.org/?probe=d1322ccf2d) | Apr 10, 2024 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [6cb6635cbb](https://linux-hardware.org/?probe=6cb6635cbb) | Apr 09, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [79e93906ae](https://linux-hardware.org/?probe=79e93906ae) | Apr 07, 2024 |
| Dell          | Latitude 5580               | [295ed34ace](https://linux-hardware.org/?probe=295ed34ace) | Apr 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [952d7591c9](https://linux-hardware.org/?probe=952d7591c9) | Apr 07, 2024 |
| HUAWEI        | NBLK-WAX9X                  | [02e385a043](https://linux-hardware.org/?probe=02e385a043) | Apr 06, 2024 |
| HP            | Pavilion 15                 | [39b89d2411](https://linux-hardware.org/?probe=39b89d2411) | Apr 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [1bdceef448](https://linux-hardware.org/?probe=1bdceef448) | Apr 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [df5337043e](https://linux-hardware.org/?probe=df5337043e) | Apr 06, 2024 |
| ASUSTek       | X550LD                      | [8684e69182](https://linux-hardware.org/?probe=8684e69182) | Apr 05, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [f06c2345e5](https://linux-hardware.org/?probe=f06c2345e5) | Apr 05, 2024 |
| Acer          | Nitro AN515-54              | [1aaafcf056](https://linux-hardware.org/?probe=1aaafcf056) | Apr 05, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [5abe3f3d6a](https://linux-hardware.org/?probe=5abe3f3d6a) | Apr 05, 2024 |
| Alienware     | m15 R7                      | [6952f403ab](https://linux-hardware.org/?probe=6952f403ab) | Apr 02, 2024 |
| HP            | 250 G3                      | [f57828a1b4](https://linux-hardware.org/?probe=f57828a1b4) | Apr 01, 2024 |
| Dell          | Inspiron 3493               | [ed7f522ffa](https://linux-hardware.org/?probe=ed7f522ffa) | Mar 30, 2024 |
| Infinix       | ZERO BOOK 13                | [cd91c5bb1e](https://linux-hardware.org/?probe=cd91c5bb1e) | Mar 28, 2024 |
| HP            | Laptop 15-dw0xxx            | [aec6aec9c6](https://linux-hardware.org/?probe=aec6aec9c6) | Mar 28, 2024 |
| Lenovo        | Legion 7 16IAX7 82TD        | [69037d2e91](https://linux-hardware.org/?probe=69037d2e91) | Mar 27, 2024 |
| Lenovo        | ThinkPad T460s 20FAS5LC0... | [59ae008766](https://linux-hardware.org/?probe=59ae008766) | Mar 27, 2024 |
| Dell          | Latitude 7390 2-in-1        | [754865d59a](https://linux-hardware.org/?probe=754865d59a) | Mar 26, 2024 |
| Casper        | EXCALIBUR G900              | [f5b2fe66ff](https://linux-hardware.org/?probe=f5b2fe66ff) | Mar 24, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [42a2c2872a](https://linux-hardware.org/?probe=42a2c2872a) | Mar 23, 2024 |
| Lenovo        | ThinkPad L450 20DS0006BR    | [b6daa171f8](https://linux-hardware.org/?probe=b6daa171f8) | Mar 23, 2024 |
| Dell          | Latitude 7390 2-in-1        | [cc405a9498](https://linux-hardware.org/?probe=cc405a9498) | Mar 22, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [8573996655](https://linux-hardware.org/?probe=8573996655) | Mar 22, 2024 |
| ASUSTek       | X455LJ                      | [aa4f64e1b7](https://linux-hardware.org/?probe=aa4f64e1b7) | Mar 22, 2024 |
| Dell          | XPS 15 9560                 | [47e7170880](https://linux-hardware.org/?probe=47e7170880) | Mar 21, 2024 |
| HP            | Laptop 15-dw0xxx            | [5845560b28](https://linux-hardware.org/?probe=5845560b28) | Mar 21, 2024 |
| Razer         | Blade 14 - RZ09-0482        | [1c48b858c2](https://linux-hardware.org/?probe=1c48b858c2) | Mar 20, 2024 |
| Dell          | XPS 15 9520                 | [d9ffc0afaf](https://linux-hardware.org/?probe=d9ffc0afaf) | Mar 20, 2024 |
| HP            | Victus by Gaming Laptop ... | [03556f08ce](https://linux-hardware.org/?probe=03556f08ce) | Mar 19, 2024 |
| MSI           | Creator Z16 A12UET          | [3e3a98e47d](https://linux-hardware.org/?probe=3e3a98e47d) | Mar 16, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [22d9bc5efb](https://linux-hardware.org/?probe=22d9bc5efb) | Mar 16, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [fb730fc344](https://linux-hardware.org/?probe=fb730fc344) | Mar 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6e0b43ec0f](https://linux-hardware.org/?probe=6e0b43ec0f) | Mar 15, 2024 |
| Apple         | MacBookPro9,1               | [244a8aa50d](https://linux-hardware.org/?probe=244a8aa50d) | Mar 15, 2024 |
| ASUSTek       | ROG Strix G731GW_G731GW     | [046ddded98](https://linux-hardware.org/?probe=046ddded98) | Mar 14, 2024 |
| ASUSTek       | ROG Strix G731GW_G731GW     | [c1d5b681d3](https://linux-hardware.org/?probe=c1d5b681d3) | Mar 14, 2024 |
| PC Special... | Lafite Pro III 15           | [36af2d3967](https://linux-hardware.org/?probe=36af2d3967) | Mar 14, 2024 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [a83e990b4e](https://linux-hardware.org/?probe=a83e990b4e) | Mar 13, 2024 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [6d944c4cae](https://linux-hardware.org/?probe=6d944c4cae) | Mar 13, 2024 |
| HUAWEI        | NDZ-WXX9                    | [b9a534289f](https://linux-hardware.org/?probe=b9a534289f) | Mar 12, 2024 |
| Alienware     | M17x                        | [073de6c7bd](https://linux-hardware.org/?probe=073de6c7bd) | Mar 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [b00732d7cc](https://linux-hardware.org/?probe=b00732d7cc) | Mar 09, 2024 |
| HP            | Pavilion Laptop 15-eh3xx... | [96df9c795f](https://linux-hardware.org/?probe=96df9c795f) | Mar 08, 2024 |
| Dell          | XPS 15 9560                 | [d2b1898b4b](https://linux-hardware.org/?probe=d2b1898b4b) | Mar 08, 2024 |
| Dell          | Precision 7540              | [e60d9106db](https://linux-hardware.org/?probe=e60d9106db) | Mar 07, 2024 |
| Dell          | XPS 15 9520                 | [c68539af0e](https://linux-hardware.org/?probe=c68539af0e) | Mar 07, 2024 |
| Dell          | Latitude 7280               | [1415cfc829](https://linux-hardware.org/?probe=1415cfc829) | Mar 07, 2024 |
| Lenovo        | ThinkPad P52s 20LCS1Q400    | [a09bbded94](https://linux-hardware.org/?probe=a09bbded94) | Mar 06, 2024 |
| Lenovo        | ThinkPad P52s 20LCS1Q400    | [5eeed0066e](https://linux-hardware.org/?probe=5eeed0066e) | Mar 06, 2024 |
| Dell          | Inspiron 7737               | [5077731ec5](https://linux-hardware.org/?probe=5077731ec5) | Mar 06, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [a7108bda20](https://linux-hardware.org/?probe=a7108bda20) | Mar 05, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [e14a9fae0a](https://linux-hardware.org/?probe=e14a9fae0a) | Mar 05, 2024 |
| Dell          | Latitude 7390               | [7eed1415ba](https://linux-hardware.org/?probe=7eed1415ba) | Mar 05, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | [6fd9429f1c](https://linux-hardware.org/?probe=6fd9429f1c) | Mar 05, 2024 |
| Acer          | Swift SFG14-71T             | [bbd9abaffc](https://linux-hardware.org/?probe=bbd9abaffc) | Mar 04, 2024 |
| Dell          | Latitude 3430               | [4d7bfb4ee6](https://linux-hardware.org/?probe=4d7bfb4ee6) | Mar 03, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [230157b598](https://linux-hardware.org/?probe=230157b598) | Mar 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [438db8c531](https://linux-hardware.org/?probe=438db8c531) | Mar 02, 2024 |
| HP            | ProBook 450 G8              | [550ad596b6](https://linux-hardware.org/?probe=550ad596b6) | Mar 02, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [f610fa6db2](https://linux-hardware.org/?probe=f610fa6db2) | Mar 01, 2024 |
| Google        | Omnigul                     | [e5222edfb9](https://linux-hardware.org/?probe=e5222edfb9) | Mar 01, 2024 |
| Dell          | Inspiron 5570               | [8be61470af](https://linux-hardware.org/?probe=8be61470af) | Feb 29, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [46c0e99842](https://linux-hardware.org/?probe=46c0e99842) | Feb 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [590a2951a0](https://linux-hardware.org/?probe=590a2951a0) | Feb 27, 2024 |
| Toshiba       | Satellite P55-A             | [105f469e59](https://linux-hardware.org/?probe=105f469e59) | Feb 26, 2024 |
| Lenovo        | ThinkPad X230 2325AS6       | [875ff13c8f](https://linux-hardware.org/?probe=875ff13c8f) | Feb 26, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9d91db67e1](https://linux-hardware.org/?probe=9d91db67e1) | Feb 26, 2024 |
| Acer          | Extensa 5620                | [80c455b66f](https://linux-hardware.org/?probe=80c455b66f) | Feb 26, 2024 |
| Dell          | XPS 15 9510                 | [398ee4b3fd](https://linux-hardware.org/?probe=398ee4b3fd) | Feb 25, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [8104acd9fa](https://linux-hardware.org/?probe=8104acd9fa) | Feb 24, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [b6158c1b82](https://linux-hardware.org/?probe=b6158c1b82) | Feb 23, 2024 |
| Sony          | SVF15218SNB                 | [1afb130e3a](https://linux-hardware.org/?probe=1afb130e3a) | Feb 22, 2024 |
| Acer          | TravelMate P215-53          | [6d5f85311e](https://linux-hardware.org/?probe=6d5f85311e) | Feb 21, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [b8151c46bb](https://linux-hardware.org/?probe=b8151c46bb) | Feb 20, 2024 |
| PC Special... | NV4XMB,ME,MZ                | [46d41dc4b2](https://linux-hardware.org/?probe=46d41dc4b2) | Feb 20, 2024 |
| PC Special... | NV4XMB,ME,MZ                | [dc9af46267](https://linux-hardware.org/?probe=dc9af46267) | Feb 20, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [5db36e90e6](https://linux-hardware.org/?probe=5db36e90e6) | Feb 20, 2024 |
| Lenovo        | V15-ADA 82C7                | [916dfe2be8](https://linux-hardware.org/?probe=916dfe2be8) | Feb 19, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RM    | [f6eb8bb7d3](https://linux-hardware.org/?probe=f6eb8bb7d3) | Feb 19, 2024 |
| Apple         | MacBookAir8,1               | [91de6d6520](https://linux-hardware.org/?probe=91de6d6520) | Feb 19, 2024 |
| I-life        | ZEDNOTE                     | [ceefa317d1](https://linux-hardware.org/?probe=ceefa317d1) | Feb 18, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [addc135693](https://linux-hardware.org/?probe=addc135693) | Feb 15, 2024 |
| MSI           | GP72M 7REX                  | [0bba140f23](https://linux-hardware.org/?probe=0bba140f23) | Feb 15, 2024 |
| MSI           | GP72M 7REX                  | [30a3b068c9](https://linux-hardware.org/?probe=30a3b068c9) | Feb 14, 2024 |
| Acer          | Swift SFX14-51G             | [038f3ddc2e](https://linux-hardware.org/?probe=038f3ddc2e) | Feb 14, 2024 |
| Acer          | Swift SF14-71T              | [be5a1a32c8](https://linux-hardware.org/?probe=be5a1a32c8) | Feb 13, 2024 |
| HP            | Laptop 15-dw0xxx            | [5b9367efbe](https://linux-hardware.org/?probe=5b9367efbe) | Feb 13, 2024 |
| HP            | Laptop 15-dw0xxx            | [c83de1da34](https://linux-hardware.org/?probe=c83de1da34) | Feb 13, 2024 |
| Dell          | Latitude E5520              | [3c94789c2b](https://linux-hardware.org/?probe=3c94789c2b) | Feb 11, 2024 |
| Dell          | Inspiron 7559               | [9f3df9cfa3](https://linux-hardware.org/?probe=9f3df9cfa3) | Feb 09, 2024 |
| Acer          | Predator PH315-51           | [5b0975c105](https://linux-hardware.org/?probe=5b0975c105) | Feb 09, 2024 |
| Lenovo        | IdeaPad C340-14API 81N6     | [1686f16b06](https://linux-hardware.org/?probe=1686f16b06) | Feb 08, 2024 |
| Lenovo        | V15 G2 ALC 82KD             | [5372f5846e](https://linux-hardware.org/?probe=5372f5846e) | Feb 08, 2024 |
| HP            | Stream Laptop 14-CB1xxx     | [36758fa351](https://linux-hardware.org/?probe=36758fa351) | Feb 08, 2024 |
| Dell          | XPS 13 7390                 | [d68f1566cc](https://linux-hardware.org/?probe=d68f1566cc) | Feb 07, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [1125374dbc](https://linux-hardware.org/?probe=1125374dbc) | Feb 05, 2024 |
| Acer          | Nitro AN517-54              | [e29ea22904](https://linux-hardware.org/?probe=e29ea22904) | Feb 03, 2024 |
| Lenovo        | ThinkPad X230 2325SW9       | [e8681e8668](https://linux-hardware.org/?probe=e8681e8668) | Feb 03, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [a538d10d4b](https://linux-hardware.org/?probe=a538d10d4b) | Feb 02, 2024 |
| ASUSTek       | K53BR                       | [bd5284a0e8](https://linux-hardware.org/?probe=bd5284a0e8) | Feb 02, 2024 |
| Schenker      | XMG PRO (Late 2021)         | [502d4a5570](https://linux-hardware.org/?probe=502d4a5570) | Feb 02, 2024 |
| MSI           | Prestige 13 AI Evo A1MG     | [abc18d1a9e](https://linux-hardware.org/?probe=abc18d1a9e) | Feb 02, 2024 |
| Schenker      | XMG PRO (Late 2021)         | [0bd25ae10e](https://linux-hardware.org/?probe=0bd25ae10e) | Feb 02, 2024 |
| ALTYK         | L14F-I5U16-N1               | [7cb618fcca](https://linux-hardware.org/?probe=7cb618fcca) | Feb 01, 2024 |
| ALTYK         | L14F-I5U16-N1               | [81274a6f09](https://linux-hardware.org/?probe=81274a6f09) | Feb 01, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [cbcf46b2fa](https://linux-hardware.org/?probe=cbcf46b2fa) | Jan 31, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [40f306477e](https://linux-hardware.org/?probe=40f306477e) | Jan 31, 2024 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [aecdf1facc](https://linux-hardware.org/?probe=aecdf1facc) | Jan 30, 2024 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [c0c78e6476](https://linux-hardware.org/?probe=c0c78e6476) | Jan 29, 2024 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ffc3c06598](https://linux-hardware.org/?probe=ffc3c06598) | Jan 29, 2024 |
| EVOO          | EG-LP6                      | [94916a68a1](https://linux-hardware.org/?probe=94916a68a1) | Jan 28, 2024 |
| System76      | Gazelle                     | [317f744565](https://linux-hardware.org/?probe=317f744565) | Jan 27, 2024 |
| System76      | Gazelle                     | [27bb9a725a](https://linux-hardware.org/?probe=27bb9a725a) | Jan 27, 2024 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | [c777cd17b5](https://linux-hardware.org/?probe=c777cd17b5) | Jan 26, 2024 |
| Monster       | ABRA A7 V13.3               | [08516ca0c2](https://linux-hardware.org/?probe=08516ca0c2) | Jan 26, 2024 |
| Acer          | Aspire A315-55G             | [c04d6bddfb](https://linux-hardware.org/?probe=c04d6bddfb) | Jan 24, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f37a4265ba](https://linux-hardware.org/?probe=f37a4265ba) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [73c0dd5770](https://linux-hardware.org/?probe=73c0dd5770) | Jan 23, 2024 |
| ASUSTek       | G2S                         | [534f9d0459](https://linux-hardware.org/?probe=534f9d0459) | Jan 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [dc6c66931e](https://linux-hardware.org/?probe=dc6c66931e) | Jan 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [833af537d7](https://linux-hardware.org/?probe=833af537d7) | Jan 21, 2024 |
| HP            | ProBook 440 G5              | [1ad08b8198](https://linux-hardware.org/?probe=1ad08b8198) | Jan 21, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [7f7ae7af9f](https://linux-hardware.org/?probe=7f7ae7af9f) | Jan 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1427f84afd](https://linux-hardware.org/?probe=1427f84afd) | Jan 18, 2024 |
| Acer          | Nitro AN517-54              | [e736d57544](https://linux-hardware.org/?probe=e736d57544) | Jan 18, 2024 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [817d6ac197](https://linux-hardware.org/?probe=817d6ac197) | Jan 18, 2024 |
| HP            | OMEN by Transcend Gaming... | [6690260fd8](https://linux-hardware.org/?probe=6690260fd8) | Jan 18, 2024 |
| Dell          | Inspiron 3583               | [e70de12740](https://linux-hardware.org/?probe=e70de12740) | Jan 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [89d8674908](https://linux-hardware.org/?probe=89d8674908) | Jan 18, 2024 |
| HP            | Laptop 15-dw0xxx            | [b17351aa59](https://linux-hardware.org/?probe=b17351aa59) | Jan 15, 2024 |
| Sony          | SVE1713X1EB                 | [43af98d3bc](https://linux-hardware.org/?probe=43af98d3bc) | Jan 14, 2024 |
| Dell          | Latitude E6420              | [78cffcaf30](https://linux-hardware.org/?probe=78cffcaf30) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [e2058a8b66](https://linux-hardware.org/?probe=e2058a8b66) | Jan 14, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0823cf66ec](https://linux-hardware.org/?probe=0823cf66ec) | Jan 13, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [49e9436217](https://linux-hardware.org/?probe=49e9436217) | Jan 13, 2024 |
| MSI           | MPG Z390 GAMING EDGE AC     | [4fc5db3901](https://linux-hardware.org/?probe=4fc5db3901) | Jan 13, 2024 |
| Dell          | Latitude E5470              | [a2211d635f](https://linux-hardware.org/?probe=a2211d635f) | Jan 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [14eff97de5](https://linux-hardware.org/?probe=14eff97de5) | Jan 10, 2024 |
| Dell          | Latitude 7280               | [de1f6a94e6](https://linux-hardware.org/?probe=de1f6a94e6) | Jan 08, 2024 |
| Dell          | G3 3579                     | [5c48d53216](https://linux-hardware.org/?probe=5c48d53216) | Jan 07, 2024 |
| Dell          | G3 3579                     | [6ee6a6d56a](https://linux-hardware.org/?probe=6ee6a6d56a) | Jan 07, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [8118029878](https://linux-hardware.org/?probe=8118029878) | Jan 06, 2024 |
| Acer          | Nitro AN515-57              | [cd2d137285](https://linux-hardware.org/?probe=cd2d137285) | Jan 05, 2024 |
| Dell          | Inspiron 14 5425            | [a66f85e48e](https://linux-hardware.org/?probe=a66f85e48e) | Jan 03, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | [ccc67d11a0](https://linux-hardware.org/?probe=ccc67d11a0) | Jan 03, 2024 |
| HP            | EliteBook 845 14 inch G1... | [abd73c6a90](https://linux-hardware.org/?probe=abd73c6a90) | Jan 03, 2024 |
| Sony          | SVE1713X1EB                 | [6c3167a5a7](https://linux-hardware.org/?probe=6c3167a5a7) | Jan 02, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [502ebc99c3](https://linux-hardware.org/?probe=502ebc99c3) | Jan 02, 2024 |
| Sony          | SVE1713X1EB                 | [f9081b680a](https://linux-hardware.org/?probe=f9081b680a) | Jan 01, 2024 |
| ASUSTek       | PRIME X570-P                | [12b2d456ed](https://linux-hardware.org/?probe=12b2d456ed) | Dec 30, 2023 |
| MSI           | Prestige 15 A10SC           | [e61eb5428f](https://linux-hardware.org/?probe=e61eb5428f) | Dec 30, 2023 |
| ASUSTek       | PRIME X570-P                | [596a41673a](https://linux-hardware.org/?probe=596a41673a) | Dec 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2490d5b834](https://linux-hardware.org/?probe=2490d5b834) | Dec 30, 2023 |
| Dell          | Latitude 5580               | [3079edcb81](https://linux-hardware.org/?probe=3079edcb81) | Dec 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [55340871af](https://linux-hardware.org/?probe=55340871af) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3b6d015d5a](https://linux-hardware.org/?probe=3b6d015d5a) | Dec 29, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0060... | [485c94e992](https://linux-hardware.org/?probe=485c94e992) | Dec 29, 2023 |
| ASUSTek       | UL80VT                      | [d9e57db214](https://linux-hardware.org/?probe=d9e57db214) | Dec 28, 2023 |
| ASUSTek       | UL80VT                      | [8532e3dcca](https://linux-hardware.org/?probe=8532e3dcca) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a1652ba789](https://linux-hardware.org/?probe=a1652ba789) | Dec 28, 2023 |
| GPD           | G1619-04                    | [f77175c08b](https://linux-hardware.org/?probe=f77175c08b) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f58bf5fe4c](https://linux-hardware.org/?probe=f58bf5fe4c) | Dec 26, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [b08bd5ba2c](https://linux-hardware.org/?probe=b08bd5ba2c) | Dec 25, 2023 |
| Acer          | Swift SF314-51              | [a2f71698e2](https://linux-hardware.org/?probe=a2f71698e2) | Dec 25, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [76b5abd1bd](https://linux-hardware.org/?probe=76b5abd1bd) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [5aae7c7b5c](https://linux-hardware.org/?probe=5aae7c7b5c) | Dec 23, 2023 |
| Dell          | XPS 15 9520                 | [9fea6c876a](https://linux-hardware.org/?probe=9fea6c876a) | Dec 21, 2023 |
| Sony          | SVE1713X1EB                 | [dd67c36ae3](https://linux-hardware.org/?probe=dd67c36ae3) | Dec 21, 2023 |
| Dell          | Inspiron 15 3520            | [dac9572e21](https://linux-hardware.org/?probe=dac9572e21) | Dec 20, 2023 |
| Acer          | Swift SF314-57G             | [b822161722](https://linux-hardware.org/?probe=b822161722) | Dec 19, 2023 |
| Dell          | Inspiron 5570               | [55a83cf2cb](https://linux-hardware.org/?probe=55a83cf2cb) | Dec 19, 2023 |
| TUXEDO        | Aura 14 Gen3                | [bdc38bf0fd](https://linux-hardware.org/?probe=bdc38bf0fd) | Dec 19, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [dec9660b8e](https://linux-hardware.org/?probe=dec9660b8e) | Dec 18, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [02ffa90273](https://linux-hardware.org/?probe=02ffa90273) | Dec 18, 2023 |
| HP            | Laptop 15-dw0xxx            | [185314f313](https://linux-hardware.org/?probe=185314f313) | Dec 17, 2023 |
| HP            | Laptop 15-dw0xxx            | [87d3b447bb](https://linux-hardware.org/?probe=87d3b447bb) | Dec 17, 2023 |
| Acer          | Aspire V5-573G              | [723eb61284](https://linux-hardware.org/?probe=723eb61284) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [2c4dba512d](https://linux-hardware.org/?probe=2c4dba512d) | Dec 16, 2023 |
| Acer          | Nitro AN715-51              | [279ade4fb0](https://linux-hardware.org/?probe=279ade4fb0) | Dec 16, 2023 |
| ASUSTek       | UX490UAR                    | [e8aa69b910](https://linux-hardware.org/?probe=e8aa69b910) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [db30b82451](https://linux-hardware.org/?probe=db30b82451) | Dec 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7b209666a3](https://linux-hardware.org/?probe=7b209666a3) | Dec 16, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [93fea0297b](https://linux-hardware.org/?probe=93fea0297b) | Dec 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [3d4b7d5e8b](https://linux-hardware.org/?probe=3d4b7d5e8b) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8339b9aa1a](https://linux-hardware.org/?probe=8339b9aa1a) | Dec 13, 2023 |
| Universal ... | MONTENERO-C                 | [dcab78af9a](https://linux-hardware.org/?probe=dcab78af9a) | Dec 13, 2023 |
| Dell          | Inspiron 16 Plus 7630       | [25017a9de6](https://linux-hardware.org/?probe=25017a9de6) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [6a742a5308](https://linux-hardware.org/?probe=6a742a5308) | Dec 13, 2023 |
| Lenovo        | ThinkPad W530 24382KU       | [b389060869](https://linux-hardware.org/?probe=b389060869) | Dec 12, 2023 |
| HP            | EliteBook 840 14 inch G1... | [17dd4245b8](https://linux-hardware.org/?probe=17dd4245b8) | Dec 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bc96bd94d2](https://linux-hardware.org/?probe=bc96bd94d2) | Dec 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e7b5bdd470](https://linux-hardware.org/?probe=e7b5bdd470) | Dec 09, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [5e6fc96a08](https://linux-hardware.org/?probe=5e6fc96a08) | Dec 09, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [b848110f65](https://linux-hardware.org/?probe=b848110f65) | Dec 08, 2023 |
| Acer          | Nitro AN515-52              | [7c4bc43db7](https://linux-hardware.org/?probe=7c4bc43db7) | Dec 06, 2023 |
| HP            | ProBook 650 G1              | [06fe795e93](https://linux-hardware.org/?probe=06fe795e93) | Dec 05, 2023 |
| Sony          | SVE1713X1EB                 | [3c8e9b9cc4](https://linux-hardware.org/?probe=3c8e9b9cc4) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | [c0681fbe8a](https://linux-hardware.org/?probe=c0681fbe8a) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | [54178ea597](https://linux-hardware.org/?probe=54178ea597) | Dec 03, 2023 |
| HP            | Laptop 15-dw0xxx            | [288b6a2f75](https://linux-hardware.org/?probe=288b6a2f75) | Dec 02, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [5f31cddd2f](https://linux-hardware.org/?probe=5f31cddd2f) | Dec 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6a029b4d87](https://linux-hardware.org/?probe=6a029b4d87) | Nov 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [62b38954c4](https://linux-hardware.org/?probe=62b38954c4) | Nov 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ad9b9e5fd1](https://linux-hardware.org/?probe=ad9b9e5fd1) | Nov 30, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [aca3298198](https://linux-hardware.org/?probe=aca3298198) | Nov 28, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0dbf67ab6f](https://linux-hardware.org/?probe=0dbf67ab6f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d5d85d7080](https://linux-hardware.org/?probe=d5d85d7080) | Nov 27, 2023 |
| HP            | EliteBook 745 G4            | [c3c18efc38](https://linux-hardware.org/?probe=c3c18efc38) | Nov 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [61a33862ad](https://linux-hardware.org/?probe=61a33862ad) | Nov 26, 2023 |
| HP            | EliteBook 745 G4            | [33d8baae78](https://linux-hardware.org/?probe=33d8baae78) | Nov 26, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [a80073b9be](https://linux-hardware.org/?probe=a80073b9be) | Nov 25, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | [06170c8841](https://linux-hardware.org/?probe=06170c8841) | Nov 25, 2023 |
| Acer          | Nitro AN515-54              | [261d00b9c1](https://linux-hardware.org/?probe=261d00b9c1) | Nov 25, 2023 |
| Acer          | Nitro AN515-54              | [fe4e9cf955](https://linux-hardware.org/?probe=fe4e9cf955) | Nov 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ac2895b3d7](https://linux-hardware.org/?probe=ac2895b3d7) | Nov 24, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [a58a5557e6](https://linux-hardware.org/?probe=a58a5557e6) | Nov 24, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [7cd9c24a07](https://linux-hardware.org/?probe=7cd9c24a07) | Nov 23, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [9d7f74829e](https://linux-hardware.org/?probe=9d7f74829e) | Nov 23, 2023 |
| HP            | EliteBook 6930p             | [6bc9169e34](https://linux-hardware.org/?probe=6bc9169e34) | Nov 23, 2023 |
| ASUSTek       | X751LD                      | [f41a7c6412](https://linux-hardware.org/?probe=f41a7c6412) | Nov 22, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [ce955eaeb4](https://linux-hardware.org/?probe=ce955eaeb4) | Nov 22, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [194465c3c5](https://linux-hardware.org/?probe=194465c3c5) | Nov 22, 2023 |
| Sony          | SVE1713X1EB                 | [a6efd4193b](https://linux-hardware.org/?probe=a6efd4193b) | Nov 21, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [86845a8402](https://linux-hardware.org/?probe=86845a8402) | Nov 20, 2023 |
| Fujitsu       | FMVC06001                   | [122e4a9608](https://linux-hardware.org/?probe=122e4a9608) | Nov 20, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [b7e16888b9](https://linux-hardware.org/?probe=b7e16888b9) | Nov 20, 2023 |
| Apple         | MacBookAir6,2               | [9274d4e825](https://linux-hardware.org/?probe=9274d4e825) | Nov 20, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [c3769c8a57](https://linux-hardware.org/?probe=c3769c8a57) | Nov 18, 2023 |
| TUXEDO        | Gemini Gen2                 | [43d1c51e23](https://linux-hardware.org/?probe=43d1c51e23) | Nov 17, 2023 |
| MSI           | GF65 Thin 10UE              | [04d65c8c40](https://linux-hardware.org/?probe=04d65c8c40) | Nov 15, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [3be8e07c6c](https://linux-hardware.org/?probe=3be8e07c6c) | Nov 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [018253183e](https://linux-hardware.org/?probe=018253183e) | Nov 14, 2023 |
| Dell          | XPS 15 9570                 | [ed85cdf855](https://linux-hardware.org/?probe=ed85cdf855) | Nov 13, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [b299fd1fe9](https://linux-hardware.org/?probe=b299fd1fe9) | Nov 09, 2023 |
| Lenovo        | ThinkPad T430s 23553J2      | [d035513169](https://linux-hardware.org/?probe=d035513169) | Nov 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [b8a00231d6](https://linux-hardware.org/?probe=b8a00231d6) | Nov 08, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [16cf6c0ede](https://linux-hardware.org/?probe=16cf6c0ede) | Nov 08, 2023 |
| Medion        | P6681 MD60814               | [a17f8ffc19](https://linux-hardware.org/?probe=a17f8ffc19) | Nov 07, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [6f5721955b](https://linux-hardware.org/?probe=6f5721955b) | Nov 07, 2023 |
| Dell          | G7 7700                     | [0fc7811fdd](https://linux-hardware.org/?probe=0fc7811fdd) | Nov 07, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [985ed440bf](https://linux-hardware.org/?probe=985ed440bf) | Nov 06, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [1cf99ffe12](https://linux-hardware.org/?probe=1cf99ffe12) | Nov 05, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [cf8911c5e0](https://linux-hardware.org/?probe=cf8911c5e0) | Nov 05, 2023 |
| HP            | ProBook 430 G1              | [451abee058](https://linux-hardware.org/?probe=451abee058) | Nov 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [db71fb65bf](https://linux-hardware.org/?probe=db71fb65bf) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b592d36d74](https://linux-hardware.org/?probe=b592d36d74) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [da695062ba](https://linux-hardware.org/?probe=da695062ba) | Nov 03, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [de293a4621](https://linux-hardware.org/?probe=de293a4621) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b0c996ac38](https://linux-hardware.org/?probe=b0c996ac38) | Nov 02, 2023 |
| ASUSTek       | UX430UNR                    | [47abbeb9c1](https://linux-hardware.org/?probe=47abbeb9c1) | Nov 01, 2023 |
| MSI           | GV62 8RD                    | [d85cb220a0](https://linux-hardware.org/?probe=d85cb220a0) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [865e6764f2](https://linux-hardware.org/?probe=865e6764f2) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [bf87ba6b55](https://linux-hardware.org/?probe=bf87ba6b55) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | [0b21a4419d](https://linux-hardware.org/?probe=0b21a4419d) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | [757199e3cf](https://linux-hardware.org/?probe=757199e3cf) | Nov 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6c1c4ea069](https://linux-hardware.org/?probe=6c1c4ea069) | Oct 31, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUA... | [701a08bdb6](https://linux-hardware.org/?probe=701a08bdb6) | Oct 31, 2023 |
| HP            | Laptop 15-dw0xxx            | [55f41faf27](https://linux-hardware.org/?probe=55f41faf27) | Oct 31, 2023 |
| MSI           | Modern 15 A11M              | [43161bd5f4](https://linux-hardware.org/?probe=43161bd5f4) | Oct 30, 2023 |
| HP            | ProBook 650 G1              | [508c244637](https://linux-hardware.org/?probe=508c244637) | Oct 30, 2023 |
| HP            | 255 G6 Notebook PC          | [f19f70993f](https://linux-hardware.org/?probe=f19f70993f) | Oct 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [448c3ca446](https://linux-hardware.org/?probe=448c3ca446) | Oct 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [c1d00eb91f](https://linux-hardware.org/?probe=c1d00eb91f) | Oct 29, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [aaf303e411](https://linux-hardware.org/?probe=aaf303e411) | Oct 28, 2023 |
| Apple         | MacBookPro16,1              | [0e1711e674](https://linux-hardware.org/?probe=0e1711e674) | Oct 28, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [e0dc47cf61](https://linux-hardware.org/?probe=e0dc47cf61) | Oct 28, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [1f5d6e4141](https://linux-hardware.org/?probe=1f5d6e4141) | Oct 27, 2023 |
| HP            | ZBook 15 G3                 | [21bcc65553](https://linux-hardware.org/?probe=21bcc65553) | Oct 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [5aef96bd0e](https://linux-hardware.org/?probe=5aef96bd0e) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [9c37fcb5c9](https://linux-hardware.org/?probe=9c37fcb5c9) | Oct 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [e2e4b18ec2](https://linux-hardware.org/?probe=e2e4b18ec2) | Oct 23, 2023 |
| HP            | Snappy                      | [2d0c13b032](https://linux-hardware.org/?probe=2d0c13b032) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f103762ce5](https://linux-hardware.org/?probe=f103762ce5) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | [147d6ad175](https://linux-hardware.org/?probe=147d6ad175) | Oct 21, 2023 |
| HP            | Snappy                      | [b8dc14dc5d](https://linux-hardware.org/?probe=b8dc14dc5d) | Oct 21, 2023 |
| Dell          | XPS 15 9520                 | [7deca235e3](https://linux-hardware.org/?probe=7deca235e3) | Oct 20, 2023 |
| Acer          | Aspire E5-523G              | [12b93b3f48](https://linux-hardware.org/?probe=12b93b3f48) | Oct 20, 2023 |
| Acer          | Aspire E5-523G              | [240879310d](https://linux-hardware.org/?probe=240879310d) | Oct 19, 2023 |
| Sony          | SVE1713X1EB                 | [ec015a6c9e](https://linux-hardware.org/?probe=ec015a6c9e) | Oct 19, 2023 |
| Dell          | XPS 15 9530                 | [e350eec913](https://linux-hardware.org/?probe=e350eec913) | Oct 19, 2023 |
| HP            | EliteBook 845 14 inch G1... | [5ee2d06317](https://linux-hardware.org/?probe=5ee2d06317) | Oct 15, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [0d80ec0e27](https://linux-hardware.org/?probe=0d80ec0e27) | Oct 15, 2023 |
| Toshiba       | Satellite C855-1KF          | [1dbc7c0de3](https://linux-hardware.org/?probe=1dbc7c0de3) | Oct 15, 2023 |
| MSI           | GS63 Stealth 8RE            | [a83fe5a954](https://linux-hardware.org/?probe=a83fe5a954) | Oct 11, 2023 |
| MSI           | GS63 Stealth 8RE            | [5f9d5460fb](https://linux-hardware.org/?probe=5f9d5460fb) | Oct 11, 2023 |
| Dell          | XPS 15 9520                 | [04fbcfc11b](https://linux-hardware.org/?probe=04fbcfc11b) | Oct 10, 2023 |
| Dell          | Latitude 7420               | [4071bd53ce](https://linux-hardware.org/?probe=4071bd53ce) | Oct 10, 2023 |
| System76      | Gazelle                     | [1a40053c3e](https://linux-hardware.org/?probe=1a40053c3e) | Oct 07, 2023 |
| Acer          | Aspire 7730G                | [d48f861a2e](https://linux-hardware.org/?probe=d48f861a2e) | Oct 05, 2023 |
| HP            | ZBook 14u G4                | [1d14da7190](https://linux-hardware.org/?probe=1d14da7190) | Oct 05, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [cc02a5e08e](https://linux-hardware.org/?probe=cc02a5e08e) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8e0792976d](https://linux-hardware.org/?probe=8e0792976d) | Oct 03, 2023 |
| Sony          | SVE1713X1EB                 | [ca5985274a](https://linux-hardware.org/?probe=ca5985274a) | Oct 02, 2023 |
| Razer         | Blade 15 Base Model (Lat... | [4e1788f184](https://linux-hardware.org/?probe=4e1788f184) | Oct 02, 2023 |
| Gigabyte      | AERO 15-X9                  | [35830807d4](https://linux-hardware.org/?probe=35830807d4) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | [1c4b1aa68d](https://linux-hardware.org/?probe=1c4b1aa68d) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | [988f015a89](https://linux-hardware.org/?probe=988f015a89) | Sep 30, 2023 |
| Lenovo        | ThinkPad E495 20NES07V00    | [935dc10f6b](https://linux-hardware.org/?probe=935dc10f6b) | Sep 30, 2023 |
| Dell          | Latitude 5410               | [d13c5769a3](https://linux-hardware.org/?probe=d13c5769a3) | Sep 30, 2023 |
| MSI           | GL73 8RE                    | [670f7351b5](https://linux-hardware.org/?probe=670f7351b5) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | [1543bac588](https://linux-hardware.org/?probe=1543bac588) | Sep 27, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [b8b2b3ff7e](https://linux-hardware.org/?probe=b8b2b3ff7e) | Sep 26, 2023 |
| Acer          | Nitro AN515-45              | [94ce4b6306](https://linux-hardware.org/?probe=94ce4b6306) | Sep 25, 2023 |
| MSI           | GS63VR 6RF                  | [03a9aed3c9](https://linux-hardware.org/?probe=03a9aed3c9) | Sep 25, 2023 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [7ea3152d65](https://linux-hardware.org/?probe=7ea3152d65) | Sep 25, 2023 |
| Dell          | G5 5505                     | [e9c461d44d](https://linux-hardware.org/?probe=e9c461d44d) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [cada97becf](https://linux-hardware.org/?probe=cada97becf) | Sep 25, 2023 |
| Acer          | Aspire A515-51              | [f6369d0be5](https://linux-hardware.org/?probe=f6369d0be5) | Sep 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [2d1e14cb66](https://linux-hardware.org/?probe=2d1e14cb66) | Sep 23, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [45f00aaf92](https://linux-hardware.org/?probe=45f00aaf92) | Sep 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [9fdc142c76](https://linux-hardware.org/?probe=9fdc142c76) | Sep 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [d940deb0df](https://linux-hardware.org/?probe=d940deb0df) | Sep 19, 2023 |
| HP            | EliteBook 865 16 inch G9... | [5cab8957eb](https://linux-hardware.org/?probe=5cab8957eb) | Sep 18, 2023 |
| HP            | Dragonfly Pro               | [0c5d439504](https://linux-hardware.org/?probe=0c5d439504) | Sep 18, 2023 |
| Dell          | Latitude E5470              | [0602c2deb2](https://linux-hardware.org/?probe=0602c2deb2) | Sep 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [aea37f693f](https://linux-hardware.org/?probe=aea37f693f) | Sep 15, 2023 |
| Dell          | Precision 7710              | [c954042e8b](https://linux-hardware.org/?probe=c954042e8b) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [2260bcd7af](https://linux-hardware.org/?probe=2260bcd7af) | Sep 12, 2023 |
| Sony          | SVE1713X1EB                 | [2284d8a2dd](https://linux-hardware.org/?probe=2284d8a2dd) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | [dca28b0d09](https://linux-hardware.org/?probe=dca28b0d09) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | [6c6c4a19ec](https://linux-hardware.org/?probe=6c6c4a19ec) | Sep 12, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [e72c31a6fc](https://linux-hardware.org/?probe=e72c31a6fc) | Sep 11, 2023 |
| Acer          | Swift SF314-512             | [4628c4e630](https://linux-hardware.org/?probe=4628c4e630) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d8ac2101a](https://linux-hardware.org/?probe=6d8ac2101a) | Sep 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [16b6bd1d3d](https://linux-hardware.org/?probe=16b6bd1d3d) | Sep 09, 2023 |
| HP            | 255 G8 Notebook PC          | [bdd270eddd](https://linux-hardware.org/?probe=bdd270eddd) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [5b0ce3438c](https://linux-hardware.org/?probe=5b0ce3438c) | Sep 08, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [6870581b7c](https://linux-hardware.org/?probe=6870581b7c) | Sep 08, 2023 |
| HP            | EliteBook 865 16 inch G9... | [872f12f24c](https://linux-hardware.org/?probe=872f12f24c) | Sep 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d5430e9279](https://linux-hardware.org/?probe=d5430e9279) | Sep 08, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [5b22cd283b](https://linux-hardware.org/?probe=5b22cd283b) | Sep 08, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [003d136012](https://linux-hardware.org/?probe=003d136012) | Sep 07, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [79ddc77f63](https://linux-hardware.org/?probe=79ddc77f63) | Sep 07, 2023 |
| Sony          | SVE1713X1EB                 | [f7c65dc902](https://linux-hardware.org/?probe=f7c65dc902) | Sep 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [cd1be324d4](https://linux-hardware.org/?probe=cd1be324d4) | Sep 05, 2023 |
| Sony          | SVE1513B1EW                 | [82fd19c99e](https://linux-hardware.org/?probe=82fd19c99e) | Sep 05, 2023 |
| MSI           | GS75 Stealth 8SG            | [fc603fc196](https://linux-hardware.org/?probe=fc603fc196) | Sep 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | [13b7789482](https://linux-hardware.org/?probe=13b7789482) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | [8a4af58adc](https://linux-hardware.org/?probe=8a4af58adc) | Sep 04, 2023 |
| ASUSTek       | N750JV                      | [f23cf01c1c](https://linux-hardware.org/?probe=f23cf01c1c) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [db2e607ae6](https://linux-hardware.org/?probe=db2e607ae6) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [b652970974](https://linux-hardware.org/?probe=b652970974) | Sep 01, 2023 |
| HP            | Pavilion Aero Laptop 13z... | [afa88a8a6a](https://linux-hardware.org/?probe=afa88a8a6a) | Sep 01, 2023 |
| MSI           | Modern 15 A5M               | [a6619c179c](https://linux-hardware.org/?probe=a6619c179c) | Aug 31, 2023 |
| Fujitsu       | LIFEBOOK U904               | [7cf4986142](https://linux-hardware.org/?probe=7cf4986142) | Aug 29, 2023 |
| Dell          | Inspiron 3542               | [320e8d218f](https://linux-hardware.org/?probe=320e8d218f) | Aug 28, 2023 |
| ASUSTek       | X550VXK                     | [897e4f89ec](https://linux-hardware.org/?probe=897e4f89ec) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [657c08f61f](https://linux-hardware.org/?probe=657c08f61f) | Aug 27, 2023 |
| Sony          | SVE1713X1EB                 | [ab8f75bb84](https://linux-hardware.org/?probe=ab8f75bb84) | Aug 27, 2023 |
| Google        | Madoo                       | [6644bab363](https://linux-hardware.org/?probe=6644bab363) | Aug 26, 2023 |
| HP            | EliteBook 645 14 inch G9... | [d02a7851a6](https://linux-hardware.org/?probe=d02a7851a6) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [3eea0be3b4](https://linux-hardware.org/?probe=3eea0be3b4) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [53ba2f91cd](https://linux-hardware.org/?probe=53ba2f91cd) | Aug 24, 2023 |
| Dell          | Latitude E5470              | [637ccef7bd](https://linux-hardware.org/?probe=637ccef7bd) | Aug 24, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [816f3ce721](https://linux-hardware.org/?probe=816f3ce721) | Aug 24, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [ef3454780b](https://linux-hardware.org/?probe=ef3454780b) | Aug 23, 2023 |
| HP            | 250 G4                      | [1eb6dc4c12](https://linux-hardware.org/?probe=1eb6dc4c12) | Aug 23, 2023 |
| Lenovo        | ThinkPad E495 20NES0KM00    | [783db5b84d](https://linux-hardware.org/?probe=783db5b84d) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | [26d59e1060](https://linux-hardware.org/?probe=26d59e1060) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | [d10b0c4ca0](https://linux-hardware.org/?probe=d10b0c4ca0) | Aug 23, 2023 |
| Sony          | SVE1713X1EB                 | [165cab2421](https://linux-hardware.org/?probe=165cab2421) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | [6112b46746](https://linux-hardware.org/?probe=6112b46746) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | [b883100fd3](https://linux-hardware.org/?probe=b883100fd3) | Aug 21, 2023 |
| MSI           | Katana 15 B13VGK            | [c21afd5e9f](https://linux-hardware.org/?probe=c21afd5e9f) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b6aa75cb80](https://linux-hardware.org/?probe=b6aa75cb80) | Aug 20, 2023 |
| Packard Be... | EasyNote TJ66               | [7e5e1655a6](https://linux-hardware.org/?probe=7e5e1655a6) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [d6df464cc7](https://linux-hardware.org/?probe=d6df464cc7) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [471f5f6132](https://linux-hardware.org/?probe=471f5f6132) | Aug 20, 2023 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [60385dd9f0](https://linux-hardware.org/?probe=60385dd9f0) | Aug 20, 2023 |
| HP            | EliteBook 865 16 inch G9... | [f99d3dca93](https://linux-hardware.org/?probe=f99d3dca93) | Aug 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | [5ed6b3612a](https://linux-hardware.org/?probe=5ed6b3612a) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [6e6a7171bf](https://linux-hardware.org/?probe=6e6a7171bf) | Aug 16, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [1632c89b98](https://linux-hardware.org/?probe=1632c89b98) | Aug 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [246c60a344](https://linux-hardware.org/?probe=246c60a344) | Aug 13, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [6cbef2a38d](https://linux-hardware.org/?probe=6cbef2a38d) | Aug 13, 2023 |
| Acer          | Aspire A317-53              | [17dacd99a6](https://linux-hardware.org/?probe=17dacd99a6) | Aug 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [083e25221d](https://linux-hardware.org/?probe=083e25221d) | Aug 10, 2023 |
| Acer          | Aspire A317-53              | [5a2d81b438](https://linux-hardware.org/?probe=5a2d81b438) | Aug 09, 2023 |
| Dell          | Latitude E5570              | [cbcea81a37](https://linux-hardware.org/?probe=cbcea81a37) | Aug 06, 2023 |
| Toshiba       | PORTEGE R700                | [f0df061bb2](https://linux-hardware.org/?probe=f0df061bb2) | Aug 04, 2023 |
| Dell          | Vostro 3500                 | [5f63621af2](https://linux-hardware.org/?probe=5f63621af2) | Aug 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [731ae84313](https://linux-hardware.org/?probe=731ae84313) | Aug 04, 2023 |
| Acer          | TravelMate P614-51-G2       | [33dd52a94f](https://linux-hardware.org/?probe=33dd52a94f) | Aug 03, 2023 |
| Dell          | Precision 3571              | [efa0df50dc](https://linux-hardware.org/?probe=efa0df50dc) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [fc2f2f7f45](https://linux-hardware.org/?probe=fc2f2f7f45) | Aug 02, 2023 |
| Sony          | VPCSB1V9R                   | [8d809c3877](https://linux-hardware.org/?probe=8d809c3877) | Aug 02, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| Acer          | Aspire A317-53              | [3f1af34e1b](https://linux-hardware.org/?probe=3f1af34e1b) | Aug 01, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [37be164783](https://linux-hardware.org/?probe=37be164783) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [e24869945e](https://linux-hardware.org/?probe=e24869945e) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [a2148fe49f](https://linux-hardware.org/?probe=a2148fe49f) | Aug 01, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [5d12cf34ca](https://linux-hardware.org/?probe=5d12cf34ca) | Jul 31, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [ae14da63f3](https://linux-hardware.org/?probe=ae14da63f3) | Jul 30, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [f1db906c7c](https://linux-hardware.org/?probe=f1db906c7c) | Jul 30, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [963eb3c0a8](https://linux-hardware.org/?probe=963eb3c0a8) | Jul 29, 2023 |
| HP            | EliteBook 2540p             | [cb13e61bae](https://linux-hardware.org/?probe=cb13e61bae) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e08f65110d](https://linux-hardware.org/?probe=e08f65110d) | Jul 27, 2023 |
| Google        | Fleex                       | [977fa266d3](https://linux-hardware.org/?probe=977fa266d3) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | [045470ba6d](https://linux-hardware.org/?probe=045470ba6d) | Jul 26, 2023 |
| MSI           | GL73 8RE                    | [7de233f9bd](https://linux-hardware.org/?probe=7de233f9bd) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| ASUSTek       | K53SD                       | [2cd6047230](https://linux-hardware.org/?probe=2cd6047230) | Jul 25, 2023 |
| HP            | ProBook 440 G2              | [85168259e3](https://linux-hardware.org/?probe=85168259e3) | Jul 25, 2023 |
| HP            | 250 G3                      | [5580b343bd](https://linux-hardware.org/?probe=5580b343bd) | Jul 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8b89c63576](https://linux-hardware.org/?probe=8b89c63576) | Jul 24, 2023 |
| MSI           | GL73 8RE                    | [86035a17da](https://linux-hardware.org/?probe=86035a17da) | Jul 24, 2023 |
| Sony          | SVE1713X1EB                 | [f2dfaee237](https://linux-hardware.org/?probe=f2dfaee237) | Jul 23, 2023 |
| Apple         | MacBookPro16,1              | [7f3a5aa8cd](https://linux-hardware.org/?probe=7f3a5aa8cd) | Jul 22, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [2a3971e2fc](https://linux-hardware.org/?probe=2a3971e2fc) | Jul 21, 2023 |
| HP            | 245 G8 Notebook PC          | [788fc0bfc9](https://linux-hardware.org/?probe=788fc0bfc9) | Jul 21, 2023 |
| ASUSTek       | G551JK                      | [fed0cf1fce](https://linux-hardware.org/?probe=fed0cf1fce) | Jul 20, 2023 |
| Acer          | Aspire A515-47              | [9a705d5047](https://linux-hardware.org/?probe=9a705d5047) | Jul 20, 2023 |
| HP            | Pavilion dv6                | [cc73a658d1](https://linux-hardware.org/?probe=cc73a658d1) | Jul 19, 2023 |
| Sony          | SVE1713X1EB                 | [89340a2cf7](https://linux-hardware.org/?probe=89340a2cf7) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [7733ed8a40](https://linux-hardware.org/?probe=7733ed8a40) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [4bba49b11c](https://linux-hardware.org/?probe=4bba49b11c) | Jul 19, 2023 |
| Dell          | XPS 15 9570                 | [e6cf0622b0](https://linux-hardware.org/?probe=e6cf0622b0) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [69a47b22c4](https://linux-hardware.org/?probe=69a47b22c4) | Jul 18, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [ef2395800e](https://linux-hardware.org/?probe=ef2395800e) | Jul 16, 2023 |
| Teclast       | F7 Plus                     | [1c317224d2](https://linux-hardware.org/?probe=1c317224d2) | Jul 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [52870865a4](https://linux-hardware.org/?probe=52870865a4) | Jul 15, 2023 |
| Maibenben     | MaiBook M                   | [44a9f08c5e](https://linux-hardware.org/?probe=44a9f08c5e) | Jul 15, 2023 |
| Notebook      | NH5x_7xRCx,RDx              | [9e8ab59ea8](https://linux-hardware.org/?probe=9e8ab59ea8) | Jul 14, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | [2213337296](https://linux-hardware.org/?probe=2213337296) | Jul 14, 2023 |
| OriginPC      | EVO16-S                     | [f3b1c85a1a](https://linux-hardware.org/?probe=f3b1c85a1a) | Jul 11, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [fddf95e5c8](https://linux-hardware.org/?probe=fddf95e5c8) | Jul 11, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | ThinkPad A275 20KCS08C0K    | [9857dab3ab](https://linux-hardware.org/?probe=9857dab3ab) | Jul 08, 2023 |
| Sony          | SVE1713X1EB                 | [7fde9afaf1](https://linux-hardware.org/?probe=7fde9afaf1) | Jul 08, 2023 |
| Dell          | XPS 15 9530                 | [09ada263c3](https://linux-hardware.org/?probe=09ada263c3) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| ASUSTek       | X455LJ                      | [60c1acd1fc](https://linux-hardware.org/?probe=60c1acd1fc) | Jul 04, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16IAH7 8... | [ad57a8dd50](https://linux-hardware.org/?probe=ad57a8dd50) | Jul 04, 2023 |
| HP            | EliteBook 8770w             | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | [0064c1c269](https://linux-hardware.org/?probe=0064c1c269) | Jul 03, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f9e366002e](https://linux-hardware.org/?probe=f9e366002e) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [c1a241c0a5](https://linux-hardware.org/?probe=c1a241c0a5) | Jul 03, 2023 |
| Dell          | Latitude E5470              | [0a50455c18](https://linux-hardware.org/?probe=0a50455c18) | Jul 02, 2023 |
| Lenovo        | Legion Y9000X IAH7 82TF     | [efb7d0f42a](https://linux-hardware.org/?probe=efb7d0f42a) | Jul 02, 2023 |
| Dell          | XPS L521X                   | [b80baf340c](https://linux-hardware.org/?probe=b80baf340c) | Jul 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [cf9a80fbbc](https://linux-hardware.org/?probe=cf9a80fbbc) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f3cb4dc749](https://linux-hardware.org/?probe=f3cb4dc749) | Jun 29, 2023 |
| eMachines     | eME728                      | [37dc0ef617](https://linux-hardware.org/?probe=37dc0ef617) | Jun 29, 2023 |
| ASUSTek       | X455LJ                      | [c147d5716d](https://linux-hardware.org/?probe=c147d5716d) | Jun 27, 2023 |
| Google        | Sasuke                      | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| Dell          | Inspiron 3583               | [e0f5116d38](https://linux-hardware.org/?probe=e0f5116d38) | Jun 23, 2023 |
| Sony          | SVE1713X1EB                 | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| Apple         | MacBookPro16,2              | [2bcd63ec1e](https://linux-hardware.org/?probe=2bcd63ec1e) | Jun 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| Dell          | Latitude E5570              | [43171e0f19](https://linux-hardware.org/?probe=43171e0f19) | Jun 14, 2023 |
| Sony          | SVE1513B1EW                 | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21a8144a2e](https://linux-hardware.org/?probe=21a8144a2e) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3c7683dfc4](https://linux-hardware.org/?probe=3c7683dfc4) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
| Dell          | Latitude E6510              | [e7c1e59ac7](https://linux-hardware.org/?probe=e7c1e59ac7) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [2f0f8eb596](https://linux-hardware.org/?probe=2f0f8eb596) | Jun 09, 2023 |
| VIT           | P2402                       | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| Dell          | Vostro 1015                 | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [33fb312b6d](https://linux-hardware.org/?probe=33fb312b6d) | Jun 05, 2023 |
| Sony          | SVE1713X1EB                 | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| TUXEDO        | InfinityBook Pro 15 v5      | [1b01df33d2](https://linux-hardware.org/?probe=1b01df33d2) | Jun 03, 2023 |
| HP            | Laptop 15-db0xxx            | [04830d213f](https://linux-hardware.org/?probe=04830d213f) | Jun 03, 2023 |
| Acer          | Aspire E5-575G              | [c4cd05b00f](https://linux-hardware.org/?probe=c4cd05b00f) | Jun 01, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3de415ea72](https://linux-hardware.org/?probe=3de415ea72) | Jun 01, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| ASUSTek       | GL553VD                     | [a1f825f4e5](https://linux-hardware.org/?probe=a1f825f4e5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | [0b04d3bf20](https://linux-hardware.org/?probe=0b04d3bf20) | May 28, 2023 |
| ASUSTek       | X455LF                      | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Aspire E5-575G              | [af33101302](https://linux-hardware.org/?probe=af33101302) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| Acer          | Aspire E5-573G              | [4c22ef876f](https://linux-hardware.org/?probe=4c22ef876f) | May 26, 2023 |
| Apple         | MacBookPro16,2              | [46cb91a74d](https://linux-hardware.org/?probe=46cb91a74d) | May 25, 2023 |
| Dell          | Inspiron 3583               | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | [a48977a871](https://linux-hardware.org/?probe=a48977a871) | May 22, 2023 |
| HP            | Laptop 14s-dk1xxx           | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| HUAWEI        | CREM-WXX9                   | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| ASUSTek       | N56VB                       | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| Acer          | Aspire A315-42G             | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| Dell          | Inspiron 3583               | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Dell          | Inspiron 5577               | [e4bfe14f2d](https://linux-hardware.org/?probe=e4bfe14f2d) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [35d056f8bd](https://linux-hardware.org/?probe=35d056f8bd) | May 11, 2023 |
| ASUSTek       | N56VB                       | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| Lenovo        | G560 0679                   | [a916fc6080](https://linux-hardware.org/?probe=a916fc6080) | May 08, 2023 |
| Timi          | TM1701                      | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| Dell          | Inspiron 5402               | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Lenovo        | ThinkPad W530 24473F2       | [937dddbff0](https://linux-hardware.org/?probe=937dddbff0) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [9984dd7707](https://linux-hardware.org/?probe=9984dd7707) | May 03, 2023 |
| Notebook      | NS5x_NS7xPU                 | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Apple         | MacBookAir7,2               | [1a343a4622](https://linux-hardware.org/?probe=1a343a4622) | Apr 30, 2023 |
| Dell          | Latitude 5580               | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Dell          | Inspiron 15 3520            | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Apple         | MacBookAir7,2               | [c1e0f0fa03](https://linux-hardware.org/?probe=c1e0f0fa03) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f1d5d361d5](https://linux-hardware.org/?probe=f1d5d361d5) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Acer          | Aspire A515-45              | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| Notebook      | NH5x_NH7xHP                 | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Sony          | SVE1713X1EB                 | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| Apple         | MacBookAir7,2               | [17ae2e245a](https://linux-hardware.org/?probe=17ae2e245a) | Apr 22, 2023 |
| Notebook      | W65_W67RB                   | [f34e442b8b](https://linux-hardware.org/?probe=f34e442b8b) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [00f7379c8f](https://linux-hardware.org/?probe=00f7379c8f) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| ASUSTek       | X55A                        | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| HUAWEI        | HLYL-WXX9                   | [8eaac4a62d](https://linux-hardware.org/?probe=8eaac4a62d) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | [47f2ba894b](https://linux-hardware.org/?probe=47f2ba894b) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| Sony          | SVE1713X1EB                 | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Acer          | Aspire E5-575               | [15d7d40bed](https://linux-hardware.org/?probe=15d7d40bed) | Apr 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | [aee22ee8b3](https://linux-hardware.org/?probe=aee22ee8b3) | Apr 08, 2023 |
| HP            | 250 G4                      | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| HP            | Unknown                     | [0af30fd642](https://linux-hardware.org/?probe=0af30fd642) | Apr 06, 2023 |
| Sony          | SVE1713X1EB                 | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [546e8e3742](https://linux-hardware.org/?probe=546e8e3742) | Apr 04, 2023 |
| Dell          | Inspiron 5402               | [5035f094da](https://linux-hardware.org/?probe=5035f094da) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Apple         | MacBookAir6,2               | [d64af320d7](https://linux-hardware.org/?probe=d64af320d7) | Apr 02, 2023 |
| Apple         | MacBookAir6,2               | [3400bd9412](https://linux-hardware.org/?probe=3400bd9412) | Apr 02, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [edb6e927bd](https://linux-hardware.org/?probe=edb6e927bd) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| GPD           | G1621-02                    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [008eb6ad60](https://linux-hardware.org/?probe=008eb6ad60) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4dd142ab8f](https://linux-hardware.org/?probe=4dd142ab8f) | Mar 31, 2023 |
| Sony          | SVE1713X1EB                 | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| AWOW          | AL34                        | [19f60f27c8](https://linux-hardware.org/?probe=19f60f27c8) | Mar 29, 2023 |
| HP            | EliteBook 840 G5            | [65671e15cb](https://linux-hardware.org/?probe=65671e15cb) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| Sony          | SVE1713X1EB                 | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [d80388d7ef](https://linux-hardware.org/?probe=d80388d7ef) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| Samsung       | 550XDA                      | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [18cd806803](https://linux-hardware.org/?probe=18cd806803) | Mar 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | [3042a430c0](https://linux-hardware.org/?probe=3042a430c0) | Mar 24, 2023 |
| HP            | EliteBook 850 G1            | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| GPD           | G1619-04                    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Acer          | Swift SF315-52G             | [f6042580d0](https://linux-hardware.org/?probe=f6042580d0) | Mar 20, 2023 |
| Notebook      | N150ZU                      | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [a911c14f22](https://linux-hardware.org/?probe=a911c14f22) | Mar 19, 2023 |
| Samsung       | 550XDA                      | [5f14b733bb](https://linux-hardware.org/?probe=5f14b733bb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| ASUSTek       | UX301LAA                    | [882d4d095b](https://linux-hardware.org/?probe=882d4d095b) | Mar 18, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| Apple         | MacBookAir5,2               | [ae4d8ba68c](https://linux-hardware.org/?probe=ae4d8ba68c) | Mar 18, 2023 |
| Toshiba       | Satellite C55-C             | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | [066f0cd17b](https://linux-hardware.org/?probe=066f0cd17b) | Mar 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | [b588252431](https://linux-hardware.org/?probe=b588252431) | Mar 14, 2023 |
| Dell          | XPS 15 9520                 | [0f3b7bd317](https://linux-hardware.org/?probe=0f3b7bd317) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7f58d0d0a0](https://linux-hardware.org/?probe=7f58d0d0a0) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0c58b8ebad](https://linux-hardware.org/?probe=0c58b8ebad) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | [fc04961aef](https://linux-hardware.org/?probe=fc04961aef) | Mar 11, 2023 |
| Dell          | Precision 7720              | [6132f690aa](https://linux-hardware.org/?probe=6132f690aa) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [8a33917a89](https://linux-hardware.org/?probe=8a33917a89) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [f4d71dcbd0](https://linux-hardware.org/?probe=f4d71dcbd0) | Mar 09, 2023 |
| Dell          | Precision 7720              | [e4a1149bcb](https://linux-hardware.org/?probe=e4a1149bcb) | Mar 08, 2023 |
| Timi          | TM1701                      | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| HP            | EliteBook 8460p             | [3519073f46](https://linux-hardware.org/?probe=3519073f46) | Mar 07, 2023 |
| Dell          | Latitude 5289               | [dcac5b8ebc](https://linux-hardware.org/?probe=dcac5b8ebc) | Mar 06, 2023 |
| Google        | Rammus                      | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | EliteBook 8460p             | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Lenovo        | Y50-70 20378                | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| Dell          | Inspiron N4010              | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| Medion        | Akoya E6412T                | [2915d1c409](https://linux-hardware.org/?probe=2915d1c409) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| ASUSTek       | X555LA                      | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [6234395029](https://linux-hardware.org/?probe=6234395029) | Feb 18, 2023 |
| Chuwi         | GemiBook Pro                | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| Google        | Helios                      | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| GPD           | G1621-02                    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| HP            | Laptop 15s-fq4xxx           | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM    | [9e0e0bef82](https://linux-hardware.org/?probe=9e0e0bef82) | Feb 13, 2023 |
| Acer          | Aspire A515-54G             | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| HP            | Compaq 6820s                | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [0c6da36f9d](https://linux-hardware.org/?probe=0c6da36f9d) | Feb 11, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [059d515c3c](https://linux-hardware.org/?probe=059d515c3c) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2LN0... | [4fdb5d662c](https://linux-hardware.org/?probe=4fdb5d662c) | Feb 08, 2023 |
| HP            | ZBook 15 G4                 | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| HP            | Setzer                      | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [bcaa2e6b1a](https://linux-hardware.org/?probe=bcaa2e6b1a) | Jan 30, 2023 |
| Dell          | Latitude 5400               | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Toshiba       | Satellite L755              | [b15899ef80](https://linux-hardware.org/?probe=b15899ef80) | Jan 27, 2023 |
| Toshiba       | Satellite L755              | [357a0cd22d](https://linux-hardware.org/?probe=357a0cd22d) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Dell          | Latitude E5410              | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| Google        | Magpie                      | [34506f260e](https://linux-hardware.org/?probe=34506f260e) | Jan 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [56a9b7ad32](https://linux-hardware.org/?probe=56a9b7ad32) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| Dell          | XPS 13 9343                 | [f371c1c8b6](https://linux-hardware.org/?probe=f371c1c8b6) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| Acer          | Aspire E5-575G              | [1153793fd9](https://linux-hardware.org/?probe=1153793fd9) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [8b1ccef51d](https://linux-hardware.org/?probe=8b1ccef51d) | Jan 15, 2023 |
| Acer          | Aspire E5-575G              | [1681bdc38e](https://linux-hardware.org/?probe=1681bdc38e) | Jan 14, 2023 |
| Dell          | Precision M4800             | [c5deb205c7](https://linux-hardware.org/?probe=c5deb205c7) | Jan 14, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [cef6a9db45](https://linux-hardware.org/?probe=cef6a9db45) | Jan 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [8defa5d641](https://linux-hardware.org/?probe=8defa5d641) | Jan 05, 2023 |
| Dell          | XPS 9320                    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [be6730b67b](https://linux-hardware.org/?probe=be6730b67b) | Jan 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [bc57a904f7](https://linux-hardware.org/?probe=bc57a904f7) | Jan 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| Toshiba       | EQUIUM A100                 | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| MSI           | Modern 15 A5M               | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ce45aaceaf](https://linux-hardware.org/?probe=ce45aaceaf) | Dec 29, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| Acer          | Swift SFX14-41G             | [e422b934d0](https://linux-hardware.org/?probe=e422b934d0) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b8099c7a94](https://linux-hardware.org/?probe=b8099c7a94) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | EliteBook 845 14 inch G9... | [475b76e98a](https://linux-hardware.org/?probe=475b76e98a) | Dec 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [244ad65a78](https://linux-hardware.org/?probe=244ad65a78) | Dec 24, 2022 |
| HP            | ProBook 450 G7              | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| Sony          | VGN-FW11E                   | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HP            | 15                          | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [54e81a596c](https://linux-hardware.org/?probe=54e81a596c) | Dec 18, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0a486ca67b](https://linux-hardware.org/?probe=0a486ca67b) | Dec 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [8c87fc340b](https://linux-hardware.org/?probe=8c87fc340b) | Dec 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| PC Special... | Elimina Iv 17               | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [2a1d9a153b](https://linux-hardware.org/?probe=2a1d9a153b) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6ae6d710b7](https://linux-hardware.org/?probe=6ae6d710b7) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b56f450d6d](https://linux-hardware.org/?probe=b56f450d6d) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [ebf5cc9d6e](https://linux-hardware.org/?probe=ebf5cc9d6e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| MSI           | GS75 Stealth 8SG            | [8741c9175e](https://linux-hardware.org/?probe=8741c9175e) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | [c3b6dada9d](https://linux-hardware.org/?probe=c3b6dada9d) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | [70be467762](https://linux-hardware.org/?probe=70be467762) | Dec 01, 2022 |
| Dell          | Inspiron 15-3567            | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| HP            | ENVY 17                     | [4a784f4642](https://linux-hardware.org/?probe=4a784f4642) | Nov 27, 2022 |
| Acer          | Aspire A517-52              | [3ce1a2c42a](https://linux-hardware.org/?probe=3ce1a2c42a) | Nov 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [4e7809f7f6](https://linux-hardware.org/?probe=4e7809f7f6) | Nov 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| Lenovo        | ThinkPad T440s 20ARA12UM... | [5e1b88160e](https://linux-hardware.org/?probe=5e1b88160e) | Nov 25, 2022 |
| Acer          | TravelMate 5730             | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| MSI           | Modern 14 B5M               | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | 15                          | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| Apple         | MacBookPro16,2              | [8c63644200](https://linux-hardware.org/?probe=8c63644200) | Nov 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [7aeba8b69a](https://linux-hardware.org/?probe=7aeba8b69a) | Nov 10, 2022 |
| Acer          | Aspire A315-22              | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AJ00    | [ec16a4b3c5](https://linux-hardware.org/?probe=ec16a4b3c5) | Nov 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fba0c1a99c](https://linux-hardware.org/?probe=fba0c1a99c) | Nov 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [0527a7a983](https://linux-hardware.org/?probe=0527a7a983) | Nov 07, 2022 |
| Lenovo        | ThinkPad T520 42406AG       | [1038487513](https://linux-hardware.org/?probe=1038487513) | Nov 06, 2022 |
| Timi          | RedmiBook Pro 15            | [226d8de9bb](https://linux-hardware.org/?probe=226d8de9bb) | Nov 04, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU    | [9e1b981f01](https://linux-hardware.org/?probe=9e1b981f01) | Nov 03, 2022 |
| MSI           | Prestige 15 A11SCX          | [973b498b3f](https://linux-hardware.org/?probe=973b498b3f) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| MSI           | Prestige 14Evo A12M         | [5e32f7b38b](https://linux-hardware.org/?probe=5e32f7b38b) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [264d164669](https://linux-hardware.org/?probe=264d164669) | Oct 27, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [7e1a95e569](https://linux-hardware.org/?probe=7e1a95e569) | Oct 26, 2022 |
| Acer          | Extensa 2540                | [367660309f](https://linux-hardware.org/?probe=367660309f) | Oct 26, 2022 |
| HP            | 650                         | [d7b73bebc7](https://linux-hardware.org/?probe=d7b73bebc7) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | [95707c7cd5](https://linux-hardware.org/?probe=95707c7cd5) | Oct 25, 2022 |
| Timi          | RedmiBook Pro 14S           | [f81e674faf](https://linux-hardware.org/?probe=f81e674faf) | Oct 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [d6275970a0](https://linux-hardware.org/?probe=d6275970a0) | Oct 21, 2022 |
| HP            | Laptop 15-bs2xx             | [0fd75382e9](https://linux-hardware.org/?probe=0fd75382e9) | Oct 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [facb462239](https://linux-hardware.org/?probe=facb462239) | Oct 20, 2022 |
| MSI           | GE75 Raider 10SF            | [dd4102e2e7](https://linux-hardware.org/?probe=dd4102e2e7) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [5e31cc470c](https://linux-hardware.org/?probe=5e31cc470c) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00fece9d77](https://linux-hardware.org/?probe=00fece9d77) | Oct 18, 2022 |
| ASUSTek       | X441SA                      | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Google        | Liara                       | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| HP            | 340S G7 Notebook PC         | [1927ae6949](https://linux-hardware.org/?probe=1927ae6949) | Oct 12, 2022 |
| Lenovo        | V110-15AST 80TD             | [9d4b6fafb6](https://linux-hardware.org/?probe=9d4b6fafb6) | Oct 12, 2022 |
| ASUSTek       | S550CA                      | [261f171b10](https://linux-hardware.org/?probe=261f171b10) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Acer          | Swift SF314-51              | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | [90c1d12ca3](https://linux-hardware.org/?probe=90c1d12ca3) | Oct 07, 2022 |
| Packard Be... | EasyNote TJ65               | [bb815f037b](https://linux-hardware.org/?probe=bb815f037b) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| HP            | 250 G4                      | [7c892fab7a](https://linux-hardware.org/?probe=7c892fab7a) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | [1a2e047ca1](https://linux-hardware.org/?probe=1a2e047ca1) | Oct 03, 2022 |
| MSI           | GF65 Thin 9SD               | [a761de487d](https://linux-hardware.org/?probe=a761de487d) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| MSI           | Modern 14 B5M               | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| ASUSTek       | GL753VE                     | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| HP            | EliteBook 745 G6            | [f9eecf6781](https://linux-hardware.org/?probe=f9eecf6781) | Sep 28, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [658f9b891f](https://linux-hardware.org/?probe=658f9b891f) | Sep 27, 2022 |
| Apple         | MacBookPro8,1               | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [2b3c66f0ee](https://linux-hardware.org/?probe=2b3c66f0ee) | Sep 24, 2022 |
| HP            | 250 G4                      | [5d4c56fe14](https://linux-hardware.org/?probe=5d4c56fe14) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8e7a7a914c](https://linux-hardware.org/?probe=8e7a7a914c) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [031f4bb4f1](https://linux-hardware.org/?probe=031f4bb4f1) | Sep 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [6f43da7fb4](https://linux-hardware.org/?probe=6f43da7fb4) | Sep 22, 2022 |
| ASUSTek       | GL553VD                     | [e6cb381fd2](https://linux-hardware.org/?probe=e6cb381fd2) | Sep 21, 2022 |
| ASUSTek       | G74Sx                       | [e8f0a018c9](https://linux-hardware.org/?probe=e8f0a018c9) | Sep 19, 2022 |
| Acer          | Aspire A515-41G             | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | [465e8d2c86](https://linux-hardware.org/?probe=465e8d2c86) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| Gigabyte      | AORUS 15G XC                | [4b0e97e947](https://linux-hardware.org/?probe=4b0e97e947) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| MSI           | Alpha 15 B5EEK              | [cf9447ce8c](https://linux-hardware.org/?probe=cf9447ce8c) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Timi          | TM1703                      | [5c30ece6ff](https://linux-hardware.org/?probe=5c30ece6ff) | Sep 08, 2022 |
| HP            | ProBook 450 G0              | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| Timi          | TM1703                      | [fb7386017f](https://linux-hardware.org/?probe=fb7386017f) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [dd3b771e55](https://linux-hardware.org/?probe=dd3b771e55) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e8887916fa](https://linux-hardware.org/?probe=e8887916fa) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [0e4f12b377](https://linux-hardware.org/?probe=0e4f12b377) | Sep 04, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | [2667cd1609](https://linux-hardware.org/?probe=2667cd1609) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [05221c6c18](https://linux-hardware.org/?probe=05221c6c18) | Sep 03, 2022 |
| ASUSTek       | X580VN                      | [fe8f1a7e6f](https://linux-hardware.org/?probe=fe8f1a7e6f) | Sep 03, 2022 |
| HP            | OMEN by Laptop 16z-c000     | [edc4a4ce85](https://linux-hardware.org/?probe=edc4a4ce85) | Sep 03, 2022 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [3a8cfc8781](https://linux-hardware.org/?probe=3a8cfc8781) | Sep 01, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | [94b00f5da5](https://linux-hardware.org/?probe=94b00f5da5) | Aug 27, 2022 |
| Google        | Peppy                       | [be4ecba4dc](https://linux-hardware.org/?probe=be4ecba4dc) | Aug 26, 2022 |
| Google        | Auron_Yuna                  | [de2984c01a](https://linux-hardware.org/?probe=de2984c01a) | Aug 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| HP            | Elite x2 1012 G1            | [94fb37c745](https://linux-hardware.org/?probe=94fb37c745) | Aug 14, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [b391d570ba](https://linux-hardware.org/?probe=b391d570ba) | Aug 12, 2022 |
| Apple         | MacBookPro14,2              | [9e297d5dde](https://linux-hardware.org/?probe=9e297d5dde) | Aug 11, 2022 |
| ASUSTek       | GL502VT                     | [5e95e514a4](https://linux-hardware.org/?probe=5e95e514a4) | Aug 11, 2022 |
| HP            | Elite x2 1012 G1            | [a76e460266](https://linux-hardware.org/?probe=a76e460266) | Aug 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d76760ffa4](https://linux-hardware.org/?probe=d76760ffa4) | Aug 11, 2022 |
| Dell          | Inspiron 5402               | [5373247b06](https://linux-hardware.org/?probe=5373247b06) | Aug 05, 2022 |
| Apple         | MacBookPro14,2              | [d1079f3fba](https://linux-hardware.org/?probe=d1079f3fba) | Aug 04, 2022 |
| Positivo      | S14BW01                     | [28c70dfa85](https://linux-hardware.org/?probe=28c70dfa85) | Aug 04, 2022 |
| HP            | EliteBook 745 G6            | [0bcc9863e3](https://linux-hardware.org/?probe=0bcc9863e3) | Jul 31, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| Acer          | Nitro AN515-43              | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [1a394fdf59](https://linux-hardware.org/?probe=1a394fdf59) | Jul 18, 2022 |
| Lenovo        | ThinkPad E595 20NF001HGE    | [9d3a54dbcf](https://linux-hardware.org/?probe=9d3a54dbcf) | Jul 17, 2022 |
| ASUSTek       | GL753VE                     | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| HP            | Laptop 14-fq1xxx            | [9aa0a38b17](https://linux-hardware.org/?probe=9aa0a38b17) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | [b9b09609b8](https://linux-hardware.org/?probe=b9b09609b8) | Jul 01, 2022 |
| HUAWEI        | MACH-WX9                    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| HONOR         | BBR-WAX9                    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| Lenovo        | V330-14ARR 81B1             | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Acer          | Aspire E5-575G              | [dc04d6eb1a](https://linux-hardware.org/?probe=dc04d6eb1a) | Jun 18, 2022 |
| ASUSTek       | N56VB                       | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| Dell          | Latitude XT                 | [6ca0e5ca92](https://linux-hardware.org/?probe=6ca0e5ca92) | Jun 14, 2022 |
| Dell          | Latitude E6440              | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| Acer          | Aspire A515-43              | [343315ec17](https://linux-hardware.org/?probe=343315ec17) | Jun 06, 2022 |
| ASUSTek       | GL753VE                     | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| Dell          | Latitude 5289               | [f9e3e0fa57](https://linux-hardware.org/?probe=f9e3e0fa57) | May 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| Sony          | VPCCA17FX                   | [4ced9d5222](https://linux-hardware.org/?probe=4ced9d5222) | May 26, 2022 |
| Dell          | Latitude E6510              | [52b94e68a9](https://linux-hardware.org/?probe=52b94e68a9) | May 23, 2022 |
| Timi          | A35S                        | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | [c4e15012d5](https://linux-hardware.org/?probe=c4e15012d5) | May 15, 2022 |
| Dell          | Inspiron 3580               | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [5dea5cd6ff](https://linux-hardware.org/?probe=5dea5cd6ff) | May 14, 2022 |
| HP            | Notebook                    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| Unknown       | Unknown                     | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Nitro AN515-45              | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | ProBook 440 G4              | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| Chuwi         | GemiBook Pro                | [b5145fe094](https://linux-hardware.org/?probe=b5145fe094) | May 08, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [6a3cbcae26](https://linux-hardware.org/?probe=6a3cbcae26) | May 06, 2022 |
| Acer          | Swift SF314-41              | [3dbf93ec7f](https://linux-hardware.org/?probe=3dbf93ec7f) | May 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| ASUSTek       | X71Vn                       | [b31a7dce8b](https://linux-hardware.org/?probe=b31a7dce8b) | Apr 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| HUAWEI        | MACH-WX9                    | [0199a1bcec](https://linux-hardware.org/?probe=0199a1bcec) | Apr 24, 2022 |
| Dell          | Latitude 7280               | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Google        | Celes                       | [a1a2262b88](https://linux-hardware.org/?probe=a1a2262b88) | Apr 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [5a58c1f799](https://linux-hardware.org/?probe=5a58c1f799) | Apr 18, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [10a97e42a3](https://linux-hardware.org/?probe=10a97e42a3) | Apr 17, 2022 |
| Google        | Candy                       | [77b6731597](https://linux-hardware.org/?probe=77b6731597) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | [2b3ac63766](https://linux-hardware.org/?probe=2b3ac63766) | Apr 16, 2022 |
| HP            | Laptop 14-dq4xxx            | [a892a2412c](https://linux-hardware.org/?probe=a892a2412c) | Apr 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8350598ef6](https://linux-hardware.org/?probe=8350598ef6) | Apr 15, 2022 |
| Dell          | Latitude E6540              | [939dbc38d3](https://linux-hardware.org/?probe=939dbc38d3) | Apr 15, 2022 |
| HP            | Pavilion Notebook           | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| Acer          | Swift SF314-57G             | [b9b31b0528](https://linux-hardware.org/?probe=b9b31b0528) | Apr 14, 2022 |
| Dell          | XPS 15 7590                 | [d90283da2d](https://linux-hardware.org/?probe=d90283da2d) | Apr 13, 2022 |
| MSI           | Modern 15 A11M              | [c3202f68fc](https://linux-hardware.org/?probe=c3202f68fc) | Apr 13, 2022 |
| ILLEGEAR      | ROGUE                       | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| TrekStor      | Notebook Slim S130          | [febbb5b9a2](https://linux-hardware.org/?probe=febbb5b9a2) | Apr 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [3327822265](https://linux-hardware.org/?probe=3327822265) | Apr 06, 2022 |
| HP            | 250 G7 Notebook PC          | [9170392920](https://linux-hardware.org/?probe=9170392920) | Apr 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [376167460b](https://linux-hardware.org/?probe=376167460b) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [ee491ed7f4](https://linux-hardware.org/?probe=ee491ed7f4) | Mar 29, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [921004463e](https://linux-hardware.org/?probe=921004463e) | Mar 23, 2022 |
| HP            | Laptop 15-bw0xx             | [3500cd92bf](https://linux-hardware.org/?probe=3500cd92bf) | Mar 19, 2022 |
| Acer          | Extensa 2520                | [f070f33060](https://linux-hardware.org/?probe=f070f33060) | Mar 19, 2022 |
| Acer          | Extensa 2520                | [f2003c1f90](https://linux-hardware.org/?probe=f2003c1f90) | Mar 19, 2022 |
| ASUSTek       | G752VT                      | [632814d6a3](https://linux-hardware.org/?probe=632814d6a3) | Mar 18, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [7e64ef177c](https://linux-hardware.org/?probe=7e64ef177c) | Mar 18, 2022 |
| Lenovo        | V330-14IKB 81B0             | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d742a1c2fa](https://linux-hardware.org/?probe=d742a1c2fa) | Mar 16, 2022 |
| Toshiba       | Satellite Pro C50-A-1E6     | [ad8e612da5](https://linux-hardware.org/?probe=ad8e612da5) | Mar 15, 2022 |
| Google        | Akemi                       | [6a52c103e9](https://linux-hardware.org/?probe=6a52c103e9) | Mar 14, 2022 |
| Dell          | Precision M6800             | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| ASUSTek       | G751JT                      | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| Unknown       | Unknown                     | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Acer          | Aspire E5-575               | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Dell          | Latitude E5430 non-vPro     | [2d2bd57c8b](https://linux-hardware.org/?probe=2d2bd57c8b) | Mar 06, 2022 |
| HP            | ZBook 17 G2                 | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d3cc5d36be](https://linux-hardware.org/?probe=d3cc5d36be) | Feb 27, 2022 |
| Eluktronic... | Prometheus XVII             | [0797cebf2d](https://linux-hardware.org/?probe=0797cebf2d) | Feb 26, 2022 |
| Dell          | Latitude 3420               | [fb586744c3](https://linux-hardware.org/?probe=fb586744c3) | Feb 22, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [655c17b9ff](https://linux-hardware.org/?probe=655c17b9ff) | Feb 20, 2022 |
| Radxa         | ROCK Pi X v1.4              | [dd6d9dc630](https://linux-hardware.org/?probe=dd6d9dc630) | Feb 19, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [973e1c8d91](https://linux-hardware.org/?probe=973e1c8d91) | Feb 19, 2022 |
| Acer          | Aspire E1-572G              | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d98a594e28](https://linux-hardware.org/?probe=d98a594e28) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Eluktronic... | Prometheus XVII             | [36436d1aff](https://linux-hardware.org/?probe=36436d1aff) | Feb 17, 2022 |
| HUAWEI        | HLYL-WXX9                   | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| ASUSTek       | UX490UA                     | [5e40078555](https://linux-hardware.org/?probe=5e40078555) | Feb 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [f84892675f](https://linux-hardware.org/?probe=f84892675f) | Feb 12, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [dda932e1ae](https://linux-hardware.org/?probe=dda932e1ae) | Feb 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [c79fe1743d](https://linux-hardware.org/?probe=c79fe1743d) | Feb 10, 2022 |
| Dell          | G3 3500                     | [92ee625013](https://linux-hardware.org/?probe=92ee625013) | Feb 09, 2022 |
| HP            | Pavilion 10 TS              | [1228be8404](https://linux-hardware.org/?probe=1228be8404) | Feb 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [f2719a9d26](https://linux-hardware.org/?probe=f2719a9d26) | Feb 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Dell          | Latitude E4310              | [ef92697af7](https://linux-hardware.org/?probe=ef92697af7) | Feb 07, 2022 |
| Dell          | Latitude E6400              | [919eb44cc5](https://linux-hardware.org/?probe=919eb44cc5) | Feb 07, 2022 |
| Acer          | Aspire V5-471               | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| HP            | Pavilion dv7                | [28bb1241de](https://linux-hardware.org/?probe=28bb1241de) | Feb 06, 2022 |
| Notebook      | NH5x_7xDPx                  | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| HUAWEI        | MACH-WX9                    | [4998bf6630](https://linux-hardware.org/?probe=4998bf6630) | Feb 02, 2022 |
| HP            | Pavilion g6                 | [c2b7d7cdd1](https://linux-hardware.org/?probe=c2b7d7cdd1) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| HP            | 250 G7 Notebook PC          | [b8f0614b9c](https://linux-hardware.org/?probe=b8f0614b9c) | Feb 01, 2022 |
| HP            | Pavilion g6                 | [be25fc4f46](https://linux-hardware.org/?probe=be25fc4f46) | Feb 01, 2022 |
| Lenovo        | Yoga 700-14ISK 80QD         | [de0d67e8c4](https://linux-hardware.org/?probe=de0d67e8c4) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| Dell          | Inspiron 3542               | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [cc0c86531b](https://linux-hardware.org/?probe=cc0c86531b) | Jan 22, 2022 |
| ASUSTek       | K45VD                       | [206ce8c174](https://linux-hardware.org/?probe=206ce8c174) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | [6eafcfd89d](https://linux-hardware.org/?probe=6eafcfd89d) | Jan 18, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Acer          | Swift SF514-54T             | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| HUAWEI        | MACH-WX9                    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| HUAWEI        | MACH-WX9                    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [568c503df0](https://linux-hardware.org/?probe=568c503df0) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb627691ce](https://linux-hardware.org/?probe=fb627691ce) | Jan 07, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c22ba841f6](https://linux-hardware.org/?probe=c22ba841f6) | Jan 06, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [be129c3a7a](https://linux-hardware.org/?probe=be129c3a7a) | Jan 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| MSI           | GP66 Leopard 10UH           | [e9689e292c](https://linux-hardware.org/?probe=e9689e292c) | Jan 05, 2022 |
| Dell          | Inspiron 5520               | [5ce6cac5cb](https://linux-hardware.org/?probe=5ce6cac5cb) | Jan 04, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [c10faa4e15](https://linux-hardware.org/?probe=c10faa4e15) | Jan 04, 2022 |
| ASUSTek       | N43SL                       | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| Timi          | A35S                        | [2dafd53d09](https://linux-hardware.org/?probe=2dafd53d09) | Jan 04, 2022 |
| HP            | EliteBook 2540p             | [12ce36d52f](https://linux-hardware.org/?probe=12ce36d52f) | Jan 03, 2022 |
| Acer          | Aspire A315-56              | [2edffdea76](https://linux-hardware.org/?probe=2edffdea76) | Jan 03, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/EndeavourOS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 814       | 90.44%  |
| EndeavourOS         | 85        | 9.44%   |
| EndeavourOS 23.1.0  | 1         | 0.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| EndeavourOS | 894       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 6.5.9-arch2-1   | 15        | 1.47%   |
| 6.2.8-arch1-1   | 15        | 1.47%   |
| 6.6.1-arch1-1   | 13        | 1.27%   |
| 6.6.7-arch1-1   | 12        | 1.17%   |
| 6.4.12-arch1-1  | 12        | 1.17%   |
| 6.6.8-arch1-1   | 11        | 1.08%   |
| 6.7.9-arch1-1   | 10        | 0.98%   |
| 6.6.2-arch1-1   | 9         | 0.88%   |
| 6.3.9-arch1-1   | 9         | 0.88%   |
| 6.8.7-arch1-1   | 8         | 0.78%   |
| 6.5.5-arch1-1   | 8         | 0.78%   |
| 6.3.4-arch1-1   | 8         | 0.78%   |
| 6.2.10-arch1-1  | 8         | 0.78%   |
| 5.19.7-arch1-1  | 8         | 0.78%   |
| 5.15.12-arch1-1 | 8         | 0.78%   |
| 6.8.5-arch1-1   | 7         | 0.68%   |
| 6.7.8-arch1-1   | 7         | 0.68%   |
| 6.7.4-arch1-1   | 7         | 0.68%   |
| 6.7.0-arch3-1   | 7         | 0.68%   |
| 6.5.3-arch1-1   | 7         | 0.68%   |
| 6.4.11-arch2-1  | 7         | 0.68%   |
| 6.3.1-arch1-1   | 7         | 0.68%   |
| 6.2.9-arch1-1   | 7         | 0.68%   |
| 6.1.12-arch1-1  | 7         | 0.68%   |
| 5.13.13-arch1-1 | 7         | 0.68%   |
| 6.8.9-arch1-1   | 6         | 0.59%   |
| 6.7.1-arch1-1   | 6         | 0.59%   |
| 6.6.4-arch1-1   | 6         | 0.59%   |
| 6.2.2-arch1-1   | 6         | 0.59%   |
| 6.2.13-arch1-1  | 6         | 0.59%   |
| 6.1.1-arch1-1   | 6         | 0.59%   |
| 6.0.9-arch1-1   | 6         | 0.59%   |
| 6.0.12-arch1-1  | 6         | 0.59%   |
| 6.8.2-arch2-1   | 5         | 0.49%   |
| 6.8.1-arch1-1   | 5         | 0.49%   |
| 6.7.6-arch1-1   | 5         | 0.49%   |
| 6.6.10-arch1-1  | 5         | 0.49%   |
| 6.5.7-arch1-1   | 5         | 0.49%   |
| 6.4.7-arch1-1   | 5         | 0.49%   |
| 6.4.3-arch1-2   | 5         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.5.9   | 18        | 1.76%   |
| 6.6.1   | 17        | 1.66%   |
| 6.2.8   | 16        | 1.56%   |
| 6.4.12  | 14        | 1.37%   |
| 6.3.1   | 14        | 1.37%   |
| 6.8.7   | 12        | 1.17%   |
| 6.6.8   | 12        | 1.17%   |
| 6.6.7   | 12        | 1.17%   |
| 6.4.11  | 12        | 1.17%   |
| 6.6.2   | 11        | 1.08%   |
| 5.15.12 | 11        | 1.08%   |
| 6.7.9   | 10        | 0.98%   |
| 6.7.8   | 10        | 0.98%   |
| 6.7.0   | 10        | 0.98%   |
| 6.5.5   | 10        | 0.98%   |
| 6.3.9   | 10        | 0.98%   |
| 6.3.4   | 10        | 0.98%   |
| 6.1.1   | 10        | 0.98%   |
| 6.0.2   | 10        | 0.98%   |
| 5.19.7  | 10        | 0.98%   |
| 5.13.13 | 10        | 0.98%   |
| 6.7.6   | 9         | 0.88%   |
| 6.4.3   | 9         | 0.88%   |
| 6.4.1   | 9         | 0.88%   |
| 6.1.12  | 9         | 0.88%   |
| 6.0.9   | 9         | 0.88%   |
| 6.8.5   | 8         | 0.78%   |
| 6.7.4   | 8         | 0.78%   |
| 6.7.2   | 8         | 0.78%   |
| 6.4.7   | 8         | 0.78%   |
| 6.2.9   | 8         | 0.78%   |
| 6.2.10  | 8         | 0.78%   |
| 6.0.12  | 8         | 0.78%   |
| 5.15.4  | 8         | 0.78%   |
| 6.7.5   | 7         | 0.68%   |
| 6.6.4   | 7         | 0.68%   |
| 6.6.10  | 7         | 0.68%   |
| 6.5.8   | 7         | 0.68%   |
| 6.5.3   | 7         | 0.68%   |
| 6.2.2   | 7         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 95        | 9.63%   |
| 6.6     | 94        | 9.53%   |
| 5.15    | 71        | 7.2%    |
| 6.7     | 70        | 7.1%    |
| 6.4     | 69        | 7%      |
| 6.2     | 69        | 7%      |
| 6.5     | 62        | 6.29%   |
| 6.3     | 52        | 5.27%   |
| 5.19    | 52        | 5.27%   |
| 6.8     | 47        | 4.77%   |
| 6.0     | 47        | 4.77%   |
| 5.16    | 37        | 3.75%   |
| 5.14    | 30        | 3.04%   |
| 5.17    | 29        | 2.94%   |
| 5.18    | 24        | 2.43%   |
| 5.13    | 24        | 2.43%   |
| 5.12    | 24        | 2.43%   |
| 5.9     | 21        | 2.13%   |
| 5.11    | 21        | 2.13%   |
| 5.10    | 20        | 2.03%   |
| 5.8     | 9         | 0.91%   |
| 5.7     | 8         | 0.81%   |
| 5.4     | 6         | 0.61%   |
| 5.6     | 2         | 0.2%    |
| 4.19    | 2         | 0.2%    |
| 5.17.1  | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 893       | 99.89%  |
| aarch64 | 1         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 325       | 35.21%  |
| GNOME           | 216       | 23.4%   |
| XFCE            | 154       | 16.68%  |
| i3              | 35        | 3.79%   |
| KDE6            | 25        | 2.71%   |
| KDE             | 25        | 2.71%   |
| X-Cinnamon      | 24        | 2.6%    |
| Budgie          | 21        | 2.28%   |
| Unknown         | 20        | 2.17%   |
| Hyprland        | 16        | 1.73%   |
| sway            | 12        | 1.3%    |
| MATE            | 12        | 1.3%    |
| Cinnamon        | 7         | 0.76%   |
| LXQt            | 5         | 0.54%   |
| awesome         | 4         | 0.43%   |
| qtile           | 3         | 0.33%   |
| openbox         | 3         | 0.33%   |
| GNOME Flashback | 3         | 0.33%   |
| bspwm           | 3         | 0.33%   |
| LXDE            | 2         | 0.22%   |
| Deepin          | 2         | 0.22%   |
| xmonad          | 1         | 0.11%   |
| wayfire         | 1         | 0.11%   |
| niri            | 1         | 0.11%   |
| LeftWM          | 1         | 0.11%   |
| GNOME Classic   | 1         | 0.11%   |
| dwm             | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 597       | 65.32%  |
| Wayland | 268       | 29.32%  |
| Tty     | 30        | 3.28%   |
| Unknown | 19        | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 277       | 30.24%  |
| SDDM    | 266       | 29.04%  |
| Unknown | 220       | 24.02%  |
| GDM     | 121       | 13.21%  |
| TDM     | 26        | 2.84%   |
| GREETD  | 3         | 0.33%   |
| LY-DM   | 2         | 0.22%   |
| LEMURS  | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 452       | 50.28%  |
| en_GB   | 71        | 7.9%    |
| it_IT   | 69        | 7.68%   |
| de_DE   | 41        | 4.56%   |
| en_CA   | 31        | 3.45%   |
| en_IN   | 25        | 2.78%   |
| ru_RU   | 24        | 2.67%   |
| fr_FR   | 20        | 2.22%   |
| es_ES   | 13        | 1.45%   |
| pl_PL   | 12        | 1.33%   |
| en_AU   | 12        | 1.33%   |
| tr_TR   | 11        | 1.22%   |
| pt_BR   | 11        | 1.22%   |
| Unknown | 11        | 1.22%   |
| nl_NL   | 8         | 0.89%   |
| es_MX   | 7         | 0.78%   |
| fi_FI   | 6         | 0.67%   |
| es_AR   | 6         | 0.67%   |
| en_PH   | 6         | 0.67%   |
| en_NZ   | 6         | 0.67%   |
| sv_SE   | 5         | 0.56%   |
| en_DK   | 4         | 0.44%   |
| de_AT   | 4         | 0.44%   |
| zh_CN   | 3         | 0.33%   |
| pt_PT   | 3         | 0.33%   |
| es_CL   | 3         | 0.33%   |
| ru_UA   | 2         | 0.22%   |
| hu_HU   | 2         | 0.22%   |
| en_ZA   | 2         | 0.22%   |
| en_SG   | 2         | 0.22%   |
| en_IL   | 2         | 0.22%   |
| en_HK   | 2         | 0.22%   |
| en_AG   | 2         | 0.22%   |
| cs_CZ   | 2         | 0.22%   |
| uk_UA   | 1         | 0.11%   |
| sr_RS   | 1         | 0.11%   |
| nl_BE   | 1         | 0.11%   |
| nb_NO   | 1         | 0.11%   |
| ko_KR   | 1         | 0.11%   |
| id_ID   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 600       | 66.3%   |
| BIOS | 305       | 33.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 627       | 69.44%  |
| Btrfs   | 224       | 24.81%  |
| Overlay | 25        | 2.77%   |
| Xfs     | 12        | 1.33%   |
| Tmpfs   | 10        | 1.11%   |
| F2fs    | 2         | 0.22%   |
| Zfs     | 1         | 0.11%   |
| Ext2    | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 627       | 69.44%  |
| Unknown | 213       | 23.59%  |
| MBR     | 63        | 6.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 800       | 88.69%  |
| Yes       | 102       | 11.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 642       | 70.78%  |
| Yes       | 265       | 29.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 243       | 27.18%  |
| ASUSTek Computer        | 149       | 16.67%  |
| Hewlett-Packard         | 135       | 15.1%   |
| Dell                    | 104       | 11.63%  |
| Acer                    | 64        | 7.16%   |
| MSI                     | 36        | 4.03%   |
| Apple                   | 25        | 2.8%    |
| HUAWEI                  | 17        | 1.9%    |
| Google                  | 13        | 1.45%   |
| Timi                    | 11        | 1.23%   |
| Toshiba                 | 10        | 1.12%   |
| TUXEDO                  | 7         | 0.78%   |
| Notebook                | 7         | 0.78%   |
| Sony                    | 6         | 0.67%   |
| Samsung Electronics     | 5         | 0.56%   |
| Schenker                | 4         | 0.45%   |
| Gigabyte Technology     | 4         | 0.45%   |
| Alienware               | 4         | 0.45%   |
| Unknown                 | 4         | 0.45%   |
| Razer                   | 3         | 0.34%   |
| Packard Bell            | 3         | 0.34%   |
| GPD                     | 3         | 0.34%   |
| Chuwi                   | 3         | 0.34%   |
| TrekStor                | 2         | 0.22%   |
| System76                | 2         | 0.22%   |
| Positivo                | 2         | 0.22%   |
| PC Specialist           | 2         | 0.22%   |
| Fujitsu                 | 2         | 0.22%   |
| Framework               | 2         | 0.22%   |
| XIAOMI                  | 1         | 0.11%   |
| VIT                     | 1         | 0.11%   |
| Universal Exports Group | 1         | 0.11%   |
| Teclast                 | 1         | 0.11%   |
| Shinelon Computer       | 1         | 0.11%   |
| Radxa                   | 1         | 0.11%   |
| Pine Microsystems       | 1         | 0.11%   |
| OriginPC                | 1         | 0.11%   |
| Monster                 | 1         | 0.11%   |
| Medion                  | 1         | 0.11%   |
| MECHREVO                | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBookAir7,2                   | 7         | 0.78%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 5         | 0.56%   |
| Unknown                               | 5         | 0.56%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 4         | 0.45%   |
| Dell XPS 15 9520                      | 4         | 0.45%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.45%   |
| MSI Modern 14 B5M                     | 3         | 0.34%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.34%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 3         | 0.34%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ      | 3         | 0.34%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.34%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5      | 3         | 0.34%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 3         | 0.34%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.34%   |
| HUAWEI HLYL-WXX9                      | 3         | 0.34%   |
| HP Laptop 15-db0xxx                   | 3         | 0.34%   |
| HP 250 G7 Notebook PC                 | 3         | 0.34%   |
| HP 250 G3                             | 3         | 0.34%   |
| Dell Latitude E6440                   | 3         | 0.34%   |
| Dell Latitude E5470                   | 3         | 0.34%   |
| Dell Inspiron 3583                    | 3         | 0.34%   |
| Dell Inspiron 3542                    | 3         | 0.34%   |
| Apple MacBookPro16,2                  | 3         | 0.34%   |
| Apple MacBookAir6,2                   | 3         | 0.34%   |
| Acer Nitro AN515-54                   | 3         | 0.34%   |
| Acer Aspire E5-575G                   | 3         | 0.34%   |
| TUXEDO Pulse 15 Gen1                  | 2         | 0.22%   |
| Timi TM1701                           | 2         | 0.22%   |
| Timi A35S                             | 2         | 0.22%   |
| System76 Gazelle                      | 2         | 0.22%   |
| Samsung 340XAA/350XAA/550XAA          | 2         | 0.22%   |
| Positivo S14BW01                      | 2         | 0.22%   |
| MSI Prestige 15 A10SC                 | 2         | 0.22%   |
| MSI Modern 15 A5M                     | 2         | 0.22%   |
| MSI Creator Z16 A12UET                | 2         | 0.22%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS    | 2         | 0.22%   |
| Lenovo ThinkPad T14 Gen 3 21CFCTO1WW  | 2         | 0.22%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB  | 2         | 0.22%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000  | 2         | 0.22%   |
| Lenovo ThinkBook 16p Gen 2 20YM       | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 114       | 12.75%  |
| Lenovo IdeaPad        | 65        | 7.27%   |
| ASUS ROG              | 41        | 4.59%   |
| Dell Latitude         | 37        | 4.14%   |
| Acer Aspire           | 33        | 3.69%   |
| Dell Inspiron         | 29        | 3.24%   |
| HP Pavilion           | 28        | 3.13%   |
| ASUS VivoBook         | 28        | 3.13%   |
| Lenovo Legion         | 27        | 3.02%   |
| HP EliteBook          | 25        | 2.8%    |
| HP Laptop             | 17        | 1.9%    |
| Dell XPS              | 16        | 1.79%   |
| ASUS ASUS             | 14        | 1.57%   |
| Lenovo ThinkBook      | 13        | 1.45%   |
| Lenovo Yoga           | 12        | 1.34%   |
| ASUS TUF              | 11        | 1.23%   |
| Acer Swift            | 11        | 1.23%   |
| Dell Precision        | 10        | 1.12%   |
| ASUS Zenbook          | 10        | 1.12%   |
| Acer Nitro            | 10        | 1.12%   |
| MSI Modern            | 9         | 1.01%   |
| HP ProBook            | 9         | 1.01%   |
| Toshiba Satellite     | 8         | 0.89%   |
| HP ZBook              | 8         | 0.89%   |
| HP 255                | 7         | 0.78%   |
| HP 250                | 7         | 0.78%   |
| Apple MacBookAir7     | 7         | 0.78%   |
| HP ENVY               | 6         | 0.67%   |
| MSI Prestige          | 5         | 0.56%   |
| HP Victus             | 5         | 0.56%   |
| HP OMEN               | 5         | 0.56%   |
| Apple MacBookPro16    | 5         | 0.56%   |
| Unknown               | 5         | 0.56%   |
| Schenker XMG          | 4         | 0.45%   |
| Dell G3               | 4         | 0.45%   |
| Acer TravelMate       | 4         | 0.45%   |
| Acer Extensa          | 4         | 0.45%   |
| TUXEDO Pulse          | 3         | 0.34%   |
| Razer Blade           | 3         | 0.34%   |
| Packard Bell EasyNote | 3         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 136       | 15.21%  |
| 2020    | 115       | 12.86%  |
| 2022    | 100       | 11.19%  |
| 2019    | 90        | 10.07%  |
| 2018    | 77        | 8.61%   |
| 2017    | 59        | 6.6%    |
| 2023    | 47        | 5.26%   |
| 2013    | 44        | 4.92%   |
| 2016    | 43        | 4.81%   |
| 2015    | 37        | 4.14%   |
| 2014    | 35        | 3.91%   |
| 2012    | 33        | 3.69%   |
| 2011    | 22        | 2.46%   |
| 2008    | 15        | 1.68%   |
| 2010    | 14        | 1.57%   |
| 2007    | 13        | 1.45%   |
| 2009    | 9         | 1.01%   |
| 2024    | 4         | 0.45%   |
| Unknown | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 894       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 893       | 99.89%  |
| Enabled  | 1         | 0.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 877       | 98.1%   |
| Yes  | 17        | 1.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 229       | 25.42%  |
| 8.01-16.0   | 220       | 24.42%  |
| 16.01-24.0  | 195       | 21.64%  |
| 32.01-64.0  | 120       | 13.32%  |
| 3.01-4.0    | 80        | 8.88%   |
| 24.01-32.0  | 28        | 3.11%   |
| 64.01-256.0 | 22        | 2.44%   |
| 1.01-2.0    | 4         | 0.44%   |
| 2.01-3.0    | 3         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 246       | 25.49%  |
| 2.01-3.0   | 246       | 25.49%  |
| 1.01-2.0   | 186       | 19.27%  |
| 3.01-4.0   | 185       | 19.17%  |
| 8.01-16.0  | 67        | 6.94%   |
| 0.51-1.0   | 25        | 2.59%   |
| 16.01-24.0 | 7         | 0.73%   |
| 0.01-0.5   | 2         | 0.21%   |
| 24.01-32.0 | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 619       | 68.17%  |
| 2      | 254       | 27.97%  |
| 3      | 28        | 3.08%   |
| 4      | 4         | 0.44%   |
| 0      | 2         | 0.22%   |
| 6      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 746       | 83.17%  |
| Yes       | 151       | 16.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 656       | 73.05%  |
| No        | 242       | 26.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 888       | 99.22%  |
| No        | 7         | 0.78%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 824       | 91.66%  |
| No        | 75        | 8.34%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 175       | 19.4%   |
| Italy       | 96        | 10.64%  |
| Germany     | 75        | 8.31%   |
| India       | 35        | 3.88%   |
| Canada      | 34        | 3.77%   |
| Russia      | 29        | 3.22%   |
| UK          | 28        | 3.1%    |
| Poland      | 28        | 3.1%    |
| Netherlands | 27        | 2.99%   |
| France      | 27        | 2.99%   |
| Turkey      | 26        | 2.88%   |
| Brazil      | 23        | 2.55%   |
| Spain       | 19        | 2.11%   |
| Finland     | 16        | 1.77%   |
| Sweden      | 13        | 1.44%   |
| Austria     | 13        | 1.44%   |
| Australia   | 13        | 1.44%   |
| Indonesia   | 11        | 1.22%   |
| Mexico      | 10        | 1.11%   |
| Argentina   | 9         | 1%      |
| Switzerland | 8         | 0.89%   |
| Romania     | 8         | 0.89%   |
| Vietnam     | 7         | 0.78%   |
| New Zealand | 7         | 0.78%   |
| Hungary     | 7         | 0.78%   |
| Czechia     | 7         | 0.78%   |
| Bangladesh  | 7         | 0.78%   |
| Ukraine     | 6         | 0.67%   |
| Philippines | 6         | 0.67%   |
| Colombia    | 6         | 0.67%   |
| Slovakia    | 5         | 0.55%   |
| Portugal    | 5         | 0.55%   |
| Norway      | 5         | 0.55%   |
| Greece      | 5         | 0.55%   |
| Denmark     | 5         | 0.55%   |
| Belgium     | 5         | 0.55%   |
| Taiwan      | 4         | 0.44%   |
| Serbia      | 4         | 0.44%   |
| Malaysia    | 4         | 0.44%   |
| Kazakhstan  | 4         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Milan             | 13        | 1.38%   |
| Helsinki          | 11        | 1.17%   |
| Istanbul          | 10        | 1.06%   |
| Berlin            | 9         | 0.95%   |
| St Petersburg     | 8         | 0.85%   |
| Rome              | 8         | 0.85%   |
| Amsterdam         | 8         | 0.85%   |
| Warsaw            | 7         | 0.74%   |
| Vienna            | 7         | 0.74%   |
| Toms River        | 7         | 0.74%   |
| Moscow            | 7         | 0.74%   |
| Montreal          | 7         | 0.74%   |
| Hyderabad         | 7         | 0.74%   |
| Sydney            | 6         | 0.64%   |
| Mesa              | 6         | 0.64%   |
| Mannheim          | 6         | 0.64%   |
| Frankfurt am Main | 6         | 0.64%   |
| Florence          | 6         | 0.64%   |
| Delhi             | 6         | 0.64%   |
| Victoria          | 5         | 0.53%   |
| Prague            | 5         | 0.53%   |
| Portland          | 5         | 0.53%   |
| Milano            | 5         | 0.53%   |
| Barberton         | 5         | 0.53%   |
| Turin             | 4         | 0.42%   |
| Rotterdam         | 4         | 0.42%   |
| Poznan            | 4         | 0.42%   |
| Paris             | 4         | 0.42%   |
| Melbourne         | 4         | 0.42%   |
| London            | 4         | 0.42%   |
| Hamburg           | 4         | 0.42%   |
| Dhaka             | 4         | 0.42%   |
| Budapest          | 4         | 0.42%   |
| Belgrade          | 4         | 0.42%   |
| Auckland          | 4         | 0.42%   |
| Zurich            | 3         | 0.32%   |
| Wroclaw           | 3         | 0.32%   |
| Singapore         | 3         | 0.32%   |
| Palermo           | 3         | 0.32%   |
| Naples            | 3         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 267       | 350    | 22.63%  |
| Sandisk                        | 109       | 125    | 9.24%   |
| Seagate                        | 81        | 90     | 6.86%   |
| SK hynix                       | 73        | 88     | 6.19%   |
| WDC                            | 70        | 78     | 5.93%   |
| Kingston                       | 58        | 70     | 4.92%   |
| Micron Technology              | 55        | 62     | 4.66%   |
| Unknown                        | 42        | 51     | 3.56%   |
| Toshiba                        | 36        | 43     | 3.05%   |
| Intel                          | 36        | 39     | 3.05%   |
| Crucial                        | 33        | 41     | 2.8%    |
| KIOXIA                         | 25        | 26     | 2.12%   |
| HGST                           | 22        | 27     | 1.86%   |
| Apple                          | 21        | 26     | 1.78%   |
| Kingston Technology Company    | 17        | 19     | 1.44%   |
| Phison Electronics             | 16        | 17     | 1.36%   |
| Micron/Crucial Technology      | 14        | 17     | 1.19%   |
| A-DATA Technology              | 13        | 15     | 1.1%    |
| MAXIO Technology (Hangzhou)    | 10        | 10     | 0.85%   |
| Hitachi                        | 9         | 9      | 0.76%   |
| Phison                         | 8         | 8      | 0.68%   |
| Silicon Motion                 | 7         | 7      | 0.59%   |
| LITEONIT                       | 7         | 8      | 0.59%   |
| China                          | 7         | 7      | 0.59%   |
| Shenzhen Longsys Electronics   | 6         | 8      | 0.51%   |
| Union Memory (Shenzhen)        | 5         | 5      | 0.42%   |
| Patriot                        | 5         | 5      | 0.42%   |
| KingSpec                       | 5         | 5      | 0.42%   |
| Transcend                      | 4         | 4      | 0.34%   |
| Solid State Storage Technology | 4         | 7      | 0.34%   |
| Realtek Semiconductor          | 4         | 4      | 0.34%   |
| OCZ                            | 4         | 4      | 0.34%   |
| Mushkin                        | 4         | 4      | 0.34%   |
| Lenovo                         | 4         | 4      | 0.34%   |
| JMicron Technology             | 4         | 4      | 0.34%   |
| Yangtze Memory Technologies    | 3         | 3      | 0.25%   |
| SSSTC                          | 3         | 3      | 0.25%   |
| SPCC                           | 3         | 3      | 0.25%   |
| Solid State Storage            | 3         | 5      | 0.25%   |
| Realtek                        | 3         | 5      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 43        | 3.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 39        | 3.19%   |
| Seagate ST1000LM035-1RK172 1TB                        | 20        | 1.64%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                    | 16        | 1.31%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 14        | 1.15%   |
| Kingston SA400S37240G 240GB SSD                       | 12        | 0.98%   |
| Samsung SSD 980 1TB                                   | 10        | 0.82%   |
| HGST HTS721010A9E630 1TB                              | 10        | 0.82%   |
| Unknown MMC Card  64GB                                | 9         | 0.74%   |
| Samsung MZALQ512HBLU-00BL2 512GB                      | 9         | 0.74%   |
| SK hynix HFM001TD3JX013N 1024GB                       | 8         | 0.66%   |
| Seagate ST500LT012-1DG142 500GB                       | 8         | 0.66%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB       | 8         | 0.66%   |
| Samsung MZVLQ512HBLU-00B00 512GB                      | 8         | 0.66%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB    | 8         | 0.66%   |
| Intel SSD 660P Series 1024GB                          | 8         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 7         | 0.57%   |
| Samsung SSD 980 500GB                                 | 7         | 0.57%   |
| Samsung SSD 870 QVO 1TB                               | 7         | 0.57%   |
| Kingston SA400S37480G 480GB SSD                       | 7         | 0.57%   |
| Kingston OM8PCP3512F-AI1 512GB                        | 7         | 0.57%   |
| Intel SSDPEKNU512GZ 512GB                             | 7         | 0.57%   |
| Crucial CT240BX500SSD1 240GB                          | 7         | 0.57%   |
| Unknown MMC Card  32GB                                | 6         | 0.49%   |
| Unknown MMC Card  16GB                                | 6         | 0.49%   |
| Unknown MMC Card  128GB                               | 6         | 0.49%   |
| Toshiba MQ01ABD100 1TB                                | 6         | 0.49%   |
| Seagate ST1000LM049-2GH172 1TB                        | 6         | 0.49%   |
| Sandisk WD Black SN850 512GB                          | 6         | 0.49%   |
| Samsung SSD 860 EVO 500GB                             | 6         | 0.49%   |
| Samsung NVMe SSD Drive 512GB                          | 6         | 0.49%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 6         | 0.49%   |
| Micron 2400_MTFDKBA512QFM 512GB                       | 6         | 0.49%   |
| Apple SSD SM0128G 121GB                               | 6         | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 5         | 0.41%   |
| Samsung SSD 970 EVO 500GB                             | 5         | 0.41%   |
| Samsung SSD 870 EVO 250GB                             | 5         | 0.41%   |
| Samsung SSD 860 EVO 250GB                             | 5         | 0.41%   |
| Samsung SSD 860 EVO 1TB                               | 5         | 0.41%   |
| Samsung SSD 850 EVO 500GB                             | 5         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 74        | 82     | 42.53%  |
| WDC                 | 39        | 42     | 22.41%  |
| HGST                | 22        | 27     | 12.64%  |
| Toshiba             | 16        | 17     | 9.2%    |
| Hitachi             | 9         | 9      | 5.17%   |
| Fujitsu             | 3         | 3      | 1.72%   |
| Unknown             | 2         | 2      | 1.15%   |
| SABRENT             | 2         | 2      | 1.15%   |
| Maxone              | 2         | 2      | 1.15%   |
| JMicron Technology  | 2         | 2      | 1.15%   |
| Samsung Electronics | 1         | 1      | 0.57%   |
| Generic-            | 1         | 1      | 0.57%   |
| ASMT                | 1         | 2      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 91        | 123    | 26.22%  |
| Kingston            | 34        | 40     | 9.8%    |
| Crucial             | 30        | 37     | 8.65%   |
| SanDisk             | 21        | 22     | 6.05%   |
| WDC                 | 20        | 24     | 5.76%   |
| SK hynix            | 13        | 18     | 3.75%   |
| Apple               | 12        | 12     | 3.46%   |
| Micron Technology   | 10        | 11     | 2.88%   |
| A-DATA Technology   | 10        | 11     | 2.88%   |
| LITEONIT            | 7         | 8      | 2.02%   |
| China               | 7         | 7      | 2.02%   |
| Toshiba             | 6         | 6      | 1.73%   |
| KingSpec            | 5         | 5      | 1.44%   |
| Intel               | 5         | 5      | 1.44%   |
| Transcend           | 4         | 4      | 1.15%   |
| Seagate             | 4         | 4      | 1.15%   |
| Patriot             | 4         | 4      | 1.15%   |
| OCZ                 | 4         | 4      | 1.15%   |
| SPCC                | 3         | 3      | 0.86%   |
| Mushkin             | 3         | 3      | 0.86%   |
| KingFast            | 3         | 3      | 0.86%   |
| GOODRAM             | 3         | 3      | 0.86%   |
| Gigabyte Technology | 3         | 4      | 0.86%   |
| Corsair             | 3         | 3      | 0.86%   |
| WDC WDS             | 2         | 2      | 0.58%   |
| Teclast             | 2         | 4      | 0.58%   |
| Team                | 2         | 3      | 0.58%   |
| TAMMUZ              | 2         | 6      | 0.58%   |
| PNY                 | 2         | 3      | 0.58%   |
| Netac               | 2         | 3      | 0.58%   |
| LITEON              | 2         | 3      | 0.58%   |
| Intenso             | 2         | 2      | 0.58%   |
| Hewlett-Packard     | 2         | 2      | 0.58%   |
| Emtec               | 2         | 2      | 0.58%   |
| Zheino              | 1         | 1      | 0.29%   |
| WALTON              | 1         | 2      | 0.29%   |
| V-GeN               | 1         | 1      | 0.29%   |
| USB3.0              | 1         | 1      | 0.29%   |
| Unknown             | 1         | 2      | 0.29%   |
| SUNEAST             | 1         | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 547       | 734    | 50.88%  |
| SSD     | 309       | 418    | 28.74%  |
| HDD     | 170       | 192    | 15.81%  |
| MMC     | 39        | 47     | 3.63%   |
| Unknown | 10        | 10     | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 547       | 725    | 52.29%  |
| SATA | 409       | 564    | 39.1%   |
| SAS  | 51        | 65     | 4.88%   |
| MMC  | 39        | 47     | 3.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 302       | 413    | 63.45%  |
| 0.51-1.0   | 147       | 161    | 30.88%  |
| 1.01-2.0   | 23        | 32     | 4.83%   |
| 10.01-20.0 | 2         | 2      | 0.42%   |
| 3.01-4.0   | 1         | 1      | 0.21%   |
| 4.01-10.0  | 1         | 1      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 204       | 22.01%  |
| 251-500        | 188       | 20.28%  |
| 501-1000       | 147       | 15.86%  |
| 1001-2000      | 127       | 13.7%   |
| 1-20           | 72        | 7.77%   |
| Unknown        | 56        | 6.04%   |
| 51-100         | 45        | 4.85%   |
| More than 3000 | 43        | 4.64%   |
| 2001-3000      | 25        | 2.7%    |
| 21-50          | 20        | 2.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 254       | 26.35%  |
| 101-250        | 173       | 17.95%  |
| 21-50          | 160       | 16.6%   |
| 51-100         | 129       | 13.38%  |
| 251-500        | 84        | 8.71%   |
| 501-1000       | 59        | 6.12%   |
| Unknown        | 56        | 5.81%   |
| 1001-2000      | 33        | 3.42%   |
| More than 3000 | 6         | 0.62%   |
| 0              | 6         | 0.62%   |
| 2001-3000      | 4         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Notebooks | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                                    | 5         | 8      | 7.94%   |
| HGST HTS721010A9E630 1TB                                      | 4         | 4      | 6.35%   |
| Seagate ST1000LM035-1RK172 1TB                                | 2         | 2      | 3.17%   |
| Samsung Electronics SSD 980 1TB                               | 2         | 2      | 3.17%   |
| Hitachi HTS545050A7E380 500GB                                 | 2         | 2      | 3.17%   |
| WDC WD5000LPVT-22G33T0 500GB                                  | 1         | 1      | 1.59%   |
| WDC WD5000BPVT-60HXZT3 500GB                                  | 1         | 1      | 1.59%   |
| WDC WD10SPZX-24Z10T0 1TB                                      | 1         | 1      | 1.59%   |
| WDC WD10SPCX-22HWST0 1TB                                      | 1         | 1      | 1.59%   |
| WDC WD10JPVX-22JC3T0 1TB                                      | 1         | 1      | 1.59%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD                      | 1         | 1      | 1.59%   |
| Transcend TS240GMTS420S 240GB SSD                             | 1         | 1      | 1.59%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD                      | 1         | 1      | 1.59%   |
| Toshiba MQ01ABD100 1TB                                        | 1         | 1      | 1.59%   |
| Toshiba MQ01ABD050 500GB                                      | 1         | 2      | 1.59%   |
| Toshiba MK5055GSXF 500GB                                      | 1         | 1      | 1.59%   |
| Toshiba MK2533GSG 250GB                                       | 1         | 1      | 1.59%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD                       | 1         | 1      | 1.59%   |
| SSSTC CV8-8E128-HP 128GB                                      | 1         | 1      | 1.59%   |
| SK hynix SC308 SATA 128GB SSD                                 | 1         | 1      | 1.59%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB                         | 1         | 1      | 1.59%   |
| SK hynix HFS512G39TND-N210A 512GB SSD                         | 1         | 1      | 1.59%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                         | 1         | 1      | 1.59%   |
| SK hynix HFS128G32TND-N210A 128GB SSD                         | 1         | 1      | 1.59%   |
| SK hynix BC711 HFM001TD3JX013N 1024GB                         | 1         | 1      | 1.59%   |
| Seagate ST9750420AS 752GB                                     | 1         | 1      | 1.59%   |
| Seagate ST9500325AS 500GB                                     | 1         | 1      | 1.59%   |
| Seagate ST9320325AS 320GB                                     | 1         | 1      | 1.59%   |
| Seagate ST500LX012-SSHD-8GB                                   | 1         | 1      | 1.59%   |
| Seagate ST500LT012-1DG142 500GB                               | 1         | 1      | 1.59%   |
| Seagate ST2000LX001-1RG174 2TB                                | 1         | 1      | 1.59%   |
| Seagate ST1000LM049-2GH172 1TB                                | 1         | 1      | 1.59%   |
| SanDisk SSD PLUS 240GB                                        | 1         | 1      | 1.59%   |
| SanDisk SDSSDA120G 120GB                                      | 1         | 1      | 1.59%   |
| SanDisk SD8SNAT128G1002 128GB SSD                             | 1         | 1      | 1.59%   |
| Samsung Electronics SSD 980 500GB                             | 1         | 1      | 1.59%   |
| Samsung Electronics SSD 970 EVO 500GB                         | 1         | 1      | 1.59%   |
| Samsung Electronics SSD 870 EVO 2TB                           | 1         | 1      | 1.59%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 1TB | 1         | 1      | 1.59%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD              | 1         | 1      | 1.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 10        | 13     | 15.87%  |
| Seagate             | 9         | 9      | 14.29%  |
| Samsung Electronics | 7         | 7      | 11.11%  |
| WDC                 | 6         | 6      | 9.52%   |
| Toshiba             | 6         | 7      | 9.52%   |
| SK hynix            | 6         | 6      | 9.52%   |
| SanDisk             | 3         | 3      | 4.76%   |
| Intel               | 2         | 2      | 3.17%   |
| Hitachi             | 2         | 2      | 3.17%   |
| China               | 2         | 2      | 3.17%   |
| Apple               | 2         | 2      | 3.17%   |
| Transcend           | 1         | 1      | 1.59%   |
| SSSTC               | 1         | 1      | 1.59%   |
| Patriot             | 1         | 1      | 1.59%   |
| LITEONIT            | 1         | 1      | 1.59%   |
| Kingston            | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |
| Corsair             | 1         | 1      | 1.59%   |
| A-DATA Technology   | 1         | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 10        | 13     | 32.26%  |
| Seagate | 9         | 9      | 29.03%  |
| WDC     | 5         | 5      | 16.13%  |
| Toshiba | 4         | 5      | 12.9%   |
| Hitachi | 2         | 2      | 6.45%   |
| Fujitsu | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 35     | 49.21%  |
| SSD  | 25        | 25     | 39.68%  |
| NVMe | 7         | 7      | 11.11%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9320320AS 320GB                        | 1         | 1      | 25%     |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 1         | 1      | 25%     |
| LITEON CA3-8D512 512GB                           | 1         | 2      | 25%     |
| JMicron Technology Generic 320GB                 | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 1         | 1      | 25%     |
| Sandisk            | 1         | 1      | 25%     |
| LITEON             | 1         | 2      | 25%     |
| JMicron Technology | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 621       | 908    | 63.82%  |
| Detected | 286       | 421    | 29.39%  |
| Malfunc  | 62        | 67     | 6.37%   |
| Failed   | 4         | 5      | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 476       | 40.1%   |
| Samsung Electronics            | 193       | 16.26%  |
| AMD                            | 115       | 9.69%   |
| SanDisk                        | 97        | 8.17%   |
| SK hynix                       | 59        | 4.97%   |
| Micron Technology              | 45        | 3.79%   |
| Kingston Technology Company    | 40        | 3.37%   |
| KIOXIA                         | 28        | 2.36%   |
| Phison Electronics             | 25        | 2.11%   |
| Micron/Crucial Technology      | 17        | 1.43%   |
| Toshiba America Info Systems   | 11        | 0.93%   |
| MAXIO Technology (Hangzhou)    | 10        | 0.84%   |
| Solid State Storage Technology | 9         | 0.76%   |
| Apple                          | 9         | 0.76%   |
| Silicon Motion                 | 7         | 0.59%   |
| Union Memory (Shenzhen)        | 6         | 0.51%   |
| Shenzhen Longsys Electronics   | 6         | 0.51%   |
| ADATA Technology               | 6         | 0.51%   |
| Realtek Semiconductor          | 4         | 0.34%   |
| Lenovo                         | 4         | 0.34%   |
| Yangtze Memory Technologies    | 3         | 0.25%   |
| Seagate Technology             | 3         | 0.25%   |
| JMicron Technology             | 3         | 0.25%   |
| Marvell Technology Group       | 2         | 0.17%   |
| Lite-On Technology             | 2         | 0.17%   |
| Hosin Global Electronics       | 2         | 0.17%   |
| Solidigm                       | 1         | 0.08%   |
| Nvidia                         | 1         | 0.08%   |
| INNOGRIT                       | 1         | 0.08%   |
| Biwin Storage Technology       | 1         | 0.08%   |
| Unknown                        | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 112       | 8.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 69        | 5.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 64        | 5.14%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 62        | 4.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 42        | 3.37%   |
| Intel Volume Management Device NVMe RAID Controller                            | 41        | 3.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 41        | 3.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 37        | 2.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 35        | 2.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 31        | 2.49%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 30        | 2.41%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 20        | 1.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 20        | 1.61%   |
| Intel Tiger Lake-LP SATA Controller                                            | 20        | 1.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 1.61%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 18        | 1.44%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 18        | 1.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 1.28%   |
| Intel SSD 660P Series                                                          | 15        | 1.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 15        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 1.2%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 14        | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                          | 14        | 1.12%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 12        | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 12        | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 0.88%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 10        | 0.8%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 10        | 0.8%    |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 9         | 0.72%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 9         | 0.72%   |
| Phison E12 NVMe Controller                                                     | 9         | 0.72%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 9         | 0.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 0.72%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 8         | 0.64%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 8         | 0.64%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 8         | 0.64%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 8         | 0.64%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 8         | 0.64%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 8         | 0.64%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 7         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 546       | 47.11%  |
| SATA | 507       | 43.74%  |
| RAID | 92        | 7.94%   |
| IDE  | 14        | 1.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 621       | 69.46%  |
| AMD    | 272       | 30.43%  |
| ARM    | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 20        | 2.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 17        | 1.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 1.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 16        | 1.79%   |
| Intel 12th Gen Core i7-12700H                 | 16        | 1.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 15        | 1.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.57%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 14        | 1.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 13        | 1.45%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 13        | 1.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 11        | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 11        | 1.23%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 11        | 1.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 1.12%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 10        | 1.12%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 1.12%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 10        | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 1.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 1.01%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 1.01%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.89%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 8         | 0.89%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 8         | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 7         | 0.78%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 7         | 0.78%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 7         | 0.78%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 7         | 0.78%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 6         | 0.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.56%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.56%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.56%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 5         | 0.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 196       | 21.92%  |
| Intel Core i7           | 186       | 20.81%  |
| Other                   | 139       | 15.55%  |
| AMD Ryzen 7             | 94        | 10.51%  |
| AMD Ryzen 5             | 78        | 8.72%   |
| Intel Core i3           | 36        | 4.03%   |
| Intel Celeron           | 31        | 3.47%   |
| AMD Ryzen 9             | 29        | 3.24%   |
| AMD Ryzen 7 PRO         | 21        | 2.35%   |
| Intel Core 2 Duo        | 19        | 2.13%   |
| AMD Ryzen 3             | 12        | 1.34%   |
| AMD A4                  | 8         | 0.89%   |
| AMD Ryzen 5 PRO         | 6         | 0.67%   |
| Intel Pentium           | 5         | 0.56%   |
| Intel Xeon              | 3         | 0.34%   |
| Intel Core              | 3         | 0.34%   |
| AMD A8                  | 3         | 0.34%   |
| AMD A10                 | 3         | 0.34%   |
| Intel Core m3           | 2         | 0.22%   |
| Intel Atom              | 2         | 0.22%   |
| AMD E1                  | 2         | 0.22%   |
| AMD E                   | 2         | 0.22%   |
| AMD Athlon              | 2         | 0.22%   |
| Intel Pentium Silver    | 1         | 0.11%   |
| Intel Pentium Dual-Core | 1         | 0.11%   |
| Intel Genuine           | 1         | 0.11%   |
| Intel Core m5           | 1         | 0.11%   |
| Intel Core M            | 1         | 0.11%   |
| Intel Core i9           | 1         | 0.11%   |
| Intel Core 2 Extreme    | 1         | 0.11%   |
| Intel Core 2            | 1         | 0.11%   |
| AMD PRO A10             | 1         | 0.11%   |
| AMD E2                  | 1         | 0.11%   |
| AMD Athlon II           | 1         | 0.11%   |
| AMD A6                  | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 281       | 31.43%  |
| 4      | 280       | 31.32%  |
| 8      | 156       | 17.45%  |
| 6      | 109       | 12.19%  |
| 14     | 28        | 3.13%   |
| 12     | 16        | 1.79%   |
| 10     | 14        | 1.57%   |
| 16     | 5         | 0.56%   |
| 24     | 4         | 0.45%   |
| 1      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 893       | 99.89%  |
| 2      | 1         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 784       | 87.6%   |
| 1      | 111       | 12.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 892       | 99.78%  |
| 64-bit         | 1         | 0.11%   |
| Unknown        | 1         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 486       | 53.17%  |
| 0x0a50000c | 36        | 3.94%   |
| 0x08108109 | 19        | 2.08%   |
| 0x806ec    | 18        | 1.97%   |
| 0x406e3    | 18        | 1.97%   |
| 0x306a9    | 17        | 1.86%   |
| 0x806ea    | 16        | 1.75%   |
| 0x806c1    | 16        | 1.75%   |
| 0x08600106 | 16        | 1.75%   |
| 0x40651    | 15        | 1.64%   |
| 0x806e9    | 14        | 1.53%   |
| 0x0a50000d | 14        | 1.53%   |
| 0x0a404102 | 14        | 1.53%   |
| 0x08600104 | 14        | 1.53%   |
| 0x906ea    | 13        | 1.42%   |
| 0x08608103 | 13        | 1.42%   |
| 0x306c3    | 12        | 1.31%   |
| 0x08108102 | 11        | 1.2%    |
| 0x906a3    | 10        | 1.09%   |
| 0x906e9    | 9         | 0.98%   |
| 0x506e3    | 9         | 0.98%   |
| 0x306d4    | 9         | 0.98%   |
| 0x206a7    | 9         | 0.98%   |
| 0x1067a    | 8         | 0.88%   |
| 0xa0652    | 7         | 0.77%   |
| 0x706e5    | 7         | 0.77%   |
| 0x806d1    | 6         | 0.66%   |
| 0x406c4    | 6         | 0.66%   |
| 0x706a1    | 5         | 0.55%   |
| 0x20655    | 5         | 0.55%   |
| 0x0a404101 | 5         | 0.55%   |
| 0x06006705 | 5         | 0.55%   |
| 0x0a704103 | 3         | 0.33%   |
| 0x08600103 | 3         | 0.33%   |
| 0x06006704 | 3         | 0.33%   |
| 0x0600611a | 3         | 0.33%   |
| 0x906ed    | 2         | 0.22%   |
| 0x906c0    | 2         | 0.22%   |
| 0x806eb    | 2         | 0.22%   |
| 0x706a8    | 2         | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 182       | 20.34%  |
| Unknown           | 100       | 11.17%  |
| Zen 3             | 73        | 8.16%   |
| Haswell           | 56        | 6.26%   |
| Zen 2             | 52        | 5.81%   |
| Skylake           | 51        | 5.7%    |
| Alderlake Hybrid  | 49        | 5.47%   |
| TigerLake         | 47        | 5.25%   |
| Zen+              | 44        | 4.92%   |
| IvyBridge         | 39        | 4.36%   |
| Icelake           | 28        | 3.13%   |
| Broadwell         | 27        | 3.02%   |
| CometLake         | 25        | 2.79%   |
| SandyBridge       | 21        | 2.35%   |
| Penryn            | 17        | 1.9%    |
| Excavator         | 16        | 1.79%   |
| Silvermont        | 14        | 1.56%   |
| Goldmont plus     | 12        | 1.34%   |
| Westmere          | 11        | 1.23%   |
| Jaguar            | 6         | 0.67%   |
| Core              | 6         | 0.67%   |
| Tremont           | 3         | 0.34%   |
| Piledriver        | 3         | 0.34%   |
| Goldmont          | 3         | 0.34%   |
| Zen               | 2         | 0.22%   |
| Puma              | 2         | 0.22%   |
| Meteorlake Hybrid | 2         | 0.22%   |
| Bobcat            | 2         | 0.22%   |
| Nehalem           | 1         | 0.11%   |
| K10               | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 586       | 48.63%  |
| Nvidia | 320       | 26.56%  |
| AMD    | 299       | 24.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 51        | 4.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 47        | 3.8%    |
| Intel UHD Graphics 620                                                                   | 44        | 3.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 3.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 44        | 3.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 40        | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 36        | 2.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 2.75%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 31        | 2.5%    |
| AMD Rembrandt [Radeon 680M]                                                              | 31        | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 2.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 25        | 2.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 25        | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 24        | 1.94%   |
| AMD Lucienne                                                                             | 24        | 1.94%   |
| Intel HD Graphics 620                                                                    | 23        | 1.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 1.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 1.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 1.53%   |
| Intel HD Graphics 5500                                                                   | 19        | 1.53%   |
| AMD Barcelo                                                                              | 19        | 1.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 1.37%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 16        | 1.29%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 15        | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 1.21%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 14        | 1.13%   |
| Intel HD Graphics 630                                                                    | 14        | 1.13%   |
| Intel HD Graphics 530                                                                    | 13        | 1.05%   |
| Nvidia GP108M [GeForce MX150]                                                            | 12        | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 0.97%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 12        | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 0.97%   |
| AMD Phoenix1                                                                             | 12        | 0.97%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 11        | 0.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 0.81%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 9         | 0.73%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.73%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 8         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 329       | 36.76%  |
| Intel + Nvidia | 226       | 25.25%  |
| 1 x AMD        | 188       | 21.01%  |
| AMD + Nvidia   | 62        | 6.93%   |
| 1 x Nvidia     | 31        | 3.46%   |
| 2 x AMD        | 27        | 3.02%   |
| Intel + AMD    | 23        | 2.57%   |
| 2 x Intel      | 7         | 0.78%   |
| Other          | 2         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 663       | 73.67%  |
| Proprietary | 232       | 25.78%  |
| Unknown     | 5         | 0.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 608       | 67.11%  |
| 0.01-0.5   | 114       | 12.58%  |
| 1.01-2.0   | 72        | 7.95%   |
| 3.01-4.0   | 39        | 4.3%    |
| 0.51-1.0   | 26        | 2.87%   |
| 7.01-8.0   | 18        | 1.99%   |
| 5.01-6.0   | 17        | 1.88%   |
| 2.01-3.0   | 7         | 0.77%   |
| 8.01-16.0  | 5         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 207       | 18.9%   |
| BOE                     | 169       | 15.43%  |
| Chimei Innolux          | 160       | 14.61%  |
| LG Display              | 120       | 10.96%  |
| Samsung Electronics     | 88        | 8.04%   |
| PANDA                   | 34        | 3.11%   |
| Dell                    | 30        | 2.74%   |
| Goldstar                | 26        | 2.37%   |
| Sharp                   | 25        | 2.28%   |
| Apple                   | 25        | 2.28%   |
| Lenovo                  | 21        | 1.92%   |
| AOC                     | 17        | 1.55%   |
| Acer                    | 16        | 1.46%   |
| CSO                     | 15        | 1.37%   |
| TMX                     | 12        | 1.1%    |
| InfoVision              | 12        | 1.1%    |
| Philips                 | 11        | 1%      |
| Hewlett-Packard         | 11        | 1%      |
| BenQ                    | 10        | 0.91%   |
| Ancor Communications    | 10        | 0.91%   |
| ASUSTek Computer        | 9         | 0.82%   |
| Iiyama                  | 6         | 0.55%   |
| Chi Mei Optoelectronics | 6         | 0.55%   |
| ViewSonic               | 5         | 0.46%   |
| Pixio                   | 5         | 0.46%   |
| JDI                     | 4         | 0.37%   |
| Gigabyte Technology     | 4         | 0.37%   |
| Toshiba                 | 3         | 0.27%   |
| Sony                    | 3         | 0.27%   |
| MSI                     | 3         | 0.27%   |
| LG Philips              | 3         | 0.27%   |
| Vestel Elektronik       | 2         | 0.18%   |
| InnoLux Display         | 2         | 0.18%   |
| HKC                     | 2         | 0.18%   |
| Vizio                   | 1         | 0.09%   |
| Unknown (XXX)           | 1         | 0.09%   |
| Unknown                 | 1         | 0.09%   |
| TMA                     | 1         | 0.09%   |
| Sun                     | 1         | 0.09%   |
| RTK                     | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 12        | 1.09%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 11        | 1%      |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 9         | 0.82%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 0.72%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 8         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 0.63%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 7         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 6         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.54%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                 | 5         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 5         | 0.45%   |
| Pixio U29I WAM2900 2560x1080 690x260mm 29.0-inch                      | 5         | 0.45%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 5         | 0.45%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 5         | 0.45%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 0.45%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 5         | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 5         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.36%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.36%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.36%   |
| BOE LCD Monitor BOE0A1F 2560x1600 344x215mm 16.0-inch                 | 4         | 0.36%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 4         | 0.36%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch        | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 4         | 0.36%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 4         | 0.36%   |
| TMX TL140ADXP01 TMX1481 2560x1600 301x188mm 14.0-inch                 | 3         | 0.27%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 3         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.27%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 3         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 525       | 51.88%  |
| 1366x768 (WXGA)    | 170       | 16.8%   |
| 2560x1440 (QHD)    | 54        | 5.34%   |
| 2560x1600          | 51        | 5.04%   |
| 3840x2160 (4K)     | 36        | 3.56%   |
| 1920x1200 (WUXGA)  | 29        | 2.87%   |
| 2880x1800          | 22        | 2.17%   |
| 1440x900 (WXGA+)   | 22        | 2.17%   |
| 1600x900 (HD+)     | 11        | 1.09%   |
| 1280x800 (WXGA)    | 11        | 1.09%   |
| 2560x1080          | 10        | 0.99%   |
| 3200x2000          | 8         | 0.79%   |
| 2160x1440          | 8         | 0.79%   |
| 3440x1440          | 7         | 0.69%   |
| 1680x1050 (WSXGA+) | 6         | 0.59%   |
| 3840x2400          | 5         | 0.49%   |
| 1280x1024 (SXGA)   | 5         | 0.49%   |
| 3456x2160          | 4         | 0.4%    |
| 3200x1800 (QHD+)   | 4         | 0.4%    |
| 3072x1920          | 3         | 0.3%    |
| 3000x2000          | 3         | 0.3%    |
| 2240x1400          | 3         | 0.3%    |
| 1360x768           | 3         | 0.3%    |
| 3840x1080          | 2         | 0.2%    |
| 2256x1504          | 2         | 0.2%    |
| 1920x1280          | 2         | 0.2%    |
| Unknown            | 2         | 0.2%    |
| 3840x1100          | 1         | 0.1%    |
| 2520x1680          | 1         | 0.1%    |
| 1920x540           | 1         | 0.1%    |
| 1600x1200          | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 404       | 36.73%  |
| 14      | 158       | 14.36%  |
| 13      | 154       | 14%     |
| 17      | 58        | 5.27%   |
| 16      | 57        | 5.18%   |
| 27      | 50        | 4.55%   |
| 24      | 45        | 4.09%   |
| 23      | 27        | 2.45%   |
| 21      | 22        | 2%      |
| 12      | 20        | 1.82%   |
| 31      | 18        | 1.64%   |
| 11      | 12        | 1.09%   |
| 34      | 8         | 0.73%   |
| 18      | 8         | 0.73%   |
| 19      | 6         | 0.55%   |
| 29      | 5         | 0.45%   |
| 54      | 4         | 0.36%   |
| 40      | 4         | 0.36%   |
| Unknown | 4         | 0.36%   |
| 84      | 3         | 0.27%   |
| 35      | 3         | 0.27%   |
| 20      | 3         | 0.27%   |
| 74      | 2         | 0.18%   |
| 58      | 2         | 0.18%   |
| 49      | 2         | 0.18%   |
| 32      | 2         | 0.18%   |
| 28      | 2         | 0.18%   |
| 25      | 2         | 0.18%   |
| 22      | 2         | 0.18%   |
| 10      | 2         | 0.18%   |
| 86      | 1         | 0.09%   |
| 72      | 1         | 0.09%   |
| 65      | 1         | 0.09%   |
| 57      | 1         | 0.09%   |
| 52      | 1         | 0.09%   |
| 46      | 1         | 0.09%   |
| 42      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 33      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 680       | 62.44%  |
| 501-600     | 115       | 10.56%  |
| 201-300     | 110       | 10.1%   |
| 351-400     | 77        | 7.07%   |
| 401-500     | 37        | 3.4%    |
| 601-700     | 28        | 2.57%   |
| 701-800     | 11        | 1.01%   |
| 1001-1500   | 11        | 1.01%   |
| 801-900     | 8         | 0.73%   |
| 1501-2000   | 6         | 0.55%   |
| Unknown     | 4         | 0.37%   |
| 101-200     | 1         | 0.09%   |
| 901-1000    | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 730       | 77.91%  |
| 16/10   | 159       | 16.97%  |
| 3/2     | 18        | 1.92%   |
| 21/9    | 12        | 1.28%   |
| 2.65    | 5         | 0.53%   |
| 5/4     | 3         | 0.32%   |
| 6/5     | 2         | 0.21%   |
| 4/3     | 2         | 0.21%   |
| Unknown | 2         | 0.21%   |
| 32/9    | 1         | 0.11%   |
| 3.40    | 1         | 0.11%   |
| 0.62    | 1         | 0.11%   |
| 0.56    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 409       | 37.39%  |
| 81-90          | 257       | 23.49%  |
| 201-250        | 76        | 6.95%   |
| 71-80          | 52        | 4.75%   |
| 301-350        | 51        | 4.66%   |
| 121-130        | 50        | 4.57%   |
| 111-120        | 50        | 4.57%   |
| 351-500        | 32        | 2.93%   |
| 251-300        | 22        | 2.01%   |
| 61-70          | 18        | 1.65%   |
| More than 1000 | 15        | 1.37%   |
| 51-60          | 13        | 1.19%   |
| 151-200        | 13        | 1.19%   |
| 131-140        | 9         | 0.82%   |
| 141-150        | 8         | 0.73%   |
| 501-1000       | 8         | 0.73%   |
| 91-100         | 4         | 0.37%   |
| Unknown        | 4         | 0.37%   |
| 41-50          | 2         | 0.18%   |
| 1-40           | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 519       | 48.28%  |
| 101-120       | 196       | 18.23%  |
| 51-100        | 149       | 13.86%  |
| 161-240       | 140       | 13.02%  |
| More than 240 | 52        | 4.84%   |
| 1-50          | 15        | 1.4%    |
| Unknown       | 4         | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 704       | 77.11%  |
| 2     | 192       | 21.03%  |
| 3     | 14        | 1.53%   |
| 0     | 3         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 536       | 38.31%  |
| Realtek Semiconductor             | 495       | 35.38%  |
| Qualcomm Atheros                  | 122       | 8.72%   |
| MediaTek                          | 80        | 5.72%   |
| Broadcom                          | 42        | 3%      |
| Broadcom Limited                  | 16        | 1.14%   |
| ASIX Electronics                  | 15        | 1.07%   |
| Qualcomm                          | 11        | 0.79%   |
| TP-Link                           | 9         | 0.64%   |
| Sierra Wireless                   | 8         | 0.57%   |
| D-Link                            | 8         | 0.57%   |
| DisplayLink                       | 7         | 0.5%    |
| Lenovo                            | 6         | 0.43%   |
| Ralink                            | 5         | 0.36%   |
| Cypress Semiconductor             | 5         | 0.36%   |
| Hewlett-Packard                   | 4         | 0.29%   |
| Apple                             | 4         | 0.29%   |
| Samsung Electronics               | 3         | 0.21%   |
| OPPO Electronics                  | 2         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.14%   |
| ICS Advent                        | 2         | 0.14%   |
| Huawei Technologies               | 2         | 0.14%   |
| Ericsson Business Mobile Networks | 2         | 0.14%   |
| Xiaomi                            | 1         | 0.07%   |
| Ralink Technology                 | 1         | 0.07%   |
| Quectel Wireless Solutions        | 1         | 0.07%   |
| Qualcomm Technologies             | 1         | 0.07%   |
| NetGear                           | 1         | 0.07%   |
| Microsoft                         | 1         | 0.07%   |
| Marvell Technology Group          | 1         | 0.07%   |
| Linksys                           | 1         | 0.07%   |
| Google                            | 1         | 0.07%   |
| FIBOCOM                           | 1         | 0.07%   |
| Dell                              | 1         | 0.07%   |
| D-Link System                     | 1         | 0.07%   |
| Belkin Components                 | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 342       | 20.79%  |
| Intel Wi-Fi 6 AX200                                                    | 73        | 4.44%   |
| Intel Wireless 8265 / 8275                                             | 46        | 2.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 44        | 2.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 41        | 2.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 40        | 2.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 39        | 2.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 38        | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 36        | 2.19%   |
| Intel Wi-Fi 6 AX201                                                    | 34        | 2.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 31        | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 31        | 1.88%   |
| Intel Wireless 7265                                                    | 28        | 1.7%    |
| Intel Wireless 8260                                                    | 25        | 1.52%   |
| Intel Wireless 7260                                                    | 24        | 1.46%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 23        | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 22        | 1.34%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 20        | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 17        | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 15        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                                  | 14        | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 13        | 0.79%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 13        | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 13        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 13        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 12        | 0.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 12        | 0.73%   |
| Intel Wireless 3165                                                    | 12        | 0.73%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 11        | 0.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 11        | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 11        | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 11        | 0.67%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 10        | 0.61%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 10        | 0.61%   |
| Intel Ethernet Connection I218-LM                                      | 10        | 0.61%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 526       | 56.44%  |
| Realtek Semiconductor      | 133       | 14.27%  |
| Qualcomm Atheros           | 100       | 10.73%  |
| MediaTek                   | 79        | 8.48%   |
| Broadcom                   | 31        | 3.33%   |
| Broadcom Limited           | 15        | 1.61%   |
| Qualcomm                   | 10        | 1.07%   |
| TP-Link                    | 8         | 0.86%   |
| Sierra Wireless            | 8         | 0.86%   |
| D-Link                     | 8         | 0.86%   |
| Ralink                     | 5         | 0.54%   |
| Ralink Technology          | 1         | 0.11%   |
| Quectel Wireless Solutions | 1         | 0.11%   |
| Qualcomm Technologies      | 1         | 0.11%   |
| Microsoft                  | 1         | 0.11%   |
| Linksys                    | 1         | 0.11%   |
| FIBOCOM                    | 1         | 0.11%   |
| Dell                       | 1         | 0.11%   |
| D-Link System              | 1         | 0.11%   |
| Belkin Components          | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 73        | 7.78%   |
| Intel Wireless 8265 / 8275                                           | 46        | 4.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 44        | 4.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 40        | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 38        | 4.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 36        | 3.84%   |
| Intel Wi-Fi 6 AX201                                                  | 34        | 3.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 31        | 3.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 31        | 3.3%    |
| Intel Wireless 7265                                                  | 28        | 2.99%   |
| Intel Wireless 8260                                                  | 25        | 2.67%   |
| Intel Wireless 7260                                                  | 24        | 2.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 23        | 2.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 22        | 2.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 20        | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 19        | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 17        | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 15        | 1.6%    |
| Intel Tiger Lake PCH CNVi WiFi                                       | 13        | 1.39%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 13        | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 13        | 1.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 12        | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 12        | 1.28%   |
| Intel Wireless 3165                                                  | 12        | 1.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 11        | 1.17%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 11        | 1.17%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 11        | 1.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 11        | 1.17%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 10        | 1.07%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 10        | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 10        | 1.07%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 10        | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 9         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                        | 9         | 0.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 8         | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 7         | 0.75%   |
| Realtek 802.11ac NIC                                                 | 7         | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 7         | 0.75%   |
| D-Link 802.11ac NIC                                                  | 7         | 0.75%   |
| Intel Wireless 3160                                                  | 6         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 437       | 64.36%  |
| Intel                         | 141       | 20.77%  |
| Qualcomm Atheros              | 34        | 5.01%   |
| Broadcom                      | 15        | 2.21%   |
| ASIX Electronics              | 15        | 2.21%   |
| DisplayLink                   | 7         | 1.03%   |
| Cypress Semiconductor         | 5         | 0.74%   |
| Lenovo                        | 4         | 0.59%   |
| Apple                         | 4         | 0.59%   |
| Samsung Electronics           | 3         | 0.44%   |
| OPPO Electronics              | 2         | 0.29%   |
| ICS Advent                    | 2         | 0.29%   |
| Xiaomi                        | 1         | 0.15%   |
| TP-Link                       | 1         | 0.15%   |
| Qualcomm                      | 1         | 0.15%   |
| OnePlus Technology (Shenzhen) | 1         | 0.15%   |
| NetGear                       | 1         | 0.15%   |
| MediaTek                      | 1         | 0.15%   |
| Marvell Technology Group      | 1         | 0.15%   |
| Hewlett-Packard               | 1         | 0.15%   |
| Google                        | 1         | 0.15%   |
| Broadcom Limited              | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 342       | 49.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 41        | 5.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 39        | 5.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 2.87%   |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 2.15%   |
| Intel Ethernet Connection (4) I219-LM                                  | 14        | 2.01%   |
| ASIX AX88179 Gigabit Ethernet                                          | 13        | 1.87%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 1.72%   |
| Intel Ethernet Connection I218-LM                                      | 10        | 1.43%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 1.43%   |
| Intel Ethernet Connection (4) I219-V                                   | 10        | 1.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 7         | 1%      |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 1%      |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6         | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 0.86%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 5         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.72%   |
| Cypress K38231_03                                                      | 5         | 0.72%   |
| Realtek Killer E2600 GbE Controller                                    | 4         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.57%   |
| Apple iBridge                                                          | 4         | 0.57%   |
| Realtek PCIe GbE Family Controller                                     | 3         | 0.43%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 3         | 0.43%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.43%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.43%   |
| Intel Ethernet Connection (16) I219-V                                  | 3         | 0.43%   |
| Intel Ethernet Connection (16) I219-LM                                 | 3         | 0.43%   |
| DisplayLink LAPDOCK                                                    | 3         | 0.43%   |
| DisplayLink Dell Universal Dock D6000                                  | 3         | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.29%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.29%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.29%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 2         | 0.29%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]            | 2         | 0.29%   |
| Intel Ethernet Controller I225-V                                       | 2         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 888       | 57.44%  |
| Ethernet | 648       | 41.91%  |
| Modem    | 9         | 0.58%   |
| Unknown  | 1         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 800       | 84.12%  |
| Ethernet | 151       | 15.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 584       | 65.25%  |
| 1     | 298       | 33.3%   |
| 3     | 8         | 0.89%   |
| 0     | 5         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 688       | 75.77%  |
| Yes  | 220       | 24.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 466       | 55.34%  |
| Realtek Semiconductor           | 88        | 10.45%  |
| IMC Networks                    | 55        | 6.53%   |
| Foxconn / Hon Hai               | 51        | 6.06%   |
| Qualcomm Atheros Communications | 47        | 5.58%   |
| Lite-On Technology              | 35        | 4.16%   |
| Broadcom                        | 25        | 2.97%   |
| Apple                           | 16        | 1.9%    |
| Realtek                         | 9         | 1.07%   |
| MediaTek                        | 9         | 1.07%   |
| USI                             | 7         | 0.83%   |
| Cambridge Silicon Radio         | 7         | 0.83%   |
| Toshiba                         | 5         | 0.59%   |
| Ralink                          | 5         | 0.59%   |
| Hewlett-Packard                 | 5         | 0.59%   |
| Dell                            | 4         | 0.48%   |
| ASUSTek Computer                | 3         | 0.36%   |
| Opticis                         | 2         | 0.24%   |
| TP-Link                         | 1         | 0.12%   |
| Foxconn International           | 1         | 0.12%   |
| Alps Electric                   | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 98        | 11.63%  |
| Intel Bluetooth wireless interface                  | 80        | 9.49%   |
| Intel AX200 Bluetooth                               | 72        | 8.54%   |
| Intel Bluetooth Device                              | 68        | 8.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 58        | 6.88%   |
| Realtek Bluetooth Radio                             | 52        | 6.17%   |
| Intel AX211 Bluetooth                               | 49        | 5.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 28        | 3.32%   |
| IMC Networks Wireless_Device                        | 27        | 3.2%    |
| Intel AX210 Bluetooth                               | 19        | 2.25%   |
| Foxconn / Hon Hai Wireless_Device                   | 18        | 2.14%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 17        | 2.02%   |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 1.9%    |
| IMC Networks Bluetooth Radio                        | 16        | 1.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1.66%   |
| Apple Bluetooth USB Host Controller                 | 12        | 1.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 1.19%   |
| Realtek Bluetooth Radio                             | 9         | 1.07%   |
| Lite-On Bluetooth Device                            | 9         | 1.07%   |
| MediaTek Wireless_Device                            | 8         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 0.95%   |
| USI Bluetooth Device                                | 7         | 0.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.83%   |
| Realtek 802.11ac WLAN Adapter                       | 7         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 0.83%   |
| Realtek RTL8821A Bluetooth                          | 6         | 0.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 0.71%   |
| IMC Networks Bluetooth Device                       | 6         | 0.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.71%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.59%   |
| Lite-On Wireless_Device                             | 5         | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.36%   |
| Lite-On Bluetooth Radio                             | 3         | 0.36%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.36%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.36%   |
| Toshiba BCM43142A0                                  | 2         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 616       | 50.66%  |
| AMD                         | 283       | 23.27%  |
| Nvidia                      | 184       | 15.13%  |
| C-Media Electronics         | 14        | 1.15%   |
| Texas Instruments           | 10        | 0.82%   |
| Realtek Semiconductor       | 8         | 0.66%   |
| Sony                        | 6         | 0.49%   |
| Lenovo                      | 6         | 0.49%   |
| KORG                        | 6         | 0.49%   |
| Focusrite-Novation          | 6         | 0.49%   |
| Apple                       | 6         | 0.49%   |
| Logitech                    | 5         | 0.41%   |
| Corsair                     | 5         | 0.41%   |
| AKAI                        | 5         | 0.41%   |
| Hewlett-Packard             | 4         | 0.33%   |
| Generalplus Technology      | 4         | 0.33%   |
| Kingston Technology         | 3         | 0.25%   |
| JMTek                       | 3         | 0.25%   |
| Creative Technology         | 3         | 0.25%   |
| TX                          | 2         | 0.16%   |
| Samson Technologies         | 2         | 0.16%   |
| Razer USA                   | 2         | 0.16%   |
| Plantronics                 | 2         | 0.16%   |
| GYROCOM C&C                 | 2         | 0.16%   |
| FiiO Electronics Technology | 2         | 0.16%   |
| Arturia                     | 2         | 0.16%   |
| AKAI Professional M.I.      | 2         | 0.16%   |
| YZ Technology               | 1         | 0.08%   |
| XMOS                        | 1         | 0.08%   |
| USB Audio                   | 1         | 0.08%   |
| Trust                       | 1         | 0.08%   |
| Tenx Technology             | 1         | 0.08%   |
| Tdlasunnic                  | 1         | 0.08%   |
| SteelSeries ApS             | 1         | 0.08%   |
| ROCCAT                      | 1         | 0.08%   |
| QinHeng Electronics         | 1         | 0.08%   |
| NAD Electronics             | 1         | 0.08%   |
| Microsoft                   | 1         | 0.08%   |
| Micro Star International    | 1         | 0.08%   |
| M-Audio                     | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 233       | 15.01%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 127       | 8.18%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 108       | 6.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 49        | 3.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 47        | 3.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 46        | 2.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 42        | 2.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 41        | 2.64%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 41        | 2.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 34        | 2.19%   |
| Intel 8 Series HD Audio Controller                                                                | 34        | 2.19%   |
| Nvidia Audio device                                                                               | 28        | 1.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 27        | 1.74%   |
| Intel Broadwell-U Audio Controller                                                                | 27        | 1.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 26        | 1.68%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 24        | 1.55%   |
| Intel Comet Lake PCH cAVS                                                                         | 23        | 1.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 19        | 1.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 19        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 1.16%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 16        | 1.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 16        | 1.03%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 16        | 1.03%   |
| Intel CM238 HD Audio Controller                                                                   | 16        | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 1.03%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 15        | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 15        | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 15        | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 0.84%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 12        | 0.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 0.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 0.77%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 12        | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 0.77%   |
| AMD High Definition Audio Controller                                                              | 12        | 0.77%   |
| AMD FCH Azalia Controller                                                                         | 11        | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 268       | 32.02%  |
| SK hynix            | 195       | 23.3%   |
| Micron Technology   | 123       | 14.7%   |
| Kingston            | 57        | 6.81%   |
| Crucial             | 47        | 5.62%   |
| Unknown             | 28        | 3.35%   |
| Ramaxel Technology  | 15        | 1.79%   |
| Corsair             | 12        | 1.43%   |
| A-DATA Technology   | 12        | 1.43%   |
| G.Skill             | 9         | 1.08%   |
| Elpida              | 8         | 0.96%   |
| Unknown (ABCD)      | 6         | 0.72%   |
| Unknown             | 6         | 0.72%   |
| Team                | 5         | 0.6%    |
| Kllisre             | 5         | 0.6%    |
| Patriot             | 4         | 0.48%   |
| Nanya Technology    | 4         | 0.48%   |
| Teikon              | 3         | 0.36%   |
| Transcend           | 2         | 0.24%   |
| Smart Brazil        | 2         | 0.24%   |
| Shenzhen Mic        | 2         | 0.24%   |
| Lexar               | 2         | 0.24%   |
| Hikvision           | 2         | 0.24%   |
| GOODRAM             | 2         | 0.24%   |
| V-GeN               | 1         | 0.12%   |
| Unknown (0x0E9D)    | 1         | 0.12%   |
| Unknown (0x0C97)    | 1         | 0.12%   |
| Unknown (0B85)      | 1         | 0.12%   |
| Toshiba             | 1         | 0.12%   |
| Silicon Power       | 1         | 0.12%   |
| Shenzhen Longsys    | 1         | 0.12%   |
| Sesame              | 1         | 0.12%   |
| Qimonda             | 1         | 0.12%   |
| Neo Forza           | 1         | 0.12%   |
| Magnum Tech         | 1         | 0.12%   |
| Juhor               | 1         | 0.12%   |
| ff                  | 1         | 0.12%   |
| CSX                 | 1         | 0.12%   |
| Axiom               | 1         | 0.12%   |
| Apacer              | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 18        | 2.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 1.92%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 15        | 1.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 1.58%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 1.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.24%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 10        | 1.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 1.01%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 1.01%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 1.01%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 1.01%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 1.01%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.9%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.79%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.79%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.79%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 0.79%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 0.68%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.68%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 6         | 0.68%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 6         | 0.68%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 6         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.68%   |
| Unknown                                                          | 6         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.56%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.56%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 5         | 0.56%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 5         | 0.56%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.56%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.56%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.45%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.45%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 399       | 57.49%  |
| DDR3    | 139       | 20.03%  |
| DDR5    | 47        | 6.77%   |
| LPDDR4  | 36        | 5.19%   |
| LPDDR5  | 30        | 4.32%   |
| LPDDR3  | 26        | 3.75%   |
| DDR2    | 12        | 1.73%   |
| SDRAM   | 4         | 0.58%   |
| Unknown | 1         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 591       | 83.83%  |
| Row Of Chips | 100       | 14.18%  |
| Chip         | 7         | 0.99%   |
| Unknown      | 4         | 0.57%   |
| DIMM         | 3         | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 356       | 46.66%  |
| 4096  | 177       | 23.2%   |
| 16384 | 149       | 19.53%  |
| 32768 | 39        | 5.11%   |
| 2048  | 38        | 4.98%   |
| 1024  | 4         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 220       | 29.45%  |
| 2667    | 153       | 20.48%  |
| 1600    | 120       | 16.06%  |
| 2400    | 47        | 6.29%   |
| 4800    | 38        | 5.09%   |
| 2133    | 32        | 4.28%   |
| 6400    | 23        | 3.08%   |
| 3266    | 18        | 2.41%   |
| 5600    | 11        | 1.47%   |
| 1867    | 11        | 1.47%   |
| 4267    | 10        | 1.34%   |
| 1334    | 10        | 1.34%   |
| 667     | 7         | 0.94%   |
| 1333    | 5         | 0.67%   |
| 1067    | 5         | 0.67%   |
| Unknown | 5         | 0.67%   |
| 4266    | 4         | 0.54%   |
| 7500    | 3         | 0.4%    |
| 2933    | 3         | 0.4%    |
| 800     | 3         | 0.4%    |
| 8400    | 2         | 0.27%   |
| 7400    | 2         | 0.27%   |
| 3733    | 2         | 0.27%   |
| 2048    | 2         | 0.27%   |
| 1066    | 2         | 0.27%   |
| 8533    | 1         | 0.13%   |
| 5500    | 1         | 0.13%   |
| 4199    | 1         | 0.13%   |
| 3600    | 1         | 0.13%   |
| 3000    | 1         | 0.13%   |
| 2134    | 1         | 0.13%   |
| 1776    | 1         | 0.13%   |
| 1639    | 1         | 0.13%   |
| 1200    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 16.67%  |
| Seiko Epson         | 1         | 16.67%  |
| Samsung Electronics | 1         | 16.67%  |
| Prolific Technology | 1         | 16.67%  |
| PM                  | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Xerox B210                    | 1         | 16.67%  |
| Seiko Epson ET-2850 Series    | 1         | 16.67%  |
| Samsung M2020 Series          | 1         | 16.67%  |
| Prolific PL2305 Parallel Port | 1         | 16.67%  |
| PM PM241-BT                   | 1         | 16.67%  |
| HP DeskJet 2130 series        | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 174       | 21.25%  |
| IMC Networks                           | 124       | 15.14%  |
| Bison Electronics                      | 71        | 8.67%   |
| Microdia                               | 58        | 7.08%   |
| Quanta                                 | 56        | 6.84%   |
| Sunplus Innovation Technology          | 41        | 5.01%   |
| Realtek Semiconductor                  | 41        | 5.01%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 4.27%   |
| Luxvisions Innotech Limited            | 28        | 3.42%   |
| Syntek                                 | 26        | 3.17%   |
| Lite-On Technology                     | 25        | 3.05%   |
| Apple                                  | 22        | 2.69%   |
| Logitech                               | 20        | 2.44%   |
| Sonix Technology                       | 19        | 2.32%   |
| Acer                                   | 18        | 2.2%    |
| Suyin                                  | 10        | 1.22%   |
| Silicon Motion                         | 5         | 0.61%   |
| Generalplus Technology                 | 5         | 0.61%   |
| Lenovo                                 | 4         | 0.49%   |
| Alcor Micro                            | 4         | 0.49%   |
| ShineTech                              | 3         | 0.37%   |
| Ricoh                                  | 3         | 0.37%   |
| Primax Electronics                     | 3         | 0.37%   |
| Tripath Technology                     | 2         | 0.24%   |
| Samsung Electronics                    | 2         | 0.24%   |
| MacroSilicon                           | 2         | 0.24%   |
| Intel                                  | 2         | 0.24%   |
| Y Media                                | 1         | 0.12%   |
| Trust                                  | 1         | 0.12%   |
| SunplusIT                              | 1         | 0.12%   |
| Sunplus IT                             | 1         | 0.12%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.12%   |
| Shine-optics                           | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| OPPO Electronics                       | 1         | 0.12%   |
| OmniVision Technologies                | 1         | 0.12%   |
| Microsoft                              | 1         | 0.12%   |
| LG Electronics                         | 1         | 0.12%   |
| GRANDSTREAM GUV3100                    | 1         | 0.12%   |
| Google                                 | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 56        | 6.81%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 47        | 5.72%   |
| IMC Networks Integrated Camera                               | 45        | 5.47%   |
| Microdia Integrated_Webcam_HD                                | 30        | 3.65%   |
| Bison Integrated Camera                                      | 22        | 2.68%   |
| Chicony HD Webcam                                            | 21        | 2.55%   |
| Syntek Integrated Camera                                     | 19        | 2.31%   |
| Realtek Integrated_Webcam_HD                                 | 17        | 2.07%   |
| Sonix USB2.0 HD UVC WebCam                                   | 13        | 1.58%   |
| Bison HD Webcam                                              | 13        | 1.58%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                              | 13        | 1.58%   |
| Bison BisonCam,NB Pro                                        | 11        | 1.34%   |
| Sunplus Integrated_Webcam_HD                                 | 9         | 1.09%   |
| Quanta HD User Facing                                        | 9         | 1.09%   |
| Acer Integrated Camera                                       | 9         | 1.09%   |
| Quanta USB2.0 HD UVC WebCam                                  | 8         | 0.97%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 8         | 0.97%   |
| Lite-On Integrated Camera                                    | 8         | 0.97%   |
| IMC Networks HD Camera                                       | 8         | 0.97%   |
| Sunplus HD WebCam                                            | 7         | 0.85%   |
| Quanta HP TrueVision HD Camera                               | 7         | 0.85%   |
| Luxvisions Innotech Limited Integrated Camera                | 7         | 0.85%   |
| Chicony USB2.0 HD UVC WebCam                                 | 7         | 0.85%   |
| Bison SunplusIT Integrated Camera                            | 7         | 0.85%   |
| Sonix USB2.0 FHD UVC WebCam                                  | 6         | 0.73%   |
| Quanta HP HD Camera                                          | 6         | 0.73%   |
| Microdia Integrated Webcam                                   | 6         | 0.73%   |
| IMC Networks USB2.0 VGA UVC WebCam                           | 6         | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam                                | 6         | 0.73%   |
| Chicony HD User Facing                                       | 6         | 0.73%   |
| Quanta VGA WebCam                                            | 5         | 0.61%   |
| Logitech C920 PRO HD Webcam                                  | 5         | 0.61%   |
| Lite-On HP HD Camera                                         | 5         | 0.61%   |
| Chicony VGA WebCam                                           | 5         | 0.61%   |
| Chicony HP Wide Vision HD Camera                             | 5         | 0.61%   |
| Chicony HP TrueVision HD Camera                              | 5         | 0.61%   |
| Chicony EasyCamera                                           | 5         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 5         | 0.61%   |
| Apple FaceTime HD Camera (Built-in)                          | 5         | 0.61%   |
| Syntek Lenovo EasyCamera                                     | 4         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 52        | 33.12%  |
| Validity Sensors                   | 43        | 27.39%  |
| Shenzhen Goodix Technology         | 26        | 16.56%  |
| Elan Microelectronics              | 18        | 11.46%  |
| LighTuning Technology              | 7         | 4.46%   |
| Upek                               | 4         | 2.55%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 2.55%   |
| AuthenTec                          | 2         | 1.27%   |
| Focal-systems.Corp                 | 1         | 0.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 11.46%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 10.19%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 7.64%   |
| Elan ELAN:Fingerprint                                                      | 10        | 6.37%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 5.73%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 5.1%    |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 5.1%    |
| Elan ELAN:ARM-M4                                                           | 8         | 5.1%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 3.82%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 3.18%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 3.18%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 2.55%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 2.55%   |
| Synaptics UWP WBDI Device                                                  | 4         | 2.55%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 2.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.91%   |
| Validity Sensors VFS491                                                    | 3         | 1.91%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 1.91%   |
| Synaptics UWP WBDI                                                         | 3         | 1.91%   |
| Synaptics  WBDI                                                            | 3         | 1.91%   |
| Unknown                                                                    | 3         | 1.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.27%   |
| Synaptics WBDI                                                             | 2         | 1.27%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.64%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.64%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.64%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.64%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.64%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.64%   |
| AuthenTec AES2810                                                          | 1         | 0.64%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.64%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 31        | 53.45%  |
| Alcor Micro | 15        | 25.86%  |
| Upek        | 5         | 8.62%   |
| Lenovo      | 4         | 6.9%    |
| O2 Micro    | 2         | 3.45%   |
| CHERRY      | 1         | 1.72%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 25.42%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 18.64%  |
| Broadcom 5880                                                                | 9         | 15.25%  |
| Broadcom 58200                                                               | 7         | 11.86%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 8.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 8.47%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.39%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 551       | 60.02%  |
| 1     | 309       | 33.66%  |
| 2     | 55        | 5.99%   |
| 3     | 3         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 155       | 37.53%  |
| Chipcard                 | 54        | 13.08%  |
| Multimedia controller    | 51        | 12.35%  |
| Graphics card            | 48        | 11.62%  |
| Net/ethernet             | 46        | 11.14%  |
| Net/wireless             | 24        | 5.81%   |
| Camera                   | 13        | 3.15%   |
| Bluetooth                | 11        | 2.66%   |
| Storage                  | 4         | 0.97%   |
| Communication controller | 3         | 0.73%   |
| Modem                    | 2         | 0.48%   |
| Unassigned class         | 1         | 0.24%   |
| Card reader              | 1         | 0.24%   |

