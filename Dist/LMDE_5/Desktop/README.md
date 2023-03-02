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

Total: 128

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte  | Z590 GAMING X               | [d39a85e759](https://linux-hardware.org/?probe=d39a85e759) | Feb 24, 2023 |
| Medion    | MS-7800                     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| Dell      | 0NK70N A03                  | [3da6e11665](https://linux-hardware.org/?probe=3da6e11665) | Feb 18, 2023 |
| ASUSTek   | P7P55D                      | [bcae3260be](https://linux-hardware.org/?probe=bcae3260be) | Feb 17, 2023 |
| Foxconn   | 2ABF                        | [2c98a8340f](https://linux-hardware.org/?probe=2c98a8340f) | Feb 17, 2023 |
| Dell      | 0MF24N A03                  | [e48d83d96d](https://linux-hardware.org/?probe=e48d83d96d) | Feb 15, 2023 |
| Gigabyte  | B450M S2H                   | [20bcead0e8](https://linux-hardware.org/?probe=20bcead0e8) | Feb 11, 2023 |
| HP        | 843C                        | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| Gigabyte  | B450 AORUS M                | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek   | M5A78L-M PLUS/USB3          | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek   | M5A78L-M PLUS/USB3          | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| ASUSTek   | P8H61-M LX R2.0             | [1985f76677](https://linux-hardware.org/?probe=1985f76677) | Feb 05, 2023 |
| Gigabyte  | B560 DS3H AC-Y1             | [6c094e2027](https://linux-hardware.org/?probe=6c094e2027) | Jan 31, 2023 |
| ASUSTek   | P7P55D                      | [981ae95b2a](https://linux-hardware.org/?probe=981ae95b2a) | Jan 31, 2023 |
| Gigabyte  | X570 AORUS ULTRA            | [40152faf5b](https://linux-hardware.org/?probe=40152faf5b) | Jan 28, 2023 |
| Intel     | H61M-DS2V                   | [0591a32a07](https://linux-hardware.org/?probe=0591a32a07) | Jan 25, 2023 |
| ASRock    | Z87 Pro3                    | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| Dell      | 0C27VV A01                  | [e43d24d2b6](https://linux-hardware.org/?probe=e43d24d2b6) | Jan 23, 2023 |
| ASUSTek   | M5A78L-M PLUS/USB3          | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [c5dd2e8482](https://linux-hardware.org/?probe=c5dd2e8482) | Jan 19, 2023 |
| Gigabyte  | H310M S2H                   | [9aec47cbf0](https://linux-hardware.org/?probe=9aec47cbf0) | Jan 12, 2023 |
| Gigabyte  | H310M S2H                   | [b3cccc4043](https://linux-hardware.org/?probe=b3cccc4043) | Jan 12, 2023 |
| ADVANSUS  | 945G                        | [3a9bdd2358](https://linux-hardware.org/?probe=3a9bdd2358) | Jan 12, 2023 |
| Gigabyte  | X470 AORUS ULTRA GAMING-... | [563d7aaba5](https://linux-hardware.org/?probe=563d7aaba5) | Jan 12, 2023 |
| ADVANSUS  | 945G                        | [db0f184e3f](https://linux-hardware.org/?probe=db0f184e3f) | Jan 11, 2023 |
| Intel     | B75                         | [ec08587a4a](https://linux-hardware.org/?probe=ec08587a4a) | Jan 09, 2023 |
| MSI       | FM2-A55M-E33                | [1ce8a2718b](https://linux-hardware.org/?probe=1ce8a2718b) | Jan 07, 2023 |
| Acer      | Aspire XC-780               | [66823871a5](https://linux-hardware.org/?probe=66823871a5) | Jan 07, 2023 |
| ASUSTek   | ROG STRIX Z490-H GAMING     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Fujitsu   | D3003-S2 S26361-D3003-S2    | [cb55beafca](https://linux-hardware.org/?probe=cb55beafca) | Dec 30, 2022 |
| Fujitsu   | D3003-S2 S26361-D3003-S2    | [938db016a2](https://linux-hardware.org/?probe=938db016a2) | Dec 30, 2022 |
| ASUSTek   | Z170M-PLUS                  | [6b61c9a811](https://linux-hardware.org/?probe=6b61c9a811) | Dec 28, 2022 |
| Gigabyte  | GA-970A-D3                  | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| ASUSTek   | PRIME B350M-A               | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| Dell      | 0C27VV A01                  | [91c790d54e](https://linux-hardware.org/?probe=91c790d54e) | Dec 18, 2022 |
| MSI       | PRO B660M-A DDR4            | [770334f093](https://linux-hardware.org/?probe=770334f093) | Dec 16, 2022 |
| Dell      | 0T1D10 A01                  | [6988ab07fe](https://linux-hardware.org/?probe=6988ab07fe) | Dec 12, 2022 |
| Dell      | 0T1D10 A01                  | [6ec6d4563d](https://linux-hardware.org/?probe=6ec6d4563d) | Dec 12, 2022 |
| ASUSTek   | LEUCITE3                    | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| ASUSTek   | PRIME B450-PLUS             | [e810c5c2eb](https://linux-hardware.org/?probe=e810c5c2eb) | Dec 08, 2022 |
| ASUSTek   | P7P55D                      | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| SiYW      | V200 Series                 | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| HP        | 8299                        | [8f6b89bf07](https://linux-hardware.org/?probe=8f6b89bf07) | Nov 25, 2022 |
| Gigabyte  | GA-78LMT-USB3               | [1ad4dcb28a](https://linux-hardware.org/?probe=1ad4dcb28a) | Nov 22, 2022 |
| Gigabyte  | B450 I AORUS PRO WIFI-CF    | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| MSI       | MAG X570S TOMAHAWK MAX W... | [d93b2b9778](https://linux-hardware.org/?probe=d93b2b9778) | Nov 21, 2022 |
| MSI       | A320M-A PRO MAX             | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Dell      | 0C27VV A01                  | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| ASUSTek   | M5A78L-M PLUS/USB3          | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| Dell      | 0C27VV A01                  | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell      | 0C27VV A01                  | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| Dell      | 0N826N A03                  | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| MSI       | A320M-A PRO MAX             | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| HP        | 8299                        | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| HP        | 8299                        | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Samsung   | DT1234567890 SEC_SW_REVI... | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung   | DT1234567890 SEC_SW_REVI... | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell      | 0D735T A00                  | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI       | B550-A PRO                  | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| AZW       | MINI S                      | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek   | Maximus VI HERO             | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| MSI       | B550-A PRO                  | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock    | A320M-HDV R4.0              | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu   | D3062-A1 S26361-D3062-A1    | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| Acer      | Aspire XC-1660G V:1.1       | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer      | Aspire XC-1660G V:1.1       | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell      | 082WXT A01                  | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell      | 082WXT A01                  | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Gateway   | DX4870                      | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| Digiboard | NM70-TI                     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Dell      | 0XC837                      | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| MSI       | B360M MORTAR                | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek   | PRIME H610M-E D4            | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell      | 0FJ030                      | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI       | B450I GAMING PLUS AC        | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Pegatron  | 2A9Eh                       | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek   | P8H77-V                     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines | EL1352G                     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| ASUSTek   | P5K-E                       | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Dell      | 042P49 A00                  | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek   | P5QPL-AM                    | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Gigabyte  | B450M DS3H-CF               | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte  | B450M DS3H-CF               | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI       | Z170A GAMING PRO            | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| MSI       | B85I                        | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Gigabyte  | H97-Gaming 3                | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte  | B85M-DS3H-A                 | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| ASRock    | H61M-DGS                    | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Gigabyte  | B450 AORUS M                | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| HP        | 8433 11                     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP        | 8433 11                     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| ASUSTek   | BM6820_BM6620_BP6320-8      | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Gigabyte  | B450 AORUS M                | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| ASUSTek   | P8H77-M PRO                 | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Dell      | 0XR1GT A00                  | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| Lenovo    | 3731 NOK                    | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo    | 3731 NOK                    | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| Dell      | 0XR1GT A00                  | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| MSI       | MPG Z390 GAMING PRO CARB... | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo    | MAHOBAY                     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| Acer      | Seawolf                     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Intel     | DQ77MK AAG39642-400         | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| MSI       | X470 GAMING PLUS MAX        | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| MSI       | 970A-G43 PLUS               | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Gigabyte  | Z68A-D3H-B3                 | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP        | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP        | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| HP        | 339A                        | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Gigabyte  | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASUSTek   | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| ASRock    | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock    | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell      | 0CU568 A00                  | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell      | 0CU568 A00                  | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| ASUSTek   | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek   | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI       | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Lenovo    | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo    | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Acer      | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek   | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| MSI       | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI       | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| ASUSTek   | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| ASUSTek   | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| HP        | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.0-21-amd64          | 15       | 15.31%  |
| 5.10.0-12-amd64          | 15       | 15.31%  |
| 5.10.0-20-amd64          | 12       | 12.24%  |
| 5.10.0-17-amd64          | 11       | 11.22%  |
| 5.10.0-14-amd64          | 10       | 10.2%   |
| 5.10.0-13-amd64          | 10       | 10.2%   |
| 5.10.0-18-amd64          | 9        | 9.18%   |
| 5.10.0-19-amd64          | 8        | 8.16%   |
| 5.10.0-15-amd64          | 3        | 3.06%   |
| 5.10.0-16-amd64          | 2        | 2.04%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1        | 1.02%   |
| 5.19.0-0.deb11.2-amd64   | 1        | 1.02%   |
| 5.10.0-13-686            | 1        | 1.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 88       | 97.78%  |
| 6.0.2   | 1        | 1.11%   |
| 5.19.0  | 1        | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 88       | 97.78%  |
| 6.0     | 1        | 1.11%   |
| 5.19    | 1        | 1.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 89       | 98.89%  |
| i686   | 1        | 1.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 81       | 90%     |
| Cinnamon   | 6        | 6.67%   |
| XFCE       | 1        | 1.11%   |
| MATE       | 1        | 1.11%   |
| KDE5       | 1        | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 90       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 60       | 66.67%  |
| LightDM | 28       | 31.11%  |
| SDDM    | 1        | 1.11%   |
| GDM     | 1        | 1.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 30       | 33.33%  |
| de_DE | 13       | 14.44%  |
| ru_RU | 8        | 8.89%   |
| pt_BR | 8        | 8.89%   |
| it_IT | 5        | 5.56%   |
| fr_FR | 4        | 4.44%   |
| en_CA | 3        | 3.33%   |
| sv_SE | 2        | 2.22%   |
| pl_PL | 2        | 2.22%   |
| es_ES | 2        | 2.22%   |
| en_GB | 2        | 2.22%   |
| sk_SK | 1        | 1.11%   |
| ru_UA | 1        | 1.11%   |
| it_CH | 1        | 1.11%   |
| fr_CA | 1        | 1.11%   |
| fr_BE | 1        | 1.11%   |
| es_NI | 1        | 1.11%   |
| en_ZA | 1        | 1.11%   |
| en_AU | 1        | 1.11%   |
| de_AT | 1        | 1.11%   |
| cs_CZ | 1        | 1.11%   |
| ar_EG | 1        | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 51       | 56.67%  |
| EFI  | 39       | 43.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 84       | 93.33%  |
| Tmpfs   | 3        | 3.33%   |
| Btrfs   | 2        | 2.22%   |
| Overlay | 1        | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 61       | 67.78%  |
| GPT     | 18       | 20%     |
| MBR     | 11       | 12.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 90%     |
| Yes       | 9        | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 85.56%  |
| Yes       | 13       | 14.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 23.33%  |
| Gigabyte Technology | 14       | 15.56%  |
| Dell                | 12       | 13.33%  |
| MSI                 | 11       | 12.22%  |
| Hewlett-Packard     | 6        | 6.67%   |
| ASRock              | 4        | 4.44%   |
| Acer                | 4        | 4.44%   |
| Lenovo              | 3        | 3.33%   |
| Intel               | 3        | 3.33%   |
| Fujitsu             | 2        | 2.22%   |
| SiYW                | 1        | 1.11%   |
| Samsung Electronics | 1        | 1.11%   |
| Pegatron            | 1        | 1.11%   |
| Medion              | 1        | 1.11%   |
| Gateway             | 1        | 1.11%   |
| Foxconn             | 1        | 1.11%   |
| eMachines           | 1        | 1.11%   |
| Digiboard           | 1        | 1.11%   |
| AZW                 | 1        | 1.11%   |
| ADVANSUS            | 1        | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Gigabyte B450 AORUS M               | 2        | 2.22%   |
| ASUS PRIME B350M-A                  | 2        | 2.22%   |
| SiYW V200 Series                    | 1        | 1.11%   |
| Samsung DeskTop System              | 1        | 1.11%   |
| Pegatron Pro 3015 Microtower PC     | 1        | 1.11%   |
| MSI MS-7D54                         | 1        | 1.11%   |
| MSI MS-7C52                         | 1        | 1.11%   |
| MSI MS-7B79                         | 1        | 1.11%   |
| MSI MS-7B23                         | 1        | 1.11%   |
| MSI MS-7B17                         | 1        | 1.11%   |
| MSI MS-7A40                         | 1        | 1.11%   |
| MSI MS-7984                         | 1        | 1.11%   |
| MSI MS-7977                         | 1        | 1.11%   |
| MSI MS-7974                         | 1        | 1.11%   |
| MSI MS-7851                         | 1        | 1.11%   |
| MSI MS-7721                         | 1        | 1.11%   |
| Medion MS-7800                      | 1        | 1.11%   |
| Lenovo V55t-15ARE 11KJ0036TX        | 1        | 1.11%   |
| Lenovo ThinkCentre M92p 3238E9U     | 1        | 1.11%   |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1        | 1.11%   |
| Intel H61M-DS2V                     | 1        | 1.11%   |
| Intel DQ77MK AAG39642-400           | 1        | 1.11%   |
| Intel B75                           | 1        | 1.11%   |
| HP Z820 Workstation                 | 1        | 1.11%   |
| HP Z600 Workstation                 | 1        | 1.11%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 1.11%   |
| HP EliteDesk 800 G3 SFF             | 1        | 1.11%   |
| HP Compaq Pro 6300 SFF              | 1        | 1.11%   |
| HP 290 G2 MT Business PC            | 1        | 1.11%   |
| Gigabyte Z68A-D3H-B3                | 1        | 1.11%   |
| Gigabyte Z590 GAMING X              | 1        | 1.11%   |
| Gigabyte X570 AORUS ULTRA           | 1        | 1.11%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 1        | 1.11%   |
| Gigabyte H110M-S2H                  | 1        | 1.11%   |
| Gigabyte GA-970A-D3                 | 1        | 1.11%   |
| Gigabyte GA-78LMT-USB3              | 1        | 1.11%   |
| Gigabyte B85M-DS3H-A                | 1        | 1.11%   |
| Gigabyte B560 DS3H AC-Y1            | 1        | 1.11%   |
| Gigabyte B450M S2H                  | 1        | 1.11%   |
| Gigabyte B450M DS3H                 | 1        | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 6        | 6.67%   |
| Dell Precision       | 4        | 4.44%   |
| Gigabyte B450        | 3        | 3.33%   |
| Acer Aspire          | 3        | 3.33%   |
| Lenovo ThinkCentre   | 2        | 2.22%   |
| Gigabyte B450M       | 2        | 2.22%   |
| Dell Vostro          | 2        | 2.22%   |
| Dell OptiPlex        | 2        | 2.22%   |
| Dell Inspiron        | 2        | 2.22%   |
| ASUS ROG             | 2        | 2.22%   |
| SiYW V200            | 1        | 1.11%   |
| Samsung DeskTop      | 1        | 1.11%   |
| Pegatron Pro         | 1        | 1.11%   |
| MSI MS-7D54          | 1        | 1.11%   |
| MSI MS-7C52          | 1        | 1.11%   |
| MSI MS-7B79          | 1        | 1.11%   |
| MSI MS-7B23          | 1        | 1.11%   |
| MSI MS-7B17          | 1        | 1.11%   |
| MSI MS-7A40          | 1        | 1.11%   |
| MSI MS-7984          | 1        | 1.11%   |
| MSI MS-7977          | 1        | 1.11%   |
| MSI MS-7974          | 1        | 1.11%   |
| MSI MS-7851          | 1        | 1.11%   |
| MSI MS-7721          | 1        | 1.11%   |
| Medion MS-7800       | 1        | 1.11%   |
| Lenovo V55t-15ARE    | 1        | 1.11%   |
| Intel H61M-DS2V      | 1        | 1.11%   |
| Intel DQ77MK         | 1        | 1.11%   |
| Intel B75            | 1        | 1.11%   |
| HP Z820              | 1        | 1.11%   |
| HP Z600              | 1        | 1.11%   |
| HP Pavilion          | 1        | 1.11%   |
| HP EliteDesk         | 1        | 1.11%   |
| HP Compaq            | 1        | 1.11%   |
| HP 290               | 1        | 1.11%   |
| Gigabyte Z68A-D3H-B3 | 1        | 1.11%   |
| Gigabyte Z590        | 1        | 1.11%   |
| Gigabyte X570        | 1        | 1.11%   |
| Gigabyte X470        | 1        | 1.11%   |
| Gigabyte H110M-S2H   | 1        | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 18       | 20%     |
| 2012 | 14       | 15.56%  |
| 2009 | 7        | 7.78%   |
| 2021 | 6        | 6.67%   |
| 2015 | 6        | 6.67%   |
| 2017 | 5        | 5.56%   |
| 2013 | 5        | 5.56%   |
| 2011 | 5        | 5.56%   |
| 2019 | 4        | 4.44%   |
| 2010 | 4        | 4.44%   |
| 2022 | 3        | 3.33%   |
| 2016 | 3        | 3.33%   |
| 2006 | 3        | 3.33%   |
| 2020 | 2        | 2.22%   |
| 2014 | 2        | 2.22%   |
| 2007 | 2        | 2.22%   |
| 2008 | 1        | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 90       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 90       | 98.9%   |
| Enabled  | 1        | 1.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 90       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 21       | 23.08%  |
| 8.01-16.0       | 20       | 21.98%  |
| 4.01-8.0        | 17       | 18.68%  |
| 32.01-64.0      | 15       | 16.48%  |
| 3.01-4.0        | 9        | 9.89%   |
| 24.01-32.0      | 3        | 3.3%    |
| 1.01-2.0        | 3        | 3.3%    |
| More than 256.0 | 1        | 1.1%    |
| 64.01-256.0     | 1        | 1.1%    |
| 0.51-1.0        | 1        | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 35       | 36.46%  |
| 2.01-3.0   | 29       | 30.21%  |
| 4.01-8.0   | 14       | 14.58%  |
| 3.01-4.0   | 10       | 10.42%  |
| 0.51-1.0   | 5        | 5.21%   |
| 8.01-16.0  | 2        | 2.08%   |
| 24.01-32.0 | 1        | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 40       | 43.96%  |
| 2      | 22       | 24.18%  |
| 3      | 15       | 16.48%  |
| 4      | 7        | 7.69%   |
| 5      | 5        | 5.49%   |
| 6      | 2        | 2.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 51.65%  |
| Yes       | 44       | 48.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 89       | 98.89%  |
| No        | 1        | 1.11%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 56.04%  |
| Yes       | 40       | 43.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 75.56%  |
| Yes       | 22       | 24.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 21       | 23.33%  |
| Germany      | 13       | 14.44%  |
| Brazil       | 9        | 10%     |
| Russia       | 8        | 8.89%   |
| Italy        | 7        | 7.78%   |
| France       | 5        | 5.56%   |
| Canada       | 4        | 4.44%   |
| Sweden       | 3        | 3.33%   |
| UK           | 2        | 2.22%   |
| Spain        | 2        | 2.22%   |
| Poland       | 2        | 2.22%   |
| Australia    | 2        | 2.22%   |
| Venezuela    | 1        | 1.11%   |
| Ukraine      | 1        | 1.11%   |
| Turkey       | 1        | 1.11%   |
| South Africa | 1        | 1.11%   |
| Slovakia     | 1        | 1.11%   |
| Nicaragua    | 1        | 1.11%   |
| Netherlands  | 1        | 1.11%   |
| Mexico       | 1        | 1.11%   |
| Latvia       | 1        | 1.11%   |
| Kazakhstan   | 1        | 1.11%   |
| Belgium      | 1        | 1.11%   |
| Austria      | 1        | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Melbourne                | 2        | 2.17%   |
| Frankfurt am Main        | 2        | 2.17%   |
| Berlin                   | 2        | 2.17%   |
| Washington               | 1        | 1.09%   |
| Volta Redonda            | 1        | 1.09%   |
| Vitória da Conquista    | 1        | 1.09%   |
| Vincennes                | 1        | 1.09%   |
| Vicente Guerrero         | 1        | 1.09%   |
| Varese                   | 1        | 1.09%   |
| Ulyanovsk                | 1        | 1.09%   |
| Trieste                  | 1        | 1.09%   |
| Tolyatti                 | 1        | 1.09%   |
| Toledo                   | 1        | 1.09%   |
| Toccoa                   | 1        | 1.09%   |
| Tacoma                   | 1        | 1.09%   |
| Stockelsdorf             | 1        | 1.09%   |
| Stockbridge              | 1        | 1.09%   |
| Spruce Grove             | 1        | 1.09%   |
| Sollentuna               | 1        | 1.09%   |
| Solingen                 | 1        | 1.09%   |
| Schruns                  | 1        | 1.09%   |
| Sao Paulo                | 1        | 1.09%   |
| Sao Lourenço            | 1        | 1.09%   |
| Sant Feliu de Llobregat  | 1        | 1.09%   |
| San Antonio de Los Altos | 1        | 1.09%   |
| San Antonio              | 1        | 1.09%   |
| Rome                     | 1        | 1.09%   |
| Riga                     | 1        | 1.09%   |
| Reynoldsburg             | 1        | 1.09%   |
| Rennes                   | 1        | 1.09%   |
| Raschau                  | 1        | 1.09%   |
| Queensbury               | 1        | 1.09%   |
| Prestatyn                | 1        | 1.09%   |
| Porto Uniao              | 1        | 1.09%   |
| Porto Alegre             | 1        | 1.09%   |
| Piaseczno                | 1        | 1.09%   |
| Petrozavodsk             | 1        | 1.09%   |
| Pensacola                | 1        | 1.09%   |
| Oxford                   | 1        | 1.09%   |
| Orekhovo-Zuyevo          | 1        | 1.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 48     | 19.35%  |
| Seagate             | 29       | 40     | 18.71%  |
| Samsung Electronics | 22       | 45     | 14.19%  |
| Kingston            | 12       | 17     | 7.74%   |
| Crucial             | 9        | 9      | 5.81%   |
| Toshiba             | 8        | 9      | 5.16%   |
| SanDisk             | 6        | 6      | 3.87%   |
| Hitachi             | 5        | 6      | 3.23%   |
| SK hynix            | 3        | 4      | 1.94%   |
| China               | 2        | 2      | 1.29%   |
| Apple               | 2        | 2      | 1.29%   |
| A-DATA Technology   | 2        | 2      | 1.29%   |
| XrayDisk            | 1        | 2      | 0.65%   |
| WALRAM              | 1        | 1      | 0.65%   |
| Unknown             | 1        | 1      | 0.65%   |
| Transcend           | 1        | 2      | 0.65%   |
| TGT                 | 1        | 1      | 0.65%   |
| TakeMS              | 1        | 1      | 0.65%   |
| SPCC                | 1        | 1      | 0.65%   |
| Silicon Motion      | 1        | 1      | 0.65%   |
| PNY                 | 1        | 1      | 0.65%   |
| Phison Electronics  | 1        | 1      | 0.65%   |
| Phison              | 1        | 1      | 0.65%   |
| OCZ-VERTEX          | 1        | 1      | 0.65%   |
| Netac               | 1        | 1      | 0.65%   |
| Micron Technology   | 1        | 1      | 0.65%   |
| Intenso             | 1        | 1      | 0.65%   |
| Intel               | 1        | 1      | 0.65%   |
| Hewlett-Packard     | 1        | 1      | 0.65%   |
| GOODRAM             | 1        | 1      | 0.65%   |
| Gigabyte Technology | 1        | 2      | 0.65%   |
| BR                  | 1        | 1      | 0.65%   |
| ASMedia             | 1        | 1      | 0.65%   |
| Apacer              | 1        | 1      | 0.65%   |
| ADATA Technology    | 1        | 1      | 0.65%   |
| 2.5''               | 1        | 1      | 0.65%   |
| Unknown             | 1        | 2      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 6        | 3.3%    |
| Kingston SA400S37240G 240GB SSD                     | 4        | 2.2%    |
| Samsung SSD 850 EVO 500GB                           | 3        | 1.65%   |
| Kingston SA400S37120G 120GB SSD                     | 3        | 1.65%   |
| Crucial CT480BX500SSD1 480GB                        | 3        | 1.65%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 1.1%    |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 1.1%    |
| Seagate ST3320418AS 320GB                           | 2        | 1.1%    |
| Seagate ST3250318AS 250GB                           | 2        | 1.1%    |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 1.1%    |
| Seagate ST1000LM048-2E7172 1TB                      | 2        | 1.1%    |
| Seagate ST1000DM003-1ER162 1TB                      | 2        | 1.1%    |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 1.1%    |
| Samsung SSD 980 PRO 1TB                             | 2        | 1.1%    |
| Samsung SSD 970 EVO 500GB                           | 2        | 1.1%    |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 2        | 1.1%    |
| Samsung NVMe SSD Drive 500GB                        | 2        | 1.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2        | 1.1%    |
| XrayDisk 480GB                                      | 1        | 0.55%   |
| XrayDisk 1TB                                        | 1        | 0.55%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1        | 0.55%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1        | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1        | 0.55%   |
| WDC WD60EZAZ-00ZGHB0 6TB                            | 1        | 0.55%   |
| WDC WD5000LPSX-08A6W 500GB                          | 1        | 0.55%   |
| WDC WD5000BEVT-22ZAT0 500GB                         | 1        | 0.55%   |
| WDC WD5000AZLX-08K2TA0 500GB                        | 1        | 0.55%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1        | 0.55%   |
| WDC WD5000AAKX-22ERMA0 500GB                        | 1        | 0.55%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1        | 0.55%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1        | 0.55%   |
| WDC WD5000AAJS-00TKA0 500GB                         | 1        | 0.55%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 1        | 0.55%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 1        | 0.55%   |
| WDC WD3200AAJS-22B4A0 320GB                         | 1        | 0.55%   |
| WDC WD30EZRZ-00Z5HB0 3TB                            | 1        | 0.55%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 1        | 0.55%   |
| WDC WD3003FZEX-00Z4SA0 3TB                          | 1        | 0.55%   |
| WDC WD20SPZX-00UA7T0 2TB                            | 1        | 0.55%   |
| WDC WD20EARS-00S8B1 2TB                             | 1        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 39     | 37.66%  |
| WDC                 | 28       | 45     | 36.36%  |
| Toshiba             | 7        | 8      | 9.09%   |
| Hitachi             | 5        | 6      | 6.49%   |
| Samsung Electronics | 4        | 6      | 5.19%   |
| Unknown             | 1        | 1      | 1.3%    |
| Intenso             | 1        | 1      | 1.3%    |
| ASMedia             | 1        | 1      | 1.3%    |
| Apple               | 1        | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 22     | 22.95%  |
| Kingston            | 10       | 15     | 16.39%  |
| Crucial             | 8        | 8      | 13.11%  |
| SanDisk             | 5        | 5      | 8.2%    |
| WDC                 | 3        | 3      | 4.92%   |
| SK hynix            | 2        | 2      | 3.28%   |
| China               | 2        | 2      | 3.28%   |
| A-DATA Technology   | 2        | 2      | 3.28%   |
| Transcend           | 1        | 2      | 1.64%   |
| Toshiba             | 1        | 1      | 1.64%   |
| TakeMS              | 1        | 1      | 1.64%   |
| SPCC                | 1        | 1      | 1.64%   |
| PNY                 | 1        | 1      | 1.64%   |
| OCZ-VERTEX          | 1        | 1      | 1.64%   |
| Netac               | 1        | 1      | 1.64%   |
| Micron Technology   | 1        | 1      | 1.64%   |
| Hewlett-Packard     | 1        | 1      | 1.64%   |
| GOODRAM             | 1        | 1      | 1.64%   |
| Gigabyte Technology | 1        | 2      | 1.64%   |
| Apple               | 1        | 1      | 1.64%   |
| Apacer              | 1        | 1      | 1.64%   |
| 2.5''               | 1        | 1      | 1.64%   |
| Unknown             | 1        | 2      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 63       | 108    | 45.65%  |
| SSD     | 52       | 77     | 37.68%  |
| NVMe    | 18       | 28     | 13.04%  |
| Unknown | 5        | 6      | 3.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 86       | 181    | 77.48%  |
| NVMe | 18       | 28     | 16.22%  |
| SAS  | 7        | 10     | 6.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 67       | 114    | 58.26%  |
| 0.51-1.0   | 29       | 45     | 25.22%  |
| 1.01-2.0   | 8        | 9      | 6.96%   |
| 3.01-4.0   | 5        | 8      | 4.35%   |
| 2.01-3.0   | 3        | 6      | 2.61%   |
| 4.01-10.0  | 3        | 3      | 2.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 22       | 24.18%  |
| 251-500        | 20       | 21.98%  |
| 1001-2000      | 15       | 16.48%  |
| 501-1000       | 14       | 15.38%  |
| More than 3000 | 7        | 7.69%   |
| 2001-3000      | 5        | 5.49%   |
| 1-20           | 4        | 4.4%    |
| 51-100         | 3        | 3.3%    |
| 21-50          | 1        | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 29       | 31.52%  |
| 21-50          | 14       | 15.22%  |
| 51-100         | 11       | 11.96%  |
| 251-500        | 10       | 10.87%  |
| 101-250        | 9        | 9.78%   |
| 501-1000       | 9        | 9.78%   |
| 1001-2000      | 6        | 6.52%   |
| More than 3000 | 2        | 2.17%   |
| 2001-3000      | 2        | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1        | 1      | 25%     |
| Seagate ST3250318AS 250GB       | 1        | 1      | 25%     |
| Seagate ST2000DX001-1CM164 2TB  | 1        | 1      | 25%     |
| Seagate ST1000LM048-2E7172 1TB  | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 4      | 100%    |

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
| Detected | 65       | 152    | 67.01%  |
| Works    | 28       | 63     | 28.87%  |
| Malfunc  | 4        | 4      | 4.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 63       | 52.5%   |
| AMD                         | 26       | 21.67%  |
| Samsung Electronics         | 9        | 7.5%    |
| JMicron Technology          | 3        | 2.5%    |
| Broadcom / LSI              | 3        | 2.5%    |
| ASMedia Technology          | 3        | 2.5%    |
| Phison Electronics          | 2        | 1.67%   |
| Nvidia                      | 2        | 1.67%   |
| Kingston Technology Company | 2        | 1.67%   |
| SK hynix                    | 1        | 0.83%   |
| Silicon Motion              | 1        | 0.83%   |
| SanDisk                     | 1        | 0.83%   |
| Micron/Crucial Technology   | 1        | 0.83%   |
| Marvell Technology Group    | 1        | 0.83%   |
| LSI Logic / Symbios Logic   | 1        | 0.83%   |
| ADATA Technology            | 1        | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 10.76%  |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 5.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 4.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 4.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 4.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 3.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 3.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 3.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.53%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.9%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 1.9%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.9%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.9%    |
| AMD FCH SATA Controller D                                                               | 3        | 1.9%    |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.27%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2        | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 1.27%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.27%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.27%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.27%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.27%   |
| SK hynix BC511                                                                          | 1        | 0.63%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.63%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.63%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.63%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.63%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.63%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.63%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 77       | 60.63%  |
| IDE  | 22       | 17.32%  |
| NVMe | 18       | 14.17%  |
| RAID | 6        | 4.72%   |
| SAS  | 3        | 2.36%   |
| SCSI | 1        | 0.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 62       | 68.89%  |
| AMD    | 28       | 31.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 5.49%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 3.3%    |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 2.2%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 2.2%    |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 2.2%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 2.2%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 2.2%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 2.2%    |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 2.2%    |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 2        | 2.2%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 2.2%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 2.2%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 2.2%    |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 1.1%    |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 1.1%    |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 1.1%    |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 1.1%    |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 1.1%    |
| Intel Xeon CPU 3.40GHz                      | 1        | 1.1%    |
| Intel Pentium Gold G7400                    | 1        | 1.1%    |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 1.1%    |
| Intel Pentium D CPU 3.40GHz                 | 1        | 1.1%    |
| Intel Pentium D CPU 2.80GHz                 | 1        | 1.1%    |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.1%    |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.1%    |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1        | 1.1%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.1%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.1%    |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 1.1%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.1%    |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 1.1%    |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 1.1%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.1%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.1%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.1%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.1%    |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1        | 1.1%    |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 1.1%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.1%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.1%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 16.48%  |
| Intel Core i7           | 14       | 15.38%  |
| Intel Xeon              | 8        | 8.79%   |
| AMD Ryzen 5             | 7        | 7.69%   |
| AMD Ryzen 7             | 6        | 6.59%   |
| Other                   | 4        | 4.4%    |
| Intel Pentium           | 4        | 4.4%    |
| Intel Core i3           | 4        | 4.4%    |
| AMD Ryzen 3             | 4        | 4.4%    |
| Intel Core 2 Quad       | 3        | 3.3%    |
| Intel Pentium Gold      | 2        | 2.2%    |
| Intel Pentium Dual-Core | 2        | 2.2%    |
| Intel Pentium D         | 2        | 2.2%    |
| Intel Core 2 Duo        | 2        | 2.2%    |
| Intel Celeron           | 2        | 2.2%    |
| AMD FX                  | 2        | 2.2%    |
| AMD Athlon II X2        | 2        | 2.2%    |
| Intel Core 2            | 1        | 1.1%    |
| AMD Ryzen 9             | 1        | 1.1%    |
| AMD Phenom II X6        | 1        | 1.1%    |
| AMD Phenom II X4        | 1        | 1.1%    |
| AMD G                   | 1        | 1.1%    |
| AMD Athlon              | 1        | 1.1%    |
| AMD A8                  | 1        | 1.1%    |
| AMD A4                  | 1        | 1.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 40       | 43.96%  |
| 2      | 25       | 27.47%  |
| 8      | 12       | 13.19%  |
| 6      | 8        | 8.79%   |
| 16     | 5        | 5.49%   |
| 1      | 1        | 1.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 84       | 93.33%  |
| 2      | 6        | 6.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 49       | 53.85%  |
| 1      | 42       | 46.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 90       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 10       | 10.87%  |
| 0x206a7    | 8        | 8.7%    |
| 0x306c3    | 5        | 5.43%   |
| 0x1067a    | 5        | 5.43%   |
| 0x08108109 | 5        | 5.43%   |
| 0x506e3    | 4        | 4.35%   |
| Unknown    | 4        | 4.35%   |
| 0xa0671    | 3        | 3.26%   |
| 0x08701021 | 3        | 3.26%   |
| 0x0800820d | 3        | 3.26%   |
| 0x906ed    | 2        | 2.17%   |
| 0x906ea    | 2        | 2.17%   |
| 0x906e9    | 2        | 2.17%   |
| 0x90675    | 2        | 2.17%   |
| 0x206d7    | 2        | 2.17%   |
| 0x106e5    | 2        | 2.17%   |
| 0x08101016 | 2        | 2.17%   |
| 0x010000c8 | 2        | 2.17%   |
| 0xf65      | 1        | 1.09%   |
| 0xf47      | 1        | 1.09%   |
| 0xf43      | 1        | 1.09%   |
| 0xa0655    | 1        | 1.09%   |
| 0xa0653    | 1        | 1.09%   |
| 0x906c0    | 1        | 1.09%   |
| 0x806ea    | 1        | 1.09%   |
| 0x6fd      | 1        | 1.09%   |
| 0x6fb      | 1        | 1.09%   |
| 0x6f2      | 1        | 1.09%   |
| 0x306e4    | 1        | 1.09%   |
| 0x206d6    | 1        | 1.09%   |
| 0x206c2    | 1        | 1.09%   |
| 0x20655    | 1        | 1.09%   |
| 0x106a5    | 1        | 1.09%   |
| 0x0a50000b | 1        | 1.09%   |
| 0x0a20120a | 1        | 1.09%   |
| 0x0a201016 | 1        | 1.09%   |
| 0x08701030 | 1        | 1.09%   |
| 0x0810100b | 1        | 1.09%   |
| 0x08001137 | 1        | 1.09%   |
| 0x08001129 | 1        | 1.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 12       | 13.19%  |
| SandyBridge | 11       | 12.09%  |
| Zen+        | 8        | 8.79%   |
| KabyLake    | 7        | 7.69%   |
| Zen         | 5        | 5.49%   |
| Penryn      | 5        | 5.49%   |
| Haswell     | 5        | 5.49%   |
| Unknown     | 5        | 5.49%   |
| Skylake     | 4        | 4.4%    |
| K10         | 4        | 4.4%    |
| Zen 3       | 3        | 3.3%    |
| Zen 2       | 3        | 3.3%    |
| Piledriver  | 3        | 3.3%    |
| NetBurst    | 3        | 3.3%    |
| Nehalem     | 3        | 3.3%    |
| Core        | 3        | 3.3%    |
| Westmere    | 2        | 2.2%    |
| CometLake   | 2        | 2.2%    |
| Tremont     | 1        | 1.1%    |
| Bulldozer   | 1        | 1.1%    |
| Bobcat      | 1        | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 51       | 52.04%  |
| Intel  | 25       | 25.51%  |
| AMD    | 22       | 22.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 6        | 6%      |
| Nvidia GT218 [GeForce 210]                                                | 5        | 5%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5        | 5%      |
| Nvidia GP108 [GeForce GT 1030]                                            | 4        | 4%      |
| Nvidia GK208B [GeForce GT 730]                                            | 4        | 4%      |
| Nvidia GK208B [GeForce GT 710]                                            | 4        | 4%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 4        | 4%      |
| Nvidia GM204 [GeForce GTX 970]                                            | 3        | 3%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 3        | 3%      |
| Nvidia GM206 [GeForce GTX 960]                                            | 2        | 2%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 2        | 2%      |
| Nvidia TU116 [GeForce GTX 1660]                                           | 1        | 1%      |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                        | 1        | 1%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1        | 1%      |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1        | 1%      |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                      | 1        | 1%      |
| Nvidia TU106 [GeForce GTX 1650]                                           | 1        | 1%      |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                     | 1        | 1%      |
| Nvidia GP107GL [Quadro P620]                                              | 1        | 1%      |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1        | 1%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1        | 1%      |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                       | 1        | 1%      |
| Nvidia GP104 [GeForce GTX 1070]                                           | 1        | 1%      |
| Nvidia GM107GL [Quadro K620]                                              | 1        | 1%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1        | 1%      |
| Nvidia GK107 [GeForce GT 640]                                             | 1        | 1%      |
| Nvidia GK106 [GeForce GTX 650 Ti]                                         | 1        | 1%      |
| Nvidia GK104 [GeForce GTX 760]                                            | 1        | 1%      |
| Nvidia GF119 [NVS 310]                                                    | 1        | 1%      |
| Nvidia GF116 [GeForce GTX 550 Ti]                                         | 1        | 1%      |
| Nvidia GF114 [GeForce GTX 560 Ti]                                         | 1        | 1%      |
| Nvidia GA102 [GeForce RTX 3090]                                           | 1        | 1%      |
| Nvidia GA102 [GeForce RTX 3080]                                           | 1        | 1%      |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                        | 1        | 1%      |
| Nvidia G92 [GeForce GTS 250]                                              | 1        | 1%      |
| Nvidia G92 [GeForce 8800 GT]                                              | 1        | 1%      |
| Nvidia G72 [GeForce 7500 LE]                                              | 1        | 1%      |
| Nvidia G72 [GeForce 7300 LE]                                              | 1        | 1%      |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                    | 1        | 1%      |
| Nvidia C78 [GeForce 9100]                                                 | 1        | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 48       | 52.17%  |
| 1 x Intel      | 21       | 22.83%  |
| 1 x AMD        | 16       | 17.39%  |
| AMD + Nvidia   | 3        | 3.26%   |
| 2 x AMD        | 2        | 2.17%   |
| Intel + Nvidia | 1        | 1.09%   |
| Intel + AMD    | 1        | 1.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 59       | 64.84%  |
| Proprietary | 22       | 24.18%  |
| Unknown     | 10       | 10.99%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 33.7%   |
| 1.01-2.0   | 21       | 22.83%  |
| 3.01-4.0   | 10       | 10.87%  |
| 0.01-0.5   | 10       | 10.87%  |
| 0.51-1.0   | 8        | 8.7%    |
| 7.01-8.0   | 4        | 4.35%   |
| 5.01-6.0   | 4        | 4.35%   |
| 8.01-16.0  | 2        | 2.17%   |
| 2.01-3.0   | 1        | 1.09%   |
| 16.01-24.0 | 1        | 1.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 14.46%  |
| Goldstar             | 11       | 13.25%  |
| Acer                 | 8        | 9.64%   |
| Hewlett-Packard      | 7        | 8.43%   |
| Dell                 | 6        | 7.23%   |
| BenQ                 | 6        | 7.23%   |
| Unknown              | 5        | 6.02%   |
| Philips              | 5        | 6.02%   |
| AOC                  | 3        | 3.61%   |
| Ancor Communications | 3        | 3.61%   |
| Iiyama               | 2        | 2.41%   |
| ___                  | 1        | 1.2%    |
| ViewSonic            | 1        | 1.2%    |
| Unknown (XXX)        | 1        | 1.2%    |
| Sony                 | 1        | 1.2%    |
| SKY                  | 1        | 1.2%    |
| PLN                  | 1        | 1.2%    |
| Medion               | 1        | 1.2%    |
| Lenovo Group Limited | 1        | 1.2%    |
| Lenovo               | 1        | 1.2%    |
| Insignia             | 1        | 1.2%    |
| HPN                  | 1        | 1.2%    |
| HannStar             | 1        | 1.2%    |
| AUS                  | 1        | 1.2%    |
| ASUSTek Computer     | 1        | 1.2%    |
| Unknown              | 1        | 1.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3        | 3.33%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 2        | 2.22%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2        | 2.22%   |
| ___ LCDTV16 ___0101 1360x768                                         | 1        | 1.11%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch             | 1        | 1.11%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                   | 1        | 1.11%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                | 1        | 1.11%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                 | 1        | 1.11%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 1.11%   |
| Unknown LCD Monitor Dell SE2717H/HX 1920x1080                        | 1        | 1.11%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 1.11%   |
| Sony LCD Monitor TV 3840x1080                                        | 1        | 1.11%   |
| SKY TV-monitor SKY1402 3840x2160 708x398mm 32.0-inch                 | 1        | 1.11%   |
| SKY TV SKY1502 3840x2160 708x398mm 32.0-inch                         | 1        | 1.11%   |
| SKY TV SKY1502 3840x2160 1150x650mm 52.0-inch                        | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 520x290mm 23.4-inch | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch | 1        | 1.11%   |
| Samsung Electronics SMFX2490HD SAM074A 1920x1080 530x300mm 24.0-inch | 1        | 1.11%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch    | 1        | 1.11%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 1.11%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 1.11%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                   | 1        | 1.11%   |
| Samsung Electronics LCD Monitor S27R65 3840x1080                     | 1        | 1.11%   |
| Samsung Electronics LCD Monitor S27R65                               | 1        | 1.11%   |
| Samsung Electronics LCD Monitor C27F390                              | 1        | 1.11%   |
| Samsung Electronics LC27T55 SAM701E 1920x1080 609x349mm 27.6-inch    | 1        | 1.11%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch   | 1        | 1.11%   |
| PLN LCD Monitor PXL2790MW 1920x1080                                  | 1        | 1.11%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch            | 1        | 1.11%   |
| Philips LCD Monitor PHL 242V8 1920x1080                              | 1        | 1.11%   |
| Philips 244E PHLC036 1920x1080 521x293mm 23.5-inch                   | 1        | 1.11%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                  | 1        | 1.11%   |
| Lenovo Group Limited LCD Monitor LEN G32qc-10 4480x1440              | 1        | 1.11%   |
| Lenovo C24-20 LEN62A8 1920x1080 527x296mm 23.8-inch                  | 1        | 1.11%   |
| Insignia DX19LD150A11 BBY1943 1360x768 409x230mm 18.5-inch           | 1        | 1.11%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch               | 1        | 1.11%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                 | 1        | 1.11%   |
| HPN LCD Monitor HP 32 Display 1920x1080                              | 1        | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 36       | 46.15%  |
| 1680x1050 (WSXGA+) | 7        | 8.97%   |
| 3840x2160 (4K)     | 5        | 6.41%   |
| 2560x1440 (QHD)    | 4        | 5.13%   |
| 1366x768 (WXGA)    | 4        | 5.13%   |
| 2560x1080          | 3        | 3.85%   |
| 1600x900 (HD+)     | 3        | 3.85%   |
| Unknown            | 3        | 3.85%   |
| 3840x1080          | 2        | 2.56%   |
| 3440x1440          | 2        | 2.56%   |
| 1440x900 (WXGA+)   | 2        | 2.56%   |
| 1360x768           | 2        | 2.56%   |
| 1280x1024 (SXGA)   | 2        | 2.56%   |
| 4480x1440          | 1        | 1.28%   |
| 1920x1200 (WUXGA)  | 1        | 1.28%   |
| 1024x768 (XGA)     | 1        | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 21.69%  |
| 21      | 11       | 13.25%  |
| 24      | 10       | 12.05%  |
| 27      | 8        | 9.64%   |
| 23      | 6        | 7.23%   |
| 34      | 4        | 4.82%   |
| 22      | 4        | 4.82%   |
| 18      | 4        | 4.82%   |
| 20      | 3        | 3.61%   |
| 19      | 3        | 3.61%   |
| 32      | 2        | 2.41%   |
| 31      | 2        | 2.41%   |
| 72      | 1        | 1.2%    |
| 64      | 1        | 1.2%    |
| 54      | 1        | 1.2%    |
| 52      | 1        | 1.2%    |
| 28      | 1        | 1.2%    |
| 25      | 1        | 1.2%    |
| 17      | 1        | 1.2%    |
| 15      | 1        | 1.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 28.57%  |
| 401-500     | 20       | 25.97%  |
| Unknown     | 18       | 23.38%  |
| 701-800     | 6        | 7.79%   |
| 601-700     | 4        | 5.19%   |
| 351-400     | 3        | 3.9%    |
| 1001-1500   | 2        | 2.6%    |
| 301-350     | 1        | 1.3%    |
| 1501-2000   | 1        | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 39       | 53.42%  |
| Unknown | 18       | 24.66%  |
| 16/10   | 8        | 10.96%  |
| 21/9    | 5        | 6.85%   |
| 5/4     | 2        | 2.74%   |
| 4/3     | 1        | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 27       | 33.75%  |
| Unknown        | 18       | 22.5%   |
| 351-500        | 8        | 10%     |
| 301-350        | 8        | 10%     |
| 151-200        | 6        | 7.5%    |
| 251-300        | 4        | 5%      |
| 141-150        | 4        | 5%      |
| More than 1000 | 3        | 3.75%   |
| 131-140        | 1        | 1.25%   |
| 101-110        | 1        | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 45       | 57.69%  |
| Unknown | 18       | 23.08%  |
| 101-120 | 12       | 15.38%  |
| 1-50    | 2        | 2.56%   |
| 121-160 | 1        | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 68       | 73.91%  |
| 2     | 13       | 14.13%  |
| 0     | 9        | 9.78%   |
| 3     | 2        | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 54       | 43.2%   |
| Intel                    | 40       | 32%     |
| Qualcomm Atheros         | 7        | 5.6%    |
| Ralink Technology        | 4        | 3.2%    |
| TP-Link                  | 3        | 2.4%    |
| Broadcom                 | 3        | 2.4%    |
| Samsung Electronics      | 2        | 1.6%    |
| Nvidia                   | 2        | 1.6%    |
| Huawei Technologies      | 2        | 1.6%    |
| Ralink                   | 1        | 0.8%    |
| Qualcomm                 | 1        | 0.8%    |
| NetGear                  | 1        | 0.8%    |
| Mercucys                 | 1        | 0.8%    |
| Marvell Technology Group | 1        | 0.8%    |
| IMC Networks             | 1        | 0.8%    |
| HTC (High Tech Computer) | 1        | 0.8%    |
| Belkin Components        | 1        | 0.8%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 43       | 29.66%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 9        | 6.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 2.76%   |
| Intel I211 Gigabit Network Connection                                                         | 4        | 2.76%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 3        | 2.07%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 2.07%   |
| Intel Ethernet Connection (7) I219-V                                                          | 3        | 2.07%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 1.38%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 1.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 1.38%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 1.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2        | 1.38%   |
| Intel Wireless-AC 9260                                                                        | 2        | 1.38%   |
| Intel Wireless 3165                                                                           | 2        | 1.38%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 1.38%   |
| Intel Ethernet Connection I217-V                                                              | 2        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2        | 1.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 1.38%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 1.38%   |
| Intel 82574L Gigabit Network Connection                                                       | 2        | 1.38%   |
| Intel 82573L Gigabit Ethernet Controller                                                      | 2        | 1.38%   |
| Huawei MLA-L11                                                                                | 2        | 1.38%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 0.69%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 0.69%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 0.69%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 0.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 0.69%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.69%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.69%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 0.69%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 1        | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 34.88%  |
| Intel                 | 12       | 27.91%  |
| Ralink Technology     | 4        | 9.3%    |
| TP-Link               | 3        | 6.98%   |
| Qualcomm Atheros      | 3        | 6.98%   |
| Ralink                | 1        | 2.33%   |
| NetGear               | 1        | 2.33%   |
| Mercucys              | 1        | 2.33%   |
| IMC Networks          | 1        | 2.33%   |
| Broadcom              | 1        | 2.33%   |
| Belkin Components     | 1        | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 9.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 6.82%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 4.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 4.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 4.55%   |
| Intel Wireless-AC 9260                                                                        | 2        | 4.55%   |
| Intel Wireless 3165                                                                           | 2        | 4.55%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 4.55%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.27%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 2.27%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 2.27%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 2.27%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 2.27%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.27%   |
| Realtek 802.11ac NIC                                                                          | 1        | 2.27%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 2.27%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 2.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 2.27%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]                | 1        | 2.27%   |
| NetGear A6150                                                                                 | 1        | 2.27%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 2.27%   |
| Intel Wireless 7265                                                                           | 1        | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1        | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 2.27%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                          | 1        | 2.27%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1        | 2.27%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1        | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 49       | 50.52%  |
| Intel                    | 33       | 34.02%  |
| Qualcomm Atheros         | 4        | 4.12%   |
| Samsung Electronics      | 2        | 2.06%   |
| Nvidia                   | 2        | 2.06%   |
| Huawei Technologies      | 2        | 2.06%   |
| Broadcom                 | 2        | 2.06%   |
| Qualcomm                 | 1        | 1.03%   |
| Marvell Technology Group | 1        | 1.03%   |
| HTC (High Tech Computer) | 1        | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43       | 42.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 8.91%   |
| Intel I211 Gigabit Network Connection                             | 4        | 3.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.97%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.97%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.98%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.98%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.98%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.98%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.98%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 1.98%   |
| Huawei MLA-L11                                                    | 2        | 1.98%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.99%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.99%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.99%   |
| Qualcomm Android                                                  | 1        | 0.99%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.99%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.99%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.99%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.99%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.99%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.99%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.99%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.99%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.99%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 0.99%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.99%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.99%   |
| Intel 82545GM Gigabit Ethernet Controller                         | 1        | 0.99%   |
| HTC (High Tech Computer) Desire HD (modem mode)                   | 1        | 0.99%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.99%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.99%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 89       | 68.99%  |
| WiFi     | 40       | 31.01%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 78.49%  |
| WiFi     | 20       | 21.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 63       | 70%     |
| 2     | 26       | 28.89%  |
| 0     | 1        | 1.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 73.91%  |
| Yes  | 24       | 26.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 12       | 52.17%  |
| Cambridge Silicon Radio | 5        | 21.74%  |
| Realtek Semiconductor   | 2        | 8.7%    |
| Broadcom                | 2        | 8.7%    |
| Lite-On Technology      | 1        | 4.35%   |
| Dell                    | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 21.74%  |
| Intel Bluetooth wireless interface                  | 3        | 13.04%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 8.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 8.7%    |
| Intel AX200 Bluetooth                               | 2        | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4.35%   |
| Realtek Bluetooth Radio                             | 1        | 4.35%   |
| Lite-On Bluetooth Device                            | 1        | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.35%   |
| Intel AX210 Bluetooth                               | 1        | 4.35%   |
| Intel AX201 Bluetooth                               | 1        | 4.35%   |
| Dell BT Mini-Receiver                               | 1        | 4.35%   |
| Broadcom BCM92045B3 ROM                             | 1        | 4.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 60       | 40.27%  |
| Nvidia                               | 46       | 30.87%  |
| AMD                                  | 31       | 20.81%  |
| C-Media Electronics                  | 3        | 2.01%   |
| JMTek                                | 2        | 1.34%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.67%   |
| Sony                                 | 1        | 0.67%   |
| Native Instruments                   | 1        | 0.67%   |
| Micro Star International             | 1        | 0.67%   |
| Logitech                             | 1        | 0.67%   |
| GN Netcom                            | 1        | 0.67%   |
| Generalplus Technology               | 1        | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 5.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 5.29%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 5.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 4.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 4.71%   |
| Nvidia High Definition Audio Controller                                    | 6        | 3.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 2.94%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 2.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 2.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 2.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 2.35%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 2.35%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 2.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 2.35%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.76%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.18%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.18%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.18%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.18%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.18%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.18%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.18%   |
| Thesycon Systemsoftware & Consulting D10 Balanced                          | 1        | 0.59%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.59%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1        | 0.59%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.59%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 21.62%  |
| Unknown             | 6        | 16.22%  |
| Micron Technology   | 4        | 10.81%  |
| Corsair             | 4        | 10.81%  |
| Kingston            | 3        | 8.11%   |
| Crucial             | 3        | 8.11%   |
| G.Skill             | 2        | 5.41%   |
| Smart               | 1        | 2.7%    |
| SK hynix            | 1        | 2.7%    |
| Nanya Technology    | 1        | 2.7%    |
| Elpida              | 1        | 2.7%    |
| AVEXIR              | 1        | 2.7%    |
| A-DATA Technology   | 1        | 2.7%    |
| Unknown             | 1        | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 2.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                | 1        | 2.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 2.5%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                | 1        | 2.5%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 1        | 2.5%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 2.5%    |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                 | 1        | 2.5%    |
| Unknown RAM D4 8G 8GB DIMM DDR4 2666MT/s                 | 1        | 2.5%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s    | 1        | 2.5%    |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s     | 1        | 2.5%    |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 2.5%    |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s                | 1        | 2.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 2.5%    |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s    | 1        | 2.5%    |
| Samsung RAM M393B5270DH0-YH9 4GB DIMM DDR3 1333MT/s      | 1        | 2.5%    |
| Samsung RAM M393B2G70DB0-CMA 16GB DIMM DDR3 1867MT/s     | 1        | 2.5%    |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1600MT/s      | 1        | 2.5%    |
| Samsung RAM M393B1G70BH0-YK0 8GB DIMM DDR3 1600MT/s      | 1        | 2.5%    |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s     | 1        | 2.5%    |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s        | 1        | 2.5%    |
| Micron RAM 36JSF2G72PZ-1G9E1 16GB DIMM DDR3 1866MT/s     | 1        | 2.5%    |
| Micron RAM 18KSF1G72PZ-1G4E1 8GB DIMM DDR3 1333MT/s      | 1        | 2.5%    |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s      | 1        | 2.5%    |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s     | 1        | 2.5%    |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 1        | 2.5%    |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.5%    |
| Kingston RAM 99U5403-034.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 2.5%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 1        | 2.5%    |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s    | 1        | 2.5%    |
| Elpida RAM EBE21UE8AFFA-8G-F 2GB DIMM DDR2 800MT/s       | 1        | 2.5%    |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s    | 1        | 2.5%    |
| Crucial RAM CT4G4DFS824A.C8FADP 4GB DIMM DDR4 2400MT/s   | 1        | 2.5%    |
| Crucial RAM CT16G4DFD8266.M16FE 16GB DIMM DDR4 2667MT/s  | 1        | 2.5%    |
| Corsair RAM VS2GB1333D4 2GB DIMM DDR3 1600MT/s           | 1        | 2.5%    |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s | 1        | 2.5%    |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s   | 1        | 2.5%    |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s      | 1        | 2.5%    |
| AVEXIR RAM DDR4-3000 CL16 8GB 8GB DIMM DDR4 2133MT/s     | 1        | 2.5%    |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s              | 1        | 2.5%    |
| Unknown                                                  | 1        | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 13       | 40.63%  |
| DDR3    | 12       | 37.5%   |
| DDR2    | 3        | 9.38%   |
| SDRAM   | 2        | 6.25%   |
| Unknown | 2        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 29       | 93.55%  |
| SODIMM | 2        | 6.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 11       | 31.43%  |
| 4096  | 10       | 28.57%  |
| 16384 | 7        | 20%     |
| 2048  | 4        | 11.43%  |
| 1024  | 2        | 5.71%   |
| 32768 | 1        | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 8        | 23.53%  |
| 1333  | 4        | 11.76%  |
| 2667  | 3        | 8.82%   |
| 3600  | 2        | 5.88%   |
| 3200  | 2        | 5.88%   |
| 2400  | 2        | 5.88%   |
| 1866  | 2        | 5.88%   |
| 667   | 2        | 5.88%   |
| 3733  | 1        | 2.94%   |
| 3400  | 1        | 2.94%   |
| 2666  | 1        | 2.94%   |
| 2133  | 1        | 2.94%   |
| 1867  | 1        | 2.94%   |
| 1334  | 1        | 2.94%   |
| 1066  | 1        | 2.94%   |
| 800   | 1        | 2.94%   |
| 533   | 1        | 2.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 1        | 25%     |
| Konica Minolta     | 1        | 25%     |
| Hewlett-Packard    | 1        | 25%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson ET-2820 Series | 1        | 25%     |
| Konica Minolta 185         | 1        | 25%     |
| HP OfficeJet Pro 8730      | 1        | 25%     |
| Brother MFC-L2685DW        | 1        | 25%     |

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
| Logitech                      | 5        | 27.78%  |
| Sunplus Innovation Technology | 3        | 16.67%  |
| Huawei Technologies           | 2        | 11.11%  |
| Creative Technology           | 2        | 11.11%  |
| Z-Star Microelectronics       | 1        | 5.56%   |
| Pixart Imaging                | 1        | 5.56%   |
| OmniVision Technologies       | 1        | 5.56%   |
| MacroSilicon                  | 1        | 5.56%   |
| ARC International             | 1        | 5.56%   |
| Alcor Micro                   | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Sunplus FHD Camera Microphone                  | 2        | 11.11%  |
| Huawei HD Webcam                               | 2        | 11.11%  |
| Z-Star Venus USB2.0 Camera                     | 1        | 5.56%   |
| Sunplus AAPDQT-0622-W                          | 1        | 5.56%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 1        | 5.56%   |
| OmniVision Integrated Webcam for Dell XPS 2010 | 1        | 5.56%   |
| MacroSilicon USB Video                         | 1        | 5.56%   |
| Logitech Webcam C925e                          | 1        | 5.56%   |
| Logitech Webcam C270                           | 1        | 5.56%   |
| Logitech Webcam C210                           | 1        | 5.56%   |
| Logitech Webcam B500                           | 1        | 5.56%   |
| Logitech Logi Webcam C920e                     | 1        | 5.56%   |
| Creative VF0610 Live! Cam Socialize HD         | 1        | 5.56%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 5.56%   |
| ARC International Camera                       | 1        | 5.56%   |
| Alcor Micro USB 5.0M AF Camera                 | 1        | 5.56%   |

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
| 0     | 67       | 72.83%  |
| 1     | 24       | 26.09%  |
| 2     | 1        | 1.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 14       | 51.85%  |
| Net/wireless             | 8        | 29.63%  |
| Unassigned class         | 1        | 3.7%    |
| Storage/raid             | 1        | 3.7%    |
| Multimedia controller    | 1        | 3.7%    |
| Communication controller | 1        | 3.7%    |
| Camera                   | 1        | 3.7%    |

