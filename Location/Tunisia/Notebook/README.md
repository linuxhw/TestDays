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

Total: 172

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 33        | 26.19%  |
| Ubuntu 18.04       | 12        | 9.52%   |
| Ubuntu 22.04       | 7         | 5.56%   |
| Ubuntu 21.10       | 5         | 3.97%   |
| Zorin 15           | 3         | 2.38%   |
| Debian 10          | 3         | 2.38%   |
| Zorin 16           | 2         | 1.59%   |
| Ubuntu 21.04       | 2         | 1.59%   |
| Ubuntu 20.10       | 2         | 1.59%   |
| Ubuntu 16.04       | 2         | 1.59%   |
| Pop!_OS 22.04      | 2         | 1.59%   |
| Pop!_OS 21.04      | 2         | 1.59%   |
| OpenMandriva 4.2   | 2         | 1.59%   |
| Manjaro 21.1.0     | 2         | 1.59%   |
| LMDE 4             | 2         | 1.59%   |
| Linux Mint 20.3    | 2         | 1.59%   |
| Linux Mint 20.2    | 2         | 1.59%   |
| KDE neon 20.04     | 2         | 1.59%   |
| Fedora 35          | 2         | 1.59%   |
| Fedora 33          | 2         | 1.59%   |
| Arch Rolling       | 2         | 1.59%   |
| Xubuntu 18.04      | 1         | 0.79%   |
| Ubuntu Unity 16.04 | 1         | 0.79%   |
| Ubuntu 19.10       | 1         | 0.79%   |
| Sodalite 35        | 1         | 0.79%   |
| ROSA R8.1          | 1         | 0.79%   |
| ROSA R11           | 1         | 0.79%   |
| ROSA R10           | 1         | 0.79%   |
| ROSA 12.3          | 1         | 0.79%   |
| Pop!_OS 20.10      | 1         | 0.79%   |
| OpenMandriva 4.3   | 1         | 0.79%   |
| Manjaro 22.0.0     | 1         | 0.79%   |
| Manjaro 21.3.6     | 1         | 0.79%   |
| Manjaro 20.2       | 1         | 0.79%   |
| Lubuntu 20.04      | 1         | 0.79%   |
| Lubuntu 18.04      | 1         | 0.79%   |
| Linux Mint 20.1    | 1         | 0.79%   |
| Linux Mint 20      | 1         | 0.79%   |
| Kubuntu 20.04      | 1         | 0.79%   |
| KDE neon 22.04     | 1         | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 61        | 50.83%  |
| Linux Mint   | 6         | 5%      |
| Zorin        | 5         | 4.17%   |
| Pop!_OS      | 5         | 4.17%   |
| Manjaro      | 5         | 4.17%   |
| Fedora       | 5         | 4.17%   |
| Debian       | 5         | 4.17%   |
| ROSA         | 4         | 3.33%   |
| OpenMandriva | 3         | 2.5%    |
| Endless      | 3         | 2.5%    |
| Arch         | 3         | 2.5%    |
| Lubuntu      | 2         | 1.67%   |
| LMDE         | 2         | 1.67%   |
| KDE neon     | 2         | 1.67%   |
| Xubuntu      | 1         | 0.83%   |
| Ubuntu Unity | 1         | 0.83%   |
| Sodalite     | 1         | 0.83%   |
| Kubuntu      | 1         | 0.83%   |
| Gentoo       | 1         | 0.83%   |
| Elementary   | 1         | 0.83%   |
| Deepin       | 1         | 0.83%   |
| BlackPanther | 1         | 0.83%   |
| ArcoLinux    | 1         | 0.83%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.13.0-28-generic        | 4         | 3.01%   |
| 5.3.0-46-generic         | 3         | 2.26%   |
| 5.15.0-52-generic        | 3         | 2.26%   |
| 5.15.0-46-generic        | 3         | 2.26%   |
| 5.15.0-43-generic        | 3         | 2.26%   |
| 5.11.0-38-generic        | 3         | 2.26%   |
| 5.8.0-38-generic         | 2         | 1.5%    |
| 5.4.0-72-generic         | 2         | 1.5%    |
| 5.4.0-58-generic         | 2         | 1.5%    |
| 5.4.0-52-generic         | 2         | 1.5%    |
| 5.4.0-42-generic         | 2         | 1.5%    |
| 5.3.0-40-generic         | 2         | 1.5%    |
| 5.3.0-28-generic         | 2         | 1.5%    |
| 5.13.0-44-generic        | 2         | 1.5%    |
| 5.13.0-40-generic        | 2         | 1.5%    |
| 5.11.0-7620-generic      | 2         | 1.5%    |
| 5.11.0-40-generic        | 2         | 1.5%    |
| 5.10.14-desktop-1omv4002 | 2         | 1.5%    |
| 5.0.0-25-generic         | 2         | 1.5%    |
| 4.19.0-6-amd64           | 2         | 1.5%    |
| 5.9.9-arch1-1            | 1         | 0.75%   |
| 5.8.15-301.fc33.x86_64   | 1         | 0.75%   |
| 5.8.0-50-generic         | 1         | 0.75%   |
| 5.8.0-44-generic         | 1         | 0.75%   |
| 5.8.0-40-generic         | 1         | 0.75%   |
| 5.8.0-33-generic         | 1         | 0.75%   |
| 5.8.0-32-generic         | 1         | 0.75%   |
| 5.8.0-28-generic         | 1         | 0.75%   |
| 5.8.0-14-generic         | 1         | 0.75%   |
| 5.6.14-desktop-2bP       | 1         | 0.75%   |
| 5.4.80-2-MANJARO         | 1         | 0.75%   |
| 5.4.143-1-pve            | 1         | 0.75%   |
| 5.4.119-1-pve            | 1         | 0.75%   |
| 5.4.0-91-generic         | 1         | 0.75%   |
| 5.4.0-90-generic         | 1         | 0.75%   |
| 5.4.0-84-generic         | 1         | 0.75%   |
| 5.4.0-65-lowlatency      | 1         | 0.75%   |
| 5.4.0-65-generic         | 1         | 0.75%   |
| 5.4.0-56-generic         | 1         | 0.75%   |
| 5.4.0-48-generic         | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 16.28%  |
| 5.13.0  | 13        | 10.08%  |
| 5.15.0  | 12        | 9.3%    |
| 5.11.0  | 11        | 8.53%   |
| 5.8.0   | 9         | 6.98%   |
| 5.3.0   | 8         | 6.2%    |
| 4.15.0  | 8         | 6.2%    |
| 5.0.0   | 6         | 4.65%   |
| 4.19.0  | 4         | 3.1%    |
| 5.19.0  | 3         | 2.33%   |
| 5.17.5  | 2         | 1.55%   |
| 5.10.14 | 2         | 1.55%   |
| 4.18.0  | 2         | 1.55%   |
| 5.9.9   | 1         | 0.78%   |
| 5.8.15  | 1         | 0.78%   |
| 5.6.14  | 1         | 0.78%   |
| 5.4.80  | 1         | 0.78%   |
| 5.4.143 | 1         | 0.78%   |
| 5.4.119 | 1         | 0.78%   |
| 5.3.8   | 1         | 0.78%   |
| 5.19.13 | 1         | 0.78%   |
| 5.18.0  | 1         | 0.78%   |
| 5.16.9  | 1         | 0.78%   |
| 5.16.7  | 1         | 0.78%   |
| 5.16.18 | 1         | 0.78%   |
| 5.16.11 | 1         | 0.78%   |
| 5.15.75 | 1         | 0.78%   |
| 5.15.46 | 1         | 0.78%   |
| 5.15.16 | 1         | 0.78%   |
| 5.13.11 | 1         | 0.78%   |
| 5.12.12 | 1         | 0.78%   |
| 5.11.17 | 1         | 0.78%   |
| 5.11.13 | 1         | 0.78%   |
| 5.10.53 | 1         | 0.78%   |
| 5.10.27 | 1         | 0.78%   |
| 5.10.19 | 1         | 0.78%   |
| 5.10.0  | 1         | 0.78%   |
| 4.9.9   | 1         | 0.78%   |
| 4.9.60  | 1         | 0.78%   |
| 4.9.124 | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 18.25%  |
| 5.15    | 15        | 11.9%   |
| 5.13    | 14        | 11.11%  |
| 5.11    | 13        | 10.32%  |
| 5.8     | 10        | 7.94%   |
| 5.3     | 9         | 7.14%   |
| 4.15    | 8         | 6.35%   |
| 5.10    | 6         | 4.76%   |
| 5.0     | 6         | 4.76%   |
| 5.19    | 4         | 3.17%   |
| 4.19    | 4         | 3.17%   |
| 5.16    | 3         | 2.38%   |
| 5.17    | 2         | 1.59%   |
| 4.9     | 2         | 1.59%   |
| 4.18    | 2         | 1.59%   |
| 5.9     | 1         | 0.79%   |
| 5.6     | 1         | 0.79%   |
| 5.18    | 1         | 0.79%   |
| 5.12    | 1         | 0.79%   |
| 3.13    | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 116       | 98.31%  |
| i686   | 2         | 1.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 74        | 60.66%  |
| KDE5            | 12        | 9.84%   |
| Unknown         | 11        | 9.02%   |
| X-Cinnamon      | 7         | 5.74%   |
| XFCE            | 5         | 4.1%    |
| KDE4            | 3         | 2.46%   |
| Pantheon        | 2         | 1.64%   |
| Unity           | 1         | 0.82%   |
| MATE            | 1         | 0.82%   |
| LXQt            | 1         | 0.82%   |
| LXDE            | 1         | 0.82%   |
| GNOME Flashback | 1         | 0.82%   |
| GNOME Classic   | 1         | 0.82%   |
| DWM             | 1         | 0.82%   |
| Deepin          | 1         | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 93        | 76.23%  |
| Wayland | 22        | 18.03%  |
| Unknown | 5         | 4.1%    |
| Tty     | 2         | 1.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 48        | 40%     |
| GDM     | 40        | 33.33%  |
| GDM3    | 11        | 9.17%   |
| SDDM    | 10        | 8.33%   |
| LightDM | 8         | 6.67%   |
| KDM     | 3         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 59        | 49.17%  |
| fr_FR   | 36        | 30%     |
| Unknown | 15        | 12.5%   |
| en_GB   | 4         | 3.33%   |
| C       | 2         | 1.67%   |
| pt_BR   | 1         | 0.83%   |
| en_IN   | 1         | 0.83%   |
| en_CA   | 1         | 0.83%   |
| ar_TN   | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 69        | 57.02%  |
| BIOS | 52        | 42.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 106       | 89.08%  |
| Unknown | 5         | 4.2%    |
| Overlay | 4         | 3.36%   |
| Btrfs   | 3         | 2.52%   |
| Xfs     | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 47.06%  |
| GPT     | 45        | 37.82%  |
| MBR     | 18        | 15.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 108       | 90.76%  |
| Yes       | 11        | 9.24%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 66.67%  |
| Yes       | 39        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 34        | 29.06%  |
| Hewlett-Packard     | 22        | 18.8%   |
| ASUSTek Computer    | 22        | 18.8%   |
| Dell                | 15        | 12.82%  |
| Acer                | 9         | 7.69%   |
| Toshiba             | 6         | 5.13%   |
| MSI                 | 4         | 3.42%   |
| Samsung Electronics | 2         | 1.71%   |
| Sony                | 1         | 0.85%   |
| Packard Bell        | 1         | 0.85%   |
| eMachines           | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 3         | 2.56%   |
| HP Pavilion g6                           | 3         | 2.56%   |
| Lenovo IdeaPad 130-15IKB 81H7            | 2         | 1.71%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 1.71%   |
| Dell Inspiron 5570                       | 2         | 1.71%   |
| ASUS X556UV                              | 2         | 1.71%   |
| ASUS X550JX                              | 2         | 1.71%   |
| Toshiba Satellite Pro L850-B339          | 1         | 0.85%   |
| Toshiba Satellite L550                   | 1         | 0.85%   |
| Toshiba Satellite L500                   | 1         | 0.85%   |
| Toshiba Satellite C650D                  | 1         | 0.85%   |
| Toshiba Satellite C50-A489               | 1         | 0.85%   |
| Toshiba Satellite A300                   | 1         | 0.85%   |
| Sony VPCEH36EF                           | 1         | 0.85%   |
| Samsung 530U3BI/530U4BI/530U4BH          | 1         | 0.85%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 0.85%   |
| Packard Bell EasyNote ML65               | 1         | 0.85%   |
| MSI Katana GF66 12UC                     | 1         | 0.85%   |
| MSI GF65 Thin 10UE                       | 1         | 0.85%   |
| MSI GF63 Thin 10SCXR                     | 1         | 0.85%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.85%   |
| Lenovo V310-15ISK 80SY                   | 1         | 0.85%   |
| Lenovo V15-IIL 82C5                      | 1         | 0.85%   |
| Lenovo V15-IGL 82C3                      | 1         | 0.85%   |
| Lenovo ThinkPad X240 20AMA0WRFR          | 1         | 0.85%   |
| Lenovo ThinkPad X201 3680FAG             | 1         | 0.85%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100 | 1         | 0.85%   |
| Lenovo ThinkPad T440s 20AQ005NUS         | 1         | 0.85%   |
| Lenovo ThinkPad E15 20RD001SFE           | 1         | 0.85%   |
| Lenovo ThinkPad E15 20RD001QFE           | 1         | 0.85%   |
| Lenovo ThinkPad E14 20RA000KFE           | 1         | 0.85%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 0.85%   |
| Lenovo IdeaPad S145-15AST 81N3           | 1         | 0.85%   |
| Lenovo IdeaPad L3 15IML05 81Y3           | 1         | 0.85%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 0.85%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 0.85%   |
| Lenovo IdeaPad 700-15ISK 80RU            | 1         | 0.85%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 0.85%   |
| Lenovo IdeaPad 330S-14AST 81F8           | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 20        | 17.09%  |
| HP Pavilion           | 9         | 7.69%   |
| Dell Inspiron         | 9         | 7.69%   |
| Lenovo ThinkPad       | 8         | 6.84%   |
| Toshiba Satellite     | 6         | 5.13%   |
| Dell Latitude         | 6         | 5.13%   |
| Acer Aspire           | 6         | 5.13%   |
| HP Laptop             | 4         | 3.42%   |
| ASUS TUF              | 4         | 3.42%   |
| MSI GF63              | 2         | 1.71%   |
| HP ProBook            | 2         | 1.71%   |
| HP 250                | 2         | 1.71%   |
| ASUS X556UV           | 2         | 1.71%   |
| ASUS X550JX           | 2         | 1.71%   |
| ASUS VivoBook         | 2         | 1.71%   |
| ASUS ROG              | 2         | 1.71%   |
| ASUS ASUS             | 2         | 1.71%   |
| Acer Swift            | 2         | 1.71%   |
| Sony VPCEH36EF        | 1         | 0.85%   |
| Samsung 530U3BI       | 1         | 0.85%   |
| Samsung 300E5EV       | 1         | 0.85%   |
| Packard Bell EasyNote | 1         | 0.85%   |
| MSI Katana            | 1         | 0.85%   |
| MSI GF65              | 1         | 0.85%   |
| Lenovo V310-15ISK     | 1         | 0.85%   |
| Lenovo V15-IIL        | 1         | 0.85%   |
| Lenovo V15-IGL        | 1         | 0.85%   |
| Lenovo G580           | 1         | 0.85%   |
| Lenovo G50-70         | 1         | 0.85%   |
| HP Notebook           | 1         | 0.85%   |
| HP EliteBook          | 1         | 0.85%   |
| HP Compaq             | 1         | 0.85%   |
| HP 630                | 1         | 0.85%   |
| HP 14                 | 1         | 0.85%   |
| eMachines E725        | 1         | 0.85%   |
| ASUS ZenBook          | 1         | 0.85%   |
| ASUS X555LD           | 1         | 0.85%   |
| ASUS X553MA           | 1         | 0.85%   |
| ASUS X550VX           | 1         | 0.85%   |
| ASUS X550LC           | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 16        | 13.68%  |
| 2020 | 15        | 12.82%  |
| 2018 | 11        | 9.4%    |
| 2017 | 11        | 9.4%    |
| 2013 | 11        | 9.4%    |
| 2015 | 8         | 6.84%   |
| 2011 | 8         | 6.84%   |
| 2021 | 7         | 5.98%   |
| 2016 | 7         | 5.98%   |
| 2014 | 5         | 4.27%   |
| 2012 | 5         | 4.27%   |
| 2008 | 5         | 4.27%   |
| 2010 | 4         | 3.42%   |
| 2009 | 3         | 2.56%   |
| 2022 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 117       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 108       | 92.31%  |
| Enabled  | 9         | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 117       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 45        | 37.82%  |
| 3.01-4.0   | 23        | 19.33%  |
| 16.01-24.0 | 22        | 18.49%  |
| 8.01-16.0  | 22        | 18.49%  |
| 32.01-64.0 | 4         | 3.36%   |
| 2.01-3.0   | 2         | 1.68%   |
| 1.01-2.0   | 1         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 40        | 31.01%  |
| 1.01-2.0  | 35        | 27.13%  |
| 4.01-8.0  | 26        | 20.16%  |
| 3.01-4.0  | 19        | 14.73%  |
| 0.51-1.0  | 4         | 3.1%    |
| 8.01-16.0 | 3         | 2.33%   |
| 0.01-0.5  | 1         | 0.78%   |
| Unknown   | 1         | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 88        | 73.95%  |
| 2      | 31        | 26.05%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 51.69%  |
| Yes       | 57        | 48.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 85.47%  |
| No        | 17        | 14.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 84.3%   |
| No        | 19        | 15.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Tunisia | 117       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Tunis              | 72        | 56.25%  |
| Sousse             | 6         | 4.69%   |
| Nabeul             | 5         | 3.91%   |
| Bizerte            | 5         | 3.91%   |
| Aryanah            | 5         | 3.91%   |
| Centre Urbain Nord | 3         | 2.34%   |
| Rades              | 2         | 1.56%   |
| Monastir           | 2         | 1.56%   |
| Masakin            | 2         | 1.56%   |
| Jedeida            | 2         | 1.56%   |
| Zarzis             | 1         | 0.78%   |
| Zaouiat Djedidi    | 1         | 0.78%   |
| Wadi Maliz         | 1         | 0.78%   |
| Tebourba           | 1         | 0.78%   |
| Tataouine          | 1         | 0.78%   |
| Sfax               | 1         | 0.78%   |
| Rafraf             | 1         | 0.78%   |
| Oued Lill          | 1         | 0.78%   |
| Mateur             | 1         | 0.78%   |
| Manouba            | 1         | 0.78%   |
| Mahdia             | 1         | 0.78%   |
| Le Bardo           | 1         | 0.78%   |
| La Marsa           | 1         | 0.78%   |
| La Goulette        | 1         | 0.78%   |
| Jendouba           | 1         | 0.78%   |
| Houmt Souk         | 1         | 0.78%   |
| Hergla             | 1         | 0.78%   |
| Gremda             | 1         | 0.78%   |
| Gafsa              | 1         | 0.78%   |
| El Fahs            | 1         | 0.78%   |
| El Battan          | 1         | 0.78%   |
| Borj el Amri       | 1         | 0.78%   |
| Ben Arous          | 1         | 0.78%   |
| Belvedere          | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 30        | 35     | 20.98%  |
| WDC                   | 21        | 29     | 14.69%  |
| Toshiba               | 17        | 19     | 11.89%  |
| SK hynix              | 10        | 11     | 6.99%   |
| Samsung Electronics   | 10        | 12     | 6.99%   |
| Team                  | 9         | 11     | 6.29%   |
| SanDisk               | 6         | 6      | 4.2%    |
| Micron Technology     | 5         | 5      | 3.5%    |
| Hitachi               | 5         | 5      | 3.5%    |
| HGST                  | 5         | 6      | 3.5%    |
| Kingston              | 4         | 6      | 2.8%    |
| Intel                 | 4         | 4      | 2.8%    |
| Unknown               | 3         | 3      | 2.1%    |
| Fujitsu               | 3         | 3      | 2.1%    |
| A-DATA Technology     | 3         | 4      | 2.1%    |
| UMIS                  | 1         | 1      | 0.7%    |
| TwinMOS               | 1         | 1      | 0.7%    |
| SPCC                  | 1         | 1      | 0.7%    |
| Realtek Semiconductor | 1         | 1      | 0.7%    |
| PNY                   | 1         | 1      | 0.7%    |
| Phison                | 1         | 1      | 0.7%    |
| Patriot               | 1         | 1      | 0.7%    |
| OCZ                   | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 11        | 7.59%   |
| Seagate ST500LT012-1DG142 500GB       | 7         | 4.83%   |
| Seagate ST2000LM007-1R8174 2TB        | 4         | 2.76%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 2.07%   |
| Toshiba MQ04ABF100 1TB                | 3         | 2.07%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 2.07%   |
| WDC WD20SPZX-08UA7 2TB                | 2         | 1.38%   |
| WDC WD10SPZX-08Z10 1TB                | 2         | 1.38%   |
| WDC WD10SPCX-24HWST1 1TB              | 2         | 1.38%   |
| Toshiba MQ01ABD100 1TB                | 2         | 1.38%   |
| Toshiba MK5076GSX 500GB               | 2         | 1.38%   |
| Toshiba MK3275GSX 320GB               | 2         | 1.38%   |
| Team T253X2512G 512GB SSD             | 2         | 1.38%   |
| SK hynix SC311 SATA 256GB SSD         | 2         | 1.38%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 1.38%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 1.38%   |
| Kingston NVMe SSD Drive 512GB         | 2         | 1.38%   |
| HGST HTS545050A7E380 500GB            | 2         | 1.38%   |
| Fujitsu MHV2100BH PL 100GB            | 2         | 1.38%   |
| WDC WD5000LPZX-60Z10T0 500GB          | 1         | 0.69%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 1         | 0.69%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 0.69%   |
| WDC WD5000LPLX-60ZNTT2 500GB          | 1         | 0.69%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 0.69%   |
| WDC WD5000BPVT-55HXZT3 500GB          | 1         | 0.69%   |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 0.69%   |
| WDC WD2500BPVT-75JJ5T0 250GB          | 1         | 0.69%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.69%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 1         | 0.69%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 0.69%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB  | 1         | 0.69%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB  | 1         | 0.69%   |
| Unknown xD/SD/M.S.                    | 1         | 0.69%   |
| Unknown SS16G  16GB                   | 1         | 0.69%   |
| Unknown 00000  64GB                   | 1         | 0.69%   |
| UMIS RPJTJ512MEE1OWX 512GB            | 1         | 0.69%   |
| TwinMOS SSD 512GB                     | 1         | 0.69%   |
| Toshiba MQ01ACF050 500GB              | 1         | 0.69%   |
| Toshiba MQ01ABD050 500GB              | 1         | 0.69%   |
| Toshiba MQ01ABD032 320GB              | 1         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 30        | 35     | 38.46%  |
| WDC     | 18        | 25     | 23.08%  |
| Toshiba | 17        | 19     | 21.79%  |
| Hitachi | 5         | 5      | 6.41%   |
| HGST    | 5         | 6      | 6.41%   |
| Fujitsu | 3         | 3      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK hynix            | 6         | 6      | 21.43%  |
| Team                | 5         | 7      | 17.86%  |
| Samsung Electronics | 5         | 7      | 17.86%  |
| SanDisk             | 4         | 4      | 14.29%  |
| A-DATA Technology   | 2         | 3      | 7.14%   |
| TwinMOS             | 1         | 1      | 3.57%   |
| SPCC                | 1         | 1      | 3.57%   |
| PNY                 | 1         | 1      | 3.57%   |
| Patriot             | 1         | 1      | 3.57%   |
| OCZ                 | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 77        | 93     | 55.4%   |
| NVMe    | 31        | 38     | 22.3%   |
| SSD     | 28        | 33     | 20.14%  |
| MMC     | 2         | 2      | 1.44%   |
| Unknown | 1         | 1      | 0.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 94        | 126    | 73.44%  |
| NVMe | 31        | 38     | 24.22%  |
| MMC  | 2         | 2      | 1.56%   |
| SAS  | 1         | 1      | 0.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 73     | 60.4%   |
| 0.51-1.0   | 34        | 46     | 33.66%  |
| 1.01-2.0   | 6         | 7      | 5.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 38        | 31.15%  |
| 101-250    | 35        | 28.69%  |
| 501-1000   | 18        | 14.75%  |
| 1001-2000  | 11        | 9.02%   |
| 51-100     | 8         | 6.56%   |
| 1-20       | 7         | 5.74%   |
| 21-50      | 3         | 2.46%   |
| 2001-3000  | 1         | 0.82%   |
| Unknown    | 1         | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 46        | 36.51%  |
| 101-250   | 25        | 19.84%  |
| 21-50     | 20        | 15.87%  |
| 51-100    | 19        | 15.08%  |
| 251-500   | 6         | 4.76%   |
| 501-1000  | 6         | 4.76%   |
| 1001-2000 | 3         | 2.38%   |
| Unknown   | 1         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 8.33%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 8.33%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 8.33%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 8.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 8.33%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 2      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 8.33%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 8.33%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 8.33%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 8.33%   |
| HGST HTS545050A7E380 500GB                          | 1         | 2      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 4         | 5      | 33.33%  |
| Seagate           | 3         | 4      | 25%     |
| Hitachi           | 2         | 2      | 16.67%  |
| WDC               | 1         | 2      | 8.33%   |
| Micron Technology | 1         | 1      | 8.33%   |
| HGST              | 1         | 2      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 5      | 36.36%  |
| Seagate | 3         | 4      | 27.27%  |
| Hitachi | 2         | 2      | 18.18%  |
| WDC     | 1         | 2      | 9.09%   |
| HGST    | 1         | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 15     | 91.67%  |
| SSD  | 1         | 1      | 8.33%   |

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
| Detected | 56        | 76     | 45.16%  |
| Works    | 55        | 74     | 44.35%  |
| Malfunc  | 12        | 16     | 9.68%   |
| Failed   | 1         | 1      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 98        | 70%     |
| AMD                          | 12        | 8.57%   |
| SanDisk                      | 5         | 3.57%   |
| Samsung Electronics          | 5         | 3.57%   |
| SK hynix                     | 4         | 2.86%   |
| Micron Technology            | 4         | 2.86%   |
| Kingston Technology Company  | 4         | 2.86%   |
| Phison Electronics           | 3         | 2.14%   |
| Realtek Semiconductor        | 2         | 1.43%   |
| Union Memory (Shenzhen)      | 1         | 0.71%   |
| Silicon Motion               | 1         | 0.71%   |
| Shenzhen Longsys Electronics | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 10.27%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 7.53%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 6.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 6.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 4.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 4.11%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 3.42%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 2.74%   |
| Micron Non-Volatile memory controller                                            | 4         | 2.74%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 2.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.74%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 2.74%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 2.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 2.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 2.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.05%   |
| SK hynix BC511                                                                   | 2         | 1.37%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 2         | 1.37%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.37%   |
| Intel SSD 660P Series                                                            | 2         | 1.37%   |
| Intel Non-Volatile memory controller                                             | 2         | 1.37%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.37%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.68%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.68%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.68%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                 | 1         | 0.68%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.68%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.68%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 94        | 66.2%   |
| NVMe | 31        | 21.83%  |
| RAID | 15        | 10.56%  |
| IDE  | 2         | 1.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 100       | 85.47%  |
| AMD    | 17        | 14.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 4.27%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 3.42%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 2.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 2.56%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 2.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 2.56%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 2.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.71%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.71%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 1.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.71%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.71%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.71%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.71%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.71%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.71%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.71%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.71%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.71%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 1.71%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.71%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.85%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.85%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.85%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.85%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.85%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.85%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz            | 1         | 0.85%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.85%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.85%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.85%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.85%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 34.19%  |
| Intel Core i7           | 24        | 20.51%  |
| Intel Core i3           | 18        | 15.38%  |
| AMD Ryzen 5             | 7         | 5.98%   |
| Other                   | 6         | 5.13%   |
| Intel Pentium           | 4         | 3.42%   |
| Intel Core 2 Duo        | 4         | 3.42%   |
| Intel Celeron           | 3         | 2.56%   |
| AMD Ryzen 7             | 2         | 1.71%   |
| Intel Pentium Dual-Core | 1         | 0.85%   |
| Intel Core m3           | 1         | 0.85%   |
| AMD Sempron             | 1         | 0.85%   |
| AMD Ryzen 3             | 1         | 0.85%   |
| AMD E2                  | 1         | 0.85%   |
| AMD E                   | 1         | 0.85%   |
| AMD A8                  | 1         | 0.85%   |
| AMD A6                  | 1         | 0.85%   |
| AMD A4                  | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 63        | 53.85%  |
| 4      | 40        | 34.19%  |
| 6      | 8         | 6.84%   |
| 8      | 4         | 3.42%   |
| 14     | 1         | 0.85%   |
| 1      | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 117       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 97        | 82.91%  |
| 1      | 20        | 17.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 116       | 99.15%  |
| Unknown        | 1         | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 20.17%  |
| 0x806ea    | 8         | 6.72%   |
| 0x40651    | 8         | 6.72%   |
| 0x206a7    | 7         | 5.88%   |
| 0x806ec    | 6         | 5.04%   |
| 0x306a9    | 6         | 5.04%   |
| 0xa0652    | 5         | 4.2%    |
| 0x406e3    | 5         | 4.2%    |
| 0x906ea    | 4         | 3.36%   |
| 0x806e9    | 3         | 2.52%   |
| 0x806c1    | 3         | 2.52%   |
| 0x706e5    | 3         | 2.52%   |
| 0x506e3    | 3         | 2.52%   |
| 0x306d4    | 3         | 2.52%   |
| 0x20655    | 3         | 2.52%   |
| 0x1067a    | 3         | 2.52%   |
| 0x08108109 | 3         | 2.52%   |
| 0x306c3    | 2         | 1.68%   |
| 0x08600106 | 2         | 1.68%   |
| 0x08108102 | 2         | 1.68%   |
| 0x06006705 | 2         | 1.68%   |
| 0x06006704 | 2         | 1.68%   |
| 0x906a3    | 1         | 0.84%   |
| 0x706a8    | 1         | 0.84%   |
| 0x6fd      | 1         | 0.84%   |
| 0x506c9    | 1         | 0.84%   |
| 0x406c4    | 1         | 0.84%   |
| 0x40661    | 1         | 0.84%   |
| 0x30678    | 1         | 0.84%   |
| 0x20652    | 1         | 0.84%   |
| 0x0a50000c | 1         | 0.84%   |
| 0x0a404101 | 1         | 0.84%   |
| 0x08600104 | 1         | 0.84%   |
| 0x02000032 | 1         | 0.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 27        | 23.08%  |
| Haswell         | 13        | 11.11%  |
| Skylake         | 9         | 7.69%   |
| SandyBridge     | 9         | 7.69%   |
| Westmere        | 6         | 5.13%   |
| IvyBridge       | 6         | 5.13%   |
| CometLake       | 6         | 5.13%   |
| Zen+            | 5         | 4.27%   |
| IceLake         | 5         | 4.27%   |
| TigerLake       | 4         | 3.42%   |
| Penryn          | 4         | 3.42%   |
| Excavator       | 4         | 3.42%   |
| Broadwell       | 4         | 3.42%   |
| Zen 2           | 3         | 2.56%   |
| Silvermont      | 3         | 2.56%   |
| Unknown         | 2         | 1.71%   |
| Zen 3           | 1         | 0.85%   |
| Puma            | 1         | 0.85%   |
| K8 & K10 hybrid | 1         | 0.85%   |
| Goldmont plus   | 1         | 0.85%   |
| Goldmont        | 1         | 0.85%   |
| Core            | 1         | 0.85%   |
| Bobcat          | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 94        | 53.71%  |
| Nvidia | 47        | 26.86%  |
| AMD    | 34        | 19.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 5.65%   |
| Intel UHD Graphics 620                                                                   | 8         | 4.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 4.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 3.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 3.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 3.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.39%   |
| Intel HD Graphics 620                                                                    | 5         | 2.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.82%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 2.26%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 2.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.26%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 2.26%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.26%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.26%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.69%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.69%   |
| Intel HD Graphics 530                                                                    | 3         | 1.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.69%   |
| AMD Renoir                                                                               | 3         | 1.69%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.69%   |
| Nvidia TU117M                                                                            | 2         | 1.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.13%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 1.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.13%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.13%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.56%   |
| Nvidia GT218M [GeForce G 105M]                                                           | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.56%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 35.9%   |
| Intel + Nvidia | 39        | 33.33%  |
| Intel + AMD    | 13        | 11.11%  |
| 1 x AMD        | 13        | 11.11%  |
| AMD + Nvidia   | 6         | 5.13%   |
| 2 x AMD        | 2         | 1.71%   |
| 1 x Nvidia     | 2         | 1.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 91        | 75.21%  |
| Proprietary | 25        | 20.66%  |
| Unknown     | 5         | 4.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 55.83%  |
| 1.01-2.0   | 18        | 15%     |
| 0.01-0.5   | 13        | 10.83%  |
| 3.01-4.0   | 11        | 9.17%   |
| 0.51-1.0   | 8         | 6.67%   |
| 2.01-3.0   | 2         | 1.67%   |
| 7.01-8.0   | 1         | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 29        | 22.31%  |
| AU Optronics            | 26        | 20%     |
| BOE                     | 24        | 18.46%  |
| Samsung Electronics     | 20        | 15.38%  |
| LG Display              | 14        | 10.77%  |
| Hewlett-Packard         | 3         | 2.31%   |
| Chi Mei Optoelectronics | 3         | 2.31%   |
| PANDA                   | 2         | 1.54%   |
| Lenovo                  | 2         | 1.54%   |
| Packard Bell            | 1         | 0.77%   |
| LG Philips              | 1         | 0.77%   |
| ITE                     | 1         | 0.77%   |
| Goldstar                | 1         | 0.77%   |
| Dell                    | 1         | 0.77%   |
| BenQ                    | 1         | 0.77%   |
| Acer                    | 1         | 0.77%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 4.58%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 3.05%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 2.29%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.29%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 2.29%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 1.53%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 2         | 1.53%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 2         | 1.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.53%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.53%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 1.53%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 1.53%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 1.53%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.53%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch        | 2         | 1.53%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch  | 1         | 0.76%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.76%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.76%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch      | 1         | 0.76%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch           | 1         | 0.76%   |
| LG Display LP156WH2-TLR1 LGD0221 1366x768 340x190mm 15.3-inch         | 1         | 0.76%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.76%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.76%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch           | 1         | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 54        | 44.63%  |
| 1366x768 (WXGA)  | 52        | 42.98%  |
| 1600x900 (HD+)   | 5         | 4.13%   |
| 3840x2160 (4K)   | 3         | 2.48%   |
| 1280x800 (WXGA)  | 3         | 2.48%   |
| 3840x1100        | 1         | 0.83%   |
| 2560x1440 (QHD)  | 1         | 0.83%   |
| 1440x900 (WXGA+) | 1         | 0.83%   |
| 1280x1024 (SXGA) | 1         | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 87        | 66.92%  |
| 17     | 8         | 6.15%   |
| 14     | 8         | 6.15%   |
| 13     | 8         | 6.15%   |
| 21     | 6         | 4.62%   |
| 24     | 4         | 3.08%   |
| 27     | 2         | 1.54%   |
| 23     | 2         | 1.54%   |
| 12     | 2         | 1.54%   |
| 31     | 1         | 0.77%   |
| 20     | 1         | 0.77%   |
| 11     | 1         | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 98        | 76.56%  |
| 501-600     | 8         | 6.25%   |
| 351-400     | 8         | 6.25%   |
| 401-500     | 7         | 5.47%   |
| 201-300     | 6         | 4.69%   |
| 601-700     | 1         | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 107       | 93.86%  |
| 16/10 | 4         | 3.51%   |
| 5/4   | 1         | 0.88%   |
| 3/2   | 1         | 0.88%   |
| 3.40  | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 66.92%  |
| 81-90          | 12        | 9.23%   |
| 201-250        | 12        | 9.23%   |
| 121-130        | 5         | 3.85%   |
| 71-80          | 3         | 2.31%   |
| 61-70          | 2         | 1.54%   |
| 51-60          | 2         | 1.54%   |
| 301-350        | 2         | 1.54%   |
| 131-140        | 2         | 1.54%   |
| 351-500        | 1         | 0.77%   |
| 151-200        | 1         | 0.77%   |
| 141-150        | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 54        | 42.52%  |
| 121-160       | 47        | 37.01%  |
| 51-100        | 19        | 14.96%  |
| 161-240       | 4         | 3.15%   |
| More than 240 | 2         | 1.57%   |
| 1-50          | 1         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 95        | 79.83%  |
| 2     | 19        | 15.97%  |
| 0     | 5         | 4.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 84        | 42.86%  |
| Intel                             | 44        | 22.45%  |
| Qualcomm Atheros                  | 31        | 15.82%  |
| Broadcom                          | 13        | 6.63%   |
| Ralink                            | 5         | 2.55%   |
| Broadcom Limited                  | 5         | 2.55%   |
| Ralink Technology                 | 2         | 1.02%   |
| MediaTek                          | 2         | 1.02%   |
| D-Link                            | 2         | 1.02%   |
| TP-Link                           | 1         | 0.51%   |
| Sierra Wireless                   | 1         | 0.51%   |
| OPPO Electronics                  | 1         | 0.51%   |
| Marvell Technology Group          | 1         | 0.51%   |
| ICS Advent                        | 1         | 0.51%   |
| Huawei Technologies               | 1         | 0.51%   |
| Ericsson Business Mobile Networks | 1         | 0.51%   |
| D-Link System                     | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 23.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 10.39%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 4.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 3.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.03%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.6%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.3%    |
| Intel Wireless 8265 / 8275                                        | 3         | 1.3%    |
| Intel Wireless 8260                                               | 3         | 1.3%    |
| Intel WiFi Link 5100                                              | 3         | 1.3%    |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.3%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.87%   |
| Intel Wireless 7265                                               | 2         | 0.87%   |
| Intel Wireless 7260                                               | 2         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.87%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.87%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.87%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.87%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 0.87%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.87%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.87%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.43%   |
| Sierra Wireless EM7455                                            | 1         | 0.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 33.86%  |
| Qualcomm Atheros      | 28        | 22.05%  |
| Realtek Semiconductor | 27        | 21.26%  |
| Broadcom              | 10        | 7.87%   |
| Ralink                | 5         | 3.94%   |
| Broadcom Limited      | 5         | 3.94%   |
| Ralink Technology     | 2         | 1.57%   |
| MediaTek              | 2         | 1.57%   |
| D-Link                | 2         | 1.57%   |
| TP-Link               | 1         | 0.79%   |
| Sierra Wireless       | 1         | 0.79%   |
| D-Link System         | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 8.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 7.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 5.47%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 5.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 4.69%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 4.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 3.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 2.34%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.34%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.34%   |
| Intel Wireless 8260                                            | 3         | 2.34%   |
| Intel WiFi Link 5100                                           | 3         | 2.34%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.34%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.56%   |
| Intel Wireless 7265                                            | 2         | 1.56%   |
| Intel Wireless 7260                                            | 2         | 1.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.56%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.56%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 1.56%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 1.56%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.78%   |
| Sierra Wireless EM7455                                         | 1         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.78%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 0.78%   |
| Realtek 802.11n                                                | 1         | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 79        | 77.45%  |
| Intel                    | 12        | 11.76%  |
| Qualcomm Atheros         | 4         | 3.92%   |
| Broadcom                 | 3         | 2.94%   |
| OPPO Electronics         | 1         | 0.98%   |
| Marvell Technology Group | 1         | 0.98%   |
| ICS Advent               | 1         | 0.98%   |
| Huawei Technologies      | 1         | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 52.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 23.53%  |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.96%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.96%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.98%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.98%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.98%   |
| OPPO SDM665-IDP _SN:18689828                                      | 1         | 0.98%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.98%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.98%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.98%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.98%   |
| Huawei HUAWEI                                                     | 1         | 0.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 53.67%  |
| Ethernet | 100       | 45.87%  |
| Modem    | 1         | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 81.82%  |
| Ethernet | 22        | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 98        | 83.05%  |
| 1     | 20        | 16.95%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 117       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 34.31%  |
| Realtek Semiconductor           | 20        | 19.61%  |
| Qualcomm Atheros Communications | 19        | 18.63%  |
| Lite-On Technology              | 8         | 7.84%   |
| Broadcom                        | 6         | 5.88%   |
| IMC Networks                    | 4         | 3.92%   |
| Ralink                          | 3         | 2.94%   |
| Foxconn / Hon Hai               | 3         | 2.94%   |
| Toshiba                         | 1         | 0.98%   |
| Realtek                         | 1         | 0.98%   |
| Hewlett-Packard                 | 1         | 0.98%   |
| Dell                            | 1         | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 14        | 13.73%  |
| Intel Bluetooth wireless interface               | 13        | 12.75%  |
| Intel AX201 Bluetooth                            | 12        | 11.76%  |
| Qualcomm Atheros  Bluetooth Device               | 11        | 10.78%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 8         | 7.84%   |
| Realtek  Bluetooth 4.2 Adapter                   | 4         | 3.92%   |
| Qualcomm Atheros AR3011 Bluetooth                | 4         | 3.92%   |
| Ralink RT3290 Bluetooth                          | 3         | 2.94%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device     | 3         | 2.94%   |
| Broadcom BCM43142A0 Bluetooth 4.0                | 3         | 2.94%   |
| Realtek RTL8723B Bluetooth                       | 2         | 1.96%   |
| Lite-On Bluetooth Device                         | 2         | 1.96%   |
| IMC Networks Wireless_Device                     | 2         | 1.96%   |
| IMC Networks Bluetooth Radio                     | 2         | 1.96%   |
| Foxconn / Hon Hai Bluetooth Device               | 2         | 1.96%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR             | 2         | 1.96%   |
| Toshiba Bluetooth USB Host Controller            | 1         | 0.98%   |
| Realtek Bluetooth Radio                          | 1         | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 1         | 0.98%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 0.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 0.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 0.98%   |
| Lite-On BCM43142A0                               | 1         | 0.98%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 0.98%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 0.98%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 0.98%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 0.98%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth    | 1         | 0.98%   |
| Dell DW375 Bluetooth Module                      | 1         | 0.98%   |
| Broadcom BCM43142 Bluetooth 4.0                  | 1         | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 100       | 68.97%  |
| AMD                       | 21        | 14.48%  |
| Nvidia                    | 20        | 13.79%  |
| C-Media Electronics       | 2         | 1.38%   |
| Sennheiser Communications | 1         | 0.69%   |
| JMTek                     | 1         | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 11.76%  |
| Intel 8 Series HD Audio Controller                                                                | 10        | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 5.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 5.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 4.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 3.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 3.53%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 3.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 2.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 2.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 2.35%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.35%   |
| AMD High Definition Audio Controller                                                              | 4         | 2.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.76%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.18%   |
| C-Media Electronics USB Audio Device                                                              | 2         | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.18%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.18%   |
| Sennheiser Communications Headset [PC 8]                                                          | 1         | 0.59%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.59%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.59%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.59%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.59%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.59%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.59%   |
| Nvidia Audio device                                                                               | 1         | 0.59%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.59%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 32.98%  |
| SK hynix            | 17        | 18.09%  |
| Micron Technology   | 10        | 10.64%  |
| Team                | 8         | 8.51%   |
| A-DATA Technology   | 7         | 7.45%   |
| Crucial             | 4         | 4.26%   |
| Unknown             | 3         | 3.19%   |
| Nanya Technology    | 3         | 3.19%   |
| Kingston            | 3         | 3.19%   |
| Toshiba             | 2         | 2.13%   |
| Ramaxel Technology  | 2         | 2.13%   |
| Elpida              | 2         | 2.13%   |
| Hikvision           | 1         | 1.06%   |
| ASint Technology    | 1         | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 2.97%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 2.97%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                      | 3         | 2.97%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 2         | 1.98%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 2         | 1.98%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 2         | 1.98%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 2         | 1.98%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 2         | 1.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.98%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 2         | 1.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.98%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.98%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.98%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.98%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 1.98%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.99%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.99%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.99%   |
| Team RAM TEAMGROUP-SD3-1600 4GB SODIMM DDR3 1600MT/s             | 1         | 0.99%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 1         | 0.99%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 1         | 0.99%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.99%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.99%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.99%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.99%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.99%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.99%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.99%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.99%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.99%   |
| SK hynix RAM HMA81GS6MFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 1         | 0.99%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.99%   |
| SK hynix RAM H9CCNNN8PTBLBR-NUD 2GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.99%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 0.99%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 0.99%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 0.99%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 61.33%  |
| DDR3   | 18        | 24%     |
| DDR2   | 4         | 5.33%   |
| SDRAM  | 2         | 2.67%   |
| LPDDR4 | 2         | 2.67%   |
| LPDDR3 | 2         | 2.67%   |
| DDR5   | 1         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 89.47%  |
| Row Of Chips | 7         | 9.21%   |
| Chip         | 1         | 1.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 35        | 39.33%  |
| 8192  | 30        | 33.71%  |
| 16384 | 10        | 11.24%  |
| 2048  | 9         | 10.11%  |
| 32768 | 4         | 4.49%   |
| 1024  | 1         | 1.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 24        | 27.91%  |
| 3200    | 17        | 19.77%  |
| 1600    | 12        | 13.95%  |
| 2400    | 7         | 8.14%   |
| 1334    | 7         | 8.14%   |
| 2133    | 3         | 3.49%   |
| 1867    | 3         | 3.49%   |
| 8400    | 2         | 2.33%   |
| 4199    | 2         | 2.33%   |
| 3266    | 2         | 2.33%   |
| 1066    | 2         | 2.33%   |
| 4800    | 1         | 1.16%   |
| 975     | 1         | 1.16%   |
| 800     | 1         | 1.16%   |
| 667     | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

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
| Chicony Electronics                    | 24        | 22.64%  |
| Realtek Semiconductor                  | 16        | 15.09%  |
| IMC Networks                           | 14        | 13.21%  |
| Microdia                               | 8         | 7.55%   |
| Acer                                   | 7         | 6.6%    |
| Suyin                                  | 6         | 5.66%   |
| Syntek                                 | 5         | 4.72%   |
| Sunplus Innovation Technology          | 5         | 4.72%   |
| Lite-On Technology                     | 5         | 4.72%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.77%   |
| Quanta                                 | 3         | 2.83%   |
| Luxvisions Innotech Limited            | 3         | 2.83%   |
| Silicon Motion                         | 1         | 0.94%   |
| Ricoh                                  | 1         | 0.94%   |
| Lenovo                                 | 1         | 0.94%   |
| Importek                               | 1         | 0.94%   |
| Apple                                  | 1         | 0.94%   |
| Alcor Micro                            | 1         | 0.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 7         | 6.54%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 5.61%   |
| IMC Networks Integrated Camera                              | 4         | 3.74%   |
| Syntek EasyCamera                                           | 3         | 2.8%    |
| Sunplus Integrated_Webcam_HD                                | 3         | 2.8%    |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 2.8%    |
| Realtek USB Camera                                          | 3         | 2.8%    |
| Realtek Integrated_Webcam_HD                                | 3         | 2.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 3         | 2.8%    |
| Lite-On Integrated Camera                                   | 3         | 2.8%    |
| Chicony HD WebCam                                           | 3         | 2.8%    |
| Acer Integrated Camera                                      | 3         | 2.8%    |
| Syntek Integrated Camera                                    | 2         | 1.87%   |
| Suyin HP TrueVision HD                                      | 2         | 1.87%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.87%   |
| Realtek Lenovo easy camera                                  | 2         | 1.87%   |
| Quanta HD WebCam                                            | 2         | 1.87%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 2         | 1.87%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.87%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.87%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.87%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.87%   |
| Chicony EasyCamera                                          | 2         | 1.87%   |
| Acer HD Webcam                                              | 2         | 1.87%   |
| Suyin USB 2.0 Camera                                        | 1         | 0.93%   |
| Suyin HP Integrated Webcam                                  | 1         | 0.93%   |
| Suyin HD WebCam                                             | 1         | 0.93%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.93%   |
| Sunplus HD User Facing                                      | 1         | 0.93%   |
| Sunplus Dell HD Webcam                                      | 1         | 0.93%   |
| Silicon Motion WebCam SC-13HDL11431N                        | 1         | 0.93%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 0.93%   |
| Realtek Integrated Webcam_HD                                | 1         | 0.93%   |
| Realtek Integrated Webcam                                   | 1         | 0.93%   |
| Realtek HP Webcam                                           | 1         | 0.93%   |
| Quanta HP Webcam                                            | 1         | 0.93%   |
| Microdia Webcam SC-10HDD12636P                              | 1         | 0.93%   |
| Microdia Integrated_Webcam_HD                               | 1         | 0.93%   |
| Microdia HP Webcam                                          | 1         | 0.93%   |
| Microdia HP Integrated Webcam                               | 1         | 0.93%   |

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
| 0     | 86        | 67.72%  |
| 1     | 33        | 25.98%  |
| 3     | 5         | 3.94%   |
| 2     | 2         | 1.57%   |
| 4     | 1         | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 14        | 27.45%  |
| Net/wireless             | 11        | 21.57%  |
| Fingerprint reader       | 9         | 17.65%  |
| Bluetooth                | 5         | 9.8%    |
| Communication controller | 3         | 5.88%   |
| Chipcard                 | 3         | 5.88%   |
| Storage                  | 2         | 3.92%   |
| Sound                    | 1         | 1.96%   |
| Network                  | 1         | 1.96%   |
| Card reader              | 1         | 1.96%   |
| Camera                   | 1         | 1.96%   |

