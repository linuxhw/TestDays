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

Total: 182

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 34        | 26.15%  |
| Ubuntu 18.04      | 16        | 12.31%  |
| Ubuntu 21.10      | 5         | 3.85%   |
| OpenMandriva 4.2  | 5         | 3.85%   |
| Ubuntu 16.04      | 4         | 3.08%   |
| Zorin 15          | 3         | 2.31%   |
| Ubuntu 19.10      | 3         | 2.31%   |
| OpenMandriva 4.3  | 3         | 2.31%   |
| Debian 10         | 3         | 2.31%   |
| Ubuntu 22.04      | 2         | 1.54%   |
| Ubuntu 21.04      | 2         | 1.54%   |
| Ubuntu 20.10      | 2         | 1.54%   |
| ROSA R10          | 2         | 1.54%   |
| Pop!_OS 22.04     | 2         | 1.54%   |
| Pop!_OS 21.04     | 2         | 1.54%   |
| Manjaro 21.1.0    | 2         | 1.54%   |
| LMDE 4            | 2         | 1.54%   |
| Linux Mint 20.3   | 2         | 1.54%   |
| Linux Mint 20.2   | 2         | 1.54%   |
| Linux Mint 20     | 2         | 1.54%   |
| Gentoo 2.7        | 2         | 1.54%   |
| Fedora 35         | 2         | 1.54%   |
| Fedora 33         | 2         | 1.54%   |
| Debian 11         | 2         | 1.54%   |
| ArcoLinux Rolling | 2         | 1.54%   |
| Arch              | 2         | 1.54%   |
| Xubuntu 18.04     | 1         | 0.77%   |
| Ubuntu 19.04      | 1         | 0.77%   |
| Sodalite 35       | 1         | 0.77%   |
| ROSA R8.1         | 1         | 0.77%   |
| ROSA R11          | 1         | 0.77%   |
| Pop!_OS 20.10     | 1         | 0.77%   |
| Manjaro 20.2      | 1         | 0.77%   |
| Lubuntu 20.04     | 1         | 0.77%   |
| Lubuntu 18.04     | 1         | 0.77%   |
| Linux Mint 20.1   | 1         | 0.77%   |
| Kubuntu 20.04     | 1         | 0.77%   |
| Gentoo 2.8        | 1         | 0.77%   |
| Fedora 31         | 1         | 0.77%   |
| Endless 3.9.5     | 1         | 0.77%   |
| Endless 3.7.8     | 1         | 0.77%   |
| Endless 3.5.0     | 1         | 0.77%   |
| Elementary 5.1.5  | 1         | 0.77%   |
| Deepin            | 1         | 0.77%   |
| BlackPanther 18.1 | 1         | 0.77%   |
| Arch Rolling      | 1         | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 66        | 52.8%   |
| OpenMandriva | 8         | 6.4%    |
| Linux Mint   | 7         | 5.6%    |
| Pop!_OS      | 5         | 4%      |
| Debian       | 5         | 4%      |
| ROSA         | 4         | 3.2%    |
| Fedora       | 4         | 3.2%    |
| Zorin        | 3         | 2.4%    |
| Manjaro      | 3         | 2.4%    |
| Endless      | 3         | 2.4%    |
| Arch         | 3         | 2.4%    |
| Lubuntu      | 2         | 1.6%    |
| LMDE         | 2         | 1.6%    |
| Gentoo       | 2         | 1.6%    |
| ArcoLinux    | 2         | 1.6%    |
| Xubuntu      | 1         | 0.8%    |
| Sodalite     | 1         | 0.8%    |
| Kubuntu      | 1         | 0.8%    |
| Elementary   | 1         | 0.8%    |
| Deepin       | 1         | 0.8%    |
| BlackPanther | 1         | 0.8%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 5         | 3.6%    |
| 5.13.0-28-generic               | 4         | 2.88%   |
| 5.3.0-46-generic                | 3         | 2.16%   |
| 5.3.0-40-generic                | 3         | 2.16%   |
| 5.16.7-desktop-1omv4003         | 3         | 2.16%   |
| 5.11.0-38-generic               | 3         | 2.16%   |
| 5.8.0-38-generic                | 2         | 1.44%   |
| 5.4.0-72-generic                | 2         | 1.44%   |
| 5.4.0-58-generic                | 2         | 1.44%   |
| 5.4.0-52-generic                | 2         | 1.44%   |
| 5.4.0-42-generic                | 2         | 1.44%   |
| 5.4.0-26-generic                | 2         | 1.44%   |
| 5.3.0-28-generic                | 2         | 1.44%   |
| 5.13.0-40-generic               | 2         | 1.44%   |
| 5.11.0-7620-generic             | 2         | 1.44%   |
| 5.11.0-40-generic               | 2         | 1.44%   |
| 5.11.0-27-generic               | 2         | 1.44%   |
| 5.10.27-gentoo                  | 2         | 1.44%   |
| 5.10.0-12-amd64                 | 2         | 1.44%   |
| 5.0.0-25-generic                | 2         | 1.44%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 1.44%   |
| 4.19.0-6-amd64                  | 2         | 1.44%   |
| 4.15.0-91-generic               | 2         | 1.44%   |
| 5.9.9-arch1-1                   | 1         | 0.72%   |
| 5.9.1-arch1-1                   | 1         | 0.72%   |
| 5.8.15-301.fc33.x86_64          | 1         | 0.72%   |
| 5.8.0-50-generic                | 1         | 0.72%   |
| 5.8.0-44-generic                | 1         | 0.72%   |
| 5.8.0-40-generic                | 1         | 0.72%   |
| 5.8.0-33-generic                | 1         | 0.72%   |
| 5.8.0-32-generic                | 1         | 0.72%   |
| 5.8.0-28-generic                | 1         | 0.72%   |
| 5.8.0-14-generic                | 1         | 0.72%   |
| 5.6.14-desktop-2bP              | 1         | 0.72%   |
| 5.4.80-2-MANJARO                | 1         | 0.72%   |
| 5.4.143-1-pve                   | 1         | 0.72%   |
| 5.4.119-1-pve                   | 1         | 0.72%   |
| 5.4.0-91-generic                | 1         | 0.72%   |
| 5.4.0-90-generic                | 1         | 0.72%   |
| 5.4.0-84-generic                | 1         | 0.72%   |
| 5.4.0-73-generic                | 1         | 0.72%   |
| 5.4.0-65-lowlatency             | 1         | 0.72%   |
| 5.4.0-65-generic                | 1         | 0.72%   |
| 5.4.0-56-generic                | 1         | 0.72%   |
| 5.4.0-48-generic                | 1         | 0.72%   |
| 5.4.0-47-generic                | 1         | 0.72%   |
| 5.4.0-45-generic                | 1         | 0.72%   |
| 5.4.0-40-generic                | 1         | 0.72%   |
| 5.4.0-33-generic                | 1         | 0.72%   |
| 5.4.0-31-generic                | 1         | 0.72%   |
| 5.4.0-29-generic                | 1         | 0.72%   |
| 5.4.0-28-lowlatency             | 1         | 0.72%   |
| 5.4.0-107-generic               | 1         | 0.72%   |
| 5.3.8-300.fc31.x86_64           | 1         | 0.72%   |
| 5.3.0-59-generic                | 1         | 0.72%   |
| 5.3.0-26-generic                | 1         | 0.72%   |
| 5.3.0-19-generic                | 1         | 0.72%   |
| 5.17.5-76051705-generic         | 1         | 0.72%   |
| 5.17.15-76051715-generic        | 1         | 0.72%   |
| 5.16.9-200.fc35.x86_64          | 1         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 18.38%  |
| 5.13.0  | 13        | 9.56%   |
| 5.11.0  | 12        | 8.82%   |
| 5.3.0   | 11        | 8.09%   |
| 4.15.0  | 10        | 7.35%   |
| 5.8.0   | 9         | 6.62%   |
| 5.0.0   | 7         | 5.15%   |
| 5.10.14 | 5         | 3.68%   |
| 4.19.0  | 4         | 2.94%   |
| 5.16.7  | 3         | 2.21%   |
| 4.18.0  | 3         | 2.21%   |
| 5.15.0  | 2         | 1.47%   |
| 5.10.27 | 2         | 1.47%   |
| 5.10.0  | 2         | 1.47%   |
| 4.9.60  | 2         | 1.47%   |
| 5.9.9   | 1         | 0.74%   |
| 5.9.1   | 1         | 0.74%   |
| 5.8.15  | 1         | 0.74%   |
| 5.6.14  | 1         | 0.74%   |
| 5.4.80  | 1         | 0.74%   |
| 5.4.143 | 1         | 0.74%   |
| 5.4.119 | 1         | 0.74%   |
| 5.3.8   | 1         | 0.74%   |
| 5.17.5  | 1         | 0.74%   |
| 5.17.15 | 1         | 0.74%   |
| 5.16.9  | 1         | 0.74%   |
| 5.16.18 | 1         | 0.74%   |
| 5.16.11 | 1         | 0.74%   |
| 5.15.5  | 1         | 0.74%   |
| 5.15.16 | 1         | 0.74%   |
| 5.15.11 | 1         | 0.74%   |
| 5.13.11 | 1         | 0.74%   |
| 5.12.12 | 1         | 0.74%   |
| 5.11.17 | 1         | 0.74%   |
| 5.11.13 | 1         | 0.74%   |
| 5.10.53 | 1         | 0.74%   |
| 5.10.19 | 1         | 0.74%   |
| 4.9.9   | 1         | 0.74%   |
| 4.9.124 | 1         | 0.74%   |
| 4.4.0   | 1         | 0.74%   |
| 3.13.0  | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 27        | 20.3%   |
| 5.13    | 14        | 10.53%  |
| 5.11    | 14        | 10.53%  |
| 5.3     | 12        | 9.02%   |
| 5.10    | 11        | 8.27%   |
| 5.8     | 10        | 7.52%   |
| 4.15    | 10        | 7.52%   |
| 5.0     | 7         | 5.26%   |
| 5.16    | 5         | 3.76%   |
| 5.15    | 5         | 3.76%   |
| 4.19    | 4         | 3.01%   |
| 4.9     | 3         | 2.26%   |
| 4.18    | 3         | 2.26%   |
| 5.9     | 2         | 1.5%    |
| 5.17    | 2         | 1.5%    |
| 5.6     | 1         | 0.75%   |
| 5.12    | 1         | 0.75%   |
| 4.4     | 1         | 0.75%   |
| 3.13    | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 120       | 97.56%  |
| i686   | 3         | 2.44%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 71        | 55.04%  |
| Unknown         | 16        | 12.4%   |
| KDE5            | 13        | 10.08%  |
| X-Cinnamon      | 8         | 6.2%    |
| XFCE            | 4         | 3.1%    |
| KDE4            | 4         | 3.1%    |
| Pantheon        | 2         | 1.55%   |
| GNOME Flashback | 2         | 1.55%   |
| Unity           | 1         | 0.78%   |
| MATE            | 1         | 0.78%   |
| LXQt            | 1         | 0.78%   |
| LXDE            | 1         | 0.78%   |
| i3              | 1         | 0.78%   |
| GNOME Classic   | 1         | 0.78%   |
| DWM             | 1         | 0.78%   |
| Deepin          | 1         | 0.78%   |
| Cinnamon        | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 100       | 79.37%  |
| Wayland | 18        | 14.29%  |
| Unknown | 5         | 3.97%   |
| Tty     | 3         | 2.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 55        | 44%     |
| GDM     | 39        | 31.2%   |
| SDDM    | 14        | 11.2%   |
| LightDM | 7         | 5.6%    |
| GDM3    | 6         | 4.8%    |
| KDM     | 4         | 3.2%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 55        | 43.65%  |
| fr_FR   | 39        | 30.95%  |
| Unknown | 19        | 15.08%  |
| en_GB   | 4         | 3.17%   |
| C       | 2         | 1.59%   |
| ar_TN   | 2         | 1.59%   |
| pt_BR   | 1         | 0.79%   |
| en_CA   | 1         | 0.79%   |
| en_AU   | 1         | 0.79%   |
| en_AG   | 1         | 0.79%   |
| de_DE   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 65        | 52%     |
| BIOS | 60        | 48%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 106       | 85.48%  |
| Overlay | 9         | 7.26%   |
| Unknown | 6         | 4.84%   |
| Btrfs   | 2         | 1.61%   |
| Xfs     | 1         | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 64        | 51.2%   |
| GPT     | 42        | 33.6%   |
| MBR     | 19        | 15.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 110       | 88%     |
| Yes       | 15        | 12%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 63.93%  |
| Yes       | 44        | 36.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 31        | 25.41%  |
| Hewlett-Packard     | 21        | 17.21%  |
| ASUSTek Computer    | 21        | 17.21%  |
| Dell                | 16        | 13.11%  |
| Acer                | 8         | 6.56%   |
| MSI                 | 7         | 5.74%   |
| Toshiba             | 5         | 4.1%    |
| Pegatron            | 3         | 2.46%   |
| Samsung Electronics | 2         | 1.64%   |
| Foxconn             | 2         | 1.64%   |
| Sony                | 1         | 0.82%   |
| Packard Bell        | 1         | 0.82%   |
| Intel               | 1         | 0.82%   |
| Gigabyte Technology | 1         | 0.82%   |
| eMachines           | 1         | 0.82%   |
| Unknown             | 1         | 0.82%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 3         | 2.46%   |
| Pegatron VS342AA-AB6 m9801af             | 2         | 1.64%   |
| Lenovo IdeaPad 130-15IKB 81H7            | 2         | 1.64%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 1.64%   |
| HP Pavilion g6                           | 2         | 1.64%   |
| Foxconn Pro 3400 Series MT               | 2         | 1.64%   |
| ASUS X556UV                              | 2         | 1.64%   |
| ASUS X550JX                              | 2         | 1.64%   |
| Unknown                                  | 2         | 1.64%   |
| Toshiba Satellite Pro L850-B339          | 1         | 0.82%   |
| Toshiba Satellite L550                   | 1         | 0.82%   |
| Toshiba Satellite L500                   | 1         | 0.82%   |
| Toshiba Satellite C50-A489               | 1         | 0.82%   |
| Toshiba Satellite A300                   | 1         | 0.82%   |
| Sony VPCEH36EF                           | 1         | 0.82%   |
| Samsung 530U3BI/530U4BI/530U4BH          | 1         | 0.82%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 0.82%   |
| Pegatron Pro 3010 Microtower PC          | 1         | 0.82%   |
| Packard Bell EasyNote ML65               | 1         | 0.82%   |
| MSI MS-7C95                              | 1         | 0.82%   |
| MSI MS-7A15                              | 1         | 0.82%   |
| MSI MS-7817                              | 1         | 0.82%   |
| MSI MS-7502                              | 1         | 0.82%   |
| MSI Katana GF66 12UC                     | 1         | 0.82%   |
| MSI GF65 Thin 10UE                       | 1         | 0.82%   |
| MSI GF63 Thin 10SCXR                     | 1         | 0.82%   |
| Lenovo V310-15ISK 80SY                   | 1         | 0.82%   |
| Lenovo V15-IIL 82C5                      | 1         | 0.82%   |
| Lenovo ThinkStation P330 30C6S33L00      | 1         | 0.82%   |
| Lenovo ThinkPad X240 20AMA0WRFR          | 1         | 0.82%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 0.82%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100 | 1         | 0.82%   |
| Lenovo ThinkPad T440s 20AQ005NUS         | 1         | 0.82%   |
| Lenovo ThinkPad E15 20RD001SFE           | 1         | 0.82%   |
| Lenovo ThinkPad E15 20RD001QFE           | 1         | 0.82%   |
| Lenovo ThinkPad E14 20RA000KFE           | 1         | 0.82%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 0.82%   |
| Lenovo IdeaPad S145-15AST 81N3           | 1         | 0.82%   |
| Lenovo IdeaPad L3 15IML05 81Y3           | 1         | 0.82%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 0.82%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 0.82%   |
| Lenovo IdeaPad 700-15ISK 80RU            | 1         | 0.82%   |
| Lenovo IdeaPad 330S-14AST 81F8           | 1         | 0.82%   |
| Lenovo IdeaPad 330-15AST 81D6            | 1         | 0.82%   |
| Lenovo IdeaPad 320-15IKB 81BT            | 1         | 0.82%   |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 0.82%   |
| Lenovo IdeaPad 100-15IBD 80QQ            | 1         | 0.82%   |
| Lenovo IdeaCentre 510-15IKL 90G8008EAL   | 1         | 0.82%   |
| Lenovo H50-50 90B70040AL                 | 1         | 0.82%   |
| Lenovo G580 20157                        | 1         | 0.82%   |
| Lenovo G50-70 20351                      | 1         | 0.82%   |
| Intel H61                                | 1         | 0.82%   |
| HP ProBook 455 G3                        | 1         | 0.82%   |
| HP ProBook 440 G7                        | 1         | 0.82%   |
| HP Pavilion Gaming Laptop 15-ec0xxx      | 1         | 0.82%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 0.82%   |
| HP Pavilion dv7                          | 1         | 0.82%   |
| HP Pavilion dv6                          | 1         | 0.82%   |
| HP Notebook                              | 1         | 0.82%   |
| HP Laptop 17-ak0xx                       | 1         | 0.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 16        | 13.11%  |
| HP Pavilion           | 8         | 6.56%   |
| Lenovo ThinkPad       | 7         | 5.74%   |
| Dell Inspiron         | 7         | 5.74%   |
| Dell Latitude         | 6         | 4.92%   |
| Toshiba Satellite     | 5         | 4.1%    |
| Acer Aspire           | 5         | 4.1%    |
| ASUS TUF              | 4         | 3.28%   |
| HP Laptop             | 3         | 2.46%   |
| Dell OptiPlex         | 3         | 2.46%   |
| Pegatron VS342AA-AB6  | 2         | 1.64%   |
| HP ProBook            | 2         | 1.64%   |
| HP Compaq             | 2         | 1.64%   |
| HP 250                | 2         | 1.64%   |
| Foxconn Pro           | 2         | 1.64%   |
| ASUS X556UV           | 2         | 1.64%   |
| ASUS X550JX           | 2         | 1.64%   |
| ASUS VivoBook         | 2         | 1.64%   |
| ASUS ASUS             | 2         | 1.64%   |
| Acer Swift            | 2         | 1.64%   |
| Unknown               | 2         | 1.64%   |
| Sony VPCEH36EF        | 1         | 0.82%   |
| Samsung 530U3BI       | 1         | 0.82%   |
| Samsung 300E5EV       | 1         | 0.82%   |
| Pegatron Pro          | 1         | 0.82%   |
| Packard Bell EasyNote | 1         | 0.82%   |
| MSI MS-7C95           | 1         | 0.82%   |
| MSI MS-7A15           | 1         | 0.82%   |
| MSI MS-7817           | 1         | 0.82%   |
| MSI MS-7502           | 1         | 0.82%   |
| MSI Katana            | 1         | 0.82%   |
| MSI GF65              | 1         | 0.82%   |
| MSI GF63              | 1         | 0.82%   |
| Lenovo V310-15ISK     | 1         | 0.82%   |
| Lenovo V15-IIL        | 1         | 0.82%   |
| Lenovo ThinkStation   | 1         | 0.82%   |
| Lenovo IdeaCentre     | 1         | 0.82%   |
| Lenovo H50-50         | 1         | 0.82%   |
| Lenovo G580           | 1         | 0.82%   |
| Lenovo G50-70         | 1         | 0.82%   |
| Intel H61             | 1         | 0.82%   |
| HP Notebook           | 1         | 0.82%   |
| HP EliteBook          | 1         | 0.82%   |
| HP Convertible        | 1         | 0.82%   |
| HP 630                | 1         | 0.82%   |
| Gigabyte B75M-D3H     | 1         | 0.82%   |
| eMachines E725        | 1         | 0.82%   |
| ASUS X555LD           | 1         | 0.82%   |
| ASUS X553MA           | 1         | 0.82%   |
| ASUS X550VX           | 1         | 0.82%   |
| ASUS X550LC           | 1         | 0.82%   |
| ASUS UX360CA          | 1         | 0.82%   |
| ASUS UX310UQK         | 1         | 0.82%   |
| ASUS ROG              | 1         | 0.82%   |
| ASUS PRIME            | 1         | 0.82%   |
| ASUS M32CD            | 1         | 0.82%   |
| Acer TravelMate       | 1         | 0.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 17        | 13.93%  |
| 2020 | 12        | 9.84%   |
| 2018 | 12        | 9.84%   |
| 2017 | 11        | 9.02%   |
| 2011 | 11        | 9.02%   |
| 2016 | 10        | 8.2%    |
| 2013 | 10        | 8.2%    |
| 2015 | 9         | 7.38%   |
| 2012 | 7         | 5.74%   |
| 2009 | 6         | 4.92%   |
| 2021 | 5         | 4.1%    |
| 2008 | 5         | 4.1%    |
| 2014 | 4         | 3.28%   |
| 2010 | 2         | 1.64%   |
| 2007 | 1         | 0.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 100       | 81.97%  |
| Desktop     | 21        | 17.21%  |
| Convertible | 1         | 0.82%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 114       | 93.44%  |
| Enabled  | 8         | 6.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 122       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 45        | 36.59%  |
| 3.01-4.0   | 26        | 21.14%  |
| 16.01-24.0 | 21        | 17.07%  |
| 8.01-16.0  | 20        | 16.26%  |
| 1.01-2.0   | 6         | 4.88%   |
| 32.01-64.0 | 4         | 3.25%   |
| 2.01-3.0   | 1         | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 44        | 32.59%  |
| 2.01-3.0  | 41        | 30.37%  |
| 4.01-8.0  | 21        | 15.56%  |
| 3.01-4.0  | 17        | 12.59%  |
| 0.51-1.0  | 5         | 3.7%    |
| 8.01-16.0 | 3         | 2.22%   |
| 0.01-0.5  | 3         | 2.22%   |
| Unknown   | 1         | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 91        | 72.8%   |
| 2      | 32        | 25.6%   |
| 4      | 1         | 0.8%    |
| 0      | 1         | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 50.41%  |
| No        | 61        | 49.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 90.16%  |
| No        | 12        | 9.84%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 91.06%  |
| No        | 11        | 8.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 76%     |
| No        | 30        | 24%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Tunisia | 122       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Tunis              | 73        | 53.28%  |
| Aryanah            | 7         | 5.11%   |
| Sousse             | 6         | 4.38%   |
| Nabeul             | 5         | 3.65%   |
| Bizerte            | 5         | 3.65%   |
| Monastir           | 3         | 2.19%   |
| Centre Urbain Nord | 3         | 2.19%   |
| Rades              | 2         | 1.46%   |
| Mateur             | 2         | 1.46%   |
| Masakin            | 2         | 1.46%   |
| Mahdia             | 2         | 1.46%   |
| Zarzis             | 1         | 0.73%   |
| Zaouiat Djedidi    | 1         | 0.73%   |
| Wadi Maliz         | 1         | 0.73%   |
| Tebourba           | 1         | 0.73%   |
| Tataouine          | 1         | 0.73%   |
| Sfax               | 1         | 0.73%   |
| Rafraf             | 1         | 0.73%   |
| Oued Lill          | 1         | 0.73%   |
| Manouba            | 1         | 0.73%   |
| La Goulette        | 1         | 0.73%   |
| Jendouba           | 1         | 0.73%   |
| Jedeida            | 1         | 0.73%   |
| Houmt Souk         | 1         | 0.73%   |
| Hergla             | 1         | 0.73%   |
| Hammamet           | 1         | 0.73%   |
| Gremda             | 1         | 0.73%   |
| Gafsa              | 1         | 0.73%   |
| El Fahs            | 1         | 0.73%   |
| El Battan          | 1         | 0.73%   |
| Carthage           | 1         | 0.73%   |
| Borj el Amri       | 1         | 0.73%   |
| Ben Arous          | 1         | 0.73%   |
| Belvedere          | 1         | 0.73%   |
| Bellevue           | 1         | 0.73%   |
| Beja               | 1         | 0.73%   |
| As Sanad           | 1         | 0.73%   |
| Akouda             | 1         | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 33        | 42     | 22%     |
| WDC                   | 30        | 39     | 20%     |
| Toshiba               | 17        | 19     | 11.33%  |
| Samsung Electronics   | 11        | 12     | 7.33%   |
| Team                  | 10        | 12     | 6.67%   |
| SK hynix              | 8         | 9      | 5.33%   |
| SanDisk               | 6         | 7      | 4%      |
| HGST                  | 6         | 7      | 4%      |
| Kingston              | 4         | 5      | 2.67%   |
| Hitachi               | 4         | 4      | 2.67%   |
| Unknown               | 3         | 3      | 2%      |
| Fujitsu               | 3         | 3      | 2%      |
| PNY                   | 2         | 2      | 1.33%   |
| Micron Technology     | 2         | 2      | 1.33%   |
| Intel                 | 2         | 2      | 1.33%   |
| UMIS                  | 1         | 1      | 0.67%   |
| TwinMOS               | 1         | 1      | 0.67%   |
| Realtek Semiconductor | 1         | 1      | 0.67%   |
| Phison                | 1         | 1      | 0.67%   |
| Patriot               | 1         | 1      | 0.67%   |
| OCZ                   | 1         | 1      | 0.67%   |
| EMTEC                 | 1         | 3      | 0.67%   |
| addlink               | 1         | 1      | 0.67%   |
| A-DATA Technology     | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 8         | 5.16%   |
| Seagate ST500LT012-1DG142 500GB      | 6         | 3.87%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 3         | 1.94%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.94%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 1.94%   |
| HGST HTS545050A7E380 500GB           | 3         | 1.94%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 1.29%   |
| WDC WD20SPZX-08UA7 2TB               | 2         | 1.29%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 1.29%   |
| WDC WD10SPCX-24HWST1 1TB             | 2         | 1.29%   |
| WDC WD10EADS-65M2B0 1TB              | 2         | 1.29%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 2         | 1.29%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.29%   |
| Toshiba MK5076GSX 500GB              | 2         | 1.29%   |
| Team T253X2512G 512GB SSD            | 2         | 1.29%   |
| SK hynix SC311 SATA 256GB SSD        | 2         | 1.29%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 1.29%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 1.29%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 1.29%   |
| SanDisk NVMe SSD Drive 512GB         | 2         | 1.29%   |
| Kingston NVMe SSD Drive 512GB        | 2         | 1.29%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 1.29%   |
| Fujitsu MHV2100BH PL 100GB           | 2         | 1.29%   |
| WDC WD5000LPZX-60Z10T0 500GB         | 1         | 0.65%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPLX-60ZNTT2 500GB         | 1         | 0.65%   |
| WDC WD5000BPVT-55HXZT3 500GB         | 1         | 0.65%   |
| WDC WD5000AVDS-63U7B1 500GB          | 1         | 0.65%   |
| WDC WD5000AAKS-402AA0 500GB          | 1         | 0.65%   |
| WDC WD5000AACS-00ZUB0 500GB          | 1         | 0.65%   |
| WDC WD3200BEKT-60KA9T0 320GB         | 1         | 0.65%   |
| WDC WD3200AAJS-60M0A1 320GB          | 1         | 0.65%   |
| WDC WD2500BPVT-75JJ5T0 250GB         | 1         | 0.65%   |
| WDC WD2500AAJS-75M0A0 250GB          | 1         | 0.65%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.65%   |
| WDC WD10PURZ-85U8XY0 1TB             | 1         | 0.65%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1         | 0.65%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.65%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB | 1         | 0.65%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.65%   |
| Unknown xD/SD/M.S.                   | 1         | 0.65%   |
| Unknown SS16G  16GB                  | 1         | 0.65%   |
| Unknown 00000  64GB                  | 1         | 0.65%   |
| UMIS RPJTJ512MEE1OWX 512GB           | 1         | 0.65%   |
| TwinMOS SSD 512GB                    | 1         | 0.65%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.65%   |
| Toshiba MQ01ABD050 500GB             | 1         | 0.65%   |
| Toshiba MQ01ABD032 320GB             | 1         | 0.65%   |
| Toshiba MK7575GSX 752GB              | 1         | 0.65%   |
| Toshiba MK4055GSX 400GB              | 1         | 0.65%   |
| Toshiba MK3275GSX 320GB              | 1         | 0.65%   |
| Toshiba MK1646GSX 160GB              | 1         | 0.65%   |
| Toshiba MK1032GSX 100GB              | 1         | 0.65%   |
| Toshiba DT01ACA100 1TB               | 1         | 0.65%   |
| Toshiba DT01ACA050 500GB             | 1         | 0.65%   |
| Team TM8FP6512G 512GB                | 1         | 0.65%   |
| Team TM8FP6256G 256GB                | 1         | 0.65%   |
| Team TM8FP6128G 128GB                | 1         | 0.65%   |
| Team TM8FP4256G 256GB                | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 33        | 42     | 37.08%  |
| WDC     | 26        | 34     | 29.21%  |
| Toshiba | 17        | 19     | 19.1%   |
| HGST    | 6         | 7      | 6.74%   |
| Hitachi | 4         | 4      | 4.49%   |
| Fujitsu | 3         | 3      | 3.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 6         | 8      | 21.43%  |
| SK hynix            | 5         | 5      | 17.86%  |
| Samsung Electronics | 5         | 6      | 17.86%  |
| SanDisk             | 3         | 3      | 10.71%  |
| PNY                 | 2         | 2      | 7.14%   |
| TwinMOS             | 1         | 1      | 3.57%   |
| Patriot             | 1         | 1      | 3.57%   |
| OCZ                 | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 1      | 3.57%   |
| Kingston            | 1         | 1      | 3.57%   |
| EMTEC               | 1         | 3      | 3.57%   |
| addlink             | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 87        | 109    | 60%     |
| SSD     | 28        | 33     | 19.31%  |
| NVMe    | 27        | 34     | 18.62%  |
| MMC     | 2         | 2      | 1.38%   |
| Unknown | 1         | 1      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 105       | 142    | 77.78%  |
| NVMe | 27        | 34     | 20%     |
| MMC  | 2         | 2      | 1.48%   |
| SAS  | 1         | 1      | 0.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 82     | 61.61%  |
| 0.51-1.0   | 38        | 54     | 33.93%  |
| 1.01-2.0   | 5         | 6      | 4.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 40        | 31.25%  |
| 251-500    | 39        | 30.47%  |
| 501-1000   | 19        | 14.84%  |
| 1001-2000  | 11        | 8.59%   |
| 51-100     | 7         | 5.47%   |
| 1-20       | 6         | 4.69%   |
| 21-50      | 4         | 3.13%   |
| Unknown    | 2         | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 53        | 39.85%  |
| 21-50     | 23        | 17.29%  |
| 101-250   | 23        | 17.29%  |
| 51-100    | 19        | 14.29%  |
| 251-500   | 6         | 4.51%   |
| 501-1000  | 5         | 3.76%   |
| 1001-2000 | 2         | 1.5%    |
| Unknown   | 2         | 1.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E380 500GB                          | 2         | 3      | 13.33%  |
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 6.67%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 6.67%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 6.67%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 6.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 6.67%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 6.67%   |
| Seagate ST3320813AS 320GB                           | 1         | 1      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 6.67%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 6.67%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 6.67%   |
| EMTEC X250 512GB SSD                                | 1         | 2      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 4         | 5      | 26.67%  |
| Seagate           | 4         | 4      | 26.67%  |
| Hitachi           | 2         | 2      | 13.33%  |
| HGST              | 2         | 3      | 13.33%  |
| WDC               | 1         | 2      | 6.67%   |
| Micron Technology | 1         | 1      | 6.67%   |
| EMTEC             | 1         | 2      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 5      | 30.77%  |
| Seagate | 4         | 4      | 30.77%  |
| Hitachi | 2         | 2      | 15.38%  |
| HGST    | 2         | 3      | 15.38%  |
| WDC     | 1         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 16     | 86.67%  |
| SSD  | 2         | 3      | 13.33%  |

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
| Detected | 61        | 85     | 46.92%  |
| Works    | 53        | 74     | 40.77%  |
| Malfunc  | 15        | 19     | 11.54%  |
| Failed   | 1         | 1      | 0.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 105       | 72.41%  |
| AMD                          | 13        | 8.97%   |
| SanDisk                      | 6         | 4.14%   |
| Samsung Electronics          | 6         | 4.14%   |
| SK hynix                     | 3         | 2.07%   |
| Phison Electronics           | 3         | 2.07%   |
| Kingston Technology Company  | 3         | 2.07%   |
| Realtek Semiconductor        | 2         | 1.38%   |
| Union Memory (Shenzhen)      | 1         | 0.69%   |
| Silicon Motion               | 1         | 0.69%   |
| Shenzhen Longsys Electronics | 1         | 0.69%   |
| Micron Technology            | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 8.44%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 7.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 6.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 4.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 4.55%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 3.9%    |
| Samsung NVMe SSD Controller 980                                                         | 5         | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 3.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 2.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 2.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 2.6%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3         | 1.95%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 1.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 1.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.95%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.95%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.95%   |
| SK hynix BC511                                                                          | 2         | 1.3%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 1.3%    |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2         | 1.3%    |
| Phison E12 NVMe Controller                                                              | 2         | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.3%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.3%    |
| Intel SSD 660P Series                                                                   | 2         | 1.3%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.3%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.65%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1         | 0.65%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.65%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.65%   |
| Micron Non-Volatile memory controller                                                   | 1         | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.65%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 1         | 0.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1         | 0.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 1         | 0.65%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1         | 0.65%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1         | 0.65%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1         | 0.65%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1         | 0.65%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 1         | 0.65%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 1         | 0.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 0.65%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1         | 0.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 95        | 65.52%  |
| NVMe | 27        | 18.62%  |
| RAID | 12        | 8.28%   |
| IDE  | 11        | 7.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 107       | 87.7%   |
| AMD    | 15        | 12.3%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 3.28%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 2.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.46%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 2.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.46%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 2.46%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 1.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.64%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.64%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.64%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.64%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.64%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.64%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.64%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 2         | 1.64%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 1.64%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.64%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.64%   |
| Intel Xeon E-2144G CPU @ 3.60GHz              | 1         | 0.82%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.82%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 0.82%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.82%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.82%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.82%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 1         | 0.82%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.82%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 1         | 0.82%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.82%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.82%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.82%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz            | 1         | 0.82%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.82%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.82%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1         | 0.82%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.82%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.82%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.82%   |
| Intel Core i5-6198DU CPU @ 2.30GHz            | 1         | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.82%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.82%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 0.82%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.82%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 0.82%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 1         | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1         | 0.82%   |
| Intel Core i5-10310U CPU @ 1.70GHz            | 1         | 0.82%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 0.82%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 28.69%  |
| Intel Core i7           | 24        | 19.67%  |
| Intel Core i3           | 21        | 17.21%  |
| Intel Pentium           | 9         | 7.38%   |
| AMD Ryzen 5             | 8         | 6.56%   |
| Other                   | 4         | 3.28%   |
| Intel Core 2 Duo        | 4         | 3.28%   |
| Intel Core 2 Quad       | 3         | 2.46%   |
| Intel Celeron           | 3         | 2.46%   |
| Intel Pentium Dual-Core | 2         | 1.64%   |
| Intel Xeon              | 1         | 0.82%   |
| Intel Core m3           | 1         | 0.82%   |
| Intel Atom              | 1         | 0.82%   |
| AMD Sempron             | 1         | 0.82%   |
| AMD Ryzen 7             | 1         | 0.82%   |
| AMD E2                  | 1         | 0.82%   |
| AMD A8                  | 1         | 0.82%   |
| AMD A6                  | 1         | 0.82%   |
| AMD A4                  | 1         | 0.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 64        | 52.46%  |
| 4       | 43        | 35.25%  |
| 6       | 9         | 7.38%   |
| 8       | 2         | 1.64%   |
| 1       | 2         | 1.64%   |
| 14      | 1         | 0.82%   |
| Unknown | 1         | 0.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 122       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 95        | 77.24%  |
| 1       | 27        | 21.95%  |
| Unknown | 1         | 0.81%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 121       | 99.18%  |
| Unknown        | 1         | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 19.2%   |
| 0x206a7    | 11        | 8.8%    |
| 0x40651    | 7         | 5.6%    |
| 0x306a9    | 7         | 5.6%    |
| 0x806ec    | 6         | 4.8%    |
| 0x806ea    | 6         | 4.8%    |
| 0x1067a    | 6         | 4.8%    |
| 0x906ea    | 5         | 4%      |
| 0x506e3    | 5         | 4%      |
| 0x406e3    | 5         | 4%      |
| 0xa0652    | 3         | 2.4%    |
| 0x706e5    | 3         | 2.4%    |
| 0x306c3    | 3         | 2.4%    |
| 0x20655    | 3         | 2.4%    |
| 0x806e9    | 2         | 1.6%    |
| 0x806c1    | 2         | 1.6%    |
| 0x406c4    | 2         | 1.6%    |
| 0x306d4    | 2         | 1.6%    |
| 0x08108102 | 2         | 1.6%    |
| 0x06006705 | 2         | 1.6%    |
| 0x06006704 | 2         | 1.6%    |
| 0xa0653    | 1         | 0.8%    |
| 0x906e9    | 1         | 0.8%    |
| 0x906a3    | 1         | 0.8%    |
| 0x6fd      | 1         | 0.8%    |
| 0x6fb      | 1         | 0.8%    |
| 0x506c9    | 1         | 0.8%    |
| 0x40661    | 1         | 0.8%    |
| 0x30678    | 1         | 0.8%    |
| 0x20652    | 1         | 0.8%    |
| 0x106ca    | 1         | 0.8%    |
| 0x0a50000c | 1         | 0.8%    |
| 0x08701013 | 1         | 0.8%    |
| 0x08600106 | 1         | 0.8%    |
| 0x08600104 | 1         | 0.8%    |
| 0x08108109 | 1         | 0.8%    |
| 0x02000032 | 1         | 0.8%    |
| 0x00000000 | 1         | 0.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 27        | 22.13%  |
| SandyBridge     | 13        | 10.66%  |
| Haswell         | 13        | 10.66%  |
| Skylake         | 11        | 9.02%   |
| Penryn          | 7         | 5.74%   |
| IvyBridge       | 7         | 5.74%   |
| Westmere        | 5         | 4.1%    |
| IceLake         | 5         | 4.1%    |
| CometLake       | 5         | 4.1%    |
| Zen 2           | 4         | 3.28%   |
| Silvermont      | 4         | 3.28%   |
| Excavator       | 4         | 3.28%   |
| Zen+            | 3         | 2.46%   |
| Broadwell       | 3         | 2.46%   |
| Zen 3           | 2         | 1.64%   |
| TigerLake       | 2         | 1.64%   |
| Core            | 2         | 1.64%   |
| Puma            | 1         | 0.82%   |
| K8 & K10 hybrid | 1         | 0.82%   |
| Goldmont        | 1         | 0.82%   |
| Bonnell         | 1         | 0.82%   |
| Unknown         | 1         | 0.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 94        | 53.71%  |
| Nvidia | 49        | 28%     |
| AMD    | 32        | 18.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 5.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 4.52%   |
| Intel UHD Graphics 620                                                                   | 6         | 3.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 3.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.39%   |
| Intel HD Graphics 620                                                                    | 5         | 2.82%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 2.26%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 2.26%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 2.26%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 2.26%   |
| Intel HD Graphics 530                                                                    | 4         | 2.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 2.26%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.69%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.69%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.69%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.69%   |
| AMD Renoir                                                                               | 3         | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.69%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.69%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.13%   |
| Nvidia TU117M                                                                            | 2         | 1.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.13%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 1.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.13%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.13%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.56%   |
| Nvidia GT218M [GeForce G 105M]                                                           | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.56%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.56%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.56%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 0.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.56%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.56%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1         | 0.56%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.56%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.56%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.56%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.56%   |
| Intel HD Graphics 610                                                                    | 1         | 0.56%   |
| Intel HD Graphics 520                                                                    | 1         | 0.56%   |
| Intel HD Graphics 515                                                                    | 1         | 0.56%   |
| Intel HD Graphics 510                                                                    | 1         | 0.56%   |
| Intel HD Graphics 500                                                                    | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 38.52%  |
| Intel + Nvidia | 32        | 26.23%  |
| Intel + AMD    | 13        | 10.66%  |
| 1 x Nvidia     | 11        | 9.02%   |
| 1 x AMD        | 11        | 9.02%   |
| AMD + Nvidia   | 6         | 4.92%   |
| 2 x AMD        | 2         | 1.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 96        | 76.19%  |
| Proprietary | 25        | 19.84%  |
| Unknown     | 5         | 3.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 54.4%   |
| 1.01-2.0   | 20        | 16%     |
| 3.01-4.0   | 12        | 9.6%    |
| 0.01-0.5   | 11        | 8.8%    |
| 0.51-1.0   | 10        | 8%      |
| 5.01-6.0   | 2         | 1.6%    |
| 2.01-3.0   | 2         | 1.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 19.85%  |
| Samsung Electronics     | 24        | 17.65%  |
| Chimei Innolux          | 20        | 14.71%  |
| BOE                     | 20        | 14.71%  |
| LG Display              | 14        | 10.29%  |
| Hewlett-Packard         | 9         | 6.62%   |
| Chi Mei Optoelectronics | 3         | 2.21%   |
| PANDA                   | 2         | 1.47%   |
| Packard Bell            | 2         | 1.47%   |
| Lenovo                  | 2         | 1.47%   |
| Dell                    | 2         | 1.47%   |
| BenQ                    | 2         | 1.47%   |
| S2-Tek                  | 1         | 0.74%   |
| PKB                     | 1         | 0.74%   |
| Philips                 | 1         | 0.74%   |
| Medion                  | 1         | 0.74%   |
| LG Philips              | 1         | 0.74%   |
| ITE                     | 1         | 0.74%   |
| Goldstar                | 1         | 0.74%   |
| GDH                     | 1         | 0.74%   |
| Acer                    | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 4         | 2.9%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 4         | 2.9%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 3         | 2.17%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 2.17%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 3         | 2.17%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 2         | 1.45%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch | 2         | 1.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 1.45%   |
| Hewlett-Packard x20LED HWP2910 1600x900 443x249mm 20.0-inch          | 2         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 2         | 1.45%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 1.45%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM0284 1280x1024 338x270mm 17.0-inch | 1         | 0.72%   |
| Samsung Electronics SMB2240 SAM06AD 1920x1080 477x268mm 21.5-inch    | 1         | 0.72%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch | 1         | 0.72%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch     | 1         | 0.72%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 340x190mm 15.3-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch | 1         | 0.72%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 0.72%   |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                      | 1         | 0.72%   |
| PKB LCD Monitor VIS220WS 1680x1050                                   | 1         | 0.72%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1         | 0.72%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 0.72%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 1         | 0.72%   |
| Packard Bell PKB VIS220WS PKB5064 1680x1050 460x290mm 21.4-inch      | 1         | 0.72%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch     | 1         | 0.72%   |
| Medion MD30422PV MED86F6 1680x1050 474x296mm 22.0-inch               | 1         | 0.72%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch          | 1         | 0.72%   |
| LG Display LP156WH2-TLR1 LGD0221 1366x768 340x190mm 15.3-inch        | 1         | 0.72%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 1         | 0.72%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 1         | 0.72%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 1         | 0.72%   |
| Lenovo T24v-10 LEN61BC 1920x1080 527x296mm 23.8-inch                 | 1         | 0.72%   |
| Lenovo LEN G27c-10 LEN66A3 1920x1080 597x336mm 27.0-inch             | 1         | 0.72%   |
| ITE DP2VGA V168 ITE6512 1680x1050 600x340mm 27.2-inch                | 1         | 0.72%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch          | 1         | 0.72%   |
| Hewlett-Packard P224 HPN361E 1920x1080 527x296mm 23.8-inch           | 1         | 0.72%   |
| Hewlett-Packard LE2001w HWP2841 1600x900 440x250mm 19.9-inch         | 1         | 0.72%   |
| Hewlett-Packard LCD Monitor 2011 1600x900                            | 1         | 0.72%   |
| Hewlett-Packard 24o HPN337C 1920x1080 531x299mm 24.0-inch            | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 55        | 43.65%  |
| 1366x768 (WXGA)    | 48        | 38.1%   |
| 1600x900 (HD+)     | 11        | 8.73%   |
| 3840x2160 (4K)     | 3         | 2.38%   |
| 1680x1050 (WSXGA+) | 3         | 2.38%   |
| 1280x800 (WXGA)    | 2         | 1.59%   |
| 1280x1024 (SXGA)   | 2         | 1.59%   |
| 1440x900 (WXGA+)   | 1         | 0.79%   |
| 1024x600           | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 73        | 53.68%  |
| 21      | 9         | 6.62%   |
| 17      | 9         | 6.62%   |
| 13      | 7         | 5.15%   |
| 24      | 6         | 4.41%   |
| 20      | 6         | 4.41%   |
| 14      | 6         | 4.41%   |
| 23      | 4         | 2.94%   |
| 27      | 3         | 2.21%   |
| 22      | 2         | 1.47%   |
| 11      | 2         | 1.47%   |
| Unknown | 2         | 1.47%   |
| 52      | 1         | 0.74%   |
| 42      | 1         | 0.74%   |
| 31      | 1         | 0.74%   |
| 19      | 1         | 0.74%   |
| 18      | 1         | 0.74%   |
| 12      | 1         | 0.74%   |
| 10      | 1         | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 63.16%  |
| 401-500     | 18        | 13.53%  |
| 501-600     | 12        | 9.02%   |
| 351-400     | 8         | 6.02%   |
| 201-300     | 6         | 4.51%   |
| Unknown     | 2         | 1.5%    |
| 601-700     | 1         | 0.75%   |
| 1001-1500   | 1         | 0.75%   |
| 901-1000    | 1         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 109       | 90.83%  |
| 16/10   | 7         | 5.83%   |
| 5/4     | 2         | 1.67%   |
| Unknown | 2         | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 73        | 53.68%  |
| 201-250        | 20        | 14.71%  |
| 81-90          | 11        | 8.09%   |
| 151-200        | 8         | 5.88%   |
| 121-130        | 5         | 3.68%   |
| 301-350        | 3         | 2.21%   |
| 141-150        | 3         | 2.21%   |
| 71-80          | 2         | 1.47%   |
| 51-60          | 2         | 1.47%   |
| 131-140        | 2         | 1.47%   |
| Unknown        | 2         | 1.47%   |
| More than 1000 | 1         | 0.74%   |
| 61-70          | 1         | 0.74%   |
| 351-500        | 1         | 0.74%   |
| 41-50          | 1         | 0.74%   |
| 501-1000       | 1         | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 50        | 37.88%  |
| 121-160       | 41        | 31.06%  |
| 51-100        | 34        | 25.76%  |
| 1-50          | 2         | 1.52%   |
| 161-240       | 2         | 1.52%   |
| Unknown       | 2         | 1.52%   |
| More than 240 | 1         | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 99        | 79.84%  |
| 2     | 20        | 16.13%  |
| 0     | 5         | 4.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 91        | 45.5%   |
| Intel                             | 44        | 22%     |
| Qualcomm Atheros                  | 27        | 13.5%   |
| Broadcom                          | 11        | 5.5%    |
| Ralink                            | 6         | 3%      |
| Ralink Technology                 | 5         | 2.5%    |
| Broadcom Limited                  | 5         | 2.5%    |
| D-Link                            | 2         | 1%      |
| Sierra Wireless                   | 1         | 0.5%    |
| Samsung Electronics               | 1         | 0.5%    |
| OPPO Electronics                  | 1         | 0.5%    |
| MediaTek                          | 1         | 0.5%    |
| Marvell Technology Group          | 1         | 0.5%    |
| IMC Networks                      | 1         | 0.5%    |
| ICS Advent                        | 1         | 0.5%    |
| Huawei Technologies               | 1         | 0.5%    |
| Ericsson Business Mobile Networks | 1         | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 27.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 9.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 3.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 3.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.1%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 2.1%    |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 2.1%    |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.26%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.26%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.26%   |
| Intel Wireless 7265                                               | 3         | 1.26%   |
| Intel WiFi Link 5100                                              | 3         | 1.26%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.84%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2         | 0.84%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.84%   |
| Intel Wireless 8260                                               | 2         | 0.84%   |
| Intel Wireless 7260                                               | 2         | 0.84%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.84%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.84%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.84%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 0.84%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.84%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.84%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.84%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.84%   |
| Sierra Wireless EM7455                                            | 1         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.42%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.42%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.42%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.42%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.42%   |
| OPPO SDM720G-IDP _SN:B922E265                                     | 1         | 0.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.42%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.42%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.42%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.42%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 33.06%  |
| Realtek Semiconductor | 27        | 22.31%  |
| Qualcomm Atheros      | 25        | 20.66%  |
| Broadcom              | 8         | 6.61%   |
| Ralink                | 6         | 4.96%   |
| Ralink Technology     | 5         | 4.13%   |
| Broadcom Limited      | 5         | 4.13%   |
| D-Link                | 2         | 1.65%   |
| Sierra Wireless       | 1         | 0.83%   |
| MediaTek              | 1         | 0.83%   |
| IMC Networks          | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 7.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 6.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 4.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 4.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 4.1%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 5         | 4.1%    |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 4.1%    |
| Ralink MT7601U Wireless Adapter                                        | 4         | 3.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 3.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 4         | 3.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 2.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 3         | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 2.46%   |
| Intel Wireless 8265 / 8275                                             | 3         | 2.46%   |
| Intel Wireless 7265                                                    | 3         | 2.46%   |
| Intel WiFi Link 5100                                                   | 3         | 2.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2         | 1.64%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2         | 1.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 1.64%   |
| Intel Wireless 8260                                                    | 2         | 1.64%   |
| Intel Wireless 7260                                                    | 2         | 1.64%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 1.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.64%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                         | 2         | 1.64%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.64%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                              | 2         | 1.64%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 2         | 1.64%   |
| Sierra Wireless EM7455                                                 | 1         | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1         | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1         | 0.82%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter               | 1         | 0.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1         | 0.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 1         | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 1         | 0.82%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                          | 1         | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 1         | 0.82%   |
| Intel Centrino Advanced-N 6200                                         | 1         | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 1         | 0.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 0.82%   |
| IMC Networks AW-NU222 802.11bgn Wireless Module [Ralink RT2770+RT2720] | 1         | 0.82%   |
| Broadcom Limited BCM43142 802.11b/g/n                                  | 1         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 1         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 88        | 77.19%  |
| Intel                    | 15        | 13.16%  |
| Qualcomm Atheros         | 3         | 2.63%   |
| Broadcom                 | 3         | 2.63%   |
| Samsung Electronics      | 1         | 0.88%   |
| OPPO Electronics         | 1         | 0.88%   |
| Marvell Technology Group | 1         | 0.88%   |
| ICS Advent               | 1         | 0.88%   |
| Huawei Technologies      | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 57.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 19.13%  |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.74%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.74%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.87%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.87%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.87%   |
| OPPO SDM720G-IDP _SN:B922E265                                     | 1         | 0.87%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.87%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.87%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.87%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.87%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.87%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.87%   |
| Huawei HUAWEI                                                     | 1         | 0.87%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 50.22%  |
| Ethernet | 110       | 49.33%  |
| Modem    | 1         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 90        | 70.87%  |
| Ethernet | 37        | 29.13%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 95        | 77.24%  |
| 1     | 28        | 22.76%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 122       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 34.74%  |
| Realtek Semiconductor           | 18        | 18.95%  |
| Qualcomm Atheros Communications | 16        | 16.84%  |
| Lite-On Technology              | 7         | 7.37%   |
| Broadcom                        | 5         | 5.26%   |
| IMC Networks                    | 4         | 4.21%   |
| Ralink                          | 3         | 3.16%   |
| Foxconn / Hon Hai               | 3         | 3.16%   |
| Cambridge Silicon Radio         | 2         | 2.11%   |
| Toshiba                         | 1         | 1.05%   |
| Realtek                         | 1         | 1.05%   |
| Hewlett-Packard                 | 1         | 1.05%   |
| Dell                            | 1         | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 13.68%  |
| Realtek Bluetooth Radio                             | 12        | 12.63%  |
| Intel AX201 Bluetooth                               | 11        | 11.58%  |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 9.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 6.32%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.21%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 4.21%   |
| Ralink RT3290 Bluetooth                             | 3         | 3.16%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 3.16%   |
| IMC Networks Bluetooth Radio                        | 3         | 3.16%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 3.16%   |
| Realtek RTL8723B Bluetooth                          | 2         | 2.11%   |
| Lite-On Bluetooth Device                            | 2         | 2.11%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 2.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.11%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 2.11%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 1.05%   |
| Realtek Bluetooth Radio                             | 1         | 1.05%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.05%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.05%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.05%   |
| Intel Bluetooth Device                              | 1         | 1.05%   |
| IMC Networks Wireless_Device                        | 1         | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.05%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.05%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 107       | 67.3%   |
| Nvidia                    | 27        | 16.98%  |
| AMD                       | 21        | 13.21%  |
| Sennheiser Communications | 1         | 0.63%   |
| Lenovo                    | 1         | 0.63%   |
| JMTek                     | 1         | 0.63%   |
| C-Media Electronics       | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 9.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 6.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 5%      |
| Intel 8 Series HD Audio Controller                                                                | 8         | 4.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 3.89%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 3.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 3.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 3.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 2.78%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.78%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 2.22%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.22%   |
| AMD High Definition Audio Controller                                                              | 4         | 2.22%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.22%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.67%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.11%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 1.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.11%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.11%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.11%   |
| Sennheiser Communications Headset [PC 8]                                                          | 1         | 0.56%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia Audio device                                                                               | 1         | 0.56%   |
| Lenovo ThinkVision T24v Wide Monitor for USB-Audio                                                | 1         | 0.56%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.56%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.56%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.56%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 0.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.56%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.56%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 0.56%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 0.56%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 29.47%  |
| SK hynix            | 16        | 16.84%  |
| Micron Technology   | 11        | 11.58%  |
| Team                | 7         | 7.37%   |
| Unknown             | 6         | 6.32%   |
| A-DATA Technology   | 6         | 6.32%   |
| Crucial             | 4         | 4.21%   |
| Elpida              | 3         | 3.16%   |
| Toshiba             | 2         | 2.11%   |
| Ramaxel Technology  | 2         | 2.11%   |
| Nanya Technology    | 2         | 2.11%   |
| Kingston            | 2         | 2.11%   |
| TwinMOS             | 1         | 1.05%   |
| Patriot             | 1         | 1.05%   |
| Hikvision           | 1         | 1.05%   |
| Goodram             | 1         | 1.05%   |
| ASint Technology    | 1         | 1.05%   |
| Unknown             | 1         | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                    | 3         | 2.94%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s             | 2         | 1.96%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s              | 2         | 1.96%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s           | 2         | 1.96%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 1.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 2         | 1.96%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s          | 2         | 1.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 1.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 2         | 1.96%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 2         | 1.96%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 1.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1.96%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s           | 2         | 1.96%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 0.98%   |
| Unknown RAM Module 4GB DIMM DDR3                               | 1         | 0.98%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1         | 0.98%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.98%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                  | 1         | 0.98%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                         | 1         | 0.98%   |
| TwinMOS RAM 9DSDBNZB-5AMP 4GB DIMM DDR3 1333MT/s               | 1         | 0.98%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s             | 1         | 0.98%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 1         | 0.98%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s          | 1         | 0.98%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s                    | 1         | 0.98%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1         | 0.98%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s          | 1         | 0.98%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.98%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s      | 1         | 0.98%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 0.98%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 0.98%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 0.98%   |
| SK hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4 2667MT/s          | 1         | 0.98%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s     | 1         | 0.98%   |
| SK hynix RAM HMA81GS6MFR8N-TF 8192MB SODIMM DDR4 2133MT/s      | 1         | 0.98%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s      | 1         | 0.98%   |
| Samsung RAM Module 4096MB DIMM DDR3 1333MT/s                   | 1         | 0.98%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 1         | 0.98%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 0.98%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 0.98%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 0.98%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s | 1         | 0.98%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 0.98%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s       | 1         | 0.98%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s          | 1         | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s       | 1         | 0.98%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s          | 1         | 0.98%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1         | 0.98%   |
| Samsung RAM K4F8E304HB-MGCj 4GB SODIMM DDR4 2400MT/s           | 1         | 0.98%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 1         | 0.98%   |
| Patriot RAM 3000 C15 Series 8GB DIMM DDR4 3000MT/s             | 1         | 0.98%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 42        | 55.26%  |
| DDR3    | 23        | 30.26%  |
| DDR2    | 4         | 5.26%   |
| SDRAM   | 3         | 3.95%   |
| LPDDR4  | 2         | 2.63%   |
| LPDDR3  | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 80%     |
| DIMM         | 11        | 14.67%  |
| Row Of Chips | 3         | 4%      |
| Chip         | 1         | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 34        | 38.64%  |
| 8192  | 26        | 29.55%  |
| 2048  | 12        | 13.64%  |
| 16384 | 10        | 11.36%  |
| 32768 | 4         | 4.55%   |
| 1024  | 2         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 23        | 26.74%  |
| 3200    | 14        | 16.28%  |
| 1600    | 13        | 15.12%  |
| 1334    | 7         | 8.14%   |
| 2400    | 6         | 6.98%   |
| 1333    | 4         | 4.65%   |
| 2133    | 3         | 3.49%   |
| 4199    | 2         | 2.33%   |
| 3266    | 2         | 2.33%   |
| 1867    | 2         | 2.33%   |
| 1066    | 2         | 2.33%   |
| 667     | 2         | 2.33%   |
| Unknown | 2         | 2.33%   |
| 8400    | 1         | 1.16%   |
| 3000    | 1         | 1.16%   |
| 975     | 1         | 1.16%   |
| 800     | 1         | 1.16%   |

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
| Chicony Electronics                    | 19        | 20.21%  |
| Realtek Semiconductor                  | 15        | 15.96%  |
| IMC Networks                           | 12        | 12.77%  |
| Microdia                               | 7         | 7.45%   |
| Suyin                                  | 6         | 6.38%   |
| Acer                                   | 6         | 6.38%   |
| Syntek                                 | 5         | 5.32%   |
| Lite-On Technology                     | 5         | 5.32%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 5.32%   |
| Sunplus Innovation Technology          | 4         | 4.26%   |
| Quanta                                 | 3         | 3.19%   |
| Luxvisions Innotech Limited            | 2         | 2.13%   |
| Silicon Motion                         | 1         | 1.06%   |
| Ricoh                                  | 1         | 1.06%   |
| Cubeternet                             | 1         | 1.06%   |
| Apple                                  | 1         | 1.06%   |
| Alcor Micro                            | 1         | 1.06%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 5.26%   |
| Chicony Integrated Camera                                                  | 5         | 5.26%   |
| Syntek EasyCamera                                                          | 3         | 3.16%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 3         | 3.16%   |
| Realtek USB Camera                                                         | 3         | 3.16%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 3.16%   |
| Lite-On Integrated Camera                                                  | 3         | 3.16%   |
| IMC Networks Integrated Camera                                             | 3         | 3.16%   |
| Acer Integrated Camera                                                     | 3         | 3.16%   |
| Suyin HP TrueVision HD                                                     | 2         | 2.11%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 2.11%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 2.11%   |
| Quanta HD WebCam                                                           | 2         | 2.11%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 2.11%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 2         | 2.11%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 2.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 2.11%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 2.11%   |
| Chicony HD WebCam                                                          | 2         | 2.11%   |
| Chicony EasyCamera                                                         | 2         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 2         | 2.11%   |
| Syntek Integrated RGB Camera                                               | 1         | 1.05%   |
| Syntek Integrated Camera                                                   | 1         | 1.05%   |
| Suyin USB 2.0 Camera                                                       | 1         | 1.05%   |
| Suyin HP Integrated Webcam                                                 | 1         | 1.05%   |
| Suyin HD WebCam                                                            | 1         | 1.05%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 1         | 1.05%   |
| Sunplus HD User Facing                                                     | 1         | 1.05%   |
| Sunplus Dell HD Webcam                                                     | 1         | 1.05%   |
| Silicon Motion WebCam SC-13HDL11431N                                       | 1         | 1.05%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 1.05%   |
| Realtek Lenovo easy camera                                                 | 1         | 1.05%   |
| Realtek Integrated Webcam_HD                                               | 1         | 1.05%   |
| Realtek Integrated Webcam                                                  | 1         | 1.05%   |
| Realtek HP Webcam                                                          | 1         | 1.05%   |
| Quanta HP Webcam                                                           | 1         | 1.05%   |
| Microdia Webcam SC-10HDD12636P                                             | 1         | 1.05%   |
| Microdia HP Webcam                                                         | 1         | 1.05%   |
| Microdia HP Integrated Webcam                                              | 1         | 1.05%   |
| Lite-On TOSHIBA Web Camera - HD                                            | 1         | 1.05%   |
| Lite-On HP HD Camera                                                       | 1         | 1.05%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.05%   |
| IMC Networks HP TrueVision HD Camera                                       | 1         | 1.05%   |
| Cubeternet WebCam                                                          | 1         | 1.05%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 1.05%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 1.05%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 1.05%   |
| Chicony TOSHIBA Web Camera                                                 | 1         | 1.05%   |
| Chicony Sony Visual Communication Camera                                   | 1         | 1.05%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 1.05%   |
| Chicony HP Webcam                                                          | 1         | 1.05%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 1         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 1.05%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 1.05%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.05%   |
| Acer Integrated IR Camera                                                  | 1         | 1.05%   |
| Acer HD Webcam                                                             | 1         | 1.05%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 50%     |
| LighTuning Technology      | 2         | 25%     |
| Synaptics                  | 1         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor      | 2         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader       | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor     | 1         | 12.5%   |
| Validity Sensors Synaptics WBDI                  | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner             | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device              | 1         | 12.5%   |

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
| 0     | 91        | 67.91%  |
| 1     | 34        | 25.37%  |
| 3     | 4         | 2.99%   |
| 2     | 4         | 2.99%   |
| 4     | 1         | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 16        | 30.19%  |
| Net/wireless             | 11        | 20.75%  |
| Fingerprint reader       | 8         | 15.09%  |
| Bluetooth                | 5         | 9.43%   |
| Communication controller | 3         | 5.66%   |
| Chipcard                 | 3         | 5.66%   |
| Storage                  | 2         | 3.77%   |
| Sound                    | 1         | 1.89%   |
| Network                  | 1         | 1.89%   |
| Net/ethernet             | 1         | 1.89%   |
| Card reader              | 1         | 1.89%   |
| Camera                   | 1         | 1.89%   |

