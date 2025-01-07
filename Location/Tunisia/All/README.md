Linux in Tunisia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Tunisia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Tunisia/Desktop/README.md) and [notebooks](/Location/Tunisia/Notebook/README.md).

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

Total: 389

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | AOD257                      | Notebook    | [48ac1f7a96](https://linux-hardware.org/?probe=48ac1f7a96) | Jan 06, 2025 |
| Dell          | Vostro 3520                 | Notebook    | [77b90abaf0](https://linux-hardware.org/?probe=77b90abaf0) | Jan 03, 2025 |
| Acer          | Aspire E5-576G              | Notebook    | [9f344c14d4](https://linux-hardware.org/?probe=9f344c14d4) | Jan 03, 2025 |
| Acer          | AOD257                      | Notebook    | [cd57ba84bc](https://linux-hardware.org/?probe=cd57ba84bc) | Jan 03, 2025 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [125c5a0ee0](https://linux-hardware.org/?probe=125c5a0ee0) | Dec 31, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [493dd462e8](https://linux-hardware.org/?probe=493dd462e8) | Dec 29, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [653f633b8c](https://linux-hardware.org/?probe=653f633b8c) | Dec 23, 2024 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [00a92f4595](https://linux-hardware.org/?probe=00a92f4595) | Dec 08, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8a76df0398](https://linux-hardware.org/?probe=8a76df0398) | Dec 04, 2024 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [cd3c505b80](https://linux-hardware.org/?probe=cd3c505b80) | Dec 02, 2024 |
| Lenovo        | ThinkBook 15 20VE           | Notebook    | [c33fad56a0](https://linux-hardware.org/?probe=c33fad56a0) | Nov 30, 2024 |
| Acer          | Aspire E5-576G              | Notebook    | [66f3dc8d70](https://linux-hardware.org/?probe=66f3dc8d70) | Nov 27, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [4f31d462cf](https://linux-hardware.org/?probe=4f31d462cf) | Nov 26, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [7e1f2fee77](https://linux-hardware.org/?probe=7e1f2fee77) | Nov 25, 2024 |
| Dell          | Latitude 5520               | Notebook    | [007adcd9ad](https://linux-hardware.org/?probe=007adcd9ad) | Nov 16, 2024 |
| HP            | EliteBook 2560p             | Notebook    | [84d5a17ce2](https://linux-hardware.org/?probe=84d5a17ce2) | Nov 12, 2024 |
| Dell          | Inspiron 16 5630            | Notebook    | [03507b0e2d](https://linux-hardware.org/?probe=03507b0e2d) | Nov 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [4aed7cd34c](https://linux-hardware.org/?probe=4aed7cd34c) | Nov 10, 2024 |
| SCHNEIDER     | SCL142ALM                   | Notebook    | [c03f43252b](https://linux-hardware.org/?probe=c03f43252b) | Nov 09, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [a50c814c14](https://linux-hardware.org/?probe=a50c814c14) | Nov 06, 2024 |
| Dell          | Latitude 3520               | Notebook    | [3b214e9caa](https://linux-hardware.org/?probe=3b214e9caa) | Nov 03, 2024 |
| Sony          | VGN-CR407E                  | Notebook    | [3bb8604ae1](https://linux-hardware.org/?probe=3bb8604ae1) | Oct 27, 2024 |
| SCHNEIDER     | SCL142ALM                   | Notebook    | [f859f241e9](https://linux-hardware.org/?probe=f859f241e9) | Oct 20, 2024 |
| SCHNEIDER     | SCL142ALM                   | Notebook    | [4df59a8a13](https://linux-hardware.org/?probe=4df59a8a13) | Oct 11, 2024 |
| SCHNEIDER     | SCL142ALM                   | Notebook    | [454208e32b](https://linux-hardware.org/?probe=454208e32b) | Oct 11, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [1183c6ec8f](https://linux-hardware.org/?probe=1183c6ec8f) | Oct 01, 2024 |
| Dell          | Vostro 1015                 | Notebook    | [e2c275f617](https://linux-hardware.org/?probe=e2c275f617) | Sep 23, 2024 |
| Dell          | Inspiron 16 5630            | Notebook    | [60730f30d3](https://linux-hardware.org/?probe=60730f30d3) | Sep 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [87a9f12a18](https://linux-hardware.org/?probe=87a9f12a18) | Sep 21, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [788e3c4a7e](https://linux-hardware.org/?probe=788e3c4a7e) | Sep 17, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [32024e5714](https://linux-hardware.org/?probe=32024e5714) | Sep 15, 2024 |
| ASUSTek       | X550LC                      | Notebook    | [470155ee76](https://linux-hardware.org/?probe=470155ee76) | Sep 15, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [4f52ba9b2f](https://linux-hardware.org/?probe=4f52ba9b2f) | Aug 31, 2024 |
| Dell          | Inspiron 16 5630            | Notebook    | [c584ed4ee0](https://linux-hardware.org/?probe=c584ed4ee0) | Aug 06, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [a717781b71](https://linux-hardware.org/?probe=a717781b71) | Jul 28, 2024 |
| Dell          | Vostro 3520                 | Notebook    | [51dc7545f8](https://linux-hardware.org/?probe=51dc7545f8) | Jul 26, 2024 |
| MSI           | Katana GF76 11UC            | Notebook    | [8ef6e6c1ae](https://linux-hardware.org/?probe=8ef6e6c1ae) | Jul 20, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2040d5317c](https://linux-hardware.org/?probe=2040d5317c) | Jul 19, 2024 |
| HP            | 15                          | Notebook    | [1f9185f9f9](https://linux-hardware.org/?probe=1f9185f9f9) | Jul 14, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [25ec8d18cc](https://linux-hardware.org/?probe=25ec8d18cc) | Jul 12, 2024 |
| HP            | OMEN by Laptop              | Notebook    | [2bc0d5b3b5](https://linux-hardware.org/?probe=2bc0d5b3b5) | Jun 28, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [da9f957584](https://linux-hardware.org/?probe=da9f957584) | Jun 27, 2024 |
| MSI           | Modern 15 A10RBS            | Notebook    | [cd4213c1b6](https://linux-hardware.org/?probe=cd4213c1b6) | Jun 26, 2024 |
| Lenovo        | ThinkPad T430 2349QM6       | Notebook    | [7e0e4be146](https://linux-hardware.org/?probe=7e0e4be146) | Jun 23, 2024 |
| ASUSTek       | X541UJ                      | Notebook    | [96a8342fe7](https://linux-hardware.org/?probe=96a8342fe7) | Jun 12, 2024 |
| Dell          | Latitude E6540              | Notebook    | [aba547e3a8](https://linux-hardware.org/?probe=aba547e3a8) | Jun 07, 2024 |
| ASUSTek       | F9E                         | Notebook    | [69b06a4303](https://linux-hardware.org/?probe=69b06a4303) | Jun 05, 2024 |
| HP            | Pavilion dv7                | Notebook    | [826b443536](https://linux-hardware.org/?probe=826b443536) | May 31, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [578e9c44c3](https://linux-hardware.org/?probe=578e9c44c3) | May 30, 2024 |
| Dell          | 0TP412                      | Desktop     | [d78622c7e2](https://linux-hardware.org/?probe=d78622c7e2) | May 24, 2024 |
| MSI           | Thin GF63 12UDX             | Notebook    | [8baf5df767](https://linux-hardware.org/?probe=8baf5df767) | May 21, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [c7b984f381](https://linux-hardware.org/?probe=c7b984f381) | May 19, 2024 |
| ASUSTek       | 900                         | Notebook    | [9d033691b4](https://linux-hardware.org/?probe=9d033691b4) | May 19, 2024 |
| ASUSTek       | 900                         | Notebook    | [770a3f0d8d](https://linux-hardware.org/?probe=770a3f0d8d) | May 17, 2024 |
| ASUSTek       | F9E                         | Notebook    | [a1e97701b0](https://linux-hardware.org/?probe=a1e97701b0) | May 14, 2024 |
| Dell          | Inspiron 16 5630            | Notebook    | [7a81cef57f](https://linux-hardware.org/?probe=7a81cef57f) | May 13, 2024 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [1fac0018e6](https://linux-hardware.org/?probe=1fac0018e6) | May 12, 2024 |
| ASUSTek       | F9E                         | Notebook    | [faf50e0119](https://linux-hardware.org/?probe=faf50e0119) | May 05, 2024 |
| ASUSTek       | F9E                         | Notebook    | [29fd3412dc](https://linux-hardware.org/?probe=29fd3412dc) | May 02, 2024 |
| MSI           | Katana 15 B12VGK            | Notebook    | [c8e4cb337e](https://linux-hardware.org/?probe=c8e4cb337e) | Apr 29, 2024 |
| HP            | Notebook                    | Notebook    | [b45aa2251b](https://linux-hardware.org/?probe=b45aa2251b) | Apr 28, 2024 |
| HP            | Notebook                    | Notebook    | [9f5ae93269](https://linux-hardware.org/?probe=9f5ae93269) | Apr 28, 2024 |
| HP            | 15                          | Notebook    | [0e0d6ab57a](https://linux-hardware.org/?probe=0e0d6ab57a) | Apr 28, 2024 |
| HP            | 15                          | Notebook    | [d329164137](https://linux-hardware.org/?probe=d329164137) | Apr 28, 2024 |
| ASUSTek       | N53SN                       | Notebook    | [4c0db81fd7](https://linux-hardware.org/?probe=4c0db81fd7) | Apr 28, 2024 |
| Lenovo        | ThinkPad E590 20NB0002FE    | Notebook    | [d7eb12b86f](https://linux-hardware.org/?probe=d7eb12b86f) | Apr 12, 2024 |
| Lenovo        | ThinkPad E590 20NB0002FE    | Notebook    | [b6cecec324](https://linux-hardware.org/?probe=b6cecec324) | Apr 12, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [1c04e1c19f](https://linux-hardware.org/?probe=1c04e1c19f) | Apr 06, 2024 |
| Dell          | G15 5511                    | Notebook    | [325c990fec](https://linux-hardware.org/?probe=325c990fec) | Mar 31, 2024 |
| Dell          | G15 5511                    | Notebook    | [f821631f0a](https://linux-hardware.org/?probe=f821631f0a) | Mar 31, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [eb685d2c83](https://linux-hardware.org/?probe=eb685d2c83) | Mar 28, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [42aee3b9b6](https://linux-hardware.org/?probe=42aee3b9b6) | Mar 22, 2024 |
| Dell          | Vostro 1015                 | Notebook    | [cdb101a446](https://linux-hardware.org/?probe=cdb101a446) | Mar 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [22c9b2637a](https://linux-hardware.org/?probe=22c9b2637a) | Mar 20, 2024 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [72f94a6e34](https://linux-hardware.org/?probe=72f94a6e34) | Mar 03, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [8891d1d31b](https://linux-hardware.org/?probe=8891d1d31b) | Feb 21, 2024 |
| ASUSTek       | N56VB                       | Notebook    | [fd2523e121](https://linux-hardware.org/?probe=fd2523e121) | Feb 09, 2024 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [c3e8a9f8e9](https://linux-hardware.org/?probe=c3e8a9f8e9) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [689f8869db](https://linux-hardware.org/?probe=689f8869db) | Jan 01, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [14f7c6a9df](https://linux-hardware.org/?probe=14f7c6a9df) | Dec 31, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [851f0386b3](https://linux-hardware.org/?probe=851f0386b3) | Dec 21, 2023 |
| Lenovo        | ThinkPad T430 2349QM6       | Notebook    | [398d3beb97](https://linux-hardware.org/?probe=398d3beb97) | Dec 16, 2023 |
| ECS           | G31T-M9                     | Desktop     | [30204f2a00](https://linux-hardware.org/?probe=30204f2a00) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [5ec5788395](https://linux-hardware.org/?probe=5ec5788395) | Dec 13, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [936fe9e153](https://linux-hardware.org/?probe=936fe9e153) | Nov 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [d322062b88](https://linux-hardware.org/?probe=d322062b88) | Nov 22, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [f8a086226b](https://linux-hardware.org/?probe=f8a086226b) | Nov 18, 2023 |
| ECS           | G31T-M9                     | Desktop     | [783af811f2](https://linux-hardware.org/?probe=783af811f2) | Nov 16, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [32874ad264](https://linux-hardware.org/?probe=32874ad264) | Nov 08, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [81ff23096c](https://linux-hardware.org/?probe=81ff23096c) | Nov 08, 2023 |
| HP            | Pavilion g6                 | Notebook    | [e6f697f0c0](https://linux-hardware.org/?probe=e6f697f0c0) | Nov 02, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [e8ea93da6d](https://linux-hardware.org/?probe=e8ea93da6d) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [6cbfd91e78](https://linux-hardware.org/?probe=6cbfd91e78) | Oct 30, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [1eed0a53b6](https://linux-hardware.org/?probe=1eed0a53b6) | Oct 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [d91ad654e6](https://linux-hardware.org/?probe=d91ad654e6) | Oct 18, 2023 |
| ASUSTek       | X556UJ                      | Notebook    | [010c7b3e14](https://linux-hardware.org/?probe=010c7b3e14) | Oct 17, 2023 |
| ASUSTek       | X556UJ                      | Notebook    | [e9065ad0d2](https://linux-hardware.org/?probe=e9065ad0d2) | Oct 17, 2023 |
| Toshiba       | Satellite C855-1KF          | Notebook    | [1dbc7c0de3](https://linux-hardware.org/?probe=1dbc7c0de3) | Oct 15, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [3c4e1ac4b0](https://linux-hardware.org/?probe=3c4e1ac4b0) | Oct 05, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [97bb5f9ea1](https://linux-hardware.org/?probe=97bb5f9ea1) | Sep 28, 2023 |
| Intel         | H81                         | Desktop     | [34f1a336e3](https://linux-hardware.org/?probe=34f1a336e3) | Sep 14, 2023 |
| Dell          | 0J8G6F A03                  | Desktop     | [490dd7a710](https://linux-hardware.org/?probe=490dd7a710) | Sep 04, 2023 |
| Intel         | H81                         | Desktop     | [98f445e831](https://linux-hardware.org/?probe=98f445e831) | Sep 03, 2023 |
| Dell          | G15 5530                    | Notebook    | [ababfa6c5e](https://linux-hardware.org/?probe=ababfa6c5e) | Aug 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [885c22f859](https://linux-hardware.org/?probe=885c22f859) | Aug 30, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [35aa466ca4](https://linux-hardware.org/?probe=35aa466ca4) | Aug 26, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [3e63b3dec0](https://linux-hardware.org/?probe=3e63b3dec0) | Aug 09, 2023 |
| HP            | ProBook 4740s               | Notebook    | [1c56daf13e](https://linux-hardware.org/?probe=1c56daf13e) | Aug 09, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [a036ddad16](https://linux-hardware.org/?probe=a036ddad16) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [732b1abb2d](https://linux-hardware.org/?probe=732b1abb2d) | Aug 03, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [1b07e3c9b2](https://linux-hardware.org/?probe=1b07e3c9b2) | Jul 31, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8d94c58c16](https://linux-hardware.org/?probe=8d94c58c16) | Jul 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [cd9bfc68b6](https://linux-hardware.org/?probe=cd9bfc68b6) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f22c6fa671](https://linux-hardware.org/?probe=f22c6fa671) | Jul 15, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [df243ca59d](https://linux-hardware.org/?probe=df243ca59d) | Jul 08, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [7973ce0535](https://linux-hardware.org/?probe=7973ce0535) | Jun 28, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [58fc9f200f](https://linux-hardware.org/?probe=58fc9f200f) | Jun 25, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [22a8a9d964](https://linux-hardware.org/?probe=22a8a9d964) | Jun 10, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [681baff23c](https://linux-hardware.org/?probe=681baff23c) | Jun 04, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [ae3bf8f79c](https://linux-hardware.org/?probe=ae3bf8f79c) | Jun 03, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [ebb5445720](https://linux-hardware.org/?probe=ebb5445720) | May 29, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [5098185f54](https://linux-hardware.org/?probe=5098185f54) | May 26, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [30f7b973cd](https://linux-hardware.org/?probe=30f7b973cd) | May 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1bd26fc56f](https://linux-hardware.org/?probe=1bd26fc56f) | May 10, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fc978d0a03](https://linux-hardware.org/?probe=fc978d0a03) | May 09, 2023 |
| HP            | Pavilion g6                 | Notebook    | [26830f860f](https://linux-hardware.org/?probe=26830f860f) | May 06, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a78e3941f5](https://linux-hardware.org/?probe=a78e3941f5) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [eb559d913e](https://linux-hardware.org/?probe=eb559d913e) | Apr 30, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [a4515227d6](https://linux-hardware.org/?probe=a4515227d6) | Apr 24, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [594ceb6023](https://linux-hardware.org/?probe=594ceb6023) | Apr 19, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [eeba9d18fa](https://linux-hardware.org/?probe=eeba9d18fa) | Apr 01, 2023 |
| Dell          | 0HMX8D A01                  | Desktop     | [36b8532260](https://linux-hardware.org/?probe=36b8532260) | Mar 31, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [d22c35c46d](https://linux-hardware.org/?probe=d22c35c46d) | Mar 29, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [2f1e23e614](https://linux-hardware.org/?probe=2f1e23e614) | Mar 24, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [13c8ab8634](https://linux-hardware.org/?probe=13c8ab8634) | Mar 18, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [23c4dc4c7c](https://linux-hardware.org/?probe=23c4dc4c7c) | Mar 17, 2023 |
| Pegatron      | Eureka3                     | Desktop     | [9a13411e08](https://linux-hardware.org/?probe=9a13411e08) | Mar 14, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [be4f604d4f](https://linux-hardware.org/?probe=be4f604d4f) | Mar 14, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [4094f2a910](https://linux-hardware.org/?probe=4094f2a910) | Mar 14, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [8659fe0f82](https://linux-hardware.org/?probe=8659fe0f82) | Mar 07, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [33b5924e71](https://linux-hardware.org/?probe=33b5924e71) | Mar 07, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [c5d5b5f2c9](https://linux-hardware.org/?probe=c5d5b5f2c9) | Mar 04, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [167394f685](https://linux-hardware.org/?probe=167394f685) | Mar 04, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [817b72f78f](https://linux-hardware.org/?probe=817b72f78f) | Mar 02, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [42d050d5ff](https://linux-hardware.org/?probe=42d050d5ff) | Feb 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50a16e7924](https://linux-hardware.org/?probe=50a16e7924) | Feb 25, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [09df6de7db](https://linux-hardware.org/?probe=09df6de7db) | Feb 23, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ddd8c34644](https://linux-hardware.org/?probe=ddd8c34644) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [39b9facc37](https://linux-hardware.org/?probe=39b9facc37) | Feb 16, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [1c8bb5ecfc](https://linux-hardware.org/?probe=1c8bb5ecfc) | Feb 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4cb7a5f214](https://linux-hardware.org/?probe=4cb7a5f214) | Jan 30, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [0eb0b40b2b](https://linux-hardware.org/?probe=0eb0b40b2b) | Jan 23, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [391c3404d3](https://linux-hardware.org/?probe=391c3404d3) | Jan 20, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [993adedd8e](https://linux-hardware.org/?probe=993adedd8e) | Jan 18, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a279a876f3](https://linux-hardware.org/?probe=a279a876f3) | Jan 17, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [a48fadfcbd](https://linux-hardware.org/?probe=a48fadfcbd) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [11202d4caa](https://linux-hardware.org/?probe=11202d4caa) | Dec 11, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [8a112e02eb](https://linux-hardware.org/?probe=8a112e02eb) | Dec 11, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [00c90e5b24](https://linux-hardware.org/?probe=00c90e5b24) | Dec 08, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [307022e985](https://linux-hardware.org/?probe=307022e985) | Nov 30, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [778a84af28](https://linux-hardware.org/?probe=778a84af28) | Nov 28, 2022 |
| HP            | Pavilion g6                 | Notebook    | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [50c70cb811](https://linux-hardware.org/?probe=50c70cb811) | Nov 20, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [27756e9ad7](https://linux-hardware.org/?probe=27756e9ad7) | Nov 20, 2022 |
| Intel         | H81                         | Desktop     | [f99a623867](https://linux-hardware.org/?probe=f99a623867) | Nov 17, 2022 |
| Intel         | H81                         | Desktop     | [5bfd56a1f8](https://linux-hardware.org/?probe=5bfd56a1f8) | Nov 17, 2022 |
| AZW           | Gemini M                    | Desktop     | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [9c732b8892](https://linux-hardware.org/?probe=9c732b8892) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [f7cd80c534](https://linux-hardware.org/?probe=f7cd80c534) | Nov 14, 2022 |
| ASUSTek       | UX330CAK                    | Notebook    | [bd7d377985](https://linux-hardware.org/?probe=bd7d377985) | Nov 14, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [bc0831aa5e](https://linux-hardware.org/?probe=bc0831aa5e) | Nov 13, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c4811dfc5e](https://linux-hardware.org/?probe=c4811dfc5e) | Nov 12, 2022 |
| Pegatron      | Benicia                     | Desktop     | [f345c0beb9](https://linux-hardware.org/?probe=f345c0beb9) | Nov 11, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [122263e850](https://linux-hardware.org/?probe=122263e850) | Nov 06, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7b65a89d4f](https://linux-hardware.org/?probe=7b65a89d4f) | Nov 04, 2022 |
| HP            | 14                          | Notebook    | [7611c14813](https://linux-hardware.org/?probe=7611c14813) | Oct 31, 2022 |
| Lenovo        | ThinkPad E15 20RD001QFE     | Notebook    | [cc9f8c3aad](https://linux-hardware.org/?probe=cc9f8c3aad) | Oct 26, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [bb2647f6c8](https://linux-hardware.org/?probe=bb2647f6c8) | Oct 24, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [bec3ad2194](https://linux-hardware.org/?probe=bec3ad2194) | Oct 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9594fcc1e0](https://linux-hardware.org/?probe=9594fcc1e0) | Oct 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [71734a9abe](https://linux-hardware.org/?probe=71734a9abe) | Oct 19, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [f80eb01da1](https://linux-hardware.org/?probe=f80eb01da1) | Oct 13, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [f44ca565c1](https://linux-hardware.org/?probe=f44ca565c1) | Oct 11, 2022 |
| MSI           | MS-B0A41                    | Desktop     | [a0d7f23a22](https://linux-hardware.org/?probe=a0d7f23a22) | Oct 05, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [0fce536c7d](https://linux-hardware.org/?probe=0fce536c7d) | Sep 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [ad367d006a](https://linux-hardware.org/?probe=ad367d006a) | Sep 22, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [eed790913e](https://linux-hardware.org/?probe=eed790913e) | Sep 16, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [22a1cba716](https://linux-hardware.org/?probe=22a1cba716) | Sep 02, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [4fdb057f33](https://linux-hardware.org/?probe=4fdb057f33) | Sep 02, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [659506d72f](https://linux-hardware.org/?probe=659506d72f) | Sep 02, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [739cbda612](https://linux-hardware.org/?probe=739cbda612) | Sep 02, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [a557da948a](https://linux-hardware.org/?probe=a557da948a) | Aug 31, 2022 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [aa5f4a0207](https://linux-hardware.org/?probe=aa5f4a0207) | Aug 29, 2022 |
| HP            | 2AF7                        | Desktop     | [7605e926c4](https://linux-hardware.org/?probe=7605e926c4) | Aug 25, 2022 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [f3facd36da](https://linux-hardware.org/?probe=f3facd36da) | Aug 24, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [f0d245ec0f](https://linux-hardware.org/?probe=f0d245ec0f) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f4fedfb271](https://linux-hardware.org/?probe=f4fedfb271) | Aug 14, 2022 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [7dab66307c](https://linux-hardware.org/?probe=7dab66307c) | Aug 09, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [c57b484523](https://linux-hardware.org/?probe=c57b484523) | Aug 07, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [672cb969fb](https://linux-hardware.org/?probe=672cb969fb) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [edfabf845b](https://linux-hardware.org/?probe=edfabf845b) | Jul 22, 2022 |
| Lenovo        | ThinkPad E14 20RA000KFE     | Notebook    | [7193e153ff](https://linux-hardware.org/?probe=7193e153ff) | Jul 20, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Packard Be... | EasyNote ML65               | Notebook    | [c8c6125dc3](https://linux-hardware.org/?probe=c8c6125dc3) | Jul 06, 2022 |
| Packard Be... | EasyNote ML65               | Notebook    | [09d1580fd5](https://linux-hardware.org/?probe=09d1580fd5) | Jul 06, 2022 |
| Dell          | Inspiron N5040              | Notebook    | [2459fb8d6e](https://linux-hardware.org/?probe=2459fb8d6e) | Jul 03, 2022 |
| Dell          | Inspiron N5040              | Notebook    | [81e318d1d5](https://linux-hardware.org/?probe=81e318d1d5) | Jul 03, 2022 |
| Lenovo        | 36C5 NOK                    | Desktop     | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | Desktop     | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| HP            | ProBook 455 G3              | Notebook    | [bac60198a3](https://linux-hardware.org/?probe=bac60198a3) | Jun 10, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [2218dd9966](https://linux-hardware.org/?probe=2218dd9966) | Jun 07, 2022 |
| Dell          | 05842Y A00                  | Desktop     | [7c67079823](https://linux-hardware.org/?probe=7c67079823) | May 19, 2022 |
| ASUSTek       | X556UV                      | Notebook    | [39b927dfdc](https://linux-hardware.org/?probe=39b927dfdc) | May 11, 2022 |
| Dell          | Latitude 3540               | Notebook    | [a97573f3cf](https://linux-hardware.org/?probe=a97573f3cf) | Apr 29, 2022 |
| Dell          | Latitude 3540               | Notebook    | [a6b8509194](https://linux-hardware.org/?probe=a6b8509194) | Apr 29, 2022 |
| Toshiba       | Satellite Pro L850-B339     | Notebook    | [d884eeae8f](https://linux-hardware.org/?probe=d884eeae8f) | Apr 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [af0e50e873](https://linux-hardware.org/?probe=af0e50e873) | Apr 14, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [9597b0a2d9](https://linux-hardware.org/?probe=9597b0a2d9) | Apr 09, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [03b34db583](https://linux-hardware.org/?probe=03b34db583) | Apr 05, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [e7a152d30a](https://linux-hardware.org/?probe=e7a152d30a) | Apr 04, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [30ed5cb046](https://linux-hardware.org/?probe=30ed5cb046) | Apr 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7c0d1ce382](https://linux-hardware.org/?probe=7c0d1ce382) | Mar 29, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [bc07a3de3d](https://linux-hardware.org/?probe=bc07a3de3d) | Mar 15, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [ddbc85ab3a](https://linux-hardware.org/?probe=ddbc85ab3a) | Mar 15, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [4b2b4e7f5a](https://linux-hardware.org/?probe=4b2b4e7f5a) | Mar 10, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [267fa2ca76](https://linux-hardware.org/?probe=267fa2ca76) | Mar 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [7803f9b898](https://linux-hardware.org/?probe=7803f9b898) | Feb 24, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [020df21e37](https://linux-hardware.org/?probe=020df21e37) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [49a3015875](https://linux-hardware.org/?probe=49a3015875) | Feb 10, 2022 |
| Intel         | H61                         | Desktop     | [6d80839afa](https://linux-hardware.org/?probe=6d80839afa) | Feb 09, 2022 |
| HP            | Pavilion dv7                | Notebook    | [3bd981aa35](https://linux-hardware.org/?probe=3bd981aa35) | Feb 09, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEP... | Notebook    | [f814537586](https://linux-hardware.org/?probe=f814537586) | Feb 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [09caab8240](https://linux-hardware.org/?probe=09caab8240) | Feb 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [75acdd40a6](https://linux-hardware.org/?probe=75acdd40a6) | Feb 07, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [06f3844911](https://linux-hardware.org/?probe=06f3844911) | Jan 30, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [0665a1599c](https://linux-hardware.org/?probe=0665a1599c) | Jan 26, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [22dd608151](https://linux-hardware.org/?probe=22dd608151) | Jan 07, 2022 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [391458138f](https://linux-hardware.org/?probe=391458138f) | Jan 07, 2022 |
| HP            | EliteBook 8740w             | Notebook    | [6f583dfeaf](https://linux-hardware.org/?probe=6f583dfeaf) | Dec 27, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [45a5de08c7](https://linux-hardware.org/?probe=45a5de08c7) | Dec 25, 2021 |
| HP            | Notebook                    | Notebook    | [032be84586](https://linux-hardware.org/?probe=032be84586) | Dec 09, 2021 |
| Toshiba       | Satellite C50-A489          | Notebook    | [4d29ea3b9c](https://linux-hardware.org/?probe=4d29ea3b9c) | Dec 04, 2021 |
| Lenovo        | ThinkPad X240 20AMA0WRFR    | Notebook    | [13fe3346fd](https://linux-hardware.org/?probe=13fe3346fd) | Dec 02, 2021 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [e6fd06720f](https://linux-hardware.org/?probe=e6fd06720f) | Nov 28, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [d0a08a7a23](https://linux-hardware.org/?probe=d0a08a7a23) | Nov 22, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [507c380abb](https://linux-hardware.org/?probe=507c380abb) | Nov 22, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [d49eff3d64](https://linux-hardware.org/?probe=d49eff3d64) | Nov 21, 2021 |
| Lenovo        | ThinkPad E15 20RD001SFE     | Notebook    | [358e3547b9](https://linux-hardware.org/?probe=358e3547b9) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD001SFE     | Notebook    | [694f05492e](https://linux-hardware.org/?probe=694f05492e) | Nov 17, 2021 |
| HP            | Compaq 6735s                | Notebook    | [6571a6fe6d](https://linux-hardware.org/?probe=6571a6fe6d) | Nov 15, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | Notebook    | [4bc0687791](https://linux-hardware.org/?probe=4bc0687791) | Nov 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [dcd2956978](https://linux-hardware.org/?probe=dcd2956978) | Nov 05, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a509e62c95](https://linux-hardware.org/?probe=a509e62c95) | Nov 05, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [60e3fe1197](https://linux-hardware.org/?probe=60e3fe1197) | Oct 26, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | Notebook    | [8f6efb8dbe](https://linux-hardware.org/?probe=8f6efb8dbe) | Oct 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9b0872b3d4](https://linux-hardware.org/?probe=9b0872b3d4) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [9b74440deb](https://linux-hardware.org/?probe=9b74440deb) | Oct 07, 2021 |
| Acer          | Swift SF514-53T             | Notebook    | [e97a52d3d9](https://linux-hardware.org/?probe=e97a52d3d9) | Sep 28, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b882e1c0f7](https://linux-hardware.org/?probe=b882e1c0f7) | Sep 22, 2021 |
| HP            | 1494                        | Desktop     | [ae5165603a](https://linux-hardware.org/?probe=ae5165603a) | Sep 09, 2021 |
| HP            | 1494                        | Desktop     | [62e74e0c1a](https://linux-hardware.org/?probe=62e74e0c1a) | Sep 09, 2021 |
| HP            | 250 G4                      | Notebook    | [b5177b1c13](https://linux-hardware.org/?probe=b5177b1c13) | Sep 08, 2021 |
| HP            | 250 G4                      | Notebook    | [32899cab30](https://linux-hardware.org/?probe=32899cab30) | Sep 08, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e57d0a5518](https://linux-hardware.org/?probe=e57d0a5518) | Sep 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d4cdb976c2](https://linux-hardware.org/?probe=d4cdb976c2) | Aug 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [633e5a9649](https://linux-hardware.org/?probe=633e5a9649) | Aug 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6339cd2e5b](https://linux-hardware.org/?probe=6339cd2e5b) | Aug 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [58fb87de66](https://linux-hardware.org/?probe=58fb87de66) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8d891b7431](https://linux-hardware.org/?probe=8d891b7431) | Aug 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [726ed18d47](https://linux-hardware.org/?probe=726ed18d47) | Jul 25, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | Notebook    | [a347415235](https://linux-hardware.org/?probe=a347415235) | Jul 19, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [236639a923](https://linux-hardware.org/?probe=236639a923) | Jul 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [98862925dc](https://linux-hardware.org/?probe=98862925dc) | Jul 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6ce3d213a](https://linux-hardware.org/?probe=b6ce3d213a) | Jul 06, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [af8d7a6b6f](https://linux-hardware.org/?probe=af8d7a6b6f) | Jun 22, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [77faf70869](https://linux-hardware.org/?probe=77faf70869) | Jun 14, 2021 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [8488c59a11](https://linux-hardware.org/?probe=8488c59a11) | May 18, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [9a767f85c2](https://linux-hardware.org/?probe=9a767f85c2) | May 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [fe125a0b5f](https://linux-hardware.org/?probe=fe125a0b5f) | May 10, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [89cfbb6a0e](https://linux-hardware.org/?probe=89cfbb6a0e) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [884b3d6f69](https://linux-hardware.org/?probe=884b3d6f69) | Apr 21, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [50e1fa29fb](https://linux-hardware.org/?probe=50e1fa29fb) | Apr 16, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [be7a218721](https://linux-hardware.org/?probe=be7a218721) | Apr 12, 2021 |
| Dell          | Latitude E6420              | Notebook    | [901b94b26d](https://linux-hardware.org/?probe=901b94b26d) | Mar 10, 2021 |
| Dell          | Latitude E6420              | Notebook    | [c0d9f82152](https://linux-hardware.org/?probe=c0d9f82152) | Mar 10, 2021 |
| Dell          | Latitude E5440              | Notebook    | [89089cf0ad](https://linux-hardware.org/?probe=89089cf0ad) | Mar 05, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [347d45179a](https://linux-hardware.org/?probe=347d45179a) | Jan 30, 2021 |
| Acer          | Aspire V5-561G              | Notebook    | [4829da6130](https://linux-hardware.org/?probe=4829da6130) | Jan 30, 2021 |
| Dell          | Latitude 7410               | Notebook    | [19e75431d4](https://linux-hardware.org/?probe=19e75431d4) | Jan 30, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [07f0354547](https://linux-hardware.org/?probe=07f0354547) | Jan 29, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [5b18be0dd0](https://linux-hardware.org/?probe=5b18be0dd0) | Jan 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [cb1f74adbd](https://linux-hardware.org/?probe=cb1f74adbd) | Jan 17, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [f4c57eb290](https://linux-hardware.org/?probe=f4c57eb290) | Jan 17, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [95610ff17c](https://linux-hardware.org/?probe=95610ff17c) | Jan 14, 2021 |
| Dell          | Inspiron 3520               | Notebook    | [c1e7a232e0](https://linux-hardware.org/?probe=c1e7a232e0) | Dec 29, 2020 |
| eMachines     | E725                        | Notebook    | [aa660241b3](https://linux-hardware.org/?probe=aa660241b3) | Dec 22, 2020 |
| Dell          | Latitude 7490               | Notebook    | [d42995d26a](https://linux-hardware.org/?probe=d42995d26a) | Dec 21, 2020 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [f52e267cc9](https://linux-hardware.org/?probe=f52e267cc9) | Dec 19, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [e4ab77e8b0](https://linux-hardware.org/?probe=e4ab77e8b0) | Dec 11, 2020 |
| Lenovo        | ThinkPad E15 20RD001QFE     | Notebook    | [d02175d76c](https://linux-hardware.org/?probe=d02175d76c) | Dec 10, 2020 |
| ASUSTek       | UX310UQK                    | Notebook    | [bb566782bc](https://linux-hardware.org/?probe=bb566782bc) | Dec 04, 2020 |
| HP            | Convertible x360 11-ab0X... | Convertible | [6b543e87f8](https://linux-hardware.org/?probe=6b543e87f8) | Nov 26, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [963065205e](https://linux-hardware.org/?probe=963065205e) | Nov 26, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [c1aeee5a95](https://linux-hardware.org/?probe=c1aeee5a95) | Nov 26, 2020 |
| ASUSTek       | X550VX                      | Notebook    | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [563be9ddd8](https://linux-hardware.org/?probe=563be9ddd8) | Nov 21, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [59de1f8260](https://linux-hardware.org/?probe=59de1f8260) | Nov 20, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [64cce3acaa](https://linux-hardware.org/?probe=64cce3acaa) | Nov 04, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [97dee881c4](https://linux-hardware.org/?probe=97dee881c4) | Nov 01, 2020 |
| Dell          | 0TTDMJ A00                  | Desktop     | [aef24f2346](https://linux-hardware.org/?probe=aef24f2346) | Oct 28, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [a236e15c5d](https://linux-hardware.org/?probe=a236e15c5d) | Oct 25, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [f81c8f31d1](https://linux-hardware.org/?probe=f81c8f31d1) | Oct 10, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [bb4464e5f1](https://linux-hardware.org/?probe=bb4464e5f1) | Oct 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [7bf6a7c3a4](https://linux-hardware.org/?probe=7bf6a7c3a4) | Sep 16, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [cdce66a7de](https://linux-hardware.org/?probe=cdce66a7de) | Jul 07, 2020 |
| ASUSTek       | UX360CA                     | Notebook    | [9d6a79d7ac](https://linux-hardware.org/?probe=9d6a79d7ac) | Jun 11, 2020 |
| ASUSTek       | UX360CA                     | Notebook    | [24742e9ec9](https://linux-hardware.org/?probe=24742e9ec9) | Jun 11, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [1cb682ea0f](https://linux-hardware.org/?probe=1cb682ea0f) | Jun 06, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [65d6dca78e](https://linux-hardware.org/?probe=65d6dca78e) | May 27, 2020 |
| Toshiba       | Satellite L550              | Notebook    | [31501ab61b](https://linux-hardware.org/?probe=31501ab61b) | May 11, 2020 |
| Toshiba       | Satellite L550              | Notebook    | [b8e2396d82](https://linux-hardware.org/?probe=b8e2396d82) | May 11, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4ff939d0e2](https://linux-hardware.org/?probe=4ff939d0e2) | Apr 28, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [31b3c13f93](https://linux-hardware.org/?probe=31b3c13f93) | Apr 28, 2020 |
| Toshiba       | Satellite L550              | Notebook    | [73f10216d6](https://linux-hardware.org/?probe=73f10216d6) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [b5721fa9d5](https://linux-hardware.org/?probe=b5721fa9d5) | Apr 22, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [b391bbea48](https://linux-hardware.org/?probe=b391bbea48) | Apr 12, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [30a8d59bdc](https://linux-hardware.org/?probe=30a8d59bdc) | Apr 09, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [fc6eaad779](https://linux-hardware.org/?probe=fc6eaad779) | Apr 09, 2020 |
| ASUSTek       | X556UV                      | Notebook    | [cb5da8627a](https://linux-hardware.org/?probe=cb5da8627a) | Apr 07, 2020 |
| MSI           | MS-7502 Fab D               | Desktop     | [242c5b8d0d](https://linux-hardware.org/?probe=242c5b8d0d) | Mar 30, 2020 |
| ASUSTek       | X550JX                      | Notebook    | [71dbec47eb](https://linux-hardware.org/?probe=71dbec47eb) | Mar 27, 2020 |
| ASUSTek       | X550JX                      | Notebook    | [cc439d9e0f](https://linux-hardware.org/?probe=cc439d9e0f) | Mar 27, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [cb7137a57a](https://linux-hardware.org/?probe=cb7137a57a) | Mar 16, 2020 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [64628c8c11](https://linux-hardware.org/?probe=64628c8c11) | Mar 12, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [7c6e2d2c29](https://linux-hardware.org/?probe=7c6e2d2c29) | Mar 10, 2020 |
| Pegatron      | Eureka3                     | Desktop     | [77bc52c3d9](https://linux-hardware.org/?probe=77bc52c3d9) | Mar 02, 2020 |
| Pegatron      | Eureka3                     | Desktop     | [84ee26b4e7](https://linux-hardware.org/?probe=84ee26b4e7) | Mar 02, 2020 |
| Pegatron      | Eureka3                     | Desktop     | [33ae5ebabc](https://linux-hardware.org/?probe=33ae5ebabc) | Feb 18, 2020 |
| ASUSTek       | X550JX                      | Notebook    | [a1fa3183ed](https://linux-hardware.org/?probe=a1fa3183ed) | Feb 15, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [97b5418b6d](https://linux-hardware.org/?probe=97b5418b6d) | Feb 03, 2020 |
| Lenovo        | ThinkPad T440s 20AQ005NU... | Notebook    | [55d9286a1b](https://linux-hardware.org/?probe=55d9286a1b) | Jan 27, 2020 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [7878eb9e27](https://linux-hardware.org/?probe=7878eb9e27) | Dec 30, 2019 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [21f916c3ef](https://linux-hardware.org/?probe=21f916c3ef) | Dec 30, 2019 |
| Acer          | Aspire E1-570               | Notebook    | [9d92944e6c](https://linux-hardware.org/?probe=9d92944e6c) | Dec 21, 2019 |
| Acer          | Aspire E1-570               | Notebook    | [64702aadcd](https://linux-hardware.org/?probe=64702aadcd) | Dec 21, 2019 |
| Lenovo        | Unknown                     | Notebook    | [10ab399874](https://linux-hardware.org/?probe=10ab399874) | Dec 14, 2019 |
| Sony          | VPCEH36EF                   | Notebook    | [5b1adbe8f0](https://linux-hardware.org/?probe=5b1adbe8f0) | Dec 10, 2019 |
| Sony          | VPCEH36EF                   | Notebook    | [6518790628](https://linux-hardware.org/?probe=6518790628) | Nov 27, 2019 |
| Dell          | Latitude E6420              | Notebook    | [3f252a50fb](https://linux-hardware.org/?probe=3f252a50fb) | Nov 12, 2019 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [1b5ae66e6f](https://linux-hardware.org/?probe=1b5ae66e6f) | Nov 10, 2019 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [a9cc2a8ea0](https://linux-hardware.org/?probe=a9cc2a8ea0) | Nov 01, 2019 |
| Unknown       | Pine Trail - M CRB          | Desktop     | [ef1e6295a8](https://linux-hardware.org/?probe=ef1e6295a8) | Oct 30, 2019 |
| Foxconn       | 2ABF                        | Desktop     | [4521f814c9](https://linux-hardware.org/?probe=4521f814c9) | Sep 17, 2019 |
| Foxconn       | 2ABF                        | Desktop     | [6a57b2ea85](https://linux-hardware.org/?probe=6a57b2ea85) | Sep 17, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [b57e5735a5](https://linux-hardware.org/?probe=b57e5735a5) | Sep 13, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [708bc2c339](https://linux-hardware.org/?probe=708bc2c339) | Sep 13, 2019 |
| HP            | 630                         | Notebook    | [8cb4c328bb](https://linux-hardware.org/?probe=8cb4c328bb) | Sep 10, 2019 |
| Acer          | Aspire V5-572G              | Notebook    | [7d046c01d0](https://linux-hardware.org/?probe=7d046c01d0) | Sep 07, 2019 |
| HP            | Pavilion g6                 | Notebook    | [6eebb27f65](https://linux-hardware.org/?probe=6eebb27f65) | Aug 28, 2019 |
| HP            | Laptop                      | Notebook    | [de71114421](https://linux-hardware.org/?probe=de71114421) | Aug 21, 2019 |
| Acer          | Aspire V5-572G              | Notebook    | [90d2c432d6](https://linux-hardware.org/?probe=90d2c432d6) | Aug 17, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [26b5185afb](https://linux-hardware.org/?probe=26b5185afb) | Aug 14, 2019 |
| Pegatron      | 2A94h                       | Desktop     | [3b6656bb11](https://linux-hardware.org/?probe=3b6656bb11) | Jul 04, 2019 |
| Acer          | TravelMate P259-M           | Notebook    | [3693d52bff](https://linux-hardware.org/?probe=3693d52bff) | Nov 09, 2018 |
| Acer          | TravelMate P259-M           | Notebook    | [a951fd5ef9](https://linux-hardware.org/?probe=a951fd5ef9) | Nov 09, 2018 |
| HP            | Laptop 17-ak0xx             | Notebook    | [83d0682234](https://linux-hardware.org/?probe=83d0682234) | Sep 20, 2018 |
| HP            | Laptop 17-ak0xx             | Notebook    | [e2076e8303](https://linux-hardware.org/?probe=e2076e8303) | Sep 19, 2018 |
| HP            | Laptop 17-ak0xx             | Notebook    | [24599e9990](https://linux-hardware.org/?probe=24599e9990) | Sep 19, 2018 |
| HP            | Pavilion g6                 | Notebook    | [c93294c4ab](https://linux-hardware.org/?probe=c93294c4ab) | Sep 18, 2018 |
| HP            | Pavilion g6                 | Notebook    | [efc4afba58](https://linux-hardware.org/?probe=efc4afba58) | Aug 10, 2018 |
| HP            | Pavilion g6                 | Notebook    | [494e0c0416](https://linux-hardware.org/?probe=494e0c0416) | Aug 10, 2018 |
| Foxconn       | 2ABF                        | Desktop     | [f6873739a8](https://linux-hardware.org/?probe=f6873739a8) | Mar 03, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 44        | 15.83%  |
| Ubuntu 22.04        | 26        | 9.35%   |
| Ubuntu 18.04        | 17        | 6.12%   |
| Debian 12           | 7         | 2.52%   |
| Ubuntu 24.04        | 6         | 2.16%   |
| Ubuntu 21.10        | 6         | 2.16%   |
| OpenMandriva 4.2    | 6         | 2.16%   |
| OpenMandriva 23.08  | 6         | 2.16%   |
| Pop!_OS 22.04       | 5         | 1.8%    |
| Linux Mint 21.2     | 5         | 1.8%    |
| KDE neon 22.04      | 5         | 1.8%    |
| ArcoLinux Rolling   | 5         | 1.8%    |
| Arch Rolling        | 5         | 1.8%    |
| OpenMandriva 4.3    | 4         | 1.44%   |
| OpenMandriva 23.03  | 4         | 1.44%   |
| Fedora 38           | 4         | 1.44%   |
| Debian 11           | 4         | 1.44%   |
| Zorin 16            | 3         | 1.08%   |
| Zorin 15            | 3         | 1.08%   |
| Ubuntu 19.10        | 3         | 1.08%   |
| Ubuntu 16.04        | 3         | 1.08%   |
| Linux Mint 21.1     | 3         | 1.08%   |
| KDE neon 20.04      | 3         | 1.08%   |
| Fedora 41           | 3         | 1.08%   |
| Fedora 40           | 3         | 1.08%   |
| EndeavourOS Rolling | 3         | 1.08%   |
| Debian 10           | 3         | 1.08%   |
| Zorin 17            | 2         | 0.72%   |
| Ubuntu 21.04        | 2         | 0.72%   |
| Ubuntu 20.10        | 2         | 0.72%   |
| ROSA R10            | 2         | 0.72%   |
| ROSA 12.3           | 2         | 0.72%   |
| Pop!_OS 21.04       | 2         | 0.72%   |
| OpenMandriva 23.07  | 2         | 0.72%   |
| NixOS 24.05         | 2         | 0.72%   |
| Manjaro 21.1.0      | 2         | 0.72%   |
| LMDE 4              | 2         | 0.72%   |
| Linux Mint 21.3     | 2         | 0.72%   |
| Linux Mint 21       | 2         | 0.72%   |
| Linux Mint 20.3     | 2         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 103       | 38.72%  |
| OpenMandriva | 24        | 9.02%   |
| Linux Mint   | 20        | 7.52%   |
| Fedora       | 15        | 5.64%   |
| Debian       | 15        | 5.64%   |
| Zorin        | 8         | 3.01%   |
| Pop!_OS      | 8         | 3.01%   |
| Arch         | 7         | 2.63%   |
| ROSA         | 6         | 2.26%   |
| Manjaro      | 6         | 2.26%   |
| KDE neon     | 6         | 2.26%   |
| Endless      | 5         | 1.88%   |
| ArcoLinux    | 5         | 1.88%   |
| Kali         | 4         | 1.5%    |
| LMDE         | 3         | 1.13%   |
| Gentoo       | 3         | 1.13%   |
| EndeavourOS  | 3         | 1.13%   |
| Xubuntu      | 2         | 0.75%   |
| NixOS        | 2         | 0.75%   |
| Lubuntu      | 2         | 0.75%   |
| Elementary   | 2         | 0.75%   |
| Bazzite      | 2         | 0.75%   |
| Xero         | 1         | 0.38%   |
| Ubuntu Unity | 1         | 0.38%   |
| TUXEDO OS    | 1         | 0.38%   |
| SteamOS      | 1         | 0.38%   |
| Sodalite     | 1         | 0.38%   |
| Parrot       | 1         | 0.38%   |
| Nobara       | 1         | 0.38%   |
| MX           | 1         | 0.38%   |
| Kubuntu      | 1         | 0.38%   |
| Garuda Linux | 1         | 0.38%   |
| Devuan       | 1         | 0.38%   |
| Deepin       | 1         | 0.38%   |
| CachyOS      | 1         | 0.38%   |
| BlackPanther | 1         | 0.38%   |
| Archcraft    | 1         | 0.38%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.4.11-desktop-1omv2390  | 6         | 1.95%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.95%   |
| 5.15.0-58-generic        | 5         | 1.63%   |
| 6.2.6-desktop-1omv2390   | 4         | 1.3%    |
| 5.16.7-desktop-1omv4003  | 4         | 1.3%    |
| 5.15.0-52-generic        | 4         | 1.3%    |
| 5.15.0-46-generic        | 4         | 1.3%    |
| 5.13.0-28-generic        | 4         | 1.3%    |
| 6.8.0-49-generic         | 3         | 0.98%   |
| 6.2.0-36-generic         | 3         | 0.98%   |
| 5.3.0-46-generic         | 3         | 0.98%   |
| 5.3.0-40-generic         | 3         | 0.98%   |
| 5.15.0-56-generic        | 3         | 0.98%   |
| 5.15.0-53-generic        | 3         | 0.98%   |
| 5.15.0-43-generic        | 3         | 0.98%   |
| 5.11.0-38-generic        | 3         | 0.98%   |
| 5.11.0-27-generic        | 3         | 0.98%   |
| 6.8.0-51-generic         | 2         | 0.65%   |
| 6.8.0-48-generic         | 2         | 0.65%   |
| 6.8.0-40-generic         | 2         | 0.65%   |
| 6.5.0-35-generic         | 2         | 0.65%   |
| 6.3.5-desktop-3omv2390   | 2         | 0.65%   |
| 6.1.0-28-amd64           | 2         | 0.65%   |
| 5.8.0-38-generic         | 2         | 0.65%   |
| 5.8.0-14-generic         | 2         | 0.65%   |
| 5.4.0-72-generic         | 2         | 0.65%   |
| 5.4.0-58-generic         | 2         | 0.65%   |
| 5.4.0-52-generic         | 2         | 0.65%   |
| 5.4.0-42-generic         | 2         | 0.65%   |
| 5.4.0-26-generic         | 2         | 0.65%   |
| 5.3.0-28-generic         | 2         | 0.65%   |
| 5.19.0-45-generic        | 2         | 0.65%   |
| 5.15.84-v8+              | 2         | 0.65%   |
| 5.15.0-47-generic        | 2         | 0.65%   |
| 5.15.0-41-generic        | 2         | 0.65%   |
| 5.15.0-107-generic       | 2         | 0.65%   |
| 5.13.0-44-generic        | 2         | 0.65%   |
| 5.13.0-40-generic        | 2         | 0.65%   |
| 5.13.0-39-generic        | 2         | 0.65%   |
| 5.11.0-7620-generic      | 2         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 37        | 12.8%   |
| 5.4.0   | 26        | 9%      |
| 5.13.0  | 16        | 5.54%   |
| 5.11.0  | 13        | 4.5%    |
| 6.8.0   | 11        | 3.81%   |
| 5.8.0   | 11        | 3.81%   |
| 5.3.0   | 11        | 3.81%   |
| 4.15.0  | 10        | 3.46%   |
| 6.5.0   | 9         | 3.11%   |
| 5.19.0  | 9         | 3.11%   |
| 6.1.0   | 7         | 2.42%   |
| 5.0.0   | 7         | 2.42%   |
| 6.4.11  | 6         | 2.08%   |
| 5.10.14 | 6         | 2.08%   |
| 6.2.0   | 5         | 1.73%   |
| 4.19.0  | 5         | 1.73%   |
| 6.2.6   | 4         | 1.38%   |
| 5.16.7  | 4         | 1.38%   |
| 5.10.0  | 4         | 1.38%   |
| 6.3.5   | 3         | 1.04%   |
| 4.18.0  | 3         | 1.04%   |
| 6.9.1   | 2         | 0.69%   |
| 6.5.7   | 2         | 0.69%   |
| 6.3.6   | 2         | 0.69%   |
| 5.18.0  | 2         | 0.69%   |
| 5.17.5  | 2         | 0.69%   |
| 5.15.84 | 2         | 0.69%   |
| 5.15.75 | 2         | 0.69%   |
| 5.10.27 | 2         | 0.69%   |
| 4.9.60  | 2         | 0.69%   |
| 6.9.9   | 1         | 0.35%   |
| 6.9.7   | 1         | 0.35%   |
| 6.9.6   | 1         | 0.35%   |
| 6.9.5   | 1         | 0.35%   |
| 6.9.3   | 1         | 0.35%   |
| 6.9.12  | 1         | 0.35%   |
| 6.8.9   | 1         | 0.35%   |
| 6.8.6   | 1         | 0.35%   |
| 6.8.4   | 1         | 0.35%   |
| 6.8.2   | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 45        | 15.96%  |
| 5.4     | 28        | 9.93%   |
| 5.13    | 17        | 6.03%   |
| 6.8     | 15        | 5.32%   |
| 5.11    | 15        | 5.32%   |
| 5.10    | 14        | 4.96%   |
| 6.5     | 13        | 4.61%   |
| 6.2     | 12        | 4.26%   |
| 5.8     | 12        | 4.26%   |
| 5.3     | 12        | 4.26%   |
| 6.1     | 10        | 3.55%   |
| 5.19    | 10        | 3.55%   |
| 4.15    | 10        | 3.55%   |
| 6.9     | 8         | 2.84%   |
| 6.6     | 7         | 2.48%   |
| 6.4     | 7         | 2.48%   |
| 5.0     | 7         | 2.48%   |
| 5.16    | 6         | 2.13%   |
| 6.3     | 5         | 1.77%   |
| 4.19    | 5         | 1.77%   |
| 6.11    | 4         | 1.42%   |
| 5.17    | 3         | 1.06%   |
| 4.9     | 3         | 1.06%   |
| 4.18    | 3         | 1.06%   |
| 5.9     | 2         | 0.71%   |
| 5.18    | 2         | 0.71%   |
| 6.12    | 1         | 0.35%   |
| 5.6     | 1         | 0.35%   |
| 5.5     | 1         | 0.35%   |
| 5.14    | 1         | 0.35%   |
| 5.12    | 1         | 0.35%   |
| 4.4     | 1         | 0.35%   |
| 3.13    | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 250       | 97.28%  |
| i686    | 4         | 1.56%   |
| aarch64 | 3         | 1.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 138       | 51.49%  |
| KDE5             | 45        | 16.79%  |
| X-Cinnamon       | 20        | 7.46%   |
| Unknown          | 20        | 7.46%   |
| XFCE             | 11        | 4.1%    |
| KDE6             | 10        | 3.73%   |
| KDE4             | 4         | 1.49%   |
| Pantheon         | 3         | 1.12%   |
| MATE             | 3         | 1.12%   |
| GNOME Flashback  | 2         | 0.75%   |
| Unity            | 1         | 0.37%   |
| Trinity          | 1         | 0.37%   |
| qtile            | 1         | 0.37%   |
| LXQt             | 1         | 0.37%   |
| LXDE             | 1         | 0.37%   |
| lightdm-xsession | 1         | 0.37%   |
| i3               | 1         | 0.37%   |
| GNOME Classic    | 1         | 0.37%   |
| Endless:GNOME    | 1         | 0.37%   |
| DWM              | 1         | 0.37%   |
| Deepin           | 1         | 0.37%   |
| Cinnamon         | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 183       | 68.8%   |
| Wayland | 72        | 27.07%  |
| Tty     | 6         | 2.26%   |
| Unknown | 5         | 1.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 98        | 36.84%  |
| GDM     | 52        | 19.55%  |
| SDDM    | 47        | 17.67%  |
| GDM3    | 42        | 15.79%  |
| LightDM | 23        | 8.65%   |
| KDM     | 4         | 1.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 127       | 48.66%  |
| fr_FR   | 79        | 30.27%  |
| Unknown | 19        | 7.28%   |
| en_GB   | 13        | 4.98%   |
| C       | 7         | 2.68%   |
| de_DE   | 3         | 1.15%   |
| pt_BR   | 2         | 0.77%   |
| it_IT   | 2         | 0.77%   |
| ar_TN   | 2         | 0.77%   |
| ru_UA   | 1         | 0.38%   |
| fr_CA   | 1         | 0.38%   |
| en_IN   | 1         | 0.38%   |
| en_IE   | 1         | 0.38%   |
| en_CA   | 1         | 0.38%   |
| en_AU   | 1         | 0.38%   |
| en_AG   | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 140       | 53.03%  |
| BIOS | 124       | 46.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 203       | 78.38%  |
| Btrfs   | 22        | 8.49%   |
| Overlay | 16        | 6.18%   |
| Tmpfs   | 11        | 4.25%   |
| Unknown | 6         | 2.32%   |
| Xfs     | 1         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 114       | 43.35%  |
| Unknown | 106       | 40.3%   |
| MBR     | 43        | 16.35%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 225       | 86.21%  |
| Yes       | 36        | 13.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 169       | 65.25%  |
| Yes       | 90        | 34.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 58        | 22.66%  |
| ASUSTek Computer        | 48        | 18.75%  |
| Dell                    | 41        | 16.02%  |
| Hewlett-Packard         | 40        | 15.63%  |
| MSI                     | 16        | 6.25%   |
| Acer                    | 16        | 6.25%   |
| Toshiba                 | 8         | 3.13%   |
| Pegatron                | 4         | 1.56%   |
| Samsung Electronics     | 3         | 1.17%   |
| Intel                   | 3         | 1.17%   |
| Sony                    | 2         | 0.78%   |
| Raspberry Pi Foundation | 2         | 0.78%   |
| Foxconn                 | 2         | 0.78%   |
| ASRock                  | 2         | 0.78%   |
| Unknown                 | 2         | 0.78%   |
| Valve                   | 1         | 0.39%   |
| SCHNEIDER               | 1         | 0.39%   |
| Packard Bell            | 1         | 0.39%   |
| LORD ELECTRONICS        | 1         | 0.39%   |
| Gigabyte Technology     | 1         | 0.39%   |
| eMachines               | 1         | 0.39%   |
| ECS                     | 1         | 0.39%   |
| AZW                     | 1         | 0.39%   |
| Apple                   | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| HP Pavilion g6                          | 6         | 2.34%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK   | 4         | 1.56%   |
| Lenovo IdeaPad 3 15ADA05 81W1           | 3         | 1.17%   |
| Dell Inspiron 5570                      | 3         | 1.17%   |
| Dell Inspiron 3543                      | 3         | 1.17%   |
| Unknown                                 | 3         | 1.17%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 2         | 0.78%   |
| Pegatron VS342AA-AB6 m9801af            | 2         | 0.78%   |
| MSI GF63 Thin 10SCXR                    | 2         | 0.78%   |
| Lenovo IdeaPad 700-15ISK 80RU           | 2         | 0.78%   |
| Lenovo IdeaPad 5 15ITL05 82FG           | 2         | 0.78%   |
| Lenovo IdeaPad 3 15IGL05 81WQ           | 2         | 0.78%   |
| Lenovo IdeaPad 130-15IKB 81H7           | 2         | 0.78%   |
| Lenovo G50-70 20351                     | 2         | 0.78%   |
| Intel H81                               | 2         | 0.78%   |
| HP Pavilion Gaming Laptop 15-ec1xxx     | 2         | 0.78%   |
| HP Pavilion dv7                         | 2         | 0.78%   |
| HP Notebook                             | 2         | 0.78%   |
| HP EliteBook 2560p                      | 2         | 0.78%   |
| Foxconn Pro 3400 Series MT              | 2         | 0.78%   |
| Dell Vostro 1015                        | 2         | 0.78%   |
| Dell Inspiron N5110                     | 2         | 0.78%   |
| Dell Inspiron 3521                      | 2         | 0.78%   |
| ASUS X556UV                             | 2         | 0.78%   |
| ASUS X553MA                             | 2         | 0.78%   |
| ASUS X550LC                             | 2         | 0.78%   |
| ASUS X550JX                             | 2         | 0.78%   |
| Acer Aspire E5-571G                     | 2         | 0.78%   |
| Valve Jupiter                           | 1         | 0.39%   |
| Toshiba Satellite Pro L850-B339         | 1         | 0.39%   |
| Toshiba Satellite L550                  | 1         | 0.39%   |
| Toshiba Satellite L500                  | 1         | 0.39%   |
| Toshiba Satellite C855-1KF              | 1         | 0.39%   |
| Toshiba Satellite C650D                 | 1         | 0.39%   |
| Toshiba Satellite C55-C                 | 1         | 0.39%   |
| Toshiba Satellite C50-A489              | 1         | 0.39%   |
| Toshiba Satellite A300                  | 1         | 0.39%   |
| Sony VPCEH36EF                          | 1         | 0.39%   |
| Sony VGN-CR407E                         | 1         | 0.39%   |
| SCHNEIDER SCL142ALM                     | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo IdeaPad       | 29        | 11.33%  |
| Dell Inspiron        | 17        | 6.64%   |
| HP Pavilion          | 14        | 5.47%   |
| Lenovo ThinkPad      | 12        | 4.69%   |
| Acer Aspire          | 11        | 4.3%    |
| Dell Latitude        | 9         | 3.52%   |
| Toshiba Satellite    | 8         | 3.13%   |
| Dell OptiPlex        | 7         | 2.73%   |
| HP ProBook           | 5         | 1.95%   |
| HP Laptop            | 5         | 1.95%   |
| Dell Vostro          | 5         | 1.95%   |
| ASUS VivoBook        | 5         | 1.95%   |
| ASUS PRIME           | 5         | 1.95%   |
| ASUS ASUS            | 5         | 1.95%   |
| HP EliteBook         | 4         | 1.56%   |
| ASUS TUF             | 4         | 1.56%   |
| MSI Katana           | 3         | 1.17%   |
| MSI GF63             | 3         | 1.17%   |
| ASUS ROG             | 3         | 1.17%   |
| Unknown              | 3         | 1.17%   |
| Samsung 300E5EV      | 2         | 0.78%   |
| RPi Raspberry        | 2         | 0.78%   |
| Pegatron VS342AA-AB6 | 2         | 0.78%   |
| Lenovo ThinkBook     | 2         | 0.78%   |
| Lenovo G50-70        | 2         | 0.78%   |
| Intel H81            | 2         | 0.78%   |
| HP Notebook          | 2         | 0.78%   |
| HP Compaq            | 2         | 0.78%   |
| HP 250               | 2         | 0.78%   |
| Foxconn Pro          | 2         | 0.78%   |
| Dell G15             | 2         | 0.78%   |
| ASUS ZenBook         | 2         | 0.78%   |
| ASUS X556UV          | 2         | 0.78%   |
| ASUS X553MA          | 2         | 0.78%   |
| ASUS X550LC          | 2         | 0.78%   |
| ASUS X550JX          | 2         | 0.78%   |
| Acer Swift           | 2         | 0.78%   |
| Valve Jupiter        | 1         | 0.39%   |
| Sony VPCEH36EF       | 1         | 0.39%   |
| Sony VGN-CR407E      | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 31        | 12.11%  |
| 2019    | 25        | 9.77%   |
| 2021    | 21        | 8.2%    |
| 2011    | 21        | 8.2%    |
| 2013    | 20        | 7.81%   |
| 2017    | 18        | 7.03%   |
| 2012    | 16        | 6.25%   |
| 2015    | 15        | 5.86%   |
| 2014    | 14        | 5.47%   |
| 2018    | 13        | 5.08%   |
| 2016    | 13        | 5.08%   |
| 2008    | 11        | 4.3%    |
| 2023    | 10        | 3.91%   |
| 2009    | 10        | 3.91%   |
| 2022    | 7         | 2.73%   |
| 2010    | 7         | 2.73%   |
| Unknown | 3         | 1.17%   |
| 2007    | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 207       | 80.86%  |
| Desktop        | 43        | 16.8%   |
| System on chip | 3         | 1.17%   |
| Convertible    | 2         | 0.78%   |
| Tablet         | 1         | 0.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 240       | 92.66%  |
| Enabled  | 19        | 7.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 256       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 79        | 30.5%   |
| 16.01-24.0 | 51        | 19.69%  |
| 8.01-16.0  | 50        | 19.31%  |
| 3.01-4.0   | 46        | 17.76%  |
| 32.01-64.0 | 13        | 5.02%   |
| 2.01-3.0   | 7         | 2.7%    |
| 1.01-2.0   | 7         | 2.7%    |
| 24.01-32.0 | 4         | 1.54%   |
| 0.51-1.0   | 2         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 85        | 29.93%  |
| 1.01-2.0  | 80        | 28.17%  |
| 4.01-8.0  | 52        | 18.31%  |
| 3.01-4.0  | 41        | 14.44%  |
| 8.01-16.0 | 10        | 3.52%   |
| 0.51-1.0  | 10        | 3.52%   |
| 0.01-0.5  | 5         | 1.76%   |
| Unknown   | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 181       | 68.56%  |
| 2      | 75        | 28.41%  |
| 4      | 4         | 1.52%   |
| 3      | 3         | 1.14%   |
| 0      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 152       | 58.69%  |
| Yes       | 107       | 41.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 221       | 85.99%  |
| No        | 36        | 14.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 88.72%  |
| No        | 29        | 11.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 197       | 75.77%  |
| No        | 63        | 24.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Tunisia | 256       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Tunis              | 140       | 47.46%  |
| Aryanah            | 20        | 6.78%   |
| Sousse             | 18        | 6.1%    |
| Nabeul             | 12        | 4.07%   |
| Sfax               | 9         | 3.05%   |
| Bizerte            | 8         | 2.71%   |
| Ben Arous          | 6         | 2.03%   |
| Rades              | 4         | 1.36%   |
| Monastir           | 4         | 1.36%   |
| Mateur             | 3         | 1.02%   |
| Mahdia             | 3         | 1.02%   |
| Kairouan           | 3         | 1.02%   |
| Houmt Souk         | 3         | 1.02%   |
| Gafsa              | 3         | 1.02%   |
| Centre Urbain Nord | 3         | 1.02%   |
| As Sanad           | 3         | 1.02%   |
| Masakin            | 2         | 0.68%   |
| Manouba            | 2         | 0.68%   |
| La Marsa           | 2         | 0.68%   |
| Jedeida            | 2         | 0.68%   |
| Hammamet           | 2         | 0.68%   |
| El Fahs            | 2         | 0.68%   |
| Borj Cedria        | 2         | 0.68%   |
| Beja               | 2         | 0.68%   |
| Zarzis             | 1         | 0.34%   |
| Zaouiat Djedidi    | 1         | 0.34%   |
| Wadi Maliz         | 1         | 0.34%   |
| Tebourba           | 1         | 0.34%   |
| Tataouine          | 1         | 0.34%   |
| Tabarka            | 1         | 0.34%   |
| Soliman            | 1         | 0.34%   |
| Sidi Bouzid        | 1         | 0.34%   |
| Sidi Abbes         | 1         | 0.34%   |
| Rafraf             | 1         | 0.34%   |
| Oued Lill          | 1         | 0.34%   |
| Medjez el Bab      | 1         | 0.34%   |
| Le Bardo           | 1         | 0.34%   |
| La Mohammedia      | 1         | 0.34%   |
| La Goulette        | 1         | 0.34%   |
| Ksar Hellal        | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 68        | 86     | 20.61%  |
| WDC                         | 40        | 53     | 12.12%  |
| Toshiba                     | 36        | 40     | 10.91%  |
| Samsung Electronics         | 27        | 45     | 8.18%   |
| Team                        | 18        | 21     | 5.45%   |
| SK hynix                    | 15        | 20     | 4.55%   |
| Hitachi                     | 14        | 15     | 4.24%   |
| SanDisk                     | 13        | 19     | 3.94%   |
| Micron Technology           | 11        | 11     | 3.33%   |
| Kingston                    | 10        | 13     | 3.03%   |
| Unknown                     | 9         | 13     | 2.73%   |
| Intel                       | 8         | 9      | 2.42%   |
| HGST                        | 8         | 9      | 2.42%   |
| A-DATA Technology           | 7         | 9      | 2.12%   |
| Emtec                       | 5         | 8      | 1.52%   |
| PNY                         | 4         | 4      | 1.21%   |
| Phison Electronics          | 3         | 3      | 0.91%   |
| Patriot                     | 3         | 3      | 0.91%   |
| Fujitsu                     | 3         | 3      | 0.91%   |
| Realtek Semiconductor       | 2         | 2      | 0.61%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.61%   |
| HS-SSD-E100                 | 2         | 3      | 0.61%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.3%    |
| UMIS                        | 1         | 1      | 0.3%    |
| TwinMOS                     | 1         | 1      | 0.3%    |
| SPCC                        | 1         | 1      | 0.3%    |
| Silicon Motion              | 1         | 1      | 0.3%    |
| SATAFIRM                    | 1         | 1      | 0.3%    |
| Phison                      | 1         | 1      | 0.3%    |
| OCZ                         | 1         | 1      | 0.3%    |
| O2 Micro                    | 1         | 1      | 0.3%    |
| MSI                         | 1         | 1      | 0.3%    |
| LITEON                      | 1         | 1      | 0.3%    |
| Lexar                       | 1         | 1      | 0.3%    |
| KVST                        | 1         | 1      | 0.3%    |
| KIOXIA                      | 1         | 1      | 0.3%    |
| Kingston Technology Company | 1         | 2      | 0.3%    |
| HS-SSD-E100N                | 1         | 1      | 0.3%    |
| Hjwdz                       | 1         | 1      | 0.3%    |
| China                       | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 19        | 5.57%   |
| Seagate ST500LT012-1DG142 500GB       | 11        | 3.23%   |
| Seagate ST2000LM007-1R8174 2TB        | 6         | 1.76%   |
| Hitachi HTS545050A7E380 500GB         | 6         | 1.76%   |
| Toshiba MQ04ABF100 1TB                | 5         | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB        | 5         | 1.47%   |
| Toshiba MQ01ABD100 1TB                | 4         | 1.17%   |
| Toshiba MQ01ABD075 752GB              | 4         | 1.17%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 0.88%   |
| Team T253X1240G 240GB SSD             | 3         | 0.88%   |
| Seagate ST9500325AS 500GB             | 3         | 0.88%   |
| Micron 2210_MTFDHBA512QFD 512GB       | 3         | 0.88%   |
| Kingston OM8PCP3512F-AI1 512GB        | 3         | 0.88%   |
| Intel SSDPEKNW512GZL 512GB            | 3         | 0.88%   |
| HGST HTS545050A7E380 500GB            | 3         | 0.88%   |
| A-DATA SU750 256GB SSD                | 3         | 0.88%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 0.59%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 2         | 0.59%   |
| WDC WD20SPZX-08UA7 2TB                | 2         | 0.59%   |
| WDC WD10SPZX-24Z10 1TB                | 2         | 0.59%   |
| WDC WD10SPZX-08Z10 1TB                | 2         | 0.59%   |
| WDC WD10SPCX-24HWST1 1TB              | 2         | 0.59%   |
| WDC WD10EADS-65M2B0 1TB               | 2         | 0.59%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 2         | 0.59%   |
| Toshiba MQ01ABF050 500GB              | 2         | 0.59%   |
| Toshiba MQ01ABD050 500GB              | 2         | 0.59%   |
| Toshiba MK5076GSX 500GB               | 2         | 0.59%   |
| Toshiba MK3275GSX 320GB               | 2         | 0.59%   |
| Toshiba HDWD110 1TB                   | 2         | 0.59%   |
| Toshiba DT01ACA050 500GB              | 2         | 0.59%   |
| Team T253X2512G 512GB SSD             | 2         | 0.59%   |
| Team T253X1480G 480GB SSD             | 2         | 0.59%   |
| Team T253512GB SSD                    | 2         | 0.59%   |
| SK hynix SC311 SATA 256GB SSD         | 2         | 0.59%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 0.59%   |
| SK hynix BC711 HFM256GD3JX013N 256GB  | 2         | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 0.59%   |
| Seagate ST3500413AS 500GB             | 2         | 0.59%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 67        | 85     | 40.85%  |
| Toshiba             | 36        | 40     | 21.95%  |
| WDC                 | 35        | 47     | 21.34%  |
| Hitachi             | 14        | 15     | 8.54%   |
| HGST                | 8         | 9      | 4.88%   |
| Fujitsu             | 3         | 3      | 1.83%   |
| Samsung Electronics | 1         | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 14        | 17     | 19.44%  |
| Samsung Electronics | 9         | 13     | 12.5%   |
| SK hynix            | 6         | 9      | 8.33%   |
| SanDisk             | 5         | 6      | 6.94%   |
| Emtec               | 5         | 8      | 6.94%   |
| A-DATA Technology   | 5         | 7      | 6.94%   |
| PNY                 | 4         | 4      | 5.56%   |
| Kingston            | 4         | 5      | 5.56%   |
| Patriot             | 3         | 3      | 4.17%   |
| Micron Technology   | 2         | 2      | 2.78%   |
| HS-SSD-E100         | 2         | 3      | 2.78%   |
| TwinMOS             | 1         | 1      | 1.39%   |
| SPCC                | 1         | 1      | 1.39%   |
| SATAFIRM            | 1         | 1      | 1.39%   |
| OCZ                 | 1         | 1      | 1.39%   |
| MSI                 | 1         | 1      | 1.39%   |
| LITEON              | 1         | 1      | 1.39%   |
| Lexar               | 1         | 1      | 1.39%   |
| KVST                | 1         | 1      | 1.39%   |
| HS-SSD-E100N        | 1         | 1      | 1.39%   |
| China               | 1         | 1      | 1.39%   |
| ASUS-PHISON         | 1         | 2      | 1.39%   |
| Apple               | 1         | 1      | 1.39%   |
| addlink             | 1         | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 157       | 200    | 50.16%  |
| NVMe    | 74        | 107    | 23.64%  |
| SSD     | 70        | 91     | 22.36%  |
| MMC     | 9         | 14     | 2.88%   |
| Unknown | 3         | 3      | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 196       | 288    | 68.77%  |
| NVMe | 74        | 107    | 25.96%  |
| MMC  | 9         | 14     | 3.16%   |
| SAS  | 6         | 6      | 2.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 130       | 167    | 58.82%  |
| 0.51-1.0   | 80        | 110    | 36.2%   |
| 1.01-2.0   | 11        | 14     | 4.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 79        | 29.59%  |
| 101-250        | 72        | 26.97%  |
| 501-1000       | 40        | 14.98%  |
| 1001-2000      | 22        | 8.24%   |
| 51-100         | 21        | 7.87%   |
| 1-20           | 15        | 5.62%   |
| 21-50          | 9         | 3.37%   |
| 2001-3000      | 4         | 1.5%    |
| Unknown        | 3         | 1.12%   |
| More than 3000 | 2         | 0.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 103       | 36.65%  |
| 21-50     | 53        | 18.86%  |
| 101-250   | 48        | 17.08%  |
| 51-100    | 38        | 13.52%  |
| 251-500   | 15        | 5.34%   |
| 501-1000  | 12        | 4.27%   |
| 1001-2000 | 9         | 3.2%    |
| Unknown   | 3         | 1.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Hitachi HTS545050A7E380 500GB                       | 4         | 5      | 11.76%  |
| Seagate ST9500325AS 500GB                           | 3         | 3      | 8.82%   |
| HGST HTS545050A7E380 500GB                          | 2         | 3      | 5.88%   |
| WDC WD6400AAKS-65A7B0 640GB                         | 1         | 1      | 2.94%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 2.94%   |
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 2.94%   |
| WDC WD5000BEVT-22A0RT0 500GB                        | 1         | 1      | 2.94%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 2.94%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 2.94%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 2.94%   |
| Seagate ST9320325AS 320GB                           | 1         | 2      | 2.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.94%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 2.94%   |
| Seagate ST3320813AS 320GB                           | 1         | 1      | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 2      | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2      | 2.94%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 2.94%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 2.94%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 2.94%   |
| Hitachi HTS547575A9E384 752GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS542516K9SA00 160GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS541616J9SA00 160GB                       | 1         | 1      | 2.94%   |
| Emtec X250 512GB SSD                                | 1         | 2      | 2.94%   |
| A-DATA Technology SX8100NP 512GB                    | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 10        | 13     | 29.41%  |
| Hitachi           | 9         | 10     | 26.47%  |
| Toshiba           | 5         | 6      | 14.71%  |
| WDC               | 4         | 5      | 11.76%  |
| HGST              | 2         | 3      | 5.88%   |
| Micron Technology | 1         | 1      | 2.94%   |
| Kingston          | 1         | 1      | 2.94%   |
| Emtec             | 1         | 2      | 2.94%   |
| A-DATA Technology | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 13     | 33.33%  |
| Hitachi | 9         | 10     | 30%     |
| Toshiba | 5         | 6      | 16.67%  |
| WDC     | 4         | 5      | 13.33%  |
| HGST    | 2         | 3      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 37     | 87.1%   |
| SSD  | 3         | 4      | 9.68%   |
| NVMe | 1         | 1      | 3.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK1646GSX 160GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 129       | 196    | 47.08%  |
| Works    | 113       | 176    | 41.24%  |
| Malfunc  | 31        | 42     | 11.31%  |
| Failed   | 1         | 1      | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 209       | 68.08%  |
| AMD                                     | 25        | 8.14%   |
| Samsung Electronics                     | 17        | 5.54%   |
| SanDisk                                 | 11        | 3.58%   |
| SK hynix                                | 9         | 2.93%   |
| Micron Technology                       | 9         | 2.93%   |
| Kingston Technology Company             | 7         | 2.28%   |
| Phison Electronics                      | 6         | 1.95%   |
| Realtek Semiconductor                   | 4         | 1.3%    |
| Silicon Motion                          | 2         | 0.65%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.65%   |
| Union Memory (Shenzhen)                 | 1         | 0.33%   |
| Shenzhen Unionmemory Information System | 1         | 0.33%   |
| Shenzhen Longsys Electronics            | 1         | 0.33%   |
| O2 Micro                                | 1         | 0.33%   |
| KIOXIA                                  | 1         | 0.33%   |
| ADATA Technology                        | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 20        | 6.04%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 19        | 5.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 16        | 4.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 14        | 4.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 13        | 3.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 12        | 3.63%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 12        | 3.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 3.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 3.02%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 10        | 3.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 2.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 2.11%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7         | 2.11%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 1.81%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 5         | 1.51%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 5         | 1.51%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 5         | 1.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 1.51%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 1.51%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 4         | 1.21%   |
| Phison E12 NVMe Controller                                                              | 4         | 1.21%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 4         | 1.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.21%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 3         | 0.91%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 3         | 0.91%   |
| Intel SSD 660P Series                                                                   | 3         | 0.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.91%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 3         | 0.91%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 0.91%   |
| SK hynix BC511 NVMe SSD                                                                 | 2         | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2         | 0.6%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2         | 0.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 190       | 61.09%  |
| NVMe | 74        | 23.79%  |
| RAID | 29        | 9.32%   |
| IDE  | 18        | 5.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 215       | 83.98%  |
| AMD    | 38        | 14.84%  |
| ARM    | 3         | 1.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 2.34%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 2.34%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 1.95%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 1.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.95%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.95%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 1.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.17%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.17%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.17%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.17%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.17%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 1.17%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.17%   |
| ARM Processor                                 | 3         | 1.17%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.17%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.17%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 0.78%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.78%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.78%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.78%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.78%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.78%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.78%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 2         | 0.78%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 60        | 23.44%  |
| Intel Core i7           | 49        | 19.14%  |
| Other                   | 35        | 13.67%  |
| Intel Core i3           | 35        | 13.67%  |
| AMD Ryzen 5             | 16        | 6.25%   |
| Intel Pentium           | 10        | 3.91%   |
| Intel Celeron           | 10        | 3.91%   |
| Intel Core 2 Duo        | 8         | 3.13%   |
| Intel Core 2 Quad       | 7         | 2.73%   |
| AMD Ryzen 7             | 5         | 1.95%   |
| Intel Pentium Dual-Core | 2         | 0.78%   |
| Intel Atom              | 2         | 0.78%   |
| AMD Ryzen 3             | 2         | 0.78%   |
| Intel Xeon              | 1         | 0.39%   |
| Intel Core m3           | 1         | 0.39%   |
| Intel Core 2 Extreme    | 1         | 0.39%   |
| Intel Celeron M         | 1         | 0.39%   |
| AMD Sempron             | 1         | 0.39%   |
| AMD Ryzen 9             | 1         | 0.39%   |
| AMD Ryzen 5 PRO         | 1         | 0.39%   |
| AMD FX                  | 1         | 0.39%   |
| AMD E2                  | 1         | 0.39%   |
| AMD E                   | 1         | 0.39%   |
| AMD Athlon              | 1         | 0.39%   |
| AMD A8                  | 1         | 0.39%   |
| AMD A6                  | 1         | 0.39%   |
| AMD A4                  | 1         | 0.39%   |
| AMD A10                 | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 118       | 46.09%  |
| 4       | 90        | 35.16%  |
| 6       | 22        | 8.59%   |
| 8       | 12        | 4.69%   |
| 10      | 4         | 1.56%   |
| 1       | 4         | 1.56%   |
| 12      | 3         | 1.17%   |
| 14      | 2         | 0.78%   |
| Unknown | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 256       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 199       | 77.43%  |
| 1       | 57        | 22.18%  |
| Unknown | 1         | 0.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 254       | 99.22%  |
| 32-bit         | 1         | 0.39%   |
| Unknown        | 1         | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 41.35%  |
| 0x206a7    | 16        | 6.02%   |
| 0x806c1    | 9         | 3.38%   |
| 0x40651    | 9         | 3.38%   |
| 0x306a9    | 9         | 3.38%   |
| 0x1067a    | 9         | 3.38%   |
| 0x806ea    | 8         | 3.01%   |
| 0xa0652    | 7         | 2.63%   |
| 0x806ec    | 7         | 2.63%   |
| 0x906ea    | 6         | 2.26%   |
| 0x506e3    | 6         | 2.26%   |
| 0x306c3    | 6         | 2.26%   |
| 0x406e3    | 5         | 1.88%   |
| 0x08108109 | 5         | 1.88%   |
| 0x306d4    | 4         | 1.5%    |
| 0x806e9    | 3         | 1.13%   |
| 0x706e5    | 3         | 1.13%   |
| 0x20655    | 3         | 1.13%   |
| 0x706a8    | 2         | 0.75%   |
| 0x406c4    | 2         | 0.75%   |
| 0x30678    | 2         | 0.75%   |
| 0x20652    | 2         | 0.75%   |
| 0x106ca    | 2         | 0.75%   |
| 0x08600106 | 2         | 0.75%   |
| 0x08108102 | 2         | 0.75%   |
| 0x06006705 | 2         | 0.75%   |
| 0x06006704 | 2         | 0.75%   |
| 0xa0671    | 1         | 0.38%   |
| 0xa0653    | 1         | 0.38%   |
| 0x906e9    | 1         | 0.38%   |
| 0x906a4    | 1         | 0.38%   |
| 0x906a3    | 1         | 0.38%   |
| 0x90672    | 1         | 0.38%   |
| 0x6fd      | 1         | 0.38%   |
| 0x6fb      | 1         | 0.38%   |
| 0x6d8      | 1         | 0.38%   |
| 0x506c9    | 1         | 0.38%   |
| 0x40661    | 1         | 0.38%   |
| 0x10677    | 1         | 0.38%   |
| 0x0a50000f | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 43        | 16.8%   |
| Haswell          | 26        | 10.16%  |
| SandyBridge      | 23        | 8.98%   |
| Skylake          | 15        | 5.86%   |
| Penryn           | 15        | 5.86%   |
| Unknown          | 15        | 5.86%   |
| TigerLake        | 14        | 5.47%   |
| IvyBridge        | 13        | 5.08%   |
| CometLake        | 11        | 4.3%    |
| Broadwell        | 10        | 3.91%   |
| Zen+             | 9         | 3.52%   |
| Icelake          | 9         | 3.52%   |
| Westmere         | 8         | 3.13%   |
| Zen 2            | 6         | 2.34%   |
| Alderlake Hybrid | 6         | 2.34%   |
| Zen 3            | 5         | 1.95%   |
| Silvermont       | 5         | 1.95%   |
| Goldmont plus    | 5         | 1.95%   |
| Excavator        | 4         | 1.56%   |
| Core             | 3         | 1.17%   |
| Piledriver       | 2         | 0.78%   |
| Goldmont         | 2         | 0.78%   |
| Bonnell          | 2         | 0.78%   |
| Zen              | 1         | 0.39%   |
| Puma             | 1         | 0.39%   |
| P6               | 1         | 0.39%   |
| K8 & K10 hybrid  | 1         | 0.39%   |
| Bobcat           | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 190       | 52.63%  |
| Nvidia | 110       | 30.47%  |
| AMD    | 61        | 16.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 4.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 4.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 3.28%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 11        | 3.01%   |
| Intel HD Graphics 5500                                                                   | 10        | 2.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 2.46%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 2.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.46%   |
| Intel HD Graphics 620                                                                    | 7         | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.64%   |
| Nvidia GM108M [GeForce MX110]                                                            | 5         | 1.37%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 1.37%   |
| Intel HD Graphics 530                                                                    | 5         | 1.37%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.37%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.09%   |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.09%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.09%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.09%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.82%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 0.82%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.82%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 3         | 0.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.82%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 3         | 0.82%   |
| Intel HD Graphics 630                                                                    | 3         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.82%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 88        | 34.38%  |
| Intel + Nvidia | 76        | 29.69%  |
| 1 x AMD        | 28        | 10.94%  |
| 1 x Nvidia     | 25        | 9.77%   |
| Intel + AMD    | 21        | 8.2%    |
| AMD + Nvidia   | 9         | 3.52%   |
| Other          | 3         | 1.17%   |
| 2 x Intel      | 3         | 1.17%   |
| 2 x AMD        | 3         | 1.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 193       | 73.11%  |
| Proprietary | 57        | 21.59%  |
| Unknown     | 14        | 5.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 159       | 60.69%  |
| 1.01-2.0   | 40        | 15.27%  |
| 0.01-0.5   | 19        | 7.25%   |
| 3.01-4.0   | 16        | 6.11%   |
| 0.51-1.0   | 15        | 5.73%   |
| 5.01-6.0   | 7         | 2.67%   |
| 7.01-8.0   | 3         | 1.15%   |
| 2.01-3.0   | 2         | 0.76%   |
| 8.01-16.0  | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 48        | 17.52%  |
| Chimei Innolux          | 42        | 15.33%  |
| AU Optronics            | 42        | 15.33%  |
| BOE                     | 40        | 14.6%   |
| LG Display              | 32        | 11.68%  |
| Hewlett-Packard         | 17        | 6.2%    |
| Lenovo                  | 6         | 2.19%   |
| Chi Mei Optoelectronics | 6         | 2.19%   |
| PANDA                   | 5         | 1.82%   |
| Dell                    | 5         | 1.82%   |
| HKC                     | 4         | 1.46%   |
| MSI                     | 3         | 1.09%   |
| Acer                    | 3         | 1.09%   |
| Philips                 | 2         | 0.73%   |
| Packard Bell            | 2         | 0.73%   |
| Goldstar                | 2         | 0.73%   |
| BenQ                    | 2         | 0.73%   |
| ViewSonic               | 1         | 0.36%   |
| Valve                   | 1         | 0.36%   |
| TMX                     | 1         | 0.36%   |
| S2-Tek                  | 1         | 0.36%   |
| PKB                     | 1         | 0.36%   |
| NCS                     | 1         | 0.36%   |
| Medion                  | 1         | 0.36%   |
| LG Philips              | 1         | 0.36%   |
| ITE                     | 1         | 0.36%   |
| HPN                     | 1         | 0.36%   |
| GDH                     | 1         | 0.36%   |
| ASUSTek Computer        | 1         | 0.36%   |
| Apple                   | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 2.88%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 7         | 2.52%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 4         | 1.44%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 4         | 1.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 4         | 1.44%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 1.44%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 4         | 1.44%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 4         | 1.44%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 3         | 1.08%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch     | 3         | 1.08%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 1.08%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 1.08%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 1.08%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch         | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 2         | 0.72%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.72%   |
| HKC GM27H10C HKC0027 1920x1080 597x336mm 27.0-inch                       | 2         | 0.72%   |
| Hewlett-Packard x20LED HWP2910 1600x900 443x249mm 20.0-inch              | 2         | 0.72%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch               | 2         | 0.72%   |
| Hewlett-Packard P224 HPN361E 1920x1080 527x296mm 23.8-inch               | 2         | 0.72%   |
| Hewlett-Packard 2011 HWP2935 1600x900 440x250mm 19.9-inch                | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.72%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.72%   |
| BOE LCD Monitor BOE08E5 1366x768 344x194mm 15.5-inch                     | 2         | 0.72%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.72%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.72%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                    | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch           | 2         | 0.72%   |
| Acer V193HQV ACR0133 1366x768 410x230mm 18.5-inch                        | 2         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 114       | 44.36%  |
| 1366x768 (WXGA)    | 92        | 35.8%   |
| 1600x900 (HD+)     | 16        | 6.23%   |
| 1280x1024 (SXGA)   | 5         | 1.95%   |
| 3840x2160 (4K)     | 4         | 1.56%   |
| 1280x800 (WXGA)    | 4         | 1.56%   |
| 1920x1200 (WUXGA)  | 3         | 1.17%   |
| 1680x1050 (WSXGA+) | 3         | 1.17%   |
| 1440x900 (WXGA+)   | 3         | 1.17%   |
| 1024x600           | 2         | 0.78%   |
| Unknown            | 2         | 0.78%   |
| 800x1280           | 1         | 0.39%   |
| 3840x1100          | 1         | 0.39%   |
| 3440x1440          | 1         | 0.39%   |
| 3072x1920          | 1         | 0.39%   |
| 2880x1800          | 1         | 0.39%   |
| 2880x1620          | 1         | 0.39%   |
| 2560x1600          | 1         | 0.39%   |
| 2560x1440 (QHD)    | 1         | 0.39%   |
| 1360x768           | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 150       | 54.55%  |
| 23      | 16        | 5.82%   |
| 17      | 15        | 5.45%   |
| 14      | 13        | 4.73%   |
| 21      | 10        | 3.64%   |
| 13      | 10        | 3.64%   |
| 24      | 9         | 3.27%   |
| 27      | 8         | 2.91%   |
| 20      | 7         | 2.55%   |
| 19      | 5         | 1.82%   |
| 18      | 5         | 1.82%   |
| 12      | 5         | 1.82%   |
| 16      | 4         | 1.45%   |
| Unknown | 4         | 1.45%   |
| 31      | 3         | 1.09%   |
| 11      | 3         | 1.09%   |
| 22      | 2         | 0.73%   |
| 10      | 2         | 0.73%   |
| 52      | 1         | 0.36%   |
| 42      | 1         | 0.36%   |
| 34      | 1         | 0.36%   |
| 7       | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 168       | 62.45%  |
| 501-600     | 31        | 11.52%  |
| 401-500     | 26        | 9.67%   |
| 351-400     | 19        | 7.06%   |
| 201-300     | 14        | 5.2%    |
| Unknown     | 4         | 1.49%   |
| 601-700     | 3         | 1.12%   |
| 701-800     | 1         | 0.37%   |
| 1001-1500   | 1         | 0.37%   |
| 901-1000    | 1         | 0.37%   |
| 1-100       | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 215       | 87.04%  |
| 16/10   | 18        | 7.29%   |
| 5/4     | 5         | 2.02%   |
| Unknown | 4         | 1.62%   |
| 4/3     | 1         | 0.4%    |
| 3/2     | 1         | 0.4%    |
| 3.40    | 1         | 0.4%    |
| 21/9    | 1         | 0.4%    |
| 0.67    | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 150       | 54.74%  |
| 201-250        | 33        | 12.04%  |
| 81-90          | 16        | 5.84%   |
| 151-200        | 14        | 5.11%   |
| 121-130        | 10        | 3.65%   |
| 301-350        | 8         | 2.92%   |
| 141-150        | 8         | 2.92%   |
| 71-80          | 5         | 1.82%   |
| 61-70          | 4         | 1.46%   |
| 51-60          | 4         | 1.46%   |
| 351-500        | 4         | 1.46%   |
| 111-120        | 4         | 1.46%   |
| Unknown        | 4         | 1.46%   |
| 41-50          | 2         | 0.73%   |
| 251-300        | 2         | 0.73%   |
| 131-140        | 2         | 0.73%   |
| More than 1000 | 1         | 0.36%   |
| 1-40           | 1         | 0.36%   |
| 501-1000       | 1         | 0.36%   |
| 91-100         | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 91        | 34.21%  |
| 121-160       | 87        | 32.71%  |
| 51-100        | 68        | 25.56%  |
| 161-240       | 10        | 3.76%   |
| Unknown       | 4         | 1.5%    |
| More than 240 | 3         | 1.13%   |
| 1-50          | 3         | 1.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 213       | 82.24%  |
| 2     | 35        | 13.51%  |
| 0     | 10        | 3.86%   |
| 3     | 1         | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 183       | 44.1%   |
| Intel                             | 97        | 23.37%  |
| Qualcomm Atheros                  | 51        | 12.29%  |
| Broadcom                          | 25        | 6.02%   |
| Ralink Technology                 | 14        | 3.37%   |
| Ralink                            | 12        | 2.89%   |
| MediaTek                          | 9         | 2.17%   |
| Broadcom Limited                  | 7         | 1.69%   |
| ICS Advent                        | 2         | 0.48%   |
| Ericsson Business Mobile Networks | 2         | 0.48%   |
| D-Link                            | 2         | 0.48%   |
| Xiaomi                            | 1         | 0.24%   |
| TP-Link                           | 1         | 0.24%   |
| Sierra Wireless                   | 1         | 0.24%   |
| Samsung Electronics               | 1         | 0.24%   |
| OPPO Electronics                  | 1         | 0.24%   |
| Microchip Technology              | 1         | 0.24%   |
| Marvell Technology Group          | 1         | 0.24%   |
| Lenovo                            | 1         | 0.24%   |
| IMC Networks                      | 1         | 0.24%   |
| Huawei Technologies               | 1         | 0.24%   |
| D-Link System                     | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 119       | 24.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 49        | 10.25%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 2.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 13        | 2.72%   |
| Intel Wi-Fi 6 AX201                                                    | 12        | 2.51%   |
| Broadcom BCM43142 802.11b/g/n                                          | 12        | 2.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 2.3%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 9         | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 7         | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.26%   |
| Ralink MT7601U Wireless Adapter                                        | 6         | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 6         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.26%   |
| Ralink RT5370 Wireless Adapter                                         | 5         | 1.05%   |
| Intel Wireless 7265                                                    | 5         | 1.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 1.05%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 4         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.84%   |
| Intel Wireless 8260                                                    | 4         | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 4         | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.63%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.63%   |
| Intel Wireless 8265 / 8275                                             | 3         | 0.63%   |
| Intel WiFi Link 5100                                                   | 3         | 0.63%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 3         | 0.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.63%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 3         | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 0.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 0.42%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 89        | 36.18%  |
| Qualcomm Atheros      | 48        | 19.51%  |
| Realtek Semiconductor | 44        | 17.89%  |
| Broadcom              | 19        | 7.72%   |
| Ralink Technology     | 14        | 5.69%   |
| Ralink                | 12        | 4.88%   |
| MediaTek              | 7         | 2.85%   |
| Broadcom Limited      | 7         | 2.85%   |
| D-Link                | 2         | 0.81%   |
| TP-Link               | 1         | 0.41%   |
| Sierra Wireless       | 1         | 0.41%   |
| IMC Networks          | 1         | 0.41%   |
| D-Link System         | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 5.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13        | 5.26%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 4.86%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 4.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 4.45%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 3.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.24%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 7         | 2.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.43%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 2.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 2.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.43%   |
| Ralink RT5370 Wireless Adapter                                 | 5         | 2.02%   |
| Intel Wireless 7265                                            | 5         | 2.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4         | 1.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.62%   |
| Intel Wireless 8260                                            | 4         | 1.62%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 1.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 1.62%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.21%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.21%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.21%   |
| Intel WiFi Link 5100                                           | 3         | 1.21%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.81%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2         | 0.81%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 2         | 0.81%   |
| Intel Wireless 7260                                            | 2         | 0.81%   |
| Intel Wireless 3165                                            | 2         | 0.81%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 0.81%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 174       | 76.65%  |
| Intel                    | 28        | 12.33%  |
| Qualcomm Atheros         | 7         | 3.08%   |
| Broadcom                 | 7         | 3.08%   |
| MediaTek                 | 2         | 0.88%   |
| ICS Advent               | 2         | 0.88%   |
| Xiaomi                   | 1         | 0.44%   |
| Samsung Electronics      | 1         | 0.44%   |
| OPPO Electronics         | 1         | 0.44%   |
| Microchip Technology     | 1         | 0.44%   |
| Marvell Technology Group | 1         | 0.44%   |
| Lenovo                   | 1         | 0.44%   |
| Huawei Technologies      | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 119       | 51.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 49        | 21.4%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 2.18%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.31%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 3         | 1.31%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 1.31%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.87%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.87%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.44%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.44%   |
| OPPO OnePlus Nord 4                                                    | 1         | 0.44%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 1         | 0.44%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.44%   |
| Lenovo ThinkPad Lan                                                    | 1         | 0.44%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.44%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.44%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.44%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.44%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.44%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.44%   |
| Intel Ethernet Connection (23) I219-V                                  | 1         | 0.44%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.44%   |
| Intel Ethernet Connection (14) I219-V                                  | 1         | 0.44%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 228       | 50.55%  |
| Ethernet | 221       | 49%     |
| Modem    | 2         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 191       | 71.8%   |
| Ethernet | 75        | 28.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 184       | 71.6%   |
| 1     | 71        | 27.63%  |
| 0     | 2         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 252       | 98.44%  |
| Yes  | 4         | 1.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 37.56%  |
| Qualcomm Atheros Communications | 32        | 16.24%  |
| Realtek Semiconductor           | 27        | 13.71%  |
| Lite-On Technology              | 13        | 6.6%    |
| IMC Networks                    | 13        | 6.6%    |
| Broadcom                        | 12        | 6.09%   |
| Ralink                          | 7         | 3.55%   |
| Foxconn / Hon Hai               | 6         | 3.05%   |
| Cambridge Silicon Radio         | 4         | 2.03%   |
| Toshiba                         | 3         | 1.52%   |
| Hewlett-Packard                 | 2         | 1.02%   |
| Realtek                         | 1         | 0.51%   |
| Dell                            | 1         | 0.51%   |
| ASUSTek Computer                | 1         | 0.51%   |
| Apple                           | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 30        | 15.23%  |
| Intel Bluetooth wireless interface                  | 22        | 11.17%  |
| Realtek Bluetooth Radio                             | 19        | 9.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 15        | 7.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 7.11%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 4.06%   |
| Ralink RT3290 Bluetooth                             | 7         | 3.55%   |
| IMC Networks Wireless_Device                        | 6         | 3.05%   |
| IMC Networks Bluetooth Radio                        | 6         | 3.05%   |
| Lite-On Bluetooth Device                            | 5         | 2.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 2.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 2.03%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 2.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.52%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 1.52%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.52%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.02%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.02%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.02%   |
| Lite-On BCM43142A0                                  | 2         | 1.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.02%   |
| Intel AX211 Bluetooth                               | 2         | 1.02%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.02%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.02%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.02%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.51%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.51%   |
| Toshiba BCM43142A0                                  | 1         | 0.51%   |
| Realtek Bluetooth Radio                             | 1         | 0.51%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.51%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.51%   |
| Intel AX210 Bluetooth                               | 1         | 0.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.51%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.51%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 216       | 65.26%  |
| Nvidia                  | 58        | 17.52%  |
| AMD                     | 45        | 13.6%   |
| C-Media Electronics     | 4         | 1.21%   |
| DSEA A/S                | 2         | 0.6%    |
| Xiamen VBeT Electronics | 1         | 0.3%    |
| Razer USA               | 1         | 0.3%    |
| Plantronics             | 1         | 0.3%    |
| Lenovo                  | 1         | 0.3%    |
| JMTek                   | 1         | 0.3%    |
| ASUSTek Computer        | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 26        | 6.75%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 22        | 5.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 4.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 18        | 4.68%   |
| Intel 8 Series HD Audio Controller                                         | 15        | 3.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 3.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 3.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 10        | 2.6%    |
| Intel Comet Lake PCH cAVS                                                  | 10        | 2.6%    |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 2.6%    |
| Intel Broadwell-U Audio Controller                                         | 10        | 2.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 2.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9         | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 2.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.56%   |
| Nvidia High Definition Audio Controller                                    | 6         | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 1.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.3%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.3%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.3%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 1.3%    |
| Nvidia GA107 High Definition Audio Controller                              | 4         | 1.04%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.04%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1.04%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 1.04%   |
| AMD High Definition Audio Controller                                       | 4         | 1.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.78%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.78%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 3         | 0.78%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 51        | 26.02%  |
| SK hynix                     | 34        | 17.35%  |
| Micron Technology            | 27        | 13.78%  |
| Team                         | 22        | 11.22%  |
| Unknown                      | 12        | 6.12%   |
| A-DATA Technology            | 10        | 5.1%    |
| Elpida                       | 6         | 3.06%   |
| Nanya Technology             | 5         | 2.55%   |
| Crucial                      | 5         | 2.55%   |
| Ramaxel Technology           | 4         | 2.04%   |
| Kingston                     | 3         | 1.53%   |
| Unknown (ABCD)               | 2         | 1.02%   |
| TwinMOS                      | 2         | 1.02%   |
| Toshiba                      | 2         | 1.02%   |
| Patriot                      | 2         | 1.02%   |
| Hikvision                    | 2         | 1.02%   |
| Transcend                    | 1         | 0.51%   |
| PNY                          | 1         | 0.51%   |
| Patriot Memory (PDP Systems) | 1         | 0.51%   |
| Melco                        | 1         | 0.51%   |
| GOODRAM                      | 1         | 0.51%   |
| ASint Technology             | 1         | 0.51%   |
| 0BBA00000000                 | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s       | 9         | 4.39%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 4         | 1.95%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s        | 3         | 1.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 1.46%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 3         | 1.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 3         | 1.46%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s    | 3         | 1.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 1.46%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s    | 3         | 1.46%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 3         | 1.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 3         | 1.46%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 3         | 1.46%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                 | 3         | 1.46%   |
| Toshiba RAM 8HTF12864HDY-800G1 4096MB SODIMM 1066MT/s       | 2         | 0.98%   |
| Toshiba RAM 64T128020EDL2.5C2 4096MB SODIMM 1066MT/s        | 2         | 0.98%   |
| Team RAM TEAMGROUP-SD4-3200 32GB Row Of Chips DDR4 3200MT/s | 2         | 0.98%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s       | 2         | 0.98%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s       | 2         | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 2         | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.98%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.98%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 0.98%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 0.98%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.98%   |
| Micron RAM MT40A512M16TB-062E:R 4GB SODIMM DDR4 3200MT/s    | 2         | 0.98%   |
| Micron RAM Module 4GB Row Of Chips DDR4 2400MT/s            | 2         | 0.98%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 2         | 0.98%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3                            | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s              | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3                       | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 400MT/s                  | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s               | 1         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                  | 1         | 0.49%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 83        | 53.55%  |
| DDR3    | 45        | 29.03%  |
| DDR2    | 8         | 5.16%   |
| SDRAM   | 5         | 3.23%   |
| LPDDR4  | 4         | 2.58%   |
| DDR5    | 4         | 2.58%   |
| LPDDR5  | 3         | 1.94%   |
| LPDDR3  | 2         | 1.29%   |
| Unknown | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 119       | 75.32%  |
| DIMM         | 22        | 13.92%  |
| Row Of Chips | 16        | 10.13%  |
| Chip         | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 63        | 34.05%  |
| 4096  | 55        | 29.73%  |
| 16384 | 27        | 14.59%  |
| 2048  | 21        | 11.35%  |
| 32768 | 14        | 7.57%   |
| 1024  | 5         | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 40        | 23.12%  |
| 2667    | 32        | 18.5%   |
| 1600    | 24        | 13.87%  |
| 2400    | 13        | 7.51%   |
| 1334    | 13        | 7.51%   |
| 1333    | 7         | 4.05%   |
| 667     | 5         | 2.89%   |
| 4800    | 4         | 2.31%   |
| 2133    | 4         | 2.31%   |
| 1066    | 4         | 2.31%   |
| 6400    | 3         | 1.73%   |
| 4199    | 3         | 1.73%   |
| 3266    | 3         | 1.73%   |
| 1867    | 3         | 1.73%   |
| Unknown | 3         | 1.73%   |
| 8400    | 2         | 1.16%   |
| 3000    | 2         | 1.16%   |
| 49926   | 1         | 0.58%   |
| 3800    | 1         | 0.58%   |
| 2465    | 1         | 0.58%   |
| 1648    | 1         | 0.58%   |
| 1067    | 1         | 0.58%   |
| 975     | 1         | 0.58%   |
| 800     | 1         | 0.58%   |
| 400     | 1         | 0.58%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 4         | 66.67%  |
| Seiko Epson     | 1         | 16.67%  |
| Canon           | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP LaserJet P1005       | 2         | 33.33%  |
| Seiko Epson L365 Series | 1         | 16.67%  |
| HP DeskJet 5810 series  | 1         | 16.67%  |
| HP Deskjet 1010 series  | 1         | 16.67%  |
| Canon G2010 series      | 1         | 16.67%  |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 19.9%   |
| IMC Networks                           | 25        | 12.76%  |
| Realtek Semiconductor                  | 23        | 11.73%  |
| Microdia                               | 17        | 8.67%   |
| Bison Electronics                      | 16        | 8.16%   |
| Suyin                                  | 10        | 5.1%    |
| Syntek                                 | 9         | 4.59%   |
| Sunplus Innovation Technology          | 9         | 4.59%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 4.59%   |
| Luxvisions Innotech Limited            | 7         | 3.57%   |
| Quanta                                 | 6         | 3.06%   |
| Lite-On Technology                     | 6         | 3.06%   |
| Sonix Technology                       | 3         | 1.53%   |
| Ricoh                                  | 2         | 1.02%   |
| Apple                                  | 2         | 1.02%   |
| Alcor Micro                            | 2         | 1.02%   |
| Acer                                   | 2         | 1.02%   |
| Silicon Motion                         | 1         | 0.51%   |
| ShineTech                              | 1         | 0.51%   |
| Samsung Electronics                    | 1         | 0.51%   |
| Lenovo                                 | 1         | 0.51%   |
| Importek                               | 1         | 0.51%   |
| Genesys Logic                          | 1         | 0.51%   |
| Cubeternet                             | 1         | 0.51%   |
| ALi                                    | 1         | 0.51%   |
| A4Tech                                 | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 10        | 5.08%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 4.57%   |
| IMC Networks Integrated Camera                                             | 7         | 3.55%   |
| Bison Integrated Camera                                                    | 7         | 3.55%   |
| Microdia Integrated_Webcam_HD                                              | 6         | 3.05%   |
| Sunplus Integrated_Webcam_HD                                               | 5         | 2.54%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 2.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 5         | 2.54%   |
| Syntek Integrated Camera                                                   | 4         | 2.03%   |
| Realtek USB Camera                                                         | 4         | 2.03%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 4         | 2.03%   |
| Lite-On Integrated Camera                                                  | 4         | 2.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 4         | 2.03%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 2.03%   |
| Chicony HD WebCam                                                          | 4         | 2.03%   |
| Bison HD Webcam                                                            | 4         | 2.03%   |
| Syntek EasyCamera                                                          | 3         | 1.52%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 3         | 1.52%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 3         | 1.52%   |
| Quanta HD WebCam                                                           | 3         | 1.52%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 1.52%   |
| Suyin Integrated_Webcam_HD                                                 | 2         | 1.02%   |
| Suyin HP TrueVision HD                                                     | 2         | 1.02%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.02%   |
| Realtek EasyCamera                                                         | 2         | 1.02%   |
| Microdia Webcam SC-10HDD12636P                                             | 2         | 1.02%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 2         | 1.02%   |
| IMC Networks Lenovo EasyCamera                                             | 2         | 1.02%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 1.02%   |
| Chicony EasyCamera                                                         | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 2         | 1.02%   |
| Bison Lenovo EasyCamera                                                    | 2         | 1.02%   |
| Bison EasyCamera                                                           | 2         | 1.02%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                                       | 1         | 0.51%   |
| Syntek Integrated RGB Camera                                               | 1         | 0.51%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.51%   |
| Suyin Laptop_Integrated_Webcam_2HDM                                        | 1         | 0.51%   |
| Suyin HP webcam [dv6-1190en]                                               | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 8         | 47.06%  |
| Synaptics                          | 2         | 11.76%  |
| Shenzhen Goodix Technology         | 2         | 11.76%  |
| LighTuning Technology              | 2         | 11.76%  |
| Upek                               | 1         | 5.88%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 5.88%   |
| AuthenTec                          | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 3         | 17.65%  |
| Validity Sensors VFS471 Fingerprint Reader                      | 2         | 11.76%  |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 11.76%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 5.88%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner                            | 1         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 1         | 5.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 5.88%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 5.88%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 5.88%   |
| AuthenTec AES1600                                               | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Broadcom    | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 194       | 71.32%  |
| 1     | 62        | 22.79%  |
| 2     | 9         | 3.31%   |
| 3     | 5         | 1.84%   |
| 5     | 1         | 0.37%   |
| 4     | 1         | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 24        | 25%     |
| Net/wireless             | 18        | 18.75%  |
| Fingerprint reader       | 17        | 17.71%  |
| Bluetooth                | 10        | 10.42%  |
| Communication controller | 5         | 5.21%   |
| Chipcard                 | 5         | 5.21%   |
| Camera                   | 5         | 5.21%   |
| Net/ethernet             | 3         | 3.13%   |
| Storage                  | 2         | 2.08%   |
| Sound                    | 2         | 2.08%   |
| Multimedia controller    | 2         | 2.08%   |
| Card reader              | 2         | 2.08%   |
| Network                  | 1         | 1.04%   |

