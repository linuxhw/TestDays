LMDE 5 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 167

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P7Q57-M DO                  | [897fc61b8c](https://linux-hardware.org/?probe=897fc61b8c) | Apr 30, 2023 |
| ASUSTek       | P7Q57-M DO                  | [4f502dcb59](https://linux-hardware.org/?probe=4f502dcb59) | Apr 30, 2023 |
| Gigabyte      | Q87M-D2H                    | [16279b3c8b](https://linux-hardware.org/?probe=16279b3c8b) | Apr 30, 2023 |
| Medion        | TJ4125                      | [ad46974b2a](https://linux-hardware.org/?probe=ad46974b2a) | Apr 29, 2023 |
| ASRock        | B450M Pro4                  | [7c8260664a](https://linux-hardware.org/?probe=7c8260664a) | Apr 29, 2023 |
| Medion        | TJ4125                      | [8f319cff50](https://linux-hardware.org/?probe=8f319cff50) | Apr 28, 2023 |
| ASRock        | B450M Pro4                  | [831cd8fa39](https://linux-hardware.org/?probe=831cd8fa39) | Apr 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [6503ed5a4c](https://linux-hardware.org/?probe=6503ed5a4c) | Apr 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [5827cd2604](https://linux-hardware.org/?probe=5827cd2604) | Apr 23, 2023 |
| Medion        | TJ4125                      | [faa241e4bc](https://linux-hardware.org/?probe=faa241e4bc) | Apr 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [93a6cb1a8a](https://linux-hardware.org/?probe=93a6cb1a8a) | Apr 22, 2023 |
| Gigabyte      | A520M DS3H                  | [c4b35f2a05](https://linux-hardware.org/?probe=c4b35f2a05) | Apr 16, 2023 |
| Intel         | SHARKBAY                    | [3bb10a5574](https://linux-hardware.org/?probe=3bb10a5574) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d6f8675bc9](https://linux-hardware.org/?probe=d6f8675bc9) | Apr 11, 2023 |
| Intel         | SHARKBAY                    | [4b50be64da](https://linux-hardware.org/?probe=4b50be64da) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | [d041ee40cc](https://linux-hardware.org/?probe=d041ee40cc) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | [2c83dbd3ef](https://linux-hardware.org/?probe=2c83dbd3ef) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | [d1e9eaed8b](https://linux-hardware.org/?probe=d1e9eaed8b) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | [82a96ca347](https://linux-hardware.org/?probe=82a96ca347) | Apr 08, 2023 |
| Gigabyte      | Q87M-D2H                    | [4552b7c999](https://linux-hardware.org/?probe=4552b7c999) | Apr 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [b627db43dd](https://linux-hardware.org/?probe=b627db43dd) | Apr 01, 2023 |
| ASUSTek       | P7P55D                      | [b50f27ad05](https://linux-hardware.org/?probe=b50f27ad05) | Mar 31, 2023 |
| Dell          | 00F82W A02                  | [8bf22304e0](https://linux-hardware.org/?probe=8bf22304e0) | Mar 31, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [b53d1202dc](https://linux-hardware.org/?probe=b53d1202dc) | Mar 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [dd71be113d](https://linux-hardware.org/?probe=dd71be113d) | Mar 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [e5cef530ff](https://linux-hardware.org/?probe=e5cef530ff) | Mar 27, 2023 |
| Gigabyte      | Q87M-D2H                    | [8690ae647e](https://linux-hardware.org/?probe=8690ae647e) | Mar 26, 2023 |
| BESSTAR Te... | TH50                        | [7165e2c0d0](https://linux-hardware.org/?probe=7165e2c0d0) | Mar 21, 2023 |
| Gigabyte      | A520M DS3H                  | [79104099a5](https://linux-hardware.org/?probe=79104099a5) | Mar 20, 2023 |
| Gigabyte      | Q87M-D2H                    | [fb5c67c585](https://linux-hardware.org/?probe=fb5c67c585) | Mar 19, 2023 |
| Gigabyte      | Q87M-D2H                    | [7051e25dc0](https://linux-hardware.org/?probe=7051e25dc0) | Mar 18, 2023 |
| ASRock        | B365M Pro4                  | [e237668eb2](https://linux-hardware.org/?probe=e237668eb2) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [29f50579db](https://linux-hardware.org/?probe=29f50579db) | Mar 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bf2b5490ba](https://linux-hardware.org/?probe=bf2b5490ba) | Mar 15, 2023 |
| Gigabyte      | Z87X-OC Force-CF            | [17deac9c67](https://linux-hardware.org/?probe=17deac9c67) | Mar 12, 2023 |
| SiYW          | V200 Series                 | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| ASUSTek       | PRIME A320M-K               | [93875c7518](https://linux-hardware.org/?probe=93875c7518) | Mar 09, 2023 |
| MSI           | 970A-G46                    | [8c3d20fa95](https://linux-hardware.org/?probe=8c3d20fa95) | Mar 08, 2023 |
| Dell          | 096JG8 A01                  | [fddb284e37](https://linux-hardware.org/?probe=fddb284e37) | Mar 03, 2023 |
| Gigabyte      | Z590 GAMING X               | [d39a85e759](https://linux-hardware.org/?probe=d39a85e759) | Feb 24, 2023 |
| Medion        | MS-7800                     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| Dell          | 0NK70N A03                  | [3da6e11665](https://linux-hardware.org/?probe=3da6e11665) | Feb 18, 2023 |
| ASUSTek       | P7P55D                      | [bcae3260be](https://linux-hardware.org/?probe=bcae3260be) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | [2c98a8340f](https://linux-hardware.org/?probe=2c98a8340f) | Feb 17, 2023 |
| Dell          | 0MF24N A03                  | [e48d83d96d](https://linux-hardware.org/?probe=e48d83d96d) | Feb 15, 2023 |
| Gigabyte      | B450M S2H                   | [20bcead0e8](https://linux-hardware.org/?probe=20bcead0e8) | Feb 11, 2023 |
| HP            | 843C                        | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| Gigabyte      | B450 AORUS M                | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [1985f76677](https://linux-hardware.org/?probe=1985f76677) | Feb 05, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | [6c094e2027](https://linux-hardware.org/?probe=6c094e2027) | Jan 31, 2023 |
| ASUSTek       | P7P55D                      | [981ae95b2a](https://linux-hardware.org/?probe=981ae95b2a) | Jan 31, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [40152faf5b](https://linux-hardware.org/?probe=40152faf5b) | Jan 28, 2023 |
| Intel         | H61M-DS2V                   | [0591a32a07](https://linux-hardware.org/?probe=0591a32a07) | Jan 25, 2023 |
| ASRock        | Z87 Pro3                    | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| Dell          | 0C27VV A01                  | [e43d24d2b6](https://linux-hardware.org/?probe=e43d24d2b6) | Jan 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c5dd2e8482](https://linux-hardware.org/?probe=c5dd2e8482) | Jan 19, 2023 |
| Gigabyte      | H310M S2H                   | [9aec47cbf0](https://linux-hardware.org/?probe=9aec47cbf0) | Jan 12, 2023 |
| Gigabyte      | H310M S2H                   | [b3cccc4043](https://linux-hardware.org/?probe=b3cccc4043) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | [3a9bdd2358](https://linux-hardware.org/?probe=3a9bdd2358) | Jan 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [563d7aaba5](https://linux-hardware.org/?probe=563d7aaba5) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | [db0f184e3f](https://linux-hardware.org/?probe=db0f184e3f) | Jan 11, 2023 |
| Intel         | B75                         | [ec08587a4a](https://linux-hardware.org/?probe=ec08587a4a) | Jan 09, 2023 |
| MSI           | FM2-A55M-E33                | [1ce8a2718b](https://linux-hardware.org/?probe=1ce8a2718b) | Jan 07, 2023 |
| Acer          | Aspire XC-780               | [66823871a5](https://linux-hardware.org/?probe=66823871a5) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | [cb55beafca](https://linux-hardware.org/?probe=cb55beafca) | Dec 30, 2022 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | [938db016a2](https://linux-hardware.org/?probe=938db016a2) | Dec 30, 2022 |
| ASUSTek       | Z170M-PLUS                  | [6b61c9a811](https://linux-hardware.org/?probe=6b61c9a811) | Dec 28, 2022 |
| Gigabyte      | GA-970A-D3                  | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| ASUSTek       | PRIME B350M-A               | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| Dell          | 0C27VV A01                  | [91c790d54e](https://linux-hardware.org/?probe=91c790d54e) | Dec 18, 2022 |
| MSI           | PRO B660M-A DDR4            | [770334f093](https://linux-hardware.org/?probe=770334f093) | Dec 16, 2022 |
| Dell          | 0T1D10 A01                  | [6988ab07fe](https://linux-hardware.org/?probe=6988ab07fe) | Dec 12, 2022 |
| Dell          | 0T1D10 A01                  | [6ec6d4563d](https://linux-hardware.org/?probe=6ec6d4563d) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e810c5c2eb](https://linux-hardware.org/?probe=e810c5c2eb) | Dec 08, 2022 |
| ASUSTek       | P7P55D                      | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| SiYW          | V200 Series                 | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| HP            | 8299                        | [8f6b89bf07](https://linux-hardware.org/?probe=8f6b89bf07) | Nov 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [1ad4dcb28a](https://linux-hardware.org/?probe=1ad4dcb28a) | Nov 22, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d93b2b9778](https://linux-hardware.org/?probe=d93b2b9778) | Nov 21, 2022 |
| MSI           | A320M-A PRO MAX             | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Dell          | 0C27VV A01                  | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| Dell          | 0C27VV A01                  | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| Dell          | 0N826N A03                  | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| MSI           | A320M-A PRO MAX             | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| HP            | 8299                        | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| HP            | 8299                        | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell          | 0D735T A00                  | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI           | B550-A PRO                  | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| AZW           | MINI S                      | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek       | Maximus VI HERO             | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock        | A320M-HDV R4.0              | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell          | 082WXT A01                  | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Gateway       | DX4870                      | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| Digiboard     | NM70-TI                     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Dell          | 0XC837                      | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| MSI           | B360M MORTAR                | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek       | PRIME H610M-E D4            | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell          | 0FJ030                      | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI           | B450I GAMING PLUS AC        | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Pegatron      | 2A9Eh                       | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek       | P8H77-V                     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines     | EL1352G                     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| ASUSTek       | P5K-E                       | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Dell          | 042P49 A00                  | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | P5QPL-AM                    | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| MSI           | B85I                        | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Gigabyte      | H97-Gaming 3                | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| ASRock        | H61M-DGS                    | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS M                | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| HP            | 8433 11                     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Gigabyte      | B450 AORUS M                | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| ASUSTek       | P8H77-M PRO                 | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Dell          | 0XR1GT A00                  | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| Lenovo        | 3731 NOK                    | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| Dell          | 0XR1GT A00                  | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| Acer          | Seawolf                     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Intel         | DQ77MK AAG39642-400         | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| HP            | 339A                        | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Gigabyte      | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| ASRock        | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| ASUSTek       | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Acer          | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| ASUSTek       | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| ASUSTek       | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| HP            | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.0-21-amd64          | 28       | 24.14%  |
| 5.10.0-12-amd64          | 18       | 15.52%  |
| 5.10.0-20-amd64          | 12       | 10.34%  |
| 5.10.0-17-amd64          | 11       | 9.48%   |
| 5.10.0-14-amd64          | 10       | 8.62%   |
| 5.10.0-13-amd64          | 10       | 8.62%   |
| 5.10.0-18-amd64          | 9        | 7.76%   |
| 5.10.0-19-amd64          | 8        | 6.9%    |
| 5.10.0-15-amd64          | 3        | 2.59%   |
| 5.10.0-16-amd64          | 2        | 1.72%   |
| 6.1.0-0.deb11.5-amd64    | 1        | 0.86%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1        | 0.86%   |
| 5.19.0-0.deb11.2-amd64   | 1        | 0.86%   |
| 5.10.0-22-amd64          | 1        | 0.86%   |
| 5.10.0-13-686            | 1        | 0.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 104      | 97.2%   |
| 6.1.0   | 1        | 0.93%   |
| 6.0.2   | 1        | 0.93%   |
| 5.19.0  | 1        | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 104      | 97.2%   |
| 6.1     | 1        | 0.93%   |
| 6.0     | 1        | 0.93%   |
| 5.19    | 1        | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 105      | 99.06%  |
| i686   | 1        | 0.94%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 92       | 85.98%  |
| Cinnamon   | 11       | 10.28%  |
| MATE       | 2        | 1.87%   |
| XFCE       | 1        | 0.93%   |
| KDE5       | 1        | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 106      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 69       | 65.09%  |
| LightDM | 35       | 33.02%  |
| SDDM    | 1        | 0.94%   |
| GDM     | 1        | 0.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 40       | 37.74%  |
| de_DE | 16       | 15.09%  |
| ru_RU | 8        | 7.55%   |
| pt_BR | 8        | 7.55%   |
| it_IT | 5        | 4.72%   |
| fr_FR | 4        | 3.77%   |
| es_ES | 3        | 2.83%   |
| en_GB | 3        | 2.83%   |
| en_CA | 3        | 2.83%   |
| sv_SE | 2        | 1.89%   |
| pl_PL | 2        | 1.89%   |
| fr_CA | 2        | 1.89%   |
| sk_SK | 1        | 0.94%   |
| ru_UA | 1        | 0.94%   |
| it_CH | 1        | 0.94%   |
| fr_BE | 1        | 0.94%   |
| es_NI | 1        | 0.94%   |
| en_ZA | 1        | 0.94%   |
| en_AU | 1        | 0.94%   |
| de_AT | 1        | 0.94%   |
| cs_CZ | 1        | 0.94%   |
| ar_EG | 1        | 0.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 58       | 54.72%  |
| EFI  | 48       | 45.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 98       | 92.45%  |
| Tmpfs   | 3        | 2.83%   |
| Btrfs   | 3        | 2.83%   |
| Overlay | 2        | 1.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 70       | 66.04%  |
| GPT     | 23       | 21.7%   |
| MBR     | 13       | 12.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 88.68%  |
| Yes       | 12       | 11.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 85.85%  |
| Yes       | 15       | 14.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 25       | 23.58%  |
| Gigabyte Technology | 18       | 16.98%  |
| Dell                | 14       | 13.21%  |
| MSI                 | 12       | 11.32%  |
| Hewlett-Packard     | 6        | 5.66%   |
| ASRock              | 6        | 5.66%   |
| Intel               | 4        | 3.77%   |
| Acer                | 4        | 3.77%   |
| Lenovo              | 3        | 2.83%   |
| Medion              | 2        | 1.89%   |
| Fujitsu             | 2        | 1.89%   |
| SiYW                | 1        | 0.94%   |
| Samsung Electronics | 1        | 0.94%   |
| Pegatron            | 1        | 0.94%   |
| Gateway             | 1        | 0.94%   |
| Foxconn             | 1        | 0.94%   |
| eMachines           | 1        | 0.94%   |
| Digiboard           | 1        | 0.94%   |
| BESSTAR Tech        | 1        | 0.94%   |
| AZW                 | 1        | 0.94%   |
| ADVANSUS            | 1        | 0.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Gigabyte B450 AORUS M               | 2        | 1.89%   |
| ASUS PRIME B350M-A                  | 2        | 1.89%   |
| SiYW V200 Series                    | 1        | 0.94%   |
| Samsung DeskTop System              | 1        | 0.94%   |
| Pegatron Pro 3015 Microtower PC     | 1        | 0.94%   |
| MSI MS-7D54                         | 1        | 0.94%   |
| MSI MS-7C52                         | 1        | 0.94%   |
| MSI MS-7B79                         | 1        | 0.94%   |
| MSI MS-7B23                         | 1        | 0.94%   |
| MSI MS-7B17                         | 1        | 0.94%   |
| MSI MS-7A40                         | 1        | 0.94%   |
| MSI MS-7984                         | 1        | 0.94%   |
| MSI MS-7977                         | 1        | 0.94%   |
| MSI MS-7974                         | 1        | 0.94%   |
| MSI MS-7851                         | 1        | 0.94%   |
| MSI MS-7721                         | 1        | 0.94%   |
| MSI MS-7693                         | 1        | 0.94%   |
| Medion S23003                       | 1        | 0.94%   |
| Medion MS-7800                      | 1        | 0.94%   |
| Lenovo V55t-15ARE 11KJ0036TX        | 1        | 0.94%   |
| Lenovo ThinkCentre M92p 3238E9U     | 1        | 0.94%   |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1        | 0.94%   |
| Intel SHARKBAY                      | 1        | 0.94%   |
| Intel H61M-DS2V                     | 1        | 0.94%   |
| Intel DQ77MK AAG39642-400           | 1        | 0.94%   |
| Intel B75                           | 1        | 0.94%   |
| HP Z820 Workstation                 | 1        | 0.94%   |
| HP Z600 Workstation                 | 1        | 0.94%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 0.94%   |
| HP EliteDesk 800 G3 SFF             | 1        | 0.94%   |
| HP Compaq Pro 6300 SFF              | 1        | 0.94%   |
| HP 290 G2 MT Business PC            | 1        | 0.94%   |
| Gigabyte Z87X-OC Force              | 1        | 0.94%   |
| Gigabyte Z68A-D3H-B3                | 1        | 0.94%   |
| Gigabyte Z590 GAMING X              | 1        | 0.94%   |
| Gigabyte X570 AORUS ULTRA           | 1        | 0.94%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 1        | 0.94%   |
| Gigabyte Q87M-D2H                   | 1        | 0.94%   |
| Gigabyte H110M-S2H                  | 1        | 0.94%   |
| Gigabyte GA-970A-D3                 | 1        | 0.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 7        | 6.6%    |
| Dell Precision       | 4        | 3.77%   |
| Dell OptiPlex        | 4        | 3.77%   |
| Gigabyte B450        | 3        | 2.83%   |
| ASUS ROG             | 3        | 2.83%   |
| Acer Aspire          | 3        | 2.83%   |
| Lenovo ThinkCentre   | 2        | 1.89%   |
| Gigabyte B450M       | 2        | 1.89%   |
| Dell Vostro          | 2        | 1.89%   |
| Dell Inspiron        | 2        | 1.89%   |
| SiYW V200            | 1        | 0.94%   |
| Samsung DeskTop      | 1        | 0.94%   |
| Pegatron Pro         | 1        | 0.94%   |
| MSI MS-7D54          | 1        | 0.94%   |
| MSI MS-7C52          | 1        | 0.94%   |
| MSI MS-7B79          | 1        | 0.94%   |
| MSI MS-7B23          | 1        | 0.94%   |
| MSI MS-7B17          | 1        | 0.94%   |
| MSI MS-7A40          | 1        | 0.94%   |
| MSI MS-7984          | 1        | 0.94%   |
| MSI MS-7977          | 1        | 0.94%   |
| MSI MS-7974          | 1        | 0.94%   |
| MSI MS-7851          | 1        | 0.94%   |
| MSI MS-7721          | 1        | 0.94%   |
| MSI MS-7693          | 1        | 0.94%   |
| Medion S23003        | 1        | 0.94%   |
| Medion MS-7800       | 1        | 0.94%   |
| Lenovo V55t-15ARE    | 1        | 0.94%   |
| Intel SHARKBAY       | 1        | 0.94%   |
| Intel H61M-DS2V      | 1        | 0.94%   |
| Intel DQ77MK         | 1        | 0.94%   |
| Intel B75            | 1        | 0.94%   |
| HP Z820              | 1        | 0.94%   |
| HP Z600              | 1        | 0.94%   |
| HP Pavilion          | 1        | 0.94%   |
| HP EliteDesk         | 1        | 0.94%   |
| HP Compaq            | 1        | 0.94%   |
| HP 290               | 1        | 0.94%   |
| Gigabyte Z87X-OC     | 1        | 0.94%   |
| Gigabyte Z68A-D3H-B3 | 1        | 0.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 22       | 20.75%  |
| 2012 | 15       | 14.15%  |
| 2021 | 7        | 6.6%    |
| 2017 | 7        | 6.6%    |
| 2015 | 7        | 6.6%    |
| 2009 | 7        | 6.6%    |
| 2013 | 6        | 5.66%   |
| 2019 | 5        | 4.72%   |
| 2011 | 5        | 4.72%   |
| 2010 | 5        | 4.72%   |
| 2022 | 4        | 3.77%   |
| 2016 | 4        | 3.77%   |
| 2020 | 3        | 2.83%   |
| 2007 | 3        | 2.83%   |
| 2006 | 3        | 2.83%   |
| 2014 | 2        | 1.89%   |
| 2008 | 1        | 0.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 106      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 104      | 97.2%   |
| Enabled  | 3        | 2.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 106      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 26       | 24.07%  |
| 8.01-16.0       | 22       | 20.37%  |
| 32.01-64.0      | 20       | 18.52%  |
| 4.01-8.0        | 18       | 16.67%  |
| 3.01-4.0        | 12       | 11.11%  |
| 1.01-2.0        | 4        | 3.7%    |
| 24.01-32.0      | 3        | 2.78%   |
| More than 256.0 | 1        | 0.93%   |
| 64.01-256.0     | 1        | 0.93%   |
| 0.51-1.0        | 1        | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 42       | 36.84%  |
| 2.01-3.0   | 34       | 29.82%  |
| 4.01-8.0   | 16       | 14.04%  |
| 3.01-4.0   | 12       | 10.53%  |
| 0.51-1.0   | 5        | 4.39%   |
| 8.01-16.0  | 4        | 3.51%   |
| 24.01-32.0 | 1        | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 45.79%  |
| 2      | 22       | 20.56%  |
| 3      | 18       | 16.82%  |
| 4      | 9        | 8.41%   |
| 5      | 6        | 5.61%   |
| 6      | 3        | 2.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 57.01%  |
| Yes       | 46       | 42.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 105      | 99.06%  |
| No        | 1        | 0.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 53.27%  |
| Yes       | 50       | 46.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 70.75%  |
| Yes       | 31       | 29.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 26       | 24.53%  |
| Germany      | 17       | 16.04%  |
| Russia       | 9        | 8.49%   |
| Brazil       | 9        | 8.49%   |
| Italy        | 7        | 6.6%    |
| Canada       | 6        | 5.66%   |
| France       | 5        | 4.72%   |
| UK           | 3        | 2.83%   |
| Sweden       | 3        | 2.83%   |
| Spain        | 3        | 2.83%   |
| South Africa | 2        | 1.89%   |
| Poland       | 2        | 1.89%   |
| Australia    | 2        | 1.89%   |
| Venezuela    | 1        | 0.94%   |
| Ukraine      | 1        | 0.94%   |
| Turkey       | 1        | 0.94%   |
| Slovakia     | 1        | 0.94%   |
| Nicaragua    | 1        | 0.94%   |
| Netherlands  | 1        | 0.94%   |
| Mexico       | 1        | 0.94%   |
| Latvia       | 1        | 0.94%   |
| Kazakhstan   | 1        | 0.94%   |
| Bolivia      | 1        | 0.94%   |
| Belgium      | 1        | 0.94%   |
| Austria      | 1        | 0.94%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Montreal                 | 2        | 1.85%   |
| Melbourne                | 2        | 1.85%   |
| Gruenenplan              | 2        | 1.85%   |
| Frankfurt am Main        | 2        | 1.85%   |
| Berlin                   | 2        | 1.85%   |
| Washington               | 1        | 0.93%   |
| Volta Redonda            | 1        | 0.93%   |
| Vitória da Conquista    | 1        | 0.93%   |
| Vincennes                | 1        | 0.93%   |
| Vicente Guerrero         | 1        | 0.93%   |
| Varese                   | 1        | 0.93%   |
| Ulyanovsk                | 1        | 0.93%   |
| Trieste                  | 1        | 0.93%   |
| Toronto                  | 1        | 0.93%   |
| Tolyatti                 | 1        | 0.93%   |
| Toledo                   | 1        | 0.93%   |
| Toccoa                   | 1        | 0.93%   |
| Tacoma                   | 1        | 0.93%   |
| Stockelsdorf             | 1        | 0.93%   |
| Stockbridge              | 1        | 0.93%   |
| Spruce Grove             | 1        | 0.93%   |
| Sollentuna               | 1        | 0.93%   |
| Solingen                 | 1        | 0.93%   |
| Schruns                  | 1        | 0.93%   |
| Sao Paulo                | 1        | 0.93%   |
| Sao Lourenço            | 1        | 0.93%   |
| Sant Feliu de Llobregat  | 1        | 0.93%   |
| San Antonio de Los Altos | 1        | 0.93%   |
| San Antonio              | 1        | 0.93%   |
| Rome                     | 1        | 0.93%   |
| Riga                     | 1        | 0.93%   |
| Reynoldsburg             | 1        | 0.93%   |
| Rennes                   | 1        | 0.93%   |
| Raschau                  | 1        | 0.93%   |
| Queensbury               | 1        | 0.93%   |
| Prestatyn                | 1        | 0.93%   |
| Porto Uniao              | 1        | 0.93%   |
| Porto Alegre             | 1        | 0.93%   |
| Ponteareas               | 1        | 0.93%   |
| Piaseczno                | 1        | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 34       | 58     | 18.38%  |
| Seagate                   | 32       | 45     | 17.3%   |
| Samsung Electronics       | 28       | 56     | 15.14%  |
| Kingston                  | 15       | 21     | 8.11%   |
| Crucial                   | 11       | 13     | 5.95%   |
| Toshiba                   | 9        | 11     | 4.86%   |
| Sandisk                   | 7        | 7      | 3.78%   |
| Hitachi                   | 5        | 6      | 2.7%    |
| SPCC                      | 3        | 3      | 1.62%   |
| SK hynix                  | 3        | 4      | 1.62%   |
| China                     | 3        | 3      | 1.62%   |
| Silicon Motion            | 2        | 2      | 1.08%   |
| PNY                       | 2        | 2      | 1.08%   |
| Phison                    | 2        | 2      | 1.08%   |
| Apple                     | 2        | 2      | 1.08%   |
| A-DATA Technology         | 2        | 2      | 1.08%   |
| XrayDisk                  | 1        | 2      | 0.54%   |
| WALRAM                    | 1        | 1      | 0.54%   |
| Unknown                   | 1        | 1      | 0.54%   |
| Transcend                 | 1        | 2      | 0.54%   |
| TGT                       | 1        | 1      | 0.54%   |
| TakeMS                    | 1        | 1      | 0.54%   |
| Phison Electronics        | 1        | 1      | 0.54%   |
| Patriot                   | 1        | 1      | 0.54%   |
| OCZ-VERTEX                | 1        | 1      | 0.54%   |
| OCZ                       | 1        | 1      | 0.54%   |
| Netac                     | 1        | 1      | 0.54%   |
| Micron/Crucial Technology | 1        | 1      | 0.54%   |
| Micron Technology         | 1        | 1      | 0.54%   |
| Intenso                   | 1        | 1      | 0.54%   |
| Intel                     | 1        | 1      | 0.54%   |
| Hewlett-Packard           | 1        | 1      | 0.54%   |
| GOODRAM                   | 1        | 1      | 0.54%   |
| Gigabyte Technology       | 1        | 2      | 0.54%   |
| Emtec                     | 1        | 1      | 0.54%   |
| BR                        | 1        | 1      | 0.54%   |
| ASMedia                   | 1        | 1      | 0.54%   |
| Apacer                    | 1        | 1      | 0.54%   |
| ADATA Technology          | 1        | 1      | 0.54%   |
| 2.5''                     | 1        | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                         | 6        | 2.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4        | 1.85%   |
| Kingston SA400S37240G 240GB SSD                   | 4        | 1.85%   |
| Kingston SA400S37120G 120GB SSD                   | 4        | 1.85%   |
| Samsung SSD 970 EVO 500GB                         | 3        | 1.39%   |
| Samsung SSD 850 EVO 500GB                         | 3        | 1.39%   |
| Crucial CT480BX500SSD1 480GB                      | 3        | 1.39%   |
| WDC WD3003FZEX-00Z4SA0 3TB                        | 2        | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2        | 0.93%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 2        | 0.93%   |
| Seagate ST500DM002-1BD142 500GB                   | 2        | 0.93%   |
| Seagate ST3320418AS 320GB                         | 2        | 0.93%   |
| Seagate ST3250318AS 250GB                         | 2        | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB                    | 2        | 0.93%   |
| Seagate ST1000LM048-2E7172 1TB                    | 2        | 0.93%   |
| Seagate ST1000DM003-1ER162 1TB                    | 2        | 0.93%   |
| Seagate ST1000DM003-1CH162 1TB                    | 2        | 0.93%   |
| Samsung SSD 980 PRO 1TB                           | 2        | 0.93%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB            | 2        | 0.93%   |
| Samsung NVMe SSD Drive 500GB                      | 2        | 0.93%   |
| Kingston SA400S37480G 480GB SSD                   | 2        | 0.93%   |
| XrayDisk 480GB                                    | 1        | 0.46%   |
| XrayDisk 1TB                                      | 1        | 0.46%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                  | 1        | 0.46%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                  | 1        | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 1        | 0.46%   |
| WDC WD60EZAZ-00ZGHB0 6TB                          | 1        | 0.46%   |
| WDC WD60EFAX-68SHWN0 6TB                          | 1        | 0.46%   |
| WDC WD5000LPSX-08A6W 500GB                        | 1        | 0.46%   |
| WDC WD5000BEVT-22ZAT0 500GB                       | 1        | 0.46%   |
| WDC WD5000AZLX-08K2TA0 500GB                      | 1        | 0.46%   |
| WDC WD5000AAKX-75U6AA0 500GB                      | 1        | 0.46%   |
| WDC WD5000AAKX-22ERMA0 500GB                      | 1        | 0.46%   |
| WDC WD5000AAKX-08U6AA0 500GB                      | 1        | 0.46%   |
| WDC WD5000AAKX-00ERMA0 500GB                      | 1        | 0.46%   |
| WDC WD5000AAJS-00TKA0 500GB                       | 1        | 0.46%   |
| WDC WD40EZRZ-00GXCB0 4TB                          | 1        | 0.46%   |
| WDC WD40EZAZ-00SF3B0 4TB                          | 1        | 0.46%   |
| WDC WD3200AAJS-22B4A0 320GB                       | 1        | 0.46%   |
| WDC WD30EZRZ-00Z5HB0 3TB                          | 1        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 32       | 55     | 36.78%  |
| Seagate             | 32       | 44     | 36.78%  |
| Toshiba             | 8        | 10     | 9.2%    |
| Samsung Electronics | 6        | 9      | 6.9%    |
| Hitachi             | 5        | 6      | 5.75%   |
| Unknown             | 1        | 1      | 1.15%   |
| Intenso             | 1        | 1      | 1.15%   |
| ASMedia             | 1        | 1      | 1.15%   |
| Apple               | 1        | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 26     | 22.67%  |
| Kingston            | 12       | 18     | 16%     |
| Crucial             | 10       | 12     | 13.33%  |
| SanDisk             | 5        | 5      | 6.67%   |
| WDC                 | 3        | 3      | 4%      |
| SPCC                | 3        | 3      | 4%      |
| China               | 3        | 3      | 4%      |
| SK hynix            | 2        | 2      | 2.67%   |
| PNY                 | 2        | 2      | 2.67%   |
| A-DATA Technology   | 2        | 2      | 2.67%   |
| Transcend           | 1        | 2      | 1.33%   |
| Toshiba             | 1        | 1      | 1.33%   |
| TakeMS              | 1        | 1      | 1.33%   |
| Phison              | 1        | 1      | 1.33%   |
| Patriot             | 1        | 1      | 1.33%   |
| OCZ-VERTEX          | 1        | 1      | 1.33%   |
| OCZ                 | 1        | 1      | 1.33%   |
| Netac               | 1        | 1      | 1.33%   |
| Micron Technology   | 1        | 1      | 1.33%   |
| Hewlett-Packard     | 1        | 1      | 1.33%   |
| GOODRAM             | 1        | 1      | 1.33%   |
| Gigabyte Technology | 1        | 2      | 1.33%   |
| Apple               | 1        | 1      | 1.33%   |
| Apacer              | 1        | 1      | 1.33%   |
| 2.5''               | 1        | 1      | 1.33%   |
| Unknown             | 1        | 2      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 69       | 128    | 42.86%  |
| SSD     | 62       | 95     | 38.51%  |
| NVMe    | 25       | 37     | 15.53%  |
| Unknown | 5        | 6      | 3.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 99       | 217    | 74.44%  |
| NVMe | 25       | 37     | 18.8%   |
| SAS  | 9        | 12     | 6.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 77       | 127    | 56.2%   |
| 0.51-1.0   | 34       | 59     | 24.82%  |
| 1.01-2.0   | 13       | 15     | 9.49%   |
| 2.01-3.0   | 5        | 10     | 3.65%   |
| 3.01-4.0   | 4        | 7      | 2.92%   |
| 4.01-10.0  | 4        | 5      | 2.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 28       | 25.93%  |
| 251-500        | 25       | 23.15%  |
| 1001-2000      | 17       | 15.74%  |
| 501-1000       | 15       | 13.89%  |
| More than 3000 | 8        | 7.41%   |
| 2001-3000      | 6        | 5.56%   |
| 1-20           | 5        | 4.63%   |
| 51-100         | 3        | 2.78%   |
| 21-50          | 1        | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 36       | 32.73%  |
| 21-50          | 14       | 12.73%  |
| 101-250        | 14       | 12.73%  |
| 251-500        | 13       | 11.82%  |
| 51-100         | 13       | 11.82%  |
| 501-1000       | 9        | 8.18%   |
| 1001-2000      | 7        | 6.36%   |
| More than 3000 | 2        | 1.82%   |
| 2001-3000      | 2        | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1        | 1      | 20%     |
| Seagate ST3250318AS 250GB       | 1        | 1      | 20%     |
| Seagate ST2000DX001-1CM164 2TB  | 1        | 1      | 20%     |
| Seagate ST1000LM048-2E7172 1TB  | 1        | 1      | 20%     |
| Samsung Electronics HD153WI 1TB | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 80%     |
| Samsung Electronics | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 80%     |
| Samsung Electronics | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 5      | 100%    |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 75       | 173    | 65.22%  |
| Works    | 35       | 88     | 30.43%  |
| Malfunc  | 5        | 5      | 4.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 73       | 50.34%  |
| AMD                         | 32       | 22.07%  |
| Samsung Electronics         | 11       | 7.59%   |
| JMicron Technology          | 4        | 2.76%   |
| Phison Electronics          | 3        | 2.07%   |
| Kingston Technology Company | 3        | 2.07%   |
| Broadcom / LSI              | 3        | 2.07%   |
| ASMedia Technology          | 3        | 2.07%   |
| Silicon Motion              | 2        | 1.38%   |
| SanDisk                     | 2        | 1.38%   |
| Nvidia                      | 2        | 1.38%   |
| Micron/Crucial Technology   | 2        | 1.38%   |
| Marvell Technology Group    | 2        | 1.38%   |
| SK hynix                    | 1        | 0.69%   |
| LSI Logic / Symbios Logic   | 1        | 0.69%   |
| ADATA Technology            | 1        | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20       | 10.58%  |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 5.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 4.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 4.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 3.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 3.17%   |
| AMD FCH SATA Controller D                                                               | 5        | 2.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 2.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.12%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.59%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 1.59%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.59%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.59%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.06%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 1.06%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 1.06%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 1.06%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.06%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.06%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.06%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 1.06%   |
| SK hynix BC511                                                                          | 1        | 0.53%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.53%   |
| SanDisk WD Black SN770 NVMe SSD                                                         | 1        | 0.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.53%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.53%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 92       | 60.13%  |
| NVMe | 25       | 16.34%  |
| IDE  | 25       | 16.34%  |
| RAID | 7        | 4.58%   |
| SAS  | 3        | 1.96%   |
| SCSI | 1        | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 72       | 67.92%  |
| AMD    | 34       | 32.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 5.61%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 3.74%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 2.8%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 2.8%    |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 1.87%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.87%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 1.87%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.87%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.87%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 1.87%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.87%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 2        | 1.87%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.87%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.87%   |
| AMD FX-4300 Quad-Core Processor             | 2        | 1.87%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 0.93%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 0.93%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 0.93%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.93%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.93%   |
| Intel Xeon CPU 3.40GHz                      | 1        | 0.93%   |
| Intel Pentium Gold G7400                    | 1        | 0.93%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.93%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.93%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 0.93%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.93%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.93%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.93%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1        | 0.93%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.93%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.93%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.93%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 0.93%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.93%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.93%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 0.93%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 0.93%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.93%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.93%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 16.82%  |
| Intel Core i7           | 17       | 15.89%  |
| AMD Ryzen 7             | 9        | 8.41%   |
| Intel Xeon              | 8        | 7.48%   |
| AMD Ryzen 5             | 8        | 7.48%   |
| Other                   | 5        | 4.67%   |
| Intel Core i3           | 5        | 4.67%   |
| Intel Pentium           | 4        | 3.74%   |
| AMD Ryzen 3             | 4        | 3.74%   |
| Intel Core 2 Quad       | 3        | 2.8%    |
| Intel Celeron           | 3        | 2.8%    |
| AMD FX                  | 3        | 2.8%    |
| Intel Pentium Gold      | 2        | 1.87%   |
| Intel Pentium Dual-Core | 2        | 1.87%   |
| Intel Pentium D         | 2        | 1.87%   |
| Intel Core 2 Duo        | 2        | 1.87%   |
| AMD Athlon II X2        | 2        | 1.87%   |
| AMD Athlon              | 2        | 1.87%   |
| Intel Pentium Dual      | 1        | 0.93%   |
| Intel Core 2            | 1        | 0.93%   |
| AMD Ryzen 9             | 1        | 0.93%   |
| AMD Phenom II X6        | 1        | 0.93%   |
| AMD Phenom II X4        | 1        | 0.93%   |
| AMD G                   | 1        | 0.93%   |
| AMD A8                  | 1        | 0.93%   |
| AMD A4                  | 1        | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 47       | 43.93%  |
| 2      | 29       | 27.1%   |
| 8      | 16       | 14.95%  |
| 6      | 9        | 8.41%   |
| 16     | 5        | 4.67%   |
| 1      | 1        | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 100      | 94.34%  |
| 2      | 6        | 5.66%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 59       | 55.14%  |
| 1      | 48       | 44.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 106      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 11       | 10.19%  |
| 0x306c3    | 8        | 7.41%   |
| 0x206a7    | 8        | 7.41%   |
| 0x506e3    | 5        | 4.63%   |
| 0x1067a    | 5        | 4.63%   |
| 0x08108109 | 5        | 4.63%   |
| 0x0800820d | 5        | 4.63%   |
| 0x08701021 | 4        | 3.7%    |
| Unknown    | 4        | 3.7%    |
| 0xa0671    | 3        | 2.78%   |
| 0x906ed    | 3        | 2.78%   |
| 0x906ea    | 2        | 1.85%   |
| 0x906e9    | 2        | 1.85%   |
| 0x90675    | 2        | 1.85%   |
| 0x6fd      | 2        | 1.85%   |
| 0x206d7    | 2        | 1.85%   |
| 0x20655    | 2        | 1.85%   |
| 0x106e5    | 2        | 1.85%   |
| 0x08101016 | 2        | 1.85%   |
| 0x0810100b | 2        | 1.85%   |
| 0x06000852 | 2        | 1.85%   |
| 0x010000c8 | 2        | 1.85%   |
| 0xf65      | 1        | 0.93%   |
| 0xf47      | 1        | 0.93%   |
| 0xf43      | 1        | 0.93%   |
| 0xa0655    | 1        | 0.93%   |
| 0xa0653    | 1        | 0.93%   |
| 0x906c0    | 1        | 0.93%   |
| 0x806ea    | 1        | 0.93%   |
| 0x806c2    | 1        | 0.93%   |
| 0x706a8    | 1        | 0.93%   |
| 0x6fb      | 1        | 0.93%   |
| 0x6f2      | 1        | 0.93%   |
| 0x306e4    | 1        | 0.93%   |
| 0x206d6    | 1        | 0.93%   |
| 0x206c2    | 1        | 0.93%   |
| 0x106a5    | 1        | 0.93%   |
| 0x0a50000d | 1        | 0.93%   |
| 0x0a50000b | 1        | 0.93%   |
| 0x0a20120a | 1        | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 13       | 12.15%  |
| SandyBridge   | 11       | 10.28%  |
| Zen+          | 10       | 9.35%   |
| KabyLake      | 8        | 7.48%   |
| Haswell       | 8        | 7.48%   |
| Zen           | 6        | 5.61%   |
| Skylake       | 5        | 4.67%   |
| Penryn        | 5        | 4.67%   |
| Unknown       | 5        | 4.67%   |
| Zen 3         | 4        | 3.74%   |
| Zen 2         | 4        | 3.74%   |
| Piledriver    | 4        | 3.74%   |
| K10           | 4        | 3.74%   |
| Core          | 4        | 3.74%   |
| Westmere      | 3        | 2.8%    |
| NetBurst      | 3        | 2.8%    |
| Nehalem       | 3        | 2.8%    |
| CometLake     | 2        | 1.87%   |
| Tremont       | 1        | 0.93%   |
| TigerLake     | 1        | 0.93%   |
| Goldmont plus | 1        | 0.93%   |
| Bulldozer     | 1        | 0.93%   |
| Bobcat        | 1        | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 60       | 51.28%  |
| Intel  | 31       | 26.5%   |
| AMD    | 26       | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 5.04%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 5.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 5.04%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 4.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 4.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 4.2%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 3.36%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 3.36%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 3.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 2.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.68%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.68%   |
| Intel HD Graphics 530                                                       | 2        | 1.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.68%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.84%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.84%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.84%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.84%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 0.84%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 0.84%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.84%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.84%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.84%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.84%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.84%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.84%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.84%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.84%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.84%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 0.84%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.84%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 0.84%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.84%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 0.84%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.84%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 0.84%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 54       | 50%     |
| 1 x Intel      | 25       | 23.15%  |
| 1 x AMD        | 20       | 18.52%  |
| Intel + Nvidia | 3        | 2.78%   |
| AMD + Nvidia   | 3        | 2.78%   |
| 2 x AMD        | 2        | 1.85%   |
| Intel + AMD    | 1        | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 71       | 66.36%  |
| Proprietary | 26       | 24.3%   |
| Unknown     | 10       | 9.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 32.41%  |
| 1.01-2.0   | 24       | 22.22%  |
| 0.01-0.5   | 12       | 11.11%  |
| 3.01-4.0   | 11       | 10.19%  |
| 0.51-1.0   | 11       | 10.19%  |
| 7.01-8.0   | 7        | 6.48%   |
| 5.01-6.0   | 4        | 3.7%    |
| 8.01-16.0  | 2        | 1.85%   |
| 2.01-3.0   | 1        | 0.93%   |
| 16.01-24.0 | 1        | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 17       | 17.35%  |
| Goldstar             | 11       | 11.22%  |
| Acer                 | 8        | 8.16%   |
| Hewlett-Packard      | 7        | 7.14%   |
| Dell                 | 7        | 7.14%   |
| BenQ                 | 7        | 7.14%   |
| Unknown              | 5        | 5.1%    |
| Philips              | 5        | 5.1%    |
| Sony                 | 3        | 3.06%   |
| AOC                  | 3        | 3.06%   |
| Ancor Communications | 3        | 3.06%   |
| ViewSonic            | 2        | 2.04%   |
| Iiyama               | 2        | 2.04%   |
| ___                  | 1        | 1.02%   |
| Unknown (XXX)        | 1        | 1.02%   |
| SKY                  | 1        | 1.02%   |
| PLN                  | 1        | 1.02%   |
| Nixeus               | 1        | 1.02%   |
| NEC Computers        | 1        | 1.02%   |
| MSI                  | 1        | 1.02%   |
| Medion               | 1        | 1.02%   |
| Lenovo Group Limited | 1        | 1.02%   |
| Lenovo               | 1        | 1.02%   |
| Insignia             | 1        | 1.02%   |
| Idek Iiyama          | 1        | 1.02%   |
| HUAWEI               | 1        | 1.02%   |
| HPN                  | 1        | 1.02%   |
| HannStar             | 1        | 1.02%   |
| AUS                  | 1        | 1.02%   |
| ASUSTek Computer     | 1        | 1.02%   |
| Unknown              | 1        | 1.02%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3        | 2.83%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 2        | 1.89%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2        | 1.89%   |
| ___ LCDTV16 ___0101 1360x768                                         | 1        | 0.94%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch           | 1        | 0.94%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch             | 1        | 0.94%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                   | 1        | 0.94%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                | 1        | 0.94%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                 | 1        | 0.94%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 0.94%   |
| Unknown LCD Monitor Dell SE2717H/HX 1920x1080                        | 1        | 0.94%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 0.94%   |
| Sony TV SNY8E01 1360x768                                             | 1        | 0.94%   |
| Sony LCD Monitor TV 3840x1080                                        | 1        | 0.94%   |
| Sony LCD Monitor TV  *00 1920x1080                                   | 1        | 0.94%   |
| SKY TV SKY1502 3840x2160 708x398mm 32.0-inch                         | 1        | 0.94%   |
| SKY TV SKY1502 3840x2160 1150x650mm 52.0-inch                        | 1        | 0.94%   |
| SKY Toshiba TV SKY1402 3840x2160 708x398mm 32.0-inch                 | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 520x290mm 23.4-inch | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM03D0 1440x900 410x257mm 19.1-inch  | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch | 1        | 0.94%   |
| Samsung Electronics SMFX2490HD SAM074A 1920x1080 530x300mm 24.0-inch | 1        | 0.94%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch    | 1        | 0.94%   |
| Samsung Electronics SMBX1950N SAM0716 1366x768 410x230mm 18.5-inch   | 1        | 0.94%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 0.94%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 0.94%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch    | 1        | 0.94%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1        | 0.94%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 0.94%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch     | 1        | 0.94%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch    | 1        | 0.94%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 1        | 0.94%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                   | 1        | 0.94%   |
| Samsung Electronics LCD Monitor S27R65 3840x1080                     | 1        | 0.94%   |
| Samsung Electronics LCD Monitor S27R65                               | 1        | 0.94%   |
| Samsung Electronics LCD Monitor C27F390                              | 1        | 0.94%   |
| Samsung Electronics LC27T55 SAM701E 1920x1080 609x349mm 27.6-inch    | 1        | 0.94%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch   | 1        | 0.94%   |
| PLN LCD Monitor PXL2790MW 1920x1080                                  | 1        | 0.94%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch            | 1        | 0.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 43       | 45.74%  |
| 1680x1050 (WSXGA+) | 8        | 8.51%   |
| 3840x2160 (4K)     | 6        | 6.38%   |
| 1366x768 (WXGA)    | 5        | 5.32%   |
| 3440x1440          | 4        | 4.26%   |
| 2560x1440 (QHD)    | 4        | 4.26%   |
| 1600x900 (HD+)     | 4        | 4.26%   |
| 2560x1080          | 3        | 3.19%   |
| 1360x768           | 3        | 3.19%   |
| 1280x1024 (SXGA)   | 3        | 3.19%   |
| Unknown            | 3        | 3.19%   |
| 3840x1080          | 2        | 2.13%   |
| 1920x1200 (WUXGA)  | 2        | 2.13%   |
| 1440x900 (WXGA+)   | 2        | 2.13%   |
| 4480x1440          | 1        | 1.06%   |
| 1024x768 (XGA)     | 1        | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 23.47%  |
| 21      | 13       | 13.27%  |
| 24      | 12       | 12.24%  |
| 27      | 7        | 7.14%   |
| 23      | 7        | 7.14%   |
| 34      | 5        | 5.1%    |
| 22      | 5        | 5.1%    |
| 18      | 5        | 5.1%    |
| 20      | 4        | 4.08%   |
| 19      | 4        | 4.08%   |
| 31      | 3        | 3.06%   |
| 72      | 2        | 2.04%   |
| 32      | 2        | 2.04%   |
| 64      | 1        | 1.02%   |
| 54      | 1        | 1.02%   |
| 52      | 1        | 1.02%   |
| 28      | 1        | 1.02%   |
| 25      | 1        | 1.02%   |
| 15      | 1        | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 25       | 27.17%  |
| 401-500     | 25       | 27.17%  |
| Unknown     | 23       | 25%     |
| 701-800     | 7        | 7.61%   |
| 601-700     | 5        | 5.43%   |
| 351-400     | 2        | 2.17%   |
| 1501-2000   | 2        | 2.17%   |
| 1001-1500   | 2        | 2.17%   |
| 301-350     | 1        | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 46       | 52.27%  |
| Unknown | 22       | 25%     |
| 16/10   | 11       | 12.5%   |
| 21/9    | 6        | 6.82%   |
| 5/4     | 2        | 2.27%   |
| 4/3     | 1        | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 31       | 32.63%  |
| Unknown        | 23       | 24.21%  |
| 351-500        | 10       | 10.53%  |
| 151-200        | 8        | 8.42%   |
| 301-350        | 7        | 7.37%   |
| 251-300        | 6        | 6.32%   |
| 141-150        | 5        | 5.26%   |
| More than 1000 | 4        | 4.21%   |
| 101-110        | 1        | 1.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 53       | 56.38%  |
| Unknown | 23       | 24.47%  |
| 101-120 | 15       | 15.96%  |
| 1-50    | 2        | 2.13%   |
| 121-160 | 1        | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 82       | 75.93%  |
| 2     | 15       | 13.89%  |
| 0     | 9        | 8.33%   |
| 3     | 2        | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 61       | 41.22%  |
| Intel                    | 50       | 33.78%  |
| Qualcomm Atheros         | 9        | 6.08%   |
| TP-Link                  | 4        | 2.7%    |
| Ralink Technology        | 4        | 2.7%    |
| Broadcom                 | 3        | 2.03%   |
| Samsung Electronics      | 2        | 1.35%   |
| Ralink                   | 2        | 1.35%   |
| Nvidia                   | 2        | 1.35%   |
| NetGear                  | 2        | 1.35%   |
| Huawei Technologies      | 2        | 1.35%   |
| Qualcomm                 | 1        | 0.68%   |
| Mercucys                 | 1        | 0.68%   |
| MediaTek                 | 1        | 0.68%   |
| Marvell Technology Group | 1        | 0.68%   |
| IMC Networks             | 1        | 0.68%   |
| HTC (High Tech Computer) | 1        | 0.68%   |
| Belkin Components        | 1        | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 49       | 28.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 10       | 5.75%   |
| Intel I211 Gigabit Network Connection                                                         | 6        | 3.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 4        | 2.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 2.3%    |
| Realtek RTL8125 2.5GbE Controller                                                             | 3        | 1.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 1.72%   |
| Intel Wireless 3165                                                                           | 3        | 1.72%   |
| Intel Ethernet Connection I217-V                                                              | 3        | 1.72%   |
| Intel Ethernet Connection (7) I219-V                                                          | 3        | 1.72%   |
| Intel Ethernet Connection (2) I219-V                                                          | 3        | 1.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 1.15%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 1.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2        | 1.15%   |
| Realtek 802.11ac NIC                                                                          | 2        | 1.15%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 2        | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 1.15%   |
| Intel Wireless-AC 9260                                                                        | 2        | 1.15%   |
| Intel Wireless 8260                                                                           | 2        | 1.15%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 1.15%   |
| Intel I210 Gigabit Network Connection                                                         | 2        | 1.15%   |
| Intel Ethernet Controller I225-V                                                              | 2        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 1.15%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 1.15%   |
| Intel 82574L Gigabit Network Connection                                                       | 2        | 1.15%   |
| Intel 82573L Gigabit Ethernet Controller                                                      | 2        | 1.15%   |
| Huawei ATU-L21                                                                                | 2        | 1.15%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.57%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                         | 1        | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.57%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 0.57%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 0.57%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 0.57%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 0.57%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.57%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 32.08%  |
| Intel                 | 15       | 28.3%   |
| TP-Link               | 4        | 7.55%   |
| Ralink Technology     | 4        | 7.55%   |
| Qualcomm Atheros      | 4        | 7.55%   |
| Ralink                | 2        | 3.77%   |
| NetGear               | 2        | 3.77%   |
| Mercucys              | 1        | 1.89%   |
| MediaTek              | 1        | 1.89%   |
| IMC Networks          | 1        | 1.89%   |
| Broadcom              | 1        | 1.89%   |
| Belkin Components     | 1        | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 4        | 7.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 7.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 5.36%   |
| Intel Wireless 3165                                                                           | 3        | 5.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 3.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 3.57%   |
| Realtek 802.11ac NIC                                                                          | 2        | 3.57%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 2        | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 3.57%   |
| Intel Wireless-AC 9260                                                                        | 2        | 3.57%   |
| Intel Wireless 8260                                                                           | 2        | 3.57%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 3.57%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 1.79%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                         | 1        | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.79%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.79%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 1.79%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 1.79%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.79%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 1.79%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]                | 1        | 1.79%   |
| NetGear A6210                                                                                 | 1        | 1.79%   |
| NetGear A6150                                                                                 | 1        | 1.79%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 1.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 1.79%   |
| Intel Wireless 7265                                                                           | 1        | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1        | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.79%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                          | 1        | 1.79%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1        | 1.79%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1        | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 55       | 48.67%  |
| Intel                    | 42       | 37.17%  |
| Qualcomm Atheros         | 5        | 4.42%   |
| Samsung Electronics      | 2        | 1.77%   |
| Nvidia                   | 2        | 1.77%   |
| Huawei Technologies      | 2        | 1.77%   |
| Broadcom                 | 2        | 1.77%   |
| Qualcomm                 | 1        | 0.88%   |
| Marvell Technology Group | 1        | 0.88%   |
| HTC (High Tech Computer) | 1        | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49       | 41.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 8.47%   |
| Intel I211 Gigabit Network Connection                             | 6        | 5.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.54%   |
| Intel Ethernet Connection I217-V                                  | 3        | 2.54%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.54%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.69%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.69%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.69%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.69%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.69%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 1.69%   |
| Huawei ATU-L21                                                    | 2        | 1.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.85%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.85%   |
| Qualcomm Android                                                  | 1        | 0.85%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.85%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.85%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.85%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.85%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.85%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.85%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.85%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.85%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.85%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.85%   |
| Intel 82545GM Gigabit Ethernet Controller                         | 1        | 0.85%   |
| HTC (High Tech Computer) Desire HD (modem mode)                   | 1        | 0.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 105      | 67.74%  |
| WiFi     | 50       | 32.26%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 86       | 77.48%  |
| WiFi     | 25       | 22.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 70       | 66.04%  |
| 2     | 33       | 31.13%  |
| 3     | 2        | 1.89%   |
| 0     | 1        | 0.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 81       | 75%     |
| Yes  | 27       | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 15       | 46.88%  |
| Cambridge Silicon Radio | 8        | 25%     |
| Realtek Semiconductor   | 2        | 6.25%   |
| Lite-On Technology      | 2        | 6.25%   |
| Broadcom                | 2        | 6.25%   |
| MediaTek                | 1        | 3.13%   |
| Dynex                   | 1        | 3.13%   |
| Dell                    | 1        | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 8        | 25%     |
| Intel Bluetooth wireless interface                       | 6        | 18.75%  |
| Lite-On Bluetooth Device                                 | 2        | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 2        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                         | 2        | 6.25%   |
| Intel AX200 Bluetooth                                    | 2        | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1        | 3.13%   |
| Realtek Bluetooth Radio                                  | 1        | 3.13%   |
| MediaTek Wireless_Device                                 | 1        | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 3.13%   |
| Intel AX210 Bluetooth                                    | 1        | 3.13%   |
| Intel AX201 Bluetooth                                    | 1        | 3.13%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 3.13%   |
| Dell BT Mini-Receiver                                    | 1        | 3.13%   |
| Broadcom BCM92045B3 ROM                                  | 1        | 3.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 1        | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 69       | 39.2%   |
| Nvidia                               | 55       | 31.25%  |
| AMD                                  | 38       | 21.59%  |
| C-Media Electronics                  | 5        | 2.84%   |
| JMTek                                | 2        | 1.14%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.57%   |
| Sony                                 | 1        | 0.57%   |
| Native Instruments                   | 1        | 0.57%   |
| Micro Star International             | 1        | 0.57%   |
| Logitech                             | 1        | 0.57%   |
| GN Netcom                            | 1        | 0.57%   |
| Generalplus Technology               | 1        | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                      | 13       | 6.44%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 5.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 4.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 3.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 3.47%   |
| Nvidia High Definition Audio Controller                                    | 6        | 2.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 2.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 2.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 2.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 2.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 2.48%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.98%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 1.98%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 1.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.98%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.49%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 1.49%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 1.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.49%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.99%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.99%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 0.99%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 0.99%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 0.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 0.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 0.99%   |
| AMD FCH Azalia Controller                                                  | 2        | 0.99%   |
| Thesycon Systemsoftware & Consulting D50s                                  | 1        | 0.5%    |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.5%    |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.5%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 18.18%  |
| Unknown             | 7        | 15.91%  |
| Corsair             | 5        | 11.36%  |
| Micron Technology   | 4        | 9.09%   |
| Kingston            | 4        | 9.09%   |
| G.Skill             | 3        | 6.82%   |
| Crucial             | 3        | 6.82%   |
| SK hynix            | 2        | 4.55%   |
| Unknown (ABCD)      | 1        | 2.27%   |
| Smart               | 1        | 2.27%   |
| Nanya Technology    | 1        | 2.27%   |
| KLEVV               | 1        | 2.27%   |
| GeIL                | 1        | 2.27%   |
| Elpida              | 1        | 2.27%   |
| AVEXIR              | 1        | 2.27%   |
| A-DATA Technology   | 1        | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 2        | 4.08%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 2.04%   |
| Unknown RAM Module 512MB DIMM DDR2 266MT/s                     | 1        | 2.04%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 2.04%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 2.04%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1        | 2.04%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 2.04%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 2.04%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                       | 1        | 2.04%   |
| Unknown RAM Module 1GB DIMM DDR2 266MT/s                       | 1        | 2.04%   |
| Unknown RAM D4 8G 8GB DIMM DDR4 2666MT/s                       | 1        | 2.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 2.04%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s          | 1        | 2.04%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s           | 1        | 2.04%   |
| SK hynix RAM HKNNNFBMAVAR-NEH 2GB Row Of Chips LPDDR4 3200MT/s | 1        | 2.04%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                      | 1        | 2.04%   |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s                      | 1        | 2.04%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 2.04%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s          | 1        | 2.04%   |
| Samsung RAM M393B5270DH0-YH9 4GB DIMM DDR3 1333MT/s            | 1        | 2.04%   |
| Samsung RAM M393B2G70DB0-CMA 16GB DIMM DDR3 1867MT/s           | 1        | 2.04%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1600MT/s            | 1        | 2.04%   |
| Samsung RAM M393B1G70BH0-YK0 8GB DIMM DDR3 1600MT/s            | 1        | 2.04%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s           | 1        | 2.04%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s              | 1        | 2.04%   |
| Micron RAM 36JSF2G72PZ-1G9E1 16GB DIMM DDR3 1866MT/s           | 1        | 2.04%   |
| Micron RAM 18KSF1G72PZ-1G4E1 8GB DIMM DDR3 1333MT/s            | 1        | 2.04%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s            | 1        | 2.04%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 2.04%   |
| KLEVV RAM KD48GU880-36A180C 8GB DIMM DDR4 3600MT/s             | 1        | 2.04%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 1        | 2.04%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s          | 1        | 2.04%   |
| Kingston RAM 99U5403-034.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 2.04%   |
| Kingston RAM 99U5402-037.A00G 2GB DIMM DDR3 1333MT/s           | 1        | 2.04%   |
| Kingston RAM 9905471-001.A01LF 2GB DIMM DDR3 1600MT/s          | 1        | 2.04%   |
| GeIL RAM CL9-9-9 DDR3-1333 2GB DIMM DDR3 1333MT/s              | 1        | 2.04%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 1        | 2.04%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s          | 1        | 2.04%   |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s             | 1        | 2.04%   |
| Elpida RAM EBE21UE8AFFA-8G-F 2GB DIMM DDR2 800MT/s             | 1        | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 14       | 36.84%  |
| DDR3    | 14       | 36.84%  |
| DDR2    | 4        | 10.53%  |
| SDRAM   | 2        | 5.26%   |
| LPDDR4  | 2        | 5.26%   |
| Unknown | 2        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 34       | 91.89%  |
| SODIMM       | 2        | 5.41%   |
| Row Of Chips | 1        | 2.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 13       | 30.23%  |
| 4096  | 12       | 27.91%  |
| 16384 | 7        | 16.28%  |
| 2048  | 6        | 13.95%  |
| 1024  | 3        | 6.98%   |
| 32768 | 1        | 2.33%   |
| 512   | 1        | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 10       | 24.39%  |
| 1333  | 5        | 12.2%   |
| 3600  | 4        | 9.76%   |
| 3200  | 3        | 7.32%   |
| 2667  | 3        | 7.32%   |
| 2400  | 3        | 7.32%   |
| 2133  | 2        | 4.88%   |
| 1866  | 2        | 4.88%   |
| 667   | 2        | 4.88%   |
| 3733  | 1        | 2.44%   |
| 1867  | 1        | 2.44%   |
| 1334  | 1        | 2.44%   |
| 1066  | 1        | 2.44%   |
| 800   | 1        | 2.44%   |
| 533   | 1        | 2.44%   |
| 266   | 1        | 2.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 40%     |
| Seiko Epson        | 1        | 20%     |
| Konica Minolta     | 1        | 20%     |
| Brother Industries | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson ET-2820 Series | 1        | 20%     |
| Konica Minolta 185         | 1        | 20%     |
| HP OfficeJet Pro 8730      | 1        | 20%     |
| HP DeskJet 2130 series     | 1        | 20%     |
| Brother MFC-L2685DW        | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 7        | 33.33%  |
| Sunplus Innovation Technology | 3        | 14.29%  |
| Huawei Technologies           | 2        | 9.52%   |
| Creative Technology           | 2        | 9.52%   |
| Z-Star Microelectronics       | 1        | 4.76%   |
| Samsung Electronics           | 1        | 4.76%   |
| Pixart Imaging                | 1        | 4.76%   |
| OmniVision Technologies       | 1        | 4.76%   |
| MacroSilicon                  | 1        | 4.76%   |
| ARC International             | 1        | 4.76%   |
| Alcor Micro                   | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Sunplus FHD Camera Microphone                  | 2        | 9.52%   |
| Logitech Webcam C270                           | 2        | 9.52%   |
| Huawei HiCamera                                | 2        | 9.52%   |
| Z-Star Venus USB2.0 Camera                     | 1        | 4.76%   |
| Sunplus USB camera                             | 1        | 4.76%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 4.76%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 1        | 4.76%   |
| OmniVision Integrated Webcam for Dell XPS 2010 | 1        | 4.76%   |
| MacroSilicon USB Video                         | 1        | 4.76%   |
| Logitech Webcam C925e                          | 1        | 4.76%   |
| Logitech Webcam C210                           | 1        | 4.76%   |
| Logitech Webcam B500                           | 1        | 4.76%   |
| Logitech QuickCam Communicate Deluxe/S7500     | 1        | 4.76%   |
| Logitech Logi Webcam C920e                     | 1        | 4.76%   |
| Creative VF0610 Live! Cam Socialize HD         | 1        | 4.76%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 4.76%   |
| ARC International Camera                       | 1        | 4.76%   |
| Alcor Micro USB 5.0M AF Camera                 | 1        | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 80       | 74.07%  |
| 1     | 27       | 25%     |
| 2     | 1        | 0.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 15       | 48.39%  |
| Net/wireless             | 10       | 32.26%  |
| Multimedia controller    | 2        | 6.45%   |
| Unassigned class         | 1        | 3.23%   |
| Storage/raid             | 1        | 3.23%   |
| Communication controller | 1        | 3.23%   |
| Camera                   | 1        | 3.23%   |

