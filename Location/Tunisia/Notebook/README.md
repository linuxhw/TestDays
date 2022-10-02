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

Total: 160

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 33        | 28.21%  |
| Ubuntu 18.04       | 12        | 10.26%  |
| Ubuntu 21.10       | 5         | 4.27%   |
| Zorin 15           | 3         | 2.56%   |
| Ubuntu 22.04       | 3         | 2.56%   |
| Debian 10          | 3         | 2.56%   |
| Ubuntu 21.04       | 2         | 1.71%   |
| Ubuntu 20.10       | 2         | 1.71%   |
| Ubuntu 16.04       | 2         | 1.71%   |
| Pop!_OS 22.04      | 2         | 1.71%   |
| Pop!_OS 21.04      | 2         | 1.71%   |
| OpenMandriva 4.2   | 2         | 1.71%   |
| Manjaro 21.1.0     | 2         | 1.71%   |
| LMDE 4             | 2         | 1.71%   |
| Linux Mint 20.3    | 2         | 1.71%   |
| Linux Mint 20.2    | 2         | 1.71%   |
| KDE neon 20.04     | 2         | 1.71%   |
| Fedora 35          | 2         | 1.71%   |
| Fedora 33          | 2         | 1.71%   |
| Zorin 16           | 1         | 0.85%   |
| Xubuntu 18.04      | 1         | 0.85%   |
| Ubuntu Unity 16.04 | 1         | 0.85%   |
| Ubuntu 19.10       | 1         | 0.85%   |
| Sodalite 35        | 1         | 0.85%   |
| ROSA R8.1          | 1         | 0.85%   |
| ROSA R11           | 1         | 0.85%   |
| ROSA R10           | 1         | 0.85%   |
| Pop!_OS 20.10      | 1         | 0.85%   |
| OpenMandriva 4.3   | 1         | 0.85%   |
| Manjaro 22.0.0     | 1         | 0.85%   |
| Manjaro 21.3.6     | 1         | 0.85%   |
| Manjaro 20.2       | 1         | 0.85%   |
| Lubuntu 20.04      | 1         | 0.85%   |
| Lubuntu 18.04      | 1         | 0.85%   |
| Linux Mint 20.1    | 1         | 0.85%   |
| Linux Mint 20      | 1         | 0.85%   |
| Kubuntu 20.04      | 1         | 0.85%   |
| Gentoo 2.8         | 1         | 0.85%   |
| Gentoo 2.7         | 1         | 0.85%   |
| Fedora 31          | 1         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 58        | 51.33%  |
| Linux Mint   | 6         | 5.31%   |
| Pop!_OS      | 5         | 4.42%   |
| Manjaro      | 5         | 4.42%   |
| Debian       | 5         | 4.42%   |
| Zorin        | 4         | 3.54%   |
| Fedora       | 4         | 3.54%   |
| ROSA         | 3         | 2.65%   |
| OpenMandriva | 3         | 2.65%   |
| Endless      | 3         | 2.65%   |
| Lubuntu      | 2         | 1.77%   |
| LMDE         | 2         | 1.77%   |
| KDE neon     | 2         | 1.77%   |
| Arch         | 2         | 1.77%   |
| Xubuntu      | 1         | 0.88%   |
| Ubuntu Unity | 1         | 0.88%   |
| Sodalite     | 1         | 0.88%   |
| Kubuntu      | 1         | 0.88%   |
| Gentoo       | 1         | 0.88%   |
| Elementary   | 1         | 0.88%   |
| Deepin       | 1         | 0.88%   |
| BlackPanther | 1         | 0.88%   |
| ArcoLinux    | 1         | 0.88%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.13.0-28-generic        | 4         | 3.23%   |
| 5.3.0-46-generic         | 3         | 2.42%   |
| 5.15.0-46-generic        | 3         | 2.42%   |
| 5.11.0-38-generic        | 3         | 2.42%   |
| 5.8.0-38-generic         | 2         | 1.61%   |
| 5.4.0-72-generic         | 2         | 1.61%   |
| 5.4.0-58-generic         | 2         | 1.61%   |
| 5.4.0-52-generic         | 2         | 1.61%   |
| 5.4.0-42-generic         | 2         | 1.61%   |
| 5.3.0-40-generic         | 2         | 1.61%   |
| 5.3.0-28-generic         | 2         | 1.61%   |
| 5.15.0-43-generic        | 2         | 1.61%   |
| 5.13.0-44-generic        | 2         | 1.61%   |
| 5.13.0-40-generic        | 2         | 1.61%   |
| 5.11.0-7620-generic      | 2         | 1.61%   |
| 5.11.0-40-generic        | 2         | 1.61%   |
| 5.10.14-desktop-1omv4002 | 2         | 1.61%   |
| 5.0.0-25-generic         | 2         | 1.61%   |
| 4.19.0-6-amd64           | 2         | 1.61%   |
| 5.9.9-arch1-1            | 1         | 0.81%   |
| 5.8.15-301.fc33.x86_64   | 1         | 0.81%   |
| 5.8.0-50-generic         | 1         | 0.81%   |
| 5.8.0-44-generic         | 1         | 0.81%   |
| 5.8.0-40-generic         | 1         | 0.81%   |
| 5.8.0-33-generic         | 1         | 0.81%   |
| 5.8.0-32-generic         | 1         | 0.81%   |
| 5.8.0-28-generic         | 1         | 0.81%   |
| 5.8.0-14-generic         | 1         | 0.81%   |
| 5.6.14-desktop-2bP       | 1         | 0.81%   |
| 5.4.80-2-MANJARO         | 1         | 0.81%   |
| 5.4.143-1-pve            | 1         | 0.81%   |
| 5.4.119-1-pve            | 1         | 0.81%   |
| 5.4.0-91-generic         | 1         | 0.81%   |
| 5.4.0-90-generic         | 1         | 0.81%   |
| 5.4.0-84-generic         | 1         | 0.81%   |
| 5.4.0-65-lowlatency      | 1         | 0.81%   |
| 5.4.0-65-generic         | 1         | 0.81%   |
| 5.4.0-56-generic         | 1         | 0.81%   |
| 5.4.0-48-generic         | 1         | 0.81%   |
| 5.4.0-47-generic         | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 17.36%  |
| 5.13.0  | 13        | 10.74%  |
| 5.11.0  | 11        | 9.09%   |
| 5.8.0   | 9         | 7.44%   |
| 5.3.0   | 8         | 6.61%   |
| 5.15.0  | 8         | 6.61%   |
| 4.15.0  | 8         | 6.61%   |
| 5.0.0   | 6         | 4.96%   |
| 4.19.0  | 4         | 3.31%   |
| 5.19.0  | 3         | 2.48%   |
| 5.10.14 | 2         | 1.65%   |
| 4.18.0  | 2         | 1.65%   |
| 5.9.9   | 1         | 0.83%   |
| 5.8.15  | 1         | 0.83%   |
| 5.6.14  | 1         | 0.83%   |
| 5.4.80  | 1         | 0.83%   |
| 5.4.143 | 1         | 0.83%   |
| 5.4.119 | 1         | 0.83%   |
| 5.3.8   | 1         | 0.83%   |
| 5.18.0  | 1         | 0.83%   |
| 5.17.5  | 1         | 0.83%   |
| 5.16.9  | 1         | 0.83%   |
| 5.16.7  | 1         | 0.83%   |
| 5.16.18 | 1         | 0.83%   |
| 5.16.11 | 1         | 0.83%   |
| 5.15.16 | 1         | 0.83%   |
| 5.13.11 | 1         | 0.83%   |
| 5.12.12 | 1         | 0.83%   |
| 5.11.17 | 1         | 0.83%   |
| 5.11.13 | 1         | 0.83%   |
| 5.10.53 | 1         | 0.83%   |
| 5.10.27 | 1         | 0.83%   |
| 5.10.19 | 1         | 0.83%   |
| 5.10.0  | 1         | 0.83%   |
| 4.9.9   | 1         | 0.83%   |
| 4.9.60  | 1         | 0.83%   |
| 4.9.124 | 1         | 0.83%   |
| 3.13.0  | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 19.49%  |
| 5.13    | 14        | 11.86%  |
| 5.11    | 13        | 11.02%  |
| 5.8     | 10        | 8.47%   |
| 5.3     | 9         | 7.63%   |
| 5.15    | 9         | 7.63%   |
| 4.15    | 8         | 6.78%   |
| 5.10    | 6         | 5.08%   |
| 5.0     | 6         | 5.08%   |
| 4.19    | 4         | 3.39%   |
| 5.19    | 3         | 2.54%   |
| 5.16    | 3         | 2.54%   |
| 4.9     | 2         | 1.69%   |
| 4.18    | 2         | 1.69%   |
| 5.9     | 1         | 0.85%   |
| 5.6     | 1         | 0.85%   |
| 5.18    | 1         | 0.85%   |
| 5.17    | 1         | 0.85%   |
| 5.12    | 1         | 0.85%   |
| 3.13    | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 109       | 98.2%   |
| i686   | 2         | 1.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 68        | 59.13%  |
| KDE5            | 11        | 9.57%   |
| Unknown         | 11        | 9.57%   |
| X-Cinnamon      | 7         | 6.09%   |
| XFCE            | 5         | 4.35%   |
| KDE4            | 3         | 2.61%   |
| Pantheon        | 2         | 1.74%   |
| Unity           | 1         | 0.87%   |
| MATE            | 1         | 0.87%   |
| LXQt            | 1         | 0.87%   |
| LXDE            | 1         | 0.87%   |
| GNOME Flashback | 1         | 0.87%   |
| GNOME Classic   | 1         | 0.87%   |
| DWM             | 1         | 0.87%   |
| Deepin          | 1         | 0.87%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 90        | 78.95%  |
| Wayland | 17        | 14.91%  |
| Unknown | 5         | 4.39%   |
| Tty     | 2         | 1.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 40.18%  |
| GDM     | 38        | 33.93%  |
| SDDM    | 10        | 8.93%   |
| LightDM | 8         | 7.14%   |
| GDM3    | 8         | 7.14%   |
| KDM     | 3         | 2.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 55        | 48.67%  |
| fr_FR   | 34        | 30.09%  |
| Unknown | 15        | 13.27%  |
| en_GB   | 4         | 3.54%   |
| C       | 2         | 1.77%   |
| pt_BR   | 1         | 0.88%   |
| en_CA   | 1         | 0.88%   |
| ar_TN   | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 66        | 58.41%  |
| BIOS | 47        | 41.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 100       | 89.29%  |
| Unknown | 5         | 4.46%   |
| Overlay | 4         | 3.57%   |
| Btrfs   | 2         | 1.79%   |
| Xfs     | 1         | 0.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 47.32%  |
| GPT     | 41        | 36.61%  |
| MBR     | 18        | 16.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 102       | 91.07%  |
| Yes       | 10        | 8.93%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 65.45%  |
| Yes       | 38        | 34.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 30        | 27.27%  |
| ASUSTek Computer    | 21        | 19.09%  |
| Hewlett-Packard     | 20        | 18.18%  |
| Dell                | 15        | 13.64%  |
| Acer                | 9         | 8.18%   |
| Toshiba             | 6         | 5.45%   |
| MSI                 | 4         | 3.64%   |
| Samsung Electronics | 2         | 1.82%   |
| Sony                | 1         | 0.91%   |
| Packard Bell        | 1         | 0.91%   |
| eMachines           | 1         | 0.91%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 3         | 2.73%   |
| Lenovo IdeaPad 130-15IKB 81H7            | 2         | 1.82%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 1.82%   |
| HP Pavilion g6                           | 2         | 1.82%   |
| Dell Inspiron 5570                       | 2         | 1.82%   |
| ASUS X556UV                              | 2         | 1.82%   |
| ASUS X550JX                              | 2         | 1.82%   |
| Toshiba Satellite Pro L850-B339          | 1         | 0.91%   |
| Toshiba Satellite L550                   | 1         | 0.91%   |
| Toshiba Satellite L500                   | 1         | 0.91%   |
| Toshiba Satellite C650D                  | 1         | 0.91%   |
| Toshiba Satellite C50-A489               | 1         | 0.91%   |
| Toshiba Satellite A300                   | 1         | 0.91%   |
| Sony VPCEH36EF                           | 1         | 0.91%   |
| Samsung 530U3BI/530U4BI/530U4BH          | 1         | 0.91%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 0.91%   |
| Packard Bell EasyNote ML65               | 1         | 0.91%   |
| MSI Katana GF66 12UC                     | 1         | 0.91%   |
| MSI GF65 Thin 10UE                       | 1         | 0.91%   |
| MSI GF63 Thin 10SCXR                     | 1         | 0.91%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.91%   |
| Lenovo V310-15ISK 80SY                   | 1         | 0.91%   |
| Lenovo V15-IIL 82C5                      | 1         | 0.91%   |
| Lenovo ThinkPad X240 20AMA0WRFR          | 1         | 0.91%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 0.91%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100 | 1         | 0.91%   |
| Lenovo ThinkPad T440s 20AQ005NUS         | 1         | 0.91%   |
| Lenovo ThinkPad E15 20RD001SFE           | 1         | 0.91%   |
| Lenovo ThinkPad E15 20RD001QFE           | 1         | 0.91%   |
| Lenovo ThinkPad E14 20RA000KFE           | 1         | 0.91%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 0.91%   |
| Lenovo IdeaPad S145-15AST 81N3           | 1         | 0.91%   |
| Lenovo IdeaPad L3 15IML05 81Y3           | 1         | 0.91%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 0.91%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 0.91%   |
| Lenovo IdeaPad 700-15ISK 80RU            | 1         | 0.91%   |
| Lenovo IdeaPad 330S-14AST 81F8           | 1         | 0.91%   |
| Lenovo IdeaPad 330-15AST 81D6            | 1         | 0.91%   |
| Lenovo IdeaPad 320-15IKB 81BT            | 1         | 0.91%   |
| Lenovo IdeaPad 320-15IKB 81BG            | 1         | 0.91%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 18        | 16.36%  |
| Dell Inspiron         | 9         | 8.18%   |
| HP Pavilion           | 8         | 7.27%   |
| Lenovo ThinkPad       | 7         | 6.36%   |
| Toshiba Satellite     | 6         | 5.45%   |
| Dell Latitude         | 6         | 5.45%   |
| Acer Aspire           | 6         | 5.45%   |
| HP Laptop             | 4         | 3.64%   |
| ASUS TUF              | 4         | 3.64%   |
| MSI GF63              | 2         | 1.82%   |
| HP ProBook            | 2         | 1.82%   |
| HP 250                | 2         | 1.82%   |
| ASUS X556UV           | 2         | 1.82%   |
| ASUS X550JX           | 2         | 1.82%   |
| ASUS VivoBook         | 2         | 1.82%   |
| ASUS ROG              | 2         | 1.82%   |
| ASUS ASUS             | 2         | 1.82%   |
| Acer Swift            | 2         | 1.82%   |
| Sony VPCEH36EF        | 1         | 0.91%   |
| Samsung 530U3BI       | 1         | 0.91%   |
| Samsung 300E5EV       | 1         | 0.91%   |
| Packard Bell EasyNote | 1         | 0.91%   |
| MSI Katana            | 1         | 0.91%   |
| MSI GF65              | 1         | 0.91%   |
| Lenovo V310-15ISK     | 1         | 0.91%   |
| Lenovo V15-IIL        | 1         | 0.91%   |
| Lenovo G580           | 1         | 0.91%   |
| Lenovo G50-70         | 1         | 0.91%   |
| HP Notebook           | 1         | 0.91%   |
| HP EliteBook          | 1         | 0.91%   |
| HP Compaq             | 1         | 0.91%   |
| HP 630                | 1         | 0.91%   |
| eMachines E725        | 1         | 0.91%   |
| ASUS ZenBook          | 1         | 0.91%   |
| ASUS X555LD           | 1         | 0.91%   |
| ASUS X553MA           | 1         | 0.91%   |
| ASUS X550VX           | 1         | 0.91%   |
| ASUS X550LC           | 1         | 0.91%   |
| ASUS UX360CA          | 1         | 0.91%   |
| ASUS UX310UQK         | 1         | 0.91%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 15        | 13.64%  |
| 2020 | 13        | 11.82%  |
| 2018 | 11        | 10%     |
| 2017 | 11        | 10%     |
| 2013 | 10        | 9.09%   |
| 2015 | 8         | 7.27%   |
| 2016 | 7         | 6.36%   |
| 2011 | 7         | 6.36%   |
| 2021 | 6         | 5.45%   |
| 2014 | 5         | 4.55%   |
| 2012 | 5         | 4.55%   |
| 2008 | 5         | 4.55%   |
| 2010 | 3         | 2.73%   |
| 2009 | 3         | 2.73%   |
| 2022 | 1         | 0.91%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 110       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 101       | 91.82%  |
| Enabled  | 9         | 8.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 44        | 39.64%  |
| 3.01-4.0   | 21        | 18.92%  |
| 16.01-24.0 | 20        | 18.02%  |
| 8.01-16.0  | 19        | 17.12%  |
| 32.01-64.0 | 4         | 3.6%    |
| 2.01-3.0   | 2         | 1.8%    |
| 1.01-2.0   | 1         | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 37        | 30.58%  |
| 1.01-2.0  | 33        | 27.27%  |
| 4.01-8.0  | 24        | 19.83%  |
| 3.01-4.0  | 18        | 14.88%  |
| 0.51-1.0  | 4         | 3.31%   |
| 8.01-16.0 | 3         | 2.48%   |
| 0.01-0.5  | 1         | 0.83%   |
| Unknown   | 1         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 83        | 74.11%  |
| 2      | 29        | 25.89%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 50.45%  |
| Yes       | 55        | 49.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 88.18%  |
| No        | 13        | 11.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 85.84%  |
| No        | 16        | 14.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Tunisia | 110       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Tunis              | 68        | 56.2%   |
| Sousse             | 6         | 4.96%   |
| Nabeul             | 5         | 4.13%   |
| Aryanah            | 5         | 4.13%   |
| Bizerte            | 4         | 3.31%   |
| Centre Urbain Nord | 3         | 2.48%   |
| Rades              | 2         | 1.65%   |
| Monastir           | 2         | 1.65%   |
| Masakin            | 2         | 1.65%   |
| Zarzis             | 1         | 0.83%   |
| Zaouiat Djedidi    | 1         | 0.83%   |
| Wadi Maliz         | 1         | 0.83%   |
| Tebourba           | 1         | 0.83%   |
| Tataouine          | 1         | 0.83%   |
| Sfax               | 1         | 0.83%   |
| Rafraf             | 1         | 0.83%   |
| Oued Lill          | 1         | 0.83%   |
| Mateur             | 1         | 0.83%   |
| Manouba            | 1         | 0.83%   |
| Mahdia             | 1         | 0.83%   |
| Le Bardo           | 1         | 0.83%   |
| La Goulette        | 1         | 0.83%   |
| Jendouba           | 1         | 0.83%   |
| Jedeida            | 1         | 0.83%   |
| Houmt Souk         | 1         | 0.83%   |
| Hergla             | 1         | 0.83%   |
| Gremda             | 1         | 0.83%   |
| Gafsa              | 1         | 0.83%   |
| El Fahs            | 1         | 0.83%   |
| El Battan          | 1         | 0.83%   |
| Borj el Amri       | 1         | 0.83%   |
| Ben Arous          | 1         | 0.83%   |
| Belvedere          | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 28        | 32     | 20.9%   |
| WDC                   | 21        | 28     | 15.67%  |
| Toshiba               | 16        | 18     | 11.94%  |
| Samsung Electronics   | 10        | 11     | 7.46%   |
| Team                  | 9         | 11     | 6.72%   |
| SK hynix              | 9         | 10     | 6.72%   |
| SanDisk               | 5         | 5      | 3.73%   |
| Hitachi               | 5         | 5      | 3.73%   |
| HGST                  | 5         | 6      | 3.73%   |
| Micron Technology     | 4         | 4      | 2.99%   |
| Kingston              | 4         | 6      | 2.99%   |
| Unknown               | 3         | 3      | 2.24%   |
| Intel                 | 3         | 3      | 2.24%   |
| Fujitsu               | 3         | 3      | 2.24%   |
| A-DATA Technology     | 2         | 2      | 1.49%   |
| UMIS                  | 1         | 1      | 0.75%   |
| TwinMOS               | 1         | 1      | 0.75%   |
| Realtek Semiconductor | 1         | 1      | 0.75%   |
| PNY                   | 1         | 1      | 0.75%   |
| Phison                | 1         | 1      | 0.75%   |
| Patriot               | 1         | 1      | 0.75%   |
| OCZ                   | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 10        | 7.35%   |
| Seagate ST500LT012-1DG142 500GB      | 7         | 5.15%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 3         | 2.21%   |
| Toshiba MQ04ABF100 1TB               | 3         | 2.21%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 2.21%   |
| Hitachi HTS545050A7E380 500GB        | 3         | 2.21%   |
| WDC WD20SPZX-08UA7 2TB               | 2         | 1.47%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 1.47%   |
| WDC WD10SPCX-24HWST1 1TB             | 2         | 1.47%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.47%   |
| Toshiba MK5076GSX 500GB              | 2         | 1.47%   |
| Toshiba MK3275GSX 320GB              | 2         | 1.47%   |
| Team T253X2512G 512GB SSD            | 2         | 1.47%   |
| SK hynix SC311 SATA 256GB SSD        | 2         | 1.47%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 1.47%   |
| Kingston NVMe SSD Drive 512GB        | 2         | 1.47%   |
| HGST HTS545050A7E380 500GB           | 2         | 1.47%   |
| Fujitsu MHV2100BH PL 100GB           | 2         | 1.47%   |
| WDC WD5000LPZX-60Z10T0 500GB         | 1         | 0.74%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.74%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.74%   |
| WDC WD5000LPLX-60ZNTT2 500GB         | 1         | 0.74%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.74%   |
| WDC WD5000BPVT-55HXZT3 500GB         | 1         | 0.74%   |
| WDC WD3200BEKT-60KA9T0 320GB         | 1         | 0.74%   |
| WDC WD2500BPVT-75JJ5T0 250GB         | 1         | 0.74%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.74%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.74%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.74%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB | 1         | 0.74%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.74%   |
| Unknown xD/SD/M.S.                   | 1         | 0.74%   |
| Unknown SS16G  16GB                  | 1         | 0.74%   |
| Unknown 00000  64GB                  | 1         | 0.74%   |
| UMIS RPJTJ512MEE1OWX 512GB           | 1         | 0.74%   |
| TwinMOS SSD 512GB                    | 1         | 0.74%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.74%   |
| Toshiba MQ01ABD050 500GB             | 1         | 0.74%   |
| Toshiba MQ01ABD032 320GB             | 1         | 0.74%   |
| Toshiba MK7575GSX 752GB              | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 28        | 32     | 37.33%  |
| WDC     | 18        | 24     | 24%     |
| Toshiba | 16        | 18     | 21.33%  |
| Hitachi | 5         | 5      | 6.67%   |
| HGST    | 5         | 6      | 6.67%   |
| Fujitsu | 3         | 3      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 5         | 7      | 20.83%  |
| SK hynix            | 5         | 5      | 20.83%  |
| Samsung Electronics | 5         | 6      | 20.83%  |
| SanDisk             | 3         | 3      | 12.5%   |
| TwinMOS             | 1         | 1      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| Patriot             | 1         | 1      | 4.17%   |
| OCZ                 | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 74        | 88     | 56.92%  |
| NVMe    | 29        | 36     | 22.31%  |
| SSD     | 24        | 27     | 18.46%  |
| MMC     | 2         | 2      | 1.54%   |
| Unknown | 1         | 1      | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 89        | 115    | 73.55%  |
| NVMe | 29        | 36     | 23.97%  |
| MMC  | 2         | 2      | 1.65%   |
| SAS  | 1         | 1      | 0.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 68     | 61.05%  |
| 0.51-1.0   | 32        | 41     | 33.68%  |
| 1.01-2.0   | 5         | 6      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 37        | 32.17%  |
| 101-250    | 34        | 29.57%  |
| 501-1000   | 16        | 13.91%  |
| 1001-2000  | 11        | 9.57%   |
| 51-100     | 8         | 6.96%   |
| 1-20       | 6         | 5.22%   |
| 21-50      | 2         | 1.74%   |
| Unknown    | 1         | 0.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 43        | 36.44%  |
| 101-250   | 23        | 19.49%  |
| 51-100    | 19        | 16.1%   |
| 21-50     | 18        | 15.25%  |
| 251-500   | 6         | 5.08%   |
| 501-1000  | 6         | 5.08%   |
| 1001-2000 | 2         | 1.69%   |
| Unknown   | 1         | 0.85%   |

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
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 8.33%   |
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
| Seagate           | 3         | 3      | 25%     |
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
| Seagate | 3         | 3      | 27.27%  |
| Hitachi | 2         | 2      | 18.18%  |
| WDC     | 1         | 2      | 9.09%   |
| HGST    | 1         | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 14     | 91.67%  |
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
| Detected | 53        | 71     | 45.3%   |
| Works    | 51        | 67     | 43.59%  |
| Malfunc  | 12        | 15     | 10.26%  |
| Failed   | 1         | 1      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 92        | 69.17%  |
| AMD                          | 12        | 9.02%   |
| SanDisk                      | 5         | 3.76%   |
| Samsung Electronics          | 5         | 3.76%   |
| SK hynix                     | 4         | 3.01%   |
| Kingston Technology Company  | 4         | 3.01%   |
| Phison Electronics           | 3         | 2.26%   |
| Micron Technology            | 3         | 2.26%   |
| Realtek Semiconductor        | 2         | 1.5%    |
| Union Memory (Shenzhen)      | 1         | 0.75%   |
| Silicon Motion               | 1         | 0.75%   |
| Shenzhen Longsys Electronics | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 10.22%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 8.03%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 7.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 5.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 5.11%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 3.65%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 2.92%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 2.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 2.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 2.19%   |
| Micron Non-Volatile memory controller                                            | 3         | 2.19%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.19%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 2.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.19%   |
| SK hynix BC511                                                                   | 2         | 1.46%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 2         | 1.46%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.46%   |
| Intel SSD 660P Series                                                            | 2         | 1.46%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.46%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.73%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.73%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.73%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                 | 1         | 0.73%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.73%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.73%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.73%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 88        | 66.17%  |
| NVMe | 29        | 21.8%   |
| RAID | 14        | 10.53%  |
| IDE  | 2         | 1.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 94        | 85.45%  |
| AMD    | 16        | 14.55%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 4.55%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 3.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 2.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 2.73%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 2.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.73%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 2.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.82%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.82%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.82%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 1.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.82%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.82%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.82%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.82%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.82%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.82%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 1.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.82%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.82%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.91%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.91%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.91%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.91%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.91%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.91%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.91%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz            | 1         | 0.91%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.91%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.91%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.91%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.91%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.91%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.91%   |
| Intel Core i5-6198DU CPU @ 2.30GHz            | 1         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 37        | 33.64%  |
| Intel Core i7           | 24        | 21.82%  |
| Intel Core i3           | 17        | 15.45%  |
| AMD Ryzen 5             | 7         | 6.36%   |
| Other                   | 5         | 4.55%   |
| Intel Pentium           | 4         | 3.64%   |
| Intel Core 2 Duo        | 4         | 3.64%   |
| Intel Celeron           | 2         | 1.82%   |
| AMD Ryzen 7             | 2         | 1.82%   |
| Intel Pentium Dual-Core | 1         | 0.91%   |
| Intel Core m3           | 1         | 0.91%   |
| AMD Sempron             | 1         | 0.91%   |
| AMD E2                  | 1         | 0.91%   |
| AMD E                   | 1         | 0.91%   |
| AMD A8                  | 1         | 0.91%   |
| AMD A6                  | 1         | 0.91%   |
| AMD A4                  | 1         | 0.91%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 57        | 51.82%  |
| 4      | 39        | 35.45%  |
| 6      | 8         | 7.27%   |
| 8      | 4         | 3.64%   |
| 14     | 1         | 0.91%   |
| 1      | 1         | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 110       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 91        | 82.73%  |
| 1      | 19        | 17.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 109       | 99.09%  |
| Unknown        | 1         | 0.91%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 19.64%  |
| 0x806ea    | 8         | 7.14%   |
| 0x40651    | 8         | 7.14%   |
| 0x806ec    | 6         | 5.36%   |
| 0x306a9    | 6         | 5.36%   |
| 0x206a7    | 6         | 5.36%   |
| 0xa0652    | 5         | 4.46%   |
| 0x406e3    | 5         | 4.46%   |
| 0x906ea    | 4         | 3.57%   |
| 0x706e5    | 3         | 2.68%   |
| 0x506e3    | 3         | 2.68%   |
| 0x306d4    | 3         | 2.68%   |
| 0x20655    | 3         | 2.68%   |
| 0x1067a    | 3         | 2.68%   |
| 0x806e9    | 2         | 1.79%   |
| 0x806c1    | 2         | 1.79%   |
| 0x306c3    | 2         | 1.79%   |
| 0x08600106 | 2         | 1.79%   |
| 0x08108109 | 2         | 1.79%   |
| 0x08108102 | 2         | 1.79%   |
| 0x06006705 | 2         | 1.79%   |
| 0x06006704 | 2         | 1.79%   |
| 0x906a3    | 1         | 0.89%   |
| 0x6fd      | 1         | 0.89%   |
| 0x506c9    | 1         | 0.89%   |
| 0x406c4    | 1         | 0.89%   |
| 0x40661    | 1         | 0.89%   |
| 0x30678    | 1         | 0.89%   |
| 0x20652    | 1         | 0.89%   |
| 0x0a50000c | 1         | 0.89%   |
| 0x0a404101 | 1         | 0.89%   |
| 0x08600104 | 1         | 0.89%   |
| 0x02000032 | 1         | 0.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 26        | 23.64%  |
| Haswell         | 12        | 10.91%  |
| Skylake         | 9         | 8.18%   |
| SandyBridge     | 8         | 7.27%   |
| IvyBridge       | 6         | 5.45%   |
| CometLake       | 6         | 5.45%   |
| Westmere        | 5         | 4.55%   |
| IceLake         | 5         | 4.55%   |
| Zen+            | 4         | 3.64%   |
| Penryn          | 4         | 3.64%   |
| Excavator       | 4         | 3.64%   |
| Broadwell       | 4         | 3.64%   |
| Zen 2           | 3         | 2.73%   |
| TigerLake       | 3         | 2.73%   |
| Silvermont      | 3         | 2.73%   |
| Unknown         | 2         | 1.82%   |
| Zen 3           | 1         | 0.91%   |
| Puma            | 1         | 0.91%   |
| K8 & K10 hybrid | 1         | 0.91%   |
| Goldmont        | 1         | 0.91%   |
| Core            | 1         | 0.91%   |
| Bobcat          | 1         | 0.91%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 88        | 53.01%  |
| Nvidia | 45        | 27.11%  |
| AMD    | 33        | 19.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 5.36%   |
| Intel UHD Graphics 620                                                                   | 8         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 3.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 3.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.98%   |
| Intel HD Graphics 620                                                                    | 5         | 2.98%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 2.38%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 2.38%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 2.38%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.38%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.38%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.79%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 1.79%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.79%   |
| Intel HD Graphics 530                                                                    | 3         | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.79%   |
| AMD Renoir                                                                               | 3         | 1.79%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.79%   |
| Nvidia TU117M                                                                            | 2         | 1.19%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.19%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 1.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.19%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.19%   |
| Nvidia GT218M [GeForce G 105M]                                                           | 1         | 0.6%    |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.6%    |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.6%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.6%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 34.55%  |
| Intel + Nvidia | 37        | 33.64%  |
| Intel + AMD    | 13        | 11.82%  |
| 1 x AMD        | 12        | 10.91%  |
| AMD + Nvidia   | 6         | 5.45%   |
| 2 x AMD        | 2         | 1.82%   |
| 1 x Nvidia     | 2         | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 85        | 74.56%  |
| Proprietary | 25        | 21.93%  |
| Unknown     | 4         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 53.57%  |
| 1.01-2.0   | 17        | 15.18%  |
| 0.01-0.5   | 13        | 11.61%  |
| 3.01-4.0   | 11        | 9.82%   |
| 0.51-1.0   | 8         | 7.14%   |
| 2.01-3.0   | 2         | 1.79%   |
| 7.01-8.0   | 1         | 0.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 26        | 21.31%  |
| AU Optronics            | 25        | 20.49%  |
| BOE                     | 23        | 18.85%  |
| Samsung Electronics     | 18        | 14.75%  |
| LG Display              | 14        | 11.48%  |
| Hewlett-Packard         | 3         | 2.46%   |
| Chi Mei Optoelectronics | 3         | 2.46%   |
| PANDA                   | 2         | 1.64%   |
| Packard Bell            | 1         | 0.82%   |
| LG Philips              | 1         | 0.82%   |
| Lenovo                  | 1         | 0.82%   |
| ITE                     | 1         | 0.82%   |
| Goldstar                | 1         | 0.82%   |
| Dell                    | 1         | 0.82%   |
| BenQ                    | 1         | 0.82%   |
| Acer                    | 1         | 0.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 4.07%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 3.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 2.44%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.44%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 2.44%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 1.63%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 2         | 1.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 1.63%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.63%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.63%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 1         | 0.81%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.81%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.81%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch      | 1         | 0.81%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch           | 1         | 0.81%   |
| LG Display LP156WH2-TLR1 LGD0221 1366x768 340x190mm 15.3-inch         | 1         | 0.81%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 51        | 44.74%  |
| 1366x768 (WXGA)  | 49        | 42.98%  |
| 1600x900 (HD+)   | 5         | 4.39%   |
| 3840x2160 (4K)   | 3         | 2.63%   |
| 1280x800 (WXGA)  | 2         | 1.75%   |
| 3840x1100        | 1         | 0.88%   |
| 2560x1440 (QHD)  | 1         | 0.88%   |
| 1440x900 (WXGA+) | 1         | 0.88%   |
| 1280x1024 (SXGA) | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 83        | 68.03%  |
| 17     | 8         | 6.56%   |
| 14     | 7         | 5.74%   |
| 13     | 7         | 5.74%   |
| 21     | 6         | 4.92%   |
| 24     | 4         | 3.28%   |
| 27     | 2         | 1.64%   |
| 31     | 1         | 0.82%   |
| 23     | 1         | 0.82%   |
| 20     | 1         | 0.82%   |
| 12     | 1         | 0.82%   |
| 11     | 1         | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 93        | 77.5%   |
| 351-400     | 8         | 6.67%   |
| 501-600     | 7         | 5.83%   |
| 401-500     | 7         | 5.83%   |
| 201-300     | 4         | 3.33%   |
| 601-700     | 1         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 101       | 94.39%  |
| 16/10 | 4         | 3.74%   |
| 5/4   | 1         | 0.93%   |
| 3.40  | 1         | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 83        | 68.03%  |
| 81-90          | 11        | 9.02%   |
| 201-250        | 11        | 9.02%   |
| 121-130        | 5         | 4.1%    |
| 71-80          | 2         | 1.64%   |
| 51-60          | 2         | 1.64%   |
| 301-350        | 2         | 1.64%   |
| 131-140        | 2         | 1.64%   |
| 61-70          | 1         | 0.82%   |
| 351-500        | 1         | 0.82%   |
| 151-200        | 1         | 0.82%   |
| 141-150        | 1         | 0.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 51        | 42.86%  |
| 121-160       | 44        | 36.97%  |
| 51-100        | 18        | 15.13%  |
| 161-240       | 3         | 2.52%   |
| More than 240 | 2         | 1.68%   |
| 1-50          | 1         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 89        | 79.46%  |
| 2     | 18        | 16.07%  |
| 0     | 5         | 4.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 82        | 44.09%  |
| Intel                             | 40        | 21.51%  |
| Qualcomm Atheros                  | 30        | 16.13%  |
| Broadcom                          | 13        | 6.99%   |
| Broadcom Limited                  | 5         | 2.69%   |
| Ralink                            | 3         | 1.61%   |
| Ralink Technology                 | 2         | 1.08%   |
| MediaTek                          | 2         | 1.08%   |
| D-Link                            | 2         | 1.08%   |
| Sierra Wireless                   | 1         | 0.54%   |
| OPPO Electronics                  | 1         | 0.54%   |
| Marvell Technology Group          | 1         | 0.54%   |
| ICS Advent                        | 1         | 0.54%   |
| Huawei Technologies               | 1         | 0.54%   |
| Ericsson Business Mobile Networks | 1         | 0.54%   |
| D-Link System                     | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 24.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 10%     |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 4.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.18%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 3.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.73%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 2.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.36%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.36%   |
| Intel WiFi Link 5100                                              | 3         | 1.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.91%   |
| Intel Wireless 8260                                               | 2         | 0.91%   |
| Intel Wireless 7265                                               | 2         | 0.91%   |
| Intel Wireless 7260                                               | 2         | 0.91%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.91%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.91%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.91%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 0.91%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.91%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.91%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.91%   |
| Sierra Wireless EM7455                                            | 1         | 0.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.45%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 39        | 32.5%   |
| Realtek Semiconductor             | 27        | 22.5%   |
| Qualcomm Atheros                  | 27        | 22.5%   |
| Broadcom                          | 10        | 8.33%   |
| Broadcom Limited                  | 5         | 4.17%   |
| Ralink                            | 3         | 2.5%    |
| Ralink Technology                 | 2         | 1.67%   |
| MediaTek                          | 2         | 1.67%   |
| D-Link                            | 2         | 1.67%   |
| Sierra Wireless                   | 1         | 0.83%   |
| Ericsson Business Mobile Networks | 1         | 0.83%   |
| D-Link System                     | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 9.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 7.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 5.79%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 5.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 4.96%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 4.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 4.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 3.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 3.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 2.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.48%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.48%   |
| Intel WiFi Link 5100                                           | 3         | 2.48%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.65%   |
| Intel Wireless 8260                                            | 2         | 1.65%   |
| Intel Wireless 7265                                            | 2         | 1.65%   |
| Intel Wireless 7260                                            | 2         | 1.65%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.65%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 1.65%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 1.65%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.65%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.65%   |
| Sierra Wireless EM7455                                         | 1         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.83%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.83%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.83%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.83%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.83%   |
| MediaTek WLAN controller                                       | 1         | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 77        | 77.78%  |
| Intel                    | 11        | 11.11%  |
| Qualcomm Atheros         | 4         | 4.04%   |
| Broadcom                 | 3         | 3.03%   |
| OPPO Electronics         | 1         | 1.01%   |
| Marvell Technology Group | 1         | 1.01%   |
| ICS Advent               | 1         | 1.01%   |
| Huawei Technologies      | 1         | 1.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 54.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 22.22%  |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.02%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 2.02%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 2.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.01%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.01%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.01%   |
| OPPO RMX2117                                                      | 1         | 1.01%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.01%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.01%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.01%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.01%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.01%   |
| Huawei HUAWEI                                                     | 1         | 1.01%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 110       | 53.14%  |
| Ethernet | 97        | 46.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 81.42%  |
| Ethernet | 21        | 18.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 95        | 85.59%  |
| 1     | 16        | 14.41%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 32.99%  |
| Realtek Semiconductor           | 20        | 20.62%  |
| Qualcomm Atheros Communications | 18        | 18.56%  |
| Lite-On Technology              | 8         | 8.25%   |
| Broadcom                        | 6         | 6.19%   |
| IMC Networks                    | 4         | 4.12%   |
| Foxconn / Hon Hai               | 3         | 3.09%   |
| Ralink                          | 2         | 2.06%   |
| Toshiba                         | 1         | 1.03%   |
| Realtek                         | 1         | 1.03%   |
| Hewlett-Packard                 | 1         | 1.03%   |
| Dell                            | 1         | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 14        | 14.43%  |
| Intel Bluetooth wireless interface               | 12        | 12.37%  |
| Intel AX201 Bluetooth                            | 12        | 12.37%  |
| Qualcomm Atheros  Bluetooth Device               | 11        | 11.34%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 6         | 6.19%   |
| Realtek  Bluetooth 4.2 Adapter                   | 4         | 4.12%   |
| Qualcomm Atheros AR3011 Bluetooth                | 4         | 4.12%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device     | 3         | 3.09%   |
| Broadcom BCM43142A0 Bluetooth 4.0                | 3         | 3.09%   |
| Realtek RTL8723B Bluetooth                       | 2         | 2.06%   |
| Ralink RT3290 Bluetooth                          | 2         | 2.06%   |
| Lite-On Bluetooth Device                         | 2         | 2.06%   |
| IMC Networks Wireless_Device                     | 2         | 2.06%   |
| IMC Networks Bluetooth Radio                     | 2         | 2.06%   |
| Foxconn / Hon Hai Bluetooth Device               | 2         | 2.06%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR             | 2         | 2.06%   |
| Toshiba Bluetooth USB Host Controller            | 1         | 1.03%   |
| Realtek Bluetooth Radio                          | 1         | 1.03%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 1.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 1.03%   |
| Lite-On BCM43142A0                               | 1         | 1.03%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 1.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 1.03%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 1.03%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth    | 1         | 1.03%   |
| Dell DW375 Bluetooth Module                      | 1         | 1.03%   |
| Broadcom BCM43142 Bluetooth 4.0                  | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 94        | 68.61%  |
| Nvidia              | 20        | 14.6%   |
| AMD                 | 20        | 14.6%   |
| JMTek               | 1         | 0.73%   |
| DSEA A/S            | 1         | 0.73%   |
| C-Media Electronics | 1         | 0.73%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 11.88%  |
| Intel 8 Series HD Audio Controller                                                                | 9         | 5.63%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 5.63%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 5%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 3.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 3.75%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 3.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 3.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 2.5%    |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.5%    |
| AMD High Definition Audio Controller                                                              | 4         | 2.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.88%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.25%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.25%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.63%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.63%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia Audio device                                                                               | 1         | 0.63%   |
| JMTek USB PnP Audio Device(EEPROM)                                                                | 1         | 0.63%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 32.58%  |
| SK hynix            | 16        | 17.98%  |
| Micron Technology   | 9         | 10.11%  |
| Team                | 8         | 8.99%   |
| A-DATA Technology   | 6         | 6.74%   |
| Crucial             | 4         | 4.49%   |
| Unknown             | 3         | 3.37%   |
| Nanya Technology    | 3         | 3.37%   |
| Kingston            | 3         | 3.37%   |
| Toshiba             | 2         | 2.25%   |
| Ramaxel Technology  | 2         | 2.25%   |
| Elpida              | 2         | 2.25%   |
| Hikvision           | 1         | 1.12%   |
| ASint Technology    | 1         | 1.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s | 3         | 3.13%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 3         | 3.13%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s               | 3         | 3.13%   |
| Toshiba RAM 8HTF12864HDY-800G1 1024MB SODIMM 1066MT/s     | 2         | 2.08%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s      | 2         | 2.08%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s      | 2         | 2.08%   |
| Team RAM TEAMGROUP-SD4-2400 16384MB SODIMM DDR4 8400MT/s  | 2         | 2.08%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s  | 2         | 2.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 2.08%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 2.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 2.08%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 2.08%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s  | 2         | 2.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 2.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 2.08%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s      | 2         | 2.08%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s            | 1         | 1.04%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 1         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s             | 1         | 1.04%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s     | 1         | 1.04%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s     | 1         | 1.04%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s      | 1         | 1.04%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s               | 1         | 1.04%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s     | 1         | 1.04%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.04%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 1.04%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 1.04%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 1.04%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 1.04%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1         | 1.04%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 1.04%   |
| SK hynix RAM HMA81GS6MFR8N-TF 8GB SODIMM DDR4 2133MT/s    | 1         | 1.04%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 1.04%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s | 1         | 1.04%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s    | 1         | 1.04%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 1         | 1.04%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s     | 1         | 1.04%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 43        | 60.56%  |
| DDR3   | 18        | 25.35%  |
| DDR2   | 4         | 5.63%   |
| SDRAM  | 2         | 2.82%   |
| LPDDR4 | 2         | 2.82%   |
| LPDDR3 | 1         | 1.41%   |
| DDR5   | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 94.37%  |
| Row Of Chips | 3         | 4.23%   |
| Chip         | 1         | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 33        | 39.29%  |
| 8192  | 29        | 34.52%  |
| 16384 | 9         | 10.71%  |
| 2048  | 8         | 9.52%   |
| 32768 | 4         | 4.76%   |
| 1024  | 1         | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 24        | 29.27%  |
| 3200    | 16        | 19.51%  |
| 1600    | 12        | 14.63%  |
| 1334    | 7         | 8.54%   |
| 2400    | 5         | 6.1%    |
| 2133    | 3         | 3.66%   |
| 8400    | 2         | 2.44%   |
| 4199    | 2         | 2.44%   |
| 3266    | 2         | 2.44%   |
| 1867    | 2         | 2.44%   |
| 1066    | 2         | 2.44%   |
| 4800    | 1         | 1.22%   |
| 975     | 1         | 1.22%   |
| 800     | 1         | 1.22%   |
| 667     | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

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
| Chicony Electronics                    | 21        | 21%     |
| Realtek Semiconductor                  | 16        | 16%     |
| IMC Networks                           | 13        | 13%     |
| Microdia                               | 8         | 8%      |
| Acer                                   | 7         | 7%      |
| Suyin                                  | 6         | 6%      |
| Sunplus Innovation Technology          | 5         | 5%      |
| Lite-On Technology                     | 5         | 5%      |
| Syntek                                 | 4         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4%      |
| Quanta                                 | 3         | 3%      |
| Luxvisions Innotech Limited            | 3         | 3%      |
| Silicon Motion                         | 1         | 1%      |
| Ricoh                                  | 1         | 1%      |
| Importek                               | 1         | 1%      |
| Apple                                  | 1         | 1%      |
| Alcor Micro                            | 1         | 1%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 5.94%   |
| Chicony Integrated Camera                                   | 6         | 5.94%   |
| Syntek EasyCamera                                           | 3         | 2.97%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 2.97%   |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 2.97%   |
| Realtek USB Camera                                          | 3         | 2.97%   |
| Realtek Integrated_Webcam_HD                                | 3         | 2.97%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 3         | 2.97%   |
| Lite-On Integrated Camera                                   | 3         | 2.97%   |
| IMC Networks Integrated Camera                              | 3         | 2.97%   |
| Chicony HD WebCam                                           | 3         | 2.97%   |
| Acer Integrated Camera                                      | 3         | 2.97%   |
| Suyin HP TrueVision HD                                      | 2         | 1.98%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.98%   |
| Realtek EasyCamera                                          | 2         | 1.98%   |
| Quanta HD WebCam                                            | 2         | 1.98%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 2         | 1.98%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.98%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.98%   |
| Chicony EasyCamera                                          | 2         | 1.98%   |
| Acer HD Webcam                                              | 2         | 1.98%   |
| Syntek Integrated Camera                                    | 1         | 0.99%   |
| Suyin USB 2.0 Camera                                        | 1         | 0.99%   |
| Suyin HP Integrated Webcam                                  | 1         | 0.99%   |
| Suyin HD WebCam                                             | 1         | 0.99%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.99%   |
| Sunplus HD User Facing                                      | 1         | 0.99%   |
| Sunplus Dell HD Webcam                                      | 1         | 0.99%   |
| Silicon Motion WebCam SC-13HDL11431N                        | 1         | 0.99%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 0.99%   |
| Realtek Integrated Webcam_HD                                | 1         | 0.99%   |
| Realtek Integrated Webcam                                   | 1         | 0.99%   |
| Realtek HP Webcam                                           | 1         | 0.99%   |
| Quanta HP Webcam                                            | 1         | 0.99%   |
| Microdia Webcam SC-10HDD12636P                              | 1         | 0.99%   |
| Microdia Integrated_Webcam_HD                               | 1         | 0.99%   |
| Microdia HP Webcam                                          | 1         | 0.99%   |
| Microdia HP Integrated Webcam                               | 1         | 0.99%   |
| Lite-On TOSHIBA Web Camera - HD                             | 1         | 0.99%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 50%     |
| LighTuning Technology      | 2         | 25%     |
| Synaptics                  | 1         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
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
| 0     | 83        | 69.17%  |
| 1     | 30        | 25%     |
| 3     | 4         | 3.33%   |
| 2     | 2         | 1.67%   |
| 4     | 1         | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 11        | 23.91%  |
| Graphics card            | 11        | 23.91%  |
| Fingerprint reader       | 8         | 17.39%  |
| Bluetooth                | 4         | 8.7%    |
| Communication controller | 3         | 6.52%   |
| Chipcard                 | 3         | 6.52%   |
| Storage                  | 2         | 4.35%   |
| Sound                    | 1         | 2.17%   |
| Network                  | 1         | 2.17%   |
| Card reader              | 1         | 2.17%   |
| Camera                   | 1         | 2.17%   |

