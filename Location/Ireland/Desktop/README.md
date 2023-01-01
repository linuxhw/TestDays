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

Total: 248

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 21B4 A01                    | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Intel         | DQ77CP AAG67261-300         | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | B85M-D3H                    | [0b63acf3b2](https://linux-hardware.org/?probe=0b63acf3b2) | Dec 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [f58f70b732](https://linux-hardware.org/?probe=f58f70b732) | Nov 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c3cacc3ed6](https://linux-hardware.org/?probe=c3cacc3ed6) | Nov 15, 2022 |
| MSI           | Z170M MORTAR                | [041dbc2c18](https://linux-hardware.org/?probe=041dbc2c18) | Oct 31, 2022 |
| Dell          | 0JP3NX A00                  | [8b457c11e8](https://linux-hardware.org/?probe=8b457c11e8) | Oct 23, 2022 |
| Foxconn       | 2ABF                        | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| Dell          | 0WR7PY A02                  | [e464adc2d9](https://linux-hardware.org/?probe=e464adc2d9) | Oct 11, 2022 |
| HP            | 21D0                        | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [59d0400171](https://linux-hardware.org/?probe=59d0400171) | Sep 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| ASUSTek       | PRIME Z270-A                | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b389a760a8](https://linux-hardware.org/?probe=b389a760a8) | Sep 12, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| Dell          | 0TP412                      | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| MSI           | MEG Z490I UNIFY             | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| Dell          | 0GY6Y8 A02                  | [caf9167ca7](https://linux-hardware.org/?probe=caf9167ca7) | Aug 16, 2022 |
| Dell          | 0GY6Y8 A02                  | [6d1b561c11](https://linux-hardware.org/?probe=6d1b561c11) | Aug 16, 2022 |
| Dell          | 0JP3NX A00                  | [531e4340a6](https://linux-hardware.org/?probe=531e4340a6) | Aug 07, 2022 |
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


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 28       | 15.64%  |
| Ubuntu 18.04      | 12       | 6.7%    |
| OpenMandriva 4.2  | 6        | 3.35%   |
| Manjaro           | 6        | 3.35%   |
| Debian 11         | 6        | 3.35%   |
| ArcoLinux Rolling | 6        | 3.35%   |
| Ubuntu 19.04      | 5        | 2.79%   |
| Pop!_OS 22.04     | 5        | 2.79%   |
| Linux Mint 20     | 5        | 2.79%   |
| Arch              | 5        | 2.79%   |
| ROSA R11          | 4        | 2.23%   |
| Pop!_OS 21.10     | 4        | 2.23%   |
| Pop!_OS 20.10     | 4        | 2.23%   |
| OpenMandriva 4.3  | 4        | 2.23%   |
| Linux Mint 20.2   | 4        | 2.23%   |
| Arch Rolling      | 4        | 2.23%   |
| Linux Mint 20.1   | 3        | 1.68%   |
| Fedora 35         | 3        | 1.68%   |
| Fedora 32         | 3        | 1.68%   |
| BlackPanther 18.1 | 3        | 1.68%   |
| ROSA R10          | 2        | 1.12%   |
| OpenMandriva 4.50 | 2        | 1.12%   |
| Linux Mint 20.3   | 2        | 1.12%   |
| Linux Mint 19     | 2        | 1.12%   |
| Linux Mint 18.3   | 2        | 1.12%   |
| KDE neon 20.04    | 2        | 1.12%   |
| Fedora 36         | 2        | 1.12%   |
| Fedora 33         | 2        | 1.12%   |
| Endless 3.7.8     | 2        | 1.12%   |
| Debian 10         | 2        | 1.12%   |
| Zorin 16          | 1        | 0.56%   |
| Zorin 15          | 1        | 0.56%   |
| Xubuntu 20.04     | 1        | 0.56%   |
| Ubuntu Core 16    | 1        | 0.56%   |
| Ubuntu 22.04      | 1        | 0.56%   |
| Ubuntu 21.04      | 1        | 0.56%   |
| Ubuntu 19.10      | 1        | 0.56%   |
| SteamOS Snapshot  | 1        | 0.56%   |
| Solus 4.2         | 1        | 0.56%   |
| ROSA R8           | 1        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 48       | 28.92%  |
| Linux Mint   | 17       | 10.24%  |
| Pop!_OS      | 13       | 7.83%   |
| OpenMandriva | 12       | 7.23%   |
| Manjaro      | 10       | 6.02%   |
| Fedora       | 9        | 5.42%   |
| Arch         | 9        | 5.42%   |
| Debian       | 8        | 4.82%   |
| ROSA         | 6        | 3.61%   |
| ArcoLinux    | 6        | 3.61%   |
| KDE neon     | 3        | 1.81%   |
| BlackPanther | 3        | 1.81%   |
| Zorin        | 2        | 1.2%    |
| Lubuntu      | 2        | 1.2%    |
| Kali         | 2        | 1.2%    |
| Gentoo       | 2        | 1.2%    |
| Endless      | 2        | 1.2%    |
| Elementary   | 2        | 1.2%    |
| Xubuntu      | 1        | 0.6%    |
| SteamOS      | 1        | 0.6%    |
| Solus        | 1        | 0.6%    |
| Peppermint   | 1        | 0.6%    |
| openSUSE     | 1        | 0.6%    |
| MX           | 1        | 0.6%    |
| Linux Lite   | 1        | 0.6%    |
| Kubuntu      | 1        | 0.6%    |
| Feren OS     | 1        | 0.6%    |
| Clear Linux  | 1        | 0.6%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.4.0-42-generic                 | 7        | 3.43%   |
| 5.10.14-desktop-1omv4002         | 6        | 2.94%   |
| 5.4.0-48-generic                 | 4        | 1.96%   |
| 5.16.7-desktop-1omv4003          | 4        | 1.96%   |
| 5.8.0-7630-generic               | 3        | 1.47%   |
| 5.4.0-91-generic                 | 3        | 1.47%   |
| 5.4.0-47-generic                 | 3        | 1.47%   |
| 5.3.0-28-generic                 | 3        | 1.47%   |
| 5.17.5-arch1-1                   | 3        | 1.47%   |
| 5.15.11-76051511-generic         | 3        | 1.47%   |
| 4.18.16-desktop-1bP              | 3        | 1.47%   |
| 5.8.14-arch1-1                   | 2        | 0.98%   |
| 5.8.0-43-generic                 | 2        | 0.98%   |
| 5.8.0-41-generic                 | 2        | 0.98%   |
| 5.4.0-88-generic                 | 2        | 0.98%   |
| 5.4.0-77-generic                 | 2        | 0.98%   |
| 5.4.0-72-generic                 | 2        | 0.98%   |
| 5.4.0-37-generic                 | 2        | 0.98%   |
| 5.3.0-45-generic                 | 2        | 0.98%   |
| 5.17.5-76051705-generic          | 2        | 0.98%   |
| 5.16.15-76051615-generic         | 2        | 0.98%   |
| 5.15.0-46-generic                | 2        | 0.98%   |
| 5.13.13-arch1-1                  | 2        | 0.98%   |
| 5.13.0-39-generic                | 2        | 0.98%   |
| 5.12.4-desktop-1omv4050          | 2        | 0.98%   |
| 5.11.0-43-generic                | 2        | 0.98%   |
| 5.0.0-23-generic                 | 2        | 0.98%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 2        | 0.98%   |
| 4.9.60-nrj-desktop-1rosa-i586    | 2        | 0.98%   |
| 4.9.155-nrj-desktop-1rosa-x86_64 | 2        | 0.98%   |
| 4.18.0-25-generic                | 2        | 0.98%   |
| 4.15.0-desktop-45.1rosa-x86_64   | 2        | 0.98%   |
| 4.10.0-38-generic                | 2        | 0.98%   |
| 6.0.9-gentoo-x86_64              | 1        | 0.49%   |
| 6.0.6-arch1-1                    | 1        | 0.49%   |
| 6.0.6-76060006-generic           | 1        | 0.49%   |
| 6.0.0-0.deb11.2-amd64            | 1        | 0.49%   |
| 5.9.3-arch1-1                    | 1        | 0.49%   |
| 5.8.7-arch1-1                    | 1        | 0.49%   |
| 5.8.11-1-MANJARO                 | 1        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 36       | 18.46%  |
| 5.8.0   | 10       | 5.13%   |
| 4.15.0  | 10       | 5.13%   |
| 5.3.0   | 8        | 4.1%    |
| 5.11.0  | 7        | 3.59%   |
| 5.0.0   | 7        | 3.59%   |
| 5.17.5  | 6        | 3.08%   |
| 5.15.0  | 6        | 3.08%   |
| 5.10.14 | 6        | 3.08%   |
| 5.13.0  | 5        | 2.56%   |
| 5.10.0  | 5        | 2.56%   |
| 4.18.0  | 5        | 2.56%   |
| 5.16.7  | 4        | 2.05%   |
| 5.15.11 | 3        | 1.54%   |
| 4.18.16 | 3        | 1.54%   |
| 6.0.6   | 2        | 1.03%   |
| 5.8.14  | 2        | 1.03%   |
| 5.19.0  | 2        | 1.03%   |
| 5.18.10 | 2        | 1.03%   |
| 5.17.6  | 2        | 1.03%   |
| 5.16.15 | 2        | 1.03%   |
| 5.16.11 | 2        | 1.03%   |
| 5.15.6  | 2        | 1.03%   |
| 5.15.12 | 2        | 1.03%   |
| 5.13.13 | 2        | 1.03%   |
| 5.12.4  | 2        | 1.03%   |
| 5.11.11 | 2        | 1.03%   |
| 5.11.10 | 2        | 1.03%   |
| 4.9.60  | 2        | 1.03%   |
| 4.9.155 | 2        | 1.03%   |
| 4.19.0  | 2        | 1.03%   |
| 4.10.0  | 2        | 1.03%   |
| 6.0.9   | 1        | 0.51%   |
| 6.0.0   | 1        | 0.51%   |
| 5.9.3   | 1        | 0.51%   |
| 5.8.7   | 1        | 0.51%   |
| 5.8.11  | 1        | 0.51%   |
| 5.8.10  | 1        | 0.51%   |
| 5.7.8   | 1        | 0.51%   |
| 5.7.12  | 1        | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 19.68%  |
| 5.15    | 16       | 8.51%   |
| 5.8     | 15       | 7.98%   |
| 5.10    | 15       | 7.98%   |
| 5.11    | 13       | 6.91%   |
| 5.16    | 10       | 5.32%   |
| 4.15    | 10       | 5.32%   |
| 5.17    | 9        | 4.79%   |
| 5.3     | 8        | 4.26%   |
| 5.13    | 8        | 4.26%   |
| 4.18    | 8        | 4.26%   |
| 5.0     | 7        | 3.72%   |
| 5.12    | 5        | 2.66%   |
| 6.0     | 4        | 2.13%   |
| 5.7     | 3        | 1.6%    |
| 5.6     | 3        | 1.6%    |
| 5.19    | 3        | 1.6%    |
| 5.18    | 3        | 1.6%    |
| 4.9     | 3        | 1.6%    |
| 4.19    | 2        | 1.06%   |
| 4.10    | 2        | 1.06%   |
| 5.9     | 1        | 0.53%   |
| 5.5     | 1        | 0.53%   |
| 5.14    | 1        | 0.53%   |
| 4.1     | 1        | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 159      | 98.15%  |
| i686   | 3        | 1.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 63       | 36.84%  |
| KDE5            | 36       | 21.05%  |
| Unknown         | 24       | 14.04%  |
| XFCE            | 13       | 7.6%    |
| X-Cinnamon      | 9        | 5.26%   |
| MATE            | 7        | 4.09%   |
| KDE             | 6        | 3.51%   |
| KDE4            | 4        | 2.34%   |
| LXQt            | 3        | 1.75%   |
| Pantheon        | 2        | 1.17%   |
| LXDE            | 1        | 0.58%   |
| LeftWM          | 1        | 0.58%   |
| GNOME Flashback | 1        | 0.58%   |
| Cinnamon        | 1        | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 133      | 80.61%  |
| Unknown | 15       | 9.09%   |
| Wayland | 13       | 7.88%   |
| Tty     | 4        | 2.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 90       | 53.57%  |
| SDDM    | 36       | 21.43%  |
| GDM     | 17       | 10.12%  |
| LightDM | 9        | 5.36%   |
| GDM3    | 6        | 3.57%   |
| TDM     | 5        | 2.98%   |
| KDM     | 4        | 2.38%   |
| LXDM    | 1        | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_IE   | 77       | 46.11%  |
| en_US   | 30       | 17.96%  |
| en_GB   | 28       | 16.77%  |
| Unknown | 26       | 15.57%  |
| es_ES   | 2        | 1.2%    |
| pt_BR   | 1        | 0.6%    |
| pl_PL   | 1        | 0.6%    |
| de_DE   | 1        | 0.6%    |
| C       | 1        | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 104      | 63.03%  |
| EFI  | 61       | 36.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 128      | 78.53%  |
| Overlay | 15       | 9.2%    |
| Btrfs   | 11       | 6.75%   |
| Unknown | 7        | 4.29%   |
| Zfs     | 1        | 0.61%   |
| Xfs     | 1        | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 89       | 52.98%  |
| GPT     | 59       | 35.12%  |
| MBR     | 20       | 11.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 78.18%  |
| Yes       | 36       | 21.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 66.27%  |
| Yes       | 56       | 33.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 37       | 23.13%  |
| Dell                | 30       | 18.75%  |
| Gigabyte Technology | 22       | 13.75%  |
| MSI                 | 16       | 10%     |
| Hewlett-Packard     | 13       | 8.13%   |
| ASRock              | 12       | 7.5%    |
| Lenovo              | 10       | 6.25%   |
| Foxconn             | 4        | 2.5%    |
| Intel               | 3        | 1.88%   |
| Shuttle             | 2        | 1.25%   |
| Seco                | 2        | 1.25%   |
| Apple               | 2        | 1.25%   |
| Pegatron            | 1        | 0.63%   |
| Packard Bell        | 1        | 0.63%   |
| MiTAC               | 1        | 0.63%   |
| Medion              | 1        | 0.63%   |
| DFI                 | 1        | 0.63%   |
| ABIT                | 1        | 0.63%   |
| Unknown             | 1        | 0.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Dell OptiPlex 7010              | 6        | 3.75%   |
| ASUS All Series                 | 6        | 3.75%   |
| Gigabyte B450M DS3H             | 4        | 2.5%    |
| HP Compaq 8200 Elite SFF PC     | 3        | 1.88%   |
| Dell OptiPlex 790               | 3        | 1.88%   |
| ASUS ROG STRIX B450-F GAMING    | 3        | 1.88%   |
| Seco C40                        | 2        | 1.25%   |
| MSI MS-7B79                     | 2        | 1.25%   |
| Lenovo ThinkStation D20 415892G | 2        | 1.25%   |
| HP EliteDesk 800 G1 SFF         | 2        | 1.25%   |
| Gigabyte X570 AORUS ULTRA       | 2        | 1.25%   |
| Foxconn Pro 3500 Series         | 2        | 1.25%   |
| Dell OptiPlex 780               | 2        | 1.25%   |
| Dell OptiPlex 7020              | 2        | 1.25%   |
| ASUS TUF Gaming X570-PLUS       | 2        | 1.25%   |
| ASUS P8P67 PRO                  | 2        | 1.25%   |
| ASUS M5A78L/USB3                | 2        | 1.25%   |
| Shuttle XS35V4                  | 1        | 0.63%   |
| Shuttle XS35V3                  | 1        | 0.63%   |
| Pegatron Pro 3010 Microtower PC | 1        | 0.63%   |
| Packard Bell Vegas2             | 1        | 0.63%   |
| MSI Pro 3515 Series             | 1        | 0.63%   |
| MSI MS-7C84                     | 1        | 0.63%   |
| MSI MS-7C77                     | 1        | 0.63%   |
| MSI MS-7C37                     | 1        | 0.63%   |
| MSI MS-7C02                     | 1        | 0.63%   |
| MSI MS-7B92                     | 1        | 0.63%   |
| MSI MS-7B89                     | 1        | 0.63%   |
| MSI MS-7B86                     | 1        | 0.63%   |
| MSI MS-7972                     | 1        | 0.63%   |
| MSI MS-7751                     | 1        | 0.63%   |
| MSI MS-7693                     | 1        | 0.63%   |
| MSI MS-7636                     | 1        | 0.63%   |
| MSI MS-7270                     | 1        | 0.63%   |
| MSI ER883AA-ABA M7470N          | 1        | 0.63%   |
| MiTAC PD14TI AAPD14TI-101       | 1        | 0.63%   |
| Medion MS-7646                  | 1        | 0.63%   |
| Lenovo V530S-07ICB 10TX002GUK   | 1        | 0.63%   |
| Lenovo ThinkCentre M91p 7052A9G | 1        | 0.63%   |
| Lenovo ThinkCentre M82 2929A58  | 1        | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 18       | 11.25%  |
| Lenovo ThinkCentre  | 7        | 4.38%   |
| ASUS PRIME          | 7        | 4.38%   |
| HP Compaq           | 6        | 3.75%   |
| ASUS All            | 6        | 3.75%   |
| ASUS TUF            | 5        | 3.13%   |
| Gigabyte B450M      | 4        | 2.5%    |
| Dell Precision      | 4        | 2.5%    |
| HP EliteDesk        | 3        | 1.88%   |
| Foxconn Pro         | 3        | 1.88%   |
| ASUS ROG            | 3        | 1.88%   |
| Seco C40            | 2        | 1.25%   |
| MSI MS-7B79         | 2        | 1.25%   |
| Lenovo ThinkStation | 2        | 1.25%   |
| Intel DESKTOP       | 2        | 1.25%   |
| Gigabyte X570       | 2        | 1.25%   |
| Gigabyte B450       | 2        | 1.25%   |
| Dell Vostro         | 2        | 1.25%   |
| Dell Inspiron       | 2        | 1.25%   |
| ASUS P8P67          | 2        | 1.25%   |
| ASUS Maximus        | 2        | 1.25%   |
| ASUS M5A78L         | 2        | 1.25%   |
| ASUS Crosshair      | 2        | 1.25%   |
| ASRock Z77          | 2        | 1.25%   |
| Shuttle XS35V4      | 1        | 0.63%   |
| Shuttle XS35V3      | 1        | 0.63%   |
| Pegatron Pro        | 1        | 0.63%   |
| Packard Bell Vegas2 | 1        | 0.63%   |
| MSI Pro             | 1        | 0.63%   |
| MSI MS-7C84         | 1        | 0.63%   |
| MSI MS-7C77         | 1        | 0.63%   |
| MSI MS-7C37         | 1        | 0.63%   |
| MSI MS-7C02         | 1        | 0.63%   |
| MSI MS-7B92         | 1        | 0.63%   |
| MSI MS-7B89         | 1        | 0.63%   |
| MSI MS-7B86         | 1        | 0.63%   |
| MSI MS-7972         | 1        | 0.63%   |
| MSI MS-7751         | 1        | 0.63%   |
| MSI MS-7693         | 1        | 0.63%   |
| MSI MS-7636         | 1        | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 24       | 15%     |
| 2013 | 21       | 13.13%  |
| 2012 | 18       | 11.25%  |
| 2011 | 18       | 11.25%  |
| 2019 | 13       | 8.13%   |
| 2010 | 12       | 7.5%    |
| 2008 | 11       | 6.88%   |
| 2020 | 9        | 5.63%   |
| 2017 | 8        | 5%      |
| 2014 | 7        | 4.38%   |
| 2015 | 6        | 3.75%   |
| 2006 | 4        | 2.5%    |
| 2009 | 3        | 1.88%   |
| 2007 | 3        | 1.88%   |
| 2021 | 1        | 0.63%   |
| 2016 | 1        | 0.63%   |
| 2005 | 1        | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 160      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 156      | 97.5%   |
| Enabled  | 4        | 2.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 160      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 43       | 25.9%   |
| 8.01-16.0   | 41       | 24.7%   |
| 3.01-4.0    | 26       | 15.66%  |
| 32.01-64.0  | 24       | 14.46%  |
| 4.01-8.0    | 17       | 10.24%  |
| 64.01-256.0 | 8        | 4.82%   |
| 24.01-32.0  | 4        | 2.41%   |
| 1.01-2.0    | 3        | 1.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 76       | 41.3%   |
| 2.01-3.0   | 38       | 20.65%  |
| 4.01-8.0   | 22       | 11.96%  |
| 3.01-4.0   | 21       | 11.41%  |
| 0.51-1.0   | 14       | 7.61%   |
| 8.01-16.0  | 11       | 5.98%   |
| 32.01-64.0 | 1        | 0.54%   |
| 0.01-0.5   | 1        | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 60       | 34.09%  |
| 2      | 43       | 24.43%  |
| 3      | 26       | 14.77%  |
| 4      | 20       | 11.36%  |
| 5      | 12       | 6.82%   |
| 7      | 6        | 3.41%   |
| 6      | 4        | 2.27%   |
| 10     | 2        | 1.14%   |
| 0      | 2        | 1.14%   |
| 9      | 1        | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 84       | 51.22%  |
| No        | 80       | 48.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 159      | 99.38%  |
| No        | 1        | 0.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 88       | 53.66%  |
| No        | 76       | 46.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 64.24%  |
| Yes       | 59       | 35.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ireland | 160      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Dublin        | 92       | 54.76%  |
| Cork          | 10       | 5.95%   |
| Limerick      | 5        | 2.98%   |
| Gorey         | 4        | 2.38%   |
| Tuam          | 3        | 1.79%   |
| Sligo         | 3        | 1.79%   |
| Portlaoise    | 3        | 1.79%   |
| Naas          | 3        | 1.79%   |
| Kenmare       | 3        | 1.79%   |
| Oranmore      | 2        | 1.19%   |
| Kildare       | 2        | 1.19%   |
| Cavan         | 2        | 1.19%   |
| Athlone       | 2        | 1.19%   |
| Wexford       | 1        | 0.6%    |
| Tullamore     | 1        | 0.6%    |
| Tralee        | 1        | 0.6%    |
| Tipperary     | 1        | 0.6%    |
| Swords        | 1        | 0.6%    |
| Summerhill    | 1        | 0.6%    |
| Shanagolden   | 1        | 0.6%    |
| Nenagh        | 1        | 0.6%    |
| Navan         | 1        | 0.6%    |
| Moyne         | 1        | 0.6%    |
| Maynooth      | 1        | 0.6%    |
| Mallow        | 1        | 0.6%    |
| Lucan         | 1        | 0.6%    |
| Listowel      | 1        | 0.6%    |
| Letterkenny   | 1        | 0.6%    |
| Kilkenny      | 1        | 0.6%    |
| Kilcoole      | 1        | 0.6%    |
| Galway        | 1        | 0.6%    |
| Enniscorthy   | 1        | 0.6%    |
| Edenderry     | 1        | 0.6%    |
| Dunshaughlin  | 1        | 0.6%    |
| Dungarvan     | 1        | 0.6%    |
| Drumcondra    | 1        | 0.6%    |
| Droichead Nua | 1        | 0.6%    |
| Cobh          | 1        | 0.6%    |
| Castlecomer   | 1        | 0.6%    |
| Callan        | 1        | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 74       | 150    | 22.98%  |
| Seagate                   | 59       | 113    | 18.32%  |
| Samsung Electronics       | 43       | 72     | 13.35%  |
| Crucial                   | 22       | 24     | 6.83%   |
| Toshiba                   | 18       | 27     | 5.59%   |
| SanDisk                   | 14       | 23     | 4.35%   |
| Hitachi                   | 13       | 23     | 4.04%   |
| Kingston                  | 11       | 17     | 3.42%   |
| A-DATA Technology         | 8        | 13     | 2.48%   |
| Phison                    | 6        | 11     | 1.86%   |
| Verbatim                  | 4        | 4      | 1.24%   |
| Intel                     | 4        | 4      | 1.24%   |
| China                     | 3        | 3      | 0.93%   |
| Transcend                 | 2        | 2      | 0.62%   |
| Team                      | 2        | 2      | 0.62%   |
| Silicon Motion            | 2        | 5      | 0.62%   |
| OCZ                       | 2        | 2      | 0.62%   |
| Micron/Crucial Technology | 2        | 3      | 0.62%   |
| Micron Technology         | 2        | 2      | 0.62%   |
| Maxtor                    | 2        | 2      | 0.62%   |
| LITEON                    | 2        | 2      | 0.62%   |
| WDS100T1                  | 1        | 1      | 0.31%   |
| USB3.0                    | 1        | 1      | 0.31%   |
| Unknown                   | 1        | 1      | 0.31%   |
| Union Memory (Shenzhen)   | 1        | 1      | 0.31%   |
| Union Memory              | 1        | 1      | 0.31%   |
| PNY                       | 1        | 1      | 0.31%   |
| Palit                     | 1        | 1      | 0.31%   |
| Netac                     | 1        | 1      | 0.31%   |
| MaxDigital                | 1        | 1      | 0.31%   |
| KIOXIA                    | 1        | 2      | 0.31%   |
| KingSpec                  | 1        | 1      | 0.31%   |
| KingDian                  | 1        | 1      | 0.31%   |
| KESU                      | 1        | 1      | 0.31%   |
| JMicron Technology        | 1        | 1      | 0.31%   |
| Integral                  | 1        | 1      | 0.31%   |
| Inateck                   | 1        | 1      | 0.31%   |
| Hikvision                 | 1        | 1      | 0.31%   |
| HGST                      | 1        | 1      | 0.31%   |
| Hewlett-Packard           | 1        | 2      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB   | 7        | 1.78%   |
| Seagate ST8000DM004-2CX188 8TB   | 6        | 1.53%   |
| WDC WD10EURX-83UY4Y0 1TB         | 5        | 1.27%   |
| Seagate ST500DM002-1BD142 500GB  | 5        | 1.27%   |
| Verbatim Vi550 S3 SSD 512GB      | 4        | 1.02%   |
| Seagate ST2000DL003-9VT166 2TB   | 4        | 1.02%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 3        | 0.76%   |
| WDC WD3200AAJS-60Z0A0 320GB      | 3        | 0.76%   |
| WDC WD20EZRX-00D8PB0 2TB         | 3        | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 0.76%   |
| WDC WD10EALX-009BA0 1TB          | 3        | 0.76%   |
| Toshiba DT01ACA100 1TB           | 3        | 0.76%   |
| Seagate ST3500418AS 500GB        | 3        | 0.76%   |
| Seagate ST3500312CS 500GB        | 3        | 0.76%   |
| Seagate ST31000528AS 1TB         | 3        | 0.76%   |
| Seagate ST2000DM006-2DM164 2TB   | 3        | 0.76%   |
| Seagate Expansion Desk 5TB       | 3        | 0.76%   |
| SanDisk NVMe SSD Drive 500GB     | 3        | 0.76%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.76%   |
| Samsung SSD 860 EVO 500GB        | 3        | 0.76%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.76%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.76%   |
| Phison Sabrent 1TB               | 3        | 0.76%   |
| Kingston SV300S37A120G 120GB SSD | 3        | 0.76%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 0.76%   |
| Hitachi HDS721616PLA380 160GB    | 3        | 0.76%   |
| Hitachi HDS721032CLA362 320GB    | 3        | 0.76%   |
| Crucial CT500MX500SSD1 500GB     | 3        | 0.76%   |
| Crucial CT1000MX500SSD1 1TB      | 3        | 0.76%   |
| A-DATA SU650 240GB SSD           | 3        | 0.76%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.51%   |
| WDC WD5000BPKT-60PK4T0 500GB     | 2        | 0.51%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 0.51%   |
| WDC WD40EZRZ-19GXCB0 4TB         | 2        | 0.51%   |
| WDC WD2500AAKX-753CA1 250GB      | 2        | 0.51%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.51%   |
| WDC WD20EARS-00MVWB0 2TB         | 2        | 0.51%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.51%   |
| Toshiba MQ01ABD100 1TB           | 2        | 0.51%   |
| Toshiba HDWD110 1TB              | 2        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 66       | 138    | 38.15%  |
| Seagate             | 58       | 112    | 33.53%  |
| Toshiba             | 17       | 25     | 9.83%   |
| Hitachi             | 13       | 23     | 7.51%   |
| Samsung Electronics | 8        | 9      | 4.62%   |
| Maxtor              | 2        | 2      | 1.16%   |
| USB3.0              | 1        | 1      | 0.58%   |
| Unknown             | 1        | 1      | 0.58%   |
| KESU                | 1        | 1      | 0.58%   |
| Inateck             | 1        | 1      | 0.58%   |
| HGST                | 1        | 1      | 0.58%   |
| Fujitsu             | 1        | 1      | 0.58%   |
| FNK TECH            | 1        | 1      | 0.58%   |
| ExcelStor           | 1        | 2      | 0.58%   |
| ASMT                | 1        | 1      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 28       | 43     | 25.69%  |
| Crucial             | 20       | 22     | 18.35%  |
| Kingston            | 10       | 15     | 9.17%   |
| SanDisk             | 9        | 13     | 8.26%   |
| A-DATA Technology   | 6        | 10     | 5.5%    |
| WDC                 | 5        | 8      | 4.59%   |
| Verbatim            | 4        | 4      | 3.67%   |
| Intel               | 4        | 4      | 3.67%   |
| China               | 3        | 3      | 2.75%   |
| Transcend           | 2        | 2      | 1.83%   |
| Team                | 2        | 2      | 1.83%   |
| OCZ                 | 2        | 2      | 1.83%   |
| LITEON              | 2        | 2      | 1.83%   |
| PNY                 | 1        | 1      | 0.92%   |
| Palit               | 1        | 1      | 0.92%   |
| Netac               | 1        | 1      | 0.92%   |
| Micron Technology   | 1        | 1      | 0.92%   |
| KingSpec            | 1        | 1      | 0.92%   |
| KingDian            | 1        | 1      | 0.92%   |
| Integral            | 1        | 1      | 0.92%   |
| Hikvision           | 1        | 1      | 0.92%   |
| Hewlett-Packard     | 1        | 2      | 0.92%   |
| DRVEO               | 1        | 1      | 0.92%   |
| Corsair             | 1        | 2      | 0.92%   |
| Apple               | 1        | 1      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 119      | 319    | 47.22%  |
| SSD     | 91       | 144    | 36.11%  |
| NVMe    | 38       | 68     | 15.08%  |
| Unknown | 4        | 4      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 151      | 448    | 73.66%  |
| NVMe | 38       | 68     | 18.54%  |
| SAS  | 16       | 19     | 7.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 112      | 228    | 45.9%   |
| 0.51-1.0   | 76       | 128    | 31.15%  |
| 1.01-2.0   | 24       | 37     | 9.84%   |
| 4.01-10.0  | 12       | 32     | 4.92%   |
| 3.01-4.0   | 11       | 26     | 4.51%   |
| 2.01-3.0   | 9        | 12     | 3.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 34       | 18.99%  |
| 251-500        | 28       | 15.64%  |
| 501-1000       | 27       | 15.08%  |
| More than 3000 | 26       | 14.53%  |
| 1001-2000      | 17       | 9.5%    |
| 51-100         | 14       | 7.82%   |
| 2001-3000      | 10       | 5.59%   |
| 1-20           | 10       | 5.59%   |
| Unknown        | 8        | 4.47%   |
| 21-50          | 5        | 2.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 57       | 30.81%  |
| 101-250        | 23       | 12.43%  |
| 501-1000       | 22       | 11.89%  |
| 51-100         | 20       | 10.81%  |
| 21-50          | 17       | 9.19%   |
| More than 3000 | 13       | 7.03%   |
| 251-500        | 10       | 5.41%   |
| 2001-3000      | 8        | 4.32%   |
| Unknown        | 8        | 4.32%   |
| 1001-2000      | 7        | 3.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                  | 3        | 8      | 7.32%   |
| Seagate ST2000DL003-9VT166 2TB           | 3        | 5      | 7.32%   |
| WDC WD2500AAKX-753CA1 250GB              | 2        | 3      | 4.88%   |
| WDC WD7500BPKX-00HPJT0 752GB             | 1        | 1      | 2.44%   |
| WDC WD5000BEVT-35A0RT0 500GB             | 1        | 1      | 2.44%   |
| WDC WD5000AAKX-001CA0 500GB              | 1        | 1      | 2.44%   |
| WDC WD400JB-00FMA0 40GB                  | 1        | 2      | 2.44%   |
| WDC WD3200AVJS-63B6A0 320GB              | 1        | 1      | 2.44%   |
| WDC WD2500BEKT-75A25T0 250GB             | 1        | 1      | 2.44%   |
| WDC WD2500AAKX-603CA0 250GB              | 1        | 1      | 2.44%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1        | 1      | 2.44%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1        | 1      | 2.44%   |
| WDC WD1001FALS-00E8B0 1TB                | 1        | 2      | 2.44%   |
| Toshiba MK1059GSM 1TB                    | 1        | 1      | 2.44%   |
| Toshiba DT01ACA050 500GB                 | 1        | 2      | 2.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1        | 1      | 2.44%   |
| Seagate ST4000DX001-1CE168 4TB           | 1        | 1      | 2.44%   |
| Seagate ST3500418AS 500GB                | 1        | 2      | 2.44%   |
| Seagate ST31500541AS 1TB                 | 1        | 1      | 2.44%   |
| Seagate ST3120026A 120GB                 | 1        | 1      | 2.44%   |
| Seagate ST31000333AS 1TB                 | 1        | 2      | 2.44%   |
| Seagate ST3000DM001-1ER166 3TB           | 1        | 1      | 2.44%   |
| Samsung Electronics SSD 970 EVO Plus 2TB | 1        | 1      | 2.44%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 2.44%   |
| Netac SSD 128GB                          | 1        | 1      | 2.44%   |
| Micron Technology 2300 NVMe 512GB        | 1        | 1      | 2.44%   |
| Maxtor STM3250310AS 250GB                | 1        | 1      | 2.44%   |
| Intel SSDSA2M080G2GC 80GB                | 1        | 1      | 2.44%   |
| Inateck ASM1153E 256GB                   | 1        | 1      | 2.44%   |
| Hitachi HUS724030ALA640 3TB              | 1        | 2      | 2.44%   |
| Hitachi HDT721016SLA380 160GB            | 1        | 2      | 2.44%   |
| Hitachi HDS721010CLA332 1TB              | 1        | 1      | 2.44%   |
| HGST HTS541010A7E630 1TB                 | 1        | 1      | 2.44%   |
| DRVEO X1 SSD 480GB                       | 1        | 1      | 2.44%   |
| China T480 480GB SSD                     | 1        | 1      | 2.44%   |
| A-DATA Technology SU800 128GB SSD        | 1        | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 23     | 31.58%  |
| Seagate             | 10       | 14     | 26.32%  |
| Hitachi             | 3        | 5      | 7.89%   |
| Toshiba             | 2        | 3      | 5.26%   |
| Samsung Electronics | 2        | 2      | 5.26%   |
| Netac               | 1        | 1      | 2.63%   |
| Micron Technology   | 1        | 1      | 2.63%   |
| Maxtor              | 1        | 1      | 2.63%   |
| Intel               | 1        | 1      | 2.63%   |
| Inateck             | 1        | 1      | 2.63%   |
| HGST                | 1        | 1      | 2.63%   |
| DRVEO               | 1        | 1      | 2.63%   |
| China               | 1        | 1      | 2.63%   |
| A-DATA Technology   | 1        | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 23     | 38.71%  |
| Seagate             | 10       | 14     | 32.26%  |
| Hitachi             | 3        | 5      | 9.68%   |
| Toshiba             | 2        | 3      | 6.45%   |
| Samsung Electronics | 1        | 1      | 3.23%   |
| Maxtor              | 1        | 1      | 3.23%   |
| Inateck             | 1        | 1      | 3.23%   |
| HGST                | 1        | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 49     | 77.42%  |
| SSD  | 5        | 5      | 16.13%  |
| NVMe | 2        | 2      | 6.45%   |

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
| Detected | 94       | 286    | 49.21%  |
| Works    | 67       | 193    | 35.08%  |
| Malfunc  | 30       | 56     | 15.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 98       | 43.17%  |
| AMD                          | 54       | 23.79%  |
| Samsung Electronics          | 14       | 6.17%   |
| SanDisk                      | 9        | 3.96%   |
| Marvell Technology Group     | 8        | 3.52%   |
| ASMedia Technology           | 8        | 3.52%   |
| Phison Electronics           | 6        | 2.64%   |
| JMicron Technology           | 5        | 2.2%    |
| Nvidia                       | 4        | 1.76%   |
| Micron/Crucial Technology    | 4        | 1.76%   |
| LSI Logic / Symbios Logic    | 3        | 1.32%   |
| Union Memory (Shenzhen)      | 2        | 0.88%   |
| Toshiba America Info Systems | 2        | 0.88%   |
| Silicon Motion               | 2        | 0.88%   |
| Realtek Semiconductor        | 2        | 0.88%   |
| ULi Electronics              | 1        | 0.44%   |
| Seagate Technology           | 1        | 0.44%   |
| Micron Technology            | 1        | 0.44%   |
| KIOXIA                       | 1        | 0.44%   |
| Kingston Technology Company  | 1        | 0.44%   |
| Broadcom / LSI               | 1        | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 36       | 12.16%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 5.41%   |
| AMD 400 Series Chipset SATA Controller                                                  | 16       | 5.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 4.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 3.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 2.7%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.7%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 2.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 2.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 2.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 1.69%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 1.69%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.35%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 1.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 1.35%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.35%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.01%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.01%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 2        | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.68%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.68%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.68%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.68%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.68%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.68%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 2        | 0.68%   |
| Marvell Group 88SE9182 PCIe 2.0 x2 2-port SATA 6 Gb/s Controller                        | 2        | 0.68%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 2        | 0.68%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 2        | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 134      | 59.82%  |
| IDE  | 42       | 18.75%  |
| NVMe | 38       | 16.96%  |
| RAID | 8        | 3.57%   |
| SCSI | 2        | 0.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 102      | 63.75%  |
| AMD    | 58       | 36.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 7        | 4.29%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 6        | 3.68%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 5        | 3.07%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 4        | 2.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 4        | 2.45%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 4        | 2.45%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 4        | 2.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 3        | 1.84%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 3        | 1.84%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 3        | 1.84%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3        | 1.84%   |
| AMD Athlon II X4 620 Processor                 | 3        | 1.84%   |
| Intel Xeon CPU X5690 @ 3.47GHz                 | 2        | 1.23%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 2        | 1.23%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 2        | 1.23%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 2        | 1.23%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 2        | 1.23%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 2        | 1.23%   |
| Intel Core i5-10500 CPU @ 3.10GHz              | 2        | 1.23%   |
| Intel Core i3-4150 CPU @ 3.50GHz               | 2        | 1.23%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 1.23%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz          | 2        | 1.23%   |
| AMD Ryzen Embedded V1605B with Radeon Vega Gfx | 2        | 1.23%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 1.23%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 1.23%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 1.23%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 2        | 1.23%   |
| AMD FX-6300 Six-Core Processor                 | 2        | 1.23%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+     | 2        | 1.23%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 0.61%   |
| Intel Xeon CPU E5462 @ 2.80GHz                 | 1        | 0.61%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz            | 1        | 0.61%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz            | 1        | 0.61%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz       | 1        | 0.61%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 1        | 0.61%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 1        | 0.61%   |
| Intel Pentium D CPU 2.80GHz                    | 1        | 0.61%   |
| Intel Pentium CPU G630 @ 2.70GHz               | 1        | 0.61%   |
| Intel Pentium CPU G2030 @ 3.00GHz              | 1        | 0.61%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 32       | 19.63%  |
| Intel Core i7           | 28       | 17.18%  |
| AMD Ryzen 5             | 17       | 10.43%  |
| Intel Core i3           | 15       | 9.2%    |
| Intel Core 2 Quad       | 8        | 4.91%   |
| Intel Xeon              | 6        | 3.68%   |
| AMD Ryzen 9             | 6        | 3.68%   |
| AMD FX                  | 5        | 3.07%   |
| AMD Athlon 64 X2        | 5        | 3.07%   |
| AMD Ryzen 7             | 4        | 2.45%   |
| Intel Core 2 Duo        | 3        | 1.84%   |
| Intel Celeron           | 3        | 1.84%   |
| AMD Ryzen 3             | 3        | 1.84%   |
| AMD Athlon II X4        | 3        | 1.84%   |
| Intel Pentium Dual-Core | 2        | 1.23%   |
| Intel Pentium 4         | 2        | 1.23%   |
| Intel Pentium           | 2        | 1.23%   |
| Intel Atom              | 2        | 1.23%   |
| AMD Ryzen Threadripper  | 2        | 1.23%   |
| AMD Ryzen Embedded      | 2        | 1.23%   |
| AMD Phenom II X6        | 2        | 1.23%   |
| AMD A6                  | 2        | 1.23%   |
| AMD A4                  | 2        | 1.23%   |
| Intel Pentium Silver    | 1        | 0.61%   |
| Intel Pentium D         | 1        | 0.61%   |
| AMD PRO A10             | 1        | 0.61%   |
| AMD Phenom II X4        | 1        | 0.61%   |
| AMD GX                  | 1        | 0.61%   |
| AMD Athlon II X2        | 1        | 0.61%   |
| AMD Athlon Dual Core    | 1        | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 80       | 49.69%  |
| 2       | 31       | 19.25%  |
| 6       | 24       | 14.91%  |
| 12      | 9        | 5.59%   |
| 8       | 7        | 4.35%   |
| 1       | 6        | 3.73%   |
| 3       | 2        | 1.24%   |
| 32      | 1        | 0.62%   |
| Unknown | 1        | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 157      | 98.13%  |
| 2      | 3        | 1.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 90       | 55.21%  |
| 1       | 72       | 44.17%  |
| Unknown | 1        | 0.61%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 157      | 98.13%  |
| Unknown        | 3        | 1.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 43       | 26.06%  |
| 0x306a9    | 15       | 9.09%   |
| 0x306c3    | 13       | 7.88%   |
| 0x206a7    | 13       | 7.88%   |
| 0x1067a    | 8        | 4.85%   |
| 0x08701021 | 7        | 4.24%   |
| 0x0800820d | 4        | 2.42%   |
| 0xa0653    | 3        | 1.82%   |
| 0x906ea    | 3        | 1.82%   |
| 0x6fb      | 3        | 1.82%   |
| 0x506e3    | 3        | 1.82%   |
| 0x206c2    | 3        | 1.82%   |
| 0x08108109 | 3        | 1.82%   |
| 0x0810100b | 3        | 1.82%   |
| 0x06000852 | 3        | 1.82%   |
| 0x906e9    | 2        | 1.21%   |
| 0x30661    | 2        | 1.21%   |
| 0x106a5    | 2        | 1.21%   |
| 0x08701013 | 2        | 1.21%   |
| 0x0600611a | 2        | 1.21%   |
| 0x010000db | 2        | 1.21%   |
| 0x010000c8 | 2        | 1.21%   |
| 0xf47      | 1        | 0.61%   |
| 0xf43      | 1        | 0.61%   |
| 0xf41      | 1        | 0.61%   |
| 0xa0655    | 1        | 0.61%   |
| 0x906ed    | 1        | 0.61%   |
| 0x906eb    | 1        | 0.61%   |
| 0x706a1    | 1        | 0.61%   |
| 0x6f7      | 1        | 0.61%   |
| 0x306e4    | 1        | 0.61%   |
| 0x30678    | 1        | 0.61%   |
| 0x106e5    | 1        | 0.61%   |
| 0x10677    | 1        | 0.61%   |
| 0x10676    | 1        | 0.61%   |
| 0x0a20120a | 1        | 0.61%   |
| 0x0a201205 | 1        | 0.61%   |
| 0x0a201016 | 1        | 0.61%   |
| 0x08301039 | 1        | 0.61%   |
| 0x08101016 | 1        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 22       | 13.66%  |
| SandyBridge   | 18       | 11.18%  |
| Haswell       | 16       | 9.94%   |
| Zen 2         | 14       | 8.7%    |
| Zen+          | 12       | 7.45%   |
| Penryn        | 10       | 6.21%   |
| KabyLake      | 10       | 6.21%   |
| K10           | 7        | 4.35%   |
| Zen           | 6        | 3.73%   |
| Piledriver    | 6        | 3.73%   |
| K8 Hammer     | 6        | 3.73%   |
| Nehalem       | 5        | 3.11%   |
| Core          | 4        | 2.48%   |
| CometLake     | 4        | 2.48%   |
| Westmere      | 3        | 1.86%   |
| Skylake       | 3        | 1.86%   |
| NetBurst      | 3        | 1.86%   |
| Zen 3         | 2        | 1.24%   |
| Goldmont plus | 2        | 1.24%   |
| Excavator     | 2        | 1.24%   |
| Bonnell       | 2        | 1.24%   |
| Steamroller   | 1        | 0.62%   |
| Silvermont    | 1        | 0.62%   |
| Jaguar        | 1        | 0.62%   |
| Bulldozer     | 1        | 0.62%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 69       | 38.55%  |
| Nvidia | 60       | 33.52%  |
| Intel  | 50       | 27.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 7.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8        | 4.26%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 8        | 4.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 3.19%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 2.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.66%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 2.66%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.13%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 2.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.13%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 4        | 2.13%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 1.6%    |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.6%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.6%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.6%    |
| Nvidia GM204 [GeForce GTX 980]                                              | 3        | 1.6%    |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.6%    |
| Intel HD Graphics 630                                                       | 3        | 1.6%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.6%    |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.6%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.6%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.06%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.06%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 1.06%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 2        | 1.06%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 1.06%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 1.06%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.06%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.53%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.53%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.53%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.53%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.53%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.53%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.53%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.53%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.53%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 62       | 37.35%  |
| 1 x Nvidia     | 56       | 33.73%  |
| 1 x Intel      | 38       | 22.89%  |
| 2 x AMD        | 6        | 3.61%   |
| Intel + Nvidia | 3        | 1.81%   |
| AMD + Nvidia   | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 128      | 77.58%  |
| Proprietary | 29       | 17.58%  |
| Unknown     | 8        | 4.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 68       | 40%     |
| 0.51-1.0   | 23       | 13.53%  |
| 1.01-2.0   | 21       | 12.35%  |
| 7.01-8.0   | 17       | 10%     |
| 3.01-4.0   | 16       | 9.41%   |
| 0.01-0.5   | 12       | 7.06%   |
| 5.01-6.0   | 8        | 4.71%   |
| 2.01-3.0   | 2        | 1.18%   |
| 8.01-16.0  | 2        | 1.18%   |
| 16.01-24.0 | 1        | 0.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 34       | 20.36%  |
| Samsung Electronics  | 15       | 8.98%   |
| Acer                 | 15       | 8.98%   |
| Hewlett-Packard      | 13       | 7.78%   |
| BenQ                 | 12       | 7.19%   |
| Iiyama               | 10       | 5.99%   |
| Goldstar             | 10       | 5.99%   |
| Philips              | 8        | 4.79%   |
| AOC                  | 8        | 4.79%   |
| Ancor Communications | 4        | 2.4%    |
| Vestel Elektronik    | 3        | 1.8%    |
| Sony                 | 3        | 1.8%    |
| HannStar             | 3        | 1.8%    |
| Apple                | 3        | 1.8%    |
| ___                  | 2        | 1.2%    |
| ViewSonic            | 2        | 1.2%    |
| Unknown              | 2        | 1.2%    |
| MiTAC                | 2        | 1.2%    |
| Lenovo               | 2        | 1.2%    |
| HKC                  | 2        | 1.2%    |
| ASUSTek Computer     | 2        | 1.2%    |
| Toshiba              | 1        | 0.6%    |
| Targa Visionary      | 1        | 0.6%    |
| Targa                | 1        | 0.6%    |
| RTK                  | 1        | 0.6%    |
| OEM                  | 1        | 0.6%    |
| NEC Computers        | 1        | 0.6%    |
| MSI                  | 1        | 0.6%    |
| Medion               | 1        | 0.6%    |
| HYO                  | 1        | 0.6%    |
| HUAWEI               | 1        | 0.6%    |
| Daewoo               | 1        | 0.6%    |
| Unknown              | 1        | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                 | 5        | 2.69%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch | 4        | 2.15%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch | 3        | 1.61%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                     | 3        | 1.61%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch              | 3        | 1.61%   |
| ___ LCDTV16 ___9000 1360x768                                         | 2        | 1.08%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 2        | 1.08%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 2        | 1.08%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 2        | 1.08%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 2        | 1.08%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                    | 2        | 1.08%   |
| Dell E171FP DEL300F 1280x1024 340x270mm 17.1-inch                    | 2        | 1.08%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                    | 2        | 1.08%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch              | 2        | 1.08%   |
| Apple LED Cinema APP9236 1920x1200 518x324mm 24.1-inch               | 2        | 1.08%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 608x355mm 27.7-inch        | 1        | 0.54%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch        | 1        | 0.54%   |
| Toshiba TV TSB1206 1360x768                                          | 1        | 0.54%   |
| Targa Visionary LCD22-1 Wide TARA229 1680x1050 474x297mm 22.0-inch   | 1        | 0.54%   |
| Targa LCD Monitor LCDTV16 1360x768                                   | 1        | 0.54%   |
| Sony TV SNY4302 1920x1080                                            | 1        | 0.54%   |
| Sony TV  *00 SNY8004 3840x2160 1440x810mm 65.0-inch                  | 1        | 0.54%   |
| Sony SDM-HS95P SNY2600 1280x1024 376x301mm 19.0-inch                 | 1        | 0.54%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch | 1        | 0.54%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch  | 1        | 0.54%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch    | 1        | 0.54%   |
| Samsung Electronics S24C300 SAM0A28 1920x1080 531x299mm 24.0-inch    | 1        | 0.54%   |
| Samsung Electronics S19E200 SAM0C69 1440x900 408x255mm 18.9-inch     | 1        | 0.54%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch     | 1        | 0.54%   |
| Samsung Electronics LCD Monitor SAM067C 1920x1080                    | 1        | 0.54%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch    | 1        | 0.54%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch               | 1        | 0.54%   |
| Philips PHL 275E1 PHLC20C 2560x1440 600x340mm 27.2-inch              | 1        | 0.54%   |
| Philips PhilipsTV (5) PHL14CA 1360x768 708x398mm 32.0-inch           | 1        | 0.54%   |
| Philips LCD Monitor FTV 1920x1080                                    | 1        | 0.54%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                   | 1        | 0.54%   |
| OEM LCD Monitor 19W_LCD_TV                                           | 1        | 0.54%   |
| NEC Computers LCD1980SX NEC6626 1280x1024 376x301mm 19.0-inch        | 1        | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 79       | 47.59%  |
| 3840x2160 (4K)     | 14       | 8.43%   |
| 2560x1440 (QHD)    | 11       | 6.63%   |
| 1280x1024 (SXGA)   | 10       | 6.02%   |
| 1440x900 (WXGA+)   | 6        | 3.61%   |
| 1366x768 (WXGA)    | 6        | 3.61%   |
| 3440x1440          | 5        | 3.01%   |
| 1920x1200 (WUXGA)  | 5        | 3.01%   |
| 1360x768           | 5        | 3.01%   |
| Unknown            | 5        | 3.01%   |
| 1680x1050 (WSXGA+) | 4        | 2.41%   |
| 1600x900 (HD+)     | 4        | 2.41%   |
| 3840x1080          | 3        | 1.81%   |
| 1024x768 (XGA)     | 2        | 1.2%    |
| 6400x2160          | 1        | 0.6%    |
| 5280x2560          | 1        | 0.6%    |
| 4480x1440          | 1        | 0.6%    |
| 3600x1080          | 1        | 0.6%    |
| 2560x1080          | 1        | 0.6%    |
| 1920x540           | 1        | 0.6%    |
| 1600x1200          | 1        | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 29       | 17.79%  |
| 24      | 25       | 15.34%  |
| 23      | 23       | 14.11%  |
| 21      | 18       | 11.04%  |
| Unknown | 13       | 7.98%   |
| 19      | 12       | 7.36%   |
| 31      | 6        | 3.68%   |
| 34      | 5        | 3.07%   |
| 18      | 5        | 3.07%   |
| 17      | 4        | 2.45%   |
| 84      | 3        | 1.84%   |
| 72      | 3        | 1.84%   |
| 32      | 3        | 1.84%   |
| 22      | 3        | 1.84%   |
| 20      | 3        | 1.84%   |
| 15      | 2        | 1.23%   |
| 65      | 1        | 0.61%   |
| 49      | 1        | 0.61%   |
| 46      | 1        | 0.61%   |
| 35      | 1        | 0.61%   |
| 33      | 1        | 0.61%   |
| 25      | 1        | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 70       | 43.75%  |
| 401-500     | 36       | 22.5%   |
| Unknown     | 13       | 8.13%   |
| 601-700     | 10       | 6.25%   |
| 701-800     | 9        | 5.63%   |
| 351-400     | 6        | 3.75%   |
| 301-350     | 6        | 3.75%   |
| 1501-2000   | 6        | 3.75%   |
| 1001-1500   | 3        | 1.88%   |
| 801-900     | 1        | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 101      | 68.24%  |
| 16/10   | 16       | 10.81%  |
| 5/4     | 10       | 6.76%   |
| Unknown | 10       | 6.76%   |
| 21/9    | 6        | 4.05%   |
| 4/3     | 3        | 2.03%   |
| 32/9    | 1        | 0.68%   |
| 3/2     | 1        | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 54       | 32.53%  |
| 301-350        | 29       | 17.47%  |
| 151-200        | 22       | 13.25%  |
| 351-500        | 16       | 9.64%   |
| 251-300        | 13       | 7.83%   |
| Unknown        | 13       | 7.83%   |
| 141-150        | 8        | 4.82%   |
| More than 1000 | 7        | 4.22%   |
| 101-110        | 2        | 1.2%    |
| 501-1000       | 2        | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 94       | 60.65%  |
| 101-120 | 31       | 20%     |
| Unknown | 13       | 8.39%   |
| 1-50    | 8        | 5.16%   |
| 121-160 | 5        | 3.23%   |
| 161-240 | 4        | 2.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 120      | 71.43%  |
| 2     | 34       | 20.24%  |
| 0     | 10       | 5.95%   |
| 3     | 4        | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 85       | 34.98%  |
| Realtek Semiconductor             | 82       | 33.74%  |
| Qualcomm Atheros                  | 12       | 4.94%   |
| Broadcom                          | 10       | 4.12%   |
| Ralink Technology                 | 9        | 3.7%    |
| TP-Link                           | 7        | 2.88%   |
| Ralink                            | 7        | 2.88%   |
| Microsoft                         | 5        | 2.06%   |
| Nvidia                            | 3        | 1.23%   |
| Marvell Technology Group          | 3        | 1.23%   |
| Broadcom Limited                  | 3        | 1.23%   |
| Qualcomm Atheros Communications   | 2        | 0.82%   |
| Belkin Components                 | 2        | 0.82%   |
| Van Ooijen Technische Informatica | 1        | 0.41%   |
| ULi Electronics                   | 1        | 0.41%   |
| Samsung Electronics               | 1        | 0.41%   |
| NetXen Incorporated               | 1        | 0.41%   |
| NetGear                           | 1        | 0.41%   |
| Microchip Technology              | 1        | 0.41%   |
| JMicron Technology                | 1        | 0.41%   |
| IMC Networks                      | 1        | 0.41%   |
| Huawei Technologies               | 1        | 0.41%   |
| HMD Global                        | 1        | 0.41%   |
| DisplayLink                       | 1        | 0.41%   |
| ASUSTek Computer                  | 1        | 0.41%   |
| ADMtek                            | 1        | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 67       | 24.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 19       | 6.86%   |
| Intel Wi-Fi 6 AX200                                                 | 15       | 5.42%   |
| Intel I211 Gigabit Network Connection                               | 10       | 3.61%   |
| Realtek 802.11ac NIC                                                | 7        | 2.53%   |
| Intel Wireless-AC 9260                                              | 7        | 2.53%   |
| Ralink MT7601U Wireless Adapter                                     | 6        | 2.17%   |
| Intel Ethernet Connection I217-LM                                   | 6        | 2.17%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 5        | 1.81%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 5        | 1.81%   |
| Intel 82579V Gigabit Network Connection                             | 4        | 1.44%   |
| Realtek RTL8125 2.5GbE Controller                                   | 3        | 1.08%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 3        | 1.08%   |
| Intel Ethernet Connection I217-V                                    | 3        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                                | 3        | 1.08%   |
| Intel Ethernet Connection (2) I218-V                                | 3        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 3        | 1.08%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express             | 3        | 1.08%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 2        | 0.72%   |
| TP-Link 802.11ac WLAN Adapter                                       | 2        | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2        | 0.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 2        | 0.72%   |
| Ralink RT5370 Wireless Adapter                                      | 2        | 0.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 2        | 0.72%   |
| Intel Wireless 7265                                                 | 2        | 0.72%   |
| Intel I210 Gigabit Network Connection                               | 2        | 0.72%   |
| Intel Ethernet Connection (7) I219-V                                | 2        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 2        | 0.72%   |
| Intel 82583V Gigabit Network Connection                             | 2        | 0.72%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express     | 2        | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 2        | 0.72%   |
| Van Ooijen Technische Informatica XCM Board                         | 1        | 0.36%   |
| ULi ULi 1689,1573 integrated ethernet.                              | 1        | 0.36%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.36%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                 | 1        | 0.36%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 31.31%  |
| Realtek Semiconductor           | 18       | 18.18%  |
| Qualcomm Atheros                | 11       | 11.11%  |
| Ralink Technology               | 9        | 9.09%   |
| TP-Link                         | 7        | 7.07%   |
| Ralink                          | 7        | 7.07%   |
| Microsoft                       | 5        | 5.05%   |
| Broadcom                        | 3        | 3.03%   |
| Qualcomm Atheros Communications | 2        | 2.02%   |
| Belkin Components               | 2        | 2.02%   |
| NetGear                         | 1        | 1.01%   |
| IMC Networks                    | 1        | 1.01%   |
| Broadcom Limited                | 1        | 1.01%   |
| ASUSTek Computer                | 1        | 1.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 15       | 14.71%  |
| Realtek 802.11ac NIC                                                          | 7        | 6.86%   |
| Intel Wireless-AC 9260                                                        | 7        | 6.86%   |
| Ralink MT7601U Wireless Adapter                                               | 6        | 5.88%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 5        | 4.9%    |
| Ralink RT2561/RT61 802.11g PCI                                                | 3        | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 2.94%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 2        | 1.96%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 1.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2        | 1.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 1.96%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 1.96%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 1.96%   |
| Intel Wireless 7265                                                           | 2        | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 1.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 2        | 1.96%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.98%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.98%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1        | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.98%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 0.98%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.98%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1        | 0.98%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1        | 0.98%   |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                                        | 1        | 0.98%   |
| Ralink Wireless Adapter Canyon CN-WF511                                       | 1        | 0.98%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 0.98%   |
| Ralink RT5592 PCIe Wireless Network Adapter                                   | 1        | 0.98%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 1        | 0.98%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 0.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 0.98%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 73       | 43.71%  |
| Intel                    | 68       | 40.72%  |
| Broadcom                 | 8        | 4.79%   |
| Nvidia                   | 3        | 1.8%    |
| Marvell Technology Group | 3        | 1.8%    |
| Qualcomm Atheros         | 2        | 1.2%    |
| Broadcom Limited         | 2        | 1.2%    |
| ULi Electronics          | 1        | 0.6%    |
| Samsung Electronics      | 1        | 0.6%    |
| NetXen Incorporated      | 1        | 0.6%    |
| JMicron Technology       | 1        | 0.6%    |
| Huawei Technologies      | 1        | 0.6%    |
| HMD Global               | 1        | 0.6%    |
| DisplayLink              | 1        | 0.6%    |
| ADMtek                   | 1        | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 67       | 38.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 19       | 10.98%  |
| Intel I211 Gigabit Network Connection                                          | 10       | 5.78%   |
| Intel Ethernet Connection I217-LM                                              | 6        | 3.47%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 5        | 2.89%   |
| Intel 82579V Gigabit Network Connection                                        | 4        | 2.31%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3        | 1.73%   |
| Intel Ethernet Connection I217-V                                               | 3        | 1.73%   |
| Intel Ethernet Connection (2) I219-V                                           | 3        | 1.73%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 1.73%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 3        | 1.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2        | 1.16%   |
| Intel I210 Gigabit Network Connection                                          | 2        | 1.16%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1.16%   |
| Intel 82583V Gigabit Network Connection                                        | 2        | 1.16%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 2        | 1.16%   |
| ULi ULi 1689,1573 integrated ethernet.                                         | 1        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.58%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 0.58%   |
| Nvidia MCP61 Ethernet                                                          | 1        | 0.58%   |
| Nvidia MCP55 Ethernet                                                          | 1        | 0.58%   |
| Nvidia MCP51 Ethernet Controller                                               | 1        | 0.58%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter           | 1        | 0.58%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1        | 0.58%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1        | 0.58%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1        | 0.58%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1        | 0.58%   |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.58%   |
| Intel Ethernet Controller I225-V                                               | 1        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.58%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1        | 0.58%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.58%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1        | 0.58%   |
| Intel 82578DM Gigabit Network Connection                                       | 1        | 0.58%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 159      | 63.86%  |
| WiFi     | 88       | 35.34%  |
| Modem    | 2        | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 127      | 72.99%  |
| WiFi     | 47       | 27.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 101      | 61.96%  |
| 2     | 50       | 30.67%  |
| 3     | 9        | 5.52%   |
| 6     | 1        | 0.61%   |
| 4     | 1        | 0.61%   |
| 0     | 1        | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 149      | 91.41%  |
| Yes  | 14       | 8.59%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 27       | 43.55%  |
| Cambridge Silicon Radio         | 16       | 25.81%  |
| Broadcom                        | 6        | 9.68%   |
| ASUSTek Computer                | 5        | 8.06%   |
| Qualcomm Atheros Communications | 2        | 3.23%   |
| Apple                           | 2        | 3.23%   |
| Realtek Semiconductor           | 1        | 1.61%   |
| Dell                            | 1        | 1.61%   |
| Conwise Technology              | 1        | 1.61%   |
| Belkin Components               | 1        | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16       | 25.4%   |
| Intel AX200 Bluetooth                               | 13       | 20.63%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6        | 9.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5        | 7.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 4.76%   |
| Intel Bluetooth wireless interface                  | 3        | 4.76%   |
| Intel AX201 Bluetooth                               | 2        | 3.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 3.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.59%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.59%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.59%   |
| Dell BT Mini-Receiver                               | 1        | 1.59%   |
| Conwise CW6622                                      | 1        | 1.59%   |
| Broadcom BCM92045B3 ROM                             | 1        | 1.59%   |
| Belkin Components F8T012 Bluetooth Adapter          | 1        | 1.59%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 1.59%   |
| ASUS Bluetooth Device                               | 1        | 1.59%   |
| ASUS BCM20702A0                                     | 1        | 1.59%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.59%   |
| Apple Bluetooth HCI                                 | 1        | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 99       | 34.62%  |
| AMD                                             | 86       | 30.07%  |
| Nvidia                                          | 56       | 19.58%  |
| Creative Labs                                   | 5        | 1.75%   |
| Plantronics                                     | 4        | 1.4%    |
| C-Media Electronics                             | 4        | 1.4%    |
| Creative Technology                             | 3        | 1.05%   |
| Texas Instruments                               | 2        | 0.7%    |
| Logitech                                        | 2        | 0.7%    |
| Kingston Technology                             | 2        | 0.7%    |
| JMTek                                           | 2        | 0.7%    |
| Ensoniq                                         | 2        | 0.7%    |
| ULi Electronics                                 | 1        | 0.35%   |
| Turtle Beach                                    | 1        | 0.35%   |
| Sony                                            | 1        | 0.35%   |
| SAVITECH                                        | 1        | 0.35%   |
| RODE Microphones                                | 1        | 0.35%   |
| Razer USA                                       | 1        | 0.35%   |
| Native Instruments                              | 1        | 0.35%   |
| Micronas                                        | 1        | 0.35%   |
| M-Audio                                         | 1        | 0.35%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.35%   |
| GN Netcom                                       | 1        | 0.35%   |
| Giga-Byte Technology                            | 1        | 0.35%   |
| Focusrite-Novation                              | 1        | 0.35%   |
| FiiO Electronics Technology                     | 1        | 0.35%   |
| Corsair                                         | 1        | 0.35%   |
| Blue Microphones                                | 1        | 0.35%   |
| BEHRINGER International                         | 1        | 0.35%   |
| AudioQuest                                      | 1        | 0.35%   |
| Audio-Technica                                  | 1        | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 22       | 6.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 16       | 4.76%   |
| AMD Starship/Matisse HD Audio Controller                                          | 16       | 4.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 15       | 4.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 14       | 4.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 13       | 3.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12       | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12       | 3.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 2.98%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 8        | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8        | 2.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 7        | 2.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 2.08%   |
| Nvidia GM204 High Definition Audio Controller                                     | 5        | 1.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 1.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 5        | 1.49%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 5        | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 1.49%   |
| Nvidia High Definition Audio Controller                                           | 4        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 1.19%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.19%   |
| AMD Navi 10 HDMI Audio                                                            | 4        | 1.19%   |
| AMD FCH Azalia Controller                                                         | 4        | 1.19%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 4        | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.89%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 0.89%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 0.89%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.89%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 0.89%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 3        | 0.89%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2        | 0.6%    |
| Plantronics Blackwire 5220 Series                                                 | 2        | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                                     | 2        | 0.6%    |
| Nvidia MCP61 High Definition Audio                                                | 2        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 22       | 21.57%  |
| Crucial             | 15       | 14.71%  |
| Unknown             | 14       | 13.73%  |
| SK hynix            | 13       | 12.75%  |
| Kingston            | 10       | 9.8%    |
| G.Skill             | 6        | 5.88%   |
| Samsung Electronics | 5        | 4.9%    |
| Team                | 3        | 2.94%   |
| Micron Technology   | 3        | 2.94%   |
| Ramaxel Technology  | 2        | 1.96%   |
| Patriot             | 2        | 1.96%   |
| A-DATA Technology   | 2        | 1.96%   |
| Toshiba             | 1        | 0.98%   |
| Infineon            | 1        | 0.98%   |
| Elpida              | 1        | 0.98%   |
| Apacer              | 1        | 0.98%   |
| A Force             | 1        | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 5        | 4.39%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s   | 3        | 2.63%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 2        | 1.75%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 2        | 1.75%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s              | 2        | 1.75%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s    | 2        | 1.75%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 2        | 1.75%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s    | 2        | 1.75%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s    | 2        | 1.75%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s   | 2        | 1.75%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s   | 2        | 1.75%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.88%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 1        | 0.88%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                 | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                    | 1        | 0.88%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s            | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s            | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                  | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM                          | 1        | 0.88%   |
| Unknown RAM Module 1GB DIMM 667MT/s                     | 1        | 0.88%   |
| Unknown RAM Module 128MB DIMM SDRAM                     | 1        | 0.88%   |
| Toshiba RAM 99U5702-094.A00G 8192MB DIMM DDR4 2400MT/s  | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s      | 1        | 0.88%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.88%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1067MT/s           | 1        | 0.88%   |
| SK hynix RAM Module 16GB DIMM DDR3 1866MT/s             | 1        | 0.88%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s     | 1        | 0.88%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 0.88%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 0.88%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 0.88%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 0.88%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 0.88%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 0.88%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 1        | 0.88%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 1        | 0.88%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.88%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s | 1        | 0.88%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8GB DIMM DDR4 2667MT/s | 1        | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 35       | 40.23%  |
| DDR3    | 31       | 35.63%  |
| Unknown | 10       | 11.49%  |
| SDRAM   | 6        | 6.9%    |
| DDR2    | 4        | 4.6%    |
| DDR     | 1        | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 83       | 98.81%  |
| SODIMM | 1        | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 33       | 34.38%  |
| 4096  | 26       | 27.08%  |
| 2048  | 16       | 16.67%  |
| 16384 | 12       | 12.5%   |
| 1024  | 4        | 4.17%   |
| 32768 | 3        | 3.13%   |
| 512   | 1        | 1.04%   |
| 128   | 1        | 1.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 18.81%  |
| 1333    | 10       | 9.9%    |
| 3200    | 9        | 8.91%   |
| 3600    | 7        | 6.93%   |
| 2400    | 7        | 6.93%   |
| 800     | 6        | 5.94%   |
| 667     | 5        | 4.95%   |
| 2667    | 4        | 3.96%   |
| 3466    | 3        | 2.97%   |
| 2133    | 3        | 2.97%   |
| 1867    | 3        | 2.97%   |
| 1800    | 3        | 2.97%   |
| 3400    | 2        | 1.98%   |
| 1866    | 2        | 1.98%   |
| 1648    | 2        | 1.98%   |
| 1066    | 2        | 1.98%   |
| 533     | 2        | 1.98%   |
| Unknown | 2        | 1.98%   |
| 3800    | 1        | 0.99%   |
| 3733    | 1        | 0.99%   |
| 3266    | 1        | 0.99%   |
| 3000    | 1        | 0.99%   |
| 2933    | 1        | 0.99%   |
| 2733    | 1        | 0.99%   |
| 2666    | 1        | 0.99%   |
| 1639    | 1        | 0.99%   |
| 1067    | 1        | 0.99%   |
| 400     | 1        | 0.99%   |

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
| Logitech                      | 14       | 43.75%  |
| Microsoft                     | 4        | 12.5%   |
| Sunplus Innovation Technology | 2        | 6.25%   |
| Generalplus Technology        | 2        | 6.25%   |
| Creative Technology           | 2        | 6.25%   |
| Samsung Electronics           | 1        | 3.13%   |
| Realtek Semiconductor         | 1        | 3.13%   |
| Razer USA                     | 1        | 3.13%   |
| Microdia                      | 1        | 3.13%   |
| GenesysLogic Technology       | 1        | 3.13%   |
| GEMBIRD                       | 1        | 3.13%   |
| Chicony Electronics           | 1        | 3.13%   |
| Apple                         | 1        | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                       | 5        | 15.15%  |
| Microsoft LifeCam HD-3000                         | 3        | 9.09%   |
| Logitech Webcam C925e                             | 2        | 6.06%   |
| Logitech Webcam C270                              | 2        | 6.06%   |
| Creative Live! Cam Sync HD [VF0770]               | 2        | 6.06%   |
| Sunplus HD 720P webcam                            | 1        | 3.03%   |
| Sunplus Full HD webcam                            | 1        | 3.03%   |
| Samsung Galaxy A5 (MTP)                           | 1        | 3.03%   |
| Realtek Full HD webcam                            | 1        | 3.03%   |
| Razer USA Gaming Webcam [Kiyo]                    | 1        | 3.03%   |
| Microsoft LifeCam NX-3000 (UVC-compliant)         | 1        | 3.03%   |
| Microdia USB 2.0 Camera                           | 1        | 3.03%   |
| Logitech Webcam C310                              | 1        | 3.03%   |
| Logitech Webcam C210                              | 1        | 3.03%   |
| Logitech Webcam C120                              | 1        | 3.03%   |
| Logitech QuickCam Vision Pro                      | 1        | 3.03%   |
| Logitech Logitech Webcam C160                     | 1        | 3.03%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 3.03%   |
| GenesysLogic USB2.0 UVC PC Camera                 | 1        | 3.03%   |
| Generalplus GENERAL WEBCAM                        | 1        | 3.03%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 1        | 3.03%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 3.03%   |
| Chicony USB2.0 2MP UVC Camera                     | 1        | 3.03%   |
| Apple iPhone5/5C/5S/6                             | 1        | 3.03%   |

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
| 0     | 137      | 84.05%  |
| 1     | 24       | 14.72%  |
| 2     | 2        | 1.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 14       | 53.85%  |
| Graphics card         | 9        | 34.62%  |
| Multimedia controller | 2        | 7.69%   |
| Net/ethernet          | 1        | 3.85%   |

