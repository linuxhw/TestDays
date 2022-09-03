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

Total: 156

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 33        | 28.95%  |
| Ubuntu 18.04      | 12        | 10.53%  |
| Ubuntu 21.10      | 5         | 4.39%   |
| Zorin 15          | 3         | 2.63%   |
| Ubuntu 22.04      | 3         | 2.63%   |
| Ubuntu 16.04      | 3         | 2.63%   |
| Debian 10         | 3         | 2.63%   |
| Ubuntu 21.04      | 2         | 1.75%   |
| Ubuntu 20.10      | 2         | 1.75%   |
| Pop!_OS 22.04     | 2         | 1.75%   |
| Pop!_OS 21.04     | 2         | 1.75%   |
| OpenMandriva 4.2  | 2         | 1.75%   |
| Manjaro 21.1.0    | 2         | 1.75%   |
| LMDE 4            | 2         | 1.75%   |
| Linux Mint 20.3   | 2         | 1.75%   |
| Linux Mint 20.2   | 2         | 1.75%   |
| Fedora 35         | 2         | 1.75%   |
| Fedora 33         | 2         | 1.75%   |
| Xubuntu 18.04     | 1         | 0.88%   |
| Ubuntu 19.10      | 1         | 0.88%   |
| Sodalite 35       | 1         | 0.88%   |
| ROSA R8.1         | 1         | 0.88%   |
| ROSA R11          | 1         | 0.88%   |
| ROSA R10          | 1         | 0.88%   |
| Pop!_OS 20.10     | 1         | 0.88%   |
| OpenMandriva 4.3  | 1         | 0.88%   |
| Manjaro 21.3.6    | 1         | 0.88%   |
| Manjaro 20.2      | 1         | 0.88%   |
| Lubuntu 20.04     | 1         | 0.88%   |
| Lubuntu 18.04     | 1         | 0.88%   |
| Linux Mint 20.1   | 1         | 0.88%   |
| Linux Mint 20     | 1         | 0.88%   |
| Kubuntu 20.04     | 1         | 0.88%   |
| KDE neon 20.04    | 1         | 0.88%   |
| Gentoo 2.8        | 1         | 0.88%   |
| Gentoo 2.7        | 1         | 0.88%   |
| Fedora 31         | 1         | 0.88%   |
| Endless 3.9.5     | 1         | 0.88%   |
| Endless 3.7.8     | 1         | 0.88%   |
| Endless 3.5.0     | 1         | 0.88%   |
| Elementary 5.1.5  | 1         | 0.88%   |
| Deepin            | 1         | 0.88%   |
| Debian Unstable   | 1         | 0.88%   |
| Debian 11         | 1         | 0.88%   |
| BlackPanther 18.1 | 1         | 0.88%   |
| ArcoLinux Rolling | 1         | 0.88%   |
| Arch Rolling      | 1         | 0.88%   |
| Arch              | 1         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 59        | 53.64%  |
| Linux Mint   | 6         | 5.45%   |
| Pop!_OS      | 5         | 4.55%   |
| Debian       | 5         | 4.55%   |
| Manjaro      | 4         | 3.64%   |
| Fedora       | 4         | 3.64%   |
| Zorin        | 3         | 2.73%   |
| ROSA         | 3         | 2.73%   |
| OpenMandriva | 3         | 2.73%   |
| Endless      | 3         | 2.73%   |
| Lubuntu      | 2         | 1.82%   |
| LMDE         | 2         | 1.82%   |
| Arch         | 2         | 1.82%   |
| Xubuntu      | 1         | 0.91%   |
| Sodalite     | 1         | 0.91%   |
| Kubuntu      | 1         | 0.91%   |
| KDE neon     | 1         | 0.91%   |
| Gentoo       | 1         | 0.91%   |
| Elementary   | 1         | 0.91%   |
| Deepin       | 1         | 0.91%   |
| BlackPanther | 1         | 0.91%   |
| ArcoLinux    | 1         | 0.91%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.13.0-28-generic        | 4         | 3.31%   |
| 5.3.0-46-generic         | 3         | 2.48%   |
| 5.11.0-38-generic        | 3         | 2.48%   |
| 5.8.0-38-generic         | 2         | 1.65%   |
| 5.4.0-72-generic         | 2         | 1.65%   |
| 5.4.0-58-generic         | 2         | 1.65%   |
| 5.4.0-52-generic         | 2         | 1.65%   |
| 5.4.0-42-generic         | 2         | 1.65%   |
| 5.3.0-40-generic         | 2         | 1.65%   |
| 5.3.0-28-generic         | 2         | 1.65%   |
| 5.15.0-43-generic        | 2         | 1.65%   |
| 5.13.0-44-generic        | 2         | 1.65%   |
| 5.13.0-40-generic        | 2         | 1.65%   |
| 5.11.0-7620-generic      | 2         | 1.65%   |
| 5.11.0-40-generic        | 2         | 1.65%   |
| 5.10.14-desktop-1omv4002 | 2         | 1.65%   |
| 5.0.0-25-generic         | 2         | 1.65%   |
| 4.19.0-6-amd64           | 2         | 1.65%   |
| 5.9.9-arch1-1            | 1         | 0.83%   |
| 5.8.15-301.fc33.x86_64   | 1         | 0.83%   |
| 5.8.0-50-generic         | 1         | 0.83%   |
| 5.8.0-44-generic         | 1         | 0.83%   |
| 5.8.0-40-generic         | 1         | 0.83%   |
| 5.8.0-33-generic         | 1         | 0.83%   |
| 5.8.0-32-generic         | 1         | 0.83%   |
| 5.8.0-28-generic         | 1         | 0.83%   |
| 5.8.0-14-generic         | 1         | 0.83%   |
| 5.6.14-desktop-2bP       | 1         | 0.83%   |
| 5.4.80-2-MANJARO         | 1         | 0.83%   |
| 5.4.143-1-pve            | 1         | 0.83%   |
| 5.4.119-1-pve            | 1         | 0.83%   |
| 5.4.0-91-generic         | 1         | 0.83%   |
| 5.4.0-90-generic         | 1         | 0.83%   |
| 5.4.0-84-generic         | 1         | 0.83%   |
| 5.4.0-65-lowlatency      | 1         | 0.83%   |
| 5.4.0-65-generic         | 1         | 0.83%   |
| 5.4.0-56-generic         | 1         | 0.83%   |
| 5.4.0-48-generic         | 1         | 0.83%   |
| 5.4.0-47-generic         | 1         | 0.83%   |
| 5.4.0-45-generic         | 1         | 0.83%   |
| 5.4.0-33-generic         | 1         | 0.83%   |
| 5.4.0-29-generic         | 1         | 0.83%   |
| 5.4.0-28-lowlatency      | 1         | 0.83%   |
| 5.4.0-26-generic         | 1         | 0.83%   |
| 5.4.0-107-generic        | 1         | 0.83%   |
| 5.3.8-300.fc31.x86_64    | 1         | 0.83%   |
| 5.3.0-59-generic         | 1         | 0.83%   |
| 5.19.0-76051900-generic  | 1         | 0.83%   |
| 5.19.0-2-MANJARO         | 1         | 0.83%   |
| 5.18.0-4-amd64           | 1         | 0.83%   |
| 5.17.5-76051705-generic  | 1         | 0.83%   |
| 5.16.9-200.fc35.x86_64   | 1         | 0.83%   |
| 5.16.7-desktop-1omv4003  | 1         | 0.83%   |
| 5.16.18-200.fc35.x86_64  | 1         | 0.83%   |
| 5.16.11-200.fc35.x86_64  | 1         | 0.83%   |
| 5.15.16-200.fc35.x86_64  | 1         | 0.83%   |
| 5.15.0-46-generic        | 1         | 0.83%   |
| 5.15.0-41-generic        | 1         | 0.83%   |
| 5.15.0-39-generic        | 1         | 0.83%   |
| 5.15.0-25-generic        | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 17.8%   |
| 5.13.0  | 13        | 11.02%  |
| 5.11.0  | 11        | 9.32%   |
| 5.8.0   | 9         | 7.63%   |
| 5.3.0   | 8         | 6.78%   |
| 4.15.0  | 8         | 6.78%   |
| 5.15.0  | 6         | 5.08%   |
| 5.0.0   | 6         | 5.08%   |
| 4.19.0  | 4         | 3.39%   |
| 5.19.0  | 2         | 1.69%   |
| 5.10.14 | 2         | 1.69%   |
| 4.18.0  | 2         | 1.69%   |
| 5.9.9   | 1         | 0.85%   |
| 5.8.15  | 1         | 0.85%   |
| 5.6.14  | 1         | 0.85%   |
| 5.4.80  | 1         | 0.85%   |
| 5.4.143 | 1         | 0.85%   |
| 5.4.119 | 1         | 0.85%   |
| 5.3.8   | 1         | 0.85%   |
| 5.18.0  | 1         | 0.85%   |
| 5.17.5  | 1         | 0.85%   |
| 5.16.9  | 1         | 0.85%   |
| 5.16.7  | 1         | 0.85%   |
| 5.16.18 | 1         | 0.85%   |
| 5.16.11 | 1         | 0.85%   |
| 5.15.16 | 1         | 0.85%   |
| 5.13.11 | 1         | 0.85%   |
| 5.12.12 | 1         | 0.85%   |
| 5.11.17 | 1         | 0.85%   |
| 5.11.13 | 1         | 0.85%   |
| 5.10.53 | 1         | 0.85%   |
| 5.10.27 | 1         | 0.85%   |
| 5.10.19 | 1         | 0.85%   |
| 5.10.0  | 1         | 0.85%   |
| 4.9.9   | 1         | 0.85%   |
| 4.9.60  | 1         | 0.85%   |
| 4.9.124 | 1         | 0.85%   |
| 3.13.0  | 1         | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 20%     |
| 5.13    | 14        | 12.17%  |
| 5.11    | 13        | 11.3%   |
| 5.8     | 10        | 8.7%    |
| 5.3     | 9         | 7.83%   |
| 4.15    | 8         | 6.96%   |
| 5.15    | 7         | 6.09%   |
| 5.10    | 6         | 5.22%   |
| 5.0     | 6         | 5.22%   |
| 4.19    | 4         | 3.48%   |
| 5.16    | 3         | 2.61%   |
| 5.19    | 2         | 1.74%   |
| 4.9     | 2         | 1.74%   |
| 4.18    | 2         | 1.74%   |
| 5.9     | 1         | 0.87%   |
| 5.6     | 1         | 0.87%   |
| 5.18    | 1         | 0.87%   |
| 5.17    | 1         | 0.87%   |
| 5.12    | 1         | 0.87%   |
| 3.13    | 1         | 0.87%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 106       | 98.15%  |
| i686   | 2         | 1.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 67        | 59.82%  |
| Unknown         | 11        | 9.82%   |
| KDE5            | 10        | 8.93%   |
| X-Cinnamon      | 7         | 6.25%   |
| XFCE            | 4         | 3.57%   |
| KDE4            | 3         | 2.68%   |
| Pantheon        | 2         | 1.79%   |
| Unity           | 1         | 0.89%   |
| MATE            | 1         | 0.89%   |
| LXQt            | 1         | 0.89%   |
| LXDE            | 1         | 0.89%   |
| GNOME Flashback | 1         | 0.89%   |
| GNOME Classic   | 1         | 0.89%   |
| DWM             | 1         | 0.89%   |
| Deepin          | 1         | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 87        | 78.38%  |
| Wayland | 17        | 15.32%  |
| Unknown | 5         | 4.5%    |
| Tty     | 2         | 1.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 44        | 40.37%  |
| GDM     | 38        | 34.86%  |
| SDDM    | 9         | 8.26%   |
| GDM3    | 8         | 7.34%   |
| LightDM | 7         | 6.42%   |
| KDM     | 3         | 2.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 54        | 49.09%  |
| fr_FR   | 32        | 29.09%  |
| Unknown | 15        | 13.64%  |
| en_GB   | 4         | 3.64%   |
| C       | 2         | 1.82%   |
| pt_BR   | 1         | 0.91%   |
| en_CA   | 1         | 0.91%   |
| ar_TN   | 1         | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 64        | 58.18%  |
| BIOS | 46        | 41.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 97        | 88.99%  |
| Unknown | 5         | 4.59%   |
| Overlay | 4         | 3.67%   |
| Btrfs   | 2         | 1.83%   |
| Xfs     | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 46.79%  |
| GPT     | 40        | 36.7%   |
| MBR     | 18        | 16.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 91.74%  |
| Yes       | 9         | 8.26%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 65.42%  |
| Yes       | 37        | 34.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 28        | 26.17%  |
| ASUSTek Computer    | 21        | 19.63%  |
| Hewlett-Packard     | 20        | 18.69%  |
| Dell                | 15        | 14.02%  |
| Acer                | 9         | 8.41%   |
| Toshiba             | 5         | 4.67%   |
| MSI                 | 4         | 3.74%   |
| Samsung Electronics | 2         | 1.87%   |
| Sony                | 1         | 0.93%   |
| Packard Bell        | 1         | 0.93%   |
| eMachines           | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 3         | 2.8%    |
| Lenovo IdeaPad 130-15IKB 81H7            | 2         | 1.87%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 1.87%   |
| HP Pavilion g6                           | 2         | 1.87%   |
| Dell Inspiron 5570                       | 2         | 1.87%   |
| ASUS X556UV                              | 2         | 1.87%   |
| ASUS X550JX                              | 2         | 1.87%   |
| Toshiba Satellite Pro L850-B339          | 1         | 0.93%   |
| Toshiba Satellite L550                   | 1         | 0.93%   |
| Toshiba Satellite L500                   | 1         | 0.93%   |
| Toshiba Satellite C50-A489               | 1         | 0.93%   |
| Toshiba Satellite A300                   | 1         | 0.93%   |
| Sony VPCEH36EF                           | 1         | 0.93%   |
| Samsung 530U3BI/530U4BI/530U4BH          | 1         | 0.93%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 0.93%   |
| Packard Bell EasyNote ML65               | 1         | 0.93%   |
| MSI Katana GF66 12UC                     | 1         | 0.93%   |
| MSI GF65 Thin 10UE                       | 1         | 0.93%   |
| MSI GF63 Thin 10SCXR                     | 1         | 0.93%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.93%   |
| Lenovo V310-15ISK 80SY                   | 1         | 0.93%   |
| Lenovo V15-IIL 82C5                      | 1         | 0.93%   |
| Lenovo ThinkPad X240 20AMA0WRFR          | 1         | 0.93%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100 | 1         | 0.93%   |
| Lenovo ThinkPad T440s 20AQ005NUS         | 1         | 0.93%   |
| Lenovo ThinkPad E15 20RD001SFE           | 1         | 0.93%   |
| Lenovo ThinkPad E15 20RD001QFE           | 1         | 0.93%   |
| Lenovo ThinkPad E14 20RA000KFE           | 1         | 0.93%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 0.93%   |
| Lenovo IdeaPad S145-15AST 81N3           | 1         | 0.93%   |
| Lenovo IdeaPad L3 15IML05 81Y3           | 1         | 0.93%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 0.93%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 0.93%   |
| Lenovo IdeaPad 700-15ISK 80RU            | 1         | 0.93%   |
| Lenovo IdeaPad 330S-14AST 81F8           | 1         | 0.93%   |
| Lenovo IdeaPad 330-15AST 81D6            | 1         | 0.93%   |
| Lenovo IdeaPad 320-15IKB 81BT            | 1         | 0.93%   |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 0.93%   |
| Lenovo IdeaPad 100-15IBD 80QQ            | 1         | 0.93%   |
| Lenovo G580 20157                        | 1         | 0.93%   |
| Lenovo G50-70 20351                      | 1         | 0.93%   |
| HP ProBook 455 G3                        | 1         | 0.93%   |
| HP ProBook 440 G7                        | 1         | 0.93%   |
| HP Pavilion Gaming Laptop 15-ec0xxx      | 1         | 0.93%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 0.93%   |
| HP Pavilion dv7                          | 1         | 0.93%   |
| HP Pavilion dv6                          | 1         | 0.93%   |
| HP Notebook                              | 1         | 0.93%   |
| HP Laptop 17-ak0xx                       | 1         | 0.93%   |
| HP Laptop 15-dw3xxx                      | 1         | 0.93%   |
| HP Laptop 15-bs0xx                       | 1         | 0.93%   |
| HP Laptop                                | 1         | 0.93%   |
| HP EliteBook 8740w                       | 1         | 0.93%   |
| HP Compaq 6735s                          | 1         | 0.93%   |
| HP 630                                   | 1         | 0.93%   |
| HP 250 G7 Notebook PC                    | 1         | 0.93%   |
| HP 250 G4                                | 1         | 0.93%   |
| eMachines E725                           | 1         | 0.93%   |
| Dell Latitude E6420                      | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 16        | 14.95%  |
| Dell Inspiron         | 9         | 8.41%   |
| HP Pavilion           | 8         | 7.48%   |
| Lenovo ThinkPad       | 7         | 6.54%   |
| Dell Latitude         | 6         | 5.61%   |
| Acer Aspire           | 6         | 5.61%   |
| Toshiba Satellite     | 5         | 4.67%   |
| HP Laptop             | 4         | 3.74%   |
| ASUS TUF              | 4         | 3.74%   |
| MSI GF63              | 2         | 1.87%   |
| HP ProBook            | 2         | 1.87%   |
| HP 250                | 2         | 1.87%   |
| ASUS X556UV           | 2         | 1.87%   |
| ASUS X550JX           | 2         | 1.87%   |
| ASUS VivoBook         | 2         | 1.87%   |
| ASUS ROG              | 2         | 1.87%   |
| ASUS ASUS             | 2         | 1.87%   |
| Acer Swift            | 2         | 1.87%   |
| Sony VPCEH36EF        | 1         | 0.93%   |
| Samsung 530U3BI       | 1         | 0.93%   |
| Samsung 300E5EV       | 1         | 0.93%   |
| Packard Bell EasyNote | 1         | 0.93%   |
| MSI Katana            | 1         | 0.93%   |
| MSI GF65              | 1         | 0.93%   |
| Lenovo V310-15ISK     | 1         | 0.93%   |
| Lenovo V15-IIL        | 1         | 0.93%   |
| Lenovo G580           | 1         | 0.93%   |
| Lenovo G50-70         | 1         | 0.93%   |
| HP Notebook           | 1         | 0.93%   |
| HP EliteBook          | 1         | 0.93%   |
| HP Compaq             | 1         | 0.93%   |
| HP 630                | 1         | 0.93%   |
| eMachines E725        | 1         | 0.93%   |
| ASUS ZenBook          | 1         | 0.93%   |
| ASUS X555LD           | 1         | 0.93%   |
| ASUS X553MA           | 1         | 0.93%   |
| ASUS X550VX           | 1         | 0.93%   |
| ASUS X550LC           | 1         | 0.93%   |
| ASUS UX360CA          | 1         | 0.93%   |
| ASUS UX310UQK         | 1         | 0.93%   |
| Acer TravelMate       | 1         | 0.93%   |
| Unknown               | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 15        | 14.02%  |
| 2020 | 13        | 12.15%  |
| 2018 | 11        | 10.28%  |
| 2017 | 10        | 9.35%   |
| 2013 | 10        | 9.35%   |
| 2015 | 8         | 7.48%   |
| 2016 | 7         | 6.54%   |
| 2011 | 7         | 6.54%   |
| 2021 | 5         | 4.67%   |
| 2014 | 5         | 4.67%   |
| 2012 | 5         | 4.67%   |
| 2008 | 5         | 4.67%   |
| 2009 | 3         | 2.8%    |
| 2010 | 2         | 1.87%   |
| 2022 | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 107       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 99        | 92.52%  |
| Enabled  | 8         | 7.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 42        | 38.89%  |
| 3.01-4.0   | 21        | 19.44%  |
| 16.01-24.0 | 20        | 18.52%  |
| 8.01-16.0  | 19        | 17.59%  |
| 32.01-64.0 | 4         | 3.7%    |
| 2.01-3.0   | 1         | 0.93%   |
| 1.01-2.0   | 1         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 35        | 29.66%  |
| 1.01-2.0  | 33        | 27.97%  |
| 4.01-8.0  | 24        | 20.34%  |
| 3.01-4.0  | 18        | 15.25%  |
| 8.01-16.0 | 3         | 2.54%   |
| 0.51-1.0  | 3         | 2.54%   |
| 0.01-0.5  | 1         | 0.85%   |
| Unknown   | 1         | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 75.23%  |
| 2      | 27        | 24.77%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 50%     |
| No        | 54        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 88.79%  |
| No        | 12        | 11.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 86.36%  |
| No        | 15        | 13.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Tunisia | 107       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Tunis              | 66        | 55.93%  |
| Sousse             | 6         | 5.08%   |
| Nabeul             | 5         | 4.24%   |
| Aryanah            | 5         | 4.24%   |
| Bizerte            | 4         | 3.39%   |
| Centre Urbain Nord | 3         | 2.54%   |
| Rades              | 2         | 1.69%   |
| Monastir           | 2         | 1.69%   |
| Masakin            | 2         | 1.69%   |
| Zarzis             | 1         | 0.85%   |
| Zaouiat Djedidi    | 1         | 0.85%   |
| Wadi Maliz         | 1         | 0.85%   |
| Tebourba           | 1         | 0.85%   |
| Tataouine          | 1         | 0.85%   |
| Sfax               | 1         | 0.85%   |
| Rafraf             | 1         | 0.85%   |
| Oued Lill          | 1         | 0.85%   |
| Mateur             | 1         | 0.85%   |
| Manouba            | 1         | 0.85%   |
| Mahdia             | 1         | 0.85%   |
| La Goulette        | 1         | 0.85%   |
| Jendouba           | 1         | 0.85%   |
| Jedeida            | 1         | 0.85%   |
| Houmt Souk         | 1         | 0.85%   |
| Hergla             | 1         | 0.85%   |
| Gremda             | 1         | 0.85%   |
| Gafsa              | 1         | 0.85%   |
| El Fahs            | 1         | 0.85%   |
| El Battan          | 1         | 0.85%   |
| Borj el Amri       | 1         | 0.85%   |
| Ben Arous          | 1         | 0.85%   |
| Belvedere          | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 27        | 31     | 20.77%  |
| WDC                   | 21        | 28     | 16.15%  |
| Toshiba               | 15        | 17     | 11.54%  |
| Samsung Electronics   | 10        | 11     | 7.69%   |
| Team                  | 9         | 11     | 6.92%   |
| SK hynix              | 9         | 10     | 6.92%   |
| SanDisk               | 5         | 5      | 3.85%   |
| Hitachi               | 5         | 5      | 3.85%   |
| HGST                  | 5         | 6      | 3.85%   |
| Micron Technology     | 4         | 4      | 3.08%   |
| Kingston              | 4         | 6      | 3.08%   |
| Unknown               | 3         | 3      | 2.31%   |
| Fujitsu               | 3         | 3      | 2.31%   |
| Intel                 | 2         | 2      | 1.54%   |
| UMIS                  | 1         | 1      | 0.77%   |
| TwinMOS               | 1         | 1      | 0.77%   |
| Realtek Semiconductor | 1         | 1      | 0.77%   |
| PNY                   | 1         | 1      | 0.77%   |
| Phison                | 1         | 1      | 0.77%   |
| Patriot               | 1         | 1      | 0.77%   |
| OCZ                   | 1         | 1      | 0.77%   |
| A-DATA Technology     | 1         | 1      | 0.77%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 9         | 6.82%   |
| Seagate ST500LT012-1DG142 500GB         | 7         | 5.3%    |
| WDC WD5000LPCX-24VHAT0 500GB            | 3         | 2.27%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 2.27%   |
| Seagate ST2000LM007-1R8174 2TB          | 3         | 2.27%   |
| Hitachi HTS545050A7E380 500GB           | 3         | 2.27%   |
| WDC WD20SPZX-08UA7 2TB                  | 2         | 1.52%   |
| WDC WD10SPZX-08Z10 1TB                  | 2         | 1.52%   |
| WDC WD10SPCX-24HWST1 1TB                | 2         | 1.52%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 1.52%   |
| Toshiba MK5076GSX 500GB                 | 2         | 1.52%   |
| Team T253X2512G 512GB SSD               | 2         | 1.52%   |
| SK hynix SC311 SATA 256GB SSD           | 2         | 1.52%   |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 1.52%   |
| Kingston NVMe SSD Drive 512GB           | 2         | 1.52%   |
| HGST HTS545050A7E380 500GB              | 2         | 1.52%   |
| Fujitsu MHV2100BH PL 100GB              | 2         | 1.52%   |
| WDC WD5000LPZX-60Z10T0 500GB            | 1         | 0.76%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 1         | 0.76%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 0.76%   |
| WDC WD5000LPLX-60ZNTT2 500GB            | 1         | 0.76%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.76%   |
| WDC WD5000BPVT-55HXZT3 500GB            | 1         | 0.76%   |
| WDC WD3200BEKT-60KA9T0 320GB            | 1         | 0.76%   |
| WDC WD2500BPVT-75JJ5T0 250GB            | 1         | 0.76%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.76%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB    | 1         | 0.76%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB    | 1         | 0.76%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB    | 1         | 0.76%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB    | 1         | 0.76%   |
| Unknown xD/SD/M.S.                      | 1         | 0.76%   |
| Unknown SS16G  16GB                     | 1         | 0.76%   |
| Unknown 00000  64GB                     | 1         | 0.76%   |
| UMIS RPJTJ512MEE1OWX 512GB              | 1         | 0.76%   |
| TwinMOS SSD 512GB                       | 1         | 0.76%   |
| Toshiba MQ01ACF050 500GB                | 1         | 0.76%   |
| Toshiba MQ01ABD050 500GB                | 1         | 0.76%   |
| Toshiba MQ01ABD032 320GB                | 1         | 0.76%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.76%   |
| Toshiba MK4055GSX 400GB                 | 1         | 0.76%   |
| Toshiba MK3275GSX 320GB                 | 1         | 0.76%   |
| Toshiba MK1646GSX 160GB                 | 1         | 0.76%   |
| Toshiba MK1032GSX 100GB                 | 1         | 0.76%   |
| Team TM8FP6512G 512GB                   | 1         | 0.76%   |
| Team TM8FP6256G 256GB                   | 1         | 0.76%   |
| Team TM8FP6128G 128GB                   | 1         | 0.76%   |
| Team TM8FP4256G 256GB                   | 1         | 0.76%   |
| Team T253LE240G 240GB SSD               | 1         | 0.76%   |
| Team T253E2512G 512GB SSD               | 1         | 0.76%   |
| Team T2535T240G 240GB SSD               | 1         | 0.76%   |
| SK hynix NVMe SSD Drive 512GB           | 1         | 0.76%   |
| SK hynix HFS512G39MND-3510A 512GB SSD   | 1         | 0.76%   |
| SK hynix HFS256G39TND-N210A 256GB SSD   | 1         | 0.76%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 1         | 0.76%   |
| SK hynix HFM512GD3JX013N 512GB          | 1         | 0.76%   |
| SK hynix HFM256GDJTNG-8310A 256GB       | 1         | 0.76%   |
| SK hynix BC511 NVMe 256GB               | 1         | 0.76%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 1         | 0.76%   |
| Seagate ST9320320AS 320GB               | 1         | 0.76%   |
| Seagate ST9120823ASG 120GB              | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 27        | 31     | 36.99%  |
| WDC     | 18        | 24     | 24.66%  |
| Toshiba | 15        | 17     | 20.55%  |
| Hitachi | 5         | 5      | 6.85%   |
| HGST    | 5         | 6      | 6.85%   |
| Fujitsu | 3         | 3      | 4.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 5         | 7      | 21.74%  |
| SK hynix            | 5         | 5      | 21.74%  |
| Samsung Electronics | 5         | 6      | 21.74%  |
| SanDisk             | 3         | 3      | 13.04%  |
| TwinMOS             | 1         | 1      | 4.35%   |
| PNY                 | 1         | 1      | 4.35%   |
| Patriot             | 1         | 1      | 4.35%   |
| OCZ                 | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 72        | 86     | 57.14%  |
| NVMe    | 28        | 35     | 22.22%  |
| SSD     | 23        | 26     | 18.25%  |
| MMC     | 2         | 2      | 1.59%   |
| Unknown | 1         | 1      | 0.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 112    | 73.73%  |
| NVMe | 28        | 35     | 23.73%  |
| MMC  | 2         | 2      | 1.69%   |
| SAS  | 1         | 1      | 0.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57        | 67     | 61.29%  |
| 0.51-1.0   | 31        | 39     | 33.33%  |
| 1.01-2.0   | 5         | 6      | 5.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 36        | 32.14%  |
| 101-250    | 34        | 30.36%  |
| 501-1000   | 16        | 14.29%  |
| 1001-2000  | 10        | 8.93%   |
| 51-100     | 7         | 6.25%   |
| 1-20       | 6         | 5.36%   |
| 21-50      | 2         | 1.79%   |
| Unknown    | 1         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 43        | 37.39%  |
| 101-250   | 22        | 19.13%  |
| 51-100    | 19        | 16.52%  |
| 21-50     | 17        | 14.78%  |
| 501-1000  | 6         | 5.22%   |
| 251-500   | 5         | 4.35%   |
| 1001-2000 | 2         | 1.74%   |
| Unknown   | 1         | 0.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 9.09%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 9.09%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 9.09%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 9.09%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 9.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 9.09%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 9.09%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 9.09%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 9.09%   |
| HGST HTS545050A7E380 500GB                          | 1         | 2      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 4         | 5      | 36.36%  |
| Seagate           | 2         | 2      | 18.18%  |
| Hitachi           | 2         | 2      | 18.18%  |
| WDC               | 1         | 2      | 9.09%   |
| Micron Technology | 1         | 1      | 9.09%   |
| HGST              | 1         | 2      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 5      | 40%     |
| Seagate | 2         | 2      | 20%     |
| Hitachi | 2         | 2      | 20%     |
| WDC     | 1         | 2      | 10%     |
| HGST    | 1         | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 13     | 90.91%  |
| SSD  | 1         | 1      | 9.09%   |

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
| Detected | 51        | 69     | 45.13%  |
| Works    | 50        | 66     | 44.25%  |
| Malfunc  | 11        | 14     | 9.73%   |
| Failed   | 1         | 1      | 0.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 90        | 69.23%  |
| AMD                          | 11        | 8.46%   |
| SanDisk                      | 5         | 3.85%   |
| Samsung Electronics          | 5         | 3.85%   |
| SK hynix                     | 4         | 3.08%   |
| Kingston Technology Company  | 4         | 3.08%   |
| Phison Electronics           | 3         | 2.31%   |
| Micron Technology            | 3         | 2.31%   |
| Realtek Semiconductor        | 2         | 1.54%   |
| Union Memory (Shenzhen)      | 1         | 0.77%   |
| Silicon Motion               | 1         | 0.77%   |
| Shenzhen Longsys Electronics | 1         | 0.77%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 13        | 9.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 8.21%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 7.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 5.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 5.22%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 3.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 3.73%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 2.99%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 2.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 2.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 2.24%   |
| Micron Non-Volatile memory controller                                            | 3         | 2.24%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.24%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 2.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.24%   |
| SK hynix BC511                                                                   | 2         | 1.49%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 2         | 1.49%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.49%   |
| Intel SSD 660P Series                                                            | 2         | 1.49%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.49%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.75%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.75%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.75%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                 | 1         | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.75%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.75%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.75%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 1         | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.75%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.75%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 86        | 66.15%  |
| NVMe | 28        | 21.54%  |
| RAID | 14        | 10.77%  |
| IDE  | 2         | 1.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 93        | 86.92%  |
| AMD    | 14        | 13.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 3.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 3.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 2.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 2.8%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 2.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.8%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 2.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.87%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.87%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 1.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.87%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.87%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.87%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.87%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.87%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.87%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 1.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.87%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.87%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.93%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.93%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.93%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.93%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.93%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz            | 1         | 0.93%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.93%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.93%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.93%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.93%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.93%   |
| Intel Core i5-6198DU CPU @ 2.30GHz            | 1         | 0.93%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.93%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 1         | 0.93%   |
| Intel Core i5-10310U CPU @ 1.70GHz            | 1         | 0.93%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 0.93%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.93%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 0.93%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 1         | 0.93%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 0.93%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 0.93%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 0.93%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 33.64%  |
| Intel Core i7           | 24        | 22.43%  |
| Intel Core i3           | 17        | 15.89%  |
| AMD Ryzen 5             | 6         | 5.61%   |
| Other                   | 5         | 4.67%   |
| Intel Pentium           | 4         | 3.74%   |
| Intel Core 2 Duo        | 4         | 3.74%   |
| Intel Celeron           | 2         | 1.87%   |
| AMD Ryzen 7             | 2         | 1.87%   |
| Intel Pentium Dual-Core | 1         | 0.93%   |
| Intel Core m3           | 1         | 0.93%   |
| AMD Sempron             | 1         | 0.93%   |
| AMD E2                  | 1         | 0.93%   |
| AMD A8                  | 1         | 0.93%   |
| AMD A6                  | 1         | 0.93%   |
| AMD A4                  | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 56        | 52.34%  |
| 4      | 37        | 34.58%  |
| 6      | 8         | 7.48%   |
| 8      | 4         | 3.74%   |
| 14     | 1         | 0.93%   |
| 1      | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 89        | 83.18%  |
| 1      | 18        | 16.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 106       | 99.07%  |
| Unknown        | 1         | 0.93%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 19.27%  |
| 0x40651    | 8         | 7.34%   |
| 0x806ea    | 7         | 6.42%   |
| 0x806ec    | 6         | 5.5%    |
| 0x306a9    | 6         | 5.5%    |
| 0x206a7    | 6         | 5.5%    |
| 0xa0652    | 5         | 4.59%   |
| 0x406e3    | 5         | 4.59%   |
| 0x906ea    | 4         | 3.67%   |
| 0x706e5    | 3         | 2.75%   |
| 0x506e3    | 3         | 2.75%   |
| 0x306d4    | 3         | 2.75%   |
| 0x20655    | 3         | 2.75%   |
| 0x1067a    | 3         | 2.75%   |
| 0x806e9    | 2         | 1.83%   |
| 0x806c1    | 2         | 1.83%   |
| 0x306c3    | 2         | 1.83%   |
| 0x08600106 | 2         | 1.83%   |
| 0x08108102 | 2         | 1.83%   |
| 0x06006705 | 2         | 1.83%   |
| 0x06006704 | 2         | 1.83%   |
| 0x906a3    | 1         | 0.92%   |
| 0x6fd      | 1         | 0.92%   |
| 0x506c9    | 1         | 0.92%   |
| 0x406c4    | 1         | 0.92%   |
| 0x40661    | 1         | 0.92%   |
| 0x30678    | 1         | 0.92%   |
| 0x20652    | 1         | 0.92%   |
| 0x0a50000c | 1         | 0.92%   |
| 0x0a404101 | 1         | 0.92%   |
| 0x08600104 | 1         | 0.92%   |
| 0x08108109 | 1         | 0.92%   |
| 0x02000032 | 1         | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 25        | 23.36%  |
| Haswell         | 12        | 11.21%  |
| Skylake         | 9         | 8.41%   |
| SandyBridge     | 8         | 7.48%   |
| IvyBridge       | 6         | 5.61%   |
| CometLake       | 6         | 5.61%   |
| Westmere        | 5         | 4.67%   |
| IceLake         | 5         | 4.67%   |
| Penryn          | 4         | 3.74%   |
| Excavator       | 4         | 3.74%   |
| Broadwell       | 4         | 3.74%   |
| Zen+            | 3         | 2.8%    |
| Zen 2           | 3         | 2.8%    |
| TigerLake       | 3         | 2.8%    |
| Silvermont      | 3         | 2.8%    |
| Unknown         | 2         | 1.87%   |
| Zen 3           | 1         | 0.93%   |
| Puma            | 1         | 0.93%   |
| K8 & K10 hybrid | 1         | 0.93%   |
| Goldmont        | 1         | 0.93%   |
| Core            | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 87        | 53.7%   |
| Nvidia | 44        | 27.16%  |
| AMD    | 31        | 19.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 5.49%   |
| Intel UHD Graphics 620                                                                   | 7         | 4.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 3.66%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 3.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 3.05%   |
| Intel HD Graphics 620                                                                    | 5         | 3.05%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 2.44%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 2.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 2.44%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.44%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.83%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 1.83%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.83%   |
| Intel HD Graphics 530                                                                    | 3         | 1.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.83%   |
| AMD Renoir                                                                               | 3         | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.83%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.83%   |
| Nvidia TU117M                                                                            | 2         | 1.22%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.22%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 1.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.22%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.22%   |
| Nvidia GT218M [GeForce G 105M]                                                           | 1         | 0.61%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.61%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.61%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.61%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.61%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.61%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.61%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.61%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.61%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.61%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.61%   |
| Intel HD Graphics 520                                                                    | 1         | 0.61%   |
| Intel HD Graphics 515                                                                    | 1         | 0.61%   |
| Intel HD Graphics 510                                                                    | 1         | 0.61%   |
| Intel HD Graphics 500                                                                    | 1         | 0.61%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.61%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 0.61%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.61%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.61%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.61%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.61%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 35.51%  |
| Intel + Nvidia | 36        | 33.64%  |
| Intel + AMD    | 13        | 12.15%  |
| 1 x AMD        | 10        | 9.35%   |
| AMD + Nvidia   | 6         | 5.61%   |
| 2 x AMD        | 2         | 1.87%   |
| 1 x Nvidia     | 2         | 1.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 83        | 74.77%  |
| Proprietary | 24        | 21.62%  |
| Unknown     | 4         | 3.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 54.13%  |
| 1.01-2.0   | 16        | 14.68%  |
| 0.01-0.5   | 13        | 11.93%  |
| 3.01-4.0   | 11        | 10.09%  |
| 0.51-1.0   | 7         | 6.42%   |
| 2.01-3.0   | 2         | 1.83%   |
| 7.01-8.0   | 1         | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 21.01%  |
| Chimei Innolux          | 24        | 20.17%  |
| BOE                     | 23        | 19.33%  |
| Samsung Electronics     | 17        | 14.29%  |
| LG Display              | 14        | 11.76%  |
| Hewlett-Packard         | 3         | 2.52%   |
| Chi Mei Optoelectronics | 3         | 2.52%   |
| PANDA                   | 2         | 1.68%   |
| Packard Bell            | 1         | 0.84%   |
| LG Philips              | 1         | 0.84%   |
| Lenovo                  | 1         | 0.84%   |
| ITE                     | 1         | 0.84%   |
| Goldstar                | 1         | 0.84%   |
| Dell                    | 1         | 0.84%   |
| BenQ                    | 1         | 0.84%   |
| Acer                    | 1         | 0.84%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 4         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 2.5%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.5%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 2.5%    |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 2         | 1.67%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 1.67%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.67%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.67%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.67%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 340x190mm 15.3-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 1         | 0.83%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.83%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch      | 1         | 0.83%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch           | 1         | 0.83%   |
| LG Display LP156WH2-TLR1 LGD0221 1366x768 340x190mm 15.3-inch         | 1         | 0.83%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| Lenovo LEN G27c-10 LEN66A3 1920x1080 597x336mm 27.0-inch              | 1         | 0.83%   |
| ITE DP2VGA V168 ITE6512 1680x1050 600x340mm 27.2-inch                 | 1         | 0.83%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch           | 1         | 0.83%   |
| Hewlett-Packard 24o HPN337C 1920x1080 530x300mm 24.0-inch             | 1         | 0.83%   |
| Hewlett-Packard 24es HWP3320 1920x1080 527x296mm 23.8-inch            | 1         | 0.83%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                 | 1         | 0.83%   |
| Dell E2418HN DELA105 1920x1080 527x296mm 23.8-inch                    | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1733 1600x900 382x215mm 17.3-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch      | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1524 1366x768 344x193mm 15.5-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 49        | 44.14%  |
| 1366x768 (WXGA)  | 48        | 43.24%  |
| 1600x900 (HD+)   | 5         | 4.5%    |
| 3840x2160 (4K)   | 3         | 2.7%    |
| 1280x800 (WXGA)  | 2         | 1.8%    |
| 3840x1100        | 1         | 0.9%    |
| 2560x1440 (QHD)  | 1         | 0.9%    |
| 1440x900 (WXGA+) | 1         | 0.9%    |
| 1280x1024 (SXGA) | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 80        | 67.23%  |
| 17     | 8         | 6.72%   |
| 14     | 7         | 5.88%   |
| 13     | 7         | 5.88%   |
| 21     | 6         | 5.04%   |
| 24     | 4         | 3.36%   |
| 27     | 2         | 1.68%   |
| 31     | 1         | 0.84%   |
| 23     | 1         | 0.84%   |
| 20     | 1         | 0.84%   |
| 12     | 1         | 0.84%   |
| 11     | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 90        | 76.92%  |
| 351-400     | 8         | 6.84%   |
| 501-600     | 7         | 5.98%   |
| 401-500     | 7         | 5.98%   |
| 201-300     | 4         | 3.42%   |
| 601-700     | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 98        | 94.23%  |
| 16/10 | 4         | 3.85%   |
| 5/4   | 1         | 0.96%   |
| 3.40  | 1         | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 80        | 67.23%  |
| 81-90          | 11        | 9.24%   |
| 201-250        | 11        | 9.24%   |
| 121-130        | 5         | 4.2%    |
| 71-80          | 2         | 1.68%   |
| 51-60          | 2         | 1.68%   |
| 301-350        | 2         | 1.68%   |
| 131-140        | 2         | 1.68%   |
| 61-70          | 1         | 0.84%   |
| 351-500        | 1         | 0.84%   |
| 151-200        | 1         | 0.84%   |
| 141-150        | 1         | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 50        | 43.1%   |
| 121-160       | 42        | 36.21%  |
| 51-100        | 18        | 15.52%  |
| 161-240       | 3         | 2.59%   |
| More than 240 | 2         | 1.72%   |
| 1-50          | 1         | 0.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 86        | 78.9%   |
| 2     | 18        | 16.51%  |
| 0     | 5         | 4.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 79        | 43.65%  |
| Intel                             | 40        | 22.1%   |
| Qualcomm Atheros                  | 28        | 15.47%  |
| Broadcom                          | 13        | 7.18%   |
| Broadcom Limited                  | 5         | 2.76%   |
| Ralink                            | 3         | 1.66%   |
| Ralink Technology                 | 2         | 1.1%    |
| MediaTek                          | 2         | 1.1%    |
| D-Link                            | 2         | 1.1%    |
| Sierra Wireless                   | 1         | 0.55%   |
| OPPO Electronics                  | 1         | 0.55%   |
| Marvell Technology Group          | 1         | 0.55%   |
| ICS Advent                        | 1         | 0.55%   |
| Huawei Technologies               | 1         | 0.55%   |
| Ericsson Business Mobile Networks | 1         | 0.55%   |
| D-Link System                     | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 53        | 24.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 10.23%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 4.19%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 3.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 2.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.4%    |
| Intel Wireless 8265 / 8275                                        | 3         | 1.4%    |
| Intel WiFi Link 5100                                              | 3         | 1.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.93%   |
| Intel Wireless 8260                                               | 2         | 0.93%   |
| Intel Wireless 7265                                               | 2         | 0.93%   |
| Intel Wireless 7260                                               | 2         | 0.93%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.93%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.93%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 0.93%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.93%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.93%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.93%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.93%   |
| Sierra Wireless EM7455                                            | 1         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.47%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.47%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.47%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.47%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.47%   |
| OPPO 9R                                                           | 1         | 0.47%   |
| MediaTek WLAN controller                                          | 1         | 0.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.47%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.47%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.47%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.47%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 0.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.47%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 0.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 39        | 33.33%  |
| Qualcomm Atheros                  | 26        | 22.22%  |
| Realtek Semiconductor             | 25        | 21.37%  |
| Broadcom                          | 10        | 8.55%   |
| Broadcom Limited                  | 5         | 4.27%   |
| Ralink                            | 3         | 2.56%   |
| Ralink Technology                 | 2         | 1.71%   |
| MediaTek                          | 2         | 1.71%   |
| D-Link                            | 2         | 1.71%   |
| Sierra Wireless                   | 1         | 0.85%   |
| Ericsson Business Mobile Networks | 1         | 0.85%   |
| D-Link System                     | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 10        | 8.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 9         | 7.63%   |
| Broadcom BCM43142 802.11b/g/n                                        | 7         | 5.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 6         | 5.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 6         | 5.08%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 6         | 5.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 5         | 4.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 4         | 3.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 4         | 3.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 2.54%   |
| Intel Wireless 8265 / 8275                                           | 3         | 2.54%   |
| Intel WiFi Link 5100                                                 | 3         | 2.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 2         | 1.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 1.69%   |
| Intel Wireless 8260                                                  | 2         | 1.69%   |
| Intel Wireless 7265                                                  | 2         | 1.69%   |
| Intel Wireless 7260                                                  | 2         | 1.69%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 1.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 2         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 1.69%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 2         | 1.69%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 1.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                            | 2         | 1.69%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 2         | 1.69%   |
| Sierra Wireless EM7455                                               | 1         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1         | 0.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1         | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1         | 0.85%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter             | 1         | 0.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1         | 0.85%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 0.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1         | 0.85%   |
| MediaTek WLAN controller                                             | 1         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1         | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 0.85%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                        | 1         | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 1         | 0.85%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 1         | 0.85%   |
| Ericsson Business Mobile Networks N5321 gw                           | 1         | 0.85%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1         | 0.85%   |
| Broadcom Limited BCM43142 802.11b/g/n                                | 1         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 76        | 78.35%  |
| Intel                    | 11        | 11.34%  |
| Qualcomm Atheros         | 3         | 3.09%   |
| Broadcom                 | 3         | 3.09%   |
| OPPO Electronics         | 1         | 1.03%   |
| Marvell Technology Group | 1         | 1.03%   |
| ICS Advent               | 1         | 1.03%   |
| Huawei Technologies      | 1         | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 53        | 54.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 22.68%  |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.06%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 2.06%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 2.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.03%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.03%   |
| OPPO 9R                                                           | 1         | 1.03%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.03%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.03%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.03%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.03%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.03%   |
| Huawei HUAWEI                                                     | 1         | 1.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 107       | 52.97%  |
| Ethernet | 95        | 47.03%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 89        | 80.91%  |
| Ethernet | 21        | 19.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 93        | 86.11%  |
| 1     | 15        | 13.89%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 33.68%  |
| Realtek Semiconductor           | 19        | 20%     |
| Qualcomm Atheros Communications | 17        | 17.89%  |
| Lite-On Technology              | 8         | 8.42%   |
| Broadcom                        | 6         | 6.32%   |
| IMC Networks                    | 4         | 4.21%   |
| Foxconn / Hon Hai               | 3         | 3.16%   |
| Ralink                          | 2         | 2.11%   |
| Toshiba                         | 1         | 1.05%   |
| Realtek                         | 1         | 1.05%   |
| Hewlett-Packard                 | 1         | 1.05%   |
| Dell                            | 1         | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 13        | 13.68%  |
| Intel Bluetooth wireless interface               | 12        | 12.63%  |
| Intel AX201 Bluetooth                            | 12        | 12.63%  |
| Qualcomm Atheros  Bluetooth Device               | 10        | 10.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 6         | 6.32%   |
| Realtek  Bluetooth 4.2 Adapter                   | 4         | 4.21%   |
| Qualcomm Atheros AR3011 Bluetooth                | 4         | 4.21%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device     | 3         | 3.16%   |
| Broadcom BCM43142A0 Bluetooth 4.0                | 3         | 3.16%   |
| Realtek RTL8723B Bluetooth                       | 2         | 2.11%   |
| Ralink RT3290 Bluetooth                          | 2         | 2.11%   |
| Lite-On Bluetooth Device                         | 2         | 2.11%   |
| IMC Networks Wireless_Device                     | 2         | 2.11%   |
| IMC Networks Bluetooth Radio                     | 2         | 2.11%   |
| Foxconn / Hon Hai Bluetooth Device               | 2         | 2.11%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR             | 2         | 2.11%   |
| Toshiba Bluetooth USB Host Controller            | 1         | 1.05%   |
| Realtek Bluetooth Radio                          | 1         | 1.05%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 1.05%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 1.05%   |
| Lite-On BCM43142A0                               | 1         | 1.05%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 1.05%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth    | 1         | 1.05%   |
| Dell DW375 Bluetooth Module                      | 1         | 1.05%   |
| Broadcom BCM43142 Bluetooth 4.0                  | 1         | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 93        | 69.4%   |
| Nvidia                    | 20        | 14.93%  |
| AMD                       | 18        | 13.43%  |
| Sennheiser Communications | 1         | 0.75%   |
| JMTek                     | 1         | 0.75%   |
| C-Media Electronics       | 1         | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 11.54%  |
| Intel 8 Series HD Audio Controller                                                                | 9         | 5.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 5.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 5.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 5.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 3.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 3.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 3.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.21%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 2.56%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.56%   |
| AMD High Definition Audio Controller                                                              | 4         | 2.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.92%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.28%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.28%   |
| Sennheiser Communications Headset [PC 8]                                                          | 1         | 0.64%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.64%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.64%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.64%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.64%   |
| Nvidia Audio device                                                                               | 1         | 0.64%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.64%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.64%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 0.64%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.64%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.64%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 0.64%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 32.18%  |
| SK hynix            | 16        | 18.39%  |
| Micron Technology   | 9         | 10.34%  |
| Team                | 7         | 8.05%   |
| A-DATA Technology   | 6         | 6.9%    |
| Crucial             | 4         | 4.6%    |
| Unknown             | 3         | 3.45%   |
| Nanya Technology    | 3         | 3.45%   |
| Kingston            | 3         | 3.45%   |
| Toshiba             | 2         | 2.3%    |
| Ramaxel Technology  | 2         | 2.3%    |
| Elpida              | 2         | 2.3%    |
| Hikvision           | 1         | 1.15%   |
| ASint Technology    | 1         | 1.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 3         | 3.19%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s           | 3         | 3.19%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                     | 3         | 3.19%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s              | 2         | 2.13%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s               | 2         | 2.13%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s            | 2         | 2.13%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 2         | 2.13%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s           | 2         | 2.13%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s        | 2         | 2.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s        | 2         | 2.13%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 2.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 2.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 2.13%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s            | 2         | 2.13%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                  | 1         | 1.06%   |
| Unknown RAM Module 4096MB SODIMM DDR3                           | 1         | 1.06%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                   | 1         | 1.06%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s           | 1         | 1.06%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s           | 1         | 1.06%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s           | 1         | 1.06%   |
| Team RAM TEAMGROUP-SD3-1600 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.06%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s                     | 1         | 1.06%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.06%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 1.06%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s          | 1         | 1.06%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 1.06%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.06%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 1         | 1.06%   |
| SK hynix RAM HMA81GS6MFR8N-TF 8192MB SODIMM DDR4 2133MT/s       | 1         | 1.06%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s          | 1         | 1.06%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.06%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s        | 1         | 1.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.06%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.06%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 1.06%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s           | 1         | 1.06%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s           | 1         | 1.06%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s              | 1         | 1.06%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB SODIMM LPDDR4 2400MT/s          | 1         | 1.06%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s         | 1         | 1.06%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s       | 1         | 1.06%   |
| Nanya RAM NT8GA64D88CX3S-JR 8GB SODIMM DDR4 3200MT/s            | 1         | 1.06%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.06%   |
| Micron RAM Module 4096MB SODIMM DDR4 3200MT/s                   | 1         | 1.06%   |
| Micron RAM L1G32D4PG107WT:B 8192MB Row Of Chips LPDDR3 1867MT/s | 1         | 1.06%   |
| Micron RAM 8KTF51264HZ-1G9N1 4096MB SODIMM DDR3 1867MT/s        | 1         | 1.06%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s           | 1         | 1.06%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s           | 1         | 1.06%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s            | 1         | 1.06%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s           | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 42        | 60%     |
| DDR3   | 18        | 25.71%  |
| DDR2   | 4         | 5.71%   |
| SDRAM  | 2         | 2.86%   |
| LPDDR4 | 2         | 2.86%   |
| LPDDR3 | 1         | 1.43%   |
| DDR5   | 1         | 1.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 66        | 94.29%  |
| Row Of Chips | 3         | 4.29%   |
| Chip         | 1         | 1.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 32        | 39.51%  |
| 8192  | 28        | 34.57%  |
| 16384 | 8         | 9.88%   |
| 2048  | 8         | 9.88%   |
| 32768 | 4         | 4.94%   |
| 1024  | 1         | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 23        | 28.75%  |
| 3200    | 16        | 20%     |
| 1600    | 12        | 15%     |
| 1334    | 7         | 8.75%   |
| 2400    | 5         | 6.25%   |
| 2133    | 3         | 3.75%   |
| 4199    | 2         | 2.5%    |
| 3266    | 2         | 2.5%    |
| 1867    | 2         | 2.5%    |
| 1066    | 2         | 2.5%    |
| 8400    | 1         | 1.25%   |
| 4800    | 1         | 1.25%   |
| 975     | 1         | 1.25%   |
| 800     | 1         | 1.25%   |
| 667     | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

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
| Chicony Electronics                    | 20        | 20.62%  |
| Realtek Semiconductor                  | 15        | 15.46%  |
| IMC Networks                           | 13        | 13.4%   |
| Microdia                               | 8         | 8.25%   |
| Acer                                   | 7         | 7.22%   |
| Suyin                                  | 6         | 6.19%   |
| Sunplus Innovation Technology          | 5         | 5.15%   |
| Lite-On Technology                     | 5         | 5.15%   |
| Syntek                                 | 4         | 4.12%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.12%   |
| Quanta                                 | 3         | 3.09%   |
| Luxvisions Innotech Limited            | 3         | 3.09%   |
| Silicon Motion                         | 1         | 1.03%   |
| Ricoh                                  | 1         | 1.03%   |
| Apple                                  | 1         | 1.03%   |
| Alcor Micro                            | 1         | 1.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 6         | 6.12%   |
| Chicony Integrated Camera                                                  | 5         | 5.1%    |
| Syntek EasyCamera                                                          | 3         | 3.06%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 3.06%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 3         | 3.06%   |
| Realtek USB Camera                                                         | 3         | 3.06%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 3.06%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 3         | 3.06%   |
| Lite-On Integrated Camera                                                  | 3         | 3.06%   |
| IMC Networks Integrated Camera                                             | 3         | 3.06%   |
| Chicony HD WebCam                                                          | 3         | 3.06%   |
| Acer Integrated Camera                                                     | 3         | 3.06%   |
| Suyin HP TrueVision HD                                                     | 2         | 2.04%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 2.04%   |
| Quanta HD WebCam                                                           | 2         | 2.04%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 2.04%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 2         | 2.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 2.04%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 2.04%   |
| Chicony EasyCamera                                                         | 2         | 2.04%   |
| Acer HD Webcam                                                             | 2         | 2.04%   |
| Syntek Integrated Camera                                                   | 1         | 1.02%   |
| Suyin USB 2.0 Camera                                                       | 1         | 1.02%   |
| Suyin HP Integrated Webcam                                                 | 1         | 1.02%   |
| Suyin HD WebCam                                                            | 1         | 1.02%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 1         | 1.02%   |
| Sunplus HD User Facing                                                     | 1         | 1.02%   |
| Sunplus Dell HD Webcam                                                     | 1         | 1.02%   |
| Silicon Motion WebCam SC-13HDL11431N                                       | 1         | 1.02%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 1.02%   |
| Realtek Integrated Webcam_HD                                               | 1         | 1.02%   |
| Realtek Integrated Webcam                                                  | 1         | 1.02%   |
| Realtek HP Webcam                                                          | 1         | 1.02%   |
| Realtek EasyCamera                                                         | 1         | 1.02%   |
| Quanta HP Webcam                                                           | 1         | 1.02%   |
| Microdia Webcam SC-10HDD12636P                                             | 1         | 1.02%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.02%   |
| Microdia HP Webcam                                                         | 1         | 1.02%   |
| Microdia HP Integrated Webcam                                              | 1         | 1.02%   |
| Lite-On TOSHIBA Web Camera - HD                                            | 1         | 1.02%   |
| Lite-On HP HD Camera                                                       | 1         | 1.02%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.02%   |
| IMC Networks HP TrueVision HD Camera                                       | 1         | 1.02%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 1.02%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 1.02%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 1.02%   |
| Chicony TOSHIBA Web Camera                                                 | 1         | 1.02%   |
| Chicony Sony Visual Communication Camera                                   | 1         | 1.02%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 1.02%   |
| Chicony HP Webcam                                                          | 1         | 1.02%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 1         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 1         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 1.02%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 1.02%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 1.02%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.02%   |
| Acer Integrated IR Camera                                                  | 1         | 1.02%   |
| Acer EasyCamera                                                            | 1         | 1.02%   |

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
| 0     | 80        | 68.38%  |
| 1     | 30        | 25.64%  |
| 3     | 4         | 3.42%   |
| 2     | 2         | 1.71%   |
| 4     | 1         | 0.85%   |

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

