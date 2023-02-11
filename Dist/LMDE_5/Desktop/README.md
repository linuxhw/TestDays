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

Total: 116

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-12-amd64          | 15       | 17.05%  |
| 5.10.0-20-amd64          | 12       | 13.64%  |
| 5.10.0-17-amd64          | 11       | 12.5%   |
| 5.10.0-14-amd64          | 10       | 11.36%  |
| 5.10.0-13-amd64          | 10       | 11.36%  |
| 5.10.0-18-amd64          | 9        | 10.23%  |
| 5.10.0-19-amd64          | 8        | 9.09%   |
| 5.10.0-21-amd64          | 5        | 5.68%   |
| 5.10.0-15-amd64          | 3        | 3.41%   |
| 5.10.0-16-amd64          | 2        | 2.27%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1        | 1.14%   |
| 5.19.0-0.deb11.2-amd64   | 1        | 1.14%   |
| 5.10.0-13-686            | 1        | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 79       | 97.53%  |
| 6.0.2   | 1        | 1.23%   |
| 5.19.0  | 1        | 1.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 79       | 97.53%  |
| 6.0     | 1        | 1.23%   |
| 5.19    | 1        | 1.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 80       | 98.77%  |
| i686   | 1        | 1.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 73       | 90.12%  |
| Cinnamon   | 5        | 6.17%   |
| XFCE       | 1        | 1.23%   |
| MATE       | 1        | 1.23%   |
| KDE5       | 1        | 1.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 81       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 70.37%  |
| LightDM | 22       | 27.16%  |
| SDDM    | 1        | 1.23%   |
| GDM     | 1        | 1.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 28       | 34.57%  |
| de_DE | 11       | 13.58%  |
| ru_RU | 7        | 8.64%   |
| pt_BR | 7        | 8.64%   |
| it_IT | 4        | 4.94%   |
| fr_FR | 4        | 4.94%   |
| en_CA | 3        | 3.7%    |
| sv_SE | 2        | 2.47%   |
| pl_PL | 2        | 2.47%   |
| es_ES | 2        | 2.47%   |
| en_GB | 2        | 2.47%   |
| sk_SK | 1        | 1.23%   |
| it_CH | 1        | 1.23%   |
| fr_CA | 1        | 1.23%   |
| es_NI | 1        | 1.23%   |
| en_ZA | 1        | 1.23%   |
| en_AU | 1        | 1.23%   |
| de_AT | 1        | 1.23%   |
| cs_CZ | 1        | 1.23%   |
| ar_EG | 1        | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 48       | 59.26%  |
| EFI  | 33       | 40.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 75       | 92.59%  |
| Tmpfs   | 3        | 3.7%    |
| Btrfs   | 2        | 2.47%   |
| Overlay | 1        | 1.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 58       | 71.6%   |
| GPT     | 14       | 17.28%  |
| MBR     | 9        | 11.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 90.12%  |
| Yes       | 8        | 9.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 70       | 86.42%  |
| Yes       | 11       | 13.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 24.69%  |
| MSI                 | 11       | 13.58%  |
| Gigabyte Technology | 11       | 13.58%  |
| Dell                | 10       | 12.35%  |
| Hewlett-Packard     | 5        | 6.17%   |
| ASRock              | 4        | 4.94%   |
| Acer                | 4        | 4.94%   |
| Lenovo              | 3        | 3.7%    |
| Intel               | 3        | 3.7%    |
| Fujitsu             | 2        | 2.47%   |
| SiYW                | 1        | 1.23%   |
| Samsung Electronics | 1        | 1.23%   |
| Pegatron            | 1        | 1.23%   |
| Gateway             | 1        | 1.23%   |
| eMachines           | 1        | 1.23%   |
| Digiboard           | 1        | 1.23%   |
| AZW                 | 1        | 1.23%   |
| ADVANSUS            | 1        | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS PRIME B350M-A                  | 2        | 2.47%   |
| SiYW V200 Series                    | 1        | 1.23%   |
| Samsung DeskTop System              | 1        | 1.23%   |
| Pegatron Pro 3015 Microtower PC     | 1        | 1.23%   |
| MSI MS-7D54                         | 1        | 1.23%   |
| MSI MS-7C52                         | 1        | 1.23%   |
| MSI MS-7B79                         | 1        | 1.23%   |
| MSI MS-7B23                         | 1        | 1.23%   |
| MSI MS-7B17                         | 1        | 1.23%   |
| MSI MS-7A40                         | 1        | 1.23%   |
| MSI MS-7984                         | 1        | 1.23%   |
| MSI MS-7977                         | 1        | 1.23%   |
| MSI MS-7974                         | 1        | 1.23%   |
| MSI MS-7851                         | 1        | 1.23%   |
| MSI MS-7721                         | 1        | 1.23%   |
| Lenovo V55t-15ARE 11KJ0036TX        | 1        | 1.23%   |
| Lenovo ThinkCentre M92p 3238E9U     | 1        | 1.23%   |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1        | 1.23%   |
| Intel H61M-DS2V                     | 1        | 1.23%   |
| Intel DQ77MK AAG39642-400           | 1        | 1.23%   |
| Intel B75                           | 1        | 1.23%   |
| HP Z820 Workstation                 | 1        | 1.23%   |
| HP Z600 Workstation                 | 1        | 1.23%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 1.23%   |
| HP EliteDesk 800 G3 SFF             | 1        | 1.23%   |
| HP Compaq Pro 6300 SFF              | 1        | 1.23%   |
| Gigabyte Z68A-D3H-B3                | 1        | 1.23%   |
| Gigabyte X570 AORUS ULTRA           | 1        | 1.23%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 1        | 1.23%   |
| Gigabyte H110M-S2H                  | 1        | 1.23%   |
| Gigabyte GA-970A-D3                 | 1        | 1.23%   |
| Gigabyte GA-78LMT-USB3              | 1        | 1.23%   |
| Gigabyte B85M-DS3H-A                | 1        | 1.23%   |
| Gigabyte B560 DS3H AC-Y1            | 1        | 1.23%   |
| Gigabyte B450M DS3H                 | 1        | 1.23%   |
| Gigabyte B450 I AORUS PRO WIFI      | 1        | 1.23%   |
| Gigabyte B450 AORUS M               | 1        | 1.23%   |
| Gateway DX4870                      | 1        | 1.23%   |
| Fujitsu D3003-S2                    | 1        | 1.23%   |
| Fujitsu CELSIUS W410                | 1        | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 6        | 7.41%   |
| Acer Aspire            | 3        | 3.7%    |
| Lenovo ThinkCentre     | 2        | 2.47%   |
| Gigabyte B450          | 2        | 2.47%   |
| Dell Vostro            | 2        | 2.47%   |
| Dell Precision         | 2        | 2.47%   |
| Dell OptiPlex          | 2        | 2.47%   |
| Dell Inspiron          | 2        | 2.47%   |
| ASUS ROG               | 2        | 2.47%   |
| SiYW V200              | 1        | 1.23%   |
| Samsung DeskTop        | 1        | 1.23%   |
| Pegatron Pro           | 1        | 1.23%   |
| MSI MS-7D54            | 1        | 1.23%   |
| MSI MS-7C52            | 1        | 1.23%   |
| MSI MS-7B79            | 1        | 1.23%   |
| MSI MS-7B23            | 1        | 1.23%   |
| MSI MS-7B17            | 1        | 1.23%   |
| MSI MS-7A40            | 1        | 1.23%   |
| MSI MS-7984            | 1        | 1.23%   |
| MSI MS-7977            | 1        | 1.23%   |
| MSI MS-7974            | 1        | 1.23%   |
| MSI MS-7851            | 1        | 1.23%   |
| MSI MS-7721            | 1        | 1.23%   |
| Lenovo V55t-15ARE      | 1        | 1.23%   |
| Intel H61M-DS2V        | 1        | 1.23%   |
| Intel DQ77MK           | 1        | 1.23%   |
| Intel B75              | 1        | 1.23%   |
| HP Z820                | 1        | 1.23%   |
| HP Z600                | 1        | 1.23%   |
| HP Pavilion            | 1        | 1.23%   |
| HP EliteDesk           | 1        | 1.23%   |
| HP Compaq              | 1        | 1.23%   |
| Gigabyte Z68A-D3H-B3   | 1        | 1.23%   |
| Gigabyte X570          | 1        | 1.23%   |
| Gigabyte X470          | 1        | 1.23%   |
| Gigabyte H110M-S2H     | 1        | 1.23%   |
| Gigabyte GA-970A-D3    | 1        | 1.23%   |
| Gigabyte GA-78LMT-USB3 | 1        | 1.23%   |
| Gigabyte B85M-DS3H-A   | 1        | 1.23%   |
| Gigabyte B560          | 1        | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 14       | 17.28%  |
| 2012 | 11       | 13.58%  |
| 2009 | 7        | 8.64%   |
| 2015 | 6        | 7.41%   |
| 2021 | 5        | 6.17%   |
| 2017 | 5        | 6.17%   |
| 2011 | 5        | 6.17%   |
| 2019 | 4        | 4.94%   |
| 2013 | 4        | 4.94%   |
| 2010 | 4        | 4.94%   |
| 2022 | 3        | 3.7%    |
| 2016 | 3        | 3.7%    |
| 2006 | 3        | 3.7%    |
| 2020 | 2        | 2.47%   |
| 2014 | 2        | 2.47%   |
| 2007 | 2        | 2.47%   |
| 2008 | 1        | 1.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 81       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 81       | 98.78%  |
| Enabled  | 1        | 1.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 81       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 20       | 24.39%  |
| 16.01-24.0  | 19       | 23.17%  |
| 4.01-8.0    | 14       | 17.07%  |
| 32.01-64.0  | 13       | 15.85%  |
| 3.01-4.0    | 8        | 9.76%   |
| 24.01-32.0  | 3        | 3.66%   |
| 1.01-2.0    | 3        | 3.66%   |
| 64.01-256.0 | 1        | 1.22%   |
| 0.51-1.0    | 1        | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 31       | 36.47%  |
| 2.01-3.0  | 25       | 29.41%  |
| 4.01-8.0  | 12       | 14.12%  |
| 3.01-4.0  | 10       | 11.76%  |
| 0.51-1.0  | 5        | 5.88%   |
| 8.01-16.0 | 2        | 2.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 42.68%  |
| 2      | 21       | 25.61%  |
| 3      | 14       | 17.07%  |
| 4      | 6        | 7.32%   |
| 5      | 4        | 4.88%   |
| 6      | 2        | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 51.22%  |
| Yes       | 40       | 48.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 80       | 98.77%  |
| No        | 1        | 1.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 54.88%  |
| Yes       | 37       | 45.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 72.84%  |
| Yes       | 22       | 27.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 19       | 23.46%  |
| Germany      | 11       | 13.58%  |
| Russia       | 8        | 9.88%   |
| Brazil       | 8        | 9.88%   |
| Italy        | 6        | 7.41%   |
| France       | 5        | 6.17%   |
| Canada       | 4        | 4.94%   |
| Sweden       | 3        | 3.7%    |
| UK           | 2        | 2.47%   |
| Spain        | 2        | 2.47%   |
| Poland       | 2        | 2.47%   |
| Australia    | 2        | 2.47%   |
| Venezuela    | 1        | 1.23%   |
| Turkey       | 1        | 1.23%   |
| South Africa | 1        | 1.23%   |
| Slovakia     | 1        | 1.23%   |
| Nicaragua    | 1        | 1.23%   |
| Netherlands  | 1        | 1.23%   |
| Mexico       | 1        | 1.23%   |
| Latvia       | 1        | 1.23%   |
| Austria      | 1        | 1.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Melbourne                | 2        | 2.41%   |
| Frankfurt am Main        | 2        | 2.41%   |
| Berlin                   | 2        | 2.41%   |
| Washington               | 1        | 1.2%    |
| Volta Redonda            | 1        | 1.2%    |
| Vitória da Conquista    | 1        | 1.2%    |
| Vincennes                | 1        | 1.2%    |
| Vicente Guerrero         | 1        | 1.2%    |
| Varese                   | 1        | 1.2%    |
| Ulyanovsk                | 1        | 1.2%    |
| Trieste                  | 1        | 1.2%    |
| Tolyatti                 | 1        | 1.2%    |
| Toledo                   | 1        | 1.2%    |
| Toccoa                   | 1        | 1.2%    |
| Tacoma                   | 1        | 1.2%    |
| Stockelsdorf             | 1        | 1.2%    |
| Stockbridge              | 1        | 1.2%    |
| Spruce Grove             | 1        | 1.2%    |
| Sollentuna               | 1        | 1.2%    |
| Solingen                 | 1        | 1.2%    |
| Schruns                  | 1        | 1.2%    |
| Sao Lourenço            | 1        | 1.2%    |
| Sant Feliu de Llobregat  | 1        | 1.2%    |
| San Antonio de Los Altos | 1        | 1.2%    |
| San Antonio              | 1        | 1.2%    |
| Rome                     | 1        | 1.2%    |
| Riga                     | 1        | 1.2%    |
| Reynoldsburg             | 1        | 1.2%    |
| Rennes                   | 1        | 1.2%    |
| Queensbury               | 1        | 1.2%    |
| Prestatyn                | 1        | 1.2%    |
| Porto Uniao              | 1        | 1.2%    |
| Porto Alegre             | 1        | 1.2%    |
| Piaseczno                | 1        | 1.2%    |
| Petrozavodsk             | 1        | 1.2%    |
| Pensacola                | 1        | 1.2%    |
| Oxford                   | 1        | 1.2%    |
| Orekhovo-Zuyevo          | 1        | 1.2%    |
| North Manchester         | 1        | 1.2%    |
| Nitra                    | 1        | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 42     | 19.29%  |
| Seagate             | 25       | 35     | 17.86%  |
| Samsung Electronics | 21       | 42     | 15%     |
| Kingston            | 10       | 13     | 7.14%   |
| Crucial             | 8        | 8      | 5.71%   |
| Toshiba             | 7        | 7      | 5%      |
| SanDisk             | 6        | 6      | 4.29%   |
| Hitachi             | 5        | 6      | 3.57%   |
| SK hynix            | 3        | 4      | 2.14%   |
| China               | 2        | 2      | 1.43%   |
| A-DATA Technology   | 2        | 2      | 1.43%   |
| XrayDisk            | 1        | 2      | 0.71%   |
| WALRAM              | 1        | 1      | 0.71%   |
| Unknown             | 1        | 1      | 0.71%   |
| Transcend           | 1        | 2      | 0.71%   |
| TGT                 | 1        | 1      | 0.71%   |
| TakeMS              | 1        | 1      | 0.71%   |
| SPCC                | 1        | 1      | 0.71%   |
| Phison Electronics  | 1        | 1      | 0.71%   |
| Phison              | 1        | 1      | 0.71%   |
| OCZ-VERTEX          | 1        | 1      | 0.71%   |
| Netac               | 1        | 1      | 0.71%   |
| Micron Technology   | 1        | 1      | 0.71%   |
| Intenso             | 1        | 1      | 0.71%   |
| Intel               | 1        | 1      | 0.71%   |
| Hewlett-Packard     | 1        | 1      | 0.71%   |
| GOODRAM             | 1        | 1      | 0.71%   |
| Gigabyte Technology | 1        | 2      | 0.71%   |
| BR                  | 1        | 1      | 0.71%   |
| ASMedia             | 1        | 1      | 0.71%   |
| Apple               | 1        | 1      | 0.71%   |
| Apacer              | 1        | 1      | 0.71%   |
| ADATA Technology    | 1        | 1      | 0.71%   |
| 2.5''               | 1        | 1      | 0.71%   |
| Unknown             | 1        | 2      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 5        | 3.05%   |
| Samsung SSD 850 EVO 500GB                           | 3        | 1.83%   |
| Kingston SA400S37240G 240GB SSD                     | 3        | 1.83%   |
| Crucial CT480BX500SSD1 480GB                        | 3        | 1.83%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 1.22%   |
| Seagate ST3320418AS 320GB                           | 2        | 1.22%   |
| Seagate ST3250318AS 249GB                           | 2        | 1.22%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 1.22%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 1.22%   |
| Samsung SSD 970 EVO 500GB                           | 2        | 1.22%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 2        | 1.22%   |
| Samsung NVMe SSD Drive 500GB                        | 2        | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 1.22%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 1.22%   |
| XrayDisk 480GB                                      | 1        | 0.61%   |
| XrayDisk 1TB                                        | 1        | 0.61%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1        | 0.61%   |
| WDC WD60EZAZ-00ZGHB0 6TB                            | 1        | 0.61%   |
| WDC WD5000LPSX-08A6W 500GB                          | 1        | 0.61%   |
| WDC WD5000AZLX-08K2TA0 500GB                        | 1        | 0.61%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1        | 0.61%   |
| WDC WD5000AAKX-22ERMA0 500GB                        | 1        | 0.61%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1        | 0.61%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1        | 0.61%   |
| WDC WD5000AAJS-00TKA0 500GB                         | 1        | 0.61%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 1        | 0.61%   |
| WDC WD3200AAJS-22B4A0 320GB                         | 1        | 0.61%   |
| WDC WD30EZRZ-00Z5HB0 3TB                            | 1        | 0.61%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 1        | 0.61%   |
| WDC WD3003FZEX-00Z4SA0 3TB                          | 1        | 0.61%   |
| WDC WD20SPZX-00UA7T0 2TB                            | 1        | 0.61%   |
| WDC WD1600HLHX-60JJPV1 160GB                        | 1        | 0.61%   |
| WDC WD1600AAJS-07PSA0 160GB                         | 1        | 0.61%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1        | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1        | 0.61%   |
| WDC WD10EZRX-00DC0B0 1TB                            | 1        | 0.61%   |
| WDC WD10EZEX-75M2NA0 1TB                            | 1        | 0.61%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1        | 0.61%   |
| WDC WD10EFRX-68JCSN0 1TB                            | 1        | 0.61%   |
| WDC WD10EFRX-68FYTN0 1TB                            | 1        | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 26       | 41     | 37.68%  |
| Seagate             | 25       | 34     | 36.23%  |
| Toshiba             | 6        | 6      | 8.7%    |
| Hitachi             | 5        | 6      | 7.25%   |
| Samsung Electronics | 4        | 5      | 5.8%    |
| Unknown             | 1        | 1      | 1.45%   |
| Intenso             | 1        | 1      | 1.45%   |
| ASMedia             | 1        | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 21     | 24.07%  |
| Kingston            | 8        | 11     | 14.81%  |
| Crucial             | 7        | 7      | 12.96%  |
| SanDisk             | 5        | 5      | 9.26%   |
| SK hynix            | 2        | 2      | 3.7%    |
| China               | 2        | 2      | 3.7%    |
| A-DATA Technology   | 2        | 2      | 3.7%    |
| WDC                 | 1        | 1      | 1.85%   |
| Transcend           | 1        | 2      | 1.85%   |
| Toshiba             | 1        | 1      | 1.85%   |
| TakeMS              | 1        | 1      | 1.85%   |
| SPCC                | 1        | 1      | 1.85%   |
| OCZ-VERTEX          | 1        | 1      | 1.85%   |
| Netac               | 1        | 1      | 1.85%   |
| Micron Technology   | 1        | 1      | 1.85%   |
| Hewlett-Packard     | 1        | 1      | 1.85%   |
| GOODRAM             | 1        | 1      | 1.85%   |
| Gigabyte Technology | 1        | 2      | 1.85%   |
| Apple               | 1        | 1      | 1.85%   |
| Apacer              | 1        | 1      | 1.85%   |
| 2.5''               | 1        | 1      | 1.85%   |
| Unknown             | 1        | 2      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 56       | 95     | 45.16%  |
| SSD     | 47       | 68     | 37.9%   |
| NVMe    | 16       | 26     | 12.9%   |
| Unknown | 5        | 6      | 4.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 77       | 159    | 77%     |
| NVMe | 16       | 26     | 16%     |
| SAS  | 7        | 10     | 7%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 59       | 99     | 57.84%  |
| 0.51-1.0   | 25       | 39     | 24.51%  |
| 1.01-2.0   | 8        | 10     | 7.84%   |
| 4.01-10.0  | 5        | 6      | 4.9%    |
| 2.01-3.0   | 3        | 6      | 2.94%   |
| 3.01-4.0   | 2        | 3      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 23.17%  |
| 251-500        | 18       | 21.95%  |
| 1001-2000      | 14       | 17.07%  |
| 501-1000       | 12       | 14.63%  |
| More than 3000 | 7        | 8.54%   |
| 2001-3000      | 4        | 4.88%   |
| 1-20           | 4        | 4.88%   |
| 51-100         | 3        | 3.66%   |
| 21-50          | 1        | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 26       | 31.33%  |
| 21-50          | 14       | 16.87%  |
| 251-500        | 9        | 10.84%  |
| 51-100         | 9        | 10.84%  |
| 501-1000       | 8        | 9.64%   |
| 101-250        | 7        | 8.43%   |
| 1001-2000      | 6        | 7.23%   |
| More than 3000 | 2        | 2.41%   |
| 2001-3000      | 2        | 2.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1        | 1      | 33.33%  |
| Seagate ST3250318AS 249GB       | 1        | 1      | 33.33%  |
| Seagate ST2000DX001-1CM164 2TB  | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 100%    |

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
| Detected | 62       | 139    | 70.45%  |
| Works    | 23       | 53     | 26.14%  |
| Malfunc  | 3        | 3      | 3.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 57       | 52.78%  |
| AMD                         | 23       | 21.3%   |
| Samsung Electronics         | 8        | 7.41%   |
| JMicron Technology          | 3        | 2.78%   |
| ASMedia Technology          | 3        | 2.78%   |
| Phison Electronics          | 2        | 1.85%   |
| Nvidia                      | 2        | 1.85%   |
| Kingston Technology Company | 2        | 1.85%   |
| Broadcom / LSI              | 2        | 1.85%   |
| SK hynix                    | 1        | 0.93%   |
| SanDisk                     | 1        | 0.93%   |
| Micron/Crucial Technology   | 1        | 0.93%   |
| Marvell Technology Group    | 1        | 0.93%   |
| LSI Logic / Symbios Logic   | 1        | 0.93%   |
| ADATA Technology            | 1        | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 10%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 5%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 5%      |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 4.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 3.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 3.57%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 2.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 2.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.14%   |
| AMD FCH SATA Controller D                                                               | 3        | 2.14%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.14%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2        | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 1.43%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.43%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.43%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.43%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.43%   |
| SK hynix BC511                                                                          | 1        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.71%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.71%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.71%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.71%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.71%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.71%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.71%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.71%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 0.71%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                    | 1        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 69       | 61.61%  |
| IDE  | 19       | 16.96%  |
| NVMe | 16       | 14.29%  |
| RAID | 6        | 5.36%   |
| SAS  | 1        | 0.89%   |
| SCSI | 1        | 0.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 56       | 69.14%  |
| AMD    | 25       | 30.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 4.88%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 3.66%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 2.44%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 2.44%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 2.44%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 2.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 2.44%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 2.44%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 2.44%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 2        | 2.44%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 2.44%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 2.44%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 1.22%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 1.22%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 1.22%   |
| Intel Xeon CPU 3.40GHz                      | 1        | 1.22%   |
| Intel Pentium Gold G7400                    | 1        | 1.22%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 1.22%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 1.22%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.22%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1        | 1.22%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.22%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.22%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 1.22%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.22%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 1.22%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 1.22%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.22%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.22%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.22%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.22%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1        | 1.22%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 1.22%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.22%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.22%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.22%   |
| Intel Core i3-4340 CPU @ 3.60GHz            | 1        | 1.22%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.22%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 1.22%   |
| Intel Core i3 CPU 560 @ 3.33GHz             | 1        | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 14       | 17.07%  |
| Intel Core i5           | 14       | 17.07%  |
| Intel Xeon              | 6        | 7.32%   |
| AMD Ryzen 5             | 6        | 7.32%   |
| AMD Ryzen 7             | 5        | 6.1%    |
| Intel Core i3           | 4        | 4.88%   |
| AMD Ryzen 3             | 4        | 4.88%   |
| Other                   | 3        | 3.66%   |
| Intel Pentium           | 3        | 3.66%   |
| Intel Core 2 Quad       | 3        | 3.66%   |
| Intel Pentium Dual-Core | 2        | 2.44%   |
| Intel Pentium D         | 2        | 2.44%   |
| Intel Core 2 Duo        | 2        | 2.44%   |
| Intel Celeron           | 2        | 2.44%   |
| AMD FX                  | 2        | 2.44%   |
| AMD Athlon II X2        | 2        | 2.44%   |
| Intel Pentium Gold      | 1        | 1.22%   |
| Intel Core 2            | 1        | 1.22%   |
| AMD Ryzen 9             | 1        | 1.22%   |
| AMD Phenom II X6        | 1        | 1.22%   |
| AMD Phenom II X4        | 1        | 1.22%   |
| AMD G                   | 1        | 1.22%   |
| AMD Athlon              | 1        | 1.22%   |
| AMD A4                  | 1        | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 39       | 47.56%  |
| 2      | 22       | 26.83%  |
| 8      | 10       | 12.2%   |
| 6      | 7        | 8.54%   |
| 16     | 3        | 3.66%   |
| 1      | 1        | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 77       | 95.06%  |
| 2      | 4        | 4.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 42       | 51.22%  |
| 1      | 40       | 48.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 81       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 9        | 10.84%  |
| 0x206a7    | 7        | 8.43%   |
| 0x306c3    | 5        | 6.02%   |
| 0x1067a    | 5        | 6.02%   |
| 0x08108109 | 5        | 6.02%   |
| 0x506e3    | 4        | 4.82%   |
| 0x08701021 | 3        | 3.61%   |
| Unknown    | 3        | 3.61%   |
| 0xa0671    | 2        | 2.41%   |
| 0x906ed    | 2        | 2.41%   |
| 0x906e9    | 2        | 2.41%   |
| 0x90675    | 2        | 2.41%   |
| 0x206d7    | 2        | 2.41%   |
| 0x106e5    | 2        | 2.41%   |
| 0x08101016 | 2        | 2.41%   |
| 0x010000c8 | 2        | 2.41%   |
| 0xf65      | 1        | 1.2%    |
| 0xf47      | 1        | 1.2%    |
| 0xf43      | 1        | 1.2%    |
| 0xa0655    | 1        | 1.2%    |
| 0xa0653    | 1        | 1.2%    |
| 0x906ea    | 1        | 1.2%    |
| 0x906c0    | 1        | 1.2%    |
| 0x806ea    | 1        | 1.2%    |
| 0x6fd      | 1        | 1.2%    |
| 0x6fb      | 1        | 1.2%    |
| 0x6f2      | 1        | 1.2%    |
| 0x206c2    | 1        | 1.2%    |
| 0x20655    | 1        | 1.2%    |
| 0x106a5    | 1        | 1.2%    |
| 0x0a50000b | 1        | 1.2%    |
| 0x0a20120a | 1        | 1.2%    |
| 0x0a201016 | 1        | 1.2%    |
| 0x08701030 | 1        | 1.2%    |
| 0x0810100b | 1        | 1.2%    |
| 0x0800820d | 1        | 1.2%    |
| 0x08001137 | 1        | 1.2%    |
| 0x08001129 | 1        | 1.2%    |
| 0x06001119 | 1        | 1.2%    |
| 0x06000852 | 1        | 1.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 10       | 12.2%   |
| SandyBridge | 9        | 10.98%  |
| Zen+        | 6        | 7.32%   |
| KabyLake    | 6        | 7.32%   |
| Zen         | 5        | 6.1%    |
| Penryn      | 5        | 6.1%    |
| Haswell     | 5        | 6.1%    |
| Skylake     | 4        | 4.88%   |
| K10         | 4        | 4.88%   |
| Unknown     | 4        | 4.88%   |
| Zen 3       | 3        | 3.66%   |
| Zen 2       | 3        | 3.66%   |
| NetBurst    | 3        | 3.66%   |
| Nehalem     | 3        | 3.66%   |
| Core        | 3        | 3.66%   |
| Westmere    | 2        | 2.44%   |
| Piledriver  | 2        | 2.44%   |
| CometLake   | 2        | 2.44%   |
| Tremont     | 1        | 1.22%   |
| Bulldozer   | 1        | 1.22%   |
| Bobcat      | 1        | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 48       | 53.93%  |
| Intel  | 21       | 23.6%   |
| AMD    | 20       | 22.47%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 5.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 5.56%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 4.44%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 4.44%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 4.44%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 4.44%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 3.33%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 2.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.22%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.11%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.11%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.11%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.11%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 1.11%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 1.11%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.11%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.11%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.11%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.11%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.11%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.11%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.11%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 1.11%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.11%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.11%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.11%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 1.11%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 1.11%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.11%   |
| Nvidia G72 [GeForce 7500 LE]                                                | 1        | 1.11%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 1.11%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                      | 1        | 1.11%   |
| Nvidia C78 [GeForce 9100]                                                   | 1        | 1.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.11%   |
| Intel UHD Graphics 620                                                      | 1        | 1.11%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 45       | 54.22%  |
| 1 x Intel      | 17       | 20.48%  |
| 1 x AMD        | 15       | 18.07%  |
| AMD + Nvidia   | 3        | 3.61%   |
| 2 x AMD        | 1        | 1.2%    |
| Intel + Nvidia | 1        | 1.2%    |
| Intel + AMD    | 1        | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 53       | 64.63%  |
| Proprietary | 20       | 24.39%  |
| Unknown     | 9        | 10.98%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 31.33%  |
| 1.01-2.0   | 21       | 25.3%   |
| 0.01-0.5   | 10       | 12.05%  |
| 3.01-4.0   | 9        | 10.84%  |
| 0.51-1.0   | 7        | 8.43%   |
| 5.01-6.0   | 4        | 4.82%   |
| 7.01-8.0   | 3        | 3.61%   |
| 8.01-16.0  | 2        | 2.41%   |
| 2.01-3.0   | 1        | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 13.33%  |
| Goldstar             | 9        | 12%     |
| Hewlett-Packard      | 7        | 9.33%   |
| Acer                 | 7        | 9.33%   |
| Dell                 | 6        | 8%      |
| BenQ                 | 6        | 8%      |
| Philips              | 5        | 6.67%   |
| Unknown              | 4        | 5.33%   |
| AOC                  | 3        | 4%      |
| Ancor Communications | 3        | 4%      |
| Iiyama               | 2        | 2.67%   |
| ___                  | 1        | 1.33%   |
| ViewSonic            | 1        | 1.33%   |
| Sony                 | 1        | 1.33%   |
| SKY                  | 1        | 1.33%   |
| PLN                  | 1        | 1.33%   |
| Medion               | 1        | 1.33%   |
| Lenovo Group Limited | 1        | 1.33%   |
| Lenovo               | 1        | 1.33%   |
| Insignia             | 1        | 1.33%   |
| HannStar             | 1        | 1.33%   |
| AUS                  | 1        | 1.33%   |
| ASUSTek Computer     | 1        | 1.33%   |
| Unknown              | 1        | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 2        | 2.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 2.47%   |
| ___ LCDTV16 ___0101 1360x768                                         | 1        | 1.23%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch             | 1        | 1.23%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                   | 1        | 1.23%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                 | 1        | 1.23%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 1.23%   |
| Unknown LCD Monitor Dell SE2717H/HX 1920x1080                        | 1        | 1.23%   |
| Sony LCD Monitor TV 3840x1080                                        | 1        | 1.23%   |
| SKY TV-monitor SKY1402 3840x2160 708x398mm 32.0-inch                 | 1        | 1.23%   |
| SKY TV SKY1502 3840x2160 1150x650mm 52.0-inch                        | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 520x290mm 23.4-inch | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch | 1        | 1.23%   |
| Samsung Electronics SMFX2490HD SAM074A 1920x1080 530x300mm 24.0-inch | 1        | 1.23%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 1.23%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 1.23%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                   | 1        | 1.23%   |
| Samsung Electronics LCD Monitor S27R65 3840x1080                     | 1        | 1.23%   |
| Samsung Electronics LCD Monitor S27R65                               | 1        | 1.23%   |
| Samsung Electronics LCD Monitor C27F390                              | 1        | 1.23%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch   | 1        | 1.23%   |
| PLN LCD Monitor PXL2790MW 1920x1080                                  | 1        | 1.23%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch            | 1        | 1.23%   |
| Philips LCD Monitor PHL 242V8 1920x1080                              | 1        | 1.23%   |
| Philips 244E PHLC036 1920x1080 521x293mm 23.5-inch                   | 1        | 1.23%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                  | 1        | 1.23%   |
| Lenovo Group Limited LCD Monitor LEN G32qc-10 4480x1440              | 1        | 1.23%   |
| Lenovo C24-20 LEN62A8 1920x1080 527x296mm 23.8-inch                  | 1        | 1.23%   |
| Insignia DX19LD150A11 BBY1943 1360x768 409x230mm 18.5-inch           | 1        | 1.23%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch               | 1        | 1.23%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                 | 1        | 1.23%   |
| Hewlett-Packard w2216 HWP280B 1680x1050 465x291mm 21.6-inch          | 1        | 1.23%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch          | 1        | 1.23%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch         | 1        | 1.23%   |
| Hewlett-Packard E232 HWP327B 1920x1080 509x286mm 23.0-inch           | 1        | 1.23%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch           | 1        | 1.23%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch           | 1        | 1.23%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch            | 1        | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 32       | 45.71%  |
| 1680x1050 (WSXGA+) | 7        | 10%     |
| 3840x2160 (4K)     | 3        | 4.29%   |
| 2560x1440 (QHD)    | 3        | 4.29%   |
| 2560x1080          | 3        | 4.29%   |
| 1600x900 (HD+)     | 3        | 4.29%   |
| 1366x768 (WXGA)    | 3        | 4.29%   |
| Unknown            | 3        | 4.29%   |
| 3840x1080          | 2        | 2.86%   |
| 3440x1440          | 2        | 2.86%   |
| 1440x900 (WXGA+)   | 2        | 2.86%   |
| 1360x768           | 2        | 2.86%   |
| 1280x1024 (SXGA)   | 2        | 2.86%   |
| 4480x1440          | 1        | 1.43%   |
| 1920x1200 (WUXGA)  | 1        | 1.43%   |
| 1024x768 (XGA)     | 1        | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 21.62%  |
| 24      | 10       | 13.51%  |
| 21      | 9        | 12.16%  |
| 27      | 7        | 9.46%   |
| 23      | 6        | 8.11%   |
| 34      | 4        | 5.41%   |
| 22      | 4        | 5.41%   |
| 20      | 3        | 4.05%   |
| 19      | 3        | 4.05%   |
| 18      | 3        | 4.05%   |
| 32      | 2        | 2.7%    |
| 72      | 1        | 1.35%   |
| 52      | 1        | 1.35%   |
| 31      | 1        | 1.35%   |
| 28      | 1        | 1.35%   |
| 25      | 1        | 1.35%   |
| 17      | 1        | 1.35%   |
| 15      | 1        | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 31.88%  |
| 401-500     | 17       | 24.64%  |
| Unknown     | 16       | 23.19%  |
| 701-800     | 6        | 8.7%    |
| 351-400     | 3        | 4.35%   |
| 601-700     | 2        | 2.9%    |
| 301-350     | 1        | 1.45%   |
| 1501-2000   | 1        | 1.45%   |
| 1001-1500   | 1        | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 33       | 50.77%  |
| Unknown | 16       | 24.62%  |
| 16/10   | 8        | 12.31%  |
| 21/9    | 5        | 7.69%   |
| 5/4     | 2        | 3.08%   |
| 4/3     | 1        | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 25       | 34.72%  |
| Unknown        | 16       | 22.22%  |
| 351-500        | 7        | 9.72%   |
| 301-350        | 7        | 9.72%   |
| 151-200        | 6        | 8.33%   |
| 251-300        | 4        | 5.56%   |
| 141-150        | 3        | 4.17%   |
| More than 1000 | 2        | 2.78%   |
| 131-140        | 1        | 1.39%   |
| 101-110        | 1        | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 42       | 60%     |
| Unknown | 16       | 22.86%  |
| 101-120 | 10       | 14.29%  |
| 1-50    | 1        | 1.43%   |
| 121-160 | 1        | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 59       | 71.95%  |
| 2     | 13       | 15.85%  |
| 0     | 8        | 9.76%   |
| 3     | 2        | 2.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 47       | 41.23%  |
| Intel                    | 38       | 33.33%  |
| Qualcomm Atheros         | 7        | 6.14%   |
| Ralink Technology        | 4        | 3.51%   |
| Broadcom                 | 3        | 2.63%   |
| TP-Link                  | 2        | 1.75%   |
| Samsung Electronics      | 2        | 1.75%   |
| Nvidia                   | 2        | 1.75%   |
| Huawei Technologies      | 2        | 1.75%   |
| Ralink                   | 1        | 0.88%   |
| Qualcomm                 | 1        | 0.88%   |
| NetGear                  | 1        | 0.88%   |
| Mercucys                 | 1        | 0.88%   |
| Marvell Technology Group | 1        | 0.88%   |
| HTC (High Tech Computer) | 1        | 0.88%   |
| Belkin Components        | 1        | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 37       | 28.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 7        | 5.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 3.03%   |
| Intel I211 Gigabit Network Connection                                                         | 4        | 3.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 2.27%   |
| Intel Ethernet Connection (7) I219-V                                                          | 3        | 2.27%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 1.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 1.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2        | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2        | 1.52%   |
| Intel Wireless-AC 9260                                                                        | 2        | 1.52%   |
| Intel Wireless 3165                                                                           | 2        | 1.52%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 1.52%   |
| Intel Ethernet Connection I217-V                                                              | 2        | 1.52%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2        | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 1.52%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 1.52%   |
| Intel 82574L Gigabit Network Connection                                                       | 2        | 1.52%   |
| Intel 82573L Gigabit Ethernet Controller                                                      | 2        | 1.52%   |
| Huawei ELS-NX9                                                                                | 2        | 1.52%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.76%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.76%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 0.76%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 0.76%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 0.76%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.76%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.76%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 0.76%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 0.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 1        | 0.76%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]                | 1        | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 35%     |
| Intel                 | 12       | 30%     |
| Ralink Technology     | 4        | 10%     |
| Qualcomm Atheros      | 3        | 7.5%    |
| TP-Link               | 2        | 5%      |
| Ralink                | 1        | 2.5%    |
| NetGear               | 1        | 2.5%    |
| Mercucys              | 1        | 2.5%    |
| Broadcom              | 1        | 2.5%    |
| Belkin Components     | 1        | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 9.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 7.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 4.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 4.88%   |
| Intel Wireless-AC 9260                                                                        | 2        | 4.88%   |
| Intel Wireless 3165                                                                           | 2        | 4.88%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 4.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 4.88%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 2.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.44%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 2.44%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 2.44%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 2.44%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.44%   |
| Realtek 802.11ac NIC                                                                          | 1        | 2.44%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 2.44%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 2.44%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]                | 1        | 2.44%   |
| NetGear A6150                                                                                 | 1        | 2.44%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 2.44%   |
| Intel Wireless 7265                                                                           | 1        | 2.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1        | 2.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 2.44%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1        | 2.44%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1        | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 42       | 47.73%  |
| Intel                    | 31       | 35.23%  |
| Qualcomm Atheros         | 4        | 4.55%   |
| Samsung Electronics      | 2        | 2.27%   |
| Nvidia                   | 2        | 2.27%   |
| Huawei Technologies      | 2        | 2.27%   |
| Broadcom                 | 2        | 2.27%   |
| Qualcomm                 | 1        | 1.14%   |
| Marvell Technology Group | 1        | 1.14%   |
| HTC (High Tech Computer) | 1        | 1.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37       | 40.66%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 7.69%   |
| Intel I211 Gigabit Network Connection                             | 4        | 4.4%    |
| Intel Ethernet Connection (7) I219-V                              | 3        | 3.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 2.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.2%    |
| Intel Ethernet Connection I217-V                                  | 2        | 2.2%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.2%    |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.2%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.2%    |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 2.2%    |
| Huawei ELS-NX9                                                    | 2        | 2.2%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.1%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.1%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.1%    |
| Qualcomm Android                                                  | 1        | 1.1%    |
| Nvidia MCP77 Ethernet                                             | 1        | 1.1%    |
| Nvidia MCP61 Ethernet                                             | 1        | 1.1%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.1%    |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.1%    |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 1.1%    |
| Intel Ethernet Controller I225-V                                  | 1        | 1.1%    |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.1%    |
| Intel Ethernet Connection (17) I219-V                             | 1        | 1.1%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.1%    |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.1%    |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.1%    |
| Intel 82545GM Gigabit Ethernet Controller                         | 1        | 1.1%    |
| HTC (High Tech Computer) Desire HD (modem mode)                   | 1        | 1.1%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.1%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 80       | 68.38%  |
| WiFi     | 37       | 31.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 66       | 78.57%  |
| WiFi     | 18       | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 67.9%   |
| 2     | 25       | 30.86%  |
| 0     | 1        | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 61       | 73.49%  |
| Yes  | 22       | 26.51%  |

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
| Intel Bluetooth Device                              | 1        | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.35%   |
| Intel AX210 Bluetooth                               | 1        | 4.35%   |
| Dell BT Mini-Receiver                               | 1        | 4.35%   |
| Broadcom BCM92045B3 ROM                             | 1        | 4.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 54       | 40.3%   |
| Nvidia                   | 43       | 32.09%  |
| AMD                      | 28       | 20.9%   |
| C-Media Electronics      | 3        | 2.24%   |
| JMTek                    | 2        | 1.49%   |
| Native Instruments       | 1        | 0.75%   |
| Micro Star International | 1        | 0.75%   |
| Logitech                 | 1        | 0.75%   |
| GN Netcom                | 1        | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 5.92%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 5.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 5.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 4.61%   |
| Nvidia High Definition Audio Controller                                    | 5        | 3.29%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 3.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 3.29%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 3.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 3.29%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 2.63%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 2.63%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.32%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.32%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.32%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 1.32%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.32%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.32%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.66%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1        | 0.66%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.66%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.66%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.66%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.66%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.66%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 19.23%  |
| Unknown             | 4        | 15.38%  |
| Corsair             | 3        | 11.54%  |
| Micron Technology   | 2        | 7.69%   |
| G.Skill             | 2        | 7.69%   |
| Crucial             | 2        | 7.69%   |
| Smart               | 1        | 3.85%   |
| SK hynix            | 1        | 3.85%   |
| Nanya Technology    | 1        | 3.85%   |
| Kingston            | 1        | 3.85%   |
| Elpida              | 1        | 3.85%   |
| AVEXIR              | 1        | 3.85%   |
| A-DATA Technology   | 1        | 3.85%   |
| Unknown             | 1        | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 3.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 3.57%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 1        | 3.57%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1        | 3.57%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                | 1        | 3.57%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s   | 1        | 3.57%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s    | 1        | 3.57%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 3.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 3.57%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s   | 1        | 3.57%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Samsung RAM M393B1G70BH0-YK0 8GB DIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s    | 1        | 3.57%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s       | 1        | 3.57%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s     | 1        | 3.57%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s    | 1        | 3.57%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 3.57%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 1        | 3.57%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s   | 1        | 3.57%   |
| Elpida RAM EBE21UE8AFFA-8G-F 2GB DIMM DDR2 800MT/s      | 1        | 3.57%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s   | 1        | 3.57%   |
| Crucial RAM CT16G4DFD8266.M16FE 16GB DIMM DDR4 2667MT/s | 1        | 3.57%   |
| Corsair RAM VS2GB1333D4 2GB DIMM DDR3 1600MT/s          | 1        | 3.57%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 1        | 3.57%   |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s  | 1        | 3.57%   |
| AVEXIR RAM DDR4-3000 CL16 8GB 8GB DIMM DDR4 2133MT/s    | 1        | 3.57%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s             | 1        | 3.57%   |
| Unknown                                                 | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 11       | 45.83%  |
| DDR3    | 7        | 29.17%  |
| DDR2    | 3        | 12.5%   |
| Unknown | 2        | 8.33%   |
| SDRAM   | 1        | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 22       | 91.67%  |
| SODIMM | 2        | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 32%     |
| 16384 | 6        | 24%     |
| 4096  | 5        | 20%     |
| 2048  | 3        | 12%     |
| 1024  | 2        | 8%      |
| 32768 | 1        | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 6        | 24%     |
| 3600  | 2        | 8%      |
| 3200  | 2        | 8%      |
| 2667  | 2        | 8%      |
| 1333  | 2        | 8%      |
| 667   | 2        | 8%      |
| 3733  | 1        | 4%      |
| 3400  | 1        | 4%      |
| 2666  | 1        | 4%      |
| 2400  | 1        | 4%      |
| 2133  | 1        | 4%      |
| 1866  | 1        | 4%      |
| 1334  | 1        | 4%      |
| 800   | 1        | 4%      |
| 533   | 1        | 4%      |

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
| Logitech                      | 5        | 31.25%  |
| Sunplus Innovation Technology | 2        | 12.5%   |
| Creative Technology           | 2        | 12.5%   |
| Z-Star Microelectronics       | 1        | 6.25%   |
| Pixart Imaging                | 1        | 6.25%   |
| OmniVision Technologies       | 1        | 6.25%   |
| MacroSilicon                  | 1        | 6.25%   |
| Huawei Technologies           | 1        | 6.25%   |
| ARC International             | 1        | 6.25%   |
| Alcor Micro                   | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera                     | 1        | 6.25%   |
| Sunplus FHD Camera Microphone                  | 1        | 6.25%   |
| Sunplus AAPDQT-0622-W                          | 1        | 6.25%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 1        | 6.25%   |
| OmniVision Integrated Webcam for Dell XPS 2010 | 1        | 6.25%   |
| MacroSilicon USB Video                         | 1        | 6.25%   |
| Logitech Webcam C925e                          | 1        | 6.25%   |
| Logitech Webcam C270                           | 1        | 6.25%   |
| Logitech Webcam C210                           | 1        | 6.25%   |
| Logitech Webcam B500                           | 1        | 6.25%   |
| Logitech Logi Webcam C920e                     | 1        | 6.25%   |
| Huawei UVC Camera                              | 1        | 6.25%   |
| Creative VF0610 Live! Cam Socialize HD         | 1        | 6.25%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 6.25%   |
| ARC International Camera                       | 1        | 6.25%   |
| Alcor Micro USB 2.0 PC Camera                  | 1        | 6.25%   |

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
| 0     | 59       | 71.08%  |
| 1     | 23       | 27.71%  |
| 2     | 1        | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 13       | 50%     |
| Net/wireless             | 8        | 30.77%  |
| Unassigned class         | 1        | 3.85%   |
| Storage/raid             | 1        | 3.85%   |
| Multimedia controller    | 1        | 3.85%   |
| Communication controller | 1        | 3.85%   |
| Camera                   | 1        | 3.85%   |

