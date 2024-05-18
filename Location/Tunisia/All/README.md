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

Total: 332

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 43        | 18.38%  |
| Ubuntu 22.04        | 21        | 8.97%   |
| Ubuntu 18.04        | 17        | 7.26%   |
| Ubuntu 21.10        | 6         | 2.56%   |
| OpenMandriva 4.2    | 6         | 2.56%   |
| Pop!_OS 22.04       | 5         | 2.14%   |
| OpenMandriva 23.08  | 5         | 2.14%   |
| Linux Mint 21.2     | 5         | 2.14%   |
| OpenMandriva 4.3    | 4         | 1.71%   |
| OpenMandriva 23.03  | 4         | 1.71%   |
| KDE neon 22.04      | 4         | 1.71%   |
| Fedora 38           | 4         | 1.71%   |
| Debian 12           | 4         | 1.71%   |
| Debian 11           | 4         | 1.71%   |
| Arch Rolling        | 4         | 1.71%   |
| Zorin 16            | 3         | 1.28%   |
| Zorin 15            | 3         | 1.28%   |
| Ubuntu 19.10        | 3         | 1.28%   |
| Ubuntu 16.04        | 3         | 1.28%   |
| Linux Mint 21.1     | 3         | 1.28%   |
| KDE neon 20.04      | 3         | 1.28%   |
| Debian 10           | 3         | 1.28%   |
| ArcoLinux Rolling   | 3         | 1.28%   |
| Ubuntu 21.04        | 2         | 0.85%   |
| Ubuntu 20.10        | 2         | 0.85%   |
| ROSA R10            | 2         | 0.85%   |
| ROSA 12.3           | 2         | 0.85%   |
| Pop!_OS 21.04       | 2         | 0.85%   |
| OpenMandriva 23.07  | 2         | 0.85%   |
| Manjaro 21.1.0      | 2         | 0.85%   |
| LMDE 4              | 2         | 0.85%   |
| Linux Mint 21       | 2         | 0.85%   |
| Linux Mint 20.3     | 2         | 0.85%   |
| Linux Mint 20.2     | 2         | 0.85%   |
| Linux Mint 20       | 2         | 0.85%   |
| Gentoo 2.8          | 2         | 0.85%   |
| Gentoo 2.7          | 2         | 0.85%   |
| Fedora 35           | 2         | 0.85%   |
| Fedora 33           | 2         | 0.85%   |
| EndeavourOS Rolling | 2         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 92        | 41.07%  |
| OpenMandriva | 22        | 9.82%   |
| Linux Mint   | 18        | 8.04%   |
| Debian       | 12        | 5.36%   |
| Fedora       | 9         | 4.02%   |
| Pop!_OS      | 8         | 3.57%   |
| Zorin        | 6         | 2.68%   |
| ROSA         | 6         | 2.68%   |
| Manjaro      | 6         | 2.68%   |
| Arch         | 6         | 2.68%   |
| KDE neon     | 5         | 2.23%   |
| Endless      | 4         | 1.79%   |
| Kali         | 3         | 1.34%   |
| Gentoo       | 3         | 1.34%   |
| ArcoLinux    | 3         | 1.34%   |
| Lubuntu      | 2         | 0.89%   |
| LMDE         | 2         | 0.89%   |
| EndeavourOS  | 2         | 0.89%   |
| Elementary   | 2         | 0.89%   |
| Xubuntu      | 1         | 0.45%   |
| Xero         | 1         | 0.45%   |
| Ubuntu Unity | 1         | 0.45%   |
| TUXEDO OS    | 1         | 0.45%   |
| SteamOS      | 1         | 0.45%   |
| Sodalite     | 1         | 0.45%   |
| Nobara       | 1         | 0.45%   |
| MX           | 1         | 0.45%   |
| Kubuntu      | 1         | 0.45%   |
| Garuda Linux | 1         | 0.45%   |
| Devuan       | 1         | 0.45%   |
| Deepin       | 1         | 0.45%   |
| BlackPanther | 1         | 0.45%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 6         | 2.33%   |
| 6.4.11-desktop-1omv2390         | 5         | 1.94%   |
| 5.15.0-58-generic               | 5         | 1.94%   |
| 6.2.6-desktop-1omv2390          | 4         | 1.55%   |
| 5.16.7-desktop-1omv4003         | 4         | 1.55%   |
| 5.15.0-52-generic               | 4         | 1.55%   |
| 5.15.0-46-generic               | 4         | 1.55%   |
| 5.13.0-28-generic               | 4         | 1.55%   |
| 6.2.0-36-generic                | 3         | 1.16%   |
| 5.3.0-46-generic                | 3         | 1.16%   |
| 5.3.0-40-generic                | 3         | 1.16%   |
| 5.15.0-56-generic               | 3         | 1.16%   |
| 5.15.0-53-generic               | 3         | 1.16%   |
| 5.15.0-43-generic               | 3         | 1.16%   |
| 5.11.0-38-generic               | 3         | 1.16%   |
| 5.11.0-27-generic               | 3         | 1.16%   |
| 6.3.5-desktop-3omv2390          | 2         | 0.78%   |
| 5.8.0-38-generic                | 2         | 0.78%   |
| 5.8.0-14-generic                | 2         | 0.78%   |
| 5.4.0-72-generic                | 2         | 0.78%   |
| 5.4.0-58-generic                | 2         | 0.78%   |
| 5.4.0-52-generic                | 2         | 0.78%   |
| 5.4.0-42-generic                | 2         | 0.78%   |
| 5.4.0-26-generic                | 2         | 0.78%   |
| 5.3.0-28-generic                | 2         | 0.78%   |
| 5.19.0-45-generic               | 2         | 0.78%   |
| 5.15.84-v8+                     | 2         | 0.78%   |
| 5.15.0-47-generic               | 2         | 0.78%   |
| 5.15.0-41-generic               | 2         | 0.78%   |
| 5.13.0-44-generic               | 2         | 0.78%   |
| 5.13.0-40-generic               | 2         | 0.78%   |
| 5.13.0-39-generic               | 2         | 0.78%   |
| 5.11.0-7620-generic             | 2         | 0.78%   |
| 5.11.0-40-generic               | 2         | 0.78%   |
| 5.10.27-gentoo                  | 2         | 0.78%   |
| 5.10.0-12-amd64                 | 2         | 0.78%   |
| 5.0.0-25-generic                | 2         | 0.78%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.78%   |
| 4.19.0-6-amd64                  | 2         | 0.78%   |
| 4.15.0-91-generic               | 2         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 35        | 14.23%  |
| 5.4.0   | 26        | 10.57%  |
| 5.13.0  | 16        | 6.5%    |
| 5.11.0  | 13        | 5.28%   |
| 5.8.0   | 11        | 4.47%   |
| 5.3.0   | 11        | 4.47%   |
| 4.15.0  | 10        | 4.07%   |
| 5.19.0  | 9         | 3.66%   |
| 5.0.0   | 7         | 2.85%   |
| 5.10.14 | 6         | 2.44%   |
| 6.4.11  | 5         | 2.03%   |
| 6.2.0   | 5         | 2.03%   |
| 4.19.0  | 5         | 2.03%   |
| 6.5.0   | 4         | 1.63%   |
| 6.2.6   | 4         | 1.63%   |
| 6.1.0   | 4         | 1.63%   |
| 5.16.7  | 4         | 1.63%   |
| 6.3.5   | 3         | 1.22%   |
| 5.10.0  | 3         | 1.22%   |
| 4.18.0  | 3         | 1.22%   |
| 6.5.7   | 2         | 0.81%   |
| 6.3.6   | 2         | 0.81%   |
| 5.18.0  | 2         | 0.81%   |
| 5.17.5  | 2         | 0.81%   |
| 5.15.84 | 2         | 0.81%   |
| 5.15.75 | 2         | 0.81%   |
| 5.10.27 | 2         | 0.81%   |
| 4.9.60  | 2         | 0.81%   |
| 6.8.2   | 1         | 0.41%   |
| 6.8.1   | 1         | 0.41%   |
| 6.8.0   | 1         | 0.41%   |
| 6.6.9   | 1         | 0.41%   |
| 6.6.22  | 1         | 0.41%   |
| 6.6.2   | 1         | 0.41%   |
| 6.5.8   | 1         | 0.41%   |
| 6.5.6   | 1         | 0.41%   |
| 6.4.12  | 1         | 0.41%   |
| 6.2.9   | 1         | 0.41%   |
| 6.2.5   | 1         | 0.41%   |
| 6.2.11  | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 43        | 17.99%  |
| 5.4     | 28        | 11.72%  |
| 5.13    | 17        | 7.11%   |
| 5.11    | 15        | 6.28%   |
| 5.10    | 13        | 5.44%   |
| 6.2     | 12        | 5.02%   |
| 5.8     | 12        | 5.02%   |
| 5.3     | 12        | 5.02%   |
| 5.19    | 10        | 4.18%   |
| 4.15    | 10        | 4.18%   |
| 6.5     | 8         | 3.35%   |
| 6.1     | 7         | 2.93%   |
| 5.0     | 7         | 2.93%   |
| 6.4     | 6         | 2.51%   |
| 5.16    | 6         | 2.51%   |
| 6.3     | 5         | 2.09%   |
| 4.19    | 5         | 2.09%   |
| 6.6     | 3         | 1.26%   |
| 5.17    | 3         | 1.26%   |
| 4.9     | 3         | 1.26%   |
| 4.18    | 3         | 1.26%   |
| 6.8     | 2         | 0.84%   |
| 5.9     | 2         | 0.84%   |
| 5.18    | 2         | 0.84%   |
| 5.6     | 1         | 0.42%   |
| 5.14    | 1         | 0.42%   |
| 5.12    | 1         | 0.42%   |
| 4.4     | 1         | 0.42%   |
| 3.13    | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 212       | 97.7%   |
| i686    | 3         | 1.38%   |
| aarch64 | 2         | 0.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 119       | 52.65%  |
| KDE5            | 42        | 18.58%  |
| X-Cinnamon      | 17        | 7.52%   |
| Unknown         | 17        | 7.52%   |
| XFCE            | 10        | 4.42%   |
| KDE4            | 4         | 1.77%   |
| Pantheon        | 3         | 1.33%   |
| MATE            | 3         | 1.33%   |
| GNOME Flashback | 2         | 0.88%   |
| Unity           | 1         | 0.44%   |
| LXQt            | 1         | 0.44%   |
| LXDE            | 1         | 0.44%   |
| KDE6            | 1         | 0.44%   |
| i3              | 1         | 0.44%   |
| GNOME Classic   | 1         | 0.44%   |
| DWM             | 1         | 0.44%   |
| Deepin          | 1         | 0.44%   |
| Cinnamon        | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 165       | 73.66%  |
| Wayland | 49        | 21.88%  |
| Tty     | 5         | 2.23%   |
| Unknown | 5         | 2.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 85        | 37.95%  |
| GDM     | 49        | 21.88%  |
| SDDM    | 37        | 16.52%  |
| GDM3    | 31        | 13.84%  |
| LightDM | 18        | 8.04%   |
| KDM     | 4         | 1.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 104       | 47.27%  |
| fr_FR   | 69        | 31.36%  |
| Unknown | 19        | 8.64%   |
| en_GB   | 11        | 5%      |
| C       | 5         | 2.27%   |
| pt_BR   | 2         | 0.91%   |
| de_DE   | 2         | 0.91%   |
| ar_TN   | 2         | 0.91%   |
| it_IT   | 1         | 0.45%   |
| fr_CA   | 1         | 0.45%   |
| en_IN   | 1         | 0.45%   |
| en_CA   | 1         | 0.45%   |
| en_AU   | 1         | 0.45%   |
| en_AG   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 120       | 53.57%  |
| BIOS | 104       | 46.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 179       | 82.11%  |
| Overlay | 16        | 7.34%   |
| Btrfs   | 12        | 5.5%    |
| Unknown | 6         | 2.75%   |
| Tmpfs   | 4         | 1.83%   |
| Xfs     | 1         | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 94        | 42.34%  |
| GPT     | 90        | 40.54%  |
| MBR     | 38        | 17.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 189       | 85.52%  |
| Yes       | 32        | 14.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 66.2%   |
| Yes       | 73        | 33.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 51        | 23.61%  |
| ASUSTek Computer        | 37        | 17.13%  |
| Hewlett-Packard         | 36        | 16.67%  |
| Dell                    | 34        | 15.74%  |
| MSI                     | 13        | 6.02%   |
| Acer                    | 13        | 6.02%   |
| Toshiba                 | 8         | 3.7%    |
| Pegatron                | 4         | 1.85%   |
| Samsung Electronics     | 3         | 1.39%   |
| Intel                   | 3         | 1.39%   |
| Raspberry Pi Foundation | 2         | 0.93%   |
| Foxconn                 | 2         | 0.93%   |
| Valve                   | 1         | 0.46%   |
| Sony                    | 1         | 0.46%   |
| Packard Bell            | 1         | 0.46%   |
| LORD ELECTRONICS        | 1         | 0.46%   |
| Gigabyte Technology     | 1         | 0.46%   |
| eMachines               | 1         | 0.46%   |
| ECS                     | 1         | 0.46%   |
| AZW                     | 1         | 0.46%   |
| ASRock                  | 1         | 0.46%   |
| Unknown                 | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| HP Pavilion g6                            | 6         | 2.78%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK     | 3         | 1.39%   |
| Lenovo IdeaPad 3 15ADA05 81W1             | 3         | 1.39%   |
| Dell Inspiron 5570                        | 3         | 1.39%   |
| Dell Inspiron 3543                        | 3         | 1.39%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV   | 2         | 0.93%   |
| Pegatron VS342AA-AB6 m9801af              | 2         | 0.93%   |
| MSI GF63 Thin 10SCXR                      | 2         | 0.93%   |
| Lenovo IdeaPad 700-15ISK 80RU             | 2         | 0.93%   |
| Lenovo IdeaPad 5 15ITL05 82FG             | 2         | 0.93%   |
| Lenovo IdeaPad 130-15IKB 81H7             | 2         | 0.93%   |
| Intel H81                                 | 2         | 0.93%   |
| HP Pavilion Gaming Laptop 15-ec1xxx       | 2         | 0.93%   |
| HP Notebook                               | 2         | 0.93%   |
| Foxconn Pro 3400 Series MT                | 2         | 0.93%   |
| Dell Vostro 1015                          | 2         | 0.93%   |
| Dell Inspiron N5110                       | 2         | 0.93%   |
| ASUS X556UV                               | 2         | 0.93%   |
| ASUS X553MA                               | 2         | 0.93%   |
| ASUS X550JX                               | 2         | 0.93%   |
| Acer Aspire E5-571G                       | 2         | 0.93%   |
| Unknown                                   | 2         | 0.93%   |
| Valve Jupiter                             | 1         | 0.46%   |
| Toshiba Satellite Pro L850-B339           | 1         | 0.46%   |
| Toshiba Satellite L550                    | 1         | 0.46%   |
| Toshiba Satellite L500                    | 1         | 0.46%   |
| Toshiba Satellite C855-1KF                | 1         | 0.46%   |
| Toshiba Satellite C650D                   | 1         | 0.46%   |
| Toshiba Satellite C55-C                   | 1         | 0.46%   |
| Toshiba Satellite C50-A489                | 1         | 0.46%   |
| Toshiba Satellite A300                    | 1         | 0.46%   |
| Sony VPCEH36EF                            | 1         | 0.46%   |
| Samsung 530U3BI/530U4BI/530U4BH           | 1         | 0.46%   |
| RPi Raspberry Pi Compute Module 4 Rev 1.0 | 1         | 0.46%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 1         | 0.46%   |
| Pegatron Pro 3010 Microtower PC           | 1         | 0.46%   |
| Pegatron FL437AA-ABF a6641af              | 1         | 0.46%   |
| Packard Bell EasyNote ML65                | 1         | 0.46%   |
| MSI PRO H510 DP21 (MS-B0A4)               | 1         | 0.46%   |
| MSI MS-7C95                               | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 27        | 12.5%   |
| Dell Inspiron         | 15        | 6.94%   |
| HP Pavilion           | 13        | 6.02%   |
| Lenovo ThinkPad       | 11        | 5.09%   |
| Acer Aspire           | 9         | 4.17%   |
| Toshiba Satellite     | 8         | 3.7%    |
| Dell OptiPlex         | 7         | 3.24%   |
| Dell Latitude         | 6         | 2.78%   |
| HP ProBook            | 5         | 2.31%   |
| HP Laptop             | 5         | 2.31%   |
| Dell Vostro           | 4         | 1.85%   |
| ASUS TUF              | 4         | 1.85%   |
| MSI GF63              | 3         | 1.39%   |
| ASUS VivoBook         | 3         | 1.39%   |
| ASUS PRIME            | 3         | 1.39%   |
| Samsung 300E5EV       | 2         | 0.93%   |
| RPi Raspberry         | 2         | 0.93%   |
| Pegatron VS342AA-AB6  | 2         | 0.93%   |
| MSI Katana            | 2         | 0.93%   |
| Intel H81             | 2         | 0.93%   |
| HP Notebook           | 2         | 0.93%   |
| HP EliteBook          | 2         | 0.93%   |
| HP Compaq             | 2         | 0.93%   |
| HP 250                | 2         | 0.93%   |
| Foxconn Pro           | 2         | 0.93%   |
| Dell G15              | 2         | 0.93%   |
| ASUS ZenBook          | 2         | 0.93%   |
| ASUS X556UV           | 2         | 0.93%   |
| ASUS X553MA           | 2         | 0.93%   |
| ASUS X550JX           | 2         | 0.93%   |
| ASUS ROG              | 2         | 0.93%   |
| ASUS ASUS             | 2         | 0.93%   |
| Acer Swift            | 2         | 0.93%   |
| Unknown               | 2         | 0.93%   |
| Valve Jupiter         | 1         | 0.46%   |
| Sony VPCEH36EF        | 1         | 0.46%   |
| Samsung 530U3BI       | 1         | 0.46%   |
| Pegatron Pro          | 1         | 0.46%   |
| Pegatron FL437AA-ABF  | 1         | 0.46%   |
| Packard Bell EasyNote | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 26        | 12.04%  |
| 2019    | 23        | 10.65%  |
| 2011    | 19        | 8.8%    |
| 2017    | 17        | 7.87%   |
| 2013    | 17        | 7.87%   |
| 2021    | 16        | 7.41%   |
| 2015    | 14        | 6.48%   |
| 2014    | 14        | 6.48%   |
| 2012    | 14        | 6.48%   |
| 2018    | 13        | 6.02%   |
| 2016    | 11        | 5.09%   |
| 2009    | 10        | 4.63%   |
| 2010    | 7         | 3.24%   |
| 2008    | 7         | 3.24%   |
| 2023    | 3         | 1.39%   |
| 2022    | 2         | 0.93%   |
| Unknown | 2         | 0.93%   |
| 2007    | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 174       | 80.56%  |
| Desktop        | 38        | 17.59%  |
| System on chip | 2         | 0.93%   |
| Convertible    | 2         | 0.93%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 202       | 92.66%  |
| Enabled  | 16        | 7.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 216       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 72        | 33.03%  |
| 3.01-4.0   | 42        | 19.27%  |
| 16.01-24.0 | 41        | 18.81%  |
| 8.01-16.0  | 40        | 18.35%  |
| 32.01-64.0 | 8         | 3.67%   |
| 2.01-3.0   | 6         | 2.75%   |
| 1.01-2.0   | 6         | 2.75%   |
| 0.51-1.0   | 2         | 0.92%   |
| 24.01-32.0 | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 74        | 30.96%  |
| 1.01-2.0  | 71        | 29.71%  |
| 4.01-8.0  | 37        | 15.48%  |
| 3.01-4.0  | 36        | 15.06%  |
| 0.51-1.0  | 8         | 3.35%   |
| 8.01-16.0 | 7         | 2.93%   |
| 0.01-0.5  | 5         | 2.09%   |
| Unknown   | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 155       | 69.51%  |
| 2      | 62        | 27.8%   |
| 4      | 3         | 1.35%   |
| 3      | 2         | 0.9%    |
| 0      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 54.13%  |
| Yes       | 100       | 45.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 186       | 86.11%  |
| No        | 30        | 13.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 193       | 88.94%  |
| No        | 24        | 11.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 75%     |
| No        | 55        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Tunisia | 216       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Tunis              | 120       | 48.78%  |
| Aryanah            | 15        | 6.1%    |
| Sousse             | 12        | 4.88%   |
| Nabeul             | 11        | 4.47%   |
| Sfax               | 8         | 3.25%   |
| Bizerte            | 7         | 2.85%   |
| Ben Arous          | 5         | 2.03%   |
| Monastir           | 4         | 1.63%   |
| Mateur             | 3         | 1.22%   |
| Mahdia             | 3         | 1.22%   |
| Centre Urbain Nord | 3         | 1.22%   |
| Rades              | 2         | 0.81%   |
| Masakin            | 2         | 0.81%   |
| Manouba            | 2         | 0.81%   |
| Kairouan           | 2         | 0.81%   |
| Jedeida            | 2         | 0.81%   |
| Houmt Souk         | 2         | 0.81%   |
| Hammamet           | 2         | 0.81%   |
| Gafsa              | 2         | 0.81%   |
| As Sanad           | 2         | 0.81%   |
| Zarzis             | 1         | 0.41%   |
| Zaouiat Djedidi    | 1         | 0.41%   |
| Wadi Maliz         | 1         | 0.41%   |
| Tebourba           | 1         | 0.41%   |
| Tataouine          | 1         | 0.41%   |
| Tabarka            | 1         | 0.41%   |
| Soliman            | 1         | 0.41%   |
| Sidi Bouzid        | 1         | 0.41%   |
| Sidi Abbes         | 1         | 0.41%   |
| Rafraf             | 1         | 0.41%   |
| Oued Lill          | 1         | 0.41%   |
| Le Bardo           | 1         | 0.41%   |
| La Mohammedia      | 1         | 0.41%   |
| La Marsa           | 1         | 0.41%   |
| La Goulette        | 1         | 0.41%   |
| Ksar Hellal        | 1         | 0.41%   |
| Kelaa Kebira       | 1         | 0.41%   |
| Kalaa Srira        | 1         | 0.41%   |
| Jendouba           | 1         | 0.41%   |
| Hergla             | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 60        | 75     | 21.9%   |
| WDC                         | 38        | 50     | 13.87%  |
| Toshiba                     | 34        | 38     | 12.41%  |
| Samsung Electronics         | 21        | 39     | 7.66%   |
| Team                        | 14        | 16     | 5.11%   |
| SK hynix                    | 13        | 17     | 4.74%   |
| Hitachi                     | 11        | 11     | 4.01%   |
| SanDisk                     | 9         | 11     | 3.28%   |
| Micron Technology           | 9         | 9      | 3.28%   |
| Kingston                    | 8         | 10     | 2.92%   |
| Unknown                     | 7         | 11     | 2.55%   |
| Intel                       | 7         | 8      | 2.55%   |
| HGST                        | 7         | 8      | 2.55%   |
| A-DATA Technology           | 6         | 7      | 2.19%   |
| PNY                         | 4         | 4      | 1.46%   |
| Fujitsu                     | 3         | 3      | 1.09%   |
| Realtek Semiconductor       | 2         | 2      | 0.73%   |
| Patriot                     | 2         | 2      | 0.73%   |
| Emtec                       | 2         | 4      | 0.73%   |
| UMIS                        | 1         | 1      | 0.36%   |
| TwinMOS                     | 1         | 1      | 0.36%   |
| SPCC                        | 1         | 1      | 0.36%   |
| SATAFIRM                    | 1         | 1      | 0.36%   |
| Phison Electronics          | 1         | 1      | 0.36%   |
| Phison                      | 1         | 1      | 0.36%   |
| OCZ                         | 1         | 1      | 0.36%   |
| O2 Micro                    | 1         | 1      | 0.36%   |
| MSI                         | 1         | 1      | 0.36%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.36%   |
| LITEON                      | 1         | 1      | 0.36%   |
| Lexar                       | 1         | 1      | 0.36%   |
| KVST                        | 1         | 1      | 0.36%   |
| HS-SSD-E100                 | 1         | 2      | 0.36%   |
| China                       | 1         | 1      | 0.36%   |
| addlink                     | 1         | 1      | 0.36%   |
| ADATA Technology            | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 17        | 6.01%   |
| Seagate ST500LT012-1DG142 500GB       | 10        | 3.53%   |
| Seagate ST2000LM007-1R8174 2TB        | 6         | 2.12%   |
| Hitachi HTS545050A7E380 500GB         | 6         | 2.12%   |
| Toshiba MQ04ABF100 1TB                | 5         | 1.77%   |
| Toshiba MQ01ABD075 752GB              | 4         | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB        | 4         | 1.41%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 1.06%   |
| Toshiba MQ01ABD100 1TB                | 3         | 1.06%   |
| Intel SSDPEKNW512GZL 512GB            | 3         | 1.06%   |
| HGST HTS545050A7E380 500GB            | 3         | 1.06%   |
| A-DATA SU750 256GB SSD                | 3         | 1.06%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 0.71%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 2         | 0.71%   |
| WDC WD20SPZX-08UA7 2TB                | 2         | 0.71%   |
| WDC WD10SPZX-08Z10 1TB                | 2         | 0.71%   |
| WDC WD10SPCX-24HWST1 1TB              | 2         | 0.71%   |
| WDC WD10EADS-65M2B0 1TB               | 2         | 0.71%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 2         | 0.71%   |
| Toshiba MQ01ABF050 500GB              | 2         | 0.71%   |
| Toshiba MQ01ABD050 500GB              | 2         | 0.71%   |
| Toshiba MK5076GSX 500GB               | 2         | 0.71%   |
| Toshiba MK3275GSX 320GB               | 2         | 0.71%   |
| Toshiba DT01ACA050 500GB              | 2         | 0.71%   |
| Team T253X2512G 512GB SSD             | 2         | 0.71%   |
| Team T253X1480G 480GB SSD             | 2         | 0.71%   |
| Team T253X1240G 240GB SSD             | 2         | 0.71%   |
| SK hynix SC311 SATA 256GB SSD         | 2         | 0.71%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 0.71%   |
| SK hynix BC711 HFM256GD3JX013N 256GB  | 2         | 0.71%   |
| Seagate ST9500325AS 500GB             | 2         | 0.71%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 0.71%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 0.71%   |
| SanDisk NVMe SSD Drive 512GB          | 2         | 0.71%   |
| Samsung SSD 980 500GB                 | 2         | 0.71%   |
| Samsung SSD 860 EVO 500GB             | 2         | 0.71%   |
| PNY CS900 240GB SSD                   | 2         | 0.71%   |
| Micron 2210_MTFDHBA512QFD 512GB       | 2         | 0.71%   |
| Kingston NVMe SSD Drive 512GB         | 2         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 74     | 39.86%  |
| Toshiba             | 34        | 38     | 22.97%  |
| WDC                 | 33        | 44     | 22.3%   |
| Hitachi             | 11        | 11     | 7.43%   |
| HGST                | 7         | 8      | 4.73%   |
| Fujitsu             | 3         | 3      | 2.03%   |
| Samsung Electronics | 1         | 1      | 0.68%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 10        | 12     | 17.54%  |
| Samsung Electronics | 7         | 11     | 12.28%  |
| SK hynix            | 6         | 9      | 10.53%  |
| SanDisk             | 5         | 6      | 8.77%   |
| PNY                 | 4         | 4      | 7.02%   |
| Kingston            | 4         | 4      | 7.02%   |
| A-DATA Technology   | 4         | 5      | 7.02%   |
| Patriot             | 2         | 2      | 3.51%   |
| Micron Technology   | 2         | 2      | 3.51%   |
| Emtec               | 2         | 4      | 3.51%   |
| TwinMOS             | 1         | 1      | 1.75%   |
| SPCC                | 1         | 1      | 1.75%   |
| SATAFIRM            | 1         | 1      | 1.75%   |
| OCZ                 | 1         | 1      | 1.75%   |
| MSI                 | 1         | 1      | 1.75%   |
| LITEON              | 1         | 1      | 1.75%   |
| Lexar               | 1         | 1      | 1.75%   |
| KVST                | 1         | 1      | 1.75%   |
| HS-SSD-E100         | 1         | 2      | 1.75%   |
| China               | 1         | 1      | 1.75%   |
| addlink             | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 143       | 179    | 54.79%  |
| NVMe    | 55        | 81     | 21.07%  |
| SSD     | 55        | 71     | 21.07%  |
| MMC     | 6         | 10     | 2.3%    |
| Unknown | 2         | 2      | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 172       | 248    | 72.57%  |
| NVMe | 55        | 81     | 23.21%  |
| MMC  | 6         | 10     | 2.53%   |
| SAS  | 4         | 4      | 1.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 115       | 142    | 59.28%  |
| 0.51-1.0   | 69        | 96     | 35.57%  |
| 1.01-2.0   | 10        | 12     | 5.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 67        | 29.78%  |
| 101-250        | 63        | 28%     |
| 501-1000       | 37        | 16.44%  |
| 1001-2000      | 17        | 7.56%   |
| 51-100         | 14        | 6.22%   |
| 1-20           | 12        | 5.33%   |
| 21-50          | 8         | 3.56%   |
| 2001-3000      | 3         | 1.33%   |
| Unknown        | 3         | 1.33%   |
| More than 3000 | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 84        | 35.9%   |
| 21-50     | 48        | 20.51%  |
| 101-250   | 43        | 18.38%  |
| 51-100    | 31        | 13.25%  |
| 251-500   | 9         | 3.85%   |
| 501-1000  | 9         | 3.85%   |
| 1001-2000 | 7         | 2.99%   |
| Unknown   | 3         | 1.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Hitachi HTS545050A7E380 500GB                       | 4         | 4      | 12.9%   |
| Seagate ST9500325AS 500GB                           | 2         | 2      | 6.45%   |
| HGST HTS545050A7E380 500GB                          | 2         | 3      | 6.45%   |
| WDC WD6400AAKS-65A7B0 640GB                         | 1         | 1      | 3.23%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 3.23%   |
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 3.23%   |
| WDC WD5000BEVT-22A0RT0 500GB                        | 1         | 1      | 3.23%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 3.23%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 3.23%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 3.23%   |
| Seagate ST9320325AS 320GB                           | 1         | 2      | 3.23%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 3.23%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 3.23%   |
| Seagate ST3320813AS 320GB                           | 1         | 1      | 3.23%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 2      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2      | 3.23%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 3.23%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 3.23%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 3.23%   |
| Hitachi HTS547575A9E384 752GB                       | 1         | 1      | 3.23%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 3.23%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 3.23%   |
| Emtec X250 512GB SSD                                | 1         | 2      | 3.23%   |
| A-DATA Technology SX8100NP 512GB                    | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 9         | 12     | 29.03%  |
| Hitachi           | 7         | 7      | 22.58%  |
| Toshiba           | 5         | 6      | 16.13%  |
| WDC               | 4         | 5      | 12.9%   |
| HGST              | 2         | 3      | 6.45%   |
| Micron Technology | 1         | 1      | 3.23%   |
| Kingston          | 1         | 1      | 3.23%   |
| Emtec             | 1         | 2      | 3.23%   |
| A-DATA Technology | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 12     | 33.33%  |
| Hitachi | 7         | 7      | 25.93%  |
| Toshiba | 5         | 6      | 18.52%  |
| WDC     | 4         | 5      | 14.81%  |
| HGST    | 2         | 3      | 7.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 33     | 86.21%  |
| SSD  | 3         | 4      | 10.34%  |
| NVMe | 1         | 1      | 3.45%   |

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
| Detected | 104       | 148    | 44.64%  |
| Works    | 99        | 156    | 42.49%  |
| Malfunc  | 29        | 38     | 12.45%  |
| Failed   | 1         | 1      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 179       | 70.47%  |
| AMD                          | 22        | 8.66%   |
| Samsung Electronics          | 13        | 5.12%   |
| SanDisk                      | 8         | 3.15%   |
| SK hynix                     | 7         | 2.76%   |
| Micron Technology            | 7         | 2.76%   |
| Realtek Semiconductor        | 4         | 1.57%   |
| Phison Electronics           | 4         | 1.57%   |
| Kingston Technology Company  | 4         | 1.57%   |
| Union Memory (Shenzhen)      | 1         | 0.39%   |
| Silicon Motion               | 1         | 0.39%   |
| Shenzhen Longsys Electronics | 1         | 0.39%   |
| O2 Micro                     | 1         | 0.39%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.39%   |
| ADATA Technology             | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 6.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 17        | 6.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 14        | 5.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 4.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 4.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 11        | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 3.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 3.61%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10        | 3.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 2.89%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 7         | 2.53%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 2.17%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 2.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 2.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6         | 2.17%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 5         | 1.81%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 4         | 1.44%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 4         | 1.44%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.44%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3         | 1.08%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 3         | 1.08%   |
| Phison E12 NVMe Controller                                                              | 3         | 1.08%   |
| Intel SSD 660P Series                                                                   | 3         | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.08%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.08%   |
| SK hynix BC511 NVMe SSD                                                                 | 2         | 0.72%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2         | 0.72%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 2         | 0.72%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 2         | 0.72%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 0.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 164       | 63.32%  |
| NVMe | 55        | 21.24%  |
| RAID | 24        | 9.27%   |
| IDE  | 16        | 6.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 184       | 85.19%  |
| AMD    | 30        | 13.89%  |
| ARM    | 2         | 0.93%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 2.31%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.31%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 2.31%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 2.31%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 2.31%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.85%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.39%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.39%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.39%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.39%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.39%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.39%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 0.93%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.93%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.93%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.93%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.93%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.93%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.93%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.93%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.93%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.93%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 0.93%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 2         | 0.93%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 2         | 0.93%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz          | 2         | 0.93%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 53        | 24.54%  |
| Intel Core i7           | 44        | 20.37%  |
| Intel Core i3           | 32        | 14.81%  |
| Other                   | 23        | 10.65%  |
| AMD Ryzen 5             | 12        | 5.56%   |
| Intel Pentium           | 10        | 4.63%   |
| Intel Celeron           | 8         | 3.7%    |
| Intel Core 2 Quad       | 7         | 3.24%   |
| Intel Core 2 Duo        | 7         | 3.24%   |
| AMD Ryzen 7             | 3         | 1.39%   |
| Intel Pentium Dual-Core | 2         | 0.93%   |
| AMD Ryzen 3             | 2         | 0.93%   |
| Intel Xeon              | 1         | 0.46%   |
| Intel Core m3           | 1         | 0.46%   |
| Intel Atom              | 1         | 0.46%   |
| AMD Sempron             | 1         | 0.46%   |
| AMD Ryzen 5 PRO         | 1         | 0.46%   |
| AMD FX                  | 1         | 0.46%   |
| AMD E2                  | 1         | 0.46%   |
| AMD E                   | 1         | 0.46%   |
| AMD Athlon              | 1         | 0.46%   |
| AMD A8                  | 1         | 0.46%   |
| AMD A6                  | 1         | 0.46%   |
| AMD A4                  | 1         | 0.46%   |
| AMD A10                 | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 106       | 49.07%  |
| 4       | 78        | 36.11%  |
| 6       | 16        | 7.41%   |
| 8       | 8         | 3.7%    |
| 10      | 3         | 1.39%   |
| 1       | 2         | 0.93%   |
| 14      | 1         | 0.46%   |
| 12      | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 216       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 165       | 76.04%  |
| 1       | 51        | 23.5%   |
| Unknown | 1         | 0.46%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 215       | 99.54%  |
| Unknown        | 1         | 0.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 32.44%  |
| 0x206a7    | 16        | 7.11%   |
| 0x40651    | 9         | 4%      |
| 0x306a9    | 9         | 4%      |
| 0x1067a    | 9         | 4%      |
| 0x806ea    | 8         | 3.56%   |
| 0x806c1    | 8         | 3.56%   |
| 0xa0652    | 7         | 3.11%   |
| 0x806ec    | 7         | 3.11%   |
| 0x906ea    | 6         | 2.67%   |
| 0x506e3    | 6         | 2.67%   |
| 0x406e3    | 5         | 2.22%   |
| 0x306c3    | 5         | 2.22%   |
| 0x08108109 | 5         | 2.22%   |
| 0x306d4    | 4         | 1.78%   |
| 0x806e9    | 3         | 1.33%   |
| 0x706e5    | 3         | 1.33%   |
| 0x20655    | 3         | 1.33%   |
| 0x706a8    | 2         | 0.89%   |
| 0x6fd      | 2         | 0.89%   |
| 0x406c4    | 2         | 0.89%   |
| 0x30678    | 2         | 0.89%   |
| 0x08600106 | 2         | 0.89%   |
| 0x08108102 | 2         | 0.89%   |
| 0x06006705 | 2         | 0.89%   |
| 0x06006704 | 2         | 0.89%   |
| 0xa0671    | 1         | 0.44%   |
| 0xa0653    | 1         | 0.44%   |
| 0x906e9    | 1         | 0.44%   |
| 0x906a4    | 1         | 0.44%   |
| 0x906a3    | 1         | 0.44%   |
| 0x90672    | 1         | 0.44%   |
| 0x6fb      | 1         | 0.44%   |
| 0x506c9    | 1         | 0.44%   |
| 0x40661    | 1         | 0.44%   |
| 0x20652    | 1         | 0.44%   |
| 0x106ca    | 1         | 0.44%   |
| 0x10677    | 1         | 0.44%   |
| 0x0a50000f | 1         | 0.44%   |
| 0x0a50000d | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 38        | 17.59%  |
| Haswell          | 23        | 10.65%  |
| SandyBridge      | 22        | 10.19%  |
| Skylake          | 14        | 6.48%   |
| Penryn           | 13        | 6.02%   |
| TigerLake        | 11        | 5.09%   |
| IvyBridge        | 11        | 5.09%   |
| Broadwell        | 10        | 4.63%   |
| Zen+             | 9         | 4.17%   |
| CometLake        | 9         | 4.17%   |
| Westmere         | 7         | 3.24%   |
| IceLake          | 7         | 3.24%   |
| Unknown          | 7         | 3.24%   |
| Silvermont       | 5         | 2.31%   |
| Zen 3            | 4         | 1.85%   |
| Zen 2            | 4         | 1.85%   |
| Goldmont plus    | 4         | 1.85%   |
| Excavator        | 4         | 1.85%   |
| Core             | 3         | 1.39%   |
| Alderlake Hybrid | 3         | 1.39%   |
| Piledriver       | 2         | 0.93%   |
| Zen              | 1         | 0.46%   |
| Puma             | 1         | 0.46%   |
| K8 & K10 hybrid  | 1         | 0.46%   |
| Goldmont         | 1         | 0.46%   |
| Bonnell          | 1         | 0.46%   |
| Bobcat           | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 162       | 52.6%   |
| Nvidia | 93        | 30.19%  |
| AMD    | 53        | 17.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 5.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 4.18%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 3.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 3.22%   |
| Intel HD Graphics 5500                                                                   | 10        | 3.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.22%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 2.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 2.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.93%   |
| Nvidia GM108M [GeForce MX110]                                                            | 5         | 1.61%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 1.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.61%   |
| Intel HD Graphics 620                                                                    | 5         | 1.61%   |
| Intel HD Graphics 530                                                                    | 5         | 1.61%   |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 1.29%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.29%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.29%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.29%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.29%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.29%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.29%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.96%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.96%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 0.96%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.96%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.96%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 0.96%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 0.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.96%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.64%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 74        | 34.26%  |
| Intel + Nvidia | 65        | 30.09%  |
| 1 x AMD        | 24        | 11.11%  |
| 1 x Nvidia     | 20        | 9.26%   |
| Intel + AMD    | 19        | 8.8%    |
| AMD + Nvidia   | 8         | 3.7%    |
| Other          | 2         | 0.93%   |
| 2 x Intel      | 2         | 0.93%   |
| 2 x AMD        | 2         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 168       | 75.68%  |
| Proprietary | 46        | 20.72%  |
| Unknown     | 8         | 3.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 58.11%  |
| 1.01-2.0   | 38        | 17.12%  |
| 0.01-0.5   | 16        | 7.21%   |
| 3.01-4.0   | 15        | 6.76%   |
| 0.51-1.0   | 15        | 6.76%   |
| 5.01-6.0   | 6         | 2.7%    |
| 2.01-3.0   | 2         | 0.9%    |
| 7.01-8.0   | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 44        | 18.97%  |
| Chimei Innolux          | 37        | 15.95%  |
| AU Optronics            | 36        | 15.52%  |
| BOE                     | 34        | 14.66%  |
| LG Display              | 27        | 11.64%  |
| Hewlett-Packard         | 15        | 6.47%   |
| Chi Mei Optoelectronics | 6         | 2.59%   |
| MSI                     | 3         | 1.29%   |
| Lenovo                  | 3         | 1.29%   |
| Dell                    | 3         | 1.29%   |
| Acer                    | 3         | 1.29%   |
| Philips                 | 2         | 0.86%   |
| PANDA                   | 2         | 0.86%   |
| Packard Bell            | 2         | 0.86%   |
| HKC                     | 2         | 0.86%   |
| BenQ                    | 2         | 0.86%   |
| Valve                   | 1         | 0.43%   |
| S2-Tek                  | 1         | 0.43%   |
| PKB                     | 1         | 0.43%   |
| NCS                     | 1         | 0.43%   |
| Medion                  | 1         | 0.43%   |
| LG Philips              | 1         | 0.43%   |
| ITE                     | 1         | 0.43%   |
| HPN                     | 1         | 0.43%   |
| Goldstar                | 1         | 0.43%   |
| GDH                     | 1         | 0.43%   |
| ASUSTek Computer        | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 3.39%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 6         | 2.54%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 4         | 1.69%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 1.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 4         | 1.69%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 1.69%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 4         | 1.69%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 3         | 1.27%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch     | 3         | 1.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 1.27%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 1.27%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 3         | 1.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 1.27%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch         | 2         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 2         | 0.85%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.85%   |
| Hewlett-Packard x20LED HWP2910 1600x900 443x249mm 20.0-inch              | 2         | 0.85%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch               | 2         | 0.85%   |
| Hewlett-Packard P224 HPN361E 1920x1080 527x296mm 23.8-inch               | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.85%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.85%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.85%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                    | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch           | 2         | 0.85%   |
| Acer V193HQV ACR0133 1366x768 410x230mm 18.5-inch                        | 2         | 0.85%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch     | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM0284 1280x1024 338x270mm 17.0-inch     | 1         | 0.42%   |
| Samsung Electronics SMB2240 SAM06AD 1920x1080 477x268mm 21.5-inch        | 1         | 0.42%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 440x250mm 19.9-inch     | 1         | 0.42%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch         | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 1         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 97        | 44.29%  |
| 1366x768 (WXGA)    | 84        | 38.36%  |
| 1600x900 (HD+)     | 14        | 6.39%   |
| 1280x1024 (SXGA)   | 5         | 2.28%   |
| 3840x2160 (4K)     | 4         | 1.83%   |
| 1280x800 (WXGA)    | 4         | 1.83%   |
| 1680x1050 (WSXGA+) | 3         | 1.37%   |
| 1440x900 (WXGA+)   | 3         | 1.37%   |
| 800x1280           | 1         | 0.46%   |
| 3840x1100          | 1         | 0.46%   |
| 2560x1440 (QHD)    | 1         | 0.46%   |
| 1024x600           | 1         | 0.46%   |
| Unknown            | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 130       | 55.79%  |
| 23      | 15        | 6.44%   |
| 17      | 13        | 5.58%   |
| 14      | 12        | 5.15%   |
| 21      | 9         | 3.86%   |
| 24      | 8         | 3.43%   |
| 13      | 8         | 3.43%   |
| 20      | 6         | 2.58%   |
| 27      | 5         | 2.15%   |
| 19      | 5         | 2.15%   |
| 18      | 4         | 1.72%   |
| 12      | 4         | 1.72%   |
| 11      | 3         | 1.29%   |
| Unknown | 3         | 1.29%   |
| 31      | 2         | 0.86%   |
| 22      | 2         | 0.86%   |
| 52      | 1         | 0.43%   |
| 42      | 1         | 0.43%   |
| 10      | 1         | 0.43%   |
| 7       | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 142       | 62.28%  |
| 501-600     | 27        | 11.84%  |
| 401-500     | 23        | 10.09%  |
| 351-400     | 17        | 7.46%   |
| 201-300     | 11        | 4.82%   |
| Unknown     | 3         | 1.32%   |
| 601-700     | 2         | 0.88%   |
| 1001-1500   | 1         | 0.44%   |
| 901-1000    | 1         | 0.44%   |
| 1-100       | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 186       | 88.57%  |
| 16/10   | 12        | 5.71%   |
| 5/4     | 5         | 2.38%   |
| Unknown | 3         | 1.43%   |
| 4/3     | 1         | 0.48%   |
| 3/2     | 1         | 0.48%   |
| 3.40    | 1         | 0.48%   |
| 0.67    | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 130       | 56.03%  |
| 201-250        | 31        | 13.36%  |
| 81-90          | 15        | 6.47%   |
| 151-200        | 12        | 5.17%   |
| 121-130        | 8         | 3.45%   |
| 141-150        | 7         | 3.02%   |
| 301-350        | 5         | 2.16%   |
| 71-80          | 4         | 1.72%   |
| 51-60          | 4         | 1.72%   |
| 61-70          | 3         | 1.29%   |
| Unknown        | 3         | 1.29%   |
| 351-500        | 2         | 0.86%   |
| 251-300        | 2         | 0.86%   |
| 131-140        | 2         | 0.86%   |
| More than 1000 | 1         | 0.43%   |
| 41-50          | 1         | 0.43%   |
| 1-40           | 1         | 0.43%   |
| 501-1000       | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 79        | 34.96%  |
| 121-160       | 71        | 31.42%  |
| 51-100        | 62        | 27.43%  |
| 161-240       | 6         | 2.65%   |
| 1-50          | 3         | 1.33%   |
| Unknown       | 3         | 1.33%   |
| More than 240 | 2         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 179       | 81.74%  |
| 2     | 32        | 14.61%  |
| 0     | 8         | 3.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 161       | 46.13%  |
| Intel                             | 76        | 21.78%  |
| Qualcomm Atheros                  | 47        | 13.47%  |
| Broadcom                          | 22        | 6.3%    |
| Ralink                            | 11        | 3.15%   |
| Ralink Technology                 | 10        | 2.87%   |
| Broadcom Limited                  | 5         | 1.43%   |
| MediaTek                          | 3         | 0.86%   |
| Ericsson Business Mobile Networks | 2         | 0.57%   |
| D-Link                            | 2         | 0.57%   |
| TP-Link                           | 1         | 0.29%   |
| Sierra Wireless                   | 1         | 0.29%   |
| Samsung Electronics               | 1         | 0.29%   |
| OPPO Electronics                  | 1         | 0.29%   |
| Microchip Technology              | 1         | 0.29%   |
| Marvell Technology Group          | 1         | 0.29%   |
| IMC Networks                      | 1         | 0.29%   |
| ICS Advent                        | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 104       | 25.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 45        | 11.19%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 13        | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 12        | 2.99%   |
| Broadcom BCM43142 802.11b/g/n                                          | 11        | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 2.24%   |
| Intel Wi-Fi 6 AX201                                                    | 9         | 2.24%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 9         | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 1.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.49%   |
| Ralink MT7601U Wireless Adapter                                        | 6         | 1.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 6         | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 6         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 1%      |
| Intel Wireless 7265                                                    | 4         | 1%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 3         | 0.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.75%   |
| Intel Wireless 8265 / 8275                                             | 3         | 0.75%   |
| Intel Wireless 8260                                                    | 3         | 0.75%   |
| Intel WiFi Link 5100                                                   | 3         | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 0.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 0.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.5%    |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.5%    |
| Ralink RT5370 Wireless Adapter                                         | 2         | 0.5%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2         | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.5%    |
| Intel Wireless 7260                                                    | 2         | 0.5%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2         | 0.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 70        | 33.65%  |
| Qualcomm Atheros      | 44        | 21.15%  |
| Realtek Semiconductor | 41        | 19.71%  |
| Broadcom              | 18        | 8.65%   |
| Ralink                | 11        | 5.29%   |
| Ralink Technology     | 10        | 4.81%   |
| Broadcom Limited      | 5         | 2.4%    |
| MediaTek              | 3         | 1.44%   |
| D-Link                | 2         | 0.96%   |
| TP-Link               | 1         | 0.48%   |
| Sierra Wireless       | 1         | 0.48%   |
| IMC Networks          | 1         | 0.48%   |
| D-Link System         | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 6.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 5.74%   |
| Broadcom BCM43142 802.11b/g/n                                  | 11        | 5.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 4.31%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 4.31%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 4.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 3.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 3.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.87%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 2.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 2.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 2.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.91%   |
| Intel Wireless 7265                                            | 4         | 1.91%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3         | 1.44%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.44%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.44%   |
| Intel Wireless 8260                                            | 3         | 1.44%   |
| Intel WiFi Link 5100                                           | 3         | 1.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.96%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.96%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2         | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.96%   |
| Intel Wireless 7260                                            | 2         | 0.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 0.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.96%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 0.96%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 0.96%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 153       | 80.53%  |
| Intel                    | 20        | 10.53%  |
| Qualcomm Atheros         | 6         | 3.16%   |
| Broadcom                 | 5         | 2.63%   |
| Samsung Electronics      | 1         | 0.53%   |
| OPPO Electronics         | 1         | 0.53%   |
| Microchip Technology     | 1         | 0.53%   |
| Marvell Technology Group | 1         | 0.53%   |
| ICS Advent               | 1         | 0.53%   |
| Huawei Technologies      | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 104       | 54.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 45        | 23.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.09%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 1.57%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 1.05%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 1.05%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.05%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.05%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.05%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.52%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 1         | 0.52%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 1         | 0.52%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.52%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.52%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 0.52%   |
| Intel 82562V-2 10/100 Network Connection                               | 1         | 0.52%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 1         | 0.52%   |
| Huawei TIT-L01                                                         | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 193       | 50.66%  |
| Ethernet | 186       | 48.82%  |
| Modem    | 2         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 162       | 72.65%  |
| Ethernet | 61        | 27.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 157       | 72.35%  |
| 1     | 58        | 26.73%  |
| 0     | 2         | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 214       | 99.07%  |
| Yes  | 2         | 0.93%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 35.76%  |
| Qualcomm Atheros Communications | 30        | 18.18%  |
| Realtek Semiconductor           | 26        | 15.76%  |
| Lite-On Technology              | 11        | 6.67%   |
| Broadcom                        | 10        | 6.06%   |
| IMC Networks                    | 8         | 4.85%   |
| Ralink                          | 6         | 3.64%   |
| Foxconn / Hon Hai               | 4         | 2.42%   |
| Cambridge Silicon Radio         | 4         | 2.42%   |
| Toshiba                         | 3         | 1.82%   |
| Realtek                         | 1         | 0.61%   |
| Hewlett-Packard                 | 1         | 0.61%   |
| Dell                            | 1         | 0.61%   |
| ASUSTek Computer                | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 23        | 13.94%  |
| Realtek Bluetooth Radio                             | 17        | 10.3%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 8.48%   |
| Intel Bluetooth wireless interface                  | 13        | 7.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 7.27%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 4.24%   |
| Ralink RT3290 Bluetooth                             | 6         | 3.64%   |
| Intel Bluetooth Device                              | 6         | 3.64%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.03%   |
| Realtek 802.11ac WLAN Adapter                       | 4         | 2.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 2.42%   |
| Lite-On Bluetooth Device                            | 4         | 2.42%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 2.42%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.82%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 1.82%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.82%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 3         | 1.82%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.21%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.21%   |
| Lite-On BCM43142A0                                  | 2         | 1.21%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.21%   |
| IMC Networks Wireless_Device                        | 2         | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.21%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.21%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.61%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.61%   |
| Toshiba BCM43142A0                                  | 1         | 0.61%   |
| Realtek Bluetooth Radio                             | 1         | 0.61%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.61%   |
| Intel AX211 Bluetooth                               | 1         | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.61%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.61%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.61%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 185       | 66.79%  |
| Nvidia                  | 46        | 16.61%  |
| AMD                     | 38        | 13.72%  |
| C-Media Electronics     | 3         | 1.08%   |
| Xiamen VBeT Electronics | 1         | 0.36%   |
| Razer USA               | 1         | 0.36%   |
| Lenovo                  | 1         | 0.36%   |
| JMTek                   | 1         | 0.36%   |
| DSEA A/S                | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 7.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 5.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 5.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 4.98%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 4.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 3.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 3.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.12%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 3.12%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 2.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 2.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.18%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.87%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.56%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.25%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.25%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.93%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.93%   |
| Nvidia Audio device                                                                               | 3         | 0.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 0.93%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 47        | 27.81%  |
| SK hynix                     | 32        | 18.93%  |
| Micron Technology            | 20        | 11.83%  |
| Team                         | 16        | 9.47%   |
| Unknown                      | 9         | 5.33%   |
| A-DATA Technology            | 9         | 5.33%   |
| Nanya Technology             | 5         | 2.96%   |
| Crucial                      | 5         | 2.96%   |
| Ramaxel Technology           | 4         | 2.37%   |
| Elpida                       | 4         | 2.37%   |
| Kingston                     | 3         | 1.78%   |
| TwinMOS                      | 2         | 1.18%   |
| Toshiba                      | 2         | 1.18%   |
| Hikvision                    | 2         | 1.18%   |
| Unknown (ABCD)               | 1         | 0.59%   |
| Transcend                    | 1         | 0.59%   |
| PNY                          | 1         | 0.59%   |
| Patriot Memory (PDP Systems) | 1         | 0.59%   |
| Patriot                      | 1         | 0.59%   |
| Melco                        | 1         | 0.59%   |
| GOODRAM                      | 1         | 0.59%   |
| ASint Technology             | 1         | 0.59%   |
| 0BBA00000000                 | 1         | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 2.26%   |
| Team RAM TEAMGROUP-SD4-3200 16384MB SODIMM DDR4 3200MT/s     | 3         | 1.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 1.69%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 3         | 1.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 1.69%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s     | 3         | 1.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 1.69%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 3         | 1.69%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s         | 3         | 1.69%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                  | 3         | 1.69%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s           | 2         | 1.13%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s         | 2         | 1.13%   |
| Team RAM TEAMGROUP-SD4-3200 8GB Row Of Chips DDR4 2400MT/s   | 2         | 1.13%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 2         | 1.13%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s         | 2         | 1.13%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s         | 2         | 1.13%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s         | 2         | 1.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.13%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.13%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 1.13%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.13%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 1.13%   |
| Micron RAM MT40A512M16TB-062E:R 4GB SODIMM DDR4 3200MT/s     | 2         | 1.13%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 2         | 1.13%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                    | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3                             | 1         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s               | 1         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                | 1         | 0.56%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                       | 1         | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1         | 0.56%   |
| TwinMOS RAM 9DSDBNZB-5AMP 4GB DIMM DDR3 1333MT/s             | 1         | 0.56%   |
| TwinMOS RAM 9D7TBNZB-TATP 4096MB DIMM DDR3 1066MT/s          | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 72        | 54.55%  |
| DDR3    | 40        | 30.3%   |
| DDR2    | 6         | 4.55%   |
| SDRAM   | 5         | 3.79%   |
| LPDDR4  | 3         | 2.27%   |
| DDR5    | 3         | 2.27%   |
| LPDDR3  | 2         | 1.52%   |
| Unknown | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 101       | 75.37%  |
| DIMM         | 20        | 14.93%  |
| Row Of Chips | 12        | 8.96%   |
| Chip         | 1         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 53        | 33.33%  |
| 4096  | 52        | 32.7%   |
| 16384 | 23        | 14.47%  |
| 2048  | 18        | 11.32%  |
| 32768 | 8         | 5.03%   |
| 1024  | 5         | 3.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 32        | 21.19%  |
| 2667    | 32        | 21.19%  |
| 1600    | 21        | 13.91%  |
| 2400    | 13        | 8.61%   |
| 1334    | 12        | 7.95%   |
| 1333    | 7         | 4.64%   |
| 1066    | 4         | 2.65%   |
| 667     | 4         | 2.65%   |
| 4800    | 3         | 1.99%   |
| 4199    | 3         | 1.99%   |
| 3266    | 3         | 1.99%   |
| 2133    | 3         | 1.99%   |
| 1867    | 3         | 1.99%   |
| 8400    | 2         | 1.32%   |
| Unknown | 2         | 1.32%   |
| 49926   | 1         | 0.66%   |
| 3800    | 1         | 0.66%   |
| 3000    | 1         | 0.66%   |
| 1648    | 1         | 0.66%   |
| 1067    | 1         | 0.66%   |
| 975     | 1         | 0.66%   |
| 800     | 1         | 0.66%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 75%     |
| Seiko Epson     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP LaserJet P1005       | 2         | 50%     |
| Seiko Epson L365 Series | 1         | 25%     |
| HP DeskJet 5810 series  | 1         | 25%     |

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
| Chicony Electronics                    | 35        | 21.21%  |
| IMC Networks                           | 22        | 13.33%  |
| Realtek Semiconductor                  | 19        | 11.52%  |
| Microdia                               | 15        | 9.09%   |
| Bison Electronics                      | 14        | 8.48%   |
| Syntek                                 | 9         | 5.45%   |
| Suyin                                  | 9         | 5.45%   |
| Sunplus Innovation Technology          | 8         | 4.85%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.24%   |
| Quanta                                 | 5         | 3.03%   |
| Luxvisions Innotech Limited            | 5         | 3.03%   |
| Lite-On Technology                     | 5         | 3.03%   |
| Acer                                   | 3         | 1.82%   |
| Silicon Motion                         | 1         | 0.61%   |
| Samsung Electronics                    | 1         | 0.61%   |
| Ricoh                                  | 1         | 0.61%   |
| Lenovo                                 | 1         | 0.61%   |
| Importek                               | 1         | 0.61%   |
| Cubeternet                             | 1         | 0.61%   |
| Apple                                  | 1         | 0.61%   |
| Alcor Micro                            | 1         | 0.61%   |
| A4Tech                                 | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 5.45%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 8         | 4.85%   |
| IMC Networks Integrated Camera                              | 6         | 3.64%   |
| Bison Integrated Camera                                     | 6         | 3.64%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 3.03%   |
| Microdia Integrated_Webcam_HD                               | 5         | 3.03%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 5         | 3.03%   |
| Chicony HD WebCam                                           | 5         | 3.03%   |
| Syntek Integrated Camera                                    | 4         | 2.42%   |
| Realtek USB Camera                                          | 4         | 2.42%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 4         | 2.42%   |
| Syntek EasyCamera                                           | 3         | 1.82%   |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 1.82%   |
| Realtek Integrated_Webcam_HD                                | 3         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 3         | 1.82%   |
| Lite-On Integrated Camera                                   | 3         | 1.82%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 1.82%   |
| Bison HD Webcam                                             | 3         | 1.82%   |
| Suyin Integrated_Webcam_HD                                  | 2         | 1.21%   |
| Suyin HP TrueVision HD                                      | 2         | 1.21%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.21%   |
| Realtek EasyCamera                                          | 2         | 1.21%   |
| Quanta VGA WebCam                                           | 2         | 1.21%   |
| Microdia Webcam SC-10HDD12636P                              | 2         | 1.21%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.21%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.21%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.21%   |
| Chicony EasyCamera                                          | 2         | 1.21%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.21%   |
| Bison Lenovo EasyCamera                                     | 2         | 1.21%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                        | 1         | 0.61%   |
| Syntek Integrated RGB Camera                                | 1         | 0.61%   |
| Suyin USB 2.0 Camera                                        | 1         | 0.61%   |
| Suyin Laptop_Integrated_Webcam_2HDM                         | 1         | 0.61%   |
| Suyin HP Integrated Webcam                                  | 1         | 0.61%   |
| Suyin HD WebCam                                             | 1         | 0.61%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.61%   |
| Sunplus HD User Facing                                      | 1         | 0.61%   |
| Sunplus Dell HD Webcam                                      | 1         | 0.61%   |
| Sunplus Asus Webcam                                         | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 42.86%  |
| Synaptics                  | 2         | 14.29%  |
| Shenzhen Goodix Technology | 2         | 14.29%  |
| LighTuning Technology      | 2         | 14.29%  |
| Upek                       | 1         | 7.14%   |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 14.29%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 14.29%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner                   | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.14%   |
| AuthenTec AES1600                                      | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Alcor Micro | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom 5880                                                                | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 164       | 71.3%   |
| 1     | 54        | 23.48%  |
| 3     | 5         | 2.17%   |
| 2     | 5         | 2.17%   |
| 5     | 1         | 0.43%   |
| 4     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 22        | 26.83%  |
| Net/wireless             | 15        | 18.29%  |
| Fingerprint reader       | 14        | 17.07%  |
| Bluetooth                | 9         | 10.98%  |
| Communication controller | 5         | 6.1%    |
| Chipcard                 | 4         | 4.88%   |
| Camera                   | 4         | 4.88%   |
| Storage                  | 2         | 2.44%   |
| Sound                    | 2         | 2.44%   |
| Net/ethernet             | 2         | 2.44%   |
| Network                  | 1         | 1.22%   |
| Multimedia controller    | 1         | 1.22%   |
| Card reader              | 1         | 1.22%   |

