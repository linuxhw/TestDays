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

Total: 300

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME A520M-K               | [ea4d9240fb](https://linux-hardware.org/?probe=ea4d9240fb) | Aug 05, 2023 |
| HP            | 21D0                        | [44e0cbb52e](https://linux-hardware.org/?probe=44e0cbb52e) | Aug 03, 2023 |
| HP            | 21D0                        | [099fea9193](https://linux-hardware.org/?probe=099fea9193) | Aug 02, 2023 |
| Dell          | 0D28YY A00                  | [08fd0fea6a](https://linux-hardware.org/?probe=08fd0fea6a) | Jul 26, 2023 |
| HP            | 21D0                        | [774375de1f](https://linux-hardware.org/?probe=774375de1f) | Jul 22, 2023 |
| ASUSTek       | M5A78L/USB3                 | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| HP            | 21D0                        | [a6d51a414c](https://linux-hardware.org/?probe=a6d51a414c) | Jul 11, 2023 |
| Dell          | 0M5DCD A00                  | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | [2bb5ca7ea2](https://linux-hardware.org/?probe=2bb5ca7ea2) | Jul 05, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | [b24c1d471d](https://linux-hardware.org/?probe=b24c1d471d) | Jul 04, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| Dell          | 0WR7PY A02                  | [ae5f4be943](https://linux-hardware.org/?probe=ae5f4be943) | Jun 20, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3d29012888](https://linux-hardware.org/?probe=3d29012888) | Jun 04, 2023 |
| HP            | 0AECh D                     | [30868178ea](https://linux-hardware.org/?probe=30868178ea) | May 26, 2023 |
| MSI           | 970 GAMING                  | [2bed616680](https://linux-hardware.org/?probe=2bed616680) | May 23, 2023 |
| MSI           | 970 GAMING                  | [785f4bad86](https://linux-hardware.org/?probe=785f4bad86) | May 23, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [f543ce6c65](https://linux-hardware.org/?probe=f543ce6c65) | Apr 29, 2023 |
| Dell          | 051FJ8 A00                  | [f2b702b631](https://linux-hardware.org/?probe=f2b702b631) | Apr 28, 2023 |
| Dell          | 040DDP A00                  | [8595139862](https://linux-hardware.org/?probe=8595139862) | Apr 25, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| Gigabyte      | Z690 UD DDR4                | [690ed7960a](https://linux-hardware.org/?probe=690ed7960a) | Apr 13, 2023 |
| Dell          | 0J3C2F A00                  | [12f634cf42](https://linux-hardware.org/?probe=12f634cf42) | Apr 11, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e04829aef9](https://linux-hardware.org/?probe=e04829aef9) | Apr 06, 2023 |
| HP            | 21D0                        | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| Gigabyte      | Z68A-D3-B3                  | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| Dell          | 0TP412                      | [f9f3e5cc04](https://linux-hardware.org/?probe=f9f3e5cc04) | Mar 29, 2023 |
| Dell          | 0200DY A02                  | [4f8515b9ed](https://linux-hardware.org/?probe=4f8515b9ed) | Mar 27, 2023 |
| HP            | 0B54h D                     | [3edc678017](https://linux-hardware.org/?probe=3edc678017) | Mar 26, 2023 |
| MSI           | X470 GAMING PRO             | [b49dbdfa77](https://linux-hardware.org/?probe=b49dbdfa77) | Mar 25, 2023 |
| HP            | 83E9                        | [a93c800fa1](https://linux-hardware.org/?probe=a93c800fa1) | Mar 19, 2023 |
| Dell          | 0JP3NX A00                  | [9d0ac027df](https://linux-hardware.org/?probe=9d0ac027df) | Mar 14, 2023 |
| ASRock        | X99 Extreme4                | [a541fe5881](https://linux-hardware.org/?probe=a541fe5881) | Mar 07, 2023 |
| Dell          | 0JC474                      | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
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


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 29       | 13.68%  |
| Ubuntu 18.04                 | 12       | 5.66%   |
| Debian 11                    | 9        | 4.25%   |
| ArcoLinux Rolling            | 7        | 3.3%    |
| OpenMandriva 4.2             | 6        | 2.83%   |
| Manjaro                      | 6        | 2.83%   |
| Arch Rolling                 | 6        | 2.83%   |
| Ubuntu 19.04                 | 5        | 2.36%   |
| Pop!_OS 22.04                | 5        | 2.36%   |
| Linux Mint 20.2              | 5        | 2.36%   |
| Linux Mint 20                | 5        | 2.36%   |
| Arch                         | 5        | 2.36%   |
| ROSA R11                     | 4        | 1.89%   |
| Pop!_OS 21.10                | 4        | 1.89%   |
| Pop!_OS 20.10                | 4        | 1.89%   |
| OpenMandriva 4.3             | 4        | 1.89%   |
| Ubuntu 22.04                 | 3        | 1.42%   |
| Linux Mint 20.1              | 3        | 1.42%   |
| Fedora 38                    | 3        | 1.42%   |
| Fedora 35                    | 3        | 1.42%   |
| Fedora 32                    | 3        | 1.42%   |
| BlackPanther 18.1            | 3        | 1.42%   |
| Zorin 16                     | 2        | 0.94%   |
| SteamOS 3.4                  | 2        | 0.94%   |
| ROSA R10                     | 2        | 0.94%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 0.94%   |
| OpenMandriva 4.50            | 2        | 0.94%   |
| OpenMandriva 23.03           | 2        | 0.94%   |
| OpenMandriva 23.01           | 2        | 0.94%   |
| Linux Mint 20.3              | 2        | 0.94%   |
| Linux Mint 19                | 2        | 0.94%   |
| Linux Mint 18.3              | 2        | 0.94%   |
| KDE neon 20.04               | 2        | 0.94%   |
| Fedora 37                    | 2        | 0.94%   |
| Fedora 36                    | 2        | 0.94%   |
| Fedora 33                    | 2        | 0.94%   |
| Endless 3.7.8                | 2        | 0.94%   |
| Debian 12                    | 2        | 0.94%   |
| Debian 10                    | 2        | 0.94%   |
| Zorin 15                     | 1        | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 52       | 26.67%  |
| Linux Mint   | 20       | 10.26%  |
| OpenMandriva | 14       | 7.18%   |
| Pop!_OS      | 13       | 6.67%   |
| Fedora       | 13       | 6.67%   |
| Debian       | 12       | 6.15%   |
| Arch         | 11       | 5.64%   |
| Manjaro      | 10       | 5.13%   |
| ArcoLinux    | 7        | 3.59%   |
| ROSA         | 6        | 3.08%   |
| KDE neon     | 4        | 2.05%   |
| Zorin        | 3        | 1.54%   |
| SteamOS      | 3        | 1.54%   |
| BlackPanther | 3        | 1.54%   |
| Xubuntu      | 2        | 1.03%   |
| openSUSE     | 2        | 1.03%   |
| Lubuntu      | 2        | 1.03%   |
| Kubuntu      | 2        | 1.03%   |
| Kali         | 2        | 1.03%   |
| Gentoo       | 2        | 1.03%   |
| Endless      | 2        | 1.03%   |
| Elementary   | 2        | 1.03%   |
| Solus        | 1        | 0.51%   |
| Peppermint   | 1        | 0.51%   |
| NixOS        | 1        | 0.51%   |
| MX           | 1        | 0.51%   |
| Linux Lite   | 1        | 0.51%   |
| Garuda Linux | 1        | 0.51%   |
| Feren OS     | 1        | 0.51%   |
| Clear Linux  | 1        | 0.51%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.4.0-42-generic                 | 7        | 2.86%   |
| 5.10.14-desktop-1omv4002         | 6        | 2.45%   |
| 5.4.0-48-generic                 | 4        | 1.63%   |
| 5.16.7-desktop-1omv4003          | 4        | 1.63%   |
| 5.8.0-7630-generic               | 3        | 1.22%   |
| 5.4.0-91-generic                 | 3        | 1.22%   |
| 5.4.0-47-generic                 | 3        | 1.22%   |
| 5.3.0-28-generic                 | 3        | 1.22%   |
| 5.17.5-arch1-1                   | 3        | 1.22%   |
| 5.15.11-76051511-generic         | 3        | 1.22%   |
| 5.10.0-23-amd64                  | 3        | 1.22%   |
| 4.18.16-desktop-1bP              | 3        | 1.22%   |
| 6.2.6-desktop-1omv2390           | 2        | 0.82%   |
| 5.8.14-arch1-1                   | 2        | 0.82%   |
| 5.8.0-43-generic                 | 2        | 0.82%   |
| 5.8.0-41-generic                 | 2        | 0.82%   |
| 5.4.0-88-generic                 | 2        | 0.82%   |
| 5.4.0-77-generic                 | 2        | 0.82%   |
| 5.4.0-72-generic                 | 2        | 0.82%   |
| 5.4.0-37-generic                 | 2        | 0.82%   |
| 5.3.0-45-generic                 | 2        | 0.82%   |
| 5.19.0-35-generic                | 2        | 0.82%   |
| 5.17.5-76051705-generic          | 2        | 0.82%   |
| 5.16.15-76051615-generic         | 2        | 0.82%   |
| 5.15.0-56-generic                | 2        | 0.82%   |
| 5.15.0-46-generic                | 2        | 0.82%   |
| 5.13.13-arch1-1                  | 2        | 0.82%   |
| 5.13.0-39-generic                | 2        | 0.82%   |
| 5.12.4-desktop-1omv4050          | 2        | 0.82%   |
| 5.11.0-43-generic                | 2        | 0.82%   |
| 5.0.0-23-generic                 | 2        | 0.82%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 2        | 0.82%   |
| 4.9.60-nrj-desktop-1rosa-i586    | 2        | 0.82%   |
| 4.9.155-nrj-desktop-1rosa-x86_64 | 2        | 0.82%   |
| 4.18.0-25-generic                | 2        | 0.82%   |
| 4.15.0-desktop-45.1rosa-x86_64   | 2        | 0.82%   |
| 4.10.0-38-generic                | 2        | 0.82%   |
| 6.4.6-1-default                  | 1        | 0.41%   |
| 6.4.2-zen1-1-zen                 | 1        | 0.41%   |
| 6.3.8-zen1-1-zen                 | 1        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 37       | 15.95%  |
| 5.8.0   | 10       | 4.31%   |
| 5.15.0  | 10       | 4.31%   |
| 4.15.0  | 10       | 4.31%   |
| 5.3.0   | 8        | 3.45%   |
| 5.19.0  | 8        | 3.45%   |
| 5.10.0  | 8        | 3.45%   |
| 5.13.0  | 7        | 3.02%   |
| 5.11.0  | 7        | 3.02%   |
| 5.0.0   | 7        | 3.02%   |
| 5.17.5  | 6        | 2.59%   |
| 5.10.14 | 6        | 2.59%   |
| 4.18.0  | 5        | 2.16%   |
| 5.16.7  | 4        | 1.72%   |
| 5.15.11 | 3        | 1.29%   |
| 4.18.16 | 3        | 1.29%   |
| 6.3.8   | 2        | 0.86%   |
| 6.2.8   | 2        | 0.86%   |
| 6.2.6   | 2        | 0.86%   |
| 6.2.11  | 2        | 0.86%   |
| 6.1.0   | 2        | 0.86%   |
| 6.0.6   | 2        | 0.86%   |
| 5.8.14  | 2        | 0.86%   |
| 5.18.10 | 2        | 0.86%   |
| 5.17.6  | 2        | 0.86%   |
| 5.16.15 | 2        | 0.86%   |
| 5.16.11 | 2        | 0.86%   |
| 5.15.6  | 2        | 0.86%   |
| 5.15.12 | 2        | 0.86%   |
| 5.13.13 | 2        | 0.86%   |
| 5.12.4  | 2        | 0.86%   |
| 5.11.11 | 2        | 0.86%   |
| 5.11.10 | 2        | 0.86%   |
| 4.9.60  | 2        | 0.86%   |
| 4.9.155 | 2        | 0.86%   |
| 4.19.0  | 2        | 0.86%   |
| 4.10.0  | 2        | 0.86%   |
| 6.4.6   | 1        | 0.43%   |
| 6.4.2   | 1        | 0.43%   |
| 6.3.5   | 1        | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 38       | 16.89%  |
| 5.15    | 21       | 9.33%   |
| 5.10    | 18       | 8%      |
| 5.8     | 15       | 6.67%   |
| 5.11    | 13       | 5.78%   |
| 5.16    | 10       | 4.44%   |
| 5.13    | 10       | 4.44%   |
| 4.15    | 10       | 4.44%   |
| 5.19    | 9        | 4%      |
| 5.17    | 9        | 4%      |
| 6.2     | 8        | 3.56%   |
| 5.3     | 8        | 3.56%   |
| 4.18    | 8        | 3.56%   |
| 5.0     | 7        | 3.11%   |
| 6.1     | 5        | 2.22%   |
| 6.0     | 5        | 2.22%   |
| 5.12    | 5        | 2.22%   |
| 6.3     | 3        | 1.33%   |
| 5.7     | 3        | 1.33%   |
| 5.6     | 3        | 1.33%   |
| 5.18    | 3        | 1.33%   |
| 4.9     | 3        | 1.33%   |
| 6.4     | 2        | 0.89%   |
| 4.19    | 2        | 0.89%   |
| 4.10    | 2        | 0.89%   |
| 5.9     | 1        | 0.44%   |
| 5.5     | 1        | 0.44%   |
| 5.14    | 1        | 0.44%   |
| 4.4     | 1        | 0.44%   |
| 4.1     | 1        | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 185      | 98.4%   |
| i686   | 3        | 1.6%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 72       | 36%     |
| KDE5            | 45       | 22.5%   |
| Unknown         | 26       | 13%     |
| XFCE            | 21       | 10.5%   |
| X-Cinnamon      | 10       | 5%      |
| MATE            | 7        | 3.5%    |
| KDE             | 6        | 3%      |
| KDE4            | 4        | 2%      |
| LXQt            | 3        | 1.5%    |
| Pantheon        | 2        | 1%      |
| LXDE            | 1        | 0.5%    |
| LeftWM          | 1        | 0.5%    |
| GNOME Flashback | 1        | 0.5%    |
| Cinnamon        | 1        | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 153      | 80.1%   |
| Wayland | 17       | 8.9%    |
| Unknown | 17       | 8.9%    |
| Tty     | 4        | 2.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 101      | 50.75%  |
| SDDM    | 43       | 21.61%  |
| GDM     | 19       | 9.55%   |
| LightDM | 15       | 7.54%   |
| GDM3    | 10       | 5.03%   |
| TDM     | 5        | 2.51%   |
| KDM     | 4        | 2.01%   |
| MDM     | 1        | 0.5%    |
| LXDM    | 1        | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_IE   | 91       | 45.96%  |
| en_GB   | 36       | 18.18%  |
| en_US   | 33       | 16.67%  |
| Unknown | 27       | 13.64%  |
| C       | 3        | 1.52%   |
| pl_PL   | 2        | 1.01%   |
| es_ES   | 2        | 1.01%   |
| pt_BR   | 1        | 0.51%   |
| hu_HU   | 1        | 0.51%   |
| en_BW   | 1        | 0.51%   |
| de_DE   | 1        | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 121      | 63.02%  |
| EFI  | 71       | 36.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 147      | 76.17%  |
| Btrfs   | 18       | 9.33%   |
| Overlay | 16       | 8.29%   |
| Unknown | 7        | 3.63%   |
| Zfs     | 2        | 1.04%   |
| Tmpfs   | 2        | 1.04%   |
| Xfs     | 1        | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 98       | 49.25%  |
| GPT     | 77       | 38.69%  |
| MBR     | 24       | 12.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 148      | 77.08%  |
| Yes       | 44       | 22.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 67.01%  |
| Yes       | 64       | 32.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 40       | 21.51%  |
| Dell                                 | 39       | 20.97%  |
| Gigabyte Technology                  | 28       | 15.05%  |
| MSI                                  | 17       | 9.14%   |
| Hewlett-Packard                      | 16       | 8.6%    |
| ASRock                               | 13       | 6.99%   |
| Lenovo                               | 11       | 5.91%   |
| Foxconn                              | 5        | 2.69%   |
| Intel                                | 3        | 1.61%   |
| Shuttle                              | 2        | 1.08%   |
| Seco                                 | 2        | 1.08%   |
| Apple                                | 2        | 1.08%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.54%   |
| Pegatron                             | 1        | 0.54%   |
| Packard Bell                         | 1        | 0.54%   |
| MiTAC                                | 1        | 0.54%   |
| Medion                               | 1        | 0.54%   |
| DFI                                  | 1        | 0.54%   |
| ABIT                                 | 1        | 0.54%   |
| Unknown                              | 1        | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex 7010                         | 8        | 4.3%    |
| ASUS All Series                            | 7        | 3.76%   |
| Gigabyte B450M DS3H                        | 4        | 2.15%   |
| Dell OptiPlex 790                          | 4        | 2.15%   |
| HP Compaq 8200 Elite SFF PC                | 3        | 1.61%   |
| Dell OptiPlex 780                          | 3        | 1.61%   |
| Dell OptiPlex 7020                         | 3        | 1.61%   |
| ASUS ROG STRIX B450-F GAMING               | 3        | 1.61%   |
| Seco C40                                   | 2        | 1.08%   |
| MSI MS-7C37                                | 2        | 1.08%   |
| MSI MS-7B79                                | 2        | 1.08%   |
| Lenovo ThinkStation D20 415892G            | 2        | 1.08%   |
| HP EliteDesk 800 G1 SFF                    | 2        | 1.08%   |
| Gigabyte X570 AORUS ULTRA                  | 2        | 1.08%   |
| Gigabyte A320M-S2H                         | 2        | 1.08%   |
| Foxconn Pro 3500 Series                    | 2        | 1.08%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 1.08%   |
| ASUS P8P67 PRO                             | 2        | 1.08%   |
| ASUS M5A78L/USB3                           | 2        | 1.08%   |
| Shuttle XS35V4                             | 1        | 0.54%   |
| Shuttle XS35V3                             | 1        | 0.54%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.54%   |
| Pegatron Pro 3010 Microtower PC            | 1        | 0.54%   |
| Packard Bell Vegas2                        | 1        | 0.54%   |
| MSI Pro 3515 Series                        | 1        | 0.54%   |
| MSI MS-7C84                                | 1        | 0.54%   |
| MSI MS-7C77                                | 1        | 0.54%   |
| MSI MS-7C02                                | 1        | 0.54%   |
| MSI MS-7B92                                | 1        | 0.54%   |
| MSI MS-7B89                                | 1        | 0.54%   |
| MSI MS-7B86                                | 1        | 0.54%   |
| MSI MS-7972                                | 1        | 0.54%   |
| MSI MS-7751                                | 1        | 0.54%   |
| MSI MS-7693                                | 1        | 0.54%   |
| MSI MS-7636                                | 1        | 0.54%   |
| MSI MS-7270                                | 1        | 0.54%   |
| MSI ER883AA-ABA M7470N                     | 1        | 0.54%   |
| MiTAC PD14TI AAPD14TI-101                  | 1        | 0.54%   |
| Medion MS-7646                             | 1        | 0.54%   |
| Lenovo V530S-07ICB 10TX002GUK              | 1        | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 26       | 13.98%  |
| Lenovo ThinkCentre                         | 8        | 4.3%    |
| ASUS PRIME                                 | 8        | 4.3%    |
| ASUS All                                   | 7        | 3.76%   |
| HP Compaq                                  | 6        | 3.23%   |
| ASUS TUF                                   | 6        | 3.23%   |
| HP EliteDesk                               | 4        | 2.15%   |
| Gigabyte B450M                             | 4        | 2.15%   |
| Dell Precision                             | 4        | 2.15%   |
| Foxconn Pro                                | 3        | 1.61%   |
| ASUS ROG                                   | 3        | 1.61%   |
| Seco C40                                   | 2        | 1.08%   |
| MSI MS-7C37                                | 2        | 1.08%   |
| MSI MS-7B79                                | 2        | 1.08%   |
| Lenovo ThinkStation                        | 2        | 1.08%   |
| Intel DESKTOP                              | 2        | 1.08%   |
| Gigabyte X570                              | 2        | 1.08%   |
| Gigabyte TRX40                             | 2        | 1.08%   |
| Gigabyte B450                              | 2        | 1.08%   |
| Gigabyte A320M-S2H                         | 2        | 1.08%   |
| Dell Vostro                                | 2        | 1.08%   |
| Dell Inspiron                              | 2        | 1.08%   |
| ASUS P8P67                                 | 2        | 1.08%   |
| ASUS Maximus                               | 2        | 1.08%   |
| ASUS M5A78L                                | 2        | 1.08%   |
| ASUS Crosshair                             | 2        | 1.08%   |
| ASRock Z77                                 | 2        | 1.08%   |
| Shuttle XS35V4                             | 1        | 0.54%   |
| Shuttle XS35V3                             | 1        | 0.54%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.54%   |
| Pegatron Pro                               | 1        | 0.54%   |
| Packard Bell Vegas2                        | 1        | 0.54%   |
| MSI Pro                                    | 1        | 0.54%   |
| MSI MS-7C84                                | 1        | 0.54%   |
| MSI MS-7C77                                | 1        | 0.54%   |
| MSI MS-7C02                                | 1        | 0.54%   |
| MSI MS-7B92                                | 1        | 0.54%   |
| MSI MS-7B89                                | 1        | 0.54%   |
| MSI MS-7B86                                | 1        | 0.54%   |
| MSI MS-7972                                | 1        | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 24       | 12.9%   |
| 2013 | 24       | 12.9%   |
| 2011 | 21       | 11.29%  |
| 2012 | 20       | 10.75%  |
| 2019 | 15       | 8.06%   |
| 2010 | 15       | 8.06%   |
| 2020 | 11       | 5.91%   |
| 2008 | 11       | 5.91%   |
| 2014 | 10       | 5.38%   |
| 2017 | 9        | 4.84%   |
| 2015 | 7        | 3.76%   |
| 2009 | 4        | 2.15%   |
| 2006 | 4        | 2.15%   |
| 2022 | 3        | 1.61%   |
| 2007 | 3        | 1.61%   |
| 2021 | 2        | 1.08%   |
| 2005 | 2        | 1.08%   |
| 2016 | 1        | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 186      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 181      | 97.31%  |
| Enabled  | 5        | 2.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 186      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 48       | 25%     |
| 8.01-16.0       | 46       | 23.96%  |
| 32.01-64.0      | 28       | 14.58%  |
| 3.01-4.0        | 27       | 14.06%  |
| 4.01-8.0        | 23       | 11.98%  |
| 64.01-256.0     | 10       | 5.21%   |
| 24.01-32.0      | 5        | 2.6%    |
| 1.01-2.0        | 3        | 1.56%   |
| More than 256.0 | 1        | 0.52%   |
| 0.51-1.0        | 1        | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 84       | 38.89%  |
| 2.01-3.0   | 48       | 22.22%  |
| 4.01-8.0   | 30       | 13.89%  |
| 3.01-4.0   | 23       | 10.65%  |
| 0.51-1.0   | 15       | 6.94%   |
| 8.01-16.0  | 14       | 6.48%   |
| 32.01-64.0 | 1        | 0.46%   |
| 0.01-0.5   | 1        | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 73       | 35.44%  |
| 2      | 47       | 22.82%  |
| 3      | 29       | 14.08%  |
| 4      | 26       | 12.62%  |
| 5      | 14       | 6.8%    |
| 7      | 6        | 2.91%   |
| 6      | 4        | 1.94%   |
| 10     | 2        | 0.97%   |
| 0      | 2        | 0.97%   |
| 11     | 1        | 0.49%   |
| 9      | 1        | 0.49%   |
| 8      | 1        | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 100      | 52.08%  |
| No        | 92       | 47.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 184      | 98.92%  |
| No        | 2        | 1.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 105      | 54.69%  |
| No        | 87       | 45.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 63.21%  |
| Yes       | 71       | 36.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ireland | 186      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Dublin       | 107      | 54.04%  |
| Cork         | 11       | 5.56%   |
| Limerick     | 6        | 3.03%   |
| Gorey        | 4        | 2.02%   |
| Tuam         | 3        | 1.52%   |
| Sligo        | 3        | 1.52%   |
| Portlaoise   | 3        | 1.52%   |
| Naas         | 3        | 1.52%   |
| Kenmare      | 3        | 1.52%   |
| Athlone      | 3        | 1.52%   |
| Wexford      | 2        | 1.01%   |
| Swords       | 2        | 1.01%   |
| Oranmore     | 2        | 1.01%   |
| Nenagh       | 2        | 1.01%   |
| Kildare      | 2        | 1.01%   |
| Ennis        | 2        | 1.01%   |
| Cavan        | 2        | 1.01%   |
| Ballincollig | 2        | 1.01%   |
| Waterford    | 1        | 0.51%   |
| Tullamore    | 1        | 0.51%   |
| Tralee       | 1        | 0.51%   |
| Tobercurry   | 1        | 0.51%   |
| Tipperary    | 1        | 0.51%   |
| Summerhill   | 1        | 0.51%   |
| Shanagolden  | 1        | 0.51%   |
| Navan        | 1        | 0.51%   |
| Moyne        | 1        | 0.51%   |
| Maynooth     | 1        | 0.51%   |
| Mallow       | 1        | 0.51%   |
| Lucan        | 1        | 0.51%   |
| Loughrea     | 1        | 0.51%   |
| Listowel     | 1        | 0.51%   |
| Letterkenny  | 1        | 0.51%   |
| Killorglin   | 1        | 0.51%   |
| Killarney    | 1        | 0.51%   |
| Kilkenny     | 1        | 0.51%   |
| Kilcoole     | 1        | 0.51%   |
| Galway       | 1        | 0.51%   |
| Enniscorthy  | 1        | 0.51%   |
| Edenderry    | 1        | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 78       | 166    | 21.25%  |
| Seagate                     | 67       | 130    | 18.26%  |
| Samsung Electronics         | 48       | 85     | 13.08%  |
| Crucial                     | 25       | 30     | 6.81%   |
| Toshiba                     | 20       | 32     | 5.45%   |
| SanDisk                     | 16       | 27     | 4.36%   |
| Hitachi                     | 15       | 25     | 4.09%   |
| Kingston                    | 13       | 24     | 3.54%   |
| A-DATA Technology           | 8        | 13     | 2.18%   |
| Phison                      | 6        | 11     | 1.63%   |
| China                       | 5        | 5      | 1.36%   |
| Verbatim                    | 4        | 4      | 1.09%   |
| Intel                       | 4        | 4      | 1.09%   |
| OCZ                         | 3        | 3      | 0.82%   |
| Micron/Crucial Technology   | 3        | 6      | 0.82%   |
| Micron Technology           | 3        | 3      | 0.82%   |
| HGST                        | 3        | 3      | 0.82%   |
| Transcend                   | 2        | 2      | 0.54%   |
| Team                        | 2        | 2      | 0.54%   |
| Silicon Motion              | 2        | 8      | 0.54%   |
| Netac                       | 2        | 2      | 0.54%   |
| Maxtor                      | 2        | 2      | 0.54%   |
| LITEON                      | 2        | 2      | 0.54%   |
| Kingston Technology Company | 2        | 2      | 0.54%   |
| Western Digital             | 1        | 2      | 0.27%   |
| WDS100T1                    | 1        | 1      | 0.27%   |
| USB3.0                      | 1        | 1      | 0.27%   |
| Unknown                     | 1        | 1      | 0.27%   |
| Union Memory (Shenzhen)     | 1        | 1      | 0.27%   |
| Union Memory                | 1        | 1      | 0.27%   |
| SABRENT                     | 1        | 1      | 0.27%   |
| QNAP                        | 1        | 11     | 0.27%   |
| PNY                         | 1        | 1      | 0.27%   |
| Patriot                     | 1        | 1      | 0.27%   |
| Palit                       | 1        | 1      | 0.27%   |
| MaxDigital                  | 1        | 1      | 0.27%   |
| KIOXIA                      | 1        | 2      | 0.27%   |
| KingSpec                    | 1        | 1      | 0.27%   |
| KingDian                    | 1        | 1      | 0.27%   |
| KESU                        | 1        | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB   | 7        | 1.56%   |
| Seagate ST8000DM004-2CX188 8TB   | 6        | 1.34%   |
| WDC WD10EURX-83UY4Y0 1TB         | 5        | 1.12%   |
| Seagate ST500DM002-1BD142 500GB  | 5        | 1.12%   |
| Crucial CT500MX500SSD1 500GB     | 5        | 1.12%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 0.89%   |
| Verbatim Vi550 S3 SSD 1TB        | 4        | 0.89%   |
| Seagate ST3500312CS 500GB        | 4        | 0.89%   |
| Seagate ST2000DL003-9VT166 2TB   | 4        | 0.89%   |
| Samsung SSD 850 EVO 500GB        | 4        | 0.89%   |
| Kingston SA400S37240G 240GB SSD  | 4        | 0.89%   |
| Crucial CT1000MX500SSD1 1TB      | 4        | 0.89%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 3        | 0.67%   |
| WDC WD3200AAJS-60Z0A0 320GB      | 3        | 0.67%   |
| WDC WD20EZRX-00D8PB0 2TB         | 3        | 0.67%   |
| WDC WD10EALX-009BA0 1TB          | 3        | 0.67%   |
| Toshiba DT01ACA100 1TB           | 3        | 0.67%   |
| Seagate ST3500418AS 500GB        | 3        | 0.67%   |
| Seagate ST31000528AS 1TB         | 3        | 0.67%   |
| Seagate ST2000DM006-2DM164 2TB   | 3        | 0.67%   |
| Seagate Expansion Desk 8TB       | 3        | 0.67%   |
| SanDisk NVMe SSD Drive 500GB     | 3        | 0.67%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.67%   |
| Samsung SSD 860 EVO 500GB        | 3        | 0.67%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.67%   |
| Phison Sabrent 1TB               | 3        | 0.67%   |
| Kingston SV300S37A120G 120GB SSD | 3        | 0.67%   |
| Hitachi HDS721616PLA380 160GB    | 3        | 0.67%   |
| Hitachi HDS721032CLA362 320GB    | 3        | 0.67%   |
| A-DATA SU650 240GB SSD           | 3        | 0.67%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.45%   |
| WDC WD5000BPKT-60PK4T0 500GB     | 2        | 0.45%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 0.45%   |
| WDC WD40EZRZ-19GXCB0 4TB         | 2        | 0.45%   |
| WDC WD40EFRX-68WT0N0 4TB         | 2        | 0.45%   |
| WDC WD2500AAKX-753CA1 250GB      | 2        | 0.45%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.45%   |
| WDC WD20EARS-00MVWB0 2TB         | 2        | 0.45%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.45%   |
| Toshiba MQ01ABD100 1TB           | 2        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 70       | 154    | 36.84%  |
| Seagate             | 66       | 128    | 34.74%  |
| Toshiba             | 17       | 28     | 8.95%   |
| Hitachi             | 15       | 25     | 7.89%   |
| Samsung Electronics | 8        | 10     | 4.21%   |
| HGST                | 3        | 3      | 1.58%   |
| Maxtor              | 2        | 2      | 1.05%   |
| USB3.0              | 1        | 1      | 0.53%   |
| Unknown             | 1        | 1      | 0.53%   |
| QNAP                | 1        | 11     | 0.53%   |
| KESU                | 1        | 1      | 0.53%   |
| Inateck             | 1        | 1      | 0.53%   |
| Fujitsu             | 1        | 2      | 0.53%   |
| FNK TECH            | 1        | 1      | 0.53%   |
| ExcelStor           | 1        | 2      | 0.53%   |
| ASMT                | 1        | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 30       | 50     | 24%     |
| Crucial             | 23       | 28     | 18.4%   |
| Kingston            | 12       | 22     | 9.6%    |
| SanDisk             | 11       | 15     | 8.8%    |
| A-DATA Technology   | 6        | 10     | 4.8%    |
| WDC                 | 5        | 8      | 4%      |
| China               | 5        | 5      | 4%      |
| Verbatim            | 4        | 4      | 3.2%    |
| Intel               | 4        | 4      | 3.2%    |
| OCZ                 | 3        | 3      | 2.4%    |
| Transcend           | 2        | 2      | 1.6%    |
| Team                | 2        | 2      | 1.6%    |
| Netac               | 2        | 2      | 1.6%    |
| LITEON              | 2        | 2      | 1.6%    |
| Toshiba             | 1        | 1      | 0.8%    |
| PNY                 | 1        | 1      | 0.8%    |
| Patriot             | 1        | 1      | 0.8%    |
| Palit               | 1        | 1      | 0.8%    |
| Micron Technology   | 1        | 1      | 0.8%    |
| KingSpec            | 1        | 1      | 0.8%    |
| KingDian            | 1        | 1      | 0.8%    |
| Integral            | 1        | 1      | 0.8%    |
| Hikvision           | 1        | 1      | 0.8%    |
| Hewlett-Packard     | 1        | 2      | 0.8%    |
| DRVEO               | 1        | 1      | 0.8%    |
| Corsair             | 1        | 2      | 0.8%    |
| Apple               | 1        | 1      | 0.8%    |
| Unknown             | 1        | 1      | 0.8%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 133      | 371    | 45.08%  |
| SSD     | 107      | 173    | 36.27%  |
| NVMe    | 48       | 88     | 16.27%  |
| Unknown | 7        | 7      | 2.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 174      | 528    | 72.2%   |
| NVMe | 47       | 87     | 19.5%   |
| SAS  | 20       | 24     | 8.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 130      | 277    | 46.76%  |
| 0.51-1.0   | 81       | 142    | 29.14%  |
| 1.01-2.0   | 29       | 44     | 10.43%  |
| 3.01-4.0   | 14       | 30     | 5.04%   |
| 4.01-10.0  | 12       | 34     | 4.32%   |
| 2.01-3.0   | 10       | 14     | 3.6%    |
| 10.01-20.0 | 2        | 3      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 41       | 19.52%  |
| 251-500        | 36       | 17.14%  |
| More than 3000 | 29       | 13.81%  |
| 501-1000       | 29       | 13.81%  |
| 1001-2000      | 21       | 10%     |
| 51-100         | 16       | 7.62%   |
| 2001-3000      | 11       | 5.24%   |
| 1-20           | 11       | 5.24%   |
| Unknown        | 10       | 4.76%   |
| 21-50          | 6        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 70       | 32.11%  |
| 101-250        | 26       | 11.93%  |
| 501-1000       | 26       | 11.93%  |
| 51-100         | 24       | 11.01%  |
| 21-50          | 22       | 10.09%  |
| More than 3000 | 14       | 6.42%   |
| 251-500        | 10       | 4.59%   |
| Unknown        | 10       | 4.59%   |
| 2001-3000      | 9        | 4.13%   |
| 1001-2000      | 7        | 3.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                  | 3        | 8      | 6.82%   |
| Seagate ST2000DL003-9VT166 2TB           | 3        | 5      | 6.82%   |
| WDC WD2500AAKX-753CA1 250GB              | 2        | 4      | 4.55%   |
| Western Digital SN730 500GB              | 1        | 2      | 2.27%   |
| WDC WD7500BPKX-00HPJT0 752GB             | 1        | 1      | 2.27%   |
| WDC WD5000HHTZ-04N21V0 500GB             | 1        | 2      | 2.27%   |
| WDC WD5000BEVT-35A0RT0 500GB             | 1        | 1      | 2.27%   |
| WDC WD5000AAKX-001CA0 500GB              | 1        | 2      | 2.27%   |
| WDC WD400JB-00FMA0 40GB                  | 1        | 2      | 2.27%   |
| WDC WD3200AVJS-63B6A0 320GB              | 1        | 1      | 2.27%   |
| WDC WD2500BEKT-75A25T0 250GB             | 1        | 1      | 2.27%   |
| WDC WD2500AAKX-603CA0 250GB              | 1        | 1      | 2.27%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1        | 2      | 2.27%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1        | 1      | 2.27%   |
| WDC WD1001FALS-00E8B0 1TB                | 1        | 2      | 2.27%   |
| Toshiba MK1059GSM 1TB                    | 1        | 1      | 2.27%   |
| Toshiba DT01ACA050 500GB                 | 1        | 3      | 2.27%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1        | 1      | 2.27%   |
| Seagate ST4000DX001-1CE168 4TB           | 1        | 1      | 2.27%   |
| Seagate ST3500418AS 500GB                | 1        | 3      | 2.27%   |
| Seagate ST31500541AS 1TB                 | 1        | 1      | 2.27%   |
| Seagate ST3120026A 120GB                 | 1        | 1      | 2.27%   |
| Seagate ST31000333AS 1TB                 | 1        | 2      | 2.27%   |
| Seagate ST3000DM001-1ER166 3TB           | 1        | 1      | 2.27%   |
| SanDisk SSD PLUS 480GB                   | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 970 EVO Plus 2TB | 1        | 1      | 2.27%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 2.27%   |
| Netac SSD 128GB                          | 1        | 1      | 2.27%   |
| Micron Technology 2300 NVMe 512GB        | 1        | 1      | 2.27%   |
| Maxtor STM3250310AS 250GB                | 1        | 1      | 2.27%   |
| Intel SSDSA2M080G2GC 80GB                | 1        | 1      | 2.27%   |
| Inateck ASM1153E 2TB                     | 1        | 1      | 2.27%   |
| Hitachi HUS724030ALA640 3TB              | 1        | 2      | 2.27%   |
| Hitachi HDT721016SLA380 160GB            | 1        | 2      | 2.27%   |
| Hitachi HDS721010CLA332 1TB              | 1        | 1      | 2.27%   |
| HGST HTS541010A7E630 1TB                 | 1        | 1      | 2.27%   |
| DRVEO X1 SSD 480GB                       | 1        | 1      | 2.27%   |
| China T480 480GB SSD                     | 1        | 1      | 2.27%   |
| A-DATA Technology SU800 128GB SSD        | 1        | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 28     | 31.71%  |
| Seagate             | 10       | 15     | 24.39%  |
| Hitachi             | 3        | 5      | 7.32%   |
| Toshiba             | 2        | 4      | 4.88%   |
| Samsung Electronics | 2        | 2      | 4.88%   |
| Western Digital     | 1        | 2      | 2.44%   |
| SanDisk             | 1        | 1      | 2.44%   |
| Netac               | 1        | 1      | 2.44%   |
| Micron Technology   | 1        | 1      | 2.44%   |
| Maxtor              | 1        | 1      | 2.44%   |
| Intel               | 1        | 1      | 2.44%   |
| Inateck             | 1        | 1      | 2.44%   |
| HGST                | 1        | 1      | 2.44%   |
| DRVEO               | 1        | 1      | 2.44%   |
| China               | 1        | 1      | 2.44%   |
| A-DATA Technology   | 1        | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 28     | 40.63%  |
| Seagate             | 10       | 15     | 31.25%  |
| Hitachi             | 3        | 5      | 9.38%   |
| Toshiba             | 2        | 4      | 6.25%   |
| Samsung Electronics | 1        | 1      | 3.13%   |
| Maxtor              | 1        | 1      | 3.13%   |
| Inateck             | 1        | 1      | 3.13%   |
| HGST                | 1        | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 56     | 73.53%  |
| SSD  | 6        | 6      | 17.65%  |
| NVMe | 3        | 4      | 8.82%   |

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
| Detected | 111      | 325    | 49.12%  |
| Works    | 82       | 248    | 36.28%  |
| Malfunc  | 33       | 66     | 14.6%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 115      | 43.4%   |
| AMD                          | 61       | 23.02%  |
| Samsung Electronics          | 17       | 6.42%   |
| SanDisk                      | 10       | 3.77%   |
| ASMedia Technology           | 10       | 3.77%   |
| Marvell Technology Group     | 9        | 3.4%    |
| Phison Electronics           | 6        | 2.26%   |
| Nvidia                       | 5        | 1.89%   |
| Micron/Crucial Technology    | 5        | 1.89%   |
| JMicron Technology           | 5        | 1.89%   |
| LSI Logic / Symbios Logic    | 4        | 1.51%   |
| Toshiba America Info Systems | 3        | 1.13%   |
| Kingston Technology Company  | 3        | 1.13%   |
| Union Memory (Shenzhen)      | 2        | 0.75%   |
| Silicon Motion               | 2        | 0.75%   |
| Realtek Semiconductor        | 2        | 0.75%   |
| Micron Technology            | 2        | 0.75%   |
| ULi Electronics              | 1        | 0.38%   |
| Seagate Technology           | 1        | 0.38%   |
| KIOXIA                       | 1        | 0.38%   |
| Broadcom / LSI               | 1        | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 42       | 12.24%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17       | 4.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 16       | 4.66%   |
| AMD 400 Series Chipset SATA Controller                                                  | 16       | 4.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 3.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11       | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11       | 3.21%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.33%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 2.04%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 1.75%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 6        | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.75%   |
| AMD FCH SATA Controller D                                                               | 5        | 1.46%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4        | 1.17%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 1.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.17%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 1.17%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.87%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 0.87%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.87%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 0.87%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                                   | 2        | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 0.58%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.58%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.58%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.58%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                               | 2        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 152      | 58.24%  |
| IDE  | 49       | 18.77%  |
| NVMe | 47       | 18.01%  |
| RAID | 10       | 3.83%   |
| SCSI | 3        | 1.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 119      | 63.98%  |
| AMD    | 67       | 36.02%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 7        | 3.68%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 6        | 3.16%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 6        | 3.16%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 4        | 2.11%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 4        | 2.11%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 4        | 2.11%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 4        | 2.11%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 4        | 2.11%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 4        | 2.11%   |
| Intel Core i3-4150 CPU @ 3.50GHz               | 3        | 1.58%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 3        | 1.58%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3        | 1.58%   |
| AMD Athlon II X4 620 Processor                 | 3        | 1.58%   |
| Intel Xeon CPU X5690 @ 3.47GHz                 | 2        | 1.05%   |
| Intel Pentium 4 CPU 3.00GHz                    | 2        | 1.05%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 2        | 1.05%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 2        | 1.05%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 2        | 1.05%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 2        | 1.05%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 2        | 1.05%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 2        | 1.05%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 2        | 1.05%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 2        | 1.05%   |
| Intel Core i5-10500 CPU @ 3.10GHz              | 2        | 1.05%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 1.05%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 2        | 1.05%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz          | 2        | 1.05%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 1.05%   |
| AMD Ryzen Embedded V1605B with Radeon Vega Gfx | 2        | 1.05%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 1.05%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 1.05%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 1.05%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 2        | 1.05%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 2        | 1.05%   |
| AMD FX-6300 Six-Core Processor                 | 2        | 1.05%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+     | 2        | 1.05%   |
| Intel Xeon CPU X5680 @ 3.33GHz                 | 1        | 0.53%   |
| Intel Xeon CPU L5640 @ 2.27GHz                 | 1        | 0.53%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 0.53%   |
| Intel Xeon CPU E5462 @ 2.80GHz                 | 1        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 36       | 18.95%  |
| Intel Core i7           | 31       | 16.32%  |
| Intel Core i3           | 20       | 10.53%  |
| AMD Ryzen 5             | 18       | 9.47%   |
| Intel Xeon              | 9        | 4.74%   |
| AMD Ryzen 9             | 9        | 4.74%   |
| Intel Core 2 Quad       | 8        | 4.21%   |
| AMD Ryzen 7             | 5        | 2.63%   |
| AMD FX                  | 5        | 2.63%   |
| AMD Athlon 64 X2        | 5        | 2.63%   |
| Intel Core 2 Duo        | 4        | 2.11%   |
| AMD Ryzen 3             | 4        | 2.11%   |
| Intel Pentium 4         | 3        | 1.58%   |
| Intel Celeron           | 3        | 1.58%   |
| AMD Ryzen Threadripper  | 3        | 1.58%   |
| AMD Athlon II X4        | 3        | 1.58%   |
| Intel Pentium Dual-Core | 2        | 1.05%   |
| Intel Pentium           | 2        | 1.05%   |
| Intel Atom              | 2        | 1.05%   |
| AMD Ryzen Embedded      | 2        | 1.05%   |
| AMD Phenom II X6        | 2        | 1.05%   |
| AMD Phenom II X4        | 2        | 1.05%   |
| AMD A6                  | 2        | 1.05%   |
| AMD A4                  | 2        | 1.05%   |
| Other                   | 1        | 0.53%   |
| Intel Pentium Silver    | 1        | 0.53%   |
| Intel Pentium D         | 1        | 0.53%   |
| AMD Ryzen 5 PRO         | 1        | 0.53%   |
| AMD PRO A10             | 1        | 0.53%   |
| AMD GX                  | 1        | 0.53%   |
| AMD Athlon II X2        | 1        | 0.53%   |
| AMD Athlon Dual Core    | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 90       | 47.87%  |
| 2       | 37       | 19.68%  |
| 6       | 26       | 13.83%  |
| 12      | 12       | 6.38%   |
| 8       | 9        | 4.79%   |
| 1       | 7        | 3.72%   |
| 3       | 2        | 1.06%   |
| 32      | 1        | 0.53%   |
| 24      | 1        | 0.53%   |
| 16      | 1        | 0.53%   |
| 10      | 1        | 0.53%   |
| Unknown | 1        | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 181      | 97.31%  |
| 2      | 5        | 2.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 108      | 56.84%  |
| 1       | 81       | 42.63%  |
| Unknown | 1        | 0.53%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 183      | 98.39%  |
| Unknown        | 3        | 1.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 57       | 29.08%  |
| 0x306a9    | 18       | 9.18%   |
| 0x306c3    | 15       | 7.65%   |
| 0x206a7    | 15       | 7.65%   |
| 0x1067a    | 9        | 4.59%   |
| 0x08701021 | 7        | 3.57%   |
| 0x0800820d | 5        | 2.55%   |
| 0x206c2    | 4        | 2.04%   |
| 0x08108109 | 4        | 2.04%   |
| 0xa0653    | 3        | 1.53%   |
| 0x906ea    | 3        | 1.53%   |
| 0x6fb      | 3        | 1.53%   |
| 0x506e3    | 3        | 1.53%   |
| 0x0810100b | 3        | 1.53%   |
| 0x06000852 | 3        | 1.53%   |
| 0xf43      | 2        | 1.02%   |
| 0x906e9    | 2        | 1.02%   |
| 0x30661    | 2        | 1.02%   |
| 0x106a5    | 2        | 1.02%   |
| 0x0a601203 | 2        | 1.02%   |
| 0x08701013 | 2        | 1.02%   |
| 0x0600611a | 2        | 1.02%   |
| 0x010000db | 2        | 1.02%   |
| 0x010000c8 | 2        | 1.02%   |
| 0xf47      | 1        | 0.51%   |
| 0xf41      | 1        | 0.51%   |
| 0xa0655    | 1        | 0.51%   |
| 0x906ed    | 1        | 0.51%   |
| 0x906eb    | 1        | 0.51%   |
| 0x706a1    | 1        | 0.51%   |
| 0x6f7      | 1        | 0.51%   |
| 0x406f1    | 1        | 0.51%   |
| 0x306e4    | 1        | 0.51%   |
| 0x30678    | 1        | 0.51%   |
| 0x106e5    | 1        | 0.51%   |
| 0x10677    | 1        | 0.51%   |
| 0x10676    | 1        | 0.51%   |
| 0x0a20120a | 1        | 0.51%   |
| 0x0a201205 | 1        | 0.51%   |
| 0x0a201016 | 1        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 26       | 13.9%   |
| SandyBridge   | 21       | 11.23%  |
| Haswell       | 19       | 10.16%  |
| Zen 2         | 16       | 8.56%   |
| Zen+          | 13       | 6.95%   |
| Penryn        | 11       | 5.88%   |
| KabyLake      | 10       | 5.35%   |
| K10           | 8        | 4.28%   |
| Zen           | 7        | 3.74%   |
| Piledriver    | 6        | 3.21%   |
| K8 Hammer     | 6        | 3.21%   |
| Westmere      | 5        | 2.67%   |
| Nehalem       | 5        | 2.67%   |
| Skylake       | 4        | 2.14%   |
| NetBurst      | 4        | 2.14%   |
| Core          | 4        | 2.14%   |
| CometLake     | 4        | 2.14%   |
| Unknown       | 4        | 2.14%   |
| Zen 3         | 3        | 1.6%    |
| Goldmont plus | 2        | 1.07%   |
| Excavator     | 2        | 1.07%   |
| Bonnell       | 2        | 1.07%   |
| Steamroller   | 1        | 0.53%   |
| Silvermont    | 1        | 0.53%   |
| Jaguar        | 1        | 0.53%   |
| Bulldozer     | 1        | 0.53%   |
| Broadwell     | 1        | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 78       | 37.5%   |
| Nvidia | 69       | 33.17%  |
| Intel  | 61       | 29.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15       | 6.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 4.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10       | 4.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 3.65%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 8        | 3.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 3.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 2.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 2.74%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 2.28%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 5        | 2.28%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.83%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1.83%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 1.37%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.37%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.37%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.37%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 3        | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.37%   |
| Intel HD Graphics 630                                                       | 3        | 1.37%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.37%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.37%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.91%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.91%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 0.91%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 2        | 0.91%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 0.91%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 0.91%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 0.91%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 0.91%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.46%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.46%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.46%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.46%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.46%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.46%   |
| Nvidia GT200GL [Quadro FX 3800]                                             | 1        | 0.46%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.46%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 68       | 35.23%  |
| 1 x Nvidia     | 64       | 33.16%  |
| 1 x Intel      | 47       | 24.35%  |
| 2 x AMD        | 6        | 3.11%   |
| Intel + Nvidia | 3        | 1.55%   |
| Intel + AMD    | 2        | 1.04%   |
| AMD + Nvidia   | 2        | 1.04%   |
| 2 x Intel      | 1        | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 147      | 76.96%  |
| Proprietary | 35       | 18.32%  |
| Unknown     | 9        | 4.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 83       | 41.92%  |
| 0.51-1.0   | 26       | 13.13%  |
| 1.01-2.0   | 23       | 11.62%  |
| 7.01-8.0   | 20       | 10.1%   |
| 3.01-4.0   | 18       | 9.09%   |
| 0.01-0.5   | 12       | 6.06%   |
| 5.01-6.0   | 9        | 4.55%   |
| 8.01-16.0  | 4        | 2.02%   |
| 2.01-3.0   | 2        | 1.01%   |
| 16.01-24.0 | 1        | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 41       | 20.81%  |
| Samsung Electronics  | 17       | 8.63%   |
| BenQ                 | 16       | 8.12%   |
| Acer                 | 16       | 8.12%   |
| Hewlett-Packard      | 15       | 7.61%   |
| Philips              | 10       | 5.08%   |
| Iiyama               | 10       | 5.08%   |
| AOC                  | 10       | 5.08%   |
| Goldstar             | 8        | 4.06%   |
| Sony                 | 4        | 2.03%   |
| Ancor Communications | 4        | 2.03%   |
| Vestel Elektronik    | 3        | 1.52%   |
| Lenovo               | 3        | 1.52%   |
| HannStar             | 3        | 1.52%   |
| Apple                | 3        | 1.52%   |
| ___                  | 2        | 1.02%   |
| ViewSonic            | 2        | 1.02%   |
| Unknown              | 2        | 1.02%   |
| Toshiba              | 2        | 1.02%   |
| MiTAC                | 2        | 1.02%   |
| HKC                  | 2        | 1.02%   |
| ASUSTek Computer     | 2        | 1.02%   |
| WIT                  | 1        | 0.51%   |
| Targa Visionary      | 1        | 0.51%   |
| Targa                | 1        | 0.51%   |
| RTK                  | 1        | 0.51%   |
| Packard Bell         | 1        | 0.51%   |
| OEM                  | 1        | 0.51%   |
| NEC Computers        | 1        | 0.51%   |
| MSI                  | 1        | 0.51%   |
| Medion               | 1        | 0.51%   |
| LG Electronics       | 1        | 0.51%   |
| Idek Iiyama          | 1        | 0.51%   |
| HYO                  | 1        | 0.51%   |
| HUAWEI               | 1        | 0.51%   |
| HannStar Display     | 1        | 0.51%   |
| Gigabyte Technology  | 1        | 0.51%   |
| Daewoo               | 1        | 0.51%   |
| CVT                  | 1        | 0.51%   |
| CTX                  | 1        | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                    | 5        | 2.28%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch    | 4        | 1.83%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                        | 3        | 1.37%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                        | 3        | 1.37%   |
| BenQ G2222HDL BNQ7859 1920x1080 477x268mm 21.5-inch                     | 3        | 1.37%   |
| ___ LCDTV16 ___9000 1360x768                                            | 2        | 0.91%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 2        | 0.91%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 2        | 0.91%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 2        | 0.91%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                 | 2        | 0.91%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                       | 2        | 0.91%   |
| Dell E171FP DEL300F 1280x1024 338x270mm 17.0-inch                       | 2        | 0.91%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                       | 2        | 0.91%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch                 | 2        | 0.91%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                       | 2        | 0.91%   |
| Apple LED Cinema APP9236 1920x1200 518x324mm 24.1-inch                  | 2        | 0.91%   |
| AOC U34G2G1 AOC3402 3440x1440 797x334mm 34.0-inch                       | 2        | 0.91%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                     | 2        | 0.91%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                      | 2        | 0.91%   |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                          | 1        | 0.46%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 608x355mm 27.7-inch           | 1        | 0.46%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch           | 1        | 0.46%   |
| Toshiba TV TSB1206 1360x768                                             | 1        | 0.46%   |
| Toshiba 50UHD_LCD_TV TSB3700 3840x2160 1872x1053mm 84.6-inch            | 1        | 0.46%   |
| Targa Visionary LCD22-1 Wide TARA229 1680x1050 474x297mm 22.0-inch      | 1        | 0.46%   |
| Targa LCD Monitor LCDTV16 1360x768                                      | 1        | 0.46%   |
| Sony TV SNY4302 1920x1080                                               | 1        | 0.46%   |
| Sony TV *02 SNYC603 1920x1080 1085x610mm 49.0-inch                      | 1        | 0.46%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                      | 1        | 0.46%   |
| Sony SDM-HS95P SNY2600 1280x1024 376x301mm 19.0-inch                    | 1        | 0.46%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch       | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch    | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch    | 1        | 0.46%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch     | 1        | 0.46%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch       | 1        | 0.46%   |
| Samsung Electronics S24C300 SAM0A28 1920x1080 531x299mm 24.0-inch       | 1        | 0.46%   |
| Samsung Electronics S19E200 SAM0C69 1440x900 408x255mm 18.9-inch        | 1        | 0.46%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch        | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SAM7218 3840x2160 1872x1053mm 84.6-inch | 1        | 0.46%   |
| Samsung Electronics LCD Monitor SAM067C 1920x1080                       | 1        | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 90       | 46.39%  |
| 2560x1440 (QHD)    | 18       | 9.28%   |
| 3840x2160 (4K)     | 16       | 8.25%   |
| 1280x1024 (SXGA)   | 13       | 6.7%    |
| 1440x900 (WXGA+)   | 7        | 3.61%   |
| 3440x1440          | 6        | 3.09%   |
| 1366x768 (WXGA)    | 6        | 3.09%   |
| 1360x768           | 6        | 3.09%   |
| Unknown            | 6        | 3.09%   |
| 1920x1200 (WUXGA)  | 5        | 2.58%   |
| 3840x1080          | 4        | 2.06%   |
| 1680x1050 (WSXGA+) | 4        | 2.06%   |
| 1600x900 (HD+)     | 4        | 2.06%   |
| 1024x768 (XGA)     | 2        | 1.03%   |
| 6400x2160          | 1        | 0.52%   |
| 5280x2560          | 1        | 0.52%   |
| 4480x1440          | 1        | 0.52%   |
| 3600x1080          | 1        | 0.52%   |
| 2560x1080          | 1        | 0.52%   |
| 1920x540           | 1        | 0.52%   |
| 1600x1200          | 1        | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 32       | 16.58%  |
| 24      | 30       | 15.54%  |
| 23      | 27       | 13.99%  |
| 21      | 21       | 10.88%  |
| Unknown | 16       | 8.29%   |
| 19      | 13       | 6.74%   |
| 34      | 7        | 3.63%   |
| 17      | 7        | 3.63%   |
| 31      | 6        | 3.11%   |
| 84      | 5        | 2.59%   |
| 18      | 5        | 2.59%   |
| 32      | 4        | 2.07%   |
| 72      | 3        | 1.55%   |
| 22      | 3        | 1.55%   |
| 20      | 3        | 1.55%   |
| 49      | 2        | 1.04%   |
| 33      | 2        | 1.04%   |
| 15      | 2        | 1.04%   |
| 65      | 1        | 0.52%   |
| 46      | 1        | 0.52%   |
| 35      | 1        | 0.52%   |
| 25      | 1        | 0.52%   |
| 12      | 1        | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 81       | 42.86%  |
| 401-500     | 40       | 21.16%  |
| Unknown     | 16       | 8.47%   |
| 701-800     | 13       | 6.88%   |
| 601-700     | 10       | 5.29%   |
| 301-350     | 9        | 4.76%   |
| 1501-2000   | 8        | 4.23%   |
| 351-400     | 6        | 3.17%   |
| 1001-1500   | 4        | 2.12%   |
| 801-900     | 1        | 0.53%   |
| 201-300     | 1        | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 119      | 68%     |
| 16/10   | 17       | 9.71%   |
| 5/4     | 13       | 7.43%   |
| Unknown | 13       | 7.43%   |
| 21/9    | 7        | 4%      |
| 4/3     | 4        | 2.29%   |
| 32/9    | 1        | 0.57%   |
| 3/2     | 1        | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 66       | 34.2%   |
| 301-350        | 32       | 16.58%  |
| 151-200        | 21       | 10.88%  |
| 351-500        | 19       | 9.84%   |
| Unknown        | 16       | 8.29%   |
| 251-300        | 13       | 6.74%   |
| 141-150        | 11       | 5.7%    |
| More than 1000 | 9        | 4.66%   |
| 501-1000       | 3        | 1.55%   |
| 101-110        | 2        | 1.04%   |
| 71-80          | 1        | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 110      | 59.78%  |
| 101-120 | 37       | 20.11%  |
| Unknown | 16       | 8.7%    |
| 1-50    | 10       | 5.43%   |
| 121-160 | 7        | 3.8%    |
| 161-240 | 4        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 141      | 71.94%  |
| 2     | 41       | 20.92%  |
| 0     | 10       | 5.1%    |
| 3     | 4        | 2.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 97       | 33.22%  |
| Intel                             | 97       | 33.22%  |
| Qualcomm Atheros                  | 14       | 4.79%   |
| Ralink Technology                 | 13       | 4.45%   |
| Broadcom                          | 13       | 4.45%   |
| TP-Link                           | 10       | 3.42%   |
| Ralink                            | 8        | 2.74%   |
| Microsoft                         | 5        | 1.71%   |
| Nvidia                            | 4        | 1.37%   |
| MediaTek                          | 4        | 1.37%   |
| Marvell Technology Group          | 3        | 1.03%   |
| Broadcom Limited                  | 3        | 1.03%   |
| Qualcomm Atheros Communications   | 2        | 0.68%   |
| NetGear                           | 2        | 0.68%   |
| Huawei Technologies               | 2        | 0.68%   |
| Belkin Components                 | 2        | 0.68%   |
| Van Ooijen Technische Informatica | 1        | 0.34%   |
| ULi Electronics                   | 1        | 0.34%   |
| Samsung Electronics               | 1        | 0.34%   |
| NetXen Incorporated               | 1        | 0.34%   |
| Microchip Technology              | 1        | 0.34%   |
| JMicron Technology                | 1        | 0.34%   |
| IMC Networks                      | 1        | 0.34%   |
| HMD Global                        | 1        | 0.34%   |
| DisplayLink                       | 1        | 0.34%   |
| Dexcom                            | 1        | 0.34%   |
| ASUSTek Computer                  | 1        | 0.34%   |
| Aquantia                          | 1        | 0.34%   |
| ADMtek                            | 1        | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75       | 22.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22       | 6.67%   |
| Intel Wi-Fi 6 AX200                                               | 17       | 5.15%   |
| Intel I211 Gigabit Network Connection                             | 11       | 3.33%   |
| Realtek 802.11ac NIC                                              | 9        | 2.73%   |
| Ralink MT7601U Wireless Adapter                                   | 8        | 2.42%   |
| Intel Wireless-AC 9260                                            | 7        | 2.12%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 1.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 1.82%   |
| Microsoft Xbox 360 Wireless Adapter                               | 5        | 1.52%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.52%   |
| Ralink RT5370 Wireless Adapter                                    | 4        | 1.21%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 4        | 1.21%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.21%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 3        | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.91%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.91%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 3        | 0.91%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 0.91%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 0.61%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 0.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.61%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.61%   |
| Intel Wireless 7265                                               | 2        | 0.61%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.61%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2        | 0.61%   |
| Intel 82583V Gigabit Network Connection                           | 2        | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 0.61%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 2        | 0.61%   |
| Van Ooijen Technische Informatica XCM Board                       | 1        | 0.3%    |
| ULi ULi 1689,1573 integrated ethernet.                            | 1        | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 34       | 27.87%  |
| Realtek Semiconductor           | 24       | 19.67%  |
| Ralink Technology               | 13       | 10.66%  |
| Qualcomm Atheros                | 13       | 10.66%  |
| TP-Link                         | 10       | 8.2%    |
| Ralink                          | 8        | 6.56%   |
| Microsoft                       | 5        | 4.1%    |
| Broadcom                        | 4        | 3.28%   |
| Qualcomm Atheros Communications | 2        | 1.64%   |
| NetGear                         | 2        | 1.64%   |
| MediaTek                        | 2        | 1.64%   |
| Belkin Components               | 2        | 1.64%   |
| IMC Networks                    | 1        | 0.82%   |
| Broadcom Limited                | 1        | 0.82%   |
| ASUSTek Computer                | 1        | 0.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 17       | 13.6%   |
| Realtek 802.11ac NIC                                                          | 9        | 7.2%    |
| Ralink MT7601U Wireless Adapter                                               | 8        | 6.4%    |
| Intel Wireless-AC 9260                                                        | 7        | 5.6%    |
| Microsoft Xbox 360 Wireless Adapter                                           | 5        | 4%      |
| Ralink RT5370 Wireless Adapter                                                | 4        | 3.2%    |
| Ralink RT2561/RT61 802.11g PCI                                                | 4        | 3.2%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 3        | 2.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 3        | 2.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 2.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 2.4%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 3        | 2.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2        | 1.6%    |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 1.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 1.6%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 1.6%    |
| Intel Wireless 7265                                                           | 2        | 1.6%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 1.6%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.8%    |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                     | 1        | 0.8%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1        | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.8%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 0.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.8%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1        | 0.8%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1        | 0.8%    |
| Ralink Wireless Adapter Canyon CN-WF511                                       | 1        | 0.8%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 0.8%    |
| Ralink RT5592 PCIe Wireless Network Adapter                                   | 1        | 0.8%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 1        | 0.8%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 0.8%    |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 84       | 43.3%   |
| Intel                    | 79       | 40.72%  |
| Broadcom                 | 10       | 5.15%   |
| Nvidia                   | 4        | 2.06%   |
| Marvell Technology Group | 3        | 1.55%   |
| Qualcomm Atheros         | 2        | 1.03%   |
| Broadcom Limited         | 2        | 1.03%   |
| ULi Electronics          | 1        | 0.52%   |
| Samsung Electronics      | 1        | 0.52%   |
| NetXen Incorporated      | 1        | 0.52%   |
| MediaTek                 | 1        | 0.52%   |
| JMicron Technology       | 1        | 0.52%   |
| Huawei Technologies      | 1        | 0.52%   |
| HMD Global               | 1        | 0.52%   |
| DisplayLink              | 1        | 0.52%   |
| Aquantia                 | 1        | 0.52%   |
| ADMtek                   | 1        | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 75       | 37.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 22       | 11%     |
| Intel I211 Gigabit Network Connection                                          | 11       | 5.5%    |
| Intel Ethernet Connection I217-LM                                              | 7        | 3.5%    |
| Realtek RTL8125 2.5GbE Controller                                              | 6        | 3%      |
| Intel 82567LM-3 Gigabit Network Connection                                     | 6        | 3%      |
| Intel Ethernet Connection (2) I218-V                                           | 5        | 2.5%    |
| Intel 82579V Gigabit Network Connection                                        | 4        | 2%      |
| Intel Ethernet Connection I217-V                                               | 3        | 1.5%    |
| Intel Ethernet Connection (2) I219-V                                           | 3        | 1.5%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 3        | 1.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2        | 1%      |
| Nvidia MCP61 Ethernet                                                          | 2        | 1%      |
| Intel I210 Gigabit Network Connection                                          | 2        | 1%      |
| Intel Ethernet Controller I225-V                                               | 2        | 1%      |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1%      |
| Intel 82583V Gigabit Network Connection                                        | 2        | 1%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2        | 1%      |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 2        | 1%      |
| ULi ULi 1689,1573 integrated ethernet.                                         | 1        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 0.5%    |
| Nvidia MCP55 Ethernet                                                          | 1        | 0.5%    |
| Nvidia MCP51 Ethernet Controller                                               | 1        | 0.5%    |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter           | 1        | 0.5%    |
| MediaTek Titan pocket                                                          | 1        | 0.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1        | 0.5%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1        | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1        | 0.5%    |
| Intel NM10/ICH7 Family LAN Controller                                          | 1        | 0.5%    |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 0.5%    |
| Intel Ethernet Connection (14) I219-LM                                         | 1        | 0.5%    |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 184      | 62.59%  |
| WiFi     | 105      | 35.71%  |
| Modem    | 5        | 1.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 146      | 71.57%  |
| WiFi     | 58       | 28.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 60.53%  |
| 2     | 61       | 32.11%  |
| 3     | 10       | 5.26%   |
| 0     | 2        | 1.05%   |
| 6     | 1        | 0.53%   |
| 4     | 1        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 170      | 89.95%  |
| Yes  | 19       | 10.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 30       | 40.54%  |
| Cambridge Silicon Radio         | 18       | 24.32%  |
| Broadcom                        | 6        | 8.11%   |
| ASUSTek Computer                | 6        | 8.11%   |
| TP-Link                         | 2        | 2.7%    |
| Qualcomm Atheros Communications | 2        | 2.7%    |
| Belkin Components               | 2        | 2.7%    |
| Apple                           | 2        | 2.7%    |
| Realtek Semiconductor           | 1        | 1.35%   |
| MediaTek                        | 1        | 1.35%   |
| ISSC                            | 1        | 1.35%   |
| IMC Networks                    | 1        | 1.35%   |
| Dell                            | 1        | 1.35%   |
| Conwise Technology              | 1        | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18       | 24%     |
| Intel AX200 Bluetooth                               | 15       | 20%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6        | 8%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 6        | 8%      |
| Intel Bluetooth wireless interface                  | 4        | 5.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 4%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3        | 4%      |
| TP-Link UB500 Adapter                               | 2        | 2.67%   |
| Intel AX201 Bluetooth                               | 2        | 2.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.33%   |
| MediaTek Wireless_Device                            | 1        | 1.33%   |
| ISSC Bluetooth Device                               | 1        | 1.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.33%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.33%   |
| Dell BT Mini-Receiver                               | 1        | 1.33%   |
| Conwise CW6622                                      | 1        | 1.33%   |
| Belkin Components F8T012 Bluetooth Adapter          | 1        | 1.33%   |
| Belkin Components Bluetooth Mini Dongle             | 1        | 1.33%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 1.33%   |
| ASUS Bluetooth Device                               | 1        | 1.33%   |
| ASUS BCM20702A0                                     | 1        | 1.33%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.33%   |
| Apple Bluetooth HCI                                 | 1        | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 114      | 34.65%  |
| AMD                                             | 97       | 29.48%  |
| Nvidia                                          | 64       | 19.45%  |
| Creative Labs                                   | 7        | 2.13%   |
| Plantronics                                     | 4        | 1.22%   |
| Kingston Technology                             | 4        | 1.22%   |
| C-Media Electronics                             | 4        | 1.22%   |
| Creative Technology                             | 3        | 0.91%   |
| Texas Instruments                               | 2        | 0.61%   |
| Micronas                                        | 2        | 0.61%   |
| Logitech                                        | 2        | 0.61%   |
| JMTek                                           | 2        | 0.61%   |
| Giga-Byte Technology                            | 2        | 0.61%   |
| Ensoniq                                         | 2        | 0.61%   |
| Blue Microphones                                | 2        | 0.61%   |
| ULi Electronics                                 | 1        | 0.3%    |
| Turtle Beach                                    | 1        | 0.3%    |
| Sony                                            | 1        | 0.3%    |
| SAVITECH                                        | 1        | 0.3%    |
| RODE Microphones                                | 1        | 0.3%    |
| Razer USA                                       | 1        | 0.3%    |
| Native Instruments                              | 1        | 0.3%    |
| M-Audio                                         | 1        | 0.3%    |
| Licensed by Sony Computer Entertainment America | 1        | 0.3%    |
| GN Netcom                                       | 1        | 0.3%    |
| Focusrite-Novation                              | 1        | 0.3%    |
| FiiO Electronics Technology                     | 1        | 0.3%    |
| Dell                                            | 1        | 0.3%    |
| Corsair                                         | 1        | 0.3%    |
| BEHRINGER International                         | 1        | 0.3%    |
| AudioQuest                                      | 1        | 0.3%    |
| Audio-Technica                                  | 1        | 0.3%    |
| AOKEO                                           | 1        | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 26       | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 19       | 4.87%   |
| AMD Starship/Matisse HD Audio Controller                                          | 19       | 4.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 15       | 3.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 15       | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 3.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 14       | 3.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 13       | 3.33%   |
| AMD Family 17h/19h HD Audio Controller                                            | 13       | 3.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 2.56%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9        | 2.31%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 8        | 2.05%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8        | 2.05%   |
| Nvidia GP106 High Definition Audio Controller                                     | 6        | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 6        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 6        | 1.54%   |
| Nvidia GM204 High Definition Audio Controller                                     | 5        | 1.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 1.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 5        | 1.28%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 5        | 1.28%   |
| AMD Navi 10 HDMI Audio                                                            | 5        | 1.28%   |
| Nvidia High Definition Audio Controller                                           | 4        | 1.03%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 1.03%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 1.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 4        | 1.03%   |
| AMD FCH Azalia Controller                                                         | 4        | 1.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 4        | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.77%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 0.77%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 0.77%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.77%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 0.77%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 3        | 0.77%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2        | 0.51%   |
| Plantronics Blackwire C5220 headset (remote control and 3.5mm audio adapter)      | 2        | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 25       | 21.19%  |
| Crucial             | 16       | 13.56%  |
| Unknown             | 15       | 12.71%  |
| SK hynix            | 13       | 11.02%  |
| Kingston            | 12       | 10.17%  |
| Samsung Electronics | 8        | 6.78%   |
| Micron Technology   | 7        | 5.93%   |
| G.Skill             | 7        | 5.93%   |
| Team                | 3        | 2.54%   |
| Ramaxel Technology  | 2        | 1.69%   |
| Patriot             | 2        | 1.69%   |
| A-DATA Technology   | 2        | 1.69%   |
| Toshiba             | 1        | 0.85%   |
| Infineon            | 1        | 0.85%   |
| Elpida              | 1        | 0.85%   |
| BiNFUL              | 1        | 0.85%   |
| Apacer              | 1        | 0.85%   |
| A Force             | 1        | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s | 5        | 3.73%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s | 3        | 2.24%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s               | 2        | 1.49%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 2        | 1.49%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                 | 2        | 1.49%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s  | 2        | 1.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s  | 2        | 1.49%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s  | 2        | 1.49%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s   | 2        | 1.49%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s  | 2        | 1.49%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s | 2        | 1.49%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s | 2        | 1.49%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                  | 1        | 0.75%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s          | 1        | 0.75%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s               | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                  | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                  | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s          | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM 667MT/s                   | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s          | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM                        | 1        | 0.75%   |
| Unknown RAM Module 1GB DIMM 667MT/s                   | 1        | 0.75%   |
| Unknown RAM Module 128MB DIMM SDRAM                   | 1        | 0.75%   |
| Toshiba RAM 99U5702-094.A00G 8GB DIMM DDR4 2400MT/s   | 1        | 0.75%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s    | 1        | 0.75%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s            | 1        | 0.75%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1067MT/s         | 1        | 0.75%   |
| SK hynix RAM Module 16GB DIMM DDR3 1866MT/s           | 1        | 0.75%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s   | 1        | 0.75%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s  | 1        | 0.75%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s  | 1        | 0.75%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s  | 1        | 0.75%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s  | 1        | 0.75%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 0.75%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s | 1        | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 0.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 39       | 38.61%  |
| DDR3    | 38       | 37.62%  |
| Unknown | 12       | 11.88%  |
| SDRAM   | 6        | 5.94%   |
| DDR2    | 4        | 3.96%   |
| DDR5    | 1        | 0.99%   |
| DDR     | 1        | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 95       | 96.94%  |
| SODIMM | 3        | 3.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 41       | 36.28%  |
| 4096  | 29       | 25.66%  |
| 2048  | 17       | 15.04%  |
| 16384 | 16       | 14.16%  |
| 32768 | 4        | 3.54%   |
| 1024  | 4        | 3.54%   |
| 512   | 1        | 0.88%   |
| 128   | 1        | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 22       | 18.8%   |
| 1333    | 14       | 11.97%  |
| 3200    | 9        | 7.69%   |
| 2400    | 8        | 6.84%   |
| 3600    | 7        | 5.98%   |
| 2667    | 6        | 5.13%   |
| 800     | 6        | 5.13%   |
| 2133    | 5        | 4.27%   |
| 667     | 5        | 4.27%   |
| 3533    | 3        | 2.56%   |
| 1867    | 3        | 2.56%   |
| 1866    | 3        | 2.56%   |
| 1800    | 3        | 2.56%   |
| 3400    | 2        | 1.71%   |
| 3266    | 2        | 1.71%   |
| 1648    | 2        | 1.71%   |
| 1066    | 2        | 1.71%   |
| 533     | 2        | 1.71%   |
| Unknown | 2        | 1.71%   |
| 5200    | 1        | 0.85%   |
| 4800    | 1        | 0.85%   |
| 3800    | 1        | 0.85%   |
| 3733    | 1        | 0.85%   |
| 3000    | 1        | 0.85%   |
| 2933    | 1        | 0.85%   |
| 2733    | 1        | 0.85%   |
| 2666    | 1        | 0.85%   |
| 1639    | 1        | 0.85%   |
| 1067    | 1        | 0.85%   |
| 400     | 1        | 0.85%   |

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
| Logitech                      | 16       | 44.44%  |
| Microsoft                     | 4        | 11.11%  |
| Sunplus Innovation Technology | 2        | 5.56%   |
| Microdia                      | 2        | 5.56%   |
| Generalplus Technology        | 2        | 5.56%   |
| Creative Technology           | 2        | 5.56%   |
| WaveRider Communications      | 1        | 2.78%   |
| Samsung Electronics           | 1        | 2.78%   |
| Realtek Semiconductor         | 1        | 2.78%   |
| Razer USA                     | 1        | 2.78%   |
| GenesysLogic Technology       | 1        | 2.78%   |
| GEMBIRD                       | 1        | 2.78%   |
| Chicony Electronics           | 1        | 2.78%   |
| Apple                         | 1        | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                       | 7        | 18.92%  |
| Microsoft LifeCam HD-3000                         | 3        | 8.11%   |
| Logitech Webcam C925e                             | 2        | 5.41%   |
| Logitech Webcam C270                              | 2        | 5.41%   |
| Creative Live! Cam Sync HD [VF0770]               | 2        | 5.41%   |
| WaveRider USB 2.0 Camera                          | 1        | 2.7%    |
| Sunplus papalook AF 925                           | 1        | 2.7%    |
| Sunplus HD 720P webcam                            | 1        | 2.7%    |
| Samsung Galaxy series, misc. (MTP mode)           | 1        | 2.7%    |
| Realtek FULL HD 1080P Webcam                      | 1        | 2.7%    |
| Razer USA Gaming Webcam [Kiyo]                    | 1        | 2.7%    |
| Microsoft LifeCam NX-3000 (UVC-compliant)         | 1        | 2.7%    |
| Microdia USB 2.0 Camera                           | 1        | 2.7%    |
| Microdia CyberTrack H6                            | 1        | 2.7%    |
| Logitech Webcam C310                              | 1        | 2.7%    |
| Logitech Webcam C210                              | 1        | 2.7%    |
| Logitech Webcam C120                              | 1        | 2.7%    |
| Logitech QuickCam Vision Pro                      | 1        | 2.7%    |
| Logitech Logitech Webcam C160                     | 1        | 2.7%    |
| Logitech C922 Pro Stream Webcam                   | 1        | 2.7%    |
| GenesysLogic USB2.0 UVC PC Camera                 | 1        | 2.7%    |
| Generalplus GENERAL WEBCAM                        | 1        | 2.7%    |
| Generalplus 808 Camera #9 (web-cam mode)          | 1        | 2.7%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 2.7%    |
| Chicony USB2.0 2MP UVC Camera                     | 1        | 2.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 1        | 2.7%    |

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
| 0     | 157      | 82.2%   |
| 1     | 28       | 14.66%  |
| 2     | 4        | 2.09%   |
| 5     | 1        | 0.52%   |
| 3     | 1        | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 19       | 48.72%  |
| Graphics card            | 11       | 28.21%  |
| Multimedia controller    | 3        | 7.69%   |
| Net/ethernet             | 2        | 5.13%   |
| Unassigned class         | 1        | 2.56%   |
| Sound                    | 1        | 2.56%   |
| Communication controller | 1        | 2.56%   |
| Camera                   | 1        | 2.56%   |

