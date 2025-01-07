Linux in New Zealand - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in New Zealand.

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

Total: 672

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | DQ67SW AAG12527-310         | [a4c7be2f1a](https://linux-hardware.org/?probe=a4c7be2f1a) | Jan 03, 2025 |
| HP            | 1494                        | [9c53750126](https://linux-hardware.org/?probe=9c53750126) | Jan 01, 2025 |
| HP            | 1494                        | [a0f989d505](https://linux-hardware.org/?probe=a0f989d505) | Dec 31, 2024 |
| HP            | 83F2                        | [28232611f8](https://linux-hardware.org/?probe=28232611f8) | Dec 27, 2024 |
| Gigabyte      | Z690 UD DDR4                | [fc2486e691](https://linux-hardware.org/?probe=fc2486e691) | Dec 26, 2024 |
| Gigabyte      | EP45-UD3LR                  | [244ba13e5e](https://linux-hardware.org/?probe=244ba13e5e) | Dec 25, 2024 |
| ASRock        | B760M Pro-A WiFi            | [8323aa21ad](https://linux-hardware.org/?probe=8323aa21ad) | Dec 24, 2024 |
| ASRock        | B760M Pro-A WiFi            | [3946d0bb57](https://linux-hardware.org/?probe=3946d0bb57) | Dec 20, 2024 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [0ae519bf73](https://linux-hardware.org/?probe=0ae519bf73) | Dec 18, 2024 |
| ASRock        | B760M Pro RS/D4 WiFi        | [34bf804bd1](https://linux-hardware.org/?probe=34bf804bd1) | Dec 17, 2024 |
| MAXSUN        | MS-Challenger B450M         | [32a2c0a5bf](https://linux-hardware.org/?probe=32a2c0a5bf) | Dec 17, 2024 |
| HP            | 1495                        | [81994e4b0e](https://linux-hardware.org/?probe=81994e4b0e) | Dec 17, 2024 |
| ASUSTek       | SABERTOOTH Z87              | [8eeff9db9d](https://linux-hardware.org/?probe=8eeff9db9d) | Dec 14, 2024 |
| Gigabyte      | Z690 UD DDR4                | [42b3bd140f](https://linux-hardware.org/?probe=42b3bd140f) | Dec 13, 2024 |
| ASUSTek       | M2N68-AM SE2                | [8b53c864fe](https://linux-hardware.org/?probe=8b53c864fe) | Dec 13, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [c7e8137b9c](https://linux-hardware.org/?probe=c7e8137b9c) | Dec 08, 2024 |
| MSI           | B450 TOMAHAWK               | [48d351ced9](https://linux-hardware.org/?probe=48d351ced9) | Dec 01, 2024 |
| MSI           | MAG B550M MORTAR            | [d290ab5d70](https://linux-hardware.org/?probe=d290ab5d70) | Dec 01, 2024 |
| ECS           | H55H-I                      | [30ab02e0cf](https://linux-hardware.org/?probe=30ab02e0cf) | Nov 24, 2024 |
| ECS           | H55H-I                      | [e15c44d10c](https://linux-hardware.org/?probe=e15c44d10c) | Nov 24, 2024 |
| Gigabyte      | B85M-D3H-A                  | [e9bbed01d3](https://linux-hardware.org/?probe=e9bbed01d3) | Nov 22, 2024 |
| Unknown       | Unknown                     | [9f933e3704](https://linux-hardware.org/?probe=9f933e3704) | Nov 22, 2024 |
| Dell          | 00V62H A01                  | [3f6a95ad11](https://linux-hardware.org/?probe=3f6a95ad11) | Nov 18, 2024 |
| Gigabyte      | H97-HD3                     | [c231e924ef](https://linux-hardware.org/?probe=c231e924ef) | Nov 11, 2024 |
| Dell          | 0WMJ54 A00                  | [7ad5566418](https://linux-hardware.org/?probe=7ad5566418) | Nov 08, 2024 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | [7646d56938](https://linux-hardware.org/?probe=7646d56938) | Nov 06, 2024 |
| ASRock        | B650 LiveMixer              | [312b0972f7](https://linux-hardware.org/?probe=312b0972f7) | Nov 06, 2024 |
| Gigabyte      | F2A58M-DS2                  | [2dcd2cd367](https://linux-hardware.org/?probe=2dcd2cd367) | Nov 05, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [04191e06b0](https://linux-hardware.org/?probe=04191e06b0) | Nov 04, 2024 |
| Acer          | Veriton X6610G              | [3d2a3caadd](https://linux-hardware.org/?probe=3d2a3caadd) | Oct 31, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [e8ca6f09e7](https://linux-hardware.org/?probe=e8ca6f09e7) | Oct 26, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [1668591553](https://linux-hardware.org/?probe=1668591553) | Oct 26, 2024 |
| Gigabyte      | B650 AORUS ELITE AX V2      | [171bf9a6b1](https://linux-hardware.org/?probe=171bf9a6b1) | Oct 23, 2024 |
| Gigabyte      | H510M DS2V                  | [aa0a212212](https://linux-hardware.org/?probe=aa0a212212) | Oct 13, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | [cbe00ef6b2](https://linux-hardware.org/?probe=cbe00ef6b2) | Oct 13, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d284464df1](https://linux-hardware.org/?probe=d284464df1) | Oct 11, 2024 |
| ASUSTek       | PRIME B450M-A               | [4747b9f85b](https://linux-hardware.org/?probe=4747b9f85b) | Oct 10, 2024 |
| Gigabyte      | H510M S2H V2                | [23da41cb81](https://linux-hardware.org/?probe=23da41cb81) | Oct 09, 2024 |
| Lenovo        | 0B98401 WIN                 | [63f829198f](https://linux-hardware.org/?probe=63f829198f) | Oct 08, 2024 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [d1f81806d0](https://linux-hardware.org/?probe=d1f81806d0) | Oct 06, 2024 |
| Gigabyte      | A620M H                     | [b144a036c9](https://linux-hardware.org/?probe=b144a036c9) | Oct 03, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [0b4d1355de](https://linux-hardware.org/?probe=0b4d1355de) | Sep 29, 2024 |
| MSI           | B550-A PRO                  | [a0c44a617b](https://linux-hardware.org/?probe=a0c44a617b) | Sep 28, 2024 |
| Dell          | 051FJ8 A00                  | [3750216f3e](https://linux-hardware.org/?probe=3750216f3e) | Sep 25, 2024 |
| Dell          | 051FJ8 A00                  | [60e4b8e20b](https://linux-hardware.org/?probe=60e4b8e20b) | Sep 25, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [b3dbaa175d](https://linux-hardware.org/?probe=b3dbaa175d) | Sep 21, 2024 |
| HP            | 83F2                        | [e77b1d8784](https://linux-hardware.org/?probe=e77b1d8784) | Sep 20, 2024 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [c5a9c6334d](https://linux-hardware.org/?probe=c5a9c6334d) | Sep 20, 2024 |
| Gigabyte      | B650M DS3H                  | [9e0c589148](https://linux-hardware.org/?probe=9e0c589148) | Sep 18, 2024 |
| HP            | Boma                        | [933386dfca](https://linux-hardware.org/?probe=933386dfca) | Sep 10, 2024 |
| ASRock        | B650E PG-ITX WiFi           | [64739c4c52](https://linux-hardware.org/?probe=64739c4c52) | Sep 03, 2024 |
| ASRock        | B650E PG-ITX WiFi           | [2f6b2386f3](https://linux-hardware.org/?probe=2f6b2386f3) | Sep 03, 2024 |
| ASRock        | 970 Extreme4                | [a25c9ccdaf](https://linux-hardware.org/?probe=a25c9ccdaf) | Sep 02, 2024 |
| ASRock        | 970 Extreme4                | [f251a3d3a0](https://linux-hardware.org/?probe=f251a3d3a0) | Sep 02, 2024 |
| ASUSTek       | PRIME B450M-A               | [c3cf874ba0](https://linux-hardware.org/?probe=c3cf874ba0) | Sep 02, 2024 |
| Gigabyte      | B360M D3H-CF                | [f769341be7](https://linux-hardware.org/?probe=f769341be7) | Aug 26, 2024 |
| MSI           | B550M PRO-VDH               | [77b92070ec](https://linux-hardware.org/?probe=77b92070ec) | Aug 24, 2024 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [52d8c6427c](https://linux-hardware.org/?probe=52d8c6427c) | Aug 24, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [4e9962f90c](https://linux-hardware.org/?probe=4e9962f90c) | Aug 22, 2024 |
| Dell          | 0PU052                      | [95f1504d6a](https://linux-hardware.org/?probe=95f1504d6a) | Aug 22, 2024 |
| ASRock        | B650M PG Riptide WiFi       | [027e15deb2](https://linux-hardware.org/?probe=027e15deb2) | Aug 18, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [db12103f69](https://linux-hardware.org/?probe=db12103f69) | Aug 18, 2024 |
| Gigabyte      | H81M-HD3                    | [f85c6f494e](https://linux-hardware.org/?probe=f85c6f494e) | Aug 17, 2024 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [1d014a5085](https://linux-hardware.org/?probe=1d014a5085) | Aug 15, 2024 |
| ASUSTek       | P5GC-MX/GBL                 | [ce7187e567](https://linux-hardware.org/?probe=ce7187e567) | Aug 15, 2024 |
| Gigabyte      | Z490 AORUS ELITE AC         | [c6e46b55fe](https://linux-hardware.org/?probe=c6e46b55fe) | Aug 14, 2024 |
| Gigabyte      | H81M-HD3                    | [10ecc6c6c4](https://linux-hardware.org/?probe=10ecc6c6c4) | Aug 12, 2024 |
| ASUSTek       | PRIME B450M-A               | [7d1d61fa3f](https://linux-hardware.org/?probe=7d1d61fa3f) | Aug 12, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [e9bf3f35c2](https://linux-hardware.org/?probe=e9bf3f35c2) | Aug 12, 2024 |
| ASRock        | B560M-ITX/ac                | [a6f4b3ba0b](https://linux-hardware.org/?probe=a6f4b3ba0b) | Aug 10, 2024 |
| ASRock        | B560M-ITX/ac                | [52ca97fd84](https://linux-hardware.org/?probe=52ca97fd84) | Aug 10, 2024 |
| Gigabyte      | H81M-HD3                    | [4d52a37c95](https://linux-hardware.org/?probe=4d52a37c95) | Aug 08, 2024 |
| Gigabyte      | Z790 UD AX                  | [a9786d615f](https://linux-hardware.org/?probe=a9786d615f) | Aug 07, 2024 |
| HP            | 83F3                        | [8b1a108704](https://linux-hardware.org/?probe=8b1a108704) | Aug 03, 2024 |
| Pegatron      | 2AB5                        | [c94576fefd](https://linux-hardware.org/?probe=c94576fefd) | Jul 24, 2024 |
| ASUSTek       | M5A97 R2.0                  | [46748aee2e](https://linux-hardware.org/?probe=46748aee2e) | Jul 23, 2024 |
| Gigabyte      | F2A58M-DS2                  | [95c63d73b5](https://linux-hardware.org/?probe=95c63d73b5) | Jul 22, 2024 |
| Gigabyte      | F2A58M-DS2                  | [e09f0b94e8](https://linux-hardware.org/?probe=e09f0b94e8) | Jul 21, 2024 |
| Acer          | Veriton X2640G V:1.0        | [85d4956501](https://linux-hardware.org/?probe=85d4956501) | Jul 21, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [cb2c5a3de3](https://linux-hardware.org/?probe=cb2c5a3de3) | Jul 20, 2024 |
| HP            | 83F2                        | [d30af24b31](https://linux-hardware.org/?probe=d30af24b31) | Jul 18, 2024 |
| Gigabyte      | Z690 UD AX DDR4             | [83f7dc4e07](https://linux-hardware.org/?probe=83f7dc4e07) | Jul 15, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [7ecc2be56e](https://linux-hardware.org/?probe=7ecc2be56e) | Jul 12, 2024 |
| ASUSTek       | B150M-A/M.2                 | [e3507bd66f](https://linux-hardware.org/?probe=e3507bd66f) | Jul 08, 2024 |
| Gigabyte      | Z690 UD DDR4                | [bd15491297](https://linux-hardware.org/?probe=bd15491297) | Jul 07, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [6c7bcd021d](https://linux-hardware.org/?probe=6c7bcd021d) | Jun 29, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [de32ab8e14](https://linux-hardware.org/?probe=de32ab8e14) | Jun 28, 2024 |
| ASRock        | N100DC-ITX                  | [b1f1c48f11](https://linux-hardware.org/?probe=b1f1c48f11) | Jun 27, 2024 |
| Pegatron      | 2AB6                        | [af3bbc9d2e](https://linux-hardware.org/?probe=af3bbc9d2e) | Jun 26, 2024 |
| Dell          | 0NC2VH A01                  | [973408b607](https://linux-hardware.org/?probe=973408b607) | Jun 22, 2024 |
| Gigabyte      | B760M H DDR4                | [8d6956f9a6](https://linux-hardware.org/?probe=8d6956f9a6) | Jun 17, 2024 |
| Gigabyte      | B760M H DDR4                | [3e87b834d6](https://linux-hardware.org/?probe=3e87b834d6) | Jun 17, 2024 |
| Gigabyte      | B550 AORUS PRO AX           | [626f9ea78b](https://linux-hardware.org/?probe=626f9ea78b) | Jun 12, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | [4ad840ce96](https://linux-hardware.org/?probe=4ad840ce96) | Jun 11, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [7e1173c163](https://linux-hardware.org/?probe=7e1173c163) | Jun 06, 2024 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [bad70d9b7d](https://linux-hardware.org/?probe=bad70d9b7d) | May 30, 2024 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [f886465cab](https://linux-hardware.org/?probe=f886465cab) | May 29, 2024 |
| MSI           | MPG B550 GAMING EDGE WIF... | [fae7db37eb](https://linux-hardware.org/?probe=fae7db37eb) | May 29, 2024 |
| ASRock        | B560M-ITX/ac                | [b68d9ac21d](https://linux-hardware.org/?probe=b68d9ac21d) | May 18, 2024 |
| Pegatron      | 2AC3                        | [90916e3259](https://linux-hardware.org/?probe=90916e3259) | May 18, 2024 |
| ASRock        | B560M-ITX/ac                | [aa1981e8c1](https://linux-hardware.org/?probe=aa1981e8c1) | May 12, 2024 |
| Gigabyte      | H270N-WIFI-CF               | [7691c4fa1d](https://linux-hardware.org/?probe=7691c4fa1d) | May 10, 2024 |
| Gigabyte      | Z68AP-D3                    | [7411eab31d](https://linux-hardware.org/?probe=7411eab31d) | May 04, 2024 |
| Dell          | 0HD5W2 A01                  | [b44b5a5556](https://linux-hardware.org/?probe=b44b5a5556) | May 03, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | [4d9e58a6de](https://linux-hardware.org/?probe=4d9e58a6de) | Apr 30, 2024 |
| Dell          | 0F3KHR A01                  | [fdcd93e140](https://linux-hardware.org/?probe=fdcd93e140) | Apr 28, 2024 |
| Dell          | 0F3KHR A01                  | [d83354002b](https://linux-hardware.org/?probe=d83354002b) | Apr 27, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [b6aa6b2262](https://linux-hardware.org/?probe=b6aa6b2262) | Apr 22, 2024 |
| Unknown       | Unknown                     | [639a73dd7e](https://linux-hardware.org/?probe=639a73dd7e) | Apr 14, 2024 |
| ASRock        | 970 Pro3 R2.0               | [c12fc6f65e](https://linux-hardware.org/?probe=c12fc6f65e) | Apr 10, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [43618657fd](https://linux-hardware.org/?probe=43618657fd) | Apr 09, 2024 |
| ASRock        | 970 Pro3 R2.0               | [33dd11bc5b](https://linux-hardware.org/?probe=33dd11bc5b) | Apr 07, 2024 |
| ASRock        | B560M-ITX/ac                | [deb5d7b1ca](https://linux-hardware.org/?probe=deb5d7b1ca) | Mar 23, 2024 |
| Gigabyte      | Z97-HD3                     | [d6dfd879ee](https://linux-hardware.org/?probe=d6dfd879ee) | Mar 20, 2024 |
| HP            | 2B38                        | [b0457c0f4a](https://linux-hardware.org/?probe=b0457c0f4a) | Mar 17, 2024 |
| ASRock        | B560M-ITX/ac                | [3c068136de](https://linux-hardware.org/?probe=3c068136de) | Mar 17, 2024 |
| MSI           | B450 TOMAHAWK               | [c8aa89bb80](https://linux-hardware.org/?probe=c8aa89bb80) | Mar 13, 2024 |
| Intel         | X99H V1.x                   | [9da589fefc](https://linux-hardware.org/?probe=9da589fefc) | Mar 11, 2024 |
| Gigabyte      | B550M DS3H AC               | [203f82333d](https://linux-hardware.org/?probe=203f82333d) | Mar 07, 2024 |
| ASUSTek       | P8Z68-V PRO                 | [cd72ba8c02](https://linux-hardware.org/?probe=cd72ba8c02) | Mar 06, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [e4944abc1f](https://linux-hardware.org/?probe=e4944abc1f) | Mar 03, 2024 |
| ASUSTek       | PRIME H310M-A R2.0          | [9953ba3b51](https://linux-hardware.org/?probe=9953ba3b51) | Mar 01, 2024 |
| Gigabyte      | H310M S2H                   | [482a7100d8](https://linux-hardware.org/?probe=482a7100d8) | Feb 27, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [b166351cca](https://linux-hardware.org/?probe=b166351cca) | Feb 24, 2024 |
| Gigabyte      | B560 HD3                    | [471e56fa2c](https://linux-hardware.org/?probe=471e56fa2c) | Feb 16, 2024 |
| HP            | 18E5                        | [3e90471e97](https://linux-hardware.org/?probe=3e90471e97) | Feb 09, 2024 |
| HP            | 18E5                        | [9ae685a4cb](https://linux-hardware.org/?probe=9ae685a4cb) | Feb 09, 2024 |
| Gigabyte      | H310M S2H                   | [87512d7e7e](https://linux-hardware.org/?probe=87512d7e7e) | Feb 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [2b98b922fe](https://linux-hardware.org/?probe=2b98b922fe) | Feb 03, 2024 |
| ASRock        | B560M-ITX/ac                | [9ed6c67efe](https://linux-hardware.org/?probe=9ed6c67efe) | Feb 02, 2024 |
| ASUSTek       | Z97I-PLUS                   | [32200add92](https://linux-hardware.org/?probe=32200add92) | Jan 31, 2024 |
| ASUSTek       | Z97I-PLUS                   | [38cafaade5](https://linux-hardware.org/?probe=38cafaade5) | Jan 31, 2024 |
| Gigabyte      | B550 GAMING X V2            | [99e90d2b89](https://linux-hardware.org/?probe=99e90d2b89) | Jan 29, 2024 |
| ASUSTek       | M4A87TD/USB3                | [185a90aec7](https://linux-hardware.org/?probe=185a90aec7) | Jan 28, 2024 |
| ASUSTek       | P8B75-M                     | [ad1a5f6757](https://linux-hardware.org/?probe=ad1a5f6757) | Jan 28, 2024 |
| HP            | 2AAC                        | [d397b1b3b3](https://linux-hardware.org/?probe=d397b1b3b3) | Jan 26, 2024 |
| Intel         | Unknown                     | [e4094a3abf](https://linux-hardware.org/?probe=e4094a3abf) | Jan 23, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [4f202be1d5](https://linux-hardware.org/?probe=4f202be1d5) | Jan 20, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a1e7338a13](https://linux-hardware.org/?probe=a1e7338a13) | Jan 19, 2024 |
| ASUSTek       | Z97M-PLUS                   | [6565fd5500](https://linux-hardware.org/?probe=6565fd5500) | Jan 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | [122b72e9f2](https://linux-hardware.org/?probe=122b72e9f2) | Jan 15, 2024 |
| ASRock        | B560M-ITX/ac                | [0ab95fc3f5](https://linux-hardware.org/?probe=0ab95fc3f5) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [4a1bc29322](https://linux-hardware.org/?probe=4a1bc29322) | Jan 06, 2024 |
| ASUSTek       | H110M-A/M.2                 | [7b663d0c10](https://linux-hardware.org/?probe=7b663d0c10) | Jan 05, 2024 |
| ASUSTek       | H110M-A/M.2                 | [d80a5355a3](https://linux-hardware.org/?probe=d80a5355a3) | Jan 05, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [251b877f2f](https://linux-hardware.org/?probe=251b877f2f) | Jan 03, 2024 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [24166c136e](https://linux-hardware.org/?probe=24166c136e) | Jan 02, 2024 |
| Dell          | 0D28YY A01                  | [f67d5d22eb](https://linux-hardware.org/?probe=f67d5d22eb) | Jan 02, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [e330d0191e](https://linux-hardware.org/?probe=e330d0191e) | Dec 31, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [a9dd36da25](https://linux-hardware.org/?probe=a9dd36da25) | Dec 29, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [a4f7b1d9d3](https://linux-hardware.org/?probe=a4f7b1d9d3) | Nov 20, 2023 |
| Acer          | Aspire X3400                | [26cedbdbde](https://linux-hardware.org/?probe=26cedbdbde) | Nov 19, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [a7d065988a](https://linux-hardware.org/?probe=a7d065988a) | Nov 19, 2023 |
| Acer          | Aspire X3400                | [83890ec21c](https://linux-hardware.org/?probe=83890ec21c) | Nov 19, 2023 |
| Gigabyte      | H170-Gaming 3               | [ad44d7ebae](https://linux-hardware.org/?probe=ad44d7ebae) | Nov 15, 2023 |
| ASRock        | 890GM Pro3                  | [a88696f0e2](https://linux-hardware.org/?probe=a88696f0e2) | Nov 13, 2023 |
| HP            | ProLiant ML310e Gen8        | [0483e390e3](https://linux-hardware.org/?probe=0483e390e3) | Nov 11, 2023 |
| ASRock        | 890GM Pro3                  | [e00099e8c5](https://linux-hardware.org/?probe=e00099e8c5) | Nov 08, 2023 |
| ASUSTek       | P8B75-M                     | [c88dde8f18](https://linux-hardware.org/?probe=c88dde8f18) | Nov 07, 2023 |
| ASUSTek       | PRIME B460M-A               | [52a36f5268](https://linux-hardware.org/?probe=52a36f5268) | Nov 04, 2023 |
| Dell          | 01NP3N A00                  | [2332805279](https://linux-hardware.org/?probe=2332805279) | Nov 04, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| ASRock        | 890GM Pro3                  | [cfeea44315](https://linux-hardware.org/?probe=cfeea44315) | Oct 30, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [3831a70240](https://linux-hardware.org/?probe=3831a70240) | Oct 27, 2023 |
| HP            | 1998                        | [4701148920](https://linux-hardware.org/?probe=4701148920) | Oct 26, 2023 |
| ASRock        | 890GM Pro3                  | [ca2fb95579](https://linux-hardware.org/?probe=ca2fb95579) | Oct 25, 2023 |
| HP            | ProLiant ML310e Gen8        | [79f6aee2c7](https://linux-hardware.org/?probe=79f6aee2c7) | Oct 24, 2023 |
| ASUSTek       | H110M-A                     | [2ad6656255](https://linux-hardware.org/?probe=2ad6656255) | Oct 21, 2023 |
| ASUSTek       | H110M-A                     | [4aaa66c7bc](https://linux-hardware.org/?probe=4aaa66c7bc) | Oct 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d3e6e2aa83](https://linux-hardware.org/?probe=d3e6e2aa83) | Oct 03, 2023 |
| MSI           | PRO B550M-VC WIFI           | [34d3a3bd47](https://linux-hardware.org/?probe=34d3a3bd47) | Oct 03, 2023 |
| Supermicro    | H8DM8-2                     | [5386350e20](https://linux-hardware.org/?probe=5386350e20) | Oct 03, 2023 |
| Dell          | 0D28YY A01                  | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| HP            | 8714                        | [235d6bd11b](https://linux-hardware.org/?probe=235d6bd11b) | Sep 24, 2023 |
| HP            | 1998                        | [27c06c8617](https://linux-hardware.org/?probe=27c06c8617) | Sep 20, 2023 |
| HP            | 1998                        | [d65f099f06](https://linux-hardware.org/?probe=d65f099f06) | Sep 19, 2023 |
| Dell          | 0VNP2H A00                  | [04e5805a67](https://linux-hardware.org/?probe=04e5805a67) | Sep 06, 2023 |
| MSI           | X79A-GD65                   | [5efb1e3e55](https://linux-hardware.org/?probe=5efb1e3e55) | Sep 06, 2023 |
| Dell          | 0D28YY A01                  | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Dell          | 042P49 A01                  | [29e55d4d72](https://linux-hardware.org/?probe=29e55d4d72) | Sep 04, 2023 |
| ASUSTek       | Z97M-PLUS                   | [5dac4ae656](https://linux-hardware.org/?probe=5dac4ae656) | Sep 03, 2023 |
| Acer          | Aspire X3400                | [62a78b2a16](https://linux-hardware.org/?probe=62a78b2a16) | Sep 01, 2023 |
| ASRock        | B560M-ITX/ac                | [1330f2ac2a](https://linux-hardware.org/?probe=1330f2ac2a) | Aug 24, 2023 |
| HP            | 18E5                        | [c17629e422](https://linux-hardware.org/?probe=c17629e422) | Aug 22, 2023 |
| ASUSTek       | GRYPHON Z87                 | [df9fab1b5b](https://linux-hardware.org/?probe=df9fab1b5b) | Aug 13, 2023 |
| ASUSTek       | PRIME B550M-K               | [60de8d6d38](https://linux-hardware.org/?probe=60de8d6d38) | Aug 11, 2023 |
| ASUSTek       | GRYPHON Z87                 | [0638b1c2dd](https://linux-hardware.org/?probe=0638b1c2dd) | Aug 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | [ff98e5f807](https://linux-hardware.org/?probe=ff98e5f807) | Aug 10, 2023 |
| CWWK          | CW-AD4L-N V1                | [8d9ea8214d](https://linux-hardware.org/?probe=8d9ea8214d) | Jul 23, 2023 |
| ASUSTek       | P7P55D                      | [61c153902b](https://linux-hardware.org/?probe=61c153902b) | Jul 19, 2023 |
| Unknown       | EMB-BT1                     | [90dbc847d2](https://linux-hardware.org/?probe=90dbc847d2) | Jul 16, 2023 |
| ASUSTek       | AT3IONT-I                   | [f1a7e1dbb3](https://linux-hardware.org/?probe=f1a7e1dbb3) | Jul 15, 2023 |
| ASUSTek       | AT3IONT-I                   | [773d5ee9aa](https://linux-hardware.org/?probe=773d5ee9aa) | Jul 13, 2023 |
| ASUSTek       | GRYPHON Z87                 | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [56c3cb8200](https://linux-hardware.org/?probe=56c3cb8200) | Jul 06, 2023 |
| ASRock        | B560M-ITX/ac                | [4c5f8f3d95](https://linux-hardware.org/?probe=4c5f8f3d95) | Jul 01, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [ffcfef2edb](https://linux-hardware.org/?probe=ffcfef2edb) | Jun 30, 2023 |
| Acer          | EG43M                       | [e6d28dd1e5](https://linux-hardware.org/?probe=e6d28dd1e5) | Jun 28, 2023 |
| Dell          | 0NDYHG A01                  | [15e9b561e3](https://linux-hardware.org/?probe=15e9b561e3) | Jun 27, 2023 |
| Dell          | 0NDYHG A01                  | [34cf8e17a2](https://linux-hardware.org/?probe=34cf8e17a2) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [ef8876640e](https://linux-hardware.org/?probe=ef8876640e) | Jun 22, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [744c44deca](https://linux-hardware.org/?probe=744c44deca) | Jun 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [5b35735d26](https://linux-hardware.org/?probe=5b35735d26) | Jun 04, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [c0f64d3436](https://linux-hardware.org/?probe=c0f64d3436) | Jun 03, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7a83a98e37](https://linux-hardware.org/?probe=7a83a98e37) | Jun 02, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a78aee5f7f](https://linux-hardware.org/?probe=a78aee5f7f) | Jun 02, 2023 |
| ASRock        | B560M-ITX/ac                | [e643aa0f5d](https://linux-hardware.org/?probe=e643aa0f5d) | May 30, 2023 |
| ASUSTek       | M5A97                       | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Unknown       | Unknown                     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [0d3bc48240](https://linux-hardware.org/?probe=0d3bc48240) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [406014a766](https://linux-hardware.org/?probe=406014a766) | May 22, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [dcb29a1ec2](https://linux-hardware.org/?probe=dcb29a1ec2) | May 21, 2023 |
| Gigabyte      | H77M-D3H                    | [88cf891056](https://linux-hardware.org/?probe=88cf891056) | May 21, 2023 |
| Unknown       | T100                        | [c4a7218b7b](https://linux-hardware.org/?probe=c4a7218b7b) | May 18, 2023 |
| HP            | 8055                        | [0efb5c8b5d](https://linux-hardware.org/?probe=0efb5c8b5d) | May 17, 2023 |
| HP            | 8055                        | [d660088965](https://linux-hardware.org/?probe=d660088965) | May 17, 2023 |
| Unknown       | T100                        | [977cdddeb1](https://linux-hardware.org/?probe=977cdddeb1) | May 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| ASRock        | B560M-ITX/ac                | [80b16a8567](https://linux-hardware.org/?probe=80b16a8567) | May 08, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [088deaf386](https://linux-hardware.org/?probe=088deaf386) | May 04, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [eeed9900b0](https://linux-hardware.org/?probe=eeed9900b0) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e84598d67c](https://linux-hardware.org/?probe=e84598d67c) | Mar 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [c239e06998](https://linux-hardware.org/?probe=c239e06998) | Mar 31, 2023 |
| Pegatron      | Maureen                     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Gigabyte      | B450M S2H                   | [7f46837f94](https://linux-hardware.org/?probe=7f46837f94) | Mar 28, 2023 |
| Dell          | 0D28YY A01                  | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| Gigabyte      | H55M-S2H                    | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7e668b89fa](https://linux-hardware.org/?probe=7e668b89fa) | Mar 07, 2023 |
| ASRock        | B560M-ITX/ac                | [0bbfe90659](https://linux-hardware.org/?probe=0bbfe90659) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [883911a8df](https://linux-hardware.org/?probe=883911a8df) | Mar 02, 2023 |
| Gigabyte      | B550M DS3H AC               | [64b2c8d5b9](https://linux-hardware.org/?probe=64b2c8d5b9) | Feb 28, 2023 |
| HP            | 158A                        | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| Dell          | 08HPGT A02                  | [69288a8011](https://linux-hardware.org/?probe=69288a8011) | Feb 24, 2023 |
| ASUSTek       | PRIME B450M-A               | [a6ebba79c9](https://linux-hardware.org/?probe=a6ebba79c9) | Feb 17, 2023 |
| Shenzhen M... | F6BFC                       | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| ASUSTek       | P6TD DELUXE                 | [f9cfe6d485](https://linux-hardware.org/?probe=f9cfe6d485) | Feb 13, 2023 |
| Gigabyte      | Z390 UD                     | [23a79acb25](https://linux-hardware.org/?probe=23a79acb25) | Feb 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [0677b143ac](https://linux-hardware.org/?probe=0677b143ac) | Feb 07, 2023 |
| Gigabyte      | B550 GAMING X V2            | [adb2f19fcd](https://linux-hardware.org/?probe=adb2f19fcd) | Feb 01, 2023 |
| Dell          | 0D28YY A01                  | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eb4687961f](https://linux-hardware.org/?probe=eb4687961f) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| Gigabyte      | B75M-D3H                    | [b5ca740834](https://linux-hardware.org/?probe=b5ca740834) | Jan 28, 2023 |
| ASUSTek       | PRIME H310M-K               | [ec43ef5c17](https://linux-hardware.org/?probe=ec43ef5c17) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d27e517254](https://linux-hardware.org/?probe=d27e517254) | Jan 21, 2023 |
| DFI           | CR101-CST                   | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [02089f3393](https://linux-hardware.org/?probe=02089f3393) | Jan 20, 2023 |
| Dell          | 0D28YY A01                  | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H AC               | [dae35d1c18](https://linux-hardware.org/?probe=dae35d1c18) | Jan 19, 2023 |
| MSI           | MAG B550M MORTAR            | [bcae5d5664](https://linux-hardware.org/?probe=bcae5d5664) | Jan 18, 2023 |
| ASUSTek       | Z97M-PLUS                   | [ea58101334](https://linux-hardware.org/?probe=ea58101334) | Jan 17, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| Dell          | 09KPNV A01                  | [aaf51b3c3b](https://linux-hardware.org/?probe=aaf51b3c3b) | Jan 09, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| HP            | ProLiant ML350p Gen8        | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| Dell          | 09KPNV A01                  | [3f2b642eb0](https://linux-hardware.org/?probe=3f2b642eb0) | Jan 01, 2023 |
| HP            | 3648h                       | [5b3a2d7e48](https://linux-hardware.org/?probe=5b3a2d7e48) | Dec 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [03c35b7588](https://linux-hardware.org/?probe=03c35b7588) | Dec 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fe5df748b0](https://linux-hardware.org/?probe=fe5df748b0) | Dec 23, 2022 |
| Dell          | 09KPNV A01                  | [534f769938](https://linux-hardware.org/?probe=534f769938) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [39bac65c16](https://linux-hardware.org/?probe=39bac65c16) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [967204fede](https://linux-hardware.org/?probe=967204fede) | Dec 09, 2022 |
| Gigabyte      | H77M-D3H                    | [5a6ebebd51](https://linux-hardware.org/?probe=5a6ebebd51) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [68004f52cd](https://linux-hardware.org/?probe=68004f52cd) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [3912675c64](https://linux-hardware.org/?probe=3912675c64) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1b361e2f17](https://linux-hardware.org/?probe=1b361e2f17) | Dec 02, 2022 |
| HP            | 1495                        | [138b5bb823](https://linux-hardware.org/?probe=138b5bb823) | Dec 01, 2022 |
| ASUSTek       | M4A87TD/USB3                | [81a2eaf6e4](https://linux-hardware.org/?probe=81a2eaf6e4) | Nov 24, 2022 |
| ASUSTek       | P5GC-MX/1333                | [dd85fb5c80](https://linux-hardware.org/?probe=dd85fb5c80) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| HP            | 339A                        | [c995f831b8](https://linux-hardware.org/?probe=c995f831b8) | Nov 13, 2022 |
| Gigabyte      | H77M-D3H                    | [2382574dbd](https://linux-hardware.org/?probe=2382574dbd) | Nov 12, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b414369067](https://linux-hardware.org/?probe=b414369067) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [27bc8e172c](https://linux-hardware.org/?probe=27bc8e172c) | Nov 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| Gigabyte      | B560M DS3H AC               | [e939a5f236](https://linux-hardware.org/?probe=e939a5f236) | Oct 19, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [93698d1670](https://linux-hardware.org/?probe=93698d1670) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Gigabyte      | H270-Gaming 3               | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| ASUSTek       | M5A97 R2.0                  | [9b3c73c104](https://linux-hardware.org/?probe=9b3c73c104) | Sep 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | [4cdcef3ebd](https://linux-hardware.org/?probe=4cdcef3ebd) | Sep 28, 2022 |
| ASUSTek       | P5G41T-M LX                 | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | [74e31be1be](https://linux-hardware.org/?probe=74e31be1be) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [4db3f9151e](https://linux-hardware.org/?probe=4db3f9151e) | Sep 11, 2022 |
| Gigabyte      | Z68AP-D3                    | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| Dell          | 0M863N A01                  | [a353883ee2](https://linux-hardware.org/?probe=a353883ee2) | Sep 07, 2022 |
| MSI           | MS-98H3                     | [41ad960dd6](https://linux-hardware.org/?probe=41ad960dd6) | Sep 06, 2022 |
| Gigabyte      | B85M-HD3                    | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Gigabyte      | M61PME-S2                   | [8f8107b683](https://linux-hardware.org/?probe=8f8107b683) | Aug 27, 2022 |
| Gigabyte      | M61PME-S2                   | [e3b89ab2db](https://linux-hardware.org/?probe=e3b89ab2db) | Aug 27, 2022 |
| Dell          | 073MMW A03                  | [b41e0fcad5](https://linux-hardware.org/?probe=b41e0fcad5) | Aug 24, 2022 |
| ASUSTek       | PRIME Z370-A II             | [d7dee32799](https://linux-hardware.org/?probe=d7dee32799) | Aug 23, 2022 |
| ASRock        | 890GM Pro3                  | [51f5d50d85](https://linux-hardware.org/?probe=51f5d50d85) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | [002a0c3f5a](https://linux-hardware.org/?probe=002a0c3f5a) | Aug 22, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [b12d6e7967](https://linux-hardware.org/?probe=b12d6e7967) | Aug 20, 2022 |
| Gigabyte      | B560M DS3H AC               | [c9e9691195](https://linux-hardware.org/?probe=c9e9691195) | Aug 10, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [ca1d7dd61b](https://linux-hardware.org/?probe=ca1d7dd61b) | Aug 03, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| HP            | 8054                        | [3b76696319](https://linux-hardware.org/?probe=3b76696319) | Jul 27, 2022 |
| Intel         | STK1AW32SC H91596-307       | [78225ba5b9](https://linux-hardware.org/?probe=78225ba5b9) | Jul 21, 2022 |
| HP            | 3397                        | [83bdaea8fc](https://linux-hardware.org/?probe=83bdaea8fc) | Jul 17, 2022 |
| Gigabyte      | H87M-D3H                    | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Gigabyte      | B460M D3H                   | [d620225518](https://linux-hardware.org/?probe=d620225518) | Jun 30, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| Alienware     | 01NYPT A00                  | [97b8d855bd](https://linux-hardware.org/?probe=97b8d855bd) | Jun 28, 2022 |
| Dell          | 0XHGV1 A01                  | [9d9ae107c9](https://linux-hardware.org/?probe=9d9ae107c9) | Jun 25, 2022 |
| ASRock        | X370 Taichi                 | [788acf13f2](https://linux-hardware.org/?probe=788acf13f2) | Jun 24, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [d11995947a](https://linux-hardware.org/?probe=d11995947a) | Jun 23, 2022 |
| Dell          | 0XHGV1 A01                  | [656f558626](https://linux-hardware.org/?probe=656f558626) | Jun 23, 2022 |
| HP            | 18E7                        | [2fd690b3b4](https://linux-hardware.org/?probe=2fd690b3b4) | Jun 22, 2022 |
| ASUSTek       | H97M-PLUS                   | [874c85b694](https://linux-hardware.org/?probe=874c85b694) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [38bf9d2a7b](https://linux-hardware.org/?probe=38bf9d2a7b) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a2e10758ca](https://linux-hardware.org/?probe=a2e10758ca) | May 13, 2022 |
| HP            | 1998                        | [b717b34f5b](https://linux-hardware.org/?probe=b717b34f5b) | May 08, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [6693954f79](https://linux-hardware.org/?probe=6693954f79) | May 07, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| ASUSTek       | B150M PRO GAMING            | [a31ab08668](https://linux-hardware.org/?probe=a31ab08668) | May 04, 2022 |
| MSI           | MAG B550M MORTAR            | [c994128afd](https://linux-hardware.org/?probe=c994128afd) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7e84138ea1](https://linux-hardware.org/?probe=7e84138ea1) | Apr 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [8888cb88d3](https://linux-hardware.org/?probe=8888cb88d3) | Apr 22, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [5ec598483e](https://linux-hardware.org/?probe=5ec598483e) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-A               | [d4295c9a47](https://linux-hardware.org/?probe=d4295c9a47) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3ddf8a6825](https://linux-hardware.org/?probe=3ddf8a6825) | Apr 11, 2022 |
| HP            | 1790                        | [5fd16b3e1e](https://linux-hardware.org/?probe=5fd16b3e1e) | Apr 03, 2022 |
| Dell          | 0M017G A00                  | [a7ee814f3a](https://linux-hardware.org/?probe=a7ee814f3a) | Apr 02, 2022 |
| Dell          | 0M863N A01                  | [c05eaeb499](https://linux-hardware.org/?probe=c05eaeb499) | Mar 24, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cf9c727b0d](https://linux-hardware.org/?probe=cf9c727b0d) | Mar 24, 2022 |
| ASUSTek       | P5E                         | [ec2b80980d](https://linux-hardware.org/?probe=ec2b80980d) | Mar 18, 2022 |
| Gigabyte      | B560M DS3H AC               | [64f278889f](https://linux-hardware.org/?probe=64f278889f) | Mar 13, 2022 |
| HP            | 2ADC                        | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| Gigabyte      | B460M DS3H AC               | [5a570f493c](https://linux-hardware.org/?probe=5a570f493c) | Mar 06, 2022 |
| Gigabyte      | H110M-H-CF                  | [5c169a1d32](https://linux-hardware.org/?probe=5c169a1d32) | Feb 25, 2022 |
| ASRock        | B450M Steel Legend          | [dfebbb508b](https://linux-hardware.org/?probe=dfebbb508b) | Feb 24, 2022 |
| ASRock        | B450M Steel Legend          | [26729d3227](https://linux-hardware.org/?probe=26729d3227) | Feb 22, 2022 |
| HP            | 2AF7                        | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| ASUSTek       | P6X58D-E                    | [c7a12417f1](https://linux-hardware.org/?probe=c7a12417f1) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [cc2c71140b](https://linux-hardware.org/?probe=cc2c71140b) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [4d1d42c8cc](https://linux-hardware.org/?probe=4d1d42c8cc) | Feb 20, 2022 |
| ASRock        | B450M Steel Legend          | [024513d4a8](https://linux-hardware.org/?probe=024513d4a8) | Feb 18, 2022 |
| ASRock        | B450M Steel Legend          | [9bc33ce91e](https://linux-hardware.org/?probe=9bc33ce91e) | Feb 16, 2022 |
| ASRock        | B450M Steel Legend          | [cc420f69ce](https://linux-hardware.org/?probe=cc420f69ce) | Feb 16, 2022 |
| ASUSTek       | P8B75-M                     | [caf1721ebe](https://linux-hardware.org/?probe=caf1721ebe) | Feb 12, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [24bd4956b6](https://linux-hardware.org/?probe=24bd4956b6) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d8ec503f66](https://linux-hardware.org/?probe=d8ec503f66) | Jan 21, 2022 |
| MediaVue      | MV-890GX V1.2               | [201163da2f](https://linux-hardware.org/?probe=201163da2f) | Jan 16, 2022 |
| Gigabyte      | X570S AERO G                | [fc3f2a485a](https://linux-hardware.org/?probe=fc3f2a485a) | Jan 08, 2022 |
| Gigabyte      | Z77X-D3H                    | [44cbef1c02](https://linux-hardware.org/?probe=44cbef1c02) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [51f97b7e46](https://linux-hardware.org/?probe=51f97b7e46) | Dec 25, 2021 |
| Gigabyte      | B460M DS3H AC               | [7bde1c408f](https://linux-hardware.org/?probe=7bde1c408f) | Dec 21, 2021 |
| Colorful T... | BATTLE-AX B450M-G DELUXE... | [52614e9f8d](https://linux-hardware.org/?probe=52614e9f8d) | Dec 19, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [a6ddae1f31](https://linux-hardware.org/?probe=a6ddae1f31) | Dec 15, 2021 |
| Intel         | DQ87PG AAG74154-403         | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Huanan        | X99-F8 V2.0                 | [71f69762fe](https://linux-hardware.org/?probe=71f69762fe) | Dec 08, 2021 |
| Dell          | 0M863N A01                  | [01a565720c](https://linux-hardware.org/?probe=01a565720c) | Dec 04, 2021 |
| Gigabyte      | B75M-D3H                    | [939cd87ee7](https://linux-hardware.org/?probe=939cd87ee7) | Nov 22, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [e2bb3dc142](https://linux-hardware.org/?probe=e2bb3dc142) | Nov 21, 2021 |
| HP            | 3396                        | [db69ec8696](https://linux-hardware.org/?probe=db69ec8696) | Nov 17, 2021 |
| HP            | 3396                        | [70fc3e699a](https://linux-hardware.org/?probe=70fc3e699a) | Nov 17, 2021 |
| ASUSTek       | P8Z77-V                     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| MSI           | MAG B365M MORTAR            | [95e40c6343](https://linux-hardware.org/?probe=95e40c6343) | Oct 30, 2021 |
| MSI           | MAG B365M MORTAR            | [f2ce1a8260](https://linux-hardware.org/?probe=f2ce1a8260) | Oct 26, 2021 |
| Gigabyte      | H97M-D3H                    | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| ASUSTek       | PRIME B560-PLUS             | [97bd114229](https://linux-hardware.org/?probe=97bd114229) | Oct 23, 2021 |
| Gigabyte      | B75M-D3H                    | [74c2c9d725](https://linux-hardware.org/?probe=74c2c9d725) | Oct 22, 2021 |
| IBM           | 81Y7071 SVT-R               | [033203aade](https://linux-hardware.org/?probe=033203aade) | Oct 16, 2021 |
| Gigabyte      | B365M HD3                   | [26e0d9a3d9](https://linux-hardware.org/?probe=26e0d9a3d9) | Oct 16, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [530994c225](https://linux-hardware.org/?probe=530994c225) | Oct 11, 2021 |
| MSI           | 2AE0                        | [e5ede0905a](https://linux-hardware.org/?probe=e5ede0905a) | Oct 10, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [55620348e7](https://linux-hardware.org/?probe=55620348e7) | Oct 08, 2021 |
| Dell          | 0D6H9T A02                  | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Gigabyte      | X570 UD                     | [636ef76e1e](https://linux-hardware.org/?probe=636ef76e1e) | Oct 05, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [ca8c02f319](https://linux-hardware.org/?probe=ca8c02f319) | Sep 29, 2021 |
| JGINYUE       | H97I PLUS V2.0              | [2e66de23a2](https://linux-hardware.org/?probe=2e66de23a2) | Sep 28, 2021 |
| Dell          | 0D6H9T A02                  | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [fb59bae064](https://linux-hardware.org/?probe=fb59bae064) | Sep 23, 2021 |
| HP            | 3398                        | [2b8efc01ba](https://linux-hardware.org/?probe=2b8efc01ba) | Sep 22, 2021 |
| HP            | 3398                        | [18b064d0d6](https://linux-hardware.org/?probe=18b064d0d6) | Sep 22, 2021 |
| HP            | 1905                        | [56945cef9c](https://linux-hardware.org/?probe=56945cef9c) | Sep 19, 2021 |
| ASRock        | 970 Pro3 R2.0               | [d172a59c18](https://linux-hardware.org/?probe=d172a59c18) | Sep 14, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [a7e1713e87](https://linux-hardware.org/?probe=a7e1713e87) | Sep 11, 2021 |
| Intel         | DG33BU AAD79951-407         | [69bbaa38d9](https://linux-hardware.org/?probe=69bbaa38d9) | Sep 08, 2021 |
| ASUSTek       | P6X58D-E                    | [cf4c0a5a4d](https://linux-hardware.org/?probe=cf4c0a5a4d) | Aug 28, 2021 |
| ASRock        | 990FX Killer                | [6dd735449b](https://linux-hardware.org/?probe=6dd735449b) | Aug 27, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [badc363516](https://linux-hardware.org/?probe=badc363516) | Aug 26, 2021 |
| HP            | 304Ah                       | [0898c11493](https://linux-hardware.org/?probe=0898c11493) | Aug 19, 2021 |
| Gigabyte      | G41M-ES2L                   | [996054b23c](https://linux-hardware.org/?probe=996054b23c) | Aug 18, 2021 |
| HP            | 3397                        | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| MSI           | MS-7028 10B                 | [d9d570cae6](https://linux-hardware.org/?probe=d9d570cae6) | Aug 12, 2021 |
| Gigabyte      | Z68AP-D3                    | [8e107590a6](https://linux-hardware.org/?probe=8e107590a6) | Aug 09, 2021 |
| ASUSTek       | P6X58D-E                    | [bd3b6b4f35](https://linux-hardware.org/?probe=bd3b6b4f35) | Jul 28, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [cd88f96d38](https://linux-hardware.org/?probe=cd88f96d38) | Jul 26, 2021 |
| Gigabyte      | 990FXA-UD3                  | [215f44bec5](https://linux-hardware.org/?probe=215f44bec5) | Jul 24, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [120f3a158c](https://linux-hardware.org/?probe=120f3a158c) | Jul 21, 2021 |
| Gigabyte      | H81M-HD3                    | [72cf6d1ac2](https://linux-hardware.org/?probe=72cf6d1ac2) | Jul 20, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [f410d6449b](https://linux-hardware.org/?probe=f410d6449b) | Jul 19, 2021 |
| MSI           | MS-7028 10B                 | [2c536a7e90](https://linux-hardware.org/?probe=2c536a7e90) | Jul 18, 2021 |
| MSI           | MS-7028 10B                 | [4077783ab8](https://linux-hardware.org/?probe=4077783ab8) | Jul 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9339298035](https://linux-hardware.org/?probe=9339298035) | Jul 14, 2021 |
| Gigabyte      | P55-UD3                     | [6431c6f93c](https://linux-hardware.org/?probe=6431c6f93c) | Jul 12, 2021 |
| Gigabyte      | P55-UD3                     | [ac267d27d6](https://linux-hardware.org/?probe=ac267d27d6) | Jul 12, 2021 |
| HP            | 1497                        | [eecafd7c6c](https://linux-hardware.org/?probe=eecafd7c6c) | Jul 09, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [e3ee4893c9](https://linux-hardware.org/?probe=e3ee4893c9) | Jul 07, 2021 |
| ASRock        | A320M-HDV                   | [841fb32f2d](https://linux-hardware.org/?probe=841fb32f2d) | Jul 05, 2021 |
| ASUSTek       | Z97M-PLUS                   | [9b30ecd00d](https://linux-hardware.org/?probe=9b30ecd00d) | Jul 03, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7926c787f0](https://linux-hardware.org/?probe=7926c787f0) | Jun 28, 2021 |
| Gigabyte      | B150M-D3H-CF                | [02924c7c01](https://linux-hardware.org/?probe=02924c7c01) | Jun 25, 2021 |
| ASRock        | 970 Pro3 R2.0               | [8ed5dab80e](https://linux-hardware.org/?probe=8ed5dab80e) | Jun 22, 2021 |
| Lenovo        | ThinkCentre M58p 7479RS2    | [0a417745c3](https://linux-hardware.org/?probe=0a417745c3) | Jun 20, 2021 |
| ASUSTek       | P5GC-MX/1333                | [79b90a017a](https://linux-hardware.org/?probe=79b90a017a) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [259f649837](https://linux-hardware.org/?probe=259f649837) | Jun 13, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [b8540739ff](https://linux-hardware.org/?probe=b8540739ff) | Jun 12, 2021 |
| ASRock        | X370 Taichi                 | [15b3d9a238](https://linux-hardware.org/?probe=15b3d9a238) | Jun 10, 2021 |
| ASRock        | X370 Taichi                 | [1ad5e88410](https://linux-hardware.org/?probe=1ad5e88410) | Jun 10, 2021 |
| ASRock        | N68-S UCC                   | [155ac9e15e](https://linux-hardware.org/?probe=155ac9e15e) | Jun 09, 2021 |
| Dell          | 0GDG8Y A00                  | [90c9163323](https://linux-hardware.org/?probe=90c9163323) | Jun 07, 2021 |
| Dell          | 0GDG8Y A00                  | [bebce06283](https://linux-hardware.org/?probe=bebce06283) | Jun 07, 2021 |
| MSI           | MS-7125                     | [66e6adf1ec](https://linux-hardware.org/?probe=66e6adf1ec) | Jun 04, 2021 |
| Dell          | 0GDG8Y A00                  | [7bc9fd5174](https://linux-hardware.org/?probe=7bc9fd5174) | Jun 04, 2021 |
| Dell          | 0RCPW3 A03                  | [536202a82c](https://linux-hardware.org/?probe=536202a82c) | May 22, 2021 |
| Dell          | 0RCPW3 A03                  | [ea6ed65a9e](https://linux-hardware.org/?probe=ea6ed65a9e) | May 20, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [363912f531](https://linux-hardware.org/?probe=363912f531) | May 14, 2021 |
| Gigabyte      | H470 HD3                    | [fb5a619781](https://linux-hardware.org/?probe=fb5a619781) | May 10, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [dcd72d6f14](https://linux-hardware.org/?probe=dcd72d6f14) | May 08, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [f409c90490](https://linux-hardware.org/?probe=f409c90490) | May 01, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fbb7ce2f8b](https://linux-hardware.org/?probe=fbb7ce2f8b) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [04a24d00e5](https://linux-hardware.org/?probe=04a24d00e5) | Apr 30, 2021 |
| Gigabyte      | B150M-D3H-CF                | [4ea82584ae](https://linux-hardware.org/?probe=4ea82584ae) | Apr 23, 2021 |
| Gigabyte      | B550M DS3H                  | [3193d396aa](https://linux-hardware.org/?probe=3193d396aa) | Apr 22, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | [190824abc9](https://linux-hardware.org/?probe=190824abc9) | Apr 16, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9c114a5942](https://linux-hardware.org/?probe=9c114a5942) | Apr 15, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [e23906e5f0](https://linux-hardware.org/?probe=e23906e5f0) | Apr 15, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | [d998403a6d](https://linux-hardware.org/?probe=d998403a6d) | Apr 14, 2021 |
| HP            | 304Ah                       | [92d8929cdf](https://linux-hardware.org/?probe=92d8929cdf) | Apr 10, 2021 |
| Lenovo        | ThinkCentre A57 9704A36     | [cdde4de4ea](https://linux-hardware.org/?probe=cdde4de4ea) | Apr 05, 2021 |
| Gigabyte      | Z77X-D3H                    | [1343705e98](https://linux-hardware.org/?probe=1343705e98) | Apr 05, 2021 |
| Gigabyte      | Z87M-D3H                    | [aaa8a98fce](https://linux-hardware.org/?probe=aaa8a98fce) | Apr 02, 2021 |
| ASRock        | N68-S UCC                   | [e566e1d5a2](https://linux-hardware.org/?probe=e566e1d5a2) | Mar 31, 2021 |
| Intel         | DQ45CB AAE30148-207         | [7f8e7a4f95](https://linux-hardware.org/?probe=7f8e7a4f95) | Mar 28, 2021 |
| ASUSTek       | KCMA-D8                     | [df17b4ced6](https://linux-hardware.org/?probe=df17b4ced6) | Mar 20, 2021 |
| ASRock        | N68-S UCC                   | [15e00c5d4a](https://linux-hardware.org/?probe=15e00c5d4a) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [402cbaf164](https://linux-hardware.org/?probe=402cbaf164) | Mar 15, 2021 |
| HP            | 3399                        | [ca3f4aa75a](https://linux-hardware.org/?probe=ca3f4aa75a) | Mar 15, 2021 |
| HP            | 3399                        | [08dbcb0c9c](https://linux-hardware.org/?probe=08dbcb0c9c) | Mar 15, 2021 |
| ASRock        | B450M Steel Legend          | [e4dca1478e](https://linux-hardware.org/?probe=e4dca1478e) | Mar 14, 2021 |
| Gigabyte      | EP45-DS3L                   | [cf36728751](https://linux-hardware.org/?probe=cf36728751) | Mar 08, 2021 |
| Dell          | 002KVM A00                  | [84dbce50b0](https://linux-hardware.org/?probe=84dbce50b0) | Mar 06, 2021 |
| Gigabyte      | GA-970A-D3                  | [ed941773ff](https://linux-hardware.org/?probe=ed941773ff) | Mar 05, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [57d8b65b84](https://linux-hardware.org/?probe=57d8b65b84) | Mar 04, 2021 |
| Gigabyte      | B75M-D3H                    | [ff15fd93df](https://linux-hardware.org/?probe=ff15fd93df) | Mar 01, 2021 |
| MSI           | MS-7125                     | [3bab98fcf2](https://linux-hardware.org/?probe=3bab98fcf2) | Feb 25, 2021 |
| Gigabyte      | H77M-D3H                    | [3ffa3067b0](https://linux-hardware.org/?probe=3ffa3067b0) | Feb 24, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [0b85af69c2](https://linux-hardware.org/?probe=0b85af69c2) | Feb 23, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [5d129c6417](https://linux-hardware.org/?probe=5d129c6417) | Feb 23, 2021 |
| MSI           | B450M MORTAR MAX            | [97b32c8185](https://linux-hardware.org/?probe=97b32c8185) | Feb 22, 2021 |
| HP            | 1495                        | [7e0c673361](https://linux-hardware.org/?probe=7e0c673361) | Feb 17, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [d7508c8abc](https://linux-hardware.org/?probe=d7508c8abc) | Feb 16, 2021 |
| Supermicro    | X8SIL                       | [b7ead0e2d5](https://linux-hardware.org/?probe=b7ead0e2d5) | Feb 16, 2021 |
| MSI           | MS-7125                     | [104c9a719f](https://linux-hardware.org/?probe=104c9a719f) | Feb 16, 2021 |
| ASUSTek       | P8Z68-V                     | [bfeecd13dd](https://linux-hardware.org/?probe=bfeecd13dd) | Feb 15, 2021 |
| ASUSTek       | P8Z68-V                     | [ced39cce40](https://linux-hardware.org/?probe=ced39cce40) | Feb 15, 2021 |
| ASUSTek       | P5GC-MX/1333                | [eded5967ea](https://linux-hardware.org/?probe=eded5967ea) | Feb 15, 2021 |
| ASUSTek       | P6TD DELUXE                 | [4db8ac896d](https://linux-hardware.org/?probe=4db8ac896d) | Feb 15, 2021 |
| Dell          | 0DFRFW A01                  | [308dadd545](https://linux-hardware.org/?probe=308dadd545) | Feb 12, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [6bee16fdd6](https://linux-hardware.org/?probe=6bee16fdd6) | Feb 08, 2021 |
| ASUSTek       | P6X58D-E                    | [65ca4b3fd8](https://linux-hardware.org/?probe=65ca4b3fd8) | Feb 08, 2021 |
| IBM           | 94Y7718 SIT                 | [f45bb4d28d](https://linux-hardware.org/?probe=f45bb4d28d) | Feb 02, 2021 |
| IBM           | 94Y7718 SIT                 | [4eda682182](https://linux-hardware.org/?probe=4eda682182) | Feb 01, 2021 |
| HP            | 82FE 11                     | [e0890897e2](https://linux-hardware.org/?probe=e0890897e2) | Jan 24, 2021 |
| HP            | 82FE 11                     | [f11621cd76](https://linux-hardware.org/?probe=f11621cd76) | Jan 24, 2021 |
| Gigabyte      | X58A-UD5                    | [e6bc960206](https://linux-hardware.org/?probe=e6bc960206) | Jan 05, 2021 |
| HP            | 304Ah                       | [484bc076eb](https://linux-hardware.org/?probe=484bc076eb) | Jan 03, 2021 |
| MSI           | B450M MORTAR MAX            | [cff3edf070](https://linux-hardware.org/?probe=cff3edf070) | Dec 22, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [da31ffedd3](https://linux-hardware.org/?probe=da31ffedd3) | Dec 19, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [365cef4ed3](https://linux-hardware.org/?probe=365cef4ed3) | Dec 18, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [da5b8f33d0](https://linux-hardware.org/?probe=da5b8f33d0) | Dec 14, 2020 |
| Gigabyte      | 970A-D3P                    | [59bb1dc077](https://linux-hardware.org/?probe=59bb1dc077) | Dec 09, 2020 |
| ASRock        | 960GM-VGS3 FX               | [d98dd8c58b](https://linux-hardware.org/?probe=d98dd8c58b) | Dec 06, 2020 |
| Lenovo        | 310C SDK0J40709 WIN 3259... | [9fed57ace1](https://linux-hardware.org/?probe=9fed57ace1) | Dec 03, 2020 |
| Lenovo        | 310C SDK0J40709 WIN 3259... | [1e4de9cf24](https://linux-hardware.org/?probe=1e4de9cf24) | Dec 03, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [6c7616d830](https://linux-hardware.org/?probe=6c7616d830) | Nov 30, 2020 |
| Gigabyte      | B450M S2H                   | [f420bcff80](https://linux-hardware.org/?probe=f420bcff80) | Nov 29, 2020 |
| HP            | 304Ah                       | [879eecaa2c](https://linux-hardware.org/?probe=879eecaa2c) | Nov 24, 2020 |
| HP            | 304Ah                       | [8822926229](https://linux-hardware.org/?probe=8822926229) | Nov 24, 2020 |
| Gigabyte      | Z68AP-D3                    | [b861a3897c](https://linux-hardware.org/?probe=b861a3897c) | Nov 24, 2020 |
| Gigabyte      | Z68AP-D3                    | [6693dd023e](https://linux-hardware.org/?probe=6693dd023e) | Nov 23, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [0343088b2c](https://linux-hardware.org/?probe=0343088b2c) | Nov 20, 2020 |
| MSI           | B450M MORTAR MAX            | [9fb23cbe75](https://linux-hardware.org/?probe=9fb23cbe75) | Nov 17, 2020 |
| ASUSTek       | PRIME X399-A                | [b32b7c28e2](https://linux-hardware.org/?probe=b32b7c28e2) | Nov 17, 2020 |
| Gigabyte      | A520M DS3H AC               | [163ddf8d0b](https://linux-hardware.org/?probe=163ddf8d0b) | Nov 16, 2020 |
| Dell          | 042P49 A00                  | [e88a5663df](https://linux-hardware.org/?probe=e88a5663df) | Nov 15, 2020 |
| Gigabyte      | B450M S2H                   | [b77ab61c1d](https://linux-hardware.org/?probe=b77ab61c1d) | Nov 10, 2020 |
| Gigabyte      | B450M S2H                   | [b2054d891d](https://linux-hardware.org/?probe=b2054d891d) | Nov 10, 2020 |
| HP            | 304Ah                       | [b306a58bbe](https://linux-hardware.org/?probe=b306a58bbe) | Nov 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [424e7b661d](https://linux-hardware.org/?probe=424e7b661d) | Nov 06, 2020 |
| Gigabyte      | H55M-USB3                   | [d8003cd392](https://linux-hardware.org/?probe=d8003cd392) | Nov 01, 2020 |
| Gigabyte      | H55M-USB3                   | [eeca2887d3](https://linux-hardware.org/?probe=eeca2887d3) | Nov 01, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [66e528143c](https://linux-hardware.org/?probe=66e528143c) | Oct 31, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4d5717bdb1](https://linux-hardware.org/?probe=4d5717bdb1) | Oct 26, 2020 |
| Gigabyte      | H87M-D3H                    | [50cdb98356](https://linux-hardware.org/?probe=50cdb98356) | Oct 26, 2020 |
| HP            | ProLiant ML350 G6           | [862c82ee17](https://linux-hardware.org/?probe=862c82ee17) | Oct 26, 2020 |
| Gigabyte      | F2A75M-D3H                  | [7851a0c8a4](https://linux-hardware.org/?probe=7851a0c8a4) | Oct 21, 2020 |
| HP            | 3396                        | [df383be5cf](https://linux-hardware.org/?probe=df383be5cf) | Oct 20, 2020 |
| HP            | 8055                        | [9cabb3c0e9](https://linux-hardware.org/?probe=9cabb3c0e9) | Oct 18, 2020 |
| Gigabyte      | B550M DS3H                  | [f5fdcbbf41](https://linux-hardware.org/?probe=f5fdcbbf41) | Oct 15, 2020 |
| Gigabyte      | F2A75M-D3H                  | [222313e9d4](https://linux-hardware.org/?probe=222313e9d4) | Oct 06, 2020 |
| ASRock        | AB350M Pro4                 | [d8f8b18b1f](https://linux-hardware.org/?probe=d8f8b18b1f) | Oct 06, 2020 |
| ASRock        | B450M Steel Legend          | [a01b2e0545](https://linux-hardware.org/?probe=a01b2e0545) | Sep 30, 2020 |
| Gigabyte      | H77M-D3H                    | [42e057fc77](https://linux-hardware.org/?probe=42e057fc77) | Sep 29, 2020 |
| Gigabyte      | H77M-D3H                    | [4737809a8c](https://linux-hardware.org/?probe=4737809a8c) | Sep 16, 2020 |
| ASUSTek       | Maximus VII HERO            | [c5f5fd0a14](https://linux-hardware.org/?probe=c5f5fd0a14) | Sep 12, 2020 |
| MSI           | B450M MORTAR MAX            | [aacb67377f](https://linux-hardware.org/?probe=aacb67377f) | Sep 03, 2020 |
| ASRock        | B450M Steel Legend          | [b8d61937bc](https://linux-hardware.org/?probe=b8d61937bc) | Sep 03, 2020 |
| ASRock        | A320M-HDV                   | [3b6586255c](https://linux-hardware.org/?probe=3b6586255c) | Sep 03, 2020 |
| Gigabyte      | Z77MX-D3H                   | [c5c33f3570](https://linux-hardware.org/?probe=c5c33f3570) | Aug 31, 2020 |
| HP            | 8055                        | [55806cdf5c](https://linux-hardware.org/?probe=55806cdf5c) | Aug 30, 2020 |
| ASRock        | X370 Taichi                 | [8cf31213d6](https://linux-hardware.org/?probe=8cf31213d6) | Aug 26, 2020 |
| HP            | 339A                        | [8b33d851ce](https://linux-hardware.org/?probe=8b33d851ce) | Aug 20, 2020 |
| HP            | 3398                        | [ab1609f338](https://linux-hardware.org/?probe=ab1609f338) | Aug 13, 2020 |
| Supermicro    | X8SIL                       | [bdee911e92](https://linux-hardware.org/?probe=bdee911e92) | Aug 12, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [89f99d81f3](https://linux-hardware.org/?probe=89f99d81f3) | Aug 12, 2020 |
| Gigabyte      | H81M-DS2                    | [9902d7243c](https://linux-hardware.org/?probe=9902d7243c) | Aug 07, 2020 |
| ASUSTek       | Z97M-PLUS                   | [b895b895f3](https://linux-hardware.org/?probe=b895b895f3) | Aug 04, 2020 |
| HP            | 1998                        | [f9df3fb967](https://linux-hardware.org/?probe=f9df3fb967) | Jul 31, 2020 |
| HP            | 18E7                        | [6c1c183fc6](https://linux-hardware.org/?probe=6c1c183fc6) | Jul 31, 2020 |
| ASUSTek       | P5E3 Deluxe                 | [0355090a1c](https://linux-hardware.org/?probe=0355090a1c) | Jul 31, 2020 |
| Gigabyte      | H81M-HD3                    | [4b574045ce](https://linux-hardware.org/?probe=4b574045ce) | Jul 30, 2020 |
| Gigabyte      | H81M-HD3                    | [8b5a82ed70](https://linux-hardware.org/?probe=8b5a82ed70) | Jul 29, 2020 |
| Gigabyte      | H81M-DS2                    | [b17cece7fd](https://linux-hardware.org/?probe=b17cece7fd) | Jul 24, 2020 |
| HP            | 1998                        | [aa54cd9e2c](https://linux-hardware.org/?probe=aa54cd9e2c) | Jul 22, 2020 |
| Gigabyte      | AB350-Gaming-CF             | [db6c2584ca](https://linux-hardware.org/?probe=db6c2584ca) | Jul 15, 2020 |
| Unknown       | MNIC8PI                     | [0f24f7650f](https://linux-hardware.org/?probe=0f24f7650f) | Jul 13, 2020 |
| HP            | 212B                        | [9b5c44d526](https://linux-hardware.org/?probe=9b5c44d526) | Jul 10, 2020 |
| ASRock        | X370 Taichi                 | [4a4c813642](https://linux-hardware.org/?probe=4a4c813642) | Jul 08, 2020 |
| Gigabyte      | F2A75M-D3H                  | [67339ac7fd](https://linux-hardware.org/?probe=67339ac7fd) | Jul 05, 2020 |
| Lenovo        | MAHOBAY NOK                 | [61948190fd](https://linux-hardware.org/?probe=61948190fd) | Jul 01, 2020 |
| ASRock        | X370 Taichi                 | [803ec85b14](https://linux-hardware.org/?probe=803ec85b14) | Jun 30, 2020 |
| Gigabyte      | 970A-D3P                    | [55e71afa91](https://linux-hardware.org/?probe=55e71afa91) | Jun 29, 2020 |
| Biostar       | A68N-5000                   | [33f0f081e9](https://linux-hardware.org/?probe=33f0f081e9) | Jun 27, 2020 |
| Gigabyte      | F2A75M-D3H                  | [8f67a7b83f](https://linux-hardware.org/?probe=8f67a7b83f) | Jun 18, 2020 |
| Acer          | Aspire XC-704G              | [3a13e1d14a](https://linux-hardware.org/?probe=3a13e1d14a) | Jun 12, 2020 |
| Acer          | Aspire XC-704G              | [3fd600b32c](https://linux-hardware.org/?probe=3fd600b32c) | Jun 12, 2020 |
| ASRock        | Z87 Killer                  | [edb30202da](https://linux-hardware.org/?probe=edb30202da) | Jun 10, 2020 |
| Gigabyte      | 970A-D3P                    | [cd7ee5a475](https://linux-hardware.org/?probe=cd7ee5a475) | Jun 06, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [4e7221a789](https://linux-hardware.org/?probe=4e7221a789) | Jun 06, 2020 |
| Gigabyte      | H81M-DS2                    | [4d45a85cae](https://linux-hardware.org/?probe=4d45a85cae) | Jun 06, 2020 |
| Gigabyte      | X58A-UD7                    | [2e81a03c85](https://linux-hardware.org/?probe=2e81a03c85) | Jun 01, 2020 |
| Gigabyte      | X58A-UD7                    | [004ae34d21](https://linux-hardware.org/?probe=004ae34d21) | Jun 01, 2020 |
| Gigabyte      | 970A-D3P                    | [83ba796d11](https://linux-hardware.org/?probe=83ba796d11) | Jun 01, 2020 |
| ASRock        | Z77 Extreme4                | [2e074b7913](https://linux-hardware.org/?probe=2e074b7913) | May 30, 2020 |
| ASUSTek       | ROG Maximus XI FORMULA      | [2892347213](https://linux-hardware.org/?probe=2892347213) | May 25, 2020 |
| ASUSTek       | M2N68-AM                    | [dbaf375be0](https://linux-hardware.org/?probe=dbaf375be0) | May 22, 2020 |
| HP            | 3396                        | [6ac1ff7341](https://linux-hardware.org/?probe=6ac1ff7341) | May 19, 2020 |
| HP            | 21B4 A01                    | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| HP            | 3396                        | [236a304cab](https://linux-hardware.org/?probe=236a304cab) | May 19, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [df2b313ce9](https://linux-hardware.org/?probe=df2b313ce9) | May 17, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [01e35cb482](https://linux-hardware.org/?probe=01e35cb482) | May 17, 2020 |
| Gigabyte      | 970A-D3P                    | [973e075347](https://linux-hardware.org/?probe=973e075347) | May 15, 2020 |
| Intel         | DG31PR AAD97573-202         | [5558e7aa8c](https://linux-hardware.org/?probe=5558e7aa8c) | May 14, 2020 |
| ASUSTek       | H110M-A                     | [b865ea9cea](https://linux-hardware.org/?probe=b865ea9cea) | May 12, 2020 |
| ASUSTek       | H110M-A                     | [e8880c2c12](https://linux-hardware.org/?probe=e8880c2c12) | May 12, 2020 |
| Lenovo        | ThinkCentre M58p 7479RS2    | [569705d7d7](https://linux-hardware.org/?probe=569705d7d7) | May 10, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [050a2216f8](https://linux-hardware.org/?probe=050a2216f8) | May 10, 2020 |
| Lenovo        | ThinkCentre M58p 7483AC4    | [65dc50f256](https://linux-hardware.org/?probe=65dc50f256) | May 05, 2020 |
| Gigabyte      | H77M-D3H                    | [3c0cbfbf66](https://linux-hardware.org/?probe=3c0cbfbf66) | May 04, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [c1760ffe1b](https://linux-hardware.org/?probe=c1760ffe1b) | Apr 30, 2020 |
| ASUSTek       | M3A78-EM                    | [5d4f28e58b](https://linux-hardware.org/?probe=5d4f28e58b) | Apr 29, 2020 |
| HP            | 1495                        | [a1f532749d](https://linux-hardware.org/?probe=a1f532749d) | Apr 25, 2020 |
| ASUSTek       | Maximus VII HERO            | [ab309746a3](https://linux-hardware.org/?probe=ab309746a3) | Apr 23, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [ae8010c021](https://linux-hardware.org/?probe=ae8010c021) | Apr 21, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [b67554882d](https://linux-hardware.org/?probe=b67554882d) | Apr 19, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [3a29b79970](https://linux-hardware.org/?probe=3a29b79970) | Apr 18, 2020 |
| Pegatron      | 2A99                        | [23eb1431c9](https://linux-hardware.org/?probe=23eb1431c9) | Apr 13, 2020 |
| ASUSTek       | M2N68-AM                    | [60aac968a5](https://linux-hardware.org/?probe=60aac968a5) | Apr 06, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [3005d3d129](https://linux-hardware.org/?probe=3005d3d129) | Apr 05, 2020 |
| ASUSTek       | PRIME B350M-A               | [7ec6fbac2b](https://linux-hardware.org/?probe=7ec6fbac2b) | Mar 29, 2020 |
| ASUSTek       | H81M-K                      | [8805131c92](https://linux-hardware.org/?probe=8805131c92) | Mar 27, 2020 |
| ASUSTek       | PRIME B350M-A               | [a39b2c1a02](https://linux-hardware.org/?probe=a39b2c1a02) | Mar 27, 2020 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [20fcc93972](https://linux-hardware.org/?probe=20fcc93972) | Mar 22, 2020 |
| ASUSTek       | M2N68-AM                    | [0d0cb38926](https://linux-hardware.org/?probe=0d0cb38926) | Mar 15, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [de4392a815](https://linux-hardware.org/?probe=de4392a815) | Mar 08, 2020 |
| Gigabyte      | H77M-D3H                    | [76a4b4dc8c](https://linux-hardware.org/?probe=76a4b4dc8c) | Mar 08, 2020 |
| HP            | 1998                        | [4976d49be8](https://linux-hardware.org/?probe=4976d49be8) | Feb 13, 2020 |
| HP            | 1496                        | [d031f2ddb3](https://linux-hardware.org/?probe=d031f2ddb3) | Feb 02, 2020 |
| Gigabyte      | P67A-UD3R-B3                | [56653049b3](https://linux-hardware.org/?probe=56653049b3) | Jan 25, 2020 |
| Intel         | DB75EN AAG39650-400         | [9829bf7442](https://linux-hardware.org/?probe=9829bf7442) | Jan 25, 2020 |
| Intel         | DB75EN AAG39650-400         | [7d5c355cec](https://linux-hardware.org/?probe=7d5c355cec) | Jan 25, 2020 |
| ASUSTek       | PRIME X470-PRO              | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| HP            | 1998                        | [d3cafd611f](https://linux-hardware.org/?probe=d3cafd611f) | Jan 17, 2020 |
| ASUSTek       | PRIME X470-PRO              | [a766080680](https://linux-hardware.org/?probe=a766080680) | Jan 11, 2020 |
| Dell          | 0TCYKM A00                  | [dc961a7541](https://linux-hardware.org/?probe=dc961a7541) | Jan 11, 2020 |
| Dell          | 0TCYKM A00                  | [fbe7233d08](https://linux-hardware.org/?probe=fbe7233d08) | Jan 11, 2020 |
| Gigabyte      | P67A-UD3R-B3                | [9670dcf2cf](https://linux-hardware.org/?probe=9670dcf2cf) | Jan 10, 2020 |
| Lenovo        | 0837A85                     | [70b8f03213](https://linux-hardware.org/?probe=70b8f03213) | Jan 08, 2020 |
| HP            | 1998                        | [bebd400cf6](https://linux-hardware.org/?probe=bebd400cf6) | Jan 05, 2020 |
| Intel         | DQ57TM AAE70931-403         | [e8d5ed783b](https://linux-hardware.org/?probe=e8d5ed783b) | Jan 05, 2020 |
| Intel         | DQ57TM AAE70931-403         | [4b841fa47f](https://linux-hardware.org/?probe=4b841fa47f) | Jan 05, 2020 |
| Lenovo        | 0837A85                     | [444269a73d](https://linux-hardware.org/?probe=444269a73d) | Jan 04, 2020 |
| Gigabyte      | P67A-UD3R-B3                | [04dde34cd2](https://linux-hardware.org/?probe=04dde34cd2) | Dec 30, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a0231b59de](https://linux-hardware.org/?probe=a0231b59de) | Dec 30, 2019 |
| ASUSTek       | PRIME B350M-A               | [4ed3a4a663](https://linux-hardware.org/?probe=4ed3a4a663) | Dec 24, 2019 |
| Acer          | Aspire X3470                | [4d5a234113](https://linux-hardware.org/?probe=4d5a234113) | Dec 01, 2019 |
| HP            | ProLiant ML330 G6           | [df7a5ac424](https://linux-hardware.org/?probe=df7a5ac424) | Nov 26, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [dba8a4e258](https://linux-hardware.org/?probe=dba8a4e258) | Nov 15, 2019 |
| ASRock        | H110M-HDV                   | [6a3d4aeb04](https://linux-hardware.org/?probe=6a3d4aeb04) | Nov 13, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [53a489591d](https://linux-hardware.org/?probe=53a489591d) | Nov 09, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [9bcd5c3692](https://linux-hardware.org/?probe=9bcd5c3692) | Nov 09, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [a40193b9fb](https://linux-hardware.org/?probe=a40193b9fb) | Nov 01, 2019 |
| Acer          | Aspire X3470                | [bb12fa0496](https://linux-hardware.org/?probe=bb12fa0496) | Oct 27, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [590377c04a](https://linux-hardware.org/?probe=590377c04a) | Oct 25, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [7b02110be5](https://linux-hardware.org/?probe=7b02110be5) | Oct 17, 2019 |
| Gigabyte      | P67A-UD3R-B3                | [023414eea0](https://linux-hardware.org/?probe=023414eea0) | Oct 10, 2019 |
| OEM           | H81U                        | [cd430ca9b3](https://linux-hardware.org/?probe=cd430ca9b3) | Oct 10, 2019 |
| ASUSTek       | P7P55D-E LX                 | [efc5587c83](https://linux-hardware.org/?probe=efc5587c83) | Oct 04, 2019 |
| Unknown       | Unknown                     | [daa8a7d137](https://linux-hardware.org/?probe=daa8a7d137) | Oct 03, 2019 |
| ASUSTek       | P7P55D-E LX                 | [ef7d61dbd6](https://linux-hardware.org/?probe=ef7d61dbd6) | Oct 01, 2019 |
| ASUSTek       | P7P55D-E LX                 | [a8134f553c](https://linux-hardware.org/?probe=a8134f553c) | Oct 01, 2019 |
| Dell          | 0Y958C A00                  | [f5b1443aa9](https://linux-hardware.org/?probe=f5b1443aa9) | Sep 29, 2019 |
| ASUSTek       | PRIME Z270-AR               | [11473758bd](https://linux-hardware.org/?probe=11473758bd) | Sep 29, 2019 |
| ASUSTek       | ROG Maximus XI FORMULA      | [6de2802483](https://linux-hardware.org/?probe=6de2802483) | Sep 22, 2019 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [3da3a9d9ad](https://linux-hardware.org/?probe=3da3a9d9ad) | Sep 18, 2019 |
| HP            | 1497                        | [51c0a64a32](https://linux-hardware.org/?probe=51c0a64a32) | Sep 14, 2019 |
| ASUSTek       | ROG Maximus XI FORMULA      | [fbac50573d](https://linux-hardware.org/?probe=fbac50573d) | Sep 12, 2019 |
| ASUSTek       | ROG Maximus XI FORMULA      | [a86676d54b](https://linux-hardware.org/?probe=a86676d54b) | Sep 12, 2019 |
| HP            | 1998                        | [5c09dfef4e](https://linux-hardware.org/?probe=5c09dfef4e) | Sep 07, 2019 |
| HP            | 1998                        | [08674f223f](https://linux-hardware.org/?probe=08674f223f) | Sep 01, 2019 |
| MSI           | B250M PRO-VH                | [520d23673a](https://linux-hardware.org/?probe=520d23673a) | Aug 20, 2019 |
| ASUSTek       | P7P55D-E PRO                | [00d0b17230](https://linux-hardware.org/?probe=00d0b17230) | Aug 10, 2019 |
| ASUSTek       | TUF X299 MARK 2             | [3a0644689a](https://linux-hardware.org/?probe=3a0644689a) | Aug 10, 2019 |
| ASUSTek       | P7P55D-E PRO                | [27f23cfc02](https://linux-hardware.org/?probe=27f23cfc02) | Aug 10, 2019 |
| ASRock        | Z97 Extreme6                | [cc9738c393](https://linux-hardware.org/?probe=cc9738c393) | Jul 21, 2019 |
| ASUSTek       | PRIME Z370-P                | [57bc67a21b](https://linux-hardware.org/?probe=57bc67a21b) | Jul 21, 2019 |
| Gigabyte      | P67A-UD3-B3                 | [68241fdb6a](https://linux-hardware.org/?probe=68241fdb6a) | Jul 17, 2019 |
| Gigabyte      | GA-K8NF-9                   | [556ae96f13](https://linux-hardware.org/?probe=556ae96f13) | Jul 17, 2019 |
| Gigabyte      | Z97X-UD3H-CF                | [2ddbcf3d21](https://linux-hardware.org/?probe=2ddbcf3d21) | Jul 06, 2019 |
| ASUSTek       | ROG ZENITH EXTREME          | [5f582a0578](https://linux-hardware.org/?probe=5f582a0578) | Jun 29, 2019 |
| ASUSTek       | P5G41T-M LE                 | [ad98351c8d](https://linux-hardware.org/?probe=ad98351c8d) | Jun 20, 2019 |
| HP            | 304Ah                       | [617269b6e1](https://linux-hardware.org/?probe=617269b6e1) | Jun 01, 2019 |
| Gigabyte      | F2A55M-DS2                  | [09bcc236c3](https://linux-hardware.org/?probe=09bcc236c3) | May 31, 2019 |
| AAEON         | UP-APL01 V0.4               | [6f498d9d7d](https://linux-hardware.org/?probe=6f498d9d7d) | May 28, 2019 |
| Gigabyte      | F2A55M-DS2                  | [e7e92370e2](https://linux-hardware.org/?probe=e7e92370e2) | May 24, 2019 |
| MSI           | IONA                        | [bb5e8345c0](https://linux-hardware.org/?probe=bb5e8345c0) | May 16, 2019 |
| OEM           | H81U                        | [17cab2af03](https://linux-hardware.org/?probe=17cab2af03) | May 08, 2019 |
| HP            | 304Ah                       | [055c45cffd](https://linux-hardware.org/?probe=055c45cffd) | May 05, 2019 |
| MSI           | IONA                        | [68df9179a1](https://linux-hardware.org/?probe=68df9179a1) | Apr 30, 2019 |
| Gigabyte      | F2A55M-DS2                  | [f47857828a](https://linux-hardware.org/?probe=f47857828a) | Apr 10, 2019 |
| ASRock        | N3700-ITX                   | [d79cedb01e](https://linux-hardware.org/?probe=d79cedb01e) | Apr 02, 2019 |
| Gigabyte      | 970A-D3P                    | [a4c7d814b0](https://linux-hardware.org/?probe=a4c7d814b0) | Mar 19, 2019 |
| HP            | 1496                        | [4e44453a25](https://linux-hardware.org/?probe=4e44453a25) | Mar 10, 2019 |
| ASUSTek       | H81M-K                      | [320985bb4c](https://linux-hardware.org/?probe=320985bb4c) | Mar 10, 2019 |
| HP            | 1496                        | [260f13dbef](https://linux-hardware.org/?probe=260f13dbef) | Mar 03, 2019 |
| Gigabyte      | H81M-S2H                    | [d56268e6dd](https://linux-hardware.org/?probe=d56268e6dd) | Feb 02, 2019 |
| Unknown       | Unknown                     | [2ad7f7c63c](https://linux-hardware.org/?probe=2ad7f7c63c) | Jan 08, 2019 |
| ASUSTek       | H81M-K                      | [6501d739bb](https://linux-hardware.org/?probe=6501d739bb) | Dec 16, 2018 |
| ASRock        | 970 Pro3 R2.0               | [43e0d718d9](https://linux-hardware.org/?probe=43e0d718d9) | Dec 03, 2018 |
| ASRock        | 970 Pro3 R2.0               | [d86366c2d9](https://linux-hardware.org/?probe=d86366c2d9) | Dec 03, 2018 |
| HP            | 83E1                        | [6676ac3581](https://linux-hardware.org/?probe=6676ac3581) | Nov 20, 2018 |
| Gigabyte      | AB350-Gaming-CF             | [6fad0c649d](https://linux-hardware.org/?probe=6fad0c649d) | Nov 17, 2018 |
| Gigabyte      | H77M-D3H                    | [9e6f5f9def](https://linux-hardware.org/?probe=9e6f5f9def) | Nov 08, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/New_Zealand/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 41       | 8.86%   |
| Ubuntu 18.04                 | 32       | 6.91%   |
| Ubuntu 22.04                 | 22       | 4.75%   |
| Arch Rolling                 | 19       | 4.1%    |
| Pop!_OS 22.04                | 9        | 1.94%   |
| Pop!_OS 20.10                | 9        | 1.94%   |
| Pop!_OS 20.04                | 8        | 1.73%   |
| Debian 11                    | 8        | 1.73%   |
| Zorin 17                     | 7        | 1.51%   |
| Zorin 16                     | 7        | 1.51%   |
| Ubuntu 20.10                 | 7        | 1.51%   |
| Manjaro                      | 7        | 1.51%   |
| Linux Mint 20.1              | 7        | 1.51%   |
| Fedora 39                    | 7        | 1.51%   |
| Debian 12                    | 7        | 1.51%   |
| Ubuntu 21.04                 | 6        | 1.3%    |
| Ubuntu 18.10                 | 6        | 1.3%    |
| openSUSE Tumbleweed-XXXXXXXX | 6        | 1.3%    |
| OpenMandriva 24.12           | 6        | 1.3%    |
| KDE neon 22.04               | 6        | 1.3%    |
| Fedora 40                    | 6        | 1.3%    |
| Fedora 37                    | 6        | 1.3%    |
| Pop!_OS 21.10                | 5        | 1.08%   |
| Pop!_OS 21.04                | 5        | 1.08%   |
| Linux Mint 20.3              | 5        | 1.08%   |
| KDE neon 20.04               | 5        | 1.08%   |
| Fedora 38                    | 5        | 1.08%   |
| Fedora 36                    | 5        | 1.08%   |
| Fedora 34                    | 5        | 1.08%   |
| Debian 10                    | 5        | 1.08%   |
| Ubuntu 24.04                 | 4        | 0.86%   |
| Ubuntu 23.04                 | 4        | 0.86%   |
| Ubuntu 22.10                 | 4        | 0.86%   |
| Ubuntu 16.04                 | 4        | 0.86%   |
| OpenMandriva 5.0             | 4        | 0.86%   |
| Linux Mint 21.1              | 4        | 0.86%   |
| Linux Mint 20.2              | 4        | 0.86%   |
| Linux Mint 20                | 4        | 0.86%   |
| Fedora 33                    | 4        | 0.86%   |
| Ubuntu 21.10                 | 3        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 132      | 31.06%  |
| Fedora           | 41       | 9.65%   |
| Linux Mint       | 35       | 8.24%   |
| Pop!_OS          | 32       | 7.53%   |
| OpenMandriva     | 24       | 5.65%   |
| Debian           | 21       | 4.94%   |
| Arch             | 21       | 4.94%   |
| Zorin            | 14       | 3.29%   |
| KDE neon         | 14       | 3.29%   |
| Manjaro          | 12       | 2.82%   |
| Kubuntu          | 10       | 2.35%   |
| Endless          | 9        | 2.12%   |
| openSUSE         | 6        | 1.41%   |
| Nobara           | 5        | 1.18%   |
| Xubuntu          | 4        | 0.94%   |
| RHEL             | 3        | 0.71%   |
| MX               | 3        | 0.71%   |
| Bazzite          | 3        | 0.71%   |
| ArcoLinux        | 3        | 0.71%   |
| Ubuntu Unity     | 2        | 0.47%   |
| ROSA             | 2        | 0.47%   |
| org.kde.Platform | 2        | 0.47%   |
| Lubuntu          | 2        | 0.47%   |
| LMDE             | 2        | 0.47%   |
| Kali             | 2        | 0.47%   |
| Elementary       | 2        | 0.47%   |
| Devuan           | 2        | 0.47%   |
| Vanilla          | 1        | 0.24%   |
| Ubuntu Studio    | 1        | 0.24%   |
| Ubuntu MATE      | 1        | 0.24%   |
| Rocky Linux      | 1        | 0.24%   |
| Regata OS        | 1        | 0.24%   |
| Redcore          | 1        | 0.24%   |
| Peppermint       | 1        | 0.24%   |
| Parrot           | 1        | 0.24%   |
| NixOS            | 1        | 0.24%   |
| Linux Lite       | 1        | 0.24%   |
| Gentoo           | 1        | 0.24%   |
| Garuda Linux     | 1        | 0.24%   |
| Dts-distro       | 1        | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 6        | 1.12%   |
| 6.12.1-desktop-1omv2490  | 5        | 0.93%   |
| 5.4.0-7634-generic       | 5        | 0.93%   |
| 5.4.0-52-generic         | 5        | 0.93%   |
| 5.3.0-46-generic         | 5        | 0.93%   |
| 5.15.0-46-generic        | 5        | 0.93%   |
| 6.9.3-76060903-generic   | 4        | 0.74%   |
| 6.6.2-desktop-1omv2390   | 4        | 0.74%   |
| 6.5.0-35-generic         | 4        | 0.74%   |
| 5.15.0-60-generic        | 4        | 0.74%   |
| 5.13.0-30-generic        | 4        | 0.74%   |
| 5.11.0-37-generic        | 4        | 0.74%   |
| 6.8.0-40-generic         | 3        | 0.56%   |
| 6.2.0-35-generic         | 3        | 0.56%   |
| 6.1.0-17-amd64           | 3        | 0.56%   |
| 5.8.0-50-generic         | 3        | 0.56%   |
| 5.8.0-44-generic         | 3        | 0.56%   |
| 5.4.0-65-generic         | 3        | 0.56%   |
| 5.4.0-33-generic         | 3        | 0.56%   |
| 5.3.0-40-generic         | 3        | 0.56%   |
| 5.16.7-desktop-1omv4003  | 3        | 0.56%   |
| 5.13.0-7614-generic      | 3        | 0.56%   |
| 5.13.0-39-generic        | 3        | 0.56%   |
| 5.11.0-7614-generic      | 3        | 0.56%   |
| 5.11.0-34-generic        | 3        | 0.56%   |
| 5.10.14-desktop-1omv4002 | 3        | 0.56%   |
| 5.0.0-37-generic         | 3        | 0.56%   |
| 4.18.0-25-generic        | 3        | 0.56%   |
| 6.8.0-51-generic         | 2        | 0.37%   |
| 6.8.0-41-generic         | 2        | 0.37%   |
| 6.8.0-38-generic         | 2        | 0.37%   |
| 6.5.6-76060506-generic   | 2        | 0.37%   |
| 6.5.0-45-generic         | 2        | 0.37%   |
| 6.2.6-desktop-1omv2390   | 2        | 0.37%   |
| 6.2.15-300.fc38.x86_64   | 2        | 0.37%   |
| 6.2.0-39-generic         | 2        | 0.37%   |
| 6.2.0-20-generic         | 2        | 0.37%   |
| 6.12.1-arch1-1           | 2        | 0.37%   |
| 6.10.0-desktop-1omv2490  | 2        | 0.37%   |
| 6.1.13-200.fc37.x86_64   | 2        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 51       | 10.3%   |
| 5.15.0  | 33       | 6.67%   |
| 4.15.0  | 25       | 5.05%   |
| 5.8.0   | 23       | 4.65%   |
| 5.11.0  | 23       | 4.65%   |
| 5.13.0  | 19       | 3.84%   |
| 5.19.0  | 17       | 3.43%   |
| 5.3.0   | 16       | 3.23%   |
| 4.18.0  | 14       | 2.83%   |
| 6.8.0   | 13       | 2.63%   |
| 6.5.0   | 13       | 2.63%   |
| 6.2.0   | 13       | 2.63%   |
| 6.1.0   | 11       | 2.22%   |
| 5.10.0  | 10       | 2.02%   |
| 5.0.0   | 8        | 1.62%   |
| 6.12.1  | 7        | 1.41%   |
| 6.9.3   | 5        | 1.01%   |
| 6.8.8   | 4        | 0.81%   |
| 6.6.2   | 4        | 0.81%   |
| 6.5.6   | 4        | 0.81%   |
| 6.9.12  | 3        | 0.61%   |
| 6.2.6   | 3        | 0.61%   |
| 6.11.0  | 3        | 0.61%   |
| 5.9.16  | 3        | 0.61%   |
| 5.16.7  | 3        | 0.61%   |
| 5.14.0  | 3        | 0.61%   |
| 5.10.15 | 3        | 0.61%   |
| 5.10.14 | 3        | 0.61%   |
| 6.8.7   | 2        | 0.4%    |
| 6.8.12  | 2        | 0.4%    |
| 6.7.7   | 2        | 0.4%    |
| 6.6.13  | 2        | 0.4%    |
| 6.6.11  | 2        | 0.4%    |
| 6.5.5   | 2        | 0.4%    |
| 6.4.12  | 2        | 0.4%    |
| 6.4.11  | 2        | 0.4%    |
| 6.2.15  | 2        | 0.4%    |
| 6.10.9  | 2        | 0.4%    |
| 6.10.6  | 2        | 0.4%    |
| 6.10.10 | 2        | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 54       | 11.04%  |
| 5.15    | 44       | 9%      |
| 5.11    | 28       | 5.73%   |
| 5.8     | 27       | 5.52%   |
| 6.8     | 25       | 5.11%   |
| 4.15    | 25       | 5.11%   |
| 6.1     | 24       | 4.91%   |
| 5.19    | 23       | 4.7%    |
| 6.5     | 22       | 4.5%    |
| 5.13    | 22       | 4.5%    |
| 6.2     | 19       | 3.89%   |
| 5.3     | 18       | 3.68%   |
| 5.10    | 17       | 3.48%   |
| 6.6     | 14       | 2.86%   |
| 4.18    | 14       | 2.86%   |
| 6.9     | 10       | 2.04%   |
| 6.12    | 10       | 2.04%   |
| 6.10    | 10       | 2.04%   |
| 5.0     | 9        | 1.84%   |
| 6.11    | 8        | 1.64%   |
| 6.7     | 7        | 1.43%   |
| 5.9     | 7        | 1.43%   |
| 5.14    | 7        | 1.43%   |
| 5.7     | 6        | 1.23%   |
| 6.4     | 5        | 1.02%   |
| 5.6     | 5        | 1.02%   |
| 5.18    | 5        | 1.02%   |
| 5.16    | 5        | 1.02%   |
| 6.0     | 4        | 0.82%   |
| 5.12    | 4        | 0.82%   |
| 6.3     | 3        | 0.61%   |
| 5.17    | 3        | 0.61%   |
| 4.19    | 3        | 0.61%   |
| 5.5     | 1        | 0.2%    |
| 5.2     | 1        | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 408      | 99.51%  |
| i686   | 1        | 0.24%   |
| i586   | 1        | 0.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 198      | 45.73%  |
| KDE5          | 67       | 15.47%  |
| Unknown       | 63       | 14.55%  |
| X-Cinnamon    | 36       | 8.31%   |
| XFCE          | 18       | 4.16%   |
| KDE6          | 13       | 3%      |
| KDE           | 12       | 2.77%   |
| MATE          | 8        | 1.85%   |
| LXQt          | 5        | 1.15%   |
| LXDE          | 3        | 0.69%   |
| Unity         | 2        | 0.46%   |
| Pantheon      | 2        | 0.46%   |
| Deepin        | 2        | 0.46%   |
| Cinnamon      | 2        | 0.46%   |
| NONE          | 1        | 0.23%   |
| Enlightenment | 1        | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 284      | 67.14%  |
| Wayland | 94       | 22.22%  |
| Unknown | 31       | 7.33%   |
| Tty     | 14       | 3.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 240      | 56.34%  |
| SDDM    | 66       | 15.49%  |
| GDM3    | 40       | 9.39%   |
| LightDM | 37       | 8.69%   |
| GDM     | 29       | 6.81%   |
| TDM     | 11       | 2.58%   |
| SLiM    | 3        | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_NZ   | 250      | 57.87%  |
| en_US   | 91       | 21.06%  |
| Unknown | 47       | 10.88%  |
| en_GB   | 17       | 3.94%   |
| en_AU   | 12       | 2.78%   |
| C       | 12       | 2.78%   |
| zh_CN   | 2        | 0.46%   |
| de_DE   | 1        | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 244      | 57.96%  |
| EFI  | 177      | 42.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 302      | 71.39%  |
| Btrfs   | 56       | 13.24%  |
| Overlay | 24       | 5.67%   |
| Tmpfs   | 14       | 3.31%   |
| Unknown | 13       | 3.07%   |
| Xfs     | 8        | 1.89%   |
| Zfs     | 4        | 0.95%   |
| F2fs    | 1        | 0.24%   |
| Ext3    | 1        | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 233      | 55.48%  |
| GPT     | 158      | 37.62%  |
| MBR     | 29       | 6.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 341      | 81.38%  |
| Yes       | 78       | 18.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 293      | 70.43%  |
| Yes       | 123      | 29.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Gigabyte Technology                  | 111      | 27.07%  |
| ASUSTek Computer                     | 111      | 27.07%  |
| Hewlett-Packard                      | 49       | 11.95%  |
| ASRock                               | 28       | 6.83%   |
| Dell                                 | 27       | 6.59%   |
| MSI                                  | 26       | 6.34%   |
| Lenovo                               | 11       | 2.68%   |
| Intel                                | 10       | 2.44%   |
| Unknown                              | 8        | 1.95%   |
| Acer                                 | 6        | 1.46%   |
| Pegatron                             | 5        | 1.22%   |
| Supermicro                           | 2        | 0.49%   |
| IBM                                  | 2        | 0.49%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.24%   |
| OEM                                  | 1        | 0.24%   |
| MediaVue                             | 1        | 0.24%   |
| MAXSUN                               | 1        | 0.24%   |
| JGINYUE                              | 1        | 0.24%   |
| Huanan                               | 1        | 0.24%   |
| ECS                                  | 1        | 0.24%   |
| DFI                                  | 1        | 0.24%   |
| CWWK                                 | 1        | 0.24%   |
| Colorful Technology                  | 1        | 0.24%   |
| Biostar                              | 1        | 0.24%   |
| Apple                                | 1        | 0.24%   |
| Alienware                            | 1        | 0.24%   |
| AAEON                                | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 10       | 2.44%   |
| Unknown                         | 9        | 2.2%    |
| Gigabyte H77M-D3H               | 6        | 1.46%   |
| ASUS TUF Gaming X570-PLUS       | 5        | 1.22%   |
| ASUS PRIME B450M-A              | 5        | 1.22%   |
| MSI MS-7C95                     | 4        | 0.98%   |
| HP EliteDesk 800 G1 SFF         | 4        | 0.98%   |
| HP Compaq 8200 Elite SFF PC     | 4        | 0.98%   |
| MSI MS-7C02                     | 3        | 0.73%   |
| MSI MS-7B89                     | 3        | 0.73%   |
| Gigabyte B75M-D3H               | 3        | 0.73%   |
| Gigabyte B550M DS3H AC          | 3        | 0.73%   |
| Gigabyte B450M S2H              | 3        | 0.73%   |
| Gigabyte 970A-D3P               | 3        | 0.73%   |
| Dell OptiPlex 3010              | 3        | 0.73%   |
| ASUS P8B75-M                    | 3        | 0.73%   |
| ASRock B450M Steel Legend       | 3        | 0.73%   |
| ASRock 970 Pro3 R2.0            | 3        | 0.73%   |
| MSI MS-7C91                     | 2        | 0.49%   |
| Lenovo ThinkCentre M58p 7479RS2 | 2        | 0.49%   |
| HP ProDesk 600 G1 SFF           | 2        | 0.49%   |
| HP EliteDesk 800 G2 DM 35W      | 2        | 0.49%   |
| HP EliteDesk 800 G1 USDT        | 2        | 0.49%   |
| HP Compaq Pro 6300 SFF          | 2        | 0.49%   |
| HP Compaq Elite 8300 USDT       | 2        | 0.49%   |
| HP Compaq Elite 8300 SFF        | 2        | 0.49%   |
| HP Compaq 8100 Elite SFF PC     | 2        | 0.49%   |
| HP Compaq 6200 Pro SFF PC       | 2        | 0.49%   |
| Gigabyte Z77X-D3H               | 2        | 0.49%   |
| Gigabyte Z690 UD DDR4           | 2        | 0.49%   |
| Gigabyte Z68AP-D3               | 2        | 0.49%   |
| Gigabyte X670 AORUS ELITE AX    | 2        | 0.49%   |
| Gigabyte H81M-HD3               | 2        | 0.49%   |
| Gigabyte GA-78LMT-USB3          | 2        | 0.49%   |
| Gigabyte F2A75M-D3H             | 2        | 0.49%   |
| Gigabyte F2A55M-DS2             | 2        | 0.49%   |
| Gigabyte B550M DS3H             | 2        | 0.49%   |
| Gigabyte B550 GAMING X V2       | 2        | 0.49%   |
| Gigabyte B550 AORUS ELITE AX V2 | 2        | 0.49%   |
| Gigabyte AB350-Gaming           | 2        | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 28       | 6.83%   |
| ASUS PRIME             | 21       | 5.12%   |
| HP Compaq              | 19       | 4.63%   |
| Dell OptiPlex          | 18       | 4.39%   |
| ASUS TUF               | 14       | 3.41%   |
| HP EliteDesk           | 10       | 2.44%   |
| ASUS All               | 10       | 2.44%   |
| Lenovo ThinkCentre     | 9        | 2.2%    |
| Unknown                | 9        | 2.2%    |
| Dell Precision         | 7        | 1.71%   |
| Gigabyte H77M-D3H      | 6        | 1.46%   |
| HP ProDesk             | 5        | 1.22%   |
| Gigabyte B550M         | 5        | 1.22%   |
| Gigabyte B550          | 5        | 1.22%   |
| MSI MS-7C95            | 4        | 0.98%   |
| HP ProLiant            | 4        | 0.98%   |
| Gigabyte Z690          | 4        | 0.98%   |
| ASUS M5A97             | 4        | 0.98%   |
| ASRock 970             | 4        | 0.98%   |
| Acer Aspire            | 4        | 0.98%   |
| MSI MS-7C02            | 3        | 0.73%   |
| MSI MS-7B89            | 3        | 0.73%   |
| Gigabyte Z790          | 3        | 0.73%   |
| Gigabyte X570          | 3        | 0.73%   |
| Gigabyte GA-78LMT-USB3 | 3        | 0.73%   |
| Gigabyte B75M-D3H      | 3        | 0.73%   |
| Gigabyte B450M         | 3        | 0.73%   |
| Gigabyte AB350-Gaming  | 3        | 0.73%   |
| Gigabyte 970A-D3P      | 3        | 0.73%   |
| ASUS P8B75-M           | 3        | 0.73%   |
| ASUS H110M-A           | 3        | 0.73%   |
| ASRock B450M           | 3        | 0.73%   |
| MSI MS-7C91            | 2        | 0.49%   |
| IBM System             | 2        | 0.49%   |
| Gigabyte Z77X-D3H      | 2        | 0.49%   |
| Gigabyte Z68AP-D3      | 2        | 0.49%   |
| Gigabyte X670          | 2        | 0.49%   |
| Gigabyte X570S         | 2        | 0.49%   |
| Gigabyte H81M-HD3      | 2        | 0.49%   |
| Gigabyte H510M         | 2        | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 58       | 14.15%  |
| 2018    | 37       | 9.02%   |
| 2020    | 33       | 8.05%   |
| 2011    | 32       | 7.8%    |
| 2019    | 31       | 7.56%   |
| 2013    | 29       | 7.07%   |
| 2014    | 26       | 6.34%   |
| 2021    | 24       | 5.85%   |
| 2017    | 22       | 5.37%   |
| 2009    | 20       | 4.88%   |
| 2010    | 19       | 4.63%   |
| 2023    | 16       | 3.9%    |
| 2015    | 14       | 3.41%   |
| 2022    | 13       | 3.17%   |
| 2016    | 12       | 2.93%   |
| 2008    | 12       | 2.93%   |
| 2007    | 4        | 0.98%   |
| 2024    | 3        | 0.73%   |
| 2005    | 2        | 0.49%   |
| Unknown | 2        | 0.49%   |
| 2004    | 1        | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 410      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 399      | 97.08%  |
| Enabled  | 12       | 2.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 409      | 99.76%  |
| Yes  | 1        | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 113      | 26.78%  |
| 32.01-64.0  | 87       | 20.62%  |
| 8.01-16.0   | 75       | 17.77%  |
| 4.01-8.0    | 54       | 12.8%   |
| 3.01-4.0    | 43       | 10.19%  |
| 64.01-256.0 | 28       | 6.64%   |
| 24.01-32.0  | 12       | 2.84%   |
| 1.01-2.0    | 7        | 1.66%   |
| 2.01-3.0    | 2        | 0.47%   |
| 0.01-0.5    | 1        | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 138      | 29.42%  |
| 2.01-3.0   | 123      | 26.23%  |
| 4.01-8.0   | 80       | 17.06%  |
| 3.01-4.0   | 57       | 12.15%  |
| 8.01-16.0  | 36       | 7.68%   |
| 0.51-1.0   | 20       | 4.26%   |
| 16.01-24.0 | 7        | 1.49%   |
| 0.01-0.5   | 5        | 1.07%   |
| 32.01-64.0 | 2        | 0.43%   |
| 24.01-32.0 | 1        | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 135      | 31.18%  |
| 2      | 131      | 30.25%  |
| 3      | 72       | 16.63%  |
| 4      | 53       | 12.24%  |
| 5      | 16       | 3.7%    |
| 6      | 15       | 3.46%   |
| 7      | 5        | 1.15%   |
| 8      | 2        | 0.46%   |
| 0      | 2        | 0.46%   |
| 410    | 1        | 0.23%   |
| 20     | 1        | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 242      | 58.03%  |
| Yes       | 175      | 41.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 408      | 99.51%  |
| No        | 2        | 0.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 214      | 51.32%  |
| Yes       | 203      | 48.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 270      | 65.22%  |
| Yes       | 144      | 34.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| New Zealand | 410      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Auckland         | 194      | 44.8%   |
| Wellington       | 58       | 13.39%  |
| Christchurch     | 55       | 12.7%   |
| Hamilton         | 22       | 5.08%   |
| Tauranga         | 19       | 4.39%   |
| Dunedin          | 15       | 3.46%   |
| Palmerston North | 7        | 1.62%   |
| Napier City      | 7        | 1.62%   |
| Whangarei        | 6        | 1.39%   |
| Whanganui        | 4        | 0.92%   |
| Cambridge        | 4        | 0.92%   |
| Timaru           | 3        | 0.69%   |
| New Plymouth     | 3        | 0.69%   |
| Nelson           | 3        | 0.69%   |
| Hastings         | 3        | 0.69%   |
| Ashburton        | 3        | 0.69%   |
| Rotorua          | 2        | 0.46%   |
| Lower Hutt       | 2        | 0.46%   |
| Invercargill     | 2        | 0.46%   |
| Westport         | 1        | 0.23%   |
| Wellsford        | 1        | 0.23%   |
| Waikato          | 1        | 0.23%   |
| Waikanae         | 1        | 0.23%   |
| Waihi            | 1        | 0.23%   |
| Te Awamutu       | 1        | 0.23%   |
| Stratford        | 1        | 0.23%   |
| Queenstown       | 1        | 0.23%   |
| Porirua          | 1        | 0.23%   |
| Otumoetai        | 1        | 0.23%   |
| Onekawa          | 1        | 0.23%   |
| Mount Maunganui  | 1        | 0.23%   |
| Mount Eden       | 1        | 0.23%   |
| Milton           | 1        | 0.23%   |
| Hunterville      | 1        | 0.23%   |
| Hornby           | 1        | 0.23%   |
| Havelock North   | 1        | 0.23%   |
| Grafton          | 1        | 0.23%   |
| Darfield         | 1        | 0.23%   |
| Carterton        | 1        | 0.23%   |
| Albany           | 1        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 168      | 330    | 21.68%  |
| WDC                          | 149      | 266    | 19.23%  |
| Samsung Electronics          | 145      | 302    | 18.71%  |
| Crucial                      | 50       | 76     | 6.45%   |
| Kingston                     | 36       | 47     | 4.65%   |
| Sandisk                      | 26       | 33     | 3.35%   |
| Toshiba                      | 22       | 29     | 2.84%   |
| Intel                        | 20       | 27     | 2.58%   |
| Hitachi                      | 18       | 27     | 2.32%   |
| A-DATA Technology            | 11       | 14     | 1.42%   |
| Micron/Crucial Technology    | 10       | 15     | 1.29%   |
| Micron Technology            | 8        | 9      | 1.03%   |
| Team                         | 6        | 6      | 0.77%   |
| SK hynix                     | 6        | 8      | 0.77%   |
| Lexar                        | 6        | 12     | 0.77%   |
| Unknown                      | 5        | 10     | 0.65%   |
| OCZ                          | 5        | 6      | 0.65%   |
| Kingston Technology Company  | 5        | 5      | 0.65%   |
| HGST                         | 5        | 7      | 0.65%   |
| Gigabyte Technology          | 5        | 6      | 0.65%   |
| Apacer                       | 5        | 6      | 0.65%   |
| Hewlett-Packard              | 4        | 6      | 0.52%   |
| XPG                          | 3        | 3      | 0.39%   |
| TO Exter                     | 3        | 3      | 0.39%   |
| Phison Electronics           | 3        | 9      | 0.39%   |
| MAXIO Technology (Hangzhou)  | 3        | 5      | 0.39%   |
| External                     | 3        | 4      | 0.39%   |
| Corsair                      | 3        | 5      | 0.39%   |
| China                        | 3        | 4      | 0.39%   |
| Apple                        | 3        | 3      | 0.39%   |
| Transcend                    | 2        | 2      | 0.26%   |
| T-FORCE                      | 2        | 2      | 0.26%   |
| Silicon Motion               | 2        | 3      | 0.26%   |
| Shenzhen Longsys Electronics | 2        | 4      | 0.26%   |
| PNY                          | 2        | 3      | 0.26%   |
| LITEON                       | 2        | 2      | 0.26%   |
| KIOXIA                       | 2        | 2      | 0.26%   |
| KingSpec                     | 2        | 2      | 0.26%   |
| JMicron Technology           | 2        | 2      | 0.26%   |
| ASMT                         | 2        | 2      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 17       | 1.79%   |
| Seagate ST2000DM008-2FR102 2TB                       | 15       | 1.58%   |
| Samsung SSD 850 EVO 500GB                            | 13       | 1.37%   |
| Seagate Expansion Desk 5TB                           | 11       | 1.16%   |
| Samsung SSD 860 EVO 500GB                            | 11       | 1.16%   |
| Seagate ST500DM002-1BD142 500GB                      | 10       | 1.05%   |
| Seagate Expansion 1TB                                | 10       | 1.05%   |
| Crucial CT240BX500SSD1 240GB                         | 10       | 1.05%   |
| Seagate ST31000528AS 1TB                             | 9        | 0.95%   |
| Seagate ST1000DM003-1CH162 1TB                       | 9        | 0.95%   |
| Samsung SSD 980 1TB                                  | 9        | 0.95%   |
| Samsung SSD 850 EVO 250GB                            | 9        | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 9        | 0.95%   |
| Seagate ST2000DM006-2DM164 2TB                       | 8        | 0.84%   |
| Seagate ST2000DM001-1CH164 2TB                       | 8        | 0.84%   |
| Seagate ST1000DM010-2EP102 1TB                       | 8        | 0.84%   |
| WDC WD20EZRZ-00Z5HB0 2TB                             | 7        | 0.74%   |
| Samsung SSD 870 EVO 1TB                              | 7        | 0.74%   |
| Samsung SSD 860 EVO 250GB                            | 7        | 0.74%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 7        | 0.74%   |
| WDC WD20EARX-00PASB0 2TB                             | 6        | 0.63%   |
| WDC WD10EALX-009BA0 1TB                              | 6        | 0.63%   |
| Samsung SSD 870 QVO 1TB                              | 6        | 0.63%   |
| Samsung SSD 870 EVO 500GB                            | 6        | 0.63%   |
| Samsung NVMe SSD Drive 500GB                         | 6        | 0.63%   |
| Kingston SA400S37240G 240GB SSD                      | 6        | 0.63%   |
| Crucial CT500MX500SSD1 500GB                         | 6        | 0.63%   |
| WDC WD10EZEX-00WN4A0 1TB                             | 5        | 0.53%   |
| Toshiba THNS128GG4BBAA 128GB SSD                     | 5        | 0.53%   |
| Seagate ST4000DM004-2CV104 4TB                       | 5        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                      | 5        | 0.53%   |
| Crucial CT1000BX500SSD1 1TB                          | 5        | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 4        | 0.42%   |
| WDC WD1002FAEX-00Z3A0 1TB                            | 4        | 0.42%   |
| Seagate ST9500325AS 500GB                            | 4        | 0.42%   |
| Seagate ST3500418AS 500GB                            | 4        | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB                       | 4        | 0.42%   |
| Seagate ST1000DM003-1ER162 1TB                       | 4        | 0.42%   |
| Samsung SSD 990 PRO 1TB                              | 4        | 0.42%   |
| Samsung SSD 980 500GB                                | 4        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 163      | 314    | 44.9%   |
| WDC                 | 138      | 234    | 38.02%  |
| Hitachi             | 18       | 27     | 4.96%   |
| Toshiba             | 14       | 21     | 3.86%   |
| Samsung Electronics | 5        | 7      | 1.38%   |
| HGST                | 5        | 7      | 1.38%   |
| TO Exter            | 3        | 3      | 0.83%   |
| External            | 3        | 4      | 0.83%   |
| Unknown             | 2        | 2      | 0.55%   |
| JMicron Technology  | 2        | 2      | 0.55%   |
| Hewlett-Packard     | 2        | 3      | 0.55%   |
| ASMT                | 2        | 2      | 0.55%   |
| Apple               | 2        | 2      | 0.55%   |
| USB                 | 1        | 2      | 0.28%   |
| Unknown (CF)        | 1        | 1      | 0.28%   |
| QUANTUM             | 1        | 1      | 0.28%   |
| Fujitsu             | 1        | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 89       | 140    | 32.36%  |
| Crucial             | 46       | 66     | 16.73%  |
| Kingston            | 25       | 35     | 9.09%   |
| SanDisk             | 17       | 23     | 6.18%   |
| Intel               | 16       | 20     | 5.82%   |
| WDC                 | 13       | 25     | 4.73%   |
| A-DATA Technology   | 9        | 11     | 3.27%   |
| Team                | 6        | 6      | 2.18%   |
| Toshiba             | 5        | 5      | 1.82%   |
| OCZ                 | 5        | 6      | 1.82%   |
| Apacer              | 5        | 6      | 1.82%   |
| Micron Technology   | 4        | 5      | 1.45%   |
| Lexar               | 4        | 9      | 1.45%   |
| Gigabyte Technology | 4        | 4      | 1.45%   |
| Seagate             | 3        | 6      | 1.09%   |
| Corsair             | 3        | 5      | 1.09%   |
| China               | 3        | 4      | 1.09%   |
| T-FORCE             | 2        | 2      | 0.73%   |
| LITEON              | 2        | 2      | 0.73%   |
| KingSpec            | 2        | 2      | 0.73%   |
| Hewlett-Packard     | 2        | 3      | 0.73%   |
| Transcend           | 1        | 1      | 0.36%   |
| SK hynix            | 1        | 1      | 0.36%   |
| PNY                 | 1        | 2      | 0.36%   |
| OCZ-VERTEX3         | 1        | 1      | 0.36%   |
| Innodisk            | 1        | 1      | 0.36%   |
| GAMER               | 1        | 1      | 0.36%   |
| FreeNAS             | 1        | 36     | 0.36%   |
| FreeBSD             | 1        | 372    | 0.36%   |
| Apple               | 1        | 1      | 0.36%   |
| Unknown             | 1        | 1      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 278      | 633    | 42.31%  |
| SSD     | 230      | 802    | 35.01%  |
| NVMe    | 139      | 280    | 21.16%  |
| Unknown | 8        | 13     | 1.22%   |
| MMC     | 2        | 2      | 0.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 369      | 1378   | 66.49%  |
| NVMe | 139      | 280    | 25.05%  |
| SAS  | 45       | 70     | 8.11%   |
| MMC  | 2        | 2      | 0.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 276      | 899    | 46.15%  |
| 0.51-1.0   | 165      | 284    | 27.59%  |
| 1.01-2.0   | 86       | 141    | 14.38%  |
| 3.01-4.0   | 31       | 53     | 5.18%   |
| 4.01-10.0  | 20       | 28     | 3.34%   |
| 2.01-3.0   | 16       | 19     | 2.68%   |
| 10.01-20.0 | 3        | 8      | 0.5%    |
| 20.01-50.0 | 1        | 3      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 89       | 19.96%  |
| 251-500        | 67       | 15.02%  |
| 501-1000       | 64       | 14.35%  |
| More than 3000 | 60       | 13.45%  |
| 1001-2000      | 60       | 13.45%  |
| 2001-3000      | 42       | 9.42%   |
| 1-20           | 30       | 6.73%   |
| 51-100         | 14       | 3.14%   |
| Unknown        | 14       | 3.14%   |
| 21-50          | 6        | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 137      | 29.15%  |
| 21-50          | 66       | 14.04%  |
| 101-250        | 48       | 10.21%  |
| 51-100         | 45       | 9.57%   |
| 501-1000       | 44       | 9.36%   |
| 251-500        | 38       | 8.09%   |
| 1001-2000      | 35       | 7.45%   |
| More than 3000 | 23       | 4.89%   |
| 2001-3000      | 20       | 4.26%   |
| Unknown        | 14       | 2.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB              | 3        | 3      | 5.66%   |
| WDC WD5000AAKX-001CA0 500GB           | 2        | 3      | 3.77%   |
| WDC WD3200AAKS-00L9A0 320GB           | 2        | 2      | 3.77%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 2        | 2      | 3.77%   |
| WDC WD20EARX-00PASB0 2TB              | 2        | 3      | 3.77%   |
| Seagate ST3500418AS 500GB             | 2        | 3      | 3.77%   |
| Seagate ST31000524AS 1TB              | 2        | 2      | 3.77%   |
| Samsung Electronics SSD 980 1TB       | 2        | 3      | 3.77%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1        | 1      | 1.89%   |
| WDC WD40EFAX-68JH4N0 4TB              | 1        | 1      | 1.89%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1        | 1      | 1.89%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1        | 1      | 1.89%   |
| WDC WD15EARS-00S0XB0 1TB              | 1        | 1      | 1.89%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1        | 3      | 1.89%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 1      | 1.89%   |
| WDC WD10EARS-003BB1 1TB               | 1        | 1      | 1.89%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 2      | 1.89%   |
| Toshiba MQ01ABD100 1TB                | 1        | 1      | 1.89%   |
| Toshiba MQ01ABD050 500GB              | 1        | 1      | 1.89%   |
| SK hynix HFS256G32MND-2900A 256GB SSD | 1        | 1      | 1.89%   |
| Seagate ST8000VN0022-2EL112 8TB       | 1        | 3      | 1.89%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 1.89%   |
| Seagate ST4000DX001-1CE168 4TB        | 1        | 1      | 1.89%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 1.89%   |
| Seagate ST3200822A 200GB              | 1        | 1      | 1.89%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 1.89%   |
| Seagate ST2000DX002-2DV164 2TB        | 1        | 1      | 1.89%   |
| Seagate ST2000DX001-1CM164 2TB        | 1        | 1      | 1.89%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 1.89%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 1.89%   |
| Seagate ST1000DM003-9YN162 1TB        | 1        | 1      | 1.89%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 1.89%   |
| SanDisk SSD PLUS 240 GB               | 1        | 1      | 1.89%   |
| Samsung Electronics SSD 980 PRO 2TB   | 1        | 1      | 1.89%   |
| Samsung Electronics SSD 980 PRO 250GB | 1        | 1      | 1.89%   |
| OCZ VERTEX3 90GB SSD                  | 1        | 1      | 1.89%   |
| Intel SSDSC2CT240A4 240GB             | 1        | 1      | 1.89%   |
| Innodisk Corp. - mSATA 3ME4 128GB     | 1        | 1      | 1.89%   |
| Hitachi HTS541010A9E680 1TB           | 1        | 1      | 1.89%   |
| HGST HTS545050A7E380 500GB            | 1        | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 22     | 34.69%  |
| Seagate             | 15       | 22     | 30.61%  |
| Samsung Electronics | 4        | 5      | 8.16%   |
| Crucial             | 3        | 4      | 6.12%   |
| Toshiba             | 2        | 2      | 4.08%   |
| SK hynix            | 1        | 1      | 2.04%   |
| SanDisk             | 1        | 1      | 2.04%   |
| OCZ                 | 1        | 1      | 2.04%   |
| Intel               | 1        | 1      | 2.04%   |
| Innodisk            | 1        | 1      | 2.04%   |
| Hitachi             | 1        | 1      | 2.04%   |
| HGST                | 1        | 1      | 2.04%   |
| ASMT                | 1        | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 16       | 21     | 44.44%  |
| Seagate | 15       | 22     | 41.67%  |
| Toshiba | 2        | 2      | 5.56%   |
| Hitachi | 1        | 1      | 2.78%   |
| HGST    | 1        | 1      | 2.78%   |
| ASMT    | 1        | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 34       | 48     | 72.34%  |
| SSD  | 9        | 10     | 19.15%  |
| NVMe | 4        | 5      | 8.51%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| WDC WD20EARS-00S8B1 2TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 259      | 787    | 55.22%  |
| Works    | 163      | 878    | 34.75%  |
| Malfunc  | 45       | 63     | 9.59%   |
| Failed   | 1        | 1      | 0.21%   |
| Limited  | 1        | 1      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 249      | 39.9%   |
| AMD                          | 146      | 23.4%   |
| Samsung Electronics          | 80       | 12.82%  |
| JMicron Technology           | 17       | 2.72%   |
| Kingston Technology Company  | 16       | 2.56%   |
| ASMedia Technology           | 16       | 2.56%   |
| Micron/Crucial Technology    | 15       | 2.4%    |
| Marvell Technology Group     | 13       | 2.08%   |
| SanDisk                      | 11       | 1.76%   |
| Nvidia                       | 10       | 1.6%    |
| Seagate Technology           | 6        | 0.96%   |
| Phison Electronics           | 6        | 0.96%   |
| SK hynix                     | 5        | 0.8%    |
| Silicon Motion               | 4        | 0.64%   |
| Shenzhen Longsys Electronics | 4        | 0.64%   |
| Micron Technology            | 4        | 0.64%   |
| Toshiba America Info Systems | 3        | 0.48%   |
| MAXIO Technology (Hangzhou)  | 3        | 0.48%   |
| LSI Logic / Symbios Logic    | 3        | 0.48%   |
| ADATA Technology             | 3        | 0.48%   |
| Realtek Semiconductor        | 2        | 0.32%   |
| KIOXIA                       | 2        | 0.32%   |
| Hewlett-Packard              | 2        | 0.32%   |
| VIA Technologies             | 1        | 0.16%   |
| Silicon Image                | 1        | 0.16%   |
| OCZ Technology Group         | 1        | 0.16%   |
| Broadcom / LSI               | 1        | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 67       | 8.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 34       | 4.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 30       | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26       | 3.33%   |
| AMD 500 Series Chipset SATA Controller                                                  | 26       | 3.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 22       | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 22       | 2.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 21       | 2.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 20       | 2.56%   |
| Intel SATA Controller [RAID mode]                                                       | 20       | 2.56%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 19       | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 19       | 2.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15       | 1.92%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 15       | 1.92%   |
| AMD 600 Series Chipset SATA Controller                                                  | 14       | 1.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 1.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 11       | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 1.41%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 10       | 1.28%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 10       | 1.28%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 9        | 1.15%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8        | 1.03%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 1.03%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 8        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 8        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 8        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.03%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 7        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7        | 0.9%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 0.9%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 6        | 0.77%   |
| JMicron JMB368 IDE controller                                                           | 6        | 0.77%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 336      | 54.99%  |
| NVMe | 141      | 23.08%  |
| IDE  | 98       | 16.04%  |
| RAID | 31       | 5.07%   |
| SAS  | 3        | 0.49%   |
| SCSI | 2        | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 254      | 61.95%  |
| AMD    | 156      | 38.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 12       | 2.93%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 11       | 2.68%   |
| AMD Ryzen 5 3600 6-Core Processor           | 10       | 2.44%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 1.95%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 1.71%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 7        | 1.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 1.46%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 1.22%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 5        | 1.22%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 5        | 1.22%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 5        | 1.22%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 5        | 1.22%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 1.22%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 1.22%   |
| Intel N100                                  | 4        | 0.98%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 0.98%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 4        | 0.98%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 0.98%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 4        | 0.98%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.98%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 4        | 0.98%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 4        | 0.98%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 0.98%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 0.98%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 0.98%   |
| AMD FX-6300 Six-Core Processor              | 4        | 0.98%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 0.73%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 3        | 0.73%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.73%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 3        | 0.73%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 0.73%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 3        | 0.73%   |
| AMD Ryzen 7 7800X3D 8-Core Processor        | 3        | 0.73%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 0.73%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.73%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.73%   |
| AMD FX-8320 Eight-Core Processor            | 3        | 0.73%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.49%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 2        | 0.49%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 85       | 20.73%  |
| Intel Core i7           | 64       | 15.61%  |
| AMD Ryzen 5             | 40       | 9.76%   |
| AMD Ryzen 7             | 32       | 7.8%    |
| Intel Core i3           | 24       | 5.85%   |
| AMD Ryzen 9             | 22       | 5.37%   |
| Intel Xeon              | 21       | 5.12%   |
| AMD FX                  | 19       | 4.63%   |
| Other                   | 16       | 3.9%    |
| Intel Core 2 Quad       | 11       | 2.68%   |
| Intel Core 2 Duo        | 9        | 2.2%    |
| Intel Pentium           | 6        | 1.46%   |
| AMD Ryzen 3             | 6        | 1.46%   |
| Intel Atom              | 5        | 1.22%   |
| AMD Athlon II X2        | 5        | 1.22%   |
| AMD Athlon 64 X2        | 5        | 1.22%   |
| Intel Core i9           | 4        | 0.98%   |
| AMD Ryzen Threadripper  | 4        | 0.98%   |
| Intel Pentium Dual-Core | 3        | 0.73%   |
| Intel Celeron           | 3        | 0.73%   |
| AMD Phenom II X6        | 3        | 0.73%   |
| AMD A8                  | 3        | 0.73%   |
| AMD Ryzen 5 PRO         | 2        | 0.49%   |
| AMD Phenom II X4        | 2        | 0.49%   |
| AMD Athlon II X4        | 2        | 0.49%   |
| AMD A6                  | 2        | 0.49%   |
| AMD A4                  | 2        | 0.49%   |
| Intel Pentium Gold      | 1        | 0.24%   |
| Intel Pentium Dual      | 1        | 0.24%   |
| Intel Pentium 4         | 1        | 0.24%   |
| AMD Six-Core Opteron    | 1        | 0.24%   |
| AMD Ryzen 7 PRO         | 1        | 0.24%   |
| AMD Opteron             | 1        | 0.24%   |
| AMD GX                  | 1        | 0.24%   |
| AMD Geode Integrated    | 1        | 0.24%   |
| AMD A12                 | 1        | 0.24%   |
| AMD A10                 | 1        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 174      | 42.23%  |
| 6      | 71       | 17.23%  |
| 2      | 65       | 15.78%  |
| 8      | 48       | 11.65%  |
| 12     | 21       | 5.1%    |
| 16     | 11       | 2.67%   |
| 3      | 6        | 1.46%   |
| 1      | 5        | 1.21%   |
| 24     | 4        | 0.97%   |
| 10     | 4        | 0.97%   |
| 20     | 2        | 0.49%   |
| 14     | 1        | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 408      | 99.51%  |
| 2      | 2        | 0.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 259      | 63.02%  |
| 1      | 152      | 36.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 405      | 98.3%   |
| Unknown        | 6        | 1.46%   |
| 32-bit         | 1        | 0.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 185      | 42.82%  |
| 0x306a9    | 24       | 5.56%   |
| 0x306c3    | 22       | 5.09%   |
| 0x206a7    | 16       | 3.7%    |
| 0x08701021 | 15       | 3.47%   |
| 0x1067a    | 11       | 2.55%   |
| 0x06000852 | 10       | 2.31%   |
| 0x0800820d | 8        | 1.85%   |
| 0x106e5    | 7        | 1.62%   |
| 0xa0655    | 6        | 1.39%   |
| 0x906e9    | 6        | 1.39%   |
| 0x0a601203 | 6        | 1.39%   |
| 0x906ea    | 5        | 1.16%   |
| 0x506e3    | 5        | 1.16%   |
| 0x0a50000c | 5        | 1.16%   |
| 0x08001137 | 5        | 1.16%   |
| 0x206d7    | 4        | 0.93%   |
| 0x106a5    | 4        | 0.93%   |
| 0x0a201016 | 4        | 0.93%   |
| 0x08701013 | 4        | 0.93%   |
| 0x010000c8 | 4        | 0.93%   |
| 0x6fb      | 3        | 0.69%   |
| 0x20655    | 3        | 0.69%   |
| 0x0a201009 | 3        | 0.69%   |
| 0x06001119 | 3        | 0.69%   |
| 0x906ed    | 2        | 0.46%   |
| 0x50654    | 2        | 0.46%   |
| 0x406c3    | 2        | 0.46%   |
| 0x40651    | 2        | 0.46%   |
| 0x306f2    | 2        | 0.46%   |
| 0x20652    | 2        | 0.46%   |
| 0x10677    | 2        | 0.46%   |
| 0x0a50000d | 2        | 0.46%   |
| 0x0a20120a | 2        | 0.46%   |
| 0x0a201025 | 2        | 0.46%   |
| 0x08600106 | 2        | 0.46%   |
| 0x08108109 | 2        | 0.46%   |
| 0x08001138 | 2        | 0.46%   |
| 0x08001129 | 2        | 0.46%   |
| 0x0700010f | 2        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 45       | 10.98%  |
| IvyBridge        | 38       | 9.27%   |
| Zen 2            | 32       | 7.8%    |
| SandyBridge      | 32       | 7.8%    |
| KabyLake         | 32       | 7.8%    |
| Zen 3            | 30       | 7.32%   |
| Unknown          | 30       | 7.32%   |
| Piledriver       | 21       | 5.12%   |
| Penryn           | 20       | 4.88%   |
| Zen+             | 16       | 3.9%    |
| Zen              | 15       | 3.66%   |
| Skylake          | 15       | 3.66%   |
| CometLake        | 15       | 3.66%   |
| Nehalem          | 13       | 3.17%   |
| K10              | 13       | 3.17%   |
| Westmere         | 7        | 1.71%   |
| Core             | 7        | 1.71%   |
| K8 Hammer        | 5        | 1.22%   |
| Bulldozer        | 5        | 1.22%   |
| Silvermont       | 4        | 0.98%   |
| Alderlake Hybrid | 3        | 0.73%   |
| Jaguar           | 2        | 0.49%   |
| Bonnell          | 2        | 0.49%   |
| Tremont          | 1        | 0.24%   |
| NetBurst         | 1        | 0.24%   |
| K10 Llano        | 1        | 0.24%   |
| Icelake          | 1        | 0.24%   |
| Gracemont        | 1        | 0.24%   |
| Goldmont         | 1        | 0.24%   |
| Geode            | 1        | 0.24%   |
| Excavator        | 1        | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 165      | 36.75%  |
| AMD                        | 151      | 33.63%  |
| Intel                      | 127      | 28.29%  |
| Matrox Electronics Systems | 5        | 1.11%   |
| ASPEED Technology          | 1        | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 22       | 4.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 22       | 4.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 16       | 3.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 13       | 2.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 2.35%   |
| AMD Raphael                                                                 | 11       | 2.35%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 10       | 2.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 1.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 9        | 1.92%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 1.71%   |
| Intel HD Graphics 530                                                       | 8        | 1.71%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 8        | 1.71%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 1.49%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 7        | 1.49%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 1.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7        | 1.49%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 1.28%   |
| Intel HD Graphics 630                                                       | 6        | 1.28%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 1.07%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 5        | 1.07%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5        | 1.07%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 5        | 1.07%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 5        | 1.07%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.85%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 0.85%   |
| Nvidia GF108 [GeForce GT 430]                                               | 4        | 0.85%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 4        | 0.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 0.85%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 4        | 0.85%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 4        | 0.85%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 4        | 0.85%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 4        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 0.64%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.64%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 3        | 0.64%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 3        | 0.64%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| 1 x Nvidia       | 147      | 35.08%  |
| 1 x AMD          | 123      | 29.36%  |
| 1 x Intel        | 103      | 24.58%  |
| 2 x AMD          | 11       | 2.63%   |
| AMD + Nvidia     | 10       | 2.39%   |
| Intel + AMD      | 8        | 1.91%   |
| 1 x Matrox       | 5        | 1.19%   |
| Intel + Nvidia   | 5        | 1.19%   |
| 2 x Nvidia       | 3        | 0.72%   |
| Other            | 1        | 0.24%   |
| 2 x Intel        | 1        | 0.24%   |
| AMD + 2 x Nvidia | 1        | 0.24%   |
| AMD + ASPEED     | 1        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 299      | 71.53%  |
| Proprietary | 105      | 25.12%  |
| Unknown     | 14       | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 198      | 46.37%  |
| 1.01-2.0   | 51       | 11.94%  |
| 7.01-8.0   | 40       | 9.37%   |
| 0.01-0.5   | 39       | 9.13%   |
| 0.51-1.0   | 31       | 7.26%   |
| 3.01-4.0   | 26       | 6.09%   |
| 8.01-16.0  | 20       | 4.68%   |
| 5.01-6.0   | 16       | 3.75%   |
| 2.01-3.0   | 4        | 0.94%   |
| 16.01-24.0 | 2        | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 78       | 16.46%  |
| AOC                     | 58       | 12.24%  |
| Goldstar                | 54       | 11.39%  |
| Dell                    | 53       | 11.18%  |
| Philips                 | 38       | 8.02%   |
| ViewSonic               | 28       | 5.91%   |
| Hewlett-Packard         | 25       | 5.27%   |
| Panasonic               | 14       | 2.95%   |
| BenQ                    | 14       | 2.95%   |
| Acer                    | 14       | 2.95%   |
| Sony                    | 13       | 2.74%   |
| Lenovo                  | 11       | 2.32%   |
| Ancor Communications    | 10       | 2.11%   |
| Denver                  | 8        | 1.69%   |
| MiTAC                   | 7        | 1.48%   |
| ASUSTek Computer        | 6        | 1.27%   |
| Gigabyte Technology     | 5        | 1.05%   |
| LG Electronics          | 4        | 0.84%   |
| Unknown                 | 3        | 0.63%   |
| Unknown                 | 3        | 0.63%   |
| Unknown (AAA)           | 2        | 0.42%   |
| MSI                     | 2        | 0.42%   |
| Konka                   | 2        | 0.42%   |
| Chi Mei Optoelectronics | 2        | 0.42%   |
| Yamaha                  | 1        | 0.21%   |
| Targa                   | 1        | 0.21%   |
| SANYO                   | 1        | 0.21%   |
| PPC                     | 1        | 0.21%   |
| Plain Tree Systems      | 1        | 0.21%   |
| NEC Computers           | 1        | 0.21%   |
| Mi                      | 1        | 0.21%   |
| Marantz                 | 1        | 0.21%   |
| KTC                     | 1        | 0.21%   |
| KON                     | 1        | 0.21%   |
| JINGLITAI               | 1        | 0.21%   |
| Iiyama                  | 1        | 0.21%   |
| Hyundai ImageQuest      | 1        | 0.21%   |
| GVV                     | 1        | 0.21%   |
| eMachines               | 1        | 0.21%   |
| Elo Touch               | 1        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 8        | 1.52%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 6        | 1.14%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 6        | 1.14%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                   | 6        | 1.14%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 5        | 0.95%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 5        | 0.95%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch               | 5        | 0.95%   |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch        | 4        | 0.76%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch              | 4        | 0.76%   |
| MiTAC MStar Demo SZM0030 3840x2160 708x398mm 32.0-inch               | 4        | 0.76%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch               | 4        | 0.76%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                    | 4        | 0.76%   |
| Sony TV SNYEE01 1920x1080                                            | 3        | 0.57%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch    | 3        | 0.57%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 3        | 0.57%   |
| Hewlett-Packard P221 HWP3057 1920x1080 476x268mm 21.5-inch           | 3        | 0.57%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 3        | 0.57%   |
| Denver M27-QHD-144-C LHC2700 2560x1440 597x336mm 27.0-inch           | 3        | 0.57%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 3        | 0.57%   |
| AOC 2367 AOC2367 1920x1080 509x286mm 23.0-inch                       | 3        | 0.57%   |
| Unknown                                                              | 3        | 0.57%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch             | 2        | 0.38%   |
| ViewSonic VX2240w VSC6B20 1680x1050 495x291mm 22.6-inch              | 2        | 0.38%   |
| ViewSonic VA702-3SERIES VSCB51D 1280x1024 338x270mm 17.0-inch        | 2        | 0.38%   |
| ViewSonic VA2231 Series VSCBB25 1920x1080 477x268mm 21.5-inch        | 2        | 0.38%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 2        | 0.38%   |
| Sony TV SNYEF03 1600x900                                             | 2        | 0.38%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch | 2        | 0.38%   |
| Samsung Electronics S24B350 SAM08DA 1920x1080 530x300mm 24.0-inch    | 2        | 0.38%   |
| Samsung Electronics LF24T370F SAM711B 1920x1080 527x296mm 23.8-inch  | 2        | 0.38%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch | 2        | 0.38%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                  | 2        | 0.38%   |
| Konka LCDTV KOA0030 1360x850 708x398mm 32.0-inch                     | 2        | 0.38%   |
| Goldstar W1941 GSM4B91 1360x768 406x229mm 18.4-inch                  | 2        | 0.38%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch             | 2        | 0.38%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 2        | 0.38%   |
| Goldstar E2351 GSM5872 1920x1080 510x290mm 23.1-inch                 | 2        | 0.38%   |
| Denver UWQHD-100-C LHC3400 3440x1440 795x334mm 33.9-inch             | 2        | 0.38%   |
| Dell G2410 DEL404B 1920x1080 531x298mm 24.0-inch                     | 2        | 0.38%   |
| Dell E228WFP DELD014 1680x1050 473x296mm 22.0-inch                   | 2        | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 196      | 41.97%  |
| 3840x2160 (4K)     | 75       | 16.06%  |
| 2560x1440 (QHD)    | 33       | 7.07%   |
| 1680x1050 (WSXGA+) | 32       | 6.85%   |
| 1280x1024 (SXGA)   | 25       | 5.35%   |
| 1440x900 (WXGA+)   | 17       | 3.64%   |
| Unknown            | 16       | 3.43%   |
| 3440x1440          | 12       | 2.57%   |
| 3840x1080          | 10       | 2.14%   |
| 1600x900 (HD+)     | 10       | 2.14%   |
| 1366x768 (WXGA)    | 7        | 1.5%    |
| 1920x1200 (WUXGA)  | 5        | 1.07%   |
| 1360x768           | 5        | 1.07%   |
| 2560x1080          | 3        | 0.64%   |
| 2560x1600          | 2        | 0.43%   |
| 2288x1287          | 2        | 0.43%   |
| 1920x540           | 2        | 0.43%   |
| 1600x1200          | 2        | 0.43%   |
| 7680x1080          | 1        | 0.21%   |
| 6720x1080          | 1        | 0.21%   |
| 5760x1080          | 1        | 0.21%   |
| 5120x1080          | 1        | 0.21%   |
| 3840x1600          | 1        | 0.21%   |
| 3840x1200          | 1        | 0.21%   |
| 3360x1080          | 1        | 0.21%   |
| 3040x1050          | 1        | 0.21%   |
| 2960x1050          | 1        | 0.21%   |
| 2560x1024          | 1        | 0.21%   |
| 2048x1152          | 1        | 0.21%   |
| 1280x800 (WXGA)    | 1        | 0.21%   |
| 1024x768 (XGA)     | 1        | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 73       | 15.47%  |
| 23      | 62       | 13.14%  |
| 24      | 56       | 11.86%  |
| 21      | 53       | 11.23%  |
| Unknown | 41       | 8.69%   |
| 31      | 35       | 7.42%   |
| 22      | 23       | 4.87%   |
| 19      | 22       | 4.66%   |
| 20      | 15       | 3.18%   |
| 17      | 15       | 3.18%   |
| 84      | 12       | 2.54%   |
| 34      | 11       | 2.33%   |
| 72      | 9        | 1.91%   |
| 18      | 8        | 1.69%   |
| 32      | 7        | 1.48%   |
| 52      | 3        | 0.64%   |
| 46      | 3        | 0.64%   |
| 40      | 3        | 0.64%   |
| 35      | 3        | 0.64%   |
| 142     | 2        | 0.42%   |
| 36      | 2        | 0.42%   |
| 15      | 2        | 0.42%   |
| 65      | 1        | 0.21%   |
| 54      | 1        | 0.21%   |
| 49      | 1        | 0.21%   |
| 48      | 1        | 0.21%   |
| 42      | 1        | 0.21%   |
| 37      | 1        | 0.21%   |
| 33      | 1        | 0.21%   |
| 30      | 1        | 0.21%   |
| 29      | 1        | 0.21%   |
| 28      | 1        | 0.21%   |
| 26      | 1        | 0.21%   |
| 16      | 1        | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 164      | 36.2%   |
| 401-500        | 109      | 24.06%  |
| 601-700        | 52       | 11.48%  |
| Unknown        | 41       | 9.05%   |
| 701-800        | 21       | 4.64%   |
| 1501-2000      | 19       | 4.19%   |
| 301-350        | 17       | 3.75%   |
| 351-400        | 10       | 2.21%   |
| 1001-1500      | 10       | 2.21%   |
| 801-900        | 7        | 1.55%   |
| More than 2000 | 2        | 0.44%   |
| 901-1000       | 1        | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 275      | 66.11%  |
| 16/10   | 56       | 13.46%  |
| Unknown | 35       | 8.41%   |
| 5/4     | 23       | 5.53%   |
| 21/9    | 15       | 3.61%   |
| 32/9    | 4        | 0.96%   |
| 4/3     | 3        | 0.72%   |
| 6/5     | 2        | 0.48%   |
| 1.00    | 2        | 0.48%   |
| 3/2     | 1        | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 158      | 34.65%  |
| 301-350        | 73       | 16.01%  |
| 351-500        | 60       | 13.16%  |
| 151-200        | 51       | 11.18%  |
| Unknown        | 41       | 8.99%   |
| More than 1000 | 25       | 5.48%   |
| 141-150        | 18       | 3.95%   |
| 251-300        | 14       | 3.07%   |
| 501-1000       | 12       | 2.63%   |
| 101-110        | 2        | 0.44%   |
| 131-140        | 1        | 0.22%   |
| 121-130        | 1        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 252      | 57.01%  |
| 101-120 | 81       | 18.33%  |
| Unknown | 41       | 9.28%   |
| 121-160 | 33       | 7.47%   |
| 1-50    | 25       | 5.66%   |
| 161-240 | 10       | 2.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 296      | 68.84%  |
| 2     | 100      | 23.26%  |
| 0     | 21       | 4.88%   |
| 3     | 10       | 2.33%   |
| 4     | 2        | 0.47%   |
| 5     | 1        | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 251      | 39.78%  |
| Intel                                 | 200      | 31.7%   |
| Qualcomm Atheros                      | 30       | 4.75%   |
| TP-Link                               | 19       | 3.01%   |
| MediaTek                              | 18       | 2.85%   |
| Broadcom                              | 16       | 2.54%   |
| Ralink Technology                     | 15       | 2.38%   |
| Ralink                                | 11       | 1.74%   |
| Nvidia                                | 8        | 1.27%   |
| Marvell Technology Group              | 8        | 1.27%   |
| NetGear                               | 6        | 0.95%   |
| Microsoft                             | 5        | 0.79%   |
| Samsung Electronics                   | 4        | 0.63%   |
| Qualcomm Atheros Communications       | 4        | 0.63%   |
| Aquantia                              | 4        | 0.63%   |
| Edimax Technology                     | 3        | 0.48%   |
| OPPO Electronics                      | 2        | 0.32%   |
| Microchip Technology                  | 2        | 0.32%   |
| IBM                                   | 2        | 0.32%   |
| D-Link                                | 2        | 0.32%   |
| Broadcom Limited                      | 2        | 0.32%   |
| ASUSTek Computer                      | 2        | 0.32%   |
| ASIX Electronics                      | 2        | 0.32%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.16%   |
| Wilocity                              | 1        | 0.16%   |
| VIA Technologies                      | 1        | 0.16%   |
| Realtek                               | 1        | 0.16%   |
| Raspberry Pi                          | 1        | 0.16%   |
| Qualcomm Technologies                 | 1        | 0.16%   |
| Mellanox Technologies                 | 1        | 0.16%   |
| MCS                                   | 1        | 0.16%   |
| Huawei Technologies                   | 1        | 0.16%   |
| DisplayLink                           | 1        | 0.16%   |
| Conexant Systems                      | 1        | 0.16%   |
| Bose                                  | 1        | 0.16%   |
| Belkin Components                     | 1        | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.16%   |
| 3Com                                  | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 183      | 26.37%  |
| Realtek RTL8125 2.5GbE Controller                                      | 40       | 5.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 30       | 4.32%   |
| Intel Wi-Fi 6 AX200                                                    | 25       | 3.6%    |
| Intel I211 Gigabit Network Connection                                  | 24       | 3.46%   |
| Intel Ethernet Connection I217-LM                                      | 12       | 1.73%   |
| Intel Ethernet Controller I225-V                                       | 11       | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                   | 11       | 1.59%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 10       | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 8        | 1.15%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 8        | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 7        | 1.01%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 7        | 1.01%   |
| Intel Ethernet Connection (2) I218-V                                   | 7        | 1.01%   |
| Intel 82574L Gigabit Network Connection                                | 7        | 1.01%   |
| Ralink MT7601U Wireless Adapter                                        | 6        | 0.86%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 6        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6        | 0.86%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                  | 5        | 0.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 5        | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5        | 0.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5        | 0.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 5        | 0.72%   |
| Intel Wireless 8265 / 8275                                             | 5        | 0.72%   |
| Intel 82579V Gigabit Network Connection                                | 5        | 0.72%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 4        | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 4        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 0.58%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 0.58%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 4        | 0.58%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 4        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3        | 0.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3        | 0.43%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 3        | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.43%   |
| Realtek 802.11ac NIC                                                   | 3        | 0.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 3        | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 73       | 33.03%  |
| Realtek Semiconductor                 | 43       | 19.46%  |
| TP-Link                               | 19       | 8.6%    |
| Ralink Technology                     | 15       | 6.79%   |
| Qualcomm Atheros                      | 13       | 5.88%   |
| MediaTek                              | 12       | 5.43%   |
| Ralink                                | 11       | 4.98%   |
| Broadcom                              | 8        | 3.62%   |
| NetGear                               | 6        | 2.71%   |
| Microsoft                             | 5        | 2.26%   |
| Qualcomm Atheros Communications       | 4        | 1.81%   |
| Edimax Technology                     | 3        | 1.36%   |
| D-Link                                | 2        | 0.9%    |
| ASUSTek Computer                      | 2        | 0.9%    |
| Wilocity                              | 1        | 0.45%   |
| Realtek                               | 1        | 0.45%   |
| Qualcomm Technologies                 | 1        | 0.45%   |
| Belkin Components                     | 1        | 0.45%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 25       | 11.06%  |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                   | 10       | 4.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 8        | 3.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 7        | 3.1%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                 | 7        | 3.1%    |
| Ralink MT7601U Wireless Adapter                                           | 6        | 2.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 6        | 2.65%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                     | 5        | 2.21%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                  | 5        | 2.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 5        | 2.21%   |
| Intel Wireless 8265 / 8275                                                | 5        | 2.21%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                       | 4        | 1.77%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                | 4        | 1.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 4        | 1.77%   |
| Microsoft Xbox Wireless Adapter for Windows                               | 4        | 1.77%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                         | 4        | 1.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 3        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 3        | 1.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                           | 3        | 1.33%   |
| Realtek 802.11ac NIC                                                      | 3        | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3        | 1.33%   |
| Qualcomm Atheros AR9271 802.11n                                           | 3        | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 3        | 1.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter             | 3        | 1.33%   |
| Intel Wireless 7265                                                       | 3        | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3        | 1.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 3        | 1.33%   |
| TP-Link Archer T4U ver.3                                                  | 2        | 0.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 2        | 0.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 2        | 0.88%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 2        | 0.88%   |
| Ralink RT5370 Wireless Adapter                                            | 2        | 0.88%   |
| Ralink RT5392 PCIe Wireless Network Adapter                               | 2        | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                 | 2        | 0.88%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                 | 2        | 0.88%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                 | 2        | 0.88%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 2        | 0.88%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                         | 2        | 0.88%   |
| Intel Wireless 7260                                                       | 2        | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 2        | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 229      | 50.89%  |
| Intel                      | 152      | 33.78%  |
| Qualcomm Atheros           | 19       | 4.22%   |
| Broadcom                   | 9        | 2%      |
| Nvidia                     | 8        | 1.78%   |
| Marvell Technology Group   | 8        | 1.78%   |
| MediaTek                   | 5        | 1.11%   |
| Aquantia                   | 4        | 0.89%   |
| Samsung Electronics        | 2        | 0.44%   |
| OPPO Electronics           | 2        | 0.44%   |
| IBM                        | 2        | 0.44%   |
| Broadcom Limited           | 2        | 0.44%   |
| ASIX Electronics           | 2        | 0.44%   |
| ZTE WCDMA Technologies MSM | 1        | 0.22%   |
| VIA Technologies           | 1        | 0.22%   |
| Mellanox Technologies      | 1        | 0.22%   |
| Huawei Technologies        | 1        | 0.22%   |
| DisplayLink                | 1        | 0.22%   |
| 3Com                       | 1        | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 183      | 39.96%  |
| Realtek RTL8125 2.5GbE Controller                                              | 40       | 8.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 30       | 6.55%   |
| Intel I211 Gigabit Network Connection                                          | 24       | 5.24%   |
| Intel Ethernet Connection I217-LM                                              | 12       | 2.62%   |
| Intel Ethernet Controller I225-V                                               | 11       | 2.4%    |
| Intel Ethernet Connection (2) I219-V                                           | 11       | 2.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8        | 1.75%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 8        | 1.75%   |
| Intel Ethernet Connection (2) I218-V                                           | 7        | 1.53%   |
| Intel 82574L Gigabit Network Connection                                        | 7        | 1.53%   |
| Intel Ethernet Connection (7) I219-V                                           | 6        | 1.31%   |
| Intel Ethernet Connection (2) I219-LM                                          | 6        | 1.31%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 5        | 1.09%   |
| Intel 82579V Gigabit Network Connection                                        | 5        | 1.09%   |
| Nvidia MCP61 Ethernet                                                          | 4        | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3        | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3        | 0.66%   |
| Intel Ethernet Controller I226-V                                               | 3        | 0.66%   |
| Intel Ethernet Connection I217-V                                               | 3        | 0.66%   |
| Intel 82578DM Gigabit Network Connection                                       | 3        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2        | 0.44%   |
| OPPO OnePlus Nord 4                                                            | 2        | 0.44%   |
| Nvidia CK804 Ethernet Controller                                               | 2        | 0.44%   |
| MediaTek TANK2                                                                 | 2        | 0.44%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 2        | 0.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 2        | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2        | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2        | 0.44%   |
| Intel Ethernet Connection (14) I219-V                                          | 2        | 0.44%   |
| Intel Ethernet Connection (11) I219-V                                          | 2        | 0.44%   |
| IBM RNDIS/CDC ETHER                                                            | 2        | 0.44%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                                    | 2        | 0.44%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.44%   |
| ZTE WCDMA MSM Unisoc Phone                                                     | 1        | 0.22%   |
| VIA VT6105M [Rhine-III]                                                        | 1        | 0.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.22%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 408      | 65.81%  |
| WiFi     | 203      | 32.74%  |
| Modem    | 7        | 1.13%   |
| Unknown  | 2        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 327      | 75.69%  |
| WiFi     | 104      | 24.07%  |
| Modem    | 1        | 0.23%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 238      | 57.35%  |
| 2     | 150      | 36.14%  |
| 3     | 22       | 5.3%    |
| 4     | 4        | 0.96%   |
| 6     | 1        | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 345      | 81.95%  |
| Yes  | 76       | 18.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 69       | 45.7%   |
| Cambridge Silicon Radio         | 30       | 19.87%  |
| ASUSTek Computer                | 8        | 5.3%    |
| Realtek Semiconductor           | 7        | 4.64%   |
| MediaTek                        | 7        | 4.64%   |
| Broadcom                        | 7        | 4.64%   |
| Qualcomm Atheros Communications | 4        | 2.65%   |
| IMC Networks                    | 4        | 2.65%   |
| Foxconn / Hon Hai               | 4        | 2.65%   |
| Edimax Technology               | 3        | 1.99%   |
| TP-Link                         | 2        | 1.32%   |
| Ralink                          | 2        | 1.32%   |
| Integrated System Solution      | 1        | 0.66%   |
| HTC (High Tech Computer)        | 1        | 0.66%   |
| Creative Technology             | 1        | 0.66%   |
| Apple                           | 1        | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 30       | 19.61%  |
| Intel AX200 Bluetooth                                                | 21       | 13.73%  |
| Intel Bluetooth wireless interface                                   | 11       | 7.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 10       | 6.54%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 8        | 5.23%   |
| Intel AX210 Bluetooth                                                | 8        | 5.23%   |
| MediaTek Wireless_Device                                             | 7        | 4.58%   |
| Realtek Bluetooth Radio                                              | 5        | 3.27%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 3.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4        | 2.61%   |
| Intel AX211 Bluetooth                                                | 4        | 2.61%   |
| Intel AX201 Bluetooth                                                | 4        | 2.61%   |
| IMC Networks Wireless_Device                                         | 3        | 1.96%   |
| Foxconn / Hon Hai Wireless_Device                                    | 3        | 1.96%   |
| Edimax Bluetooth Adapter                                             | 3        | 1.96%   |
| ASUS Bluetooth Radio                                                 | 3        | 1.96%   |
| TP-Link TP-Link Bluetooth USB Adapter                                | 2        | 1.31%   |
| Ralink RT3290 Bluetooth                                              | 2        | 1.31%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 1.31%   |
| Broadcom HP Portable Bumble Bee                                      | 2        | 1.31%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.65%   |
| Realtek 802.11ac WLAN Adapter                                        | 1        | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.65%   |
| Intel Bluetooth Device                                               | 1        | 0.65%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.65%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.65%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.65%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1        | 0.65%   |
| Creative Bluetooth Audio W2                                          | 1        | 0.65%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.65%   |
| ASUS Bluetooth Device                                                | 1        | 0.65%   |
| ASUS Bluetooth Adapter                                               | 1        | 0.65%   |
| ASUS BCM20702A0                                                      | 1        | 0.65%   |
| ASUS ASUS USB-BT500                                                  | 1        | 0.65%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 244      | 34.22%  |
| AMD                                          | 202      | 28.33%  |
| Nvidia                                       | 159      | 22.3%   |
| Logitech                                     | 19       | 2.66%   |
| C-Media Electronics                          | 19       | 2.66%   |
| SteelSeries ApS                              | 6        | 0.84%   |
| Kingston Technology                          | 6        | 0.84%   |
| Razer USA                                    | 4        | 0.56%   |
| Generalplus Technology                       | 4        | 0.56%   |
| JMTek                                        | 3        | 0.42%   |
| GN Netcom                                    | 3        | 0.42%   |
| FiiO Electronics Technology                  | 3        | 0.42%   |
| ASUSTek Computer                             | 3        | 0.42%   |
| XMOS                                         | 2        | 0.28%   |
| Hewlett-Packard                              | 2        | 0.28%   |
| GYROCOM C&C                                  | 2        | 0.28%   |
| Dell                                         | 2        | 0.28%   |
| Creative Technology                          | 2        | 0.28%   |
| Audio-Technica                               | 2        | 0.28%   |
| AKAI Professional M.I.                       | 2        | 0.28%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.14%   |
| VIA Technologies                             | 1        | 0.14%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.14%   |
| Texas Instruments                            | 1        | 0.14%   |
| RODE Microphones                             | 1        | 0.14%   |
| RME                                          | 1        | 0.14%   |
| Numark                                       | 1        | 0.14%   |
| Microsoft                                    | 1        | 0.14%   |
| Micro Star International                     | 1        | 0.14%   |
| Medeli Electronics                           | 1        | 0.14%   |
| Lenovo                                       | 1        | 0.14%   |
| KTMicro                                      | 1        | 0.14%   |
| Jieli Technology                             | 1        | 0.14%   |
| Giga-Byte Technology                         | 1        | 0.14%   |
| Focusrite-Novation                           | 1        | 0.14%   |
| DSEA A/S                                     | 1        | 0.14%   |
| Creative Labs                                | 1        | 0.14%   |
| Cambridge Silicon Radio                      | 1        | 0.14%   |
| Blue Microphones                             | 1        | 0.14%   |
| AudioQuest                                   | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 48       | 5.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 32       | 3.8%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 31       | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 29       | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 28       | 3.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 27       | 3.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 24       | 2.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 24       | 2.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 22       | 2.61%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 21       | 2.49%   |
| Intel 200 Series PCH HD Audio                                                     | 16       | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 16       | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                        | 14       | 1.66%   |
| Nvidia GP106 High Definition Audio Controller                                     | 13       | 1.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 13       | 1.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 12       | 1.42%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 12       | 1.42%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 12       | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 11       | 1.3%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 11       | 1.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 11       | 1.3%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 11       | 1.3%    |
| AMD Navi 10 HDMI Audio                                                            | 11       | 1.3%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 11       | 1.3%    |
| Nvidia GP104 High Definition Audio Controller                                     | 10       | 1.19%   |
| Nvidia GP102 HDMI Audio Controller                                                | 9        | 1.07%   |
| Intel Raptor Lake High Definition Audio Controller                                | 9        | 1.07%   |
| AMD FCH Azalia Controller                                                         | 9        | 1.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8        | 0.95%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 8        | 0.95%   |
| Nvidia GP108 High Definition Audio Controller                                     | 7        | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                | 7        | 0.83%   |
| Nvidia GA102 High Definition Audio Controller                                     | 7        | 0.83%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 7        | 0.83%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                                     | 6        | 0.71%   |
| Nvidia GA106 High Definition Audio Controller                                     | 6        | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                                     | 6        | 0.71%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 6        | 0.71%   |
| AMD Navi 31 HDMI/DP Audio                                                         | 6        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 43       | 18.94%  |
| Kingston            | 33       | 14.54%  |
| Unknown             | 24       | 10.57%  |
| SK hynix            | 23       | 10.13%  |
| Corsair             | 19       | 8.37%   |
| Samsung Electronics | 18       | 7.93%   |
| Crucial             | 17       | 7.49%   |
| A-DATA Technology   | 13       | 5.73%   |
| Team                | 8        | 3.52%   |
| Micron Technology   | 6        | 2.64%   |
| Transcend           | 3        | 1.32%   |
| Strontium           | 3        | 1.32%   |
| PNY                 | 2        | 0.88%   |
| Hewlett-Packard     | 2        | 0.88%   |
| Elpida              | 2        | 0.88%   |
| Unknown (ABCD)      | 1        | 0.44%   |
| Unknown (0x0080)    | 1        | 0.44%   |
| Super Talent        | 1        | 0.44%   |
| Ramaxel Technology  | 1        | 0.44%   |
| pqi                 | 1        | 0.44%   |
| OCZ                 | 1        | 0.44%   |
| Nanya Technology    | 1        | 0.44%   |
| Innodisk            | 1        | 0.44%   |
| Hyundai lnc         | 1        | 0.44%   |
| Atermiter           | 1        | 0.44%   |
| Apacer              | 1        | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s   | 4        | 1.65%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s      | 3        | 1.23%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 3        | 1.23%   |
| G.Skill RAM F4-2666C15-8GVR 8GB DIMM DDR4 2800MT/s       | 3        | 1.23%   |
| G.Skill RAM F3-1600C9-4GAB 4GB DIMM DDR3 1600MT/s        | 3        | 1.23%   |
| Crucial RAM CT102464BA160B.C16 8192MB DIMM DDR3 1600MT/s | 3        | 1.23%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 2        | 0.82%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 0.82%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 2        | 0.82%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 2        | 0.82%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s     | 2        | 0.82%   |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s   | 2        | 0.82%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s      | 2        | 0.82%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s   | 2        | 0.82%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s     | 2        | 0.82%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 0.82%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 2        | 0.82%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s         | 2        | 0.82%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 2        | 0.82%   |
| Kingston RAM 9905403-011.A03LF 2GB DIMM DDR3 1600MT/s    | 2        | 0.82%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s     | 2        | 0.82%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s      | 2        | 0.82%   |
| G.Skill RAM F4-3200C16-8GTZB 8GB DIMM DDR4 3200MT/s      | 2        | 0.82%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3600MT/s    | 2        | 0.82%   |
| G.Skill RAM F3-14900CL10-8GBXL 8GB DIMM DDR3 1867MT/s    | 2        | 0.82%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s    | 2        | 0.82%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s   | 2        | 0.82%   |
| Corsair RAM CMK64GX5M2B5600Z40 32GB DIMM DDR5 5600MT/s   | 2        | 0.82%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s   | 2        | 0.82%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s              | 2        | 0.82%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM 1066MT/s                     | 1        | 0.41%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                   | 1        | 0.41%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR2 266MT/s                 | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM 800MT/s                      | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM                              | 1        | 0.41%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1066MT/s            | 1        | 0.41%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 88       | 46.32%  |
| DDR3    | 64       | 33.68%  |
| DDR5    | 13       | 6.84%   |
| Unknown | 10       | 5.26%   |
| SDRAM   | 7        | 3.68%   |
| DDR2    | 6        | 3.16%   |
| LPDDR4  | 1        | 0.53%   |
| DDR     | 1        | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 174      | 92.55%  |
| SODIMM | 14       | 7.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 68       | 33.33%  |
| 16384 | 47       | 23.04%  |
| 4096  | 45       | 22.06%  |
| 2048  | 23       | 11.27%  |
| 32768 | 16       | 7.84%   |
| 1024  | 5        | 2.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 46       | 21.7%   |
| 3600    | 22       | 10.38%  |
| 3200    | 19       | 8.96%   |
| 1333    | 19       | 8.96%   |
| 2400    | 11       | 5.19%   |
| 3800    | 7        | 3.3%    |
| 3733    | 7        | 3.3%    |
| 2133    | 7        | 3.3%    |
| 1867    | 7        | 3.3%    |
| 800     | 7        | 3.3%    |
| 2667    | 6        | 2.83%   |
| 6000    | 4        | 1.89%   |
| 3866    | 4        | 1.89%   |
| 2800    | 4        | 1.89%   |
| 5600    | 3        | 1.42%   |
| 3466    | 3        | 1.42%   |
| 2666    | 3        | 1.42%   |
| 1800    | 3        | 1.42%   |
| 1066    | 3        | 1.42%   |
| 12800   | 2        | 0.94%   |
| 6400    | 2        | 0.94%   |
| 4800    | 2        | 0.94%   |
| 3400    | 2        | 0.94%   |
| 3000    | 2        | 0.94%   |
| 1067    | 2        | 0.94%   |
| 667     | 2        | 0.94%   |
| Unknown | 2        | 0.94%   |
| 3534    | 1        | 0.47%   |
| 3151    | 1        | 0.47%   |
| 2933    | 1        | 0.47%   |
| 2465    | 1        | 0.47%   |
| 2448    | 1        | 0.47%   |
| 2200    | 1        | 0.47%   |
| 2048    | 1        | 0.47%   |
| 2000    | 1        | 0.47%   |
| 1866    | 1        | 0.47%   |
| 333     | 1        | 0.47%   |
| 266     | 1        | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 9        | 42.86%  |
| Hewlett-Packard    | 7        | 33.33%  |
| Canon              | 3        | 14.29%  |
| Fuji Xerox         | 1        | 4.76%   |
| Dymo-CoStar        | 1        | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| HP Officejet 4630 series         | 2        | 9.52%   |
| Brother Printer                  | 2        | 9.52%   |
| HP OfficeJet 8010 series         | 1        | 4.76%   |
| HP LaserJet Professional P1102w  | 1        | 4.76%   |
| HP ENVY 6400 series              | 1        | 4.76%   |
| HP ENVY 4520 series              | 1        | 4.76%   |
| HP DeskJet 2130 series           | 1        | 4.76%   |
| Fuji Xerox DocuPrint CM315/318 z | 1        | 4.76%   |
| Dymo-CoStar LabelWriter 450      | 1        | 4.76%   |
| Canon TS3100 series              | 1        | 4.76%   |
| Canon MB5300 series              | 1        | 4.76%   |
| Canon i950                       | 1        | 4.76%   |
| Brother MFC-J430W                | 1        | 4.76%   |
| Brother MFC-9140CDN              | 1        | 4.76%   |
| Brother MFC-9120CN               | 1        | 4.76%   |
| Brother MFC-7340                 | 1        | 4.76%   |
| Brother HL-L3230CDW series       | 1        | 4.76%   |
| Brother HL-2270DW Laser Printer  | 1        | 4.76%   |
| Brother HL-1430 Laser Printer    | 1        | 4.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 3        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Canon CanoScan LiDE 110  | 2        | 66.67%  |
| Canon CanoScan LiDE 500F | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 43       | 52.44%  |
| Microdia                    | 5        | 6.1%    |
| Chicony Electronics         | 5        | 6.1%    |
| Samsung Electronics         | 4        | 4.88%   |
| Microsoft                   | 3        | 3.66%   |
| GEMBIRD                     | 3        | 3.66%   |
| ARC International           | 3        | 3.66%   |
| KYE Systems (Mouse Systems) | 2        | 2.44%   |
| Z-Star Microelectronics     | 1        | 1.22%   |
| Xiongmai                    | 1        | 1.22%   |
| XHT-220428-ZW               | 1        | 1.22%   |
| UltraSemi                   | 1        | 1.22%   |
| SunplusIT                   | 1        | 1.22%   |
| Realtek Semiconductor       | 1        | 1.22%   |
| Novatek Microelectronics    | 1        | 1.22%   |
| MacroSilicon                | 1        | 1.22%   |
| Lenovo                      | 1        | 1.22%   |
| Google                      | 1        | 1.22%   |
| Generalplus Technology      | 1        | 1.22%   |
| EVGA                        | 1        | 1.22%   |
| Asuscom Network             | 1        | 1.22%   |
| Arkmicro Technologies       | 1        | 1.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                       | 8        | 9.76%   |
| Logitech Webcam C270                              | 7        | 8.54%   |
| Logitech Webcam C170                              | 6        | 7.32%   |
| Samsung Galaxy series, misc. (MTP mode)           | 4        | 4.88%   |
| Microsoft LifeCam HD-3000                         | 3        | 3.66%   |
| Logitech QuickCam Pro 9000                        | 3        | 3.66%   |
| ARC International Camera                          | 3        | 3.66%   |
| Logitech Webcam Pro 9000                          | 2        | 2.44%   |
| Logitech Webcam C600                              | 2        | 2.44%   |
| Logitech Logitech Webcam C925e                    | 2        | 2.44%   |
| Logitech HD Webcam C615                           | 2        | 2.44%   |
| Logitech HD Webcam C525                           | 2        | 2.44%   |
| Logitech C922 Pro Stream Webcam                   | 2        | 2.44%   |
| Logitech BRIO Ultra HD Webcam                     | 2        | 2.44%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 2        | 2.44%   |
| Chicony HP High Definition 1MP Webcam             | 2        | 2.44%   |
| Z-Star Venus USB2.0 Camera                        | 1        | 1.22%   |
| Xiongmai web camera                               | 1        | 1.22%   |
| XHT-220428-ZW KC#43157174                         | 1        | 1.22%   |
| UltraSemi USB3 Video                              | 1        | 1.22%   |
| SunplusIT USB 2.0 Camera                          | 1        | 1.22%   |
| Realtek HD 720P Webcam                            | 1        | 1.22%   |
| Novatek HP High Definition 2MP Webcam             | 1        | 1.22%   |
| Microdia USB Microscope                           | 1        | 1.22%   |
| Microdia USB 2.0 Camera                           | 1        | 1.22%   |
| Microdia Sonix USB 2.0 Camera                     | 1        | 1.22%   |
| Microdia Integrated Camera                        | 1        | 1.22%   |
| Microdia Camera                                   | 1        | 1.22%   |
| MacroSilicon USB Video                            | 1        | 1.22%   |
| Logitech Webcam C300                              | 1        | 1.22%   |
| Logitech Mic (Fusion)                             | 1        | 1.22%   |
| Logitech HD Webcam C910                           | 1        | 1.22%   |
| Logitech HD Webcam C510                           | 1        | 1.22%   |
| Logitech BCC950 ConferenceCam                     | 1        | 1.22%   |
| Lenovo FULL HD 1080P Webcam                       | 1        | 1.22%   |
| KYE Systems (Mouse Systems) FaceCam 3000          | 1        | 1.22%   |
| KYE Systems (Mouse Systems) FaceCam 1000X         | 1        | 1.22%   |
| Google Nexus/Pixel Device (MTP + debug)           | 1        | 1.22%   |
| Generalplus GENERAL WEBCAM                        | 1        | 1.22%   |
| GEMBIRD USB2.0 PC CAMERA                          | 1        | 1.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| AuthenTec | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| AuthenTec AES2550 Fingerprint Sensor | 1        | 100%    |

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
| 0     | 348      | 81.31%  |
| 1     | 73       | 17.06%  |
| 2     | 6        | 1.4%    |
| 5     | 1        | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 30       | 34.88%  |
| Net/wireless             | 27       | 31.4%   |
| Bluetooth                | 6        | 6.98%   |
| Multimedia controller    | 4        | 4.65%   |
| Unassigned class         | 3        | 3.49%   |
| Sound                    | 3        | 3.49%   |
| Dvb card                 | 3        | 3.49%   |
| Storage/ide              | 2        | 2.33%   |
| Network                  | 2        | 2.33%   |
| Communication controller | 2        | 2.33%   |
| Storage/raid             | 1        | 1.16%   |
| Modem                    | 1        | 1.16%   |
| Firewire controller      | 1        | 1.16%   |
| Fingerprint reader       | 1        | 1.16%   |

