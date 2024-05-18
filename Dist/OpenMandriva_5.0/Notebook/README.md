OpenMandriva 5.0 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 5.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 384

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS EXPERTBOOK L2502CYA... | [03df260579](https://linux-hardware.org/?probe=03df260579) | May 09, 2024 |
| ASUSTek       | K52F                        | [f67d81858e](https://linux-hardware.org/?probe=f67d81858e) | May 09, 2024 |
| Dell          | Inspiron N5040              | [5fae884a07](https://linux-hardware.org/?probe=5fae884a07) | May 08, 2024 |
| Sony          | VGN-Z51MG_B                 | [6e5ed9d5f6](https://linux-hardware.org/?probe=6e5ed9d5f6) | May 08, 2024 |
| Dell          | Inspiron 5420               | [24c2d41566](https://linux-hardware.org/?probe=24c2d41566) | May 08, 2024 |
| Fujitsu       | FMVNR1PE                    | [95504ca73e](https://linux-hardware.org/?probe=95504ca73e) | May 08, 2024 |
| Lenovo        | XiaoXin-15IIL 2020 81YL     | [b95cda619a](https://linux-hardware.org/?probe=b95cda619a) | May 06, 2024 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [ae77241a92](https://linux-hardware.org/?probe=ae77241a92) | May 06, 2024 |
| HP            | EliteBook 820 G2            | [254af47954](https://linux-hardware.org/?probe=254af47954) | May 06, 2024 |
| Lenovo        | V110-15IAP 80TG             | [2ba8347b04](https://linux-hardware.org/?probe=2ba8347b04) | May 05, 2024 |
| ASUSTek       | F5SL                        | [da423af0cb](https://linux-hardware.org/?probe=da423af0cb) | May 05, 2024 |
| HP            | Notebook                    | [87f06569d7](https://linux-hardware.org/?probe=87f06569d7) | May 04, 2024 |
| ASUSTek       | X553MA                      | [0418112d2f](https://linux-hardware.org/?probe=0418112d2f) | May 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [cee4dd63f5](https://linux-hardware.org/?probe=cee4dd63f5) | Apr 30, 2024 |
| Chuwi         | LapBook Air                 | [ee0775cfb7](https://linux-hardware.org/?probe=ee0775cfb7) | Apr 30, 2024 |
| Dell          | Inspiron 15 3511            | [48c356da20](https://linux-hardware.org/?probe=48c356da20) | Apr 25, 2024 |
| Dell          | Inspiron 15 3515            | [cd29a525ed](https://linux-hardware.org/?probe=cd29a525ed) | Apr 24, 2024 |
| HP            | Laptop 15s-fq2xxx           | [06c81aed79](https://linux-hardware.org/?probe=06c81aed79) | Apr 23, 2024 |
| Dell          | Latitude E5550              | [2193ab1cfa](https://linux-hardware.org/?probe=2193ab1cfa) | Apr 23, 2024 |
| ASUSTek       | K93SM                       | [031f10fad0](https://linux-hardware.org/?probe=031f10fad0) | Apr 22, 2024 |
| Acer          | TM8573                      | [9c3c528235](https://linux-hardware.org/?probe=9c3c528235) | Apr 21, 2024 |
| HUAWEI        | BOHK-WAX9X                  | [b69304aa9b](https://linux-hardware.org/?probe=b69304aa9b) | Apr 21, 2024 |
| ASUSTek       | Strix 15 GL503GE            | [efeb67efdf](https://linux-hardware.org/?probe=efeb67efdf) | Apr 19, 2024 |
| HP            | 240 G8 Notebook PC          | [13af7544f2](https://linux-hardware.org/?probe=13af7544f2) | Apr 17, 2024 |
| Lenovo        | ThinkPad L560 20F2S0TB00    | [943647251c](https://linux-hardware.org/?probe=943647251c) | Apr 17, 2024 |
| Dell          | Latitude E5470              | [f286256e09](https://linux-hardware.org/?probe=f286256e09) | Apr 17, 2024 |
| ASUSTek       | X751LJ                      | [ee2d127680](https://linux-hardware.org/?probe=ee2d127680) | Apr 16, 2024 |
| Acer          | Aspire E1-572G              | [5428a93214](https://linux-hardware.org/?probe=5428a93214) | Apr 16, 2024 |
| HP            | Laptop 15-ef0xxx            | [dbbb032e1b](https://linux-hardware.org/?probe=dbbb032e1b) | Apr 15, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6c2703c57b](https://linux-hardware.org/?probe=6c2703c57b) | Apr 13, 2024 |
| Dell          | Inspiron 7720               | [3ceb371831](https://linux-hardware.org/?probe=3ceb371831) | Apr 09, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1da57352b2](https://linux-hardware.org/?probe=1da57352b2) | Apr 08, 2024 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [113bdef0c9](https://linux-hardware.org/?probe=113bdef0c9) | Apr 08, 2024 |
| Info Quest... | GTN1402 4-64                | [057ad875b5](https://linux-hardware.org/?probe=057ad875b5) | Apr 08, 2024 |
| ASUSTek       | S550CB                      | [04013b8286](https://linux-hardware.org/?probe=04013b8286) | Apr 07, 2024 |
| Dell          | Inspiron 16 5635            | [0f0bacc25d](https://linux-hardware.org/?probe=0f0bacc25d) | Apr 06, 2024 |
| ASUSTek       | X550ZE                      | [ce16f4beb9](https://linux-hardware.org/?probe=ce16f4beb9) | Apr 06, 2024 |
| Lenovo        | B590 20208                  | [bcf0312d12](https://linux-hardware.org/?probe=bcf0312d12) | Apr 06, 2024 |
| Login Info... | LOG-M301H                   | [85373f9f2b](https://linux-hardware.org/?probe=85373f9f2b) | Apr 06, 2024 |
| Toshiba       | Satellite U500              | [4872d0c452](https://linux-hardware.org/?probe=4872d0c452) | Apr 06, 2024 |
| Acer          | Aspire E5-571G              | [c43dd19a4d](https://linux-hardware.org/?probe=c43dd19a4d) | Apr 06, 2024 |
| HP            | 240 G6 Notebook PC          | [b946fe73c4](https://linux-hardware.org/?probe=b946fe73c4) | Apr 05, 2024 |
| ASUSTek       | K53U                        | [bd1d2c95e9](https://linux-hardware.org/?probe=bd1d2c95e9) | Apr 05, 2024 |
| Lenovo        | ThinkPad W530 24476F1       | [14d694fe39](https://linux-hardware.org/?probe=14d694fe39) | Apr 05, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b30ba46617](https://linux-hardware.org/?probe=b30ba46617) | Apr 05, 2024 |
| HP            | EliteBook 840 G2            | [cb733ed3d2](https://linux-hardware.org/?probe=cb733ed3d2) | Apr 05, 2024 |
| Dell          | Vostro 5468                 | [065b2c71f1](https://linux-hardware.org/?probe=065b2c71f1) | Apr 04, 2024 |
| ASUSTek       | K42F                        | [73ef819d0c](https://linux-hardware.org/?probe=73ef819d0c) | Apr 04, 2024 |
| Toshiba       | Satellite S855D             | [5f79e80e44](https://linux-hardware.org/?probe=5f79e80e44) | Apr 03, 2024 |
| ASUSTek       | X751MJ                      | [cdb26bf7a8](https://linux-hardware.org/?probe=cdb26bf7a8) | Apr 03, 2024 |
| Dell          | Inspiron 15 3520            | [ceface0ac8](https://linux-hardware.org/?probe=ceface0ac8) | Mar 31, 2024 |
| Google        | Blorb                       | [48c735d25a](https://linux-hardware.org/?probe=48c735d25a) | Mar 31, 2024 |
| Acer          | Acadia V1.45                | [f126c80f18](https://linux-hardware.org/?probe=f126c80f18) | Mar 31, 2024 |
| Timi          | Redmi Book Pro 15 2022      | [67084fde52](https://linux-hardware.org/?probe=67084fde52) | Mar 31, 2024 |
| HP            | Laptop 17-cp0xxx            | [ad835fa809](https://linux-hardware.org/?probe=ad835fa809) | Mar 30, 2024 |
| Metabox       | Alpha-V V158PNH             | [9d020b5c12](https://linux-hardware.org/?probe=9d020b5c12) | Mar 29, 2024 |
| Toshiba       | Satellite L700              | [d2073d2786](https://linux-hardware.org/?probe=d2073d2786) | Mar 29, 2024 |
| Toshiba       | PORTEGE Z930                | [e1f25da3fd](https://linux-hardware.org/?probe=e1f25da3fd) | Mar 28, 2024 |
| HP            | EliteBook 840 14 inch G9... | [401fd1d912](https://linux-hardware.org/?probe=401fd1d912) | Mar 28, 2024 |
| Dell          | Inspiron 3521               | [64c0a44737](https://linux-hardware.org/?probe=64c0a44737) | Mar 27, 2024 |
| ASUSTek       | K46CM                       | [81723c2d41](https://linux-hardware.org/?probe=81723c2d41) | Mar 27, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [448e52314e](https://linux-hardware.org/?probe=448e52314e) | Mar 26, 2024 |
| HP            | 550                         | [2e06980f11](https://linux-hardware.org/?probe=2e06980f11) | Mar 26, 2024 |
| Acer          | Aspire 5610                 | [6f172dbbce](https://linux-hardware.org/?probe=6f172dbbce) | Mar 26, 2024 |
| ASUSTek       | X541NA                      | [6d98c3288f](https://linux-hardware.org/?probe=6d98c3288f) | Mar 24, 2024 |
| ASUSTek       | X550CC                      | [5e519a6603](https://linux-hardware.org/?probe=5e519a6603) | Mar 24, 2024 |
| Dell          | G5 5505                     | [bbe548c3a5](https://linux-hardware.org/?probe=bbe548c3a5) | Mar 24, 2024 |
| ASUSTek       | F5RL                        | [6d1c82c10a](https://linux-hardware.org/?probe=6d1c82c10a) | Mar 24, 2024 |
| Fujitsu       | LIFEBOOK E734               | [1da01e0e94](https://linux-hardware.org/?probe=1da01e0e94) | Mar 24, 2024 |
| Apple         | MacBookPro9,2               | [fdfc1584b0](https://linux-hardware.org/?probe=fdfc1584b0) | Mar 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [ac91f9a09e](https://linux-hardware.org/?probe=ac91f9a09e) | Mar 20, 2024 |
| EVOO          | TEV-CE-141-2                | [610e0430fb](https://linux-hardware.org/?probe=610e0430fb) | Mar 20, 2024 |
| HP            | 15                          | [42f7c3330f](https://linux-hardware.org/?probe=42f7c3330f) | Mar 20, 2024 |
| ASUSTek       | X550LA                      | [0e6e1ad03f](https://linux-hardware.org/?probe=0e6e1ad03f) | Mar 19, 2024 |
| EVOO          | TEV-CE-141-2                | [1249a2e867](https://linux-hardware.org/?probe=1249a2e867) | Mar 19, 2024 |
| NEC Comput... | PC-VK23LBZDU                | [24b87183b2](https://linux-hardware.org/?probe=24b87183b2) | Mar 16, 2024 |
| Lenovo        | G50-30 80G0                 | [3c7f756761](https://linux-hardware.org/?probe=3c7f756761) | Mar 15, 2024 |
| ASUSTek       | K501UW                      | [b340853193](https://linux-hardware.org/?probe=b340853193) | Mar 14, 2024 |
| EVOO          | TEV-CE-141-2                | [9114f3455d](https://linux-hardware.org/?probe=9114f3455d) | Mar 14, 2024 |
| HP            | 650                         | [8968085c5a](https://linux-hardware.org/?probe=8968085c5a) | Mar 13, 2024 |
| HP            | Unknown                     | [cd14ad3a78](https://linux-hardware.org/?probe=cd14ad3a78) | Mar 11, 2024 |
| Dell          | Inspiron M5010              | [b5456dc305](https://linux-hardware.org/?probe=b5456dc305) | Mar 11, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [45bd992a0b](https://linux-hardware.org/?probe=45bd992a0b) | Mar 09, 2024 |
| Login Info... | LOG-S14BW01-CD              | [7f65234175](https://linux-hardware.org/?probe=7f65234175) | Mar 08, 2024 |
| Dell          | Latitude E5550              | [4832591086](https://linux-hardware.org/?probe=4832591086) | Mar 08, 2024 |
| HP            | 248 G1                      | [918afcb1a0](https://linux-hardware.org/?probe=918afcb1a0) | Mar 07, 2024 |
| Lenovo        | ThinkPad T60 8744HDG        | [95634ccb20](https://linux-hardware.org/?probe=95634ccb20) | Mar 06, 2024 |
| eMachines     | Unknown                     | [419c39fa61](https://linux-hardware.org/?probe=419c39fa61) | Mar 06, 2024 |
| HP            | Laptop 15s-eq1xxx           | [42b75630c2](https://linux-hardware.org/?probe=42b75630c2) | Mar 05, 2024 |
| Toshiba       | Satellite C650              | [ee60747898](https://linux-hardware.org/?probe=ee60747898) | Mar 02, 2024 |
| Razer         | Blade Pro                   | [e7958de2ad](https://linux-hardware.org/?probe=e7958de2ad) | Mar 02, 2024 |
| Toshiba       | PORTEGE Z30-A               | [a685c7e5d5](https://linux-hardware.org/?probe=a685c7e5d5) | Feb 28, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [14a2b4f3ca](https://linux-hardware.org/?probe=14a2b4f3ca) | Feb 25, 2024 |
| ASUSTek       | G501JW                      | [fc8be1147a](https://linux-hardware.org/?probe=fc8be1147a) | Feb 21, 2024 |
| HP            | Compaq 610                  | [e32de41ce7](https://linux-hardware.org/?probe=e32de41ce7) | Feb 18, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b4370c5953](https://linux-hardware.org/?probe=b4370c5953) | Feb 17, 2024 |
| ASUSTek       | X751MA                      | [9f7154507e](https://linux-hardware.org/?probe=9f7154507e) | Feb 17, 2024 |
| Dell          | Studio 1537                 | [9392cffcbe](https://linux-hardware.org/?probe=9392cffcbe) | Feb 17, 2024 |
| ASUSTek       | X750JB                      | [6280d27845](https://linux-hardware.org/?probe=6280d27845) | Feb 16, 2024 |
| Lenovo        | ThinkPad T60 1951BS9        | [ead853576a](https://linux-hardware.org/?probe=ead853576a) | Feb 16, 2024 |
| HP            | ProBook 640 G1              | [759b600f96](https://linux-hardware.org/?probe=759b600f96) | Feb 16, 2024 |
| Google        | Morphius                    | [b12084d8b3](https://linux-hardware.org/?probe=b12084d8b3) | Feb 15, 2024 |
| HP            | Laptop 17-cn0xxx            | [7453a324f5](https://linux-hardware.org/?probe=7453a324f5) | Feb 15, 2024 |
| ASUSTek       | 1015BXO                     | [51e861c84c](https://linux-hardware.org/?probe=51e861c84c) | Feb 15, 2024 |
| Acer          | Aspire ES1-531              | [6ff8090f67](https://linux-hardware.org/?probe=6ff8090f67) | Feb 13, 2024 |
| Dell          | Inspiron 7720               | [d9409c4dec](https://linux-hardware.org/?probe=d9409c4dec) | Feb 12, 2024 |
| Acer          | Aspire 7739G                | [a817ec1ea1](https://linux-hardware.org/?probe=a817ec1ea1) | Feb 11, 2024 |
| Sony          | VPCEH3P1E                   | [63d0520d0e](https://linux-hardware.org/?probe=63d0520d0e) | Feb 10, 2024 |
| HP            | Compaq CQ58                 | [be03210645](https://linux-hardware.org/?probe=be03210645) | Feb 09, 2024 |
| HP            | 250 G7 Notebook PC          | [729d14272d](https://linux-hardware.org/?probe=729d14272d) | Feb 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ab5ad71c2a](https://linux-hardware.org/?probe=ab5ad71c2a) | Feb 08, 2024 |
| Sony          | SVE14A25CFP                 | [82b1cf235d](https://linux-hardware.org/?probe=82b1cf235d) | Feb 08, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [c96a13877b](https://linux-hardware.org/?probe=c96a13877b) | Feb 06, 2024 |
| HP            | Pavilion dv7                | [2d1b97ab8f](https://linux-hardware.org/?probe=2d1b97ab8f) | Feb 05, 2024 |
| Dell          | Latitude E7270              | [ff1a8893d9](https://linux-hardware.org/?probe=ff1a8893d9) | Feb 05, 2024 |
| Lenovo        | ThinkPad X13 Gen 2a 20XJ... | [d9db0185ec](https://linux-hardware.org/?probe=d9db0185ec) | Feb 05, 2024 |
| Dell          | G15 5515                    | [7eb4ec5f9b](https://linux-hardware.org/?probe=7eb4ec5f9b) | Feb 05, 2024 |
| HP            | G62                         | [e4a53339ea](https://linux-hardware.org/?probe=e4a53339ea) | Feb 04, 2024 |
| HP            | ProBook 5320m               | [3be604f862](https://linux-hardware.org/?probe=3be604f862) | Feb 03, 2024 |
| ASUSTek       | X540YA                      | [4e8d90738d](https://linux-hardware.org/?probe=4e8d90738d) | Jan 31, 2024 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [3bba660f51](https://linux-hardware.org/?probe=3bba660f51) | Jan 31, 2024 |
| Packard Be... | EasyNote ENLG71BM           | [ab713b894e](https://linux-hardware.org/?probe=ab713b894e) | Jan 31, 2024 |
| Toshiba       | Portable PC                 | [5c293a3c24](https://linux-hardware.org/?probe=5c293a3c24) | Jan 30, 2024 |
| ARCELIK       | GNB 1150 B1 N2              | [eb35406b7e](https://linux-hardware.org/?probe=eb35406b7e) | Jan 29, 2024 |
| Acer          | Aspire 5720Z                | [2353edc7dd](https://linux-hardware.org/?probe=2353edc7dd) | Jan 29, 2024 |
| HP            | Pavilion Laptop 15t-eg00... | [fd0435f25b](https://linux-hardware.org/?probe=fd0435f25b) | Jan 29, 2024 |
| Acer          | Aspire 5750                 | [f05ba6ae6f](https://linux-hardware.org/?probe=f05ba6ae6f) | Jan 29, 2024 |
| Acer          | Aspire V5-471PG             | [621c9286da](https://linux-hardware.org/?probe=621c9286da) | Jan 28, 2024 |
| Dell          | Latitude 3510               | [0be0a86c59](https://linux-hardware.org/?probe=0be0a86c59) | Jan 28, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [dd39831e6f](https://linux-hardware.org/?probe=dd39831e6f) | Jan 27, 2024 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [01dd8556d5](https://linux-hardware.org/?probe=01dd8556d5) | Jan 26, 2024 |
| Acer          | Aspire ES1-531              | [7faffb7f83](https://linux-hardware.org/?probe=7faffb7f83) | Jan 25, 2024 |
| HP            | Compaq 6730s                | [caa48b80fb](https://linux-hardware.org/?probe=caa48b80fb) | Jan 25, 2024 |
| Acer          | Aspire ES1-572              | [10d96173cd](https://linux-hardware.org/?probe=10d96173cd) | Jan 25, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [057c708875](https://linux-hardware.org/?probe=057c708875) | Jan 24, 2024 |
| HP            | EliteBook 840 G3            | [eceea6fa49](https://linux-hardware.org/?probe=eceea6fa49) | Jan 24, 2024 |
| eMachines     | eME732Z                     | [fe3d184f11](https://linux-hardware.org/?probe=fe3d184f11) | Jan 24, 2024 |
| Toshiba       | Satellite C650              | [2fa418e377](https://linux-hardware.org/?probe=2fa418e377) | Jan 24, 2024 |
| Apple         | MacBookPro4,1               | [4c99b7a6ff](https://linux-hardware.org/?probe=4c99b7a6ff) | Jan 23, 2024 |
| HP            | Stream Laptop 14-ax0XX      | [16c6b944fb](https://linux-hardware.org/?probe=16c6b944fb) | Jan 23, 2024 |
| Lenovo        | ThinkPad T430 2347A81       | [7209687602](https://linux-hardware.org/?probe=7209687602) | Jan 22, 2024 |
| HP            | ProBook 450 G5              | [ea8cc27b1a](https://linux-hardware.org/?probe=ea8cc27b1a) | Jan 21, 2024 |
| Fujitsu       | LIFEBOOK A555/G             | [f87640231d](https://linux-hardware.org/?probe=f87640231d) | Jan 21, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [af044c261f](https://linux-hardware.org/?probe=af044c261f) | Jan 20, 2024 |
| Acer          | Aspire 1810T                | [068454b849](https://linux-hardware.org/?probe=068454b849) | Jan 20, 2024 |
| Apple         | MacBookPro3,1               | [057f8b6477](https://linux-hardware.org/?probe=057f8b6477) | Jan 20, 2024 |
| Google        | Garg                        | [b0e91d1473](https://linux-hardware.org/?probe=b0e91d1473) | Jan 19, 2024 |
| Lenovo        | 100e 2nd Gen 81M8           | [a4aa40979a](https://linux-hardware.org/?probe=a4aa40979a) | Jan 18, 2024 |
| HP            | Laptop 15-dw3xxx            | [77766f1cc1](https://linux-hardware.org/?probe=77766f1cc1) | Jan 17, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | [589c4362a6](https://linux-hardware.org/?probe=589c4362a6) | Jan 16, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f73401456d](https://linux-hardware.org/?probe=f73401456d) | Jan 16, 2024 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [22802134b7](https://linux-hardware.org/?probe=22802134b7) | Jan 15, 2024 |
| Dell          | XPS 15 9510                 | [55cbe62073](https://linux-hardware.org/?probe=55cbe62073) | Jan 15, 2024 |
| Lenovo        | ThinkPad T450s 20BWS05V0... | [fffdee8af3](https://linux-hardware.org/?probe=fffdee8af3) | Jan 15, 2024 |
| HP            | Laptop 15-db0xxx            | [cb2cda915a](https://linux-hardware.org/?probe=cb2cda915a) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [f35fb9dd1c](https://linux-hardware.org/?probe=f35fb9dd1c) | Jan 13, 2024 |
| TUXEDO        | Book BM15 Gen10             | [dcb4b6ab6a](https://linux-hardware.org/?probe=dcb4b6ab6a) | Jan 13, 2024 |
| Dell          | Vostro 3401                 | [cd47812859](https://linux-hardware.org/?probe=cd47812859) | Jan 11, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [47ca371fcb](https://linux-hardware.org/?probe=47ca371fcb) | Jan 10, 2024 |
| Toshiba       | Satellite C660              | [34eaf45d7f](https://linux-hardware.org/?probe=34eaf45d7f) | Jan 09, 2024 |
| HP            | 2000                        | [d23f668910](https://linux-hardware.org/?probe=d23f668910) | Jan 09, 2024 |
| HP            | Compaq 610                  | [da1dd5ace4](https://linux-hardware.org/?probe=da1dd5ace4) | Jan 08, 2024 |
| Lenovo        | G710 20252                  | [ec645bc6c5](https://linux-hardware.org/?probe=ec645bc6c5) | Jan 08, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [9d534bf283](https://linux-hardware.org/?probe=9d534bf283) | Jan 07, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [770f12c749](https://linux-hardware.org/?probe=770f12c749) | Jan 07, 2024 |
| HP            | 250 G3                      | [259acacdb3](https://linux-hardware.org/?probe=259acacdb3) | Jan 06, 2024 |
| Dell          | Inspiron 5515               | [6ff66dee9c](https://linux-hardware.org/?probe=6ff66dee9c) | Jan 06, 2024 |
| Toshiba       | Satellite L55D-B            | [e0358ccedc](https://linux-hardware.org/?probe=e0358ccedc) | Jan 06, 2024 |
| Dell          | Precision 7710              | [a2b5f2de51](https://linux-hardware.org/?probe=a2b5f2de51) | Jan 02, 2024 |
| Acer          | Extensa 2540                | [0dd0c273c1](https://linux-hardware.org/?probe=0dd0c273c1) | Jan 02, 2024 |
| MSI           | Modern 14 B4MW              | [f1f1b527ce](https://linux-hardware.org/?probe=f1f1b527ce) | Jan 02, 2024 |
| Apple         | MacBookAir9,1               | [5a511e238e](https://linux-hardware.org/?probe=5a511e238e) | Jan 01, 2024 |
| ASUSTek       | X751LA                      | [089bb5bca9](https://linux-hardware.org/?probe=089bb5bca9) | Jan 01, 2024 |
| Dell          | Latitude E6500              | [8d7d1376fd](https://linux-hardware.org/?probe=8d7d1376fd) | Dec 31, 2023 |
| Info Quest... | GTN1402 4-64                | [c363bd26ad](https://linux-hardware.org/?probe=c363bd26ad) | Dec 31, 2023 |
| HP            | Compaq 610                  | [d0849e0580](https://linux-hardware.org/?probe=d0849e0580) | Dec 30, 2023 |
| Lenovo        | B560                        | [1f8cf50933](https://linux-hardware.org/?probe=1f8cf50933) | Dec 29, 2023 |
| Lenovo        | Yoga 2 11 20332             | [04bb236111](https://linux-hardware.org/?probe=04bb236111) | Dec 29, 2023 |
| HP            | Laptop 15-da0xxx            | [4e00c088e8](https://linux-hardware.org/?probe=4e00c088e8) | Dec 29, 2023 |
| Notebook      | NS5x_NS7xAU                 | [d520b97118](https://linux-hardware.org/?probe=d520b97118) | Dec 29, 2023 |
| Dell          | Inspiron 15 3515            | [6369debba7](https://linux-hardware.org/?probe=6369debba7) | Dec 26, 2023 |
| Lenovo        | ThinkPad T61 7663DL1        | [b01632df81](https://linux-hardware.org/?probe=b01632df81) | Dec 26, 2023 |
| HP            | 15 Notebook PC              | [0b603c74cf](https://linux-hardware.org/?probe=0b603c74cf) | Dec 26, 2023 |
| Acer          | Extensa 2519                | [29bc812d6d](https://linux-hardware.org/?probe=29bc812d6d) | Dec 23, 2023 |
| Acer          | Aspire A515-45              | [acab7c340a](https://linux-hardware.org/?probe=acab7c340a) | Dec 22, 2023 |
| Dell          | System Vostro 3750          | [aa1fb5d9a6](https://linux-hardware.org/?probe=aa1fb5d9a6) | Dec 21, 2023 |
| Dell          | Latitude E6320              | [a1e4b48d85](https://linux-hardware.org/?probe=a1e4b48d85) | Dec 20, 2023 |
| Lenovo        | ThinkPad T480 20L6S01W00    | [c38a7a8ad4](https://linux-hardware.org/?probe=c38a7a8ad4) | Dec 20, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [e3dded7dc3](https://linux-hardware.org/?probe=e3dded7dc3) | Dec 20, 2023 |
| Dell          | Inspiron 1750               | [508bf60ff7](https://linux-hardware.org/?probe=508bf60ff7) | Dec 20, 2023 |
| Dell          | Inspiron 1545               | [fc8665de21](https://linux-hardware.org/?probe=fc8665de21) | Dec 18, 2023 |
| Dell          | Precision 7530              | [6de510283f](https://linux-hardware.org/?probe=6de510283f) | Dec 18, 2023 |
| Apple         | MacBookAir9,1               | [73f451cbe0](https://linux-hardware.org/?probe=73f451cbe0) | Dec 17, 2023 |
| ASUSTek       | K53SC                       | [4424929359](https://linux-hardware.org/?probe=4424929359) | Dec 17, 2023 |
| Fujitsu       | LIFEBOOK U727               | [dceda9b2a1](https://linux-hardware.org/?probe=dceda9b2a1) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ead7baed80](https://linux-hardware.org/?probe=ead7baed80) | Dec 17, 2023 |
| ASUSTek       | S550CB                      | [20c9c415c9](https://linux-hardware.org/?probe=20c9c415c9) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [ae7d12ef06](https://linux-hardware.org/?probe=ae7d12ef06) | Dec 17, 2023 |
| ASUSTek       | K61IC                       | [1442626988](https://linux-hardware.org/?probe=1442626988) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [d34cfca6c8](https://linux-hardware.org/?probe=d34cfca6c8) | Dec 16, 2023 |
| MSI           | Modern 15 B5M               | [893ff177b3](https://linux-hardware.org/?probe=893ff177b3) | Dec 16, 2023 |
| AWOW          | Unknown                     | [7061726896](https://linux-hardware.org/?probe=7061726896) | Dec 16, 2023 |
| AZW           | GT-R                        | [205436106b](https://linux-hardware.org/?probe=205436106b) | Dec 16, 2023 |
| Dell          | Precision 7510              | [c70e7da2e8](https://linux-hardware.org/?probe=c70e7da2e8) | Dec 16, 2023 |
| Dell          | Latitude E5410              | [ee4251c01c](https://linux-hardware.org/?probe=ee4251c01c) | Dec 15, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e03062f53d](https://linux-hardware.org/?probe=e03062f53d) | Dec 15, 2023 |
| Lenovo        | ThinkPad L330 34701V0       | [d418989434](https://linux-hardware.org/?probe=d418989434) | Dec 15, 2023 |
| Medion        | E16401                      | [0c81bbcb2b](https://linux-hardware.org/?probe=0c81bbcb2b) | Dec 14, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [8374878f6a](https://linux-hardware.org/?probe=8374878f6a) | Dec 14, 2023 |
| Acer          | Nitro AN517-54              | [c16cb0947e](https://linux-hardware.org/?probe=c16cb0947e) | Dec 14, 2023 |
| HP            | Laptop 17-by4xxx            | [bb89121e0c](https://linux-hardware.org/?probe=bb89121e0c) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [9227c29b16](https://linux-hardware.org/?probe=9227c29b16) | Dec 14, 2023 |
| HP            | Laptop 17-by4xxx            | [0c728e7b27](https://linux-hardware.org/?probe=0c728e7b27) | Dec 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [bd8707be32](https://linux-hardware.org/?probe=bd8707be32) | Dec 13, 2023 |
| Dell          | Latitude E5470              | [cc7982deb0](https://linux-hardware.org/?probe=cc7982deb0) | Dec 13, 2023 |
| Dell          | Inspiron 1501               | [c4103f9e5c](https://linux-hardware.org/?probe=c4103f9e5c) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S792               | [811be0cce0](https://linux-hardware.org/?probe=811be0cce0) | Dec 13, 2023 |
| Acer          | Aspire E5-576               | [72fc5247a6](https://linux-hardware.org/?probe=72fc5247a6) | Dec 12, 2023 |
| Acer          | Aspire E5-571G              | [30c8f1f622](https://linux-hardware.org/?probe=30c8f1f622) | Dec 11, 2023 |
| ASUSTek       | K54L                        | [a50a95f076](https://linux-hardware.org/?probe=a50a95f076) | Dec 11, 2023 |
| Dell          | Latitude 5590               | [ebdbfc1740](https://linux-hardware.org/?probe=ebdbfc1740) | Dec 11, 2023 |
| Acer          | Aspire ES1-512              | [40438b3cd0](https://linux-hardware.org/?probe=40438b3cd0) | Dec 11, 2023 |
| Lenovo        | ThinkPad T410 2522V3S       | [7a6c259421](https://linux-hardware.org/?probe=7a6c259421) | Dec 10, 2023 |
| HP            | Laptop 14-bs0xx             | [f096c75cf9](https://linux-hardware.org/?probe=f096c75cf9) | Dec 10, 2023 |
| HP            | Notebook                    | [19c87ca6c5](https://linux-hardware.org/?probe=19c87ca6c5) | Dec 10, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [1709e5c519](https://linux-hardware.org/?probe=1709e5c519) | Dec 10, 2023 |
| HP            | Laptop 15-bw0xx             | [69ebcd04b9](https://linux-hardware.org/?probe=69ebcd04b9) | Dec 10, 2023 |
| MSI           | Katana GF66 11UE            | [451c5731ae](https://linux-hardware.org/?probe=451c5731ae) | Dec 09, 2023 |
| HP            | G61                         | [ce104b5b73](https://linux-hardware.org/?probe=ce104b5b73) | Dec 09, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [0d57f82fc5](https://linux-hardware.org/?probe=0d57f82fc5) | Dec 09, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [9b973fc192](https://linux-hardware.org/?probe=9b973fc192) | Dec 08, 2023 |
| Dell          | Latitude 7490               | [13759c617a](https://linux-hardware.org/?probe=13759c617a) | Dec 08, 2023 |
| HP            | ZBook 15v G5                | [96133249d0](https://linux-hardware.org/?probe=96133249d0) | Dec 08, 2023 |
| Adreamer      | Mybook PN1308P              | [e2dba2aff0](https://linux-hardware.org/?probe=e2dba2aff0) | Dec 08, 2023 |
| Lenovo        | ThinkPad T430 23498Y3       | [5382654b9b](https://linux-hardware.org/?probe=5382654b9b) | Dec 07, 2023 |
| Lenovo        | ThinkPad T440 20B7S0N10F    | [350da642e5](https://linux-hardware.org/?probe=350da642e5) | Dec 07, 2023 |
| Dell          | Precision 3550              | [da173d0ccc](https://linux-hardware.org/?probe=da173d0ccc) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [18d69df8d2](https://linux-hardware.org/?probe=18d69df8d2) | Dec 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3fce748548](https://linux-hardware.org/?probe=3fce748548) | Dec 06, 2023 |
| HP            | EliteBook 840 G1            | [923f26e8d8](https://linux-hardware.org/?probe=923f26e8d8) | Dec 06, 2023 |
| Packard Be... | DOT S                       | [131c38200b](https://linux-hardware.org/?probe=131c38200b) | Dec 06, 2023 |
| Dell          | Latitude E7440              | [6b3c7ea2b5](https://linux-hardware.org/?probe=6b3c7ea2b5) | Dec 06, 2023 |
| Dell          | Latitude 3330               | [843751ec33](https://linux-hardware.org/?probe=843751ec33) | Dec 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ee3494fa57](https://linux-hardware.org/?probe=ee3494fa57) | Dec 06, 2023 |
| ASUSTek       | N76VZ                       | [3d8844bc98](https://linux-hardware.org/?probe=3d8844bc98) | Dec 05, 2023 |
| Lenovo        | ThinkPad E15 20RD003KMH     | [d54efc5833](https://linux-hardware.org/?probe=d54efc5833) | Dec 05, 2023 |
| HP            | 15                          | [561269f586](https://linux-hardware.org/?probe=561269f586) | Dec 05, 2023 |
| Lenovo        | ThinkPad X390 20Q1S1WB00    | [ab1ae6521e](https://linux-hardware.org/?probe=ab1ae6521e) | Dec 05, 2023 |
| HP            | Laptop 15-dy2xxx            | [729837dc5c](https://linux-hardware.org/?probe=729837dc5c) | Dec 05, 2023 |
| HP            | ProBook 650 G1              | [b4b71ada44](https://linux-hardware.org/?probe=b4b71ada44) | Dec 04, 2023 |
| HP            | Pavilion 15                 | [15b5925773](https://linux-hardware.org/?probe=15b5925773) | Dec 04, 2023 |
| HP            | ProBook 4330s               | [48a060af86](https://linux-hardware.org/?probe=48a060af86) | Dec 04, 2023 |
| Lenovo        | ThinkPad L460 20FVS07C00    | [fd5a4dbeb9](https://linux-hardware.org/?probe=fd5a4dbeb9) | Dec 04, 2023 |
| Lenovo        | B50-50 80S2                 | [6150907e1e](https://linux-hardware.org/?probe=6150907e1e) | Dec 04, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [9acc9cef23](https://linux-hardware.org/?probe=9acc9cef23) | Dec 04, 2023 |
| Toshiba       | Satellite A300              | [5817017508](https://linux-hardware.org/?probe=5817017508) | Dec 04, 2023 |
| Dell          | XPS 13 9350                 | [aec9f3cb3c](https://linux-hardware.org/?probe=aec9f3cb3c) | Dec 04, 2023 |
| Toshiba       | Satellite C855D             | [84e97d4578](https://linux-hardware.org/?probe=84e97d4578) | Dec 04, 2023 |
| HP            | ProBook 640 G1              | [287093ae53](https://linux-hardware.org/?probe=287093ae53) | Dec 03, 2023 |
| Dell          | Latitude D630               | [84a1008ee2](https://linux-hardware.org/?probe=84a1008ee2) | Dec 03, 2023 |
| ASUSTek       | K53SJ                       | [50979ecbd2](https://linux-hardware.org/?probe=50979ecbd2) | Dec 03, 2023 |
| Dell          | Latitude E6410              | [bae67b7a50](https://linux-hardware.org/?probe=bae67b7a50) | Dec 03, 2023 |
| HP            | ENVY m6                     | [3a3cde32ab](https://linux-hardware.org/?probe=3a3cde32ab) | Dec 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [e7c23bf6d5](https://linux-hardware.org/?probe=e7c23bf6d5) | Dec 03, 2023 |
| Medion        | E6214                       | [f5e38ac376](https://linux-hardware.org/?probe=f5e38ac376) | Dec 03, 2023 |
| HP            | ZBook 15 G2                 | [f60bc8a984](https://linux-hardware.org/?probe=f60bc8a984) | Dec 03, 2023 |
| Acer          | Aspire 8951G                | [f98b449dba](https://linux-hardware.org/?probe=f98b449dba) | Dec 03, 2023 |
| Dell          | Inspiron 13-5378            | [0beeed51bc](https://linux-hardware.org/?probe=0beeed51bc) | Dec 03, 2023 |
| Lenovo        | ThinkPad T530 2429F37       | [7db847c98e](https://linux-hardware.org/?probe=7db847c98e) | Dec 03, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [13816c1292](https://linux-hardware.org/?probe=13816c1292) | Dec 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9d3a34c3da](https://linux-hardware.org/?probe=9d3a34c3da) | Dec 02, 2023 |
| ASUSTek       | F3E                         | [26a960dd12](https://linux-hardware.org/?probe=26a960dd12) | Dec 02, 2023 |
| Dell          | Precision 5520              | [aa1a1feefc](https://linux-hardware.org/?probe=aa1a1feefc) | Dec 02, 2023 |
| Dell          | Latitude E6510              | [0c49353fa5](https://linux-hardware.org/?probe=0c49353fa5) | Dec 02, 2023 |
| MSI           | Modern 14 B5M               | [c22637e524](https://linux-hardware.org/?probe=c22637e524) | Dec 02, 2023 |
| Toshiba       | Satellite C650D             | [704507bfd5](https://linux-hardware.org/?probe=704507bfd5) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [7ddcba051c](https://linux-hardware.org/?probe=7ddcba051c) | Dec 02, 2023 |
| HP            | Pavilion g7                 | [5c596e9e4f](https://linux-hardware.org/?probe=5c596e9e4f) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [58a0ae4fcc](https://linux-hardware.org/?probe=58a0ae4fcc) | Dec 02, 2023 |
| Lenovo        | G585                        | [a62a35b461](https://linux-hardware.org/?probe=a62a35b461) | Dec 01, 2023 |
| HP            | Pavilion dv7                | [dc015f1023](https://linux-hardware.org/?probe=dc015f1023) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [32a0e568cc](https://linux-hardware.org/?probe=32a0e568cc) | Dec 01, 2023 |
| Acer          | Aspire A317-51K             | [aa5652abe0](https://linux-hardware.org/?probe=aa5652abe0) | Dec 01, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7eb86d01c5](https://linux-hardware.org/?probe=7eb86d01c5) | Dec 01, 2023 |
| Dell          | Inspiron 1545               | [7fbbf18938](https://linux-hardware.org/?probe=7fbbf18938) | Dec 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | [679acd4c7a](https://linux-hardware.org/?probe=679acd4c7a) | Dec 01, 2023 |
| Packard Be... | EasyNote LJ75               | [0f21e6cb39](https://linux-hardware.org/?probe=0f21e6cb39) | Dec 01, 2023 |
| Acer          | Aspire 5732Z                | [f79a825fcd](https://linux-hardware.org/?probe=f79a825fcd) | Dec 01, 2023 |
| Dell          | Latitude E5410              | [074e7de8d8](https://linux-hardware.org/?probe=074e7de8d8) | Dec 01, 2023 |
| Acer          | Aspire A114-31              | [1eb938404f](https://linux-hardware.org/?probe=1eb938404f) | Dec 01, 2023 |
| HP            | Laptop 14-ck0xxx            | [40a0a394cc](https://linux-hardware.org/?probe=40a0a394cc) | Dec 01, 2023 |
| Dell          | Inspiron 5558               | [49c6f0b57f](https://linux-hardware.org/?probe=49c6f0b57f) | Dec 01, 2023 |
| Apple         | MacBookPro8,1               | [ad16e37b50](https://linux-hardware.org/?probe=ad16e37b50) | Dec 01, 2023 |
| Dell          | Latitude E6440              | [4459a634ca](https://linux-hardware.org/?probe=4459a634ca) | Dec 01, 2023 |
| Toshiba       | Satellite L755              | [511b79d4dc](https://linux-hardware.org/?probe=511b79d4dc) | Nov 30, 2023 |
| Dell          | Inspiron 15 3515            | [162854d649](https://linux-hardware.org/?probe=162854d649) | Nov 30, 2023 |
| Acer          | Aspire V5-591G              | [fcb901f377](https://linux-hardware.org/?probe=fcb901f377) | Nov 30, 2023 |
| Acer          | Aspire A315-35              | [dad806dd8b](https://linux-hardware.org/?probe=dad806dd8b) | Nov 30, 2023 |
| Toshiba       | Satellite C660              | [03de11e5b3](https://linux-hardware.org/?probe=03de11e5b3) | Nov 30, 2023 |
| Toshiba       | Satellite C850-19D          | [cd9dbac72b](https://linux-hardware.org/?probe=cd9dbac72b) | Nov 30, 2023 |
| HP            | Laptop 15-bs1xx             | [e8f82bc03f](https://linux-hardware.org/?probe=e8f82bc03f) | Nov 29, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b682c56733](https://linux-hardware.org/?probe=b682c56733) | Nov 29, 2023 |
| eMachines     | eME440                      | [a622dddd66](https://linux-hardware.org/?probe=a622dddd66) | Nov 29, 2023 |
| HUAWEI        | NbDE-WXX9                   | [8fc5d22e76](https://linux-hardware.org/?probe=8fc5d22e76) | Nov 29, 2023 |
| HP            | 250 G7 Notebook PC          | [395fbd2b48](https://linux-hardware.org/?probe=395fbd2b48) | Nov 29, 2023 |
| HP            | Laptop 17-by3xxx            | [63860f689c](https://linux-hardware.org/?probe=63860f689c) | Nov 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [685ce27fae](https://linux-hardware.org/?probe=685ce27fae) | Nov 29, 2023 |
| TUXEDO        | Book BA1510                 | [0c59322d62](https://linux-hardware.org/?probe=0c59322d62) | Nov 29, 2023 |
| HP            | Laptop 14s-fq0xxx           | [cc31cdf621](https://linux-hardware.org/?probe=cc31cdf621) | Nov 29, 2023 |
| HUAWEI        | RLEF-XX                     | [9b8fabda07](https://linux-hardware.org/?probe=9b8fabda07) | Nov 29, 2023 |
| Acer          | TravelMate P614-51-G2       | [17c4552f25](https://linux-hardware.org/?probe=17c4552f25) | Nov 29, 2023 |
| Lenovo        | ThinkPad X201 3323BSG       | [e0ad13d1e8](https://linux-hardware.org/?probe=e0ad13d1e8) | Nov 29, 2023 |
| Fujitsu       | FMVNS6HE                    | [df459431eb](https://linux-hardware.org/?probe=df459431eb) | Nov 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [066daf7cac](https://linux-hardware.org/?probe=066daf7cac) | Nov 29, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | [6af16f3cbb](https://linux-hardware.org/?probe=6af16f3cbb) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [7ca8c7adc5](https://linux-hardware.org/?probe=7ca8c7adc5) | Nov 29, 2023 |
| HP            | Compaq 6730s                | [ff2ae39e03](https://linux-hardware.org/?probe=ff2ae39e03) | Nov 29, 2023 |
| Lenovo        | ThinkPad R500 27148UG       | [546c56f7bb](https://linux-hardware.org/?probe=546c56f7bb) | Nov 28, 2023 |
| HP            | Compaq 610                  | [f0022a2c56](https://linux-hardware.org/?probe=f0022a2c56) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [577a8fa908](https://linux-hardware.org/?probe=577a8fa908) | Nov 28, 2023 |
| Dell          | Inspiron 15 3515            | [20007eacdb](https://linux-hardware.org/?probe=20007eacdb) | Nov 28, 2023 |
| Dell          | Inspiron 15 3515            | [e41d34ea1c](https://linux-hardware.org/?probe=e41d34ea1c) | Nov 28, 2023 |
| Sony          | VPCEL1E1E                   | [9c88ceb0b0](https://linux-hardware.org/?probe=9c88ceb0b0) | Nov 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [11d4048dc9](https://linux-hardware.org/?probe=11d4048dc9) | Nov 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | [34f3153910](https://linux-hardware.org/?probe=34f3153910) | Nov 28, 2023 |
| HP            | Laptop 15-db1xxx            | [52a0c464fe](https://linux-hardware.org/?probe=52a0c464fe) | Nov 28, 2023 |
| Samsung       | RV413/RV513                 | [42fb4ae911](https://linux-hardware.org/?probe=42fb4ae911) | Nov 28, 2023 |
| Acer          | Aspire E5-521G              | [d639f77bd9](https://linux-hardware.org/?probe=d639f77bd9) | Nov 28, 2023 |
| Lenovo        | ThinkPad T540p 20BFS31F0... | [8db080dffe](https://linux-hardware.org/?probe=8db080dffe) | Nov 28, 2023 |
| Acer          | Aspire A315-57G             | [10678fbceb](https://linux-hardware.org/?probe=10678fbceb) | Nov 28, 2023 |
| Google        | Fleex                       | [0f905372c0](https://linux-hardware.org/?probe=0f905372c0) | Nov 28, 2023 |
| HP            | Laptop 15-dy2xxx            | [c56c2fcff2](https://linux-hardware.org/?probe=c56c2fcff2) | Nov 28, 2023 |
| HUAWEI        | MACH-WX9                    | [a09dd535a7](https://linux-hardware.org/?probe=a09dd535a7) | Nov 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34603... | [edb57fe6c8](https://linux-hardware.org/?probe=edb57fe6c8) | Nov 28, 2023 |
| HP            | Pavilion Notebook           | [39dd843280](https://linux-hardware.org/?probe=39dd843280) | Nov 28, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [b3bea8127f](https://linux-hardware.org/?probe=b3bea8127f) | Nov 27, 2023 |
| Apple         | MacBookPro10,1              | [3982dc173a](https://linux-hardware.org/?probe=3982dc173a) | Nov 27, 2023 |
| Machcreato... | 14X                         | [25e406809e](https://linux-hardware.org/?probe=25e406809e) | Nov 27, 2023 |
| ASUSTek       | K73SD                       | [cd71879827](https://linux-hardware.org/?probe=cd71879827) | Nov 27, 2023 |
| Timi          | TM1701                      | [dfb21da820](https://linux-hardware.org/?probe=dfb21da820) | Nov 27, 2023 |
| Dell          | Latitude 3350               | [395158b705](https://linux-hardware.org/?probe=395158b705) | Nov 27, 2023 |
| MSI           | CR620                       | [336d403e1b](https://linux-hardware.org/?probe=336d403e1b) | Nov 27, 2023 |
| Dell          | Inspiron 1012               | [ffe483f5fd](https://linux-hardware.org/?probe=ffe483f5fd) | Nov 27, 2023 |
| HP            | 250 G6 Notebook PC          | [936970029f](https://linux-hardware.org/?probe=936970029f) | Nov 27, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [02f1616520](https://linux-hardware.org/?probe=02f1616520) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0ddcbc9eb9](https://linux-hardware.org/?probe=0ddcbc9eb9) | Nov 27, 2023 |
| Samsung       | 910S3L/911S3L               | [5356e7f33b](https://linux-hardware.org/?probe=5356e7f33b) | Nov 27, 2023 |
| Lenovo        | ThinkPad T520 4242AU2       | [71ffabfcb1](https://linux-hardware.org/?probe=71ffabfcb1) | Nov 27, 2023 |
| Lenovo        | V340-17IWL 81RG             | [c2a7190ba8](https://linux-hardware.org/?probe=c2a7190ba8) | Nov 27, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [be532e0503](https://linux-hardware.org/?probe=be532e0503) | Nov 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [cb6d17a69a](https://linux-hardware.org/?probe=cb6d17a69a) | Nov 26, 2023 |
| HP            | Pavilion dv7                | [940ce7b8ed](https://linux-hardware.org/?probe=940ce7b8ed) | Nov 26, 2023 |
| HP            | Compaq Presario CQ60        | [acd145c278](https://linux-hardware.org/?probe=acd145c278) | Nov 26, 2023 |
| Dell          | XPS 13 9300                 | [68ba1c0162](https://linux-hardware.org/?probe=68ba1c0162) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [e552669069](https://linux-hardware.org/?probe=e552669069) | Nov 26, 2023 |
| Philco        | 14H                         | [f4256fe390](https://linux-hardware.org/?probe=f4256fe390) | Nov 26, 2023 |
| Acer          | Swift SF514-56T             | [687fc34fd5](https://linux-hardware.org/?probe=687fc34fd5) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [435a764eeb](https://linux-hardware.org/?probe=435a764eeb) | Nov 26, 2023 |
| Dell          | Inspiron 5770               | [c35b932f41](https://linux-hardware.org/?probe=c35b932f41) | Nov 26, 2023 |
| Lenovo        | G580 20157                  | [f03f814b9c](https://linux-hardware.org/?probe=f03f814b9c) | Nov 26, 2023 |
| Lenovo        | G50-45 80E3                 | [6f475bfe64](https://linux-hardware.org/?probe=6f475bfe64) | Nov 26, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TM... | [c333f48b93](https://linux-hardware.org/?probe=c333f48b93) | Nov 26, 2023 |
| Chuwi         | GemiBook Plus               | [6316398e5b](https://linux-hardware.org/?probe=6316398e5b) | Nov 26, 2023 |
| ASUSTek       | X75VC                       | [be2ff8350a](https://linux-hardware.org/?probe=be2ff8350a) | Nov 26, 2023 |
| Lenovo        | ThinkPad Edge E325 12973... | [0f165c67ac](https://linux-hardware.org/?probe=0f165c67ac) | Nov 26, 2023 |
| HP            | EliteBook 8570p             | [f31c8412d9](https://linux-hardware.org/?probe=f31c8412d9) | Nov 26, 2023 |
| HP            | 255 G8 Notebook PC          | [f889c15ce7](https://linux-hardware.org/?probe=f889c15ce7) | Nov 26, 2023 |
| HP            | Pavilion dv6                | [2f757867e7](https://linux-hardware.org/?probe=2f757867e7) | Nov 26, 2023 |
| Acer          | Aspire S5-371               | [d3efa32b61](https://linux-hardware.org/?probe=d3efa32b61) | Nov 26, 2023 |
| HP            | Laptop 14-dk1xxx            | [eb3634e98f](https://linux-hardware.org/?probe=eb3634e98f) | Nov 26, 2023 |
| Dell          | Precision 7520              | [26c0a80c45](https://linux-hardware.org/?probe=26c0a80c45) | Nov 26, 2023 |
| Unknown       | Unknown                     | [2b84a63677](https://linux-hardware.org/?probe=2b84a63677) | Nov 26, 2023 |
| Lenovo        | IdeaPad Y580                | [c17c868d52](https://linux-hardware.org/?probe=c17c868d52) | Nov 26, 2023 |
| Lenovo        | ThinkPad T450 20BUS20301    | [4d8f1df3d2](https://linux-hardware.org/?probe=4d8f1df3d2) | Nov 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [721fac0123](https://linux-hardware.org/?probe=721fac0123) | Nov 26, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [79c8961819](https://linux-hardware.org/?probe=79c8961819) | Nov 26, 2023 |
| Toshiba       | Satellite L55t-A            | [b037dccb20](https://linux-hardware.org/?probe=b037dccb20) | Nov 25, 2023 |
| Lenovo        | ThinkPad X201 3680WFQ       | [3b6eaf2c6e](https://linux-hardware.org/?probe=3b6eaf2c6e) | Nov 25, 2023 |
| Dell          | Precision M6700             | [1817097d25](https://linux-hardware.org/?probe=1817097d25) | Nov 25, 2023 |
| Dell          | Latitude 5511               | [254abd404f](https://linux-hardware.org/?probe=254abd404f) | Nov 25, 2023 |
| HP            | ProBook 5330m               | [74e3bacd14](https://linux-hardware.org/?probe=74e3bacd14) | Nov 25, 2023 |
| Acer          | Aspire A515-52G             | [5b0ff6d81a](https://linux-hardware.org/?probe=5b0ff6d81a) | Nov 25, 2023 |
| Alienware     | x14                         | [af501023a5](https://linux-hardware.org/?probe=af501023a5) | Nov 25, 2023 |
| Packard Be... | EasyNote TS11HR             | [cf23a5df5b](https://linux-hardware.org/?probe=cf23a5df5b) | Nov 25, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 6.6.2-desktop-1omv2390       | 376       | 98.95%  |
| 6.7.0-desktop-0.rc2.1omv2390 | 2         | 0.53%   |
| 6.6.1-desktop-1omv2390       | 2         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6.2   | 376       | 98.95%  |
| 6.7.0   | 2         | 0.53%   |
| 6.6.1   | 2         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6     | 378       | 99.47%  |
| 6.7     | 2         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 380       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 267       | 70.26%  |
| LXQt    | 72        | 18.95%  |
| GNOME   | 40        | 10.53%  |
| Unknown | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 369       | 97.11%  |
| X11     | 10        | 2.63%   |
| Unknown | 1         | 0.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 340       | 89.47%  |
| GDM  | 40        | 10.53%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 197       | 51.84%  |
| pl_PL | 30        | 7.89%   |
| fr_FR | 29        | 7.63%   |
| de_DE | 28        | 7.37%   |
| ru_RU | 24        | 6.32%   |
| it_IT | 13        | 3.42%   |
| pt_BR | 10        | 2.63%   |
| cs_CZ | 9         | 2.37%   |
| es_ES | 8         | 2.11%   |
| en_GB | 6         | 1.58%   |
| tr_TR | 3         | 0.79%   |
| hu_HU | 3         | 0.79%   |
| en_CA | 3         | 0.79%   |
| pt_PT | 2         | 0.53%   |
| ja_JP | 2         | 0.53%   |
| en_NZ | 2         | 0.53%   |
| de_CH | 2         | 0.53%   |
| UTF-8 | 1         | 0.26%   |
| es_MX | 1         | 0.26%   |
| es_BO | 1         | 0.26%   |
| es_AR | 1         | 0.26%   |
| en_NG | 1         | 0.26%   |
| en_IN | 1         | 0.26%   |
| en_IL | 1         | 0.26%   |
| en_HK | 1         | 0.26%   |
| en_AU | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 246       | 64.74%  |
| BIOS | 134       | 35.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Overlay | 229       | 60.26%  |
| Ext4    | 137       | 36.05%  |
| Btrfs   | 9         | 2.37%   |
| Xfs     | 3         | 0.79%   |
| F2fs    | 2         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 299       | 78.68%  |
| MBR  | 81        | 21.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 51.58%  |
| No        | 184       | 48.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 236       | 62.11%  |
| Yes       | 144       | 37.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 78        | 20.53%  |
| Lenovo                  | 74        | 19.47%  |
| Dell                    | 60        | 15.79%  |
| ASUSTek Computer        | 50        | 13.16%  |
| Acer                    | 32        | 8.42%   |
| Toshiba                 | 17        | 4.47%   |
| MSI                     | 6         | 1.58%   |
| Fujitsu                 | 6         | 1.58%   |
| Apple                   | 6         | 1.58%   |
| Sony                    | 4         | 1.05%   |
| Packard Bell            | 4         | 1.05%   |
| HUAWEI                  | 4         | 1.05%   |
| TUXEDO                  | 3         | 0.79%   |
| Samsung Electronics     | 3         | 0.79%   |
| Google                  | 3         | 0.79%   |
| EVOO                    | 3         | 0.79%   |
| eMachines               | 3         | 0.79%   |
| Timi                    | 2         | 0.53%   |
| Medion                  | 2         | 0.53%   |
| Login Informatica       | 2         | 0.53%   |
| Info Quest Technologies | 2         | 0.53%   |
| Chuwi                   | 2         | 0.53%   |
| SLIMBOOK                | 1         | 0.26%   |
| Razer                   | 1         | 0.26%   |
| Philco                  | 1         | 0.26%   |
| Notebook                | 1         | 0.26%   |
| NEC Computers           | 1         | 0.26%   |
| Metabox                 | 1         | 0.26%   |
| Machcreator             | 1         | 0.26%   |
| LG Electronics          | 1         | 0.26%   |
| AZW                     | 1         | 0.26%   |
| AWOW                    | 1         | 0.26%   |
| ARCELIK                 | 1         | 0.26%   |
| Alienware               | 1         | 0.26%   |
| Adreamer                | 1         | 0.26%   |
| Unknown                 | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 15 3515                    | 5         | 1.32%   |
| HP Compaq 610                            | 4         | 1.05%   |
| Unknown                                  | 4         | 1.05%   |
| HP Pavilion dv7                          | 3         | 0.79%   |
| EVOO TEV-CE-141-2                        | 3         | 0.79%   |
| Toshiba Satellite C660                   | 2         | 0.53%   |
| Toshiba Satellite C650                   | 2         | 0.53%   |
| Lenovo IdeaPad 330S-15IKB 81F5           | 2         | 0.53%   |
| Info Quest GTN1402 4-64                  | 2         | 0.53%   |
| HP ProBook 640 G1                        | 2         | 0.53%   |
| HP Pavilion Gaming Laptop 15-ec0xxx      | 2         | 0.53%   |
| HP Notebook                              | 2         | 0.53%   |
| HP Laptop 17-by4xxx                      | 2         | 0.53%   |
| HP Laptop 15-dy2xxx                      | 2         | 0.53%   |
| HP Compaq 6730s                          | 2         | 0.53%   |
| HP 250 G7 Notebook PC                    | 2         | 0.53%   |
| HP 15                                    | 2         | 0.53%   |
| Dell Latitude E5550                      | 2         | 0.53%   |
| Dell Latitude E5470                      | 2         | 0.53%   |
| Dell Latitude E5430 non-vPro             | 2         | 0.53%   |
| Dell Latitude E5410                      | 2         | 0.53%   |
| Dell Inspiron 7720                       | 2         | 0.53%   |
| Dell Inspiron 1545                       | 2         | 0.53%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA   | 2         | 0.53%   |
| ASUS VivoBook_ASUSLaptop X1603ZA_X1603ZA | 2         | 0.53%   |
| Apple MacBookAir9,1                      | 2         | 0.53%   |
| Acer Aspire ES1-531                      | 2         | 0.53%   |
| Acer Aspire E5-571G                      | 2         | 0.53%   |
| TUXEDO Pulse 15 Gen1                     | 1         | 0.26%   |
| TUXEDO Book BM15 Gen10                   | 1         | 0.26%   |
| TUXEDO Book BA1510                       | 1         | 0.26%   |
| Toshiba Satellite U500                   | 1         | 0.26%   |
| Toshiba Satellite S855D                  | 1         | 0.26%   |
| Toshiba Satellite L755                   | 1         | 0.26%   |
| Toshiba Satellite L700                   | 1         | 0.26%   |
| Toshiba Satellite L55t-A                 | 1         | 0.26%   |
| Toshiba Satellite L55D-B                 | 1         | 0.26%   |
| Toshiba Satellite C855D                  | 1         | 0.26%   |
| Toshiba Satellite C850-19D               | 1         | 0.26%   |
| Toshiba Satellite C650D                  | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 35        | 9.21%   |
| Acer Aspire           | 26        | 6.84%   |
| Lenovo IdeaPad        | 23        | 6.05%   |
| Dell Latitude         | 22        | 5.79%   |
| Dell Inspiron         | 22        | 5.79%   |
| HP Laptop             | 20        | 5.26%   |
| Toshiba Satellite     | 14        | 3.68%   |
| ASUS VivoBook         | 14        | 3.68%   |
| HP Pavilion           | 10        | 2.63%   |
| HP ProBook            | 8         | 2.11%   |
| HP Compaq             | 8         | 2.11%   |
| Dell Precision        | 7         | 1.84%   |
| HP EliteBook          | 6         | 1.58%   |
| HP 250                | 4         | 1.05%   |
| Fujitsu LIFEBOOK      | 4         | 1.05%   |
| Unknown               | 4         | 1.05%   |
| Packard Bell EasyNote | 3         | 0.79%   |
| MSI Modern            | 3         | 0.79%   |
| HP 15                 | 3         | 0.79%   |
| EVOO TEV-CE-141-2     | 3         | 0.79%   |
| Dell XPS              | 3         | 0.79%   |
| TUXEDO Book           | 2         | 0.53%   |
| Toshiba PORTEGE       | 2         | 0.53%   |
| Lenovo Legion         | 2         | 0.53%   |
| Info Quest GTN1402    | 2         | 0.53%   |
| HP ZBook              | 2         | 0.53%   |
| HP Stream             | 2         | 0.53%   |
| HP Notebook           | 2         | 0.53%   |
| HP 240                | 2         | 0.53%   |
| Dell Vostro           | 2         | 0.53%   |
| ASUS ROG              | 2         | 0.53%   |
| ASUS ASUS             | 2         | 0.53%   |
| Apple MacBookAir9     | 2         | 0.53%   |
| Acer Extensa          | 2         | 0.53%   |
| TUXEDO Pulse          | 1         | 0.26%   |
| Toshiba Portable      | 1         | 0.26%   |
| Timi TM1701           | 1         | 0.26%   |
| Timi Redmi            | 1         | 0.26%   |
| Sony VPCEL1E1E        | 1         | 0.26%   |
| Sony VPCEH3P1E        | 1         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 36        | 9.47%   |
| 2012 | 35        | 9.21%   |
| 2020 | 32        | 8.42%   |
| 2011 | 29        | 7.63%   |
| 2013 | 26        | 6.84%   |
| 2022 | 23        | 6.05%   |
| 2015 | 23        | 6.05%   |
| 2017 | 22        | 5.79%   |
| 2019 | 20        | 5.26%   |
| 2018 | 20        | 5.26%   |
| 2014 | 20        | 5.26%   |
| 2010 | 20        | 5.26%   |
| 2016 | 18        | 4.74%   |
| 2008 | 17        | 4.47%   |
| 2009 | 14        | 3.68%   |
| 2023 | 11        | 2.89%   |
| 2007 | 10        | 2.63%   |
| 2006 | 4         | 1.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 380       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 380       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 377       | 99.21%  |
| Yes  | 3         | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 111       | 29.21%  |
| 3.01-4.0    | 105       | 27.63%  |
| 8.01-16.0   | 60        | 15.79%  |
| 16.01-24.0  | 55        | 14.47%  |
| 1.01-2.0    | 18        | 4.74%   |
| 32.01-64.0  | 13        | 3.42%   |
| 2.01-3.0    | 10        | 2.63%   |
| 24.01-32.0  | 6         | 1.58%   |
| 64.01-256.0 | 1         | 0.26%   |
| 0.51-1.0    | 1         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 245       | 64.3%   |
| 2.01-3.0  | 61        | 16.01%  |
| 0.51-1.0  | 53        | 13.91%  |
| 3.01-4.0  | 16        | 4.2%    |
| 0.01-0.5  | 4         | 1.05%   |
| 4.01-8.0  | 1         | 0.26%   |
| 8.01-16.0 | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 263       | 69.21%  |
| 2      | 95        | 25%     |
| 3      | 16        | 4.21%   |
| 4      | 2         | 0.53%   |
| 0      | 2         | 0.53%   |
| 13     | 1         | 0.26%   |
| 5      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 219       | 57.63%  |
| Yes       | 161       | 42.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 298       | 78.42%  |
| No        | 82        | 21.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 378       | 99.47%  |
| No        | 2         | 0.53%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 301       | 79.21%  |
| No        | 79        | 20.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 65        | 17.11%  |
| Germany             | 40        | 10.53%  |
| Poland              | 36        | 9.47%   |
| Russia              | 32        | 8.42%   |
| France              | 27        | 7.11%   |
| Italy               | 18        | 4.74%   |
| Brazil              | 18        | 4.74%   |
| Czechia             | 12        | 3.16%   |
| Spain               | 11        | 2.89%   |
| Japan               | 10        | 2.63%   |
| Hungary             | 9         | 2.37%   |
| Turkey              | 8         | 2.11%   |
| Canada              | 8         | 2.11%   |
| Indonesia           | 7         | 1.84%   |
| UK                  | 6         | 1.58%   |
| Norway              | 5         | 1.32%   |
| Belgium             | 5         | 1.32%   |
| Netherlands         | 4         | 1.05%   |
| Switzerland         | 3         | 0.79%   |
| Portugal            | 3         | 0.79%   |
| Mexico              | 3         | 0.79%   |
| Cyprus              | 3         | 0.79%   |
| Thailand            | 2         | 0.53%   |
| Romania             | 2         | 0.53%   |
| New Zealand         | 2         | 0.53%   |
| Morocco             | 2         | 0.53%   |
| Malaysia            | 2         | 0.53%   |
| Lithuania           | 2         | 0.53%   |
| India               | 2         | 0.53%   |
| Grenada             | 2         | 0.53%   |
| Greece              | 2         | 0.53%   |
| Finland             | 2         | 0.53%   |
| China               | 2         | 0.53%   |
| Belarus             | 2         | 0.53%   |
| Austria             | 2         | 0.53%   |
| Australia           | 2         | 0.53%   |
| Vietnam             | 1         | 0.26%   |
| Ukraine             | 1         | 0.26%   |
| Trinidad and Tobago | 1         | 0.26%   |
| Sudan               | 1         | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Prague         | 8         | 2.11%   |
| Warsaw         | 6         | 1.58%   |
| Paris          | 5         | 1.32%   |
| Oliveira       | 5         | 1.32%   |
| Poznan         | 4         | 1.05%   |
| Budapest       | 4         | 1.05%   |
| Stuhr          | 3         | 0.79%   |
| San Pedro      | 3         | 0.79%   |
| Moscow         | 3         | 0.79%   |
| Montreal       | 3         | 0.79%   |
| Milan          | 3         | 0.79%   |
| Limassol       | 3         | 0.79%   |
| Hanover        | 3         | 0.79%   |
| Érd           | 3         | 0.79%   |
| Wroclaw        | 2         | 0.53%   |
| Voronezh       | 2         | 0.53%   |
| Uberlingen     | 2         | 0.53%   |
| Tokyo          | 2         | 0.53%   |
| St Petersburg  | 2         | 0.53%   |
| Sao Paulo      | 2         | 0.53%   |
| Salvador       | 2         | 0.53%   |
| Saint George's | 2         | 0.53%   |
| Rome           | 2         | 0.53%   |
| Rimini         | 2         | 0.53%   |
| Olsztyn        | 2         | 0.53%   |
| Nagoya         | 2         | 0.53%   |
| Munich         | 2         | 0.53%   |
| Lublin         | 2         | 0.53%   |
| Le Grau-du-Roi | 2         | 0.53%   |
| Kraszew        | 2         | 0.53%   |
| Krasnoyarsk    | 2         | 0.53%   |
| Krasnodar      | 2         | 0.53%   |
| Katowice       | 2         | 0.53%   |
| Hot Springs    | 2         | 0.53%   |
| Glen Burnie    | 2         | 0.53%   |
| Bialystok      | 2         | 0.53%   |
| Beverly Hills  | 2         | 0.53%   |
| Berlin         | 2         | 0.53%   |
| Bekasi         | 2         | 0.53%   |
| Barnaul        | 2         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 66        | 66     | 13.58%  |
| Samsung Electronics         | 61        | 70     | 12.55%  |
| Seagate                     | 43        | 43     | 8.85%   |
| Toshiba                     | 28        | 29     | 5.76%   |
| SanDisk                     | 27        | 29     | 5.56%   |
| Kingston                    | 27        | 27     | 5.56%   |
| Unknown                     | 17        | 19     | 3.5%    |
| Micron Technology           | 15        | 17     | 3.09%   |
| Hitachi                     | 15        | 15     | 3.09%   |
| Crucial                     | 15        | 15     | 3.09%   |
| Unknown                     | 14        | 14     | 2.88%   |
| SK hynix                    | 12        | 12     | 2.47%   |
| JMicron Technology          | 10        | 10     | 2.06%   |
| HGST                        | 10        | 10     | 2.06%   |
| SPCC                        | 9         | 9      | 1.85%   |
| Intel                       | 9         | 9      | 1.85%   |
| China                       | 8         | 8      | 1.65%   |
| Intenso                     | 7         | 7      | 1.44%   |
| A-DATA Technology           | 5         | 5      | 1.03%   |
| KingSpec                    | 4         | 4      | 0.82%   |
| GOODRAM                     | 4         | 4      | 0.82%   |
| UMIS                        | 3         | 3      | 0.62%   |
| SSSTC                       | 3         | 3      | 0.62%   |
| Lexar                       | 3         | 3      | 0.62%   |
| Kingston Technology Company | 3         | 3      | 0.62%   |
| Hewlett-Packard             | 3         | 3      | 0.62%   |
| Apple                       | 3         | 3      | 0.62%   |
| Transcend                   | 2         | 2      | 0.41%   |
| Team                        | 2         | 2      | 0.41%   |
| Silicon Motion              | 2         | 2      | 0.41%   |
| SABRENT                     | 2         | 3      | 0.41%   |
| RX7                         | 2         | 2      | 0.41%   |
| PNY                         | 2         | 2      | 0.41%   |
| MSI                         | 2         | 2      | 0.41%   |
| JetFlash                    | 2         | 2      | 0.41%   |
| HS-SSD-E100                 | 2         | 2      | 0.41%   |
| Gigabyte Technology         | 2         | 2      | 0.41%   |
| FORESEE                     | 2         | 2      | 0.41%   |
| Dahua                       | 2         | 3      | 0.41%   |
| ASMT                        | 2         | 2      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 14        | 2.83%   |
| SanDisk NVMe SSD Drive 1TB           | 8         | 1.62%   |
| JMicron Generic 320GB                | 7         | 1.42%   |
| Toshiba MQ04ABF100 1TB               | 6         | 1.21%   |
| Seagate ST500LT012-1DG142 500GB      | 6         | 1.21%   |
| Kingston SNVS500G 500GB              | 5         | 1.01%   |
| Kingston SA400S37240G 240GB SSD      | 5         | 1.01%   |
| Unknown SD/MMC/MS PRO 128GB          | 4         | 0.81%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 0.81%   |
| Micron 2210_MTFDHBA512QFD 512GB      | 4         | 0.81%   |
| SPCC M.2 PCIe SSD 512GB              | 3         | 0.61%   |
| Seagate ST9500325AS 500GB            | 3         | 0.61%   |
| Seagate ST9320423AS 320GB            | 3         | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.61%   |
| Samsung SSD 870 QVO 1TB              | 3         | 0.61%   |
| Kingston Company SNV2S1000G 1TB      | 3         | 0.61%   |
| JMicron Tech 250GB                   | 3         | 0.61%   |
| Hitachi HTS545032B9A300 320GB        | 3         | 0.61%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 0.61%   |
| HGST HTS545050A7E680 500GB           | 3         | 0.61%   |
| Crucial CT480BX500SSD1 480GB         | 3         | 0.61%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 2         | 0.4%    |
| WDC WD7500BPVX-16JC3T3 752GB         | 2         | 0.4%    |
| WDC WD5000LPLX-08ZNTT0 500GB         | 2         | 0.4%    |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.4%    |
| WDC WD5000LPCX-21VHAT0 500GB         | 2         | 0.4%    |
| WDC WD5000BPKT-75PK4T0 500GB         | 2         | 0.4%    |
| WDC WD3200BPVT-80JJ5T0 320GB         | 2         | 0.4%    |
| WDC WD10SPZX-75Z10T3 1TB             | 2         | 0.4%    |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.4%    |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 2         | 0.4%    |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 2         | 0.4%    |
| Unknown TA2964  64GB                 | 2         | 0.4%    |
| Toshiba MQ01ABF050 500GB             | 2         | 0.4%    |
| Toshiba MQ01ABD075 752GB             | 2         | 0.4%    |
| Toshiba MQ01ABD050 500GB             | 2         | 0.4%    |
| SPCC Solid State Disk 512GB          | 2         | 0.4%    |
| SPCC Solid State Disk 256GB          | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 45        | 45     | 29.41%  |
| Seagate             | 42        | 42     | 27.45%  |
| Toshiba             | 25        | 26     | 16.34%  |
| Hitachi             | 14        | 14     | 9.15%   |
| HGST                | 10        | 10     | 6.54%   |
| JMicron Technology  | 7         | 7      | 4.58%   |
| Unknown             | 4         | 4      | 2.61%   |
| Samsung Electronics | 2         | 2      | 1.31%   |
| SABRENT             | 2         | 3      | 1.31%   |
| TO Exter            | 1         | 1      | 0.65%   |
| Fujitsu             | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 42     | 20.86%  |
| SanDisk             | 16        | 17     | 9.82%   |
| Kingston            | 15        | 15     | 9.2%    |
| Crucial             | 8         | 8      | 4.91%   |
| China               | 8         | 8      | 4.91%   |
| SPCC                | 6         | 6      | 3.68%   |
| Intenso             | 6         | 6      | 3.68%   |
| WDC                 | 5         | 5      | 3.07%   |
| Micron Technology   | 5         | 7      | 3.07%   |
| KingSpec            | 4         | 4      | 2.45%   |
| Intel               | 4         | 4      | 2.45%   |
| A-DATA Technology   | 4         | 4      | 2.45%   |
| Hewlett-Packard     | 3         | 3      | 1.84%   |
| GOODRAM             | 3         | 3      | 1.84%   |
| Transcend           | 2         | 2      | 1.23%   |
| RX7                 | 2         | 2      | 1.23%   |
| HS-SSD-E100         | 2         | 2      | 1.23%   |
| Dahua               | 2         | 3      | 1.23%   |
| ASMT                | 2         | 2      | 1.23%   |
| Verbatim            | 1         | 1      | 0.61%   |
| USB                 | 1         | 1      | 0.61%   |
| TwinMOS             | 1         | 1      | 0.61%   |
| Toshiba             | 1         | 1      | 0.61%   |
| Team                | 1         | 1      | 0.61%   |
| T-FORCE             | 1         | 1      | 0.61%   |
| SSK                 | 1         | 1      | 0.61%   |
| SPCC M.2            | 1         | 1      | 0.61%   |
| SK hynix            | 1         | 1      | 0.61%   |
| PNY                 | 1         | 1      | 0.61%   |
| OCZ                 | 1         | 1      | 0.61%   |
| LITEONIT            | 1         | 1      | 0.61%   |
| LITEON              | 1         | 1      | 0.61%   |
| Lexar               | 1         | 1      | 0.61%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.61%   |
| Hitachi             | 1         | 1      | 0.61%   |
| Hikvision           | 1         | 1      | 0.61%   |
| G521S               | 1         | 1      | 0.61%   |
| FORESEE             | 1         | 1      | 0.61%   |
| External            | 1         | 1      | 0.61%   |
| EXRAM               | 1         | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 153       | 175    | 33.48%  |
| HDD     | 148       | 155    | 32.39%  |
| NVMe    | 121       | 135    | 26.48%  |
| MMC     | 25        | 28     | 5.47%   |
| Unknown | 10        | 12     | 2.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 254       | 287    | 58.39%  |
| NVMe | 121       | 133    | 27.82%  |
| SAS  | 35        | 57     | 8.05%   |
| MMC  | 25        | 28     | 5.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 206       | 223    | 69.13%  |
| 0.51-1.0   | 83        | 92     | 27.85%  |
| 1.01-2.0   | 6         | 11     | 2.01%   |
| 3.01-4.0   | 2         | 3      | 0.67%   |
| 10.01-20.0 | 1         | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 157       | 41.32%  |
| 101-250        | 74        | 19.47%  |
| 251-500        | 45        | 11.84%  |
| 501-1000       | 26        | 6.84%   |
| 51-100         | 25        | 6.58%   |
| 21-50          | 23        | 6.05%   |
| Unknown        | 19        | 5%      |
| 1001-2000      | 8         | 2.11%   |
| 2001-3000      | 2         | 0.53%   |
| More than 3000 | 1         | 0.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 290       | 76.32%  |
| 21-50    | 19        | 5%      |
| Unknown  | 19        | 5%      |
| 0        | 15        | 3.95%   |
| 101-250  | 14        | 3.68%   |
| 51-100   | 13        | 3.42%   |
| 251-500  | 6         | 1.58%   |
| 501-1000 | 4         | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 3         | 3      | 3.95%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 3      | 3.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 3      | 3.95%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 2      | 2.63%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 2      | 2.63%   |
| Hitachi HTS545032B9A300 320GB       | 2         | 2      | 2.63%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 1         | 1      | 1.32%   |
| WDC WD6400BPVT-16HXZT1 640GB        | 1         | 1      | 1.32%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 1      | 1.32%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 1.32%   |
| WDC WD5000LPLX-08ZNTT0 500GB        | 1         | 1      | 1.32%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 1         | 1      | 1.32%   |
| WDC WD5000BEVT-75A0RT0 500GB        | 1         | 1      | 1.32%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 1         | 1      | 1.32%   |
| WDC WD3200BEVT-75A23T0 320GB        | 1         | 1      | 1.32%   |
| WDC WD3200BEKT-08PVMT1 320GB        | 1         | 1      | 1.32%   |
| WDC WD2500BEVT-60ZCT1 250GB         | 1         | 1      | 1.32%   |
| WDC WD2500BEVT-22ZCT0 250GB         | 1         | 1      | 1.32%   |
| WDC WD2500BEVT-22A23T0 250GB        | 1         | 1      | 1.32%   |
| WDC WD1600BEVT-75A23T0 160GB        | 1         | 1      | 1.32%   |
| WDC WD1600BEKT-60F3T1 160GB         | 1         | 1      | 1.32%   |
| WDC WD10JPVT-60A1YT0 1TB            | 1         | 1      | 1.32%   |
| Transcend TS128GMTS430S 128GB SSD   | 1         | 1      | 1.32%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.32%   |
| Toshiba MK3276GSX 320GB             | 1         | 1      | 1.32%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 1.32%   |
| Toshiba MK3263GSX 320GB             | 1         | 1      | 1.32%   |
| Toshiba MK2565GSXN 250GB            | 1         | 1      | 1.32%   |
| Team TM8FPD001T 1TB                 | 1         | 1      | 1.32%   |
| Seagate ST9500423AS 500GB           | 1         | 1      | 1.32%   |
| Seagate ST9500420AS 500GB           | 1         | 1      | 1.32%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 1.32%   |
| Seagate ST9250827AS 250GB           | 1         | 1      | 1.32%   |
| Seagate ST9100824AS 100GB           | 1         | 1      | 1.32%   |
| Seagate ST9100821AS 100GB           | 1         | 1      | 1.32%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.32%   |
| Seagate ST500LM000-SSHD-8GB         | 1         | 1      | 1.32%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1      | 1.32%   |
| Seagate ST1000LM014-1EJ164 1TB      | 1         | 1      | 1.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 21     | 27.63%  |
| WDC                 | 16        | 16     | 21.05%  |
| Toshiba             | 7         | 7      | 9.21%   |
| Hitachi             | 7         | 7      | 9.21%   |
| Kingston            | 4         | 4      | 5.26%   |
| Samsung Electronics | 3         | 3      | 3.95%   |
| HGST                | 3         | 3      | 3.95%   |
| KingSpec            | 2         | 2      | 2.63%   |
| Crucial             | 2         | 2      | 2.63%   |
| Transcend           | 1         | 1      | 1.32%   |
| Team                | 1         | 1      | 1.32%   |
| SanDisk             | 1         | 1      | 1.32%   |
| OCZ                 | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| Lexar               | 1         | 1      | 1.32%   |
| JMicron Technology  | 1         | 1      | 1.32%   |
| Intel               | 1         | 1      | 1.32%   |
| Dogfish             | 1         | 1      | 1.32%   |
| China               | 1         | 1      | 1.32%   |
| Unknown             | 1         | 1      | 1.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 21     | 38.18%  |
| WDC                 | 15        | 15     | 27.27%  |
| Toshiba             | 7         | 7      | 12.73%  |
| Hitachi             | 7         | 7      | 12.73%  |
| HGST                | 3         | 3      | 5.45%   |
| Samsung Electronics | 2         | 2      | 3.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 55        | 55     | 72.37%  |
| SSD     | 18        | 18     | 23.68%  |
| NVMe    | 2         | 2      | 2.63%   |
| Unknown | 1         | 1      | 1.32%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 288       | 344    | 67.92%  |
| Malfunc  | 74        | 76     | 17.45%  |
| Detected | 62        | 85     | 14.62%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 269       | 60.04%  |
| AMD                                     | 47        | 10.49%  |
| Samsung Electronics                     | 26        | 5.8%    |
| SanDisk                                 | 24        | 5.36%   |
| Kingston Technology Company             | 15        | 3.35%   |
| SK hynix                                | 11        | 2.46%   |
| Phison Electronics                      | 10        | 2.23%   |
| Micron Technology                       | 10        | 2.23%   |
| Micron/Crucial Technology               | 7         | 1.56%   |
| Silicon Motion                          | 5         | 1.12%   |
| Solid State Storage Technology          | 3         | 0.67%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.67%   |
| Union Memory (Shenzhen)                 | 2         | 0.45%   |
| Nvidia                                  | 2         | 0.45%   |
| KIOXIA                                  | 2         | 0.45%   |
| Apple                                   | 2         | 0.45%   |
| ADATA Technology                        | 2         | 0.45%   |
| Toshiba America Info Systems            | 1         | 0.22%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.22%   |
| Shenzhen Unionmemory Information System | 1         | 0.22%   |
| Shenzhen Longsys Electronics            | 1         | 0.22%   |
| Seagate Technology                      | 1         | 0.22%   |
| Realtek Semiconductor                   | 1         | 0.22%   |
| Netac Technology                        | 1         | 0.22%   |
| ASMedia Technology                      | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 34        | 7.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 32        | 6.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 30        | 6.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 18        | 3.73%   |
| Intel Volume Management Device NVMe RAID Controller                              | 16        | 3.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 16        | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 3.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 15        | 3.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 2.48%   |
| Intel Tiger Lake-LP SATA Controller                                              | 11        | 2.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 11        | 2.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 11        | 2.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 2.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 2.28%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 10        | 2.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 2.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 1.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 1.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 1.24%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 5         | 1.04%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                               | 5         | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.04%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 4         | 0.83%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 4         | 0.83%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 4         | 0.83%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 4         | 0.83%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 4         | 0.83%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 0.62%   |
| SK hynix BC511 NVMe SSD                                                          | 3         | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 3         | 0.62%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 3         | 0.62%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 3         | 0.62%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 0.62%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.62%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 271       | 58.91%  |
| NVMe | 121       | 26.3%   |
| RAID | 40        | 8.7%    |
| IDE  | 28        | 6.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 305       | 80.26%  |
| AMD    | 75        | 19.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 1.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.58%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 1.58%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 1.58%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 1.32%   |
| Intel 12th Gen Core i5-12500H                 | 5         | 1.32%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 5         | 1.32%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 4         | 1.05%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 1.05%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 4         | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.05%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.05%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 4         | 1.05%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 1.05%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 4         | 1.05%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 1.05%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 1.05%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.05%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 3         | 0.79%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.79%   |
| Intel Genuine CPU T1500 @ 1.86GHz             | 3         | 0.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.79%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.79%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 3         | 0.79%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.79%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 3         | 0.79%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 0.79%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.79%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 3         | 0.79%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 0.79%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 3         | 0.79%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.79%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 77        | 20.26%  |
| Intel Core i3           | 50        | 13.16%  |
| Intel Core i7           | 44        | 11.58%  |
| Other                   | 43        | 11.32%  |
| Intel Celeron           | 41        | 10.79%  |
| AMD Ryzen 5             | 24        | 6.32%   |
| Intel Pentium           | 14        | 3.68%   |
| Intel Core 2 Duo        | 14        | 3.68%   |
| AMD Ryzen 7             | 10        | 2.63%   |
| Intel Pentium Dual-Core | 7         | 1.84%   |
| AMD E                   | 5         | 1.32%   |
| AMD A6                  | 5         | 1.32%   |
| Intel Genuine           | 4         | 1.05%   |
| Intel Atom              | 4         | 1.05%   |
| Intel Pentium Dual      | 3         | 0.79%   |
| Intel Core 2            | 3         | 0.79%   |
| AMD Ryzen 3             | 3         | 0.79%   |
| AMD Athlon              | 3         | 0.79%   |
| AMD A8                  | 3         | 0.79%   |
| Intel Pentium Silver    | 2         | 0.53%   |
| Intel Pentium Gold      | 2         | 0.53%   |
| AMD Turion 64 X2 Mobile | 2         | 0.53%   |
| AMD Ryzen 9             | 2         | 0.53%   |
| AMD E2                  | 2         | 0.53%   |
| AMD Athlon II Dual-Core | 2         | 0.53%   |
| AMD A4                  | 2         | 0.53%   |
| AMD A10                 | 2         | 0.53%   |
| Intel Core 2 Solo       | 1         | 0.26%   |
| AMD V140                | 1         | 0.26%   |
| AMD V120                | 1         | 0.26%   |
| AMD Turion II Dual-Core | 1         | 0.26%   |
| AMD Turion II           | 1         | 0.26%   |
| AMD E1                  | 1         | 0.26%   |
| AMD C-50                | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 223       | 58.68%  |
| 4      | 102       | 26.84%  |
| 6      | 15        | 3.95%   |
| 8      | 14        | 3.68%   |
| 12     | 8         | 2.11%   |
| 1      | 8         | 2.11%   |
| 14     | 6         | 1.58%   |
| 10     | 4         | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 380       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 250       | 65.79%  |
| 1      | 130       | 34.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 380       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 312       | 82.11%  |
| 0x08108109 | 15        | 3.95%   |
| 0x08608103 | 5         | 1.32%   |
| 0x06006705 | 4         | 1.05%   |
| 0x0a50000d | 3         | 0.79%   |
| 0x0a50000c | 3         | 0.79%   |
| 0x08108102 | 3         | 0.79%   |
| 0x05000101 | 3         | 0.79%   |
| 0x0a50000f | 2         | 0.53%   |
| 0x0a404102 | 2         | 0.53%   |
| 0x08608102 | 2         | 0.53%   |
| 0x07030105 | 2         | 0.53%   |
| 0x07030104 | 2         | 0.53%   |
| 0x0700010b | 2         | 0.53%   |
| 0x06001116 | 2         | 0.53%   |
| 0x0500010d | 2         | 0.53%   |
| 0x05000028 | 2         | 0.53%   |
| 0x010000b6 | 2         | 0.53%   |
| 0x0a704104 | 1         | 0.26%   |
| 0x0a704103 | 1         | 0.26%   |
| 0x08608104 | 1         | 0.26%   |
| 0x08600106 | 1         | 0.26%   |
| 0x08600104 | 1         | 0.26%   |
| 0x08600103 | 1         | 0.26%   |
| 0x08200103 | 1         | 0.26%   |
| 0x07030106 | 1         | 0.26%   |
| 0x06003106 | 1         | 0.26%   |
| 0x0300000f | 1         | 0.26%   |
| 0x010000c8 | 1         | 0.26%   |
| 0x00000000 | 1         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 9.21%   |
| IvyBridge        | 33        | 8.68%   |
| Skylake          | 23        | 6.05%   |
| Haswell          | 23        | 6.05%   |
| Westmere         | 22        | 5.79%   |
| SandyBridge      | 22        | 5.79%   |
| Zen+             | 19        | 5%      |
| TigerLake        | 19        | 5%      |
| Silvermont       | 19        | 5%      |
| Core             | 18        | 4.74%   |
| Alderlake Hybrid | 18        | 4.74%   |
| Penryn           | 17        | 4.47%   |
| IceLake          | 14        | 3.68%   |
| Broadwell        | 13        | 3.42%   |
| Unknown          | 12        | 3.16%   |
| Goldmont         | 11        | 2.89%   |
| Goldmont plus    | 9         | 2.37%   |
| Zen 3            | 8         | 2.11%   |
| Bobcat           | 7         | 1.84%   |
| K10              | 6         | 1.58%   |
| Puma             | 5         | 1.32%   |
| Excavator        | 4         | 1.05%   |
| Zen 2            | 3         | 0.79%   |
| CometLake        | 3         | 0.79%   |
| Bonnell          | 3         | 0.79%   |
| Zen              | 2         | 0.53%   |
| Tremont          | 2         | 0.53%   |
| Piledriver       | 2         | 0.53%   |
| K8 Hammer        | 2         | 0.53%   |
| K10 Llano        | 2         | 0.53%   |
| Jaguar           | 2         | 0.53%   |
| Steamroller      | 1         | 0.26%   |
| Gracemont        | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 283       | 61.93%  |
| AMD    | 88        | 19.26%  |
| Nvidia | 86        | 18.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 6.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 4.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 4.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 4.05%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 3.84%   |
| Intel UHD Graphics 620                                                                   | 14        | 2.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 2.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 2.56%   |
| Intel HD Graphics 5500                                                                   | 12        | 2.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.35%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 10        | 2.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.92%   |
| Intel HD Graphics 500                                                                    | 8         | 1.71%   |
| AMD Lucienne                                                                             | 8         | 1.71%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 7         | 1.49%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.49%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.28%   |
| Intel HD Graphics 620                                                                    | 6         | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.28%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 5         | 1.07%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.85%   |
| Intel HD Graphics 530                                                                    | 4         | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.85%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4         | 0.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 0.85%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 3         | 0.64%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 3         | 0.64%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 3         | 0.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.64%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 3         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 188       | 49.47%  |
| 1 x AMD        | 70        | 18.42%  |
| Intel + Nvidia | 66        | 17.37%  |
| 2 x Intel      | 23        | 6.05%   |
| 1 x Nvidia     | 15        | 3.95%   |
| 2 x AMD        | 7         | 1.84%   |
| Intel + AMD    | 6         | 1.58%   |
| AMD + Nvidia   | 5         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 372       | 97.89%  |
| Proprietary | 7         | 1.84%   |
| Unknown     | 1         | 0.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 221       | 58.16%  |
| 1.01-2.0   | 55        | 14.47%  |
| 0.01-0.5   | 48        | 12.63%  |
| 0.51-1.0   | 29        | 7.63%   |
| 3.01-4.0   | 19        | 5%      |
| 5.01-6.0   | 3         | 0.79%   |
| 7.01-8.0   | 2         | 0.53%   |
| 2.01-3.0   | 2         | 0.53%   |
| 16.01-24.0 | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 96        | 23.94%  |
| Chimei Innolux          | 72        | 17.96%  |
| BOE                     | 59        | 14.71%  |
| LG Display              | 52        | 12.97%  |
| Samsung Electronics     | 35        | 8.73%   |
| Chi Mei Optoelectronics | 14        | 3.49%   |
| Lenovo                  | 12        | 2.99%   |
| Apple                   | 7         | 1.75%   |
| Sharp                   | 6         | 1.5%    |
| LG Philips              | 6         | 1.5%    |
| Goldstar                | 5         | 1.25%   |
| TMX                     | 3         | 0.75%   |
| PANDA                   | 3         | 0.75%   |
| Hewlett-Packard         | 3         | 0.75%   |
| Dell                    | 3         | 0.75%   |
| CSO                     | 3         | 0.75%   |
| Panasonic               | 2         | 0.5%    |
| InnoLux Display         | 2         | 0.5%    |
| InfoVision              | 2         | 0.5%    |
| ___                     | 1         | 0.25%   |
| ViewSonic               | 1         | 0.25%   |
| Vestel Elektronik       | 1         | 0.25%   |
| Unknown                 | 1         | 0.25%   |
| Toshiba                 | 1         | 0.25%   |
| TGL                     | 1         | 0.25%   |
| TFT                     | 1         | 0.25%   |
| Philips                 | 1         | 0.25%   |
| NEC Computers           | 1         | 0.25%   |
| Mitsubishi              | 1         | 0.25%   |
| KDC                     | 1         | 0.25%   |
| JDI                     | 1         | 0.25%   |
| IBM                     | 1         | 0.25%   |
| HKC                     | 1         | 0.25%   |
| HannStar                | 1         | 0.25%   |
| Ancor Communications    | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 1.49%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 5         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch         | 5         | 1.24%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.24%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 4         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 4         | 0.99%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 4         | 0.99%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.74%   |
| Lenovo LEN E2002bA LEN60BB 1600x900 432x240mm 19.5-inch                  | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 3         | 0.74%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 3         | 0.74%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.74%   |
| BOE LCD Monitor BOE05F3 1366x768 309x173mm 13.9-inch                     | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO459D 1920x1200 344x215mm 16.0-inch           | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.74%   |
| Samsung Electronics LS24C36x SAM7314 1920x1080 598x336mm 27.0-inch       | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 2         | 0.5%    |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch              | 2         | 0.5%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 2         | 0.5%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.5%    |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1720 1920x1080 382x215mm 17.3-inch         | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 2         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.5%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.5%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 0.5%    |
| BOE LCD Monitor BOE06F3 1920x1080 309x173mm 13.9-inch                    | 2         | 0.5%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 0.5%    |
| BOE LCD Monitor BOE0660 1600x900 382x215mm 17.3-inch                     | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 152       | 38.29%  |
| 1920x1080 (FHD)    | 135       | 34.01%  |
| 1600x900 (HD+)     | 35        | 8.82%   |
| 1280x800 (WXGA)    | 22        | 5.54%   |
| 1920x1200 (WUXGA)  | 18        | 4.53%   |
| 2560x1600          | 8         | 2.02%   |
| 2560x1440 (QHD)    | 5         | 1.26%   |
| 1440x900 (WXGA+)   | 4         | 1.01%   |
| 2880x1800          | 3         | 0.76%   |
| 1024x600           | 3         | 0.76%   |
| 3840x2160 (4K)     | 2         | 0.5%    |
| 1680x1050 (WSXGA+) | 2         | 0.5%    |
| 3840x2400          | 1         | 0.25%   |
| 3200x2000          | 1         | 0.25%   |
| 3200x1800 (QHD+)   | 1         | 0.25%   |
| 3000x2000          | 1         | 0.25%   |
| 2560x1080          | 1         | 0.25%   |
| 1920x540           | 1         | 0.25%   |
| 1360x768           | 1         | 0.25%   |
| 1024x768 (XGA)     | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 197       | 48.88%  |
| 13      | 61        | 15.14%  |
| 14      | 42        | 10.42%  |
| 17      | 38        | 9.43%   |
| 16      | 12        | 2.98%   |
| 24      | 7         | 1.74%   |
| 12      | 7         | 1.74%   |
| 27      | 6         | 1.49%   |
| 23      | 5         | 1.24%   |
| 11      | 5         | 1.24%   |
| 19      | 4         | 0.99%   |
| 18      | 4         | 0.99%   |
| 10      | 3         | 0.74%   |
| Unknown | 3         | 0.74%   |
| 21      | 2         | 0.5%    |
| 84      | 1         | 0.25%   |
| 72      | 1         | 0.25%   |
| 40      | 1         | 0.25%   |
| 39      | 1         | 0.25%   |
| 34      | 1         | 0.25%   |
| 31      | 1         | 0.25%   |
| 22      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 276       | 68.49%  |
| 351-400     | 48        | 11.91%  |
| 201-300     | 41        | 10.17%  |
| 501-600     | 16        | 3.97%   |
| 401-500     | 13        | 3.23%   |
| Unknown     | 3         | 0.74%   |
| 801-900     | 2         | 0.5%    |
| 1501-2000   | 2         | 0.5%    |
| 701-800     | 1         | 0.25%   |
| 601-700     | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 318       | 84.13%  |
| 16/10 | 54        | 14.29%  |
| 3/2   | 3         | 0.79%   |
| 4/3   | 1         | 0.26%   |
| 32/9  | 1         | 0.26%   |
| 21/9  | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 199       | 49.38%  |
| 81-90          | 80        | 19.85%  |
| 121-130        | 31        | 7.69%   |
| 71-80          | 22        | 5.46%   |
| 201-250        | 12        | 2.98%   |
| 111-120        | 10        | 2.48%   |
| 61-70          | 7         | 1.74%   |
| 131-140        | 7         | 1.74%   |
| 301-350        | 6         | 1.49%   |
| 51-60          | 5         | 1.24%   |
| 151-200        | 5         | 1.24%   |
| 141-150        | 4         | 0.99%   |
| 41-50          | 3         | 0.74%   |
| Unknown        | 3         | 0.74%   |
| More than 1000 | 2         | 0.5%    |
| 351-500        | 2         | 0.5%    |
| 251-300        | 2         | 0.5%    |
| 501-1000       | 2         | 0.5%    |
| 91-100         | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 164       | 41.21%  |
| 121-160       | 141       | 35.43%  |
| 51-100        | 62        | 15.58%  |
| 161-240       | 21        | 5.28%   |
| More than 240 | 6         | 1.51%   |
| Unknown       | 3         | 0.75%   |
| 1-50          | 1         | 0.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 343       | 90.26%  |
| 2     | 29        | 7.63%   |
| 0     | 6         | 1.58%   |
| 3     | 2         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 190       | 32.53%  |
| Intel                            | 165       | 28.25%  |
| Qualcomm Atheros                 | 103       | 17.64%  |
| Broadcom                         | 45        | 7.71%   |
| MediaTek                         | 13        | 2.23%   |
| Broadcom Limited                 | 11        | 1.88%   |
| Ralink                           | 9         | 1.54%   |
| Marvell Technology Group         | 9         | 1.54%   |
| ASIX Electronics                 | 9         | 1.54%   |
| Ralink Technology                | 5         | 0.86%   |
| Linksys                          | 3         | 0.51%   |
| TP-Link                          | 2         | 0.34%   |
| Sierra Wireless                  | 2         | 0.34%   |
| JMicron Technology               | 2         | 0.34%   |
| Huawei Technologies              | 2         | 0.34%   |
| ZyXEL Communications             | 1         | 0.17%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.17%   |
| Toshiba                          | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| Samsung Electronics              | 1         | 0.17%   |
| PLANEX                           | 1         | 0.17%   |
| Nvidia                           | 1         | 0.17%   |
| NetGear                          | 1         | 0.17%   |
| Elecom                           | 1         | 0.17%   |
| Edimax Technology                | 1         | 0.17%   |
| Dell                             | 1         | 0.17%   |
| Belkin Components                | 1         | 0.17%   |
| Attansic Technology              | 1         | 0.17%   |
| ASUSTek Computer                 | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 110       | 15.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 40        | 5.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 22        | 3.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 1.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 13        | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 1.86%   |
| Intel Wireless 8260                                                     | 12        | 1.71%   |
| Intel Wireless 7260                                                     | 12        | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 1.57%   |
| Intel Wireless 8265 / 8275                                              | 11        | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.43%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.43%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.29%   |
| Intel Wireless 7265                                                     | 9         | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 1.29%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 1.14%   |
| Intel Wireless 3165                                                     | 8         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                           | 8         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.86%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                    | 6         | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 0.86%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 0.86%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.86%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 5         | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.71%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.71%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 4         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 156       | 39.8%   |
| Qualcomm Atheros      | 85        | 21.68%  |
| Realtek Semiconductor | 75        | 19.13%  |
| Broadcom              | 32        | 8.16%   |
| MediaTek              | 11        | 2.81%   |
| Ralink                | 9         | 2.3%    |
| Broadcom Limited      | 8         | 2.04%   |
| Ralink Technology     | 5         | 1.28%   |
| Sierra Wireless       | 2         | 0.51%   |
| ZyXEL Communications  | 1         | 0.26%   |
| TP-Link               | 1         | 0.26%   |
| PLANEX                | 1         | 0.26%   |
| NetGear               | 1         | 0.26%   |
| Elecom                | 1         | 0.26%   |
| Edimax Technology     | 1         | 0.26%   |
| Dell                  | 1         | 0.26%   |
| Belkin Components     | 1         | 0.26%   |
| ASUSTek Computer      | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 6.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 22        | 5.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 3.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 3.31%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 13        | 3.31%   |
| Intel Wireless 8260                                                     | 12        | 3.05%   |
| Intel Wireless 7260                                                     | 12        | 3.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 3.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 2.8%    |
| Intel Wireless 8265 / 8275                                              | 11        | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.54%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 2.54%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 2.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 2.29%   |
| Intel Wireless 7265                                                     | 9         | 2.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.29%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 2.04%   |
| Intel Wireless 3165                                                     | 8         | 2.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 1.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 1.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 5         | 1.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.27%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 1.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.02%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 1.02%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 1.02%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.76%   |
| Intel WiFi Link 5100                                                    | 3         | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 154       | 50.99%  |
| Intel                            | 67        | 22.19%  |
| Qualcomm Atheros                 | 27        | 8.94%   |
| Broadcom                         | 20        | 6.62%   |
| Marvell Technology Group         | 9         | 2.98%   |
| ASIX Electronics                 | 9         | 2.98%   |
| Linksys                          | 3         | 0.99%   |
| Broadcom Limited                 | 3         | 0.99%   |
| MediaTek                         | 2         | 0.66%   |
| JMicron Technology               | 2         | 0.66%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.33%   |
| TP-Link                          | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Samsung Electronics              | 1         | 0.33%   |
| Nvidia                           | 1         | 0.33%   |
| Attansic Technology              | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 110       | 36.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 13.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 4.3%    |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 2.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 1.99%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 6         | 1.99%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 1.99%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 1.66%   |
| Intel Ethernet Connection (3) I218-LM                                  | 5         | 1.66%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 1.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 4         | 1.32%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.32%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 3         | 0.99%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 0.99%   |
| Linksys Gigabit Ethernet Adapter                                       | 3         | 0.99%   |
| Intel Ethernet Connection I219-V                                       | 3         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.99%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 3         | 0.99%   |
| MediaTek RMX3085                                                       | 2         | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.66%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 0.66%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.66%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.66%   |
| Intel Ethernet Connection (11) I219-LM                                 | 2         | 0.66%   |
| Intel 82573L Gigabit Ethernet Controller                               | 2         | 0.66%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 0.66%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.66%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 0.66%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2         | 0.66%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.66%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 2         | 0.66%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                            | 1         | 0.33%   |
| TP-Link M7010                                                          | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 378       | 55.67%  |
| Ethernet | 296       | 43.59%  |
| Modem    | 3         | 0.44%   |
| Unknown  | 2         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 285       | 76.82%  |
| Ethernet | 86        | 23.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 281       | 73.95%  |
| 1     | 92        | 24.21%  |
| 0     | 5         | 1.32%   |
| 3     | 2         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 255       | 67.11%  |
| Yes  | 125       | 32.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 124       | 41.06%  |
| Realtek Semiconductor           | 48        | 15.89%  |
| Qualcomm Atheros Communications | 24        | 7.95%   |
| Broadcom                        | 21        | 6.95%   |
| Lite-On Technology              | 15        | 4.97%   |
| IMC Networks                    | 15        | 4.97%   |
| Foxconn / Hon Hai               | 11        | 3.64%   |
| Hewlett-Packard                 | 7         | 2.32%   |
| Dell                            | 6         | 1.99%   |
| Ralink                          | 5         | 1.66%   |
| Cambridge Silicon Radio         | 4         | 1.32%   |
| ASUSTek Computer                | 4         | 1.32%   |
| Apple                           | 4         | 1.32%   |
| Toshiba                         | 3         | 0.99%   |
| Foxconn International           | 3         | 0.99%   |
| MediaTek                        | 2         | 0.66%   |
| Chicony Electronics             | 2         | 0.66%   |
| Realtek                         | 1         | 0.33%   |
| Opticis                         | 1         | 0.33%   |
| Belkin Components               | 1         | 0.33%   |
| Alps Electric                   | 1         | 0.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 32        | 10.6%   |
| Realtek Bluetooth Radio                             | 26        | 8.61%   |
| Intel AX201 Bluetooth                               | 26        | 8.61%   |
| Intel Bluetooth Device                              | 20        | 6.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 4.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 4.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 3.97%   |
| Intel AX200 Bluetooth                               | 10        | 3.31%   |
| Intel AX211 Bluetooth                               | 8         | 2.65%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 2.32%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 1.99%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 1.99%   |
| Realtek 802.11ac WLAN Adapter                       | 5         | 1.66%   |
| Ralink RT3290 Bluetooth                             | 5         | 1.66%   |
| IMC Networks Bluetooth Device                       | 5         | 1.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 1.66%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.32%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.32%   |
| Dell DW375 Bluetooth Module                         | 4         | 1.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.99%   |
| IMC Networks Wireless_Device                        | 3         | 0.99%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.99%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.99%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.99%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.99%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.66%   |
| MediaTek Wireless_Device                            | 2         | 0.66%   |
| Lite-On Bluetooth Device                            | 2         | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.66%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.66%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.66%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 0.66%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.66%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.66%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 301       | 68.88%  |
| AMD                              | 79        | 18.08%  |
| Nvidia                           | 43        | 9.84%   |
| C-Media Electronics              | 3         | 0.69%   |
| Generalplus Technology           | 2         | 0.46%   |
| Apple                            | 2         | 0.46%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Realtek Semiconductor            | 1         | 0.23%   |
| Nordic Semiconductor ASA         | 1         | 0.23%   |
| Microsoft                        | 1         | 0.23%   |
| Logitech                         | 1         | 0.23%   |
| EGO SYStems                      | 1         | 0.23%   |
| ASUSTek Computer                 | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 43        | 7.95%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 7.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 37        | 6.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 22        | 4.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 3.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 3.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 3.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 15        | 2.77%   |
| AMD FCH Azalia Controller                                                                         | 14        | 2.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 2.4%    |
| Intel Broadwell-U Audio Controller                                                                | 13        | 2.4%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 2.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 2.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 2.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 11        | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 2.03%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 2.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 1.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.66%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.29%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.29%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.11%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.74%   |
| Nvidia Audio device                                                                               | 4         | 0.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 4         | 0.74%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.55%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.55%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 127       | 27.97%  |
| SK hynix               | 79        | 17.4%   |
| Micron Technology      | 62        | 13.66%  |
| Kingston               | 37        | 8.15%   |
| Unknown                | 32        | 7.05%   |
| Nanya Technology       | 15        | 3.3%    |
| Crucial                | 15        | 3.3%    |
| Elpida                 | 13        | 2.86%   |
| A-DATA Technology      | 12        | 2.64%   |
| Unknown (ABCD)         | 8         | 1.76%   |
| Timetec                | 4         | 0.88%   |
| SHARETRONIC            | 4         | 0.88%   |
| Ramaxel Technology     | 4         | 0.88%   |
| Juhor                  | 4         | 0.88%   |
| G.Skill                | 4         | 0.88%   |
| Smart                  | 3         | 0.66%   |
| Corsair                | 3         | 0.66%   |
| Unknown                | 3         | 0.66%   |
| Patriot                | 2         | 0.44%   |
| Multilaser             | 2         | 0.44%   |
| ASint Technology       | 2         | 0.44%   |
| Unknown (268C)         | 1         | 0.22%   |
| Unknown (0x0B5E)       | 1         | 0.22%   |
| Unknown (0000000080CE) | 1         | 0.22%   |
| Transcend              | 1         | 0.22%   |
| Team                   | 1         | 0.22%   |
| Silicon Power          | 1         | 0.22%   |
| Qimonda                | 1         | 0.22%   |
| PSC                    | 1         | 0.22%   |
| PNY                    | 1         | 0.22%   |
| Innodisk               | 1         | 0.22%   |
| Hikvision              | 1         | 0.22%   |
| GOODRAM                | 1         | 0.22%   |
| ff                     | 1         | 0.22%   |
| CSX                    | 1         | 0.22%   |
| Centon                 | 1         | 0.22%   |
| Avant                  | 1         | 0.22%   |
| Apacer                 | 1         | 0.22%   |
| AMD                    | 1         | 0.22%   |
| 4ea5                   | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 9         | 1.85%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 8         | 1.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 1.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 1.44%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 6         | 1.23%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.23%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 5         | 1.03%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 4         | 0.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.82%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.82%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.82%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.82%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 4         | 0.82%   |
| Micron RAM 16HTF25664HY-800J1 2GB SODIMM DDR2 800MT/s            | 4         | 0.82%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s            | 4         | 0.82%   |
| Juhor RAM JHD2666S1908JG 8GB SODIMM DDR4 2667MT/s                | 4         | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.62%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.62%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 3         | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.62%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 3         | 0.62%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.62%   |
| Nanya RAM NT8GA64D88CX3S-JR 8GB SODIMM DDR4 3200MT/s             | 3         | 0.62%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 3         | 0.62%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 3         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.62%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.62%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.62%   |
| Unknown                                                          | 3         | 0.62%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 165       | 41.88%  |
| DDR4    | 133       | 33.76%  |
| LPDDR4  | 24        | 6.09%   |
| SDRAM   | 23        | 5.84%   |
| DDR2    | 21        | 5.33%   |
| LPDDR5  | 9         | 2.28%   |
| DDR5    | 8         | 2.03%   |
| LPDDR3  | 4         | 1.02%   |
| DDR     | 3         | 0.76%   |
| Unknown | 3         | 0.76%   |
| DRAM    | 1         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 342       | 89.76%  |
| Row Of Chips | 27        | 7.09%   |
| DIMM         | 4         | 1.05%   |
| Chip         | 4         | 1.05%   |
| Unknown      | 4         | 1.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 147       | 34.83%  |
| 4096  | 140       | 33.18%  |
| 2048  | 74        | 17.54%  |
| 16384 | 36        | 8.53%   |
| 1024  | 19        | 4.5%    |
| 32768 | 5         | 1.18%   |
| 8     | 1         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 111       | 26.12%  |
| 3200    | 66        | 15.53%  |
| 2667    | 55        | 12.94%  |
| 2400    | 28        | 6.59%   |
| 1334    | 28        | 6.59%   |
| 1333    | 21        | 4.94%   |
| 4199    | 11        | 2.59%   |
| 2133    | 11        | 2.59%   |
| 800     | 11        | 2.59%   |
| 2048    | 10        | 2.35%   |
| 6400    | 9         | 2.12%   |
| 1067    | 9         | 2.12%   |
| 667     | 9         | 2.12%   |
| Unknown | 8         | 1.88%   |
| 3266    | 7         | 1.65%   |
| 4800    | 6         | 1.41%   |
| 4267    | 4         | 0.94%   |
| 1867    | 4         | 0.94%   |
| 975     | 3         | 0.71%   |
| 4266    | 2         | 0.47%   |
| 3733    | 2         | 0.47%   |
| 2933    | 2         | 0.47%   |
| 533     | 2         | 0.47%   |
| 8400    | 1         | 0.24%   |
| 5600    | 1         | 0.24%   |
| 5200    | 1         | 0.24%   |
| 1866    | 1         | 0.24%   |
| 1639    | 1         | 0.24%   |
| 1066    | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Brother Industries  | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung M2020 Series | 1         | 50%     |
| Brother DCP-7010     | 1         | 50%     |

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
| Chicony Electronics                    | 89        | 26.25%  |
| IMC Networks                           | 31        | 9.14%   |
| Microdia                               | 28        | 8.26%   |
| Realtek Semiconductor                  | 21        | 6.19%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 5.9%    |
| Bison Electronics                      | 19        | 5.6%    |
| Sunplus Innovation Technology          | 15        | 4.42%   |
| Suyin                                  | 14        | 4.13%   |
| Quanta                                 | 13        | 3.83%   |
| Syntek                                 | 12        | 3.54%   |
| Luxvisions Innotech Limited            | 11        | 3.24%   |
| Apple                                  | 9         | 2.65%   |
| Lite-On Technology                     | 8         | 2.36%   |
| Alcor Micro                            | 7         | 2.06%   |
| Importek                               | 6         | 1.77%   |
| Acer                                   | 6         | 1.77%   |
| Sonix Technology                       | 5         | 1.47%   |
| Ricoh                                  | 5         | 1.47%   |
| Lenovo                                 | 3         | 0.88%   |
| Silicon Motion                         | 2         | 0.59%   |
| icSpring                               | 2         | 0.59%   |
| BUFFALO                                | 2         | 0.59%   |
| Z-Star Microelectronics                | 1         | 0.29%   |
| SunplusIT                              | 1         | 0.29%   |
| Sunplus Technology                     | 1         | 0.29%   |
| OPPO Electronics                       | 1         | 0.29%   |
| Logitech                               | 1         | 0.29%   |
| lihappe8                               | 1         | 0.29%   |
| Genesys Logic                          | 1         | 0.29%   |
| Foxconn / Hon Hai                      | 1         | 0.29%   |
| Cubeternet                             | 1         | 0.29%   |
| ALi                                    | 1         | 0.29%   |
| Unknown                                | 1         | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 15        | 4.42%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 10        | 2.95%   |
| Chicony VGA WebCam                                             | 9         | 2.65%   |
| Chicony Integrated Camera                                      | 9         | 2.65%   |
| Chicony HD WebCam                                              | 7         | 2.06%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 7         | 2.06%   |
| Bison Integrated Camera                                        | 7         | 2.06%   |
| Syntek Integrated Camera                                       | 6         | 1.77%   |
| Realtek USB Camera                                             | 6         | 1.77%   |
| Realtek Integrated_Webcam_HD                                   | 6         | 1.77%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 6         | 1.77%   |
| Sunplus Integrated_Webcam_HD                                   | 5         | 1.47%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 5         | 1.47%   |
| Chicony HP TrueVision HD Camera                                | 5         | 1.47%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 5         | 1.47%   |
| Sonix USB2.0 HD UVC WebCam                                     | 4         | 1.18%   |
| Microdia Integrated Webcam                                     | 4         | 1.18%   |
| Lite-On Integrated Camera                                      | 4         | 1.18%   |
| IMC Networks Integrated Camera                                 | 4         | 1.18%   |
| Chicony HP TrueVision HD                                       | 4         | 1.18%   |
| Chicony HD User Facing                                         | 4         | 1.18%   |
| Chicony FJ Camera                                              | 4         | 1.18%   |
| Chicony CNF8243 Webcam                                         | 4         | 1.18%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera                          | 3         | 0.88%   |
| Sunplus Dell E5570 integrated webcam                           | 3         | 0.88%   |
| Quanta HP Webcam                                               | 3         | 0.88%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 0.88%   |
| Lite-On HP HD Webcam                                           | 3         | 0.88%   |
| Lenovo Integrated Webcam                                       | 3         | 0.88%   |
| Importek TOSHIBA Web Camera - HD                               | 3         | 0.88%   |
| Importek Laptop Integrated Webcam                              | 3         | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 3         | 0.88%   |
| IMC Networks Lenovo EasyCamera                                 | 3         | 0.88%   |
| Bison HD Webcam                                                | 3         | 0.88%   |
| Bison EasyCamera                                               | 3         | 0.88%   |
| Alcor Micro USB 2.0 PC Camera                                  | 3         | 0.88%   |
| Acer Lenovo Integrated Webcam                                  | 3         | 0.88%   |
| Syntek Lenovo EasyCamera                                       | 2         | 0.59%   |
| Suyin HP TrueVision HD                                         | 2         | 0.59%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 2         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 12        | 28.57%  |
| Shenzhen Goodix Technology         | 7         | 16.67%  |
| Synaptics                          | 5         | 11.9%   |
| Elan Microelectronics              | 5         | 11.9%   |
| STMicroelectronics                 | 4         | 9.52%   |
| LighTuning Technology              | 3         | 7.14%   |
| AuthenTec                          | 3         | 7.14%   |
| Upek                               | 2         | 4.76%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 11.9%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 9.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 7.14%   |
| Elan ELAN:ARM-M4                                                           | 3         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4.76%   |
| LighTuning Fingerprint Reader                                              | 2         | 4.76%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.76%   |
| AuthenTec AES2810                                                          | 2         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.38%   |
| Validity Sensors VFS491                                                    | 1         | 2.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.38%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.38%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.38%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 2.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.38%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 2.38%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.38%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.38%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 2.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.38%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 13        | 52%     |
| Upek                  | 4         | 16%     |
| O2 Micro              | 3         | 12%     |
| Lenovo                | 2         | 8%      |
| Alcor Micro           | 2         | 8%      |
| Gemalto (was Gemplus) | 1         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 7         | 28%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 16%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 12%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 12%     |
| Lenovo Integrated Smart Card Reader                                          | 2         | 8%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8%      |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 8%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 4%      |
| Broadcom 58200                                                               | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 282       | 74.21%  |
| 1     | 83        | 21.84%  |
| 2     | 15        | 3.95%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 42        | 37.84%  |
| Chipcard              | 24        | 21.62%  |
| Graphics card         | 21        | 18.92%  |
| Net/wireless          | 10        | 9.01%   |
| Bluetooth             | 6         | 5.41%   |
| Sound                 | 2         | 1.8%    |
| Camera                | 2         | 1.8%    |
| Net/ethernet          | 1         | 0.9%    |
| Multimedia controller | 1         | 0.9%    |
| Flash memory          | 1         | 0.9%    |
| Card reader           | 1         | 0.9%    |

