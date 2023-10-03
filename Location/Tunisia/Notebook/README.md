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

Total: 216

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 38        | 23.6%   |
| Ubuntu 22.04       | 12        | 7.45%   |
| Ubuntu 18.04       | 12        | 7.45%   |
| Ubuntu 21.10       | 5         | 3.11%   |
| Zorin 16           | 3         | 1.86%   |
| Zorin 15           | 3         | 1.86%   |
| Pop!_OS 22.04      | 3         | 1.86%   |
| OpenMandriva 23.03 | 3         | 1.86%   |
| KDE neon 22.04     | 3         | 1.86%   |
| Debian 10          | 3         | 1.86%   |
| Ubuntu 21.04       | 2         | 1.24%   |
| Ubuntu 20.10       | 2         | 1.24%   |
| Ubuntu 16.04       | 2         | 1.24%   |
| Pop!_OS 21.04      | 2         | 1.24%   |
| OpenMandriva 4.2   | 2         | 1.24%   |
| Manjaro 21.1.0     | 2         | 1.24%   |
| LMDE 4             | 2         | 1.24%   |
| Linux Mint 21.2    | 2         | 1.24%   |
| Linux Mint 21.1    | 2         | 1.24%   |
| Linux Mint 20.3    | 2         | 1.24%   |
| Linux Mint 20.2    | 2         | 1.24%   |
| KDE neon 20.04     | 2         | 1.24%   |
| Fedora 35          | 2         | 1.24%   |
| Fedora 33          | 2         | 1.24%   |
| ArcoLinux Rolling  | 2         | 1.24%   |
| Arch Rolling       | 2         | 1.24%   |
| Xubuntu 18.04      | 1         | 0.62%   |
| Xero Rolling       | 1         | 0.62%   |
| Ubuntu Unity 16.04 | 1         | 0.62%   |
| Ubuntu 19.10       | 1         | 0.62%   |
| Sodalite 35        | 1         | 0.62%   |
| ROSA R8.1          | 1         | 0.62%   |
| ROSA R11           | 1         | 0.62%   |
| ROSA R10           | 1         | 0.62%   |
| ROSA 12.3          | 1         | 0.62%   |
| Pop!_OS 20.10      | 1         | 0.62%   |
| OpenMandriva 4.3   | 1         | 0.62%   |
| OpenMandriva 23.08 | 1         | 0.62%   |
| OpenMandriva 23.07 | 1         | 0.62%   |
| Nobara 37          | 1         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 71        | 45.81%  |
| Linux Mint   | 11        | 7.1%    |
| OpenMandriva | 8         | 5.16%   |
| Zorin        | 6         | 3.87%   |
| Pop!_OS      | 6         | 3.87%   |
| Manjaro      | 6         | 3.87%   |
| Fedora       | 6         | 3.87%   |
| Debian       | 6         | 3.87%   |
| ROSA         | 4         | 2.58%   |
| KDE neon     | 4         | 2.58%   |
| Endless      | 4         | 2.58%   |
| Arch         | 3         | 1.94%   |
| Lubuntu      | 2         | 1.29%   |
| LMDE         | 2         | 1.29%   |
| Elementary   | 2         | 1.29%   |
| ArcoLinux    | 2         | 1.29%   |
| Xubuntu      | 1         | 0.65%   |
| Xero         | 1         | 0.65%   |
| Ubuntu Unity | 1         | 0.65%   |
| Sodalite     | 1         | 0.65%   |
| Nobara       | 1         | 0.65%   |
| MX           | 1         | 0.65%   |
| Kubuntu      | 1         | 0.65%   |
| Gentoo       | 1         | 0.65%   |
| Garuda Linux | 1         | 0.65%   |
| EndeavourOS  | 1         | 0.65%   |
| Deepin       | 1         | 0.65%   |
| BlackPanther | 1         | 0.65%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.13.0-28-generic           | 4         | 2.38%   |
| 6.2.6-desktop-1omv2390      | 3         | 1.79%   |
| 5.3.0-46-generic            | 3         | 1.79%   |
| 5.15.0-58-generic           | 3         | 1.79%   |
| 5.15.0-52-generic           | 3         | 1.79%   |
| 5.15.0-46-generic           | 3         | 1.79%   |
| 5.15.0-43-generic           | 3         | 1.79%   |
| 5.11.0-38-generic           | 3         | 1.79%   |
| 5.8.0-38-generic            | 2         | 1.19%   |
| 5.8.0-14-generic            | 2         | 1.19%   |
| 5.4.0-72-generic            | 2         | 1.19%   |
| 5.4.0-58-generic            | 2         | 1.19%   |
| 5.4.0-52-generic            | 2         | 1.19%   |
| 5.4.0-42-generic            | 2         | 1.19%   |
| 5.3.0-40-generic            | 2         | 1.19%   |
| 5.3.0-28-generic            | 2         | 1.19%   |
| 5.15.0-56-generic           | 2         | 1.19%   |
| 5.15.0-41-generic           | 2         | 1.19%   |
| 5.13.0-44-generic           | 2         | 1.19%   |
| 5.13.0-40-generic           | 2         | 1.19%   |
| 5.11.0-7620-generic         | 2         | 1.19%   |
| 5.11.0-40-generic           | 2         | 1.19%   |
| 5.11.0-27-generic           | 2         | 1.19%   |
| 5.10.14-desktop-1omv4002    | 2         | 1.19%   |
| 5.0.0-25-generic            | 2         | 1.19%   |
| 4.19.0-6-amd64              | 2         | 1.19%   |
| 6.4.12-arch1-1              | 1         | 0.6%    |
| 6.4.11-desktop-1omv2390     | 1         | 0.6%    |
| 6.3.6-arch1-1               | 1         | 0.6%    |
| 6.3.6-200.fc38.x86_64       | 1         | 0.6%    |
| 6.3.5-desktop-3omv2390      | 1         | 0.6%    |
| 6.3.5-201.fsync.fc37.x86_64 | 1         | 0.6%    |
| 6.2.5-zen1-1-zen            | 1         | 0.6%    |
| 6.2.11-060211-generic       | 1         | 0.6%    |
| 6.2.0-76060200-generic      | 1         | 0.6%    |
| 6.1.31-1-lts                | 1         | 0.6%    |
| 6.1.29-1-MANJARO            | 1         | 0.6%    |
| 6.1.0-9-amd64               | 1         | 0.6%    |
| 5.9.9-arch1-1               | 1         | 0.6%    |
| 5.8.15-301.fc33.x86_64      | 1         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 23        | 14.02%  |
| 5.4.0   | 21        | 12.8%   |
| 5.13.0  | 13        | 7.93%   |
| 5.11.0  | 12        | 7.32%   |
| 5.8.0   | 10        | 6.1%    |
| 5.3.0   | 8         | 4.88%   |
| 5.19.0  | 8         | 4.88%   |
| 4.15.0  | 8         | 4.88%   |
| 5.0.0   | 6         | 3.66%   |
| 4.19.0  | 4         | 2.44%   |
| 6.2.6   | 3         | 1.83%   |
| 6.3.6   | 2         | 1.22%   |
| 6.3.5   | 2         | 1.22%   |
| 5.17.5  | 2         | 1.22%   |
| 5.10.14 | 2         | 1.22%   |
| 5.10.0  | 2         | 1.22%   |
| 4.18.0  | 2         | 1.22%   |
| 6.4.12  | 1         | 0.61%   |
| 6.4.11  | 1         | 0.61%   |
| 6.2.5   | 1         | 0.61%   |
| 6.2.11  | 1         | 0.61%   |
| 6.2.0   | 1         | 0.61%   |
| 6.1.31  | 1         | 0.61%   |
| 6.1.29  | 1         | 0.61%   |
| 6.1.0   | 1         | 0.61%   |
| 5.9.9   | 1         | 0.61%   |
| 5.8.15  | 1         | 0.61%   |
| 5.6.14  | 1         | 0.61%   |
| 5.4.80  | 1         | 0.61%   |
| 5.4.143 | 1         | 0.61%   |
| 5.4.119 | 1         | 0.61%   |
| 5.3.8   | 1         | 0.61%   |
| 5.19.13 | 1         | 0.61%   |
| 5.18.0  | 1         | 0.61%   |
| 5.16.9  | 1         | 0.61%   |
| 5.16.7  | 1         | 0.61%   |
| 5.16.18 | 1         | 0.61%   |
| 5.16.11 | 1         | 0.61%   |
| 5.15.75 | 1         | 0.61%   |
| 5.15.46 | 1         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 25        | 15.63%  |
| 5.4     | 23        | 14.38%  |
| 5.13    | 14        | 8.75%   |
| 5.11    | 14        | 8.75%   |
| 5.8     | 11        | 6.88%   |
| 5.3     | 9         | 5.63%   |
| 5.19    | 9         | 5.63%   |
| 4.15    | 8         | 5%      |
| 5.10    | 7         | 4.38%   |
| 6.2     | 6         | 3.75%   |
| 5.0     | 6         | 3.75%   |
| 6.3     | 4         | 2.5%    |
| 4.19    | 4         | 2.5%    |
| 6.1     | 3         | 1.88%   |
| 5.16    | 3         | 1.88%   |
| 6.4     | 2         | 1.25%   |
| 5.17    | 2         | 1.25%   |
| 4.9     | 2         | 1.25%   |
| 4.18    | 2         | 1.25%   |
| 5.9     | 1         | 0.63%   |
| 5.6     | 1         | 0.63%   |
| 5.18    | 1         | 0.63%   |
| 5.14    | 1         | 0.63%   |
| 5.12    | 1         | 0.63%   |
| 3.13    | 1         | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 147       | 98.66%  |
| i686   | 2         | 1.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 89        | 57.42%  |
| KDE5            | 23        | 14.84%  |
| X-Cinnamon      | 11        | 7.1%    |
| Unknown         | 11        | 7.1%    |
| XFCE            | 7         | 4.52%   |
| Pantheon        | 3         | 1.94%   |
| KDE4            | 3         | 1.94%   |
| Unity           | 1         | 0.65%   |
| MATE            | 1         | 0.65%   |
| LXQt            | 1         | 0.65%   |
| LXDE            | 1         | 0.65%   |
| GNOME Flashback | 1         | 0.65%   |
| GNOME Classic   | 1         | 0.65%   |
| DWM             | 1         | 0.65%   |
| Deepin          | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 118       | 76.62%  |
| Wayland | 29        | 18.83%  |
| Unknown | 5         | 3.25%   |
| Tty     | 2         | 1.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 36.6%   |
| GDM     | 43        | 28.1%   |
| SDDM    | 20        | 13.07%  |
| GDM3    | 18        | 11.76%  |
| LightDM | 13        | 8.5%    |
| KDM     | 3         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 75        | 49.67%  |
| fr_FR   | 46        | 30.46%  |
| Unknown | 15        | 9.93%   |
| en_GB   | 6         | 3.97%   |
| C       | 4         | 2.65%   |
| pt_BR   | 2         | 1.32%   |
| en_IN   | 1         | 0.66%   |
| en_CA   | 1         | 0.66%   |
| ar_TN   | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 86        | 56.21%  |
| BIOS | 67        | 43.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 126       | 84%     |
| Overlay | 9         | 6%      |
| Btrfs   | 7         | 4.67%   |
| Unknown | 5         | 3.33%   |
| Tmpfs   | 2         | 1.33%   |
| Xfs     | 1         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 64        | 42.67%  |
| GPT     | 60        | 40%     |
| MBR     | 26        | 17.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 133       | 88.08%  |
| Yes       | 18        | 11.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 98        | 66.22%  |
| Yes       | 50        | 33.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 42        | 28.38%  |
| Hewlett-Packard     | 28        | 18.92%  |
| ASUSTek Computer    | 28        | 18.92%  |
| Dell                | 21        | 14.19%  |
| Acer                | 12        | 8.11%   |
| Toshiba             | 7         | 4.73%   |
| MSI                 | 5         | 3.38%   |
| Samsung Electronics | 2         | 1.35%   |
| Sony                | 1         | 0.68%   |
| Packard Bell        | 1         | 0.68%   |
| eMachines           | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP Pavilion g6                           | 5         | 3.38%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 3         | 2.03%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 3         | 2.03%   |
| MSI GF63 Thin 10SCXR                     | 2         | 1.35%   |
| Lenovo IdeaPad 700-15ISK 80RU            | 2         | 1.35%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 2         | 1.35%   |
| Lenovo IdeaPad 130-15IKB 81H7            | 2         | 1.35%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 1.35%   |
| Dell Inspiron N5110                      | 2         | 1.35%   |
| Dell Inspiron 5570                       | 2         | 1.35%   |
| ASUS X556UV                              | 2         | 1.35%   |
| ASUS X553MA                              | 2         | 1.35%   |
| ASUS X550JX                              | 2         | 1.35%   |
| Acer Aspire E5-571G                      | 2         | 1.35%   |
| Toshiba Satellite Pro L850-B339          | 1         | 0.68%   |
| Toshiba Satellite L550                   | 1         | 0.68%   |
| Toshiba Satellite L500                   | 1         | 0.68%   |
| Toshiba Satellite C650D                  | 1         | 0.68%   |
| Toshiba Satellite C55-C                  | 1         | 0.68%   |
| Toshiba Satellite C50-A489               | 1         | 0.68%   |
| Toshiba Satellite A300                   | 1         | 0.68%   |
| Sony VPCEH36EF                           | 1         | 0.68%   |
| Samsung 530U3BI/530U4BI/530U4BH          | 1         | 0.68%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 0.68%   |
| Packard Bell EasyNote ML65               | 1         | 0.68%   |
| MSI Katana GF66 12UC                     | 1         | 0.68%   |
| MSI GF65 Thin 10UE                       | 1         | 0.68%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.68%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 0.68%   |
| Lenovo V310-15ISK 80SY                   | 1         | 0.68%   |
| Lenovo V15-IIL 82C5                      | 1         | 0.68%   |
| Lenovo V15-IGL 82C3                      | 1         | 0.68%   |
| Lenovo ThinkPad X240 20AMA0WRFR          | 1         | 0.68%   |
| Lenovo ThinkPad X201 3680FAG             | 1         | 0.68%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100 | 1         | 0.68%   |
| Lenovo ThinkPad T440s 20AQ005NUS         | 1         | 0.68%   |
| Lenovo ThinkPad E15 20RD001SFE           | 1         | 0.68%   |
| Lenovo ThinkPad E15 20RD001QFE           | 1         | 0.68%   |
| Lenovo ThinkPad E14 20RA000KFE           | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 26        | 17.57%  |
| HP Pavilion           | 12        | 8.11%   |
| Dell Inspiron         | 11        | 7.43%   |
| Acer Aspire           | 9         | 6.08%   |
| Lenovo ThinkPad       | 8         | 5.41%   |
| Toshiba Satellite     | 7         | 4.73%   |
| Dell Latitude         | 6         | 4.05%   |
| HP Laptop             | 5         | 3.38%   |
| ASUS TUF              | 4         | 2.7%    |
| MSI GF63              | 3         | 2.03%   |
| HP ProBook            | 3         | 2.03%   |
| Dell Vostro           | 3         | 2.03%   |
| HP EliteBook          | 2         | 1.35%   |
| HP 250                | 2         | 1.35%   |
| ASUS ZenBook          | 2         | 1.35%   |
| ASUS X556UV           | 2         | 1.35%   |
| ASUS X553MA           | 2         | 1.35%   |
| ASUS X550JX           | 2         | 1.35%   |
| ASUS VivoBook         | 2         | 1.35%   |
| ASUS ROG              | 2         | 1.35%   |
| ASUS ASUS             | 2         | 1.35%   |
| Acer Swift            | 2         | 1.35%   |
| Sony VPCEH36EF        | 1         | 0.68%   |
| Samsung 530U3BI       | 1         | 0.68%   |
| Samsung 300E5EV       | 1         | 0.68%   |
| Packard Bell EasyNote | 1         | 0.68%   |
| MSI Katana            | 1         | 0.68%   |
| MSI GF65              | 1         | 0.68%   |
| Lenovo Y520-15IKBN    | 1         | 0.68%   |
| Lenovo V310-15ISK     | 1         | 0.68%   |
| Lenovo V15-IIL        | 1         | 0.68%   |
| Lenovo V15-IGL        | 1         | 0.68%   |
| Lenovo ThinkBook      | 1         | 0.68%   |
| Lenovo G580           | 1         | 0.68%   |
| Lenovo G50-70         | 1         | 0.68%   |
| HP Notebook           | 1         | 0.68%   |
| HP Compaq             | 1         | 0.68%   |
| HP 630                | 1         | 0.68%   |
| HP 14                 | 1         | 0.68%   |
| eMachines E725        | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 21        | 14.19%  |
| 2019 | 17        | 11.49%  |
| 2017 | 15        | 10.14%  |
| 2013 | 12        | 8.11%   |
| 2011 | 12        | 8.11%   |
| 2018 | 10        | 6.76%   |
| 2015 | 10        | 6.76%   |
| 2021 | 9         | 6.08%   |
| 2014 | 9         | 6.08%   |
| 2012 | 8         | 5.41%   |
| 2016 | 7         | 4.73%   |
| 2010 | 6         | 4.05%   |
| 2009 | 5         | 3.38%   |
| 2008 | 5         | 3.38%   |
| 2023 | 1         | 0.68%   |
| 2022 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 148       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 136       | 91.89%  |
| Enabled  | 12        | 8.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 148       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 55        | 36.67%  |
| 3.01-4.0   | 32        | 21.33%  |
| 16.01-24.0 | 29        | 19.33%  |
| 8.01-16.0  | 25        | 16.67%  |
| 32.01-64.0 | 5         | 3.33%   |
| 2.01-3.0   | 3         | 2%      |
| 1.01-2.0   | 1         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 50        | 31.06%  |
| 1.01-2.0  | 48        | 29.81%  |
| 4.01-8.0  | 29        | 18.01%  |
| 3.01-4.0  | 24        | 14.91%  |
| 8.01-16.0 | 4         | 2.48%   |
| 0.51-1.0  | 4         | 2.48%   |
| 0.01-0.5  | 1         | 0.62%   |
| Unknown   | 1         | 0.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 110       | 72.37%  |
| 2      | 41        | 26.97%  |
| 3      | 1         | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 53.02%  |
| Yes       | 70        | 46.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 83.78%  |
| No        | 24        | 16.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 98.65%  |
| No        | 2         | 1.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 127       | 83.55%  |
| No        | 25        | 16.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Tunisia | 148       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Tunis              | 87        | 53.7%   |
| Sousse             | 7         | 4.32%   |
| Aryanah            | 7         | 4.32%   |
| Nabeul             | 6         | 3.7%    |
| Sfax               | 5         | 3.09%   |
| Bizerte            | 5         | 3.09%   |
| Centre Urbain Nord | 3         | 1.85%   |
| Rades              | 2         | 1.23%   |
| Monastir           | 2         | 1.23%   |
| Mateur             | 2         | 1.23%   |
| Masakin            | 2         | 1.23%   |
| Manouba            | 2         | 1.23%   |
| Jedeida            | 2         | 1.23%   |
| Houmt Souk         | 2         | 1.23%   |
| Gafsa              | 2         | 1.23%   |
| Ben Arous          | 2         | 1.23%   |
| Zarzis             | 1         | 0.62%   |
| Zaouiat Djedidi    | 1         | 0.62%   |
| Wadi Maliz         | 1         | 0.62%   |
| Tebourba           | 1         | 0.62%   |
| Tataouine          | 1         | 0.62%   |
| Tabarka            | 1         | 0.62%   |
| Soliman            | 1         | 0.62%   |
| Rafraf             | 1         | 0.62%   |
| Oued Lill          | 1         | 0.62%   |
| Mahdia             | 1         | 0.62%   |
| Le Bardo           | 1         | 0.62%   |
| La Marsa           | 1         | 0.62%   |
| La Goulette        | 1         | 0.62%   |
| Kelaa Kebira       | 1         | 0.62%   |
| Kairouan           | 1         | 0.62%   |
| Jendouba           | 1         | 0.62%   |
| Hergla             | 1         | 0.62%   |
| Gremda             | 1         | 0.62%   |
| El Fahs            | 1         | 0.62%   |
| El Battan          | 1         | 0.62%   |
| Chebba             | 1         | 0.62%   |
| Borj el Amri       | 1         | 0.62%   |
| Beni Khiar         | 1         | 0.62%   |
| Belvedere          | 1         | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 42        | 49     | 22.7%   |
| WDC                         | 24        | 32     | 12.97%  |
| Toshiba                     | 23        | 25     | 12.43%  |
| Samsung Electronics         | 13        | 15     | 7.03%   |
| SK hynix                    | 12        | 16     | 6.49%   |
| Team                        | 10        | 12     | 5.41%   |
| Hitachi                     | 9         | 9      | 4.86%   |
| Intel                       | 7         | 8      | 3.78%   |
| SanDisk                     | 6         | 6      | 3.24%   |
| Micron Technology           | 6         | 6      | 3.24%   |
| HGST                        | 6         | 7      | 3.24%   |
| Kingston                    | 4         | 6      | 2.16%   |
| A-DATA Technology           | 4         | 5      | 2.16%   |
| Unknown                     | 3         | 3      | 1.62%   |
| Fujitsu                     | 3         | 3      | 1.62%   |
| UMIS                        | 1         | 1      | 0.54%   |
| TwinMOS                     | 1         | 1      | 0.54%   |
| SPCC                        | 1         | 1      | 0.54%   |
| SATAFIRM                    | 1         | 1      | 0.54%   |
| Realtek Semiconductor       | 1         | 1      | 0.54%   |
| PNY                         | 1         | 1      | 0.54%   |
| Phison Electronics          | 1         | 1      | 0.54%   |
| Phison                      | 1         | 1      | 0.54%   |
| Patriot                     | 1         | 1      | 0.54%   |
| OCZ                         | 1         | 1      | 0.54%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.54%   |
| LITEON                      | 1         | 1      | 0.54%   |
| ADATA Technology            | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 16        | 8.56%   |
| Seagate ST500LT012-1DG142 500GB       | 8         | 4.28%   |
| Toshiba MQ04ABF100 1TB                | 5         | 2.67%   |
| Seagate ST2000LM007-1R8174 2TB        | 5         | 2.67%   |
| Hitachi HTS545050A7E380 500GB         | 5         | 2.67%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 1.6%    |
| Toshiba MQ01ABD100 1TB                | 3         | 1.6%    |
| Intel SSDPEKNW512GZL 512GB            | 3         | 1.6%    |
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 1.07%   |
| WDC WD20SPZX-08UA7 2TB                | 2         | 1.07%   |
| WDC WD10SPZX-08Z10 1TB                | 2         | 1.07%   |
| WDC WD10SPCX-24HWST1 1TB              | 2         | 1.07%   |
| Toshiba MK5076GSX 500GB               | 2         | 1.07%   |
| Toshiba MK3275GSX 320GB               | 2         | 1.07%   |
| Team T253X2512G 512GB SSD             | 2         | 1.07%   |
| SK hynix SC311 SATA 256GB SSD         | 2         | 1.07%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 1.07%   |
| Seagate ST9500325AS 500GB             | 2         | 1.07%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 1.07%   |
| Micron 2210_MTFDHBA512QFD 512GB       | 2         | 1.07%   |
| Kingston NVMe SSD Drive 512GB         | 2         | 1.07%   |
| HGST HTS545050A7E380 500GB            | 2         | 1.07%   |
| Fujitsu MHV2100BH PL 100GB            | 2         | 1.07%   |
| WDC WD5000LPZX-60Z10T0 500GB          | 1         | 0.53%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 1         | 0.53%   |
| WDC WD5000LPLX-60ZNTT2 500GB          | 1         | 0.53%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 0.53%   |
| WDC WD5000BPVT-55HXZT3 500GB          | 1         | 0.53%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 0.53%   |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 0.53%   |
| WDC WD2500BPVT-75JJ5T0 250GB          | 1         | 0.53%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.53%   |
| WDC WD10JPVX-80JC3T0 1TB              | 1         | 0.53%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 1         | 0.53%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 0.53%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB  | 1         | 0.53%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB  | 1         | 0.53%   |
| Unknown xD/SD/M.S.                    | 1         | 0.53%   |
| Unknown SS16G  16GB                   | 1         | 0.53%   |
| Unknown 00000  64GB                   | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 41        | 48     | 39.81%  |
| Toshiba | 23        | 25     | 22.33%  |
| WDC     | 21        | 28     | 20.39%  |
| Hitachi | 9         | 9      | 8.74%   |
| HGST    | 6         | 7      | 5.83%   |
| Fujitsu | 3         | 3      | 2.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 6         | 8      | 18.75%  |
| SK hynix            | 6         | 9      | 18.75%  |
| Samsung Electronics | 6         | 8      | 18.75%  |
| SanDisk             | 4         | 4      | 12.5%   |
| A-DATA Technology   | 2         | 3      | 6.25%   |
| TwinMOS             | 1         | 1      | 3.13%   |
| SPCC                | 1         | 1      | 3.13%   |
| SATAFIRM            | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| Patriot             | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| LITEON              | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 100       | 120    | 56.18%  |
| NVMe    | 43        | 51     | 24.16%  |
| SSD     | 31        | 40     | 17.42%  |
| MMC     | 2         | 2      | 1.12%   |
| Unknown | 2         | 2      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 118       | 159    | 71.08%  |
| NVMe | 43        | 51     | 25.9%   |
| SAS  | 3         | 3      | 1.81%   |
| MMC  | 2         | 2      | 1.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 93     | 58.27%  |
| 0.51-1.0   | 46        | 59     | 36.22%  |
| 1.01-2.0   | 7         | 8      | 5.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 46        | 29.68%  |
| 101-250        | 42        | 27.1%   |
| 501-1000       | 25        | 16.13%  |
| 1001-2000      | 13        | 8.39%   |
| 1-20           | 10        | 6.45%   |
| 51-100         | 10        | 6.45%   |
| 21-50          | 5         | 3.23%   |
| 2001-3000      | 2         | 1.29%   |
| More than 3000 | 1         | 0.65%   |
| Unknown        | 1         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 59        | 37.34%  |
| 101-250   | 31        | 19.62%  |
| 21-50     | 26        | 16.46%  |
| 51-100    | 22        | 13.92%  |
| 501-1000  | 7         | 4.43%   |
| 251-500   | 6         | 3.8%    |
| 1001-2000 | 6         | 3.8%    |
| Unknown   | 1         | 0.63%   |

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
| Detected | 71        | 96     | 44.94%  |
| Works    | 67        | 91     | 42.41%  |
| Malfunc  | 19        | 27     | 12.03%  |
| Failed   | 1         | 1      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 125       | 69.83%  |
| AMD                          | 15        | 8.38%   |
| Samsung Electronics          | 7         | 3.91%   |
| SK hynix                     | 6         | 3.35%   |
| SanDisk                      | 5         | 2.79%   |
| Micron Technology            | 5         | 2.79%   |
| Phison Electronics           | 4         | 2.23%   |
| Kingston Technology Company  | 4         | 2.23%   |
| Realtek Semiconductor        | 3         | 1.68%   |
| Union Memory (Shenzhen)      | 1         | 0.56%   |
| Silicon Motion               | 1         | 0.56%   |
| Shenzhen Longsys Electronics | 1         | 0.56%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.56%   |
| ADATA Technology             | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 8.51%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 13        | 6.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 6.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 5.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 5.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 4.79%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 3.72%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 3.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 6         | 3.19%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 2.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 2.66%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 2.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 2.66%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 2.66%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 4         | 2.13%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 4         | 2.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.6%    |
| Realtek RTS5763DL NVMe SSD Controller                                            | 3         | 1.6%    |
| Phison E12 NVMe Controller                                                       | 3         | 1.6%    |
| Intel SSD 660P Series                                                            | 3         | 1.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.6%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 1.06%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.06%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 2         | 1.06%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.06%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                            | 1         | 0.53%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                | 1         | 0.53%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.53%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                 | 1         | 0.53%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.53%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 123       | 66.85%  |
| NVMe | 43        | 23.37%  |
| RAID | 16        | 8.7%    |
| IDE  | 2         | 1.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 127       | 85.81%  |
| AMD    | 21        | 14.19%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 3.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 3.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 2.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 2.7%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 2.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.03%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.03%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 2.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.03%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 2.03%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 1.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.35%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.35%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.35%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 1.35%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.35%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.35%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.35%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.35%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.35%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.35%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.35%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.35%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.35%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.35%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.35%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 1.35%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.35%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.35%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.35%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.68%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.68%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.68%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.68%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 46        | 31.08%  |
| Intel Core i7           | 29        | 19.59%  |
| Intel Core i3           | 24        | 16.22%  |
| Other                   | 12        | 8.11%   |
| AMD Ryzen 5             | 8         | 5.41%   |
| Intel Pentium           | 5         | 3.38%   |
| Intel Core 2 Duo        | 5         | 3.38%   |
| Intel Celeron           | 5         | 3.38%   |
| AMD Ryzen 7             | 3         | 2.03%   |
| AMD Ryzen 3             | 2         | 1.35%   |
| Intel Pentium Dual-Core | 1         | 0.68%   |
| Intel Core m3           | 1         | 0.68%   |
| AMD Sempron             | 1         | 0.68%   |
| AMD E2                  | 1         | 0.68%   |
| AMD E                   | 1         | 0.68%   |
| AMD Athlon              | 1         | 0.68%   |
| AMD A8                  | 1         | 0.68%   |
| AMD A6                  | 1         | 0.68%   |
| AMD A4                  | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 80        | 54.05%  |
| 4      | 51        | 34.46%  |
| 6      | 9         | 6.08%   |
| 8      | 5         | 3.38%   |
| 14     | 1         | 0.68%   |
| 10     | 1         | 0.68%   |
| 1      | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 148       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 122       | 82.43%  |
| 1      | 26        | 17.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 147       | 99.32%  |
| Unknown        | 1         | 0.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 26.97%  |
| 0x40651    | 9         | 5.92%   |
| 0x206a7    | 9         | 5.92%   |
| 0x806ea    | 8         | 5.26%   |
| 0x806ec    | 7         | 4.61%   |
| 0x806c1    | 7         | 4.61%   |
| 0x306a9    | 7         | 4.61%   |
| 0xa0652    | 6         | 3.95%   |
| 0x406e3    | 5         | 3.29%   |
| 0x906ea    | 4         | 2.63%   |
| 0x506e3    | 4         | 2.63%   |
| 0x1067a    | 4         | 2.63%   |
| 0x08108109 | 4         | 2.63%   |
| 0x806e9    | 3         | 1.97%   |
| 0x706e5    | 3         | 1.97%   |
| 0x306d4    | 3         | 1.97%   |
| 0x20655    | 3         | 1.97%   |
| 0x306c3    | 2         | 1.32%   |
| 0x30678    | 2         | 1.32%   |
| 0x08600106 | 2         | 1.32%   |
| 0x08108102 | 2         | 1.32%   |
| 0x06006705 | 2         | 1.32%   |
| 0x06006704 | 2         | 1.32%   |
| 0x906a3    | 1         | 0.66%   |
| 0x706a8    | 1         | 0.66%   |
| 0x6fd      | 1         | 0.66%   |
| 0x506c9    | 1         | 0.66%   |
| 0x406c4    | 1         | 0.66%   |
| 0x40661    | 1         | 0.66%   |
| 0x20652    | 1         | 0.66%   |
| 0x0a50000d | 1         | 0.66%   |
| 0x0a50000c | 1         | 0.66%   |
| 0x0a404101 | 1         | 0.66%   |
| 0x08608103 | 1         | 0.66%   |
| 0x08600104 | 1         | 0.66%   |
| 0x02000032 | 1         | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 20.27%  |
| Haswell          | 17        | 11.49%  |
| SandyBridge      | 14        | 9.46%   |
| Skylake          | 11        | 7.43%   |
| TigerLake        | 9         | 6.08%   |
| Zen+             | 7         | 4.73%   |
| Westmere         | 7         | 4.73%   |
| IvyBridge        | 7         | 4.73%   |
| CometLake        | 7         | 4.73%   |
| Penryn           | 5         | 3.38%   |
| IceLake          | 5         | 3.38%   |
| Broadwell        | 5         | 3.38%   |
| Silvermont       | 4         | 2.7%    |
| Excavator        | 4         | 2.7%    |
| Zen 2            | 3         | 2.03%   |
| Unknown          | 3         | 2.03%   |
| Zen 3            | 2         | 1.35%   |
| Goldmont plus    | 2         | 1.35%   |
| Puma             | 1         | 0.68%   |
| K8 & K10 hybrid  | 1         | 0.68%   |
| Goldmont         | 1         | 0.68%   |
| Core             | 1         | 0.68%   |
| Bobcat           | 1         | 0.68%   |
| Alderlake Hybrid | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 120       | 53.33%  |
| Nvidia | 64        | 28.44%  |
| AMD    | 41        | 18.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 5.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 5.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 9         | 3.96%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 3.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 3.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 3.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.64%   |
| Nvidia GM108M [GeForce MX110]                                                            | 5         | 2.2%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 2.2%    |
| Intel HD Graphics 620                                                                    | 5         | 2.2%    |
| Intel HD Graphics 5500                                                                   | 5         | 2.2%    |
| Nvidia TU117M                                                                            | 4         | 1.76%   |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 1.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.76%   |
| Intel HD Graphics 530                                                                    | 4         | 1.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.76%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.32%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.32%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.32%   |
| AMD Renoir                                                                               | 3         | 1.32%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.32%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.88%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.88%   |
| Intel HD Graphics 630                                                                    | 2         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 55        | 37.16%  |
| 1 x Intel      | 49        | 33.11%  |
| 1 x AMD        | 17        | 11.49%  |
| Intel + AMD    | 15        | 10.14%  |
| AMD + Nvidia   | 7         | 4.73%   |
| 2 x AMD        | 2         | 1.35%   |
| 1 x Nvidia     | 2         | 1.35%   |
| 2 x Intel      | 1         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 114       | 75%     |
| Proprietary | 33        | 21.71%  |
| Unknown     | 5         | 3.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 57.62%  |
| 1.01-2.0   | 24        | 15.89%  |
| 0.01-0.5   | 14        | 9.27%   |
| 3.01-4.0   | 12        | 7.95%   |
| 0.51-1.0   | 11        | 7.28%   |
| 2.01-3.0   | 2         | 1.32%   |
| 7.01-8.0   | 1         | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 34        | 21.25%  |
| AU Optronics            | 31        | 19.38%  |
| BOE                     | 29        | 18.13%  |
| Samsung Electronics     | 24        | 15%     |
| LG Display              | 21        | 13.13%  |
| Chi Mei Optoelectronics | 4         | 2.5%    |
| Hewlett-Packard         | 3         | 1.88%   |
| PANDA                   | 2         | 1.25%   |
| Lenovo                  | 2         | 1.25%   |
| HKC                     | 2         | 1.25%   |
| Acer                    | 2         | 1.25%   |
| Packard Bell            | 1         | 0.63%   |
| LG Philips              | 1         | 0.63%   |
| ITE                     | 1         | 0.63%   |
| Goldstar                | 1         | 0.63%   |
| Dell                    | 1         | 0.63%   |
| BenQ                    | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 4.97%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 2.48%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 4         | 2.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 1.86%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 3         | 1.86%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 1.86%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.86%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch         | 3         | 1.86%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 1.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 1.24%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.24%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 1.24%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.24%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.24%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                 | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch        | 2         | 1.24%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 340x190mm 15.3-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 1         | 0.62%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch      | 1         | 0.62%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch           | 1         | 0.62%   |
| LG Display LP156WH2-TLR1 LGD0221 1366x768 340x190mm 15.3-inch         | 1         | 0.62%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD0738 1920x1080 344x194mm 15.5-inch          | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 67        | 44.67%  |
| 1366x768 (WXGA)  | 66        | 44%     |
| 1600x900 (HD+)   | 7         | 4.67%   |
| 3840x2160 (4K)   | 3         | 2%      |
| 1280x800 (WXGA)  | 3         | 2%      |
| 3840x1100        | 1         | 0.67%   |
| 2560x1440 (QHD)  | 1         | 0.67%   |
| 1440x900 (WXGA+) | 1         | 0.67%   |
| 1280x1024 (SXGA) | 1         | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 108       | 67.5%   |
| 17     | 11        | 6.88%   |
| 14     | 11        | 6.88%   |
| 13     | 8         | 5%      |
| 21     | 6         | 3.75%   |
| 24     | 4         | 2.5%    |
| 27     | 3         | 1.88%   |
| 23     | 2         | 1.25%   |
| 18     | 2         | 1.25%   |
| 12     | 2         | 1.25%   |
| 31     | 1         | 0.63%   |
| 20     | 1         | 0.63%   |
| 11     | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 120       | 75.95%  |
| 351-400     | 13        | 8.23%   |
| 501-600     | 9         | 5.7%    |
| 401-500     | 9         | 5.7%    |
| 201-300     | 6         | 3.8%    |
| 601-700     | 1         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 136       | 95.1%   |
| 16/10 | 4         | 2.8%    |
| 5/4   | 1         | 0.7%    |
| 3/2   | 1         | 0.7%    |
| 3.40  | 1         | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 108       | 67.5%   |
| 81-90          | 15        | 9.38%   |
| 201-250        | 12        | 7.5%    |
| 121-130        | 8         | 5%      |
| 71-80          | 3         | 1.88%   |
| 301-350        | 3         | 1.88%   |
| 141-150        | 3         | 1.88%   |
| 61-70          | 2         | 1.25%   |
| 51-60          | 2         | 1.25%   |
| 131-140        | 2         | 1.25%   |
| 351-500        | 1         | 0.63%   |
| 151-200        | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 66        | 42.31%  |
| 121-160       | 58        | 37.18%  |
| 51-100        | 25        | 16.03%  |
| 161-240       | 4         | 2.56%   |
| More than 240 | 2         | 1.28%   |
| 1-50          | 1         | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 123       | 82%     |
| 2     | 21        | 14%     |
| 0     | 6         | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 106       | 43.09%  |
| Intel                             | 55        | 22.36%  |
| Qualcomm Atheros                  | 40        | 16.26%  |
| Broadcom                          | 17        | 6.91%   |
| Ralink                            | 8         | 3.25%   |
| Broadcom Limited                  | 5         | 2.03%   |
| Ralink Technology                 | 3         | 1.22%   |
| MediaTek                          | 2         | 0.81%   |
| D-Link                            | 2         | 0.81%   |
| TP-Link                           | 1         | 0.41%   |
| Sierra Wireless                   | 1         | 0.41%   |
| OPPO Electronics                  | 1         | 0.41%   |
| Marvell Technology Group          | 1         | 0.41%   |
| ICS Advent                        | 1         | 0.41%   |
| Huawei Technologies               | 1         | 0.41%   |
| Ericsson Business Mobile Networks | 1         | 0.41%   |
| D-Link System                     | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69        | 24.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 10.53%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 4.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 3.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 3.16%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 3.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.46%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 2.46%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 2.46%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 2.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.05%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.05%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.05%   |
| Intel Wireless 8260                                               | 3         | 1.05%   |
| Intel Wireless 7265                                               | 3         | 1.05%   |
| Intel WiFi Link 5100                                              | 3         | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.7%    |
| Intel Wireless 7260                                               | 2         | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.7%    |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.7%    |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.7%    |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.7%    |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 0.7%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.7%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.7%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.7%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 33.76%  |
| Qualcomm Atheros      | 37        | 23.57%  |
| Realtek Semiconductor | 30        | 19.11%  |
| Broadcom              | 14        | 8.92%   |
| Ralink                | 8         | 5.1%    |
| Broadcom Limited      | 5         | 3.18%   |
| Ralink Technology     | 3         | 1.91%   |
| MediaTek              | 2         | 1.27%   |
| D-Link                | 2         | 1.27%   |
| TP-Link               | 1         | 0.64%   |
| Sierra Wireless       | 1         | 0.64%   |
| D-Link System         | 1         | 0.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 7.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 6.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 5.7%    |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 5.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 4.43%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 4.43%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 4.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 3.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 3.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.9%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.9%    |
| Intel Wireless 8265 / 8275                                     | 3         | 1.9%    |
| Intel Wireless 8260                                            | 3         | 1.9%    |
| Intel Wireless 7265                                            | 3         | 1.9%    |
| Intel WiFi Link 5100                                           | 3         | 1.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.27%   |
| Intel Wireless 7260                                            | 2         | 1.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.27%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.27%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 1.27%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 1.27%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.27%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.63%   |
| Sierra Wireless EM7455                                         | 1         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 100       | 79.37%  |
| Intel                    | 13        | 10.32%  |
| Qualcomm Atheros         | 5         | 3.97%   |
| Broadcom                 | 4         | 3.17%   |
| OPPO Electronics         | 1         | 0.79%   |
| Marvell Technology Group | 1         | 0.79%   |
| ICS Advent               | 1         | 0.79%   |
| Huawei Technologies      | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69        | 54.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 23.81%  |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.59%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.59%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.79%   |
| OPPO 8                                                            | 1         | 0.79%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.79%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.79%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.79%   |
| Huawei HUAWEI                                                     | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 146       | 53.87%  |
| Ethernet | 124       | 45.76%  |
| Modem    | 1         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 125       | 82.24%  |
| Ethernet | 27        | 17.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 120       | 80.54%  |
| 1     | 29        | 19.46%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 148       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 35.43%  |
| Qualcomm Atheros Communications | 25        | 19.69%  |
| Realtek Semiconductor           | 23        | 18.11%  |
| Lite-On Technology              | 11        | 8.66%   |
| Broadcom                        | 6         | 4.72%   |
| Ralink                          | 5         | 3.94%   |
| IMC Networks                    | 4         | 3.15%   |
| Foxconn / Hon Hai               | 3         | 2.36%   |
| Toshiba                         | 2         | 1.57%   |
| Realtek                         | 1         | 0.79%   |
| Hewlett-Packard                 | 1         | 0.79%   |
| Dell                            | 1         | 0.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 17        | 13.39%  |
| Intel Bluetooth wireless interface               | 16        | 12.6%   |
| Intel AX201 Bluetooth                            | 15        | 11.81%  |
| Qualcomm Atheros  Bluetooth Device               | 13        | 10.24%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 12        | 9.45%   |
| Ralink RT3290 Bluetooth                          | 5         | 3.94%   |
| Qualcomm Atheros AR3011 Bluetooth                | 5         | 3.94%   |
| Realtek  Bluetooth 4.2 Adapter                   | 4         | 3.15%   |
| Lite-On Bluetooth Device                         | 4         | 3.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 3         | 2.36%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device     | 3         | 2.36%   |
| Broadcom BCM43142A0 Bluetooth 4.0                | 3         | 2.36%   |
| Realtek RTL8723B Bluetooth                       | 2         | 1.57%   |
| Qualcomm Atheros AR9462 Bluetooth                | 2         | 1.57%   |
| Lite-On BCM43142A0                               | 2         | 1.57%   |
| IMC Networks Wireless_Device                     | 2         | 1.57%   |
| IMC Networks Bluetooth Radio                     | 2         | 1.57%   |
| Foxconn / Hon Hai Bluetooth Device               | 2         | 1.57%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR             | 2         | 1.57%   |
| Toshiba Bluetooth USB Host Controller            | 1         | 0.79%   |
| Toshiba BCM43142A0                               | 1         | 0.79%   |
| Realtek Bluetooth Radio                          | 1         | 0.79%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 0.79%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 0.79%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth    | 1         | 0.79%   |
| Dell DW375 Bluetooth Module                      | 1         | 0.79%   |
| Broadcom BCM43142 Bluetooth 4.0                  | 1         | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 127       | 70.56%  |
| AMD                       | 26        | 14.44%  |
| Nvidia                    | 23        | 12.78%  |
| C-Media Electronics       | 2         | 1.11%   |
| Sennheiser Communications | 1         | 0.56%   |
| JMTek                     | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 9.86%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 6.57%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 6.1%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 5.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 5.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 4.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 4.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 3.29%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 3.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.29%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 2.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 2.35%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.88%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.41%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.94%   |
| Nvidia Audio device                                                                               | 2         | 0.94%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.94%   |
| C-Media Electronics USB Audio Device                                                              | 2         | 0.94%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.94%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.94%   |
| Sennheiser Communications Headset [PC 8]                                                          | 1         | 0.47%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 31.4%   |
| SK hynix            | 23        | 19.01%  |
| Micron Technology   | 16        | 13.22%  |
| Team                | 12        | 9.92%   |
| A-DATA Technology   | 8         | 6.61%   |
| Unknown             | 4         | 3.31%   |
| Nanya Technology    | 4         | 3.31%   |
| Crucial             | 4         | 3.31%   |
| Ramaxel Technology  | 3         | 2.48%   |
| Kingston            | 3         | 2.48%   |
| Toshiba             | 2         | 1.65%   |
| Elpida              | 2         | 1.65%   |
| Hikvision           | 1         | 0.83%   |
| ASint Technology    | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s       | 4         | 3.13%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 3         | 2.34%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 3         | 2.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 2.34%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 2.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 3         | 2.34%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 3         | 2.34%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                 | 3         | 2.34%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s          | 2         | 1.56%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s           | 2         | 1.56%   |
| Team RAM TEAMGROUP-SD4-3200 8GB Row Of Chips DDR4 2400MT/s  | 2         | 1.56%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 1.56%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s        | 2         | 1.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.56%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s       | 2         | 1.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 1.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 1.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 1.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 1.56%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 1.56%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 2         | 1.56%   |
| Micron RAM MT40A512M16TB-062E:R 4GB SODIMM DDR4 3200MT/s    | 2         | 1.56%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 2         | 1.56%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.78%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s              | 1         | 0.78%   |
| Unknown RAM Module 4096MB SODIMM DDR3                       | 1         | 0.78%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s               | 1         | 0.78%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s        | 1         | 0.78%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s                 | 1         | 0.78%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s       | 1         | 0.78%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.78%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 0.78%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 1         | 0.78%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s   | 1         | 0.78%   |
| SK hynix RAM HMCG66MEBSA095N 8GB SODIMM DDR5 4800MT/s       | 1         | 0.78%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 1         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s   | 1         | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 56        | 58.95%  |
| DDR3   | 27        | 28.42%  |
| DDR2   | 4         | 4.21%   |
| SDRAM  | 2         | 2.11%   |
| LPDDR4 | 2         | 2.11%   |
| LPDDR3 | 2         | 2.11%   |
| DDR5   | 2         | 2.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 87.76%  |
| Row Of Chips | 11        | 11.22%  |
| Chip         | 1         | 1.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 41        | 35.04%  |
| 4096  | 40        | 34.19%  |
| 16384 | 16        | 13.68%  |
| 2048  | 12        | 10.26%  |
| 32768 | 6         | 5.13%   |
| 1024  | 2         | 1.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 27        | 24.55%  |
| 3200    | 24        | 21.82%  |
| 1600    | 16        | 14.55%  |
| 2400    | 10        | 9.09%   |
| 1334    | 9         | 8.18%   |
| 3266    | 3         | 2.73%   |
| 2133    | 3         | 2.73%   |
| 1867    | 3         | 2.73%   |
| 8400    | 2         | 1.82%   |
| 4800    | 2         | 1.82%   |
| 4199    | 2         | 1.82%   |
| 1333    | 2         | 1.82%   |
| 1066    | 2         | 1.82%   |
| 1067    | 1         | 0.91%   |
| 975     | 1         | 0.91%   |
| 800     | 1         | 0.91%   |
| 667     | 1         | 0.91%   |
| Unknown | 1         | 0.91%   |

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
| Chicony Electronics                    | 33        | 24.26%  |
| IMC Networks                           | 19        | 13.97%  |
| Realtek Semiconductor                  | 16        | 11.76%  |
| Microdia                               | 11        | 8.09%   |
| Suyin                                  | 8         | 5.88%   |
| Sunplus Innovation Technology          | 7         | 5.15%   |
| Bison Electronics                      | 7         | 5.15%   |
| Syntek                                 | 6         | 4.41%   |
| Luxvisions Innotech Limited            | 5         | 3.68%   |
| Lite-On Technology                     | 5         | 3.68%   |
| Acer                                   | 5         | 3.68%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.94%   |
| Quanta                                 | 3         | 2.21%   |
| Silicon Motion                         | 1         | 0.74%   |
| Samsung Electronics                    | 1         | 0.74%   |
| Ricoh                                  | 1         | 0.74%   |
| Lenovo                                 | 1         | 0.74%   |
| Importek                               | 1         | 0.74%   |
| Apple                                  | 1         | 0.74%   |
| Alcor Micro                            | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 6.62%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 8         | 5.88%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 3.68%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 5         | 3.68%   |
| IMC Networks Integrated Camera                              | 5         | 3.68%   |
| Chicony HD WebCam                                           | 4         | 2.94%   |
| Syntek Integrated Camera                                    | 3         | 2.21%   |
| Syntek EasyCamera                                           | 3         | 2.21%   |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 2.21%   |
| Realtek USB Camera                                          | 3         | 2.21%   |
| Realtek Integrated_Webcam_HD                                | 3         | 2.21%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 3         | 2.21%   |
| Lite-On Integrated Camera                                   | 3         | 2.21%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 2.21%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 2.21%   |
| Bison Integrated Camera                                     | 3         | 2.21%   |
| Suyin HP TrueVision HD                                      | 2         | 1.47%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.47%   |
| Realtek EasyCamera                                          | 2         | 1.47%   |
| Quanta HD WebCam                                            | 2         | 1.47%   |
| Microdia Integrated_Webcam_HD                               | 2         | 1.47%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.47%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.47%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.47%   |
| Chicony EasyCamera                                          | 2         | 1.47%   |
| Bison HD Webcam                                             | 2         | 1.47%   |
| Acer Integrated Camera                                      | 2         | 1.47%   |
| Suyin USB 2.0 Camera                                        | 1         | 0.74%   |
| Suyin Laptop_Integrated_Webcam_2HDM                         | 1         | 0.74%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.74%   |
| Suyin HP Integrated Webcam                                  | 1         | 0.74%   |
| Suyin HD WebCam                                             | 1         | 0.74%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.74%   |
| Sunplus HD User Facing                                      | 1         | 0.74%   |
| Sunplus Dell HD Webcam                                      | 1         | 0.74%   |
| Silicon Motion WebCam SC-13HDL11431N                        | 1         | 0.74%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.74%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 0.74%   |
| Realtek Integrated Webcam_HD                                | 1         | 0.74%   |
| Realtek Integrated Webcam                                   | 1         | 0.74%   |

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
| 0     | 108       | 68.35%  |
| 1     | 40        | 25.32%  |
| 3     | 5         | 3.16%   |
| 2     | 4         | 2.53%   |
| 4     | 1         | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 16        | 26.23%  |
| Net/wireless             | 12        | 19.67%  |
| Fingerprint reader       | 10        | 16.39%  |
| Bluetooth                | 7         | 11.48%  |
| Communication controller | 4         | 6.56%   |
| Chipcard                 | 4         | 6.56%   |
| Storage                  | 2         | 3.28%   |
| Camera                   | 2         | 3.28%   |
| Sound                    | 1         | 1.64%   |
| Network                  | 1         | 1.64%   |
| Multimedia controller    | 1         | 1.64%   |
| Card reader              | 1         | 1.64%   |

