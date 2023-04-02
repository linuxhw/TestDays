LMDE - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for LMDE.

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

Total: 389

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Gigabyte      | X570 AORUS MASTER           | [2d26056501](https://linux-hardware.org/?probe=2d26056501) | Feb 13, 2023 |
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
| ASRock        | G41M-S3                     | [2cdcaebd43](https://linux-hardware.org/?probe=2cdcaebd43) | Sep 10, 2022 |
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
| ASUSTek       | P5B                         | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
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
| ASUSTek       | P5QL PRO                    | [9ea782b1d2](https://linux-hardware.org/?probe=9ea782b1d2) | May 08, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| HP            | 339A                        | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Gigabyte      | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Dell          | 0XR1GT A00                  | [2a3b9ad6cf](https://linux-hardware.org/?probe=2a3b9ad6cf) | Apr 24, 2022 |
| ASRock        | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Foxconn       | Cinema Series FAB           | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [eb751efc1f](https://linux-hardware.org/?probe=eb751efc1f) | Apr 09, 2022 |
| Acer          | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| ASUSTek       | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Acer          | EG43M                       | [28b4dd5236](https://linux-hardware.org/?probe=28b4dd5236) | Mar 31, 2022 |
| ASUSTek       | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [346857be22](https://linux-hardware.org/?probe=346857be22) | Mar 24, 2022 |
| ASUSTek       | P4P800                      | [0cb6a89491](https://linux-hardware.org/?probe=0cb6a89491) | Mar 19, 2022 |
| HP            | 0AA8h                       | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| HP            | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Dell          | 0HR330                      | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell          | 0HR330                      | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| HP            | 0AA8h                       | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| Gigabyte      | Z77-D3H                     | [a0d52488b2](https://linux-hardware.org/?probe=a0d52488b2) | Feb 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [0731118682](https://linux-hardware.org/?probe=0731118682) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [5026ea812a](https://linux-hardware.org/?probe=5026ea812a) | Feb 15, 2022 |
| Dell          | 0Y2K8N A01                  | [e3922aecf0](https://linux-hardware.org/?probe=e3922aecf0) | Feb 04, 2022 |
| EVGA          | 131-HE-E095                 | [6d45d47131](https://linux-hardware.org/?probe=6d45d47131) | Jan 31, 2022 |
| ASUSTek       | A68HM-K                     | [00cd805015](https://linux-hardware.org/?probe=00cd805015) | Jan 23, 2022 |
| MSI           | Z97 PC Mate                 | [be068c5a3a](https://linux-hardware.org/?probe=be068c5a3a) | Jan 21, 2022 |
| Dell          | 0XR1GT A00                  | [a988797ac9](https://linux-hardware.org/?probe=a988797ac9) | Jan 16, 2022 |
| eMachines     | EMCP73VT-PM                 | [1d55cceee4](https://linux-hardware.org/?probe=1d55cceee4) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | [43b421ad06](https://linux-hardware.org/?probe=43b421ad06) | Jan 08, 2022 |
| ASRock        | N68-S3 UCC                  | [bfcf287c09](https://linux-hardware.org/?probe=bfcf287c09) | Jan 08, 2022 |
| OEM           | Unknown                     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| Unknown       | K7VM2                       | [06f13210ad](https://linux-hardware.org/?probe=06f13210ad) | Dec 29, 2021 |
| Unknown       | K7VM2                       | [be785b672c](https://linux-hardware.org/?probe=be785b672c) | Dec 29, 2021 |
| HP            | 2AE3                        | [fb02077f16](https://linux-hardware.org/?probe=fb02077f16) | Dec 14, 2021 |
| HP            | 2AE3                        | [18efa559b9](https://linux-hardware.org/?probe=18efa559b9) | Dec 14, 2021 |
| ECS           | G41T-M7                     | [5a8641a9aa](https://linux-hardware.org/?probe=5a8641a9aa) | Dec 13, 2021 |
| Acer          | RS880M05                    | [2ce9c25975](https://linux-hardware.org/?probe=2ce9c25975) | Nov 25, 2021 |
| NEC Comput... | GA-8I945PM                  | [3d3711b8cc](https://linux-hardware.org/?probe=3d3711b8cc) | Nov 22, 2021 |
| ASUSTek       | A68HM-K                     | [b4b709eb1b](https://linux-hardware.org/?probe=b4b709eb1b) | Nov 18, 2021 |
| ASUSTek       | A68HM-K                     | [18236d5a16](https://linux-hardware.org/?probe=18236d5a16) | Nov 18, 2021 |
| Intel         | H61                         | [51f383b050](https://linux-hardware.org/?probe=51f383b050) | Nov 04, 2021 |
| HP            | 843C                        | [e7df8fecdd](https://linux-hardware.org/?probe=e7df8fecdd) | Oct 30, 2021 |
| ASUSTek       | P7F-M                       | [f0983027ee](https://linux-hardware.org/?probe=f0983027ee) | Oct 26, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | [48187accde](https://linux-hardware.org/?probe=48187accde) | Oct 21, 2021 |
| ASUSTek       | Z97-K                       | [f1fcb9d1db](https://linux-hardware.org/?probe=f1fcb9d1db) | Oct 17, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | [a1820d8f0c](https://linux-hardware.org/?probe=a1820d8f0c) | Oct 17, 2021 |
| Gigabyte      | H61M-D2-B3                  | [138df954cb](https://linux-hardware.org/?probe=138df954cb) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | [dabe5d459a](https://linux-hardware.org/?probe=dabe5d459a) | Oct 15, 2021 |
| ASUSTek       | Z97-K                       | [940a27249a](https://linux-hardware.org/?probe=940a27249a) | Oct 12, 2021 |
| ASUSTek       | Z97-K                       | [012056e32d](https://linux-hardware.org/?probe=012056e32d) | Sep 28, 2021 |
| Biostar       | G41D3C                      | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [9c0ade7c9c](https://linux-hardware.org/?probe=9c0ade7c9c) | Sep 20, 2021 |
| ASUSTek       | P5VD2-VM                    | [9eec34a3f2](https://linux-hardware.org/?probe=9eec34a3f2) | Sep 13, 2021 |
| Foxconn       | 945 7MC Series              | [623cb095f2](https://linux-hardware.org/?probe=623cb095f2) | Sep 12, 2021 |
| Pegatron      | 2AB5                        | [3c335b37fa](https://linux-hardware.org/?probe=3c335b37fa) | Sep 10, 2021 |
| ASUSTek       | UN62                        | [0702f80222](https://linux-hardware.org/?probe=0702f80222) | Sep 09, 2021 |
| ASUSTek       | P5VD2-VM                    | [305d566f57](https://linux-hardware.org/?probe=305d566f57) | Sep 07, 2021 |
| Gigabyte      | H61M-S1                     | [d1773b3e3d](https://linux-hardware.org/?probe=d1773b3e3d) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | [5d2cc7f4ca](https://linux-hardware.org/?probe=5d2cc7f4ca) | Sep 06, 2021 |
| Intel         | DG31PR AAD97573-302         | [7122e4bd16](https://linux-hardware.org/?probe=7122e4bd16) | Sep 04, 2021 |
| Gigabyte      | M52LT-D3P                   | [09cbb5b50e](https://linux-hardware.org/?probe=09cbb5b50e) | Sep 03, 2021 |
| Gigabyte      | M52LT-D3P                   | [949b2062ea](https://linux-hardware.org/?probe=949b2062ea) | Sep 03, 2021 |
| ASRock        | G41M-S3                     | [c34caa75e2](https://linux-hardware.org/?probe=c34caa75e2) | Aug 23, 2021 |
| MSI           | MS-7142                     | [2700c74bd9](https://linux-hardware.org/?probe=2700c74bd9) | Aug 21, 2021 |
| MSI           | MS-7142                     | [18ae0c1bb3](https://linux-hardware.org/?probe=18ae0c1bb3) | Aug 21, 2021 |
| HP            | 0AA8h                       | [d9a8fd3722](https://linux-hardware.org/?probe=d9a8fd3722) | Aug 15, 2021 |
| ASUSTek       | A7N8X-LA                    | [0e9fd81caf](https://linux-hardware.org/?probe=0e9fd81caf) | Aug 11, 2021 |
| ASUSTek       | A7N8X-LA                    | [f14c99bbce](https://linux-hardware.org/?probe=f14c99bbce) | Aug 11, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| ASUSTek       | P7F-M                       | [cff87306ab](https://linux-hardware.org/?probe=cff87306ab) | Aug 07, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| ASUSTek       | PRIME Z370-A                | [05c1703574](https://linux-hardware.org/?probe=05c1703574) | Aug 03, 2021 |
| ASUSTek       | PRIME Z370-A                | [faf304d157](https://linux-hardware.org/?probe=faf304d157) | Aug 02, 2021 |
| OEM           | 45CMX/45GMX/45CMX-K         | [65d8eb687e](https://linux-hardware.org/?probe=65d8eb687e) | Jul 30, 2021 |
| ASUSTek       | P7F-M                       | [33a6186148](https://linux-hardware.org/?probe=33a6186148) | Jul 30, 2021 |
| Intel         | BTC-T37                     | [bb5051b598](https://linux-hardware.org/?probe=bb5051b598) | Jul 27, 2021 |
| ASRock        | FM2A85X Extreme4-M          | [aa0030f094](https://linux-hardware.org/?probe=aa0030f094) | Jul 26, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [763cb39ac0](https://linux-hardware.org/?probe=763cb39ac0) | Jul 25, 2021 |
| Gigabyte      | X570 AORUS PRO              | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| Dell          | 08HPGT A01                  | [64d562d6ef](https://linux-hardware.org/?probe=64d562d6ef) | Jul 16, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| ASUSTek       | P7F-M                       | [3007b813c6](https://linux-hardware.org/?probe=3007b813c6) | Jul 13, 2021 |
| ASUSTek       | P7F-M                       | [5cfa1dcb4f](https://linux-hardware.org/?probe=5cfa1dcb4f) | Jul 12, 2021 |
| MSI           | H81M-E34                    | [14c2f8a49d](https://linux-hardware.org/?probe=14c2f8a49d) | Jul 05, 2021 |
| MSI           | A320M-A PRO                 | [9d356e787a](https://linux-hardware.org/?probe=9d356e787a) | Jul 01, 2021 |
| HP            | 0A98h                       | [40990f73a5](https://linux-hardware.org/?probe=40990f73a5) | Jun 22, 2021 |
| HP            | 0AA8h                       | [43103b39a5](https://linux-hardware.org/?probe=43103b39a5) | Jun 17, 2021 |
| HP            | 0AA8h                       | [9154911bc9](https://linux-hardware.org/?probe=9154911bc9) | Jun 13, 2021 |
| ASUSTek       | Maximus VI HERO             | [699d10613e](https://linux-hardware.org/?probe=699d10613e) | Jun 11, 2021 |
| Unknown       | Unknown                     | [3e408e9ead](https://linux-hardware.org/?probe=3e408e9ead) | May 31, 2021 |
| Unknown       | Unknown                     | [39b2780acf](https://linux-hardware.org/?probe=39b2780acf) | May 31, 2021 |
| Dell          | 0HY9JP A01                  | [3f6ddbd81d](https://linux-hardware.org/?probe=3f6ddbd81d) | May 30, 2021 |
| ASUSTek       | H61M-A/BR                   | [7d2b37e6e1](https://linux-hardware.org/?probe=7d2b37e6e1) | May 29, 2021 |
| ASRock        | G41M-S3                     | [adc801308b](https://linux-hardware.org/?probe=adc801308b) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | [d03d2796a0](https://linux-hardware.org/?probe=d03d2796a0) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | [200072e2a7](https://linux-hardware.org/?probe=200072e2a7) | May 29, 2021 |
| ASRock        | G41M-S3                     | [47f6c3e962](https://linux-hardware.org/?probe=47f6c3e962) | May 28, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | [cd3697bd15](https://linux-hardware.org/?probe=cd3697bd15) | May 25, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | [7c520b0d6e](https://linux-hardware.org/?probe=7c520b0d6e) | May 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [55d981b2ed](https://linux-hardware.org/?probe=55d981b2ed) | May 23, 2021 |
| Intel         | H61                         | [1954634de4](https://linux-hardware.org/?probe=1954634de4) | May 22, 2021 |
| Foxconn       | 945 7MC Series              | [f4634ec470](https://linux-hardware.org/?probe=f4634ec470) | May 17, 2021 |
| Dell          | 0FM586 A00                  | [8a955d2c5a](https://linux-hardware.org/?probe=8a955d2c5a) | May 16, 2021 |
| ASUSTek       | B150M-A                     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Dell          | 0XR1GT A00                  | [a502e8842e](https://linux-hardware.org/?probe=a502e8842e) | May 12, 2021 |
| ASUSTek       | V-P7H55E                    | [3c0a297ede](https://linux-hardware.org/?probe=3c0a297ede) | May 08, 2021 |
| ASUSTek       | Crosshair V Formula         | [0fd87c485e](https://linux-hardware.org/?probe=0fd87c485e) | May 07, 2021 |
| ASUSTek       | P5KC                        | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASUSTek       | P5KC                        | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [46b0bab7d8](https://linux-hardware.org/?probe=46b0bab7d8) | Apr 27, 2021 |
| Unknown       | Phitronics N68C-M           | [3076a5bae3](https://linux-hardware.org/?probe=3076a5bae3) | Apr 24, 2021 |
| Unknown       | Phitronics N68C-M           | [d3a56832d9](https://linux-hardware.org/?probe=d3a56832d9) | Apr 23, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [761a9ce0e9](https://linux-hardware.org/?probe=761a9ce0e9) | Apr 21, 2021 |
| ASUSTek       | P5Q DELUXE                  | [8ab143ec6b](https://linux-hardware.org/?probe=8ab143ec6b) | Apr 20, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [2813977a91](https://linux-hardware.org/?probe=2813977a91) | Apr 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [d6c3daff43](https://linux-hardware.org/?probe=d6c3daff43) | Apr 19, 2021 |
| ASUSTek       | V-P7H55E                    | [fb3b69b074](https://linux-hardware.org/?probe=fb3b69b074) | Apr 18, 2021 |
| Gigabyte      | M68MT-S2P                   | [47deff8a39](https://linux-hardware.org/?probe=47deff8a39) | Apr 17, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [16d03cb92f](https://linux-hardware.org/?probe=16d03cb92f) | Apr 12, 2021 |
| Dell          | 0KP561                      | [3579bff9c4](https://linux-hardware.org/?probe=3579bff9c4) | Apr 08, 2021 |
| DFI           | LP BI P45-T2S Elite         | [01f0babd70](https://linux-hardware.org/?probe=01f0babd70) | Apr 08, 2021 |
| ASUSTek       | PRIME Z390-P                | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| ASUSTek       | P5KC                        | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| Pegatron      | 2ADC                        | [e4bfddb8d9](https://linux-hardware.org/?probe=e4bfddb8d9) | Apr 04, 2021 |
| MSI           | MS-7267                     | [d16e8a4364](https://linux-hardware.org/?probe=d16e8a4364) | Apr 03, 2021 |
| Intel         | H61                         | [d7c3f87e52](https://linux-hardware.org/?probe=d7c3f87e52) | Mar 26, 2021 |
| Gigabyte      | Z77-D3H                     | [6ab1c423db](https://linux-hardware.org/?probe=6ab1c423db) | Mar 25, 2021 |
| MSI           | Z77A-GD65                   | [a9c3672597](https://linux-hardware.org/?probe=a9c3672597) | Mar 25, 2021 |
| ASUSTek       | M5A97 PRO                   | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| MSI           | MS-6785                     | [303c1ac636](https://linux-hardware.org/?probe=303c1ac636) | Mar 17, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | [f8503ecc3b](https://linux-hardware.org/?probe=f8503ecc3b) | Mar 10, 2021 |
| ECS           | A740GM-M                    | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| ASUSTek       | P7F-M                       | [a8d2e4fa56](https://linux-hardware.org/?probe=a8d2e4fa56) | Mar 07, 2021 |
| MSI           | B450M PRO-VDH MAX           | [79e6e8bbfc](https://linux-hardware.org/?probe=79e6e8bbfc) | Mar 06, 2021 |
| ASRock        | G31M-GS                     | [ea6fbcd94e](https://linux-hardware.org/?probe=ea6fbcd94e) | Mar 02, 2021 |
| Acer          | EG43LMK                     | [249967a21a](https://linux-hardware.org/?probe=249967a21a) | Feb 28, 2021 |
| ASRock        | A320M-HDV R4.0              | [527b138b70](https://linux-hardware.org/?probe=527b138b70) | Feb 22, 2021 |
| Acer          | EG43LMK                     | [1c1fdf43c0](https://linux-hardware.org/?probe=1c1fdf43c0) | Feb 17, 2021 |
| MSI           | MS-7267                     | [6bf114a22f](https://linux-hardware.org/?probe=6bf114a22f) | Feb 15, 2021 |
| MSI           | MS-7267                     | [78e4d03c89](https://linux-hardware.org/?probe=78e4d03c89) | Feb 15, 2021 |
| Intel         | DP55WB AAE64798-206         | [4b2befb0d2](https://linux-hardware.org/?probe=4b2befb0d2) | Feb 14, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c8e67a7d41](https://linux-hardware.org/?probe=c8e67a7d41) | Feb 07, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [6e605fd64d](https://linux-hardware.org/?probe=6e605fd64d) | Feb 06, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [ec667e7b35](https://linux-hardware.org/?probe=ec667e7b35) | Feb 05, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [b71d20e5de](https://linux-hardware.org/?probe=b71d20e5de) | Feb 05, 2021 |
| ASUSTek       | Z97-K                       | [3adb6d9dc1](https://linux-hardware.org/?probe=3adb6d9dc1) | Feb 05, 2021 |
| ASRock        | X570 Taichi                 | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| ASRock        | H61M-HVS                    | [05c23c4247](https://linux-hardware.org/?probe=05c23c4247) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | [8c45cfc073](https://linux-hardware.org/?probe=8c45cfc073) | Feb 02, 2021 |
| ASUSTek       | P5E3 Deluxe                 | [47324765ec](https://linux-hardware.org/?probe=47324765ec) | Feb 02, 2021 |
| Unknown       | Unknown                     | [94d77e9dd0](https://linux-hardware.org/?probe=94d77e9dd0) | Feb 02, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [9761a3446c](https://linux-hardware.org/?probe=9761a3446c) | Jan 30, 2021 |
| Dell          | 03NVJ6 A02                  | [9c930ede42](https://linux-hardware.org/?probe=9c930ede42) | Jan 28, 2021 |
| MSI           | B450M-A PRO MAX             | [e5bc80f882](https://linux-hardware.org/?probe=e5bc80f882) | Jan 26, 2021 |
| Dell          | 0TT708 A01                  | [d04b2d493f](https://linux-hardware.org/?probe=d04b2d493f) | Jan 20, 2021 |
| Dell          | 0TT708 A01                  | [08ac15e868](https://linux-hardware.org/?probe=08ac15e868) | Jan 15, 2021 |
| Dell          | 0TT708 A01                  | [d0da7a44f7](https://linux-hardware.org/?probe=d0da7a44f7) | Jan 14, 2021 |
| Alienware     | 06G6JW A00                  | [992089d02a](https://linux-hardware.org/?probe=992089d02a) | Jan 12, 2021 |
| Intel         | DP55WB AAE64798-206         | [51ec8a1510](https://linux-hardware.org/?probe=51ec8a1510) | Jan 06, 2021 |
| ASUSTek       | P5K                         | [22a568db8e](https://linux-hardware.org/?probe=22a568db8e) | Jan 02, 2021 |
| ASUSTek       | P5K                         | [4233bd7b15](https://linux-hardware.org/?probe=4233bd7b15) | Jan 02, 2021 |
| MSI           | MS-6570                     | [f6bdec1638](https://linux-hardware.org/?probe=f6bdec1638) | Dec 28, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| MSI           | Z87 MPOWER MAX              | [5db0b2dedf](https://linux-hardware.org/?probe=5db0b2dedf) | Dec 23, 2020 |
| MSI           | MS-7541                     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| ASUSTek       | Maximus VI HERO             | [862b159eb2](https://linux-hardware.org/?probe=862b159eb2) | Dec 19, 2020 |
| Toshiba       | STI 910123                  | [f9f7a69232](https://linux-hardware.org/?probe=f9f7a69232) | Dec 18, 2020 |
| Toshiba       | STI 910123                  | [ae79e069f3](https://linux-hardware.org/?probe=ae79e069f3) | Dec 18, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | [fdc26c9f6d](https://linux-hardware.org/?probe=fdc26c9f6d) | Dec 18, 2020 |
| ASUSTek       | P8B75-V                     | [edb814f54a](https://linux-hardware.org/?probe=edb814f54a) | Dec 15, 2020 |
| ASUSTek       | Z97-K                       | [5b78a6b7ee](https://linux-hardware.org/?probe=5b78a6b7ee) | Dec 13, 2020 |
| ASUSTek       | Z97-K                       | [e1afb118e5](https://linux-hardware.org/?probe=e1afb118e5) | Dec 12, 2020 |
| Acer          | Aspire XC600 v1.0           | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| EVGA          | 131-HE-E095                 | [8fca80343b](https://linux-hardware.org/?probe=8fca80343b) | Dec 08, 2020 |
| HP            | 1496                        | [61eeea25ed](https://linux-hardware.org/?probe=61eeea25ed) | Dec 04, 2020 |
| Dell          | 0XPDFK A01                  | [02ffa180c8](https://linux-hardware.org/?probe=02ffa180c8) | Nov 30, 2020 |
| ASRock        | X370 Taichi                 | [a229c68d0e](https://linux-hardware.org/?probe=a229c68d0e) | Nov 27, 2020 |
| Gigabyte      | 945GM-S2                    | [1bbf0f874b](https://linux-hardware.org/?probe=1bbf0f874b) | Nov 26, 2020 |
| MSI           | B85M-G43                    | [dee4fcacb7](https://linux-hardware.org/?probe=dee4fcacb7) | Nov 26, 2020 |
| Gigabyte      | H81M-S2PV                   | [1c5cc4c12e](https://linux-hardware.org/?probe=1c5cc4c12e) | Nov 25, 2020 |
| Dell          | 0F6X5P A00                  | [458d498ed4](https://linux-hardware.org/?probe=458d498ed4) | Nov 24, 2020 |
| ASUSTek       | M4A785TD-V EVO              | [c03bf04e1e](https://linux-hardware.org/?probe=c03bf04e1e) | Nov 15, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [2fe3e165eb](https://linux-hardware.org/?probe=2fe3e165eb) | Oct 31, 2020 |
| Dell          | 0DR845                      | [958876c9d6](https://linux-hardware.org/?probe=958876c9d6) | Oct 27, 2020 |
| HP            | 843B                        | [cf9214c9e8](https://linux-hardware.org/?probe=cf9214c9e8) | Oct 25, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [c637e2732a](https://linux-hardware.org/?probe=c637e2732a) | Oct 22, 2020 |
| Gigabyte      | G33M-S2                     | [d5b1adf1cc](https://linux-hardware.org/?probe=d5b1adf1cc) | Oct 21, 2020 |
| MSI           | Z97 GAMING 3                | [d70dc5679f](https://linux-hardware.org/?probe=d70dc5679f) | Oct 15, 2020 |
| ASUSTek       | P7F-M                       | [a931f70b33](https://linux-hardware.org/?probe=a931f70b33) | Oct 14, 2020 |
| HP            | 304Ah                       | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| HP            | 304Ah                       | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
| HP            | 304Ah                       | [11dc9e4238](https://linux-hardware.org/?probe=11dc9e4238) | Sep 28, 2020 |
| ASUSTek       | P8H61-MX USB3               | [2def8c0128](https://linux-hardware.org/?probe=2def8c0128) | Sep 19, 2020 |
| ASUSTek       | P5E3 Deluxe                 | [694576f25f](https://linux-hardware.org/?probe=694576f25f) | Sep 14, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | [e5260021d2](https://linux-hardware.org/?probe=e5260021d2) | Sep 06, 2020 |
| Dell          | 0DR845                      | [f9dfefaf63](https://linux-hardware.org/?probe=f9dfefaf63) | Aug 31, 2020 |
| Gigabyte      | EP45C-DS3R                  | [3baa06afa2](https://linux-hardware.org/?probe=3baa06afa2) | Aug 24, 2020 |
| ECS           | KAM1-I                      | [cef51c9cd7](https://linux-hardware.org/?probe=cef51c9cd7) | Aug 15, 2020 |
| MSI           | D2414 S26361-D2414-A10      | [a0ea23eae8](https://linux-hardware.org/?probe=a0ea23eae8) | Aug 10, 2020 |
| Unknown       | P4M800Pro-8237              | [e632211d18](https://linux-hardware.org/?probe=e632211d18) | Aug 04, 2020 |
| Gigabyte      | Z77-D3H                     | [05331a0b70](https://linux-hardware.org/?probe=05331a0b70) | Aug 04, 2020 |
| Intel         | DG33FB AAD81072-309         | [217bfd48bd](https://linux-hardware.org/?probe=217bfd48bd) | Aug 04, 2020 |
| Dell          | 0DR845                      | [a70d949ebc](https://linux-hardware.org/?probe=a70d949ebc) | Jul 30, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | [4af42f19bb](https://linux-hardware.org/?probe=4af42f19bb) | Jul 14, 2020 |
| HP            | 3396                        | [53167bce1a](https://linux-hardware.org/?probe=53167bce1a) | Jul 09, 2020 |
| ASUSTek       | G11DF                       | [73ddfc32aa](https://linux-hardware.org/?probe=73ddfc32aa) | Jun 23, 2020 |
| ASUSTek       | G11DF                       | [497ebd9b60](https://linux-hardware.org/?probe=497ebd9b60) | Jun 23, 2020 |
| Biostar       | NF61S-M2A                   | [c071fa24d8](https://linux-hardware.org/?probe=c071fa24d8) | Jun 21, 2020 |
| PCWare        | IPMH81G1                    | [416c3e2997](https://linux-hardware.org/?probe=416c3e2997) | Jun 07, 2020 |
| Dell          | 0200DY A03                  | [aebb17da40](https://linux-hardware.org/?probe=aebb17da40) | Jun 01, 2020 |
| Dell          | 0DR845                      | [4b8a511c08](https://linux-hardware.org/?probe=4b8a511c08) | May 29, 2020 |
| Dell          | 042P49 A00                  | [aca1fb8ea1](https://linux-hardware.org/?probe=aca1fb8ea1) | May 21, 2020 |
| Dell          | 042P49 A00                  | [8e547a1414](https://linux-hardware.org/?probe=8e547a1414) | May 20, 2020 |
| ASRock        | EP2C602-4L/D16              | [cf5fe3dbce](https://linux-hardware.org/?probe=cf5fe3dbce) | May 17, 2020 |
| ASRock        | B75M R2.0                   | [efd3354b61](https://linux-hardware.org/?probe=efd3354b61) | May 10, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | [1a79fa9925](https://linux-hardware.org/?probe=1a79fa9925) | May 03, 2020 |
| ASRock        | J4205-ITX                   | [4fc5d5a325](https://linux-hardware.org/?probe=4fc5d5a325) | Apr 22, 2020 |
| ECS           | Nettle2                     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| ASUSTek       | A88XM-A                     | [12c198a6f5](https://linux-hardware.org/?probe=12c198a6f5) | Apr 18, 2020 |
| ASUSTek       | A88XM-A                     | [0d1b40e847](https://linux-hardware.org/?probe=0d1b40e847) | Apr 14, 2020 |
| ASRock        | N68-GS3 UCC                 | [3cc8e9e496](https://linux-hardware.org/?probe=3cc8e9e496) | Apr 12, 2020 |
| ASRock        | N68-GS3 UCC                 | [8822c3378d](https://linux-hardware.org/?probe=8822c3378d) | Apr 12, 2020 |
| HP            | 8526 MVB, A                 | [30e90998e1](https://linux-hardware.org/?probe=30e90998e1) | Apr 08, 2020 |
| Gigabyte      | B450M DS3H-CF               | [b660991573](https://linux-hardware.org/?probe=b660991573) | Mar 29, 2020 |
| MSI           | G31M2                       | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| Acer          | Aspire TC-605               | [495fffaa63](https://linux-hardware.org/?probe=495fffaa63) | Mar 26, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | [fb006f397c](https://linux-hardware.org/?probe=fb006f397c) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | [5c7e0a86df](https://linux-hardware.org/?probe=5c7e0a86df) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | [c6a5cf98ee](https://linux-hardware.org/?probe=c6a5cf98ee) | Mar 24, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | [0c52aebe31](https://linux-hardware.org/?probe=0c52aebe31) | Mar 23, 2020 |
| Intel         | D34010WYK H14771-303        | [0c19bbe87a](https://linux-hardware.org/?probe=0c19bbe87a) | Feb 18, 2020 |
| HP            | ProLiant MicroServer        | [363851a935](https://linux-hardware.org/?probe=363851a935) | Dec 19, 2019 |
| HP            | ProLiant MicroServer        | [708dff507f](https://linux-hardware.org/?probe=708dff507f) | Dec 19, 2019 |
| Dell          | OptiPlex GX620              | [21f221a304](https://linux-hardware.org/?probe=21f221a304) | May 17, 2019 |
| Dell          | OptiPlex GX620              | [3e9258a7c5](https://linux-hardware.org/?probe=3e9258a7c5) | Apr 15, 2019 |
| Dell          | OptiPlex GX620              | [87babb0fa3](https://linux-hardware.org/?probe=87babb0fa3) | Apr 15, 2019 |
| Gigabyte      | 945GCM-S2L                  | [d950de89e7](https://linux-hardware.org/?probe=d950de89e7) | Mar 26, 2019 |
| Gigabyte      | 970A-UD3P                   | [d425ca175b](https://linux-hardware.org/?probe=d425ca175b) | Oct 11, 2018 |
| Intel         | DG31PR AAD97573-205         | [693096a808](https://linux-hardware.org/?probe=693096a808) | Sep 06, 2018 |
| ASUSTek       | P8Z77-V                     | [bcdb9633d9](https://linux-hardware.org/?probe=bcdb9633d9) | Sep 05, 2018 |
| Foxconn       | 945 7MA Series              | [95d9e1dba9](https://linux-hardware.org/?probe=95d9e1dba9) | Nov 14, 2017 |
| ASUSTek       | H61M-K                      | [78a1c15c22](https://linux-hardware.org/?probe=78a1c15c22) | Sep 09, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| LMDE 4 | 148      | 56.92%  |
| LMDE 5 | 102      | 39.23%  |
| LMDE 3 | 8        | 3.08%   |
| LMDE 2 | 2        | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LMDE | 257      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.0-21-amd64          | 25       | 8.68%   |
| 4.19.0-16-amd64          | 23       | 7.99%   |
| 4.19.0-17-amd64          | 20       | 6.94%   |
| 4.19.0-18-amd64          | 19       | 6.6%    |
| 5.10.0-12-amd64          | 18       | 6.25%   |
| 4.19.0-14-amd64          | 18       | 6.25%   |
| 4.19.0-13-amd64          | 17       | 5.9%    |
| 4.19.0-8-amd64           | 15       | 5.21%   |
| 5.10.0-20-amd64          | 12       | 4.17%   |
| 5.10.0-17-amd64          | 11       | 3.82%   |
| 5.10.0-14-amd64          | 10       | 3.47%   |
| 5.10.0-13-amd64          | 10       | 3.47%   |
| 5.10.0-18-amd64          | 9        | 3.13%   |
| 4.19.0-12-amd64          | 9        | 3.13%   |
| 5.10.0-19-amd64          | 8        | 2.78%   |
| 4.19.0-10-amd64          | 8        | 2.78%   |
| 4.19.0-9-amd64           | 7        | 2.43%   |
| 4.9.0-8-amd64            | 4        | 1.39%   |
| 4.19.0-11-amd64          | 4        | 1.39%   |
| 5.10.0-15-amd64          | 3        | 1.04%   |
| 4.19.0-17-686            | 3        | 1.04%   |
| 4.19.0-16-686            | 3        | 1.04%   |
| 4.19.0-14-686            | 3        | 1.04%   |
| 5.10.0-16-amd64          | 2        | 0.69%   |
| 4.19.0-8-686             | 2        | 0.69%   |
| 4.19.0-20-amd64          | 2        | 0.69%   |
| 4.19.0-19-686            | 2        | 0.69%   |
| 4.19.0-18-686            | 2        | 0.69%   |
| 4.19.0-13-686            | 2        | 0.69%   |
| 3.16.0-4-amd64           | 2        | 0.69%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1        | 0.35%   |
| 5.8.0-3-amd64            | 1        | 0.35%   |
| 5.6.0-0.bpo.2-amd64      | 1        | 0.35%   |
| 5.4.0-0.bpo.4-amd64      | 1        | 0.35%   |
| 5.19.0-0.deb11.2-amd64   | 1        | 0.35%   |
| 5.10.0-7-amd64           | 1        | 0.35%   |
| 5.10.0-13-686            | 1        | 0.35%   |
| 4.9.0-9-amd64            | 1        | 0.35%   |
| 4.9.0-17-amd64           | 1        | 0.35%   |
| 4.9.0-11-amd64           | 1        | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 144      | 55.38%  |
| 5.10.0  | 101      | 38.85%  |
| 4.9.0   | 7        | 2.69%   |
| 3.16.0  | 2        | 0.77%   |
| 6.0.2   | 1        | 0.38%   |
| 5.8.0   | 1        | 0.38%   |
| 5.6.0   | 1        | 0.38%   |
| 5.4.0   | 1        | 0.38%   |
| 5.19.0  | 1        | 0.38%   |
| 4.17.0  | 1        | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 144      | 55.38%  |
| 5.10    | 101      | 38.85%  |
| 4.9     | 7        | 2.69%   |
| 3.16    | 2        | 0.77%   |
| 6.0     | 1        | 0.38%   |
| 5.8     | 1        | 0.38%   |
| 5.6     | 1        | 0.38%   |
| 5.4     | 1        | 0.38%   |
| 5.19    | 1        | 0.38%   |
| 4.17    | 1        | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 237      | 92.22%  |
| i686   | 20       | 7.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 220      | 85.27%  |
| Cinnamon   | 22       | 8.53%   |
| MATE       | 6        | 2.33%   |
| Unknown    | 3        | 1.16%   |
| XFCE       | 2        | 0.78%   |
| GNOME      | 2        | 0.78%   |
| LXQt       | 1        | 0.39%   |
| LXDE       | 1        | 0.39%   |
| KDE5       | 1        | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 257      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 197      | 76.65%  |
| LightDM | 40       | 15.56%  |
| TDM     | 15       | 5.84%   |
| MDM     | 2        | 0.78%   |
| GDM     | 2        | 0.78%   |
| SDDM    | 1        | 0.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 75       | 29.18%  |
| de_DE   | 33       | 12.84%  |
| pt_BR   | 23       | 8.95%   |
| fr_FR   | 16       | 6.23%   |
| ru_RU   | 13       | 5.06%   |
| pl_PL   | 9        | 3.5%    |
| Unknown | 9        | 3.5%    |
| it_IT   | 8        | 3.11%   |
| en_GB   | 8        | 3.11%   |
| en_CA   | 7        | 2.72%   |
| sv_SE   | 5        | 1.95%   |
| es_ES   | 5        | 1.95%   |
| en_AU   | 4        | 1.56%   |
| nl_BE   | 3        | 1.17%   |
| fr_CA   | 3        | 1.17%   |
| es_AR   | 3        | 1.17%   |
| cs_CZ   | 3        | 1.17%   |
| sk_SK   | 2        | 0.78%   |
| pt_PT   | 2        | 0.78%   |
| hu_HU   | 2        | 0.78%   |
| en_ZA   | 2        | 0.78%   |
| de_AT   | 2        | 0.78%   |
| ar_EG   | 2        | 0.78%   |
| unm_US  | 1        | 0.39%   |
| uk_UA   | 1        | 0.39%   |
| tr_TR   | 1        | 0.39%   |
| ru_UA   | 1        | 0.39%   |
| nb_NO   | 1        | 0.39%   |
| it_CH   | 1        | 0.39%   |
| fr_BE   | 1        | 0.39%   |
| fi_FI   | 1        | 0.39%   |
| et_EE   | 1        | 0.39%   |
| es_UY   | 1        | 0.39%   |
| es_NI   | 1        | 0.39%   |
| es_MX   | 1        | 0.39%   |
| es_EC   | 1        | 0.39%   |
| es_CO   | 1        | 0.39%   |
| es_CL   | 1        | 0.39%   |
| el_GR   | 1        | 0.39%   |
| ca_ES   | 1        | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 171      | 66.28%  |
| EFI  | 87       | 33.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 240      | 93.02%  |
| Btrfs   | 7        | 2.71%   |
| Unknown | 5        | 1.94%   |
| Tmpfs   | 3        | 1.16%   |
| Overlay | 2        | 0.78%   |
| Ext3    | 1        | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 197      | 76.06%  |
| GPT     | 36       | 13.9%   |
| MBR     | 26       | 10.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 238      | 91.89%  |
| Yes       | 21       | 8.11%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 230      | 89.49%  |
| Yes       | 27       | 10.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 59       | 22.96%  |
| Gigabyte Technology | 41       | 15.95%  |
| MSI                 | 29       | 11.28%  |
| Dell                | 29       | 11.28%  |
| Hewlett-Packard     | 17       | 6.61%   |
| ASRock              | 17       | 6.61%   |
| Intel               | 10       | 3.89%   |
| Acer                | 9        | 3.5%    |
| Lenovo              | 5        | 1.95%   |
| Unknown             | 5        | 1.95%   |
| Foxconn             | 4        | 1.56%   |
| ECS                 | 4        | 1.56%   |
| Pegatron            | 3        | 1.17%   |
| OEM                 | 2        | 0.78%   |
| Fujitsu             | 2        | 0.78%   |
| EVGA                | 2        | 0.78%   |
| eMachines           | 2        | 0.78%   |
| Biostar             | 2        | 0.78%   |
| SiYW                | 1        | 0.39%   |
| Semp Toshiba        | 1        | 0.39%   |
| Samsung Electronics | 1        | 0.39%   |
| Positivo            | 1        | 0.39%   |
| PCWare              | 1        | 0.39%   |
| NEC Computers       | 1        | 0.39%   |
| Medion              | 1        | 0.39%   |
| Gateway             | 1        | 0.39%   |
| Fujitsu Siemens     | 1        | 0.39%   |
| Digiboard           | 1        | 0.39%   |
| DFI                 | 1        | 0.39%   |
| BESSTAR Tech        | 1        | 0.39%   |
| AZW                 | 1        | 0.39%   |
| Alienware           | 1        | 0.39%   |
| ADVANSUS            | 1        | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 6        | 2.33%   |
| Dell OptiPlex 780               | 3        | 1.17%   |
| ASUS All Series                 | 3        | 1.17%   |
| MSI MS-7C52                     | 2        | 0.78%   |
| HP Pavilion Desktop 590-p0xxx   | 2        | 0.78%   |
| HP 290 G2 MT Business PC        | 2        | 0.78%   |
| Gigabyte X570 AORUS ULTRA       | 2        | 0.78%   |
| Gigabyte B450M DS3H             | 2        | 0.78%   |
| Gigabyte B450 AORUS M           | 2        | 0.78%   |
| Dell OptiPlex 3010              | 2        | 0.78%   |
| ASUS PRIME B350M-A              | 2        | 0.78%   |
| ASRock A320M-HDV R4.0           | 2        | 0.78%   |
| SiYW V200 Series                | 1        | 0.39%   |
| Semp Toshiba STI                | 1        | 0.39%   |
| Samsung DeskTop System          | 1        | 0.39%   |
| Positivo POS-EIH61CE            | 1        | 0.39%   |
| Pegatron Pro 3015 Microtower PC | 1        | 0.39%   |
| Pegatron Elite 7300 Series MT   | 1        | 0.39%   |
| Pegatron 520-1188la             | 1        | 0.39%   |
| PCWare IPMH81G1                 | 1        | 0.39%   |
| OEM 45CMX/45GMX/45CMX-K         | 1        | 0.39%   |
| NEC Computers IMEDIA S9509      | 1        | 0.39%   |
| MSI PX714AA-ABH t3040.nl        | 1        | 0.39%   |
| MSI MS-7D54                     | 1        | 0.39%   |
| MSI MS-7C51                     | 1        | 0.39%   |
| MSI MS-7B79                     | 1        | 0.39%   |
| MSI MS-7B23                     | 1        | 0.39%   |
| MSI MS-7B17                     | 1        | 0.39%   |
| MSI MS-7A40                     | 1        | 0.39%   |
| MSI MS-7A38                     | 1        | 0.39%   |
| MSI MS-7984                     | 1        | 0.39%   |
| MSI MS-7977                     | 1        | 0.39%   |
| MSI MS-7974                     | 1        | 0.39%   |
| MSI MS-7918                     | 1        | 0.39%   |
| MSI MS-7851                     | 1        | 0.39%   |
| MSI MS-7850                     | 1        | 0.39%   |
| MSI MS-7823                     | 1        | 0.39%   |
| MSI MS-7817                     | 1        | 0.39%   |
| MSI MS-7815                     | 1        | 0.39%   |
| MSI MS-7751                     | 1        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 14       | 5.45%   |
| ASUS PRIME             | 10       | 3.89%   |
| Dell Precision         | 7        | 2.72%   |
| HP Compaq              | 6        | 2.33%   |
| Acer Aspire            | 6        | 2.33%   |
| Unknown                | 6        | 2.33%   |
| ASUS ROG               | 5        | 1.95%   |
| Gigabyte X570          | 4        | 1.56%   |
| Dell Inspiron          | 4        | 1.56%   |
| Lenovo ThinkCentre     | 3        | 1.17%   |
| Gigabyte B450M         | 3        | 1.17%   |
| Gigabyte B450          | 3        | 1.17%   |
| ASUS All               | 3        | 1.17%   |
| Acer Veriton           | 3        | 1.17%   |
| MSI MS-7C52            | 2        | 0.78%   |
| HP Pavilion            | 2        | 0.78%   |
| HP 290                 | 2        | 0.78%   |
| Gigabyte Z390          | 2        | 0.78%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.78%   |
| Foxconn 945            | 2        | 0.78%   |
| Dell Vostro            | 2        | 0.78%   |
| ASUS P5KPL-AM          | 2        | 0.78%   |
| ASRock A320M-HDV       | 2        | 0.78%   |
| SiYW V200              | 1        | 0.39%   |
| Semp Toshiba STI       | 1        | 0.39%   |
| Samsung DeskTop        | 1        | 0.39%   |
| Positivo POS-EIH61CE   | 1        | 0.39%   |
| Pegatron Pro           | 1        | 0.39%   |
| Pegatron Elite         | 1        | 0.39%   |
| Pegatron 520-1188la    | 1        | 0.39%   |
| PCWare IPMH81G1        | 1        | 0.39%   |
| OEM 45CMX              | 1        | 0.39%   |
| NEC Computers IMEDIA   | 1        | 0.39%   |
| MSI PX714AA-ABH        | 1        | 0.39%   |
| MSI MS-7D54            | 1        | 0.39%   |
| MSI MS-7C51            | 1        | 0.39%   |
| MSI MS-7B79            | 1        | 0.39%   |
| MSI MS-7B23            | 1        | 0.39%   |
| MSI MS-7B17            | 1        | 0.39%   |
| MSI MS-7A40            | 1        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 34       | 13.23%  |
| 2018 | 28       | 10.89%  |
| 2009 | 23       | 8.95%   |
| 2019 | 17       | 6.61%   |
| 2007 | 17       | 6.61%   |
| 2011 | 16       | 6.23%   |
| 2010 | 16       | 6.23%   |
| 2014 | 15       | 5.84%   |
| 2013 | 15       | 5.84%   |
| 2017 | 12       | 4.67%   |
| 2008 | 12       | 4.67%   |
| 2006 | 11       | 4.28%   |
| 2021 | 8        | 3.11%   |
| 2015 | 8        | 3.11%   |
| 2020 | 7        | 2.72%   |
| 2016 | 6        | 2.33%   |
| 2022 | 4        | 1.56%   |
| 2003 | 4        | 1.56%   |
| 2005 | 3        | 1.17%   |
| 2004 | 1        | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 257      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 255      | 98.46%  |
| Enabled  | 4        | 1.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 257      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 64       | 24.43%  |
| 16.01-24.0      | 49       | 18.7%   |
| 3.01-4.0        | 48       | 18.32%  |
| 4.01-8.0        | 36       | 13.74%  |
| 32.01-64.0      | 31       | 11.83%  |
| 2.01-3.0        | 11       | 4.2%    |
| 1.01-2.0        | 11       | 4.2%    |
| 0.51-1.0        | 5        | 1.91%   |
| 24.01-32.0      | 3        | 1.15%   |
| 64.01-256.0     | 3        | 1.15%   |
| More than 256.0 | 1        | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 118      | 42.6%   |
| 2.01-3.0   | 69       | 24.91%  |
| 3.01-4.0   | 33       | 11.91%  |
| 4.01-8.0   | 26       | 9.39%   |
| 0.51-1.0   | 26       | 9.39%   |
| 8.01-16.0  | 3        | 1.08%   |
| 32.01-64.0 | 1        | 0.36%   |
| 24.01-32.0 | 1        | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 121      | 45.49%  |
| 2      | 75       | 28.2%   |
| 3      | 33       | 12.41%  |
| 4      | 19       | 7.14%   |
| 5      | 8        | 3.01%   |
| 6      | 5        | 1.88%   |
| 7      | 4        | 1.5%    |
| 8      | 1        | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 139      | 53.05%  |
| No        | 123      | 46.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 256      | 99.61%  |
| No        | 1        | 0.39%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 158      | 60.08%  |
| Yes       | 105      | 39.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 203      | 78.38%  |
| Yes       | 56       | 21.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 43       | 16.73%  |
| Germany      | 37       | 14.4%   |
| Brazil       | 25       | 9.73%   |
| Russia       | 16       | 6.23%   |
| France       | 16       | 6.23%   |
| Canada       | 12       | 4.67%   |
| Italy        | 11       | 4.28%   |
| Spain        | 7        | 2.72%   |
| Poland       | 7        | 2.72%   |
| Ukraine      | 6        | 2.33%   |
| UK           | 6        | 2.33%   |
| Netherlands  | 6        | 2.33%   |
| Sweden       | 5        | 1.95%   |
| Australia    | 5        | 1.95%   |
| Belgium      | 4        | 1.56%   |
| South Africa | 3        | 1.17%   |
| Bulgaria     | 3        | 1.17%   |
| Austria      | 3        | 1.17%   |
| Argentina    | 3        | 1.17%   |
| Turkey       | 2        | 0.78%   |
| Slovakia     | 2        | 0.78%   |
| Puerto Rico  | 2        | 0.78%   |
| Portugal     | 2        | 0.78%   |
| Mexico       | 2        | 0.78%   |
| Hungary      | 2        | 0.78%   |
| Greece       | 2        | 0.78%   |
| Finland      | 2        | 0.78%   |
| Czechia      | 2        | 0.78%   |
| Venezuela    | 1        | 0.39%   |
| Uruguay      | 1        | 0.39%   |
| Serbia       | 1        | 0.39%   |
| Romania      | 1        | 0.39%   |
| Philippines  | 1        | 0.39%   |
| Pakistan     | 1        | 0.39%   |
| Norway       | 1        | 0.39%   |
| Nicaragua    | 1        | 0.39%   |
| Luxembourg   | 1        | 0.39%   |
| Latvia       | 1        | 0.39%   |
| Kazakhstan   | 1        | 0.39%   |
| India        | 1        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Hamburg               | 4        | 1.47%   |
| Paris                 | 3        | 1.1%    |
| Montreal              | 3        | 1.1%    |
| Melbourne             | 3        | 1.1%    |
| Frankfurt am Main     | 3        | 1.1%    |
| Berlin                | 3        | 1.1%    |
| Warsaw                | 2        | 0.73%   |
| Sofia                 | 2        | 0.73%   |
| San Antonio           | 2        | 0.73%   |
| Rio de Janeiro        | 2        | 0.73%   |
| Perth                 | 2        | 0.73%   |
| Nitra                 | 2        | 0.73%   |
| Moscow                | 2        | 0.73%   |
| Milan                 | 2        | 0.73%   |
| Marseille             | 2        | 0.73%   |
| Helsinki              | 2        | 0.73%   |
| Gothenburg            | 2        | 0.73%   |
| Florianópolis        | 2        | 0.73%   |
| Belo Horizonte        | 2        | 0.73%   |
| Bayamón              | 2        | 0.73%   |
| Athens                | 2        | 0.73%   |
| Amsterdam             | 2        | 0.73%   |
| Zaporozhe             | 1        | 0.37%   |
| Zaandam               | 1        | 0.37%   |
| Wroclaw               | 1        | 0.37%   |
| Wijchen               | 1        | 0.37%   |
| Weiden                | 1        | 0.37%   |
| Washington            | 1        | 0.37%   |
| Warmsen               | 1        | 0.37%   |
| Voronezh              | 1        | 0.37%   |
| Volta Redonda         | 1        | 0.37%   |
| Vitória da Conquista | 1        | 0.37%   |
| Vincennes             | 1        | 0.37%   |
| Vienna                | 1        | 0.37%   |
| Victoria              | 1        | 0.37%   |
| Vicente Guerrero      | 1        | 0.37%   |
| Varese                | 1        | 0.37%   |
| Valencia              | 1        | 0.37%   |
| Ulyanovsk             | 1        | 0.37%   |
| Ukhta                 | 1        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 96       | 168    | 22.33%  |
| Seagate                   | 73       | 116    | 16.98%  |
| Samsung Electronics       | 65       | 109    | 15.12%  |
| Kingston                  | 28       | 37     | 6.51%   |
| Toshiba                   | 21       | 30     | 4.88%   |
| Crucial                   | 19       | 24     | 4.42%   |
| Hitachi                   | 17       | 21     | 3.95%   |
| SanDisk                   | 16       | 19     | 3.72%   |
| A-DATA Technology         | 9        | 9      | 2.09%   |
| Phison                    | 7        | 8      | 1.63%   |
| Intel                     | 6        | 6      | 1.4%    |
| China                     | 6        | 6      | 1.4%    |
| Intenso                   | 4        | 5      | 0.93%   |
| SPCC                      | 3        | 3      | 0.7%    |
| SK hynix                  | 3        | 4      | 0.7%    |
| Silicon Motion            | 3        | 3      | 0.7%    |
| OCZ                       | 3        | 5      | 0.7%    |
| Micron Technology         | 3        | 3      | 0.7%    |
| Maxtor                    | 3        | 5      | 0.7%    |
| Unknown                   | 2        | 3      | 0.47%   |
| Transcend                 | 2        | 3      | 0.47%   |
| TCSUNBOW                  | 2        | 2      | 0.47%   |
| PNY                       | 2        | 2      | 0.47%   |
| Patriot                   | 2        | 2      | 0.47%   |
| Gigabyte Technology       | 2        | 3      | 0.47%   |
| CT500MX5                  | 2        | 3      | 0.47%   |
| Apple                     | 2        | 2      | 0.47%   |
| XrayDisk                  | 1        | 2      | 0.23%   |
| WALRAM                    | 1        | 1      | 0.23%   |
| TGT                       | 1        | 1      | 0.23%   |
| Team                      | 1        | 2      | 0.23%   |
| TakeMS                    | 1        | 1      | 0.23%   |
| Smartbuy                  | 1        | 1      | 0.23%   |
| SABRENT                   | 1        | 1      | 0.23%   |
| Plextor                   | 1        | 2      | 0.23%   |
| Phison Electronics        | 1        | 1      | 0.23%   |
| OCZ-VERTEX                | 1        | 1      | 0.23%   |
| Netac                     | 1        | 1      | 0.23%   |
| Mushkin                   | 1        | 1      | 0.23%   |
| Micron/Crucial Technology | 1        | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 9        | 1.78%   |
| Kingston SA400S37120G 120GB SSD                     | 7        | 1.39%   |
| Kingston SA400S37240G 240GB SSD                     | 6        | 1.19%   |
| Toshiba DT01ACA100 1TB                              | 5        | 0.99%   |
| Seagate ST1000DM010-2EP102 1TB                      | 5        | 0.99%   |
| Samsung SSD 850 EVO 500GB                           | 5        | 0.99%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4        | 0.79%   |
| Seagate ST500DM002-1BD142 500GB                     | 4        | 0.79%   |
| Samsung SSD 860 EVO 500GB                           | 4        | 0.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4        | 0.79%   |
| Kingston SA400S37480G 480GB SSD                     | 4        | 0.79%   |
| Toshiba HDWD110 1TB                                 | 3        | 0.59%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 0.59%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3        | 0.59%   |
| Seagate ST1000DM003-1ER162 1TB                      | 3        | 0.59%   |
| Seagate ST1000DM003-1CH162 1TB                      | 3        | 0.59%   |
| Samsung NVMe SSD Drive 500GB                        | 3        | 0.59%   |
| Samsung HD322HJ 320GB                               | 3        | 0.59%   |
| Samsung HD161HJ 160GB                               | 3        | 0.59%   |
| Samsung HD103SJ 1TB                                 | 3        | 0.59%   |
| Crucial CT480BX500SSD1 480GB                        | 3        | 0.59%   |
| Crucial CT240BX500SSD1 240GB                        | 3        | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2        | 0.4%    |
| WDC WD5000AAKX-00U6AA0 500GB                        | 2        | 0.4%    |
| WDC WD40EZAZ-00SF3B0 4TB                            | 2        | 0.4%    |
| WDC WD40EFRX-68N32N0 4TB                            | 2        | 0.4%    |
| WDC WD3200AAKS-00L9A0 320GB                         | 2        | 0.4%    |
| WDC WD3003FZEX-00Z4SA0 3TB                          | 2        | 0.4%    |
| WDC WD2500AAKX-753CA1 250GB                         | 2        | 0.4%    |
| WDC WD1600AABS-00PRA0 160GB                         | 2        | 0.4%    |
| WDC WD10EZEX-60WN4A0 1TB                            | 2        | 0.4%    |
| WDC WD10EARS-00Y5B1 1TB                             | 2        | 0.4%    |
| WDC WD1003FZEX-00MK2A0 1TB                          | 2        | 0.4%    |
| Unknown SD/MMC/MS PRO 64GB                          | 2        | 0.4%    |
| Toshiba DT01ACA300 3TB                              | 2        | 0.4%    |
| Toshiba DT01ACA200 2TB                              | 2        | 0.4%    |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB   | 2        | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                     | 2        | 0.4%    |
| Seagate ST3500418AS 500GB                           | 2        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 87       | 155    | 36.86%  |
| Seagate             | 73       | 115    | 30.93%  |
| Samsung Electronics | 29       | 39     | 12.29%  |
| Toshiba             | 17       | 22     | 7.2%    |
| Hitachi             | 17       | 21     | 7.2%    |
| Maxtor              | 3        | 5      | 1.27%   |
| Unknown             | 2        | 2      | 0.85%   |
| SABRENT             | 1        | 1      | 0.42%   |
| KESU                | 1        | 2      | 0.42%   |
| Intenso             | 1        | 1      | 0.42%   |
| HPE                 | 1        | 4      | 0.42%   |
| Fujitsu             | 1        | 1      | 0.42%   |
| ExcelStor           | 1        | 1      | 0.42%   |
| ASMedia             | 1        | 1      | 0.42%   |
| Apple               | 1        | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 28       | 41     | 17.61%  |
| Kingston            | 24       | 33     | 15.09%  |
| Crucial             | 18       | 23     | 11.32%  |
| SanDisk             | 14       | 17     | 8.81%   |
| WDC                 | 10       | 11     | 6.29%   |
| A-DATA Technology   | 9        | 9      | 5.66%   |
| China               | 6        | 6      | 3.77%   |
| Toshiba             | 4        | 8      | 2.52%   |
| Intel               | 4        | 4      | 2.52%   |
| SPCC                | 3        | 3      | 1.89%   |
| OCZ                 | 3        | 5      | 1.89%   |
| Micron Technology   | 3        | 3      | 1.89%   |
| Intenso             | 3        | 4      | 1.89%   |
| Transcend           | 2        | 3      | 1.26%   |
| TCSUNBOW            | 2        | 2      | 1.26%   |
| SK hynix            | 2        | 2      | 1.26%   |
| PNY                 | 2        | 2      | 1.26%   |
| Patriot             | 2        | 2      | 1.26%   |
| Gigabyte Technology | 2        | 3      | 1.26%   |
| CT500MX5            | 2        | 3      | 1.26%   |
| Unknown             | 1        | 1      | 0.63%   |
| Team                | 1        | 2      | 0.63%   |
| TakeMS              | 1        | 1      | 0.63%   |
| Smartbuy            | 1        | 1      | 0.63%   |
| Plextor             | 1        | 2      | 0.63%   |
| OCZ-VERTEX          | 1        | 1      | 0.63%   |
| Netac               | 1        | 1      | 0.63%   |
| KingSpec            | 1        | 1      | 0.63%   |
| Kingmax             | 1        | 1      | 0.63%   |
| Hewlett-Packard     | 1        | 1      | 0.63%   |
| GOODRAM             | 1        | 1      | 0.63%   |
| Dogfish             | 1        | 1      | 0.63%   |
| Apple               | 1        | 1      | 0.63%   |
| Apacer              | 1        | 1      | 0.63%   |
| 2.5''               | 1        | 1      | 0.63%   |
| Unknown             | 1        | 2      | 0.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 187      | 371    | 51.52%  |
| SSD     | 130      | 203    | 35.81%  |
| NVMe    | 41       | 58     | 11.29%  |
| Unknown | 5        | 6      | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 243      | 550    | 80.46%  |
| NVMe | 41       | 58     | 13.58%  |
| SAS  | 18       | 30     | 5.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 199      | 366    | 59.4%   |
| 0.51-1.0   | 83       | 127    | 24.78%  |
| 1.01-2.0   | 31       | 41     | 9.25%   |
| 3.01-4.0   | 8        | 14     | 2.39%   |
| 2.01-3.0   | 8        | 19     | 2.39%   |
| 4.01-10.0  | 6        | 7      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 76       | 28.57%  |
| 251-500        | 59       | 22.18%  |
| 1001-2000      | 38       | 14.29%  |
| 501-1000       | 27       | 10.15%  |
| More than 3000 | 22       | 8.27%   |
| 51-100         | 16       | 6.02%   |
| 2001-3000      | 14       | 5.26%   |
| 21-50          | 9        | 3.38%   |
| 1-20           | 5        | 1.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 87       | 31.52%  |
| 21-50          | 55       | 19.93%  |
| 51-100         | 32       | 11.59%  |
| 101-250        | 27       | 9.78%   |
| 251-500        | 25       | 9.06%   |
| 501-1000       | 19       | 6.88%   |
| 1001-2000      | 17       | 6.16%   |
| More than 3000 | 7        | 2.54%   |
| 2001-3000      | 7        | 2.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD2500BEVT-24A23T0 250GB      | 1        | 1      | 10%     |
| Seagate ST9320325AS 320GB         | 1        | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB   | 1        | 1      | 10%     |
| Seagate ST3250318AS 250GB         | 1        | 1      | 10%     |
| Seagate ST2000DX001-1CM164 2TB    | 1        | 1      | 10%     |
| Seagate ST1000LM048-2E7172 1TB    | 1        | 1      | 10%     |
| Samsung Electronics SP2004C 200GB | 1        | 1      | 10%     |
| Samsung Electronics HM500JI 500GB | 1        | 1      | 10%     |
| Samsung Electronics HD153WI 1TB   | 1        | 1      | 10%     |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 50%     |
| Samsung Electronics | 4        | 4      | 40%     |
| WDC                 | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 50%     |
| Samsung Electronics | 4        | 4      | 40%     |
| WDC                 | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 10     | 100%    |

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
| Detected | 204      | 485    | 73.91%  |
| Works    | 62       | 143    | 22.46%  |
| Malfunc  | 10       | 10     | 3.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 177      | 51.6%   |
| AMD                              | 62       | 18.08%  |
| Samsung Electronics              | 18       | 5.25%   |
| Nvidia                           | 13       | 3.79%   |
| ASMedia Technology               | 13       | 3.79%   |
| JMicron Technology               | 12       | 3.5%    |
| Phison Electronics               | 9        | 2.62%   |
| Marvell Technology Group         | 7        | 2.04%   |
| VIA Technologies                 | 6        | 1.75%   |
| Silicon Motion                   | 4        | 1.17%   |
| SanDisk                          | 4        | 1.17%   |
| Kingston Technology Company      | 4        | 1.17%   |
| Broadcom / LSI                   | 4        | 1.17%   |
| Silicon Integrated Systems [SiS] | 2        | 0.58%   |
| Silicon Image                    | 2        | 0.58%   |
| Micron/Crucial Technology        | 2        | 0.58%   |
| SK hynix                         | 1        | 0.29%   |
| LSI Logic / Symbios Logic        | 1        | 0.29%   |
| Integrated Technology Express    | 1        | 0.29%   |
| ADATA Technology                 | 1        | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 34       | 7.36%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 24       | 5.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 21       | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 21       | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14       | 3.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 2.81%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13       | 2.81%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 2.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 2.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9        | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 1.95%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 1.73%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 1.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 1.73%   |
| AMD FCH SATA Controller D                                                               | 8        | 1.73%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7        | 1.52%   |
| Nvidia MCP61 IDE                                                                        | 6        | 1.3%    |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.3%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.3%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 1.3%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 5        | 1.08%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5        | 1.08%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.08%   |
| Phison E12 NVMe Controller                                                              | 4        | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4        | 0.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.87%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 0.87%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 0.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 0.87%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3        | 0.65%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.65%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3        | 0.65%   |
| JMicron JMB368 IDE controller                                                           | 3        | 0.65%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 187      | 53.58%  |
| IDE  | 97       | 27.79%  |
| NVMe | 41       | 11.75%  |
| RAID | 17       | 4.87%   |
| SAS  | 5        | 1.43%   |
| SCSI | 2        | 0.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 180      | 70.04%  |
| AMD    | 77       | 29.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 8        | 3.1%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 2.33%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 1.55%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 4        | 1.55%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.55%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 4        | 1.55%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 4        | 1.55%   |
| Intel Pentium D CPU 2.80GHz                 | 3        | 1.16%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 3        | 1.16%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 1.16%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.16%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 1.16%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.16%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.16%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 3        | 1.16%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.16%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.16%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 1.16%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.16%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 1.16%   |
| AMD FX-4300 Quad-Core Processor             | 3        | 1.16%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 0.78%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 2        | 0.78%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 0.78%   |
| Intel Pentium D CPU 3.00GHz                 | 2        | 0.78%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 0.78%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 0.78%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.78%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.78%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 0.78%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.78%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.78%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.78%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.78%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz       | 2        | 0.78%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 0.78%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.78%   |
| AMD Sempron Processor 3000+                 | 2        | 0.78%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 36       | 13.95%  |
| Intel Core i7           | 32       | 12.4%   |
| Intel Core 2 Duo        | 20       | 7.75%   |
| Intel Xeon              | 16       | 6.2%    |
| Intel Core i3           | 16       | 6.2%    |
| AMD Ryzen 7             | 14       | 5.43%   |
| AMD Ryzen 5             | 13       | 5.04%   |
| Intel Core 2 Quad       | 12       | 4.65%   |
| Intel Pentium           | 10       | 3.88%   |
| Intel Celeron           | 9        | 3.49%   |
| AMD FX                  | 8        | 3.1%    |
| Intel Pentium D         | 7        | 2.71%   |
| Other                   | 5        | 1.94%   |
| Intel Pentium Dual-Core | 5        | 1.94%   |
| AMD Ryzen 3             | 5        | 1.94%   |
| Intel Core 2            | 4        | 1.55%   |
| AMD Sempron             | 4        | 1.55%   |
| AMD Phenom II X4        | 4        | 1.55%   |
| AMD Athlon 64 X2        | 4        | 1.55%   |
| Intel Pentium 4         | 3        | 1.16%   |
| AMD Phenom II X6        | 3        | 1.16%   |
| AMD Athlon XP           | 3        | 1.16%   |
| AMD Athlon II X2        | 3        | 1.16%   |
| AMD Athlon              | 3        | 1.16%   |
| Intel Pentium Gold      | 2        | 0.78%   |
| Intel Pentium Dual      | 2        | 0.78%   |
| Intel Core i9           | 2        | 0.78%   |
| AMD Ryzen 9             | 2        | 0.78%   |
| AMD Athlon II X4        | 2        | 0.78%   |
| AMD A4                  | 2        | 0.78%   |
| AMD Turion II Neo       | 1        | 0.39%   |
| AMD Ryzen 5 PRO         | 1        | 0.39%   |
| AMD Phenom II X2        | 1        | 0.39%   |
| AMD G                   | 1        | 0.39%   |
| AMD E1                  | 1        | 0.39%   |
| AMD A8                  | 1        | 0.39%   |
| AMD A10                 | 1        | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 102      | 39.53%  |
| 2      | 90       | 34.88%  |
| 8      | 25       | 9.69%   |
| 6      | 18       | 6.98%   |
| 1      | 13       | 5.04%   |
| 16     | 6        | 2.33%   |
| 3      | 2        | 0.78%   |
| 12     | 1        | 0.39%   |
| 10     | 1        | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 249      | 96.89%  |
| 2      | 8        | 3.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 148      | 57.36%  |
| 2      | 110      | 42.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 251      | 97.67%  |
| 32-bit         | 6        | 2.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 22       | 8.43%   |
| 0x1067a    | 22       | 8.43%   |
| Unknown    | 22       | 8.43%   |
| 0x306c3    | 19       | 7.28%   |
| 0x206a7    | 19       | 7.28%   |
| 0x08108109 | 8        | 3.07%   |
| 0x6fd      | 7        | 2.68%   |
| 0x506e3    | 7        | 2.68%   |
| 0x010000c8 | 7        | 2.68%   |
| 0x906ed    | 6        | 2.3%    |
| 0x6fb      | 6        | 2.3%    |
| 0x08701021 | 6        | 2.3%    |
| 0x0800820d | 6        | 2.3%    |
| 0x106e5    | 5        | 1.92%   |
| 0x10677    | 5        | 1.92%   |
| 0xf65      | 4        | 1.53%   |
| 0x906eb    | 4        | 1.53%   |
| 0x906ea    | 4        | 1.53%   |
| 0x06000852 | 4        | 1.53%   |
| 0xf64      | 3        | 1.15%   |
| 0xa0671    | 3        | 1.15%   |
| 0x6f2      | 3        | 1.15%   |
| 0x206d7    | 3        | 1.15%   |
| 0x106a5    | 3        | 1.15%   |
| 0x08101016 | 3        | 1.15%   |
| 0x06001119 | 3        | 1.15%   |
| 0xf29      | 2        | 0.77%   |
| 0xa0655    | 2        | 0.77%   |
| 0x906e9    | 2        | 0.77%   |
| 0x90675    | 2        | 0.77%   |
| 0x40651    | 2        | 0.77%   |
| 0x20655    | 2        | 0.77%   |
| 0x10676    | 2        | 0.77%   |
| 0x08701013 | 2        | 0.77%   |
| 0x0810100b | 2        | 0.77%   |
| 0x08001129 | 2        | 0.77%   |
| 0x0600063e | 2        | 0.77%   |
| 0x05000119 | 2        | 0.77%   |
| 0x010000dc | 2        | 0.77%   |
| 0xf47      | 1        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 29       | 11.24%  |
| SandyBridge   | 26       | 10.08%  |
| IvyBridge     | 24       | 9.3%    |
| Haswell       | 22       | 8.53%   |
| Core          | 19       | 7.36%   |
| KabyLake      | 18       | 6.98%   |
| Zen+          | 14       | 5.43%   |
| K10           | 14       | 5.43%   |
| NetBurst      | 12       | 4.65%   |
| Zen           | 10       | 3.88%   |
| Piledriver    | 9        | 3.49%   |
| Zen 2         | 8        | 3.1%    |
| Nehalem       | 8        | 3.1%    |
| Skylake       | 7        | 2.71%   |
| K8 Hammer     | 7        | 2.71%   |
| Zen 3         | 6        | 2.33%   |
| Unknown       | 5        | 1.94%   |
| Westmere      | 3        | 1.16%   |
| K6            | 3        | 1.16%   |
| CometLake     | 3        | 1.16%   |
| Bulldozer     | 3        | 1.16%   |
| Bobcat        | 2        | 0.78%   |
| Tremont       | 1        | 0.39%   |
| TigerLake     | 1        | 0.39%   |
| Jaguar        | 1        | 0.39%   |
| Goldmont plus | 1        | 0.39%   |
| Goldmont      | 1        | 0.39%   |
| Broadwell     | 1        | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 124      | 44.6%   |
| Intel                      | 84       | 30.22%  |
| AMD                        | 63       | 22.66%  |
| VIA Technologies           | 4        | 1.44%   |
| S3 Graphics                | 1        | 0.36%   |
| Matrox Electronics Systems | 1        | 0.36%   |
| ASPEED Technology          | 1        | 0.36%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 18       | 6.29%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 11       | 3.85%   |
| Nvidia GT218 [GeForce 210]                                                  | 9        | 3.15%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 9        | 3.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 3.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 3.15%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 2.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 8        | 2.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 8        | 2.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 2.45%   |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 2.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.75%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.4%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.4%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 1.4%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 1.4%    |
| AMD RV710 [Radeon HD 4350/4550]                                             | 4        | 1.4%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.05%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.05%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 1.05%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 3        | 1.05%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.05%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.7%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.7%    |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 2        | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.7%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.7%    |
| Nvidia GF119 [NVS 310]                                                      | 2        | 0.7%    |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 2        | 0.7%    |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 0.7%    |
| Nvidia G92 [GeForce GTS 250]                                                | 2        | 0.7%    |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 0.7%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 0.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.7%    |
| Intel HD Graphics 530                                                       | 2        | 0.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2        | 0.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.7%    |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 115      | 44.23%  |
| 1 x Intel       | 68       | 26.15%  |
| 1 x AMD         | 54       | 20.77%  |
| Intel + Nvidia  | 6        | 2.31%   |
| 2 x AMD         | 5        | 1.92%   |
| 1 x VIA         | 4        | 1.54%   |
| AMD + Nvidia    | 3        | 1.15%   |
| 2 x Nvidia      | 1        | 0.38%   |
| 1 x S3 Graphics | 1        | 0.38%   |
| 1 x Matrox      | 1        | 0.38%   |
| Intel + AMD     | 1        | 0.38%   |
| 1 x ASPEED      | 1        | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 174      | 66.67%  |
| Proprietary | 54       | 20.69%  |
| Unknown     | 33       | 12.64%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 102      | 38.93%  |
| 1.01-2.0   | 41       | 15.65%  |
| 0.01-0.5   | 35       | 13.36%  |
| 0.51-1.0   | 34       | 12.98%  |
| 3.01-4.0   | 23       | 8.78%   |
| 7.01-8.0   | 16       | 6.11%   |
| 5.01-6.0   | 5        | 1.91%   |
| 2.01-3.0   | 3        | 1.15%   |
| 8.01-16.0  | 2        | 0.76%   |
| 16.01-24.0 | 1        | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 47       | 17.8%   |
| Goldstar             | 28       | 10.61%  |
| Dell                 | 24       | 9.09%   |
| Acer                 | 24       | 9.09%   |
| Hewlett-Packard      | 14       | 5.3%    |
| BenQ                 | 14       | 5.3%    |
| AOC                  | 12       | 4.55%   |
| Unknown              | 11       | 4.17%   |
| Philips              | 11       | 4.17%   |
| Ancor Communications | 11       | 4.17%   |
| Sony                 | 6        | 2.27%   |
| Lenovo               | 5        | 1.89%   |
| Iiyama               | 5        | 1.89%   |
| Fujitsu Siemens      | 4        | 1.52%   |
| ___                  | 2        | 0.76%   |
| ViewSonic            | 2        | 0.76%   |
| Sceptre Tech         | 2        | 0.76%   |
| NEC Computers        | 2        | 0.76%   |
| Medion               | 2        | 0.76%   |
| LG Electronics       | 2        | 0.76%   |
| eMachines            | 2        | 0.76%   |
| AUS                  | 2        | 0.76%   |
| ASUSTek Computer     | 2        | 0.76%   |
| Vestel               | 1        | 0.38%   |
| Unknown (XXX)        | 1        | 0.38%   |
| Toshiba              | 1        | 0.38%   |
| Targa Visionary      | 1        | 0.38%   |
| SKY                  | 1        | 0.38%   |
| PLN                  | 1        | 0.38%   |
| OEM                  | 1        | 0.38%   |
| Nixeus               | 1        | 0.38%   |
| NCS                  | 1        | 0.38%   |
| MSI                  | 1        | 0.38%   |
| Mitsubishi           | 1        | 0.38%   |
| Microstep            | 1        | 0.38%   |
| Lenovo Group Limited | 1        | 0.38%   |
| Insignia             | 1        | 0.38%   |
| IBM                  | 1        | 0.38%   |
| HUAWEI               | 1        | 0.38%   |
| HPN                  | 1        | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 3        | 1.08%   |
| Unknown LCD Monitor SAMSUNG                                         | 2        | 0.72%   |
| Sony LCD Monitor TV 3840x1080                                       | 2        | 0.72%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch | 2        | 0.72%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch   | 2        | 0.72%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch             | 2        | 0.72%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                 | 2        | 0.72%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 2        | 0.72%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch               | 2        | 0.72%   |
| Dell P190S DEL405B 1280x1024 376x301mm 19.0-inch                    | 2        | 0.72%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                   | 2        | 0.72%   |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                       | 2        | 0.72%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch    | 2        | 0.72%   |
| Acer T272HL ACR013B 1920x1080 598x336mm 27.0-inch                   | 2        | 0.72%   |
| ___ LCDTV16 ___0101 1360x768                                        | 1        | 0.36%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch               | 1        | 0.36%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch          | 1        | 0.36%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch            | 1        | 0.36%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                           | 1        | 0.36%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                  | 1        | 0.36%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                  | 1        | 0.36%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                               | 1        | 0.36%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                               | 1        | 0.36%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                | 1        | 0.36%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                   | 1        | 0.36%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                            | 1        | 0.36%   |
| Unknown LCD Monitor Dell SE2717H/HX 1920x1080                       | 1        | 0.36%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch              | 1        | 0.36%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch       | 1        | 0.36%   |
| Toshiba LCD Monitor TV 1920x1080                                    | 1        | 0.36%   |
| Targa Visionary LCD19-4 TARA194 1280x1024 376x301mm 19.0-inch       | 1        | 0.36%   |
| Sony TV SNY8E01 1360x768                                            | 1        | 0.36%   |
| Sony TV SNY4C03 1920x1080 1063x598mm 48.0-inch                      | 1        | 0.36%   |
| Sony TV SNY1B02 1360x768                                            | 1        | 0.36%   |
| Sony TV  *00 SNYF503 1920x1080 1220x680mm 55.0-inch                 | 1        | 0.36%   |
| Sony LCD Monitor TV  *00 1920x1080                                  | 1        | 0.36%   |
| SKY TV SKY1502 3840x2160 708x398mm 32.0-inch                        | 1        | 0.36%   |
| SKY TV SKY1502 3840x2160 1150x650mm 52.0-inch                       | 1        | 0.36%   |
| SKY Toshiba TV SKY1402 3840x2160 708x398mm 32.0-inch                | 1        | 0.36%   |
| Sceptre Tech F24 SPT0961 1920x1080 480x260mm 21.5-inch              | 1        | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 113      | 44.66%  |
| 1280x1024 (SXGA)   | 35       | 13.83%  |
| 1680x1050 (WSXGA+) | 18       | 7.11%   |
| 1366x768 (WXGA)    | 12       | 4.74%   |
| 1440x900 (WXGA+)   | 11       | 4.35%   |
| 3840x2160 (4K)     | 9        | 3.56%   |
| 1360x768           | 8        | 3.16%   |
| 1920x1200 (WUXGA)  | 7        | 2.77%   |
| 1600x900 (HD+)     | 7        | 2.77%   |
| 3440x1440          | 6        | 2.37%   |
| 2560x1440 (QHD)    | 6        | 2.37%   |
| Unknown            | 6        | 2.37%   |
| 1024x768 (XGA)     | 5        | 1.98%   |
| 3840x1080          | 3        | 1.19%   |
| 2560x1080          | 3        | 1.19%   |
| 7680x2160          | 1        | 0.4%    |
| 4480x1440          | 1        | 0.4%    |
| 4240x1440          | 1        | 0.4%    |
| 1600x1200          | 1        | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 16.6%   |
| 21      | 33       | 12.74%  |
| 24      | 27       | 10.42%  |
| 23      | 22       | 8.49%   |
| 19      | 22       | 8.49%   |
| 27      | 19       | 7.34%   |
| 18      | 18       | 6.95%   |
| 17      | 16       | 6.18%   |
| 22      | 11       | 4.25%   |
| 15      | 9        | 3.47%   |
| 20      | 8        | 3.09%   |
| 31      | 6        | 2.32%   |
| 34      | 5        | 1.93%   |
| 32      | 3        | 1.16%   |
| 72      | 2        | 0.77%   |
| 54      | 2        | 0.77%   |
| 52      | 2        | 0.77%   |
| 65      | 1        | 0.39%   |
| 64      | 1        | 0.39%   |
| 48      | 1        | 0.39%   |
| 33      | 1        | 0.39%   |
| 28      | 1        | 0.39%   |
| 26      | 1        | 0.39%   |
| 25      | 1        | 0.39%   |
| 16      | 1        | 0.39%   |
| 14      | 1        | 0.39%   |
| 13      | 1        | 0.39%   |
| 12      | 1        | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 73       | 29.2%   |
| 501-600     | 63       | 25.2%   |
| Unknown     | 43       | 17.2%   |
| 301-350     | 25       | 10%     |
| 351-400     | 18       | 7.2%    |
| 701-800     | 9        | 3.6%    |
| 601-700     | 9        | 3.6%    |
| 1001-1500   | 6        | 2.4%    |
| 201-300     | 2        | 0.8%    |
| 1501-2000   | 2        | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 120      | 49.18%  |
| Unknown | 42       | 17.21%  |
| 16/10   | 33       | 13.52%  |
| 5/4     | 30       | 12.3%   |
| 4/3     | 11       | 4.51%   |
| 21/9    | 7        | 2.87%   |
| 3/2     | 1        | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 76       | 29.8%   |
| Unknown        | 43       | 16.86%  |
| 151-200        | 40       | 15.69%  |
| 141-150        | 29       | 11.37%  |
| 301-350        | 20       | 7.84%   |
| 351-500        | 15       | 5.88%   |
| 251-300        | 11       | 4.31%   |
| 101-110        | 8        | 3.14%   |
| More than 1000 | 7        | 2.75%   |
| 111-120        | 3        | 1.18%   |
| 81-90          | 1        | 0.39%   |
| 71-80          | 1        | 0.39%   |
| 501-1000       | 1        | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 152      | 61.79%  |
| Unknown | 43       | 17.48%  |
| 101-120 | 39       | 15.85%  |
| 1-50    | 7        | 2.85%   |
| 121-160 | 4        | 1.63%   |
| 161-240 | 1        | 0.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 207      | 78.71%  |
| 2     | 38       | 14.45%  |
| 0     | 15       | 5.7%    |
| 3     | 3        | 1.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 151      | 41.71%  |
| Intel                            | 90       | 24.86%  |
| Qualcomm Atheros                 | 29       | 8.01%   |
| Ralink Technology                | 15       | 4.14%   |
| Broadcom                         | 12       | 3.31%   |
| Nvidia                           | 11       | 3.04%   |
| TP-Link                          | 8        | 2.21%   |
| VIA Technologies                 | 4        | 1.1%    |
| Marvell Technology Group         | 4        | 1.1%    |
| Samsung Electronics              | 3        | 0.83%   |
| Ralink                           | 3        | 0.83%   |
| Huawei Technologies              | 3        | 0.83%   |
| Broadcom Limited                 | 3        | 0.83%   |
| Sitecom Europe                   | 2        | 0.55%   |
| NetGear                          | 2        | 0.55%   |
| Microsoft                        | 2        | 0.55%   |
| MediaTek                         | 2        | 0.55%   |
| AVM                              | 2        | 0.55%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.28%   |
| Silicon Integrated Systems [SiS] | 1        | 0.28%   |
| Qualcomm                         | 1        | 0.28%   |
| Mercucys                         | 1        | 0.28%   |
| Mellanox Technologies            | 1        | 0.28%   |
| LSI                              | 1        | 0.28%   |
| JMicron Technology               | 1        | 0.28%   |
| IMC Networks                     | 1        | 0.28%   |
| HTC (High Tech Computer)         | 1        | 0.28%   |
| Edimax Technology                | 1        | 0.28%   |
| DisplayLink                      | 1        | 0.28%   |
| D-Link System                    | 1        | 0.28%   |
| Belkin Components                | 1        | 0.28%   |
| ASUSTek Computer                 | 1        | 0.28%   |
| ADMtek                           | 1        | 0.28%   |
| 3Com                             | 1        | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 112      | 27.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14       | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 12       | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 2.46%   |
| Nvidia MCP61 Ethernet                                             | 8        | 1.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7        | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 1.48%   |
| Intel Wi-Fi 6 AX200                                               | 6        | 1.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 1.23%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5        | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 5        | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 1.23%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.23%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4        | 0.99%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 0.99%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4        | 0.99%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 0.99%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.74%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 3        | 0.74%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3        | 0.74%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.74%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3        | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.74%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.74%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 0.74%   |
| Huawei ANA-NX9                                                    | 3        | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.49%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.49%   |
| Realtek 802.11ac WLAN Adapter                                     | 2        | 0.49%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 2        | 0.49%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 33       | 28.7%   |
| Intel                 | 23       | 20%     |
| Ralink Technology     | 15       | 13.04%  |
| Qualcomm Atheros      | 12       | 10.43%  |
| TP-Link               | 8        | 6.96%   |
| Broadcom              | 4        | 3.48%   |
| Ralink                | 3        | 2.61%   |
| Sitecom Europe        | 2        | 1.74%   |
| NetGear               | 2        | 1.74%   |
| Microsoft             | 2        | 1.74%   |
| MediaTek              | 2        | 1.74%   |
| AVM                   | 2        | 1.74%   |
| Mercucys              | 1        | 0.87%   |
| IMC Networks          | 1        | 0.87%   |
| Edimax Technology     | 1        | 0.87%   |
| D-Link System         | 1        | 0.87%   |
| Broadcom Limited      | 1        | 0.87%   |
| Belkin Components     | 1        | 0.87%   |
| ASUSTek Computer      | 1        | 0.87%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7        | 5.98%   |
| Intel Wi-Fi 6 AX200                                            | 6        | 5.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 5        | 4.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4        | 3.42%   |
| Ralink MT7601U Wireless Adapter                                | 4        | 3.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3        | 2.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3        | 2.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 3        | 2.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3        | 2.56%   |
| Ralink RT5370 Wireless Adapter                                 | 3        | 2.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3        | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3        | 2.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2        | 1.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2        | 1.71%   |
| Realtek 802.11ac WLAN Adapter                                  | 2        | 1.71%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 2        | 1.71%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 2        | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 1.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2        | 1.71%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 2        | 1.71%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2        | 1.71%   |
| Intel Wireless-AC 9260                                         | 2        | 1.71%   |
| Intel Wireless 7265                                            | 2        | 1.71%   |
| Intel Wireless 3165                                            | 2        | 1.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 0.85%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 0.85%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                          | 1        | 0.85%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 1        | 0.85%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 0.85%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                | 1        | 0.85%   |
| Sitecom Europe RTL8188S WLAN Adapter                           | 1        | 0.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.85%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 0.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 0.85%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 0.85%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1        | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 0.85%   |
| Realtek RTL8187 Wireless Adapter                               | 1        | 0.85%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 1        | 0.85%   |
| Realtek 802.11ac NIC                                           | 1        | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 137      | 49.46%  |
| Intel                            | 80       | 28.88%  |
| Qualcomm Atheros                 | 17       | 6.14%   |
| Nvidia                           | 11       | 3.97%   |
| Broadcom                         | 8        | 2.89%   |
| VIA Technologies                 | 4        | 1.44%   |
| Marvell Technology Group         | 4        | 1.44%   |
| Samsung Electronics              | 3        | 1.08%   |
| Huawei Technologies              | 3        | 1.08%   |
| Broadcom Limited                 | 2        | 0.72%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.36%   |
| Silicon Integrated Systems [SiS] | 1        | 0.36%   |
| Qualcomm                         | 1        | 0.36%   |
| JMicron Technology               | 1        | 0.36%   |
| HTC (High Tech Computer)         | 1        | 0.36%   |
| DisplayLink                      | 1        | 0.36%   |
| ADMtek                           | 1        | 0.36%   |
| 3Com                             | 1        | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 112      | 39.02%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14       | 4.88%   |
| Intel I211 Gigabit Network Connection                             | 12       | 4.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 3.48%   |
| Nvidia MCP61 Ethernet                                             | 8        | 2.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 2.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 1.74%   |
| Intel Ethernet Connection I217-V                                  | 5        | 1.74%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 1.74%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.74%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 1.39%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4        | 1.39%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 1.05%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 1.05%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 1.05%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 1.05%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.05%   |
| Huawei ANA-NX9                                                    | 3        | 1.05%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.7%    |
| Nvidia nForce2 Ethernet Controller                                | 2        | 0.7%    |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 0.7%    |
| Intel I210 Gigabit Network Connection                             | 2        | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 2        | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.7%    |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.7%    |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 0.7%    |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 0.7%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.7%    |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1        | 0.35%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 256      | 70.52%  |
| WiFi     | 105      | 28.93%  |
| Modem    | 1        | 0.28%   |
| Unknown  | 1        | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 213      | 79.78%  |
| WiFi     | 54       | 20.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 180      | 70.04%  |
| 2     | 69       | 26.85%  |
| 3     | 6        | 2.33%   |
| 4     | 1        | 0.39%   |
| 0     | 1        | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 211      | 79.32%  |
| Yes  | 55       | 20.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 22       | 37.93%  |
| Cambridge Silicon Radio         | 16       | 27.59%  |
| Realtek Semiconductor           | 5        | 8.62%   |
| Broadcom                        | 4        | 6.9%    |
| Qualcomm Atheros Communications | 2        | 3.45%   |
| MediaTek                        | 2        | 3.45%   |
| Lite-On Technology              | 2        | 3.45%   |
| ASUSTek Computer                | 2        | 3.45%   |
| Dynex                           | 1        | 1.72%   |
| Dell                            | 1        | 1.72%   |
| Apple                           | 1        | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 16       | 27.59%  |
| Intel Bluetooth wireless interface                       | 6        | 10.34%  |
| Intel AX200 Bluetooth                                    | 6        | 10.34%  |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 5.17%   |
| Intel Wireless-AC 3168 Bluetooth                         | 3        | 5.17%   |
| Realtek Bluetooth Radio                                  | 2        | 3.45%   |
| MediaTek Wireless_Device                                 | 2        | 3.45%   |
| Lite-On Bluetooth Device                                 | 2        | 3.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 2        | 3.45%   |
| Intel AX201 Bluetooth                                    | 2        | 3.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2        | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 1.72%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 1.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 1.72%   |
| Intel AX210 Bluetooth                                    | 1        | 1.72%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.72%   |
| Dell BT Mini-Receiver                                    | 1        | 1.72%   |
| Broadcom HP Bluethunder                                  | 1        | 1.72%   |
| Broadcom BCM92045B3 ROM                                  | 1        | 1.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 1        | 1.72%   |
| Broadcom BCM2045 Bluetooth                               | 1        | 1.72%   |
| Apple Bluetooth USB Host Controller                      | 1        | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 164      | 39.61%  |
| Nvidia                               | 110      | 26.57%  |
| AMD                                  | 82       | 19.81%  |
| C-Media Electronics                  | 15       | 3.62%   |
| VIA Technologies                     | 8        | 1.93%   |
| Generalplus Technology               | 5        | 1.21%   |
| GN Netcom                            | 4        | 0.97%   |
| Creative Labs                        | 4        | 0.97%   |
| Logitech                             | 3        | 0.72%   |
| JMTek                                | 3        | 0.72%   |
| Silicon Integrated Systems [SiS]     | 2        | 0.48%   |
| Plantronics                          | 2        | 0.48%   |
| Yamaha                               | 1        | 0.24%   |
| Xilinx                               | 1        | 0.24%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.24%   |
| Tenx Technology                      | 1        | 0.24%   |
| Sony                                 | 1        | 0.24%   |
| Native Instruments                   | 1        | 0.24%   |
| Micro Star International             | 1        | 0.24%   |
| M-Audio                              | 1        | 0.24%   |
| GYROCOM C&C                          | 1        | 0.24%   |
| Focusrite-Novation                   | 1        | 0.24%   |
| Evolution Electronics                | 1        | 0.24%   |
| Creative Technology                  | 1        | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 27       | 5.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 23       | 4.95%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 18       | 3.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16       | 3.44%   |
| AMD Family 17h/19h HD Audio Controller                                     | 16       | 3.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 15       | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 3.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13       | 2.8%    |
| Nvidia High Definition Audio Controller                                    | 12       | 2.58%   |
| Intel Cannon Lake PCH cAVS                                                 | 11       | 2.37%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 11       | 2.37%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11       | 2.37%   |
| Nvidia GM206 High Definition Audio Controller                              | 10       | 2.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10       | 2.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 1.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 1.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 1.94%   |
| Nvidia MCP61 High Definition Audio                                         | 8        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 1.51%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 1.08%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 1.08%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.08%   |
| Generalplus Technology USB Audio Device                                    | 5        | 1.08%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 5        | 1.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.08%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.08%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 4        | 0.86%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.86%   |
| Nvidia GK104 HDMI Audio Controller                                         | 4        | 0.86%   |
| Nvidia GF116 High Definition Audio Controller                              | 4        | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 0.86%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 0.86%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4        | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 21       | 27.27%  |
| Samsung Electronics | 10       | 12.99%  |
| Kingston            | 10       | 12.99%  |
| Crucial             | 8        | 10.39%  |
| Micron Technology   | 5        | 6.49%   |
| Corsair             | 5        | 6.49%   |
| SK hynix            | 4        | 5.19%   |
| G.Skill             | 4        | 5.19%   |
| Smart               | 1        | 1.3%    |
| PLEXHD              | 1        | 1.3%    |
| Nanya Technology    | 1        | 1.3%    |
| KLEVV               | 1        | 1.3%    |
| Kingmax             | 1        | 1.3%    |
| GeIL                | 1        | 1.3%    |
| Exceleram           | 1        | 1.3%    |
| Elpida              | 1        | 1.3%    |
| AVEXIR              | 1        | 1.3%    |
| A-DATA Technology   | 1        | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2        | 2.41%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 2        | 2.41%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 1.2%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                        | 1        | 1.2%    |
| Unknown RAM Module 512MB DIMM DDR2 266MT/s                     | 1        | 1.2%    |
| Unknown RAM Module 512MB DIMM 667MT/s                          | 1        | 1.2%    |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 1.2%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 1.2%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1        | 1.2%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1        | 1.2%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 1.2%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 1.2%    |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 1        | 1.2%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                    | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                    | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                     | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM 667MT/s                         | 1        | 1.2%    |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                       | 1        | 1.2%    |
| Unknown RAM Module 1GB DIMM DDR2 266MT/s                       | 1        | 1.2%    |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1        | 1.2%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                         | 1        | 1.2%    |
| Unknown RAM Module 1024MB DIMM                                 | 1        | 1.2%    |
| Unknown RAM D4 8G 8GB DIMM DDR4 2666MT/s                       | 1        | 1.2%    |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s             | 1        | 1.2%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s          | 1        | 1.2%    |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s                  | 1        | 1.2%    |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s          | 1        | 1.2%    |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 1.2%    |
| SK hynix RAM HKNNNFBMAVAR-NEH 2GB Row Of Chips LPDDR4 3200MT/s | 1        | 1.2%    |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                      | 1        | 1.2%    |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s                      | 1        | 1.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1.2%    |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s          | 1        | 1.2%    |
| Samsung RAM M393B5270DH0-YH9 4GB DIMM DDR3 1333MT/s            | 1        | 1.2%    |
| Samsung RAM M393B2G70DB0-CMA 16GB DIMM DDR3 1867MT/s           | 1        | 1.2%    |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1600MT/s            | 1        | 1.2%    |
| Samsung RAM M393B1G70BH0-YK0 8GB DIMM DDR3 1600MT/s            | 1        | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 26       | 37.14%  |
| DDR4    | 22       | 31.43%  |
| DDR2    | 8        | 11.43%  |
| Unknown | 6        | 8.57%   |
| SDRAM   | 4        | 5.71%   |
| DDR     | 3        | 4.29%   |
| LPDDR4  | 1        | 1.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 62       | 91.18%  |
| SODIMM       | 5        | 7.35%   |
| Row Of Chips | 1        | 1.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 22       | 29.33%  |
| 4096  | 20       | 26.67%  |
| 2048  | 15       | 20%     |
| 16384 | 9        | 12%     |
| 1024  | 6        | 8%      |
| 512   | 2        | 2.67%   |
| 32768 | 1        | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 25.68%  |
| 1333    | 8        | 10.81%  |
| 800     | 6        | 8.11%   |
| 667     | 5        | 6.76%   |
| 3200    | 4        | 5.41%   |
| 2667    | 4        | 5.41%   |
| 2400    | 4        | 5.41%   |
| 3600    | 3        | 4.05%   |
| 2133    | 3        | 4.05%   |
| 1866    | 2        | 2.7%    |
| 533     | 2        | 2.7%    |
| Unknown | 2        | 2.7%    |
| 4266    | 1        | 1.35%   |
| 3800    | 1        | 1.35%   |
| 3733    | 1        | 1.35%   |
| 3500    | 1        | 1.35%   |
| 3400    | 1        | 1.35%   |
| 2666    | 1        | 1.35%   |
| 1867    | 1        | 1.35%   |
| 1334    | 1        | 1.35%   |
| 1067    | 1        | 1.35%   |
| 1066    | 1        | 1.35%   |
| 400     | 1        | 1.35%   |
| 266     | 1        | 1.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 41.18%  |
| Brother Industries  | 3        | 17.65%  |
| Samsung Electronics | 2        | 11.76%  |
| Canon               | 2        | 11.76%  |
| Seiko Epson         | 1        | 5.88%   |
| Ricoh               | 1        | 5.88%   |
| Konica Minolta      | 1        | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Brother MFC-L2685DW              | 2        | 11.76%  |
| Seiko Epson ET-2820 Series       | 1        | 5.88%   |
| Samsung SCX-3400 Series          | 1        | 5.88%   |
| Samsung ML-1670 Series           | 1        | 5.88%   |
| Ricoh SP C260SFNw                | 1        | 5.88%   |
| Konica Minolta 185               | 1        | 5.88%   |
| HP OfficeJet Pro 8730            | 1        | 5.88%   |
| HP LaserJet P1006                | 1        | 5.88%   |
| HP LaserJet 3050                 | 1        | 5.88%   |
| HP DeskJet F4200 series          | 1        | 5.88%   |
| HP Deskjet 2540 series           | 1        | 5.88%   |
| HP DeskJet 2130 series           | 1        | 5.88%   |
| HP Deskjet 1050 J410             | 1        | 5.88%   |
| Canon LaserShot LBP-1120 Printer | 1        | 5.88%   |
| Canon iP4200                     | 1        | 5.88%   |
| Brother HL-L2300D series         | 1        | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 1        | 33.33%  |
| Hewlett-Packard | 1        | 33.33%  |
| Canon           | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 33.33%  |
| HP ScanJet 3800c                              | 1        | 33.33%  |
| Canon CanoScan LiDE 110                       | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 15       | 35.71%  |
| Sunplus Innovation Technology | 4        | 9.52%   |
| Microsoft                     | 3        | 7.14%   |
| Z-Star Microelectronics       | 2        | 4.76%   |
| Huawei Technologies           | 2        | 4.76%   |
| Creative Technology           | 2        | 4.76%   |
| Xiongmai                      | 1        | 2.38%   |
| WCM_USB                       | 1        | 2.38%   |
| Service & Quality Technology  | 1        | 2.38%   |
| Samsung Electronics           | 1        | 2.38%   |
| Pixart Imaging                | 1        | 2.38%   |
| OmniVision Technologies       | 1        | 2.38%   |
| Nintendo                      | 1        | 2.38%   |
| Microdia                      | 1        | 2.38%   |
| MacroSilicon                  | 1        | 2.38%   |
| KYE Systems (Mouse Systems)   | 1        | 2.38%   |
| Generalplus Technology        | 1        | 2.38%   |
| Chicony Electronics           | 1        | 2.38%   |
| ARC International             | 1        | 2.38%   |
| Alcor Micro                   | 1        | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Logitech Webcam C270                               | 5        | 11.9%   |
| Z-Star Venus USB2.0 Camera                         | 2        | 4.76%   |
| Sunplus WEMISS CM-A1                               | 2        | 4.76%   |
| Microsoft LifeCam HD-3000                          | 2        | 4.76%   |
| Logitech Webcam C310                               | 2        | 4.76%   |
| Huawei UVC Camera                                  | 2        | 4.76%   |
| Xiongmai web camera                                | 1        | 2.38%   |
| WCM_USB WEB CAM                                    | 1        | 2.38%   |
| Sunplus USB camera                                 | 1        | 2.38%   |
| Sunplus Full HD webcam                             | 1        | 2.38%   |
| Service & Quality USB PC Camera                    | 1        | 2.38%   |
| Samsung Galaxy A5 (MTP)                            | 1        | 2.38%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro               | 1        | 2.38%   |
| OmniVision Integrated Webcam for Dell XPS 2010     | 1        | 2.38%   |
| Nintendo USB Camera                                | 1        | 2.38%   |
| Microsoft MicrosoftÂ LifeCam VX-5500              | 1        | 2.38%   |
| Microdia Webcam Vitade AF                          | 1        | 2.38%   |
| MacroSilicon USB Video                             | 1        | 2.38%   |
| Logitech Webcam Pro 9000                           | 1        | 2.38%   |
| Logitech Webcam C930e                              | 1        | 2.38%   |
| Logitech Webcam C925e                              | 1        | 2.38%   |
| Logitech Webcam C210                               | 1        | 2.38%   |
| Logitech Webcam B500                               | 1        | 2.38%   |
| Logitech QuickCam Communicate Deluxe/S7500         | 1        | 2.38%   |
| Logitech Logi Webcam C920e                         | 1        | 2.38%   |
| Logitech HD Pro Webcam C920                        | 1        | 2.38%   |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 1        | 2.38%   |
| Generalplus 808 Camera #9 (web-cam mode)           | 1        | 2.38%   |
| Creative VF0610 Live! Cam Socialize HD             | 1        | 2.38%   |
| Creative Live! Cam Sync HD [VF0770]                | 1        | 2.38%   |
| Chicony HP High Definition 1MP Webcam              | 1        | 2.38%   |
| ARC International Camera                           | 1        | 2.38%   |
| Alcor Micro USB 5.0M AF Camera                     | 1        | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| VASCO Data Security International | 1        | 33.33%  |
| OmniKey                           | 1        | 33.33%  |
| Jing-Mold Enterprise              | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| VASCO Data Security International DIGIPASS 870                    | 1        | 33.33%  |
| OmniKey CardMan 1021                                              | 1        | 33.33%  |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 188      | 71.48%  |
| 1     | 66       | 25.1%   |
| 2     | 5        | 1.9%    |
| 4     | 2        | 0.76%   |
| 3     | 2        | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 42       | 48.84%  |
| Net/wireless             | 23       | 26.74%  |
| Communication controller | 6        | 6.98%   |
| Unassigned class         | 3        | 3.49%   |
| Network                  | 2        | 2.33%   |
| Net/ethernet             | 2        | 2.33%   |
| Multimedia controller    | 2        | 2.33%   |
| Storage/raid             | 1        | 1.16%   |
| Storage/ide              | 1        | 1.16%   |
| Modem                    | 1        | 1.16%   |
| Fingerprint reader       | 1        | 1.16%   |
| Chipcard                 | 1        | 1.16%   |
| Camera                   | 1        | 1.16%   |

