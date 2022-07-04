Linux in Austria - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Austria.

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

Total: 745

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0T7D40 A01                  | [42b1694c97](https://linux-hardware.org/?probe=42b1694c97) | Jul 01, 2022 |
| ASRock        | Z490 Pro4                   | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | MAG Z690 TORPEDO            | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| HP            | 8906 SMVB                   | [a10adc5a33](https://linux-hardware.org/?probe=a10adc5a33) | Jun 24, 2022 |
| ASRock        | Z370 Extreme4               | [c971857c53](https://linux-hardware.org/?probe=c971857c53) | Jun 20, 2022 |
| MSI           | 970A-G43                    | [9514e1e2ef](https://linux-hardware.org/?probe=9514e1e2ef) | Jun 16, 2022 |
| AZW           | U59                         | [5a661910dc](https://linux-hardware.org/?probe=5a661910dc) | Jun 16, 2022 |
| MSI           | H510M PRO                   | [b75b035492](https://linux-hardware.org/?probe=b75b035492) | Jun 14, 2022 |
| HP            | 8906 SMVB                   | [772043704c](https://linux-hardware.org/?probe=772043704c) | Jun 13, 2022 |
| HP            | 8906 SMVB                   | [7cc9d90361](https://linux-hardware.org/?probe=7cc9d90361) | Jun 12, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [2f1acce421](https://linux-hardware.org/?probe=2f1acce421) | Jun 08, 2022 |
| MSI           | B450M PRO-VDH MAX           | [11c7f60ef1](https://linux-hardware.org/?probe=11c7f60ef1) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F                | [90b2505b78](https://linux-hardware.org/?probe=90b2505b78) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F                | [722cfa9375](https://linux-hardware.org/?probe=722cfa9375) | Jun 06, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2aeb22bc4b](https://linux-hardware.org/?probe=2aeb22bc4b) | Jun 06, 2022 |
| ASUSTek       | H87-PRO                     | [fd496870e4](https://linux-hardware.org/?probe=fd496870e4) | Jun 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [eccf357f9f](https://linux-hardware.org/?probe=eccf357f9f) | Jun 03, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [156b265da0](https://linux-hardware.org/?probe=156b265da0) | Jun 01, 2022 |
| Gigabyte      | 970A-UD3                    | [c56522071c](https://linux-hardware.org/?probe=c56522071c) | Jun 01, 2022 |
| MSI           | MEG X570 UNIFY              | [b86f47e828](https://linux-hardware.org/?probe=b86f47e828) | May 29, 2022 |
| HP            | 158B                        | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| HP            | 304Bh                       | [eaf30cead9](https://linux-hardware.org/?probe=eaf30cead9) | May 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d6bd3ae553](https://linux-hardware.org/?probe=d6bd3ae553) | May 26, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [257b7363bd](https://linux-hardware.org/?probe=257b7363bd) | May 24, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [666b9afd8f](https://linux-hardware.org/?probe=666b9afd8f) | May 24, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [e4fa1610cb](https://linux-hardware.org/?probe=e4fa1610cb) | May 22, 2022 |
| ASUSTek       | F2A85-V                     | [4d990d8f08](https://linux-hardware.org/?probe=4d990d8f08) | May 21, 2022 |
| ASUSTek       | H61M-A/USB3                 | [4d5f3d8c33](https://linux-hardware.org/?probe=4d5f3d8c33) | May 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [886a958a28](https://linux-hardware.org/?probe=886a958a28) | May 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | [371eb0d1b7](https://linux-hardware.org/?probe=371eb0d1b7) | May 19, 2022 |
| Gigabyte      | Z68XP-UD3                   | [063aeed1a1](https://linux-hardware.org/?probe=063aeed1a1) | May 19, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [cea36d8ad8](https://linux-hardware.org/?probe=cea36d8ad8) | May 15, 2022 |
| Gigabyte      | B450M S2H                   | [1185abcaaa](https://linux-hardware.org/?probe=1185abcaaa) | May 14, 2022 |
| ASRock        | N68C-S UCC                  | [369f214ed2](https://linux-hardware.org/?probe=369f214ed2) | May 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [6003e5a67f](https://linux-hardware.org/?probe=6003e5a67f) | May 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f7d09ea6c5](https://linux-hardware.org/?probe=f7d09ea6c5) | May 13, 2022 |
| ASRock        | B365M Pro4-F                | [75587e5d3e](https://linux-hardware.org/?probe=75587e5d3e) | May 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [91404c39c7](https://linux-hardware.org/?probe=91404c39c7) | May 12, 2022 |
| ASUSTek       | Z87-A                       | [62ffc7ab1a](https://linux-hardware.org/?probe=62ffc7ab1a) | May 11, 2022 |
| Dell          | 0T7D40 A01                  | [36b253f8bc](https://linux-hardware.org/?probe=36b253f8bc) | May 09, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| ASRock        | B450 Steel Legend           | [d2a6709c96](https://linux-hardware.org/?probe=d2a6709c96) | May 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [feaa2cb9fb](https://linux-hardware.org/?probe=feaa2cb9fb) | May 06, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [935eb1722b](https://linux-hardware.org/?probe=935eb1722b) | May 02, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [b923126955](https://linux-hardware.org/?probe=b923126955) | Apr 27, 2022 |
| ASRock        | H110 Pro BTC+               | [1251ef669d](https://linux-hardware.org/?probe=1251ef669d) | Apr 24, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [dbb48b83bf](https://linux-hardware.org/?probe=dbb48b83bf) | Apr 24, 2022 |
| ASUSTek       | M4A78-E                     | [e4779f4dc8](https://linux-hardware.org/?probe=e4779f4dc8) | Apr 23, 2022 |
| ASRock        | X470 Taichi Ultimate        | [d10be6941f](https://linux-hardware.org/?probe=d10be6941f) | Apr 20, 2022 |
| ASRock        | Z490 Pro4                   | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e269a6b9b8](https://linux-hardware.org/?probe=e269a6b9b8) | Apr 18, 2022 |
| ASUSTek       | P7P55D LE                   | [381477f3e6](https://linux-hardware.org/?probe=381477f3e6) | Apr 15, 2022 |
| Fujitsu       | D3434-S2 S26361-D3434-S2    | [7ff488cc8d](https://linux-hardware.org/?probe=7ff488cc8d) | Apr 14, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [cf0c239670](https://linux-hardware.org/?probe=cf0c239670) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9af096ef7f](https://linux-hardware.org/?probe=9af096ef7f) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-A                | [cb3eb74403](https://linux-hardware.org/?probe=cb3eb74403) | Apr 13, 2022 |
| ASUSTek       | P9X79                       | [b7a035ea6b](https://linux-hardware.org/?probe=b7a035ea6b) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f75dc153d0](https://linux-hardware.org/?probe=f75dc153d0) | Apr 13, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [3930b32e77](https://linux-hardware.org/?probe=3930b32e77) | Apr 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [1e302e1cce](https://linux-hardware.org/?probe=1e302e1cce) | Apr 12, 2022 |
| Medion        | MS-7707                     | [fb95ae3a92](https://linux-hardware.org/?probe=fb95ae3a92) | Apr 09, 2022 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [fa2e3ae8ee](https://linux-hardware.org/?probe=fa2e3ae8ee) | Apr 08, 2022 |
| ECS           | CMLU-MINI                   | [742c0da37b](https://linux-hardware.org/?probe=742c0da37b) | Apr 05, 2022 |
| Gigabyte      | B75M-D3V                    | [16d1981053](https://linux-hardware.org/?probe=16d1981053) | Apr 04, 2022 |
| MSI           | MEG X570 UNIFY              | [0c57600526](https://linux-hardware.org/?probe=0c57600526) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [a9cf0523c2](https://linux-hardware.org/?probe=a9cf0523c2) | Mar 31, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [99acee5d56](https://linux-hardware.org/?probe=99acee5d56) | Mar 29, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [85a3c0a47e](https://linux-hardware.org/?probe=85a3c0a47e) | Mar 29, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [8696148b4a](https://linux-hardware.org/?probe=8696148b4a) | Mar 29, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [973087697b](https://linux-hardware.org/?probe=973087697b) | Mar 28, 2022 |
| ASUSTek       | M3A32-MVP DELUXE            | [1bfef458ea](https://linux-hardware.org/?probe=1bfef458ea) | Mar 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d2b4181439](https://linux-hardware.org/?probe=d2b4181439) | Mar 16, 2022 |
| Dell          | 0T7D40 A01                  | [192926e183](https://linux-hardware.org/?probe=192926e183) | Mar 14, 2022 |
| Acer          | Predator PO3-600 V:1.1      | [fc992250ca](https://linux-hardware.org/?probe=fc992250ca) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| MSI           | H81M-P33                    | [0f103bcb15](https://linux-hardware.org/?probe=0f103bcb15) | Mar 12, 2022 |
| MSI           | H81M-P33                    | [304738db66](https://linux-hardware.org/?probe=304738db66) | Mar 11, 2022 |
| ASRock        | B450M Pro4                  | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [5183569327](https://linux-hardware.org/?probe=5183569327) | Mar 06, 2022 |
| BESSTAR Te... | UM200 V1.0                  | [bae5f3ad77](https://linux-hardware.org/?probe=bae5f3ad77) | Feb 26, 2022 |
| ASUSTek       | P9X79                       | [cd0609e2cc](https://linux-hardware.org/?probe=cd0609e2cc) | Feb 25, 2022 |
| ASUSTek       | P9X79                       | [f576f08ecb](https://linux-hardware.org/?probe=f576f08ecb) | Feb 24, 2022 |
| MSI           | H81M-P33                    | [64955f775b](https://linux-hardware.org/?probe=64955f775b) | Feb 24, 2022 |
| Medion        | B250H4-EM                   | [851288ccf7](https://linux-hardware.org/?probe=851288ccf7) | Feb 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [803b4d504c](https://linux-hardware.org/?probe=803b4d504c) | Feb 19, 2022 |
| HP            | 8906 SMVB                   | [ae83ee4d22](https://linux-hardware.org/?probe=ae83ee4d22) | Feb 19, 2022 |
| ASRock        | X299 Taichi XE              | [04a1425dca](https://linux-hardware.org/?probe=04a1425dca) | Feb 17, 2022 |
| ASRock        | X299 Taichi XE              | [45b82f5330](https://linux-hardware.org/?probe=45b82f5330) | Feb 17, 2022 |
| MSI           | Z270 GAMING PRO             | [6c6a916a0b](https://linux-hardware.org/?probe=6c6a916a0b) | Feb 15, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [4ff66e932f](https://linux-hardware.org/?probe=4ff66e932f) | Feb 13, 2022 |
| HP            | 3397                        | [8ea2c45260](https://linux-hardware.org/?probe=8ea2c45260) | Feb 13, 2022 |
| Lenovo        | ThinkCentre A58 7515M6G     | [7b86a1d792](https://linux-hardware.org/?probe=7b86a1d792) | Feb 12, 2022 |
| HP            | 3397                        | [f92e367657](https://linux-hardware.org/?probe=f92e367657) | Feb 12, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [b229af38f0](https://linux-hardware.org/?probe=b229af38f0) | Feb 12, 2022 |
| Biostar       | A10N-8800E                  | [8231d95ddc](https://linux-hardware.org/?probe=8231d95ddc) | Feb 12, 2022 |
| Intel         | DH67GD AAG10206-202         | [56c802164a](https://linux-hardware.org/?probe=56c802164a) | Feb 11, 2022 |
| HP            | 1494                        | [93502b8c70](https://linux-hardware.org/?probe=93502b8c70) | Feb 11, 2022 |
| MSI           | B550-A PRO                  | [577fc1abce](https://linux-hardware.org/?probe=577fc1abce) | Feb 11, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [529666b867](https://linux-hardware.org/?probe=529666b867) | Feb 10, 2022 |
| ASRock        | H81M-HDS                    | [5f2ada50f9](https://linux-hardware.org/?probe=5f2ada50f9) | Feb 10, 2022 |
| ASRock        | 970 Pro3 R2.0               | [c83ca2e528](https://linux-hardware.org/?probe=c83ca2e528) | Feb 10, 2022 |
| HP            | 8906 SMVB                   | [646a1296e0](https://linux-hardware.org/?probe=646a1296e0) | Feb 10, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [4706a4f369](https://linux-hardware.org/?probe=4706a4f369) | Feb 10, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [c945332cad](https://linux-hardware.org/?probe=c945332cad) | Feb 10, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [eb3836e9d0](https://linux-hardware.org/?probe=eb3836e9d0) | Feb 10, 2022 |
| ASUSTek       | PRIME X570-PRO              | [88181832a0](https://linux-hardware.org/?probe=88181832a0) | Feb 09, 2022 |
| ASUSTek       | PRIME X570-PRO              | [9ff4906aa1](https://linux-hardware.org/?probe=9ff4906aa1) | Feb 09, 2022 |
| ASUSTek       | H97-PLUS                    | [435e9532a8](https://linux-hardware.org/?probe=435e9532a8) | Feb 09, 2022 |
| HP            | 8906 SMVB                   | [454f14e47d](https://linux-hardware.org/?probe=454f14e47d) | Feb 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [ab81e91207](https://linux-hardware.org/?probe=ab81e91207) | Feb 08, 2022 |
| Dell          | 0GY6Y8 A01                  | [8b8eda08e4](https://linux-hardware.org/?probe=8b8eda08e4) | Feb 07, 2022 |
| Dell          | 042P49 A00                  | [9f98143f82](https://linux-hardware.org/?probe=9f98143f82) | Feb 07, 2022 |
| ASUSTek       | Z87-A                       | [b48601a549](https://linux-hardware.org/?probe=b48601a549) | Jan 31, 2022 |
| ASUSTek       | Z87-A                       | [b62cc09b63](https://linux-hardware.org/?probe=b62cc09b63) | Jan 30, 2022 |
| ASRock        | 970 Extreme4                | [f024dd97a0](https://linux-hardware.org/?probe=f024dd97a0) | Jan 29, 2022 |
| ASUSTek       | P8H77-M PRO                 | [16d9024680](https://linux-hardware.org/?probe=16d9024680) | Jan 26, 2022 |
| HP            | 8906 SMVB                   | [132c3acbb1](https://linux-hardware.org/?probe=132c3acbb1) | Jan 26, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [dfe4dda46b](https://linux-hardware.org/?probe=dfe4dda46b) | Jan 26, 2022 |
| MSI           | B450M MORTAR MAX            | [619b081f40](https://linux-hardware.org/?probe=619b081f40) | Jan 23, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [635e361ebb](https://linux-hardware.org/?probe=635e361ebb) | Jan 22, 2022 |
| HP            | 1998                        | [422b7b3f1c](https://linux-hardware.org/?probe=422b7b3f1c) | Jan 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0aab49a3e3](https://linux-hardware.org/?probe=0aab49a3e3) | Jan 20, 2022 |
| HP            | 8906 SMVB                   | [566e943f08](https://linux-hardware.org/?probe=566e943f08) | Jan 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6438d5a5af](https://linux-hardware.org/?probe=6438d5a5af) | Jan 15, 2022 |
| HP            | 8906 SMVB                   | [118b411a8c](https://linux-hardware.org/?probe=118b411a8c) | Jan 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [960bd82b34](https://linux-hardware.org/?probe=960bd82b34) | Jan 11, 2022 |
| MSI           | B360M PRO-VDH               | [bd136c19e0](https://linux-hardware.org/?probe=bd136c19e0) | Jan 10, 2022 |
| ASUSTek       | H81M-PLUS                   | [67ab65d5f0](https://linux-hardware.org/?probe=67ab65d5f0) | Jan 10, 2022 |
| ASUSTek       | F2A85-V PRO                 | [9333fdb2cc](https://linux-hardware.org/?probe=9333fdb2cc) | Jan 06, 2022 |
| ASRock        | Z77 Pro4-M                  | [c3ddad9a30](https://linux-hardware.org/?probe=c3ddad9a30) | Jan 03, 2022 |
| ASRock        | X370 Killer SLI             | [7c10b6f7ae](https://linux-hardware.org/?probe=7c10b6f7ae) | Dec 30, 2021 |
| Unknown       | Unknown                     | [cbe80d8c24](https://linux-hardware.org/?probe=cbe80d8c24) | Dec 30, 2021 |
| Dell          | 051FJ8 A02                  | [8cc53ce548](https://linux-hardware.org/?probe=8cc53ce548) | Dec 30, 2021 |
| Gigabyte      | Z170N-WIFI-CF               | [9bcfc1e034](https://linux-hardware.org/?probe=9bcfc1e034) | Dec 23, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6653477f61](https://linux-hardware.org/?probe=6653477f61) | Dec 18, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [b3d411a4d7](https://linux-hardware.org/?probe=b3d411a4d7) | Dec 18, 2021 |
| Gigabyte      | GA-870A-UD3                 | [c4b9060346](https://linux-hardware.org/?probe=c4b9060346) | Dec 18, 2021 |
| ASUSTek       | M4A77                       | [4231ac26aa](https://linux-hardware.org/?probe=4231ac26aa) | Dec 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [bd4a0c5d2f](https://linux-hardware.org/?probe=bd4a0c5d2f) | Dec 12, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [89dd614f98](https://linux-hardware.org/?probe=89dd614f98) | Dec 09, 2021 |
| Acer          | Aspire XC-605               | [770f6167f6](https://linux-hardware.org/?probe=770f6167f6) | Dec 08, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [01b9229bd4](https://linux-hardware.org/?probe=01b9229bd4) | Dec 08, 2021 |
| MSI           | X570-A PRO                  | [d2704f29ec](https://linux-hardware.org/?probe=d2704f29ec) | Dec 06, 2021 |
| ASUSTek       | P9X79-E WS                  | [b65be23e52](https://linux-hardware.org/?probe=b65be23e52) | Dec 06, 2021 |
| ASRockRack    | C3558D4I-4L                 | [d563eb82ae](https://linux-hardware.org/?probe=d563eb82ae) | Dec 04, 2021 |
| Gigabyte      | Z270P-D3-CF                 | [ca35105e1a](https://linux-hardware.org/?probe=ca35105e1a) | Dec 04, 2021 |
| HP            | 21D0                        | [50548c11b7](https://linux-hardware.org/?probe=50548c11b7) | Dec 04, 2021 |
| Lenovo        | MAHOBAY                     | [e6f6525ecd](https://linux-hardware.org/?probe=e6f6525ecd) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a1669a775b](https://linux-hardware.org/?probe=a1669a775b) | Nov 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0d42fdd2bf](https://linux-hardware.org/?probe=0d42fdd2bf) | Nov 30, 2021 |
| Medion        | MS-7748                     | [bb473ca5d8](https://linux-hardware.org/?probe=bb473ca5d8) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f6ab5c54f6](https://linux-hardware.org/?probe=f6ab5c54f6) | Nov 27, 2021 |
| Dell          | 0T7D40 A01                  | [065636c444](https://linux-hardware.org/?probe=065636c444) | Nov 25, 2021 |
| MSI           | A78M-E35                    | [999bbc1197](https://linux-hardware.org/?probe=999bbc1197) | Nov 24, 2021 |
| Acer          | Revo 70                     | [f5cdb95334](https://linux-hardware.org/?probe=f5cdb95334) | Nov 24, 2021 |
| Acer          | Revo 70                     | [4c99b6ac71](https://linux-hardware.org/?probe=4c99b6ac71) | Nov 24, 2021 |
| ASRock        | X570 Pro4                   | [1cce90a2eb](https://linux-hardware.org/?probe=1cce90a2eb) | Nov 23, 2021 |
| HP            | 0AECh D                     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| HP            | ProLiant MicroServer Gen... | [0178a25382](https://linux-hardware.org/?probe=0178a25382) | Nov 18, 2021 |
| ASUSTek       | P7P55D EVO                  | [f453f8d58d](https://linux-hardware.org/?probe=f453f8d58d) | Nov 18, 2021 |
| ASUSTek       | Z170-P                      | [1e333032a4](https://linux-hardware.org/?probe=1e333032a4) | Nov 14, 2021 |
| ASRock        | P67 Pro3                    | [17c9af356a](https://linux-hardware.org/?probe=17c9af356a) | Nov 08, 2021 |
| ASUSTek       | Z170-P                      | [37f9ff3c0b](https://linux-hardware.org/?probe=37f9ff3c0b) | Nov 07, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [5cea4f8e91](https://linux-hardware.org/?probe=5cea4f8e91) | Nov 04, 2021 |
| Dell          | 0Y2MRG A00                  | [80cfec46fc](https://linux-hardware.org/?probe=80cfec46fc) | Nov 03, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| ASRock        | A320M-HDV R4.0              | [267a4603eb](https://linux-hardware.org/?probe=267a4603eb) | Nov 02, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [500411363b](https://linux-hardware.org/?probe=500411363b) | Nov 01, 2021 |
| Gigabyte      | P55M-UD2                    | [b14c0e8dd2](https://linux-hardware.org/?probe=b14c0e8dd2) | Oct 29, 2021 |
| MSI           | A78M-E35                    | [69da26c946](https://linux-hardware.org/?probe=69da26c946) | Oct 29, 2021 |
| ASUSTek       | SABERTOOTH X79              | [2b361b1035](https://linux-hardware.org/?probe=2b361b1035) | Oct 28, 2021 |
| ASUSTek       | M11BB                       | [c049f2b753](https://linux-hardware.org/?probe=c049f2b753) | Oct 28, 2021 |
| Acer          | FIH57                       | [719b6ffbe5](https://linux-hardware.org/?probe=719b6ffbe5) | Oct 24, 2021 |
| ASUSTek       | PRIME J4005I-C              | [2c5d786879](https://linux-hardware.org/?probe=2c5d786879) | Oct 20, 2021 |
| Intel         | D54250WYK H13922-303        | [21b715e26a](https://linux-hardware.org/?probe=21b715e26a) | Oct 17, 2021 |
| Gigabyte      | H61MA-D2V                   | [3968e39b0b](https://linux-hardware.org/?probe=3968e39b0b) | Oct 12, 2021 |
| ASUSTek       | PRIME A320I-K               | [eee2a960f5](https://linux-hardware.org/?probe=eee2a960f5) | Oct 11, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [4054b4ec35](https://linux-hardware.org/?probe=4054b4ec35) | Oct 11, 2021 |
| HP            | 8906 SMVB                   | [8fca5ef20e](https://linux-hardware.org/?probe=8fca5ef20e) | Oct 11, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [971cdf3ab8](https://linux-hardware.org/?probe=971cdf3ab8) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [d01c751c63](https://linux-hardware.org/?probe=d01c751c63) | Oct 11, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | [719e7db7f5](https://linux-hardware.org/?probe=719e7db7f5) | Oct 09, 2021 |
| Gigabyte      | X570 AORUS PRO              | [d3c72411ee](https://linux-hardware.org/?probe=d3c72411ee) | Oct 09, 2021 |
| HP            | 212B                        | [a4318b7064](https://linux-hardware.org/?probe=a4318b7064) | Oct 06, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8f7011b085](https://linux-hardware.org/?probe=8f7011b085) | Oct 03, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [b6eca9083a](https://linux-hardware.org/?probe=b6eca9083a) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [415f0d9244](https://linux-hardware.org/?probe=415f0d9244) | Oct 01, 2021 |
| Gigabyte      | GA-M56S-S3                  | [4502947e1a](https://linux-hardware.org/?probe=4502947e1a) | Sep 30, 2021 |
| ASRock        | Z170 Gaming K4              | [f107c84c00](https://linux-hardware.org/?probe=f107c84c00) | Sep 30, 2021 |
| MSI           | 790FX-GD70                  | [ba5f2949aa](https://linux-hardware.org/?probe=ba5f2949aa) | Sep 26, 2021 |
| Gigabyte      | Z590 D                      | [97c779cffc](https://linux-hardware.org/?probe=97c779cffc) | Sep 20, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [83649103a6](https://linux-hardware.org/?probe=83649103a6) | Sep 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [ee40317007](https://linux-hardware.org/?probe=ee40317007) | Sep 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [ae610c34e9](https://linux-hardware.org/?probe=ae610c34e9) | Sep 16, 2021 |
| ASUSTek       | P5K-VM                      | [59fc10448f](https://linux-hardware.org/?probe=59fc10448f) | Sep 14, 2021 |
| MSI           | Z170-A PRO                  | [5b702a6c05](https://linux-hardware.org/?probe=5b702a6c05) | Sep 12, 2021 |
| HP            | 8767 A                      | [bb5655cf3b](https://linux-hardware.org/?probe=bb5655cf3b) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [bc2d35138c](https://linux-hardware.org/?probe=bc2d35138c) | Sep 10, 2021 |
| Unknown       | 1.21                        | [dbf4f53e70](https://linux-hardware.org/?probe=dbf4f53e70) | Sep 05, 2021 |
| Biostar       | X470NH                      | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| Gigabyte      | M52LT-D3P                   | [949b2062ea](https://linux-hardware.org/?probe=949b2062ea) | Sep 03, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [68da5f41b2](https://linux-hardware.org/?probe=68da5f41b2) | Aug 27, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [d87877599e](https://linux-hardware.org/?probe=d87877599e) | Aug 26, 2021 |
| Shuttle       | FS61                        | [fc97f7167b](https://linux-hardware.org/?probe=fc97f7167b) | Aug 26, 2021 |
| HP            | 8906 SMVB                   | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| HP            | 8906 SMVB                   | [5f90a39c6f](https://linux-hardware.org/?probe=5f90a39c6f) | Aug 20, 2021 |
| ASRock        | J4205-ITX                   | [30de75d2c8](https://linux-hardware.org/?probe=30de75d2c8) | Aug 18, 2021 |
| Medion        | MS-7707                     | [66ace31297](https://linux-hardware.org/?probe=66ace31297) | Aug 16, 2021 |
| ASRock        | Z590 Pro4                   | [5d9a3a97f2](https://linux-hardware.org/?probe=5d9a3a97f2) | Aug 16, 2021 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| ASRock        | H97M Pro4                   | [5edf7e02c8](https://linux-hardware.org/?probe=5edf7e02c8) | Aug 14, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [3fd838012c](https://linux-hardware.org/?probe=3fd838012c) | Aug 12, 2021 |
| HP            | 8906 SMVB                   | [98dc285619](https://linux-hardware.org/?probe=98dc285619) | Aug 11, 2021 |
| HP            | 8906 SMVB                   | [4c7e9555c1](https://linux-hardware.org/?probe=4c7e9555c1) | Aug 08, 2021 |
| Dell          | 0T7D40 A01                  | [0728097100](https://linux-hardware.org/?probe=0728097100) | Aug 06, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [2c843a3d35](https://linux-hardware.org/?probe=2c843a3d35) | Aug 04, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [729ae360b5](https://linux-hardware.org/?probe=729ae360b5) | Aug 03, 2021 |
| HP            | 1495                        | [48e893c344](https://linux-hardware.org/?probe=48e893c344) | Aug 03, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [50136afddd](https://linux-hardware.org/?probe=50136afddd) | Aug 02, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [27e7a22365](https://linux-hardware.org/?probe=27e7a22365) | Aug 02, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [55f86a29a2](https://linux-hardware.org/?probe=55f86a29a2) | Jul 29, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [816edfa4bb](https://linux-hardware.org/?probe=816edfa4bb) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| ASUSTek       | B150M-K                     | [34e2582dc2](https://linux-hardware.org/?probe=34e2582dc2) | Jul 25, 2021 |
| ASUSTek       | X79-DELUXE                  | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| MSI           | B85M-E45                    | [16178cb493](https://linux-hardware.org/?probe=16178cb493) | Jul 24, 2021 |
| ASUSTek       | Z170-WS                     | [3368a26a83](https://linux-hardware.org/?probe=3368a26a83) | Jul 23, 2021 |
| Acer          | Aspire TC-780               | [cc39834e1d](https://linux-hardware.org/?probe=cc39834e1d) | Jul 21, 2021 |
| ASUSTek       | F2A85-V                     | [ad05a07bb3](https://linux-hardware.org/?probe=ad05a07bb3) | Jul 19, 2021 |
| HP            | 1495                        | [f2affe9c46](https://linux-hardware.org/?probe=f2affe9c46) | Jul 18, 2021 |
| HP            | 212A                        | [56cd9e7eaa](https://linux-hardware.org/?probe=56cd9e7eaa) | Jul 18, 2021 |
| HP            | 0AECh D                     | [9b91275879](https://linux-hardware.org/?probe=9b91275879) | Jul 13, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [497c16be4b](https://linux-hardware.org/?probe=497c16be4b) | Jul 12, 2021 |
| HP            | 0AECh D                     | [540f6d1b4e](https://linux-hardware.org/?probe=540f6d1b4e) | Jul 11, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [7adcf7dc7c](https://linux-hardware.org/?probe=7adcf7dc7c) | Jul 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [07e45f519d](https://linux-hardware.org/?probe=07e45f519d) | Jul 09, 2021 |
| ASRock        | H67M                        | [660e47da08](https://linux-hardware.org/?probe=660e47da08) | Jul 08, 2021 |
| ASUSTek       | Maximus VII HERO            | [1e8044f366](https://linux-hardware.org/?probe=1e8044f366) | Jul 07, 2021 |
| MSI           | A78M-E35                    | [cef9d93dd1](https://linux-hardware.org/?probe=cef9d93dd1) | Jul 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [647b8b3725](https://linux-hardware.org/?probe=647b8b3725) | Jul 02, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [9a49b1159d](https://linux-hardware.org/?probe=9a49b1159d) | Jul 01, 2021 |
| ASUSTek       | Maximus VII HERO            | [0e605c5229](https://linux-hardware.org/?probe=0e605c5229) | Jun 26, 2021 |
| Dell          | 0T7D40 A01                  | [5ee785eb32](https://linux-hardware.org/?probe=5ee785eb32) | Jun 24, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [dbc4494db2](https://linux-hardware.org/?probe=dbc4494db2) | Jun 23, 2021 |
| Gigabyte      | X570 AORUS PRO              | [ea70f9fe3b](https://linux-hardware.org/?probe=ea70f9fe3b) | Jun 23, 2021 |
| MSI           | Z170A SLI PLUS              | [d715625644](https://linux-hardware.org/?probe=d715625644) | Jun 22, 2021 |
| Unknown       | Unknown                     | [489dc53e4d](https://linux-hardware.org/?probe=489dc53e4d) | Jun 20, 2021 |
| Unknown       | Unknown                     | [077a1849dd](https://linux-hardware.org/?probe=077a1849dd) | Jun 20, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [bd42ad29b1](https://linux-hardware.org/?probe=bd42ad29b1) | Jun 18, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [42e10b10fd](https://linux-hardware.org/?probe=42e10b10fd) | Jun 15, 2021 |
| Gigabyte      | Z590 VISION G               | [c3b20ee137](https://linux-hardware.org/?probe=c3b20ee137) | Jun 12, 2021 |
| ASRock        | ALiveXFire-eSATA2           | [17af721bae](https://linux-hardware.org/?probe=17af721bae) | Jun 10, 2021 |
| Lenovo        | SDK0E50510 WIN 262508179... | [489ce4720c](https://linux-hardware.org/?probe=489ce4720c) | Jun 06, 2021 |
| ASRock        | H87 Pro4                    | [5f78dd5211](https://linux-hardware.org/?probe=5f78dd5211) | Jun 06, 2021 |
| ASUSTek       | P7P55D LE                   | [5e58b5909b](https://linux-hardware.org/?probe=5e58b5909b) | Jun 04, 2021 |
| ASUSTek       | P7P55D LE                   | [119ec1d3ba](https://linux-hardware.org/?probe=119ec1d3ba) | Jun 04, 2021 |
| Gigabyte      | Z590 VISION G               | [ea4492aeee](https://linux-hardware.org/?probe=ea4492aeee) | May 30, 2021 |
| MSI           | H97 PC Mate                 | [05dcac5e7f](https://linux-hardware.org/?probe=05dcac5e7f) | May 30, 2021 |
| ASUSTek       | P5Q-E                       | [ef3b21caf0](https://linux-hardware.org/?probe=ef3b21caf0) | May 30, 2021 |
| Gigabyte      | 990FXA-UD3                  | [02fee32807](https://linux-hardware.org/?probe=02fee32807) | May 29, 2021 |
| HP            | 1495                        | [660c4ff2ed](https://linux-hardware.org/?probe=660c4ff2ed) | May 28, 2021 |
| ASRock        | J5040-ITX                   | [5ffe86e682](https://linux-hardware.org/?probe=5ffe86e682) | May 28, 2021 |
| Medion        | B460H6-EM                   | [0b9ae4f256](https://linux-hardware.org/?probe=0b9ae4f256) | May 28, 2021 |
| HP            | 198E                        | [39fd78a563](https://linux-hardware.org/?probe=39fd78a563) | May 26, 2021 |
| MSI           | X570-A PRO                  | [49eb802c2e](https://linux-hardware.org/?probe=49eb802c2e) | May 25, 2021 |
| ASRock        | A320M-HDV R4.0              | [2983d7e745](https://linux-hardware.org/?probe=2983d7e745) | May 25, 2021 |
| ASRock        | Z170 Extreme7+              | [324df6eb69](https://linux-hardware.org/?probe=324df6eb69) | May 25, 2021 |
| ASRock        | H77M                        | [3a362598fb](https://linux-hardware.org/?probe=3a362598fb) | May 23, 2021 |
| ASUSTek       | J1900I-C                    | [560fd63326](https://linux-hardware.org/?probe=560fd63326) | May 21, 2021 |
| ASRock        | B365M Pro4-F                | [9b31a1e94f](https://linux-hardware.org/?probe=9b31a1e94f) | May 21, 2021 |
| ASRock        | H77M                        | [e3d59b843a](https://linux-hardware.org/?probe=e3d59b843a) | May 21, 2021 |
| ASRock        | 970 Pro3 R2.0               | [d811152e10](https://linux-hardware.org/?probe=d811152e10) | May 19, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [daf3bcdc44](https://linux-hardware.org/?probe=daf3bcdc44) | May 18, 2021 |
| ASUSTek       | P5B                         | [ff621cb51a](https://linux-hardware.org/?probe=ff621cb51a) | May 17, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [c11404a76b](https://linux-hardware.org/?probe=c11404a76b) | May 14, 2021 |
| MSI           | H97 PC Mate                 | [14457815f8](https://linux-hardware.org/?probe=14457815f8) | May 13, 2021 |
| ASUSTek       | P8H77-M PRO                 | [524de3a747](https://linux-hardware.org/?probe=524de3a747) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | [daf2cdf31f](https://linux-hardware.org/?probe=daf2cdf31f) | May 09, 2021 |
| ASUSTek       | PRIME A320M-K               | [70628bdf55](https://linux-hardware.org/?probe=70628bdf55) | May 06, 2021 |
| Gigabyte      | H110N-CF                    | [d03c007deb](https://linux-hardware.org/?probe=d03c007deb) | May 06, 2021 |
| Gigabyte      | B450M S2H                   | [9e1c2c1ffd](https://linux-hardware.org/?probe=9e1c2c1ffd) | May 05, 2021 |
| Biostar       | A78MD                       | [3f56e00dd2](https://linux-hardware.org/?probe=3f56e00dd2) | May 04, 2021 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [573b65efbd](https://linux-hardware.org/?probe=573b65efbd) | May 02, 2021 |
| HP            | 844C                        | [913d5aff80](https://linux-hardware.org/?probe=913d5aff80) | Apr 30, 2021 |
| ASRock        | H110 Pro BTC+               | [799ad15d8b](https://linux-hardware.org/?probe=799ad15d8b) | Apr 30, 2021 |
| ASRock        | Z170 Extreme6+              | [74e3dec02b](https://linux-hardware.org/?probe=74e3dec02b) | Apr 29, 2021 |
| ASRock        | Z170 Extreme6+              | [7f2a8a7ab8](https://linux-hardware.org/?probe=7f2a8a7ab8) | Apr 29, 2021 |
| Dell          | 0Y7WYT A00                  | [399bf0d60e](https://linux-hardware.org/?probe=399bf0d60e) | Apr 28, 2021 |
| HP            | 304Bh                       | [dc42bd8e41](https://linux-hardware.org/?probe=dc42bd8e41) | Apr 27, 2021 |
| ASUSTek       | GRYPHON Z87                 | [8a54738ba0](https://linux-hardware.org/?probe=8a54738ba0) | Apr 26, 2021 |
| MSI           | X570-A PRO                  | [1a7d9facd2](https://linux-hardware.org/?probe=1a7d9facd2) | Apr 25, 2021 |
| ASRock        | Z170 Gaming K4              | [69ec5d246b](https://linux-hardware.org/?probe=69ec5d246b) | Apr 25, 2021 |
| ASRock        | P4i65G                      | [3818ed802a](https://linux-hardware.org/?probe=3818ed802a) | Apr 24, 2021 |
| Sapphire      | PI-AM3RS760G2               | [f54647d31e](https://linux-hardware.org/?probe=f54647d31e) | Apr 24, 2021 |
| MSI           | MS-7091                     | [f5d9a3ba0e](https://linux-hardware.org/?probe=f5d9a3ba0e) | Apr 19, 2021 |
| MSI           | B450M PRO-VDH MAX           | [ca0c473e06](https://linux-hardware.org/?probe=ca0c473e06) | Apr 18, 2021 |
| MSI           | X570-A PRO                  | [c4e4afedd6](https://linux-hardware.org/?probe=c4e4afedd6) | Apr 17, 2021 |
| ASUSTek       | J1900I-C                    | [e980e0a528](https://linux-hardware.org/?probe=e980e0a528) | Apr 17, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [12b9e4bb0f](https://linux-hardware.org/?probe=12b9e4bb0f) | Apr 16, 2021 |
| ASUSTek       | M2N-MX                      | [8dd14baaf0](https://linux-hardware.org/?probe=8dd14baaf0) | Apr 16, 2021 |
| Medion        | MS-7713                     | [0acac9a543](https://linux-hardware.org/?probe=0acac9a543) | Apr 13, 2021 |
| ASRock        | X370 Taichi                 | [fbefa3cd0b](https://linux-hardware.org/?probe=fbefa3cd0b) | Apr 11, 2021 |
| ASUSTek       | P5QPL-AM                    | [b609880289](https://linux-hardware.org/?probe=b609880289) | Apr 10, 2021 |
| Acer          | Veriton M480                | [a7a0203b44](https://linux-hardware.org/?probe=a7a0203b44) | Apr 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [e4dcbccb5c](https://linux-hardware.org/?probe=e4dcbccb5c) | Apr 05, 2021 |
| MSI           | X570-A PRO                  | [465d54d765](https://linux-hardware.org/?probe=465d54d765) | Apr 05, 2021 |
| Acer          | Nitro N50-600 V:1.1         | [e7ddf93f9f](https://linux-hardware.org/?probe=e7ddf93f9f) | Apr 04, 2021 |
| Acer          | Nitro N50-600 V:1.1         | [b281b84f5b](https://linux-hardware.org/?probe=b281b84f5b) | Apr 04, 2021 |
| MSI           | Z77 MPower                  | [a6d2710163](https://linux-hardware.org/?probe=a6d2710163) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [7100e0c7bc](https://linux-hardware.org/?probe=7100e0c7bc) | Mar 30, 2021 |
| ASRock        | J3160-NUC                   | [3f44c1a54f](https://linux-hardware.org/?probe=3f44c1a54f) | Mar 28, 2021 |
| ASUSTek       | PRIME H310-PLUS             | [6e36a57c6d](https://linux-hardware.org/?probe=6e36a57c6d) | Mar 28, 2021 |
| Medion        | B550A4-EM                   | [641ec219ff](https://linux-hardware.org/?probe=641ec219ff) | Mar 27, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ed38cf686e](https://linux-hardware.org/?probe=ed38cf686e) | Mar 26, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [70072ce040](https://linux-hardware.org/?probe=70072ce040) | Mar 26, 2021 |
| Lenovo        | SHARKBAY NOK                | [87a2ba2f24](https://linux-hardware.org/?probe=87a2ba2f24) | Mar 25, 2021 |
| ASRock        | Z87 Extreme3                | [702e348746](https://linux-hardware.org/?probe=702e348746) | Mar 25, 2021 |
| ASUSTek       | F2A85-V                     | [a393c07087](https://linux-hardware.org/?probe=a393c07087) | Mar 20, 2021 |
| HP            | 1494                        | [8aec7a3cbf](https://linux-hardware.org/?probe=8aec7a3cbf) | Mar 20, 2021 |
| MSI           | B450-A PRO MAX              | [1f8eee9aa4](https://linux-hardware.org/?probe=1f8eee9aa4) | Mar 18, 2021 |
| HP            | 1998                        | [43924e927e](https://linux-hardware.org/?probe=43924e927e) | Mar 18, 2021 |
| HP            | 1998                        | [c98634a421](https://linux-hardware.org/?probe=c98634a421) | Mar 18, 2021 |
| MSI           | B450-A PRO MAX              | [a15b0ecd7b](https://linux-hardware.org/?probe=a15b0ecd7b) | Mar 18, 2021 |
| ASUSTek       | P8Z68-V LX                  | [d1673f61bc](https://linux-hardware.org/?probe=d1673f61bc) | Mar 17, 2021 |
| ASRock        | H77M                        | [13d87f3380](https://linux-hardware.org/?probe=13d87f3380) | Mar 16, 2021 |
| ASRock        | H77M                        | [f7f669b943](https://linux-hardware.org/?probe=f7f669b943) | Mar 14, 2021 |
| ASRock        | B365M Pro4-F                | [0c6489fca5](https://linux-hardware.org/?probe=0c6489fca5) | Mar 14, 2021 |
| ASUSTek       | Z170-A                      | [2fe6674c71](https://linux-hardware.org/?probe=2fe6674c71) | Mar 13, 2021 |
| ASRock        | X570 Taichi                 | [31906d8b73](https://linux-hardware.org/?probe=31906d8b73) | Mar 13, 2021 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [41735bfb3d](https://linux-hardware.org/?probe=41735bfb3d) | Mar 12, 2021 |
| ASUSTek       | Pro WS W480-ACE             | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| MSI           | H81M-P33                    | [5498e38a32](https://linux-hardware.org/?probe=5498e38a32) | Mar 10, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [74c947442a](https://linux-hardware.org/?probe=74c947442a) | Mar 10, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a35ded4130](https://linux-hardware.org/?probe=a35ded4130) | Mar 09, 2021 |
| ASRock        | A300M-STX                   | [6377ea853f](https://linux-hardware.org/?probe=6377ea853f) | Mar 07, 2021 |
| ASUSTek       | P5Q3                        | [dd50fe59b2](https://linux-hardware.org/?probe=dd50fe59b2) | Mar 07, 2021 |
| MSI           | Z87-G45 GAMING              | [3464f180fe](https://linux-hardware.org/?probe=3464f180fe) | Mar 04, 2021 |
| Biostar       | A78MD                       | [0bd08c0771](https://linux-hardware.org/?probe=0bd08c0771) | Mar 02, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [332fc8bbcf](https://linux-hardware.org/?probe=332fc8bbcf) | Mar 01, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [94a4e1db49](https://linux-hardware.org/?probe=94a4e1db49) | Feb 28, 2021 |
| Biostar       | A78MD                       | [06b1319f09](https://linux-hardware.org/?probe=06b1319f09) | Feb 28, 2021 |
| Biostar       | A78MD                       | [6aff42d829](https://linux-hardware.org/?probe=6aff42d829) | Feb 28, 2021 |
| Biostar       | A78MD                       | [c468e84e6d](https://linux-hardware.org/?probe=c468e84e6d) | Feb 28, 2021 |
| MSI           | Z97 GAMING 9 ACK            | [11e9217472](https://linux-hardware.org/?probe=11e9217472) | Feb 28, 2021 |
| ASUSTek       | PRIME A320M-K               | [cb866ef0ba](https://linux-hardware.org/?probe=cb866ef0ba) | Feb 28, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [8ad661d01b](https://linux-hardware.org/?probe=8ad661d01b) | Feb 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [95f839ef17](https://linux-hardware.org/?probe=95f839ef17) | Feb 26, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [fe1a81c6bc](https://linux-hardware.org/?probe=fe1a81c6bc) | Feb 24, 2021 |
| Gigabyte      | A520M S2H                   | [f502acb72d](https://linux-hardware.org/?probe=f502acb72d) | Feb 24, 2021 |
| ASUSTek       | PRIME X370-PRO              | [91a16f1c67](https://linux-hardware.org/?probe=91a16f1c67) | Feb 21, 2021 |
| ASUSTek       | F2A85-V                     | [48e9166aea](https://linux-hardware.org/?probe=48e9166aea) | Feb 21, 2021 |
| ASUSTek       | M5A99X EVO                  | [2300d9d1f9](https://linux-hardware.org/?probe=2300d9d1f9) | Feb 20, 2021 |
| ASUSTek       | PRIME H310-PLUS             | [b0af95e7a7](https://linux-hardware.org/?probe=b0af95e7a7) | Feb 20, 2021 |
| Gigabyte      | GA-MA78LMT-S2               | [a642c82f46](https://linux-hardware.org/?probe=a642c82f46) | Feb 19, 2021 |
| MSI           | A320M-A PRO MAX             | [f22bf6b05d](https://linux-hardware.org/?probe=f22bf6b05d) | Feb 18, 2021 |
| HP            | ProLiant ML30 Gen9          | [f6af5a4d70](https://linux-hardware.org/?probe=f6af5a4d70) | Feb 16, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [015f4f6c33](https://linux-hardware.org/?probe=015f4f6c33) | Feb 15, 2021 |
| ASUSTek       | Z87-C                       | [601b3fd251](https://linux-hardware.org/?probe=601b3fd251) | Feb 14, 2021 |
| ASUSTek       | B85-PRO GAMER               | [3cd9ecf495](https://linux-hardware.org/?probe=3cd9ecf495) | Feb 14, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [105a38c590](https://linux-hardware.org/?probe=105a38c590) | Feb 14, 2021 |
| ASRock        | Z77 Pro3                    | [d129998ffb](https://linux-hardware.org/?probe=d129998ffb) | Feb 13, 2021 |
| Gigabyte      | 970A-DS3P                   | [bdecca84fa](https://linux-hardware.org/?probe=bdecca84fa) | Feb 13, 2021 |
| ASRock        | Z77 Pro3                    | [06b57f0a75](https://linux-hardware.org/?probe=06b57f0a75) | Feb 13, 2021 |
| Dell          | 0WWJRX A00                  | [a3efc0b825](https://linux-hardware.org/?probe=a3efc0b825) | Feb 13, 2021 |
| ASUSTek       | P5QPL-AM                    | [d51e8f5abc](https://linux-hardware.org/?probe=d51e8f5abc) | Feb 10, 2021 |
| ASUSTek       | M2N-MX                      | [c8ae57e616](https://linux-hardware.org/?probe=c8ae57e616) | Feb 07, 2021 |
| ASUSTek       | P5E3 Deluxe                 | [47324765ec](https://linux-hardware.org/?probe=47324765ec) | Feb 02, 2021 |
| Dell          | 05XGC8 A01                  | [910c9c3e21](https://linux-hardware.org/?probe=910c9c3e21) | Feb 01, 2021 |
| Dell          | 05XGC8 A01                  | [46719a0e53](https://linux-hardware.org/?probe=46719a0e53) | Feb 01, 2021 |
| Dell          | 05XGC8 A01                  | [b1c22c1894](https://linux-hardware.org/?probe=b1c22c1894) | Feb 01, 2021 |
| ASUSTek       | P5Q                         | [037cf0158e](https://linux-hardware.org/?probe=037cf0158e) | Jan 30, 2021 |
| ASUSTek       | P5Q                         | [aaa6e7b901](https://linux-hardware.org/?probe=aaa6e7b901) | Jan 30, 2021 |
| ASRock        | Z77 Pro3                    | [ea0df821be](https://linux-hardware.org/?probe=ea0df821be) | Jan 28, 2021 |
| ASRock        | Z77 Pro3                    | [9592e5cbb6](https://linux-hardware.org/?probe=9592e5cbb6) | Jan 28, 2021 |
| HP            | 3646h                       | [e540758f9c](https://linux-hardware.org/?probe=e540758f9c) | Jan 26, 2021 |
| ASUSTek       | PRIME Z270-A                | [e6f737276c](https://linux-hardware.org/?probe=e6f737276c) | Jan 25, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | [5d23694899](https://linux-hardware.org/?probe=5d23694899) | Jan 24, 2021 |
| MSI           | Z170-A PRO                  | [6c8926dc8c](https://linux-hardware.org/?probe=6c8926dc8c) | Jan 23, 2021 |
| MSI           | Z97 GAMING 5                | [8da68cf0c1](https://linux-hardware.org/?probe=8da68cf0c1) | Jan 20, 2021 |
| HP            | 1998                        | [06c680725c](https://linux-hardware.org/?probe=06c680725c) | Jan 19, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [536f80b3b5](https://linux-hardware.org/?probe=536f80b3b5) | Jan 17, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [7d647c8ecb](https://linux-hardware.org/?probe=7d647c8ecb) | Jan 16, 2021 |
| MSI           | MS-7A66                     | [083df1e870](https://linux-hardware.org/?probe=083df1e870) | Jan 16, 2021 |
| ASRock        | X470 Taichi                 | [d7179bef44](https://linux-hardware.org/?probe=d7179bef44) | Jan 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [742e66b7f0](https://linux-hardware.org/?probe=742e66b7f0) | Jan 12, 2021 |
| ASRock        | X470 Taichi                 | [da311c1d96](https://linux-hardware.org/?probe=da311c1d96) | Jan 11, 2021 |
| ASRock        | B450 Steel Legend           | [2b825ca52c](https://linux-hardware.org/?probe=2b825ca52c) | Jan 11, 2021 |
| HP            | 0AECh D                     | [8ae3501e15](https://linux-hardware.org/?probe=8ae3501e15) | Jan 10, 2021 |
| Lenovo        | MAHOBAY                     | [6186295ee1](https://linux-hardware.org/?probe=6186295ee1) | Jan 10, 2021 |
| MSI           | Z390-A PRO                  | [5927c2d7dd](https://linux-hardware.org/?probe=5927c2d7dd) | Jan 09, 2021 |
| Intel         | B75                         | [991f6ce47d](https://linux-hardware.org/?probe=991f6ce47d) | Jan 09, 2021 |
| Intel         | B75                         | [f2aa38279b](https://linux-hardware.org/?probe=f2aa38279b) | Jan 09, 2021 |
| Gigabyte      | B550M AORUS PRO             | [32a3812ca0](https://linux-hardware.org/?probe=32a3812ca0) | Jan 08, 2021 |
| HP            | 0AECh D                     | [d870844e43](https://linux-hardware.org/?probe=d870844e43) | Jan 08, 2021 |
| ASUSTek       | P8Z77-V LX                  | [c5ed6d05c0](https://linux-hardware.org/?probe=c5ed6d05c0) | Jan 08, 2021 |
| MSI           | H110 PC MATE                | [e4353652f8](https://linux-hardware.org/?probe=e4353652f8) | Jan 07, 2021 |
| Medion        | MS-7707                     | [c48264f558](https://linux-hardware.org/?probe=c48264f558) | Jan 06, 2021 |
| ASUSTek       | Z97-AR                      | [7bb75eb062](https://linux-hardware.org/?probe=7bb75eb062) | Jan 04, 2021 |
| ASRock        | B450 Steel Legend           | [11ee0a81c2](https://linux-hardware.org/?probe=11ee0a81c2) | Jan 03, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [feb58a7b82](https://linux-hardware.org/?probe=feb58a7b82) | Jan 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [f3aa67a60f](https://linux-hardware.org/?probe=f3aa67a60f) | Jan 02, 2021 |
| HP            | 0AACh                       | [73e545d08e](https://linux-hardware.org/?probe=73e545d08e) | Dec 30, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [7443ed9c8e](https://linux-hardware.org/?probe=7443ed9c8e) | Dec 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [7774d76390](https://linux-hardware.org/?probe=7774d76390) | Dec 29, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [a747cbbc12](https://linux-hardware.org/?probe=a747cbbc12) | Dec 29, 2020 |
| ASUSTek       | P8H77-M PRO                 | [7479398d6b](https://linux-hardware.org/?probe=7479398d6b) | Dec 26, 2020 |
| ASUSTek       | P8H77-M PRO                 | [dae4f56b87](https://linux-hardware.org/?probe=dae4f56b87) | Dec 26, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [14d8088058](https://linux-hardware.org/?probe=14d8088058) | Dec 26, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [5f9cd7bf8d](https://linux-hardware.org/?probe=5f9cd7bf8d) | Dec 26, 2020 |
| Gigabyte      | H61M-S2PV                   | [c8192fa1b8](https://linux-hardware.org/?probe=c8192fa1b8) | Dec 25, 2020 |
| ASUSTek       | Z87-A                       | [1f96153282](https://linux-hardware.org/?probe=1f96153282) | Dec 24, 2020 |
| MSI           | B450M MORTAR MAX            | [95d87e6473](https://linux-hardware.org/?probe=95d87e6473) | Dec 22, 2020 |
| ASRock        | 970 Extreme4                | [036cbb8abd](https://linux-hardware.org/?probe=036cbb8abd) | Dec 19, 2020 |
| ASRock        | 970 Extreme4                | [076e600b98](https://linux-hardware.org/?probe=076e600b98) | Dec 17, 2020 |
| ASRock        | 970 Extreme4                | [c772b379fb](https://linux-hardware.org/?probe=c772b379fb) | Dec 16, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [52ea92c087](https://linux-hardware.org/?probe=52ea92c087) | Dec 11, 2020 |
| Gigabyte      | B460M D3H                   | [5a7f0069e7](https://linux-hardware.org/?probe=5a7f0069e7) | Dec 10, 2020 |
| ASUSTek       | P5B-PLUS Series             | [ba214d2a0b](https://linux-hardware.org/?probe=ba214d2a0b) | Dec 08, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | [3597a3315a](https://linux-hardware.org/?probe=3597a3315a) | Dec 07, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [e8e2d0cdfc](https://linux-hardware.org/?probe=e8e2d0cdfc) | Dec 05, 2020 |
| ASUSTek       | Rampage II GENE             | [c551fbc02b](https://linux-hardware.org/?probe=c551fbc02b) | Dec 05, 2020 |
| Medion        | MS-7785                     | [7db825feae](https://linux-hardware.org/?probe=7db825feae) | Dec 05, 2020 |
| HP            | 83E1                        | [b02eab0d7b](https://linux-hardware.org/?probe=b02eab0d7b) | Dec 03, 2020 |
| ASUSTek       | PRIME X570-P                | [2745a37c0a](https://linux-hardware.org/?probe=2745a37c0a) | Dec 02, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [4f5d0b5689](https://linux-hardware.org/?probe=4f5d0b5689) | Dec 02, 2020 |
| HP            | 304Ah                       | [e0127b5745](https://linux-hardware.org/?probe=e0127b5745) | Dec 02, 2020 |
| MSI           | H110 PC MATE                | [1ace18d8c6](https://linux-hardware.org/?probe=1ace18d8c6) | Dec 02, 2020 |
| MSI           | X570-A PRO                  | [619a44519d](https://linux-hardware.org/?probe=619a44519d) | Nov 26, 2020 |
| MSI           | X570-A PRO                  | [4da3e1e733](https://linux-hardware.org/?probe=4da3e1e733) | Nov 25, 2020 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [c7afad637f](https://linux-hardware.org/?probe=c7afad637f) | Nov 21, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [34e2c6b1de](https://linux-hardware.org/?probe=34e2c6b1de) | Nov 21, 2020 |
| ASUSTek       | P6T SE                      | [ab5ae06143](https://linux-hardware.org/?probe=ab5ae06143) | Nov 20, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [4a2a55be34](https://linux-hardware.org/?probe=4a2a55be34) | Nov 19, 2020 |
| ASUSTek       | Z170-A                      | [7ecb8cf20c](https://linux-hardware.org/?probe=7ecb8cf20c) | Nov 18, 2020 |
| ASUSTek       | P5Q3                        | [7aea73f517](https://linux-hardware.org/?probe=7aea73f517) | Nov 18, 2020 |
| MSI           | B450 TOMAHAWK               | [12ad3a5613](https://linux-hardware.org/?probe=12ad3a5613) | Nov 17, 2020 |
| Unknown       | 1.21                        | [03bbb3fe9d](https://linux-hardware.org/?probe=03bbb3fe9d) | Nov 17, 2020 |
| MSI           | 970 GAMING                  | [ad2e6869d2](https://linux-hardware.org/?probe=ad2e6869d2) | Nov 16, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [dad48b0b71](https://linux-hardware.org/?probe=dad48b0b71) | Nov 15, 2020 |
| ASUSTek       | SABERTOOTH X79              | [85af1aa380](https://linux-hardware.org/?probe=85af1aa380) | Nov 15, 2020 |
| MSI           | B450-A PRO MAX              | [174f09979c](https://linux-hardware.org/?probe=174f09979c) | Nov 15, 2020 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [afa9fa19f7](https://linux-hardware.org/?probe=afa9fa19f7) | Nov 13, 2020 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [848659f1bb](https://linux-hardware.org/?probe=848659f1bb) | Nov 13, 2020 |
| HP            | 304Bh                       | [eabe5c6576](https://linux-hardware.org/?probe=eabe5c6576) | Nov 12, 2020 |
| HP            | 1998                        | [ba70213a7c](https://linux-hardware.org/?probe=ba70213a7c) | Nov 12, 2020 |
| HP            | 304Bh                       | [2a0818c8b9](https://linux-hardware.org/?probe=2a0818c8b9) | Nov 12, 2020 |
| Dell          | 0KWVT8 A02                  | [f5beb28b88](https://linux-hardware.org/?probe=f5beb28b88) | Nov 10, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1eaf5979d8](https://linux-hardware.org/?probe=1eaf5979d8) | Nov 10, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a0619b8d1d](https://linux-hardware.org/?probe=a0619b8d1d) | Nov 10, 2020 |
| ASUSTek       | Z170-DELUXE                 | [ece6cbfa68](https://linux-hardware.org/?probe=ece6cbfa68) | Nov 10, 2020 |
| ASUSTek       | Rampage II GENE             | [bf53346564](https://linux-hardware.org/?probe=bf53346564) | Nov 10, 2020 |
| ASUSTek       | PRIME A320M-K               | [901ff66119](https://linux-hardware.org/?probe=901ff66119) | Nov 10, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [e84ecfe5e0](https://linux-hardware.org/?probe=e84ecfe5e0) | Nov 08, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [f33a623bd5](https://linux-hardware.org/?probe=f33a623bd5) | Nov 08, 2020 |
| MSI           | B450-A PRO MAX              | [5052705b44](https://linux-hardware.org/?probe=5052705b44) | Nov 07, 2020 |
| MSI           | B450-A PRO MAX              | [aa0cd52789](https://linux-hardware.org/?probe=aa0cd52789) | Nov 07, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8090d5d13d](https://linux-hardware.org/?probe=8090d5d13d) | Nov 07, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [33b552fa2a](https://linux-hardware.org/?probe=33b552fa2a) | Nov 07, 2020 |
| Medion        | MS-7800                     | [2bda8fb463](https://linux-hardware.org/?probe=2bda8fb463) | Nov 06, 2020 |
| ASUSTek       | Z87M-PLUS                   | [fe30aa6977](https://linux-hardware.org/?probe=fe30aa6977) | Nov 06, 2020 |
| MSI           | 970 GAMING                  | [8787720406](https://linux-hardware.org/?probe=8787720406) | Nov 06, 2020 |
| ASUSTek       | Z170-DELUXE                 | [5b260893c7](https://linux-hardware.org/?probe=5b260893c7) | Nov 04, 2020 |
| Gigabyte      | H61M-S2PV                   | [3ddf6dd16e](https://linux-hardware.org/?probe=3ddf6dd16e) | Nov 02, 2020 |
| Gigabyte      | H61M-S2PV                   | [602a208acb](https://linux-hardware.org/?probe=602a208acb) | Nov 02, 2020 |
| MSI           | Z170-A PRO                  | [6f36f04e56](https://linux-hardware.org/?probe=6f36f04e56) | Oct 31, 2020 |
| MSI           | Z390-A PRO                  | [7e3367f5de](https://linux-hardware.org/?probe=7e3367f5de) | Oct 31, 2020 |
| Gigabyte      | B550M AORUS PRO             | [cc234953ee](https://linux-hardware.org/?probe=cc234953ee) | Oct 29, 2020 |
| Gigabyte      | B550M AORUS PRO             | [8694779259](https://linux-hardware.org/?probe=8694779259) | Oct 28, 2020 |
| Gigabyte      | 990FXA-UD3                  | [2640f19771](https://linux-hardware.org/?probe=2640f19771) | Oct 27, 2020 |
| MSI           | B450-A PRO                  | [8d3080c24b](https://linux-hardware.org/?probe=8d3080c24b) | Oct 27, 2020 |
| Gigabyte      | 990FXA-UD3                  | [edad386a06](https://linux-hardware.org/?probe=edad386a06) | Oct 26, 2020 |
| Dell          | 0KWVT8 A02                  | [6067b5fdca](https://linux-hardware.org/?probe=6067b5fdca) | Oct 26, 2020 |
| MSI           | 785G-E53                    | [896761d94a](https://linux-hardware.org/?probe=896761d94a) | Oct 26, 2020 |
| MSI           | B450-A PRO                  | [2af48de4a6](https://linux-hardware.org/?probe=2af48de4a6) | Oct 25, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [18dfc7eccc](https://linux-hardware.org/?probe=18dfc7eccc) | Oct 20, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [1e299c5dbc](https://linux-hardware.org/?probe=1e299c5dbc) | Oct 20, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [e6d077732c](https://linux-hardware.org/?probe=e6d077732c) | Oct 19, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c37609a667](https://linux-hardware.org/?probe=c37609a667) | Oct 18, 2020 |
| ASRock        | H55M/USB3                   | [74202436b2](https://linux-hardware.org/?probe=74202436b2) | Oct 18, 2020 |
| ASRock        | B75 Pro3-M                  | [d8b4105b7c](https://linux-hardware.org/?probe=d8b4105b7c) | Oct 18, 2020 |
| Intel         | DN2820FYK H24582-202        | [64105a10e1](https://linux-hardware.org/?probe=64105a10e1) | Oct 13, 2020 |
| ASUSTek       | Z97-DELUXE                  | [5bfe608b47](https://linux-hardware.org/?probe=5bfe608b47) | Oct 12, 2020 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [648cae37e8](https://linux-hardware.org/?probe=648cae37e8) | Oct 11, 2020 |
| Fujitsu       | D2779 S26361-D2779-A1       | [07795a357a](https://linux-hardware.org/?probe=07795a357a) | Oct 09, 2020 |
| Dell          | 0G261D A00                  | [f42ed32356](https://linux-hardware.org/?probe=f42ed32356) | Oct 08, 2020 |
| ASRock        | Z170 Extreme4               | [b6708fc3ec](https://linux-hardware.org/?probe=b6708fc3ec) | Oct 08, 2020 |
| ASRock        | Z170 Extreme4               | [67f95905f8](https://linux-hardware.org/?probe=67f95905f8) | Oct 08, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | [f304a2629f](https://linux-hardware.org/?probe=f304a2629f) | Oct 04, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [becb2dabd4](https://linux-hardware.org/?probe=becb2dabd4) | Oct 02, 2020 |
| Gigabyte      | Z77-D3H                     | [12b1ada1b7](https://linux-hardware.org/?probe=12b1ada1b7) | Oct 01, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [019f1044f5](https://linux-hardware.org/?probe=019f1044f5) | Sep 30, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [34ab2deca5](https://linux-hardware.org/?probe=34ab2deca5) | Sep 30, 2020 |
| Lenovo        | ThinkCentre A55 96417RG     | [e66b41beda](https://linux-hardware.org/?probe=e66b41beda) | Sep 30, 2020 |
| Lenovo        | ThinkCentre A55 96417RG     | [40217b727c](https://linux-hardware.org/?probe=40217b727c) | Sep 30, 2020 |
| HP            | 3396                        | [08d4e10fe8](https://linux-hardware.org/?probe=08d4e10fe8) | Sep 29, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | [d1379f41e9](https://linux-hardware.org/?probe=d1379f41e9) | Sep 28, 2020 |
| MSI           | X470 GAMING PLUS            | [1f88d959a3](https://linux-hardware.org/?probe=1f88d959a3) | Sep 28, 2020 |
| MSI           | H170A PC MATE               | [1ccbc6d2a3](https://linux-hardware.org/?probe=1ccbc6d2a3) | Sep 26, 2020 |
| HP            | 3396                        | [54a44b3423](https://linux-hardware.org/?probe=54a44b3423) | Sep 24, 2020 |
| Gigabyte      | B550M AORUS PRO             | [f4ca6f2be3](https://linux-hardware.org/?probe=f4ca6f2be3) | Sep 24, 2020 |
| ASUSTek       | P9X79 PRO                   | [6cdc4d7b68](https://linux-hardware.org/?probe=6cdc4d7b68) | Sep 18, 2020 |
| MSI           | A68HM-E33 V2                | [f3b0511fad](https://linux-hardware.org/?probe=f3b0511fad) | Sep 16, 2020 |
| ASUSTek       | P5E3 Deluxe                 | [694576f25f](https://linux-hardware.org/?probe=694576f25f) | Sep 14, 2020 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [2a2f29d4f4](https://linux-hardware.org/?probe=2a2f29d4f4) | Sep 13, 2020 |
| MSI           | X470 GAMING PLUS            | [c863e26606](https://linux-hardware.org/?probe=c863e26606) | Sep 13, 2020 |
| Gigabyte      | 970A-UD3                    | [d54620a8e6](https://linux-hardware.org/?probe=d54620a8e6) | Sep 04, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [e5f0dd8145](https://linux-hardware.org/?probe=e5f0dd8145) | Sep 04, 2020 |
| ASUSTek       | NODUSM3                     | [f8d3ca460a](https://linux-hardware.org/?probe=f8d3ca460a) | Sep 04, 2020 |
| MSI           | Z97-G45 GAMING              | [23d327ddd1](https://linux-hardware.org/?probe=23d327ddd1) | Sep 02, 2020 |
| Medion        | MS-7800                     | [350be22d12](https://linux-hardware.org/?probe=350be22d12) | Sep 02, 2020 |
| Gigabyte      | B550M AORUS PRO             | [a4b94dc9a0](https://linux-hardware.org/?probe=a4b94dc9a0) | Sep 02, 2020 |
| MSI           | MS-7502 Fab D               | [90f4a91dab](https://linux-hardware.org/?probe=90f4a91dab) | Sep 02, 2020 |
| MSI           | MS-7502 Fab D               | [bb820cc0f5](https://linux-hardware.org/?probe=bb820cc0f5) | Sep 02, 2020 |
| ASRock        | TRX40 Creator               | [e8bbe1674e](https://linux-hardware.org/?probe=e8bbe1674e) | Sep 01, 2020 |
| Gigabyte      | B250-FinTech-CF             | [0b97759dbc](https://linux-hardware.org/?probe=0b97759dbc) | Aug 31, 2020 |
| Gigabyte      | H370M DS3H-CF               | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [9c6deccbd7](https://linux-hardware.org/?probe=9c6deccbd7) | Aug 29, 2020 |
| ASRock        | TRX40 Creator               | [3e63a6cb23](https://linux-hardware.org/?probe=3e63a6cb23) | Aug 29, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [804af7bd77](https://linux-hardware.org/?probe=804af7bd77) | Aug 29, 2020 |
| MSI           | B450 TOMAHAWK               | [8d2a486570](https://linux-hardware.org/?probe=8d2a486570) | Aug 23, 2020 |
| Gigabyte      | 970A-UD3                    | [a5bc169d85](https://linux-hardware.org/?probe=a5bc169d85) | Aug 19, 2020 |
| ASUSTek       | M5A99X EVO                  | [6aae8e8b65](https://linux-hardware.org/?probe=6aae8e8b65) | Aug 12, 2020 |
| ASUSTek       | P5KC                        | [9fb165eec5](https://linux-hardware.org/?probe=9fb165eec5) | Aug 10, 2020 |
| Gigabyte      | X570 GAMING X               | [cf865f40d3](https://linux-hardware.org/?probe=cf865f40d3) | Aug 10, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | [ba1dcb2d6a](https://linux-hardware.org/?probe=ba1dcb2d6a) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [eea93c64ef](https://linux-hardware.org/?probe=eea93c64ef) | Aug 04, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5f6337d416](https://linux-hardware.org/?probe=5f6337d416) | Aug 04, 2020 |
| ASRock        | Z390 Taichi Ultimate        | [9bc233d847](https://linux-hardware.org/?probe=9bc233d847) | Jul 28, 2020 |
| ASUSTek       | M5A97 PRO                   | [2feb4909d3](https://linux-hardware.org/?probe=2feb4909d3) | Jul 26, 2020 |
| ASUSTek       | PRIME X570-P                | [57be047558](https://linux-hardware.org/?probe=57be047558) | Jul 21, 2020 |
| ASRock        | Z87M Extreme4               | [c964d8e6aa](https://linux-hardware.org/?probe=c964d8e6aa) | Jul 17, 2020 |
| ASRock        | Z87M Extreme4               | [647e26f9c0](https://linux-hardware.org/?probe=647e26f9c0) | Jul 17, 2020 |
| MSI           | B360 GAMING PRO CARBON      | [878e756625](https://linux-hardware.org/?probe=878e756625) | Jul 13, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [89a4e31a34](https://linux-hardware.org/?probe=89a4e31a34) | Jul 12, 2020 |
| ASUSTek       | P5KC                        | [b43325a5a2](https://linux-hardware.org/?probe=b43325a5a2) | Jul 09, 2020 |
| Gigabyte      | B450M DS3H-CF               | [f680a985bf](https://linux-hardware.org/?probe=f680a985bf) | Jul 06, 2020 |
| ASUSTek       | SABERTOOTH X58              | [dc448a83c5](https://linux-hardware.org/?probe=dc448a83c5) | Jul 06, 2020 |
| ASUSTek       | SABERTOOTH X58              | [a4a160f8f5](https://linux-hardware.org/?probe=a4a160f8f5) | Jul 06, 2020 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [e4db7317e2](https://linux-hardware.org/?probe=e4db7317e2) | Jul 03, 2020 |
| Foxconn       | NETBOX NT-425/525 Ver       | [bdce37f0a6](https://linux-hardware.org/?probe=bdce37f0a6) | Jul 02, 2020 |
| Acer          | Veriton X4630G              | [504ec0d230](https://linux-hardware.org/?probe=504ec0d230) | Jun 30, 2020 |
| MSI           | 760GM-P23                   | [c130373ac8](https://linux-hardware.org/?probe=c130373ac8) | Jun 29, 2020 |
| ASUSTek       | P7H55-M PRO                 | [76aa2e624e](https://linux-hardware.org/?probe=76aa2e624e) | Jun 28, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | [120fd84f28](https://linux-hardware.org/?probe=120fd84f28) | Jun 26, 2020 |
| MSI           | X470 GAMING PRO             | [a7138e79c0](https://linux-hardware.org/?probe=a7138e79c0) | Jun 23, 2020 |
| MSI           | 760GM-P23                   | [8463ee797e](https://linux-hardware.org/?probe=8463ee797e) | Jun 21, 2020 |
| ASUSTek       | P5Q3                        | [4e73fc0ebd](https://linux-hardware.org/?probe=4e73fc0ebd) | Jun 16, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [ae1cea8d82](https://linux-hardware.org/?probe=ae1cea8d82) | Jun 15, 2020 |
| ASUSTek       | P5Q3                        | [f2a4215c2c](https://linux-hardware.org/?probe=f2a4215c2c) | Jun 14, 2020 |
| Fujitsu Si... | D2610-A1 S26361-D2610-A1    | [1598cd7c04](https://linux-hardware.org/?probe=1598cd7c04) | Jun 10, 2020 |
| MSI           | H270 GAMING M3              | [10c5cc23af](https://linux-hardware.org/?probe=10c5cc23af) | Jun 09, 2020 |
| MSI           | B450 GAMING PLUS            | [534ac38dd7](https://linux-hardware.org/?probe=534ac38dd7) | Jun 09, 2020 |
| ASUSTek       | Q87T                        | [8eae2b51f5](https://linux-hardware.org/?probe=8eae2b51f5) | Jun 08, 2020 |
| ASUSTek       | M4A785TD-M EVO              | [8c865a795a](https://linux-hardware.org/?probe=8c865a795a) | Jun 05, 2020 |
| ASRock        | B150M Pro4                  | [d704cdc9e0](https://linux-hardware.org/?probe=d704cdc9e0) | Jun 04, 2020 |
| Dell          | 0CT017                      | [7a9a09ec49](https://linux-hardware.org/?probe=7a9a09ec49) | Jun 03, 2020 |
| Gigabyte      | H110N-CF                    | [3e9da1e0fc](https://linux-hardware.org/?probe=3e9da1e0fc) | Jun 02, 2020 |
| Gigabyte      | GA-890FXA-UD5               | [b9edeb9db7](https://linux-hardware.org/?probe=b9edeb9db7) | Jun 01, 2020 |
| Fujitsu Si... | D2610-A1 S26361-D2610-A1    | [2290624850](https://linux-hardware.org/?probe=2290624850) | May 31, 2020 |
| MSI           | A88X-G45 GAMING             | [5321862a29](https://linux-hardware.org/?probe=5321862a29) | May 25, 2020 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [fe4766c68b](https://linux-hardware.org/?probe=fe4766c68b) | May 24, 2020 |
| Fujitsu Si... | D2610-A1 S26361-D2610-A1    | [73ff075e8b](https://linux-hardware.org/?probe=73ff075e8b) | May 23, 2020 |
| Fujitsu Si... | D2610-A1 S26361-D2610-A1    | [83c143bfd7](https://linux-hardware.org/?probe=83c143bfd7) | May 23, 2020 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [04495f26dd](https://linux-hardware.org/?probe=04495f26dd) | May 23, 2020 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [104dcd648a](https://linux-hardware.org/?probe=104dcd648a) | May 23, 2020 |
| Medion        | B250H4-EM                   | [7202ccb609](https://linux-hardware.org/?probe=7202ccb609) | May 23, 2020 |
| Gigabyte      | P55A-UD4                    | [c1f8a1209b](https://linux-hardware.org/?probe=c1f8a1209b) | May 20, 2020 |
| ASUSTek       | PRIME A320I-K               | [bea9fd77be](https://linux-hardware.org/?probe=bea9fd77be) | May 19, 2020 |
| HP            | 1905                        | [e70c3c026a](https://linux-hardware.org/?probe=e70c3c026a) | May 16, 2020 |
| MSI           | Z68MA-ED55                  | [2562e1a6d7](https://linux-hardware.org/?probe=2562e1a6d7) | May 14, 2020 |
| HP            | 1495                        | [f0d3a50933](https://linux-hardware.org/?probe=f0d3a50933) | May 13, 2020 |
| Lenovo        | GA-6UASV2 E1_2              | [38e4b2547a](https://linux-hardware.org/?probe=38e4b2547a) | May 13, 2020 |
| ASUSTek       | P8H77-V LE                  | [bf8510147c](https://linux-hardware.org/?probe=bf8510147c) | May 13, 2020 |
| ASUSTek       | P6X58D-E                    | [5a566d4992](https://linux-hardware.org/?probe=5a566d4992) | May 12, 2020 |
| Gigabyte      | P55A-UD4                    | [697d506a6f](https://linux-hardware.org/?probe=697d506a6f) | May 11, 2020 |
| Gigabyte      | Z97P-D3                     | [9ee0d24e00](https://linux-hardware.org/?probe=9ee0d24e00) | May 10, 2020 |
| HP            | 1495                        | [34b3c59a20](https://linux-hardware.org/?probe=34b3c59a20) | May 09, 2020 |
| MSI           | H61MU-E35                   | [e5efecff9f](https://linux-hardware.org/?probe=e5efecff9f) | May 05, 2020 |
| ASUSTek       | PRIME A320I-K               | [1a70114ffb](https://linux-hardware.org/?probe=1a70114ffb) | May 05, 2020 |
| ASUSTek       | Z170I PRO GAMING            | [13c69a7e65](https://linux-hardware.org/?probe=13c69a7e65) | May 05, 2020 |
| IBM           | 59Y3432 SIT                 | [056b639e0c](https://linux-hardware.org/?probe=056b639e0c) | May 04, 2020 |
| Shuttle       | FS61                        | [06e7b64da1](https://linux-hardware.org/?probe=06e7b64da1) | May 03, 2020 |
| Sapphire      | PI-AM3RS760G2               | [9ac1ac4237](https://linux-hardware.org/?probe=9ac1ac4237) | May 02, 2020 |
| Sapphire      | PI-AM3RS760G2               | [a700f16cf8](https://linux-hardware.org/?probe=a700f16cf8) | May 02, 2020 |
| Sapphire      | PI-AM3RS760G2               | [e0632f7f90](https://linux-hardware.org/?probe=e0632f7f90) | May 02, 2020 |
| HP            | 1495                        | [79ab6a37e9](https://linux-hardware.org/?probe=79ab6a37e9) | May 02, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [dd0d7252fc](https://linux-hardware.org/?probe=dd0d7252fc) | May 02, 2020 |
| ASRock        | Z390 Taichi Ultimate        | [b4ed75c290](https://linux-hardware.org/?probe=b4ed75c290) | May 01, 2020 |
| Medion        | MS-7800                     | [b49432576f](https://linux-hardware.org/?probe=b49432576f) | Apr 30, 2020 |
| Medion        | MS-7800                     | [c6e7751601](https://linux-hardware.org/?probe=c6e7751601) | Apr 30, 2020 |
| ASUSTek       | M5A78L-M LE                 | [4c00485154](https://linux-hardware.org/?probe=4c00485154) | Apr 29, 2020 |
| ASUSTek       | P6T                         | [08f2e0c42d](https://linux-hardware.org/?probe=08f2e0c42d) | Apr 29, 2020 |
| Sapphire      | PI-AM3RS760G2               | [d5a11756e4](https://linux-hardware.org/?probe=d5a11756e4) | Apr 27, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | [25299e6aa0](https://linux-hardware.org/?probe=25299e6aa0) | Apr 26, 2020 |
| ASRock        | Z390 Taichi Ultimate        | [0040f0e90b](https://linux-hardware.org/?probe=0040f0e90b) | Apr 26, 2020 |
| MSI           | Z97 GAMING 9 ACK            | [7b9e17c081](https://linux-hardware.org/?probe=7b9e17c081) | Apr 25, 2020 |
| Acer          | RS780HVF                    | [15e8b006b4](https://linux-hardware.org/?probe=15e8b006b4) | Apr 24, 2020 |
| Acer          | RS780HVF                    | [fd298ac831](https://linux-hardware.org/?probe=fd298ac831) | Apr 22, 2020 |
| Acer          | RS780HVF                    | [1118996f35](https://linux-hardware.org/?probe=1118996f35) | Apr 22, 2020 |
| Acer          | RS780HVF                    | [c1fee6cb8b](https://linux-hardware.org/?probe=c1fee6cb8b) | Apr 21, 2020 |
| ASUSTek       | P5B                         | [436080c949](https://linux-hardware.org/?probe=436080c949) | Apr 20, 2020 |
| ASRock        | Z68 Pro3                    | [4313e511b6](https://linux-hardware.org/?probe=4313e511b6) | Apr 14, 2020 |
| ASRock        | Z68 Pro3                    | [099a117f0b](https://linux-hardware.org/?probe=099a117f0b) | Apr 14, 2020 |
| ASUSTek       | F2A85-V PRO                 | [28f4f3baf5](https://linux-hardware.org/?probe=28f4f3baf5) | Apr 10, 2020 |
| ASRock        | N68-GE3 UCC                 | [212d62f70b](https://linux-hardware.org/?probe=212d62f70b) | Apr 10, 2020 |
| Lenovo        | SHARKBAY NOK                | [ca34648c4b](https://linux-hardware.org/?probe=ca34648c4b) | Apr 08, 2020 |
| ASUSTek       | F2A85-V PRO                 | [256ee14889](https://linux-hardware.org/?probe=256ee14889) | Apr 07, 2020 |
| ASUSTek       | F2A85-V PRO                 | [39d4b7909a](https://linux-hardware.org/?probe=39d4b7909a) | Apr 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [993050d9df](https://linux-hardware.org/?probe=993050d9df) | Apr 04, 2020 |
| Medion        | MS-7800                     | [f3afd63ba2](https://linux-hardware.org/?probe=f3afd63ba2) | Apr 01, 2020 |
| Gigabyte      | GA-78LMT-S2P                | [0120aa60f5](https://linux-hardware.org/?probe=0120aa60f5) | Mar 29, 2020 |
| Gigabyte      | Z370M D3H-CF                | [176480702c](https://linux-hardware.org/?probe=176480702c) | Mar 14, 2020 |
| Foxconn       | AT-5000 Series PCB/1.1      | [7dc424d59f](https://linux-hardware.org/?probe=7dc424d59f) | Mar 06, 2020 |
| Foxconn       | AT-5000 Series PCB/1.1      | [94c91254ef](https://linux-hardware.org/?probe=94c91254ef) | Mar 06, 2020 |
| ASRock        | Z87 Killer                  | [983418b600](https://linux-hardware.org/?probe=983418b600) | Mar 06, 2020 |
| MSI           | B450 TOMAHAWK               | [8088ded621](https://linux-hardware.org/?probe=8088ded621) | Feb 21, 2020 |
| ASUSTek       | X99-A                       | [2d2ef6c415](https://linux-hardware.org/?probe=2d2ef6c415) | Feb 20, 2020 |
| MSI           | B450 TOMAHAWK               | [ce8f69c02b](https://linux-hardware.org/?probe=ce8f69c02b) | Feb 20, 2020 |
| ASRock        | Z87 Killer                  | [6ce107652f](https://linux-hardware.org/?probe=6ce107652f) | Feb 10, 2020 |
| Medion        | MS-7728                     | [645a7667ce](https://linux-hardware.org/?probe=645a7667ce) | Feb 07, 2020 |
| Medion        | MS-7728                     | [c55f5705f3](https://linux-hardware.org/?probe=c55f5705f3) | Feb 07, 2020 |
| ASRock        | FM2A88X Extreme4+           | [f3c713b688](https://linux-hardware.org/?probe=f3c713b688) | Feb 04, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [c2bebe9cae](https://linux-hardware.org/?probe=c2bebe9cae) | Feb 03, 2020 |
| Pegatron      | Benicia                     | [077bb98064](https://linux-hardware.org/?probe=077bb98064) | Feb 03, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [2fdfff2aeb](https://linux-hardware.org/?probe=2fdfff2aeb) | Feb 02, 2020 |
| ASRock        | H97 Pro4                    | [9692f4331b](https://linux-hardware.org/?probe=9692f4331b) | Jan 30, 2020 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [9e2420dad2](https://linux-hardware.org/?probe=9e2420dad2) | Jan 30, 2020 |
| ASRock        | H97 Pro4                    | [8e0ed4d700](https://linux-hardware.org/?probe=8e0ed4d700) | Jan 30, 2020 |
| Pegatron      | Benicia                     | [7ad790ff7a](https://linux-hardware.org/?probe=7ad790ff7a) | Jan 29, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [146d3c4f96](https://linux-hardware.org/?probe=146d3c4f96) | Jan 29, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | [5642861837](https://linux-hardware.org/?probe=5642861837) | Jan 24, 2020 |
| Lenovo        | MAHOBAY No DPK              | [d72cbdf691](https://linux-hardware.org/?probe=d72cbdf691) | Jan 20, 2020 |
| Biostar       | A10N-8800E                  | [1b678941da](https://linux-hardware.org/?probe=1b678941da) | Jan 19, 2020 |
| ASUSTek       | H87M-PRO                    | [001ad7f036](https://linux-hardware.org/?probe=001ad7f036) | Jan 19, 2020 |
| ASUSTek       | M3N78-EM                    | [e7441046c0](https://linux-hardware.org/?probe=e7441046c0) | Jan 15, 2020 |
| ASUSTek       | M4A78T-E                    | [259abe496b](https://linux-hardware.org/?probe=259abe496b) | Jan 10, 2020 |
| HP            | 0AA8h                       | [6bfa4ca4a7](https://linux-hardware.org/?probe=6bfa4ca4a7) | Jan 01, 2020 |
| ASUSTek       | H81M-PLUS                   | [08a52838c1](https://linux-hardware.org/?probe=08a52838c1) | Dec 29, 2019 |
| Medion        | MS-7728                     | [a86ef1e6d5](https://linux-hardware.org/?probe=a86ef1e6d5) | Dec 26, 2019 |
| Gigabyte      | B250-FinTech-CF             | [74a6661df4](https://linux-hardware.org/?probe=74a6661df4) | Dec 09, 2019 |
| MSI           | X470 GAMING PRO             | [3c409e3fac](https://linux-hardware.org/?probe=3c409e3fac) | Nov 17, 2019 |
| ASUSTek       | P8H67                       | [6592929d60](https://linux-hardware.org/?probe=6592929d60) | Nov 13, 2019 |
| MSI           | X370 KRAIT GAMING           | [2030142a09](https://linux-hardware.org/?probe=2030142a09) | Nov 08, 2019 |
| MSI           | X370 KRAIT GAMING           | [2fc6906f36](https://linux-hardware.org/?probe=2fc6906f36) | Nov 08, 2019 |
| Dell          | 0DN075                      | [588c79360b](https://linux-hardware.org/?probe=588c79360b) | Oct 31, 2019 |
| ASUSTek       | V-P7H55E                    | [f973a6c8a9](https://linux-hardware.org/?probe=f973a6c8a9) | Oct 28, 2019 |
| Packard Be... | IMEDIA S1300                | [0fda47e3b7](https://linux-hardware.org/?probe=0fda47e3b7) | Oct 23, 2019 |
| ASRock        | Z87 Killer                  | [8ae3df832b](https://linux-hardware.org/?probe=8ae3df832b) | Oct 17, 2019 |
| ASRock        | Z87 Killer                  | [41c93cac66](https://linux-hardware.org/?probe=41c93cac66) | Oct 08, 2019 |
| MSI           | X470 GAMING PRO             | [7904813ed9](https://linux-hardware.org/?probe=7904813ed9) | Oct 06, 2019 |
| ASRock        | Z87 Killer                  | [ff79176dae](https://linux-hardware.org/?probe=ff79176dae) | Oct 04, 2019 |
| MSI           | X470 GAMING PRO             | [21c0db91eb](https://linux-hardware.org/?probe=21c0db91eb) | Oct 02, 2019 |
| ASRock        | Z87 Killer                  | [46b0add918](https://linux-hardware.org/?probe=46b0add918) | Sep 30, 2019 |
| ASUSTek       | P8H67                       | [8e59924d0d](https://linux-hardware.org/?probe=8e59924d0d) | Sep 30, 2019 |
| ASUSTek       | P6T SE                      | [f829c40cce](https://linux-hardware.org/?probe=f829c40cce) | Sep 28, 2019 |
| ASUSTek       | P6T SE                      | [8dcf40d84d](https://linux-hardware.org/?probe=8dcf40d84d) | Sep 28, 2019 |
| Acer          | Veriton M2631 V:1.0         | [6542efae35](https://linux-hardware.org/?probe=6542efae35) | Sep 23, 2019 |
| MSI           | X99S MPOWER                 | [fd30de16b0](https://linux-hardware.org/?probe=fd30de16b0) | Sep 22, 2019 |
| Lenovo        | ThinkCentre M58p 6137E61    | [ed59e38f8c](https://linux-hardware.org/?probe=ed59e38f8c) | Sep 06, 2019 |
| Lenovo        | ThinkCentre M58p 6137E61    | [52fa080e49](https://linux-hardware.org/?probe=52fa080e49) | Sep 06, 2019 |
| Unknown       | 1.2                         | [e6ac162ade](https://linux-hardware.org/?probe=e6ac162ade) | Aug 27, 2019 |
| ASUSTek       | P8H61-M LE/USB3             | [d73f3f8528](https://linux-hardware.org/?probe=d73f3f8528) | Aug 22, 2019 |
| Gigabyte      | Z270P-D3-CF                 | [85ef01ba25](https://linux-hardware.org/?probe=85ef01ba25) | Aug 15, 2019 |
| Gigabyte      | Z270P-D3-CF                 | [cfc5e59508](https://linux-hardware.org/?probe=cfc5e59508) | Aug 15, 2019 |
| MSI           | X470 GAMING PRO             | [9d586233cb](https://linux-hardware.org/?probe=9d586233cb) | Aug 13, 2019 |
| ASUSTek       | H61M-A/USB3                 | [f2e8562a52](https://linux-hardware.org/?probe=f2e8562a52) | Aug 10, 2019 |
| MSI           | A75MA-P35                   | [6a11324b77](https://linux-hardware.org/?probe=6a11324b77) | Aug 04, 2019 |
| MSI           | X370 XPOWER GAMING TITAN... | [d084d64bdf](https://linux-hardware.org/?probe=d084d64bdf) | Jul 27, 2019 |
| Medion        | MS-7646                     | [0be5f7a9e8](https://linux-hardware.org/?probe=0be5f7a9e8) | Jul 26, 2019 |
| Gigabyte      | Z270P-D3-CF                 | [9a41c725f3](https://linux-hardware.org/?probe=9a41c725f3) | Jul 23, 2019 |
| HP            | 1495                        | [2d53282148](https://linux-hardware.org/?probe=2d53282148) | Jul 18, 2019 |
| HP            | 1495                        | [f63a4cd715](https://linux-hardware.org/?probe=f63a4cd715) | Jul 18, 2019 |
| ASUSTek       | P8H67                       | [7a74eb0f6f](https://linux-hardware.org/?probe=7a74eb0f6f) | Jul 16, 2019 |
| ASUSTek       | P8H67                       | [640c9f1ab7](https://linux-hardware.org/?probe=640c9f1ab7) | Jul 16, 2019 |
| ASUSTek       | P8H67                       | [9a951d161f](https://linux-hardware.org/?probe=9a951d161f) | Jul 16, 2019 |
| Medion        | H81H3-EM2                   | [98746816d9](https://linux-hardware.org/?probe=98746816d9) | Jul 04, 2019 |
| Medion        | H81H3-EM2                   | [a87ceb42ad](https://linux-hardware.org/?probe=a87ceb42ad) | Jul 04, 2019 |
| Pegatron      | Benicia                     | [719994a01b](https://linux-hardware.org/?probe=719994a01b) | Jul 01, 2019 |
| Shuttle       | XS36V                       | [cd64391dda](https://linux-hardware.org/?probe=cd64391dda) | Jun 19, 2019 |
| Acer          | Aspire TC-710 V:1.1         | [98a8d47fc0](https://linux-hardware.org/?probe=98a8d47fc0) | Jun 12, 2019 |
| ASUSTek       | A68HM-K                     | [1a2a8102fb](https://linux-hardware.org/?probe=1a2a8102fb) | Jun 02, 2019 |
| ASUSTek       | H81M-PLUS                   | [d2de9e43a6](https://linux-hardware.org/?probe=d2de9e43a6) | May 13, 2019 |
| ASUSTek       | Rampage III Extreme         | [204eddf27d](https://linux-hardware.org/?probe=204eddf27d) | May 10, 2019 |
| ASUSTek       | M5A78L-M LX3                | [0987b1062f](https://linux-hardware.org/?probe=0987b1062f) | May 09, 2019 |
| Acer          | RS880M05                    | [3cc746c01b](https://linux-hardware.org/?probe=3cc746c01b) | May 04, 2019 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [80427eb045](https://linux-hardware.org/?probe=80427eb045) | May 04, 2019 |
| ASUSTek       | P9X79                       | [e47e6eba5d](https://linux-hardware.org/?probe=e47e6eba5d) | May 02, 2019 |
| ASUSTek       | H81M-PLUS                   | [289f136d3f](https://linux-hardware.org/?probe=289f136d3f) | Apr 29, 2019 |
| ASRock        | 970 Pro3 R2.0               | [89e1c14d18](https://linux-hardware.org/?probe=89e1c14d18) | Apr 28, 2019 |
| HP            | 500-287eg                   | [92eae585a5](https://linux-hardware.org/?probe=92eae585a5) | Apr 21, 2019 |
| Lenovo        | 31900058 STD                | [1b6751d51a](https://linux-hardware.org/?probe=1b6751d51a) | Apr 16, 2019 |
| TYAN Compu... | S5120                       | [7ce7f79d09](https://linux-hardware.org/?probe=7ce7f79d09) | Apr 03, 2019 |
| Gigabyte      | Z87N-WIFI                   | [c689ce31bb](https://linux-hardware.org/?probe=c689ce31bb) | Mar 25, 2019 |
| Biostar       | GF8100 M2+ TE               | [0e4bbf6c92](https://linux-hardware.org/?probe=0e4bbf6c92) | Mar 13, 2019 |
| ASUSTek       | M4A77TD                     | [a3a5486ddc](https://linux-hardware.org/?probe=a3a5486ddc) | Mar 13, 2019 |
| Gigabyte      | Z77X-UP5 TH-CF              | [190e0fcd2a](https://linux-hardware.org/?probe=190e0fcd2a) | Mar 11, 2019 |
| HP            | 8433 11                     | [2bcad0a319](https://linux-hardware.org/?probe=2bcad0a319) | Mar 07, 2019 |
| MSI           | X470 GAMING PRO             | [040f7ac7c4](https://linux-hardware.org/?probe=040f7ac7c4) | Feb 27, 2019 |
| Acer          | Aspire XC-830               | [683ab95a31](https://linux-hardware.org/?probe=683ab95a31) | Feb 18, 2019 |
| Gigabyte      | MZBSWBP-00                  | [22bf9556b0](https://linux-hardware.org/?probe=22bf9556b0) | Feb 03, 2019 |
| Intel         | DB75EN AAG39650-302         | [1aac6deb59](https://linux-hardware.org/?probe=1aac6deb59) | Jan 31, 2019 |
| AMI           | Cherry Trail CR             | [0ad2e06845](https://linux-hardware.org/?probe=0ad2e06845) | Jan 30, 2019 |
| ASUSTek       | Z10PE-D16 WS                | [9ee9f662a8](https://linux-hardware.org/?probe=9ee9f662a8) | Jan 19, 2019 |
| ASUSTek       | Z10PE-D16 WS                | [8683e5f64d](https://linux-hardware.org/?probe=8683e5f64d) | Jan 19, 2019 |
| MSI           | 880GM-E41                   | [4b8fd34544](https://linux-hardware.org/?probe=4b8fd34544) | Jan 12, 2019 |
| ASUSTek       | X99-A                       | [5cf9372da9](https://linux-hardware.org/?probe=5cf9372da9) | Dec 29, 2018 |
| Gigabyte      | X58A-UD3R                   | [06a381a625](https://linux-hardware.org/?probe=06a381a625) | Dec 28, 2018 |
| Gigabyte      | X58A-UD3R                   | [3c1b7efac9](https://linux-hardware.org/?probe=3c1b7efac9) | Dec 28, 2018 |
| ASUSTek       | P8Z68-V PRO                 | [41f8c8c4bb](https://linux-hardware.org/?probe=41f8c8c4bb) | Dec 23, 2018 |
| MSI           | A320M PRO-M2                | [4408553bfe](https://linux-hardware.org/?probe=4408553bfe) | Dec 22, 2018 |
| MSI           | A320M PRO-M2                | [0adc826264](https://linux-hardware.org/?probe=0adc826264) | Dec 22, 2018 |
| ASRock        | H87 Pro4                    | [484cf4a1a4](https://linux-hardware.org/?probe=484cf4a1a4) | Dec 14, 2018 |
| Lenovo        | ThinkCentre M81 5048W4M     | [cc79e0559c](https://linux-hardware.org/?probe=cc79e0559c) | Dec 11, 2018 |
| Lenovo        | ThinkCentre M81 5048W4M     | [49b676468f](https://linux-hardware.org/?probe=49b676468f) | Dec 11, 2018 |
| Biostar       | A78MD                       | [ccfbf83ff8](https://linux-hardware.org/?probe=ccfbf83ff8) | Nov 25, 2018 |
| Biostar       | A78MD                       | [80cbd4570d](https://linux-hardware.org/?probe=80cbd4570d) | Nov 25, 2018 |
| HP            | 81C5 MVB                    | [e39b189386](https://linux-hardware.org/?probe=e39b189386) | Nov 24, 2018 |
| Foxconn       | G31MX Series                | [a0a7c180c5](https://linux-hardware.org/?probe=a0a7c180c5) | Nov 21, 2018 |
| MSI           | MS-7502 Fab D               | [11f6c0d362](https://linux-hardware.org/?probe=11f6c0d362) | Nov 16, 2018 |
| MSI           | MS-7502 Fab D               | [8fa6a7b89f](https://linux-hardware.org/?probe=8fa6a7b89f) | Nov 11, 2018 |
| ASRock        | H97 Anniversary             | [8fd474da8b](https://linux-hardware.org/?probe=8fd474da8b) | Nov 04, 2018 |
| ASRock        | E350M1                      | [51fb6fa87d](https://linux-hardware.org/?probe=51fb6fa87d) | Nov 01, 2018 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2fe6ddfbdf](https://linux-hardware.org/?probe=2fe6ddfbdf) | Oct 18, 2018 |
| HP            | 0A54h                       | [a30fb7b788](https://linux-hardware.org/?probe=a30fb7b788) | Oct 14, 2018 |
| ASUSTek       | PRIME Z270-A                | [b0872a1be5](https://linux-hardware.org/?probe=b0872a1be5) | Sep 17, 2018 |
| ASRock        | Z270 Gaming K6              | [a64b2acb05](https://linux-hardware.org/?probe=a64b2acb05) | Sep 07, 2018 |
| ASUSTek       | H110M-K                     | [b8488b8bd7](https://linux-hardware.org/?probe=b8488b8bd7) | Sep 07, 2018 |
| ASUSTek       | H110M-K                     | [cc813a1c15](https://linux-hardware.org/?probe=cc813a1c15) | Sep 07, 2018 |
| ASUSTek       | H110M-K                     | [2c499101d4](https://linux-hardware.org/?probe=2c499101d4) | Sep 06, 2018 |
| MSI           | X470 GAMING PRO             | [4d480c550e](https://linux-hardware.org/?probe=4d480c550e) | Sep 02, 2018 |
| MSI           | X470 GAMING PRO             | [75193022d0](https://linux-hardware.org/?probe=75193022d0) | Jul 31, 2018 |
| Intel         | Thurley                     | [e37057e69e](https://linux-hardware.org/?probe=e37057e69e) | Jun 12, 2018 |
| ASRock        | 970M Pro3                   | [c956817504](https://linux-hardware.org/?probe=c956817504) | Dec 22, 2017 |
| ASRock        | Z68 Professional Gen3       | [3e2eeae3e8](https://linux-hardware.org/?probe=3e2eeae3e8) | Jun 02, 2017 |
| ASUSTek       | F1A75-M-PRO R2.0            | [8ae18559e3](https://linux-hardware.org/?probe=8ae18559e3) | May 16, 2017 |
| MSI           | A78M-E35                    | [de8317d2c2](https://linux-hardware.org/?probe=de8317d2c2) | Apr 21, 2017 |
| Gigabyte      | F2A88XM-DS2                 | [1e5325c9d7](https://linux-hardware.org/?probe=1e5325c9d7) | Apr 09, 2017 |
| ASUSTek       | X99-A II                    | [fcf4afe5c6](https://linux-hardware.org/?probe=fcf4afe5c6) | Jan 21, 2017 |
| ECS           | A780GM-A                    | [6a2afa0d77](https://linux-hardware.org/?probe=6a2afa0d77) | Jan 03, 2017 |
| ASUSTek       | Maximus VIII EXTREME        | [f3e8817609](https://linux-hardware.org/?probe=f3e8817609) | Jul 22, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 92       | 16.97%  |
| Ubuntu 18.04                 | 57       | 10.52%  |
| OpenMandriva 4.2             | 22       | 4.06%   |
| Arch Rolling                 | 17       | 3.14%   |
| Arch                         | 17       | 3.14%   |
| OpenMandriva 4.3             | 15       | 2.77%   |
| Debian 11                    | 14       | 2.58%   |
| Ubuntu 20.10                 | 11       | 2.03%   |
| Pop!_OS 20.10                | 11       | 2.03%   |
| Ubuntu 21.04                 | 10       | 1.85%   |
| Manjaro                      | 10       | 1.85%   |
| Linux Mint 19.3              | 10       | 1.85%   |
| ROSA R11                     | 9        | 1.66%   |
| Linux Mint 20.1              | 9        | 1.66%   |
| Linux Mint 20                | 8        | 1.48%   |
| Fedora 35                    | 8        | 1.48%   |
| ROSA R10                     | 7        | 1.29%   |
| Fedora 33                    | 7        | 1.29%   |
| Fedora 32                    | 7        | 1.29%   |
| Debian 10                    | 7        | 1.29%   |
| ArcoLinux Rolling            | 7        | 1.29%   |
| Xubuntu 20.04                | 6        | 1.11%   |
| Ubuntu 18.10                 | 6        | 1.11%   |
| OpenMandriva 4.50            | 6        | 1.11%   |
| Linux Mint 20.3              | 6        | 1.11%   |
| Linux Mint 20.2              | 6        | 1.11%   |
| Pop!_OS 20.04                | 5        | 0.92%   |
| KDE neon 20.04               | 5        | 0.92%   |
| Ubuntu 22.04                 | 4        | 0.74%   |
| Ubuntu 21.10                 | 4        | 0.74%   |
| Ubuntu 19.04                 | 4        | 0.74%   |
| Linux Mint 19.1              | 4        | 0.74%   |
| Kubuntu 20.04                | 4        | 0.74%   |
| Fedora 34                    | 4        | 0.74%   |
| EndeavourOS Rolling          | 4        | 0.74%   |
| Debian Testing               | 4        | 0.74%   |
| BlackPanther 18.1            | 4        | 0.74%   |
| Zorin 16                     | 3        | 0.55%   |
| Zorin 15                     | 3        | 0.55%   |
| Ubuntu 19.10                 | 3        | 0.55%   |
| Ubuntu 16.04                 | 3        | 0.55%   |
| ROSA R8.1                    | 3        | 0.55%   |
| Pop!_OS 22.04                | 3        | 0.55%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 0.55%   |
| Linux Mint 19.2              | 3        | 0.55%   |
| Linux Mint 18.3              | 3        | 0.55%   |
| Kubuntu 18.04                | 3        | 0.55%   |
| Gentoo 2.6                   | 3        | 0.55%   |
| Fedora 31                    | 3        | 0.55%   |
| ROSA R8                      | 2        | 0.37%   |
| ROSA R11.1                   | 2        | 0.37%   |
| ROSA 12                      | 2        | 0.37%   |
| Manjaro 21.2.6               | 2        | 0.37%   |
| Manjaro 20.1                 | 2        | 0.37%   |
| Manjaro 18.1.5               | 2        | 0.37%   |
| LMDE 4                       | 2        | 0.37%   |
| Gentoo 2.7                   | 2        | 0.37%   |
| Fedora 29                    | 2        | 0.37%   |
| Elementary 6.1               | 2        | 0.37%   |
| Elementary 6                 | 2        | 0.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 193      | 36.69%  |
| Linux Mint    | 48       | 9.13%   |
| OpenMandriva  | 43       | 8.17%   |
| Arch          | 34       | 6.46%   |
| Debian        | 27       | 5.13%   |
| Fedora        | 26       | 4.94%   |
| Manjaro       | 24       | 4.56%   |
| ROSA          | 23       | 4.37%   |
| Pop!_OS       | 21       | 3.99%   |
| Kubuntu       | 12       | 2.28%   |
| Xubuntu       | 8        | 1.52%   |
| ArcoLinux     | 8        | 1.52%   |
| Zorin         | 6        | 1.14%   |
| KDE neon      | 6        | 1.14%   |
| Gentoo        | 5        | 0.95%   |
| Elementary    | 5        | 0.95%   |
| openSUSE      | 4        | 0.76%   |
| EndeavourOS   | 4        | 0.76%   |
| BlackPanther  | 4        | 0.76%   |
| Ubuntu MATE   | 3        | 0.57%   |
| Clear Linux   | 3        | 0.57%   |
| Parrot        | 2        | 0.38%   |
| NixOS         | 2        | 0.38%   |
| LMDE          | 2        | 0.38%   |
| Endless       | 2        | 0.38%   |
| Xero          | 1        | 0.19%   |
| UbuntuDDE     | 1        | 0.19%   |
| Ubuntu Studio | 1        | 0.19%   |
| Siduction     | 1        | 0.19%   |
| RHEL          | 1        | 0.19%   |
| Reborn OS     | 1        | 0.19%   |
| MX            | 1        | 0.19%   |
| Lubuntu       | 1        | 0.19%   |
| Deepin        | 1        | 0.19%   |
| Artix         | 1        | 0.19%   |
| Alpine        | 1        | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 21       | 3.47%   |
| 5.16.7-desktop-1omv4003         | 15       | 2.48%   |
| 5.4.0-42-generic                | 11       | 1.82%   |
| 5.4.0-58-generic                | 8        | 1.32%   |
| 5.4.0-52-generic                | 7        | 1.16%   |
| 5.4.0-28-generic                | 7        | 1.16%   |
| 5.8.0-7630-generic              | 6        | 0.99%   |
| 5.4.0-33-generic                | 6        | 0.99%   |
| 5.13.0-39-generic               | 6        | 0.99%   |
| 4.15.0-desktop-60.7rosa-x86_64  | 6        | 0.99%   |
| 5.4.0-80-generic                | 5        | 0.83%   |
| 5.4.0-72-generic                | 5        | 0.83%   |
| 5.4.0-48-generic                | 5        | 0.83%   |
| 5.12.4-desktop-1omv4050         | 5        | 0.83%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5        | 0.83%   |
| 4.18.0-15-generic               | 5        | 0.83%   |
| 5.8.0-44-generic                | 4        | 0.66%   |
| 5.8.0-41-generic                | 4        | 0.66%   |
| 5.4.0-89-generic                | 4        | 0.66%   |
| 5.4.0-74-generic                | 4        | 0.66%   |
| 5.4.0-71-generic                | 4        | 0.66%   |
| 5.4.0-67-generic                | 4        | 0.66%   |
| 5.4.0-65-generic                | 4        | 0.66%   |
| 5.4.0-40-generic                | 4        | 0.66%   |
| 5.3.0-46-generic                | 4        | 0.66%   |
| 5.13.0-30-generic               | 4        | 0.66%   |
| 5.13.0-27-generic               | 4        | 0.66%   |
| 5.11.0-22-generic               | 4        | 0.66%   |
| 5.10.0-9-amd64                  | 4        | 0.66%   |
| 4.18.16-desktop-1bP             | 4        | 0.66%   |
| 4.15.0-66-generic               | 4        | 0.66%   |
| 4.15.0-54-generic               | 4        | 0.66%   |
| 5.8.0-7642-generic              | 3        | 0.5%    |
| 5.8.0-43-generic                | 3        | 0.5%    |
| 5.8.0-36-generic                | 3        | 0.5%    |
| 5.4.0-91-generic                | 3        | 0.5%    |
| 5.4.0-77-generic                | 3        | 0.5%    |
| 5.4.0-70-generic                | 3        | 0.5%    |
| 5.4.0-53-generic                | 3        | 0.5%    |
| 5.4.0-45-generic                | 3        | 0.5%    |
| 5.13.0-35-generic               | 3        | 0.5%    |
| 5.11.0-40-generic               | 3        | 0.5%    |
| 5.11.0-37-generic               | 3        | 0.5%    |
| 5.11.0-34-generic               | 3        | 0.5%    |
| 5.11.0-27-generic               | 3        | 0.5%    |
| 5.11.0-25-generic               | 3        | 0.5%    |
| 5.10.0-8-amd64                  | 3        | 0.5%    |
| 4.18.0-18-generic               | 3        | 0.5%    |
| 4.15.0-38-generic               | 3        | 0.5%    |
| 5.9.16-200.fc33.x86_64          | 2        | 0.33%   |
| 5.9.16-1-MANJARO                | 2        | 0.33%   |
| 5.9.14-arch1-1                  | 2        | 0.33%   |
| 5.9.11-arch2-1                  | 2        | 0.33%   |
| 5.9.0-1-amd64                   | 2        | 0.33%   |
| 5.8.6-1-MANJARO                 | 2        | 0.33%   |
| 5.8.4-200.fc32.x86_64           | 2        | 0.33%   |
| 5.8.0-7625-generic              | 2        | 0.33%   |
| 5.8.0-59-generic                | 2        | 0.33%   |
| 5.8.0-55-generic                | 2        | 0.33%   |
| 5.8.0-50-generic                | 2        | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 113      | 20.04%  |
| 4.15.0  | 50       | 8.87%   |
| 5.8.0   | 36       | 6.38%   |
| 5.11.0  | 32       | 5.67%   |
| 5.13.0  | 27       | 4.79%   |
| 5.10.14 | 22       | 3.9%    |
| 4.18.0  | 17       | 3.01%   |
| 5.16.7  | 16       | 2.84%   |
| 5.3.0   | 15       | 2.66%   |
| 5.10.0  | 13       | 2.3%    |
| 5.0.0   | 10       | 1.77%   |
| 4.19.0  | 7        | 1.24%   |
| 5.15.0  | 6        | 1.06%   |
| 5.12.4  | 6        | 1.06%   |
| 4.9.60  | 5        | 0.89%   |
| 5.9.16  | 4        | 0.71%   |
| 5.9.11  | 4        | 0.71%   |
| 5.17.5  | 4        | 0.71%   |
| 5.16.0  | 4        | 0.71%   |
| 4.4.0   | 4        | 0.71%   |
| 4.18.16 | 4        | 0.71%   |
| 5.8.13  | 3        | 0.53%   |
| 5.15.6  | 3        | 0.53%   |
| 5.9.14  | 2        | 0.35%   |
| 5.9.0   | 2        | 0.35%   |
| 5.8.9   | 2        | 0.35%   |
| 5.8.6   | 2        | 0.35%   |
| 5.8.4   | 2        | 0.35%   |
| 5.8.14  | 2        | 0.35%   |
| 5.6.7   | 2        | 0.35%   |
| 5.5.0   | 2        | 0.35%   |
| 5.4.43  | 2        | 0.35%   |
| 5.4.28  | 2        | 0.35%   |
| 5.4.15  | 2        | 0.35%   |
| 5.17.9  | 2        | 0.35%   |
| 5.17.0  | 2        | 0.35%   |
| 5.16.2  | 2        | 0.35%   |
| 5.16.18 | 2        | 0.35%   |
| 5.15.43 | 2        | 0.35%   |
| 5.15.15 | 2        | 0.35%   |
| 5.14.9  | 2        | 0.35%   |
| 5.13.6  | 2        | 0.35%   |
| 5.12.0  | 2        | 0.35%   |
| 5.11.12 | 2        | 0.35%   |
| 5.10.71 | 2        | 0.35%   |
| 5.10.42 | 2        | 0.35%   |
| 5.10.16 | 2        | 0.35%   |
| 4.10.0  | 2        | 0.35%   |
| 4.1.38  | 2        | 0.35%   |
| 4.1.34  | 2        | 0.35%   |
| 5.9.9   | 1        | 0.18%   |
| 5.9.6   | 1        | 0.18%   |
| 5.9.10  | 1        | 0.18%   |
| 5.9.1   | 1        | 0.18%   |
| 5.8.18  | 1        | 0.18%   |
| 5.8.16  | 1        | 0.18%   |
| 5.8.15  | 1        | 0.18%   |
| 5.8.12  | 1        | 0.18%   |
| 5.8.11  | 1        | 0.18%   |
| 5.7.6   | 1        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 132      | 23.74%  |
| 5.8     | 51       | 9.17%   |
| 5.10    | 50       | 8.99%   |
| 4.15    | 50       | 8.99%   |
| 5.11    | 42       | 7.55%   |
| 5.13    | 33       | 5.94%   |
| 5.16    | 26       | 4.68%   |
| 5.15    | 23       | 4.14%   |
| 4.18    | 23       | 4.14%   |
| 5.3     | 17       | 3.06%   |
| 5.12    | 17       | 3.06%   |
| 5.9     | 15       | 2.7%    |
| 5.17    | 11       | 1.98%   |
| 5.0     | 10       | 1.8%    |
| 4.9     | 10       | 1.8%    |
| 4.19    | 9        | 1.62%   |
| 5.6     | 6        | 1.08%   |
| 5.14    | 6        | 1.08%   |
| 5.7     | 4        | 0.72%   |
| 5.5     | 4        | 0.72%   |
| 5.18    | 4        | 0.72%   |
| 4.4     | 4        | 0.72%   |
| 4.1     | 4        | 0.72%   |
| 4.10    | 2        | 0.36%   |
| 4.6     | 1        | 0.18%   |
| 4.12    | 1        | 0.18%   |
| 3.10    | 1        | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 511      | 98.84%  |
| i686   | 6        | 1.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 200      | 37.38%  |
| Unknown       | 95       | 17.76%  |
| KDE5          | 91       | 17.01%  |
| XFCE          | 41       | 7.66%   |
| X-Cinnamon    | 36       | 6.73%   |
| KDE           | 17       | 3.18%   |
| KDE4          | 13       | 2.43%   |
| MATE          | 12       | 2.24%   |
| Pantheon      | 5        | 0.93%   |
| Cinnamon      | 5        | 0.93%   |
| Unity         | 3        | 0.56%   |
| LXQt          | 3        | 0.56%   |
| i3            | 3        | 0.56%   |
| xmonad        | 2        | 0.37%   |
| Deepin        | 2        | 0.37%   |
| Budgie        | 2        | 0.37%   |
| awesome       | 2        | 0.37%   |
| sway          | 1        | 0.19%   |
| leftwm        | 1        | 0.19%   |
| GNOME Classic | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 418      | 79.02%  |
| Unknown | 52       | 9.83%   |
| Wayland | 38       | 7.18%   |
| Tty     | 21       | 3.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 282      | 53.11%  |
| SDDM    | 90       | 16.95%  |
| GDM     | 50       | 9.42%   |
| LightDM | 39       | 7.34%   |
| GDM3    | 31       | 5.84%   |
| TDM     | 21       | 3.95%   |
| KDM     | 14       | 2.64%   |
| SLiM    | 2        | 0.38%   |
| XDM     | 1        | 0.19%   |
| LXDM    | 1        | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| de_AT      | 207      | 39.35%  |
| en_US      | 120      | 22.81%  |
| Unknown    | 92       | 17.49%  |
| de_DE      | 71       | 13.5%   |
| en_GB      | 13       | 2.47%   |
| C          | 6        | 1.14%   |
| en_IE      | 5        | 0.95%   |
| pl_PL      | 3        | 0.57%   |
| ru_RU      | 2        | 0.38%   |
| it_IT      | 2        | 0.38%   |
| tr_TR      | 1        | 0.19%   |
| hu_HU      | 1        | 0.19%   |
| fa_IR      | 1        | 0.19%   |
| en_US.UTF8 | 1        | 0.19%   |
| de_AT.UTF8 | 1        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 288      | 54.44%  |
| EFI  | 241      | 45.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 400      | 76.48%  |
| Overlay | 49       | 9.37%   |
| Btrfs   | 34       | 6.5%    |
| Unknown | 26       | 4.97%   |
| Xfs     | 5        | 0.96%   |
| Zfs     | 4        | 0.76%   |
| Ext2    | 3        | 0.57%   |
| Tmpfs   | 1        | 0.19%   |
| F2fs    | 1        | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 297      | 56.68%  |
| GPT     | 177      | 33.78%  |
| MBR     | 50       | 9.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 409      | 77.32%  |
| Yes       | 120      | 22.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 327      | 61.93%  |
| Yes       | 201      | 38.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 161      | 31.14%  |
| MSI                 | 85       | 16.44%  |
| ASRock              | 68       | 13.15%  |
| Gigabyte Technology | 62       | 11.99%  |
| Hewlett-Packard     | 36       | 6.96%   |
| Lenovo              | 23       | 4.45%   |
| Medion              | 16       | 3.09%   |
| Acer                | 14       | 2.71%   |
| Dell                | 12       | 2.32%   |
| Intel               | 6        | 1.16%   |
| Biostar             | 6        | 1.16%   |
| Fujitsu             | 5        | 0.97%   |
| Unknown             | 4        | 0.77%   |
| Foxconn             | 3        | 0.58%   |
| Shuttle             | 2        | 0.39%   |
| Sapphire            | 2        | 0.39%   |
| Pegatron            | 2        | 0.39%   |
| ECS                 | 2        | 0.39%   |
| TYAN Computer       | 1        | 0.19%   |
| Packard Bell        | 1        | 0.19%   |
| IBM                 | 1        | 0.19%   |
| Fujitsu Siemens     | 1        | 0.19%   |
| BESSTAR Tech        | 1        | 0.19%   |
| AZW                 | 1        | 0.19%   |
| ASRockRack          | 1        | 0.19%   |
| AMI                 | 1        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 23       | 4.45%   |
| MSI MS-7C37                          | 8        | 1.55%   |
| MSI MS-7B79                          | 6        | 1.16%   |
| ASRock Z87 Killer                    | 6        | 1.16%   |
| MSI MS-7B86                          | 5        | 0.97%   |
| ASUS ROG STRIX B450-F GAMING         | 5        | 0.97%   |
| MSI MS-7C91                          | 4        | 0.77%   |
| ASUS ROG STRIX B550-I GAMING         | 4        | 0.77%   |
| Unknown                              | 4        | 0.77%   |
| MSI MS-7971                          | 3        | 0.58%   |
| MSI MS-7817                          | 3        | 0.58%   |
| MSI MS-7721                          | 3        | 0.58%   |
| Medion MS-7800                       | 3        | 0.58%   |
| Medion MS-7707                       | 3        | 0.58%   |
| HP Z800 Workstation                  | 3        | 0.58%   |
| HP Compaq 8100 Elite CMT PC          | 3        | 0.58%   |
| ASUS TUF Gaming B550-PLUS            | 3        | 0.58%   |
| ASUS SABERTOOTH 990FX R2.0           | 3        | 0.58%   |
| ASUS PRIME B450-PLUS                 | 3        | 0.58%   |
| ASUS PRIME A320M-K                   | 3        | 0.58%   |
| ASUS P8H77-M PRO                     | 3        | 0.58%   |
| ASRock 970 Pro3 R2.0                 | 3        | 0.58%   |
| Pegatron FZ116AA-ACP a6551.at        | 2        | 0.39%   |
| MSI MS-7C35                          | 2        | 0.39%   |
| MSI MS-7C02                          | 2        | 0.39%   |
| MSI MS-7B89                          | 2        | 0.39%   |
| MSI MS-7B85                          | 2        | 0.39%   |
| MSI MS-7A38                          | 2        | 0.39%   |
| MSI MS-7821                          | 2        | 0.39%   |
| MSI MS-7693                          | 2        | 0.39%   |
| MSI MS-7502                          | 2        | 0.39%   |
| Medion MS-7728                       | 2        | 0.39%   |
| Lenovo ThinkCentre M93p 10A8S0CE11   | 2        | 0.39%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 2        | 0.39%   |
| HP EliteDesk 800 G1 SFF              | 2        | 0.39%   |
| HP Compaq Elite 8300 SFF             | 2        | 0.39%   |
| HP Compaq 8200 Elite SFF PC          | 2        | 0.39%   |
| HP Compaq 8200 Elite CMT PC          | 2        | 0.39%   |
| Gigabyte X570 AORUS PRO              | 2        | 0.39%   |
| Gigabyte X570 AORUS MASTER           | 2        | 0.39%   |
| Gigabyte B450M S2H                   | 2        | 0.39%   |
| Gigabyte 990FXA-UD3                  | 2        | 0.39%   |
| Gigabyte 970A-UD3                    | 2        | 0.39%   |
| Biostar A78MD                        | 2        | 0.39%   |
| Biostar A10N-8800E                   | 2        | 0.39%   |
| ASUS Z170I PRO GAMING                | 2        | 0.39%   |
| ASUS Z170-A                          | 2        | 0.39%   |
| ASUS SABERTOOTH X79                  | 2        | 0.39%   |
| ASUS ROG STRIX B550-F GAMING         | 2        | 0.39%   |
| ASUS Rampage IV EXTREME              | 2        | 0.39%   |
| ASUS PRIME Z270-A                    | 2        | 0.39%   |
| ASUS PRIME X570-P                    | 2        | 0.39%   |
| ASUS PRIME X299-DELUXE II            | 2        | 0.39%   |
| ASUS PRIME A320I-K                   | 2        | 0.39%   |
| ASUS P9X79                           | 2        | 0.39%   |
| ASUS P8H67                           | 2        | 0.39%   |
| ASUS P6T SE                          | 2        | 0.39%   |
| ASUS Maximus VIII RANGER             | 2        | 0.39%   |
| ASUS M5A99X EVO                      | 2        | 0.39%   |
| ASUS M5A78L-M PLUS/USB3              | 2        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS All             | 23       | 4.45%   |
| ASUS PRIME           | 22       | 4.26%   |
| ASUS ROG             | 20       | 3.87%   |
| Lenovo ThinkCentre   | 15       | 2.9%    |
| HP Compaq            | 14       | 2.71%   |
| ASUS TUF             | 10       | 1.93%   |
| MSI MS-7C37          | 8        | 1.55%   |
| Dell OptiPlex        | 8        | 1.55%   |
| ASUS SABERTOOTH      | 7        | 1.35%   |
| ASRock Z87           | 7        | 1.35%   |
| MSI MS-7B79          | 6        | 1.16%   |
| Gigabyte X570        | 6        | 1.16%   |
| Acer Aspire          | 6        | 1.16%   |
| MSI MS-7B86          | 5        | 0.97%   |
| ASUS M5A78L-M        | 5        | 0.97%   |
| ASRock 970           | 5        | 0.97%   |
| MSI MS-7C91          | 4        | 0.77%   |
| HP Pavilion          | 4        | 0.77%   |
| Gigabyte Z390        | 4        | 0.77%   |
| ASUS Rampage         | 4        | 0.77%   |
| ASRock Z170          | 4        | 0.77%   |
| Acer Veriton         | 4        | 0.77%   |
| Unknown              | 4        | 0.77%   |
| MSI MS-7971          | 3        | 0.58%   |
| MSI MS-7817          | 3        | 0.58%   |
| MSI MS-7721          | 3        | 0.58%   |
| Medion MS-7800       | 3        | 0.58%   |
| Medion MS-7707       | 3        | 0.58%   |
| Lenovo ThinkStation  | 3        | 0.58%   |
| Lenovo IdeaCentre    | 3        | 0.58%   |
| HP Z800              | 3        | 0.58%   |
| HP EliteDesk         | 3        | 0.58%   |
| Gigabyte B550        | 3        | 0.58%   |
| Gigabyte B450M       | 3        | 0.58%   |
| ASUS P9X79           | 3        | 0.58%   |
| ASUS P8H77-M         | 3        | 0.58%   |
| ASUS P6T             | 3        | 0.58%   |
| ASUS Maximus         | 3        | 0.58%   |
| ASUS M5A97           | 3        | 0.58%   |
| ASRock X570          | 3        | 0.58%   |
| ASRock X470          | 3        | 0.58%   |
| Pegatron FZ116AA-ACP | 2        | 0.39%   |
| MSI MS-7C35          | 2        | 0.39%   |
| MSI MS-7C02          | 2        | 0.39%   |
| MSI MS-7B89          | 2        | 0.39%   |
| MSI MS-7B85          | 2        | 0.39%   |
| MSI MS-7A38          | 2        | 0.39%   |
| MSI MS-7821          | 2        | 0.39%   |
| MSI MS-7693          | 2        | 0.39%   |
| MSI MS-7502          | 2        | 0.39%   |
| Medion MS-7728       | 2        | 0.39%   |
| Medion Akoya         | 2        | 0.39%   |
| HP ProLiant          | 2        | 0.39%   |
| HP ProDesk           | 2        | 0.39%   |
| Gigabyte Z590        | 2        | 0.39%   |
| Gigabyte B450        | 2        | 0.39%   |
| Gigabyte 990FXA-UD3  | 2        | 0.39%   |
| Gigabyte 970A-UD3    | 2        | 0.39%   |
| Fujitsu ESPRIMO      | 2        | 0.39%   |
| Biostar A78MD        | 2        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 67       | 12.96%  |
| 2013 | 58       | 11.22%  |
| 2019 | 56       | 10.83%  |
| 2012 | 46       | 8.9%    |
| 2020 | 43       | 8.32%   |
| 2011 | 41       | 7.93%   |
| 2010 | 31       | 6%      |
| 2014 | 29       | 5.61%   |
| 2015 | 26       | 5.03%   |
| 2016 | 25       | 4.84%   |
| 2017 | 24       | 4.64%   |
| 2009 | 23       | 4.45%   |
| 2021 | 15       | 2.9%    |
| 2007 | 14       | 2.71%   |
| 2008 | 10       | 1.93%   |
| 2006 | 6        | 1.16%   |
| 2022 | 2        | 0.39%   |
| 2005 | 1        | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 517      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 504      | 97.11%  |
| Enabled  | 15       | 2.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 517      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 138      | 26.44%  |
| 8.01-16.0       | 105      | 20.11%  |
| 32.01-64.0      | 102      | 19.54%  |
| 4.01-8.0        | 67       | 12.84%  |
| 3.01-4.0        | 56       | 10.73%  |
| 64.01-256.0     | 22       | 4.21%   |
| 24.01-32.0      | 17       | 3.26%   |
| 1.01-2.0        | 6        | 1.15%   |
| More than 256.0 | 4        | 0.77%   |
| 2.01-3.0        | 3        | 0.57%   |
| 0.51-1.0        | 1        | 0.19%   |
| Unknown         | 1        | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 192      | 34.04%  |
| 2.01-3.0   | 133      | 23.58%  |
| 4.01-8.0   | 85       | 15.07%  |
| 3.01-4.0   | 67       | 11.88%  |
| 8.01-16.0  | 40       | 7.09%   |
| 0.51-1.0   | 28       | 4.96%   |
| 0.01-0.5   | 8        | 1.42%   |
| 16.01-24.0 | 6        | 1.06%   |
| 32.01-64.0 | 2        | 0.35%   |
| 24.01-32.0 | 2        | 0.35%   |
| Unknown    | 1        | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 178      | 32.78%  |
| 2      | 153      | 28.18%  |
| 3      | 102      | 18.78%  |
| 4      | 55       | 10.13%  |
| 5      | 22       | 4.05%   |
| 6      | 13       | 2.39%   |
| 9      | 8        | 1.47%   |
| 7      | 6        | 1.1%    |
| 10     | 2        | 0.37%   |
| 8      | 2        | 0.37%   |
| 11     | 1        | 0.18%   |
| 0      | 1        | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 284      | 54.51%  |
| No        | 237      | 45.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 514      | 99.42%  |
| No        | 3        | 0.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 312      | 59.77%  |
| Yes       | 210      | 40.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 364      | 70%     |
| Yes       | 156      | 30%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Austria | 517      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Vienna              | 284      | 52.89%  |
| Graz                | 32       | 5.96%   |
| Linz                | 17       | 3.17%   |
| Innsbruck           | 15       | 2.79%   |
| Bad Hall            | 11       | 2.05%   |
| Salzburg            | 10       | 1.86%   |
| Dornbirn            | 9        | 1.68%   |
| Sankt Pölten       | 8        | 1.49%   |
| Klagenfurt          | 6        | 1.12%   |
| Wels                | 5        | 0.93%   |
| Wiener Neustadt     | 4        | 0.74%   |
| Steyr               | 4        | 0.74%   |
| Zell am See         | 3        | 0.56%   |
| Voecklabruck        | 3        | 0.56%   |
| Klosterneuburg      | 3        | 0.56%   |
| Horn                | 3        | 0.56%   |
| Hallein             | 3        | 0.56%   |
| Brunn am Gebirge    | 3        | 0.56%   |
| Villach             | 2        | 0.37%   |
| Traunkirchen        | 2        | 0.37%   |
| Seiersberg          | 2        | 0.37%   |
| Schwechat           | 2        | 0.37%   |
| Sankt Valentin      | 2        | 0.37%   |
| Ried im Innkreis    | 2        | 0.37%   |
| Perg                | 2        | 0.37%   |
| Perchtoldsdorf      | 2        | 0.37%   |
| Neunkirchen         | 2        | 0.37%   |
| Feldkirch           | 2        | 0.37%   |
| Ernsthofen          | 2        | 0.37%   |
| Wörgl              | 1        | 0.19%   |
| Walding             | 1        | 0.19%   |
| Wagna               | 1        | 0.19%   |
| Voitsberg           | 1        | 0.19%   |
| Unterweissenbach    | 1        | 0.19%   |
| Unterpremstaetten   | 1        | 0.19%   |
| Unterpetersdorf     | 1        | 0.19%   |
| Trasdorf            | 1        | 0.19%   |
| Telfs               | 1        | 0.19%   |
| Telfes im Stubai    | 1        | 0.19%   |
| Taxerhof Lake       | 1        | 0.19%   |
| Tattendorf          | 1        | 0.19%   |
| Strasswalchen       | 1        | 0.19%   |
| Stockerau           | 1        | 0.19%   |
| Steinhaus           | 1        | 0.19%   |
| Stadl-Traun         | 1        | 0.19%   |
| St Johann im Pongau | 1        | 0.19%   |
| Spittal an der Drau | 1        | 0.19%   |
| Sigless             | 1        | 0.19%   |
| Schoerfling         | 1        | 0.19%   |
| Schaerding          | 1        | 0.19%   |
| Sarasdorf           | 1        | 0.19%   |
| Rossleithen         | 1        | 0.19%   |
| Rietz               | 1        | 0.19%   |
| Rein                | 1        | 0.19%   |
| Radstadt            | 1        | 0.19%   |
| Prinzersdorf        | 1        | 0.19%   |
| Pressbaum           | 1        | 0.19%   |
| Polling im Innkreis | 1        | 0.19%   |
| Poechlarn           | 1        | 0.19%   |
| Plosdorf            | 1        | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 222      | 356    | 22.11%  |
| WDC                       | 162      | 259    | 16.14%  |
| Seagate                   | 162      | 240    | 16.14%  |
| SanDisk                   | 89       | 124    | 8.86%   |
| Crucial                   | 52       | 81     | 5.18%   |
| Toshiba                   | 47       | 89     | 4.68%   |
| Kingston                  | 47       | 57     | 4.68%   |
| Intel                     | 22       | 32     | 2.19%   |
| Hitachi                   | 21       | 23     | 2.09%   |
| Intenso                   | 15       | 20     | 1.49%   |
| Phison                    | 14       | 20     | 1.39%   |
| Unknown                   | 13       | 25     | 1.29%   |
| HGST                      | 11       | 18     | 1.1%    |
| A-DATA Technology         | 11       | 14     | 1.1%    |
| Micron Technology         | 9        | 10     | 0.9%    |
| Transcend                 | 8        | 9      | 0.8%    |
| OCZ                       | 8        | 15     | 0.8%    |
| Corsair                   | 8        | 11     | 0.8%    |
| Micron/Crucial Technology | 5        | 7      | 0.5%    |
| China                     | 5        | 6      | 0.5%    |
| Silicon Motion            | 4        | 5      | 0.4%    |
| Maxtor                    | 4        | 4      | 0.4%    |
| ASMT                      | 4        | 10     | 0.4%    |
| Apacer                    | 4        | 5      | 0.4%    |
| SK hynix                  | 3        | 6      | 0.3%    |
| Patriot                   | 3        | 3      | 0.3%    |
| KIOXIA                    | 3        | 7      | 0.3%    |
| SPCC                      | 2        | 7      | 0.2%    |
| SABRENT                   | 2        | 3      | 0.2%    |
| PNY                       | 2        | 2      | 0.2%    |
| Plextor                   | 2        | 2      | 0.2%    |
| LITEON                    | 2        | 2      | 0.2%    |
| JMicron Technology        | 2        | 5      | 0.2%    |
| Goodram                   | 2        | 2      | 0.2%    |
| Gigabyte Technology       | 2        | 3      | 0.2%    |
| WDC WDS2                  | 1        | 1      | 0.1%    |
| WD MediaMax               | 1        | 1      | 0.1%    |
| ViperTeq                  | 1        | 4      | 0.1%    |
| VERICO                    | 1        | 1      | 0.1%    |
| Verbatim                  | 1        | 1      | 0.1%    |
| V7                        | 1        | 1      | 0.1%    |
| USB3.1                    | 1        | 2      | 0.1%    |
| TSA                       | 1        | 1      | 0.1%    |
| TrekStor                  | 1        | 1      | 0.1%    |
| TO Exter                  | 1        | 3      | 0.1%    |
| Team                      | 1        | 1      | 0.1%    |
| TCSUNBOW                  | 1        | 1      | 0.1%    |
| T-FORCE                   | 1        | 1      | 0.1%    |
| Synology                  | 1        | 8      | 0.1%    |
| Realtek Semiconductor     | 1        | 1      | 0.1%    |
| OCZ-VERTEX3               | 1        | 1      | 0.1%    |
| NGFF                      | 1        | 1      | 0.1%    |
| Magnetic Data             | 1        | 1      | 0.1%    |
| LITEONIT                  | 1        | 1      | 0.1%    |
| Lite-On                   | 1        | 1      | 0.1%    |
| Lexar                     | 1        | 2      | 0.1%    |
| KingSpec                  | 1        | 1      | 0.1%    |
| KingDian                  | 1        | 1      | 0.1%    |
| INNOVATION IT             | 1        | 1      | 0.1%    |
| HUAWEI                    | 1        | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB              | 16       | 1.36%   |
| Samsung SSD 850 EVO 250GB              | 16       | 1.36%   |
| Seagate Expansion 1TB                  | 15       | 1.27%   |
| Samsung SSD 860 EVO 500GB              | 14       | 1.19%   |
| Samsung SSD 860 EVO 1TB                | 13       | 1.1%    |
| Samsung SSD 840 EVO 250GB              | 13       | 1.1%    |
| Samsung SSD 850 PRO 256GB              | 11       | 0.93%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 11       | 0.93%   |
| Toshiba DT01ACA200 2TB                 | 10       | 0.85%   |
| SanDisk SSD PLUS 240GB                 | 10       | 0.85%   |
| Toshiba HDWD110 1TB                    | 9        | 0.76%   |
| Toshiba DT01ACA100 1TB                 | 8        | 0.68%   |
| Seagate ST31000528AS 1TB               | 8        | 0.68%   |
| SanDisk SSD PLUS 480GB                 | 8        | 0.68%   |
| SanDisk SSD PLUS 1000GB                | 8        | 0.68%   |
| Samsung SSD 860 EVO 250GB              | 8        | 0.68%   |
| Samsung HD103SJ 1TB                    | 8        | 0.68%   |
| Crucial CT500MX500SSD1 500GB           | 8        | 0.68%   |
| WDC WD30EFRX-68EUZN0 3TB               | 7        | 0.59%   |
| WDC WD10EADS-22M2B0 1TB                | 7        | 0.59%   |
| Unknown SD/MMC/MS PRO 128GB            | 7        | 0.59%   |
| Seagate ST4000DM000-1F2168 4TB         | 7        | 0.59%   |
| Seagate ST2000DM008-2FR102 2TB         | 7        | 0.59%   |
| SanDisk SDSSDH3 1T00 1TB               | 7        | 0.59%   |
| SanDisk NVMe SSD Drive 1TB             | 7        | 0.59%   |
| Samsung SSD 970 EVO Plus 1TB           | 7        | 0.59%   |
| Crucial CT1000MX500SSD1 1TB            | 7        | 0.59%   |
| WDC WD20EZRX-00D8PB0 2TB               | 6        | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB         | 6        | 0.51%   |
| SanDisk SDSSDA240G 240GB               | 6        | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB         | 6        | 0.51%   |
| Samsung SSD 860 QVO 1TB                | 6        | 0.51%   |
| Samsung NVMe SSD Drive 1TB             | 6        | 0.51%   |
| Samsung HD501LJ 500GB                  | 6        | 0.51%   |
| Kingston SA400S37240G 240GB SSD        | 6        | 0.51%   |
| Crucial CT250BX100SSD1 250GB           | 6        | 0.51%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 5        | 0.42%   |
| WDC WD20EARX-00PASB0 2TB               | 5        | 0.42%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 5        | 0.42%   |
| Seagate ST4000VN008-2DR166 4TB         | 5        | 0.42%   |
| Seagate ST1000DM010-2EP102 1TB         | 5        | 0.42%   |
| Seagate ST1000DM003-1CH162 1TB         | 5        | 0.42%   |
| SanDisk SD6SF1M128G1022I 128GB SSD     | 5        | 0.42%   |
| SanDisk Extreme SSD 1TB                | 5        | 0.42%   |
| Samsung SSD 980 PRO 1TB                | 5        | 0.42%   |
| Samsung SSD 850 EVO 120GB              | 5        | 0.42%   |
| Samsung SSD 840 PRO Series 128GB       | 5        | 0.42%   |
| Samsung HD154UI 1TB                    | 5        | 0.42%   |
| Kingston SA400S37120G 120GB SSD        | 5        | 0.42%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 4        | 0.34%   |
| WDC WD40EFRX-68WT0N0 4TB               | 4        | 0.34%   |
| WDC WD20EZRZ-00Z5HB0 2TB               | 4        | 0.34%   |
| Seagate ST8000DM004-2CX188 8TB         | 4        | 0.34%   |
| Seagate ST4000DM004-2CV104 4TB         | 4        | 0.34%   |
| Seagate ST2000DM001-1CH164 2TB         | 4        | 0.34%   |
| Seagate Expansion+ Desk 4TB            | 4        | 0.34%   |
| SanDisk Ultra II 480GB SSD             | 4        | 0.34%   |
| SanDisk SDSSDA480G 480GB               | 4        | 0.34%   |
| Samsung SSD 980 1TB                    | 4        | 0.34%   |
| Samsung SSD 970 EVO 250GB              | 4        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 157      | 231    | 35.84%  |
| WDC                 | 144      | 231    | 32.88%  |
| Toshiba             | 47       | 88     | 10.73%  |
| Samsung Electronics | 37       | 52     | 8.45%   |
| Hitachi             | 21       | 23     | 4.79%   |
| HGST                | 11       | 18     | 2.51%   |
| Unknown             | 8        | 13     | 1.83%   |
| Maxtor              | 4        | 4      | 0.91%   |
| ASMT                | 3        | 4      | 0.68%   |
| Intenso             | 2        | 2      | 0.46%   |
| WD MediaMax         | 1        | 1      | 0.23%   |
| Synology            | 1        | 8      | 0.23%   |
| JMicron Technology  | 1        | 3      | 0.23%   |
| Hewlett-Packard     | 1        | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 144      | 206    | 34.04%  |
| SanDisk             | 77       | 108    | 18.2%   |
| Crucial             | 47       | 69     | 11.11%  |
| Kingston            | 40       | 45     | 9.46%   |
| Intel               | 13       | 19     | 3.07%   |
| Intenso             | 11       | 16     | 2.6%    |
| WDC                 | 10       | 12     | 2.36%   |
| Transcend           | 8        | 9      | 1.89%   |
| OCZ                 | 8        | 15     | 1.89%   |
| Micron Technology   | 7        | 8      | 1.65%   |
| A-DATA Technology   | 7        | 9      | 1.65%   |
| Corsair             | 6        | 6      | 1.42%   |
| China               | 5        | 6      | 1.18%   |
| Apacer              | 4        | 4      | 0.95%   |
| SK hynix            | 2        | 5      | 0.47%   |
| Plextor             | 2        | 2      | 0.47%   |
| Patriot             | 2        | 2      | 0.47%   |
| LITEON              | 2        | 2      | 0.47%   |
| Goodram             | 2        | 2      | 0.47%   |
| WDC WDS2            | 1        | 1      | 0.24%   |
| ViperTeq            | 1        | 4      | 0.24%   |
| VERICO              | 1        | 1      | 0.24%   |
| Verbatim            | 1        | 1      | 0.24%   |
| V7                  | 1        | 1      | 0.24%   |
| TSA                 | 1        | 1      | 0.24%   |
| TO Exter            | 1        | 3      | 0.24%   |
| Team                | 1        | 1      | 0.24%   |
| TCSUNBOW            | 1        | 1      | 0.24%   |
| T-FORCE             | 1        | 1      | 0.24%   |
| SPCC                | 1        | 1      | 0.24%   |
| Seagate             | 1        | 1      | 0.24%   |
| PNY                 | 1        | 1      | 0.24%   |
| Phison              | 1        | 2      | 0.24%   |
| OCZ-VERTEX3         | 1        | 1      | 0.24%   |
| NGFF                | 1        | 1      | 0.24%   |
| LITEONIT            | 1        | 1      | 0.24%   |
| KingSpec            | 1        | 1      | 0.24%   |
| KingDian            | 1        | 1      | 0.24%   |
| JMicron Technology  | 1        | 1      | 0.24%   |
| INNOVATION IT       | 1        | 1      | 0.24%   |
| Drevo               | 1        | 1      | 0.24%   |
| Dogfish             | 1        | 1      | 0.24%   |
| BAITITON            | 1        | 1      | 0.24%   |
| ASMT                | 1        | 6      | 0.24%   |
| AMD                 | 1        | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 338      | 582    | 41.02%  |
| HDD     | 331      | 679    | 40.17%  |
| NVMe    | 141      | 240    | 17.11%  |
| Unknown | 12       | 24     | 1.46%   |
| MMC     | 2        | 3      | 0.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 472      | 1203   | 71.52%  |
| NVMe | 139      | 237    | 21.06%  |
| SAS  | 47       | 85     | 7.12%   |
| MMC  | 2        | 3      | 0.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 344      | 622    | 46.11%  |
| 0.51-1.0   | 216      | 332    | 28.95%  |
| 1.01-2.0   | 85       | 135    | 11.39%  |
| 3.01-4.0   | 45       | 82     | 6.03%   |
| 2.01-3.0   | 30       | 43     | 4.02%   |
| 4.01-10.0  | 22       | 32     | 2.95%   |
| 10.01-20.0 | 4        | 15     | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 110      | 19.96%  |
| 501-1000       | 90       | 16.33%  |
| 251-500        | 67       | 12.16%  |
| More than 3000 | 65       | 11.8%   |
| 1001-2000      | 65       | 11.8%   |
| 1-20           | 41       | 7.44%   |
| 2001-3000      | 39       | 7.08%   |
| 51-100         | 29       | 5.26%   |
| Unknown        | 24       | 4.36%   |
| 21-50          | 21       | 3.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 192      | 33.86%  |
| 21-50          | 59       | 10.41%  |
| 251-500        | 56       | 9.88%   |
| 501-1000       | 53       | 9.35%   |
| 101-250        | 51       | 8.99%   |
| 1001-2000      | 47       | 8.29%   |
| 51-100         | 40       | 7.05%   |
| More than 3000 | 25       | 4.41%   |
| Unknown        | 24       | 4.23%   |
| 2001-3000      | 20       | 3.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD10EADS-22M2B0 1TB                      | 7        | 7      | 9.33%   |
| SanDisk SD6SF1M128G1022I 128GB SSD           | 5        | 5      | 6.67%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 2        | 2      | 2.67%   |
| Seagate ST3500413AS 500GB                    | 2        | 2      | 2.67%   |
| SanDisk SSD PLUS 480GB                       | 2        | 2      | 2.67%   |
| Samsung Electronics HD103UJ 1TB              | 2        | 2      | 2.67%   |
| WDC WD5000AAKX-08U6AA0 500GB                 | 1        | 1      | 1.33%   |
| WDC WD5000AAKS-00UU3A0 500GB                 | 1        | 1      | 1.33%   |
| WDC WD5000AADS-00M2B0 500GB                  | 1        | 1      | 1.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB                     | 1        | 1      | 1.33%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 1        | 1      | 1.33%   |
| WDC WD20EFRX-68AX9N0 2TB                     | 1        | 6      | 1.33%   |
| WDC WD2003FYYS-02W0B1 2TB                    | 1        | 1      | 1.33%   |
| WDC WD2000FYYZ-01UL1B1 2TB                   | 1        | 1      | 1.33%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1        | 1      | 1.33%   |
| WDC WD10EZRX-00L4HB0 1TB                     | 1        | 1      | 1.33%   |
| WDC WD10EACS-00D6B0 1TB                      | 1        | 2      | 1.33%   |
| WDC WD1002FAEX-00Y9A0 1TB                    | 1        | 1      | 1.33%   |
| Transcend TS240GSSD220S 240GB                | 1        | 1      | 1.33%   |
| Toshiba MK1665GSX 160GB                      | 1        | 1      | 1.33%   |
| Toshiba HDWD110 1TB                          | 1        | 2      | 1.33%   |
| SK hynix SC308 SATA 128GB SSD                | 1        | 4      | 1.33%   |
| Seagate ST9500325AS 500GB                    | 1        | 1      | 1.33%   |
| Seagate ST500LM021-1KJ152 500GB              | 1        | 1      | 1.33%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 1      | 1.33%   |
| Seagate ST3500830AS 500GB                    | 1        | 1      | 1.33%   |
| Seagate ST3400832AS 400GB                    | 1        | 1      | 1.33%   |
| Seagate ST3250823AS 250GB                    | 1        | 1      | 1.33%   |
| Seagate ST3250410AS 250GB                    | 1        | 1      | 1.33%   |
| Seagate ST31000528AS 1TB                     | 1        | 1      | 1.33%   |
| Seagate ST3000DM001-9YN166 3TB               | 1        | 1      | 1.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB           | 1        | 1      | 1.33%   |
| Seagate ST2000DX002-2DV164 2TB               | 1        | 1      | 1.33%   |
| Seagate ST2000DM006-2DM164 2TB               | 1        | 1      | 1.33%   |
| Seagate ST2000DM001-9YN164 2TB               | 1        | 1      | 1.33%   |
| Seagate ST2000DM001-1CH164 2TB               | 1        | 1      | 1.33%   |
| SanDisk SD8SBAT256G1122 256GB SSD            | 1        | 1      | 1.33%   |
| SanDisk SD7UB3Q256G1001 256GB SSD            | 1        | 1      | 1.33%   |
| Samsung Electronics SSD 960 PRO 512GB        | 1        | 2      | 1.33%   |
| Samsung Electronics SSD 960 PRO 1TB          | 1        | 1      | 1.33%   |
| Samsung Electronics SSD 850 PRO 1TB          | 1        | 1      | 1.33%   |
| Samsung Electronics SSD 840 Series 120GB     | 1        | 1      | 1.33%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 1        | 1      | 1.33%   |
| Samsung Electronics SSD 840 PRO Series 128GB | 1        | 2      | 1.33%   |
| Samsung Electronics SP1614N 160GB            | 1        | 1      | 1.33%   |
| Samsung Electronics HM500JI 500GB            | 1        | 1      | 1.33%   |
| Samsung Electronics HD502IJ 500GB            | 1        | 1      | 1.33%   |
| Samsung Electronics HD502HJ 500GB            | 1        | 1      | 1.33%   |
| Samsung Electronics HD103SJ 1TB              | 1        | 1      | 1.33%   |
| OCZ AGILITY3 64GB SSD                        | 1        | 1      | 1.33%   |
| OCZ AGILITY3 240GB SSD                       | 1        | 2      | 1.33%   |
| OCZ AGILITY3 120GB SSD                       | 1        | 1      | 1.33%   |
| Maxtor 6Y200P0 208GB                         | 1        | 1      | 1.33%   |
| Kingston SA400S37240G 240GB SSD              | 1        | 1      | 1.33%   |
| Intenso SSD Sata III 128GB                   | 1        | 1      | 1.33%   |
| Intel SSDPEKKW256G7 256GB                    | 1        | 1      | 1.33%   |
| Hitachi HTS541010G9SA00 100GB                | 1        | 1      | 1.33%   |
| Hitachi HDS5C1010CLA382 1TB                  | 1        | 1      | 1.33%   |
| Hitachi HDP725050GLA360 500GB                | 1        | 1      | 1.33%   |
| HGST HTS725050A7E630 500GB                   | 1        | 6      | 1.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 27     | 29.58%  |
| Seagate             | 14       | 16     | 19.72%  |
| Samsung Electronics | 12       | 15     | 16.9%   |
| SanDisk             | 9        | 9      | 12.68%  |
| Hitachi             | 3        | 3      | 4.23%   |
| Toshiba             | 2        | 3      | 2.82%   |
| OCZ                 | 2        | 4      | 2.82%   |
| Transcend           | 1        | 1      | 1.41%   |
| SK hynix            | 1        | 4      | 1.41%   |
| Maxtor              | 1        | 1      | 1.41%   |
| Kingston            | 1        | 1      | 1.41%   |
| Intenso             | 1        | 1      | 1.41%   |
| Intel               | 1        | 1      | 1.41%   |
| HGST                | 1        | 6      | 1.41%   |
| Crucial             | 1        | 1      | 1.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 27     | 43.75%  |
| Seagate             | 14       | 16     | 29.17%  |
| Samsung Electronics | 6        | 7      | 12.5%   |
| Hitachi             | 3        | 3      | 6.25%   |
| Toshiba             | 2        | 3      | 4.17%   |
| Maxtor              | 1        | 1      | 2.08%   |
| HGST                | 1        | 6      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 44       | 63     | 65.67%  |
| SSD  | 20       | 26     | 29.85%  |
| NVMe | 3        | 4      | 4.48%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB | 1        | 1      | 100%    |

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
| Detected | 313      | 797    | 53.14%  |
| Works    | 217      | 636    | 36.84%  |
| Malfunc  | 57       | 93     | 9.68%   |
| Failed   | 1        | 1      | 0.17%   |
| Limited  | 1        | 1      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 314      | 38.86%  |
| AMD                           | 195      | 24.13%  |
| Samsung Electronics           | 75       | 9.28%   |
| ASMedia Technology            | 51       | 6.31%   |
| Marvell Technology Group      | 32       | 3.96%   |
| JMicron Technology            | 25       | 3.09%   |
| SanDisk                       | 22       | 2.72%   |
| Phison Electronics            | 19       | 2.35%   |
| Micron/Crucial Technology     | 10       | 1.24%   |
| Nvidia                        | 9        | 1.11%   |
| LSI Logic / Symbios Logic     | 9        | 1.11%   |
| Kingston Technology Company   | 9        | 1.11%   |
| ADATA Technology              | 5        | 0.62%   |
| Silicon Motion                | 4        | 0.5%    |
| Seagate Technology            | 4        | 0.5%    |
| Broadcom / LSI                | 4        | 0.5%    |
| VIA Technologies              | 3        | 0.37%   |
| Silicon Image                 | 3        | 0.37%   |
| KIOXIA                        | 3        | 0.37%   |
| SK hynix                      | 2        | 0.25%   |
| OCZ Technology Group          | 2        | 0.25%   |
| Micron Technology             | 2        | 0.25%   |
| Realtek Semiconductor         | 1        | 0.12%   |
| MAXIO Technology (Hangzhou)   | 1        | 0.12%   |
| Lite-On Technology            | 1        | 0.12%   |
| Lite-On IT Corp. / Plextor    | 1        | 0.12%   |
| Integrated Technology Express | 1        | 0.12%   |
| Adaptec                       | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 112      | 11.31%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 49       | 4.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 47       | 4.75%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 47       | 4.75%   |
| AMD 400 Series Chipset SATA Controller                                                  | 43       | 4.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 35       | 3.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 34       | 3.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 32       | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 28       | 2.83%   |
| AMD 500 Series Chipset SATA Controller                                                  | 25       | 2.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 21       | 2.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 18       | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 18       | 1.82%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 17       | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17       | 1.72%   |
| Intel SATA Controller [RAID mode]                                                       | 16       | 1.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 13       | 1.31%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 13       | 1.31%   |
| Phison E12 NVMe Controller                                                              | 11       | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10       | 1.01%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 9        | 0.91%   |
| AMD FCH SATA Controller D                                                               | 9        | 0.91%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 8        | 0.81%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 8        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 0.81%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 7        | 0.71%   |
| Samsung NVMe SSD Controller 980                                                         | 7        | 0.71%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 7        | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6        | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6        | 0.61%   |
| Kingston Company A2000 NVMe SSD                                                         | 6        | 0.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 0.61%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 6        | 0.61%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 0.61%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 0.61%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 0.61%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 0.61%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 0.61%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 0.61%   |
| AMD X370 Series Chipset SATA Controller                                                 | 6        | 0.61%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 0.51%   |
| Nvidia MCP61 IDE                                                                        | 5        | 0.51%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 5        | 0.51%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 0.51%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 0.51%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 0.4%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 0.4%    |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 4        | 0.4%    |
| JMicron JMB362 SATA Controller                                                          | 4        | 0.4%    |
| Intel SSD 660P Series                                                                   | 4        | 0.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4        | 0.4%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 0.4%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 0.4%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 0.3%    |
| Seagate FireCuda 530 SSD                                                                | 3        | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 446      | 60.11%  |
| NVMe | 142      | 19.14%  |
| IDE  | 112      | 15.09%  |
| RAID | 30       | 4.04%   |
| SAS  | 6        | 0.81%   |
| SCSI | 6        | 0.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 311      | 60.15%  |
| AMD    | 206      | 39.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 15       | 2.9%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 9        | 1.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 1.74%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 8        | 1.55%   |
| AMD Ryzen 5 3600 6-Core Processor           | 8        | 1.55%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 8        | 1.55%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 1.55%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 7        | 1.35%   |
| AMD FX-8350 Eight-Core Processor            | 7        | 1.35%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 6        | 1.16%   |
| Intel Core i5-4570TE CPU @ 2.70GHz          | 6        | 1.16%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 6        | 1.16%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 6        | 1.16%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 6        | 1.16%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 1.16%   |
| AMD FX-6300 Six-Core Processor              | 6        | 1.16%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 0.97%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 0.97%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 5        | 0.97%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 5        | 0.97%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 5        | 0.97%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 5        | 0.97%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 0.97%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 0.97%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 0.97%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 0.97%   |
| AMD Phenom II X4 955 Processor              | 5        | 0.97%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 0.77%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 4        | 0.77%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 4        | 0.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 0.77%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 4        | 0.77%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.77%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.77%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 0.77%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 4        | 0.77%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 4        | 0.77%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 0.77%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 0.77%   |
| AMD Phenom II X6 1055T Processor            | 4        | 0.77%   |
| AMD FX-9590 Eight-Core Processor            | 4        | 0.77%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.58%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 0.58%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.58%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 3        | 0.58%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.58%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 3        | 0.58%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.58%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 0.58%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 3        | 0.58%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 0.58%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 3        | 0.58%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 3        | 0.58%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 3        | 0.58%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 3        | 0.58%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 0.58%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 0.58%   |
| AMD Phenom II X4 945 Processor              | 3        | 0.58%   |
| AMD FX-4300 Quad-Core Processor             | 3        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 97       | 18.76%  |
| Intel Core i7           | 95       | 18.38%  |
| AMD Ryzen 5             | 46       | 8.9%    |
| AMD Ryzen 7             | 38       | 7.35%   |
| AMD FX                  | 25       | 4.84%   |
| Intel Xeon              | 23       | 4.45%   |
| Intel Core i3           | 21       | 4.06%   |
| Intel Celeron           | 15       | 2.9%    |
| AMD Ryzen 9             | 15       | 2.9%    |
| AMD Phenom II X4        | 14       | 2.71%   |
| AMD Ryzen 3             | 12       | 2.32%   |
| AMD A8                  | 11       | 2.13%   |
| Intel Core i9           | 10       | 1.93%   |
| Intel Core 2 Duo        | 9        | 1.74%   |
| Intel Pentium           | 8        | 1.55%   |
| Intel Core 2 Quad       | 8        | 1.55%   |
| AMD A10                 | 8        | 1.55%   |
| Other                   | 7        | 1.35%   |
| AMD Phenom II X6        | 7        | 1.35%   |
| AMD Athlon II X4        | 6        | 1.16%   |
| Intel Atom              | 5        | 0.97%   |
| AMD Athlon 64 X2        | 5        | 0.97%   |
| Intel Pentium Dual-Core | 4        | 0.77%   |
| Intel Core 2            | 4        | 0.77%   |
| AMD Ryzen Threadripper  | 4        | 0.77%   |
| AMD Athlon              | 3        | 0.58%   |
| Intel Pentium 4         | 2        | 0.39%   |
| AMD Ryzen 7 PRO         | 2        | 0.39%   |
| AMD Phenom              | 2        | 0.39%   |
| AMD E                   | 2        | 0.39%   |
| AMD Athlon II X2        | 2        | 0.39%   |
| Intel Pentium Silver    | 1        | 0.19%   |
| Intel Pentium Dual      | 1        | 0.19%   |
| Intel Genuine           | 1        | 0.19%   |
| AMD Ryzen 5 PRO         | 1        | 0.19%   |
| AMD Ryzen 3 PRO         | 1        | 0.19%   |
| AMD Phenom II X2        | 1        | 0.19%   |
| AMD A6                  | 1        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 243      | 46.91%  |
| 2       | 100      | 19.31%  |
| 6       | 71       | 13.71%  |
| 8       | 56       | 10.81%  |
| 12      | 15       | 2.9%    |
| 16      | 10       | 1.93%   |
| 3       | 6        | 1.16%   |
| 10      | 5        | 0.97%   |
| 1       | 4        | 0.77%   |
| 14      | 3        | 0.58%   |
| Unknown | 2        | 0.39%   |
| 64      | 1        | 0.19%   |
| 40      | 1        | 0.19%   |
| 24      | 1        | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 512      | 99.03%  |
| 2      | 5        | 0.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 317      | 61.2%   |
| 1       | 199      | 38.42%  |
| Unknown | 2        | 0.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 505      | 97.68%  |
| Unknown        | 10       | 1.93%   |
| 32-bit         | 2        | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 102      | 19.14%  |
| 0x306c3    | 47       | 8.82%   |
| 0x206a7    | 26       | 4.88%   |
| 0x306a9    | 25       | 4.69%   |
| 0x506e3    | 24       | 4.5%    |
| 0x08701021 | 21       | 3.94%   |
| 0x06000852 | 14       | 2.63%   |
| 0x08701013 | 13       | 2.44%   |
| 0x906e9    | 12       | 2.25%   |
| 0x08108109 | 12       | 2.25%   |
| 0x010000c8 | 12       | 2.25%   |
| 0x906ea    | 11       | 2.06%   |
| 0x0800820d | 11       | 2.06%   |
| 0x06001119 | 11       | 2.06%   |
| 0x1067a    | 9        | 1.69%   |
| 0x106e5    | 8        | 1.5%    |
| 0x0a201016 | 8        | 1.5%    |
| 0x08001138 | 8        | 1.5%    |
| 0x0a50000c | 7        | 1.31%   |
| 0x306f2    | 6        | 1.13%   |
| 0x106a5    | 6        | 1.13%   |
| 0x0a201009 | 6        | 1.13%   |
| 0x010000dc | 6        | 1.13%   |
| 0xa0655    | 5        | 0.94%   |
| 0x6fb      | 5        | 0.94%   |
| 0x906ed    | 4        | 0.75%   |
| 0x0800820b | 4        | 0.75%   |
| 0x0600611a | 4        | 0.75%   |
| 0x010000db | 4        | 0.75%   |
| 0xa0671    | 3        | 0.56%   |
| 0x6f6      | 3        | 0.56%   |
| 0x506c9    | 3        | 0.56%   |
| 0x206d7    | 3        | 0.56%   |
| 0x206c2    | 3        | 0.56%   |
| 0x20655    | 3        | 0.56%   |
| 0x20652    | 3        | 0.56%   |
| 0x06003106 | 3        | 0.56%   |
| 0x0600063e | 3        | 0.56%   |
| 0x03000027 | 3        | 0.56%   |
| 0x010000c6 | 3        | 0.56%   |
| 0xa0653    | 2        | 0.38%   |
| 0x906ec    | 2        | 0.38%   |
| 0x90672    | 2        | 0.38%   |
| 0x706a8    | 2        | 0.38%   |
| 0x6fd      | 2        | 0.38%   |
| 0x50657    | 2        | 0.38%   |
| 0x50654    | 2        | 0.38%   |
| 0x406f1    | 2        | 0.38%   |
| 0x406c4    | 2        | 0.38%   |
| 0x306e4    | 2        | 0.38%   |
| 0x30661    | 2        | 0.38%   |
| 0x10677    | 2        | 0.38%   |
| 0x10676    | 2        | 0.38%   |
| 0x0a50000b | 2        | 0.38%   |
| 0x08101016 | 2        | 0.38%   |
| 0x0810100b | 2        | 0.38%   |
| 0x06000817 | 2        | 0.38%   |
| 0x010000b6 | 2        | 0.38%   |
| 0x01000095 | 2        | 0.38%   |
| 0xf49      | 1        | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 70       | 13.54%  |
| Zen 2            | 48       | 9.28%   |
| KabyLake         | 41       | 7.93%   |
| Skylake          | 36       | 6.96%   |
| SandyBridge      | 36       | 6.96%   |
| IvyBridge        | 34       | 6.58%   |
| Zen+             | 32       | 6.19%   |
| Piledriver       | 31       | 6%      |
| K10              | 31       | 6%      |
| Zen 3            | 26       | 5.03%   |
| Zen              | 16       | 3.09%   |
| Nehalem          | 16       | 3.09%   |
| Penryn           | 14       | 2.71%   |
| Core             | 12       | 2.32%   |
| Westmere         | 11       | 2.13%   |
| CometLake        | 11       | 2.13%   |
| Silvermont       | 5        | 0.97%   |
| K8 Hammer        | 5        | 0.97%   |
| Steamroller      | 4        | 0.77%   |
| Goldmont plus    | 4        | 0.77%   |
| Goldmont         | 4        | 0.77%   |
| Excavator        | 4        | 0.77%   |
| Unknown          | 4        | 0.77%   |
| NetBurst         | 3        | 0.58%   |
| K10 Llano        | 3        | 0.58%   |
| Bulldozer        | 3        | 0.58%   |
| Broadwell        | 3        | 0.58%   |
| Bonnell          | 3        | 0.58%   |
| Icelake          | 2        | 0.39%   |
| Bobcat           | 2        | 0.39%   |
| Alderlake Hybrid | 2        | 0.39%   |
| Tremont          | 1        | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 227      | 41.12%  |
| AMD                        | 195      | 35.33%  |
| Intel                      | 125      | 22.64%  |
| Matrox Electronics Systems | 2        | 0.36%   |
| ASPEED Technology          | 2        | 0.36%   |
| ATI Technologies           | 1        | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 26       | 4.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 23       | 4.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16       | 2.83%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 13       | 2.3%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12       | 2.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12       | 2.12%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 11       | 1.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 10       | 1.77%   |
| Nvidia GT218 [GeForce 210]                                                               | 9        | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 9        | 1.59%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 8        | 1.42%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 8        | 1.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8        | 1.42%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 8        | 1.42%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 8        | 1.42%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8        | 1.42%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 7        | 1.24%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 7        | 1.24%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 7        | 1.24%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 7        | 1.24%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 6        | 1.06%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 6        | 1.06%   |
| Intel HD Graphics 630                                                                    | 6        | 1.06%   |
| Intel HD Graphics 530                                                                    | 6        | 1.06%   |
| AMD Cezanne                                                                              | 6        | 1.06%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 5        | 0.88%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 0.88%   |
| AMD Renoir                                                                               | 5        | 0.88%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 5        | 0.88%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 0.71%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 4        | 0.71%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 4        | 0.71%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 4        | 0.71%   |
| Nvidia GF106 [GeForce GTS 450 OEM]                                                       | 4        | 0.71%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 4        | 0.71%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 4        | 0.71%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                                        | 4        | 0.71%   |
| AMD RS780L [Radeon 3000]                                                                 | 4        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4        | 0.71%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 4        | 0.71%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 4        | 0.71%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 4        | 0.71%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 4        | 0.71%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 3        | 0.53%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 3        | 0.53%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 0.53%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 3        | 0.53%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 3        | 0.53%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 3        | 0.53%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 0.53%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 0.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 0.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 0.53%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3        | 0.53%   |
| AMD Trinity [Radeon HD 7560D]                                                            | 3        | 0.53%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                                   | 3        | 0.53%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                             | 3        | 0.53%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 3        | 0.53%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 213      | 40.96%  |
| 1 x AMD         | 184      | 35.38%  |
| 1 x Intel       | 100      | 19.23%  |
| 2 x AMD         | 5        | 0.96%   |
| AMD + Nvidia    | 5        | 0.96%   |
| Intel + Nvidia  | 4        | 0.77%   |
| 2 x Nvidia      | 3        | 0.58%   |
| 1 x Matrox      | 2        | 0.38%   |
| Other           | 1        | 0.19%   |
| Nvidia + ASPEED | 1        | 0.19%   |
| Intel + AMD     | 1        | 0.19%   |
| 1 x ASPEED      | 1        | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 381      | 72.71%  |
| Proprietary | 123      | 23.47%  |
| Unknown     | 20       | 3.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 171      | 32.45%  |
| 1.01-2.0   | 87       | 16.51%  |
| 7.01-8.0   | 62       | 11.76%  |
| 0.51-1.0   | 57       | 10.82%  |
| 0.01-0.5   | 53       | 10.06%  |
| 3.01-4.0   | 51       | 9.68%   |
| 5.01-6.0   | 23       | 4.36%   |
| 8.01-16.0  | 13       | 2.47%   |
| 2.01-3.0   | 7        | 1.33%   |
| 16.01-24.0 | 2        | 0.38%   |
| 4.01-5.0   | 1        | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 118      | 20.31%  |
| BenQ                    | 60       | 10.33%  |
| Dell                    | 42       | 7.23%   |
| Acer                    | 40       | 6.88%   |
| Hewlett-Packard         | 37       | 6.37%   |
| Goldstar                | 32       | 5.51%   |
| AOC                     | 30       | 5.16%   |
| Philips                 | 29       | 4.99%   |
| Iiyama                  | 28       | 4.82%   |
| Ancor Communications    | 22       | 3.79%   |
| Eizo                    | 16       | 2.75%   |
| Medion                  | 13       | 2.24%   |
| NEC Computers           | 10       | 1.72%   |
| ViewSonic               | 8        | 1.38%   |
| Unknown                 | 8        | 1.38%   |
| Gericom                 | 8        | 1.38%   |
| Lenovo                  | 7        | 1.2%    |
| Fujitsu Siemens         | 7        | 1.2%    |
| Sony                    | 6        | 1.03%   |
| Idek Iiyama             | 5        | 0.86%   |
| LG Electronics          | 4        | 0.69%   |
| HannStar                | 4        | 0.69%   |
| Toshiba                 | 3        | 0.52%   |
| Belinea                 | 3        | 0.52%   |
| ASUSTek Computer        | 3        | 0.52%   |
| Apple                   | 3        | 0.52%   |
| Plain Tree Systems      | 2        | 0.34%   |
| MSI                     | 2        | 0.34%   |
| Lenovo Group Limited    | 2        | 0.34%   |
| Jean                    | 2        | 0.34%   |
| HVR                     | 2        | 0.34%   |
| Hitachi                 | 2        | 0.34%   |
| Chi Mei Optoelectronics | 2        | 0.34%   |
| YUK                     | 1        | 0.17%   |
| Vestel Elektronik       | 1        | 0.17%   |
| TopView                 | 1        | 0.17%   |
| SKY                     | 1        | 0.17%   |
| SIM                     | 1        | 0.17%   |
| Sharp                   | 1        | 0.17%   |
| NEX                     | 1        | 0.17%   |
| KTC                     | 1        | 0.17%   |
| Hyundai ImageQuest      | 1        | 0.17%   |
| HUAWEI                  | 1        | 0.17%   |
| HCG                     | 1        | 0.17%   |
| Grundig                 | 1        | 0.17%   |
| GRM                     | 1        | 0.17%   |
| Gigabyte Technology     | 1        | 0.17%   |
| CVT                     | 1        | 0.17%   |
| Compal                  | 1        | 0.17%   |
| CHD                     | 1        | 0.17%   |
| Beko                    | 1        | 0.17%   |
| AUS                     | 1        | 0.17%   |
| AU Optronics            | 1        | 0.17%   |
| Unknown                 | 1        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 7        | 1.11%   |
| Acer B193 ACR001D 1280x1024 376x301mm 19.0-inch                       | 7        | 1.11%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 5        | 0.79%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 5        | 0.79%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                 | 4        | 0.63%   |
| Gericom Q24 QMX2421 1920x1080 521x293mm 23.5-inch                     | 4        | 0.63%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 4        | 0.63%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.47%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 3        | 0.47%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 3        | 0.47%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 3        | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3        | 0.47%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch     | 3        | 0.47%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.47%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 3        | 0.47%   |
| Eizo S2202W ENC1975 1680x1050 474x297mm 22.0-inch                     | 3        | 0.47%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 3        | 0.47%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 3        | 0.47%   |
| Unknown LCD Monitor GRM GM2600 1920x1200                              | 2        | 0.32%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM0486 1920x1080                      | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch  | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch  | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 2        | 0.32%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch    | 2        | 0.32%   |
| Samsung Electronics SMBX2035 SAM06FE 1600x900 440x250mm 19.9-inch     | 2        | 0.32%   |
| Samsung Electronics S27E330 SAM0D90 1920x1080 598x336mm 27.0-inch     | 2        | 0.32%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 520x320mm 24.0-inch     | 2        | 0.32%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch     | 2        | 0.32%   |
| Samsung Electronics LS32R75 SAM0F93 3840x2160 700x390mm 31.5-inch     | 2        | 0.32%   |
| Samsung Electronics LF32TU87 SAM706B 3840x2160 698x393mm 31.5-inch    | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 2        | 0.32%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 2        | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 0.32%   |
| Philips PHL BDM4037U PHLC142 3840x2160 885x498mm 40.0-inch            | 2        | 0.32%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 2        | 0.32%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 2        | 0.32%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 2        | 0.32%   |
| Philips 220BLP PHL08BF 1680x1050 474x296mm 22.0-inch                  | 2        | 0.32%   |
| Medion MD20432 MED36A8 1920x1080 521x293mm 23.5-inch                  | 2        | 0.32%   |
| Jean GM2200 JEN1003 1680x1050 474x297mm 22.0-inch                     | 2        | 0.32%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 2        | 0.32%   |
| Iiyama PL2790 IVM6616 1920x1080 598x336mm 27.0-inch                   | 2        | 0.32%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                 | 2        | 0.32%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                  | 2        | 0.32%   |
| Iiyama PL2452 IVM610A 1920x1080 521x293mm 23.5-inch                   | 2        | 0.32%   |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                             | 2        | 0.32%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 2        | 0.32%   |
| Hewlett-Packard V27e HPN36B1 1920x1080 598x336mm 27.0-inch            | 2        | 0.32%   |
| Hewlett-Packard LP2475w HWP26F7 1920x1200 540x350mm 25.3-inch         | 2        | 0.32%   |
| Hewlett-Packard Compaq W220q HWP2809 1680x1050 473x296mm 22.0-inch    | 2        | 0.32%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch             | 2        | 0.32%   |
| Goldstar W2442 GSM56CC 1920x1080 531x299mm 24.0-inch                  | 2        | 0.32%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                  | 2        | 0.32%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 2        | 0.32%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2        | 0.32%   |
| Goldstar 24EB23 GSM59B4 1920x1200 520x330mm 24.2-inch                 | 2        | 0.32%   |
| Gericom Vision L22FHD QMX2472 1920x1080 478x269mm 21.6-inch           | 2        | 0.32%   |
| Dell U2719D DEL415F 2560x1440 600x340mm 27.2-inch                     | 2        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 254      | 43.94%  |
| 3840x2160 (4K)     | 65       | 11.25%  |
| 2560x1440 (QHD)    | 55       | 9.52%   |
| 1680x1050 (WSXGA+) | 50       | 8.65%   |
| 1280x1024 (SXGA)   | 41       | 7.09%   |
| 1920x1200 (WUXGA)  | 36       | 6.23%   |
| Unknown            | 13       | 2.25%   |
| 3440x1440          | 9        | 1.56%   |
| 2560x1080          | 7        | 1.21%   |
| 3840x1080          | 6        | 1.04%   |
| 2560x1600          | 5        | 0.87%   |
| 1920x540           | 4        | 0.69%   |
| 1600x900 (HD+)     | 4        | 0.69%   |
| 1440x900 (WXGA+)   | 4        | 0.69%   |
| 1366x768 (WXGA)    | 3        | 0.52%   |
| 1024x768 (XGA)     | 3        | 0.52%   |
| 5120x1440          | 2        | 0.35%   |
| 4480x1440          | 2        | 0.35%   |
| 2160x1200          | 2        | 0.35%   |
| 2048x1152          | 2        | 0.35%   |
| 5760x2160          | 1        | 0.17%   |
| 5760x1080          | 1        | 0.17%   |
| 3840x2560          | 1        | 0.17%   |
| 3600x1080          | 1        | 0.17%   |
| 3520x1080          | 1        | 0.17%   |
| 3360x1050          | 1        | 0.17%   |
| 3200x1080          | 1        | 0.17%   |
| 1600x1200          | 1        | 0.17%   |
| 1400x1050          | 1        | 0.17%   |
| 1360x768           | 1        | 0.17%   |
| 1280x960           | 1        | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 102      | 17.5%   |
| 27      | 96       | 16.47%  |
| 23      | 71       | 12.18%  |
| Unknown | 68       | 11.66%  |
| 22      | 38       | 6.52%   |
| 19      | 37       | 6.35%   |
| 21      | 33       | 5.66%   |
| 31      | 28       | 4.8%    |
| 25      | 13       | 2.23%   |
| 34      | 11       | 1.89%   |
| 20      | 11       | 1.89%   |
| 17      | 10       | 1.72%   |
| 84      | 9        | 1.54%   |
| 32      | 6        | 1.03%   |
| 28      | 6        | 1.03%   |
| 54      | 5        | 0.86%   |
| 40      | 5        | 0.86%   |
| 18      | 5        | 0.86%   |
| 65      | 4        | 0.69%   |
| 15      | 4        | 0.69%   |
| 72      | 3        | 0.51%   |
| 29      | 3        | 0.51%   |
| 42      | 2        | 0.34%   |
| 33      | 2        | 0.34%   |
| 55      | 1        | 0.17%   |
| 49      | 1        | 0.17%   |
| 48      | 1        | 0.17%   |
| 46      | 1        | 0.17%   |
| 43      | 1        | 0.17%   |
| 41      | 1        | 0.17%   |
| 39      | 1        | 0.17%   |
| 35      | 1        | 0.17%   |
| 26      | 1        | 0.17%   |
| 16      | 1        | 0.17%   |
| 13      | 1        | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 241      | 43.04%  |
| 401-500     | 90       | 16.07%  |
| Unknown     | 68       | 12.14%  |
| 601-700     | 53       | 9.46%   |
| 351-400     | 38       | 6.79%   |
| 701-800     | 18       | 3.21%   |
| 301-350     | 14       | 2.5%    |
| 1001-1500   | 13       | 2.32%   |
| 1501-2000   | 12       | 2.14%   |
| 801-900     | 7        | 1.25%   |
| 901-1000    | 4        | 0.71%   |
| 201-300     | 2        | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 327      | 60.11%  |
| 16/10   | 93       | 17.1%   |
| Unknown | 53       | 9.74%   |
| 5/4     | 42       | 7.72%   |
| 21/9    | 12       | 2.21%   |
| 4/3     | 5        | 0.92%   |
| 32/9    | 5        | 0.92%   |
| 3/2     | 4        | 0.74%   |
| 6/5     | 2        | 0.37%   |
| 0.80    | 1        | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 189      | 32.93%  |
| 301-350        | 97       | 16.9%   |
| Unknown        | 68       | 11.85%  |
| 151-200        | 63       | 10.98%  |
| 351-500        | 54       | 9.41%   |
| 251-300        | 51       | 8.89%   |
| More than 1000 | 22       | 3.83%   |
| 501-1000       | 13       | 2.26%   |
| 141-150        | 10       | 1.74%   |
| 101-110        | 3        | 0.52%   |
| 71-80          | 1        | 0.17%   |
| 131-140        | 1        | 0.17%   |
| 121-130        | 1        | 0.17%   |
| 111-120        | 1        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 318      | 60.34%  |
| 101-120 | 82       | 15.56%  |
| Unknown | 68       | 12.9%   |
| 121-160 | 36       | 6.83%   |
| 1-50    | 13       | 2.47%   |
| 161-240 | 10       | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 385      | 73.19%  |
| 2     | 96       | 18.25%  |
| 0     | 27       | 5.13%   |
| 3     | 18       | 3.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 289      | 40.14%  |
| Intel                                 | 239      | 33.19%  |
| Qualcomm Atheros                      | 42       | 5.83%   |
| Broadcom                              | 16       | 2.22%   |
| Ralink Technology                     | 13       | 1.81%   |
| TP-Link                               | 11       | 1.53%   |
| IMC Networks                          | 11       | 1.53%   |
| ASUSTek Computer                      | 9        | 1.25%   |
| Nvidia                                | 8        | 1.11%   |
| Microsoft                             | 8        | 1.11%   |
| Marvell Technology Group              | 8        | 1.11%   |
| Ralink                                | 7        | 0.97%   |
| NetGear                               | 6        | 0.83%   |
| Edimax Technology                     | 6        | 0.83%   |
| Aquantia                              | 5        | 0.69%   |
| Samsung Electronics                   | 4        | 0.56%   |
| Qualcomm Atheros Communications       | 4        | 0.56%   |
| D-Link System                         | 4        | 0.56%   |
| D-Link                                | 4        | 0.56%   |
| Broadcom Limited                      | 3        | 0.42%   |
| VIA Technologies                      | 2        | 0.28%   |
| Huawei Technologies                   | 2        | 0.28%   |
| ASIX Electronics                      | 2        | 0.28%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.28%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.14%   |
| Xiaomi                                | 1        | 0.14%   |
| Winbond Electronics                   | 1        | 0.14%   |
| Wilocity                              | 1        | 0.14%   |
| SEGGER                                | 1        | 0.14%   |
| Prusa Research (prusa3d.com)          | 1        | 0.14%   |
| Philips (or NXP)                      | 1        | 0.14%   |
| Oculus VR                             | 1        | 0.14%   |
| Motorola                              | 1        | 0.14%   |
| Microchip Technology                  | 1        | 0.14%   |
| Mellanox Technologies                 | 1        | 0.14%   |
| Lenovo                                | 1        | 0.14%   |
| BUFFALO                               | 1        | 0.14%   |
| Belkin Components                     | 1        | 0.14%   |
| Arduino SA                            | 1        | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 244      | 29.61%  |
| Intel I211 Gigabit Network Connection                                | 42       | 5.1%    |
| Intel Ethernet Connection (2) I219-V                                 | 31       | 3.76%   |
| Intel Wi-Fi 6 AX200                                                  | 29       | 3.52%   |
| Realtek RTL8125 2.5GbE Controller                                    | 23       | 2.79%   |
| Intel Ethernet Controller I225-V                                     | 18       | 2.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 16       | 1.94%   |
| Intel 82579V Gigabit Network Connection                              | 15       | 1.82%   |
| Intel Ethernet Connection (7) I219-V                                 | 13       | 1.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 12       | 1.46%   |
| Intel Ethernet Connection I217-V                                     | 10       | 1.21%   |
| Intel Ethernet Connection I217-LM                                    | 10       | 1.21%   |
| Intel Wireless-AC 9260                                               | 9        | 1.09%   |
| Intel Ethernet Connection (2) I218-V                                 | 9        | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 9        | 1.09%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                 | 9        | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 8        | 0.97%   |
| Intel 82574L Gigabit Network Connection                              | 8        | 0.97%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 7        | 0.85%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 7        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7        | 0.85%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]   | 7        | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                | 6        | 0.73%   |
| Ralink RT5370 Wireless Adapter                                       | 5        | 0.61%   |
| Nvidia MCP61 Ethernet                                                | 5        | 0.61%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller              | 5        | 0.61%   |
| Intel I210 Gigabit Network Connection                                | 5        | 0.61%   |
| Intel 82578DM Gigabit Network Connection                             | 5        | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4        | 0.49%   |
| Ralink RT2800 802.11n PCI                                            | 4        | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                      | 4        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 4        | 0.49%   |
| Intel Wireless 8260                                                  | 4        | 0.49%   |
| Intel Ethernet Connection (2) I218-LM                                | 4        | 0.49%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 4        | 0.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 3        | 0.36%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 3        | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 3        | 0.36%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 3        | 0.36%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 3        | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 3        | 0.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3        | 0.36%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 3        | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 3        | 0.36%   |
| Realtek 802.11ac NIC                                                 | 3        | 0.36%   |
| Ralink RT5572 Wireless Adapter                                       | 3        | 0.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3        | 0.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3        | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 3        | 0.36%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]              | 3        | 0.36%   |
| Intel Wireless 3165                                                  | 3        | 0.36%   |
| Intel Centrino Wireless-N 2230                                       | 3        | 0.36%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 3        | 0.36%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 3        | 0.36%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 3        | 0.36%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 3        | 0.36%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                   | 3        | 0.36%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]    | 3        | 0.36%   |
| VIA VT6105/VT6106S [Rhine-III]                                       | 2        | 0.24%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 76       | 32.62%  |
| Realtek Semiconductor                 | 45       | 19.31%  |
| Qualcomm Atheros                      | 15       | 6.44%   |
| Ralink Technology                     | 13       | 5.58%   |
| TP-Link                               | 11       | 4.72%   |
| IMC Networks                          | 11       | 4.72%   |
| ASUSTek Computer                      | 9        | 3.86%   |
| Microsoft                             | 8        | 3.43%   |
| Broadcom                              | 8        | 3.43%   |
| Ralink                                | 7        | 3%      |
| NetGear                               | 6        | 2.58%   |
| Edimax Technology                     | 6        | 2.58%   |
| Qualcomm Atheros Communications       | 4        | 1.72%   |
| D-Link System                         | 4        | 1.72%   |
| D-Link                                | 3        | 1.29%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.86%   |
| Wilocity                              | 1        | 0.43%   |
| Philips (or NXP)                      | 1        | 0.43%   |
| BUFFALO                               | 1        | 0.43%   |
| Broadcom Limited                      | 1        | 0.43%   |
| Belkin Components                     | 1        | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                                 | 29       | 12.24%  |
| Intel Wireless-AC 9260                                                                              | 9        | 3.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                    | 9        | 3.8%    |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                                | 9        | 3.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                  | 8        | 3.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 7        | 2.95%   |
| Microsoft Xbox 360 Wireless Adapter                                                                 | 7        | 2.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 7        | 2.95%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]                                  | 7        | 2.95%   |
| Ralink RT5370 Wireless Adapter                                                                      | 5        | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                            | 4        | 1.69%   |
| Ralink RT2800 802.11n PCI                                                                           | 4        | 1.69%   |
| Qualcomm Atheros AR9271 802.11n                                                                     | 4        | 1.69%   |
| Intel Wireless 8260                                                                                 | 4        | 1.69%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                                      | 4        | 1.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 3        | 1.27%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                              | 3        | 1.27%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 3        | 1.27%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                                     | 3        | 1.27%   |
| Realtek 802.11ac NIC                                                                                | 3        | 1.27%   |
| Ralink RT5572 Wireless Adapter                                                                      | 3        | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                          | 3        | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                    | 3        | 1.27%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                                             | 3        | 1.27%   |
| Intel Wireless 3165                                                                                 | 3        | 1.27%   |
| Intel Centrino Wireless-N 2230                                                                      | 3        | 1.27%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                                | 3        | 1.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                                  | 3        | 1.27%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                                  | 3        | 1.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                        | 2        | 0.84%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                             | 2        | 0.84%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                              | 2        | 0.84%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                              | 2        | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                 | 2        | 0.84%   |
| Ralink MT7601U Wireless Adapter                                                                     | 2        | 0.84%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                                | 2        | 0.84%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                    | 2        | 0.84%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                                         | 2        | 0.84%   |
| Intel Wireless 8265 / 8275                                                                          | 2        | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 2        | 0.84%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                                    | 2        | 0.84%   |
| IMC Networks AW-NU222 802.11bgn Wireless Module [Ralink RT2770+RT2720]                              | 2        | 0.84%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A1) [Atheros AR9170+AR9104]         | 2        | 0.84%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 2        | 0.84%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                                  | 1        | 0.42%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                               | 1        | 0.42%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                                 | 1        | 0.42%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                          | 1        | 0.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 0.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 0.42%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                                     | 1        | 0.42%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                          | 1        | 0.42%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                                              | 1        | 0.42%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                          | 1        | 0.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1        | 0.42%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                              | 1        | 0.42%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                         | 1        | 0.42%   |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1        | 0.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                          | 1        | 0.42%   |
| Realtek RTL8187 Wireless Adapter                                                                    | 1        | 0.42%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 276      | 49.64%  |
| Intel                      | 209      | 37.59%  |
| Qualcomm Atheros           | 28       | 5.04%   |
| Nvidia                     | 8        | 1.44%   |
| Marvell Technology Group   | 8        | 1.44%   |
| Broadcom                   | 8        | 1.44%   |
| Aquantia                   | 5        | 0.9%    |
| Samsung Electronics        | 4        | 0.72%   |
| VIA Technologies           | 2        | 0.36%   |
| Broadcom Limited           | 2        | 0.36%   |
| ASIX Electronics           | 2        | 0.36%   |
| ZTE WCDMA Technologies MSM | 1        | 0.18%   |
| Xiaomi                     | 1        | 0.18%   |
| Mellanox Technologies      | 1        | 0.18%   |
| D-Link                     | 1        | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 244      | 42.29%  |
| Intel I211 Gigabit Network Connection                             | 42       | 7.28%   |
| Intel Ethernet Connection (2) I219-V                              | 31       | 5.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23       | 3.99%   |
| Intel Ethernet Controller I225-V                                  | 18       | 3.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16       | 2.77%   |
| Intel 82579V Gigabit Network Connection                           | 15       | 2.6%    |
| Intel Ethernet Connection (7) I219-V                              | 13       | 2.25%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12       | 2.08%   |
| Intel Ethernet Connection I217-V                                  | 10       | 1.73%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 1.73%   |
| Intel Ethernet Connection (2) I218-V                              | 9        | 1.56%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 6        | 1.04%   |
| Nvidia MCP61 Ethernet                                             | 5        | 0.87%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 0.87%   |
| Intel I210 Gigabit Network Connection                             | 5        | 0.87%   |
| Intel 82578DM Gigabit Network Connection                          | 5        | 0.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.69%   |
| Intel Ethernet Connection (2) I218-LM                             | 4        | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 0.52%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3        | 0.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.52%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.35%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.35%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2        | 0.35%   |
| Intel I350 Gigabit Network Connection                             | 2        | 0.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.35%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 2        | 0.35%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.35%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 0.35%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.35%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.35%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1        | 0.17%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 0.17%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.17%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.17%   |
| Nvidia MCP65 Ethernet                                             | 1        | 0.17%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.17%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 0.17%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.17%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.17%   |
| Intel Ethernet Virtual Function 700 Series                        | 1        | 0.17%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 0.17%   |
| Intel Ethernet Controller X550                                    | 1        | 0.17%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 0.17%   |
| Intel Ethernet Connection X553 1GbE                               | 1        | 0.17%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 514      | 70.12%  |
| WiFi     | 210      | 28.65%  |
| Modem    | 9        | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 419      | 79.36%  |
| WiFi     | 109      | 20.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 350      | 67.31%  |
| 2     | 132      | 25.38%  |
| 3     | 27       | 5.19%   |
| 4     | 4        | 0.77%   |
| 5     | 3        | 0.58%   |
| 0     | 2        | 0.38%   |
| 13    | 1        | 0.19%   |
| 6     | 1        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 482      | 93.05%  |
| Yes  | 36       | 6.95%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 72       | 45.28%  |
| Cambridge Silicon Radio         | 40       | 25.16%  |
| ASUSTek Computer                | 13       | 8.18%   |
| Realtek Semiconductor           | 11       | 6.92%   |
| Broadcom                        | 7        | 4.4%    |
| Qualcomm Atheros Communications | 4        | 2.52%   |
| HTC (High Tech Computer)        | 2        | 1.26%   |
| D-Link System                   | 2        | 1.26%   |
| Belkin Components               | 2        | 1.26%   |
| Apple                           | 2        | 1.26%   |
| Micro Star International        | 1        | 0.63%   |
| Logitech                        | 1        | 0.63%   |
| Lite-On Technology              | 1        | 0.63%   |
| IMC Networks                    | 1        | 0.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 40       | 25.16%  |
| Intel AX200 Bluetooth                                                | 30       | 18.87%  |
| Intel Bluetooth wireless interface                                   | 12       | 7.55%   |
| Realtek Bluetooth Radio                                              | 8        | 5.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 8        | 5.03%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 8        | 5.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 7        | 4.4%    |
| Intel Bluetooth Device                                               | 4        | 2.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4        | 2.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 4        | 2.52%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 3        | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 1.89%   |
| ASUS BCM20702A0                                                      | 3        | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 1.26%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 1.26%   |
| D-Link System DBT-122 Bluetooth                                      | 2        | 1.26%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 2        | 1.26%   |
| ASUS Bluetooth Adapter                                               | 2        | 1.26%   |
| Apple Bluetooth USB Host Controller                                  | 2        | 1.26%   |
| Realtek Bluetooth 5.1 Radio                                          | 1        | 0.63%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 1        | 0.63%   |
| Micro Star International Bluetooth Device                            | 1        | 0.63%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 1        | 0.63%   |
| Lite-On Bluetooth Device                                             | 1        | 0.63%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.63%   |
| Broadcom Bluetooth 3.0 Device                                        | 1        | 0.63%   |
| Broadcom BCM2210 Bluetooth                                           | 1        | 0.63%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 0.63%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.63%   |
| Belkin Components F8T013 Bluetooth Adapter                           | 1        | 0.63%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.63%   |
| ASUS Bluetooth Device                                                | 1        | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 295      | 32.49%  |
| AMD                        | 258      | 28.41%  |
| Nvidia                     | 217      | 23.9%   |
| C-Media Electronics        | 31       | 3.41%   |
| Logitech                   | 15       | 1.65%   |
| Creative Labs              | 11       | 1.21%   |
| Razer USA                  | 5        | 0.55%   |
| GN Netcom                  | 5        | 0.55%   |
| SteelSeries ApS            | 4        | 0.44%   |
| Corsair                    | 4        | 0.44%   |
| Kingston Technology        | 3        | 0.33%   |
| JMTek                      | 3        | 0.33%   |
| Focusrite-Novation         | 3        | 0.33%   |
| Bose                       | 3        | 0.33%   |
| ASUSTek Computer           | 3        | 0.33%   |
| Thomann                    | 2        | 0.22%   |
| Texas Instruments          | 2        | 0.22%   |
| Sony                       | 2        | 0.22%   |
| RODE Microphones           | 2        | 0.22%   |
| Project                    | 2        | 0.22%   |
| Microdia                   | 2        | 0.22%   |
| Micro Star International   | 2        | 0.22%   |
| GYROCOM C&C                | 2        | 0.22%   |
| Generalplus Technology     | 2        | 0.22%   |
| Asahi Kasei Microsystems   | 2        | 0.22%   |
| ZOOM                       | 1        | 0.11%   |
| VIA Technologies           | 1        | 0.11%   |
| Unknown                    | 1        | 0.11%   |
| Turtle Beach               | 1        | 0.11%   |
| Textech International      | 1        | 0.11%   |
| TerraTec Electronic        | 1        | 0.11%   |
| Sennheiser Communications  | 1        | 0.11%   |
| SAVITECH                   | 1        | 0.11%   |
| Realtek Semiconductor      | 1        | 0.11%   |
| Razer                      | 1        | 0.11%   |
| Quanta                     | 1        | 0.11%   |
| Qualcomm                   | 1        | 0.11%   |
| PreSonus Audio Electronics | 1        | 0.11%   |
| Plantronics                | 1        | 0.11%   |
| OLKB                       | 1        | 0.11%   |
| Meizu                      | 1        | 0.11%   |
| Mad Catz                   | 1        | 0.11%   |
| M-Audio                    | 1        | 0.11%   |
| LG Electronics             | 1        | 0.11%   |
| JBL                        | 1        | 0.11%   |
| iCreate Technologies       | 1        | 0.11%   |
| Elite Silicon              | 1        | 0.11%   |
| Elgato Systems             | 1        | 0.11%   |
| Dell                       | 1        | 0.11%   |
| Creative Technology        | 1        | 0.11%   |
| ATI Technologies           | 1        | 0.11%   |
| Apple                      | 1        | 0.11%   |
| Afatech                    | 1        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 58       | 5.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 53       | 4.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 48       | 4.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 33       | 3.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 33       | 3.08%   |
| AMD Family 17h/19h HD Audio Controller                                            | 31       | 2.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 29       | 2.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 26       | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 25       | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 25       | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                        | 20       | 1.87%   |
| Intel 200 Series PCH HD Audio                                                     | 20       | 1.87%   |
| AMD FCH Azalia Controller                                                         | 18       | 1.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 17       | 1.59%   |
| Nvidia GP104 High Definition Audio Controller                                     | 16       | 1.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 16       | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 16       | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 14       | 1.31%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 14       | 1.31%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 14       | 1.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 14       | 1.31%   |
| Nvidia GP108 High Definition Audio Controller                                     | 13       | 1.21%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 13       | 1.21%   |
| AMD Navi 10 HDMI Audio                                                            | 13       | 1.21%   |
| Nvidia GM204 High Definition Audio Controller                                     | 12       | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                                     | 11       | 1.03%   |
| Nvidia High Definition Audio Controller                                           | 11       | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                                     | 11       | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 11       | 1.03%   |
| Nvidia TU104 HD Audio Controller                                                  | 10       | 0.93%   |
| Nvidia GM206 High Definition Audio Controller                                     | 10       | 0.93%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 10       | 0.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 10       | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 10       | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9        | 0.84%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 9        | 0.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 9        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                                     | 8        | 0.75%   |
| Nvidia GA102 High Definition Audio Controller                                     | 8        | 0.75%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 8        | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 8        | 0.75%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8        | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                | 7        | 0.65%   |
| Nvidia GK104 HDMI Audio Controller                                                | 7        | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                                | 7        | 0.65%   |
| Intel Comet Lake PCH cAVS                                                         | 7        | 0.65%   |
| Nvidia GK106 HDMI Audio Controller                                                | 6        | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                                     | 6        | 0.56%   |
| AMD Trinity HDMI Audio Controller                                                 | 6        | 0.56%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]             | 6        | 0.56%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 5        | 0.47%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 5        | 0.47%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 5        | 0.47%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                             | 5        | 0.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4        | 0.37%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 0.37%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 0.37%   |
| Nvidia GF106 High Definition Audio Controller                                     | 4        | 0.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 4        | 0.37%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                          | 4        | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 69       | 21.9%   |
| Kingston            | 57       | 18.1%   |
| G.Skill             | 45       | 14.29%  |
| Crucial             | 44       | 13.97%  |
| Unknown             | 34       | 10.79%  |
| Samsung Electronics | 20       | 6.35%   |
| SK hynix            | 16       | 5.08%   |
| Micron Technology   | 7        | 2.22%   |
| Nanya Technology    | 3        | 0.95%   |
| A-DATA Technology   | 3        | 0.95%   |
| JOY-IT              | 2        | 0.63%   |
| Elpida              | 2        | 0.63%   |
| Avant               | 2        | 0.63%   |
| Unifosa             | 1        | 0.32%   |
| Transcend           | 1        | 0.32%   |
| Toshiba             | 1        | 0.32%   |
| Team                | 1        | 0.32%   |
| TakeMS              | 1        | 0.32%   |
| Qimonda             | 1        | 0.32%   |
| PNY                 | 1        | 0.32%   |
| Mushkin             | 1        | 0.32%   |
| Hitachi             | 1        | 0.32%   |
| Hewlett-Packard     | 1        | 0.32%   |
| Unknown             | 1        | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 10       | 2.93%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 8        | 2.35%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 8        | 2.35%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s | 5        | 1.47%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s      | 4        | 1.17%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 4        | 1.17%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 4        | 1.17%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3000MT/s    | 4        | 1.17%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 3        | 0.88%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s  | 3        | 0.88%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 3        | 0.88%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s    | 3        | 0.88%   |
| G.Skill RAM F4-2666C19-16GIS 16GB DIMM DDR4 2667MT/s     | 3        | 0.88%   |
| Corsair RAM CMX8GX3M1A1600C11 8192MB DIMM DDR3 1600MT/s  | 3        | 0.88%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s      | 3        | 0.88%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s   | 3        | 0.88%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s   | 3        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 2        | 0.59%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 2        | 0.59%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                     | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 2        | 0.59%   |
| Unknown RAM Module 1024MB DIMM DDR2 266MT/s              | 2        | 0.59%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8192MB DIMM DDR4 2465MT/s  | 2        | 0.59%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s   | 2        | 0.59%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s      | 2        | 0.59%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s   | 2        | 0.59%   |
| Kingston RAM Module 32GB DIMM DDR4 2400MT/s              | 2        | 0.59%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s     | 2        | 0.59%   |
| Kingston RAM 99U5471-002.A00LF 2GB DIMM DDR3 1334MT/s    | 2        | 0.59%   |
| Kingston RAM 9905584-027.A00LF 4GB DIMM 1600MT/s         | 2        | 0.59%   |
| JOY-IT RAM QLA304G08-GGN 4GB DIMM DDR3 1600MT/s          | 2        | 0.59%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 2        | 0.59%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s      | 2        | 0.59%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 2        | 0.59%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s     | 2        | 0.59%   |
| G.Skill RAM F3-1600C11-4GNS 4096MB DIMM DDR3 1600MT/s    | 2        | 0.59%   |
| Crucial RAM CT8G4DFRA32A.C4FE 8GB DIMM DDR4 3200MT/s     | 2        | 0.59%   |
| Crucial RAM CT102464BA160B.C16 8192MB DIMM DDR3 1600MT/s | 2        | 0.59%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3600MT/s | 2        | 0.59%   |
| Crucial RAM BL16G26C16U4W.16FD 16GB DIMM DDR4 2667MT/s   | 2        | 0.59%   |
| Corsair RAM VS2GB1333D3 2GB DIMM DDR3 1333MT/s           | 2        | 0.59%   |
| Corsair RAM CMZ16GX3M4X1600C9 4GB DIMM DDR3 1333MT/s     | 2        | 0.59%   |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s      | 2        | 0.59%   |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s   | 2        | 0.59%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s    | 2        | 0.59%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s     | 2        | 0.59%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s     | 2        | 0.59%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 2        | 0.59%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s   | 2        | 0.59%   |
| Unknown RAM Module 8GB DIMM SDRAM 1333MT/s               | 1        | 0.29%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 0.29%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                | 1        | 0.29%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.29%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s             | 1        | 0.29%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 0.29%   |
| Unknown RAM Module 8192MB DIMM 2133MT/s                  | 1        | 0.29%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                  | 1        | 0.29%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s               | 1        | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.29%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 141      | 50.72%  |
| DDR3    | 104      | 37.41%  |
| Unknown | 12       | 4.32%   |
| SDRAM   | 9        | 3.24%   |
| DDR2    | 9        | 3.24%   |
| DDR     | 3        | 1.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 263      | 96.34%  |
| SODIMM | 10       | 3.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 126      | 40.78%  |
| 4096  | 72       | 23.3%   |
| 16384 | 55       | 17.8%   |
| 2048  | 34       | 11%     |
| 32768 | 9        | 2.91%   |
| 1024  | 8        | 2.59%   |
| 512   | 3        | 0.97%   |
| 256   | 1        | 0.32%   |
| 16    | 1        | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 61       | 20.07%  |
| 3200    | 39       | 12.83%  |
| 1333    | 31       | 10.2%   |
| 2400    | 24       | 7.89%   |
| 3600    | 20       | 6.58%   |
| 3000    | 15       | 4.93%   |
| 2133    | 14       | 4.61%   |
| 2667    | 12       | 3.95%   |
| 1867    | 9        | 2.96%   |
| 3466    | 8        | 2.63%   |
| 2933    | 7        | 2.3%    |
| 667     | 6        | 1.97%   |
| 3733    | 4        | 1.32%   |
| 3400    | 4        | 1.32%   |
| 1866    | 4        | 1.32%   |
| 1066    | 4        | 1.32%   |
| 3533    | 3        | 0.99%   |
| 2800    | 3        | 0.99%   |
| 2666    | 3        | 0.99%   |
| 1334    | 3        | 0.99%   |
| 800     | 3        | 0.99%   |
| 3866    | 2        | 0.66%   |
| 3800    | 2        | 0.66%   |
| 3266    | 2        | 0.66%   |
| 3066    | 2        | 0.66%   |
| 2465    | 2        | 0.66%   |
| 1800    | 2        | 0.66%   |
| 1067    | 2        | 0.66%   |
| 400     | 2        | 0.66%   |
| 266     | 2        | 0.66%   |
| Unknown | 2        | 0.66%   |
| 50664   | 1        | 0.33%   |
| 3666    | 1        | 0.33%   |
| 3334    | 1        | 0.33%   |
| 2733    | 1        | 0.33%   |
| 1400    | 1        | 0.33%   |
| 533     | 1        | 0.33%   |
| 133     | 1        | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 8        | 25%     |
| Brother Industries    | 8        | 25%     |
| Canon                 | 7        | 21.88%  |
| Seiko Epson           | 4        | 12.5%   |
| Samsung Electronics   | 1        | 3.13%   |
| Ricoh                 | 1        | 3.13%   |
| Prolific Technology   | 1        | 3.13%   |
| Oki Data              | 1        | 3.13%   |
| Lexmark International | 1        | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2530 Series                                 | 2        | 6.25%   |
| HP Deskjet 3520 series                                     | 2        | 6.25%   |
| Brother HL-3040CN series                                   | 2        | 6.25%   |
| Seiko Epson XP-230 Series                                  | 1        | 3.13%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 3.13%   |
| Samsung C48x Series Color Laser Multifunction Printer      | 1        | 3.13%   |
| Ricoh SP 212SUw                                            | 1        | 3.13%   |
| Prolific PL2305 Parallel Port                              | 1        | 3.13%   |
| Oki Data USB Device                                        | 1        | 3.13%   |
| Lexmark International CS417dn                              | 1        | 3.13%   |
| HP OfficeJet Pro 7720 series                               | 1        | 3.13%   |
| HP LaserJet 1320                                           | 1        | 3.13%   |
| HP ENVY 5000 series                                        | 1        | 3.13%   |
| HP ENVY 4520 series                                        | 1        | 3.13%   |
| HP DeskJet 940c                                            | 1        | 3.13%   |
| HP Deskjet 2050 J510                                       | 1        | 3.13%   |
| Canon TS5100 series                                        | 1        | 3.13%   |
| Canon PIXMA MX320 series                                   | 1        | 3.13%   |
| Canon MF5650 (FAX)                                         | 1        | 3.13%   |
| Canon LiDE 300                                             | 1        | 3.13%   |
| Canon LaserShot LBP-1120 Printer                           | 1        | 3.13%   |
| Canon L100/L150/L170                                       | 1        | 3.13%   |
| Canon iP7200 series                                        | 1        | 3.13%   |
| Brother Printer                                            | 1        | 3.13%   |
| Brother MFC-L2710DW series                                 | 1        | 3.13%   |
| Brother MFC-L2710DN series                                 | 1        | 3.13%   |
| Brother MFC-9142CDN                                        | 1        | 3.13%   |
| Brother DCP-J140W                                          | 1        | 3.13%   |
| Brother DCP-1510                                           | 1        | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 17       | 73.91%  |
| Seiko Epson | 3        | 13.04%  |
| Fujitsu     | 3        | 13.04%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Fujitsu ScanSnap SV600                                   | 3        | 13.04%  |
| Canon CanoScan                                           | 3        | 13.04%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 2        | 8.7%    |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2        | 8.7%    |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 2        | 8.7%    |
| Canon CanoScan LiDE 220                                  | 2        | 8.7%    |
| Canon CanoScan LiDE 110                                  | 2        | 8.7%    |
| Canon CanoScan LiDE 100                                  | 2        | 8.7%    |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1        | 4.35%   |
| Canon CanoScan N650U/N656U                               | 1        | 4.35%   |
| Canon CanoScan N1240U/LiDE 30                            | 1        | 4.35%   |
| Canon CanoScan LiDE 210                                  | 1        | 4.35%   |
| Canon CanoScan FB630U                                    | 1        | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 37       | 40.22%  |
| Microsoft                     | 8        | 8.7%    |
| Microdia                      | 7        | 7.61%   |
| Realtek Semiconductor         | 6        | 6.52%   |
| Sunplus Innovation Technology | 4        | 4.35%   |
| ARC International             | 4        | 4.35%   |
| Apple                         | 4        | 4.35%   |
| Z-Star Microelectronics       | 3        | 3.26%   |
| Samsung Electronics           | 3        | 3.26%   |
| Fujitsu                       | 3        | 3.26%   |
| SHENZHEN EMEET TECHNOLOGY     | 2        | 2.17%   |
| Unknown                       | 1        | 1.09%   |
| SunplusIT                     | 1        | 1.09%   |
| Quanta                        | 1        | 1.09%   |
| Novatek Microelectronics      | 1        | 1.09%   |
| Nikon                         | 1        | 1.09%   |
| Jieli Technology              | 1        | 1.09%   |
| Generalplus Technology        | 1        | 1.09%   |
| GEMBIRD                       | 1        | 1.09%   |
| Etron Technology              | 1        | 1.09%   |
| Creative Technology           | 1        | 1.09%   |
| Arkmicro Technologies         | 1        | 1.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 8        | 8.7%    |
| Microsoft LifeCam HD-3000                         | 6        | 6.52%   |
| Microdia Webcam Vitade AF                         | 5        | 5.43%   |
| Logitech HD Webcam C525                           | 5        | 5.43%   |
| Logitech HD Pro Webcam C920                       | 5        | 5.43%   |
| ARC International Camera                          | 4        | 4.35%   |
| Samsung Galaxy series, misc. (MTP mode)           | 3        | 3.26%   |
| Realtek FULL HD 1080P Webcam                      | 3        | 3.26%   |
| Logitech Webcam C170                              | 3        | 3.26%   |
| Logitech QuickCam Pro for Notebooks               | 3        | 3.26%   |
| Logitech QuickCam Pro 9000                        | 3        | 3.26%   |
| Fujitsu USB Camera                                | 3        | 3.26%   |
| Z-Star Venus USB2.0 Camera                        | 2        | 2.17%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960    | 2        | 2.17%   |
| Realtek Full HD Webcam                            | 2        | 2.17%   |
| Logitech HD Webcam C510                           | 2        | 2.17%   |
| Apple iPhone 5/5C/5S/6/SE                         | 2        | 2.17%   |
| Z-Star Integrated Camera                          | 1        | 1.09%   |
| Unknown Konftel Cam20                             | 1        | 1.09%   |
| SunplusIT USB 2.0 Camera                          | 1        | 1.09%   |
| Sunplus SPCA2281 Web Camera                       | 1        | 1.09%   |
| Sunplus Full HD webcam                            | 1        | 1.09%   |
| Sunplus FHD Camera Microphone                     | 1        | 1.09%   |
| Sunplus Aukey-PC-LM1E Camera                      | 1        | 1.09%   |
| Realtek WEB CAMERA M9 Pro                         | 1        | 1.09%   |
| Quanta HD Camera                                  | 1        | 1.09%   |
| Novatek J1455                                     | 1        | 1.09%   |
| Nikon DSC D90                                     | 1        | 1.09%   |
| Microsoft MicrosoftÃ‚ LifeCam VX-5500          | 1        | 1.09%   |
| Microsoft LifeCam VX-500 [1357]                   | 1        | 1.09%   |
| Microdia USB 2.0 Camera                           | 1        | 1.09%   |
| Microdia Sonix USB 2.0 Camera                     | 1        | 1.09%   |
| Logitech Webcam Pro 9000                          | 1        | 1.09%   |
| Logitech Webcam C925e                             | 1        | 1.09%   |
| Logitech Webcam C310                              | 1        | 1.09%   |
| Logitech Webcam B500                              | 1        | 1.09%   |
| Logitech QuickCam Orbit/Sphere AF                 | 1        | 1.09%   |
| Logitech Logi 4K Stream Edition                   | 1        | 1.09%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 1.09%   |
| Logitech B525 HD Webcam                           | 1        | 1.09%   |
| Jieli USB PHY 2.0                                 | 1        | 1.09%   |
| Generalplus GENERAL WEBCAM                        | 1        | 1.09%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 1.09%   |
| Etron SPEEDLINK SNAPPY Smart Webcam               | 1        | 1.09%   |
| Creative VF0610 Live! Cam Socialize HD            | 1        | 1.09%   |
| Arkmicro USB2.0 PC CAMERA                         | 1        | 1.09%   |
| Apple iSight in LED Cinema Display                | 1        | 1.09%   |
| Apple iPhone 4S                                   | 1        | 1.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Upek                  | 1        | 50%     |
| Elan Microelectronics | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 50%     |
| Elan ELAN:Fingerprint                                  | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 50%     |
| Cherry                | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 50%     |
| Cherry Smart Terminal XX44                        | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 450      | 85.71%  |
| 1     | 60       | 11.43%  |
| 2     | 12       | 2.29%   |
| 6     | 1        | 0.19%   |
| 5     | 1        | 0.19%   |
| 4     | 1        | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 28       | 31.11%  |
| Net/wireless             | 21       | 23.33%  |
| Unassigned class         | 10       | 11.11%  |
| Communication controller | 6        | 6.67%   |
| Multimedia controller    | 4        | 4.44%   |
| Sound                    | 3        | 3.33%   |
| Net/ethernet             | 3        | 3.33%   |
| Camera                   | 3        | 3.33%   |
| Tv card                  | 2        | 2.22%   |
| Fingerprint reader       | 2        | 2.22%   |
| Bluetooth                | 2        | 2.22%   |
| Storage/raid             | 1        | 1.11%   |
| Storage/ide              | 1        | 1.11%   |
| Network                  | 1        | 1.11%   |
| Modem                    | 1        | 1.11%   |
| Chipcard                 | 1        | 1.11%   |
| Card reader              | 1        | 1.11%   |

