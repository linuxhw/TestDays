Reborn OS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Reborn OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Reborn_OS/Desktop/README.md) and [notebooks](/Dist/Reborn_OS/Notebook/README.md).

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

Total: 216

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 8619                        | Desktop     | [00c3a60e4c](https://linux-hardware.org/?probe=00c3a60e4c) | Aug 11, 2023 |
| HP            | 2B26 A01                    | All in one  | [41de8f48f0](https://linux-hardware.org/?probe=41de8f48f0) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [8c5385a962](https://linux-hardware.org/?probe=8c5385a962) | Jul 17, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [dc36b0a5e7](https://linux-hardware.org/?probe=dc36b0a5e7) | Jun 24, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [8503c5d0fe](https://linux-hardware.org/?probe=8503c5d0fe) | Jun 21, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [ab83a7d817](https://linux-hardware.org/?probe=ab83a7d817) | Jun 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8173a6e67f](https://linux-hardware.org/?probe=8173a6e67f) | Jun 08, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [772d1f8765](https://linux-hardware.org/?probe=772d1f8765) | Jun 03, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [54bddcb324](https://linux-hardware.org/?probe=54bddcb324) | May 24, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [db1ad69341](https://linux-hardware.org/?probe=db1ad69341) | May 06, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [8c41580881](https://linux-hardware.org/?probe=8c41580881) | May 06, 2023 |
| Timi          | A35S                        | Notebook    | [92022a5fa2](https://linux-hardware.org/?probe=92022a5fa2) | Mar 25, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [9bfb72d26a](https://linux-hardware.org/?probe=9bfb72d26a) | Mar 21, 2023 |
| HP            | 18E7                        | Desktop     | [9f4d303ffa](https://linux-hardware.org/?probe=9f4d303ffa) | Mar 18, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [bd0af3660b](https://linux-hardware.org/?probe=bd0af3660b) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [12d1ccac8d](https://linux-hardware.org/?probe=12d1ccac8d) | Mar 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [57edb37217](https://linux-hardware.org/?probe=57edb37217) | Mar 08, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [72b8072c9a](https://linux-hardware.org/?probe=72b8072c9a) | Feb 20, 2023 |
| Medion        | X6816                       | Notebook    | [3f05d06600](https://linux-hardware.org/?probe=3f05d06600) | Feb 18, 2023 |
| Medion        | X6816                       | Notebook    | [fe99854800](https://linux-hardware.org/?probe=fe99854800) | Feb 17, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [7037d37121](https://linux-hardware.org/?probe=7037d37121) | Feb 05, 2023 |
| HP            | 8460                        | Desktop     | [078e151afc](https://linux-hardware.org/?probe=078e151afc) | Jan 29, 2023 |
| HP            | 8460                        | Desktop     | [2bfad5b267](https://linux-hardware.org/?probe=2bfad5b267) | Jan 24, 2023 |
| Biostar       | A320MH                      | Desktop     | [3fb3a04230](https://linux-hardware.org/?probe=3fb3a04230) | Jan 14, 2023 |
| HP            | 8460                        | Desktop     | [6089c30228](https://linux-hardware.org/?probe=6089c30228) | Dec 07, 2022 |
| Dell          | G15 5511                    | Notebook    | [d2c2cb8454](https://linux-hardware.org/?probe=d2c2cb8454) | Nov 30, 2022 |
| Dell          | G15 5511                    | Notebook    | [f9e456efd0](https://linux-hardware.org/?probe=f9e456efd0) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d9af542480](https://linux-hardware.org/?probe=d9af542480) | Nov 08, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [0b91ee456b](https://linux-hardware.org/?probe=0b91ee456b) | Nov 02, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [5f90d4e478](https://linux-hardware.org/?probe=5f90d4e478) | Nov 02, 2022 |
| HP            | 8460                        | Desktop     | [d74207aa28](https://linux-hardware.org/?probe=d74207aa28) | Sep 08, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [f4a5cc4ace](https://linux-hardware.org/?probe=f4a5cc4ace) | Sep 04, 2022 |
| HP            | 81B7 1101                   | All in one  | [7b1f1044ae](https://linux-hardware.org/?probe=7b1f1044ae) | Aug 18, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [6d014552aa](https://linux-hardware.org/?probe=6d014552aa) | Aug 15, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8dd3e52620](https://linux-hardware.org/?probe=8dd3e52620) | Jul 21, 2022 |
| Biostar       | A320MH                      | Desktop     | [7580882598](https://linux-hardware.org/?probe=7580882598) | Jul 10, 2022 |
| HP            | ProBook 6565b               | Notebook    | [2d35057d85](https://linux-hardware.org/?probe=2d35057d85) | Jul 03, 2022 |
| HP            | ProBook 6565b               | Notebook    | [947c54ac42](https://linux-hardware.org/?probe=947c54ac42) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [58e0a1814b](https://linux-hardware.org/?probe=58e0a1814b) | Apr 21, 2022 |
| Gigabyte      | H110M-S2PT-CF               | Desktop     | [506afdf9c7](https://linux-hardware.org/?probe=506afdf9c7) | Mar 09, 2022 |
| Shuttle       | FZ270                       | Desktop     | [ed3e018227](https://linux-hardware.org/?probe=ed3e018227) | Mar 09, 2022 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [5ac6cdc8fb](https://linux-hardware.org/?probe=5ac6cdc8fb) | Feb 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [bc31f5f2bd](https://linux-hardware.org/?probe=bc31f5f2bd) | Jan 17, 2022 |
| Dell          | 0V8DVD A01                  | All in one  | [1645dd96fd](https://linux-hardware.org/?probe=1645dd96fd) | Jan 04, 2022 |
| HP            | ProBook 6550b               | Notebook    | [c09879cfcd](https://linux-hardware.org/?probe=c09879cfcd) | Dec 15, 2021 |
| HUAWEI        | MRC-WX0                     | Notebook    | [714f759476](https://linux-hardware.org/?probe=714f759476) | Dec 06, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [7dba1540ad](https://linux-hardware.org/?probe=7dba1540ad) | Dec 06, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5dbef9a6a7](https://linux-hardware.org/?probe=5dbef9a6a7) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a2d1a17ff1](https://linux-hardware.org/?probe=a2d1a17ff1) | Nov 09, 2021 |
| Digma         | EVE 10 C301T ES1043EW       | Tablet      | [66c592a074](https://linux-hardware.org/?probe=66c592a074) | Nov 05, 2021 |
| Lenovo        | Yoga Book C930 ZA3S         | Convertible | [6b0d6d003d](https://linux-hardware.org/?probe=6b0d6d003d) | Nov 03, 2021 |
| Lenovo        | Yoga Book C930 ZA3S         | Convertible | [9fd4c9e3a2](https://linux-hardware.org/?probe=9fd4c9e3a2) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de36837a42](https://linux-hardware.org/?probe=de36837a42) | Nov 02, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [fd68d44a6a](https://linux-hardware.org/?probe=fd68d44a6a) | Oct 16, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [409fb80ae5](https://linux-hardware.org/?probe=409fb80ae5) | Sep 10, 2021 |
| Acer          | Aspire V3-111P              | Notebook    | [8c38c04148](https://linux-hardware.org/?probe=8c38c04148) | Sep 05, 2021 |
| Acer          | Aspire V3-111P              | Notebook    | [af61c27b54](https://linux-hardware.org/?probe=af61c27b54) | Sep 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [779374b300](https://linux-hardware.org/?probe=779374b300) | Aug 05, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [13aee77624](https://linux-hardware.org/?probe=13aee77624) | Jun 30, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [19226582d9](https://linux-hardware.org/?probe=19226582d9) | May 31, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [dd4a0707ba](https://linux-hardware.org/?probe=dd4a0707ba) | May 19, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Dell          | 0200DY A01                  | Desktop     | [426fc0381c](https://linux-hardware.org/?probe=426fc0381c) | May 08, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [58fbf7553b](https://linux-hardware.org/?probe=58fbf7553b) | May 03, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [27595787eb](https://linux-hardware.org/?probe=27595787eb) | Apr 26, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ec119e020d](https://linux-hardware.org/?probe=ec119e020d) | Apr 26, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [989604544a](https://linux-hardware.org/?probe=989604544a) | Apr 02, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [1b1d0bc44f](https://linux-hardware.org/?probe=1b1d0bc44f) | Mar 27, 2021 |
| CyberPower... | Tracer Series               | Notebook    | [295977bfa3](https://linux-hardware.org/?probe=295977bfa3) | Mar 24, 2021 |
| HP            | 3048h                       | Desktop     | [b61eb90220](https://linux-hardware.org/?probe=b61eb90220) | Mar 20, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [890d530c6a](https://linux-hardware.org/?probe=890d530c6a) | Mar 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0e8f323e0f](https://linux-hardware.org/?probe=0e8f323e0f) | Mar 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [a949911df6](https://linux-hardware.org/?probe=a949911df6) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4a76fb93d3](https://linux-hardware.org/?probe=4a76fb93d3) | Mar 16, 2021 |
| Dell          | Latitude E6320              | Notebook    | [9439943a67](https://linux-hardware.org/?probe=9439943a67) | Mar 15, 2021 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [926ae13f69](https://linux-hardware.org/?probe=926ae13f69) | Mar 09, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [1f0a994797](https://linux-hardware.org/?probe=1f0a994797) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6c98f8666d](https://linux-hardware.org/?probe=6c98f8666d) | Feb 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [e6476ce804](https://linux-hardware.org/?probe=e6476ce804) | Feb 05, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6042185966](https://linux-hardware.org/?probe=6042185966) | Feb 05, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8c4549fed4](https://linux-hardware.org/?probe=8c4549fed4) | Feb 05, 2021 |
| Dell          | Precision M4600             | Notebook    | [661670d030](https://linux-hardware.org/?probe=661670d030) | Jan 27, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [0bb6c600d0](https://linux-hardware.org/?probe=0bb6c600d0) | Jan 25, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [8289f3c10b](https://linux-hardware.org/?probe=8289f3c10b) | Jan 24, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [cb03a43d6b](https://linux-hardware.org/?probe=cb03a43d6b) | Jan 18, 2021 |
| ASUSTek       | Q87M-E                      | Desktop     | [e95dad9e90](https://linux-hardware.org/?probe=e95dad9e90) | Jan 14, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b07052df59](https://linux-hardware.org/?probe=b07052df59) | Jan 13, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| MSI           | MEG X570 ACE                | Desktop     | [5b061048ce](https://linux-hardware.org/?probe=5b061048ce) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [f50fd232e1](https://linux-hardware.org/?probe=f50fd232e1) | Jan 06, 2021 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ed3e1cc88a](https://linux-hardware.org/?probe=ed3e1cc88a) | Jan 04, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [fb77017d74](https://linux-hardware.org/?probe=fb77017d74) | Jan 04, 2021 |
| ASUSTek       | P8B75-V                     | Desktop     | [a8ba58ce8d](https://linux-hardware.org/?probe=a8ba58ce8d) | Jan 03, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [99c0e6fe8e](https://linux-hardware.org/?probe=99c0e6fe8e) | Jan 03, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [60d4c9b8f1](https://linux-hardware.org/?probe=60d4c9b8f1) | Jan 02, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bab82e261e](https://linux-hardware.org/?probe=bab82e261e) | Jan 02, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [253b9e5126](https://linux-hardware.org/?probe=253b9e5126) | Jan 01, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [016282f72d](https://linux-hardware.org/?probe=016282f72d) | Jan 01, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [45b5f0850b](https://linux-hardware.org/?probe=45b5f0850b) | Dec 30, 2020 |
| HP            | Pavilion g7                 | Notebook    | [4df7168c54](https://linux-hardware.org/?probe=4df7168c54) | Dec 27, 2020 |
| HP            | Pavilion g7                 | Notebook    | [e2b98139df](https://linux-hardware.org/?probe=e2b98139df) | Dec 27, 2020 |
| Acer          | Aspire E5-523               | Notebook    | [ff03816a1e](https://linux-hardware.org/?probe=ff03816a1e) | Dec 16, 2020 |
| Lenovo        | ThinkPad E570 20H50048US    | Notebook    | [db0d5b5a47](https://linux-hardware.org/?probe=db0d5b5a47) | Dec 15, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [c537d4854e](https://linux-hardware.org/?probe=c537d4854e) | Dec 14, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [f1f14b545e](https://linux-hardware.org/?probe=f1f14b545e) | Dec 13, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [d0fc564ec7](https://linux-hardware.org/?probe=d0fc564ec7) | Dec 11, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [c5a5070a6f](https://linux-hardware.org/?probe=c5a5070a6f) | Dec 10, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [f5429557cc](https://linux-hardware.org/?probe=f5429557cc) | Dec 10, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [2385d54def](https://linux-hardware.org/?probe=2385d54def) | Dec 09, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [6ea56336d8](https://linux-hardware.org/?probe=6ea56336d8) | Dec 03, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [a4e4cd792d](https://linux-hardware.org/?probe=a4e4cd792d) | Dec 02, 2020 |
| Lenovo        | IdeaPad Y450                | Notebook    | [a5ec379304](https://linux-hardware.org/?probe=a5ec379304) | Dec 01, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [67aeba9d99](https://linux-hardware.org/?probe=67aeba9d99) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y450                | Notebook    | [300a14fb31](https://linux-hardware.org/?probe=300a14fb31) | Nov 29, 2020 |
| HP            | ProBook 640 G5              | Notebook    | [fc9abd07f4](https://linux-hardware.org/?probe=fc9abd07f4) | Nov 20, 2020 |
| Lenovo        | G470 20078                  | Notebook    | [98c4778da6](https://linux-hardware.org/?probe=98c4778da6) | Nov 18, 2020 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [a135ed4b82](https://linux-hardware.org/?probe=a135ed4b82) | Nov 08, 2020 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [151ca5d99e](https://linux-hardware.org/?probe=151ca5d99e) | Nov 08, 2020 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [9153f43376](https://linux-hardware.org/?probe=9153f43376) | Nov 02, 2020 |
| Gigabyte      | EP43-UD3L                   | Desktop     | [d6fd55eee0](https://linux-hardware.org/?probe=d6fd55eee0) | Nov 01, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [9d695214a4](https://linux-hardware.org/?probe=9d695214a4) | Oct 27, 2020 |
| Lenovo        | ThinkCentre M58 6258WCY     | Desktop     | [a1896b3549](https://linux-hardware.org/?probe=a1896b3549) | Oct 26, 2020 |
| Dell          | Latitude 5500               | Notebook    | [b1f5e9ea7a](https://linux-hardware.org/?probe=b1f5e9ea7a) | Oct 25, 2020 |
| Sony          | VPCEH10EB                   | Notebook    | [167720fe57](https://linux-hardware.org/?probe=167720fe57) | Oct 25, 2020 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [5f4ab6b326](https://linux-hardware.org/?probe=5f4ab6b326) | Oct 18, 2020 |
| Foxconn       | H61S                        | Desktop     | [0fd947c658](https://linux-hardware.org/?probe=0fd947c658) | Oct 12, 2020 |
| Razer         | Blade                       | Notebook    | [14ed46b628](https://linux-hardware.org/?probe=14ed46b628) | Oct 04, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [337abf3073](https://linux-hardware.org/?probe=337abf3073) | Sep 30, 2020 |
| Lenovo        | ThinkPad Edge E431 62775... | Notebook    | [6141f19045](https://linux-hardware.org/?probe=6141f19045) | Sep 17, 2020 |
| Lenovo        | ThinkPad Edge E431 62775... | Notebook    | [a34a40a5ff](https://linux-hardware.org/?probe=a34a40a5ff) | Sep 17, 2020 |
| Dell          | Latitude E6430              | Notebook    | [4fcaaadd6e](https://linux-hardware.org/?probe=4fcaaadd6e) | Sep 12, 2020 |
| Huanan        | X79-8D VAA31                | Desktop     | [e0551a0a1c](https://linux-hardware.org/?probe=e0551a0a1c) | Sep 10, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [69b6d5e2e2](https://linux-hardware.org/?probe=69b6d5e2e2) | Sep 08, 2020 |
| Huanan        | X79-8D VAA31                | Desktop     | [66006c461d](https://linux-hardware.org/?probe=66006c461d) | Sep 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [524f57a765](https://linux-hardware.org/?probe=524f57a765) | Sep 06, 2020 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [3fe15728ad](https://linux-hardware.org/?probe=3fe15728ad) | Sep 06, 2020 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [e3f12cdd9b](https://linux-hardware.org/?probe=e3f12cdd9b) | Sep 05, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [8af1b0565b](https://linux-hardware.org/?probe=8af1b0565b) | Sep 03, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| HP            | 630                         | Notebook    | [baf66f73a2](https://linux-hardware.org/?probe=baf66f73a2) | Aug 14, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [49170a6643](https://linux-hardware.org/?probe=49170a6643) | Aug 12, 2020 |
| HP            | 630                         | Notebook    | [1f0b52b96d](https://linux-hardware.org/?probe=1f0b52b96d) | Aug 12, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [6aae8e8b65](https://linux-hardware.org/?probe=6aae8e8b65) | Aug 12, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [27ed844469](https://linux-hardware.org/?probe=27ed844469) | Aug 08, 2020 |
| MSI           | IONA                        | Desktop     | [0510d0f8ef](https://linux-hardware.org/?probe=0510d0f8ef) | Aug 06, 2020 |
| MSI           | IONA                        | Desktop     | [446e406f22](https://linux-hardware.org/?probe=446e406f22) | Aug 06, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [d40ce43d66](https://linux-hardware.org/?probe=d40ce43d66) | Jul 31, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [9c79ef0e1c](https://linux-hardware.org/?probe=9c79ef0e1c) | Jul 31, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [242b101828](https://linux-hardware.org/?probe=242b101828) | Jul 31, 2020 |
| Toshiba       | Satellite C850-C1S          | Notebook    | [3b431d9c9a](https://linux-hardware.org/?probe=3b431d9c9a) | Jul 31, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [3fea05b48d](https://linux-hardware.org/?probe=3fea05b48d) | Jul 30, 2020 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [52b8fcb9b0](https://linux-hardware.org/?probe=52b8fcb9b0) | Jul 26, 2020 |
| Dell          | Latitude E6430              | Notebook    | [d14e88e089](https://linux-hardware.org/?probe=d14e88e089) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [56cc69c796](https://linux-hardware.org/?probe=56cc69c796) | Jun 27, 2020 |
| Gigabyte      | Z87-HD3                     | Desktop     | [3eff281cc0](https://linux-hardware.org/?probe=3eff281cc0) | Jun 27, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [a1aaa82c04](https://linux-hardware.org/?probe=a1aaa82c04) | Jun 25, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [1bab33423f](https://linux-hardware.org/?probe=1bab33423f) | Jun 25, 2020 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [9db3e10b4f](https://linux-hardware.org/?probe=9db3e10b4f) | Jun 21, 2020 |
| Lenovo        | ThinkPad T510 4349BS9       | Notebook    | [c525e8d7d2](https://linux-hardware.org/?probe=c525e8d7d2) | May 18, 2020 |
| ASUSTek       | UX430UAR                    | Notebook    | [acc88c72e9](https://linux-hardware.org/?probe=acc88c72e9) | May 06, 2020 |
| ASUSTek       | UX430UAR                    | Notebook    | [34b28c7178](https://linux-hardware.org/?probe=34b28c7178) | May 06, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [cd1f7d692d](https://linux-hardware.org/?probe=cd1f7d692d) | May 01, 2020 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [7f1a8c200a](https://linux-hardware.org/?probe=7f1a8c200a) | Apr 26, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [ddff2712b8](https://linux-hardware.org/?probe=ddff2712b8) | Apr 17, 2020 |
| Dell          | G7 7588                     | Notebook    | [68c487eb50](https://linux-hardware.org/?probe=68c487eb50) | Apr 15, 2020 |
| Lenovo        | ThinkPad 10 20C10026UK      | Tablet      | [6460dcf515](https://linux-hardware.org/?probe=6460dcf515) | Apr 13, 2020 |
| Gigabyte      | F2A75-D3H                   | Desktop     | [59a8d5230f](https://linux-hardware.org/?probe=59a8d5230f) | Apr 09, 2020 |
| Pegatron      | 2A99                        | Desktop     | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [c27fa8aa9c](https://linux-hardware.org/?probe=c27fa8aa9c) | Apr 06, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [97ffeec17e](https://linux-hardware.org/?probe=97ffeec17e) | Mar 23, 2020 |
| Dell          | Latitude E6410              | Notebook    | [9d64ff0beb](https://linux-hardware.org/?probe=9d64ff0beb) | Mar 22, 2020 |
| Dell          | Inspiron 5421               | Notebook    | [2d8871e6ac](https://linux-hardware.org/?probe=2d8871e6ac) | Mar 19, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aaac6f9d4d](https://linux-hardware.org/?probe=aaac6f9d4d) | Mar 17, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [63b8db155d](https://linux-hardware.org/?probe=63b8db155d) | Mar 02, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [ed0b979970](https://linux-hardware.org/?probe=ed0b979970) | Mar 01, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [85c6480266](https://linux-hardware.org/?probe=85c6480266) | Mar 01, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [0f180375d6](https://linux-hardware.org/?probe=0f180375d6) | Feb 25, 2020 |
| HP            | Pavilion 17                 | Notebook    | [5d3ccb9ed7](https://linux-hardware.org/?probe=5d3ccb9ed7) | Feb 24, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [55c569be56](https://linux-hardware.org/?probe=55c569be56) | Feb 23, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [98ae2a8227](https://linux-hardware.org/?probe=98ae2a8227) | Feb 22, 2020 |
| HP            | Pavilion dm1                | Notebook    | [e2e4a2c41f](https://linux-hardware.org/?probe=e2e4a2c41f) | Feb 13, 2020 |
| HP            | Pavilion 17                 | Notebook    | [26bdca3832](https://linux-hardware.org/?probe=26bdca3832) | Feb 09, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [48487463eb](https://linux-hardware.org/?probe=48487463eb) | Feb 09, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [b189e00138](https://linux-hardware.org/?probe=b189e00138) | Jan 16, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [ecb6ade802](https://linux-hardware.org/?probe=ecb6ade802) | Jan 16, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [9c202df9eb](https://linux-hardware.org/?probe=9c202df9eb) | Jan 14, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [12d0a26c62](https://linux-hardware.org/?probe=12d0a26c62) | Jan 12, 2020 |
| HP            | Pavilion 17                 | Notebook    | [baeaa7afdc](https://linux-hardware.org/?probe=baeaa7afdc) | Jan 11, 2020 |
| Acer          | Aspire E1-571               | Notebook    | [3b1545354e](https://linux-hardware.org/?probe=3b1545354e) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | Notebook    | [25229b0eaf](https://linux-hardware.org/?probe=25229b0eaf) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | Notebook    | [3d68993148](https://linux-hardware.org/?probe=3d68993148) | Jan 08, 2020 |
| Avell High... | G1550 FOX                   | Notebook    | [b2380e6e7a](https://linux-hardware.org/?probe=b2380e6e7a) | Dec 30, 2019 |
| Intel         | DH55HC AAE70933-501         | Desktop     | [64266b67a2](https://linux-hardware.org/?probe=64266b67a2) | Dec 26, 2019 |
| HP            | 82F2 A01                    | Desktop     | [0b8306e086](https://linux-hardware.org/?probe=0b8306e086) | Nov 18, 2019 |
| Dell          | 0773VG A00                  | Desktop     | [adf2d5daca](https://linux-hardware.org/?probe=adf2d5daca) | Oct 31, 2019 |
| Dell          | 0773VG A00                  | Desktop     | [2f3044da6d](https://linux-hardware.org/?probe=2f3044da6d) | Oct 31, 2019 |
| MSI           | C236A WORKSTATION           | Desktop     | [fcc16b2804](https://linux-hardware.org/?probe=fcc16b2804) | Oct 11, 2019 |
| MSI           | C236A WORKSTATION           | Desktop     | [f68bc503a9](https://linux-hardware.org/?probe=f68bc503a9) | Oct 11, 2019 |
| ASUSTek       | X555YI                      | Notebook    | [728d78c48c](https://linux-hardware.org/?probe=728d78c48c) | Sep 25, 2019 |
| Dell          | Inspiron 5520               | Notebook    | [26951086cf](https://linux-hardware.org/?probe=26951086cf) | Aug 29, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2560a1cb4e](https://linux-hardware.org/?probe=2560a1cb4e) | Aug 28, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b013eab87a](https://linux-hardware.org/?probe=b013eab87a) | Aug 27, 2019 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [81c929f40d](https://linux-hardware.org/?probe=81c929f40d) | Jan 23, 2019 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [2180eb318a](https://linux-hardware.org/?probe=2180eb318a) | Dec 30, 2018 |
| Lenovo        | G570 20079                  | Notebook    | [b1b5baaf85](https://linux-hardware.org/?probe=b1b5baaf85) | Dec 12, 2018 |
| ASRock        | H97M Pro4                   | Desktop     | [2e4984a12a](https://linux-hardware.org/?probe=2e4984a12a) | Nov 27, 2018 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | Desktop     | [812afde3d9](https://linux-hardware.org/?probe=812afde3d9) | Nov 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Reborn OS         | 123       | 80.92%  |
| Reborn OS Rolling | 29        | 19.08%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Reborn OS | 151       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.9.14-arch1-1     | 8         | 4.97%   |
| 5.9.1-arch1-1      | 4         | 2.48%   |
| 5.7.12-arch1-1     | 4         | 2.48%   |
| 5.5.9-arch1-2      | 4         | 2.48%   |
| 5.10.3-arch1-1     | 4         | 2.48%   |
| 5.9.10-arch1-1     | 3         | 1.86%   |
| 5.8.5-arch1-1      | 3         | 1.86%   |
| 5.5.2-arch1-1      | 3         | 1.86%   |
| 5.4.10-arch1-1     | 3         | 1.86%   |
| 6.4.3-arch1-2      | 2         | 1.24%   |
| 6.1.12-arch1-1     | 2         | 1.24%   |
| 5.9.13-arch1-1     | 2         | 1.24%   |
| 5.9.11-arch2-1     | 2         | 1.24%   |
| 5.8.7-arch1-1      | 2         | 1.24%   |
| 5.7.11-arch1-1     | 2         | 1.24%   |
| 5.7.10-arch1-1     | 2         | 1.24%   |
| 5.6.4-arch1-1      | 2         | 1.24%   |
| 5.6.3-arch1-1      | 2         | 1.24%   |
| 5.2.9-arch1-1-ARCH | 2         | 1.24%   |
| 5.16.9-arch1-1     | 2         | 1.24%   |
| 5.16.12-arch1-1    | 2         | 1.24%   |
| 5.14.16-arch1-1    | 2         | 1.24%   |
| 5.11.7-arch1-1     | 2         | 1.24%   |
| 5.11.6-arch1-1     | 2         | 1.24%   |
| 5.11.1-arch1-1     | 2         | 1.24%   |
| 5.10.4-arch2-1     | 2         | 1.24%   |
| 5.10.13-arch1-1    | 2         | 1.24%   |
| 6.4.9-arch1-1      | 1         | 0.62%   |
| 6.3.9-arch1-1      | 1         | 0.62%   |
| 6.3.4-arch1-1      | 1         | 0.62%   |
| 6.3.3-arch1-1      | 1         | 0.62%   |
| 6.2.8-arch1-1      | 1         | 0.62%   |
| 6.2.7-arch1-1      | 1         | 0.62%   |
| 6.2.6-arch1-1      | 1         | 0.62%   |
| 6.2.2-zen1-1-zen   | 1         | 0.62%   |
| 6.2.2-arch1-1      | 1         | 0.62%   |
| 6.1.7-arch1-1      | 1         | 0.62%   |
| 6.1.33-1-lts       | 1         | 0.62%   |
| 6.0.8-arch1-1      | 1         | 0.62%   |
| 6.0.6-arch1-1      | 1         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 8         | 5%      |
| 5.9.10  | 4         | 2.5%    |
| 5.9.1   | 4         | 2.5%    |
| 5.7.12  | 4         | 2.5%    |
| 5.5.9   | 4         | 2.5%    |
| 5.10.3  | 4         | 2.5%    |
| 5.8.5   | 3         | 1.88%   |
| 5.5.2   | 3         | 1.88%   |
| 5.4.10  | 3         | 1.88%   |
| 6.4.3   | 2         | 1.25%   |
| 6.2.2   | 2         | 1.25%   |
| 6.1.12  | 2         | 1.25%   |
| 5.9.2   | 2         | 1.25%   |
| 5.9.13  | 2         | 1.25%   |
| 5.9.11  | 2         | 1.25%   |
| 5.8.7   | 2         | 1.25%   |
| 5.7.6   | 2         | 1.25%   |
| 5.7.11  | 2         | 1.25%   |
| 5.7.10  | 2         | 1.25%   |
| 5.6.4   | 2         | 1.25%   |
| 5.6.3   | 2         | 1.25%   |
| 5.2.9   | 2         | 1.25%   |
| 5.16.9  | 2         | 1.25%   |
| 5.16.12 | 2         | 1.25%   |
| 5.14.16 | 2         | 1.25%   |
| 5.11.7  | 2         | 1.25%   |
| 5.11.6  | 2         | 1.25%   |
| 5.11.11 | 2         | 1.25%   |
| 5.11.1  | 2         | 1.25%   |
| 5.10.4  | 2         | 1.25%   |
| 5.10.13 | 2         | 1.25%   |
| 6.4.9   | 1         | 0.63%   |
| 6.3.9   | 1         | 0.63%   |
| 6.3.4   | 1         | 0.63%   |
| 6.3.3   | 1         | 0.63%   |
| 6.2.8   | 1         | 0.63%   |
| 6.2.7   | 1         | 0.63%   |
| 6.2.6   | 1         | 0.63%   |
| 6.1.7   | 1         | 0.63%   |
| 6.1.33  | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9     | 25        | 15.82%  |
| 5.10    | 17        | 10.76%  |
| 5.7     | 12        | 7.59%   |
| 5.8     | 11        | 6.96%   |
| 5.11    | 11        | 6.96%   |
| 5.5     | 9         | 5.7%    |
| 5.6     | 8         | 5.06%   |
| 5.4     | 8         | 5.06%   |
| 6.2     | 5         | 3.16%   |
| 5.16    | 5         | 3.16%   |
| 5.14    | 5         | 3.16%   |
| 6.1     | 4         | 2.53%   |
| 5.3     | 4         | 2.53%   |
| 5.19    | 4         | 2.53%   |
| 5.15    | 4         | 2.53%   |
| 5.12    | 4         | 2.53%   |
| 4.19    | 4         | 2.53%   |
| 6.4     | 3         | 1.9%    |
| 6.3     | 3         | 1.9%    |
| 6.0     | 3         | 1.9%    |
| 5.18    | 3         | 1.9%    |
| 5.2     | 2         | 1.27%   |
| 5.13    | 2         | 1.27%   |
| 4.20    | 1         | 0.63%   |
| 4.18    | 1         | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 150       | 99.34%  |
| aarch64 | 1         | 0.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 30        | 19.74%  |
| KDE5              | 23        | 15.13%  |
| XFCE              | 18        | 11.84%  |
| X-Cinnamon        | 18        | 11.84%  |
| KDE               | 17        | 11.18%  |
| Deepin            | 16        | 10.53%  |
| Unknown           | 10        | 6.58%   |
| Budgie            | 7         | 4.61%   |
| LXQt              | 4         | 2.63%   |
| MATE              | 3         | 1.97%   |
| i3                | 3         | 1.97%   |
| Yaru:ubuntu:GNOME | 1         | 0.66%   |
| Enlightenment     | 1         | 0.66%   |
| Cinnamon          | 1         | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 123       | 80.92%  |
| Wayland | 28        | 18.42%  |
| Tty     | 1         | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 119       | 77.78%  |
| LightDM | 13        | 8.5%    |
| SDDM    | 11        | 7.19%   |
| TDM     | 6         | 3.92%   |
| GDM     | 3         | 1.96%   |
| XDM     | 1         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 56        | 37.09%  |
| de_DE   | 13        | 8.61%   |
| Unknown | 11        | 7.28%   |
| pt_BR   | 9         | 5.96%   |
| en_GB   | 9         | 5.96%   |
| en_AU   | 8         | 5.3%    |
| es_ES   | 7         | 4.64%   |
| ru_RU   | 5         | 3.31%   |
| es_MX   | 4         | 2.65%   |
| en_CA   | 4         | 2.65%   |
| pl_PL   | 2         | 1.32%   |
| nl_NL   | 2         | 1.32%   |
| es_AR   | 2         | 1.32%   |
| en_AG   | 2         | 1.32%   |
| tr_TR   | 1         | 0.66%   |
| sv_SE   | 1         | 0.66%   |
| ru_UA   | 1         | 0.66%   |
| pt_PT   | 1         | 0.66%   |
| it_IT   | 1         | 0.66%   |
| fr_FR   | 1         | 0.66%   |
| fr_BE   | 1         | 0.66%   |
| fi_FI   | 1         | 0.66%   |
| es_PA   | 1         | 0.66%   |
| es_CL   | 1         | 0.66%   |
| en_PH   | 1         | 0.66%   |
| en_DK   | 1         | 0.66%   |
| el_GR   | 1         | 0.66%   |
| de_CH   | 1         | 0.66%   |
| de_AT   | 1         | 0.66%   |
| cs_CZ   | 1         | 0.66%   |
| C       | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 103       | 67.32%  |
| EFI  | 50        | 32.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 114       | 75%     |
| Unknown | 12        | 7.89%   |
| Btrfs   | 11        | 7.24%   |
| Tmpfs   | 10        | 6.58%   |
| Xfs     | 3         | 1.97%   |
| Overlay | 1         | 0.66%   |
| Ext3    | 1         | 0.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 119       | 78.29%  |
| GPT     | 29        | 19.08%  |
| MBR     | 4         | 2.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 141       | 93.38%  |
| Yes       | 10        | 6.62%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 135       | 88.82%  |
| Yes       | 17        | 11.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 29        | 19.21%  |
| ASUSTek Computer       | 24        | 15.89%  |
| Dell                   | 23        | 15.23%  |
| Hewlett-Packard        | 21        | 13.91%  |
| Gigabyte Technology    | 9         | 5.96%   |
| Acer                   | 9         | 5.96%   |
| ASRock                 | 7         | 4.64%   |
| MSI                    | 6         | 3.97%   |
| Pegatron               | 2         | 1.32%   |
| Medion                 | 2         | 1.32%   |
| Avell High Performance | 2         | 1.32%   |
| Toshiba                | 1         | 0.66%   |
| Timi                   | 1         | 0.66%   |
| Sony                   | 1         | 0.66%   |
| Shuttle                | 1         | 0.66%   |
| Razer                  | 1         | 0.66%   |
| Radxa                  | 1         | 0.66%   |
| OEM                    | 1         | 0.66%   |
| Microsoft              | 1         | 0.66%   |
| Intel                  | 1         | 0.66%   |
| HUAWEI                 | 1         | 0.66%   |
| Huanan                 | 1         | 0.66%   |
| Foxconn                | 1         | 0.66%   |
| Digma                  | 1         | 0.66%   |
| CyberPowerPC           | 1         | 0.66%   |
| Chuwi                  | 1         | 0.66%   |
| Biostar                | 1         | 0.66%   |
| BESSTAR Tech           | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo IdeaPad 1 14IGL05 81VU             | 3         | 1.99%   |
| Dell Inspiron 5520                        | 3         | 1.99%   |
| MSI MS-7721                               | 2         | 1.32%   |
| Dell Latitude E6430                       | 2         | 1.32%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA    | 2         | 1.32%   |
| ASRock X570 Phantom Gaming 4              | 2         | 1.32%   |
| Toshiba Satellite C850-C1S                | 1         | 0.66%   |
| Timi A35S                                 | 1         | 0.66%   |
| Sony VPCEH10EB                            | 1         | 0.66%   |
| Shuttle SZ270                             | 1         | 0.66%   |
| Razer Blade                               | 1         | 0.66%   |
| Radxa ROCK 5B                             | 1         | 0.66%   |
| Pegatron Elite 7500 Series MT             | 1         | 0.66%   |
| Pegatron CQ3476L                          | 1         | 0.66%   |
| OEM G41 775 ICH7 8712                     | 1         | 0.66%   |
| MSI WK711AA-ACB HPE-110ru                 | 1         | 0.66%   |
| MSI MS-7C35                               | 1         | 0.66%   |
| MSI MS-7A36                               | 1         | 0.66%   |
| MSI MS-7998                               | 1         | 0.66%   |
| Microsoft Surface Pro 4                   | 1         | 0.66%   |
| Medion X6816                              | 1         | 0.66%   |
| Medion P961x                              | 1         | 0.66%   |
| Lenovo Z70-80 80FG                        | 1         | 0.66%   |
| Lenovo Yoga Book C930 ZA3S                | 1         | 0.66%   |
| Lenovo Y50-70 20378                       | 1         | 0.66%   |
| Lenovo ThinkPad X13 Yoga Gen 2 20W8001TUS | 1         | 0.66%   |
| Lenovo ThinkPad T510 4349BS9              | 1         | 0.66%   |
| Lenovo ThinkPad T440p 20AWS0Y800          | 1         | 0.66%   |
| Lenovo ThinkPad T410 253725G              | 1         | 0.66%   |
| Lenovo ThinkPad Edge E431 62775AU         | 1         | 0.66%   |
| Lenovo ThinkPad E570 20H50048US           | 1         | 0.66%   |
| Lenovo ThinkPad E490 20N8CTO1WW           | 1         | 0.66%   |
| Lenovo ThinkPad 10 20C10026UK             | 1         | 0.66%   |
| Lenovo ThinkCentre M92 32071F5            | 1         | 0.66%   |
| Lenovo ThinkCentre M91p 0266RZ1           | 1         | 0.66%   |
| Lenovo ThinkCentre M75q-1 11A4001WUS      | 1         | 0.66%   |
| Lenovo ThinkCentre M715q 10VGCTO1WW       | 1         | 0.66%   |
| Lenovo ThinkCentre M58 6258WCY            | 1         | 0.66%   |
| Lenovo IdeaPad Y580                       | 1         | 0.66%   |
| Lenovo IdeaPad Y450                       | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 11        | 7.28%   |
| Lenovo ThinkPad    | 8         | 5.3%    |
| HP Pavilion        | 7         | 4.64%   |
| Acer Aspire        | 7         | 4.64%   |
| Dell Latitude      | 6         | 3.97%   |
| Dell Inspiron      | 6         | 3.97%   |
| ASUS PRIME         | 6         | 3.97%   |
| Lenovo ThinkCentre | 5         | 3.31%   |
| Dell OptiPlex      | 5         | 3.31%   |
| ASUS ROG           | 4         | 2.65%   |
| HP ProBook         | 3         | 1.99%   |
| HP EliteBook       | 3         | 1.99%   |
| ASRock X570        | 3         | 1.99%   |
| MSI MS-7721        | 2         | 1.32%   |
| HP EliteDesk       | 2         | 1.32%   |
| Dell XPS           | 2         | 1.32%   |
| ASUS VivoBook      | 2         | 1.32%   |
| Toshiba Satellite  | 1         | 0.66%   |
| Timi A35S          | 1         | 0.66%   |
| Sony VPCEH10EB     | 1         | 0.66%   |
| Shuttle SZ270      | 1         | 0.66%   |
| Razer Blade        | 1         | 0.66%   |
| Radxa ROCK         | 1         | 0.66%   |
| Pegatron Elite     | 1         | 0.66%   |
| Pegatron CQ3476L   | 1         | 0.66%   |
| OEM G41            | 1         | 0.66%   |
| MSI WK711AA-ACB    | 1         | 0.66%   |
| MSI MS-7C35        | 1         | 0.66%   |
| MSI MS-7A36        | 1         | 0.66%   |
| MSI MS-7998        | 1         | 0.66%   |
| Microsoft Surface  | 1         | 0.66%   |
| Medion X6816       | 1         | 0.66%   |
| Medion P961x       | 1         | 0.66%   |
| Lenovo Z70-80      | 1         | 0.66%   |
| Lenovo Yoga        | 1         | 0.66%   |
| Lenovo Y50-70      | 1         | 0.66%   |
| Lenovo G570        | 1         | 0.66%   |
| Lenovo G470        | 1         | 0.66%   |
| Intel DH55HC       | 1         | 0.66%   |
| HUAWEI MRC-WX0     | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 20        | 13.25%  |
| 2012    | 18        | 11.92%  |
| 2018    | 16        | 10.6%   |
| 2013    | 13        | 8.61%   |
| 2011    | 13        | 8.61%   |
| 2020    | 12        | 7.95%   |
| 2016    | 10        | 6.62%   |
| 2009    | 10        | 6.62%   |
| 2014    | 8         | 5.3%    |
| 2010    | 8         | 5.3%    |
| 2021    | 6         | 3.97%   |
| 2017    | 5         | 3.31%   |
| 2015    | 5         | 3.31%   |
| 2022    | 3         | 1.99%   |
| 2008    | 2         | 1.32%   |
| 2023    | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 72        | 47.68%  |
| Desktop        | 66        | 43.71%  |
| Convertible    | 4         | 2.65%   |
| Tablet         | 3         | 1.99%   |
| All in one     | 3         | 1.99%   |
| Mini pc        | 2         | 1.32%   |
| System on chip | 1         | 0.66%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 151       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 151       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 49        | 32.03%  |
| 8.01-16.0   | 35        | 22.88%  |
| 16.01-24.0  | 32        | 20.92%  |
| 3.01-4.0    | 19        | 12.42%  |
| 32.01-64.0  | 14        | 9.15%   |
| 64.01-256.0 | 2         | 1.31%   |
| 2.01-3.0    | 1         | 0.65%   |
| 1.01-2.0    | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 63        | 39.62%  |
| 2.01-3.0  | 48        | 30.19%  |
| 4.01-8.0  | 18        | 11.32%  |
| 3.01-4.0  | 18        | 11.32%  |
| 0.51-1.0  | 7         | 4.4%    |
| 8.01-16.0 | 5         | 3.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 88        | 57.14%  |
| 2      | 41        | 26.62%  |
| 3      | 11        | 7.14%   |
| 4      | 9         | 5.84%   |
| 0      | 2         | 1.3%    |
| 7      | 1         | 0.65%   |
| 6      | 1         | 0.65%   |
| 5      | 1         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 57.89%  |
| Yes       | 64        | 42.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 84.77%  |
| No        | 23        | 15.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 77.48%  |
| No        | 34        | 22.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 56.95%  |
| No        | 65        | 43.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 40        | 26.49%  |
| Germany     | 16        | 10.6%   |
| Brazil      | 11        | 7.28%   |
| Spain       | 8         | 5.3%    |
| UK          | 7         | 4.64%   |
| Canada      | 7         | 4.64%   |
| Russia      | 6         | 3.97%   |
| Australia   | 6         | 3.97%   |
| Netherlands | 5         | 3.31%   |
| Mexico      | 4         | 2.65%   |
| Turkey      | 3         | 1.99%   |
| Thailand    | 2         | 1.32%   |
| Portugal    | 2         | 1.32%   |
| Poland      | 2         | 1.32%   |
| Panama      | 2         | 1.32%   |
| India       | 2         | 1.32%   |
| Greece      | 2         | 1.32%   |
| Estonia     | 2         | 1.32%   |
| Austria     | 2         | 1.32%   |
| Argentina   | 2         | 1.32%   |
| Ukraine     | 1         | 0.66%   |
| UAE         | 1         | 0.66%   |
| Switzerland | 1         | 0.66%   |
| Sweden      | 1         | 0.66%   |
| Philippines | 1         | 0.66%   |
| Malaysia    | 1         | 0.66%   |
| Italy       | 1         | 0.66%   |
| Ireland     | 1         | 0.66%   |
| Hungary     | 1         | 0.66%   |
| Finland     | 1         | 0.66%   |
| Egypt       | 1         | 0.66%   |
| Czechia     | 1         | 0.66%   |
| Costa Rica  | 1         | 0.66%   |
| Colombia    | 1         | 0.66%   |
| Chile       | 1         | 0.66%   |
| Bulgaria    | 1         | 0.66%   |
| Benin       | 1         | 0.66%   |
| Belgium     | 1         | 0.66%   |
| Barbados    | 1         | 0.66%   |
| Azerbaijan  | 1         | 0.66%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 3         | 1.91%   |
| Melbourne         | 3         | 1.91%   |
| Aleksandrov       | 3         | 1.91%   |
| Tres Cantos       | 2         | 1.27%   |
| Toronto           | 2         | 1.27%   |
| Tallinn           | 2         | 1.27%   |
| Santa Clara       | 2         | 1.27%   |
| Miami             | 2         | 1.27%   |
| Mexico City       | 2         | 1.27%   |
| Lelystad          | 2         | 1.27%   |
| Cupertino         | 2         | 1.27%   |
| Cologne           | 2         | 1.27%   |
| Buffalo           | 2         | 1.27%   |
| Athens            | 2         | 1.27%   |
| Zutphen           | 1         | 0.64%   |
| Zabrze            | 1         | 0.64%   |
| Yadrin            | 1         | 0.64%   |
| Wuppertal         | 1         | 0.64%   |
| Winsted           | 1         | 0.64%   |
| Weil im Schonbuch | 1         | 0.64%   |
| Watford           | 1         | 0.64%   |
| Warsaw            | 1         | 0.64%   |
| Villahermosa      | 1         | 0.64%   |
| Verwood           | 1         | 0.64%   |
| Toledo            | 1         | 0.64%   |
| The Hague         | 1         | 0.64%   |
| Szekszárd        | 1         | 0.64%   |
| Sydney            | 1         | 0.64%   |
| Surrey            | 1         | 0.64%   |
| Stuttgart         | 1         | 0.64%   |
| Streatham         | 1         | 0.64%   |
| St Louis          | 1         | 0.64%   |
| Spremberg         | 1         | 0.64%   |
| Southampton       | 1         | 0.64%   |
| Smithfield        | 1         | 0.64%   |
| Silverton         | 1         | 0.64%   |
| Si Racha          | 1         | 0.64%   |
| Seville           | 1         | 0.64%   |
| Santiago          | 1         | 0.64%   |
| Sankt Pölten     | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 42        | 50     | 18.1%   |
| Samsung Electronics       | 36        | 44     | 15.52%  |
| Seagate                   | 30        | 38     | 12.93%  |
| Toshiba                   | 17        | 19     | 7.33%   |
| Unknown                   | 13        | 15     | 5.6%    |
| Kingston                  | 11        | 12     | 4.74%   |
| SanDisk                   | 10        | 12     | 4.31%   |
| Crucial                   | 9         | 10     | 3.88%   |
| Hitachi                   | 7         | 7      | 3.02%   |
| Phison                    | 6         | 7      | 2.59%   |
| Intel                     | 5         | 5      | 2.16%   |
| HGST                      | 5         | 5      | 2.16%   |
| SK hynix                  | 3         | 3      | 1.29%   |
| Phison Electronics        | 3         | 4      | 1.29%   |
| ZOTAC                     | 2         | 2      | 0.86%   |
| Transcend                 | 2         | 2      | 0.86%   |
| SPCC                      | 2         | 3      | 0.86%   |
| PNY                       | 2         | 2      | 0.86%   |
| Patriot                   | 2         | 2      | 0.86%   |
| Micron Technology         | 2         | 2      | 0.86%   |
| KIOXIA                    | 2         | 2      | 0.86%   |
| Emtec                     | 2         | 3      | 0.86%   |
| Dell                      | 2         | 2      | 0.86%   |
| XPG                       | 1         | 1      | 0.43%   |
| OYUNKEY                   | 1         | 1      | 0.43%   |
| OCZ                       | 1         | 2      | 0.43%   |
| Netac                     | 1         | 1      | 0.43%   |
| Micron/Crucial Technology | 1         | 1      | 0.43%   |
| LITEONIT                  | 1         | 1      | 0.43%   |
| KingSpec                  | 1         | 1      | 0.43%   |
| JMicron Technology        | 1         | 1      | 0.43%   |
| Hewlett-Packard           | 1         | 2      | 0.43%   |
| Gigabyte Technology       | 1         | 2      | 0.43%   |
| Drevo                     | 1         | 1      | 0.43%   |
| ASMT                      | 1         | 1      | 0.43%   |
| AMD                       | 1         | 1      | 0.43%   |
| addlink                   | 1         | 1      | 0.43%   |
| ADATA Technology          | 1         | 1      | 0.43%   |
| A-DATA Technology         | 1         | 1      | 0.43%   |
| Unknown                   | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 6         | 2.38%   |
| Samsung SSD 860 EVO 500GB          | 4         | 1.59%   |
| Intel NVMe SSD Drive 512GB         | 4         | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 1.19%   |
| Kingston SA400S37480G 480GB SSD    | 3         | 1.19%   |
| HGST HTS725050A7E630 500GB         | 3         | 1.19%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.79%   |
| WDC WD10JPVT-08A1YT2 1TB           | 2         | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 0.79%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 2         | 0.79%   |
| WDC WD1001FALS-403AA0 1TB          | 2         | 0.79%   |
| Unknown SD/MMC/MS PRO 128GB        | 2         | 0.79%   |
| Toshiba NVMe SSD Drive 512GB       | 2         | 0.79%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.79%   |
| SK hynix NVMe SSD Drive 256GB      | 2         | 0.79%   |
| Seagate ST9500325AS 500GB          | 2         | 0.79%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.79%   |
| Seagate ST3500312CS 500GB          | 2         | 0.79%   |
| Seagate ST2000DM006-2DM164 2TB     | 2         | 0.79%   |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 0.79%   |
| Seagate Expansion Desk 8TB         | 2         | 0.79%   |
| Samsung SSD 850 EVO 500GB          | 2         | 0.79%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.79%   |
| Samsung NVMe SSD Drive 512GB       | 2         | 0.79%   |
| Samsung NVMe SSD Drive 500GB       | 2         | 0.79%   |
| PNY CS900 120GB SSD                | 2         | 0.79%   |
| Phison NVMe SSD Drive 960GB        | 2         | 0.79%   |
| Phison NVMe SSD Drive 240GB        | 2         | 0.79%   |
| Phison NVMe SSD Drive 1TB          | 2         | 0.79%   |
| Crucial CT1000MX500SSD1 1TB        | 2         | 0.79%   |
| ZOTAC ZTSSD-S11-120G-P 120GB       | 1         | 0.4%    |
| ZOTAC ZTSSD-A4P-120G               | 1         | 0.4%    |
| XPG NVMe SSD Drive 1TB             | 1         | 0.4%    |
| WDC WDS500G2X0C-00L350 500GB       | 1         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.4%    |
| WDC WDS100T3X0C-00SJG0 1TB         | 1         | 0.4%    |
| WDC WD7500LPCX-60HWST0 752GB       | 1         | 0.4%    |
| WDC WD6400AAKS-22A7B0 640GB        | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 37        | 44     | 38.54%  |
| Seagate             | 30        | 38     | 31.25%  |
| Toshiba             | 9         | 10     | 9.38%   |
| Hitachi             | 7         | 7      | 7.29%   |
| HGST                | 5         | 5      | 5.21%   |
| Samsung Electronics | 4         | 4      | 4.17%   |
| Unknown             | 2         | 2      | 2.08%   |
| JMicron Technology  | 1         | 1      | 1.04%   |
| ASMT                | 1         | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 25     | 30.56%  |
| Kingston            | 11        | 12     | 15.28%  |
| Crucial             | 8         | 9      | 11.11%  |
| SanDisk             | 7         | 9      | 9.72%   |
| WDC                 | 3         | 3      | 4.17%   |
| ZOTAC               | 2         | 2      | 2.78%   |
| Transcend           | 2         | 2      | 2.78%   |
| Toshiba             | 2         | 2      | 2.78%   |
| PNY                 | 2         | 2      | 2.78%   |
| Patriot             | 2         | 2      | 2.78%   |
| SPCC                | 1         | 2      | 1.39%   |
| OCZ                 | 1         | 2      | 1.39%   |
| Netac               | 1         | 1      | 1.39%   |
| LITEONIT            | 1         | 1      | 1.39%   |
| KingSpec            | 1         | 1      | 1.39%   |
| Hewlett-Packard     | 1         | 2      | 1.39%   |
| Gigabyte Technology | 1         | 2      | 1.39%   |
| Emtec               | 1         | 1      | 1.39%   |
| Drevo               | 1         | 1      | 1.39%   |
| AMD                 | 1         | 1      | 1.39%   |
| A-DATA Technology   | 1         | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 78        | 112    | 38.42%  |
| SSD     | 63        | 83     | 31.03%  |
| NVMe    | 47        | 57     | 23.15%  |
| MMC     | 10        | 13     | 4.93%   |
| Unknown | 5         | 6      | 2.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 117       | 189    | 63.93%  |
| NVMe | 47        | 57     | 25.68%  |
| MMC  | 10        | 13     | 5.46%   |
| SAS  | 9         | 12     | 4.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 86        | 112    | 56.21%  |
| 0.51-1.0   | 52        | 63     | 33.99%  |
| 1.01-2.0   | 7         | 10     | 4.58%   |
| 2.01-3.0   | 4         | 5      | 2.61%   |
| 4.01-10.0  | 3         | 4      | 1.96%   |
| 3.01-4.0   | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 43        | 27.74%  |
| 101-250        | 36        | 23.23%  |
| 501-1000       | 29        | 18.71%  |
| 1001-2000      | 12        | 7.74%   |
| 51-100         | 12        | 7.74%   |
| More than 3000 | 9         | 5.81%   |
| Unknown        | 7         | 4.52%   |
| 21-50          | 3         | 1.94%   |
| 2001-3000      | 3         | 1.94%   |
| 1-20           | 1         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 54        | 33.75%  |
| 21-50          | 39        | 24.38%  |
| 101-250        | 19        | 11.88%  |
| 51-100         | 18        | 11.25%  |
| 251-500        | 10        | 6.25%   |
| 501-1000       | 8         | 5%      |
| Unknown        | 7         | 4.38%   |
| 2001-3000      | 3         | 1.88%   |
| More than 3000 | 1         | 0.63%   |
| 1001-2000      | 1         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500DM009-2F110A 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 126       | 219    | 81.29%  |
| Works    | 28        | 51     | 18.06%  |
| Malfunc  | 1         | 1      | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 96        | 50.79%  |
| AMD                          | 42        | 22.22%  |
| Samsung Electronics          | 13        | 6.88%   |
| Phison Electronics           | 10        | 5.29%   |
| Toshiba America Info Systems | 6         | 3.17%   |
| SanDisk                      | 5         | 2.65%   |
| SK hynix                     | 3         | 1.59%   |
| JMicron Technology           | 3         | 1.59%   |
| ADATA Technology             | 3         | 1.59%   |
| Micron/Crucial Technology    | 2         | 1.06%   |
| Micron Technology            | 2         | 1.06%   |
| KIOXIA                       | 2         | 1.06%   |
| Nvidia                       | 1         | 0.53%   |
| ASMedia Technology           | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 36        | 16.22%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 9         | 4.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7         | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 3.15%   |
| Phison E12 NVMe Controller                                                              | 6         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 2.7%    |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 2.25%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 2.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 2.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 2.25%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.8%    |
| Samsung NVMe SSD Controller 980                                                         | 3         | 1.35%   |
| Intel SSD 660P Series                                                                   | 3         | 1.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.35%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 1.35%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.9%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2         | 0.9%    |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.9%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.9%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 0.9%    |
| JMicron JMB368 IDE controller                                                           | 2         | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 0.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 0.9%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 0.9%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2         | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 0.9%    |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2         | 0.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 2         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 2         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 116       | 61.05%  |
| NVMe | 46        | 24.21%  |
| IDE  | 21        | 11.05%  |
| RAID | 7         | 3.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 104       | 68.87%  |
| AMD    | 46        | 30.46%  |
| ARM    | 1         | 0.66%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.63%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 4         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.97%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.97%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.97%   |
| Intel Core i7-6700T CPU @ 2.80GHz             | 2         | 1.32%   |
| Intel Core i7-4770S CPU @ 3.10GHz             | 2         | 1.32%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 1.32%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.32%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.32%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.32%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.32%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 1.32%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.32%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.32%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 1.32%   |
| AMD A4-5300 APU with Radeon HD Graphics       | 2         | 1.32%   |
| AMD A10-5800K APU with Radeon HD Graphics     | 2         | 1.32%   |
| Intel Xeon CPU E5530 @ 2.40GHz                | 1         | 0.66%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz           | 1         | 0.66%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz           | 1         | 0.66%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz           | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.66%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.66%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1         | 0.66%   |
| Intel Pentium CPU G3258 @ 3.20GHz             | 1         | 0.66%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.66%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.66%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.66%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.66%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.66%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.66%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 38        | 25%     |
| Intel Core i7           | 29        | 19.08%  |
| AMD Ryzen 5             | 13        | 8.55%   |
| Intel Core i3           | 8         | 5.26%   |
| Intel Core 2 Duo        | 8         | 5.26%   |
| Intel Celeron           | 8         | 5.26%   |
| AMD Ryzen 7             | 8         | 5.26%   |
| Other                   | 4         | 2.63%   |
| Intel Xeon              | 4         | 2.63%   |
| Intel Pentium           | 4         | 2.63%   |
| AMD FX                  | 3         | 1.97%   |
| AMD A4                  | 3         | 1.97%   |
| Intel Pentium Dual-Core | 2         | 1.32%   |
| AMD Ryzen 9             | 2         | 1.32%   |
| AMD Ryzen 5 PRO         | 2         | 1.32%   |
| AMD Ryzen 3             | 2         | 1.32%   |
| AMD A8                  | 2         | 1.32%   |
| AMD A6                  | 2         | 1.32%   |
| AMD A10                 | 2         | 1.32%   |
| Intel Core m3           | 1         | 0.66%   |
| Intel Atom              | 1         | 0.66%   |
| AMD Ryzen 7 PRO         | 1         | 0.66%   |
| AMD PRO A10             | 1         | 0.66%   |
| AMD Phenom II X4        | 1         | 0.66%   |
| AMD E                   | 1         | 0.66%   |
| AMD Athlon II X2        | 1         | 0.66%   |
| AMD A12                 | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 60        | 39.74%  |
| 2      | 59        | 39.07%  |
| 6      | 16        | 10.6%   |
| 8      | 9         | 5.96%   |
| 1      | 3         | 1.99%   |
| 24     | 1         | 0.66%   |
| 16     | 1         | 0.66%   |
| 12     | 1         | 0.66%   |
| 3      | 1         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 148       | 98.01%  |
| 2      | 3         | 1.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 104       | 68.87%  |
| 1      | 47        | 31.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 141       | 93.38%  |
| Unknown        | 10        | 6.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 33.12%  |
| 0x306a9    | 11        | 7.14%   |
| 0x206a7    | 9         | 5.84%   |
| 0x306c3    | 7         | 4.55%   |
| 0x506e3    | 5         | 3.25%   |
| 0x0800820d | 5         | 3.25%   |
| 0x906ea    | 4         | 2.6%    |
| 0x1067a    | 4         | 2.6%    |
| 0x06001119 | 4         | 2.6%    |
| 0x906e9    | 3         | 1.95%   |
| 0x806eb    | 3         | 1.95%   |
| 0x806e9    | 3         | 1.95%   |
| 0x20652    | 3         | 1.95%   |
| 0x08108109 | 3         | 1.95%   |
| 0x806ec    | 2         | 1.3%    |
| 0x40651    | 2         | 1.3%    |
| 0x20655    | 2         | 1.3%    |
| 0x106e5    | 2         | 1.3%    |
| 0x07030106 | 2         | 1.3%    |
| 0x806ea    | 1         | 0.65%   |
| 0x806d1    | 1         | 0.65%   |
| 0x6fb      | 1         | 0.65%   |
| 0x406e3    | 1         | 0.65%   |
| 0x406c3    | 1         | 0.65%   |
| 0x306e4    | 1         | 0.65%   |
| 0x306d4    | 1         | 0.65%   |
| 0x30678    | 1         | 0.65%   |
| 0x106a5    | 1         | 0.65%   |
| 0x10676    | 1         | 0.65%   |
| 0x0a601203 | 1         | 0.65%   |
| 0x0a50000d | 1         | 0.65%   |
| 0x0a50000c | 1         | 0.65%   |
| 0x0a20120a | 1         | 0.65%   |
| 0x0a201016 | 1         | 0.65%   |
| 0x0a201009 | 1         | 0.65%   |
| 0x08701021 | 1         | 0.65%   |
| 0x08600102 | 1         | 0.65%   |
| 0x0810100b | 1         | 0.65%   |
| 0x08001138 | 1         | 0.65%   |
| 0x06006704 | 1         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 15.23%  |
| IvyBridge     | 17        | 11.26%  |
| SandyBridge   | 14        | 9.27%   |
| Zen+          | 13        | 8.61%   |
| Haswell       | 12        | 7.95%   |
| Skylake       | 8         | 5.3%    |
| Penryn        | 8         | 5.3%    |
| Zen 3         | 6         | 3.97%   |
| Westmere      | 6         | 3.97%   |
| Piledriver    | 6         | 3.97%   |
| Zen 2         | 5         | 3.31%   |
| Goldmont plus | 4         | 2.65%   |
| Excavator     | 4         | 2.65%   |
| Zen           | 3         | 1.99%   |
| Silvermont    | 3         | 1.99%   |
| Puma          | 3         | 1.99%   |
| Nehalem       | 3         | 1.99%   |
| K10           | 2         | 1.32%   |
| Unknown       | 2         | 1.32%   |
| TigerLake     | 1         | 0.66%   |
| Steamroller   | 1         | 0.66%   |
| K10 Llano     | 1         | 0.66%   |
| Icelake       | 1         | 0.66%   |
| Goldmont      | 1         | 0.66%   |
| Core          | 1         | 0.66%   |
| CometLake     | 1         | 0.66%   |
| Broadwell     | 1         | 0.66%   |
| Bobcat        | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 77        | 43.75%  |
| AMD               | 50        | 28.41%  |
| Nvidia            | 48        | 27.27%  |
| ASPEED Technology | 1         | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 13        | 7.18%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 9         | 4.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7         | 3.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 6         | 3.31%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 2.21%   |
| Intel UHD Graphics 620                                                      | 4         | 2.21%   |
| Intel HD Graphics 530                                                       | 4         | 2.21%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 2.21%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 2.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4         | 2.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 2.21%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.66%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3         | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 3         | 1.66%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 3         | 1.66%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                   | 3         | 1.66%   |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 1.1%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 1.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.1%    |
| Intel HD Graphics 620                                                       | 2         | 1.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 1.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.1%    |
| AMD Trinity [Radeon HD 7660D]                                               | 2         | 1.1%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 2         | 1.1%    |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2         | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.55%   |
| Nvidia TU117M                                                               | 1         | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.55%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                     | 1         | 0.55%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1         | 0.55%   |
| Nvidia GT218M [NVS 3100M]                                                   | 1         | 0.55%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.55%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.55%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.55%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1         | 0.55%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 1         | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 35.1%   |
| 1 x AMD        | 41        | 27.15%  |
| 1 x Nvidia     | 29        | 19.21%  |
| Intel + Nvidia | 16        | 10.6%   |
| Intel + AMD    | 5         | 3.31%   |
| 2 x AMD        | 2         | 1.32%   |
| AMD + Nvidia   | 2         | 1.32%   |
| Other          | 1         | 0.66%   |
| 3 x Nvidia     | 1         | 0.66%   |
| 1 x ASPEED     | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 128       | 84.21%  |
| Proprietary | 22        | 14.47%  |
| Unknown     | 2         | 1.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 58.55%  |
| 0.51-1.0   | 16        | 10.53%  |
| 1.01-2.0   | 12        | 7.89%   |
| 0.01-0.5   | 12        | 7.89%   |
| 7.01-8.0   | 8         | 5.26%   |
| 3.01-4.0   | 7         | 4.61%   |
| 8.01-16.0  | 4         | 2.63%   |
| 2.01-3.0   | 2         | 1.32%   |
| 5.01-6.0   | 1         | 0.66%   |
| 16.01-24.0 | 1         | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 25        | 15.43%  |
| AU Optronics            | 25        | 15.43%  |
| LG Display              | 18        | 11.11%  |
| Hewlett-Packard         | 13        | 8.02%   |
| BOE                     | 9         | 5.56%   |
| Dell                    | 8         | 4.94%   |
| Chimei Innolux          | 8         | 4.94%   |
| Goldstar                | 7         | 4.32%   |
| BenQ                    | 6         | 3.7%    |
| Acer                    | 6         | 3.7%    |
| Philips                 | 4         | 2.47%   |
| Chi Mei Optoelectronics | 4         | 2.47%   |
| AOC                     | 3         | 1.85%   |
| Ancor Communications    | 3         | 1.85%   |
| Sony                    | 2         | 1.23%   |
| Sharp                   | 2         | 1.23%   |
| MSI                     | 2         | 1.23%   |
| Lenovo                  | 2         | 1.23%   |
| Vizio                   | 1         | 0.62%   |
| Vestel                  | 1         | 0.62%   |
| Unknown                 | 1         | 0.62%   |
| Sceptre Tech            | 1         | 0.62%   |
| Plain Tree Systems      | 1         | 0.62%   |
| ONN                     | 1         | 0.62%   |
| MStar                   | 1         | 0.62%   |
| Microstep               | 1         | 0.62%   |
| Medion                  | 1         | 0.62%   |
| InfoVision              | 1         | 0.62%   |
| Iiyama                  | 1         | 0.62%   |
| Hitachi                 | 1         | 0.62%   |
| GRM                     | 1         | 0.62%   |
| CSO                     | 1         | 0.62%   |
| ASUSTek Computer        | 1         | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 2.34%   |
| Hewlett-Packard 27ea HPN3395 1920x1080 527x296mm 23.8-inch               | 3         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 1.75%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 3         | 1.75%   |
| Samsung Electronics SA300/SA350 SAM0791 1920x1080 510x287mm 23.0-inch    | 2         | 1.17%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                   | 2         | 1.17%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 1.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 1.17%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 1.17%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                    | 1         | 0.58%   |
| Vestel LCD Monitor 32W_LCD_TV                                            | 1         | 0.58%   |
| Unknown LCD Monitor DAC Moniter 5760x1080                                | 1         | 0.58%   |
| Sony TV SNYF301 1920x1080                                                | 1         | 0.58%   |
| Sony TV *00 SNY7105 3840x2160 1218x685mm 55.0-inch                       | 1         | 0.58%   |
| Sharp LQ156M1JW08 SHP14D4 1920x1080 344x194mm 15.5-inch                  | 1         | 0.58%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 1         | 0.58%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 698x393mm 31.5-inch           | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch     | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch     | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch      | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch     | 1         | 0.58%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch        | 1         | 0.58%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch    | 1         | 0.58%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1         | 0.58%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch        | 1         | 0.58%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch        | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch     | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC5744 1920x1080 344x194mm 15.5-inch    | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC464C 1366x768 309x174mm 14.0-inch     | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch    | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch    | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch    | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch    | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0297 1360x768 885x498mm 40.0-inch     | 1         | 0.58%   |
| Samsung Electronics LCD Monitor S24D300 1920x1080                        | 1         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 39.62%  |
| 1366x768 (WXGA)    | 39        | 24.53%  |
| 3840x2160 (4K)     | 11        | 6.92%   |
| 1600x900 (HD+)     | 9         | 5.66%   |
| 1680x1050 (WSXGA+) | 7         | 4.4%    |
| 1440x900 (WXGA+)   | 5         | 3.14%   |
| 1280x1024 (SXGA)   | 4         | 2.52%   |
| Unknown            | 4         | 2.52%   |
| 1920x1200 (WUXGA)  | 3         | 1.89%   |
| 7680x2160          | 2         | 1.26%   |
| 3440x1440          | 2         | 1.26%   |
| 2560x1440 (QHD)    | 2         | 1.26%   |
| 1360x768           | 2         | 1.26%   |
| 5760x1080          | 1         | 0.63%   |
| 3840x1200          | 1         | 0.63%   |
| 3456x2160          | 1         | 0.63%   |
| 2736x1824          | 1         | 0.63%   |
| 2560x1600          | 1         | 0.63%   |
| 2160x1440          | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 41        | 25%     |
| 14      | 14        | 8.54%   |
| 23      | 13        | 7.93%   |
| 21      | 11        | 6.71%   |
| 24      | 10        | 6.1%    |
| 17      | 9         | 5.49%   |
| 13      | 9         | 5.49%   |
| Unknown | 9         | 5.49%   |
| 27      | 8         | 4.88%   |
| 22      | 6         | 3.66%   |
| 19      | 6         | 3.66%   |
| 18      | 4         | 2.44%   |
| 84      | 2         | 1.22%   |
| 54      | 2         | 1.22%   |
| 34      | 2         | 1.22%   |
| 31      | 2         | 1.22%   |
| 20      | 2         | 1.22%   |
| 11      | 2         | 1.22%   |
| 72      | 1         | 0.61%   |
| 65      | 1         | 0.61%   |
| 52      | 1         | 0.61%   |
| 49      | 1         | 0.61%   |
| 46      | 1         | 0.61%   |
| 40      | 1         | 0.61%   |
| 36      | 1         | 0.61%   |
| 33      | 1         | 0.61%   |
| 28      | 1         | 0.61%   |
| 16      | 1         | 0.61%   |
| 12      | 1         | 0.61%   |
| 10      | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 61        | 37.65%  |
| 501-600     | 28        | 17.28%  |
| 401-500     | 26        | 16.05%  |
| 351-400     | 11        | 6.79%   |
| 201-300     | 9         | 5.56%   |
| Unknown     | 9         | 5.56%   |
| 1001-1500   | 6         | 3.7%    |
| 701-800     | 4         | 2.47%   |
| 601-700     | 4         | 2.47%   |
| 1501-2000   | 3         | 1.85%   |
| 801-900     | 1         | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 119       | 78.29%  |
| 16/10   | 16        | 10.53%  |
| Unknown | 9         | 5.92%   |
| 5/4     | 4         | 2.63%   |
| 3/2     | 2         | 1.32%   |
| 21/9    | 2         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 25.63%  |
| 201-250        | 34        | 21.25%  |
| 81-90          | 19        | 11.88%  |
| 151-200        | 10        | 6.25%   |
| Unknown        | 9         | 5.63%   |
| More than 1000 | 8         | 5%      |
| 301-350        | 8         | 5%      |
| 121-130        | 8         | 5%      |
| 351-500        | 5         | 3.13%   |
| 141-150        | 5         | 3.13%   |
| 71-80          | 4         | 2.5%    |
| 501-1000       | 3         | 1.88%   |
| 51-60          | 2         | 1.25%   |
| 61-70          | 1         | 0.63%   |
| 41-50          | 1         | 0.63%   |
| 251-300        | 1         | 0.63%   |
| 111-120        | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 54        | 33.33%  |
| 101-120       | 50        | 30.86%  |
| 121-160       | 32        | 19.75%  |
| Unknown       | 9         | 5.56%   |
| 1-50          | 7         | 4.32%   |
| 161-240       | 6         | 3.7%    |
| More than 240 | 4         | 2.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 130       | 85.53%  |
| 2     | 18        | 11.84%  |
| 0     | 3         | 1.97%   |
| 3     | 1         | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 85        | 37.95%  |
| Intel                             | 73        | 32.59%  |
| Qualcomm Atheros                  | 27        | 12.05%  |
| Broadcom                          | 9         | 4.02%   |
| Ralink Technology                 | 4         | 1.79%   |
| TP-Link                           | 3         | 1.34%   |
| Microsoft                         | 3         | 1.34%   |
| Huawei Technologies               | 3         | 1.34%   |
| Xiaomi                            | 2         | 0.89%   |
| Ralink                            | 2         | 0.89%   |
| Spreadtrum Communications         | 1         | 0.45%   |
| Sierra Wireless                   | 1         | 0.45%   |
| Samsung Electronics               | 1         | 0.45%   |
| Qualcomm Atheros Communications   | 1         | 0.45%   |
| Nvidia                            | 1         | 0.45%   |
| NetXen Incorporated               | 1         | 0.45%   |
| MediaTek                          | 1         | 0.45%   |
| Marvell Technology Group          | 1         | 0.45%   |
| Ericsson Business Mobile Networks | 1         | 0.45%   |
| DisplayLink                       | 1         | 0.45%   |
| Dell                              | 1         | 0.45%   |
| Broadcom Limited                  | 1         | 0.45%   |
| Belkin Components                 | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57        | 21.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 4.17%   |
| Intel I211 Gigabit Network Connection                             | 10        | 3.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.79%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 3.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.89%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 1.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.52%   |
| Intel Wireless-AC 9260                                            | 4         | 1.52%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.14%   |
| Intel Wireless 7265                                               | 3         | 1.14%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 3         | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.14%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.14%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.14%   |
| Huawei E353/E3131                                                 | 3         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.14%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.76%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.76%   |
| Ralink RT5572 Wireless Adapter                                    | 2         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.76%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.76%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 51        | 41.46%  |
| Realtek Semiconductor             | 24        | 19.51%  |
| Qualcomm Atheros                  | 24        | 19.51%  |
| Broadcom                          | 6         | 4.88%   |
| Ralink Technology                 | 4         | 3.25%   |
| TP-Link                           | 3         | 2.44%   |
| Ralink                            | 2         | 1.63%   |
| Microsoft                         | 2         | 1.63%   |
| Sierra Wireless                   | 1         | 0.81%   |
| Qualcomm Atheros Communications   | 1         | 0.81%   |
| MediaTek                          | 1         | 0.81%   |
| Marvell Technology Group          | 1         | 0.81%   |
| Ericsson Business Mobile Networks | 1         | 0.81%   |
| Broadcom Limited                  | 1         | 0.81%   |
| Belkin Components                 | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 7.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 4.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 4.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 4.03%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 4.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 3.23%   |
| Intel Wireless-AC 9260                                         | 4         | 3.23%   |
| Intel Wireless 8265 / 8275                                     | 4         | 3.23%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 2.42%   |
| Intel Wireless 7265                                            | 3         | 2.42%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 2.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 2.42%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 2.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2         | 1.61%   |
| Ralink RT5572 Wireless Adapter                                 | 2         | 1.61%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.61%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.61%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1         | 0.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.81%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 1         | 0.81%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.81%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.81%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.81%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.81%   |
| Realtek 802.11ac NIC                                           | 1         | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.81%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                           | 1         | 0.81%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 73        | 53.28%  |
| Intel                     | 44        | 32.12%  |
| Qualcomm Atheros          | 7         | 5.11%   |
| Huawei Technologies       | 3         | 2.19%   |
| Broadcom                  | 3         | 2.19%   |
| Xiaomi                    | 2         | 1.46%   |
| Spreadtrum Communications | 1         | 0.73%   |
| Nvidia                    | 1         | 0.73%   |
| NetXen Incorporated       | 1         | 0.73%   |
| Microsoft                 | 1         | 0.73%   |
| DisplayLink               | 1         | 0.73%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 57        | 41.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 11        | 7.97%   |
| Intel I211 Gigabit Network Connection                                | 10        | 7.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 10        | 7.25%   |
| Intel Ethernet Connection I217-LM                                    | 5         | 3.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 3         | 2.17%   |
| Intel 82577LM Gigabit Network Connection                             | 3         | 2.17%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 3         | 2.17%   |
| Huawei E353/E3131                                                    | 3         | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                    | 2         | 1.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 2         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 2         | 1.45%   |
| Intel Ethernet Controller I225-V                                     | 2         | 1.45%   |
| Intel Ethernet Connection (2) I219-V                                 | 2         | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                 | 1         | 0.72%   |
| Spreadtrum Spreadtrum Phone                                          | 1         | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 1         | 0.72%   |
| Nvidia MCP61 Ethernet                                                | 1         | 0.72%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 0.72%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                    | 1         | 0.72%   |
| Intel Ethernet Connection I217-V                                     | 1         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                                 | 1         | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 0.72%   |
| Intel Ethernet Connection (2) I218-V                                 | 1         | 0.72%   |
| Intel 82579V Gigabit Network Connection                              | 1         | 0.72%   |
| Intel 82578DC Gigabit Network Connection                             | 1         | 0.72%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 0.72%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 0.72%   |
| DisplayLink Dell Universal Dock D6000                                | 1         | 0.72%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                    | 1         | 0.72%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                      | 1         | 0.72%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                      | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 128       | 51.82%  |
| WiFi     | 117       | 47.37%  |
| Modem    | 2         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 78        | 50.32%  |
| WiFi     | 77        | 49.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 77        | 50.99%  |
| 1     | 65        | 43.05%  |
| 3     | 4         | 2.65%   |
| 0     | 4         | 2.65%   |
| 6     | 1         | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 133       | 87.5%   |
| Yes  | 19        | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 45.35%  |
| Realtek Semiconductor           | 10        | 11.63%  |
| Cambridge Silicon Radio         | 8         | 9.3%    |
| Qualcomm Atheros Communications | 6         | 6.98%   |
| Lite-On Technology              | 5         | 5.81%   |
| IMC Networks                    | 3         | 3.49%   |
| Dell                            | 3         | 3.49%   |
| Broadcom                        | 3         | 3.49%   |
| Hewlett-Packard                 | 2         | 2.33%   |
| Foxconn / Hon Hai               | 2         | 2.33%   |
| ASUSTek Computer                | 2         | 2.33%   |
| MediaTek                        | 1         | 1.16%   |
| Marvell Semiconductor           | 1         | 1.16%   |
| Foxconn International           | 1         | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 10.47%  |
| Intel AX200 Bluetooth                               | 9         | 10.47%  |
| Realtek Bluetooth Radio                             | 8         | 9.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 9.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 6.98%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 4.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 4.65%   |
| Intel AX201 Bluetooth                               | 4         | 4.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 3.49%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.33%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.33%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 2.33%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.16%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.16%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.16%   |
| MediaTek Wireless_Device                            | 1         | 1.16%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.16%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 1.16%   |
| Lite-On BCM43142A0                                  | 1         | 1.16%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.16%   |
| Intel AX210 Bluetooth                               | 1         | 1.16%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.16%   |
| IMC Networks Bluetooth Module                       | 1         | 1.16%   |
| IMC Networks Bluetooth Device                       | 1         | 1.16%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.16%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.16%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.16%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.16%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.16%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.16%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.16%   |
| ASUS BCM20702A0                                     | 1         | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 102       | 47.44%  |
| AMD                    | 54        | 25.12%  |
| Nvidia                 | 39        | 18.14%  |
| C-Media Electronics    | 5         | 2.33%   |
| Logitech               | 2         | 0.93%   |
| JMTek                  | 2         | 0.93%   |
| GN Netcom              | 2         | 0.93%   |
| Sony                   | 1         | 0.47%   |
| Plantronics            | 1         | 0.47%   |
| Microsoft              | 1         | 0.47%   |
| Generalplus Technology | 1         | 0.47%   |
| Focusrite-Novation     | 1         | 0.47%   |
| Creative Labs          | 1         | 0.47%   |
| Blue Microphones       | 1         | 0.47%   |
| ASUSTek Computer       | 1         | 0.47%   |
| Alesis                 | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 5%      |
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 3.46%   |
| AMD FCH Azalia Controller                                                  | 9         | 3.46%   |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 3.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 3.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 3.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 3.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 2.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 2.31%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 2.31%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 2.31%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 1.92%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 1.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 1.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.54%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.54%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.54%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 1.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 1.15%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 1.15%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3         | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.77%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.77%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.77%   |
| JMTek USB PnP Audio Device                                                 | 2         | 0.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.77%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 0.77%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 0.77%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 17.5%   |
| SK hynix            | 6         | 15%     |
| Micron Technology   | 6         | 15%     |
| Kingston            | 5         | 12.5%   |
| Unknown             | 3         | 7.5%    |
| Crucial             | 3         | 7.5%    |
| Corsair             | 3         | 7.5%    |
| Team                | 2         | 5%      |
| Unknown (ABCD)      | 1         | 2.5%    |
| Smart               | 1         | 2.5%    |
| Ramaxel Technology  | 1         | 2.5%    |
| PNY                 | 1         | 2.5%    |
| G.Skill             | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 2         | 4.55%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 2.27%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 2.27%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 2.27%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.27%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 1         | 2.27%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.27%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.27%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 2.27%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.27%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.27%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 1         | 2.27%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.27%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 2.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 2.27%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 2.27%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s              | 1         | 2.27%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s              | 1         | 2.27%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.27%   |
| Samsung RAM K3QF3F30BM-AGCF 2GB Row Of Chips LPDDR3 1867MT/s     | 1         | 2.27%   |
| Ramaxel RAM RMT1970ED48E8F1066 2048MB SODIMM DDR3 1067MT/s       | 1         | 2.27%   |
| PNY RAM 8GBU1X08QJLL42-12-K 8GB SODIMM DDR4 3200MT/s             | 1         | 2.27%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 2.27%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.27%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 2.27%   |
| Micron RAM 4ATF11G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s      | 1         | 2.27%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 2.27%   |
| Micron RAM 16ATF1G64AZ-2G1A2 8GB DIMM DDR4 2400MT/s              | 1         | 2.27%   |
| Kingston RAM Module 8GB DIMM DDR4 2667MT/s                       | 1         | 2.27%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                | 1         | 2.27%   |
| Kingston RAM HX426C16FB2/8 8GB DIMM DDR4 2667MT/s                | 1         | 2.27%   |
| Kingston RAM 99P5471-002.A00LF 2GB DIMM DDR3 1600MT/s            | 1         | 2.27%   |
| Kingston RAM 99P5471-001.A01LF 2GB DIMM DDR3 1333MT/s            | 1         | 2.27%   |
| Kingston RAM 99P5471-001.A00LF 2GB DIMM DDR3 1333MT/s            | 1         | 2.27%   |
| Kingston RAM 9905584-023.A00LF 4096MB DIMM DDR3 1600MT/s         | 1         | 2.27%   |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 3600MT/s              | 1         | 2.27%   |
| Crucial RAM CT8G4SFD8213.C16FHP 8192MB SODIMM DDR4 2133MT/s      | 1         | 2.27%   |
| Crucial RAM BLT4G3D1869DT 4096MB DIMM DDR3 1333MT/s              | 1         | 2.27%   |
| Crucial RAM BL16G36C16U4W.M16FE1 16384MB DIMM DDR4 3733MT/s      | 1         | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 19        | 52.78%  |
| DDR3    | 10        | 27.78%  |
| LPDDR4  | 2         | 5.56%   |
| LPDDR3  | 2         | 5.56%   |
| SDRAM   | 1         | 2.78%   |
| DDR5    | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 50%     |
| DIMM         | 13        | 38.24%  |
| Row Of Chips | 4         | 11.76%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 20        | 52.63%  |
| 4096  | 7         | 18.42%  |
| 2048  | 5         | 13.16%  |
| 32768 | 3         | 7.89%   |
| 16384 | 3         | 7.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 8         | 20%     |
| 2667  | 8         | 20%     |
| 1600  | 8         | 20%     |
| 2400  | 3         | 7.5%    |
| 2133  | 2         | 5%      |
| 1867  | 2         | 5%      |
| 1333  | 2         | 5%      |
| 6400  | 1         | 2.5%    |
| 3733  | 1         | 2.5%    |
| 3600  | 1         | 2.5%    |
| 3500  | 1         | 2.5%    |
| 3000  | 1         | 2.5%    |
| 1067  | 1         | 2.5%    |
| 800   | 1         | 2.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 50%     |
| Canon           | 2         | 33.33%  |
| Seiko Epson     | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L120 Series            | 1         | 16.67%  |
| HP LaserJet 1300                   | 1         | 16.67%  |
| HP DeskJet 3830 series             | 1         | 16.67%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 16.67%  |
| Canon PIXMA MX920 Series           | 1         | 16.67%  |
| Canon PIXMA MG2500 Series          | 1         | 16.67%  |

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
| Chicony Electronics                    | 18        | 20%     |
| Microdia                               | 15        | 16.67%  |
| Realtek Semiconductor                  | 8         | 8.89%   |
| IMC Networks                           | 8         | 8.89%   |
| Logitech                               | 5         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 5.56%   |
| Acer                                   | 5         | 5.56%   |
| Syntek                                 | 3         | 3.33%   |
| Suyin                                  | 3         | 3.33%   |
| Sunplus Innovation Technology          | 2         | 2.22%   |
| Samsung Electronics                    | 2         | 2.22%   |
| Quanta                                 | 2         | 2.22%   |
| Generalplus Technology                 | 2         | 2.22%   |
| Bison Electronics                      | 2         | 2.22%   |
| Alcor Micro                            | 2         | 2.22%   |
| Z-Star Microelectronics                | 1         | 1.11%   |
| Ricoh                                  | 1         | 1.11%   |
| Lite-On Technology                     | 1         | 1.11%   |
| Lenovo                                 | 1         | 1.11%   |
| KYE Systems (Mouse Systems)            | 1         | 1.11%   |
| GEMBIRD                                | 1         | 1.11%   |
| Cubeternet                             | 1         | 1.11%   |
| 2M UVC CAMERA                          | 1         | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                                          | 5         | 5.56%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 4.44%   |
| Chicony Integrated Camera                                                  | 4         | 4.44%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                     | 3         | 3.33%   |
| Logitech HD Pro Webcam C920                                                | 3         | 3.33%   |
| Acer EasyCamera                                                            | 3         | 3.33%   |
| Syntek Integrated Camera                                                   | 2         | 2.22%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 2.22%   |
| IMC Networks Integrated Camera                                             | 2         | 2.22%   |
| Generalplus 808 Camera #9 (web-cam mode)                                   | 2         | 2.22%   |
| Chicony Integrated HP HD Webcam                                            | 2         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 2.22%   |
| Z-Star Venus USB2.0 Camera                                                 | 1         | 1.11%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.11%   |
| Suyin Sony Visual Communication Camera                                     | 1         | 1.11%   |
| Suyin Lenovo EasyCamera                                                    | 1         | 1.11%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 1.11%   |
| Sunplus USB 2.0 Camera                                                     | 1         | 1.11%   |
| Sunplus HD WebCam                                                          | 1         | 1.11%   |
| Ricoh HD Webcam                                                            | 1         | 1.11%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 1.11%   |
| Realtek USB Camera                                                         | 1         | 1.11%   |
| Realtek Laptop_Integrated_Webcam_HD                                        | 1         | 1.11%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.11%   |
| Realtek HP Wide Vision FHD Camera                                          | 1         | 1.11%   |
| Realtek HP Truevision HD                                                   | 1         | 1.11%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 1.11%   |
| Realtek HD WebCam                                                          | 1         | 1.11%   |
| Quanta hm1091_techfront                                                    | 1         | 1.11%   |
| Quanta HD User Facing                                                      | 1         | 1.11%   |
| Microdia Webcam Vitade AF                                                  | 1         | 1.11%   |
| Microdia USB 2.0 Camera                                                    | 1         | 1.11%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 1         | 1.11%   |
| Microdia Laptop Integrated Webcam HD (Composite Device)                    | 1         | 1.11%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 1.11%   |
| Microdia Front camera                                                      | 1         | 1.11%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 1         | 1.11%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.11%   |
| Logitech Webcam C110                                                       | 1         | 1.11%   |
| Logitech C922 Pro Stream Webcam                                            | 1         | 1.11%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 8         | 53.33%  |
| Synaptics             | 4         | 26.67%  |
| Elan Microelectronics | 2         | 13.33%  |
| Upek                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 20%     |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 13.33%  |
| Elan ELAN:Fingerprint                                  | 2         | 13.33%  |
| Validity Sensors VFS491                                | 1         | 6.67%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.67%   |
| Synaptics WBDI Fingerprint Reader USB 102              | 1         | 6.67%   |
| Synaptics UWP WBDI Device                              | 1         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 6.67%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 50%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 108       | 71.52%  |
| 1     | 37        | 24.5%   |
| 2     | 6         | 3.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 30.61%  |
| Net/wireless             | 12        | 24.49%  |
| Graphics card            | 6         | 12.24%  |
| Chipcard                 | 6         | 12.24%  |
| Multimedia controller    | 5         | 10.2%   |
| Storage                  | 2         | 4.08%   |
| Tv card                  | 1         | 2.04%   |
| Communication controller | 1         | 2.04%   |
| Camera                   | 1         | 2.04%   |

