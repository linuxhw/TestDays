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

Total: 263

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0F5C5X A00                  | [0496d0bbcf](https://linux-hardware.org/?probe=0496d0bbcf) | Feb 18, 2023 |
| Dell          | 0F5C5X A00                  | [ba5a46ec10](https://linux-hardware.org/?probe=ba5a46ec10) | Feb 18, 2023 |
| Dell          | 0200DY A02                  | [fdab522500](https://linux-hardware.org/?probe=fdab522500) | Feb 17, 2023 |
| Dell          | 0200DY A02                  | [dd863b4bdf](https://linux-hardware.org/?probe=dd863b4bdf) | Feb 17, 2023 |
| Foxconn       | H67M-S/H67M-V/H67M          | [78dc1c5856](https://linux-hardware.org/?probe=78dc1c5856) | Feb 17, 2023 |
| Dell          | 051FJ8 A00                  | [8de835c5da](https://linux-hardware.org/?probe=8de835c5da) | Feb 17, 2023 |
| Dell          | 051FJ8 A00                  | [e689bce0ca](https://linux-hardware.org/?probe=e689bce0ca) | Feb 14, 2023 |
| Dell          | 051FJ8 A00                  | [bc1c7ec97f](https://linux-hardware.org/?probe=bc1c7ec97f) | Feb 14, 2023 |
| Pegatron      | 2A94h                       | [b1b8672218](https://linux-hardware.org/?probe=b1b8672218) | Feb 13, 2023 |
| Shenzhen M... | F7BFC                       | [08820689e8](https://linux-hardware.org/?probe=08820689e8) | Feb 11, 2023 |
| MSI           | X470 GAMING PRO             | [a53ab3e915](https://linux-hardware.org/?probe=a53ab3e915) | Feb 10, 2023 |
| Gigabyte      | M68MT-S2P                   | [09735072af](https://linux-hardware.org/?probe=09735072af) | Jan 23, 2023 |
| Dell          | 0GXM1W A01                  | [dc468fd3a8](https://linux-hardware.org/?probe=dc468fd3a8) | Jan 12, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| Dell          | 0JP3NX A00                  | [21b5ec2d81](https://linux-hardware.org/?probe=21b5ec2d81) | Jan 03, 2023 |
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


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 29       | 15.34%  |
| Ubuntu 18.04       | 12       | 6.35%   |
| OpenMandriva 4.2   | 6        | 3.17%   |
| Manjaro            | 6        | 3.17%   |
| Debian 11          | 6        | 3.17%   |
| ArcoLinux Rolling  | 6        | 3.17%   |
| Ubuntu 19.04       | 5        | 2.65%   |
| Pop!_OS 22.04      | 5        | 2.65%   |
| Linux Mint 20.2    | 5        | 2.65%   |
| Linux Mint 20      | 5        | 2.65%   |
| Arch Rolling       | 5        | 2.65%   |
| Arch               | 5        | 2.65%   |
| ROSA R11           | 4        | 2.12%   |
| Pop!_OS 21.10      | 4        | 2.12%   |
| Pop!_OS 20.10      | 4        | 2.12%   |
| OpenMandriva 4.3   | 4        | 2.12%   |
| Linux Mint 20.1    | 3        | 1.59%   |
| Fedora 35          | 3        | 1.59%   |
| Fedora 32          | 3        | 1.59%   |
| BlackPanther 18.1  | 3        | 1.59%   |
| Ubuntu 22.04       | 2        | 1.06%   |
| ROSA R10           | 2        | 1.06%   |
| OpenMandriva 4.50  | 2        | 1.06%   |
| OpenMandriva 23.01 | 2        | 1.06%   |
| Linux Mint 20.3    | 2        | 1.06%   |
| Linux Mint 19      | 2        | 1.06%   |
| Linux Mint 18.3    | 2        | 1.06%   |
| KDE neon 20.04     | 2        | 1.06%   |
| Fedora 36          | 2        | 1.06%   |
| Fedora 33          | 2        | 1.06%   |
| Endless 3.7.8      | 2        | 1.06%   |
| Debian 10          | 2        | 1.06%   |
| Zorin 16           | 1        | 0.53%   |
| Zorin 15           | 1        | 0.53%   |
| Xubuntu 20.04      | 1        | 0.53%   |
| Ubuntu Core 16     | 1        | 0.53%   |
| Ubuntu 21.04       | 1        | 0.53%   |
| Ubuntu 19.10       | 1        | 0.53%   |
| SteamOS Snapshot   | 1        | 0.53%   |
| SteamOS 3.4        | 1        | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 50       | 28.57%  |
| Linux Mint   | 19       | 10.86%  |
| Pop!_OS      | 13       | 7.43%   |
| OpenMandriva | 13       | 7.43%   |
| Manjaro      | 10       | 5.71%   |
| Fedora       | 10       | 5.71%   |
| Arch         | 10       | 5.71%   |
| Debian       | 8        | 4.57%   |
| ROSA         | 6        | 3.43%   |
| ArcoLinux    | 6        | 3.43%   |
| KDE neon     | 3        | 1.71%   |
| BlackPanther | 3        | 1.71%   |
| Zorin        | 2        | 1.14%   |
| SteamOS      | 2        | 1.14%   |
| Lubuntu      | 2        | 1.14%   |
| Kubuntu      | 2        | 1.14%   |
| Kali         | 2        | 1.14%   |
| Gentoo       | 2        | 1.14%   |
| Endless      | 2        | 1.14%   |
| Elementary   | 2        | 1.14%   |
| Xubuntu      | 1        | 0.57%   |
| Solus        | 1        | 0.57%   |
| Peppermint   | 1        | 0.57%   |
| openSUSE     | 1        | 0.57%   |
| MX           | 1        | 0.57%   |
| Linux Lite   | 1        | 0.57%   |
| Feren OS     | 1        | 0.57%   |
| Clear Linux  | 1        | 0.57%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.4.0-42-generic                 | 7        | 3.26%   |
| 5.10.14-desktop-1omv4002         | 6        | 2.79%   |
| 5.4.0-48-generic                 | 4        | 1.86%   |
| 5.16.7-desktop-1omv4003          | 4        | 1.86%   |
| 5.8.0-7630-generic               | 3        | 1.4%    |
| 5.4.0-91-generic                 | 3        | 1.4%    |
| 5.4.0-47-generic                 | 3        | 1.4%    |
| 5.3.0-28-generic                 | 3        | 1.4%    |
| 5.17.5-arch1-1                   | 3        | 1.4%    |
| 5.15.11-76051511-generic         | 3        | 1.4%    |
| 4.18.16-desktop-1bP              | 3        | 1.4%    |
| 5.8.14-arch1-1                   | 2        | 0.93%   |
| 5.8.0-43-generic                 | 2        | 0.93%   |
| 5.8.0-41-generic                 | 2        | 0.93%   |
| 5.4.0-88-generic                 | 2        | 0.93%   |
| 5.4.0-77-generic                 | 2        | 0.93%   |
| 5.4.0-72-generic                 | 2        | 0.93%   |
| 5.4.0-37-generic                 | 2        | 0.93%   |
| 5.3.0-45-generic                 | 2        | 0.93%   |
| 5.17.5-76051705-generic          | 2        | 0.93%   |
| 5.16.15-76051615-generic         | 2        | 0.93%   |
| 5.15.0-46-generic                | 2        | 0.93%   |
| 5.13.13-arch1-1                  | 2        | 0.93%   |
| 5.13.0-39-generic                | 2        | 0.93%   |
| 5.12.4-desktop-1omv4050          | 2        | 0.93%   |
| 5.11.0-43-generic                | 2        | 0.93%   |
| 5.0.0-23-generic                 | 2        | 0.93%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 2        | 0.93%   |
| 4.9.60-nrj-desktop-1rosa-i586    | 2        | 0.93%   |
| 4.9.155-nrj-desktop-1rosa-x86_64 | 2        | 0.93%   |
| 4.18.0-25-generic                | 2        | 0.93%   |
| 4.15.0-desktop-45.1rosa-x86_64   | 2        | 0.93%   |
| 4.10.0-38-generic                | 2        | 0.93%   |
| 6.1.9-arch1-2                    | 1        | 0.47%   |
| 6.1.4-desktop-1omv2301           | 1        | 0.47%   |
| 6.1.1-desktop-1omv2290           | 1        | 0.47%   |
| 6.0.9-gentoo-x86_64              | 1        | 0.47%   |
| 6.0.6-arch1-1                    | 1        | 0.47%   |
| 6.0.6-76060006-generic           | 1        | 0.47%   |
| 6.0.17-300.fc37.x86_64           | 1        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 37       | 18.05%  |
| 5.8.0   | 10       | 4.88%   |
| 4.15.0  | 10       | 4.88%   |
| 5.3.0   | 8        | 3.9%    |
| 5.15.0  | 8        | 3.9%    |
| 5.11.0  | 7        | 3.41%   |
| 5.0.0   | 7        | 3.41%   |
| 5.17.5  | 6        | 2.93%   |
| 5.13.0  | 6        | 2.93%   |
| 5.10.14 | 6        | 2.93%   |
| 5.10.0  | 5        | 2.44%   |
| 4.18.0  | 5        | 2.44%   |
| 5.16.7  | 4        | 1.95%   |
| 5.19.0  | 3        | 1.46%   |
| 5.15.11 | 3        | 1.46%   |
| 4.18.16 | 3        | 1.46%   |
| 6.0.6   | 2        | 0.98%   |
| 5.8.14  | 2        | 0.98%   |
| 5.18.10 | 2        | 0.98%   |
| 5.17.6  | 2        | 0.98%   |
| 5.16.15 | 2        | 0.98%   |
| 5.16.11 | 2        | 0.98%   |
| 5.15.6  | 2        | 0.98%   |
| 5.15.12 | 2        | 0.98%   |
| 5.13.13 | 2        | 0.98%   |
| 5.12.4  | 2        | 0.98%   |
| 5.11.11 | 2        | 0.98%   |
| 5.11.10 | 2        | 0.98%   |
| 4.9.60  | 2        | 0.98%   |
| 4.9.155 | 2        | 0.98%   |
| 4.19.0  | 2        | 0.98%   |
| 4.10.0  | 2        | 0.98%   |
| 6.1.9   | 1        | 0.49%   |
| 6.1.4   | 1        | 0.49%   |
| 6.1.1   | 1        | 0.49%   |
| 6.0.9   | 1        | 0.49%   |
| 6.0.17  | 1        | 0.49%   |
| 6.0.0   | 1        | 0.49%   |
| 5.9.3   | 1        | 0.49%   |
| 5.8.7   | 1        | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 38       | 19.19%  |
| 5.15    | 18       | 9.09%   |
| 5.8     | 15       | 7.58%   |
| 5.10    | 15       | 7.58%   |
| 5.11    | 13       | 6.57%   |
| 5.16    | 10       | 5.05%   |
| 4.15    | 10       | 5.05%   |
| 5.17    | 9        | 4.55%   |
| 5.13    | 9        | 4.55%   |
| 5.3     | 8        | 4.04%   |
| 4.18    | 8        | 4.04%   |
| 5.0     | 7        | 3.54%   |
| 6.0     | 5        | 2.53%   |
| 5.12    | 5        | 2.53%   |
| 5.19    | 4        | 2.02%   |
| 6.1     | 3        | 1.52%   |
| 5.7     | 3        | 1.52%   |
| 5.6     | 3        | 1.52%   |
| 5.18    | 3        | 1.52%   |
| 4.9     | 3        | 1.52%   |
| 4.19    | 2        | 1.01%   |
| 4.10    | 2        | 1.01%   |
| 5.9     | 1        | 0.51%   |
| 5.5     | 1        | 0.51%   |
| 5.14    | 1        | 0.51%   |
| 4.4     | 1        | 0.51%   |
| 4.1     | 1        | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 167      | 98.24%  |
| i686   | 3        | 1.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 66       | 36.87%  |
| KDE5            | 39       | 21.79%  |
| Unknown         | 24       | 13.41%  |
| XFCE            | 14       | 7.82%   |
| X-Cinnamon      | 10       | 5.59%   |
| MATE            | 7        | 3.91%   |
| KDE             | 6        | 3.35%   |
| KDE4            | 4        | 2.23%   |
| LXQt            | 3        | 1.68%   |
| Pantheon        | 2        | 1.12%   |
| LXDE            | 1        | 0.56%   |
| LeftWM          | 1        | 0.56%   |
| GNOME Flashback | 1        | 0.56%   |
| Cinnamon        | 1        | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 140      | 80.92%  |
| Unknown | 15       | 8.67%   |
| Wayland | 14       | 8.09%   |
| Tty     | 4        | 2.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 93       | 52.54%  |
| SDDM    | 38       | 21.47%  |
| GDM     | 18       | 10.17%  |
| LightDM | 9        | 5.08%   |
| GDM3    | 8        | 4.52%   |
| TDM     | 5        | 2.82%   |
| KDM     | 4        | 2.26%   |
| MDM     | 1        | 0.56%   |
| LXDM    | 1        | 0.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_IE   | 83       | 46.89%  |
| en_US   | 31       | 17.51%  |
| en_GB   | 31       | 17.51%  |
| Unknown | 26       | 14.69%  |
| es_ES   | 2        | 1.13%   |
| pt_BR   | 1        | 0.56%   |
| pl_PL   | 1        | 0.56%   |
| de_DE   | 1        | 0.56%   |
| C       | 1        | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 111      | 64.16%  |
| EFI  | 62       | 35.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 136      | 79.07%  |
| Overlay | 15       | 8.72%   |
| Btrfs   | 12       | 6.98%   |
| Unknown | 7        | 4.07%   |
| Zfs     | 1        | 0.58%   |
| Xfs     | 1        | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 92       | 52.27%  |
| GPT     | 62       | 35.23%  |
| MBR     | 22       | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 136      | 78.61%  |
| Yes       | 37       | 21.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 67.82%  |
| Yes       | 56       | 32.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 38       | 22.62%  |
| Dell                                 | 34       | 20.24%  |
| Gigabyte Technology                  | 23       | 13.69%  |
| MSI                                  | 16       | 9.52%   |
| Hewlett-Packard                      | 13       | 7.74%   |
| ASRock                               | 12       | 7.14%   |
| Lenovo                               | 10       | 5.95%   |
| Foxconn                              | 5        | 2.98%   |
| Intel                                | 3        | 1.79%   |
| Shuttle                              | 2        | 1.19%   |
| Seco                                 | 2        | 1.19%   |
| Apple                                | 2        | 1.19%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.6%    |
| Pegatron                             | 1        | 0.6%    |
| Packard Bell                         | 1        | 0.6%    |
| MiTAC                                | 1        | 0.6%    |
| Medion                               | 1        | 0.6%    |
| DFI                                  | 1        | 0.6%    |
| ABIT                                 | 1        | 0.6%    |
| Unknown                              | 1        | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex 7010                         | 7        | 4.17%   |
| ASUS All Series                            | 7        | 4.17%   |
| Gigabyte B450M DS3H                        | 4        | 2.38%   |
| HP Compaq 8200 Elite SFF PC                | 3        | 1.79%   |
| Dell OptiPlex 790                          | 3        | 1.79%   |
| Dell OptiPlex 780                          | 3        | 1.79%   |
| Dell OptiPlex 7020                         | 3        | 1.79%   |
| ASUS ROG STRIX B450-F GAMING               | 3        | 1.79%   |
| Seco C40                                   | 2        | 1.19%   |
| MSI MS-7B79                                | 2        | 1.19%   |
| Lenovo ThinkStation D20 415892G            | 2        | 1.19%   |
| HP EliteDesk 800 G1 SFF                    | 2        | 1.19%   |
| Gigabyte X570 AORUS ULTRA                  | 2        | 1.19%   |
| Foxconn Pro 3500 Series                    | 2        | 1.19%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 1.19%   |
| ASUS P8P67 PRO                             | 2        | 1.19%   |
| ASUS M5A78L/USB3                           | 2        | 1.19%   |
| Shuttle XS35V4                             | 1        | 0.6%    |
| Shuttle XS35V3                             | 1        | 0.6%    |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.6%    |
| Pegatron Pro 3010 Microtower PC            | 1        | 0.6%    |
| Packard Bell Vegas2                        | 1        | 0.6%    |
| MSI Pro 3515 Series                        | 1        | 0.6%    |
| MSI MS-7C84                                | 1        | 0.6%    |
| MSI MS-7C77                                | 1        | 0.6%    |
| MSI MS-7C37                                | 1        | 0.6%    |
| MSI MS-7C02                                | 1        | 0.6%    |
| MSI MS-7B92                                | 1        | 0.6%    |
| MSI MS-7B89                                | 1        | 0.6%    |
| MSI MS-7B86                                | 1        | 0.6%    |
| MSI MS-7972                                | 1        | 0.6%    |
| MSI MS-7751                                | 1        | 0.6%    |
| MSI MS-7693                                | 1        | 0.6%    |
| MSI MS-7636                                | 1        | 0.6%    |
| MSI MS-7270                                | 1        | 0.6%    |
| MSI ER883AA-ABA M7470N                     | 1        | 0.6%    |
| MiTAC PD14TI AAPD14TI-101                  | 1        | 0.6%    |
| Medion MS-7646                             | 1        | 0.6%    |
| Lenovo V530S-07ICB 10TX002GUK              | 1        | 0.6%    |
| Lenovo ThinkCentre M91p 7052A9G            | 1        | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 22       | 13.1%   |
| Lenovo ThinkCentre                         | 7        | 4.17%   |
| ASUS PRIME                                 | 7        | 4.17%   |
| ASUS All                                   | 7        | 4.17%   |
| HP Compaq                                  | 6        | 3.57%   |
| ASUS TUF                                   | 5        | 2.98%   |
| Gigabyte B450M                             | 4        | 2.38%   |
| Dell Precision                             | 4        | 2.38%   |
| HP EliteDesk                               | 3        | 1.79%   |
| Foxconn Pro                                | 3        | 1.79%   |
| ASUS ROG                                   | 3        | 1.79%   |
| Seco C40                                   | 2        | 1.19%   |
| MSI MS-7B79                                | 2        | 1.19%   |
| Lenovo ThinkStation                        | 2        | 1.19%   |
| Intel DESKTOP                              | 2        | 1.19%   |
| Gigabyte X570                              | 2        | 1.19%   |
| Gigabyte B450                              | 2        | 1.19%   |
| Dell Vostro                                | 2        | 1.19%   |
| Dell Inspiron                              | 2        | 1.19%   |
| ASUS P8P67                                 | 2        | 1.19%   |
| ASUS Maximus                               | 2        | 1.19%   |
| ASUS M5A78L                                | 2        | 1.19%   |
| ASUS Crosshair                             | 2        | 1.19%   |
| ASRock Z77                                 | 2        | 1.19%   |
| Shuttle XS35V4                             | 1        | 0.6%    |
| Shuttle XS35V3                             | 1        | 0.6%    |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.6%    |
| Pegatron Pro                               | 1        | 0.6%    |
| Packard Bell Vegas2                        | 1        | 0.6%    |
| MSI Pro                                    | 1        | 0.6%    |
| MSI MS-7C84                                | 1        | 0.6%    |
| MSI MS-7C77                                | 1        | 0.6%    |
| MSI MS-7C37                                | 1        | 0.6%    |
| MSI MS-7C02                                | 1        | 0.6%    |
| MSI MS-7B92                                | 1        | 0.6%    |
| MSI MS-7B89                                | 1        | 0.6%    |
| MSI MS-7B86                                | 1        | 0.6%    |
| MSI MS-7972                                | 1        | 0.6%    |
| MSI MS-7751                                | 1        | 0.6%    |
| MSI MS-7693                                | 1        | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 24       | 14.29%  |
| 2013 | 23       | 13.69%  |
| 2012 | 20       | 11.9%   |
| 2011 | 18       | 10.71%  |
| 2019 | 13       | 7.74%   |
| 2010 | 13       | 7.74%   |
| 2008 | 11       | 6.55%   |
| 2020 | 9        | 5.36%   |
| 2014 | 8        | 4.76%   |
| 2017 | 7        | 4.17%   |
| 2015 | 7        | 4.17%   |
| 2009 | 4        | 2.38%   |
| 2006 | 4        | 2.38%   |
| 2007 | 3        | 1.79%   |
| 2022 | 1        | 0.6%    |
| 2021 | 1        | 0.6%    |
| 2016 | 1        | 0.6%    |
| 2005 | 1        | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 168      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 164      | 97.62%  |
| Enabled  | 4        | 2.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 168      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 45       | 25.86%  |
| 8.01-16.0   | 43       | 24.71%  |
| 3.01-4.0    | 27       | 15.52%  |
| 32.01-64.0  | 24       | 13.79%  |
| 4.01-8.0    | 20       | 11.49%  |
| 64.01-256.0 | 8        | 4.6%    |
| 24.01-32.0  | 4        | 2.3%    |
| 1.01-2.0    | 3        | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 79       | 40.72%  |
| 2.01-3.0   | 42       | 21.65%  |
| 4.01-8.0   | 24       | 12.37%  |
| 3.01-4.0   | 21       | 10.82%  |
| 0.51-1.0   | 14       | 7.22%   |
| 8.01-16.0  | 12       | 6.19%   |
| 32.01-64.0 | 1        | 0.52%   |
| 0.01-0.5   | 1        | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 35.68%  |
| 2      | 44       | 23.78%  |
| 3      | 27       | 14.59%  |
| 4      | 20       | 10.81%  |
| 5      | 12       | 6.49%   |
| 7      | 6        | 3.24%   |
| 6      | 4        | 2.16%   |
| 10     | 2        | 1.08%   |
| 0      | 2        | 1.08%   |
| 11     | 1        | 0.54%   |
| 9      | 1        | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 91       | 52.6%   |
| No        | 82       | 47.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 167      | 99.4%   |
| No        | 1        | 0.6%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 94       | 54.34%  |
| No        | 79       | 45.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 63.79%  |
| Yes       | 63       | 36.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ireland | 168      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Dublin        | 96       | 54.55%  |
| Cork          | 11       | 6.25%   |
| Limerick      | 6        | 3.41%   |
| Gorey         | 4        | 2.27%   |
| Tuam          | 3        | 1.7%    |
| Sligo         | 3        | 1.7%    |
| Portlaoise    | 3        | 1.7%    |
| Naas          | 3        | 1.7%    |
| Kenmare       | 3        | 1.7%    |
| Oranmore      | 2        | 1.14%   |
| Kildare       | 2        | 1.14%   |
| Cavan         | 2        | 1.14%   |
| Ballincollig  | 2        | 1.14%   |
| Athlone       | 2        | 1.14%   |
| Wexford       | 1        | 0.57%   |
| Tullamore     | 1        | 0.57%   |
| Tralee        | 1        | 0.57%   |
| Tipperary     | 1        | 0.57%   |
| Swords        | 1        | 0.57%   |
| Summerhill    | 1        | 0.57%   |
| Shanagolden   | 1        | 0.57%   |
| Nenagh        | 1        | 0.57%   |
| Navan         | 1        | 0.57%   |
| Moyne         | 1        | 0.57%   |
| Maynooth      | 1        | 0.57%   |
| Mallow        | 1        | 0.57%   |
| Lucan         | 1        | 0.57%   |
| Listowel      | 1        | 0.57%   |
| Letterkenny   | 1        | 0.57%   |
| Killorglin    | 1        | 0.57%   |
| Kilkenny      | 1        | 0.57%   |
| Kilcoole      | 1        | 0.57%   |
| Galway        | 1        | 0.57%   |
| Enniscorthy   | 1        | 0.57%   |
| Edenderry     | 1        | 0.57%   |
| Dunshaughlin  | 1        | 0.57%   |
| Dungarvan     | 1        | 0.57%   |
| Drumcondra    | 1        | 0.57%   |
| Droichead Nua | 1        | 0.57%   |
| Cobh          | 1        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 75       | 156    | 22.52%  |
| Seagate                     | 59       | 113    | 17.72%  |
| Samsung Electronics         | 44       | 73     | 13.21%  |
| Crucial                     | 23       | 26     | 6.91%   |
| Toshiba                     | 18       | 29     | 5.41%   |
| SanDisk                     | 14       | 24     | 4.2%    |
| Hitachi                     | 14       | 24     | 4.2%    |
| Kingston                    | 13       | 19     | 3.9%    |
| A-DATA Technology           | 8        | 13     | 2.4%    |
| Phison                      | 6        | 11     | 1.8%    |
| Verbatim                    | 4        | 4      | 1.2%    |
| Intel                       | 4        | 4      | 1.2%    |
| Micron Technology           | 3        | 3      | 0.9%    |
| China                       | 3        | 3      | 0.9%    |
| Transcend                   | 2        | 2      | 0.6%    |
| Team                        | 2        | 2      | 0.6%    |
| Silicon Motion              | 2        | 5      | 0.6%    |
| OCZ                         | 2        | 2      | 0.6%    |
| Micron/Crucial Technology   | 2        | 4      | 0.6%    |
| Maxtor                      | 2        | 2      | 0.6%    |
| LITEON                      | 2        | 2      | 0.6%    |
| WDS100T1                    | 1        | 1      | 0.3%    |
| USB3.0                      | 1        | 1      | 0.3%    |
| Unknown                     | 1        | 1      | 0.3%    |
| Union Memory (Shenzhen)     | 1        | 1      | 0.3%    |
| Union Memory                | 1        | 1      | 0.3%    |
| QNAP                        | 1        | 7      | 0.3%    |
| PNY                         | 1        | 1      | 0.3%    |
| Palit                       | 1        | 1      | 0.3%    |
| Netac                       | 1        | 1      | 0.3%    |
| MaxDigital                  | 1        | 1      | 0.3%    |
| KIOXIA                      | 1        | 2      | 0.3%    |
| Kingston Technology Company | 1        | 1      | 0.3%    |
| KingSpec                    | 1        | 1      | 0.3%    |
| KingDian                    | 1        | 1      | 0.3%    |
| KESU                        | 1        | 1      | 0.3%    |
| JMicron Technology          | 1        | 1      | 0.3%    |
| Integral                    | 1        | 1      | 0.3%    |
| Inateck                     | 1        | 1      | 0.3%    |
| HUAWEI                      | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB   | 7        | 1.72%   |
| Seagate ST8000DM004-2CX188 8TB   | 6        | 1.47%   |
| WDC WD10EURX-83UY4Y0 1TB         | 5        | 1.23%   |
| Seagate ST500DM002-1BD142 500GB  | 5        | 1.23%   |
| Verbatim Vi550 S3 SSD 256GB      | 4        | 0.98%   |
| Seagate ST2000DL003-9VT166 2TB   | 4        | 0.98%   |
| Kingston SA400S37240G 240GB SSD  | 4        | 0.98%   |
| Crucial CT1000MX500SSD1 1TB      | 4        | 0.98%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 3        | 0.74%   |
| WDC WD3200AAJS-60Z0A0 320GB      | 3        | 0.74%   |
| WDC WD20EZRX-00D8PB0 2TB         | 3        | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 0.74%   |
| WDC WD10EALX-009BA0 1TB          | 3        | 0.74%   |
| Toshiba DT01ACA100 1TB           | 3        | 0.74%   |
| Seagate ST3500418AS 500GB        | 3        | 0.74%   |
| Seagate ST3500312CS 500GB        | 3        | 0.74%   |
| Seagate ST31000528AS 1TB         | 3        | 0.74%   |
| Seagate ST2000DM006-2DM164 2TB   | 3        | 0.74%   |
| Seagate Expansion Desk 5TB       | 3        | 0.74%   |
| SanDisk NVMe SSD Drive 500GB     | 3        | 0.74%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.74%   |
| Samsung SSD 860 EVO 500GB        | 3        | 0.74%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.74%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.74%   |
| Phison Sabrent 1TB               | 3        | 0.74%   |
| Kingston SV300S37A120G 120GB SSD | 3        | 0.74%   |
| Hitachi HDS721616PLA380 160GB    | 3        | 0.74%   |
| Hitachi HDS721032CLA362 320GB    | 3        | 0.74%   |
| Crucial CT500MX500SSD1 500GB     | 3        | 0.74%   |
| A-DATA SU650 240GB SSD           | 3        | 0.74%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.49%   |
| WDC WD5000BPKT-60PK4T0 500GB     | 2        | 0.49%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 0.49%   |
| WDC WD40EZRZ-19GXCB0 4TB         | 2        | 0.49%   |
| WDC WD2500AAKX-753CA1 250GB      | 2        | 0.49%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.49%   |
| WDC WD20EARS-00MVWB0 2TB         | 2        | 0.49%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.49%   |
| Toshiba MQ01ABD100 1TB           | 2        | 0.49%   |
| Toshiba HDWD110 1TB              | 2        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 67       | 144    | 38.29%  |
| Seagate             | 58       | 112    | 33.14%  |
| Toshiba             | 17       | 27     | 9.71%   |
| Hitachi             | 14       | 24     | 8%      |
| Samsung Electronics | 8        | 9      | 4.57%   |
| Maxtor              | 2        | 2      | 1.14%   |
| USB3.0              | 1        | 1      | 0.57%   |
| Unknown             | 1        | 1      | 0.57%   |
| QNAP                | 1        | 7      | 0.57%   |
| KESU                | 1        | 1      | 0.57%   |
| HGST                | 1        | 1      | 0.57%   |
| Fujitsu             | 1        | 1      | 0.57%   |
| FNK TECH            | 1        | 1      | 0.57%   |
| ExcelStor           | 1        | 2      | 0.57%   |
| ASMT                | 1        | 1      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 29       | 44     | 25.22%  |
| Crucial             | 21       | 24     | 18.26%  |
| Kingston            | 12       | 17     | 10.43%  |
| SanDisk             | 9        | 13     | 7.83%   |
| A-DATA Technology   | 6        | 10     | 5.22%   |
| WDC                 | 5        | 8      | 4.35%   |
| Verbatim            | 4        | 4      | 3.48%   |
| Intel               | 4        | 4      | 3.48%   |
| China               | 3        | 3      | 2.61%   |
| Transcend           | 2        | 2      | 1.74%   |
| Team                | 2        | 2      | 1.74%   |
| OCZ                 | 2        | 2      | 1.74%   |
| LITEON              | 2        | 2      | 1.74%   |
| PNY                 | 1        | 1      | 0.87%   |
| Palit               | 1        | 1      | 0.87%   |
| Netac               | 1        | 1      | 0.87%   |
| Micron Technology   | 1        | 1      | 0.87%   |
| KingSpec            | 1        | 1      | 0.87%   |
| KingDian            | 1        | 1      | 0.87%   |
| Integral            | 1        | 1      | 0.87%   |
| Inateck             | 1        | 1      | 0.87%   |
| Hikvision           | 1        | 1      | 0.87%   |
| Hewlett-Packard     | 1        | 2      | 0.87%   |
| DRVEO               | 1        | 1      | 0.87%   |
| Corsair             | 1        | 2      | 0.87%   |
| Apple               | 1        | 1      | 0.87%   |
| Unknown             | 1        | 1      | 0.87%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 121      | 334    | 46.18%  |
| SSD     | 96       | 151    | 36.64%  |
| NVMe    | 40       | 72     | 15.27%  |
| Unknown | 5        | 5      | 1.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 158      | 470    | 73.49%  |
| NVMe | 40       | 72     | 18.6%   |
| SAS  | 17       | 20     | 7.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 119      | 243    | 47.22%  |
| 0.51-1.0   | 75       | 131    | 29.76%  |
| 1.01-2.0   | 26       | 40     | 10.32%  |
| 4.01-10.0  | 12       | 33     | 4.76%   |
| 3.01-4.0   | 10       | 25     | 3.97%   |
| 2.01-3.0   | 10       | 13     | 3.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 37       | 19.68%  |
| 251-500        | 30       | 15.96%  |
| 501-1000       | 27       | 14.36%  |
| More than 3000 | 26       | 13.83%  |
| 1001-2000      | 18       | 9.57%   |
| 51-100         | 16       | 8.51%   |
| 2001-3000      | 11       | 5.85%   |
| 1-20           | 10       | 5.32%   |
| Unknown        | 8        | 4.26%   |
| 21-50          | 5        | 2.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 61       | 31.44%  |
| 101-250        | 23       | 11.86%  |
| 501-1000       | 23       | 11.86%  |
| 51-100         | 22       | 11.34%  |
| 21-50          | 19       | 9.79%   |
| More than 3000 | 13       | 6.7%    |
| 251-500        | 10       | 5.15%   |
| 2001-3000      | 8        | 4.12%   |
| Unknown        | 8        | 4.12%   |
| 1001-2000      | 7        | 3.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                  | 3        | 8      | 7.14%   |
| Seagate ST2000DL003-9VT166 2TB           | 3        | 5      | 7.14%   |
| WDC WD2500AAKX-753CA1 250GB              | 2        | 3      | 4.76%   |
| WDC WD7500BPKX-00HPJT0 752GB             | 1        | 1      | 2.38%   |
| WDC WD5000HHTZ-04N21V0 500GB             | 1        | 1      | 2.38%   |
| WDC WD5000BEVT-35A0RT0 500GB             | 1        | 1      | 2.38%   |
| WDC WD5000AAKX-001CA0 500GB              | 1        | 2      | 2.38%   |
| WDC WD400JB-00FMA0 40GB                  | 1        | 2      | 2.38%   |
| WDC WD3200AVJS-63B6A0 320GB              | 1        | 1      | 2.38%   |
| WDC WD2500BEKT-75A25T0 250GB             | 1        | 1      | 2.38%   |
| WDC WD2500AAKX-603CA0 250GB              | 1        | 1      | 2.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1        | 2      | 2.38%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1        | 1      | 2.38%   |
| WDC WD1001FALS-00E8B0 1TB                | 1        | 2      | 2.38%   |
| Toshiba MK1059GSM 1TB                    | 1        | 1      | 2.38%   |
| Toshiba DT01ACA050 500GB                 | 1        | 2      | 2.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1        | 1      | 2.38%   |
| Seagate ST4000DX001-1CE168 4TB           | 1        | 1      | 2.38%   |
| Seagate ST3500418AS 500GB                | 1        | 2      | 2.38%   |
| Seagate ST31500541AS 1TB                 | 1        | 1      | 2.38%   |
| Seagate ST3120026A 120GB                 | 1        | 1      | 2.38%   |
| Seagate ST31000333AS 1TB                 | 1        | 2      | 2.38%   |
| Seagate ST3000DM001-1ER166 3TB           | 1        | 1      | 2.38%   |
| Samsung Electronics SSD 970 EVO Plus 2TB | 1        | 1      | 2.38%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 2.38%   |
| Netac SSD 128GB                          | 1        | 1      | 2.38%   |
| Micron Technology 2300 NVMe 512GB        | 1        | 1      | 2.38%   |
| Maxtor STM3250310AS 250GB                | 1        | 1      | 2.38%   |
| Intel SSDSA2M080G2GC 80GB                | 1        | 1      | 2.38%   |
| Inateck ASM1153E 2TB                     | 1        | 1      | 2.38%   |
| Hitachi HUS724030ALA640 3TB              | 1        | 2      | 2.38%   |
| Hitachi HDT721016SLA380 160GB            | 1        | 2      | 2.38%   |
| Hitachi HDS721010CLA332 1TB              | 1        | 1      | 2.38%   |
| HGST HTS541010A7E630 1TB                 | 1        | 1      | 2.38%   |
| DRVEO X1 SSD 480GB                       | 1        | 1      | 2.38%   |
| China T480 480GB SSD                     | 1        | 1      | 2.38%   |
| A-DATA Technology SU800 128GB SSD        | 1        | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 26     | 33.33%  |
| Seagate             | 10       | 14     | 25.64%  |
| Hitachi             | 3        | 5      | 7.69%   |
| Toshiba             | 2        | 3      | 5.13%   |
| Samsung Electronics | 2        | 2      | 5.13%   |
| Netac               | 1        | 1      | 2.56%   |
| Micron Technology   | 1        | 1      | 2.56%   |
| Maxtor              | 1        | 1      | 2.56%   |
| Intel               | 1        | 1      | 2.56%   |
| Inateck             | 1        | 1      | 2.56%   |
| HGST                | 1        | 1      | 2.56%   |
| DRVEO               | 1        | 1      | 2.56%   |
| China               | 1        | 1      | 2.56%   |
| A-DATA Technology   | 1        | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 26     | 41.94%  |
| Seagate             | 10       | 14     | 32.26%  |
| Hitachi             | 3        | 5      | 9.68%   |
| Toshiba             | 2        | 3      | 6.45%   |
| Samsung Electronics | 1        | 1      | 3.23%   |
| Maxtor              | 1        | 1      | 3.23%   |
| HGST                | 1        | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 51     | 75.76%  |
| SSD  | 6        | 6      | 18.18%  |
| NVMe | 2        | 2      | 6.06%   |

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
| Detected | 100      | 296    | 49.75%  |
| Works    | 70       | 207    | 34.83%  |
| Malfunc  | 31       | 59     | 15.42%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 104      | 44.07%  |
| AMD                          | 54       | 22.88%  |
| Samsung Electronics          | 14       | 5.93%   |
| SanDisk                      | 9        | 3.81%   |
| Marvell Technology Group     | 8        | 3.39%   |
| ASMedia Technology           | 8        | 3.39%   |
| Phison Electronics           | 6        | 2.54%   |
| Nvidia                       | 5        | 2.12%   |
| JMicron Technology           | 5        | 2.12%   |
| Micron/Crucial Technology    | 4        | 1.69%   |
| LSI Logic / Symbios Logic    | 3        | 1.27%   |
| Union Memory (Shenzhen)      | 2        | 0.85%   |
| Toshiba America Info Systems | 2        | 0.85%   |
| Silicon Motion               | 2        | 0.85%   |
| Realtek Semiconductor        | 2        | 0.85%   |
| Micron Technology            | 2        | 0.85%   |
| Kingston Technology Company  | 2        | 0.85%   |
| ULi Electronics              | 1        | 0.42%   |
| Seagate Technology           | 1        | 0.42%   |
| KIOXIA                       | 1        | 0.42%   |
| Broadcom / LSI               | 1        | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 36       | 11.73%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 5.21%   |
| AMD 400 Series Chipset SATA Controller                                                  | 16       | 5.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 4.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 3.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 3.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9        | 2.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9        | 2.93%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 2.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.61%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 2.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 2.28%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 6        | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.95%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 1.63%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 1.3%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.3%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 1.3%    |
| AMD FCH SATA Controller D                                                               | 4        | 1.3%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.98%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 0.98%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 2        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.65%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.65%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.65%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.65%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.65%   |
| Micron Non-Volatile memory controller                                                   | 2        | 0.65%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 2        | 0.65%   |
| Marvell Group 88SE9182 PCIe 2.0 x2 2-port SATA 6 Gb/s Controller                        | 2        | 0.65%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 2        | 0.65%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 2        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 138      | 58.97%  |
| IDE  | 45       | 19.23%  |
| NVMe | 40       | 17.09%  |
| RAID | 9        | 3.85%   |
| SCSI | 2        | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 108      | 64.29%  |
| AMD    | 60       | 35.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 7        | 4.09%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 6        | 3.51%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 5        | 2.92%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 4        | 2.34%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 4        | 2.34%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 4        | 2.34%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 4        | 2.34%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 4        | 2.34%   |
| Intel Core i3-4150 CPU @ 3.50GHz               | 3        | 1.75%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 3        | 1.75%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 3        | 1.75%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3        | 1.75%   |
| AMD Athlon II X4 620 Processor                 | 3        | 1.75%   |
| Intel Xeon CPU X5690 @ 3.47GHz                 | 2        | 1.17%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 2        | 1.17%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 2        | 1.17%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 2        | 1.17%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 2        | 1.17%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 2        | 1.17%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 2        | 1.17%   |
| Intel Core i5-10500 CPU @ 3.10GHz              | 2        | 1.17%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 1.17%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 2        | 1.17%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz          | 2        | 1.17%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 1.17%   |
| AMD Ryzen Embedded V1605B with Radeon Vega Gfx | 2        | 1.17%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 1.17%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 1.17%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 1.17%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 2        | 1.17%   |
| AMD FX-6300 Six-Core Processor                 | 2        | 1.17%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+     | 2        | 1.17%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 0.58%   |
| Intel Xeon CPU E5462 @ 2.80GHz                 | 1        | 0.58%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz            | 1        | 0.58%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz            | 1        | 0.58%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz       | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 1        | 0.58%   |
| Intel Pentium D CPU 2.80GHz                    | 1        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 33       | 19.3%   |
| Intel Core i7           | 29       | 16.96%  |
| Intel Core i3           | 18       | 10.53%  |
| AMD Ryzen 5             | 17       | 9.94%   |
| Intel Core 2 Quad       | 8        | 4.68%   |
| AMD Ryzen 9             | 7        | 4.09%   |
| Intel Xeon              | 6        | 3.51%   |
| AMD FX                  | 5        | 2.92%   |
| AMD Athlon 64 X2        | 5        | 2.92%   |
| Intel Core 2 Duo        | 4        | 2.34%   |
| AMD Ryzen 7             | 4        | 2.34%   |
| Intel Celeron           | 3        | 1.75%   |
| AMD Ryzen 3             | 3        | 1.75%   |
| AMD Athlon II X4        | 3        | 1.75%   |
| Intel Pentium Dual-Core | 2        | 1.17%   |
| Intel Pentium 4         | 2        | 1.17%   |
| Intel Pentium           | 2        | 1.17%   |
| Intel Atom              | 2        | 1.17%   |
| AMD Ryzen Threadripper  | 2        | 1.17%   |
| AMD Ryzen Embedded      | 2        | 1.17%   |
| AMD Phenom II X6        | 2        | 1.17%   |
| AMD Phenom II X4        | 2        | 1.17%   |
| AMD A6                  | 2        | 1.17%   |
| AMD A4                  | 2        | 1.17%   |
| Intel Pentium Silver    | 1        | 0.58%   |
| Intel Pentium D         | 1        | 0.58%   |
| AMD PRO A10             | 1        | 0.58%   |
| AMD GX                  | 1        | 0.58%   |
| AMD Athlon II X2        | 1        | 0.58%   |
| AMD Athlon Dual Core    | 1        | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 83       | 49.11%  |
| 2       | 35       | 20.71%  |
| 6       | 24       | 14.2%   |
| 12      | 9        | 5.33%   |
| 8       | 8        | 4.73%   |
| 1       | 6        | 3.55%   |
| 3       | 2        | 1.18%   |
| 32      | 1        | 0.59%   |
| Unknown | 1        | 0.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 165      | 98.21%  |
| 2      | 3        | 1.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 95       | 55.56%  |
| 1       | 75       | 43.86%  |
| Unknown | 1        | 0.58%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 165      | 98.21%  |
| Unknown        | 3        | 1.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 45       | 25.86%  |
| 0x306a9    | 18       | 10.34%  |
| 0x306c3    | 15       | 8.62%   |
| 0x206a7    | 13       | 7.47%   |
| 0x1067a    | 9        | 5.17%   |
| 0x08701021 | 7        | 4.02%   |
| 0x0800820d | 5        | 2.87%   |
| 0xa0653    | 3        | 1.72%   |
| 0x906ea    | 3        | 1.72%   |
| 0x6fb      | 3        | 1.72%   |
| 0x506e3    | 3        | 1.72%   |
| 0x206c2    | 3        | 1.72%   |
| 0x08108109 | 3        | 1.72%   |
| 0x0810100b | 3        | 1.72%   |
| 0x06000852 | 3        | 1.72%   |
| 0x906e9    | 2        | 1.15%   |
| 0x30661    | 2        | 1.15%   |
| 0x106a5    | 2        | 1.15%   |
| 0x08701013 | 2        | 1.15%   |
| 0x0600611a | 2        | 1.15%   |
| 0x010000db | 2        | 1.15%   |
| 0x010000c8 | 2        | 1.15%   |
| 0xf47      | 1        | 0.57%   |
| 0xf43      | 1        | 0.57%   |
| 0xf41      | 1        | 0.57%   |
| 0xa0655    | 1        | 0.57%   |
| 0x906ed    | 1        | 0.57%   |
| 0x906eb    | 1        | 0.57%   |
| 0x706a1    | 1        | 0.57%   |
| 0x6f7      | 1        | 0.57%   |
| 0x306e4    | 1        | 0.57%   |
| 0x30678    | 1        | 0.57%   |
| 0x106e5    | 1        | 0.57%   |
| 0x10677    | 1        | 0.57%   |
| 0x10676    | 1        | 0.57%   |
| 0x0a20120a | 1        | 0.57%   |
| 0x0a201205 | 1        | 0.57%   |
| 0x0a201016 | 1        | 0.57%   |
| 0x08301039 | 1        | 0.57%   |
| 0x08101016 | 1        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 25       | 14.79%  |
| SandyBridge   | 18       | 10.65%  |
| Haswell       | 18       | 10.65%  |
| Zen 2         | 14       | 8.28%   |
| Zen+          | 12       | 7.1%    |
| Penryn        | 11       | 6.51%   |
| KabyLake      | 10       | 5.92%   |
| K10           | 8        | 4.73%   |
| Zen           | 6        | 3.55%   |
| Piledriver    | 6        | 3.55%   |
| K8 Hammer     | 6        | 3.55%   |
| Nehalem       | 5        | 2.96%   |
| Core          | 4        | 2.37%   |
| CometLake     | 4        | 2.37%   |
| Westmere      | 3        | 1.78%   |
| Skylake       | 3        | 1.78%   |
| NetBurst      | 3        | 1.78%   |
| Zen 3         | 2        | 1.18%   |
| Goldmont plus | 2        | 1.18%   |
| Excavator     | 2        | 1.18%   |
| Bonnell       | 2        | 1.18%   |
| Steamroller   | 1        | 0.59%   |
| Silvermont    | 1        | 0.59%   |
| Jaguar        | 1        | 0.59%   |
| Bulldozer     | 1        | 0.59%   |
| Unknown       | 1        | 0.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 71       | 37.97%  |
| Nvidia | 61       | 32.62%  |
| Intel  | 55       | 29.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8        | 4.08%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 8        | 4.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 3.57%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 3.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 3.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 2.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.55%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 2.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.04%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 4        | 2.04%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 1.53%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.53%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.53%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.53%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 3        | 1.53%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.53%   |
| Intel HD Graphics 630                                                       | 3        | 1.53%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.53%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.53%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.53%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.02%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.02%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 1.02%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 2        | 1.02%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 1.02%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 1.02%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.51%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.51%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.51%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.51%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.51%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.51%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.51%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.51%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.51%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 64       | 36.57%  |
| 1 x Nvidia     | 57       | 32.57%  |
| 1 x Intel      | 43       | 24.57%  |
| 2 x AMD        | 6        | 3.43%   |
| Intel + Nvidia | 3        | 1.71%   |
| 2 x Intel      | 1        | 0.57%   |
| AMD + Nvidia   | 1        | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 134      | 77.46%  |
| Proprietary | 30       | 17.34%  |
| Unknown     | 9        | 5.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 74       | 41.57%  |
| 0.51-1.0   | 24       | 13.48%  |
| 1.01-2.0   | 21       | 11.8%   |
| 7.01-8.0   | 18       | 10.11%  |
| 3.01-4.0   | 16       | 8.99%   |
| 0.01-0.5   | 12       | 6.74%   |
| 5.01-6.0   | 8        | 4.49%   |
| 2.01-3.0   | 2        | 1.12%   |
| 8.01-16.0  | 2        | 1.12%   |
| 16.01-24.0 | 1        | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 36       | 20.22%  |
| Samsung Electronics  | 15       | 8.43%   |
| Acer                 | 15       | 8.43%   |
| Hewlett-Packard      | 13       | 7.3%    |
| BenQ                 | 13       | 7.3%    |
| Philips              | 10       | 5.62%   |
| Iiyama               | 10       | 5.62%   |
| Goldstar             | 10       | 5.62%   |
| AOC                  | 8        | 4.49%   |
| Ancor Communications | 4        | 2.25%   |
| Vestel Elektronik    | 3        | 1.69%   |
| Sony                 | 3        | 1.69%   |
| HannStar             | 3        | 1.69%   |
| Apple                | 3        | 1.69%   |
| ___                  | 2        | 1.12%   |
| ViewSonic            | 2        | 1.12%   |
| Unknown              | 2        | 1.12%   |
| Toshiba              | 2        | 1.12%   |
| MiTAC                | 2        | 1.12%   |
| Lenovo               | 2        | 1.12%   |
| HKC                  | 2        | 1.12%   |
| ASUSTek Computer     | 2        | 1.12%   |
| WIT                  | 1        | 0.56%   |
| Targa Visionary      | 1        | 0.56%   |
| Targa                | 1        | 0.56%   |
| RTK                  | 1        | 0.56%   |
| OEM                  | 1        | 0.56%   |
| NEC Computers        | 1        | 0.56%   |
| MSI                  | 1        | 0.56%   |
| Medion               | 1        | 0.56%   |
| LG Electronics       | 1        | 0.56%   |
| Idek Iiyama          | 1        | 0.56%   |
| HYO                  | 1        | 0.56%   |
| HUAWEI               | 1        | 0.56%   |
| Daewoo               | 1        | 0.56%   |
| CVT                  | 1        | 0.56%   |
| CTX                  | 1        | 0.56%   |
| Unknown              | 1        | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                 | 5        | 2.53%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch | 4        | 2.02%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                     | 3        | 1.52%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                     | 3        | 1.52%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch              | 3        | 1.52%   |
| ___ LCD TV ___9000 1360x768                                          | 2        | 1.01%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 2        | 1.01%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 2        | 1.01%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 2        | 1.01%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 2        | 1.01%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                    | 2        | 1.01%   |
| Dell E171FP DEL300F 1280x1024 338x270mm 17.0-inch                    | 2        | 1.01%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                    | 2        | 1.01%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch              | 2        | 1.01%   |
| Apple LED Cinema APP9236 1920x1200 518x324mm 24.1-inch               | 2        | 1.01%   |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                       | 1        | 0.51%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 608x355mm 27.7-inch        | 1        | 0.51%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch        | 1        | 0.51%   |
| Toshiba TV TSB1206 1360x768                                          | 1        | 0.51%   |
| Toshiba 43FHD_LCD_TV TSB3700 1920x1080 1360x768mm 61.5-inch          | 1        | 0.51%   |
| Targa Visionary LCD22-1 Wide TARA229 1680x1050 474x297mm 22.0-inch   | 1        | 0.51%   |
| Targa LCD Monitor LCDTV16 1360x768                                   | 1        | 0.51%   |
| Sony TV SNY4302 1920x1080                                            | 1        | 0.51%   |
| Sony TV *00 SNY8004 3840x2160 1439x809mm 65.0-inch                   | 1        | 0.51%   |
| Sony SDM-HS95P SNY2600 1280x1024 376x301mm 19.0-inch                 | 1        | 0.51%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch | 1        | 0.51%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch  | 1        | 0.51%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch    | 1        | 0.51%   |
| Samsung Electronics S24C300 SAM0A28 1920x1080 531x299mm 24.0-inch    | 1        | 0.51%   |
| Samsung Electronics S19E200 SAM0C69 1440x900 408x255mm 18.9-inch     | 1        | 0.51%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch     | 1        | 0.51%   |
| Samsung Electronics LCD Monitor SAM067C 1920x1080                    | 1        | 0.51%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch    | 1        | 0.51%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch               | 1        | 0.51%   |
| Philips PHL 275E1 PHLC20C 2560x1440 597x336mm 27.0-inch              | 1        | 0.51%   |
| Philips PHL 272V8 PHLC21A 1920x1080 598x336mm 27.0-inch              | 1        | 0.51%   |
| Philips PhilipsTV (5) PHL14CA 1360x768 708x398mm 32.0-inch           | 1        | 0.51%   |
| Philips LCD Monitor PHL 241B8Q 1920x1080                             | 1        | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 84       | 47.73%  |
| 3840x2160 (4K)     | 15       | 8.52%   |
| 2560x1440 (QHD)    | 11       | 6.25%   |
| 1280x1024 (SXGA)   | 11       | 6.25%   |
| 1440x900 (WXGA+)   | 6        | 3.41%   |
| 1366x768 (WXGA)    | 6        | 3.41%   |
| 1360x768           | 6        | 3.41%   |
| Unknown            | 6        | 3.41%   |
| 3440x1440          | 5        | 2.84%   |
| 1920x1200 (WUXGA)  | 5        | 2.84%   |
| 3840x1080          | 4        | 2.27%   |
| 1680x1050 (WSXGA+) | 4        | 2.27%   |
| 1600x900 (HD+)     | 4        | 2.27%   |
| 1024x768 (XGA)     | 2        | 1.14%   |
| 6400x2160          | 1        | 0.57%   |
| 5280x2560          | 1        | 0.57%   |
| 4480x1440          | 1        | 0.57%   |
| 3600x1080          | 1        | 0.57%   |
| 2560x1080          | 1        | 0.57%   |
| 1920x540           | 1        | 0.57%   |
| 1600x1200          | 1        | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 30       | 17.24%  |
| 24      | 29       | 16.67%  |
| 23      | 23       | 13.22%  |
| 21      | 19       | 10.92%  |
| Unknown | 15       | 8.62%   |
| 19      | 12       | 6.9%    |
| 34      | 6        | 3.45%   |
| 31      | 6        | 3.45%   |
| 18      | 5        | 2.87%   |
| 17      | 5        | 2.87%   |
| 84      | 4        | 2.3%    |
| 72      | 3        | 1.72%   |
| 32      | 3        | 1.72%   |
| 22      | 3        | 1.72%   |
| 20      | 3        | 1.72%   |
| 15      | 2        | 1.15%   |
| 65      | 1        | 0.57%   |
| 49      | 1        | 0.57%   |
| 46      | 1        | 0.57%   |
| 35      | 1        | 0.57%   |
| 33      | 1        | 0.57%   |
| 25      | 1        | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 74       | 43.53%  |
| 401-500     | 37       | 21.76%  |
| Unknown     | 15       | 8.82%   |
| 701-800     | 10       | 5.88%   |
| 601-700     | 10       | 5.88%   |
| 301-350     | 7        | 4.12%   |
| 1501-2000   | 7        | 4.12%   |
| 351-400     | 6        | 3.53%   |
| 1001-1500   | 3        | 1.76%   |
| 801-900     | 1        | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 107      | 68.15%  |
| 16/10   | 16       | 10.19%  |
| Unknown | 12       | 7.64%   |
| 5/4     | 11       | 7.01%   |
| 21/9    | 6        | 3.82%   |
| 4/3     | 3        | 1.91%   |
| 32/9    | 1        | 0.64%   |
| 3/2     | 1        | 0.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 58       | 32.95%  |
| 301-350        | 30       | 17.05%  |
| 151-200        | 22       | 12.5%   |
| 351-500        | 16       | 9.09%   |
| Unknown        | 15       | 8.52%   |
| 251-300        | 13       | 7.39%   |
| 141-150        | 9        | 5.11%   |
| More than 1000 | 8        | 4.55%   |
| 501-1000       | 3        | 1.7%    |
| 101-110        | 2        | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 100      | 60.61%  |
| 101-120 | 32       | 19.39%  |
| Unknown | 15       | 9.09%   |
| 1-50    | 9        | 5.45%   |
| 121-160 | 5        | 3.03%   |
| 161-240 | 4        | 2.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 127      | 71.35%  |
| 2     | 37       | 20.79%  |
| 0     | 10       | 5.62%   |
| 3     | 4        | 2.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 91       | 34.87%  |
| Realtek Semiconductor             | 85       | 32.57%  |
| Qualcomm Atheros                  | 13       | 4.98%   |
| Broadcom                          | 11       | 4.21%   |
| Ralink Technology                 | 10       | 3.83%   |
| TP-Link                           | 8        | 3.07%   |
| Ralink                            | 8        | 3.07%   |
| Microsoft                         | 5        | 1.92%   |
| Nvidia                            | 4        | 1.53%   |
| Marvell Technology Group          | 3        | 1.15%   |
| Broadcom Limited                  | 3        | 1.15%   |
| Qualcomm Atheros Communications   | 2        | 0.77%   |
| NetGear                           | 2        | 0.77%   |
| Huawei Technologies               | 2        | 0.77%   |
| Belkin Components                 | 2        | 0.77%   |
| Van Ooijen Technische Informatica | 1        | 0.38%   |
| ULi Electronics                   | 1        | 0.38%   |
| Samsung Electronics               | 1        | 0.38%   |
| NetXen Incorporated               | 1        | 0.38%   |
| Microchip Technology              | 1        | 0.38%   |
| MediaTek                          | 1        | 0.38%   |
| JMicron Technology                | 1        | 0.38%   |
| IMC Networks                      | 1        | 0.38%   |
| HMD Global                        | 1        | 0.38%   |
| DisplayLink                       | 1        | 0.38%   |
| ASUSTek Computer                  | 1        | 0.38%   |
| ADMtek                            | 1        | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68       | 23.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21       | 7.12%   |
| Intel Wi-Fi 6 AX200                                               | 15       | 5.08%   |
| Intel I211 Gigabit Network Connection                             | 10       | 3.39%   |
| Realtek 802.11ac NIC                                              | 8        | 2.71%   |
| Intel Wireless-AC 9260                                            | 7        | 2.37%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.37%   |
| Ralink MT7601U Wireless Adapter                                   | 6        | 2.03%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 2.03%   |
| Microsoft Xbox 360 Wireless Adapter                               | 5        | 1.69%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 4        | 1.36%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.36%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.36%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 3        | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.02%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 1.02%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.02%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.02%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 3        | 1.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 1.02%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.68%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.68%   |
| Intel Wireless 7265                                               | 2        | 0.68%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2        | 0.68%   |
| Intel 82583V Gigabit Network Connection                           | 2        | 0.68%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 2        | 0.68%   |
| Van Ooijen Technische Informatica XCM Board                       | 1        | 0.34%   |
| ULi ULi 1689,1573 integrated ethernet.                            | 1        | 0.34%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.34%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 28.7%   |
| Realtek Semiconductor           | 20       | 18.52%  |
| Qualcomm Atheros                | 12       | 11.11%  |
| Ralink Technology               | 10       | 9.26%   |
| TP-Link                         | 8        | 7.41%   |
| Ralink                          | 8        | 7.41%   |
| Microsoft                       | 5        | 4.63%   |
| Broadcom                        | 4        | 3.7%    |
| Qualcomm Atheros Communications | 2        | 1.85%   |
| NetGear                         | 2        | 1.85%   |
| Belkin Components               | 2        | 1.85%   |
| MediaTek                        | 1        | 0.93%   |
| IMC Networks                    | 1        | 0.93%   |
| Broadcom Limited                | 1        | 0.93%   |
| ASUSTek Computer                | 1        | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 15       | 13.51%  |
| Realtek 802.11ac NIC                                                          | 8        | 7.21%   |
| Intel Wireless-AC 9260                                                        | 7        | 6.31%   |
| Ralink MT7601U Wireless Adapter                                               | 6        | 5.41%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 5        | 4.5%    |
| Ralink RT2561/RT61 802.11g PCI                                                | 4        | 3.6%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 3        | 2.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 2.7%    |
| Ralink RT5370 Wireless Adapter                                                | 3        | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 2.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 3        | 2.7%    |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 1.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2        | 1.8%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 1.8%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 1.8%    |
| Intel Wireless 7265                                                           | 2        | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 1.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.9%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.9%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1        | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.9%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 0.9%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.9%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.9%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1        | 0.9%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1        | 0.9%    |
| Ralink Wireless Adapter Canyon CN-WF511                                       | 1        | 0.9%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 0.9%    |
| Ralink RT5592 PCIe Wireless Network Adapter                                   | 1        | 0.9%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 1        | 0.9%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 0.9%    |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.9%    |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 74       | 42.29%  |
| Intel                    | 74       | 42.29%  |
| Broadcom                 | 8        | 4.57%   |
| Nvidia                   | 4        | 2.29%   |
| Marvell Technology Group | 3        | 1.71%   |
| Qualcomm Atheros         | 2        | 1.14%   |
| Broadcom Limited         | 2        | 1.14%   |
| ULi Electronics          | 1        | 0.57%   |
| Samsung Electronics      | 1        | 0.57%   |
| NetXen Incorporated      | 1        | 0.57%   |
| JMicron Technology       | 1        | 0.57%   |
| Huawei Technologies      | 1        | 0.57%   |
| HMD Global               | 1        | 0.57%   |
| DisplayLink              | 1        | 0.57%   |
| ADMtek                   | 1        | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 68       | 37.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 21       | 11.6%   |
| Intel I211 Gigabit Network Connection                                          | 10       | 5.52%   |
| Intel Ethernet Connection I217-LM                                              | 7        | 3.87%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 6        | 3.31%   |
| Intel Ethernet Connection (2) I218-V                                           | 4        | 2.21%   |
| Intel 82579V Gigabit Network Connection                                        | 4        | 2.21%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3        | 1.66%   |
| Intel Ethernet Connection I217-V                                               | 3        | 1.66%   |
| Intel Ethernet Connection (2) I219-V                                           | 3        | 1.66%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 3        | 1.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2        | 1.1%    |
| Nvidia MCP61 Ethernet                                                          | 2        | 1.1%    |
| Intel I210 Gigabit Network Connection                                          | 2        | 1.1%    |
| Intel Ethernet Controller I225-V                                               | 2        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1.1%    |
| Intel 82583V Gigabit Network Connection                                        | 2        | 1.1%    |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 2        | 1.1%    |
| ULi ULi 1689,1573 integrated ethernet.                                         | 1        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 0.55%   |
| Nvidia MCP55 Ethernet                                                          | 1        | 0.55%   |
| Nvidia MCP51 Ethernet Controller                                               | 1        | 0.55%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter           | 1        | 0.55%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1        | 0.55%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1        | 0.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1        | 0.55%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1        | 0.55%   |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.55%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1        | 0.55%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.55%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1        | 0.55%   |
| Intel 82578DM Gigabit Network Connection                                       | 1        | 0.55%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 167      | 63.26%  |
| WiFi     | 94       | 35.61%  |
| Modem    | 3        | 1.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 131      | 72.38%  |
| WiFi     | 50       | 27.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 105      | 61.4%   |
| 2     | 54       | 31.58%  |
| 3     | 9        | 5.26%   |
| 6     | 1        | 0.58%   |
| 4     | 1        | 0.58%   |
| 0     | 1        | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 156      | 91.23%  |
| Yes  | 15       | 8.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 27       | 40.91%  |
| Cambridge Silicon Radio         | 17       | 25.76%  |
| Broadcom                        | 6        | 9.09%   |
| ASUSTek Computer                | 6        | 9.09%   |
| Qualcomm Atheros Communications | 2        | 3.03%   |
| Belkin Components               | 2        | 3.03%   |
| Apple                           | 2        | 3.03%   |
| Realtek Semiconductor           | 1        | 1.52%   |
| MediaTek                        | 1        | 1.52%   |
| Dell                            | 1        | 1.52%   |
| Conwise Technology              | 1        | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17       | 25.37%  |
| Intel AX200 Bluetooth                               | 13       | 19.4%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6        | 8.96%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5        | 7.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 4.48%   |
| Intel Bluetooth wireless interface                  | 3        | 4.48%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3        | 4.48%   |
| Intel AX201 Bluetooth                               | 2        | 2.99%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.49%   |
| MediaTek Wireless_Device                            | 1        | 1.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.49%   |
| Dell BT Mini-Receiver                               | 1        | 1.49%   |
| Conwise CW6622                                      | 1        | 1.49%   |
| Broadcom BCM92045B3 ROM                             | 1        | 1.49%   |
| Belkin Components F8T012 Bluetooth Adapter          | 1        | 1.49%   |
| Belkin Components Bluetooth Mini Dongle             | 1        | 1.49%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 1.49%   |
| ASUS Bluetooth Device                               | 1        | 1.49%   |
| ASUS BCM20702A0                                     | 1        | 1.49%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.49%   |
| Apple Bluetooth HCI                                 | 1        | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 105      | 35.35%  |
| AMD                                             | 88       | 29.63%  |
| Nvidia                                          | 57       | 19.19%  |
| Creative Labs                                   | 5        | 1.68%   |
| Plantronics                                     | 4        | 1.35%   |
| C-Media Electronics                             | 4        | 1.35%   |
| Kingston Technology                             | 3        | 1.01%   |
| Creative Technology                             | 3        | 1.01%   |
| Texas Instruments                               | 2        | 0.67%   |
| Logitech                                        | 2        | 0.67%   |
| JMTek                                           | 2        | 0.67%   |
| Ensoniq                                         | 2        | 0.67%   |
| ULi Electronics                                 | 1        | 0.34%   |
| Turtle Beach                                    | 1        | 0.34%   |
| Sony                                            | 1        | 0.34%   |
| SAVITECH                                        | 1        | 0.34%   |
| RODE Microphones                                | 1        | 0.34%   |
| Razer USA                                       | 1        | 0.34%   |
| Native Instruments                              | 1        | 0.34%   |
| Micronas                                        | 1        | 0.34%   |
| M-Audio                                         | 1        | 0.34%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.34%   |
| GN Netcom                                       | 1        | 0.34%   |
| Giga-Byte Technology                            | 1        | 0.34%   |
| Focusrite-Novation                              | 1        | 0.34%   |
| FiiO Electronics Technology                     | 1        | 0.34%   |
| Corsair                                         | 1        | 0.34%   |
| Blue Microphones                                | 1        | 0.34%   |
| BEHRINGER International                         | 1        | 0.34%   |
| AudioQuest                                      | 1        | 0.34%   |
| Audio-Technica                                  | 1        | 0.34%   |
| AOKEO                                           | 1        | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 23       | 6.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 18       | 5.14%   |
| AMD Starship/Matisse HD Audio Controller                                          | 16       | 4.57%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 15       | 4.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 14       | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 13       | 3.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13       | 3.71%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 13       | 3.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 2.86%   |
| AMD Family 17h/19h HD Audio Controller                                            | 9        | 2.57%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 8        | 2.29%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 7        | 2%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 2%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 6        | 1.71%   |
| Nvidia GM204 High Definition Audio Controller                                     | 5        | 1.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 5        | 1.43%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 5        | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 1.43%   |
| Nvidia High Definition Audio Controller                                           | 4        | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 1.14%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 1.14%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.14%   |
| AMD Navi 10 HDMI Audio                                                            | 4        | 1.14%   |
| AMD FCH Azalia Controller                                                         | 4        | 1.14%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 4        | 1.14%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.86%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 0.86%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 0.86%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.86%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 0.86%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 3        | 0.86%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2        | 0.57%   |
| Plantronics Blackwire 5220 Series                                                 | 2        | 0.57%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 22       | 21.15%  |
| Crucial             | 16       | 15.38%  |
| Unknown             | 14       | 13.46%  |
| SK hynix            | 13       | 12.5%   |
| Kingston            | 10       | 9.62%   |
| Samsung Electronics | 6        | 5.77%   |
| G.Skill             | 6        | 5.77%   |
| Team                | 3        | 2.88%   |
| Micron Technology   | 3        | 2.88%   |
| Ramaxel Technology  | 2        | 1.92%   |
| Patriot             | 2        | 1.92%   |
| A-DATA Technology   | 2        | 1.92%   |
| Toshiba             | 1        | 0.96%   |
| Infineon            | 1        | 0.96%   |
| Elpida              | 1        | 0.96%   |
| Apacer              | 1        | 0.96%   |
| A Force             | 1        | 0.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 5        | 4.31%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s   | 3        | 2.59%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 2        | 1.72%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 2        | 1.72%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                   | 2        | 1.72%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s    | 2        | 1.72%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 1.72%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s    | 2        | 1.72%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s    | 2        | 1.72%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM 1600MT/s        | 2        | 1.72%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s   | 2        | 1.72%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.86%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 1        | 0.86%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                 | 1        | 0.86%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                    | 1        | 0.86%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s            | 1        | 0.86%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 1        | 0.86%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s            | 1        | 0.86%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                  | 1        | 0.86%   |
| Unknown RAM Module 2048MB DIMM                          | 1        | 0.86%   |
| Unknown RAM Module 1GB DIMM 667MT/s                     | 1        | 0.86%   |
| Unknown RAM Module 128MB DIMM SDRAM                     | 1        | 0.86%   |
| Toshiba RAM 99U5702-094.A00G 8192MB DIMM DDR4 2400MT/s  | 1        | 0.86%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s      | 1        | 0.86%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.86%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1067MT/s           | 1        | 0.86%   |
| SK hynix RAM Module 16GB DIMM DDR3 1866MT/s             | 1        | 0.86%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s     | 1        | 0.86%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 0.86%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 0.86%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 0.86%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 0.86%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 0.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 0.86%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 1        | 0.86%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s          | 1        | 0.86%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.86%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 1        | 0.86%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s | 1        | 0.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 35       | 39.33%  |
| DDR3    | 33       | 37.08%  |
| Unknown | 10       | 11.24%  |
| SDRAM   | 6        | 6.74%   |
| DDR2    | 4        | 4.49%   |
| DDR     | 1        | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 85       | 98.84%  |
| SODIMM | 1        | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 34       | 34.69%  |
| 4096  | 27       | 27.55%  |
| 2048  | 16       | 16.33%  |
| 16384 | 12       | 12.24%  |
| 1024  | 4        | 4.08%   |
| 32768 | 3        | 3.06%   |
| 512   | 1        | 1.02%   |
| 128   | 1        | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 20       | 19.42%  |
| 1333    | 10       | 9.71%   |
| 3200    | 8        | 7.77%   |
| 3600    | 7        | 6.8%    |
| 2400    | 7        | 6.8%    |
| 800     | 6        | 5.83%   |
| 667     | 5        | 4.85%   |
| 2667    | 4        | 3.88%   |
| 2133    | 4        | 3.88%   |
| 3466    | 3        | 2.91%   |
| 1867    | 3        | 2.91%   |
| 1800    | 3        | 2.91%   |
| 3400    | 2        | 1.94%   |
| 3266    | 2        | 1.94%   |
| 1866    | 2        | 1.94%   |
| 1648    | 2        | 1.94%   |
| 1066    | 2        | 1.94%   |
| 533     | 2        | 1.94%   |
| Unknown | 2        | 1.94%   |
| 3800    | 1        | 0.97%   |
| 3733    | 1        | 0.97%   |
| 3000    | 1        | 0.97%   |
| 2933    | 1        | 0.97%   |
| 2733    | 1        | 0.97%   |
| 2666    | 1        | 0.97%   |
| 1639    | 1        | 0.97%   |
| 1067    | 1        | 0.97%   |
| 400     | 1        | 0.97%   |

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
| Logitech                      | 15       | 44.12%  |
| Microsoft                     | 4        | 11.76%  |
| Sunplus Innovation Technology | 2        | 5.88%   |
| Generalplus Technology        | 2        | 5.88%   |
| Creative Technology           | 2        | 5.88%   |
| WaveRider Communications      | 1        | 2.94%   |
| Samsung Electronics           | 1        | 2.94%   |
| Realtek Semiconductor         | 1        | 2.94%   |
| Razer USA                     | 1        | 2.94%   |
| Microdia                      | 1        | 2.94%   |
| GenesysLogic Technology       | 1        | 2.94%   |
| GEMBIRD                       | 1        | 2.94%   |
| Chicony Electronics           | 1        | 2.94%   |
| Apple                         | 1        | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                       | 6        | 17.14%  |
| Microsoft LifeCam HD-3000                         | 3        | 8.57%   |
| Logitech Webcam C925e                             | 2        | 5.71%   |
| Logitech Webcam C270                              | 2        | 5.71%   |
| Creative Live! Cam Sync HD [VF0770]               | 2        | 5.71%   |
| WaveRider USB 2.0 Camera                          | 1        | 2.86%   |
| Sunplus HD 720P webcam                            | 1        | 2.86%   |
| Sunplus Full HD webcam                            | 1        | 2.86%   |
| Samsung Galaxy A5 (MTP)                           | 1        | 2.86%   |
| Realtek FULL HD 1080P Webcam                      | 1        | 2.86%   |
| Razer USA Razer Kiyo                              | 1        | 2.86%   |
| Microsoft LifeCam NX-3000 (UVC-compliant)         | 1        | 2.86%   |
| Microdia CameraA                                  | 1        | 2.86%   |
| Logitech Webcam C310                              | 1        | 2.86%   |
| Logitech Webcam C210                              | 1        | 2.86%   |
| Logitech Webcam C120                              | 1        | 2.86%   |
| Logitech QuickCam Vision Pro                      | 1        | 2.86%   |
| Logitech Logitech Webcam C160                     | 1        | 2.86%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 2.86%   |
| GenesysLogic USB2.0 UVC PC Camera                 | 1        | 2.86%   |
| Generalplus GENERAL WEBCAM                        | 1        | 2.86%   |
| Generalplus 808 Camera                            | 1        | 2.86%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 2.86%   |
| Chicony USB2.0 2MP UVC Camera                     | 1        | 2.86%   |
| Apple iPhone 5/5C/5S/6/SE                         | 1        | 2.86%   |

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
| 0     | 140      | 81.87%  |
| 1     | 28       | 16.37%  |
| 2     | 3        | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 16       | 50%     |
| Graphics card         | 11       | 34.38%  |
| Multimedia controller | 3        | 9.38%   |
| Net/ethernet          | 2        | 6.25%   |

