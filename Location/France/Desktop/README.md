Linux in France - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in France.

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

Total: 5663

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME Z270-A                | [725ce23e28](https://linux-hardware.org/?probe=725ce23e28) | Nov 06, 2023 |
| Shuttle       | XS35V3                      | [0c51d541de](https://linux-hardware.org/?probe=0c51d541de) | Nov 06, 2023 |
| Dell          | 0WMJ54 A01                  | [5cff6ffdfc](https://linux-hardware.org/?probe=5cff6ffdfc) | Nov 05, 2023 |
| HP            | 1497                        | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| HP            | 802F                        | [8fe557cc85](https://linux-hardware.org/?probe=8fe557cc85) | Nov 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [7152c7ed2c](https://linux-hardware.org/?probe=7152c7ed2c) | Nov 05, 2023 |
| ASRock        | A320M Pro4-F                | [7dab52cd8c](https://linux-hardware.org/?probe=7dab52cd8c) | Nov 05, 2023 |
| MSI           | H110I PRO                   | [c335c71c4b](https://linux-hardware.org/?probe=c335c71c4b) | Nov 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [8841ab599e](https://linux-hardware.org/?probe=8841ab599e) | Nov 04, 2023 |
| Dell          | 0W0CHX A00                  | [3ed37b3d70](https://linux-hardware.org/?probe=3ed37b3d70) | Nov 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [d35fc5aa78](https://linux-hardware.org/?probe=d35fc5aa78) | Nov 03, 2023 |
| Dell          | 0427JK A00                  | [ac631c05bc](https://linux-hardware.org/?probe=ac631c05bc) | Nov 03, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [b58b97e74a](https://linux-hardware.org/?probe=b58b97e74a) | Nov 02, 2023 |
| Biostar       | B250MHC                     | [528c04a30a](https://linux-hardware.org/?probe=528c04a30a) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [9a5c45e54b](https://linux-hardware.org/?probe=9a5c45e54b) | Nov 02, 2023 |
| ASUSTek       | M52AD_M12AD                 | [a75715ee4a](https://linux-hardware.org/?probe=a75715ee4a) | Nov 01, 2023 |
| ASUSTek       | P5K PRO                     | [00af1ea679](https://linux-hardware.org/?probe=00af1ea679) | Nov 01, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [a31e5e0862](https://linux-hardware.org/?probe=a31e5e0862) | Nov 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [4881df8aec](https://linux-hardware.org/?probe=4881df8aec) | Nov 01, 2023 |
| MSI           | A320M PRO-M2 V2             | [3b667e2123](https://linux-hardware.org/?probe=3b667e2123) | Oct 31, 2023 |
| MSI           | B85-G43 GAMING              | [5d218dd764](https://linux-hardware.org/?probe=5d218dd764) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [3ea2a80843](https://linux-hardware.org/?probe=3ea2a80843) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [52c3eeea68](https://linux-hardware.org/?probe=52c3eeea68) | Oct 31, 2023 |
| Gigabyte      | GA-970A-D3                  | [38ae588910](https://linux-hardware.org/?probe=38ae588910) | Oct 30, 2023 |
| ASRock        | FM2A88X+ Killer             | [2310075f2d](https://linux-hardware.org/?probe=2310075f2d) | Oct 30, 2023 |
| MSI           | B85-G43 GAMING              | [fa91d8044f](https://linux-hardware.org/?probe=fa91d8044f) | Oct 30, 2023 |
| Acer          | Veriton X2631G V:1.0        | [c2c4828db8](https://linux-hardware.org/?probe=c2c4828db8) | Oct 30, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e18680d1f4](https://linux-hardware.org/?probe=e18680d1f4) | Oct 29, 2023 |
| Dell          | 02YYK5 A00                  | [bda6b9ff10](https://linux-hardware.org/?probe=bda6b9ff10) | Oct 29, 2023 |
| ASUSTek       | P7P55-M                     | [3fa8a23f12](https://linux-hardware.org/?probe=3fa8a23f12) | Oct 29, 2023 |
| MSI           | X299 TOMAHAWK AC            | [b878ce40e7](https://linux-hardware.org/?probe=b878ce40e7) | Oct 29, 2023 |
| MSI           | X570-A PRO                  | [b6f56d4f6c](https://linux-hardware.org/?probe=b6f56d4f6c) | Oct 29, 2023 |
| ASRock        | Z370 Professional Gaming... | [f589e0c914](https://linux-hardware.org/?probe=f589e0c914) | Oct 28, 2023 |
| MSI           | B360 GAMING PLUS            | [bb17f05c7f](https://linux-hardware.org/?probe=bb17f05c7f) | Oct 28, 2023 |
| HP            | 8053                        | [352cc1bad8](https://linux-hardware.org/?probe=352cc1bad8) | Oct 28, 2023 |
| HP            | 8053                        | [25f2c6e830](https://linux-hardware.org/?probe=25f2c6e830) | Oct 28, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | [fdb96441a0](https://linux-hardware.org/?probe=fdb96441a0) | Oct 27, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | [dde83d5de1](https://linux-hardware.org/?probe=dde83d5de1) | Oct 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [880bf38f49](https://linux-hardware.org/?probe=880bf38f49) | Oct 27, 2023 |
| HP            | 339A                        | [d0deadc097](https://linux-hardware.org/?probe=d0deadc097) | Oct 27, 2023 |
| ASUSTek       | H110M-A                     | [a58f65d857](https://linux-hardware.org/?probe=a58f65d857) | Oct 27, 2023 |
| Gigabyte      | H97-D3H-CF                  | [e248fcb770](https://linux-hardware.org/?probe=e248fcb770) | Oct 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f7c6d6e17e](https://linux-hardware.org/?probe=f7c6d6e17e) | Oct 27, 2023 |
| ASUSTek       | P8P67 PRO                   | [a1916cc782](https://linux-hardware.org/?probe=a1916cc782) | Oct 26, 2023 |
| LattePanda    | Sigma                       | [d287cf2d8a](https://linux-hardware.org/?probe=d287cf2d8a) | Oct 26, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [0a305499ef](https://linux-hardware.org/?probe=0a305499ef) | Oct 26, 2023 |
| Dell          | 06D7TR A00                  | [a7097bd7f1](https://linux-hardware.org/?probe=a7097bd7f1) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [67021475e9](https://linux-hardware.org/?probe=67021475e9) | Oct 26, 2023 |
| HP            | 212B                        | [714373878e](https://linux-hardware.org/?probe=714373878e) | Oct 24, 2023 |
| ASUSTek       | PRIME A320M-K               | [d09253d43a](https://linux-hardware.org/?probe=d09253d43a) | Oct 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [9b0be83ecc](https://linux-hardware.org/?probe=9b0be83ecc) | Oct 24, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [3daca4912e](https://linux-hardware.org/?probe=3daca4912e) | Oct 24, 2023 |
| Dell          | 0R790T A00                  | [905555c7d5](https://linux-hardware.org/?probe=905555c7d5) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [5f6d67d67e](https://linux-hardware.org/?probe=5f6d67d67e) | Oct 23, 2023 |
| Acer          | WG43M                       | [0580e7ab1b](https://linux-hardware.org/?probe=0580e7ab1b) | Oct 23, 2023 |
| Unknown       | Unknown                     | [95d6dab241](https://linux-hardware.org/?probe=95d6dab241) | Oct 23, 2023 |
| Trigkey       | Green G5                    | [a0cb634fc5](https://linux-hardware.org/?probe=a0cb634fc5) | Oct 22, 2023 |
| Gigabyte      | B550M DS3H                  | [8bfba005ad](https://linux-hardware.org/?probe=8bfba005ad) | Oct 22, 2023 |
| Gigabyte      | B550M DS3H                  | [6677da99ae](https://linux-hardware.org/?probe=6677da99ae) | Oct 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b6df3ae720](https://linux-hardware.org/?probe=b6df3ae720) | Oct 22, 2023 |
| ASUSTek       | P8H67                       | [5e8558b08d](https://linux-hardware.org/?probe=5e8558b08d) | Oct 22, 2023 |
| Acer          | Veriton X2631G V:1.0        | [22402b17d1](https://linux-hardware.org/?probe=22402b17d1) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9d3213958f](https://linux-hardware.org/?probe=9d3213958f) | Oct 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | [30d9002099](https://linux-hardware.org/?probe=30d9002099) | Oct 21, 2023 |
| HP            | 09F0h                       | [97710d8f02](https://linux-hardware.org/?probe=97710d8f02) | Oct 21, 2023 |
| ASUSTek       | P9X79                       | [3df64c6ee4](https://linux-hardware.org/?probe=3df64c6ee4) | Oct 21, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [2fb0ec8fa2](https://linux-hardware.org/?probe=2fb0ec8fa2) | Oct 21, 2023 |
| AZW           | SER V1                      | [60f9b9fdd9](https://linux-hardware.org/?probe=60f9b9fdd9) | Oct 21, 2023 |
| Lenovo        | SHARKBAY NOK                | [cb8d8311e7](https://linux-hardware.org/?probe=cb8d8311e7) | Oct 20, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [4d1d3bb840](https://linux-hardware.org/?probe=4d1d3bb840) | Oct 19, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [82633fd1ef](https://linux-hardware.org/?probe=82633fd1ef) | Oct 19, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [b677f99638](https://linux-hardware.org/?probe=b677f99638) | Oct 19, 2023 |
| HP            | 1496                        | [c0c1d4b920](https://linux-hardware.org/?probe=c0c1d4b920) | Oct 19, 2023 |
| MSI           | Z590-A PRO                  | [804682ff68](https://linux-hardware.org/?probe=804682ff68) | Oct 19, 2023 |
| MSI           | B450 TOMAHAWK               | [911d7f21e7](https://linux-hardware.org/?probe=911d7f21e7) | Oct 18, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [6e81d4f878](https://linux-hardware.org/?probe=6e81d4f878) | Oct 18, 2023 |
| ASUSTek       | PRIME Z370-P                | [aa01fa43ac](https://linux-hardware.org/?probe=aa01fa43ac) | Oct 18, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [793ba23be0](https://linux-hardware.org/?probe=793ba23be0) | Oct 18, 2023 |
| MSI           | H77MA-G43                   | [b741ca0ecc](https://linux-hardware.org/?probe=b741ca0ecc) | Oct 18, 2023 |
| Lenovo        | SHARKBAY NOK                | [15064c45a9](https://linux-hardware.org/?probe=15064c45a9) | Oct 17, 2023 |
| Dell          | 0GK35Y A00                  | [99aded4434](https://linux-hardware.org/?probe=99aded4434) | Oct 17, 2023 |
| ASRock        | B560M Pro4                  | [77690da2b6](https://linux-hardware.org/?probe=77690da2b6) | Oct 17, 2023 |
| ASUSTek       | UN42                        | [53267f9960](https://linux-hardware.org/?probe=53267f9960) | Oct 17, 2023 |
| Foxconn       | 2ABF                        | [cf4a419a07](https://linux-hardware.org/?probe=cf4a419a07) | Oct 17, 2023 |
| ASRock        | A320M-HDV R3.0              | [95642179a1](https://linux-hardware.org/?probe=95642179a1) | Oct 16, 2023 |
| Dell          | 0CRH6C A00                  | [861e34ac85](https://linux-hardware.org/?probe=861e34ac85) | Oct 16, 2023 |
| MACHINIST     | X99-MR9A PRO MAX V1.2       | [abace10ada](https://linux-hardware.org/?probe=abace10ada) | Oct 16, 2023 |
| MSI           | Z97A GAMING 7               | [8af7152ba5](https://linux-hardware.org/?probe=8af7152ba5) | Oct 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [f12bcba44c](https://linux-hardware.org/?probe=f12bcba44c) | Oct 16, 2023 |
| HP            | 0AE4h                       | [a31dd4463f](https://linux-hardware.org/?probe=a31dd4463f) | Oct 16, 2023 |
| HP            | 0AE4h                       | [4ebaa677df](https://linux-hardware.org/?probe=4ebaa677df) | Oct 16, 2023 |
| HP            | 18E5                        | [d869fcd6dc](https://linux-hardware.org/?probe=d869fcd6dc) | Oct 16, 2023 |
| Dell          | 0HN7XN A01                  | [6ca94363be](https://linux-hardware.org/?probe=6ca94363be) | Oct 15, 2023 |
| Dell          | 0HN7XN A01                  | [de23701ea4](https://linux-hardware.org/?probe=de23701ea4) | Oct 15, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | [dd3eca03df](https://linux-hardware.org/?probe=dd3eca03df) | Oct 15, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [1f718e54bf](https://linux-hardware.org/?probe=1f718e54bf) | Oct 15, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [16a117accb](https://linux-hardware.org/?probe=16a117accb) | Oct 15, 2023 |
| Intel         | DN2820FYK H24582-204        | [721e07849a](https://linux-hardware.org/?probe=721e07849a) | Oct 14, 2023 |
| Dell          | 0F5C5X A00                  | [78e96592c1](https://linux-hardware.org/?probe=78e96592c1) | Oct 14, 2023 |
| Unknown       | Unknown                     | [b45f1baf7a](https://linux-hardware.org/?probe=b45f1baf7a) | Oct 14, 2023 |
| BESSTAR Te... | UM250 V1.0                  | [b4697a227f](https://linux-hardware.org/?probe=b4697a227f) | Oct 14, 2023 |
| ASUSTek       | PRIME Z370-P                | [c8c0c21213](https://linux-hardware.org/?probe=c8c0c21213) | Oct 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [0e5e9d0e0f](https://linux-hardware.org/?probe=0e5e9d0e0f) | Oct 14, 2023 |
| ASUSTek       | P9X79                       | [93898c0a2b](https://linux-hardware.org/?probe=93898c0a2b) | Oct 13, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [2da1e6091f](https://linux-hardware.org/?probe=2da1e6091f) | Oct 13, 2023 |
| HP            | 1495                        | [e524318d58](https://linux-hardware.org/?probe=e524318d58) | Oct 13, 2023 |
| Dell          | 0HN7XN A00                  | [d4a17eb118](https://linux-hardware.org/?probe=d4a17eb118) | Oct 13, 2023 |
| MSI           | B85-G43                     | [8684995c92](https://linux-hardware.org/?probe=8684995c92) | Oct 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [2c2a10deb9](https://linux-hardware.org/?probe=2c2a10deb9) | Oct 12, 2023 |
| ASUSTek       | G11CD                       | [32a4a9380e](https://linux-hardware.org/?probe=32a4a9380e) | Oct 12, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [17b8025f8d](https://linux-hardware.org/?probe=17b8025f8d) | Oct 11, 2023 |
| Gigabyte      | MC12-LE0-00 01000100        | [c95171af54](https://linux-hardware.org/?probe=c95171af54) | Oct 11, 2023 |
| Online Lab... | SR 42                       | [905b8dc78b](https://linux-hardware.org/?probe=905b8dc78b) | Oct 11, 2023 |
| ASUSTek       | H61M-K                      | [77ff5b185a](https://linux-hardware.org/?probe=77ff5b185a) | Oct 11, 2023 |
| Gigabyte      | F2A78M-HD2                  | [4e83b42f8d](https://linux-hardware.org/?probe=4e83b42f8d) | Oct 11, 2023 |
| Intel         | JSL MRD                     | [52918e7bbc](https://linux-hardware.org/?probe=52918e7bbc) | Oct 10, 2023 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | [15d9d16ec9](https://linux-hardware.org/?probe=15d9d16ec9) | Oct 09, 2023 |
| Gigabyte      | H270-HD3-CF                 | [8c6732798b](https://linux-hardware.org/?probe=8c6732798b) | Oct 09, 2023 |
| Pegatron      | Benicia                     | [895d65cd9b](https://linux-hardware.org/?probe=895d65cd9b) | Oct 08, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [26708ac497](https://linux-hardware.org/?probe=26708ac497) | Oct 08, 2023 |
| Shuttle       | FS110                       | [cd7c40ed57](https://linux-hardware.org/?probe=cd7c40ed57) | Oct 08, 2023 |
| Gigabyte      | F2A78M-HD2                  | [e9b2c833e0](https://linux-hardware.org/?probe=e9b2c833e0) | Oct 08, 2023 |
| HP            | 212B                        | [faa56daf1d](https://linux-hardware.org/?probe=faa56daf1d) | Oct 07, 2023 |
| Dell          | 0GK35Y A00                  | [47987fd9dd](https://linux-hardware.org/?probe=47987fd9dd) | Oct 07, 2023 |
| Dell          | 0M5DCD A00                  | [30d2522c95](https://linux-hardware.org/?probe=30d2522c95) | Oct 07, 2023 |
| ASRock        | N68C-GS FX                  | [cfafd2008d](https://linux-hardware.org/?probe=cfafd2008d) | Oct 07, 2023 |
| MSI           | 09AC                        | [f70ac0139f](https://linux-hardware.org/?probe=f70ac0139f) | Oct 07, 2023 |
| Lenovo        | 361A SDK0J40700 WIN 3258... | [9dcc3f1734](https://linux-hardware.org/?probe=9dcc3f1734) | Oct 07, 2023 |
| Dell          | 0XJ5V0 A01                  | [db35d96d14](https://linux-hardware.org/?probe=db35d96d14) | Oct 06, 2023 |
| Lenovo        | ThinkCentre xxx 7090A17     | [669bc2a016](https://linux-hardware.org/?probe=669bc2a016) | Oct 06, 2023 |
| Dell          | 0NK5PH A01                  | [abf0015687](https://linux-hardware.org/?probe=abf0015687) | Oct 06, 2023 |
| Foxconn       | 2ABF                        | [887c13dff8](https://linux-hardware.org/?probe=887c13dff8) | Oct 06, 2023 |
| Foxconn       | 2ABF                        | [5bd11bbd69](https://linux-hardware.org/?probe=5bd11bbd69) | Oct 06, 2023 |
| ASRock        | X470 Master SLI             | [b44384b1ba](https://linux-hardware.org/?probe=b44384b1ba) | Oct 05, 2023 |
| HP            | 18E5                        | [653e855c90](https://linux-hardware.org/?probe=653e855c90) | Oct 05, 2023 |
| Dell          | 0GXM1W A00                  | [529f4a7005](https://linux-hardware.org/?probe=529f4a7005) | Oct 04, 2023 |
| Dell          | 0G785M A00                  | [8edd52e89c](https://linux-hardware.org/?probe=8edd52e89c) | Oct 04, 2023 |
| Lenovo        | 3708 SDK0T76465 WIN 3422... | [d1efe97f1a](https://linux-hardware.org/?probe=d1efe97f1a) | Oct 04, 2023 |
| HP            | 3396                        | [e83b1b4945](https://linux-hardware.org/?probe=e83b1b4945) | Oct 03, 2023 |
| Gigabyte      | A320M-S2H-CF                | [ae9334124d](https://linux-hardware.org/?probe=ae9334124d) | Oct 03, 2023 |
| Gigabyte      | B550M S2H                   | [92cf4d1df2](https://linux-hardware.org/?probe=92cf4d1df2) | Oct 03, 2023 |
| Gigabyte      | B550M S2H                   | [d7efd8ecaa](https://linux-hardware.org/?probe=d7efd8ecaa) | Oct 03, 2023 |
| HP            | 83EF                        | [fc4526b206](https://linux-hardware.org/?probe=fc4526b206) | Oct 03, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [d7108a55e5](https://linux-hardware.org/?probe=d7108a55e5) | Oct 02, 2023 |
| ASRock        | J4105-ITX                   | [f4d4b23c31](https://linux-hardware.org/?probe=f4d4b23c31) | Oct 02, 2023 |
| HP            | 81C5 MVB                    | [ccdf9d0cfa](https://linux-hardware.org/?probe=ccdf9d0cfa) | Oct 02, 2023 |
| Dell          | 0NDYHG A01                  | [c84e2b4e06](https://linux-hardware.org/?probe=c84e2b4e06) | Oct 02, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [ff0e651b1b](https://linux-hardware.org/?probe=ff0e651b1b) | Oct 01, 2023 |
| ASUSTek       | P5Q SE2                     | [df644adbab](https://linux-hardware.org/?probe=df644adbab) | Oct 01, 2023 |
| ASUSTek       | P5Q SE2                     | [2ccade9ad8](https://linux-hardware.org/?probe=2ccade9ad8) | Oct 01, 2023 |
| ASRock        | J4105-ITX                   | [ee4a3e4056](https://linux-hardware.org/?probe=ee4a3e4056) | Oct 01, 2023 |
| HP            | 8055                        | [260bebafcd](https://linux-hardware.org/?probe=260bebafcd) | Oct 01, 2023 |
| HP            | 18E5                        | [1f3e02bd3e](https://linux-hardware.org/?probe=1f3e02bd3e) | Oct 01, 2023 |
| Dell          | 0X8DXD A00                  | [a44e0088f6](https://linux-hardware.org/?probe=a44e0088f6) | Oct 01, 2023 |
| ASRock        | X570 Taichi                 | [7a670fe0ef](https://linux-hardware.org/?probe=7a670fe0ef) | Sep 30, 2023 |
| MSI           | PRO B660M-A DDR4            | [a7683dc02d](https://linux-hardware.org/?probe=a7683dc02d) | Sep 30, 2023 |
| Dell          | 0P301D A00                  | [99587baa3d](https://linux-hardware.org/?probe=99587baa3d) | Sep 30, 2023 |
| Dell          | 0Y958C A00                  | [95bf9d14db](https://linux-hardware.org/?probe=95bf9d14db) | Sep 30, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [5705bf79ad](https://linux-hardware.org/?probe=5705bf79ad) | Sep 30, 2023 |
| Dell          | 0PRR48 A00                  | [52fd06666a](https://linux-hardware.org/?probe=52fd06666a) | Sep 29, 2023 |
| Intel         | H110D4-P1                   | [ccedaaab02](https://linux-hardware.org/?probe=ccedaaab02) | Sep 29, 2023 |
| ASUSTek       | EB1501P                     | [df48fa7e96](https://linux-hardware.org/?probe=df48fa7e96) | Sep 29, 2023 |
| MSI           | H97M-G43                    | [b74346acb3](https://linux-hardware.org/?probe=b74346acb3) | Sep 28, 2023 |
| ASUSTek       | M2N-E SLI                   | [2a5937c5e5](https://linux-hardware.org/?probe=2a5937c5e5) | Sep 28, 2023 |
| Unknown       | Unknown                     | [995b6fba4d](https://linux-hardware.org/?probe=995b6fba4d) | Sep 28, 2023 |
| ASUSTek       | PRIME B365M-A               | [76937ddbce](https://linux-hardware.org/?probe=76937ddbce) | Sep 28, 2023 |
| HP            | 2B35                        | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| MSI           | Z97 PC Mate                 | [15a7321226](https://linux-hardware.org/?probe=15a7321226) | Sep 27, 2023 |
| MSI           | Z97 PC Mate                 | [18bf7cff74](https://linux-hardware.org/?probe=18bf7cff74) | Sep 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [e54490e96a](https://linux-hardware.org/?probe=e54490e96a) | Sep 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [2f574aa287](https://linux-hardware.org/?probe=2f574aa287) | Sep 27, 2023 |
| AZW           | Green G2                    | [cb9b97f24b](https://linux-hardware.org/?probe=cb9b97f24b) | Sep 26, 2023 |
| Supermicro    | X10SDE-DF                   | [c2ba80af3b](https://linux-hardware.org/?probe=c2ba80af3b) | Sep 26, 2023 |
| ASUSTek       | G10DK                       | [882b029219](https://linux-hardware.org/?probe=882b029219) | Sep 25, 2023 |
| Pegatron      | EVANS                       | [b9347254b0](https://linux-hardware.org/?probe=b9347254b0) | Sep 25, 2023 |
| Supermicro    | X10SDE-DF                   | [fb93d199f3](https://linux-hardware.org/?probe=fb93d199f3) | Sep 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [c3e942a9e9](https://linux-hardware.org/?probe=c3e942a9e9) | Sep 24, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [7ecb558538](https://linux-hardware.org/?probe=7ecb558538) | Sep 24, 2023 |
| Supermicro    | X10SDE-DF                   | [b0297cff82](https://linux-hardware.org/?probe=b0297cff82) | Sep 24, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [19757abbb8](https://linux-hardware.org/?probe=19757abbb8) | Sep 23, 2023 |
| HP            | 2B2C                        | [79ccf62c55](https://linux-hardware.org/?probe=79ccf62c55) | Sep 23, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [6f3c1fed91](https://linux-hardware.org/?probe=6f3c1fed91) | Sep 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | [898219c64a](https://linux-hardware.org/?probe=898219c64a) | Sep 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | [988711772b](https://linux-hardware.org/?probe=988711772b) | Sep 22, 2023 |
| HP            | 8643 SMVB                   | [913927a01a](https://linux-hardware.org/?probe=913927a01a) | Sep 22, 2023 |
| ASUSTek       | Z87-A                       | [97747fb973](https://linux-hardware.org/?probe=97747fb973) | Sep 21, 2023 |
| HP            | 3047h                       | [cb19fdc589](https://linux-hardware.org/?probe=cb19fdc589) | Sep 21, 2023 |
| ASUSTek       | P8Z77-M PRO                 | [6fd5940c85](https://linux-hardware.org/?probe=6fd5940c85) | Sep 21, 2023 |
| Unknown       | Unknown                     | [742bffa5fe](https://linux-hardware.org/?probe=742bffa5fe) | Sep 20, 2023 |
| Dell          | 0NK5PH A01                  | [eb3f293f98](https://linux-hardware.org/?probe=eb3f293f98) | Sep 20, 2023 |
| HP            | 212B                        | [f961d48c51](https://linux-hardware.org/?probe=f961d48c51) | Sep 20, 2023 |
| ASUSTek       | Q170M2                      | [962ed87784](https://linux-hardware.org/?probe=962ed87784) | Sep 20, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [07f641459d](https://linux-hardware.org/?probe=07f641459d) | Sep 20, 2023 |
| Dell          | 09KPNV A01                  | [4ce81f3886](https://linux-hardware.org/?probe=4ce81f3886) | Sep 20, 2023 |
| BESSTAR Te... | HM90                        | [bbb35ce98b](https://linux-hardware.org/?probe=bbb35ce98b) | Sep 20, 2023 |
| HP            | 212B                        | [1d71ef5e64](https://linux-hardware.org/?probe=1d71ef5e64) | Sep 19, 2023 |
| MSI           | A320M-A PRO MAX             | [411b34f287](https://linux-hardware.org/?probe=411b34f287) | Sep 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [c7ab5c00f8](https://linux-hardware.org/?probe=c7ab5c00f8) | Sep 19, 2023 |
| Gigabyte      | A320M-S2H-CF                | [717867b71c](https://linux-hardware.org/?probe=717867b71c) | Sep 19, 2023 |
| ASUSTek       | M5A78L-M LX3                | [25d66d7f8a](https://linux-hardware.org/?probe=25d66d7f8a) | Sep 19, 2023 |
| MSI           | H61M-P22                    | [4c32887473](https://linux-hardware.org/?probe=4c32887473) | Sep 18, 2023 |
| Dell          | 0M863N A01                  | [ef0a92ec76](https://linux-hardware.org/?probe=ef0a92ec76) | Sep 17, 2023 |
| HP            | 212B                        | [a041c8b5a9](https://linux-hardware.org/?probe=a041c8b5a9) | Sep 17, 2023 |
| ASUSTek       | Pro H510M-C                 | [aff784bd75](https://linux-hardware.org/?probe=aff784bd75) | Sep 16, 2023 |
| HP            | 3647h                       | [89c406366a](https://linux-hardware.org/?probe=89c406366a) | Sep 16, 2023 |
| Gigabyte      | H55M-UD2H                   | [a95113f868](https://linux-hardware.org/?probe=a95113f868) | Sep 16, 2023 |
| Intel         | DX79SI AAG28808-602         | [2ccc7fc308](https://linux-hardware.org/?probe=2ccc7fc308) | Sep 16, 2023 |
| ASUSTek       | PRIME X670-P                | [76d6f570a8](https://linux-hardware.org/?probe=76d6f570a8) | Sep 16, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [02bd43e898](https://linux-hardware.org/?probe=02bd43e898) | Sep 15, 2023 |
| Dell          | OptiPlex 7010               | [37edc6416e](https://linux-hardware.org/?probe=37edc6416e) | Sep 14, 2023 |
| MSI           | PRO B660M-B DDR4            | [9463a6f106](https://linux-hardware.org/?probe=9463a6f106) | Sep 14, 2023 |
| MSI           | B85-G43 GAMING              | [44d14cb672](https://linux-hardware.org/?probe=44d14cb672) | Sep 14, 2023 |
| Gigabyte      | Z97X-SOC-CF                 | [9c86fc8235](https://linux-hardware.org/?probe=9c86fc8235) | Sep 14, 2023 |
| Packard Be... | MCP73                       | [b47efcac04](https://linux-hardware.org/?probe=b47efcac04) | Sep 13, 2023 |
| AZW           | MINI S 10                   | [f6bc099f62](https://linux-hardware.org/?probe=f6bc099f62) | Sep 13, 2023 |
| MSI           | B450M PRO-VDH               | [c06182cc86](https://linux-hardware.org/?probe=c06182cc86) | Sep 12, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [515cb66794](https://linux-hardware.org/?probe=515cb66794) | Sep 10, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [b771d7b475](https://linux-hardware.org/?probe=b771d7b475) | Sep 10, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [6002a35e23](https://linux-hardware.org/?probe=6002a35e23) | Sep 10, 2023 |
| MSI           | 2A9C                        | [2416e50c09](https://linux-hardware.org/?probe=2416e50c09) | Sep 10, 2023 |
| Intel         | DQ77KB AAG81483-500         | [a6ddf1199e](https://linux-hardware.org/?probe=a6ddf1199e) | Sep 09, 2023 |
| Intel         | DQ77KB AAG81483-500         | [4dccf2a41d](https://linux-hardware.org/?probe=4dccf2a41d) | Sep 09, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [7e478d179a](https://linux-hardware.org/?probe=7e478d179a) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3f937bad2e](https://linux-hardware.org/?probe=3f937bad2e) | Sep 09, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [72bc6278d3](https://linux-hardware.org/?probe=72bc6278d3) | Sep 09, 2023 |
| Intel         | DN2820FYK H24582-204        | [625b62078a](https://linux-hardware.org/?probe=625b62078a) | Sep 09, 2023 |
| Intel         | DN2820FYK H24582-204        | [440c9854ff](https://linux-hardware.org/?probe=440c9854ff) | Sep 09, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [81c167f9f9](https://linux-hardware.org/?probe=81c167f9f9) | Sep 08, 2023 |
| MSI           | B360M GAMING PLUS           | [1faaa87b61](https://linux-hardware.org/?probe=1faaa87b61) | Sep 07, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [f98e7f20ca](https://linux-hardware.org/?probe=f98e7f20ca) | Sep 06, 2023 |
| ASUSTek       | Z97-K                       | [849ecb3c82](https://linux-hardware.org/?probe=849ecb3c82) | Sep 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [03e260aff4](https://linux-hardware.org/?probe=03e260aff4) | Sep 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [c890510220](https://linux-hardware.org/?probe=c890510220) | Sep 06, 2023 |
| Dell          | 0NK5PH A01                  | [49e0ac3e09](https://linux-hardware.org/?probe=49e0ac3e09) | Sep 06, 2023 |
| HP            | 844C                        | [6f4911cda7](https://linux-hardware.org/?probe=6f4911cda7) | Sep 06, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [51202f2fd7](https://linux-hardware.org/?probe=51202f2fd7) | Sep 06, 2023 |
| ASRock        | X570 Taichi                 | [6515c97b89](https://linux-hardware.org/?probe=6515c97b89) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [23f0f9321c](https://linux-hardware.org/?probe=23f0f9321c) | Sep 05, 2023 |
| ASUSTek       | GD30CI                      | [f1c877be0e](https://linux-hardware.org/?probe=f1c877be0e) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | [77c07d0f70](https://linux-hardware.org/?probe=77c07d0f70) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | [a0aaf4be5d](https://linux-hardware.org/?probe=a0aaf4be5d) | Sep 05, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [59b9a21678](https://linux-hardware.org/?probe=59b9a21678) | Sep 04, 2023 |
| ASUSTek       | Pro H510M-C                 | [ea823862a6](https://linux-hardware.org/?probe=ea823862a6) | Sep 04, 2023 |
| HP            | 198E                        | [7f57cfbacc](https://linux-hardware.org/?probe=7f57cfbacc) | Sep 04, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [49e3c842c1](https://linux-hardware.org/?probe=49e3c842c1) | Sep 04, 2023 |
| Gigabyte      | B360HD3                     | [1242798344](https://linux-hardware.org/?probe=1242798344) | Sep 04, 2023 |
| ASUSTek       | VM42                        | [2869496e53](https://linux-hardware.org/?probe=2869496e53) | Sep 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | [9918661e50](https://linux-hardware.org/?probe=9918661e50) | Sep 04, 2023 |
| Lenovo        | Dory CRB                    | [9bacefd984](https://linux-hardware.org/?probe=9bacefd984) | Sep 04, 2023 |
| HP            | 8298                        | [49d5421cb5](https://linux-hardware.org/?probe=49d5421cb5) | Sep 03, 2023 |
| ASUSTek       | A88XM-PLUS                  | [16eb26e2bc](https://linux-hardware.org/?probe=16eb26e2bc) | Sep 03, 2023 |
| Dell          | 0GK35Y A00                  | [d785138af0](https://linux-hardware.org/?probe=d785138af0) | Sep 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | [976846f5c4](https://linux-hardware.org/?probe=976846f5c4) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [ca5351b378](https://linux-hardware.org/?probe=ca5351b378) | Sep 03, 2023 |
| MSI           | PRO X670-P WIFI             | [174cff0e19](https://linux-hardware.org/?probe=174cff0e19) | Sep 02, 2023 |
| MSI           | B450M MORTAR MAX            | [b161a13302](https://linux-hardware.org/?probe=b161a13302) | Sep 02, 2023 |
| HP            | 2B2C                        | [a24d61a0f4](https://linux-hardware.org/?probe=a24d61a0f4) | Sep 02, 2023 |
| Lenovo        | SDK0E50510 WIN              | [84cd7c1a93](https://linux-hardware.org/?probe=84cd7c1a93) | Sep 02, 2023 |
| ASUSTek       | Z97-A                       | [b9d50bc865](https://linux-hardware.org/?probe=b9d50bc865) | Sep 02, 2023 |
| Dell          | 04YP6J A02                  | [02c6b100f0](https://linux-hardware.org/?probe=02c6b100f0) | Sep 02, 2023 |
| HP            | 198E                        | [3f3cb2e64c](https://linux-hardware.org/?probe=3f3cb2e64c) | Sep 02, 2023 |
| Intel         | DN2820FYK H24582-204        | [6decc4abdd](https://linux-hardware.org/?probe=6decc4abdd) | Sep 01, 2023 |
| Acer          | Veriton M4610G              | [a5e1bdfce5](https://linux-hardware.org/?probe=a5e1bdfce5) | Sep 01, 2023 |
| MSI           | A320M PRO-M2 V2             | [35a0110255](https://linux-hardware.org/?probe=35a0110255) | Sep 01, 2023 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [0075af1992](https://linux-hardware.org/?probe=0075af1992) | Sep 01, 2023 |
| AZW           | U59                         | [4cca42eeb3](https://linux-hardware.org/?probe=4cca42eeb3) | Sep 01, 2023 |
| Gigabyte      | X58A-UD3R                   | [8ee240ba0b](https://linux-hardware.org/?probe=8ee240ba0b) | Sep 01, 2023 |
| ASUSTek       | H110M-A/M.2                 | [6010a74736](https://linux-hardware.org/?probe=6010a74736) | Sep 01, 2023 |
| MSI           | Z87-G45 GAMING              | [ce1e538f59](https://linux-hardware.org/?probe=ce1e538f59) | Sep 01, 2023 |
| Shenzhen M... | F6BFC                       | [c5fc2337ec](https://linux-hardware.org/?probe=c5fc2337ec) | Aug 31, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [b1571fcf3b](https://linux-hardware.org/?probe=b1571fcf3b) | Aug 31, 2023 |
| Dell          | 0M5DCD A00                  | [dbc3edd473](https://linux-hardware.org/?probe=dbc3edd473) | Aug 31, 2023 |
| ASUSTek       | P5N-E SLI                   | [04688c03ea](https://linux-hardware.org/?probe=04688c03ea) | Aug 31, 2023 |
| MSI           | X470 GAMING PRO             | [408707e9e6](https://linux-hardware.org/?probe=408707e9e6) | Aug 31, 2023 |
| MSI           | X470 GAMING PRO             | [b00577f6ea](https://linux-hardware.org/?probe=b00577f6ea) | Aug 31, 2023 |
| ASUSTek       | P8Z68-V LX                  | [7de2ff1052](https://linux-hardware.org/?probe=7de2ff1052) | Aug 30, 2023 |
| Alienware     | 0PGRP5 A02                  | [9a95d4ab16](https://linux-hardware.org/?probe=9a95d4ab16) | Aug 30, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [a65c8bb631](https://linux-hardware.org/?probe=a65c8bb631) | Aug 30, 2023 |
| ASUSTek       | A88XM-E/USB                 | [376615315b](https://linux-hardware.org/?probe=376615315b) | Aug 30, 2023 |
| HP            | 876C SMVB                   | [246cb7a1ca](https://linux-hardware.org/?probe=246cb7a1ca) | Aug 30, 2023 |
| Gigabyte      | Z77-D3H                     | [b61285544c](https://linux-hardware.org/?probe=b61285544c) | Aug 30, 2023 |
| HP            | 83EE                        | [d558afff67](https://linux-hardware.org/?probe=d558afff67) | Aug 29, 2023 |
| MSI           | MAG B550 TORPEDO            | [7ac77b7bac](https://linux-hardware.org/?probe=7ac77b7bac) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [d2caf1942c](https://linux-hardware.org/?probe=d2caf1942c) | Aug 28, 2023 |
| ASUSTek       | P5Q                         | [8b814da79a](https://linux-hardware.org/?probe=8b814da79a) | Aug 28, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [f54073855c](https://linux-hardware.org/?probe=f54073855c) | Aug 28, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [4bcfe8de49](https://linux-hardware.org/?probe=4bcfe8de49) | Aug 28, 2023 |
| HP            | 83EF                        | [05c3bcb04f](https://linux-hardware.org/?probe=05c3bcb04f) | Aug 28, 2023 |
| ASUSTek       | Maximus VII RANGER          | [79803f8898](https://linux-hardware.org/?probe=79803f8898) | Aug 28, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [22d4876142](https://linux-hardware.org/?probe=22d4876142) | Aug 28, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [60fddabe34](https://linux-hardware.org/?probe=60fddabe34) | Aug 28, 2023 |
| Dell          | 06X1TJ A00                  | [450512bee1](https://linux-hardware.org/?probe=450512bee1) | Aug 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [9a571d0670](https://linux-hardware.org/?probe=9a571d0670) | Aug 27, 2023 |
| ASUSTek       | Z97-PRO                     | [033aa63d16](https://linux-hardware.org/?probe=033aa63d16) | Aug 27, 2023 |
| ASUSTek       | Z97-PRO                     | [e5600a4d2f](https://linux-hardware.org/?probe=e5600a4d2f) | Aug 27, 2023 |
| HP            | 1495                        | [86b148e011](https://linux-hardware.org/?probe=86b148e011) | Aug 26, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | [206043f3a7](https://linux-hardware.org/?probe=206043f3a7) | Aug 26, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [6a38c0266f](https://linux-hardware.org/?probe=6a38c0266f) | Aug 26, 2023 |
| MSI           | H510M-A PRO                 | [0620b43b6a](https://linux-hardware.org/?probe=0620b43b6a) | Aug 26, 2023 |
| MSI           | B150 GAMING M3              | [5a1ef4b710](https://linux-hardware.org/?probe=5a1ef4b710) | Aug 25, 2023 |
| ASUSTek       | P8Z68-V LE                  | [5457261ab6](https://linux-hardware.org/?probe=5457261ab6) | Aug 25, 2023 |
| ASUSTek       | M32CD4-K                    | [2a4c3a0031](https://linux-hardware.org/?probe=2a4c3a0031) | Aug 25, 2023 |
| Acer          | Aspire XC-705               | [abb2a529c7](https://linux-hardware.org/?probe=abb2a529c7) | Aug 24, 2023 |
| Acer          | Aspire XC-705               | [1e42c10a2f](https://linux-hardware.org/?probe=1e42c10a2f) | Aug 24, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [6486781183](https://linux-hardware.org/?probe=6486781183) | Aug 24, 2023 |
| Acer          | Aspire XC-780               | [e154995d9e](https://linux-hardware.org/?probe=e154995d9e) | Aug 24, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | [18fdc0c2a2](https://linux-hardware.org/?probe=18fdc0c2a2) | Aug 24, 2023 |
| Dell          | 0T7D40 A00                  | [85e74676ed](https://linux-hardware.org/?probe=85e74676ed) | Aug 24, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [bc15f84b8c](https://linux-hardware.org/?probe=bc15f84b8c) | Aug 24, 2023 |
| ASUSTek       | P7H55-USB3                  | [86ca529583](https://linux-hardware.org/?probe=86ca529583) | Aug 23, 2023 |
| ASUSTek       | Q170M2                      | [a3de2e9813](https://linux-hardware.org/?probe=a3de2e9813) | Aug 23, 2023 |
| HP            | 870C                        | [e0f1f3de1f](https://linux-hardware.org/?probe=e0f1f3de1f) | Aug 23, 2023 |
| Intel         | DZ77BH-55K AAG39008-400     | [30c81f585a](https://linux-hardware.org/?probe=30c81f585a) | Aug 23, 2023 |
| Dell          | 0NK5PH A01                  | [3a15964324](https://linux-hardware.org/?probe=3a15964324) | Aug 23, 2023 |
| Dell          | 0NK5PH A00                  | [e0770fc916](https://linux-hardware.org/?probe=e0770fc916) | Aug 23, 2023 |
| Dell          | 0NK5PH A00                  | [7ab825e697](https://linux-hardware.org/?probe=7ab825e697) | Aug 23, 2023 |
| MSI           | A320M-A PRO                 | [c5ea9af7cd](https://linux-hardware.org/?probe=c5ea9af7cd) | Aug 23, 2023 |
| Gigabyte      | M68M-S2P                    | [25729bd4f8](https://linux-hardware.org/?probe=25729bd4f8) | Aug 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [824c7b257e](https://linux-hardware.org/?probe=824c7b257e) | Aug 23, 2023 |
| Dell          | 0M858N A01                  | [f8f62c1afb](https://linux-hardware.org/?probe=f8f62c1afb) | Aug 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [9d10830c14](https://linux-hardware.org/?probe=9d10830c14) | Aug 20, 2023 |
| MSI           | PRO X670-P WIFI             | [0887b2e549](https://linux-hardware.org/?probe=0887b2e549) | Aug 20, 2023 |
| Gigabyte      | GA-N680SLI-DQ6              | [0838a31aaf](https://linux-hardware.org/?probe=0838a31aaf) | Aug 19, 2023 |
| Gigabyte      | G31M-S2L                    | [5768055184](https://linux-hardware.org/?probe=5768055184) | Aug 19, 2023 |
| ASUSTek       | B85M-G                      | [c8eaccabf2](https://linux-hardware.org/?probe=c8eaccabf2) | Aug 18, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | [e5b049be3a](https://linux-hardware.org/?probe=e5b049be3a) | Aug 18, 2023 |
| Gigabyte      | B560 HD3                    | [3dfc4104a4](https://linux-hardware.org/?probe=3dfc4104a4) | Aug 18, 2023 |
| Gigabyte      | H77N-WIFI                   | [687a84cc8b](https://linux-hardware.org/?probe=687a84cc8b) | Aug 18, 2023 |
| Gigabyte      | Z77X-UD5H                   | [63a0a35452](https://linux-hardware.org/?probe=63a0a35452) | Aug 18, 2023 |
| ASUSTek       | Z97-PRO                     | [607356bb8f](https://linux-hardware.org/?probe=607356bb8f) | Aug 17, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [4368fbfada](https://linux-hardware.org/?probe=4368fbfada) | Aug 17, 2023 |
| MSI           | Z87-GD65 GAMING             | [7c09135f98](https://linux-hardware.org/?probe=7c09135f98) | Aug 17, 2023 |
| Unknown       | Unknown                     | [6b82ccd639](https://linux-hardware.org/?probe=6b82ccd639) | Aug 17, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [e4fe24b00a](https://linux-hardware.org/?probe=e4fe24b00a) | Aug 16, 2023 |
| ASUSTek       | PRIME B360M-D               | [cf1c4e8c82](https://linux-hardware.org/?probe=cf1c4e8c82) | Aug 16, 2023 |
| Apple         | Mac-F221BEC8                | [2db998a2ca](https://linux-hardware.org/?probe=2db998a2ca) | Aug 16, 2023 |
| Acer          | EM61SM/EM61PM               | [428f134de7](https://linux-hardware.org/?probe=428f134de7) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [6e7b731daa](https://linux-hardware.org/?probe=6e7b731daa) | Aug 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ec0576c5aa](https://linux-hardware.org/?probe=ec0576c5aa) | Aug 15, 2023 |
| Dell          | 0GX297                      | [0fa81b620e](https://linux-hardware.org/?probe=0fa81b620e) | Aug 14, 2023 |
| AK3V          | 1.0                         | [02b6f071a6](https://linux-hardware.org/?probe=02b6f071a6) | Aug 14, 2023 |
| HP            | 21F5 0A                     | [7a8b1ea89a](https://linux-hardware.org/?probe=7a8b1ea89a) | Aug 14, 2023 |
| Gigabyte      | F2A55M-HD2                  | [bed2e58bf4](https://linux-hardware.org/?probe=bed2e58bf4) | Aug 14, 2023 |
| Gigabyte      | H61N-D2V                    | [19259c73ab](https://linux-hardware.org/?probe=19259c73ab) | Aug 14, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [e2fe66aca4](https://linux-hardware.org/?probe=e2fe66aca4) | Aug 13, 2023 |
| HP            | 8643 SMVB                   | [2832e701f2](https://linux-hardware.org/?probe=2832e701f2) | Aug 12, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [ae7ae594f1](https://linux-hardware.org/?probe=ae7ae594f1) | Aug 12, 2023 |
| Gigabyte      | B550 GAMING X V2            | [1f4aa5bf97](https://linux-hardware.org/?probe=1f4aa5bf97) | Aug 12, 2023 |
| Gigabyte      | M720-US3                    | [222bc02e4f](https://linux-hardware.org/?probe=222bc02e4f) | Aug 11, 2023 |
| Gigabyte      | B450 AORUS M                | [f4a323eb82](https://linux-hardware.org/?probe=f4a323eb82) | Aug 11, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [f711709f3f](https://linux-hardware.org/?probe=f711709f3f) | Aug 11, 2023 |
| MSI           | H410M-A PRO                 | [de3739c2a5](https://linux-hardware.org/?probe=de3739c2a5) | Aug 11, 2023 |
| HP            | 18E7                        | [ff27f888f0](https://linux-hardware.org/?probe=ff27f888f0) | Aug 10, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [0028486d9d](https://linux-hardware.org/?probe=0028486d9d) | Aug 10, 2023 |
| Gigabyte      | B560M DS3H                  | [96d3419a5f](https://linux-hardware.org/?probe=96d3419a5f) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [0521e62bf9](https://linux-hardware.org/?probe=0521e62bf9) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [198fcb1fc2](https://linux-hardware.org/?probe=198fcb1fc2) | Aug 10, 2023 |
| MSI           | Z590-A PRO                  | [4448c9f2e1](https://linux-hardware.org/?probe=4448c9f2e1) | Aug 09, 2023 |
| MSI           | Z590-A PRO                  | [6e1d11025a](https://linux-hardware.org/?probe=6e1d11025a) | Aug 09, 2023 |
| MSI           | Z97-G45 GAMING              | [65d491c109](https://linux-hardware.org/?probe=65d491c109) | Aug 09, 2023 |
| Intel         | DQ77KB AAG40294-401         | [3a761b76d6](https://linux-hardware.org/?probe=3a761b76d6) | Aug 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [0cf2ab49c0](https://linux-hardware.org/?probe=0cf2ab49c0) | Aug 09, 2023 |
| Dell          | 040DDP A00                  | [13d99d66da](https://linux-hardware.org/?probe=13d99d66da) | Aug 09, 2023 |
| Shuttle       | XS35V3                      | [ced8776e4d](https://linux-hardware.org/?probe=ced8776e4d) | Aug 09, 2023 |
| Dell          | 08HPGT A01                  | [273e794a99](https://linux-hardware.org/?probe=273e794a99) | Aug 09, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [ee7bcf8fe1](https://linux-hardware.org/?probe=ee7bcf8fe1) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | [04d19635d5](https://linux-hardware.org/?probe=04d19635d5) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | [671a686166](https://linux-hardware.org/?probe=671a686166) | Aug 08, 2023 |
| Dell          | 0NK5PH A01                  | [eb06b6713d](https://linux-hardware.org/?probe=eb06b6713d) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [d9c999ffa3](https://linux-hardware.org/?probe=d9c999ffa3) | Aug 08, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [c48e0220d8](https://linux-hardware.org/?probe=c48e0220d8) | Aug 08, 2023 |
| Intel         | D33217GKE G76540-203        | [fa0fbda262](https://linux-hardware.org/?probe=fa0fbda262) | Aug 08, 2023 |
| Dell          | 0GWHMW A03                  | [ce5dea2bc6](https://linux-hardware.org/?probe=ce5dea2bc6) | Aug 08, 2023 |
| Dell          | 0GWHMW A03                  | [1ba2de9148](https://linux-hardware.org/?probe=1ba2de9148) | Aug 08, 2023 |
| Intel         | D33217GKE G76540-203        | [f75916b7c7](https://linux-hardware.org/?probe=f75916b7c7) | Aug 08, 2023 |
| Dell          | 08HPGT A01                  | [616f6ba289](https://linux-hardware.org/?probe=616f6ba289) | Aug 08, 2023 |
| Gigabyte      | H610M S2H DDR4              | [ff4ead4bd3](https://linux-hardware.org/?probe=ff4ead4bd3) | Aug 08, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ef73e2e520](https://linux-hardware.org/?probe=ef73e2e520) | Aug 07, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c04ac90ce8](https://linux-hardware.org/?probe=c04ac90ce8) | Aug 07, 2023 |
| ASUSTek       | P5N-E SLI                   | [d552e347f5](https://linux-hardware.org/?probe=d552e347f5) | Aug 07, 2023 |
| MSI           | Z97 GAMING 5                | [d076b394d9](https://linux-hardware.org/?probe=d076b394d9) | Aug 06, 2023 |
| Dell          | 0WMJ54 A01                  | [7f6aa0ed0c](https://linux-hardware.org/?probe=7f6aa0ed0c) | Aug 06, 2023 |
| MSI           | H310M PRO-D                 | [201844f73e](https://linux-hardware.org/?probe=201844f73e) | Aug 06, 2023 |
| Foxconn       | 2AAF                        | [e0b2d4efb6](https://linux-hardware.org/?probe=e0b2d4efb6) | Aug 06, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [7a15d18c93](https://linux-hardware.org/?probe=7a15d18c93) | Aug 06, 2023 |
| ASRock        | Z75 Pro3                    | [597461a5ac](https://linux-hardware.org/?probe=597461a5ac) | Aug 06, 2023 |
| Dell          | 02YYK5 A01                  | [5796ca55ef](https://linux-hardware.org/?probe=5796ca55ef) | Aug 06, 2023 |
| HP            | 1791                        | [4a89aab3d6](https://linux-hardware.org/?probe=4a89aab3d6) | Aug 05, 2023 |
| ASUSTek       | Z87-PRO                     | [9d39447e43](https://linux-hardware.org/?probe=9d39447e43) | Aug 05, 2023 |
| ASUSTek       | PRIME Z270-K                | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| ASUSTek       | P5B-Deluxe                  | [122ba504c1](https://linux-hardware.org/?probe=122ba504c1) | Aug 04, 2023 |
| MSI           | PRO X670-P WIFI             | [cd0d64a16a](https://linux-hardware.org/?probe=cd0d64a16a) | Aug 03, 2023 |
| MSI           | Z97 GAMING 3                | [caac03a431](https://linux-hardware.org/?probe=caac03a431) | Aug 03, 2023 |
| MSI           | 760GM-P23                   | [c9e70623fc](https://linux-hardware.org/?probe=c9e70623fc) | Aug 02, 2023 |
| Intel         | DH67BL AAG10189-211         | [db043e1572](https://linux-hardware.org/?probe=db043e1572) | Aug 02, 2023 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | [5cbdefa7c5](https://linux-hardware.org/?probe=5cbdefa7c5) | Aug 02, 2023 |
| Pegatron      | Benicia                     | [5db4c563c6](https://linux-hardware.org/?probe=5db4c563c6) | Aug 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8353d48977](https://linux-hardware.org/?probe=8353d48977) | Aug 01, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [abe7173905](https://linux-hardware.org/?probe=abe7173905) | Aug 01, 2023 |
| HP            | 1496                        | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [c7f6e64888](https://linux-hardware.org/?probe=c7f6e64888) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4e4e6cd3eb](https://linux-hardware.org/?probe=4e4e6cd3eb) | Jul 31, 2023 |
| Unknown       | Unknown                     | [11d7923fa3](https://linux-hardware.org/?probe=11d7923fa3) | Jul 31, 2023 |
| ASUSTek       | P6T SE                      | [aead9f82b2](https://linux-hardware.org/?probe=aead9f82b2) | Jul 31, 2023 |
| ASUSTek       | P6T SE                      | [9e8f131101](https://linux-hardware.org/?probe=9e8f131101) | Jul 31, 2023 |
| Shuttle       | XS35V3                      | [52c5dda710](https://linux-hardware.org/?probe=52c5dda710) | Jul 31, 2023 |
| Intel         | DH67BL AAG10189-211         | [33ac97b0c6](https://linux-hardware.org/?probe=33ac97b0c6) | Jul 30, 2023 |
| Gigabyte      | X58A-UD7                    | [98759e7a12](https://linux-hardware.org/?probe=98759e7a12) | Jul 30, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [3bbfa332c0](https://linux-hardware.org/?probe=3bbfa332c0) | Jul 30, 2023 |
| ASRock        | B650M PG Riptide            | [9f95c471d0](https://linux-hardware.org/?probe=9f95c471d0) | Jul 30, 2023 |
| Lenovo        | 0C48431 WIN                 | [4e0d5538b2](https://linux-hardware.org/?probe=4e0d5538b2) | Jul 30, 2023 |
| ASUSTek       | P5G41C-M LX                 | [18f28e3fb6](https://linux-hardware.org/?probe=18f28e3fb6) | Jul 29, 2023 |
| Pegatron      | EVANS                       | [323d6a7283](https://linux-hardware.org/?probe=323d6a7283) | Jul 29, 2023 |
| Intel         | D33217GKE G76540-203        | [d551e6904d](https://linux-hardware.org/?probe=d551e6904d) | Jul 29, 2023 |
| Shuttle       | XS35V3                      | [1753d8ab39](https://linux-hardware.org/?probe=1753d8ab39) | Jul 29, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [5473e8bab9](https://linux-hardware.org/?probe=5473e8bab9) | Jul 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [d4774401e3](https://linux-hardware.org/?probe=d4774401e3) | Jul 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [45c79840cc](https://linux-hardware.org/?probe=45c79840cc) | Jul 28, 2023 |
| Pegatron      | 2A99                        | [068f8c77fd](https://linux-hardware.org/?probe=068f8c77fd) | Jul 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | [75dec2a4a4](https://linux-hardware.org/?probe=75dec2a4a4) | Jul 27, 2023 |
| Intel         | D33217GKE G76540-203        | [b4089ed499](https://linux-hardware.org/?probe=b4089ed499) | Jul 26, 2023 |
| Cincoze       | DS-1300.00.001              | [e359107d20](https://linux-hardware.org/?probe=e359107d20) | Jul 26, 2023 |
| Cincoze       | DS-1300.00.001              | [01309bf370](https://linux-hardware.org/?probe=01309bf370) | Jul 26, 2023 |
| Gigabyte      | X570 UD                     | [c693096b39](https://linux-hardware.org/?probe=c693096b39) | Jul 26, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [86e9608516](https://linux-hardware.org/?probe=86e9608516) | Jul 25, 2023 |
| Dell          | 0M5DCD A00                  | [f03fba3891](https://linux-hardware.org/?probe=f03fba3891) | Jul 25, 2023 |
| Gigabyte      | B365M H                     | [12902831a7](https://linux-hardware.org/?probe=12902831a7) | Jul 25, 2023 |
| MSI           | Z77A-GD65                   | [4df7cd69af](https://linux-hardware.org/?probe=4df7cd69af) | Jul 25, 2023 |
| Pegatron      | Benicia                     | [ad8b67f72e](https://linux-hardware.org/?probe=ad8b67f72e) | Jul 24, 2023 |
| Unknown       | 1.2                         | [b18dd168dd](https://linux-hardware.org/?probe=b18dd168dd) | Jul 24, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [f6c6668305](https://linux-hardware.org/?probe=f6c6668305) | Jul 23, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [567693892b](https://linux-hardware.org/?probe=567693892b) | Jul 23, 2023 |
| ASUSTek       | PRIME X570-P                | [c052f51a67](https://linux-hardware.org/?probe=c052f51a67) | Jul 23, 2023 |
| Gigabyte      | P67A-UD3-B3                 | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| ASRock        | B560M Pro4                  | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| ASRock        | 4X4-4000 Series             | [d95040e760](https://linux-hardware.org/?probe=d95040e760) | Jul 23, 2023 |
| ASUSTek       | Q170M2                      | [f3435d221b](https://linux-hardware.org/?probe=f3435d221b) | Jul 21, 2023 |
| ASUSTek       | H110S2                      | [3e43d97432](https://linux-hardware.org/?probe=3e43d97432) | Jul 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [97edd15b78](https://linux-hardware.org/?probe=97edd15b78) | Jul 21, 2023 |
| Dell          | 0D28YY A01                  | [6b01835487](https://linux-hardware.org/?probe=6b01835487) | Jul 20, 2023 |
| MSI           | A88XM-E35 V2                | [7ab6252e08](https://linux-hardware.org/?probe=7ab6252e08) | Jul 19, 2023 |
| Dell          | 0XC7MM A00                  | [8d7dd80fa4](https://linux-hardware.org/?probe=8d7dd80fa4) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [158ce24cd5](https://linux-hardware.org/?probe=158ce24cd5) | Jul 19, 2023 |
| ASUSTek       | PRIME Z390-A                | [94856d413f](https://linux-hardware.org/?probe=94856d413f) | Jul 19, 2023 |
| HP            | 3047h                       | [a45f598a92](https://linux-hardware.org/?probe=a45f598a92) | Jul 18, 2023 |
| ASRock        | H370M Pro4                  | [7682b57f64](https://linux-hardware.org/?probe=7682b57f64) | Jul 18, 2023 |
| ASUSTek       | Z87-C                       | [5324c1542f](https://linux-hardware.org/?probe=5324c1542f) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [25aef4eda4](https://linux-hardware.org/?probe=25aef4eda4) | Jul 18, 2023 |
| HP            | 3047h                       | [614b6a73e0](https://linux-hardware.org/?probe=614b6a73e0) | Jul 17, 2023 |
| Acer          | TDPS05 R3700                | [78a7951688](https://linux-hardware.org/?probe=78a7951688) | Jul 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [fb1a31ec95](https://linux-hardware.org/?probe=fb1a31ec95) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | [1e8eeb8513](https://linux-hardware.org/?probe=1e8eeb8513) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | [8efa3cf99d](https://linux-hardware.org/?probe=8efa3cf99d) | Jul 16, 2023 |
| GEEKOM        | Mini IT 8                   | [4754a5fc1b](https://linux-hardware.org/?probe=4754a5fc1b) | Jul 16, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [7fe3a6b5b2](https://linux-hardware.org/?probe=7fe3a6b5b2) | Jul 16, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [9161db3013](https://linux-hardware.org/?probe=9161db3013) | Jul 15, 2023 |
| ASUSTek       | Z87-C                       | [33e96d6f34](https://linux-hardware.org/?probe=33e96d6f34) | Jul 15, 2023 |
| Gigabyte      | H81M-HD3                    | [4a6f56c54a](https://linux-hardware.org/?probe=4a6f56c54a) | Jul 15, 2023 |
| MSI           | Z590-A PRO                  | [8c4fe85b51](https://linux-hardware.org/?probe=8c4fe85b51) | Jul 15, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [2be21e12f5](https://linux-hardware.org/?probe=2be21e12f5) | Jul 14, 2023 |
| Gigabyte      | H510M H                     | [8771f0ddd0](https://linux-hardware.org/?probe=8771f0ddd0) | Jul 14, 2023 |
| ASUSTek       | M5A78L LE                   | [5e2e7e4f4b](https://linux-hardware.org/?probe=5e2e7e4f4b) | Jul 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| ASUSTek       | P8Z68-V LX                  | [7c9bb65c6a](https://linux-hardware.org/?probe=7c9bb65c6a) | Jul 13, 2023 |
| ASUSTek       | P8Z68-V LX                  | [3795772e96](https://linux-hardware.org/?probe=3795772e96) | Jul 13, 2023 |
| HP            | 1495                        | [fdbc0b7f33](https://linux-hardware.org/?probe=fdbc0b7f33) | Jul 13, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [4875c100c1](https://linux-hardware.org/?probe=4875c100c1) | Jul 12, 2023 |
| Dell          | 0T10XW A01                  | [51cf410b69](https://linux-hardware.org/?probe=51cf410b69) | Jul 12, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [ce55d97846](https://linux-hardware.org/?probe=ce55d97846) | Jul 12, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | [493d7a5ab7](https://linux-hardware.org/?probe=493d7a5ab7) | Jul 12, 2023 |
| MSI           | H81M-P32                    | [2bf59485a6](https://linux-hardware.org/?probe=2bf59485a6) | Jul 12, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| Unknown       | 1.0                         | [73e4a885a4](https://linux-hardware.org/?probe=73e4a885a4) | Jul 11, 2023 |
| Dell          | 048DY8 A00                  | [66c586dfe4](https://linux-hardware.org/?probe=66c586dfe4) | Jul 11, 2023 |
| Foxconn       | 2ABF                        | [0cc7523fc4](https://linux-hardware.org/?probe=0cc7523fc4) | Jul 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c09e539c94](https://linux-hardware.org/?probe=c09e539c94) | Jul 09, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2d5d457159](https://linux-hardware.org/?probe=2d5d457159) | Jul 09, 2023 |
| ASRock        | B650 PG Lightning           | [86c4d26a95](https://linux-hardware.org/?probe=86c4d26a95) | Jul 09, 2023 |
| HP            | 3048h                       | [99232ecd53](https://linux-hardware.org/?probe=99232ecd53) | Jul 09, 2023 |
| Gigabyte      | H410M S2H V2                | [dfc7f7a309](https://linux-hardware.org/?probe=dfc7f7a309) | Jul 09, 2023 |
| Gigabyte      | B450M DS3H-CF               | [144cb029ba](https://linux-hardware.org/?probe=144cb029ba) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [89e81df1b9](https://linux-hardware.org/?probe=89e81df1b9) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [0eaaaced27](https://linux-hardware.org/?probe=0eaaaced27) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [a208acb623](https://linux-hardware.org/?probe=a208acb623) | Jul 08, 2023 |
| Dell          | 096JG8 A01                  | [3bf9689ee5](https://linux-hardware.org/?probe=3bf9689ee5) | Jul 08, 2023 |
| HP            | 3399                        | [432d638098](https://linux-hardware.org/?probe=432d638098) | Jul 08, 2023 |
| ASUSTek       | P8B75-M                     | [1cc2699f88](https://linux-hardware.org/?probe=1cc2699f88) | Jul 08, 2023 |
| ASRock        | Z370 Professional Gaming... | [9101223f5e](https://linux-hardware.org/?probe=9101223f5e) | Jul 07, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [6afd29fd20](https://linux-hardware.org/?probe=6afd29fd20) | Jul 06, 2023 |
| MSI           | Indio                       | [b61c090b7e](https://linux-hardware.org/?probe=b61c090b7e) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| HP            | 83EF                        | [5f850e2bc1](https://linux-hardware.org/?probe=5f850e2bc1) | Jul 04, 2023 |
| Dell          | 0KYWH7 A00                  | [0c16b66976](https://linux-hardware.org/?probe=0c16b66976) | Jul 04, 2023 |
| Intel         | X79-SERVER V1.1             | [b3f63a5b2b](https://linux-hardware.org/?probe=b3f63a5b2b) | Jul 04, 2023 |
| HP            | 1791                        | [64fdea845b](https://linux-hardware.org/?probe=64fdea845b) | Jul 03, 2023 |
| ASRock        | P67 Performance             | [5abbfdce39](https://linux-hardware.org/?probe=5abbfdce39) | Jul 02, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [7429ccb00c](https://linux-hardware.org/?probe=7429ccb00c) | Jul 01, 2023 |
| ASUSTek       | P5E Deluxe                  | [895759fa79](https://linux-hardware.org/?probe=895759fa79) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [4f7a6ff110](https://linux-hardware.org/?probe=4f7a6ff110) | Jul 01, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | [0d3ecc7c44](https://linux-hardware.org/?probe=0d3ecc7c44) | Jun 30, 2023 |
| Gigabyte      | B550M AORUS PRO             | [08d14942e4](https://linux-hardware.org/?probe=08d14942e4) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [6a4f9f32d6](https://linux-hardware.org/?probe=6a4f9f32d6) | Jun 30, 2023 |
| ASUSTek       | P8H67-V                     | [afe93b44f3](https://linux-hardware.org/?probe=afe93b44f3) | Jun 30, 2023 |
| ASUSTek       | PRIME X370-PRO              | [6c7621fe04](https://linux-hardware.org/?probe=6c7621fe04) | Jun 29, 2023 |
| ASUSTek       | PRIME Z270-A                | [171e61b165](https://linux-hardware.org/?probe=171e61b165) | Jun 29, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [49f05e412e](https://linux-hardware.org/?probe=49f05e412e) | Jun 28, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [5c049dc792](https://linux-hardware.org/?probe=5c049dc792) | Jun 28, 2023 |
| ASUSTek       | M4N78                       | [03e5d24ba1](https://linux-hardware.org/?probe=03e5d24ba1) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | [cb40f5d060](https://linux-hardware.org/?probe=cb40f5d060) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | [13ac46e7fb](https://linux-hardware.org/?probe=13ac46e7fb) | Jun 28, 2023 |
| MSI           | H81M-P32                    | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | P8Z77-V                     | [177c923e5a](https://linux-hardware.org/?probe=177c923e5a) | Jun 27, 2023 |
| Unknown       | T3 MRD                      | [7478cd5b81](https://linux-hardware.org/?probe=7478cd5b81) | Jun 27, 2023 |
| Intel         | DN2820FYK H24582-204        | [f296b651e4](https://linux-hardware.org/?probe=f296b651e4) | Jun 27, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [309cb87000](https://linux-hardware.org/?probe=309cb87000) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M91p 7033A1G    | [a3ca410b6a](https://linux-hardware.org/?probe=a3ca410b6a) | Jun 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [3505659de8](https://linux-hardware.org/?probe=3505659de8) | Jun 25, 2023 |
| Dell          | 0J3C2F A00                  | [96184db86b](https://linux-hardware.org/?probe=96184db86b) | Jun 25, 2023 |
| ASUSTek       | P5Q-PRO                     | [eb8a9d675b](https://linux-hardware.org/?probe=eb8a9d675b) | Jun 25, 2023 |
| HP            | 8055                        | [7fac5a1354](https://linux-hardware.org/?probe=7fac5a1354) | Jun 24, 2023 |
| ASRock        | B85 Pro4                    | [f42da342bc](https://linux-hardware.org/?probe=f42da342bc) | Jun 24, 2023 |
| Intel         | DH55HC AAE70933-503         | [8dab0b7f0d](https://linux-hardware.org/?probe=8dab0b7f0d) | Jun 24, 2023 |
| HP            | 1496                        | [9d4549de6c](https://linux-hardware.org/?probe=9d4549de6c) | Jun 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [83eb8cda4a](https://linux-hardware.org/?probe=83eb8cda4a) | Jun 23, 2023 |
| Acer          | WG43M                       | [b3eae58854](https://linux-hardware.org/?probe=b3eae58854) | Jun 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [0a065bce17](https://linux-hardware.org/?probe=0a065bce17) | Jun 22, 2023 |
| Dell          | 0NKW6Y A01                  | [def5a35ba4](https://linux-hardware.org/?probe=def5a35ba4) | Jun 21, 2023 |
| Gigabyte      | Z490 GAMING X               | [596a01e7a5](https://linux-hardware.org/?probe=596a01e7a5) | Jun 21, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | [ff224b2f9d](https://linux-hardware.org/?probe=ff224b2f9d) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | [acbd33c5c8](https://linux-hardware.org/?probe=acbd33c5c8) | Jun 21, 2023 |
| ASUSTek       | PRIME X470-PRO              | [f1acdd3081](https://linux-hardware.org/?probe=f1acdd3081) | Jun 20, 2023 |
| ASUSTek       | Maximus VI HERO             | [ec5318fcd1](https://linux-hardware.org/?probe=ec5318fcd1) | Jun 20, 2023 |
| Dell          | 0VHRW1 A03                  | [f077d9dc8f](https://linux-hardware.org/?probe=f077d9dc8f) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5a51d4431b](https://linux-hardware.org/?probe=5a51d4431b) | Jun 20, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [d9d8f74eca](https://linux-hardware.org/?probe=d9d8f74eca) | Jun 19, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [257c60290f](https://linux-hardware.org/?probe=257c60290f) | Jun 19, 2023 |
| HP            | 1497                        | [a922d11f63](https://linux-hardware.org/?probe=a922d11f63) | Jun 19, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [fcec0ed2a4](https://linux-hardware.org/?probe=fcec0ed2a4) | Jun 19, 2023 |
| ASUSTek       | Maximus VI HERO             | [fcbe9b509b](https://linux-hardware.org/?probe=fcbe9b509b) | Jun 18, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [02de076b1c](https://linux-hardware.org/?probe=02de076b1c) | Jun 18, 2023 |
| HP            | 2820h                       | [b6d16a685f](https://linux-hardware.org/?probe=b6d16a685f) | Jun 17, 2023 |
| Gigabyte      | H81M-S2H                    | [7a3f7dcd73](https://linux-hardware.org/?probe=7a3f7dcd73) | Jun 17, 2023 |
| Dell          | 0P301D A00                  | [91bec0952f](https://linux-hardware.org/?probe=91bec0952f) | Jun 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | [3c45e54fd2](https://linux-hardware.org/?probe=3c45e54fd2) | Jun 17, 2023 |
| Intel         | DQ77KB AAG81483-500         | [f06eae8b41](https://linux-hardware.org/?probe=f06eae8b41) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| ASUSTek       | PRIME X570-P                | [1f5163e415](https://linux-hardware.org/?probe=1f5163e415) | Jun 16, 2023 |
| Unknown       | Unknown                     | [f94cf27a96](https://linux-hardware.org/?probe=f94cf27a96) | Jun 15, 2023 |
| Gigabyte      | B360N WIFI-CF               | [d517ea1435](https://linux-hardware.org/?probe=d517ea1435) | Jun 15, 2023 |
| ASRock        | X470 Master SLI             | [448a3cf6b1](https://linux-hardware.org/?probe=448a3cf6b1) | Jun 15, 2023 |
| ASUSTek       | P6T DELUXE V2               | [887bfc11d5](https://linux-hardware.org/?probe=887bfc11d5) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | [04f1fdc3c9](https://linux-hardware.org/?probe=04f1fdc3c9) | Jun 14, 2023 |
| ASUSTek       | P8B75-M LE                  | [2bc004d4b4](https://linux-hardware.org/?probe=2bc004d4b4) | Jun 14, 2023 |
| MSI           | Z77A-G45                    | [db1a941e2c](https://linux-hardware.org/?probe=db1a941e2c) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [0f19266aaf](https://linux-hardware.org/?probe=0f19266aaf) | Jun 13, 2023 |
| Gigabyte      | G41M-Combo                  | [a22e7ac3ea](https://linux-hardware.org/?probe=a22e7ac3ea) | Jun 13, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [b870560cb8](https://linux-hardware.org/?probe=b870560cb8) | Jun 12, 2023 |
| Biostar       | A520MH                      | [70760c5e70](https://linux-hardware.org/?probe=70760c5e70) | Jun 12, 2023 |
| Supermicro    | X9DAi                       | [07f73cff06](https://linux-hardware.org/?probe=07f73cff06) | Jun 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c433d533f0](https://linux-hardware.org/?probe=c433d533f0) | Jun 11, 2023 |
| ASUSTek       | H110M-PLUS                  | [c544318b46](https://linux-hardware.org/?probe=c544318b46) | Jun 11, 2023 |
| ASUSTek       | V-P5G43 R1.04G              | [e2400bfebe](https://linux-hardware.org/?probe=e2400bfebe) | Jun 11, 2023 |
| ASUSTek       | PRIME X370-PRO              | [008148f553](https://linux-hardware.org/?probe=008148f553) | Jun 11, 2023 |
| HP            | 8643 SMVB                   | [db301ecd59](https://linux-hardware.org/?probe=db301ecd59) | Jun 11, 2023 |
| Acer          | Veriton X2631G V:1.0        | [99f3070065](https://linux-hardware.org/?probe=99f3070065) | Jun 11, 2023 |
| ASUSTek       | M5A78L/USB3                 | [81e4b3fe5c](https://linux-hardware.org/?probe=81e4b3fe5c) | Jun 10, 2023 |
| ASUSTek       | M5A78L/USB3                 | [b5aee5a0a1](https://linux-hardware.org/?probe=b5aee5a0a1) | Jun 10, 2023 |
| Pegatron      | Benicia                     | [c57fee6ea0](https://linux-hardware.org/?probe=c57fee6ea0) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0eae3567d9](https://linux-hardware.org/?probe=0eae3567d9) | Jun 10, 2023 |
| HP            | 339B                        | [bc6de07e07](https://linux-hardware.org/?probe=bc6de07e07) | Jun 09, 2023 |
| ASUSTek       | PRIME X370-PRO              | [77145a587d](https://linux-hardware.org/?probe=77145a587d) | Jun 09, 2023 |
| Gigabyte      | X570 UD                     | [98a10d2fd9](https://linux-hardware.org/?probe=98a10d2fd9) | Jun 08, 2023 |
| Dell          | 0GY6Y8 A02                  | [65f988a0c3](https://linux-hardware.org/?probe=65f988a0c3) | Jun 08, 2023 |
| AZW           | SEi                         | [399b4a7add](https://linux-hardware.org/?probe=399b4a7add) | Jun 08, 2023 |
| Unknown       | Unknown                     | [2c3b00b1ae](https://linux-hardware.org/?probe=2c3b00b1ae) | Jun 08, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [f78a07f792](https://linux-hardware.org/?probe=f78a07f792) | Jun 08, 2023 |
| Techvision    | TVI7309X B0                 | [57b238a5ff](https://linux-hardware.org/?probe=57b238a5ff) | Jun 08, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [87f789c059](https://linux-hardware.org/?probe=87f789c059) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| HP            | 8169                        | [45543e5040](https://linux-hardware.org/?probe=45543e5040) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [8b82994313](https://linux-hardware.org/?probe=8b82994313) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [8f3282c700](https://linux-hardware.org/?probe=8f3282c700) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | [326a620bbd](https://linux-hardware.org/?probe=326a620bbd) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | [9cfd61dae7](https://linux-hardware.org/?probe=9cfd61dae7) | Jun 06, 2023 |
| ASRock        | G41M-GS3                    | [f8789775fe](https://linux-hardware.org/?probe=f8789775fe) | Jun 05, 2023 |
| Intel         | DE3815TYKH H26998-402       | [d2f97c16e9](https://linux-hardware.org/?probe=d2f97c16e9) | Jun 05, 2023 |
| Dell          | 0DF42J A00                  | [c68dff0dd7](https://linux-hardware.org/?probe=c68dff0dd7) | Jun 05, 2023 |
| Gigabyte      | F2A55M-DS2                  | [74b01a9071](https://linux-hardware.org/?probe=74b01a9071) | Jun 05, 2023 |
| HP            | 1850                        | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| Intel         | DH55HC AAE70933-503         | [b3d5e112eb](https://linux-hardware.org/?probe=b3d5e112eb) | Jun 04, 2023 |
| MSI           | H81M-P32                    | [f2423b3ef9](https://linux-hardware.org/?probe=f2423b3ef9) | Jun 04, 2023 |
| MSI           | H81M-P32                    | [f1d0b1d487](https://linux-hardware.org/?probe=f1d0b1d487) | Jun 04, 2023 |
| Acer          | Aspire TC-705               | [8aa3bc4947](https://linux-hardware.org/?probe=8aa3bc4947) | Jun 03, 2023 |
| MSI           | H97M-G43                    | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| Gigabyte      | B650M GAMING X AX           | [610ba5871f](https://linux-hardware.org/?probe=610ba5871f) | Jun 03, 2023 |
| Acer          | Aspire X3950                | [82aa882647](https://linux-hardware.org/?probe=82aa882647) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ECS           | Nettle2                     | [6fe297e475](https://linux-hardware.org/?probe=6fe297e475) | Jun 02, 2023 |
| Acer          | Aspire X3950                | [1c7f0f7567](https://linux-hardware.org/?probe=1c7f0f7567) | Jun 02, 2023 |
| HP            | 802E                        | [1837c96bfd](https://linux-hardware.org/?probe=1837c96bfd) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [def2c6020b](https://linux-hardware.org/?probe=def2c6020b) | Jun 01, 2023 |
| MSI           | H81M-E34                    | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [f517c1893a](https://linux-hardware.org/?probe=f517c1893a) | Jun 01, 2023 |
| HP            | 18E5                        | [9d89c3065b](https://linux-hardware.org/?probe=9d89c3065b) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | [8511ce89ad](https://linux-hardware.org/?probe=8511ce89ad) | Jun 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [9faf2de183](https://linux-hardware.org/?probe=9faf2de183) | Jun 01, 2023 |
| MSI           | B85M-G43                    | [38fb05719a](https://linux-hardware.org/?probe=38fb05719a) | May 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [6c3655186f](https://linux-hardware.org/?probe=6c3655186f) | May 31, 2023 |
| ASUSTek       | P4S8L                       | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| Cincoze       | 1.0.01.001                  | [1552e93368](https://linux-hardware.org/?probe=1552e93368) | May 30, 2023 |
| MSI           | H55M-ED55                   | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| HP            | 0B54h D                     | [c7813156eb](https://linux-hardware.org/?probe=c7813156eb) | May 30, 2023 |
| ASUSTek       | PRIME Z370-P                | [afb02cee29](https://linux-hardware.org/?probe=afb02cee29) | May 29, 2023 |
| MSI           | Z170A MPOWER GAMING TITA... | [0e9239c5f7](https://linux-hardware.org/?probe=0e9239c5f7) | May 29, 2023 |
| Gigabyte      | H410M H                     | [7a52f09646](https://linux-hardware.org/?probe=7a52f09646) | May 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a46f523ea2](https://linux-hardware.org/?probe=a46f523ea2) | May 29, 2023 |
| MSI           | A320M-A PRO                 | [88f3c7f5e5](https://linux-hardware.org/?probe=88f3c7f5e5) | May 29, 2023 |
| ASUSTek       | H81M-C                      | [ece00aac41](https://linux-hardware.org/?probe=ece00aac41) | May 29, 2023 |
| Dell          | 048DY8 A01                  | [9bfe61714e](https://linux-hardware.org/?probe=9bfe61714e) | May 28, 2023 |
| ASRock        | Z370 Professional Gaming... | [f7d00f30cb](https://linux-hardware.org/?probe=f7d00f30cb) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [7af2cff4d7](https://linux-hardware.org/?probe=7af2cff4d7) | May 27, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [449d13baa5](https://linux-hardware.org/?probe=449d13baa5) | May 27, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [7d4df58daf](https://linux-hardware.org/?probe=7d4df58daf) | May 27, 2023 |
| MSI           | H55M-ED55                   | [61e1fc3841](https://linux-hardware.org/?probe=61e1fc3841) | May 27, 2023 |
| Dell          | 0TP406                      | [c7300f35f4](https://linux-hardware.org/?probe=c7300f35f4) | May 26, 2023 |
| ASRock        | X300M-STX                   | [c3af0f3242](https://linux-hardware.org/?probe=c3af0f3242) | May 26, 2023 |
| Dell          | 0NDYHG A01                  | [07be92d6f3](https://linux-hardware.org/?probe=07be92d6f3) | May 26, 2023 |
| ASUSTek       | P4S8L                       | [75096a0d55](https://linux-hardware.org/?probe=75096a0d55) | May 25, 2023 |
| ASRock        | H61M-VG4                    | [4a6c3586fa](https://linux-hardware.org/?probe=4a6c3586fa) | May 25, 2023 |
| Foxconn       | 2ABF                        | [a764ae9f3c](https://linux-hardware.org/?probe=a764ae9f3c) | May 25, 2023 |
| Acer          | EG31M R01-A4                | [447645dad3](https://linux-hardware.org/?probe=447645dad3) | May 25, 2023 |
| Foxconn       | 2ABF                        | [9fbeb26e54](https://linux-hardware.org/?probe=9fbeb26e54) | May 24, 2023 |
| HP            | 1496                        | [2edc574902](https://linux-hardware.org/?probe=2edc574902) | May 24, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [8fd8cdb823](https://linux-hardware.org/?probe=8fd8cdb823) | May 24, 2023 |
| Lenovo        | 318E SDK0L22692 WIN 3792... | [5fb6f16a6d](https://linux-hardware.org/?probe=5fb6f16a6d) | May 24, 2023 |
| ASRock        | E350M1                      | [d366f5f318](https://linux-hardware.org/?probe=d366f5f318) | May 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5837575ac6](https://linux-hardware.org/?probe=5837575ac6) | May 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [dc47e13a60](https://linux-hardware.org/?probe=dc47e13a60) | May 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4e817c1abf](https://linux-hardware.org/?probe=4e817c1abf) | May 23, 2023 |
| ASRock        | E350M1                      | [1debe3dcdf](https://linux-hardware.org/?probe=1debe3dcdf) | May 23, 2023 |
| MSI           | H81M-E34                    | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| HP            | 1791                        | [7fa95d1b7b](https://linux-hardware.org/?probe=7fa95d1b7b) | May 22, 2023 |
| ASRock        | B450 Steel Legend           | [012c721256](https://linux-hardware.org/?probe=012c721256) | May 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2b2367f9b1](https://linux-hardware.org/?probe=2b2367f9b1) | May 22, 2023 |
| MSI           | PRO Z690-A DDR4             | [b3fb445705](https://linux-hardware.org/?probe=b3fb445705) | May 22, 2023 |
| Dell          | 0PC5F7 A03                  | [8b4b66a085](https://linux-hardware.org/?probe=8b4b66a085) | May 22, 2023 |
| HP            | 1589                        | [a7d56849a5](https://linux-hardware.org/?probe=a7d56849a5) | May 22, 2023 |
| Lenovo        | 3753 NOK                    | [f2971c14a7](https://linux-hardware.org/?probe=f2971c14a7) | May 21, 2023 |
| Gigabyte      | B450M H                     | [9db5706bfc](https://linux-hardware.org/?probe=9db5706bfc) | May 21, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [31c946c569](https://linux-hardware.org/?probe=31c946c569) | May 21, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | [14e978a000](https://linux-hardware.org/?probe=14e978a000) | May 20, 2023 |
| ASUSTek       | P8Z77-V                     | [b38a68e146](https://linux-hardware.org/?probe=b38a68e146) | May 20, 2023 |
| MSI           | H97M-G43                    | [2e31a2b7e0](https://linux-hardware.org/?probe=2e31a2b7e0) | May 20, 2023 |
| Pegatron      | Benicia                     | [24fc512198](https://linux-hardware.org/?probe=24fc512198) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9f1830f264](https://linux-hardware.org/?probe=9f1830f264) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [52bfbb69ee](https://linux-hardware.org/?probe=52bfbb69ee) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [6d04bdb08d](https://linux-hardware.org/?probe=6d04bdb08d) | May 19, 2023 |
| Gigabyte      | H55M-USB3                   | [bb5b5bd73c](https://linux-hardware.org/?probe=bb5b5bd73c) | May 19, 2023 |
| Pegatron      | Benicia                     | [6bb420fe9a](https://linux-hardware.org/?probe=6bb420fe9a) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d8d391a609](https://linux-hardware.org/?probe=d8d391a609) | May 18, 2023 |
| Packard Be... | PT890-8237A                 | [b15e7cc105](https://linux-hardware.org/?probe=b15e7cc105) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c09d32ebc2](https://linux-hardware.org/?probe=c09d32ebc2) | May 18, 2023 |
| ASUSTek       | P5KPL-SE                    | [2914e5278a](https://linux-hardware.org/?probe=2914e5278a) | May 18, 2023 |
| ASUSTek       | M4A77TD                     | [ccd791a9d4](https://linux-hardware.org/?probe=ccd791a9d4) | May 18, 2023 |
| Gateway       | DS10G                       | [556a92e56a](https://linux-hardware.org/?probe=556a92e56a) | May 18, 2023 |
| Pegatron      | Benicia                     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Gigabyte      | B560 HD3                    | [2a6dcbf826](https://linux-hardware.org/?probe=2a6dcbf826) | May 17, 2023 |
| ASUSTek       | PRIME B365-PLUS             | [d43fc4e5b9](https://linux-hardware.org/?probe=d43fc4e5b9) | May 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [863f20642f](https://linux-hardware.org/?probe=863f20642f) | May 17, 2023 |
| ASUSTek       | B150-PLUS                   | [41b19667a8](https://linux-hardware.org/?probe=41b19667a8) | May 17, 2023 |
| ASRock        | A300M-STX                   | [b06c75ac5e](https://linux-hardware.org/?probe=b06c75ac5e) | May 16, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [4529ae76bb](https://linux-hardware.org/?probe=4529ae76bb) | May 15, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [6a8a2f481e](https://linux-hardware.org/?probe=6a8a2f481e) | May 15, 2023 |
| ASUSTek       | M5A88-V EVO                 | [02da78340f](https://linux-hardware.org/?probe=02da78340f) | May 15, 2023 |
| HP            | 8436                        | [ae94b377fd](https://linux-hardware.org/?probe=ae94b377fd) | May 15, 2023 |
| Gigabyte      | Z77X-D3H                    | [2e2744285f](https://linux-hardware.org/?probe=2e2744285f) | May 15, 2023 |
| HP            | 3397                        | [c6f97f09f1](https://linux-hardware.org/?probe=c6f97f09f1) | May 13, 2023 |
| ASUSTek       | P5N-E SLI                   | [56783f77b9](https://linux-hardware.org/?probe=56783f77b9) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [ede664c4ca](https://linux-hardware.org/?probe=ede664c4ca) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [4849aadd59](https://linux-hardware.org/?probe=4849aadd59) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [ef9c6905f1](https://linux-hardware.org/?probe=ef9c6905f1) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [bfff1b604f](https://linux-hardware.org/?probe=bfff1b604f) | May 13, 2023 |
| ASUSTek       | GL10CS                      | [270c5658e6](https://linux-hardware.org/?probe=270c5658e6) | May 13, 2023 |
| Dell          | 0D883F A05                  | [99e782e805](https://linux-hardware.org/?probe=99e782e805) | May 13, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | [30bda7d8cb](https://linux-hardware.org/?probe=30bda7d8cb) | May 12, 2023 |
| ASUSTek       | P5B-Deluxe                  | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| Dell          | 04YP6J A02                  | [aec2bbbb46](https://linux-hardware.org/?probe=aec2bbbb46) | May 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [64159d4a10](https://linux-hardware.org/?probe=64159d4a10) | May 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [68caa87cfd](https://linux-hardware.org/?probe=68caa87cfd) | May 11, 2023 |
| Dell          | 09M8Y8 A01                  | [6131eb37d1](https://linux-hardware.org/?probe=6131eb37d1) | May 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | [25b993b097](https://linux-hardware.org/?probe=25b993b097) | May 10, 2023 |
| ASUSTek       | PRIME Z370-P II             | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [dc1db599ea](https://linux-hardware.org/?probe=dc1db599ea) | May 09, 2023 |
| MSI           | B85-G43                     | [461e3ed4bc](https://linux-hardware.org/?probe=461e3ed4bc) | May 09, 2023 |
| Gigabyte      | F2A78M-HD2                  | [0a758d5a5d](https://linux-hardware.org/?probe=0a758d5a5d) | May 08, 2023 |
| Dell          | 0XCR8D A02                  | [5bc5ccdcad](https://linux-hardware.org/?probe=5bc5ccdcad) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4e424e0ad2](https://linux-hardware.org/?probe=4e424e0ad2) | May 08, 2023 |
| Dell          | 0T656F A01                  | [94294c8cf0](https://linux-hardware.org/?probe=94294c8cf0) | May 08, 2023 |
| HP            | 3031h                       | [dc7b257f83](https://linux-hardware.org/?probe=dc7b257f83) | May 08, 2023 |
| ASUSTek       | P5Q SE2                     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [0fa7cb39ce](https://linux-hardware.org/?probe=0fa7cb39ce) | May 07, 2023 |
| ASRock        | X570 Phantom Gaming X       | [4681975f9d](https://linux-hardware.org/?probe=4681975f9d) | May 07, 2023 |
| Shuttle       | FZ77                        | [e4a71bcb2d](https://linux-hardware.org/?probe=e4a71bcb2d) | May 07, 2023 |
| Intel         | WADE-8076-ST-WMS            | [ae71682181](https://linux-hardware.org/?probe=ae71682181) | May 06, 2023 |
| HP            | 1589                        | [dd3e55b423](https://linux-hardware.org/?probe=dd3e55b423) | May 05, 2023 |
| Dell          | 0PU052                      | [03c6b8486e](https://linux-hardware.org/?probe=03c6b8486e) | May 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [11a0e59867](https://linux-hardware.org/?probe=11a0e59867) | May 04, 2023 |
| Acer          | Aspire X1430                | [4bdb74f57e](https://linux-hardware.org/?probe=4bdb74f57e) | May 04, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [da8be5a40f](https://linux-hardware.org/?probe=da8be5a40f) | May 04, 2023 |
| Acer          | H57M01                      | [affe73e1a5](https://linux-hardware.org/?probe=affe73e1a5) | May 03, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [456582ed94](https://linux-hardware.org/?probe=456582ed94) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [f115308631](https://linux-hardware.org/?probe=f115308631) | May 03, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [ee33a17baa](https://linux-hardware.org/?probe=ee33a17baa) | May 02, 2023 |
| HP            | 2AFB                        | [a2d8494867](https://linux-hardware.org/?probe=a2d8494867) | May 01, 2023 |
| MSI           | A320M-A PRO MAX             | [6bfbb6bee6](https://linux-hardware.org/?probe=6bfbb6bee6) | May 01, 2023 |
| ASRock        | H61M-VS                     | [4946cab965](https://linux-hardware.org/?probe=4946cab965) | May 01, 2023 |
| Intel         | DG41RQ AAE54511-203         | [4eb2bc6e88](https://linux-hardware.org/?probe=4eb2bc6e88) | May 01, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | [2fd44c38fd](https://linux-hardware.org/?probe=2fd44c38fd) | May 01, 2023 |
| MSI           | B85-G43 GAMING              | [0d041ed447](https://linux-hardware.org/?probe=0d041ed447) | May 01, 2023 |
| MSI           | X99A GAMING 7               | [dfb285267c](https://linux-hardware.org/?probe=dfb285267c) | May 01, 2023 |
| MSI           | Z77A-G43                    | [02c2bfee54](https://linux-hardware.org/?probe=02c2bfee54) | May 01, 2023 |
| MSI           | IONA                        | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Pegatron      | NARRA5                      | [4c8bb5eff0](https://linux-hardware.org/?probe=4c8bb5eff0) | Apr 30, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [9a1d443928](https://linux-hardware.org/?probe=9a1d443928) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [8cb7a3612c](https://linux-hardware.org/?probe=8cb7a3612c) | Apr 30, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [c203c197b7](https://linux-hardware.org/?probe=c203c197b7) | Apr 29, 2023 |
| ASUSTek       | PRIME X470-PRO              | [244cfe88a4](https://linux-hardware.org/?probe=244cfe88a4) | Apr 29, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [815dd8e866](https://linux-hardware.org/?probe=815dd8e866) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | [266688994a](https://linux-hardware.org/?probe=266688994a) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | [af0663fd52](https://linux-hardware.org/?probe=af0663fd52) | Apr 28, 2023 |
| ASUSTek       | P5Q                         | [6daa7002c8](https://linux-hardware.org/?probe=6daa7002c8) | Apr 27, 2023 |
| ASUSTek       | Z97-P                       | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [e694779b17](https://linux-hardware.org/?probe=e694779b17) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [1e07e42dd3](https://linux-hardware.org/?probe=1e07e42dd3) | Apr 26, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [474c43577f](https://linux-hardware.org/?probe=474c43577f) | Apr 26, 2023 |
| ASUSTek       | P8H67-M                     | [7bed835979](https://linux-hardware.org/?probe=7bed835979) | Apr 26, 2023 |
| HP            | 1825                        | [5a26051aec](https://linux-hardware.org/?probe=5a26051aec) | Apr 26, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [a89604dccd](https://linux-hardware.org/?probe=a89604dccd) | Apr 26, 2023 |
| MSI           | H110M PRO-VD                | [d9decf6f0a](https://linux-hardware.org/?probe=d9decf6f0a) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| ASRock        | G31M-S                      | [98c2b2c382](https://linux-hardware.org/?probe=98c2b2c382) | Apr 25, 2023 |
| ASUSTek       | PRIME X570-P                | [290f3ebad7](https://linux-hardware.org/?probe=290f3ebad7) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | [cb8885f205](https://linux-hardware.org/?probe=cb8885f205) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | [cacc141f4f](https://linux-hardware.org/?probe=cacc141f4f) | Apr 25, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | [f82b3152d0](https://linux-hardware.org/?probe=f82b3152d0) | Apr 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [e4c737a64d](https://linux-hardware.org/?probe=e4c737a64d) | Apr 25, 2023 |
| MSI           | H110M ECO                   | [bfa2b17374](https://linux-hardware.org/?probe=bfa2b17374) | Apr 24, 2023 |
| ASUSTek       | PRIME Z590-P                | [ebe492b020](https://linux-hardware.org/?probe=ebe492b020) | Apr 24, 2023 |
| Gigabyte      | Z97-D3H-CF                  | [a62e386eae](https://linux-hardware.org/?probe=a62e386eae) | Apr 24, 2023 |
| G7-2011       | X79                         | [5070a0a7a7](https://linux-hardware.org/?probe=5070a0a7a7) | Apr 24, 2023 |
| Dell          | 0VHRW1 A03                  | [6316886f98](https://linux-hardware.org/?probe=6316886f98) | Apr 24, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [5e6b796278](https://linux-hardware.org/?probe=5e6b796278) | Apr 24, 2023 |
| Gigabyte      | Z97-D3H-CF                  | [bd9d832f72](https://linux-hardware.org/?probe=bd9d832f72) | Apr 23, 2023 |
| Gigabyte      | Z97P-D3                     | [5da4c37f75](https://linux-hardware.org/?probe=5da4c37f75) | Apr 23, 2023 |
| Shuttle       | DS20U                       | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| HP            | 845A                        | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| MSI           | X370 GAMING PLUS            | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Gigabyte      | EP45-UD3                    | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| Dell          | 0CRH6C A00                  | [cbb78e1785](https://linux-hardware.org/?probe=cbb78e1785) | Apr 22, 2023 |
| Gigabyte      | Z390 UD                     | [c9e17ad011](https://linux-hardware.org/?probe=c9e17ad011) | Apr 22, 2023 |
| MSI           | X399 SLI PLUS               | [ebb44ab29d](https://linux-hardware.org/?probe=ebb44ab29d) | Apr 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [90e0cff0ad](https://linux-hardware.org/?probe=90e0cff0ad) | Apr 22, 2023 |
| ASUSTek       | PRIME X570-P                | [f23eeda727](https://linux-hardware.org/?probe=f23eeda727) | Apr 22, 2023 |
| Gigabyte      | EX58-UD5                    | [1ffb09ff2a](https://linux-hardware.org/?probe=1ffb09ff2a) | Apr 22, 2023 |
| Medion        | MS-7621                     | [efb8293786](https://linux-hardware.org/?probe=efb8293786) | Apr 21, 2023 |
| Intel         | D54250WYK H13922-305        | [a7ef0d6dad](https://linux-hardware.org/?probe=a7ef0d6dad) | Apr 21, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [fd91075868](https://linux-hardware.org/?probe=fd91075868) | Apr 21, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [9f81660d12](https://linux-hardware.org/?probe=9f81660d12) | Apr 20, 2023 |
| Gigabyte      | H61M-DS2                    | [8c43353ee9](https://linux-hardware.org/?probe=8c43353ee9) | Apr 20, 2023 |
| Lenovo        | ThinkCentre M90p 3282B5G    | [9741f7bd1e](https://linux-hardware.org/?probe=9741f7bd1e) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [6ea882bacb](https://linux-hardware.org/?probe=6ea882bacb) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| Gigabyte      | Z97-HD3                     | [8b560b455e](https://linux-hardware.org/?probe=8b560b455e) | Apr 19, 2023 |
| Dell          | 0NDYHG A01                  | [64ea7a1e04](https://linux-hardware.org/?probe=64ea7a1e04) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Intel         | D510MO AAE76523-401         | [cf5c07a318](https://linux-hardware.org/?probe=cf5c07a318) | Apr 19, 2023 |
| ZOTAC         | H67ITX-C-E 02/03/05         | [27131cb048](https://linux-hardware.org/?probe=27131cb048) | Apr 19, 2023 |
| Unknown       | Unknown                     | [bac14fb22e](https://linux-hardware.org/?probe=bac14fb22e) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH X58              | [270e47ceb8](https://linux-hardware.org/?probe=270e47ceb8) | Apr 19, 2023 |
| HP            | 1825                        | [5c637a9ef6](https://linux-hardware.org/?probe=5c637a9ef6) | Apr 18, 2023 |
| HP            | 18E7                        | [ef0b00cf80](https://linux-hardware.org/?probe=ef0b00cf80) | Apr 17, 2023 |
| ASUSTek       | P4C800-E                    | [4521f2b9b4](https://linux-hardware.org/?probe=4521f2b9b4) | Apr 17, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [64e06d7111](https://linux-hardware.org/?probe=64e06d7111) | Apr 17, 2023 |
| ASUSTek       | P5Q DELUXE                  | [ebd62c0513](https://linux-hardware.org/?probe=ebd62c0513) | Apr 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [7820a9b7bc](https://linux-hardware.org/?probe=7820a9b7bc) | Apr 16, 2023 |
| Gigabyte      | Z170-Gaming K3              | [c31465c0a1](https://linux-hardware.org/?probe=c31465c0a1) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [fec4fc20a6](https://linux-hardware.org/?probe=fec4fc20a6) | Apr 16, 2023 |
| eMachines     | E945GCU                     | [4e6aa4be24](https://linux-hardware.org/?probe=4e6aa4be24) | Apr 16, 2023 |
| MSI           | PRO H610M-B DDR4            | [65b2e4afa9](https://linux-hardware.org/?probe=65b2e4afa9) | Apr 16, 2023 |
| Dell          | 0TP412                      | [7491d6d66d](https://linux-hardware.org/?probe=7491d6d66d) | Apr 16, 2023 |
| ASRock        | B560M Pro4                  | [af72ecc689](https://linux-hardware.org/?probe=af72ecc689) | Apr 16, 2023 |
| Dell          | 0TP412                      | [c5f0ba736e](https://linux-hardware.org/?probe=c5f0ba736e) | Apr 16, 2023 |
| MSI           | B150A GAMING PRO            | [26432a7622](https://linux-hardware.org/?probe=26432a7622) | Apr 16, 2023 |
| HP            | 83E2                        | [af01123687](https://linux-hardware.org/?probe=af01123687) | Apr 15, 2023 |
| HP            | 83E2                        | [f5052291a4](https://linux-hardware.org/?probe=f5052291a4) | Apr 15, 2023 |
| HP            | 2B4B                        | [9103ce1fce](https://linux-hardware.org/?probe=9103ce1fce) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [e5b11f4136](https://linux-hardware.org/?probe=e5b11f4136) | Apr 14, 2023 |
| Gigabyte      | P55-UD3R                    | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN         | [9ab9baf194](https://linux-hardware.org/?probe=9ab9baf194) | Apr 14, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [30d6d32fc1](https://linux-hardware.org/?probe=30d6d32fc1) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| Gigabyte      | B460M DS3H V2               | [4e09a1cd3e](https://linux-hardware.org/?probe=4e09a1cd3e) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [d79266b94f](https://linux-hardware.org/?probe=d79266b94f) | Apr 13, 2023 |
| Lenovo        | MAHOBAY                     | [527e436d2b](https://linux-hardware.org/?probe=527e436d2b) | Apr 12, 2023 |
| ASRock        | Z97M Pro4                   | [d98390c8a7](https://linux-hardware.org/?probe=d98390c8a7) | Apr 12, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [0d8eb6aa86](https://linux-hardware.org/?probe=0d8eb6aa86) | Apr 12, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [796f3afe73](https://linux-hardware.org/?probe=796f3afe73) | Apr 12, 2023 |
| Dell          | 0XHGV1 A00                  | [6cbdeb350e](https://linux-hardware.org/?probe=6cbdeb350e) | Apr 12, 2023 |
| Intel         | D33217GKE G76540-203        | [c07a4d67ca](https://linux-hardware.org/?probe=c07a4d67ca) | Apr 12, 2023 |
| Unknown       | SKYBAY                      | [9cd0292459](https://linux-hardware.org/?probe=9cd0292459) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| HP            | 2AF7                        | [e9621d5a9c](https://linux-hardware.org/?probe=e9621d5a9c) | Apr 11, 2023 |
| HP            | 2AF7                        | [b187733415](https://linux-hardware.org/?probe=b187733415) | Apr 11, 2023 |
| HP            | 8298                        | [ccde341ebf](https://linux-hardware.org/?probe=ccde341ebf) | Apr 11, 2023 |
| HP            | 8298                        | [bab1bd2943](https://linux-hardware.org/?probe=bab1bd2943) | Apr 11, 2023 |
| ASRock        | B85M-HDS R2.0               | [24bdbac13a](https://linux-hardware.org/?probe=24bdbac13a) | Apr 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [c31f7b3b5c](https://linux-hardware.org/?probe=c31f7b3b5c) | Apr 10, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [35f953cfe0](https://linux-hardware.org/?probe=35f953cfe0) | Apr 10, 2023 |
| Dell          | 0F6X5P A00                  | [ab53417291](https://linux-hardware.org/?probe=ab53417291) | Apr 10, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [979e7ab8f3](https://linux-hardware.org/?probe=979e7ab8f3) | Apr 10, 2023 |
| Gigabyte      | H61M-D2-B3                  | [bf18b5af69](https://linux-hardware.org/?probe=bf18b5af69) | Apr 10, 2023 |
| Dell          | 0TTDMJ A00                  | [2b039ea053](https://linux-hardware.org/?probe=2b039ea053) | Apr 09, 2023 |
| MSI           | A320M PRO-VD PLUS           | [709cc4af2c](https://linux-hardware.org/?probe=709cc4af2c) | Apr 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [0f364f6e82](https://linux-hardware.org/?probe=0f364f6e82) | Apr 09, 2023 |
| Gigabyte      | B450M H                     | [7806838777](https://linux-hardware.org/?probe=7806838777) | Apr 09, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d01569c067](https://linux-hardware.org/?probe=d01569c067) | Apr 08, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [9cd5518f53](https://linux-hardware.org/?probe=9cd5518f53) | Apr 08, 2023 |
| MSI           | B85-G43                     | [49c7de9ea6](https://linux-hardware.org/?probe=49c7de9ea6) | Apr 08, 2023 |
| ASRock        | X79 Extreme6                | [2b3f00ac79](https://linux-hardware.org/?probe=2b3f00ac79) | Apr 08, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [64b9978ed0](https://linux-hardware.org/?probe=64b9978ed0) | Apr 06, 2023 |
| QTQD          | Unknown                     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| ASRock        | H61M-DGS                    | [e2dd28ca36](https://linux-hardware.org/?probe=e2dd28ca36) | Apr 06, 2023 |
| Dell          | 0F5C5X A00                  | [0e0a176bf8](https://linux-hardware.org/?probe=0e0a176bf8) | Apr 06, 2023 |
| ASUSTek       | H97M-E                      | [4d639304bf](https://linux-hardware.org/?probe=4d639304bf) | Apr 05, 2023 |
| HP            | 84FD                        | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | [eb35e0beff](https://linux-hardware.org/?probe=eb35e0beff) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | [d89431372f](https://linux-hardware.org/?probe=d89431372f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [b5106f816a](https://linux-hardware.org/?probe=b5106f816a) | Apr 04, 2023 |
| MSI           | H110M ECO                   | [983153c81e](https://linux-hardware.org/?probe=983153c81e) | Apr 04, 2023 |
| ASRock        | A320M-DVS R3.0              | [518d9bcac3](https://linux-hardware.org/?probe=518d9bcac3) | Apr 04, 2023 |
| MSI           | MAG B560M MORTAR            | [bbb597effc](https://linux-hardware.org/?probe=bbb597effc) | Apr 04, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [e6b864d24e](https://linux-hardware.org/?probe=e6b864d24e) | Apr 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [248ef68079](https://linux-hardware.org/?probe=248ef68079) | Apr 03, 2023 |
| MSI           | 760GM-P23                   | [7c446415d8](https://linux-hardware.org/?probe=7c446415d8) | Apr 03, 2023 |
| Dell          | 07N90W A02                  | [fd992821e0](https://linux-hardware.org/?probe=fd992821e0) | Apr 03, 2023 |
| Intel         | DG41TY AAE47335-302         | [ecd1f451f0](https://linux-hardware.org/?probe=ecd1f451f0) | Apr 03, 2023 |
| ASRock        | G31M-S                      | [70f35c82f1](https://linux-hardware.org/?probe=70f35c82f1) | Apr 03, 2023 |
| Intel         | DN2820FYK H24582-204        | [ed4e86ebbb](https://linux-hardware.org/?probe=ed4e86ebbb) | Apr 03, 2023 |
| HP            | 1905                        | [2044e303ea](https://linux-hardware.org/?probe=2044e303ea) | Apr 02, 2023 |
| MSI           | A88XM-E35                   | [fb40e13d92](https://linux-hardware.org/?probe=fb40e13d92) | Apr 02, 2023 |
| ASUSTek       | Z97-K                       | [d56ea84c5f](https://linux-hardware.org/?probe=d56ea84c5f) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| ASRock        | FM2A88X+ Killer             | [e1c055e8dc](https://linux-hardware.org/?probe=e1c055e8dc) | Apr 02, 2023 |
| Acer          | Veriton X2632G V:1.0        | [f5eafafc96](https://linux-hardware.org/?probe=f5eafafc96) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | [e97e71fc7a](https://linux-hardware.org/?probe=e97e71fc7a) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | [f96e01d74d](https://linux-hardware.org/?probe=f96e01d74d) | Apr 01, 2023 |
| Dell          | 040DDP A00                  | [0771f1547e](https://linux-hardware.org/?probe=0771f1547e) | Apr 01, 2023 |
| Acer          | RS880M05                    | [bddd902030](https://linux-hardware.org/?probe=bddd902030) | Apr 01, 2023 |
| Acer          | Aspire X3400                | [093b0a0239](https://linux-hardware.org/?probe=093b0a0239) | Apr 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [79ef948789](https://linux-hardware.org/?probe=79ef948789) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [35bae3b94d](https://linux-hardware.org/?probe=35bae3b94d) | Apr 01, 2023 |
| ASUSTek       | PRIME B350M-A               | [f8afb163dc](https://linux-hardware.org/?probe=f8afb163dc) | Apr 01, 2023 |
| MSI           | H97M-G43                    | [b93caf26e4](https://linux-hardware.org/?probe=b93caf26e4) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [3599b8e875](https://linux-hardware.org/?probe=3599b8e875) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d79127e48c](https://linux-hardware.org/?probe=d79127e48c) | Mar 31, 2023 |
| ASUSTek       | P8Z77-V                     | [498726ce78](https://linux-hardware.org/?probe=498726ce78) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Foxconn       | 2ABF                        | [8daf4bf0a5](https://linux-hardware.org/?probe=8daf4bf0a5) | Mar 30, 2023 |
| MSI           | A320M PRO-VD PLUS           | [9e43a17d1a](https://linux-hardware.org/?probe=9e43a17d1a) | Mar 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ad1392d8c0](https://linux-hardware.org/?probe=ad1392d8c0) | Mar 30, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [76e09994d0](https://linux-hardware.org/?probe=76e09994d0) | Mar 30, 2023 |
| Packard Be... | MCP73PV                     | [2082d90602](https://linux-hardware.org/?probe=2082d90602) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [de5bf4239c](https://linux-hardware.org/?probe=de5bf4239c) | Mar 30, 2023 |
| HP            | 82B4                        | [0829a64947](https://linux-hardware.org/?probe=0829a64947) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [cfe80f22f8](https://linux-hardware.org/?probe=cfe80f22f8) | Mar 30, 2023 |
| ASUSTek       | M5A97                       | [4d12d122e1](https://linux-hardware.org/?probe=4d12d122e1) | Mar 30, 2023 |
| Shuttle       | FH170                       | [0fa0f1ab72](https://linux-hardware.org/?probe=0fa0f1ab72) | Mar 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| ASUSTek       | Q170M2                      | [8808e457a1](https://linux-hardware.org/?probe=8808e457a1) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [dadeec8815](https://linux-hardware.org/?probe=dadeec8815) | Mar 29, 2023 |
| ASRock        | X470 Master SLI             | [e4d56ca8c8](https://linux-hardware.org/?probe=e4d56ca8c8) | Mar 28, 2023 |
| ASRock        | H61M-DG3/USB3               | [6e7b188568](https://linux-hardware.org/?probe=6e7b188568) | Mar 28, 2023 |
| HP            | 0A60h                       | [6ad65f4f2b](https://linux-hardware.org/?probe=6ad65f4f2b) | Mar 28, 2023 |
| MSI           | B85-G43                     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [16db0eb166](https://linux-hardware.org/?probe=16db0eb166) | Mar 28, 2023 |
| Dell          | 0WR7PY A01                  | [5f0453caf8](https://linux-hardware.org/?probe=5f0453caf8) | Mar 28, 2023 |
| ASRock        | G31M-S                      | [4ad324790c](https://linux-hardware.org/?probe=4ad324790c) | Mar 28, 2023 |
| ASRock        | G31M-S                      | [225f122e05](https://linux-hardware.org/?probe=225f122e05) | Mar 28, 2023 |
| HP            | 1497                        | [94c6f8a63a](https://linux-hardware.org/?probe=94c6f8a63a) | Mar 27, 2023 |
| Gigabyte      | WRX80-SU8                   | [88c24f7e44](https://linux-hardware.org/?probe=88c24f7e44) | Mar 27, 2023 |
| Dell          | 0G919G A00                  | [139207e1a7](https://linux-hardware.org/?probe=139207e1a7) | Mar 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | [d56f48b9d1](https://linux-hardware.org/?probe=d56f48b9d1) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ebed945eae](https://linux-hardware.org/?probe=ebed945eae) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fd16b858df](https://linux-hardware.org/?probe=fd16b858df) | Mar 27, 2023 |
| ASUSTek       | P8H61-M LE                  | [e834f14d64](https://linux-hardware.org/?probe=e834f14d64) | Mar 27, 2023 |
| HP            | ProLiant ML350 G5           | [b0000fc633](https://linux-hardware.org/?probe=b0000fc633) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Wistron       | ProLiant ML110 G6           | [2e14ac2984](https://linux-hardware.org/?probe=2e14ac2984) | Mar 26, 2023 |
| Dell          | 0VHRW1 A03                  | [9aa3215de8](https://linux-hardware.org/?probe=9aa3215de8) | Mar 26, 2023 |
| ASUSTek       | PRIME H510M-K               | [54e2f18738](https://linux-hardware.org/?probe=54e2f18738) | Mar 26, 2023 |
| Dell          | 0VHRW1 A03                  | [129c2be9aa](https://linux-hardware.org/?probe=129c2be9aa) | Mar 26, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [e6219e18b1](https://linux-hardware.org/?probe=e6219e18b1) | Mar 25, 2023 |
| Dell          | 0654JC A01                  | [3771b8bf2e](https://linux-hardware.org/?probe=3771b8bf2e) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| ASUSTek       | H97-PLUS                    | [30d5652df2](https://linux-hardware.org/?probe=30d5652df2) | Mar 25, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [276aa0b036](https://linux-hardware.org/?probe=276aa0b036) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [623f5742ab](https://linux-hardware.org/?probe=623f5742ab) | Mar 25, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [5fccdb098d](https://linux-hardware.org/?probe=5fccdb098d) | Mar 24, 2023 |
| Lenovo        | SDK0E50519 WIN              | [2fb6bb5874](https://linux-hardware.org/?probe=2fb6bb5874) | Mar 24, 2023 |
| Dell          | 0NK5PH A00                  | [f76bc64ee4](https://linux-hardware.org/?probe=f76bc64ee4) | Mar 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | [8af246641b](https://linux-hardware.org/?probe=8af246641b) | Mar 24, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | [0027308e3d](https://linux-hardware.org/?probe=0027308e3d) | Mar 23, 2023 |
| HP            | 3048h                       | [8cee790d83](https://linux-hardware.org/?probe=8cee790d83) | Mar 23, 2023 |
| HP            | 1905                        | [7bccc34bf4](https://linux-hardware.org/?probe=7bccc34bf4) | Mar 23, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME O... | [d5afcaf7a1](https://linux-hardware.org/?probe=d5afcaf7a1) | Mar 22, 2023 |
| AZW           | GK35                        | [bd935978b7](https://linux-hardware.org/?probe=bd935978b7) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| MSI           | Z77A-GD80                   | [bcb120034c](https://linux-hardware.org/?probe=bcb120034c) | Mar 21, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| HP            | 21F5                        | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| MSI           | H310M PRO-VD                | [1b98d965e7](https://linux-hardware.org/?probe=1b98d965e7) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| ASUSTek       | M3A78-EMH HDMI              | [0aa8c2bf55](https://linux-hardware.org/?probe=0aa8c2bf55) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [bbe02b925a](https://linux-hardware.org/?probe=bbe02b925a) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [d376f92f8d](https://linux-hardware.org/?probe=d376f92f8d) | Mar 19, 2023 |
| Gigabyte      | Z77X-UD5H                   | [dc0a9ba834](https://linux-hardware.org/?probe=dc0a9ba834) | Mar 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| ASUSTek       | F2A85-M PRO                 | [5e3e1f990b](https://linux-hardware.org/?probe=5e3e1f990b) | Mar 18, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [0e6f572d41](https://linux-hardware.org/?probe=0e6f572d41) | Mar 18, 2023 |
| Gigabyte      | G41MT-D3                    | [9a4ac88209](https://linux-hardware.org/?probe=9a4ac88209) | Mar 17, 2023 |
| Gigabyte      | AX370-Gaming 5              | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| HP            | 158A                        | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [293b961af2](https://linux-hardware.org/?probe=293b961af2) | Mar 16, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [c7a98e4c15](https://linux-hardware.org/?probe=c7a98e4c15) | Mar 16, 2023 |
| ASUSTek       | M5A97 R2.0                  | [526e33e980](https://linux-hardware.org/?probe=526e33e980) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | [34ad3eb730](https://linux-hardware.org/?probe=34ad3eb730) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | [06c53ecdec](https://linux-hardware.org/?probe=06c53ecdec) | Mar 15, 2023 |
| MSI           | H510M-A PRO                 | [92c35e8f43](https://linux-hardware.org/?probe=92c35e8f43) | Mar 15, 2023 |
| MSI           | FM2-A55M-E33                | [d6106fe9e3](https://linux-hardware.org/?probe=d6106fe9e3) | Mar 14, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2f69480899](https://linux-hardware.org/?probe=2f69480899) | Mar 14, 2023 |
| Packard Be... | IMEDIA S3840                | [b54abceafe](https://linux-hardware.org/?probe=b54abceafe) | Mar 14, 2023 |
| HP            | 339A                        | [3110e1b98c](https://linux-hardware.org/?probe=3110e1b98c) | Mar 14, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [49737df106](https://linux-hardware.org/?probe=49737df106) | Mar 14, 2023 |
| Foxconn       | 2AAF                        | [6d5e3ffeed](https://linux-hardware.org/?probe=6d5e3ffeed) | Mar 13, 2023 |
| MSI           | B85-G43                     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| MSI           | B85-G43                     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [e259b3e70a](https://linux-hardware.org/?probe=e259b3e70a) | Mar 12, 2023 |
| HP            | 339A                        | [fa78907d67](https://linux-hardware.org/?probe=fa78907d67) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [053e36ef52](https://linux-hardware.org/?probe=053e36ef52) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | [28e364aa1a](https://linux-hardware.org/?probe=28e364aa1a) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | [932497a278](https://linux-hardware.org/?probe=932497a278) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [ef3ba694a9](https://linux-hardware.org/?probe=ef3ba694a9) | Mar 11, 2023 |
| MSI           | B85-G43                     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| HP            | 212B                        | [0ea1ad02f7](https://linux-hardware.org/?probe=0ea1ad02f7) | Mar 11, 2023 |
| Intel         | DH55HC AAE70933-503         | [4d1f3745ac](https://linux-hardware.org/?probe=4d1f3745ac) | Mar 10, 2023 |
| Intel         | DH55HC AAE70933-503         | [46160d5ef3](https://linux-hardware.org/?probe=46160d5ef3) | Mar 10, 2023 |
| Gigabyte      | A320M-H-CF                  | [d519ac8d3e](https://linux-hardware.org/?probe=d519ac8d3e) | Mar 09, 2023 |
| MSI           | Z77A-GD80                   | [3b63adee43](https://linux-hardware.org/?probe=3b63adee43) | Mar 09, 2023 |
| MSI           | Z77A-GD80                   | [f447b1afca](https://linux-hardware.org/?probe=f447b1afca) | Mar 09, 2023 |
| Pegatron      | 2AB5                        | [7e36ff0272](https://linux-hardware.org/?probe=7e36ff0272) | Mar 08, 2023 |
| ASUSTek       | PRIME X570-P                | [588a008ee1](https://linux-hardware.org/?probe=588a008ee1) | Mar 08, 2023 |
| ASUSTek       | H110M-K                     | [f69aaa84ed](https://linux-hardware.org/?probe=f69aaa84ed) | Mar 08, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [cea86809fd](https://linux-hardware.org/?probe=cea86809fd) | Mar 08, 2023 |
| Dell          | 0T10XW A00                  | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Intel         | D33217GKE G76540-203        | [f18444c5dd](https://linux-hardware.org/?probe=f18444c5dd) | Mar 08, 2023 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [79459b8b4b](https://linux-hardware.org/?probe=79459b8b4b) | Mar 08, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [b1a69ac03b](https://linux-hardware.org/?probe=b1a69ac03b) | Mar 08, 2023 |
| MSI           | A320M PRO-VD PLUS           | [85e83db4dc](https://linux-hardware.org/?probe=85e83db4dc) | Mar 08, 2023 |
| Packard Be... | IXTREME M5850               | [60b6ba7904](https://linux-hardware.org/?probe=60b6ba7904) | Mar 07, 2023 |
| Pegatron      | 2AD5                        | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| ASUSTek       | Z97-A                       | [6bc7428949](https://linux-hardware.org/?probe=6bc7428949) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [98f8bd8557](https://linux-hardware.org/?probe=98f8bd8557) | Mar 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [38cb86265f](https://linux-hardware.org/?probe=38cb86265f) | Mar 06, 2023 |
| Dell          | 048DY8 A00                  | [2ae03ba26f](https://linux-hardware.org/?probe=2ae03ba26f) | Mar 06, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [39187f7b13](https://linux-hardware.org/?probe=39187f7b13) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 686      | 16.36%  |
| Ubuntu 22.04       | 305      | 7.27%   |
| Ubuntu 18.04       | 222      | 5.29%   |
| OpenMandriva 4.2   | 185      | 4.41%   |
| Debian 11          | 160      | 3.82%   |
| OpenMandriva 4.3   | 144      | 3.43%   |
| Xubuntu 20.04      | 80       | 1.91%   |
| Arch Rolling       | 69       | 1.65%   |
| OpenMandriva 23.01 | 68       | 1.62%   |
| Linux Mint 20.3    | 65       | 1.55%   |
| Linux Mint 20.1    | 58       | 1.38%   |
| Debian 10          | 58       | 1.38%   |
| Linux Mint 21.1    | 56       | 1.34%   |
| OpenMandriva 23.03 | 50       | 1.19%   |
| Linux Mint 20.2    | 44       | 1.05%   |
| Zorin 16           | 43       | 1.03%   |
| Ubuntu 20.10       | 41       | 0.98%   |
| Ubuntu 21.04       | 40       | 0.95%   |
| Ubuntu 21.10       | 39       | 0.93%   |
| Manjaro            | 39       | 0.93%   |
| OpenMandriva 23.08 | 37       | 0.88%   |
| Linux Mint 19.3    | 37       | 0.88%   |
| Arch               | 37       | 0.88%   |
| Pop!_OS 22.04      | 36       | 0.86%   |
| Kubuntu 20.04      | 36       | 0.86%   |
| Fedora 33          | 35       | 0.83%   |
| Linux Mint 20      | 33       | 0.79%   |
| Fedora 35          | 32       | 0.76%   |
| Ubuntu 23.04       | 31       | 0.74%   |
| Linux Mint 21      | 31       | 0.74%   |
| KDE neon 20.04     | 31       | 0.74%   |
| Ubuntu 19.04       | 29       | 0.69%   |
| Kubuntu 22.04      | 28       | 0.67%   |
| ArcoLinux Rolling  | 28       | 0.67%   |
| Ubuntu 19.10       | 26       | 0.62%   |
| Lubuntu 20.04      | 26       | 0.62%   |
| Xubuntu 22.04      | 25       | 0.6%    |
| Xubuntu 18.04      | 25       | 0.6%    |
| Ubuntu MATE 20.04  | 25       | 0.6%    |
| OpenMandriva 4.50  | 25       | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 1415     | 36.12%  |
| OpenMandriva  | 507      | 12.94%  |
| Linux Mint    | 336      | 8.58%   |
| Debian        | 264      | 6.74%   |
| Fedora        | 158      | 4.03%   |
| Xubuntu       | 151      | 3.85%   |
| Manjaro       | 106      | 2.71%   |
| Arch          | 102      | 2.6%    |
| ROSA          | 94       | 2.4%    |
| Kubuntu       | 92       | 2.35%   |
| Pop!_OS       | 83       | 2.12%   |
| Zorin         | 60       | 1.53%   |
| Ubuntu MATE   | 57       | 1.46%   |
| Lubuntu       | 52       | 1.33%   |
| Ubuntu Unity  | 46       | 1.17%   |
| KDE neon      | 44       | 1.12%   |
| Gentoo        | 33       | 0.84%   |
| ArcoLinux     | 28       | 0.71%   |
| openSUSE      | 26       | 0.66%   |
| Mageia        | 18       | 0.46%   |
| LMDE          | 18       | 0.46%   |
| EndeavourOS   | 17       | 0.43%   |
| Ubuntu Budgie | 16       | 0.41%   |
| Elementary    | 16       | 0.41%   |
| BlackPanther  | 16       | 0.41%   |
| Nobara        | 15       | 0.38%   |
| CentOS        | 15       | 0.38%   |
| Kali          | 12       | 0.31%   |
| Clear Linux   | 11       | 0.28%   |
| Ubuntu Studio | 10       | 0.26%   |
| Devuan        | 10       | 0.26%   |
| MX            | 8        | 0.2%    |
| SteamOS       | 7        | 0.18%   |
| Endless       | 7        | 0.18%   |
| Artix         | 7        | 0.18%   |
| LinuxFX       | 5        | 0.13%   |
| Trisquel      | 4        | 0.1%    |
| Sparky        | 3        | 0.08%   |
| Solus         | 3        | 0.08%   |
| NixOS         | 3        | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 178      | 3.83%   |
| 5.16.7-desktop-1omv4003  | 127      | 2.73%   |
| 6.1.1-desktop-1omv2290   | 61       | 1.31%   |
| 5.4.0-58-generic         | 50       | 1.08%   |
| 6.2.6-desktop-1omv2390   | 46       | 0.99%   |
| 5.4.0-42-generic         | 44       | 0.95%   |
| 5.15.0-56-generic        | 43       | 0.92%   |
| 5.15.0-52-generic        | 39       | 0.84%   |
| 5.15.0-58-generic        | 35       | 0.75%   |
| 6.4.11-desktop-1omv2390  | 32       | 0.69%   |
| 5.4.0-52-generic         | 32       | 0.69%   |
| 5.4.0-65-generic         | 31       | 0.67%   |
| 5.4.0-48-generic         | 31       | 0.67%   |
| 5.4.0-29-generic         | 30       | 0.65%   |
| 5.11.0-37-generic        | 30       | 0.65%   |
| 5.11.0-27-generic        | 29       | 0.62%   |
| 5.4.0-26-generic         | 28       | 0.6%    |
| 5.15.0-48-generic        | 28       | 0.6%    |
| 5.15.0-43-generic        | 28       | 0.6%    |
| 5.8.0-43-generic         | 27       | 0.58%   |
| 5.15.0-46-generic        | 27       | 0.58%   |
| 5.13.0-28-generic        | 27       | 0.58%   |
| 5.8.0-50-generic         | 26       | 0.56%   |
| 5.19.0-38-generic        | 26       | 0.56%   |
| 5.13.0-39-generic        | 26       | 0.56%   |
| 5.4.0-54-generic         | 25       | 0.54%   |
| 5.11.0-38-generic        | 23       | 0.49%   |
| 5.4.0-81-generic         | 21       | 0.45%   |
| 5.15.0-47-generic        | 21       | 0.45%   |
| 5.8.0-48-generic         | 20       | 0.43%   |
| 5.4.0-74-generic         | 20       | 0.43%   |
| 5.19.0-35-generic        | 20       | 0.43%   |
| 5.11.0-40-generic        | 20       | 0.43%   |
| 5.8.0-44-generic         | 19       | 0.41%   |
| 5.4.0-91-generic         | 19       | 0.41%   |
| 5.4.0-73-generic         | 19       | 0.41%   |
| 5.4.0-70-generic         | 19       | 0.41%   |
| 5.4.0-37-generic         | 19       | 0.41%   |
| 5.11.0-41-generic        | 19       | 0.41%   |
| 5.4.0-72-generic         | 18       | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 747      | 17.23%  |
| 5.15.0  | 459      | 10.59%  |
| 5.11.0  | 238      | 5.49%   |
| 5.8.0   | 219      | 5.05%   |
| 4.15.0  | 207      | 4.77%   |
| 5.10.14 | 180      | 4.15%   |
| 5.13.0  | 179      | 4.13%   |
| 5.19.0  | 159      | 3.67%   |
| 5.10.0  | 152      | 3.51%   |
| 5.16.7  | 129      | 2.98%   |
| 5.3.0   | 104      | 2.4%    |
| 6.2.0   | 88       | 2.03%   |
| 6.1.1   | 65       | 1.5%    |
| 5.0.0   | 60       | 1.38%   |
| 4.19.0  | 59       | 1.36%   |
| 4.18.0  | 59       | 1.36%   |
| 6.2.6   | 58       | 1.34%   |
| 6.4.11  | 33       | 0.76%   |
| 6.1.0   | 28       | 0.65%   |
| 5.16.13 | 19       | 0.44%   |
| 4.9.20  | 19       | 0.44%   |
| 4.9.60  | 16       | 0.37%   |
| 6.5.5   | 14       | 0.32%   |
| 5.18.0  | 14       | 0.32%   |
| 5.11.12 | 14       | 0.32%   |
| 4.4.0   | 14       | 0.32%   |
| 4.18.16 | 14       | 0.32%   |
| 6.0.0   | 13       | 0.3%    |
| 5.18.12 | 13       | 0.3%    |
| 5.12.4  | 13       | 0.3%    |
| 6.5.0   | 12       | 0.28%   |
| 5.4.32  | 11       | 0.25%   |
| 6.4.8   | 10       | 0.23%   |
| 6.0.12  | 10       | 0.23%   |
| 5.17.5  | 10       | 0.23%   |
| 5.14.0  | 10       | 0.23%   |
| 3.10.0  | 10       | 0.23%   |
| 6.2.11  | 9        | 0.21%   |
| 5.19.12 | 9        | 0.21%   |
| 5.9.16  | 8        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 788      | 18.39%  |
| 5.15    | 531      | 12.39%  |
| 5.10    | 379      | 8.85%   |
| 5.11    | 278      | 6.49%   |
| 5.8     | 261      | 6.09%   |
| 5.13    | 213      | 4.97%   |
| 4.15    | 208      | 4.86%   |
| 5.19    | 193      | 4.51%   |
| 6.2     | 188      | 4.39%   |
| 5.16    | 182      | 4.25%   |
| 6.1     | 141      | 3.29%   |
| 5.3     | 120      | 2.8%    |
| 4.18    | 74       | 1.73%   |
| 6.4     | 73       | 1.7%    |
| 5.0     | 67       | 1.56%   |
| 4.19    | 66       | 1.54%   |
| 4.9     | 64       | 1.49%   |
| 5.18    | 52       | 1.21%   |
| 6.5     | 48       | 1.12%   |
| 6.0     | 48       | 1.12%   |
| 5.9     | 43       | 1%      |
| 5.17    | 39       | 0.91%   |
| 5.14    | 36       | 0.84%   |
| 6.3     | 33       | 0.77%   |
| 5.6     | 29       | 0.68%   |
| 5.7     | 27       | 0.63%   |
| 5.12    | 27       | 0.63%   |
| 5.5     | 15       | 0.35%   |
| 4.4     | 15       | 0.35%   |
| 4.1     | 13       | 0.3%    |
| 3.10    | 10       | 0.23%   |
| 4.20    | 5        | 0.12%   |
| 4.12    | 4        | 0.09%   |
| 5.2     | 3        | 0.07%   |
| 4.14    | 3        | 0.07%   |
| 5.1     | 2        | 0.05%   |
| 4.8     | 2        | 0.05%   |
| 4.13    | 2        | 0.05%   |
| 6.6     | 1        | 0.02%   |
| 2.6     | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3680     | 97.35%  |
| i686   | 98       | 2.59%   |
| armv7l | 2        | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GNOME             | 1590     | 40.25%  |
| KDE5              | 806      | 20.41%  |
| Unknown           | 419      | 10.61%  |
| XFCE              | 341      | 8.63%   |
| X-Cinnamon        | 261      | 6.61%   |
| MATE              | 155      | 3.92%   |
| LXQt              | 67       | 1.7%    |
| KDE4              | 61       | 1.54%   |
| KDE               | 50       | 1.27%   |
| Unity             | 46       | 1.16%   |
| Cinnamon          | 41       | 1.04%   |
| Budgie            | 19       | 0.48%   |
| Pantheon          | 18       | 0.46%   |
| LXDE              | 18       | 0.46%   |
| i3                | 11       | 0.28%   |
| GNOME Classic     | 9        | 0.23%   |
| GNOME Flashback   | 8        | 0.2%    |
| qtile             | 4        | 0.1%    |
| Deepin            | 4        | 0.1%    |
| bspwm             | 3        | 0.08%   |
| sway              | 2        | 0.05%   |
| icewm             | 2        | 0.05%   |
| Hyprland          | 2        | 0.05%   |
| awesome           | 2        | 0.05%   |
| ubuntu:pika:GNOME | 1        | 0.03%   |
| trinity           | 1        | 0.03%   |
| Openbox           | 1        | 0.03%   |
| LeftWM            | 1        | 0.03%   |
| INPT              | 1        | 0.03%   |
| Hypr              | 1        | 0.03%   |
| GNUstep           | 1        | 0.03%   |
| fluxbox           | 1        | 0.03%   |
| Enlightenment     | 1        | 0.03%   |
| DWM               | 1        | 0.03%   |
| chadwm            | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3019     | 77.23%  |
| Wayland | 533      | 13.64%  |
| Unknown | 182      | 4.66%   |
| Tty     | 175      | 4.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1457     | 36.77%  |
| SDDM    | 810      | 20.44%  |
| GDM     | 550      | 13.88%  |
| GDM3    | 479      | 12.09%  |
| LightDM | 452      | 11.41%  |
| TDM     | 139      | 3.51%   |
| KDM     | 58       | 1.46%   |
| SLiM    | 6        | 0.15%   |
| Ly      | 5        | 0.13%   |
| XDM     | 2        | 0.05%   |
| LXDM    | 2        | 0.05%   |
| WDM     | 1        | 0.03%   |
| NODM    | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| fr_FR       | 2821     | 72.95%  |
| en_US       | 532      | 13.76%  |
| Unknown     | 324      | 8.38%   |
| en_GB       | 56       | 1.45%   |
| C           | 45       | 1.16%   |
| de_DE       | 17       | 0.44%   |
| ru_RU       | 9        | 0.23%   |
| en_IE       | 7        | 0.18%   |
| pt_PT       | 5        | 0.13%   |
| nl_NL       | 5        | 0.13%   |
| es_ES       | 5        | 0.13%   |
| it_IT       | 4        | 0.1%    |
| fr_CA       | 4        | 0.1%    |
| C.UTF8      | 4        | 0.1%    |
| fr_CH       | 3        | 0.08%   |
| en_DK       | 3        | 0.08%   |
| sv_SE       | 2        | 0.05%   |
| fr_FR.UTF8  | 2        | 0.05%   |
| fr_BE       | 2        | 0.05%   |
| sr_RS@latin | 1        | 0.03%   |
| sr_RS       | 1        | 0.03%   |
| ru_UA       | 1        | 0.03%   |
| POSIX       | 1        | 0.03%   |
| nb_NO       | 1        | 0.03%   |
| fr_LU       | 1        | 0.03%   |
| fr_FR.utf-8 | 1        | 0.03%   |
| fi_FI       | 1        | 0.03%   |
| es_ES@euro  | 1        | 0.03%   |
| es_BO       | 1        | 0.03%   |
| en_US.utf-8 | 1        | 0.03%   |
| en_IE@euro  | 1        | 0.03%   |
| en_EN       | 1        | 0.03%   |
| en_AU       | 1        | 0.03%   |
| en_AG       | 1        | 0.03%   |
| en          | 1        | 0.03%   |
| ar_SA       | 1        | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2239     | 57.95%  |
| EFI  | 1625     | 42.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 2989     | 76.13%  |
| Overlay  | 434      | 11.05%  |
| Btrfs    | 225      | 5.73%   |
| Unknown  | 98       | 2.5%    |
| Tmpfs    | 81       | 2.06%   |
| Xfs      | 50       | 1.27%   |
| Zfs      | 28       | 0.71%   |
| Ext3     | 7        | 0.18%   |
| Ext2     | 6        | 0.15%   |
| F2fs     | 4        | 0.1%    |
| Reiserfs | 2        | 0.05%   |
| Rootfs   | 1        | 0.03%   |
| Aufs     | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1645     | 42.03%  |
| Unknown | 1508     | 38.53%  |
| MBR     | 761      | 19.44%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2873     | 73.86%  |
| Yes       | 1017     | 26.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2459     | 63.44%  |
| Yes       | 1417     | 36.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1025     | 27.13%  |
| MSI                                  | 613      | 16.23%  |
| Gigabyte Technology                  | 555      | 14.69%  |
| Dell                                 | 359      | 9.5%    |
| Hewlett-Packard                      | 278      | 7.36%   |
| ASRock                               | 231      | 6.11%   |
| Lenovo                               | 133      | 3.52%   |
| Acer                                 | 89       | 2.36%   |
| Intel                                | 67       | 1.77%   |
| Foxconn                              | 52       | 1.38%   |
| Pegatron                             | 48       | 1.27%   |
| Unknown                              | 47       | 1.24%   |
| Packard Bell                         | 39       | 1.03%   |
| Fujitsu                              | 29       | 0.77%   |
| Medion                               | 20       | 0.53%   |
| Shuttle                              | 18       | 0.48%   |
| eMachines                            | 17       | 0.45%   |
| Supermicro                           | 16       | 0.42%   |
| AZW                                  | 15       | 0.4%    |
| ECS                                  | 14       | 0.37%   |
| Biostar                              | 9        | 0.24%   |
| Apple                                | 9        | 0.24%   |
| Alienware                            | 7        | 0.19%   |
| BESSTAR Tech                         | 6        | 0.16%   |
| ASRockRack                           | 6        | 0.16%   |
| AMI                                  | 6        | 0.16%   |
| ZOTAC                                | 4        | 0.11%   |
| NEC Computers                        | 4        | 0.11%   |
| Huanan                               | 4        | 0.11%   |
| Fujitsu Siemens                      | 4        | 0.11%   |
| OEM                                  | 3        | 0.08%   |
| Gateway                              | 3        | 0.08%   |
| ABIT                                 | 3        | 0.08%   |
| Wistron                              | 2        | 0.05%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.05%   |
| Online Labs                          | 2        | 0.05%   |
| MACHINIST                            | 2        | 0.05%   |
| ICP / iEi                            | 2        | 0.05%   |
| Cincoze                              | 2        | 0.05%   |
| WinFast                              | 1        | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUS All Series             | 132      | 3.49%   |
| Unknown                     | 50       | 1.32%   |
| Gigabyte B450M DS3H         | 30       | 0.79%   |
| Dell OptiPlex 7010          | 23       | 0.61%   |
| Dell OptiPlex 390           | 23       | 0.61%   |
| Dell OptiPlex 9020          | 20       | 0.53%   |
| ASUS PRIME A320M-K          | 18       | 0.48%   |
| MSI MS-7C91                 | 17       | 0.45%   |
| MSI MS-7816                 | 17       | 0.45%   |
| MSI MS-7C37                 | 16       | 0.42%   |
| MSI MS-7C02                 | 16       | 0.42%   |
| Dell OptiPlex 3020          | 16       | 0.42%   |
| MSI MS-7817                 | 14       | 0.37%   |
| MSI MS-7A38                 | 13       | 0.34%   |
| MSI MS-7758                 | 13       | 0.34%   |
| HP Compaq Elite 8300 SFF    | 13       | 0.34%   |
| Gigabyte B450 AORUS ELITE   | 13       | 0.34%   |
| Gigabyte 970A-DS3P          | 13       | 0.34%   |
| ASUS TUF Gaming X570-PLUS   | 13       | 0.34%   |
| MSI MS-7B79                 | 12       | 0.32%   |
| MSI MS-7693                 | 12       | 0.32%   |
| ASUS PRIME X470-PRO         | 12       | 0.32%   |
| ASUS PRIME B450M-A          | 12       | 0.32%   |
| MSI MS-7B86                 | 11       | 0.29%   |
| MSI MS-7B84                 | 11       | 0.29%   |
| MSI MS-7721                 | 11       | 0.29%   |
| HP Compaq 8200 Elite SFF PC | 11       | 0.29%   |
| MSI MS-7850                 | 10       | 0.26%   |
| MSI MS-7821                 | 10       | 0.26%   |
| Dell OptiPlex 3010          | 10       | 0.26%   |
| ASUS P8Z77-V                | 10       | 0.26%   |
| MSI MS-7A32                 | 9        | 0.24%   |
| MSI MS-7924                 | 9        | 0.24%   |
| Gigabyte G41M-Combo         | 9        | 0.24%   |
| Dell Precision T1700        | 9        | 0.24%   |
| Dell OptiPlex 760           | 9        | 0.24%   |
| ASUS TUF Gaming B550-PLUS   | 9        | 0.24%   |
| ASUS TUF B450-PLUS GAMING   | 9        | 0.24%   |
| ASUS P7P55D                 | 9        | 0.24%   |
| ASRock B450M Pro4           | 9        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 210      | 5.56%   |
| ASUS PRIME          | 166      | 4.39%   |
| ASUS All            | 132      | 3.49%   |
| Dell Precision      | 102      | 2.7%    |
| Lenovo ThinkCentre  | 97       | 2.57%   |
| HP Compaq           | 96       | 2.54%   |
| ASUS ROG            | 84       | 2.22%   |
| ASUS TUF            | 70       | 1.85%   |
| Acer Aspire         | 55       | 1.46%   |
| Unknown             | 50       | 1.32%   |
| Gigabyte B450M      | 36       | 0.95%   |
| HP EliteDesk        | 33       | 0.87%   |
| HP ProDesk          | 32       | 0.85%   |
| Packard Bell IMEDIA | 31       | 0.82%   |
| Gigabyte B450       | 27       | 0.71%   |
| ASUS P8Z77-V        | 26       | 0.69%   |
| Fujitsu ESPRIMO     | 23       | 0.61%   |
| Acer Veriton        | 23       | 0.61%   |
| Gigabyte B550       | 21       | 0.56%   |
| Gigabyte X570       | 19       | 0.5%    |
| HP Pavilion         | 18       | 0.48%   |
| MSI MS-7C91         | 17       | 0.45%   |
| MSI MS-7816         | 17       | 0.45%   |
| MSI MS-7C37         | 16       | 0.42%   |
| MSI MS-7C02         | 16       | 0.42%   |
| ASUS P8P67          | 16       | 0.42%   |
| Dell Inspiron       | 15       | 0.4%    |
| ASUS P8H61-M        | 15       | 0.4%    |
| MSI MS-7817         | 14       | 0.37%   |
| HP ProLiant         | 14       | 0.37%   |
| Gigabyte 970A-DS3P  | 14       | 0.37%   |
| ASUS P7P55D         | 14       | 0.37%   |
| ASUS M5A78L-M       | 14       | 0.37%   |
| MSI MS-7A38         | 13       | 0.34%   |
| MSI MS-7758         | 13       | 0.34%   |
| Lenovo IdeaCentre   | 13       | 0.34%   |
| Gigabyte Z390       | 13       | 0.34%   |
| Dell XPS            | 13       | 0.34%   |
| ASUS P5Q            | 13       | 0.34%   |
| ASUS M5A97          | 13       | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 381      | 10.08%  |
| 2012    | 355      | 9.4%    |
| 2013    | 338      | 8.95%   |
| 2011    | 282      | 7.46%   |
| 2014    | 276      | 7.31%   |
| 2020    | 244      | 6.46%   |
| 2010    | 232      | 6.14%   |
| 2019    | 230      | 6.09%   |
| 2009    | 225      | 5.96%   |
| 2015    | 202      | 5.35%   |
| 2017    | 198      | 5.24%   |
| 2008    | 177      | 4.69%   |
| 2021    | 163      | 4.31%   |
| 2016    | 159      | 4.21%   |
| 2007    | 103      | 2.73%   |
| 2006    | 72       | 1.91%   |
| 2022    | 61       | 1.61%   |
| 2005    | 33       | 0.87%   |
| 2023    | 24       | 0.64%   |
| 2004    | 9        | 0.24%   |
| 2003    | 8        | 0.21%   |
| Unknown | 3        | 0.08%   |
| 2001    | 2        | 0.05%   |
| 2002    | 1        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3778     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3671     | 96.96%  |
| Enabled  | 115      | 3.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3777     | 99.97%  |
| Yes  | 1        | 0.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 976      | 25.21%  |
| 8.01-16.0       | 751      | 19.4%   |
| 3.01-4.0        | 656      | 16.95%  |
| 4.01-8.0        | 570      | 14.72%  |
| 32.01-64.0      | 464      | 11.99%  |
| 64.01-256.0     | 131      | 3.38%   |
| 1.01-2.0        | 131      | 3.38%   |
| 24.01-32.0      | 104      | 2.69%   |
| 2.01-3.0        | 56       | 1.45%   |
| 0.51-1.0        | 23       | 0.59%   |
| More than 256.0 | 3        | 0.08%   |
| 0.01-0.5        | 3        | 0.08%   |
| Unknown         | 3        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 1511     | 35.83%  |
| 2.01-3.0    | 946      | 22.43%  |
| 4.01-8.0    | 620      | 14.7%   |
| 3.01-4.0    | 515      | 12.21%  |
| 0.51-1.0    | 309      | 7.33%   |
| 8.01-16.0   | 179      | 4.24%   |
| 0.01-0.5    | 69       | 1.64%   |
| 16.01-24.0  | 39       | 0.92%   |
| 32.01-64.0  | 12       | 0.28%   |
| 24.01-32.0  | 9        | 0.21%   |
| 64.01-256.0 | 4        | 0.09%   |
| Unknown     | 4        | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1471     | 37.18%  |
| 2       | 1103     | 27.88%  |
| 3       | 661      | 16.71%  |
| 4       | 354      | 8.95%   |
| 5       | 161      | 4.07%   |
| 6       | 92       | 2.33%   |
| 7       | 43       | 1.09%   |
| 0       | 31       | 0.78%   |
| 8       | 15       | 0.38%   |
| 9       | 12       | 0.3%    |
| Unknown | 3        | 0.08%   |
| 13      | 2        | 0.05%   |
| 11      | 2        | 0.05%   |
| 25      | 1        | 0.03%   |
| 22      | 1        | 0.03%   |
| 21      | 1        | 0.03%   |
| 17      | 1        | 0.03%   |
| 14      | 1        | 0.03%   |
| 10      | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2113     | 55.1%   |
| No        | 1722     | 44.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3752     | 99.31%  |
| No        | 26       | 0.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2350     | 61.13%  |
| Yes       | 1494     | 38.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2816     | 73.39%  |
| Yes       | 1021     | 26.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| France  | 3778     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Paris            | 478      | 11.67%  |
| Marseille        | 72       | 1.76%   |
| Lyon             | 69       | 1.68%   |
| Strasbourg       | 49       | 1.2%    |
| Toulouse         | 42       | 1.03%   |
| Nantes           | 40       | 0.98%   |
| Roubaix          | 35       | 0.85%   |
| Nice             | 33       | 0.81%   |
| Montpellier      | 33       | 0.81%   |
| Rennes           | 32       | 0.78%   |
| Bordeaux         | 30       | 0.73%   |
| Clichy-sous-Bois | 27       | 0.66%   |
| Grenoble         | 26       | 0.63%   |
| Tours            | 24       | 0.59%   |
| Lille            | 24       | 0.59%   |
| Caen             | 23       | 0.56%   |
| Poitiers         | 19       | 0.46%   |
| La Rochelle      | 17       | 0.41%   |
| Toulon           | 16       | 0.39%   |
| Limoges          | 16       | 0.39%   |
| Nîmes           | 15       | 0.37%   |
| Valenciennes     | 14       | 0.34%   |
| Dijon            | 14       | 0.34%   |
| Amiens           | 14       | 0.34%   |
| Perpignan        | 13       | 0.32%   |
| Pau              | 13       | 0.32%   |
| Besançon        | 13       | 0.32%   |
| Argenteuil       | 13       | 0.32%   |
| Versailles       | 12       | 0.29%   |
| Saint-Nazaire    | 12       | 0.29%   |
| Rouen            | 12       | 0.29%   |
| Metz             | 12       | 0.29%   |
| Colomiers        | 12       | 0.29%   |
| Aubervilliers    | 12       | 0.29%   |
| Aix-en-Provence  | 12       | 0.29%   |
| Vannes           | 11       | 0.27%   |
| Valence          | 11       | 0.27%   |
| Tourcoing        | 11       | 0.27%   |
| Rosny-sous-Bois  | 11       | 0.27%   |
| Orléans         | 11       | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1450     | 2376   | 20.65%  |
| WDC                         | 1276     | 2187   | 18.17%  |
| Samsung Electronics         | 1084     | 1910   | 15.43%  |
| Crucial                     | 569      | 846    | 8.1%    |
| Kingston                    | 364      | 468    | 5.18%   |
| Toshiba                     | 330      | 465    | 4.7%    |
| SanDisk                     | 271      | 371    | 3.86%   |
| Hitachi                     | 229      | 321    | 3.26%   |
| PNY                         | 123      | 160    | 1.75%   |
| Maxtor                      | 112      | 147    | 1.59%   |
| Intel                       | 96       | 121    | 1.37%   |
| Unknown                     | 84       | 128    | 1.2%    |
| HGST                        | 75       | 122    | 1.07%   |
| China                       | 68       | 88     | 0.97%   |
| Corsair                     | 56       | 66     | 0.8%    |
| Phison                      | 55       | 72     | 0.78%   |
| LDLC                        | 54       | 84     | 0.77%   |
| Micron/Crucial Technology   | 49       | 75     | 0.7%    |
| OCZ                         | 46       | 62     | 0.65%   |
| Transcend                   | 37       | 47     | 0.53%   |
| SK hynix                    | 37       | 46     | 0.53%   |
| SPCC                        | 35       | 48     | 0.5%    |
| Micron Technology           | 29       | 39     | 0.41%   |
| A-DATA Technology           | 27       | 30     | 0.38%   |
| Phison Electronics          | 25       | 38     | 0.36%   |
| Emtec                       | 24       | 31     | 0.34%   |
| Gigabyte Technology         | 19       | 22     | 0.27%   |
| Silicon Motion              | 17       | 26     | 0.24%   |
| Intenso                     | 17       | 20     | 0.24%   |
| Unknown                     | 14       | 18     | 0.2%    |
| Hewlett-Packard             | 13       | 52     | 0.19%   |
| ASMT                        | 13       | 17     | 0.19%   |
| TEXTORM                     | 11       | 13     | 0.16%   |
| LITEONIT                    | 11       | 11     | 0.16%   |
| Kingston Technology Company | 11       | 11     | 0.16%   |
| JMicron Technology          | 11       | 22     | 0.16%   |
| Patriot                     | 10       | 16     | 0.14%   |
| Fujitsu                     | 10       | 20     | 0.14%   |
| KIOXIA                      | 9        | 11     | 0.13%   |
| KingSpec                    | 9        | 11     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB                         | 96       | 1.17%   |
| Seagate ST500DM002-1BD142 500GB                   | 93       | 1.13%   |
| Seagate ST2000DM008-2FR102 2TB                    | 92       | 1.12%   |
| Seagate ST1000DM010-2EP102 1TB                    | 90       | 1.09%   |
| Crucial CT240BX500SSD1 240GB                      | 86       | 1.05%   |
| Crucial CT500MX500SSD1 500GB                      | 73       | 0.89%   |
| Seagate ST2000DM001-1ER164 2TB                    | 72       | 0.88%   |
| Samsung SSD 850 EVO 250GB                         | 71       | 0.86%   |
| Seagate ST1000DM003-1ER162 1TB                    | 68       | 0.83%   |
| Kingston SA400S37240G 240GB SSD                   | 66       | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB                    | 63       | 0.77%   |
| Samsung SSD 850 EVO 500GB                         | 63       | 0.77%   |
| Seagate ST2000DM001-1CH164 2TB                    | 59       | 0.72%   |
| Toshiba DT01ACA100 1TB                            | 55       | 0.67%   |
| Crucial CT1000MX500SSD1 1TB                       | 53       | 0.64%   |
| Samsung SSD 860 EVO 1TB                           | 52       | 0.63%   |
| Samsung SSD 860 EVO 250GB                         | 49       | 0.6%    |
| Seagate ST4000DM004-2CV104 4TB                    | 47       | 0.57%   |
| Crucial CT480BX500SSD1 480GB                      | 46       | 0.56%   |
| Seagate ST2000DM006-2DM164 2TB                    | 45       | 0.55%   |
| Kingston SA400S37120G 120GB SSD                   | 43       | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 42       | 0.51%   |
| Seagate ST3500418AS 500GB                         | 40       | 0.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 40       | 0.49%   |
| PNY CS900 120GB SSD                               | 40       | 0.49%   |
| Samsung HD103SJ 1TB                               | 39       | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                  | 39       | 0.47%   |
| Unknown SD/MMC/MS PRO 16GB                        | 38       | 0.46%   |
| Samsung NVMe SSD Drive 500GB                      | 38       | 0.46%   |
| Kingston SA400S37480G 480GB SSD                   | 36       | 0.44%   |
| Samsung SSD 870 QVO 1TB                           | 35       | 0.43%   |
| WDC WD20EZRX-00D8PB0 2TB                          | 34       | 0.41%   |
| Seagate ST1000DM003-1SB102 1TB                    | 34       | 0.41%   |
| PNY CS900 240GB SSD                               | 33       | 0.4%    |
| Toshiba HDWD110 1TB                               | 31       | 0.38%   |
| Seagate ST31000524AS 1TB                          | 31       | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 30       | 0.36%   |
| Samsung SSD 860 QVO 1TB                           | 29       | 0.35%   |
| Samsung SSD 840 EVO 250GB                         | 29       | 0.35%   |
| Samsung HD103UJ 1TB                               | 29       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1427     | 2319   | 39.12%  |
| WDC                 | 1178     | 2007   | 32.29%  |
| Toshiba             | 304      | 423    | 8.33%   |
| Hitachi             | 229      | 321    | 6.28%   |
| Samsung Electronics | 224      | 333    | 6.14%   |
| Maxtor              | 112      | 147    | 3.07%   |
| HGST                | 74       | 120    | 2.03%   |
| Unknown             | 41       | 49     | 1.12%   |
| Fujitsu             | 10       | 20     | 0.27%   |
| Hewlett-Packard     | 9        | 24     | 0.25%   |
| Magnetic Data       | 6        | 6      | 0.16%   |
| ASMT                | 5        | 7      | 0.14%   |
| USB3.0              | 3        | 3      | 0.08%   |
| LaCie               | 3        | 3      | 0.08%   |
| ASMT109x            | 3        | 4      | 0.08%   |
| Apple               | 3        | 3      | 0.08%   |
| Intenso             | 2        | 3      | 0.05%   |
| Initio              | 2        | 2      | 0.05%   |
| H/W                 | 2        | 19     | 0.05%   |
| USB                 | 1        | 3      | 0.03%   |
| Storeva             | 1        | 1      | 0.03%   |
| RSH-319             | 1        | 1      | 0.03%   |
| QEMU                | 1        | 1      | 0.03%   |
| MDT                 | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| JMicron Technology  | 1        | 6      | 0.03%   |
| IB-AC703            | 1        | 1      | 0.03%   |
| External            | 1        | 1      | 0.03%   |
| ExcelStor           | 1        | 1      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 670      | 1041   | 26.32%  |
| Crucial             | 502      | 738    | 19.72%  |
| Kingston            | 324      | 418    | 12.73%  |
| SanDisk             | 219      | 279    | 8.6%    |
| PNY                 | 115      | 148    | 4.52%   |
| WDC                 | 91       | 115    | 3.57%   |
| Intel               | 68       | 86     | 2.67%   |
| China               | 68       | 88     | 2.67%   |
| OCZ                 | 45       | 58     | 1.77%   |
| Transcend           | 36       | 46     | 1.41%   |
| LDLC                | 34       | 42     | 1.34%   |
| SPCC                | 32       | 45     | 1.26%   |
| Corsair             | 31       | 34     | 1.22%   |
| Emtec               | 22       | 26     | 0.86%   |
| A-DATA Technology   | 22       | 25     | 0.86%   |
| SK hynix            | 20       | 27     | 0.79%   |
| Micron Technology   | 20       | 28     | 0.79%   |
| Toshiba             | 18       | 26     | 0.71%   |
| Intenso             | 12       | 14     | 0.47%   |
| LITEONIT            | 11       | 11     | 0.43%   |
| TEXTORM             | 10       | 12     | 0.39%   |
| Patriot             | 9        | 15     | 0.35%   |
| KingSpec            | 9        | 11     | 0.35%   |
| Unknown             | 9        | 12     | 0.35%   |
| Verbatim            | 8        | 8      | 0.31%   |
| Gigabyte Technology | 8        | 10     | 0.31%   |
| SABRENT             | 7        | 7      | 0.27%   |
| LITEON              | 7        | 7      | 0.27%   |
| ASMT                | 7        | 9      | 0.27%   |
| Plextor             | 6        | 6      | 0.24%   |
| KingDian            | 6        | 10     | 0.24%   |
| Goodram             | 5        | 7      | 0.2%    |
| GALAX               | 5        | 5      | 0.2%    |
| Apacer              | 5        | 5      | 0.2%    |
| TO Exter            | 4        | 4      | 0.16%   |
| Seagate             | 4        | 4      | 0.16%   |
| Integral            | 4        | 4      | 0.16%   |
| BAITITON            | 4        | 4      | 0.16%   |
| ASMedia             | 4        | 6      | 0.16%   |
| TCSUNBOW            | 3        | 6      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2741     | 5831   | 47.72%  |
| SSD     | 2071     | 3522   | 36.06%  |
| NVMe    | 789      | 1318   | 13.74%  |
| Unknown | 116      | 218    | 2.02%   |
| MMC     | 27       | 33     | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3498     | 9113   | 76.46%  |
| NVMe | 780      | 1294   | 17.05%  |
| SAS  | 270      | 482    | 5.9%    |
| MMC  | 27       | 33     | 0.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2685     | 5009   | 50.78%  |
| 0.51-1.0   | 1487     | 2481   | 28.13%  |
| 1.01-2.0   | 636      | 1039   | 12.03%  |
| 3.01-4.0   | 227      | 375    | 4.29%   |
| 2.01-3.0   | 162      | 268    | 3.06%   |
| 4.01-10.0  | 73       | 137    | 1.38%   |
| 10.01-20.0 | 17       | 44     | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 863      | 21.22%  |
| 251-500        | 709      | 17.44%  |
| 501-1000       | 610      | 15%     |
| 1001-2000      | 487      | 11.98%  |
| More than 3000 | 380      | 9.35%   |
| 1-20           | 323      | 7.94%   |
| 2001-3000      | 223      | 5.48%   |
| Unknown        | 184      | 4.53%   |
| 51-100         | 182      | 4.48%   |
| 21-50          | 105      | 2.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1309     | 31.44%  |
| 21-50          | 524      | 12.58%  |
| 101-250        | 478      | 11.48%  |
| 51-100         | 419      | 10.06%  |
| 251-500        | 381      | 9.15%   |
| 501-1000       | 370      | 8.89%   |
| 1001-2000      | 265      | 6.36%   |
| Unknown        | 184      | 4.42%   |
| More than 3000 | 143      | 3.43%   |
| 2001-3000      | 90       | 2.16%   |
| 0              | 1        | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 13       | 14     | 1.77%   |
| Seagate ST2000DM001-1ER164 2TB    | 8        | 13     | 1.09%   |
| Seagate ST2000DM001-1CH164 2TB    | 8        | 9      | 1.09%   |
| Seagate ST31000528AS 1TB          | 7        | 8      | 0.95%   |
| Seagate ST31000524AS 1TB          | 7        | 7      | 0.95%   |
| Samsung Electronics HD103SJ 1TB   | 7        | 8      | 0.95%   |
| Crucial CT240M500SSD1 240GB       | 7        | 8      | 0.95%   |
| WDC WD10EADS-22M2B0 1TB           | 6        | 6      | 0.82%   |
| Seagate ST3500418AS 500GB         | 6        | 6      | 0.82%   |
| Seagate ST3250310AS 250GB         | 6        | 6      | 0.82%   |
| WDC WD6400AAKS-22A7B2 640GB       | 5        | 8      | 0.68%   |
| WDC WD10EARS-00Y5B1 1TB           | 5        | 6      | 0.68%   |
| WDC WD10EADS-65L5B1 1TB           | 5        | 5      | 0.68%   |
| WDC WD10EADS-00M2B0 1TB           | 5        | 7      | 0.68%   |
| Toshiba DT01ACA100 1TB            | 5        | 6      | 0.68%   |
| Seagate ST3320820AS 320GB         | 5        | 5      | 0.68%   |
| Samsung Electronics HD103UJ 1TB   | 5        | 7      | 0.68%   |
| Maxtor 6V160E0 160GB              | 5        | 5      | 0.68%   |
| LDLC SSD 120GB                    | 5        | 5      | 0.68%   |
| Kingston SV300S37A120G 120GB SSD  | 5        | 7      | 0.68%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 4        | 5      | 0.54%   |
| WDC WD5000AAKX-001CA0 500GB       | 4        | 6      | 0.54%   |
| WDC WD3200AAKS-00L9A0 320GB       | 4        | 4      | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB          | 4        | 8      | 0.54%   |
| WDC WD10EZEX-21M2NA0 1TB          | 4        | 4      | 0.54%   |
| WDC WD1002FAEX-00Z3A0 1TB         | 4        | 5      | 0.54%   |
| Seagate ST3500320AS 500GB         | 4        | 4      | 0.54%   |
| Seagate ST250DM000-1BD141 250GB   | 4        | 4      | 0.54%   |
| Seagate ST2000DM001-9YN164 2TB    | 4        | 4      | 0.54%   |
| Seagate ST1000DM003-9YN162 1TB    | 4        | 5      | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB    | 4        | 4      | 0.54%   |
| Samsung Electronics HD321KJ 320GB | 4        | 4      | 0.54%   |
| Samsung Electronics HD103SI 1TB   | 4        | 4      | 0.54%   |
| Maxtor STM3500320AS 500GB         | 4        | 5      | 0.54%   |
| Maxtor STM3250310AS 250GB         | 4        | 7      | 0.54%   |
| Maxtor 6B200M0 208GB              | 4        | 5      | 0.54%   |
| Intel SSDSC2CW120A3 120GB         | 4        | 4      | 0.54%   |
| Hitachi HDS721010CLA332 1TB       | 4        | 7      | 0.54%   |
| Crucial CT275MX300SSD1 275GB      | 4        | 5      | 0.54%   |
| Crucial CT128MX100SSD1 128GB      | 4        | 4      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 209      | 267    | 29.6%   |
| Seagate             | 193      | 232    | 27.34%  |
| Samsung Electronics | 60       | 73     | 8.5%    |
| Hitachi             | 43       | 54     | 6.09%   |
| Maxtor              | 39       | 44     | 5.52%   |
| Crucial             | 29       | 33     | 4.11%   |
| Toshiba             | 24       | 31     | 3.4%    |
| Kingston            | 19       | 24     | 2.69%   |
| Intel               | 16       | 19     | 2.27%   |
| HGST                | 11       | 14     | 1.56%   |
| SanDisk             | 10       | 12     | 1.42%   |
| OCZ                 | 9        | 10     | 1.27%   |
| LDLC                | 7        | 7      | 0.99%   |
| SK hynix            | 5        | 9      | 0.71%   |
| China               | 3        | 3      | 0.42%   |
| A-DATA Technology   | 3        | 3      | 0.42%   |
| SPCC                | 2        | 2      | 0.28%   |
| Micron Technology   | 2        | 2      | 0.28%   |
| LITEONIT            | 2        | 2      | 0.28%   |
| Hewlett-Packard     | 2        | 2      | 0.28%   |
| Fujitsu             | 2        | 2      | 0.28%   |
| Corsair             | 2        | 2      | 0.28%   |
| Transcend           | 1        | 2      | 0.14%   |
| TEXTORM             | 1        | 1      | 0.14%   |
| SABRENT             | 1        | 1      | 0.14%   |
| Patriot             | 1        | 1      | 0.14%   |
| OCZ-VERTEX          | 1        | 1      | 0.14%   |
| Netac               | 1        | 1      | 0.14%   |
| Magnetic Data       | 1        | 1      | 0.14%   |
| KingSpec            | 1        | 1      | 0.14%   |
| JMicron Technology  | 1        | 2      | 0.14%   |
| INNOVATION IT       | 1        | 1      | 0.14%   |
| EXRAM               | 1        | 1      | 0.14%   |
| ASMT                | 1        | 1      | 0.14%   |
| Apacer              | 1        | 1      | 0.14%   |
| 2.5"                | 1        | 4      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 205      | 263    | 36.54%  |
| Seagate             | 193      | 232    | 34.4%   |
| Hitachi             | 43       | 54     | 7.66%   |
| Samsung Electronics | 42       | 50     | 7.49%   |
| Maxtor              | 39       | 44     | 6.95%   |
| Toshiba             | 23       | 30     | 4.1%    |
| HGST                | 11       | 14     | 1.96%   |
| Hewlett-Packard     | 2        | 2      | 0.36%   |
| Fujitsu             | 2        | 2      | 0.36%   |
| Magnetic Data       | 1        | 1      | 0.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 495      | 692    | 77.59%  |
| SSD     | 133      | 163    | 20.85%  |
| NVMe    | 9        | 9      | 1.41%   |
| Unknown | 1        | 2      | 0.16%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD800BB-00FJA0 80GB                          | 1        | 1      | 6.67%   |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1        | 1      | 6.67%   |
| WDC WD3200AAJS-22VWA0 320GB                      | 1        | 1      | 6.67%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1        | 2      | 6.67%   |
| WDC WD20EARS-00J99B0 2TB                         | 1        | 2      | 6.67%   |
| WDC WD10EALX-759BA1 1TB                          | 1        | 1      | 6.67%   |
| Seagate ST3500418AS 500GB                        | 1        | 1      | 6.67%   |
| Seagate ST3250318AS 250GB                        | 1        | 1      | 6.67%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB      | 1        | 1      | 6.67%   |
| Samsung Electronics SSD 980 1TB                  | 1        | 2      | 6.67%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 1        | 2      | 6.67%   |
| Samsung Electronics HD753LJ 752GB                | 1        | 1      | 6.67%   |
| Samsung Electronics HD501LJ 500GB                | 1        | 1      | 6.67%   |
| Kingston SMS200S360G 64GB SSD                    | 1        | 1      | 6.67%   |
| Intel SSDSC2KW256G8 256GB                        | 1        | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 8      | 40%     |
| Samsung Electronics | 5        | 7      | 33.33%  |
| Seagate             | 2        | 2      | 13.33%  |
| Kingston            | 1        | 1      | 6.67%   |
| Intel               | 1        | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 2023     | 4838   | 45.72%  |
| Detected | 1779     | 5199   | 40.2%   |
| Malfunc  | 608      | 866    | 13.74%  |
| Failed   | 15       | 19     | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2528     | 48.45%  |
| AMD                              | 1051     | 20.14%  |
| Samsung Electronics              | 332      | 6.36%   |
| ASMedia Technology               | 168      | 3.22%   |
| Marvell Technology Group         | 160      | 3.07%   |
| Nvidia                           | 150      | 2.87%   |
| JMicron Technology               | 143      | 2.74%   |
| Micron/Crucial Technology        | 120      | 2.3%    |
| Phison Electronics               | 117      | 2.24%   |
| SanDisk                          | 108      | 2.07%   |
| VIA Technologies                 | 57       | 1.09%   |
| Kingston Technology Company      | 55       | 1.05%   |
| Silicon Motion                   | 24       | 0.46%   |
| Silicon Image                    | 22       | 0.42%   |
| LSI Logic / Symbios Logic        | 19       | 0.36%   |
| SK hynix                         | 17       | 0.33%   |
| Micron Technology                | 17       | 0.33%   |
| Broadcom / LSI                   | 17       | 0.33%   |
| Toshiba America Info Systems     | 16       | 0.31%   |
| Seagate Technology               | 13       | 0.25%   |
| ADATA Technology                 | 10       | 0.19%   |
| Adaptec                          | 9        | 0.17%   |
| Silicon Integrated Systems [SiS] | 8        | 0.15%   |
| Realtek Semiconductor            | 7        | 0.13%   |
| Integrated Technology Express    | 7        | 0.13%   |
| MAXIO Technology (Hangzhou)      | 6        | 0.11%   |
| KIOXIA                           | 6        | 0.11%   |
| Shenzhen Longsys Electronics     | 5        | 0.1%    |
| Hewlett-Packard                  | 5        | 0.1%    |
| Union Memory (Shenzhen)          | 3        | 0.06%   |
| Promise Technology               | 3        | 0.06%   |
| Solidigm                         | 2        | 0.04%   |
| Lite-On Technology               | 2        | 0.04%   |
| ULi Electronics                  | 1        | 0.02%   |
| Transcend                        | 1        | 0.02%   |
| Tekram Technology                | 1        | 0.02%   |
| Red Hat                          | 1        | 0.02%   |
| OCZ Technology Group             | 1        | 0.02%   |
| Netac Technology                 | 1        | 0.02%   |
| INNOGRIT                         | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 595      | 9.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 320      | 4.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 231      | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 209      | 3.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 203      | 3.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 193      | 2.94%   |
| Intel SATA Controller [RAID mode]                                                       | 185      | 2.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 167      | 2.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 166      | 2.53%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 150      | 2.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 144      | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 140      | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 135      | 2.06%   |
| AMD 500 Series Chipset SATA Controller                                                  | 135      | 2.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 127      | 1.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 125      | 1.9%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 110      | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 94       | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 88       | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 88       | 1.34%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 79       | 1.2%    |
| Nvidia MCP61 SATA Controller                                                            | 76       | 1.16%   |
| AMD FCH SATA Controller D                                                               | 68       | 1.04%   |
| Phison E12 NVMe Controller                                                              | 65       | 0.99%   |
| Nvidia MCP61 IDE                                                                        | 65       | 0.99%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 63       | 0.96%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 61       | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 60       | 0.91%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 58       | 0.88%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 51       | 0.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 51       | 0.78%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 50       | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 47       | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 45       | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 42       | 0.64%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 42       | 0.64%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 40       | 0.61%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 40       | 0.61%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 39       | 0.59%   |
| AMD 300 Series Chipset SATA Controller                                                  | 37       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2886     | 56.98%  |
| IDE  | 1024     | 20.22%  |
| NVMe | 788      | 15.56%  |
| RAID | 319      | 6.3%    |
| SAS  | 26       | 0.51%   |
| SCSI | 22       | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2589     | 68.53%  |
| AMD                   | 1185     | 31.37%  |
| CentaurHauls          | 2        | 0.05%   |
| Marvell Semiconductor | 1        | 0.03%   |
| ARM                   | 1        | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 65       | 1.71%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 53       | 1.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 49       | 1.29%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 41       | 1.08%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 40       | 1.05%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 38       | 1%      |
| Intel Core i7-4790K CPU @ 4.00GHz           | 37       | 0.97%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 37       | 0.97%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 37       | 0.97%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 37       | 0.97%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 36       | 0.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 34       | 0.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 33       | 0.87%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 33       | 0.87%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 31       | 0.82%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 30       | 0.79%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 28       | 0.74%   |
| AMD FX-8350 Eight-Core Processor            | 28       | 0.74%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 26       | 0.68%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 26       | 0.68%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 26       | 0.68%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 25       | 0.66%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 25       | 0.66%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 25       | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 23       | 0.61%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 23       | 0.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 23       | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 23       | 0.61%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 22       | 0.58%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 22       | 0.58%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 22       | 0.58%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 22       | 0.58%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 22       | 0.58%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 22       | 0.58%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 22       | 0.58%   |
| AMD FX-6300 Six-Core Processor              | 22       | 0.58%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 21       | 0.55%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 21       | 0.55%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 21       | 0.55%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 21       | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 769      | 20.28%  |
| Intel Core i7           | 512      | 13.5%   |
| AMD Ryzen 5             | 293      | 7.73%   |
| Intel Core i3           | 281      | 7.41%   |
| Intel Xeon              | 194      | 5.12%   |
| AMD Ryzen 7             | 189      | 4.98%   |
| Intel Core 2 Duo        | 132      | 3.48%   |
| Intel Celeron           | 107      | 2.82%   |
| Intel Pentium           | 106      | 2.8%    |
| Intel Core 2 Quad       | 104      | 2.74%   |
| Other                   | 100      | 2.64%   |
| AMD FX                  | 100      | 2.64%   |
| AMD Ryzen 9             | 80       | 2.11%   |
| Intel Pentium Dual-Core | 70       | 1.85%   |
| AMD Athlon II X2        | 65       | 1.71%   |
| AMD Ryzen 3             | 64       | 1.69%   |
| AMD Athlon 64 X2        | 53       | 1.4%    |
| Intel Atom              | 52       | 1.37%   |
| AMD Phenom II X4        | 42       | 1.11%   |
| Intel Pentium Dual      | 34       | 0.9%    |
| AMD A8                  | 33       | 0.87%   |
| Intel Core 2            | 32       | 0.84%   |
| Intel Pentium 4         | 31       | 0.82%   |
| Intel Core i9           | 31       | 0.82%   |
| AMD A4                  | 29       | 0.76%   |
| AMD A6                  | 22       | 0.58%   |
| Intel Pentium D         | 21       | 0.55%   |
| Intel Pentium Gold      | 19       | 0.5%    |
| AMD Athlon 64           | 19       | 0.5%    |
| AMD A10                 | 18       | 0.47%   |
| AMD Ryzen Threadripper  | 17       | 0.45%   |
| AMD Athlon II X4        | 16       | 0.42%   |
| AMD Sempron             | 15       | 0.4%    |
| AMD Phenom II X6        | 15       | 0.4%    |
| AMD Ryzen 5 PRO         | 13       | 0.34%   |
| AMD Athlon              | 13       | 0.34%   |
| AMD E                   | 10       | 0.26%   |
| AMD Athlon X4           | 9        | 0.24%   |
| AMD Athlon Dual Core    | 9        | 0.24%   |
| AMD Athlon II X3        | 8        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1563     | 41.11%  |
| 2       | 1020     | 26.83%  |
| 6       | 532      | 13.99%  |
| 8       | 302      | 7.94%   |
| 1       | 132      | 3.47%   |
| 12      | 94       | 2.47%   |
| 3       | 51       | 1.34%   |
| 16      | 42       | 1.1%    |
| Unknown | 21       | 0.55%   |
| 10      | 19       | 0.5%    |
| 14      | 7        | 0.18%   |
| 32      | 6        | 0.16%   |
| 24      | 5        | 0.13%   |
| 20      | 4        | 0.11%   |
| 64      | 3        | 0.08%   |
| 40      | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3724     | 98.54%  |
| 2      | 53       | 1.4%    |
| 4      | 1        | 0.03%   |
| 0      | 1        | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1932     | 50.86%  |
| 1       | 1845     | 48.57%  |
| Unknown | 21       | 0.55%   |
| 4       | 1        | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3731     | 98.55%  |
| Unknown        | 29       | 0.77%   |
| 32-bit         | 26       | 0.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 899      | 22.77%  |
| 0x306c3    | 381      | 9.65%   |
| 0x206a7    | 228      | 5.78%   |
| 0x306a9    | 215      | 5.45%   |
| 0x1067a    | 187      | 4.74%   |
| 0x506e3    | 151      | 3.82%   |
| 0x906ea    | 107      | 2.71%   |
| 0x08701021 | 103      | 2.61%   |
| 0x010000c8 | 89       | 2.25%   |
| 0x906e9    | 84       | 2.13%   |
| 0x0800820d | 82       | 2.08%   |
| 0x06000852 | 55       | 1.39%   |
| 0x06001119 | 52       | 1.32%   |
| 0x08701013 | 51       | 1.29%   |
| 0x106e5    | 47       | 1.19%   |
| 0x6fd      | 46       | 1.17%   |
| 0x08108109 | 44       | 1.11%   |
| 0x10676    | 37       | 0.94%   |
| 0xa0653    | 35       | 0.89%   |
| 0x0a201016 | 35       | 0.89%   |
| 0x6fb      | 34       | 0.86%   |
| 0x906ed    | 33       | 0.84%   |
| 0xa0671    | 29       | 0.73%   |
| 0xa0655    | 29       | 0.73%   |
| 0x106a5    | 28       | 0.71%   |
| 0x306f2    | 26       | 0.66%   |
| 0x08001138 | 26       | 0.66%   |
| 0x206d7    | 23       | 0.58%   |
| 0x08001137 | 21       | 0.53%   |
| 0x10677    | 20       | 0.51%   |
| 0x906ec    | 18       | 0.46%   |
| 0x6f6      | 18       | 0.46%   |
| 0x20655    | 18       | 0.46%   |
| 0x0a20120a | 18       | 0.46%   |
| 0x08101016 | 18       | 0.46%   |
| 0x0a50000d | 17       | 0.43%   |
| 0x0a201009 | 17       | 0.43%   |
| 0x906eb    | 16       | 0.41%   |
| 0x90672    | 16       | 0.41%   |
| 0x08600106 | 16       | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 513      | 13.54%  |
| KabyLake         | 340      | 8.97%   |
| SandyBridge      | 304      | 8.02%   |
| Penryn           | 278      | 7.34%   |
| IvyBridge        | 267      | 7.04%   |
| Zen 2            | 239      | 6.31%   |
| Skylake          | 223      | 5.88%   |
| K10              | 175      | 4.62%   |
| Zen+             | 166      | 4.38%   |
| Piledriver       | 145      | 3.83%   |
| Zen 3            | 134      | 3.54%   |
| Core             | 130      | 3.43%   |
| Zen              | 110      | 2.9%    |
| Nehalem          | 96       | 2.53%   |
| K8 Hammer        | 96       | 2.53%   |
| CometLake        | 92       | 2.43%   |
| Unknown          | 63       | 1.66%   |
| NetBurst         | 58       | 1.53%   |
| Westmere         | 57       | 1.5%    |
| Silvermont       | 35       | 0.92%   |
| Bonnell          | 35       | 0.92%   |
| Broadwell        | 31       | 0.82%   |
| Alderlake Hybrid | 31       | 0.82%   |
| Icelake          | 29       | 0.77%   |
| Excavator        | 23       | 0.61%   |
| Goldmont plus    | 19       | 0.5%    |
| Steamroller      | 18       | 0.47%   |
| Bobcat           | 15       | 0.4%    |
| K10 Llano        | 14       | 0.37%   |
| Bulldozer        | 14       | 0.37%   |
| Goldmont         | 11       | 0.29%   |
| Puma             | 9        | 0.24%   |
| Tremont          | 7        | 0.18%   |
| Jaguar           | 6        | 0.16%   |
| K6               | 4        | 0.11%   |
| Gracemont        | 2        | 0.05%   |
| TigerLake        | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1780     | 43.91%  |
| Intel                                        | 1129     | 27.85%  |
| AMD                                          | 1096     | 27.04%  |
| ASPEED Technology                            | 17       | 0.42%   |
| Matrox Electronics Systems                   | 16       | 0.39%   |
| VIA Technologies                             | 6        | 0.15%   |
| Silicon Integrated Systems [SiS]             | 5        | 0.12%   |
| ATI Technologies                             | 2        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.02%   |
| S3 Graphics                                  | 1        | 0.02%   |
| Red Hat                                      | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 214      | 5.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 126      | 3.01%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 108      | 2.58%   |
| Nvidia GK208B [GeForce GT 710]                                              | 104      | 2.49%   |
| Intel HD Graphics 530                                                       | 93       | 2.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 91       | 2.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 88       | 2.1%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 81       | 1.94%   |
| Nvidia GT218 [GeForce 210]                                                  | 73       | 1.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 70       | 1.67%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 58       | 1.39%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 58       | 1.39%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 54       | 1.29%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 52       | 1.24%   |
| Nvidia GK208B [GeForce GT 730]                                              | 51       | 1.22%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 48       | 1.15%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 47       | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 46       | 1.1%    |
| Nvidia GF119 [GeForce GT 610]                                               | 44       | 1.05%   |
| Intel HD Graphics 630                                                       | 44       | 1.05%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 43       | 1.03%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 34       | 0.81%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 34       | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 33       | 0.79%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 32       | 0.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 32       | 0.76%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 28       | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 28       | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 28       | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 27       | 0.65%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 27       | 0.65%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 27       | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 26       | 0.62%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 26       | 0.62%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 26       | 0.62%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 26       | 0.62%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 25       | 0.6%    |
| Nvidia GK106 [GeForce GTX 660]                                              | 23       | 0.55%   |
| AMD RS780L [Radeon 3000]                                                    | 23       | 0.55%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 22       | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1657     | 43.05%  |
| 1 x AMD              | 968      | 25.15%  |
| 1 x Intel            | 928      | 24.11%  |
| Intel + Nvidia       | 75       | 1.95%   |
| 2 x AMD              | 59       | 1.53%   |
| AMD + Nvidia         | 38       | 0.99%   |
| Intel + AMD          | 31       | 0.81%   |
| 2 x Nvidia           | 23       | 0.6%    |
| 1 x Matrox           | 14       | 0.36%   |
| 1 x ASPEED           | 14       | 0.36%   |
| 2 x Intel            | 11       | 0.29%   |
| Other                | 7        | 0.18%   |
| 1 x VIA              | 6        | 0.16%   |
| 1 x SiS              | 5        | 0.13%   |
| 3 x AMD              | 2        | 0.05%   |
| 3 x Nvidia           | 1        | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.03%   |
| 2 x AMD + 1 x ASPEED | 1        | 0.03%   |
| 1 x XGI              | 1        | 0.03%   |
| 1 x S3 Graphics      | 1        | 0.03%   |
| 1 x Red Hat          | 1        | 0.03%   |
| Nvidia + Matrox      | 1        | 0.03%   |
| Nvidia + ASPEED      | 1        | 0.03%   |
| Intel + 2 x Nvidia   | 1        | 0.03%   |
| Intel + 2 x AMD      | 1        | 0.03%   |
| AMD + ASPEED         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2749     | 70.96%  |
| Proprietary | 916      | 23.64%  |
| Unknown     | 209      | 5.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1488     | 37.88%  |
| 1.01-2.0   | 581      | 14.79%  |
| 0.01-0.5   | 505      | 12.86%  |
| 0.51-1.0   | 501      | 12.75%  |
| 3.01-4.0   | 294      | 7.48%   |
| 7.01-8.0   | 262      | 6.67%   |
| 5.01-6.0   | 127      | 3.23%   |
| 8.01-16.0  | 103      | 2.62%   |
| 2.01-3.0   | 47       | 1.2%    |
| 16.01-24.0 | 14       | 0.36%   |
| 4.01-5.0   | 6        | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 635      | 15.58%  |
| Iiyama               | 412      | 10.11%  |
| Dell                 | 348      | 8.54%   |
| Hewlett-Packard      | 321      | 7.88%   |
| Acer                 | 277      | 6.8%    |
| Goldstar             | 273      | 6.7%    |
| Ancor Communications | 239      | 5.86%   |
| Philips              | 225      | 5.52%   |
| AOC                  | 183      | 4.49%   |
| BenQ                 | 158      | 3.88%   |
| ViewSonic            | 94       | 2.31%   |
| ASUSTek Computer     | 68       | 1.67%   |
| Lenovo               | 58       | 1.42%   |
| Unknown              | 47       | 1.15%   |
| HannStar             | 37       | 0.91%   |
| Sony                 | 36       | 0.88%   |
| Idek Iiyama          | 36       | 0.88%   |
| LG Electronics       | 33       | 0.81%   |
| Packard Bell         | 32       | 0.79%   |
| NEC Computers        | 26       | 0.64%   |
| Eizo                 | 26       | 0.64%   |
| Vestel Elektronik    | 22       | 0.54%   |
| HKC                  | 20       | 0.49%   |
| Hitachi              | 20       | 0.49%   |
| Fujitsu Siemens      | 20       | 0.49%   |
| Denver               | 20       | 0.49%   |
| Medion               | 19       | 0.47%   |
| MSI                  | 18       | 0.44%   |
| SNC                  | 17       | 0.42%   |
| Hyundai ImageQuest   | 16       | 0.39%   |
| Toshiba              | 12       | 0.29%   |
| NECCI                | 11       | 0.27%   |
| Gigabyte Technology  | 11       | 0.27%   |
| Belinea              | 11       | 0.27%   |
| Unknown              | 11       | 0.27%   |
| RTK                  | 10       | 0.25%   |
| RS                   | 10       | 0.25%   |
| Panasonic            | 9        | 0.22%   |
| Plain Tree Systems   | 8        | 0.2%    |
| MiTAC                | 7        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 37       | 0.85%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 22       | 0.5%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 22       | 0.5%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 19       | 0.44%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 530x300mm 24.0-inch     | 17       | 0.39%   |
| Iiyama PL2283H IVM562E 1920x1080 480x270mm 21.7-inch                  | 16       | 0.37%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 15       | 0.34%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 15       | 0.34%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 15       | 0.34%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                 | 13       | 0.3%    |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 13       | 0.3%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 13       | 0.3%    |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                      | 12       | 0.28%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 12       | 0.28%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 12       | 0.28%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 11       | 0.25%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 11       | 0.25%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 11       | 0.25%   |
| AOC 2200W AOC2200 1920x1080 476x268mm 21.5-inch                       | 11       | 0.25%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch      | 11       | 0.25%   |
| Unknown                                                               | 11       | 0.25%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 10       | 0.23%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 10       | 0.23%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 10       | 0.23%   |
| Iiyama PL2530H IVM6133 1920x1080 540x300mm 24.3-inch                  | 10       | 0.23%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                  | 10       | 0.23%   |
| Hewlett-Packard v220 HWP26FE 1680x1050 473x296mm 22.0-inch            | 10       | 0.23%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 10       | 0.23%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 10       | 0.23%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 9        | 0.21%   |
| Iiyama X2483/2481 IVM6128 1920x1080 527x296mm 23.8-inch               | 9        | 0.21%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                 | 9        | 0.21%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                | 9        | 0.21%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                 | 9        | 0.21%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                  | 9        | 0.21%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 9        | 0.21%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 9        | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 8        | 0.18%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 8        | 0.18%   |
| Iiyama PLE2403WS IVM5604 1920x1200 519x324mm 24.1-inch                | 8        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1911     | 48.12%  |
| 1280x1024 (SXGA)   | 328      | 8.26%   |
| 1680x1050 (WSXGA+) | 322      | 8.11%   |
| 2560x1440 (QHD)    | 272      | 6.85%   |
| 3840x2160 (4K)     | 247      | 6.22%   |
| 1440x900 (WXGA+)   | 156      | 3.93%   |
| 1920x1200 (WUXGA)  | 140      | 3.53%   |
| Unknown            | 104      | 2.62%   |
| 1600x900 (HD+)     | 87       | 2.19%   |
| 1366x768 (WXGA)    | 57       | 1.44%   |
| 1360x768           | 50       | 1.26%   |
| 3840x1080          | 48       | 1.21%   |
| 3440x1440          | 44       | 1.11%   |
| 2560x1080          | 36       | 0.91%   |
| 1600x1200          | 27       | 0.68%   |
| 1024x768 (XGA)     | 19       | 0.48%   |
| 2288x1287          | 12       | 0.3%    |
| 1920x540           | 10       | 0.25%   |
| 4480x1440          | 7        | 0.18%   |
| 3200x1080          | 7        | 0.18%   |
| 3840x1600          | 6        | 0.15%   |
| 3600x1080          | 6        | 0.15%   |
| 2560x1600          | 6        | 0.15%   |
| 5760x1080          | 5        | 0.13%   |
| 1280x960           | 4        | 0.1%    |
| 5760x2160          | 3        | 0.08%   |
| 5760x1200          | 3        | 0.08%   |
| 2560x1024          | 3        | 0.08%   |
| 2048x1152          | 3        | 0.08%   |
| 1280x768           | 3        | 0.08%   |
| 1280x720 (HD)      | 3        | 0.08%   |
| 7680x2160          | 2        | 0.05%   |
| 3360x1050          | 2        | 0.05%   |
| 3280x1080          | 2        | 0.05%   |
| 3200x1200          | 2        | 0.05%   |
| 3120x1050          | 2        | 0.05%   |
| 2960x1050          | 2        | 0.05%   |
| 720x480            | 1        | 0.03%   |
| 6720x2160          | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 608      | 14.99%  |
| 24      | 592      | 14.6%   |
| 27      | 555      | 13.68%  |
| 21      | 472      | 11.64%  |
| Unknown | 378      | 9.32%   |
| 19      | 297      | 7.32%   |
| 22      | 211      | 5.2%    |
| 17      | 170      | 4.19%   |
| 20      | 136      | 3.35%   |
| 31      | 101      | 2.49%   |
| 18      | 99       | 2.44%   |
| 34      | 63       | 1.55%   |
| 84      | 47       | 1.16%   |
| 25      | 33       | 0.81%   |
| 40      | 32       | 0.79%   |
| 32      | 31       | 0.76%   |
| 15      | 29       | 0.71%   |
| 72      | 28       | 0.69%   |
| 54      | 19       | 0.47%   |
| 33      | 18       | 0.44%   |
| 48      | 11       | 0.27%   |
| 46      | 11       | 0.27%   |
| 142     | 10       | 0.25%   |
| 65      | 10       | 0.25%   |
| 29      | 10       | 0.25%   |
| 12      | 8        | 0.2%    |
| 52      | 7        | 0.17%   |
| 42      | 7        | 0.17%   |
| 35      | 6        | 0.15%   |
| 26      | 6        | 0.15%   |
| 39      | 5        | 0.12%   |
| 38      | 5        | 0.12%   |
| 36      | 5        | 0.12%   |
| 16      | 5        | 0.12%   |
| 49      | 4        | 0.1%    |
| 37      | 4        | 0.1%    |
| 28      | 4        | 0.1%    |
| 14      | 4        | 0.1%    |
| 58      | 2        | 0.05%   |
| 55      | 2        | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1592     | 40.79%  |
| 401-500        | 1029     | 26.36%  |
| Unknown        | 378      | 9.68%   |
| 301-350        | 194      | 4.97%   |
| 351-400        | 185      | 4.74%   |
| 601-700        | 177      | 4.53%   |
| 701-800        | 118      | 3.02%   |
| 1501-2000      | 76       | 1.95%   |
| 1001-1500      | 72       | 1.84%   |
| 801-900        | 52       | 1.33%   |
| 201-300        | 12       | 0.31%   |
| More than 2000 | 10       | 0.26%   |
| 901-1000       | 8        | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2309     | 61.44%  |
| 16/10   | 585      | 15.57%  |
| Unknown | 329      | 8.75%   |
| 5/4     | 304      | 8.09%   |
| 21/9    | 79       | 2.1%    |
| 4/3     | 65       | 1.73%   |
| 3/2     | 37       | 0.98%   |
| 6/5     | 20       | 0.53%   |
| 32/9    | 13       | 0.35%   |
| 1.00    | 10       | 0.27%   |
| 11/10   | 2        | 0.05%   |
| 0.56    | 2        | 0.05%   |
| 2.00    | 1        | 0.03%   |
| 1.03    | 1        | 0.03%   |
| 0.75    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1505     | 38.2%   |
| 151-200        | 580      | 14.72%  |
| 301-350        | 564      | 14.31%  |
| Unknown        | 378      | 9.59%   |
| 351-500        | 221      | 5.61%   |
| 251-300        | 214      | 5.43%   |
| 141-150        | 208      | 5.28%   |
| More than 1000 | 133      | 3.38%   |
| 501-1000       | 86       | 2.18%   |
| 101-110        | 25       | 0.63%   |
| 71-80          | 9        | 0.23%   |
| 131-140        | 6        | 0.15%   |
| 121-130        | 4        | 0.1%    |
| 111-120        | 4        | 0.1%    |
| 81-90          | 3        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2452     | 65.16%  |
| 101-120 | 669      | 17.78%  |
| Unknown | 378      | 10.05%  |
| 121-160 | 126      | 3.35%   |
| 1-50    | 103      | 2.74%   |
| 161-240 | 35       | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2886     | 74.67%  |
| 2     | 659      | 17.05%  |
| 0     | 247      | 6.39%   |
| 3     | 68       | 1.76%   |
| 4     | 5        | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 2276     | 43.43%  |
| Intel                            | 1470     | 28.05%  |
| Qualcomm Atheros                 | 365      | 6.96%   |
| Broadcom                         | 168      | 3.21%   |
| Nvidia                           | 113      | 2.16%   |
| TP-Link                          | 83       | 1.58%   |
| Marvell Technology Group         | 75       | 1.43%   |
| Ralink                           | 67       | 1.28%   |
| NetGear                          | 64       | 1.22%   |
| Ralink Technology                | 62       | 1.18%   |
| MediaTek                         | 40       | 0.76%   |
| Broadcom Limited                 | 40       | 0.76%   |
| D-Link System                    | 38       | 0.73%   |
| Samsung Electronics              | 26       | 0.5%    |
| Aquantia                         | 26       | 0.5%    |
| Microsoft                        | 23       | 0.44%   |
| D-Link                           | 23       | 0.44%   |
| VIA Technologies                 | 22       | 0.42%   |
| Belkin Components                | 22       | 0.42%   |
| Qualcomm Atheros Communications  | 17       | 0.32%   |
| ASIX Electronics                 | 16       | 0.31%   |
| Xiaomi                           | 13       | 0.25%   |
| Guillemot                        | 13       | 0.25%   |
| ASUSTek Computer                 | 11       | 0.21%   |
| Google                           | 10       | 0.19%   |
| Huawei Technologies              | 9        | 0.17%   |
| Edimax Technology                | 8        | 0.15%   |
| Qualcomm                         | 6        | 0.11%   |
| TRENDnet                         | 5        | 0.1%    |
| OPPO Electronics                 | 5        | 0.1%    |
| IMC Networks                     | 5        | 0.1%    |
| 3Com                             | 5        | 0.1%    |
| Silicon Integrated Systems [SiS] | 4        | 0.08%   |
| Sagem                            | 4        | 0.08%   |
| OnePlus Technology (Shenzhen)    | 4        | 0.08%   |
| Motorola PCS                     | 4        | 0.08%   |
| JMicron Technology               | 4        | 0.08%   |
| Gemtek                           | 4        | 0.08%   |
| Tenda                            | 3        | 0.06%   |
| STMicroelectronics               | 3        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1831     | 31.19%  |
| Realtek RTL8125 2.5GbE Controller                                 | 169      | 2.88%   |
| Intel I211 Gigabit Network Connection                             | 146      | 2.49%   |
| Intel Wi-Fi 6 AX200                                               | 144      | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 144      | 2.45%   |
| Intel Ethernet Connection (2) I219-V                              | 139      | 2.37%   |
| Intel Ethernet Connection I217-LM                                 | 96       | 1.64%   |
| Intel 82579V Gigabit Network Connection                           | 83       | 1.41%   |
| Intel Ethernet Connection (7) I219-V                              | 72       | 1.23%   |
| Intel Ethernet Controller I225-V                                  | 64       | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 63       | 1.07%   |
| Intel Ethernet Connection (2) I219-LM                             | 59       | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 57       | 0.97%   |
| Nvidia MCP61 Ethernet                                             | 57       | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 56       | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 52       | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 51       | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 44       | 0.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 44       | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 44       | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 41       | 0.7%    |
| Intel Wireless-AC 9260                                            | 41       | 0.7%    |
| Intel 82574L Gigabit Network Connection                           | 41       | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 33       | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 32       | 0.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 31       | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 31       | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 31       | 0.53%   |
| Intel I210 Gigabit Network Connection                             | 31       | 0.53%   |
| Realtek 802.11ac NIC                                              | 29       | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 29       | 0.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 29       | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 28       | 0.48%   |
| Intel Wireless 3165                                               | 27       | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 27       | 0.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27       | 0.46%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 26       | 0.44%   |
| Intel Wireless 7260                                               | 26       | 0.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25       | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 25       | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 434      | 27.38%  |
| Realtek Semiconductor                 | 414      | 26.12%  |
| Qualcomm Atheros                      | 190      | 11.99%  |
| TP-Link                               | 82       | 5.17%   |
| Ralink                                | 67       | 4.23%   |
| NetGear                               | 63       | 3.97%   |
| Ralink Technology                     | 62       | 3.91%   |
| Broadcom                              | 53       | 3.34%   |
| MediaTek                              | 33       | 2.08%   |
| Microsoft                             | 23       | 1.45%   |
| D-Link                                | 23       | 1.45%   |
| Belkin Components                     | 22       | 1.39%   |
| D-Link System                         | 18       | 1.14%   |
| Qualcomm Atheros Communications       | 17       | 1.07%   |
| Guillemot                             | 13       | 0.82%   |
| Broadcom Limited                      | 11       | 0.69%   |
| ASUSTek Computer                      | 11       | 0.69%   |
| Edimax Technology                     | 8        | 0.5%    |
| TRENDnet                              | 5        | 0.32%   |
| IMC Networks                          | 5        | 0.32%   |
| Sagem                                 | 4        | 0.25%   |
| Gemtek                                | 4        | 0.25%   |
| Tenda                                 | 3        | 0.19%   |
| Marvell Technology Group              | 3        | 0.19%   |
| ZyDAS                                 | 2        | 0.13%   |
| Toshiba                               | 2        | 0.13%   |
| Linksys                               | 2        | 0.13%   |
| Fujitsu Siemens Computers             | 2        | 0.13%   |
| Accton Technology                     | 2        | 0.13%   |
| Z-Com                                 | 1        | 0.06%   |
| Yoctopuce Sarl                        | 1        | 0.06%   |
| Wilocity                              | 1        | 0.06%   |
| Wacom                                 | 1        | 0.06%   |
| Micro Star International              | 1        | 0.06%   |
| BUFFALO                               | 1        | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 144      | 9.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 44       | 2.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 41       | 2.56%   |
| Intel Wireless-AC 9260                                         | 41       | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 33       | 2.06%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 31       | 1.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 31       | 1.94%   |
| Realtek 802.11ac NIC                                           | 29       | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 29       | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 29       | 1.81%   |
| Intel Wireless 3165                                            | 27       | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27       | 1.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 26       | 1.63%   |
| Intel Wireless 7260                                            | 26       | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25       | 1.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 25       | 1.56%   |
| Ralink MT7601U Wireless Adapter                                | 25       | 1.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 23       | 1.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 21       | 1.31%   |
| Intel Wireless 7265                                            | 21       | 1.31%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 20       | 1.25%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 20       | 1.25%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 19       | 1.19%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 18       | 1.13%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 18       | 1.13%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 17       | 1.06%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 16       | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 16       | 1%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 16       | 1%      |
| Intel Wireless 8260                                            | 15       | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 14       | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                | 14       | 0.88%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]        | 14       | 0.88%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 14       | 0.88%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 13       | 0.81%   |
| NetGear A6210                                                  | 13       | 0.81%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 12       | 0.75%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 12       | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 12       | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12       | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2124     | 52.12%  |
| Intel                             | 1222     | 29.99%  |
| Qualcomm Atheros                  | 192      | 4.71%   |
| Broadcom                          | 115      | 2.82%   |
| Nvidia                            | 113      | 2.77%   |
| Marvell Technology Group          | 72       | 1.77%   |
| Broadcom Limited                  | 29       | 0.71%   |
| Samsung Electronics               | 26       | 0.64%   |
| Aquantia                          | 26       | 0.64%   |
| VIA Technologies                  | 20       | 0.49%   |
| D-Link System                     | 20       | 0.49%   |
| ASIX Electronics                  | 16       | 0.39%   |
| Xiaomi                            | 13       | 0.32%   |
| Google                            | 10       | 0.25%   |
| Huawei Technologies               | 9        | 0.22%   |
| Qualcomm                          | 6        | 0.15%   |
| MediaTek                          | 6        | 0.15%   |
| OPPO Electronics                  | 5        | 0.12%   |
| 3Com                              | 5        | 0.12%   |
| OnePlus Technology (Shenzhen)     | 4        | 0.1%    |
| Motorola PCS                      | 4        | 0.1%    |
| JMicron Technology                | 4        | 0.1%    |
| Silicon Integrated Systems [SiS]  | 3        | 0.07%   |
| QLogic                            | 3        | 0.07%   |
| Mellanox Technologies             | 3        | 0.07%   |
| ICS Advent                        | 3        | 0.07%   |
| HTC (High Tech Computer)          | 3        | 0.07%   |
| DisplayLink                       | 2        | 0.05%   |
| Xilinx                            | 1        | 0.02%   |
| TP-Link                           | 1        | 0.02%   |
| Tehuti Networks                   | 1        | 0.02%   |
| Sundance Technology Inc / IC Plus | 1        | 0.02%   |
| Spreadtrum Communications         | 1        | 0.02%   |
| NetGear                           | 1        | 0.02%   |
| Netchip Technology                | 1        | 0.02%   |
| National Semiconductor            | 1        | 0.02%   |
| MYRICOM                           | 1        | 0.02%   |
| Linksys                           | 1        | 0.02%   |
| Lenovo                            | 1        | 0.02%   |
| Intellon                          | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1831     | 43.35%  |
| Realtek RTL8125 2.5GbE Controller                                 | 169      | 4%      |
| Intel I211 Gigabit Network Connection                             | 146      | 3.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 144      | 3.41%   |
| Intel Ethernet Connection (2) I219-V                              | 139      | 3.29%   |
| Intel Ethernet Connection I217-LM                                 | 96       | 2.27%   |
| Intel 82579V Gigabit Network Connection                           | 83       | 1.96%   |
| Intel Ethernet Connection (7) I219-V                              | 72       | 1.7%    |
| Intel Ethernet Controller I225-V                                  | 64       | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 63       | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 59       | 1.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 57       | 1.35%   |
| Nvidia MCP61 Ethernet                                             | 57       | 1.35%   |
| Intel Ethernet Connection (2) I218-V                              | 56       | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 52       | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 51       | 1.21%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 44       | 1.04%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 44       | 1.04%   |
| Intel 82574L Gigabit Network Connection                           | 41       | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 32       | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 31       | 0.73%   |
| Intel I210 Gigabit Network Connection                             | 31       | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 28       | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 27       | 0.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23       | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 22       | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19       | 0.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 18       | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                             | 18       | 0.43%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 17       | 0.4%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 16       | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 14       | 0.33%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 14       | 0.33%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 14       | 0.33%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 13       | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13       | 0.31%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 13       | 0.31%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 13       | 0.31%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13       | 0.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 12       | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3752     | 70.95%  |
| WiFi     | 1490     | 28.18%  |
| Modem    | 36       | 0.68%   |
| Unknown  | 10       | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3149     | 79.84%  |
| WiFi     | 795      | 20.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2504     | 65.62%  |
| 2     | 1133     | 29.69%  |
| 3     | 121      | 3.17%   |
| 0     | 26       | 0.68%   |
| 4     | 18       | 0.47%   |
| 5     | 7        | 0.18%   |
| 7     | 3        | 0.08%   |
| 6     | 2        | 0.05%   |
| 9     | 1        | 0.03%   |
| 8     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2311     | 59.23%  |
| Yes  | 1591     | 40.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 387      | 36.79%  |
| Cambridge Silicon Radio         | 285      | 27.09%  |
| ASUSTek Computer                | 82       | 7.79%   |
| Realtek Semiconductor           | 77       | 7.32%   |
| IMC Networks                    | 42       | 3.99%   |
| Broadcom                        | 41       | 3.9%    |
| Qualcomm Atheros Communications | 27       | 2.57%   |
| Belkin Components               | 20       | 1.9%    |
| TP-Link                         | 19       | 1.81%   |
| MediaTek                        | 17       | 1.62%   |
| Apple                           | 12       | 1.14%   |
| Lite-On Technology              | 8        | 0.76%   |
| Foxconn / Hon Hai               | 7        | 0.67%   |
| Integrated System Solution      | 5        | 0.48%   |
| Realtek                         | 4        | 0.38%   |
| HTC (High Tech Computer)        | 3        | 0.29%   |
| Kensington                      | 2        | 0.19%   |
| TRENDnet                        | 1        | 0.1%    |
| Toshiba                         | 1        | 0.1%    |
| Roper                           | 1        | 0.1%    |
| Micro Star International        | 1        | 0.1%    |
| Marvell Semiconductor           | 1        | 0.1%    |
| Logitech                        | 1        | 0.1%    |
| Fujitsu                         | 1        | 0.1%    |
| Edimax Technology               | 1        | 0.1%    |
| Dell                            | 1        | 0.1%    |
| D-Link System                   | 1        | 0.1%    |
| D-Link                          | 1        | 0.1%    |
| Creative Technology             | 1        | 0.1%    |
| Conwise Technology              | 1        | 0.1%    |
| Com One                         | 1        | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 285      | 27.09%  |
| Intel AX200 Bluetooth                                                | 129      | 12.26%  |
| Intel Bluetooth wireless interface                                   | 90       | 8.56%   |
| Realtek Bluetooth Radio                                              | 63       | 5.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 40       | 3.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 33       | 3.14%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 31       | 2.95%   |
| Intel AX210 Bluetooth                                                | 26       | 2.47%   |
| IMC Networks Bluetooth Radio                                         | 26       | 2.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 25       | 2.38%   |
| Intel AX201 Bluetooth                                                | 23       | 2.19%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 23       | 2.19%   |
| TP-Link UB500 Adapter                                                | 19       | 1.81%   |
| MediaTek Wireless_Device                                             | 17       | 1.62%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 14       | 1.33%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 13       | 1.24%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 13       | 1.24%   |
| ASUS Bluetooth Radio                                                 | 11       | 1.05%   |
| ASUS Bluetooth Adapter                                               | 11       | 1.05%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 10       | 0.95%   |
| ASUS ASUS USB-BT500                                                  | 10       | 0.95%   |
| Intel Bluetooth Device                                               | 9        | 0.86%   |
| ASUS BCM20702A0                                                      | 8        | 0.76%   |
| Belkin Components Bluetooth Mini Dongle                              | 7        | 0.67%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 6        | 0.57%   |
| IMC Networks Bluetooth Device                                        | 6        | 0.57%   |
| Realtek Bluetooth Radio                                              | 4        | 0.38%   |
| Qualcomm Atheros  Bluetooth Device                                   | 4        | 0.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 4        | 0.38%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 4        | 0.38%   |
| IMC Networks Wireless_Device                                         | 4        | 0.38%   |
| IMC Networks BCM20702A0                                              | 4        | 0.38%   |
| Foxconn / Hon Hai Wireless_Device                                    | 4        | 0.38%   |
| Broadcom BCM2045 Bluetooth                                           | 4        | 0.38%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 4        | 0.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3        | 0.29%   |
| Integrated System Solution Bluetooth Device                          | 3        | 0.29%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3        | 0.29%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 3        | 0.29%   |
| Apple Bluetooth Host Controller                                      | 3        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2419     | 37.32%  |
| Nvidia                           | 1659     | 25.6%   |
| AMD                              | 1462     | 22.56%  |
| C-Media Electronics              | 158      | 2.44%   |
| Logitech                         | 91       | 1.4%    |
| Creative Labs                    | 88       | 1.36%   |
| Texas Instruments                | 38       | 0.59%   |
| VIA Technologies                 | 37       | 0.57%   |
| Kingston Technology              | 35       | 0.54%   |
| Corsair                          | 31       | 0.48%   |
| GN Netcom                        | 29       | 0.45%   |
| Focusrite-Novation               | 28       | 0.43%   |
| JMTek                            | 22       | 0.34%   |
| Razer USA                        | 21       | 0.32%   |
| Generalplus Technology           | 21       | 0.32%   |
| SteelSeries ApS                  | 20       | 0.31%   |
| ASUSTek Computer                 | 18       | 0.28%   |
| Sennheiser Communications        | 17       | 0.26%   |
| Plantronics                      | 17       | 0.26%   |
| Creative Technology              | 13       | 0.2%    |
| XMOS                             | 11       | 0.17%   |
| M-Audio                          | 11       | 0.17%   |
| Ensoniq                          | 9        | 0.14%   |
| Silicon Integrated Systems [SiS] | 8        | 0.12%   |
| Yamaha                           | 7        | 0.11%   |
| Tenx Technology                  | 7        | 0.11%   |
| Micro Star International         | 7        | 0.11%   |
| BEHRINGER International          | 7        | 0.11%   |
| Turtle Beach                     | 6        | 0.09%   |
| Sony                             | 6        | 0.09%   |
| RODE Microphones                 | 6        | 0.09%   |
| GYROCOM C&C                      | 6        | 0.09%   |
| Dell                             | 6        | 0.09%   |
| PreSonus Audio Electronics       | 5        | 0.08%   |
| Medeli Electronics               | 5        | 0.08%   |
| KTMicro                          | 5        | 0.08%   |
| Alesis                           | 5        | 0.08%   |
| AKAI Professional M.I.           | 5        | 0.08%   |
| Realtek Semiconductor            | 4        | 0.06%   |
| Hewlett-Packard                  | 4        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 347      | 4.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 301      | 4.07%   |
| AMD Starship/Matisse HD Audio Controller                                          | 297      | 4.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 241      | 3.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 238      | 3.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 213      | 2.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 208      | 2.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 181      | 2.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 178      | 2.4%    |
| Intel 200 Series PCH HD Audio                                                     | 170      | 2.3%    |
| AMD Family 17h/19h HD Audio Controller                                            | 168      | 2.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 167      | 2.26%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 151      | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                        | 139      | 1.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 121      | 1.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 115      | 1.55%   |
| AMD FCH Azalia Controller                                                         | 114      | 1.54%   |
| Nvidia High Definition Audio Controller                                           | 113      | 1.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 113      | 1.53%   |
| Nvidia GP106 High Definition Audio Controller                                     | 87       | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 84       | 1.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 84       | 1.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 80       | 1.08%   |
| Nvidia GP104 High Definition Audio Controller                                     | 78       | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                                | 76       | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 75       | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 74       | 1%      |
| Nvidia MCP61 High Definition Audio                                                | 73       | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                                     | 65       | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 65       | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 63       | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                                     | 62       | 0.84%   |
| Nvidia GK104 HDMI Audio Controller                                                | 62       | 0.84%   |
| Nvidia GM204 High Definition Audio Controller                                     | 61       | 0.82%   |
| Nvidia GM206 High Definition Audio Controller                                     | 60       | 0.81%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 60       | 0.81%   |
| Nvidia GP108 High Definition Audio Controller                                     | 58       | 0.78%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 57       | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                                     | 56       | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                                | 54       | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 429      | 14.89%  |
| Kingston            | 423      | 14.68%  |
| Corsair             | 421      | 14.61%  |
| Samsung Electronics | 306      | 10.62%  |
| G.Skill             | 302      | 10.48%  |
| SK hynix            | 277      | 9.61%   |
| Crucial             | 260      | 9.02%   |
| Micron Technology   | 166      | 5.76%   |
| Nanya Technology    | 45       | 1.56%   |
| Transcend           | 25       | 0.87%   |
| Ramaxel Technology  | 25       | 0.87%   |
| Elpida              | 25       | 0.87%   |
| A-DATA Technology   | 19       | 0.66%   |
| Unknown             | 17       | 0.59%   |
| Unknown (ABCD)      | 15       | 0.52%   |
| Team                | 14       | 0.49%   |
| Patriot             | 14       | 0.49%   |
| Unifosa             | 13       | 0.45%   |
| PNY                 | 13       | 0.45%   |
| Unknown (0x0C97)    | 6        | 0.21%   |
| Qimonda             | 6        | 0.21%   |
| Timetec             | 5        | 0.17%   |
| Innodisk            | 4        | 0.14%   |
| TEXTORM             | 3        | 0.1%    |
| OCZ                 | 3        | 0.1%    |
| Hewlett-Packard     | 3        | 0.1%    |
| ASint Technology    | 3        | 0.1%    |
| Toshiba             | 2        | 0.07%   |
| Swissbit            | 2        | 0.07%   |
| Ramos Technology    | 2        | 0.07%   |
| Lexar               | 2        | 0.07%   |
| Kllisre             | 2        | 0.07%   |
| Apacer              | 2        | 0.07%   |
| Wodposit            | 1        | 0.03%   |
| Unknown (F301)      | 1        | 0.03%   |
| Unknown (AB)        | 1        | 0.03%   |
| Unknown (0x0C26)    | 1        | 0.03%   |
| Unknown (07FB)      | 1        | 0.03%   |
| Thermaltake         | 1        | 0.03%   |
| Texas_Instrument    | 1        | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 42       | 1.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 25       | 0.79%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s           | 21       | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 18       | 0.57%   |
| Unknown                                                        | 17       | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 16       | 0.51%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 16       | 0.51%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s          | 16       | 0.51%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 16       | 0.51%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 15       | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 15       | 0.47%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 15       | 0.47%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 15       | 0.47%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 14       | 0.44%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 14       | 0.44%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 14       | 0.44%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1800MT/s         | 13       | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 12       | 0.38%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 12       | 0.38%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s           | 12       | 0.38%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 12       | 0.38%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 12       | 0.38%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 12       | 0.38%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 11       | 0.35%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 11       | 0.35%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 11       | 0.35%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 11       | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 10       | 0.32%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s            | 10       | 0.32%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s            | 10       | 0.32%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 10       | 0.32%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 10       | 0.32%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s          | 10       | 0.32%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 9        | 0.28%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 9        | 0.28%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s         | 9        | 0.28%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s            | 9        | 0.28%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s            | 9        | 0.28%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s          | 9        | 0.28%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s            | 9        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 1008     | 39.61%  |
| DDR3    | 958      | 37.64%  |
| DDR2    | 181      | 7.11%   |
| Unknown | 155      | 6.09%   |
| SDRAM   | 145      | 5.7%    |
| DDR     | 49       | 1.93%   |
| LPDDR4  | 20       | 0.79%   |
| DDR5    | 20       | 0.79%   |
| DRAM    | 6        | 0.24%   |
| RAM     | 1        | 0.04%   |
| LPDDR5  | 1        | 0.04%   |
| LPDDR3  | 1        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2313     | 93.15%  |
| SODIMM       | 148      | 5.96%   |
| RIMM         | 11       | 0.44%   |
| FB-DIMM      | 7        | 0.28%   |
| Row Of Chips | 4        | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 943      | 33.85%  |
| 4096  | 809      | 29.04%  |
| 2048  | 465      | 16.69%  |
| 16384 | 314      | 11.27%  |
| 1024  | 173      | 6.21%   |
| 32768 | 48       | 1.72%   |
| 512   | 30       | 1.08%   |
| 256   | 3        | 0.11%   |
| 6144  | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 509      | 18.11%  |
| 1333    | 328      | 11.67%  |
| 3200    | 216      | 7.69%   |
| 2400    | 172      | 6.12%   |
| 2133    | 139      | 4.95%   |
| 2667    | 137      | 4.88%   |
| 800     | 134      | 4.77%   |
| 3600    | 132      | 4.7%    |
| 667     | 89       | 3.17%   |
| 1867    | 81       | 2.88%   |
| 1066    | 63       | 2.24%   |
| 1800    | 59       | 2.1%    |
| Unknown | 54       | 1.92%   |
| 1866    | 51       | 1.81%   |
| 2666    | 48       | 1.71%   |
| 3000    | 47       | 1.67%   |
| 2933    | 45       | 1.6%    |
| 3400    | 41       | 1.46%   |
| 3733    | 27       | 0.96%   |
| 400     | 25       | 0.89%   |
| 2800    | 23       | 0.82%   |
| 1067    | 22       | 0.78%   |
| 2048    | 21       | 0.75%   |
| 533     | 20       | 0.71%   |
| 3800    | 19       | 0.68%   |
| 3533    | 18       | 0.64%   |
| 3466    | 18       | 0.64%   |
| 3666    | 15       | 0.53%   |
| 3266    | 15       | 0.53%   |
| 2000    | 14       | 0.5%    |
| 3534    | 12       | 0.43%   |
| 2465    | 12       | 0.43%   |
| 1648    | 12       | 0.43%   |
| 1639    | 12       | 0.43%   |
| 1334    | 12       | 0.43%   |
| 2733    | 11       | 0.39%   |
| 3866    | 10       | 0.36%   |
| 333     | 10       | 0.36%   |
| 4800    | 9        | 0.32%   |
| 3100    | 9        | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 103      | 44.02%  |
| Brother Industries    | 40       | 17.09%  |
| Canon                 | 34       | 14.53%  |
| Samsung Electronics   | 30       | 12.82%  |
| Seiko Epson           | 14       | 5.98%   |
| Prolific Technology   | 3        | 1.28%   |
| Ricoh                 | 2        | 0.85%   |
| Lexmark International | 2        | 0.85%   |
| Xerox                 | 1        | 0.43%   |
| STMicroelectronics    | 1        | 0.43%   |
| QinHeng Electronics   | 1        | 0.43%   |
| Pantum                | 1        | 0.43%   |
| Kyocera               | 1        | 0.43%   |
| Apple                 | 1        | 0.43%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| HP ENVY 4520 series                  | 9        | 3.83%   |
| Samsung M2070 Series                 | 8        | 3.4%    |
| HP DeskJet 3630 series               | 6        | 2.55%   |
| HP DeskJet 2700 series               | 6        | 2.55%   |
| HP ENVY Photo 6200 series            | 5        | 2.13%   |
| HP DeskJet 2600 series               | 5        | 2.13%   |
| Canon PIXMA MG3600 Series            | 5        | 2.13%   |
| HP OfficeJet 3830 series             | 4        | 1.7%    |
| HP ENVY 5000 series                  | 4        | 1.7%    |
| HP DeskJet 3700 series               | 4        | 1.7%    |
| HP Deskjet 3050A                     | 4        | 1.7%    |
| Brother HL-2030 Laser Printer        | 4        | 1.7%    |
| Seiko Epson XP-240 Series            | 3        | 1.28%   |
| Samsung ML-1640 Series Laser Printer | 3        | 1.28%   |
| Samsung CLX-3170 Series              | 3        | 1.28%   |
| Prolific PL2305 Parallel Port        | 3        | 1.28%   |
| HP DeskJet Plus 4100 series          | 3        | 1.28%   |
| HP DeskJet F4200 series              | 3        | 1.28%   |
| Brother Printer                      | 3        | 1.28%   |
| Brother DCP-7055 scanner/printer     | 3        | 1.28%   |
| Seiko Epson XP-2100 Series           | 2        | 0.85%   |
| Samsung SCX-3400 Series              | 2        | 0.85%   |
| Samsung ML-1660 Series               | 2        | 0.85%   |
| Samsung ML-1630 Series               | 2        | 0.85%   |
| Samsung M2020 Series                 | 2        | 0.85%   |
| Samsung CLX-3180 Series              | 2        | 0.85%   |
| HP LaserJet 1200                     | 2        | 0.85%   |
| HP ENVY 5540 series                  | 2        | 0.85%   |
| HP DeskJet 5550                      | 2        | 0.85%   |
| HP Deskjet 3070 B611 series          | 2        | 0.85%   |
| HP DeskJet 2130 series               | 2        | 0.85%   |
| HP Deskjet 1510                      | 2        | 0.85%   |
| Canon TS5100 series                  | 2        | 0.85%   |
| Canon LiDE 400                       | 2        | 0.85%   |
| Canon iP7200 series                  | 2        | 0.85%   |
| Brother MFC-L2710DW series           | 2        | 0.85%   |
| Brother MFC-9330CDW                  | 2        | 0.85%   |
| Brother HL-L2375DW series            | 2        | 0.85%   |
| Brother HL-L2350DW series            | 2        | 0.85%   |
| Brother DCP-L2530DW series           | 2        | 0.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 53       | 63.86%  |
| Seiko Epson     | 18       | 21.69%  |
| Hewlett-Packard | 8        | 9.64%   |
| AGFA-Gevaert NV | 4        | 4.82%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                            | 8        | 9.64%   |
| Canon CanoScan N1240U/LiDE 30                                 | 8        | 9.64%   |
| Canon CanoScan LIDE 25                                        | 7        | 8.43%   |
| Canon CanoScan LiDE 110                                       | 7        | 8.43%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 4        | 4.82%   |
| Canon CanoScan LiDE 60                                        | 3        | 3.61%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 3        | 3.61%   |
| Canon CanoScan LiDE 200                                       | 3        | 3.61%   |
| AGFA-Gevaert NV SnapScan e20                                  | 3        | 3.61%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 2        | 2.41%   |
| Seiko Epson GT-F700 [Perfection V350]                         | 2        | 2.41%   |
| Seiko Epson GT-9800F [Perfection 3200]                        | 2        | 2.41%   |
| Seiko Epson GT-6600U [Perfection 610]                         | 2        | 2.41%   |
| Canon CanoScan N650U/N656U                                    | 2        | 2.41%   |
| Canon CanoScan LiDE 220                                       | 2        | 2.41%   |
| Canon CanoScan LiDE 210                                       | 2        | 2.41%   |
| Canon CanoScan LiDE 120                                       | 2        | 2.41%   |
| Canon CanoScan 4200F                                          | 2        | 2.41%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]       | 1        | 1.2%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1        | 1.2%    |
| Seiko Epson GT-F600 [Perfection 4180]                         | 1        | 1.2%    |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 1.2%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]            | 1        | 1.2%    |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 1        | 1.2%    |
| HP ScanJet G4050                                              | 1        | 1.2%    |
| HP ScanJet G4010                                              | 1        | 1.2%    |
| HP ScanJet 5200c                                              | 1        | 1.2%    |
| HP ScanJet 4570c                                              | 1        | 1.2%    |
| HP ScanJet 3570c                                              | 1        | 1.2%    |
| HP ScanJet 3500c                                              | 1        | 1.2%    |
| HP ScanJet 2300c                                              | 1        | 1.2%    |
| HP PSC 1200                                                   | 1        | 1.2%    |
| Canon CanoScan LiDE 70                                        | 1        | 1.2%    |
| Canon CanoScan LiDE 100                                       | 1        | 1.2%    |
| Canon CanoScan 9000F Mark II                                  | 1        | 1.2%    |
| Canon CanoScan 4400F                                          | 1        | 1.2%    |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 1        | 1.2%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 310      | 44.8%   |
| Microdia                      | 44       | 6.36%   |
| Microsoft                     | 43       | 6.21%   |
| Samsung Electronics           | 30       | 4.34%   |
| Sunplus Innovation Technology | 26       | 3.76%   |
| Guillemot                     | 22       | 3.18%   |
| Chicony Electronics           | 19       | 2.75%   |
| ARC International             | 15       | 2.17%   |
| Apple                         | 14       | 2.02%   |
| Creative Technology           | 13       | 1.88%   |
| Realtek Semiconductor         | 12       | 1.73%   |
| Generalplus Technology        | 11       | 1.59%   |
| Sonix Technology              | 10       | 1.45%   |
| Hewlett-Packard               | 9        | 1.3%    |
| KYE Systems (Mouse Systems)   | 8        | 1.16%   |
| GEMBIRD                       | 8        | 1.16%   |
| HD 2MP WEBCAM                 | 7        | 1.01%   |
| Z-Star Microelectronics       | 6        | 0.87%   |
| WaveRider Communications      | 6        | 0.87%   |
| Cubeternet                    | 6        | 0.87%   |
| Sunplus IT                    | 5        | 0.72%   |
| AVerMedia Technologies        | 5        | 0.72%   |
| Arkmicro Technologies         | 4        | 0.58%   |
| Trust                         | 3        | 0.43%   |
| MacroSilicon                  | 3        | 0.43%   |
| Jieli Technology              | 3        | 0.43%   |
| Huawei Technologies           | 3        | 0.43%   |
| Xiongmai                      | 2        | 0.29%   |
| Syntek                        | 2        | 0.29%   |
| Razer USA                     | 2        | 0.29%   |
| Philips (or NXP)              | 2        | 0.29%   |
| Novatek Microelectronics      | 2        | 0.29%   |
| IMC Networks                  | 2        | 0.29%   |
| Genesys Logic                 | 2        | 0.29%   |
| Alcor Micro                   | 2        | 0.29%   |
| YGTek                         | 1        | 0.14%   |
| Yealink Network Technology    | 1        | 0.14%   |
| Xiaomi                        | 1        | 0.14%   |
| WCM_USB                       | 1        | 0.14%   |
| ViewSonic                     | 1        | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 69       | 9.97%   |
| Logitech HD Pro Webcam C920                       | 33       | 4.77%   |
| Samsung Galaxy series, misc. (MTP mode)           | 30       | 4.34%   |
| Logitech HD Webcam C525                           | 28       | 4.05%   |
| Logitech Webcam C170                              | 17       | 2.46%   |
| Logitech C922 Pro Stream Webcam                   | 16       | 2.31%   |
| Microsoft LifeCam HD-3000                         | 15       | 2.17%   |
| ARC International Camera                          | 14       | 2.02%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 14       | 2.02%   |
| Sunplus Full HD webcam                            | 13       | 1.88%   |
| Logitech Webcam C310                              | 13       | 1.88%   |
| Microdia Webcam Vitade AF                         | 12       | 1.73%   |
| Microdia Camera                                   | 11       | 1.59%   |
| Logitech C920 PRO HD Webcam                       | 11       | 1.59%   |
| Guillemot Hercules HD Twist                       | 9        | 1.3%    |
| Sonix USB Camera                                  | 8        | 1.16%   |
| Logitech StreamCam                                | 8        | 1.16%   |
| Logitech HD Webcam C910                           | 8        | 1.16%   |
| Logitech BRIO Ultra HD Webcam                     | 8        | 1.16%   |
| Logitech BRIO 4K Stream Edition                   | 8        | 1.16%   |
| Realtek Full HD webcam                            | 7        | 1.01%   |
| Microdia USB 2.0 Camera                           | 7        | 1.01%   |
| Microdia Sonix USB 2.0 Camera                     | 7        | 1.01%   |
| Logitech Webcam C930e                             | 7        | 1.01%   |
| Logitech QuickCam Pro 5000                        | 7        | 1.01%   |
| Logitech HD Webcam C615                           | 7        | 1.01%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                       | 7        | 1.01%   |
| Microsoft LifeCam VX-5000                         | 6        | 0.87%   |
| Logitech Webcam C300                              | 6        | 0.87%   |
| Logitech QuickCam Pro 4000                        | 6        | 0.87%   |
| Logitech B525 HD Webcam                           | 6        | 0.87%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera        | 6        | 0.87%   |
| HP Webcam HD 4310                                 | 6        | 0.87%   |
| Guillemot Hercules Dualpix Exchange               | 6        | 0.87%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 6        | 0.87%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 6        | 0.87%   |
| WaveRider USB 2.0 Camera                          | 5        | 0.72%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 5        | 0.72%   |
| Sunplus MTD Camera                                | 5        | 0.72%   |
| Microsoft LifeCam Cinema                          | 5        | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Validity Sensors           | 1        | 20%     |
| Synaptics                  | 1        | 20%     |
| Shenzhen Goodix Technology | 1        | 20%     |
| Elan Microelectronics      | 1        | 20%     |
| AuthenTec                  | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 20%     |
| Synaptics  WBDI Fingerprint Reader - USB 052                | 1        | 20%     |
| Shenzhen Goodix  Fingerprint Device                         | 1        | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 1        | 20%     |
| AuthenTec AES2501 Fingerprint Sensor                        | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Hewlett-Packard           | 4        | 16.67%  |
| Gemalto (was Gemplus)     | 4        | 16.67%  |
| SCM Microsystems          | 2        | 8.33%   |
| Realtek Semiconductor     | 2        | 8.33%   |
| Chicony Electronics       | 2        | 8.33%   |
| Aladdin Knowledge Systems | 2        | 8.33%   |
| Yubico.com                | 1        | 4.17%   |
| ST-Ericsson               | 1        | 4.17%   |
| Jing-Mold Enterprise      | 1        | 4.17%   |
| Feitian Technologies      | 1        | 4.17%   |
| Clay Logic                | 1        | 4.17%   |
| Cherry                    | 1        | 4.17%   |
| Alcor Micro               | 1        | 4.17%   |
| Advanced Card Systems     | 1        | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                     | 4        | 16.67%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                 | 3        | 12.5%   |
| Realtek Semiconductor Smart Card Reader Interface                 | 2        | 8.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard              | 2        | 8.33%   |
| Aladdin Knowledge Systems Token JC                                | 2        | 8.33%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                   | 1        | 4.17%   |
| ST-Ericsson Chipcard Reader                                       | 1        | 4.17%   |
| SCM Microsystems SCR335 SmartCard Reader                          | 1        | 4.17%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                   | 1        | 4.17%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 4.17%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                  | 1        | 4.17%   |
| Feitian Technologies FT SCR310                                    | 1        | 4.17%   |
| Clay Logic Nitrokey Pro                                           | 1        | 4.17%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                        | 1        | 4.17%   |
| Alcor Micro Watchdata W 1981                                      | 1        | 4.17%   |
| Advanced Card Systems ACR122U                                     | 1        | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3285     | 85.04%  |
| 1     | 481      | 12.45%  |
| 2     | 73       | 1.89%   |
| 3     | 12       | 0.31%   |
| 4     | 10       | 0.26%   |
| 9     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 278      | 41.68%  |
| Net/wireless             | 130      | 19.49%  |
| Unassigned class         | 55       | 8.25%   |
| Communication controller | 55       | 8.25%   |
| Multimedia controller    | 31       | 4.65%   |
| Sound                    | 25       | 3.75%   |
| Net/ethernet             | 14       | 2.1%    |
| Bluetooth                | 14       | 2.1%    |
| Camera                   | 13       | 1.95%   |
| Chipcard                 | 10       | 1.5%    |
| Network                  | 9        | 1.35%   |
| Storage/raid             | 7        | 1.05%   |
| Storage/ide              | 5        | 0.75%   |
| Firewire controller      | 5        | 0.75%   |
| Card reader              | 5        | 0.75%   |
| Modem                    | 4        | 0.6%    |
| Fingerprint reader       | 4        | 0.6%    |
| Tv card                  | 2        | 0.3%    |
| Dvb card                 | 1        | 0.15%   |

