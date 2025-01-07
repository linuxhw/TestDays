Linux in Croatia - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

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

Total: 286

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | H510M-HDV/M.2 SE            | [cd15dad76b](https://linux-hardware.org/?probe=cd15dad76b) | Jan 02, 2025 |
| HP            | 1495                        | [f9588cf3eb](https://linux-hardware.org/?probe=f9588cf3eb) | Dec 30, 2024 |
| Gigabyte      | B550M DS3H                  | [01c866bd0e](https://linux-hardware.org/?probe=01c866bd0e) | Dec 21, 2024 |
| ASRock        | B650M PG Lightning          | [93343b543c](https://linux-hardware.org/?probe=93343b543c) | Dec 16, 2024 |
| Gigabyte      | H97M-HD3                    | [0e0965bc17](https://linux-hardware.org/?probe=0e0965bc17) | Dec 15, 2024 |
| ASRock        | B250M-HDV                   | [feade65edb](https://linux-hardware.org/?probe=feade65edb) | Dec 13, 2024 |
| ASRock        | B650M PG Lightning          | [4370a5ccdf](https://linux-hardware.org/?probe=4370a5ccdf) | Dec 11, 2024 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [c2162b5ffe](https://linux-hardware.org/?probe=c2162b5ffe) | Nov 30, 2024 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [1997f45737](https://linux-hardware.org/?probe=1997f45737) | Nov 28, 2024 |
| HP            | 81C5 MVB                    | [18206773c5](https://linux-hardware.org/?probe=18206773c5) | Nov 24, 2024 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [efffc4e893](https://linux-hardware.org/?probe=efffc4e893) | Nov 05, 2024 |
| HP            | 3048h                       | [8984b9b0ff](https://linux-hardware.org/?probe=8984b9b0ff) | Oct 31, 2024 |
| HP            | 1495                        | [2fd3ea9199](https://linux-hardware.org/?probe=2fd3ea9199) | Oct 25, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | [632d66a3f3](https://linux-hardware.org/?probe=632d66a3f3) | Oct 23, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [abab79db3c](https://linux-hardware.org/?probe=abab79db3c) | Oct 19, 2024 |
| ASRock        | A620M-HDV/M.2               | [2f77fd05f6](https://linux-hardware.org/?probe=2f77fd05f6) | Oct 15, 2024 |
| EMC           | 110-335-541B-04 FFF         | [a45ce6a612](https://linux-hardware.org/?probe=a45ce6a612) | Oct 01, 2024 |
| Gigabyte      | A620M S2H                   | [125f5a8d74](https://linux-hardware.org/?probe=125f5a8d74) | Sep 10, 2024 |
| ASUSTek       | M5A97 R2.0                  | [1e5012faa8](https://linux-hardware.org/?probe=1e5012faa8) | Sep 05, 2024 |
| ASUSTek       | M5A97 R2.0                  | [03c509b9db](https://linux-hardware.org/?probe=03c509b9db) | Sep 02, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [18c81a5d40](https://linux-hardware.org/?probe=18c81a5d40) | Aug 24, 2024 |
| Gigabyte      | B450 AORUS M                | [6ef48298ce](https://linux-hardware.org/?probe=6ef48298ce) | Aug 13, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | [b2182890a9](https://linux-hardware.org/?probe=b2182890a9) | Aug 09, 2024 |
| ASRock        | H97 Anniversary             | [ec56437f32](https://linux-hardware.org/?probe=ec56437f32) | Jul 31, 2024 |
| ASRock        | B560 Steel Legend           | [d3002dc7c2](https://linux-hardware.org/?probe=d3002dc7c2) | Jul 29, 2024 |
| MAXSUN        | MS-TZZ B560M                | [cca7e1333d](https://linux-hardware.org/?probe=cca7e1333d) | Jul 23, 2024 |
| HP            | 18E4                        | [bcfb2d82b4](https://linux-hardware.org/?probe=bcfb2d82b4) | Jul 20, 2024 |
| ASRock        | B650 PG Lightning           | [69f46fe2a1](https://linux-hardware.org/?probe=69f46fe2a1) | Jul 04, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | [8211ffc9b9](https://linux-hardware.org/?probe=8211ffc9b9) | Jun 07, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [15dd095045](https://linux-hardware.org/?probe=15dd095045) | Jun 01, 2024 |
| ASUSTek       | M5A78L LE                   | [5afe282618](https://linux-hardware.org/?probe=5afe282618) | May 27, 2024 |
| Gigabyte      | B760 GAMING X DDR4          | [740702872c](https://linux-hardware.org/?probe=740702872c) | May 27, 2024 |
| Gigabyte      | B550M DS3H                  | [34390c3261](https://linux-hardware.org/?probe=34390c3261) | May 12, 2024 |
| Gigabyte      | B550M DS3H                  | [3d5dfb554e](https://linux-hardware.org/?probe=3d5dfb554e) | May 12, 2024 |
| HP            | 1496                        | [64f726b9c5](https://linux-hardware.org/?probe=64f726b9c5) | Apr 30, 2024 |
| ASUSTek       | PRIME B560M-A               | [886328abc3](https://linux-hardware.org/?probe=886328abc3) | Apr 25, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [0b8cd1192f](https://linux-hardware.org/?probe=0b8cd1192f) | Apr 24, 2024 |
| HP            | 8876 11                     | [b15b96ee62](https://linux-hardware.org/?probe=b15b96ee62) | Apr 23, 2024 |
| MSI           | PRO Z790-P WIFI             | [3ac4d133b8](https://linux-hardware.org/?probe=3ac4d133b8) | Apr 23, 2024 |
| Dell          | 06JWJY A01                  | [824cb2807f](https://linux-hardware.org/?probe=824cb2807f) | Apr 11, 2024 |
| HP            | 1495                        | [7bb71cc6c8](https://linux-hardware.org/?probe=7bb71cc6c8) | Apr 03, 2024 |
| HP            | 1495                        | [369904b953](https://linux-hardware.org/?probe=369904b953) | Apr 03, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | [74e95f0015](https://linux-hardware.org/?probe=74e95f0015) | Mar 24, 2024 |
| HP            | 83EF                        | [34c1c23a84](https://linux-hardware.org/?probe=34c1c23a84) | Mar 23, 2024 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [fac66be915](https://linux-hardware.org/?probe=fac66be915) | Mar 19, 2024 |
| Gigabyte      | B650M DS3H                  | [91f2211c0c](https://linux-hardware.org/?probe=91f2211c0c) | Feb 14, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [bf2ce0efeb](https://linux-hardware.org/?probe=bf2ce0efeb) | Jan 15, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [80799f979c](https://linux-hardware.org/?probe=80799f979c) | Jan 10, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ff9686f03c](https://linux-hardware.org/?probe=ff9686f03c) | Jan 06, 2024 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [7a9ff71d9b](https://linux-hardware.org/?probe=7a9ff71d9b) | Dec 28, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [58bbd67a73](https://linux-hardware.org/?probe=58bbd67a73) | Dec 23, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [155e0f1c37](https://linux-hardware.org/?probe=155e0f1c37) | Dec 22, 2023 |
| Dell          | 0R790T A00                  | [8a72b2a4ce](https://linux-hardware.org/?probe=8a72b2a4ce) | Dec 13, 2023 |
| eMachines     | ET1850                      | [b433ca3cfa](https://linux-hardware.org/?probe=b433ca3cfa) | Dec 02, 2023 |
| MSI           | PRO B650M-A WIFI            | [2a9ba6fc77](https://linux-hardware.org/?probe=2a9ba6fc77) | Nov 17, 2023 |
| HP            | 18E4                        | [fb73ea4228](https://linux-hardware.org/?probe=fb73ea4228) | Nov 12, 2023 |
| ASRock        | B450M-HDV R4.0              | [c019f410aa](https://linux-hardware.org/?probe=c019f410aa) | Nov 08, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [24304767eb](https://linux-hardware.org/?probe=24304767eb) | Oct 21, 2023 |
| Intel         | DG965RY AAD41691-301        | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [e0158c541c](https://linux-hardware.org/?probe=e0158c541c) | Sep 29, 2023 |
| Gigabyte      | X570S UD                    | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [5a6ff779bd](https://linux-hardware.org/?probe=5a6ff779bd) | Sep 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [bd389fb2a0](https://linux-hardware.org/?probe=bd389fb2a0) | Sep 15, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Intel         | DH61CR AAG14064-204         | [2fa0bbc7ec](https://linux-hardware.org/?probe=2fa0bbc7ec) | Aug 28, 2023 |
| ASRock        | B560 Steel Legend           | [b2e8cd4ed2](https://linux-hardware.org/?probe=b2e8cd4ed2) | Aug 26, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| HP            | 2B47                        | [06373794be](https://linux-hardware.org/?probe=06373794be) | Aug 01, 2023 |
| ASRock        | B450M-HDV R4.0              | [289d9fe165](https://linux-hardware.org/?probe=289d9fe165) | Jun 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| MSI           | PRO Z690-A DDR4             | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| HPE           | ProLiant ML30 Gen10 Plus    | [3a75fa5c03](https://linux-hardware.org/?probe=3a75fa5c03) | May 07, 2023 |
| ASUSTek       | GRYPHON Z87                 | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [490a059818](https://linux-hardware.org/?probe=490a059818) | Apr 13, 2023 |
| ASUSTek       | PRIME B560M-A               | [171e39cdb6](https://linux-hardware.org/?probe=171e39cdb6) | Apr 05, 2023 |
| MSI           | B450M PRO-M2 MAX            | [bdfe7a3498](https://linux-hardware.org/?probe=bdfe7a3498) | Mar 21, 2023 |
| ASUSTek       | H110M-R                     | [2409dc15b4](https://linux-hardware.org/?probe=2409dc15b4) | Mar 10, 2023 |
| ASRock        | H97 Pro4                    | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| MSI           | 0A90                        | [9210981559](https://linux-hardware.org/?probe=9210981559) | Feb 06, 2023 |
| MSI           | 0A90                        | [aedd414dbf](https://linux-hardware.org/?probe=aedd414dbf) | Feb 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| ASUSTek       | PRIME B560M-A               | [2b04043ef0](https://linux-hardware.org/?probe=2b04043ef0) | Jan 10, 2023 |
| ASRock        | B550M Steel Legend          | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [15d7102174](https://linux-hardware.org/?probe=15d7102174) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [52525a1058](https://linux-hardware.org/?probe=52525a1058) | Dec 08, 2022 |
| ASRock        | K10N78D                     | [b5e2e7a024](https://linux-hardware.org/?probe=b5e2e7a024) | Dec 02, 2022 |
| ASRock        | B550M-ITX/ac                | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| HP            | 1998                        | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| ASUSTek       | PRIME H410M-A               | [b3cac9f8b8](https://linux-hardware.org/?probe=b3cac9f8b8) | Nov 02, 2022 |
| ASUSTek       | PRIME B560M-A               | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| ASUSTek       | M5A78L LE                   | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Lenovo        | 0x30F617AA NOK              | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| ASRock        | A320M-DVS R4.0              | [0dca3e500c](https://linux-hardware.org/?probe=0dca3e500c) | Sep 22, 2022 |
| ASUSTek       | Z97-PRO                     | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5ddb15f201](https://linux-hardware.org/?probe=5ddb15f201) | Aug 07, 2022 |
| HP            | 1825                        | [4a21a02ae4](https://linux-hardware.org/?probe=4a21a02ae4) | Jul 29, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [3c665fb25f](https://linux-hardware.org/?probe=3c665fb25f) | Jul 28, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| ASRock        | K10N78D                     | [650465a972](https://linux-hardware.org/?probe=650465a972) | Jul 06, 2022 |
| WinFast       | NF-MCP55 FAB1.0             | [bb066cc2da](https://linux-hardware.org/?probe=bb066cc2da) | Jul 03, 2022 |
| MSI           | Z87-G41 PC Mate             | [c73501602b](https://linux-hardware.org/?probe=c73501602b) | Jun 26, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [0d4266a0f3](https://linux-hardware.org/?probe=0d4266a0f3) | Jun 15, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [987ef7b2e7](https://linux-hardware.org/?probe=987ef7b2e7) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Gigabyte      | X48T-DQ6                    | [2953148fae](https://linux-hardware.org/?probe=2953148fae) | May 16, 2022 |
| Dell          | 0J37VM A01                  | [a5363ae511](https://linux-hardware.org/?probe=a5363ae511) | May 09, 2022 |
| ASUSTek       | PRIME H510M-A               | [1e2ee4a2fb](https://linux-hardware.org/?probe=1e2ee4a2fb) | May 09, 2022 |
| ASRock        | Z87 Extreme4                | [db3a8bef92](https://linux-hardware.org/?probe=db3a8bef92) | May 09, 2022 |
| ASRock        | H470M-HDV                   | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| MSI           | B450 TOMAHAWK               | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| Gigabyte      | P31-ES3G                    | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| Intel         | H61M-S2PV                   | [caa602b556](https://linux-hardware.org/?probe=caa602b556) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | [4db68ede02](https://linux-hardware.org/?probe=4db68ede02) | Apr 27, 2022 |
| ASRock        | H61M-DGS                    | [c8019d43f7](https://linux-hardware.org/?probe=c8019d43f7) | Apr 25, 2022 |
| ASRock        | H97 Pro4                    | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Pegatron      | 2AC3                        | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| ASRock        | A320M-HDV R4.0              | [73cf5373cf](https://linux-hardware.org/?probe=73cf5373cf) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | [f76380fdae](https://linux-hardware.org/?probe=f76380fdae) | Apr 03, 2022 |
| Gigabyte      | X48T-DQ6                    | [f63c898bc3](https://linux-hardware.org/?probe=f63c898bc3) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [561a945c5a](https://linux-hardware.org/?probe=561a945c5a) | Mar 13, 2022 |
| ASRock        | B360 Gaming K4              | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| ASUSTek       | Z170-P                      | [fac84edcf2](https://linux-hardware.org/?probe=fac84edcf2) | Mar 08, 2022 |
| ASRock        | H97 Pro4                    | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | X48T-DQ6                    | [593cb60512](https://linux-hardware.org/?probe=593cb60512) | Mar 06, 2022 |
| Foxconn       | 2A8Ch                       | [49093d0be0](https://linux-hardware.org/?probe=49093d0be0) | Mar 05, 2022 |
| Gigabyte      | H410M H V3                  | [d0ee45a4b1](https://linux-hardware.org/?probe=d0ee45a4b1) | Feb 26, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [731457f46c](https://linux-hardware.org/?probe=731457f46c) | Feb 13, 2022 |
| ECS           | A75F2-M2                    | [0c4ea60fd5](https://linux-hardware.org/?probe=0c4ea60fd5) | Feb 12, 2022 |
| Gigabyte      | B85M-DS3H                   | [98d6451ac1](https://linux-hardware.org/?probe=98d6451ac1) | Feb 07, 2022 |
| ASRock        | Z97M Pro4                   | [a496090845](https://linux-hardware.org/?probe=a496090845) | Feb 01, 2022 |
| Foxconn       | 2A8Ch                       | [276caa5169](https://linux-hardware.org/?probe=276caa5169) | Jan 23, 2022 |
| ASRock        | Z590 Pro4                   | [a89877d9de](https://linux-hardware.org/?probe=a89877d9de) | Jan 16, 2022 |
| ASRock        | Z590 Pro4                   | [7a2453280a](https://linux-hardware.org/?probe=7a2453280a) | Jan 14, 2022 |
| ECS           | H61H2-M2                    | [21704ab656](https://linux-hardware.org/?probe=21704ab656) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | [47b4da86e2](https://linux-hardware.org/?probe=47b4da86e2) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | [f1f247b586](https://linux-hardware.org/?probe=f1f247b586) | Jan 09, 2022 |
| MSI           | H81M-P33                    | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| Gigabyte      | 965P-DS3                    | [467762be06](https://linux-hardware.org/?probe=467762be06) | Dec 29, 2021 |
| ECS           | H61H2-M2                    | [6f3d8856df](https://linux-hardware.org/?probe=6f3d8856df) | Dec 29, 2021 |
| ASRock        | 870 Extreme3                | [d202f241ee](https://linux-hardware.org/?probe=d202f241ee) | Dec 23, 2021 |
| Intel         | DH61CR AAG14064-204         | [13c79f41a6](https://linux-hardware.org/?probe=13c79f41a6) | Dec 18, 2021 |
| Intel         | DH61CR AAG14064-204         | [dbc555c5ad](https://linux-hardware.org/?probe=dbc555c5ad) | Dec 16, 2021 |
| ASRock        | B450M-HDV R4.0              | [594becb8c9](https://linux-hardware.org/?probe=594becb8c9) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | PRIME A320M-K               | [d9019c420c](https://linux-hardware.org/?probe=d9019c420c) | Dec 04, 2021 |
| Dell          | 0GDG8Y A00                  | [d0cf0cc443](https://linux-hardware.org/?probe=d0cf0cc443) | Dec 01, 2021 |
| Foxconn       | 2A8Ch                       | [1eff06a331](https://linux-hardware.org/?probe=1eff06a331) | Nov 30, 2021 |
| Foxconn       | 2A8Ch                       | [1f650ebd72](https://linux-hardware.org/?probe=1f650ebd72) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [c77e499435](https://linux-hardware.org/?probe=c77e499435) | Nov 13, 2021 |
| ASUSTek       | M4A78T-E                    | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| ASUSTek       | P8Z77-V LX                  | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| MSI           | P55-CD53                    | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| MSI           | P55-CD53                    | [12bf811a5c](https://linux-hardware.org/?probe=12bf811a5c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | M5A78L LE                   | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Pegatron      | 2A73h                       | [dc24d5d19f](https://linux-hardware.org/?probe=dc24d5d19f) | Oct 16, 2021 |
| ASUSTek       | PRIME H410M-R               | [d891006b52](https://linux-hardware.org/?probe=d891006b52) | Oct 14, 2021 |
| ASUSTek       | B85M-E                      | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| ASUSTek       | A58M-K                      | [2ca6ce79db](https://linux-hardware.org/?probe=2ca6ce79db) | Oct 03, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e5508ac7ab](https://linux-hardware.org/?probe=e5508ac7ab) | Sep 27, 2021 |
| ASUSTek       | M4A78T-E                    | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| MSI           | A320M PRO-VH PLUS           | [149504315f](https://linux-hardware.org/?probe=149504315f) | Aug 10, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| ASRock        | B450M-HDV R4.0              | [f15116c26a](https://linux-hardware.org/?probe=f15116c26a) | Jul 30, 2021 |
| ASRock        | Z370 Pro4                   | [9a9f7c5e69](https://linux-hardware.org/?probe=9a9f7c5e69) | Jul 20, 2021 |
| Gigabyte      | GA-990XA-UD3                | [af31bae015](https://linux-hardware.org/?probe=af31bae015) | Jun 10, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [83b3cc659a](https://linux-hardware.org/?probe=83b3cc659a) | Jun 07, 2021 |
| Dell          | 06CV2N A01                  | [35a0afd617](https://linux-hardware.org/?probe=35a0afd617) | May 25, 2021 |
| MSI           | B450 TOMAHAWK               | [eb4e8e4cc2](https://linux-hardware.org/?probe=eb4e8e4cc2) | May 25, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASRock        | P45DE                       | [2f6b602e36](https://linux-hardware.org/?probe=2f6b602e36) | Apr 18, 2021 |
| ASRock        | Z370 Pro4                   | [7ad77d82ba](https://linux-hardware.org/?probe=7ad77d82ba) | Apr 03, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [b776bc7947](https://linux-hardware.org/?probe=b776bc7947) | Mar 31, 2021 |
| MSI           | B450M PRO-M2 MAX            | [6e5e0c9ef4](https://linux-hardware.org/?probe=6e5e0c9ef4) | Mar 19, 2021 |
| MSI           | Z390-A PRO                  | [12566ee726](https://linux-hardware.org/?probe=12566ee726) | Mar 10, 2021 |
| Gigabyte      | G1.Sniper Z87               | [c9a3501b03](https://linux-hardware.org/?probe=c9a3501b03) | Mar 02, 2021 |
| ASRock        | FM2A75M-DGS                 | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME A320M-K               | [24a672b8ac](https://linux-hardware.org/?probe=24a672b8ac) | Feb 25, 2021 |
| ASRock        | Z87 Extreme4                | [081e14044d](https://linux-hardware.org/?probe=081e14044d) | Feb 13, 2021 |
| Dell          | 0NNGP2 A00                  | [9be58392b6](https://linux-hardware.org/?probe=9be58392b6) | Feb 08, 2021 |
| Dell          | 0J37VM A01                  | [3062914f46](https://linux-hardware.org/?probe=3062914f46) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | [34e1267a80](https://linux-hardware.org/?probe=34e1267a80) | Feb 07, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [eee7c1f592](https://linux-hardware.org/?probe=eee7c1f592) | Feb 03, 2021 |
| ASRock        | ConRoe1333-D667             | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | [28cb4726bb](https://linux-hardware.org/?probe=28cb4726bb) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | [0b4b751863](https://linux-hardware.org/?probe=0b4b751863) | Jan 31, 2021 |
| ASRock        | X570M Pro4                  | [9cd91004ab](https://linux-hardware.org/?probe=9cd91004ab) | Jan 24, 2021 |
| Gigabyte      | F2A78M-DS2                  | [9afb5c207a](https://linux-hardware.org/?probe=9afb5c207a) | Jan 23, 2021 |
| Dell          | 0DFRFW A01                  | [482bc5334f](https://linux-hardware.org/?probe=482bc5334f) | Jan 22, 2021 |
| MSI           | B450 TOMAHAWK               | [943284255a](https://linux-hardware.org/?probe=943284255a) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | [df34a7d718](https://linux-hardware.org/?probe=df34a7d718) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | [0d8e905a30](https://linux-hardware.org/?probe=0d8e905a30) | Jan 16, 2021 |
| ASUSTek       | Maximus VII HERO            | [9b72f3a82b](https://linux-hardware.org/?probe=9b72f3a82b) | Jan 11, 2021 |
| ASUSTek       | M4A78T-E                    | [e2fa1223c4](https://linux-hardware.org/?probe=e2fa1223c4) | Jan 03, 2021 |
| ASUSTek       | M4A78T-E                    | [db7dfe41a5](https://linux-hardware.org/?probe=db7dfe41a5) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | [2ca3b4e129](https://linux-hardware.org/?probe=2ca3b4e129) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | [638a245f5f](https://linux-hardware.org/?probe=638a245f5f) | Jan 03, 2021 |
| Gigabyte      | GA-MA785GMT-UD2H            | [15160d8a87](https://linux-hardware.org/?probe=15160d8a87) | Jan 02, 2021 |
| HP            | 18EA                        | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| Gigabyte      | GA-MA770-UD3                | [120e788567](https://linux-hardware.org/?probe=120e788567) | Dec 24, 2020 |
| ASUSTek       | H81M-K                      | [03b737b966](https://linux-hardware.org/?probe=03b737b966) | Dec 23, 2020 |
| ASRock        | Z370 Pro4                   | [e6df8b78b5](https://linux-hardware.org/?probe=e6df8b78b5) | Dec 21, 2020 |
| ASUSTek       | M5A78L LE                   | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L LE                   | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| ASRock        | N68-S3 UCC                  | [b75cfae4a3](https://linux-hardware.org/?probe=b75cfae4a3) | Nov 01, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [36db0ea3d4](https://linux-hardware.org/?probe=36db0ea3d4) | Oct 21, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [ff7ecd0641](https://linux-hardware.org/?probe=ff7ecd0641) | Oct 15, 2020 |
| Pegatron      | 2A94h                       | [668c4bbb8b](https://linux-hardware.org/?probe=668c4bbb8b) | Oct 06, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | [b098cfc85e](https://linux-hardware.org/?probe=b098cfc85e) | Sep 30, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | [df11954c4f](https://linux-hardware.org/?probe=df11954c4f) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | [8220732bda](https://linux-hardware.org/?probe=8220732bda) | Sep 28, 2020 |
| ASUSTek       | M5A78L LE                   | [7f4940b41c](https://linux-hardware.org/?probe=7f4940b41c) | Sep 28, 2020 |
| ASRock        | N68-S3 UCC                  | [42ed26b195](https://linux-hardware.org/?probe=42ed26b195) | Sep 19, 2020 |
| ASUSTek       | M4A77                       | [d076f8fe03](https://linux-hardware.org/?probe=d076f8fe03) | Sep 08, 2020 |
| ASRock        | Z87E-ITX                    | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| ASRock        | N68-S3 UCC                  | [a2d99d11fc](https://linux-hardware.org/?probe=a2d99d11fc) | Aug 30, 2020 |
| ASUSTek       | P8H77-V LE                  | [1c2eaa2346](https://linux-hardware.org/?probe=1c2eaa2346) | Aug 23, 2020 |
| HP            | 2129                        | [d1eda00971](https://linux-hardware.org/?probe=d1eda00971) | Aug 20, 2020 |
| MSI           | Z87-G41 PC Mate             | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| Gigabyte      | G41M-Combo                  | [2f3657530f](https://linux-hardware.org/?probe=2f3657530f) | Jun 29, 2020 |
| ASUSTek       | B85M-E                      | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| ASRock        | H97M Pro4                   | [31f3732dc9](https://linux-hardware.org/?probe=31f3732dc9) | Jun 19, 2020 |
| Gigabyte      | G31MX-S2                    | [7da6752573](https://linux-hardware.org/?probe=7da6752573) | May 31, 2020 |
| Gigabyte      | G31MX-S2                    | [5472c53dca](https://linux-hardware.org/?probe=5472c53dca) | May 31, 2020 |
| ASRock        | H81M-DGS R2.0               | [26a9c7f62c](https://linux-hardware.org/?probe=26a9c7f62c) | May 30, 2020 |
| Gigabyte      | 990FXA-UD3                  | [e3042f4583](https://linux-hardware.org/?probe=e3042f4583) | May 24, 2020 |
| ASUSTek       | P8H77-V LE                  | [e6f20d976d](https://linux-hardware.org/?probe=e6f20d976d) | May 17, 2020 |
| Gigabyte      | 965P-DS3                    | [abfb95a938](https://linux-hardware.org/?probe=abfb95a938) | May 11, 2020 |
| Gigabyte      | 965P-DS3                    | [e59e1593d5](https://linux-hardware.org/?probe=e59e1593d5) | May 11, 2020 |
| MSI           | MS-7360                     | [ab94189bcf](https://linux-hardware.org/?probe=ab94189bcf) | May 07, 2020 |
| MSI           | Z87-G41 PC Mate             | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| HP            | 3031h                       | [b4638888cb](https://linux-hardware.org/?probe=b4638888cb) | Apr 14, 2020 |
| ASUSTek       | M5A78L LE                   | [1562c544a6](https://linux-hardware.org/?probe=1562c544a6) | Apr 14, 2020 |
| ASRock        | H61M-DGS                    | [0a090881ae](https://linux-hardware.org/?probe=0a090881ae) | Apr 12, 2020 |
| ASUSTek       | A8V-MQ                      | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| ASRock        | H61M-VS                     | [799e1670fd](https://linux-hardware.org/?probe=799e1670fd) | Mar 18, 2020 |
| HP            | 212B                        | [6058dd53b1](https://linux-hardware.org/?probe=6058dd53b1) | Mar 16, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [26545c7add](https://linux-hardware.org/?probe=26545c7add) | Feb 24, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [1693523c61](https://linux-hardware.org/?probe=1693523c61) | Feb 21, 2020 |
| Intel         | DH67BL AAG10189-213         | [b0e9895bef](https://linux-hardware.org/?probe=b0e9895bef) | Feb 16, 2020 |
| ASRock        | B150M-HDV                   | [c08c6d0574](https://linux-hardware.org/?probe=c08c6d0574) | Feb 08, 2020 |
| HP            | 18E7                        | [de846e5f4f](https://linux-hardware.org/?probe=de846e5f4f) | Jan 22, 2020 |
| Intel         | DH67BL AAG10189-213         | [9ed2076b0d](https://linux-hardware.org/?probe=9ed2076b0d) | Jan 18, 2020 |
| Intel         | DH67BL AAG10189-213         | [dc121e5512](https://linux-hardware.org/?probe=dc121e5512) | Jan 18, 2020 |
| Acer          | Veriton S680G               | [277889b2ff](https://linux-hardware.org/?probe=277889b2ff) | Jan 15, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [e097415087](https://linux-hardware.org/?probe=e097415087) | Dec 26, 2019 |
| ASRock        | N68-S3 UCC                  | [9cbd6c2e0e](https://linux-hardware.org/?probe=9cbd6c2e0e) | Dec 25, 2019 |
| ASRock        | 990FX Extreme3              | [107280e5a9](https://linux-hardware.org/?probe=107280e5a9) | Dec 23, 2019 |
| ASRock        | 990FX Extreme3              | [66a084d547](https://linux-hardware.org/?probe=66a084d547) | Dec 11, 2019 |
| ASRock        | H97 Killer                  | [8538b88e3d](https://linux-hardware.org/?probe=8538b88e3d) | Nov 27, 2019 |
| ASRock        | 970 Pro3 R2.0               | [73c6829ffb](https://linux-hardware.org/?probe=73c6829ffb) | Nov 27, 2019 |
| HP            | 18EA                        | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| ASRock        | A320M-HDV R3.0              | [d3d79c2a8d](https://linux-hardware.org/?probe=d3d79c2a8d) | Sep 16, 2019 |
| Gigabyte      | A320M-H-CF                  | [a35aea421b](https://linux-hardware.org/?probe=a35aea421b) | Sep 09, 2019 |
| Intel         | DX58SO AAE29331-501         | [349ef8982a](https://linux-hardware.org/?probe=349ef8982a) | Sep 09, 2019 |
| Gigabyte      | A320M-H-CF                  | [59782a89ea](https://linux-hardware.org/?probe=59782a89ea) | Sep 06, 2019 |
| Gigabyte      | A320M-H-CF                  | [b4ef0f5499](https://linux-hardware.org/?probe=b4ef0f5499) | Sep 05, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | [be3a07802c](https://linux-hardware.org/?probe=be3a07802c) | Aug 13, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | [9cdd546881](https://linux-hardware.org/?probe=9cdd546881) | Jul 29, 2019 |
| ASRock        | A300M-STX                   | [edf300f175](https://linux-hardware.org/?probe=edf300f175) | Jul 29, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | [aad0551e27](https://linux-hardware.org/?probe=aad0551e27) | Jul 25, 2019 |
| ASUSTek       | E35M1-M                     | [1b78cc518f](https://linux-hardware.org/?probe=1b78cc518f) | Jul 08, 2019 |
| ASUSTek       | E35M1-M                     | [1f5e6b026b](https://linux-hardware.org/?probe=1f5e6b026b) | Jun 23, 2019 |
| ASUSTek       | PRIME A320M-K               | [f8c4365b6c](https://linux-hardware.org/?probe=f8c4365b6c) | Jun 07, 2019 |
| ASUSTek       | PRIME A320M-K               | [3968b06d9c](https://linux-hardware.org/?probe=3968b06d9c) | Jun 07, 2019 |
| HP            | 83ED                        | [532b72754e](https://linux-hardware.org/?probe=532b72754e) | May 06, 2019 |
| Gigabyte      | Z77P-D3                     | [e7259783d1](https://linux-hardware.org/?probe=e7259783d1) | Apr 13, 2019 |
| Pegatron      | 2A99                        | [196712630c](https://linux-hardware.org/?probe=196712630c) | Feb 26, 2019 |
| ASUSTek       | B150M-C                     | [88898f6797](https://linux-hardware.org/?probe=88898f6797) | Feb 10, 2019 |
| ECS           | A770M-A                     | [feacfccf11](https://linux-hardware.org/?probe=feacfccf11) | Feb 05, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | [bf1298d356](https://linux-hardware.org/?probe=bf1298d356) | Jan 29, 2019 |
| ABIT          | IP35-E                      | [87b22d6a66](https://linux-hardware.org/?probe=87b22d6a66) | Jan 26, 2019 |
| Gigabyte      | AX370-Gaming K7             | [bc26ed35a0](https://linux-hardware.org/?probe=bc26ed35a0) | Dec 08, 2018 |
| Unknown       | Grantsdale                  | [65da6a461b](https://linux-hardware.org/?probe=65da6a461b) | Nov 21, 2018 |
| Pegatron      | 2AB6                        | [00a8407210](https://linux-hardware.org/?probe=00a8407210) | Oct 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 20       | 9.3%    |
| Ubuntu 18.04                 | 14       | 6.51%   |
| Ubuntu 22.04                 | 9        | 4.19%   |
| Debian 11                    | 7        | 3.26%   |
| OpenMandriva 4.3             | 6        | 2.79%   |
| Linux Mint 20.3              | 6        | 2.79%   |
| Linux Mint 20.2              | 6        | 2.79%   |
| ArcoLinux Rolling            | 6        | 2.79%   |
| Ubuntu 18.10                 | 5        | 2.33%   |
| openSUSE Tumbleweed-XXXXXXXX | 5        | 2.33%   |
| Manjaro                      | 5        | 2.33%   |
| Zorin 16                     | 4        | 1.86%   |
| Ubuntu 24.04                 | 4        | 1.86%   |
| OpenMandriva 23.08           | 4        | 1.86%   |
| Fedora 38                    | 4        | 1.86%   |
| Debian 10                    | 4        | 1.86%   |
| Ubuntu MATE 22.04            | 3        | 1.4%    |
| Ubuntu 19.10                 | 3        | 1.4%    |
| Pop!_OS 21.10                | 3        | 1.4%    |
| OpenMandriva 4.2             | 3        | 1.4%    |
| Fedora 39                    | 3        | 1.4%    |
| Fedora 31                    | 3        | 1.4%    |
| EndeavourOS Rolling          | 3        | 1.4%    |
| Debian 12                    | 3        | 1.4%    |
| Ubuntu 24.10                 | 2        | 0.93%   |
| Ubuntu 21.04                 | 2        | 0.93%   |
| Pop!_OS 20.10                | 2        | 0.93%   |
| openSUSE Leap-15.2           | 2        | 0.93%   |
| OpenMandriva 4.50            | 2        | 0.93%   |
| OpenMandriva 24.07           | 2        | 0.93%   |
| OpenMandriva 23.11           | 2        | 0.93%   |
| OpenMandriva 23.03           | 2        | 0.93%   |
| LMDE 6                       | 2        | 0.93%   |
| Linux Mint 21.3              | 2        | 0.93%   |
| Linux Mint 21.1              | 2        | 0.93%   |
| Linux Mint 20                | 2        | 0.93%   |
| KDE neon 20.04               | 2        | 0.93%   |
| Debian                       | 2        | 0.93%   |
| Arch Rolling                 | 2        | 0.93%   |
| Zorin 15                     | 1        | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 62       | 30.85%  |
| OpenMandriva  | 21       | 10.45%  |
| Linux Mint    | 21       | 10.45%  |
| Debian        | 14       | 6.97%   |
| Fedora        | 12       | 5.97%   |
| Manjaro       | 10       | 4.98%   |
| Pop!_OS       | 9        | 4.48%   |
| openSUSE      | 7        | 3.48%   |
| ArcoLinux     | 6        | 2.99%   |
| Zorin         | 5        | 2.49%   |
| Ubuntu MATE   | 3        | 1.49%   |
| Ubuntu Budgie | 3        | 1.49%   |
| LMDE          | 3        | 1.49%   |
| KDE neon      | 3        | 1.49%   |
| EndeavourOS   | 3        | 1.49%   |
| Arch          | 3        | 1.49%   |
| Xubuntu       | 2        | 1%      |
| Kubuntu       | 2        | 1%      |
| Gentoo        | 2        | 1%      |
| Ubuntu Unity  | 1        | 0.5%    |
| ROSA          | 1        | 0.5%    |
| Nobara        | 1        | 0.5%    |
| MX            | 1        | 0.5%    |
| Lubuntu       | 1        | 0.5%    |
| LinuxFX       | 1        | 0.5%    |
| Endless       | 1        | 0.5%    |
| Elementary    | 1        | 0.5%    |
| Dts-distro    | 1        | 0.5%    |
| Clear Linux   | 1        | 0.5%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 6        | 2.5%    |
| 6.4.11-desktop-1omv2390  | 4        | 1.67%   |
| 5.4.0-58-generic         | 4        | 1.67%   |
| 6.2.9-300.fc38.x86_64    | 3        | 1.25%   |
| 5.4.0-91-generic         | 3        | 1.25%   |
| 5.3.0-26-generic         | 3        | 1.25%   |
| 5.10.14-desktop-1omv4002 | 3        | 1.25%   |
| 5.0.0-27-generic         | 3        | 1.25%   |
| 6.6.2-desktop-1omv2390   | 2        | 0.83%   |
| 6.2.6-desktop-1omv2390   | 2        | 0.83%   |
| 5.8.0-48-generic         | 2        | 0.83%   |
| 5.4.0-48-generic         | 2        | 0.83%   |
| 5.4.0-42-generic         | 2        | 0.83%   |
| 5.4.0-26-generic         | 2        | 0.83%   |
| 5.4.0-100-generic        | 2        | 0.83%   |
| 5.3.0-42-generic         | 2        | 0.83%   |
| 5.3.0-28-generic         | 2        | 0.83%   |
| 5.15.0-52-generic        | 2        | 0.83%   |
| 5.15.0-48-generic        | 2        | 0.83%   |
| 5.15.0-105-generic       | 2        | 0.83%   |
| 5.13.0-40-generic        | 2        | 0.83%   |
| 5.12.4-desktop-1omv4050  | 2        | 0.83%   |
| 5.11.0-41-generic        | 2        | 0.83%   |
| 5.11.0-38-generic        | 2        | 0.83%   |
| 5.11.0-37-generic        | 2        | 0.83%   |
| 5.10.0-13-amd64          | 2        | 0.83%   |
| 4.19.0-14-amd64          | 2        | 0.83%   |
| 4.18.0-10-generic        | 2        | 0.83%   |
| 4.15.0-45-generic        | 2        | 0.83%   |
| 4.15.0-20-generic        | 2        | 0.83%   |
| 6.8.8-1-default          | 1        | 0.42%   |
| 6.8.7-zen1-1-zen         | 1        | 0.42%   |
| 6.8.12-4-pve             | 1        | 0.42%   |
| 6.8.1-zen1-1-zen         | 1        | 0.42%   |
| 6.8.0-51-generic         | 1        | 0.42%   |
| 6.8.0-48-generic         | 1        | 0.42%   |
| 6.8.0-47-generic         | 1        | 0.42%   |
| 6.8.0-45-generic         | 1        | 0.42%   |
| 6.8.0-38-generic         | 1        | 0.42%   |
| 6.7.4-arch1-1            | 1        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 33       | 14.8%   |
| 5.15.0  | 13       | 5.83%   |
| 5.11.0  | 12       | 5.38%   |
| 5.3.0   | 11       | 4.93%   |
| 4.15.0  | 10       | 4.48%   |
| 5.10.0  | 8        | 3.59%   |
| 4.18.0  | 8        | 3.59%   |
| 5.16.7  | 6        | 2.69%   |
| 5.13.0  | 6        | 2.69%   |
| 5.8.0   | 5        | 2.24%   |
| 6.8.0   | 4        | 1.79%   |
| 6.4.11  | 4        | 1.79%   |
| 5.0.0   | 4        | 1.79%   |
| 6.5.0   | 3        | 1.35%   |
| 6.2.9   | 3        | 1.35%   |
| 6.1.0   | 3        | 1.35%   |
| 5.12.4  | 3        | 1.35%   |
| 5.10.14 | 3        | 1.35%   |
| 4.19.0  | 3        | 1.35%   |
| 6.6.2   | 2        | 0.9%    |
| 6.5.4   | 2        | 0.9%    |
| 6.2.6   | 2        | 0.9%    |
| 6.11.0  | 2        | 0.9%    |
| 5.3.18  | 2        | 0.9%    |
| 5.19.0  | 2        | 0.9%    |
| 5.16.11 | 2        | 0.9%    |
| 6.8.8   | 1        | 0.45%   |
| 6.8.7   | 1        | 0.45%   |
| 6.8.12  | 1        | 0.45%   |
| 6.8.1   | 1        | 0.45%   |
| 6.7.4   | 1        | 0.45%   |
| 6.7.11  | 1        | 0.45%   |
| 6.7.10  | 1        | 0.45%   |
| 6.6.7   | 1        | 0.45%   |
| 6.6.19  | 1        | 0.45%   |
| 6.6.13  | 1        | 0.45%   |
| 6.6.11  | 1        | 0.45%   |
| 6.6.0   | 1        | 0.45%   |
| 6.5.9   | 1        | 0.45%   |
| 6.5.13  | 1        | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 16.74%  |
| 5.15    | 18       | 8.14%   |
| 5.10    | 15       | 6.79%   |
| 5.3     | 14       | 6.33%   |
| 5.11    | 13       | 5.88%   |
| 4.15    | 10       | 4.52%   |
| 6.8     | 8        | 3.62%   |
| 5.16    | 8        | 3.62%   |
| 4.18    | 8        | 3.62%   |
| 6.6     | 7        | 3.17%   |
| 6.5     | 7        | 3.17%   |
| 6.2     | 7        | 3.17%   |
| 5.13    | 6        | 2.71%   |
| 6.4     | 5        | 2.26%   |
| 6.10    | 5        | 2.26%   |
| 6.1     | 5        | 2.26%   |
| 5.8     | 5        | 2.26%   |
| 5.19    | 5        | 2.26%   |
| 6.11    | 4        | 1.81%   |
| 5.0     | 4        | 1.81%   |
| 6.7     | 3        | 1.36%   |
| 6.12    | 3        | 1.36%   |
| 6.0     | 3        | 1.36%   |
| 5.18    | 3        | 1.36%   |
| 5.12    | 3        | 1.36%   |
| 4.19    | 3        | 1.36%   |
| 6.3     | 2        | 0.9%    |
| 5.7     | 2        | 0.9%    |
| 5.17    | 2        | 0.9%    |
| 5.14    | 2        | 0.9%    |
| 5.9     | 1        | 0.45%   |
| 5.6     | 1        | 0.45%   |
| 4.14    | 1        | 0.45%   |
| 4.13    | 1        | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 193      | 98.97%  |
| i686   | 2        | 1.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 73       | 36.14%  |
| KDE5       | 44       | 21.78%  |
| Unknown    | 29       | 14.36%  |
| X-Cinnamon | 17       | 8.42%   |
| XFCE       | 9        | 4.46%   |
| MATE       | 5        | 2.48%   |
| KDE        | 5        | 2.48%   |
| Cinnamon   | 5        | 2.48%   |
| Budgie     | 3        | 1.49%   |
| LXQt       | 2        | 0.99%   |
| KDE6       | 2        | 0.99%   |
| Unity      | 1        | 0.5%    |
| ubuntu     | 1        | 0.5%    |
| Pantheon   | 1        | 0.5%    |
| openbox    | 1        | 0.5%    |
| LXDE       | 1        | 0.5%    |
| i3         | 1        | 0.5%    |
| DWM        | 1        | 0.5%    |
| dk         | 1        | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 151      | 74.75%  |
| Wayland | 32       | 15.84%  |
| Unknown | 12       | 5.94%   |
| Tty     | 7        | 3.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 99       | 49.01%  |
| SDDM    | 41       | 20.3%   |
| LightDM | 23       | 11.39%  |
| GDM3    | 22       | 10.89%  |
| GDM     | 13       | 6.44%   |
| TDM     | 4        | 1.98%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 116      | 57.71%  |
| hr_HR   | 45       | 22.39%  |
| Unknown | 26       | 12.94%  |
| en_GB   | 10       | 4.98%   |
| C       | 3        | 1.49%   |
| nb_NO   | 1        | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 102      | 51.78%  |
| EFI  | 95       | 48.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 145      | 71.43%  |
| Btrfs   | 24       | 11.82%  |
| Overlay | 19       | 9.36%   |
| Tmpfs   | 6        | 2.96%   |
| Zfs     | 4        | 1.97%   |
| Unknown | 4        | 1.97%   |
| Xfs     | 1        | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 100      | 50.25%  |
| GPT     | 78       | 39.2%   |
| MBR     | 21       | 10.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 162      | 80.2%   |
| Yes       | 40       | 19.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 62%     |
| Yes       | 76       | 38%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 47       | 24.1%   |
| ASUSTek Computer    | 42       | 21.54%  |
| Gigabyte Technology | 38       | 19.49%  |
| MSI                 | 17       | 8.72%   |
| Hewlett-Packard     | 17       | 8.72%   |
| Intel               | 6        | 3.08%   |
| Dell                | 6        | 3.08%   |
| Pegatron            | 5        | 2.56%   |
| Lenovo              | 4        | 2.05%   |
| ECS                 | 3        | 1.54%   |
| WinFast             | 1        | 0.51%   |
| MAXSUN              | 1        | 0.51%   |
| HPE                 | 1        | 0.51%   |
| Fujitsu Siemens     | 1        | 0.51%   |
| Foxconn             | 1        | 0.51%   |
| EMC                 | 1        | 0.51%   |
| eMachines           | 1        | 0.51%   |
| Acer                | 1        | 0.51%   |
| ABIT                | 1        | 0.51%   |
| Unknown             | 1        | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 6        | 3.08%   |
| ASRock B450M-HDV R4.0                  | 4        | 2.05%   |
| ASUS PRIME A320M-K                     | 3        | 1.54%   |
| MSI MS-7C02                            | 2        | 1.03%   |
| MSI MS-7850                            | 2        | 1.03%   |
| Intel DH61CR AAG14064-204              | 2        | 1.03%   |
| HP Compaq 8200 Elite SFF PC            | 2        | 1.03%   |
| Gigabyte B550M DS3H                    | 2        | 1.03%   |
| Gigabyte B450 AORUS ELITE              | 2        | 1.03%   |
| Gigabyte A320M-S2H                     | 2        | 1.03%   |
| ASUS TUF Gaming X570-PLUS              | 2        | 1.03%   |
| ASUS P8H77-V LE                        | 2        | 1.03%   |
| ASUS M5A78L LE                         | 2        | 1.03%   |
| ASRock H61M-DGS                        | 2        | 1.03%   |
| ASRock B560 Steel Legend               | 2        | 1.03%   |
| WinFast N570SM2AA                      | 1        | 0.51%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.51%   |
| Pegatron HPE-520ad                     | 1        | 0.51%   |
| Pegatron G5261de                       | 1        | 0.51%   |
| Pegatron Compaq dx2400 Microtower PC   | 1        | 0.51%   |
| Pegatron 27-1001eu                     | 1        | 0.51%   |
| MSI MS-7E06                            | 1        | 0.51%   |
| MSI MS-7D77                            | 1        | 0.51%   |
| MSI MS-7D40                            | 1        | 0.51%   |
| MSI MS-7D25                            | 1        | 0.51%   |
| MSI MS-7C84                            | 1        | 0.51%   |
| MSI MS-7B98                            | 1        | 0.51%   |
| MSI MS-7B84                            | 1        | 0.51%   |
| MSI MS-7B07                            | 1        | 0.51%   |
| MSI MS-7817                            | 1        | 0.51%   |
| MSI MS-7681                            | 1        | 0.51%   |
| MSI MS-7586                            | 1        | 0.51%   |
| MSI MS-7360                            | 1        | 0.51%   |
| MSI 0A90                               | 1        | 0.51%   |
| MAXSUN MS-TZZ B560M                    | 1        | 0.51%   |
| Lenovo ThinkStation P310 30AT0029GE    | 1        | 0.51%   |
| Lenovo ThinkCentre M720s 10SUS1FQ00    | 1        | 0.51%   |
| Lenovo ThinkCentre A58 77057FG         | 1        | 0.51%   |
| Lenovo S510                            | 1        | 0.51%   |
| Intel H61M-S2PV                        | 1        | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 9        | 4.62%   |
| ASUS TUF           | 6        | 3.08%   |
| ASUS All           | 6        | 3.08%   |
| HP Compaq          | 5        | 2.56%   |
| Gigabyte B450      | 4        | 2.05%   |
| ASRock B450M-HDV   | 4        | 2.05%   |
| HP ProDesk         | 3        | 1.54%   |
| HP EliteDesk       | 3        | 1.54%   |
| Dell Vostro        | 3        | 1.54%   |
| ASUS ROG           | 3        | 1.54%   |
| ASRock H97         | 3        | 1.54%   |
| MSI MS-7C02        | 2        | 1.03%   |
| MSI MS-7850        | 2        | 1.03%   |
| Lenovo ThinkCentre | 2        | 1.03%   |
| Intel DH61CR       | 2        | 1.03%   |
| Gigabyte Z790      | 2        | 1.03%   |
| Gigabyte Z390      | 2        | 1.03%   |
| Gigabyte B550M     | 2        | 1.03%   |
| Gigabyte A320M-S2H | 2        | 1.03%   |
| Dell OptiPlex      | 2        | 1.03%   |
| ASUS P8H77-V       | 2        | 1.03%   |
| ASUS M5A78L        | 2        | 1.03%   |
| ASRock H61M-DGS    | 2        | 1.03%   |
| ASRock B560        | 2        | 1.03%   |
| ASRock B550M       | 2        | 1.03%   |
| ASRock A320M-HDV   | 2        | 1.03%   |
| WinFast N570SM2AA  | 1        | 0.51%   |
| Pegatron Pro       | 1        | 0.51%   |
| Pegatron HPE-520ad | 1        | 0.51%   |
| Pegatron G5261de   | 1        | 0.51%   |
| Pegatron Compaq    | 1        | 0.51%   |
| Pegatron 27-1001eu | 1        | 0.51%   |
| MSI MS-7E06        | 1        | 0.51%   |
| MSI MS-7D77        | 1        | 0.51%   |
| MSI MS-7D40        | 1        | 0.51%   |
| MSI MS-7D25        | 1        | 0.51%   |
| MSI MS-7C84        | 1        | 0.51%   |
| MSI MS-7B98        | 1        | 0.51%   |
| MSI MS-7B84        | 1        | 0.51%   |
| MSI MS-7B07        | 1        | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 19       | 9.74%   |
| 2013 | 19       | 9.74%   |
| 2020 | 16       | 8.21%   |
| 2012 | 16       | 8.21%   |
| 2011 | 16       | 8.21%   |
| 2021 | 13       | 6.67%   |
| 2017 | 13       | 6.67%   |
| 2014 | 11       | 5.64%   |
| 2009 | 11       | 5.64%   |
| 2022 | 10       | 5.13%   |
| 2019 | 10       | 5.13%   |
| 2023 | 7        | 3.59%   |
| 2010 | 7        | 3.59%   |
| 2008 | 7        | 3.59%   |
| 2015 | 6        | 3.08%   |
| 2007 | 6        | 3.08%   |
| 2016 | 3        | 1.54%   |
| 2006 | 2        | 1.03%   |
| 2005 | 2        | 1.03%   |
| 2024 | 1        | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 195      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 188      | 95.92%  |
| Enabled  | 8        | 4.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 195      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 49       | 24.62%  |
| 8.01-16.0   | 46       | 23.12%  |
| 32.01-64.0  | 30       | 15.08%  |
| 4.01-8.0    | 28       | 14.07%  |
| 3.01-4.0    | 20       | 10.05%  |
| 64.01-256.0 | 9        | 4.52%   |
| 24.01-32.0  | 8        | 4.02%   |
| 1.01-2.0    | 8        | 4.02%   |
| 2.01-3.0    | 1        | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 73       | 33.49%  |
| 2.01-3.0   | 57       | 26.15%  |
| 4.01-8.0   | 35       | 16.06%  |
| 3.01-4.0   | 25       | 11.47%  |
| 8.01-16.0  | 12       | 5.5%    |
| 0.51-1.0   | 10       | 4.59%   |
| 16.01-24.0 | 3        | 1.38%   |
| 0.01-0.5   | 2        | 0.92%   |
| 24.01-32.0 | 1        | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 71       | 34.63%  |
| 2      | 60       | 29.27%  |
| 3      | 36       | 17.56%  |
| 4      | 16       | 7.8%    |
| 5      | 13       | 6.34%   |
| 6      | 3        | 1.46%   |
| 0      | 3        | 1.46%   |
| 7      | 2        | 0.98%   |
| 8      | 1        | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 57.36%  |
| Yes       | 84       | 42.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 192      | 98.46%  |
| No        | 3        | 1.54%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 125      | 63.13%  |
| Yes       | 73       | 36.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 74.62%  |
| Yes       | 50       | 25.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Croatia | 195      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Zagreb               | 102      | 46.79%  |
| Split                | 16       | 7.34%   |
| Rijeka               | 15       | 6.88%   |
| Osijek               | 6        | 2.75%   |
| Varaždin            | 5        | 2.29%   |
| Velika Gorica        | 4        | 1.83%   |
| Pula                 | 4        | 1.83%   |
| Zaprešić           | 3        | 1.38%   |
| Samobor              | 3        | 1.38%   |
| Koprivnica           | 3        | 1.38%   |
| Bjelovar             | 3        | 1.38%   |
| Zadar                | 2        | 0.92%   |
| Virovitica           | 2        | 0.92%   |
| Slatina              | 2        | 0.92%   |
| Sisak                | 2        | 0.92%   |
| Pitomaca             | 2        | 0.92%   |
| Ivanja Reka          | 2        | 0.92%   |
| GJurgevac            | 2        | 0.92%   |
| Červar-Porat        | 2        | 0.92%   |
| Čakovec             | 2        | 0.92%   |
| Visnjevac            | 1        | 0.46%   |
| Sveti Petar Orehovec | 1        | 0.46%   |
| Supetar              | 1        | 0.46%   |
| Stari Perkovci       | 1        | 0.46%   |
| Slavonski Brod       | 1        | 0.46%   |
| Skrad                | 1        | 0.46%   |
| Sesvete              | 1        | 0.46%   |
| Rogotin              | 1        | 0.46%   |
| Raslina              | 1        | 0.46%   |
| Prelog               | 1        | 0.46%   |
| Postira              | 1        | 0.46%   |
| Novi Marof           | 1        | 0.46%   |
| Nerezine             | 1        | 0.46%   |
| Matulji              | 1        | 0.46%   |
| Mali Lošinj         | 1        | 0.46%   |
| Mahicno              | 1        | 0.46%   |
| Lovran               | 1        | 0.46%   |
| Labin                | 1        | 0.46%   |
| Kućan Marof         | 1        | 0.46%   |
| Krizevci             | 1        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 83       | 143    | 22.49%  |
| Samsung Electronics         | 48       | 77     | 13.01%  |
| Kingston                    | 42       | 70     | 11.38%  |
| Seagate                     | 40       | 63     | 10.84%  |
| Toshiba                     | 29       | 48     | 7.86%   |
| Crucial                     | 24       | 36     | 6.5%    |
| A-DATA Technology           | 13       | 17     | 3.52%   |
| Intel                       | 12       | 14     | 3.25%   |
| Sandisk                     | 8        | 11     | 2.17%   |
| Patriot                     | 6        | 9      | 1.63%   |
| Hitachi                     | 6        | 9      | 1.63%   |
| Kingston Technology Company | 5        | 8      | 1.36%   |
| SPCC                        | 4        | 4      | 1.08%   |
| Silicon Motion              | 4        | 5      | 1.08%   |
| Transcend                   | 3        | 7      | 0.81%   |
| Phison                      | 3        | 3      | 0.81%   |
| Phison Electronics          | 2        | 3      | 0.54%   |
| OCZ                         | 2        | 3      | 0.54%   |
| Micron/Crucial Technology   | 2        | 2      | 0.54%   |
| Micron Technology           | 2        | 2      | 0.54%   |
| Maxtor                      | 2        | 2      | 0.54%   |
| KingSpec                    | 2        | 2      | 0.54%   |
| HPE                         | 2        | 4      | 0.54%   |
| Gigabyte Technology         | 2        | 2      | 0.54%   |
| External                    | 2        | 2      | 0.54%   |
| Corsair                     | 2        | 2      | 0.54%   |
| XPG                         | 1        | 3      | 0.27%   |
| Unknown                     | 1        | 1      | 0.27%   |
| TO Exter                    | 1        | 1      | 0.27%   |
| Realtek Semiconductor       | 1        | 1      | 0.27%   |
| PNY                         | 1        | 1      | 0.27%   |
| Netac                       | 1        | 1      | 0.27%   |
| Mushkin                     | 1        | 2      | 0.27%   |
| Min Yi U                    | 1        | 1      | 0.27%   |
| KIOXIA                      | 1        | 1      | 0.27%   |
| Kingmax                     | 1        | 1      | 0.27%   |
| INNOVATION IT               | 1        | 1      | 0.27%   |
| Hikvision                   | 1        | 1      | 0.27%   |
| HGST HTS                    | 1        | 1      | 0.27%   |
| HGST                        | 1        | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD                     | 6        | 1.41%   |
| Kingston SA400S37240G 240GB SSD                     | 6        | 1.41%   |
| Kingston SA400S37120G 120GB SSD                     | 6        | 1.41%   |
| Toshiba HDWD130 3TB                                 | 5        | 1.17%   |
| Kingston SV300S37A120G 120GB SSD                    | 5        | 1.17%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4        | 0.94%   |
| Toshiba HDWD110 1TB                                 | 4        | 0.94%   |
| Toshiba DT01ACA100 1TB                              | 4        | 0.94%   |
| Seagate ST1000DM010-2EP102 1TB                      | 4        | 0.94%   |
| Samsung SSD 850 EVO 250GB                           | 4        | 0.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 4        | 0.94%   |
| Intel SSDSC2BW120A4 120GB                           | 4        | 0.94%   |
| WDC WD5000AAKX-001CA0 500GB                         | 3        | 0.7%    |
| WDC WD30EFRX-68EUZN0 3TB                            | 3        | 0.7%    |
| WDC WD10EZEX-08M2NA0 1TB                            | 3        | 0.7%    |
| Toshiba HDWD120 2TB                                 | 3        | 0.7%    |
| Toshiba DT01ACA300 3TB                              | 3        | 0.7%    |
| Seagate ST3250410AS 250GB                           | 3        | 0.7%    |
| Seagate ST31500341AS 1TB                            | 3        | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 0.7%    |
| SanDisk SDSSDA240G 240GB                            | 3        | 0.7%    |
| Samsung SSD 970 EVO Plus 1TB                        | 3        | 0.7%    |
| Samsung SSD 860 EVO 500GB                           | 3        | 0.7%    |
| Samsung HD103SI 1TB                                 | 3        | 0.7%    |
| Patriot Burst 240GB SSD                             | 3        | 0.7%    |
| Kingston Company SNV2S1000G 1TB                     | 3        | 0.7%    |
| Kingston SKC3000D2048G 2TB                          | 3        | 0.7%    |
| Crucial CT2000P3PSSD8 2TB                           | 3        | 0.7%    |
| Crucial CT120BX500SSD1 120GB                        | 3        | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2        | 0.47%   |
| WDC WD6400AAKS-22A7B0 640GB                         | 2        | 0.47%   |
| WDC WD5003ABYX-88 LEN 500GB                         | 2        | 0.47%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 2        | 0.47%   |
| WDC WD5000AAKX-22ERMA0 500GB                        | 2        | 0.47%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 2        | 0.47%   |
| WDC WD3200AAKS-00L9A0 320GB                         | 2        | 0.47%   |
| WDC WD30EZRX-00AZ6B0 3TB                            | 2        | 0.47%   |
| WDC WD2500AVJS-63WDA0 250GB                         | 2        | 0.47%   |
| WDC WD20PURX-64P6ZY0 2TB                            | 2        | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 2        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 80       | 133    | 46.78%  |
| Seagate             | 38       | 60     | 22.22%  |
| Toshiba             | 28       | 47     | 16.37%  |
| Samsung Electronics | 8        | 10     | 4.68%   |
| Hitachi             | 6        | 9      | 3.51%   |
| Maxtor              | 2        | 2      | 1.17%   |
| External            | 2        | 2      | 1.17%   |
| Unknown             | 1        | 1      | 0.58%   |
| TO Exter            | 1        | 1      | 0.58%   |
| Min Yi U            | 1        | 1      | 0.58%   |
| HPE                 | 1        | 2      | 0.58%   |
| HGST HTS            | 1        | 1      | 0.58%   |
| HGST                | 1        | 1      | 0.58%   |
| ASMedia             | 1        | 1      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 35       | 50     | 27.34%  |
| Samsung Electronics | 21       | 34     | 16.41%  |
| Crucial             | 18       | 24     | 14.06%  |
| A-DATA Technology   | 11       | 14     | 8.59%   |
| Intel               | 10       | 12     | 7.81%   |
| Patriot             | 5        | 8      | 3.91%   |
| SPCC                | 4        | 4      | 3.13%   |
| WDC                 | 3        | 3      | 2.34%   |
| SanDisk             | 3        | 5      | 2.34%   |
| Transcend           | 2        | 2      | 1.56%   |
| OCZ                 | 2        | 3      | 1.56%   |
| KingSpec            | 2        | 2      | 1.56%   |
| Gigabyte Technology | 2        | 2      | 1.56%   |
| Seagate             | 1        | 1      | 0.78%   |
| PNY                 | 1        | 1      | 0.78%   |
| Netac               | 1        | 1      | 0.78%   |
| Mushkin             | 1        | 2      | 0.78%   |
| Kingmax             | 1        | 1      | 0.78%   |
| INNOVATION IT       | 1        | 1      | 0.78%   |
| GOODRAM             | 1        | 1      | 0.78%   |
| Corsair             | 1        | 1      | 0.78%   |
| China               | 1        | 2      | 0.78%   |
| AMD                 | 1        | 2      | 0.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 132      | 271    | 43.42%  |
| SSD     | 104      | 176    | 34.21%  |
| NVMe    | 66       | 121    | 21.71%  |
| Unknown | 2        | 4      | 0.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 169      | 439    | 69.26%  |
| NVMe | 66       | 121    | 27.05%  |
| SAS  | 9        | 12     | 3.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 128      | 240    | 50.39%  |
| 0.51-1.0   | 66       | 105    | 25.98%  |
| 1.01-2.0   | 27       | 43     | 10.63%  |
| 2.01-3.0   | 16       | 33     | 6.3%    |
| 3.01-4.0   | 14       | 22     | 5.51%   |
| 4.01-10.0  | 3        | 4      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 48       | 22.64%  |
| 251-500        | 33       | 15.57%  |
| 1001-2000      | 33       | 15.57%  |
| 501-1000       | 30       | 14.15%  |
| More than 3000 | 23       | 10.85%  |
| 1-20           | 16       | 7.55%   |
| 51-100         | 11       | 5.19%   |
| 2001-3000      | 8        | 3.77%   |
| Unknown        | 8        | 3.77%   |
| 21-50          | 2        | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 86       | 39.09%  |
| 21-50          | 26       | 11.82%  |
| 501-1000       | 22       | 10%     |
| 251-500        | 18       | 8.18%   |
| 101-250        | 16       | 7.27%   |
| 1001-2000      | 16       | 7.27%   |
| 51-100         | 13       | 5.91%   |
| Unknown        | 8        | 3.64%   |
| More than 3000 | 7        | 3.18%   |
| 2001-3000      | 7        | 3.18%   |
| 0              | 1        | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                    | Desktops | Drives | Percent |
|----------------------------------------------------------|----------|--------|---------|
| Seagate ST31500341AS 1TB                                 | 2        | 3      | 6.9%    |
| WDC WD6400AAKS-07A7B0 640GB                              | 1        | 1      | 3.45%   |
| WDC WD5003ABYX-88 LEN 500GB                              | 1        | 1      | 3.45%   |
| WDC WD5000AAKX-221CA1 500GB                              | 1        | 1      | 3.45%   |
| WDC WD3200BEKT-08PVMT1 320GB                             | 1        | 1      | 3.45%   |
| WDC WD3200AAKS-00L9A0 320GB                              | 1        | 1      | 3.45%   |
| WDC WD2500AAKX-75U6AA0 250GB                             | 1        | 1      | 3.45%   |
| WDC WD20PURX-64P6ZY0 2TB                                 | 1        | 1      | 3.45%   |
| WDC WD10EZRZ-00HTKB0 1TB                                 | 1        | 1      | 3.45%   |
| WDC WD10EZEX-00MFCA0 1TB                                 | 1        | 1      | 3.45%   |
| Transcend TS480GSSD220S 480GB                            | 1        | 1      | 3.45%   |
| Toshiba DT01ACA100 1TB                                   | 1        | 1      | 3.45%   |
| SPCC Solid State Disk 128GB                              | 1        | 1      | 3.45%   |
| Seagate ST3250410AS 250GB                                | 1        | 2      | 3.45%   |
| Seagate ST2000DM008-2FR102 2TB                           | 1        | 1      | 3.45%   |
| Seagate ST2000DM001-1ER164 2TB                           | 1        | 1      | 3.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                       | 1        | 3      | 3.45%   |
| Seagate ST1000DX002-2DV162 1TB                           | 1        | 1      | 3.45%   |
| SanDisk SDSSDA240G 240GB                                 | 1        | 1      | 3.45%   |
| Samsung Electronics SSD 970 EVO Plus 1TB S6P7NG3R755349M | 1        | 1      | 3.45%   |
| Kingston SKC2500M8500G 500GB                             | 1        | 1      | 3.45%   |
| Kingston SHFS37A120G 120GB SSD                           | 1        | 1      | 3.45%   |
| Intel SSDSC2BW180A4 180GB                                | 1        | 1      | 3.45%   |
| Intel SSDSC2BW120A4 120GB                                | 1        | 1      | 3.45%   |
| Hitachi HDS723020BLA642 2TB                              | 1        | 1      | 3.45%   |
| Crucial CT525MX300SSD1 528GB                             | 1        | 1      | 3.45%   |
| Crucial CT120BX500SSD1 120GB                             | 1        | 2      | 3.45%   |
| A-DATA Technology SP900 64GB SSD                         | 1        | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 9      | 32.14%  |
| Seagate             | 6        | 11     | 21.43%  |
| Kingston            | 2        | 2      | 7.14%   |
| Intel               | 2        | 2      | 7.14%   |
| Crucial             | 2        | 3      | 7.14%   |
| Transcend           | 1        | 1      | 3.57%   |
| Toshiba             | 1        | 1      | 3.57%   |
| SPCC                | 1        | 1      | 3.57%   |
| SanDisk             | 1        | 1      | 3.57%   |
| Samsung Electronics | 1        | 1      | 3.57%   |
| Hitachi             | 1        | 1      | 3.57%   |
| A-DATA Technology   | 1        | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 9        | 9      | 52.94%  |
| Seagate | 6        | 11     | 35.29%  |
| Toshiba | 1        | 1      | 5.88%   |
| Hitachi | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 22     | 59.26%  |
| SSD  | 9        | 10     | 33.33%  |
| NVMe | 2        | 2      | 7.41%   |

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
| Detected | 112      | 317    | 51.85%  |
| Works    | 80       | 221    | 37.04%  |
| Malfunc  | 24       | 34     | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 120      | 41.52%  |
| AMD                          | 68       | 23.53%  |
| Samsung Electronics          | 24       | 8.3%    |
| Kingston Technology Company  | 17       | 5.88%   |
| Micron/Crucial Technology    | 8        | 2.77%   |
| Phison Electronics           | 7        | 2.42%   |
| SanDisk                      | 6        | 2.08%   |
| ASMedia Technology           | 6        | 2.08%   |
| JMicron Technology           | 5        | 1.73%   |
| Silicon Motion               | 4        | 1.38%   |
| Nvidia                       | 4        | 1.38%   |
| Marvell Technology Group     | 4        | 1.38%   |
| ADATA Technology             | 4        | 1.38%   |
| Micron Technology            | 2        | 0.69%   |
| Adaptec                      | 2        | 0.69%   |
| VIA Technologies             | 1        | 0.35%   |
| Transcend                    | 1        | 0.35%   |
| Toshiba America Info Systems | 1        | 0.35%   |
| Silicon Image                | 1        | 0.35%   |
| Realtek Semiconductor        | 1        | 0.35%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.35%   |
| KIOXIA                       | 1        | 0.35%   |
| Broadcom / LSI               | 1        | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 31       | 8.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17       | 4.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 3.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 3%      |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 3%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 2.72%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 10       | 2.72%   |
| AMD 600 Series Chipset SATA Controller                                                  | 9        | 2.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 2.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 8        | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 2.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.91%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 1.91%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 1.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 1.63%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 1.36%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                    | 5        | 1.36%   |
| Intel SATA Controller [RAID Mode]                                                       | 5        | 1.36%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 5        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.36%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 5        | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 1.09%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 4        | 1.09%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 4        | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.09%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.09%   |
| AMD FCH IDE Controller                                                                  | 4        | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 0.82%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 3        | 0.82%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 3        | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.82%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 0.82%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 154      | 53.66%  |
| NVMe | 67       | 23.34%  |
| IDE  | 51       | 17.77%  |
| RAID | 14       | 4.88%   |
| SAS  | 1        | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 121      | 62.05%  |
| AMD    | 74       | 37.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 2.53%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.02%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 2.02%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 2.02%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.52%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 1.52%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 1.52%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 1.52%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 1.52%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.52%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3        | 1.52%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.52%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 3        | 1.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.52%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1.52%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 1.52%   |
| AMD Ryzen 7 7700 8-Core Processor           | 3        | 1.52%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.01%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 1.01%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.01%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 2        | 1.01%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.01%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.01%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 2        | 1.01%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.01%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.01%   |
| Intel Core 2 CPU 6320 @ 1.86GHz             | 2        | 1.01%   |
| Intel 13th Gen Core i5-13600K               | 2        | 1.01%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 2        | 1.01%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 1.01%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.01%   |
| AMD Ryzen 5 5600 6-Core Processor           | 2        | 1.01%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 2        | 1.01%   |
| AMD Phenom II X4 965 Processor              | 2        | 1.01%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.01%   |
| AMD Athlon X4 740 Quad Core Processor       | 2        | 1.01%   |
| AMD Athlon 64 X2 Dual Core Processor 6400+  | 2        | 1.01%   |
| Intel Xeon W-2295 CPU @ 3.00GHz             | 1        | 0.51%   |
| Intel Xeon W-2145 CPU @ 3.70GHz             | 1        | 0.51%   |
| Intel Xeon E-2314 CPU @ 2.80GHz             | 1        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 38       | 19.19%  |
| Intel Core i3           | 19       | 9.6%    |
| AMD Ryzen 5             | 17       | 8.59%   |
| Intel Core i7           | 16       | 8.08%   |
| Other                   | 14       | 7.07%   |
| AMD Ryzen 9             | 10       | 5.05%   |
| AMD Ryzen 7             | 10       | 5.05%   |
| Intel Core 2 Duo        | 9        | 4.55%   |
| Intel Xeon              | 7        | 3.54%   |
| AMD Ryzen 3             | 6        | 3.03%   |
| AMD FX                  | 6        | 3.03%   |
| Intel Pentium           | 5        | 2.53%   |
| AMD Athlon II X4        | 4        | 2.02%   |
| Intel Pentium Dual-Core | 3        | 1.52%   |
| Intel Core 2            | 3        | 1.52%   |
| AMD Phenom II X4        | 3        | 1.52%   |
| AMD Athlon X4           | 3        | 1.52%   |
| AMD Athlon 64 X2        | 3        | 1.52%   |
| Intel Pentium Dual      | 2        | 1.01%   |
| Intel Pentium 4         | 2        | 1.01%   |
| Intel Core i9           | 2        | 1.01%   |
| Intel Core 2 Quad       | 2        | 1.01%   |
| AMD A8                  | 2        | 1.01%   |
| Intel Celeron           | 1        | 0.51%   |
| AMD Ryzen Threadripper  | 1        | 0.51%   |
| AMD Ryzen 7 PRO         | 1        | 0.51%   |
| AMD Ryzen 5 PRO         | 1        | 0.51%   |
| AMD Ryzen 3 PRO         | 1        | 0.51%   |
| AMD Phenom II X6        | 1        | 0.51%   |
| AMD Phenom II X2        | 1        | 0.51%   |
| AMD Phenom              | 1        | 0.51%   |
| AMD E                   | 1        | 0.51%   |
| AMD Athlon 64           | 1        | 0.51%   |
| AMD Athlon              | 1        | 0.51%   |
| AMD A6                  | 1        | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 74       | 37.37%  |
| 2      | 46       | 23.23%  |
| 6      | 32       | 16.16%  |
| 8      | 17       | 8.59%   |
| 12     | 8        | 4.04%   |
| 1      | 5        | 2.53%   |
| 24     | 3        | 1.52%   |
| 16     | 3        | 1.52%   |
| 14     | 3        | 1.52%   |
| 3      | 3        | 1.52%   |
| 10     | 2        | 1.01%   |
| 20     | 1        | 0.51%   |
| 18     | 1        | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 194      | 99.49%  |
| 2      | 1        | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 108      | 55.1%   |
| 1      | 88       | 44.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 193      | 98.97%  |
| Unknown        | 2        | 1.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 33%     |
| 0x306c3    | 21       | 10.34%  |
| 0x206a7    | 12       | 5.91%   |
| 0x1067a    | 7        | 3.45%   |
| 0xa0653    | 5        | 2.46%   |
| 0x906ea    | 5        | 2.46%   |
| 0x0800820d | 5        | 2.46%   |
| 0x906e9    | 4        | 1.97%   |
| 0x506e3    | 4        | 1.97%   |
| 0x010000db | 4        | 1.97%   |
| 0x010000c8 | 4        | 1.97%   |
| 0xa0671    | 3        | 1.48%   |
| 0x6fd      | 3        | 1.48%   |
| 0x306a9    | 3        | 1.48%   |
| 0x0a601203 | 3        | 1.48%   |
| 0x08701021 | 3        | 1.48%   |
| 0x06001119 | 3        | 1.48%   |
| 0xf43      | 2        | 0.99%   |
| 0xb0671    | 2        | 0.99%   |
| 0xa0655    | 2        | 0.99%   |
| 0x906ed    | 2        | 0.99%   |
| 0x906eb    | 2        | 0.99%   |
| 0x6fb      | 2        | 0.99%   |
| 0x306f2    | 2        | 0.99%   |
| 0x0a601206 | 2        | 0.99%   |
| 0x08701013 | 2        | 0.99%   |
| 0x08600106 | 2        | 0.99%   |
| 0x0810100b | 2        | 0.99%   |
| 0x08001137 | 2        | 0.99%   |
| 0x06000852 | 2        | 0.99%   |
| 0x0600063e | 2        | 0.99%   |
| 0x90672    | 1        | 0.49%   |
| 0x6f6      | 1        | 0.49%   |
| 0x20655    | 1        | 0.49%   |
| 0x106a4    | 1        | 0.49%   |
| 0x0a50000d | 1        | 0.49%   |
| 0x0a50000c | 1        | 0.49%   |
| 0x0a20120e | 1        | 0.49%   |
| 0x0a201009 | 1        | 0.49%   |
| 0x0a201005 | 1        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 30       | 15.23%  |
| SandyBridge      | 16       | 8.12%   |
| Unknown          | 15       | 7.61%   |
| KabyLake         | 14       | 7.11%   |
| Zen 2            | 12       | 6.09%   |
| Zen              | 10       | 5.08%   |
| Penryn           | 10       | 5.08%   |
| Zen+             | 9        | 4.57%   |
| Skylake          | 9        | 4.57%   |
| Piledriver       | 9        | 4.57%   |
| K10              | 9        | 4.57%   |
| Core             | 9        | 4.57%   |
| Zen 3            | 8        | 4.06%   |
| CometLake        | 8        | 4.06%   |
| Icelake          | 6        | 3.05%   |
| Alderlake Hybrid | 6        | 3.05%   |
| K8 Hammer        | 4        | 2.03%   |
| IvyBridge        | 4        | 2.03%   |
| Westmere         | 2        | 1.02%   |
| NetBurst         | 2        | 1.02%   |
| Bulldozer        | 2        | 1.02%   |
| Nehalem          | 1        | 0.51%   |
| Excavator        | 1        | 0.51%   |
| Bobcat           | 1        | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 83       | 37.39%  |
| Nvidia                     | 80       | 36.04%  |
| Intel                      | 56       | 25.23%  |
| Matrox Electronics Systems | 2        | 0.9%    |
| ATI Technologies           | 1        | 0.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 13       | 5.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 5.29%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 3.52%   |
| AMD Raphael                                                                 | 8        | 3.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 2.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.2%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 1.76%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 1.76%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 4        | 1.76%   |
| Intel HD Graphics 530                                                       | 4        | 1.76%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 4        | 1.76%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.32%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 1.32%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.32%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.32%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.32%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1.32%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 1.32%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 3        | 1.32%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.32%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.32%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 3        | 1.32%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 1.32%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.32%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                         | 2        | 0.88%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 0.88%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 0.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 0.88%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.88%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.88%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 0.88%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 0.88%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 0.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 0.88%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 0.88%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 70       | 34.48%  |
| 1 x AMD        | 70       | 34.48%  |
| 1 x Intel      | 42       | 20.69%  |
| Intel + Nvidia | 6        | 2.96%   |
| Intel + AMD    | 5        | 2.46%   |
| 2 x AMD        | 4        | 1.97%   |
| AMD + Nvidia   | 4        | 1.97%   |
| 1 x Matrox     | 2        | 0.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 141      | 69.12%  |
| Proprietary | 56       | 27.45%  |
| Unknown     | 7        | 3.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 37.75%  |
| 1.01-2.0   | 31       | 15.2%   |
| 0.51-1.0   | 31       | 15.2%   |
| 7.01-8.0   | 21       | 10.29%  |
| 0.01-0.5   | 15       | 7.35%   |
| 3.01-4.0   | 13       | 6.37%   |
| 5.01-6.0   | 7        | 3.43%   |
| 8.01-16.0  | 6        | 2.94%   |
| 2.01-3.0   | 3        | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 47       | 21.46%  |
| Dell                 | 31       | 14.16%  |
| AOC                  | 26       | 11.87%  |
| Goldstar             | 23       | 10.5%   |
| Acer                 | 20       | 9.13%   |
| Philips              | 19       | 8.68%   |
| Ancor Communications | 11       | 5.02%   |
| Hewlett-Packard      | 6        | 2.74%   |
| BenQ                 | 4        | 1.83%   |
| ASUSTek Computer     | 4        | 1.83%   |
| Unknown              | 3        | 1.37%   |
| LG Electronics       | 3        | 1.37%   |
| Sony                 | 2        | 0.91%   |
| Huion                | 2        | 0.91%   |
| Grundig              | 2        | 0.91%   |
| Fujitsu Siemens      | 2        | 0.91%   |
| ViewSonic            | 1        | 0.46%   |
| Vestel Elektronik    | 1        | 0.46%   |
| RTK                  | 1        | 0.46%   |
| Panasonic            | 1        | 0.46%   |
| NOA VISION           | 1        | 0.46%   |
| NEC Computers        | 1        | 0.46%   |
| LG Display           | 1        | 0.46%   |
| Lenovo               | 1        | 0.46%   |
| KTC                  | 1        | 0.46%   |
| Jean                 | 1        | 0.46%   |
| InnoLux Display      | 1        | 0.46%   |
| Hitachi              | 1        | 0.46%   |
| Gigabyte Technology  | 1        | 0.46%   |
| AU Optronics         | 1        | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 3        | 1.26%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 3        | 1.26%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                     | 2        | 0.84%   |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                    | 2        | 0.84%   |
| Huion Kamvas 22 HAT2150 1920x1080 476x267mm 21.5-inch                 | 2        | 0.84%   |
| Grundig WXGA GRU4448 1600x1200                                        | 2        | 0.84%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2        | 0.84%   |
| Goldstar HDR 4K GSM7780 3840x2160 697x392mm 31.5-inch                 | 2        | 0.84%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 2        | 0.84%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 0.84%   |
| Dell S2721DGF DEL41DB 2560x1440 597x336mm 27.0-inch                   | 2        | 0.84%   |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                     | 2        | 0.84%   |
| Dell LCD Monitor SE2416H 5760x1080                                    | 2        | 0.84%   |
| Dell LCD Monitor SE2416H                                              | 2        | 0.84%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                     | 2        | 0.84%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 2        | 0.84%   |
| AOC U2879G6 AOC2879 3840x2160 621x341mm 27.9-inch                     | 2        | 0.84%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                       | 2        | 0.84%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 2        | 0.84%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                        | 2        | 0.84%   |
| AOC 22P1W AOC2201 1920x1080 477x268mm 21.5-inch                       | 2        | 0.84%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 2        | 0.84%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                     | 2        | 0.84%   |
| Acer K272HL ACR03DC 1920x1080 598x336mm 27.0-inch                     | 2        | 0.84%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch         | 1        | 0.42%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 1        | 0.42%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.42%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.42%   |
| Unknown LCD Monitor CVT STD LCDTV 3840x1080                           | 1        | 0.42%   |
| Sony TV SNY1A02 1920x1080                                             | 1        | 0.42%   |
| Sony TV *00 SNY2B05 3840x2160                                         | 1        | 0.42%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.42%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0608 1920x1080 510x290mm 23.1-inch  | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM05C6 1920x1080 520x290mm 23.4-inch  | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 440x250mm 19.9-inch   | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch  | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch   | 1        | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 97       | 45.33%  |
| 2560x1440 (QHD)    | 23       | 10.75%  |
| 3840x2160 (4K)     | 20       | 9.35%   |
| 1280x1024 (SXGA)   | 14       | 6.54%   |
| 1680x1050 (WSXGA+) | 12       | 5.61%   |
| 1920x1200 (WUXGA)  | 8        | 3.74%   |
| Unknown            | 8        | 3.74%   |
| 3840x1080          | 5        | 2.34%   |
| 1600x900 (HD+)     | 5        | 2.34%   |
| 2560x1080          | 4        | 1.87%   |
| 1440x900 (WXGA+)   | 4        | 1.87%   |
| 1360x768           | 4        | 1.87%   |
| 5760x1080          | 2        | 0.93%   |
| 3440x1440          | 2        | 0.93%   |
| 2048x1152          | 2        | 0.93%   |
| 1366x768 (WXGA)    | 2        | 0.93%   |
| 4480x1440          | 1        | 0.47%   |
| 2560x1600          | 1        | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 35       | 15.98%  |
| 27      | 32       | 14.61%  |
| 24      | 30       | 13.7%   |
| 21      | 27       | 12.33%  |
| Unknown | 21       | 9.59%   |
| 31      | 10       | 4.57%   |
| 19      | 10       | 4.57%   |
| 22      | 9        | 4.11%   |
| 17      | 9        | 4.11%   |
| 20      | 7        | 3.2%    |
| 34      | 5        | 2.28%   |
| 84      | 3        | 1.37%   |
| 54      | 3        | 1.37%   |
| 33      | 3        | 1.37%   |
| 18      | 3        | 1.37%   |
| 25      | 2        | 0.91%   |
| 72      | 1        | 0.46%   |
| 64      | 1        | 0.46%   |
| 60      | 1        | 0.46%   |
| 58      | 1        | 0.46%   |
| 49      | 1        | 0.46%   |
| 46      | 1        | 0.46%   |
| 39      | 1        | 0.46%   |
| 32      | 1        | 0.46%   |
| 26      | 1        | 0.46%   |
| 15      | 1        | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 87       | 41.63%  |
| 401-500     | 48       | 22.97%  |
| Unknown     | 21       | 10.05%  |
| 601-700     | 15       | 7.18%   |
| 701-800     | 9        | 4.31%   |
| 351-400     | 8        | 3.83%   |
| 301-350     | 8        | 3.83%   |
| 1001-1500   | 8        | 3.83%   |
| 1501-2000   | 4        | 1.91%   |
| 901-1000    | 1        | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 131      | 66.5%   |
| 16/10   | 27       | 13.71%  |
| Unknown | 18       | 9.14%   |
| 5/4     | 13       | 6.6%    |
| 21/9    | 6        | 3.05%   |
| 32/9    | 1        | 0.51%   |
| 3/2     | 1        | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 74       | 34.58%  |
| 301-350        | 33       | 15.42%  |
| 151-200        | 24       | 11.21%  |
| Unknown        | 21       | 9.81%   |
| 351-500        | 19       | 8.88%   |
| 251-300        | 17       | 7.94%   |
| More than 1000 | 10       | 4.67%   |
| 141-150        | 10       | 4.67%   |
| 501-1000       | 3        | 1.4%    |
| 121-130        | 2        | 0.93%   |
| 101-110        | 1        | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 118      | 58.42%  |
| 101-120 | 43       | 21.29%  |
| Unknown | 21       | 10.4%   |
| 121-160 | 11       | 5.45%   |
| 1-50    | 7        | 3.47%   |
| 161-240 | 2        | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 142      | 70.65%  |
| 2     | 45       | 22.39%  |
| 0     | 9        | 4.48%   |
| 3     | 4        | 1.99%   |
| 4     | 1        | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 128      | 45.07%  |
| Intel                             | 68       | 23.94%  |
| TP-Link                           | 11       | 3.87%   |
| Qualcomm Atheros                  | 10       | 3.52%   |
| Broadcom                          | 9        | 3.17%   |
| Ralink Technology                 | 6        | 2.11%   |
| MediaTek                          | 6        | 2.11%   |
| Ralink                            | 5        | 1.76%   |
| Qualcomm Atheros Communications   | 5        | 1.76%   |
| D-Link                            | 5        | 1.76%   |
| Nvidia                            | 4        | 1.41%   |
| Samsung Electronics               | 3        | 1.06%   |
| Marvell Technology Group          | 3        | 1.06%   |
| Xiaomi                            | 2        | 0.7%    |
| Sundance Technology Inc / IC Plus | 2        | 0.7%    |
| NetGear                           | 2        | 0.7%    |
| Linksys                           | 2        | 0.7%    |
| ASIX Electronics                  | 2        | 0.7%    |
| VIA Technologies                  | 1        | 0.35%   |
| T & A Mobile Phones               | 1        | 0.35%   |
| Nokia Mobile Phones               | 1        | 0.35%   |
| Microsoft                         | 1        | 0.35%   |
| ICS Advent                        | 1        | 0.35%   |
| Huawei Technologies               | 1        | 0.35%   |
| Edimax Technology                 | 1        | 0.35%   |
| D-Link System                     | 1        | 0.35%   |
| Broadcom Limited                  | 1        | 0.35%   |
| ASUSTek Computer                  | 1        | 0.35%   |
| Aquantia                          | 1        | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 98       | 32.13%  |
| Realtek RTL8125 2.5GbE Controller                                      | 16       | 5.25%   |
| Intel Wi-Fi 6 AX200                                                    | 7        | 2.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 5        | 1.64%   |
| Qualcomm Atheros AR9271 802.11n                                        | 5        | 1.64%   |
| Intel Ethernet Controller I225-V                                       | 5        | 1.64%   |
| Intel Ethernet Connection (7) I219-V                                   | 5        | 1.64%   |
| Intel Ethernet Connection (2) I218-V                                   | 5        | 1.64%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 1.31%   |
| Intel I210 Gigabit Network Connection                                  | 4        | 1.31%   |
| Intel Ethernet Connection I217-V                                       | 4        | 1.31%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 1.31%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 1.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3        | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 0.98%   |
| Ralink MT7601U Wireless Adapter                                        | 3        | 0.98%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 3        | 0.98%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 3        | 0.98%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 0.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 0.66%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                  | 2        | 0.66%   |
| TP-Link 802.11ac NIC                                                   | 2        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.66%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2        | 0.66%   |
| Realtek 802.11ac NIC                                                   | 2        | 0.66%   |
| Ralink RT2070 Wireless Adapter                                         | 2        | 0.66%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                   | 2        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.66%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter             | 2        | 0.66%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 0.66%   |
| NetGear A6210                                                          | 2        | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2        | 0.66%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.66%   |
| Intel Wireless 3165                                                    | 2        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.66%   |
| Intel Ethernet Connection (2) I218-LM                                  | 2        | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 16       | 20%     |
| Realtek Semiconductor           | 12       | 15%     |
| TP-Link                         | 11       | 13.75%  |
| Ralink Technology               | 6        | 7.5%    |
| Broadcom                        | 6        | 7.5%    |
| Ralink                          | 5        | 6.25%   |
| Qualcomm Atheros Communications | 5        | 6.25%   |
| D-Link                          | 5        | 6.25%   |
| Qualcomm Atheros                | 4        | 5%      |
| MediaTek                        | 3        | 3.75%   |
| NetGear                         | 2        | 2.5%    |
| Linksys                         | 2        | 2.5%    |
| Microsoft                       | 1        | 1.25%   |
| Edimax Technology               | 1        | 1.25%   |
| ASUSTek Computer                | 1        | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 7        | 8.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 5        | 6.17%   |
| Qualcomm Atheros AR9271 802.11n                                      | 5        | 6.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                      | 3        | 3.7%    |
| Ralink RT2561/RT61 802.11g PCI                                       | 3        | 3.7%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 3        | 3.7%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 2        | 2.47%   |
| TP-Link 802.11ac NIC                                                 | 2        | 2.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 2        | 2.47%   |
| Realtek 802.11ac NIC                                                 | 2        | 2.47%   |
| Ralink RT2070 Wireless Adapter                                       | 2        | 2.47%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 2.47%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter           | 2        | 2.47%   |
| NetGear A6210                                                        | 2        | 2.47%   |
| Intel Wireless 3165                                                  | 2        | 2.47%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 2        | 2.47%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 2        | 2.47%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2        | 2.47%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 1.23%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1        | 1.23%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 1.23%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1        | 1.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 1.23%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 1.23%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 1        | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 1.23%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 1.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1        | 1.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1        | 1.23%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                  | 1        | 1.23%   |
| Linksys WUSB6400M                                                    | 1        | 1.23%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 1.23%   |
| Intel Wireless 8265 / 8275                                           | 1        | 1.23%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1        | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 1.23%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 122      | 57.28%  |
| Intel                             | 58       | 27.23%  |
| Qualcomm Atheros                  | 6        | 2.82%   |
| Nvidia                            | 4        | 1.88%   |
| Marvell Technology Group          | 3        | 1.41%   |
| Broadcom                          | 3        | 1.41%   |
| Xiaomi                            | 2        | 0.94%   |
| Sundance Technology Inc / IC Plus | 2        | 0.94%   |
| Samsung Electronics               | 2        | 0.94%   |
| MediaTek                          | 2        | 0.94%   |
| ASIX Electronics                  | 2        | 0.94%   |
| VIA Technologies                  | 1        | 0.47%   |
| T & A Mobile Phones               | 1        | 0.47%   |
| ICS Advent                        | 1        | 0.47%   |
| Huawei Technologies               | 1        | 0.47%   |
| D-Link System                     | 1        | 0.47%   |
| Broadcom Limited                  | 1        | 0.47%   |
| Aquantia                          | 1        | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 98       | 44.34%  |
| Realtek RTL8125 2.5GbE Controller                                          | 16       | 7.24%   |
| Intel Ethernet Controller I225-V                                           | 5        | 2.26%   |
| Intel Ethernet Connection (7) I219-V                                       | 5        | 2.26%   |
| Intel Ethernet Connection (2) I218-V                                       | 5        | 2.26%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 1.81%   |
| Intel I210 Gigabit Network Connection                                      | 4        | 1.81%   |
| Intel Ethernet Connection I217-V                                           | 4        | 1.81%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 1.81%   |
| Intel Ethernet Connection (2) I219-V                                       | 4        | 1.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 1.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 1.36%   |
| Intel 82579V Gigabit Network Connection                                    | 3        | 1.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 3        | 1.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                              | 2        | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 0.9%    |
| Nvidia MCP61 Ethernet                                                      | 2        | 0.9%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                                      | 2        | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 0.9%    |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 0.9%    |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.45%   |
| T & A Mobile Phones 9008A                                                  | 1        | 0.45%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.45%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.45%   |
| Realtek RT8126 PCIe Ethernet Controller                                    | 1        | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 1        | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.45%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.45%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter              | 1        | 0.45%   |
| MediaTek Infinix SMART 5                                                   | 1        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 192      | 71.64%  |
| WiFi     | 73       | 27.24%  |
| Modem    | 2        | 0.75%   |
| Unknown  | 1        | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 148      | 75.51%  |
| WiFi     | 48       | 24.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 138      | 70.41%  |
| 2     | 52       | 26.53%  |
| 0     | 3        | 1.53%   |
| 13    | 1        | 0.51%   |
| 4     | 1        | 0.51%   |
| 3     | 1        | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 182      | 92.86%  |
| Yes  | 14       | 7.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 17       | 33.33%  |
| Cambridge Silicon Radio         | 11       | 21.57%  |
| Realtek Semiconductor           | 4        | 7.84%   |
| Broadcom                        | 4        | 7.84%   |
| TP-Link                         | 3        | 5.88%   |
| Foxconn / Hon Hai               | 3        | 5.88%   |
| MediaTek                        | 2        | 3.92%   |
| Integrated System Solution      | 2        | 3.92%   |
| ASUSTek Computer                | 2        | 3.92%   |
| Qualcomm Atheros Communications | 1        | 1.96%   |
| IMC Networks                    | 1        | 1.96%   |
| Apple                           | 1        | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 11       | 21.57%  |
| Intel AX200 Bluetooth                                 | 7        | 13.73%  |
| Realtek Bluetooth Radio                               | 4        | 7.84%   |
| TP-Link TP-Link Bluetooth USB Adapter                 | 3        | 5.88%   |
| Intel Bluetooth wireless interface                    | 3        | 5.88%   |
| Intel AX211 Bluetooth                                 | 3        | 5.88%   |
| MediaTek Wireless_Device                              | 2        | 3.92%   |
| Foxconn / Hon Hai Wireless_Device                     | 2        | 3.92%   |
| Broadcom HP Portable Bumble Bee                       | 2        | 3.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 3.92%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 1.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 1.96%   |
| Intel Bluetooth Device                                | 1        | 1.96%   |
| Intel AX201 Bluetooth                                 | 1        | 1.96%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 1.96%   |
| Integrated System Solution Bluetooth Device           | 1        | 1.96%   |
| IMC Networks BCM20702A0                               | 1        | 1.96%   |
| Foxconn / Hon Hai BT                                  | 1        | 1.96%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 1.96%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 1.96%   |
| Apple Bluetooth Host Controller                       | 1        | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 118      | 34.2%   |
| AMD                      | 109      | 31.59%  |
| Nvidia                   | 77       | 22.32%  |
| C-Media Electronics      | 12       | 3.48%   |
| Logitech                 | 4        | 1.16%   |
| Creative Labs            | 3        | 0.87%   |
| Yamaha                   | 2        | 0.58%   |
| Microsoft                | 2        | 0.58%   |
| XMOS                     | 1        | 0.29%   |
| VIA Technologies         | 1        | 0.29%   |
| Trust                    | 1        | 0.29%   |
| Tenx Technology          | 1        | 0.29%   |
| Razer USA                | 1        | 0.29%   |
| Nordic Semiconductor ASA | 1        | 0.29%   |
| Native Instruments       | 1        | 0.29%   |
| MCS                      | 1        | 0.29%   |
| Kingston Technology      | 1        | 0.29%   |
| JMTek                    | 1        | 0.29%   |
| Generalplus Technology   | 1        | 0.29%   |
| Focusrite-Novation       | 1        | 0.29%   |
| Ensoniq                  | 1        | 0.29%   |
| Cirrus Logic             | 1        | 0.29%   |
| ATI Technologies         | 1        | 0.29%   |
| ASUSTek Computer         | 1        | 0.29%   |
| Astro Gaming             | 1        | 0.29%   |
| Unknown                  | 1        | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 21       | 5.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17       | 4.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16       | 3.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 15       | 3.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 3.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13       | 3.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 12       | 2.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 2.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 2.48%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 2.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 2.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 9        | 2.23%   |
| Nvidia TU116 High Definition Audio Controller                              | 8        | 1.99%   |
| Intel 200 Series PCH HD Audio                                              | 8        | 1.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 1.99%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 8        | 1.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 1.74%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7        | 1.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 6        | 1.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 1.49%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 6        | 1.49%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 6        | 1.49%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 6        | 1.49%   |
| Intel Raptor Lake High Definition Audio Controller                         | 5        | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.24%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.24%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 0.99%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 0.99%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 0.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 0.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 0.99%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 4        | 0.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 0.99%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 4        | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 0.74%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 36       | 30.51%  |
| Corsair             | 17       | 14.41%  |
| G.Skill             | 14       | 11.86%  |
| Unknown             | 12       | 10.17%  |
| SK hynix            | 9        | 7.63%   |
| Samsung Electronics | 8        | 6.78%   |
| Crucial             | 7        | 5.93%   |
| Transcend           | 3        | 2.54%   |
| Patriot             | 2        | 1.69%   |
| Kingmax             | 2        | 1.69%   |
| Elpida              | 2        | 1.69%   |
| Silicon Power       | 1        | 0.85%   |
| Ramaxel Technology  | 1        | 0.85%   |
| Mushkin             | 1        | 0.85%   |
| Micron Technology   | 1        | 0.85%   |
| Apacer              | 1        | 0.85%   |
| A-DATA Technology   | 1        | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 4        | 3.2%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s    | 3        | 2.4%    |
| Unknown RAM Module 4096MB DIMM 667MT/s                 | 2        | 1.6%    |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s | 2        | 1.6%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 2        | 1.6%    |
| Kingston RAM KF560C40-16 16GB DIMM DDR5 6000MT/s       | 2        | 1.6%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 1.6%    |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s   | 2        | 1.6%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s    | 2        | 1.6%    |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 2        | 1.6%    |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s             | 1        | 0.8%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1        | 0.8%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 0.8%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 0.8%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.8%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s              | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM 1600MT/s                   | 1        | 0.8%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 1        | 0.8%    |
| Unknown RAM Module 2048MB DIMM 1600MT/s                | 1        | 0.8%    |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s               | 1        | 0.8%    |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s             | 1        | 0.8%    |
| Unknown RAM 4000 C19 Series 8192MB DIMM DDR4 4000MT/s  | 1        | 0.8%    |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s   | 1        | 0.8%    |
| Transcend RAM JM1600KLN-2G 2GB DIMM DDR3 1333MT/s      | 1        | 0.8%    |
| Transcend RAM JM1333KLN-2G 2GB DIMM 1333MT/s           | 1        | 0.8%    |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s             | 1        | 0.8%    |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.8%    |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s   | 1        | 0.8%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 1        | 0.8%    |
| SK hynix RAM HMT125U6BFR8C-H9 2GB DIMM DDR3 1333MT/s   | 1        | 0.8%    |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s   | 1        | 0.8%    |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s  | 1        | 0.8%    |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 0.8%    |
| SK hynix RAM HMA41GR7AFR4N-TF 8GB DIMM 2133MT/s        | 1        | 0.8%    |
| Silicon Power RAM Module 8GB DIMM DDR3 1600MT/s        | 1        | 0.8%    |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s              | 1        | 0.8%    |
| Samsung RAM M471B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 1        | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 1        | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 51       | 50%     |
| DDR3    | 30       | 29.41%  |
| DDR5    | 9        | 8.82%   |
| SDRAM   | 4        | 3.92%   |
| Unknown | 4        | 3.92%   |
| DDR2    | 3        | 2.94%   |
| DDR     | 1        | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 97       | 96.04%  |
| SODIMM | 4        | 3.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 38       | 34.23%  |
| 16384 | 26       | 23.42%  |
| 4096  | 25       | 22.52%  |
| 2048  | 14       | 12.61%  |
| 32768 | 4        | 3.6%    |
| 1024  | 3        | 2.7%    |
| 512   | 1        | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 16       | 14.81%  |
| 3200  | 12       | 11.11%  |
| 1333  | 10       | 9.26%   |
| 2400  | 9        | 8.33%   |
| 3600  | 7        | 6.48%   |
| 2667  | 7        | 6.48%   |
| 3400  | 5        | 4.63%   |
| 2133  | 4        | 3.7%    |
| 6000  | 3        | 2.78%   |
| 4000  | 3        | 2.78%   |
| 3733  | 3        | 2.78%   |
| 1800  | 3        | 2.78%   |
| 800   | 3        | 2.78%   |
| 5600  | 2        | 1.85%   |
| 5200  | 2        | 1.85%   |
| 1867  | 2        | 1.85%   |
| 667   | 2        | 1.85%   |
| 6600  | 1        | 0.93%   |
| 4800  | 1        | 0.93%   |
| 3933  | 1        | 0.93%   |
| 3800  | 1        | 0.93%   |
| 3466  | 1        | 0.93%   |
| 3334  | 1        | 0.93%   |
| 3333  | 1        | 0.93%   |
| 2933  | 1        | 0.93%   |
| 2866  | 1        | 0.93%   |
| 2800  | 1        | 0.93%   |
| 1866  | 1        | 0.93%   |
| 1067  | 1        | 0.93%   |
| 1066  | 1        | 0.93%   |
| 533   | 1        | 0.93%   |
| 400   | 1        | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 8        | 66.67%  |
| Prolific Technology | 2        | 16.67%  |
| Canon               | 2        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Prolific PL2305 Parallel Port   | 2        | 16.67%  |
| HP DeskJet 3630 series          | 2        | 16.67%  |
| HP LaserJet P1102               | 1        | 8.33%   |
| HP LaserJet M101-M106           | 1        | 8.33%   |
| HP Ink Tank Wireless 410 series | 1        | 8.33%   |
| HP HP LaserJet M14-M17          | 1        | 8.33%   |
| HP DeskJet 2700 series          | 1        | 8.33%   |
| HP DeskJet 2130 series          | 1        | 8.33%   |
| Canon PIXMA iP1800 Printer      | 1        | 8.33%   |
| Canon LiDE 400                  | 1        | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1        | 50%     |
| Canon CanoScan LiDE 220       | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 13       | 40.63%  |
| Sunplus Innovation Technology | 4        | 12.5%   |
| Microdia                      | 4        | 12.5%   |
| Realtek Semiconductor         | 3        | 9.38%   |
| Chicony Electronics           | 2        | 6.25%   |
| Trust                         | 1        | 3.13%   |
| icSpring                      | 1        | 3.13%   |
| GenesysLogic Technology       | 1        | 3.13%   |
| Genesys Logic                 | 1        | 3.13%   |
| Anker                         | 1        | 3.13%   |
| Alcor Micro                   | 1        | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 4        | 12.5%   |
| Sunplus HD 720P webcam                | 3        | 9.38%   |
| Realtek FULL HD 1080P Webcam          | 2        | 6.25%   |
| Microdia Camera                       | 2        | 6.25%   |
| Logitech Webcam C170                  | 2        | 6.25%   |
| Trust Trust Full HD Webcam            | 1        | 3.13%   |
| Sunplus Full HD webcam                | 1        | 3.13%   |
| Realtek Asus laptop camera            | 1        | 3.13%   |
| Microdia Streaming Camera W8GS        | 1        | 3.13%   |
| Microdia Sonix USB 2.0 Camera         | 1        | 3.13%   |
| Logitech Webcam C310                  | 1        | 3.13%   |
| Logitech Webcam C250                  | 1        | 3.13%   |
| Logitech Webcam C210                  | 1        | 3.13%   |
| Logitech Webcam C110                  | 1        | 3.13%   |
| Logitech Logitech Webcam C925e        | 1        | 3.13%   |
| Logitech HD Pro Webcam C920           | 1        | 3.13%   |
| Logitech C922 Pro Stream Webcam       | 1        | 3.13%   |
| icSpring icspring camera              | 1        | 3.13%   |
| GenesysLogic USB2.0 UVC PC Camera     | 1        | 3.13%   |
| Genesys Logic USB2.0 UVC PC Camera    | 1        | 3.13%   |
| Chicony HP High Definition Webcam     | 1        | 3.13%   |
| Chicony HP High Definition 1MP Webcam | 1        | 3.13%   |
| Anker Anker PowerConf C300            | 1        | 3.13%   |
| Alcor Micro USB 2.0 Camera            | 1        | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Gemalto (was Gemplus)      | 3        | 50%     |
| Aladdin Knowledge Systems  | 2        | 33.33%  |
| Athena Smartcard Solutions | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Key SmartCard Reader  | 2        | 33.33%  |
| Aladdin Knowledge Systems Token JC                | 2        | 33.33%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 16.67%  |
| Athena Smartcard Solutions ASEDrive V3C           | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 168      | 84.42%  |
| 1     | 22       | 11.06%  |
| 2     | 8        | 4.02%   |
| 4     | 1        | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 11       | 28.95%  |
| Net/wireless             | 9        | 23.68%  |
| Chipcard                 | 4        | 10.53%  |
| Bluetooth                | 4        | 10.53%  |
| Unassigned class         | 3        | 7.89%   |
| Communication controller | 3        | 7.89%   |
| Storage/raid             | 1        | 2.63%   |
| Sound                    | 1        | 2.63%   |
| Network                  | 1        | 2.63%   |
| Fingerprint reader       | 1        | 2.63%   |

