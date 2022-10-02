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

Total: 200

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite C650D             | Notebook    | [0fce536c7d](https://linux-hardware.org/?probe=0fce536c7d) | Sep 28, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [31a7427ce3](https://linux-hardware.org/?probe=31a7427ce3) | Sep 25, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 36        | 24.83%  |
| Ubuntu 18.04       | 17        | 11.72%  |
| Ubuntu 21.10       | 6         | 4.14%   |
| OpenMandriva 4.2   | 5         | 3.45%   |
| Ubuntu 22.04       | 4         | 2.76%   |
| Zorin 15           | 3         | 2.07%   |
| Ubuntu 19.10       | 3         | 2.07%   |
| Ubuntu 16.04       | 3         | 2.07%   |
| Pop!_OS 22.04      | 3         | 2.07%   |
| OpenMandriva 4.3   | 3         | 2.07%   |
| KDE neon 20.04     | 3         | 2.07%   |
| Debian 10          | 3         | 2.07%   |
| Ubuntu 21.04       | 2         | 1.38%   |
| Ubuntu 20.10       | 2         | 1.38%   |
| ROSA R10           | 2         | 1.38%   |
| Pop!_OS 21.04      | 2         | 1.38%   |
| Manjaro 21.1.0     | 2         | 1.38%   |
| LMDE 4             | 2         | 1.38%   |
| Linux Mint 20.3    | 2         | 1.38%   |
| Linux Mint 20.2    | 2         | 1.38%   |
| Linux Mint 20      | 2         | 1.38%   |
| Gentoo 2.7         | 2         | 1.38%   |
| Fedora 35          | 2         | 1.38%   |
| Fedora 33          | 2         | 1.38%   |
| Debian 11          | 2         | 1.38%   |
| ArcoLinux Rolling  | 2         | 1.38%   |
| Arch               | 2         | 1.38%   |
| Zorin 16           | 1         | 0.69%   |
| Xubuntu 18.04      | 1         | 0.69%   |
| Ubuntu Unity 16.04 | 1         | 0.69%   |
| Ubuntu 19.04       | 1         | 0.69%   |
| Sodalite 35        | 1         | 0.69%   |
| ROSA R8.1          | 1         | 0.69%   |
| ROSA R11           | 1         | 0.69%   |
| Pop!_OS 20.10      | 1         | 0.69%   |
| Manjaro 22.0.0     | 1         | 0.69%   |
| Manjaro 21.3.6     | 1         | 0.69%   |
| Manjaro 20.2       | 1         | 0.69%   |
| Lubuntu 20.04      | 1         | 0.69%   |
| Lubuntu 18.04      | 1         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 70        | 50.36%  |
| OpenMandriva | 8         | 5.76%   |
| Linux Mint   | 7         | 5.04%   |
| Pop!_OS      | 6         | 4.32%   |
| Debian       | 6         | 4.32%   |
| Manjaro      | 5         | 3.6%    |
| Zorin        | 4         | 2.88%   |
| ROSA         | 4         | 2.88%   |
| Fedora       | 4         | 2.88%   |
| KDE neon     | 3         | 2.16%   |
| Endless      | 3         | 2.16%   |
| Arch         | 3         | 2.16%   |
| Lubuntu      | 2         | 1.44%   |
| LMDE         | 2         | 1.44%   |
| Gentoo       | 2         | 1.44%   |
| ArcoLinux    | 2         | 1.44%   |
| Xubuntu      | 1         | 0.72%   |
| Ubuntu Unity | 1         | 0.72%   |
| Sodalite     | 1         | 0.72%   |
| Kubuntu      | 1         | 0.72%   |
| Kali         | 1         | 0.72%   |
| Elementary   | 1         | 0.72%   |
| Deepin       | 1         | 0.72%   |
| BlackPanther | 1         | 0.72%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 5         | 3.25%   |
| 5.15.0-46-generic               | 4         | 2.6%    |
| 5.13.0-28-generic               | 4         | 2.6%    |
| 5.3.0-46-generic                | 3         | 1.95%   |
| 5.3.0-40-generic                | 3         | 1.95%   |
| 5.16.7-desktop-1omv4003         | 3         | 1.95%   |
| 5.11.0-38-generic               | 3         | 1.95%   |
| 5.8.0-38-generic                | 2         | 1.3%    |
| 5.4.0-72-generic                | 2         | 1.3%    |
| 5.4.0-58-generic                | 2         | 1.3%    |
| 5.4.0-52-generic                | 2         | 1.3%    |
| 5.4.0-42-generic                | 2         | 1.3%    |
| 5.4.0-26-generic                | 2         | 1.3%    |
| 5.3.0-28-generic                | 2         | 1.3%    |
| 5.15.0-43-generic               | 2         | 1.3%    |
| 5.13.0-44-generic               | 2         | 1.3%    |
| 5.13.0-40-generic               | 2         | 1.3%    |
| 5.11.0-7620-generic             | 2         | 1.3%    |
| 5.11.0-40-generic               | 2         | 1.3%    |
| 5.11.0-27-generic               | 2         | 1.3%    |
| 5.10.27-gentoo                  | 2         | 1.3%    |
| 5.10.0-12-amd64                 | 2         | 1.3%    |
| 5.0.0-25-generic                | 2         | 1.3%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 1.3%    |
| 4.19.0-6-amd64                  | 2         | 1.3%    |
| 4.15.0-91-generic               | 2         | 1.3%    |
| 5.9.9-arch1-1                   | 1         | 0.65%   |
| 5.9.1-arch1-1                   | 1         | 0.65%   |
| 5.8.15-301.fc33.x86_64          | 1         | 0.65%   |
| 5.8.0-50-generic                | 1         | 0.65%   |
| 5.8.0-44-generic                | 1         | 0.65%   |
| 5.8.0-40-generic                | 1         | 0.65%   |
| 5.8.0-33-generic                | 1         | 0.65%   |
| 5.8.0-32-generic                | 1         | 0.65%   |
| 5.8.0-28-generic                | 1         | 0.65%   |
| 5.8.0-14-generic                | 1         | 0.65%   |
| 5.6.14-desktop-2bP              | 1         | 0.65%   |
| 5.4.80-2-MANJARO                | 1         | 0.65%   |
| 5.4.143-1-pve                   | 1         | 0.65%   |
| 5.4.119-1-pve                   | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 26        | 17.22%  |
| 5.13.0  | 14        | 9.27%   |
| 5.11.0  | 12        | 7.95%   |
| 5.3.0   | 11        | 7.28%   |
| 5.15.0  | 10        | 6.62%   |
| 4.15.0  | 10        | 6.62%   |
| 5.8.0   | 9         | 5.96%   |
| 5.0.0   | 7         | 4.64%   |
| 5.10.14 | 5         | 3.31%   |
| 4.19.0  | 4         | 2.65%   |
| 5.19.0  | 3         | 1.99%   |
| 5.16.7  | 3         | 1.99%   |
| 4.18.0  | 3         | 1.99%   |
| 5.18.0  | 2         | 1.32%   |
| 5.10.27 | 2         | 1.32%   |
| 5.10.0  | 2         | 1.32%   |
| 4.9.60  | 2         | 1.32%   |
| 5.9.9   | 1         | 0.66%   |
| 5.9.1   | 1         | 0.66%   |
| 5.8.15  | 1         | 0.66%   |
| 5.6.14  | 1         | 0.66%   |
| 5.4.80  | 1         | 0.66%   |
| 5.4.143 | 1         | 0.66%   |
| 5.4.119 | 1         | 0.66%   |
| 5.3.8   | 1         | 0.66%   |
| 5.17.5  | 1         | 0.66%   |
| 5.17.15 | 1         | 0.66%   |
| 5.16.9  | 1         | 0.66%   |
| 5.16.18 | 1         | 0.66%   |
| 5.16.11 | 1         | 0.66%   |
| 5.15.5  | 1         | 0.66%   |
| 5.15.16 | 1         | 0.66%   |
| 5.15.11 | 1         | 0.66%   |
| 5.13.11 | 1         | 0.66%   |
| 5.12.12 | 1         | 0.66%   |
| 5.11.17 | 1         | 0.66%   |
| 5.11.13 | 1         | 0.66%   |
| 5.10.53 | 1         | 0.66%   |
| 5.10.19 | 1         | 0.66%   |
| 4.9.9   | 1         | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 18.92%  |
| 5.13    | 15        | 10.14%  |
| 5.11    | 14        | 9.46%   |
| 5.15    | 13        | 8.78%   |
| 5.3     | 12        | 8.11%   |
| 5.10    | 11        | 7.43%   |
| 5.8     | 10        | 6.76%   |
| 4.15    | 10        | 6.76%   |
| 5.0     | 7         | 4.73%   |
| 5.16    | 5         | 3.38%   |
| 4.19    | 4         | 2.7%    |
| 5.19    | 3         | 2.03%   |
| 4.9     | 3         | 2.03%   |
| 4.18    | 3         | 2.03%   |
| 5.9     | 2         | 1.35%   |
| 5.18    | 2         | 1.35%   |
| 5.17    | 2         | 1.35%   |
| 5.6     | 1         | 0.68%   |
| 5.12    | 1         | 0.68%   |
| 4.4     | 1         | 0.68%   |
| 3.13    | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 134       | 97.81%  |
| i686   | 3         | 2.19%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 79        | 55.24%  |
| KDE5            | 17        | 11.89%  |
| Unknown         | 16        | 11.19%  |
| X-Cinnamon      | 8         | 5.59%   |
| XFCE            | 6         | 4.2%    |
| KDE4            | 4         | 2.8%    |
| Pantheon        | 2         | 1.4%    |
| GNOME Flashback | 2         | 1.4%    |
| Unity           | 1         | 0.7%    |
| MATE            | 1         | 0.7%    |
| LXQt            | 1         | 0.7%    |
| LXDE            | 1         | 0.7%    |
| i3              | 1         | 0.7%    |
| GNOME Classic   | 1         | 0.7%    |
| DWM             | 1         | 0.7%    |
| Deepin          | 1         | 0.7%    |
| Cinnamon        | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 110       | 78.57%  |
| Wayland | 22        | 15.71%  |
| Unknown | 5         | 3.57%   |
| Tty     | 3         | 2.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 57        | 41.01%  |
| GDM     | 41        | 29.5%   |
| SDDM    | 17        | 12.23%  |
| GDM3    | 11        | 7.91%   |
| LightDM | 9         | 6.47%   |
| KDM     | 4         | 2.88%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 64        | 45.71%  |
| fr_FR   | 44        | 31.43%  |
| Unknown | 19        | 13.57%  |
| en_GB   | 4         | 2.86%   |
| C       | 2         | 1.43%   |
| ar_TN   | 2         | 1.43%   |
| pt_BR   | 1         | 0.71%   |
| en_CA   | 1         | 0.71%   |
| en_AU   | 1         | 0.71%   |
| en_AG   | 1         | 0.71%   |
| de_DE   | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 79        | 56.43%  |
| BIOS | 61        | 43.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 120       | 86.96%  |
| Overlay | 9         | 6.52%   |
| Unknown | 6         | 4.35%   |
| Btrfs   | 2         | 1.45%   |
| Xfs     | 1         | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 68        | 48.92%  |
| GPT     | 52        | 37.41%  |
| MBR     | 19        | 13.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 123       | 88.49%  |
| Yes       | 16        | 11.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 63.24%  |
| Yes       | 50        | 36.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 34        | 25%     |
| ASUSTek Computer    | 24        | 17.65%  |
| Hewlett-Packard     | 23        | 16.91%  |
| Dell                | 18        | 13.24%  |
| MSI                 | 9         | 6.62%   |
| Acer                | 9         | 6.62%   |
| Toshiba             | 6         | 4.41%   |
| Pegatron            | 3         | 2.21%   |
| Samsung Electronics | 2         | 1.47%   |
| Foxconn             | 2         | 1.47%   |
| Sony                | 1         | 0.74%   |
| Packard Bell        | 1         | 0.74%   |
| Intel               | 1         | 0.74%   |
| Gigabyte Technology | 1         | 0.74%   |
| eMachines           | 1         | 0.74%   |
| Unknown             | 1         | 0.74%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 3         | 2.21%   |
| Pegatron VS342AA-AB6 m9801af             | 2         | 1.47%   |
| Lenovo IdeaPad 130-15IKB 81H7            | 2         | 1.47%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 1.47%   |
| HP Pavilion g6                           | 2         | 1.47%   |
| Foxconn Pro 3400 Series MT               | 2         | 1.47%   |
| Dell Inspiron 5570                       | 2         | 1.47%   |
| ASUS X556UV                              | 2         | 1.47%   |
| ASUS X550JX                              | 2         | 1.47%   |
| Unknown                                  | 2         | 1.47%   |
| Toshiba Satellite Pro L850-B339          | 1         | 0.74%   |
| Toshiba Satellite L550                   | 1         | 0.74%   |
| Toshiba Satellite L500                   | 1         | 0.74%   |
| Toshiba Satellite C650D                  | 1         | 0.74%   |
| Toshiba Satellite C50-A489               | 1         | 0.74%   |
| Toshiba Satellite A300                   | 1         | 0.74%   |
| Sony VPCEH36EF                           | 1         | 0.74%   |
| Samsung 530U3BI/530U4BI/530U4BH          | 1         | 0.74%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 0.74%   |
| Pegatron Pro 3010 Microtower PC          | 1         | 0.74%   |
| Packard Bell EasyNote ML65               | 1         | 0.74%   |
| MSI MS-7C95                              | 1         | 0.74%   |
| MSI MS-7C52                              | 1         | 0.74%   |
| MSI MS-7A15                              | 1         | 0.74%   |
| MSI MS-7817                              | 1         | 0.74%   |
| MSI MS-7502                              | 1         | 0.74%   |
| MSI Katana GF66 12UC                     | 1         | 0.74%   |
| MSI GF65 Thin 10UE                       | 1         | 0.74%   |
| MSI GF63 Thin 10SCXR                     | 1         | 0.74%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.74%   |
| Lenovo V310-15ISK 80SY                   | 1         | 0.74%   |
| Lenovo V15-IIL 82C5                      | 1         | 0.74%   |
| Lenovo ThinkStation P330 30C6S33L00      | 1         | 0.74%   |
| Lenovo ThinkPad X240 20AMA0WRFR          | 1         | 0.74%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 0.74%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100 | 1         | 0.74%   |
| Lenovo ThinkPad T440s 20AQ005NUS         | 1         | 0.74%   |
| Lenovo ThinkPad E15 20RD001SFE           | 1         | 0.74%   |
| Lenovo ThinkPad E15 20RD001QFE           | 1         | 0.74%   |
| Lenovo ThinkPad E14 20RA000KFE           | 1         | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 18        | 13.24%  |
| Dell Inspiron         | 9         | 6.62%   |
| HP Pavilion           | 8         | 5.88%   |
| Lenovo ThinkPad       | 7         | 5.15%   |
| Toshiba Satellite     | 6         | 4.41%   |
| Dell Latitude         | 6         | 4.41%   |
| Acer Aspire           | 6         | 4.41%   |
| HP Laptop             | 4         | 2.94%   |
| ASUS TUF              | 4         | 2.94%   |
| Dell OptiPlex         | 3         | 2.21%   |
| Pegatron VS342AA-AB6  | 2         | 1.47%   |
| MSI GF63              | 2         | 1.47%   |
| HP ProBook            | 2         | 1.47%   |
| HP Compaq             | 2         | 1.47%   |
| HP 250                | 2         | 1.47%   |
| Foxconn Pro           | 2         | 1.47%   |
| ASUS X556UV           | 2         | 1.47%   |
| ASUS X550JX           | 2         | 1.47%   |
| ASUS VivoBook         | 2         | 1.47%   |
| ASUS ROG              | 2         | 1.47%   |
| ASUS PRIME            | 2         | 1.47%   |
| ASUS ASUS             | 2         | 1.47%   |
| Acer Swift            | 2         | 1.47%   |
| Unknown               | 2         | 1.47%   |
| Sony VPCEH36EF        | 1         | 0.74%   |
| Samsung 530U3BI       | 1         | 0.74%   |
| Samsung 300E5EV       | 1         | 0.74%   |
| Pegatron Pro          | 1         | 0.74%   |
| Packard Bell EasyNote | 1         | 0.74%   |
| MSI MS-7C95           | 1         | 0.74%   |
| MSI MS-7C52           | 1         | 0.74%   |
| MSI MS-7A15           | 1         | 0.74%   |
| MSI MS-7817           | 1         | 0.74%   |
| MSI MS-7502           | 1         | 0.74%   |
| MSI Katana            | 1         | 0.74%   |
| MSI GF65              | 1         | 0.74%   |
| Lenovo V310-15ISK     | 1         | 0.74%   |
| Lenovo V15-IIL        | 1         | 0.74%   |
| Lenovo ThinkStation   | 1         | 0.74%   |
| Lenovo IdeaPadFlex    | 1         | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 18        | 13.24%  |
| 2020 | 15        | 11.03%  |
| 2017 | 13        | 9.56%   |
| 2018 | 12        | 8.82%   |
| 2013 | 11        | 8.09%   |
| 2011 | 11        | 8.09%   |
| 2016 | 10        | 7.35%   |
| 2015 | 9         | 6.62%   |
| 2021 | 8         | 5.88%   |
| 2012 | 7         | 5.15%   |
| 2014 | 6         | 4.41%   |
| 2009 | 6         | 4.41%   |
| 2008 | 5         | 3.68%   |
| 2010 | 3         | 2.21%   |
| 2022 | 1         | 0.74%   |
| 2007 | 1         | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 110       | 80.88%  |
| Desktop     | 24        | 17.65%  |
| Convertible | 2         | 1.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 126       | 92.65%  |
| Enabled  | 10        | 7.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 136       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 50        | 36.5%   |
| 3.01-4.0   | 26        | 18.98%  |
| 16.01-24.0 | 24        | 17.52%  |
| 8.01-16.0  | 24        | 17.52%  |
| 1.01-2.0   | 6         | 4.38%   |
| 32.01-64.0 | 5         | 3.65%   |
| 2.01-3.0   | 2         | 1.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 45        | 30%     |
| 2.01-3.0  | 44        | 29.33%  |
| 4.01-8.0  | 26        | 17.33%  |
| 3.01-4.0  | 22        | 14.67%  |
| 0.51-1.0  | 6         | 4%      |
| 8.01-16.0 | 3         | 2%      |
| 0.01-0.5  | 3         | 2%      |
| Unknown   | 1         | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 101       | 72.66%  |
| 2      | 35        | 25.18%  |
| 4      | 2         | 1.44%   |
| 0      | 1         | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 70        | 51.09%  |
| Yes       | 67        | 48.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 88.97%  |
| No        | 15        | 11.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 90.51%  |
| No        | 13        | 9.49%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 76.26%  |
| No        | 33        | 23.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Tunisia | 136       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Tunis              | 82        | 54.3%   |
| Aryanah            | 8         | 5.3%    |
| Sousse             | 6         | 3.97%   |
| Nabeul             | 6         | 3.97%   |
| Bizerte            | 6         | 3.97%   |
| Monastir           | 3         | 1.99%   |
| Centre Urbain Nord | 3         | 1.99%   |
| Rades              | 2         | 1.32%   |
| Mateur             | 2         | 1.32%   |
| Masakin            | 2         | 1.32%   |
| Mahdia             | 2         | 1.32%   |
| Ben Arous          | 2         | 1.32%   |
| Zarzis             | 1         | 0.66%   |
| Zaouiat Djedidi    | 1         | 0.66%   |
| Wadi Maliz         | 1         | 0.66%   |
| Tebourba           | 1         | 0.66%   |
| Tataouine          | 1         | 0.66%   |
| Sfax               | 1         | 0.66%   |
| Rafraf             | 1         | 0.66%   |
| Oued Lill          | 1         | 0.66%   |
| Manouba            | 1         | 0.66%   |
| Le Bardo           | 1         | 0.66%   |
| La Goulette        | 1         | 0.66%   |
| Jendouba           | 1         | 0.66%   |
| Jedeida            | 1         | 0.66%   |
| Houmt Souk         | 1         | 0.66%   |
| Hergla             | 1         | 0.66%   |
| Hammamet           | 1         | 0.66%   |
| Gremda             | 1         | 0.66%   |
| Gafsa              | 1         | 0.66%   |
| El Fahs            | 1         | 0.66%   |
| El Battan          | 1         | 0.66%   |
| Carthage           | 1         | 0.66%   |
| Borj el Amri       | 1         | 0.66%   |
| Belvedere          | 1         | 0.66%   |
| Bellevue           | 1         | 0.66%   |
| Beja               | 1         | 0.66%   |
| As Sanad           | 1         | 0.66%   |
| Akouda             | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 36        | 45     | 21.56%  |
| WDC                   | 31        | 40     | 18.56%  |
| Toshiba               | 19        | 21     | 11.38%  |
| Samsung Electronics   | 14        | 17     | 8.38%   |
| Team                  | 11        | 13     | 6.59%   |
| SK hynix              | 9         | 10     | 5.39%   |
| SanDisk               | 6         | 7      | 3.59%   |
| HGST                  | 6         | 7      | 3.59%   |
| Kingston              | 5         | 7      | 2.99%   |
| Hitachi               | 5         | 5      | 2.99%   |
| Micron Technology     | 4         | 4      | 2.4%    |
| Unknown               | 3         | 3      | 1.8%    |
| Intel                 | 3         | 3      | 1.8%    |
| Fujitsu               | 3         | 3      | 1.8%    |
| PNY                   | 2         | 2      | 1.2%    |
| A-DATA Technology     | 2         | 2      | 1.2%    |
| UMIS                  | 1         | 1      | 0.6%    |
| TwinMOS               | 1         | 1      | 0.6%    |
| Realtek Semiconductor | 1         | 1      | 0.6%    |
| Phison                | 1         | 1      | 0.6%    |
| Patriot               | 1         | 1      | 0.6%    |
| OCZ                   | 1         | 1      | 0.6%    |
| EMTEC                 | 1         | 3      | 0.6%    |
| addlink               | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 10        | 5.78%   |
| Seagate ST500LT012-1DG142 500GB      | 7         | 4.05%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 3         | 1.73%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.73%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 1.73%   |
| Hitachi HTS545050A7E380 500GB        | 3         | 1.73%   |
| HGST HTS545050A7E380 500GB           | 3         | 1.73%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 1.16%   |
| WDC WD20SPZX-08UA7 2TB               | 2         | 1.16%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 1.16%   |
| WDC WD10SPCX-24HWST1 1TB             | 2         | 1.16%   |
| WDC WD10EADS-65M2B0 1TB              | 2         | 1.16%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 2         | 1.16%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.16%   |
| Toshiba MK5076GSX 500GB              | 2         | 1.16%   |
| Toshiba MK3275GSX 320GB              | 2         | 1.16%   |
| Toshiba DT01ACA050 500GB             | 2         | 1.16%   |
| Team T253X2512G 512GB SSD            | 2         | 1.16%   |
| SK hynix SC311 SATA 256GB SSD        | 2         | 1.16%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 1.16%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 1.16%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 1.16%   |
| SanDisk NVMe SSD Drive 512GB         | 2         | 1.16%   |
| Kingston NVMe SSD Drive 512GB        | 2         | 1.16%   |
| Fujitsu MHV2100BH PL 100GB           | 2         | 1.16%   |
| WDC WD5000LPZX-60Z10T0 500GB         | 1         | 0.58%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.58%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.58%   |
| WDC WD5000LPLX-60ZNTT2 500GB         | 1         | 0.58%   |
| WDC WD5000BPVT-55HXZT3 500GB         | 1         | 0.58%   |
| WDC WD5000AVDS-63U7B1 500GB          | 1         | 0.58%   |
| WDC WD5000AAKS-402AA0 500GB          | 1         | 0.58%   |
| WDC WD5000AACS-00ZUB0 500GB          | 1         | 0.58%   |
| WDC WD3200BEKT-60KA9T0 320GB         | 1         | 0.58%   |
| WDC WD3200AAJS-60M0A1 320GB          | 1         | 0.58%   |
| WDC WD2500BPVT-75JJ5T0 250GB         | 1         | 0.58%   |
| WDC WD2500AAJS-75M0A0 250GB          | 1         | 0.58%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.58%   |
| WDC WD10PURZ-85U8XY0 1TB             | 1         | 0.58%   |
| WDC WD10EZEX-75WN4A1 1TB             | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 36        | 45     | 37.5%   |
| WDC     | 27        | 35     | 28.13%  |
| Toshiba | 19        | 21     | 19.79%  |
| HGST    | 6         | 7      | 6.25%   |
| Hitachi | 5         | 5      | 5.21%   |
| Fujitsu | 3         | 3      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 7         | 9      | 22.58%  |
| Samsung Electronics | 6         | 9      | 19.35%  |
| SK hynix            | 5         | 5      | 16.13%  |
| SanDisk             | 3         | 3      | 9.68%   |
| PNY                 | 2         | 2      | 6.45%   |
| TwinMOS             | 1         | 1      | 3.23%   |
| Patriot             | 1         | 1      | 3.23%   |
| OCZ                 | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Kingston            | 1         | 1      | 3.23%   |
| EMTEC               | 1         | 3      | 3.23%   |
| addlink             | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 94        | 116    | 58.39%  |
| NVMe    | 33        | 42     | 20.5%   |
| SSD     | 31        | 38     | 19.25%  |
| MMC     | 2         | 2      | 1.24%   |
| Unknown | 1         | 1      | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 113       | 154    | 75.84%  |
| NVMe | 33        | 42     | 22.15%  |
| MMC  | 2         | 2      | 1.34%   |
| SAS  | 1         | 1      | 0.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 90     | 61.98%  |
| 0.51-1.0   | 41        | 58     | 33.88%  |
| 1.01-2.0   | 5         | 6      | 4.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 47        | 33.1%   |
| 101-250    | 41        | 28.87%  |
| 501-1000   | 20        | 14.08%  |
| 1001-2000  | 13        | 9.15%   |
| 51-100     | 9         | 6.34%   |
| 1-20       | 6         | 4.23%   |
| 21-50      | 4         | 2.82%   |
| Unknown    | 2         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 56        | 37.84%  |
| 101-250   | 25        | 16.89%  |
| 21-50     | 24        | 16.22%  |
| 51-100    | 24        | 16.22%  |
| 251-500   | 8         | 5.41%   |
| 501-1000  | 7         | 4.73%   |
| 1001-2000 | 2         | 1.35%   |
| Unknown   | 2         | 1.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E380 500GB                          | 2         | 3      | 12.5%   |
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 6.25%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 6.25%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 6.25%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 6.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 6.25%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 6.25%   |
| Seagate ST3320813AS 320GB                           | 1         | 1      | 6.25%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 6.25%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 6.25%   |
| EMTEC X250 512GB SSD                                | 1         | 2      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 5         | 5      | 31.25%  |
| Toshiba           | 4         | 5      | 25%     |
| Hitachi           | 2         | 2      | 12.5%   |
| HGST              | 2         | 3      | 12.5%   |
| WDC               | 1         | 2      | 6.25%   |
| Micron Technology | 1         | 1      | 6.25%   |
| EMTEC             | 1         | 2      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 35.71%  |
| Toshiba | 4         | 5      | 28.57%  |
| Hitachi | 2         | 2      | 14.29%  |
| HGST    | 2         | 3      | 14.29%  |
| WDC     | 1         | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 17     | 87.5%   |
| SSD  | 2         | 3      | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK1646GSX 160GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 65        | 90     | 44.83%  |
| Works    | 63        | 88     | 43.45%  |
| Malfunc  | 16        | 20     | 11.03%  |
| Failed   | 1         | 1      | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 114       | 70.37%  |
| AMD                          | 15        | 9.26%   |
| Samsung Electronics          | 8         | 4.94%   |
| SanDisk                      | 6         | 3.7%    |
| SK hynix                     | 4         | 2.47%   |
| Kingston Technology Company  | 4         | 2.47%   |
| Phison Electronics           | 3         | 1.85%   |
| Micron Technology            | 3         | 1.85%   |
| Realtek Semiconductor        | 2         | 1.23%   |
| Union Memory (Shenzhen)      | 1         | 0.62%   |
| Silicon Motion               | 1         | 0.62%   |
| Shenzhen Longsys Electronics | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 14        | 8.05%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 6.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 11        | 6.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 4.6%    |
| Samsung NVMe SSD Controller 980                                                         | 7         | 4.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 4.02%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 2.87%   |
| Kingston Company Company Non-Volatile memory controller                                 | 4         | 2.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 2.3%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 2.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 2.3%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4         | 2.3%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3         | 1.72%   |
| Micron Non-Volatile memory controller                                                   | 3         | 1.72%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.72%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.72%   |
| SK hynix BC511                                                                          | 2         | 1.15%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 1.15%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2         | 1.15%   |
| Phison E12 NVMe Controller                                                              | 2         | 1.15%   |
| Intel SSD 660P Series                                                                   | 2         | 1.15%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.15%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 0.57%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.57%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1         | 0.57%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 104       | 63.8%   |
| NVMe | 33        | 20.25%  |
| RAID | 15        | 9.2%    |
| IDE  | 11        | 6.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 117       | 86.03%  |
| AMD    | 19        | 13.97%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 3.68%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 2.94%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 2.21%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 2.21%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 2.21%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.21%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 2.21%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 1.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.47%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.47%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 1.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.47%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.47%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.47%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.47%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.47%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.47%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 2         | 1.47%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 1.47%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.47%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.47%   |
| Intel Xeon E-2144G CPU @ 3.60GHz              | 1         | 0.74%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.74%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 0.74%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.74%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.74%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.74%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 1         | 0.74%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.74%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 1         | 0.74%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.74%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.74%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 28.68%  |
| Intel Core i7           | 26        | 19.12%  |
| Intel Core i3           | 22        | 16.18%  |
| Intel Pentium           | 9         | 6.62%   |
| AMD Ryzen 5             | 9         | 6.62%   |
| Other                   | 7         | 5.15%   |
| Intel Core 2 Duo        | 4         | 2.94%   |
| Intel Core 2 Quad       | 3         | 2.21%   |
| Intel Celeron           | 3         | 2.21%   |
| Intel Pentium Dual-Core | 2         | 1.47%   |
| AMD Ryzen 7             | 2         | 1.47%   |
| Intel Xeon              | 1         | 0.74%   |
| Intel Core m3           | 1         | 0.74%   |
| Intel Atom              | 1         | 0.74%   |
| AMD Sempron             | 1         | 0.74%   |
| AMD Ryzen 5 PRO         | 1         | 0.74%   |
| AMD E2                  | 1         | 0.74%   |
| AMD E                   | 1         | 0.74%   |
| AMD A8                  | 1         | 0.74%   |
| AMD A6                  | 1         | 0.74%   |
| AMD A4                  | 1         | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 67        | 49.26%  |
| 4       | 50        | 36.76%  |
| 6       | 10        | 7.35%   |
| 8       | 4         | 2.94%   |
| 1       | 2         | 1.47%   |
| 14      | 1         | 0.74%   |
| 12      | 1         | 0.74%   |
| Unknown | 1         | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 107       | 78.1%   |
| 1       | 29        | 21.17%  |
| Unknown | 1         | 0.73%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 135       | 99.26%  |
| Unknown        | 1         | 0.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 18.57%  |
| 0x206a7    | 11        | 7.86%   |
| 0x806ea    | 8         | 5.71%   |
| 0x40651    | 8         | 5.71%   |
| 0x306a9    | 7         | 5%      |
| 0x806ec    | 6         | 4.29%   |
| 0x1067a    | 6         | 4.29%   |
| 0xa0652    | 5         | 3.57%   |
| 0x906ea    | 5         | 3.57%   |
| 0x506e3    | 5         | 3.57%   |
| 0x406e3    | 5         | 3.57%   |
| 0x306c3    | 4         | 2.86%   |
| 0x806c1    | 3         | 2.14%   |
| 0x706e5    | 3         | 2.14%   |
| 0x306d4    | 3         | 2.14%   |
| 0x20655    | 3         | 2.14%   |
| 0x08108109 | 3         | 2.14%   |
| 0x806e9    | 2         | 1.43%   |
| 0x406c4    | 2         | 1.43%   |
| 0x08600106 | 2         | 1.43%   |
| 0x08108102 | 2         | 1.43%   |
| 0x06006705 | 2         | 1.43%   |
| 0x06006704 | 2         | 1.43%   |
| 0xa0653    | 1         | 0.71%   |
| 0x906e9    | 1         | 0.71%   |
| 0x906a3    | 1         | 0.71%   |
| 0x90672    | 1         | 0.71%   |
| 0x6fd      | 1         | 0.71%   |
| 0x6fb      | 1         | 0.71%   |
| 0x506c9    | 1         | 0.71%   |
| 0x40661    | 1         | 0.71%   |
| 0x30678    | 1         | 0.71%   |
| 0x20652    | 1         | 0.71%   |
| 0x106ca    | 1         | 0.71%   |
| 0x0a50000c | 1         | 0.71%   |
| 0x0a404101 | 1         | 0.71%   |
| 0x08701013 | 1         | 0.71%   |
| 0x08600104 | 1         | 0.71%   |
| 0x02000032 | 1         | 0.71%   |
| 0x00000000 | 1         | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 21.32%  |
| Haswell          | 15        | 11.03%  |
| SandyBridge      | 13        | 9.56%   |
| Skylake          | 11        | 8.09%   |
| Penryn           | 7         | 5.15%   |
| IvyBridge        | 7         | 5.15%   |
| CometLake        | 7         | 5.15%   |
| Zen+             | 5         | 3.68%   |
| Westmere         | 5         | 3.68%   |
| IceLake          | 5         | 3.68%   |
| Zen 2            | 4         | 2.94%   |
| TigerLake        | 4         | 2.94%   |
| Silvermont       | 4         | 2.94%   |
| Excavator        | 4         | 2.94%   |
| Broadwell        | 4         | 2.94%   |
| Zen 3            | 2         | 1.47%   |
| Core             | 2         | 1.47%   |
| Unknown          | 2         | 1.47%   |
| Puma             | 1         | 0.74%   |
| K8 & K10 hybrid  | 1         | 0.74%   |
| Goldmont         | 1         | 0.74%   |
| Bonnell          | 1         | 0.74%   |
| Bobcat           | 1         | 0.74%   |
| Alderlake Hybrid | 1         | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 102       | 52.58%  |
| Nvidia | 56        | 28.87%  |
| AMD    | 36        | 18.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 4.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.59%   |
| Intel UHD Graphics 620                                                                   | 8         | 4.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 3.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 3.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.06%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.55%   |
| Intel HD Graphics 620                                                                    | 5         | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.55%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 2.04%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.04%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 2.04%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.04%   |
| Intel HD Graphics 530                                                                    | 4         | 2.04%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.04%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.53%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.53%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 1.53%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.53%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.53%   |
| AMD Renoir                                                                               | 3         | 1.53%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.53%   |
| Nvidia TU117M                                                                            | 2         | 1.02%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.02%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.02%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.02%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.51%   |
| Nvidia GT218M [GeForce G 105M]                                                           | 1         | 0.51%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.51%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 50        | 36.76%  |
| Intel + Nvidia | 37        | 27.21%  |
| 1 x AMD        | 15        | 11.03%  |
| 1 x Nvidia     | 13        | 9.56%   |
| Intel + AMD    | 13        | 9.56%   |
| AMD + Nvidia   | 6         | 4.41%   |
| 2 x AMD        | 2         | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 108       | 76.6%   |
| Proprietary | 28        | 19.86%  |
| Unknown     | 5         | 3.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 52.14%  |
| 1.01-2.0   | 24        | 17.14%  |
| 3.01-4.0   | 13        | 9.29%   |
| 0.01-0.5   | 13        | 9.29%   |
| 0.51-1.0   | 11        | 7.86%   |
| 5.01-6.0   | 3         | 2.14%   |
| 2.01-3.0   | 2         | 1.43%   |
| 7.01-8.0   | 1         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 27        | 18%     |
| AU Optronics            | 27        | 18%     |
| Chimei Innolux          | 26        | 17.33%  |
| BOE                     | 24        | 16%     |
| LG Display              | 14        | 9.33%   |
| Hewlett-Packard         | 9         | 6%      |
| Chi Mei Optoelectronics | 3         | 2%      |
| PANDA                   | 2         | 1.33%   |
| Packard Bell            | 2         | 1.33%   |
| Lenovo                  | 2         | 1.33%   |
| Dell                    | 2         | 1.33%   |
| BenQ                    | 2         | 1.33%   |
| S2-Tek                  | 1         | 0.67%   |
| PKB                     | 1         | 0.67%   |
| Philips                 | 1         | 0.67%   |
| MSI                     | 1         | 0.67%   |
| Medion                  | 1         | 0.67%   |
| LG Philips              | 1         | 0.67%   |
| ITE                     | 1         | 0.67%   |
| Goldstar                | 1         | 0.67%   |
| GDH                     | 1         | 0.67%   |
| Acer                    | 1         | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 3.29%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 1.97%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.97%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 1.97%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 1.32%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 1.32%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 2         | 1.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 1.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.32%   |
| Hewlett-Packard x20LED HWP2910 1600x900 443x249mm 20.0-inch           | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 1.32%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.32%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.32%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM0284 1280x1024 338x270mm 17.0-inch  | 1         | 0.66%   |
| Samsung Electronics SMB2240 SAM06AD 1920x1080 477x268mm 21.5-inch     | 1         | 0.66%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 1         | 0.66%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch      | 1         | 0.66%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 1         | 0.66%   |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                       | 1         | 0.66%   |
| PKB LCD Monitor VIS220WS 1680x1050                                    | 1         | 0.66%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1         | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.66%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 62        | 44.29%  |
| 1366x768 (WXGA)    | 52        | 37.14%  |
| 1600x900 (HD+)     | 11        | 7.86%   |
| 3840x2160 (4K)     | 4         | 2.86%   |
| 1680x1050 (WSXGA+) | 3         | 2.14%   |
| 1280x800 (WXGA)    | 2         | 1.43%   |
| 1280x1024 (SXGA)   | 2         | 1.43%   |
| 3840x1100          | 1         | 0.71%   |
| 2560x1440 (QHD)    | 1         | 0.71%   |
| 1440x900 (WXGA+)   | 1         | 0.71%   |
| 1024x600           | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 84        | 56%     |
| 21      | 9         | 6%      |
| 17      | 9         | 6%      |
| 14      | 7         | 4.67%   |
| 13      | 7         | 4.67%   |
| 24      | 6         | 4%      |
| 23      | 6         | 4%      |
| 20      | 6         | 4%      |
| 27      | 3         | 2%      |
| 22      | 2         | 1.33%   |
| 11      | 2         | 1.33%   |
| Unknown | 2         | 1.33%   |
| 52      | 1         | 0.67%   |
| 42      | 1         | 0.67%   |
| 31      | 1         | 0.67%   |
| 19      | 1         | 0.67%   |
| 18      | 1         | 0.67%   |
| 12      | 1         | 0.67%   |
| 10      | 1         | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 95        | 65.07%  |
| 401-500     | 18        | 12.33%  |
| 501-600     | 14        | 9.59%   |
| 351-400     | 8         | 5.48%   |
| 201-300     | 6         | 4.11%   |
| Unknown     | 2         | 1.37%   |
| 601-700     | 1         | 0.68%   |
| 1001-1500   | 1         | 0.68%   |
| 901-1000    | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 122       | 91.04%  |
| 16/10   | 7         | 5.22%   |
| 5/4     | 2         | 1.49%   |
| Unknown | 2         | 1.49%   |
| 3.40    | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 84        | 56%     |
| 201-250        | 22        | 14.67%  |
| 81-90          | 11        | 7.33%   |
| 151-200        | 8         | 5.33%   |
| 121-130        | 5         | 3.33%   |
| 51-60          | 3         | 2%      |
| 301-350        | 3         | 2%      |
| 141-150        | 3         | 2%      |
| 71-80          | 2         | 1.33%   |
| 131-140        | 2         | 1.33%   |
| Unknown        | 2         | 1.33%   |
| More than 1000 | 1         | 0.67%   |
| 61-70          | 1         | 0.67%   |
| 351-500        | 1         | 0.67%   |
| 41-50          | 1         | 0.67%   |
| 501-1000       | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 54        | 37.24%  |
| 121-160       | 46        | 31.72%  |
| 51-100        | 36        | 24.83%  |
| 161-240       | 3         | 2.07%   |
| More than 240 | 2         | 1.38%   |
| 1-50          | 2         | 1.38%   |
| Unknown       | 2         | 1.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 112       | 81.16%  |
| 2     | 21        | 15.22%  |
| 0     | 5         | 3.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 103       | 46.19%  |
| Intel                             | 48        | 21.52%  |
| Qualcomm Atheros                  | 30        | 13.45%  |
| Broadcom                          | 13        | 5.83%   |
| Ralink                            | 6         | 2.69%   |
| Ralink Technology                 | 5         | 2.24%   |
| Broadcom Limited                  | 5         | 2.24%   |
| MediaTek                          | 2         | 0.9%    |
| D-Link                            | 2         | 0.9%    |
| Sierra Wireless                   | 1         | 0.45%   |
| Samsung Electronics               | 1         | 0.45%   |
| OPPO Electronics                  | 1         | 0.45%   |
| Marvell Technology Group          | 1         | 0.45%   |
| IMC Networks                      | 1         | 0.45%   |
| ICS Advent                        | 1         | 0.45%   |
| Huawei Technologies               | 1         | 0.45%   |
| Ericsson Business Mobile Networks | 1         | 0.45%   |
| D-Link System                     | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 27.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 9.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 4.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 3.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.67%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 2.67%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.91%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.53%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.15%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.15%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.15%   |
| Intel Wireless 7265                                               | 3         | 1.15%   |
| Intel WiFi Link 5100                                              | 3         | 1.15%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.15%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.76%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.76%   |
| Intel Wireless 8260                                               | 2         | 0.76%   |
| Intel Wireless 7260                                               | 2         | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.76%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.76%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 0.76%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.76%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.76%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.76%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.76%   |
| Sierra Wireless EM7455                                            | 1         | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 44        | 32.59%  |
| Realtek Semiconductor             | 30        | 22.22%  |
| Qualcomm Atheros                  | 27        | 20%     |
| Broadcom                          | 10        | 7.41%   |
| Ralink                            | 6         | 4.44%   |
| Ralink Technology                 | 5         | 3.7%    |
| Broadcom Limited                  | 5         | 3.7%    |
| MediaTek                          | 2         | 1.48%   |
| D-Link                            | 2         | 1.48%   |
| Sierra Wireless                   | 1         | 0.74%   |
| IMC Networks                      | 1         | 0.74%   |
| Ericsson Business Mobile Networks | 1         | 0.74%   |
| D-Link System                     | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 8.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 6.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 5.15%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 5.15%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 5.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 4.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.68%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 2.21%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.21%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.21%   |
| Intel Wireless 7265                                            | 3         | 2.21%   |
| Intel WiFi Link 5100                                           | 3         | 2.21%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.21%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 1.47%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2         | 1.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.47%   |
| Intel Wireless 8260                                            | 2         | 1.47%   |
| Intel Wireless 7260                                            | 2         | 1.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.47%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 1.47%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 1.47%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.47%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.47%   |
| Sierra Wireless EM7455                                         | 1         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.74%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.74%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 98        | 78.4%   |
| Intel                    | 15        | 12%     |
| Qualcomm Atheros         | 4         | 3.2%    |
| Broadcom                 | 3         | 2.4%    |
| Samsung Electronics      | 1         | 0.8%    |
| OPPO Electronics         | 1         | 0.8%    |
| Marvell Technology Group | 1         | 0.8%    |
| ICS Advent               | 1         | 0.8%    |
| Huawei Technologies      | 1         | 0.8%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 57.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 19.05%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.59%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.59%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.79%   |
| OPPO RMX2117                                                      | 1         | 0.79%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.79%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.79%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.79%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.79%   |
| Huawei HUAWEI                                                     | 1         | 0.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 124       | 50.61%  |
| Ethernet | 121       | 49.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 71.43%  |
| Ethernet | 40        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 104       | 75.91%  |
| 1     | 33        | 24.09%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 136       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 34.91%  |
| Realtek Semiconductor           | 20        | 18.87%  |
| Qualcomm Atheros Communications | 18        | 16.98%  |
| Lite-On Technology              | 8         | 7.55%   |
| Broadcom                        | 6         | 5.66%   |
| IMC Networks                    | 5         | 4.72%   |
| Ralink                          | 3         | 2.83%   |
| Foxconn / Hon Hai               | 3         | 2.83%   |
| Cambridge Silicon Radio         | 2         | 1.89%   |
| Toshiba                         | 1         | 0.94%   |
| Realtek                         | 1         | 0.94%   |
| Hewlett-Packard                 | 1         | 0.94%   |
| Dell                            | 1         | 0.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 15        | 14.15%  |
| Realtek Bluetooth Radio                             | 14        | 13.21%  |
| Intel Bluetooth wireless interface                  | 13        | 12.26%  |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 10.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 5.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 3.77%   |
| Ralink RT3290 Bluetooth                             | 3         | 2.83%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 2.83%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.83%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 2.83%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.89%   |
| Lite-On Bluetooth Device                            | 2         | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.89%   |
| IMC Networks Wireless_Device                        | 2         | 1.89%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.89%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.89%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.94%   |
| Realtek Bluetooth Radio                             | 1         | 0.94%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.94%   |
| Lite-On BCM43142A0                                  | 1         | 0.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.94%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.94%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.94%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.94%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 117       | 66.1%   |
| Nvidia              | 31        | 17.51%  |
| AMD                 | 25        | 14.12%  |
| Lenovo              | 1         | 0.56%   |
| JMTek               | 1         | 0.56%   |
| DSEA A/S            | 1         | 0.56%   |
| C-Media Electronics | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 9.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 5.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 4.95%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 4.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 4.46%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 3.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 3.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 3.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 2.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 2.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 2.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.48%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.98%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.98%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.98%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.98%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.49%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.99%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.99%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.99%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.99%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia Audio device                                                                               | 1         | 0.5%    |
| Lenovo ThinkVision T24v Wide Monitor for USB-Audio                                                | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 29.63%  |
| SK hynix            | 19        | 17.59%  |
| Micron Technology   | 11        | 10.19%  |
| Team                | 10        | 9.26%   |
| Unknown             | 6         | 5.56%   |
| A-DATA Technology   | 6         | 5.56%   |
| Crucial             | 5         | 4.63%   |
| Nanya Technology    | 3         | 2.78%   |
| Kingston            | 3         | 2.78%   |
| Elpida              | 3         | 2.78%   |
| Toshiba             | 2         | 1.85%   |
| Ramaxel Technology  | 2         | 1.85%   |
| TwinMOS             | 1         | 0.93%   |
| Patriot             | 1         | 0.93%   |
| Hikvision           | 1         | 0.93%   |
| GOODRAM             | 1         | 0.93%   |
| ASint Technology    | 1         | 0.93%   |
| Unknown             | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s | 3         | 2.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 3         | 2.61%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s               | 3         | 2.61%   |
| Toshiba RAM 8HTF12864HDY-800G1 1024MB SODIMM 1066MT/s     | 2         | 1.74%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s      | 2         | 1.74%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s      | 2         | 1.74%   |
| Team RAM TEAMGROUP-SD4-2400 16384MB SODIMM DDR4 8400MT/s  | 2         | 1.74%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s  | 2         | 1.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 1.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 1.74%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.74%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s  | 2         | 1.74%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.74%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s      | 2         | 1.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1         | 0.87%   |
| Unknown RAM Module 4GB DIMM DDR3                          | 1         | 0.87%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s            | 1         | 0.87%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 1         | 0.87%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s             | 1         | 0.87%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                    | 1         | 0.87%   |
| TwinMOS RAM 9DSDBNZB-5AMP 4GB DIMM DDR3 1333MT/s          | 1         | 0.87%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s        | 1         | 0.87%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s        | 1         | 0.87%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s     | 1         | 0.87%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s     | 1         | 0.87%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s      | 1         | 0.87%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s               | 1         | 0.87%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1333MT/s             | 1         | 0.87%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s     | 1         | 0.87%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.87%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 0.87%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 0.87%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 0.87%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 0.87%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 0.87%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1         | 0.87%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 51        | 58.62%  |
| DDR3    | 24        | 27.59%  |
| DDR2    | 4         | 4.6%    |
| SDRAM   | 3         | 3.45%   |
| LPDDR4  | 2         | 2.3%    |
| LPDDR3  | 1         | 1.15%   |
| DDR5    | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 80.23%  |
| DIMM         | 13        | 15.12%  |
| Row Of Chips | 3         | 3.49%   |
| Chip         | 1         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 37        | 37%     |
| 8192  | 33        | 33%     |
| 16384 | 12        | 12%     |
| 2048  | 11        | 11%     |
| 32768 | 5         | 5%      |
| 1024  | 2         | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 25        | 25.51%  |
| 3200    | 21        | 21.43%  |
| 1600    | 14        | 14.29%  |
| 1334    | 7         | 7.14%   |
| 2400    | 6         | 6.12%   |
| 1333    | 4         | 4.08%   |
| 2133    | 3         | 3.06%   |
| 8400    | 2         | 2.04%   |
| 4199    | 2         | 2.04%   |
| 3266    | 2         | 2.04%   |
| 1867    | 2         | 2.04%   |
| 1066    | 2         | 2.04%   |
| 667     | 2         | 2.04%   |
| Unknown | 2         | 2.04%   |
| 4800    | 1         | 1.02%   |
| 3000    | 1         | 1.02%   |
| 975     | 1         | 1.02%   |
| 800     | 1         | 1.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 66.67%  |
| Seiko Epson     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L365 Series | 1         | 33.33%  |
| HP LaserJet P1005       | 1         | 33.33%  |
| HP DeskJet 5810 series  | 1         | 33.33%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 20.19%  |
| Realtek Semiconductor                  | 16        | 15.38%  |
| IMC Networks                           | 13        | 12.5%   |
| Microdia                               | 8         | 7.69%   |
| Acer                                   | 8         | 7.69%   |
| Suyin                                  | 6         | 5.77%   |
| Syntek                                 | 5         | 4.81%   |
| Sunplus Innovation Technology          | 5         | 4.81%   |
| Lite-On Technology                     | 5         | 4.81%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.81%   |
| Quanta                                 | 3         | 2.88%   |
| Luxvisions Innotech Limited            | 3         | 2.88%   |
| Silicon Motion                         | 1         | 0.96%   |
| Ricoh                                  | 1         | 0.96%   |
| Importek                               | 1         | 0.96%   |
| Cubeternet                             | 1         | 0.96%   |
| Apple                                  | 1         | 0.96%   |
| Alcor Micro                            | 1         | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 5.71%   |
| Chicony Integrated Camera                                   | 6         | 5.71%   |
| Acer Integrated Camera                                      | 4         | 3.81%   |
| Syntek EasyCamera                                           | 3         | 2.86%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 2.86%   |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 2.86%   |
| Realtek USB Camera                                          | 3         | 2.86%   |
| Realtek Integrated_Webcam_HD                                | 3         | 2.86%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 3         | 2.86%   |
| Lite-On Integrated Camera                                   | 3         | 2.86%   |
| IMC Networks Integrated Camera                              | 3         | 2.86%   |
| Chicony HD WebCam                                           | 3         | 2.86%   |
| Suyin HP TrueVision HD                                      | 2         | 1.9%    |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.9%    |
| Realtek EasyCamera                                          | 2         | 1.9%    |
| Quanta HD WebCam                                            | 2         | 1.9%    |
| Microdia Laptop_Integrated_Webcam_HD                        | 2         | 1.9%    |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.9%    |
| Chicony Lenovo EasyCamera                                   | 2         | 1.9%    |
| Chicony EasyCamera                                          | 2         | 1.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.9%    |
| Acer HD Webcam                                              | 2         | 1.9%    |
| Syntek Integrated RGB Camera                                | 1         | 0.95%   |
| Syntek Integrated Camera                                    | 1         | 0.95%   |
| Suyin USB 2.0 Camera                                        | 1         | 0.95%   |
| Suyin HP Integrated Webcam                                  | 1         | 0.95%   |
| Suyin HD WebCam                                             | 1         | 0.95%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.95%   |
| Sunplus HD User Facing                                      | 1         | 0.95%   |
| Sunplus Dell HD Webcam                                      | 1         | 0.95%   |
| Silicon Motion WebCam SC-13HDL11431N                        | 1         | 0.95%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 0.95%   |
| Realtek Integrated Webcam_HD                                | 1         | 0.95%   |
| Realtek Integrated Webcam                                   | 1         | 0.95%   |
| Realtek HP Webcam                                           | 1         | 0.95%   |
| Quanta HP Webcam                                            | 1         | 0.95%   |
| Microdia Webcam SC-10HDD12636P                              | 1         | 0.95%   |
| Microdia Integrated_Webcam_HD                               | 1         | 0.95%   |
| Microdia HP Webcam                                          | 1         | 0.95%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 44.44%  |
| Shenzhen Goodix Technology | 2         | 22.22%  |
| LighTuning Technology      | 2         | 22.22%  |
| Synaptics                  | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor      | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader       | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor     | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                  | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner             | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device              | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader               | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom 5880                                                                | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 106       | 71.14%  |
| 1     | 35        | 23.49%  |
| 3     | 4         | 2.68%   |
| 2     | 3         | 2.01%   |
| 4     | 1         | 0.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 13        | 25%     |
| Net/wireless             | 12        | 23.08%  |
| Fingerprint reader       | 9         | 17.31%  |
| Bluetooth                | 5         | 9.62%   |
| Communication controller | 3         | 5.77%   |
| Chipcard                 | 3         | 5.77%   |
| Storage                  | 2         | 3.85%   |
| Sound                    | 1         | 1.92%   |
| Network                  | 1         | 1.92%   |
| Net/ethernet             | 1         | 1.92%   |
| Card reader              | 1         | 1.92%   |
| Camera                   | 1         | 1.92%   |

