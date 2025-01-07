Linux in Tunisia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Tunisia.

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

Total: 301

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | AOD257                      | [48ac1f7a96](https://linux-hardware.org/?probe=48ac1f7a96) | Jan 06, 2025 |
| Dell          | Vostro 3520                 | [77b90abaf0](https://linux-hardware.org/?probe=77b90abaf0) | Jan 03, 2025 |
| Acer          | Aspire E5-576G              | [9f344c14d4](https://linux-hardware.org/?probe=9f344c14d4) | Jan 03, 2025 |
| Acer          | AOD257                      | [cd57ba84bc](https://linux-hardware.org/?probe=cd57ba84bc) | Jan 03, 2025 |
| Lenovo        | G50-70 20351                | [493dd462e8](https://linux-hardware.org/?probe=493dd462e8) | Dec 29, 2024 |
| Acer          | Aspire A315-24P             | [653f633b8c](https://linux-hardware.org/?probe=653f633b8c) | Dec 23, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8a76df0398](https://linux-hardware.org/?probe=8a76df0398) | Dec 04, 2024 |
| Lenovo        | ThinkBook 15 20VE           | [c33fad56a0](https://linux-hardware.org/?probe=c33fad56a0) | Nov 30, 2024 |
| Acer          | Aspire E5-576G              | [66f3dc8d70](https://linux-hardware.org/?probe=66f3dc8d70) | Nov 27, 2024 |
| Dell          | Inspiron 3521               | [7e1f2fee77](https://linux-hardware.org/?probe=7e1f2fee77) | Nov 25, 2024 |
| Dell          | Latitude 5520               | [007adcd9ad](https://linux-hardware.org/?probe=007adcd9ad) | Nov 16, 2024 |
| HP            | EliteBook 2560p             | [84d5a17ce2](https://linux-hardware.org/?probe=84d5a17ce2) | Nov 12, 2024 |
| Dell          | Inspiron 16 5630            | [03507b0e2d](https://linux-hardware.org/?probe=03507b0e2d) | Nov 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [4aed7cd34c](https://linux-hardware.org/?probe=4aed7cd34c) | Nov 10, 2024 |
| SCHNEIDER     | SCL142ALM                   | [c03f43252b](https://linux-hardware.org/?probe=c03f43252b) | Nov 09, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [a50c814c14](https://linux-hardware.org/?probe=a50c814c14) | Nov 06, 2024 |
| Dell          | Latitude 3520               | [3b214e9caa](https://linux-hardware.org/?probe=3b214e9caa) | Nov 03, 2024 |
| Sony          | VGN-CR407E                  | [3bb8604ae1](https://linux-hardware.org/?probe=3bb8604ae1) | Oct 27, 2024 |
| SCHNEIDER     | SCL142ALM                   | [f859f241e9](https://linux-hardware.org/?probe=f859f241e9) | Oct 20, 2024 |
| SCHNEIDER     | SCL142ALM                   | [4df59a8a13](https://linux-hardware.org/?probe=4df59a8a13) | Oct 11, 2024 |
| SCHNEIDER     | SCL142ALM                   | [454208e32b](https://linux-hardware.org/?probe=454208e32b) | Oct 11, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [1183c6ec8f](https://linux-hardware.org/?probe=1183c6ec8f) | Oct 01, 2024 |
| Dell          | Vostro 1015                 | [e2c275f617](https://linux-hardware.org/?probe=e2c275f617) | Sep 23, 2024 |
| Dell          | Inspiron 16 5630            | [60730f30d3](https://linux-hardware.org/?probe=60730f30d3) | Sep 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [87a9f12a18](https://linux-hardware.org/?probe=87a9f12a18) | Sep 21, 2024 |
| ASUSTek       | X550LC                      | [470155ee76](https://linux-hardware.org/?probe=470155ee76) | Sep 15, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [4f52ba9b2f](https://linux-hardware.org/?probe=4f52ba9b2f) | Aug 31, 2024 |
| Dell          | Inspiron 16 5630            | [c584ed4ee0](https://linux-hardware.org/?probe=c584ed4ee0) | Aug 06, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [a717781b71](https://linux-hardware.org/?probe=a717781b71) | Jul 28, 2024 |
| Dell          | Vostro 3520                 | [51dc7545f8](https://linux-hardware.org/?probe=51dc7545f8) | Jul 26, 2024 |
| MSI           | Katana GF76 11UC            | [8ef6e6c1ae](https://linux-hardware.org/?probe=8ef6e6c1ae) | Jul 20, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2040d5317c](https://linux-hardware.org/?probe=2040d5317c) | Jul 19, 2024 |
| HP            | 15                          | [1f9185f9f9](https://linux-hardware.org/?probe=1f9185f9f9) | Jul 14, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [25ec8d18cc](https://linux-hardware.org/?probe=25ec8d18cc) | Jul 12, 2024 |
| HP            | OMEN by Laptop              | [2bc0d5b3b5](https://linux-hardware.org/?probe=2bc0d5b3b5) | Jun 28, 2024 |
| Apple         | MacBookPro10,1              | [da9f957584](https://linux-hardware.org/?probe=da9f957584) | Jun 27, 2024 |
| MSI           | Modern 15 A10RBS            | [cd4213c1b6](https://linux-hardware.org/?probe=cd4213c1b6) | Jun 26, 2024 |
| Lenovo        | ThinkPad T430 2349QM6       | [7e0e4be146](https://linux-hardware.org/?probe=7e0e4be146) | Jun 23, 2024 |
| ASUSTek       | X541UJ                      | [96a8342fe7](https://linux-hardware.org/?probe=96a8342fe7) | Jun 12, 2024 |
| Dell          | Latitude E6540              | [aba547e3a8](https://linux-hardware.org/?probe=aba547e3a8) | Jun 07, 2024 |
| ASUSTek       | F9E                         | [69b06a4303](https://linux-hardware.org/?probe=69b06a4303) | Jun 05, 2024 |
| HP            | Pavilion dv7                | [826b443536](https://linux-hardware.org/?probe=826b443536) | May 31, 2024 |
| MSI           | Thin GF63 12UDX             | [8baf5df767](https://linux-hardware.org/?probe=8baf5df767) | May 21, 2024 |
| HP            | EliteBook 820 G3            | [c7b984f381](https://linux-hardware.org/?probe=c7b984f381) | May 19, 2024 |
| ASUSTek       | 900                         | [9d033691b4](https://linux-hardware.org/?probe=9d033691b4) | May 19, 2024 |
| ASUSTek       | 900                         | [770a3f0d8d](https://linux-hardware.org/?probe=770a3f0d8d) | May 17, 2024 |
| ASUSTek       | F9E                         | [a1e97701b0](https://linux-hardware.org/?probe=a1e97701b0) | May 14, 2024 |
| Dell          | Inspiron 16 5630            | [7a81cef57f](https://linux-hardware.org/?probe=7a81cef57f) | May 13, 2024 |
| HP            | Laptop 14s-dq2xxx           | [1fac0018e6](https://linux-hardware.org/?probe=1fac0018e6) | May 12, 2024 |
| ASUSTek       | F9E                         | [faf50e0119](https://linux-hardware.org/?probe=faf50e0119) | May 05, 2024 |
| ASUSTek       | F9E                         | [29fd3412dc](https://linux-hardware.org/?probe=29fd3412dc) | May 02, 2024 |
| MSI           | Katana 15 B12VGK            | [c8e4cb337e](https://linux-hardware.org/?probe=c8e4cb337e) | Apr 29, 2024 |
| HP            | Notebook                    | [b45aa2251b](https://linux-hardware.org/?probe=b45aa2251b) | Apr 28, 2024 |
| HP            | Notebook                    | [9f5ae93269](https://linux-hardware.org/?probe=9f5ae93269) | Apr 28, 2024 |
| HP            | 15                          | [0e0d6ab57a](https://linux-hardware.org/?probe=0e0d6ab57a) | Apr 28, 2024 |
| HP            | 15                          | [d329164137](https://linux-hardware.org/?probe=d329164137) | Apr 28, 2024 |
| ASUSTek       | N53SN                       | [4c0db81fd7](https://linux-hardware.org/?probe=4c0db81fd7) | Apr 28, 2024 |
| Lenovo        | ThinkPad E590 20NB0002FE    | [d7eb12b86f](https://linux-hardware.org/?probe=d7eb12b86f) | Apr 12, 2024 |
| Lenovo        | ThinkPad E590 20NB0002FE    | [b6cecec324](https://linux-hardware.org/?probe=b6cecec324) | Apr 12, 2024 |
| Dell          | Inspiron 3543               | [1c04e1c19f](https://linux-hardware.org/?probe=1c04e1c19f) | Apr 06, 2024 |
| Dell          | G15 5511                    | [325c990fec](https://linux-hardware.org/?probe=325c990fec) | Mar 31, 2024 |
| Dell          | G15 5511                    | [f821631f0a](https://linux-hardware.org/?probe=f821631f0a) | Mar 31, 2024 |
| Dell          | Inspiron 3543               | [eb685d2c83](https://linux-hardware.org/?probe=eb685d2c83) | Mar 28, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [42aee3b9b6](https://linux-hardware.org/?probe=42aee3b9b6) | Mar 22, 2024 |
| Dell          | Vostro 1015                 | [cdb101a446](https://linux-hardware.org/?probe=cdb101a446) | Mar 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [22c9b2637a](https://linux-hardware.org/?probe=22c9b2637a) | Mar 20, 2024 |
| Dell          | Inspiron 3543               | [8891d1d31b](https://linux-hardware.org/?probe=8891d1d31b) | Feb 21, 2024 |
| ASUSTek       | N56VB                       | [fd2523e121](https://linux-hardware.org/?probe=fd2523e121) | Feb 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [689f8869db](https://linux-hardware.org/?probe=689f8869db) | Jan 01, 2024 |
| Acer          | Nitro AN515-55              | [14f7c6a9df](https://linux-hardware.org/?probe=14f7c6a9df) | Dec 31, 2023 |
| Lenovo        | ThinkPad T430 2349QM6       | [398d3beb97](https://linux-hardware.org/?probe=398d3beb97) | Dec 16, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [5ec5788395](https://linux-hardware.org/?probe=5ec5788395) | Dec 13, 2023 |
| Dell          | Inspiron 3558               | [936fe9e153](https://linux-hardware.org/?probe=936fe9e153) | Nov 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [d322062b88](https://linux-hardware.org/?probe=d322062b88) | Nov 22, 2023 |
| HP            | ProBook 655 G1              | [32874ad264](https://linux-hardware.org/?probe=32874ad264) | Nov 08, 2023 |
| HP            | ProBook 655 G1              | [81ff23096c](https://linux-hardware.org/?probe=81ff23096c) | Nov 08, 2023 |
| HP            | Pavilion g6                 | [e6f697f0c0](https://linux-hardware.org/?probe=e6f697f0c0) | Nov 02, 2023 |
| Lenovo        | V15-ADA 82C7                | [e8ea93da6d](https://linux-hardware.org/?probe=e8ea93da6d) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [6cbfd91e78](https://linux-hardware.org/?probe=6cbfd91e78) | Oct 30, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [1eed0a53b6](https://linux-hardware.org/?probe=1eed0a53b6) | Oct 22, 2023 |
| Valve         | Jupiter                     | [d91ad654e6](https://linux-hardware.org/?probe=d91ad654e6) | Oct 18, 2023 |
| ASUSTek       | X556UJ                      | [010c7b3e14](https://linux-hardware.org/?probe=010c7b3e14) | Oct 17, 2023 |
| ASUSTek       | X556UJ                      | [e9065ad0d2](https://linux-hardware.org/?probe=e9065ad0d2) | Oct 17, 2023 |
| Toshiba       | Satellite C855-1KF          | [1dbc7c0de3](https://linux-hardware.org/?probe=1dbc7c0de3) | Oct 15, 2023 |
| Dell          | Inspiron 5570               | [3c4e1ac4b0](https://linux-hardware.org/?probe=3c4e1ac4b0) | Oct 05, 2023 |
| ASUSTek       | UX330CAK                    | [97bb5f9ea1](https://linux-hardware.org/?probe=97bb5f9ea1) | Sep 28, 2023 |
| Dell          | G15 5530                    | [ababfa6c5e](https://linux-hardware.org/?probe=ababfa6c5e) | Aug 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [885c22f859](https://linux-hardware.org/?probe=885c22f859) | Aug 30, 2023 |
| ASUSTek       | UX330CAK                    | [35aa466ca4](https://linux-hardware.org/?probe=35aa466ca4) | Aug 26, 2023 |
| HP            | ProBook 4740s               | [1c56daf13e](https://linux-hardware.org/?probe=1c56daf13e) | Aug 09, 2023 |
| MSI           | GF63 Thin 10SCXR            | [1b07e3c9b2](https://linux-hardware.org/?probe=1b07e3c9b2) | Jul 31, 2023 |
| Dell          | Inspiron N5110              | [8d94c58c16](https://linux-hardware.org/?probe=8d94c58c16) | Jul 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | [cd9bfc68b6](https://linux-hardware.org/?probe=cd9bfc68b6) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f22c6fa671](https://linux-hardware.org/?probe=f22c6fa671) | Jul 15, 2023 |
| HP            | EliteBook 2560p             | [df243ca59d](https://linux-hardware.org/?probe=df243ca59d) | Jul 08, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [58fc9f200f](https://linux-hardware.org/?probe=58fc9f200f) | Jun 25, 2023 |
| ASUSTek       | X541UVK                     | [22a8a9d964](https://linux-hardware.org/?probe=22a8a9d964) | Jun 10, 2023 |
| Dell          | Vostro 1015                 | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [681baff23c](https://linux-hardware.org/?probe=681baff23c) | Jun 04, 2023 |
| ASUSTek       | X550JK                      | [ae3bf8f79c](https://linux-hardware.org/?probe=ae3bf8f79c) | Jun 03, 2023 |
| Dell          | Vostro 1015                 | [ebb5445720](https://linux-hardware.org/?probe=ebb5445720) | May 29, 2023 |
| Dell          | Vostro 1015                 | [5098185f54](https://linux-hardware.org/?probe=5098185f54) | May 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1bd26fc56f](https://linux-hardware.org/?probe=1bd26fc56f) | May 10, 2023 |
| HP            | Pavilion g6                 | [fc978d0a03](https://linux-hardware.org/?probe=fc978d0a03) | May 09, 2023 |
| HP            | Pavilion g6                 | [26830f860f](https://linux-hardware.org/?probe=26830f860f) | May 06, 2023 |
| HP            | Pavilion g6                 | [a78e3941f5](https://linux-hardware.org/?probe=a78e3941f5) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [eb559d913e](https://linux-hardware.org/?probe=eb559d913e) | Apr 30, 2023 |
| Toshiba       | Satellite C55-C             | [594ceb6023](https://linux-hardware.org/?probe=594ceb6023) | Apr 19, 2023 |
| Acer          | Aspire 5740                 | [eeba9d18fa](https://linux-hardware.org/?probe=eeba9d18fa) | Apr 01, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [2f1e23e614](https://linux-hardware.org/?probe=2f1e23e614) | Mar 24, 2023 |
| ASUSTek       | S551LB                      | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| ASUSTek       | GL753VE                     | [13c8ab8634](https://linux-hardware.org/?probe=13c8ab8634) | Mar 18, 2023 |
| Acer          | Aspire E5-571G              | [be4f604d4f](https://linux-hardware.org/?probe=be4f604d4f) | Mar 14, 2023 |
| Acer          | Aspire E5-571G              | [4094f2a910](https://linux-hardware.org/?probe=4094f2a910) | Mar 14, 2023 |
| Dell          | Vostro 3400                 | [33b5924e71](https://linux-hardware.org/?probe=33b5924e71) | Mar 07, 2023 |
| Dell          | Vostro 3400                 | [c5d5b5f2c9](https://linux-hardware.org/?probe=c5d5b5f2c9) | Mar 04, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [817b72f78f](https://linux-hardware.org/?probe=817b72f78f) | Mar 02, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [50a16e7924](https://linux-hardware.org/?probe=50a16e7924) | Feb 25, 2023 |
| ASUSTek       | X553MA                      | [09df6de7db](https://linux-hardware.org/?probe=09df6de7db) | Feb 23, 2023 |
| ASUSTek       | UX330CAK                    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ddd8c34644](https://linux-hardware.org/?probe=ddd8c34644) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [39b9facc37](https://linux-hardware.org/?probe=39b9facc37) | Feb 16, 2023 |
| Dell          | Inspiron 3542               | [0eb0b40b2b](https://linux-hardware.org/?probe=0eb0b40b2b) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [993adedd8e](https://linux-hardware.org/?probe=993adedd8e) | Jan 18, 2023 |
| Acer          | Aspire V3-771               | [a48fadfcbd](https://linux-hardware.org/?probe=a48fadfcbd) | Jan 06, 2023 |
| Dell          | Vostro 3500                 | [00c90e5b24](https://linux-hardware.org/?probe=00c90e5b24) | Dec 08, 2022 |
| HP            | Pavilion g6                 | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [50c70cb811](https://linux-hardware.org/?probe=50c70cb811) | Nov 20, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [9c732b8892](https://linux-hardware.org/?probe=9c732b8892) | Nov 14, 2022 |
| ASUSTek       | UX330CAK                    | [bd7d377985](https://linux-hardware.org/?probe=bd7d377985) | Nov 14, 2022 |
| Lenovo        | V15-IGL 82C3                | [bc0831aa5e](https://linux-hardware.org/?probe=bc0831aa5e) | Nov 13, 2022 |
| Lenovo        | V15-IGL 82C3                | [c4811dfc5e](https://linux-hardware.org/?probe=c4811dfc5e) | Nov 12, 2022 |
| HP            | 14                          | [7611c14813](https://linux-hardware.org/?probe=7611c14813) | Oct 31, 2022 |
| Lenovo        | ThinkPad E15 20RD001QFE     | [cc9f8c3aad](https://linux-hardware.org/?probe=cc9f8c3aad) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9594fcc1e0](https://linux-hardware.org/?probe=9594fcc1e0) | Oct 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [71734a9abe](https://linux-hardware.org/?probe=71734a9abe) | Oct 19, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | [f80eb01da1](https://linux-hardware.org/?probe=f80eb01da1) | Oct 13, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | [f44ca565c1](https://linux-hardware.org/?probe=f44ca565c1) | Oct 11, 2022 |
| Toshiba       | Satellite C650D             | [0fce536c7d](https://linux-hardware.org/?probe=0fce536c7d) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [4fdb057f33](https://linux-hardware.org/?probe=4fdb057f33) | Sep 02, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [659506d72f](https://linux-hardware.org/?probe=659506d72f) | Sep 02, 2022 |
| Dell          | Inspiron 3543               | [a557da948a](https://linux-hardware.org/?probe=a557da948a) | Aug 31, 2022 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [aa5f4a0207](https://linux-hardware.org/?probe=aa5f4a0207) | Aug 29, 2022 |
| MSI           | GF63 Thin 10SCSR            | [f3facd36da](https://linux-hardware.org/?probe=f3facd36da) | Aug 24, 2022 |
| HP            | Laptop 15-dw3xxx            | [f0d245ec0f](https://linux-hardware.org/?probe=f0d245ec0f) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f4fedfb271](https://linux-hardware.org/?probe=f4fedfb271) | Aug 14, 2022 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [7dab66307c](https://linux-hardware.org/?probe=7dab66307c) | Aug 09, 2022 |
| Dell          | Inspiron 5570               | [c57b484523](https://linux-hardware.org/?probe=c57b484523) | Aug 07, 2022 |
| Acer          | Aspire E5-571G              | [672cb969fb](https://linux-hardware.org/?probe=672cb969fb) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [edfabf845b](https://linux-hardware.org/?probe=edfabf845b) | Jul 22, 2022 |
| Lenovo        | ThinkPad E14 20RA000KFE     | [7193e153ff](https://linux-hardware.org/?probe=7193e153ff) | Jul 20, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Packard Be... | EasyNote ML65               | [c8c6125dc3](https://linux-hardware.org/?probe=c8c6125dc3) | Jul 06, 2022 |
| Packard Be... | EasyNote ML65               | [09d1580fd5](https://linux-hardware.org/?probe=09d1580fd5) | Jul 06, 2022 |
| Dell          | Inspiron N5040              | [2459fb8d6e](https://linux-hardware.org/?probe=2459fb8d6e) | Jul 03, 2022 |
| Dell          | Inspiron N5040              | [81e318d1d5](https://linux-hardware.org/?probe=81e318d1d5) | Jul 03, 2022 |
| HP            | ProBook 455 G3              | [bac60198a3](https://linux-hardware.org/?probe=bac60198a3) | Jun 10, 2022 |
| Lenovo        | V310-15ISK 80SY             | [2218dd9966](https://linux-hardware.org/?probe=2218dd9966) | Jun 07, 2022 |
| ASUSTek       | X556UV                      | [39b927dfdc](https://linux-hardware.org/?probe=39b927dfdc) | May 11, 2022 |
| Dell          | Latitude 3540               | [a97573f3cf](https://linux-hardware.org/?probe=a97573f3cf) | Apr 29, 2022 |
| Dell          | Latitude 3540               | [a6b8509194](https://linux-hardware.org/?probe=a6b8509194) | Apr 29, 2022 |
| Toshiba       | Satellite Pro L850-B339     | [d884eeae8f](https://linux-hardware.org/?probe=d884eeae8f) | Apr 20, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [03b34db583](https://linux-hardware.org/?probe=03b34db583) | Apr 05, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [e7a152d30a](https://linux-hardware.org/?probe=e7a152d30a) | Apr 04, 2022 |
| ASUSTek       | X550LC                      | [30ed5cb046](https://linux-hardware.org/?probe=30ed5cb046) | Apr 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7c0d1ce382](https://linux-hardware.org/?probe=7c0d1ce382) | Mar 29, 2022 |
| MSI           | Katana GF66 12UC            | [bc07a3de3d](https://linux-hardware.org/?probe=bc07a3de3d) | Mar 15, 2022 |
| MSI           | Katana GF66 12UC            | [ddbc85ab3a](https://linux-hardware.org/?probe=ddbc85ab3a) | Mar 15, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [4b2b4e7f5a](https://linux-hardware.org/?probe=4b2b4e7f5a) | Mar 10, 2022 |
| ASUSTek       | X550LC                      | [267fa2ca76](https://linux-hardware.org/?probe=267fa2ca76) | Mar 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [7803f9b898](https://linux-hardware.org/?probe=7803f9b898) | Feb 24, 2022 |
| ASUSTek       | X553MA                      | [020df21e37](https://linux-hardware.org/?probe=020df21e37) | Feb 23, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [49a3015875](https://linux-hardware.org/?probe=49a3015875) | Feb 10, 2022 |
| HP            | Pavilion dv7                | [3bd981aa35](https://linux-hardware.org/?probe=3bd981aa35) | Feb 09, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEP... | [f814537586](https://linux-hardware.org/?probe=f814537586) | Feb 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [09caab8240](https://linux-hardware.org/?probe=09caab8240) | Feb 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [75acdd40a6](https://linux-hardware.org/?probe=75acdd40a6) | Feb 07, 2022 |
| ASUSTek       | X553MA                      | [06f3844911](https://linux-hardware.org/?probe=06f3844911) | Jan 30, 2022 |
| ASUSTek       | X555LD                      | [0665a1599c](https://linux-hardware.org/?probe=0665a1599c) | Jan 26, 2022 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | [22dd608151](https://linux-hardware.org/?probe=22dd608151) | Jan 07, 2022 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | [391458138f](https://linux-hardware.org/?probe=391458138f) | Jan 07, 2022 |
| HP            | EliteBook 8740w             | [6f583dfeaf](https://linux-hardware.org/?probe=6f583dfeaf) | Dec 27, 2021 |
| Acer          | Aspire 5742                 | [45a5de08c7](https://linux-hardware.org/?probe=45a5de08c7) | Dec 25, 2021 |
| HP            | Notebook                    | [032be84586](https://linux-hardware.org/?probe=032be84586) | Dec 09, 2021 |
| Toshiba       | Satellite C50-A489          | [4d29ea3b9c](https://linux-hardware.org/?probe=4d29ea3b9c) | Dec 04, 2021 |
| Lenovo        | ThinkPad X240 20AMA0WRFR    | [13fe3346fd](https://linux-hardware.org/?probe=13fe3346fd) | Dec 02, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [d0a08a7a23](https://linux-hardware.org/?probe=d0a08a7a23) | Nov 22, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [507c380abb](https://linux-hardware.org/?probe=507c380abb) | Nov 22, 2021 |
| Acer          | Aspire A315-51              | [d49eff3d64](https://linux-hardware.org/?probe=d49eff3d64) | Nov 21, 2021 |
| Lenovo        | ThinkPad E15 20RD001SFE     | [358e3547b9](https://linux-hardware.org/?probe=358e3547b9) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD001SFE     | [694f05492e](https://linux-hardware.org/?probe=694f05492e) | Nov 17, 2021 |
| HP            | Compaq 6735s                | [6571a6fe6d](https://linux-hardware.org/?probe=6571a6fe6d) | Nov 15, 2021 |
| HP            | ProBook 440 G7              | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | [4bc0687791](https://linux-hardware.org/?probe=4bc0687791) | Nov 08, 2021 |
| HP            | Pavilion dv6                | [dcd2956978](https://linux-hardware.org/?probe=dcd2956978) | Nov 05, 2021 |
| HP            | Pavilion dv6                | [a509e62c95](https://linux-hardware.org/?probe=a509e62c95) | Nov 05, 2021 |
| Lenovo        | G50-70 20351                | [60e3fe1197](https://linux-hardware.org/?probe=60e3fe1197) | Oct 26, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | [8f6efb8dbe](https://linux-hardware.org/?probe=8f6efb8dbe) | Oct 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9b0872b3d4](https://linux-hardware.org/?probe=9b0872b3d4) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [9b74440deb](https://linux-hardware.org/?probe=9b74440deb) | Oct 07, 2021 |
| Acer          | Swift SF514-53T             | [e97a52d3d9](https://linux-hardware.org/?probe=e97a52d3d9) | Sep 28, 2021 |
| HP            | 250 G4                      | [b5177b1c13](https://linux-hardware.org/?probe=b5177b1c13) | Sep 08, 2021 |
| HP            | 250 G4                      | [32899cab30](https://linux-hardware.org/?probe=32899cab30) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d4cdb976c2](https://linux-hardware.org/?probe=d4cdb976c2) | Aug 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [633e5a9649](https://linux-hardware.org/?probe=633e5a9649) | Aug 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6339cd2e5b](https://linux-hardware.org/?probe=6339cd2e5b) | Aug 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [58fb87de66](https://linux-hardware.org/?probe=58fb87de66) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8d891b7431](https://linux-hardware.org/?probe=8d891b7431) | Aug 02, 2021 |
| HP            | 250 G7 Notebook PC          | [726ed18d47](https://linux-hardware.org/?probe=726ed18d47) | Jul 25, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | [a347415235](https://linux-hardware.org/?probe=a347415235) | Jul 19, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [236639a923](https://linux-hardware.org/?probe=236639a923) | Jul 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [98862925dc](https://linux-hardware.org/?probe=98862925dc) | Jul 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [b6ce3d213a](https://linux-hardware.org/?probe=b6ce3d213a) | Jul 06, 2021 |
| MSI           | GF65 Thin 10UE              | [af8d7a6b6f](https://linux-hardware.org/?probe=af8d7a6b6f) | Jun 22, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [9a767f85c2](https://linux-hardware.org/?probe=9a767f85c2) | May 17, 2021 |
| Dell          | Inspiron 5570               | [fe125a0b5f](https://linux-hardware.org/?probe=fe125a0b5f) | May 10, 2021 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [89cfbb6a0e](https://linux-hardware.org/?probe=89cfbb6a0e) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [884b3d6f69](https://linux-hardware.org/?probe=884b3d6f69) | Apr 21, 2021 |
| Lenovo        | V15-IIL 82C5                | [50e1fa29fb](https://linux-hardware.org/?probe=50e1fa29fb) | Apr 16, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [be7a218721](https://linux-hardware.org/?probe=be7a218721) | Apr 12, 2021 |
| Dell          | Latitude E6420              | [901b94b26d](https://linux-hardware.org/?probe=901b94b26d) | Mar 10, 2021 |
| Dell          | Latitude E6420              | [c0d9f82152](https://linux-hardware.org/?probe=c0d9f82152) | Mar 10, 2021 |
| Dell          | Latitude E5440              | [89089cf0ad](https://linux-hardware.org/?probe=89089cf0ad) | Mar 05, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [347d45179a](https://linux-hardware.org/?probe=347d45179a) | Jan 30, 2021 |
| Acer          | Aspire V5-561G              | [4829da6130](https://linux-hardware.org/?probe=4829da6130) | Jan 30, 2021 |
| Dell          | Latitude 7410               | [19e75431d4](https://linux-hardware.org/?probe=19e75431d4) | Jan 30, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [07f0354547](https://linux-hardware.org/?probe=07f0354547) | Jan 29, 2021 |
| Dell          | Inspiron N5110              | [5b18be0dd0](https://linux-hardware.org/?probe=5b18be0dd0) | Jan 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [cb1f74adbd](https://linux-hardware.org/?probe=cb1f74adbd) | Jan 17, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [f4c57eb290](https://linux-hardware.org/?probe=f4c57eb290) | Jan 17, 2021 |
| HP            | Laptop 15-bs0xx             | [95610ff17c](https://linux-hardware.org/?probe=95610ff17c) | Jan 14, 2021 |
| Dell          | Inspiron 3520               | [c1e7a232e0](https://linux-hardware.org/?probe=c1e7a232e0) | Dec 29, 2020 |
| eMachines     | E725                        | [aa660241b3](https://linux-hardware.org/?probe=aa660241b3) | Dec 22, 2020 |
| Dell          | Latitude 7490               | [d42995d26a](https://linux-hardware.org/?probe=d42995d26a) | Dec 21, 2020 |
| MSI           | GF63 Thin 10SCXR            | [f52e267cc9](https://linux-hardware.org/?probe=f52e267cc9) | Dec 19, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [e4ab77e8b0](https://linux-hardware.org/?probe=e4ab77e8b0) | Dec 11, 2020 |
| Lenovo        | ThinkPad E15 20RD001QFE     | [d02175d76c](https://linux-hardware.org/?probe=d02175d76c) | Dec 10, 2020 |
| ASUSTek       | UX310UQK                    | [bb566782bc](https://linux-hardware.org/?probe=bb566782bc) | Dec 04, 2020 |
| Toshiba       | Satellite A300              | [963065205e](https://linux-hardware.org/?probe=963065205e) | Nov 26, 2020 |
| Toshiba       | Satellite A300              | [c1aeee5a95](https://linux-hardware.org/?probe=c1aeee5a95) | Nov 26, 2020 |
| ASUSTek       | X550VX                      | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [563be9ddd8](https://linux-hardware.org/?probe=563be9ddd8) | Nov 21, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [59de1f8260](https://linux-hardware.org/?probe=59de1f8260) | Nov 20, 2020 |
| Dell          | Inspiron N5110              | [64cce3acaa](https://linux-hardware.org/?probe=64cce3acaa) | Nov 04, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [97dee881c4](https://linux-hardware.org/?probe=97dee881c4) | Nov 01, 2020 |
| Dell          | Inspiron 3593               | [a236e15c5d](https://linux-hardware.org/?probe=a236e15c5d) | Oct 25, 2020 |
| Acer          | Swift SF314-52              | [f81c8f31d1](https://linux-hardware.org/?probe=f81c8f31d1) | Oct 10, 2020 |
| Acer          | Swift SF314-52              | [bb4464e5f1](https://linux-hardware.org/?probe=bb4464e5f1) | Oct 10, 2020 |
| Dell          | Latitude 7480               | [7bf6a7c3a4](https://linux-hardware.org/?probe=7bf6a7c3a4) | Sep 16, 2020 |
| ASUSTek       | UX360CA                     | [9d6a79d7ac](https://linux-hardware.org/?probe=9d6a79d7ac) | Jun 11, 2020 |
| ASUSTek       | UX360CA                     | [24742e9ec9](https://linux-hardware.org/?probe=24742e9ec9) | Jun 11, 2020 |
| Toshiba       | Satellite L500              | [1cb682ea0f](https://linux-hardware.org/?probe=1cb682ea0f) | Jun 06, 2020 |
| Toshiba       | Satellite L550              | [31501ab61b](https://linux-hardware.org/?probe=31501ab61b) | May 11, 2020 |
| Toshiba       | Satellite L550              | [b8e2396d82](https://linux-hardware.org/?probe=b8e2396d82) | May 11, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4ff939d0e2](https://linux-hardware.org/?probe=4ff939d0e2) | Apr 28, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [31b3c13f93](https://linux-hardware.org/?probe=31b3c13f93) | Apr 28, 2020 |
| Toshiba       | Satellite L550              | [73f10216d6](https://linux-hardware.org/?probe=73f10216d6) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | [b5721fa9d5](https://linux-hardware.org/?probe=b5721fa9d5) | Apr 22, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [b391bbea48](https://linux-hardware.org/?probe=b391bbea48) | Apr 12, 2020 |
| Lenovo        | G580 20157                  | [30a8d59bdc](https://linux-hardware.org/?probe=30a8d59bdc) | Apr 09, 2020 |
| Lenovo        | G580 20157                  | [fc6eaad779](https://linux-hardware.org/?probe=fc6eaad779) | Apr 09, 2020 |
| ASUSTek       | X556UV                      | [cb5da8627a](https://linux-hardware.org/?probe=cb5da8627a) | Apr 07, 2020 |
| ASUSTek       | X550JX                      | [71dbec47eb](https://linux-hardware.org/?probe=71dbec47eb) | Mar 27, 2020 |
| ASUSTek       | X550JX                      | [cc439d9e0f](https://linux-hardware.org/?probe=cc439d9e0f) | Mar 27, 2020 |
| Dell          | Inspiron 3521               | [cb7137a57a](https://linux-hardware.org/?probe=cb7137a57a) | Mar 16, 2020 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [64628c8c11](https://linux-hardware.org/?probe=64628c8c11) | Mar 12, 2020 |
| ASUSTek       | X550JX                      | [a1fa3183ed](https://linux-hardware.org/?probe=a1fa3183ed) | Feb 15, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [97b5418b6d](https://linux-hardware.org/?probe=97b5418b6d) | Feb 03, 2020 |
| Lenovo        | ThinkPad T440s 20AQ005NU... | [55d9286a1b](https://linux-hardware.org/?probe=55d9286a1b) | Jan 27, 2020 |
| Acer          | Aspire E1-570               | [9d92944e6c](https://linux-hardware.org/?probe=9d92944e6c) | Dec 21, 2019 |
| Acer          | Aspire E1-570               | [64702aadcd](https://linux-hardware.org/?probe=64702aadcd) | Dec 21, 2019 |
| Lenovo        | Unknown                     | [10ab399874](https://linux-hardware.org/?probe=10ab399874) | Dec 14, 2019 |
| Sony          | VPCEH36EF                   | [5b1adbe8f0](https://linux-hardware.org/?probe=5b1adbe8f0) | Dec 10, 2019 |
| Sony          | VPCEH36EF                   | [6518790628](https://linux-hardware.org/?probe=6518790628) | Nov 27, 2019 |
| Dell          | Latitude E6420              | [3f252a50fb](https://linux-hardware.org/?probe=3f252a50fb) | Nov 12, 2019 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | [1b5ae66e6f](https://linux-hardware.org/?probe=1b5ae66e6f) | Nov 10, 2019 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | [a9cc2a8ea0](https://linux-hardware.org/?probe=a9cc2a8ea0) | Nov 01, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [b57e5735a5](https://linux-hardware.org/?probe=b57e5735a5) | Sep 13, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [708bc2c339](https://linux-hardware.org/?probe=708bc2c339) | Sep 13, 2019 |
| HP            | 630                         | [8cb4c328bb](https://linux-hardware.org/?probe=8cb4c328bb) | Sep 10, 2019 |
| Acer          | Aspire V5-572G              | [7d046c01d0](https://linux-hardware.org/?probe=7d046c01d0) | Sep 07, 2019 |
| HP            | Pavilion g6                 | [6eebb27f65](https://linux-hardware.org/?probe=6eebb27f65) | Aug 28, 2019 |
| HP            | Laptop                      | [de71114421](https://linux-hardware.org/?probe=de71114421) | Aug 21, 2019 |
| Acer          | Aspire V5-572G              | [90d2c432d6](https://linux-hardware.org/?probe=90d2c432d6) | Aug 17, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [26b5185afb](https://linux-hardware.org/?probe=26b5185afb) | Aug 14, 2019 |
| Acer          | TravelMate P259-M           | [3693d52bff](https://linux-hardware.org/?probe=3693d52bff) | Nov 09, 2018 |
| Acer          | TravelMate P259-M           | [a951fd5ef9](https://linux-hardware.org/?probe=a951fd5ef9) | Nov 09, 2018 |
| HP            | Laptop 17-ak0xx             | [83d0682234](https://linux-hardware.org/?probe=83d0682234) | Sep 20, 2018 |
| HP            | Laptop 17-ak0xx             | [e2076e8303](https://linux-hardware.org/?probe=e2076e8303) | Sep 19, 2018 |
| HP            | Laptop 17-ak0xx             | [24599e9990](https://linux-hardware.org/?probe=24599e9990) | Sep 19, 2018 |
| HP            | Pavilion g6                 | [c93294c4ab](https://linux-hardware.org/?probe=c93294c4ab) | Sep 18, 2018 |
| HP            | Pavilion g6                 | [efc4afba58](https://linux-hardware.org/?probe=efc4afba58) | Aug 10, 2018 |
| HP            | Pavilion g6                 | [494e0c0416](https://linux-hardware.org/?probe=494e0c0416) | Aug 10, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 40        | 17.86%  |
| Ubuntu 22.04        | 20        | 8.93%   |
| Ubuntu 18.04        | 12        | 5.36%   |
| Debian 12           | 7         | 3.13%   |
| Ubuntu 21.10        | 5         | 2.23%   |
| Ubuntu 24.04        | 4         | 1.79%   |
| Pop!_OS 22.04       | 4         | 1.79%   |
| Linux Mint 21.2     | 4         | 1.79%   |
| KDE neon 22.04      | 4         | 1.79%   |
| Fedora 38           | 4         | 1.79%   |
| ArcoLinux Rolling   | 4         | 1.79%   |
| Arch Rolling        | 4         | 1.79%   |
| Zorin 16            | 3         | 1.34%   |
| Zorin 15            | 3         | 1.34%   |
| OpenMandriva 4.2    | 3         | 1.34%   |
| OpenMandriva 23.08  | 3         | 1.34%   |
| OpenMandriva 23.03  | 3         | 1.34%   |
| Fedora 40           | 3         | 1.34%   |
| EndeavourOS Rolling | 3         | 1.34%   |
| Debian 10           | 3         | 1.34%   |
| Ubuntu 21.04        | 2         | 0.89%   |
| Ubuntu 20.10        | 2         | 0.89%   |
| Ubuntu 16.04        | 2         | 0.89%   |
| Pop!_OS 21.04       | 2         | 0.89%   |
| OpenMandriva 23.07  | 2         | 0.89%   |
| NixOS 24.05         | 2         | 0.89%   |
| Manjaro 21.1.0      | 2         | 0.89%   |
| LMDE 4              | 2         | 0.89%   |
| Linux Mint 21.3     | 2         | 0.89%   |
| Linux Mint 21.1     | 2         | 0.89%   |
| Linux Mint 21       | 2         | 0.89%   |
| Linux Mint 20.3     | 2         | 0.89%   |
| Linux Mint 20.2     | 2         | 0.89%   |
| KDE neon 20.04      | 2         | 0.89%   |
| Kali 2024.1         | 2         | 0.89%   |
| Fedora 41           | 2         | 0.89%   |
| Fedora 35           | 2         | 0.89%   |
| Fedora 33           | 2         | 0.89%   |
| Zorin 17            | 1         | 0.45%   |
| Xubuntu 22.04       | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 84        | 38.89%  |
| Linux Mint   | 17        | 7.87%   |
| OpenMandriva | 14        | 6.48%   |
| Fedora       | 14        | 6.48%   |
| Debian       | 12        | 5.56%   |
| Zorin        | 7         | 3.24%   |
| Pop!_OS      | 7         | 3.24%   |
| Manjaro      | 6         | 2.78%   |
| KDE neon     | 5         | 2.31%   |
| Endless      | 5         | 2.31%   |
| Arch         | 5         | 2.31%   |
| ROSA         | 4         | 1.85%   |
| ArcoLinux    | 4         | 1.85%   |
| LMDE         | 3         | 1.39%   |
| Kali         | 3         | 1.39%   |
| EndeavourOS  | 3         | 1.39%   |
| Xubuntu      | 2         | 0.93%   |
| NixOS        | 2         | 0.93%   |
| Lubuntu      | 2         | 0.93%   |
| Elementary   | 2         | 0.93%   |
| Xero         | 1         | 0.46%   |
| Ubuntu Unity | 1         | 0.46%   |
| TUXEDO OS    | 1         | 0.46%   |
| SteamOS      | 1         | 0.46%   |
| Sodalite     | 1         | 0.46%   |
| Parrot       | 1         | 0.46%   |
| Nobara       | 1         | 0.46%   |
| MX           | 1         | 0.46%   |
| Kubuntu      | 1         | 0.46%   |
| Gentoo       | 1         | 0.46%   |
| Garuda Linux | 1         | 0.46%   |
| Deepin       | 1         | 0.46%   |
| CachyOS      | 1         | 0.46%   |
| BlackPanther | 1         | 0.46%   |
| Archcraft    | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.13.0-28-generic        | 4         | 1.68%   |
| 6.4.11-desktop-1omv2390  | 3         | 1.26%   |
| 6.2.6-desktop-1omv2390   | 3         | 1.26%   |
| 5.3.0-46-generic         | 3         | 1.26%   |
| 5.15.0-58-generic        | 3         | 1.26%   |
| 5.15.0-52-generic        | 3         | 1.26%   |
| 5.15.0-46-generic        | 3         | 1.26%   |
| 5.15.0-43-generic        | 3         | 1.26%   |
| 5.11.0-38-generic        | 3         | 1.26%   |
| 5.10.14-desktop-1omv4002 | 3         | 1.26%   |
| 6.8.0-51-generic         | 2         | 0.84%   |
| 6.8.0-49-generic         | 2         | 0.84%   |
| 6.8.0-48-generic         | 2         | 0.84%   |
| 6.8.0-40-generic         | 2         | 0.84%   |
| 6.3.5-desktop-3omv2390   | 2         | 0.84%   |
| 6.1.0-28-amd64           | 2         | 0.84%   |
| 5.8.0-38-generic         | 2         | 0.84%   |
| 5.8.0-14-generic         | 2         | 0.84%   |
| 5.4.0-72-generic         | 2         | 0.84%   |
| 5.4.0-58-generic         | 2         | 0.84%   |
| 5.4.0-52-generic         | 2         | 0.84%   |
| 5.4.0-42-generic         | 2         | 0.84%   |
| 5.3.0-40-generic         | 2         | 0.84%   |
| 5.3.0-28-generic         | 2         | 0.84%   |
| 5.15.0-56-generic        | 2         | 0.84%   |
| 5.15.0-41-generic        | 2         | 0.84%   |
| 5.15.0-107-generic       | 2         | 0.84%   |
| 5.13.0-44-generic        | 2         | 0.84%   |
| 5.13.0-40-generic        | 2         | 0.84%   |
| 5.11.0-7620-generic      | 2         | 0.84%   |
| 5.11.0-40-generic        | 2         | 0.84%   |
| 5.11.0-27-generic        | 2         | 0.84%   |
| 5.0.0-25-generic         | 2         | 0.84%   |
| 4.19.0-6-amd64           | 2         | 0.84%   |
| 6.9.9-arch1-1            | 1         | 0.42%   |
| 6.9.7-200.fc40.x86_64    | 1         | 0.42%   |
| 6.9.6-3-cachyos          | 1         | 0.42%   |
| 6.9.5-200.fc40.x86_64    | 1         | 0.42%   |
| 6.9.3-1-liquorix-amd64   | 1         | 0.42%   |
| 6.9.1-arch1-1            | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 29        | 12.72%  |
| 5.4.0   | 21        | 9.21%   |
| 5.13.0  | 15        | 6.58%   |
| 5.11.0  | 12        | 5.26%   |
| 6.8.0   | 10        | 4.39%   |
| 5.8.0   | 10        | 4.39%   |
| 5.3.0   | 8         | 3.51%   |
| 5.19.0  | 8         | 3.51%   |
| 4.15.0  | 8         | 3.51%   |
| 6.5.0   | 7         | 3.07%   |
| 6.1.0   | 6         | 2.63%   |
| 5.0.0   | 6         | 2.63%   |
| 4.19.0  | 4         | 1.75%   |
| 6.4.11  | 3         | 1.32%   |
| 6.3.5   | 3         | 1.32%   |
| 6.2.6   | 3         | 1.32%   |
| 6.2.0   | 3         | 1.32%   |
| 5.10.14 | 3         | 1.32%   |
| 5.10.0  | 3         | 1.32%   |
| 6.5.7   | 2         | 0.88%   |
| 6.3.6   | 2         | 0.88%   |
| 5.17.5  | 2         | 0.88%   |
| 4.18.0  | 2         | 0.88%   |
| 6.9.9   | 1         | 0.44%   |
| 6.9.7   | 1         | 0.44%   |
| 6.9.6   | 1         | 0.44%   |
| 6.9.5   | 1         | 0.44%   |
| 6.9.3   | 1         | 0.44%   |
| 6.9.1   | 1         | 0.44%   |
| 6.8.9   | 1         | 0.44%   |
| 6.8.6   | 1         | 0.44%   |
| 6.8.4   | 1         | 0.44%   |
| 6.8.2   | 1         | 0.44%   |
| 6.8.1   | 1         | 0.44%   |
| 6.6.9   | 1         | 0.44%   |
| 6.6.60  | 1         | 0.44%   |
| 6.6.42  | 1         | 0.44%   |
| 6.6.40  | 1         | 0.44%   |
| 6.6.22  | 1         | 0.44%   |
| 6.6.2   | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 13.9%   |
| 5.4     | 23        | 10.31%  |
| 5.13    | 16        | 7.17%   |
| 6.8     | 14        | 6.28%   |
| 5.11    | 14        | 6.28%   |
| 6.5     | 11        | 4.93%   |
| 5.8     | 11        | 4.93%   |
| 6.2     | 9         | 4.04%   |
| 5.3     | 9         | 4.04%   |
| 5.19    | 9         | 4.04%   |
| 5.10    | 9         | 4.04%   |
| 6.1     | 8         | 3.59%   |
| 4.15    | 8         | 3.59%   |
| 6.6     | 7         | 3.14%   |
| 6.9     | 6         | 2.69%   |
| 5.0     | 6         | 2.69%   |
| 6.3     | 5         | 2.24%   |
| 6.4     | 4         | 1.79%   |
| 4.19    | 4         | 1.79%   |
| 6.11    | 3         | 1.35%   |
| 5.16    | 3         | 1.35%   |
| 5.17    | 2         | 0.9%    |
| 4.9     | 2         | 0.9%    |
| 4.18    | 2         | 0.9%    |
| 5.9     | 1         | 0.45%   |
| 5.6     | 1         | 0.45%   |
| 5.5     | 1         | 0.45%   |
| 5.18    | 1         | 0.45%   |
| 5.14    | 1         | 0.45%   |
| 5.12    | 1         | 0.45%   |
| 3.13    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 205       | 98.56%  |
| i686   | 3         | 1.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 116       | 53.7%   |
| KDE5             | 35        | 16.2%   |
| X-Cinnamon       | 18        | 8.33%   |
| Unknown          | 13        | 6.02%   |
| XFCE             | 9         | 4.17%   |
| KDE6             | 6         | 2.78%   |
| Pantheon         | 3         | 1.39%   |
| KDE4             | 3         | 1.39%   |
| MATE             | 2         | 0.93%   |
| Unity            | 1         | 0.46%   |
| Trinity          | 1         | 0.46%   |
| qtile            | 1         | 0.46%   |
| LXQt             | 1         | 0.46%   |
| LXDE             | 1         | 0.46%   |
| lightdm-xsession | 1         | 0.46%   |
| GNOME Flashback  | 1         | 0.46%   |
| GNOME Classic    | 1         | 0.46%   |
| Endless:GNOME    | 1         | 0.46%   |
| DWM              | 1         | 0.46%   |
| Deepin           | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 155       | 72.09%  |
| Wayland | 53        | 24.65%  |
| Unknown | 5         | 2.33%   |
| Tty     | 2         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 35.51%  |
| GDM     | 46        | 21.5%   |
| SDDM    | 36        | 16.82%  |
| GDM3    | 32        | 14.95%  |
| LightDM | 21        | 9.81%   |
| KDM     | 3         | 1.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 107       | 50.71%  |
| fr_FR   | 62        | 29.38%  |
| Unknown | 15        | 7.11%   |
| en_GB   | 11        | 5.21%   |
| C       | 6         | 2.84%   |
| pt_BR   | 2         | 0.95%   |
| it_IT   | 2         | 0.95%   |
| de_DE   | 2         | 0.95%   |
| en_IN   | 1         | 0.47%   |
| en_IE   | 1         | 0.47%   |
| en_CA   | 1         | 0.47%   |
| ar_TN   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 115       | 53.99%  |
| BIOS | 98        | 46.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 167       | 79.52%  |
| Btrfs   | 19        | 9.05%   |
| Tmpfs   | 9         | 4.29%   |
| Overlay | 9         | 4.29%   |
| Unknown | 5         | 2.38%   |
| Xfs     | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 92        | 43.81%  |
| Unknown | 84        | 40%     |
| MBR     | 34        | 16.19%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 187       | 89.05%  |
| Yes       | 23        | 10.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 137       | 65.24%  |
| Yes       | 73        | 34.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 53        | 25.6%   |
| ASUSTek Computer    | 41        | 19.81%  |
| Hewlett-Packard     | 37        | 17.87%  |
| Dell                | 33        | 15.94%  |
| Acer                | 16        | 7.73%   |
| MSI                 | 9         | 4.35%   |
| Toshiba             | 8         | 3.86%   |
| Samsung Electronics | 3         | 1.45%   |
| Sony                | 2         | 0.97%   |
| Valve               | 1         | 0.48%   |
| SCHNEIDER           | 1         | 0.48%   |
| Packard Bell        | 1         | 0.48%   |
| eMachines           | 1         | 0.48%   |
| Apple               | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Pavilion g6                          | 6         | 2.9%    |
| Lenovo IdeaPad L340-15IRH Gaming 81LK   | 4         | 1.93%   |
| Lenovo IdeaPad 3 15ADA05 81W1           | 3         | 1.45%   |
| Dell Inspiron 5570                      | 3         | 1.45%   |
| Dell Inspiron 3543                      | 3         | 1.45%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 2         | 0.97%   |
| MSI GF63 Thin 10SCXR                    | 2         | 0.97%   |
| Lenovo IdeaPad 700-15ISK 80RU           | 2         | 0.97%   |
| Lenovo IdeaPad 5 15ITL05 82FG           | 2         | 0.97%   |
| Lenovo IdeaPad 3 15IGL05 81WQ           | 2         | 0.97%   |
| Lenovo IdeaPad 130-15IKB 81H7           | 2         | 0.97%   |
| Lenovo G50-70 20351                     | 2         | 0.97%   |
| HP Pavilion Gaming Laptop 15-ec1xxx     | 2         | 0.97%   |
| HP Pavilion dv7                         | 2         | 0.97%   |
| HP Notebook                             | 2         | 0.97%   |
| HP EliteBook 2560p                      | 2         | 0.97%   |
| Dell Vostro 1015                        | 2         | 0.97%   |
| Dell Inspiron N5110                     | 2         | 0.97%   |
| Dell Inspiron 3521                      | 2         | 0.97%   |
| ASUS X556UV                             | 2         | 0.97%   |
| ASUS X553MA                             | 2         | 0.97%   |
| ASUS X550LC                             | 2         | 0.97%   |
| ASUS X550JX                             | 2         | 0.97%   |
| Acer Aspire E5-571G                     | 2         | 0.97%   |
| Valve Jupiter                           | 1         | 0.48%   |
| Toshiba Satellite Pro L850-B339         | 1         | 0.48%   |
| Toshiba Satellite L550                  | 1         | 0.48%   |
| Toshiba Satellite L500                  | 1         | 0.48%   |
| Toshiba Satellite C855-1KF              | 1         | 0.48%   |
| Toshiba Satellite C650D                 | 1         | 0.48%   |
| Toshiba Satellite C55-C                 | 1         | 0.48%   |
| Toshiba Satellite C50-A489              | 1         | 0.48%   |
| Toshiba Satellite A300                  | 1         | 0.48%   |
| Sony VPCEH36EF                          | 1         | 0.48%   |
| Sony VGN-CR407E                         | 1         | 0.48%   |
| SCHNEIDER SCL142ALM                     | 1         | 0.48%   |
| Samsung 530U3BI/530U4BI/530U4BH         | 1         | 0.48%   |
| Packard Bell EasyNote ML65              | 1         | 0.48%   |
| MSI Thin GF63 12UDX                     | 1         | 0.48%   |
| MSI Modern 15 A10RBS                    | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 29        | 14.01%  |
| Dell Inspiron         | 17        | 8.21%   |
| HP Pavilion           | 14        | 6.76%   |
| Lenovo ThinkPad       | 12        | 5.8%    |
| Acer Aspire           | 11        | 5.31%   |
| Dell Latitude         | 9         | 4.35%   |
| Toshiba Satellite     | 8         | 3.86%   |
| HP ProBook            | 5         | 2.42%   |
| HP Laptop             | 5         | 2.42%   |
| Dell Vostro           | 5         | 2.42%   |
| ASUS VivoBook         | 5         | 2.42%   |
| ASUS ASUS             | 5         | 2.42%   |
| HP EliteBook          | 4         | 1.93%   |
| ASUS TUF              | 4         | 1.93%   |
| MSI Katana            | 3         | 1.45%   |
| MSI GF63              | 3         | 1.45%   |
| Samsung 300E5EV       | 2         | 0.97%   |
| Lenovo ThinkBook      | 2         | 0.97%   |
| Lenovo G50-70         | 2         | 0.97%   |
| HP Notebook           | 2         | 0.97%   |
| HP 250                | 2         | 0.97%   |
| Dell G15              | 2         | 0.97%   |
| ASUS ZenBook          | 2         | 0.97%   |
| ASUS X556UV           | 2         | 0.97%   |
| ASUS X553MA           | 2         | 0.97%   |
| ASUS X550LC           | 2         | 0.97%   |
| ASUS X550JX           | 2         | 0.97%   |
| ASUS ROG              | 2         | 0.97%   |
| Acer Swift            | 2         | 0.97%   |
| Valve Jupiter         | 1         | 0.48%   |
| Sony VPCEH36EF        | 1         | 0.48%   |
| Sony VGN-CR407E       | 1         | 0.48%   |
| SCHNEIDER SCL142ALM   | 1         | 0.48%   |
| Samsung 530U3BI       | 1         | 0.48%   |
| Packard Bell EasyNote | 1         | 0.48%   |
| MSI Thin              | 1         | 0.48%   |
| MSI Modern            | 1         | 0.48%   |
| MSI GF65              | 1         | 0.48%   |
| Lenovo Yoga           | 1         | 0.48%   |
| Lenovo Y520-15IKBN    | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 27        | 13.04%  |
| 2013 | 19        | 9.18%   |
| 2019 | 18        | 8.7%    |
| 2017 | 17        | 8.21%   |
| 2021 | 16        | 7.73%   |
| 2011 | 16        | 7.73%   |
| 2012 | 14        | 6.76%   |
| 2015 | 13        | 6.28%   |
| 2014 | 12        | 5.8%    |
| 2018 | 10        | 4.83%   |
| 2023 | 9         | 4.35%   |
| 2016 | 9         | 4.35%   |
| 2008 | 9         | 4.35%   |
| 2022 | 6         | 2.9%    |
| 2010 | 6         | 2.9%    |
| 2009 | 6         | 2.9%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 207       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 193       | 92.34%  |
| Enabled  | 16        | 7.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 207       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 66        | 31.43%  |
| 8.01-16.0  | 41        | 19.52%  |
| 3.01-4.0   | 40        | 19.05%  |
| 16.01-24.0 | 40        | 19.05%  |
| 32.01-64.0 | 11        | 5.24%   |
| 2.01-3.0   | 6         | 2.86%   |
| 24.01-32.0 | 4         | 1.9%    |
| 1.01-2.0   | 2         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 70        | 30.97%  |
| 1.01-2.0  | 61        | 26.99%  |
| 4.01-8.0  | 44        | 19.47%  |
| 3.01-4.0  | 34        | 15.04%  |
| 8.01-16.0 | 8         | 3.54%   |
| 0.51-1.0  | 7         | 3.1%    |
| 0.01-0.5  | 1         | 0.44%   |
| Unknown   | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 151       | 71.23%  |
| 2      | 59        | 27.83%  |
| 3      | 2         | 0.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 119       | 56.94%  |
| Yes       | 90        | 43.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 84.13%  |
| No        | 33        | 15.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 203       | 98.07%  |
| No        | 4         | 1.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 85.78%  |
| No        | 30        | 14.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Tunisia | 207       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Tunis              | 117       | 50.21%  |
| Sousse             | 15        | 6.44%   |
| Aryanah            | 13        | 5.58%   |
| Nabeul             | 9         | 3.86%   |
| Sfax               | 6         | 2.58%   |
| Bizerte            | 6         | 2.58%   |
| Ben Arous          | 4         | 1.72%   |
| Rades              | 3         | 1.29%   |
| Kairouan           | 3         | 1.29%   |
| Houmt Souk         | 3         | 1.29%   |
| Gafsa              | 3         | 1.29%   |
| Centre Urbain Nord | 3         | 1.29%   |
| Monastir           | 2         | 0.86%   |
| Mateur             | 2         | 0.86%   |
| Masakin            | 2         | 0.86%   |
| Manouba            | 2         | 0.86%   |
| Mahdia             | 2         | 0.86%   |
| La Marsa           | 2         | 0.86%   |
| Jedeida            | 2         | 0.86%   |
| Borj Cedria        | 2         | 0.86%   |
| As Sanad           | 2         | 0.86%   |
| Zarzis             | 1         | 0.43%   |
| Zaouiat Djedidi    | 1         | 0.43%   |
| Wadi Maliz         | 1         | 0.43%   |
| Tebourba           | 1         | 0.43%   |
| Tataouine          | 1         | 0.43%   |
| Tabarka            | 1         | 0.43%   |
| Soliman            | 1         | 0.43%   |
| Sidi Bouzid        | 1         | 0.43%   |
| Rafraf             | 1         | 0.43%   |
| Oued Lill          | 1         | 0.43%   |
| Le Bardo           | 1         | 0.43%   |
| La Mohammedia      | 1         | 0.43%   |
| La Goulette        | 1         | 0.43%   |
| Kelaa Kebira       | 1         | 0.43%   |
| Kalaa Srira        | 1         | 0.43%   |
| Jendouba           | 1         | 0.43%   |
| Hergla             | 1         | 0.43%   |
| Hammamet           | 1         | 0.43%   |
| Gremda             | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 53        | 65     | 20.31%  |
| Toshiba                     | 28        | 30     | 10.73%  |
| WDC                         | 26        | 35     | 9.96%   |
| Samsung Electronics         | 21        | 23     | 8.05%   |
| Team                        | 15        | 18     | 5.75%   |
| SK hynix                    | 15        | 20     | 5.75%   |
| Hitachi                     | 13        | 14     | 4.98%   |
| Micron Technology           | 11        | 11     | 4.21%   |
| Sandisk                     | 10        | 14     | 3.83%   |
| Kingston                    | 8         | 11     | 3.07%   |
| Intel                       | 8         | 9      | 3.07%   |
| HGST                        | 7         | 8      | 2.68%   |
| A-DATA Technology           | 7         | 9      | 2.68%   |
| Unknown                     | 4         | 5      | 1.53%   |
| Phison Electronics          | 3         | 3      | 1.15%   |
| Patriot                     | 3         | 3      | 1.15%   |
| Fujitsu                     | 3         | 3      | 1.15%   |
| Realtek Semiconductor       | 2         | 2      | 0.77%   |
| PNY                         | 2         | 2      | 0.77%   |
| Emtec                       | 2         | 2      | 0.77%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.38%   |
| UMIS                        | 1         | 1      | 0.38%   |
| TwinMOS                     | 1         | 1      | 0.38%   |
| SPCC                        | 1         | 1      | 0.38%   |
| Silicon Motion              | 1         | 1      | 0.38%   |
| SATAFIRM                    | 1         | 1      | 0.38%   |
| Phison                      | 1         | 1      | 0.38%   |
| OCZ                         | 1         | 1      | 0.38%   |
| O2 Micro                    | 1         | 1      | 0.38%   |
| MSI                         | 1         | 1      | 0.38%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.38%   |
| LITEON                      | 1         | 1      | 0.38%   |
| KIOXIA                      | 1         | 1      | 0.38%   |
| Kingston Technology Company | 1         | 2      | 0.38%   |
| HS-SSD-E100N                | 1         | 1      | 0.38%   |
| HS-SSD-E100                 | 1         | 1      | 0.38%   |
| Hjwdz                       | 1         | 1      | 0.38%   |
| ASUS-PHISON                 | 1         | 2      | 0.38%   |
| Apple                       | 1         | 1      | 0.38%   |
| ADATA Technology            | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 19        | 7.2%    |
| Seagate ST500LT012-1DG142 500GB       | 11        | 4.17%   |
| Seagate ST2000LM007-1R8174 2TB        | 6         | 2.27%   |
| Hitachi HTS545050A7E380 500GB         | 6         | 2.27%   |
| Toshiba MQ04ABF100 1TB                | 5         | 1.89%   |
| Toshiba MQ01ABD100 1TB                | 4         | 1.52%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 1.14%   |
| Seagate ST9500325AS 500GB             | 3         | 1.14%   |
| Micron 2210_MTFDHBA512QFD 512GB       | 3         | 1.14%   |
| Kingston OM8PCP3512F-AI1 512GB        | 3         | 1.14%   |
| Intel SSDPEKNW512GZL 512GB            | 3         | 1.14%   |
| A-DATA SU750 256GB SSD                | 3         | 1.14%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 0.76%   |
| WDC WD20SPZX-08UA7 2TB                | 2         | 0.76%   |
| WDC WD10SPZX-24Z10 1TB                | 2         | 0.76%   |
| WDC WD10SPZX-08Z10 1TB                | 2         | 0.76%   |
| WDC WD10SPCX-24HWST1 1TB              | 2         | 0.76%   |
| Toshiba MQ01ABF050 500GB              | 2         | 0.76%   |
| Toshiba MQ01ABD075 752GB              | 2         | 0.76%   |
| Toshiba MQ01ABD050 500GB              | 2         | 0.76%   |
| Toshiba MK5076GSX 500GB               | 2         | 0.76%   |
| Toshiba MK3275GSX 320GB               | 2         | 0.76%   |
| Team T253X2512G 512GB SSD             | 2         | 0.76%   |
| Team T253X1240G 240GB SSD             | 2         | 0.76%   |
| SK hynix SC311 SATA 256GB SSD         | 2         | 0.76%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 0.76%   |
| SK hynix BC711 HFM256GD3JX013N 256GB  | 2         | 0.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 0.76%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 0.76%   |
| Samsung MZVLQ512HBLU-00B00 512GB      | 2         | 0.76%   |
| Samsung MZVL4512HBLU-00BTW 512GB      | 2         | 0.76%   |
| Phison E12 NVMe Controller 480GB      | 2         | 0.76%   |
| Micron 2450_MTFDKBA512TFK 512GB       | 2         | 0.76%   |
| Kingston NVMe SSD Drive 512GB         | 2         | 0.76%   |
| HGST HTS545050A7E380 500GB            | 2         | 0.76%   |
| Fujitsu MHV2100BH PL 100GB            | 2         | 0.76%   |
| Emtec X150 120GB SSD                  | 2         | 0.76%   |
| A-DATA SU750 512GB SSD                | 2         | 0.76%   |
| WDC WD5000LPZX-60Z10T0 500GB          | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 52        | 64     | 41.27%  |
| Toshiba | 28        | 30     | 22.22%  |
| WDC     | 23        | 31     | 18.25%  |
| Hitachi | 13        | 14     | 10.32%  |
| HGST    | 7         | 8      | 5.56%   |
| Fujitsu | 3         | 3      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 11        | 14     | 20%     |
| Samsung Electronics | 8         | 10     | 14.55%  |
| SK hynix            | 6         | 9      | 10.91%  |
| A-DATA Technology   | 5         | 7      | 9.09%   |
| SanDisk             | 4         | 4      | 7.27%   |
| Patriot             | 3         | 3      | 5.45%   |
| PNY                 | 2         | 2      | 3.64%   |
| Micron Technology   | 2         | 2      | 3.64%   |
| Kingston            | 2         | 3      | 3.64%   |
| Emtec               | 2         | 2      | 3.64%   |
| TwinMOS             | 1         | 1      | 1.82%   |
| SPCC                | 1         | 1      | 1.82%   |
| SATAFIRM            | 1         | 1      | 1.82%   |
| OCZ                 | 1         | 1      | 1.82%   |
| MSI                 | 1         | 1      | 1.82%   |
| LITEON              | 1         | 1      | 1.82%   |
| HS-SSD-E100N        | 1         | 1      | 1.82%   |
| HS-SSD-E100         | 1         | 1      | 1.82%   |
| ASUS-PHISON         | 1         | 2      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 122       | 150    | 49%     |
| NVMe    | 66        | 83     | 26.51%  |
| SSD     | 54        | 67     | 21.69%  |
| MMC     | 4         | 6      | 1.61%   |
| Unknown | 3         | 3      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 156       | 215    | 67.53%  |
| NVMe | 66        | 83     | 28.57%  |
| SAS  | 5         | 5      | 2.16%   |
| MMC  | 4         | 6      | 1.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 103       | 130    | 60.23%  |
| 0.51-1.0   | 59        | 76     | 34.5%   |
| 1.01-2.0   | 9         | 11     | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 66        | 30.56%  |
| 101-250        | 59        | 27.31%  |
| 501-1000       | 32        | 14.81%  |
| 1001-2000      | 17        | 7.87%   |
| 51-100         | 17        | 7.87%   |
| 1-20           | 13        | 6.02%   |
| 21-50          | 6         | 2.78%   |
| More than 3000 | 2         | 0.93%   |
| 2001-3000      | 2         | 0.93%   |
| Unknown        | 2         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 81        | 36.16%  |
| 101-250   | 42        | 18.75%  |
| 21-50     | 39        | 17.41%  |
| 51-100    | 32        | 14.29%  |
| 251-500   | 11        | 4.91%   |
| 501-1000  | 10        | 4.46%   |
| 1001-2000 | 7         | 3.13%   |
| Unknown   | 2         | 0.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Hitachi HTS545050A7E380 500GB                       | 4         | 5      | 15.38%  |
| Seagate ST9500325AS 500GB                           | 3         | 3      | 11.54%  |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 3.85%   |
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 3.85%   |
| WDC WD5000BEVT-22A0RT0 500GB                        | 1         | 1      | 3.85%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 3.85%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 3.85%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 3.85%   |
| Seagate ST9320325AS 320GB                           | 1         | 2      | 3.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 3.85%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 2      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2      | 3.85%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 3.85%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 3.85%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 3.85%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 3.85%   |
| Hitachi HTS542516K9SA00 160GB                       | 1         | 1      | 3.85%   |
| Hitachi HTS541616J9SA00 160GB                       | 1         | 1      | 3.85%   |
| HGST HTS545050A7E380 500GB                          | 1         | 2      | 3.85%   |
| A-DATA Technology SX8100NP 512GB                    | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Hitachi           | 8         | 9      | 30.77%  |
| Seagate           | 7         | 10     | 26.92%  |
| Toshiba           | 4         | 5      | 15.38%  |
| WDC               | 3         | 4      | 11.54%  |
| Micron Technology | 1         | 1      | 3.85%   |
| Kingston          | 1         | 1      | 3.85%   |
| HGST              | 1         | 2      | 3.85%   |
| A-DATA Technology | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 9      | 34.78%  |
| Seagate | 7         | 10     | 30.43%  |
| Toshiba | 4         | 5      | 17.39%  |
| WDC     | 3         | 4      | 13.04%  |
| HGST    | 1         | 2      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 30     | 86.96%  |
| SSD  | 2         | 2      | 8.7%    |
| NVMe | 1         | 1      | 4.35%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK1646GSX 160GB | 1         | 1      | 100%    |

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
| Detected | 103       | 149    | 47.03%  |
| Works    | 92        | 126    | 42.01%  |
| Malfunc  | 23        | 33     | 10.5%   |
| Failed   | 1         | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 174       | 67.97%  |
| AMD                                     | 17        | 6.64%   |
| Samsung Electronics                     | 13        | 5.08%   |
| SK hynix                                | 9         | 3.52%   |
| Micron Technology                       | 9         | 3.52%   |
| SanDisk                                 | 8         | 3.13%   |
| Kingston Technology Company             | 7         | 2.73%   |
| Phison Electronics                      | 6         | 2.34%   |
| Realtek Semiconductor                   | 4         | 1.56%   |
| Silicon Motion                          | 2         | 0.78%   |
| Union Memory (Shenzhen)                 | 1         | 0.39%   |
| Shenzhen Unionmemory Information System | 1         | 0.39%   |
| Shenzhen Longsys Electronics            | 1         | 0.39%   |
| O2 Micro                                | 1         | 0.39%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.39%   |
| KIOXIA                                  | 1         | 0.39%   |
| ADATA Technology                        | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 20        | 7.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 5.99%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 15        | 5.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 5.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 4.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 4.49%   |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 4.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 3.75%   |
| Intel Tiger Lake-LP SATA Controller                                              | 10        | 3.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 9         | 3.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 2.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 2.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 2.25%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 5         | 1.87%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 5         | 1.87%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 1.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 4         | 1.5%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 4         | 1.5%    |
| Phison E12 NVMe Controller                                                       | 4         | 1.5%    |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 4         | 1.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.5%    |
| Realtek RTS5762 NVMe SSD Controller                                              | 3         | 1.12%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 3         | 1.12%   |
| Intel SSD 660P Series                                                            | 3         | 1.12%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 3         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.12%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 0.75%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 2         | 0.75%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation            | 2         | 0.75%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 2         | 0.75%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 161       | 62.4%   |
| NVMe | 66        | 25.58%  |
| RAID | 26        | 10.08%  |
| IDE  | 5         | 1.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 178       | 85.99%  |
| AMD    | 29        | 14.01%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 2.9%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 2.42%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 2.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 2.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 2.42%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.93%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 1.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.45%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.45%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.45%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.45%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.45%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 1.45%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.45%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.45%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.45%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.97%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.97%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.97%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.97%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.97%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.97%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.97%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.97%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.97%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.97%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.97%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.97%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.97%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 2         | 0.97%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.97%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.97%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 0.97%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 56        | 27.05%  |
| Intel Core i7           | 43        | 20.77%  |
| Intel Core i3           | 29        | 14.01%  |
| Other                   | 28        | 13.53%  |
| AMD Ryzen 5             | 11        | 5.31%   |
| Intel Core 2 Duo        | 8         | 3.86%   |
| Intel Celeron           | 8         | 3.86%   |
| Intel Pentium           | 5         | 2.42%   |
| AMD Ryzen 7             | 4         | 1.93%   |
| AMD Ryzen 3             | 2         | 0.97%   |
| Intel Pentium Dual-Core | 1         | 0.48%   |
| Intel Core m3           | 1         | 0.48%   |
| Intel Celeron M         | 1         | 0.48%   |
| Intel Atom              | 1         | 0.48%   |
| AMD Sempron             | 1         | 0.48%   |
| AMD Ryzen 9             | 1         | 0.48%   |
| AMD E2                  | 1         | 0.48%   |
| AMD E                   | 1         | 0.48%   |
| AMD Athlon              | 1         | 0.48%   |
| AMD A8                  | 1         | 0.48%   |
| AMD A6                  | 1         | 0.48%   |
| AMD A4                  | 1         | 0.48%   |
| AMD A10                 | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 107       | 51.69%  |
| 4      | 67        | 32.37%  |
| 6      | 15        | 7.25%   |
| 8      | 8         | 3.86%   |
| 10     | 4         | 1.93%   |
| 14     | 2         | 0.97%   |
| 12     | 2         | 0.97%   |
| 1      | 2         | 0.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 207       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 172       | 83.09%  |
| 1      | 35        | 16.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 205       | 99.03%  |
| 32-bit         | 1         | 0.48%   |
| Unknown        | 1         | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 41.98%  |
| 0x206a7    | 11        | 5.19%   |
| 0x40651    | 9         | 4.25%   |
| 0x806ea    | 8         | 3.77%   |
| 0x806c1    | 8         | 3.77%   |
| 0x306a9    | 8         | 3.77%   |
| 0xa0652    | 7         | 3.3%    |
| 0x806ec    | 7         | 3.3%    |
| 0x406e3    | 5         | 2.36%   |
| 0x906ea    | 4         | 1.89%   |
| 0x506e3    | 4         | 1.89%   |
| 0x306d4    | 4         | 1.89%   |
| 0x1067a    | 4         | 1.89%   |
| 0x08108109 | 4         | 1.89%   |
| 0x806e9    | 3         | 1.42%   |
| 0x706e5    | 3         | 1.42%   |
| 0x306c3    | 3         | 1.42%   |
| 0x20655    | 3         | 1.42%   |
| 0x30678    | 2         | 0.94%   |
| 0x20652    | 2         | 0.94%   |
| 0x08600106 | 2         | 0.94%   |
| 0x08108102 | 2         | 0.94%   |
| 0x06006705 | 2         | 0.94%   |
| 0x06006704 | 2         | 0.94%   |
| 0x906a4    | 1         | 0.47%   |
| 0x906a3    | 1         | 0.47%   |
| 0x706a8    | 1         | 0.47%   |
| 0x6fd      | 1         | 0.47%   |
| 0x6d8      | 1         | 0.47%   |
| 0x506c9    | 1         | 0.47%   |
| 0x406c4    | 1         | 0.47%   |
| 0x40661    | 1         | 0.47%   |
| 0x106ca    | 1         | 0.47%   |
| 0x0a50000f | 1         | 0.47%   |
| 0x0a50000d | 1         | 0.47%   |
| 0x0a50000c | 1         | 0.47%   |
| 0x0a404101 | 1         | 0.47%   |
| 0x08608103 | 1         | 0.47%   |
| 0x08600104 | 1         | 0.47%   |
| 0x02000032 | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 17.87%  |
| Haswell          | 20        | 9.66%   |
| SandyBridge      | 18        | 8.7%    |
| TigerLake        | 13        | 6.28%   |
| Skylake          | 13        | 6.28%   |
| IvyBridge        | 12        | 5.8%    |
| Broadwell        | 10        | 4.83%   |
| Unknown          | 10        | 4.83%   |
| CometLake        | 9         | 4.35%   |
| Westmere         | 8         | 3.86%   |
| IceLake          | 8         | 3.86%   |
| Zen+             | 7         | 3.38%   |
| Penryn           | 7         | 3.38%   |
| Alderlake Hybrid | 5         | 2.42%   |
| Zen 3            | 4         | 1.93%   |
| Silvermont       | 4         | 1.93%   |
| Goldmont plus    | 4         | 1.93%   |
| Excavator        | 4         | 1.93%   |
| Zen 2            | 3         | 1.45%   |
| Goldmont         | 2         | 0.97%   |
| Core             | 2         | 0.97%   |
| Zen              | 1         | 0.48%   |
| Puma             | 1         | 0.48%   |
| Piledriver       | 1         | 0.48%   |
| P6               | 1         | 0.48%   |
| K8 & K10 hybrid  | 1         | 0.48%   |
| Bonnell          | 1         | 0.48%   |
| Bobcat           | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 169       | 53.99%  |
| Nvidia | 88        | 28.12%  |
| AMD    | 56        | 17.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 16        | 5.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 15        | 4.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 12        | 3.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 12        | 3.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 11        | 3.46%   |
| Intel HD Graphics 5500                                                                | 10        | 3.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 9         | 2.83%   |
| Intel UHD Graphics 620                                                                | 9         | 2.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 9         | 2.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 2.52%   |
| Intel HD Graphics 620                                                                 | 7         | 2.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 2.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 7         | 2.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 6         | 1.89%   |
| Nvidia GM108M [GeForce MX110]                                                         | 5         | 1.57%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 5         | 1.57%   |
| Nvidia GP108M [GeForce MX330]                                                         | 4         | 1.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 1.26%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 4         | 1.26%   |
| Intel HD Graphics 530                                                                 | 4         | 1.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 1.26%   |
| Intel Core Processor Integrated Graphics Controller                                   | 4         | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 1.26%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 4         | 1.26%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 4         | 1.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 4         | 1.26%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 3         | 0.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 3         | 0.94%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 3         | 0.94%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 3         | 0.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 0.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 0.94%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 3         | 0.94%   |
| Intel HD Graphics 630                                                                 | 3         | 0.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 3         | 0.94%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                           | 3         | 0.94%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 3         | 0.94%   |
| Nvidia TU117M [GeForce MX450]                                                         | 2         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 76        | 36.71%  |
| 1 x Intel      | 69        | 33.33%  |
| 1 x AMD        | 23        | 11.11%  |
| Intel + AMD    | 21        | 10.14%  |
| AMD + Nvidia   | 9         | 4.35%   |
| 2 x Intel      | 3         | 1.45%   |
| 2 x AMD        | 3         | 1.45%   |
| 1 x Nvidia     | 3         | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 155       | 72.77%  |
| Proprietary | 49        | 23%     |
| Unknown     | 9         | 4.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 131       | 62.38%  |
| 1.01-2.0   | 29        | 13.81%  |
| 0.01-0.5   | 18        | 8.57%   |
| 3.01-4.0   | 14        | 6.67%   |
| 0.51-1.0   | 12        | 5.71%   |
| 7.01-8.0   | 2         | 0.95%   |
| 5.01-6.0   | 2         | 0.95%   |
| 2.01-3.0   | 2         | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 42        | 18.58%  |
| AU Optronics            | 40        | 17.7%   |
| BOE                     | 39        | 17.26%  |
| Samsung Electronics     | 34        | 15.04%  |
| LG Display              | 32        | 14.16%  |
| Hewlett-Packard         | 6         | 2.65%   |
| Chi Mei Optoelectronics | 6         | 2.65%   |
| PANDA                   | 5         | 2.21%   |
| Lenovo                  | 3         | 1.33%   |
| HKC                     | 3         | 1.33%   |
| Acer                    | 3         | 1.33%   |
| Dell                    | 2         | 0.88%   |
| Valve                   | 1         | 0.44%   |
| TMX                     | 1         | 0.44%   |
| Packard Bell            | 1         | 0.44%   |
| NCS                     | 1         | 0.44%   |
| MSI                     | 1         | 0.44%   |
| LG Philips              | 1         | 0.44%   |
| ITE                     | 1         | 0.44%   |
| Goldstar                | 1         | 0.44%   |
| BenQ                    | 1         | 0.44%   |
| ASUSTek Computer        | 1         | 0.44%   |
| Apple                   | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 3.51%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 4         | 1.75%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 4         | 1.75%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 1.75%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 4         | 1.75%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 4         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 3         | 1.32%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch     | 3         | 1.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 1.32%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 1.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 1.32%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 2         | 0.88%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.88%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.88%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.88%   |
| HKC GM27H10C HKC0027 1920x1080 597x336mm 27.0-inch                       | 2         | 0.88%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch               | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.88%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.88%   |
| BOE LCD Monitor BOE08E5 1366x768 344x194mm 15.5-inch                     | 2         | 0.88%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.88%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.88%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                    | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch           | 2         | 0.88%   |
| Acer V193HQV ACR0133 1366x768 410x230mm 18.5-inch                        | 2         | 0.88%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 1         | 0.44%   |
| TMX TL160ADMP03-0 TMX1603 2560x1600 345x215mm 16.0-inch                  | 1         | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.44%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch         | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 91        | 43.13%  |
| 1366x768 (WXGA)   | 89        | 42.18%  |
| 1600x900 (HD+)    | 9         | 4.27%   |
| 1280x800 (WXGA)   | 4         | 1.9%    |
| 3840x2160 (4K)    | 3         | 1.42%   |
| 1920x1200 (WUXGA) | 3         | 1.42%   |
| 1440x900 (WXGA+)  | 3         | 1.42%   |
| 800x1280          | 1         | 0.47%   |
| 3840x1100         | 1         | 0.47%   |
| 3072x1920         | 1         | 0.47%   |
| 2880x1800         | 1         | 0.47%   |
| 2880x1620         | 1         | 0.47%   |
| 2560x1600         | 1         | 0.47%   |
| 2560x1440 (QHD)   | 1         | 0.47%   |
| 1280x1024 (SXGA)  | 1         | 0.47%   |
| 1024x600          | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 149       | 65.64%  |
| 17     | 13        | 5.73%   |
| 14     | 13        | 5.73%   |
| 13     | 10        | 4.41%   |
| 21     | 6         | 2.64%   |
| 24     | 5         | 2.2%    |
| 23     | 5         | 2.2%    |
| 12     | 5         | 2.2%    |
| 27     | 4         | 1.76%   |
| 16     | 4         | 1.76%   |
| 31     | 3         | 1.32%   |
| 18     | 3         | 1.32%   |
| 19     | 2         | 0.88%   |
| 11     | 2         | 0.88%   |
| 20     | 1         | 0.44%   |
| 10     | 1         | 0.44%   |
| 7      | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 165       | 73.99%  |
| 351-400     | 17        | 7.62%   |
| 501-600     | 13        | 5.83%   |
| 401-500     | 12        | 5.38%   |
| 201-300     | 12        | 5.38%   |
| 601-700     | 3         | 1.35%   |
| 1-100       | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 183       | 91.04%  |
| 16/10 | 13        | 6.47%   |
| 5/4   | 1         | 0.5%    |
| 4/3   | 1         | 0.5%    |
| 3/2   | 1         | 0.5%    |
| 3.40  | 1         | 0.5%    |
| 0.67  | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 149       | 65.93%  |
| 81-90          | 16        | 7.08%   |
| 201-250        | 16        | 7.08%   |
| 121-130        | 10        | 4.42%   |
| 71-80          | 5         | 2.21%   |
| 61-70          | 4         | 1.77%   |
| 301-350        | 4         | 1.77%   |
| 141-150        | 4         | 1.77%   |
| 111-120        | 4         | 1.77%   |
| 51-60          | 3         | 1.33%   |
| 351-500        | 3         | 1.33%   |
| 151-200        | 3         | 1.33%   |
| 131-140        | 2         | 0.88%   |
| 41-50          | 1         | 0.44%   |
| 1-40           | 1         | 0.44%   |
| 91-100         | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 86        | 38.91%  |
| 121-160       | 85        | 38.46%  |
| 51-100        | 35        | 15.84%  |
| 161-240       | 10        | 4.52%   |
| More than 240 | 3         | 1.36%   |
| 1-50          | 2         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 171       | 81.43%  |
| 2     | 30        | 14.29%  |
| 0     | 8         | 3.81%   |
| 3     | 1         | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 147       | 42.24%  |
| Intel                             | 82        | 23.56%  |
| Qualcomm Atheros                  | 50        | 14.37%  |
| Broadcom                          | 23        | 6.61%   |
| Ralink                            | 9         | 2.59%   |
| Ralink Technology                 | 8         | 2.3%    |
| MediaTek                          | 8         | 2.3%    |
| Broadcom Limited                  | 7         | 2.01%   |
| ICS Advent                        | 2         | 0.57%   |
| Ericsson Business Mobile Networks | 2         | 0.57%   |
| D-Link                            | 2         | 0.57%   |
| Xiaomi                            | 1         | 0.29%   |
| TP-Link                           | 1         | 0.29%   |
| Sierra Wireless                   | 1         | 0.29%   |
| OPPO Electronics                  | 1         | 0.29%   |
| Marvell Technology Group          | 1         | 0.29%   |
| Lenovo                            | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 92        | 22.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 43        | 10.7%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 3.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 12        | 2.99%   |
| Broadcom BCM43142 802.11b/g/n                                          | 12        | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 2.74%   |
| Intel Wi-Fi 6 AX201                                                    | 11        | 2.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.99%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 8         | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 1.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 6         | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 6         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 1%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 1%      |
| Intel Wireless 8260                                                    | 4         | 1%      |
| Intel Wireless 7265                                                    | 4         | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 1%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1%      |
| Ralink RT5370 Wireless Adapter                                         | 3         | 0.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.75%   |
| Intel Wireless 8265 / 8275                                             | 3         | 0.75%   |
| Intel WiFi Link 5100                                                   | 3         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 0.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 3         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.75%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 3         | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 0.5%    |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.5%    |
| Ralink MT7601U Wireless Adapter                                        | 2         | 0.5%    |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 2         | 0.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.5%    |
| Intel Wireless 7260                                                    | 2         | 0.5%    |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 0.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 80        | 36.53%  |
| Qualcomm Atheros      | 47        | 21.46%  |
| Realtek Semiconductor | 37        | 16.89%  |
| Broadcom              | 19        | 8.68%   |
| Ralink                | 9         | 4.11%   |
| Ralink Technology     | 8         | 3.65%   |
| MediaTek              | 7         | 3.2%    |
| Broadcom Limited      | 7         | 3.2%    |
| D-Link                | 2         | 0.91%   |
| TP-Link               | 1         | 0.46%   |
| Sierra Wireless       | 1         | 0.46%   |
| D-Link System         | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 6.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 5.45%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 5.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 5%      |
| Intel Wi-Fi 6 AX201                                            | 11        | 5%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.64%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 3.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 3.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 2.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 2.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.82%   |
| Intel Wireless 8260                                            | 4         | 1.82%   |
| Intel Wireless 7265                                            | 4         | 1.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 1.82%   |
| Ralink RT5370 Wireless Adapter                                 | 3         | 1.36%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.36%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.36%   |
| Intel WiFi Link 5100                                           | 3         | 1.36%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 1.36%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.91%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.91%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 2         | 0.91%   |
| Intel Wireless 7260                                            | 2         | 0.91%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 0.91%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.91%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 0.91%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 0.91%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 139       | 77.65%  |
| Intel                    | 20        | 11.17%  |
| Qualcomm Atheros         | 7         | 3.91%   |
| Broadcom                 | 5         | 2.79%   |
| ICS Advent               | 2         | 1.12%   |
| Xiaomi                   | 1         | 0.56%   |
| OPPO Electronics         | 1         | 0.56%   |
| MediaTek                 | 1         | 0.56%   |
| Marvell Technology Group | 1         | 0.56%   |
| Lenovo                   | 1         | 0.56%   |
| Huawei Technologies      | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 92        | 51.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 43        | 23.89%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.22%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 3         | 1.67%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 1.11%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.11%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 1.11%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.11%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.56%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.56%   |
| OPPO OnePlus Nord 4                                                    | 1         | 0.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.56%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.56%   |
| Lenovo ThinkPad Lan                                                    | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.56%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.56%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.56%   |
| Intel Ethernet Connection (23) I219-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 0.56%   |
| ICS Advent USB 10/100 LAN                                              | 1         | 0.56%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 1         | 0.56%   |
| Huawei TIT-L01                                                         | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 203       | 53.42%  |
| Ethernet | 175       | 46.05%  |
| Modem    | 2         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 175       | 80.65%  |
| Ethernet | 42        | 19.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 168       | 80.77%  |
| 1     | 40        | 19.23%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 203       | 98.07%  |
| Yes  | 4         | 1.93%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 35.91%  |
| Qualcomm Atheros Communications | 32        | 17.68%  |
| Realtek Semiconductor           | 27        | 14.92%  |
| Lite-On Technology              | 13        | 7.18%   |
| IMC Networks                    | 12        | 6.63%   |
| Broadcom                        | 12        | 6.63%   |
| Ralink                          | 6         | 3.31%   |
| Foxconn / Hon Hai               | 5         | 2.76%   |
| Toshiba                         | 3         | 1.66%   |
| Hewlett-Packard                 | 2         | 1.1%    |
| Realtek                         | 1         | 0.55%   |
| Dell                            | 1         | 0.55%   |
| ASUSTek Computer                | 1         | 0.55%   |
| Apple                           | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                             | 26        | 14.36%  |
| Intel Bluetooth wireless interface                | 20        | 11.05%  |
| Realtek Bluetooth Radio                           | 19        | 10.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 15        | 8.29%   |
| Qualcomm Atheros  Bluetooth Device                | 14        | 7.73%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 8         | 4.42%   |
| Ralink RT3290 Bluetooth                           | 6         | 3.31%   |
| IMC Networks Wireless_Device                      | 6         | 3.31%   |
| Lite-On Bluetooth Device                          | 5         | 2.76%   |
| IMC Networks Bluetooth Radio                      | 5         | 2.76%   |
| Realtek  Bluetooth 4.2 Adapter                    | 4         | 2.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 4         | 2.21%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 4         | 2.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 3         | 1.66%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 3         | 1.66%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 3         | 1.66%   |
| Realtek RTL8723B Bluetooth                        | 2         | 1.1%    |
| Realtek 802.11ac WLAN Adapter                     | 2         | 1.1%    |
| Qualcomm Atheros AR9462 Bluetooth                 | 2         | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 1.1%    |
| Lite-On BCM43142A0                                | 2         | 1.1%    |
| Intel AX211 Bluetooth                             | 2         | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                | 2         | 1.1%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 2         | 1.1%    |
| Toshiba RT Bluetooth Radio                        | 1         | 0.55%   |
| Toshiba Bluetooth USB Host Controller             | 1         | 0.55%   |
| Toshiba BCM43142A0                                | 1         | 0.55%   |
| Realtek Bluetooth Radio                           | 1         | 0.55%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 1         | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.55%   |
| Intel Wireless-AC 3168 Bluetooth                  | 1         | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                 | 1         | 0.55%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter      | 1         | 0.55%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 1         | 0.55%   |
| Dell DW375 Bluetooth Module                       | 1         | 0.55%   |
| Broadcom HP Portable Valentine                    | 1         | 0.55%   |
| Broadcom HP Portable Bumble Bee                   | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 178       | 69.26%  |
| Nvidia              | 37        | 14.4%   |
| AMD                 | 35        | 13.62%  |
| C-Media Electronics | 3         | 1.17%   |
| Razer USA           | 1         | 0.39%   |
| Plantronics         | 1         | 0.39%   |
| JMTek               | 1         | 0.39%   |
| DSEA A/S            | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 8.5%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 20        | 6.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 5.56%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 4.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 4.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 4.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 4.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.27%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 2.94%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 2.29%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 2.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.63%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 4         | 1.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.31%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 4         | 1.31%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.31%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.98%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 0.98%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.98%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 47        | 28.66%  |
| SK hynix                     | 27        | 16.46%  |
| Micron Technology            | 24        | 14.63%  |
| Team                         | 20        | 12.2%   |
| A-DATA Technology            | 10        | 6.1%    |
| Unknown                      | 7         | 4.27%   |
| Nanya Technology             | 5         | 3.05%   |
| Elpida                       | 5         | 3.05%   |
| Ramaxel Technology           | 4         | 2.44%   |
| Crucial                      | 4         | 2.44%   |
| Kingston                     | 3         | 1.83%   |
| Toshiba                      | 2         | 1.22%   |
| Hikvision                    | 2         | 1.22%   |
| Unknown (ABCD)               | 1         | 0.61%   |
| Patriot Memory (PDP Systems) | 1         | 0.61%   |
| Patriot                      | 1         | 0.61%   |
| ASint Technology             | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 9         | 5.2%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 2.31%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 3         | 1.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.73%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.73%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 3         | 1.73%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.73%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 1.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.73%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 3         | 1.73%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                      | 3         | 1.73%   |
| Toshiba RAM 8HTF12864HDY-800G1 4096MB SODIMM 1066MT/s            | 2         | 1.16%   |
| Toshiba RAM 64T128020EDL2.5C2 4096MB SODIMM 1066MT/s             | 2         | 1.16%   |
| Team RAM TEAMGROUP-SD4-3200 32GB Row Of Chips DDR4 3200MT/s      | 2         | 1.16%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 2         | 1.16%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 2         | 1.16%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.16%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.16%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.16%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.16%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.16%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.16%   |
| Micron RAM MT40A512M16TB-062E:R 4GB SODIMM DDR4 3200MT/s         | 2         | 1.16%   |
| Micron RAM Module 4GB Row Of Chips DDR4 2400MT/s                 | 2         | 1.16%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.16%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.58%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.58%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR2 400MT/s                       | 1         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.58%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 0.58%   |
| Team RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 0.58%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 1         | 0.58%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR 975MT/s             | 1         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 70        | 54.26%  |
| DDR3   | 37        | 28.68%  |
| DDR2   | 7         | 5.43%   |
| DDR5   | 4         | 3.1%    |
| SDRAM  | 3         | 2.33%   |
| LPDDR5 | 3         | 2.33%   |
| LPDDR4 | 3         | 2.33%   |
| LPDDR3 | 2         | 1.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 116       | 87.22%  |
| Row Of Chips | 16        | 12.03%  |
| Chip         | 1         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 55        | 34.59%  |
| 4096  | 47        | 29.56%  |
| 16384 | 23        | 14.47%  |
| 2048  | 17        | 10.69%  |
| 32768 | 13        | 8.18%   |
| 1024  | 4         | 2.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 36        | 24.83%  |
| 2667    | 28        | 19.31%  |
| 1600    | 21        | 14.48%  |
| 1334    | 13        | 8.97%   |
| 2400    | 11        | 7.59%   |
| 4800    | 4         | 2.76%   |
| 2133    | 4         | 2.76%   |
| 6400    | 3         | 2.07%   |
| 4199    | 3         | 2.07%   |
| 3266    | 3         | 2.07%   |
| 1867    | 3         | 2.07%   |
| 1333    | 3         | 2.07%   |
| 667     | 3         | 2.07%   |
| 8400    | 2         | 1.38%   |
| 1066    | 2         | 1.38%   |
| Unknown | 2         | 1.38%   |
| 1067    | 1         | 0.69%   |
| 975     | 1         | 0.69%   |
| 800     | 1         | 0.69%   |
| 400     | 1         | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 39        | 20.42%  |
| IMC Networks                           | 25        | 13.09%  |
| Realtek Semiconductor                  | 23        | 12.04%  |
| Microdia                               | 17        | 8.9%    |
| Bison Electronics                      | 15        | 7.85%   |
| Suyin                                  | 10        | 5.24%   |
| Sunplus Innovation Technology          | 9         | 4.71%   |
| Syntek                                 | 8         | 4.19%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.19%   |
| Luxvisions Innotech Limited            | 7         | 3.66%   |
| Quanta                                 | 6         | 3.14%   |
| Lite-On Technology                     | 6         | 3.14%   |
| Sonix Technology                       | 3         | 1.57%   |
| Ricoh                                  | 2         | 1.05%   |
| Apple                                  | 2         | 1.05%   |
| Alcor Micro                            | 2         | 1.05%   |
| Acer                                   | 2         | 1.05%   |
| Silicon Motion                         | 1         | 0.52%   |
| ShineTech                              | 1         | 0.52%   |
| Samsung Electronics                    | 1         | 0.52%   |
| Lenovo                                 | 1         | 0.52%   |
| Importek                               | 1         | 0.52%   |
| Genesys Logic                          | 1         | 0.52%   |
| ALi                                    | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 10        | 5.21%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 4.69%   |
| IMC Networks Integrated Camera                                             | 7         | 3.65%   |
| Microdia Integrated_Webcam_HD                                              | 6         | 3.13%   |
| Bison Integrated Camera                                                    | 6         | 3.13%   |
| Sunplus Integrated_Webcam_HD                                               | 5         | 2.6%    |
| Realtek Integrated_Webcam_HD                                               | 5         | 2.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 5         | 2.6%    |
| Syntek Integrated Camera                                                   | 4         | 2.08%   |
| Realtek USB Camera                                                         | 4         | 2.08%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 4         | 2.08%   |
| Lite-On Integrated Camera                                                  | 4         | 2.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 4         | 2.08%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 2.08%   |
| Chicony HD WebCam                                                          | 4         | 2.08%   |
| Bison HD Webcam                                                            | 4         | 2.08%   |
| Syntek EasyCamera                                                          | 3         | 1.56%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 3         | 1.56%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 3         | 1.56%   |
| Quanta HD WebCam                                                           | 3         | 1.56%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 1.56%   |
| Suyin Integrated_Webcam_HD                                                 | 2         | 1.04%   |
| Suyin HP TrueVision HD                                                     | 2         | 1.04%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.04%   |
| Realtek EasyCamera                                                         | 2         | 1.04%   |
| Microdia Webcam SC-10HDD12636P                                             | 2         | 1.04%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 2         | 1.04%   |
| IMC Networks Lenovo EasyCamera                                             | 2         | 1.04%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 1.04%   |
| Chicony EasyCamera                                                         | 2         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 2         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 2         | 1.04%   |
| Bison Lenovo EasyCamera                                                    | 2         | 1.04%   |
| Bison EasyCamera                                                           | 2         | 1.04%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                                       | 1         | 0.52%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.52%   |
| Suyin Laptop_Integrated_Webcam_2HDM                                        | 1         | 0.52%   |
| Suyin HP webcam [dv6-1190en]                                               | 1         | 0.52%   |
| Suyin HP Integrated Webcam                                                 | 1         | 0.52%   |
| Suyin HD WebCam                                                            | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 8         | 50%     |
| Synaptics                          | 2         | 12.5%   |
| LighTuning Technology              | 2         | 12.5%   |
| Upek                               | 1         | 6.25%   |
| Shenzhen Goodix Technology         | 1         | 6.25%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 6.25%   |
| AuthenTec                          | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 3         | 18.75%  |
| Validity Sensors VFS471 Fingerprint Reader                      | 2         | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 6.25%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 6.25%   |
| Validity Sensors Fingerprint scanner                            | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 1         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 6.25%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 6.25%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 6.25%   |
| AuthenTec AES1600                                               | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Broadcom    | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 60%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom 5880                                                                | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 151       | 68.64%  |
| 1     | 55        | 25%     |
| 2     | 7         | 3.18%   |
| 3     | 5         | 2.27%   |
| 5     | 1         | 0.45%   |
| 4     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 21        | 24.14%  |
| Fingerprint reader       | 16        | 18.39%  |
| Net/wireless             | 15        | 17.24%  |
| Bluetooth                | 9         | 10.34%  |
| Communication controller | 5         | 5.75%   |
| Chipcard                 | 5         | 5.75%   |
| Camera                   | 5         | 5.75%   |
| Storage                  | 2         | 2.3%    |
| Sound                    | 2         | 2.3%    |
| Net/ethernet             | 2         | 2.3%    |
| Multimedia controller    | 2         | 2.3%    |
| Card reader              | 2         | 2.3%    |
| Network                  | 1         | 1.15%   |

