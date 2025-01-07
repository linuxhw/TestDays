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

Total: 394

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | Z170M Pro4S                 | [14a8e0fe62](https://linux-hardware.org/?probe=14a8e0fe62) | Dec 31, 2024 |
| ASRock        | A75 Extreme6                | [86fd341a89](https://linux-hardware.org/?probe=86fd341a89) | Dec 31, 2024 |
| ASUSTek       | PRIME A520M-K               | [83995fdfa3](https://linux-hardware.org/?probe=83995fdfa3) | Dec 21, 2024 |
| ASUSTek       | H81-PLUS                    | [b1c71133ae](https://linux-hardware.org/?probe=b1c71133ae) | Dec 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [80d60e6ac6](https://linux-hardware.org/?probe=80d60e6ac6) | Dec 19, 2024 |
| Gigabyte      | B450 AORUS M                | [7dfcccc6eb](https://linux-hardware.org/?probe=7dfcccc6eb) | Dec 19, 2024 |
| Dell          | 0JP3NX A00                  | [f80311b20d](https://linux-hardware.org/?probe=f80311b20d) | Dec 18, 2024 |
| Dell          | 0200DY A02                  | [4cf84c1ce5](https://linux-hardware.org/?probe=4cf84c1ce5) | Dec 06, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [d025744ff8](https://linux-hardware.org/?probe=d025744ff8) | Dec 06, 2024 |
| ASUSTek       | V-P8H67E                    | [d1c21b9076](https://linux-hardware.org/?probe=d1c21b9076) | Dec 03, 2024 |
| ASUSTek       | V-P8H67E                    | [89f2b30be4](https://linux-hardware.org/?probe=89f2b30be4) | Nov 28, 2024 |
| Gigabyte      | X870 AORUS ELITE WIFI7      | [5193ed5476](https://linux-hardware.org/?probe=5193ed5476) | Nov 01, 2024 |
| ASUSTek       | PRIME B550M-A               | [d0f6ac1a5b](https://linux-hardware.org/?probe=d0f6ac1a5b) | Oct 29, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a4f16dff63](https://linux-hardware.org/?probe=a4f16dff63) | Oct 25, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [dccda71823](https://linux-hardware.org/?probe=dccda71823) | Oct 22, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1fb4ba033c](https://linux-hardware.org/?probe=1fb4ba033c) | Oct 19, 2024 |
| Dell          | 0J3C2F A00                  | [13429e7bda](https://linux-hardware.org/?probe=13429e7bda) | Oct 17, 2024 |
| ASRock        | Z77 Extreme3                | [d8afc712e5](https://linux-hardware.org/?probe=d8afc712e5) | Oct 02, 2024 |
| ASRock        | Z77 Extreme3                | [506ca6ed34](https://linux-hardware.org/?probe=506ca6ed34) | Oct 02, 2024 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [0da6f1fd46](https://linux-hardware.org/?probe=0da6f1fd46) | Sep 28, 2024 |
| Dell          | 0NW73C A01                  | [a219f52b9b](https://linux-hardware.org/?probe=a219f52b9b) | Sep 25, 2024 |
| Dell          | 0NW73C A01                  | [6f6c30cd6f](https://linux-hardware.org/?probe=6f6c30cd6f) | Sep 25, 2024 |
| MSI           | 2AE0                        | [7ccc588275](https://linux-hardware.org/?probe=7ccc588275) | Sep 23, 2024 |
| HP            | 0B4Ch D                     | [798c2aed63](https://linux-hardware.org/?probe=798c2aed63) | Sep 22, 2024 |
| Pegatron      | 2A6C                        | [46d503af68](https://linux-hardware.org/?probe=46d503af68) | Sep 21, 2024 |
| ASUSTek       | PRIME A520M-K               | [0de24f49c8](https://linux-hardware.org/?probe=0de24f49c8) | Sep 17, 2024 |
| MSI           | MAG B550M MORTAR            | [f1283f35a2](https://linux-hardware.org/?probe=f1283f35a2) | Sep 12, 2024 |
| Foxconn       | 2AA9h                       | [20e06a61c2](https://linux-hardware.org/?probe=20e06a61c2) | Sep 09, 2024 |
| MSI           | PRO B650-VC WIFI            | [047d37a789](https://linux-hardware.org/?probe=047d37a789) | Sep 08, 2024 |
| ASRock        | AB350M                      | [1cd8bb8d06](https://linux-hardware.org/?probe=1cd8bb8d06) | Sep 03, 2024 |
| Dell          | 0K240Y A02                  | [8e63f0cc67](https://linux-hardware.org/?probe=8e63f0cc67) | Aug 30, 2024 |
| Dell          | 0PRR48 A01                  | [d92db0ea54](https://linux-hardware.org/?probe=d92db0ea54) | Aug 12, 2024 |
| ASRock        | B650M Pro RS WiFi           | [0d84feef29](https://linux-hardware.org/?probe=0d84feef29) | Aug 06, 2024 |
| HP            | ProLiant MicroServer        | [cd4e49eeeb](https://linux-hardware.org/?probe=cd4e49eeeb) | Aug 05, 2024 |
| Dell          | 0FDY5C A00                  | [f494d1f180](https://linux-hardware.org/?probe=f494d1f180) | Aug 03, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | [6b88264648](https://linux-hardware.org/?probe=6b88264648) | Jul 31, 2024 |
| Gigabyte      | B85-HD3                     | [ce9e0e79fb](https://linux-hardware.org/?probe=ce9e0e79fb) | Jul 10, 2024 |
| ASRock        | X399 Taichi                 | [75a6e84995](https://linux-hardware.org/?probe=75a6e84995) | Jun 08, 2024 |
| Dell          | 0JP3NX A00                  | [0c47cbeefd](https://linux-hardware.org/?probe=0c47cbeefd) | Jun 03, 2024 |
| HP            | 87D6 SMVB                   | [45c984912b](https://linux-hardware.org/?probe=45c984912b) | Jun 02, 2024 |
| ASUSTek       | P8H77-M PRO                 | [b5afb9f441](https://linux-hardware.org/?probe=b5afb9f441) | May 23, 2024 |
| Gigabyte      | Z77-DS3H                    | [a36dfede38](https://linux-hardware.org/?probe=a36dfede38) | May 23, 2024 |
| Dell          | 0HJ054                      | [8d6c3f640c](https://linux-hardware.org/?probe=8d6c3f640c) | May 22, 2024 |
| Gigabyte      | Z77-DS3H                    | [b044004def](https://linux-hardware.org/?probe=b044004def) | May 18, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | [c96622de49](https://linux-hardware.org/?probe=c96622de49) | May 18, 2024 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [a566624747](https://linux-hardware.org/?probe=a566624747) | May 15, 2024 |
| Gigabyte      | Z77-DS3H                    | [239aa09252](https://linux-hardware.org/?probe=239aa09252) | May 04, 2024 |
| Shenzhen M... | F7BFC                       | [43fd55c47a](https://linux-hardware.org/?probe=43fd55c47a) | Apr 30, 2024 |
| Shenzhen M... | F7BFC                       | [d480d08c5e](https://linux-hardware.org/?probe=d480d08c5e) | Apr 30, 2024 |
| MSI           | PRO B650M-P                 | [90165c7480](https://linux-hardware.org/?probe=90165c7480) | Apr 18, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [24acebde2b](https://linux-hardware.org/?probe=24acebde2b) | Apr 18, 2024 |
| Gigabyte      | Z77-DS3H                    | [c0e482caa4](https://linux-hardware.org/?probe=c0e482caa4) | Apr 16, 2024 |
| ANGXUN        | X99-DM3 V3.0                | [7beaf3fb93](https://linux-hardware.org/?probe=7beaf3fb93) | Apr 14, 2024 |
| Alienware     | 0TYR0X A01                  | [ef1d3c4e97](https://linux-hardware.org/?probe=ef1d3c4e97) | Apr 04, 2024 |
| HP            | 21D0                        | [8097b780d4](https://linux-hardware.org/?probe=8097b780d4) | Apr 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e04b94ae7b](https://linux-hardware.org/?probe=e04b94ae7b) | Mar 30, 2024 |
| ASUSTek       | PRIME B760M-A               | [df41ae1364](https://linux-hardware.org/?probe=df41ae1364) | Feb 20, 2024 |
| HP            | 21D0                        | [a19cdbd10a](https://linux-hardware.org/?probe=a19cdbd10a) | Feb 20, 2024 |
| Dell          | 051FJ8 A00                  | [abce3a8f48](https://linux-hardware.org/?probe=abce3a8f48) | Feb 06, 2024 |
| HP            | 21D0                        | [b9cb80ae88](https://linux-hardware.org/?probe=b9cb80ae88) | Jan 23, 2024 |
| Gigabyte      | GA-MA790X-UD4P              | [4e5951814a](https://linux-hardware.org/?probe=4e5951814a) | Jan 09, 2024 |
| MSI           | B550 GAMING GEN3            | [02163b04b7](https://linux-hardware.org/?probe=02163b04b7) | Dec 30, 2023 |
| HP            | 8643 SMVB                   | [bbdb2204d8](https://linux-hardware.org/?probe=bbdb2204d8) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | [03ddd69e34](https://linux-hardware.org/?probe=03ddd69e34) | Dec 22, 2023 |
| Gigabyte      | B85M-D3H                    | [1dd35fdb02](https://linux-hardware.org/?probe=1dd35fdb02) | Dec 19, 2023 |
| Dell          | 051FJ8 A00                  | [18f1d4c5d0](https://linux-hardware.org/?probe=18f1d4c5d0) | Dec 18, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [647f96ad2c](https://linux-hardware.org/?probe=647f96ad2c) | Dec 08, 2023 |
| ASRock        | H310CM-DVS                  | [ec402bfe2f](https://linux-hardware.org/?probe=ec402bfe2f) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | [8425b9dc62](https://linux-hardware.org/?probe=8425b9dc62) | Nov 30, 2023 |
| Dell          | 03NVJ6 A03                  | [9a5c924695](https://linux-hardware.org/?probe=9a5c924695) | Nov 26, 2023 |
| AZW           | Green G3                    | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| Dell          | 0X4H68 A00                  | [9fe4290fb6](https://linux-hardware.org/?probe=9fe4290fb6) | Nov 21, 2023 |
| Dell          | 0X4H68 A00                  | [93d573033d](https://linux-hardware.org/?probe=93d573033d) | Nov 21, 2023 |
| MSI           | 970 GAMING                  | [1d3516385d](https://linux-hardware.org/?probe=1d3516385d) | Nov 16, 2023 |
| Unknown       | Unknown                     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| Dell          | 0J8H4R A00                  | [d743b33cc7](https://linux-hardware.org/?probe=d743b33cc7) | Nov 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [fc6336fedd](https://linux-hardware.org/?probe=fc6336fedd) | Nov 02, 2023 |
| HP            | 3399                        | [3dca1c2950](https://linux-hardware.org/?probe=3dca1c2950) | Oct 22, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [86fca6aaf4](https://linux-hardware.org/?probe=86fca6aaf4) | Oct 20, 2023 |
| MSI           | X470 GAMING PRO             | [88057db3aa](https://linux-hardware.org/?probe=88057db3aa) | Oct 11, 2023 |
| Dell          | 0YJPT1 A00                  | [27b01f468d](https://linux-hardware.org/?probe=27b01f468d) | Sep 30, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [20e0572ade](https://linux-hardware.org/?probe=20e0572ade) | Sep 21, 2023 |
| HP            | 0B54h D                     | [f5259ad0b1](https://linux-hardware.org/?probe=f5259ad0b1) | Sep 16, 2023 |
| Gigabyte      | B75M-D2V                    | [8f6631088b](https://linux-hardware.org/?probe=8f6631088b) | Sep 08, 2023 |
| ASUSTek       | TALAS                       | [094153c6f4](https://linux-hardware.org/?probe=094153c6f4) | Sep 04, 2023 |
| Dell          | 0TDG4V A01                  | [0f98d77b72](https://linux-hardware.org/?probe=0f98d77b72) | Sep 01, 2023 |
| Gigabyte      | X58A-UD7                    | [9d47465c31](https://linux-hardware.org/?probe=9d47465c31) | Aug 29, 2023 |
| Dell          | 0WR7PY A02                  | [db091802b1](https://linux-hardware.org/?probe=db091802b1) | Aug 26, 2023 |
| Gigabyte      | Z77-DS3H                    | [8f51778271](https://linux-hardware.org/?probe=8f51778271) | Aug 25, 2023 |
| ASUSTek       | A68HM-PLUS                  | [7e397373d8](https://linux-hardware.org/?probe=7e397373d8) | Aug 25, 2023 |
| Dell          | 0200DY A02                  | [0182dad759](https://linux-hardware.org/?probe=0182dad759) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [23d9892448](https://linux-hardware.org/?probe=23d9892448) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [e280c00c8b](https://linux-hardware.org/?probe=e280c00c8b) | Aug 12, 2023 |
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
| Ubuntu 20.04                 | 29       | 10.14%  |
| Ubuntu 18.04                 | 12       | 4.2%    |
| ArcoLinux Rolling            | 10       | 3.5%    |
| Arch Rolling                 | 10       | 3.5%    |
| Debian 11                    | 9        | 3.15%   |
| Ubuntu 22.04                 | 8        | 2.8%    |
| OpenMandriva 4.2             | 6        | 2.1%    |
| Manjaro                      | 6        | 2.1%    |
| Ubuntu 19.04                 | 5        | 1.75%   |
| Pop!_OS 22.04                | 5        | 1.75%   |
| Linux Mint 20.2              | 5        | 1.75%   |
| Linux Mint 20                | 5        | 1.75%   |
| Fedora 40                    | 5        | 1.75%   |
| Arch                         | 5        | 1.75%   |
| Zorin 16                     | 4        | 1.4%    |
| Ubuntu 24.04                 | 4        | 1.4%    |
| ROSA R11                     | 4        | 1.4%    |
| Pop!_OS 21.10                | 4        | 1.4%    |
| Pop!_OS 20.10                | 4        | 1.4%    |
| OpenMandriva 4.3             | 4        | 1.4%    |
| Linux Mint 20.3              | 4        | 1.4%    |
| Linux Mint 20.1              | 4        | 1.4%    |
| Gentoo 2.14                  | 4        | 1.4%    |
| Fedora 38                    | 4        | 1.4%    |
| Fedora 35                    | 4        | 1.4%    |
| Debian 12                    | 4        | 1.4%    |
| Zorin 17                     | 3        | 1.05%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.05%   |
| Linux Mint 21.3              | 3        | 1.05%   |
| KDE neon 22.04               | 3        | 1.05%   |
| Fedora 37                    | 3        | 1.05%   |
| Fedora 32                    | 3        | 1.05%   |
| BlackPanther 18.1            | 3        | 1.05%   |
| Xubuntu 22.04                | 2        | 0.7%    |
| SteamOS 3.4                  | 2        | 0.7%    |
| ROSA R11.1                   | 2        | 0.7%    |
| ROSA R10                     | 2        | 0.7%    |
| OpenMandriva 4.50            | 2        | 0.7%    |
| OpenMandriva 24.12           | 2        | 0.7%    |
| OpenMandriva 24.07           | 2        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 59       | 22.78%  |
| Linux Mint   | 27       | 10.42%  |
| Fedora       | 21       | 8.11%   |
| OpenMandriva | 20       | 7.72%   |
| Debian       | 17       | 6.56%   |
| Arch         | 15       | 5.79%   |
| Pop!_OS      | 13       | 5.02%   |
| Manjaro      | 10       | 3.86%   |
| ArcoLinux    | 10       | 3.86%   |
| Zorin        | 8        | 3.09%   |
| ROSA         | 8        | 3.09%   |
| KDE neon     | 6        | 2.32%   |
| Xubuntu      | 5        | 1.93%   |
| Kubuntu      | 5        | 1.93%   |
| Gentoo       | 5        | 1.93%   |
| SteamOS      | 3        | 1.16%   |
| openSUSE     | 3        | 1.16%   |
| BlackPanther | 3        | 1.16%   |
| MX           | 2        | 0.77%   |
| Lubuntu      | 2        | 0.77%   |
| Kali         | 2        | 0.77%   |
| Endless      | 2        | 0.77%   |
| Elementary   | 2        | 0.77%   |
| Solus        | 1        | 0.39%   |
| Peppermint   | 1        | 0.39%   |
| Parrot       | 1        | 0.39%   |
| Nobara       | 1        | 0.39%   |
| NixOS        | 1        | 0.39%   |
| Linux Lite   | 1        | 0.39%   |
| Garuda Linux | 1        | 0.39%   |
| Feren OS     | 1        | 0.39%   |
| Clear Linux  | 1        | 0.39%   |
| Bazzite      | 1        | 0.39%   |
| Alpine       | 1        | 0.39%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.4.0-42-generic                | 7        | 2.14%   |
| 5.10.14-desktop-1omv4002        | 6        | 1.83%   |
| 6.8.0-45-generic                | 4        | 1.22%   |
| 5.4.0-48-generic                | 4        | 1.22%   |
| 5.16.7-desktop-1omv4003         | 4        | 1.22%   |
| 5.10.0-23-amd64                 | 4        | 1.22%   |
| 6.5.0-26-generic                | 3        | 0.92%   |
| 6.2.0-26-generic                | 3        | 0.92%   |
| 5.8.0-7630-generic              | 3        | 0.92%   |
| 5.4.0-91-generic                | 3        | 0.92%   |
| 5.4.0-47-generic                | 3        | 0.92%   |
| 5.3.0-28-generic                | 3        | 0.92%   |
| 5.17.5-arch1-1                  | 3        | 0.92%   |
| 5.15.11-76051511-generic        | 3        | 0.92%   |
| 4.18.16-desktop-1bP             | 3        | 0.92%   |
| 6.8.0-49-generic                | 2        | 0.61%   |
| 6.4.11-desktop-1omv2390         | 2        | 0.61%   |
| 6.2.6-desktop-1omv2390          | 2        | 0.61%   |
| 6.12.1-desktop-1omv2490         | 2        | 0.61%   |
| 6.10.0-desktop-1omv2490         | 2        | 0.61%   |
| 5.8.14-arch1-1                  | 2        | 0.61%   |
| 5.8.0-43-generic                | 2        | 0.61%   |
| 5.8.0-41-generic                | 2        | 0.61%   |
| 5.4.0-88-generic                | 2        | 0.61%   |
| 5.4.0-77-generic                | 2        | 0.61%   |
| 5.4.0-72-generic                | 2        | 0.61%   |
| 5.4.0-37-generic                | 2        | 0.61%   |
| 5.3.0-45-generic                | 2        | 0.61%   |
| 5.19.0-35-generic               | 2        | 0.61%   |
| 5.17.5-76051705-generic         | 2        | 0.61%   |
| 5.16.15-76051615-generic        | 2        | 0.61%   |
| 5.15.0-56-generic               | 2        | 0.61%   |
| 5.15.0-46-generic               | 2        | 0.61%   |
| 5.13.13-arch1-1                 | 2        | 0.61%   |
| 5.13.0-39-generic               | 2        | 0.61%   |
| 5.12.4-desktop-1omv4050         | 2        | 0.61%   |
| 5.11.0-43-generic               | 2        | 0.61%   |
| 5.0.0-23-generic                | 2        | 0.61%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2        | 0.61%   |
| 4.9.60-nrj-desktop-1rosa-i586   | 2        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 38       | 12.26%  |
| 5.15.0  | 15       | 4.84%   |
| 6.8.0   | 11       | 3.55%   |
| 4.15.0  | 11       | 3.55%   |
| 5.8.0   | 10       | 3.23%   |
| 5.10.0  | 9        | 2.9%    |
| 6.5.0   | 8        | 2.58%   |
| 5.3.0   | 8        | 2.58%   |
| 5.19.0  | 8        | 2.58%   |
| 5.13.0  | 7        | 2.26%   |
| 5.11.0  | 7        | 2.26%   |
| 5.0.0   | 7        | 2.26%   |
| 6.2.0   | 6        | 1.94%   |
| 5.17.5  | 6        | 1.94%   |
| 5.10.14 | 6        | 1.94%   |
| 4.18.0  | 5        | 1.61%   |
| 6.10.9  | 4        | 1.29%   |
| 6.1.0   | 4        | 1.29%   |
| 5.16.7  | 4        | 1.29%   |
| 5.15.11 | 3        | 0.97%   |
| 4.18.16 | 3        | 0.97%   |
| 6.9.12  | 2        | 0.65%   |
| 6.8.9   | 2        | 0.65%   |
| 6.4.11  | 2        | 0.65%   |
| 6.3.8   | 2        | 0.65%   |
| 6.2.8   | 2        | 0.65%   |
| 6.2.6   | 2        | 0.65%   |
| 6.2.11  | 2        | 0.65%   |
| 6.12.1  | 2        | 0.65%   |
| 6.11.4  | 2        | 0.65%   |
| 6.10.0  | 2        | 0.65%   |
| 6.0.6   | 2        | 0.65%   |
| 5.8.14  | 2        | 0.65%   |
| 5.18.10 | 2        | 0.65%   |
| 5.17.6  | 2        | 0.65%   |
| 5.16.15 | 2        | 0.65%   |
| 5.16.11 | 2        | 0.65%   |
| 5.15.6  | 2        | 0.65%   |
| 5.15.12 | 2        | 0.65%   |
| 5.13.13 | 2        | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 40       | 13.33%  |
| 5.15    | 26       | 8.67%   |
| 5.10    | 19       | 6.33%   |
| 5.8     | 15       | 5%      |
| 6.8     | 14       | 4.67%   |
| 6.2     | 14       | 4.67%   |
| 5.11    | 13       | 4.33%   |
| 4.15    | 11       | 3.67%   |
| 5.16    | 10       | 3.33%   |
| 5.13    | 10       | 3.33%   |
| 6.5     | 9        | 3%      |
| 6.1     | 9        | 3%      |
| 5.19    | 9        | 3%      |
| 5.17    | 9        | 3%      |
| 6.10    | 8        | 2.67%   |
| 5.3     | 8        | 2.67%   |
| 4.18    | 8        | 2.67%   |
| 6.0     | 7        | 2.33%   |
| 5.0     | 7        | 2.33%   |
| 6.4     | 6        | 2%      |
| 6.6     | 5        | 1.67%   |
| 6.11    | 5        | 1.67%   |
| 5.12    | 5        | 1.67%   |
| 6.3     | 4        | 1.33%   |
| 6.9     | 3        | 1%      |
| 6.12    | 3        | 1%      |
| 5.7     | 3        | 1%      |
| 5.6     | 3        | 1%      |
| 5.18    | 3        | 1%      |
| 4.9     | 3        | 1%      |
| 4.19    | 2        | 0.67%   |
| 4.10    | 2        | 0.67%   |
| 6.7     | 1        | 0.33%   |
| 5.9     | 1        | 0.33%   |
| 5.5     | 1        | 0.33%   |
| 5.14    | 1        | 0.33%   |
| 4.4     | 1        | 0.33%   |
| 4.20    | 1        | 0.33%   |
| 4.1     | 1        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 244      | 98.39%  |
| i686   | 4        | 1.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 94       | 35.61%  |
| KDE5            | 54       | 20.45%  |
| Unknown         | 34       | 12.88%  |
| XFCE            | 30       | 11.36%  |
| X-Cinnamon      | 14       | 5.3%    |
| MATE            | 8        | 3.03%   |
| KDE6            | 7        | 2.65%   |
| KDE             | 7        | 2.65%   |
| KDE4            | 5        | 1.89%   |
| LXQt            | 3        | 1.14%   |
| Pantheon        | 2        | 0.76%   |
| LXDE            | 1        | 0.38%   |
| LeftWM          | 1        | 0.38%   |
| Hyprland        | 1        | 0.38%   |
| GNOME Flashback | 1        | 0.38%   |
| Cinnamon        | 1        | 0.38%   |
| Budgie          | 1        | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 184      | 72.73%  |
| Wayland | 46       | 18.18%  |
| Unknown | 18       | 7.11%   |
| Tty     | 5        | 1.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 122      | 46.21%  |
| SDDM    | 57       | 21.59%  |
| LightDM | 27       | 10.23%  |
| GDM     | 26       | 9.85%   |
| GDM3    | 20       | 7.58%   |
| TDM     | 5        | 1.89%   |
| KDM     | 5        | 1.89%   |
| MDM     | 1        | 0.38%   |
| LXDM    | 1        | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_IE   | 118      | 45.21%  |
| en_GB   | 56       | 21.46%  |
| en_US   | 44       | 16.86%  |
| Unknown | 28       | 10.73%  |
| C       | 5        | 1.92%   |
| pl_PL   | 2        | 0.77%   |
| es_ES   | 2        | 0.77%   |
| pt_BR   | 1        | 0.38%   |
| lt_LT   | 1        | 0.38%   |
| hu_HU   | 1        | 0.38%   |
| en_BW   | 1        | 0.38%   |
| de_DE   | 1        | 0.38%   |
| C.UTF8  | 1        | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 151      | 59.68%  |
| EFI  | 102      | 40.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 180      | 69.77%  |
| Btrfs   | 35       | 13.57%  |
| Overlay | 18       | 6.98%   |
| Tmpfs   | 9        | 3.49%   |
| Unknown | 7        | 2.71%   |
| Xfs     | 6        | 2.33%   |
| Zfs     | 2        | 0.78%   |
| Fake    | 1        | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 118      | 45.04%  |
| GPT     | 115      | 43.89%  |
| MBR     | 29       | 11.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 195      | 76.77%  |
| Yes       | 59       | 23.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 66.8%   |
| Yes       | 85       | 33.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 52       | 21.14%  |
| Dell                                 | 48       | 19.51%  |
| Gigabyte Technology                  | 38       | 15.45%  |
| MSI                                  | 24       | 9.76%   |
| Hewlett-Packard                      | 21       | 8.54%   |
| ASRock                               | 19       | 7.72%   |
| Lenovo                               | 14       | 5.69%   |
| Foxconn                              | 6        | 2.44%   |
| Intel                                | 3        | 1.22%   |
| Shuttle                              | 2        | 0.81%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.81%   |
| Seco                                 | 2        | 0.81%   |
| Pegatron                             | 2        | 0.81%   |
| Apple                                | 2        | 0.81%   |
| Unknown                              | 2        | 0.81%   |
| Packard Bell                         | 1        | 0.41%   |
| MiTAC                                | 1        | 0.41%   |
| Medion                               | 1        | 0.41%   |
| Fujitsu                              | 1        | 0.41%   |
| DFI                                  | 1        | 0.41%   |
| AZW                                  | 1        | 0.41%   |
| ANGXUN                               | 1        | 0.41%   |
| Alienware                            | 1        | 0.41%   |
| ABIT                                 | 1        | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex 7010                         | 8        | 3.25%   |
| ASUS All Series                            | 8        | 3.25%   |
| Gigabyte B450M DS3H                        | 5        | 2.03%   |
| Dell OptiPlex 790                          | 4        | 1.63%   |
| Dell OptiPlex 780                          | 4        | 1.63%   |
| Lenovo ThinkCentre E73 10DS000TUK          | 3        | 1.22%   |
| HP Compaq 8200 Elite SFF PC                | 3        | 1.22%   |
| Dell OptiPlex 7020                         | 3        | 1.22%   |
| ASUS TUF Gaming X570-PLUS                  | 3        | 1.22%   |
| ASUS ROG STRIX B450-F GAMING               | 3        | 1.22%   |
| Shenzhen Meigao Electronic Equipment UM690 | 2        | 0.81%   |
| Seco C40                                   | 2        | 0.81%   |
| MSI Pro 3515 Series                        | 2        | 0.81%   |
| MSI MS-7C37                                | 2        | 0.81%   |
| MSI MS-7B86                                | 2        | 0.81%   |
| MSI MS-7B79                                | 2        | 0.81%   |
| Lenovo ThinkStation D20 415892G            | 2        | 0.81%   |
| HP EliteDesk 800 G1 SFF                    | 2        | 0.81%   |
| Gigabyte Z77-DS3H                          | 2        | 0.81%   |
| Gigabyte X570 AORUS ULTRA                  | 2        | 0.81%   |
| Gigabyte B450 AORUS M                      | 2        | 0.81%   |
| Gigabyte A320M-S2H                         | 2        | 0.81%   |
| Foxconn Pro 3500 Series                    | 2        | 0.81%   |
| ASUS ROG CROSSHAIR VIII HERO               | 2        | 0.81%   |
| ASUS PRIME B550M-A                         | 2        | 0.81%   |
| ASUS P8P67 PRO                             | 2        | 0.81%   |
| ASUS P8H77-M PRO                           | 2        | 0.81%   |
| ASUS M5A78L/USB3                           | 2        | 0.81%   |
| Unknown                                    | 2        | 0.81%   |
| Shuttle XS35V4                             | 1        | 0.41%   |
| Shuttle XS35V3                             | 1        | 0.41%   |
| Pegatron s5747c                            | 1        | 0.41%   |
| Pegatron Pro 3010 Microtower PC            | 1        | 0.41%   |
| Packard Bell Vegas2                        | 1        | 0.41%   |
| MSI MS-7E27                                | 1        | 0.41%   |
| MSI MS-7E26                                | 1        | 0.41%   |
| MSI MS-7D78                                | 1        | 0.41%   |
| MSI MS-7C94                                | 1        | 0.41%   |
| MSI MS-7C84                                | 1        | 0.41%   |
| MSI MS-7C77                                | 1        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 28       | 11.38%  |
| Lenovo ThinkCentre                         | 11       | 4.47%   |
| ASUS PRIME                                 | 10       | 4.07%   |
| ASUS TUF                                   | 8        | 3.25%   |
| ASUS All                                   | 8        | 3.25%   |
| HP Compaq                                  | 7        | 2.85%   |
| Dell Precision                             | 7        | 2.85%   |
| Gigabyte B450M                             | 5        | 2.03%   |
| ASUS ROG                                   | 5        | 2.03%   |
| HP EliteDesk                               | 4        | 1.63%   |
| Foxconn Pro                                | 4        | 1.63%   |
| Gigabyte B450                              | 3        | 1.22%   |
| Dell Vostro                                | 3        | 1.22%   |
| Shenzhen Meigao Electronic Equipment UM690 | 2        | 0.81%   |
| Seco C40                                   | 2        | 0.81%   |
| MSI Pro                                    | 2        | 0.81%   |
| MSI MS-7C37                                | 2        | 0.81%   |
| MSI MS-7B86                                | 2        | 0.81%   |
| MSI MS-7B79                                | 2        | 0.81%   |
| Lenovo ThinkStation                        | 2        | 0.81%   |
| Intel DESKTOP                              | 2        | 0.81%   |
| Gigabyte Z77-DS3H                          | 2        | 0.81%   |
| Gigabyte X570                              | 2        | 0.81%   |
| Gigabyte TRX40                             | 2        | 0.81%   |
| Gigabyte A320M-S2H                         | 2        | 0.81%   |
| Dell XPS                                   | 2        | 0.81%   |
| Dell Inspiron                              | 2        | 0.81%   |
| ASUS P8P67                                 | 2        | 0.81%   |
| ASUS P8H77-M                               | 2        | 0.81%   |
| ASUS Maximus                               | 2        | 0.81%   |
| ASUS M5A78L                                | 2        | 0.81%   |
| ASUS Crosshair                             | 2        | 0.81%   |
| ASRock Z77                                 | 2        | 0.81%   |
| Unknown                                    | 2        | 0.81%   |
| Shuttle XS35V4                             | 1        | 0.41%   |
| Shuttle XS35V3                             | 1        | 0.41%   |
| Pegatron s5747c                            | 1        | 0.41%   |
| Pegatron Pro                               | 1        | 0.41%   |
| Packard Bell Vegas2                        | 1        | 0.41%   |
| MSI MS-7E27                                | 1        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 29       | 11.79%  |
| 2018    | 27       | 10.98%  |
| 2012    | 26       | 10.57%  |
| 2011    | 22       | 8.94%   |
| 2010    | 21       | 8.54%   |
| 2020    | 16       | 6.5%    |
| 2019    | 16       | 6.5%    |
| 2017    | 13       | 5.28%   |
| 2014    | 12       | 4.88%   |
| 2015    | 11       | 4.47%   |
| 2008    | 11       | 4.47%   |
| 2023    | 8        | 3.25%   |
| 2022    | 7        | 2.85%   |
| 2009    | 6        | 2.44%   |
| 2006    | 6        | 2.44%   |
| 2021    | 4        | 1.63%   |
| 2007    | 4        | 1.63%   |
| 2024    | 3        | 1.22%   |
| 2005    | 2        | 0.81%   |
| 2016    | 1        | 0.41%   |
| Unknown | 1        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 246      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 240      | 97.56%  |
| Enabled  | 6        | 2.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 246      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 60       | 23.81%  |
| 8.01-16.0       | 55       | 21.83%  |
| 32.01-64.0      | 40       | 15.87%  |
| 3.01-4.0        | 36       | 14.29%  |
| 4.01-8.0        | 28       | 11.11%  |
| 64.01-256.0     | 17       | 6.75%   |
| 24.01-32.0      | 11       | 4.37%   |
| 1.01-2.0        | 3        | 1.19%   |
| More than 256.0 | 1        | 0.4%    |
| 0.51-1.0        | 1        | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 96       | 33.57%  |
| 2.01-3.0   | 60       | 20.98%  |
| 4.01-8.0   | 50       | 17.48%  |
| 3.01-4.0   | 44       | 15.38%  |
| 8.01-16.0  | 17       | 5.94%   |
| 0.51-1.0   | 16       | 5.59%   |
| 32.01-64.0 | 1        | 0.35%   |
| 0.01-0.5   | 1        | 0.35%   |
| Unknown    | 1        | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 32.1%   |
| 2      | 71       | 26.2%   |
| 3      | 42       | 15.5%   |
| 4      | 34       | 12.55%  |
| 5      | 15       | 5.54%   |
| 7      | 6        | 2.21%   |
| 6      | 6        | 2.21%   |
| 0      | 4        | 1.48%   |
| 10     | 3        | 1.11%   |
| 11     | 1        | 0.37%   |
| 9      | 1        | 0.37%   |
| 8      | 1        | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 133      | 52.16%  |
| Yes       | 122      | 47.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 242      | 98.37%  |
| No        | 4        | 1.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 142      | 55.25%  |
| No        | 115      | 44.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 154      | 60.39%  |
| Yes       | 101      | 39.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ireland | 246      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Dublin       | 141      | 53.61%  |
| Cork         | 14       | 5.32%   |
| Limerick     | 8        | 3.04%   |
| Kenmare      | 5        | 1.9%    |
| Sligo        | 4        | 1.52%   |
| Gorey        | 4        | 1.52%   |
| Ennis        | 4        | 1.52%   |
| Tuam         | 3        | 1.14%   |
| Portlaoise   | 3        | 1.14%   |
| Nenagh       | 3        | 1.14%   |
| Naas         | 3        | 1.14%   |
| Enniscorthy  | 3        | 1.14%   |
| Athlone      | 3        | 1.14%   |
| Wexford      | 2        | 0.76%   |
| Swords       | 2        | 0.76%   |
| Oranmore     | 2        | 0.76%   |
| Navan        | 2        | 0.76%   |
| Kilkelly     | 2        | 0.76%   |
| Kildare      | 2        | 0.76%   |
| Galway       | 2        | 0.76%   |
| Drogheda     | 2        | 0.76%   |
| Cavan        | 2        | 0.76%   |
| Blackrock    | 2        | 0.76%   |
| Ballincollig | 2        | 0.76%   |
| Waterford    | 1        | 0.38%   |
| Tullamore    | 1        | 0.38%   |
| Tralee       | 1        | 0.38%   |
| Tobercurry   | 1        | 0.38%   |
| Tipperary    | 1        | 0.38%   |
| Summerhill   | 1        | 0.38%   |
| Shanagolden  | 1        | 0.38%   |
| Roscrea      | 1        | 0.38%   |
| Roscommon    | 1        | 0.38%   |
| Rathangan    | 1        | 0.38%   |
| Moyne        | 1        | 0.38%   |
| Maynooth     | 1        | 0.38%   |
| Mallow       | 1        | 0.38%   |
| Lucan        | 1        | 0.38%   |
| Loughrea     | 1        | 0.38%   |
| Listowel     | 1        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 92       | 192    | 18.7%   |
| Seagate                      | 92       | 171    | 18.7%   |
| Samsung Electronics          | 67       | 120    | 13.62%  |
| Crucial                      | 30       | 36     | 6.1%    |
| Toshiba                      | 23       | 36     | 4.67%   |
| Hitachi                      | 22       | 33     | 4.47%   |
| SanDisk                      | 20       | 35     | 4.07%   |
| Kingston                     | 18       | 39     | 3.66%   |
| China                        | 10       | 12     | 2.03%   |
| A-DATA Technology            | 10       | 17     | 2.03%   |
| Micron/Crucial Technology    | 8        | 14     | 1.63%   |
| Intel                        | 7        | 8      | 1.42%   |
| Phison                       | 6        | 11     | 1.22%   |
| Micron Technology            | 5        | 6      | 1.02%   |
| ADATA Technology             | 5        | 6      | 1.02%   |
| Verbatim                     | 4        | 4      | 0.81%   |
| OCZ                          | 4        | 4      | 0.81%   |
| HGST                         | 4        | 4      | 0.81%   |
| Transcend                    | 3        | 3      | 0.61%   |
| Silicon Motion               | 3        | 12     | 0.61%   |
| Phison Electronics           | 3        | 5      | 0.61%   |
| Netac                        | 3        | 3      | 0.61%   |
| Kingston Technology Company  | 3        | 3      | 0.61%   |
| Team                         | 2        | 2      | 0.41%   |
| Patriot                      | 2        | 3      | 0.41%   |
| Maxtor                       | 2        | 2      | 0.41%   |
| LITEON                       | 2        | 2      | 0.41%   |
| KIOXIA                       | 2        | 4      | 0.41%   |
| JMicron Technology           | 2        | 2      | 0.41%   |
| Hewlett-Packard              | 2        | 4      | 0.41%   |
| Emtec                        | 2        | 2      | 0.41%   |
| Unknown                      | 2        | 2      | 0.41%   |
| Western Digital              | 1        | 2      | 0.2%    |
| WDS100T1                     | 1        | 1      | 0.2%    |
| USB3.0                       | 1        | 1      | 0.2%    |
| Unknown                      | 1        | 1      | 0.2%    |
| Union Memory (Shenzhen)      | 1        | 1      | 0.2%    |
| Union Memory                 | 1        | 1      | 0.2%    |
| SK hynix                     | 1        | 1      | 0.2%    |
| Shenzhen Longsys Electronics | 1        | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 8        | 1.37%   |
| Seagate ST2000DL003-9VT166 2TB                        | 7        | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB                        | 7        | 1.2%    |
| Crucial CT500MX500SSD1 500GB                          | 7        | 1.2%    |
| Seagate ST8000DM004-2CX188 8TB                        | 6        | 1.03%   |
| WDC WD10EURX-83UY4Y0 1TB                              | 5        | 0.86%   |
| WDC WD10EALX-009BA0 1TB                               | 5        | 0.86%   |
| Kingston SA400S37240G 240GB SSD                       | 5        | 0.86%   |
| WDC WD3200AAJS-60Z0A0 320GB                           | 4        | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 4        | 0.69%   |
| Verbatim Vi550 S3 SSD 512GB                           | 4        | 0.69%   |
| Seagate ST3500312CS 500GB                             | 4        | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB                        | 4        | 0.69%   |
| Seagate ST2000DM006-2DM164 2TB                        | 4        | 0.69%   |
| Samsung SSD 870 EVO 1TB                               | 4        | 0.69%   |
| Samsung SSD 850 EVO 500GB                             | 4        | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 4        | 0.69%   |
| Crucial CT1000MX500SSD1 1TB                           | 4        | 0.69%   |
| A-DATA SU650 240GB SSD                                | 4        | 0.69%   |
| WDC WD5000AZLX-08K2TA0 500GB                          | 3        | 0.51%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 3        | 0.51%   |
| WDC WD20EZRX-00D8PB0 2TB                              | 3        | 0.51%   |
| Toshiba HDWD110 1TB                                   | 3        | 0.51%   |
| Toshiba DT01ACA100 1TB                                | 3        | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3        | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB                        | 3        | 0.51%   |
| Seagate ST3500418AS 500GB                             | 3        | 0.51%   |
| Seagate ST3160812AS 160GB                             | 3        | 0.51%   |
| Seagate ST31000528AS 1TB                              | 3        | 0.51%   |
| Seagate ST3000DM001-1CH166 3TB                        | 3        | 0.51%   |
| Seagate Expansion Desk 5TB                            | 3        | 0.51%   |
| SanDisk SSD PLUS 480GB                                | 3        | 0.51%   |
| SanDisk NVMe SSD Drive 500GB                          | 3        | 0.51%   |
| Samsung SSD 980 1TB                                   | 3        | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB                        | 3        | 0.51%   |
| Samsung SSD 860 EVO 500GB                             | 3        | 0.51%   |
| Samsung SSD 840 EVO 250GB                             | 3        | 0.51%   |
| Phison Sabrent 1TB                                    | 3        | 0.51%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 3        | 0.51%   |
| Kingston SV300S37A120G 120GB SSD                      | 3        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 91       | 169    | 37.6%   |
| WDC                 | 84       | 180    | 34.71%  |
| Hitachi             | 22       | 33     | 9.09%   |
| Toshiba             | 20       | 32     | 8.26%   |
| Samsung Electronics | 9        | 13     | 3.72%   |
| HGST                | 4        | 4      | 1.65%   |
| Maxtor              | 2        | 2      | 0.83%   |
| Unknown             | 1        | 1      | 0.41%   |
| SABRENT             | 1        | 1      | 0.41%   |
| QNAP                | 1        | 17     | 0.41%   |
| KESU                | 1        | 1      | 0.41%   |
| Inateck             | 1        | 1      | 0.41%   |
| Fujitsu             | 1        | 3      | 0.41%   |
| FNK TECH            | 1        | 1      | 0.41%   |
| ExcelStor           | 1        | 2      | 0.41%   |
| DAS                 | 1        | 4      | 0.41%   |
| ASMT                | 1        | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 38       | 68     | 22.89%  |
| Crucial             | 27       | 33     | 16.27%  |
| Kingston            | 16       | 35     | 9.64%   |
| SanDisk             | 14       | 19     | 8.43%   |
| China               | 10       | 12     | 6.02%   |
| A-DATA Technology   | 8        | 14     | 4.82%   |
| WDC                 | 5        | 8      | 3.01%   |
| Intel               | 5        | 5      | 3.01%   |
| Verbatim            | 4        | 4      | 2.41%   |
| OCZ                 | 4        | 4      | 2.41%   |
| Transcend           | 3        | 3      | 1.81%   |
| Netac               | 3        | 3      | 1.81%   |
| Micron Technology   | 3        | 4      | 1.81%   |
| Team                | 2        | 2      | 1.2%    |
| Patriot             | 2        | 3      | 1.2%    |
| LITEON              | 2        | 2      | 1.2%    |
| Hewlett-Packard     | 2        | 4      | 1.2%    |
| Emtec               | 2        | 2      | 1.2%    |
| Unknown             | 2        | 2      | 1.2%    |
| USB3.0              | 1        | 1      | 0.6%    |
| Toshiba             | 1        | 1      | 0.6%    |
| SK hynix            | 1        | 1      | 0.6%    |
| PNY                 | 1        | 1      | 0.6%    |
| Palit               | 1        | 1      | 0.6%    |
| Lexar               | 1        | 1      | 0.6%    |
| KingSpec            | 1        | 1      | 0.6%    |
| KingDian            | 1        | 1      | 0.6%    |
| Integral            | 1        | 1      | 0.6%    |
| Hikvision           | 1        | 1      | 0.6%    |
| Fanxiang            | 1        | 1      | 0.6%    |
| DRVEO               | 1        | 1      | 0.6%    |
| Corsair             | 1        | 2      | 0.6%    |
| Apple               | 1        | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 172      | 465    | 43.88%  |
| SSD     | 139      | 242    | 35.46%  |
| NVMe    | 73       | 138    | 18.62%  |
| Unknown | 8        | 8      | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 221      | 685    | 69.72%  |
| NVMe | 73       | 138    | 23.03%  |
| SAS  | 23       | 30     | 7.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 159      | 337    | 45.04%  |
| 0.51-1.0   | 104      | 196    | 29.46%  |
| 1.01-2.0   | 46       | 72     | 13.03%  |
| 3.01-4.0   | 18       | 42     | 5.1%    |
| 4.01-10.0  | 13       | 37     | 3.68%   |
| 2.01-3.0   | 10       | 17     | 2.83%   |
| 10.01-20.0 | 3        | 6      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 54       | 19.29%  |
| 501-1000       | 48       | 17.14%  |
| 251-500        | 42       | 15%     |
| More than 3000 | 41       | 14.64%  |
| 1001-2000      | 29       | 10.36%  |
| 2001-3000      | 18       | 6.43%   |
| 51-100         | 16       | 5.71%   |
| 1-20           | 13       | 4.64%   |
| Unknown        | 11       | 3.93%   |
| 21-50          | 8        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 86       | 29.66%  |
| 21-50          | 33       | 11.38%  |
| 101-250        | 33       | 11.38%  |
| 501-1000       | 33       | 11.38%  |
| 51-100         | 33       | 11.38%  |
| More than 3000 | 23       | 7.93%   |
| 251-500        | 14       | 4.83%   |
| 1001-2000      | 13       | 4.48%   |
| 2001-3000      | 11       | 3.79%   |
| Unknown        | 11       | 3.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                  | 5        | 11     | 8.77%   |
| Seagate ST2000DL003-9VT166 2TB           | 5        | 8      | 8.77%   |
| WDC WD3200AVJS-63B6A0 320GB              | 2        | 2      | 3.51%   |
| WDC WD2500AAKX-753CA1 250GB              | 2        | 5      | 3.51%   |
| Hitachi HDS721010CLA330 1TB              | 2        | 2      | 3.51%   |
| Western Digital SN730 500GB              | 1        | 2      | 1.75%   |
| WDC WD7500BPKX-00HPJT0 752GB             | 1        | 1      | 1.75%   |
| WDC WD5000HHTZ-04N21V0 500GB             | 1        | 3      | 1.75%   |
| WDC WD5000BEVT-35A0RT0 500GB             | 1        | 1      | 1.75%   |
| WDC WD5000AAKX-001CA0 500GB              | 1        | 2      | 1.75%   |
| WDC WD400JB-00FMA0 40GB                  | 1        | 2      | 1.75%   |
| WDC WD2500BEKT-75A25T0 250GB             | 1        | 1      | 1.75%   |
| WDC WD2500AAKX-603CA0 250GB              | 1        | 1      | 1.75%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1        | 2      | 1.75%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1        | 1      | 1.75%   |
| WDC WD1001FALS-00E8B0 1TB                | 1        | 2      | 1.75%   |
| Toshiba MK1059GSM 1TB                    | 1        | 1      | 1.75%   |
| Toshiba DT01ACA050 500GB                 | 1        | 3      | 1.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1        | 1      | 1.75%   |
| Seagate ST4000DX001-1CE168 4TB           | 1        | 1      | 1.75%   |
| Seagate ST3500418AS 500GB                | 1        | 3      | 1.75%   |
| Seagate ST320LT009-9WC142 320GB          | 1        | 1      | 1.75%   |
| Seagate ST31500541AS 1TB                 | 1        | 1      | 1.75%   |
| Seagate ST3120026A 120GB                 | 1        | 1      | 1.75%   |
| Seagate ST31000333AS 1TB                 | 1        | 2      | 1.75%   |
| Seagate ST3000DM001-1ER166 3TB           | 1        | 1      | 1.75%   |
| Seagate ST3000DM001-1CH166 3TB           | 1        | 1      | 1.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1        | 1      | 1.75%   |
| Seagate ST1000DM003-1CH162 1TB           | 1        | 1      | 1.75%   |
| SanDisk SSD PLUS 480GB                   | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 970 EVO Plus 2TB | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 870 EVO 2TB      | 1        | 1      | 1.75%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 1.75%   |
| Netac SSD 128GB                          | 1        | 1      | 1.75%   |
| Micron Technology 2300 NVMe 512GB        | 1        | 1      | 1.75%   |
| Maxtor STM3250310AS 250GB                | 1        | 1      | 1.75%   |
| Intel SSDSA2M080G2GC 80GB                | 1        | 1      | 1.75%   |
| Inateck ASM1153E 12TB                    | 1        | 1      | 1.75%   |
| Hitachi HUS724030ALA640 3TB              | 1        | 2      | 1.75%   |
| Hitachi HDT721016SLA380 160GB            | 1        | 2      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 34     | 29.63%  |
| Seagate             | 16       | 22     | 29.63%  |
| Hitachi             | 5        | 7      | 9.26%   |
| Samsung Electronics | 3        | 3      | 5.56%   |
| Toshiba             | 2        | 4      | 3.7%    |
| Western Digital     | 1        | 2      | 1.85%   |
| SanDisk             | 1        | 1      | 1.85%   |
| Netac               | 1        | 1      | 1.85%   |
| Micron Technology   | 1        | 1      | 1.85%   |
| Maxtor              | 1        | 1      | 1.85%   |
| Intel               | 1        | 1      | 1.85%   |
| Inateck             | 1        | 1      | 1.85%   |
| HGST                | 1        | 1      | 1.85%   |
| DRVEO               | 1        | 1      | 1.85%   |
| China               | 1        | 1      | 1.85%   |
| ADATA Technology    | 1        | 1      | 1.85%   |
| A-DATA Technology   | 1        | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 34     | 37.21%  |
| Seagate             | 16       | 22     | 37.21%  |
| Hitachi             | 5        | 7      | 11.63%  |
| Toshiba             | 2        | 4      | 4.65%   |
| Samsung Electronics | 1        | 1      | 2.33%   |
| Maxtor              | 1        | 1      | 2.33%   |
| Inateck             | 1        | 1      | 2.33%   |
| HGST                | 1        | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 32       | 71     | 74.42%  |
| SSD  | 7        | 7      | 16.28%  |
| NVMe | 4        | 5      | 9.3%    |

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
| Detected | 134      | 416    | 45.42%  |
| Works    | 119      | 354    | 40.34%  |
| Malfunc  | 42       | 83     | 14.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 147      | 40.38%  |
| AMD                          | 88       | 24.18%  |
| Samsung Electronics          | 29       | 7.97%   |
| Marvell Technology Group     | 12       | 3.3%    |
| ASMedia Technology           | 12       | 3.3%    |
| SanDisk                      | 11       | 3.02%   |
| Micron/Crucial Technology    | 11       | 3.02%   |
| Phison Electronics           | 9        | 2.47%   |
| JMicron Technology           | 7        | 1.92%   |
| Nvidia                       | 6        | 1.65%   |
| Kingston Technology Company  | 5        | 1.37%   |
| ADATA Technology             | 5        | 1.37%   |
| LSI Logic / Symbios Logic    | 4        | 1.1%    |
| Toshiba America Info Systems | 3        | 0.82%   |
| Silicon Motion               | 3        | 0.82%   |
| Union Memory (Shenzhen)      | 2        | 0.55%   |
| Realtek Semiconductor        | 2        | 0.55%   |
| Micron Technology            | 2        | 0.55%   |
| KIOXIA                       | 2        | 0.55%   |
| ULi Electronics              | 1        | 0.27%   |
| Shenzhen Longsys Electronics | 1        | 0.27%   |
| Seagate Technology           | 1        | 0.27%   |
| Broadcom / LSI               | 1        | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 51       | 11.02%  |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 21       | 4.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 20       | 4.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19       | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 19       | 4.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12       | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 2.59%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 10       | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 1.94%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 1.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 1.73%   |
| AMD 600 Series Chipset SATA Controller                                                  | 8        | 1.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 1.51%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 1.51%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 1.51%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6        | 1.3%    |
| Phison E12 NVMe Controller                                                              | 6        | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.3%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.08%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 1.08%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 5        | 1.08%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 4        | 0.86%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.86%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 0.86%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 4        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 4        | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.65%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 3        | 0.65%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 201      | 56.78%  |
| NVMe | 73       | 20.62%  |
| IDE  | 60       | 16.95%  |
| RAID | 17       | 4.8%    |
| SCSI | 3        | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 149      | 60.57%  |
| AMD    | 96       | 39.02%  |
| iSH    | 1        | 0.41%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz               | 9        | 3.6%    |
| Intel Core i7-2600K CPU @ 3.40GHz              | 8        | 3.2%    |
| AMD Ryzen 5 3600 6-Core Processor              | 8        | 3.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz               | 6        | 2.4%    |
| Intel Core i7-3770K CPU @ 3.50GHz              | 4        | 1.6%    |
| Intel Core i5-2400 CPU @ 3.10GHz               | 4        | 1.6%    |
| Intel Core i3-2100 CPU @ 3.10GHz               | 4        | 1.6%    |
| AMD Ryzen 9 3900X 12-Core Processor            | 4        | 1.6%    |
| AMD Ryzen 5 2600X Six-Core Processor           | 4        | 1.6%    |
| Intel Pentium 4 CPU 3.00GHz                    | 3        | 1.2%    |
| Intel Core i7-2600 CPU @ 3.40GHz               | 3        | 1.2%    |
| Intel Core i5-4570 CPU @ 3.20GHz               | 3        | 1.2%    |
| Intel Core i5-4460S CPU @ 2.90GHz              | 3        | 1.2%    |
| Intel Core i3-4150 CPU @ 3.50GHz               | 3        | 1.2%    |
| Intel Core i3-3220 CPU @ 3.30GHz               | 3        | 1.2%    |
| Intel Core i3-2120 CPU @ 3.30GHz               | 3        | 1.2%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3        | 1.2%    |
| AMD Ryzen 9 5900X 12-Core Processor            | 3        | 1.2%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 3        | 1.2%    |
| AMD Ryzen 5 2600 Six-Core Processor            | 3        | 1.2%    |
| AMD Athlon II X4 620 Processor                 | 3        | 1.2%    |
| Intel Xeon CPU X5690 @ 3.47GHz                 | 2        | 0.8%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 2        | 0.8%    |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 0.8%    |
| Intel Core i7-4790K CPU @ 4.00GHz              | 2        | 0.8%    |
| Intel Core i7-4770K CPU @ 3.50GHz              | 2        | 0.8%    |
| Intel Core i5-8500T CPU @ 2.10GHz              | 2        | 0.8%    |
| Intel Core i5-6500T CPU @ 2.50GHz              | 2        | 0.8%    |
| Intel Core i5-4690K CPU @ 3.50GHz              | 2        | 0.8%    |
| Intel Core i5-4670K CPU @ 3.40GHz              | 2        | 0.8%    |
| Intel Core i5-4670 CPU @ 3.40GHz               | 2        | 0.8%    |
| Intel Core i5-4590 CPU @ 3.30GHz               | 2        | 0.8%    |
| Intel Core i5-3570 CPU @ 3.40GHz               | 2        | 0.8%    |
| Intel Core i5-2500 CPU @ 3.30GHz               | 2        | 0.8%    |
| Intel Core i5-10500 CPU @ 3.10GHz              | 2        | 0.8%    |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 0.8%    |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz          | 2        | 0.8%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 0.8%    |
| AMD Ryzen Embedded V1605B with Radeon Vega Gfx | 2        | 0.8%    |
| AMD Ryzen 9 6900HX with Radeon Graphics        | 2        | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 46       | 18.4%   |
| Intel Core i7           | 39       | 15.6%   |
| AMD Ryzen 5             | 26       | 10.4%   |
| Intel Core i3           | 23       | 9.2%    |
| AMD Ryzen 9             | 16       | 6.4%    |
| Intel Xeon              | 12       | 4.8%    |
| AMD Ryzen 7             | 11       | 4.4%    |
| Intel Core 2 Quad       | 8        | 3.2%    |
| AMD FX                  | 5        | 2%      |
| AMD Athlon 64 X2        | 5        | 2%      |
| Other                   | 4        | 1.6%    |
| Intel Pentium 4         | 4        | 1.6%    |
| Intel Core 2 Duo        | 4        | 1.6%    |
| Intel Celeron           | 4        | 1.6%    |
| AMD Ryzen Threadripper  | 4        | 1.6%    |
| AMD Ryzen 3             | 4        | 1.6%    |
| Intel Pentium Dual-Core | 3        | 1.2%    |
| AMD Phenom II X4        | 3        | 1.2%    |
| AMD Athlon II X4        | 3        | 1.2%    |
| AMD Athlon II X2        | 3        | 1.2%    |
| AMD A6                  | 3        | 1.2%    |
| Intel Pentium D         | 2        | 0.8%    |
| Intel Pentium           | 2        | 0.8%    |
| Intel Atom              | 2        | 0.8%    |
| AMD Ryzen Embedded      | 2        | 0.8%    |
| AMD Phenom II X6        | 2        | 0.8%    |
| AMD A4                  | 2        | 0.8%    |
| Intel Pentium Silver    | 1        | 0.4%    |
| AMD Turion II Neo       | 1        | 0.4%    |
| AMD Ryzen 5 PRO         | 1        | 0.4%    |
| AMD PRO A10             | 1        | 0.4%    |
| AMD GX                  | 1        | 0.4%    |
| AMD Athlon Dual Core    | 1        | 0.4%    |
| AMD A8                  | 1        | 0.4%    |
| AMD A10                 | 1        | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 110      | 44.35%  |
| 2       | 45       | 18.15%  |
| 6       | 39       | 15.73%  |
| 12      | 17       | 6.85%   |
| 8       | 16       | 6.45%   |
| 1       | 9        | 3.63%   |
| 16      | 5        | 2.02%   |
| 3       | 2        | 0.81%   |
| Unknown | 2        | 0.81%   |
| 32      | 1        | 0.4%    |
| 24      | 1        | 0.4%    |
| 10      | 1        | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 240      | 97.56%  |
| 2       | 5        | 2.03%   |
| Unknown | 1        | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 146      | 58.4%   |
| 1       | 102      | 40.8%   |
| Unknown | 2        | 0.8%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 242      | 98.37%  |
| Unknown        | 4        | 1.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 102      | 39.23%  |
| 0x306a9    | 19       | 7.31%   |
| 0x206a7    | 17       | 6.54%   |
| 0x306c3    | 16       | 6.15%   |
| 0x1067a    | 10       | 3.85%   |
| 0x08701021 | 7        | 2.69%   |
| 0x08108109 | 5        | 1.92%   |
| 0x0800820d | 5        | 1.92%   |
| 0x506e3    | 4        | 1.54%   |
| 0x206c2    | 4        | 1.54%   |
| 0xf43      | 3        | 1.15%   |
| 0xa0653    | 3        | 1.15%   |
| 0x906ea    | 3        | 1.15%   |
| 0x6fb      | 3        | 1.15%   |
| 0x0810100b | 3        | 1.15%   |
| 0x06000852 | 3        | 1.15%   |
| 0x010000db | 3        | 1.15%   |
| 0x010000c8 | 3        | 1.15%   |
| 0x906e9    | 2        | 0.77%   |
| 0x30661    | 2        | 0.77%   |
| 0x106a5    | 2        | 0.77%   |
| 0x0a601206 | 2        | 0.77%   |
| 0x0a601203 | 2        | 0.77%   |
| 0x0a201016 | 2        | 0.77%   |
| 0x08701013 | 2        | 0.77%   |
| 0x0600611a | 2        | 0.77%   |
| 0xf64      | 1        | 0.38%   |
| 0xf47      | 1        | 0.38%   |
| 0xf41      | 1        | 0.38%   |
| 0xa0655    | 1        | 0.38%   |
| 0x906ed    | 1        | 0.38%   |
| 0x906eb    | 1        | 0.38%   |
| 0x906c0    | 1        | 0.38%   |
| 0x706a1    | 1        | 0.38%   |
| 0x6f7      | 1        | 0.38%   |
| 0x406f1    | 1        | 0.38%   |
| 0x306e4    | 1        | 0.38%   |
| 0x30678    | 1        | 0.38%   |
| 0x106e5    | 1        | 0.38%   |
| 0x10677    | 1        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 32       | 12.96%  |
| Haswell          | 27       | 10.93%  |
| SandyBridge      | 24       | 9.72%   |
| Zen 2            | 22       | 8.91%   |
| Zen+             | 15       | 6.07%   |
| Unknown          | 13       | 5.26%   |
| Penryn           | 12       | 4.86%   |
| KabyLake         | 12       | 4.86%   |
| K10              | 12       | 4.86%   |
| Zen 3            | 9        | 3.64%   |
| Zen              | 8        | 3.24%   |
| Piledriver       | 8        | 3.24%   |
| Westmere         | 7        | 2.83%   |
| Skylake          | 7        | 2.83%   |
| NetBurst         | 6        | 2.43%   |
| K8 Hammer        | 6        | 2.43%   |
| Nehalem          | 5        | 2.02%   |
| Core             | 4        | 1.62%   |
| CometLake        | 4        | 1.62%   |
| Goldmont plus    | 2        | 0.81%   |
| Excavator        | 2        | 0.81%   |
| Bonnell          | 2        | 0.81%   |
| Tremont          | 1        | 0.4%    |
| Steamroller      | 1        | 0.4%    |
| Silvermont       | 1        | 0.4%    |
| K10 Llano        | 1        | 0.4%    |
| Jaguar           | 1        | 0.4%    |
| Bulldozer        | 1        | 0.4%    |
| Broadwell        | 1        | 0.4%    |
| Alderlake Hybrid | 1        | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 107      | 39.48%  |
| Nvidia | 94       | 34.69%  |
| Intel  | 70       | 25.83%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 20       | 6.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 3.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10       | 3.47%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 3.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 3.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 8        | 2.78%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 8        | 2.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 2.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.74%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5        | 1.74%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 5        | 1.74%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 1.39%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.39%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.39%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.39%   |
| AMD Raphael                                                                 | 4        | 1.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1.39%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 1.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.04%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 3        | 1.04%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.04%   |
| Nvidia GF119 [GeForce GT 610]                                               | 3        | 1.04%   |
| Intel HD Graphics 630                                                       | 3        | 1.04%   |
| Intel HD Graphics 530                                                       | 3        | 1.04%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.04%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 3        | 1.04%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.04%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 1.04%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.69%   |
| Nvidia GM204GL [Quadro M4000]                                               | 2        | 0.69%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 0.69%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.69%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 0.69%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 0.69%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 2        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 92       | 35.8%   |
| 1 x Nvidia     | 88       | 34.24%  |
| 1 x Intel      | 55       | 21.4%   |
| 2 x AMD        | 10       | 3.89%   |
| Intel + Nvidia | 3        | 1.17%   |
| Intel + AMD    | 3        | 1.17%   |
| AMD + Nvidia   | 3        | 1.17%   |
| Other          | 1        | 0.39%   |
| 2 x Nvidia     | 1        | 0.39%   |
| 2 x Intel      | 1        | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 188      | 74.02%  |
| Proprietary | 51       | 20.08%  |
| Unknown     | 15       | 5.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 111      | 42.21%  |
| 1.01-2.0   | 34       | 12.93%  |
| 0.51-1.0   | 30       | 11.41%  |
| 7.01-8.0   | 26       | 9.89%   |
| 3.01-4.0   | 21       | 7.98%   |
| 0.01-0.5   | 14       | 5.32%   |
| 5.01-6.0   | 12       | 4.56%   |
| 8.01-16.0  | 10       | 3.8%    |
| 16.01-24.0 | 3        | 1.14%   |
| 2.01-3.0   | 2        | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 53       | 19.92%  |
| Samsung Electronics  | 25       | 9.4%    |
| Acer                 | 20       | 7.52%   |
| Hewlett-Packard      | 19       | 7.14%   |
| BenQ                 | 19       | 7.14%   |
| Goldstar             | 15       | 5.64%   |
| AOC                  | 15       | 5.64%   |
| Philips              | 14       | 5.26%   |
| Iiyama               | 11       | 4.14%   |
| Lenovo               | 7        | 2.63%   |
| Ancor Communications | 6        | 2.26%   |
| Sony                 | 5        | 1.88%   |
| ASUSTek Computer     | 5        | 1.88%   |
| ViewSonic            | 4        | 1.5%    |
| Vestel Elektronik    | 3        | 1.13%   |
| Unknown              | 3        | 1.13%   |
| MSI                  | 3        | 1.13%   |
| HKC                  | 3        | 1.13%   |
| HannStar             | 3        | 1.13%   |
| Apple                | 3        | 1.13%   |
| ___                  | 2        | 0.75%   |
| Toshiba              | 2        | 0.75%   |
| NEC Computers        | 2        | 0.75%   |
| MiTAC                | 2        | 0.75%   |
| HannStar Display     | 2        | 0.75%   |
| WIT                  | 1        | 0.38%   |
| UGD                  | 1        | 0.38%   |
| Targa Visionary      | 1        | 0.38%   |
| Targa                | 1        | 0.38%   |
| RTK                  | 1        | 0.38%   |
| Pixio                | 1        | 0.38%   |
| Packard Bell         | 1        | 0.38%   |
| OEM                  | 1        | 0.38%   |
| Medion               | 1        | 0.38%   |
| LG Electronics       | 1        | 0.38%   |
| Idek Iiyama          | 1        | 0.38%   |
| HYO                  | 1        | 0.38%   |
| HVR                  | 1        | 0.38%   |
| HUAWEI               | 1        | 0.38%   |
| Gigabyte Technology  | 1        | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                  | 5        | 1.71%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch               | 5        | 1.71%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 5        | 1.71%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch  | 4        | 1.37%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 3        | 1.03%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 3        | 1.03%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                      | 3        | 1.03%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 3        | 1.03%   |
| ___ LCD TV ___9000 1360x768                                           | 2        | 0.68%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 2        | 0.68%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                   | 2        | 0.68%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2        | 0.68%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch     | 2        | 0.68%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 2        | 0.68%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2        | 0.68%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch          | 2        | 0.68%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch             | 2        | 0.68%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 2        | 0.68%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 2        | 0.68%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 0.68%   |
| Dell S2419HN DELD0D3 1920x1080 527x296mm 23.8-inch                    | 2        | 0.68%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                     | 2        | 0.68%   |
| Dell E171FP DEL300F 1280x1024 338x270mm 17.0-inch                     | 2        | 0.68%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 2        | 0.68%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch               | 2        | 0.68%   |
| ASUSTek Computer VX279 AUS27E4 1920x1080 598x336mm 27.0-inch          | 2        | 0.68%   |
| Apple LED Cinema APP9236 1920x1200 518x324mm 24.1-inch                | 2        | 0.68%   |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                   | 2        | 0.68%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 2        | 0.68%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 2        | 0.68%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                    | 2        | 0.68%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 2        | 0.68%   |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                        | 1        | 0.34%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch         | 1        | 0.34%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 610x360mm 27.9-inch         | 1        | 0.34%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1        | 0.34%   |
| ViewSonic VA1655-FHD VSC313C 1920x1080 344x194mm 15.5-inch            | 1        | 0.34%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.34%   |
| UGD Artist13.3pro UGD1302 1920x1080 294x165mm 13.3-inch               | 1        | 0.34%   |
| Toshiba TV TSB1206 1360x768                                           | 1        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 118      | 46.27%  |
| 2560x1440 (QHD)    | 28       | 10.98%  |
| 3840x2160 (4K)     | 26       | 10.2%   |
| 1280x1024 (SXGA)   | 17       | 6.67%   |
| 3440x1440          | 8        | 3.14%   |
| 1360x768           | 7        | 2.75%   |
| 1920x1200 (WUXGA)  | 6        | 2.35%   |
| 1680x1050 (WSXGA+) | 6        | 2.35%   |
| 1600x900 (HD+)     | 6        | 2.35%   |
| 1440x900 (WXGA+)   | 6        | 2.35%   |
| 1366x768 (WXGA)    | 6        | 2.35%   |
| Unknown            | 6        | 2.35%   |
| 3840x1080          | 4        | 1.57%   |
| 2560x1080          | 2        | 0.78%   |
| 1024x768 (XGA)     | 2        | 0.78%   |
| 6400x2160          | 1        | 0.39%   |
| 5280x2560          | 1        | 0.39%   |
| 4480x1440          | 1        | 0.39%   |
| 3600x1080          | 1        | 0.39%   |
| 2160x1200          | 1        | 0.39%   |
| 1920x540           | 1        | 0.39%   |
| 1600x1200          | 1        | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 46       | 17.76%  |
| 24      | 41       | 15.83%  |
| 23      | 32       | 12.36%  |
| 21      | 28       | 10.81%  |
| Unknown | 19       | 7.34%   |
| 19      | 16       | 6.18%   |
| 34      | 9        | 3.47%   |
| 17      | 9        | 3.47%   |
| 31      | 8        | 3.09%   |
| 84      | 6        | 2.32%   |
| 18      | 6        | 2.32%   |
| 33      | 5        | 1.93%   |
| 32      | 5        | 1.93%   |
| 22      | 5        | 1.93%   |
| 20      | 5        | 1.93%   |
| 72      | 3        | 1.16%   |
| 65      | 3        | 1.16%   |
| 15      | 3        | 1.16%   |
| 49      | 2        | 0.77%   |
| 28      | 2        | 0.77%   |
| 46      | 1        | 0.39%   |
| 39      | 1        | 0.39%   |
| 35      | 1        | 0.39%   |
| 25      | 1        | 0.39%   |
| 13      | 1        | 0.39%   |
| 12      | 1        | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 108      | 42.69%  |
| 401-500     | 53       | 20.95%  |
| 701-800     | 19       | 7.51%   |
| Unknown     | 19       | 7.51%   |
| 601-700     | 15       | 5.93%   |
| 301-350     | 11       | 4.35%   |
| 351-400     | 9        | 3.56%   |
| 1501-2000   | 9        | 3.56%   |
| 1001-1500   | 6        | 2.37%   |
| 201-300     | 2        | 0.79%   |
| 801-900     | 1        | 0.4%    |
| 901-1000    | 1        | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 161      | 69.1%   |
| 16/10   | 24       | 10.3%   |
| 5/4     | 16       | 6.87%   |
| Unknown | 15       | 6.44%   |
| 21/9    | 10       | 4.29%   |
| 4/3     | 5        | 2.15%   |
| 32/9    | 1        | 0.43%   |
| 3/2     | 1        | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 85       | 32.82%  |
| 301-350        | 46       | 17.76%  |
| 351-500        | 29       | 11.2%   |
| 151-200        | 27       | 10.42%  |
| 251-300        | 19       | 7.34%   |
| Unknown        | 19       | 7.34%   |
| 141-150        | 13       | 5.02%   |
| More than 1000 | 12       | 4.63%   |
| 501-1000       | 4        | 1.54%   |
| 101-110        | 3        | 1.16%   |
| 71-80          | 2        | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 146      | 58.63%  |
| 101-120 | 53       | 21.29%  |
| Unknown | 19       | 7.63%   |
| 121-160 | 14       | 5.62%   |
| 1-50    | 11       | 4.42%   |
| 161-240 | 6        | 2.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 190      | 73.08%  |
| 2     | 50       | 19.23%  |
| 0     | 13       | 5%      |
| 3     | 7        | 2.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 140      | 36.08%  |
| Intel                             | 121      | 31.19%  |
| Qualcomm Atheros                  | 19       | 4.9%    |
| TP-Link                           | 18       | 4.64%   |
| Broadcom                          | 16       | 4.12%   |
| Ralink Technology                 | 15       | 3.87%   |
| MediaTek                          | 10       | 2.58%   |
| Ralink                            | 8        | 2.06%   |
| Microsoft                         | 6        | 1.55%   |
| Nvidia                            | 4        | 1.03%   |
| Marvell Technology Group          | 4        | 1.03%   |
| Broadcom Limited                  | 3        | 0.77%   |
| Samsung Electronics               | 2        | 0.52%   |
| Qualcomm Atheros Communications   | 2        | 0.52%   |
| NetGear                           | 2        | 0.52%   |
| Microchip Technology              | 2        | 0.52%   |
| Huawei Technologies               | 2        | 0.52%   |
| Belkin Components                 | 2        | 0.52%   |
| Van Ooijen Technische Informatica | 1        | 0.26%   |
| ULi Electronics                   | 1        | 0.26%   |
| NetXen Incorporated               | 1        | 0.26%   |
| JMicron Technology                | 1        | 0.26%   |
| IMC Networks                      | 1        | 0.26%   |
| HMD Global                        | 1        | 0.26%   |
| DisplayLink                       | 1        | 0.26%   |
| Dexcom                            | 1        | 0.26%   |
| ASUSTek Computer                  | 1        | 0.26%   |
| ASIX Electronics                  | 1        | 0.26%   |
| Aquantia                          | 1        | 0.26%   |
| ADMtek                            | 1        | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 100      | 22.94%  |
| Intel Wi-Fi 6 AX200                                                    | 23       | 5.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23       | 5.28%   |
| Realtek RTL8125 2.5GbE Controller                                      | 17       | 3.9%    |
| Intel I211 Gigabit Network Connection                                  | 14       | 3.21%   |
| Realtek 802.11ac NIC                                                   | 12       | 2.75%   |
| Ralink MT7601U Wireless Adapter                                        | 9        | 2.06%   |
| Intel Ethernet Connection I217-LM                                      | 9        | 2.06%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 8        | 1.83%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 7        | 1.61%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 6        | 1.38%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 5        | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5        | 1.15%   |
| Intel Ethernet Connection (2) I218-V                                   | 5        | 1.15%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 4        | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 0.92%   |
| Ralink RT5370 Wireless Adapter                                         | 4        | 0.92%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 4        | 0.92%   |
| Intel Wireless 7265                                                    | 4        | 0.92%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4        | 0.92%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 0.92%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 4        | 0.92%   |
| TP-Link 802.11ac NIC                                                   | 3        | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3        | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3        | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 3        | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 0.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3        | 0.69%   |
| Intel Ethernet Connection I217-V                                       | 3        | 0.69%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 0.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3        | 0.69%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 3        | 0.69%   |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 0.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 0.46%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 45       | 28.3%   |
| Realtek Semiconductor           | 30       | 18.87%  |
| TP-Link                         | 18       | 11.32%  |
| Qualcomm Atheros                | 16       | 10.06%  |
| Ralink Technology               | 15       | 9.43%   |
| Ralink                          | 8        | 5.03%   |
| Microsoft                       | 6        | 3.77%   |
| MediaTek                        | 6        | 3.77%   |
| Broadcom                        | 5        | 3.14%   |
| Qualcomm Atheros Communications | 2        | 1.26%   |
| NetGear                         | 2        | 1.26%   |
| Belkin Components               | 2        | 1.26%   |
| Marvell Technology Group        | 1        | 0.63%   |
| IMC Networks                    | 1        | 0.63%   |
| Broadcom Limited                | 1        | 0.63%   |
| ASUSTek Computer                | 1        | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 23       | 14.2%   |
| Realtek 802.11ac NIC                                                | 12       | 7.41%   |
| Ralink MT7601U Wireless Adapter                                     | 9        | 5.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]             | 8        | 4.94%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 6        | 3.7%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 5        | 3.09%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 4        | 2.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 4        | 2.47%   |
| Ralink RT5370 Wireless Adapter                                      | 4        | 2.47%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 4        | 2.47%   |
| Intel Wireless 7265                                                 | 4        | 2.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 4        | 2.47%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter        | 4        | 2.47%   |
| TP-Link 802.11ac NIC                                                | 3        | 1.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 3        | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 3        | 1.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 3        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 3        | 1.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 3        | 1.85%   |
| TP-Link 802.11ac WLAN Adapter                                       | 2        | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 2        | 1.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 2        | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 2        | 1.23%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                 | 1        | 0.62%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                               | 1        | 0.62%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                           | 1        | 0.62%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.62%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 1        | 0.62%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.62%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.62%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                          | 1        | 0.62%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 0.62%   |
| Ralink Wireless Adapter Canyon CN-WF511                             | 1        | 0.62%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 0.62%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 1        | 0.62%   |
| Ralink RT5592 PCIe Wireless Network Adapter                         | 1        | 0.62%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 1        | 0.62%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                           | 1        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 123      | 47.86%  |
| Intel                    | 95       | 36.96%  |
| Broadcom                 | 12       | 4.67%   |
| Qualcomm Atheros         | 4        | 1.56%   |
| Nvidia                   | 4        | 1.56%   |
| MediaTek                 | 3        | 1.17%   |
| Marvell Technology Group | 3        | 1.17%   |
| Samsung Electronics      | 2        | 0.78%   |
| Broadcom Limited         | 2        | 0.78%   |
| ULi Electronics          | 1        | 0.39%   |
| NetXen Incorporated      | 1        | 0.39%   |
| JMicron Technology       | 1        | 0.39%   |
| Huawei Technologies      | 1        | 0.39%   |
| HMD Global               | 1        | 0.39%   |
| DisplayLink              | 1        | 0.39%   |
| ASIX Electronics         | 1        | 0.39%   |
| Aquantia                 | 1        | 0.39%   |
| ADMtek                   | 1        | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 100      | 37.31%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 23       | 8.58%   |
| Realtek RTL8125 2.5GbE Controller                                              | 17       | 6.34%   |
| Intel I211 Gigabit Network Connection                                          | 14       | 5.22%   |
| Intel Ethernet Connection I217-LM                                              | 9        | 3.36%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 7        | 2.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5        | 1.87%   |
| Intel Ethernet Connection (2) I218-V                                           | 5        | 1.87%   |
| Intel Ethernet Connection (2) I219-V                                           | 4        | 1.49%   |
| Intel 82579V Gigabit Network Connection                                        | 4        | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3        | 1.12%   |
| Intel Ethernet Connection I217-V                                               | 3        | 1.12%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 1.12%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3        | 1.12%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 3        | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2        | 0.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2        | 0.75%   |
| Nvidia MCP61 Ethernet                                                          | 2        | 0.75%   |
| MediaTek Infinix SMART 5                                                       | 2        | 0.75%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 2        | 0.75%   |
| Intel I210 Gigabit Network Connection                                          | 2        | 0.75%   |
| Intel Ethernet Controller I225-V                                               | 2        | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2        | 0.75%   |
| Intel 82583V Gigabit Network Connection                                        | 2        | 0.75%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 2        | 0.75%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 2        | 0.75%   |
| ULi ULi 1689,1573 integrated ethernet.                                         | 1        | 0.37%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                    | 1        | 0.37%   |
| Realtek Killer E2600 GbE Controller                                            | 1        | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.37%   |
| Nvidia MCP55 Ethernet                                                          | 1        | 0.37%   |
| Nvidia MCP51 Ethernet Controller                                               | 1        | 0.37%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter           | 1        | 0.37%   |
| MediaTek WLAN controller                                                       | 1        | 0.37%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.37%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1        | 0.37%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1        | 0.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 242      | 62.21%  |
| WiFi     | 141      | 36.25%  |
| Modem    | 6        | 1.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 186      | 70.19%  |
| WiFi     | 79       | 29.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 144      | 57.6%   |
| 2     | 83       | 33.2%   |
| 3     | 14       | 5.6%    |
| 0     | 7        | 2.8%    |
| 6     | 1        | 0.4%    |
| 4     | 1        | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 222      | 89.16%  |
| Yes  | 27       | 10.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 41       | 38.68%  |
| Cambridge Silicon Radio         | 22       | 20.75%  |
| Realtek Semiconductor           | 7        | 6.6%    |
| ASUSTek Computer                | 7        | 6.6%    |
| Broadcom                        | 6        | 5.66%   |
| MediaTek                        | 5        | 4.72%   |
| Qualcomm Atheros Communications | 4        | 3.77%   |
| TP-Link                         | 2        | 1.89%   |
| IMC Networks                    | 2        | 1.89%   |
| Belkin Components               | 2        | 1.89%   |
| Apple                           | 2        | 1.89%   |
| SiW                             | 1        | 0.94%   |
| Foxconn / Hon Hai               | 1        | 0.94%   |
| Edimax Technology               | 1        | 0.94%   |
| Dell                            | 1        | 0.94%   |
| Conwise Technology              | 1        | 0.94%   |
| Unknown                         | 1        | 0.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22       | 20.56%  |
| Intel AX200 Bluetooth                               | 21       | 19.63%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7        | 6.54%   |
| Intel Bluetooth wireless interface                  | 7        | 6.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 6        | 5.61%   |
| MediaTek Wireless_Device                            | 5        | 4.67%   |
| Realtek Bluetooth Radio                             | 4        | 3.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 3.74%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4        | 3.74%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2        | 1.87%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 1.87%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2        | 1.87%   |
| Intel AX201 Bluetooth                               | 2        | 1.87%   |
| SiW SiW                                             | 1        | 0.93%   |
| Realtek Bluetooth 5.4 Radio                         | 1        | 0.93%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 0.93%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 0.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 0.93%   |
| IMC Networks Wireless_Device                        | 1        | 0.93%   |
| IMC Networks Bluetooth Radio                        | 1        | 0.93%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 0.93%   |
| Edimax Bluetooth Adapter                            | 1        | 0.93%   |
| Dell BT Mini-Receiver                               | 1        | 0.93%   |
| Conwise CW6622                                      | 1        | 0.93%   |
| Belkin Components F8T012 Bluetooth Adapter          | 1        | 0.93%   |
| Belkin Components Bluetooth Mini Dongle             | 1        | 0.93%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 0.93%   |
| ASUS Bluetooth Device                               | 1        | 0.93%   |
| ASUS BCM20702A0                                     | 1        | 0.93%   |
| Apple Bluetooth Host Controller                     | 1        | 0.93%   |
| Apple Bluetooth HCI                                 | 1        | 0.93%   |
| Unknown                                             | 1        | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 144      | 32.51%  |
| AMD                                             | 135      | 30.47%  |
| Nvidia                                          | 90       | 20.32%  |
| Creative Labs                                   | 8        | 1.81%   |
| C-Media Electronics                             | 7        | 1.58%   |
| Kingston Technology                             | 5        | 1.13%   |
| Plantronics                                     | 4        | 0.9%    |
| Texas Instruments                               | 3        | 0.68%   |
| Logitech                                        | 3        | 0.68%   |
| JMTek                                           | 3        | 0.68%   |
| Focusrite-Novation                              | 3        | 0.68%   |
| Creative Technology                             | 3        | 0.68%   |
| SteelSeries ApS                                 | 2        | 0.45%   |
| Micronas                                        | 2        | 0.45%   |
| GN Netcom                                       | 2        | 0.45%   |
| Giga-Byte Technology                            | 2        | 0.45%   |
| FiiO Electronics Technology                     | 2        | 0.45%   |
| Ensoniq                                         | 2        | 0.45%   |
| Dell                                            | 2        | 0.45%   |
| Blue Microphones                                | 2        | 0.45%   |
| Walmart                                         | 1        | 0.23%   |
| ULi Electronics                                 | 1        | 0.23%   |
| Turtle Beach                                    | 1        | 0.23%   |
| Sony                                            | 1        | 0.23%   |
| SAVITECH                                        | 1        | 0.23%   |
| RODE Microphones                                | 1        | 0.23%   |
| Razer USA                                       | 1        | 0.23%   |
| Native Instruments                              | 1        | 0.23%   |
| M-Audio                                         | 1        | 0.23%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.23%   |
| KTMicro                                         | 1        | 0.23%   |
| Harman International                            | 1        | 0.23%   |
| Generalplus Technology                          | 1        | 0.23%   |
| DEXP BK-20                                      | 1        | 0.23%   |
| Corsair                                         | 1        | 0.23%   |
| BEHRINGER International                         | 1        | 0.23%   |
| AudioQuest                                      | 1        | 0.23%   |
| Audio-Technica                                  | 1        | 0.23%   |
| AOKEO                                           | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 30       | 5.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 29       | 5.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 26       | 4.93%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 22       | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 20       | 3.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 20       | 3.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 17       | 3.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 15       | 2.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 2.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 12       | 2.28%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 10       | 1.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 10       | 1.9%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 9        | 1.71%   |
| Nvidia GP106 High Definition Audio Controller                                     | 9        | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 8        | 1.52%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8        | 1.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 1.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 7        | 1.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 7        | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 1.33%   |
| AMD FCH Azalia Controller                                                         | 7        | 1.33%   |
| Nvidia GM204 High Definition Audio Controller                                     | 6        | 1.14%   |
| Intel 200 Series PCH HD Audio                                                     | 6        | 1.14%   |
| AMD Navi 10 HDMI Audio                                                            | 6        | 1.14%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 6        | 1.14%   |
| Nvidia High Definition Audio Controller                                           | 5        | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5        | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 0.95%   |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 0.95%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 5        | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 0.76%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 0.76%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                                | 4        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 0.57%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 0.57%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 0.57%   |
| Nvidia GA106 High Definition Audio Controller                                     | 3        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 41       | 25.15%  |
| Unknown             | 21       | 12.88%  |
| SK hynix            | 19       | 11.66%  |
| Kingston            | 19       | 11.66%  |
| Crucial             | 17       | 10.43%  |
| Samsung Electronics | 10       | 6.13%   |
| G.Skill             | 9        | 5.52%   |
| Micron Technology   | 8        | 4.91%   |
| Team                | 3        | 1.84%   |
| Ramaxel Technology  | 3        | 1.84%   |
| Patriot             | 3        | 1.84%   |
| A-DATA Technology   | 2        | 1.23%   |
| Toshiba             | 1        | 0.61%   |
| Nanya Technology    | 1        | 0.61%   |
| KLEVV               | 1        | 0.61%   |
| Infineon            | 1        | 0.61%   |
| Elpida              | 1        | 0.61%   |
| BiNFUL              | 1        | 0.61%   |
| Apacer              | 1        | 0.61%   |
| A Force             | 1        | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 6        | 3.28%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 4        | 2.19%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s  | 4        | 2.19%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s   | 3        | 1.64%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s | 3        | 1.64%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s  | 3        | 1.64%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s  | 3        | 1.64%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 2        | 1.09%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 2        | 1.09%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 2        | 1.09%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                  | 2        | 1.09%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 2        | 1.09%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s   | 2        | 1.09%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 2        | 1.09%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 3000MT/s    | 2        | 1.09%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s    | 2        | 1.09%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s  | 2        | 1.09%   |
| Corsair RAM CMK32GX5M2B6000Z30 16GB DIMM DDR5 6000MT/s | 2        | 1.09%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s | 2        | 1.09%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 1        | 0.55%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM 800MT/s                    | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                   | 1        | 0.55%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s           | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM 667MT/s                    | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                   | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s           | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                 | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM                         | 1        | 0.55%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 1        | 0.55%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 1        | 0.55%   |
| Unknown RAM Module 128MB DIMM SDRAM                    | 1        | 0.55%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s   | 1        | 0.55%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s     | 1        | 0.55%   |
| Toshiba RAM 99U5702-094.A00G 8GB DIMM DDR4 2400MT/s    | 1        | 0.55%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s     | 1        | 0.55%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 57       | 40.14%  |
| DDR3    | 51       | 35.92%  |
| Unknown | 14       | 9.86%   |
| DDR5    | 8        | 5.63%   |
| SDRAM   | 6        | 4.23%   |
| DDR2    | 5        | 3.52%   |
| DDR     | 1        | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 131      | 94.24%  |
| SODIMM | 7        | 5.04%   |
| RIMM   | 1        | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 57       | 36.31%  |
| 4096  | 39       | 24.84%  |
| 16384 | 27       | 17.2%   |
| 2048  | 18       | 11.46%  |
| 32768 | 8        | 5.1%    |
| 1024  | 6        | 3.82%   |
| 512   | 1        | 0.64%   |
| 128   | 1        | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 30       | 18.29%  |
| 1333    | 17       | 10.37%  |
| 3600    | 14       | 8.54%   |
| 3200    | 12       | 7.32%   |
| 2400    | 7        | 4.27%   |
| 2133    | 7        | 4.27%   |
| 800     | 7        | 4.27%   |
| 3800    | 6        | 3.66%   |
| 1866    | 6        | 3.66%   |
| 1800    | 6        | 3.66%   |
| 667     | 6        | 3.66%   |
| 2667    | 5        | 3.05%   |
| 6000    | 4        | 2.44%   |
| 1867    | 4        | 2.44%   |
| 3000    | 3        | 1.83%   |
| 1066    | 3        | 1.83%   |
| 4800    | 2        | 1.22%   |
| 3400    | 2        | 1.22%   |
| 2666    | 2        | 1.22%   |
| 1648    | 2        | 1.22%   |
| 1639    | 2        | 1.22%   |
| 533     | 2        | 1.22%   |
| Unknown | 2        | 1.22%   |
| 5600    | 1        | 0.61%   |
| 5200    | 1        | 0.61%   |
| 4266    | 1        | 0.61%   |
| 3866    | 1        | 0.61%   |
| 3733    | 1        | 0.61%   |
| 3666    | 1        | 0.61%   |
| 3534    | 1        | 0.61%   |
| 3467    | 1        | 0.61%   |
| 3266    | 1        | 0.61%   |
| 2933    | 1        | 0.61%   |
| 2733    | 1        | 0.61%   |
| 1067    | 1        | 0.61%   |
| 400     | 1        | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 2        | 33.33%  |
| Brother Industries  | 2        | 33.33%  |
| Samsung Electronics | 1        | 16.67%  |
| Hewlett-Packard     | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung M2070 Series          | 1        | 16.67%  |
| HP Officejet 4500 G510g-m     | 1        | 16.67%  |
| Canon PIXMA MG3600 Series     | 1        | 16.67%  |
| Canon PIXMA MG2500 Series     | 1        | 16.67%  |
| Brother MFC-L2700DW           | 1        | 16.67%  |
| Brother HL-2030 Laser Printer | 1        | 16.67%  |

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


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 22       | 42.31%  |
| Microsoft                              | 6        | 11.54%  |
| Sunplus Innovation Technology          | 4        | 7.69%   |
| Microdia                               | 4        | 7.69%   |
| Generalplus Technology                 | 2        | 3.85%   |
| Creative Technology                    | 2        | 3.85%   |
| WaveRider Communications               | 1        | 1.92%   |
| Trust                                  | 1        | 1.92%   |
| Samsung Electronics                    | 1        | 1.92%   |
| Realtek Semiconductor                  | 1        | 1.92%   |
| Razer USA                              | 1        | 1.92%   |
| GenesysLogic Technology                | 1        | 1.92%   |
| GEMBIRD                                | 1        | 1.92%   |
| Chicony Electronics                    | 1        | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 1.92%   |
| Apple                                  | 1        | 1.92%   |
| Anker PowerConf C200                   | 1        | 1.92%   |
| 2M UVC CAMERA                          | 1        | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                            | 10       | 18.87%  |
| Microsoft LifeCam HD-3000                                              | 4        | 7.55%   |
| Logitech Webcam C270                                                   | 3        | 5.66%   |
| Sunplus Full HD webcam                                                 | 2        | 3.77%   |
| Logitech Logitech Webcam C925e                                         | 2        | 3.77%   |
| Logitech C922 Pro Stream Webcam                                        | 2        | 3.77%   |
| Creative Live! Cam Sync HD [VF0770]                                    | 2        | 3.77%   |
| WaveRider USB 2.0 Camera                                               | 1        | 1.89%   |
| Trust Trust Full HD Webcam                                             | 1        | 1.89%   |
| Sunplus HD 720P webcam                                                 | 1        | 1.89%   |
| Sunplus FHD Capture                                                    | 1        | 1.89%   |
| Samsung Galaxy series, misc. (MTP mode)                                | 1        | 1.89%   |
| Realtek FULL HD 1080P Webcam                                           | 1        | 1.89%   |
| Razer USA Gaming Webcam [Kiyo]                                         | 1        | 1.89%   |
| Microsoft LifeCam NX-3000 (UVC-compliant)                              | 1        | 1.89%   |
| Microsoft LifeCam Cinema                                               | 1        | 1.89%   |
| Microdia Webcam Vitade AF                                              | 1        | 1.89%   |
| Microdia USB 2.0 Camera                                                | 1        | 1.89%   |
| Microdia UHD4K Webcam                                                  | 1        | 1.89%   |
| Microdia Integrated Camera                                             | 1        | 1.89%   |
| Logitech Webcam C930e                                                  | 1        | 1.89%   |
| Logitech Webcam C310                                                   | 1        | 1.89%   |
| Logitech Webcam C210                                                   | 1        | 1.89%   |
| Logitech Webcam C120                                                   | 1        | 1.89%   |
| Logitech QuickCam Vision Pro                                           | 1        | 1.89%   |
| Logitech Logitech Webcam C160                                          | 1        | 1.89%   |
| GenesysLogic USB2.0 UVC PC Camera                                      | 1        | 1.89%   |
| Generalplus GENERAL WEBCAM                                             | 1        | 1.89%   |
| Generalplus 808 Camera #9 (web-cam mode)                               | 1        | 1.89%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                      | 1        | 1.89%   |
| Chicony USB2.0 2MP UVC Camera                                          | 1        | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP 2.0MP High Definition Webcam | 1        | 1.89%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                     | 1        | 1.89%   |
| Anker PowerConf C200 Anker PowerConf C200                              | 1        | 1.89%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam                                    | 1        | 1.89%   |

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
| 0     | 203      | 79.92%  |
| 1     | 43       | 16.93%  |
| 2     | 6        | 2.36%   |
| 5     | 1        | 0.39%   |
| 4     | 1        | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 26       | 45.61%  |
| Graphics card            | 19       | 33.33%  |
| Multimedia controller    | 3        | 5.26%   |
| Unassigned class         | 2        | 3.51%   |
| Net/ethernet             | 2        | 3.51%   |
| Storage/raid             | 1        | 1.75%   |
| Sound                    | 1        | 1.75%   |
| Firewire controller      | 1        | 1.75%   |
| Communication controller | 1        | 1.75%   |
| Camera                   | 1        | 1.75%   |

