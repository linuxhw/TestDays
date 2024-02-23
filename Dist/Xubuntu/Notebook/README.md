Xubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Xubuntu.

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

Total: 3614

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Modern 15 A10M              | [22f3c2e58e](https://linux-hardware.org/?probe=22f3c2e58e) | Feb 02, 2024 |
| Acer          | NC-F5-771G-72XY             | [2f4c6fbadb](https://linux-hardware.org/?probe=2f4c6fbadb) | Feb 02, 2024 |
| Apple         | MacBookPro5,4               | [c22226fe6f](https://linux-hardware.org/?probe=c22226fe6f) | Feb 01, 2024 |
| HP            | EliteBook 840 G1            | [920b1ecb34](https://linux-hardware.org/?probe=920b1ecb34) | Jan 31, 2024 |
| Acer          | Aspire 5735                 | [365fd9fe4d](https://linux-hardware.org/?probe=365fd9fe4d) | Jan 31, 2024 |
| Acer          | Aspire 5735                 | [bed38c72c8](https://linux-hardware.org/?probe=bed38c72c8) | Jan 31, 2024 |
| HP            | Pavilion g6                 | [7f9863aaa2](https://linux-hardware.org/?probe=7f9863aaa2) | Jan 31, 2024 |
| Lenovo        | ThinkPad T570 20HAS0NU00    | [39f3b9fb56](https://linux-hardware.org/?probe=39f3b9fb56) | Jan 30, 2024 |
| Dell          | Inspiron 1525               | [ad26dae776](https://linux-hardware.org/?probe=ad26dae776) | Jan 30, 2024 |
| Dell          | Inspiron 1525               | [bc4394a85f](https://linux-hardware.org/?probe=bc4394a85f) | Jan 30, 2024 |
| Dell          | Latitude 5510               | [4abbee3451](https://linux-hardware.org/?probe=4abbee3451) | Jan 30, 2024 |
| HP            | EliteBook 860 16 inch G1... | [737d54004b](https://linux-hardware.org/?probe=737d54004b) | Jan 29, 2024 |
| Dell          | Latitude 5511               | [40fad497db](https://linux-hardware.org/?probe=40fad497db) | Jan 29, 2024 |
| Lenovo        | V560                        | [a0dbd66d53](https://linux-hardware.org/?probe=a0dbd66d53) | Jan 28, 2024 |
| ASUSTek       | X205TA                      | [83899dcb83](https://linux-hardware.org/?probe=83899dcb83) | Jan 27, 2024 |
| Lenovo        | ThinkPad T400 6474AW6       | [0ddfcaf599](https://linux-hardware.org/?probe=0ddfcaf599) | Jan 27, 2024 |
| Acer          | Aspire A315-58              | [c85674acbd](https://linux-hardware.org/?probe=c85674acbd) | Jan 26, 2024 |
| Toshiba       | Satellite L300              | [127697d4f1](https://linux-hardware.org/?probe=127697d4f1) | Jan 26, 2024 |
| Toshiba       | Satellite L300              | [63be13a245](https://linux-hardware.org/?probe=63be13a245) | Jan 26, 2024 |
| PC Special... | NH5x_7xDPx                  | [0f28a5d513](https://linux-hardware.org/?probe=0f28a5d513) | Jan 26, 2024 |
| Apple         | MacBook5,1                  | [51346a4084](https://linux-hardware.org/?probe=51346a4084) | Jan 25, 2024 |
| Dell          | Latitude 7340               | [880054b099](https://linux-hardware.org/?probe=880054b099) | Jan 25, 2024 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [5a5ec0016f](https://linux-hardware.org/?probe=5a5ec0016f) | Jan 24, 2024 |
| Dell          | Inspiron 5567               | [dc061193f2](https://linux-hardware.org/?probe=dc061193f2) | Jan 22, 2024 |
| HP            | Pavilion dv6                | [ac628c20c7](https://linux-hardware.org/?probe=ac628c20c7) | Jan 22, 2024 |
| HP            | Pavilion dv6                | [6d29e8c44e](https://linux-hardware.org/?probe=6d29e8c44e) | Jan 22, 2024 |
| MSI           | GF63 Thin 11UC              | [b6fa224856](https://linux-hardware.org/?probe=b6fa224856) | Jan 21, 2024 |
| ASUSTek       | T100HAN                     | [02f115dc2a](https://linux-hardware.org/?probe=02f115dc2a) | Jan 21, 2024 |
| ASUSTek       | K55VM                       | [a684c7f5fc](https://linux-hardware.org/?probe=a684c7f5fc) | Jan 19, 2024 |
| Lenovo        | ThinkPad X240 20AMS00100    | [4b39b1cbe0](https://linux-hardware.org/?probe=4b39b1cbe0) | Jan 17, 2024 |
| HP            | Compaq Presario CQ60        | [fd48d4e0d2](https://linux-hardware.org/?probe=fd48d4e0d2) | Jan 15, 2024 |
| MSI           | GF63 Thin 11UC              | [6d2801d1d8](https://linux-hardware.org/?probe=6d2801d1d8) | Jan 14, 2024 |
| Lenovo        | G500 20236                  | [5dacf75c7d](https://linux-hardware.org/?probe=5dacf75c7d) | Jan 12, 2024 |
| ASUSTek       | K55VM                       | [99003258ce](https://linux-hardware.org/?probe=99003258ce) | Jan 11, 2024 |
| Gigazone      | X107(B-B)                   | [a72cbb0097](https://linux-hardware.org/?probe=a72cbb0097) | Jan 10, 2024 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [ce397f675e](https://linux-hardware.org/?probe=ce397f675e) | Jan 10, 2024 |
| Acer          | Swift SF314-43              | [60423ae46b](https://linux-hardware.org/?probe=60423ae46b) | Jan 10, 2024 |
| Dell          | Inspiron 14-3452            | [0e47261be0](https://linux-hardware.org/?probe=0e47261be0) | Jan 09, 2024 |
| Gigazone      | X107(B-B)                   | [54085fcb32](https://linux-hardware.org/?probe=54085fcb32) | Jan 09, 2024 |
| Dell          | Inspiron 14-3452            | [1834cfc875](https://linux-hardware.org/?probe=1834cfc875) | Jan 09, 2024 |
| Apple         | MacBook5,2                  | [2ed16f6a80](https://linux-hardware.org/?probe=2ed16f6a80) | Jan 07, 2024 |
| Lenovo        | IdeaPad 510S-13ISK 80SJ     | [90fe273da6](https://linux-hardware.org/?probe=90fe273da6) | Jan 06, 2024 |
| Dell          | Latitude E5530 non-vPro     | [40b853c9b9](https://linux-hardware.org/?probe=40b853c9b9) | Jan 06, 2024 |
| Dell          | Inspiron 1501               | [65d521ef7c](https://linux-hardware.org/?probe=65d521ef7c) | Jan 06, 2024 |
| Dell          | Latitude E5530 non-vPro     | [d138fd288d](https://linux-hardware.org/?probe=d138fd288d) | Jan 06, 2024 |
| Acer          | Aspire A315-51              | [753ed1e625](https://linux-hardware.org/?probe=753ed1e625) | Jan 05, 2024 |
| Acer          | Aspire A517-52              | [610817c6c9](https://linux-hardware.org/?probe=610817c6c9) | Jan 05, 2024 |
| HP            | Pavilion dv7                | [dc31f854de](https://linux-hardware.org/?probe=dc31f854de) | Jan 04, 2024 |
| Dell          | Precision M6800             | [5049c54004](https://linux-hardware.org/?probe=5049c54004) | Jan 04, 2024 |
| ASUSTek       | X540SAA                     | [179249edef](https://linux-hardware.org/?probe=179249edef) | Jan 03, 2024 |
| Lenovo        | ThinkPad X260 20F5S0KE00    | [08d2a7a982](https://linux-hardware.org/?probe=08d2a7a982) | Jan 01, 2024 |
| Packard Be... | EasyNote MH35               | [2b8b39d335](https://linux-hardware.org/?probe=2b8b39d335) | Dec 27, 2023 |
| Dell          | Latitude 7390               | [8c74383dab](https://linux-hardware.org/?probe=8c74383dab) | Dec 27, 2023 |
| Dell          | Latitude 7390               | [889337bb1c](https://linux-hardware.org/?probe=889337bb1c) | Dec 27, 2023 |
| HP            | ProBook 6570b               | [61f91864e5](https://linux-hardware.org/?probe=61f91864e5) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [38b1c283b4](https://linux-hardware.org/?probe=38b1c283b4) | Dec 26, 2023 |
| Acer          | Aspire 5739G                | [6b4237a1ea](https://linux-hardware.org/?probe=6b4237a1ea) | Dec 26, 2023 |
| Acer          | Aspire 5739G                | [408e19e1f2](https://linux-hardware.org/?probe=408e19e1f2) | Dec 26, 2023 |
| HP            | Compaq nx7400 (RH609ES#A... | [6a6b1d3722](https://linux-hardware.org/?probe=6a6b1d3722) | Dec 26, 2023 |
| Acer          | Aspire V5-123               | [1a5a81980b](https://linux-hardware.org/?probe=1a5a81980b) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [14d453985d](https://linux-hardware.org/?probe=14d453985d) | Dec 25, 2023 |
| ASUSTek       | X201EP                      | [944a54b7f4](https://linux-hardware.org/?probe=944a54b7f4) | Dec 25, 2023 |
| eMachines     | E527                        | [cf5b096be7](https://linux-hardware.org/?probe=cf5b096be7) | Dec 22, 2023 |
| Dell          | Latitude E5510              | [92074a5231](https://linux-hardware.org/?probe=92074a5231) | Dec 22, 2023 |
| Lenovo        | Yoga 2 11 20332             | [16a8e6f875](https://linux-hardware.org/?probe=16a8e6f875) | Dec 21, 2023 |
| Sony          | VGN-NW270F                  | [eee640a54d](https://linux-hardware.org/?probe=eee640a54d) | Dec 20, 2023 |
| HP            | Pavilion dv6                | [4cc379dfbd](https://linux-hardware.org/?probe=4cc379dfbd) | Dec 19, 2023 |
| HP            | Notebook                    | [31d6fc4280](https://linux-hardware.org/?probe=31d6fc4280) | Dec 19, 2023 |
| ASUSTek       | X541UVK                     | [a6ae535887](https://linux-hardware.org/?probe=a6ae535887) | Dec 18, 2023 |
| MSI           | GF63 Thin 11UC              | [06556bd61a](https://linux-hardware.org/?probe=06556bd61a) | Dec 17, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [ce0e0e1bc1](https://linux-hardware.org/?probe=ce0e0e1bc1) | Dec 17, 2023 |
| Apple         | MacBookPro8,1               | [f0ed04c975](https://linux-hardware.org/?probe=f0ed04c975) | Dec 16, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [6a2633018c](https://linux-hardware.org/?probe=6a2633018c) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e7ca2f3a6e](https://linux-hardware.org/?probe=e7ca2f3a6e) | Dec 14, 2023 |
| HUAWEI        | MACHD-WXX9                  | [35a6370b07](https://linux-hardware.org/?probe=35a6370b07) | Dec 14, 2023 |
| Toshiba       | Satellite Pro C660          | [63cf57fa53](https://linux-hardware.org/?probe=63cf57fa53) | Dec 12, 2023 |
| Dell          | Inspiron 7591               | [10a266d0ff](https://linux-hardware.org/?probe=10a266d0ff) | Dec 12, 2023 |
| Lenovo        | ThinkPad T530 2429W1E       | [02a4811e8d](https://linux-hardware.org/?probe=02a4811e8d) | Dec 10, 2023 |
| HP            | ProBook 4535s               | [9005c587a8](https://linux-hardware.org/?probe=9005c587a8) | Dec 10, 2023 |
| Dell          | Inspiron 7591               | [7907f73ee0](https://linux-hardware.org/?probe=7907f73ee0) | Dec 09, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [beaa75c727](https://linux-hardware.org/?probe=beaa75c727) | Dec 06, 2023 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [dfc6e4c96b](https://linux-hardware.org/?probe=dfc6e4c96b) | Dec 05, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | [0c680c33ec](https://linux-hardware.org/?probe=0c680c33ec) | Dec 05, 2023 |
| Dell          | Latitude 7370               | [30fc1de681](https://linux-hardware.org/?probe=30fc1de681) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [203357a4dd](https://linux-hardware.org/?probe=203357a4dd) | Dec 03, 2023 |
| Dell          | Latitude 7370               | [356b2e9e31](https://linux-hardware.org/?probe=356b2e9e31) | Nov 30, 2023 |
| HP            | ProBook 450 G1              | [7c7825a9c9](https://linux-hardware.org/?probe=7c7825a9c9) | Nov 30, 2023 |
| Sony          | VGN-NS12M_W                 | [c1400d8699](https://linux-hardware.org/?probe=c1400d8699) | Nov 27, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [25fd880050](https://linux-hardware.org/?probe=25fd880050) | Nov 26, 2023 |
| ASUSTek       | GL753VD                     | [214c1cc15b](https://linux-hardware.org/?probe=214c1cc15b) | Nov 25, 2023 |
| Dell          | System XPS L502X            | [a59b920838](https://linux-hardware.org/?probe=a59b920838) | Nov 24, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [8edef55308](https://linux-hardware.org/?probe=8edef55308) | Nov 24, 2023 |
| HP            | EliteBook 725 G2            | [b6cfe558cb](https://linux-hardware.org/?probe=b6cfe558cb) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2b84d65d1a](https://linux-hardware.org/?probe=2b84d65d1a) | Nov 20, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [d5ccc9cfc9](https://linux-hardware.org/?probe=d5ccc9cfc9) | Nov 20, 2023 |
| HP            | Pavilion g6                 | [b81902d8d5](https://linux-hardware.org/?probe=b81902d8d5) | Nov 20, 2023 |
| HP            | ProBook 6570b               | [39ba398a11](https://linux-hardware.org/?probe=39ba398a11) | Nov 20, 2023 |
| Dell          | Latitude E6330              | [078f4227bd](https://linux-hardware.org/?probe=078f4227bd) | Nov 19, 2023 |
| Thomson       | N15C8BK2T                   | [e5a62b2035](https://linux-hardware.org/?probe=e5a62b2035) | Nov 18, 2023 |
| Lenovo        | IdeaPad N585 20179          | [b8bca4e3cd](https://linux-hardware.org/?probe=b8bca4e3cd) | Nov 18, 2023 |
| SiComputer    | Nauta 01E                   | [1631e065bd](https://linux-hardware.org/?probe=1631e065bd) | Nov 17, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [6806c7c828](https://linux-hardware.org/?probe=6806c7c828) | Nov 15, 2023 |
| Lenovo        | IdeaPad S300 9803           | [21f7433934](https://linux-hardware.org/?probe=21f7433934) | Nov 15, 2023 |
| ASUSTek       | GL753VD                     | [a05c294e1e](https://linux-hardware.org/?probe=a05c294e1e) | Nov 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS2P703    | [b15506a2b9](https://linux-hardware.org/?probe=b15506a2b9) | Nov 14, 2023 |
| Acer          | Aspire A114-33              | [e592b6bf5d](https://linux-hardware.org/?probe=e592b6bf5d) | Nov 13, 2023 |
| Dell          | Inspiron 15 3511            | [79b891b4df](https://linux-hardware.org/?probe=79b891b4df) | Nov 13, 2023 |
| Dell          | Latitude E5420              | [dc67f70b3b](https://linux-hardware.org/?probe=dc67f70b3b) | Nov 13, 2023 |
| Acer          | Aspire 5740                 | [7deb21f5d9](https://linux-hardware.org/?probe=7deb21f5d9) | Nov 13, 2023 |
| Apple         | MacBookAir4,2               | [aefe53a7b6](https://linux-hardware.org/?probe=aefe53a7b6) | Nov 13, 2023 |
| Acer          | Aspire A114-33              | [6c532c337f](https://linux-hardware.org/?probe=6c532c337f) | Nov 12, 2023 |
| HP            | Pavilion g6                 | [450bb23de1](https://linux-hardware.org/?probe=450bb23de1) | Nov 10, 2023 |
| Lenovo        | ThinkPad E470 20H1006NHV    | [a43db58ab7](https://linux-hardware.org/?probe=a43db58ab7) | Nov 10, 2023 |
| HP            | ProBook 650 G2              | [4caad7b0d1](https://linux-hardware.org/?probe=4caad7b0d1) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | [1d0638865e](https://linux-hardware.org/?probe=1d0638865e) | Nov 07, 2023 |
| Medion        | Crawler E25                 | [945026c1b8](https://linux-hardware.org/?probe=945026c1b8) | Nov 07, 2023 |
| Lenovo        | G505 20240                  | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| MECHREVO      | Code 01 Series PF5NU1G      | [767c3ff7fa](https://linux-hardware.org/?probe=767c3ff7fa) | Nov 05, 2023 |
| Dell          | Inspiron 7501               | [0926c7cdad](https://linux-hardware.org/?probe=0926c7cdad) | Nov 05, 2023 |
| HP            | Presario C500 (GF849EA#A... | [a4965dff09](https://linux-hardware.org/?probe=a4965dff09) | Nov 04, 2023 |
| Thomson       | N14C4WH64                   | [51c94bc00f](https://linux-hardware.org/?probe=51c94bc00f) | Nov 03, 2023 |
| Acer          | Predator PH717-71           | [a72ab29450](https://linux-hardware.org/?probe=a72ab29450) | Nov 02, 2023 |
| HP            | Presario CQ57               | [4874030c75](https://linux-hardware.org/?probe=4874030c75) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [a2a8295797](https://linux-hardware.org/?probe=a2a8295797) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [0d49a75fe1](https://linux-hardware.org/?probe=0d49a75fe1) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [cbe947aefc](https://linux-hardware.org/?probe=cbe947aefc) | Nov 01, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [cd9e941307](https://linux-hardware.org/?probe=cd9e941307) | Nov 01, 2023 |
| Lenovo        | IdeaPad S300 9803           | [543dfc0b4e](https://linux-hardware.org/?probe=543dfc0b4e) | Oct 31, 2023 |
| HP            | Presario C500 (GF849EA#A... | [580f4bdb18](https://linux-hardware.org/?probe=580f4bdb18) | Oct 31, 2023 |
| AMI           | Intel                       | [98d35ad708](https://linux-hardware.org/?probe=98d35ad708) | Oct 31, 2023 |
| ASUSTek       | K53E                        | [8b7c83e9d7](https://linux-hardware.org/?probe=8b7c83e9d7) | Oct 31, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [6273e445bd](https://linux-hardware.org/?probe=6273e445bd) | Oct 30, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a718d2e0ba](https://linux-hardware.org/?probe=a718d2e0ba) | Oct 28, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [c866e0068b](https://linux-hardware.org/?probe=c866e0068b) | Oct 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6a8554304e](https://linux-hardware.org/?probe=6a8554304e) | Oct 27, 2023 |
| Dell          | Inspiron 1501               | [2c88e089bb](https://linux-hardware.org/?probe=2c88e089bb) | Oct 27, 2023 |
| Lenovo        | ThinkPad T61 64607EU        | [413cefff03](https://linux-hardware.org/?probe=413cefff03) | Oct 26, 2023 |
| HP            | Presario CQ57               | [a3f31b427e](https://linux-hardware.org/?probe=a3f31b427e) | Oct 26, 2023 |
| Acer          | Aspire 5740                 | [78702b9deb](https://linux-hardware.org/?probe=78702b9deb) | Oct 23, 2023 |
| Dell          | Latitude 3490               | [174ee1b12e](https://linux-hardware.org/?probe=174ee1b12e) | Oct 20, 2023 |
| Lenovo        | ThinkPad T61 64607EU        | [7be90734f6](https://linux-hardware.org/?probe=7be90734f6) | Oct 19, 2023 |
| HUAWEI        | RLEF-XX                     | [4a5c5417b7](https://linux-hardware.org/?probe=4a5c5417b7) | Oct 17, 2023 |
| Lenovo        | 15ARE05 81W4                | [dcb09acd04](https://linux-hardware.org/?probe=dcb09acd04) | Oct 17, 2023 |
| HP            | 250 G8 Notebook PC          | [949b939768](https://linux-hardware.org/?probe=949b939768) | Oct 16, 2023 |
| Acer          | Aspire A317-51K             | [b342c56fc5](https://linux-hardware.org/?probe=b342c56fc5) | Oct 15, 2023 |
| Dell          | Latitude 7330               | [8632b84be8](https://linux-hardware.org/?probe=8632b84be8) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | [edb8f551bf](https://linux-hardware.org/?probe=edb8f551bf) | Oct 14, 2023 |
| HP            | Laptop 15-dw0xxx            | [b7a193296f](https://linux-hardware.org/?probe=b7a193296f) | Oct 14, 2023 |
| Dynabook      | B65/ER                      | [2bda5e79a4](https://linux-hardware.org/?probe=2bda5e79a4) | Oct 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [41ca042a36](https://linux-hardware.org/?probe=41ca042a36) | Oct 14, 2023 |
| Dynabook      | B65/ER                      | [4bc1c4e1b6](https://linux-hardware.org/?probe=4bc1c4e1b6) | Oct 14, 2023 |
| Lenovo        | ThinkPad T430u 3352A83      | [c5a829d842](https://linux-hardware.org/?probe=c5a829d842) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | [1a8e527488](https://linux-hardware.org/?probe=1a8e527488) | Oct 13, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [ef43db2db3](https://linux-hardware.org/?probe=ef43db2db3) | Oct 12, 2023 |
| Dell          | Latitude 5411               | [48ecb46d24](https://linux-hardware.org/?probe=48ecb46d24) | Oct 09, 2023 |
| Dell          | MXG061                      | [61763acf36](https://linux-hardware.org/?probe=61763acf36) | Oct 08, 2023 |
| Dell          | MXG061                      | [93939082fa](https://linux-hardware.org/?probe=93939082fa) | Oct 08, 2023 |
| MSI           | GP65 Leopard 10SDK          | [6b02c3ce0f](https://linux-hardware.org/?probe=6b02c3ce0f) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [3e5383da88](https://linux-hardware.org/?probe=3e5383da88) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [cab160aff3](https://linux-hardware.org/?probe=cab160aff3) | Oct 08, 2023 |
| Fujitsu Si... | LIFEBOOK T4215              | [392481b855](https://linux-hardware.org/?probe=392481b855) | Oct 04, 2023 |
| ASUSTek       | ROG Strix G814JU_G814JU     | [45be832065](https://linux-hardware.org/?probe=45be832065) | Oct 04, 2023 |
| ASUSTek       | ROG Strix G814JU_G814JU     | [2dc93ff736](https://linux-hardware.org/?probe=2dc93ff736) | Oct 04, 2023 |
| Toshiba       | Satellite C55-C             | [e9ce3eada7](https://linux-hardware.org/?probe=e9ce3eada7) | Oct 02, 2023 |
| Google        | Swanky                      | [599959ccbe](https://linux-hardware.org/?probe=599959ccbe) | Sep 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [39fd38bc98](https://linux-hardware.org/?probe=39fd38bc98) | Sep 28, 2023 |
| ASUSTek       | N550JV                      | [ac27d821ae](https://linux-hardware.org/?probe=ac27d821ae) | Sep 27, 2023 |
| Fujitsu       | LIFEBOOK E734               | [61f61b1b63](https://linux-hardware.org/?probe=61f61b1b63) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK E734               | [ffb5ff9359](https://linux-hardware.org/?probe=ffb5ff9359) | Sep 25, 2023 |
| Toshiba       | Satellite C50D-A-10E        | [46f0ec000d](https://linux-hardware.org/?probe=46f0ec000d) | Sep 24, 2023 |
| Google        | Magpie                      | [3da6f69ed3](https://linux-hardware.org/?probe=3da6f69ed3) | Sep 24, 2023 |
| MSI           | GS75 Stealth 10SGS          | [9a310dd76b](https://linux-hardware.org/?probe=9a310dd76b) | Sep 24, 2023 |
| Dell          | XPS 15 9570                 | [fe5f9ad018](https://linux-hardware.org/?probe=fe5f9ad018) | Sep 23, 2023 |
| ASUSTek       | X510UQR                     | [364ee59aef](https://linux-hardware.org/?probe=364ee59aef) | Sep 23, 2023 |
| Dell          | Latitude D500               | [1861582ebd](https://linux-hardware.org/?probe=1861582ebd) | Sep 21, 2023 |
| Dell          | Latitude D500               | [19ccfd47c6](https://linux-hardware.org/?probe=19ccfd47c6) | Sep 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a6fd72ec9a](https://linux-hardware.org/?probe=a6fd72ec9a) | Sep 20, 2023 |
| Lenovo        | ThinkPad T430 2349BG6       | [dbd8f7715f](https://linux-hardware.org/?probe=dbd8f7715f) | Sep 19, 2023 |
| Apple         | MacBookPro5,4               | [f2d4f47a8e](https://linux-hardware.org/?probe=f2d4f47a8e) | Sep 18, 2023 |
| Dell          | Latitude 3520               | [c74d2293dd](https://linux-hardware.org/?probe=c74d2293dd) | Sep 18, 2023 |
| Acer          | Aspire E5-473G              | [936a48fb5a](https://linux-hardware.org/?probe=936a48fb5a) | Sep 16, 2023 |
| Lenovo        | ThinkPad T450 20BVA01QHV    | [4f0a2bdfdc](https://linux-hardware.org/?probe=4f0a2bdfdc) | Sep 15, 2023 |
| ASUSTek       | K72Dr                       | [46edd6eb72](https://linux-hardware.org/?probe=46edd6eb72) | Sep 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [cf69e328c4](https://linux-hardware.org/?probe=cf69e328c4) | Sep 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [b6a4327a8b](https://linux-hardware.org/?probe=b6a4327a8b) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [a51361ebb2](https://linux-hardware.org/?probe=a51361ebb2) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [00cbde2fb9](https://linux-hardware.org/?probe=00cbde2fb9) | Sep 12, 2023 |
| Medion        | Akoya P2213T                | [7d201de7d6](https://linux-hardware.org/?probe=7d201de7d6) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5b93cd5b36](https://linux-hardware.org/?probe=5b93cd5b36) | Sep 11, 2023 |
| Dell          | Vostro 3501                 | [7caa16d219](https://linux-hardware.org/?probe=7caa16d219) | Sep 11, 2023 |
| Olivetti      | OLIBOOK PX5-XXXAES          | [70225c18e1](https://linux-hardware.org/?probe=70225c18e1) | Sep 10, 2023 |
| Google        | Rabbid                      | [c55be85343](https://linux-hardware.org/?probe=c55be85343) | Sep 09, 2023 |
| Lenovo        | ThinkPad X250 20CLA1YJUK    | [a068fec56f](https://linux-hardware.org/?probe=a068fec56f) | Sep 09, 2023 |
| Dell          | XPS 13 9305                 | [b3756f752a](https://linux-hardware.org/?probe=b3756f752a) | Sep 08, 2023 |
| Medion        | Akoya P2213T                | [2464869ce2](https://linux-hardware.org/?probe=2464869ce2) | Sep 06, 2023 |
| Acer          | Aspire 5349                 | [62f941ff29](https://linux-hardware.org/?probe=62f941ff29) | Sep 03, 2023 |
| HP            | ZBook 17 G3                 | [43c2d13a44](https://linux-hardware.org/?probe=43c2d13a44) | Aug 31, 2023 |
| HP            | EliteBook 820 G3            | [5ef4c889a4](https://linux-hardware.org/?probe=5ef4c889a4) | Aug 31, 2023 |
| Dell          | Latitude E5510              | [61f6df7426](https://linux-hardware.org/?probe=61f6df7426) | Aug 29, 2023 |
| HP            | Pavilion 17                 | [ba077d7ea1](https://linux-hardware.org/?probe=ba077d7ea1) | Aug 29, 2023 |
| Dell          | XPS 15 9500                 | [74ad31c9de](https://linux-hardware.org/?probe=74ad31c9de) | Aug 29, 2023 |
| Apple         | MacBookPro7,1               | [f520b2dd72](https://linux-hardware.org/?probe=f520b2dd72) | Aug 28, 2023 |
| ASUSTek       | ROG Strix G733PY_G733PY     | [b886de0613](https://linux-hardware.org/?probe=b886de0613) | Aug 28, 2023 |
| Google        | Banjo                       | [fcac9f460e](https://linux-hardware.org/?probe=fcac9f460e) | Aug 28, 2023 |
| HP            | Pavilion 17                 | [1d04c114d6](https://linux-hardware.org/?probe=1d04c114d6) | Aug 26, 2023 |
| Toshiba       | Satellite C55D-B            | [b7dce1f6e0](https://linux-hardware.org/?probe=b7dce1f6e0) | Aug 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [add8b61fa2](https://linux-hardware.org/?probe=add8b61fa2) | Aug 24, 2023 |
| Lenovo        | ThinkPad T460s 20F9003VM... | [e6e076d380](https://linux-hardware.org/?probe=e6e076d380) | Aug 23, 2023 |
| Acer          | AOD255                      | [06c6346db1](https://linux-hardware.org/?probe=06c6346db1) | Aug 23, 2023 |
| Acer          | TMP255-M                    | [4d5632e2d0](https://linux-hardware.org/?probe=4d5632e2d0) | Aug 22, 2023 |
| GPU Compan... | GWTN156-5                   | [22efc40cfd](https://linux-hardware.org/?probe=22efc40cfd) | Aug 21, 2023 |
| HP            | Presario CQ42               | [183f035603](https://linux-hardware.org/?probe=183f035603) | Aug 20, 2023 |
| Lenovo        | G50-70 20351                | [a8a0c22567](https://linux-hardware.org/?probe=a8a0c22567) | Aug 20, 2023 |
| HP            | 250 G4 Notebook PC          | [ea6fdc81ab](https://linux-hardware.org/?probe=ea6fdc81ab) | Aug 18, 2023 |
| Acer          | Aspire E1-571G              | [6aec4cb61e](https://linux-hardware.org/?probe=6aec4cb61e) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f626ffa833](https://linux-hardware.org/?probe=f626ffa833) | Aug 17, 2023 |
| Sony          | VGN-SR19VN                  | [013756c475](https://linux-hardware.org/?probe=013756c475) | Aug 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [48af3e541c](https://linux-hardware.org/?probe=48af3e541c) | Aug 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [5b482b674c](https://linux-hardware.org/?probe=5b482b674c) | Aug 16, 2023 |
| MSI           | U90/U100                    | [e8ae0fbcfb](https://linux-hardware.org/?probe=e8ae0fbcfb) | Aug 14, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Lenovo        | B50-50 80S2                 | [6c897e0c63](https://linux-hardware.org/?probe=6c897e0c63) | Aug 14, 2023 |
| Daten Tecn... | DT02-M4                     | [39acd7fbd5](https://linux-hardware.org/?probe=39acd7fbd5) | Aug 13, 2023 |
| Lenovo        | IdeaPad Y570 0862           | [0ea140ff49](https://linux-hardware.org/?probe=0ea140ff49) | Aug 12, 2023 |
| Dell          | Latitude 3540               | [496e3ab340](https://linux-hardware.org/?probe=496e3ab340) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| Unknown       | Unknown                     | [5f186cbc4d](https://linux-hardware.org/?probe=5f186cbc4d) | Aug 09, 2023 |
| ASUSTek       | X541UVK                     | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Acer          | Aspire 5732Z                | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | [cc5ec06f60](https://linux-hardware.org/?probe=cc5ec06f60) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | [14e4cbffd4](https://linux-hardware.org/?probe=14e4cbffd4) | Aug 08, 2023 |
| Dell          | Latitude 5411               | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| Lenovo        | G500 20236                  | [88a569c8ee](https://linux-hardware.org/?probe=88a569c8ee) | Aug 03, 2023 |
| Acer          | Aspire A517-52              | [aa9fd10def](https://linux-hardware.org/?probe=aa9fd10def) | Aug 01, 2023 |
| Acer          | AOD255                      | [bdaffcb2ef](https://linux-hardware.org/?probe=bdaffcb2ef) | Jul 31, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [67fbb84480](https://linux-hardware.org/?probe=67fbb84480) | Jul 31, 2023 |
| SiComputer    | NL40_50CU                   | [95afbe5674](https://linux-hardware.org/?probe=95afbe5674) | Jul 30, 2023 |
| Acer          | Aspire A517-52              | [1df8f3a3ed](https://linux-hardware.org/?probe=1df8f3a3ed) | Jul 29, 2023 |
| Medion        | Akoya P2213T                | [740da3bf14](https://linux-hardware.org/?probe=740da3bf14) | Jul 29, 2023 |
| Acer          | AOD255                      | [53c73b6ad3](https://linux-hardware.org/?probe=53c73b6ad3) | Jul 29, 2023 |
| HP            | ProBook 4525s               | [f1f6309860](https://linux-hardware.org/?probe=f1f6309860) | Jul 29, 2023 |
| Gateway       | NV57H                       | [efc311477f](https://linux-hardware.org/?probe=efc311477f) | Jul 28, 2023 |
| Samsung       | N250P/N145P                 | [6b6e675a4c](https://linux-hardware.org/?probe=6b6e675a4c) | Jul 28, 2023 |
| Acer          | Extensa 2510                | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| Acer          | AOD255                      | [4f96dbf750](https://linux-hardware.org/?probe=4f96dbf750) | Jul 25, 2023 |
| Acer          | AOD255                      | [3543f0800e](https://linux-hardware.org/?probe=3543f0800e) | Jul 24, 2023 |
| MSI           | MEGA BOOK GX620             | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [ff6179199d](https://linux-hardware.org/?probe=ff6179199d) | Jul 22, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [1c28b8d159](https://linux-hardware.org/?probe=1c28b8d159) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| Itautec       | Infoway w7535               | [bde95c0c99](https://linux-hardware.org/?probe=bde95c0c99) | Jul 21, 2023 |
| Thomson       | N15C8BK2T                   | [2e04333da5](https://linux-hardware.org/?probe=2e04333da5) | Jul 19, 2023 |
| Dell          | Latitude 5590               | [93857a3b66](https://linux-hardware.org/?probe=93857a3b66) | Jul 18, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | [f0f2c5a6a7](https://linux-hardware.org/?probe=f0f2c5a6a7) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | [6070a533c5](https://linux-hardware.org/?probe=6070a533c5) | Jul 17, 2023 |
| MSI           | GF65 Thin 10SER             | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| Dell          | Inspiron 1501               | [a79d62db7c](https://linux-hardware.org/?probe=a79d62db7c) | Jul 16, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [c9a443767b](https://linux-hardware.org/?probe=c9a443767b) | Jul 16, 2023 |
| MSI           | Modern 15 A10RBS            | [fde24c2a13](https://linux-hardware.org/?probe=fde24c2a13) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | [d18c64af74](https://linux-hardware.org/?probe=d18c64af74) | Jul 14, 2023 |
| GPU Compan... | GWNC21524                   | [e3e2452c10](https://linux-hardware.org/?probe=e3e2452c10) | Jul 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| HP            | ProBook 4525s               | [6bae89bb98](https://linux-hardware.org/?probe=6bae89bb98) | Jul 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | [5aacfb69aa](https://linux-hardware.org/?probe=5aacfb69aa) | Jul 12, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [d4bc86a90a](https://linux-hardware.org/?probe=d4bc86a90a) | Jul 12, 2023 |
| Lenovo        | ThinkPad T460s 20FAS42W0... | [add1dac3cb](https://linux-hardware.org/?probe=add1dac3cb) | Jul 11, 2023 |
| HP            | ProBook 11 G2               | [db2ec8adc8](https://linux-hardware.org/?probe=db2ec8adc8) | Jul 08, 2023 |
| Acer          | Aspire A315-54              | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Olidata       | Stainer 8050                | [beb3c029a6](https://linux-hardware.org/?probe=beb3c029a6) | Jul 07, 2023 |
| Dell          | Latitude 3540               | [4ebbd2913f](https://linux-hardware.org/?probe=4ebbd2913f) | Jul 06, 2023 |
| HP            | Compaq Presario CQ60        | [983745a0d2](https://linux-hardware.org/?probe=983745a0d2) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | [a5bd493e91](https://linux-hardware.org/?probe=a5bd493e91) | Jul 03, 2023 |
| Google        | Snappy                      | [683d8bf80a](https://linux-hardware.org/?probe=683d8bf80a) | Jul 02, 2023 |
| Google        | Snappy                      | [d3502a53cc](https://linux-hardware.org/?probe=d3502a53cc) | Jul 02, 2023 |
| HP            | Pavilion 17                 | [e6daccb5b9](https://linux-hardware.org/?probe=e6daccb5b9) | Jul 02, 2023 |
| Acer          | Aspire A517-52              | [7c14851b62](https://linux-hardware.org/?probe=7c14851b62) | Jul 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [f252a559f2](https://linux-hardware.org/?probe=f252a559f2) | Jul 02, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [b9d71582c0](https://linux-hardware.org/?probe=b9d71582c0) | Jul 01, 2023 |
| MSI           | GF63 Thin 11UC              | [5270a5ddc7](https://linux-hardware.org/?probe=5270a5ddc7) | Jul 01, 2023 |
| Dynabook      | B65/ER                      | [8f6f243e98](https://linux-hardware.org/?probe=8f6f243e98) | Jul 01, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| Acer          | Aspire A517-52              | [79f2cae4d6](https://linux-hardware.org/?probe=79f2cae4d6) | Jun 30, 2023 |
| Google        | Fleex                       | [7e3eb2d4f9](https://linux-hardware.org/?probe=7e3eb2d4f9) | Jun 30, 2023 |
| HP            | Unknown                     | [0f4ae63ce0](https://linux-hardware.org/?probe=0f4ae63ce0) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | [06d27800c2](https://linux-hardware.org/?probe=06d27800c2) | Jun 29, 2023 |
| Apple         | MacBookPro7,1               | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| HP            | Unknown                     | [d681765bb7](https://linux-hardware.org/?probe=d681765bb7) | Jun 26, 2023 |
| Dell          | Inspiron MM061              | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [338b2e7db3](https://linux-hardware.org/?probe=338b2e7db3) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Dell          | Latitude E6410              | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Dell          | Inspiron N4030              | [89116ab6be](https://linux-hardware.org/?probe=89116ab6be) | Jun 24, 2023 |
| Alienware     | 18                          | [047bc74541](https://linux-hardware.org/?probe=047bc74541) | Jun 24, 2023 |
| ASUSTek       | N53SV                       | [0908f99494](https://linux-hardware.org/?probe=0908f99494) | Jun 23, 2023 |
| ASUSTek       | N53SV                       | [1999834725](https://linux-hardware.org/?probe=1999834725) | Jun 23, 2023 |
| Google        | Link                        | [b8284753ca](https://linux-hardware.org/?probe=b8284753ca) | Jun 22, 2023 |
| HP            | Unknown                     | [4f27a83f9e](https://linux-hardware.org/?probe=4f27a83f9e) | Jun 21, 2023 |
| TUXEDO        | P65xRP                      | [cfefc9c13a](https://linux-hardware.org/?probe=cfefc9c13a) | Jun 20, 2023 |
| Dell          | Inspiron 5415               | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| Acer          | Aspire 5600                 | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| GPU Compan... | GWNC21524                   | [5a31ac8b21](https://linux-hardware.org/?probe=5a31ac8b21) | Jun 15, 2023 |
| HP            | Unknown                     | [00c49ad567](https://linux-hardware.org/?probe=00c49ad567) | Jun 14, 2023 |
| Samsung       | 760XDA                      | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| Dell          | Latitude E5270              | [49f184b9e9](https://linux-hardware.org/?probe=49f184b9e9) | Jun 13, 2023 |
| GPU Compan... | GWTN156-5                   | [b0afd2fa7b](https://linux-hardware.org/?probe=b0afd2fa7b) | Jun 13, 2023 |
| Dell          | Latitude 5411               | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| HP            | EliteBook 640 14 inch G9... | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| Toshiba       | Satellite C650              | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| Acer          | AO722                       | [a57b6cf2ff](https://linux-hardware.org/?probe=a57b6cf2ff) | Jun 08, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [2f5adf59a3](https://linux-hardware.org/?probe=2f5adf59a3) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Acer          | AO722                       | [8840b1284b](https://linux-hardware.org/?probe=8840b1284b) | Jun 06, 2023 |
| Dell          | Precision 5510              | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [46751741ef](https://linux-hardware.org/?probe=46751741ef) | Jun 05, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| Lenovo        | V560                        | [b2564e07cc](https://linux-hardware.org/?probe=b2564e07cc) | Jun 03, 2023 |
| SK hynix      | HyBook                      | [c25f19e040](https://linux-hardware.org/?probe=c25f19e040) | Jun 03, 2023 |
| HP            | Laptop 14s-dq0xxx           | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| Dell          | Latitude 7390               | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Unknown       | Unknown                     | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Chuwi         | CoreBook X                  | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| Acer          | Aspire E5-772G              | [ae0b46c29f](https://linux-hardware.org/?probe=ae0b46c29f) | May 28, 2023 |
| Unknown       | Unknown                     | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Dell          | Latitude 7390               | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| Toshiba       | Satellite L300              | [10adda3362](https://linux-hardware.org/?probe=10adda3362) | May 25, 2023 |
| Samsung       | 730QCJ/730QCR               | [7788147663](https://linux-hardware.org/?probe=7788147663) | May 24, 2023 |
| Dell          | Inspiron 15-3552            | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| Lenovo        | ThinkPad W500 40626NG       | [9466f83af8](https://linux-hardware.org/?probe=9466f83af8) | May 22, 2023 |
| Dell          | Latitude E4200              | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| Dell          | Vostro 5620                 | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [bfaa8e099f](https://linux-hardware.org/?probe=bfaa8e099f) | May 21, 2023 |
| Dell          | G3 3500                     | [cbe9c2f010](https://linux-hardware.org/?probe=cbe9c2f010) | May 21, 2023 |
| Google        | Snappy                      | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Acer          | TravelMate P215-41-G2       | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7661V3L        | [5714171d2a](https://linux-hardware.org/?probe=5714171d2a) | May 14, 2023 |
| Acer          | Aspire V5-552G              | [4384294484](https://linux-hardware.org/?probe=4384294484) | May 14, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [7e178a2a32](https://linux-hardware.org/?probe=7e178a2a32) | May 13, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [0b0b5e02cc](https://linux-hardware.org/?probe=0b0b5e02cc) | May 13, 2023 |
| Fujitsu       | LIFEBOOK P702               | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Dell          | Vostro 5620                 | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7b53d1c3dc](https://linux-hardware.org/?probe=7b53d1c3dc) | May 11, 2023 |
| Dell          | Latitude E4310              | [84d1a3fda9](https://linux-hardware.org/?probe=84d1a3fda9) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Google        | Edgar                       | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| Gigabyte      | A7 K1                       | [1c37df2d10](https://linux-hardware.org/?probe=1c37df2d10) | May 09, 2023 |
| Google        | Snappy                      | [52836871bb](https://linux-hardware.org/?probe=52836871bb) | May 09, 2023 |
| Google        | Snappy                      | [a026aff306](https://linux-hardware.org/?probe=a026aff306) | May 09, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [0f322b6e3f](https://linux-hardware.org/?probe=0f322b6e3f) | May 08, 2023 |
| GPU Compan... | GWTC116-2                   | [a915e84a9a](https://linux-hardware.org/?probe=a915e84a9a) | May 08, 2023 |
| Google        | Auron_Yuna                  | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| HP            | Pavilion dv6                | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| Dell          | Inspiron 15-3567            | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [c693555567](https://linux-hardware.org/?probe=c693555567) | May 05, 2023 |
| HP            | ENVY 4                      | [20395a1739](https://linux-hardware.org/?probe=20395a1739) | May 04, 2023 |
| MSI           | Modern 15 A5M               | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| HP            | 15                          | [17817f5320](https://linux-hardware.org/?probe=17817f5320) | May 02, 2023 |
| Dell          | Latitude E7270              | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| Dell          | Latitude E7270              | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| Toshiba       | EQUIUM P200                 | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Acer          | Peppy                       | [dcac703c46](https://linux-hardware.org/?probe=dcac703c46) | Apr 30, 2023 |
| Acer          | Extensa 5620                | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| Sony          | VPCZ13M9E                   | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Dell          | Vostro 1520                 | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [76c4edb7f3](https://linux-hardware.org/?probe=76c4edb7f3) | Apr 23, 2023 |
| Dell          | XPS 13 9333                 | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| Acer          | Aspire E1-571G              | [e062ca363c](https://linux-hardware.org/?probe=e062ca363c) | Apr 20, 2023 |
| HP            | ProBook 650 G3              | [704778a577](https://linux-hardware.org/?probe=704778a577) | Apr 19, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| HP            | ProBook 11 G2               | [222f45e8c6](https://linux-hardware.org/?probe=222f45e8c6) | Apr 18, 2023 |
| HP            | Pavilion g6                 | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| HP            | Laptop 17-cp2xxx            | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Toshiba       | Satellite L750D             | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U759               | [08e8eb7cea](https://linux-hardware.org/?probe=08e8eb7cea) | Apr 05, 2023 |
| ASUSTek       | X58C                        | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| ASUSTek       | X58C                        | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [86de0a83c3](https://linux-hardware.org/?probe=86de0a83c3) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [81c43aeb0d](https://linux-hardware.org/?probe=81c43aeb0d) | Mar 30, 2023 |
| Medion        | S321X                       | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| Gateway       | LT27                        | [4697cead5f](https://linux-hardware.org/?probe=4697cead5f) | Mar 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a7ff24abc4](https://linux-hardware.org/?probe=a7ff24abc4) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [8d5a135264](https://linux-hardware.org/?probe=8d5a135264) | Mar 26, 2023 |
| Samsung       | RV408/RV508                 | [5f5efa7edc](https://linux-hardware.org/?probe=5f5efa7edc) | Mar 25, 2023 |
| Samsung       | RV408/RV508                 | [cce3fdd054](https://linux-hardware.org/?probe=cce3fdd054) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| Unknown       | Unknown                     | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [f97f90f7ce](https://linux-hardware.org/?probe=f97f90f7ce) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Gateway       | EC14 Series                 | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| Lenovo        | ThinkPad T530 2429LT7       | [ebb127610b](https://linux-hardware.org/?probe=ebb127610b) | Mar 20, 2023 |
| Chuwi         | CoreBook X                  | [fd4d05d961](https://linux-hardware.org/?probe=fd4d05d961) | Mar 20, 2023 |
| Gateway       | EC14 Series                 | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [a174d9ea53](https://linux-hardware.org/?probe=a174d9ea53) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| Google        | Kefka                       | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| Apple         | MacBookPro1,1               | [105d39532f](https://linux-hardware.org/?probe=105d39532f) | Mar 10, 2023 |
| Toshiba       | Satellite L300              | [a35bb278ba](https://linux-hardware.org/?probe=a35bb278ba) | Mar 09, 2023 |
| Toshiba       | Satellite L300              | [13418c9605](https://linux-hardware.org/?probe=13418c9605) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| Toshiba       | Satellite C55D-B            | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Toshiba       | Satellite L775              | [75a1948a64](https://linux-hardware.org/?probe=75a1948a64) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| Microtech     | ebookPro                    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [64c40ef1a4](https://linux-hardware.org/?probe=64c40ef1a4) | Mar 06, 2023 |
| Acer          | Aspire A315-43              | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Acer          | Aspire 5740                 | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| HP            | 655                         | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Alienware     | 17 R4                       | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| Dell          | Studio 1450                 | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| Acer          | Aspire 7736                 | [479496a645](https://linux-hardware.org/?probe=479496a645) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| HP            | Pavilion 15                 | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| Sony          | VPCEA3S1E                   | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Sony          | VPCZ13M9E                   | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| HP            | Pavilion g6                 | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Sony          | VPCX11Z6R                   | [ad87a45a26](https://linux-hardware.org/?probe=ad87a45a26) | Feb 12, 2023 |
| Packard Be... | DOT S                       | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| Dell          | Latitude E5450              | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| HP            | Compaq Presario A900        | [d3c4a9e1e6](https://linux-hardware.org/?probe=d3c4a9e1e6) | Feb 09, 2023 |
| Lenovo        | ThinkPad T430s 23562Z3      | [7338d8375a](https://linux-hardware.org/?probe=7338d8375a) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T440p 20AN006NU... | [e3bd76eeaf](https://linux-hardware.org/?probe=e3bd76eeaf) | Feb 07, 2023 |
| Dell          | Latitude D430               | [0c1ad39f32](https://linux-hardware.org/?probe=0c1ad39f32) | Feb 06, 2023 |
| Insyde        | CherryTrail                 | [cb02cfc77c](https://linux-hardware.org/?probe=cb02cfc77c) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Intel         | Unknown                     | [f12482330f](https://linux-hardware.org/?probe=f12482330f) | Feb 05, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| HP            | 250 G7 Notebook PC          | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| HP            | 240 G3                      | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | Latitude D630               | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| HP            | 240 G8 Notebook PC          | [00a3607d18](https://linux-hardware.org/?probe=00a3607d18) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [f409b1df0b](https://linux-hardware.org/?probe=f409b1df0b) | Jan 27, 2023 |
| Philco        | 14E                         | [1c069ed627](https://linux-hardware.org/?probe=1c069ed627) | Jan 27, 2023 |
| Philco        | 14E                         | [cfb283e599](https://linux-hardware.org/?probe=cfb283e599) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Packard Be... | EasyNote TK87               | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Acer          | Aspire 5920G                | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Dell          | Inspiron 3541               | [12d8081c29](https://linux-hardware.org/?probe=12d8081c29) | Jan 23, 2023 |
| Notebook      | W65_67SZ                    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | [8d876754f3](https://linux-hardware.org/?probe=8d876754f3) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | [f1f61785e5](https://linux-hardware.org/?probe=f1f61785e5) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | [fb70812654](https://linux-hardware.org/?probe=fb70812654) | Jan 21, 2023 |
| ASUSTek       | N53SN                       | [bc8c82ca9a](https://linux-hardware.org/?probe=bc8c82ca9a) | Jan 21, 2023 |
| Dell          | Inspiron 5391               | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| Dell          | Venue 11 Pro 7139           | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76ab21d17b](https://linux-hardware.org/?probe=76ab21d17b) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| Dell          | Latitude E6440              | [f2b34c7c46](https://linux-hardware.org/?probe=f2b34c7c46) | Jan 17, 2023 |
| Dell          | Inspiron N4010              | [7d03111ac0](https://linux-hardware.org/?probe=7d03111ac0) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [558f3d0d93](https://linux-hardware.org/?probe=558f3d0d93) | Jan 14, 2023 |
| ASUSTek       | A7K                         | [1303f158ab](https://linux-hardware.org/?probe=1303f158ab) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| Sony          | VPCEB3L9E                   | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Aspire E5-771               | [dc397ff7f7](https://linux-hardware.org/?probe=dc397ff7f7) | Jan 09, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | [2f9ff5256a](https://linux-hardware.org/?probe=2f9ff5256a) | Jan 08, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | [b952438f2c](https://linux-hardware.org/?probe=b952438f2c) | Jan 08, 2023 |
| Toshiba       | NB205                       | [3d6ba0d0b3](https://linux-hardware.org/?probe=3d6ba0d0b3) | Jan 07, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Dell          | Latitude 5590               | [f32e1efdef](https://linux-hardware.org/?probe=f32e1efdef) | Jan 05, 2023 |
| Samsung       | R530/R730                   | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Latitude E6420              | [0ac727d853](https://linux-hardware.org/?probe=0ac727d853) | Jan 03, 2023 |
| Dell          | Inspiron 5423               | [14aa07b144](https://linux-hardware.org/?probe=14aa07b144) | Jan 02, 2023 |
| Dell          | Inspiron 5423               | [0c30f220cb](https://linux-hardware.org/?probe=0c30f220cb) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Dell          | Latitude E5440              | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Toshiba       | Satellite C650              | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Unknown       | OA Q-ONE BRAND_V2.0         | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| Clevo         | P170EM                      | [3c8b8bd784](https://linux-hardware.org/?probe=3c8b8bd784) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Dell          | Latitude E5450              | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| HP            | Pavilion dv7                | [075b40bb9e](https://linux-hardware.org/?probe=075b40bb9e) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| Dell          | Latitude E6430              | [643c90d5e1](https://linux-hardware.org/?probe=643c90d5e1) | Dec 20, 2022 |
| Dell          | Latitude E6430              | [ba280c7787](https://linux-hardware.org/?probe=ba280c7787) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| Sony          | VPCS12V9E                   | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Toshiba       | Satellite M70               | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| HP            | 350 G1                      | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Fusion5       | Lapbook T90B                | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| Acer          | Aspire 5935                 | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Dell          | XPS 15 9560                 | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| ASUSTek       | K53SC                       | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [762b81c49e](https://linux-hardware.org/?probe=762b81c49e) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [01543655e9](https://linux-hardware.org/?probe=01543655e9) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude D610               | [437f7630fd](https://linux-hardware.org/?probe=437f7630fd) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| ASUSTek       | 1015CX                      | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| Positivo      | Mobile                      | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Unknown       | Unknown                     | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| HP            | 8540w                       | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| Dell          | Latitude 5490               | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| HP            | 245 G8 Notebook PC          | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| ASUSTek       | K53U                        | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| HP            | ProBook 6450b               | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | ProBook 640 G4              | [c120112085](https://linux-hardware.org/?probe=c120112085) | Nov 13, 2022 |
| HP            | Laptop 17-cp0xxx            | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS33U0... | [ce3e5599ad](https://linux-hardware.org/?probe=ce3e5599ad) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| Apple         | MacBookAir6,2               | [fa6ec2e89c](https://linux-hardware.org/?probe=fa6ec2e89c) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Dell          | Precision M6400             | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| Dell          | Inspiron 5490               | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Latitude E6510              | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Dell          | Latitude E6510              | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| Dell          | Inspiron N5030              | [dbc717a299](https://linux-hardware.org/?probe=dbc717a299) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| Toshiba       | Satellite C75D-B            | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| HP            | 15                          | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Dell          | 500                         | [91b78b800a](https://linux-hardware.org/?probe=91b78b800a) | Oct 17, 2022 |
| Dell          | Latitude E5270              | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| Samsung       | NC10                        | [1ea93f5095](https://linux-hardware.org/?probe=1ea93f5095) | Oct 16, 2022 |
| MSI           | GS40 6QE Phantom            | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Unknown       | Unknown                     | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| HP            | 255 G1                      | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| GPU Compan... | GWTN116-3                   | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Dell          | Inspiron 3521               | [50615f4621](https://linux-hardware.org/?probe=50615f4621) | Oct 04, 2022 |
| Acer          | Extensa 5230                | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Dell          | Inspiron 7520               | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Dell          | 500                         | [83c01aa11f](https://linux-hardware.org/?probe=83c01aa11f) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Acer          | Aspire A315-55G             | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Lenovo        | IdeaPad N585 20179          | [0a8aed635a](https://linux-hardware.org/?probe=0a8aed635a) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Toshiba       | Satellite C650              | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Toshiba       | Satellite C55D-B            | [5b2029b4d3](https://linux-hardware.org/?probe=5b2029b4d3) | Sep 24, 2022 |
| Toshiba       | Satellite A300              | [3f6203e550](https://linux-hardware.org/?probe=3f6203e550) | Sep 24, 2022 |
| Tactus        | GeoBook 140                 | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| Dell          | Precision 7750              | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| HP            | Laptop 15-ef1xxx            | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Dell          | Precision 5540              | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| HP            | 1000                        | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| Dell          | Inspiron 3537               | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| Dell          | Latitude 9520               | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Apple         | MacBookPro16,1              | [8add31fdfe](https://linux-hardware.org/?probe=8add31fdfe) | Sep 02, 2022 |
| Acer          | Aspire A315-31              | [21d3a4bd56](https://linux-hardware.org/?probe=21d3a4bd56) | Sep 02, 2022 |
| Dell          | Latitude E5530 non-vPro     | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| Acer          | Aspire E5-771G              | [76803c2532](https://linux-hardware.org/?probe=76803c2532) | Aug 30, 2022 |
| Sony          | VPCSB1V9R                   | [b54e74887f](https://linux-hardware.org/?probe=b54e74887f) | Aug 29, 2022 |
| Acer          | Aspire E5-771G              | [52cc79c6d9](https://linux-hardware.org/?probe=52cc79c6d9) | Aug 29, 2022 |
| Dell          | Inspiron N5010              | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| Dell          | XPS 13 9380                 | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Acer          | Unknown                     | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4291V1C       | [8ab56e33c4](https://linux-hardware.org/?probe=8ab56e33c4) | Aug 21, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [dd53f23249](https://linux-hardware.org/?probe=dd53f23249) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| ASUSTek       | K53TA                       | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | K84C                        | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Panasonic     | CF-31XEUAXMF                | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| Dell          | System XPS L502X            | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| ASUSTek       | K53SC                       | [15522c32d7](https://linux-hardware.org/?probe=15522c32d7) | Aug 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Render        | NOTEBOOK Revision A         | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| ASUSTek       | 1015CX                      | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| Acer          | Aspire V3-551G              | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [8aa899fe67](https://linux-hardware.org/?probe=8aa899fe67) | Aug 02, 2022 |
| GMKtec        | NucBox5                     | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [e512f0884d](https://linux-hardware.org/?probe=e512f0884d) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| Unknown       | Unknown                     | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Unknown       | Unknown                     | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Alienware     | 17 R4                       | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| Samsung       | R59P/R60P/R61P              | [d435057109](https://linux-hardware.org/?probe=d435057109) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| LG Electro... | LE50-5BC6H1                 | [010123b7d5](https://linux-hardware.org/?probe=010123b7d5) | Jul 26, 2022 |
| Lenovo        | G50-30 80G0                 | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| Apple         | MacBookPro12,1              | [4db419918b](https://linux-hardware.org/?probe=4db419918b) | Jul 25, 2022 |
| Toshiba       | NB205                       | [2dd373f150](https://linux-hardware.org/?probe=2dd373f150) | Jul 23, 2022 |
| ASUSTek       | N56VZ                       | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Dell          | Inspiron N5030              | [3ae520c245](https://linux-hardware.org/?probe=3ae520c245) | Jul 22, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| MSI           | U-100 Ver.001               | [b5b7407958](https://linux-hardware.org/?probe=b5b7407958) | Jul 20, 2022 |
| MSI           | U-100 Ver.001               | [819488216f](https://linux-hardware.org/?probe=819488216f) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| ASUSTek       | FX503VM                     | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| Dell          | Latitude D430               | [7ae462d6f7](https://linux-hardware.org/?probe=7ae462d6f7) | Jul 18, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| Acer          | Aspire E1-532               | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| Samsung       | R59P/R60P/R61P              | [4773de66cf](https://linux-hardware.org/?probe=4773de66cf) | Jul 15, 2022 |
| ASUSTek       | K53SC                       | [dd45175b9d](https://linux-hardware.org/?probe=dd45175b9d) | Jul 15, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [daf43ce57a](https://linux-hardware.org/?probe=daf43ce57a) | Jul 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [4a587952db](https://linux-hardware.org/?probe=4a587952db) | Jul 13, 2022 |
| Apple         | MacBookPro15,3              | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| ASUSTek       | X453MA                      | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | [17b90f7a4b](https://linux-hardware.org/?probe=17b90f7a4b) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | [3b8444274b](https://linux-hardware.org/?probe=3b8444274b) | Jul 10, 2022 |
| Lenovo        | ThinkPad W540 20BG001KGE    | [434091ba07](https://linux-hardware.org/?probe=434091ba07) | Jul 10, 2022 |
| Toshiba       | NB205                       | [f4046cb02f](https://linux-hardware.org/?probe=f4046cb02f) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b2d4e91300](https://linux-hardware.org/?probe=b2d4e91300) | Jul 07, 2022 |
| HP            | Notebook                    | [0c64a91465](https://linux-hardware.org/?probe=0c64a91465) | Jul 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | G50-70 20351                | [68efa303fa](https://linux-hardware.org/?probe=68efa303fa) | Jul 07, 2022 |
| Chuwi         | FreeBook                    | [3e0b057e38](https://linux-hardware.org/?probe=3e0b057e38) | Jul 07, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e5bf9b72d0](https://linux-hardware.org/?probe=e5bf9b72d0) | Jul 07, 2022 |
| Acer          | Aspire E5-571               | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Dell          | Inspiron 5593               | [542470182e](https://linux-hardware.org/?probe=542470182e) | Jul 05, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| ASUSTek       | K53SC                       | [ef75149636](https://linux-hardware.org/?probe=ef75149636) | Jul 03, 2022 |
| Samsung       | 370E4K                      | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Dell          | 500                         | [040e3cb12c](https://linux-hardware.org/?probe=040e3cb12c) | Jun 30, 2022 |
| HP            | EliteBook 840 G3            | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [e08493100f](https://linux-hardware.org/?probe=e08493100f) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [2fa204d33e](https://linux-hardware.org/?probe=2fa204d33e) | Jun 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [bd4018ed46](https://linux-hardware.org/?probe=bd4018ed46) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| ASUSTek       | X551MA                      | [9bdb2a5577](https://linux-hardware.org/?probe=9bdb2a5577) | Jun 28, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Standard      | Unknown                     | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| Apple         | MacBookPro1,1               | [feddac03b9](https://linux-hardware.org/?probe=feddac03b9) | Jun 26, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | [cc52ed5e41](https://linux-hardware.org/?probe=cc52ed5e41) | Jun 26, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| HP            | Laptop 15-ef1xxx            | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Alienware     | 17 R4                       | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| Dell          | Inspiron 15-3567            | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| HP            | 15                          | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Acer          | Aspire 7720                 | [3f098cc493](https://linux-hardware.org/?probe=3f098cc493) | Jun 15, 2022 |
| Dynabook      | TECRA A50-J                 | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| Sony          | VPCSB1V9R                   | [c1490b2a1c](https://linux-hardware.org/?probe=c1490b2a1c) | Jun 14, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 255 G7 Notebook PC          | [0ebaae147d](https://linux-hardware.org/?probe=0ebaae147d) | Jun 12, 2022 |
| GPU Compan... | GWTN141-4                   | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Matsushita... | CF-W5LWEZZBM                | [380c6df037](https://linux-hardware.org/?probe=380c6df037) | Jun 11, 2022 |
| Packard Be... | EasyNote TK11BZ             | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| GPU Compan... | GWTN116-3                   | [bd0f56a43c](https://linux-hardware.org/?probe=bd0f56a43c) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Acer          | Aspire 7720                 | [640b757bc8](https://linux-hardware.org/?probe=640b757bc8) | Jun 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [674cab9d61](https://linux-hardware.org/?probe=674cab9d61) | Jun 08, 2022 |
| Lenovo        | ThinkPad L380 20M6S4J400    | [dc1bcd1532](https://linux-hardware.org/?probe=dc1bcd1532) | Jun 08, 2022 |
| Acer          | Aspire E5-573               | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | [ac4362743a](https://linux-hardware.org/?probe=ac4362743a) | Jun 07, 2022 |
| AMI           | Intel                       | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [c4250d2ee2](https://linux-hardware.org/?probe=c4250d2ee2) | Jun 07, 2022 |
| Fujitsu       | LIFEBOOK U772               | [8dcf195f94](https://linux-hardware.org/?probe=8dcf195f94) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [3ee16e0227](https://linux-hardware.org/?probe=3ee16e0227) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| MSI           | PR601/VR603                 | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Inspiron N4010              | [49e472d67e](https://linux-hardware.org/?probe=49e472d67e) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Dell          | Latitude D820               | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Lenovo        | ThinkPad L13 20R4S4WG00     | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| Medion        | E15407                      | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| TUXEDO        | N14xWU                      | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X510UA                      | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Google        | Snappy                      | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| IBM           | ThinkPad T43 2668F5G        | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Dell          | Latitude D610               | [2e945626d4](https://linux-hardware.org/?probe=2e945626d4) | May 17, 2022 |
| Dell          | Latitude D610               | [9ee1df5d0e](https://linux-hardware.org/?probe=9ee1df5d0e) | May 17, 2022 |
| Dell          | Latitude E6410              | [ae757ea3a4](https://linux-hardware.org/?probe=ae757ea3a4) | May 16, 2022 |
| ASUSTek       | UL30A                       | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| ASUSTek       | X101CH                      | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| HP            | Mini 110-1100               | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| Dell          | Latitude 5580               | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| Google        | Droid                       | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| AMI           | Cherry Trail CR             | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | A7K                         | [29ca1c7e33](https://linux-hardware.org/?probe=29ca1c7e33) | May 11, 2022 |
| Dell          | Latitude E6410              | [a14c28c93f](https://linux-hardware.org/?probe=a14c28c93f) | May 11, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Unknown       | Unknown                     | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| Dell          | Latitude E6410              | [361bcaa4cc](https://linux-hardware.org/?probe=361bcaa4cc) | May 07, 2022 |
| Dell          | Inspiron 7501               | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| HP            | Compaq 6820s                | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| Toshiba       | Satellite C70D-B            | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Acer          | Aspire 5740                 | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| Dell          | Latitude 7420               | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Dell          | XPS M1530                   | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASUSTek       | K53SC                       | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| Acer          | Aspire 5740                 | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| Razer         | Blade Stealth 13 Late 20... | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Acer          | Aspire 5740                 | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | XPS M1530                   | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| ASUSTek       | K53SC                       | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Acer          | Aspire ES1-311              | [aa4612575b](https://linux-hardware.org/?probe=aa4612575b) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| Dell          | Inspiron 3135               | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| Acer          | Aspire ES1-512              | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Dell          | Latitude 7480               | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Dell          | XPS M1530                   | [f22a6a2c55](https://linux-hardware.org/?probe=f22a6a2c55) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| HP            | 255 G8 Notebook PC          | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| Dell          | XPS M1530                   | [60d3e4f97f](https://linux-hardware.org/?probe=60d3e4f97f) | Apr 20, 2022 |
| HP            | Compaq 6730s                | [4902d2bf25](https://linux-hardware.org/?probe=4902d2bf25) | Apr 16, 2022 |
| Positivo B... | VJC141F11X-B0111L           | [5ea499eca7](https://linux-hardware.org/?probe=5ea499eca7) | Apr 16, 2022 |
| Dell          | Latitude E6540              | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| HP            | Compaq 6730s                | [755dcc7629](https://linux-hardware.org/?probe=755dcc7629) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Dell          | Precision 7550              | [624c231f19](https://linux-hardware.org/?probe=624c231f19) | Apr 13, 2022 |
| Lenovo        | IdeaPad Y550 4186           | [0ba7d3b80a](https://linux-hardware.org/?probe=0ba7d3b80a) | Apr 13, 2022 |
| HP            | Laptop 15-bw0xx             | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| Dell          | OptiPlex 9020               | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | K53SC                       | [8b6bb16303](https://linux-hardware.org/?probe=8b6bb16303) | Apr 08, 2022 |
| Toshiba       | NB505                       | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| Dell          | Latitude 5521               | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Xubuntu 20.04        | 1039      | 42.12%  |
| Xubuntu 18.04        | 611       | 24.77%  |
| Xubuntu 22.04        | 389       | 15.77%  |
| Xubuntu 19.10        | 110       | 4.46%   |
| Xubuntu 21.10        | 57        | 2.31%   |
| Xubuntu 16.04        | 50        | 2.03%   |
| Xubuntu 21.04        | 42        | 1.7%    |
| Xubuntu 20.10        | 42        | 1.7%    |
| Xubuntu 23.04        | 35        | 1.42%   |
| Xubuntu 22.10        | 30        | 1.22%   |
| Xubuntu 23.10        | 23        | 0.93%   |
| Xubuntu 19.04        | 13        | 0.53%   |
| Xubuntu 18.10        | 6         | 0.24%   |
| Xubuntu 17.10        | 6         | 0.24%   |
| Xubuntu              | 4         | 0.16%   |
| Xubuntu 14.04        | 3         | 0.12%   |
| Xubuntu 2023.4~rc    | 2         | 0.08%   |
| Xubuntu 2023.2       | 2         | 0.08%   |
| Xubuntu 17.04        | 2         | 0.08%   |
| Xubuntu 2023.1-beta5 | 1         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Xubuntu | 2395      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 87        | 3.11%   |
| 5.3.0-46-generic    | 41        | 1.47%   |
| 5.11.0-27-generic   | 39        | 1.4%    |
| 5.4.0-58-generic    | 34        | 1.22%   |
| 5.4.0-47-generic    | 31        | 1.11%   |
| 5.4.0-52-generic    | 30        | 1.07%   |
| 5.4.0-29-generic    | 30        | 1.07%   |
| 5.4.0-48-generic    | 28        | 1%      |
| 5.4.0-65-generic    | 27        | 0.97%   |
| 5.3.0-40-generic    | 27        | 0.97%   |
| 5.15.0-56-generic   | 27        | 0.97%   |
| 5.3.0-42-generic    | 26        | 0.93%   |
| 5.4.0-54-generic    | 25        | 0.9%    |
| 5.3.0-51-generic    | 22        | 0.79%   |
| 5.4.0-31-generic    | 21        | 0.75%   |
| 5.0.0-37-generic    | 21        | 0.75%   |
| 5.4.0-40-generic    | 20        | 0.72%   |
| 5.15.0-58-generic   | 20        | 0.72%   |
| 6.2.0-26-generic    | 19        | 0.68%   |
| 5.3.0-28-generic    | 19        | 0.68%   |
| 5.15.0-52-generic   | 19        | 0.68%   |
| 5.15.0-47-generic   | 19        | 0.68%   |
| 4.15.0-99-generic   | 19        | 0.68%   |
| 5.4.0-42-lowlatency | 18        | 0.64%   |
| 5.4.0-26-generic    | 18        | 0.64%   |
| 5.3.0-53-generic    | 18        | 0.64%   |
| 5.15.0-48-generic   | 18        | 0.64%   |
| 5.4.0-89-generic    | 17        | 0.61%   |
| 5.4.0-66-generic    | 17        | 0.61%   |
| 5.4.0-67-generic    | 16        | 0.57%   |
| 5.4.0-53-generic    | 16        | 0.57%   |
| 5.4.0-37-generic    | 16        | 0.57%   |
| 5.13.0-39-generic   | 16        | 0.57%   |
| 5.13.0-30-generic   | 16        | 0.57%   |
| 5.8.0-53-generic    | 15        | 0.54%   |
| 5.8.0-43-generic    | 15        | 0.54%   |
| 5.4.0-56-generic    | 15        | 0.54%   |
| 5.4.0-72-generic    | 14        | 0.5%    |
| 5.4.0-60-generic    | 14        | 0.5%    |
| 5.4.0-33-generic    | 14        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 845       | 33.55%  |
| 5.15.0  | 292       | 11.59%  |
| 5.3.0   | 258       | 10.24%  |
| 4.15.0  | 251       | 9.96%   |
| 5.11.0  | 167       | 6.63%   |
| 5.13.0  | 133       | 5.28%   |
| 5.8.0   | 132       | 5.24%   |
| 6.2.0   | 99        | 3.93%   |
| 5.19.0  | 86        | 3.41%   |
| 5.0.0   | 57        | 2.26%   |
| 6.5.0   | 32        | 1.27%   |
| 4.4.0   | 27        | 1.07%   |
| 4.18.0  | 14        | 0.56%   |
| 5.17.0  | 10        | 0.4%    |
| 4.13.0  | 7         | 0.28%   |
| 6.1.0   | 6         | 0.24%   |
| 5.10.0  | 5         | 0.2%    |
| 5.14.0  | 4         | 0.16%   |
| 5.6.0   | 3         | 0.12%   |
| 5.4.217 | 3         | 0.12%   |
| 5.18.0  | 3         | 0.12%   |
| 6.0.9   | 2         | 0.08%   |
| 6.0.0   | 2         | 0.08%   |
| 5.6.19  | 2         | 0.08%   |
| 5.5.19  | 2         | 0.08%   |
| 5.11.11 | 2         | 0.08%   |
| 4.8.0   | 2         | 0.08%   |
| 4.4.254 | 2         | 0.08%   |
| 4.11.0  | 2         | 0.08%   |
| 4.10.0  | 2         | 0.08%   |
| 6.6.7   | 1         | 0.04%   |
| 6.5.5   | 1         | 0.04%   |
| 6.5.1   | 1         | 0.04%   |
| 6.4.2   | 1         | 0.04%   |
| 6.4.15  | 1         | 0.04%   |
| 6.4.0   | 1         | 0.04%   |
| 6.3.2   | 1         | 0.04%   |
| 6.2.2   | 1         | 0.04%   |
| 6.1.6   | 1         | 0.04%   |
| 6.0.7   | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 852       | 33.84%  |
| 5.15    | 295       | 11.72%  |
| 5.3     | 260       | 10.33%  |
| 4.15    | 252       | 10.01%  |
| 5.11    | 173       | 6.87%   |
| 5.13    | 134       | 5.32%   |
| 5.8     | 133       | 5.28%   |
| 6.2     | 100       | 3.97%   |
| 5.19    | 88        | 3.49%   |
| 5.0     | 58        | 2.3%    |
| 6.5     | 34        | 1.35%   |
| 4.4     | 29        | 1.15%   |
| 4.18    | 14        | 0.56%   |
| 5.17    | 11        | 0.44%   |
| 5.10    | 11        | 0.44%   |
| 5.14    | 8         | 0.32%   |
| 6.1     | 7         | 0.28%   |
| 5.6     | 7         | 0.28%   |
| 4.13    | 7         | 0.28%   |
| 6.0     | 5         | 0.2%    |
| 5.7     | 5         | 0.2%    |
| 4.19    | 5         | 0.2%    |
| 5.9     | 4         | 0.16%   |
| 5.12    | 4         | 0.16%   |
| 6.4     | 3         | 0.12%   |
| 5.18    | 3         | 0.12%   |
| 5.5     | 2         | 0.08%   |
| 5.16    | 2         | 0.08%   |
| 4.8     | 2         | 0.08%   |
| 4.11    | 2         | 0.08%   |
| 4.10    | 2         | 0.08%   |
| 6.6     | 1         | 0.04%   |
| 6.3     | 1         | 0.04%   |
| 4.20    | 1         | 0.04%   |
| 4.14    | 1         | 0.04%   |
| 4.12    | 1         | 0.04%   |
| 3.13    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2050      | 85.49%  |
| i686   | 348       | 14.51%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 2317      | 96.58%  |
| GNOME           | 54        | 2.25%   |
| i3              | 8         | 0.33%   |
| Unicorn:XFCE    | 4         | 0.17%   |
| KDE5            | 4         | 0.17%   |
| Unity           | 3         | 0.13%   |
| MATE            | 2         | 0.08%   |
| Cinnamon        | 2         | 0.08%   |
| xmonad          | 1         | 0.04%   |
| ICEWM           | 1         | 0.04%   |
| GNUstep         | 1         | 0.04%   |
| GNOME Flashback | 1         | 0.04%   |
| awesome         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2366      | 98.75%  |
| Tty     | 15        | 0.63%   |
| Wayland | 14        | 0.58%   |
| Unknown | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1144      | 46.32%  |
| LightDM | 960       | 38.87%  |
| TDM     | 284       | 11.5%   |
| GDM3    | 44        | 1.78%   |
| GDM     | 22        | 0.89%   |
| SDDM    | 12        | 0.49%   |
| SLiM    | 2         | 0.08%   |
| XDM     | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 819       | 34.08%  |
| de_DE   | 244       | 10.15%  |
| fr_FR   | 217       | 9.03%   |
| it_IT   | 186       | 7.74%   |
| pt_BR   | 112       | 4.66%   |
| ru_RU   | 97        | 4.04%   |
| en_GB   | 97        | 4.04%   |
| C       | 84        | 3.5%    |
| es_ES   | 69        | 2.87%   |
| Unknown | 43        | 1.79%   |
| pl_PL   | 41        | 1.71%   |
| en_CA   | 36        | 1.5%    |
| en_AU   | 30        | 1.25%   |
| cs_CZ   | 24        | 1%      |
| hu_HU   | 20        | 0.83%   |
| en_IN   | 19        | 0.79%   |
| es_AR   | 18        | 0.75%   |
| nl_NL   | 17        | 0.71%   |
| es_MX   | 15        | 0.62%   |
| ja_JP   | 14        | 0.58%   |
| pt_PT   | 11        | 0.46%   |
| tr_TR   | 10        | 0.42%   |
| ru_UA   | 10        | 0.42%   |
| el_GR   | 10        | 0.42%   |
| fr_BE   | 9         | 0.37%   |
| fi_FI   | 9         | 0.37%   |
| sk_SK   | 8         | 0.33%   |
| es_CO   | 8         | 0.33%   |
| en_ZA   | 8         | 0.33%   |
| sv_SE   | 7         | 0.29%   |
| es_CL   | 7         | 0.29%   |
| de_CH   | 7         | 0.29%   |
| zh_CN   | 6         | 0.25%   |
| nl_BE   | 6         | 0.25%   |
| es_VE   | 5         | 0.21%   |
| de_AT   | 5         | 0.21%   |
| ca_ES   | 5         | 0.21%   |
| bg_BG   | 5         | 0.21%   |
| uk_UA   | 4         | 0.17%   |
| nb_NO   | 4         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1466      | 60.68%  |
| EFI  | 950       | 39.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2129      | 87.98%  |
| Overlay | 109       | 4.5%    |
| Tmpfs   | 95        | 3.93%   |
| Btrfs   | 38        | 1.57%   |
| Zfs     | 21        | 0.87%   |
| Unknown | 12        | 0.5%    |
| Xfs     | 6         | 0.25%   |
| Ext3    | 5         | 0.21%   |
| Ext2    | 4         | 0.17%   |
| Ufs     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1379      | 56.63%  |
| GPT     | 745       | 30.6%   |
| MBR     | 311       | 12.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2147      | 87.99%  |
| Yes       | 293       | 12.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1681      | 69.32%  |
| Yes       | 744       | 30.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 478       | 19.96%  |
| Lenovo              | 437       | 18.25%  |
| Dell                | 321       | 13.4%   |
| ASUSTek Computer    | 266       | 11.11%  |
| Acer                | 238       | 9.94%   |
| Toshiba             | 104       | 4.34%   |
| Samsung Electronics | 59        | 2.46%   |
| Sony                | 52        | 2.17%   |
| Apple               | 47        | 1.96%   |
| MSI                 | 39        | 1.63%   |
| Medion              | 27        | 1.13%   |
| Fujitsu Siemens     | 27        | 1.13%   |
| Google              | 26        | 1.09%   |
| Packard Bell        | 20        | 0.84%   |
| Notebook            | 17        | 0.71%   |
| Fujitsu             | 17        | 0.71%   |
| Clevo               | 15        | 0.63%   |
| HUAWEI              | 14        | 0.58%   |
| Unknown             | 13        | 0.54%   |
| Positivo            | 10        | 0.42%   |
| GPU Company         | 9         | 0.38%   |
| Gateway             | 9         | 0.38%   |
| Intel               | 8         | 0.33%   |
| IBM                 | 7         | 0.29%   |
| TUXEDO              | 6         | 0.25%   |
| eMachines           | 6         | 0.25%   |
| LG Electronics      | 5         | 0.21%   |
| Dynabook            | 5         | 0.21%   |
| Alienware           | 5         | 0.21%   |
| Schenker            | 4         | 0.17%   |
| Itautec             | 4         | 0.17%   |
| AMI                 | 4         | 0.17%   |
| Semp Toshiba        | 3         | 0.13%   |
| OEM                 | 3         | 0.13%   |
| Gigabyte Technology | 3         | 0.13%   |
| Dixonsxp            | 3         | 0.13%   |
| Chuwi               | 3         | 0.13%   |
| Thomson             | 2         | 0.08%   |
| System76            | 2         | 0.08%   |
| SiComputer          | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 33        | 1.38%   |
| HP Pavilion dv6                        | 20        | 0.84%   |
| HP Notebook                            | 17        | 0.71%   |
| Dell Latitude D630                     | 11        | 0.46%   |
| HP Pavilion 15                         | 10        | 0.42%   |
| HP 15                                  | 10        | 0.42%   |
| HP Pavilion g6                         | 9         | 0.38%   |
| Dell Latitude E6430                    | 9         | 0.38%   |
| HP Pavilion dv7                        | 8         | 0.33%   |
| HP Pavilion dv6500                     | 7         | 0.29%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.25%   |
| HP Pavilion 17                         | 5         | 0.21%   |
| HP EliteBook 840 G3                    | 5         | 0.21%   |
| Dell Latitude E6520                    | 5         | 0.21%   |
| Dell Latitude E6400                    | 5         | 0.21%   |
| Dell Latitude E6330                    | 5         | 0.21%   |
| Dell Inspiron 1525                     | 5         | 0.21%   |
| Dell Inspiron 15-3567                  | 5         | 0.21%   |
| ASUS T100HAN                           | 5         | 0.21%   |
| ASUS 1005HA                            | 5         | 0.21%   |
| Acer Aspire one                        | 5         | 0.21%   |
| Acer AO751h                            | 5         | 0.21%   |
| Positivo Mobile                        | 4         | 0.17%   |
| HP ProBook 6570b                       | 4         | 0.17%   |
| HP Pavilion g7                         | 4         | 0.17%   |
| HP Laptop 15-bw0xx                     | 4         | 0.17%   |
| HP G62                                 | 4         | 0.17%   |
| HP G42                                 | 4         | 0.17%   |
| HP EliteBook 8560p                     | 4         | 0.17%   |
| HP EliteBook 820 G3                    | 4         | 0.17%   |
| HP Compaq Presario CQ60                | 4         | 0.17%   |
| HP Compaq Presario C700                | 4         | 0.17%   |
| HP Compaq 6730s                        | 4         | 0.17%   |
| HP 255 G7 Notebook PC                  | 4         | 0.17%   |
| Google Snappy                          | 4         | 0.17%   |
| Dell Studio 1535                       | 4         | 0.17%   |
| Dell Latitude E6420                    | 4         | 0.17%   |
| Dell Latitude E6410                    | 4         | 0.17%   |
| Dell Inspiron 7520                     | 4         | 0.17%   |
| Dell Inspiron 1545                     | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 265       | 11.06%  |
| Acer Aspire             | 158       | 6.6%    |
| Dell Latitude           | 139       | 5.8%    |
| HP Pavilion             | 116       | 4.84%   |
| Dell Inspiron           | 104       | 4.34%   |
| Toshiba Satellite       | 88        | 3.67%   |
| Lenovo IdeaPad          | 80        | 3.34%   |
| HP EliteBook            | 61        | 2.55%   |
| HP Compaq               | 50        | 2.09%   |
| HP ProBook              | 49        | 2.05%   |
| HP Laptop               | 43        | 1.8%    |
| ASUS VivoBook           | 40        | 1.67%   |
| Unknown                 | 33        | 1.38%   |
| Dell XPS                | 21        | 0.88%   |
| Dell Vostro             | 20        | 0.84%   |
| HP Notebook             | 18        | 0.75%   |
| Acer Extensa            | 18        | 0.75%   |
| Dell Precision          | 16        | 0.67%   |
| Packard Bell EasyNote   | 15        | 0.63%   |
| Fujitsu Siemens AMILO   | 15        | 0.63%   |
| Fujitsu LIFEBOOK        | 15        | 0.63%   |
| HP Presario             | 13        | 0.54%   |
| HP Mini                 | 11        | 0.46%   |
| HP 255                  | 11        | 0.46%   |
| HP 15                   | 11        | 0.46%   |
| Acer TravelMate         | 11        | 0.46%   |
| HP ZBook                | 10        | 0.42%   |
| HP Stream               | 10        | 0.42%   |
| HP 250                  | 10        | 0.42%   |
| ASUS ROG                | 9         | 0.38%   |
| ASUS ASUS               | 9         | 0.38%   |
| Acer Swift              | 9         | 0.38%   |
| HP ENVY                 | 8         | 0.33%   |
| Dell Studio             | 7         | 0.29%   |
| Acer Nitro              | 7         | 0.29%   |
| Toshiba PORTEGE         | 6         | 0.25%   |
| Lenovo ThinkBook        | 6         | 0.25%   |
| IBM ThinkPad            | 6         | 0.25%   |
| Fujitsu Siemens ESPRIMO | 6         | 0.25%   |
| Lenovo Yoga             | 5         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 206       | 8.6%    |
| 2008    | 198       | 8.27%   |
| 2012    | 195       | 8.14%   |
| 2010    | 183       | 7.64%   |
| 2013    | 162       | 6.76%   |
| 2007    | 161       | 6.72%   |
| 2019    | 143       | 5.97%   |
| 2009    | 137       | 5.72%   |
| 2020    | 133       | 5.55%   |
| 2014    | 120       | 5.01%   |
| 2017    | 118       | 4.93%   |
| 2021    | 116       | 4.84%   |
| 2018    | 114       | 4.76%   |
| 2016    | 109       | 4.55%   |
| 2015    | 100       | 4.18%   |
| 2006    | 84        | 3.51%   |
| 2022    | 47        | 1.96%   |
| 2005    | 35        | 1.46%   |
| 2023    | 16        | 0.67%   |
| 2003    | 8         | 0.33%   |
| 2004    | 7         | 0.29%   |
| Unknown | 2         | 0.08%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2395      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2226      | 92.33%  |
| Enabled  | 185       | 7.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2367      | 98.83%  |
| Yes  | 28        | 1.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 708       | 29.27%  |
| 4.01-8.0        | 524       | 21.66%  |
| 1.01-2.0        | 319       | 13.19%  |
| 8.01-16.0       | 274       | 11.33%  |
| 16.01-24.0      | 231       | 9.55%   |
| 0.51-1.0        | 113       | 4.67%   |
| 2.01-3.0        | 103       | 4.26%   |
| 32.01-64.0      | 94        | 3.89%   |
| 64.01-256.0     | 24        | 0.99%   |
| 24.01-32.0      | 21        | 0.87%   |
| 0.01-0.5        | 7         | 0.29%   |
| More than 256.0 | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1066      | 40.83%  |
| 0.51-1.0   | 521       | 19.95%  |
| 2.01-3.0   | 502       | 19.23%  |
| 4.01-8.0   | 203       | 7.77%   |
| 3.01-4.0   | 174       | 6.66%   |
| 0.01-0.5   | 75        | 2.87%   |
| 8.01-16.0  | 58        | 2.22%   |
| 16.01-24.0 | 9         | 0.34%   |
| 24.01-32.0 | 2         | 0.08%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1849      | 76%     |
| 2      | 490       | 20.14%  |
| 3      | 55        | 2.26%   |
| 0      | 28        | 1.15%   |
| 4      | 8         | 0.33%   |
| 5      | 2         | 0.08%   |
| 7      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1222      | 50.92%  |
| Yes       | 1178      | 49.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2070      | 86.32%  |
| No        | 328       | 13.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2336      | 97.37%  |
| No        | 63        | 2.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1508      | 62.24%  |
| No        | 915       | 37.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 339       | 14.05%  |
| Germany     | 307       | 12.72%  |
| France      | 239       | 9.9%    |
| Italy       | 204       | 8.45%   |
| Russia      | 134       | 5.55%   |
| Brazil      | 133       | 5.51%   |
| UK          | 96        | 3.98%   |
| Spain       | 83        | 3.44%   |
| Canada      | 73        | 3.03%   |
| Poland      | 53        | 2.2%    |
| Netherlands | 52        | 2.15%   |
| Czechia     | 38        | 1.57%   |
| Australia   | 36        | 1.49%   |
| Belgium     | 32        | 1.33%   |
| Mexico      | 31        | 1.28%   |
| Ukraine     | 30        | 1.24%   |
| India       | 28        | 1.16%   |
| Argentina   | 26        | 1.08%   |
| Portugal    | 24        | 0.99%   |
| Hungary     | 22        | 0.91%   |
| Greece      | 22        | 0.91%   |
| Finland     | 22        | 0.91%   |
| Sweden      | 21        | 0.87%   |
| Indonesia   | 19        | 0.79%   |
| Turkey      | 18        | 0.75%   |
| Japan       | 18        | 0.75%   |
| Romania     | 16        | 0.66%   |
| Bulgaria    | 16        | 0.66%   |
| Austria     | 16        | 0.66%   |
| Switzerland | 14        | 0.58%   |
| Slovakia    | 12        | 0.5%    |
| Iran        | 12        | 0.5%    |
| Colombia    | 12        | 0.5%    |
| Chile       | 12        | 0.5%    |
| Norway      | 11        | 0.46%   |
| Denmark     | 11        | 0.46%   |
| Belarus     | 10        | 0.41%   |
| Israel      | 9         | 0.37%   |
| Venezuela   | 8         | 0.33%   |
| Philippines | 8         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 35        | 1.37%   |
| Moscow            | 29        | 1.14%   |
| Berlin            | 29        | 1.14%   |
| Rome              | 26        | 1.02%   |
| Milan             | 24        | 0.94%   |
| St Petersburg     | 20        | 0.79%   |
| Warsaw            | 19        | 0.75%   |
| Athens            | 19        | 0.75%   |
| Québec           | 17        | 0.67%   |
| Prague            | 15        | 0.59%   |
| Munich            | 15        | 0.59%   |
| Sao Paulo         | 13        | 0.51%   |
| Amsterdam         | 13        | 0.51%   |
| Madrid            | 12        | 0.47%   |
| Hamburg           | 12        | 0.47%   |
| Budapest          | 12        | 0.47%   |
| Helsinki          | 11        | 0.43%   |
| Barcelona         | 11        | 0.43%   |
| Kyiv              | 10        | 0.39%   |
| Sydney            | 9         | 0.35%   |
| Stuttgart         | 9         | 0.35%   |
| Rio de Janeiro    | 9         | 0.35%   |
| Bucharest         | 9         | 0.35%   |
| Ankara            | 9         | 0.35%   |
| Turin             | 8         | 0.31%   |
| Tehran            | 8         | 0.31%   |
| Melbourne         | 8         | 0.31%   |
| Leipzig           | 8         | 0.31%   |
| Karlsruhe         | 8         | 0.31%   |
| Genoa             | 8         | 0.31%   |
| Frankfurt am Main | 8         | 0.31%   |
| Yokohama          | 7         | 0.27%   |
| Vienna            | 7         | 0.27%   |
| Sofia             | 7         | 0.27%   |
| Lisbon            | 7         | 0.27%   |
| Bogotá           | 7         | 0.27%   |
| Uppsala           | 6         | 0.24%   |
| Toronto           | 6         | 0.24%   |
| Seattle           | 6         | 0.24%   |
| Samara            | 6         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 406       | 497    | 14.42%  |
| Samsung Electronics | 400       | 490    | 14.2%   |
| WDC                 | 346       | 428    | 12.29%  |
| Toshiba             | 254       | 290    | 9.02%   |
| Unknown             | 198       | 256    | 7.03%   |
| Hitachi             | 171       | 200    | 6.07%   |
| Kingston            | 116       | 148    | 4.12%   |
| SanDisk             | 110       | 131    | 3.91%   |
| HGST                | 85        | 98     | 3.02%   |
| SK hynix            | 78        | 98     | 2.77%   |
| Crucial             | 67        | 78     | 2.38%   |
| Intel               | 62        | 81     | 2.2%    |
| Fujitsu             | 62        | 78     | 2.2%    |
| Micron Technology   | 43        | 49     | 1.53%   |
| A-DATA Technology   | 35        | 50     | 1.24%   |
| China               | 31        | 34     | 1.1%    |
| KIOXIA              | 17        | 19     | 0.6%    |
| Transcend           | 15        | 16     | 0.53%   |
| Apple               | 15        | 24     | 0.53%   |
| LITEONIT            | 14        | 17     | 0.5%    |
| LITEON              | 14        | 16     | 0.5%    |
| PNY                 | 13        | 15     | 0.46%   |
| Intenso             | 13        | 13     | 0.46%   |
| Unknown             | 13        | 14     | 0.46%   |
| SPCC                | 12        | 14     | 0.43%   |
| Phison              | 12        | 16     | 0.43%   |
| OCZ                 | 12        | 13     | 0.43%   |
| JMicron Technology  | 9         | 8      | 0.32%   |
| KingSpec            | 8         | 10     | 0.28%   |
| Apacer              | 8         | 10     | 0.28%   |
| Patriot             | 7         | 7      | 0.25%   |
| Netac               | 7         | 11     | 0.25%   |
| KingDian            | 7         | 10     | 0.25%   |
| Silicon Motion      | 6         | 6      | 0.21%   |
| IBM/Hitachi         | 6         | 6      | 0.21%   |
| USB3.0              | 5         | 6      | 0.18%   |
| HUAWEI              | 5         | 5      | 0.18%   |
| Hewlett-Packard     | 5         | 5      | 0.18%   |
| ASMT                | 5         | 10     | 0.18%   |
| Smartbuy            | 4         | 4      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 46        | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 30        | 1.03%   |
| Seagate ST500LT012-1DG142 500GB     | 27        | 0.93%   |
| Toshiba MQ01ABF050 500GB            | 26        | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB      | 24        | 0.83%   |
| Toshiba MQ01ABD100 1TB              | 23        | 0.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 23        | 0.79%   |
| Kingston SA400S37480G 480GB SSD     | 22        | 0.76%   |
| Unknown MMC Card  64GB              | 20        | 0.69%   |
| Seagate ST9320325AS 320GB           | 19        | 0.65%   |
| Kingston SA400S37240G 240GB SSD     | 19        | 0.65%   |
| HGST HTS541010A9E680 1TB            | 19        | 0.65%   |
| Seagate ST9500325AS 500GB           | 18        | 0.62%   |
| HGST HTS721010A9E630 1TB            | 18        | 0.62%   |
| Unknown MMC Card  128GB             | 17        | 0.59%   |
| Seagate ST500LT012-9WS142 500GB     | 16        | 0.55%   |
| Samsung SSD 860 EVO 500GB           | 16        | 0.55%   |
| Samsung SSD 850 EVO 250GB           | 16        | 0.55%   |
| Unknown MMC Card  16GB              | 14        | 0.48%   |
| Toshiba MQ04ABF100 1TB              | 14        | 0.48%   |
| Samsung SSD 850 EVO 500GB           | 14        | 0.48%   |
| Crucial CT240BX500SSD1 240GB        | 14        | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB            | 13        | 0.45%   |
| Kingston SA400S37120G 120GB SSD     | 13        | 0.45%   |
| Unknown                             | 13        | 0.45%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 12        | 0.41%   |
| HGST HTS725050A7E630 500GB          | 12        | 0.41%   |
| SK hynix NVMe SSD Drive 256GB       | 11        | 0.38%   |
| Seagate ST9250315AS 250GB           | 11        | 0.38%   |
| Seagate ST9160310AS 160GB           | 11        | 0.38%   |
| HGST HTS545050A7E680 500GB          | 11        | 0.38%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 10        | 0.34%   |
| Unknown SD/MMC/MS PRO 256GB         | 10        | 0.34%   |
| Seagate ST1000LM048-2E7172 1TB      | 10        | 0.34%   |
| Seagate Expansion 1TB               | 10        | 0.34%   |
| Samsung SSD 860 EVO 1TB             | 10        | 0.34%   |
| Samsung NVMe SSD Drive 512GB        | 10        | 0.34%   |
| Samsung HM321HI 320GB               | 10        | 0.34%   |
| Hitachi HTS543232A7A384 320GB       | 10        | 0.34%   |
| HGST HTS545050A7E380 500GB          | 10        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 400       | 488    | 30.98%  |
| WDC                 | 266       | 334    | 20.6%   |
| Toshiba             | 208       | 240    | 16.11%  |
| Hitachi             | 171       | 200    | 13.25%  |
| HGST                | 85        | 98     | 6.58%   |
| Samsung Electronics | 61        | 70     | 4.73%   |
| Fujitsu             | 60        | 76     | 4.65%   |
| Unknown             | 10        | 12     | 0.77%   |
| IBM/Hitachi         | 6         | 6      | 0.46%   |
| JMicron Technology  | 5         | 5      | 0.39%   |
| TO Exter            | 3         | 3      | 0.23%   |
| SSK                 | 3         | 3      | 0.23%   |
| HGST HTS            | 2         | 2      | 0.15%   |
| External            | 2         | 2      | 0.15%   |
| ASMT                | 2         | 4      | 0.15%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Intenso             | 1         | 1      | 0.08%   |
| Inateck             | 1         | 1      | 0.08%   |
| CLOVER              | 1         | 1      | 0.08%   |
| Apricorn            | 1         | 2      | 0.08%   |
| ACASIS              | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 204       | 259    | 24.03%  |
| Kingston            | 101       | 131    | 11.9%   |
| SanDisk             | 73        | 90     | 8.6%    |
| Crucial             | 64        | 75     | 7.54%   |
| China               | 31        | 34     | 3.65%   |
| A-DATA Technology   | 31        | 46     | 3.65%   |
| WDC                 | 28        | 29     | 3.3%    |
| Micron Technology   | 26        | 28     | 3.06%   |
| Intel               | 23        | 32     | 2.71%   |
| Toshiba             | 21        | 22     | 2.47%   |
| SK hynix            | 20        | 21     | 2.36%   |
| Transcend           | 15        | 15     | 1.77%   |
| LITEONIT            | 14        | 17     | 1.65%   |
| LITEON              | 14        | 16     | 1.65%   |
| PNY                 | 13        | 15     | 1.53%   |
| SPCC                | 12        | 14     | 1.41%   |
| OCZ                 | 12        | 13     | 1.41%   |
| Intenso             | 12        | 12     | 1.41%   |
| Apple               | 9         | 14     | 1.06%   |
| Patriot             | 7         | 7      | 0.82%   |
| KingSpec            | 7         | 9      | 0.82%   |
| KingDian            | 7         | 10     | 0.82%   |
| Apacer              | 7         | 9      | 0.82%   |
| Unknown             | 6         | 7      | 0.71%   |
| Netac               | 5         | 9      | 0.59%   |
| USB3.0              | 4         | 5      | 0.47%   |
| Smartbuy            | 4         | 4      | 0.47%   |
| Pioneer             | 4         | 4      | 0.47%   |
| Hewlett-Packard     | 4         | 5      | 0.47%   |
| GOODRAM             | 4         | 4      | 0.47%   |
| Plextor             | 3         | 9      | 0.35%   |
| Drevo               | 3         | 3      | 0.35%   |
| Dogfish             | 3         | 6      | 0.35%   |
| ASMT                | 3         | 6      | 0.35%   |
| Zheino              | 2         | 2      | 0.24%   |
| Team                | 2         | 7      | 0.24%   |
| TCSUNBOW            | 2         | 2      | 0.24%   |
| SSSTC               | 2         | 2      | 0.24%   |
| Mushkin             | 2         | 2      | 0.24%   |
| Lexar               | 2         | 2      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1251      | 1551   | 46.08%  |
| SSD     | 788       | 1051   | 29.02%  |
| NVMe    | 446       | 543    | 16.43%  |
| MMC     | 198       | 253    | 7.29%   |
| Unknown | 32        | 35     | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1880      | 2511   | 71.56%  |
| NVMe | 445       | 541    | 16.94%  |
| MMC  | 198       | 253    | 7.54%   |
| SAS  | 104       | 128    | 3.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1546      | 2011   | 76.57%  |
| 0.51-1.0   | 419       | 519    | 20.75%  |
| 1.01-2.0   | 43        | 55     | 2.13%   |
| 4.01-10.0  | 5         | 11     | 0.25%   |
| 3.01-4.0   | 4         | 4      | 0.2%    |
| 2.01-3.0   | 1         | 1      | 0.05%   |
| 0          | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 846       | 34.1%   |
| 251-500        | 645       | 26%     |
| 501-1000       | 303       | 12.21%  |
| 51-100         | 241       | 9.71%   |
| 21-50          | 170       | 6.85%   |
| 1-20           | 124       | 5%      |
| 1001-2000      | 95        | 3.83%   |
| More than 3000 | 22        | 0.89%   |
| 2001-3000      | 22        | 0.89%   |
| Unknown        | 13        | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1154      | 44.69%  |
| 21-50          | 481       | 18.63%  |
| 101-250        | 331       | 12.82%  |
| 51-100         | 299       | 11.58%  |
| 251-500        | 161       | 6.24%   |
| 501-1000       | 103       | 3.99%   |
| 1001-2000      | 29        | 1.12%   |
| Unknown        | 13        | 0.5%    |
| 2001-3000      | 6         | 0.23%   |
| More than 3000 | 5         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 8         | 8      | 4.65%   |
| Seagate ST9500325AS 500GB          | 6         | 8      | 3.49%   |
| Toshiba MQ01ABD100 1TB             | 5         | 6      | 2.91%   |
| Seagate ST500LT012-9WS142 500GB    | 5         | 5      | 2.91%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 3      | 1.74%   |
| HGST HTS545050A7E680 500GB         | 3         | 3      | 1.74%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 1.74%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 2      | 1.16%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 3      | 1.16%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 1.16%   |
| Toshiba MK5065GSXN 500GB           | 2         | 4      | 1.16%   |
| Seagate ST9500423AS 500GB          | 2         | 2      | 1.16%   |
| Seagate ST9320325AS 320GB          | 2         | 2      | 1.16%   |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 2      | 1.16%   |
| Samsung Electronics HM321HI 320GB  | 2         | 2      | 1.16%   |
| Hitachi HTS725050A9A364 500GB      | 2         | 3      | 1.16%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.16%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 3      | 1.16%   |
| Hitachi HTS543216L9A300 160GB      | 2         | 2      | 1.16%   |
| Fujitsu MHZ2160BJ FFS G2 160GB     | 2         | 3      | 1.16%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 1      | 0.58%   |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 2      | 0.58%   |
| WDC WD7500BPVT-24HXZT1 752GB       | 1         | 2      | 0.58%   |
| WDC WD7500BPKX-00HPJT0 752GB       | 1         | 1      | 0.58%   |
| WDC WD5000LPVT-08G33T1 500GB       | 1         | 1      | 0.58%   |
| WDC WD5000BEVT-60ZAT1 500GB        | 1         | 1      | 0.58%   |
| WDC WD5000BEKT-75KA9T0 500GB       | 1         | 1      | 0.58%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.58%   |
| WDC WD3200BPVT-35ZEST0 320GB       | 1         | 1      | 0.58%   |
| WDC WD3200BEVT-60ZCT1 320GB        | 1         | 1      | 0.58%   |
| WDC WD3200BEKT-75PVMT0 320GB       | 1         | 1      | 0.58%   |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.58%   |
| WDC WD1600BJKT-75F4T0 160GB        | 1         | 1      | 0.58%   |
| WDC WD1200BEVS-60UST0 120GB        | 1         | 1      | 0.58%   |
| WDC WD10SPCX-24HWST1 1TB           | 1         | 1      | 0.58%   |
| WDC WD10JPVT-08A1YT2 1TB           | 1         | 1      | 0.58%   |
| Toshiba MQ04ABF100 1TB             | 1         | 1      | 0.58%   |
| Toshiba MQ01ACF050 500GB           | 1         | 1      | 0.58%   |
| Toshiba MQ01ABD032 320GB           | 1         | 1      | 0.58%   |
| Toshiba MK7575GSX 752GB            | 1         | 1      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 49     | 26.16%  |
| Toshiba             | 23        | 28     | 13.37%  |
| WDC                 | 20        | 23     | 11.63%  |
| Hitachi             | 19        | 21     | 11.05%  |
| Samsung Electronics | 10        | 10     | 5.81%   |
| HGST                | 8         | 9      | 4.65%   |
| Fujitsu             | 8         | 9      | 4.65%   |
| Kingston            | 5         | 7      | 2.91%   |
| SK hynix            | 4         | 5      | 2.33%   |
| SanDisk             | 4         | 4      | 2.33%   |
| Micron Technology   | 4         | 4      | 2.33%   |
| Intel               | 3         | 3      | 1.74%   |
| OCZ                 | 2         | 2      | 1.16%   |
| LITEON              | 2         | 2      | 1.16%   |
| A-DATA Technology   | 2         | 3      | 1.16%   |
| SSSTC               | 1         | 1      | 0.58%   |
| Netac               | 1         | 1      | 0.58%   |
| Neo Forza           | 1         | 1      | 0.58%   |
| Mushkin             | 1         | 1      | 0.58%   |
| LDLC                | 1         | 1      | 0.58%   |
| KingDian            | 1         | 3      | 0.58%   |
| JMicron Technology  | 1         | 1      | 0.58%   |
| Intenso             | 1         | 1      | 0.58%   |
| Drevo               | 1         | 1      | 0.58%   |
| Crucial             | 1         | 1      | 0.58%   |
| China               | 1         | 1      | 0.58%   |
| Apple               | 1         | 2      | 0.58%   |
| Unknown             | 1         | 1      | 0.58%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 49     | 34.88%  |
| Toshiba             | 23        | 28     | 17.83%  |
| WDC                 | 19        | 22     | 14.73%  |
| Hitachi             | 19        | 21     | 14.73%  |
| HGST                | 8         | 9      | 6.2%    |
| Fujitsu             | 8         | 9      | 6.2%    |
| Samsung Electronics | 6         | 6      | 4.65%   |
| JMicron Technology  | 1         | 1      | 0.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 128       | 145    | 74.85%  |
| SSD  | 40        | 47     | 23.39%  |
| NVMe | 3         | 3      | 1.75%   |

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
| Detected | 1603      | 2314   | 64.35%  |
| Works    | 719       | 924    | 28.86%  |
| Malfunc  | 169       | 195    | 6.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1729      | 68.07%  |
| AMD                              | 296       | 11.65%  |
| Samsung Electronics              | 147       | 5.79%   |
| SanDisk                          | 86        | 3.39%   |
| SK hynix                         | 52        | 2.05%   |
| Nvidia                           | 37        | 1.46%   |
| Silicon Integrated Systems [SiS] | 33        | 1.3%    |
| Toshiba America Info Systems     | 24        | 0.94%   |
| Kingston Technology Company      | 20        | 0.79%   |
| KIOXIA                           | 19        | 0.75%   |
| Micron Technology                | 16        | 0.63%   |
| Phison Electronics               | 15        | 0.59%   |
| VIA Technologies                 | 13        | 0.51%   |
| Silicon Motion                   | 8         | 0.31%   |
| Apple                            | 6         | 0.24%   |
| Micron/Crucial Technology        | 5         | 0.2%    |
| ULi Electronics                  | 4         | 0.16%   |
| Realtek Semiconductor            | 4         | 0.16%   |
| Lenovo                           | 4         | 0.16%   |
| JMicron Technology               | 4         | 0.16%   |
| Union Memory (Shenzhen)          | 3         | 0.12%   |
| Silicon Image                    | 3         | 0.12%   |
| ADATA Technology                 | 3         | 0.12%   |
| Seagate Technology               | 2         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.08%   |
| Lite-On Technology               | 2         | 0.08%   |
| Netac Technology                 | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| Hosin Global Electronics         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 203       | 6.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 183       | 6.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 136       | 4.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 135       | 4.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 132       | 4.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 130       | 4.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 108       | 3.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 103       | 3.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 82        | 2.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 73        | 2.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 72        | 2.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 61        | 2.1%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 56        | 1.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 56        | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 54        | 1.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 51        | 1.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 49        | 1.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 44        | 1.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 42        | 1.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 40        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 40        | 1.37%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 36        | 1.24%   |
| Intel Volume Management Device NVMe RAID Controller                              | 36        | 1.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 34        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 31        | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 31        | 1.07%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 30        | 1.03%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 24        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 24        | 0.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 24        | 0.82%   |
| AMD IXP SB4x0 IDE Controller                                                     | 22        | 0.76%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 20        | 0.69%   |
| AMD SB600 IDE                                                                    | 20        | 0.69%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 19        | 0.65%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 18        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 17        | 0.58%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 17        | 0.58%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 17        | 0.58%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 16        | 0.55%   |
| Intel Comet Lake SATA AHCI Controller                                            | 16        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1681      | 60.82%  |
| IDE  | 493       | 17.84%  |
| NVMe | 440       | 15.92%  |
| RAID | 150       | 5.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2009      | 83.88%  |
| AMD          | 384       | 16.03%  |
| CentaurHauls | 2         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz           | 31        | 1.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 23        | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 23        | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 23        | 0.96%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 23        | 0.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 23        | 0.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 22        | 0.92%   |
| Intel Atom CPU N450 @ 1.66GHz           | 22        | 0.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 0.88%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 21        | 0.88%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 21        | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 20        | 0.83%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 19        | 0.79%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 19        | 0.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 18        | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 18        | 0.75%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 18        | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 17        | 0.71%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz    | 17        | 0.71%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 16        | 0.67%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 16        | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 15        | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 15        | 0.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 15        | 0.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 15        | 0.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 15        | 0.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 15        | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 15        | 0.63%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 15        | 0.63%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 15        | 0.63%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 15        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 14        | 0.58%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 14        | 0.58%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 14        | 0.58%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 14        | 0.58%   |
| Intel Atom CPU N455 @ 1.66GHz           | 14        | 0.58%   |
| Intel Pentium M processor 1.73GHz       | 13        | 0.54%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 13        | 0.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 13        | 0.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 13        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 454       | 18.93%  |
| Intel Core i7           | 360       | 15.01%  |
| Intel Core 2 Duo        | 220       | 9.17%   |
| Intel Celeron           | 203       | 8.47%   |
| Intel Core i3           | 186       | 7.76%   |
| Intel Atom              | 148       | 6.17%   |
| Other                   | 101       | 4.21%   |
| Intel Pentium           | 68        | 2.84%   |
| Intel Genuine           | 56        | 2.34%   |
| AMD Ryzen 5             | 51        | 2.13%   |
| Intel Pentium Dual      | 43        | 1.79%   |
| Intel Pentium Dual-Core | 42        | 1.75%   |
| AMD Ryzen 7             | 40        | 1.67%   |
| Intel Core 2            | 35        | 1.46%   |
| AMD A8                  | 30        | 1.25%   |
| Intel Pentium M         | 29        | 1.21%   |
| AMD E1                  | 28        | 1.17%   |
| Intel Celeron M         | 26        | 1.08%   |
| AMD A6                  | 25        | 1.04%   |
| AMD Turion 64 X2 Mobile | 20        | 0.83%   |
| AMD A4                  | 20        | 0.83%   |
| AMD Ryzen 7 PRO         | 16        | 0.67%   |
| AMD E                   | 16        | 0.67%   |
| AMD E2                  | 15        | 0.63%   |
| AMD Ryzen 3             | 12        | 0.5%    |
| AMD Turion 64 Mobile    | 11        | 0.46%   |
| Intel Pentium Silver    | 9         | 0.38%   |
| AMD Athlon              | 9         | 0.38%   |
| AMD Mobile Sempron      | 8         | 0.33%   |
| AMD A10                 | 8         | 0.33%   |
| Intel Pentium 4         | 7         | 0.29%   |
| Intel Core Duo          | 7         | 0.29%   |
| Intel Celeron Dual-Core | 7         | 0.29%   |
| AMD Ryzen 9             | 7         | 0.29%   |
| AMD Athlon 64 X2        | 7         | 0.29%   |
| AMD C-60                | 6         | 0.25%   |
| Intel Core i9           | 5         | 0.21%   |
| AMD Athlon II           | 5         | 0.21%   |
| AMD Sempron             | 4         | 0.17%   |
| AMD Ryzen 5 PRO         | 4         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1441      | 60.12%  |
| 4      | 540       | 22.53%  |
| 1      | 233       | 9.72%   |
| 6      | 92        | 3.84%   |
| 8      | 65        | 2.71%   |
| 10     | 9         | 0.38%   |
| 12     | 7         | 0.29%   |
| 14     | 6         | 0.25%   |
| 16     | 4         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2395      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1360      | 56.78%  |
| 1      | 1035      | 43.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2225      | 92.86%  |
| 32-bit         | 171       | 7.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 494       | 20.16%  |
| 0x206a7    | 161       | 6.57%   |
| 0x306a9    | 144       | 5.88%   |
| 0x6fd      | 111       | 4.53%   |
| 0x1067a    | 108       | 4.41%   |
| 0x20655    | 77        | 3.14%   |
| 0x40651    | 65        | 2.65%   |
| 0x406e3    | 58        | 2.37%   |
| 0x10676    | 51        | 2.08%   |
| 0x30678    | 47        | 1.92%   |
| 0x106ca    | 46        | 1.88%   |
| 0x806ec    | 45        | 1.84%   |
| 0x806ea    | 45        | 1.84%   |
| 0x306c3    | 44        | 1.8%    |
| 0x806c1    | 42        | 1.71%   |
| 0x406c4    | 42        | 1.71%   |
| 0x106c2    | 42        | 1.71%   |
| 0x306d4    | 41        | 1.67%   |
| 0x20652    | 39        | 1.59%   |
| 0x806e9    | 37        | 1.51%   |
| 0x906ea    | 35        | 1.43%   |
| 0x6e8      | 35        | 1.43%   |
| 0x6d8      | 34        | 1.39%   |
| 0x6f6      | 31        | 1.27%   |
| 0x05000119 | 29        | 1.18%   |
| 0x406c3    | 26        | 1.06%   |
| 0xa0652    | 25        | 1.02%   |
| 0x07030105 | 25        | 1.02%   |
| 0x6ec      | 24        | 0.98%   |
| 0x6fb      | 23        | 0.94%   |
| 0x0700010f | 20        | 0.82%   |
| 0x706a1    | 19        | 0.78%   |
| 0x10661    | 17        | 0.69%   |
| 0x08108109 | 17        | 0.69%   |
| 0x08108102 | 17        | 0.69%   |
| 0x906e9    | 15        | 0.61%   |
| 0x706e5    | 15        | 0.61%   |
| 0x706a8    | 15        | 0.61%   |
| 0x08608103 | 15        | 0.61%   |
| 0x03000027 | 15        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 262       | 10.92%  |
| Core             | 202       | 8.42%   |
| Penryn           | 191       | 7.96%   |
| SandyBridge      | 187       | 7.79%   |
| IvyBridge        | 170       | 7.08%   |
| Westmere         | 138       | 5.75%   |
| Silvermont       | 133       | 5.54%   |
| Haswell          | 133       | 5.54%   |
| Bonnell          | 112       | 4.67%   |
| P6               | 101       | 4.21%   |
| Skylake          | 94        | 3.92%   |
| TigerLake        | 57        | 2.38%   |
| Broadwell        | 54        | 2.25%   |
| K8 Hammer        | 53        | 2.21%   |
| Goldmont plus    | 45        | 1.88%   |
| Bobcat           | 42        | 1.75%   |
| Unknown          | 42        | 1.75%   |
| Zen+             | 38        | 1.58%   |
| CometLake        | 37        | 1.54%   |
| Zen 2            | 34        | 1.42%   |
| Puma             | 34        | 1.42%   |
| IceLake          | 31        | 1.29%   |
| Excavator        | 29        | 1.21%   |
| Jaguar           | 24        | 1%      |
| Zen 3            | 23        | 0.96%   |
| Goldmont         | 21        | 0.88%   |
| K10 Llano        | 17        | 0.71%   |
| Alderlake Hybrid | 17        | 0.71%   |
| Zen              | 14        | 0.58%   |
| Piledriver       | 14        | 0.58%   |
| K10              | 13        | 0.54%   |
| K8 & K10 hybrid  | 12        | 0.5%    |
| NetBurst         | 10        | 0.42%   |
| Steamroller      | 5         | 0.21%   |
| Nehalem          | 5         | 0.21%   |
| Tremont          | 4         | 0.17%   |
| K6               | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1720      | 61.17%  |
| AMD                              | 549       | 19.52%  |
| Nvidia                           | 507       | 18.03%  |
| Silicon Integrated Systems [SiS] | 22        | 0.78%   |
| VIA Technologies                 | 12        | 0.43%   |
| S3 Graphics                      | 1         | 0.04%   |
| ASPEED Technology                | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 173       | 5.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 160       | 5.29%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 130       | 4.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 103       | 3.4%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 94        | 3.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 87        | 2.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 87        | 2.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 77        | 2.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 77        | 2.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 67        | 2.21%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 60        | 1.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 56        | 1.85%   |
| Intel UHD Graphics 620                                                                   | 55        | 1.82%   |
| Intel HD Graphics 620                                                                    | 52        | 1.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 50        | 1.65%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 49        | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 48        | 1.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 45        | 1.49%   |
| Intel HD Graphics 5500                                                                   | 43        | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 1.29%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 37        | 1.22%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 34        | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 1.12%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 33        | 1.09%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 32        | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 28        | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 0.69%   |
| Intel HD Graphics 500                                                                    | 21        | 0.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 21        | 0.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 0.66%   |
| AMD Lucienne                                                                             | 20        | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 19        | 0.63%   |
| Intel HD Graphics 630                                                                    | 18        | 0.6%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 18        | 0.6%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18        | 0.6%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 17        | 0.56%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 16        | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 0.53%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 15        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1318      | 55.01%  |
| 1 x AMD         | 407       | 16.99%  |
| Intel + Nvidia  | 303       | 12.65%  |
| 1 x Nvidia      | 178       | 7.43%   |
| Intel + AMD     | 85        | 3.55%   |
| 2 x AMD         | 31        | 1.29%   |
| AMD + Nvidia    | 26        | 1.09%   |
| 1 x SiS         | 22        | 0.92%   |
| 1 x VIA         | 12        | 0.5%    |
| Other           | 10        | 0.42%   |
| 2 x Intel       | 2         | 0.08%   |
| 1 x S3 Graphics | 1         | 0.04%   |
| Nvidia + ASPEED | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2090      | 86.76%  |
| Proprietary | 235       | 9.76%   |
| Unknown     | 84        | 3.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1438      | 59.3%   |
| 0.01-0.5   | 481       | 19.84%  |
| 1.01-2.0   | 230       | 9.48%   |
| 0.51-1.0   | 142       | 5.86%   |
| 3.01-4.0   | 91        | 3.75%   |
| 5.01-6.0   | 24        | 0.99%   |
| 7.01-8.0   | 10        | 0.41%   |
| 2.01-3.0   | 5         | 0.21%   |
| 8.01-16.0  | 3         | 0.12%   |
| 16.01-24.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 491       | 19.55%  |
| LG Display              | 384       | 15.29%  |
| Samsung Electronics     | 338       | 13.46%  |
| Chimei Innolux          | 248       | 9.88%   |
| BOE                     | 247       | 9.84%   |
| Chi Mei Optoelectronics | 99        | 3.94%   |
| LG Philips              | 75        | 2.99%   |
| Lenovo                  | 74        | 2.95%   |
| Apple                   | 46        | 1.83%   |
| Dell                    | 45        | 1.79%   |
| Goldstar                | 38        | 1.51%   |
| HannStar                | 34        | 1.35%   |
| InfoVision              | 33        | 1.31%   |
| Sharp                   | 32        | 1.27%   |
| CPT                     | 24        | 0.96%   |
| Acer                    | 22        | 0.88%   |
| PANDA                   | 21        | 0.84%   |
| Philips                 | 18        | 0.72%   |
| Hewlett-Packard         | 18        | 0.72%   |
| BenQ                    | 18        | 0.72%   |
| Ancor Communications    | 14        | 0.56%   |
| Sony                    | 13        | 0.52%   |
| ViewSonic               | 11        | 0.44%   |
| Toshiba                 | 11        | 0.44%   |
| Quanta Display          | 11        | 0.44%   |
| Iiyama                  | 10        | 0.4%    |
| CSO                     | 10        | 0.4%    |
| AOC                     | 9         | 0.36%   |
| Seiko/Epson             | 7         | 0.28%   |
| InnoLux Display         | 7         | 0.28%   |
| Panasonic               | 5         | 0.2%    |
| Nvidia                  | 5         | 0.2%    |
| LPL                     | 5         | 0.2%    |
| Vizio                   | 4         | 0.16%   |
| LGD                     | 4         | 0.16%   |
| IBM                     | 4         | 0.16%   |
| Fujitsu Siemens         | 4         | 0.16%   |
| SLD                     | 3         | 0.12%   |
| Lenovo Group Limited    | 3         | 0.12%   |
| KDC                     | 3         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 28        | 1.1%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 23        | 0.91%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 20        | 0.79%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 19        | 0.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 14        | 0.55%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 13        | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.51%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 13        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.47%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 11        | 0.43%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 10        | 0.39%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.39%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 9         | 0.35%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 9         | 0.35%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 9         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 8         | 0.32%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 8         | 0.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 8         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 8         | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 8         | 0.32%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 8         | 0.32%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.32%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 8         | 0.32%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 8         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 7         | 0.28%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 7         | 0.28%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 7         | 0.28%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 7         | 0.28%   |
| InfoVision LCD Monitor IVO03F4 1366x768 344x193mm 15.5-inch              | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch            | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 7         | 0.28%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.24%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 6         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 850       | 35.11%  |
| 1920x1080 (FHD)    | 716       | 29.57%  |
| 1280x800 (WXGA)    | 264       | 10.9%   |
| 1600x900 (HD+)     | 147       | 6.07%   |
| 1440x900 (WXGA+)   | 82        | 3.39%   |
| 1024x600           | 71        | 2.93%   |
| 3840x2160 (4K)     | 59        | 2.44%   |
| 1920x1200 (WUXGA)  | 44        | 1.82%   |
| 1680x1050 (WSXGA+) | 34        | 1.4%    |
| 2560x1440 (QHD)    | 29        | 1.2%    |
| 1280x1024 (SXGA)   | 23        | 0.95%   |
| 1024x768 (XGA)     | 20        | 0.83%   |
| 2560x1600          | 9         | 0.37%   |
| 1360x768           | 7         | 0.29%   |
| 1920x540           | 6         | 0.25%   |
| 3200x1800 (QHD+)   | 5         | 0.21%   |
| 1400x1050          | 5         | 0.21%   |
| 3840x1080          | 4         | 0.17%   |
| 2880x1800          | 4         | 0.17%   |
| 2160x1440          | 4         | 0.17%   |
| Unknown            | 4         | 0.17%   |
| 3840x2400          | 3         | 0.12%   |
| 2560x1080          | 3         | 0.12%   |
| 2288x1287          | 3         | 0.12%   |
| 3440x1440          | 2         | 0.08%   |
| 3000x2000          | 2         | 0.08%   |
| 2304x1440          | 2         | 0.08%   |
| 1600x1200          | 2         | 0.08%   |
| 800x480            | 1         | 0.04%   |
| 3840x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3600x1080          | 1         | 0.04%   |
| 3120x1050          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 2880x1620          | 1         | 0.04%   |
| 2560x1700          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2240x1400          | 1         | 0.04%   |
| 1920x515           | 1         | 0.04%   |
| 1920x1280          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1039      | 41.3%   |
| 14      | 330       | 13.12%  |
| 13      | 278       | 11.05%  |
| 17      | 213       | 8.47%   |
| 12      | 82        | 3.26%   |
| 10      | 74        | 2.94%   |
| 11      | 73        | 2.9%    |
| 24      | 64        | 2.54%   |
| 27      | 55        | 2.19%   |
| 21      | 53        | 2.11%   |
| Unknown | 50        | 1.99%   |
| 23      | 43        | 1.71%   |
| 18      | 28        | 1.11%   |
| 16      | 21        | 0.83%   |
| 19      | 18        | 0.72%   |
| 22      | 13        | 0.52%   |
| 54      | 11        | 0.44%   |
| 31      | 11        | 0.44%   |
| 20      | 8         | 0.32%   |
| 84      | 5         | 0.2%    |
| 40      | 5         | 0.2%    |
| 34      | 5         | 0.2%    |
| 32      | 4         | 0.16%   |
| 8       | 4         | 0.16%   |
| 72      | 3         | 0.12%   |
| 37      | 3         | 0.12%   |
| 26      | 3         | 0.12%   |
| 25      | 3         | 0.12%   |
| 86      | 2         | 0.08%   |
| 52      | 2         | 0.08%   |
| 48      | 2         | 0.08%   |
| 42      | 2         | 0.08%   |
| 74      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |
| 49      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 39      | 1         | 0.04%   |
| 38      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1494      | 59.76%  |
| 201-300     | 367       | 14.68%  |
| 351-400     | 259       | 10.36%  |
| 501-600     | 155       | 6.2%    |
| 401-500     | 99        | 3.96%   |
| Unknown     | 50        | 2%      |
| 1001-1500   | 22        | 0.88%   |
| 601-700     | 20        | 0.8%    |
| 801-900     | 10        | 0.4%    |
| 701-800     | 9         | 0.36%   |
| 1501-2000   | 9         | 0.36%   |
| 101-200     | 4         | 0.16%   |
| 901-1000    | 2         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1752      | 76.44%  |
| 16/10   | 419       | 18.28%  |
| Unknown | 37        | 1.61%   |
| 4/3     | 27        | 1.18%   |
| 5/4     | 21        | 0.92%   |
| 3/2     | 19        | 0.83%   |
| 21/9    | 6         | 0.26%   |
| 32/9    | 3         | 0.13%   |
| 6/5     | 2         | 0.09%   |
| 0.56    | 2         | 0.09%   |
| 3.73    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1036      | 41.24%  |
| 81-90          | 495       | 19.71%  |
| 121-130        | 164       | 6.53%   |
| 201-250        | 139       | 5.53%   |
| 71-80          | 97        | 3.86%   |
| 61-70          | 80        | 3.18%   |
| 41-50          | 74        | 2.95%   |
| 51-60          | 73        | 2.91%   |
| 301-350        | 56        | 2.23%   |
| 151-200        | 51        | 2.03%   |
| Unknown        | 50        | 1.99%   |
| 131-140        | 46        | 1.83%   |
| 141-150        | 28        | 1.11%   |
| More than 1000 | 27        | 1.07%   |
| 91-100         | 22        | 0.88%   |
| 351-500        | 21        | 0.84%   |
| 251-300        | 18        | 0.72%   |
| 501-1000       | 16        | 0.64%   |
| 111-120        | 15        | 0.6%    |
| 1-40           | 4         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 978       | 39.72%  |
| 121-160       | 763       | 30.99%  |
| 51-100        | 510       | 20.71%  |
| 161-240       | 102       | 4.14%   |
| Unknown       | 50        | 2.03%   |
| More than 240 | 31        | 1.26%   |
| 1-50          | 28        | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2045      | 83.71%  |
| 2     | 296       | 12.12%  |
| 0     | 77        | 3.15%   |
| 3     | 23        | 0.94%   |
| 4     | 2         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1170      | 29.67%  |
| Intel                             | 1100      | 27.9%   |
| Qualcomm Atheros                  | 651       | 16.51%  |
| Broadcom                          | 355       | 9%      |
| Marvell Technology Group          | 114       | 2.89%   |
| Broadcom Limited                  | 92        | 2.33%   |
| Ralink                            | 51        | 1.29%   |
| TP-Link                           | 33        | 0.84%   |
| Silicon Integrated Systems [SiS]  | 30        | 0.76%   |
| Nvidia                            | 30        | 0.76%   |
| MediaTek                          | 29        | 0.74%   |
| Ralink Technology                 | 28        | 0.71%   |
| Samsung Electronics               | 25        | 0.63%   |
| JMicron Technology                | 21        | 0.53%   |
| Sierra Wireless                   | 18        | 0.46%   |
| Ericsson Business Mobile Networks | 17        | 0.43%   |
| Huawei Technologies               | 15        | 0.38%   |
| Attansic Technology               | 15        | 0.38%   |
| VIA Technologies                  | 11        | 0.28%   |
| Dell                              | 11        | 0.28%   |
| Xiaomi                            | 8         | 0.2%    |
| Qualcomm Atheros Communications   | 8         | 0.2%    |
| ASIX Electronics                  | 8         | 0.2%    |
| Qualcomm                          | 7         | 0.18%   |
| Lenovo                            | 7         | 0.18%   |
| AMD                               | 7         | 0.18%   |
| Fibocom                           | 6         | 0.15%   |
| DisplayLink                       | 6         | 0.15%   |
| Hewlett-Packard                   | 5         | 0.13%   |
| D-Link System                     | 5         | 0.13%   |
| ZyDAS                             | 4         | 0.1%    |
| ULi Electronics                   | 4         | 0.1%    |
| Motorola PCS                      | 4         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 3         | 0.08%   |
| Toshiba                           | 3         | 0.08%   |
| NetGear                           | 3         | 0.08%   |
| Edimax Technology                 | 3         | 0.08%   |
| D-Link                            | 3         | 0.08%   |
| ASUSTek Computer                  | 3         | 0.08%   |
| Spreadtrum Communications         | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 603       | 12.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 294       | 6.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 118       | 2.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 101       | 2.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 100       | 2.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 90        | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 1.79%   |
| Intel Wireless 7260                                                     | 76        | 1.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 73        | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 72        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 68        | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 67        | 1.41%   |
| Intel Wireless 8265 / 8275                                              | 57        | 1.2%    |
| Intel Wireless 7265                                                     | 57        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 56        | 1.18%   |
| Intel Wi-Fi 6 AX200                                                     | 56        | 1.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 55        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 51        | 1.07%   |
| Intel Wireless 8260                                                     | 50        | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 41        | 0.86%   |
| Intel Wi-Fi 6 AX201                                                     | 38        | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 36        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 36        | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 36        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 35        | 0.74%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 35        | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 32        | 0.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 32        | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 32        | 0.67%   |
| Intel Wireless 3165                                                     | 31        | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 31        | 0.65%   |
| Intel Centrino Advanced-N 6200                                          | 31        | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 30        | 0.63%   |
| Intel Ethernet Connection I219-LM                                       | 30        | 0.63%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 30        | 0.63%   |
| Intel 82577LM Gigabit Network Connection                                | 30        | 0.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 29        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                                | 29        | 0.61%   |
| Intel Centrino Ultimate-N 6300                                          | 27        | 0.57%   |
| Intel WiFi Link 5100                                                    | 26        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1042      | 41.85%  |
| Qualcomm Atheros                      | 562       | 22.57%  |
| Realtek Semiconductor                 | 370       | 14.86%  |
| Broadcom                              | 251       | 10.08%  |
| Ralink                                | 51        | 2.05%   |
| Broadcom Limited                      | 48        | 1.93%   |
| TP-Link                               | 28        | 1.12%   |
| Ralink Technology                     | 28        | 1.12%   |
| MediaTek                              | 25        | 1%      |
| Sierra Wireless                       | 18        | 0.72%   |
| Qualcomm Atheros Communications       | 8         | 0.32%   |
| Qualcomm                              | 7         | 0.28%   |
| Dell                                  | 7         | 0.28%   |
| Fibocom                               | 6         | 0.24%   |
| D-Link System                         | 5         | 0.2%    |
| ZyDAS                                 | 4         | 0.16%   |
| NetGear                               | 3         | 0.12%   |
| Ericsson Business Mobile Networks     | 3         | 0.12%   |
| Edimax Technology                     | 3         | 0.12%   |
| D-Link                                | 3         | 0.12%   |
| Sitecom Europe                        | 2         | 0.08%   |
| Linksys                               | 2         | 0.08%   |
| Hewlett-Packard                       | 2         | 0.08%   |
| ASUSTek Computer                      | 2         | 0.08%   |
| Winbond Electronics                   | 1         | 0.04%   |
| TRENDnet                              | 1         | 0.04%   |
| Toshiba                               | 1         | 0.04%   |
| Texas Instruments                     | 1         | 0.04%   |
| Qcom                                  | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| BUFFALO                               | 1         | 0.04%   |
| Belkin Components                     | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 118       | 4.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 100       | 3.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 90        | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 85        | 3.37%   |
| Intel Wireless 7260                                                           | 76        | 3.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 73        | 2.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 72        | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 68        | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 67        | 2.66%   |
| Intel Wireless 8265 / 8275                                                    | 57        | 2.26%   |
| Intel Wireless 7265                                                           | 57        | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 56        | 2.22%   |
| Intel Wi-Fi 6 AX200                                                           | 56        | 2.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 51        | 2.02%   |
| Intel Wireless 8260                                                           | 50        | 1.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 41        | 1.63%   |
| Intel Wi-Fi 6 AX201                                                           | 38        | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 36        | 1.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 36        | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 35        | 1.39%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 35        | 1.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 32        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 32        | 1.27%   |
| Intel Wireless 3165                                                           | 31        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 31        | 1.23%   |
| Intel Centrino Advanced-N 6200                                                | 31        | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 30        | 1.19%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 29        | 1.15%   |
| Intel Centrino Ultimate-N 6300                                                | 27        | 1.07%   |
| Intel WiFi Link 5100                                                          | 26        | 1.03%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 25        | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 24        | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 22        | 0.87%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 22        | 0.87%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 20        | 0.79%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 20        | 0.79%   |
| Intel Centrino Advanced-N 6235                                                | 20        | 0.79%   |
| Intel Wireless 3160                                                           | 18        | 0.71%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 18        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 17        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1006      | 46.86%  |
| Intel                            | 461       | 21.47%  |
| Qualcomm Atheros                 | 178       | 8.29%   |
| Broadcom                         | 144       | 6.71%   |
| Marvell Technology Group         | 114       | 5.31%   |
| Broadcom Limited                 | 45        | 2.1%    |
| Nvidia                           | 29        | 1.35%   |
| Silicon Integrated Systems [SiS] | 28        | 1.3%    |
| Samsung Electronics              | 24        | 1.12%   |
| JMicron Technology               | 21        | 0.98%   |
| Attansic Technology              | 15        | 0.7%    |
| VIA Technologies                 | 11        | 0.51%   |
| Xiaomi                           | 8         | 0.37%   |
| Huawei Technologies              | 8         | 0.37%   |
| ASIX Electronics                 | 8         | 0.37%   |
| Lenovo                           | 7         | 0.33%   |
| DisplayLink                      | 6         | 0.28%   |
| TP-Link                          | 5         | 0.23%   |
| MediaTek                         | 5         | 0.23%   |
| Motorola PCS                     | 3         | 0.14%   |
| Hewlett-Packard                  | 3         | 0.14%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.09%   |
| Spreadtrum Communications        | 2         | 0.09%   |
| OPPO Electronics                 | 2         | 0.09%   |
| LG Electronics                   | 2         | 0.09%   |
| Apple                            | 2         | 0.09%   |
| ULi Electronics                  | 1         | 0.05%   |
| National Semiconductor           | 1         | 0.05%   |
| Microchip Technology             | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| HTC (High Tech Computer)         | 1         | 0.05%   |
| Foxconn / Hon Hai                | 1         | 0.05%   |
| ASUSTek Computer                 | 1         | 0.05%   |
| Aquantia                         | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 603       | 27.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 294       | 13.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 101       | 4.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 55        | 2.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 36        | 1.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 32        | 1.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 30        | 1.39%   |
| Intel Ethernet Connection I219-LM                                              | 30        | 1.39%   |
| Intel 82577LM Gigabit Network Connection                                       | 30        | 1.39%   |
| Intel 82567LM Gigabit Network Connection                                       | 29        | 1.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 25        | 1.16%   |
| Intel Ethernet Connection I217-LM                                              | 25        | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                                          | 22        | 1.02%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 22        | 1.02%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 20        | 0.93%   |
| Intel 82566MM Gigabit Network Connection                                       | 20        | 0.93%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 19        | 0.88%   |
| Intel Ethernet Connection I218-LM                                              | 19        | 0.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 19        | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 17        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 17        | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 16        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                                          | 16        | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 15        | 0.7%    |
| Intel PRO/100 VE Network Connection                                            | 15        | 0.7%    |
| Broadcom BCM4401-B0 100Base-TX                                                 | 15        | 0.7%    |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 15        | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 13        | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 13        | 0.6%    |
| Nvidia MCP79 Ethernet                                                          | 12        | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 12        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                                           | 12        | 0.56%   |
| Intel Ethernet Connection (10) I219-V                                          | 12        | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 12        | 0.56%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 12        | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 0.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 11        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 11        | 0.51%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 11        | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 11        | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2336      | 52.05%  |
| Ethernet | 2067      | 46.06%  |
| Modem    | 84        | 1.87%   |
| Unknown  | 1         | 0.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1968      | 78.34%  |
| Ethernet | 544       | 21.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1923      | 80.06%  |
| 1     | 413       | 17.19%  |
| 0     | 56        | 2.33%   |
| 3     | 10        | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2021      | 82.93%  |
| Yes  | 416       | 17.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 595       | 39.07%  |
| Realtek Semiconductor           | 151       | 9.91%   |
| Broadcom                        | 151       | 9.91%   |
| Qualcomm Atheros Communications | 146       | 9.59%   |
| Foxconn / Hon Hai               | 65        | 4.27%   |
| Lite-On Technology              | 63        | 4.14%   |
| IMC Networks                    | 58        | 3.81%   |
| Dell                            | 56        | 3.68%   |
| Hewlett-Packard                 | 51        | 3.35%   |
| Apple                           | 40        | 2.63%   |
| Cambridge Silicon Radio         | 35        | 2.3%    |
| Toshiba                         | 21        | 1.38%   |
| ASUSTek Computer                | 17        | 1.12%   |
| Ralink                          | 16        | 1.05%   |
| Alps Electric                   | 14        | 0.92%   |
| Realtek                         | 8         | 0.53%   |
| Foxconn International           | 8         | 0.53%   |
| Ralink Technology               | 7         | 0.46%   |
| MediaTek                        | 4         | 0.26%   |
| Chicony Electronics             | 4         | 0.26%   |
| Taiyo Yuden                     | 3         | 0.2%    |
| Qcom                            | 2         | 0.13%   |
| Micro Star International        | 2         | 0.13%   |
| Integrated System Solution      | 2         | 0.13%   |
| USI                             | 1         | 0.07%   |
| Syntek                          | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |
| Askey Computer                  | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 272       | 17.84%  |
| Realtek Bluetooth Radio                                                             | 99        | 6.49%   |
| Intel AX201 Bluetooth                                                               | 89        | 5.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 73        | 4.79%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 60        | 3.93%   |
| Intel AX200 Bluetooth                                                               | 53        | 3.48%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 39        | 2.56%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 36        | 2.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 35        | 2.3%    |
| Intel Bluetooth Device                                                              | 32        | 2.1%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 32        | 2.1%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 27        | 1.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 25        | 1.64%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 24        | 1.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 22        | 1.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 22        | 1.44%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 20        | 1.31%   |
| Apple Bluetooth Host Controller                                                     | 19        | 1.25%   |
| IMC Networks Bluetooth Device                                                       | 18        | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 17        | 1.11%   |
| Ralink RT3290 Bluetooth                                                             | 16        | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 0.98%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 15        | 0.98%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 15        | 0.98%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 15        | 0.98%   |
| Lite-On Bluetooth Device                                                            | 14        | 0.92%   |
| IMC Networks Bluetooth Radio                                                        | 14        | 0.92%   |
| Dell DW375 Bluetooth Module                                                         | 14        | 0.92%   |
| Broadcom BCM2045 Bluetooth                                                          | 14        | 0.92%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 13        | 0.85%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 13        | 0.85%   |
| Intel AX210 Bluetooth                                                               | 12        | 0.79%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 12        | 0.79%   |
| Toshiba Integrated Bluetooth HCI                                                    | 11        | 0.72%   |
| Realtek RTL8723B Bluetooth                                                          | 11        | 0.72%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 11        | 0.72%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 11        | 0.72%   |
| Apple Bluetooth HCI                                                                 | 11        | 0.72%   |
| Dell Wireless 360 Bluetooth                                                         | 10        | 0.66%   |
| Broadcom HP Portable SoftSailing                                                    | 10        | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1901      | 68.65%  |
| AMD                              | 423       | 15.28%  |
| Nvidia                           | 256       | 9.25%   |
| Silicon Integrated Systems [SiS] | 33        | 1.19%   |
| C-Media Electronics              | 22        | 0.79%   |
| Logitech                         | 15        | 0.54%   |
| VIA Technologies                 | 13        | 0.47%   |
| GN Netcom                        | 9         | 0.33%   |
| Plantronics                      | 7         | 0.25%   |
| Lenovo                           | 7         | 0.25%   |
| Generalplus Technology           | 6         | 0.22%   |
| Texas Instruments                | 5         | 0.18%   |
| Realtek Semiconductor            | 5         | 0.18%   |
| ULi Electronics                  | 4         | 0.14%   |
| M-Audio                          | 4         | 0.14%   |
| JMTek                            | 4         | 0.14%   |
| Focusrite-Novation               | 4         | 0.14%   |
| Textech International            | 3         | 0.11%   |
| ASUSTek Computer                 | 3         | 0.11%   |
| Sennheiser Communications        | 2         | 0.07%   |
| BEHRINGER International          | 2         | 0.07%   |
| Avid Technology                  | 2         | 0.07%   |
| Audio-Technica                   | 2         | 0.07%   |
| Apple                            | 2         | 0.07%   |
| ZOOM                             | 1         | 0.04%   |
| XMOS                             | 1         | 0.04%   |
| Tenx Technology                  | 1         | 0.04%   |
| TEAC                             | 1         | 0.04%   |
| TC Electronic                    | 1         | 0.04%   |
| Syntek                           | 1         | 0.04%   |
| Roland                           | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |
| Razer USA                        | 1         | 0.04%   |
| QinHeng Electronics              | 1         | 0.04%   |
| PreSonus Audio Electronics       | 1         | 0.04%   |
| Numark                           | 1         | 0.04%   |
| Native Instruments               | 1         | 0.04%   |
| Microsoft                        | 1         | 0.04%   |
| Microchip Technology             | 1         | 0.04%   |
| KTMicro                          | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 212       | 6.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 189       | 5.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 184       | 5.66%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 169       | 5.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 145       | 4.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 143       | 4.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 140       | 4.31%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 132       | 4.06%   |
| AMD FCH Azalia Controller                                                                         | 112       | 3.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 78        | 2.4%    |
| Intel 8 Series HD Audio Controller                                                                | 78        | 2.4%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 70        | 2.15%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 68        | 2.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 66        | 2.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 57        | 1.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 55        | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 54        | 1.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 54        | 1.66%   |
| Intel Broadwell-U Audio Controller                                                                | 54        | 1.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 53        | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 48        | 1.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 48        | 1.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 45        | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 45        | 1.38%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 39        | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 39        | 1.2%    |
| Intel Comet Lake PCH cAVS                                                                         | 34        | 1.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 34        | 1.05%   |
| AMD Wrestler HDMI Audio                                                                           | 33        | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 28        | 0.86%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 23        | 0.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 23        | 0.71%   |
| Intel CM238 HD Audio Controller                                                                   | 22        | 0.68%   |
| Nvidia High Definition Audio Controller                                                           | 21        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 21        | 0.65%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 21        | 0.65%   |
| AMD High Definition Audio Controller                                                              | 21        | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 20        | 0.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 0.55%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 17        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 365       | 26.8%   |
| SK hynix                                         | 278       | 20.41%  |
| Unknown                                          | 180       | 13.22%  |
| Micron Technology                                | 137       | 10.06%  |
| Kingston                                         | 114       | 8.37%   |
| Crucial                                          | 60        | 4.41%   |
| Ramaxel Technology                               | 33        | 2.42%   |
| Elpida                                           | 31        | 2.28%   |
| Unknown (ABCD)                                   | 28        | 2.06%   |
| A-DATA Technology                                | 19        | 1.4%    |
| Nanya Technology                                 | 18        | 1.32%   |
| Corsair                                          | 15        | 1.1%    |
| Smart                                            | 14        | 1.03%   |
| G.Skill                                          | 11        | 0.81%   |
| GOODRAM                                          | 6         | 0.44%   |
| Unknown                                          | 5         | 0.37%   |
| Transcend                                        | 4         | 0.29%   |
| 48spaces                                         | 4         | 0.29%   |
| fef5                                             | 3         | 0.22%   |
| Unifosa                                          | 2         | 0.15%   |
| Teikon                                           | 2         | 0.15%   |
| Team                                             | 2         | 0.15%   |
| Super Talent                                     | 2         | 0.15%   |
| Qimonda                                          | 2         | 0.15%   |
| High Bridge                                      | 2         | 0.15%   |
| Avant                                            | 2         | 0.15%   |
| Apacer                                           | 2         | 0.15%   |
| V-GeN                                            | 1         | 0.07%   |
| V-Color                                          | 1         | 0.07%   |
| Unknown (7F7F7F7F7F7F6B00)                       | 1         | 0.07%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.07%   |
| Unknown (0x0043415455000000)                     | 1         | 0.07%   |
| Timetec                                          | 1         | 0.07%   |
| Smart Brazil                                     | 1         | 0.07%   |
| SHARETRONIC                                      | 1         | 0.07%   |
| Patriot                                          | 1         | 0.07%   |
| Neo Forza                                        | 1         | 0.07%   |
| Memox                                            | 1         | 0.07%   |
| Lexar                                            | 1         | 0.07%   |
| Foxline                                          | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 27        | 1.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 21        | 1.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 18        | 1.24%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 17        | 1.17%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 16        | 1.1%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 16        | 1.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 16        | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 15        | 1.03%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 14        | 0.96%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 12        | 0.82%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 12        | 0.82%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 11        | 0.76%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 10        | 0.69%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 10        | 0.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 10        | 0.69%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 10        | 0.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 10        | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 10        | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 9         | 0.62%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 9         | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 9         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 9         | 0.62%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 8         | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 8         | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 8         | 0.55%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 8         | 0.55%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 8         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 7         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 7         | 0.48%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 7         | 0.48%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 7         | 0.48%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 7         | 0.48%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 7         | 0.48%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 7         | 0.48%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 6         | 0.41%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                           | 6         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 6         | 0.41%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 6         | 0.41%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 6         | 0.41%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 6         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 467       | 39.58%  |
| DDR4    | 412       | 34.92%  |
| DDR2    | 122       | 10.34%  |
| LPDDR4  | 65        | 5.51%   |
| SDRAM   | 35        | 2.97%   |
| LPDDR3  | 28        | 2.37%   |
| Unknown | 15        | 1.27%   |
| DDR     | 11        | 0.93%   |
| DDR5    | 10        | 0.85%   |
| DRAM    | 8         | 0.68%   |
| LPDDR5  | 7         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1069      | 91.68%  |
| Row Of Chips | 70        | 6%      |
| Chip         | 11        | 0.94%   |
| Unknown      | 9         | 0.77%   |
| DIMM         | 7         | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 391       | 30.38%  |
| 4096    | 373       | 28.98%  |
| 2048    | 258       | 20.05%  |
| 16384   | 144       | 11.19%  |
| 1024    | 82        | 6.37%   |
| 32768   | 30        | 2.33%   |
| 512     | 6         | 0.47%   |
| 1536    | 1         | 0.08%   |
| 256     | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 298       | 23.95%  |
| 2667    | 201       | 16.16%  |
| 3200    | 165       | 13.26%  |
| 2400    | 85        | 6.83%   |
| 667     | 77        | 6.19%   |
| 1334    | 70        | 5.63%   |
| 1333    | 63        | 5.06%   |
| Unknown | 44        | 3.54%   |
| 2133    | 42        | 3.38%   |
| 800     | 25        | 2.01%   |
| 4199    | 21        | 1.69%   |
| 1067    | 21        | 1.69%   |
| 4267    | 16        | 1.29%   |
| 3266    | 15        | 1.21%   |
| 1066    | 13        | 1.05%   |
| 533     | 12        | 0.96%   |
| 2048    | 11        | 0.88%   |
| 1867    | 11        | 0.88%   |
| 4800    | 10        | 0.8%    |
| 975     | 10        | 0.8%    |
| 6400    | 5         | 0.4%    |
| 4266    | 5         | 0.4%    |
| 333     | 4         | 0.32%   |
| 3733    | 3         | 0.24%   |
| 1866    | 3         | 0.24%   |
| 8400    | 2         | 0.16%   |
| 400     | 2         | 0.16%   |
| 7467    | 1         | 0.08%   |
| 5600    | 1         | 0.08%   |
| 5500    | 1         | 0.08%   |
| 3000    | 1         | 0.08%   |
| 2933    | 1         | 0.08%   |
| 2134    | 1         | 0.08%   |
| 1800    | 1         | 0.08%   |
| 1776    | 1         | 0.08%   |
| 266     | 1         | 0.08%   |
| 133     | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 9         | 36%     |
| Canon                 | 7         | 28%     |
| Brother Industries    | 3         | 12%     |
| Prolific Technology   | 2         | 8%      |
| Xiaomi                | 1         | 4%      |
| Seiko Epson           | 1         | 4%      |
| Lexmark International | 1         | 4%      |
| Kyocera               | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port   | 2         | 7.69%   |
| Xiaomi MiMouse 2                | 1         | 3.85%   |
| Seiko Epson L360 Series         | 1         | 3.85%   |
| Lexmark International E360d     | 1         | 3.85%   |
| Kyocera Mita FS-920             | 1         | 3.85%   |
| HP PSC 750xi                    | 1         | 3.85%   |
| HP OfficeJet Reflash            | 1         | 3.85%   |
| HP LaserJet P1005               | 1         | 3.85%   |
| HP LaserJet 1320                | 1         | 3.85%   |
| HP LaserJet 1020                | 1         | 3.85%   |
| HP LaserJet 1018                | 1         | 3.85%   |
| HP LaserJet 1015                | 1         | 3.85%   |
| HP LaserJet 1012                | 1         | 3.85%   |
| HP DeskJet F2100 Printer series | 1         | 3.85%   |
| HP DeskJet 3700 series          | 1         | 3.85%   |
| Canon TS5100 series             | 1         | 3.85%   |
| Canon TS3300 series             | 1         | 3.85%   |
| Canon TS3100 series             | 1         | 3.85%   |
| Canon PIXMA MX320 series        | 1         | 3.85%   |
| Canon MF3200 series             | 1         | 3.85%   |
| Canon LBP6230/6240              | 1         | 3.85%   |
| Canon LBP6000                   | 1         | 3.85%   |
| Brother MFC-L2710DW series      | 1         | 3.85%   |
| Brother HL-L2320D series        | 1         | 3.85%   |
| Brother HL-2140 series          | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 71.43%  |
| Seiko Epson     | 1         | 14.29%  |
| Hewlett-Packard | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 14.29%  |
| HP ScanJet 3570c                                 | 1         | 14.29%  |
| Canon CanoScan N650U/N656U                       | 1         | 14.29%  |
| Canon CanoScan LIDE 25                           | 1         | 14.29%  |
| Canon CanoScan LiDE 220                          | 1         | 14.29%  |
| Canon CanoScan LiDE 100                          | 1         | 14.29%  |
| Canon CanoScan 4400F                             | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 545       | 27.98%  |
| Microdia                               | 154       | 7.91%   |
| IMC Networks                           | 148       | 7.6%    |
| Realtek Semiconductor                  | 134       | 6.88%   |
| Suyin                                  | 123       | 6.31%   |
| Sunplus Innovation Technology          | 97        | 4.98%   |
| Bison Electronics                      | 89        | 4.57%   |
| Quanta                                 | 77        | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 73        | 3.75%   |
| Acer                                   | 57        | 2.93%   |
| Silicon Motion                         | 44        | 2.26%   |
| Ricoh                                  | 42        | 2.16%   |
| Alcor Micro                            | 42        | 2.16%   |
| Lite-On Technology                     | 40        | 2.05%   |
| Syntek                                 | 39        | 2%      |
| Apple                                  | 37        | 1.9%    |
| Logitech                               | 21        | 1.08%   |
| Samsung Electronics                    | 18        | 0.92%   |
| Luxvisions Innotech Limited            | 17        | 0.87%   |
| Lenovo                                 | 17        | 0.87%   |
| ALi                                    | 17        | 0.87%   |
| Z-Star Microelectronics                | 15        | 0.77%   |
| Primax Electronics                     | 11        | 0.56%   |
| Importek                               | 10        | 0.51%   |
| Sonix Technology                       | 9         | 0.46%   |
| USB Camera                             | 8         | 0.41%   |
| DigiTech                               | 7         | 0.36%   |
| OmniVision Technologies                | 6         | 0.31%   |
| GEMBIRD                                | 5         | 0.26%   |
| USB Camera CS                          | 3         | 0.15%   |
| 8SSC21D67422V1SR3AV5KW1                | 3         | 0.15%   |
| Y Media                                | 2         | 0.1%    |
| Unknown                                | 2         | 0.1%    |
| SunplusIT                              | 2         | 0.1%    |
| Sunplus Technology                     | 2         | 0.1%    |
| OYT Tech                               | 2         | 0.1%    |
| Microsoft                              | 2         | 0.1%    |
| MacroSilicon                           | 2         | 0.1%    |
| Genesys Logic                          | 2         | 0.1%    |
| Cubeternet                             | 2         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 89        | 4.55%   |
| Microdia Integrated_Webcam_HD                    | 40        | 2.04%   |
| Realtek Integrated_Webcam_HD                     | 38        | 1.94%   |
| Chicony HD WebCam                                | 36        | 1.84%   |
| IMC Networks USB2.0 HD UVC WebCam                | 31        | 1.58%   |
| Chicony USB 2.0 Camera                           | 29        | 1.48%   |
| Sunplus Integrated_Webcam_HD                     | 26        | 1.33%   |
| IMC Networks Integrated Camera                   | 24        | 1.23%   |
| Chicony TOSHIBA Web Camera - HD                  | 24        | 1.23%   |
| Realtek USB Camera                               | 21        | 1.07%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 20        | 1.02%   |
| Alcor Micro USB 2.0 Camera                       | 20        | 1.02%   |
| Lite-On Integrated Camera                        | 19        | 0.97%   |
| Chicony HP TrueVision HD                         | 19        | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 19        | 0.97%   |
| Chicony Lenovo EasyCamera                        | 18        | 0.92%   |
| Suyin HP TrueVision HD                           | 17        | 0.87%   |
| Samsung Galaxy series, misc. (MTP mode)          | 17        | 0.87%   |
| Bison Lenovo EasyCamera                          | 17        | 0.87%   |
| Microdia Sonix USB 2.0 Camera                    | 16        | 0.82%   |
| Chicony USB2.0 VGA UVC WebCam                    | 16        | 0.82%   |
| Microdia Integrated Webcam                       | 15        | 0.77%   |
| IMC Networks UVC VGA Webcam                      | 15        | 0.77%   |
| Bison Integrated Camera                          | 15        | 0.77%   |
| Suyin Acer CrystalEye Webcam                     | 14        | 0.72%   |
| Sunplus HD WebCam                                | 14        | 0.72%   |
| Chicony HP HD Camera                             | 14        | 0.72%   |
| Acer SunplusIT Integrated Camera                 | 14        | 0.72%   |
| Quanta HP Webcam                                 | 13        | 0.66%   |
| Quanta HD User Facing                            | 13        | 0.66%   |
| Chicony HP Truevision HD camera                  | 13        | 0.66%   |
| Apple Built-in iSight                            | 13        | 0.66%   |
| Syntek Lenovo EasyCamera                         | 12        | 0.61%   |
| Realtek Lenovo EasyCamera                        | 12        | 0.61%   |
| Chicony USB2.0 Camera                            | 12        | 0.61%   |
| Acer Integrated Camera                           | 12        | 0.61%   |
| Syntek Integrated Camera                         | 11        | 0.56%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 11        | 0.56%   |
| Quanta HP TrueVision HD Camera                   | 11        | 0.56%   |
| Lite-On HP HD Camera                             | 11        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 135       | 36.89%  |
| Synaptics                          | 66        | 18.03%  |
| AuthenTec                          | 57        | 15.57%  |
| Upek                               | 34        | 9.29%   |
| Shenzhen Goodix Technology         | 25        | 6.83%   |
| STMicroelectronics                 | 21        | 5.74%   |
| LighTuning Technology              | 14        | 3.83%   |
| Elan Microelectronics              | 10        | 2.73%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.55%   |
| Samsung Electronics                | 1         | 0.27%   |
| Focal-systems.Corp                 | 1         | 0.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 31        | 8.47%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 8.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 8.2%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 24        | 6.56%   |
| STMicroelectronics Fingerprint Reader                                      | 21        | 5.74%   |
| Shenzhen Goodix  Fingerprint Device                                        | 19        | 5.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 4.92%   |
| AuthenTec AES2810                                                          | 16        | 4.37%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 3.83%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 3.28%   |
| Validity Sensors VFS491                                                    | 11        | 3.01%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 3.01%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 2.73%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 2.46%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 2.19%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.19%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 2.19%   |
| AuthenTec AES1600                                                          | 7         | 1.91%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.37%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.37%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.37%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.09%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.09%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1.09%   |
| Synaptics  WBDI                                                            | 4         | 1.09%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.09%   |
| LighTuning Fingerprint Reader                                              | 4         | 1.09%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.82%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.82%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.55%   |
| Synaptics WBDI Device                                                      | 2         | 0.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.55%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 0.55%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.55%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.55%   |
| Unknown                                                                    | 2         | 0.55%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 77        | 37.56%  |
| Alcor Micro              | 55        | 26.83%  |
| O2 Micro                 | 31        | 15.12%  |
| Upek                     | 17        | 8.29%   |
| Lenovo                   | 17        | 8.29%   |
| Yubico.com               | 1         | 0.49%   |
| Reiner SCT Kartensysteme | 1         | 0.49%   |
| OmniKey                  | 1         | 0.49%   |
| Gemalto (was Gemplus)    | 1         | 0.49%   |
| Clay Logic               | 1         | 0.49%   |
| C3PO                     | 1         | 0.49%   |
| Aktiv                    | 1         | 0.49%   |
| Advanced Card Systems    | 1         | 0.49%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 55        | 26.83%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 16.59%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 11.71%  |
| Broadcom 5880                                                                | 19        | 9.27%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 8.29%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 8.29%   |
| Broadcom 58200                                                               | 12        | 5.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 5.37%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 3.41%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.49%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.49%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.49%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.49%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.49%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.49%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.49%   |
| Aktiv Rutoken lite                                                           | 1         | 0.49%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.49%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1534      | 63.02%  |
| 1     | 703       | 28.88%  |
| 2     | 165       | 6.78%   |
| 3     | 22        | 0.9%    |
| 4     | 6         | 0.25%   |
| 10    | 1         | 0.04%   |
| 8     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 363       | 32.79%  |
| Graphics card            | 230       | 20.78%  |
| Chipcard                 | 195       | 17.62%  |
| Net/wireless             | 86        | 7.77%   |
| Modem                    | 45        | 4.07%   |
| Camera                   | 39        | 3.52%   |
| Bluetooth                | 28        | 2.53%   |
| Storage                  | 26        | 2.35%   |
| Communication controller | 20        | 1.81%   |
| Card reader              | 20        | 1.81%   |
| Flash memory             | 16        | 1.45%   |
| Multimedia controller    | 15        | 1.36%   |
| Sound                    | 8         | 0.72%   |
| Network                  | 5         | 0.45%   |
| Net/ethernet             | 5         | 0.45%   |
| Unassigned class         | 2         | 0.18%   |
| Dvb card                 | 2         | 0.18%   |
| Storage/ide              | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |

