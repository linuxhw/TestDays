Linux in Mexico - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Mexico.

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

Total: 2152

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-db0xxx            | [03f0e4060e](https://linux-hardware.org/?probe=03f0e4060e) | Jun 10, 2023 |
| Google        | Pirika                      | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | [86f646e00f](https://linux-hardware.org/?probe=86f646e00f) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | [1bb9178df2](https://linux-hardware.org/?probe=1bb9178df2) | Jun 10, 2023 |
| HP            | Laptop 15-db0xxx            | [881d5dc409](https://linux-hardware.org/?probe=881d5dc409) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [a579703f97](https://linux-hardware.org/?probe=a579703f97) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c35e22de2b](https://linux-hardware.org/?probe=c35e22de2b) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [68be9da7f1](https://linux-hardware.org/?probe=68be9da7f1) | Jun 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e28668e147](https://linux-hardware.org/?probe=e28668e147) | Jun 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59ff5486a9](https://linux-hardware.org/?probe=59ff5486a9) | Jun 08, 2023 |
| ASUSTek       | X455LA                      | [583596672d](https://linux-hardware.org/?probe=583596672d) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [3acaedf40f](https://linux-hardware.org/?probe=3acaedf40f) | Jun 08, 2023 |
| Acer          | Nitro AN515-55              | [99b42755e8](https://linux-hardware.org/?probe=99b42755e8) | Jun 07, 2023 |
| Dell          | Latitude E6400              | [ced90af89e](https://linux-hardware.org/?probe=ced90af89e) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [a9ea51ea77](https://linux-hardware.org/?probe=a9ea51ea77) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| HP            | Pavilion g4                 | [af0c33de44](https://linux-hardware.org/?probe=af0c33de44) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| HP            | 240 G3                      | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Dell          | Inspiron 5559               | [9ee7eff678](https://linux-hardware.org/?probe=9ee7eff678) | Jun 04, 2023 |
| Lanix         | AL V9                       | [3bd23fdde7](https://linux-hardware.org/?probe=3bd23fdde7) | Jun 04, 2023 |
| Dell          | Inspiron 5555               | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Dell          | Latitude E5470              | [daa15a6cb0](https://linux-hardware.org/?probe=daa15a6cb0) | Jun 02, 2023 |
| Dell          | Latitude E5470              | [92d3a8b502](https://linux-hardware.org/?probe=92d3a8b502) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | [29d6e72544](https://linux-hardware.org/?probe=29d6e72544) | Jun 02, 2023 |
| HP            | EliteBook 8470p             | [bc606409ff](https://linux-hardware.org/?probe=bc606409ff) | Jun 01, 2023 |
| Valve         | Jupiter                     | [30a2370d6e](https://linux-hardware.org/?probe=30a2370d6e) | Jun 01, 2023 |
| Acer          | AO756                       | [e135dbe37e](https://linux-hardware.org/?probe=e135dbe37e) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [560680687c](https://linux-hardware.org/?probe=560680687c) | May 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [65b03710b2](https://linux-hardware.org/?probe=65b03710b2) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | [a09171afde](https://linux-hardware.org/?probe=a09171afde) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [32ba69494b](https://linux-hardware.org/?probe=32ba69494b) | May 31, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [bb05a8a89b](https://linux-hardware.org/?probe=bb05a8a89b) | May 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7816244e1a](https://linux-hardware.org/?probe=7816244e1a) | May 30, 2023 |
| Acer          | Aspire E5-573               | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [412b42ae92](https://linux-hardware.org/?probe=412b42ae92) | May 28, 2023 |
| HP            | Mini 110-3700               | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [3f6fc3ec0c](https://linux-hardware.org/?probe=3f6fc3ec0c) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Acer          | Aspire E5-575               | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| Dell          | Latitude E5470              | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| Dell          | Inspiron 5548               | [5665ccbc0a](https://linux-hardware.org/?probe=5665ccbc0a) | May 23, 2023 |
| Toshiba       | Satellite C645D             | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| MSI           | GF65 Thin 9SE               | [c485674a13](https://linux-hardware.org/?probe=c485674a13) | May 23, 2023 |
| HP            | Pavilion dm4                | [81f264e4ef](https://linux-hardware.org/?probe=81f264e4ef) | May 22, 2023 |
| HP            | Pavilion dm4                | [1f1a9e3f62](https://linux-hardware.org/?probe=1f1a9e3f62) | May 22, 2023 |
| Apple         | MacBookPro5,5               | [a4b0d5fd13](https://linux-hardware.org/?probe=a4b0d5fd13) | May 22, 2023 |
| HP            | Pavilion dm4                | [e25186a486](https://linux-hardware.org/?probe=e25186a486) | May 22, 2023 |
| HUAWEI        | NBM-WXX9                    | [e3ea42dd02](https://linux-hardware.org/?probe=e3ea42dd02) | May 22, 2023 |
| Lenovo        | ThinkPad W530 24382LU       | [908f53f58b](https://linux-hardware.org/?probe=908f53f58b) | May 20, 2023 |
| Apple         | MacBookPro12,1              | [c25d920f3d](https://linux-hardware.org/?probe=c25d920f3d) | May 20, 2023 |
| Lenovo        | G50-30 80G0                 | [03c6d7a815](https://linux-hardware.org/?probe=03c6d7a815) | May 19, 2023 |
| HP            | Pavilion Notebook           | [f76ac6d7b5](https://linux-hardware.org/?probe=f76ac6d7b5) | May 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2C... | [a0f983e519](https://linux-hardware.org/?probe=a0f983e519) | May 18, 2023 |
| ASUSTek       | G73Sw                       | [ec9817e3d1](https://linux-hardware.org/?probe=ec9817e3d1) | May 16, 2023 |
| HP            | Laptop 15-db0xxx            | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Samsung       | R530/R730                   | [d7674fa203](https://linux-hardware.org/?probe=d7674fa203) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| Apple         | MacBookPro9,2               | [ecb43775d1](https://linux-hardware.org/?probe=ecb43775d1) | May 11, 2023 |
| HP            | Laptop 14-dk0xxx            | [e644ef3b24](https://linux-hardware.org/?probe=e644ef3b24) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9ff409cce8](https://linux-hardware.org/?probe=9ff409cce8) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [79d149ff5c](https://linux-hardware.org/?probe=79d149ff5c) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b791be35c2](https://linux-hardware.org/?probe=b791be35c2) | May 10, 2023 |
| eMachines     | E625                        | [1271e33078](https://linux-hardware.org/?probe=1271e33078) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7058baf75d](https://linux-hardware.org/?probe=7058baf75d) | May 10, 2023 |
| eMachines     | E625                        | [3160c872b8](https://linux-hardware.org/?probe=3160c872b8) | May 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | [82c3d7dd74](https://linux-hardware.org/?probe=82c3d7dd74) | May 09, 2023 |
| Lanix Amer... | A V19                       | [31e64dbd5d](https://linux-hardware.org/?probe=31e64dbd5d) | May 08, 2023 |
| HP            | 15                          | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [75fe05267b](https://linux-hardware.org/?probe=75fe05267b) | May 08, 2023 |
| Apple         | MacBookPro9,2               | [a8d45ac430](https://linux-hardware.org/?probe=a8d45ac430) | May 07, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c3ef7b4de9](https://linux-hardware.org/?probe=c3ef7b4de9) | May 06, 2023 |
| HP            | Pavilion g4                 | [55a4a7978e](https://linux-hardware.org/?probe=55a4a7978e) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [fde0845fa4](https://linux-hardware.org/?probe=fde0845fa4) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [1a15177f0a](https://linux-hardware.org/?probe=1a15177f0a) | May 04, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | [3a9a2590e3](https://linux-hardware.org/?probe=3a9a2590e3) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | [fe2f2e420f](https://linux-hardware.org/?probe=fe2f2e420f) | May 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0784fc9b1c](https://linux-hardware.org/?probe=0784fc9b1c) | Apr 30, 2023 |
| Dell          | Latitude 5580               | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9c07454907](https://linux-hardware.org/?probe=9c07454907) | Apr 30, 2023 |
| HP            | Laptop 15-dw1xxx            | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| HP            | Laptop 15-dy2xxx            | [210ceedb6d](https://linux-hardware.org/?probe=210ceedb6d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| Acer          | Aspire A315-56              | [1fb0741f20](https://linux-hardware.org/?probe=1fb0741f20) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | [f43777b85b](https://linux-hardware.org/?probe=f43777b85b) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [c9ef115a29](https://linux-hardware.org/?probe=c9ef115a29) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [1602540ab8](https://linux-hardware.org/?probe=1602540ab8) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | [e05975b1cc](https://linux-hardware.org/?probe=e05975b1cc) | Apr 25, 2023 |
| DERE          | X16                         | [8c51699ade](https://linux-hardware.org/?probe=8c51699ade) | Apr 23, 2023 |
| Acer          | AOD270                      | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| Toshiba       | Satellite C845              | [8174d09074](https://linux-hardware.org/?probe=8174d09074) | Apr 21, 2023 |
| Dell          | G15 5510                    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| ASUSTek       | T100TAF                     | [9e59d428d2](https://linux-hardware.org/?probe=9e59d428d2) | Apr 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2cb8ecb34d](https://linux-hardware.org/?probe=2cb8ecb34d) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| HP            | Unknown                     | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| Apple         | MacBook4,1                  | [39057bb60a](https://linux-hardware.org/?probe=39057bb60a) | Apr 18, 2023 |
| Apple         | MacBook4,1                  | [ebfd8fec1b](https://linux-hardware.org/?probe=ebfd8fec1b) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [28f6e6e6c6](https://linux-hardware.org/?probe=28f6e6e6c6) | Apr 18, 2023 |
| HP            | ProBook 645 G1              | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ad381ae6d8](https://linux-hardware.org/?probe=ad381ae6d8) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [4644eb92ef](https://linux-hardware.org/?probe=4644eb92ef) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [52e4ec34e1](https://linux-hardware.org/?probe=52e4ec34e1) | Apr 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2e6b5600aa](https://linux-hardware.org/?probe=2e6b5600aa) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| Dell          | Vostro 14-3468              | [947f70ebf7](https://linux-hardware.org/?probe=947f70ebf7) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [77384847ef](https://linux-hardware.org/?probe=77384847ef) | Apr 12, 2023 |
| Dell          | Inspiron 15-3567            | [23c158b19b](https://linux-hardware.org/?probe=23c158b19b) | Apr 12, 2023 |
| HP            | ProBook 655 G1              | [aaef8a36db](https://linux-hardware.org/?probe=aaef8a36db) | Apr 10, 2023 |
| Gateway       | M-6812M                     | [6101b79a06](https://linux-hardware.org/?probe=6101b79a06) | Apr 08, 2023 |
| Samsung       | RV415/RV515                 | [fe77afbdfa](https://linux-hardware.org/?probe=fe77afbdfa) | Apr 07, 2023 |
| HP            | ProBook 6360b               | [bfa6c44b14](https://linux-hardware.org/?probe=bfa6c44b14) | Apr 07, 2023 |
| Acer          | Aspire 3680                 | [b5511d9060](https://linux-hardware.org/?probe=b5511d9060) | Apr 05, 2023 |
| Apple         | MacBookPro10,2              | [ad5d8f611a](https://linux-hardware.org/?probe=ad5d8f611a) | Apr 04, 2023 |
| Notebook      | L140PU                      | [628319771e](https://linux-hardware.org/?probe=628319771e) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | [9da88b2a33](https://linux-hardware.org/?probe=9da88b2a33) | Apr 04, 2023 |
| Sony          | VPCF236FM                   | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| Valve         | Jupiter                     | [7a6dcc077f](https://linux-hardware.org/?probe=7a6dcc077f) | Apr 03, 2023 |
| HP            | Unknown                     | [bd783cf180](https://linux-hardware.org/?probe=bd783cf180) | Apr 03, 2023 |
| HP            | 2000                        | [3fffec7875](https://linux-hardware.org/?probe=3fffec7875) | Apr 03, 2023 |
| HUAWEI        | HVY-WXX9                    | [63d38ddebf](https://linux-hardware.org/?probe=63d38ddebf) | Apr 02, 2023 |
| Dell          | System XPS L502X            | [2ed08c70a9](https://linux-hardware.org/?probe=2ed08c70a9) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [111eeac3b3](https://linux-hardware.org/?probe=111eeac3b3) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [2fcab6a925](https://linux-hardware.org/?probe=2fcab6a925) | Apr 01, 2023 |
| EVOO          | EVC156-1                    | [8e665ae8b2](https://linux-hardware.org/?probe=8e665ae8b2) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [f5db7a6030](https://linux-hardware.org/?probe=f5db7a6030) | Mar 30, 2023 |
| HP            | Notebook                    | [e631e8e62a](https://linux-hardware.org/?probe=e631e8e62a) | Mar 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [31d94ffb5f](https://linux-hardware.org/?probe=31d94ffb5f) | Mar 29, 2023 |
| Apple         | MacBookPro8,3               | [90fadbf903](https://linux-hardware.org/?probe=90fadbf903) | Mar 28, 2023 |
| Apple         | MacBookPro9,2               | [bce7f8b531](https://linux-hardware.org/?probe=bce7f8b531) | Mar 27, 2023 |
| Alienware     | 17 R4                       | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Lenovo        | IdeaPad Y910-17ISK 80V1     | [5e4e7975c1](https://linux-hardware.org/?probe=5e4e7975c1) | Mar 26, 2023 |
| HUAWEI        | BOHB-WAX9                   | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Toshiba       | Satellite C845D             | [32341bde2a](https://linux-hardware.org/?probe=32341bde2a) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| American M... | XA133PR110                  | [7e49d89ca8](https://linux-hardware.org/?probe=7e49d89ca8) | Mar 25, 2023 |
| ASUSTek       | N56VJ                       | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| HP            | Unknown                     | [c27dcda931](https://linux-hardware.org/?probe=c27dcda931) | Mar 24, 2023 |
| Dell          | Inspiron 7559               | [51aab276a2](https://linux-hardware.org/?probe=51aab276a2) | Mar 23, 2023 |
| ASUSTek       | X202EP                      | [5cc1f3216b](https://linux-hardware.org/?probe=5cc1f3216b) | Mar 23, 2023 |
| HP            | Unknown                     | [913aa678bf](https://linux-hardware.org/?probe=913aa678bf) | Mar 23, 2023 |
| Lenovo        | Yoga 500-14IBD 80N4         | [f364402e8a](https://linux-hardware.org/?probe=f364402e8a) | Mar 23, 2023 |
| HONOR         | BBR-WAX9                    | [b16e6324ed](https://linux-hardware.org/?probe=b16e6324ed) | Mar 22, 2023 |
| Dell          | G15 5511                    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | G15 5510                    | [3ddfc82bcd](https://linux-hardware.org/?probe=3ddfc82bcd) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | [8a70a156a4](https://linux-hardware.org/?probe=8a70a156a4) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6dc3256710](https://linux-hardware.org/?probe=6dc3256710) | Mar 21, 2023 |
| HP            | Unknown                     | [66723d18e0](https://linux-hardware.org/?probe=66723d18e0) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | [56b1138062](https://linux-hardware.org/?probe=56b1138062) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | [1fe782c379](https://linux-hardware.org/?probe=1fe782c379) | Mar 21, 2023 |
| HP            | Laptop 14-cm0xxx            | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Lenovo        | G40-80 80E4                 | [70b2fab92b](https://linux-hardware.org/?probe=70b2fab92b) | Mar 17, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [70812fb9c8](https://linux-hardware.org/?probe=70812fb9c8) | Mar 17, 2023 |
| HP            | Pavilion Notebook           | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Toshiba       | Satellite P55t-B            | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [f3dd1409f6](https://linux-hardware.org/?probe=f3dd1409f6) | Mar 14, 2023 |
| HUAWEI        | NBM-WXX9                    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f91bf005b0](https://linux-hardware.org/?probe=f91bf005b0) | Mar 11, 2023 |
| HP            | Pavilion Notebook           | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Acer          | Aspire R3-131T              | [94435f58ed](https://linux-hardware.org/?probe=94435f58ed) | Mar 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e770c2f24c](https://linux-hardware.org/?probe=e770c2f24c) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| Dell          | G3 3500                     | [5cfed5bee9](https://linux-hardware.org/?probe=5cfed5bee9) | Mar 10, 2023 |
| HP            | Pavilion dv4                | [79a8c505ef](https://linux-hardware.org/?probe=79a8c505ef) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d677609a51](https://linux-hardware.org/?probe=d677609a51) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [67d9219fc2](https://linux-hardware.org/?probe=67d9219fc2) | Mar 07, 2023 |
| Dell          | Inspiron 5567               | [780dc15bcc](https://linux-hardware.org/?probe=780dc15bcc) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6f7e8084e5](https://linux-hardware.org/?probe=6f7e8084e5) | Mar 04, 2023 |
| HP            | ProBook 6360b               | [8b6826988f](https://linux-hardware.org/?probe=8b6826988f) | Mar 03, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [c3113c9da6](https://linux-hardware.org/?probe=c3113c9da6) | Mar 02, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [73efff8199](https://linux-hardware.org/?probe=73efff8199) | Mar 02, 2023 |
| HP            | Pavilion 14                 | [ae0e65f5d1](https://linux-hardware.org/?probe=ae0e65f5d1) | Feb 28, 2023 |
| Dell          | Latitude E7270              | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| Dell          | Latitude E7450              | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| HP            | Pavilion 14                 | [c9b9f213b5](https://linux-hardware.org/?probe=c9b9f213b5) | Feb 26, 2023 |
| Lenovo        | B40-45 20394                | [8472ed364a](https://linux-hardware.org/?probe=8472ed364a) | Feb 26, 2023 |
| HUAWEI        | WRT-WX9                     | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Alienware     | 17 R4                       | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| Valve         | Jupiter                     | [0ec37b6ef2](https://linux-hardware.org/?probe=0ec37b6ef2) | Feb 25, 2023 |
| Chuwi         | HeroBook Air                | [8daed679c2](https://linux-hardware.org/?probe=8daed679c2) | Feb 24, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [bfd3019210](https://linux-hardware.org/?probe=bfd3019210) | Feb 22, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| Toshiba       | Satellite C50D-A            | [3e9201a0fe](https://linux-hardware.org/?probe=3e9201a0fe) | Feb 20, 2023 |
| HP            | Pavilion g6                 | [2b4de6efbe](https://linux-hardware.org/?probe=2b4de6efbe) | Feb 18, 2023 |
| Dell          | Studio 1558                 | [4a2f0524b9](https://linux-hardware.org/?probe=4a2f0524b9) | Feb 17, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Dell          | Latitude E7440              | [86f8d34ba7](https://linux-hardware.org/?probe=86f8d34ba7) | Feb 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [269420c3fe](https://linux-hardware.org/?probe=269420c3fe) | Feb 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [de592b6218](https://linux-hardware.org/?probe=de592b6218) | Feb 14, 2023 |
| Dell          | Latitude E7270              | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| HP            | Laptop 15-da2xxx            | [41bf5d50f8](https://linux-hardware.org/?probe=41bf5d50f8) | Feb 14, 2023 |
| Dell          | Inspiron 5555               | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [cfeb6479d1](https://linux-hardware.org/?probe=cfeb6479d1) | Feb 13, 2023 |
| Apple         | MacBookPro10,2              | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| Dell          | Latitude E7270              | [c684709755](https://linux-hardware.org/?probe=c684709755) | Feb 11, 2023 |
| HP            | Laptop 15-da2xxx            | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| HONOR         | NMH-WCX9                    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| HP            | 240 G3                      | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| HP            | Laptop 15-bw0xx             | [da8dac3c03](https://linux-hardware.org/?probe=da8dac3c03) | Feb 07, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [f7c5e9e498](https://linux-hardware.org/?probe=f7c5e9e498) | Feb 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [44aed7e81a](https://linux-hardware.org/?probe=44aed7e81a) | Feb 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [5acc007668](https://linux-hardware.org/?probe=5acc007668) | Feb 04, 2023 |
| HP            | 240 G3                      | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 240 G3                      | [a977b66ced](https://linux-hardware.org/?probe=a977b66ced) | Feb 02, 2023 |
| HP            | 240 G3                      | [816a3f4b28](https://linux-hardware.org/?probe=816a3f4b28) | Feb 02, 2023 |
| HUAWEI        | KLVD-WXX9                   | [6546c6e279](https://linux-hardware.org/?probe=6546c6e279) | Feb 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [73230e9490](https://linux-hardware.org/?probe=73230e9490) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| ASUSTek       | N56VB                       | [d5b5c983c9](https://linux-hardware.org/?probe=d5b5c983c9) | Feb 02, 2023 |
| Apple         | MacBookPro15,2              | [7c17db143e](https://linux-hardware.org/?probe=7c17db143e) | Feb 01, 2023 |
| Apple         | MacBookPro8,1               | [13467e9e83](https://linux-hardware.org/?probe=13467e9e83) | Feb 01, 2023 |
| Dell          | Latitude 5430               | [2afa57d0fa](https://linux-hardware.org/?probe=2afa57d0fa) | Feb 01, 2023 |
| Apple         | MacBookPro15,2              | [7612aba4cb](https://linux-hardware.org/?probe=7612aba4cb) | Jan 31, 2023 |
| Lenovo        | ThinkPad T430 2349A44       | [9f8528c5da](https://linux-hardware.org/?probe=9f8528c5da) | Jan 31, 2023 |
| Dell          | G15 5511                    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| Dell          | G15 5515                    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| HP            | Laptop 15-da2xxx            | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| HP            | Laptop 15-dw1xxx            | [c7d825c34c](https://linux-hardware.org/?probe=c7d825c34c) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [bd58d910f7](https://linux-hardware.org/?probe=bd58d910f7) | Jan 25, 2023 |
| Dell          | Latitude E5440              | [f8e7f1785b](https://linux-hardware.org/?probe=f8e7f1785b) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [65b6391803](https://linux-hardware.org/?probe=65b6391803) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Dell          | Inspiron 5558               | [bf87467519](https://linux-hardware.org/?probe=bf87467519) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [57ed6980d4](https://linux-hardware.org/?probe=57ed6980d4) | Jan 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS27Y0... | [e1678320fc](https://linux-hardware.org/?probe=e1678320fc) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [0667ad7cee](https://linux-hardware.org/?probe=0667ad7cee) | Jan 22, 2023 |
| Apple         | MacBook5,1                  | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9c9279b845](https://linux-hardware.org/?probe=9c9279b845) | Jan 19, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | Laptop 15-dy2xxx            | [7e61f98275](https://linux-hardware.org/?probe=7e61f98275) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HUAWEI        | EMD-WXX                     | [3709c83303](https://linux-hardware.org/?probe=3709c83303) | Jan 15, 2023 |
| HUAWEI        | EMD-WXX                     | [6eeac14bb9](https://linux-hardware.org/?probe=6eeac14bb9) | Jan 15, 2023 |
| Dell          | Latitude E6440              | [d04d05f246](https://linux-hardware.org/?probe=d04d05f246) | Jan 14, 2023 |
| Lenovo        | B490 20205                  | [14243e79d2](https://linux-hardware.org/?probe=14243e79d2) | Jan 13, 2023 |
| HP            | ProBook 4230s               | [63a87864b9](https://linux-hardware.org/?probe=63a87864b9) | Jan 12, 2023 |
| HP            | ProBook 4230s               | [9a6505c0aa](https://linux-hardware.org/?probe=9a6505c0aa) | Jan 12, 2023 |
| Lenovo        | Y50-70 20378                | [64ec4b6816](https://linux-hardware.org/?probe=64ec4b6816) | Jan 12, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [d859e0ff10](https://linux-hardware.org/?probe=d859e0ff10) | Jan 12, 2023 |
| Gateway       | M-6854m                     | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| Dell          | Precision M4400             | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8c1eb7fc02](https://linux-hardware.org/?probe=8c1eb7fc02) | Jan 11, 2023 |
| Lenovo        | Y50-70 20378                | [9cd68b4513](https://linux-hardware.org/?probe=9cd68b4513) | Jan 11, 2023 |
| Sony          | VPCEH1AFX                   | [3f64681bc7](https://linux-hardware.org/?probe=3f64681bc7) | Jan 11, 2023 |
| HP            | Pavilion Notebook           | [2132701432](https://linux-hardware.org/?probe=2132701432) | Jan 11, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Valve         | Jupiter                     | [57b570af42](https://linux-hardware.org/?probe=57b570af42) | Jan 09, 2023 |
| HP            | Pavilion 15                 | [2937882035](https://linux-hardware.org/?probe=2937882035) | Jan 08, 2023 |
| Notebook      | W9x0LU                      | [a81dd09b0c](https://linux-hardware.org/?probe=a81dd09b0c) | Jan 07, 2023 |
| HP            | Stream Laptop 11-y0XX       | [b40a3e32e9](https://linux-hardware.org/?probe=b40a3e32e9) | Jan 06, 2023 |
| HP            | Stream Laptop 11-y0XX       | [73db1ffcf6](https://linux-hardware.org/?probe=73db1ffcf6) | Jan 06, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| Lenovo        | G580 20157                  | [c0199fa7bf](https://linux-hardware.org/?probe=c0199fa7bf) | Jan 05, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [23bfcb7f4c](https://linux-hardware.org/?probe=23bfcb7f4c) | Jan 04, 2023 |
| HP            | EliteBook 840 G5            | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| HP            | EliteBook 8460p             | [3365055862](https://linux-hardware.org/?probe=3365055862) | Jan 02, 2023 |
| HP            | EliteBook 8460p             | [45184e1f70](https://linux-hardware.org/?probe=45184e1f70) | Jan 02, 2023 |
| HP            | Laptop 15-dy2xxx            | [8c76b9ad8e](https://linux-hardware.org/?probe=8c76b9ad8e) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [0179007813](https://linux-hardware.org/?probe=0179007813) | Jan 01, 2023 |
| Acer          | Aspire A114-33              | [bba53b0159](https://linux-hardware.org/?probe=bba53b0159) | Jan 01, 2023 |
| Toshiba       | Satellite A305D             | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| Acer          | Aspire R7-371T              | [057e717cb7](https://linux-hardware.org/?probe=057e717cb7) | Dec 30, 2022 |
| HP            | 240 G7 Notebook PC          | [414db30bff](https://linux-hardware.org/?probe=414db30bff) | Dec 30, 2022 |
| ASUSTek       | N56VB                       | [6201ddc028](https://linux-hardware.org/?probe=6201ddc028) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| Dell          | Inspiron MM061              | [34804f8a34](https://linux-hardware.org/?probe=34804f8a34) | Dec 29, 2022 |
| HUAWEI        | HVY-WXX9                    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | Laptop 14-fq0xxx            | [e020678b51](https://linux-hardware.org/?probe=e020678b51) | Dec 28, 2022 |
| HP            | Laptop 15-dy2xxx            | [8e2393e7b4](https://linux-hardware.org/?probe=8e2393e7b4) | Dec 26, 2022 |
| Acer          | Aspire E1-522               | [8bf37cf82d](https://linux-hardware.org/?probe=8bf37cf82d) | Dec 26, 2022 |
| HP            | ProBook 6470b               | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Google        | Bobba360                    | [bdad461cec](https://linux-hardware.org/?probe=bdad461cec) | Dec 23, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [77e30fee83](https://linux-hardware.org/?probe=77e30fee83) | Dec 23, 2022 |
| Schenker      | VIA 15 Pro                  | [b1a40c91d2](https://linux-hardware.org/?probe=b1a40c91d2) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | [75efe6fb52](https://linux-hardware.org/?probe=75efe6fb52) | Dec 22, 2022 |
| Dell          | Inspiron 7559               | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| Acer          | Aspire A515-51              | [29af4c3712](https://linux-hardware.org/?probe=29af4c3712) | Dec 20, 2022 |
| Google        | Coral                       | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [96dcb47ba1](https://linux-hardware.org/?probe=96dcb47ba1) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7c678e18cd](https://linux-hardware.org/?probe=7c678e18cd) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AMA40QLM    | [ec9133f05d](https://linux-hardware.org/?probe=ec9133f05d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| Valve         | Jupiter                     | [f89644c711](https://linux-hardware.org/?probe=f89644c711) | Dec 15, 2022 |
| HP            | Laptop 15-da2xxx            | [cd64f27416](https://linux-hardware.org/?probe=cd64f27416) | Dec 14, 2022 |
| MSI           | GL75 Leopard 10SDK          | [03dc950ee5](https://linux-hardware.org/?probe=03dc950ee5) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [b2d808ab85](https://linux-hardware.org/?probe=b2d808ab85) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | [36bd6688bb](https://linux-hardware.org/?probe=36bd6688bb) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | [ed5d274c1a](https://linux-hardware.org/?probe=ed5d274c1a) | Dec 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [5ea80edee8](https://linux-hardware.org/?probe=5ea80edee8) | Dec 14, 2022 |
| Alienware     | 15 R4                       | [f365266667](https://linux-hardware.org/?probe=f365266667) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| Toshiba       | TECRA A10                   | [760bda2b7d](https://linux-hardware.org/?probe=760bda2b7d) | Dec 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | [469a37f1e4](https://linux-hardware.org/?probe=469a37f1e4) | Dec 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [bdddbb7807](https://linux-hardware.org/?probe=bdddbb7807) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Toshiba       | Satellite L855              | [932d8fec2d](https://linux-hardware.org/?probe=932d8fec2d) | Dec 12, 2022 |
| Sony          | VGN-NS220TH                 | [29e1373be4](https://linux-hardware.org/?probe=29e1373be4) | Dec 11, 2022 |
| Sony          | VPCEE27FL                   | [dd2bc8b6ff](https://linux-hardware.org/?probe=dd2bc8b6ff) | Dec 10, 2022 |
| Dell          | Latitude E6420              | [acd81c73d0](https://linux-hardware.org/?probe=acd81c73d0) | Dec 09, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [38d274571d](https://linux-hardware.org/?probe=38d274571d) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1595cc246a](https://linux-hardware.org/?probe=1595cc246a) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [94c151e95d](https://linux-hardware.org/?probe=94c151e95d) | Dec 09, 2022 |
| HP            | Pavilion dv5                | [cdd08235ff](https://linux-hardware.org/?probe=cdd08235ff) | Dec 09, 2022 |
| Acer          | TravelMate 5720             | [d0a54f621e](https://linux-hardware.org/?probe=d0a54f621e) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | [148040d1fd](https://linux-hardware.org/?probe=148040d1fd) | Dec 09, 2022 |
| Acer          | TravelMate B117-M           | [00ff19b078](https://linux-hardware.org/?probe=00ff19b078) | Dec 08, 2022 |
| Acer          | Aspire A315-51              | [3ab56a93d6](https://linux-hardware.org/?probe=3ab56a93d6) | Dec 07, 2022 |
| HP            | Pavilion dv6000 (RV009UA... | [6dcd661136](https://linux-hardware.org/?probe=6dcd661136) | Dec 05, 2022 |
| HP            | 15                          | [132fad5c38](https://linux-hardware.org/?probe=132fad5c38) | Dec 04, 2022 |
| Acer          | TravelMate B117-M           | [0b86a9c3b9](https://linux-hardware.org/?probe=0b86a9c3b9) | Dec 03, 2022 |
| HP            | Pavilion g4                 | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| MSI           | GE75 Raider 10SE            | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| HP            | Pavilion 14                 | [dedd30adc4](https://linux-hardware.org/?probe=dedd30adc4) | Nov 30, 2022 |
| Sony          | VGN-NS150FJ                 | [e675a19a27](https://linux-hardware.org/?probe=e675a19a27) | Nov 29, 2022 |
| Apple         | MacBookPro8,1               | [7ba1690c68](https://linux-hardware.org/?probe=7ba1690c68) | Nov 28, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [a7b7f4f100](https://linux-hardware.org/?probe=a7b7f4f100) | Nov 25, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AX05    | [c4a2ce46ca](https://linux-hardware.org/?probe=c4a2ce46ca) | Nov 24, 2022 |
| HUAWEI        | CREM-WXX9                   | [240694e932](https://linux-hardware.org/?probe=240694e932) | Nov 23, 2022 |
| HP            | Notebook                    | [616c071073](https://linux-hardware.org/?probe=616c071073) | Nov 23, 2022 |
| Dell          | G3 3579                     | [7f4d27ea26](https://linux-hardware.org/?probe=7f4d27ea26) | Nov 23, 2022 |
| Unknown       | Unknown                     | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| Toshiba       | Satellite L45Dt-B           | [9cdcee20dc](https://linux-hardware.org/?probe=9cdcee20dc) | Nov 22, 2022 |
| Valve         | Jupiter                     | [e9f2caddf6](https://linux-hardware.org/?probe=e9f2caddf6) | Nov 21, 2022 |
| MSI           | Stealth GS66 12UGS          | [ca3d88f38d](https://linux-hardware.org/?probe=ca3d88f38d) | Nov 21, 2022 |
| Dell          | Latitude E5440              | [f423bbe9b0](https://linux-hardware.org/?probe=f423bbe9b0) | Nov 19, 2022 |
| Dell          | Latitude E5440              | [0f98fe6066](https://linux-hardware.org/?probe=0f98fe6066) | Nov 18, 2022 |
| HP            | Laptop 15-da2xxx            | [e55a0e2ae1](https://linux-hardware.org/?probe=e55a0e2ae1) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [c08218542c](https://linux-hardware.org/?probe=c08218542c) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [4830cb0a27](https://linux-hardware.org/?probe=4830cb0a27) | Nov 17, 2022 |
| ASUSTek       | X556UQK                     | [fb33c2bdea](https://linux-hardware.org/?probe=fb33c2bdea) | Nov 16, 2022 |
| ASUSTek       | X556UQK                     | [b4f8d67230](https://linux-hardware.org/?probe=b4f8d67230) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f29e7d7659](https://linux-hardware.org/?probe=f29e7d7659) | Nov 16, 2022 |
| HP            | Laptop 15-da2xxx            | [b1ed3e6190](https://linux-hardware.org/?probe=b1ed3e6190) | Nov 16, 2022 |
| HP            | EliteBook 820 G3            | [fe84036164](https://linux-hardware.org/?probe=fe84036164) | Nov 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b9d92c6041](https://linux-hardware.org/?probe=b9d92c6041) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [61b131a3ae](https://linux-hardware.org/?probe=61b131a3ae) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [3f3280fa71](https://linux-hardware.org/?probe=3f3280fa71) | Nov 13, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [9a69ea4724](https://linux-hardware.org/?probe=9a69ea4724) | Nov 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [416c73c293](https://linux-hardware.org/?probe=416c73c293) | Nov 09, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [eac572ee3d](https://linux-hardware.org/?probe=eac572ee3d) | Nov 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [6b1f5f2c2a](https://linux-hardware.org/?probe=6b1f5f2c2a) | Nov 08, 2022 |
| Chuwi         | GemiBook Pro                | [315d8b6ff7](https://linux-hardware.org/?probe=315d8b6ff7) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Google        | Grunt                       | [dc9067b4b6](https://linux-hardware.org/?probe=dc9067b4b6) | Nov 07, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [20826ec148](https://linux-hardware.org/?probe=20826ec148) | Nov 06, 2022 |
| Lenovo        | G485 20136                  | [f8ee5082f8](https://linux-hardware.org/?probe=f8ee5082f8) | Nov 06, 2022 |
| Lenovo        | G40-30 80FY                 | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [41e941e3ca](https://linux-hardware.org/?probe=41e941e3ca) | Nov 03, 2022 |
| HP            | Laptop 17-ca0xxx            | [af3aa996df](https://linux-hardware.org/?probe=af3aa996df) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | [caaca6d1f1](https://linux-hardware.org/?probe=caaca6d1f1) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [7a5f1eaf6c](https://linux-hardware.org/?probe=7a5f1eaf6c) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [cecc0cca9d](https://linux-hardware.org/?probe=cecc0cca9d) | Nov 03, 2022 |
| Toshiba       | Satellite L55-B             | [ca03715db3](https://linux-hardware.org/?probe=ca03715db3) | Nov 03, 2022 |
| Acer          | Aspire E5-522               | [32f73c64a6](https://linux-hardware.org/?probe=32f73c64a6) | Nov 02, 2022 |
| Acer          | Aspire E5-522               | [412b8c701e](https://linux-hardware.org/?probe=412b8c701e) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [95d825cd94](https://linux-hardware.org/?probe=95d825cd94) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| Dell          | Inspiron 5537               | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| ASUSTek       | X556UQK                     | [f8bdcbce4e](https://linux-hardware.org/?probe=f8bdcbce4e) | Oct 29, 2022 |
| GPU Compan... | GWNR71517                   | [168f199ffd](https://linux-hardware.org/?probe=168f199ffd) | Oct 29, 2022 |
| Dell          | Latitude 3590               | [d1b6c7cd85](https://linux-hardware.org/?probe=d1b6c7cd85) | Oct 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0957761dea](https://linux-hardware.org/?probe=0957761dea) | Oct 28, 2022 |
| HP            | Laptop 15-da2xxx            | [071938b19a](https://linux-hardware.org/?probe=071938b19a) | Oct 28, 2022 |
| GPU Compan... | GWNR71517                   | [e03f1db8e1](https://linux-hardware.org/?probe=e03f1db8e1) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | [16b3338525](https://linux-hardware.org/?probe=16b3338525) | Oct 27, 2022 |
| HP            | EliteBook 8570w             | [7d30f96368](https://linux-hardware.org/?probe=7d30f96368) | Oct 27, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Dell          | Latitude 9420               | [ab37e0d841](https://linux-hardware.org/?probe=ab37e0d841) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [3b6666b5ba](https://linux-hardware.org/?probe=3b6666b5ba) | Oct 24, 2022 |
| Dell          | Inspiron 3505               | [891f846aac](https://linux-hardware.org/?probe=891f846aac) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [487a972bda](https://linux-hardware.org/?probe=487a972bda) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| HP            | Laptop 15-da2xxx            | [a9de489f26](https://linux-hardware.org/?probe=a9de489f26) | Oct 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [914bab2302](https://linux-hardware.org/?probe=914bab2302) | Oct 20, 2022 |
| Dell          | Inspiron 7460               | [879fabd350](https://linux-hardware.org/?probe=879fabd350) | Oct 20, 2022 |
| GPU Compan... | GWNR71517                   | [f467f29abf](https://linux-hardware.org/?probe=f467f29abf) | Oct 19, 2022 |
| Lenovo        | Yoga 900-13ISK2 80UE        | [efadc96c65](https://linux-hardware.org/?probe=efadc96c65) | Oct 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c14937070e](https://linux-hardware.org/?probe=c14937070e) | Oct 19, 2022 |
| Lenovo        | G450 2949                   | [13c0232085](https://linux-hardware.org/?probe=13c0232085) | Oct 19, 2022 |
| Lenovo        | G450 2949                   | [1e5a91a31d](https://linux-hardware.org/?probe=1e5a91a31d) | Oct 18, 2022 |
| Dell          | Latitude 7430               | [d4d6f89390](https://linux-hardware.org/?probe=d4d6f89390) | Oct 18, 2022 |
| HP            | Unknown                     | [4a0df43034](https://linux-hardware.org/?probe=4a0df43034) | Oct 17, 2022 |
| Dell          | Vostro 14-3468              | [c0958ba47f](https://linux-hardware.org/?probe=c0958ba47f) | Oct 17, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [2dd84a41e8](https://linux-hardware.org/?probe=2dd84a41e8) | Oct 17, 2022 |
| HP            | 245 G7 Notebook PC          | [c164c2ab59](https://linux-hardware.org/?probe=c164c2ab59) | Oct 16, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [87cf4b398b](https://linux-hardware.org/?probe=87cf4b398b) | Oct 16, 2022 |
| HUAWEI        | CREM-WXX9                   | [3edd19f985](https://linux-hardware.org/?probe=3edd19f985) | Oct 15, 2022 |
| Dell          | Latitude E5440              | [432aa93109](https://linux-hardware.org/?probe=432aa93109) | Oct 14, 2022 |
| HP            | Laptop 14-bw0xx             | [3a190d5718](https://linux-hardware.org/?probe=3a190d5718) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [2813d441b5](https://linux-hardware.org/?probe=2813d441b5) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [4039ed6d6f](https://linux-hardware.org/?probe=4039ed6d6f) | Oct 13, 2022 |
| Toshiba       | Satellite P55t-A            | [60d52e85a0](https://linux-hardware.org/?probe=60d52e85a0) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| MSI           | GV62 8RD                    | [8902a355f4](https://linux-hardware.org/?probe=8902a355f4) | Oct 09, 2022 |
| Dell          | System XPS L502X            | [cd40a3f168](https://linux-hardware.org/?probe=cd40a3f168) | Oct 08, 2022 |
| Dell          | Inspiron 3520               | [5cf6d495ff](https://linux-hardware.org/?probe=5cf6d495ff) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| Dell          | Precision 5530              | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [167321509c](https://linux-hardware.org/?probe=167321509c) | Oct 07, 2022 |
| Apple         | MacBookPro8,1               | [0d9e169836](https://linux-hardware.org/?probe=0d9e169836) | Oct 06, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0382d1ec36](https://linux-hardware.org/?probe=0382d1ec36) | Oct 02, 2022 |
| HP            | ProBook 6470b               | [10438199c4](https://linux-hardware.org/?probe=10438199c4) | Oct 02, 2022 |
| HP            | Unknown                     | [72a00fa1a2](https://linux-hardware.org/?probe=72a00fa1a2) | Oct 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion                    | [124e8b760a](https://linux-hardware.org/?probe=124e8b760a) | Oct 01, 2022 |
| EVOO          | EG-LP10                     | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| GHIA          | LFI3H                       | [4233e4e6c5](https://linux-hardware.org/?probe=4233e4e6c5) | Sep 29, 2022 |
| GHIA          | LFI3H                       | [482e78460a](https://linux-hardware.org/?probe=482e78460a) | Sep 29, 2022 |
| HP            | Pavilion Notebook           | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HUAWEI        | HVY-WXX9                    | [4f2655de78](https://linux-hardware.org/?probe=4f2655de78) | Sep 29, 2022 |
| Lenovo        | ThinkPad T430 23501K0       | [124afba97e](https://linux-hardware.org/?probe=124afba97e) | Sep 28, 2022 |
| Apple         | MacBookPro8,1               | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| Dell          | Latitude E7440              | [d211ff97c6](https://linux-hardware.org/?probe=d211ff97c6) | Sep 27, 2022 |
| Dell          | Latitude E5450              | [8738ac7280](https://linux-hardware.org/?probe=8738ac7280) | Sep 26, 2022 |
| HP            | Unknown                     | [63af86aa38](https://linux-hardware.org/?probe=63af86aa38) | Sep 25, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| Chuwi         | CoreBook XPro               | [5ace2b3ea5](https://linux-hardware.org/?probe=5ace2b3ea5) | Sep 23, 2022 |
| MSI           | Prestige 14Evo A11M         | [609225524a](https://linux-hardware.org/?probe=609225524a) | Sep 23, 2022 |
| ASUSTek       | G750JM                      | [2e53c11312](https://linux-hardware.org/?probe=2e53c11312) | Sep 22, 2022 |
| MSI           | GT70 2OC/2OD                | [c6a0b0d987](https://linux-hardware.org/?probe=c6a0b0d987) | Sep 22, 2022 |
| Lenovo        | G40-80 80E4                 | [575b85b038](https://linux-hardware.org/?probe=575b85b038) | Sep 21, 2022 |
| Lenovo        | G40-80 80E4                 | [18a0a2158c](https://linux-hardware.org/?probe=18a0a2158c) | Sep 21, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| American M... | XA133PR110                  | [b79d35c0bd](https://linux-hardware.org/?probe=b79d35c0bd) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Sony          | VPCF236FM                   | [397f485cfc](https://linux-hardware.org/?probe=397f485cfc) | Sep 19, 2022 |
| HP            | EliteBook 2740p             | [6643773237](https://linux-hardware.org/?probe=6643773237) | Sep 18, 2022 |
| HP            | Notebook                    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| ASUSTek       | X555DG                      | [c46c229dfb](https://linux-hardware.org/?probe=c46c229dfb) | Sep 16, 2022 |
| ASUSTek       | X555DG                      | [e39d4a8247](https://linux-hardware.org/?probe=e39d4a8247) | Sep 16, 2022 |
| Toshiba       | Satellite L855              | [1065197a6e](https://linux-hardware.org/?probe=1065197a6e) | Sep 15, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | [9e0c10b8e3](https://linux-hardware.org/?probe=9e0c10b8e3) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| Dell          | Latitude E6400              | [0c6b0c35e6](https://linux-hardware.org/?probe=0c6b0c35e6) | Sep 14, 2022 |
| Dell          | Latitude E6400              | [b4c9fcf4c3](https://linux-hardware.org/?probe=b4c9fcf4c3) | Sep 14, 2022 |
| Lanix         | AL V9                       | [03e7c7ece5](https://linux-hardware.org/?probe=03e7c7ece5) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| Chuwi         | GemiBook Pro                | [5b62dddb37](https://linux-hardware.org/?probe=5b62dddb37) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [d1b95841a4](https://linux-hardware.org/?probe=d1b95841a4) | Sep 13, 2022 |
| HP            | EliteBook 745 G6            | [61da5fee97](https://linux-hardware.org/?probe=61da5fee97) | Sep 13, 2022 |
| Lanix         | AL V9                       | [e03f9aecc3](https://linux-hardware.org/?probe=e03f9aecc3) | Sep 12, 2022 |
| ASUSTek       | X553MA                      | [32c5b56788](https://linux-hardware.org/?probe=32c5b56788) | Sep 11, 2022 |
| Lenovo        | G50-45 80E3                 | [2f4b4e4203](https://linux-hardware.org/?probe=2f4b4e4203) | Sep 10, 2022 |
| Gateway       | NE56R                       | [c928861fb0](https://linux-hardware.org/?probe=c928861fb0) | Sep 09, 2022 |
| Gateway       | NE56R                       | [3167a59b9b](https://linux-hardware.org/?probe=3167a59b9b) | Sep 09, 2022 |
| ASUSTek       | X553MA                      | [32edc5cfad](https://linux-hardware.org/?probe=32edc5cfad) | Sep 08, 2022 |
| Apple         | MacBook4,1                  | [500d050ad6](https://linux-hardware.org/?probe=500d050ad6) | Sep 06, 2022 |
| Dell          | Latitude D410               | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| HP            | Laptop 15-bw0xx             | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | [01b8531ddf](https://linux-hardware.org/?probe=01b8531ddf) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | [9e4c1bc292](https://linux-hardware.org/?probe=9e4c1bc292) | Sep 04, 2022 |
| Dell          | Latitude E7450              | [de66677d3d](https://linux-hardware.org/?probe=de66677d3d) | Sep 03, 2022 |
| HP            | Pavilion 14                 | [7a2b6c5f4b](https://linux-hardware.org/?probe=7a2b6c5f4b) | Sep 02, 2022 |
| Dell          | Inspiron 5559               | [7da5af06fb](https://linux-hardware.org/?probe=7da5af06fb) | Sep 02, 2022 |
| Dell          | Inspiron 5559               | [c7b43caa52](https://linux-hardware.org/?probe=c7b43caa52) | Sep 01, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | [bceac5a658](https://linux-hardware.org/?probe=bceac5a658) | Aug 30, 2022 |
| Toshiba       | Satellite C845              | [58d3152512](https://linux-hardware.org/?probe=58d3152512) | Aug 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c44a50e117](https://linux-hardware.org/?probe=c44a50e117) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6f169db96b](https://linux-hardware.org/?probe=6f169db96b) | Aug 29, 2022 |
| HUAWEI        | KLVL-WXXW                   | [829a45ed6f](https://linux-hardware.org/?probe=829a45ed6f) | Aug 28, 2022 |
| HP            | 240 G7 Notebook PC          | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8021bbb58b](https://linux-hardware.org/?probe=8021bbb58b) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| MSI           | GL75 Leopard 10SDK          | [7004b23b33](https://linux-hardware.org/?probe=7004b23b33) | Aug 23, 2022 |
| HP            | ENVY m6 Notebook            | [c51af546e7](https://linux-hardware.org/?probe=c51af546e7) | Aug 22, 2022 |
| HP            | Pavilion dv7                | [81b7ddb4e9](https://linux-hardware.org/?probe=81b7ddb4e9) | Aug 21, 2022 |
| Dell          | Inspiron 5447               | [aa44fba5de](https://linux-hardware.org/?probe=aa44fba5de) | Aug 21, 2022 |
| Dell          | Inspiron 5447               | [21d9982f20](https://linux-hardware.org/?probe=21d9982f20) | Aug 21, 2022 |
| HUAWEI        | EMD-WXX                     | [1ee66f2c65](https://linux-hardware.org/?probe=1ee66f2c65) | Aug 20, 2022 |
| HUAWEI        | EMD-WXX                     | [9c4217c76b](https://linux-hardware.org/?probe=9c4217c76b) | Aug 19, 2022 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d78fb85708](https://linux-hardware.org/?probe=d78fb85708) | Aug 18, 2022 |
| Acer          | Aspire E5-573               | [1815c3a2f2](https://linux-hardware.org/?probe=1815c3a2f2) | Aug 17, 2022 |
| HP            | 240 G7 Notebook PC          | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| HP            | Pavilion TS 14              | [145fc8369f](https://linux-hardware.org/?probe=145fc8369f) | Aug 16, 2022 |
| Acer          | Aspire E5-573               | [d3bd05f20b](https://linux-hardware.org/?probe=d3bd05f20b) | Aug 16, 2022 |
| Toshiba       | Satellite P200              | [83fcabac55](https://linux-hardware.org/?probe=83fcabac55) | Aug 13, 2022 |
| Dell          | Vostro 1520                 | [9dab88f3ee](https://linux-hardware.org/?probe=9dab88f3ee) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| HP            | Pavilion Notebook           | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Sony          | VPCYB20AL                   | [f886e2ff98](https://linux-hardware.org/?probe=f886e2ff98) | Aug 10, 2022 |
| Lenovo        | L340-15API 81LW             | [50eca7fa1e](https://linux-hardware.org/?probe=50eca7fa1e) | Aug 10, 2022 |
| HUAWEI        | WRT-WX9                     | [f9c85afff2](https://linux-hardware.org/?probe=f9c85afff2) | Aug 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [dee5c21fb7](https://linux-hardware.org/?probe=dee5c21fb7) | Aug 09, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [699bd44c36](https://linux-hardware.org/?probe=699bd44c36) | Aug 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7dc1825a38](https://linux-hardware.org/?probe=7dc1825a38) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0a6068ab6b](https://linux-hardware.org/?probe=0a6068ab6b) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Google        | Blorb                       | [b893b34702](https://linux-hardware.org/?probe=b893b34702) | Aug 06, 2022 |
| Acer          | AO756                       | [4bc715a31c](https://linux-hardware.org/?probe=4bc715a31c) | Aug 05, 2022 |
| Dell          | Inspiron 5559               | [3e02305524](https://linux-hardware.org/?probe=3e02305524) | Aug 04, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [5ab9ae3992](https://linux-hardware.org/?probe=5ab9ae3992) | Aug 03, 2022 |
| HP            | ProBook 4520s               | [8e03860e5f](https://linux-hardware.org/?probe=8e03860e5f) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| Alienware     | 17 R4                       | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [057703210a](https://linux-hardware.org/?probe=057703210a) | Jul 28, 2022 |
| Sony          | VPCS110FL                   | [8576955f3c](https://linux-hardware.org/?probe=8576955f3c) | Jul 28, 2022 |
| HP            | ProBook 4520s               | [80024f9b67](https://linux-hardware.org/?probe=80024f9b67) | Jul 26, 2022 |
| HP            | 245 G7 Notebook PC          | [07c70033f5](https://linux-hardware.org/?probe=07c70033f5) | Jul 25, 2022 |
| Alienware     | M11xR3                      | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| Dell          | Inspiron 3505               | [5bec1168d0](https://linux-hardware.org/?probe=5bec1168d0) | Jul 22, 2022 |
| HP            | 240 G4                      | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| Unknown       | W1415A                      | [3a2f4f9848](https://linux-hardware.org/?probe=3a2f4f9848) | Jul 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [8bf06ee1c1](https://linux-hardware.org/?probe=8bf06ee1c1) | Jul 21, 2022 |
| Dell          | Latitude E7250              | [5fdb8cad05](https://linux-hardware.org/?probe=5fdb8cad05) | Jul 21, 2022 |
| GHIA          | Notebook                    | [2193ab1cd3](https://linux-hardware.org/?probe=2193ab1cd3) | Jul 20, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [5859932a73](https://linux-hardware.org/?probe=5859932a73) | Jul 20, 2022 |
| HP            | EliteBook 8570w             | [6b8bf59f68](https://linux-hardware.org/?probe=6b8bf59f68) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Dell          | Inspiron 3421               | [d4c15eb5fd](https://linux-hardware.org/?probe=d4c15eb5fd) | Jul 18, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [27f6399025](https://linux-hardware.org/?probe=27f6399025) | Jul 16, 2022 |
| Dell          | Precision M4600             | [96f8364d87](https://linux-hardware.org/?probe=96f8364d87) | Jul 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [1cf6844d33](https://linux-hardware.org/?probe=1cf6844d33) | Jul 14, 2022 |
| Toshiba       | Satellite L55-B             | [0e0ba8274b](https://linux-hardware.org/?probe=0e0ba8274b) | Jul 13, 2022 |
| Toshiba       | Satellite L55-B             | [a7bebd622f](https://linux-hardware.org/?probe=a7bebd622f) | Jul 13, 2022 |
| Dell          | Inspiron 7460               | [316285fb12](https://linux-hardware.org/?probe=316285fb12) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Dell          | Latitude E5530 non-vPro     | [0ab6a30f98](https://linux-hardware.org/?probe=0ab6a30f98) | Jul 12, 2022 |
| Sony          | VPCYB20AL                   | [c9645d6952](https://linux-hardware.org/?probe=c9645d6952) | Jul 10, 2022 |
| Lenovo        | IdeaPad Y430 2781           | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Dell          | Inspiron 3558               | [14cacca8ad](https://linux-hardware.org/?probe=14cacca8ad) | Jul 09, 2022 |
| MSI           | GF63 Thin 11UC              | [ecfb5f39c5](https://linux-hardware.org/?probe=ecfb5f39c5) | Jul 09, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [a64c483143](https://linux-hardware.org/?probe=a64c483143) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [39e56d90b1](https://linux-hardware.org/?probe=39e56d90b1) | Jul 07, 2022 |
| Acer          | Nitro AN515-51              | [0b57ab5b5b](https://linux-hardware.org/?probe=0b57ab5b5b) | Jul 07, 2022 |
| ASUSTek       | X555DG                      | [b7a2c97bf2](https://linux-hardware.org/?probe=b7a2c97bf2) | Jul 07, 2022 |
| Acer          | Aspire E3-112M              | [6de763aad6](https://linux-hardware.org/?probe=6de763aad6) | Jul 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7e53f712c5](https://linux-hardware.org/?probe=7e53f712c5) | Jul 06, 2022 |
| Acer          | Aspire F5-573               | [1ada0ad162](https://linux-hardware.org/?probe=1ada0ad162) | Jul 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a673b1557d](https://linux-hardware.org/?probe=a673b1557d) | Jul 05, 2022 |
| HP            | Pavilion dv4                | [d40a5bd13e](https://linux-hardware.org/?probe=d40a5bd13e) | Jul 04, 2022 |
| Lenovo        | G40-45 80E1                 | [bce4ceea50](https://linux-hardware.org/?probe=bce4ceea50) | Jul 03, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [a5ad48eeb5](https://linux-hardware.org/?probe=a5ad48eeb5) | Jul 03, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [c364b347a5](https://linux-hardware.org/?probe=c364b347a5) | Jul 02, 2022 |
| Dell          | Precision M4600             | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| HUAWEI        | NBM-WXX9                    | [6ed674f77e](https://linux-hardware.org/?probe=6ed674f77e) | Jul 01, 2022 |
| Acer          | Aspire E5-573               | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [e7f3ea5cf5](https://linux-hardware.org/?probe=e7f3ea5cf5) | Jun 30, 2022 |
| HP            | Compaq CQ45                 | [74948790d0](https://linux-hardware.org/?probe=74948790d0) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Dell          | Latitude E6400              | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| Dell          | Latitude 7420               | [3730ffb739](https://linux-hardware.org/?probe=3730ffb739) | Jun 27, 2022 |
| HP            | OMEN Notebook PC 15         | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Sony          | VPCF236FM                   | [b2af243689](https://linux-hardware.org/?probe=b2af243689) | Jun 25, 2022 |
| Google        | Kip                         | [d21adde488](https://linux-hardware.org/?probe=d21adde488) | Jun 24, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| Dell          | Latitude E6400              | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| Alienware     | 17 R4                       | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [68ca5e600d](https://linux-hardware.org/?probe=68ca5e600d) | Jun 18, 2022 |
| Apple         | MacBookAir6,1               | [665cfa446b](https://linux-hardware.org/?probe=665cfa446b) | Jun 18, 2022 |
| HP            | Laptop 15-bs0xx             | [aa89682b09](https://linux-hardware.org/?probe=aa89682b09) | Jun 18, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Lenovo        | ThinkPad T540p 20BE003NU... | [e05c2e42c2](https://linux-hardware.org/?probe=e05c2e42c2) | Jun 17, 2022 |
| Gateway       | NE513                       | [c33ad72253](https://linux-hardware.org/?probe=c33ad72253) | Jun 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e4d5856a72](https://linux-hardware.org/?probe=e4d5856a72) | Jun 16, 2022 |
| Lenovo        | IdeaPad Z480                | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| Dell          | Latitude E6410              | [6194911b41](https://linux-hardware.org/?probe=6194911b41) | Jun 15, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| Lenovo        | Y50-70 20378                | [6153f90073](https://linux-hardware.org/?probe=6153f90073) | Jun 13, 2022 |
| Apple         | MacBookPro14,1              | [537b26aaf0](https://linux-hardware.org/?probe=537b26aaf0) | Jun 12, 2022 |
| Dell          | Latitude E6410              | [005799b9bf](https://linux-hardware.org/?probe=005799b9bf) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [ca2c0e822c](https://linux-hardware.org/?probe=ca2c0e822c) | Jun 11, 2022 |
| Dell          | Studio XPS 1340             | [36f61b29b5](https://linux-hardware.org/?probe=36f61b29b5) | Jun 11, 2022 |
| HP            | Pavilion dv6                | [c8e7eea8fc](https://linux-hardware.org/?probe=c8e7eea8fc) | Jun 11, 2022 |
| Corporativ... | Neuron LT                   | [84ed262694](https://linux-hardware.org/?probe=84ed262694) | Jun 10, 2022 |
| Corporativ... | Neuron LT                   | [ad265d5197](https://linux-hardware.org/?probe=ad265d5197) | Jun 10, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [479a01b8d8](https://linux-hardware.org/?probe=479a01b8d8) | Jun 10, 2022 |
| ASUSTek       | K43E                        | [cd9e7dab5e](https://linux-hardware.org/?probe=cd9e7dab5e) | Jun 09, 2022 |
| Acer          | Aspire E5-573               | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 2767AL9       | [8084a9ed95](https://linux-hardware.org/?probe=8084a9ed95) | Jun 08, 2022 |
| Toshiba       | Satellite L55-B             | [38c0d1cebc](https://linux-hardware.org/?probe=38c0d1cebc) | Jun 07, 2022 |
| HP            | Laptop 15-dy0xxx            | [e2a9ba60e2](https://linux-hardware.org/?probe=e2a9ba60e2) | Jun 07, 2022 |
| HP            | Laptop 15-dy2xxx            | [ecc580e75f](https://linux-hardware.org/?probe=ecc580e75f) | Jun 06, 2022 |
| HP            | Laptop 15-dy2xxx            | [e737d522f2](https://linux-hardware.org/?probe=e737d522f2) | Jun 06, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [84d72b2b06](https://linux-hardware.org/?probe=84d72b2b06) | Jun 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [058bd1f6b9](https://linux-hardware.org/?probe=058bd1f6b9) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| EVOO          | EV-C-116-7                  | [1955955afc](https://linux-hardware.org/?probe=1955955afc) | Jun 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [978a80c358](https://linux-hardware.org/?probe=978a80c358) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a3e63f04e7](https://linux-hardware.org/?probe=a3e63f04e7) | May 31, 2022 |
| Dell          | G7 7588                     | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| Dell          | Inspiron 5547               | [066f6369b2](https://linux-hardware.org/?probe=066f6369b2) | May 31, 2022 |
| Lenovo        | IdeaPad S300 20197          | [fcb07ac9aa](https://linux-hardware.org/?probe=fcb07ac9aa) | May 31, 2022 |
| Lenovo        | IdeaPad Z480                | [b1cf8ca505](https://linux-hardware.org/?probe=b1cf8ca505) | May 30, 2022 |
| Lenovo        | G50-30 80G0                 | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [55dfdf01c6](https://linux-hardware.org/?probe=55dfdf01c6) | May 29, 2022 |
| HP            | Presario CQ62               | [fe3cac8868](https://linux-hardware.org/?probe=fe3cac8868) | May 27, 2022 |
| Dell          | Inspiron 5570               | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| Acer          | Swift SF113-31              | [2bdba73cfa](https://linux-hardware.org/?probe=2bdba73cfa) | May 26, 2022 |
| Acer          | Aspire E3-112M              | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ad9da27671](https://linux-hardware.org/?probe=ad9da27671) | May 26, 2022 |
| HP            | Pavilion g4                 | [0c943e458a](https://linux-hardware.org/?probe=0c943e458a) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| ASUSTek       | X402CA                      | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| HUAWEI        | HVY-WXX9                    | [93bb32d1b2](https://linux-hardware.org/?probe=93bb32d1b2) | May 21, 2022 |
| Acer          | Aspire 5332                 | [f48da95c17](https://linux-hardware.org/?probe=f48da95c17) | May 21, 2022 |
| System76      | Oryx Pro                    | [b68edfe15c](https://linux-hardware.org/?probe=b68edfe15c) | May 17, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [f0fef230c2](https://linux-hardware.org/?probe=f0fef230c2) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [2f0e46cc27](https://linux-hardware.org/?probe=2f0e46cc27) | May 15, 2022 |
| Lenovo        | S10-3                       | [b2eb29a65e](https://linux-hardware.org/?probe=b2eb29a65e) | May 14, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4316b121b1](https://linux-hardware.org/?probe=4316b121b1) | May 14, 2022 |
| Dell          | Studio 1558                 | [ccffb59f97](https://linux-hardware.org/?probe=ccffb59f97) | May 13, 2022 |
| Toshiba       | Satellite C55-C             | [2695dd828d](https://linux-hardware.org/?probe=2695dd828d) | May 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [2bd7babedc](https://linux-hardware.org/?probe=2bd7babedc) | May 13, 2022 |
| Toshiba       | TECRA Z50-A                 | [985d5869bf](https://linux-hardware.org/?probe=985d5869bf) | May 12, 2022 |
| Dell          | XPS 15 9550                 | [de90425a28](https://linux-hardware.org/?probe=de90425a28) | May 09, 2022 |
| Google        | Blooglet                    | [64b4f18c1c](https://linux-hardware.org/?probe=64b4f18c1c) | May 09, 2022 |
| Google        | Blooglet                    | [f3dc91bf66](https://linux-hardware.org/?probe=f3dc91bf66) | May 09, 2022 |
| HP            | Laptop 17z-ca300            | [c43f2b0e29](https://linux-hardware.org/?probe=c43f2b0e29) | May 08, 2022 |
| Acer          | Aspire ES1-531              | [a7927b8b27](https://linux-hardware.org/?probe=a7927b8b27) | May 08, 2022 |
| Acer          | Aspire F5-573               | [d6961632c4](https://linux-hardware.org/?probe=d6961632c4) | May 07, 2022 |
| HP            | Notebook                    | [04f5e602de](https://linux-hardware.org/?probe=04f5e602de) | May 07, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [46d0c349d6](https://linux-hardware.org/?probe=46d0c349d6) | May 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [38f5d37dcc](https://linux-hardware.org/?probe=38f5d37dcc) | May 07, 2022 |
| HP            | Pavilion 14                 | [2bd48eeb41](https://linux-hardware.org/?probe=2bd48eeb41) | May 06, 2022 |
| Apple         | MacBookAir6,2               | [d04d5e927d](https://linux-hardware.org/?probe=d04d5e927d) | May 05, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [4208da52ad](https://linux-hardware.org/?probe=4208da52ad) | May 04, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | [a3eb29c75d](https://linux-hardware.org/?probe=a3eb29c75d) | May 04, 2022 |
| Dell          | Latitude 7420               | [a0bd1ee0f4](https://linux-hardware.org/?probe=a0bd1ee0f4) | May 03, 2022 |
| Sony          | VPCF236FM                   | [ec0af02205](https://linux-hardware.org/?probe=ec0af02205) | May 02, 2022 |
| Acer          | Aspire V5-561               | [e9dfda82d4](https://linux-hardware.org/?probe=e9dfda82d4) | May 02, 2022 |
| Dell          | Latitude E5550              | [42a576bd39](https://linux-hardware.org/?probe=42a576bd39) | May 01, 2022 |
| HP            | Pavilion 13 x2 PC           | [fbb6d3b97e](https://linux-hardware.org/?probe=fbb6d3b97e) | May 01, 2022 |
| HP            | Pavilion 13 x2 PC           | [d594f3335c](https://linux-hardware.org/?probe=d594f3335c) | May 01, 2022 |
| ASUSTek       | X202E                       | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f5d70fb9d3](https://linux-hardware.org/?probe=f5d70fb9d3) | Apr 30, 2022 |
| Lenovo        | S10-3                       | [712c2dced9](https://linux-hardware.org/?probe=712c2dced9) | Apr 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [824ccc1317](https://linux-hardware.org/?probe=824ccc1317) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [35e8d13a74](https://linux-hardware.org/?probe=35e8d13a74) | Apr 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| Toshiba       | Satellite L735D             | [4bd23809e6](https://linux-hardware.org/?probe=4bd23809e6) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [d48006a0b2](https://linux-hardware.org/?probe=d48006a0b2) | Apr 26, 2022 |
| Toshiba       | Satellite C55-C             | [e9bc1aaf05](https://linux-hardware.org/?probe=e9bc1aaf05) | Apr 26, 2022 |
| Dell          | Inspiron 5577               | [0925d92173](https://linux-hardware.org/?probe=0925d92173) | Apr 25, 2022 |
| Lenovo        | ThinkPad E460 20ET000YLM    | [c82beac367](https://linux-hardware.org/?probe=c82beac367) | Apr 23, 2022 |
| HUAWEI        | HVY-WXX9                    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| ASUSTek       | K46CA                       | [e762eba391](https://linux-hardware.org/?probe=e762eba391) | Apr 23, 2022 |
| HP            | EliteBook 8570w             | [0a4b339d0f](https://linux-hardware.org/?probe=0a4b339d0f) | Apr 23, 2022 |
| Chuwi         | Unknown                     | [96105ecbb2](https://linux-hardware.org/?probe=96105ecbb2) | Apr 23, 2022 |
| Lenovo        | ThinkPad W530 2463A49       | [202b5d34a1](https://linux-hardware.org/?probe=202b5d34a1) | Apr 18, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [55186a3c2e](https://linux-hardware.org/?probe=55186a3c2e) | Apr 18, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | [726f69890c](https://linux-hardware.org/?probe=726f69890c) | Apr 17, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [382836d952](https://linux-hardware.org/?probe=382836d952) | Apr 16, 2022 |
| Acer          | Aspire R3-131T              | [776575ecdb](https://linux-hardware.org/?probe=776575ecdb) | Apr 16, 2022 |
| Lenovo        | G40-45 80E1                 | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Sony          | VPCEE23FX                   | [4c7634a096](https://linux-hardware.org/?probe=4c7634a096) | Apr 15, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [25c2200e11](https://linux-hardware.org/?probe=25c2200e11) | Apr 14, 2022 |
| HP            | Laptop 14-cm0xxx            | [d6463e4014](https://linux-hardware.org/?probe=d6463e4014) | Apr 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | [8888d86504](https://linux-hardware.org/?probe=8888d86504) | Apr 13, 2022 |
| Acer          | Nitro AN515-41              | [b938e715f4](https://linux-hardware.org/?probe=b938e715f4) | Apr 13, 2022 |
| HP            | ProBook 650 G1              | [5d153a1030](https://linux-hardware.org/?probe=5d153a1030) | Apr 12, 2022 |
| HP            | ZBook 15                    | [c8c2248854](https://linux-hardware.org/?probe=c8c2248854) | Apr 11, 2022 |
| Toshiba       | Satellite L735D             | [47f0119635](https://linux-hardware.org/?probe=47f0119635) | Apr 10, 2022 |
| HP            | EliteBook 8570w             | [9d7c1a88d6](https://linux-hardware.org/?probe=9d7c1a88d6) | Apr 10, 2022 |
| HP            | Laptop 15-da1xxx            | [8d9c212045](https://linux-hardware.org/?probe=8d9c212045) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Dell          | Inspiron 5570               | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| HP            | ZBook 15                    | [ee70932ef2](https://linux-hardware.org/?probe=ee70932ef2) | Apr 09, 2022 |
| HP            | Pavilion dv6                | [9d37acefa0](https://linux-hardware.org/?probe=9d37acefa0) | Apr 09, 2022 |
| Sony          | VPCF236FM                   | [ea109b146b](https://linux-hardware.org/?probe=ea109b146b) | Apr 08, 2022 |
| Toshiba       | NB505                       | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| Toshiba       | Satellite P775              | [3acd0b8861](https://linux-hardware.org/?probe=3acd0b8861) | Apr 08, 2022 |
| Dell          | Inspiron 5570               | [801e4fdab1](https://linux-hardware.org/?probe=801e4fdab1) | Apr 07, 2022 |
| Dell          | Latitude E5440              | [18a9d37c02](https://linux-hardware.org/?probe=18a9d37c02) | Apr 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | [e168714dee](https://linux-hardware.org/?probe=e168714dee) | Apr 06, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| HP            | 245 G7 Notebook PC          | [9d26a79ca6](https://linux-hardware.org/?probe=9d26a79ca6) | Apr 05, 2022 |
| HP            | 245 G7 Notebook PC          | [54db9ac27f](https://linux-hardware.org/?probe=54db9ac27f) | Apr 05, 2022 |
| HP            | Pavilion 14                 | [136105017c](https://linux-hardware.org/?probe=136105017c) | Apr 04, 2022 |
| HP            | Presario CQ56               | [7233c29381](https://linux-hardware.org/?probe=7233c29381) | Apr 03, 2022 |
| Toshiba       | Satellite S855D             | [45b97d03ed](https://linux-hardware.org/?probe=45b97d03ed) | Apr 03, 2022 |
| Apple         | MacBookPro9,2               | [f646cb03d2](https://linux-hardware.org/?probe=f646cb03d2) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [b87a95ae1a](https://linux-hardware.org/?probe=b87a95ae1a) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [fecf079b63](https://linux-hardware.org/?probe=fecf079b63) | Mar 31, 2022 |
| Dell          | Venue 8 Pro 5855            | [35a463a0fb](https://linux-hardware.org/?probe=35a463a0fb) | Mar 31, 2022 |
| HUAWEI        | HVY-WXX9                    | [5af7df2c2a](https://linux-hardware.org/?probe=5af7df2c2a) | Mar 30, 2022 |
| Acer          | Aspire one                  | [2b0b231b1a](https://linux-hardware.org/?probe=2b0b231b1a) | Mar 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [d346f2a1b1](https://linux-hardware.org/?probe=d346f2a1b1) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [67475db5e9](https://linux-hardware.org/?probe=67475db5e9) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [2c7227662f](https://linux-hardware.org/?probe=2c7227662f) | Mar 29, 2022 |
| Toshiba       | NB505                       | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Dell          | Latitude E6510              | [4feee8c983](https://linux-hardware.org/?probe=4feee8c983) | Mar 26, 2022 |
| HP            | Pavilion 11 x360 PC         | [975bcd1031](https://linux-hardware.org/?probe=975bcd1031) | Mar 25, 2022 |
| HP            | Laptop 15-bw0xx             | [eb140d5b4d](https://linux-hardware.org/?probe=eb140d5b4d) | Mar 25, 2022 |
| Sony          | SVT13125CLS                 | [5332da89c8](https://linux-hardware.org/?probe=5332da89c8) | Mar 25, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [4b955479cc](https://linux-hardware.org/?probe=4b955479cc) | Mar 24, 2022 |
| System76      | Gazelle                     | [5a83198dd6](https://linux-hardware.org/?probe=5a83198dd6) | Mar 24, 2022 |
| Acer          | Nitro AN515-54              | [4bb7650e38](https://linux-hardware.org/?probe=4bb7650e38) | Mar 23, 2022 |
| Lenovo        | Unknown                     | [661ddbd0df](https://linux-hardware.org/?probe=661ddbd0df) | Mar 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [e1f3c645b5](https://linux-hardware.org/?probe=e1f3c645b5) | Mar 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1PD0M    | [ed01dc4465](https://linux-hardware.org/?probe=ed01dc4465) | Mar 17, 2022 |
| HP            | EliteBook 8460p             | [6c0caa0de4](https://linux-hardware.org/?probe=6c0caa0de4) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1PD0M    | [dbed1562e8](https://linux-hardware.org/?probe=dbed1562e8) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| HP            | Pavilion 15                 | [29ac5f13cd](https://linux-hardware.org/?probe=29ac5f13cd) | Mar 16, 2022 |
| Apple         | MacBookPro15,2              | [a77a1ff925](https://linux-hardware.org/?probe=a77a1ff925) | Mar 16, 2022 |
| Dell          | Latitude E6220              | [0dbd85da47](https://linux-hardware.org/?probe=0dbd85da47) | Mar 13, 2022 |
| Dell          | G5 5505                     | [286d140bd5](https://linux-hardware.org/?probe=286d140bd5) | Mar 10, 2022 |
| HP            | ProBook 650 G1              | [046572a251](https://linux-hardware.org/?probe=046572a251) | Mar 09, 2022 |
| Dell          | XPS 15 9570                 | [dd0ebc18ce](https://linux-hardware.org/?probe=dd0ebc18ce) | Mar 07, 2022 |
| Acer          | Aspire E5-575               | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Chuwi         | GemiBook                    | [60146fd918](https://linux-hardware.org/?probe=60146fd918) | Mar 07, 2022 |
| Acer          | Aspire VN7-572              | [952fd83515](https://linux-hardware.org/?probe=952fd83515) | Mar 06, 2022 |
| Unknown       | KN12A                       | [3ba6165509](https://linux-hardware.org/?probe=3ba6165509) | Mar 05, 2022 |
| Panasonic     | CF-30KTPA9NP                | [fffe3abd97](https://linux-hardware.org/?probe=fffe3abd97) | Mar 05, 2022 |
| Lenovo        | G40-70 20369                | [fd797ac0c1](https://linux-hardware.org/?probe=fd797ac0c1) | Mar 03, 2022 |
| Chuwi         | GemiBook                    | [af28b0f0d8](https://linux-hardware.org/?probe=af28b0f0d8) | Mar 02, 2022 |
| Timi          | TM1612                      | [dc1c26b3a9](https://linux-hardware.org/?probe=dc1c26b3a9) | Mar 01, 2022 |
| Sony          | VGN-Z690N                   | [d3465abe44](https://linux-hardware.org/?probe=d3465abe44) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | [0a0e3feff6](https://linux-hardware.org/?probe=0a0e3feff6) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | [2b791434ce](https://linux-hardware.org/?probe=2b791434ce) | Feb 28, 2022 |
| Toshiba       | Satellite C655D             | [10f38d005e](https://linux-hardware.org/?probe=10f38d005e) | Feb 28, 2022 |
| ASUSTek       | X401A                       | [e97f529634](https://linux-hardware.org/?probe=e97f529634) | Feb 28, 2022 |
| Lenovo        | Z40-70 20366                | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Apple         | MacBookAir5,2               | [fb0403c8b8](https://linux-hardware.org/?probe=fb0403c8b8) | Feb 26, 2022 |
| Timi          | RedmiBook 13 R              | [a74bea030c](https://linux-hardware.org/?probe=a74bea030c) | Feb 25, 2022 |
| Timi          | RedmiBook 13 R              | [318a4d1d35](https://linux-hardware.org/?probe=318a4d1d35) | Feb 25, 2022 |
| MSI           | GL75 Leopard 10SDK          | [6a14728490](https://linux-hardware.org/?probe=6a14728490) | Feb 24, 2022 |
| Apple         | MacBookPro15,2              | [aebbda3f2d](https://linux-hardware.org/?probe=aebbda3f2d) | Feb 23, 2022 |
| Apple         | MacBookPro15,2              | [302836f9d3](https://linux-hardware.org/?probe=302836f9d3) | Feb 23, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [fe042017e6](https://linux-hardware.org/?probe=fe042017e6) | Feb 23, 2022 |
| ASUSTek       | X45U                        | [41f11e9487](https://linux-hardware.org/?probe=41f11e9487) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [229a11c203](https://linux-hardware.org/?probe=229a11c203) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [2a934577d6](https://linux-hardware.org/?probe=2a934577d6) | Feb 20, 2022 |
| Acer          | Aspire A315-56              | [26d9aa49e7](https://linux-hardware.org/?probe=26d9aa49e7) | Feb 19, 2022 |
| HP            | ProBook 4530s               | [26a60b46d2](https://linux-hardware.org/?probe=26a60b46d2) | Feb 18, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [91540e8aa6](https://linux-hardware.org/?probe=91540e8aa6) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3e5d5d5afe](https://linux-hardware.org/?probe=3e5d5d5afe) | Feb 18, 2022 |
| Hyundai Te... | Thinnote 13                 | [16d5bcb194](https://linux-hardware.org/?probe=16d5bcb194) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [eb1d4cf9d8](https://linux-hardware.org/?probe=eb1d4cf9d8) | Feb 17, 2022 |
| Acer          | Aspire A315-56              | [38fe80e2a8](https://linux-hardware.org/?probe=38fe80e2a8) | Feb 17, 2022 |
| Acer          | Aspire A315-56              | [cf4c296719](https://linux-hardware.org/?probe=cf4c296719) | Feb 17, 2022 |
| Apple         | MacBookPro14,1              | [f7c7bd4baf](https://linux-hardware.org/?probe=f7c7bd4baf) | Feb 17, 2022 |
| Acer          | TravelMate P214-53          | [4d1c34fef7](https://linux-hardware.org/?probe=4d1c34fef7) | Feb 17, 2022 |
| Lenovo        | G40-45 80E1                 | [f181193143](https://linux-hardware.org/?probe=f181193143) | Feb 16, 2022 |
| Lenovo        | G40-45 80E1                 | [88c9f0db96](https://linux-hardware.org/?probe=88c9f0db96) | Feb 16, 2022 |
| Dell          | Latitude E7440              | [1efc982c71](https://linux-hardware.org/?probe=1efc982c71) | Feb 16, 2022 |
| HP            | Laptop 15-da0xxx            | [84171dc3cd](https://linux-hardware.org/?probe=84171dc3cd) | Feb 16, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [34fff5bf39](https://linux-hardware.org/?probe=34fff5bf39) | Feb 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [85d4a8278e](https://linux-hardware.org/?probe=85d4a8278e) | Feb 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [a533f0d469](https://linux-hardware.org/?probe=a533f0d469) | Feb 14, 2022 |
| HP            | 655                         | [b0189b16b1](https://linux-hardware.org/?probe=b0189b16b1) | Feb 14, 2022 |
| HP            | Laptop 15-da2xxx            | [51dfcad0d4](https://linux-hardware.org/?probe=51dfcad0d4) | Feb 14, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [429d06ed33](https://linux-hardware.org/?probe=429d06ed33) | Feb 13, 2022 |
| HP            | 245 G1                      | [30c3eb937a](https://linux-hardware.org/?probe=30c3eb937a) | Feb 13, 2022 |
| Dell          | Inspiron 5537               | [3ef228db80](https://linux-hardware.org/?probe=3ef228db80) | Feb 11, 2022 |
| Dell          | Latitude 7420               | [2547d7836e](https://linux-hardware.org/?probe=2547d7836e) | Feb 11, 2022 |
| HP            | Laptop 15-dw0xxx            | [16157beba6](https://linux-hardware.org/?probe=16157beba6) | Feb 11, 2022 |
| Sony          | VGN-Z575FN                  | [4998f7ae6d](https://linux-hardware.org/?probe=4998f7ae6d) | Feb 11, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [cc5c3cd3d0](https://linux-hardware.org/?probe=cc5c3cd3d0) | Feb 11, 2022 |
| Lenovo        | ThinkPad T430 2349L38       | [85d1c3705e](https://linux-hardware.org/?probe=85d1c3705e) | Feb 09, 2022 |
| Dell          | Inspiron 5567               | [eec17e2cdc](https://linux-hardware.org/?probe=eec17e2cdc) | Feb 09, 2022 |
| HP            | ProBook 645 G1              | [98bdb87a7c](https://linux-hardware.org/?probe=98bdb87a7c) | Feb 08, 2022 |
| Lanix         | A V16                       | [2cbb463004](https://linux-hardware.org/?probe=2cbb463004) | Feb 08, 2022 |
| Lenovo        | ThinkPad Edge 13IAL# 019... | [78011da841](https://linux-hardware.org/?probe=78011da841) | Feb 07, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | [7196de2b08](https://linux-hardware.org/?probe=7196de2b08) | Feb 06, 2022 |
| HP            | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Sony          | VPCF236FM                   | [784b1b0c3b](https://linux-hardware.org/?probe=784b1b0c3b) | Feb 06, 2022 |
| Lanix         | NEURON_FLEX                 | [566f9282eb](https://linux-hardware.org/?probe=566f9282eb) | Feb 05, 2022 |
| HP            | Laptop 17-cn0xxx            | [cfdee7d88e](https://linux-hardware.org/?probe=cfdee7d88e) | Feb 05, 2022 |
| Lanix         | NEURON_FLEX                 | [90d39053df](https://linux-hardware.org/?probe=90d39053df) | Feb 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5a11c55e55](https://linux-hardware.org/?probe=5a11c55e55) | Feb 05, 2022 |
| HP            | 240 G4                      | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| Samsung       | 305V4A/305V5A               | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| Dell          | Latitude 3420               | [98d388a60d](https://linux-hardware.org/?probe=98d388a60d) | Feb 03, 2022 |
| Lenovo        | V14-ARE 82DQ                | [b3cfaa23eb](https://linux-hardware.org/?probe=b3cfaa23eb) | Feb 01, 2022 |
| Lenovo        | Rev B 20YM                  | [83c63da100](https://linux-hardware.org/?probe=83c63da100) | Feb 01, 2022 |
| Dell          | Latitude 3330               | [c3b39f74b4](https://linux-hardware.org/?probe=c3b39f74b4) | Jan 31, 2022 |
| Dell          | Latitude 3330               | [61a24473d4](https://linux-hardware.org/?probe=61a24473d4) | Jan 31, 2022 |
| Corporativ... | MB40II5                     | [ba6bc223c3](https://linux-hardware.org/?probe=ba6bc223c3) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [2248ba47d2](https://linux-hardware.org/?probe=2248ba47d2) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [74eb47cb2f](https://linux-hardware.org/?probe=74eb47cb2f) | Jan 30, 2022 |
| Corporativ... | MB40II5                     | [3c62692a0f](https://linux-hardware.org/?probe=3c62692a0f) | Jan 30, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e06431af49](https://linux-hardware.org/?probe=e06431af49) | Jan 29, 2022 |
| HP            | Laptop 14-cm0xxx            | [36fa473b25](https://linux-hardware.org/?probe=36fa473b25) | Jan 29, 2022 |
| Apple         | MacBookAir6,2               | [f25c578f5a](https://linux-hardware.org/?probe=f25c578f5a) | Jan 28, 2022 |
| Timi          | TM1701                      | [c4387537b3](https://linux-hardware.org/?probe=c4387537b3) | Jan 28, 2022 |
| Dell          | Latitude E6410              | [8f9cad1934](https://linux-hardware.org/?probe=8f9cad1934) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWA15L0... | [6e1153bb21](https://linux-hardware.org/?probe=6e1153bb21) | Jan 28, 2022 |
| Timi          | TM1701                      | [90877c2a8a](https://linux-hardware.org/?probe=90877c2a8a) | Jan 28, 2022 |
| HP            | EliteBook 8460p             | [49ab3da4e2](https://linux-hardware.org/?probe=49ab3da4e2) | Jan 28, 2022 |
| System76      | Gazelle                     | [4066e8f06a](https://linux-hardware.org/?probe=4066e8f06a) | Jan 24, 2022 |
| ASUSTek       | B551LG                      | [4df03afb9f](https://linux-hardware.org/?probe=4df03afb9f) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f9deb1d329](https://linux-hardware.org/?probe=f9deb1d329) | Jan 20, 2022 |
| Alienware     | x15 R1                      | [5f9dce49b3](https://linux-hardware.org/?probe=5f9dce49b3) | Jan 20, 2022 |
| Acer          | Predator G9-591             | [187b246949](https://linux-hardware.org/?probe=187b246949) | Jan 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [efdc064669](https://linux-hardware.org/?probe=efdc064669) | Jan 19, 2022 |
| Dell          | Latitude E6400              | [05d5d5de96](https://linux-hardware.org/?probe=05d5d5de96) | Jan 17, 2022 |
| Google        | Ultima                      | [d942b9081b](https://linux-hardware.org/?probe=d942b9081b) | Jan 16, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | [750744f996](https://linux-hardware.org/?probe=750744f996) | Jan 16, 2022 |
| Dell          | XPS 15 9570                 | [eb68d3d4dd](https://linux-hardware.org/?probe=eb68d3d4dd) | Jan 15, 2022 |
| Dell          | Inspiron 1525               | [286a7e58fd](https://linux-hardware.org/?probe=286a7e58fd) | Jan 14, 2022 |
| Dell          | Inspiron 1525               | [981a9aff50](https://linux-hardware.org/?probe=981a9aff50) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2d83a27067](https://linux-hardware.org/?probe=2d83a27067) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [ee8a872afd](https://linux-hardware.org/?probe=ee8a872afd) | Jan 13, 2022 |
| Dell          | Inspiron 3505               | [85c2838614](https://linux-hardware.org/?probe=85c2838614) | Jan 11, 2022 |
| Acer          | Aspire F5-573               | [2bf3f44e95](https://linux-hardware.org/?probe=2bf3f44e95) | Jan 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [99a245965c](https://linux-hardware.org/?probe=99a245965c) | Jan 09, 2022 |
| HUAWEI        | MACHD-WXX9                  | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Apple         | MacBook3,1                  | [b384dcb200](https://linux-hardware.org/?probe=b384dcb200) | Jan 06, 2022 |
| Dell          | Inspiron M5030              | [1715a3e584](https://linux-hardware.org/?probe=1715a3e584) | Jan 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [1660421dd9](https://linux-hardware.org/?probe=1660421dd9) | Jan 05, 2022 |
| MSI           | Bravo 15 A4DDR              | [d9aa580e5f](https://linux-hardware.org/?probe=d9aa580e5f) | Jan 05, 2022 |
| HP            | Compaq Mini CQ10-400        | [643f4e101f](https://linux-hardware.org/?probe=643f4e101f) | Jan 05, 2022 |
| HP            | Compaq Mini CQ10-400        | [ca3df238bc](https://linux-hardware.org/?probe=ca3df238bc) | Jan 05, 2022 |
| HP            | Pavilion 14                 | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| Acer          | Aspire E3-112M              | [466004173b](https://linux-hardware.org/?probe=466004173b) | Jan 04, 2022 |
| Lenovo        | ThinkPad W530 24382HU       | [5a4cc794e4](https://linux-hardware.org/?probe=5a4cc794e4) | Jan 02, 2022 |
| Lanix         | NeuronALV5                  | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| ASUSTek       | G75VW                       | [ffda51867b](https://linux-hardware.org/?probe=ffda51867b) | Jan 01, 2022 |
| eMachines     | E525                        | [192bbb8b30](https://linux-hardware.org/?probe=192bbb8b30) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Alienware     | 17 R3                       | [d5f4157f56](https://linux-hardware.org/?probe=d5f4157f56) | Dec 30, 2021 |
| Alienware     | 17 R3                       | [6c4813d3fd](https://linux-hardware.org/?probe=6c4813d3fd) | Dec 30, 2021 |
| Sony          | SVF14215CLW                 | [de9115a89c](https://linux-hardware.org/?probe=de9115a89c) | Dec 30, 2021 |
| Sony          | SVF14215CLW                 | [bf4fd6e13c](https://linux-hardware.org/?probe=bf4fd6e13c) | Dec 30, 2021 |
| HP            | ZBook 15u G3                | [e220b55c78](https://linux-hardware.org/?probe=e220b55c78) | Dec 30, 2021 |
| ASUSTek       | K43E                        | [38e1c3f86f](https://linux-hardware.org/?probe=38e1c3f86f) | Dec 30, 2021 |
| HUAWEI        | WRTD-WXX9                   | [0184868fb6](https://linux-hardware.org/?probe=0184868fb6) | Dec 29, 2021 |
| HP            | EliteBook 8460p             | [e9cf5c0353](https://linux-hardware.org/?probe=e9cf5c0353) | Dec 29, 2021 |
| Sony          | VPCEA35FL                   | [6c2b68633d](https://linux-hardware.org/?probe=6c2b68633d) | Dec 27, 2021 |
| HP            | ZBook 15u G3                | [f770dacb13](https://linux-hardware.org/?probe=f770dacb13) | Dec 25, 2021 |
| Acer          | Aspire 4752                 | [bb08100c63](https://linux-hardware.org/?probe=bb08100c63) | Dec 24, 2021 |
| MSI           | GF65 Thin 9SEXR             | [2be4e41c8e](https://linux-hardware.org/?probe=2be4e41c8e) | Dec 22, 2021 |
| Samsung       | RC410/RC510/RC710           | [123bdbfa71](https://linux-hardware.org/?probe=123bdbfa71) | Dec 22, 2021 |
| HP            | Pavilion dv4                | [7152c2fcd9](https://linux-hardware.org/?probe=7152c2fcd9) | Dec 22, 2021 |
| Apple         | MacBookPro14,1              | [e82554da93](https://linux-hardware.org/?probe=e82554da93) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [022cabd3f2](https://linux-hardware.org/?probe=022cabd3f2) | Dec 21, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | [d14536043e](https://linux-hardware.org/?probe=d14536043e) | Dec 20, 2021 |
| HUAWEI        | MACH-WX9                    | [033e872459](https://linux-hardware.org/?probe=033e872459) | Dec 19, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [ffd979b53f](https://linux-hardware.org/?probe=ffd979b53f) | Dec 19, 2021 |
| HP            | 14                          | [921783a9be](https://linux-hardware.org/?probe=921783a9be) | Dec 17, 2021 |
| ASUSTek       | X541NA                      | [70801591a7](https://linux-hardware.org/?probe=70801591a7) | Dec 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [66c985876e](https://linux-hardware.org/?probe=66c985876e) | Dec 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [ca0c96e24b](https://linux-hardware.org/?probe=ca0c96e24b) | Dec 15, 2021 |
| ASUSTek       | N53SV                       | [c17076e55c](https://linux-hardware.org/?probe=c17076e55c) | Dec 15, 2021 |
| Toshiba       | TECRA Z50-A                 | [0119ac4373](https://linux-hardware.org/?probe=0119ac4373) | Dec 15, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | [191acd1645](https://linux-hardware.org/?probe=191acd1645) | Dec 14, 2021 |
| Acer          | Aspire 4352                 | [f87ff266d6](https://linux-hardware.org/?probe=f87ff266d6) | Dec 13, 2021 |
| Acer          | Aspire 4352                 | [38f2bc6cc7](https://linux-hardware.org/?probe=38f2bc6cc7) | Dec 13, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [2e8509fb8b](https://linux-hardware.org/?probe=2e8509fb8b) | Dec 12, 2021 |
| Dell          | Inspiron 5570               | [1bed203660](https://linux-hardware.org/?probe=1bed203660) | Dec 12, 2021 |
| Timi          | TM1612                      | [1179aed154](https://linux-hardware.org/?probe=1179aed154) | Dec 12, 2021 |
| Dell          | Latitude E5400              | [3ce40a821b](https://linux-hardware.org/?probe=3ce40a821b) | Dec 09, 2021 |
| Gateway       | NE511                       | [ca37375600](https://linux-hardware.org/?probe=ca37375600) | Dec 09, 2021 |
| Lenovo        | ThinkPad E550 20DF002YUS    | [1533118145](https://linux-hardware.org/?probe=1533118145) | Dec 09, 2021 |
| HONOR         | NBR-WAX9                    | [e4edda2131](https://linux-hardware.org/?probe=e4edda2131) | Dec 08, 2021 |
| Lenovo        | ThinkPad W520 4284D47       | [a48239fba8](https://linux-hardware.org/?probe=a48239fba8) | Dec 08, 2021 |
| HUAWEI        | HVY-WXX9                    | [89330570db](https://linux-hardware.org/?probe=89330570db) | Dec 07, 2021 |
| HUAWEI        | HVY-WXX9                    | [7ff7601d59](https://linux-hardware.org/?probe=7ff7601d59) | Dec 07, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | [3f2487b1a6](https://linux-hardware.org/?probe=3f2487b1a6) | Dec 07, 2021 |
| Dell          | Vostro 3405                 | [b2dc2ac6b8](https://linux-hardware.org/?probe=b2dc2ac6b8) | Dec 05, 2021 |
| Lenovo        | G50-45 80E3                 | [cf43f05660](https://linux-hardware.org/?probe=cf43f05660) | Dec 03, 2021 |
| HP            | Laptop 15-db0xxx            | [4993feea8f](https://linux-hardware.org/?probe=4993feea8f) | Dec 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4855fe75cb](https://linux-hardware.org/?probe=4855fe75cb) | Dec 01, 2021 |
| HP            | Pavilion dv5                | [71ea9a6485](https://linux-hardware.org/?probe=71ea9a6485) | Nov 30, 2021 |
| HUAWEI        | HVY-WXX9                    | [c6289480ca](https://linux-hardware.org/?probe=c6289480ca) | Nov 27, 2021 |
| HUAWEI        | HVY-WXX9                    | [7569ef6338](https://linux-hardware.org/?probe=7569ef6338) | Nov 26, 2021 |
| Dell          | Latitude 3520               | [dfb19a422e](https://linux-hardware.org/?probe=dfb19a422e) | Nov 25, 2021 |
| Dell          | Latitude 3520               | [a0271563a5](https://linux-hardware.org/?probe=a0271563a5) | Nov 25, 2021 |
| Dell          | Inspiron 3505               | [9d28cad38c](https://linux-hardware.org/?probe=9d28cad38c) | Nov 24, 2021 |
| Alienware     | m15 R6                      | [7a71325757](https://linux-hardware.org/?probe=7a71325757) | Nov 24, 2021 |
| HP            | Laptop 15-da2xxx            | [eade5e3428](https://linux-hardware.org/?probe=eade5e3428) | Nov 24, 2021 |
| HP            | EliteBook 8460p             | [8278dcbd86](https://linux-hardware.org/?probe=8278dcbd86) | Nov 23, 2021 |
| MSI           | Prestige 14Evo A11M         | [ecc3ddf24a](https://linux-hardware.org/?probe=ecc3ddf24a) | Nov 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [af11f87974](https://linux-hardware.org/?probe=af11f87974) | Nov 22, 2021 |
| HP            | Laptop 14-cm0xxx            | [55e4412774](https://linux-hardware.org/?probe=55e4412774) | Nov 20, 2021 |
| Lenovo        | G475 20080                  | [98bc985284](https://linux-hardware.org/?probe=98bc985284) | Nov 18, 2021 |
| Dell          | System XPS L502X            | [8d247d71f2](https://linux-hardware.org/?probe=8d247d71f2) | Nov 17, 2021 |
| HP            | ENVY m7 Notebook            | [4b101cc132](https://linux-hardware.org/?probe=4b101cc132) | Nov 17, 2021 |
| Sony          | VPCF236FM                   | [70cffc5595](https://linux-hardware.org/?probe=70cffc5595) | Nov 16, 2021 |
| Dell          | Latitude E6400              | [e86a11de03](https://linux-hardware.org/?probe=e86a11de03) | Nov 15, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [5df470b888](https://linux-hardware.org/?probe=5df470b888) | Nov 15, 2021 |
| HP            | Pavilion g4                 | [e82daa0aba](https://linux-hardware.org/?probe=e82daa0aba) | Nov 13, 2021 |
| HP            | Pavilion g4                 | [ec71ab6f0c](https://linux-hardware.org/?probe=ec71ab6f0c) | Nov 12, 2021 |
| Dell          | Inspiron 1501               | [94ca9e7f47](https://linux-hardware.org/?probe=94ca9e7f47) | Nov 12, 2021 |
| Sony          | SVF14211CLB                 | [7c0dacdd54](https://linux-hardware.org/?probe=7c0dacdd54) | Nov 10, 2021 |
| Sony          | SVF14211CLB                 | [fdfd650fcc](https://linux-hardware.org/?probe=fdfd650fcc) | Nov 10, 2021 |
| HP            | ProBook 645 G2              | [beada5c26b](https://linux-hardware.org/?probe=beada5c26b) | Nov 09, 2021 |
| HP            | ProBook 645 G2              | [64b38adff8](https://linux-hardware.org/?probe=64b38adff8) | Nov 09, 2021 |
| HP            | Laptop 15-dy1xxx            | [e019dfb216](https://linux-hardware.org/?probe=e019dfb216) | Nov 09, 2021 |
| Dell          | XPS 15 9570                 | [a990ce7acd](https://linux-hardware.org/?probe=a990ce7acd) | Nov 08, 2021 |
| Sony          | VPCF236FM                   | [dda9f712f8](https://linux-hardware.org/?probe=dda9f712f8) | Nov 07, 2021 |
| Unknown       | Unknown                     | [38d3058206](https://linux-hardware.org/?probe=38d3058206) | Nov 05, 2021 |
| Unknown       | Unknown                     | [c78a5c81b2](https://linux-hardware.org/?probe=c78a5c81b2) | Nov 05, 2021 |
| Sony          | VPCEG23EL                   | [cc967c03fb](https://linux-hardware.org/?probe=cc967c03fb) | Nov 05, 2021 |
| ASUSTek       | T100TA                      | [7ac20ab25f](https://linux-hardware.org/?probe=7ac20ab25f) | Nov 03, 2021 |
| ASUSTek       | T100TA                      | [fa6b87b50d](https://linux-hardware.org/?probe=fa6b87b50d) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [d7c67d8ce7](https://linux-hardware.org/?probe=d7c67d8ce7) | Nov 02, 2021 |
| System76      | Gazelle                     | [09a256c5ae](https://linux-hardware.org/?probe=09a256c5ae) | Nov 02, 2021 |
| System76      | Gazelle                     | [09da0264ca](https://linux-hardware.org/?probe=09da0264ca) | Nov 01, 2021 |
| Gateway       | NV42                        | [8f46bc202f](https://linux-hardware.org/?probe=8f46bc202f) | Nov 01, 2021 |
| Toshiba       | Satellite P105              | [1b17b5c927](https://linux-hardware.org/?probe=1b17b5c927) | Oct 31, 2021 |
| Toshiba       | Satellite P105              | [8f6268031e](https://linux-hardware.org/?probe=8f6268031e) | Oct 31, 2021 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [2fca11cf26](https://linux-hardware.org/?probe=2fca11cf26) | Oct 31, 2021 |
| Dell          | Inspiron 3537               | [0812a6b105](https://linux-hardware.org/?probe=0812a6b105) | Oct 29, 2021 |
| Dell          | Inspiron 3537               | [0e2d73ad29](https://linux-hardware.org/?probe=0e2d73ad29) | Oct 29, 2021 |
| HP            | Laptop 17z-ca300            | [0071faabac](https://linux-hardware.org/?probe=0071faabac) | Oct 29, 2021 |
| HP            | Notebook                    | [0ba26ccc72](https://linux-hardware.org/?probe=0ba26ccc72) | Oct 28, 2021 |
| Dell          | Studio 1535                 | [69dc8fefa7](https://linux-hardware.org/?probe=69dc8fefa7) | Oct 27, 2021 |
| Dell          | Studio 1535                 | [3779b20704](https://linux-hardware.org/?probe=3779b20704) | Oct 27, 2021 |
| HP            | ENVY m7 Notebook            | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| HP            | Laptop 15-db0xxx            | [57be86b920](https://linux-hardware.org/?probe=57be86b920) | Oct 24, 2021 |
| Dell          | Inspiron 1545               | [e8e9a85406](https://linux-hardware.org/?probe=e8e9a85406) | Oct 23, 2021 |
| HP            | 240 G4 Notebook PC          | [b4cd0bde35](https://linux-hardware.org/?probe=b4cd0bde35) | Oct 23, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [20123f6b2f](https://linux-hardware.org/?probe=20123f6b2f) | Oct 23, 2021 |
| Dell          | Inspiron 1545               | [172b30ebe0](https://linux-hardware.org/?probe=172b30ebe0) | Oct 23, 2021 |
| Dell          | Latitude 5400               | [6a14ed2d5e](https://linux-hardware.org/?probe=6a14ed2d5e) | Oct 21, 2021 |
| HP            | Pavilion dv5                | [74cee5b7a8](https://linux-hardware.org/?probe=74cee5b7a8) | Oct 20, 2021 |
| Acer          | Aspire V5-122P              | [14086a6760](https://linux-hardware.org/?probe=14086a6760) | Oct 19, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [90aa462368](https://linux-hardware.org/?probe=90aa462368) | Oct 18, 2021 |
| Acer          | Aspire E5-523               | [fb8d7a6a25](https://linux-hardware.org/?probe=fb8d7a6a25) | Oct 18, 2021 |
| HP            | Compaq Presario CQ50        | [bb34275819](https://linux-hardware.org/?probe=bb34275819) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [b4c6139d09](https://linux-hardware.org/?probe=b4c6139d09) | Oct 17, 2021 |
| Sony          | SVE14A15FLB                 | [22a4b460cc](https://linux-hardware.org/?probe=22a4b460cc) | Oct 14, 2021 |
| Acer          | Aspire A514-53              | [ef16468238](https://linux-hardware.org/?probe=ef16468238) | Oct 13, 2021 |
| Sony          | SVE14A15FLB                 | [51170d9250](https://linux-hardware.org/?probe=51170d9250) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Apple         | MacBookPro8,1               | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [bdc66de1e6](https://linux-hardware.org/?probe=bdc66de1e6) | Oct 11, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [90dd918da6](https://linux-hardware.org/?probe=90dd918da6) | Oct 11, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [0562199997](https://linux-hardware.org/?probe=0562199997) | Oct 11, 2021 |
| HP            | EliteBook 820 G2            | [96da43b986](https://linux-hardware.org/?probe=96da43b986) | Oct 11, 2021 |
| Toshiba       | Satellite A215              | [06c3b56836](https://linux-hardware.org/?probe=06c3b56836) | Oct 11, 2021 |
| ASUSTek       | N61Jq                       | [2307cb57c4](https://linux-hardware.org/?probe=2307cb57c4) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Mexico/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 165       | 10.93%  |
| Ubuntu 18.04       | 114       | 7.55%   |
| Ubuntu 22.04       | 74        | 4.9%    |
| OpenMandriva 4.3   | 47        | 3.11%   |
| Debian 11          | 44        | 2.92%   |
| OpenMandriva 4.2   | 43        | 2.85%   |
| Zorin 16           | 38        | 2.52%   |
| Manjaro            | 37        | 2.45%   |
| KDE neon 20.04     | 36        | 2.39%   |
| Fedora 36          | 31        | 2.05%   |
| Linux Mint 20.3    | 27        | 1.79%   |
| Pop!_OS 22.04      | 23        | 1.52%   |
| Pop!_OS 20.04      | 23        | 1.52%   |
| Arch               | 21        | 1.39%   |
| Fedora 37          | 20        | 1.33%   |
| Zorin 15           | 19        | 1.26%   |
| Linux Mint 20      | 19        | 1.26%   |
| Ubuntu 19.10       | 18        | 1.19%   |
| Ubuntu 19.04       | 18        | 1.19%   |
| Debian 10          | 18        | 1.19%   |
| Linux Mint 19.3    | 17        | 1.13%   |
| Ubuntu 21.10       | 16        | 1.06%   |
| Pop!_OS 21.04      | 15        | 0.99%   |
| Kubuntu 20.04      | 15        | 0.99%   |
| Fedora 34          | 15        | 0.99%   |
| Xubuntu 18.04      | 14        | 0.93%   |
| Ubuntu 22.10       | 14        | 0.93%   |
| Ubuntu 20.10       | 14        | 0.93%   |
| Linux Mint 21.1    | 14        | 0.93%   |
| Linux Mint 21      | 14        | 0.93%   |
| Fedora 38          | 14        | 0.93%   |
| Fedora 35          | 14        | 0.93%   |
| OpenMandriva 23.03 | 13        | 0.86%   |
| Linux Mint 20.1    | 13        | 0.86%   |
| Elementary 6.1     | 13        | 0.86%   |
| Arch Rolling       | 13        | 0.86%   |
| OpenMandriva 23.01 | 12        | 0.8%    |
| KDE neon 22.04     | 12        | 0.8%    |
| Fedora 32          | 12        | 0.8%    |
| Xubuntu 20.04      | 10        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 447       | 30.81%  |
| Fedora        | 121       | 8.34%   |
| OpenMandriva  | 117       | 8.06%   |
| Linux Mint    | 114       | 7.86%   |
| Pop!_OS       | 73        | 5.03%   |
| Debian        | 70        | 4.82%   |
| Manjaro       | 64        | 4.41%   |
| Zorin         | 60        | 4.14%   |
| KDE neon      | 51        | 3.51%   |
| Kubuntu       | 33        | 2.27%   |
| Arch          | 33        | 2.27%   |
| Xubuntu       | 31        | 2.14%   |
| Elementary    | 25        | 1.72%   |
| Kali          | 21        | 1.45%   |
| ROSA          | 16        | 1.1%    |
| openSUSE      | 14        | 0.96%   |
| Endless       | 12        | 0.83%   |
| Clear Linux   | 12        | 0.83%   |
| Lubuntu       | 11        | 0.76%   |
| LMDE          | 11        | 0.76%   |
| ArcoLinux     | 9         | 0.62%   |
| Ubuntu Budgie | 8         | 0.55%   |
| Ubuntu Unity  | 7         | 0.48%   |
| Ubuntu MATE   | 7         | 0.48%   |
| SteamOS       | 7         | 0.48%   |
| Gentoo        | 7         | 0.48%   |
| EndeavourOS   | 7         | 0.48%   |
| Nobara        | 6         | 0.41%   |
| Garuda Linux  | 5         | 0.34%   |
| CentOS        | 5         | 0.34%   |
| Parrot        | 4         | 0.28%   |
| MX            | 4         | 0.28%   |
| Archcraft     | 4         | 0.28%   |
| RHEL          | 3         | 0.21%   |
| Peppermint    | 3         | 0.21%   |
| Reborn OS     | 2         | 0.14%   |
| Loc OS        | 2         | 0.14%   |
| LinuxFX       | 2         | 0.14%   |
| BlackPanther  | 2         | 0.14%   |
| Xero          | 1         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 47        | 2.85%   |
| 5.10.14-desktop-1omv4002 | 43        | 2.61%   |
| 5.4.0-42-generic         | 27        | 1.64%   |
| 5.4.0-58-generic         | 17        | 1.03%   |
| 5.15.0-56-generic        | 17        | 1.03%   |
| 5.4.0-52-generic         | 14        | 0.85%   |
| 5.3.0-46-generic         | 14        | 0.85%   |
| 5.4.0-91-generic         | 12        | 0.73%   |
| 5.4.0-48-generic         | 12        | 0.73%   |
| 5.19.0-38-generic        | 12        | 0.73%   |
| 5.15.0-58-generic        | 12        | 0.73%   |
| 5.15.0-48-generic        | 12        | 0.73%   |
| 5.11.0-27-generic        | 12        | 0.73%   |
| 5.0.0-37-generic         | 12        | 0.73%   |
| 6.1.1-desktop-1omv2290   | 11        | 0.67%   |
| 5.3.0-40-generic         | 11        | 0.67%   |
| 5.15.0-43-generic        | 11        | 0.67%   |
| 6.2.6-desktop-1omv2390   | 10        | 0.61%   |
| 5.3.0-42-generic         | 10        | 0.61%   |
| 5.19.0-35-generic        | 10        | 0.61%   |
| 5.13.0-39-generic        | 10        | 0.61%   |
| 5.13.0-28-generic        | 10        | 0.61%   |
| 5.11.0-43-generic        | 10        | 0.61%   |
| 5.4.0-7642-generic       | 9         | 0.55%   |
| 5.4.0-74-generic         | 9         | 0.55%   |
| 5.4.0-65-generic         | 9         | 0.55%   |
| 5.4.0-45-generic         | 9         | 0.55%   |
| 5.3.0-28-generic         | 9         | 0.55%   |
| 5.15.0-52-generic        | 9         | 0.55%   |
| 5.15.0-47-generic        | 9         | 0.55%   |
| 5.13.0-40-generic        | 9         | 0.55%   |
| 5.11.0-7620-generic      | 9         | 0.55%   |
| 5.11.0-37-generic        | 9         | 0.55%   |
| 5.8.0-43-generic         | 8         | 0.49%   |
| 5.4.0-37-generic         | 8         | 0.49%   |
| 4.18.0-25-generic        | 8         | 0.49%   |
| 4.18.0-15-generic        | 8         | 0.49%   |
| 6.2.15-300.fc38.x86_64   | 7         | 0.43%   |
| 5.4.0-7634-generic       | 7         | 0.43%   |
| 5.4.0-40-generic         | 7         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 232       | 14.93%  |
| 5.15.0  | 133       | 8.56%   |
| 5.11.0  | 85        | 5.47%   |
| 5.13.0  | 79        | 5.08%   |
| 5.8.0   | 72        | 4.63%   |
| 5.3.0   | 72        | 4.63%   |
| 4.15.0  | 65        | 4.18%   |
| 5.19.0  | 57        | 3.67%   |
| 5.0.0   | 54        | 3.47%   |
| 5.10.0  | 52        | 3.35%   |
| 5.16.7  | 48        | 3.09%   |
| 4.18.0  | 48        | 3.09%   |
| 5.10.14 | 43        | 2.77%   |
| 4.19.0  | 28        | 1.8%    |
| 6.1.1   | 17        | 1.09%   |
| 6.2.6   | 15        | 0.97%   |
| 6.1.0   | 9         | 0.58%   |
| 6.2.15  | 8         | 0.51%   |
| 6.2.0   | 8         | 0.51%   |
| 5.17.5  | 8         | 0.51%   |
| 6.0.12  | 7         | 0.45%   |
| 5.14.0  | 6         | 0.39%   |
| 6.2.14  | 5         | 0.32%   |
| 6.0.11  | 5         | 0.32%   |
| 5.9.1   | 5         | 0.32%   |
| 5.15.8  | 5         | 0.32%   |
| 6.1.9   | 4         | 0.26%   |
| 6.0.0   | 4         | 0.26%   |
| 5.3.18  | 4         | 0.26%   |
| 5.19.8  | 4         | 0.26%   |
| 5.17.0  | 4         | 0.26%   |
| 5.16.0  | 4         | 0.26%   |
| 5.15.13 | 4         | 0.26%   |
| 4.9.20  | 4         | 0.26%   |
| 4.4.0   | 4         | 0.26%   |
| 6.3.5   | 3         | 0.19%   |
| 6.3.2   | 3         | 0.19%   |
| 6.2.2   | 3         | 0.19%   |
| 6.2.13  | 3         | 0.19%   |
| 5.9.14  | 3         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 249       | 16.26%  |
| 5.15    | 182       | 11.89%  |
| 5.10    | 123       | 8.03%   |
| 5.11    | 94        | 6.14%   |
| 5.13    | 91        | 5.94%   |
| 5.3     | 83        | 5.42%   |
| 5.19    | 83        | 5.42%   |
| 5.8     | 79        | 5.16%   |
| 5.16    | 70        | 4.57%   |
| 4.15    | 65        | 4.25%   |
| 5.0     | 54        | 3.53%   |
| 6.2     | 49        | 3.2%    |
| 4.18    | 49        | 3.2%    |
| 6.1     | 42        | 2.74%   |
| 4.19    | 30        | 1.96%   |
| 6.0     | 29        | 1.89%   |
| 5.17    | 26        | 1.7%    |
| 5.18    | 22        | 1.44%   |
| 5.14    | 19        | 1.24%   |
| 5.9     | 16        | 1.05%   |
| 5.6     | 12        | 0.78%   |
| 4.9     | 12        | 0.78%   |
| 5.12    | 11        | 0.72%   |
| 5.7     | 10        | 0.65%   |
| 6.3     | 9         | 0.59%   |
| 5.5     | 7         | 0.46%   |
| 4.4     | 4         | 0.26%   |
| 4.13    | 3         | 0.2%    |
| 5.2     | 2         | 0.13%   |
| 4.12    | 2         | 0.13%   |
| 5.1     | 1         | 0.07%   |
| 4.10    | 1         | 0.07%   |
| 3.2     | 1         | 0.07%   |
| 3.10    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1349      | 96.56%  |
| i686   | 48        | 3.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 666       | 45.77%  |
| KDE5              | 255       | 17.53%  |
| Unknown           | 142       | 9.76%   |
| XFCE              | 104       | 7.15%   |
| X-Cinnamon        | 86        | 5.91%   |
| KDE               | 53        | 3.64%   |
| MATE              | 41        | 2.82%   |
| Pantheon          | 25        | 1.72%   |
| Cinnamon          | 16        | 1.1%    |
| LXQt              | 14        | 0.96%   |
| Budgie            | 10        | 0.69%   |
| Unity             | 7         | 0.48%   |
| LXDE              | 7         | 0.48%   |
| KDE4              | 5         | 0.34%   |
| openbox           | 4         | 0.27%   |
| i3                | 4         | 0.27%   |
| Deepin            | 4         | 0.27%   |
| trinity           | 2         | 0.14%   |
| GNOME Classic     | 2         | 0.14%   |
| Enlightenment     | 2         | 0.14%   |
| Yaru:ubuntu:GNOME | 1         | 0.07%   |
| xmonad            | 1         | 0.07%   |
| qtile             | 1         | 0.07%   |
| lightdm-xsession  | 1         | 0.07%   |
| GNOME Flashback   | 1         | 0.07%   |
| bspwm             | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1097      | 76.34%  |
| Wayland | 248       | 17.26%  |
| Unknown | 84        | 5.85%   |
| Tty     | 8         | 0.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 741       | 51.07%  |
| SDDM    | 216       | 14.89%  |
| GDM     | 176       | 12.13%  |
| GDM3    | 142       | 9.79%   |
| LightDM | 127       | 8.75%   |
| TDM     | 34        | 2.34%   |
| KDM     | 5         | 0.34%   |
| XDM     | 4         | 0.28%   |
| SLiM    | 3         | 0.21%   |
| MDM     | 1         | 0.07%   |
| Ly      | 1         | 0.07%   |
| LXDM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_MX      | 698       | 48.98%  |
| en_US      | 440       | 30.88%  |
| Unknown    | 132       | 9.26%   |
| es_ES      | 90        | 6.32%   |
| C          | 27        | 1.89%   |
| en_GB      | 11        | 0.77%   |
| es_US      | 5         | 0.35%   |
| fr_FR      | 3         | 0.21%   |
| en_CA      | 3         | 0.21%   |
| es_MX.UTF8 | 2         | 0.14%   |
| es_AR      | 2         | 0.14%   |
| en_MX      | 2         | 0.14%   |
| C.UTF8     | 2         | 0.14%   |
| uk_UA      | 1         | 0.07%   |
| pt_BR      | 1         | 0.07%   |
| POSIX      | 1         | 0.07%   |
| it_IT      | 1         | 0.07%   |
| es_PE      | 1         | 0.07%   |
| es_CR      | 1         | 0.07%   |
| es_419     | 1         | 0.07%   |
| en_IE      | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 721       | 50.42%  |
| BIOS | 709       | 49.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1086      | 76.21%  |
| Overlay | 129       | 9.05%   |
| Btrfs   | 124       | 8.7%    |
| Unknown | 36        | 2.53%   |
| Xfs     | 21        | 1.47%   |
| Tmpfs   | 11        | 0.77%   |
| Zfs     | 9         | 0.63%   |
| Ext2    | 4         | 0.28%   |
| XXXXXXX | 2         | 0.14%   |
| Ext3    | 2         | 0.14%   |
| Aufs    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 808       | 56.46%  |
| GPT     | 467       | 32.63%  |
| MBR     | 156       | 10.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1262      | 89.06%  |
| Yes       | 155       | 10.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 983       | 69.13%  |
| Yes       | 439       | 30.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 339       | 24.28%  |
| Lenovo              | 269       | 19.27%  |
| Dell                | 208       | 14.9%   |
| Acer                | 110       | 7.88%   |
| ASUSTek Computer    | 100       | 7.16%   |
| Toshiba             | 68        | 4.87%   |
| HUAWEI              | 54        | 3.87%   |
| Apple               | 53        | 3.8%    |
| Sony                | 40        | 2.87%   |
| Samsung Electronics | 19        | 1.36%   |
| MSI                 | 19        | 1.36%   |
| Gateway             | 17        | 1.22%   |
| Google              | 14        | 1%      |
| Alienware           | 11        | 0.79%   |
| Lanix               | 7         | 0.5%    |
| Unknown             | 7         | 0.5%    |
| Valve               | 6         | 0.43%   |
| Chuwi               | 6         | 0.43%   |
| EVOO                | 4         | 0.29%   |
| A-DATA Technology   | 4         | 0.29%   |
| Timi                | 3         | 0.21%   |
| System76            | 3         | 0.21%   |
| Notebook            | 3         | 0.21%   |
| HONOR               | 3         | 0.21%   |
| GPU Company         | 3         | 0.21%   |
| eMachines           | 3         | 0.21%   |
| Panasonic           | 2         | 0.14%   |
| Insyde              | 2         | 0.14%   |
| GHIA                | 2         | 0.14%   |
| Corporativo Lanix   | 2         | 0.14%   |
| American Megatrends | 2         | 0.14%   |
| TECH PAD            | 1         | 0.07%   |
| SK hynix            | 1         | 0.07%   |
| Schenker            | 1         | 0.07%   |
| Razer               | 1         | 0.07%   |
| LG Electronics      | 1         | 0.07%   |
| Lanix America       | 1         | 0.07%   |
| Hyundai Technology  | 1         | 0.07%   |
| Hannspree           | 1         | 0.07%   |
| Eluktronics         | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP Notebook                   | 27        | 1.93%   |
| Unknown                       | 21        | 1.5%    |
| HP Pavilion Laptop 15-cw0xxx  | 17        | 1.22%   |
| HP Pavilion g4                | 15        | 1.07%   |
| HUAWEI HVY-WXX9               | 14        | 1%      |
| HP Pavilion Notebook          | 13        | 0.93%   |
| HP Pavilion Laptop 15-cw1xxx  | 10        | 0.72%   |
| Apple MacBookPro9,2           | 10        | 0.72%   |
| HP Laptop 15-da0xxx           | 9         | 0.64%   |
| Lenovo IdeaPad 330-14AST 81D5 | 8         | 0.57%   |
| HP Laptop 15-bw0xx            | 8         | 0.57%   |
| HP EliteBook 8460p            | 8         | 0.57%   |
| Dell Latitude E6430           | 8         | 0.57%   |
| HP Pavilion dv4               | 7         | 0.5%    |
| Dell Inspiron 5559            | 7         | 0.5%    |
| Apple MacBookPro8,1           | 7         | 0.5%    |
| Valve Jupiter                 | 6         | 0.43%   |
| HP Pavilion dv5               | 6         | 0.43%   |
| Dell Inspiron 3421            | 6         | 0.43%   |
| Acer Aspire E5-573            | 6         | 0.43%   |
| Lenovo Y50-70 20378           | 5         | 0.36%   |
| Lenovo G50-30 80G0            | 5         | 0.36%   |
| HUAWEI NBLB-WAX9N             | 5         | 0.36%   |
| HP Pavilion 14                | 5         | 0.36%   |
| HP Laptop 15-db0xxx           | 5         | 0.36%   |
| HP Laptop 15-da2xxx           | 5         | 0.36%   |
| HP Laptop 14-cm0xxx           | 5         | 0.36%   |
| Dell Latitude E6400           | 5         | 0.36%   |
| Apple MacBookPro12,1          | 5         | 0.36%   |
| Acer Aspire E3-112M           | 5         | 0.36%   |
| Toshiba Satellite L855        | 4         | 0.29%   |
| Toshiba Satellite L55-B       | 4         | 0.29%   |
| Lenovo Y720-15IKB 80VR        | 4         | 0.29%   |
| Lenovo IdeaPad 330-15AST 81D6 | 4         | 0.29%   |
| Lenovo IdeaPad 3 15ALC6 82KU  | 4         | 0.29%   |
| Lenovo G40-45 80E1            | 4         | 0.29%   |
| HUAWEI NBLK-WAX9X             | 4         | 0.29%   |
| HUAWEI BOHK-WAX9X             | 4         | 0.29%   |
| HP Pavilion 15                | 4         | 0.29%   |
| HP Laptop 15-bs0xx            | 4         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 110       | 7.88%   |
| Lenovo ThinkPad    | 104       | 7.45%   |
| Lenovo IdeaPad     | 98        | 7.02%   |
| Dell Inspiron      | 79        | 5.66%   |
| Dell Latitude      | 77        | 5.52%   |
| Acer Aspire        | 77        | 5.52%   |
| Toshiba Satellite  | 63        | 4.51%   |
| HP Laptop          | 60        | 4.3%    |
| HP Notebook        | 27        | 1.93%   |
| HP EliteBook       | 26        | 1.86%   |
| ASUS VivoBook      | 25        | 1.79%   |
| HP ProBook         | 24        | 1.72%   |
| Unknown            | 21        | 1.5%    |
| HUAWEI HVY-WXX9    | 14        | 1%      |
| HP Compaq          | 13        | 0.93%   |
| HP 240             | 11        | 0.79%   |
| Dell Vostro        | 11        | 0.79%   |
| Apple MacBookPro9  | 11        | 0.79%   |
| Lenovo Legion      | 9         | 0.64%   |
| HP ENVY            | 9         | 0.64%   |
| Dell XPS           | 9         | 0.64%   |
| Dell Studio        | 9         | 0.64%   |
| Apple MacBookPro8  | 8         | 0.57%   |
| HP OMEN            | 7         | 0.5%    |
| Acer Nitro         | 7         | 0.5%    |
| Valve Jupiter      | 6         | 0.43%   |
| HP ZBook           | 6         | 0.43%   |
| Dell Precision     | 6         | 0.43%   |
| ASUS ASUS          | 6         | 0.43%   |
| MSI GF63           | 5         | 0.36%   |
| Lenovo Yoga        | 5         | 0.36%   |
| Lenovo Y50-70      | 5         | 0.36%   |
| Lenovo G50-30      | 5         | 0.36%   |
| HUAWEI NBLB-WAX9N  | 5         | 0.36%   |
| HP 245             | 5         | 0.36%   |
| Dell G3            | 5         | 0.36%   |
| Dell G15           | 5         | 0.36%   |
| Apple MacBookPro12 | 5         | 0.36%   |
| Lenovo Y720-15IKB  | 4         | 0.29%   |
| Lenovo G40-45      | 4         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 127       | 9.1%    |
| 2011    | 122       | 8.74%   |
| 2019    | 121       | 8.67%   |
| 2020    | 109       | 7.81%   |
| 2012    | 108       | 7.74%   |
| 2015    | 105       | 7.52%   |
| 2013    | 96        | 6.88%   |
| 2017    | 94        | 6.73%   |
| 2014    | 93        | 6.66%   |
| 2021    | 90        | 6.45%   |
| 2010    | 81        | 5.8%    |
| 2016    | 74        | 5.3%    |
| 2008    | 73        | 5.23%   |
| 2009    | 35        | 2.51%   |
| 2022    | 26        | 1.86%   |
| 2007    | 24        | 1.72%   |
| 2006    | 8         | 0.57%   |
| 2005    | 4         | 0.29%   |
| Unknown | 3         | 0.21%   |
| 2004    | 2         | 0.14%   |
| 2023    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1396      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1240      | 87.82%  |
| Enabled  | 172       | 12.18%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1380      | 98.85%  |
| Yes  | 16        | 1.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 423       | 29.96%  |
| 3.01-4.0    | 337       | 23.87%  |
| 8.01-16.0   | 269       | 19.05%  |
| 16.01-24.0  | 172       | 12.18%  |
| 1.01-2.0    | 95        | 6.73%   |
| 32.01-64.0  | 44        | 3.12%   |
| 2.01-3.0    | 30        | 2.12%   |
| 0.51-1.0    | 17        | 1.2%    |
| 24.01-32.0  | 16        | 1.13%   |
| 64.01-256.0 | 9         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 562       | 36.66%  |
| 2.01-3.0   | 435       | 28.38%  |
| 3.01-4.0   | 196       | 12.79%  |
| 4.01-8.0   | 170       | 11.09%  |
| 0.51-1.0   | 105       | 6.85%   |
| 8.01-16.0  | 43        | 2.8%    |
| 0.01-0.5   | 14        | 0.91%   |
| 16.01-24.0 | 6         | 0.39%   |
| 32.01-64.0 | 1         | 0.07%   |
| Unknown    | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1075      | 75.49%  |
| 2      | 298       | 20.93%  |
| 3      | 26        | 1.83%   |
| 0      | 18        | 1.26%   |
| 4      | 5         | 0.35%   |
| 6      | 1         | 0.07%   |
| 5      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 891       | 63.46%  |
| Yes       | 513       | 36.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1146      | 82.09%  |
| No        | 250       | 17.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1372      | 98.28%  |
| No        | 24        | 1.72%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1040      | 73.45%  |
| No        | 376       | 26.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Mexico  | 1396      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Mexico City           | 311       | 21.1%   |
| Guadalajara           | 73        | 4.95%   |
| Monterrey             | 44        | 2.99%   |
| Zapopan               | 41        | 2.78%   |
| Puebla City           | 40        | 2.71%   |
| Tijuana               | 39        | 2.65%   |
| Queretaro             | 32        | 2.17%   |
| Mérida               | 25        | 1.7%    |
| Cancún               | 24        | 1.63%   |
| Toluca                | 23        | 1.56%   |
| Xalapa                | 18        | 1.22%   |
| Hermosillo            | 18        | 1.22%   |
| Ciudad Lopez Mateos   | 17        | 1.15%   |
| Ecatepec              | 16        | 1.09%   |
| Ciudad Juárez        | 16        | 1.09%   |
| Naucalpan             | 15        | 1.02%   |
| Mexicali              | 15        | 1.02%   |
| León                 | 15        | 1.02%   |
| Apodaca               | 15        | 1.02%   |
| Veracruz              | 14        | 0.95%   |
| Tlalnepantla          | 13        | 0.88%   |
| Morelia               | 13        | 0.88%   |
| Culiacán             | 13        | 0.88%   |
| Cuernavaca            | 13        | 0.88%   |
| Celaya                | 13        | 0.88%   |
| Villahermosa          | 12        | 0.81%   |
| Mexico                | 12        | 0.81%   |
| Guadalupe             | 12        | 0.81%   |
| Ciudad Nezahualcoyotl | 12        | 0.81%   |
| Chihuahua City        | 12        | 0.81%   |
| San Luis Potosí City | 11        | 0.75%   |
| Oaxaca City           | 11        | 0.75%   |
| Durango               | 11        | 0.75%   |
| Cuautitlán Izcalli   | 11        | 0.75%   |
| Zacatecas City        | 10        | 0.68%   |
| Iztapalapa            | 10        | 0.68%   |
| Ensenada              | 10        | 0.68%   |
| Azcapotzalco          | 10        | 0.68%   |
| Puerto Vallarta       | 9         | 0.61%   |
| Acapulco de Juárez   | 9         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 248       | 312    | 14.51%  |
| WDC                         | 224       | 279    | 13.11%  |
| Toshiba                     | 178       | 217    | 10.42%  |
| Kingston                    | 164       | 201    | 9.6%    |
| Samsung Electronics         | 132       | 168    | 7.72%   |
| A-DATA Technology           | 112       | 131    | 6.55%   |
| Unknown                     | 97        | 111    | 5.68%   |
| Hitachi                     | 79        | 87     | 4.62%   |
| HGST                        | 69        | 73     | 4.04%   |
| SanDisk                     | 67        | 87     | 3.92%   |
| SK hynix                    | 39        | 48     | 2.28%   |
| Intel                       | 33        | 46     | 1.93%   |
| Apple                       | 25        | 33     | 1.46%   |
| Crucial                     | 20        | 22     | 1.17%   |
| Micron Technology           | 19        | 20     | 1.11%   |
| XPG                         | 14        | 22     | 0.82%   |
| Fujitsu                     | 13        | 14     | 0.76%   |
| LITEON                      | 11        | 16     | 0.64%   |
| KIOXIA                      | 10        | 12     | 0.59%   |
| Phison                      | 9         | 9      | 0.53%   |
| YMTC                        | 8         | 9      | 0.47%   |
| Realtek Semiconductor       | 8         | 9      | 0.47%   |
| China                       | 8         | 8      | 0.47%   |
| Silicon Motion              | 7         | 7      | 0.41%   |
| ADATA Technology            | 7         | 7      | 0.41%   |
| Unknown                     | 7         | 7      | 0.41%   |
| Phison Electronics          | 6         | 7      | 0.35%   |
| Netac                       | 6         | 6      | 0.35%   |
| PNY                         | 5         | 7      | 0.29%   |
| JMicron Technology          | 5         | 5      | 0.29%   |
| Patriot                     | 4         | 7      | 0.23%   |
| LITEONIT                    | 4         | 4      | 0.23%   |
| Kingston Technology Company | 4         | 4      | 0.23%   |
| Union Memory (Shenzhen)     | 3         | 3      | 0.18%   |
| SABRENT                     | 3         | 3      | 0.18%   |
| Pioneer                     | 3         | 4      | 0.18%   |
| Hewlett-Packard             | 3         | 3      | 0.18%   |
| Gigabyte Technology         | 3         | 3      | 0.18%   |
| BHT                         | 3         | 3      | 0.18%   |
| AS201                       | 3         | 3      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 58        | 3.29%   |
| Kingston SA400S37240G 240GB SSD                     | 39        | 2.21%   |
| Toshiba MQ01ABD100 1TB                              | 37        | 2.1%    |
| Toshiba MQ04ABF100 1TB                              | 36        | 2.04%   |
| Kingston SA400S37480G 480GB SSD                     | 36        | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 34        | 1.93%   |
| Unknown MMC Card  32GB                              | 23        | 1.31%   |
| Toshiba MQ01ABF050 500GB                            | 22        | 1.25%   |
| Seagate ST500LT012-1DG142 500GB                     | 22        | 1.25%   |
| A-DATA SU650 120GB SSD                              | 19        | 1.08%   |
| A-DATA SU630 240GB SSD                              | 16        | 0.91%   |
| Unknown MMC Card  64GB                              | 13        | 0.74%   |
| Kingston SA400S37960G 960GB SSD                     | 13        | 0.74%   |
| HGST HTS725050A7E630 500GB                          | 13        | 0.74%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 12        | 0.68%   |
| HGST HTS541010A9E680 1TB                            | 12        | 0.68%   |
| Samsung NVMe SSD Drive 512GB                        | 11        | 0.62%   |
| Seagate ST9500325AS 500GB                           | 10        | 0.57%   |
| Seagate ST500LM021-1KJ152 500GB                     | 10        | 0.57%   |
| HGST HTS721010A9E630 1TB                            | 10        | 0.57%   |
| A-DATA SU650 240GB SSD                              | 10        | 0.57%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 9         | 0.51%   |
| WDC WD10SPZX-08Z10 1TB                              | 9         | 0.51%   |
| WDC WD10JPVX-60JC3T1 1TB                            | 9         | 0.51%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 9         | 0.51%   |
| Unknown MMC Card  16GB                              | 9         | 0.51%   |
| Seagate ST2000LM007-1R8174 2TB                      | 9         | 0.51%   |
| Seagate Expansion 1TB                               | 9         | 0.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 9         | 0.51%   |
| Kingston SA400S37120G 120GB SSD                     | 9         | 0.51%   |
| HGST HTS545050A7E680 500GB                          | 9         | 0.51%   |
| HGST HTS541075A9E680 752GB                          | 9         | 0.51%   |
| A-DATA SU630 480GB SSD                              | 9         | 0.51%   |
| YMTC PC005 512GB                                    | 7         | 0.4%    |
| WDC WD10SPZX-60Z10T0 1TB                            | 7         | 0.4%    |
| Seagate ST1000LM049-2GH172 1TB                      | 7         | 0.4%    |
| Seagate ST1000LM048-2E7172 1TB                      | 7         | 0.4%    |
| Kingston SUV400S37480G 480GB SSD                    | 7         | 0.4%    |
| Hitachi HTS547550A9E384 500GB                       | 7         | 0.4%    |
| A-DATA SU800 512GB SSD                              | 7         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 246       | 308    | 31.46%  |
| WDC                 | 186       | 227    | 23.79%  |
| Toshiba             | 159       | 194    | 20.33%  |
| Hitachi             | 79        | 87     | 10.1%   |
| HGST                | 69        | 73     | 8.82%   |
| Samsung Electronics | 13        | 14     | 1.66%   |
| Fujitsu             | 13        | 14     | 1.66%   |
| Unknown             | 5         | 5      | 0.64%   |
| Apple               | 4         | 5      | 0.51%   |
| Pioneer             | 2         | 3      | 0.26%   |
| Hewlett-Packard     | 2         | 2      | 0.26%   |
| SAGE                | 1         | 1      | 0.13%   |
| LaCie               | 1         | 2      | 0.13%   |
| IBM/Hitachi         | 1         | 1      | 0.13%   |
| ASMedia             | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 147       | 181    | 30.95%  |
| A-DATA Technology   | 106       | 125    | 22.32%  |
| Samsung Electronics | 42        | 47     | 8.84%   |
| SanDisk             | 28        | 33     | 5.89%   |
| WDC                 | 17        | 24     | 3.58%   |
| Crucial             | 17        | 17     | 3.58%   |
| Apple               | 16        | 18     | 3.37%   |
| LITEON              | 10        | 15     | 2.11%   |
| SK hynix            | 9         | 10     | 1.89%   |
| Micron Technology   | 8         | 9      | 1.68%   |
| China               | 8         | 8      | 1.68%   |
| Intel               | 7         | 8      | 1.47%   |
| Netac               | 6         | 6      | 1.26%   |
| PNY                 | 5         | 7      | 1.05%   |
| LITEONIT            | 4         | 4      | 0.84%   |
| Toshiba             | 3         | 3      | 0.63%   |
| Patriot             | 3         | 6      | 0.63%   |
| Gigabyte Technology | 3         | 3      | 0.63%   |
| BHT                 | 3         | 3      | 0.63%   |
| AS201               | 3         | 3      | 0.63%   |
| Unknown             | 3         | 3      | 0.63%   |
| Unknown             | 2         | 2      | 0.42%   |
| OCZ                 | 2         | 4      | 0.42%   |
| JMicron Technology  | 2         | 2      | 0.42%   |
| Blackpcs            | 2         | 2      | 0.42%   |
| ZTC                 | 1         | 1      | 0.21%   |
| Zheino              | 1         | 1      | 0.21%   |
| Yeyian              | 1         | 3      | 0.21%   |
| Wibtek              | 1         | 1      | 0.21%   |
| Transcend           | 1         | 1      | 0.21%   |
| Team                | 1         | 1      | 0.21%   |
| StoreJet            | 1         | 1      | 0.21%   |
| SSSTC               | 1         | 1      | 0.21%   |
| SPCC                | 1         | 1      | 0.21%   |
| ShanDianZhe         | 1         | 2      | 0.21%   |
| SABRENT             | 1         | 1      | 0.21%   |
| Pioneer             | 1         | 1      | 0.21%   |
| Lexar               | 1         | 1      | 0.21%   |
| KingSpec            | 1         | 4      | 0.21%   |
| Hikvision           | 1         | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 767       | 937    | 46.6%   |
| SSD     | 443       | 571    | 26.91%  |
| NVMe    | 320       | 438    | 19.44%  |
| MMC     | 94        | 109    | 5.71%   |
| Unknown | 22        | 27     | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1101      | 1467   | 69.99%  |
| NVMe | 319       | 437    | 20.28%  |
| MMC  | 94        | 109    | 5.98%   |
| SAS  | 59        | 69     | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 762       | 957    | 63.45%  |
| 0.51-1.0   | 404       | 498    | 33.64%  |
| 1.01-2.0   | 30        | 47     | 2.5%    |
| 3.01-4.0   | 3         | 4      | 0.25%   |
| 10.01-20.0 | 1         | 1      | 0.08%   |
| 4.01-10.0  | 1         | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 395       | 27.07%  |
| 251-500        | 360       | 24.67%  |
| 501-1000       | 244       | 16.72%  |
| 1-20           | 130       | 8.91%   |
| 51-100         | 122       | 8.36%   |
| 1001-2000      | 81        | 5.55%   |
| 21-50          | 74        | 5.07%   |
| More than 3000 | 20        | 1.37%   |
| 2001-3000      | 17        | 1.17%   |
| Unknown        | 16        | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 665       | 43.92%  |
| 21-50          | 298       | 19.68%  |
| 101-250        | 187       | 12.35%  |
| 51-100         | 161       | 10.63%  |
| 251-500        | 99        | 6.54%   |
| 501-1000       | 59        | 3.9%    |
| 1001-2000      | 21        | 1.39%   |
| Unknown        | 16        | 1.06%   |
| More than 3000 | 5         | 0.33%   |
| 2001-3000      | 3         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 6         | 7      | 4.62%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 6      | 3.85%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 4      | 3.08%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 3.08%   |
| HGST HTS541075A9E680 752GB          | 4         | 4      | 3.08%   |
| Toshiba MQ04ABF100 1TB              | 3         | 3      | 2.31%   |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 2.31%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 2      | 1.54%   |
| WDC WD2500BEVS-60UST0 250GB         | 2         | 2      | 1.54%   |
| Seagate ST9500420AS 500GB           | 2         | 2      | 1.54%   |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 2      | 1.54%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 2      | 1.54%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 2         | 2      | 1.54%   |
| LITEON CV8-8E128-HP 128GB SSD       | 2         | 2      | 1.54%   |
| Hitachi HTS545016B9A300 160GB       | 2         | 2      | 1.54%   |
| Hitachi HTS543232A7A384 320GB       | 2         | 2      | 1.54%   |
| HGST HTS541010A7E630 1TB            | 2         | 2      | 1.54%   |
| China SSD 256GB                     | 2         | 2      | 1.54%   |
| A-DATA Technology SU650 240GB SSD   | 2         | 2      | 1.54%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.77%   |
| WDC WD5000BPVT-22HXZT1 500GB        | 1         | 2      | 0.77%   |
| WDC WD50 00BEVT-11ZAT0 500GB        | 1         | 1      | 0.77%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 0.77%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 1      | 0.77%   |
| WDC WD2500LPVX-22V0TT0 250GB        | 1         | 1      | 0.77%   |
| WDC WD2500BEVT-80A23T0 250GB        | 1         | 2      | 0.77%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1         | 1      | 0.77%   |
| WDC WD10SPZX-24Z10T0 1TB            | 1         | 1      | 0.77%   |
| WDC WD10SPCX-60KHST0 1TB            | 1         | 1      | 0.77%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 1      | 0.77%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 0.77%   |
| WDC WD10JPVX-55JC3T3 1TB            | 1         | 1      | 0.77%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 0.77%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 0.77%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 0.77%   |
| Toshiba MK7559GSXP 752GB            | 1         | 7      | 0.77%   |
| Toshiba MK6465GSX 640GB             | 1         | 1      | 0.77%   |
| Toshiba MK3276GSX H 320GB           | 1         | 1      | 0.77%   |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 0.77%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 25        | 32     | 19.23%  |
| Seagate             | 25        | 29     | 19.23%  |
| Hitachi             | 22        | 23     | 16.92%  |
| WDC                 | 18        | 20     | 13.85%  |
| HGST                | 14        | 14     | 10.77%  |
| Kingston            | 9         | 9      | 6.92%   |
| SanDisk             | 4         | 4      | 3.08%   |
| Fujitsu             | 3         | 3      | 2.31%   |
| Samsung Electronics | 2         | 2      | 1.54%   |
| LITEON              | 2         | 2      | 1.54%   |
| China               | 2         | 2      | 1.54%   |
| A-DATA Technology   | 2         | 2      | 1.54%   |
| Micron Technology   | 1         | 1      | 0.77%   |
| Crucial             | 1         | 1      | 0.77%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 25        | 32     | 23.15%  |
| Seagate             | 25        | 29     | 23.15%  |
| Hitachi             | 22        | 23     | 20.37%  |
| WDC                 | 18        | 20     | 16.67%  |
| HGST                | 14        | 14     | 12.96%  |
| Fujitsu             | 3         | 3      | 2.78%   |
| Samsung Electronics | 1         | 1      | 0.93%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 108       | 122    | 83.08%  |
| SSD  | 19        | 19     | 14.62%  |
| NVMe | 3         | 3      | 2.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-75A23T0 160GB  | 1         | 1      | 50%     |
| Hitachi HTS545016B9A300 160GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 895       | 1327   | 61.09%  |
| Works    | 440       | 609    | 30.03%  |
| Malfunc  | 128       | 144    | 8.74%   |
| Failed   | 2         | 2      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 932       | 59.86%  |
| AMD                                     | 282       | 18.11%  |
| Samsung Electronics                     | 84        | 5.39%   |
| SanDisk                                 | 58        | 3.73%   |
| SK hynix                                | 30        | 1.93%   |
| Kingston Technology Company             | 21        | 1.35%   |
| Nvidia                                  | 19        | 1.22%   |
| ADATA Technology                        | 19        | 1.22%   |
| Toshiba America Info Systems            | 17        | 1.09%   |
| Phison Electronics                      | 15        | 0.96%   |
| Realtek Semiconductor                   | 13        | 0.83%   |
| Micron Technology                       | 11        | 0.71%   |
| KIOXIA                                  | 11        | 0.71%   |
| Yangtze Memory Technologies             | 8         | 0.51%   |
| Silicon Motion                          | 7         | 0.45%   |
| Union Memory (Shenzhen)                 | 6         | 0.39%   |
| Micron/Crucial Technology               | 5         | 0.32%   |
| Marvell Technology Group                | 5         | 0.32%   |
| Apple                                   | 5         | 0.32%   |
| Lite-On Technology                      | 2         | 0.13%   |
| Solid State Storage Technology          | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.06%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.06%   |
| Lenovo                                  | 1         | 0.06%   |
| Biwin Storage Technology                | 1         | 0.06%   |
| Unknown                                 | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 229       | 13.71%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 111       | 6.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 107       | 6.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 77        | 4.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 76        | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 46        | 2.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 44        | 2.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 40        | 2.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 39        | 2.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 38        | 2.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 38        | 2.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 34        | 2.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 30        | 1.8%    |
| Samsung NVMe SSD Controller 980                                                  | 29        | 1.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 29        | 1.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 28        | 1.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 26        | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 25        | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 21        | 1.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 21        | 1.26%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 20        | 1.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 20        | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                              | 18        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                            | 18        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 0.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 14        | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 14        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 14        | 0.84%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 13        | 0.78%   |
| SanDisk Non-Volatile memory controller                                           | 13        | 0.78%   |
| Phison PS5013 E13 NVMe Controller                                                | 13        | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 13        | 0.78%   |
| Realtek NVMe Controller                                                          | 12        | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 0.72%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 11        | 0.66%   |
| Micron NVMe Storage Controller                                                   | 11        | 0.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 11        | 0.66%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 10        | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 10        | 0.6%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 9         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1058      | 65.27%  |
| NVMe | 321       | 19.8%   |
| RAID | 132       | 8.14%   |
| IDE  | 110       | 6.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1047      | 75%     |
| AMD    | 349       | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 22        | 1.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 1.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 20        | 1.43%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 19        | 1.36%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 18        | 1.29%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 18        | 1.29%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 1.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 16        | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 1.07%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 15        | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1%      |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 1%      |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 14        | 1%      |
| Intel Celeron N4000 CPU @ 1.10GHz             | 13        | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.86%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 12        | 0.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 12        | 0.86%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 12        | 0.86%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 0.86%   |
| AMD Ryzen 3 2300U with Radeon Vega Mobile Gfx | 12        | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 0.79%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 11        | 0.79%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 11        | 0.79%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 11        | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 0.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 10        | 0.72%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 10        | 0.72%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 10        | 0.72%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 0.72%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 10        | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.64%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 9         | 0.64%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 9         | 0.64%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 8         | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 283       | 20.27%  |
| Intel Core i7                  | 254       | 18.19%  |
| Intel Celeron                  | 154       | 11.03%  |
| Intel Core i3                  | 128       | 9.17%   |
| Other                          | 74        | 5.3%    |
| AMD Ryzen 5                    | 72        | 5.16%   |
| Intel Core 2 Duo               | 60        | 4.3%    |
| Intel Atom                     | 43        | 3.08%   |
| AMD Ryzen 7                    | 32        | 2.29%   |
| AMD A6                         | 28        | 2.01%   |
| AMD A8                         | 26        | 1.86%   |
| Intel Pentium                  | 25        | 1.79%   |
| AMD Ryzen 3                    | 22        | 1.58%   |
| AMD A4                         | 21        | 1.5%    |
| AMD E                          | 20        | 1.43%   |
| AMD A10                        | 20        | 1.43%   |
| Intel Pentium Dual             | 13        | 0.93%   |
| AMD Turion 64 X2 Mobile        | 10        | 0.72%   |
| Intel Pentium Dual-Core        | 9         | 0.64%   |
| AMD Athlon II                  | 9         | 0.64%   |
| Intel Genuine                  | 8         | 0.57%   |
| Intel Core 2                   | 6         | 0.43%   |
| AMD Ryzen 9                    | 6         | 0.43%   |
| AMD Ryzen 5 PRO                | 6         | 0.43%   |
| AMD E1                         | 6         | 0.43%   |
| AMD FX                         | 5         | 0.36%   |
| AMD Athlon                     | 5         | 0.36%   |
| AMD A12                        | 5         | 0.36%   |
| AMD E2                         | 4         | 0.29%   |
| AMD Athlon 64 X2               | 4         | 0.29%   |
| Intel Pentium Silver           | 3         | 0.21%   |
| Intel Celeron M                | 3         | 0.21%   |
| AMD Sempron                    | 3         | 0.21%   |
| Intel Pentium M                | 2         | 0.14%   |
| Intel Core Duo                 | 2         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.14%   |
| AMD C-60                       | 2         | 0.14%   |
| AMD Athlon X2                  | 2         | 0.14%   |
| AMD Athlon II Neo              | 2         | 0.14%   |
| Intel Xeon                     | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 828       | 59.31%  |
| 4      | 382       | 27.36%  |
| 6      | 87        | 6.23%   |
| 1      | 63        | 4.51%   |
| 8      | 29        | 2.08%   |
| 10     | 3         | 0.21%   |
| 14     | 2         | 0.14%   |
| 12     | 1         | 0.07%   |
| 3      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1396      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 907       | 64.97%  |
| 1      | 488       | 34.96%  |
| 4      | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1359      | 97.35%  |
| 32-bit         | 18        | 1.29%   |
| Unknown        | 14        | 1%      |
| 64-bit         | 5         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 328       | 22.65%  |
| 0x206a7    | 91        | 6.28%   |
| 0x306a9    | 72        | 4.97%   |
| 0x40651    | 51        | 3.52%   |
| 0x806ec    | 43        | 2.97%   |
| 0x306d4    | 38        | 2.62%   |
| 0x30678    | 36        | 2.49%   |
| 0x806e9    | 34        | 2.35%   |
| 0x1067a    | 33        | 2.28%   |
| 0x06006705 | 32        | 2.21%   |
| 0x906ea    | 31        | 2.14%   |
| 0x806ea    | 30        | 2.07%   |
| 0x806c1    | 30        | 2.07%   |
| 0x406e3    | 28        | 1.93%   |
| 0x20655    | 26        | 1.8%    |
| 0x08108109 | 25        | 1.73%   |
| 0x406c4    | 22        | 1.52%   |
| 0x406c3    | 22        | 1.52%   |
| 0x6fd      | 21        | 1.45%   |
| 0x106ca    | 21        | 1.45%   |
| 0x08600106 | 21        | 1.45%   |
| 0x506e3    | 20        | 1.38%   |
| 0x306c3    | 20        | 1.38%   |
| 0x0810100b | 20        | 1.38%   |
| 0x08108102 | 18        | 1.24%   |
| 0x20652    | 17        | 1.17%   |
| 0x10676    | 16        | 1.1%    |
| 0x07030105 | 16        | 1.1%    |
| 0x706e5    | 15        | 1.04%   |
| 0x506c9    | 15        | 1.04%   |
| 0x05000119 | 15        | 1.04%   |
| 0xa0652    | 14        | 0.97%   |
| 0x906e9    | 14        | 0.97%   |
| 0x06001119 | 14        | 0.97%   |
| 0x706a1    | 13        | 0.9%    |
| 0x010000c8 | 12        | 0.83%   |
| 0x08608103 | 10        | 0.69%   |
| 0x106c2    | 9         | 0.62%   |
| 0x06006704 | 9         | 0.62%   |
| 0x06006110 | 9         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 202       | 14.47%  |
| SandyBridge      | 116       | 8.31%   |
| IvyBridge        | 94        | 6.73%   |
| Silvermont       | 93        | 6.66%   |
| Haswell          | 87        | 6.23%   |
| Excavator        | 66        | 4.73%   |
| Skylake          | 64        | 4.58%   |
| Penryn           | 60        | 4.3%    |
| Zen+             | 54        | 3.87%   |
| Broadwell        | 53        | 3.8%    |
| Westmere         | 47        | 3.37%   |
| Core             | 43        | 3.08%   |
| TigerLake        | 36        | 2.58%   |
| Zen 2            | 34        | 2.44%   |
| Bonnell          | 32        | 2.29%   |
| Goldmont plus    | 30        | 2.15%   |
| Bobcat           | 29        | 2.08%   |
| Unknown          | 29        | 2.08%   |
| Zen              | 25        | 1.79%   |
| CometLake        | 24        | 1.72%   |
| Piledriver       | 23        | 1.65%   |
| Puma             | 22        | 1.58%   |
| Goldmont         | 21        | 1.5%    |
| Icelake          | 20        | 1.43%   |
| K8 Hammer        | 18        | 1.29%   |
| K10              | 16        | 1.15%   |
| Zen 3            | 12        | 0.86%   |
| P6               | 10        | 0.72%   |
| K8 & K10 hybrid  | 9         | 0.64%   |
| Jaguar           | 9         | 0.64%   |
| K10 Llano        | 6         | 0.43%   |
| Alderlake Hybrid | 5         | 0.36%   |
| Steamroller      | 3         | 0.21%   |
| Tremont          | 2         | 0.14%   |
| Nehalem          | 2         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 987       | 60.66%  |
| AMD                              | 388       | 23.85%  |
| Nvidia                           | 251       | 15.43%  |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 108       | 6.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 87        | 5.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 60        | 3.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 55        | 3.24%   |
| Intel HD Graphics 5500                                                                   | 47        | 2.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 47        | 2.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 46        | 2.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 43        | 2.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 41        | 2.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 41        | 2.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 41        | 2.41%   |
| Intel HD Graphics 620                                                                    | 40        | 2.36%   |
| AMD Renoir                                                                               | 33        | 1.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 1.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 32        | 1.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 32        | 1.88%   |
| Intel UHD Graphics 620                                                                   | 31        | 1.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 28        | 1.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 28        | 1.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 1.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 27        | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 1.47%   |
| Intel HD Graphics 530                                                                    | 24        | 1.41%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 24        | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 23        | 1.35%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 23        | 1.35%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 21        | 1.24%   |
| Intel HD Graphics 500                                                                    | 18        | 1.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 17        | 1%      |
| Intel HD Graphics 630                                                                    | 17        | 1%      |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 17        | 1%      |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 17        | 1%      |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 16        | 0.94%   |
| AMD Lucienne                                                                             | 15        | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.77%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 13        | 0.77%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 13        | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 13        | 0.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 10        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 773       | 55.29%  |
| 1 x AMD        | 308       | 22.03%  |
| Intel + Nvidia | 172       | 12.3%   |
| 1 x Nvidia     | 57        | 4.08%   |
| Intel + AMD    | 33        | 2.36%   |
| 2 x AMD        | 26        | 1.86%   |
| AMD + Nvidia   | 21        | 1.5%    |
| Other          | 4         | 0.29%   |
| 2 x Intel      | 3         | 0.21%   |
| 1 x SiS        | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1257      | 89.4%   |
| Proprietary | 122       | 8.68%   |
| Unknown     | 27        | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 931       | 65.47%  |
| 0.01-0.5   | 204       | 14.35%  |
| 1.01-2.0   | 114       | 8.02%   |
| 0.51-1.0   | 92        | 6.47%   |
| 3.01-4.0   | 50        | 3.52%   |
| 5.01-6.0   | 16        | 1.13%   |
| 7.01-8.0   | 11        | 0.77%   |
| 2.01-3.0   | 4         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 273       | 17.41%  |
| BOE                     | 253       | 16.14%  |
| Chimei Innolux          | 228       | 14.54%  |
| LG Display              | 215       | 13.71%  |
| Samsung Electronics     | 171       | 10.91%  |
| Apple                   | 56        | 3.57%   |
| Chi Mei Optoelectronics | 38        | 2.42%   |
| Lenovo                  | 30        | 1.91%   |
| Goldstar                | 30        | 1.91%   |
| Hewlett-Packard         | 29        | 1.85%   |
| Dell                    | 25        | 1.59%   |
| LG Philips              | 22        | 1.4%    |
| BenQ                    | 20        | 1.28%   |
| Sharp                   | 17        | 1.08%   |
| PANDA                   | 17        | 1.08%   |
| Acer                    | 15        | 0.96%   |
| HannStar                | 11        | 0.7%    |
| Unknown                 | 10        | 0.64%   |
| InfoVision              | 8         | 0.51%   |
| AOC                     | 7         | 0.45%   |
| Sony                    | 6         | 0.38%   |
| Valve                   | 5         | 0.32%   |
| InnoLux Display         | 5         | 0.32%   |
| JDI                     | 4         | 0.26%   |
| Gateway                 | 4         | 0.26%   |
| CPT                     | 4         | 0.26%   |
| ___                     | 3         | 0.19%   |
| Toshiba                 | 3         | 0.19%   |
| SLD                     | 3         | 0.19%   |
| Hitachi                 | 3         | 0.19%   |
| FOX                     | 3         | 0.19%   |
| CSO                     | 3         | 0.19%   |
| ASUSTek Computer        | 3         | 0.19%   |
| Vizio                   | 2         | 0.13%   |
| ViewSonic               | 2         | 0.13%   |
| Unknown (AAA)           | 2         | 0.13%   |
| TMX                     | 2         | 0.13%   |
| LGD                     | 2         | 0.13%   |
| KDC                     | 2         | 0.13%   |
| HUAWEI                  | 2         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 18        | 1.14%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                     | 17        | 1.08%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 14        | 0.89%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 13        | 0.82%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 13        | 0.82%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 13        | 0.82%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.76%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 12        | 0.76%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 11        | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 10        | 0.63%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 10        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 10        | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 10        | 0.63%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 10        | 0.63%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 10        | 0.63%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 9         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 9         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 8         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 8         | 0.51%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 8         | 0.51%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 8         | 0.51%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 7         | 0.44%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 7         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch          | 7         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 7         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch          | 7         | 0.44%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 7         | 0.44%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.44%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 7         | 0.44%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch     | 6         | 0.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 6         | 0.38%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 6         | 0.38%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 6         | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 6         | 0.38%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 6         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 6         | 0.38%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 6         | 0.38%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 6         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 737       | 49.4%   |
| 1920x1080 (FHD)    | 409       | 27.41%  |
| 1280x800 (WXGA)    | 92        | 6.17%   |
| 1600x900 (HD+)     | 44        | 2.95%   |
| 3840x2160 (4K)     | 26        | 1.74%   |
| 1024x600           | 26        | 1.74%   |
| 1440x900 (WXGA+)   | 25        | 1.68%   |
| 2160x1440          | 15        | 1.01%   |
| 2560x1440 (QHD)    | 12        | 0.8%    |
| 2560x1600          | 11        | 0.74%   |
| 1920x1200 (WUXGA)  | 9         | 0.6%    |
| 1360x768           | 9         | 0.6%    |
| 2560x1080          | 8         | 0.54%   |
| 1280x1024 (SXGA)   | 8         | 0.54%   |
| 3440x1440          | 7         | 0.47%   |
| 1680x1050 (WSXGA+) | 7         | 0.47%   |
| 800x1280           | 6         | 0.4%    |
| 1024x768 (XGA)     | 6         | 0.4%    |
| 3000x2000          | 5         | 0.34%   |
| 2880x1800          | 5         | 0.34%   |
| 3200x1800 (QHD+)   | 4         | 0.27%   |
| 2520x1680          | 3         | 0.2%    |
| Unknown            | 3         | 0.2%    |
| 3840x2400          | 2         | 0.13%   |
| 2288x1287          | 2         | 0.13%   |
| 1600x1200          | 2         | 0.13%   |
| 1280x768           | 2         | 0.13%   |
| 3840x1080          | 1         | 0.07%   |
| 3600x1080          | 1         | 0.07%   |
| 3280x1080          | 1         | 0.07%   |
| 1920x540           | 1         | 0.07%   |
| 1400x1050          | 1         | 0.07%   |
| 1366x912           | 1         | 0.07%   |
| 1152x864           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 586       | 37.42%  |
| 13      | 301       | 19.22%  |
| 14      | 248       | 15.84%  |
| 11      | 59        | 3.77%   |
| 17      | 45        | 2.87%   |
| 21      | 39        | 2.49%   |
| 12      | 31        | 1.98%   |
| 24      | 29        | 1.85%   |
| 23      | 25        | 1.6%    |
| 10      | 24        | 1.53%   |
| 27      | 20        | 1.28%   |
| 16      | 20        | 1.28%   |
| 18      | 19        | 1.21%   |
| Unknown | 15        | 0.96%   |
| 34      | 14        | 0.89%   |
| 20      | 14        | 0.89%   |
| 31      | 11        | 0.7%    |
| 19      | 11        | 0.7%    |
| 84      | 9         | 0.57%   |
| 22      | 5         | 0.32%   |
| 7       | 5         | 0.32%   |
| 72      | 4         | 0.26%   |
| 54      | 4         | 0.26%   |
| 40      | 4         | 0.26%   |
| 32      | 4         | 0.26%   |
| 142     | 2         | 0.13%   |
| 42      | 2         | 0.13%   |
| 39      | 2         | 0.13%   |
| 8       | 2         | 0.13%   |
| 74      | 1         | 0.06%   |
| 63      | 1         | 0.06%   |
| 55      | 1         | 0.06%   |
| 52      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 35      | 1         | 0.06%   |
| 29      | 1         | 0.06%   |
| 26      | 1         | 0.06%   |
| 25      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1017      | 65.4%   |
| 201-300        | 219       | 14.08%  |
| 401-500        | 86        | 5.53%   |
| 501-600        | 73        | 4.69%   |
| 351-400        | 71        | 4.57%   |
| 701-800        | 18        | 1.16%   |
| Unknown        | 15        | 0.96%   |
| 1501-2000      | 14        | 0.9%    |
| 601-700        | 13        | 0.84%   |
| 1001-1500      | 9         | 0.58%   |
| 801-900        | 8         | 0.51%   |
| 1-100          | 6         | 0.39%   |
| More than 2000 | 2         | 0.13%   |
| 101-200        | 2         | 0.13%   |
| 901-1000       | 2         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1173      | 83.61%  |
| 16/10   | 153       | 10.91%  |
| 3/2     | 27        | 1.92%   |
| 21/9    | 15        | 1.07%   |
| 4/3     | 11        | 0.78%   |
| Unknown | 10        | 0.71%   |
| 5/4     | 6         | 0.43%   |
| 0.67    | 5         | 0.36%   |
| 1.00    | 2         | 0.14%   |
| 6/5     | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 598       | 38.26%  |
| 81-90          | 492       | 31.48%  |
| 201-250        | 81        | 5.18%   |
| 51-60          | 59        | 3.77%   |
| 71-80          | 58        | 3.71%   |
| 151-200        | 32        | 2.05%   |
| 351-500        | 30        | 1.92%   |
| 121-130        | 30        | 1.92%   |
| 61-70          | 29        | 1.86%   |
| 41-50          | 24        | 1.54%   |
| More than 1000 | 23        | 1.47%   |
| 141-150        | 23        | 1.47%   |
| 301-350        | 21        | 1.34%   |
| Unknown        | 15        | 0.96%   |
| 131-140        | 11        | 0.7%    |
| 501-1000       | 10        | 0.64%   |
| 1-40           | 8         | 0.51%   |
| 251-300        | 8         | 0.51%   |
| 111-120        | 7         | 0.45%   |
| 91-100         | 4         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 757       | 49.25%  |
| 121-160       | 432       | 28.11%  |
| 51-100        | 223       | 14.51%  |
| 161-240       | 61        | 3.97%   |
| 1-50          | 26        | 1.69%   |
| More than 240 | 23        | 1.5%    |
| Unknown       | 15        | 0.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1157      | 80.97%  |
| 2     | 220       | 15.4%   |
| 0     | 30        | 2.1%    |
| 3     | 22        | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 799       | 37.13%  |
| Intel                                  | 546       | 25.37%  |
| Qualcomm Atheros                       | 341       | 15.85%  |
| Broadcom                               | 197       | 9.15%   |
| Broadcom Limited                       | 43        | 2%      |
| Ralink                                 | 39        | 1.81%   |
| Marvell Technology Group               | 35        | 1.63%   |
| TP-Link                                | 19        | 0.88%   |
| Ralink Technology                      | 19        | 0.88%   |
| MediaTek                               | 17        | 0.79%   |
| Nvidia                                 | 16        | 0.74%   |
| ASIX Electronics                       | 12        | 0.56%   |
| Huawei Technologies                    | 9         | 0.42%   |
| DisplayLink                            | 6         | 0.28%   |
| Qualcomm Atheros Communications        | 5         | 0.23%   |
| Xiaomi                                 | 4         | 0.19%   |
| Spreadtrum Communications              | 4         | 0.19%   |
| Motorola PCS                           | 4         | 0.19%   |
| ICS Advent                             | 4         | 0.19%   |
| Samsung Electronics                    | 3         | 0.14%   |
| Lenovo                                 | 3         | 0.14%   |
| Qualcomm                               | 2         | 0.09%   |
| JMicron Technology                     | 2         | 0.09%   |
| Google                                 | 2         | 0.09%   |
| Dell                                   | 2         | 0.09%   |
| D-Link                                 | 2         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.05%   |
| T & A Mobile Phones                    | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.05%   |
| Shenzhen Goodix Technology             | 1         | 0.05%   |
| OPPO Electronics                       | 1         | 0.05%   |
| OpenMoko                               | 1         | 0.05%   |
| NIIMBOT                                | 1         | 0.05%   |
| NetGear                                | 1         | 0.05%   |
| Mercucys                               | 1         | 0.05%   |
| Linksys                                | 1         | 0.05%   |
| LG Electronics                         | 1         | 0.05%   |
| Lab126                                 | 1         | 0.05%   |
| Hewlett-Packard                        | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 395       | 14.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 257       | 9.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 80        | 3%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 63        | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 53        | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 51        | 1.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 48        | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 47        | 1.76%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 44        | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 44        | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 43        | 1.61%   |
| Intel Wi-Fi 6 AX200                                               | 43        | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                     | 37        | 1.39%   |
| Intel Wireless 7265                                               | 35        | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 32        | 1.2%    |
| Intel Wireless 8265 / 8275                                        | 31        | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 31        | 1.16%   |
| Intel Wireless 7260                                               | 29        | 1.09%   |
| Intel Wi-Fi 6 AX201                                               | 28        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 28        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 27        | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 0.97%   |
| Intel Wireless 8260                                               | 23        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 22        | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 21        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 21        | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 20        | 0.75%   |
| Intel Wireless 3160                                               | 20        | 0.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 20        | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 0.64%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 17        | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 16        | 0.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 16        | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 15        | 0.56%   |
| Intel Wireless 3165                                               | 15        | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 14        | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 14        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 510       | 35.49%  |
| Realtek Semiconductor                 | 337       | 23.45%  |
| Qualcomm Atheros                      | 289       | 20.11%  |
| Broadcom                              | 168       | 11.69%  |
| Ralink                                | 39        | 2.71%   |
| Broadcom Limited                      | 32        | 2.23%   |
| Ralink Technology                     | 19        | 1.32%   |
| TP-Link                               | 15        | 1.04%   |
| MediaTek                              | 14        | 0.97%   |
| Qualcomm Atheros Communications       | 5         | 0.35%   |
| Qualcomm                              | 2         | 0.14%   |
| D-Link                                | 2         | 0.14%   |
| NetGear                               | 1         | 0.07%   |
| Mercucys                              | 1         | 0.07%   |
| Dell                                  | 1         | 0.07%   |
| D-Link System                         | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 80        | 5.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 63        | 4.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 53        | 3.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 51        | 3.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 48        | 3.29%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 44        | 3.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 44        | 3.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 43        | 2.95%   |
| Intel Wi-Fi 6 AX200                                                     | 43        | 2.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 37        | 2.53%   |
| Intel Wireless 7265                                                     | 35        | 2.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 32        | 2.19%   |
| Intel Wireless 8265 / 8275                                              | 31        | 2.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 31        | 2.12%   |
| Intel Wireless 7260                                                     | 29        | 1.99%   |
| Intel Wi-Fi 6 AX201                                                     | 28        | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 28        | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 27        | 1.85%   |
| Intel Wireless 8260                                                     | 23        | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 22        | 1.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 21        | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 21        | 1.44%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 20        | 1.37%   |
| Intel Wireless 3160                                                     | 20        | 1.37%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 20        | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 1.16%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 17        | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 16        | 1.1%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 16        | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 15        | 1.03%   |
| Intel Wireless 3165                                                     | 15        | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 14        | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 14        | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 0.89%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 12        | 0.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.82%   |
| Intel WiFi Link 5100                                                    | 12        | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.82%   |
| Intel Centrino Ultimate-N 6300                                          | 12        | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 689       | 58.14%  |
| Intel                                  | 201       | 16.96%  |
| Qualcomm Atheros                       | 107       | 9.03%   |
| Broadcom                               | 63        | 5.32%   |
| Marvell Technology Group               | 35        | 2.95%   |
| Nvidia                                 | 16        | 1.35%   |
| ASIX Electronics                       | 12        | 1.01%   |
| Broadcom Limited                       | 11        | 0.93%   |
| Huawei Technologies                    | 8         | 0.68%   |
| DisplayLink                            | 6         | 0.51%   |
| Xiaomi                                 | 4         | 0.34%   |
| TP-Link                                | 4         | 0.34%   |
| Spreadtrum Communications              | 4         | 0.34%   |
| ICS Advent                             | 4         | 0.34%   |
| MediaTek                               | 3         | 0.25%   |
| Lenovo                                 | 3         | 0.25%   |
| JMicron Technology                     | 2         | 0.17%   |
| Google                                 | 2         | 0.17%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.08%   |
| T & A Mobile Phones                    | 1         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.08%   |
| Samsung Electronics                    | 1         | 0.08%   |
| OPPO Electronics                       | 1         | 0.08%   |
| Motorola PCS                           | 1         | 0.08%   |
| Linksys                                | 1         | 0.08%   |
| LG Electronics                         | 1         | 0.08%   |
| Lab126                                 | 1         | 0.08%   |
| Foxconn / Hon Hai                      | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 395       | 33.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 257       | 21.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 47        | 3.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 26        | 2.18%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 19        | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 18        | 1.51%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 1.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 14        | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                                          | 13        | 1.09%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 12        | 1.01%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 12        | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                                          | 12        | 1.01%   |
| Intel 82577LM Gigabit Network Connection                                       | 12        | 1.01%   |
| Intel 82567LM Gigabit Network Connection                                       | 12        | 1.01%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 11        | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 11        | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 10        | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 9         | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 9         | 0.75%   |
| Intel Ethernet Connection I217-LM                                              | 9         | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 9         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 8         | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 8         | 0.67%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 7         | 0.59%   |
| Nvidia MCP67 Ethernet                                                          | 7         | 0.59%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                           | 7         | 0.59%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                                          | 7         | 0.59%   |
| Huawei ANE-LX1                                                                 | 7         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 6         | 0.5%    |
| Nvidia MCP79 Ethernet                                                          | 5         | 0.42%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.42%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 5         | 0.42%   |
| Intel Ethernet Connection I219-V                                               | 5         | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                                          | 5         | 0.42%   |
| Intel Ethernet Connection (10) I219-V                                          | 5         | 0.42%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 5         | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1372      | 54.19%  |
| Ethernet | 1144      | 45.18%  |
| Modem    | 11        | 0.43%   |
| Unknown  | 5         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1119      | 75.35%  |
| Ethernet | 365       | 24.58%  |
| Unknown  | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1063      | 76.15%  |
| 1     | 303       | 21.7%   |
| 0     | 25        | 1.79%   |
| 3     | 5         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 996       | 69.75%  |
| Yes  | 432       | 30.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 364       | 34.9%   |
| Realtek Semiconductor           | 201       | 19.27%  |
| Qualcomm Atheros Communications | 107       | 10.26%  |
| Broadcom                        | 77        | 7.38%   |
| Apple                           | 47        | 4.51%   |
| Lite-On Technology              | 46        | 4.41%   |
| IMC Networks                    | 40        | 3.84%   |
| Foxconn / Hon Hai               | 38        | 3.64%   |
| Dell                            | 24        | 2.3%    |
| Hewlett-Packard                 | 21        | 2.01%   |
| Realtek                         | 19        | 1.82%   |
| Toshiba                         | 18        | 1.73%   |
| Ralink                          | 16        | 1.53%   |
| Cambridge Silicon Radio         | 8         | 0.77%   |
| Ralink Technology               | 7         | 0.67%   |
| Alps Electric                   | 4         | 0.38%   |
| Foxconn International           | 3         | 0.29%   |
| Integrated System Solution      | 1         | 0.1%    |
| Chicony Electronics             | 1         | 0.1%    |
| ASUSTek Computer                | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 147       | 14.07%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 85        | 8.13%   |
| Realtek Bluetooth Radio                                                             | 85        | 8.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 80        | 7.66%   |
| Intel AX201 Bluetooth                                                               | 55        | 5.26%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 53        | 5.07%   |
| Intel AX200 Bluetooth                                                               | 42        | 4.02%   |
| Apple Bluetooth Host Controller                                                     | 22        | 2.11%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 20        | 1.91%   |
| Realtek Bluetooth Radio                                                             | 19        | 1.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 19        | 1.82%   |
| Intel Bluetooth Device                                                              | 18        | 1.72%   |
| IMC Networks Bluetooth Radio                                                        | 18        | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 17        | 1.63%   |
| Ralink RT3290 Bluetooth                                                             | 16        | 1.53%   |
| Apple Bluetooth USB Host Controller                                                 | 16        | 1.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 15        | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 15        | 1.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 14        | 1.34%   |
| Realtek RTL8723B Bluetooth                                                          | 13        | 1.24%   |
| Lite-On Bluetooth Device                                                            | 13        | 1.24%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 13        | 1.24%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 11        | 1.05%   |
| Realtek RTL8821A Bluetooth                                                          | 10        | 0.96%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 10        | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 10        | 0.96%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 10        | 0.96%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 0.96%   |
| IMC Networks Wireless_Device                                                        | 8         | 0.77%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 8         | 0.77%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 8         | 0.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 0.77%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 7         | 0.67%   |
| IMC Networks Bluetooth Device                                                       | 6         | 0.57%   |
| Dell Wireless 355 Bluetooth                                                         | 6         | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 6         | 0.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 5         | 0.48%   |
| Broadcom HP Portable Bumble Bee                                                     | 5         | 0.48%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 5         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1028      | 63.54%  |
| AMD                                             | 351       | 21.69%  |
| Nvidia                                          | 157       | 9.7%    |
| Logitech                                        | 8         | 0.49%   |
| Texas Instruments                               | 7         | 0.43%   |
| C-Media Electronics                             | 7         | 0.43%   |
| Generalplus Technology                          | 6         | 0.37%   |
| Realtek Semiconductor                           | 5         | 0.31%   |
| Plantronics                                     | 5         | 0.31%   |
| Lenovo                                          | 5         | 0.31%   |
| Tenx Technology                                 | 4         | 0.25%   |
| Kingston Technology                             | 4         | 0.25%   |
| GN Netcom                                       | 4         | 0.25%   |
| Creative Technology                             | 3         | 0.19%   |
| Syntek                                          | 2         | 0.12%   |
| Synaptics                                       | 2         | 0.12%   |
| Samson Technologies                             | 2         | 0.12%   |
| JMTek                                           | 2         | 0.12%   |
| ASUSTek Computer                                | 2         | 0.12%   |
| Apple                                           | 2         | 0.12%   |
| Yamaha                                          | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.06%   |
| Sony                                            | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.06%   |
| Sennheiser Communications                       | 1         | 0.06%   |
| Samsung Electronics                             | 1         | 0.06%   |
| Razer USA                                       | 1         | 0.06%   |
| M-Audio                                         | 1         | 0.06%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.06%   |
| DisplayLink                                     | 1         | 0.06%   |
| DCMT Technology                                 | 1         | 0.06%   |
| Cambridge Audio                                 | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 125       | 6.14%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 123       | 6.04%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 113       | 5.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 85        | 4.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 76        | 3.73%   |
| AMD FCH Azalia Controller                                                                         | 74        | 3.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 65        | 3.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 60        | 2.95%   |
| Intel 8 Series HD Audio Controller                                                                | 60        | 2.95%   |
| AMD Kabini HDMI/DP Audio                                                                          | 54        | 2.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 53        | 2.6%    |
| Intel Broadwell-U Audio Controller                                                                | 53        | 2.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 52        | 2.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 50        | 2.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 49        | 2.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 49        | 2.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 45        | 2.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 44        | 2.16%   |
| AMD High Definition Audio Controller                                                              | 43        | 2.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 42        | 2.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 40        | 1.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 36        | 1.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 35        | 1.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 35        | 1.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 31        | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 30        | 1.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 26        | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24        | 1.18%   |
| Intel Comet Lake PCH cAVS                                                                         | 23        | 1.13%   |
| AMD Trinity HDMI Audio Controller                                                                 | 23        | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 21        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 0.88%   |
| Intel CM238 HD Audio Controller                                                                   | 18        | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 0.83%   |
| AMD Wrestler HDMI Audio                                                                           | 17        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 16        | 0.79%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 13        | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 10        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 236       | 28.13%  |
| SK hynix                                         | 183       | 21.81%  |
| Kingston                                         | 110       | 13.11%  |
| Micron Technology                                | 109       | 12.99%  |
| Unknown                                          | 59        | 7.03%   |
| A-DATA Technology                                | 36        | 4.29%   |
| Ramaxel Technology                               | 27        | 3.22%   |
| Elpida                                           | 15        | 1.79%   |
| Unknown (ABCD)                                   | 11        | 1.31%   |
| Nanya Technology                                 | 11        | 1.31%   |
| Crucial                                          | 10        | 1.19%   |
| Corsair                                          | 6         | 0.72%   |
| Team                                             | 3         | 0.36%   |
| Qimonda                                          | 3         | 0.36%   |
| PNY                                              | 3         | 0.36%   |
| Transcend                                        | 2         | 0.24%   |
| Patriot                                          | 2         | 0.24%   |
| ChangXin Memory                                  | 2         | 0.24%   |
| Unknown                                          | 2         | 0.24%   |
| Unknown (0x8AF1)                                 | 1         | 0.12%   |
| Unknown (0x4D342037305435363633515A332D43453620) | 1         | 0.12%   |
| Timetec                                          | 1         | 0.12%   |
| SHARETRONIC                                      | 1         | 0.12%   |
| Goldkey                                          | 1         | 0.12%   |
| G.Skill                                          | 1         | 0.12%   |
| Avant                                            | 1         | 0.12%   |
| 3235CB0010E4                                     | 1         | 0.12%   |
| 0161000080AD                                     | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 2.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 1.66%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 1.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 12        | 1.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 11        | 1.22%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 1.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.1%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 1.1%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 10        | 1.1%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.99%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 7         | 0.77%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.77%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.77%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.77%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 7         | 0.77%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 7         | 0.77%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 6         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.66%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 5         | 0.55%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.55%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.55%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.55%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.55%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 5         | 0.55%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 5         | 0.55%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 5         | 0.55%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 5         | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 4         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 4         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 4         | 0.44%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 4         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 285       | 41.79%  |
| DDR4    | 276       | 40.47%  |
| DDR2    | 44        | 6.45%   |
| LPDDR4  | 27        | 3.96%   |
| LPDDR3  | 21        | 3.08%   |
| SDRAM   | 12        | 1.76%   |
| DDR     | 7         | 1.03%   |
| Unknown | 5         | 0.73%   |
| LPDDR5  | 2         | 0.29%   |
| DDR5    | 2         | 0.29%   |
| RAM     | 1         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 609       | 89.3%   |
| Row Of Chips | 68        | 9.97%   |
| Chip         | 4         | 0.59%   |
| Unknown      | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 296       | 37.28%  |
| 8192  | 287       | 36.15%  |
| 2048  | 118       | 14.86%  |
| 16384 | 51        | 6.42%   |
| 1024  | 30        | 3.78%   |
| 32768 | 8         | 1.01%   |
| 512   | 3         | 0.38%   |
| 256   | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 219       | 28.89%  |
| 2667    | 144       | 19%     |
| 3200    | 81        | 10.69%  |
| 2400    | 50        | 6.6%    |
| 2133    | 41        | 5.41%   |
| 1334    | 40        | 5.28%   |
| 1333    | 34        | 4.49%   |
| 667     | 27        | 3.56%   |
| 3266    | 25        | 3.3%    |
| Unknown | 21        | 2.77%   |
| 4267    | 12        | 1.58%   |
| 800     | 12        | 1.58%   |
| 2048    | 8         | 1.06%   |
| 1067    | 7         | 0.92%   |
| 1867    | 6         | 0.79%   |
| 975     | 6         | 0.79%   |
| 1066    | 5         | 0.66%   |
| 4199    | 4         | 0.53%   |
| 533     | 4         | 0.53%   |
| 8400    | 3         | 0.4%    |
| 6400    | 2         | 0.26%   |
| 4800    | 2         | 0.26%   |
| 3733    | 2         | 0.26%   |
| 2933    | 1         | 0.13%   |
| 1866    | 1         | 0.13%   |
| 400     | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Seiko Epson            | 3         | 21.43%  |
| Samsung Electronics    | 2         | 14.29%  |
| Hewlett-Packard        | 2         | 14.29%  |
| Canon                  | 2         | 14.29%  |
| Brother Industries     | 2         | 14.29%  |
| TSC Auto ID Technology | 1         | 7.14%   |
| Kyocera                | 1         | 7.14%   |
| BIXOLON                | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP DeskJet 2300 series  | 2         | 14.29%  |
| TSC Auto ID Printer     | 1         | 7.14%   |
| Seiko Epson L555 Series | 1         | 7.14%   |
| Seiko Epson L210 Series | 1         | 7.14%   |
| Seiko Epson L120 Series | 1         | 7.14%   |
| Samsung ML-1660 Series  | 1         | 7.14%   |
| Samsung M2020 Series    | 1         | 7.14%   |
| Kyocera FS-1116MFP      | 1         | 7.14%   |
| Canon iP2600 series     | 1         | 7.14%   |
| Canon G2010 series      | 1         | 7.14%   |
| Brother MFC-J470DW      | 1         | 7.14%   |
| Brother DCP-1510        | 1         | 7.14%   |
| BIXOLON SRP-350plusIII  | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| HP ScanJet 5590 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 302       | 23.7%   |
| IMC Networks                           | 129       | 10.13%  |
| Microdia                               | 122       | 9.58%   |
| Realtek Semiconductor                  | 87        | 6.83%   |
| Cheng Uei Precision Industry (Foxlink) | 74        | 5.81%   |
| Sunplus Innovation Technology          | 67        | 5.26%   |
| Suyin                                  | 65        | 5.1%    |
| Quanta                                 | 54        | 4.24%   |
| Bison Electronics                      | 45        | 3.53%   |
| Syntek                                 | 44        | 3.45%   |
| Acer                                   | 38        | 2.98%   |
| Apple                                  | 37        | 2.9%    |
| Lite-On Technology                     | 36        | 2.83%   |
| Ricoh                                  | 21        | 1.65%   |
| Silicon Motion                         | 19        | 1.49%   |
| Importek                               | 16        | 1.26%   |
| Alcor Micro                            | 14        | 1.1%    |
| Logitech                               | 13        | 1.02%   |
| Luxvisions Innotech Limited            | 8         | 0.63%   |
| ALi                                    | 8         | 0.63%   |
| Y Media                                | 7         | 0.55%   |
| Primax Electronics                     | 7         | 0.55%   |
| OmniVision Technologies                | 6         | 0.47%   |
| Sonix Technology                       | 5         | 0.39%   |
| Genesys Logic                          | 4         | 0.31%   |
| Generalplus Technology                 | 4         | 0.31%   |
| Microsoft                              | 3         | 0.24%   |
| MacroSilicon                           | 3         | 0.24%   |
| Lenovo                                 | 3         | 0.24%   |
| icSpring                               | 3         | 0.24%   |
| HRY                                    | 3         | 0.24%   |
| Z-Star Microelectronics                | 2         | 0.16%   |
| Tobii Technology AB                    | 2         | 0.16%   |
| Sunplus Technology                     | 2         | 0.16%   |
| Samsung Electronics                    | 2         | 0.16%   |
| Jieli Technology                       | 2         | 0.16%   |
| DigiTech                               | 2         | 0.16%   |
| Novatek Microelectronics               | 1         | 0.08%   |
| Nebraska Furniture Mart                | 1         | 0.08%   |
| LG Electronics                         | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 43        | 3.36%   |
| Microdia Integrated_Webcam_HD                                  | 39        | 3.05%   |
| Chicony HD WebCam                                              | 34        | 2.66%   |
| IMC Networks Integrated Camera                                 | 27        | 2.11%   |
| IMC Networks HD Camera                                         | 23        | 1.8%    |
| Realtek Integrated_Webcam_HD                                   | 22        | 1.72%   |
| Chicony HP Webcam                                              | 21        | 1.64%   |
| Sunplus Integrated_Webcam_HD                                   | 20        | 1.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 19        | 1.49%   |
| Bison Integrated Camera                                        | 18        | 1.41%   |
| Apple FaceTime HD Camera                                       | 18        | 1.41%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 17        | 1.33%   |
| Syntek Lenovo EasyCamera                                       | 15        | 1.17%   |
| Chicony HP TrueVision HD Camera                                | 15        | 1.17%   |
| Chicony HP Truevision HD                                       | 15        | 1.17%   |
| Microdia Integrated Webcam                                     | 14        | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera               | 14        | 1.09%   |
| Quanta HP Webcam                                               | 13        | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 13        | 1.02%   |
| Sunplus HD WebCam                                              | 12        | 0.94%   |
| IMC Networks EasyCamera                                        | 12        | 0.94%   |
| Chicony HP Wide Vision HD Camera                               | 12        | 0.94%   |
| Acer Integrated Camera                                         | 12        | 0.94%   |
| Syntek Integrated Camera                                       | 11        | 0.86%   |
| Lite-On HP Wide Vision HD Camera                               | 11        | 0.86%   |
| Suyin HP Truevision HD                                         | 10        | 0.78%   |
| Microdia Lenovo EasyCamera                                     | 10        | 0.78%   |
| Chicony USB 2.0 Camera                                         | 10        | 0.78%   |
| Chicony TOSHIBA Web Camera - HD                                | 10        | 0.78%   |
| Chicony HP HD Camera                                           | 10        | 0.78%   |
| Acer Lenovo EasyCamera                                         | 10        | 0.78%   |
| Chicony Lenovo EasyCamera                                      | 9         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 9         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 9         | 0.7%    |
| Bison EasyCamera                                               | 9         | 0.7%    |
| Realtek HP Truevision HD                                       | 8         | 0.63%   |
| Realtek HD WebCam                                              | 8         | 0.63%   |
| Quanta HP TrueVision HD Camera                                 | 8         | 0.63%   |
| Microdia Sonix USB 2.0 Camera                                  | 8         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 8         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 83        | 36.56%  |
| Shenzhen Goodix Technology         | 48        | 21.15%  |
| Synaptics                          | 35        | 15.42%  |
| AuthenTec                          | 21        | 9.25%   |
| Upek                               | 16        | 7.05%   |
| Elan Microelectronics              | 7         | 3.08%   |
| STMicroelectronics                 | 5         | 2.2%    |
| Focal-systems.Corp                 | 5         | 2.2%    |
| LighTuning Technology              | 3         | 1.32%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.88%   |
| Suprema                            | 1         | 0.44%   |
| Samsung Electronics                | 1         | 0.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 43        | 18.94%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 8.37%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 6.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 6.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 4.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 4.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 4.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 4.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 4.41%   |
| Validity Sensors VFS491                                                    | 5         | 2.2%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.2%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 2.2%    |
| STMicroelectronics Fingerprint Reader                                      | 5         | 2.2%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 2.2%    |
| AuthenTec AES2810                                                          | 5         | 2.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.76%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.76%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.76%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.32%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.32%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.32%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.32%   |
| AuthenTec AES1600                                                          | 3         | 1.32%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.88%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 0.88%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.88%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.88%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.88%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.88%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.88%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.44%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.44%   |
| Synaptics WBDI                                                             | 1         | 0.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.44%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader                           | 1         | 0.44%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.44%   |
| Samsung Fingerprint Device                                                 | 1         | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 39        | 60.94%  |
| Alcor Micro           | 11        | 17.19%  |
| Upek                  | 7         | 10.94%  |
| Lenovo                | 6         | 9.38%   |
| Gemalto (was Gemplus) | 1         | 1.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 23.44%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 18.75%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 17.19%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 10.94%  |
| Lenovo Integrated Smart Card Reader                                          | 6         | 9.38%   |
| Broadcom 58200                                                               | 6         | 9.38%   |
| Broadcom 5880                                                                | 5         | 7.81%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 912       | 63.96%  |
| 1     | 426       | 29.87%  |
| 2     | 77        | 5.4%    |
| 3     | 7         | 0.49%   |
| 5     | 2         | 0.14%   |
| 7     | 1         | 0.07%   |
| 6     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 224       | 36.78%  |
| Graphics card            | 98        | 16.09%  |
| Net/wireless             | 87        | 14.29%  |
| Chipcard                 | 61        | 10.02%  |
| Multimedia controller    | 39        | 6.4%    |
| Camera                   | 22        | 3.61%   |
| Bluetooth                | 21        | 3.45%   |
| Communication controller | 12        | 1.97%   |
| Storage                  | 10        | 1.64%   |
| Net/ethernet             | 10        | 1.64%   |
| Sound                    | 7         | 1.15%   |
| Card reader              | 7         | 1.15%   |
| Modem                    | 5         | 0.82%   |
| Network                  | 3         | 0.49%   |
| Storage/ide              | 1         | 0.16%   |
| Firewire controller      | 1         | 0.16%   |
| Dvb card                 | 1         | 0.16%   |

