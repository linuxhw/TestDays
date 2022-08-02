Linux in Ireland - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

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

Total: 224

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | AMETHYST-M                  | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Dell          | 0V8WGR A01                  | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| Dell          | 0J3C2F A00                  | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| Gigabyte      | B85M-D3H                    | [028b64776a](https://linux-hardware.org/?probe=028b64776a) | Jun 15, 2022 |
| Gigabyte      | B85M-D3H                    | [eef8a87283](https://linux-hardware.org/?probe=eef8a87283) | Jun 15, 2022 |
| ASUSTek       | P8H77-M PRO                 | [674cb88747](https://linux-hardware.org/?probe=674cb88747) | Jun 13, 2022 |
| ASUSTek       | Maximus VII IMPACT          | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| ASRock        | B365M Pro4-F                | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte      | A320M-H-CF                  | [522da9476b](https://linux-hardware.org/?probe=522da9476b) | May 29, 2022 |
| Foxconn       | 2ABF                        | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| Dell          | 02YYK5 A01                  | [8471800bb3](https://linux-hardware.org/?probe=8471800bb3) | May 16, 2022 |
| MSI           | B450M MORTAR MAX            | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| Dell          | 02YYK5 A01                  | [373e009d3b](https://linux-hardware.org/?probe=373e009d3b) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [6836f79bdf](https://linux-hardware.org/?probe=6836f79bdf) | May 08, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [41cc4d30d4](https://linux-hardware.org/?probe=41cc4d30d4) | May 08, 2022 |
| Gigabyte      | GA-970A-D3                  | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| MSI           | H55M-E23                    | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| ASUSTek       | PRIME X470-PRO              | [5e1b40c8b5](https://linux-hardware.org/?probe=5e1b40c8b5) | Apr 25, 2022 |
| ASUSTek       | PRIME X470-PRO              | [346c9b6c59](https://linux-hardware.org/?probe=346c9b6c59) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Lenovo        | 312A SDK0J40700 WIN 3258... | [a645768047](https://linux-hardware.org/?probe=a645768047) | Apr 05, 2022 |
| Foxconn       | 2ABF                        | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0f98a36a43](https://linux-hardware.org/?probe=0f98a36a43) | Mar 30, 2022 |
| ASUSTek       | P8H61-MX USB3               | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| Intel         | DG45ID AAE46743-302         | [c185ef78b1](https://linux-hardware.org/?probe=c185ef78b1) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| Foxconn       | 2ABF                        | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| ASRock        | Z68 Pro3                    | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| HP            | 21D0                        | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ace22bd471](https://linux-hardware.org/?probe=ace22bd471) | Feb 11, 2022 |
| Gigabyte      | B450 AORUS M                | [bb5bd32928](https://linux-hardware.org/?probe=bb5bd32928) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS M                | [2c93e69093](https://linux-hardware.org/?probe=2c93e69093) | Feb 07, 2022 |
| Dell          | 0X4H68 A00                  | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Dell          | 0X4H68 A00                  | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| ASRock        | Z68 Pro3                    | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [c8932dbfd0](https://linux-hardware.org/?probe=c8932dbfd0) | Jan 15, 2022 |
| Intel         | DG45ID AAE46743-302         | [ab40e8dd7d](https://linux-hardware.org/?probe=ab40e8dd7d) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| ASUSTek       | PRIME Z370-P                | [4894e2c956](https://linux-hardware.org/?probe=4894e2c956) | Jan 02, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [4161b37157](https://linux-hardware.org/?probe=4161b37157) | Dec 30, 2021 |
| Gigabyte      | B450M DS3H-CF               | [296af779e4](https://linux-hardware.org/?probe=296af779e4) | Dec 20, 2021 |
| HP            | 1495                        | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| MSI           | B450 GAMING PLUS            | [69b4695e8d](https://linux-hardware.org/?probe=69b4695e8d) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| Gigabyte      | 970A-DS3P                   | [bb51358294](https://linux-hardware.org/?probe=bb51358294) | Nov 18, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [3e574fa012](https://linux-hardware.org/?probe=3e574fa012) | Oct 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [4add26ac8c](https://linux-hardware.org/?probe=4add26ac8c) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| HP            | 21D0                        | [1dbb2b4a2d](https://linux-hardware.org/?probe=1dbb2b4a2d) | Oct 20, 2021 |
| Gigabyte      | B450M DS3H-CF               | [74cbbcac9f](https://linux-hardware.org/?probe=74cbbcac9f) | Oct 07, 2021 |
| MSI           | MS-7270                     | [4281e009bb](https://linux-hardware.org/?probe=4281e009bb) | Oct 05, 2021 |
| HP            | 1998                        | [74a28b051a](https://linux-hardware.org/?probe=74a28b051a) | Oct 03, 2021 |
| ASUSTek       | Maximus VIII FORMULA        | [5acbf68626](https://linux-hardware.org/?probe=5acbf68626) | Sep 25, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [7500e17316](https://linux-hardware.org/?probe=7500e17316) | Sep 11, 2021 |
| ASUSTek       | PRIME X570-P                | [f1b601400c](https://linux-hardware.org/?probe=f1b601400c) | Sep 01, 2021 |
| Dell          | 0J37VM A01                  | [88012fdf33](https://linux-hardware.org/?probe=88012fdf33) | Aug 30, 2021 |
| MSI           | B450 GAMING PLUS            | [f5d2b51d19](https://linux-hardware.org/?probe=f5d2b51d19) | Aug 16, 2021 |
| Dell          | 0X9M3X A01                  | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1ea279df08](https://linux-hardware.org/?probe=1ea279df08) | Aug 08, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | [32e0ae8af0](https://linux-hardware.org/?probe=32e0ae8af0) | Aug 03, 2021 |
| Dell          | 0KRC95 A00                  | [f8c48b22e6](https://linux-hardware.org/?probe=f8c48b22e6) | Aug 02, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [69869dec40](https://linux-hardware.org/?probe=69869dec40) | Jul 27, 2021 |
| ASRock        | J4105M                      | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| ASRock        | Z77 Extreme3                | [ecd7ec8f36](https://linux-hardware.org/?probe=ecd7ec8f36) | Jul 02, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [27fea5c8cb](https://linux-hardware.org/?probe=27fea5c8cb) | Jun 12, 2021 |
| ASUSTek       | P6X58D-E                    | [1ccc05a479](https://linux-hardware.org/?probe=1ccc05a479) | Jun 09, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f8241fa3ce](https://linux-hardware.org/?probe=f8241fa3ce) | Jun 08, 2021 |
| Gigabyte      | GA-MA770-UD3                | [6c770833c9](https://linux-hardware.org/?probe=6c770833c9) | Jun 04, 2021 |
| Dell          | 07F37C A01                  | [baba8a29ac](https://linux-hardware.org/?probe=baba8a29ac) | Jun 02, 2021 |
| MSI           | MS-7270                     | [7cc66e3a90](https://linux-hardware.org/?probe=7cc66e3a90) | May 29, 2021 |
| ASUSTek       | PRIME A320M-K               | [3c83289b45](https://linux-hardware.org/?probe=3c83289b45) | May 28, 2021 |
| HP            | 3397                        | [ae9a8581c5](https://linux-hardware.org/?probe=ae9a8581c5) | May 23, 2021 |
| MSI           | X470 GAMING PRO             | [f7c5833c2a](https://linux-hardware.org/?probe=f7c5833c2a) | May 23, 2021 |
| Shuttle       | FS35V4                      | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| HP            | 18E5                        | [6cbae0f799](https://linux-hardware.org/?probe=6cbae0f799) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ea97f7d05d](https://linux-hardware.org/?probe=ea97f7d05d) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [824ec14630](https://linux-hardware.org/?probe=824ec14630) | May 20, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [452f706571](https://linux-hardware.org/?probe=452f706571) | May 07, 2021 |
| ASRock        | Z490M Pro4                  | [d1d4f84e0a](https://linux-hardware.org/?probe=d1d4f84e0a) | May 03, 2021 |
| ASUSTek       | M5A78L/USB3                 | [fe576d54b4](https://linux-hardware.org/?probe=fe576d54b4) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | [e651f5da2c](https://linux-hardware.org/?probe=e651f5da2c) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | [be651d63a0](https://linux-hardware.org/?probe=be651d63a0) | Apr 19, 2021 |
| Dell          | 0NNNCT A01                  | [8253ac8502](https://linux-hardware.org/?probe=8253ac8502) | Apr 10, 2021 |
| ASRock        | B450M Pro4                  | [2e946e600e](https://linux-hardware.org/?probe=2e946e600e) | Apr 08, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | [6917221b5b](https://linux-hardware.org/?probe=6917221b5b) | Apr 02, 2021 |
| ASUSTek       | P8Z77-V                     | [9e21f67ab7](https://linux-hardware.org/?probe=9e21f67ab7) | Mar 28, 2021 |
| ASUSTek       | M5A78L/USB3                 | [1b571fd1c4](https://linux-hardware.org/?probe=1b571fd1c4) | Mar 18, 2021 |
| Dell          | 0NNNCT A01                  | [e5a6c9dcb9](https://linux-hardware.org/?probe=e5a6c9dcb9) | Mar 17, 2021 |
| Pegatron      | 2A94h                       | [b035a149a3](https://linux-hardware.org/?probe=b035a149a3) | Mar 02, 2021 |
| Medion        | MS-7646                     | [5ca2e128b6](https://linux-hardware.org/?probe=5ca2e128b6) | Feb 24, 2021 |
| Dell          | 0GDG8Y A00                  | [8f2450a3b0](https://linux-hardware.org/?probe=8f2450a3b0) | Feb 20, 2021 |
| Dell          | 0WR7PY A03                  | [878e82f1a3](https://linux-hardware.org/?probe=878e82f1a3) | Feb 19, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [78c7860103](https://linux-hardware.org/?probe=78c7860103) | Feb 10, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [8647ccdbef](https://linux-hardware.org/?probe=8647ccdbef) | Feb 10, 2021 |
| MSI           | 2AE0                        | [374ff27ab8](https://linux-hardware.org/?probe=374ff27ab8) | Feb 09, 2021 |
| HP            | 1495                        | [d8d36f4b2b](https://linux-hardware.org/?probe=d8d36f4b2b) | Feb 08, 2021 |
| Dell          | 0HY9JP A02                  | [51ede3687a](https://linux-hardware.org/?probe=51ede3687a) | Feb 05, 2021 |
| Dell          | 0HY9JP A02                  | [6c4261b08f](https://linux-hardware.org/?probe=6c4261b08f) | Feb 05, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2c59be484e](https://linux-hardware.org/?probe=2c59be484e) | Jan 22, 2021 |
| ASUSTek       | Maximus IV Extreme          | [9ce5eab595](https://linux-hardware.org/?probe=9ce5eab595) | Jan 16, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [192f01dd70](https://linux-hardware.org/?probe=192f01dd70) | Jan 16, 2021 |
| ASUSTek       | Crosshair IV Formula        | [54b2f4c522](https://linux-hardware.org/?probe=54b2f4c522) | Jan 11, 2021 |
| MSI           | X470 GAMING PRO             | [d7528e4806](https://linux-hardware.org/?probe=d7528e4806) | Jan 09, 2021 |
| ASUSTek       | F2A55-M LK2                 | [b6ffae8f7a](https://linux-hardware.org/?probe=b6ffae8f7a) | Dec 27, 2020 |
| HP            | 3032h                       | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| MSI           | MEG X399 CREATION           | [d1e772d769](https://linux-hardware.org/?probe=d1e772d769) | Dec 11, 2020 |
| MSI           | MS-7270                     | [b4e45eae99](https://linux-hardware.org/?probe=b4e45eae99) | Nov 26, 2020 |
| MSI           | MS-7270                     | [c70e52b025](https://linux-hardware.org/?probe=c70e52b025) | Nov 13, 2020 |
| HP            | 1495                        | [a250ea93d5](https://linux-hardware.org/?probe=a250ea93d5) | Nov 10, 2020 |
| MSI           | MS-7270                     | [97556dedc3](https://linux-hardware.org/?probe=97556dedc3) | Nov 05, 2020 |
| Dell          | Dimension 5100              | [f18393d9aa](https://linux-hardware.org/?probe=f18393d9aa) | Nov 03, 2020 |
| HP            | 1497                        | [dea5079fad](https://linux-hardware.org/?probe=dea5079fad) | Oct 19, 2020 |
| Dell          | 0RY206                      | [4e0283b4c8](https://linux-hardware.org/?probe=4e0283b4c8) | Oct 18, 2020 |
| Dell          | 0RY206                      | [5d45dd253e](https://linux-hardware.org/?probe=5d45dd253e) | Oct 18, 2020 |
| HP            | 1497                        | [8dd5fc52bd](https://linux-hardware.org/?probe=8dd5fc52bd) | Oct 15, 2020 |
| Foxconn       | 2ABF                        | [bd7a8f0f96](https://linux-hardware.org/?probe=bd7a8f0f96) | Oct 15, 2020 |
| Dell          | Dimension 5100              | [5b80714363](https://linux-hardware.org/?probe=5b80714363) | Oct 14, 2020 |
| ASUSTek       | PRIME B550M-A               | [ab8c149b9f](https://linux-hardware.org/?probe=ab8c149b9f) | Oct 14, 2020 |
| Lenovo        | ThinkStation D20 415892G    | [08619ece44](https://linux-hardware.org/?probe=08619ece44) | Oct 14, 2020 |
| ASUSTek       | H81M-PLUS                   | [d245d1c5a5](https://linux-hardware.org/?probe=d245d1c5a5) | Oct 06, 2020 |
| HP            | 1495                        | [d1cf757d40](https://linux-hardware.org/?probe=d1cf757d40) | Oct 05, 2020 |
| HP            | 1495                        | [2389a49dc0](https://linux-hardware.org/?probe=2389a49dc0) | Oct 05, 2020 |
| Lenovo        | ThinkStation D20 415892G    | [1e8497692d](https://linux-hardware.org/?probe=1e8497692d) | Oct 02, 2020 |
| ASRock        | H97M Pro4                   | [c2148ec054](https://linux-hardware.org/?probe=c2148ec054) | Oct 01, 2020 |
| ASUSTek       | H81M-PLUS                   | [c22330bac3](https://linux-hardware.org/?probe=c22330bac3) | Sep 26, 2020 |
| ASUSTek       | H81M-PLUS                   | [a2c5c1ea67](https://linux-hardware.org/?probe=a2c5c1ea67) | Sep 18, 2020 |
| Foxconn       | 2ABF                        | [3eba500997](https://linux-hardware.org/?probe=3eba500997) | Sep 15, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [20c0d6785b](https://linux-hardware.org/?probe=20c0d6785b) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Unknown       | RS780-SB700 Unknox          | [a084e40027](https://linux-hardware.org/?probe=a084e40027) | Aug 30, 2020 |
| Gigabyte      | GA-MA790X-UD3P              | [f5a642ebbb](https://linux-hardware.org/?probe=f5a642ebbb) | Aug 28, 2020 |
| ASRock        | Z77 Extreme4                | [f710d270fe](https://linux-hardware.org/?probe=f710d270fe) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | [f25aa5934e](https://linux-hardware.org/?probe=f25aa5934e) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | [ebb3d9d7aa](https://linux-hardware.org/?probe=ebb3d9d7aa) | Aug 15, 2020 |
| Gigabyte      | G1.Sniper                   | [8d1bc7ce18](https://linux-hardware.org/?probe=8d1bc7ce18) | Aug 15, 2020 |
| Foxconn       | 2ABF                        | [e1529e585d](https://linux-hardware.org/?probe=e1529e585d) | Aug 14, 2020 |
| ASRock        | N68C-S UCC                  | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| Foxconn       | 2ABF                        | [92a135b7d2](https://linux-hardware.org/?probe=92a135b7d2) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | [c3fbdc22c8](https://linux-hardware.org/?probe=c3fbdc22c8) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | [4a551e8c6b](https://linux-hardware.org/?probe=4a551e8c6b) | Aug 09, 2020 |
| ASRock        | N68C-S UCC                  | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| Dell          | 0T568R A00                  | [fb620a31fc](https://linux-hardware.org/?probe=fb620a31fc) | Aug 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [5101109869](https://linux-hardware.org/?probe=5101109869) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| HP            | 8648                        | [e034f483fc](https://linux-hardware.org/?probe=e034f483fc) | Aug 06, 2020 |
| Foxconn       | 2ABF                        | [b5911c66d7](https://linux-hardware.org/?probe=b5911c66d7) | Aug 02, 2020 |
| Gigabyte      | B450M DS3H-CF               | [9b5d494924](https://linux-hardware.org/?probe=9b5d494924) | Jul 25, 2020 |
| HP            | 8425                        | [25fd18c4f7](https://linux-hardware.org/?probe=25fd18c4f7) | Jul 19, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [332ba4769f](https://linux-hardware.org/?probe=332ba4769f) | Jul 01, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [0c0f90ba39](https://linux-hardware.org/?probe=0c0f90ba39) | Jun 27, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [92adc3c517](https://linux-hardware.org/?probe=92adc3c517) | Jun 25, 2020 |
| MSI           | X570-A PRO                  | [60c99711b8](https://linux-hardware.org/?probe=60c99711b8) | Jun 23, 2020 |
| ASUSTek       | M5A97 R2.0                  | [d79300ba76](https://linux-hardware.org/?probe=d79300ba76) | Jun 18, 2020 |
| MSI           | MEG X399 CREATION           | [89214de087](https://linux-hardware.org/?probe=89214de087) | Jun 12, 2020 |
| Lenovo        | ThinkCentre M58 7373BVU     | [5c40e26f41](https://linux-hardware.org/?probe=5c40e26f41) | Jun 09, 2020 |
| ASUSTek       | M5A97 R2.0                  | [a1615f709d](https://linux-hardware.org/?probe=a1615f709d) | Jun 07, 2020 |
| Dell          | 0GY6Y8 A02                  | [7b570e8172](https://linux-hardware.org/?probe=7b570e8172) | Jun 01, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | [1538853c0c](https://linux-hardware.org/?probe=1538853c0c) | May 26, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | [cdcb59b3fb](https://linux-hardware.org/?probe=cdcb59b3fb) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | [495a29d64c](https://linux-hardware.org/?probe=495a29d64c) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | [1c2ca9c7de](https://linux-hardware.org/?probe=1c2ca9c7de) | May 22, 2020 |
| ASRock        | H97M Pro4                   | [deca13654e](https://linux-hardware.org/?probe=deca13654e) | May 13, 2020 |
| Intel         | DQ57TM AAE92694-401         | [c2abb26814](https://linux-hardware.org/?probe=c2abb26814) | May 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | [db25140369](https://linux-hardware.org/?probe=db25140369) | May 06, 2020 |
| Dell          | 0FH884                      | [1f7976ed89](https://linux-hardware.org/?probe=1f7976ed89) | Apr 30, 2020 |
| Dell          | 0200DY A03                  | [473467f488](https://linux-hardware.org/?probe=473467f488) | Apr 29, 2020 |
| Dell          | 0FH884                      | [306c5d73fb](https://linux-hardware.org/?probe=306c5d73fb) | Apr 27, 2020 |
| Dell          | 0FH884                      | [9fd393aab9](https://linux-hardware.org/?probe=9fd393aab9) | Apr 27, 2020 |
| ABIT          | KN9                         | [6254e80aba](https://linux-hardware.org/?probe=6254e80aba) | Apr 26, 2020 |
| ABIT          | KN9                         | [be7c3f4dc9](https://linux-hardware.org/?probe=be7c3f4dc9) | Apr 14, 2020 |
| Lenovo        | ThinkStation D20 415892G    | [79ceb06042](https://linux-hardware.org/?probe=79ceb06042) | Apr 05, 2020 |
| ASUSTek       | Z87-K                       | [2ccf545fb8](https://linux-hardware.org/?probe=2ccf545fb8) | Apr 03, 2020 |
| Dell          | 0P301D A00                  | [5996aa0d7b](https://linux-hardware.org/?probe=5996aa0d7b) | Apr 02, 2020 |
| ASUSTek       | Z87-PRO                     | [cf7a7cb442](https://linux-hardware.org/?probe=cf7a7cb442) | Mar 21, 2020 |
| Lenovo        | ThinkCentre A70 7844Q2G     | [7a3df56f82](https://linux-hardware.org/?probe=7a3df56f82) | Mar 20, 2020 |
| Gigabyte      | F2A58M-DS2                  | [b5c9d31ae9](https://linux-hardware.org/?probe=b5c9d31ae9) | Mar 18, 2020 |
| Dell          | 0J3C2F A00                  | [3a37c7a548](https://linux-hardware.org/?probe=3a37c7a548) | Mar 11, 2020 |
| Lenovo        | ThinkStation D20 415892G    | [6672072cc5](https://linux-hardware.org/?probe=6672072cc5) | Mar 03, 2020 |
| ABIT          | KN9                         | [dafc30ae16](https://linux-hardware.org/?probe=dafc30ae16) | Mar 02, 2020 |
| ABIT          | KN9                         | [e26e7f08ca](https://linux-hardware.org/?probe=e26e7f08ca) | Feb 23, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [11d467ac47](https://linux-hardware.org/?probe=11d467ac47) | Feb 22, 2020 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [e53a35010c](https://linux-hardware.org/?probe=e53a35010c) | Feb 22, 2020 |
| HP            | 1998                        | [edb9bba986](https://linux-hardware.org/?probe=edb9bba986) | Jan 19, 2020 |
| ASUSTek       | P8P67 PRO                   | [0c3d1fcefe](https://linux-hardware.org/?probe=0c3d1fcefe) | Dec 05, 2019 |
| MSI           | Z77 MPower                  | [ab7afebfb6](https://linux-hardware.org/?probe=ab7afebfb6) | Nov 26, 2019 |
| MSI           | Z77 MPower                  | [77c87b6b71](https://linux-hardware.org/?probe=77c87b6b71) | Nov 26, 2019 |
| Seco          | C40 C                       | [a3f6f85e6a](https://linux-hardware.org/?probe=a3f6f85e6a) | Sep 15, 2019 |
| Seco          | C40 C                       | [16208d3700](https://linux-hardware.org/?probe=16208d3700) | Sep 04, 2019 |
| Seco          | C40 C                       | [3a7afd413f](https://linux-hardware.org/?probe=3a7afd413f) | Aug 28, 2019 |
| ASUSTek       | K5130                       | [72b7a5b445](https://linux-hardware.org/?probe=72b7a5b445) | Aug 08, 2019 |
| DFI           | INF P35                     | [7987560cdc](https://linux-hardware.org/?probe=7987560cdc) | Aug 02, 2019 |
| DFI           | INF P35                     | [0379ced795](https://linux-hardware.org/?probe=0379ced795) | Aug 02, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | [b7db1f6d08](https://linux-hardware.org/?probe=b7db1f6d08) | Jul 27, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | [bf4c96625e](https://linux-hardware.org/?probe=bf4c96625e) | Jul 27, 2019 |
| Apple         | Mac-F42C88C8 Proto1         | [649ff143ad](https://linux-hardware.org/?probe=649ff143ad) | Jul 08, 2019 |
| ASUSTek       | F2A55-M LK2                 | [93d8ad05a1](https://linux-hardware.org/?probe=93d8ad05a1) | Jun 30, 2019 |
| Shuttle       | XS35V3                      | [de0cc0ab6f](https://linux-hardware.org/?probe=de0cc0ab6f) | Jun 16, 2019 |
| Dell          | 0FJ030                      | [c3dfb2bea5](https://linux-hardware.org/?probe=c3dfb2bea5) | Jun 05, 2019 |
| Lenovo        | MAHOBAY                     | [71dd964fb5](https://linux-hardware.org/?probe=71dd964fb5) | Jun 04, 2019 |
| ASRock        | G31M-S                      | [213f2f20b6](https://linux-hardware.org/?probe=213f2f20b6) | May 24, 2019 |
| Dell          | 0Y2MRG A00                  | [f32755062c](https://linux-hardware.org/?probe=f32755062c) | May 23, 2019 |
| Dell          | 03NVJ6 A02                  | [915e0bab53](https://linux-hardware.org/?probe=915e0bab53) | May 12, 2019 |
| ASUSTek       | P8P67 PRO                   | [b0dcc92563](https://linux-hardware.org/?probe=b0dcc92563) | Apr 03, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6bae84797a](https://linux-hardware.org/?probe=6bae84797a) | Mar 22, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [9e86bfbcc2](https://linux-hardware.org/?probe=9e86bfbcc2) | Mar 22, 2019 |
| Shuttle       | FS35V4                      | [03af7dbe17](https://linux-hardware.org/?probe=03af7dbe17) | Mar 20, 2019 |
| Dell          | 0CRH6C A00                  | [300a99b1d0](https://linux-hardware.org/?probe=300a99b1d0) | Feb 10, 2019 |
| Shuttle       | XS35V3                      | [ae76390fb4](https://linux-hardware.org/?probe=ae76390fb4) | Jan 18, 2019 |
| ASUSTek       | P8P67 PRO                   | [1cfe678b48](https://linux-hardware.org/?probe=1cfe678b48) | Jan 16, 2019 |
| ASRock        | X370 Gaming-ITX/ac          | [2311962133](https://linux-hardware.org/?probe=2311962133) | Sep 30, 2018 |
| ASUSTek       | P8P67 PRO                   | [6a91010c14](https://linux-hardware.org/?probe=6a91010c14) | Jul 07, 2018 |
| ASUSTek       | P8P67 PRO                   | [e5e3ed1c7c](https://linux-hardware.org/?probe=e5e3ed1c7c) | Jun 01, 2018 |
| ASUSTek       | P8P67 PRO                   | [1b14483855](https://linux-hardware.org/?probe=1b14483855) | Feb 23, 2018 |
| ASUSTek       | P8P67 PRO                   | [bbe4f7f994](https://linux-hardware.org/?probe=bbe4f7f994) | Feb 11, 2018 |
| ASUSTek       | P8P67 PRO                   | [b32d7f9bc2](https://linux-hardware.org/?probe=b32d7f9bc2) | Jan 12, 2018 |
| Gigabyte      | H61M-S2PV                   | [7cf734ce05](https://linux-hardware.org/?probe=7cf734ce05) | Nov 04, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 27       | 16.46%  |
| Ubuntu 18.04                 | 12       | 7.32%   |
| OpenMandriva 4.2             | 6        | 3.66%   |
| Ubuntu 19.04                 | 5        | 3.05%   |
| Manjaro                      | 5        | 3.05%   |
| Linux Mint 20                | 5        | 3.05%   |
| ArcoLinux Rolling            | 5        | 3.05%   |
| Arch                         | 5        | 3.05%   |
| ROSA R11                     | 4        | 2.44%   |
| Pop!_OS 22.04                | 4        | 2.44%   |
| Pop!_OS 21.10                | 4        | 2.44%   |
| Pop!_OS 20.10                | 4        | 2.44%   |
| Linux Mint 20.2              | 4        | 2.44%   |
| OpenMandriva 4.3             | 3        | 1.83%   |
| Linux Mint 20.1              | 3        | 1.83%   |
| Fedora 35                    | 3        | 1.83%   |
| Fedora 32                    | 3        | 1.83%   |
| Debian 11                    | 3        | 1.83%   |
| BlackPanther 18.1            | 3        | 1.83%   |
| Arch Rolling                 | 3        | 1.83%   |
| ROSA R10                     | 2        | 1.22%   |
| OpenMandriva 4.50            | 2        | 1.22%   |
| Linux Mint 19                | 2        | 1.22%   |
| Linux Mint 18.3              | 2        | 1.22%   |
| KDE neon 20.04               | 2        | 1.22%   |
| Fedora 36                    | 2        | 1.22%   |
| Fedora 33                    | 2        | 1.22%   |
| Endless 3.7.8                | 2        | 1.22%   |
| Debian 10                    | 2        | 1.22%   |
| Zorin 15                     | 1        | 0.61%   |
| Xubuntu 20.04                | 1        | 0.61%   |
| Ubuntu Core 16               | 1        | 0.61%   |
| Ubuntu 21.04                 | 1        | 0.61%   |
| Ubuntu 19.10                 | 1        | 0.61%   |
| SteamOS Snapshot             | 1        | 0.61%   |
| Solus 4.2                    | 1        | 0.61%   |
| ROSA R8                      | 1        | 0.61%   |
| ROSA R11.1                   | 1        | 0.61%   |
| Pop!_OS 21.04                | 1        | 0.61%   |
| Pop!_OS 20.04                | 1        | 0.61%   |
| Peppermint 10                | 1        | 0.61%   |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 0.61%   |
| MX 19                        | 1        | 0.61%   |
| Manjaro 21.2.0               | 1        | 0.61%   |
| Manjaro 21.1.0               | 1        | 0.61%   |
| Manjaro 21.0.5               | 1        | 0.61%   |
| Manjaro 21.0.4               | 1        | 0.61%   |
| Manjaro 21.0.3               | 1        | 0.61%   |
| Lubuntu 20.04                | 1        | 0.61%   |
| Linux Mint 20.3              | 1        | 0.61%   |
| Linux Mint 19.3              | 1        | 0.61%   |
| Linux Mint 19.1              | 1        | 0.61%   |
| Linux Lite 5.0               | 1        | 0.61%   |
| Kubuntu 20.10                | 1        | 0.61%   |
| KDE neon 18.04               | 1        | 0.61%   |
| Kali Rolling                 | 1        | 0.61%   |
| Kali 2021.2                  | 1        | 0.61%   |
| Gentoo 2.8                   | 1        | 0.61%   |
| Gentoo 2.7                   | 1        | 0.61%   |
| Feren OS 20.04               | 1        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 47       | 30.52%  |
| Linux Mint   | 16       | 10.39%  |
| Pop!_OS      | 12       | 7.79%   |
| OpenMandriva | 11       | 7.14%   |
| Manjaro      | 9        | 5.84%   |
| Fedora       | 9        | 5.84%   |
| Arch         | 8        | 5.19%   |
| ROSA         | 6        | 3.9%    |
| Debian       | 6        | 3.9%    |
| ArcoLinux    | 5        | 3.25%   |
| KDE neon     | 3        | 1.95%   |
| BlackPanther | 3        | 1.95%   |
| Kali         | 2        | 1.3%    |
| Gentoo       | 2        | 1.3%    |
| Endless      | 2        | 1.3%    |
| Zorin        | 1        | 0.65%   |
| Xubuntu      | 1        | 0.65%   |
| SteamOS      | 1        | 0.65%   |
| Solus        | 1        | 0.65%   |
| Peppermint   | 1        | 0.65%   |
| openSUSE     | 1        | 0.65%   |
| MX           | 1        | 0.65%   |
| Lubuntu      | 1        | 0.65%   |
| Linux Lite   | 1        | 0.65%   |
| Kubuntu      | 1        | 0.65%   |
| Feren OS     | 1        | 0.65%   |
| Elementary   | 1        | 0.65%   |
| Clear Linux  | 1        | 0.65%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.4.0-42-generic                 | 7        | 3.83%   |
| 5.10.14-desktop-1omv4002         | 6        | 3.28%   |
| 5.4.0-48-generic                 | 4        | 2.19%   |
| 5.8.0-7630-generic               | 3        | 1.64%   |
| 5.4.0-91-generic                 | 3        | 1.64%   |
| 5.4.0-47-generic                 | 3        | 1.64%   |
| 5.3.0-28-generic                 | 3        | 1.64%   |
| 5.17.5-arch1-1                   | 3        | 1.64%   |
| 5.16.7-desktop-1omv4003          | 3        | 1.64%   |
| 5.15.11-76051511-generic         | 3        | 1.64%   |
| 4.18.16-desktop-1bP              | 3        | 1.64%   |
| 5.8.14-arch1-1                   | 2        | 1.09%   |
| 5.8.0-43-generic                 | 2        | 1.09%   |
| 5.8.0-41-generic                 | 2        | 1.09%   |
| 5.4.0-88-generic                 | 2        | 1.09%   |
| 5.4.0-77-generic                 | 2        | 1.09%   |
| 5.4.0-72-generic                 | 2        | 1.09%   |
| 5.4.0-37-generic                 | 2        | 1.09%   |
| 5.3.0-45-generic                 | 2        | 1.09%   |
| 5.17.5-76051705-generic          | 2        | 1.09%   |
| 5.16.15-76051615-generic         | 2        | 1.09%   |
| 5.13.13-arch1-1                  | 2        | 1.09%   |
| 5.13.0-39-generic                | 2        | 1.09%   |
| 5.12.4-desktop-1omv4050          | 2        | 1.09%   |
| 5.0.0-23-generic                 | 2        | 1.09%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 2        | 1.09%   |
| 4.9.60-nrj-desktop-1rosa-i586    | 2        | 1.09%   |
| 4.9.155-nrj-desktop-1rosa-x86_64 | 2        | 1.09%   |
| 4.18.0-25-generic                | 2        | 1.09%   |
| 4.15.0-desktop-45.1rosa-x86_64   | 2        | 1.09%   |
| 4.10.0-38-generic                | 2        | 1.09%   |
| 5.9.3-arch1-1                    | 1        | 0.55%   |
| 5.8.7-arch1-1                    | 1        | 0.55%   |
| 5.8.11-1-MANJARO                 | 1        | 0.55%   |
| 5.8.10-200.fc32.x86_64           | 1        | 0.55%   |
| 5.8.0-7642-generic               | 1        | 0.55%   |
| 5.8.0-53-generic                 | 1        | 0.55%   |
| 5.8.0-33-generic                 | 1        | 0.55%   |
| 5.7.8-968.native                 | 1        | 0.55%   |
| 5.7.12-arch1-1                   | 1        | 0.55%   |
| 5.7.11-1-default                 | 1        | 0.55%   |
| 5.6.3-300.fc32.x86_64            | 1        | 0.55%   |
| 5.6.10-300.fc32.x86_64           | 1        | 0.55%   |
| 5.6.0-2-amd64                    | 1        | 0.55%   |
| 5.5.6-201.fc31.x86_64            | 1        | 0.55%   |
| 5.5.5-200.fc31.x86_64            | 1        | 0.55%   |
| 5.4.66-1-lts                     | 1        | 0.55%   |
| 5.4.32-generic-2rosa-x86_64      | 1        | 0.55%   |
| 5.4.0-kali4-amd64                | 1        | 0.55%   |
| 5.4.0-70-generic                 | 1        | 0.55%   |
| 5.4.0-64-generic                 | 1        | 0.55%   |
| 5.4.0-58-generic                 | 1        | 0.55%   |
| 5.4.0-54-generic                 | 1        | 0.55%   |
| 5.4.0-52-generic                 | 1        | 0.55%   |
| 5.4.0-51-generic                 | 1        | 0.55%   |
| 5.4.0-40-generic                 | 1        | 0.55%   |
| 5.4.0-39-generic                 | 1        | 0.55%   |
| 5.4.0-33-generic                 | 1        | 0.55%   |
| 5.4.0-31-generic                 | 1        | 0.55%   |
| 5.4.0-29-generic                 | 1        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 35       | 20%     |
| 5.8.0   | 10       | 5.71%   |
| 4.15.0  | 10       | 5.71%   |
| 5.3.0   | 8        | 4.57%   |
| 5.0.0   | 7        | 4%      |
| 5.17.5  | 6        | 3.43%   |
| 5.11.0  | 6        | 3.43%   |
| 5.10.14 | 6        | 3.43%   |
| 4.18.0  | 5        | 2.86%   |
| 5.13.0  | 4        | 2.29%   |
| 5.10.0  | 4        | 2.29%   |
| 5.16.7  | 3        | 1.71%   |
| 5.15.11 | 3        | 1.71%   |
| 4.18.16 | 3        | 1.71%   |
| 5.8.14  | 2        | 1.14%   |
| 5.18.10 | 2        | 1.14%   |
| 5.16.15 | 2        | 1.14%   |
| 5.16.11 | 2        | 1.14%   |
| 5.15.6  | 2        | 1.14%   |
| 5.15.12 | 2        | 1.14%   |
| 5.15.0  | 2        | 1.14%   |
| 5.13.13 | 2        | 1.14%   |
| 5.12.4  | 2        | 1.14%   |
| 5.11.11 | 2        | 1.14%   |
| 5.11.10 | 2        | 1.14%   |
| 4.9.60  | 2        | 1.14%   |
| 4.9.155 | 2        | 1.14%   |
| 4.19.0  | 2        | 1.14%   |
| 4.10.0  | 2        | 1.14%   |
| 5.9.3   | 1        | 0.57%   |
| 5.8.7   | 1        | 0.57%   |
| 5.8.11  | 1        | 0.57%   |
| 5.8.10  | 1        | 0.57%   |
| 5.7.8   | 1        | 0.57%   |
| 5.7.12  | 1        | 0.57%   |
| 5.7.11  | 1        | 0.57%   |
| 5.6.3   | 1        | 0.57%   |
| 5.6.10  | 1        | 0.57%   |
| 5.6.0   | 1        | 0.57%   |
| 5.5.6   | 1        | 0.57%   |
| 5.5.5   | 1        | 0.57%   |
| 5.4.66  | 1        | 0.57%   |
| 5.4.32  | 1        | 0.57%   |
| 5.17.6  | 1        | 0.57%   |
| 5.17.11 | 1        | 0.57%   |
| 5.16.2  | 1        | 0.57%   |
| 5.16.19 | 1        | 0.57%   |
| 5.16.16 | 1        | 0.57%   |
| 5.15.7  | 1        | 0.57%   |
| 5.15.17 | 1        | 0.57%   |
| 5.15.16 | 1        | 0.57%   |
| 5.14.10 | 1        | 0.57%   |
| 5.13.19 | 1        | 0.57%   |
| 5.12.8  | 1        | 0.57%   |
| 5.12.2  | 1        | 0.57%   |
| 5.12.12 | 1        | 0.57%   |
| 5.11.9  | 1        | 0.57%   |
| 5.11.21 | 1        | 0.57%   |
| 5.10.56 | 1        | 0.57%   |
| 5.10.34 | 1        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 36       | 21.43%  |
| 5.8     | 15       | 8.93%   |
| 5.10    | 14       | 8.33%   |
| 5.11    | 12       | 7.14%   |
| 5.15    | 10       | 5.95%   |
| 4.15    | 10       | 5.95%   |
| 5.16    | 9        | 5.36%   |
| 5.3     | 8        | 4.76%   |
| 5.17    | 8        | 4.76%   |
| 4.18    | 8        | 4.76%   |
| 5.13    | 7        | 4.17%   |
| 5.0     | 7        | 4.17%   |
| 5.12    | 5        | 2.98%   |
| 5.7     | 3        | 1.79%   |
| 5.6     | 3        | 1.79%   |
| 4.9     | 3        | 1.79%   |
| 5.18    | 2        | 1.19%   |
| 4.19    | 2        | 1.19%   |
| 4.10    | 2        | 1.19%   |
| 5.9     | 1        | 0.6%    |
| 5.5     | 1        | 0.6%    |
| 5.14    | 1        | 0.6%    |
| 4.1     | 1        | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 147      | 98%     |
| i686   | 3        | 2%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 60       | 38.22%  |
| KDE5       | 34       | 21.66%  |
| Unknown    | 23       | 14.65%  |
| XFCE       | 10       | 6.37%   |
| X-Cinnamon | 9        | 5.73%   |
| KDE        | 6        | 3.82%   |
| MATE       | 5        | 3.18%   |
| KDE4       | 4        | 2.55%   |
| LXQt       | 2        | 1.27%   |
| Pantheon   | 1        | 0.64%   |
| LXDE       | 1        | 0.64%   |
| LeftWM     | 1        | 0.64%   |
| Cinnamon   | 1        | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 121      | 80.67%  |
| Unknown | 15       | 10%     |
| Wayland | 11       | 7.33%   |
| Tty     | 3        | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 56.21%  |
| SDDM    | 33       | 21.57%  |
| GDM     | 16       | 10.46%  |
| LightDM | 6        | 3.92%   |
| TDM     | 5        | 3.27%   |
| KDM     | 4        | 2.61%   |
| GDM3    | 2        | 1.31%   |
| LXDM    | 1        | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_IE   | 72       | 46.75%  |
| en_US   | 28       | 18.18%  |
| Unknown | 26       | 16.88%  |
| en_GB   | 24       | 15.58%  |
| es_ES   | 2        | 1.3%    |
| pl_PL   | 1        | 0.65%   |
| C       | 1        | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 95       | 63.33%  |
| EFI  | 55       | 36.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 118      | 78.67%  |
| Overlay | 14       | 9.33%   |
| Btrfs   | 10       | 6.67%   |
| Unknown | 7        | 4.67%   |
| Zfs     | 1        | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 84       | 54.9%   |
| GPT     | 53       | 34.64%  |
| MBR     | 16       | 10.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 78.81%  |
| Yes       | 32       | 21.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 65.58%  |
| Yes       | 53       | 34.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 35       | 23.65%  |
| Dell                | 26       | 17.57%  |
| Gigabyte Technology | 21       | 14.19%  |
| MSI                 | 14       | 9.46%   |
| Hewlett-Packard     | 12       | 8.11%   |
| ASRock              | 12       | 8.11%   |
| Lenovo              | 10       | 6.76%   |
| Foxconn             | 3        | 2.03%   |
| Shuttle             | 2        | 1.35%   |
| Seco                | 2        | 1.35%   |
| Intel               | 2        | 1.35%   |
| Apple               | 2        | 1.35%   |
| Pegatron            | 1        | 0.68%   |
| Packard Bell        | 1        | 0.68%   |
| MiTAC               | 1        | 0.68%   |
| Medion              | 1        | 0.68%   |
| DFI                 | 1        | 0.68%   |
| ABIT                | 1        | 0.68%   |
| Unknown             | 1        | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 6        | 4.05%   |
| Gigabyte B450M DS3H                    | 4        | 2.7%    |
| Dell OptiPlex 7010                     | 4        | 2.7%    |
| HP Compaq 8200 Elite SFF PC            | 3        | 2.03%   |
| Dell OptiPlex 790                      | 3        | 2.03%   |
| ASUS ROG STRIX B450-F GAMING           | 3        | 2.03%   |
| Seco C40                               | 2        | 1.35%   |
| MSI MS-7B79                            | 2        | 1.35%   |
| Lenovo ThinkStation D20 415892G        | 2        | 1.35%   |
| HP EliteDesk 800 G1 SFF                | 2        | 1.35%   |
| Gigabyte X570 AORUS ULTRA              | 2        | 1.35%   |
| Dell OptiPlex 780                      | 2        | 1.35%   |
| Dell OptiPlex 7020                     | 2        | 1.35%   |
| ASUS TUF Gaming X570-PLUS              | 2        | 1.35%   |
| ASUS P8P67 PRO                         | 2        | 1.35%   |
| ASUS M5A78L/USB3                       | 2        | 1.35%   |
| Shuttle XS35V4                         | 1        | 0.68%   |
| Shuttle XS35V3                         | 1        | 0.68%   |
| Pegatron Pro 3010 Microtower PC        | 1        | 0.68%   |
| Packard Bell Vegas2                    | 1        | 0.68%   |
| MSI Pro 3515 Series                    | 1        | 0.68%   |
| MSI MS-7C84                            | 1        | 0.68%   |
| MSI MS-7C37                            | 1        | 0.68%   |
| MSI MS-7C02                            | 1        | 0.68%   |
| MSI MS-7B92                            | 1        | 0.68%   |
| MSI MS-7B89                            | 1        | 0.68%   |
| MSI MS-7B86                            | 1        | 0.68%   |
| MSI MS-7751                            | 1        | 0.68%   |
| MSI MS-7693                            | 1        | 0.68%   |
| MSI MS-7636                            | 1        | 0.68%   |
| MSI MS-7270                            | 1        | 0.68%   |
| MSI ER883AA-ABA M7470N                 | 1        | 0.68%   |
| MiTAC PD14TI AAPD14TI-101              | 1        | 0.68%   |
| Medion MS-7646                         | 1        | 0.68%   |
| Lenovo V530S-07ICB 10TX002GUK          | 1        | 0.68%   |
| Lenovo ThinkCentre M91p 7052A9G        | 1        | 0.68%   |
| Lenovo ThinkCentre M82 2929A58         | 1        | 0.68%   |
| Lenovo ThinkCentre M82 2756AF5         | 1        | 0.68%   |
| Lenovo ThinkCentre M720t 10SQCTO1WW    | 1        | 0.68%   |
| Lenovo ThinkCentre M58 7373BVU         | 1        | 0.68%   |
| Lenovo ThinkCentre E73 10DS000TUK      | 1        | 0.68%   |
| Lenovo ThinkCentre A70 7844Q2G         | 1        | 0.68%   |
| Intel QC6003                           | 1        | 0.68%   |
| Intel DESKTOP 300                      | 1        | 0.68%   |
| HP Slim Desktop S01-aF0xxx             | 1        | 0.68%   |
| HP ProDesk 600 G1 DM                   | 1        | 0.68%   |
| HP EliteDesk 800 G1 USDT               | 1        | 0.68%   |
| HP Compaq Elite 8300 SFF               | 1        | 0.68%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 0.68%   |
| HP Compaq 6200 Pro MT PC               | 1        | 0.68%   |
| HP 280 G2 SFF                          | 1        | 0.68%   |
| Gigabyte Z97-D3H                       | 1        | 0.68%   |
| Gigabyte TRX40 DESIGNARE               | 1        | 0.68%   |
| Gigabyte H61M-S2PV                     | 1        | 0.68%   |
| Gigabyte H110M-S2H-CF                  | 1        | 0.68%   |
| Gigabyte GA-MA790X-UD3P                | 1        | 0.68%   |
| Gigabyte GA-MA770-UD3                  | 1        | 0.68%   |
| Gigabyte GA-970A-D3                    | 1        | 0.68%   |
| Gigabyte GA-78LMT-USB3                 | 1        | 0.68%   |
| Gigabyte G1.Sniper                     | 1        | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 15       | 10.14%  |
| Lenovo ThinkCentre      | 7        | 4.73%   |
| HP Compaq               | 6        | 4.05%   |
| ASUS PRIME              | 6        | 4.05%   |
| ASUS All                | 6        | 4.05%   |
| Gigabyte B450M          | 4        | 2.7%    |
| ASUS TUF                | 4        | 2.7%    |
| HP EliteDesk            | 3        | 2.03%   |
| Dell Precision          | 3        | 2.03%   |
| ASUS ROG                | 3        | 2.03%   |
| Seco C40                | 2        | 1.35%   |
| MSI MS-7B79             | 2        | 1.35%   |
| Lenovo ThinkStation     | 2        | 1.35%   |
| Gigabyte X570           | 2        | 1.35%   |
| Gigabyte B450           | 2        | 1.35%   |
| Foxconn Pro             | 2        | 1.35%   |
| Dell Vostro             | 2        | 1.35%   |
| Dell Inspiron           | 2        | 1.35%   |
| ASUS P8P67              | 2        | 1.35%   |
| ASUS Maximus            | 2        | 1.35%   |
| ASUS M5A78L             | 2        | 1.35%   |
| ASUS Crosshair          | 2        | 1.35%   |
| ASRock Z77              | 2        | 1.35%   |
| Shuttle XS35V4          | 1        | 0.68%   |
| Shuttle XS35V3          | 1        | 0.68%   |
| Pegatron Pro            | 1        | 0.68%   |
| Packard Bell Vegas2     | 1        | 0.68%   |
| MSI Pro                 | 1        | 0.68%   |
| MSI MS-7C84             | 1        | 0.68%   |
| MSI MS-7C37             | 1        | 0.68%   |
| MSI MS-7C02             | 1        | 0.68%   |
| MSI MS-7B92             | 1        | 0.68%   |
| MSI MS-7B89             | 1        | 0.68%   |
| MSI MS-7B86             | 1        | 0.68%   |
| MSI MS-7751             | 1        | 0.68%   |
| MSI MS-7693             | 1        | 0.68%   |
| MSI MS-7636             | 1        | 0.68%   |
| MSI MS-7270             | 1        | 0.68%   |
| MSI ER883AA-ABA         | 1        | 0.68%   |
| MiTAC PD14TI            | 1        | 0.68%   |
| Medion MS-7646          | 1        | 0.68%   |
| Lenovo V530S-07ICB      | 1        | 0.68%   |
| Intel QC6003            | 1        | 0.68%   |
| Intel DESKTOP           | 1        | 0.68%   |
| HP Slim                 | 1        | 0.68%   |
| HP ProDesk              | 1        | 0.68%   |
| HP 280                  | 1        | 0.68%   |
| Gigabyte Z97-D3H        | 1        | 0.68%   |
| Gigabyte TRX40          | 1        | 0.68%   |
| Gigabyte H61M-S2PV      | 1        | 0.68%   |
| Gigabyte H110M-S2H-CF   | 1        | 0.68%   |
| Gigabyte GA-MA790X-UD3P | 1        | 0.68%   |
| Gigabyte GA-MA770-UD3   | 1        | 0.68%   |
| Gigabyte GA-970A-D3     | 1        | 0.68%   |
| Gigabyte GA-78LMT-USB3  | 1        | 0.68%   |
| Gigabyte G1.Sniper      | 1        | 0.68%   |
| Gigabyte F2A58M-DS2     | 1        | 0.68%   |
| Gigabyte B85M-D3H       | 1        | 0.68%   |
| Gigabyte A320M-H        | 1        | 0.68%   |
| Gigabyte 970A-DS3P      | 1        | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 24       | 16.22%  |
| 2013 | 18       | 12.16%  |
| 2012 | 18       | 12.16%  |
| 2011 | 17       | 11.49%  |
| 2019 | 13       | 8.78%   |
| 2010 | 12       | 8.11%   |
| 2008 | 10       | 6.76%   |
| 2020 | 7        | 4.73%   |
| 2017 | 6        | 4.05%   |
| 2014 | 6        | 4.05%   |
| 2015 | 5        | 3.38%   |
| 2006 | 4        | 2.7%    |
| 2009 | 3        | 2.03%   |
| 2007 | 3        | 2.03%   |
| 2021 | 1        | 0.68%   |
| 2005 | 1        | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 148      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 145      | 97.97%  |
| Enabled  | 3        | 2.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 148      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 39       | 25.66%  |
| 16.01-24.0  | 37       | 24.34%  |
| 3.01-4.0    | 26       | 17.11%  |
| 32.01-64.0  | 21       | 13.82%  |
| 4.01-8.0    | 15       | 9.87%   |
| 64.01-256.0 | 7        | 4.61%   |
| 24.01-32.0  | 4        | 2.63%   |
| 1.01-2.0    | 3        | 1.97%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 69       | 41.57%  |
| 2.01-3.0   | 36       | 21.69%  |
| 4.01-8.0   | 18       | 10.84%  |
| 3.01-4.0   | 18       | 10.84%  |
| 0.51-1.0   | 13       | 7.83%   |
| 8.01-16.0  | 10       | 6.02%   |
| 32.01-64.0 | 1        | 0.6%    |
| 0.01-0.5   | 1        | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 55       | 33.95%  |
| 2      | 41       | 25.31%  |
| 3      | 22       | 13.58%  |
| 4      | 19       | 11.73%  |
| 5      | 11       | 6.79%   |
| 7      | 5        | 3.09%   |
| 6      | 4        | 2.47%   |
| 10     | 2        | 1.23%   |
| 0      | 2        | 1.23%   |
| 9      | 1        | 0.62%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 82       | 53.95%  |
| No        | 70       | 46.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 147      | 99.32%  |
| No        | 1        | 0.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 80       | 53.33%  |
| No        | 70       | 46.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 98       | 64.05%  |
| Yes       | 55       | 35.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ireland | 148      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Dublin        | 86       | 55.84%  |
| Cork          | 8        | 5.19%   |
| Limerick      | 5        | 3.25%   |
| Tuam          | 3        | 1.95%   |
| Portlaoise    | 3        | 1.95%   |
| Naas          | 3        | 1.95%   |
| Kenmare       | 3        | 1.95%   |
| Gorey         | 3        | 1.95%   |
| Sligo         | 2        | 1.3%    |
| Oranmore      | 2        | 1.3%    |
| Cavan         | 2        | 1.3%    |
| Wexford       | 1        | 0.65%   |
| Tullamore     | 1        | 0.65%   |
| Tipperary     | 1        | 0.65%   |
| Swords        | 1        | 0.65%   |
| Summerhill    | 1        | 0.65%   |
| Shanagolden   | 1        | 0.65%   |
| Nenagh        | 1        | 0.65%   |
| Navan         | 1        | 0.65%   |
| Moyne         | 1        | 0.65%   |
| Maynooth      | 1        | 0.65%   |
| Mallow        | 1        | 0.65%   |
| Lucan         | 1        | 0.65%   |
| Listowel      | 1        | 0.65%   |
| Letterkenny   | 1        | 0.65%   |
| Kilkenny      | 1        | 0.65%   |
| Kildare       | 1        | 0.65%   |
| Kilcoole      | 1        | 0.65%   |
| Galway        | 1        | 0.65%   |
| Edenderry     | 1        | 0.65%   |
| Dunshaughlin  | 1        | 0.65%   |
| Dungarvan     | 1        | 0.65%   |
| Drumcondra    | 1        | 0.65%   |
| Droichead Nua | 1        | 0.65%   |
| Cobh          | 1        | 0.65%   |
| Castlecomer   | 1        | 0.65%   |
| Callan        | 1        | 0.65%   |
| Buncrana      | 1        | 0.65%   |
| Bray          | 1        | 0.65%   |
| Ballyshannon  | 1        | 0.65%   |
| Ballycanew    | 1        | 0.65%   |
| Ballincollig  | 1        | 0.65%   |
| Balbriggan    | 1        | 0.65%   |
| Athlone       | 1        | 0.65%   |
| Arklow        | 1        | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 69       | 139    | 23.55%  |
| Seagate                   | 54       | 101    | 18.43%  |
| Samsung Electronics       | 39       | 64     | 13.31%  |
| Crucial                   | 21       | 23     | 7.17%   |
| Toshiba                   | 17       | 24     | 5.8%    |
| Hitachi                   | 12       | 22     | 4.1%    |
| SanDisk                   | 11       | 17     | 3.75%   |
| Kingston                  | 10       | 14     | 3.41%   |
| A-DATA Technology         | 7        | 12     | 2.39%   |
| Phison                    | 4        | 9      | 1.37%   |
| Intel                     | 4        | 4      | 1.37%   |
| Verbatim                  | 3        | 3      | 1.02%   |
| China                     | 3        | 3      | 1.02%   |
| Transcend                 | 2        | 2      | 0.68%   |
| Team                      | 2        | 2      | 0.68%   |
| OCZ                       | 2        | 2      | 0.68%   |
| Micron/Crucial Technology | 2        | 3      | 0.68%   |
| Micron Technology         | 2        | 2      | 0.68%   |
| Maxtor                    | 2        | 2      | 0.68%   |
| LITEON                    | 2        | 2      | 0.68%   |
| WDS100T1                  | 1        | 1      | 0.34%   |
| USB3.0                    | 1        | 1      | 0.34%   |
| Unknown                   | 1        | 1      | 0.34%   |
| Union Memory (Shenzhen)   | 1        | 1      | 0.34%   |
| Silicon Motion            | 1        | 2      | 0.34%   |
| PNY                       | 1        | 1      | 0.34%   |
| Palit                     | 1        | 1      | 0.34%   |
| Netac                     | 1        | 1      | 0.34%   |
| MaxDigital                | 1        | 1      | 0.34%   |
| KIOXIA                    | 1        | 2      | 0.34%   |
| KingSpec                  | 1        | 1      | 0.34%   |
| KingDian                  | 1        | 1      | 0.34%   |
| KESU                      | 1        | 1      | 0.34%   |
| JMicron Technology        | 1        | 1      | 0.34%   |
| Integral                  | 1        | 1      | 0.34%   |
| Hikvision                 | 1        | 1      | 0.34%   |
| HGST                      | 1        | 1      | 0.34%   |
| Hewlett-Packard           | 1        | 2      | 0.34%   |
| Fujitsu                   | 1        | 1      | 0.34%   |
| ExcelStor                 | 1        | 2      | 0.34%   |
| DRVEO                     | 1        | 1      | 0.34%   |
| Corsair                   | 1        | 2      | 0.34%   |
| ASMT                      | 1        | 1      | 0.34%   |
| Apple                     | 1        | 1      | 0.34%   |
| AMD                       | 1        | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB   | 6        | 1.69%   |
| Seagate ST8000DM004-2CX188 8TB   | 5        | 1.4%    |
| WDC WD10EURX-83UY4Y0 1TB         | 4        | 1.12%   |
| Seagate ST500DM002-1BD142 500GB  | 4        | 1.12%   |
| Seagate ST2000DL003-9VT166 2TB   | 4        | 1.12%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 3        | 0.84%   |
| WDC WD3200AAJS-60Z0A0 320GB      | 3        | 0.84%   |
| WDC WD20EZRX-00D8PB0 2TB         | 3        | 0.84%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 0.84%   |
| WDC WD10EALX-009BA0 1TB          | 3        | 0.84%   |
| Verbatim Vi550 S3 SSD 128GB      | 3        | 0.84%   |
| Toshiba DT01ACA100 1TB           | 3        | 0.84%   |
| Seagate ST3500418AS 500GB        | 3        | 0.84%   |
| Seagate ST3500312CS 500GB        | 3        | 0.84%   |
| Seagate ST31000528AS 1TB         | 3        | 0.84%   |
| Seagate Expansion Desk 4TB       | 3        | 0.84%   |
| SanDisk NVMe SSD Drive 500GB     | 3        | 0.84%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.84%   |
| Samsung SSD 860 EVO 500GB        | 3        | 0.84%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.84%   |
| Kingston SV300S37A120G 120GB SSD | 3        | 0.84%   |
| Hitachi HDS721032CLA362 320GB    | 3        | 0.84%   |
| Crucial CT500MX500SSD1 500GB     | 3        | 0.84%   |
| Crucial CT1000MX500SSD1 1TB      | 3        | 0.84%   |
| A-DATA SU650 240GB SSD           | 3        | 0.84%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.56%   |
| WDC WD5000BPKT-60PK4T0 500GB     | 2        | 0.56%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 0.56%   |
| WDC WD40EZRZ-19GXCB0 4TB         | 2        | 0.56%   |
| WDC WD2500AAKX-753CA1 250GB      | 2        | 0.56%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.56%   |
| WDC WD20EARS-00MVWB0 2TB         | 2        | 0.56%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.56%   |
| Toshiba MQ01ABD100 1TB           | 2        | 0.56%   |
| Toshiba HDWD110 1TB              | 2        | 0.56%   |
| Toshiba DT01ACA050 500GB         | 2        | 0.56%   |
| Seagate ST3160812AS 160GB        | 2        | 0.56%   |
| Seagate ST31000524AS 1TB         | 2        | 0.56%   |
| Seagate ST3000DM001-1CH166 3TB   | 2        | 0.56%   |
| Seagate ST2000LM007-1R8174 2TB   | 2        | 0.56%   |
| Samsung SSD PM851 2.5 7mm 128GB  | 2        | 0.56%   |
| Samsung SSD 970 EVO 500GB        | 2        | 0.56%   |
| Samsung SSD 870 QVO 1TB          | 2        | 0.56%   |
| Samsung SSD 860 QVO 1TB          | 2        | 0.56%   |
| Samsung SSD 860 EVO M.2 500GB    | 2        | 0.56%   |
| Samsung SSD 860 EVO 250GB        | 2        | 0.56%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.56%   |
| Samsung SSD 850 EVO 250GB        | 2        | 0.56%   |
| Samsung SSD 840 EVO 120GB        | 2        | 0.56%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 0.56%   |
| Samsung HD103SI 1TB              | 2        | 0.56%   |
| Phison Sabrent 1TB               | 2        | 0.56%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 0.56%   |
| Hitachi HDS721616PLA380 160GB    | 2        | 0.56%   |
| Crucial CT500P2SSD8 500GB        | 2        | 0.56%   |
| Crucial CT480BX500SSD1 480GB     | 2        | 0.56%   |
| Crucial CT256MX100SSD1 256GB     | 2        | 0.56%   |
| Crucial CT240M500SSD1 240GB      | 2        | 0.56%   |
| WDS100T1 X0E-00AFY0 1TB          | 1        | 0.28%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 61       | 127    | 38.85%  |
| Seagate             | 53       | 100    | 33.76%  |
| Toshiba             | 16       | 22     | 10.19%  |
| Hitachi             | 12       | 22     | 7.64%   |
| Samsung Electronics | 7        | 8      | 4.46%   |
| Maxtor              | 2        | 2      | 1.27%   |
| Unknown             | 1        | 1      | 0.64%   |
| KESU                | 1        | 1      | 0.64%   |
| HGST                | 1        | 1      | 0.64%   |
| Fujitsu             | 1        | 1      | 0.64%   |
| ExcelStor           | 1        | 2      | 0.64%   |
| ASMT                | 1        | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 26       | 38     | 25.24%  |
| Crucial             | 19       | 21     | 18.45%  |
| Kingston            | 9        | 12     | 8.74%   |
| SanDisk             | 7        | 10     | 6.8%    |
| A-DATA Technology   | 6        | 10     | 5.83%   |
| WDC                 | 5        | 8      | 4.85%   |
| Intel               | 4        | 4      | 3.88%   |
| Verbatim            | 3        | 3      | 2.91%   |
| China               | 3        | 3      | 2.91%   |
| Transcend           | 2        | 2      | 1.94%   |
| Team                | 2        | 2      | 1.94%   |
| OCZ                 | 2        | 2      | 1.94%   |
| LITEON              | 2        | 2      | 1.94%   |
| USB3.0              | 1        | 1      | 0.97%   |
| PNY                 | 1        | 1      | 0.97%   |
| Palit               | 1        | 1      | 0.97%   |
| Netac               | 1        | 1      | 0.97%   |
| Micron Technology   | 1        | 1      | 0.97%   |
| KingSpec            | 1        | 1      | 0.97%   |
| KingDian            | 1        | 1      | 0.97%   |
| Integral            | 1        | 1      | 0.97%   |
| Hikvision           | 1        | 1      | 0.97%   |
| Hewlett-Packard     | 1        | 2      | 0.97%   |
| DRVEO               | 1        | 1      | 0.97%   |
| Corsair             | 1        | 2      | 0.97%   |
| Apple               | 1        | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 110      | 288    | 48.03%  |
| SSD     | 84       | 132    | 36.68%  |
| NVMe    | 31       | 56     | 13.54%  |
| Unknown | 4        | 4      | 1.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 140      | 407    | 75.68%  |
| NVMe | 31       | 56     | 16.76%  |
| SAS  | 14       | 17     | 7.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 105      | 210    | 46.05%  |
| 0.51-1.0   | 71       | 115    | 31.14%  |
| 1.01-2.0   | 22       | 32     | 9.65%   |
| 3.01-4.0   | 14       | 30     | 6.14%   |
| 2.01-3.0   | 8        | 11     | 3.51%   |
| 4.01-10.0  | 8        | 22     | 3.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 31       | 18.9%   |
| 251-500        | 26       | 15.85%  |
| 501-1000       | 26       | 15.85%  |
| More than 3000 | 23       | 14.02%  |
| 1001-2000      | 14       | 8.54%   |
| 51-100         | 14       | 8.54%   |
| 2001-3000      | 10       | 6.1%    |
| 1-20           | 9        | 5.49%   |
| Unknown        | 8        | 4.88%   |
| 21-50          | 3        | 1.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 51       | 30.91%  |
| 101-250        | 21       | 12.73%  |
| 501-1000       | 20       | 12.12%  |
| 51-100         | 19       | 11.52%  |
| 21-50          | 13       | 7.88%   |
| More than 3000 | 11       | 6.67%   |
| 251-500        | 9        | 5.45%   |
| Unknown        | 8        | 4.85%   |
| 2001-3000      | 7        | 4.24%   |
| 1001-2000      | 6        | 3.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                  | 3        | 8      | 7.69%   |
| Seagate ST2000DL003-9VT166 2TB           | 3        | 5      | 7.69%   |
| WDC WD2500AAKX-753CA1 250GB              | 2        | 3      | 5.13%   |
| WDC WD7500BPKX-00HPJT0 752GB             | 1        | 1      | 2.56%   |
| WDC WD5000BEVT-35A0RT0 500GB             | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-001CA0 500GB              | 1        | 1      | 2.56%   |
| WDC WD400JB-00FMA0 40GB                  | 1        | 2      | 2.56%   |
| WDC WD3200AVJS-63B6A0 320GB              | 1        | 1      | 2.56%   |
| WDC WD2500BEKT-75A25T0 250GB             | 1        | 1      | 2.56%   |
| WDC WD2500AAKX-603CA0 250GB              | 1        | 1      | 2.56%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1        | 1      | 2.56%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1        | 1      | 2.56%   |
| WDC WD1001FALS-00E8B0 1TB                | 1        | 2      | 2.56%   |
| Toshiba MK1059GSM 1TB                    | 1        | 1      | 2.56%   |
| Toshiba DT01ACA050 500GB                 | 1        | 1      | 2.56%   |
| Seagate ST4000DX001-1CE168 4TB           | 1        | 1      | 2.56%   |
| Seagate ST3500418AS 500GB                | 1        | 2      | 2.56%   |
| Seagate ST31500541AS 1TB                 | 1        | 1      | 2.56%   |
| Seagate ST3120026A 120GB                 | 1        | 1      | 2.56%   |
| Seagate ST31000333AS 1TB                 | 1        | 2      | 2.56%   |
| Seagate ST3000DM001-1ER166 3TB           | 1        | 1      | 2.56%   |
| Samsung Electronics SSD 970 EVO Plus 2TB | 1        | 1      | 2.56%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 2.56%   |
| Netac SSD 128GB                          | 1        | 1      | 2.56%   |
| Micron Technology 2300 NVMe 512GB        | 1        | 1      | 2.56%   |
| Maxtor STM3250310AS 250GB                | 1        | 1      | 2.56%   |
| Intel SSDSA2M080G2GC 80GB                | 1        | 1      | 2.56%   |
| Hitachi HUS724030ALA640 3TB              | 1        | 2      | 2.56%   |
| Hitachi HDT721016SLA380 160GB            | 1        | 2      | 2.56%   |
| Hitachi HDS721010CLA332 1TB              | 1        | 1      | 2.56%   |
| HGST HTS541010A7E630 1TB                 | 1        | 1      | 2.56%   |
| DRVEO X1 SSD 480GB                       | 1        | 1      | 2.56%   |
| China T480 480GB SSD                     | 1        | 1      | 2.56%   |
| A-DATA Technology SU800 128GB SSD        | 1        | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 23     | 33.33%  |
| Seagate             | 9        | 13     | 25%     |
| Hitachi             | 3        | 5      | 8.33%   |
| Toshiba             | 2        | 2      | 5.56%   |
| Samsung Electronics | 2        | 2      | 5.56%   |
| Netac               | 1        | 1      | 2.78%   |
| Micron Technology   | 1        | 1      | 2.78%   |
| Maxtor              | 1        | 1      | 2.78%   |
| Intel               | 1        | 1      | 2.78%   |
| HGST                | 1        | 1      | 2.78%   |
| DRVEO               | 1        | 1      | 2.78%   |
| China               | 1        | 1      | 2.78%   |
| A-DATA Technology   | 1        | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 23     | 41.38%  |
| Seagate             | 9        | 13     | 31.03%  |
| Hitachi             | 3        | 5      | 10.34%  |
| Toshiba             | 2        | 2      | 6.9%    |
| Samsung Electronics | 1        | 1      | 3.45%   |
| Maxtor              | 1        | 1      | 3.45%   |
| HGST                | 1        | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 46     | 76.67%  |
| SSD  | 5        | 5      | 16.67%  |
| NVMe | 2        | 2      | 6.67%   |

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
| Detected | 87       | 264    | 49.71%  |
| Works    | 59       | 163    | 33.71%  |
| Malfunc  | 29       | 53     | 16.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 88       | 42.72%  |
| AMD                          | 51       | 24.76%  |
| Samsung Electronics          | 13       | 6.31%   |
| Marvell Technology Group     | 8        | 3.88%   |
| ASMedia Technology           | 8        | 3.88%   |
| SanDisk                      | 7        | 3.4%    |
| JMicron Technology           | 5        | 2.43%   |
| Phison Electronics           | 4        | 1.94%   |
| Nvidia                       | 4        | 1.94%   |
| Micron/Crucial Technology    | 4        | 1.94%   |
| LSI Logic / Symbios Logic    | 3        | 1.46%   |
| Toshiba America Info Systems | 2        | 0.97%   |
| Union Memory (Shenzhen)      | 1        | 0.49%   |
| ULi Electronics              | 1        | 0.49%   |
| Silicon Motion               | 1        | 0.49%   |
| Seagate Technology           | 1        | 0.49%   |
| Realtek Semiconductor        | 1        | 0.49%   |
| Micron Technology            | 1        | 0.49%   |
| KIOXIA                       | 1        | 0.49%   |
| Kingston Technology Company  | 1        | 0.49%   |
| Broadcom / LSI               | 1        | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 35       | 12.73%  |
| AMD 400 Series Chipset SATA Controller                                                  | 16       | 5.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15       | 5.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 4%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 2.91%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.91%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 2.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 2.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 2.18%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 1.82%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 1.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.45%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 1.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.09%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.09%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.09%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.73%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.73%   |
| Phison E12 NVMe Controller                                                              | 2        | 0.73%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.73%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.73%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.73%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.73%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 2        | 0.73%   |
| Marvell Group 88SE9182 PCIe 2.0 x2 2-port SATA 6 Gb/s Controller                        | 2        | 0.73%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 2        | 0.73%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 2        | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.73%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.73%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.73%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.73%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.73%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 0.73%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1        | 0.36%   |
| ULi ULi M5288 SATA                                                                      | 1        | 0.36%   |
| ULi M5229 IDE                                                                           | 1        | 0.36%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.36%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1        | 0.36%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.36%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 0.36%   |
| SanDisk WD Blue SN570 NVMe SSD                                                          | 1        | 0.36%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.36%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.36%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.36%   |
| Samsung Apple PCIe SSD                                                                  | 1        | 0.36%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.36%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 121      | 59.31%  |
| IDE  | 42       | 20.59%  |
| NVMe | 31       | 15.2%   |
| RAID | 8        | 3.92%   |
| SCSI | 2        | 0.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 93       | 62.84%  |
| AMD    | 55       | 37.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 7        | 4.64%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 5        | 3.31%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 4        | 2.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 4        | 2.65%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 4        | 2.65%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 4        | 2.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 3        | 1.99%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 3        | 1.99%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 3        | 1.99%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 3        | 1.99%   |
| AMD Athlon II X4 620 Processor                 | 3        | 1.99%   |
| Intel Xeon CPU X5690 @ 3.47GHz                 | 2        | 1.32%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 2        | 1.32%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 2        | 1.32%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 2        | 1.32%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 2        | 1.32%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 2        | 1.32%   |
| Intel Core i5-10500 CPU @ 3.10GHz              | 2        | 1.32%   |
| Intel Core i3-4150 CPU @ 3.50GHz               | 2        | 1.32%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 1.32%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz          | 2        | 1.32%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 2        | 1.32%   |
| AMD Ryzen Embedded V1605B with Radeon Vega Gfx | 2        | 1.32%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 1.32%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 1.32%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 1.32%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 2        | 1.32%   |
| AMD FX-6300 Six-Core Processor                 | 2        | 1.32%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+     | 2        | 1.32%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 0.66%   |
| Intel Xeon CPU E5462 @ 2.80GHz                 | 1        | 0.66%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz            | 1        | 0.66%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz            | 1        | 0.66%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz       | 1        | 0.66%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 1        | 0.66%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 1        | 0.66%   |
| Intel Pentium D CPU 2.80GHz                    | 1        | 0.66%   |
| Intel Pentium CPU G630 @ 2.70GHz               | 1        | 0.66%   |
| Intel Pentium CPU G2030 @ 3.00GHz              | 1        | 0.66%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 0.66%   |
| Intel Pentium 4 CPU 3.00GHz                    | 1        | 0.66%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 1        | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 0.66%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 0.66%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 0.66%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 1        | 0.66%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 0.66%   |
| Intel Core i7 CPU 960 @ 3.20GHz                | 1        | 0.66%   |
| Intel Core i7 CPU 950 @ 3.07GHz                | 1        | 0.66%   |
| Intel Core i7 CPU 860 @ 2.80GHz                | 1        | 0.66%   |
| Intel Core i5-8600K CPU @ 3.60GHz              | 1        | 0.66%   |
| Intel Core i5-8500T CPU @ 2.10GHz              | 1        | 0.66%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 0.66%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 1        | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1        | 0.66%   |
| Intel Core i5-4670 CPU @ 3.40GHz               | 1        | 0.66%   |
| Intel Core i5-4570S CPU @ 2.90GHz              | 1        | 0.66%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 0.66%   |
| Intel Core i5-4460S CPU @ 2.90GHz              | 1        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 31       | 20.53%  |
| Intel Core i7           | 23       | 15.23%  |
| AMD Ryzen 5             | 17       | 11.26%  |
| Intel Core i3           | 13       | 8.61%   |
| Intel Core 2 Quad       | 7        | 4.64%   |
| Intel Xeon              | 6        | 3.97%   |
| AMD Ryzen 9             | 5        | 3.31%   |
| AMD FX                  | 5        | 3.31%   |
| AMD Athlon 64 X2        | 5        | 3.31%   |
| Intel Core 2 Duo        | 3        | 1.99%   |
| Intel Celeron           | 3        | 1.99%   |
| AMD Ryzen 7             | 3        | 1.99%   |
| AMD Ryzen 3             | 3        | 1.99%   |
| AMD Athlon II X4        | 3        | 1.99%   |
| Intel Pentium Dual-Core | 2        | 1.32%   |
| Intel Pentium 4         | 2        | 1.32%   |
| Intel Pentium           | 2        | 1.32%   |
| Intel Atom              | 2        | 1.32%   |
| AMD Ryzen Threadripper  | 2        | 1.32%   |
| AMD Ryzen Embedded      | 2        | 1.32%   |
| AMD Phenom II X6        | 2        | 1.32%   |
| AMD A6                  | 2        | 1.32%   |
| AMD A4                  | 2        | 1.32%   |
| Intel Pentium Silver    | 1        | 0.66%   |
| Intel Pentium D         | 1        | 0.66%   |
| AMD PRO A10             | 1        | 0.66%   |
| AMD Phenom II X4        | 1        | 0.66%   |
| AMD Athlon II X2        | 1        | 0.66%   |
| AMD Athlon Dual Core    | 1        | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 73       | 48.99%  |
| 2       | 29       | 19.46%  |
| 6       | 24       | 16.11%  |
| 12      | 8        | 5.37%   |
| 1       | 6        | 4.03%   |
| 8       | 5        | 3.36%   |
| 3       | 2        | 1.34%   |
| 32      | 1        | 0.67%   |
| Unknown | 1        | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 145      | 97.97%  |
| 2      | 3        | 2.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 81       | 53.64%  |
| 1       | 69       | 45.7%   |
| Unknown | 1        | 0.66%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 145      | 97.97%  |
| Unknown        | 3        | 2.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 25.33%  |
| 0x306c3    | 13       | 8.67%   |
| 0x306a9    | 13       | 8.67%   |
| 0x206a7    | 13       | 8.67%   |
| 0x1067a    | 8        | 5.33%   |
| 0x08701021 | 6        | 4%      |
| 0x0800820d | 4        | 2.67%   |
| 0xa0653    | 3        | 2%      |
| 0x906ea    | 3        | 2%      |
| 0x206c2    | 3        | 2%      |
| 0x08108109 | 3        | 2%      |
| 0x0810100b | 3        | 2%      |
| 0x06000852 | 3        | 2%      |
| 0x6fb      | 2        | 1.33%   |
| 0x30661    | 2        | 1.33%   |
| 0x106a5    | 2        | 1.33%   |
| 0x08701013 | 2        | 1.33%   |
| 0x0600611a | 2        | 1.33%   |
| 0x010000db | 2        | 1.33%   |
| 0x010000c8 | 2        | 1.33%   |
| 0xf47      | 1        | 0.67%   |
| 0xf43      | 1        | 0.67%   |
| 0xf41      | 1        | 0.67%   |
| 0x906ed    | 1        | 0.67%   |
| 0x906eb    | 1        | 0.67%   |
| 0x906e9    | 1        | 0.67%   |
| 0x706a1    | 1        | 0.67%   |
| 0x6f7      | 1        | 0.67%   |
| 0x506e3    | 1        | 0.67%   |
| 0x306e4    | 1        | 0.67%   |
| 0x30678    | 1        | 0.67%   |
| 0x106e5    | 1        | 0.67%   |
| 0x10677    | 1        | 0.67%   |
| 0x10676    | 1        | 0.67%   |
| 0x0a201205 | 1        | 0.67%   |
| 0x0a201016 | 1        | 0.67%   |
| 0x08301039 | 1        | 0.67%   |
| 0x08101016 | 1        | 0.67%   |
| 0x08001126 | 1        | 0.67%   |
| 0x06003104 | 1        | 0.67%   |
| 0x06001119 | 1        | 0.67%   |
| 0x010000bf | 1        | 0.67%   |
| 0x01000086 | 1        | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 18       | 12.08%  |
| IvyBridge     | 18       | 12.08%  |
| Haswell       | 16       | 10.74%  |
| Zen+          | 12       | 8.05%   |
| Zen 2         | 12       | 8.05%   |
| Penryn        | 10       | 6.71%   |
| KabyLake      | 8        | 5.37%   |
| K10           | 7        | 4.7%    |
| Zen           | 6        | 4.03%   |
| Piledriver    | 6        | 4.03%   |
| K8 Hammer     | 6        | 4.03%   |
| Nehalem       | 5        | 3.36%   |
| Westmere      | 3        | 2.01%   |
| NetBurst      | 3        | 2.01%   |
| Core          | 3        | 2.01%   |
| CometLake     | 3        | 2.01%   |
| Zen 3         | 2        | 1.34%   |
| Skylake       | 2        | 1.34%   |
| Goldmont plus | 2        | 1.34%   |
| Excavator     | 2        | 1.34%   |
| Bonnell       | 2        | 1.34%   |
| Steamroller   | 1        | 0.67%   |
| Silvermont    | 1        | 0.67%   |
| Bulldozer     | 1        | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 63       | 37.95%  |
| Nvidia | 56       | 33.73%  |
| Intel  | 47       | 28.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 8%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8        | 4.57%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 7        | 4%      |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 3.43%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 2.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 2.86%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.29%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 4        | 2.29%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 1.71%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.71%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.71%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 3        | 1.71%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 1.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.71%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.71%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.71%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.14%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.14%   |
| Intel HD Graphics 630                                                       | 2        | 1.14%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 1.14%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 2        | 1.14%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 1.14%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.14%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.57%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.57%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.57%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.57%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.57%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.57%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.57%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.57%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 0.57%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.57%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.57%   |
| Nvidia GK208B [GeForce GT 720]                                              | 1        | 0.57%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.57%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                           | 1        | 0.57%   |
| Nvidia GF110GL [Tesla C2050 / C2075]                                        | 1        | 0.57%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.57%   |
| Nvidia GF108 [GeForce GT 530]                                               | 1        | 0.57%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 0.57%   |
| Nvidia GF100GL [Quadro 6000]                                                | 1        | 0.57%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 0.57%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.57%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 0.57%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 0.57%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.57%   |
| Nvidia G80 [GeForce 8800 GTX]                                               | 1        | 0.57%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 0.57%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 0.57%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 0.57%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 1        | 0.57%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 56       | 36.6%   |
| 1 x Nvidia     | 52       | 33.99%  |
| 1 x Intel      | 35       | 22.88%  |
| 2 x AMD        | 6        | 3.92%   |
| Intel + Nvidia | 3        | 1.96%   |
| AMD + Nvidia   | 1        | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 118      | 77.12%  |
| Proprietary | 27       | 17.65%  |
| Unknown     | 8        | 5.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 38.85%  |
| 0.51-1.0   | 23       | 14.65%  |
| 1.01-2.0   | 20       | 12.74%  |
| 7.01-8.0   | 16       | 10.19%  |
| 3.01-4.0   | 14       | 8.92%   |
| 0.01-0.5   | 10       | 6.37%   |
| 5.01-6.0   | 8        | 5.1%    |
| 2.01-3.0   | 2        | 1.27%   |
| 8.01-16.0  | 2        | 1.27%   |
| 16.01-24.0 | 1        | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 32       | 20.92%  |
| Samsung Electronics  | 15       | 9.8%    |
| Acer                 | 14       | 9.15%   |
| BenQ                 | 12       | 7.84%   |
| Hewlett-Packard      | 11       | 7.19%   |
| Goldstar             | 10       | 6.54%   |
| Iiyama               | 9        | 5.88%   |
| Philips              | 8        | 5.23%   |
| AOC                  | 5        | 3.27%   |
| Ancor Communications | 4        | 2.61%   |
| Vestel Elektronik    | 3        | 1.96%   |
| HannStar             | 3        | 1.96%   |
| Apple                | 3        | 1.96%   |
| ___                  | 2        | 1.31%   |
| ViewSonic            | 2        | 1.31%   |
| Unknown              | 2        | 1.31%   |
| Sony                 | 2        | 1.31%   |
| MiTAC                | 2        | 1.31%   |
| Toshiba              | 1        | 0.65%   |
| Targa Visionary      | 1        | 0.65%   |
| Targa                | 1        | 0.65%   |
| RTK                  | 1        | 0.65%   |
| OEM                  | 1        | 0.65%   |
| NEC Computers        | 1        | 0.65%   |
| MSI                  | 1        | 0.65%   |
| Medion               | 1        | 0.65%   |
| Lenovo               | 1        | 0.65%   |
| HYO                  | 1        | 0.65%   |
| HUAWEI               | 1        | 0.65%   |
| HKC                  | 1        | 0.65%   |
| ASUSTek Computer     | 1        | 0.65%   |
| Unknown              | 1        | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                  | 5        | 2.91%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 4        | 2.33%   |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 3        | 1.74%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                      | 3        | 1.74%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch               | 3        | 1.74%   |
| ___ LCD TV ___9000 1360x768                                           | 2        | 1.16%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 2        | 1.16%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2        | 1.16%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 2        | 1.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2        | 1.16%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                     | 2        | 1.16%   |
| Dell E171FP DEL300F 1280x1024 340x270mm 17.1-inch                     | 2        | 1.16%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 2        | 1.16%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch               | 2        | 1.16%   |
| Apple LED Cinema APP9236 1920x1200 518x324mm 24.1-inch                | 2        | 1.16%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 608x355mm 27.7-inch         | 1        | 0.58%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1        | 0.58%   |
| Toshiba TV TSB1206 1360x768                                           | 1        | 0.58%   |
| Targa Visionary LCD22-1 Wide TARA229 1680x1050 474x297mm 22.0-inch    | 1        | 0.58%   |
| Targa LCD Monitor LCDTV16 1360x768                                    | 1        | 0.58%   |
| Sony TV SNY4302 1920x1080                                             | 1        | 0.58%   |
| Sony SDM-HS95P SNY2600 1280x1024 376x301mm 19.0-inch                  | 1        | 0.58%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch  | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch  | 1        | 0.58%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 1        | 0.58%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 1        | 0.58%   |
| Samsung Electronics S24C300 SAM0A28 1920x1080 531x299mm 24.0-inch     | 1        | 0.58%   |
| Samsung Electronics S19E200 SAM0C69 1440x900 408x255mm 18.9-inch      | 1        | 0.58%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch      | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SAM067C 1920x1080                     | 1        | 0.58%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch     | 1        | 0.58%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1        | 0.58%   |
| Philips PHL 275E1 PHLC20C 2560x1440 597x336mm 27.0-inch               | 1        | 0.58%   |
| Philips PhilipsTV (5) PHL14CA 1360x768 708x398mm 32.0-inch            | 1        | 0.58%   |
| Philips LCD Monitor FTV 1920x1080                                     | 1        | 0.58%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1        | 0.58%   |
| OEM LCD Monitor 19W_LCD_TV                                            | 1        | 0.58%   |
| NEC Computers LCD1980SX NEC6626 1280x1024 376x301mm 19.0-inch         | 1        | 0.58%   |
| MSI Optix MAG24C MSI1462 1920x1080 520x290mm 23.4-inch                | 1        | 0.58%   |
| MiTAC Smart TV SZM0030 1920x1080 708x398mm 32.0-inch                  | 1        | 0.58%   |
| MiTAC MTC26T42 MTC0B01 1920x540 708x398mm 32.0-inch                   | 1        | 0.58%   |
| Medion MD 20999 MED3694 1920x1080 510x290mm 23.1-inch                 | 1        | 0.58%   |
| Medion MD 20999 MED3693 1920x1080 509x286mm 23.0-inch                 | 1        | 0.58%   |
| Lenovo L24e-30 LEN66BC 1920x1080 527x296mm 23.8-inch                  | 1        | 0.58%   |
| Iiyama PLT2454M IVM613F 1920x1080 527x296mm 23.8-inch                 | 1        | 0.58%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch               | 1        | 0.58%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                  | 1        | 0.58%   |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                  | 1        | 0.58%   |
| HYO DUAL-DVI HYO049B 2560x1440 597x336mm 27.0-inch                    | 1        | 0.58%   |
| HUAWEI XWU-CBA HWV62F5 2560x1440 597x336mm 27.0-inch                  | 1        | 0.58%   |
| HKC LCD Monitor TV 1360x768                                           | 1        | 0.58%   |
| Hewlett-Packard LA2205 HWP2849 1680x1050 470x300mm 22.0-inch          | 1        | 0.58%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch          | 1        | 0.58%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch            | 1        | 0.58%   |
| Hewlett-Packard E271i HWP3106 1920x1080 600x340mm 27.2-inch           | 1        | 0.58%   |
| Hewlett-Packard E243i HPN3463 1920x1200 518x324mm 24.1-inch           | 1        | 0.58%   |
| Hewlett-Packard E243i HPN3462 1920x1200 518x324mm 24.1-inch           | 1        | 0.58%   |
| Hewlett-Packard E241i HWP3123 1920x1200 518x324mm 24.1-inch           | 1        | 0.58%   |
| Hewlett-Packard E222 HWP3261 1920x1080 476x268mm 21.5-inch            | 1        | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 72       | 47.37%  |
| 3840x2160 (4K)     | 11       | 7.24%   |
| 2560x1440 (QHD)    | 11       | 7.24%   |
| 1280x1024 (SXGA)   | 9        | 5.92%   |
| 1366x768 (WXGA)    | 6        | 3.95%   |
| 1920x1200 (WUXGA)  | 5        | 3.29%   |
| 1440x900 (WXGA+)   | 5        | 3.29%   |
| 1360x768           | 5        | 3.29%   |
| Unknown            | 5        | 3.29%   |
| 1680x1050 (WSXGA+) | 4        | 2.63%   |
| 1600x900 (HD+)     | 4        | 2.63%   |
| 3840x1080          | 3        | 1.97%   |
| 3440x1440          | 3        | 1.97%   |
| 1024x768 (XGA)     | 2        | 1.32%   |
| 6400x2160          | 1        | 0.66%   |
| 5280x2560          | 1        | 0.66%   |
| 4480x1440          | 1        | 0.66%   |
| 3600x1080          | 1        | 0.66%   |
| 2560x1080          | 1        | 0.66%   |
| 1920x540           | 1        | 0.66%   |
| 1600x1200          | 1        | 0.66%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 27       | 18.12%  |
| 24      | 22       | 14.77%  |
| 23      | 21       | 14.09%  |
| 21      | 17       | 11.41%  |
| Unknown | 13       | 8.72%   |
| 19      | 10       | 6.71%   |
| 31      | 6        | 4.03%   |
| 18      | 5        | 3.36%   |
| 17      | 4        | 2.68%   |
| 84      | 3        | 2.01%   |
| 72      | 3        | 2.01%   |
| 34      | 3        | 2.01%   |
| 32      | 3        | 2.01%   |
| 22      | 3        | 2.01%   |
| 20      | 3        | 2.01%   |
| 15      | 2        | 1.34%   |
| 49      | 1        | 0.67%   |
| 46      | 1        | 0.67%   |
| 35      | 1        | 0.67%   |
| 25      | 1        | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 64       | 43.84%  |
| 401-500     | 34       | 23.29%  |
| Unknown     | 13       | 8.9%    |
| 601-700     | 9        | 6.16%   |
| 701-800     | 6        | 4.11%   |
| 301-350     | 6        | 4.11%   |
| 1501-2000   | 6        | 4.11%   |
| 351-400     | 5        | 3.42%   |
| 1001-1500   | 2        | 1.37%   |
| 801-900     | 1        | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 93       | 68.89%  |
| 16/10   | 14       | 10.37%  |
| Unknown | 10       | 7.41%   |
| 5/4     | 9        | 6.67%   |
| 21/9    | 4        | 2.96%   |
| 4/3     | 3        | 2.22%   |
| 32/9    | 1        | 0.74%   |
| 3/2     | 1        | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 50       | 32.89%  |
| 301-350        | 27       | 17.76%  |
| 151-200        | 19       | 12.5%   |
| 351-500        | 13       | 8.55%   |
| Unknown        | 13       | 8.55%   |
| 251-300        | 12       | 7.89%   |
| 141-150        | 8        | 5.26%   |
| More than 1000 | 6        | 3.95%   |
| 101-110        | 2        | 1.32%   |
| 501-1000       | 2        | 1.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 84       | 59.15%  |
| 101-120 | 29       | 20.42%  |
| Unknown | 13       | 9.15%   |
| 1-50    | 8        | 5.63%   |
| 161-240 | 4        | 2.82%   |
| 121-160 | 4        | 2.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 112      | 71.79%  |
| 2     | 32       | 20.51%  |
| 0     | 8        | 5.13%   |
| 3     | 4        | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 76       | 34.39%  |
| Realtek Semiconductor             | 75       | 33.94%  |
| Qualcomm Atheros                  | 12       | 5.43%   |
| Broadcom                          | 9        | 4.07%   |
| Ralink Technology                 | 8        | 3.62%   |
| Ralink                            | 7        | 3.17%   |
| TP-Link                           | 5        | 2.26%   |
| Microsoft                         | 5        | 2.26%   |
| Nvidia                            | 3        | 1.36%   |
| Marvell Technology Group          | 3        | 1.36%   |
| Broadcom Limited                  | 3        | 1.36%   |
| Belkin Components                 | 2        | 0.9%    |
| Van Ooijen Technische Informatica | 1        | 0.45%   |
| ULi Electronics                   | 1        | 0.45%   |
| Samsung Electronics               | 1        | 0.45%   |
| Qualcomm Atheros Communications   | 1        | 0.45%   |
| NetXen Incorporated               | 1        | 0.45%   |
| NetGear                           | 1        | 0.45%   |
| JMicron Technology                | 1        | 0.45%   |
| IMC Networks                      | 1        | 0.45%   |
| Huawei Technologies               | 1        | 0.45%   |
| HMD Global                        | 1        | 0.45%   |
| DisplayLink                       | 1        | 0.45%   |
| ASUSTek Computer                  | 1        | 0.45%   |
| ADMtek                            | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 62       | 24.51%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 16       | 6.32%   |
| Intel Wi-Fi 6 AX200                                                 | 12       | 4.74%   |
| Intel I211 Gigabit Network Connection                               | 10       | 3.95%   |
| Realtek 802.11ac NIC                                                | 8        | 3.16%   |
| Intel Wireless-AC 9260                                              | 7        | 2.77%   |
| Intel Ethernet Connection I217-LM                                   | 6        | 2.37%   |
| Ralink MT7601U Wireless Adapter                                     | 5        | 1.98%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 5        | 1.98%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 5        | 1.98%   |
| Intel 82579V Gigabit Network Connection                             | 4        | 1.58%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 3        | 1.19%   |
| Intel Ethernet Connection I217-V                                    | 3        | 1.19%   |
| Intel Ethernet Connection (2) I218-V                                | 3        | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 3        | 1.19%   |
| TP-Link 802.11ac WLAN Adapter                                       | 2        | 0.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 2        | 0.79%   |
| Ralink RT5370 Wireless Adapter                                      | 2        | 0.79%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 2        | 0.79%   |
| Intel Wireless 7265                                                 | 2        | 0.79%   |
| Intel I210 Gigabit Network Connection                               | 2        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                | 2        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                                | 2        | 0.79%   |
| Intel 82583V Gigabit Network Connection                             | 2        | 0.79%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express             | 2        | 0.79%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express     | 2        | 0.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 2        | 0.79%   |
| Van Ooijen Technische Informatica XCM Board                         | 1        | 0.4%    |
| ULi ULi 1689,1573 integrated ethernet.                              | 1        | 0.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.4%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.4%    |
| TP-Link 802.11ac NIC                                                | 1        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.4%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 1        | 0.4%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1        | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                          | 1        | 0.4%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 0.4%    |
| Realtek RTL8125 2.5GbE Controller                                   | 1        | 0.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.4%    |
| Ralink Wireless Adapter Canyon CN-WF511                             | 1        | 0.4%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 1        | 0.4%    |
| Ralink RT5592 PCIe Wireless Network Adapter                         | 1        | 0.4%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 1        | 0.4%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                           | 1        | 0.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 0.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 1        | 0.4%    |
| Qualcomm Atheros AR9271 802.11n                                     | 1        | 0.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 0.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 1        | 0.4%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 1        | 0.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 26       | 29.21%  |
| Realtek Semiconductor           | 17       | 19.1%   |
| Qualcomm Atheros                | 11       | 12.36%  |
| Ralink Technology               | 8        | 8.99%   |
| Ralink                          | 7        | 7.87%   |
| TP-Link                         | 5        | 5.62%   |
| Microsoft                       | 5        | 5.62%   |
| Broadcom                        | 3        | 3.37%   |
| Belkin Components               | 2        | 2.25%   |
| Qualcomm Atheros Communications | 1        | 1.12%   |
| NetGear                         | 1        | 1.12%   |
| IMC Networks                    | 1        | 1.12%   |
| Broadcom Limited                | 1        | 1.12%   |
| ASUSTek Computer                | 1        | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 12       | 13.19%  |
| Realtek 802.11ac NIC                                                          | 8        | 8.79%   |
| Intel Wireless-AC 9260                                                        | 7        | 7.69%   |
| Ralink MT7601U Wireless Adapter                                               | 5        | 5.49%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 5        | 5.49%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 3        | 3.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 3.3%    |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 2.2%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 2.2%    |
| Ralink RT5370 Wireless Adapter                                                | 2        | 2.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 2.2%    |
| Intel Wireless 7265                                                           | 2        | 2.2%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 2        | 2.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 1.1%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1        | 1.1%    |
| TP-Link 802.11ac NIC                                                          | 1        | 1.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 1.1%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 1.1%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 1.1%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1        | 1.1%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1        | 1.1%    |
| Ralink Wireless Adapter Canyon CN-WF511                                       | 1        | 1.1%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 1.1%    |
| Ralink RT5592 PCIe Wireless Network Adapter                                   | 1        | 1.1%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 1        | 1.1%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1        | 1.1%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.1%    |
| NetGear A6210                                                                 | 1        | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1        | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 1        | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 1.1%    |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                          | 1        | 1.1%    |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1        | 1.1%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 1.1%    |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]        | 1        | 1.1%    |
| Belkin Components F5D7050 Wireless G Adapter v5000 [Realtek RTL8187B]         | 1        | 1.1%    |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]                      | 1        | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 66       | 42.58%  |
| Intel                    | 64       | 41.29%  |
| Broadcom                 | 7        | 4.52%   |
| Nvidia                   | 3        | 1.94%   |
| Marvell Technology Group | 3        | 1.94%   |
| Qualcomm Atheros         | 2        | 1.29%   |
| Broadcom Limited         | 2        | 1.29%   |
| ULi Electronics          | 1        | 0.65%   |
| Samsung Electronics      | 1        | 0.65%   |
| NetXen Incorporated      | 1        | 0.65%   |
| JMicron Technology       | 1        | 0.65%   |
| Huawei Technologies      | 1        | 0.65%   |
| HMD Global               | 1        | 0.65%   |
| DisplayLink              | 1        | 0.65%   |
| ADMtek                   | 1        | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 62       | 38.51%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16       | 9.94%   |
| Intel I211 Gigabit Network Connection                                          | 10       | 6.21%   |
| Intel Ethernet Connection I217-LM                                              | 6        | 3.73%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 5        | 3.11%   |
| Intel 82579V Gigabit Network Connection                                        | 4        | 2.48%   |
| Intel Ethernet Connection I217-V                                               | 3        | 1.86%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 1.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2        | 1.24%   |
| Intel I210 Gigabit Network Connection                                          | 2        | 1.24%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1.24%   |
| Intel Ethernet Connection (2) I219-V                                           | 2        | 1.24%   |
| Intel 82583V Gigabit Network Connection                                        | 2        | 1.24%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2        | 1.24%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 2        | 1.24%   |
| ULi ULi 1689,1573 integrated ethernet.                                         | 1        | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 0.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 0.62%   |
| Nvidia MCP61 Ethernet                                                          | 1        | 0.62%   |
| Nvidia MCP55 Ethernet                                                          | 1        | 0.62%   |
| Nvidia MCP51 Ethernet Controller                                               | 1        | 0.62%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter           | 1        | 0.62%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.62%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1        | 0.62%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1        | 0.62%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1        | 0.62%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1        | 0.62%   |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.62%   |
| Intel Ethernet Controller I225-V                                               | 1        | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.62%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1        | 0.62%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.62%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1        | 0.62%   |
| Intel 82578DM Gigabit Network Connection                                       | 1        | 0.62%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 0.62%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1        | 0.62%   |
| Intel 82567LF-2 Gigabit Network Connection                                     | 1        | 0.62%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                         | 1        | 0.62%   |
| Huawei LYA-L09                                                                 | 1        | 0.62%   |
| HMD Global SDM439-QRD _SN:609DB907                                             | 1        | 0.62%   |
| DisplayLink Plugable UD-3900                                                   | 1        | 0.62%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 1        | 0.62%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 0.62%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                        | 1        | 0.62%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 1        | 0.62%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1        | 0.62%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                           | 1        | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 147      | 64.47%  |
| WiFi     | 80       | 35.09%  |
| Modem    | 1        | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 118      | 74.68%  |
| WiFi     | 40       | 25.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 93       | 62%     |
| 2     | 45       | 30%     |
| 3     | 9        | 6%      |
| 6     | 1        | 0.67%   |
| 4     | 1        | 0.67%   |
| 0     | 1        | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 139      | 93.29%  |
| Yes  | 10       | 6.71%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 24       | 41.38%  |
| Cambridge Silicon Radio         | 16       | 27.59%  |
| Broadcom                        | 6        | 10.34%  |
| ASUSTek Computer                | 4        | 6.9%    |
| Qualcomm Atheros Communications | 2        | 3.45%   |
| Apple                           | 2        | 3.45%   |
| Realtek Semiconductor           | 1        | 1.72%   |
| Dell                            | 1        | 1.72%   |
| Conwise Technology              | 1        | 1.72%   |
| Belkin Components               | 1        | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16       | 27.12%  |
| Intel AX200 Bluetooth                               | 11       | 18.64%  |
| Intel Bluetooth Device                              | 6        | 10.17%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5        | 8.47%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 5.08%   |
| Intel Bluetooth wireless interface                  | 3        | 5.08%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.69%   |
| Intel AX201 Bluetooth                               | 1        | 1.69%   |
| Dell BT Mini-Receiver                               | 1        | 1.69%   |
| Conwise CW6622                                      | 1        | 1.69%   |
| Broadcom BCM92045B3 ROM                             | 1        | 1.69%   |
| Belkin Components F8T012 Bluetooth Adapter          | 1        | 1.69%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 1.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.69%   |
| ASUS Bluetooth Device                               | 1        | 1.69%   |
| ASUS BCM20702A0                                     | 1        | 1.69%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.69%   |
| Apple Bluetooth HCI                                 | 1        | 1.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 90       | 34.35%  |
| AMD                                             | 79       | 30.15%  |
| Nvidia                                          | 53       | 20.23%  |
| Creative Labs                                   | 4        | 1.53%   |
| C-Media Electronics                             | 4        | 1.53%   |
| Plantronics                                     | 3        | 1.15%   |
| Creative Technology                             | 3        | 1.15%   |
| Texas Instruments                               | 2        | 0.76%   |
| Logitech                                        | 2        | 0.76%   |
| JMTek                                           | 2        | 0.76%   |
| Ensoniq                                         | 2        | 0.76%   |
| ULi Electronics                                 | 1        | 0.38%   |
| Turtle Beach                                    | 1        | 0.38%   |
| Sony                                            | 1        | 0.38%   |
| SAVITECH                                        | 1        | 0.38%   |
| Razer USA                                       | 1        | 0.38%   |
| Native Instruments                              | 1        | 0.38%   |
| Micronas                                        | 1        | 0.38%   |
| M-Audio                                         | 1        | 0.38%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.38%   |
| Kingston Technology                             | 1        | 0.38%   |
| GN Netcom                                       | 1        | 0.38%   |
| Giga-Byte Technology                            | 1        | 0.38%   |
| Focusrite-Novation                              | 1        | 0.38%   |
| FiiO Electronics Technology                     | 1        | 0.38%   |
| Corsair                                         | 1        | 0.38%   |
| Blue Microphones                                | 1        | 0.38%   |
| AudioQuest                                      | 1        | 0.38%   |
| Audio-Technica                                  | 1        | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 21       | 6.77%   |
| AMD Starship/Matisse HD Audio Controller                                          | 14       | 4.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 14       | 4.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 13       | 4.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 13       | 4.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 13       | 4.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12       | 3.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12       | 3.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 3.23%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 8        | 2.58%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8        | 2.58%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 7        | 2.26%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 2.26%   |
| Nvidia GM204 High Definition Audio Controller                                     | 5        | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 1.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 5        | 1.61%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 5        | 1.61%   |
| Nvidia High Definition Audio Controller                                           | 4        | 1.29%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 1.29%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 1.29%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.29%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.97%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 0.97%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 0.97%   |
| AMD Navi 10 HDMI Audio                                                            | 3        | 0.97%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 3        | 0.97%   |
| AMD FCH Azalia Controller                                                         | 3        | 0.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3        | 0.97%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2        | 0.65%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.65%   |
| JMTek USB PnP Audio Device                                                        | 2        | 0.65%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 0.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2        | 0.65%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 0.65%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                                      | 2        | 0.65%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 2        | 0.65%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 2        | 0.65%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 0.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 2        | 0.65%   |
| AMD Cayman/Antilles HDMI Audio [Radeon HD 6930/6950/6970/6990]                    | 2        | 0.65%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                        | 2        | 0.65%   |
| ULi Electronics HD Audio Controller                                               | 1        | 0.32%   |
| Turtle Beach Z22 Chat                                                             | 1        | 0.32%   |
| Sony DualSense wireless controller (PS5)                                          | 1        | 0.32%   |
| SAVITECH SA9023 audio controller                                                  | 1        | 0.32%   |
| Razer USA Nommo Chroma                                                            | 1        | 0.32%   |
| Plantronics Blackwire 5220 Series                                                 | 1        | 0.32%   |
| Plantronics Blackwire 3225 Series                                                 | 1        | 0.32%   |
| Plantronics Audio 646 DSP                                                         | 1        | 0.32%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.32%   |
| Nvidia MCP55 High Definition Audio                                                | 1        | 0.32%   |
| Nvidia MCP51 High Definition Audio                                                | 1        | 0.32%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 0.32%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 19       | 21.35%  |
| Unknown             | 14       | 15.73%  |
| Crucial             | 14       | 15.73%  |
| SK hynix            | 11       | 12.36%  |
| Kingston            | 7        | 7.87%   |
| G.Skill             | 6        | 6.74%   |
| Samsung Electronics | 4        | 4.49%   |
| Team                | 3        | 3.37%   |
| Ramaxel Technology  | 2        | 2.25%   |
| Patriot             | 2        | 2.25%   |
| Micron Technology   | 2        | 2.25%   |
| Toshiba             | 1        | 1.12%   |
| Infineon            | 1        | 1.12%   |
| Elpida              | 1        | 1.12%   |
| Apacer              | 1        | 1.12%   |
| A-DATA Technology   | 1        | 1.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 5        | 5.15%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 3        | 3.09%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 2        | 2.06%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 2        | 2.06%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                | 2        | 2.06%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s      | 2        | 2.06%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s   | 2        | 2.06%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s      | 2        | 2.06%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s     | 2        | 2.06%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s     | 2        | 2.06%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                      | 1        | 1.03%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 1.03%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                   | 1        | 1.03%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                      | 1        | 1.03%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s              | 1        | 1.03%   |
| Unknown RAM Module 2GB DIMM 667MT/s                       | 1        | 1.03%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s              | 1        | 1.03%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                    | 1        | 1.03%   |
| Unknown RAM Module 2048MB DIMM                            | 1        | 1.03%   |
| Unknown RAM Module 1GB DIMM 667MT/s                       | 1        | 1.03%   |
| Unknown RAM Module 128MB DIMM SDRAM                       | 1        | 1.03%   |
| Toshiba RAM 99U5702-094.A00G 8192MB DIMM DDR4 2400MT/s    | 1        | 1.03%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s        | 1        | 1.03%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.03%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1067MT/s             | 1        | 1.03%   |
| SK hynix RAM Module 16GB DIMM DDR3 1866MT/s               | 1        | 1.03%   |
| SK hynix RAM HYMP112U64CP8-S6 1024MB DIMM DDR 800MT/s     | 1        | 1.03%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 1.03%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s      | 1        | 1.03%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s      | 1        | 1.03%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s      | 1        | 1.03%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                 | 1        | 1.03%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s       | 1        | 1.03%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s       | 1        | 1.03%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s       | 1        | 1.03%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s   | 1        | 1.03%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8GB DIMM DDR4 2667MT/s   | 1        | 1.03%   |
| Patriot RAM PSD22G8002 2GB DIMM DDR2 800MT/s              | 1        | 1.03%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 1        | 1.03%   |
| Micron RAM Module 2048MB DIMM DDR3 1067MT/s               | 1        | 1.03%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s      | 1        | 1.03%   |
| Kingston RAM KPN424-ELG 1024MB DIMM DDR 667MT/s           | 1        | 1.03%   |
| Kingston RAM KHX1866C9D3/4GX 4GB DIMM DDR3 1867MT/s       | 1        | 1.03%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s       | 1        | 1.03%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s    | 1        | 1.03%   |
| Kingston RAM KC6844-IFA37 2GB DIMM DDR 533MT/s            | 1        | 1.03%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 1.03%   |
| Kingston RAM 9905474-050.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 1.03%   |
| Kingston RAM 9905403-518.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 1.03%   |
| Kingston RAM 9905403-198.A 4GB DIMM DDR3 667MT/s          | 1        | 1.03%   |
| Kingston RAM 2G-UDIMM 2GB DIMM DDR2 800MT/s               | 1        | 1.03%   |
| Infineon RAM 64T64000HU3.7A 512MB DIMM DDR 533MT/s        | 1        | 1.03%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s | 1        | 1.03%   |
| G.Skill RAM F4-3600C16-16GTZN 16GB DIMM DDR4 3733MT/s     | 1        | 1.03%   |
| G.Skill RAM F3-2133C9-8GTX 8GB DIMM DDR3 2133MT/s         | 1        | 1.03%   |
| G.Skill RAM F3-12800CL7-4GBXM 4GB DIMM DDR3 1600MT/s      | 1        | 1.03%   |
| Elpida RAM Module 2048MB DIMM DDR3 1067MT/s               | 1        | 1.03%   |
| Crucial RAM CT8G4DFS8266.M8FJ 8GB DIMM DDR4 2667MT/s      | 1        | 1.03%   |
| Crucial RAM CT8G4DFS824A.C8FHD1 8GB DIMM DDR4 2667MT/s    | 1        | 1.03%   |
| Crucial RAM CT8G4DFRA32A.M16FG 8192MB DIMM DDR4 2933MT/s  | 1        | 1.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 32       | 40.51%  |
| DDR3    | 27       | 34.18%  |
| Unknown | 10       | 12.66%  |
| SDRAM   | 6        | 7.59%   |
| DDR2    | 3        | 3.8%    |
| DDR     | 1        | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 76       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 30       | 35.71%  |
| 4096  | 22       | 26.19%  |
| 2048  | 14       | 16.67%  |
| 16384 | 11       | 13.1%   |
| 1024  | 3        | 3.57%   |
| 32768 | 2        | 2.38%   |
| 512   | 1        | 1.19%   |
| 128   | 1        | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 19.32%  |
| 1333    | 8        | 9.09%   |
| 3600    | 7        | 7.95%   |
| 3200    | 6        | 6.82%   |
| 800     | 6        | 6.82%   |
| 2400    | 5        | 5.68%   |
| 2667    | 4        | 4.55%   |
| 667     | 4        | 4.55%   |
| 3466    | 3        | 3.41%   |
| 2133    | 3        | 3.41%   |
| 1867    | 3        | 3.41%   |
| 1800    | 3        | 3.41%   |
| 3400    | 2        | 2.27%   |
| 1866    | 2        | 2.27%   |
| 1066    | 2        | 2.27%   |
| 533     | 2        | 2.27%   |
| Unknown | 2        | 2.27%   |
| 3800    | 1        | 1.14%   |
| 3733    | 1        | 1.14%   |
| 3266    | 1        | 1.14%   |
| 3000    | 1        | 1.14%   |
| 2933    | 1        | 1.14%   |
| 2733    | 1        | 1.14%   |
| 2666    | 1        | 1.14%   |
| 1067    | 1        | 1.14%   |
| 400     | 1        | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 33.33%  |
| Canon               | 1        | 33.33%  |
| Brother Industries  | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Samsung M2070 Series      | 1        | 33.33%  |
| Canon PIXMA MG2500 Series | 1        | 33.33%  |
| Brother MFC-L2700DW       | 1        | 33.33%  |

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
| Canon CanoScan LiDE 220 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 11       | 40.74%  |
| Microsoft                     | 4        | 14.81%  |
| Sunplus Innovation Technology | 2        | 7.41%   |
| Generalplus Technology        | 2        | 7.41%   |
| Creative Technology           | 2        | 7.41%   |
| Realtek Semiconductor         | 1        | 3.7%    |
| Razer USA                     | 1        | 3.7%    |
| GenesysLogic Technology       | 1        | 3.7%    |
| GEMBIRD                       | 1        | 3.7%    |
| Chicony Electronics           | 1        | 3.7%    |
| Apple                         | 1        | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                       | 4        | 14.29%  |
| Microsoft LifeCam HD-3000                         | 3        | 10.71%  |
| Logitech Webcam C270                              | 2        | 7.14%   |
| Creative Live! Cam Sync HD [VF0770]               | 2        | 7.14%   |
| Sunplus HD 720P webcam                            | 1        | 3.57%   |
| Sunplus Full HD webcam                            | 1        | 3.57%   |
| Realtek FULL HD 1080P Webcam                      | 1        | 3.57%   |
| Razer USA Gaming Webcam [Kiyo]                    | 1        | 3.57%   |
| Microsoft LifeCam NX-3000 (UVC-compliant)         | 1        | 3.57%   |
| Logitech Webcam C925e                             | 1        | 3.57%   |
| Logitech Webcam C310                              | 1        | 3.57%   |
| Logitech Webcam C210                              | 1        | 3.57%   |
| Logitech QuickCam Vision Pro                      | 1        | 3.57%   |
| Logitech Logitech Webcam C160                     | 1        | 3.57%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 3.57%   |
| GenesysLogic USB2.0 UVC PC Camera                 | 1        | 3.57%   |
| Generalplus WEB CAM                               | 1        | 3.57%   |
| Generalplus 808 Camera                            | 1        | 3.57%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 3.57%   |
| Chicony USB2.0 2MP UVC Camera                     | 1        | 3.57%   |
| Apple iPhone 5/5C/5S/6/SE                         | 1        | 3.57%   |

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
| 0     | 124      | 82.67%  |
| 1     | 24       | 16%     |
| 2     | 2        | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 12       | 46.15%  |
| Graphics card         | 11       | 42.31%  |
| Multimedia controller | 2        | 7.69%   |
| Net/ethernet          | 1        | 3.85%   |

