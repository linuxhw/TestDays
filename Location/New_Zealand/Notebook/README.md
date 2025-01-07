Linux in New Zealand - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in New Zealand.

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

Total: 749

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Precision 3571              | [95b1b27d71](https://linux-hardware.org/?probe=95b1b27d71) | Jan 06, 2025 |
| HP            | EliteBook 8460p             | [0a8d680cf0](https://linux-hardware.org/?probe=0a8d680cf0) | Jan 05, 2025 |
| HP            | EliteBook 840 G5            | [ec0eaf35ef](https://linux-hardware.org/?probe=ec0eaf35ef) | Jan 03, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [68304adc38](https://linux-hardware.org/?probe=68304adc38) | Jan 02, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ae6fbefd79](https://linux-hardware.org/?probe=ae6fbefd79) | Jan 01, 2025 |
| HP            | ENVY Notebook               | [b6d4605e3e](https://linux-hardware.org/?probe=b6d4605e3e) | Jan 01, 2025 |
| Dell          | Latitude E6420              | [46c2760e4e](https://linux-hardware.org/?probe=46c2760e4e) | Dec 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [659017d09e](https://linux-hardware.org/?probe=659017d09e) | Dec 06, 2024 |
| HP            | EliteBook 850 G5            | [39d29e9e31](https://linux-hardware.org/?probe=39d29e9e31) | Nov 30, 2024 |
| Lenovo        | ThinkPad Edge 0302CTO       | [453f972762](https://linux-hardware.org/?probe=453f972762) | Nov 26, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [412e0842bc](https://linux-hardware.org/?probe=412e0842bc) | Nov 21, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6cd8e82a85](https://linux-hardware.org/?probe=6cd8e82a85) | Nov 21, 2024 |
| Dell          | Inspiron 5567               | [cb5b5c8c93](https://linux-hardware.org/?probe=cb5b5c8c93) | Nov 16, 2024 |
| Dell          | Latitude 7420               | [5c3fe4e30f](https://linux-hardware.org/?probe=5c3fe4e30f) | Nov 16, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [cc545ad6f0](https://linux-hardware.org/?probe=cc545ad6f0) | Nov 15, 2024 |
| Acer          | E1-510                      | [0d4221de7e](https://linux-hardware.org/?probe=0d4221de7e) | Nov 09, 2024 |
| Apple         | MacBookPro9,1               | [a41e7684ba](https://linux-hardware.org/?probe=a41e7684ba) | Nov 09, 2024 |
| Toshiba       | Satellite L850              | [21b8f6ffc6](https://linux-hardware.org/?probe=21b8f6ffc6) | Nov 07, 2024 |
| Toshiba       | Satellite L850              | [fc40c7d71c](https://linux-hardware.org/?probe=fc40c7d71c) | Nov 03, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [71425bff17](https://linux-hardware.org/?probe=71425bff17) | Oct 29, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [721a42e36b](https://linux-hardware.org/?probe=721a42e36b) | Oct 28, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f57dd2c60b](https://linux-hardware.org/?probe=f57dd2c60b) | Oct 27, 2024 |
| Alienware     | m15 R7                      | [2a1872a750](https://linux-hardware.org/?probe=2a1872a750) | Oct 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a777da34f0](https://linux-hardware.org/?probe=a777da34f0) | Oct 18, 2024 |
| AMD           | Brazos Platform             | [9dd03dc5dc](https://linux-hardware.org/?probe=9dd03dc5dc) | Oct 14, 2024 |
| HP            | Laptop 14-dg0xxx            | [3dc2166f97](https://linux-hardware.org/?probe=3dc2166f97) | Oct 13, 2024 |
| Dell          | Studio 1747                 | [1159e24f15](https://linux-hardware.org/?probe=1159e24f15) | Oct 12, 2024 |
| HP            | ProBook 640 G1              | [20a7878d28](https://linux-hardware.org/?probe=20a7878d28) | Oct 12, 2024 |
| Apple         | MacBookPro9,2               | [5ffe9c3801](https://linux-hardware.org/?probe=5ffe9c3801) | Oct 08, 2024 |
| Apple         | MacBookPro9,2               | [5124f0d14b](https://linux-hardware.org/?probe=5124f0d14b) | Oct 08, 2024 |
| Dell          | XPS 15 9500                 | [92563424c0](https://linux-hardware.org/?probe=92563424c0) | Oct 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [daf78aa588](https://linux-hardware.org/?probe=daf78aa588) | Oct 06, 2024 |
| Fujitsu       | LIFEBOOK U729               | [15f399627a](https://linux-hardware.org/?probe=15f399627a) | Oct 06, 2024 |
| Acer          | Swift SF314-41              | [5049b3c066](https://linux-hardware.org/?probe=5049b3c066) | Oct 06, 2024 |
| Acer          | Aspire A315-51              | [603e00f852](https://linux-hardware.org/?probe=603e00f852) | Sep 28, 2024 |
| Dell          | Inspiron 5565               | [665b2cc68c](https://linux-hardware.org/?probe=665b2cc68c) | Sep 25, 2024 |
| Dell          | Inspiron 5565               | [3763aeacb5](https://linux-hardware.org/?probe=3763aeacb5) | Sep 25, 2024 |
| HP            | Pavilion dv6500             | [f9af2fb181](https://linux-hardware.org/?probe=f9af2fb181) | Sep 19, 2024 |
| Fujitsu       | LIFEBOOK U729               | [94bef52ce4](https://linux-hardware.org/?probe=94bef52ce4) | Sep 15, 2024 |
| Dell          | XPS 15 7590                 | [fc5fb22b68](https://linux-hardware.org/?probe=fc5fb22b68) | Sep 15, 2024 |
| Toshiba       | Satellite S40-B             | [5568883cd6](https://linux-hardware.org/?probe=5568883cd6) | Sep 10, 2024 |
| Apple         | MacBookPro11,3              | [f41e3827ec](https://linux-hardware.org/?probe=f41e3827ec) | Sep 06, 2024 |
| Lenovo        | ThinkPad X131e 33681Q1      | [f3e3569ea0](https://linux-hardware.org/?probe=f3e3569ea0) | Sep 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [27d62581b6](https://linux-hardware.org/?probe=27d62581b6) | Sep 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [264b39ca1e](https://linux-hardware.org/?probe=264b39ca1e) | Sep 02, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | [0a47a5ee51](https://linux-hardware.org/?probe=0a47a5ee51) | Aug 31, 2024 |
| GPD           | G1617-01                    | [a594a51f8f](https://linux-hardware.org/?probe=a594a51f8f) | Aug 31, 2024 |
| Acer          | TravelMate P414-52          | [53e032dfc4](https://linux-hardware.org/?probe=53e032dfc4) | Aug 30, 2024 |
| Lenovo        | ThinkPad P53 20QQS3831V     | [7011c28a17](https://linux-hardware.org/?probe=7011c28a17) | Aug 28, 2024 |
| HP            | EliteBook 840 G5            | [1ef6676af1](https://linux-hardware.org/?probe=1ef6676af1) | Aug 27, 2024 |
| Acer          | TravelMate P414-52          | [f1a981cb7c](https://linux-hardware.org/?probe=f1a981cb7c) | Aug 25, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | [19d17bf64f](https://linux-hardware.org/?probe=19d17bf64f) | Aug 21, 2024 |
| HP            | ENVY 15                     | [49f2ac2a2f](https://linux-hardware.org/?probe=49f2ac2a2f) | Aug 21, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e78c7f9776](https://linux-hardware.org/?probe=e78c7f9776) | Aug 21, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | [5c9e84e6b3](https://linux-hardware.org/?probe=5c9e84e6b3) | Aug 19, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [412b73e5d1](https://linux-hardware.org/?probe=412b73e5d1) | Aug 19, 2024 |
| Fujitsu       | LIFEBOOK U729               | [84c5ee6ec3](https://linux-hardware.org/?probe=84c5ee6ec3) | Aug 18, 2024 |
| HP            | ProBook 450 G6              | [abcd3ebd0f](https://linux-hardware.org/?probe=abcd3ebd0f) | Aug 18, 2024 |
| HP            | ENVY TS 15                  | [5ae88f75d1](https://linux-hardware.org/?probe=5ae88f75d1) | Aug 15, 2024 |
| HP            | ProBook 4740s               | [d515f60fdf](https://linux-hardware.org/?probe=d515f60fdf) | Aug 14, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | [48e265111e](https://linux-hardware.org/?probe=48e265111e) | Aug 13, 2024 |
| HP            | ProBook 650 G1              | [948de2035b](https://linux-hardware.org/?probe=948de2035b) | Aug 13, 2024 |
| Acer          | Aspire A314-31              | [baab264ab4](https://linux-hardware.org/?probe=baab264ab4) | Aug 12, 2024 |
| Dell          | Inspiron 5565               | [f3a59f4478](https://linux-hardware.org/?probe=f3a59f4478) | Aug 11, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [0d1b4d0ac4](https://linux-hardware.org/?probe=0d1b4d0ac4) | Aug 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [8561a6bc16](https://linux-hardware.org/?probe=8561a6bc16) | Aug 09, 2024 |
| Toshiba       | Satellite L850              | [80bf318b30](https://linux-hardware.org/?probe=80bf318b30) | Aug 08, 2024 |
| Dell          | Inspiron N5110              | [7d1f67623f](https://linux-hardware.org/?probe=7d1f67623f) | Aug 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [c0e5b2a4dc](https://linux-hardware.org/?probe=c0e5b2a4dc) | Aug 03, 2024 |
| Lenovo        | ThinkPad Edge 0302CTO       | [3e723d09c8](https://linux-hardware.org/?probe=3e723d09c8) | Aug 02, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [c9e614ecd6](https://linux-hardware.org/?probe=c9e614ecd6) | Aug 01, 2024 |
| Lenovo        | V15-IIL 82C5                | [8dbc443fe5](https://linux-hardware.org/?probe=8dbc443fe5) | Jul 31, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c0b5449d2f](https://linux-hardware.org/?probe=c0b5449d2f) | Jul 30, 2024 |
| HP            | ENVY TS 15                  | [4e23524711](https://linux-hardware.org/?probe=4e23524711) | Jul 29, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [28bdd7232a](https://linux-hardware.org/?probe=28bdd7232a) | Jul 25, 2024 |
| Dell          | Inspiron 3542               | [9a81359405](https://linux-hardware.org/?probe=9a81359405) | Jul 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b1df4c5f37](https://linux-hardware.org/?probe=b1df4c5f37) | Jul 19, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [5a90fa26da](https://linux-hardware.org/?probe=5a90fa26da) | Jul 17, 2024 |
| Samsung       | 300E5E/300E4E/300E5V/300... | [ca43efc3a4](https://linux-hardware.org/?probe=ca43efc3a4) | Jul 14, 2024 |
| Acer          | Aspire ES1-531              | [c2f3d5573c](https://linux-hardware.org/?probe=c2f3d5573c) | Jul 11, 2024 |
| Dell          | XPS 13 9360                 | [155337b9a0](https://linux-hardware.org/?probe=155337b9a0) | Jul 07, 2024 |
| Dell          | XPS 15 9510                 | [475903534b](https://linux-hardware.org/?probe=475903534b) | Jul 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [9fb2474a87](https://linux-hardware.org/?probe=9fb2474a87) | Jul 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3f94cf54c9](https://linux-hardware.org/?probe=3f94cf54c9) | Jul 03, 2024 |
| Toshiba       | Satellite Pro R50-B         | [a4b671dbdc](https://linux-hardware.org/?probe=a4b671dbdc) | Jun 30, 2024 |
| Acer          | Predator PT315-52           | [abaf6fae75](https://linux-hardware.org/?probe=abaf6fae75) | Jun 28, 2024 |
| HP            | EliteBook 2740p             | [a477c0789c](https://linux-hardware.org/?probe=a477c0789c) | Jun 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e028ca3815](https://linux-hardware.org/?probe=e028ca3815) | Jun 27, 2024 |
| Panasonic     | CF53-4                      | [b1bd272cb9](https://linux-hardware.org/?probe=b1bd272cb9) | Jun 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [11bcad49f7](https://linux-hardware.org/?probe=11bcad49f7) | Jun 22, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [918b7fe620](https://linux-hardware.org/?probe=918b7fe620) | Jun 19, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [f5c79b2b42](https://linux-hardware.org/?probe=f5c79b2b42) | Jun 10, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | [dc0057e34a](https://linux-hardware.org/?probe=dc0057e34a) | Jun 04, 2024 |
| Valve         | Galileo                     | [66613e5eb2](https://linux-hardware.org/?probe=66613e5eb2) | May 27, 2024 |
| Lenovo        | G580 20157                  | [618ba27996](https://linux-hardware.org/?probe=618ba27996) | May 26, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9e6346f767](https://linux-hardware.org/?probe=9e6346f767) | May 26, 2024 |
| Lenovo        | ThinkPad E15 20RDS0RD00     | [ff1961961a](https://linux-hardware.org/?probe=ff1961961a) | May 25, 2024 |
| Valve         | Jupiter                     | [f3cac40a5a](https://linux-hardware.org/?probe=f3cac40a5a) | May 25, 2024 |
| HP            | ProBook 430 G7              | [8cce8b33d0](https://linux-hardware.org/?probe=8cce8b33d0) | May 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8c61738c77](https://linux-hardware.org/?probe=8c61738c77) | May 20, 2024 |
| Acer          | Aspire A114-33              | [a72ff8e182](https://linux-hardware.org/?probe=a72ff8e182) | May 19, 2024 |
| HP            | EliteBook 850 G5            | [cabfe742c9](https://linux-hardware.org/?probe=cabfe742c9) | May 15, 2024 |
| Apple         | MacBookPro11,3              | [182ebd66c7](https://linux-hardware.org/?probe=182ebd66c7) | May 12, 2024 |
| Dell          | System XPS L702X            | [fec4b7f7ff](https://linux-hardware.org/?probe=fec4b7f7ff) | May 06, 2024 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [41e3014295](https://linux-hardware.org/?probe=41e3014295) | May 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [cee4dd63f5](https://linux-hardware.org/?probe=cee4dd63f5) | Apr 30, 2024 |
| Lenovo        | ThinkPad T510 4349RW1       | [afaac362f7](https://linux-hardware.org/?probe=afaac362f7) | Apr 28, 2024 |
| HP            | EliteBook 830 G5            | [055d3d55a1](https://linux-hardware.org/?probe=055d3d55a1) | Apr 28, 2024 |
| Acer          | Nitro AN715-51              | [0056e3f773](https://linux-hardware.org/?probe=0056e3f773) | Apr 27, 2024 |
| Lenovo        | ThinkPad T460s 20FAS21A0... | [f8c5a44d3d](https://linux-hardware.org/?probe=f8c5a44d3d) | Apr 27, 2024 |
| HP            | EliteBook 850 G5            | [366a6a7aaf](https://linux-hardware.org/?probe=366a6a7aaf) | Apr 26, 2024 |
| HP            | Laptop 14-bs0xx             | [e403e1c979](https://linux-hardware.org/?probe=e403e1c979) | Apr 19, 2024 |
| HP            | Pavilion x2 Detachable      | [9e5556a266](https://linux-hardware.org/?probe=9e5556a266) | Apr 17, 2024 |
| HP            | EliteBook 8740w             | [39d5987bd0](https://linux-hardware.org/?probe=39d5987bd0) | Apr 13, 2024 |
| HP            | EliteBook 840 G5            | [552cd13a50](https://linux-hardware.org/?probe=552cd13a50) | Apr 12, 2024 |
| HP            | OMEN by Laptop 17-an0xx     | [e236ba52be](https://linux-hardware.org/?probe=e236ba52be) | Apr 10, 2024 |
| Dell          | Latitude 5330               | [3327ec32e4](https://linux-hardware.org/?probe=3327ec32e4) | Apr 06, 2024 |
| Acer          | Nitro AN715-51              | [8f37d9426f](https://linux-hardware.org/?probe=8f37d9426f) | Apr 05, 2024 |
| HP            | ZBook Firefly 14 inch G1... | [5158b23532](https://linux-hardware.org/?probe=5158b23532) | Apr 04, 2024 |
| HP            | EliteBook 8470p             | [9f0fc743f7](https://linux-hardware.org/?probe=9f0fc743f7) | Apr 03, 2024 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [26bfbd7911](https://linux-hardware.org/?probe=26bfbd7911) | Apr 03, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [1120862001](https://linux-hardware.org/?probe=1120862001) | Mar 24, 2024 |
| Apple         | MacBookAir3,2               | [1e9279f941](https://linux-hardware.org/?probe=1e9279f941) | Mar 18, 2024 |
| Dell          | Inspiron 5567               | [3828683188](https://linux-hardware.org/?probe=3828683188) | Mar 17, 2024 |
| Lenovo        | ThinkPad T470 20HES23B0U    | [6b7342964b](https://linux-hardware.org/?probe=6b7342964b) | Mar 16, 2024 |
| MSI           | Alpha 15 A3DD               | [4410e98550](https://linux-hardware.org/?probe=4410e98550) | Mar 11, 2024 |
| Dell          | Latitude 7490               | [93e3272d83](https://linux-hardware.org/?probe=93e3272d83) | Mar 10, 2024 |
| Dell          | Latitude 7490               | [d8c5dd5832](https://linux-hardware.org/?probe=d8c5dd5832) | Mar 09, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | [d7d8cc5cc7](https://linux-hardware.org/?probe=d7d8cc5cc7) | Mar 02, 2024 |
| HP            | Spectre Notebook            | [3530672860](https://linux-hardware.org/?probe=3530672860) | Feb 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [63b1269b5c](https://linux-hardware.org/?probe=63b1269b5c) | Feb 19, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [646a977cdd](https://linux-hardware.org/?probe=646a977cdd) | Jan 30, 2024 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [40e2ad53e8](https://linux-hardware.org/?probe=40e2ad53e8) | Jan 29, 2024 |
| Apple         | MacBookPro14,3              | [1b5bfa9bcb](https://linux-hardware.org/?probe=1b5bfa9bcb) | Jan 28, 2024 |
| HP            | EliteBook 820 G3            | [abc0872688](https://linux-hardware.org/?probe=abc0872688) | Jan 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3d7fcea179](https://linux-hardware.org/?probe=3d7fcea179) | Jan 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b1484cba42](https://linux-hardware.org/?probe=b1484cba42) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cb3946a0b0](https://linux-hardware.org/?probe=cb3946a0b0) | Jan 04, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [db656f3905](https://linux-hardware.org/?probe=db656f3905) | Jan 04, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | [942c025f11](https://linux-hardware.org/?probe=942c025f11) | Dec 31, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [690962312c](https://linux-hardware.org/?probe=690962312c) | Dec 29, 2023 |
| Dell          | Latitude E6430              | [d949738171](https://linux-hardware.org/?probe=d949738171) | Dec 24, 2023 |
| Dell          | Latitude E6430              | [c821d379ec](https://linux-hardware.org/?probe=c821d379ec) | Dec 24, 2023 |
| Toshiba       | Satellite L750              | [8f2f7cd8c9](https://linux-hardware.org/?probe=8f2f7cd8c9) | Dec 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [19e33f2ead](https://linux-hardware.org/?probe=19e33f2ead) | Dec 23, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| Toshiba       | Satellite C50D-C            | [476915f215](https://linux-hardware.org/?probe=476915f215) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [ae7d12ef06](https://linux-hardware.org/?probe=ae7d12ef06) | Dec 17, 2023 |
| HP            | EliteBook 840 G5            | [ee8ea2b093](https://linux-hardware.org/?probe=ee8ea2b093) | Dec 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [f91ead8a19](https://linux-hardware.org/?probe=f91ead8a19) | Dec 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [cedb8ab2b7](https://linux-hardware.org/?probe=cedb8ab2b7) | Dec 10, 2023 |
| Valve         | Jupiter                     | [e6d5beb948](https://linux-hardware.org/?probe=e6d5beb948) | Dec 01, 2023 |
| Dell          | Latitude E6430              | [8b68261a59](https://linux-hardware.org/?probe=8b68261a59) | Nov 30, 2023 |
| Dell          | XPS 13 9360                 | [8a91691d0b](https://linux-hardware.org/?probe=8a91691d0b) | Nov 30, 2023 |
| Apple         | MacBookPro7,1               | [a680e370dc](https://linux-hardware.org/?probe=a680e370dc) | Nov 29, 2023 |
| Apple         | MacBookPro7,1               | [71c73a255e](https://linux-hardware.org/?probe=71c73a255e) | Nov 29, 2023 |
| Toshiba       | TECRA R850                  | [6930db743c](https://linux-hardware.org/?probe=6930db743c) | Nov 24, 2023 |
| Acer          | Nitro AN515-43              | [a9d9ea53da](https://linux-hardware.org/?probe=a9d9ea53da) | Nov 17, 2023 |
| Toshiba       | TECRA R850                  | [9974b99f5a](https://linux-hardware.org/?probe=9974b99f5a) | Nov 16, 2023 |
| Google        | Magolor                     | [375ff87615](https://linux-hardware.org/?probe=375ff87615) | Nov 14, 2023 |
| Google        | Magolor                     | [f287edf382](https://linux-hardware.org/?probe=f287edf382) | Nov 14, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [8415697290](https://linux-hardware.org/?probe=8415697290) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [14ae5dbe92](https://linux-hardware.org/?probe=14ae5dbe92) | Nov 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [bc514556b3](https://linux-hardware.org/?probe=bc514556b3) | Nov 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [aa17167e95](https://linux-hardware.org/?probe=aa17167e95) | Nov 09, 2023 |
| Apple         | MacBookPro9,2               | [1801a9c841](https://linux-hardware.org/?probe=1801a9c841) | Nov 05, 2023 |
| HP            | ProBook 450 G7              | [d1c293b080](https://linux-hardware.org/?probe=d1c293b080) | Oct 26, 2023 |
| Acer          | Aspire VN7-793G             | [e4a7d4f368](https://linux-hardware.org/?probe=e4a7d4f368) | Oct 26, 2023 |
| HP            | 14                          | [3d65da2b45](https://linux-hardware.org/?probe=3d65da2b45) | Oct 08, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [058c6a0ee6](https://linux-hardware.org/?probe=058c6a0ee6) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [bdfa072267](https://linux-hardware.org/?probe=bdfa072267) | Oct 04, 2023 |
| Acer          | Aspire A315-59              | [4c34ba59ba](https://linux-hardware.org/?probe=4c34ba59ba) | Oct 02, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e87fdc15ed](https://linux-hardware.org/?probe=e87fdc15ed) | Sep 29, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [b1333a2976](https://linux-hardware.org/?probe=b1333a2976) | Sep 29, 2023 |
| Gigabyte      | P35V3                       | [573f9ea2f5](https://linux-hardware.org/?probe=573f9ea2f5) | Sep 28, 2023 |
| System76      | Oryx Pro                    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [c4387fc499](https://linux-hardware.org/?probe=c4387fc499) | Sep 24, 2023 |
| HP            | ENVY TS 15                  | [98aa98d974](https://linux-hardware.org/?probe=98aa98d974) | Sep 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [e098daf3a4](https://linux-hardware.org/?probe=e098daf3a4) | Sep 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | [22a0210f8f](https://linux-hardware.org/?probe=22a0210f8f) | Sep 13, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | [4c56913d07](https://linux-hardware.org/?probe=4c56913d07) | Sep 13, 2023 |
| HP            | Notebook                    | [5a36d2a3bf](https://linux-hardware.org/?probe=5a36d2a3bf) | Sep 08, 2023 |
| Dell          | Latitude E5550              | [90fc999e4a](https://linux-hardware.org/?probe=90fc999e4a) | Sep 08, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [a9db40cece](https://linux-hardware.org/?probe=a9db40cece) | Sep 08, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [fc63e4f764](https://linux-hardware.org/?probe=fc63e4f764) | Sep 08, 2023 |
| Acer          | Aspire 5733Z                | [bc3d42d633](https://linux-hardware.org/?probe=bc3d42d633) | Sep 06, 2023 |
| HP            | ProBook 4740s               | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | Pavilion Aero Laptop 13z... | [afa88a8a6a](https://linux-hardware.org/?probe=afa88a8a6a) | Sep 01, 2023 |
| Toshiba       | Satellite C50-B             | [9d05ea660f](https://linux-hardware.org/?probe=9d05ea660f) | Aug 31, 2023 |
| Dell          | 0HD5W2 A00                  | [492d08445d](https://linux-hardware.org/?probe=492d08445d) | Aug 28, 2023 |
| Sony          | VPCEB43FG                   | [99812c6c56](https://linux-hardware.org/?probe=99812c6c56) | Aug 28, 2023 |
| HP            | ProBook 4740s               | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| Dell          | Inspiron 5567               | [76c16d7ffe](https://linux-hardware.org/?probe=76c16d7ffe) | Aug 22, 2023 |
| System76      | Oryx Pro                    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Apple         | MacBookPro5,2               | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| Dell          | 0NKW6Y A00                  | [c48afaf5bd](https://linux-hardware.org/?probe=c48afaf5bd) | Aug 15, 2023 |
| Dell          | 0NKW6Y A00                  | [774306b244](https://linux-hardware.org/?probe=774306b244) | Aug 15, 2023 |
| Dell          | 0NKW6Y A00                  | [14deab8375](https://linux-hardware.org/?probe=14deab8375) | Aug 15, 2023 |
| Alienware     | 15                          | [d6c9c4f931](https://linux-hardware.org/?probe=d6c9c4f931) | Aug 12, 2023 |
| Acer          | Nitro AN715-51              | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| Dell          | Inspiron 3180               | [40c31ab8e5](https://linux-hardware.org/?probe=40c31ab8e5) | Aug 11, 2023 |
| HP            | Beats 15                    | [933bd63249](https://linux-hardware.org/?probe=933bd63249) | Jul 29, 2023 |
| HP            | Beats 15                    | [acea7d6786](https://linux-hardware.org/?probe=acea7d6786) | Jul 29, 2023 |
| Acer          | E1-510                      | [2a83ad14c0](https://linux-hardware.org/?probe=2a83ad14c0) | Jul 27, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [823eca937c](https://linux-hardware.org/?probe=823eca937c) | Jul 24, 2023 |
| HP            | Notebook                    | [1a4ba0be2f](https://linux-hardware.org/?probe=1a4ba0be2f) | Jul 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [0e18492205](https://linux-hardware.org/?probe=0e18492205) | Jul 20, 2023 |
| Toshiba       | TECRA Z50-A                 | [d2b1eef8ac](https://linux-hardware.org/?probe=d2b1eef8ac) | Jul 18, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [2c05f1a964](https://linux-hardware.org/?probe=2c05f1a964) | Jul 16, 2023 |
| Dell          | System XPS L502X            | [e6b4c3cf4e](https://linux-hardware.org/?probe=e6b4c3cf4e) | Jul 12, 2023 |
| HP            | ProBook 470 G5              | [cb6e26bcb4](https://linux-hardware.org/?probe=cb6e26bcb4) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | [37049406c3](https://linux-hardware.org/?probe=37049406c3) | Jul 11, 2023 |
| Apple         | MacBookAir7,2               | [c1d387dfc5](https://linux-hardware.org/?probe=c1d387dfc5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| Toshiba       | Satellite C50D-C            | [ea1fabfdc3](https://linux-hardware.org/?probe=ea1fabfdc3) | Jun 17, 2023 |
| Toshiba       | Satellite C50D-C            | [207d5f5dbd](https://linux-hardware.org/?probe=207d5f5dbd) | Jun 17, 2023 |
| HP            | Laptop 15-bw0xx             | [1b97aa6745](https://linux-hardware.org/?probe=1b97aa6745) | Jun 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | [68a77b486e](https://linux-hardware.org/?probe=68a77b486e) | Jun 09, 2023 |
| ASUSTek       | N750JV                      | [acc54fe70f](https://linux-hardware.org/?probe=acc54fe70f) | Jun 01, 2023 |
| HP            | EliteBook 840 G5            | [4a54b4e82c](https://linux-hardware.org/?probe=4a54b4e82c) | May 28, 2023 |
| HP            | ProBook 4740s               | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| HP            | EliteBook 830 G5            | [b34371b4ba](https://linux-hardware.org/?probe=b34371b4ba) | May 21, 2023 |
| HP            | EliteBook 850 G5            | [1b444989b5](https://linux-hardware.org/?probe=1b444989b5) | May 16, 2023 |
| HP            | EliteBook 830 G5            | [a438db6a33](https://linux-hardware.org/?probe=a438db6a33) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| HP            | Pavilion 15                 | [5a43663b87](https://linux-hardware.org/?probe=5a43663b87) | May 15, 2023 |
| HP            | Pavilion 15                 | [b298e421bb](https://linux-hardware.org/?probe=b298e421bb) | May 15, 2023 |
| HP            | ENVY TS 15                  | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| Apple         | MacBookPro11,3              | [17282aeeb3](https://linux-hardware.org/?probe=17282aeeb3) | May 11, 2023 |
| Acer          | Aspire E1-521               | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| HP            | EliteBook 840 G6            | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [c7308f11ce](https://linux-hardware.org/?probe=c7308f11ce) | May 06, 2023 |
| Google        | Lars                        | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [69d95c7c30](https://linux-hardware.org/?probe=69d95c7c30) | May 02, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [864b1a4325](https://linux-hardware.org/?probe=864b1a4325) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| HP            | Pavilion 15                 | [a8bd7a401e](https://linux-hardware.org/?probe=a8bd7a401e) | Apr 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| Lenovo        | N22 80S6                    | [e915245bfd](https://linux-hardware.org/?probe=e915245bfd) | Apr 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [78c8b8578f](https://linux-hardware.org/?probe=78c8b8578f) | Apr 19, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [41e83eedd0](https://linux-hardware.org/?probe=41e83eedd0) | Apr 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ec36fe087a](https://linux-hardware.org/?probe=ec36fe087a) | Apr 17, 2023 |
| Apple         | MacBookPro5,3               | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Toshiba       | Satellite U940              | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | [488dc3a686](https://linux-hardware.org/?probe=488dc3a686) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | [bf1af4af46](https://linux-hardware.org/?probe=bf1af4af46) | Mar 31, 2023 |
| Apple         | MacBookPro11,3              | [c3f0c2a691](https://linux-hardware.org/?probe=c3f0c2a691) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | [cdb78d0527](https://linux-hardware.org/?probe=cdb78d0527) | Mar 30, 2023 |
| Google        | Swanky                      | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| HP            | ProBook 6550b               | [4629264a10](https://linux-hardware.org/?probe=4629264a10) | Mar 27, 2023 |
| HP            | EliteBook 850 G1            | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| Dell          | Latitude E5570              | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX431FN             | [0185de4fa6](https://linux-hardware.org/?probe=0185de4fa6) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| Acer          | Aspire E1-572               | [bde56e1cc3](https://linux-hardware.org/?probe=bde56e1cc3) | Mar 11, 2023 |
| HP            | Victus by Gaming Laptop ... | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| HP            | Notebook                    | [06e805be3d](https://linux-hardware.org/?probe=06e805be3d) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Valve         | Jupiter                     | [b0b2b55298](https://linux-hardware.org/?probe=b0b2b55298) | Mar 04, 2023 |
| Valve         | Jupiter                     | [da5eea6a75](https://linux-hardware.org/?probe=da5eea6a75) | Mar 03, 2023 |
| Acer          | Aspire F5-573G              | [ce2bc0c00d](https://linux-hardware.org/?probe=ce2bc0c00d) | Feb 27, 2023 |
| HP            | EliteBook 840 14 inch G9... | [8ce6b54b09](https://linux-hardware.org/?probe=8ce6b54b09) | Feb 24, 2023 |
| MSI           | GE63VR 7RF                  | [b9aeb1ce18](https://linux-hardware.org/?probe=b9aeb1ce18) | Feb 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| Dell          | G3 3590                     | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| Dell          | Latitude E6400              | [d9fc10c008](https://linux-hardware.org/?probe=d9fc10c008) | Feb 17, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [d1c4626fd3](https://linux-hardware.org/?probe=d1c4626fd3) | Feb 13, 2023 |
| Dell          | Studio XPS 1640             | [dfb8064df6](https://linux-hardware.org/?probe=dfb8064df6) | Feb 12, 2023 |
| Dell          | Studio XPS 1640             | [deff8d7055](https://linux-hardware.org/?probe=deff8d7055) | Feb 11, 2023 |
| ASUSTek       | UX430UNR                    | [f0b972d056](https://linux-hardware.org/?probe=f0b972d056) | Feb 10, 2023 |
| Dell          | System XPS L702X            | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| HP            | EliteBook 8570p             | [93c3d6c151](https://linux-hardware.org/?probe=93c3d6c151) | Feb 06, 2023 |
| HP            | EliteBook 8540p             | [1614d002e0](https://linux-hardware.org/?probe=1614d002e0) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| Lenovo        | ThinkPad T480 20L5001KAU    | [4b7046e26c](https://linux-hardware.org/?probe=4b7046e26c) | Jan 30, 2023 |
| Acer          | E1-510                      | [659bb96537](https://linux-hardware.org/?probe=659bb96537) | Jan 29, 2023 |
| Gigabyte      | A5 K1                       | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| HP            | Victus by Gaming Laptop ... | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [567ae7f5ba](https://linux-hardware.org/?probe=567ae7f5ba) | Jan 21, 2023 |
| Toshiba       | PORTEGE M780                | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| HP            | ProBook 4740s               | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| HP            | EliteBook 850 G5            | [4afba6f67d](https://linux-hardware.org/?probe=4afba6f67d) | Jan 18, 2023 |
| Sony          | VGN-SR16GN_B                | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| HP            | EliteBook 840 G5            | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| HP            | EliteBook 840 G5            | [bcb3fca0a2](https://linux-hardware.org/?probe=bcb3fca0a2) | Jan 10, 2023 |
| HP            | ZBook Firefly 14 G7 Mobi... | [20bfe72df5](https://linux-hardware.org/?probe=20bfe72df5) | Jan 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444G... | [29331861b5](https://linux-hardware.org/?probe=29331861b5) | Jan 09, 2023 |
| Lenovo        | N22 80S6                    | [a5638d3bf2](https://linux-hardware.org/?probe=a5638d3bf2) | Jan 08, 2023 |
| Lenovo        | N22 80S6                    | [ad72a0fad1](https://linux-hardware.org/?probe=ad72a0fad1) | Jan 08, 2023 |
| Sony          | VGN-Z16GN_B                 | [63bb6c7c43](https://linux-hardware.org/?probe=63bb6c7c43) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [45c8b096c5](https://linux-hardware.org/?probe=45c8b096c5) | Jan 08, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| HP            | ProBook 470 G5              | [aa8715fc5c](https://linux-hardware.org/?probe=aa8715fc5c) | Jan 03, 2023 |
| HP            | ENVY TS 15                  | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| Dell          | Precision 7740              | [952da37737](https://linux-hardware.org/?probe=952da37737) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [d7806eec79](https://linux-hardware.org/?probe=d7806eec79) | Dec 30, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [77390ced3c](https://linux-hardware.org/?probe=77390ced3c) | Dec 24, 2022 |
| Unknown       | Unknown                     | [56781f9824](https://linux-hardware.org/?probe=56781f9824) | Dec 19, 2022 |
| HP            | EliteBook 8460p             | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Google        | Laser14                     | [b07a01ffe4](https://linux-hardware.org/?probe=b07a01ffe4) | Dec 16, 2022 |
| Dell          | Inspiron N5110              | [b333e1030f](https://linux-hardware.org/?probe=b333e1030f) | Dec 16, 2022 |
| HP            | Pavilion dv6                | [d6d4bd4dcd](https://linux-hardware.org/?probe=d6d4bd4dcd) | Dec 14, 2022 |
| HP            | Pavilion dv6                | [2472ce95cb](https://linux-hardware.org/?probe=2472ce95cb) | Dec 14, 2022 |
| Lenovo        | B50-30 20382                | [e2ecbddf15](https://linux-hardware.org/?probe=e2ecbddf15) | Dec 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [3eb157838e](https://linux-hardware.org/?probe=3eb157838e) | Dec 13, 2022 |
| HP            | Laptop 17-bs0xx             | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| Dell          | Inspiron 5459               | [d9cc4844ac](https://linux-hardware.org/?probe=d9cc4844ac) | Dec 12, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [037216f966](https://linux-hardware.org/?probe=037216f966) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [1c27bd3d06](https://linux-hardware.org/?probe=1c27bd3d06) | Dec 03, 2022 |
| Acer          | E1-510                      | [8aadf699f9](https://linux-hardware.org/?probe=8aadf699f9) | Nov 30, 2022 |
| Dell          | G7 7700                     | [16407c6485](https://linux-hardware.org/?probe=16407c6485) | Nov 27, 2022 |
| MSI           | Stealth GS77 12UHS          | [462cb0ce56](https://linux-hardware.org/?probe=462cb0ce56) | Nov 21, 2022 |
| Google        | Swanky                      | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| HP            | ProBook 430 G3              | [e69d9794fd](https://linux-hardware.org/?probe=e69d9794fd) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | [d8bae2c402](https://linux-hardware.org/?probe=d8bae2c402) | Nov 08, 2022 |
| Toshiba       | Satellite C660              | [47ca2c5cb7](https://linux-hardware.org/?probe=47ca2c5cb7) | Nov 06, 2022 |
| Unknown       | Unknown                     | [6702cb2ca7](https://linux-hardware.org/?probe=6702cb2ca7) | Oct 25, 2022 |
| Google        | Swanky                      | [375d986028](https://linux-hardware.org/?probe=375d986028) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Google        | Swanky                      | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [d5b2d74cd8](https://linux-hardware.org/?probe=d5b2d74cd8) | Oct 21, 2022 |
| Dell          | Latitude E7440              | [5c81fc2db0](https://linux-hardware.org/?probe=5c81fc2db0) | Oct 19, 2022 |
| Toshiba       | Satellite C660              | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Toshiba       | Satellite L750              | [9998a32d98](https://linux-hardware.org/?probe=9998a32d98) | Oct 09, 2022 |
| Dell          | Inspiron 3521               | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Dell          | Precision 3570              | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Apple         | MacBookPro14,3              | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| HP            | Pavilion g7                 | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| HP            | 15                          | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HP            | 15                          | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| Toshiba       | Satellite C660              | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Google        | Snappy                      | [e428dec368](https://linux-hardware.org/?probe=e428dec368) | Sep 14, 2022 |
| HP            | Laptop 17-bs0xx             | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| HP            | Pavilion dv6                | [5877abaab3](https://linux-hardware.org/?probe=5877abaab3) | Sep 07, 2022 |
| Acer          | Aspire F5-573G              | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| The Wareho... | E2037                       | [e9599d1061](https://linux-hardware.org/?probe=e9599d1061) | Aug 31, 2022 |
| Lenovo        | V145-15AST 81MT             | [40b9d37c2a](https://linux-hardware.org/?probe=40b9d37c2a) | Aug 29, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [0a08f13779](https://linux-hardware.org/?probe=0a08f13779) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | Latitude 5420               | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| HP            | ProBook 450 G6              | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| ASUSTek       | P81IJ                       | [7ab324abea](https://linux-hardware.org/?probe=7ab324abea) | Aug 25, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Acer          | Aspire M5-581TG             | [03ec19b37d](https://linux-hardware.org/?probe=03ec19b37d) | Aug 23, 2022 |
| Google        | Galtic                      | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Dell          | Latitude E6500              | [defd0003bc](https://linux-hardware.org/?probe=defd0003bc) | Aug 22, 2022 |
| Dell          | Vostro 7500                 | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| HP            | ProBook 6570b               | [335eb52112](https://linux-hardware.org/?probe=335eb52112) | Aug 12, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| Dell          | Latitude E6420              | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| Dell          | Latitude E6430s             | [542db6380a](https://linux-hardware.org/?probe=542db6380a) | Aug 04, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| HP            | 2000                        | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| HP            | Notebook                    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| Lenovo        | 14w 81MQ0013AU              | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| Lenovo        | G40-30 80FY                 | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| ASUSTek       | GL703VD                     | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [36fdd87ff3](https://linux-hardware.org/?probe=36fdd87ff3) | Jun 21, 2022 |
| HP            | ProBook 450 G1              | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
| HP            | 550                         | [1db816d0b2](https://linux-hardware.org/?probe=1db816d0b2) | Jun 19, 2022 |
| Dell          | Precision 3571              | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| HP            | EliteBook 830 G5            | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Toshiba       | Satellite Pro C665          | [23fd853a45](https://linux-hardware.org/?probe=23fd853a45) | May 24, 2022 |
| Acer          | TravelMate 7750G            | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | [06cb917381](https://linux-hardware.org/?probe=06cb917381) | May 22, 2022 |
| HP            | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [556940f73e](https://linux-hardware.org/?probe=556940f73e) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [fbea498a36](https://linux-hardware.org/?probe=fbea498a36) | May 21, 2022 |
| Toshiba       | Satellite L50D-C            | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [60d56e6b15](https://linux-hardware.org/?probe=60d56e6b15) | May 13, 2022 |
| Alienware     | x17 R2                      | [0a81fc619e](https://linux-hardware.org/?probe=0a81fc619e) | May 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bd6e42ac60](https://linux-hardware.org/?probe=bd6e42ac60) | May 07, 2022 |
| Toshiba       | Satellite C660              | [2b4d9cbd0c](https://linux-hardware.org/?probe=2b4d9cbd0c) | May 03, 2022 |
| Lenovo        | B50-30 20382                | [1eb95bb123](https://linux-hardware.org/?probe=1eb95bb123) | May 01, 2022 |
| Toshiba       | Satellite C660              | [c3bb583347](https://linux-hardware.org/?probe=c3bb583347) | Apr 24, 2022 |
| Lenovo        | B50-70 20384                | [35cf0f09e4](https://linux-hardware.org/?probe=35cf0f09e4) | Apr 22, 2022 |
| Dell          | XPS 13 9360                 | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Dell          | XPS 15 9510                 | [ff5563e261](https://linux-hardware.org/?probe=ff5563e261) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | [5ad4aa0994](https://linux-hardware.org/?probe=5ad4aa0994) | Apr 13, 2022 |
| HP            | ProBook 650 G1              | [a7d004962f](https://linux-hardware.org/?probe=a7d004962f) | Apr 08, 2022 |
| Dell          | Latitude 7480               | [ccc8107d39](https://linux-hardware.org/?probe=ccc8107d39) | Apr 01, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| eMachines     | eM350                       | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [9b194b03b4](https://linux-hardware.org/?probe=9b194b03b4) | Mar 25, 2022 |
| HP            | Laptop 15-bs0xx             | [e12f0f1eed](https://linux-hardware.org/?probe=e12f0f1eed) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [24d5a323cc](https://linux-hardware.org/?probe=24d5a323cc) | Mar 23, 2022 |
| ASUSTek       | G75VX                       | [4673f4edd8](https://linux-hardware.org/?probe=4673f4edd8) | Mar 21, 2022 |
| HP            | EliteBook 8460p             | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [33980f3303](https://linux-hardware.org/?probe=33980f3303) | Mar 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [5b83093837](https://linux-hardware.org/?probe=5b83093837) | Mar 15, 2022 |
| Dell          | Inspiron 5770               | [fc12718113](https://linux-hardware.org/?probe=fc12718113) | Mar 13, 2022 |
| Dell          | Inspiron 5770               | [8a7c1daf70](https://linux-hardware.org/?probe=8a7c1daf70) | Mar 13, 2022 |
| Dell          | XPS 15 9550                 | [c39fe1a3e3](https://linux-hardware.org/?probe=c39fe1a3e3) | Mar 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Acer          | Aspire E1-571G              | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [96aa797713](https://linux-hardware.org/?probe=96aa797713) | Feb 21, 2022 |
| Toshiba       | Satellite Pro R50-C         | [d185900f87](https://linux-hardware.org/?probe=d185900f87) | Feb 16, 2022 |
| Dell          | Inspiron 5415               | [3324e66890](https://linux-hardware.org/?probe=3324e66890) | Feb 15, 2022 |
| Dell          | Inspiron 5415               | [c2bd021f7e](https://linux-hardware.org/?probe=c2bd021f7e) | Feb 13, 2022 |
| ASUSTek       | K55A                        | [e88dba3a7e](https://linux-hardware.org/?probe=e88dba3a7e) | Feb 12, 2022 |
| System76      | Lemur Pro                   | [a0e5f04131](https://linux-hardware.org/?probe=a0e5f04131) | Feb 12, 2022 |
| Acer          | Aspire ES1-411              | [e534d71dc2](https://linux-hardware.org/?probe=e534d71dc2) | Feb 12, 2022 |
| Lenovo        | ThinkPad T470 20HES23B0U    | [c080812ddb](https://linux-hardware.org/?probe=c080812ddb) | Feb 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Acer          | Aspire A715-42G             | [f9c872ec0c](https://linux-hardware.org/?probe=f9c872ec0c) | Jan 30, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| Toshiba       | PORTEGE R930                | [1ee5471d24](https://linux-hardware.org/?probe=1ee5471d24) | Jan 20, 2022 |
| HP            | ProBook 450 G2              | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Star Labs     | LabTop                      | [c7cc8bae59](https://linux-hardware.org/?probe=c7cc8bae59) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [2e7edfda25](https://linux-hardware.org/?probe=2e7edfda25) | Jan 04, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Acer          | Swift SF314-41              | [d7b4fd099d](https://linux-hardware.org/?probe=d7b4fd099d) | Jan 01, 2022 |
| ASUSTek       | UX303LAB                    | [196ff1f41f](https://linux-hardware.org/?probe=196ff1f41f) | Dec 29, 2021 |
| Google        | Kip                         | [8c60d949d0](https://linux-hardware.org/?probe=8c60d949d0) | Dec 20, 2021 |
| Acer          | Aspire 4830T                | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Dell          | System XPS L702X            | [805619ba8c](https://linux-hardware.org/?probe=805619ba8c) | Nov 25, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| HP            | Laptop 15-bs0xx             | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
| Acer          | Aspire 4830T                | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9fc484d01e](https://linux-hardware.org/?probe=9fc484d01e) | Nov 11, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [edc363bc59](https://linux-hardware.org/?probe=edc363bc59) | Nov 11, 2021 |
| Timi          | A30                         | [63583fcf04](https://linux-hardware.org/?probe=63583fcf04) | Nov 09, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| ASUSTek       | K52Jc                       | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| Dell          | Vostro 14 5410              | [b6966ebc42](https://linux-hardware.org/?probe=b6966ebc42) | Oct 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [94e0e3f047](https://linux-hardware.org/?probe=94e0e3f047) | Oct 27, 2021 |
| HP            | Spectre x2 Detachable       | [d20c059f3d](https://linux-hardware.org/?probe=d20c059f3d) | Oct 24, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [01ca7ca744](https://linux-hardware.org/?probe=01ca7ca744) | Oct 23, 2021 |
| Dell          | Latitude 7490               | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| HP            | Pavilion tx2500             | [1410381a3d](https://linux-hardware.org/?probe=1410381a3d) | Oct 16, 2021 |
| HP            | Pavilion tx2500             | [e420777c94](https://linux-hardware.org/?probe=e420777c94) | Oct 16, 2021 |
| Dell          | Latitude 7285               | [5097e0f8c8](https://linux-hardware.org/?probe=5097e0f8c8) | Oct 14, 2021 |
| Acer          | Aspire VN7-593G             | [d9f2adbdfc](https://linux-hardware.org/?probe=d9f2adbdfc) | Oct 11, 2021 |
| HP            | Pavilion g6                 | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| Toshiba       | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| HP            | EliteBook 2170p             | [58e81067e0](https://linux-hardware.org/?probe=58e81067e0) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | [5e8a05628b](https://linux-hardware.org/?probe=5e8a05628b) | Sep 26, 2021 |
| MSI           | GE66 Raider 10SF            | [9d11ef435a](https://linux-hardware.org/?probe=9d11ef435a) | Sep 16, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [8f19930d07](https://linux-hardware.org/?probe=8f19930d07) | Sep 15, 2021 |
| Acer          | TravelMate 5760             | [eb8b4b37a4](https://linux-hardware.org/?probe=eb8b4b37a4) | Sep 13, 2021 |
| Acer          | TravelMate 5760             | [a0376eeefc](https://linux-hardware.org/?probe=a0376eeefc) | Sep 13, 2021 |
| Dell          | XPS 15 9500                 | [83bf40cb1d](https://linux-hardware.org/?probe=83bf40cb1d) | Sep 12, 2021 |
| Dell          | XPS 15 9500                 | [65102530f5](https://linux-hardware.org/?probe=65102530f5) | Sep 12, 2021 |
| HP            | EliteBook 8560p             | [48828ad0d3](https://linux-hardware.org/?probe=48828ad0d3) | Sep 10, 2021 |
| Dell          | System XPS L702X            | [e0ff0245fb](https://linux-hardware.org/?probe=e0ff0245fb) | Sep 10, 2021 |
| Toshiba       | Satellite C50D-C            | [af1933f8ad](https://linux-hardware.org/?probe=af1933f8ad) | Sep 09, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [35c6eb0703](https://linux-hardware.org/?probe=35c6eb0703) | Aug 31, 2021 |
| Lenovo        | B50-30 20382                | [1b602738e7](https://linux-hardware.org/?probe=1b602738e7) | Aug 30, 2021 |
| Medion        | P6815                       | [e3e586bafe](https://linux-hardware.org/?probe=e3e586bafe) | Aug 29, 2021 |
| Medion        | P6815                       | [46b6aaf8c5](https://linux-hardware.org/?probe=46b6aaf8c5) | Aug 29, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | [6bcc1e1e33](https://linux-hardware.org/?probe=6bcc1e1e33) | Aug 28, 2021 |
| HP            | Pavilion dv6                | [c1ad958c3f](https://linux-hardware.org/?probe=c1ad958c3f) | Aug 28, 2021 |
| Lenovo        | B50-30 20382                | [a7bca9bc08](https://linux-hardware.org/?probe=a7bca9bc08) | Aug 27, 2021 |
| Sony          | VPCEB43FG                   | [4a81e892f0](https://linux-hardware.org/?probe=4a81e892f0) | Aug 26, 2021 |
| Dell          | Latitude 7490               | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [efeb81eaea](https://linux-hardware.org/?probe=efeb81eaea) | Aug 21, 2021 |
| Dell          | XPS 15 9500                 | [1216df6214](https://linux-hardware.org/?probe=1216df6214) | Aug 19, 2021 |
| TWG           | E2017                       | [3f335e736c](https://linux-hardware.org/?probe=3f335e736c) | Aug 18, 2021 |
| Dell          | Latitude 7490               | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| Toshiba       | Satellite C50D-C            | [dda3acac30](https://linux-hardware.org/?probe=dda3acac30) | Aug 08, 2021 |
| Samsung       | RC410/RC510/RC710           | [4e03a59c3f](https://linux-hardware.org/?probe=4e03a59c3f) | Aug 03, 2021 |
| Samsung       | RC410/RC510/RC710           | [37550654db](https://linux-hardware.org/?probe=37550654db) | Aug 03, 2021 |
| Lenovo        | V15-IIL 82C5                | [20007580cb](https://linux-hardware.org/?probe=20007580cb) | Aug 01, 2021 |
| Lenovo        | V15-IIL 82C5                | [359e3c40ca](https://linux-hardware.org/?probe=359e3c40ca) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [812ba32a31](https://linux-hardware.org/?probe=812ba32a31) | Aug 01, 2021 |
| HP            | Pavilion g6                 | [147539a271](https://linux-hardware.org/?probe=147539a271) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [cc238ca2aa](https://linux-hardware.org/?probe=cc238ca2aa) | Jul 30, 2021 |
| HP            | Spectre x2 Detachable       | [7b96d53aa9](https://linux-hardware.org/?probe=7b96d53aa9) | Jul 29, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [2a54318c46](https://linux-hardware.org/?probe=2a54318c46) | Jul 27, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [c499631e7e](https://linux-hardware.org/?probe=c499631e7e) | Jul 19, 2021 |
| HP            | Laptop 14s-dk0xxx           | [0acaedd30c](https://linux-hardware.org/?probe=0acaedd30c) | Jul 13, 2021 |
| HP            | Laptop 14s-dk0xxx           | [f655e1ca50](https://linux-hardware.org/?probe=f655e1ca50) | Jul 12, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [331968a8d9](https://linux-hardware.org/?probe=331968a8d9) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [59e9a66bff](https://linux-hardware.org/?probe=59e9a66bff) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [e20b747527](https://linux-hardware.org/?probe=e20b747527) | Jul 03, 2021 |
| Sony          | SVE14A15FGS                 | [adb8d0cc94](https://linux-hardware.org/?probe=adb8d0cc94) | Jun 14, 2021 |
| Acer          | Aspire A715-71G             | [cb59081351](https://linux-hardware.org/?probe=cb59081351) | Jun 14, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [e82b7b36f2](https://linux-hardware.org/?probe=e82b7b36f2) | Jun 12, 2021 |
| ASUSTek       | K52Jc                       | [4b93dc4ee8](https://linux-hardware.org/?probe=4b93dc4ee8) | Jun 07, 2021 |
| HP            | ProBook 650 G1              | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| HP            | EliteBook 8560p             | [ea1bd5e314](https://linux-hardware.org/?probe=ea1bd5e314) | May 30, 2021 |
| Sony          | SVE11126CGB                 | [b7ee22588d](https://linux-hardware.org/?probe=b7ee22588d) | May 29, 2021 |
| Toshiba       | Satellite S70t-B            | [33d64c7a69](https://linux-hardware.org/?probe=33d64c7a69) | May 26, 2021 |
| Toshiba       | Satellite S70t-B            | [60c1bab5d9](https://linux-hardware.org/?probe=60c1bab5d9) | May 26, 2021 |
| HP            | Pavilion Notebook           | [37695077ba](https://linux-hardware.org/?probe=37695077ba) | May 21, 2021 |
| HP            | ENVY 15                     | [2a23609955](https://linux-hardware.org/?probe=2a23609955) | May 15, 2021 |
| Acer          | E5-571-551U                 | [152105400d](https://linux-hardware.org/?probe=152105400d) | May 05, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| Lenovo        | V110-15IAP 80TG             | [76ac42ca9c](https://linux-hardware.org/?probe=76ac42ca9c) | Apr 30, 2021 |
| MSI           | GS63VR 7RF                  | [4a7125aec0](https://linux-hardware.org/?probe=4a7125aec0) | Apr 18, 2021 |
| MSI           | GS63VR 7RF                  | [76126cd5fd](https://linux-hardware.org/?probe=76126cd5fd) | Apr 18, 2021 |
| Toshiba       | PORTEGE M930                | [aac37423e5](https://linux-hardware.org/?probe=aac37423e5) | Apr 13, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d65bc55ad0](https://linux-hardware.org/?probe=d65bc55ad0) | Apr 11, 2021 |
| Apple         | MacBook7,1                  | [9b4e89202e](https://linux-hardware.org/?probe=9b4e89202e) | Apr 09, 2021 |
| HP            | ProBook 650 G1              | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| HP            | EliteBook 2560p             | [ecdecf72ec](https://linux-hardware.org/?probe=ecdecf72ec) | Mar 30, 2021 |
| HP            | ProBook 650 G1              | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| HP            | ZBook Firefly 15 G7 Mobi... | [0653cc5343](https://linux-hardware.org/?probe=0653cc5343) | Mar 29, 2021 |
| Metabox       | X170SM                      | [eb5af1bbd3](https://linux-hardware.org/?probe=eb5af1bbd3) | Mar 26, 2021 |
| Metabox       | X170SM                      | [544b6cd3d5](https://linux-hardware.org/?probe=544b6cd3d5) | Mar 26, 2021 |
| HP            | ProBook 4540s               | [4fe9e650c2](https://linux-hardware.org/?probe=4fe9e650c2) | Mar 13, 2021 |
| HP            | ProBook 4540s               | [d2c0c69a0d](https://linux-hardware.org/?probe=d2c0c69a0d) | Mar 13, 2021 |
| Acer          | Aspire 5750                 | [6aaf201a58](https://linux-hardware.org/?probe=6aaf201a58) | Mar 10, 2021 |
| Toshiba       | Satellite U920t             | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | [b1088bed99](https://linux-hardware.org/?probe=b1088bed99) | Feb 26, 2021 |
| Dell          | XPS 13 9360                 | [7de34c9abe](https://linux-hardware.org/?probe=7de34c9abe) | Feb 26, 2021 |
| HP            | ZBook 14                    | [042b4b4a48](https://linux-hardware.org/?probe=042b4b4a48) | Feb 26, 2021 |
| Dell          | Latitude E6430s             | [cb9032f7b7](https://linux-hardware.org/?probe=cb9032f7b7) | Feb 24, 2021 |
| Dell          | Latitude 7285               | [844392cd2c](https://linux-hardware.org/?probe=844392cd2c) | Feb 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [d20e5c1f85](https://linux-hardware.org/?probe=d20e5c1f85) | Feb 15, 2021 |
| HP            | EliteBook 820 G3            | [e1a72b607e](https://linux-hardware.org/?probe=e1a72b607e) | Feb 14, 2021 |
| Dell          | Latitude E4300              | [a09ca20174](https://linux-hardware.org/?probe=a09ca20174) | Feb 14, 2021 |
| HP            | Notebook                    | [e5bc3a0317](https://linux-hardware.org/?probe=e5bc3a0317) | Feb 12, 2021 |
| MSI           | GE66 Raider 10SF            | [a9bc0b88b6](https://linux-hardware.org/?probe=a9bc0b88b6) | Feb 10, 2021 |
| HP            | 355 G2                      | [ac856a41b8](https://linux-hardware.org/?probe=ac856a41b8) | Feb 03, 2021 |
| Acer          | ES1-512-P8NA                | [c393cb6ad4](https://linux-hardware.org/?probe=c393cb6ad4) | Jan 24, 2021 |
| HP            | ProBook 450 G3              | [c5e2124079](https://linux-hardware.org/?probe=c5e2124079) | Jan 21, 2021 |
| Toshiba       | Satellite U920t             | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [ecc872dc4a](https://linux-hardware.org/?probe=ecc872dc4a) | Jan 16, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [3c308a7199](https://linux-hardware.org/?probe=3c308a7199) | Jan 15, 2021 |
| Acer          | ConceptD CN315-71P          | [7d1c394d7a](https://linux-hardware.org/?probe=7d1c394d7a) | Dec 26, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| Lenovo        | ThinkPad P52 20M9000KUS     | [ed51fc90e5](https://linux-hardware.org/?probe=ed51fc90e5) | Dec 19, 2020 |
| HP            | ZBook Studio G5             | [af0417cef5](https://linux-hardware.org/?probe=af0417cef5) | Dec 10, 2020 |
| Dell          | Precision 7530              | [c82b4c0f51](https://linux-hardware.org/?probe=c82b4c0f51) | Dec 03, 2020 |
| HP            | Pavilion dv6                | [2c1cf2da53](https://linux-hardware.org/?probe=2c1cf2da53) | Nov 30, 2020 |
| eMachines     | eM350                       | [0ba740f085](https://linux-hardware.org/?probe=0ba740f085) | Nov 28, 2020 |
| Dell          | XPS 15 9560                 | [463c0c961e](https://linux-hardware.org/?probe=463c0c961e) | Nov 15, 2020 |
| Dell          | Latitude D630               | [4b5f3f19ae](https://linux-hardware.org/?probe=4b5f3f19ae) | Nov 14, 2020 |
| Toshiba       | Satellite Pro L830          | [97a68dd7c5](https://linux-hardware.org/?probe=97a68dd7c5) | Nov 14, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [3ffb0e062e](https://linux-hardware.org/?probe=3ffb0e062e) | Nov 13, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [7e7b6fe785](https://linux-hardware.org/?probe=7e7b6fe785) | Nov 13, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [0001b76ceb](https://linux-hardware.org/?probe=0001b76ceb) | Nov 10, 2020 |
| Acer          | Aspire ES1-511              | [13485ce10c](https://linux-hardware.org/?probe=13485ce10c) | Nov 08, 2020 |
| Acer          | Aspire ES1-511              | [903c4d5729](https://linux-hardware.org/?probe=903c4d5729) | Nov 08, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [c4d3f6f37d](https://linux-hardware.org/?probe=c4d3f6f37d) | Nov 07, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [841d75822e](https://linux-hardware.org/?probe=841d75822e) | Nov 04, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | [41c93bb503](https://linux-hardware.org/?probe=41c93bb503) | Oct 29, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | [7678291690](https://linux-hardware.org/?probe=7678291690) | Oct 28, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [bacac44e9d](https://linux-hardware.org/?probe=bacac44e9d) | Oct 26, 2020 |
| HP            | ProBook 6550b               | [d93b3bfeac](https://linux-hardware.org/?probe=d93b3bfeac) | Oct 22, 2020 |
| Toshiba       | Satellite C660              | [d8ac831c61](https://linux-hardware.org/?probe=d8ac831c61) | Oct 20, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [8720432e33](https://linux-hardware.org/?probe=8720432e33) | Oct 16, 2020 |
| ASUSTek       | X550EP                      | [f13a8d8d9b](https://linux-hardware.org/?probe=f13a8d8d9b) | Oct 15, 2020 |
| Dell          | XPS 13 9360                 | [8cf28e044c](https://linux-hardware.org/?probe=8cf28e044c) | Oct 11, 2020 |
| HP            | Compaq Presario A900        | [352f29d57c](https://linux-hardware.org/?probe=352f29d57c) | Oct 08, 2020 |
| HP            | Laptop 15s-fq1xxx           | [b3ae2a4d2c](https://linux-hardware.org/?probe=b3ae2a4d2c) | Oct 06, 2020 |
| ASUSTek       | 1015PX                      | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer          | Swift SF314-41              | [26350d0806](https://linux-hardware.org/?probe=26350d0806) | Oct 04, 2020 |
| HP            | Compaq CQ45                 | [ea61076771](https://linux-hardware.org/?probe=ea61076771) | Sep 30, 2020 |
| MSI           | GP75 Leopard 9SD            | [9c152a1117](https://linux-hardware.org/?probe=9c152a1117) | Sep 30, 2020 |
| HP            | Compaq CQ45                 | [f62190e31d](https://linux-hardware.org/?probe=f62190e31d) | Sep 29, 2020 |
| HP            | EliteBook 850 G5            | [86422636a2](https://linux-hardware.org/?probe=86422636a2) | Sep 25, 2020 |
| Apple         | MacBook5,1                  | [fb2f9dd279](https://linux-hardware.org/?probe=fb2f9dd279) | Sep 24, 2020 |
| HP            | EliteBook Folio 1040 G1     | [0848bad0d4](https://linux-hardware.org/?probe=0848bad0d4) | Sep 23, 2020 |
| Apple         | MacBook5,1                  | [ad39052e7a](https://linux-hardware.org/?probe=ad39052e7a) | Sep 22, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [616e26ca49](https://linux-hardware.org/?probe=616e26ca49) | Sep 20, 2020 |
| HP            | ProBook 450 G5              | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| HP            | ProBook 6560b               | [109cd57459](https://linux-hardware.org/?probe=109cd57459) | Sep 12, 2020 |
| Dell          | Latitude E6430s             | [bd8ab4dd1c](https://linux-hardware.org/?probe=bd8ab4dd1c) | Sep 08, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [b673064c0f](https://linux-hardware.org/?probe=b673064c0f) | Sep 08, 2020 |
| Acer          | Aspire 5750                 | [b65a1db938](https://linux-hardware.org/?probe=b65a1db938) | Sep 07, 2020 |
| Toshiba       | Satellite C50-B             | [167e9daeb7](https://linux-hardware.org/?probe=167e9daeb7) | Sep 05, 2020 |
| HP            | Pavilion dv6                | [4c2298d7bb](https://linux-hardware.org/?probe=4c2298d7bb) | Sep 05, 2020 |
| Dell          | Latitude E7440              | [0db3907088](https://linux-hardware.org/?probe=0db3907088) | Sep 05, 2020 |
| HP            | Laptop 15-db0xxx            | [3949b5f183](https://linux-hardware.org/?probe=3949b5f183) | Sep 04, 2020 |
| Dell          | Inspiron 5567               | [ab299d27a4](https://linux-hardware.org/?probe=ab299d27a4) | Sep 04, 2020 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [9c1bd6b943](https://linux-hardware.org/?probe=9c1bd6b943) | Sep 03, 2020 |
| MSI           | GT80S 6QD                   | [e14f86e038](https://linux-hardware.org/?probe=e14f86e038) | Sep 03, 2020 |
| Acer          | Aspire 5750                 | [6c84136b17](https://linux-hardware.org/?probe=6c84136b17) | Sep 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [c9cf3aef22](https://linux-hardware.org/?probe=c9cf3aef22) | Sep 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [65612b9b8f](https://linux-hardware.org/?probe=65612b9b8f) | Sep 03, 2020 |
| Toshiba       | Satellite C660              | [e7791768a3](https://linux-hardware.org/?probe=e7791768a3) | Sep 02, 2020 |
| Toshiba       | Satellite C50-B             | [186e22ea8c](https://linux-hardware.org/?probe=186e22ea8c) | Sep 01, 2020 |
| Dell          | XPS 15 9570                 | [cb17688de8](https://linux-hardware.org/?probe=cb17688de8) | Sep 01, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [4d92725c5a](https://linux-hardware.org/?probe=4d92725c5a) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [1707834024](https://linux-hardware.org/?probe=1707834024) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [db76b91e62](https://linux-hardware.org/?probe=db76b91e62) | Aug 21, 2020 |
| HP            | Pavilion dv6                | [65033f4392](https://linux-hardware.org/?probe=65033f4392) | Aug 19, 2020 |
| MSI           | GE66 Raider 10SF            | [3bcf471b04](https://linux-hardware.org/?probe=3bcf471b04) | Aug 15, 2020 |
| Dell          | Latitude E6430              | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| System76      | Lemur Pro                   | [c2619f1014](https://linux-hardware.org/?probe=c2619f1014) | Aug 14, 2020 |
| MSI           | GT72 2PC                    | [464657ada9](https://linux-hardware.org/?probe=464657ada9) | Aug 11, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [fb69c1f324](https://linux-hardware.org/?probe=fb69c1f324) | Aug 10, 2020 |
| Apple         | MacBookPro5,5               | [37d32b3bac](https://linux-hardware.org/?probe=37d32b3bac) | Aug 03, 2020 |
| Apple         | MacBookPro5,5               | [6aee03b649](https://linux-hardware.org/?probe=6aee03b649) | Jul 31, 2020 |
| HP            | Pavilion dv4                | [ec2bd27559](https://linux-hardware.org/?probe=ec2bd27559) | Jul 25, 2020 |
| MSI           | GE66 Raider 10SF            | [3dcde22239](https://linux-hardware.org/?probe=3dcde22239) | Jul 25, 2020 |
| HP            | Laptop 15-dy0xxx            | [cad2dbb88f](https://linux-hardware.org/?probe=cad2dbb88f) | Jul 25, 2020 |
| HP            | ProBook 450 G5              | [a8dfd5a806](https://linux-hardware.org/?probe=a8dfd5a806) | Jul 21, 2020 |
| HP            | Laptop 15-dy0xxx            | [e471bc69b2](https://linux-hardware.org/?probe=e471bc69b2) | Jul 21, 2020 |
| Dell          | Latitude E5570              | [6408e82f4f](https://linux-hardware.org/?probe=6408e82f4f) | Jul 20, 2020 |
| HP            | EliteBook 840 G1            | [75a2e58b47](https://linux-hardware.org/?probe=75a2e58b47) | Jun 30, 2020 |
| HP            | EliteBook 8560p             | [e83d7e33f2](https://linux-hardware.org/?probe=e83d7e33f2) | Jun 29, 2020 |
| HP            | EliteBook 840 G6            | [9fccdcc42f](https://linux-hardware.org/?probe=9fccdcc42f) | Jun 25, 2020 |
| HP            | ProBook 650 G1              | [d8e10f56ec](https://linux-hardware.org/?probe=d8e10f56ec) | Jun 24, 2020 |
| MSI           | GE66 Raider 10SF            | [ca5d80f8f9](https://linux-hardware.org/?probe=ca5d80f8f9) | Jun 16, 2020 |
| MSI           | GE66 Raider 10SF            | [220b2a94c8](https://linux-hardware.org/?probe=220b2a94c8) | Jun 10, 2020 |
| HP            | ProBook 4540s               | [b28f2f3b8a](https://linux-hardware.org/?probe=b28f2f3b8a) | Jun 05, 2020 |
| HP            | Presario CQ56               | [4eed3fc6f6](https://linux-hardware.org/?probe=4eed3fc6f6) | Jun 05, 2020 |
| MSI           | GE66 Raider 10SF            | [8c0b76c629](https://linux-hardware.org/?probe=8c0b76c629) | Jun 01, 2020 |
| Acer          | Aspire E1-571               | [25ca966875](https://linux-hardware.org/?probe=25ca966875) | Jun 01, 2020 |
| MSI           | GE66 Raider 10SF            | [1cb7bb7ad9](https://linux-hardware.org/?probe=1cb7bb7ad9) | May 23, 2020 |
| MSI           | GE66 Raider 10SF            | [afec91ff4d](https://linux-hardware.org/?probe=afec91ff4d) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [72f3e05699](https://linux-hardware.org/?probe=72f3e05699) | May 22, 2020 |
| HP            | EliteBook 8560p             | [5439d2f06b](https://linux-hardware.org/?probe=5439d2f06b) | May 22, 2020 |
| Dell          | Latitude E6430s             | [891fd84ed1](https://linux-hardware.org/?probe=891fd84ed1) | May 21, 2020 |
| Dell          | Latitude E6430s             | [b2f67f2744](https://linux-hardware.org/?probe=b2f67f2744) | May 20, 2020 |
| Sony          | VPCEH28FG                   | [f241603946](https://linux-hardware.org/?probe=f241603946) | May 17, 2020 |
| Lenovo        | ThinkPad E590 20NBS0SC00    | [50ca962181](https://linux-hardware.org/?probe=50ca962181) | May 14, 2020 |
| HP            | EliteBook 8570p             | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| HP            | EliteBook 8560p             | [605660fceb](https://linux-hardware.org/?probe=605660fceb) | May 11, 2020 |
| Lenovo        | ThinkPad E520 1143CTO       | [d1258905c6](https://linux-hardware.org/?probe=d1258905c6) | May 10, 2020 |
| Lenovo        | ThinkPad E520 1143CTO       | [51adfc765c](https://linux-hardware.org/?probe=51adfc765c) | May 10, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [8ca322cd11](https://linux-hardware.org/?probe=8ca322cd11) | May 06, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [e0d0592e34](https://linux-hardware.org/?probe=e0d0592e34) | May 05, 2020 |
| HP            | ProBook 650 G1              | [ed42eb842d](https://linux-hardware.org/?probe=ed42eb842d) | May 04, 2020 |
| HP            | ProBook 650 G1              | [d29d76cb5c](https://linux-hardware.org/?probe=d29d76cb5c) | May 04, 2020 |
| HP            | Presario CQ57               | [df09ee9161](https://linux-hardware.org/?probe=df09ee9161) | Apr 26, 2020 |
| Toshiba       | TECRA Z50-A                 | [ff5b768627](https://linux-hardware.org/?probe=ff5b768627) | Apr 21, 2020 |
| Acer          | Aspire A315-21G             | [7f9e52f0dd](https://linux-hardware.org/?probe=7f9e52f0dd) | Apr 20, 2020 |
| Acer          | Aspire A315-21G             | [4409c8dae5](https://linux-hardware.org/?probe=4409c8dae5) | Apr 20, 2020 |
| HP            | Pavilion g6                 | [15ad84ee0f](https://linux-hardware.org/?probe=15ad84ee0f) | Apr 15, 2020 |
| Dell          | XPS 13 9360                 | [89cce1b8b6](https://linux-hardware.org/?probe=89cce1b8b6) | Apr 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [e4ed30a655](https://linux-hardware.org/?probe=e4ed30a655) | Apr 04, 2020 |
| Toshiba       | Satellite L750              | [391a50ded4](https://linux-hardware.org/?probe=391a50ded4) | Apr 03, 2020 |
| ASUSTek       | N56VZ                       | [04666ab26e](https://linux-hardware.org/?probe=04666ab26e) | Apr 01, 2020 |
| HP            | Pavilion 10 TS              | [87484a7033](https://linux-hardware.org/?probe=87484a7033) | Mar 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0c505fcd69](https://linux-hardware.org/?probe=0c505fcd69) | Mar 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [fc12fa3a4d](https://linux-hardware.org/?probe=fc12fa3a4d) | Mar 25, 2020 |
| Dell          | Precision M6800             | [adb3b768f7](https://linux-hardware.org/?probe=adb3b768f7) | Mar 24, 2020 |
| ASUSTek       | TAICHI21                    | [608a903011](https://linux-hardware.org/?probe=608a903011) | Mar 11, 2020 |
| HP            | EliteBook 840 G6            | [a26150e202](https://linux-hardware.org/?probe=a26150e202) | Mar 07, 2020 |
| HP            | EliteBook 840 G6            | [0d6d26562c](https://linux-hardware.org/?probe=0d6d26562c) | Mar 07, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [f49a66ef1e](https://linux-hardware.org/?probe=f49a66ef1e) | Feb 25, 2020 |
| HP            | Pavilion 15                 | [72784962fe](https://linux-hardware.org/?probe=72784962fe) | Feb 25, 2020 |
| HP            | Pavilion 15                 | [a1e89aa309](https://linux-hardware.org/?probe=a1e89aa309) | Feb 25, 2020 |
| Dell          | Latitude E4300              | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| HP            | EliteBook x360 1040 G6      | [a838427772](https://linux-hardware.org/?probe=a838427772) | Feb 12, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [5f61d3d553](https://linux-hardware.org/?probe=5f61d3d553) | Feb 09, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [10d5285055](https://linux-hardware.org/?probe=10d5285055) | Feb 07, 2020 |
| HP            | ProBook 650 G1              | [b5d441afe1](https://linux-hardware.org/?probe=b5d441afe1) | Feb 01, 2020 |
| Lenovo        | V110-14IAP 80TF             | [85b3202273](https://linux-hardware.org/?probe=85b3202273) | Jan 30, 2020 |
| Dell          | XPS 13 9360                 | [c770de6326](https://linux-hardware.org/?probe=c770de6326) | Jan 25, 2020 |
| Lenovo        | ThinkPad X131e 33691A4      | [a30712cd7d](https://linux-hardware.org/?probe=a30712cd7d) | Jan 22, 2020 |
| HP            | Notebook                    | [8f2fc8e2ec](https://linux-hardware.org/?probe=8f2fc8e2ec) | Jan 09, 2020 |
| ASUSTek       | K46CB                       | [45b756e92d](https://linux-hardware.org/?probe=45b756e92d) | Jan 04, 2020 |
| ASUSTek       | K46CB                       | [1a25890709](https://linux-hardware.org/?probe=1a25890709) | Jan 04, 2020 |
| HP            | ProBook 650 G1              | [0763c1c109](https://linux-hardware.org/?probe=0763c1c109) | Jan 02, 2020 |
| HP            | ProBook 650 G1              | [023556890d](https://linux-hardware.org/?probe=023556890d) | Jan 02, 2020 |
| Acer          | Aspire F5-573G              | [ead658852a](https://linux-hardware.org/?probe=ead658852a) | Jan 01, 2020 |
| Acer          | Aspire F5-573G              | [e19db7603d](https://linux-hardware.org/?probe=e19db7603d) | Jan 01, 2020 |
| HP            | ProBook 6550b               | [65a8d66fb9](https://linux-hardware.org/?probe=65a8d66fb9) | Dec 31, 2019 |
| HP            | ProBook 650 G1              | [0085227124](https://linux-hardware.org/?probe=0085227124) | Dec 30, 2019 |
| HP            | EliteBook 850 G5            | [65b1eb0ca1](https://linux-hardware.org/?probe=65b1eb0ca1) | Dec 26, 2019 |
| Lenovo        | ThinkPad T420 4180AQ3       | [4da7aff7a2](https://linux-hardware.org/?probe=4da7aff7a2) | Dec 23, 2019 |
| ASUSTek       | UL50Ag                      | [ba1e7f648c](https://linux-hardware.org/?probe=ba1e7f648c) | Dec 19, 2019 |
| MSI           | GT72 2PC                    | [dbe1269ea7](https://linux-hardware.org/?probe=dbe1269ea7) | Dec 11, 2019 |
| HP            | Pavilion g6                 | [3acb153d5d](https://linux-hardware.org/?probe=3acb153d5d) | Dec 06, 2019 |
| HP            | EliteBook 6930p             | [94af8c86b1](https://linux-hardware.org/?probe=94af8c86b1) | Dec 03, 2019 |
| HP            | Pavilion g6                 | [034500d792](https://linux-hardware.org/?probe=034500d792) | Nov 26, 2019 |
| Dell          | Latitude 7285               | [87a44ef029](https://linux-hardware.org/?probe=87a44ef029) | Nov 22, 2019 |
| Dell          | Latitude 7285               | [34937530ea](https://linux-hardware.org/?probe=34937530ea) | Nov 21, 2019 |
| HP            | Notebook                    | [31d1bef6c1](https://linux-hardware.org/?probe=31d1bef6c1) | Nov 11, 2019 |
| HP            | ProBook 4540s               | [5cc8316a85](https://linux-hardware.org/?probe=5cc8316a85) | Nov 08, 2019 |
| HP            | ProBook 4730s               | [ed03fd8077](https://linux-hardware.org/?probe=ed03fd8077) | Oct 29, 2019 |
| HP            | ProBook 4730s               | [cd284908ca](https://linux-hardware.org/?probe=cd284908ca) | Oct 28, 2019 |
| HP            | Notebook                    | [1bccff3cda](https://linux-hardware.org/?probe=1bccff3cda) | Sep 25, 2019 |
| Toshiba       | PORTEGE M780                | [64824e5a04](https://linux-hardware.org/?probe=64824e5a04) | Sep 21, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [8e78a0ebf5](https://linux-hardware.org/?probe=8e78a0ebf5) | Sep 11, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [fd27e8c70f](https://linux-hardware.org/?probe=fd27e8c70f) | Sep 11, 2019 |
| HP            | Notebook                    | [776ffefbc2](https://linux-hardware.org/?probe=776ffefbc2) | Sep 11, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [f5b3521c55](https://linux-hardware.org/?probe=f5b3521c55) | Sep 11, 2019 |
| HP            | Notebook                    | [cf646ad1f2](https://linux-hardware.org/?probe=cf646ad1f2) | Sep 11, 2019 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [873e28fce7](https://linux-hardware.org/?probe=873e28fce7) | Sep 02, 2019 |
| HP            | Compaq 6910p (GM903PA#AB... | [2724623348](https://linux-hardware.org/?probe=2724623348) | Aug 12, 2019 |
| ASUSTek       | X542UQ                      | [7a4797b166](https://linux-hardware.org/?probe=7a4797b166) | Aug 11, 2019 |
| HP            | ProBook 6570b               | [4f80f9ba3c](https://linux-hardware.org/?probe=4f80f9ba3c) | Aug 04, 2019 |
| Lenovo        | ThinkPad T440p 20AWS1J00... | [31bcd5a103](https://linux-hardware.org/?probe=31bcd5a103) | Jul 31, 2019 |
| HP            | ProBook 450 G3              | [b9e21a89da](https://linux-hardware.org/?probe=b9e21a89da) | Jul 23, 2019 |
| HP            | ProBook 650 G1              | [6d584d5dab](https://linux-hardware.org/?probe=6d584d5dab) | Jul 22, 2019 |
| HP            | ProBook 450 G3              | [10b8987b19](https://linux-hardware.org/?probe=10b8987b19) | Jul 17, 2019 |
| HP            | ProBook 6550b               | [801f83247c](https://linux-hardware.org/?probe=801f83247c) | Jul 06, 2019 |
| HP            | ProBook 4730s               | [ed98a45d81](https://linux-hardware.org/?probe=ed98a45d81) | Jul 01, 2019 |
| Acer          | Aspire 5100                 | [a28f7b2623](https://linux-hardware.org/?probe=a28f7b2623) | Jun 27, 2019 |
| Acer          | Aspire 5100                 | [aa61fb2b9c](https://linux-hardware.org/?probe=aa61fb2b9c) | Jun 11, 2019 |
| YJKC          | vBOOK Plus                  | [80eae9ed5f](https://linux-hardware.org/?probe=80eae9ed5f) | Jun 09, 2019 |
| HP            | Unknown                     | [ef6ea82cf5](https://linux-hardware.org/?probe=ef6ea82cf5) | May 20, 2019 |
| ASUSTek       | K84L                        | [231a7d9bc6](https://linux-hardware.org/?probe=231a7d9bc6) | Apr 18, 2019 |
| HP            | ProBook 6570b               | [42129ed417](https://linux-hardware.org/?probe=42129ed417) | Mar 23, 2019 |
| HP            | ProBook 6570b               | [25a7d4cca8](https://linux-hardware.org/?probe=25a7d4cca8) | Mar 03, 2019 |
| Acer          | Aspire E5-721               | [e6dca4d6fd](https://linux-hardware.org/?probe=e6dca4d6fd) | Feb 28, 2019 |
| HP            | Mini 110-1100               | [1ba5e0d0b2](https://linux-hardware.org/?probe=1ba5e0d0b2) | Feb 23, 2019 |
| HP            | ProBook 6570b               | [82e153050f](https://linux-hardware.org/?probe=82e153050f) | Jan 28, 2019 |
| HP            | ProBook 650 G1              | [2756a314e5](https://linux-hardware.org/?probe=2756a314e5) | Jan 14, 2019 |
| HP            | ProBook 650 G1              | [f81c16faea](https://linux-hardware.org/?probe=f81c16faea) | Jan 14, 2019 |
| Lenovo        | B590 20208                  | [7c06278f98](https://linux-hardware.org/?probe=7c06278f98) | Dec 28, 2018 |
| Lenovo        | B590 20208                  | [d4897cc9d7](https://linux-hardware.org/?probe=d4897cc9d7) | Dec 28, 2018 |
| HP            | Pavilion 15                 | [5407e9ab05](https://linux-hardware.org/?probe=5407e9ab05) | Dec 22, 2018 |
| HP            | Pavilion 15                 | [a47a651328](https://linux-hardware.org/?probe=a47a651328) | Dec 22, 2018 |
| HP            | 14                          | [553085d233](https://linux-hardware.org/?probe=553085d233) | Jul 06, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/New_Zealand/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 37        | 6.83%   |
| Ubuntu 22.04        | 36        | 6.64%   |
| Pop!_OS 22.04       | 26        | 4.8%    |
| Arch Rolling        | 17        | 3.14%   |
| Ubuntu 24.04        | 16        | 2.95%   |
| Ubuntu 18.04        | 15        | 2.77%   |
| Zorin 16            | 14        | 2.58%   |
| OpenMandriva 4.3    | 12        | 2.21%   |
| Debian 12           | 11        | 2.03%   |
| Zorin 15            | 10        | 1.85%   |
| Arch                | 10        | 1.85%   |
| Debian 11           | 9         | 1.66%   |
| Pop!_OS 20.04       | 8         | 1.48%   |
| OpenMandriva 4.2    | 8         | 1.48%   |
| OpenMandriva 23.01  | 7         | 1.29%   |
| Ubuntu 21.10        | 6         | 1.11%   |
| Ubuntu 20.10        | 6         | 1.11%   |
| Linux Mint 21.3     | 6         | 1.11%   |
| Linux Mint 21.2     | 6         | 1.11%   |
| Linux Mint 21.1     | 6         | 1.11%   |
| Linux Mint 21       | 6         | 1.11%   |
| Linux Mint 20.3     | 6         | 1.11%   |
| Linux Mint 20.2     | 6         | 1.11%   |
| Kubuntu 22.04       | 6         | 1.11%   |
| Fedora 40           | 6         | 1.11%   |
| Fedora 31           | 6         | 1.11%   |
| EndeavourOS Rolling | 6         | 1.11%   |
| Debian 10           | 6         | 1.11%   |
| Zorin 17            | 5         | 0.92%   |
| Pop!_OS 20.10       | 5         | 0.92%   |
| OpenMandriva 23.03  | 5         | 0.92%   |
| Manjaro             | 5         | 0.92%   |
| Fedora 35           | 5         | 0.92%   |
| Ubuntu 21.04        | 4         | 0.74%   |
| Pop!_OS 21.04       | 4         | 0.74%   |
| OpenMandriva 24.12  | 4         | 0.74%   |
| MX 21               | 4         | 0.74%   |
| Linux Mint 19.2     | 4         | 0.74%   |
| Kubuntu 20.04       | 4         | 0.74%   |
| Fedora 34           | 4         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 125       | 24.51%  |
| Linux Mint       | 50        | 9.8%    |
| Pop!_OS          | 44        | 8.63%   |
| OpenMandriva     | 42        | 8.24%   |
| Fedora           | 41        | 8.04%   |
| Debian           | 30        | 5.88%   |
| Zorin            | 29        | 5.69%   |
| Arch             | 26        | 5.1%    |
| Kubuntu          | 13        | 2.55%   |
| Manjaro          | 12        | 2.35%   |
| EndeavourOS      | 7         | 1.37%   |
| Elementary       | 7         | 1.37%   |
| Endless          | 6         | 1.18%   |
| SteamOS          | 5         | 0.98%   |
| Nobara           | 5         | 0.98%   |
| MX               | 5         | 0.98%   |
| KDE neon         | 5         | 0.98%   |
| Kali             | 5         | 0.98%   |
| ArcoLinux        | 5         | 0.98%   |
| Xubuntu          | 4         | 0.78%   |
| Ubuntu Unity     | 4         | 0.78%   |
| LMDE             | 4         | 0.78%   |
| Gentoo           | 4         | 0.78%   |
| Ubuntu MATE      | 3         | 0.59%   |
| openSUSE         | 3         | 0.59%   |
| Solus            | 2         | 0.39%   |
| ROSA             | 2         | 0.39%   |
| Peppermint       | 2         | 0.39%   |
| org.kde.Platform | 2         | 0.39%   |
| Lubuntu          | 2         | 0.39%   |
| BuildRoot        | 2         | 0.39%   |
| antiX            | 2         | 0.39%   |
| Void Linux       | 1         | 0.2%    |
| Vanilla          | 1         | 0.2%    |
| Ubuntu Budgie    | 1         | 0.2%    |
| Sparky           | 1         | 0.2%    |
| Parrot           | 1         | 0.2%    |
| LFS              | 1         | 0.2%    |
| Garuda Linux     | 1         | 0.2%    |
| Devuan           | 1         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 12        | 2.01%   |
| 5.16.7-desktop-1omv4003  | 10        | 1.67%   |
| 5.15.0-46-generic        | 8         | 1.34%   |
| 5.10.14-desktop-1omv4002 | 8         | 1.34%   |
| 6.8.0-40-generic         | 7         | 1.17%   |
| 6.1.1-desktop-1omv2290   | 7         | 1.17%   |
| 6.0.12-76060006-generic  | 7         | 1.17%   |
| 6.9.3-76060903-generic   | 5         | 0.84%   |
| 5.4.0-48-generic         | 5         | 0.84%   |
| 5.3.0-28-generic         | 5         | 0.84%   |
| 6.8.0-45-generic         | 4         | 0.67%   |
| 6.8.0-41-generic         | 4         | 0.67%   |
| 6.5.0-41-generic         | 4         | 0.67%   |
| 6.4.11-desktop-1omv2390  | 4         | 0.67%   |
| 6.2.6-desktop-1omv2390   | 4         | 0.67%   |
| 5.3.16-300.fc31.x86_64   | 4         | 0.67%   |
| 5.17.5-76051705-generic  | 4         | 0.67%   |
| 5.15.0-58-generic        | 4         | 0.67%   |
| 5.15.0-56-generic        | 4         | 0.67%   |
| 5.11.0-7620-generic      | 4         | 0.67%   |
| 5.11.0-27-generic        | 4         | 0.67%   |
| 6.8.0-38-generic         | 3         | 0.5%    |
| 6.6.2-desktop-1omv2390   | 3         | 0.5%    |
| 6.2.0-39-generic         | 3         | 0.5%    |
| 6.2.0-33-generic         | 3         | 0.5%    |
| 6.2.0-32-generic         | 3         | 0.5%    |
| 6.11.7-300.fc41.x86_64   | 3         | 0.5%    |
| 6.10.0-desktop-1omv2490  | 3         | 0.5%    |
| 6.1.0-21-amd64           | 3         | 0.5%    |
| 5.8.0-53-generic         | 3         | 0.5%    |
| 5.4.0-81-generic         | 3         | 0.5%    |
| 5.4.0-7642-generic       | 3         | 0.5%    |
| 5.4.0-74-generic         | 3         | 0.5%    |
| 5.4.0-65-generic         | 3         | 0.5%    |
| 5.4.0-45-generic         | 3         | 0.5%    |
| 5.4.0-26-generic         | 3         | 0.5%    |
| 5.19.0-46-generic        | 3         | 0.5%    |
| 5.15.0-60-generic        | 3         | 0.5%    |
| 5.15.0-57-generic        | 3         | 0.5%    |
| 5.15.0-53-generic        | 3         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 58        | 10.18%  |
| 5.15.0  | 50        | 8.77%   |
| 6.8.0   | 24        | 4.21%   |
| 5.13.0  | 22        | 3.86%   |
| 6.5.0   | 19        | 3.33%   |
| 5.11.0  | 18        | 3.16%   |
| 6.1.0   | 16        | 2.81%   |
| 5.3.0   | 16        | 2.81%   |
| 5.8.0   | 15        | 2.63%   |
| 6.2.0   | 14        | 2.46%   |
| 4.15.0  | 14        | 2.46%   |
| 5.10.0  | 13        | 2.28%   |
| 5.0.0   | 12        | 2.11%   |
| 5.19.0  | 11        | 1.93%   |
| 5.16.7  | 10        | 1.75%   |
| 6.1.1   | 9         | 1.58%   |
| 5.10.14 | 9         | 1.58%   |
| 6.0.12  | 7         | 1.23%   |
| 4.19.0  | 7         | 1.23%   |
| 6.4.11  | 6         | 1.05%   |
| 6.2.6   | 6         | 1.05%   |
| 4.18.0  | 6         | 1.05%   |
| 6.9.3   | 5         | 0.88%   |
| 6.8.11  | 4         | 0.7%    |
| 6.1.52  | 4         | 0.7%    |
| 5.3.16  | 4         | 0.7%    |
| 5.17.5  | 4         | 0.7%    |
| 6.6.2   | 3         | 0.53%   |
| 6.4.6   | 3         | 0.53%   |
| 6.4.10  | 3         | 0.53%   |
| 6.2.12  | 3         | 0.53%   |
| 6.11.7  | 3         | 0.53%   |
| 6.10.0  | 3         | 0.53%   |
| 5.15.4  | 3         | 0.53%   |
| 6.8.5   | 2         | 0.35%   |
| 6.7.9   | 2         | 0.35%   |
| 6.6.10  | 2         | 0.35%   |
| 6.3.1   | 2         | 0.35%   |
| 6.2.8   | 2         | 0.35%   |
| 6.12.6  | 2         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 63        | 11.31%  |
| 5.15    | 63        | 11.31%  |
| 6.1     | 36        | 6.46%   |
| 6.8     | 34        | 6.1%    |
| 5.10    | 28        | 5.03%   |
| 6.2     | 26        | 4.67%   |
| 5.13    | 25        | 4.49%   |
| 5.11    | 23        | 4.13%   |
| 6.5     | 22        | 3.95%   |
| 5.8     | 21        | 3.77%   |
| 5.3     | 21        | 3.77%   |
| 5.16    | 19        | 3.41%   |
| 6.0     | 15        | 2.69%   |
| 5.19    | 14        | 2.51%   |
| 4.15    | 14        | 2.51%   |
| 6.4     | 12        | 2.15%   |
| 6.10    | 12        | 2.15%   |
| 5.0     | 12        | 2.15%   |
| 5.18    | 9         | 1.62%   |
| 6.9     | 8         | 1.44%   |
| 5.17    | 8         | 1.44%   |
| 6.6     | 7         | 1.26%   |
| 4.19    | 7         | 1.26%   |
| 4.18    | 7         | 1.26%   |
| 6.3     | 6         | 1.08%   |
| 6.11    | 6         | 1.08%   |
| 5.6     | 6         | 1.08%   |
| 5.14    | 6         | 1.08%   |
| 5.7     | 5         | 0.9%    |
| 6.7     | 4         | 0.72%   |
| 6.12    | 4         | 0.72%   |
| 5.9     | 4         | 0.72%   |
| 4.9     | 3         | 0.54%   |
| 5.5     | 2         | 0.36%   |
| 4.20    | 2         | 0.36%   |
| 5.2     | 1         | 0.18%   |
| 4.13    | 1         | 0.18%   |
| 4.11    | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 474       | 98.14%  |
| i686   | 9         | 1.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 238       | 46.85%  |
| KDE5             | 73        | 14.37%  |
| Unknown          | 47        | 9.25%   |
| X-Cinnamon       | 39        | 7.68%   |
| XFCE             | 34        | 6.69%   |
| MATE             | 14        | 2.76%   |
| KDE              | 10        | 1.97%   |
| Pantheon         | 7         | 1.38%   |
| KDE6             | 7         | 1.38%   |
| LXQt             | 6         | 1.18%   |
| i3               | 5         | 0.98%   |
| Unity            | 4         | 0.79%   |
| Hyprland         | 4         | 0.79%   |
| Cinnamon         | 4         | 0.79%   |
| LXDE             | 3         | 0.59%   |
| Budgie           | 3         | 0.59%   |
| icewm            | 2         | 0.39%   |
| i3-with-shmlog   | 2         | 0.39%   |
| sway             | 1         | 0.2%    |
| lightdm-xsession | 1         | 0.2%    |
| KDE4             | 1         | 0.2%    |
| fluxbox          | 1         | 0.2%    |
| Endless:GNOME    | 1         | 0.2%    |
| Deepin           | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 340       | 67.46%  |
| Wayland | 141       | 27.98%  |
| Unknown | 17        | 3.37%   |
| Tty     | 6         | 1.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 235       | 46.26%  |
| SDDM    | 75        | 14.76%  |
| GDM3    | 75        | 14.76%  |
| LightDM | 57        | 11.22%  |
| GDM     | 47        | 9.25%   |
| TDM     | 11        | 2.17%   |
| Ly      | 2         | 0.39%   |
| LXDM    | 2         | 0.39%   |
| XDM     | 1         | 0.2%    |
| SLIMSKI | 1         | 0.2%    |
| SLiM    | 1         | 0.2%    |
| KDM     | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_NZ   | 299       | 58.74%  |
| en_US   | 113       | 22.2%   |
| Unknown | 33        | 6.48%   |
| en_GB   | 27        | 5.3%    |
| C       | 19        | 3.73%   |
| en_AU   | 10        | 1.96%   |
| zh_CN   | 2         | 0.39%   |
| mi_NZ   | 2         | 0.39%   |
| pt_BR   | 1         | 0.2%    |
| fr_FR   | 1         | 0.2%    |
| de_DE   | 1         | 0.2%    |
| C.UTF8  | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 262       | 53.14%  |
| BIOS | 231       | 46.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 364       | 72.08%  |
| Btrfs   | 56        | 11.09%  |
| Overlay | 40        | 7.92%   |
| Tmpfs   | 21        | 4.16%   |
| Unknown | 14        | 2.77%   |
| Zfs     | 3         | 0.59%   |
| Ext2    | 3         | 0.59%   |
| Xfs     | 2         | 0.4%    |
| XXXXXXX | 1         | 0.2%    |
| Ext3    | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 234       | 47.27%  |
| GPT     | 209       | 42.22%  |
| MBR     | 52        | 10.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 435       | 87.53%  |
| Yes       | 62        | 12.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 380       | 77.08%  |
| Yes       | 113       | 22.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 142       | 29.4%   |
| Lenovo              | 78        | 16.15%  |
| Dell                | 68        | 14.08%  |
| ASUSTek Computer    | 50        | 10.35%  |
| Acer                | 41        | 8.49%   |
| Toshiba             | 25        | 5.18%   |
| Apple               | 18        | 3.73%   |
| MSI                 | 11        | 2.28%   |
| Google              | 7         | 1.45%   |
| Sony                | 6         | 1.24%   |
| Valve               | 5         | 1.04%   |
| Samsung Electronics | 5         | 1.04%   |
| System76            | 4         | 0.83%   |
| Gigabyte Technology | 3         | 0.62%   |
| Alienware           | 3         | 0.62%   |
| HUAWEI              | 2         | 0.41%   |
| YJKC                | 1         | 0.21%   |
| TWG                 | 1         | 0.21%   |
| Timi                | 1         | 0.21%   |
| The Warehouse Group | 1         | 0.21%   |
| Star Labs           | 1         | 0.21%   |
| Panasonic           | 1         | 0.21%   |
| Metabox             | 1         | 0.21%   |
| Medion              | 1         | 0.21%   |
| Kogan               | 1         | 0.21%   |
| IBM                 | 1         | 0.21%   |
| GPD                 | 1         | 0.21%   |
| Fujitsu             | 1         | 0.21%   |
| eMachines           | 1         | 0.21%   |
| AMD                 | 1         | 0.21%   |
| Unknown             | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell XPS 13 9360                            | 7         | 1.45%   |
| HP Notebook                                 | 5         | 1.04%   |
| HP EliteBook 840 G5                         | 5         | 1.04%   |
| Valve Jupiter                               | 4         | 0.83%   |
| HP ProBook 6550b                            | 4         | 0.83%   |
| HP Pavilion dv6                             | 4         | 0.83%   |
| HP Pavilion 15                              | 4         | 0.83%   |
| HP EliteBook 850 G5                         | 4         | 0.83%   |
| Toshiba Satellite L750                      | 3         | 0.62%   |
| HP ProBook 4540s                            | 3         | 0.62%   |
| HP Pavilion Laptop 15-cw1xxx                | 3         | 0.62%   |
| HP EliteBook 8560p                          | 3         | 0.62%   |
| Dell XPS 15 9500                            | 3         | 0.62%   |
| Dell Latitude E6430                         | 3         | 0.62%   |
| Dell Latitude 7490                          | 3         | 0.62%   |
| ASUS ASUS EXPERTBOOK P2451FA_P2451FA        | 3         | 0.62%   |
| Apple MacBookPro11,3                        | 3         | 0.62%   |
| Acer Swift SF314-41                         | 3         | 0.62%   |
| Acer Aspire F5-573G                         | 3         | 0.62%   |
| Toshiba TECRA Z50-A                         | 2         | 0.41%   |
| Toshiba Satellite L850                      | 2         | 0.41%   |
| Toshiba Satellite C50-B                     | 2         | 0.41%   |
| System76 Oryx Pro                           | 2         | 0.41%   |
| MSI GE66 Raider 10SF                        | 2         | 0.41%   |
| Lenovo V15-IIL 82C5                         | 2         | 0.41%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW | 2         | 0.41%   |
| Lenovo ThinkPad T460 20FMS2FR00             | 2         | 0.41%   |
| Lenovo ThinkPad T420 4180AQ3                | 2         | 0.41%   |
| Lenovo Legion Y540-17IRH 81Q4               | 2         | 0.41%   |
| HUAWEI BOHK-WAX9X                           | 2         | 0.41%   |
| HP ZBook Firefly 15 G7 Mobile Workstation   | 2         | 0.41%   |
| HP ProBook 6570b                            | 2         | 0.41%   |
| HP ProBook 650 G1                           | 2         | 0.41%   |
| HP ProBook 4740s                            | 2         | 0.41%   |
| HP ProBook 470 G5                           | 2         | 0.41%   |
| HP ProBook 450 G6                           | 2         | 0.41%   |
| HP ProBook 450 G5                           | 2         | 0.41%   |
| HP ProBook 450 G3                           | 2         | 0.41%   |
| HP ENVY 15                                  | 2         | 0.41%   |
| HP EliteBook 8570p                          | 2         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 55        | 11.39%  |
| HP EliteBook       | 38        | 7.87%   |
| HP ProBook         | 31        | 6.42%   |
| Acer Aspire        | 26        | 5.38%   |
| HP Pavilion        | 25        | 5.18%   |
| Dell Latitude      | 25        | 5.18%   |
| Toshiba Satellite  | 18        | 3.73%   |
| Dell XPS           | 16        | 3.31%   |
| Dell Inspiron      | 11        | 2.28%   |
| ASUS Vivobook      | 11        | 2.28%   |
| ASUS ASUS          | 10        | 2.07%   |
| HP ZBook           | 9         | 1.86%   |
| HP Laptop          | 9         | 1.86%   |
| ASUS ROG           | 8         | 1.66%   |
| Lenovo IdeaPad     | 5         | 1.04%   |
| HP Notebook        | 5         | 1.04%   |
| HP ENVY            | 5         | 1.04%   |
| Dell Precision     | 5         | 1.04%   |
| Acer TravelMate    | 5         | 1.04%   |
| Valve Jupiter      | 4         | 0.83%   |
| Toshiba PORTEGE    | 4         | 0.83%   |
| Apple MacBookPro5  | 4         | 0.83%   |
| Toshiba TECRA      | 3         | 0.62%   |
| HP OMEN            | 3         | 0.62%   |
| HP Compaq          | 3         | 0.62%   |
| Dell System        | 3         | 0.62%   |
| Apple MacBookPro9  | 3         | 0.62%   |
| Apple MacBookPro11 | 3         | 0.62%   |
| Acer Swift         | 3         | 0.62%   |
| System76 Oryx      | 2         | 0.41%   |
| MSI GE66           | 2         | 0.41%   |
| Lenovo Yoga        | 2         | 0.41%   |
| Lenovo V15-IIL     | 2         | 0.41%   |
| Lenovo Legion      | 2         | 0.41%   |
| HUAWEI BOHK-WAX9X  | 2         | 0.41%   |
| HP Spectre         | 2         | 0.41%   |
| HP Presario        | 2         | 0.41%   |
| HP 14              | 2         | 0.41%   |
| Dell Vostro        | 2         | 0.41%   |
| Dell Studio        | 2         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 53        | 10.97%  |
| 2011 | 43        | 8.9%    |
| 2018 | 42        | 8.7%    |
| 2020 | 37        | 7.66%   |
| 2019 | 37        | 7.66%   |
| 2021 | 36        | 7.45%   |
| 2022 | 30        | 6.21%   |
| 2017 | 28        | 5.8%    |
| 2013 | 28        | 5.8%    |
| 2016 | 26        | 5.38%   |
| 2014 | 26        | 5.38%   |
| 2015 | 21        | 4.35%   |
| 2010 | 21        | 4.35%   |
| 2023 | 18        | 3.73%   |
| 2008 | 16        | 3.31%   |
| 2009 | 11        | 2.28%   |
| 2007 | 5         | 1.04%   |
| 2024 | 2         | 0.41%   |
| 2006 | 2         | 0.41%   |
| 2005 | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 483       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 427       | 87.5%   |
| Enabled  | 61        | 12.5%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 471       | 97.52%  |
| Yes  | 12        | 2.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 138       | 27.88%  |
| 8.01-16.0   | 91        | 18.38%  |
| 16.01-24.0  | 90        | 18.18%  |
| 3.01-4.0    | 84        | 16.97%  |
| 32.01-64.0  | 48        | 9.7%    |
| 24.01-32.0  | 13        | 2.63%   |
| 64.01-256.0 | 13        | 2.63%   |
| 1.01-2.0    | 11        | 2.22%   |
| 2.01-3.0    | 4         | 0.81%   |
| 0.51-1.0    | 3         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 167       | 30.53%  |
| 2.01-3.0   | 145       | 26.51%  |
| 4.01-8.0   | 90        | 16.45%  |
| 3.01-4.0   | 81        | 14.81%  |
| 0.51-1.0   | 31        | 5.67%   |
| 8.01-16.0  | 20        | 3.66%   |
| 16.01-24.0 | 8         | 1.46%   |
| 24.01-32.0 | 3         | 0.55%   |
| 0.01-0.5   | 2         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 379       | 75.5%   |
| 2      | 102       | 20.32%  |
| 3      | 18        | 3.59%   |
| 0      | 2         | 0.4%    |
| 4      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 312       | 63.93%  |
| Yes       | 176       | 36.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 395       | 80.78%  |
| No        | 94        | 19.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 477       | 98.76%  |
| No        | 6         | 1.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 409       | 83.13%  |
| No        | 83        | 16.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| New Zealand | 483       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Auckland         | 236       | 46.37%  |
| Wellington       | 56        | 11%     |
| Christchurch     | 48        | 9.43%   |
| Hamilton         | 28        | 5.5%    |
| Tauranga         | 17        | 3.34%   |
| Cambridge        | 13        | 2.55%   |
| Dunedin          | 12        | 2.36%   |
| Palmerston North | 11        | 2.16%   |
| Whangarei        | 9         | 1.77%   |
| Nelson           | 9         | 1.77%   |
| Lower Hutt       | 8         | 1.57%   |
| Napier City      | 7         | 1.38%   |
| New Plymouth     | 6         | 1.18%   |
| Invercargill     | 6         | 1.18%   |
| Whanganui        | 5         | 0.98%   |
| Rotorua          | 4         | 0.79%   |
| Hastings         | 4         | 0.79%   |
| Levin            | 3         | 0.59%   |
| Timaru           | 2         | 0.39%   |
| Otaki            | 2         | 0.39%   |
| Grafton          | 2         | 0.39%   |
| Blenheim         | 2         | 0.39%   |
| Ashburton        | 2         | 0.39%   |
| Whatawhata       | 1         | 0.2%    |
| Waikanae         | 1         | 0.2%    |
| Tutukaka         | 1         | 0.2%    |
| Te Puke          | 1         | 0.2%    |
| Taupo            | 1         | 0.2%    |
| Saint Andrews    | 1         | 0.2%    |
| Queenstown       | 1         | 0.2%    |
| Paraparaumu      | 1         | 0.2%    |
| Pakuranga        | 1         | 0.2%    |
| Masterton        | 1         | 0.2%    |
| Kerikeri         | 1         | 0.2%    |
| Katikati         | 1         | 0.2%    |
| Karamea          | 1         | 0.2%    |
| Gore             | 1         | 0.2%    |
| Gordonton        | 1         | 0.2%    |
| Edgecumbe        | 1         | 0.2%    |
| Bulls            | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 116       | 163    | 19.66%  |
| Seagate                     | 69        | 79     | 11.69%  |
| WDC                         | 52        | 77     | 8.81%   |
| Toshiba                     | 51        | 62     | 8.64%   |
| SanDisk                     | 32        | 34     | 5.42%   |
| Unknown                     | 31        | 43     | 5.25%   |
| SK hynix                    | 31        | 36     | 5.25%   |
| Crucial                     | 31        | 53     | 5.25%   |
| Intel                       | 26        | 32     | 4.41%   |
| Kingston                    | 19        | 28     | 3.22%   |
| Micron Technology           | 18        | 23     | 3.05%   |
| HGST                        | 15        | 16     | 2.54%   |
| Hitachi                     | 12        | 14     | 2.03%   |
| Apple                       | 7         | 8      | 1.19%   |
| Micron/Crucial Technology   | 6         | 7      | 1.02%   |
| LITEON                      | 6         | 6      | 1.02%   |
| Kingston Technology Company | 5         | 5      | 0.85%   |
| China                       | 5         | 6      | 0.85%   |
| A-DATA Technology           | 5         | 5      | 0.85%   |
| Team                        | 4         | 4      | 0.68%   |
| KIOXIA                      | 4         | 6      | 0.68%   |
| KingSpec                    | 4         | 4      | 0.68%   |
| ASMT                        | 4         | 5      | 0.68%   |
| Transcend                   | 2         | 2      | 0.34%   |
| TO Exter                    | 2         | 2      | 0.34%   |
| Silicon Motion              | 2         | 3      | 0.34%   |
| ROG                         | 2         | 2      | 0.34%   |
| Phison                      | 2         | 2      | 0.34%   |
| O2 Micro                    | 2         | 2      | 0.34%   |
| Netac                       | 2         | 2      | 0.34%   |
| JMicron Technology          | 2         | 2      | 0.34%   |
| Hewlett-Packard             | 2         | 4      | 0.34%   |
| Fujitsu                     | 2         | 2      | 0.34%   |
| XPG                         | 1         | 1      | 0.17%   |
| Timetec                     | 1         | 1      | 0.17%   |
| T-FORCE                     | 1         | 1      | 0.17%   |
| StoreJet                    | 1         | 1      | 0.17%   |
| Star Drive                  | 1         | 1      | 0.17%   |
| SSD 128G                    | 1         | 1      | 0.17%   |
| ShiJi                       | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                      | 9         | 1.46%   |
| Seagate ST1000LM035-1RK172 1TB                       | 8         | 1.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 8         | 1.29%   |
| Intel NVMe SSD Drive 512GB                           | 7         | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 6         | 0.97%   |
| Samsung SSD 860 EVO 500GB                            | 6         | 0.97%   |
| Samsung NVMe SSD Drive 512GB                         | 6         | 0.97%   |
| WDC WD10JPVX-60JC3T0 1TB                             | 5         | 0.81%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 5         | 0.81%   |
| Unknown MMC Card  64GB                               | 5         | 0.81%   |
| Seagate ST9500420AS 500GB                            | 5         | 0.81%   |
| Seagate Expansion 1TB                                | 5         | 0.81%   |
| Samsung SSD 850 EVO 500GB                            | 5         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 5         | 0.81%   |
| Intel SSDPEKNU512GZ 512GB                            | 5         | 0.81%   |
| Crucial CT500MX500SSD1 500GB                         | 5         | 0.81%   |
| WDC WD5000LPVX-22V0TT0 500GB                         | 4         | 0.65%   |
| Unknown MMC Card  32GB                               | 4         | 0.65%   |
| Unknown MMC Card  128GB                              | 4         | 0.65%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 4         | 0.65%   |
| Toshiba MQ01ABF050 500GB                             | 4         | 0.65%   |
| SanDisk NVMe SSD Drive 512GB                         | 4         | 0.65%   |
| Samsung SSD 980 1TB                                  | 4         | 0.65%   |
| Samsung SSD 870 EVO 1TB                              | 4         | 0.65%   |
| Samsung NVMe SSD Drive 256GB                         | 4         | 0.65%   |
| Kingston SV300S37A240G 240GB SSD                     | 4         | 0.65%   |
| HGST HTS721010A9E630 1TB                             | 4         | 0.65%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                     | 3         | 0.49%   |
| Unknown MMC Card  2GB                                | 3         | 0.49%   |
| Toshiba NVMe SSD Drive 512GB                         | 3         | 0.49%   |
| Toshiba MQ01ABD100 1TB                               | 3         | 0.49%   |
| Toshiba MQ01ABD075 752GB                             | 3         | 0.49%   |
| Toshiba BG3 NVMe SSD Controller 128GB                | 3         | 0.49%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 3         | 0.49%   |
| Seagate ST9500325AS 500GB                            | 3         | 0.49%   |
| Seagate ST2000LM007-1R8174 2TB                       | 3         | 0.49%   |
| Seagate ST1000LM014-1EJ164 1TB                       | 3         | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB                         | 3         | 0.49%   |
| Samsung SSD 850 EVO 1TB                              | 3         | 0.49%   |
| Samsung PM9A1 NVMe 1024GB                            | 3         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 76     | 38.6%   |
| WDC                 | 37        | 51     | 21.64%  |
| Toshiba             | 26        | 32     | 15.2%   |
| HGST                | 15        | 16     | 8.77%   |
| Hitachi             | 12        | 14     | 7.02%   |
| TO Exter            | 2         | 2      | 1.17%   |
| Samsung Electronics | 2         | 2      | 1.17%   |
| JMicron Technology  | 2         | 2      | 1.17%   |
| Fujitsu             | 2         | 2      | 1.17%   |
| ASMT                | 2         | 2      | 1.17%   |
| Unknown             | 1         | 3      | 0.58%   |
| StoreJet            | 1         | 1      | 0.58%   |
| HGST HTS            | 1         | 1      | 0.58%   |
| External            | 1         | 1      | 0.58%   |
| Apple               | 1         | 1      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 58     | 26.95%  |
| Crucial             | 26        | 48     | 15.57%  |
| SanDisk             | 16        | 16     | 9.58%   |
| Kingston            | 13        | 17     | 7.78%   |
| Micron Technology   | 8         | 11     | 4.79%   |
| Intel               | 6         | 11     | 3.59%   |
| Apple               | 6         | 7      | 3.59%   |
| WDC                 | 5         | 12     | 2.99%   |
| LITEON              | 5         | 5      | 2.99%   |
| China               | 5         | 6      | 2.99%   |
| A-DATA Technology   | 5         | 5      | 2.99%   |
| Team                | 4         | 4      | 2.4%    |
| KingSpec            | 4         | 4      | 2.4%    |
| Toshiba             | 3         | 4      | 1.8%    |
| SK hynix            | 3         | 3      | 1.8%    |
| Transcend           | 2         | 2      | 1.2%    |
| Seagate             | 2         | 2      | 1.2%    |
| Timetec             | 1         | 1      | 0.6%    |
| T-FORCE             | 1         | 1      | 0.6%    |
| OCZ                 | 1         | 1      | 0.6%    |
| Netac               | 1         | 1      | 0.6%    |
| LITEONIT            | 1         | 3      | 0.6%    |
| Lexar               | 1         | 1      | 0.6%    |
| Hewlett-Packard     | 1         | 3      | 0.6%    |
| Dell                | 1         | 1      | 0.6%    |
| Apacer              | 1         | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 202       | 279    | 36.01%  |
| HDD     | 163       | 206    | 29.06%  |
| SSD     | 159       | 228    | 28.34%  |
| MMC     | 31        | 40     | 5.53%   |
| Unknown | 6         | 6      | 1.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 290       | 410    | 52.73%  |
| NVMe | 202       | 276    | 36.73%  |
| MMC  | 31        | 40     | 5.64%   |
| SAS  | 27        | 33     | 4.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 211       | 285    | 64.53%  |
| 0.51-1.0   | 98        | 130    | 29.97%  |
| 1.01-2.0   | 15        | 16     | 4.59%   |
| 4.01-10.0  | 2         | 2      | 0.61%   |
| 10.01-20.0 | 1         | 1      | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 131       | 25.69%  |
| 101-250        | 131       | 25.69%  |
| 501-1000       | 79        | 15.49%  |
| 1-20           | 44        | 8.63%   |
| 1001-2000      | 37        | 7.25%   |
| 51-100         | 31        | 6.08%   |
| 21-50          | 19        | 3.73%   |
| Unknown        | 14        | 2.75%   |
| More than 3000 | 13        | 2.55%   |
| 2001-3000      | 11        | 2.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 203       | 37.8%   |
| 21-50          | 106       | 19.74%  |
| 101-250        | 68        | 12.66%  |
| 51-100         | 65        | 12.1%   |
| 251-500        | 36        | 6.7%    |
| 501-1000       | 32        | 5.96%   |
| Unknown        | 14        | 2.61%   |
| 1001-2000      | 8         | 1.49%   |
| More than 3000 | 3         | 0.56%   |
| 2001-3000      | 2         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 2      | 5%      |
| WDC WD7500BPKX-00HPJT0 752GB                        | 1         | 1      | 2.5%    |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 2.5%    |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.5%    |
| Toshiba MK5076GSX 500GB                             | 1         | 1      | 2.5%    |
| Toshiba MK5065GSXF 500GB                            | 1         | 1      | 2.5%    |
| Toshiba MK3261GSYN 320GB                            | 1         | 1      | 2.5%    |
| Toshiba MK3256GSY 320GB                             | 1         | 1      | 2.5%    |
| SK hynix SC308 SATA 128GB SSD                       | 1         | 1      | 2.5%    |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 3      | 2.5%    |
| SK hynix BC501 HFM512GDJTNG-8310A 512GB             | 1         | 1      | 2.5%    |
| ShiJi 512GB M.2-NVMe                                | 1         | 1      | 2.5%    |
| Seagate ST9500420ASG 500GB                          | 1         | 1      | 2.5%    |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 2.5%    |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 2.5%    |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.5%    |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 2.5%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD                 | 1         | 1      | 2.5%    |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 2.5%    |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 2.5%    |
| Intel SSDSCKKW240H6 240GB                           | 1         | 1      | 2.5%    |
| Intel SSDSC2KF256H6 SATA 256GB                      | 1         | 3      | 2.5%    |
| Intel SSDPEKKF512G7H BTPY71141D7T512F 512GB         | 1         | 1      | 2.5%    |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 2.5%    |
| Hitachi HTS545032B9SA00 320GB                       | 1         | 1      | 2.5%    |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2.5%    |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 2.5%    |
| HGST HTS545050A7E680 500GB                          | 1         | 2      | 2.5%    |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 2.5%    |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 2.5%    |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.5%    |
| HGST HTS 541075A9E680 752GB                         | 1         | 1      | 2.5%    |
| HGST HCC545050A7E380 500GB                          | 1         | 1      | 2.5%    |
| Crucial CT525MX300SSD1 528GB                        | 1         | 1      | 2.5%    |
| Crucial CT275MX300SSD1 275GB                        | 1         | 1      | 2.5%    |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 2.5%    |
| ASMT ASM105x 500GB                                  | 1         | 1      | 2.5%    |
| Apple HDD HTS547550A9E384 500GB                     | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 7         | 8      | 17.95%  |
| Toshiba             | 5         | 5      | 12.82%  |
| Seagate             | 5         | 5      | 12.82%  |
| Intel               | 3         | 5      | 7.69%   |
| Crucial             | 3         | 3      | 7.69%   |
| WDC                 | 2         | 2      | 5.13%   |
| SK hynix            | 2         | 5      | 5.13%   |
| SanDisk             | 2         | 2      | 5.13%   |
| Samsung Electronics | 2         | 2      | 5.13%   |
| Micron Technology   | 2         | 2      | 5.13%   |
| Hitachi             | 2         | 2      | 5.13%   |
| ShiJi               | 1         | 1      | 2.56%   |
| HGST HTS            | 1         | 1      | 2.56%   |
| ASMT                | 1         | 1      | 2.56%   |
| Apple               | 1         | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| HGST     | 7         | 8      | 29.17%  |
| Toshiba  | 5         | 5      | 20.83%  |
| Seagate  | 5         | 5      | 20.83%  |
| WDC      | 2         | 2      | 8.33%   |
| Hitachi  | 2         | 2      | 8.33%   |
| HGST HTS | 1         | 1      | 4.17%   |
| ASMT     | 1         | 1      | 4.17%   |
| Apple    | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 25     | 61.54%  |
| SSD  | 11        | 13     | 28.21%  |
| NVMe | 4         | 7      | 10.26%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 286       | 455    | 55.43%  |
| Works    | 191       | 258    | 37.02%  |
| Malfunc  | 38        | 45     | 7.36%   |
| Failed   | 1         | 1      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 315       | 54.69%  |
| Samsung Electronics          | 77        | 13.37%  |
| AMD                          | 51        | 8.85%   |
| SK hynix                     | 28        | 4.86%   |
| SanDisk                      | 26        | 4.51%   |
| Toshiba America Info Systems | 23        | 3.99%   |
| Micron/Crucial Technology    | 11        | 1.91%   |
| Kingston Technology Company  | 11        | 1.91%   |
| Micron Technology            | 10        | 1.74%   |
| Nvidia                       | 9         | 1.56%   |
| Phison Electronics           | 4         | 0.69%   |
| KIOXIA                       | 3         | 0.52%   |
| Silicon Motion               | 2         | 0.35%   |
| O2 Micro                     | 2         | 0.35%   |
| Solidigm                     | 1         | 0.17%   |
| Netac Technology             | 1         | 0.17%   |
| Lite-On Technology           | 1         | 0.17%   |
| ADATA Technology             | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 45        | 7.39%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 45        | 7.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 34        | 5.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 33        | 5.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 32        | 5.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 20        | 3.28%   |
| Intel Volume Management Device NVMe RAID Controller                              | 18        | 2.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 17        | 2.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 16        | 2.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 14        | 2.3%    |
| Intel Comet Lake SATA AHCI Controller                                            | 12        | 1.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 1.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 1.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 11        | 1.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 10        | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 1.64%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 9         | 1.48%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 9         | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 9         | 1.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 1.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 1.48%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 8         | 1.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 1.31%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 7         | 1.15%   |
| Intel SSD 660P Series                                                            | 7         | 1.15%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.99%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 6         | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 6         | 0.99%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 5         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 4         | 0.66%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 4         | 0.66%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                        | 4         | 0.66%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 0.66%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 4         | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 323       | 55.21%  |
| NVMe | 203       | 34.7%   |
| RAID | 43        | 7.35%   |
| IDE  | 16        | 2.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 396       | 81.99%  |
| AMD    | 87        | 18.01%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 2.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 1.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 1.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 1.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 1.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 1.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.24%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 1.24%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.24%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 6         | 1.24%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.04%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 1.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.04%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 1.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.04%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 5         | 1.04%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 5         | 1.04%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 5         | 1.04%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.04%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics    | 5         | 1.04%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.83%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.83%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 4         | 0.83%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 4         | 0.83%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 0.83%   |
| Intel 12th Gen Core i5-12500H                 | 4         | 0.83%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 0.83%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.83%   |
| AMD Custom APU 0405                           | 4         | 0.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.62%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.62%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.62%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.62%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 0.62%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz            | 3         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 130       | 26.92%  |
| Intel Core i5                  | 130       | 26.92%  |
| Other                          | 52        | 10.77%  |
| Intel Core 2 Duo               | 26        | 5.38%   |
| Intel Celeron                  | 24        | 4.97%   |
| Intel Core i3                  | 22        | 4.55%   |
| AMD Ryzen 7                    | 14        | 2.9%    |
| AMD Ryzen 5                    | 13        | 2.69%   |
| AMD A6                         | 9         | 1.86%   |
| AMD Ryzen 9                    | 7         | 1.45%   |
| AMD Ryzen 5 PRO                | 7         | 1.45%   |
| Intel Pentium                  | 6         | 1.24%   |
| AMD E2                         | 5         | 1.04%   |
| Intel Atom                     | 4         | 0.83%   |
| AMD A8                         | 4         | 0.83%   |
| AMD A4                         | 4         | 0.83%   |
| Intel Core i9                  | 3         | 0.62%   |
| Intel Pentium Silver           | 2         | 0.41%   |
| Intel Pentium M                | 2         | 0.41%   |
| AMD Ryzen 7 PRO                | 2         | 0.41%   |
| AMD Ryzen 3                    | 2         | 0.41%   |
| AMD E1                         | 2         | 0.41%   |
| AMD E                          | 2         | 0.41%   |
| Intel Xeon                     | 1         | 0.21%   |
| Intel Genuine                  | 1         | 0.21%   |
| Intel Core m7                  | 1         | 0.21%   |
| Intel Core                     | 1         | 0.21%   |
| Intel Celeron Dual-Core        | 1         | 0.21%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.21%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.21%   |
| AMD G                          | 1         | 0.21%   |
| AMD Athlon II                  | 1         | 0.21%   |
| AMD A12                        | 1         | 0.21%   |
| AMD A10                        | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 227       | 46.9%   |
| 4      | 156       | 32.23%  |
| 6      | 35        | 7.23%   |
| 8      | 31        | 6.4%    |
| 14     | 10        | 2.07%   |
| 10     | 9         | 1.86%   |
| 12     | 8         | 1.65%   |
| 1      | 7         | 1.45%   |
| 24     | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 483       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 375       | 77.32%  |
| 1      | 109       | 22.47%  |
| 8      | 1         | 0.21%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 475       | 97.34%  |
| Unknown        | 10        | 2.05%   |
| 32-bit         | 3         | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 206       | 41.04%  |
| 0x206a7    | 32        | 6.37%   |
| 0x306a9    | 28        | 5.58%   |
| 0x806ea    | 16        | 3.19%   |
| 0x806ec    | 14        | 2.79%   |
| 0x406e3    | 14        | 2.79%   |
| 0x1067a    | 12        | 2.39%   |
| 0x806e9    | 10        | 1.99%   |
| 0x20655    | 9         | 1.79%   |
| 0x306c3    | 8         | 1.59%   |
| 0x30678    | 8         | 1.59%   |
| 0xa0652    | 7         | 1.39%   |
| 0x40651    | 7         | 1.39%   |
| 0x306d4    | 7         | 1.39%   |
| 0x10676    | 7         | 1.39%   |
| 0x0a50000d | 7         | 1.39%   |
| 0x906a4    | 6         | 1.2%    |
| 0x07030105 | 6         | 1.2%    |
| 0x906e9    | 5         | 1%      |
| 0x08108109 | 5         | 1%      |
| 0x906ea    | 4         | 0.8%    |
| 0x906a3    | 4         | 0.8%    |
| 0x806c1    | 4         | 0.8%    |
| 0x506e3    | 4         | 0.8%    |
| 0x506c9    | 4         | 0.8%    |
| 0x0a50000c | 4         | 0.8%    |
| 0x06006705 | 4         | 0.8%    |
| 0x806d1    | 3         | 0.6%    |
| 0x706a8    | 3         | 0.6%    |
| 0x6fd      | 3         | 0.6%    |
| 0x08600106 | 3         | 0.6%    |
| 0x08108102 | 3         | 0.6%    |
| 0x06001119 | 3         | 0.6%    |
| 0x05000119 | 3         | 0.6%    |
| 0xa0660    | 2         | 0.4%    |
| 0x906ed    | 2         | 0.4%    |
| 0x906c0    | 2         | 0.4%    |
| 0x806eb    | 2         | 0.4%    |
| 0x706a1    | 2         | 0.4%    |
| 0x6d8      | 2         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 94        | 19.38%  |
| SandyBridge       | 45        | 9.28%   |
| IvyBridge         | 43        | 8.87%   |
| Haswell           | 32        | 6.6%    |
| Skylake           | 27        | 5.57%   |
| Unknown           | 25        | 5.15%   |
| Penryn            | 23        | 4.74%   |
| Alderlake Hybrid  | 21        | 4.33%   |
| CometLake         | 17        | 3.51%   |
| Zen 3             | 16        | 3.3%    |
| Silvermont        | 16        | 3.3%    |
| Westmere          | 14        | 2.89%   |
| Excavator         | 13        | 2.68%   |
| Zen+              | 12        | 2.47%   |
| TigerLake         | 11        | 2.27%   |
| Broadwell         | 11        | 2.27%   |
| Puma              | 10        | 2.06%   |
| IceLake           | 8         | 1.65%   |
| Zen 2             | 5         | 1.03%   |
| Nehalem           | 5         | 1.03%   |
| Goldmont plus     | 5         | 1.03%   |
| Goldmont          | 5         | 1.03%   |
| Core              | 5         | 1.03%   |
| Jaguar            | 4         | 0.82%   |
| Bobcat            | 4         | 0.82%   |
| Piledriver        | 3         | 0.62%   |
| Bonnell           | 3         | 0.62%   |
| Tremont           | 2         | 0.41%   |
| P6                | 2         | 0.41%   |
| Meteorlake Hybrid | 1         | 0.21%   |
| K8 Hammer         | 1         | 0.21%   |
| K8 & K10 hybrid   | 1         | 0.21%   |
| K10               | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 348       | 56.86%  |
| Nvidia | 133       | 21.73%  |
| AMD    | 131       | 21.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 39        | 6.1%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 37        | 5.79%   |
| Intel UHD Graphics 620                                                                   | 27        | 4.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 2.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 2.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 2.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 2.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 2.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 1.88%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 1.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 1.88%   |
| Intel HD Graphics 620                                                                    | 11        | 1.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 1.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 1.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 1.56%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 10        | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 1.41%   |
| Intel HD Graphics 630                                                                    | 8         | 1.25%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.1%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 7         | 1.1%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 6         | 0.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 6         | 0.94%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 0.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 0.78%   |
| Intel HD Graphics 530                                                                    | 5         | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.78%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 5         | 0.78%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 5         | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 0.63%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.63%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 4         | 0.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.63%   |
| Intel HD Graphics 500                                                                    | 4         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 227       | 47%     |
| Intel + Nvidia | 92        | 19.05%  |
| 1 x AMD        | 77        | 15.94%  |
| 1 x Nvidia     | 28        | 5.8%    |
| Intel + AMD    | 27        | 5.59%   |
| 2 x AMD        | 18        | 3.73%   |
| AMD + Nvidia   | 9         | 1.86%   |
| 2 x Nvidia     | 3         | 0.62%   |
| Other          | 1         | 0.21%   |
| 2 x Intel      | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 404       | 82.62%  |
| Proprietary | 69        | 14.11%  |
| Unknown     | 16        | 3.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 334       | 67.07%  |
| 0.01-0.5   | 46        | 9.24%   |
| 1.01-2.0   | 38        | 7.63%   |
| 0.51-1.0   | 32        | 6.43%   |
| 3.01-4.0   | 28        | 5.62%   |
| 5.01-6.0   | 9         | 1.81%   |
| 7.01-8.0   | 7         | 1.41%   |
| 2.01-3.0   | 2         | 0.4%    |
| 8.01-16.0  | 2         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 100       | 17.51%  |
| LG Display              | 79        | 13.84%  |
| Chimei Innolux          | 74        | 12.96%  |
| Samsung Electronics     | 61        | 10.68%  |
| BOE                     | 60        | 10.51%  |
| Dell                    | 25        | 4.38%   |
| Goldstar                | 20        | 3.5%    |
| Sharp                   | 18        | 3.15%   |
| Chi Mei Optoelectronics | 17        | 2.98%   |
| Apple                   | 16        | 2.8%    |
| AOC                     | 14        | 2.45%   |
| PANDA                   | 8         | 1.4%    |
| InfoVision              | 8         | 1.4%    |
| Philips                 | 6         | 1.05%   |
| Lenovo                  | 6         | 1.05%   |
| Hewlett-Packard         | 5         | 0.88%   |
| ViewSonic               | 4         | 0.7%    |
| Valve                   | 4         | 0.7%    |
| Sony                    | 4         | 0.7%    |
| TMX                     | 3         | 0.53%   |
| Panasonic               | 3         | 0.53%   |
| Denver                  | 3         | 0.53%   |
| Acer                    | 3         | 0.53%   |
| Quanta Display          | 2         | 0.35%   |
| InnoLux Display         | 2         | 0.35%   |
| HannStar                | 2         | 0.35%   |
| Gigabyte Technology     | 2         | 0.35%   |
| Ancor Communications    | 2         | 0.35%   |
| Yamaha                  | 1         | 0.18%   |
| Wacom                   | 1         | 0.18%   |
| Toshiba                 | 1         | 0.18%   |
| TCL                     | 1         | 0.18%   |
| SKY                     | 1         | 0.18%   |
| SANYO                   | 1         | 0.18%   |
| PRISM+                  | 1         | 0.18%   |
| MStar                   | 1         | 0.18%   |
| MSI                     | 1         | 0.18%   |
| MiTAC                   | 1         | 0.18%   |
| Mi                      | 1         | 0.18%   |
| LGD                     | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 6         | 1.02%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.85%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 4         | 0.68%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 4         | 0.68%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 4         | 0.68%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.68%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 0.68%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 3         | 0.51%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 3         | 0.51%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 3         | 0.51%   |
| LG Display LCD Monitor LGD056E 1920x1080 344x194mm 15.5-inch             | 3         | 0.51%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 3         | 0.51%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 3         | 0.51%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 3         | 0.51%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 3         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch            | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.51%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 2         | 0.34%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 2         | 0.34%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch        | 2         | 0.34%   |
| Samsung Electronics LU28R55 SAM1019 3840x2160 632x360mm 28.6-inch        | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch    | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch    | 2         | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.34%   |
| Panasonic TV MEIA0A6 1920x1080 698x392mm 31.5-inch                       | 2         | 0.34%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch             | 2         | 0.34%   |
| LG Display LCD Monitor LGD041E 1920x1080 345x194mm 15.6-inch             | 2         | 0.34%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 2         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 222       | 40.96%  |
| 1366x768 (WXGA)    | 138       | 25.46%  |
| 1600x900 (HD+)     | 33        | 6.09%   |
| 3840x2160 (4K)     | 27        | 4.98%   |
| 2560x1440 (QHD)    | 21        | 3.87%   |
| 1280x800 (WXGA)    | 20        | 3.69%   |
| 1920x1200 (WUXGA)  | 18        | 3.32%   |
| 1440x900 (WXGA+)   | 10        | 1.85%   |
| 3440x1440          | 9         | 1.66%   |
| 2880x1800          | 7         | 1.29%   |
| 3200x1800 (QHD+)   | 5         | 0.92%   |
| 800x1280           | 4         | 0.74%   |
| 2560x1600          | 4         | 0.74%   |
| 3456x2160          | 3         | 0.55%   |
| 1680x1050 (WSXGA+) | 3         | 0.55%   |
| 1280x1024 (SXGA)   | 3         | 0.55%   |
| 1024x600           | 3         | 0.55%   |
| 3840x1600          | 2         | 0.37%   |
| 3200x2000          | 2         | 0.37%   |
| 1920x540           | 2         | 0.37%   |
| 3840x2400          | 1         | 0.18%   |
| 2880x1920          | 1         | 0.18%   |
| 2560x1080          | 1         | 0.18%   |
| 1920x1280          | 1         | 0.18%   |
| 1360x768           | 1         | 0.18%   |
| 1280x720 (HD)      | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 215       | 37.26%  |
| 13      | 80        | 13.86%  |
| 14      | 74        | 12.82%  |
| 17      | 42        | 7.28%   |
| 27      | 28        | 4.85%   |
| 31      | 15        | 2.6%    |
| 24      | 14        | 2.43%   |
| 23      | 14        | 2.43%   |
| 16      | 11        | 1.91%   |
| 21      | 10        | 1.73%   |
| 11      | 9         | 1.56%   |
| 12      | 8         | 1.39%   |
| 34      | 6         | 1.04%   |
| Unknown | 6         | 1.04%   |
| 10      | 5         | 0.87%   |
| 7       | 5         | 0.87%   |
| 72      | 3         | 0.52%   |
| 37      | 3         | 0.52%   |
| 22      | 3         | 0.52%   |
| 20      | 3         | 0.52%   |
| 19      | 3         | 0.52%   |
| 84      | 2         | 0.35%   |
| 46      | 2         | 0.35%   |
| 35      | 2         | 0.35%   |
| 29      | 2         | 0.35%   |
| 28      | 2         | 0.35%   |
| 18      | 2         | 0.35%   |
| 95      | 1         | 0.17%   |
| 64      | 1         | 0.17%   |
| 60      | 1         | 0.17%   |
| 54      | 1         | 0.17%   |
| 52      | 1         | 0.17%   |
| 40      | 1         | 0.17%   |
| 33      | 1         | 0.17%   |
| 25      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 340       | 59.54%  |
| 201-300     | 55        | 9.63%   |
| 501-600     | 53        | 9.28%   |
| 351-400     | 48        | 8.41%   |
| 601-700     | 21        | 3.68%   |
| 401-500     | 19        | 3.33%   |
| 701-800     | 7         | 1.23%   |
| 801-900     | 6         | 1.05%   |
| 1001-1500   | 6         | 1.05%   |
| Unknown     | 6         | 1.05%   |
| 1501-2000   | 5         | 0.88%   |
| 1-100       | 4         | 0.7%    |
| 101-200     | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 397       | 80.2%   |
| 16/10   | 69        | 13.94%  |
| 21/9    | 12        | 2.42%   |
| Unknown | 4         | 0.81%   |
| 5/4     | 3         | 0.61%   |
| 3/2     | 3         | 0.61%   |
| 0.67    | 3         | 0.61%   |
| 4/3     | 2         | 0.4%    |
| 32/9    | 1         | 0.2%    |
| 0.62    | 1         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 212       | 36.87%  |
| 81-90          | 128       | 22.26%  |
| 121-130        | 39        | 6.78%   |
| 201-250        | 36        | 6.26%   |
| 301-350        | 28        | 4.87%   |
| 351-500        | 27        | 4.7%    |
| 71-80          | 26        | 4.52%   |
| 111-120        | 12        | 2.09%   |
| More than 1000 | 9         | 1.57%   |
| 51-60          | 9         | 1.57%   |
| 151-200        | 8         | 1.39%   |
| 61-70          | 7         | 1.22%   |
| 501-1000       | 6         | 1.04%   |
| Unknown        | 6         | 1.04%   |
| 41-50          | 5         | 0.87%   |
| 1-40           | 5         | 0.87%   |
| 251-300        | 5         | 0.87%   |
| 141-150        | 3         | 0.52%   |
| 131-140        | 3         | 0.52%   |
| 91-100         | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 217       | 38.61%  |
| 101-120       | 177       | 31.49%  |
| 51-100        | 88        | 15.66%  |
| 161-240       | 44        | 7.83%   |
| More than 240 | 20        | 3.56%   |
| 1-50          | 10        | 1.78%   |
| Unknown       | 6         | 1.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 381       | 75.9%   |
| 2     | 89        | 17.73%  |
| 3     | 16        | 3.19%   |
| 0     | 14        | 2.79%   |
| 4     | 2         | 0.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 286       | 37.05%  |
| Realtek Semiconductor             | 239       | 30.96%  |
| Qualcomm Atheros                  | 89        | 11.53%  |
| Broadcom                          | 47        | 6.09%   |
| MediaTek                          | 21        | 2.72%   |
| Broadcom Limited                  | 10        | 1.3%    |
| TP-Link                           | 9         | 1.17%   |
| Ralink                            | 8         | 1.04%   |
| Hewlett-Packard                   | 8         | 1.04%   |
| Nvidia                            | 7         | 0.91%   |
| DisplayLink                       | 5         | 0.65%   |
| Sierra Wireless                   | 4         | 0.52%   |
| ASIX Electronics                  | 4         | 0.52%   |
| Qualcomm                          | 3         | 0.39%   |
| OPPO Electronics                  | 3         | 0.39%   |
| Marvell Technology Group          | 3         | 0.39%   |
| Lenovo                            | 3         | 0.39%   |
| Dell                              | 3         | 0.39%   |
| Samsung Electronics               | 2         | 0.26%   |
| JMicron Technology                | 2         | 0.26%   |
| Xiaomi                            | 1         | 0.13%   |
| vivo                              | 1         | 0.13%   |
| U-Blox                            | 1         | 0.13%   |
| Toshiba                           | 1         | 0.13%   |
| STMicroelectronics                | 1         | 0.13%   |
| QinHeng Electronics               | 1         | 0.13%   |
| NetGear                           | 1         | 0.13%   |
| Microsoft                         | 1         | 0.13%   |
| Lite-On Technology                | 1         | 0.13%   |
| ICS Advent                        | 1         | 0.13%   |
| Fujitsu                           | 1         | 0.13%   |
| Fibocom                           | 1         | 0.13%   |
| Espressi                          | 1         | 0.13%   |
| Ericsson Business Mobile Networks | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |
| Attansic Technology               | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 143       | 15.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 37        | 3.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 31        | 3.3%    |
| Intel Wireless 8265 / 8275                                             | 26        | 2.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 2.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 23        | 2.45%   |
| Intel Wi-Fi 6 AX200                                                    | 22        | 2.34%   |
| Intel Wireless 7260                                                    | 19        | 2.02%   |
| Intel Wireless 8260                                                    | 18        | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 17        | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 16        | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 15        | 1.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 15        | 1.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 14        | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 12        | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 12        | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 12        | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 11        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 11        | 1.17%   |
| Intel Wireless 7265                                                    | 11        | 1.17%   |
| Intel Centrino Ultimate-N 6300                                         | 11        | 1.17%   |
| Intel Wireless 3165                                                    | 10        | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 1.06%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 9         | 0.96%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 0.85%   |
| Intel Centrino Advanced-N 6200                                         | 8         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 8         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 7         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 0.74%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 0.74%   |
| Intel Centrino Wireless-N 2230                                         | 7         | 0.74%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 7         | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.64%   |
| Nvidia MCP79 Ethernet                                                  | 6         | 0.64%   |
| Intel Wireless 3160                                                    | 6         | 0.64%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.64%   |
| Intel WiFi Link 5100                                                   | 5         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 273       | 53.95%  |
| Qualcomm Atheros      | 80        | 15.81%  |
| Realtek Semiconductor | 49        | 9.68%   |
| Broadcom              | 38        | 7.51%   |
| MediaTek              | 20        | 3.95%   |
| Broadcom Limited      | 10        | 1.98%   |
| TP-Link               | 9         | 1.78%   |
| Ralink                | 8         | 1.58%   |
| Sierra Wireless       | 4         | 0.79%   |
| Qualcomm              | 3         | 0.59%   |
| Hewlett-Packard       | 3         | 0.59%   |
| Dell                  | 3         | 0.59%   |
| Samsung Electronics   | 1         | 0.2%    |
| NetGear               | 1         | 0.2%    |
| Microsoft             | 1         | 0.2%    |
| Lite-On Technology    | 1         | 0.2%    |
| Fibocom               | 1         | 0.2%    |
| D-Link                | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 26        | 5.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 4.53%   |
| Intel Wi-Fi 6 AX200                                            | 22        | 4.33%   |
| Intel Wireless 7260                                            | 19        | 3.74%   |
| Intel Wireless 8260                                            | 18        | 3.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 17        | 3.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 3.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 2.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 2.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 14        | 2.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 2.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 12        | 2.36%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 2.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 11        | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 2.17%   |
| Intel Wireless 7265                                            | 11        | 2.17%   |
| Intel Centrino Ultimate-N 6300                                 | 11        | 2.17%   |
| Intel Wireless 3165                                            | 10        | 1.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 1.77%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 1.57%   |
| Intel Centrino Advanced-N 6200                                 | 8         | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8         | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 1.38%   |
| Intel Centrino Wireless-N 2230                                 | 7         | 1.38%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 7         | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.18%   |
| Intel Wireless 3160                                            | 6         | 1.18%   |
| Intel WiFi Link 5100                                           | 5         | 0.98%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 0.98%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 4         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.79%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.79%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 4         | 0.79%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 4         | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.79%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 3         | 0.59%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 222       | 53.49%  |
| Intel                    | 120       | 28.92%  |
| Qualcomm Atheros         | 23        | 5.54%   |
| Broadcom                 | 16        | 3.86%   |
| Nvidia                   | 7         | 1.69%   |
| DisplayLink              | 5         | 1.2%    |
| ASIX Electronics         | 4         | 0.96%   |
| OPPO Electronics         | 3         | 0.72%   |
| Marvell Technology Group | 3         | 0.72%   |
| Lenovo                   | 3         | 0.72%   |
| JMicron Technology       | 2         | 0.48%   |
| Xiaomi                   | 1         | 0.24%   |
| vivo                     | 1         | 0.24%   |
| Samsung Electronics      | 1         | 0.24%   |
| QinHeng Electronics      | 1         | 0.24%   |
| MediaTek                 | 1         | 0.24%   |
| ICS Advent               | 1         | 0.24%   |
| Attansic Technology      | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 143       | 34.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 37        | 8.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 31        | 7.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 5.95%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 2.38%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 2.14%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 1.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 1.67%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 1.67%   |
| Nvidia MCP79 Ethernet                                                  | 6         | 1.43%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 1.43%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 1.19%   |
| Intel 82577LC Gigabit Network Connection                               | 5         | 1.19%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 0.95%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 4         | 0.95%   |
| Intel Ethernet Connection (10) I219-V                                  | 4         | 0.95%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 3         | 0.71%   |
| Intel Ethernet Connection I217-V                                       | 3         | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.48%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 0.48%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.48%   |
| OPPO OnePlus Nord 4                                                    | 2         | 0.48%   |
| Lenovo USB-C Dock Ethernet                                             | 2         | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 0.48%   |
| Intel Killer E3100 2.5 Gigabit Ethernet Controller                     | 2         | 0.48%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.48%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.48%   |
| Intel Ethernet Connection (3) I218-V                                   | 2         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 477       | 53.96%  |
| Ethernet | 395       | 44.68%  |
| Modem    | 12        | 1.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 410       | 78.39%  |
| Ethernet | 113       | 21.61%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 348       | 72.05%  |
| 1     | 125       | 25.88%  |
| 3     | 7         | 1.45%   |
| 0     | 3         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 409       | 82.63%  |
| Yes  | 86        | 17.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 214       | 51.94%  |
| Qualcomm Atheros Communications | 34        | 8.25%   |
| IMC Networks                    | 24        | 5.83%   |
| Broadcom                        | 24        | 5.83%   |
| Realtek Semiconductor           | 21        | 5.1%    |
| Lite-On Technology              | 19        | 4.61%   |
| Foxconn / Hon Hai               | 17        | 4.13%   |
| Apple                           | 17        | 4.13%   |
| Hewlett-Packard                 | 16        | 3.88%   |
| Toshiba                         | 6         | 1.46%   |
| Dell                            | 4         | 0.97%   |
| Ralink Technology               | 3         | 0.73%   |
| Realtek                         | 2         | 0.49%   |
| Ralink                          | 2         | 0.49%   |
| Edimax Technology               | 2         | 0.49%   |
| ASUSTek Computer                | 2         | 0.49%   |
| Alps Electric                   | 2         | 0.49%   |
| USI                             | 1         | 0.24%   |
| MediaTek                        | 1         | 0.24%   |
| Cambridge Silicon Radio         | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 84        | 20.39%  |
| Intel AX201 Bluetooth                            | 38        | 9.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 25        | 6.07%   |
| Intel AX200 Bluetooth                            | 22        | 5.34%   |
| Intel AX211 Bluetooth                            | 15        | 3.64%   |
| Qualcomm Atheros  Bluetooth Device               | 13        | 3.16%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 13        | 3.16%   |
| IMC Networks Wireless_Device                     | 13        | 3.16%   |
| HP Broadcom 2070 Bluetooth Combo                 | 11        | 2.67%   |
| Realtek Bluetooth Radio                          | 10        | 2.43%   |
| Realtek  Bluetooth 4.2 Adapter                   | 9         | 2.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 9         | 2.18%   |
| IMC Networks Bluetooth Radio                     | 9         | 2.18%   |
| Apple Bluetooth Host Controller                  | 9         | 2.18%   |
| Lite-On Bluetooth Device                         | 7         | 1.7%    |
| Apple Bluetooth USB Host Controller              | 7         | 1.7%    |
| Lite-On Atheros AR3012 Bluetooth                 | 6         | 1.46%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 6         | 1.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 5         | 1.21%   |
| Intel Wireless-AC 3168 Bluetooth                 | 5         | 1.21%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter     | 5         | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device               | 5         | 1.21%   |
| Broadcom BCM2045B (BDC-2.1)                      | 5         | 1.21%   |
| Qualcomm Atheros AR3011 Bluetooth                | 4         | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 4         | 0.97%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 4         | 0.97%   |
| Broadcom HP Portable SoftSailing                 | 4         | 0.97%   |
| Broadcom BCM20702A0                              | 4         | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 3         | 0.73%   |
| Intel AX210 Bluetooth                            | 3         | 0.73%   |
| Foxconn / Hon Hai Acer Module                    | 3         | 0.73%   |
| Toshiba Bluetooth USB Host Controller            | 2         | 0.49%   |
| Toshiba Bluetooth Radio                          | 2         | 0.49%   |
| Realtek Bluetooth Radio                          | 2         | 0.49%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter     | 2         | 0.49%   |
| Ralink RT3290 Bluetooth                          | 2         | 0.49%   |
| Qualcomm Atheros AR9462 Bluetooth                | 2         | 0.49%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 2         | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                 | 2         | 0.49%   |
| Broadcom BCM43142A0 Bluetooth Device             | 2         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 385       | 61.5%   |
| AMD                                             | 105       | 16.77%  |
| Nvidia                                          | 82        | 13.1%   |
| Hewlett-Packard                                 | 9         | 1.44%   |
| Realtek Semiconductor                           | 6         | 0.96%   |
| Plantronics                                     | 4         | 0.64%   |
| Logitech                                        | 4         | 0.64%   |
| Lenovo                                          | 3         | 0.48%   |
| SteelSeries ApS                                 | 2         | 0.32%   |
| JMTek                                           | 2         | 0.32%   |
| Generalplus Technology                          | 2         | 0.32%   |
| C-Media Electronics                             | 2         | 0.32%   |
| Texas Instruments                               | 1         | 0.16%   |
| Tenx Technology                                 | 1         | 0.16%   |
| Sony                                            | 1         | 0.16%   |
| Sennheiser Communications                       | 1         | 0.16%   |
| Samson Technologies                             | 1         | 0.16%   |
| Microsoft                                       | 1         | 0.16%   |
| Micro Star International                        | 1         | 0.16%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.16%   |
| Huawei Technologies                             | 1         | 0.16%   |
| Harman                                          | 1         | 0.16%   |
| GYROCOM C&C                                     | 1         | 0.16%   |
| Google                                          | 1         | 0.16%   |
| GN Netcom                                       | 1         | 0.16%   |
| FiiO Electronics Technology                     | 1         | 0.16%   |
| Creative Technology                             | 1         | 0.16%   |
| Conexant Systems                                | 1         | 0.16%   |
| CMX Systems                                     | 1         | 0.16%   |
| ClearOne Communications                         | 1         | 0.16%   |
| Belkin Components                               | 1         | 0.16%   |
| AST Research                                    | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 60        | 8.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 50        | 6.69%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 45        | 6.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 38        | 5.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 24        | 3.21%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 19        | 2.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 19        | 2.54%   |
| AMD FCH Azalia Controller                                                  | 19        | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 17        | 2.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 2.14%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 2.14%   |
| AMD Kabini HDMI/DP Audio                                                   | 16        | 2.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 2.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 15        | 2.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 2.01%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 1.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 1.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 13        | 1.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 13        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 1.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 1.47%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 11        | 1.47%   |
| AMD High Definition Audio Controller                                       | 11        | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9         | 1.2%    |
| Intel CM238 HD Audio Controller                                            | 9         | 1.2%    |
| Hewlett-Packard USB Audio                                                  | 9         | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.07%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 0.94%   |
| Realtek Semiconductor USB Audio                                            | 6         | 0.8%    |
| Nvidia MCP79 High Definition Audio                                         | 6         | 0.8%    |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 0.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 0.8%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 6         | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.67%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 105       | 31.82%  |
| SK hynix            | 76        | 23.03%  |
| Micron Technology   | 52        | 15.76%  |
| Kingston            | 28        | 8.48%   |
| Crucial             | 24        | 7.27%   |
| Unknown             | 9         | 2.73%   |
| A-DATA Technology   | 7         | 2.12%   |
| Elpida              | 6         | 1.82%   |
| Ramaxel Technology  | 3         | 0.91%   |
| Transcend           | 2         | 0.61%   |
| Team                | 2         | 0.61%   |
| Strontium           | 2         | 0.61%   |
| Shenzhen Mic        | 2         | 0.61%   |
| Neo Forza           | 2         | 0.61%   |
| G.Skill             | 2         | 0.61%   |
| Unknown (D386)      | 1         | 0.3%    |
| Unknown (ABCD)      | 1         | 0.3%    |
| Netac               | 1         | 0.3%    |
| Nanya Technology    | 1         | 0.3%    |
| fef5                | 1         | 0.3%    |
| Corsair             | 1         | 0.3%    |
| Apacer              | 1         | 0.3%    |
| Unknown             | 1         | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 9         | 2.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 7         | 2.02%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 1.73%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 5         | 1.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 5         | 1.45%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 4         | 1.16%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                  | 4         | 1.16%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.16%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.16%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 1.16%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 4         | 1.16%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 4         | 1.16%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 4         | 1.16%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                 | 3         | 0.87%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                | 3         | 0.87%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.87%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 3         | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 0.87%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                 | 3         | 0.87%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 3         | 0.87%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s       | 3         | 0.87%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 3         | 0.87%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s      | 3         | 0.87%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 2         | 0.58%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 2         | 0.58%   |
| SK hynix RAM Module 16GB SODIMM DDR5 4800MT/s                | 2         | 0.58%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s        | 2         | 0.58%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s     | 2         | 0.58%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 2         | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 2         | 0.58%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s  | 2         | 0.58%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                  | 2         | 0.58%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                 | 2         | 0.58%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 2         | 0.58%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 2         | 0.58%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 0.58%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.58%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s     | 2         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 122       | 45.52%  |
| DDR3    | 97        | 36.19%  |
| DDR5    | 11        | 4.1%    |
| LPDDR3  | 10        | 3.73%   |
| DDR2    | 8         | 2.99%   |
| LPDDR5  | 7         | 2.61%   |
| SDRAM   | 6         | 2.24%   |
| LPDDR4  | 5         | 1.87%   |
| Unknown | 2         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 241       | 89.26%  |
| Row Of Chips | 20        | 7.41%   |
| Chip         | 4         | 1.48%   |
| Unknown      | 4         | 1.48%   |
| DIMM         | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 112       | 38.75%  |
| 4096  | 80        | 27.68%  |
| 16384 | 60        | 20.76%  |
| 2048  | 26        | 9%      |
| 32768 | 10        | 3.46%   |
| 1024  | 1         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 70        | 24.05%  |
| 3200    | 56        | 19.24%  |
| 2667    | 41        | 14.09%  |
| 2400    | 23        | 7.9%    |
| 1334    | 19        | 6.53%   |
| 2133    | 12        | 4.12%   |
| 4800    | 11        | 3.78%   |
| 1333    | 9         | 3.09%   |
| 1867    | 7         | 2.41%   |
| 1067    | 7         | 2.41%   |
| 667     | 5         | 1.72%   |
| 8400    | 4         | 1.37%   |
| 6400    | 4         | 1.37%   |
| Unknown | 4         | 1.37%   |
| 7500    | 3         | 1.03%   |
| 4199    | 3         | 1.03%   |
| 800     | 3         | 1.03%   |
| 3733    | 2         | 0.69%   |
| 2048    | 2         | 0.69%   |
| 975     | 2         | 0.69%   |
| 5600    | 1         | 0.34%   |
| 4267    | 1         | 0.34%   |
| 3266    | 1         | 0.34%   |
| 1866    | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 33.33%  |
| HP DeskJet 2300 series        | 1         | 33.33%  |
| Canon G3010 series            | 1         | 33.33%  |

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


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 125       | 28.41%  |
| IMC Networks                           | 38        | 8.64%   |
| Realtek Semiconductor                  | 33        | 7.5%    |
| Sunplus Innovation Technology          | 31        | 7.05%   |
| Microdia                               | 30        | 6.82%   |
| Quanta                                 | 29        | 6.59%   |
| Bison Electronics                      | 21        | 4.77%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 3.86%   |
| Apple                                  | 16        | 3.64%   |
| Lite-On Technology                     | 15        | 3.41%   |
| Suyin                                  | 11        | 2.5%    |
| Luxvisions Innotech Limited            | 10        | 2.27%   |
| Logitech                               | 9         | 2.05%   |
| Syntek                                 | 7         | 1.59%   |
| Acer                                   | 6         | 1.36%   |
| Sonix Technology                       | 5         | 1.14%   |
| Samsung Electronics                    | 5         | 1.14%   |
| Silicon Motion                         | 4         | 0.91%   |
| Ricoh                                  | 4         | 0.91%   |
| Primax Electronics                     | 4         | 0.91%   |
| Alcor Micro                            | 4         | 0.91%   |
| ShineTech                              | 2         | 0.45%   |
| Importek                               | 2         | 0.45%   |
| ALi                                    | 2         | 0.45%   |
| Z-Star Microelectronics                | 1         | 0.23%   |
| Yealink Network Technology             | 1         | 0.23%   |
| ValueHD                                | 1         | 0.23%   |
| Microsoft                              | 1         | 0.23%   |
| Lenovo                                 | 1         | 0.23%   |
| Intel                                  | 1         | 0.23%   |
| GEMBIRD                                | 1         | 0.23%   |
| DigiTech                               | 1         | 0.23%   |
| AVer Information                       | 1         | 0.23%   |
| Aveo Technology                        | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 23        | 5.2%    |
| IMC Networks USB2.0 HD UVC WebCam             | 19        | 4.3%    |
| Chicony HP HD Camera                          | 16        | 3.62%   |
| Chicony HD WebCam                             | 12        | 2.71%   |
| Realtek Integrated_Webcam_HD                  | 11        | 2.49%   |
| IMC Networks Integrated Camera                | 10        | 2.26%   |
| Microdia Integrated_Webcam_HD                 | 9         | 2.04%   |
| Chicony TOSHIBA Web Camera - HD               | 8         | 1.81%   |
| Chicony HP HD Webcam                          | 8         | 1.81%   |
| Sunplus Integrated_Webcam_HD                  | 7         | 1.58%   |
| Sunplus HP HD Webcam [Fixed]                  | 7         | 1.58%   |
| Microdia Integrated Webcam HD                 | 7         | 1.58%   |
| Apple Built-in iSight                         | 7         | 1.58%   |
| Realtek HP Truevision HD                      | 6         | 1.36%   |
| Quanta HP HD Camera                           | 6         | 1.36%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 6         | 1.36%   |
| Bison Integrated Camera                       | 6         | 1.36%   |
| Samsung Galaxy series, misc. (MTP mode)       | 5         | 1.13%   |
| Chicony VGA WebCam                            | 5         | 1.13%   |
| Syntek Integrated Camera                      | 4         | 0.9%    |
| Sunplus HD WebCam                             | 4         | 0.9%    |
| Sonix USB2.0 HD UVC WebCam                    | 4         | 0.9%    |
| Quanta HP TrueVision HD Camera                | 4         | 0.9%    |
| Quanta HD User Facing                         | 4         | 0.9%    |
| Lite-On Integrated Camera                     | 4         | 0.9%    |
| Chicony HP Truevision HD                      | 4         | 0.9%    |
| Bison HD Webcam                               | 4         | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR            | 4         | 0.9%    |
| Quanta Laptop_Integrated_Webcam_2HDM          | 3         | 0.68%   |
| Luxvisions Innotech Limited HP HD Camera      | 3         | 0.68%   |
| Logitech Webcam C270                          | 3         | 0.68%   |
| Lite-On TOSHIBA Web Camera - HD               | 3         | 0.68%   |
| Lite-On HP HD Camera                          | 3         | 0.68%   |
| Chicony Integrated HP HD Webcam               | 3         | 0.68%   |
| Chicony HP Wide Vision HD Camera              | 3         | 0.68%   |
| Chicony HP Webcam [2 MP Macro]                | 3         | 0.68%   |
| Bison SunplusIT Integrated Camera             | 3         | 0.68%   |
| Apple FaceTime HD Camera                      | 3         | 0.68%   |
| Syntek EasyCamera                             | 2         | 0.45%   |
| Suyin HP Webcam                               | 2         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 65        | 49.62%  |
| Synaptics                  | 37        | 28.24%  |
| Shenzhen Goodix Technology | 7         | 5.34%   |
| AuthenTec                  | 7         | 5.34%   |
| Upek                       | 6         | 4.58%   |
| Elan Microelectronics      | 6         | 4.58%   |
| LighTuning Technology      | 2         | 1.53%   |
| STMicroelectronics         | 1         | 0.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 10.69%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 8.4%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 8.4%    |
| Validity Sensors VFS491                                                    | 8         | 6.11%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 5.34%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 4.58%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 4.58%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 4.58%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 4.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.82%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 3.82%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 3.05%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 3.05%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.29%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.29%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.29%   |
| Elan WBF Fingerprint Sensor                                                | 3         | 2.29%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 2.29%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.53%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 1.53%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 1.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.53%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.53%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.53%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.53%   |
| Synaptics WBDI                                                             | 1         | 0.76%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.76%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.76%   |
| AuthenTec AES2810                                                          | 1         | 0.76%   |
| AuthenTec AES1600                                                          | 1         | 0.76%   |
| Unknown                                                                    | 1         | 0.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 68.97%  |
| Alcor Micro | 4         | 13.79%  |
| Lenovo      | 3         | 10.34%  |
| Upek        | 1         | 3.45%   |
| O2 Micro    | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 27.59%  |
| Broadcom 58200                                                               | 6         | 20.69%  |
| Broadcom 5880                                                                | 4         | 13.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 13.79%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 274       | 54.69%  |
| 1     | 180       | 35.93%  |
| 2     | 39        | 7.78%   |
| 3     | 5         | 1%      |
| 6     | 2         | 0.4%    |
| 5     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 129       | 47.08%  |
| Graphics card            | 40        | 14.6%   |
| Net/wireless             | 28        | 10.22%  |
| Chipcard                 | 28        | 10.22%  |
| Multimedia controller    | 15        | 5.47%   |
| Camera                   | 8         | 2.92%   |
| Communication controller | 5         | 1.82%   |
| Storage                  | 4         | 1.46%   |
| Net/ethernet             | 4         | 1.46%   |
| Sound                    | 3         | 1.09%   |
| Bluetooth                | 3         | 1.09%   |
| Network                  | 2         | 0.73%   |
| Card reader              | 2         | 0.73%   |
| Modem                    | 1         | 0.36%   |
| Flash memory             | 1         | 0.36%   |
| Firewire controller      | 1         | 0.36%   |

