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

Total: 357

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| LMDE 4 | 148      | 61.92%  |
| LMDE 5 | 81       | 33.89%  |
| LMDE 3 | 8        | 3.35%   |
| LMDE 2 | 2        | 0.84%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LMDE | 236      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 4.19.0-16-amd64          | 23       | 8.68%   |
| 4.19.0-17-amd64          | 20       | 7.55%   |
| 4.19.0-18-amd64          | 19       | 7.17%   |
| 4.19.0-14-amd64          | 18       | 6.79%   |
| 4.19.0-13-amd64          | 17       | 6.42%   |
| 5.10.0-12-amd64          | 15       | 5.66%   |
| 4.19.0-8-amd64           | 15       | 5.66%   |
| 5.10.0-20-amd64          | 12       | 4.53%   |
| 5.10.0-17-amd64          | 11       | 4.15%   |
| 5.10.0-14-amd64          | 10       | 3.77%   |
| 5.10.0-13-amd64          | 10       | 3.77%   |
| 5.10.0-18-amd64          | 9        | 3.4%    |
| 4.19.0-12-amd64          | 9        | 3.4%    |
| 5.10.0-19-amd64          | 8        | 3.02%   |
| 4.19.0-10-amd64          | 8        | 3.02%   |
| 4.19.0-9-amd64           | 7        | 2.64%   |
| 5.10.0-21-amd64          | 5        | 1.89%   |
| 4.9.0-8-amd64            | 4        | 1.51%   |
| 4.19.0-11-amd64          | 4        | 1.51%   |
| 5.10.0-15-amd64          | 3        | 1.13%   |
| 4.19.0-17-686            | 3        | 1.13%   |
| 4.19.0-16-686            | 3        | 1.13%   |
| 4.19.0-14-686            | 3        | 1.13%   |
| 5.10.0-16-amd64          | 2        | 0.75%   |
| 4.19.0-8-686             | 2        | 0.75%   |
| 4.19.0-20-amd64          | 2        | 0.75%   |
| 4.19.0-19-686            | 2        | 0.75%   |
| 4.19.0-18-686            | 2        | 0.75%   |
| 4.19.0-13-686            | 2        | 0.75%   |
| 3.16.0-4-amd64           | 2        | 0.75%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1        | 0.38%   |
| 5.8.0-3-amd64            | 1        | 0.38%   |
| 5.6.0-0.bpo.2-amd64      | 1        | 0.38%   |
| 5.4.0-0.bpo.4-amd64      | 1        | 0.38%   |
| 5.19.0-0.deb11.2-amd64   | 1        | 0.38%   |
| 5.10.0-7-amd64           | 1        | 0.38%   |
| 5.10.0-13-686            | 1        | 0.38%   |
| 4.9.0-9-amd64            | 1        | 0.38%   |
| 4.9.0-17-amd64           | 1        | 0.38%   |
| 4.9.0-11-amd64           | 1        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 144      | 60.25%  |
| 5.10.0  | 80       | 33.47%  |
| 4.9.0   | 7        | 2.93%   |
| 3.16.0  | 2        | 0.84%   |
| 6.0.2   | 1        | 0.42%   |
| 5.8.0   | 1        | 0.42%   |
| 5.6.0   | 1        | 0.42%   |
| 5.4.0   | 1        | 0.42%   |
| 5.19.0  | 1        | 0.42%   |
| 4.17.0  | 1        | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 144      | 60.25%  |
| 5.10    | 80       | 33.47%  |
| 4.9     | 7        | 2.93%   |
| 3.16    | 2        | 0.84%   |
| 6.0     | 1        | 0.42%   |
| 5.8     | 1        | 0.42%   |
| 5.6     | 1        | 0.42%   |
| 5.4     | 1        | 0.42%   |
| 5.19    | 1        | 0.42%   |
| 4.17    | 1        | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 216      | 91.53%  |
| i686   | 20       | 8.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 204      | 86.08%  |
| Cinnamon   | 18       | 7.59%   |
| MATE       | 5        | 2.11%   |
| Unknown    | 3        | 1.27%   |
| XFCE       | 2        | 0.84%   |
| GNOME      | 2        | 0.84%   |
| LXQt       | 1        | 0.42%   |
| LXDE       | 1        | 0.42%   |
| KDE5       | 1        | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 236      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 188      | 79.66%  |
| LightDM | 28       | 11.86%  |
| TDM     | 15       | 6.36%   |
| MDM     | 2        | 0.85%   |
| GDM     | 2        | 0.85%   |
| SDDM    | 1        | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 65       | 27.54%  |
| de_DE   | 29       | 12.29%  |
| pt_BR   | 22       | 9.32%   |
| fr_FR   | 16       | 6.78%   |
| ru_RU   | 12       | 5.08%   |
| pl_PL   | 9        | 3.81%   |
| Unknown | 9        | 3.81%   |
| en_GB   | 8        | 3.39%   |
| it_IT   | 7        | 2.97%   |
| en_CA   | 7        | 2.97%   |
| sv_SE   | 5        | 2.12%   |
| es_ES   | 4        | 1.69%   |
| en_AU   | 4        | 1.69%   |
| nl_BE   | 3        | 1.27%   |
| es_AR   | 3        | 1.27%   |
| cs_CZ   | 3        | 1.27%   |
| sk_SK   | 2        | 0.85%   |
| pt_PT   | 2        | 0.85%   |
| hu_HU   | 2        | 0.85%   |
| fr_CA   | 2        | 0.85%   |
| en_ZA   | 2        | 0.85%   |
| de_AT   | 2        | 0.85%   |
| ar_EG   | 2        | 0.85%   |
| unm_US  | 1        | 0.42%   |
| uk_UA   | 1        | 0.42%   |
| tr_TR   | 1        | 0.42%   |
| nb_NO   | 1        | 0.42%   |
| it_CH   | 1        | 0.42%   |
| fi_FI   | 1        | 0.42%   |
| et_EE   | 1        | 0.42%   |
| es_UY   | 1        | 0.42%   |
| es_NI   | 1        | 0.42%   |
| es_MX   | 1        | 0.42%   |
| es_EC   | 1        | 0.42%   |
| es_CO   | 1        | 0.42%   |
| es_CL   | 1        | 0.42%   |
| el_GR   | 1        | 0.42%   |
| ca_ES   | 1        | 0.42%   |
| bg_BG   | 1        | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 163      | 68.78%  |
| EFI  | 74       | 31.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 220      | 92.83%  |
| Btrfs   | 7        | 2.95%   |
| Unknown | 5        | 2.11%   |
| Tmpfs   | 3        | 1.27%   |
| Overlay | 1        | 0.42%   |
| Ext3    | 1        | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 188      | 78.99%  |
| GPT     | 28       | 11.76%  |
| MBR     | 22       | 9.24%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 221      | 92.86%  |
| Yes       | 17       | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 213      | 90.25%  |
| Yes       | 23       | 9.75%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 55       | 23.31%  |
| Gigabyte Technology | 34       | 14.41%  |
| MSI                 | 28       | 11.86%  |
| Dell                | 25       | 10.59%  |
| Hewlett-Packard     | 16       | 6.78%   |
| ASRock              | 16       | 6.78%   |
| Intel               | 10       | 4.24%   |
| Acer                | 9        | 3.81%   |
| Lenovo              | 5        | 2.12%   |
| Unknown             | 5        | 2.12%   |
| ECS                 | 4        | 1.69%   |
| Pegatron            | 3        | 1.27%   |
| Foxconn             | 3        | 1.27%   |
| OEM                 | 2        | 0.85%   |
| Fujitsu             | 2        | 0.85%   |
| EVGA                | 2        | 0.85%   |
| eMachines           | 2        | 0.85%   |
| Biostar             | 2        | 0.85%   |
| SiYW                | 1        | 0.42%   |
| Semp Toshiba        | 1        | 0.42%   |
| Samsung Electronics | 1        | 0.42%   |
| Positivo            | 1        | 0.42%   |
| PCWare              | 1        | 0.42%   |
| NEC Computers       | 1        | 0.42%   |
| Gateway             | 1        | 0.42%   |
| Fujitsu Siemens     | 1        | 0.42%   |
| Digiboard           | 1        | 0.42%   |
| DFI                 | 1        | 0.42%   |
| AZW                 | 1        | 0.42%   |
| Alienware           | 1        | 0.42%   |
| ADVANSUS            | 1        | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 6        | 2.54%   |
| Dell OptiPlex 780               | 3        | 1.27%   |
| ASUS All Series                 | 3        | 1.27%   |
| MSI MS-7C52                     | 2        | 0.85%   |
| HP Pavilion Desktop 590-p0xxx   | 2        | 0.85%   |
| Gigabyte X570 AORUS ULTRA       | 2        | 0.85%   |
| Gigabyte B450M DS3H             | 2        | 0.85%   |
| Dell OptiPlex 3010              | 2        | 0.85%   |
| ASUS PRIME B350M-A              | 2        | 0.85%   |
| ASRock A320M-HDV R4.0           | 2        | 0.85%   |
| SiYW V200 Series                | 1        | 0.42%   |
| Semp Toshiba STI                | 1        | 0.42%   |
| Samsung DeskTop System          | 1        | 0.42%   |
| Positivo POS-EIH61CE            | 1        | 0.42%   |
| Pegatron Pro 3015 Microtower PC | 1        | 0.42%   |
| Pegatron Elite 7300 Series MT   | 1        | 0.42%   |
| Pegatron 520-1188la             | 1        | 0.42%   |
| PCWare IPMH81G1                 | 1        | 0.42%   |
| OEM 45CMX/45GMX/45CMX-K         | 1        | 0.42%   |
| NEC Computers IMEDIA S9509      | 1        | 0.42%   |
| MSI PX714AA-ABH t3040.nl        | 1        | 0.42%   |
| MSI MS-7D54                     | 1        | 0.42%   |
| MSI MS-7C51                     | 1        | 0.42%   |
| MSI MS-7B79                     | 1        | 0.42%   |
| MSI MS-7B23                     | 1        | 0.42%   |
| MSI MS-7B17                     | 1        | 0.42%   |
| MSI MS-7A40                     | 1        | 0.42%   |
| MSI MS-7A38                     | 1        | 0.42%   |
| MSI MS-7984                     | 1        | 0.42%   |
| MSI MS-7977                     | 1        | 0.42%   |
| MSI MS-7974                     | 1        | 0.42%   |
| MSI MS-7918                     | 1        | 0.42%   |
| MSI MS-7851                     | 1        | 0.42%   |
| MSI MS-7850                     | 1        | 0.42%   |
| MSI MS-7823                     | 1        | 0.42%   |
| MSI MS-7817                     | 1        | 0.42%   |
| MSI MS-7815                     | 1        | 0.42%   |
| MSI MS-7751                     | 1        | 0.42%   |
| MSI MS-7721                     | 1        | 0.42%   |
| MSI MS-7383                     | 1        | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 12       | 5.08%   |
| ASUS PRIME             | 9        | 3.81%   |
| HP Compaq              | 6        | 2.54%   |
| Acer Aspire            | 6        | 2.54%   |
| Unknown                | 6        | 2.54%   |
| Dell Precision         | 5        | 2.12%   |
| Gigabyte X570          | 4        | 1.69%   |
| Dell Inspiron          | 4        | 1.69%   |
| ASUS ROG               | 4        | 1.69%   |
| Lenovo ThinkCentre     | 3        | 1.27%   |
| ASUS All               | 3        | 1.27%   |
| Acer Veriton           | 3        | 1.27%   |
| MSI MS-7C52            | 2        | 0.85%   |
| HP Pavilion            | 2        | 0.85%   |
| Gigabyte Z390          | 2        | 0.85%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.85%   |
| Gigabyte B450M         | 2        | 0.85%   |
| Gigabyte B450          | 2        | 0.85%   |
| Foxconn 945            | 2        | 0.85%   |
| Dell Vostro            | 2        | 0.85%   |
| ASUS P5KPL-AM          | 2        | 0.85%   |
| ASRock A320M-HDV       | 2        | 0.85%   |
| SiYW V200              | 1        | 0.42%   |
| Semp Toshiba STI       | 1        | 0.42%   |
| Samsung DeskTop        | 1        | 0.42%   |
| Positivo POS-EIH61CE   | 1        | 0.42%   |
| Pegatron Pro           | 1        | 0.42%   |
| Pegatron Elite         | 1        | 0.42%   |
| Pegatron 520-1188la    | 1        | 0.42%   |
| PCWare IPMH81G1        | 1        | 0.42%   |
| OEM 45CMX              | 1        | 0.42%   |
| NEC Computers IMEDIA   | 1        | 0.42%   |
| MSI PX714AA-ABH        | 1        | 0.42%   |
| MSI MS-7D54            | 1        | 0.42%   |
| MSI MS-7C51            | 1        | 0.42%   |
| MSI MS-7B79            | 1        | 0.42%   |
| MSI MS-7B23            | 1        | 0.42%   |
| MSI MS-7B17            | 1        | 0.42%   |
| MSI MS-7A40            | 1        | 0.42%   |
| MSI MS-7A38            | 1        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 30       | 12.71%  |
| 2009 | 23       | 9.75%   |
| 2018 | 21       | 8.9%    |
| 2019 | 16       | 6.78%   |
| 2011 | 16       | 6.78%   |
| 2010 | 16       | 6.78%   |
| 2007 | 16       | 6.78%   |
| 2014 | 15       | 6.36%   |
| 2013 | 13       | 5.51%   |
| 2008 | 12       | 5.08%   |
| 2006 | 11       | 4.66%   |
| 2017 | 10       | 4.24%   |
| 2015 | 8        | 3.39%   |
| 2021 | 7        | 2.97%   |
| 2020 | 6        | 2.54%   |
| 2016 | 5        | 2.12%   |
| 2003 | 4        | 1.69%   |
| 2022 | 3        | 1.27%   |
| 2005 | 3        | 1.27%   |
| 2004 | 1        | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 236      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 235      | 98.74%  |
| Enabled  | 3        | 1.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 236      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 62       | 25.83%  |
| 3.01-4.0    | 46       | 19.17%  |
| 16.01-24.0  | 44       | 18.33%  |
| 4.01-8.0    | 32       | 13.33%  |
| 32.01-64.0  | 24       | 10%     |
| 2.01-3.0    | 11       | 4.58%   |
| 1.01-2.0    | 10       | 4.17%   |
| 0.51-1.0    | 5        | 2.08%   |
| 24.01-32.0  | 3        | 1.25%   |
| 64.01-256.0 | 3        | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 109      | 43.25%  |
| 2.01-3.0   | 60       | 23.81%  |
| 3.01-4.0   | 32       | 12.7%   |
| 0.51-1.0   | 26       | 10.32%  |
| 4.01-8.0   | 22       | 8.73%   |
| 8.01-16.0  | 2        | 0.79%   |
| 32.01-64.0 | 1        | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 110      | 45.08%  |
| 2      | 73       | 29.92%  |
| 3      | 29       | 11.89%  |
| 4      | 17       | 6.97%   |
| 5      | 6        | 2.46%   |
| 7      | 4        | 1.64%   |
| 6      | 4        | 1.64%   |
| 8      | 1        | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 133      | 55.19%  |
| No        | 108      | 44.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 235      | 99.58%  |
| No        | 1        | 0.42%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 60.74%  |
| Yes       | 95       | 39.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 188      | 78.99%  |
| Yes       | 50       | 21.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 36       | 15.25%  |
| Germany      | 32       | 13.56%  |
| Brazil       | 24       | 10.17%  |
| Russia       | 16       | 6.78%   |
| France       | 16       | 6.78%   |
| Canada       | 11       | 4.66%   |
| Italy        | 10       | 4.24%   |
| Poland       | 7        | 2.97%   |
| UK           | 6        | 2.54%   |
| Spain        | 6        | 2.54%   |
| Netherlands  | 6        | 2.54%   |
| Ukraine      | 5        | 2.12%   |
| Sweden       | 5        | 2.12%   |
| Australia    | 5        | 2.12%   |
| Bulgaria     | 3        | 1.27%   |
| Belgium      | 3        | 1.27%   |
| Austria      | 3        | 1.27%   |
| Argentina    | 3        | 1.27%   |
| Turkey       | 2        | 0.85%   |
| South Africa | 2        | 0.85%   |
| Slovakia     | 2        | 0.85%   |
| Puerto Rico  | 2        | 0.85%   |
| Portugal     | 2        | 0.85%   |
| Mexico       | 2        | 0.85%   |
| Hungary      | 2        | 0.85%   |
| Greece       | 2        | 0.85%   |
| Finland      | 2        | 0.85%   |
| Czechia      | 2        | 0.85%   |
| Venezuela    | 1        | 0.42%   |
| Uruguay      | 1        | 0.42%   |
| Serbia       | 1        | 0.42%   |
| Romania      | 1        | 0.42%   |
| Philippines  | 1        | 0.42%   |
| Pakistan     | 1        | 0.42%   |
| Norway       | 1        | 0.42%   |
| Nicaragua    | 1        | 0.42%   |
| Luxembourg   | 1        | 0.42%   |
| Latvia       | 1        | 0.42%   |
| India        | 1        | 0.42%   |
| Estonia      | 1        | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Hamburg               | 4        | 1.59%   |
| Paris                 | 3        | 1.19%   |
| Melbourne             | 3        | 1.19%   |
| Frankfurt am Main     | 3        | 1.19%   |
| Berlin                | 3        | 1.19%   |
| Warsaw                | 2        | 0.79%   |
| Sofia                 | 2        | 0.79%   |
| San Antonio           | 2        | 0.79%   |
| Rio de Janeiro        | 2        | 0.79%   |
| Perth                 | 2        | 0.79%   |
| Nitra                 | 2        | 0.79%   |
| Moscow                | 2        | 0.79%   |
| Montreal              | 2        | 0.79%   |
| Milan                 | 2        | 0.79%   |
| Marseille             | 2        | 0.79%   |
| Helsinki              | 2        | 0.79%   |
| Gothenburg            | 2        | 0.79%   |
| Florianópolis        | 2        | 0.79%   |
| Belo Horizonte        | 2        | 0.79%   |
| Bayamón              | 2        | 0.79%   |
| Athens                | 2        | 0.79%   |
| Amsterdam             | 2        | 0.79%   |
| Zaporozhe             | 1        | 0.4%    |
| Zaandam               | 1        | 0.4%    |
| Wroclaw               | 1        | 0.4%    |
| Wijchen               | 1        | 0.4%    |
| Weiden                | 1        | 0.4%    |
| Washington            | 1        | 0.4%    |
| Warmsen               | 1        | 0.4%    |
| Voronezh              | 1        | 0.4%    |
| Volta Redonda         | 1        | 0.4%    |
| Vitória da Conquista | 1        | 0.4%    |
| Vincennes             | 1        | 0.4%    |
| Vienna                | 1        | 0.4%    |
| Victoria              | 1        | 0.4%    |
| Vicente Guerrero      | 1        | 0.4%    |
| Varese                | 1        | 0.4%    |
| Valencia              | 1        | 0.4%    |
| Ulyanovsk             | 1        | 0.4%    |
| Ukhta                 | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 90       | 153    | 22.96%  |
| Seagate             | 67       | 108    | 17.09%  |
| Samsung Electronics | 60       | 100    | 15.31%  |
| Kingston            | 24       | 30     | 6.12%   |
| Toshiba             | 19       | 25     | 4.85%   |
| Hitachi             | 17       | 21     | 4.34%   |
| Crucial             | 16       | 20     | 4.08%   |
| SanDisk             | 15       | 18     | 3.83%   |
| A-DATA Technology   | 9        | 9      | 2.3%    |
| Phison              | 7        | 8      | 1.79%   |
| Intel               | 6        | 6      | 1.53%   |
| China               | 5        | 5      | 1.28%   |
| Intenso             | 4        | 5      | 1.02%   |
| SK hynix            | 3        | 4      | 0.77%   |
| OCZ                 | 3        | 5      | 0.77%   |
| Micron Technology   | 3        | 3      | 0.77%   |
| Maxtor              | 3        | 5      | 0.77%   |
| Unknown             | 2        | 3      | 0.51%   |
| Transcend           | 2        | 3      | 0.51%   |
| TCSUNBOW            | 2        | 2      | 0.51%   |
| Gigabyte Technology | 2        | 3      | 0.51%   |
| CT500MX5            | 2        | 2      | 0.51%   |
| XrayDisk            | 1        | 2      | 0.26%   |
| WALRAM              | 1        | 1      | 0.26%   |
| TGT                 | 1        | 1      | 0.26%   |
| Team                | 1        | 2      | 0.26%   |
| TakeMS              | 1        | 1      | 0.26%   |
| SPCC                | 1        | 1      | 0.26%   |
| Smartbuy            | 1        | 1      | 0.26%   |
| Silicon Motion      | 1        | 1      | 0.26%   |
| SABRENT             | 1        | 1      | 0.26%   |
| Plextor             | 1        | 2      | 0.26%   |
| Phison Electronics  | 1        | 1      | 0.26%   |
| Patriot             | 1        | 1      | 0.26%   |
| OCZ-VERTEX          | 1        | 1      | 0.26%   |
| Netac               | 1        | 1      | 0.26%   |
| Mushkin             | 1        | 1      | 0.26%   |
| KingSpec            | 1        | 1      | 0.26%   |
| Kingmax             | 1        | 1      | 0.26%   |
| KESU                | 1        | 2      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB        | 8        | 1.74%   |
| Seagate ST1000DM010-2EP102 1TB   | 5        | 1.08%   |
| Samsung SSD 850 EVO 500GB        | 5        | 1.08%   |
| Kingston SA400S37240G 240GB SSD  | 5        | 1.08%   |
| Kingston SA400S37120G 120GB SSD  | 5        | 1.08%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 0.87%   |
| Toshiba DT01ACA100 1TB           | 4        | 0.87%   |
| Samsung SSD 860 EVO 500GB        | 4        | 0.87%   |
| Kingston SA400S37480G 480GB SSD  | 4        | 0.87%   |
| Toshiba HDWD110 1TB              | 3        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 0.65%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 0.65%   |
| Samsung NVMe SSD Drive 500GB     | 3        | 0.65%   |
| Samsung HD322HJ 320GB            | 3        | 0.65%   |
| Samsung HD161HJ 160GB            | 3        | 0.65%   |
| Samsung HD103SJ 1TB              | 3        | 0.65%   |
| Crucial CT480BX500SSD1 480GB     | 3        | 0.65%   |
| Crucial CT240BX500SSD1 240GB     | 3        | 0.65%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 0.43%   |
| WDC WD5000AAKX-00U6AA0 500GB     | 2        | 0.43%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 2        | 0.43%   |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 0.43%   |
| WDC WD3200AAKS-00L9A0 320GB      | 2        | 0.43%   |
| WDC WD2500AAKX-753CA1 250GB      | 2        | 0.43%   |
| WDC WD1600AABS-00PRA0 160GB      | 2        | 0.43%   |
| WDC WD10EZEX-60WN4A0 1TB         | 2        | 0.43%   |
| WDC WD10EARS-00Y5B1 1TB          | 2        | 0.43%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 2        | 0.43%   |
| Unknown SD/MMC/MS PRO 2GB        | 2        | 0.43%   |
| Toshiba DT01ACA200 2TB           | 2        | 0.43%   |
| Seagate ST500LT012-1DG142 500GB  | 2        | 0.43%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 0.43%   |
| Seagate ST3500418AS 500GB        | 2        | 0.43%   |
| Seagate ST3320418AS 320GB        | 2        | 0.43%   |
| Seagate ST3250318AS 249GB        | 2        | 0.43%   |
| Seagate ST3160021A 160GB         | 2        | 0.43%   |
| Seagate ST31000528AS 1TB         | 2        | 0.43%   |
| Seagate ST2000LX001-1RG174 2TB   | 2        | 0.43%   |
| Seagate ST2000DM001-9YN164 2TB   | 2        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 82       | 142    | 37.27%  |
| Seagate             | 67       | 107    | 30.45%  |
| Samsung Electronics | 27       | 36     | 12.27%  |
| Hitachi             | 17       | 21     | 7.73%   |
| Toshiba             | 15       | 17     | 6.82%   |
| Maxtor              | 3        | 5      | 1.36%   |
| Unknown             | 2        | 2      | 0.91%   |
| SABRENT             | 1        | 1      | 0.45%   |
| KESU                | 1        | 2      | 0.45%   |
| Intenso             | 1        | 1      | 0.45%   |
| HPE                 | 1        | 4      | 0.45%   |
| Fujitsu             | 1        | 1      | 0.45%   |
| ExcelStor           | 1        | 1      | 0.45%   |
| ASMedia             | 1        | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 26       | 38     | 18.18%  |
| Kingston            | 21       | 27     | 14.69%  |
| Crucial             | 15       | 19     | 10.49%  |
| SanDisk             | 14       | 17     | 9.79%   |
| A-DATA Technology   | 9        | 9      | 6.29%   |
| WDC                 | 8        | 9      | 5.59%   |
| China               | 5        | 5      | 3.5%    |
| Toshiba             | 4        | 8      | 2.8%    |
| Intel               | 4        | 4      | 2.8%    |
| OCZ                 | 3        | 5      | 2.1%    |
| Micron Technology   | 3        | 3      | 2.1%    |
| Intenso             | 3        | 4      | 2.1%    |
| Transcend           | 2        | 3      | 1.4%    |
| TCSUNBOW            | 2        | 2      | 1.4%    |
| SK hynix            | 2        | 2      | 1.4%    |
| Gigabyte Technology | 2        | 3      | 1.4%    |
| CT500MX5            | 2        | 2      | 1.4%    |
| Unknown             | 1        | 1      | 0.7%    |
| Team                | 1        | 2      | 0.7%    |
| TakeMS              | 1        | 1      | 0.7%    |
| SPCC                | 1        | 1      | 0.7%    |
| Smartbuy            | 1        | 1      | 0.7%    |
| Plextor             | 1        | 2      | 0.7%    |
| Patriot             | 1        | 1      | 0.7%    |
| OCZ-VERTEX          | 1        | 1      | 0.7%    |
| Netac               | 1        | 1      | 0.7%    |
| KingSpec            | 1        | 1      | 0.7%    |
| Kingmax             | 1        | 1      | 0.7%    |
| Hewlett-Packard     | 1        | 1      | 0.7%    |
| GOODRAM             | 1        | 1      | 0.7%    |
| Dogfish             | 1        | 1      | 0.7%    |
| Apple               | 1        | 1      | 0.7%    |
| Apacer              | 1        | 1      | 0.7%    |
| 2.5''               | 1        | 1      | 0.7%    |
| Unknown             | 1        | 2      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 175      | 341    | 52.87%  |
| SSD     | 119      | 181    | 35.95%  |
| NVMe    | 32       | 49     | 9.67%   |
| Unknown | 5        | 6      | 1.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 225      | 500    | 82.12%  |
| NVMe | 32       | 49     | 11.68%  |
| SAS  | 17       | 28     | 6.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 185      | 341    | 60.46%  |
| 0.51-1.0   | 74       | 108    | 24.18%  |
| 1.01-2.0   | 27       | 39     | 8.82%   |
| 3.01-4.0   | 7        | 12     | 2.29%   |
| 4.01-10.0  | 7        | 8      | 2.29%   |
| 2.01-3.0   | 6        | 14     | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 70       | 28.69%  |
| 251-500        | 52       | 21.31%  |
| 1001-2000      | 35       | 14.34%  |
| 501-1000       | 24       | 9.84%   |
| More than 3000 | 22       | 9.02%   |
| 51-100         | 16       | 6.56%   |
| 2001-3000      | 12       | 4.92%   |
| 21-50          | 9        | 3.69%   |
| 1-20           | 4        | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 80       | 31.5%   |
| 21-50          | 55       | 21.65%  |
| 51-100         | 29       | 11.42%  |
| 251-500        | 22       | 8.66%   |
| 101-250        | 20       | 7.87%   |
| 501-1000       | 18       | 7.09%   |
| 1001-2000      | 16       | 6.3%    |
| More than 3000 | 7        | 2.76%   |
| 2001-3000      | 7        | 2.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD2500BEVT-24A23T0 250GB      | 1        | 1      | 12.5%   |
| Seagate ST9320325AS 320GB         | 1        | 1      | 12.5%   |
| Seagate ST500LT012-1DG142 500GB   | 1        | 1      | 12.5%   |
| Seagate ST3250318AS 249GB         | 1        | 1      | 12.5%   |
| Seagate ST2000DX001-1CM164 2TB    | 1        | 1      | 12.5%   |
| Samsung Electronics SP2004C 200GB | 1        | 1      | 12.5%   |
| Samsung Electronics HM500JI 500GB | 1        | 1      | 12.5%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 50%     |
| Samsung Electronics | 3        | 3      | 37.5%   |
| WDC                 | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 50%     |
| Samsung Electronics | 3        | 3      | 37.5%   |
| WDC                 | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 8      | 100%    |

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
| Detected | 194      | 456    | 76.68%  |
| Works    | 51       | 113    | 20.16%  |
| Malfunc  | 8        | 8      | 3.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 164      | 52.73%  |
| AMD                              | 54       | 17.36%  |
| Samsung Electronics              | 15       | 4.82%   |
| Nvidia                           | 13       | 4.18%   |
| ASMedia Technology               | 13       | 4.18%   |
| JMicron Technology               | 12       | 3.86%   |
| Phison Electronics               | 8        | 2.57%   |
| VIA Technologies                 | 6        | 1.93%   |
| Marvell Technology Group         | 6        | 1.93%   |
| SanDisk                          | 3        | 0.96%   |
| Kingston Technology Company      | 3        | 0.96%   |
| Broadcom / LSI                   | 3        | 0.96%   |
| Silicon Motion                   | 2        | 0.64%   |
| Silicon Integrated Systems [SiS] | 2        | 0.64%   |
| Silicon Image                    | 2        | 0.64%   |
| SK hynix                         | 1        | 0.32%   |
| Micron/Crucial Technology        | 1        | 0.32%   |
| LSI Logic / Symbios Logic        | 1        | 0.32%   |
| Integrated Technology Express    | 1        | 0.32%   |
| ADATA Technology                 | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29       | 6.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 23       | 5.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 20       | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20       | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 3.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13       | 3.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 2.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 2.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 2.14%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 1.9%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 1.9%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.67%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7        | 1.67%   |
| Nvidia MCP61 IDE                                                                        | 6        | 1.43%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.43%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 1.43%   |
| AMD FCH SATA Controller D                                                               | 6        | 1.43%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 5        | 1.19%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.19%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.19%   |
| Phison E12 NVMe Controller                                                              | 4        | 0.95%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4        | 0.95%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.95%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 0.95%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 0.95%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3        | 0.71%   |
| JMicron JMB368 IDE controller                                                           | 3        | 0.71%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 0.71%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.71%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 0.71%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 0.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 168      | 53.67%  |
| IDE  | 93       | 29.71%  |
| NVMe | 32       | 10.22%  |
| RAID | 15       | 4.79%   |
| SAS  | 3        | 0.96%   |
| SCSI | 2        | 0.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 167      | 70.76%  |
| AMD    | 69       | 29.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 2.53%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 2.11%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 1.69%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 4        | 1.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.69%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 4        | 1.69%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 4        | 1.69%   |
| Intel Pentium D CPU 2.80GHz                 | 3        | 1.27%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 3        | 1.27%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.27%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 1.27%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.27%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.27%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 3        | 1.27%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.27%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.27%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 1.27%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 1.27%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 0.84%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 0.84%   |
| Intel Pentium D CPU 3.00GHz                 | 2        | 0.84%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 0.84%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 0.84%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.84%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.84%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.84%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.84%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 0.84%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.84%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.84%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.84%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.84%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz       | 2        | 0.84%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 0.84%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.84%   |
| AMD Sempron Processor 3000+                 | 2        | 0.84%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 0.84%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 0.84%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 0.84%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 2        | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 32       | 13.5%   |
| Intel Core i7           | 30       | 12.66%  |
| Intel Core 2 Duo        | 20       | 8.44%   |
| Intel Core i3           | 16       | 6.75%   |
| Intel Xeon              | 14       | 5.91%   |
| Intel Core 2 Quad       | 12       | 5.06%   |
| AMD Ryzen 5             | 12       | 5.06%   |
| AMD Ryzen 7             | 10       | 4.22%   |
| Intel Pentium           | 9        | 3.8%    |
| Intel Celeron           | 9        | 3.8%    |
| Intel Pentium D         | 7        | 2.95%   |
| AMD FX                  | 7        | 2.95%   |
| Intel Pentium Dual-Core | 5        | 2.11%   |
| AMD Ryzen 3             | 5        | 2.11%   |
| Intel Core 2            | 4        | 1.69%   |
| AMD Sempron             | 4        | 1.69%   |
| AMD Phenom II X4        | 4        | 1.69%   |
| AMD Athlon 64 X2        | 4        | 1.69%   |
| Other                   | 3        | 1.27%   |
| Intel Pentium 4         | 3        | 1.27%   |
| AMD Phenom II X6        | 3        | 1.27%   |
| AMD Athlon XP           | 3        | 1.27%   |
| AMD Athlon II X2        | 3        | 1.27%   |
| Intel Core i9           | 2        | 0.84%   |
| AMD Ryzen 9             | 2        | 0.84%   |
| AMD Athlon II X4        | 2        | 0.84%   |
| AMD Athlon              | 2        | 0.84%   |
| AMD A4                  | 2        | 0.84%   |
| Intel Pentium Gold      | 1        | 0.42%   |
| Intel Pentium Dual      | 1        | 0.42%   |
| AMD Turion II Neo       | 1        | 0.42%   |
| AMD Ryzen 5 PRO         | 1        | 0.42%   |
| AMD Phenom II X2        | 1        | 0.42%   |
| AMD G                   | 1        | 0.42%   |
| AMD E1                  | 1        | 0.42%   |
| AMD A10                 | 1        | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 96       | 40.51%  |
| 2      | 84       | 35.44%  |
| 8      | 19       | 8.02%   |
| 6      | 17       | 7.17%   |
| 1      | 13       | 5.49%   |
| 16     | 4        | 1.69%   |
| 3      | 2        | 0.84%   |
| 12     | 1        | 0.42%   |
| 10     | 1        | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 230      | 97.46%  |
| 2      | 6        | 2.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 141      | 59.49%  |
| 2      | 96       | 40.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 230      | 97.46%  |
| 32-bit         | 6        | 2.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 22       | 9.17%   |
| Unknown    | 21       | 8.75%   |
| 0x306a9    | 20       | 8.33%   |
| 0x206a7    | 18       | 7.5%    |
| 0x306c3    | 17       | 7.08%   |
| 0x08108109 | 8        | 3.33%   |
| 0x010000c8 | 7        | 2.92%   |
| 0x6fd      | 6        | 2.5%    |
| 0x6fb      | 6        | 2.5%    |
| 0x506e3    | 6        | 2.5%    |
| 0x906ed    | 5        | 2.08%   |
| 0x106e5    | 5        | 2.08%   |
| 0x10677    | 5        | 2.08%   |
| 0x08701021 | 5        | 2.08%   |
| 0xf65      | 4        | 1.67%   |
| 0x906eb    | 4        | 1.67%   |
| 0xf64      | 3        | 1.25%   |
| 0x906ea    | 3        | 1.25%   |
| 0x6f2      | 3        | 1.25%   |
| 0x206d7    | 3        | 1.25%   |
| 0x106a5    | 3        | 1.25%   |
| 0x08101016 | 3        | 1.25%   |
| 0x0800820d | 3        | 1.25%   |
| 0x06001119 | 3        | 1.25%   |
| 0x06000852 | 3        | 1.25%   |
| 0xf29      | 2        | 0.83%   |
| 0xa0671    | 2        | 0.83%   |
| 0xa0655    | 2        | 0.83%   |
| 0x906e9    | 2        | 0.83%   |
| 0x90675    | 2        | 0.83%   |
| 0x40651    | 2        | 0.83%   |
| 0x20655    | 2        | 0.83%   |
| 0x10676    | 2        | 0.83%   |
| 0x08701013 | 2        | 0.83%   |
| 0x08001129 | 2        | 0.83%   |
| 0x0600063e | 2        | 0.83%   |
| 0x05000119 | 2        | 0.83%   |
| 0x010000dc | 2        | 0.83%   |
| 0xf47      | 1        | 0.42%   |
| 0xf43      | 1        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 29       | 12.24%  |
| SandyBridge   | 24       | 10.13%  |
| IvyBridge     | 21       | 8.86%   |
| Haswell       | 20       | 8.44%   |
| Core          | 18       | 7.59%   |
| KabyLake      | 16       | 6.75%   |
| K10           | 14       | 5.91%   |
| NetBurst      | 12       | 5.06%   |
| Zen+          | 11       | 4.64%   |
| Zen           | 9        | 3.8%    |
| Nehalem       | 8        | 3.38%   |
| Zen 2         | 7        | 2.95%   |
| Piledriver    | 7        | 2.95%   |
| K8 Hammer     | 7        | 2.95%   |
| Skylake       | 6        | 2.53%   |
| Zen 3         | 5        | 2.11%   |
| Unknown       | 4        | 1.69%   |
| Westmere      | 3        | 1.27%   |
| K6            | 3        | 1.27%   |
| CometLake     | 3        | 1.27%   |
| Bulldozer     | 3        | 1.27%   |
| Bobcat        | 2        | 0.84%   |
| Tremont       | 1        | 0.42%   |
| Jaguar        | 1        | 0.42%   |
| Goldmont plus | 1        | 0.42%   |
| Goldmont      | 1        | 0.42%   |
| Broadwell     | 1        | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 116      | 45.49%  |
| Intel                      | 75       | 29.41%  |
| AMD                        | 57       | 22.35%  |
| VIA Technologies           | 4        | 1.57%   |
| S3 Graphics                | 1        | 0.39%   |
| Matrox Electronics Systems | 1        | 0.39%   |
| ASPEED Technology          | 1        | 0.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 17       | 6.49%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 9        | 3.44%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 3.44%   |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 3.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 8        | 3.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 8        | 3.05%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 2.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 2.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 2.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 2.67%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.91%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.53%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.53%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 1.53%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 4        | 1.53%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.15%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.15%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.15%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 1.15%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 3        | 1.15%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.15%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.15%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.76%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.76%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 2        | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.76%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.76%   |
| Nvidia GF119 [NVS 310]                                                      | 2        | 0.76%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 2        | 0.76%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 0.76%   |
| Nvidia G92 [GeForce GTS 250]                                                | 2        | 0.76%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 0.76%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2        | 0.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.76%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 0.76%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                  | 1        | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 109      | 45.61%  |
| 1 x Intel       | 61       | 25.52%  |
| 1 x AMD         | 49       | 20.5%   |
| 2 x AMD         | 4        | 1.67%   |
| 1 x VIA         | 4        | 1.67%   |
| Intel + Nvidia  | 4        | 1.67%   |
| AMD + Nvidia    | 3        | 1.26%   |
| 2 x Nvidia      | 1        | 0.42%   |
| 1 x S3 Graphics | 1        | 0.42%   |
| 1 x Matrox      | 1        | 0.42%   |
| Intel + AMD     | 1        | 0.42%   |
| 1 x ASPEED      | 1        | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 158      | 65.83%  |
| Proprietary | 50       | 20.83%  |
| Unknown     | 32       | 13.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 94       | 39%     |
| 1.01-2.0   | 39       | 16.18%  |
| 0.01-0.5   | 33       | 13.69%  |
| 0.51-1.0   | 32       | 13.28%  |
| 3.01-4.0   | 21       | 8.71%   |
| 7.01-8.0   | 12       | 4.98%   |
| 5.01-6.0   | 5        | 2.07%   |
| 2.01-3.0   | 3        | 1.24%   |
| 8.01-16.0  | 2        | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 41       | 16.67%  |
| Goldstar             | 27       | 10.98%  |
| Dell                 | 23       | 9.35%   |
| Acer                 | 23       | 9.35%   |
| Hewlett-Packard      | 14       | 5.69%   |
| BenQ                 | 13       | 5.28%   |
| AOC                  | 12       | 4.88%   |
| Ancor Communications | 12       | 4.88%   |
| Philips              | 11       | 4.47%   |
| Unknown              | 10       | 4.07%   |
| Lenovo               | 5        | 2.03%   |
| Iiyama               | 5        | 2.03%   |
| Sony                 | 4        | 1.63%   |
| Fujitsu Siemens      | 4        | 1.63%   |
| ___                  | 2        | 0.81%   |
| Sceptre Tech         | 2        | 0.81%   |
| NEC Computers        | 2        | 0.81%   |
| Medion               | 2        | 0.81%   |
| LG Electronics       | 2        | 0.81%   |
| eMachines            | 2        | 0.81%   |
| AUS                  | 2        | 0.81%   |
| ASUSTek Computer     | 2        | 0.81%   |
| ViewSonic            | 1        | 0.41%   |
| Vestel               | 1        | 0.41%   |
| Toshiba              | 1        | 0.41%   |
| Targa Visionary      | 1        | 0.41%   |
| SKY                  | 1        | 0.41%   |
| PLN                  | 1        | 0.41%   |
| OEM                  | 1        | 0.41%   |
| NCS                  | 1        | 0.41%   |
| Mitsubishi           | 1        | 0.41%   |
| Microstep            | 1        | 0.41%   |
| Lenovo Group Limited | 1        | 0.41%   |
| Insignia             | 1        | 0.41%   |
| IBM                  | 1        | 0.41%   |
| Hitachi              | 1        | 0.41%   |
| HannStar             | 1        | 0.41%   |
| ELSA International   | 1        | 0.41%   |
| Elo Touch            | 1        | 0.41%   |
| ELO                  | 1        | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor SAMSUNG                                          | 2        | 0.78%   |
| Sony LCD Monitor TV 3840x1080                                        | 2        | 0.78%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 2        | 0.78%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 2        | 0.78%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 2        | 0.78%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2        | 0.78%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 0.78%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                | 2        | 0.78%   |
| Dell P190S DEL405B 1280x1024 376x301mm 19.0-inch                     | 2        | 0.78%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                    | 2        | 0.78%   |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                        | 2        | 0.78%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch     | 2        | 0.78%   |
| Acer T272HL ACR013B 1920x1080 598x336mm 27.0-inch                    | 2        | 0.78%   |
| ___ LCDTV16 ___0101 1360x768                                         | 1        | 0.39%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch                | 1        | 0.39%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch             | 1        | 0.39%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                            | 1        | 0.39%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                   | 1        | 0.39%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                   | 1        | 0.39%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                | 1        | 0.39%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                 | 1        | 0.39%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                    | 1        | 0.39%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                             | 1        | 0.39%   |
| Unknown LCD Monitor Dell SE2717H/HX 1920x1080                        | 1        | 0.39%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch               | 1        | 0.39%   |
| Toshiba LCD Monitor TV 1920x1080                                     | 1        | 0.39%   |
| Targa Visionary LCD19-4 TARA194 1280x1024 376x301mm 19.0-inch        | 1        | 0.39%   |
| Sony TV SNY4C03 1920x1080 1063x598mm 48.0-inch                       | 1        | 0.39%   |
| Sony TV SNY1B02 1360x768                                             | 1        | 0.39%   |
| Sony TV  *00 SNYF503 1920x1080 1220x680mm 55.0-inch                  | 1        | 0.39%   |
| SKY TV-monitor SKY1402 3840x2160 708x398mm 32.0-inch                 | 1        | 0.39%   |
| SKY TV SKY1502 3840x2160 1150x650mm 52.0-inch                        | 1        | 0.39%   |
| Sceptre Tech F24 SPT0961 1920x1080 480x260mm 21.5-inch               | 1        | 0.39%   |
| Sceptre Tech E27 SPT0ABF 1920x1080 521x293mm 23.5-inch               | 1        | 0.39%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch    | 1        | 0.39%   |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch    | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 520x290mm 23.4-inch | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch  | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 459x296mm 21.5-inch | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 440x300mm 21.0-inch | 1        | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 104      | 44.44%  |
| 1280x1024 (SXGA)   | 35       | 14.96%  |
| 1680x1050 (WSXGA+) | 17       | 7.26%   |
| 1440x900 (WXGA+)   | 11       | 4.7%    |
| 1366x768 (WXGA)    | 10       | 4.27%   |
| 3840x2160 (4K)     | 7        | 2.99%   |
| 1600x900 (HD+)     | 7        | 2.99%   |
| 1360x768           | 7        | 2.99%   |
| 1920x1200 (WUXGA)  | 6        | 2.56%   |
| Unknown            | 6        | 2.56%   |
| 2560x1440 (QHD)    | 5        | 2.14%   |
| 1024x768 (XGA)     | 5        | 2.14%   |
| 3440x1440          | 4        | 1.71%   |
| 3840x1080          | 3        | 1.28%   |
| 2560x1080          | 3        | 1.28%   |
| 7680x2160          | 1        | 0.43%   |
| 4480x1440          | 1        | 0.43%   |
| 4240x1440          | 1        | 0.43%   |
| 1600x1200          | 1        | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 15.77%  |
| 21      | 29       | 12.03%  |
| 24      | 26       | 10.79%  |
| 23      | 22       | 9.13%   |
| 19      | 21       | 8.71%   |
| 27      | 19       | 7.88%   |
| 17      | 17       | 7.05%   |
| 18      | 16       | 6.64%   |
| 22      | 10       | 4.15%   |
| 15      | 9        | 3.73%   |
| 20      | 8        | 3.32%   |
| 34      | 4        | 1.66%   |
| 31      | 4        | 1.66%   |
| 32      | 3        | 1.24%   |
| 72      | 2        | 0.83%   |
| 52      | 2        | 0.83%   |
| 65      | 1        | 0.41%   |
| 54      | 1        | 0.41%   |
| 48      | 1        | 0.41%   |
| 33      | 1        | 0.41%   |
| 28      | 1        | 0.41%   |
| 26      | 1        | 0.41%   |
| 25      | 1        | 0.41%   |
| 16      | 1        | 0.41%   |
| 14      | 1        | 0.41%   |
| 13      | 1        | 0.41%   |
| 12      | 1        | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 66       | 28.45%  |
| 501-600     | 61       | 26.29%  |
| Unknown     | 38       | 16.38%  |
| 301-350     | 25       | 10.78%  |
| 351-400     | 19       | 8.19%   |
| 701-800     | 8        | 3.45%   |
| 601-700     | 6        | 2.59%   |
| 1001-1500   | 5        | 2.16%   |
| 201-300     | 2        | 0.86%   |
| 1501-2000   | 2        | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 110      | 48.67%  |
| Unknown | 38       | 16.81%  |
| 5/4     | 30       | 13.27%  |
| 16/10   | 30       | 13.27%  |
| 4/3     | 11       | 4.87%   |
| 21/9    | 6        | 2.65%   |
| 3/2     | 1        | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 71       | 29.83%  |
| 151-200        | 39       | 16.39%  |
| Unknown        | 38       | 15.97%  |
| 141-150        | 27       | 11.34%  |
| 301-350        | 20       | 8.4%    |
| 351-500        | 12       | 5.04%   |
| 251-300        | 10       | 4.2%    |
| 101-110        | 8        | 3.36%   |
| More than 1000 | 6        | 2.52%   |
| 111-120        | 3        | 1.26%   |
| 81-90          | 1        | 0.42%   |
| 71-80          | 1        | 0.42%   |
| 131-140        | 1        | 0.42%   |
| 501-1000       | 1        | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 144      | 63.44%  |
| Unknown | 38       | 16.74%  |
| 101-120 | 34       | 14.98%  |
| 1-50    | 6        | 2.64%   |
| 121-160 | 4        | 1.76%   |
| 161-240 | 1        | 0.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 188      | 78.01%  |
| 2     | 36       | 14.94%  |
| 0     | 14       | 5.81%   |
| 3     | 3        | 1.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 139      | 41.74%  |
| Intel                            | 81       | 24.32%  |
| Qualcomm Atheros                 | 27       | 8.11%   |
| Ralink Technology                | 15       | 4.5%    |
| Broadcom                         | 12       | 3.6%    |
| Nvidia                           | 11       | 3.3%    |
| TP-Link                          | 6        | 1.8%    |
| VIA Technologies                 | 4        | 1.2%    |
| Marvell Technology Group         | 4        | 1.2%    |
| Samsung Electronics              | 3        | 0.9%    |
| Huawei Technologies              | 3        | 0.9%    |
| Broadcom Limited                 | 3        | 0.9%    |
| Sitecom Europe                   | 2        | 0.6%    |
| Ralink                           | 2        | 0.6%    |
| Microsoft                        | 2        | 0.6%    |
| AVM                              | 2        | 0.6%    |
| ZTE WCDMA Technologies MSM       | 1        | 0.3%    |
| Silicon Integrated Systems [SiS] | 1        | 0.3%    |
| Qualcomm                         | 1        | 0.3%    |
| NetGear                          | 1        | 0.3%    |
| Mercucys                         | 1        | 0.3%    |
| Mellanox Technologies            | 1        | 0.3%    |
| MediaTek                         | 1        | 0.3%    |
| LSI                              | 1        | 0.3%    |
| JMicron Technology               | 1        | 0.3%    |
| HTC (High Tech Computer)         | 1        | 0.3%    |
| Edimax Technology                | 1        | 0.3%    |
| DisplayLink                      | 1        | 0.3%    |
| D-Link System                    | 1        | 0.3%    |
| Belkin Components                | 1        | 0.3%    |
| ASUSTek Computer                 | 1        | 0.3%    |
| ADMtek                           | 1        | 0.3%    |
| 3Com                             | 1        | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 102      | 27.42%  |
| Intel I211 Gigabit Network Connection                                                         | 11       | 2.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 11       | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 10       | 2.69%   |
| Nvidia MCP61 Ethernet                                                                         | 8        | 2.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 7        | 1.88%   |
| Intel Wi-Fi 6 AX200                                                                           | 6        | 1.61%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 5        | 1.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 5        | 1.34%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 5        | 1.34%   |
| Intel Ethernet Connection (7) I219-V                                                          | 5        | 1.34%   |
| Intel 82579V Gigabit Network Connection                                                       | 5        | 1.34%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 4        | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 1.08%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 1.08%   |
| Intel Ethernet Connection I217-V                                                              | 4        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                                                          | 4        | 1.08%   |
| Intel 82574L Gigabit Network Connection                                                       | 4        | 1.08%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 3        | 0.81%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 3        | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 3        | 0.81%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                    | 3        | 0.81%   |
| Ralink RT5370 Wireless Adapter                                                                | 3        | 0.81%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                                 | 3        | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 3        | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 3        | 0.81%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 3        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 3        | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 3        | 0.81%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 3        | 0.81%   |
| Huawei ELS-NX9                                                                                | 3        | 0.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 0.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 2        | 0.54%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.54%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2        | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 31       | 29.52%  |
| Intel                 | 22       | 20.95%  |
| Ralink Technology     | 15       | 14.29%  |
| Qualcomm Atheros      | 11       | 10.48%  |
| TP-Link               | 6        | 5.71%   |
| Broadcom              | 4        | 3.81%   |
| Sitecom Europe        | 2        | 1.9%    |
| Ralink                | 2        | 1.9%    |
| Microsoft             | 2        | 1.9%    |
| AVM                   | 2        | 1.9%    |
| NetGear               | 1        | 0.95%   |
| Mercucys              | 1        | 0.95%   |
| MediaTek              | 1        | 0.95%   |
| Edimax Technology     | 1        | 0.95%   |
| D-Link System         | 1        | 0.95%   |
| Broadcom Limited      | 1        | 0.95%   |
| Belkin Components     | 1        | 0.95%   |
| ASUSTek Computer      | 1        | 0.95%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 7        | 6.6%    |
| Intel Wi-Fi 6 AX200                                                                           | 6        | 5.66%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 5        | 4.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 3.77%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 3.77%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 3        | 2.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 3        | 2.83%   |
| Ralink RT5370 Wireless Adapter                                                                | 3        | 2.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 3        | 2.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 1.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 1.89%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 1.89%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 1.89%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 1.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 1.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 1.89%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2        | 1.89%   |
| Intel Wireless-AC 9260                                                                        | 2        | 1.89%   |
| Intel Wireless 7265                                                                           | 2        | 1.89%   |
| Intel Wireless 3165                                                                           | 2        | 1.89%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.94%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.94%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 0.94%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 0.94%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                                               | 1        | 0.94%   |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1        | 0.94%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.94%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.94%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 0.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 0.94%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 0.94%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 0.94%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 0.94%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 0.94%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.94%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1        | 0.94%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 0.94%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 126      | 49.22%  |
| Intel                            | 71       | 27.73%  |
| Qualcomm Atheros                 | 16       | 6.25%   |
| Nvidia                           | 11       | 4.3%    |
| Broadcom                         | 8        | 3.13%   |
| VIA Technologies                 | 4        | 1.56%   |
| Marvell Technology Group         | 4        | 1.56%   |
| Samsung Electronics              | 3        | 1.17%   |
| Huawei Technologies              | 3        | 1.17%   |
| Broadcom Limited                 | 2        | 0.78%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.39%   |
| Silicon Integrated Systems [SiS] | 1        | 0.39%   |
| Qualcomm                         | 1        | 0.39%   |
| JMicron Technology               | 1        | 0.39%   |
| HTC (High Tech Computer)         | 1        | 0.39%   |
| DisplayLink                      | 1        | 0.39%   |
| ADMtek                           | 1        | 0.39%   |
| 3Com                             | 1        | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 102      | 38.64%  |
| Intel I211 Gigabit Network Connection                             | 11       | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 3.79%   |
| Nvidia MCP61 Ethernet                                             | 8        | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 1.89%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 1.89%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.89%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 1.52%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.52%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.52%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 1.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 1.14%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 1.14%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 1.14%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 1.14%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 1.14%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 1.14%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.14%   |
| Huawei ELS-NX9                                                    | 3        | 1.14%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.76%   |
| Nvidia nForce2 Ethernet Controller                                | 2        | 0.76%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 0.76%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.76%   |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 0.76%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 0.76%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.76%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1        | 0.38%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.38%   |
| Qualcomm Android                                                  | 1        | 0.38%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.38%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 235      | 70.78%  |
| WiFi     | 95       | 28.61%  |
| Modem    | 1        | 0.3%    |
| Unknown  | 1        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 196      | 80.33%  |
| WiFi     | 48       | 19.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 166      | 70.34%  |
| 2     | 64       | 27.12%  |
| 3     | 4        | 1.69%   |
| 4     | 1        | 0.42%   |
| 0     | 1        | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 195      | 79.59%  |
| Yes  | 50       | 20.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 21       | 40.38%  |
| Cambridge Silicon Radio         | 14       | 26.92%  |
| Realtek Semiconductor           | 5        | 9.62%   |
| Broadcom                        | 4        | 7.69%   |
| Qualcomm Atheros Communications | 2        | 3.85%   |
| ASUSTek Computer                | 2        | 3.85%   |
| MediaTek                        | 1        | 1.92%   |
| Lite-On Technology              | 1        | 1.92%   |
| Dell                            | 1        | 1.92%   |
| Apple                           | 1        | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14       | 26.92%  |
| Intel AX200 Bluetooth                               | 6        | 11.54%  |
| Intel Bluetooth wireless interface                  | 5        | 9.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3        | 5.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 5.77%   |
| Realtek Bluetooth Radio                             | 2        | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 3.85%   |
| Intel Bluetooth Device                              | 2        | 3.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.92%   |
| MediaTek Wireless_Device                            | 1        | 1.92%   |
| Lite-On Bluetooth Device                            | 1        | 1.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 1.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.92%   |
| Intel AX210 Bluetooth                               | 1        | 1.92%   |
| Dell BT Mini-Receiver                               | 1        | 1.92%   |
| Broadcom HP Bluethunder                             | 1        | 1.92%   |
| Broadcom BCM92045B3 ROM                             | 1        | 1.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.92%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 1.92%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 151      | 39.95%  |
| Nvidia                           | 102      | 26.98%  |
| AMD                              | 73       | 19.31%  |
| C-Media Electronics              | 13       | 3.44%   |
| VIA Technologies                 | 8        | 2.12%   |
| GN Netcom                        | 4        | 1.06%   |
| Generalplus Technology           | 4        | 1.06%   |
| Creative Labs                    | 4        | 1.06%   |
| Logitech                         | 3        | 0.79%   |
| JMTek                            | 3        | 0.79%   |
| Silicon Integrated Systems [SiS] | 2        | 0.53%   |
| Yamaha                           | 1        | 0.26%   |
| Xilinx                           | 1        | 0.26%   |
| Tenx Technology                  | 1        | 0.26%   |
| Plantronics                      | 1        | 0.26%   |
| Native Instruments               | 1        | 0.26%   |
| Micro Star International         | 1        | 0.26%   |
| M-Audio                          | 1        | 0.26%   |
| GYROCOM C&C                      | 1        | 0.26%   |
| Focusrite-Novation               | 1        | 0.26%   |
| Evolution Electronics            | 1        | 0.26%   |
| Creative Technology              | 1        | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25       | 5.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 22       | 5.23%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 17       | 4.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 3.56%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14       | 3.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 13       | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 3.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13       | 3.09%   |
| Nvidia High Definition Audio Controller                                    | 11       | 2.61%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 11       | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10       | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 2.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 2.14%   |
| Nvidia GM206 High Definition Audio Controller                              | 9        | 2.14%   |
| Nvidia MCP61 High Definition Audio                                         | 8        | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 1.66%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 1.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 1.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 1.43%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.19%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 5        | 1.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.19%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 4        | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 0.95%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.95%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 0.95%   |
| Nvidia GK104 HDMI Audio Controller                                         | 4        | 0.95%   |
| Nvidia GF116 High Definition Audio Controller                              | 4        | 0.95%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 0.95%   |
| Generalplus Technology USB Audio Device                                    | 4        | 0.95%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4        | 0.95%   |
| AMD FCH Azalia Controller                                                  | 4        | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.71%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.71%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 18       | 30%     |
| Samsung Electronics | 7        | 11.67%  |
| Kingston            | 7        | 11.67%  |
| Crucial             | 7        | 11.67%  |
| SK hynix            | 3        | 5%      |
| Micron Technology   | 3        | 5%      |
| G.Skill             | 3        | 5%      |
| Corsair             | 3        | 5%      |
| Smart               | 1        | 1.67%   |
| PLEXHD              | 1        | 1.67%   |
| Nanya Technology    | 1        | 1.67%   |
| Kingmax             | 1        | 1.67%   |
| Exceleram           | 1        | 1.67%   |
| Elpida              | 1        | 1.67%   |
| AVEXIR              | 1        | 1.67%   |
| A-DATA Technology   | 1        | 1.67%   |
| Unknown             | 1        | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 2        | 3.13%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 1        | 1.56%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                | 1        | 1.56%   |
| Unknown RAM Module 512MB DIMM 667MT/s                  | 1        | 1.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 1.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s           | 1        | 1.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1        | 1.56%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 1.56%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 1.56%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 1.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 1        | 1.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 1        | 1.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s            | 1        | 1.56%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s             | 1        | 1.56%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s             | 1        | 1.56%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                 | 1        | 1.56%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s               | 1        | 1.56%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 1        | 1.56%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                 | 1        | 1.56%   |
| Unknown RAM Module 1024MB DIMM                         | 1        | 1.56%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s     | 1        | 1.56%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s  | 1        | 1.56%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s          | 1        | 1.56%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s  | 1        | 1.56%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s   | 1        | 1.56%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s              | 1        | 1.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 1        | 1.56%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s  | 1        | 1.56%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1600MT/s    | 1        | 1.56%   |
| Samsung RAM M393B1G70BH0-YK0 8GB DIMM DDR3 1600MT/s    | 1        | 1.56%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s   | 1        | 1.56%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s    | 1        | 1.56%   |
| PLEXHD RAM Module 8192MB DIMM DDR3 1333MT/s            | 1        | 1.56%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s      | 1        | 1.56%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 1        | 1.56%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s    | 1        | 1.56%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s   | 1        | 1.56%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s         | 1        | 1.56%   |
| Kingston RAM KHX3600C17D4/16GX 16GB DIMM DDR4 3800MT/s | 1        | 1.56%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 1        | 1.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 19       | 33.33%  |
| DDR3    | 19       | 33.33%  |
| DDR2    | 7        | 12.28%  |
| Unknown | 6        | 10.53%  |
| SDRAM   | 3        | 5.26%   |
| DDR     | 3        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 51       | 91.07%  |
| SODIMM | 5        | 8.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 29.31%  |
| 4096  | 13       | 22.41%  |
| 2048  | 12       | 20.69%  |
| 16384 | 9        | 15.52%  |
| 1024  | 5        | 8.62%   |
| 32768 | 1        | 1.72%   |
| 512   | 1        | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 15       | 25.42%  |
| 800     | 6        | 10.17%  |
| 1333    | 5        | 8.47%   |
| 667     | 5        | 8.47%   |
| 2667    | 4        | 6.78%   |
| 3200    | 3        | 5.08%   |
| 2400    | 3        | 5.08%   |
| 3600    | 2        | 3.39%   |
| 2133    | 2        | 3.39%   |
| 533     | 2        | 3.39%   |
| Unknown | 2        | 3.39%   |
| 4266    | 1        | 1.69%   |
| 3800    | 1        | 1.69%   |
| 3733    | 1        | 1.69%   |
| 3500    | 1        | 1.69%   |
| 3400    | 1        | 1.69%   |
| 2666    | 1        | 1.69%   |
| 1866    | 1        | 1.69%   |
| 1334    | 1        | 1.69%   |
| 1067    | 1        | 1.69%   |
| 400     | 1        | 1.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 37.5%   |
| Brother Industries  | 3        | 18.75%  |
| Samsung Electronics | 2        | 12.5%   |
| Canon               | 2        | 12.5%   |
| Seiko Epson         | 1        | 6.25%   |
| Ricoh               | 1        | 6.25%   |
| Konica Minolta      | 1        | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Brother MFC-L2685DW              | 2        | 12.5%   |
| Seiko Epson ET-2820 Series       | 1        | 6.25%   |
| Samsung SCX-3400 Series          | 1        | 6.25%   |
| Samsung ML-1670 Series           | 1        | 6.25%   |
| Ricoh SP C260SFNw                | 1        | 6.25%   |
| Konica Minolta 185               | 1        | 6.25%   |
| HP OfficeJet Pro 8730            | 1        | 6.25%   |
| HP LaserJet P1006                | 1        | 6.25%   |
| HP LaserJet 3050                 | 1        | 6.25%   |
| HP DeskJet F4200 series          | 1        | 6.25%   |
| HP Deskjet 2540 series           | 1        | 6.25%   |
| HP Deskjet 1050 J410             | 1        | 6.25%   |
| Canon LaserShot LBP-1120 Printer | 1        | 6.25%   |
| Canon iP4200                     | 1        | 6.25%   |
| Brother HL-L2300D series         | 1        | 6.25%   |

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
| Logitech                      | 14       | 36.84%  |
| Sunplus Innovation Technology | 3        | 7.89%   |
| Microsoft                     | 3        | 7.89%   |
| Z-Star Microelectronics       | 2        | 5.26%   |
| Creative Technology           | 2        | 5.26%   |
| Xiongmai                      | 1        | 2.63%   |
| WCM_USB                       | 1        | 2.63%   |
| Service & Quality Technology  | 1        | 2.63%   |
| Pixart Imaging                | 1        | 2.63%   |
| OmniVision Technologies       | 1        | 2.63%   |
| Nintendo                      | 1        | 2.63%   |
| Microdia                      | 1        | 2.63%   |
| MacroSilicon                  | 1        | 2.63%   |
| KYE Systems (Mouse Systems)   | 1        | 2.63%   |
| Huawei Technologies           | 1        | 2.63%   |
| Generalplus Technology        | 1        | 2.63%   |
| Chicony Electronics           | 1        | 2.63%   |
| ARC International             | 1        | 2.63%   |
| Alcor Micro                   | 1        | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Logitech Webcam C270                               | 5        | 13.16%  |
| Z-Star Venus USB2.0 Camera                         | 2        | 5.26%   |
| Microsoft LifeCam HD-3000                          | 2        | 5.26%   |
| Logitech Webcam C310                               | 2        | 5.26%   |
| Xiongmai web camera                                | 1        | 2.63%   |
| WCM_USB WEB CAM                                    | 1        | 2.63%   |
| Sunplus Full HD webcam                             | 1        | 2.63%   |
| Sunplus FHD Camera Microphone                      | 1        | 2.63%   |
| Sunplus AAPDQT-0622-W                              | 1        | 2.63%   |
| Service & Quality USB PC Camera                    | 1        | 2.63%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro               | 1        | 2.63%   |
| OmniVision Integrated Webcam for Dell XPS 2010     | 1        | 2.63%   |
| Nintendo USB Camera                                | 1        | 2.63%   |
| Microsoft MicrosoftÂ LifeCam VX-5500              | 1        | 2.63%   |
| Microdia Webcam Vitade AF                          | 1        | 2.63%   |
| MacroSilicon USB Video                             | 1        | 2.63%   |
| Logitech Webcam Pro 9000                           | 1        | 2.63%   |
| Logitech Webcam C930e                              | 1        | 2.63%   |
| Logitech Webcam C925e                              | 1        | 2.63%   |
| Logitech Webcam C210                               | 1        | 2.63%   |
| Logitech Webcam B500                               | 1        | 2.63%   |
| Logitech Logi Webcam C920e                         | 1        | 2.63%   |
| Logitech HD Pro Webcam C920                        | 1        | 2.63%   |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 1        | 2.63%   |
| Huawei UVC Camera                                  | 1        | 2.63%   |
| Generalplus 808 Camera #9 (web-cam mode)           | 1        | 2.63%   |
| Creative VF0610 Live! Cam Socialize HD             | 1        | 2.63%   |
| Creative Live! Cam Sync HD [VF0770]                | 1        | 2.63%   |
| Chicony HP High Definition 1MP Webcam              | 1        | 2.63%   |
| ARC International Camera                           | 1        | 2.63%   |
| Alcor Micro USB 2.0 PC Camera                      | 1        | 2.63%   |

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
| 0     | 168      | 69.42%  |
| 1     | 64       | 26.45%  |
| 2     | 6        | 2.48%   |
| 4     | 2        | 0.83%   |
| 3     | 2        | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 44       | 51.16%  |
| Net/wireless             | 22       | 25.58%  |
| Communication controller | 6        | 6.98%   |
| Unassigned class         | 3        | 3.49%   |
| Network                  | 2        | 2.33%   |
| Net/ethernet             | 2        | 2.33%   |
| Storage/raid             | 1        | 1.16%   |
| Storage/ide              | 1        | 1.16%   |
| Multimedia controller    | 1        | 1.16%   |
| Modem                    | 1        | 1.16%   |
| Fingerprint reader       | 1        | 1.16%   |
| Chipcard                 | 1        | 1.16%   |
| Camera                   | 1        | 1.16%   |

