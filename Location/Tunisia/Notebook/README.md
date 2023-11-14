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

Total: 225

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 38        | 22.49%  |
| Ubuntu 22.04        | 14        | 8.28%   |
| Ubuntu 18.04        | 12        | 7.1%    |
| Ubuntu 21.10        | 5         | 2.96%   |
| Fedora 38           | 4         | 2.37%   |
| Zorin 16            | 3         | 1.78%   |
| Zorin 15            | 3         | 1.78%   |
| Pop!_OS 22.04       | 3         | 1.78%   |
| OpenMandriva 23.03  | 3         | 1.78%   |
| Linux Mint 21.2     | 3         | 1.78%   |
| KDE neon 22.04      | 3         | 1.78%   |
| Debian 10           | 3         | 1.78%   |
| Ubuntu 21.04        | 2         | 1.18%   |
| Ubuntu 20.10        | 2         | 1.18%   |
| Ubuntu 16.04        | 2         | 1.18%   |
| Pop!_OS 21.04       | 2         | 1.18%   |
| OpenMandriva 4.2    | 2         | 1.18%   |
| Manjaro 21.1.0      | 2         | 1.18%   |
| LMDE 4              | 2         | 1.18%   |
| Linux Mint 21.1     | 2         | 1.18%   |
| Linux Mint 20.3     | 2         | 1.18%   |
| Linux Mint 20.2     | 2         | 1.18%   |
| KDE neon 20.04      | 2         | 1.18%   |
| Fedora 35           | 2         | 1.18%   |
| Fedora 33           | 2         | 1.18%   |
| EndeavourOS Rolling | 2         | 1.18%   |
| ArcoLinux Rolling   | 2         | 1.18%   |
| Arch Rolling        | 2         | 1.18%   |
| Xubuntu 18.04       | 1         | 0.59%   |
| Xero Rolling        | 1         | 0.59%   |
| Ubuntu Unity 16.04  | 1         | 0.59%   |
| Ubuntu 19.10        | 1         | 0.59%   |
| SteamOS 3.4.11      | 1         | 0.59%   |
| Sodalite 35         | 1         | 0.59%   |
| ROSA R8.1           | 1         | 0.59%   |
| ROSA R11            | 1         | 0.59%   |
| ROSA R10            | 1         | 0.59%   |
| ROSA 12.3           | 1         | 0.59%   |
| Pop!_OS 20.10       | 1         | 0.59%   |
| OpenMandriva 4.3    | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 73        | 44.79%  |
| Linux Mint   | 12        | 7.36%   |
| Fedora       | 9         | 5.52%   |
| OpenMandriva | 8         | 4.91%   |
| Zorin        | 6         | 3.68%   |
| Pop!_OS      | 6         | 3.68%   |
| Manjaro      | 6         | 3.68%   |
| Debian       | 6         | 3.68%   |
| ROSA         | 4         | 2.45%   |
| KDE neon     | 4         | 2.45%   |
| Endless      | 4         | 2.45%   |
| Arch         | 3         | 1.84%   |
| Lubuntu      | 2         | 1.23%   |
| LMDE         | 2         | 1.23%   |
| EndeavourOS  | 2         | 1.23%   |
| Elementary   | 2         | 1.23%   |
| ArcoLinux    | 2         | 1.23%   |
| Xubuntu      | 1         | 0.61%   |
| Xero         | 1         | 0.61%   |
| Ubuntu Unity | 1         | 0.61%   |
| SteamOS      | 1         | 0.61%   |
| Sodalite     | 1         | 0.61%   |
| Nobara       | 1         | 0.61%   |
| MX           | 1         | 0.61%   |
| Kubuntu      | 1         | 0.61%   |
| Gentoo       | 1         | 0.61%   |
| Garuda Linux | 1         | 0.61%   |
| Deepin       | 1         | 0.61%   |
| BlackPanther | 1         | 0.61%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.13.0-28-generic           | 4         | 2.27%   |
| 6.2.6-desktop-1omv2390      | 3         | 1.7%    |
| 5.3.0-46-generic            | 3         | 1.7%    |
| 5.15.0-58-generic           | 3         | 1.7%    |
| 5.15.0-52-generic           | 3         | 1.7%    |
| 5.15.0-46-generic           | 3         | 1.7%    |
| 5.15.0-43-generic           | 3         | 1.7%    |
| 5.11.0-38-generic           | 3         | 1.7%    |
| 5.8.0-38-generic            | 2         | 1.14%   |
| 5.8.0-14-generic            | 2         | 1.14%   |
| 5.4.0-72-generic            | 2         | 1.14%   |
| 5.4.0-58-generic            | 2         | 1.14%   |
| 5.4.0-52-generic            | 2         | 1.14%   |
| 5.4.0-42-generic            | 2         | 1.14%   |
| 5.3.0-40-generic            | 2         | 1.14%   |
| 5.3.0-28-generic            | 2         | 1.14%   |
| 5.15.0-56-generic           | 2         | 1.14%   |
| 5.15.0-41-generic           | 2         | 1.14%   |
| 5.13.0-44-generic           | 2         | 1.14%   |
| 5.13.0-40-generic           | 2         | 1.14%   |
| 5.11.0-7620-generic         | 2         | 1.14%   |
| 5.11.0-40-generic           | 2         | 1.14%   |
| 5.11.0-27-generic           | 2         | 1.14%   |
| 5.10.14-desktop-1omv4002    | 2         | 1.14%   |
| 5.0.0-25-generic            | 2         | 1.14%   |
| 4.19.0-6-amd64              | 2         | 1.14%   |
| 6.5.8-200.fc38.x86_64       | 1         | 0.57%   |
| 6.5.7-arch1-1               | 1         | 0.57%   |
| 6.5.7-200.fc38.x86_64       | 1         | 0.57%   |
| 6.5.6-200.fc38.x86_64       | 1         | 0.57%   |
| 6.4.12-arch1-1              | 1         | 0.57%   |
| 6.4.11-desktop-1omv2390     | 1         | 0.57%   |
| 6.3.6-arch1-1               | 1         | 0.57%   |
| 6.3.6-200.fc38.x86_64       | 1         | 0.57%   |
| 6.3.5-desktop-3omv2390      | 1         | 0.57%   |
| 6.3.5-201.fsync.fc37.x86_64 | 1         | 0.57%   |
| 6.2.5-zen1-1-zen            | 1         | 0.57%   |
| 6.2.11-060211-generic       | 1         | 0.57%   |
| 6.2.0-76060200-generic      | 1         | 0.57%   |
| 6.2.0-36-generic            | 1         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 24        | 13.95%  |
| 5.4.0   | 21        | 12.21%  |
| 5.13.0  | 14        | 8.14%   |
| 5.11.0  | 12        | 6.98%   |
| 5.8.0   | 10        | 5.81%   |
| 5.3.0   | 8         | 4.65%   |
| 5.19.0  | 8         | 4.65%   |
| 4.15.0  | 8         | 4.65%   |
| 5.0.0   | 6         | 3.49%   |
| 4.19.0  | 4         | 2.33%   |
| 6.2.6   | 3         | 1.74%   |
| 6.2.0   | 3         | 1.74%   |
| 6.5.7   | 2         | 1.16%   |
| 6.3.6   | 2         | 1.16%   |
| 6.3.5   | 2         | 1.16%   |
| 5.17.5  | 2         | 1.16%   |
| 5.10.14 | 2         | 1.16%   |
| 5.10.0  | 2         | 1.16%   |
| 4.18.0  | 2         | 1.16%   |
| 6.5.8   | 1         | 0.58%   |
| 6.5.6   | 1         | 0.58%   |
| 6.4.12  | 1         | 0.58%   |
| 6.4.11  | 1         | 0.58%   |
| 6.2.5   | 1         | 0.58%   |
| 6.2.11  | 1         | 0.58%   |
| 6.1.31  | 1         | 0.58%   |
| 6.1.29  | 1         | 0.58%   |
| 6.1.0   | 1         | 0.58%   |
| 5.9.9   | 1         | 0.58%   |
| 5.8.15  | 1         | 0.58%   |
| 5.6.14  | 1         | 0.58%   |
| 5.4.80  | 1         | 0.58%   |
| 5.4.143 | 1         | 0.58%   |
| 5.4.119 | 1         | 0.58%   |
| 5.3.8   | 1         | 0.58%   |
| 5.19.13 | 1         | 0.58%   |
| 5.18.0  | 1         | 0.58%   |
| 5.16.9  | 1         | 0.58%   |
| 5.16.7  | 1         | 0.58%   |
| 5.16.18 | 1         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 26        | 15.48%  |
| 5.4     | 23        | 13.69%  |
| 5.13    | 15        | 8.93%   |
| 5.11    | 14        | 8.33%   |
| 5.8     | 11        | 6.55%   |
| 5.3     | 9         | 5.36%   |
| 5.19    | 9         | 5.36%   |
| 6.2     | 8         | 4.76%   |
| 4.15    | 8         | 4.76%   |
| 5.10    | 7         | 4.17%   |
| 5.0     | 6         | 3.57%   |
| 6.5     | 4         | 2.38%   |
| 6.3     | 4         | 2.38%   |
| 4.19    | 4         | 2.38%   |
| 6.1     | 3         | 1.79%   |
| 5.16    | 3         | 1.79%   |
| 6.4     | 2         | 1.19%   |
| 5.17    | 2         | 1.19%   |
| 4.9     | 2         | 1.19%   |
| 4.18    | 2         | 1.19%   |
| 5.9     | 1         | 0.6%    |
| 5.6     | 1         | 0.6%    |
| 5.18    | 1         | 0.6%    |
| 5.14    | 1         | 0.6%    |
| 5.12    | 1         | 0.6%    |
| 3.13    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 155       | 98.73%  |
| i686   | 2         | 1.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 94        | 57.67%  |
| KDE5            | 25        | 15.34%  |
| X-Cinnamon      | 12        | 7.36%   |
| Unknown         | 11        | 6.75%   |
| XFCE            | 7         | 4.29%   |
| Pantheon        | 3         | 1.84%   |
| KDE4            | 3         | 1.84%   |
| Unity           | 1         | 0.61%   |
| MATE            | 1         | 0.61%   |
| LXQt            | 1         | 0.61%   |
| LXDE            | 1         | 0.61%   |
| GNOME Flashback | 1         | 0.61%   |
| GNOME Classic   | 1         | 0.61%   |
| DWM             | 1         | 0.61%   |
| Deepin          | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 122       | 75.31%  |
| Wayland | 33        | 20.37%  |
| Unknown | 5         | 3.09%   |
| Tty     | 2         | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 62        | 38.51%  |
| GDM     | 43        | 26.71%  |
| SDDM    | 20        | 12.42%  |
| GDM3    | 20        | 12.42%  |
| LightDM | 13        | 8.07%   |
| KDM     | 3         | 1.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 79        | 49.69%  |
| fr_FR   | 49        | 30.82%  |
| Unknown | 15        | 9.43%   |
| en_GB   | 7         | 4.4%    |
| C       | 4         | 2.52%   |
| pt_BR   | 2         | 1.26%   |
| en_IN   | 1         | 0.63%   |
| en_CA   | 1         | 0.63%   |
| ar_TN   | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 91        | 56.52%  |
| BIOS | 70        | 43.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 130       | 82.28%  |
| Btrfs   | 11        | 6.96%   |
| Overlay | 9         | 5.7%    |
| Unknown | 5         | 3.16%   |
| Tmpfs   | 2         | 1.27%   |
| Xfs     | 1         | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 70        | 44.3%   |
| GPT     | 62        | 39.24%  |
| MBR     | 26        | 16.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 141       | 88.68%  |
| Yes       | 18        | 11.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 105       | 67.31%  |
| Yes       | 51        | 32.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 43        | 27.56%  |
| Hewlett-Packard     | 30        | 19.23%  |
| ASUSTek Computer    | 30        | 19.23%  |
| Dell                | 22        | 14.1%   |
| Acer                | 12        | 7.69%   |
| Toshiba             | 8         | 5.13%   |
| MSI                 | 5         | 3.21%   |
| Samsung Electronics | 2         | 1.28%   |
| Valve               | 1         | 0.64%   |
| Sony                | 1         | 0.64%   |
| Packard Bell        | 1         | 0.64%   |
| eMachines           | 1         | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP Pavilion g6                           | 6         | 3.85%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 3         | 1.92%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 3         | 1.92%   |
| Dell Inspiron 5570                       | 3         | 1.92%   |
| MSI GF63 Thin 10SCXR                     | 2         | 1.28%   |
| Lenovo IdeaPad 700-15ISK 80RU            | 2         | 1.28%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 2         | 1.28%   |
| Lenovo IdeaPad 130-15IKB 81H7            | 2         | 1.28%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 1.28%   |
| Dell Inspiron N5110                      | 2         | 1.28%   |
| ASUS X556UV                              | 2         | 1.28%   |
| ASUS X553MA                              | 2         | 1.28%   |
| ASUS X550JX                              | 2         | 1.28%   |
| Acer Aspire E5-571G                      | 2         | 1.28%   |
| Valve Jupiter                            | 1         | 0.64%   |
| Toshiba Satellite Pro L850-B339          | 1         | 0.64%   |
| Toshiba Satellite L550                   | 1         | 0.64%   |
| Toshiba Satellite L500                   | 1         | 0.64%   |
| Toshiba Satellite C855-1KF               | 1         | 0.64%   |
| Toshiba Satellite C650D                  | 1         | 0.64%   |
| Toshiba Satellite C55-C                  | 1         | 0.64%   |
| Toshiba Satellite C50-A489               | 1         | 0.64%   |
| Toshiba Satellite A300                   | 1         | 0.64%   |
| Sony VPCEH36EF                           | 1         | 0.64%   |
| Samsung 530U3BI/530U4BI/530U4BH          | 1         | 0.64%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 0.64%   |
| Packard Bell EasyNote ML65               | 1         | 0.64%   |
| MSI Katana GF66 12UC                     | 1         | 0.64%   |
| MSI GF65 Thin 10UE                       | 1         | 0.64%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.64%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 0.64%   |
| Lenovo V310-15ISK 80SY                   | 1         | 0.64%   |
| Lenovo V15-IIL 82C5                      | 1         | 0.64%   |
| Lenovo V15-IGL 82C3                      | 1         | 0.64%   |
| Lenovo V15-ADA 82C7                      | 1         | 0.64%   |
| Lenovo ThinkPad X240 20AMA0WRFR          | 1         | 0.64%   |
| Lenovo ThinkPad X201 3680FAG             | 1         | 0.64%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 0.64%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100 | 1         | 0.64%   |
| Lenovo ThinkPad T440s 20AQ005NUS         | 1         | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 26        | 16.67%  |
| HP Pavilion           | 13        | 8.33%   |
| Dell Inspiron         | 12        | 7.69%   |
| Acer Aspire           | 9         | 5.77%   |
| Toshiba Satellite     | 8         | 5.13%   |
| Lenovo ThinkPad       | 8         | 5.13%   |
| Dell Latitude         | 6         | 3.85%   |
| HP Laptop             | 5         | 3.21%   |
| HP ProBook            | 4         | 2.56%   |
| ASUS TUF              | 4         | 2.56%   |
| MSI GF63              | 3         | 1.92%   |
| Dell Vostro           | 3         | 1.92%   |
| ASUS VivoBook         | 3         | 1.92%   |
| HP EliteBook          | 2         | 1.28%   |
| HP 250                | 2         | 1.28%   |
| ASUS ZenBook          | 2         | 1.28%   |
| ASUS X556UV           | 2         | 1.28%   |
| ASUS X553MA           | 2         | 1.28%   |
| ASUS X550JX           | 2         | 1.28%   |
| ASUS ROG              | 2         | 1.28%   |
| ASUS ASUS             | 2         | 1.28%   |
| Acer Swift            | 2         | 1.28%   |
| Valve Jupiter         | 1         | 0.64%   |
| Sony VPCEH36EF        | 1         | 0.64%   |
| Samsung 530U3BI       | 1         | 0.64%   |
| Samsung 300E5EV       | 1         | 0.64%   |
| Packard Bell EasyNote | 1         | 0.64%   |
| MSI Katana            | 1         | 0.64%   |
| MSI GF65              | 1         | 0.64%   |
| Lenovo Y520-15IKBN    | 1         | 0.64%   |
| Lenovo V310-15ISK     | 1         | 0.64%   |
| Lenovo V15-IIL        | 1         | 0.64%   |
| Lenovo V15-IGL        | 1         | 0.64%   |
| Lenovo V15-ADA        | 1         | 0.64%   |
| Lenovo ThinkBook      | 1         | 0.64%   |
| Lenovo G580           | 1         | 0.64%   |
| Lenovo G50-70         | 1         | 0.64%   |
| HP Notebook           | 1         | 0.64%   |
| HP Compaq             | 1         | 0.64%   |
| HP 630                | 1         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 23        | 14.74%  |
| 2019 | 17        | 10.9%   |
| 2017 | 15        | 9.62%   |
| 2013 | 13        | 8.33%   |
| 2011 | 13        | 8.33%   |
| 2015 | 11        | 7.05%   |
| 2021 | 10        | 6.41%   |
| 2018 | 10        | 6.41%   |
| 2014 | 9         | 5.77%   |
| 2016 | 8         | 5.13%   |
| 2012 | 8         | 5.13%   |
| 2010 | 6         | 3.85%   |
| 2009 | 5         | 3.21%   |
| 2008 | 5         | 3.21%   |
| 2023 | 2         | 1.28%   |
| 2022 | 1         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 156       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 143       | 91.67%  |
| Enabled  | 13        | 8.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 57        | 36.08%  |
| 3.01-4.0   | 34        | 21.52%  |
| 16.01-24.0 | 30        | 18.99%  |
| 8.01-16.0  | 27        | 17.09%  |
| 32.01-64.0 | 6         | 3.8%    |
| 2.01-3.0   | 3         | 1.9%    |
| 1.01-2.0   | 1         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 54        | 31.95%  |
| 1.01-2.0  | 49        | 28.99%  |
| 4.01-8.0  | 29        | 17.16%  |
| 3.01-4.0  | 26        | 15.38%  |
| 8.01-16.0 | 5         | 2.96%   |
| 0.51-1.0  | 4         | 2.37%   |
| 0.01-0.5  | 1         | 0.59%   |
| Unknown   | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 116       | 72.5%   |
| 2      | 43        | 26.88%  |
| 3      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 52.23%  |
| Yes       | 75        | 47.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 82.69%  |
| No        | 27        | 17.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 98.72%  |
| No        | 2         | 1.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 84.38%  |
| No        | 25        | 15.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Tunisia | 156       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Tunis              | 93        | 54.71%  |
| Sousse             | 7         | 4.12%   |
| Aryanah            | 7         | 4.12%   |
| Nabeul             | 6         | 3.53%   |
| Sfax               | 5         | 2.94%   |
| Bizerte            | 5         | 2.94%   |
| Monastir           | 3         | 1.76%   |
| Centre Urbain Nord | 3         | 1.76%   |
| Rades              | 2         | 1.18%   |
| Mateur             | 2         | 1.18%   |
| Masakin            | 2         | 1.18%   |
| Manouba            | 2         | 1.18%   |
| Jedeida            | 2         | 1.18%   |
| Houmt Souk         | 2         | 1.18%   |
| Gafsa              | 2         | 1.18%   |
| Ben Arous          | 2         | 1.18%   |
| Zarzis             | 1         | 0.59%   |
| Zaouiat Djedidi    | 1         | 0.59%   |
| Wadi Maliz         | 1         | 0.59%   |
| Tebourba           | 1         | 0.59%   |
| Tataouine          | 1         | 0.59%   |
| Tabarka            | 1         | 0.59%   |
| Soliman            | 1         | 0.59%   |
| Rafraf             | 1         | 0.59%   |
| Oued Lill          | 1         | 0.59%   |
| Mahdia             | 1         | 0.59%   |
| Le Bardo           | 1         | 0.59%   |
| La Mohammedia      | 1         | 0.59%   |
| La Marsa           | 1         | 0.59%   |
| La Goulette        | 1         | 0.59%   |
| Kelaa Kebira       | 1         | 0.59%   |
| Kairouan           | 1         | 0.59%   |
| Jendouba           | 1         | 0.59%   |
| Hergla             | 1         | 0.59%   |
| Gremda             | 1         | 0.59%   |
| El Fahs            | 1         | 0.59%   |
| El Battan          | 1         | 0.59%   |
| Chebba             | 1         | 0.59%   |
| Borj el Amri       | 1         | 0.59%   |
| Beni Khiar         | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 43        | 50     | 22.16%  |
| WDC                         | 24        | 32     | 12.37%  |
| Toshiba                     | 24        | 26     | 12.37%  |
| SK hynix                    | 13        | 17     | 6.7%    |
| Samsung Electronics         | 13        | 15     | 6.7%    |
| Team                        | 10        | 12     | 5.15%   |
| Hitachi                     | 9         | 9      | 4.64%   |
| Micron Technology           | 7         | 7      | 3.61%   |
| Intel                       | 7         | 8      | 3.61%   |
| SanDisk                     | 6         | 6      | 3.09%   |
| HGST                        | 6         | 7      | 3.09%   |
| A-DATA Technology           | 5         | 6      | 2.58%   |
| Unknown                     | 4         | 4      | 2.06%   |
| Kingston                    | 4         | 6      | 2.06%   |
| Fujitsu                     | 3         | 3      | 1.55%   |
| PNY                         | 2         | 2      | 1.03%   |
| UMIS                        | 1         | 1      | 0.52%   |
| TwinMOS                     | 1         | 1      | 0.52%   |
| SPCC                        | 1         | 1      | 0.52%   |
| SATAFIRM                    | 1         | 1      | 0.52%   |
| Realtek Semiconductor       | 1         | 1      | 0.52%   |
| Phison Electronics          | 1         | 1      | 0.52%   |
| Phison                      | 1         | 1      | 0.52%   |
| Patriot                     | 1         | 1      | 0.52%   |
| OCZ                         | 1         | 1      | 0.52%   |
| O2 Micro                    | 1         | 1      | 0.52%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.52%   |
| LITEON                      | 1         | 1      | 0.52%   |
| Emtec                       | 1         | 1      | 0.52%   |
| ADATA Technology            | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 16        | 8.16%   |
| Seagate ST500LT012-1DG142 500GB       | 8         | 4.08%   |
| Seagate ST2000LM007-1R8174 2TB        | 6         | 3.06%   |
| Toshiba MQ04ABF100 1TB                | 5         | 2.55%   |
| Hitachi HTS545050A7E380 500GB         | 5         | 2.55%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 1.53%   |
| Toshiba MQ01ABD100 1TB                | 3         | 1.53%   |
| Intel SSDPEKNW512GZL 512GB            | 3         | 1.53%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 1.02%   |
| WDC WD20SPZX-08UA7 2TB                | 2         | 1.02%   |
| WDC WD10SPZX-08Z10 1TB                | 2         | 1.02%   |
| WDC WD10SPCX-24HWST1 1TB              | 2         | 1.02%   |
| Toshiba MK5076GSX 500GB               | 2         | 1.02%   |
| Toshiba MK3275GSX 320GB               | 2         | 1.02%   |
| Team T253X2512G 512GB SSD             | 2         | 1.02%   |
| SK hynix SC311 SATA 256GB SSD         | 2         | 1.02%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 1.02%   |
| SK hynix BC711 HFM256GD3JX013N 256GB  | 2         | 1.02%   |
| Seagate ST9500325AS 500GB             | 2         | 1.02%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 1.02%   |
| Micron 2210_MTFDHBA512QFD 512GB       | 2         | 1.02%   |
| Kingston NVMe SSD Drive 512GB         | 2         | 1.02%   |
| HGST HTS545050A7E380 500GB            | 2         | 1.02%   |
| Fujitsu MHV2100BH PL 100GB            | 2         | 1.02%   |
| A-DATA SU750 256GB SSD                | 2         | 1.02%   |
| WDC WD5000LPZX-60Z10T0 500GB          | 1         | 0.51%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 1         | 0.51%   |
| WDC WD5000LPLX-60ZNTT2 500GB          | 1         | 0.51%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 0.51%   |
| WDC WD5000BPVT-55HXZT3 500GB          | 1         | 0.51%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 0.51%   |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 0.51%   |
| WDC WD2500BPVT-75JJ5T0 250GB          | 1         | 0.51%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.51%   |
| WDC WD10JPVX-80JC3T0 1TB              | 1         | 0.51%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 1         | 0.51%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 0.51%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB  | 1         | 0.51%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB  | 1         | 0.51%   |
| Unknown xD/SD/M.S.                    | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 42        | 49     | 40%     |
| Toshiba | 24        | 26     | 22.86%  |
| WDC     | 21        | 28     | 20%     |
| Hitachi | 9         | 9      | 8.57%   |
| HGST    | 6         | 7      | 5.71%   |
| Fujitsu | 3         | 3      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 6         | 8      | 16.67%  |
| SK hynix            | 6         | 9      | 16.67%  |
| Samsung Electronics | 6         | 8      | 16.67%  |
| SanDisk             | 4         | 4      | 11.11%  |
| A-DATA Technology   | 3         | 4      | 8.33%   |
| PNY                 | 2         | 2      | 5.56%   |
| Micron Technology   | 2         | 2      | 5.56%   |
| TwinMOS             | 1         | 1      | 2.78%   |
| SPCC                | 1         | 1      | 2.78%   |
| SATAFIRM            | 1         | 1      | 2.78%   |
| Patriot             | 1         | 1      | 2.78%   |
| OCZ                 | 1         | 1      | 2.78%   |
| LITEON              | 1         | 1      | 2.78%   |
| Emtec               | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 102       | 122    | 54.55%  |
| NVMe    | 45        | 53     | 24.06%  |
| SSD     | 35        | 44     | 18.72%  |
| MMC     | 3         | 3      | 1.6%    |
| Unknown | 2         | 2      | 1.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 123       | 165    | 70.69%  |
| NVMe | 45        | 53     | 25.86%  |
| SAS  | 3         | 3      | 1.72%   |
| MMC  | 3         | 3      | 1.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 79        | 97     | 58.96%  |
| 0.51-1.0   | 47        | 60     | 35.07%  |
| 1.01-2.0   | 8         | 9      | 5.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 48        | 29.45%  |
| 101-250        | 45        | 27.61%  |
| 501-1000       | 25        | 15.34%  |
| 1001-2000      | 13        | 7.98%   |
| 51-100         | 12        | 7.36%   |
| 1-20           | 10        | 6.13%   |
| 21-50          | 5         | 3.07%   |
| 2001-3000      | 2         | 1.23%   |
| Unknown        | 2         | 1.23%   |
| More than 3000 | 1         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 60        | 36.14%  |
| 101-250   | 32        | 19.28%  |
| 21-50     | 30        | 18.07%  |
| 51-100    | 23        | 13.86%  |
| 501-1000  | 7         | 4.22%   |
| 251-500   | 6         | 3.61%   |
| 1001-2000 | 6         | 3.61%   |
| Unknown   | 2         | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 14.29%  |
| Seagate ST9500325AS 500GB                           | 2         | 2      | 9.52%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 4.76%   |
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 4.76%   |
| WDC WD5000BEVT-22A0RT0 500GB                        | 1         | 1      | 4.76%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 4.76%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 4.76%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 4.76%   |
| Seagate ST9320325AS 320GB                           | 1         | 2      | 4.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 2      | 4.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2      | 4.76%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 4.76%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 4.76%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 4.76%   |
| HGST HTS545050A7E380 500GB                          | 1         | 2      | 4.76%   |
| A-DATA Technology SX8100NP 512GB                    | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 9      | 28.57%  |
| Hitachi           | 5         | 5      | 23.81%  |
| Toshiba           | 4         | 5      | 19.05%  |
| WDC               | 3         | 4      | 14.29%  |
| Micron Technology | 1         | 1      | 4.76%   |
| HGST              | 1         | 2      | 4.76%   |
| A-DATA Technology | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 9      | 31.58%  |
| Hitachi | 5         | 5      | 26.32%  |
| Toshiba | 4         | 5      | 21.05%  |
| WDC     | 3         | 4      | 15.79%  |
| HGST    | 1         | 2      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 25     | 89.47%  |
| NVMe | 1         | 1      | 5.26%   |
| SSD  | 1         | 1      | 5.26%   |

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
| Detected | 77        | 102    | 46.39%  |
| Works    | 69        | 94     | 41.57%  |
| Malfunc  | 19        | 27     | 11.45%  |
| Failed   | 1         | 1      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 131       | 69.68%  |
| AMD                          | 16        | 8.51%   |
| SK hynix                     | 7         | 3.72%   |
| Samsung Electronics          | 7         | 3.72%   |
| SanDisk                      | 5         | 2.66%   |
| Micron Technology            | 5         | 2.66%   |
| Phison Electronics           | 4         | 2.13%   |
| Kingston Technology Company  | 4         | 2.13%   |
| Realtek Semiconductor        | 3         | 1.6%    |
| Union Memory (Shenzhen)      | 1         | 0.53%   |
| Silicon Motion               | 1         | 0.53%   |
| Shenzhen Longsys Electronics | 1         | 0.53%   |
| O2 Micro                     | 1         | 0.53%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.53%   |
| ADATA Technology             | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 8.63%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 7.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 6.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 6.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 5.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 5.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 4.06%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 3.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 6         | 3.05%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 5         | 2.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 2.54%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 2.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 2.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 2.54%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 4         | 2.03%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 4         | 2.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.03%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 1.52%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 3         | 1.52%   |
| Realtek RTS5762 NVMe SSD Controller                                              | 3         | 1.52%   |
| Phison E12 NVMe Controller                                                       | 3         | 1.52%   |
| Intel SSD 660P Series                                                            | 3         | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.52%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.02%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 2         | 1.02%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.02%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                            | 1         | 0.51%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                | 1         | 0.51%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.51%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM NVME SSD (DRAM-less)                | 1         | 0.51%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 1         | 0.51%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 0.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 128       | 66.32%  |
| NVMe | 45        | 23.32%  |
| RAID | 18        | 9.33%   |
| IDE  | 2         | 1.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 133       | 85.26%  |
| AMD    | 23        | 14.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 3.21%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 3.21%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 2.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 2.56%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 2.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.92%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.92%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.92%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.92%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.92%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 1.28%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.28%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.28%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.28%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.28%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 1.28%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.28%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.28%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.28%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.28%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.28%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.28%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.28%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.28%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.28%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.28%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 1.28%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.28%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.28%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.64%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.64%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.64%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 47        | 30.13%  |
| Intel Core i7           | 31        | 19.87%  |
| Intel Core i3           | 25        | 16.03%  |
| Other                   | 15        | 9.62%   |
| AMD Ryzen 5             | 8         | 5.13%   |
| Intel Celeron           | 6         | 3.85%   |
| Intel Pentium           | 5         | 3.21%   |
| Intel Core 2 Duo        | 5         | 3.21%   |
| AMD Ryzen 7             | 3         | 1.92%   |
| AMD Ryzen 3             | 2         | 1.28%   |
| Intel Pentium Dual-Core | 1         | 0.64%   |
| Intel Core m3           | 1         | 0.64%   |
| AMD Sempron             | 1         | 0.64%   |
| AMD E2                  | 1         | 0.64%   |
| AMD E                   | 1         | 0.64%   |
| AMD Athlon              | 1         | 0.64%   |
| AMD A8                  | 1         | 0.64%   |
| AMD A6                  | 1         | 0.64%   |
| AMD A4                  | 1         | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 85        | 54.49%  |
| 4      | 54        | 34.62%  |
| 6      | 9         | 5.77%   |
| 8      | 5         | 3.21%   |
| 14     | 1         | 0.64%   |
| 10     | 1         | 0.64%   |
| 1      | 1         | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 156       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 128       | 82.05%  |
| 1      | 28        | 17.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 155       | 99.36%  |
| Unknown        | 1         | 0.64%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 30%     |
| 0x206a7    | 10        | 6.25%   |
| 0x40651    | 9         | 5.63%   |
| 0x806ea    | 8         | 5%      |
| 0x806ec    | 7         | 4.38%   |
| 0x806c1    | 7         | 4.38%   |
| 0x306a9    | 7         | 4.38%   |
| 0xa0652    | 6         | 3.75%   |
| 0x406e3    | 5         | 3.13%   |
| 0x906ea    | 4         | 2.5%    |
| 0x506e3    | 4         | 2.5%    |
| 0x1067a    | 4         | 2.5%    |
| 0x08108109 | 4         | 2.5%    |
| 0x806e9    | 3         | 1.88%   |
| 0x706e5    | 3         | 1.88%   |
| 0x306d4    | 3         | 1.88%   |
| 0x20655    | 3         | 1.88%   |
| 0x306c3    | 2         | 1.25%   |
| 0x30678    | 2         | 1.25%   |
| 0x08600106 | 2         | 1.25%   |
| 0x08108102 | 2         | 1.25%   |
| 0x06006705 | 2         | 1.25%   |
| 0x06006704 | 2         | 1.25%   |
| 0x906a3    | 1         | 0.63%   |
| 0x706a8    | 1         | 0.63%   |
| 0x6fd      | 1         | 0.63%   |
| 0x506c9    | 1         | 0.63%   |
| 0x406c4    | 1         | 0.63%   |
| 0x40661    | 1         | 0.63%   |
| 0x20652    | 1         | 0.63%   |
| 0x0a50000d | 1         | 0.63%   |
| 0x0a50000c | 1         | 0.63%   |
| 0x0a404101 | 1         | 0.63%   |
| 0x08608103 | 1         | 0.63%   |
| 0x08600104 | 1         | 0.63%   |
| 0x02000032 | 1         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 19.87%  |
| Haswell          | 17        | 10.9%   |
| SandyBridge      | 16        | 10.26%  |
| Skylake          | 12        | 7.69%   |
| TigerLake        | 10        | 6.41%   |
| Zen+             | 7         | 4.49%   |
| Westmere         | 7         | 4.49%   |
| IvyBridge        | 7         | 4.49%   |
| CometLake        | 7         | 4.49%   |
| Penryn           | 5         | 3.21%   |
| IceLake          | 5         | 3.21%   |
| Broadwell        | 5         | 3.21%   |
| Silvermont       | 4         | 2.56%   |
| Excavator        | 4         | 2.56%   |
| Unknown          | 4         | 2.56%   |
| Zen 2            | 3         | 1.92%   |
| Goldmont plus    | 3         | 1.92%   |
| Zen 3            | 2         | 1.28%   |
| Zen              | 1         | 0.64%   |
| Puma             | 1         | 0.64%   |
| K8 & K10 hybrid  | 1         | 0.64%   |
| Goldmont         | 1         | 0.64%   |
| Core             | 1         | 0.64%   |
| Bobcat           | 1         | 0.64%   |
| Alderlake Hybrid | 1         | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 125       | 52.97%  |
| Nvidia | 65        | 27.54%  |
| AMD    | 46        | 19.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 5.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 5.46%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 9         | 3.78%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 3.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 2.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 2.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.52%   |
| Nvidia GM108M [GeForce MX110]                                                            | 5         | 2.1%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 2.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.1%    |
| Intel HD Graphics 620                                                                    | 5         | 2.1%    |
| Intel HD Graphics 5500                                                                   | 5         | 2.1%    |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 1.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.68%   |
| Intel HD Graphics 530                                                                    | 4         | 1.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.68%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.26%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.26%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 1.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.26%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.26%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.26%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.84%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.84%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.84%   |
| Intel HD Graphics 630                                                                    | 2         | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 56        | 35.9%   |
| 1 x Intel      | 51        | 32.69%  |
| 1 x AMD        | 20        | 12.82%  |
| Intel + AMD    | 17        | 10.9%   |
| AMD + Nvidia   | 7         | 4.49%   |
| 2 x AMD        | 2         | 1.28%   |
| 1 x Nvidia     | 2         | 1.28%   |
| 2 x Intel      | 1         | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 122       | 76.25%  |
| Proprietary | 33        | 20.63%  |
| Unknown     | 5         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 57.86%  |
| 1.01-2.0   | 25        | 15.72%  |
| 0.01-0.5   | 14        | 8.81%   |
| 3.01-4.0   | 13        | 8.18%   |
| 0.51-1.0   | 12        | 7.55%   |
| 2.01-3.0   | 2         | 1.26%   |
| 7.01-8.0   | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 34        | 20.24%  |
| AU Optronics            | 33        | 19.64%  |
| BOE                     | 30        | 17.86%  |
| Samsung Electronics     | 26        | 15.48%  |
| LG Display              | 23        | 13.69%  |
| Chi Mei Optoelectronics | 4         | 2.38%   |
| Hewlett-Packard         | 3         | 1.79%   |
| PANDA                   | 2         | 1.19%   |
| Lenovo                  | 2         | 1.19%   |
| HKC                     | 2         | 1.19%   |
| Acer                    | 2         | 1.19%   |
| Valve                   | 1         | 0.6%    |
| Packard Bell            | 1         | 0.6%    |
| LG Philips              | 1         | 0.6%    |
| ITE                     | 1         | 0.6%    |
| Goldstar                | 1         | 0.6%    |
| Dell                    | 1         | 0.6%    |
| BenQ                    | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 4.73%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 2.37%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 4         | 2.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 3         | 1.78%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 3         | 1.78%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 1.78%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.78%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch         | 3         | 1.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.78%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 1.18%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 1.18%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 1.18%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 1.18%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.18%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.18%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                 | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch         | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch        | 2         | 1.18%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.59%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 580x320mm 26.1-inch  | 1         | 0.59%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch      | 1         | 0.59%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch           | 1         | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 71        | 44.94%  |
| 1920x1080 (FHD)  | 69        | 43.67%  |
| 1600x900 (HD+)   | 7         | 4.43%   |
| 3840x2160 (4K)   | 3         | 1.9%    |
| 1280x800 (WXGA)  | 3         | 1.9%    |
| 800x1280         | 1         | 0.63%   |
| 3840x1100        | 1         | 0.63%   |
| 2560x1440 (QHD)  | 1         | 0.63%   |
| 1440x900 (WXGA+) | 1         | 0.63%   |
| 1280x1024 (SXGA) | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 113       | 67.26%  |
| 17     | 11        | 6.55%   |
| 14     | 11        | 6.55%   |
| 13     | 8         | 4.76%   |
| 21     | 6         | 3.57%   |
| 24     | 4         | 2.38%   |
| 27     | 3         | 1.79%   |
| 31     | 2         | 1.19%   |
| 23     | 2         | 1.19%   |
| 18     | 2         | 1.19%   |
| 12     | 2         | 1.19%   |
| 11     | 2         | 1.19%   |
| 20     | 1         | 0.6%    |
| 7      | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 125       | 75.3%   |
| 351-400     | 13        | 7.83%   |
| 501-600     | 9         | 5.42%   |
| 401-500     | 9         | 5.42%   |
| 201-300     | 7         | 4.22%   |
| 601-700     | 2         | 1.2%    |
| 1-100       | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 142       | 94.67%  |
| 16/10 | 4         | 2.67%   |
| 5/4   | 1         | 0.67%   |
| 3/2   | 1         | 0.67%   |
| 3.40  | 1         | 0.67%   |
| 0.67  | 1         | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 113       | 67.26%  |
| 81-90          | 15        | 8.93%   |
| 201-250        | 12        | 7.14%   |
| 121-130        | 8         | 4.76%   |
| 71-80          | 3         | 1.79%   |
| 51-60          | 3         | 1.79%   |
| 301-350        | 3         | 1.79%   |
| 141-150        | 3         | 1.79%   |
| 61-70          | 2         | 1.19%   |
| 351-500        | 2         | 1.19%   |
| 131-140        | 2         | 1.19%   |
| 1-40           | 1         | 0.6%    |
| 151-200        | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 69        | 42.07%  |
| 121-160       | 61        | 37.2%   |
| 51-100        | 25        | 15.24%  |
| 161-240       | 5         | 3.05%   |
| More than 240 | 2         | 1.22%   |
| 1-50          | 2         | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 130       | 82.28%  |
| 2     | 22        | 13.92%  |
| 0     | 6         | 3.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 113       | 43.97%  |
| Intel                             | 56        | 21.79%  |
| Qualcomm Atheros                  | 42        | 16.34%  |
| Broadcom                          | 18        | 7%      |
| Ralink                            | 8         | 3.11%   |
| Broadcom Limited                  | 5         | 1.95%   |
| Ralink Technology                 | 3         | 1.17%   |
| MediaTek                          | 2         | 0.78%   |
| D-Link                            | 2         | 0.78%   |
| TP-Link                           | 1         | 0.39%   |
| Sierra Wireless                   | 1         | 0.39%   |
| OPPO Electronics                  | 1         | 0.39%   |
| Marvell Technology Group          | 1         | 0.39%   |
| ICS Advent                        | 1         | 0.39%   |
| Huawei Technologies               | 1         | 0.39%   |
| Ericsson Business Mobile Networks | 1         | 0.39%   |
| D-Link System                     | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 23.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 11.07%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 4.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 3.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 3.02%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 3.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.68%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 2.68%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 2.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 2.01%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.34%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.01%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.01%   |
| Intel Wireless 8260                                               | 3         | 1.01%   |
| Intel Wireless 7265                                               | 3         | 1.01%   |
| Intel WiFi Link 5100                                              | 3         | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.67%   |
| Intel Wireless 7260                                               | 2         | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.67%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.67%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.67%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.67%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 0.67%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.67%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.67%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 54        | 32.53%  |
| Qualcomm Atheros                  | 39        | 23.49%  |
| Realtek Semiconductor             | 34        | 20.48%  |
| Broadcom                          | 15        | 9.04%   |
| Ralink                            | 8         | 4.82%   |
| Broadcom Limited                  | 5         | 3.01%   |
| Ralink Technology                 | 3         | 1.81%   |
| MediaTek                          | 2         | 1.2%    |
| D-Link                            | 2         | 1.2%    |
| TP-Link                           | 1         | 0.6%    |
| Sierra Wireless                   | 1         | 0.6%    |
| Ericsson Business Mobile Networks | 1         | 0.6%    |
| D-Link System                     | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 7.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 6.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 5.39%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 5.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 4.79%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 4.79%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 4.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 3.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 2.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 2.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.4%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.8%    |
| Intel Wireless 8265 / 8275                                     | 3         | 1.8%    |
| Intel Wireless 8260                                            | 3         | 1.8%    |
| Intel Wireless 7265                                            | 3         | 1.8%    |
| Intel WiFi Link 5100                                           | 3         | 1.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.2%    |
| Intel Wireless 7260                                            | 2         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.2%    |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.2%    |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 1.2%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 1.2%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.2%    |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.6%    |
| Sierra Wireless EM7455                                         | 1         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.6%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 105       | 80.15%  |
| Intel                    | 13        | 9.92%   |
| Qualcomm Atheros         | 5         | 3.82%   |
| Broadcom                 | 4         | 3.05%   |
| OPPO Electronics         | 1         | 0.76%   |
| Marvell Technology Group | 1         | 0.76%   |
| ICS Advent               | 1         | 0.76%   |
| Huawei Technologies      | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 54.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 25.19%  |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.53%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.53%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.53%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.76%   |
| OPPO RMX2027                                                      | 1         | 0.76%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.76%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.76%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.76%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.76%   |
| Huawei TIT-L01                                                    | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 154       | 54.42%  |
| Ethernet | 129       | 45.58%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 132       | 81.99%  |
| Ethernet | 29        | 18.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 125       | 79.62%  |
| 1     | 32        | 20.38%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 34.07%  |
| Qualcomm Atheros Communications | 27        | 20%     |
| Realtek Semiconductor           | 24        | 17.78%  |
| Lite-On Technology              | 11        | 8.15%   |
| Broadcom                        | 7         | 5.19%   |
| IMC Networks                    | 6         | 4.44%   |
| Ralink                          | 5         | 3.7%    |
| Toshiba                         | 3         | 2.22%   |
| Foxconn / Hon Hai               | 3         | 2.22%   |
| Realtek                         | 1         | 0.74%   |
| Hewlett-Packard                 | 1         | 0.74%   |
| Dell                            | 1         | 0.74%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 18        | 13.33%  |
| Intel Bluetooth wireless interface             | 16        | 11.85%  |
| Intel AX201 Bluetooth                          | 16        | 11.85%  |
| Qualcomm Atheros  Bluetooth Device             | 14        | 10.37%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 12        | 8.89%   |
| Ralink RT3290 Bluetooth                        | 5         | 3.7%    |
| Qualcomm Atheros AR3011 Bluetooth              | 5         | 3.7%    |
| Realtek  Bluetooth 4.2 Adapter                 | 4         | 2.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 4         | 2.96%   |
| Lite-On Bluetooth Device                       | 4         | 2.96%   |
| IMC Networks Bluetooth Radio                   | 4         | 2.96%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device   | 3         | 2.22%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 3         | 2.22%   |
| Realtek RTL8723B Bluetooth                     | 2         | 1.48%   |
| Qualcomm Atheros AR9462 Bluetooth              | 2         | 1.48%   |
| Lite-On BCM43142A0                             | 2         | 1.48%   |
| IMC Networks Wireless_Device                   | 2         | 1.48%   |
| Foxconn / Hon Hai Bluetooth Device             | 2         | 1.48%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 2         | 1.48%   |
| Toshiba RT Bluetooth Radio                     | 1         | 0.74%   |
| Toshiba Bluetooth USB Host Controller          | 1         | 0.74%   |
| Toshiba BCM43142A0                             | 1         | 0.74%   |
| Realtek Bluetooth Radio                        | 1         | 0.74%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 0.74%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 0.74%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 0.74%   |
| Intel Bluetooth Device                         | 1         | 0.74%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 0.74%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth  | 1         | 0.74%   |
| Dell DW375 Bluetooth Module                    | 1         | 0.74%   |
| Broadcom HP Portable Valentine                 | 1         | 0.74%   |
| Broadcom BCM43142 Bluetooth 4.0                | 1         | 0.74%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 133       | 70%     |
| AMD                       | 29        | 15.26%  |
| Nvidia                    | 24        | 12.63%  |
| C-Media Electronics       | 2         | 1.05%   |
| Sennheiser Communications | 1         | 0.53%   |
| JMTek                     | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 10.27%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 6.7%    |
| Intel 8 Series HD Audio Controller                                                                | 13        | 5.8%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 5.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 4.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 4.46%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 3.13%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 3.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.68%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 2.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 2.23%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.23%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.79%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.89%   |
| Nvidia Audio device                                                                               | 2         | 0.89%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.89%   |
| C-Media Electronics USB Audio Device                                                              | 2         | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.89%   |
| Sennheiser Communications Headset [PC 8]                                                          | 1         | 0.45%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.45%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 30.89%  |
| SK hynix            | 24        | 19.51%  |
| Micron Technology   | 16        | 13.01%  |
| Team                | 12        | 9.76%   |
| A-DATA Technology   | 9         | 7.32%   |
| Unknown             | 4         | 3.25%   |
| Nanya Technology    | 4         | 3.25%   |
| Crucial             | 4         | 3.25%   |
| Ramaxel Technology  | 3         | 2.44%   |
| Kingston            | 3         | 2.44%   |
| Toshiba             | 2         | 1.63%   |
| Elpida              | 2         | 1.63%   |
| Hikvision           | 1         | 0.81%   |
| ASint Technology    | 1         | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s        | 3         | 2.31%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 3         | 2.31%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 3         | 2.31%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 2.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 2.31%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 3         | 2.31%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 3         | 2.31%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                 | 3         | 2.31%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s          | 2         | 1.54%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s      | 2         | 1.54%   |
| Team RAM TEAMGROUP-SD4-3200 8GB Row Of Chips DDR4 2400MT/s  | 2         | 1.54%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s       | 2         | 1.54%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s       | 2         | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.54%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s       | 2         | 1.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 1.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 1.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 1.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 1.54%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 1.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 1.54%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 2         | 1.54%   |
| Micron RAM MT40A512M16TB-062E:R 4GB SODIMM DDR4 3200MT/s    | 2         | 1.54%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 2         | 1.54%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.77%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s              | 1         | 0.77%   |
| Unknown RAM Module 4096MB SODIMM DDR3                       | 1         | 0.77%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s               | 1         | 0.77%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s       | 1         | 0.77%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s        | 1         | 0.77%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s                 | 1         | 0.77%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s       | 1         | 0.77%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.77%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 1         | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 0.77%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 1         | 0.77%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s      | 1         | 0.77%   |
| SK hynix RAM HMCG66MEBSA095N 8GB SODIMM DDR5 4800MT/s       | 1         | 0.77%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 0.77%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 1         | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 58        | 59.79%  |
| DDR3   | 27        | 27.84%  |
| DDR2   | 4         | 4.12%   |
| SDRAM  | 2         | 2.06%   |
| LPDDR4 | 2         | 2.06%   |
| LPDDR3 | 2         | 2.06%   |
| DDR5   | 2         | 2.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 87%     |
| Row Of Chips | 12        | 12%     |
| Chip         | 1         | 1%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 42        | 35.29%  |
| 4096  | 40        | 33.61%  |
| 16384 | 17        | 14.29%  |
| 2048  | 12        | 10.08%  |
| 32768 | 6         | 5.04%   |
| 1024  | 2         | 1.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 28        | 25%     |
| 3200    | 24        | 21.43%  |
| 1600    | 16        | 14.29%  |
| 2400    | 11        | 9.82%   |
| 1334    | 9         | 8.04%   |
| 3266    | 3         | 2.68%   |
| 2133    | 3         | 2.68%   |
| 1867    | 3         | 2.68%   |
| 8400    | 2         | 1.79%   |
| 4800    | 2         | 1.79%   |
| 4199    | 2         | 1.79%   |
| 1333    | 2         | 1.79%   |
| 1066    | 2         | 1.79%   |
| 1067    | 1         | 0.89%   |
| 975     | 1         | 0.89%   |
| 800     | 1         | 0.89%   |
| 667     | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

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
| Chicony Electronics                    | 34        | 23.78%  |
| IMC Networks                           | 20        | 13.99%  |
| Realtek Semiconductor                  | 17        | 11.89%  |
| Microdia                               | 12        | 8.39%   |
| Suyin                                  | 8         | 5.59%   |
| Syntek                                 | 7         | 4.9%    |
| Sunplus Innovation Technology          | 7         | 4.9%    |
| Bison Electronics                      | 7         | 4.9%    |
| Luxvisions Innotech Limited            | 5         | 3.5%    |
| Lite-On Technology                     | 5         | 3.5%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.5%    |
| Acer                                   | 5         | 3.5%    |
| Quanta                                 | 4         | 2.8%    |
| Silicon Motion                         | 1         | 0.7%    |
| Samsung Electronics                    | 1         | 0.7%    |
| Ricoh                                  | 1         | 0.7%    |
| Lenovo                                 | 1         | 0.7%    |
| Importek                               | 1         | 0.7%    |
| Apple                                  | 1         | 0.7%    |
| Alcor Micro                            | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 6.29%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 8         | 5.59%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 3.5%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 5         | 3.5%    |
| IMC Networks Integrated Camera                              | 5         | 3.5%    |
| Syntek Integrated Camera                                    | 4         | 2.8%    |
| Realtek USB Camera                                          | 4         | 2.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                          | 4         | 2.8%    |
| Chicony HD WebCam                                           | 4         | 2.8%    |
| Acer Integrated Camera                                      | 4         | 2.8%    |
| Syntek EasyCamera                                           | 3         | 2.1%    |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 2.1%    |
| Realtek Integrated_Webcam_HD                                | 3         | 2.1%    |
| Microdia Laptop_Integrated_Webcam_HD                        | 3         | 2.1%    |
| Microdia Integrated_Webcam_HD                               | 3         | 2.1%    |
| Lite-On Integrated Camera                                   | 3         | 2.1%    |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 2.1%    |
| Suyin HP TrueVision HD                                      | 2         | 1.4%    |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.4%    |
| Realtek EasyCamera                                          | 2         | 1.4%    |
| Quanta VGA WebCam                                           | 2         | 1.4%    |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.4%    |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.4%    |
| Chicony Lenovo EasyCamera                                   | 2         | 1.4%    |
| Chicony EasyCamera                                          | 2         | 1.4%    |
| Bison Lenovo EasyCamera                                     | 2         | 1.4%    |
| Bison HD Webcam                                             | 2         | 1.4%    |
| Suyin USB 2.0 Camera                                        | 1         | 0.7%    |
| Suyin Laptop_Integrated_Webcam_2HDM                         | 1         | 0.7%    |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.7%    |
| Suyin HP Integrated Webcam                                  | 1         | 0.7%    |
| Suyin HD WebCam                                             | 1         | 0.7%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.7%    |
| Sunplus HD User Facing                                      | 1         | 0.7%    |
| Sunplus Dell HD Webcam                                      | 1         | 0.7%    |
| Silicon Motion WebCam SC-13HDL11431N                        | 1         | 0.7%    |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.7%    |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 0.7%    |
| Realtek Integrated Webcam_HD                                | 1         | 0.7%    |
| Realtek Integrated Webcam                                   | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 50%     |
| LighTuning Technology      | 2         | 20%     |
| Upek                       | 1         | 10%     |
| Synaptics                  | 1         | 10%     |
| Shenzhen Goodix Technology | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 10%     |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 10%     |
| Validity Sensors Synaptics WBDI                        | 1         | 10%     |
| Validity Sensors Fingerprint scanner                   | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 10%     |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Alcor Micro | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 115       | 69.28%  |
| 1     | 41        | 24.7%   |
| 3     | 5         | 3.01%   |
| 2     | 4         | 2.41%   |
| 4     | 1         | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 17        | 27.42%  |
| Net/wireless             | 12        | 19.35%  |
| Fingerprint reader       | 10        | 16.13%  |
| Bluetooth                | 7         | 11.29%  |
| Communication controller | 4         | 6.45%   |
| Chipcard                 | 4         | 6.45%   |
| Storage                  | 2         | 3.23%   |
| Camera                   | 2         | 3.23%   |
| Sound                    | 1         | 1.61%   |
| Network                  | 1         | 1.61%   |
| Multimedia controller    | 1         | 1.61%   |
| Card reader              | 1         | 1.61%   |

