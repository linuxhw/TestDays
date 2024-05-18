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

Total: 570

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 40       | 10.36%  |
| Ubuntu 18.04                 | 32       | 8.29%   |
| Ubuntu 22.04                 | 21       | 5.44%   |
| Arch Rolling                 | 15       | 3.89%   |
| Pop!_OS 20.10                | 9        | 2.33%   |
| Pop!_OS 20.04                | 8        | 2.07%   |
| Zorin 16                     | 7        | 1.81%   |
| Ubuntu 20.10                 | 7        | 1.81%   |
| Linux Mint 20.1              | 7        | 1.81%   |
| Debian 11                    | 7        | 1.81%   |
| Ubuntu 21.04                 | 6        | 1.55%   |
| Ubuntu 18.10                 | 6        | 1.55%   |
| Pop!_OS 22.04                | 6        | 1.55%   |
| Manjaro                      | 6        | 1.55%   |
| Fedora 39                    | 6        | 1.55%   |
| Fedora 37                    | 6        | 1.55%   |
| Pop!_OS 21.10                | 5        | 1.3%    |
| Pop!_OS 21.04                | 5        | 1.3%    |
| Linux Mint 20.3              | 5        | 1.3%    |
| KDE neon 20.04               | 5        | 1.3%    |
| Fedora 38                    | 5        | 1.3%    |
| Fedora 36                    | 5        | 1.3%    |
| Fedora 34                    | 5        | 1.3%    |
| Ubuntu 23.04                 | 4        | 1.04%   |
| Ubuntu 22.10                 | 4        | 1.04%   |
| Ubuntu 16.04                 | 4        | 1.04%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.04%   |
| Linux Mint 21.1              | 4        | 1.04%   |
| Linux Mint 20.2              | 4        | 1.04%   |
| Linux Mint 20                | 4        | 1.04%   |
| KDE neon 22.04               | 4        | 1.04%   |
| Fedora 33                    | 4        | 1.04%   |
| Debian 12                    | 4        | 1.04%   |
| Debian 10                    | 4        | 1.04%   |
| Ubuntu 21.10                 | 3        | 0.78%   |
| Ubuntu 19.10                 | 3        | 0.78%   |
| Ubuntu 19.04                 | 3        | 0.78%   |
| OpenMandriva 4.50            | 3        | 0.78%   |
| OpenMandriva 4.3             | 3        | 0.78%   |
| OpenMandriva 4.2             | 3        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 126      | 35.59%  |
| Fedora           | 33       | 9.32%   |
| Linux Mint       | 31       | 8.76%   |
| Pop!_OS          | 29       | 8.19%   |
| Arch             | 17       | 4.8%    |
| Debian           | 15       | 4.24%   |
| OpenMandriva     | 13       | 3.67%   |
| Manjaro          | 11       | 3.11%   |
| KDE neon         | 11       | 3.11%   |
| Zorin            | 10       | 2.82%   |
| Endless          | 9        | 2.54%   |
| Kubuntu          | 7        | 1.98%   |
| Xubuntu          | 4        | 1.13%   |
| openSUSE         | 4        | 1.13%   |
| Nobara           | 4        | 1.13%   |
| RHEL             | 3        | 0.85%   |
| Ubuntu Unity     | 2        | 0.56%   |
| ROSA             | 2        | 0.56%   |
| MX               | 2        | 0.56%   |
| Lubuntu          | 2        | 0.56%   |
| Devuan           | 2        | 0.56%   |
| ArcoLinux        | 2        | 0.56%   |
| Vanilla          | 1        | 0.28%   |
| Ubuntu MATE      | 1        | 0.28%   |
| Regata OS        | 1        | 0.28%   |
| Redcore          | 1        | 0.28%   |
| Peppermint       | 1        | 0.28%   |
| Parrot           | 1        | 0.28%   |
| org.kde.Platform | 1        | 0.28%   |
| NixOS            | 1        | 0.28%   |
| LMDE             | 1        | 0.28%   |
| Linux Lite       | 1        | 0.28%   |
| Gentoo           | 1        | 0.28%   |
| Elementary       | 1        | 0.28%   |
| Dts-distro       | 1        | 0.28%   |
| Deepin           | 1        | 0.28%   |
| ChimeraOS        | 1        | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 6        | 1.33%   |
| 5.4.0-7634-generic       | 5        | 1.11%   |
| 5.4.0-52-generic         | 5        | 1.11%   |
| 5.3.0-46-generic         | 5        | 1.11%   |
| 5.15.0-46-generic        | 5        | 1.11%   |
| 5.15.0-60-generic        | 4        | 0.88%   |
| 5.13.0-30-generic        | 4        | 0.88%   |
| 5.11.0-37-generic        | 4        | 0.88%   |
| 6.2.0-35-generic         | 3        | 0.66%   |
| 5.8.0-50-generic         | 3        | 0.66%   |
| 5.8.0-44-generic         | 3        | 0.66%   |
| 5.4.0-65-generic         | 3        | 0.66%   |
| 5.4.0-33-generic         | 3        | 0.66%   |
| 5.3.0-40-generic         | 3        | 0.66%   |
| 5.16.7-desktop-1omv4003  | 3        | 0.66%   |
| 5.13.0-7614-generic      | 3        | 0.66%   |
| 5.13.0-39-generic        | 3        | 0.66%   |
| 5.11.0-7614-generic      | 3        | 0.66%   |
| 5.11.0-34-generic        | 3        | 0.66%   |
| 5.10.14-desktop-1omv4002 | 3        | 0.66%   |
| 5.0.0-37-generic         | 3        | 0.66%   |
| 4.18.0-25-generic        | 3        | 0.66%   |
| 6.5.6-76060506-generic   | 2        | 0.44%   |
| 6.2.6-desktop-1omv2390   | 2        | 0.44%   |
| 6.2.15-300.fc38.x86_64   | 2        | 0.44%   |
| 6.2.0-39-generic         | 2        | 0.44%   |
| 6.2.0-20-generic         | 2        | 0.44%   |
| 6.1.13-200.fc37.x86_64   | 2        | 0.44%   |
| 6.1.1-desktop-1omv2290   | 2        | 0.44%   |
| 6.1.0-18-amd64           | 2        | 0.44%   |
| 6.1.0-17-amd64           | 2        | 0.44%   |
| 5.9.16-200.fc33.x86_64   | 2        | 0.44%   |
| 5.8.0-7630-generic       | 2        | 0.44%   |
| 5.8.0-59-generic         | 2        | 0.44%   |
| 5.8.0-55-generic         | 2        | 0.44%   |
| 5.8.0-43-generic         | 2        | 0.44%   |
| 5.8.0-33-generic         | 2        | 0.44%   |
| 5.8.0-14-generic         | 2        | 0.44%   |
| 5.4.0-77-generic         | 2        | 0.44%   |
| 5.4.0-7642-generic       | 2        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 51       | 12.41%  |
| 5.15.0  | 31       | 7.54%   |
| 4.15.0  | 25       | 6.08%   |
| 5.8.0   | 23       | 5.6%    |
| 5.11.0  | 23       | 5.6%    |
| 5.13.0  | 19       | 4.62%   |
| 5.3.0   | 16       | 3.89%   |
| 5.19.0  | 16       | 3.89%   |
| 4.18.0  | 14       | 3.41%   |
| 6.2.0   | 12       | 2.92%   |
| 5.10.0  | 9        | 2.19%   |
| 5.0.0   | 8        | 1.95%   |
| 6.1.0   | 7        | 1.7%    |
| 6.5.6   | 4        | 0.97%   |
| 6.5.0   | 4        | 0.97%   |
| 6.2.6   | 3        | 0.73%   |
| 5.9.16  | 3        | 0.73%   |
| 5.16.7  | 3        | 0.73%   |
| 5.10.15 | 3        | 0.73%   |
| 5.10.14 | 3        | 0.73%   |
| 6.8.7   | 2        | 0.49%   |
| 6.7.7   | 2        | 0.49%   |
| 6.6.13  | 2        | 0.49%   |
| 6.6.11  | 2        | 0.49%   |
| 6.5.5   | 2        | 0.49%   |
| 6.4.12  | 2        | 0.49%   |
| 6.2.15  | 2        | 0.49%   |
| 6.1.8   | 2        | 0.49%   |
| 6.1.7   | 2        | 0.49%   |
| 6.1.6   | 2        | 0.49%   |
| 6.1.13  | 2        | 0.49%   |
| 6.1.1   | 2        | 0.49%   |
| 5.8.12  | 2        | 0.49%   |
| 5.7.0   | 2        | 0.49%   |
| 5.6.11  | 2        | 0.49%   |
| 5.18.5  | 2        | 0.49%   |
| 5.18.13 | 2        | 0.49%   |
| 5.17.4  | 2        | 0.49%   |
| 5.15.8  | 2        | 0.49%   |
| 5.15.15 | 2        | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 54       | 13.33%  |
| 5.15    | 42       | 10.37%  |
| 5.11    | 28       | 6.91%   |
| 5.8     | 27       | 6.67%   |
| 4.15    | 25       | 6.17%   |
| 5.19    | 22       | 5.43%   |
| 5.13    | 22       | 5.43%   |
| 6.1     | 20       | 4.94%   |
| 6.2     | 18       | 4.44%   |
| 5.3     | 18       | 4.44%   |
| 5.10    | 16       | 3.95%   |
| 4.18    | 14       | 3.46%   |
| 6.5     | 13       | 3.21%   |
| 6.6     | 10       | 2.47%   |
| 5.0     | 9        | 2.22%   |
| 6.7     | 7        | 1.73%   |
| 5.9     | 7        | 1.73%   |
| 5.7     | 6        | 1.48%   |
| 5.14    | 6        | 1.48%   |
| 5.6     | 5        | 1.23%   |
| 5.18    | 5        | 1.23%   |
| 5.16    | 5        | 1.23%   |
| 6.8     | 4        | 0.99%   |
| 6.4     | 4        | 0.99%   |
| 6.0     | 4        | 0.99%   |
| 5.12    | 4        | 0.99%   |
| 6.3     | 3        | 0.74%   |
| 5.17    | 3        | 0.74%   |
| 4.19    | 2        | 0.49%   |
| 5.5     | 1        | 0.25%   |
| 5.2     | 1        | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 338      | 99.71%  |
| i686   | 1        | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 175      | 48.75%  |
| KDE5          | 53       | 14.76%  |
| Unknown       | 50       | 13.93%  |
| X-Cinnamon    | 31       | 8.64%   |
| XFCE          | 16       | 4.46%   |
| KDE           | 11       | 3.06%   |
| MATE          | 8        | 2.23%   |
| LXQt          | 4        | 1.11%   |
| Unity         | 2        | 0.56%   |
| LXDE          | 2        | 0.56%   |
| Deepin        | 2        | 0.56%   |
| Cinnamon      | 2        | 0.56%   |
| Pantheon      | 1        | 0.28%   |
| KDE6          | 1        | 0.28%   |
| Enlightenment | 1        | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 249      | 71.35%  |
| Wayland | 60       | 17.19%  |
| Unknown | 29       | 8.31%   |
| Tty     | 11       | 3.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 202      | 57.06%  |
| SDDM    | 44       | 12.43%  |
| GDM3    | 37       | 10.45%  |
| LightDM | 29       | 8.19%   |
| GDM     | 28       | 7.91%   |
| TDM     | 11       | 3.11%   |
| SLiM    | 3        | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_NZ   | 211      | 58.45%  |
| en_US   | 70       | 19.39%  |
| Unknown | 45       | 12.47%  |
| en_GB   | 13       | 3.6%    |
| en_AU   | 12       | 3.32%   |
| C       | 7        | 1.94%   |
| zh_CN   | 2        | 0.55%   |
| de_DE   | 1        | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 201      | 57.59%  |
| EFI  | 148      | 42.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 265      | 75.5%   |
| Btrfs   | 37       | 10.54%  |
| Overlay | 18       | 5.13%   |
| Unknown | 13       | 3.7%    |
| Tmpfs   | 9        | 2.56%   |
| Xfs     | 4        | 1.14%   |
| Zfs     | 3        | 0.85%   |
| F2fs    | 1        | 0.28%   |
| Ext3    | 1        | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 203      | 58.17%  |
| GPT     | 123      | 35.24%  |
| MBR     | 23       | 6.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 289      | 83.05%  |
| Yes       | 59       | 16.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 244      | 70.72%  |
| Yes       | 101      | 29.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 94       | 27.73%  |
| Gigabyte Technology                  | 90       | 26.55%  |
| Hewlett-Packard                      | 44       | 12.98%  |
| Dell                                 | 22       | 6.49%   |
| MSI                                  | 21       | 6.19%   |
| ASRock                               | 21       | 6.19%   |
| Lenovo                               | 9        | 2.65%   |
| Intel                                | 9        | 2.65%   |
| Unknown                              | 7        | 2.06%   |
| Acer                                 | 4        | 1.18%   |
| Supermicro                           | 2        | 0.59%   |
| Pegatron                             | 2        | 0.59%   |
| IBM                                  | 2        | 0.59%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.29%   |
| OEM                                  | 1        | 0.29%   |
| MediaVue                             | 1        | 0.29%   |
| JGINYUE                              | 1        | 0.29%   |
| Huanan                               | 1        | 0.29%   |
| DFI                                  | 1        | 0.29%   |
| CWWK                                 | 1        | 0.29%   |
| Colorful Technology                  | 1        | 0.29%   |
| Biostar                              | 1        | 0.29%   |
| Apple                                | 1        | 0.29%   |
| Alienware                            | 1        | 0.29%   |
| AAEON                                | 1        | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 9        | 2.65%   |
| Unknown                              | 8        | 2.36%   |
| Gigabyte H77M-D3H                    | 6        | 1.77%   |
| ASUS TUF Gaming X570-PLUS            | 5        | 1.47%   |
| HP EliteDesk 800 G1 SFF              | 4        | 1.18%   |
| MSI MS-7C02                          | 3        | 0.88%   |
| MSI MS-7B89                          | 3        | 0.88%   |
| HP Compaq 8200 Elite SFF PC          | 3        | 0.88%   |
| Gigabyte B75M-D3H                    | 3        | 0.88%   |
| Gigabyte B550M DS3H AC               | 3        | 0.88%   |
| Gigabyte B450M S2H                   | 3        | 0.88%   |
| Gigabyte 970A-D3P                    | 3        | 0.88%   |
| Dell OptiPlex 3010                   | 3        | 0.88%   |
| ASUS P8B75-M                         | 3        | 0.88%   |
| ASRock B450M Steel Legend            | 3        | 0.88%   |
| ASRock 970 Pro3 R2.0                 | 3        | 0.88%   |
| MSI MS-7C91                          | 2        | 0.59%   |
| Lenovo ThinkCentre M58p 7479RS2      | 2        | 0.59%   |
| HP ProDesk 600 G1 SFF                | 2        | 0.59%   |
| HP EliteDesk 800 G2 DM 35W           | 2        | 0.59%   |
| HP EliteDesk 800 G1 USDT             | 2        | 0.59%   |
| HP Compaq Pro 6300 SFF               | 2        | 0.59%   |
| HP Compaq Elite 8300 USDT            | 2        | 0.59%   |
| HP Compaq Elite 8300 SFF             | 2        | 0.59%   |
| HP Compaq 8100 Elite SFF PC          | 2        | 0.59%   |
| HP Compaq 6200 Pro SFF PC            | 2        | 0.59%   |
| Gigabyte Z77X-D3H                    | 2        | 0.59%   |
| Gigabyte Z68AP-D3                    | 2        | 0.59%   |
| Gigabyte X670 AORUS ELITE AX         | 2        | 0.59%   |
| Gigabyte GA-78LMT-USB3               | 2        | 0.59%   |
| Gigabyte F2A75M-D3H                  | 2        | 0.59%   |
| Gigabyte F2A55M-DS2                  | 2        | 0.59%   |
| Gigabyte B550M DS3H                  | 2        | 0.59%   |
| Gigabyte B550 GAMING X V2            | 2        | 0.59%   |
| Gigabyte B550 AORUS ELITE AX V2      | 2        | 0.59%   |
| Gigabyte AB350-Gaming                | 2        | 0.59%   |
| Dell Precision T3600                 | 2        | 0.59%   |
| Dell OptiPlex 990                    | 2        | 0.59%   |
| ASUS SABERTOOTH 990FX R2.0           | 2        | 0.59%   |
| ASUS ROG STRIX X570-E GAMING WIFI II | 2        | 0.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 21       | 6.19%   |
| ASUS PRIME             | 18       | 5.31%   |
| HP Compaq              | 17       | 5.01%   |
| Dell OptiPlex          | 13       | 3.83%   |
| ASUS TUF               | 11       | 3.24%   |
| HP EliteDesk           | 10       | 2.95%   |
| ASUS All               | 9        | 2.65%   |
| Unknown                | 8        | 2.36%   |
| Lenovo ThinkCentre     | 7        | 2.06%   |
| Dell Precision         | 7        | 2.06%   |
| Gigabyte H77M-D3H      | 6        | 1.77%   |
| Gigabyte B550M         | 5        | 1.47%   |
| HP ProLiant            | 4        | 1.18%   |
| Gigabyte B550          | 4        | 1.18%   |
| ASUS M5A97             | 4        | 1.18%   |
| Acer Aspire            | 4        | 1.18%   |
| MSI MS-7C02            | 3        | 0.88%   |
| MSI MS-7B89            | 3        | 0.88%   |
| HP ProDesk             | 3        | 0.88%   |
| Gigabyte X570          | 3        | 0.88%   |
| Gigabyte GA-78LMT-USB3 | 3        | 0.88%   |
| Gigabyte B75M-D3H      | 3        | 0.88%   |
| Gigabyte B450M         | 3        | 0.88%   |
| Gigabyte AB350-Gaming  | 3        | 0.88%   |
| Gigabyte 970A-D3P      | 3        | 0.88%   |
| ASUS P8B75-M           | 3        | 0.88%   |
| ASUS H110M-A           | 3        | 0.88%   |
| ASRock B450M           | 3        | 0.88%   |
| ASRock 970             | 3        | 0.88%   |
| MSI MS-7C91            | 2        | 0.59%   |
| IBM System             | 2        | 0.59%   |
| Gigabyte Z77X-D3H      | 2        | 0.59%   |
| Gigabyte Z68AP-D3      | 2        | 0.59%   |
| Gigabyte X670          | 2        | 0.59%   |
| Gigabyte X570S         | 2        | 0.59%   |
| Gigabyte F2A75M-D3H    | 2        | 0.59%   |
| Gigabyte F2A55M-DS2    | 2        | 0.59%   |
| Gigabyte B560M         | 2        | 0.59%   |
| ASUS SABERTOOTH        | 2        | 0.59%   |
| ASUS P8Z68-V           | 2        | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 56       | 16.52%  |
| 2020    | 28       | 8.26%   |
| 2019    | 28       | 8.26%   |
| 2018    | 27       | 7.96%   |
| 2013    | 26       | 7.67%   |
| 2011    | 25       | 7.37%   |
| 2017    | 22       | 6.49%   |
| 2014    | 20       | 5.9%    |
| 2010    | 17       | 5.01%   |
| 2009    | 17       | 5.01%   |
| 2021    | 16       | 4.72%   |
| 2015    | 14       | 4.13%   |
| 2008    | 12       | 3.54%   |
| 2022    | 9        | 2.65%   |
| 2016    | 9        | 2.65%   |
| 2023    | 5        | 1.47%   |
| 2007    | 3        | 0.88%   |
| 2005    | 2        | 0.59%   |
| 2024    | 1        | 0.29%   |
| 2004    | 1        | 0.29%   |
| Unknown | 1        | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 339      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 328      | 96.76%  |
| Enabled  | 11       | 3.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 338      | 99.71%  |
| Yes  | 1        | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 96       | 27.51%  |
| 8.01-16.0   | 65       | 18.62%  |
| 32.01-64.0  | 63       | 18.05%  |
| 4.01-8.0    | 47       | 13.47%  |
| 3.01-4.0    | 39       | 11.17%  |
| 64.01-256.0 | 23       | 6.59%   |
| 24.01-32.0  | 9        | 2.58%   |
| 1.01-2.0    | 5        | 1.43%   |
| 2.01-3.0    | 2        | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 118      | 30.26%  |
| 2.01-3.0   | 104      | 26.67%  |
| 4.01-8.0   | 66       | 16.92%  |
| 3.01-4.0   | 45       | 11.54%  |
| 8.01-16.0  | 27       | 6.92%   |
| 0.51-1.0   | 18       | 4.62%   |
| 16.01-24.0 | 6        | 1.54%   |
| 0.01-0.5   | 4        | 1.03%   |
| 32.01-64.0 | 1        | 0.26%   |
| 24.01-32.0 | 1        | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 114      | 31.84%  |
| 2      | 113      | 31.56%  |
| 3      | 58       | 16.2%   |
| 4      | 40       | 11.17%  |
| 6      | 13       | 3.63%   |
| 5      | 12       | 3.35%   |
| 7      | 3        | 0.84%   |
| 8      | 2        | 0.56%   |
| 410    | 1        | 0.28%   |
| 20     | 1        | 0.28%   |
| 0      | 1        | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 193      | 55.94%  |
| Yes       | 152      | 44.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 337      | 99.41%  |
| No        | 2        | 0.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 180      | 52.33%  |
| Yes       | 164      | 47.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 232      | 67.64%  |
| Yes       | 111      | 32.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| New Zealand | 339      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Auckland         | 165      | 46.22%  |
| Wellington       | 46       | 12.89%  |
| Christchurch     | 43       | 12.04%  |
| Hamilton         | 20       | 5.6%    |
| Tauranga         | 14       | 3.92%   |
| Dunedin          | 11       | 3.08%   |
| Palmerston North | 7        | 1.96%   |
| Whangarei        | 5        | 1.4%    |
| Napier City      | 4        | 1.12%   |
| Cambridge        | 4        | 1.12%   |
| Whanganui        | 3        | 0.84%   |
| New Plymouth     | 3        | 0.84%   |
| Nelson           | 3        | 0.84%   |
| Ashburton        | 3        | 0.84%   |
| Rotorua          | 2        | 0.56%   |
| Invercargill     | 2        | 0.56%   |
| Hastings         | 2        | 0.56%   |
| Westport         | 1        | 0.28%   |
| Wellsford        | 1        | 0.28%   |
| Waikanae         | 1        | 0.28%   |
| Waihi            | 1        | 0.28%   |
| Timaru           | 1        | 0.28%   |
| Stratford        | 1        | 0.28%   |
| Queenstown       | 1        | 0.28%   |
| Porirua          | 1        | 0.28%   |
| Onekawa          | 1        | 0.28%   |
| Mount Maunganui  | 1        | 0.28%   |
| Mount Eden       | 1        | 0.28%   |
| Milton           | 1        | 0.28%   |
| Lower Hutt       | 1        | 0.28%   |
| Hunterville      | 1        | 0.28%   |
| Hornby           | 1        | 0.28%   |
| Havelock North   | 1        | 0.28%   |
| Grafton          | 1        | 0.28%   |
| Darfield         | 1        | 0.28%   |
| Carterton        | 1        | 0.28%   |
| Albany           | 1        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 151      | 296    | 23.82%  |
| WDC                          | 126      | 228    | 19.87%  |
| Samsung Electronics          | 112      | 242    | 17.67%  |
| Crucial                      | 37       | 60     | 5.84%   |
| Kingston                     | 30       | 41     | 4.73%   |
| SanDisk                      | 21       | 27     | 3.31%   |
| Intel                        | 19       | 26     | 3%      |
| Toshiba                      | 18       | 25     | 2.84%   |
| Hitachi                      | 17       | 26     | 2.68%   |
| A-DATA Technology            | 10       | 13     | 1.58%   |
| Micron Technology            | 7        | 8      | 1.1%    |
| Micron/Crucial Technology    | 5        | 6      | 0.79%   |
| HGST                         | 5        | 7      | 0.79%   |
| Unknown                      | 4        | 6      | 0.63%   |
| Team                         | 4        | 4      | 0.63%   |
| Lexar                        | 4        | 7      | 0.63%   |
| Gigabyte Technology          | 4        | 5      | 0.63%   |
| Apacer                       | 4        | 5      | 0.63%   |
| TO Exter                     | 3        | 3      | 0.47%   |
| SK hynix                     | 3        | 3      | 0.47%   |
| OCZ                          | 3        | 3      | 0.47%   |
| Hewlett-Packard              | 3        | 5      | 0.47%   |
| External                     | 3        | 4      | 0.47%   |
| Corsair                      | 3        | 5      | 0.47%   |
| China                        | 3        | 4      | 0.47%   |
| XPG                          | 2        | 2      | 0.32%   |
| Transcend                    | 2        | 2      | 0.32%   |
| T-FORCE                      | 2        | 2      | 0.32%   |
| Silicon Motion               | 2        | 3      | 0.32%   |
| KIOXIA                       | 2        | 2      | 0.32%   |
| KingSpec                     | 2        | 2      | 0.32%   |
| ASMT                         | 2        | 2      | 0.32%   |
| Apple                        | 2        | 2      | 0.32%   |
| USB                          | 1        | 2      | 0.16%   |
| ShiJi                        | 1        | 1      | 0.16%   |
| Shenzhen Longsys Electronics | 1        | 2      | 0.16%   |
| Realtek Semiconductor        | 1        | 1      | 0.16%   |
| QUANTUM                      | 1        | 1      | 0.16%   |
| PNY                          | 1        | 1      | 0.16%   |
| Phison Electronics           | 1        | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                     | 15       | 1.93%   |
| Seagate Expansion+ Desk 4TB                        | 11       | 1.41%   |
| Samsung SSD 860 EVO 500GB                          | 11       | 1.41%   |
| Samsung SSD 850 EVO 500GB                          | 11       | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 10       | 1.29%   |
| Crucial CT240BX500SSD1 240GB                       | 10       | 1.29%   |
| Seagate ST500DM002-1BD142 500GB                    | 8        | 1.03%   |
| Seagate ST31000528AS 1TB                           | 8        | 1.03%   |
| Seagate ST1000DM003-1CH162 1TB                     | 8        | 1.03%   |
| Samsung SSD 850 EVO 250GB                          | 8        | 1.03%   |
| Seagate ST2000DM006-2DM164 2TB                     | 7        | 0.9%    |
| Seagate ST2000DM001-1CH164 2TB                     | 7        | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB                     | 7        | 0.9%    |
| Seagate Expansion 2TB                              | 7        | 0.9%    |
| Samsung SSD 980 1TB                                | 7        | 0.9%    |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 6        | 0.77%   |
| Samsung NVMe SSD Drive 500GB                       | 6        | 0.77%   |
| Toshiba THNS128GG4BBAA 128GB SSD                   | 5        | 0.64%   |
| Samsung SSD 870 QVO 1TB                            | 5        | 0.64%   |
| Samsung SSD 870 EVO 1TB                            | 5        | 0.64%   |
| Samsung SSD 860 EVO 250GB                          | 5        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 5        | 0.64%   |
| Kingston SA400S37240G 240GB SSD                    | 5        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                    | 5        | 0.64%   |
| Crucial CT500MX500SSD1 500GB                       | 5        | 0.64%   |
| WDC WD20EARX-00PASB0 2TB                           | 4        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 4        | 0.51%   |
| WDC WD10EZEX-00WN4A0 1TB                           | 4        | 0.51%   |
| WDC WD10EALX-009BA0 1TB                            | 4        | 0.51%   |
| WDC WD1002FAEX-00Z3A0 1TB                          | 4        | 0.51%   |
| Seagate ST9500325AS 500GB                          | 4        | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB                     | 4        | 0.51%   |
| Seagate ST3500418AS 500GB                          | 4        | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB                     | 4        | 0.51%   |
| Samsung SSD 980 250GB                              | 4        | 0.51%   |
| Samsung SSD 870 EVO 500GB                          | 4        | 0.51%   |
| Samsung NVMe SSD Drive 1TB                         | 4        | 0.51%   |
| Crucial CT1000BX500SSD1 1TB                        | 4        | 0.51%   |
| WDC WD40EFRX-68N32N0 4TB                           | 3        | 0.39%   |
| WDC WD2003FZEX-00Z4SA0 2TB                         | 3        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 146      | 282    | 46.5%   |
| WDC                 | 116      | 200    | 36.94%  |
| Hitachi             | 17       | 26     | 5.41%   |
| Toshiba             | 11       | 18     | 3.5%    |
| HGST                | 5        | 7      | 1.59%   |
| Samsung Electronics | 4        | 6      | 1.27%   |
| TO Exter            | 3        | 3      | 0.96%   |
| Unknown             | 2        | 2      | 0.64%   |
| Hewlett-Packard     | 2        | 3      | 0.64%   |
| ASMT                | 2        | 2      | 0.64%   |
| USB                 | 1        | 2      | 0.32%   |
| QUANTUM             | 1        | 1      | 0.32%   |
| JMicron Technology  | 1        | 1      | 0.32%   |
| Fujitsu             | 1        | 1      | 0.32%   |
| External            | 1        | 1      | 0.32%   |
| Apple               | 1        | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 74       | 115    | 31.9%   |
| Crucial             | 34       | 52     | 14.66%  |
| Kingston            | 21       | 31     | 9.05%   |
| Intel               | 16       | 20     | 6.9%    |
| SanDisk             | 15       | 21     | 6.47%   |
| WDC                 | 11       | 21     | 4.74%   |
| A-DATA Technology   | 8        | 10     | 3.45%   |
| Toshiba             | 5        | 5      | 2.16%   |
| Team                | 4        | 4      | 1.72%   |
| Micron Technology   | 4        | 5      | 1.72%   |
| Lexar               | 4        | 7      | 1.72%   |
| Apacer              | 4        | 5      | 1.72%   |
| Seagate             | 3        | 6      | 1.29%   |
| OCZ                 | 3        | 3      | 1.29%   |
| Gigabyte Technology | 3        | 3      | 1.29%   |
| Corsair             | 3        | 5      | 1.29%   |
| China               | 3        | 4      | 1.29%   |
| T-FORCE             | 2        | 2      | 0.86%   |
| KingSpec            | 2        | 2      | 0.86%   |
| External            | 2        | 3      | 0.86%   |
| Transcend           | 1        | 1      | 0.43%   |
| SK hynix            | 1        | 1      | 0.43%   |
| OCZ-VERTEX3         | 1        | 1      | 0.43%   |
| LITEON              | 1        | 1      | 0.43%   |
| Innodisk            | 1        | 1      | 0.43%   |
| Hewlett-Packard     | 1        | 2      | 0.43%   |
| GAMER               | 1        | 1      | 0.43%   |
| FreeNAS             | 1        | 36     | 0.43%   |
| FreeBSD             | 1        | 372    | 0.43%   |
| Apple               | 1        | 1      | 0.43%   |
| Unknown             | 1        | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 238      | 556    | 43.83%  |
| SSD     | 195      | 742    | 35.91%  |
| NVMe    | 102      | 199    | 18.78%  |
| Unknown | 6        | 8      | 1.1%    |
| MMC     | 2        | 2      | 0.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 311      | 1249   | 68.81%  |
| NVMe | 102      | 198    | 22.57%  |
| SAS  | 37       | 58     | 8.19%   |
| MMC  | 2        | 2      | 0.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 237      | 846    | 46.84%  |
| 0.51-1.0   | 138      | 234    | 27.27%  |
| 1.01-2.0   | 70       | 121    | 13.83%  |
| 3.01-4.0   | 37       | 60     | 7.31%   |
| 2.01-3.0   | 13       | 15     | 2.57%   |
| 4.01-10.0  | 7        | 12     | 1.38%   |
| 10.01-20.0 | 3        | 8      | 0.59%   |
| 20.01-50.0 | 1        | 2      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 78       | 20.97%  |
| 251-500        | 58       | 15.59%  |
| 501-1000       | 54       | 14.52%  |
| 1001-2000      | 51       | 13.71%  |
| More than 3000 | 47       | 12.63%  |
| 2001-3000      | 36       | 9.68%   |
| 1-20           | 23       | 6.18%   |
| 51-100         | 12       | 3.23%   |
| Unknown        | 10       | 2.69%   |
| 21-50          | 3        | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 113      | 28.61%  |
| 21-50          | 59       | 14.94%  |
| 501-1000       | 39       | 9.87%   |
| 51-100         | 39       | 9.87%   |
| 101-250        | 36       | 9.11%   |
| 251-500        | 34       | 8.61%   |
| 1001-2000      | 30       | 7.59%   |
| More than 3000 | 18       | 4.56%   |
| 2001-3000      | 17       | 4.3%    |
| Unknown        | 10       | 2.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB           | 2        | 3      | 4.65%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 2        | 2      | 4.65%   |
| Seagate ST3500418AS 500GB             | 2        | 3      | 4.65%   |
| Seagate ST31000528AS 1TB              | 2        | 2      | 4.65%   |
| Samsung Electronics SSD 980 1TB       | 2        | 2      | 4.65%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1        | 1      | 2.33%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1        | 1      | 2.33%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1        | 1      | 2.33%   |
| WDC WD15EARS-00S0XB0 1TB              | 1        | 1      | 2.33%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1        | 3      | 2.33%   |
| WDC WD10EARS-003BB1 1TB               | 1        | 1      | 2.33%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 2      | 2.33%   |
| Toshiba MQ01ABD050 500GB              | 1        | 1      | 2.33%   |
| SK hynix HFS256G32MND-2900A 256GB SSD | 1        | 1      | 2.33%   |
| Seagate ST8000VN0022-2EL112 8TB       | 1        | 3      | 2.33%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 2.33%   |
| Seagate ST4000DX001-1CE168 4TB        | 1        | 1      | 2.33%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 2.33%   |
| Seagate ST3200822A 200GB              | 1        | 1      | 2.33%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 2.33%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 2.33%   |
| Seagate ST2000DX002-2DV164 2TB        | 1        | 1      | 2.33%   |
| Seagate ST2000DX001-1CM164 2TB        | 1        | 1      | 2.33%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 2.33%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 2.33%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 2.33%   |
| SanDisk SSD PLUS 240 GB               | 1        | 1      | 2.33%   |
| Samsung Electronics SSD 980 PRO 2TB   | 1        | 1      | 2.33%   |
| Samsung Electronics SSD 980 PRO 250GB | 1        | 1      | 2.33%   |
| OCZ VERTEX3 90GB SSD                  | 1        | 1      | 2.33%   |
| Intel SSDSC2CT240A4 240GB             | 1        | 1      | 2.33%   |
| Innodisk Corp. - mSATA 3ME4 128GB     | 1        | 1      | 2.33%   |
| Hitachi HTS541010A9E680 1TB           | 1        | 1      | 2.33%   |
| HGST HTS545050A7E380 500GB            | 1        | 1      | 2.33%   |
| Crucial CT480M500SSD1 480GB           | 1        | 1      | 2.33%   |
| Crucial CT480BX500SSD1 480GB          | 1        | 1      | 2.33%   |
| Crucial CT1000BX500SSD1 1TB           | 1        | 2      | 2.33%   |
| ASMT ASM1156-PM 2TB                   | 1        | 1      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 19     | 32.5%   |
| WDC                 | 11       | 15     | 27.5%   |
| Samsung Electronics | 4        | 4      | 10%     |
| Crucial             | 3        | 4      | 7.5%    |
| Toshiba             | 1        | 1      | 2.5%    |
| SK hynix            | 1        | 1      | 2.5%    |
| SanDisk             | 1        | 1      | 2.5%    |
| OCZ                 | 1        | 1      | 2.5%    |
| Intel               | 1        | 1      | 2.5%    |
| Innodisk            | 1        | 1      | 2.5%    |
| Hitachi             | 1        | 1      | 2.5%    |
| HGST                | 1        | 1      | 2.5%    |
| ASMT                | 1        | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 13       | 19     | 48.15%  |
| WDC     | 10       | 14     | 37.04%  |
| Toshiba | 1        | 1      | 3.7%    |
| Hitachi | 1        | 1      | 3.7%    |
| HGST    | 1        | 1      | 3.7%    |
| ASMT    | 1        | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 37     | 65.79%  |
| SSD  | 9        | 10     | 23.68%  |
| NVMe | 4        | 4      | 10.53%  |

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
| Detected | 221      | 659    | 57.11%  |
| Works    | 129      | 796    | 33.33%  |
| Malfunc  | 36       | 51     | 9.3%    |
| Limited  | 1        | 1      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 201      | 40.28%  |
| AMD                          | 125      | 25.05%  |
| Samsung Electronics          | 59       | 11.82%  |
| JMicron Technology           | 16       | 3.21%   |
| ASMedia Technology           | 14       | 2.81%   |
| Marvell Technology Group     | 13       | 2.61%   |
| Kingston Technology Company  | 10       | 2%      |
| Nvidia                       | 9        | 1.8%    |
| Micron/Crucial Technology    | 9        | 1.8%    |
| SanDisk                      | 8        | 1.6%    |
| Seagate Technology           | 5        | 1%      |
| Silicon Motion               | 4        | 0.8%    |
| Phison Electronics           | 4        | 0.8%    |
| Micron Technology            | 3        | 0.6%    |
| LSI Logic / Symbios Logic    | 3        | 0.6%    |
| Toshiba America Info Systems | 2        | 0.4%    |
| SK hynix                     | 2        | 0.4%    |
| Realtek Semiconductor        | 2        | 0.4%    |
| KIOXIA                       | 2        | 0.4%    |
| Hewlett-Packard              | 2        | 0.4%    |
| VIA Technologies             | 1        | 0.2%    |
| Silicon Image                | 1        | 0.2%    |
| Shenzhen Longsys Electronics | 1        | 0.2%    |
| MAXIO Technology (Hangzhou)  | 1        | 0.2%    |
| Broadcom / LSI               | 1        | 0.2%    |
| ADATA Technology             | 1        | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 63       | 9.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 26       | 4.09%   |
| AMD 400 Series Chipset SATA Controller                                                  | 25       | 3.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 3.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 20       | 3.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 20       | 3.15%   |
| AMD 500 Series Chipset SATA Controller                                                  | 20       | 3.15%   |
| Intel SATA Controller [RAID mode]                                                       | 18       | 2.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 18       | 2.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 16       | 2.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 15       | 2.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15       | 2.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13       | 2.05%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 13       | 2.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 1.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 1.42%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 1.42%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 1.26%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 8        | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 8        | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 8        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 7        | 1.1%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 1.1%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 1.1%    |
| AMD 600 Series Chipset SATA Controller                                                  | 7        | 1.1%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 0.94%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 0.79%   |
| JMicron JMB368 IDE controller                                                           | 5        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 0.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 0.79%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 270      | 54.77%  |
| NVMe | 104      | 21.1%   |
| IDE  | 88       | 17.85%  |
| RAID | 27       | 5.48%   |
| SAS  | 3        | 0.61%   |
| SCSI | 1        | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 206      | 60.77%  |
| AMD    | 133      | 39.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz       | 11       | 3.24%   |
| AMD Ryzen 5 3600 6-Core Processor      | 9        | 2.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 8        | 2.36%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 8        | 2.36%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 6        | 1.77%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 6        | 1.77%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 5        | 1.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 5        | 1.47%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 5        | 1.47%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 5        | 1.47%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 4        | 1.18%   |
| Intel Core i7-10700 CPU @ 2.90GHz      | 4        | 1.18%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz  | 4        | 1.18%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 4        | 1.18%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 4        | 1.18%   |
| AMD FX-6300 Six-Core Processor         | 4        | 1.18%   |
| Intel N100                             | 3        | 0.88%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 3        | 0.88%   |
| Intel Core i7 CPU 950 @ 3.07GHz        | 3        | 0.88%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 3        | 0.88%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 3        | 0.88%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 0.88%   |
| Intel Core i3-3220 CPU @ 3.30GHz       | 3        | 0.88%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 3        | 0.88%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 3        | 0.88%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 0.88%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 3        | 0.88%   |
| AMD FX-8350 Eight-Core Processor       | 3        | 0.88%   |
| AMD FX-8320 Eight-Core Processor       | 3        | 0.88%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 0.59%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2        | 0.59%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 2        | 0.59%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 2        | 0.59%   |
| Intel Core i5-8600K CPU @ 3.60GHz      | 2        | 0.59%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 2        | 0.59%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 2        | 0.59%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 2        | 0.59%   |
| Intel Core i5-4670 CPU @ 3.40GHz       | 2        | 0.59%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 2        | 0.59%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 2        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 70       | 20.65%  |
| Intel Core i7           | 54       | 15.93%  |
| AMD Ryzen 5             | 33       | 9.73%   |
| AMD Ryzen 7             | 27       | 7.96%   |
| Intel Xeon              | 20       | 5.9%    |
| AMD FX                  | 19       | 5.6%    |
| Intel Core i3           | 18       | 5.31%   |
| AMD Ryzen 9             | 17       | 5.01%   |
| Intel Core 2 Quad       | 11       | 3.24%   |
| Intel Core 2 Duo        | 7        | 2.06%   |
| Other                   | 6        | 1.77%   |
| AMD Ryzen 3             | 6        | 1.77%   |
| Intel Pentium           | 5        | 1.47%   |
| Intel Atom              | 5        | 1.47%   |
| AMD Athlon 64 X2        | 5        | 1.47%   |
| AMD Ryzen Threadripper  | 4        | 1.18%   |
| AMD Athlon II X2        | 4        | 1.18%   |
| Intel Celeron           | 3        | 0.88%   |
| Intel Pentium Dual-Core | 2        | 0.59%   |
| Intel Core i9           | 2        | 0.59%   |
| AMD Phenom II X6        | 2        | 0.59%   |
| AMD Phenom II X4        | 2        | 0.59%   |
| AMD Athlon II X4        | 2        | 0.59%   |
| AMD A8                  | 2        | 0.59%   |
| AMD A6                  | 2        | 0.59%   |
| AMD A4                  | 2        | 0.59%   |
| Intel Pentium Gold      | 1        | 0.29%   |
| Intel Pentium Dual      | 1        | 0.29%   |
| Intel Pentium 4         | 1        | 0.29%   |
| AMD Six-Core Opteron    | 1        | 0.29%   |
| AMD Ryzen 7 PRO         | 1        | 0.29%   |
| AMD Opteron             | 1        | 0.29%   |
| AMD GX                  | 1        | 0.29%   |
| AMD A12                 | 1        | 0.29%   |
| AMD A10                 | 1        | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 151      | 44.41%  |
| 2      | 56       | 16.47%  |
| 6      | 54       | 15.88%  |
| 8      | 40       | 11.76%  |
| 12     | 16       | 4.71%   |
| 16     | 8        | 2.35%   |
| 3      | 6        | 1.76%   |
| 1      | 4        | 1.18%   |
| 24     | 2        | 0.59%   |
| 10     | 2        | 0.59%   |
| 14     | 1        | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 337      | 99.41%  |
| 2      | 2        | 0.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 212      | 62.54%  |
| 1      | 127      | 37.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 335      | 98.24%  |
| Unknown        | 6        | 1.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 116      | 32.49%  |
| 0x306a9    | 24       | 6.72%   |
| 0x306c3    | 21       | 5.88%   |
| 0x206a7    | 16       | 4.48%   |
| 0x08701021 | 15       | 4.2%    |
| 0x1067a    | 11       | 3.08%   |
| 0x06000852 | 10       | 2.8%    |
| 0x106e5    | 7        | 1.96%   |
| 0x0800820d | 7        | 1.96%   |
| 0xa0655    | 6        | 1.68%   |
| 0x906e9    | 6        | 1.68%   |
| 0x0a601203 | 6        | 1.68%   |
| 0x506e3    | 5        | 1.4%    |
| 0x0a50000c | 5        | 1.4%    |
| 0x08001137 | 5        | 1.4%    |
| 0x906ea    | 4        | 1.12%   |
| 0x206d7    | 4        | 1.12%   |
| 0x106a5    | 4        | 1.12%   |
| 0x0a201016 | 4        | 1.12%   |
| 0x08701013 | 4        | 1.12%   |
| 0x010000c8 | 4        | 1.12%   |
| 0x6fb      | 3        | 0.84%   |
| 0x20655    | 3        | 0.84%   |
| 0x0a201009 | 3        | 0.84%   |
| 0x06001119 | 3        | 0.84%   |
| 0x906ed    | 2        | 0.56%   |
| 0x50654    | 2        | 0.56%   |
| 0x406c3    | 2        | 0.56%   |
| 0x40651    | 2        | 0.56%   |
| 0x306f2    | 2        | 0.56%   |
| 0x20652    | 2        | 0.56%   |
| 0x10677    | 2        | 0.56%   |
| 0x0a50000d | 2        | 0.56%   |
| 0x0a20120a | 2        | 0.56%   |
| 0x0a201025 | 2        | 0.56%   |
| 0x08600106 | 2        | 0.56%   |
| 0x08108109 | 2        | 0.56%   |
| 0x08001138 | 2        | 0.56%   |
| 0x08001129 | 2        | 0.56%   |
| 0x0700010f | 2        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 38       | 11.21%  |
| IvyBridge   | 36       | 10.62%  |
| Zen 2       | 30       | 8.85%   |
| SandyBridge | 25       | 7.37%   |
| Zen 3       | 23       | 6.78%   |
| KabyLake    | 23       | 6.78%   |
| Piledriver  | 20       | 5.9%    |
| Penryn      | 18       | 5.31%   |
| Zen+        | 14       | 4.13%   |
| Zen         | 14       | 4.13%   |
| CometLake   | 14       | 4.13%   |
| Skylake     | 13       | 3.83%   |
| Nehalem     | 13       | 3.83%   |
| Unknown     | 12       | 3.54%   |
| K10         | 11       | 3.24%   |
| Westmere    | 6        | 1.77%   |
| K8 Hammer   | 5        | 1.47%   |
| Core        | 5        | 1.47%   |
| Bulldozer   | 5        | 1.47%   |
| Silvermont  | 4        | 1.18%   |
| Jaguar      | 2        | 0.59%   |
| Bonnell     | 2        | 0.59%   |
| Tremont     | 1        | 0.29%   |
| NetBurst    | 1        | 0.29%   |
| K10 Llano   | 1        | 0.29%   |
| Gracemont   | 1        | 0.29%   |
| Goldmont    | 1        | 0.29%   |
| Excavator   | 1        | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 136      | 36.66%  |
| AMD                        | 127      | 34.23%  |
| Intel                      | 102      | 27.49%  |
| Matrox Electronics Systems | 5        | 1.35%   |
| ASPEED Technology          | 1        | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20       | 5.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18       | 4.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12       | 3.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12       | 3.11%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 8        | 2.07%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 8        | 2.07%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7        | 1.81%   |
| Intel HD Graphics 530                                                                    | 7        | 1.81%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 7        | 1.81%   |
| AMD Raphael                                                                              | 7        | 1.81%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6        | 1.55%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6        | 1.55%   |
| Intel HD Graphics 630                                                                    | 6        | 1.55%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 1.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5        | 1.3%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 5        | 1.3%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 1.3%    |
| AMD Park [Mobility Radeon HD 5430]                                                       | 5        | 1.3%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 5        | 1.3%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 5        | 1.3%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5        | 1.3%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5        | 1.3%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 1.04%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 1.04%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 4        | 1.04%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 3        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 3        | 0.78%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 3        | 0.78%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 3        | 0.78%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 3        | 0.78%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 3        | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 0.78%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 3        | 0.78%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 0.78%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 3        | 0.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 0.78%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 3        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| 1 x Nvidia       | 121      | 34.77%  |
| 1 x AMD          | 108      | 31.03%  |
| 1 x Intel        | 85       | 24.43%  |
| AMD + Nvidia     | 8        | 2.3%    |
| 2 x AMD          | 7        | 2.01%   |
| 1 x Matrox       | 5        | 1.44%   |
| Intel + AMD      | 5        | 1.44%   |
| Intel + Nvidia   | 4        | 1.15%   |
| 2 x Nvidia       | 3        | 0.86%   |
| AMD + 2 x Nvidia | 1        | 0.29%   |
| AMD + ASPEED     | 1        | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 247      | 71.59%  |
| Proprietary | 88       | 25.51%  |
| Unknown     | 10       | 2.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 146      | 41.13%  |
| 1.01-2.0   | 47       | 13.24%  |
| 0.01-0.5   | 37       | 10.42%  |
| 7.01-8.0   | 34       | 9.58%   |
| 0.51-1.0   | 28       | 7.89%   |
| 3.01-4.0   | 24       | 6.76%   |
| 8.01-16.0  | 17       | 4.79%   |
| 5.01-6.0   | 16       | 4.51%   |
| 2.01-3.0   | 4        | 1.13%   |
| 16.01-24.0 | 2        | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 61       | 15.52%  |
| AOC                     | 51       | 12.98%  |
| Dell                    | 45       | 11.45%  |
| Goldstar                | 42       | 10.69%  |
| Philips                 | 33       | 8.4%    |
| ViewSonic               | 24       | 6.11%   |
| Hewlett-Packard         | 20       | 5.09%   |
| Sony                    | 12       | 3.05%   |
| Panasonic               | 11       | 2.8%    |
| Acer                    | 11       | 2.8%    |
| Lenovo                  | 9        | 2.29%   |
| BenQ                    | 9        | 2.29%   |
| Ancor Communications    | 9        | 2.29%   |
| MiTAC                   | 7        | 1.78%   |
| Denver                  | 7        | 1.78%   |
| LG Electronics          | 4        | 1.02%   |
| ASUSTek Computer        | 4        | 1.02%   |
| Unknown                 | 3        | 0.76%   |
| Unknown                 | 3        | 0.76%   |
| Unknown (AAA)           | 2        | 0.51%   |
| MSI                     | 2        | 0.51%   |
| Konka                   | 2        | 0.51%   |
| Gigabyte Technology     | 2        | 0.51%   |
| Chi Mei Optoelectronics | 2        | 0.51%   |
| Yamaha                  | 1        | 0.25%   |
| Targa                   | 1        | 0.25%   |
| SANYO                   | 1        | 0.25%   |
| PPC                     | 1        | 0.25%   |
| Plain Tree Systems      | 1        | 0.25%   |
| NEC Computers           | 1        | 0.25%   |
| Mi                      | 1        | 0.25%   |
| Marantz                 | 1        | 0.25%   |
| KTC                     | 1        | 0.25%   |
| KON                     | 1        | 0.25%   |
| JINGLITAI               | 1        | 0.25%   |
| Iiyama                  | 1        | 0.25%   |
| GVV                     | 1        | 0.25%   |
| eMachines               | 1        | 0.25%   |
| Elo Touch               | 1        | 0.25%   |
| CVT                     | 1        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 7        | 1.6%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 5        | 1.14%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 5        | 1.14%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 5        | 1.14%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                     | 5        | 1.14%   |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch        | 4        | 0.92%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch              | 4        | 0.92%   |
| MiTAC MStar Demo SZM0030 3840x2160 708x398mm 32.0-inch               | 4        | 0.92%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch               | 4        | 0.92%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch    | 3        | 0.69%   |
| Denver 27C1R LHC2700 2560x1440 597x336mm 27.0-inch                   | 3        | 0.69%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                    | 3        | 0.69%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 3        | 0.69%   |
| AOC 2367 AOC2367 1920x1080 509x286mm 23.0-inch                       | 3        | 0.69%   |
| Unknown                                                              | 3        | 0.69%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch             | 2        | 0.46%   |
| ViewSonic VA702-3SERIES VSCB51D 1280x1024 338x270mm 17.0-inch        | 2        | 0.46%   |
| ViewSonic VA2231 Series VSCBB25 1920x1080 477x268mm 21.5-inch        | 2        | 0.46%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 2        | 0.46%   |
| Sony TV SNYEF03 1600x900                                             | 2        | 0.46%   |
| Sony TV SNYEE01 1920x1080                                            | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch | 2        | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 2        | 0.46%   |
| Samsung Electronics S24B350 SAM08DA 1920x1080 531x299mm 24.0-inch    | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch | 2        | 0.46%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 2        | 0.46%   |
| Konka TV MONIOR KOA0030 1360x850 708x398mm 32.0-inch                 | 2        | 0.46%   |
| Hewlett-Packard P221 HWP3057 1920x1080 476x268mm 21.5-inch           | 2        | 0.46%   |
| Goldstar W1941 GSM4B91 1360x768 406x229mm 18.4-inch                  | 2        | 0.46%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 2        | 0.46%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 2        | 0.46%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch               | 2        | 0.46%   |
| Goldstar E2351 GSM5872 1920x1080 510x290mm 23.1-inch                 | 2        | 0.46%   |
| Denver 34A5QR LHC3400 3440x1440 797x334mm 34.0-inch                  | 2        | 0.46%   |
| Dell G2410 DEL404B 1920x1080 531x298mm 24.0-inch                     | 2        | 0.46%   |
| Dell E228WFP DELD014 1680x1050 473x296mm 22.0-inch                   | 2        | 0.46%   |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                    | 2        | 0.46%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 2        | 0.46%   |
| AOC U2868G6R3B AOC2868 3840x2160 621x341mm 27.9-inch                 | 2        | 0.46%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                   | 2        | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 160      | 40.82%  |
| 3840x2160 (4K)     | 64       | 16.33%  |
| 1680x1050 (WSXGA+) | 27       | 6.89%   |
| 2560x1440 (QHD)    | 23       | 5.87%   |
| 1280x1024 (SXGA)   | 21       | 5.36%   |
| Unknown            | 16       | 4.08%   |
| 1440x900 (WXGA+)   | 15       | 3.83%   |
| 1600x900 (HD+)     | 11       | 2.81%   |
| 3840x1080          | 10       | 2.55%   |
| 3440x1440          | 10       | 2.55%   |
| 1360x768           | 5        | 1.28%   |
| 1920x1200 (WUXGA)  | 4        | 1.02%   |
| 1366x768 (WXGA)    | 4        | 1.02%   |
| 2560x1600          | 2        | 0.51%   |
| 2560x1080          | 2        | 0.51%   |
| 2288x1287          | 2        | 0.51%   |
| 1600x1200          | 2        | 0.51%   |
| 7680x1080          | 1        | 0.26%   |
| 6720x1080          | 1        | 0.26%   |
| 5760x1080          | 1        | 0.26%   |
| 5120x1080          | 1        | 0.26%   |
| 3840x1600          | 1        | 0.26%   |
| 3840x1200          | 1        | 0.26%   |
| 3360x1080          | 1        | 0.26%   |
| 3040x1050          | 1        | 0.26%   |
| 2960x1050          | 1        | 0.26%   |
| 2560x1024          | 1        | 0.26%   |
| 2048x1152          | 1        | 0.26%   |
| 1920x540           | 1        | 0.26%   |
| 1280x800 (WXGA)    | 1        | 0.26%   |
| 1024x768 (XGA)     | 1        | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 52       | 13.3%   |
| 24      | 49       | 12.53%  |
| 21      | 49       | 12.53%  |
| 23      | 48       | 12.28%  |
| Unknown | 38       | 9.72%   |
| 31      | 22       | 5.63%   |
| 22      | 20       | 5.12%   |
| 19      | 20       | 5.12%   |
| 20      | 14       | 3.58%   |
| 17      | 12       | 3.07%   |
| 84      | 11       | 2.81%   |
| 72      | 8        | 2.05%   |
| 34      | 8        | 2.05%   |
| 32      | 7        | 1.79%   |
| 18      | 6        | 1.53%   |
| 52      | 3        | 0.77%   |
| 40      | 3        | 0.77%   |
| 35      | 3        | 0.77%   |
| 142     | 2        | 0.51%   |
| 46      | 2        | 0.51%   |
| 15      | 2        | 0.51%   |
| 65      | 1        | 0.26%   |
| 54      | 1        | 0.26%   |
| 49      | 1        | 0.26%   |
| 48      | 1        | 0.26%   |
| 42      | 1        | 0.26%   |
| 37      | 1        | 0.26%   |
| 36      | 1        | 0.26%   |
| 33      | 1        | 0.26%   |
| 30      | 1        | 0.26%   |
| 29      | 1        | 0.26%   |
| 28      | 1        | 0.26%   |
| 26      | 1        | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 125      | 33.42%  |
| 401-500        | 98       | 26.2%   |
| 601-700        | 38       | 10.16%  |
| Unknown        | 38       | 10.16%  |
| 701-800        | 17       | 4.55%   |
| 1501-2000      | 17       | 4.55%   |
| 301-350        | 14       | 3.74%   |
| 1001-1500      | 9        | 2.41%   |
| 351-400        | 8        | 2.14%   |
| 801-900        | 7        | 1.87%   |
| More than 2000 | 2        | 0.53%   |
| 901-1000       | 1        | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 220      | 63.22%  |
| 16/10   | 52       | 14.94%  |
| Unknown | 34       | 9.77%   |
| 5/4     | 20       | 5.75%   |
| 21/9    | 12       | 3.45%   |
| 4/3     | 3        | 0.86%   |
| 32/9    | 3        | 0.86%   |
| 1.00    | 2        | 0.57%   |
| 6/5     | 1        | 0.29%   |
| 3/2     | 1        | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 135      | 35.81%  |
| 301-350        | 52       | 13.79%  |
| 151-200        | 46       | 12.2%   |
| 351-500        | 44       | 11.67%  |
| Unknown        | 38       | 10.08%  |
| More than 1000 | 23       | 6.1%    |
| 141-150        | 15       | 3.98%   |
| 251-300        | 12       | 3.18%   |
| 501-1000       | 10       | 2.65%   |
| 101-110        | 2        | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 202      | 55.34%  |
| 101-120 | 69       | 18.9%   |
| Unknown | 38       | 10.41%  |
| 121-160 | 27       | 7.4%    |
| 1-50    | 22       | 6.03%   |
| 161-240 | 7        | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 247      | 68.99%  |
| 2     | 85       | 23.74%  |
| 0     | 15       | 4.19%   |
| 3     | 9        | 2.51%   |
| 4     | 2        | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 196      | 38.21%  |
| Intel                                 | 165      | 32.16%  |
| Qualcomm Atheros                      | 30       | 5.85%   |
| Broadcom                              | 16       | 3.12%   |
| TP-Link                               | 15       | 2.92%   |
| Ralink Technology                     | 13       | 2.53%   |
| MediaTek                              | 12       | 2.34%   |
| Marvell Technology Group              | 8        | 1.56%   |
| Ralink                                | 7        | 1.36%   |
| Nvidia                                | 7        | 1.36%   |
| Samsung Electronics                   | 4        | 0.78%   |
| Qualcomm Atheros Communications       | 4        | 0.78%   |
| NetGear                               | 4        | 0.78%   |
| Microsoft                             | 4        | 0.78%   |
| Edimax Technology                     | 3        | 0.58%   |
| Aquantia                              | 3        | 0.58%   |
| Microchip Technology                  | 2        | 0.39%   |
| IBM                                   | 2        | 0.39%   |
| Broadcom Limited                      | 2        | 0.39%   |
| ASIX Electronics                      | 2        | 0.39%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.19%   |
| Wilocity                              | 1        | 0.19%   |
| Raspberry Pi                          | 1        | 0.19%   |
| OPPO Electronics                      | 1        | 0.19%   |
| Mellanox Technologies                 | 1        | 0.19%   |
| MCS                                   | 1        | 0.19%   |
| Huawei Technologies                   | 1        | 0.19%   |
| DisplayLink                           | 1        | 0.19%   |
| D-Link                                | 1        | 0.19%   |
| Bose                                  | 1        | 0.19%   |
| Belkin Components                     | 1        | 0.19%   |
| ASUSTek Computer                      | 1        | 0.19%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.19%   |
| 3Com                                  | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 151      | 26.63%  |
| Realtek RTL8125 2.5GbE Controller                                      | 24       | 4.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24       | 4.23%   |
| Intel I211 Gigabit Network Connection                                  | 22       | 3.88%   |
| Intel Wi-Fi 6 AX200                                                    | 20       | 3.53%   |
| Intel Ethernet Connection I217-LM                                      | 11       | 1.94%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 9        | 1.59%   |
| Intel Ethernet Controller I225-V                                       | 9        | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                   | 9        | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8        | 1.41%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 8        | 1.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 7        | 1.23%   |
| Intel Ethernet Connection (2) I218-V                                   | 7        | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 7        | 1.23%   |
| Intel 82574L Gigabit Network Connection                                | 7        | 1.23%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6        | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6        | 1.06%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                  | 5        | 0.88%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 5        | 0.88%   |
| Ralink MT7601U Wireless Adapter                                        | 5        | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5        | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5        | 0.88%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 5        | 0.88%   |
| Intel 82579V Gigabit Network Connection                                | 5        | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 4        | 0.71%   |
| Intel Wireless 8265 / 8275                                             | 4        | 0.71%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 3        | 0.53%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 3        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3        | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3        | 0.53%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 3        | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3        | 0.53%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 3        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 0.53%   |
| Nvidia MCP61 Ethernet                                                  | 3        | 0.53%   |
| Microsoft XBOX ACC                                                     | 3        | 0.53%   |
| Intel Wireless 7265                                                    | 3        | 0.53%   |
| Intel 82578DM Gigabit Network Connection                               | 3        | 0.53%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 3        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 55       | 30.9%   |
| Realtek Semiconductor                 | 36       | 20.22%  |
| TP-Link                               | 15       | 8.43%   |
| Ralink Technology                     | 13       | 7.3%    |
| Qualcomm Atheros                      | 13       | 7.3%    |
| MediaTek                              | 11       | 6.18%   |
| Broadcom                              | 8        | 4.49%   |
| Ralink                                | 7        | 3.93%   |
| Qualcomm Atheros Communications       | 4        | 2.25%   |
| NetGear                               | 4        | 2.25%   |
| Microsoft                             | 4        | 2.25%   |
| Edimax Technology                     | 3        | 1.69%   |
| Wilocity                              | 1        | 0.56%   |
| D-Link                                | 1        | 0.56%   |
| Belkin Components                     | 1        | 0.56%   |
| ASUSTek Computer                      | 1        | 0.56%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 20       | 10.93%  |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]             | 9        | 4.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 7        | 3.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 7        | 3.83%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]           | 6        | 3.28%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 5        | 2.73%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 5        | 2.73%   |
| Ralink MT7601U Wireless Adapter                                     | 5        | 2.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 5        | 2.73%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 5        | 2.73%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 4        | 2.19%   |
| Intel Wireless 8265 / 8275                                          | 4        | 2.19%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                 | 3        | 1.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 3        | 1.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 3        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 3        | 1.64%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 3        | 1.64%   |
| Qualcomm Atheros AR9271 802.11n                                     | 3        | 1.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 3        | 1.64%   |
| Microsoft XBOX ACC                                                  | 3        | 1.64%   |
| Intel Wireless 7265                                                 | 3        | 1.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 3        | 1.64%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 1.09%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 2        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 1.09%   |
| Realtek 802.11ac NIC                                                | 2        | 1.09%   |
| Ralink RT5370 Wireless Adapter                                      | 2        | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 2        | 1.09%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                           | 2        | 1.09%   |
| Intel Wireless 7260                                                 | 2        | 1.09%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]      | 2        | 1.09%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter        | 2        | 1.09%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 1        | 0.55%   |
| TP-Link Archer T4U ver.3                                            | 1        | 0.55%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 0.55%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.55%   |
| TP-Link 802.11ac WLAN Adapter                                       | 1        | 0.55%   |
| TP-Link 802.11ac NIC                                                | 1        | 0.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.55%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 179      | 47.99%  |
| Intel                      | 131      | 35.12%  |
| Qualcomm Atheros           | 19       | 5.09%   |
| Broadcom                   | 9        | 2.41%   |
| Marvell Technology Group   | 8        | 2.14%   |
| Nvidia                     | 7        | 1.88%   |
| Samsung Electronics        | 4        | 1.07%   |
| Aquantia                   | 3        | 0.8%    |
| IBM                        | 2        | 0.54%   |
| Broadcom Limited           | 2        | 0.54%   |
| ASIX Electronics           | 2        | 0.54%   |
| ZTE WCDMA Technologies MSM | 1        | 0.27%   |
| OPPO Electronics           | 1        | 0.27%   |
| Mellanox Technologies      | 1        | 0.27%   |
| MediaTek                   | 1        | 0.27%   |
| Huawei Technologies        | 1        | 0.27%   |
| DisplayLink                | 1        | 0.27%   |
| 3Com                       | 1        | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 151      | 39.95%  |
| Realtek RTL8125 2.5GbE Controller                                              | 24       | 6.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 24       | 6.35%   |
| Intel I211 Gigabit Network Connection                                          | 22       | 5.82%   |
| Intel Ethernet Connection I217-LM                                              | 11       | 2.91%   |
| Intel Ethernet Controller I225-V                                               | 9        | 2.38%   |
| Intel Ethernet Connection (2) I219-V                                           | 9        | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8        | 2.12%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 8        | 2.12%   |
| Intel Ethernet Connection (2) I218-V                                           | 7        | 1.85%   |
| Intel 82574L Gigabit Network Connection                                        | 7        | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                                          | 6        | 1.59%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 5        | 1.32%   |
| Intel 82579V Gigabit Network Connection                                        | 5        | 1.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3        | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3        | 0.79%   |
| Nvidia MCP61 Ethernet                                                          | 3        | 0.79%   |
| Intel 82578DM Gigabit Network Connection                                       | 3        | 0.79%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2        | 0.53%   |
| Nvidia CK804 Ethernet Controller                                               | 2        | 0.53%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 2        | 0.53%   |
| Intel Ethernet Connection I217-V                                               | 2        | 0.53%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2        | 0.53%   |
| Intel Ethernet Connection (14) I219-V                                          | 2        | 0.53%   |
| Intel Ethernet Connection (11) I219-V                                          | 2        | 0.53%   |
| IBM XClarity Controller                                                        | 2        | 0.53%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                                    | 2        | 0.53%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.53%   |
| ZTE WCDMA MSM Unisoc Phone                                                     | 1        | 0.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 0.26%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.26%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1        | 0.26%   |
| OPPO SM8350-MTP _SN:9338D66C                                                   | 1        | 0.26%   |
| Nvidia MCP77 Ethernet                                                          | 1        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 337      | 66.6%   |
| WiFi     | 164      | 32.41%  |
| Modem    | 4        | 0.79%   |
| Unknown  | 1        | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 277      | 77.37%  |
| WiFi     | 81       | 22.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 199      | 57.85%  |
| 2     | 122      | 35.47%  |
| 3     | 18       | 5.23%   |
| 4     | 4        | 1.16%   |
| 6     | 1        | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 290      | 82.86%  |
| Yes  | 60       | 17.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 49       | 43.36%  |
| Cambridge Silicon Radio         | 26       | 23.01%  |
| Broadcom                        | 7        | 6.19%   |
| ASUSTek Computer                | 7        | 6.19%   |
| MediaTek                        | 5        | 4.42%   |
| Qualcomm Atheros Communications | 4        | 3.54%   |
| Realtek Semiconductor           | 3        | 2.65%   |
| IMC Networks                    | 3        | 2.65%   |
| Ralink                          | 2        | 1.77%   |
| Foxconn / Hon Hai               | 2        | 1.77%   |
| Edimax Technology               | 2        | 1.77%   |
| Integrated System Solution      | 1        | 0.88%   |
| HTC (High Tech Computer)        | 1        | 0.88%   |
| Apple                           | 1        | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 26       | 22.61%  |
| Intel AX200 Bluetooth                                                | 16       | 13.91%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 9        | 7.83%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 7        | 6.09%   |
| Intel AX210 Bluetooth                                                | 6        | 5.22%   |
| MediaTek Wireless_Device                                             | 5        | 4.35%   |
| Intel Bluetooth wireless interface                                   | 5        | 4.35%   |
| Intel Bluetooth Device                                               | 5        | 4.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 4.35%   |
| ASUS Bluetooth Radio                                                 | 3        | 2.61%   |
| Realtek Bluetooth Radio                                              | 2        | 1.74%   |
| Ralink RT3290 Bluetooth                                              | 2        | 1.74%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 1.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 1.74%   |
| IMC Networks Wireless_Device                                         | 2        | 1.74%   |
| Foxconn / Hon Hai Wireless_Device                                    | 2        | 1.74%   |
| Edimax Edimax Bluetooth Adapter                                      | 2        | 1.74%   |
| Broadcom HP Portable Bumble Bee                                      | 2        | 1.74%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 0.87%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.87%   |
| Intel AX201 Bluetooth                                                | 1        | 0.87%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.87%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.87%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.87%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.87%   |
| ASUS Bluetooth Device                                                | 1        | 0.87%   |
| ASUS Bluetooth Adapter                                               | 1        | 0.87%   |
| ASUS BCM20702A0                                                      | 1        | 0.87%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.87%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 195      | 33.05%  |
| AMD                                          | 171      | 28.98%  |
| Nvidia                                       | 130      | 22.03%  |
| C-Media Electronics                          | 19       | 3.22%   |
| Logitech                                     | 16       | 2.71%   |
| Kingston Technology                          | 6        | 1.02%   |
| SteelSeries ApS                              | 5        | 0.85%   |
| Razer USA                                    | 4        | 0.68%   |
| Generalplus Technology                       | 4        | 0.68%   |
| JMTek                                        | 3        | 0.51%   |
| GN Netcom                                    | 3        | 0.51%   |
| XMOS                                         | 2        | 0.34%   |
| GYROCOM C&C                                  | 2        | 0.34%   |
| FiiO Electronics Technology                  | 2        | 0.34%   |
| Dell                                         | 2        | 0.34%   |
| Creative Technology                          | 2        | 0.34%   |
| ASUSTek Computer                             | 2        | 0.34%   |
| AKAI Professional M.I.                       | 2        | 0.34%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.17%   |
| VIA Technologies                             | 1        | 0.17%   |
| Texas Instruments                            | 1        | 0.17%   |
| RODE Microphones                             | 1        | 0.17%   |
| RME                                          | 1        | 0.17%   |
| Microsoft                                    | 1        | 0.17%   |
| Medeli Electronics                           | 1        | 0.17%   |
| Lenovo                                       | 1        | 0.17%   |
| Hewlett-Packard                              | 1        | 0.17%   |
| Giga-Byte Technology                         | 1        | 0.17%   |
| DCMT Technology                              | 1        | 0.17%   |
| Creative Labs                                | 1        | 0.17%   |
| Cambridge Silicon Radio                      | 1        | 0.17%   |
| BR25                                         | 1        | 0.17%   |
| Blue Microphones                             | 1        | 0.17%   |
| AudioQuest                                   | 1        | 0.17%   |
| Audio-Technica                               | 1        | 0.17%   |
| Astro Gaming                                 | 1        | 0.17%   |
| Asahi Kasei Microsystems                     | 1        | 0.17%   |
| Apogee Electronics                           | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 43       | 6.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 30       | 4.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 26       | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 22       | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 22       | 3.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 22       | 3.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 20       | 2.87%   |
| AMD Family 17h/19h HD Audio Controller                                            | 20       | 2.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 20       | 2.87%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 15       | 2.16%   |
| Intel 200 Series PCH HD Audio                                                     | 14       | 2.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 14       | 2.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 11       | 1.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 10       | 1.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 10       | 1.44%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 10       | 1.44%   |
| AMD Navi 10 HDMI Audio                                                            | 10       | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9        | 1.29%   |
| Nvidia GP104 High Definition Audio Controller                                     | 9        | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 9        | 1.29%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9        | 1.29%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 9        | 1.29%   |
| Nvidia GP106 High Definition Audio Controller                                     | 8        | 1.15%   |
| Nvidia GP102 HDMI Audio Controller                                                | 8        | 1.15%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 8        | 1.15%   |
| AMD FCH Azalia Controller                                                         | 8        | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                                | 7        | 1.01%   |
| Nvidia GA102 High Definition Audio Controller                                     | 7        | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 1.01%   |
| Intel Cannon Lake PCH cAVS                                                        | 7        | 1.01%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 7        | 1.01%   |
| Nvidia GP108 High Definition Audio Controller                                     | 6        | 0.86%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 6        | 0.86%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 6        | 0.86%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 6        | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5        | 0.72%   |
| Nvidia High Definition Audio Controller                                           | 5        | 0.72%   |
| Nvidia GK104 HDMI Audio Controller                                                | 5        | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                                     | 5        | 0.72%   |
| Intel Comet Lake PCH cAVS                                                         | 5        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 36       | 19.67%  |
| Kingston            | 24       | 13.11%  |
| SK hynix            | 20       | 10.93%  |
| Unknown             | 18       | 9.84%   |
| Corsair             | 15       | 8.2%    |
| Samsung Electronics | 14       | 7.65%   |
| Crucial             | 13       | 7.1%    |
| A-DATA Technology   | 11       | 6.01%   |
| Team                | 7        | 3.83%   |
| Micron Technology   | 5        | 2.73%   |
| Transcend           | 3        | 1.64%   |
| Strontium           | 2        | 1.09%   |
| PNY                 | 2        | 1.09%   |
| Hewlett-Packard     | 2        | 1.09%   |
| Elpida              | 2        | 1.09%   |
| Unknown (ABCD)      | 1        | 0.55%   |
| Unknown (0x0080)    | 1        | 0.55%   |
| Super Talent        | 1        | 0.55%   |
| Ramaxel Technology  | 1        | 0.55%   |
| pqi                 | 1        | 0.55%   |
| OCZ                 | 1        | 0.55%   |
| Nanya Technology    | 1        | 0.55%   |
| Innodisk            | 1        | 0.55%   |
| Atermiter           | 1        | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s             | 4        | 2.06%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s                | 3        | 1.55%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s               | 3        | 1.55%   |
| G.Skill RAM F3-1600C9-4GAB 4GB DIMM DDR3 1600MT/s                  | 3        | 1.55%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                               | 2        | 1.03%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                       | 2        | 1.03%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s               | 2        | 1.03%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 2        | 1.03%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s                | 2        | 1.03%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s             | 2        | 1.03%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                  | 2        | 1.03%   |
| Kingston RAM 9905403-011.A03LF 2GB DIMM DDR3 1333MT/s              | 2        | 1.03%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s                | 2        | 1.03%   |
| G.Skill RAM F4-3200C16-8GTZB 8GB DIMM DDR4 3200MT/s                | 2        | 1.03%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3600MT/s              | 2        | 1.03%   |
| G.Skill RAM F4-2666C15-8GVR 8GB DIMM DDR4 2800MT/s                 | 2        | 1.03%   |
| G.Skill RAM F3-14900CL10-8GBXL 8GB DIMM DDR3 1867MT/s              | 2        | 1.03%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s              | 2        | 1.03%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s              | 2        | 1.03%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s             | 2        | 1.03%   |
| Corsair RAM CMK64GX5M2B5600Z40 32GB DIMM DDR5 5600MT/s             | 2        | 1.03%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s             | 2        | 1.03%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                          | 1        | 0.52%   |
| Unknown RAM Module 8GB DIMM 1066MT/s                               | 1        | 0.52%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                             | 1        | 0.52%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                            | 1        | 0.52%   |
| Unknown RAM Module 4GB DIMM DDR2 266MT/s                           | 1        | 0.52%   |
| Unknown RAM Module 4GB DIMM 800MT/s                                | 1        | 0.52%   |
| Unknown RAM Module 4GB DIMM                                        | 1        | 0.52%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1066MT/s                      | 1        | 0.52%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                       | 1        | 0.52%   |
| Unknown RAM Module 4096MB DIMM DDR2 1067MT/s                       | 1        | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                          | 1        | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR2 266MT/s                           | 1        | 0.52%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                | 1        | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                        | 1        | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                        | 1        | 0.52%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                        | 1        | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s       | 1        | 0.52%   |
| Unknown (0x0080) RAM KINSOTIN16GB2666MHZ 16GB SODIMM DDR4 2667MT/s | 1        | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 75       | 48.7%   |
| DDR3    | 53       | 34.42%  |
| Unknown | 9        | 5.84%   |
| DDR5    | 6        | 3.9%    |
| SDRAM   | 5        | 3.25%   |
| DDR2    | 4        | 2.6%    |
| LPDDR4  | 1        | 0.65%   |
| DDR     | 1        | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 138      | 90.79%  |
| SODIMM | 14       | 9.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 58       | 34.94%  |
| 4096  | 37       | 22.29%  |
| 16384 | 36       | 21.69%  |
| 2048  | 19       | 11.45%  |
| 32768 | 13       | 7.83%   |
| 1024  | 3        | 1.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 36       | 21.18%  |
| 3600    | 20       | 11.76%  |
| 1333    | 18       | 10.59%  |
| 3200    | 16       | 9.41%   |
| 2400    | 7        | 4.12%   |
| 3800    | 6        | 3.53%   |
| 3733    | 6        | 3.53%   |
| 2667    | 6        | 3.53%   |
| 1867    | 6        | 3.53%   |
| 2133    | 5        | 2.94%   |
| 3866    | 4        | 2.35%   |
| 800     | 4        | 2.35%   |
| 2800    | 3        | 1.76%   |
| 2666    | 3        | 1.76%   |
| 1066    | 3        | 1.76%   |
| 6400    | 2        | 1.18%   |
| 5600    | 2        | 1.18%   |
| 3466    | 2        | 1.18%   |
| 3400    | 2        | 1.18%   |
| 1800    | 2        | 1.18%   |
| 667     | 2        | 1.18%   |
| 6000    | 1        | 0.59%   |
| 4800    | 1        | 0.59%   |
| 3534    | 1        | 0.59%   |
| 3151    | 1        | 0.59%   |
| 3000    | 1        | 0.59%   |
| 2933    | 1        | 0.59%   |
| 2465    | 1        | 0.59%   |
| 2448    | 1        | 0.59%   |
| 2200    | 1        | 0.59%   |
| 2048    | 1        | 0.59%   |
| 2000    | 1        | 0.59%   |
| 1866    | 1        | 0.59%   |
| 1067    | 1        | 0.59%   |
| 266     | 1        | 0.59%   |
| Unknown | 1        | 0.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 8        | 40%     |
| Hewlett-Packard    | 7        | 35%     |
| Canon              | 3        | 15%     |
| Fuji Xerox         | 1        | 5%      |
| Dymo-CoStar        | 1        | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| HP Officejet 4630 series         | 2        | 10%     |
| Brother Printer                  | 2        | 10%     |
| HP OfficeJet 8010 series         | 1        | 5%      |
| HP LaserJet Professional P1102w  | 1        | 5%      |
| HP ENVY 6400 series              | 1        | 5%      |
| HP ENVY 4520 series              | 1        | 5%      |
| HP DeskJet 2130 series           | 1        | 5%      |
| Fuji Xerox DocuPrint CM315/318 z | 1        | 5%      |
| Dymo-CoStar LabelWriter 450      | 1        | 5%      |
| Canon TS3100 series              | 1        | 5%      |
| Canon MB5300 series              | 1        | 5%      |
| Canon i950                       | 1        | 5%      |
| Brother MFC-J430W                | 1        | 5%      |
| Brother MFC-9140CDN              | 1        | 5%      |
| Brother MFC-7340                 | 1        | 5%      |
| Brother HL-L3230CDW series       | 1        | 5%      |
| Brother HL-2270DW Laser Printer  | 1        | 5%      |
| Brother HL-1430 Laser Printer    | 1        | 5%      |

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


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Canon CanoScan LiDE 500F | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 34       | 50.75%  |
| Microdia                    | 5        | 7.46%   |
| Samsung Electronics         | 3        | 4.48%   |
| GEMBIRD                     | 3        | 4.48%   |
| Chicony Electronics         | 3        | 4.48%   |
| ARC International           | 3        | 4.48%   |
| Microsoft                   | 2        | 2.99%   |
| KYE Systems (Mouse Systems) | 2        | 2.99%   |
| Z-Star Microelectronics     | 1        | 1.49%   |
| Xiongmai                    | 1        | 1.49%   |
| Sunplus IT                  | 1        | 1.49%   |
| Realtek Semiconductor       | 1        | 1.49%   |
| Novatek Microelectronics    | 1        | 1.49%   |
| MacroSilicon                | 1        | 1.49%   |
| Lenovo                      | 1        | 1.49%   |
| Google                      | 1        | 1.49%   |
| Generalplus Technology      | 1        | 1.49%   |
| EVGA                        | 1        | 1.49%   |
| Asuscom Network             | 1        | 1.49%   |
| Arkmicro Technologies       | 1        | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 6        | 8.96%   |
| Logitech Webcam C170                              | 6        | 8.96%   |
| Logitech HD Pro Webcam C920                       | 4        | 5.97%   |
| Samsung Galaxy series, misc. (MTP mode)           | 3        | 4.48%   |
| Logitech QuickCam Pro 9000                        | 3        | 4.48%   |
| ARC International Camera                          | 3        | 4.48%   |
| Microsoft LifeCam HD-3000                         | 2        | 2.99%   |
| Logitech Webcam Pro 9000                          | 2        | 2.99%   |
| Logitech Webcam C600                              | 2        | 2.99%   |
| Logitech HD Webcam C615                           | 2        | 2.99%   |
| Logitech HD Webcam C525                           | 2        | 2.99%   |
| Logitech C922 Pro Stream Webcam                   | 2        | 2.99%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 2        | 2.99%   |
| Z-Star Venus USB2.0 Camera                        | 1        | 1.49%   |
| Xiongmai web camera                               | 1        | 1.49%   |
| Sunplus IT 1080P Webcam                           | 1        | 1.49%   |
| Realtek HD 720P Webcam                            | 1        | 1.49%   |
| Novatek HP High Definition 2MP Webcam             | 1        | 1.49%   |
| Microdia USB Microscope                           | 1        | 1.49%   |
| Microdia USB 2.0 Camera                           | 1        | 1.49%   |
| Microdia Sonix USB 2.0 Camera                     | 1        | 1.49%   |
| Microdia Integrated Camera                        | 1        | 1.49%   |
| Microdia Camera                                   | 1        | 1.49%   |
| MacroSilicon MiraBox Capture                      | 1        | 1.49%   |
| Logitech Webcam C925e                             | 1        | 1.49%   |
| Logitech Webcam C300                              | 1        | 1.49%   |
| Logitech Mic (Fusion)                             | 1        | 1.49%   |
| Logitech HD Webcam C510                           | 1        | 1.49%   |
| Logitech BRIO Ultra HD Webcam                     | 1        | 1.49%   |
| Lenovo FULL HD 1080P Webcam                       | 1        | 1.49%   |
| KYE Systems (Mouse Systems) FaceCam 3000          | 1        | 1.49%   |
| KYE Systems (Mouse Systems) FaceCam 1000X         | 1        | 1.49%   |
| Google Nexus/Pixel Device (MTP + debug)           | 1        | 1.49%   |
| Generalplus GENERAL WEBCAM                        | 1        | 1.49%   |
| GEMBIRD USB2.0 PC CAMERA                          | 1        | 1.49%   |
| EVGA XR1 Capture Box                              | 1        | 1.49%   |
| Chicony HP High Definition Webcam                 | 1        | 1.49%   |
| Chicony HP High Definition 1MP Webcam             | 1        | 1.49%   |
| Chicony CNF7042                                   | 1        | 1.49%   |
| Asuscom Network REDRAGON Live Camera              | 1        | 1.49%   |

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
| 0     | 290      | 81.69%  |
| 1     | 58       | 16.34%  |
| 2     | 6        | 1.69%   |
| 5     | 1        | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 23       | 32.39%  |
| Net/wireless             | 22       | 30.99%  |
| Bluetooth                | 6        | 8.45%   |
| Multimedia controller    | 4        | 5.63%   |
| Unassigned class         | 3        | 4.23%   |
| Sound                    | 3        | 4.23%   |
| Dvb card                 | 3        | 4.23%   |
| Storage/ide              | 2        | 2.82%   |
| Communication controller | 2        | 2.82%   |
| Storage/raid             | 1        | 1.41%   |
| Modem                    | 1        | 1.41%   |
| Fingerprint reader       | 1        | 1.41%   |

