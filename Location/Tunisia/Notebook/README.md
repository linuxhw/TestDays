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

Total: 206

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 38        | 25.17%  |
| Ubuntu 18.04       | 12        | 7.95%   |
| Ubuntu 22.04       | 11        | 7.28%   |
| Ubuntu 21.10       | 5         | 3.31%   |
| Zorin 16           | 3         | 1.99%   |
| Zorin 15           | 3         | 1.99%   |
| Pop!_OS 22.04      | 3         | 1.99%   |
| Debian 10          | 3         | 1.99%   |
| Ubuntu 21.04       | 2         | 1.32%   |
| Ubuntu 20.10       | 2         | 1.32%   |
| Ubuntu 16.04       | 2         | 1.32%   |
| Pop!_OS 21.04      | 2         | 1.32%   |
| OpenMandriva 4.2   | 2         | 1.32%   |
| OpenMandriva 23.03 | 2         | 1.32%   |
| Manjaro 21.1.0     | 2         | 1.32%   |
| LMDE 4             | 2         | 1.32%   |
| Linux Mint 21.1    | 2         | 1.32%   |
| Linux Mint 20.3    | 2         | 1.32%   |
| Linux Mint 20.2    | 2         | 1.32%   |
| KDE neon 22.04     | 2         | 1.32%   |
| KDE neon 20.04     | 2         | 1.32%   |
| Fedora 35          | 2         | 1.32%   |
| Fedora 33          | 2         | 1.32%   |
| Arch Rolling       | 2         | 1.32%   |
| Xubuntu 18.04      | 1         | 0.66%   |
| Ubuntu Unity 16.04 | 1         | 0.66%   |
| Ubuntu 19.10       | 1         | 0.66%   |
| Sodalite 35        | 1         | 0.66%   |
| ROSA R8.1          | 1         | 0.66%   |
| ROSA R11           | 1         | 0.66%   |
| ROSA R10           | 1         | 0.66%   |
| ROSA 12.3          | 1         | 0.66%   |
| Pop!_OS 20.10      | 1         | 0.66%   |
| OpenMandriva 4.3   | 1         | 0.66%   |
| Nobara 37          | 1         | 0.66%   |
| MX 21              | 1         | 0.66%   |
| Manjaro 22.1.3     | 1         | 0.66%   |
| Manjaro 22.0.0     | 1         | 0.66%   |
| Manjaro 21.3.6     | 1         | 0.66%   |
| Manjaro 20.2       | 1         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 70        | 48.28%  |
| Linux Mint   | 9         | 6.21%   |
| Zorin        | 6         | 4.14%   |
| Pop!_OS      | 6         | 4.14%   |
| Manjaro      | 6         | 4.14%   |
| Fedora       | 6         | 4.14%   |
| OpenMandriva | 5         | 3.45%   |
| Debian       | 5         | 3.45%   |
| ROSA         | 4         | 2.76%   |
| Endless      | 4         | 2.76%   |
| KDE neon     | 3         | 2.07%   |
| Arch         | 3         | 2.07%   |
| Lubuntu      | 2         | 1.38%   |
| LMDE         | 2         | 1.38%   |
| Elementary   | 2         | 1.38%   |
| Xubuntu      | 1         | 0.69%   |
| Ubuntu Unity | 1         | 0.69%   |
| Sodalite     | 1         | 0.69%   |
| Nobara       | 1         | 0.69%   |
| MX           | 1         | 0.69%   |
| Kubuntu      | 1         | 0.69%   |
| Gentoo       | 1         | 0.69%   |
| Garuda Linux | 1         | 0.69%   |
| EndeavourOS  | 1         | 0.69%   |
| Deepin       | 1         | 0.69%   |
| BlackPanther | 1         | 0.69%   |
| ArcoLinux    | 1         | 0.69%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.13.0-28-generic           | 4         | 2.53%   |
| 5.3.0-46-generic            | 3         | 1.9%    |
| 5.15.0-58-generic           | 3         | 1.9%    |
| 5.15.0-52-generic           | 3         | 1.9%    |
| 5.15.0-46-generic           | 3         | 1.9%    |
| 5.15.0-43-generic           | 3         | 1.9%    |
| 5.11.0-38-generic           | 3         | 1.9%    |
| 6.2.6-desktop-1omv2390      | 2         | 1.27%   |
| 5.8.0-38-generic            | 2         | 1.27%   |
| 5.8.0-14-generic            | 2         | 1.27%   |
| 5.4.0-72-generic            | 2         | 1.27%   |
| 5.4.0-58-generic            | 2         | 1.27%   |
| 5.4.0-52-generic            | 2         | 1.27%   |
| 5.4.0-42-generic            | 2         | 1.27%   |
| 5.3.0-40-generic            | 2         | 1.27%   |
| 5.3.0-28-generic            | 2         | 1.27%   |
| 5.15.0-56-generic           | 2         | 1.27%   |
| 5.15.0-41-generic           | 2         | 1.27%   |
| 5.13.0-44-generic           | 2         | 1.27%   |
| 5.13.0-40-generic           | 2         | 1.27%   |
| 5.11.0-7620-generic         | 2         | 1.27%   |
| 5.11.0-40-generic           | 2         | 1.27%   |
| 5.11.0-27-generic           | 2         | 1.27%   |
| 5.10.14-desktop-1omv4002    | 2         | 1.27%   |
| 5.0.0-25-generic            | 2         | 1.27%   |
| 4.19.0-6-amd64              | 2         | 1.27%   |
| 6.3.6-arch1-1               | 1         | 0.63%   |
| 6.3.6-200.fc38.x86_64       | 1         | 0.63%   |
| 6.3.5-201.fsync.fc37.x86_64 | 1         | 0.63%   |
| 6.2.5-zen1-1-zen            | 1         | 0.63%   |
| 6.2.11-060211-generic       | 1         | 0.63%   |
| 6.2.0-76060200-generic      | 1         | 0.63%   |
| 6.1.29-1-MANJARO            | 1         | 0.63%   |
| 5.9.9-arch1-1               | 1         | 0.63%   |
| 5.8.15-301.fc33.x86_64      | 1         | 0.63%   |
| 5.8.0-50-generic            | 1         | 0.63%   |
| 5.8.0-44-generic            | 1         | 0.63%   |
| 5.8.0-40-generic            | 1         | 0.63%   |
| 5.8.0-33-generic            | 1         | 0.63%   |
| 5.8.0-32-generic            | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 13.64%  |
| 5.15.0  | 21        | 13.64%  |
| 5.13.0  | 13        | 8.44%   |
| 5.11.0  | 12        | 7.79%   |
| 5.8.0   | 10        | 6.49%   |
| 5.3.0   | 8         | 5.19%   |
| 4.15.0  | 8         | 5.19%   |
| 5.19.0  | 6         | 3.9%    |
| 5.0.0   | 6         | 3.9%    |
| 4.19.0  | 4         | 2.6%    |
| 6.3.6   | 2         | 1.3%    |
| 6.2.6   | 2         | 1.3%    |
| 5.17.5  | 2         | 1.3%    |
| 5.10.14 | 2         | 1.3%    |
| 5.10.0  | 2         | 1.3%    |
| 4.18.0  | 2         | 1.3%    |
| 6.3.5   | 1         | 0.65%   |
| 6.2.5   | 1         | 0.65%   |
| 6.2.11  | 1         | 0.65%   |
| 6.2.0   | 1         | 0.65%   |
| 6.1.29  | 1         | 0.65%   |
| 5.9.9   | 1         | 0.65%   |
| 5.8.15  | 1         | 0.65%   |
| 5.6.14  | 1         | 0.65%   |
| 5.4.80  | 1         | 0.65%   |
| 5.4.143 | 1         | 0.65%   |
| 5.4.119 | 1         | 0.65%   |
| 5.3.8   | 1         | 0.65%   |
| 5.19.13 | 1         | 0.65%   |
| 5.18.0  | 1         | 0.65%   |
| 5.16.9  | 1         | 0.65%   |
| 5.16.7  | 1         | 0.65%   |
| 5.16.18 | 1         | 0.65%   |
| 5.16.11 | 1         | 0.65%   |
| 5.15.75 | 1         | 0.65%   |
| 5.15.46 | 1         | 0.65%   |
| 5.15.16 | 1         | 0.65%   |
| 5.14.0  | 1         | 0.65%   |
| 5.13.11 | 1         | 0.65%   |
| 5.12.12 | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 24        | 15.89%  |
| 5.4     | 23        | 15.23%  |
| 5.13    | 14        | 9.27%   |
| 5.11    | 14        | 9.27%   |
| 5.8     | 11        | 7.28%   |
| 5.3     | 9         | 5.96%   |
| 4.15    | 8         | 5.3%    |
| 5.19    | 7         | 4.64%   |
| 5.10    | 7         | 4.64%   |
| 5.0     | 6         | 3.97%   |
| 6.2     | 5         | 3.31%   |
| 4.19    | 4         | 2.65%   |
| 6.3     | 3         | 1.99%   |
| 5.16    | 3         | 1.99%   |
| 5.17    | 2         | 1.32%   |
| 4.9     | 2         | 1.32%   |
| 4.18    | 2         | 1.32%   |
| 6.1     | 1         | 0.66%   |
| 5.9     | 1         | 0.66%   |
| 5.6     | 1         | 0.66%   |
| 5.18    | 1         | 0.66%   |
| 5.14    | 1         | 0.66%   |
| 5.12    | 1         | 0.66%   |
| 3.13    | 1         | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 139       | 98.58%  |
| i686   | 2         | 1.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 88        | 60.27%  |
| KDE5            | 17        | 11.64%  |
| Unknown         | 11        | 7.53%   |
| X-Cinnamon      | 9         | 6.16%   |
| XFCE            | 7         | 4.79%   |
| Pantheon        | 3         | 2.05%   |
| KDE4            | 3         | 2.05%   |
| Unity           | 1         | 0.68%   |
| MATE            | 1         | 0.68%   |
| LXQt            | 1         | 0.68%   |
| LXDE            | 1         | 0.68%   |
| GNOME Flashback | 1         | 0.68%   |
| GNOME Classic   | 1         | 0.68%   |
| DWM             | 1         | 0.68%   |
| Deepin          | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 111       | 76.03%  |
| Wayland | 28        | 19.18%  |
| Unknown | 5         | 3.42%   |
| Tty     | 2         | 1.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 38.89%  |
| GDM     | 43        | 29.86%  |
| GDM3    | 17        | 11.81%  |
| SDDM    | 14        | 9.72%   |
| LightDM | 11        | 7.64%   |
| KDM     | 3         | 2.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 70        | 48.95%  |
| fr_FR   | 44        | 30.77%  |
| Unknown | 15        | 10.49%  |
| en_GB   | 5         | 3.5%    |
| C       | 4         | 2.8%    |
| pt_BR   | 2         | 1.4%    |
| en_IN   | 1         | 0.7%    |
| en_CA   | 1         | 0.7%    |
| ar_TN   | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 81        | 55.86%  |
| BIOS | 64        | 44.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 121       | 85.21%  |
| Overlay | 7         | 4.93%   |
| Btrfs   | 7         | 4.93%   |
| Unknown | 5         | 3.52%   |
| Xfs     | 1         | 0.7%    |
| Tmpfs   | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 64        | 45.07%  |
| GPT     | 54        | 38.03%  |
| MBR     | 24        | 16.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 127       | 88.81%  |
| Yes       | 16        | 11.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 68.57%  |
| Yes       | 44        | 31.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 40        | 28.57%  |
| ASUSTek Computer    | 28        | 20%     |
| Hewlett-Packard     | 25        | 17.86%  |
| Dell                | 19        | 13.57%  |
| Acer                | 12        | 8.57%   |
| Toshiba             | 7         | 5%      |
| MSI                 | 4         | 2.86%   |
| Samsung Electronics | 2         | 1.43%   |
| Sony                | 1         | 0.71%   |
| Packard Bell        | 1         | 0.71%   |
| eMachines           | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP Pavilion g6                           | 5         | 3.57%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 3         | 2.14%   |
| Lenovo IdeaPad 700-15ISK 80RU            | 2         | 1.43%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 2         | 1.43%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 2         | 1.43%   |
| Lenovo IdeaPad 130-15IKB 81H7            | 2         | 1.43%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 1.43%   |
| Dell Inspiron 5570                       | 2         | 1.43%   |
| ASUS X556UV                              | 2         | 1.43%   |
| ASUS X553MA                              | 2         | 1.43%   |
| ASUS X550JX                              | 2         | 1.43%   |
| Acer Aspire E5-571G                      | 2         | 1.43%   |
| Toshiba Satellite Pro L850-B339          | 1         | 0.71%   |
| Toshiba Satellite L550                   | 1         | 0.71%   |
| Toshiba Satellite L500                   | 1         | 0.71%   |
| Toshiba Satellite C650D                  | 1         | 0.71%   |
| Toshiba Satellite C55-C                  | 1         | 0.71%   |
| Toshiba Satellite C50-A489               | 1         | 0.71%   |
| Toshiba Satellite A300                   | 1         | 0.71%   |
| Sony VPCEH36EF                           | 1         | 0.71%   |
| Samsung 530U3BI/530U4BI/530U4BH          | 1         | 0.71%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 0.71%   |
| Packard Bell EasyNote ML65               | 1         | 0.71%   |
| MSI Katana GF66 12UC                     | 1         | 0.71%   |
| MSI GF65 Thin 10UE                       | 1         | 0.71%   |
| MSI GF63 Thin 10SCXR                     | 1         | 0.71%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.71%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 0.71%   |
| Lenovo V310-15ISK 80SY                   | 1         | 0.71%   |
| Lenovo V15-IIL 82C5                      | 1         | 0.71%   |
| Lenovo V15-IGL 82C3                      | 1         | 0.71%   |
| Lenovo ThinkPad X240 20AMA0WRFR          | 1         | 0.71%   |
| Lenovo ThinkPad X201 3680FAG             | 1         | 0.71%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100 | 1         | 0.71%   |
| Lenovo ThinkPad T440s 20AQ005NUS         | 1         | 0.71%   |
| Lenovo ThinkPad E15 20RD001SFE           | 1         | 0.71%   |
| Lenovo ThinkPad E15 20RD001QFE           | 1         | 0.71%   |
| Lenovo ThinkPad E14 20RA000KFE           | 1         | 0.71%   |
| Lenovo ThinkBook 15 G3 ACL 21A4          | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 24        | 17.14%  |
| HP Pavilion           | 12        | 8.57%   |
| Dell Inspiron         | 10        | 7.14%   |
| Acer Aspire           | 9         | 6.43%   |
| Lenovo ThinkPad       | 8         | 5.71%   |
| Toshiba Satellite     | 7         | 5%      |
| Dell Latitude         | 6         | 4.29%   |
| HP Laptop             | 4         | 2.86%   |
| ASUS TUF              | 4         | 2.86%   |
| Dell Vostro           | 3         | 2.14%   |
| MSI GF63              | 2         | 1.43%   |
| HP ProBook            | 2         | 1.43%   |
| HP 250                | 2         | 1.43%   |
| ASUS ZenBook          | 2         | 1.43%   |
| ASUS X556UV           | 2         | 1.43%   |
| ASUS X553MA           | 2         | 1.43%   |
| ASUS X550JX           | 2         | 1.43%   |
| ASUS VivoBook         | 2         | 1.43%   |
| ASUS ROG              | 2         | 1.43%   |
| ASUS ASUS             | 2         | 1.43%   |
| Acer Swift            | 2         | 1.43%   |
| Sony VPCEH36EF        | 1         | 0.71%   |
| Samsung 530U3BI       | 1         | 0.71%   |
| Samsung 300E5EV       | 1         | 0.71%   |
| Packard Bell EasyNote | 1         | 0.71%   |
| MSI Katana            | 1         | 0.71%   |
| MSI GF65              | 1         | 0.71%   |
| Lenovo Y520-15IKBN    | 1         | 0.71%   |
| Lenovo V310-15ISK     | 1         | 0.71%   |
| Lenovo V15-IIL        | 1         | 0.71%   |
| Lenovo V15-IGL        | 1         | 0.71%   |
| Lenovo ThinkBook      | 1         | 0.71%   |
| Lenovo G580           | 1         | 0.71%   |
| Lenovo G50-70         | 1         | 0.71%   |
| HP Notebook           | 1         | 0.71%   |
| HP EliteBook          | 1         | 0.71%   |
| HP Compaq             | 1         | 0.71%   |
| HP 630                | 1         | 0.71%   |
| HP 14                 | 1         | 0.71%   |
| eMachines E725        | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 19        | 13.57%  |
| 2019 | 16        | 11.43%  |
| 2017 | 14        | 10%     |
| 2013 | 12        | 8.57%   |
| 2018 | 11        | 7.86%   |
| 2015 | 10        | 7.14%   |
| 2011 | 10        | 7.14%   |
| 2021 | 9         | 6.43%   |
| 2014 | 9         | 6.43%   |
| 2016 | 7         | 5%      |
| 2012 | 6         | 4.29%   |
| 2010 | 6         | 4.29%   |
| 2009 | 5         | 3.57%   |
| 2008 | 5         | 3.57%   |
| 2022 | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 140       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 129       | 92.14%  |
| Enabled  | 11        | 7.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 140       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 51        | 35.92%  |
| 3.01-4.0   | 32        | 22.54%  |
| 16.01-24.0 | 28        | 19.72%  |
| 8.01-16.0  | 22        | 15.49%  |
| 32.01-64.0 | 5         | 3.52%   |
| 2.01-3.0   | 3         | 2.11%   |
| 1.01-2.0   | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 47        | 30.72%  |
| 1.01-2.0  | 45        | 29.41%  |
| 4.01-8.0  | 28        | 18.3%   |
| 3.01-4.0  | 23        | 15.03%  |
| 8.01-16.0 | 4         | 2.61%   |
| 0.51-1.0  | 4         | 2.61%   |
| 0.01-0.5  | 1         | 0.65%   |
| Unknown   | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 105       | 73.43%  |
| 2      | 38        | 26.57%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 51.06%  |
| Yes       | 69        | 48.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 85%     |
| No        | 21        | 15%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 99.29%  |
| No        | 1         | 0.71%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 84.03%  |
| No        | 23        | 15.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Tunisia | 140       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Tunis              | 83        | 54.25%  |
| Sousse             | 7         | 4.58%   |
| Nabeul             | 6         | 3.92%   |
| Aryanah            | 6         | 3.92%   |
| Bizerte            | 5         | 3.27%   |
| Sfax               | 4         | 2.61%   |
| Centre Urbain Nord | 3         | 1.96%   |
| Rades              | 2         | 1.31%   |
| Monastir           | 2         | 1.31%   |
| Mateur             | 2         | 1.31%   |
| Masakin            | 2         | 1.31%   |
| Manouba            | 2         | 1.31%   |
| Jedeida            | 2         | 1.31%   |
| Houmt Souk         | 2         | 1.31%   |
| Gafsa              | 2         | 1.31%   |
| Ben Arous          | 2         | 1.31%   |
| Zarzis             | 1         | 0.65%   |
| Zaouiat Djedidi    | 1         | 0.65%   |
| Wadi Maliz         | 1         | 0.65%   |
| Tebourba           | 1         | 0.65%   |
| Tataouine          | 1         | 0.65%   |
| Soliman            | 1         | 0.65%   |
| Rafraf             | 1         | 0.65%   |
| Oued Lill          | 1         | 0.65%   |
| Mahdia             | 1         | 0.65%   |
| Le Bardo           | 1         | 0.65%   |
| La Marsa           | 1         | 0.65%   |
| La Goulette        | 1         | 0.65%   |
| Kairouan           | 1         | 0.65%   |
| Jendouba           | 1         | 0.65%   |
| Hergla             | 1         | 0.65%   |
| Gremda             | 1         | 0.65%   |
| El Fahs            | 1         | 0.65%   |
| El Battan          | 1         | 0.65%   |
| Chebba             | 1         | 0.65%   |
| Borj el Amri       | 1         | 0.65%   |
| Belvedere          | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 40        | 47     | 23.12%  |
| WDC                   | 23        | 31     | 13.29%  |
| Toshiba               | 21        | 23     | 12.14%  |
| Samsung Electronics   | 13        | 15     | 7.51%   |
| Team                  | 10        | 12     | 5.78%   |
| SK hynix              | 10        | 12     | 5.78%   |
| Hitachi               | 7         | 7      | 4.05%   |
| SanDisk               | 6         | 6      | 3.47%   |
| Intel                 | 6         | 7      | 3.47%   |
| HGST                  | 6         | 7      | 3.47%   |
| Micron Technology     | 5         | 5      | 2.89%   |
| Kingston              | 4         | 6      | 2.31%   |
| A-DATA Technology     | 4         | 5      | 2.31%   |
| Unknown               | 3         | 3      | 1.73%   |
| Fujitsu               | 3         | 3      | 1.73%   |
| UMIS                  | 1         | 1      | 0.58%   |
| TwinMOS               | 1         | 1      | 0.58%   |
| SPCC                  | 1         | 1      | 0.58%   |
| SATAFIRM              | 1         | 1      | 0.58%   |
| Realtek Semiconductor | 1         | 1      | 0.58%   |
| PNY                   | 1         | 1      | 0.58%   |
| Phison Electronics    | 1         | 1      | 0.58%   |
| Phison                | 1         | 1      | 0.58%   |
| Patriot               | 1         | 1      | 0.58%   |
| OCZ                   | 1         | 1      | 0.58%   |
| LITEON                | 1         | 1      | 0.58%   |
| ADATA Technology      | 1         | 1      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 16        | 9.14%   |
| Seagate ST500LT012-1DG142 500GB       | 8         | 4.57%   |
| Seagate ST2000LM007-1R8174 2TB        | 5         | 2.86%   |
| Toshiba MQ04ABF100 1TB                | 4         | 2.29%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 1.71%   |
| Toshiba MQ01ABD100 1TB                | 3         | 1.71%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 1.71%   |
| WDC WD20SPZX-08UA7 2TB                | 2         | 1.14%   |
| WDC WD10SPZX-08Z10 1TB                | 2         | 1.14%   |
| WDC WD10SPCX-24HWST1 1TB              | 2         | 1.14%   |
| Toshiba MK5076GSX 500GB               | 2         | 1.14%   |
| Toshiba MK3275GSX 320GB               | 2         | 1.14%   |
| Team T253X2512G 512GB SSD             | 2         | 1.14%   |
| SK hynix SC311 SATA 256GB SSD         | 2         | 1.14%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 1.14%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 1.14%   |
| Kingston NVMe SSD Drive 512GB         | 2         | 1.14%   |
| Intel SSDPEKNW512GZL 512GB            | 2         | 1.14%   |
| HGST HTS545050A7E380 500GB            | 2         | 1.14%   |
| Fujitsu MHV2100BH PL 100GB            | 2         | 1.14%   |
| WDC WD5000LPZX-60Z10T0 500GB          | 1         | 0.57%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 1         | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 0.57%   |
| WDC WD5000LPLX-60ZNTT2 500GB          | 1         | 0.57%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 0.57%   |
| WDC WD5000BPVT-55HXZT3 500GB          | 1         | 0.57%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 0.57%   |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 0.57%   |
| WDC WD2500BPVT-75JJ5T0 250GB          | 1         | 0.57%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.57%   |
| WDC WD10JPVX-80JC3T0 1TB              | 1         | 0.57%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 1         | 0.57%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 0.57%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB  | 1         | 0.57%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB  | 1         | 0.57%   |
| Unknown xD/SD/M.S.                    | 1         | 0.57%   |
| Unknown SS16G  16GB                   | 1         | 0.57%   |
| Unknown 00000  64GB                   | 1         | 0.57%   |
| UMIS RPJTJ512MEE1OWX 512GB            | 1         | 0.57%   |
| TwinMOS SSD 512GB                     | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 39        | 46     | 40.63%  |
| Toshiba | 21        | 23     | 21.88%  |
| WDC     | 20        | 27     | 20.83%  |
| Hitachi | 7         | 7      | 7.29%   |
| HGST    | 6         | 7      | 6.25%   |
| Fujitsu | 3         | 3      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 6         | 8      | 18.75%  |
| SK hynix            | 6         | 7      | 18.75%  |
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
| HDD     | 95        | 113    | 56.55%  |
| NVMe    | 38        | 46     | 22.62%  |
| SSD     | 31        | 38     | 18.45%  |
| MMC     | 2         | 2      | 1.19%   |
| Unknown | 2         | 2      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 151    | 73.08%  |
| NVMe | 38        | 46     | 24.36%  |
| SAS  | 2         | 2      | 1.28%   |
| MMC  | 2         | 2      | 1.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 71        | 86     | 58.2%   |
| 0.51-1.0   | 44        | 57     | 36.07%  |
| 1.01-2.0   | 7         | 8      | 5.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 44        | 30.14%  |
| 101-250        | 37        | 25.34%  |
| 501-1000       | 24        | 16.44%  |
| 1001-2000      | 13        | 8.9%    |
| 1-20           | 10        | 6.85%   |
| 51-100         | 10        | 6.85%   |
| 21-50          | 4         | 2.74%   |
| 2001-3000      | 2         | 1.37%   |
| More than 3000 | 1         | 0.68%   |
| Unknown        | 1         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 56        | 37.33%  |
| 101-250   | 29        | 19.33%  |
| 21-50     | 23        | 15.33%  |
| 51-100    | 22        | 14.67%  |
| 501-1000  | 7         | 4.67%   |
| 251-500   | 6         | 4%      |
| 1001-2000 | 6         | 4%      |
| Unknown   | 1         | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 6.25%   |
| WDC WD5000BEVT-22A0RT0 500GB                        | 1         | 1      | 6.25%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 6.25%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 6.25%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 6.25%   |
| Seagate ST9320325AS 320GB                           | 1         | 2      | 6.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 6.25%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 2      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2      | 6.25%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 6.25%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 6.25%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 6.25%   |
| HGST HTS545050A7E380 500GB                          | 1         | 2      | 6.25%   |
| A-DATA Technology SX8100NP 512GB                    | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 4         | 5      | 25%     |
| Seagate           | 4         | 7      | 25%     |
| Hitachi           | 3         | 3      | 18.75%  |
| WDC               | 2         | 3      | 12.5%   |
| Micron Technology | 1         | 1      | 6.25%   |
| HGST              | 1         | 2      | 6.25%   |
| A-DATA Technology | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 5      | 28.57%  |
| Seagate | 4         | 7      | 28.57%  |
| Hitachi | 3         | 3      | 21.43%  |
| WDC     | 2         | 3      | 14.29%  |
| HGST    | 1         | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 20     | 87.5%   |
| NVMe | 1         | 1      | 6.25%   |
| SSD  | 1         | 1      | 6.25%   |

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
| Detected | 69        | 94     | 46.31%  |
| Works    | 63        | 84     | 42.28%  |
| Malfunc  | 16        | 22     | 10.74%  |
| Failed   | 1         | 1      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 118       | 70.24%  |
| AMD                          | 15        | 8.93%   |
| Samsung Electronics          | 7         | 4.17%   |
| SanDisk                      | 5         | 2.98%   |
| SK hynix                     | 4         | 2.38%   |
| Phison Electronics           | 4         | 2.38%   |
| Micron Technology            | 4         | 2.38%   |
| Kingston Technology Company  | 4         | 2.38%   |
| Realtek Semiconductor        | 3         | 1.79%   |
| Union Memory (Shenzhen)      | 1         | 0.6%    |
| Silicon Motion               | 1         | 0.6%    |
| Shenzhen Longsys Electronics | 1         | 0.6%    |
| ADATA Technology             | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 9.04%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 13        | 7.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 6.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 6.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 5.08%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 3.95%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 3.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 6         | 3.39%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 2.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 2.82%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 2.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 2.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.26%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 2.26%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.69%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 3         | 1.69%   |
| Phison E12 NVMe Controller                                                       | 3         | 1.69%   |
| Micron NVMe Storage Controller                                                   | 3         | 1.69%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 1.69%   |
| Intel SSD 660P Series                                                            | 3         | 1.69%   |
| Intel Non-Volatile memory controller                                             | 3         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.69%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.13%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.13%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.56%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.56%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                 | 1         | 0.56%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.56%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 116       | 67.05%  |
| NVMe | 38        | 21.97%  |
| RAID | 17        | 9.83%   |
| IDE  | 2         | 1.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 120       | 85.71%  |
| AMD    | 20        | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 3.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 2.86%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 2.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 2.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 2.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.14%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 2.14%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.14%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 2.14%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.43%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.43%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.43%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 1.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.43%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.43%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.43%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.43%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.43%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.43%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.43%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.43%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.43%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.43%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 1.43%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.43%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.43%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.71%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.71%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.71%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.71%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.71%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz            | 1         | 0.71%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 30.71%  |
| Intel Core i7           | 28        | 20%     |
| Intel Core i3           | 23        | 16.43%  |
| Other                   | 10        | 7.14%   |
| AMD Ryzen 5             | 7         | 5%      |
| Intel Pentium           | 5         | 3.57%   |
| Intel Core 2 Duo        | 5         | 3.57%   |
| Intel Celeron           | 5         | 3.57%   |
| AMD Ryzen 7             | 3         | 2.14%   |
| AMD Ryzen 3             | 2         | 1.43%   |
| Intel Pentium Dual-Core | 1         | 0.71%   |
| Intel Core m3           | 1         | 0.71%   |
| AMD Sempron             | 1         | 0.71%   |
| AMD E2                  | 1         | 0.71%   |
| AMD E                   | 1         | 0.71%   |
| AMD Athlon              | 1         | 0.71%   |
| AMD A8                  | 1         | 0.71%   |
| AMD A6                  | 1         | 0.71%   |
| AMD A4                  | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 77        | 55%     |
| 4      | 48        | 34.29%  |
| 6      | 8         | 5.71%   |
| 8      | 5         | 3.57%   |
| 14     | 1         | 0.71%   |
| 1      | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 140       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 114       | 81.43%  |
| 1      | 26        | 18.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 139       | 99.29%  |
| Unknown        | 1         | 0.71%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 25.17%  |
| 0x40651    | 9         | 6.29%   |
| 0x206a7    | 9         | 6.29%   |
| 0x806ea    | 8         | 5.59%   |
| 0x806ec    | 6         | 4.2%    |
| 0x806c1    | 6         | 4.2%    |
| 0x306a9    | 6         | 4.2%    |
| 0xa0652    | 5         | 3.5%    |
| 0x406e3    | 5         | 3.5%    |
| 0x906ea    | 4         | 2.8%    |
| 0x506e3    | 4         | 2.8%    |
| 0x1067a    | 4         | 2.8%    |
| 0x08108109 | 4         | 2.8%    |
| 0x806e9    | 3         | 2.1%    |
| 0x706e5    | 3         | 2.1%    |
| 0x306d4    | 3         | 2.1%    |
| 0x20655    | 3         | 2.1%    |
| 0x306c3    | 2         | 1.4%    |
| 0x30678    | 2         | 1.4%    |
| 0x08600106 | 2         | 1.4%    |
| 0x08108102 | 2         | 1.4%    |
| 0x06006705 | 2         | 1.4%    |
| 0x06006704 | 2         | 1.4%    |
| 0x906a3    | 1         | 0.7%    |
| 0x706a8    | 1         | 0.7%    |
| 0x6fd      | 1         | 0.7%    |
| 0x506c9    | 1         | 0.7%    |
| 0x406c4    | 1         | 0.7%    |
| 0x40661    | 1         | 0.7%    |
| 0x20652    | 1         | 0.7%    |
| 0x0a50000d | 1         | 0.7%    |
| 0x0a50000c | 1         | 0.7%    |
| 0x0a404101 | 1         | 0.7%    |
| 0x08608103 | 1         | 0.7%    |
| 0x08600104 | 1         | 0.7%    |
| 0x02000032 | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 29        | 20.71%  |
| Haswell         | 17        | 12.14%  |
| SandyBridge     | 12        | 8.57%   |
| Skylake         | 11        | 7.86%   |
| TigerLake       | 8         | 5.71%   |
| Westmere        | 7         | 5%      |
| Zen+            | 6         | 4.29%   |
| IvyBridge       | 6         | 4.29%   |
| CometLake       | 6         | 4.29%   |
| Penryn          | 5         | 3.57%   |
| IceLake         | 5         | 3.57%   |
| Broadwell       | 5         | 3.57%   |
| Silvermont      | 4         | 2.86%   |
| Excavator       | 4         | 2.86%   |
| Zen 2           | 3         | 2.14%   |
| Unknown         | 3         | 2.14%   |
| Zen 3           | 2         | 1.43%   |
| Goldmont plus   | 2         | 1.43%   |
| Puma            | 1         | 0.71%   |
| K8 & K10 hybrid | 1         | 0.71%   |
| Goldmont        | 1         | 0.71%   |
| Core            | 1         | 0.71%   |
| Bobcat          | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 113       | 53.3%   |
| Nvidia | 60        | 28.3%   |
| AMD    | 39        | 18.4%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 6.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 5.14%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 9         | 4.21%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 3.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 2.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.8%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 2.34%   |
| Intel HD Graphics 620                                                                    | 5         | 2.34%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.34%   |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 1.87%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 1.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.87%   |
| Intel HD Graphics 530                                                                    | 4         | 1.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.4%    |
| Nvidia TU117M                                                                            | 3         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.4%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 1.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.4%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.4%    |
| AMD Renoir                                                                               | 3         | 1.4%    |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.4%    |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.93%   |
| Intel HD Graphics 630                                                                    | 2         | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.93%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 51        | 36.43%  |
| 1 x Intel      | 47        | 33.57%  |
| 1 x AMD        | 16        | 11.43%  |
| Intel + AMD    | 14        | 10%     |
| AMD + Nvidia   | 7         | 5%      |
| 2 x AMD        | 2         | 1.43%   |
| 1 x Nvidia     | 2         | 1.43%   |
| 2 x Intel      | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 109       | 75.69%  |
| Proprietary | 30        | 20.83%  |
| Unknown     | 5         | 3.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 56.64%  |
| 1.01-2.0   | 23        | 16.08%  |
| 0.01-0.5   | 14        | 9.79%   |
| 3.01-4.0   | 12        | 8.39%   |
| 0.51-1.0   | 10        | 6.99%   |
| 2.01-3.0   | 2         | 1.4%    |
| 7.01-8.0   | 1         | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 34        | 22.37%  |
| AU Optronics            | 28        | 18.42%  |
| BOE                     | 27        | 17.76%  |
| Samsung Electronics     | 23        | 15.13%  |
| LG Display              | 20        | 13.16%  |
| Chi Mei Optoelectronics | 4         | 2.63%   |
| Hewlett-Packard         | 3         | 1.97%   |
| PANDA                   | 2         | 1.32%   |
| Lenovo                  | 2         | 1.32%   |
| HKC                     | 2         | 1.32%   |
| Packard Bell            | 1         | 0.66%   |
| LG Philips              | 1         | 0.66%   |
| ITE                     | 1         | 0.66%   |
| Goldstar                | 1         | 0.66%   |
| Dell                    | 1         | 0.66%   |
| BenQ                    | 1         | 0.66%   |
| Acer                    | 1         | 0.66%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 5.23%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 2.61%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 3         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 1.96%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.96%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 1.96%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch         | 3         | 1.96%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 2         | 1.31%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 1.31%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 1.31%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 1.31%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.31%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.31%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                 | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch        | 2         | 1.31%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 1         | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.65%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.65%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch      | 1         | 0.65%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch           | 1         | 0.65%   |
| LG Display LP156WH2-TLR1 LGD0221 1366x768 340x190mm 15.3-inch         | 1         | 0.65%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 63        | 44.37%  |
| 1366x768 (WXGA)  | 63        | 44.37%  |
| 1600x900 (HD+)   | 6         | 4.23%   |
| 3840x2160 (4K)   | 3         | 2.11%   |
| 1280x800 (WXGA)  | 3         | 2.11%   |
| 3840x1100        | 1         | 0.7%    |
| 2560x1440 (QHD)  | 1         | 0.7%    |
| 1440x900 (WXGA+) | 1         | 0.7%    |
| 1280x1024 (SXGA) | 1         | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 103       | 67.76%  |
| 17     | 10        | 6.58%   |
| 14     | 10        | 6.58%   |
| 13     | 8         | 5.26%   |
| 21     | 6         | 3.95%   |
| 24     | 4         | 2.63%   |
| 27     | 3         | 1.97%   |
| 23     | 2         | 1.32%   |
| 12     | 2         | 1.32%   |
| 31     | 1         | 0.66%   |
| 20     | 1         | 0.66%   |
| 18     | 1         | 0.66%   |
| 11     | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 115       | 76.67%  |
| 351-400     | 11        | 7.33%   |
| 501-600     | 9         | 6%      |
| 401-500     | 8         | 5.33%   |
| 201-300     | 6         | 4%      |
| 601-700     | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 128       | 94.81%  |
| 16/10 | 4         | 2.96%   |
| 5/4   | 1         | 0.74%   |
| 3/2   | 1         | 0.74%   |
| 3.40  | 1         | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 103       | 67.76%  |
| 81-90          | 14        | 9.21%   |
| 201-250        | 12        | 7.89%   |
| 121-130        | 7         | 4.61%   |
| 71-80          | 3         | 1.97%   |
| 301-350        | 3         | 1.97%   |
| 61-70          | 2         | 1.32%   |
| 51-60          | 2         | 1.32%   |
| 141-150        | 2         | 1.32%   |
| 131-140        | 2         | 1.32%   |
| 351-500        | 1         | 0.66%   |
| 151-200        | 1         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 64        | 43.24%  |
| 121-160       | 54        | 36.49%  |
| 51-100        | 23        | 15.54%  |
| 161-240       | 4         | 2.7%    |
| More than 240 | 2         | 1.35%   |
| 1-50          | 1         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 115       | 80.99%  |
| 2     | 21        | 14.79%  |
| 0     | 6         | 4.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 101       | 43.16%  |
| Intel                             | 52        | 22.22%  |
| Qualcomm Atheros                  | 38        | 16.24%  |
| Broadcom                          | 16        | 6.84%   |
| Ralink                            | 7         | 2.99%   |
| Broadcom Limited                  | 5         | 2.14%   |
| Ralink Technology                 | 3         | 1.28%   |
| MediaTek                          | 2         | 0.85%   |
| D-Link                            | 2         | 0.85%   |
| TP-Link                           | 1         | 0.43%   |
| Sierra Wireless                   | 1         | 0.43%   |
| OPPO Electronics                  | 1         | 0.43%   |
| Marvell Technology Group          | 1         | 0.43%   |
| ICS Advent                        | 1         | 0.43%   |
| Huawei Technologies               | 1         | 0.43%   |
| Ericsson Business Mobile Networks | 1         | 0.43%   |
| D-Link System                     | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 24.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 10.62%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 4.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 3.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 3.3%    |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 3.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.56%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 2.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 2.2%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 2.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.1%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.1%    |
| Intel Wireless 8265 / 8275                                        | 3         | 1.1%    |
| Intel Wireless 8260                                               | 3         | 1.1%    |
| Intel Wireless 7265                                               | 3         | 1.1%    |
| Intel WiFi Link 5100                                              | 3         | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.73%   |
| Intel Wireless 7260                                               | 2         | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.73%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.73%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.73%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.73%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.73%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 0.73%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.73%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.73%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.73%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.73%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.37%   |
| Sierra Wireless EM7455                                            | 1         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 34%     |
| Qualcomm Atheros      | 35        | 23.33%  |
| Realtek Semiconductor | 29        | 19.33%  |
| Broadcom              | 13        | 8.67%   |
| Ralink                | 7         | 4.67%   |
| Broadcom Limited      | 5         | 3.33%   |
| Ralink Technology     | 3         | 2%      |
| MediaTek              | 2         | 1.33%   |
| D-Link                | 2         | 1.33%   |
| TP-Link               | 1         | 0.67%   |
| Sierra Wireless       | 1         | 0.67%   |
| D-Link System         | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 7.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 5.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 5.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 5.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 4.64%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 4.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 3.97%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 3.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.31%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 2.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.99%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.99%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.99%   |
| Intel Wireless 8260                                            | 3         | 1.99%   |
| Intel Wireless 7265                                            | 3         | 1.99%   |
| Intel WiFi Link 5100                                           | 3         | 1.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.32%   |
| Intel Wireless 7260                                            | 2         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.32%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.32%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.32%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 1.32%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 1.32%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.32%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.66%   |
| Sierra Wireless EM7455                                         | 1         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.66%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.66%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.66%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 96        | 79.34%  |
| Intel                    | 12        | 9.92%   |
| Qualcomm Atheros         | 5         | 4.13%   |
| Broadcom                 | 4         | 3.31%   |
| OPPO Electronics         | 1         | 0.83%   |
| Marvell Technology Group | 1         | 0.83%   |
| ICS Advent               | 1         | 0.83%   |
| Huawei Technologies      | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 54.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 23.97%  |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.65%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.65%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.65%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.83%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.83%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.83%   |
| OPPO CPH2411                                                      | 1         | 0.83%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.83%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.83%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.83%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.83%   |
| Huawei HUAWEI                                                     | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 139       | 53.67%  |
| Ethernet | 119       | 45.95%  |
| Modem    | 1         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 119       | 82.64%  |
| Ethernet | 25        | 17.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 116       | 82.27%  |
| 1     | 25        | 17.73%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 140       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 35.54%  |
| Qualcomm Atheros Communications | 23        | 19.01%  |
| Realtek Semiconductor           | 22        | 18.18%  |
| Lite-On Technology              | 11        | 9.09%   |
| Broadcom                        | 6         | 4.96%   |
| Ralink                          | 4         | 3.31%   |
| IMC Networks                    | 4         | 3.31%   |
| Foxconn / Hon Hai               | 3         | 2.48%   |
| Toshiba                         | 2         | 1.65%   |
| Realtek                         | 1         | 0.83%   |
| Hewlett-Packard                 | 1         | 0.83%   |
| Dell                            | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 16        | 13.22%  |
| Intel Bluetooth wireless interface               | 16        | 13.22%  |
| Intel AX201 Bluetooth                            | 13        | 10.74%  |
| Qualcomm Atheros  Bluetooth Device               | 12        | 9.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 12        | 9.92%   |
| Qualcomm Atheros AR3011 Bluetooth                | 5         | 4.13%   |
| Realtek  Bluetooth 4.2 Adapter                   | 4         | 3.31%   |
| Ralink RT3290 Bluetooth                          | 4         | 3.31%   |
| Lite-On Bluetooth Device                         | 4         | 3.31%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device     | 3         | 2.48%   |
| Broadcom BCM43142A0 Bluetooth 4.0                | 3         | 2.48%   |
| Realtek RTL8723B Bluetooth                       | 2         | 1.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 2         | 1.65%   |
| Qualcomm Atheros AR9462 Bluetooth                | 2         | 1.65%   |
| Lite-On BCM43142A0                               | 2         | 1.65%   |
| IMC Networks Wireless_Device                     | 2         | 1.65%   |
| IMC Networks Bluetooth Radio                     | 2         | 1.65%   |
| Foxconn / Hon Hai Bluetooth Device               | 2         | 1.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR             | 2         | 1.65%   |
| Toshiba Bluetooth USB Host Controller            | 1         | 0.83%   |
| Toshiba BCM43142A0                               | 1         | 0.83%   |
| Realtek Bluetooth Radio                          | 1         | 0.83%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 0.83%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth    | 1         | 0.83%   |
| Dell DW375 Bluetooth Module                      | 1         | 0.83%   |
| Broadcom BCM43142 Bluetooth 4.0                  | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 120       | 70.59%  |
| AMD                       | 25        | 14.71%  |
| Nvidia                    | 21        | 12.35%  |
| C-Media Electronics       | 2         | 1.18%   |
| Sennheiser Communications | 1         | 0.59%   |
| JMTek                     | 1         | 0.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 10.4%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 6.44%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 6.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 5.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 4.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 3.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 3.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.47%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.97%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 2.48%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 2.48%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.48%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.98%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.49%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.99%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.99%   |
| C-Media Electronics USB Audio Device                                                              | 2         | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.99%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.99%   |
| Sennheiser Communications Headset [PC 8]                                                          | 1         | 0.5%    |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 33.03%  |
| SK hynix            | 19        | 17.43%  |
| Micron Technology   | 12        | 11.01%  |
| Team                | 11        | 10.09%  |
| A-DATA Technology   | 8         | 7.34%   |
| Unknown             | 4         | 3.67%   |
| Nanya Technology    | 4         | 3.67%   |
| Crucial             | 4         | 3.67%   |
| Kingston            | 3         | 2.75%   |
| Toshiba             | 2         | 1.83%   |
| Ramaxel Technology  | 2         | 1.83%   |
| Elpida              | 2         | 1.83%   |
| Hikvision           | 1         | 0.92%   |
| ASint Technology    | 1         | 0.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s          | 4         | 3.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 3         | 2.59%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 3         | 2.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 3         | 2.59%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                    | 3         | 2.59%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s             | 2         | 1.72%   |
| Toshiba RAM 64T128020EDL2.5C2 1GB SODIMM 1066MT/s              | 2         | 1.72%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s          | 2         | 1.72%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s          | 2         | 1.72%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 1.72%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s       | 2         | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 1.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.72%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 2         | 1.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 1.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1.72%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 2         | 1.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 1.72%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s           | 2         | 1.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.86%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1         | 0.86%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.86%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                  | 1         | 0.86%   |
| Team RAM TEAMGROUP-SD4-3200 16384MB Row Of Chips DDR4 2400MT/s | 1         | 0.86%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s                    | 1         | 0.86%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s          | 1         | 0.86%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.86%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s         | 1         | 0.86%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s         | 1         | 0.86%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 0.86%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 0.86%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 0.86%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.86%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 0.86%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 0.86%   |
| SK hynix RAM HMA81GS6MFR8N-TF 8GB SODIMM DDR4 2133MT/s         | 1         | 0.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 52        | 59.77%  |
| DDR3   | 24        | 27.59%  |
| DDR2   | 4         | 4.6%    |
| SDRAM  | 2         | 2.3%    |
| LPDDR4 | 2         | 2.3%    |
| LPDDR3 | 2         | 2.3%    |
| DDR5   | 1         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 78        | 87.64%  |
| Row Of Chips | 10        | 11.24%  |
| Chip         | 1         | 1.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 37        | 35.24%  |
| 8192  | 34        | 32.38%  |
| 16384 | 15        | 14.29%  |
| 2048  | 11        | 10.48%  |
| 32768 | 6         | 5.71%   |
| 1024  | 2         | 1.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 26        | 25.74%  |
| 3200    | 21        | 20.79%  |
| 1600    | 14        | 13.86%  |
| 2400    | 9         | 8.91%   |
| 1334    | 8         | 7.92%   |
| 3266    | 3         | 2.97%   |
| 2133    | 3         | 2.97%   |
| 1867    | 3         | 2.97%   |
| 8400    | 2         | 1.98%   |
| 4199    | 2         | 1.98%   |
| 1333    | 2         | 1.98%   |
| 1066    | 2         | 1.98%   |
| 4800    | 1         | 0.99%   |
| 1067    | 1         | 0.99%   |
| 975     | 1         | 0.99%   |
| 800     | 1         | 0.99%   |
| 667     | 1         | 0.99%   |
| Unknown | 1         | 0.99%   |

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
| Chicony Electronics                    | 31        | 24.03%  |
| IMC Networks                           | 18        | 13.95%  |
| Realtek Semiconductor                  | 16        | 12.4%   |
| Microdia                               | 10        | 7.75%   |
| Suyin                                  | 8         | 6.2%    |
| Acer                                   | 7         | 5.43%   |
| Sunplus Innovation Technology          | 6         | 4.65%   |
| Syntek                                 | 5         | 3.88%   |
| Lite-On Technology                     | 5         | 3.88%   |
| Bison Electronics                      | 5         | 3.88%   |
| Luxvisions Innotech Limited            | 4         | 3.1%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.1%    |
| Quanta                                 | 3         | 2.33%   |
| Silicon Motion                         | 1         | 0.78%   |
| Samsung Electronics                    | 1         | 0.78%   |
| Ricoh                                  | 1         | 0.78%   |
| Lenovo                                 | 1         | 0.78%   |
| Importek                               | 1         | 0.78%   |
| Apple                                  | 1         | 0.78%   |
| Alcor Micro                            | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 6.98%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 8         | 6.2%    |
| Chicony HD WebCam                                           | 5         | 3.88%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 3.1%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 4         | 3.1%    |
| IMC Networks Integrated Camera                              | 4         | 3.1%    |
| Syntek EasyCamera                                           | 3         | 2.33%   |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 2.33%   |
| Realtek USB Camera                                          | 3         | 2.33%   |
| Realtek Integrated_Webcam_HD                                | 3         | 2.33%   |
| Lite-On Integrated Camera                                   | 3         | 2.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 2.33%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 2.33%   |
| Bison Integrated Camera                                     | 3         | 2.33%   |
| Syntek Integrated Camera                                    | 2         | 1.55%   |
| Suyin HP TrueVision HD                                      | 2         | 1.55%   |
| Realtek EasyCamera                                          | 2         | 1.55%   |
| Quanta VGA WebCam                                           | 2         | 1.55%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 2         | 1.55%   |
| Microdia Integrated_Webcam_HD                               | 2         | 1.55%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.55%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.55%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.55%   |
| Chicony EasyCamera                                          | 2         | 1.55%   |
| Acer Integrated Camera                                      | 2         | 1.55%   |
| Acer HD Webcam                                              | 2         | 1.55%   |
| Suyin USB 2.0 Camera                                        | 1         | 0.78%   |
| Suyin Laptop_Integrated_Webcam_2HDM                         | 1         | 0.78%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.78%   |
| Suyin HP Integrated Webcam                                  | 1         | 0.78%   |
| Suyin HD WebCam                                             | 1         | 0.78%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.78%   |
| Sunplus HD User Facing                                      | 1         | 0.78%   |
| Sunplus Dell HD Webcam                                      | 1         | 0.78%   |
| Silicon Motion WebCam SC-13HDL11431N                        | 1         | 0.78%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 0.78%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 0.78%   |
| Realtek USB2.0 HD UVC WebCam                                | 1         | 0.78%   |
| Realtek USB Webcam                                          | 1         | 0.78%   |
| Realtek Integrated Webcam_HD                                | 1         | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 44.44%  |
| LighTuning Technology      | 2         | 22.22%  |
| Upek                       | 1         | 11.11%  |
| Synaptics                  | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                        | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner                   | 1         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom 5880                                                                | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 103       | 68.67%  |
| 1     | 38        | 25.33%  |
| 3     | 5         | 3.33%   |
| 2     | 3         | 2%      |
| 4     | 1         | 0.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 16        | 28.07%  |
| Net/wireless             | 12        | 21.05%  |
| Fingerprint reader       | 9         | 15.79%  |
| Bluetooth                | 6         | 10.53%  |
| Communication controller | 4         | 7.02%   |
| Chipcard                 | 3         | 5.26%   |
| Storage                  | 2         | 3.51%   |
| Sound                    | 1         | 1.75%   |
| Network                  | 1         | 1.75%   |
| Multimedia controller    | 1         | 1.75%   |
| Card reader              | 1         | 1.75%   |
| Camera                   | 1         | 1.75%   |

