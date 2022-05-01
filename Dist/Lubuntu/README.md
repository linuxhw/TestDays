Lubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Lubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

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

Total: 1354

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| HP            | Pavilion g4                 | Notebook    | [d225cb6b3d](https://linux-hardware.org/?probe=d225cb6b3d) | Apr 28, 2022 |
| HP            | Pavilion g4                 | Notebook    | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| Gigabyte      | M912                        | Notebook    | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [b921f6fbae](https://linux-hardware.org/?probe=b921f6fbae) | Apr 24, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| Mediacom      | GTZS                        | Notebook    | [41939828a4](https://linux-hardware.org/?probe=41939828a4) | Apr 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [12d817136f](https://linux-hardware.org/?probe=12d817136f) | Apr 22, 2022 |
| Google        | Droid                       | Notebook    | [b7b4dc6117](https://linux-hardware.org/?probe=b7b4dc6117) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| Mediacom      | GTZS                        | Notebook    | [edc22ef82a](https://linux-hardware.org/?probe=edc22ef82a) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| Dell          | Latitude E6410              | Notebook    | [e5e350a4a8](https://linux-hardware.org/?probe=e5e350a4a8) | Apr 13, 2022 |
| Google        | Kip                         | Notebook    | [4641a94428](https://linux-hardware.org/?probe=4641a94428) | Apr 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [1a369ad73a](https://linux-hardware.org/?probe=1a369ad73a) | Apr 12, 2022 |
| ASRock        | G31M-S                      | Desktop     | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| Samsung       | 950QDB                      | Convertible | [41d1bb5ecf](https://linux-hardware.org/?probe=41d1bb5ecf) | Apr 08, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [a09ecdae05](https://linux-hardware.org/?probe=a09ecdae05) | Apr 07, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Gigabyte      | Q77M-D2H                    | Desktop     | [ecbd26a0e1](https://linux-hardware.org/?probe=ecbd26a0e1) | Apr 02, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Samsung       | N100SP                      | Notebook    | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Acer          | AOA150                      | Notebook    | [a59a005250](https://linux-hardware.org/?probe=a59a005250) | Mar 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [926a8980fc](https://linux-hardware.org/?probe=926a8980fc) | Mar 30, 2022 |
| Intel         | W7650                       | Notebook    | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | Desktop     | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [abdf251dcf](https://linux-hardware.org/?probe=abdf251dcf) | Mar 25, 2022 |
| Haier         | U1520EM                     | Notebook    | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [af80d44a27](https://linux-hardware.org/?probe=af80d44a27) | Mar 23, 2022 |
| HP            | Pavilion g7                 | Notebook    | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| IBM           | Unknown                     | Notebook    | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [d4c7ecbc5e](https://linux-hardware.org/?probe=d4c7ecbc5e) | Mar 20, 2022 |
| Acer          | AO751h                      | Notebook    | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| Google        | Celes                       | Notebook    | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| ASUSTek       | X550LA                      | Notebook    | [eb7071ed13](https://linux-hardware.org/?probe=eb7071ed13) | Mar 12, 2022 |
| Nvidia        | Tegra                       | Soc         | [3f369fa012](https://linux-hardware.org/?probe=3f369fa012) | Mar 11, 2022 |
| ASRock        | Q1900M                      | Desktop     | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | Notebook    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| ASUSTek       | M2N-SLI                     | Desktop     | [675f15b6db](https://linux-hardware.org/?probe=675f15b6db) | Mar 07, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [9c8ac31778](https://linux-hardware.org/?probe=9c8ac31778) | Mar 07, 2022 |
| HP            | 3647h                       | Desktop     | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [ac36138ae4](https://linux-hardware.org/?probe=ac36138ae4) | Mar 04, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [96416af97f](https://linux-hardware.org/?probe=96416af97f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [1da1f4ab04](https://linux-hardware.org/?probe=1da1f4ab04) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| HP            | 339A                        | Desktop     | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [ba023e3489](https://linux-hardware.org/?probe=ba023e3489) | Feb 24, 2022 |
| Insyde        | N116                        | Notebook    | [a6dd43dfb4](https://linux-hardware.org/?probe=a6dd43dfb4) | Feb 21, 2022 |
| HP            | 2AF7                        | Desktop     | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Dell          | 0DR845                      | Desktop     | [73ab1563bc](https://linux-hardware.org/?probe=73ab1563bc) | Feb 18, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |
| Alienware     | M17                         | Notebook    | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| Pegatron      | Narra6                      | Desktop     | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5601a4d596](https://linux-hardware.org/?probe=5601a4d596) | Feb 14, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [1f9694d47d](https://linux-hardware.org/?probe=1f9694d47d) | Feb 12, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [677d24e366](https://linux-hardware.org/?probe=677d24e366) | Feb 11, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3731e90788](https://linux-hardware.org/?probe=3731e90788) | Feb 11, 2022 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [b3977cd496](https://linux-hardware.org/?probe=b3977cd496) | Feb 10, 2022 |
| Positivo      | N600                        | Notebook    | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Positivo      | N600                        | Notebook    | [1591046f31](https://linux-hardware.org/?probe=1591046f31) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | Notebook    | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| ASUSTek       | Puffer                      | Desktop     | [a14c8ed9ad](https://linux-hardware.org/?probe=a14c8ed9ad) | Feb 06, 2022 |
| Unknown       | 865G-M8                     | Desktop     | [ecc67cf3bc](https://linux-hardware.org/?probe=ecc67cf3bc) | Feb 06, 2022 |
| Lenovo        | 3000 N200 0769ALU           | Notebook    | [695855f143](https://linux-hardware.org/?probe=695855f143) | Feb 05, 2022 |
| Lenovo        | 3000 N200 0769ALU           | Notebook    | [661ffedd80](https://linux-hardware.org/?probe=661ffedd80) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4c355aa7c2](https://linux-hardware.org/?probe=4c355aa7c2) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [61fc6b2cb0](https://linux-hardware.org/?probe=61fc6b2cb0) | Feb 05, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| HP            | 0A80h                       | Desktop     | [ad7e41ed45](https://linux-hardware.org/?probe=ad7e41ed45) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | Desktop     | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Toshiba       | Satellite C875              | Notebook    | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Insyde        | i101c                       | Notebook    | [375f7e61b2](https://linux-hardware.org/?probe=375f7e61b2) | Feb 02, 2022 |
| Dell          | 0FJM8V A03                  | Server      | [398f8f6326](https://linux-hardware.org/?probe=398f8f6326) | Feb 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| Google        | Peppy                       | Notebook    | [15cd563f21](https://linux-hardware.org/?probe=15cd563f21) | Jan 27, 2022 |
| HP            | 3048h                       | Desktop     | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| ASUSTek       | GL553VW                     | Notebook    | [7713319e74](https://linux-hardware.org/?probe=7713319e74) | Jan 24, 2022 |
| HP            | 3048h                       | Desktop     | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [1aa2cd2e8f](https://linux-hardware.org/?probe=1aa2cd2e8f) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | Notebook    | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [804b4adedc](https://linux-hardware.org/?probe=804b4adedc) | Jan 15, 2022 |
| Unknown       | K8Upgrade-1689              | Desktop     | [d2e29b9e82](https://linux-hardware.org/?probe=d2e29b9e82) | Jan 15, 2022 |
| Dell          | 07N90W A01                  | Desktop     | [c8db7d01bd](https://linux-hardware.org/?probe=c8db7d01bd) | Jan 15, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Nvidia        | Tegra                       | Soc         | [143a4e3c60](https://linux-hardware.org/?probe=143a4e3c60) | Jan 13, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [79e8f681f1](https://linux-hardware.org/?probe=79e8f681f1) | Jan 13, 2022 |
| HP            | Notebook                    | Notebook    | [847afd8ac5](https://linux-hardware.org/?probe=847afd8ac5) | Jan 12, 2022 |
| Acer          | WG43M                       | Desktop     | [af76e9bcfe](https://linux-hardware.org/?probe=af76e9bcfe) | Jan 12, 2022 |
| Acer          | WG43M                       | Desktop     | [5784b66aee](https://linux-hardware.org/?probe=5784b66aee) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4c24369bb7](https://linux-hardware.org/?probe=4c24369bb7) | Jan 11, 2022 |
| System76      | Lemur Pro                   | Notebook    | [fa22d4610e](https://linux-hardware.org/?probe=fa22d4610e) | Jan 11, 2022 |
| Positivo      | N600                        | Notebook    | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [9bd6fe4b7c](https://linux-hardware.org/?probe=9bd6fe4b7c) | Jan 08, 2022 |
| HP            | Compaq 6910p (GX316UC#AB... | Notebook    | [0ffa23c15e](https://linux-hardware.org/?probe=0ffa23c15e) | Jan 07, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [c8aafbbc8d](https://linux-hardware.org/?probe=c8aafbbc8d) | Jan 04, 2022 |
| Alienware     | m15                         | Notebook    | [a0d4f93250](https://linux-hardware.org/?probe=a0d4f93250) | Jan 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [eaf2e708d9](https://linux-hardware.org/?probe=eaf2e708d9) | Jan 03, 2022 |
| Acer          | Aspire 7715Z                | Notebook    | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | Notebook    | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Dell          | Latitude 7480               | Notebook    | [a338b67d45](https://linux-hardware.org/?probe=a338b67d45) | Dec 30, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Dell          | Inspiron 15 3515            | Notebook    | [8d130910ab](https://linux-hardware.org/?probe=8d130910ab) | Dec 26, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [f5924cb8b4](https://linux-hardware.org/?probe=f5924cb8b4) | Dec 25, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| ASUSTek       | A8N5X                       | Desktop     | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ea7740294a](https://linux-hardware.org/?probe=ea7740294a) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| HP            | 090Ch                       | Desktop     | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| Acer          | AOA150                      | Notebook    | [47cae573c1](https://linux-hardware.org/?probe=47cae573c1) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [2e9fd50292](https://linux-hardware.org/?probe=2e9fd50292) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [452b8c0ac4](https://linux-hardware.org/?probe=452b8c0ac4) | Dec 20, 2021 |
| Dell          | Latitude E6520              | Notebook    | [c7edb79be7](https://linux-hardware.org/?probe=c7edb79be7) | Dec 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [c52d7dc596](https://linux-hardware.org/?probe=c52d7dc596) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [a58123c368](https://linux-hardware.org/?probe=a58123c368) | Dec 17, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [175dda01f6](https://linux-hardware.org/?probe=175dda01f6) | Dec 15, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b956646608](https://linux-hardware.org/?probe=b956646608) | Dec 12, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [7cf21876b0](https://linux-hardware.org/?probe=7cf21876b0) | Dec 12, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [950da990e7](https://linux-hardware.org/?probe=950da990e7) | Dec 12, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [8419e68dd3](https://linux-hardware.org/?probe=8419e68dd3) | Dec 12, 2021 |
| ASUSTek       | 1015BXO                     | Notebook    | [f9eb963d74](https://linux-hardware.org/?probe=f9eb963d74) | Dec 12, 2021 |
| MSI           | Katana GF76 11UC            | Notebook    | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| Positivo      | AT300b                      | Notebook    | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [c5f877312c](https://linux-hardware.org/?probe=c5f877312c) | Dec 05, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [6c0aeae287](https://linux-hardware.org/?probe=6c0aeae287) | Dec 05, 2021 |
| HP            | Compaq 6510b (GR691EA#AB... | Notebook    | [4d657211eb](https://linux-hardware.org/?probe=4d657211eb) | Dec 04, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [ddafe324b7](https://linux-hardware.org/?probe=ddafe324b7) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [e9b454a745](https://linux-hardware.org/?probe=e9b454a745) | Dec 04, 2021 |
| MSI           | Boston                      | Desktop     | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| HP            | 1497                        | Desktop     | [f848ad29cd](https://linux-hardware.org/?probe=f848ad29cd) | Dec 04, 2021 |
| Acer          | AOD255E                     | Notebook    | [390afd35cb](https://linux-hardware.org/?probe=390afd35cb) | Dec 03, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [6719bb7131](https://linux-hardware.org/?probe=6719bb7131) | Dec 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [b096d0494e](https://linux-hardware.org/?probe=b096d0494e) | Dec 02, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2e5a8410bc](https://linux-hardware.org/?probe=2e5a8410bc) | Dec 01, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [edce40927f](https://linux-hardware.org/?probe=edce40927f) | Dec 01, 2021 |
| Toshiba       | Satellite C50-A-19U         | Notebook    | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| ASUSTek       | CM1435                      | Desktop     | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| HP            | Compaq 6720s                | Notebook    | [2c62d9df9c](https://linux-hardware.org/?probe=2c62d9df9c) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [0598f63a64](https://linux-hardware.org/?probe=0598f63a64) | Nov 25, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [4528ddf31d](https://linux-hardware.org/?probe=4528ddf31d) | Nov 25, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| MSI           | Boston                      | Desktop     | [71b7b63020](https://linux-hardware.org/?probe=71b7b63020) | Nov 25, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Gigabyte      | A520I AC                    | Desktop     | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Dell          | Latitude 3330               | Notebook    | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [2f1bc07165](https://linux-hardware.org/?probe=2f1bc07165) | Nov 17, 2021 |
| Medion        | P6630                       | Notebook    | [edc09031bd](https://linux-hardware.org/?probe=edc09031bd) | Nov 16, 2021 |
| HP            | Pavilion dv6                | Notebook    | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | Notebook    | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Dell          | 0T568R A00                  | Desktop     | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| Intel         | S1200BTL E98681-307         | Server      | [13f02631fe](https://linux-hardware.org/?probe=13f02631fe) | Nov 12, 2021 |
| Acer          | Aspire X1700                | Desktop     | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| Acer          | AO751h                      | Notebook    | [e2beb798cc](https://linux-hardware.org/?probe=e2beb798cc) | Nov 10, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [03bba840c5](https://linux-hardware.org/?probe=03bba840c5) | Nov 07, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [25f858c7b1](https://linux-hardware.org/?probe=25f858c7b1) | Nov 05, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [5cea4f8e91](https://linux-hardware.org/?probe=5cea4f8e91) | Nov 04, 2021 |
| Mediacom      | GTZS                        | Notebook    | [a2a881793d](https://linux-hardware.org/?probe=a2a881793d) | Nov 03, 2021 |
| Foxconn       | 2AA9h                       | Desktop     | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| Medion        | MS-7728                     | Desktop     | [564ffdab3d](https://linux-hardware.org/?probe=564ffdab3d) | Nov 02, 2021 |
| HP            | ProBook 4540s               | Notebook    | [fca622f4c4](https://linux-hardware.org/?probe=fca622f4c4) | Nov 01, 2021 |
| Samsung       | R40/R41                     | Notebook    | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [2c6c86b1fb](https://linux-hardware.org/?probe=2c6c86b1fb) | Oct 31, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e12d7e47e6](https://linux-hardware.org/?probe=e12d7e47e6) | Oct 31, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f86520f5a7](https://linux-hardware.org/?probe=f86520f5a7) | Oct 28, 2021 |
| HP            | Presario CQ58               | Notebook    | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | Notebook    | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| HP            | 2000                        | Notebook    | [65ec913842](https://linux-hardware.org/?probe=65ec913842) | Oct 27, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [45ba0657f1](https://linux-hardware.org/?probe=45ba0657f1) | Oct 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| Samsung       | N100SP                      | Notebook    | [7e4ef50289](https://linux-hardware.org/?probe=7e4ef50289) | Oct 26, 2021 |
| MSI           | MS-7309                     | Desktop     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| Samsung       | N100SP                      | Notebook    | [66b0ed9638](https://linux-hardware.org/?probe=66b0ed9638) | Oct 25, 2021 |
| Acer          | TravelMate P253             | Notebook    | [d74c10f41f](https://linux-hardware.org/?probe=d74c10f41f) | Oct 24, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Samsung       | N100SP                      | Notebook    | [4d8eadf806](https://linux-hardware.org/?probe=4d8eadf806) | Oct 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Acer          | Aspire ES1-131              | Notebook    | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| Intel         | W7650                       | Notebook    | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [15969208ae](https://linux-hardware.org/?probe=15969208ae) | Oct 18, 2021 |
| Unknown       | X99-D8                      | Desktop     | [e335225bdb](https://linux-hardware.org/?probe=e335225bdb) | Oct 17, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | Notebook    | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| Noblex        | E11IS2                      | Notebook    | [463e1f38e8](https://linux-hardware.org/?probe=463e1f38e8) | Oct 14, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | 2000                        | Notebook    | [d84546de1b](https://linux-hardware.org/?probe=d84546de1b) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| MSI           | B350 TOMAHAWK PLUS          | Desktop     | [acbc75f1b8](https://linux-hardware.org/?probe=acbc75f1b8) | Oct 06, 2021 |
| Unknown       | X79M2-Q                     | Desktop     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2f7c2f51f8](https://linux-hardware.org/?probe=2f7c2f51f8) | Oct 01, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| Sony          | VPCSA2FGX                   | Notebook    | [60cfbaebef](https://linux-hardware.org/?probe=60cfbaebef) | Sep 29, 2021 |
| Toshiba       | Satellite L755D             | Notebook    | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| Pegatron      | Acacia                      | Desktop     | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| ZOTAC         | NM10                        | Desktop     | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [29a6b45091](https://linux-hardware.org/?probe=29a6b45091) | Sep 26, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [5ed9f083e1](https://linux-hardware.org/?probe=5ed9f083e1) | Sep 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Foxconn       | Priv                        | Desktop     | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | Desktop     | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [c45de8d3b1](https://linux-hardware.org/?probe=c45de8d3b1) | Sep 21, 2021 |
| Toshiba       | Satellite L20               | Notebook    | [654c60e971](https://linux-hardware.org/?probe=654c60e971) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [64604612b2](https://linux-hardware.org/?probe=64604612b2) | Sep 19, 2021 |
| ASUSTek       | P8C WS                      | Desktop     | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| Foxconn       | 2AAF                        | Desktop     | [be2ce05253](https://linux-hardware.org/?probe=be2ce05253) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [b50449f73f](https://linux-hardware.org/?probe=b50449f73f) | Sep 14, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [be96e8a7e1](https://linux-hardware.org/?probe=be96e8a7e1) | Sep 13, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [f1414fdf7b](https://linux-hardware.org/?probe=f1414fdf7b) | Sep 13, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Dell          | 01V648 A03                  | Server      | [f46a021c88](https://linux-hardware.org/?probe=f46a021c88) | Sep 02, 2021 |
| Toshiba       | Satellite A215              | Notebook    | [2d0d778e8e](https://linux-hardware.org/?probe=2d0d778e8e) | Aug 31, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [e6c4f7b650](https://linux-hardware.org/?probe=e6c4f7b650) | Aug 30, 2021 |
| Notebook      | NL40_50GU                   | Notebook    | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| Google        | Careena                     | Notebook    | [ab1bafda25](https://linux-hardware.org/?probe=ab1bafda25) | Aug 27, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [50f9ce0180](https://linux-hardware.org/?probe=50f9ce0180) | Aug 26, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [6e1f484406](https://linux-hardware.org/?probe=6e1f484406) | Aug 24, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0fa53c65bb](https://linux-hardware.org/?probe=0fa53c65bb) | Aug 24, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [a4693372f9](https://linux-hardware.org/?probe=a4693372f9) | Aug 24, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [f09b96d997](https://linux-hardware.org/?probe=f09b96d997) | Aug 20, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [42151c3765](https://linux-hardware.org/?probe=42151c3765) | Aug 20, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [63b870739f](https://linux-hardware.org/?probe=63b870739f) | Aug 19, 2021 |
| MSI           | 760GM-E51                   | Desktop     | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [c696bffde7](https://linux-hardware.org/?probe=c696bffde7) | Aug 19, 2021 |
| Nvidia        | Tegra                       | Soc         | [369b72f0fd](https://linux-hardware.org/?probe=369b72f0fd) | Aug 18, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [90eb20e882](https://linux-hardware.org/?probe=90eb20e882) | Aug 17, 2021 |
| MSI           | Boston                      | Desktop     | [d706f54222](https://linux-hardware.org/?probe=d706f54222) | Aug 16, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [7c15d3c35d](https://linux-hardware.org/?probe=7c15d3c35d) | Aug 16, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [bc09a1e988](https://linux-hardware.org/?probe=bc09a1e988) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | Notebook    | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| MSI           | Boston                      | Desktop     | [2a5e7f9687](https://linux-hardware.org/?probe=2a5e7f9687) | Aug 12, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [798feee097](https://linux-hardware.org/?probe=798feee097) | Aug 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| HP            | Pavilion g4                 | Notebook    | [f1d3ddf197](https://linux-hardware.org/?probe=f1d3ddf197) | Aug 06, 2021 |
| MSI           | Boston                      | Desktop     | [c61c0e3351](https://linux-hardware.org/?probe=c61c0e3351) | Aug 05, 2021 |
| Dell          | G3 3500                     | Notebook    | [239b740235](https://linux-hardware.org/?probe=239b740235) | Aug 03, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [7ca0de35b4](https://linux-hardware.org/?probe=7ca0de35b4) | Aug 01, 2021 |
| Dell          | Latitude E5450              | Notebook    | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | 8299                        | Desktop     | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [b62225a801](https://linux-hardware.org/?probe=b62225a801) | Jul 24, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [db933e0ebd](https://linux-hardware.org/?probe=db933e0ebd) | Jul 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [51a121d461](https://linux-hardware.org/?probe=51a121d461) | Jul 24, 2021 |
| Intel         | DG965SS AAD41678-307        | Desktop     | [d3f38dbf63](https://linux-hardware.org/?probe=d3f38dbf63) | Jul 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [d77a8cde0f](https://linux-hardware.org/?probe=d77a8cde0f) | Jul 23, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Dell          | Inspiron M5040              | Notebook    | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Dell          | 0CN7X8 A05                  | Server      | [e5766c8331](https://linux-hardware.org/?probe=e5766c8331) | Jul 22, 2021 |
| HP            | 0A1Ch E                     | Desktop     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| Gigabyte      | B450M H                     | Desktop     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| Sony          | SVE1113M1EW                 | Notebook    | [b01beadd52](https://linux-hardware.org/?probe=b01beadd52) | Jul 16, 2021 |
| Toshiba       | K201                        | Notebook    | [85abf16ca0](https://linux-hardware.org/?probe=85abf16ca0) | Jul 15, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| Google        | Winky                       | Notebook    | [696230b066](https://linux-hardware.org/?probe=696230b066) | Jul 14, 2021 |
| Google        | Winky                       | Notebook    | [6048ac2ff9](https://linux-hardware.org/?probe=6048ac2ff9) | Jul 14, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [0f8c7a6b66](https://linux-hardware.org/?probe=0f8c7a6b66) | Jul 12, 2021 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [572b814c9a](https://linux-hardware.org/?probe=572b814c9a) | Jul 11, 2021 |
| Medion        | E3216 MD60900               | Convertible | [bc2d5652f6](https://linux-hardware.org/?probe=bc2d5652f6) | Jul 10, 2021 |
| HP            | 3397                        | Desktop     | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| LEADER        | TW9/SW9                     | Notebook    | [6da16947e1](https://linux-hardware.org/?probe=6da16947e1) | Jul 07, 2021 |
| Positivo      | POS-MI945AA                 | Desktop     | [2a1eda1972](https://linux-hardware.org/?probe=2a1eda1972) | Jul 07, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
| ASUSTek       | 1015PE                      | Notebook    | [051265df6e](https://linux-hardware.org/?probe=051265df6e) | Jul 05, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [b083bc08c4](https://linux-hardware.org/?probe=b083bc08c4) | Jul 04, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | Notebook    | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| ASUSTek       | P5K                         | Desktop     | [11fed8f8ae](https://linux-hardware.org/?probe=11fed8f8ae) | Jul 03, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| MSI           | GX780R/GT780R/GT780DXR/G... | Notebook    | [212a084b93](https://linux-hardware.org/?probe=212a084b93) | Jul 01, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [2383fe9425](https://linux-hardware.org/?probe=2383fe9425) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [e09b0ac6cf](https://linux-hardware.org/?probe=e09b0ac6cf) | Jun 30, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [b98c7e4685](https://linux-hardware.org/?probe=b98c7e4685) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [caa1dadc98](https://linux-hardware.org/?probe=caa1dadc98) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| Intel         | DG41WV AAE90316-102         | Desktop     | [c04c0fcc65](https://linux-hardware.org/?probe=c04c0fcc65) | Jun 25, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [5d8e8c301f](https://linux-hardware.org/?probe=5d8e8c301f) | Jun 24, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [8a1c5e9daf](https://linux-hardware.org/?probe=8a1c5e9daf) | Jun 21, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [d94415969c](https://linux-hardware.org/?probe=d94415969c) | Jun 19, 2021 |
| Notebook      | NHxxRZQ                     | Notebook    | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [5e9110ee62](https://linux-hardware.org/?probe=5e9110ee62) | Jun 18, 2021 |
| IBM           | 8183V6D                     | Desktop     | [d5c4e8c76b](https://linux-hardware.org/?probe=d5c4e8c76b) | Jun 18, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [51b0adff27](https://linux-hardware.org/?probe=51b0adff27) | Jun 17, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [b8cf45e412](https://linux-hardware.org/?probe=b8cf45e412) | Jun 15, 2021 |
| Positivo      | Mobile                      | Notebook    | [050aa55013](https://linux-hardware.org/?probe=050aa55013) | Jun 14, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [b14314b1d4](https://linux-hardware.org/?probe=b14314b1d4) | Jun 12, 2021 |
| Samsung       | RC512                       | Notebook    | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | Notebook    | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | Notebook    | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [0eb8caf654](https://linux-hardware.org/?probe=0eb8caf654) | Jun 08, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | Notebook    | [0a5cb29f98](https://linux-hardware.org/?probe=0a5cb29f98) | Jun 07, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | Notebook    | [29f66db2d1](https://linux-hardware.org/?probe=29f66db2d1) | Jun 07, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [5824a05a58](https://linux-hardware.org/?probe=5824a05a58) | Jun 05, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [f4ce6e2f6a](https://linux-hardware.org/?probe=f4ce6e2f6a) | Jun 02, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [52c67d407d](https://linux-hardware.org/?probe=52c67d407d) | May 31, 2021 |
| Lenovo        | ThinkPad T410s 2924C39      | Notebook    | [5dc4a1e557](https://linux-hardware.org/?probe=5dc4a1e557) | May 31, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [2e325cddc1](https://linux-hardware.org/?probe=2e325cddc1) | May 30, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [417206cc6a](https://linux-hardware.org/?probe=417206cc6a) | May 30, 2021 |
| Dell          | Latitude D820               | Notebook    | [5b23528d58](https://linux-hardware.org/?probe=5b23528d58) | May 29, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| HP            | ProBook 6550b               | Notebook    | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | Latitude D630               | Notebook    | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| ASUSTek       | K8N                         | Desktop     | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| HP            | 1905                        | Desktop     | [fd0f9e5ab1](https://linux-hardware.org/?probe=fd0f9e5ab1) | May 23, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [3eb7729825](https://linux-hardware.org/?probe=3eb7729825) | May 23, 2021 |
| HP            | 09C4h                       | Desktop     | [a94946d561](https://linux-hardware.org/?probe=a94946d561) | May 23, 2021 |
| HP            | 21B4 A01                    | Desktop     | [b2a7cbbc72](https://linux-hardware.org/?probe=b2a7cbbc72) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Dell          | 0HY175 A03                  | Desktop     | [d1b6626b26](https://linux-hardware.org/?probe=d1b6626b26) | May 20, 2021 |
| HP            | 1905                        | Desktop     | [28fb3ce7e8](https://linux-hardware.org/?probe=28fb3ce7e8) | May 20, 2021 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [bc53ad8072](https://linux-hardware.org/?probe=bc53ad8072) | May 20, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [6e24cb56ad](https://linux-hardware.org/?probe=6e24cb56ad) | May 19, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | K8N                         | Desktop     | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| HP            | Presario V5000 (ET820UA#... | Notebook    | [f91a752d4d](https://linux-hardware.org/?probe=f91a752d4d) | May 19, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [e819e51835](https://linux-hardware.org/?probe=e819e51835) | May 18, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [c23a919651](https://linux-hardware.org/?probe=c23a919651) | May 18, 2021 |
| Acer          | Extensa 5620                | Notebook    | [2da2f6a795](https://linux-hardware.org/?probe=2da2f6a795) | May 17, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [aa3fceee37](https://linux-hardware.org/?probe=aa3fceee37) | May 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| Lenovo        | ThinkPad X240 20AMS2P400    | Notebook    | [9f6e7024d4](https://linux-hardware.org/?probe=9f6e7024d4) | May 13, 2021 |
| MSI           | H61M-E33                    | Desktop     | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [a54c655ae8](https://linux-hardware.org/?probe=a54c655ae8) | May 12, 2021 |
| Packard Be... | EasyNote MH35               | Notebook    | [b755c5449a](https://linux-hardware.org/?probe=b755c5449a) | May 11, 2021 |
| ASUSTek       | K8N                         | Desktop     | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [c42f475a67](https://linux-hardware.org/?probe=c42f475a67) | May 08, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8c9dd0e965](https://linux-hardware.org/?probe=8c9dd0e965) | May 06, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | Notebook    | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [0b34a1f92d](https://linux-hardware.org/?probe=0b34a1f92d) | May 04, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| IBM           | 8183V6D                     | Desktop     | [0df40278d1](https://linux-hardware.org/?probe=0df40278d1) | May 02, 2021 |
| HP            | Notebook                    | Notebook    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| Lenovo        | 100-14IBY 80R7              | Notebook    | [61af9638d2](https://linux-hardware.org/?probe=61af9638d2) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [ef051b442a](https://linux-hardware.org/?probe=ef051b442a) | Apr 28, 2021 |
| Packard Be... | imedia S1350                | Desktop     | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [de8b267423](https://linux-hardware.org/?probe=de8b267423) | Apr 25, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [c660d95c3f](https://linux-hardware.org/?probe=c660d95c3f) | Apr 25, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [cf6ec831df](https://linux-hardware.org/?probe=cf6ec831df) | Apr 25, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Vostro A90                  | Notebook    | [21b167db8c](https://linux-hardware.org/?probe=21b167db8c) | Apr 25, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Intel         | DX58SO AAE29331-404         | Desktop     | [e4f384c278](https://linux-hardware.org/?probe=e4f384c278) | Apr 24, 2021 |
| Gateway       | Blade-K8F                   | Notebook    | [13e1a6028e](https://linux-hardware.org/?probe=13e1a6028e) | Apr 24, 2021 |
| Dell          | Inspiron 7706 2n1           | Convertible | [82eb222c26](https://linux-hardware.org/?probe=82eb222c26) | Apr 23, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [04a4129216](https://linux-hardware.org/?probe=04a4129216) | Apr 20, 2021 |
| Intel Clie... | LAPQC71B                    | Notebook    | [272956b140](https://linux-hardware.org/?probe=272956b140) | Apr 20, 2021 |
| Acer          | Aspire V5-123               | Notebook    | [448b0afd35](https://linux-hardware.org/?probe=448b0afd35) | Apr 20, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [f03d856fe1](https://linux-hardware.org/?probe=f03d856fe1) | Apr 20, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Toshiba       | Satellite L35               | Notebook    | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| HP            | Compaq 6820s                | Notebook    | [551053e9d6](https://linux-hardware.org/?probe=551053e9d6) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | Notebook    | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| Toshiba       | Satellite L450              | Notebook    | [2c5ef0687b](https://linux-hardware.org/?probe=2c5ef0687b) | Apr 13, 2021 |
| Intel         | D525MW AAE93082-401         | Desktop     | [aea7beb5c3](https://linux-hardware.org/?probe=aea7beb5c3) | Apr 12, 2021 |
| HP            | EliteBook 8440p (VV954AV... | Notebook    | [3e0b56daf3](https://linux-hardware.org/?probe=3e0b56daf3) | Apr 12, 2021 |
| ASHI          | Unknown                     | Notebook    | [68a2b34c2f](https://linux-hardware.org/?probe=68a2b34c2f) | Apr 12, 2021 |
| HP            | ProBook 6560b               | Notebook    | [8c2a2cfdef](https://linux-hardware.org/?probe=8c2a2cfdef) | Apr 12, 2021 |
| ASUSTek       | P7P55 LX                    | Desktop     | [219757d806](https://linux-hardware.org/?probe=219757d806) | Apr 11, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [0f6ed90100](https://linux-hardware.org/?probe=0f6ed90100) | Apr 11, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [530be6ce7b](https://linux-hardware.org/?probe=530be6ce7b) | Apr 08, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | Notebook    | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [a7f2749d3b](https://linux-hardware.org/?probe=a7f2749d3b) | Apr 06, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [2c58a29c2a](https://linux-hardware.org/?probe=2c58a29c2a) | Apr 02, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d36d3e1e58](https://linux-hardware.org/?probe=d36d3e1e58) | Apr 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | Notebook    | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| MSI           | Boston                      | Desktop     | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6224897fde](https://linux-hardware.org/?probe=6224897fde) | Mar 29, 2021 |
| HP            | 1589                        | Desktop     | [8b3a28644e](https://linux-hardware.org/?probe=8b3a28644e) | Mar 28, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [25fd34ad8f](https://linux-hardware.org/?probe=25fd34ad8f) | Mar 27, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [354da6602b](https://linux-hardware.org/?probe=354da6602b) | Mar 27, 2021 |
| HP            | 8054                        | Desktop     | [b3bc9388b0](https://linux-hardware.org/?probe=b3bc9388b0) | Mar 27, 2021 |
| HP            | 1589                        | Desktop     | [7b3c9bf186](https://linux-hardware.org/?probe=7b3c9bf186) | Mar 27, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [b477c99ab7](https://linux-hardware.org/?probe=b477c99ab7) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [383cee85b7](https://linux-hardware.org/?probe=383cee85b7) | Mar 25, 2021 |
| Dell          | Latitude D810               | Notebook    | [ca3886900f](https://linux-hardware.org/?probe=ca3886900f) | Mar 25, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [e366c8c206](https://linux-hardware.org/?probe=e366c8c206) | Mar 24, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [83716bfba8](https://linux-hardware.org/?probe=83716bfba8) | Mar 24, 2021 |
| HP            | 21D0                        | Desktop     | [ebf910609e](https://linux-hardware.org/?probe=ebf910609e) | Mar 23, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [0baf745232](https://linux-hardware.org/?probe=0baf745232) | Mar 21, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Samsung       | 950QCG                      | Convertible | [657a462187](https://linux-hardware.org/?probe=657a462187) | Mar 21, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e1adceeeeb](https://linux-hardware.org/?probe=e1adceeeeb) | Mar 20, 2021 |
| Lenovo        | S10-3                       | Notebook    | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | XPS 15Z                     | Notebook    | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [8ae162d330](https://linux-hardware.org/?probe=8ae162d330) | Mar 16, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [e099627755](https://linux-hardware.org/?probe=e099627755) | Mar 15, 2021 |
| HP            | 8267 A01                    | Mini pc     | [3aa09cf72a](https://linux-hardware.org/?probe=3aa09cf72a) | Mar 15, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [2abee1f31e](https://linux-hardware.org/?probe=2abee1f31e) | Mar 14, 2021 |
| ASRock        | 775Dual-VSTA                | Desktop     | [6f870bccf3](https://linux-hardware.org/?probe=6f870bccf3) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [821bcfc074](https://linux-hardware.org/?probe=821bcfc074) | Mar 09, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [47a0bdcb00](https://linux-hardware.org/?probe=47a0bdcb00) | Mar 08, 2021 |
| ASUSTek       | P53E                        | Notebook    | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| Toshiba       | Satellite L20               | Notebook    | [e40c220e30](https://linux-hardware.org/?probe=e40c220e30) | Mar 07, 2021 |
| IBM           | 2647KNG                     | Notebook    | [65d3c4c3c2](https://linux-hardware.org/?probe=65d3c4c3c2) | Mar 07, 2021 |
| IBM           | 2647KNG                     | Notebook    | [e4d4761cfe](https://linux-hardware.org/?probe=e4d4761cfe) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [8273ed53f3](https://linux-hardware.org/?probe=8273ed53f3) | Mar 04, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| MSI           | Boston                      | Desktop     | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| Dell          | Inspiron 1012               | Notebook    | [e66eef020e](https://linux-hardware.org/?probe=e66eef020e) | Mar 03, 2021 |
| Toshiba       | Satellite A135              | Notebook    | [05bbae8a9c](https://linux-hardware.org/?probe=05bbae8a9c) | Mar 02, 2021 |
| MSI           | MS-1453                     | Notebook    | [2be581dfbb](https://linux-hardware.org/?probe=2be581dfbb) | Mar 02, 2021 |
| MSI           | MS-1453                     | Notebook    | [bfaf417259](https://linux-hardware.org/?probe=bfaf417259) | Mar 02, 2021 |
| Toshiba       | Satellite A135              | Notebook    | [1986fa7acf](https://linux-hardware.org/?probe=1986fa7acf) | Mar 02, 2021 |
| Toshiba       | Satellite A660              | Notebook    | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [439d425d4b](https://linux-hardware.org/?probe=439d425d4b) | Mar 01, 2021 |
| Lenovo        | S10-3                       | Notebook    | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3ed340b3ba](https://linux-hardware.org/?probe=3ed340b3ba) | Feb 28, 2021 |
| Dell          | 0RY007                      | Desktop     | [6172822ebb](https://linux-hardware.org/?probe=6172822ebb) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Acer          | Aspire 5610                 | Notebook    | [1cac0acc28](https://linux-hardware.org/?probe=1cac0acc28) | Feb 25, 2021 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [47d5daa739](https://linux-hardware.org/?probe=47d5daa739) | Feb 25, 2021 |
| Itautec       | Infoway w7430               | Notebook    | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | Notebook    | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c8fa1fd6d2](https://linux-hardware.org/?probe=c8fa1fd6d2) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [bda750c182](https://linux-hardware.org/?probe=bda750c182) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| ASRock        | 775VM800                    | Desktop     | [5b04151216](https://linux-hardware.org/?probe=5b04151216) | Feb 15, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [e40f1f67bd](https://linux-hardware.org/?probe=e40f1f67bd) | Feb 15, 2021 |
| Dell          | Inspiron 15-3565            | Notebook    | [7c39aa2965](https://linux-hardware.org/?probe=7c39aa2965) | Feb 14, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [0f15feb522](https://linux-hardware.org/?probe=0f15feb522) | Feb 13, 2021 |
| ASRock        | 775VM800                    | Desktop     | [d292f6ac7b](https://linux-hardware.org/?probe=d292f6ac7b) | Feb 12, 2021 |
| Intel         | ChiefRiver                  | Desktop     | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9c1652cf08](https://linux-hardware.org/?probe=9c1652cf08) | Feb 10, 2021 |
| Intel         | D945GTP AAC97834-305        | Desktop     | [fa876f7290](https://linux-hardware.org/?probe=fa876f7290) | Feb 10, 2021 |
| ASUSTek       | M2A-MX                      | Desktop     | [1541b0dbe1](https://linux-hardware.org/?probe=1541b0dbe1) | Feb 09, 2021 |
| ASUSTek       | M2A-MX                      | Desktop     | [391d63e436](https://linux-hardware.org/?probe=391d63e436) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | Desktop     | [7c78d0efc3](https://linux-hardware.org/?probe=7c78d0efc3) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | Desktop     | [beddd7c01d](https://linux-hardware.org/?probe=beddd7c01d) | Feb 09, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [f08dd9c298](https://linux-hardware.org/?probe=f08dd9c298) | Feb 08, 2021 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [a8af34d0ee](https://linux-hardware.org/?probe=a8af34d0ee) | Feb 08, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [32061cad93](https://linux-hardware.org/?probe=32061cad93) | Feb 08, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [bcad30556a](https://linux-hardware.org/?probe=bcad30556a) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | Notebook    | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | Notebook    | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | Notebook    | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| Supermicro    | X8DA3                       | Server      | [039bf2c96a](https://linux-hardware.org/?probe=039bf2c96a) | Feb 04, 2021 |
| Supermicro    | X8DA3                       | Server      | [3731f93e51](https://linux-hardware.org/?probe=3731f93e51) | Feb 04, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [51102bc7a6](https://linux-hardware.org/?probe=51102bc7a6) | Feb 04, 2021 |
| HP            | Pavilion dv6000 (RP154UA... | Notebook    | [44347b7399](https://linux-hardware.org/?probe=44347b7399) | Jan 31, 2021 |
| HP            | 3048h                       | Desktop     | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | Notebook    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [0528f0d3fa](https://linux-hardware.org/?probe=0528f0d3fa) | Jan 28, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [8b9ca2262c](https://linux-hardware.org/?probe=8b9ca2262c) | Jan 28, 2021 |
| Dell          | 0TP406                      | Desktop     | [8d298a20d5](https://linux-hardware.org/?probe=8d298a20d5) | Jan 28, 2021 |
| HP            | Notebook                    | Notebook    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Lenovo        | ThinkCentre XXXX 9632AU8    | Desktop     | [cdc139f77e](https://linux-hardware.org/?probe=cdc139f77e) | Jan 24, 2021 |
| MSI           | MS-7270                     | Desktop     | [9e5fa11934](https://linux-hardware.org/?probe=9e5fa11934) | Jan 24, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [8cf59ea427](https://linux-hardware.org/?probe=8cf59ea427) | Jan 23, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [19b2ebc706](https://linux-hardware.org/?probe=19b2ebc706) | Jan 22, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [d5121e6efb](https://linux-hardware.org/?probe=d5121e6efb) | Jan 22, 2021 |
| Dell          | Latitude 3440               | Notebook    | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [304fa83224](https://linux-hardware.org/?probe=304fa83224) | Jan 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [09c2da07b2](https://linux-hardware.org/?probe=09c2da07b2) | Jan 21, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [3460a2d2a4](https://linux-hardware.org/?probe=3460a2d2a4) | Jan 21, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [fdc50253da](https://linux-hardware.org/?probe=fdc50253da) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [3761191ef4](https://linux-hardware.org/?probe=3761191ef4) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [5446971c89](https://linux-hardware.org/?probe=5446971c89) | Jan 20, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| HP            | ProBook 6360b               | Notebook    | [3e3cda2a19](https://linux-hardware.org/?probe=3e3cda2a19) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | Notebook    | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [71a9d08996](https://linux-hardware.org/?probe=71a9d08996) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| HP            | Pavilion g6                 | Notebook    | [23360e9a39](https://linux-hardware.org/?probe=23360e9a39) | Jan 12, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [057c04b2ae](https://linux-hardware.org/?probe=057c04b2ae) | Jan 11, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [55f1890303](https://linux-hardware.org/?probe=55f1890303) | Jan 11, 2021 |
| Pegatron      | NARRA3                      | Desktop     | [ebb1428c72](https://linux-hardware.org/?probe=ebb1428c72) | Jan 11, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [3aca8223d6](https://linux-hardware.org/?probe=3aca8223d6) | Jan 09, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [9764fca96a](https://linux-hardware.org/?probe=9764fca96a) | Jan 08, 2021 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [653ea393e6](https://linux-hardware.org/?probe=653ea393e6) | Jan 06, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [1bf71bd97d](https://linux-hardware.org/?probe=1bf71bd97d) | Jan 04, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [8f5c1dc1ca](https://linux-hardware.org/?probe=8f5c1dc1ca) | Jan 04, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [266231dab8](https://linux-hardware.org/?probe=266231dab8) | Jan 04, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [4fe52138ff](https://linux-hardware.org/?probe=4fe52138ff) | Jan 04, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [d86f56eaf3](https://linux-hardware.org/?probe=d86f56eaf3) | Jan 04, 2021 |
| MSI           | MS-7250                     | Desktop     | [72950b548d](https://linux-hardware.org/?probe=72950b548d) | Jan 04, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [48edae2fa9](https://linux-hardware.org/?probe=48edae2fa9) | Jan 04, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [412fb4b348](https://linux-hardware.org/?probe=412fb4b348) | Jan 04, 2021 |
| Sony          | VPCYB35AL                   | Notebook    | [f82ea2b0dc](https://linux-hardware.org/?probe=f82ea2b0dc) | Jan 03, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | Notebook    | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [73f8eb43d6](https://linux-hardware.org/?probe=73f8eb43d6) | Jan 01, 2021 |
| Gigabyte      | H81M-HD3                    | Desktop     | [5df1b1d371](https://linux-hardware.org/?probe=5df1b1d371) | Dec 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [752fb8d0c7](https://linux-hardware.org/?probe=752fb8d0c7) | Dec 25, 2020 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [c9e03e6b85](https://linux-hardware.org/?probe=c9e03e6b85) | Dec 25, 2020 |
| eMachines     | EZ1600                      | All in one  | [a9de3eb91d](https://linux-hardware.org/?probe=a9de3eb91d) | Dec 24, 2020 |
| ASRock        | FM2A88X Pro3+               | Desktop     | [a57902b2df](https://linux-hardware.org/?probe=a57902b2df) | Dec 23, 2020 |
| eMachines     | EZ1600                      | All in one  | [7880997578](https://linux-hardware.org/?probe=7880997578) | Dec 23, 2020 |
| Lenovo        | Board                       | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Sony          | VPCYB35AL                   | Notebook    | [04597b3a72](https://linux-hardware.org/?probe=04597b3a72) | Dec 23, 2020 |
| Sony          | VPCYB35AL                   | Notebook    | [490e3a1b0a](https://linux-hardware.org/?probe=490e3a1b0a) | Dec 23, 2020 |
| Dell          | 0WG864                      | Desktop     | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | Notebook    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | Notebook    | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | Notebook    | [0377183ebd](https://linux-hardware.org/?probe=0377183ebd) | Dec 20, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | Notebook    | [17467ac4ff](https://linux-hardware.org/?probe=17467ac4ff) | Dec 20, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [cdc016f9d1](https://linux-hardware.org/?probe=cdc016f9d1) | Dec 18, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8402e6dc04](https://linux-hardware.org/?probe=8402e6dc04) | Dec 18, 2020 |
| HP            | 3031h                       | Desktop     | [b1c4657359](https://linux-hardware.org/?probe=b1c4657359) | Dec 16, 2020 |
| Acer          | Aspire 4720Z                | Notebook    | [88bd8075b2](https://linux-hardware.org/?probe=88bd8075b2) | Dec 16, 2020 |
| Acer          | Aspire 4720Z                | Notebook    | [93cfeab463](https://linux-hardware.org/?probe=93cfeab463) | Dec 16, 2020 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [43ba858067](https://linux-hardware.org/?probe=43ba858067) | Dec 16, 2020 |
| Sony          | VGN-S5XP_B                  | Notebook    | [50c6c9d78a](https://linux-hardware.org/?probe=50c6c9d78a) | Dec 15, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [8cf11c15f8](https://linux-hardware.org/?probe=8cf11c15f8) | Dec 13, 2020 |
| ASUSTek       | K53SD                       | Notebook    | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | Notebook    | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Dell          | 0WG864                      | Desktop     | [f45926d7a7](https://linux-hardware.org/?probe=f45926d7a7) | Dec 11, 2020 |
| Dell          | 0WG864                      | Desktop     | [de92f1f8e4](https://linux-hardware.org/?probe=de92f1f8e4) | Dec 11, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [8e251a6942](https://linux-hardware.org/?probe=8e251a6942) | Dec 10, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | Notebook    | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [1c0400a8c0](https://linux-hardware.org/?probe=1c0400a8c0) | Dec 10, 2020 |
| ASUSTek       | X58L                        | Notebook    | [a7fd194aaa](https://linux-hardware.org/?probe=a7fd194aaa) | Dec 07, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f31b40572a](https://linux-hardware.org/?probe=f31b40572a) | Dec 02, 2020 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| eMachines     | EMCP61M                     | Desktop     | [19e0a468d5](https://linux-hardware.org/?probe=19e0a468d5) | Dec 01, 2020 |
| eMachines     | EMCP61M                     | Desktop     | [c76fe73c42](https://linux-hardware.org/?probe=c76fe73c42) | Dec 01, 2020 |
| Gigabyte      | W466U                       | Notebook    | [527d2ea4da](https://linux-hardware.org/?probe=527d2ea4da) | Nov 30, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [ce0a64067a](https://linux-hardware.org/?probe=ce0a64067a) | Nov 29, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [d7ac62fba3](https://linux-hardware.org/?probe=d7ac62fba3) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | Desktop     | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [174de8e1d6](https://linux-hardware.org/?probe=174de8e1d6) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [7b85d35e4d](https://linux-hardware.org/?probe=7b85d35e4d) | Nov 29, 2020 |
| Panasonic     | CF-52PGNBE2M                | Notebook    | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| MSI           | P55-GD80                    | Desktop     | [409cb71474](https://linux-hardware.org/?probe=409cb71474) | Nov 27, 2020 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [761ecd0a1c](https://linux-hardware.org/?probe=761ecd0a1c) | Nov 25, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| HP            | 2820h                       | Desktop     | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | Notebook    | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [63776843ec](https://linux-hardware.org/?probe=63776843ec) | Nov 21, 2020 |
| Pegatron      | Narra6                      | Desktop     | [7878c50c46](https://linux-hardware.org/?probe=7878c50c46) | Nov 20, 2020 |
| LG Electro... | C400-G.BG21P1               | Notebook    | [033a9d8cd0](https://linux-hardware.org/?probe=033a9d8cd0) | Nov 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [bb11d08947](https://linux-hardware.org/?probe=bb11d08947) | Nov 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [4f73e063d1](https://linux-hardware.org/?probe=4f73e063d1) | Nov 19, 2020 |
| HP            | Pavilion TS 11              | Notebook    | [a71dfc4983](https://linux-hardware.org/?probe=a71dfc4983) | Nov 19, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [86e6b8d3b3](https://linux-hardware.org/?probe=86e6b8d3b3) | Nov 18, 2020 |
| Positivo      | S14BW01                     | Notebook    | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| MSI           | MS-7250                     | Desktop     | [8f408a7fec](https://linux-hardware.org/?probe=8f408a7fec) | Nov 17, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [3d005c24b6](https://linux-hardware.org/?probe=3d005c24b6) | Nov 17, 2020 |
| LG Electro... | C400-G.BG21P1               | Notebook    | [8a24bb0ec4](https://linux-hardware.org/?probe=8a24bb0ec4) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| HP            | 09F8h                       | Desktop     | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| Foxconn       | 2AA9                        | Desktop     | [dbe623f2ad](https://linux-hardware.org/?probe=dbe623f2ad) | Nov 14, 2020 |
| ECS           | Iris8                       | Desktop     | [1614d7d736](https://linux-hardware.org/?probe=1614d7d736) | Nov 14, 2020 |
| IBM           | 8183V6D                     | Desktop     | [7784e64311](https://linux-hardware.org/?probe=7784e64311) | Nov 14, 2020 |
| ECS           | Iris8                       | Desktop     | [c2d76cebd4](https://linux-hardware.org/?probe=c2d76cebd4) | Nov 14, 2020 |
| Toshiba       | Satellite L20               | Notebook    | [70c077066e](https://linux-hardware.org/?probe=70c077066e) | Nov 12, 2020 |
| HP            | ProBook 4720s               | Notebook    | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Dell          | Inspiron 5423               | Notebook    | [3bd134ed30](https://linux-hardware.org/?probe=3bd134ed30) | Nov 11, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b2054d891d](https://linux-hardware.org/?probe=b2054d891d) | Nov 10, 2020 |
| Unknown       | Unknown                     | Notebook    | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [86e840f6cb](https://linux-hardware.org/?probe=86e840f6cb) | Nov 08, 2020 |
| HP            | Unknown                     | Notebook    | [1cee50e485](https://linux-hardware.org/?probe=1cee50e485) | Nov 07, 2020 |
| Sony          | VGN-S5XP_B                  | Notebook    | [62453951ca](https://linux-hardware.org/?probe=62453951ca) | Nov 06, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [e6edfc8360](https://linux-hardware.org/?probe=e6edfc8360) | Nov 06, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [20951f6ce6](https://linux-hardware.org/?probe=20951f6ce6) | Nov 05, 2020 |
| Samsung       | SX11S                       | Notebook    | [7946db3be4](https://linux-hardware.org/?probe=7946db3be4) | Nov 05, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| HP            | 650                         | Notebook    | [d1e41ec5c0](https://linux-hardware.org/?probe=d1e41ec5c0) | Nov 03, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [2139a80238](https://linux-hardware.org/?probe=2139a80238) | Nov 03, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | Notebook    | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| IBM           | 8183V6D                     | Desktop     | [440a6a1057](https://linux-hardware.org/?probe=440a6a1057) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| HP            | 0AA8h                       | Desktop     | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | Desktop     | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| Lenovo        | 100-14IBY 80R7              | Notebook    | [2358ab2c86](https://linux-hardware.org/?probe=2358ab2c86) | Oct 31, 2020 |
| Lenovo        | 100-14IBY 80R7              | Notebook    | [48cb3a624d](https://linux-hardware.org/?probe=48cb3a624d) | Oct 31, 2020 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [3e90cc2ba4](https://linux-hardware.org/?probe=3e90cc2ba4) | Oct 31, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [986ac8d550](https://linux-hardware.org/?probe=986ac8d550) | Oct 30, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | Notebook    | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | Notebook    | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Alienware     | 13 R3                       | Notebook    | [c0fc10a320](https://linux-hardware.org/?probe=c0fc10a320) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | Notebook    | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | Notebook    | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | Notebook    | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | Notebook    | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Toshiba       | Satellite L20               | Notebook    | [9d18447b9c](https://linux-hardware.org/?probe=9d18447b9c) | Oct 26, 2020 |
| Toshiba       | Satellite L30               | Notebook    | [0504cfe362](https://linux-hardware.org/?probe=0504cfe362) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | Notebook    | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Acer          | Aspire F5-573               | Notebook    | [60b785b9cf](https://linux-hardware.org/?probe=60b785b9cf) | Oct 25, 2020 |
| Dell          | 0J3C2F A02                  | Desktop     | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| Acer          | Extensa 4620                | Notebook    | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| ASRock        | G41M-GS3                    | Desktop     | [55872633b0](https://linux-hardware.org/?probe=55872633b0) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [ed8c0e270a](https://linux-hardware.org/?probe=ed8c0e270a) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [873e321107](https://linux-hardware.org/?probe=873e321107) | Oct 20, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c1a4649fc7](https://linux-hardware.org/?probe=c1a4649fc7) | Oct 20, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [116ce8b261](https://linux-hardware.org/?probe=116ce8b261) | Oct 20, 2020 |
| HP            | Presario V5000 (RE317EA#... | Notebook    | [87b9f12d09](https://linux-hardware.org/?probe=87b9f12d09) | Oct 19, 2020 |
| HP            | Presario V5000 (RE317EA#... | Notebook    | [e09f71e34f](https://linux-hardware.org/?probe=e09f71e34f) | Oct 19, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [003da597cd](https://linux-hardware.org/?probe=003da597cd) | Oct 19, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| ASUSTek       | P5S800-VM                   | Desktop     | [abb4e0e0c2](https://linux-hardware.org/?probe=abb4e0e0c2) | Oct 17, 2020 |
| HP            | Pavilion zd8000 (EL017EA... | Notebook    | [944d295a6b](https://linux-hardware.org/?probe=944d295a6b) | Oct 16, 2020 |
| Toshiba       | Satellite L840              | Notebook    | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | Notebook    | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | Notebook    | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [706aa7bb74](https://linux-hardware.org/?probe=706aa7bb74) | Oct 13, 2020 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [132e2b687c](https://linux-hardware.org/?probe=132e2b687c) | Oct 13, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LG Electro... | C400-G.BG21P1               | Notebook    | [feb6bd4cac](https://linux-hardware.org/?probe=feb6bd4cac) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | Notebook    | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | Notebook    | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| Dell          | 0KRC95 A01                  | Desktop     | [a6576290b5](https://linux-hardware.org/?probe=a6576290b5) | Oct 10, 2020 |
| MSI           | H97M-E35                    | Desktop     | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | Notebook    | [5171d8bc33](https://linux-hardware.org/?probe=5171d8bc33) | Oct 08, 2020 |
| HP            | Pavilion dv6                | Notebook    | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [53ecc0af0c](https://linux-hardware.org/?probe=53ecc0af0c) | Oct 07, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | Notebook    | [5e75a35a7d](https://linux-hardware.org/?probe=5e75a35a7d) | Oct 07, 2020 |
| HP            | Unknown                     | Notebook    | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| HP            | Unknown                     | Notebook    | [3815163813](https://linux-hardware.org/?probe=3815163813) | Oct 06, 2020 |
| MSI           | H110M ECO                   | Desktop     | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [9a5387bb3b](https://linux-hardware.org/?probe=9a5387bb3b) | Oct 04, 2020 |
| Dell          | Latitude D630               | Notebook    | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [bcac6bcfaf](https://linux-hardware.org/?probe=bcac6bcfaf) | Oct 03, 2020 |
| HP            | Laptop 15-da2xxx            | Notebook    | [a071c6ca32](https://linux-hardware.org/?probe=a071c6ca32) | Sep 30, 2020 |
| Biostar       | N61PC-M2S                   | Desktop     | [f41fe9205d](https://linux-hardware.org/?probe=f41fe9205d) | Sep 30, 2020 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [a112988e2e](https://linux-hardware.org/?probe=a112988e2e) | Sep 28, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | Notebook    | [adb08b74c2](https://linux-hardware.org/?probe=adb08b74c2) | Sep 28, 2020 |
| Panasonic     | CF-31JAGAX1M                | Notebook    | [50fe0189f0](https://linux-hardware.org/?probe=50fe0189f0) | Sep 27, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [426bdc3586](https://linux-hardware.org/?probe=426bdc3586) | Sep 24, 2020 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Samsung       | N230                        | Notebook    | [d4ba29fa0c](https://linux-hardware.org/?probe=d4ba29fa0c) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Samsung       | N230                        | Notebook    | [786e9275d0](https://linux-hardware.org/?probe=786e9275d0) | Sep 22, 2020 |
| Gateway       | SX2185                      | Desktop     | [7404f09683](https://linux-hardware.org/?probe=7404f09683) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [c30f194de1](https://linux-hardware.org/?probe=c30f194de1) | Sep 22, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| Apple         | MacBook3,1                  | Notebook    | [900daa65d7](https://linux-hardware.org/?probe=900daa65d7) | Sep 20, 2020 |
| Dell          | 0J3C2F A02                  | Desktop     | [c1cbfad587](https://linux-hardware.org/?probe=c1cbfad587) | Sep 20, 2020 |
| Fujitsu       | FMVA05008                   | Notebook    | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| Lenovo        | 3000 N200 0769ALU           | Notebook    | [16fb38706f](https://linux-hardware.org/?probe=16fb38706f) | Sep 17, 2020 |
| ASUSTek       | 1015PE                      | Notebook    | [9328bb0c6a](https://linux-hardware.org/?probe=9328bb0c6a) | Sep 16, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [bb9ff1e41f](https://linux-hardware.org/?probe=bb9ff1e41f) | Sep 15, 2020 |
| Sony          | VPCEG25EN                   | Notebook    | [10bd76f50c](https://linux-hardware.org/?probe=10bd76f50c) | Sep 14, 2020 |
| HP            | Pavilion x2 Detachable      | Tablet      | [5c305017e8](https://linux-hardware.org/?probe=5c305017e8) | Sep 13, 2020 |
| Acer          | Aspire 3050                 | Notebook    | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| ASRock        | A320M-DGS                   | Desktop     | [0ee0a67ae6](https://linux-hardware.org/?probe=0ee0a67ae6) | Sep 13, 2020 |
| Acer          | Aspire 3050                 | Notebook    | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| HP            | 0A50h                       | Desktop     | [ace0e3fed5](https://linux-hardware.org/?probe=ace0e3fed5) | Sep 13, 2020 |
| HP            | 0A50h                       | Desktop     | [f70b1ce07f](https://linux-hardware.org/?probe=f70b1ce07f) | Sep 12, 2020 |
| ASUSTek       | F7L                         | Notebook    | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | Notebook    | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | Notebook    | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Samsung       | SX11S                       | Notebook    | [748c8347e7](https://linux-hardware.org/?probe=748c8347e7) | Sep 10, 2020 |
| Samsung       | SX11S                       | Notebook    | [de5f3f5244](https://linux-hardware.org/?probe=de5f3f5244) | Sep 10, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [2cca042481](https://linux-hardware.org/?probe=2cca042481) | Sep 10, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [84a053df62](https://linux-hardware.org/?probe=84a053df62) | Sep 09, 2020 |
| Dell          | Latitude E5450              | Notebook    | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c2a66820da](https://linux-hardware.org/?probe=c2a66820da) | Sep 06, 2020 |
| ASUSTek       | V-P8H67E                    | Desktop     | [a86b68e7e2](https://linux-hardware.org/?probe=a86b68e7e2) | Sep 05, 2020 |
| Google        | Gandof                      | Notebook    | [6b79edadc5](https://linux-hardware.org/?probe=6b79edadc5) | Sep 04, 2020 |
| HP            | Compaq Presario CQ50        | Notebook    | [18e30a3f69](https://linux-hardware.org/?probe=18e30a3f69) | Sep 02, 2020 |
| Acer          | Aspire ES1-522              | Notebook    | [c5e6143bbd](https://linux-hardware.org/?probe=c5e6143bbd) | Sep 02, 2020 |
| Acer          | Aspire ES1-523              | Notebook    | [e0afac617e](https://linux-hardware.org/?probe=e0afac617e) | Aug 31, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [121fd4e00e](https://linux-hardware.org/?probe=121fd4e00e) | Aug 30, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [3a0e9bb81b](https://linux-hardware.org/?probe=3a0e9bb81b) | Aug 30, 2020 |
| Toshiba       | Satellite L20               | Notebook    | [aa53cdd994](https://linux-hardware.org/?probe=aa53cdd994) | Aug 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5e37d8f34b](https://linux-hardware.org/?probe=5e37d8f34b) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [b5a228d9bf](https://linux-hardware.org/?probe=b5a228d9bf) | Aug 26, 2020 |
| Dell          | 0CU409                      | Desktop     | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [607ce70f10](https://linux-hardware.org/?probe=607ce70f10) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [8dcd639b58](https://linux-hardware.org/?probe=8dcd639b58) | Aug 26, 2020 |
| Acer          | Aspire ES1-523              | Notebook    | [b0a8136f20](https://linux-hardware.org/?probe=b0a8136f20) | Aug 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [50f1173d1b](https://linux-hardware.org/?probe=50f1173d1b) | Aug 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [95dde54ab4](https://linux-hardware.org/?probe=95dde54ab4) | Aug 24, 2020 |
| ASRock        | A320M-HD                    | Desktop     | [8e8b3d8d21](https://linux-hardware.org/?probe=8e8b3d8d21) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1c32470733](https://linux-hardware.org/?probe=1c32470733) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e95b44a1c2](https://linux-hardware.org/?probe=e95b44a1c2) | Aug 23, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [043232c833](https://linux-hardware.org/?probe=043232c833) | Aug 20, 2020 |
| ASUSTek       | K50C                        | Notebook    | [dd9986741e](https://linux-hardware.org/?probe=dd9986741e) | Aug 19, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [955c527ef0](https://linux-hardware.org/?probe=955c527ef0) | Aug 19, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [72e40559e9](https://linux-hardware.org/?probe=72e40559e9) | Aug 17, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| Digibras      | NH4CU03                     | Notebook    | [3ba7006e38](https://linux-hardware.org/?probe=3ba7006e38) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [18e6bfd3b5](https://linux-hardware.org/?probe=18e6bfd3b5) | Aug 14, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [ca848be2f0](https://linux-hardware.org/?probe=ca848be2f0) | Aug 12, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [723c72f289](https://linux-hardware.org/?probe=723c72f289) | Aug 12, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [a8401cc827](https://linux-hardware.org/?probe=a8401cc827) | Aug 12, 2020 |
| Philco        | 14M-W549                    | Notebook    | [d69911bb55](https://linux-hardware.org/?probe=d69911bb55) | Aug 12, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| PCChips       | A13G                        | Desktop     | [d3bc7edc49](https://linux-hardware.org/?probe=d3bc7edc49) | Aug 09, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | Notebook    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Lenovo        | Board                       | Desktop     | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [f8e01e00f5](https://linux-hardware.org/?probe=f8e01e00f5) | Aug 05, 2020 |
| Toshiba       | Satellite L310              | Notebook    | [eba63dd806](https://linux-hardware.org/?probe=eba63dd806) | Aug 03, 2020 |
| Samsung       | N150/N210/N220              | Notebook    | [e15da00326](https://linux-hardware.org/?probe=e15da00326) | Aug 02, 2020 |
| Positivo      | CHT14B                      | Notebook    | [bb848a6069](https://linux-hardware.org/?probe=bb848a6069) | Aug 01, 2020 |
| Philco        | 14F                         | Desktop     | [8fce6fc79b](https://linux-hardware.org/?probe=8fce6fc79b) | Jul 31, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [29919d9aa9](https://linux-hardware.org/?probe=29919d9aa9) | Jul 30, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [10a2f3c16b](https://linux-hardware.org/?probe=10a2f3c16b) | Jul 30, 2020 |
| HP            | 245 G6                      | Notebook    | [eb51696edd](https://linux-hardware.org/?probe=eb51696edd) | Jul 29, 2020 |
| ASUSTek       | K52Je                       | Notebook    | [5e4fd0731b](https://linux-hardware.org/?probe=5e4fd0731b) | Jul 29, 2020 |
| Dell          | Latitude C840               | Notebook    | [5489df545b](https://linux-hardware.org/?probe=5489df545b) | Jul 28, 2020 |
| Dell          | Latitude C840               | Notebook    | [8a43fc9d72](https://linux-hardware.org/?probe=8a43fc9d72) | Jul 28, 2020 |
| ASUSTek       | X101CH                      | Notebook    | [92c248f423](https://linux-hardware.org/?probe=92c248f423) | Jul 27, 2020 |
| ASUSTek       | X101CH                      | Notebook    | [a729294016](https://linux-hardware.org/?probe=a729294016) | Jul 27, 2020 |
| Acer          | AO722                       | Notebook    | [75b6a0b9d5](https://linux-hardware.org/?probe=75b6a0b9d5) | Jul 27, 2020 |
| Lenovo        | SDK0E50515 STD              | Desktop     | [def93851d7](https://linux-hardware.org/?probe=def93851d7) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| HP            | ProBook 445 G7              | Notebook    | [6507b9ca49](https://linux-hardware.org/?probe=6507b9ca49) | Jul 25, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [aea6ae732a](https://linux-hardware.org/?probe=aea6ae732a) | Jul 25, 2020 |
| Acer          | V5-171                      | Notebook    | [1f30ec8b2e](https://linux-hardware.org/?probe=1f30ec8b2e) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8b84442168](https://linux-hardware.org/?probe=8b84442168) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [468608973e](https://linux-hardware.org/?probe=468608973e) | Jul 25, 2020 |
| ASUSTek       | P7P55 LX                    | Desktop     | [b907d5353a](https://linux-hardware.org/?probe=b907d5353a) | Jul 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [fd15d7f633](https://linux-hardware.org/?probe=fd15d7f633) | Jul 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [e79c3ae616](https://linux-hardware.org/?probe=e79c3ae616) | Jul 24, 2020 |
| Intel         | H55                         | Desktop     | [f9399791b8](https://linux-hardware.org/?probe=f9399791b8) | Jul 24, 2020 |
| Acer          | Aspire F5-573               | Notebook    | [af6c0b4c67](https://linux-hardware.org/?probe=af6c0b4c67) | Jul 24, 2020 |
| Positivo      | H14BT58                     | Notebook    | [3cb433c2cc](https://linux-hardware.org/?probe=3cb433c2cc) | Jul 24, 2020 |
| ASUSTek       | 1015BX                      | Notebook    | [5f48c6c53b](https://linux-hardware.org/?probe=5f48c6c53b) | Jul 24, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [a10d8d5d4f](https://linux-hardware.org/?probe=a10d8d5d4f) | Jul 22, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [d9470e64f2](https://linux-hardware.org/?probe=d9470e64f2) | Jul 22, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| HP            | 085Ch                       | Desktop     | [c22eb5394a](https://linux-hardware.org/?probe=c22eb5394a) | Jul 22, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [3d1f4e7cb8](https://linux-hardware.org/?probe=3d1f4e7cb8) | Jul 21, 2020 |
| HP            | 085Ch                       | Desktop     | [a6b75813e8](https://linux-hardware.org/?probe=a6b75813e8) | Jul 20, 2020 |
| IBM           | Board                       | Desktop     | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [ee73a556b1](https://linux-hardware.org/?probe=ee73a556b1) | Jul 19, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [33e46bd029](https://linux-hardware.org/?probe=33e46bd029) | Jul 19, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [09f9209cda](https://linux-hardware.org/?probe=09f9209cda) | Jul 18, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [03b6eef668](https://linux-hardware.org/?probe=03b6eef668) | Jul 16, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [61727004f5](https://linux-hardware.org/?probe=61727004f5) | Jul 16, 2020 |
| Dell          | Studio 1555                 | Notebook    | [0d511c045e](https://linux-hardware.org/?probe=0d511c045e) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [b97000d1d8](https://linux-hardware.org/?probe=b97000d1d8) | Jul 16, 2020 |
| Dell          | Latitude D520               | Notebook    | [c41f563801](https://linux-hardware.org/?probe=c41f563801) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [94cba10ae4](https://linux-hardware.org/?probe=94cba10ae4) | Jul 15, 2020 |
| ASUSTek       | P5S800-VM                   | Desktop     | [214ec41334](https://linux-hardware.org/?probe=214ec41334) | Jul 14, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [448b62138b](https://linux-hardware.org/?probe=448b62138b) | Jul 14, 2020 |
| ASUSTek       | Q302LA                      | Notebook    | [c453eada8f](https://linux-hardware.org/?probe=c453eada8f) | Jul 09, 2020 |
| HP            | Notebook                    | Notebook    | [10cadcd9b6](https://linux-hardware.org/?probe=10cadcd9b6) | Jul 09, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [9e35eb4bff](https://linux-hardware.org/?probe=9e35eb4bff) | Jul 08, 2020 |
| HP            | Pavilion 15                 | Notebook    | [9f54b2c875](https://linux-hardware.org/?probe=9f54b2c875) | Jul 06, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| HP            | 3396                        | Desktop     | [820e05ee01](https://linux-hardware.org/?probe=820e05ee01) | Jul 03, 2020 |
| Acer          | Swift SF314-52G             | Notebook    | [8cd6b05831](https://linux-hardware.org/?probe=8cd6b05831) | Jul 03, 2020 |
| HP            | Pavilion dv6000 (RD870AV... | Notebook    | [921ea4c212](https://linux-hardware.org/?probe=921ea4c212) | Jul 03, 2020 |
| Acer          | Aspire ES1-331              | Notebook    | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| ASUSTek       | P5LD2EB2-DHS                | Desktop     | [66d4b86237](https://linux-hardware.org/?probe=66d4b86237) | Jul 01, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [193cbfc862](https://linux-hardware.org/?probe=193cbfc862) | Jun 30, 2020 |
| HP            | Compaq 615                  | Notebook    | [38dc3f0f55](https://linux-hardware.org/?probe=38dc3f0f55) | Jun 29, 2020 |
| Toshiba       | Satellite L20               | Notebook    | [06b394c839](https://linux-hardware.org/?probe=06b394c839) | Jun 27, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| ASUSTek       | 1011PX                      | Notebook    | [868f757bd9](https://linux-hardware.org/?probe=868f757bd9) | Jun 25, 2020 |
| Toshiba       | Satellite L20               | Notebook    | [189c3fc3a9](https://linux-hardware.org/?probe=189c3fc3a9) | Jun 25, 2020 |
| HP            | Compaq 6710b (RM338UT#AB... | Notebook    | [997dd3289c](https://linux-hardware.org/?probe=997dd3289c) | Jun 25, 2020 |
| OEM           | I41SI                       | Notebook    | [04a393c6ca](https://linux-hardware.org/?probe=04a393c6ca) | Jun 25, 2020 |
| HP            | Compaq 615                  | Notebook    | [d24b727a5b](https://linux-hardware.org/?probe=d24b727a5b) | Jun 24, 2020 |
| Acer          | Aspire one                  | Notebook    | [3eefd3d4df](https://linux-hardware.org/?probe=3eefd3d4df) | Jun 23, 2020 |
| Acer          | Aspire one                  | Notebook    | [68e2ee0c29](https://linux-hardware.org/?probe=68e2ee0c29) | Jun 23, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [8d3308bf38](https://linux-hardware.org/?probe=8d3308bf38) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| HP            | 304Ah                       | Desktop     | [196b570551](https://linux-hardware.org/?probe=196b570551) | Jun 23, 2020 |
| HP            | 304Ah                       | Desktop     | [bfe838c10f](https://linux-hardware.org/?probe=bfe838c10f) | Jun 23, 2020 |
| ASUSTek       | K52Je                       | Notebook    | [401a42e02d](https://linux-hardware.org/?probe=401a42e02d) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f7cfb3c14a](https://linux-hardware.org/?probe=f7cfb3c14a) | Jun 20, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| OEM           | I41SI                       | Notebook    | [900d32d15b](https://linux-hardware.org/?probe=900d32d15b) | Jun 20, 2020 |
| Toshiba       | Satellite L20               | Notebook    | [412df08a10](https://linux-hardware.org/?probe=412df08a10) | Jun 18, 2020 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [ee1eb9d6fb](https://linux-hardware.org/?probe=ee1eb9d6fb) | Jun 18, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [93ced4c964](https://linux-hardware.org/?probe=93ced4c964) | Jun 18, 2020 |
| HP            | 09E0h                       | Desktop     | [4979e74209](https://linux-hardware.org/?probe=4979e74209) | Jun 18, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| MSI           | 0A48                        | Desktop     | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [a612626f7b](https://linux-hardware.org/?probe=a612626f7b) | Jun 16, 2020 |
| HP            | 09E0h                       | Desktop     | [3fbd5af0ab](https://linux-hardware.org/?probe=3fbd5af0ab) | Jun 16, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [9e786bc6e0](https://linux-hardware.org/?probe=9e786bc6e0) | Jun 12, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [dbbb512dc1](https://linux-hardware.org/?probe=dbbb512dc1) | Jun 11, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [cf72cf6048](https://linux-hardware.org/?probe=cf72cf6048) | Jun 11, 2020 |
| Toshiba       | Satellite L735              | Notebook    | [71df99e435](https://linux-hardware.org/?probe=71df99e435) | Jun 11, 2020 |
| Lenovo        | MIIX 3-1030 80HV            | Tablet      | [b9bd264405](https://linux-hardware.org/?probe=b9bd264405) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [5473d1a8e3](https://linux-hardware.org/?probe=5473d1a8e3) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [ad60c0409d](https://linux-hardware.org/?probe=ad60c0409d) | Jun 09, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [4400ee29ed](https://linux-hardware.org/?probe=4400ee29ed) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [d730ecdbd6](https://linux-hardware.org/?probe=d730ecdbd6) | Jun 08, 2020 |
| Acer          | Aspire 5734Z                | Notebook    | [6af54cea15](https://linux-hardware.org/?probe=6af54cea15) | Jun 07, 2020 |
| Samsung       | RV413/RV513                 | Notebook    | [7c9043ca0a](https://linux-hardware.org/?probe=7c9043ca0a) | Jun 04, 2020 |
| Sony          | VGN-P610                    | Notebook    | [950506fe40](https://linux-hardware.org/?probe=950506fe40) | Jun 04, 2020 |
| HP            | Pavilion 15                 | Notebook    | [131d6a40c2](https://linux-hardware.org/?probe=131d6a40c2) | Jun 03, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [ea9fb1590a](https://linux-hardware.org/?probe=ea9fb1590a) | Jun 03, 2020 |
| Sony          | VGN-P610                    | Notebook    | [6c66c60336](https://linux-hardware.org/?probe=6c66c60336) | Jun 02, 2020 |
| HUAWEI        | KPL-W0X                     | Notebook    | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| Qbex          | HDC-M                       | Desktop     | [5d547380f0](https://linux-hardware.org/?probe=5d547380f0) | Jun 01, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| ASUSTek       | K45VM                       | Notebook    | [15c4339e00](https://linux-hardware.org/?probe=15c4339e00) | May 30, 2020 |
| HP            | Pavilion dv5                | Notebook    | [41390482f3](https://linux-hardware.org/?probe=41390482f3) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [6e0b7c86d5](https://linux-hardware.org/?probe=6e0b7c86d5) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [9a4a664a94](https://linux-hardware.org/?probe=9a4a664a94) | May 30, 2020 |
| Positivo      | S14CT01                     | Notebook    | [027689152b](https://linux-hardware.org/?probe=027689152b) | May 28, 2020 |
| HP            | Pavilion dv6                | Notebook    | [2431a0aa32](https://linux-hardware.org/?probe=2431a0aa32) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [4a7ecd1578](https://linux-hardware.org/?probe=4a7ecd1578) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [51f3309bfb](https://linux-hardware.org/?probe=51f3309bfb) | May 28, 2020 |
| Dell          | Latitude C840               | Notebook    | [f56665d93f](https://linux-hardware.org/?probe=f56665d93f) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [73d7cd6398](https://linux-hardware.org/?probe=73d7cd6398) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [a3759de413](https://linux-hardware.org/?probe=a3759de413) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [63b8cdead7](https://linux-hardware.org/?probe=63b8cdead7) | May 27, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [663bfb0664](https://linux-hardware.org/?probe=663bfb0664) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [26bdbf2454](https://linux-hardware.org/?probe=26bdbf2454) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [cb7235636f](https://linux-hardware.org/?probe=cb7235636f) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [0493e9e9bc](https://linux-hardware.org/?probe=0493e9e9bc) | May 27, 2020 |
| Biostar       | GF7025-M2                   | Desktop     | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [acacfa8d27](https://linux-hardware.org/?probe=acacfa8d27) | May 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [0686c2c434](https://linux-hardware.org/?probe=0686c2c434) | May 25, 2020 |
| HP            | Pavilion dv6                | Notebook    | [d2b5ccc307](https://linux-hardware.org/?probe=d2b5ccc307) | May 25, 2020 |
| Dell          | Latitude D420               | Notebook    | [40458ce50c](https://linux-hardware.org/?probe=40458ce50c) | May 25, 2020 |
| ASUSTek       | A8N-SLI                     | Desktop     | [5ccefc89ce](https://linux-hardware.org/?probe=5ccefc89ce) | May 23, 2020 |
| ASUSTek       | A8N-SLI                     | Desktop     | [2c0867a9ec](https://linux-hardware.org/?probe=2c0867a9ec) | May 23, 2020 |
| Dell          | Latitude C840               | Notebook    | [94307b80af](https://linux-hardware.org/?probe=94307b80af) | May 22, 2020 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [0ba192cc01](https://linux-hardware.org/?probe=0ba192cc01) | May 22, 2020 |
| Positivo      | Smash                       | Notebook    | [662402d21c](https://linux-hardware.org/?probe=662402d21c) | May 22, 2020 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [f231ceaf4a](https://linux-hardware.org/?probe=f231ceaf4a) | May 21, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [78df8e8526](https://linux-hardware.org/?probe=78df8e8526) | May 21, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [4da7cc2128](https://linux-hardware.org/?probe=4da7cc2128) | May 21, 2020 |
| ASUSTek       | P5S800-VM                   | Desktop     | [d491ba4166](https://linux-hardware.org/?probe=d491ba4166) | May 20, 2020 |
| ASUSTek       | P5S800-VM                   | Desktop     | [7d4f750922](https://linux-hardware.org/?probe=7d4f750922) | May 20, 2020 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [4010948e4f](https://linux-hardware.org/?probe=4010948e4f) | May 20, 2020 |
| HP            | 21B4 A01                    | Desktop     | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [bdd3ec7fdf](https://linux-hardware.org/?probe=bdd3ec7fdf) | May 19, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a68c9e0a74](https://linux-hardware.org/?probe=a68c9e0a74) | May 18, 2020 |
| Gigabyte      | 8I865G775-G                 | Desktop     | [f7d448edb4](https://linux-hardware.org/?probe=f7d448edb4) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | Desktop     | [71f901a69f](https://linux-hardware.org/?probe=71f901a69f) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | Desktop     | [bce5724752](https://linux-hardware.org/?probe=bce5724752) | May 18, 2020 |
| ASUSTek       | X201E                       | Notebook    | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| ASUSTek       | 1001HA                      | Notebook    | [973de18bf0](https://linux-hardware.org/?probe=973de18bf0) | May 17, 2020 |
| ASUSTek       | 1001HA                      | Notebook    | [ec49101a42](https://linux-hardware.org/?probe=ec49101a42) | May 17, 2020 |
| Packard Be... | EN Butterfly s              | Notebook    | [587286fd1b](https://linux-hardware.org/?probe=587286fd1b) | May 17, 2020 |
| ASUSTek       | F5N                         | Notebook    | [19a648832e](https://linux-hardware.org/?probe=19a648832e) | May 15, 2020 |
| Sony          | VGN-NR430E                  | Notebook    | [6e3da2829e](https://linux-hardware.org/?probe=6e3da2829e) | May 15, 2020 |
| Unknown       | P4M800Pro-8237              | Desktop     | [13f705413c](https://linux-hardware.org/?probe=13f705413c) | May 15, 2020 |
| Unknown       | P4M800Pro-8237              | Desktop     | [21d6bc116d](https://linux-hardware.org/?probe=21d6bc116d) | May 15, 2020 |
| VIA Techno... | P4X266-8233                 | Desktop     | [0bf3b29d80](https://linux-hardware.org/?probe=0bf3b29d80) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | Desktop     | [58b07f389d](https://linux-hardware.org/?probe=58b07f389d) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | Desktop     | [47c81c501b](https://linux-hardware.org/?probe=47c81c501b) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | Desktop     | [2ae542835d](https://linux-hardware.org/?probe=2ae542835d) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | Desktop     | [597e6a2b14](https://linux-hardware.org/?probe=597e6a2b14) | May 14, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | Desktop     | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [c0cf69cb37](https://linux-hardware.org/?probe=c0cf69cb37) | May 13, 2020 |
| Positivo      | EC10IS1                     | Notebook    | [b66b7b1fe1](https://linux-hardware.org/?probe=b66b7b1fe1) | May 12, 2020 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [7af6f2c4d4](https://linux-hardware.org/?probe=7af6f2c4d4) | May 11, 2020 |
| ASUSTek       | F5N                         | Notebook    | [81878f74de](https://linux-hardware.org/?probe=81878f74de) | May 10, 2020 |
| ASUSTek       | P5S800-VM                   | Desktop     | [a4020f35b9](https://linux-hardware.org/?probe=a4020f35b9) | May 10, 2020 |
| Toshiba       | NB505                       | Notebook    | [26eaa80c8a](https://linux-hardware.org/?probe=26eaa80c8a) | May 10, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [0e50f534db](https://linux-hardware.org/?probe=0e50f534db) | May 10, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [a8c07c11cb](https://linux-hardware.org/?probe=a8c07c11cb) | May 09, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [dd51c6c85e](https://linux-hardware.org/?probe=dd51c6c85e) | May 09, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [7ee061c41d](https://linux-hardware.org/?probe=7ee061c41d) | May 09, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [794202d954](https://linux-hardware.org/?probe=794202d954) | May 08, 2020 |
| Dell          | Latitude D810               | Notebook    | [7391f06281](https://linux-hardware.org/?probe=7391f06281) | May 07, 2020 |
| Acer          | Aspire XC-703G              | Desktop     | [87c5ee1001](https://linux-hardware.org/?probe=87c5ee1001) | May 07, 2020 |
| HP            | Notebook                    | Notebook    | [0cab8a6d17](https://linux-hardware.org/?probe=0cab8a6d17) | May 07, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Dell          | Latitude D810               | Notebook    | [da4ecfc379](https://linux-hardware.org/?probe=da4ecfc379) | May 06, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [baf1cb6830](https://linux-hardware.org/?probe=baf1cb6830) | May 06, 2020 |
| Positivo      | Mobile                      | Notebook    | [d5e1de02bb](https://linux-hardware.org/?probe=d5e1de02bb) | May 05, 2020 |
| Positivo      | Mobile                      | Notebook    | [814d59f2a0](https://linux-hardware.org/?probe=814d59f2a0) | May 05, 2020 |
| Positivo      | Mobile                      | Notebook    | [84338255ae](https://linux-hardware.org/?probe=84338255ae) | May 05, 2020 |
| HP            | 090Ch                       | Desktop     | [c471684991](https://linux-hardware.org/?probe=c471684991) | May 04, 2020 |
| HP            | 090Ch                       | Desktop     | [6f88fbc1ad](https://linux-hardware.org/?probe=6f88fbc1ad) | May 04, 2020 |
| Gigabyte      | GA-K8NF-9                   | Desktop     | [70a90ff062](https://linux-hardware.org/?probe=70a90ff062) | May 04, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [180e7f281b](https://linux-hardware.org/?probe=180e7f281b) | May 03, 2020 |
| Positivo      | Smash                       | Notebook    | [02a9fd0d4a](https://linux-hardware.org/?probe=02a9fd0d4a) | May 03, 2020 |
| Positivo      | Smash                       | Notebook    | [f9734c79af](https://linux-hardware.org/?probe=f9734c79af) | May 03, 2020 |
| VIA Techno... | P4X266-8233                 | Desktop     | [069ba04b1c](https://linux-hardware.org/?probe=069ba04b1c) | May 02, 2020 |
| Toshiba       | TECRA A3X                   | Notebook    | [52ea725f65](https://linux-hardware.org/?probe=52ea725f65) | May 02, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [fd139d35fc](https://linux-hardware.org/?probe=fd139d35fc) | May 01, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | Notebook    | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| HP            | 17E2                        | Mini pc     | [fe57173b3f](https://linux-hardware.org/?probe=fe57173b3f) | May 01, 2020 |
| Acer          | Extensa 5630                | Notebook    | [2040fe8553](https://linux-hardware.org/?probe=2040fe8553) | Apr 30, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [91d94aa092](https://linux-hardware.org/?probe=91d94aa092) | Apr 30, 2020 |
| Intel         | DN2800MT AAG23738-801       | Desktop     | [eba41acd95](https://linux-hardware.org/?probe=eba41acd95) | Apr 29, 2020 |
| Toshiba       | TECRA A8                    | Notebook    | [6110d010ad](https://linux-hardware.org/?probe=6110d010ad) | Apr 28, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [0fc9a3fc11](https://linux-hardware.org/?probe=0fc9a3fc11) | Apr 28, 2020 |
| Packard Be... | EasyNote_GN45               | Notebook    | [a06ff5e1c7](https://linux-hardware.org/?probe=a06ff5e1c7) | Apr 27, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [1a00b67e81](https://linux-hardware.org/?probe=1a00b67e81) | Apr 27, 2020 |
| Standard      | EF20EA                      | Notebook    | [11882357e0](https://linux-hardware.org/?probe=11882357e0) | Apr 26, 2020 |
| ASUSTek       | VM40B                       | Desktop     | [acf2922656](https://linux-hardware.org/?probe=acf2922656) | Apr 26, 2020 |
| ASUSTek       | VM40B                       | Desktop     | [2fc777ae6a](https://linux-hardware.org/?probe=2fc777ae6a) | Apr 26, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [74edb3ce25](https://linux-hardware.org/?probe=74edb3ce25) | Apr 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [86e4dd0977](https://linux-hardware.org/?probe=86e4dd0977) | Apr 26, 2020 |
| Toshiba       | Satellite U500              | Notebook    | [cbb92d0bb3](https://linux-hardware.org/?probe=cbb92d0bb3) | Apr 25, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [fb56e66f65](https://linux-hardware.org/?probe=fb56e66f65) | Apr 24, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| MSI           | PR200                       | Notebook    | [4da6b718ee](https://linux-hardware.org/?probe=4da6b718ee) | Apr 22, 2020 |
| MSI           | PR200                       | Notebook    | [7b74d9f38e](https://linux-hardware.org/?probe=7b74d9f38e) | Apr 22, 2020 |
| MSI           | PR200                       | Notebook    | [bd6e464307](https://linux-hardware.org/?probe=bd6e464307) | Apr 22, 2020 |
| Samsung       | 600B4B/600B5B               | Notebook    | [66fdcd74f6](https://linux-hardware.org/?probe=66fdcd74f6) | Apr 22, 2020 |
| MSI           | Boston                      | Desktop     | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| HP            | Compaq CQ58                 | Notebook    | [82172cc7b5](https://linux-hardware.org/?probe=82172cc7b5) | Apr 21, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2acae4110c](https://linux-hardware.org/?probe=2acae4110c) | Apr 20, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [01b278ea81](https://linux-hardware.org/?probe=01b278ea81) | Apr 20, 2020 |
| Acer          | Aspire X1800                | Desktop     | [beb70c1fc5](https://linux-hardware.org/?probe=beb70c1fc5) | Apr 19, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [6e83174540](https://linux-hardware.org/?probe=6e83174540) | Apr 18, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [878a9628b9](https://linux-hardware.org/?probe=878a9628b9) | Apr 18, 2020 |
| ASUSTek       | K52Je                       | Notebook    | [2954b09134](https://linux-hardware.org/?probe=2954b09134) | Apr 17, 2020 |
| ASUSTek       | K52Je                       | Notebook    | [bd4175ea08](https://linux-hardware.org/?probe=bd4175ea08) | Apr 17, 2020 |
| Toshiba       | NB505                       | Notebook    | [174dd8b4cd](https://linux-hardware.org/?probe=174dd8b4cd) | Apr 16, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [4998a5a5b5](https://linux-hardware.org/?probe=4998a5a5b5) | Apr 15, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [6500bad3f7](https://linux-hardware.org/?probe=6500bad3f7) | Apr 14, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [c263eac3e9](https://linux-hardware.org/?probe=c263eac3e9) | Apr 13, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [75fff2a0a6](https://linux-hardware.org/?probe=75fff2a0a6) | Apr 13, 2020 |
| Toshiba       | NB505                       | Notebook    | [a28c9ef432](https://linux-hardware.org/?probe=a28c9ef432) | Apr 12, 2020 |
| HP            | Compaq Presario CQ50        | Notebook    | [6c0d513235](https://linux-hardware.org/?probe=6c0d513235) | Apr 12, 2020 |
| ASUSTek       | A6R                         | Notebook    | [e298b642f1](https://linux-hardware.org/?probe=e298b642f1) | Apr 11, 2020 |
| eMachines     | EL1360G                     | Desktop     | [53d061d3b2](https://linux-hardware.org/?probe=53d061d3b2) | Apr 11, 2020 |
| Ematic        | EW147                       | Notebook    | [ea27684494](https://linux-hardware.org/?probe=ea27684494) | Apr 11, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [734c5c160a](https://linux-hardware.org/?probe=734c5c160a) | Apr 11, 2020 |
| Ematic        | EW147                       | Notebook    | [3a6dad2abe](https://linux-hardware.org/?probe=3a6dad2abe) | Apr 11, 2020 |
| Ematic        | EW147                       | Notebook    | [a6d2f7cfcf](https://linux-hardware.org/?probe=a6d2f7cfcf) | Apr 11, 2020 |
| Phoenix/Si... | M7X0SU                      | Notebook    | [c86682fc32](https://linux-hardware.org/?probe=c86682fc32) | Apr 11, 2020 |
| Dell          | 0MM599                      | Desktop     | [19e2d2af44](https://linux-hardware.org/?probe=19e2d2af44) | Apr 11, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [05de338581](https://linux-hardware.org/?probe=05de338581) | Apr 09, 2020 |
| ASUSTek       | 1000H                       | Notebook    | [ee3f7c6ddc](https://linux-hardware.org/?probe=ee3f7c6ddc) | Apr 09, 2020 |
| ASUSTek       | 1005HA                      | Notebook    | [94dda7bdc8](https://linux-hardware.org/?probe=94dda7bdc8) | Apr 08, 2020 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [77cf46ddde](https://linux-hardware.org/?probe=77cf46ddde) | Apr 06, 2020 |
| Toshiba       | NB505                       | Notebook    | [c52e8296ad](https://linux-hardware.org/?probe=c52e8296ad) | Apr 06, 2020 |
| HP            | Pavilion 15                 | Notebook    | [b7c8f5e391](https://linux-hardware.org/?probe=b7c8f5e391) | Apr 05, 2020 |
| HP            | Pavilion 15                 | Notebook    | [7c02c74049](https://linux-hardware.org/?probe=7c02c74049) | Apr 05, 2020 |
| HP            | Pavilion 15                 | Notebook    | [bbd258ed84](https://linux-hardware.org/?probe=bbd258ed84) | Apr 05, 2020 |
| HP            | Pavilion 15                 | Notebook    | [812ce15917](https://linux-hardware.org/?probe=812ce15917) | Apr 05, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [9f7081cc76](https://linux-hardware.org/?probe=9f7081cc76) | Apr 04, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [053784b92f](https://linux-hardware.org/?probe=053784b92f) | Apr 03, 2020 |
| Gigabyte      | nForce                      | Desktop     | [46e8276491](https://linux-hardware.org/?probe=46e8276491) | Apr 03, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [7759201b72](https://linux-hardware.org/?probe=7759201b72) | Apr 03, 2020 |
| HP            | Pavilion dm1                | Notebook    | [f3ade8b8f4](https://linux-hardware.org/?probe=f3ade8b8f4) | Apr 02, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [e8f51bac70](https://linux-hardware.org/?probe=e8f51bac70) | Apr 01, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [46150bf014](https://linux-hardware.org/?probe=46150bf014) | Mar 30, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [8e8dbf13fb](https://linux-hardware.org/?probe=8e8dbf13fb) | Mar 30, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [a33d65ebf9](https://linux-hardware.org/?probe=a33d65ebf9) | Mar 29, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [ceb9ae3821](https://linux-hardware.org/?probe=ceb9ae3821) | Mar 29, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [d60d4df102](https://linux-hardware.org/?probe=d60d4df102) | Mar 29, 2020 |
| Itautec       | Infoway                     | Notebook    | [6df484929a](https://linux-hardware.org/?probe=6df484929a) | Mar 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [90da63892f](https://linux-hardware.org/?probe=90da63892f) | Mar 28, 2020 |
| Dell          | 0WG864                      | Desktop     | [092ae3a8ca](https://linux-hardware.org/?probe=092ae3a8ca) | Mar 27, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [779a3bf901](https://linux-hardware.org/?probe=779a3bf901) | Mar 27, 2020 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [548577276f](https://linux-hardware.org/?probe=548577276f) | Mar 27, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [daf3f5783d](https://linux-hardware.org/?probe=daf3f5783d) | Mar 27, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [d86fb5acc6](https://linux-hardware.org/?probe=d86fb5acc6) | Mar 27, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [b01aa90028](https://linux-hardware.org/?probe=b01aa90028) | Mar 26, 2020 |
| Dell          | Inspiron 910                | Notebook    | [5a445b86f5](https://linux-hardware.org/?probe=5a445b86f5) | Mar 26, 2020 |
| Sony          | VGN-CS325J                  | Notebook    | [a2f2fc1b18](https://linux-hardware.org/?probe=a2f2fc1b18) | Mar 25, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [cdcf191c24](https://linux-hardware.org/?probe=cdcf191c24) | Mar 25, 2020 |
| Toshiba       | Satellite A100              | Notebook    | [f7fb11c89f](https://linux-hardware.org/?probe=f7fb11c89f) | Mar 25, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [be88d1499a](https://linux-hardware.org/?probe=be88d1499a) | Mar 25, 2020 |
| ASUSTek       | A8V-MQ                      | Desktop     | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| Dell          | Inspiron 910                | Notebook    | [6441625d8b](https://linux-hardware.org/?probe=6441625d8b) | Mar 24, 2020 |
| Sony          | VGN-CS325J                  | Notebook    | [628add2bae](https://linux-hardware.org/?probe=628add2bae) | Mar 23, 2020 |
| Sony          | VGN-FE21M                   | Notebook    | [b117ba3f2f](https://linux-hardware.org/?probe=b117ba3f2f) | Mar 22, 2020 |
| Dell          | Inspiron 910                | Notebook    | [50081ceef7](https://linux-hardware.org/?probe=50081ceef7) | Mar 22, 2020 |
| Sony          | VGN-CS325J                  | Notebook    | [3eeafc3bdb](https://linux-hardware.org/?probe=3eeafc3bdb) | Mar 22, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b65f9246d0](https://linux-hardware.org/?probe=b65f9246d0) | Mar 21, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [a02304934f](https://linux-hardware.org/?probe=a02304934f) | Mar 21, 2020 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [e4588ca61a](https://linux-hardware.org/?probe=e4588ca61a) | Mar 21, 2020 |
| Acer          | Aspire E1-431               | Notebook    | [7a4eb7e049](https://linux-hardware.org/?probe=7a4eb7e049) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | Notebook    | [912c22a4fd](https://linux-hardware.org/?probe=912c22a4fd) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | Notebook    | [3a11fa91b5](https://linux-hardware.org/?probe=3a11fa91b5) | Mar 20, 2020 |
| HP            | Compaq Presario CQ50        | Notebook    | [210babb2ca](https://linux-hardware.org/?probe=210babb2ca) | Mar 19, 2020 |
| HP            | Compaq Presario CQ50        | Notebook    | [faba377964](https://linux-hardware.org/?probe=faba377964) | Mar 19, 2020 |
| Thomson       | NEO14A-4BK64                | Notebook    | [a0cc23a5cf](https://linux-hardware.org/?probe=a0cc23a5cf) | Mar 19, 2020 |
| Thomson       | NEO14A-4BK64                | Notebook    | [38b21006a6](https://linux-hardware.org/?probe=38b21006a6) | Mar 19, 2020 |
| Dell          | Inspiron 910                | Notebook    | [40deae1721](https://linux-hardware.org/?probe=40deae1721) | Mar 18, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [e8d667b1cf](https://linux-hardware.org/?probe=e8d667b1cf) | Mar 17, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [1361d9dfb7](https://linux-hardware.org/?probe=1361d9dfb7) | Mar 17, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [43a588f1dd](https://linux-hardware.org/?probe=43a588f1dd) | Mar 17, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2cdafa2543](https://linux-hardware.org/?probe=2cdafa2543) | Mar 17, 2020 |
| Dell          | 0T287N A03                  | Desktop     | [02ebc6d299](https://linux-hardware.org/?probe=02ebc6d299) | Mar 16, 2020 |
| ASRock        | ConRoe865GV                 | Desktop     | [e849d8b11f](https://linux-hardware.org/?probe=e849d8b11f) | Mar 15, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [d7eb29abd9](https://linux-hardware.org/?probe=d7eb29abd9) | Mar 13, 2020 |
| ASRock        | ConRoe865GV                 | Desktop     | [2f52f8c106](https://linux-hardware.org/?probe=2f52f8c106) | Mar 12, 2020 |
| ASUSTek       | M2A-VM HDMI                 | Desktop     | [3746f6db56](https://linux-hardware.org/?probe=3746f6db56) | Mar 12, 2020 |
| ASUSTek       | 1001PXD                     | Notebook    | [011393aea9](https://linux-hardware.org/?probe=011393aea9) | Mar 12, 2020 |
| ASUSTek       | K43E                        | Notebook    | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | X51R                        | Notebook    | [27bb6f3f14](https://linux-hardware.org/?probe=27bb6f3f14) | Mar 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [2e3821b18f](https://linux-hardware.org/?probe=2e3821b18f) | Mar 11, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [30880bf78e](https://linux-hardware.org/?probe=30880bf78e) | Mar 11, 2020 |
| Dell          | Inspiron 910                | Notebook    | [b8ec7ce084](https://linux-hardware.org/?probe=b8ec7ce084) | Mar 10, 2020 |
| Acer          | Aspire ES1-571              | Notebook    | [6fa4f9484a](https://linux-hardware.org/?probe=6fa4f9484a) | Mar 10, 2020 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [c00f70d6a6](https://linux-hardware.org/?probe=c00f70d6a6) | Mar 10, 2020 |
| ASUSTek       | K43E                        | Notebook    | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |
| Acer          | Aspire ES1-571              | Notebook    | [7980f53bfc](https://linux-hardware.org/?probe=7980f53bfc) | Mar 10, 2020 |
| ASUSTek       | H81M-E                      | Desktop     | [709a2484bc](https://linux-hardware.org/?probe=709a2484bc) | Mar 09, 2020 |
| Acer          | Aspire 6930G                | Notebook    | [0ec678525f](https://linux-hardware.org/?probe=0ec678525f) | Mar 09, 2020 |
| Dell          | Inspiron 1464               | Notebook    | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [339f91031b](https://linux-hardware.org/?probe=339f91031b) | Mar 04, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [8aca087539](https://linux-hardware.org/?probe=8aca087539) | Mar 03, 2020 |
| Sony          | VPCYB15AB                   | Notebook    | [af5e9fd3c4](https://linux-hardware.org/?probe=af5e9fd3c4) | Mar 03, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [db39fea346](https://linux-hardware.org/?probe=db39fea346) | Mar 02, 2020 |
| Positivo      | MOBILE                      | Notebook    | [3dc5b2844f](https://linux-hardware.org/?probe=3dc5b2844f) | Feb 29, 2020 |
| HP            | Compaq Presario CQ50        | Notebook    | [552f694c90](https://linux-hardware.org/?probe=552f694c90) | Feb 27, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [168bd28370](https://linux-hardware.org/?probe=168bd28370) | Feb 27, 2020 |
| Positivo      | MOBILE                      | Notebook    | [6908d01959](https://linux-hardware.org/?probe=6908d01959) | Feb 26, 2020 |
| HP            | Compaq Presario CQ50        | Notebook    | [0cac2c9b86](https://linux-hardware.org/?probe=0cac2c9b86) | Feb 26, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [54921e20ad](https://linux-hardware.org/?probe=54921e20ad) | Feb 23, 2020 |
| ASUSTek       | CUSL2-M                     | Desktop     | [a20a268bb5](https://linux-hardware.org/?probe=a20a268bb5) | Feb 23, 2020 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [d44a499c90](https://linux-hardware.org/?probe=d44a499c90) | Feb 21, 2020 |
| Dell          | 08HPGT A01                  | Desktop     | [64e6dd4ba1](https://linux-hardware.org/?probe=64e6dd4ba1) | Feb 20, 2020 |
| Toshiba       | Satellite C650D             | Notebook    | [fff96c147a](https://linux-hardware.org/?probe=fff96c147a) | Feb 20, 2020 |
| Dell          | Latitude D630               | Notebook    | [81239fd39f](https://linux-hardware.org/?probe=81239fd39f) | Feb 19, 2020 |
| ASUSTek       | 1005HA                      | Notebook    | [ea9e3ae02c](https://linux-hardware.org/?probe=ea9e3ae02c) | Feb 18, 2020 |
| ASUSTek       | 1005HA                      | Notebook    | [0f5187ce04](https://linux-hardware.org/?probe=0f5187ce04) | Feb 18, 2020 |
| HP            | Stream Notebook             | Notebook    | [413af6cde9](https://linux-hardware.org/?probe=413af6cde9) | Feb 18, 2020 |
| HP            | Stream Notebook             | Notebook    | [305ee95288](https://linux-hardware.org/?probe=305ee95288) | Feb 18, 2020 |
| HP            | Stream Notebook             | Notebook    | [3cc3c65c80](https://linux-hardware.org/?probe=3cc3c65c80) | Feb 18, 2020 |
| Acer          | AOD257                      | Notebook    | [42c2447bcf](https://linux-hardware.org/?probe=42c2447bcf) | Feb 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [147eea4e00](https://linux-hardware.org/?probe=147eea4e00) | Feb 17, 2020 |
| Acer          | Aspire 9420                 | Notebook    | [eb72545df3](https://linux-hardware.org/?probe=eb72545df3) | Feb 13, 2020 |
| Acer          | Aspire 9420                 | Notebook    | [7321cd7d41](https://linux-hardware.org/?probe=7321cd7d41) | Feb 13, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [42000d4c07](https://linux-hardware.org/?probe=42000d4c07) | Feb 10, 2020 |
| HP            | 0A64h                       | Desktop     | [23d32db8b9](https://linux-hardware.org/?probe=23d32db8b9) | Feb 10, 2020 |
| Samsung       | 275E4E/275E5E               | Notebook    | [15d64735e6](https://linux-hardware.org/?probe=15d64735e6) | Feb 07, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [064e671b09](https://linux-hardware.org/?probe=064e671b09) | Feb 07, 2020 |
| HP            | 0A64h                       | Desktop     | [ded9dbdb6b](https://linux-hardware.org/?probe=ded9dbdb6b) | Feb 07, 2020 |
| HP            | 0A64h                       | Desktop     | [eed7c64698](https://linux-hardware.org/?probe=eed7c64698) | Feb 06, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [9f00848eda](https://linux-hardware.org/?probe=9f00848eda) | Feb 06, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [00e62f0a24](https://linux-hardware.org/?probe=00e62f0a24) | Feb 04, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [c8da6705be](https://linux-hardware.org/?probe=c8da6705be) | Feb 02, 2020 |
| Acer          | Lugano M                    | Notebook    | [312fa4b009](https://linux-hardware.org/?probe=312fa4b009) | Feb 02, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [10e8be6a70](https://linux-hardware.org/?probe=10e8be6a70) | Feb 02, 2020 |
| Acer          | Aspire E1-530               | Notebook    | [0e64af354b](https://linux-hardware.org/?probe=0e64af354b) | Jan 30, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [93f3eefff1](https://linux-hardware.org/?probe=93f3eefff1) | Jan 27, 2020 |
| ASRock        | N73V-S                      | Desktop     | [80b08d6e38](https://linux-hardware.org/?probe=80b08d6e38) | Jan 27, 2020 |
| ASRock        | N73V-S                      | Desktop     | [1f67c1102b](https://linux-hardware.org/?probe=1f67c1102b) | Jan 26, 2020 |
| Gigabyte      | GA-K8NF-9                   | Desktop     | [2b8833407a](https://linux-hardware.org/?probe=2b8833407a) | Jan 25, 2020 |
| MSI           | MS-7369                     | Desktop     | [5c6d33ae36](https://linux-hardware.org/?probe=5c6d33ae36) | Jan 25, 2020 |
| Dell          | Vostro A90                  | Notebook    | [26217e36fd](https://linux-hardware.org/?probe=26217e36fd) | Jan 25, 2020 |
| Dell          | Vostro A90                  | Notebook    | [ea2668497d](https://linux-hardware.org/?probe=ea2668497d) | Jan 25, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [cc1a05b68f](https://linux-hardware.org/?probe=cc1a05b68f) | Jan 24, 2020 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [88961c610a](https://linux-hardware.org/?probe=88961c610a) | Jan 23, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [179223c787](https://linux-hardware.org/?probe=179223c787) | Jan 21, 2020 |
| TrekStor      | Surfbook A13B               | Notebook    | [a5b513e810](https://linux-hardware.org/?probe=a5b513e810) | Jan 18, 2020 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [97cfb25196](https://linux-hardware.org/?probe=97cfb25196) | Jan 17, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [b63e1a7dee](https://linux-hardware.org/?probe=b63e1a7dee) | Jan 15, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [b8f9fdb262](https://linux-hardware.org/?probe=b8f9fdb262) | Jan 14, 2020 |
| ASUSTek       | 1015PN                      | Notebook    | [5619d74a6f](https://linux-hardware.org/?probe=5619d74a6f) | Jan 13, 2020 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [d96168ded2](https://linux-hardware.org/?probe=d96168ded2) | Jan 12, 2020 |
| Toshiba       | Satellite L20               | Notebook    | [271d6dbfd3](https://linux-hardware.org/?probe=271d6dbfd3) | Jan 09, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [947354716f](https://linux-hardware.org/?probe=947354716f) | Jan 07, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [045a82f0f6](https://linux-hardware.org/?probe=045a82f0f6) | Jan 06, 2020 |
| HP            | 82DD                        | All in one  | [4cb5c7afef](https://linux-hardware.org/?probe=4cb5c7afef) | Jan 05, 2020 |
| Acer          | Aspire 5542                 | Notebook    | [aeeb077808](https://linux-hardware.org/?probe=aeeb077808) | Jan 05, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [464d7a82b6](https://linux-hardware.org/?probe=464d7a82b6) | Jan 05, 2020 |
| Acer          | Aspire 5542                 | Notebook    | [1458705a5f](https://linux-hardware.org/?probe=1458705a5f) | Jan 04, 2020 |
| HP            | 0AA8h                       | Desktop     | [77b5333591](https://linux-hardware.org/?probe=77b5333591) | Jan 04, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [e5d9ec4712](https://linux-hardware.org/?probe=e5d9ec4712) | Dec 31, 2019 |
| Toshiba       | Satellite Pro S500          | Notebook    | [db0edb9f16](https://linux-hardware.org/?probe=db0edb9f16) | Dec 31, 2019 |
| Toshiba       | Satellite Pro S500          | Notebook    | [fdcb757efe](https://linux-hardware.org/?probe=fdcb757efe) | Dec 31, 2019 |
| Toshiba       | Satellite Pro S500          | Notebook    | [4cf474fd47](https://linux-hardware.org/?probe=4cf474fd47) | Dec 31, 2019 |
| Fujitsu       | LIFEBOOK S710               | Notebook    | [b3b0d2e40e](https://linux-hardware.org/?probe=b3b0d2e40e) | Dec 30, 2019 |
| HP            | Pavilion dv7                | Notebook    | [1147f13741](https://linux-hardware.org/?probe=1147f13741) | Dec 30, 2019 |
| Dell          | Studio 1555                 | Notebook    | [4507496780](https://linux-hardware.org/?probe=4507496780) | Dec 29, 2019 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [aca2eac05b](https://linux-hardware.org/?probe=aca2eac05b) | Dec 29, 2019 |
| Toshiba       | Satellite Pro S500          | Notebook    | [1bf57edaba](https://linux-hardware.org/?probe=1bf57edaba) | Dec 29, 2019 |
| Dell          | Studio 1555                 | Notebook    | [9aba9666d7](https://linux-hardware.org/?probe=9aba9666d7) | Dec 28, 2019 |
| Toshiba       | Satellite L20               | Notebook    | [2184b17801](https://linux-hardware.org/?probe=2184b17801) | Dec 28, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [666a988e9b](https://linux-hardware.org/?probe=666a988e9b) | Dec 28, 2019 |
| HP            | Compaq Presario CQ50        | Notebook    | [ad1aea7e39](https://linux-hardware.org/?probe=ad1aea7e39) | Dec 27, 2019 |
| Toshiba       | Satellite Pro S500          | Notebook    | [9be4f247b6](https://linux-hardware.org/?probe=9be4f247b6) | Dec 24, 2019 |
| Toshiba       | Satellite Pro S500          | Notebook    | [4199720757](https://linux-hardware.org/?probe=4199720757) | Dec 24, 2019 |
| HP            | Pavilion 15                 | Notebook    | [98e4efccb2](https://linux-hardware.org/?probe=98e4efccb2) | Dec 24, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [011ab343ef](https://linux-hardware.org/?probe=011ab343ef) | Dec 22, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [80bfe1c21e](https://linux-hardware.org/?probe=80bfe1c21e) | Dec 22, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [bb9da61133](https://linux-hardware.org/?probe=bb9da61133) | Dec 21, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [274eea3275](https://linux-hardware.org/?probe=274eea3275) | Dec 20, 2019 |
| Toshiba       | Satellite L20               | Notebook    | [563f05aae7](https://linux-hardware.org/?probe=563f05aae7) | Dec 18, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [030c06dbf0](https://linux-hardware.org/?probe=030c06dbf0) | Dec 15, 2019 |
| HP            | Compaq Presario CQ50        | Notebook    | [d672b4583e](https://linux-hardware.org/?probe=d672b4583e) | Dec 15, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [893a9b3000](https://linux-hardware.org/?probe=893a9b3000) | Dec 14, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [3a1243a77f](https://linux-hardware.org/?probe=3a1243a77f) | Dec 12, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [71a8ef2f9c](https://linux-hardware.org/?probe=71a8ef2f9c) | Dec 12, 2019 |
| AAEON         | MF-001 V1.0                 | Desktop     | [08480474f8](https://linux-hardware.org/?probe=08480474f8) | Dec 08, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [70309e8b8e](https://linux-hardware.org/?probe=70309e8b8e) | Dec 02, 2019 |
| Dell          | Inspiron MM061              | Notebook    | [74039c6d39](https://linux-hardware.org/?probe=74039c6d39) | Dec 01, 2019 |
| Toshiba       | Satellite Pro S500          | Notebook    | [45f548ba27](https://linux-hardware.org/?probe=45f548ba27) | Dec 01, 2019 |
| Toshiba       | Satellite Pro S500          | Notebook    | [5cf7a1f9b8](https://linux-hardware.org/?probe=5cf7a1f9b8) | Dec 01, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [36a930502d](https://linux-hardware.org/?probe=36a930502d) | Nov 30, 2019 |
| Toshiba       | Satellite Pro S500          | Notebook    | [03ab084bc4](https://linux-hardware.org/?probe=03ab084bc4) | Nov 30, 2019 |
| ASUSTek       | X51RL                       | Notebook    | [2d4367bb57](https://linux-hardware.org/?probe=2d4367bb57) | Nov 29, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [4e229f13aa](https://linux-hardware.org/?probe=4e229f13aa) | Nov 23, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [3bf663653b](https://linux-hardware.org/?probe=3bf663653b) | Nov 23, 2019 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c0c7973b78](https://linux-hardware.org/?probe=c0c7973b78) | Nov 20, 2019 |
| AMI           | Cherry Trail CR             | Notebook    | [fd9a3df2b6](https://linux-hardware.org/?probe=fd9a3df2b6) | Nov 19, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c4b7195697](https://linux-hardware.org/?probe=c4b7195697) | Nov 18, 2019 |
| Dell          | Inspiron MM061              | Notebook    | [c382fdc34a](https://linux-hardware.org/?probe=c382fdc34a) | Nov 14, 2019 |
| Sony          | SVE14A2V1EW                 | Notebook    | [e80c47963a](https://linux-hardware.org/?probe=e80c47963a) | Nov 12, 2019 |
| ASRock        | H55M                        | Desktop     | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | Desktop     | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| Acer          | Aspire XC-703               | Desktop     | [5e3493c08f](https://linux-hardware.org/?probe=5e3493c08f) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | Desktop     | [d31b932863](https://linux-hardware.org/?probe=d31b932863) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | Desktop     | [e4ae098bfc](https://linux-hardware.org/?probe=e4ae098bfc) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | Desktop     | [0a5f0a6adc](https://linux-hardware.org/?probe=0a5f0a6adc) | Nov 11, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [2e7b8ff7ae](https://linux-hardware.org/?probe=2e7b8ff7ae) | Nov 11, 2019 |
| ASUSTek       | U32U                        | Notebook    | [656773dca2](https://linux-hardware.org/?probe=656773dca2) | Oct 22, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [ccf33cd499](https://linux-hardware.org/?probe=ccf33cd499) | Oct 02, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [d7fb0ff803](https://linux-hardware.org/?probe=d7fb0ff803) | Oct 01, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [8b551f88e3](https://linux-hardware.org/?probe=8b551f88e3) | Oct 01, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [4bfb294198](https://linux-hardware.org/?probe=4bfb294198) | Oct 01, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [351b3bfda7](https://linux-hardware.org/?probe=351b3bfda7) | Sep 19, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [55480cd067](https://linux-hardware.org/?probe=55480cd067) | Sep 05, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [59fbd049bb](https://linux-hardware.org/?probe=59fbd049bb) | Aug 25, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [0b0497458b](https://linux-hardware.org/?probe=0b0497458b) | Aug 22, 2019 |
| Toshiba       | Satellite L20               | Notebook    | [10173fe107](https://linux-hardware.org/?probe=10173fe107) | Aug 18, 2019 |
| Toshiba       | Satellite L20               | Notebook    | [9e524c52e7](https://linux-hardware.org/?probe=9e524c52e7) | Jul 31, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [d85c2d26cb](https://linux-hardware.org/?probe=d85c2d26cb) | Jul 26, 2019 |
| Acer          | Aspire one 1-431            | Notebook    | [33ff5f5399](https://linux-hardware.org/?probe=33ff5f5399) | Jul 14, 2019 |
| Toshiba       | Satellite L20               | Notebook    | [ba3f405ef7](https://linux-hardware.org/?probe=ba3f405ef7) | Jul 05, 2019 |
| ASRock        | AD525PV3                    | Desktop     | [682bc26535](https://linux-hardware.org/?probe=682bc26535) | Jul 03, 2019 |
| ASUSTek       | 1215B                       | Notebook    | [5e3f89149f](https://linux-hardware.org/?probe=5e3f89149f) | Jun 29, 2019 |
| HP            | ProBook 430 G1              | Notebook    | [9be61e9a2d](https://linux-hardware.org/?probe=9be61e9a2d) | Jun 24, 2019 |
| Dell          | Inspiron 5566               | Notebook    | [a8122ef82d](https://linux-hardware.org/?probe=a8122ef82d) | Apr 26, 2019 |
| Toshiba       | Satellite L20               | Notebook    | [d9ee5a5ff8](https://linux-hardware.org/?probe=d9ee5a5ff8) | Apr 09, 2019 |
| ASUSTek       | K55VJ                       | Notebook    | [fac5cee3e3](https://linux-hardware.org/?probe=fac5cee3e3) | Apr 05, 2019 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [b99ee7c099](https://linux-hardware.org/?probe=b99ee7c099) | Apr 02, 2019 |
| Dell          | Inspiron 5566               | Notebook    | [e4dc78de4f](https://linux-hardware.org/?probe=e4dc78de4f) | Mar 28, 2019 |
| ASUSTek       | M2N4-SLI                    | Desktop     | [84abf7384b](https://linux-hardware.org/?probe=84abf7384b) | Mar 24, 2019 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [81ac047bce](https://linux-hardware.org/?probe=81ac047bce) | Mar 10, 2019 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [26ccc6c647](https://linux-hardware.org/?probe=26ccc6c647) | Mar 10, 2019 |
| Unknown       | Unknown                     | Desktop     | [52b4b037a1](https://linux-hardware.org/?probe=52b4b037a1) | Feb 01, 2019 |
| Unknown       | Unknown                     | Desktop     | [f9908c15ca](https://linux-hardware.org/?probe=f9908c15ca) | Feb 01, 2019 |
| Acer          | Aspire F5-771G              | Notebook    | [8f2bbcbea8](https://linux-hardware.org/?probe=8f2bbcbea8) | Dec 23, 2018 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [b54d9c9c47](https://linux-hardware.org/?probe=b54d9c9c47) | Dec 19, 2018 |
| PCWare        | IPX1800G2                   | Desktop     | [1721a635e2](https://linux-hardware.org/?probe=1721a635e2) | Nov 25, 2018 |
| Toshiba       | Satellite L20               | Notebook    | [409df1d9a6](https://linux-hardware.org/?probe=409df1d9a6) | Oct 30, 2018 |
| Toshiba       | Satellite L300              | Notebook    | [c50c4eed87](https://linux-hardware.org/?probe=c50c4eed87) | Sep 02, 2018 |
| ASUSTek       | X200MA                      | Notebook    | [62851925f7](https://linux-hardware.org/?probe=62851925f7) | Jul 27, 2018 |
| Lenovo        | G580 20150                  | Notebook    | [69369b93d2](https://linux-hardware.org/?probe=69369b93d2) | Jul 09, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Lubuntu 20.04   | 369       | 43.46%  |
| Lubuntu 18.04   | 184       | 21.67%  |
| Lubuntu 21.10   | 67        | 7.89%   |
| Lubuntu 19.10   | 62        | 7.3%    |
| Lubuntu 21.04   | 50        | 5.89%   |
| Lubuntu 20.10   | 46        | 5.42%   |
| Lubuntu 16.04   | 27        | 3.18%   |
| Lubuntu 19.04   | 14        | 1.65%   |
| Lubuntu 18.10   | 11        | 1.3%    |
| Lubuntu 22.04   | 10        | 1.18%   |
| Lubuntu         | 3         | 0.35%   |
| Lubuntu 16.10   | 2         | 0.24%   |
| Lubuntu 20.04.1 | 1         | 0.12%   |
| Lubuntu 18.04.4 | 1         | 0.12%   |
| Lubuntu 17.10   | 1         | 0.12%   |
| Lubuntu 17.04   | 1         | 0.12%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 830       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 37        | 3.91%   |
| 5.4.0-52-generic   | 24        | 2.53%   |
| 5.13.0-28-generic  | 16        | 1.69%   |
| 5.4.0-47-generic   | 15        | 1.58%   |
| 5.13.0-19-generic  | 15        | 1.58%   |
| 5.4.0-48-generic   | 13        | 1.37%   |
| 5.3.0-46-generic   | 13        | 1.37%   |
| 5.11.0-16-generic  | 13        | 1.37%   |
| 5.4.0-26-generic   | 12        | 1.27%   |
| 5.13.0-30-generic  | 12        | 1.27%   |
| 5.8.0-50-generic   | 11        | 1.16%   |
| 5.4.0-40-generic   | 11        | 1.16%   |
| 5.11.0-27-generic  | 11        | 1.16%   |
| 5.4.0-73-generic   | 10        | 1.06%   |
| 5.4.0-54-generic   | 10        | 1.06%   |
| 5.4.0-29-generic   | 10        | 1.06%   |
| 5.3.0-18-generic   | 10        | 1.06%   |
| 5.13.0-35-generic  | 10        | 1.06%   |
| 4.15.0-96-generic  | 10        | 1.06%   |
| 5.4.0-72-generic   | 9         | 0.95%   |
| 5.4.0-33-generic   | 9         | 0.95%   |
| 5.3.0-51-generic   | 9         | 0.95%   |
| 5.3.0-42-generic   | 9         | 0.95%   |
| 5.3.0-40-generic   | 9         | 0.95%   |
| 4.15.0-91-generic  | 9         | 0.95%   |
| 4.15.0-112-generic | 9         | 0.95%   |
| 5.8.0-63-generic   | 8         | 0.84%   |
| 5.4.0-65-generic   | 8         | 0.84%   |
| 5.11.0-38-generic  | 8         | 0.84%   |
| 5.11.0-37-generic  | 8         | 0.84%   |
| 5.11.0-25-generic  | 8         | 0.84%   |
| 4.15.0-106-generic | 8         | 0.84%   |
| 5.8.0-53-generic   | 7         | 0.74%   |
| 5.8.0-49-generic   | 7         | 0.74%   |
| 5.8.0-45-generic   | 7         | 0.74%   |
| 5.8.0-41-generic   | 7         | 0.74%   |
| 5.4.0-58-generic   | 7         | 0.74%   |
| 5.4.0-51-generic   | 7         | 0.74%   |
| 5.4.0-37-generic   | 7         | 0.74%   |
| 5.13.0-22-generic  | 7         | 0.74%   |
| 5.11.0-17-generic  | 7         | 0.74%   |
| 5.0.0-37-generic   | 7         | 0.74%   |
| 4.15.0-136-generic | 7         | 0.74%   |
| 5.8.0-59-generic   | 6         | 0.63%   |
| 5.8.0-48-generic   | 6         | 0.63%   |
| 5.4.0-91-generic   | 6         | 0.63%   |
| 5.4.0-89-generic   | 6         | 0.63%   |
| 5.4.0-67-generic   | 6         | 0.63%   |
| 5.4.0-66-generic   | 6         | 0.63%   |
| 5.4.0-60-generic   | 6         | 0.63%   |
| 5.13.0-27-generic  | 6         | 0.63%   |
| 5.11.0-43-generic  | 6         | 0.63%   |
| 5.11.0-41-generic  | 6         | 0.63%   |
| 5.11.0-40-generic  | 6         | 0.63%   |
| 4.15.0-99-generic  | 6         | 0.63%   |
| 4.15.0-88-generic  | 6         | 0.63%   |
| 5.8.0-55-generic   | 5         | 0.53%   |
| 5.8.0-43-generic   | 5         | 0.53%   |
| 5.4.0-77-generic   | 5         | 0.53%   |
| 5.4.0-70-generic   | 5         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 281       | 32.83%  |
| 4.15.0   | 121       | 14.14%  |
| 5.13.0   | 97        | 11.33%  |
| 5.11.0   | 96        | 11.21%  |
| 5.8.0    | 95        | 11.1%   |
| 5.3.0    | 86        | 10.05%  |
| 5.0.0    | 22        | 2.57%   |
| 4.18.0   | 11        | 1.29%   |
| 5.15.0   | 10        | 1.17%   |
| 4.4.0    | 8         | 0.93%   |
| 5.6.0    | 2         | 0.23%   |
| 4.9.253  | 2         | 0.23%   |
| 4.8.0    | 2         | 0.23%   |
| 4.13.0   | 2         | 0.23%   |
| 4.10.0   | 2         | 0.23%   |
| 5.9.0    | 1         | 0.12%   |
| 5.7.9    | 1         | 0.12%   |
| 5.7.0    | 1         | 0.12%   |
| 5.6.15   | 1         | 0.12%   |
| 5.5.2    | 1         | 0.12%   |
| 5.4.30   | 1         | 0.12%   |
| 5.3.18   | 1         | 0.12%   |
| 5.16.5   | 1         | 0.12%   |
| 5.16.0   | 1         | 0.12%   |
| 5.15.5   | 1         | 0.12%   |
| 5.14.0   | 1         | 0.12%   |
| 5.12.1   | 1         | 0.12%   |
| 5.10.9   | 1         | 0.12%   |
| 5.10.0   | 1         | 0.12%   |
| 4.9.201  | 1         | 0.12%   |
| 4.20.0   | 1         | 0.12%   |
| 4.15.18  | 1         | 0.12%   |
| 4.14.225 | 1         | 0.12%   |
| 4.13.9   | 1         | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 282       | 32.94%  |
| 4.15    | 122       | 14.25%  |
| 5.13    | 97        | 11.33%  |
| 5.11    | 96        | 11.21%  |
| 5.8     | 95        | 11.1%   |
| 5.3     | 87        | 10.16%  |
| 5.0     | 22        | 2.57%   |
| 5.15    | 11        | 1.29%   |
| 4.18    | 11        | 1.29%   |
| 4.4     | 8         | 0.93%   |
| 5.6     | 3         | 0.35%   |
| 4.9     | 3         | 0.35%   |
| 4.13    | 3         | 0.35%   |
| 5.7     | 2         | 0.23%   |
| 5.16    | 2         | 0.23%   |
| 5.10    | 2         | 0.23%   |
| 4.8     | 2         | 0.23%   |
| 4.10    | 2         | 0.23%   |
| 5.9     | 1         | 0.12%   |
| 5.5     | 1         | 0.12%   |
| 5.14    | 1         | 0.12%   |
| 5.12    | 1         | 0.12%   |
| 4.20    | 1         | 0.12%   |
| 4.14    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 716       | 86.27%  |
| i686    | 106       | 12.77%  |
| aarch64 | 6         | 0.72%   |
| ppc64   | 1         | 0.12%   |
| armv7l  | 1         | 0.12%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| LXQt            | 594       | 71.05%  |
| LXDE            | 187       | 22.37%  |
| Unknown         | 21        | 2.51%   |
| GNOME           | 12        | 1.44%   |
| Openbox         | 8         | 0.96%   |
| KDE5            | 3         | 0.36%   |
| GNOME Flashback | 2         | 0.24%   |
| Cinnamon        | 2         | 0.24%   |
| XFCE            | 1         | 0.12%   |
| X-Cinnamon      | 1         | 0.12%   |
| MATE            | 1         | 0.12%   |
| Lubuntu         | 1         | 0.12%   |
| KDE             | 1         | 0.12%   |
| i3              | 1         | 0.12%   |
| Budgie          | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 804       | 96.4%   |
| Tty         | 22        | 2.64%   |
| Wayland     | 5         | 0.6%    |
| Unknown     | 2         | 0.24%   |
| Unspecified | 1         | 0.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 351       | 41.69%  |
| SDDM    | 317       | 37.65%  |
| TDM     | 69        | 8.19%   |
| LightDM | 65        | 7.72%   |
| GDM     | 32        | 3.8%    |
| LXDM    | 3         | 0.36%   |
| GDM3    | 3         | 0.36%   |
| XDM     | 2         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 215       | 25.75%  |
| pt_BR   | 71        | 8.5%    |
| fr_FR   | 64        | 7.66%   |
| it_IT   | 51        | 6.11%   |
| de_DE   | 45        | 5.39%   |
| en_GB   | 42        | 5.03%   |
| C       | 38        | 4.55%   |
| ru_RU   | 35        | 4.19%   |
| Unknown | 30        | 3.59%   |
| pl_PL   | 22        | 2.63%   |
| en_CA   | 21        | 2.51%   |
| es_ES   | 19        | 2.28%   |
| en_AU   | 18        | 2.16%   |
| es_AR   | 11        | 1.32%   |
| cs_CZ   | 10        | 1.2%    |
| tr_TR   | 9         | 1.08%   |
| hu_HU   | 9         | 1.08%   |
| nl_NL   | 8         | 0.96%   |
| en_IN   | 8         | 0.96%   |
| ja_JP   | 7         | 0.84%   |
| es_CR   | 7         | 0.84%   |
| es_MX   | 6         | 0.72%   |
| en_IE   | 6         | 0.72%   |
| fr_BE   | 5         | 0.6%    |
| es_CL   | 5         | 0.6%    |
| es_UY   | 4         | 0.48%   |
| es_PE   | 4         | 0.48%   |
| es_CO   | 4         | 0.48%   |
| en_NZ   | 4         | 0.48%   |
| el_GR   | 4         | 0.48%   |
| nl_BE   | 3         | 0.36%   |
| fr_CA   | 3         | 0.36%   |
| fi_FI   | 3         | 0.36%   |
| en_ZA   | 3         | 0.36%   |
| en_SG   | 3         | 0.36%   |
| de_AT   | 3         | 0.36%   |
| bg_BG   | 3         | 0.36%   |
| zh_TW   | 2         | 0.24%   |
| pt_PT   | 2         | 0.24%   |
| id_ID   | 2         | 0.24%   |
| fr_CH   | 2         | 0.24%   |
| es_VE   | 2         | 0.24%   |
| zh_CN   | 1         | 0.12%   |
| uk_UA   | 1         | 0.12%   |
| sv_SE   | 1         | 0.12%   |
| sr_RS   | 1         | 0.12%   |
| ru_UA   | 1         | 0.12%   |
| ro_RO   | 1         | 0.12%   |
| nb_NO   | 1         | 0.12%   |
| lt_LT   | 1         | 0.12%   |
| ko_KR   | 1         | 0.12%   |
| hr_HR   | 1         | 0.12%   |
| fa_IR   | 1         | 0.12%   |
| es_GT   | 1         | 0.12%   |
| es_EC   | 1         | 0.12%   |
| es_DO   | 1         | 0.12%   |
| en_ZM   | 1         | 0.12%   |
| en_PH   | 1         | 0.12%   |
| en_HK   | 1         | 0.12%   |
| en_DE   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 559       | 66.87%  |
| EFI  | 277       | 33.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 769       | 92.54%  |
| Overlay | 36        | 4.33%   |
| Btrfs   | 10        | 1.2%    |
| Unknown | 5         | 0.6%    |
| Aufs    | 4         | 0.48%   |
| Xfs     | 3         | 0.36%   |
| Ext3    | 2         | 0.24%   |
| F2fs    | 1         | 0.12%   |
| Ext2    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 420       | 50.3%   |
| GPT     | 211       | 25.27%  |
| MBR     | 204       | 24.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 749       | 89.59%  |
| Yes       | 87        | 10.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 607       | 72.78%  |
| Yes       | 227       | 27.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 153       | 18.43%  |
| ASUSTek Computer        | 108       | 13.01%  |
| Dell                    | 88        | 10.6%   |
| Lenovo                  | 73        | 8.8%    |
| Acer                    | 57        | 6.87%   |
| Gigabyte Technology     | 37        | 4.46%   |
| Toshiba                 | 35        | 4.22%   |
| MSI                     | 30        | 3.61%   |
| ASRock                  | 25        | 3.01%   |
| Samsung Electronics     | 24        | 2.89%   |
| Intel                   | 18        | 2.17%   |
| Sony                    | 16        | 1.93%   |
| Apple                   | 15        | 1.81%   |
| Positivo                | 13        | 1.57%   |
| Unknown                 | 13        | 1.57%   |
| Google                  | 10        | 1.2%    |
| Pegatron                | 6         | 0.72%   |
| Fujitsu Siemens         | 6         | 0.72%   |
| Foxconn                 | 6         | 0.72%   |
| Packard Bell            | 5         | 0.6%    |
| Notebook                | 5         | 0.6%    |
| IBM                     | 5         | 0.6%    |
| Biostar                 | 5         | 0.6%    |
| AMI                     | 5         | 0.6%    |
| Raspberry Pi Foundation | 4         | 0.48%   |
| Fujitsu                 | 4         | 0.48%   |
| AAEON                   | 4         | 0.48%   |
| Nvidia                  | 3         | 0.36%   |
| Mediacom                | 3         | 0.36%   |
| Alienware               | 3         | 0.36%   |
| ZOTAC                   | 2         | 0.24%   |
| TrekStor                | 2         | 0.24%   |
| Philco                  | 2         | 0.24%   |
| Panasonic               | 2         | 0.24%   |
| Medion                  | 2         | 0.24%   |
| Itautec                 | 2         | 0.24%   |
| Insyde                  | 2         | 0.24%   |
| Gateway                 | 2         | 0.24%   |
| eMachines               | 2         | 0.24%   |
| Dixonsxp                | 2         | 0.24%   |
| YASHI                   | 1         | 0.12%   |
| VIA Technologies        | 1         | 0.12%   |
| UNOWHY                  | 1         | 0.12%   |
| Timi                    | 1         | 0.12%   |
| Thomson                 | 1         | 0.12%   |
| System76                | 1         | 0.12%   |
| Supermicro              | 1         | 0.12%   |
| Standard                | 1         | 0.12%   |
| Semp Toshiba            | 1         | 0.12%   |
| Qbex                    | 1         | 0.12%   |
| Prestigio               | 1         | 0.12%   |
| Phoenix/SiS             | 1         | 0.12%   |
| PCWare                  | 1         | 0.12%   |
| PCChips                 | 1         | 0.12%   |
| OEM                     | 1         | 0.12%   |
| Noblex                  | 1         | 0.12%   |
| Microsoft               | 1         | 0.12%   |
| LG Electronics          | 1         | 0.12%   |
| LEADER                  | 1         | 0.12%   |
| Lanix                   | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 20        | 2.41%   |
| HP Notebook                        | 6         | 0.72%   |
| Apple MacBookPro8,1                | 5         | 0.6%    |
| HP Pavilion dv6                    | 4         | 0.48%   |
| Dell Latitude D630                 | 4         | 0.48%   |
| AAEON MF-001                       | 4         | 0.48%   |
| Nvidia Tegra                       | 3         | 0.36%   |
| HP ProBook 440 G7                  | 3         | 0.36%   |
| HP Pavilion g6                     | 3         | 0.36%   |
| HP Pavilion 15                     | 3         | 0.36%   |
| Dell OptiPlex 790                  | 3         | 0.36%   |
| ASUS V-P8H67E                      | 3         | 0.36%   |
| ASUS All Series                    | 3         | 0.36%   |
| Acer Aspire 5742G                  | 3         | 0.36%   |
| Toshiba Satellite A205             | 2         | 0.24%   |
| Samsung RV415/RV515                | 2         | 0.24%   |
| Samsung 275E4E/275E5E              | 2         | 0.24%   |
| RPi Raspberry Pi                   | 2         | 0.24%   |
| Positivo Mobile                    | 2         | 0.24%   |
| Positivo H14BT58                   | 2         | 0.24%   |
| MSI MS-7C37                        | 2         | 0.24%   |
| MSI MS-7B89                        | 2         | 0.24%   |
| Mediacom GTZS                      | 2         | 0.24%   |
| Lenovo IdeaPad 330-17AST 81D7      | 2         | 0.24%   |
| Lenovo IdeaPad 320-15AST 80XV      | 2         | 0.24%   |
| Lenovo IdeaPad 100-15IBD 80QQ      | 2         | 0.24%   |
| Itautec Infoway                    | 2         | 0.24%   |
| HP t620 Quad Core TC               | 2         | 0.24%   |
| HP ProBook 450 G2                  | 2         | 0.24%   |
| HP ProBook 440 G8 Notebook PC      | 2         | 0.24%   |
| HP Pavilion x2 Detachable          | 2         | 0.24%   |
| HP Pavilion g7                     | 2         | 0.24%   |
| HP Pavilion g4                     | 2         | 0.24%   |
| HP Laptop 15-bw0xx                 | 2         | 0.24%   |
| HP EliteBook 840 G1                | 2         | 0.24%   |
| HP EliteBook 2560p                 | 2         | 0.24%   |
| HP Compaq Presario CQ50            | 2         | 0.24%   |
| HP Compaq Presario C700            | 2         | 0.24%   |
| HP Compaq dc7800 Small Form Factor | 2         | 0.24%   |
| HP Compaq 6000 Pro SFF PC          | 2         | 0.24%   |
| Gigabyte H81M-DS2                  | 2         | 0.24%   |
| Dell XPS 13 9300                   | 2         | 0.24%   |
| Dell Studio 1555                   | 2         | 0.24%   |
| Dell OptiPlex 7010                 | 2         | 0.24%   |
| Dell Latitude 7480                 | 2         | 0.24%   |
| Dell Inspiron 15-3567              | 2         | 0.24%   |
| Dell DM061                         | 2         | 0.24%   |
| ASUS PRIME H410M-E                 | 2         | 0.24%   |
| ASUS 1215B                         | 2         | 0.24%   |
| ASUS 1015PE                        | 2         | 0.24%   |
| ASUS 1015BX                        | 2         | 0.24%   |
| ASUS 1000H                         | 2         | 0.24%   |
| ASRock N68-VS3 UCC                 | 2         | 0.24%   |
| ASRock FM2A85X Extreme6            | 2         | 0.24%   |
| ASRock 775Dual-VSTA                | 2         | 0.24%   |
| Apple iMac7,1                      | 2         | 0.24%   |
| Acer Aspire 5735                   | 2         | 0.24%   |
| Acer Aspire 5715Z                  | 2         | 0.24%   |
| Acer AOD257                        | 2         | 0.24%   |
| ZOTAC ZBOX-CI323NANO               | 1         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 45        | 5.42%   |
| HP Pavilion           | 33        | 3.98%   |
| Dell Inspiron         | 32        | 3.86%   |
| Toshiba Satellite     | 31        | 3.73%   |
| HP Compaq             | 31        | 3.73%   |
| Lenovo ThinkPad       | 25        | 3.01%   |
| Lenovo IdeaPad        | 23        | 2.77%   |
| HP ProBook            | 22        | 2.65%   |
| Unknown               | 20        | 2.41%   |
| Dell Latitude         | 19        | 2.29%   |
| HP EliteBook          | 14        | 1.69%   |
| Dell OptiPlex         | 13        | 1.57%   |
| HP Laptop             | 9         | 1.08%   |
| Lenovo ThinkCentre    | 8         | 0.96%   |
| HP Notebook           | 6         | 0.72%   |
| Dell XPS              | 6         | 0.72%   |
| Dell Vostro           | 6         | 0.72%   |
| Fujitsu Siemens AMILO | 5         | 0.6%    |
| ASUS VivoBook         | 5         | 0.6%    |
| ASUS PRIME            | 5         | 0.6%    |
| Apple MacBookPro8     | 5         | 0.6%    |
| RPi Raspberry         | 4         | 0.48%   |
| HP Spectre            | 4         | 0.48%   |
| HP Presario           | 4         | 0.48%   |
| AAEON MF-001          | 4         | 0.48%   |
| Packard Bell EasyNote | 3         | 0.36%   |
| Nvidia Tegra          | 3         | 0.36%   |
| HP t620               | 3         | 0.36%   |
| HP Stream             | 3         | 0.36%   |
| Dell Studio           | 3         | 0.36%   |
| Dell PowerEdge        | 3         | 0.36%   |
| ASUS V-P8H67E         | 3         | 0.36%   |
| ASUS All              | 3         | 0.36%   |
| Acer Extensa          | 3         | 0.36%   |
| Toshiba TECRA         | 2         | 0.24%   |
| Samsung RV415         | 2         | 0.24%   |
| Samsung 275E4E        | 2         | 0.24%   |
| Positivo Mobile       | 2         | 0.24%   |
| Positivo H14BT58      | 2         | 0.24%   |
| Notebook W54          | 2         | 0.24%   |
| MSI MS-7C37           | 2         | 0.24%   |
| MSI MS-7B89           | 2         | 0.24%   |
| Mediacom GTZS         | 2         | 0.24%   |
| Itautec Infoway       | 2         | 0.24%   |
| Intel DG31PR          | 2         | 0.24%   |
| HP EliteDesk          | 2         | 0.24%   |
| HP dc5000             | 2         | 0.24%   |
| Gigabyte H81M-DS2     | 2         | 0.24%   |
| Gigabyte B450M        | 2         | 0.24%   |
| Fujitsu LIFEBOOK      | 2         | 0.24%   |
| Dell Precision        | 2         | 0.24%   |
| Dell DM061            | 2         | 0.24%   |
| ASUS 1215B            | 2         | 0.24%   |
| ASUS 1015PE           | 2         | 0.24%   |
| ASUS 1015BX           | 2         | 0.24%   |
| ASUS 1000H            | 2         | 0.24%   |
| ASRock N68-VS3        | 2         | 0.24%   |
| ASRock FM2A85X        | 2         | 0.24%   |
| ASRock B450M          | 2         | 0.24%   |
| ASRock 775Dual-VSTA   | 2         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 82        | 9.88%   |
| 2007    | 74        | 8.92%   |
| 2008    | 67        | 8.07%   |
| 2012    | 65        | 7.83%   |
| 2010    | 62        | 7.47%   |
| 2013    | 58        | 6.99%   |
| 2009    | 54        | 6.51%   |
| 2017    | 46        | 5.54%   |
| 2019    | 43        | 5.18%   |
| 2014    | 42        | 5.06%   |
| 2020    | 37        | 4.46%   |
| 2006    | 37        | 4.46%   |
| 2016    | 36        | 4.34%   |
| 2018    | 33        | 3.98%   |
| 2015    | 32        | 3.86%   |
| 2021    | 23        | 2.77%   |
| 2005    | 18        | 2.17%   |
| Unknown | 10        | 1.2%    |
| 2004    | 4         | 0.48%   |
| 2022    | 2         | 0.24%   |
| 2002    | 2         | 0.24%   |
| 2003    | 1         | 0.12%   |
| 2001    | 1         | 0.12%   |
| 2000    | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 512       | 61.69%  |
| Desktop        | 279       | 33.61%  |
| Convertible    | 11        | 1.33%   |
| System on chip | 7         | 0.84%   |
| Mini pc        | 6         | 0.72%   |
| Server         | 6         | 0.72%   |
| All in one     | 5         | 0.6%    |
| Tablet         | 4         | 0.48%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 793       | 95.43%  |
| Enabled  | 38        | 4.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 819       | 98.67%  |
| Yes  | 11        | 1.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 252       | 29.96%  |
| 4.01-8.0        | 158       | 18.79%  |
| 1.01-2.0        | 157       | 18.67%  |
| 8.01-16.0       | 94        | 11.18%  |
| 16.01-24.0      | 71        | 8.44%   |
| 2.01-3.0        | 42        | 4.99%   |
| 0.51-1.0        | 29        | 3.45%   |
| 32.01-64.0      | 21        | 2.5%    |
| 0.01-0.5        | 7         | 0.83%   |
| 24.01-32.0      | 5         | 0.59%   |
| 64.01-256.0     | 3         | 0.36%   |
| More than 256.0 | 2         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 388       | 43.6%   |
| 0.51-1.0   | 227       | 25.51%  |
| 2.01-3.0   | 116       | 13.03%  |
| 0.01-0.5   | 57        | 6.4%    |
| 4.01-8.0   | 53        | 5.96%   |
| 3.01-4.0   | 39        | 4.38%   |
| 8.01-16.0  | 9         | 1.01%   |
| 16.01-24.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 578       | 68.97%  |
| 2      | 189       | 22.55%  |
| 4      | 20        | 2.39%   |
| 3      | 20        | 2.39%   |
| 0      | 15        | 1.79%   |
| 5      | 10        | 1.19%   |
| 7      | 2         | 0.24%   |
| 6      | 2         | 0.24%   |
| 14     | 1         | 0.12%   |
| 10     | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 433       | 52.04%  |
| No        | 399       | 47.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 743       | 89.41%  |
| No        | 88        | 10.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 617       | 74.07%  |
| No        | 216       | 25.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 472       | 56.19%  |
| Yes       | 368       | 43.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 115       | 13.82%  |
| Brazil                 | 89        | 10.7%   |
| Italy                  | 63        | 7.57%   |
| France                 | 63        | 7.57%   |
| Germany                | 55        | 6.61%   |
| Russia                 | 48        | 5.77%   |
| UK                     | 35        | 4.21%   |
| Canada                 | 31        | 3.73%   |
| Poland                 | 23        | 2.76%   |
| Spain                  | 19        | 2.28%   |
| Netherlands            | 18        | 2.16%   |
| Australia              | 17        | 2.04%   |
| Czechia                | 14        | 1.68%   |
| Belgium                | 14        | 1.68%   |
| Turkey                 | 13        | 1.56%   |
| Hungary                | 12        | 1.44%   |
| Switzerland            | 11        | 1.32%   |
| Argentina              | 11        | 1.32%   |
| Mexico                 | 10        | 1.2%    |
| Finland                | 10        | 1.2%    |
| India                  | 9         | 1.08%   |
| Ukraine                | 7         | 0.84%   |
| Indonesia              | 7         | 0.84%   |
| Costa Rica             | 7         | 0.84%   |
| Malaysia               | 6         | 0.72%   |
| Japan                  | 6         | 0.72%   |
| Colombia               | 6         | 0.72%   |
| Bulgaria               | 6         | 0.72%   |
| New Zealand            | 5         | 0.6%    |
| Ireland                | 5         | 0.6%    |
| Greece                 | 5         | 0.6%    |
| Chile                  | 5         | 0.6%    |
| Austria                | 5         | 0.6%    |
| Uruguay                | 4         | 0.48%   |
| South Africa           | 4         | 0.48%   |
| Romania                | 4         | 0.48%   |
| Peru                   | 4         | 0.48%   |
| Sweden                 | 3         | 0.36%   |
| Slovenia               | 3         | 0.36%   |
| Singapore              | 3         | 0.36%   |
| Serbia                 | 3         | 0.36%   |
| Portugal               | 3         | 0.36%   |
| Lithuania              | 3         | 0.36%   |
| Ecuador                | 3         | 0.36%   |
| Bosnia and Herzegovina | 3         | 0.36%   |
| Tunisia                | 2         | 0.24%   |
| Taiwan                 | 2         | 0.24%   |
| South Korea            | 2         | 0.24%   |
| Slovakia               | 2         | 0.24%   |
| Puerto Rico            | 2         | 0.24%   |
| Norway                 | 2         | 0.24%   |
| Luxembourg             | 2         | 0.24%   |
| Iran                   | 2         | 0.24%   |
| Denmark                | 2         | 0.24%   |
| Belarus                | 2         | 0.24%   |
| Zambia                 | 1         | 0.12%   |
| Vietnam                | 1         | 0.12%   |
| Venezuela              | 1         | 0.12%   |
| Thailand               | 1         | 0.12%   |
| Sri Lanka              | 1         | 0.12%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Rome              | 13        | 1.49%   |
| Milan             | 12        | 1.38%   |
| Paris             | 7         | 0.8%    |
| Moscow            | 7         | 0.8%    |
| Helsinki          | 7         | 0.8%    |
| Oshawa            | 6         | 0.69%   |
| Istanbul          | 6         | 0.69%   |
| Heredia           | 6         | 0.69%   |
| Zurich            | 5         | 0.57%   |
| Warsaw            | 5         | 0.57%   |
| BrasГ­lia       | 5         | 0.57%   |
| Berlin            | 5         | 0.57%   |
| Teresina          | 4         | 0.46%   |
| Sydney            | 4         | 0.46%   |
| Stuttgart         | 4         | 0.46%   |
| St Petersburg     | 4         | 0.46%   |
| Rio de Janeiro    | 4         | 0.46%   |
| Prague            | 4         | 0.46%   |
| Porto Alegre      | 4         | 0.46%   |
| Kuala Lumpur      | 4         | 0.46%   |
| Glasgow           | 4         | 0.46%   |
| Frankfurt am Main | 4         | 0.46%   |
| Budapest          | 4         | 0.46%   |
| Bengaluru         | 4         | 0.46%   |
| Athens            | 4         | 0.46%   |
| Yekaterinburg     | 3         | 0.34%   |
| Winnipeg          | 3         | 0.34%   |
| Windsor           | 3         | 0.34%   |
| Wellington        | 3         | 0.34%   |
| Voronezh          | 3         | 0.34%   |
| Singapore         | 3         | 0.34%   |
| Sao Paulo         | 3         | 0.34%   |
| Salvador          | 3         | 0.34%   |
| Poznan            | 3         | 0.34%   |
| Parkdale          | 3         | 0.34%   |
| Novo Gama         | 3         | 0.34%   |
| New York          | 3         | 0.34%   |
| Naples            | 3         | 0.34%   |
| Munich            | 3         | 0.34%   |
| Montevideo        | 3         | 0.34%   |
| Mexico City       | 3         | 0.34%   |
| Melbourne         | 3         | 0.34%   |
| JoГЈo Pessoa    | 3         | 0.34%   |
| Ghent             | 3         | 0.34%   |
| Eger              | 3         | 0.34%   |
| Curitiba          | 3         | 0.34%   |
| Cape Town         | 3         | 0.34%   |
| Buenos Aires      | 3         | 0.34%   |
| BogotГЎ         | 3         | 0.34%   |
| Birmingham        | 3         | 0.34%   |
| Amsterdam         | 3         | 0.34%   |
| Westwood          | 2         | 0.23%   |
| VitГіria        | 2         | 0.23%   |
| Vienna            | 2         | 0.23%   |
| Vicosa            | 2         | 0.23%   |
| Valinhos          | 2         | 0.23%   |
| Turin             | 2         | 0.23%   |
| Treviso           | 2         | 0.23%   |
| Toronto           | 2         | 0.23%   |
| The Hague         | 2         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 195       | 257    | 19.1%   |
| WDC                 | 180       | 239    | 17.63%  |
| Samsung Electronics | 97        | 147    | 9.5%    |
| Toshiba             | 74        | 82     | 7.25%   |
| Hitachi             | 71        | 91     | 6.95%   |
| Unknown             | 68        | 83     | 6.66%   |
| Kingston            | 50        | 53     | 4.9%    |
| Crucial             | 29        | 32     | 2.84%   |
| SanDisk             | 26        | 31     | 2.55%   |
| Intel               | 22        | 26     | 2.15%   |
| HGST                | 22        | 27     | 2.15%   |
| Fujitsu             | 19        | 20     | 1.86%   |
| MAXTOR              | 14        | 15     | 1.37%   |
| A-DATA Technology   | 11        | 13     | 1.08%   |
| SK Hynix            | 9         | 9      | 0.88%   |
| China               | 9         | 11     | 0.88%   |
| Micron Technology   | 8         | 8      | 0.78%   |
| Apacer              | 7         | 7      | 0.69%   |
| OCZ                 | 6         | 7      | 0.59%   |
| KIOXIA              | 6         | 6      | 0.59%   |
| Transcend           | 4         | 4      | 0.39%   |
| SPCC                | 4         | 7      | 0.39%   |
| PNY                 | 4         | 4      | 0.39%   |
| LITEONIT            | 4         | 4      | 0.39%   |
| LDLC                | 4         | 4      | 0.39%   |
| Patriot             | 3         | 3      | 0.29%   |
| LITEON              | 3         | 4      | 0.29%   |
| JMicron             | 3         | 3      | 0.29%   |
| Intenso             | 3         | 3      | 0.29%   |
| Apple               | 3         | 9      | 0.29%   |
| Unknown             | 3         | 4      | 0.29%   |
| USB                 | 2         | 2      | 0.2%    |
| TO Exter            | 2         | 2      | 0.2%    |
| Team                | 2         | 2      | 0.2%    |
| STEC                | 2         | 3      | 0.2%    |
| Silicon Motion      | 2         | 3      | 0.2%    |
| PLEXTOR             | 2         | 4      | 0.2%    |
| Mushkin             | 2         | 2      | 0.2%    |
| Lexar               | 2         | 2      | 0.2%    |
| KingDian            | 2         | 2      | 0.2%    |
| IBM/Hitachi         | 2         | 3      | 0.2%    |
| Gigabyte Technology | 2         | 2      | 0.2%    |
| Dogfish             | 2         | 2      | 0.2%    |
| Corsair             | 2         | 2      | 0.2%    |
| ASMT                | 2         | 3      | 0.2%    |
| TSA                 | 1         | 1      | 0.1%    |
| TEAM T25            | 1         | 1      | 0.1%    |
| TCSUNBOW            | 1         | 1      | 0.1%    |
| Smartbuy            | 1         | 1      | 0.1%    |
| ShiJi               | 1         | 1      | 0.1%    |
| PNY USB             | 1         | 1      | 0.1%    |
| Phison Electronics  | 1         | 1      | 0.1%    |
| Phison              | 1         | 5      | 0.1%    |
| ORTIAL              | 1         | 1      | 0.1%    |
| NGFF                | 1         | 1      | 0.1%    |
| MyDigitalSSD        | 1         | 1      | 0.1%    |
| MaxDigital          | 1         | 1      | 0.1%    |
| LS                  | 1         | 1      | 0.1%    |
| LONDISK             | 1         | 1      | 0.1%    |
| Leven               | 1         | 2      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 14        | 1.28%   |
| Kingston SA400S37240G 240GB SSD     | 14        | 1.28%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 9         | 0.83%   |
| Unknown MMC Card  64GB              | 8         | 0.73%   |
| Toshiba MQ01ABF050 500GB            | 8         | 0.73%   |
| Toshiba MQ01ABD100 1TB              | 8         | 0.73%   |
| Seagate ST9500325AS 500GB           | 8         | 0.73%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8         | 0.73%   |
| Seagate ST1000LM035-1RK172 1TB      | 7         | 0.64%   |
| Samsung SSD 850 EVO 250GB           | 7         | 0.64%   |
| Kingston SA400S37120G 120GB SSD     | 7         | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 6         | 0.55%   |
| Crucial CT240BX500SSD1 240GB        | 6         | 0.55%   |
| Unknown SD/MMC/MS PRO 16GB          | 5         | 0.46%   |
| Seagate ST9250315AS 250GB           | 5         | 0.46%   |
| Seagate ST3500418AS 500GB           | 5         | 0.46%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.46%   |
| Kingston SA400S37480G 480GB SSD     | 5         | 0.46%   |
| Crucial CT480BX500SSD1 480GB        | 5         | 0.46%   |
| A-DATA SU650 240GB SSD              | 5         | 0.46%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 4         | 0.37%   |
| Unknown MMC Card  16GB              | 4         | 0.37%   |
| Unknown DA4064  64GB                | 4         | 0.37%   |
| Toshiba MQ01ABD050 500GB            | 4         | 0.37%   |
| Seagate ST9320325AS 320GB           | 4         | 0.37%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB      | 4         | 0.37%   |
| Seagate Expansion+ 2TB              | 4         | 0.37%   |
| Samsung HM321HI 320GB               | 4         | 0.37%   |
| Hitachi HTS543216L9SA00 160GB       | 4         | 0.37%   |
| Hitachi HTS542512K9SA00 120GB       | 4         | 0.37%   |
| Hitachi HTS541616J9SA00 160GB       | 4         | 0.37%   |
| HGST HTS545050A7E380 500GB          | 4         | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 3         | 0.28%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.28%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 3         | 0.28%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 3         | 0.28%   |
| WDC WD2500BEVT-80A23T0 250GB        | 3         | 0.28%   |
| WDC WD2500BEVT-22ZCT0 250GB         | 3         | 0.28%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.28%   |
| Unknown MMC Card  128GB             | 3         | 0.28%   |
| Unknown M52516  16GB                | 3         | 0.28%   |
| Toshiba MQ04ABF100 1TB              | 3         | 0.28%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 3         | 0.28%   |
| Seagate ST98823AS 80GB              | 3         | 0.28%   |
| Seagate ST9250410AS 250GB           | 3         | 0.28%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 0.28%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 0.28%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 0.28%   |
| Seagate ST4000DM004-2CV104 4TB      | 3         | 0.28%   |
| Seagate ST3500312CS 500GB           | 3         | 0.28%   |
| Seagate ST3250410AS 250GB           | 3         | 0.28%   |
| Seagate ST3250310AS 250GB           | 3         | 0.28%   |
| Seagate ST3160318AS 160GB           | 3         | 0.28%   |
| Seagate ST31000528AS 1TB            | 3         | 0.28%   |
| Seagate ST2000DM001-1ER164 2TB      | 3         | 0.28%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 0.28%   |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 0.28%   |
| Seagate ST1000DM003-9YN162 1TB      | 3         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 194       | 256    | 32.61%  |
| WDC                 | 163       | 216    | 27.39%  |
| Hitachi             | 71        | 91     | 11.93%  |
| Toshiba             | 60        | 66     | 10.08%  |
| Samsung Electronics | 41        | 59     | 6.89%   |
| HGST                | 22        | 27     | 3.7%    |
| Fujitsu             | 19        | 20     | 3.19%   |
| MAXTOR              | 13        | 14     | 2.18%   |
| Unknown             | 5         | 5      | 0.84%   |
| USB                 | 2         | 2      | 0.34%   |
| IBM/Hitachi         | 2         | 3      | 0.34%   |
| LaCie               | 1         | 1      | 0.17%   |
| ASMT                | 1         | 2      | 0.17%   |
| Apple               | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 46        | 48     | 15.86%  |
| Samsung Electronics | 43        | 61     | 14.83%  |
| Crucial             | 28        | 31     | 9.66%   |
| SanDisk             | 18        | 23     | 6.21%   |
| Intel               | 18        | 22     | 6.21%   |
| WDC                 | 16        | 19     | 5.52%   |
| China               | 9         | 11     | 3.1%    |
| A-DATA Technology   | 9         | 11     | 3.1%    |
| Toshiba             | 8         | 9      | 2.76%   |
| Apacer              | 7         | 7      | 2.41%   |
| OCZ                 | 6         | 7      | 2.07%   |
| Micron Technology   | 6         | 6      | 2.07%   |
| Transcend           | 4         | 4      | 1.38%   |
| PNY                 | 4         | 4      | 1.38%   |
| LITEONIT            | 4         | 4      | 1.38%   |
| Patriot             | 3         | 3      | 1.03%   |
| LITEON              | 3         | 4      | 1.03%   |
| LDLC                | 3         | 3      | 1.03%   |
| Intenso             | 3         | 3      | 1.03%   |
| Unknown             | 2         | 2      | 0.69%   |
| TO Exter            | 2         | 2      | 0.69%   |
| Team                | 2         | 2      | 0.69%   |
| SPCC                | 2         | 2      | 0.69%   |
| PLEXTOR             | 2         | 4      | 0.69%   |
| Mushkin             | 2         | 2      | 0.69%   |
| Lexar               | 2         | 2      | 0.69%   |
| KingDian            | 2         | 2      | 0.69%   |
| Dogfish             | 2         | 2      | 0.69%   |
| Corsair             | 2         | 2      | 0.69%   |
| Apple               | 2         | 8      | 0.69%   |
| TSA                 | 1         | 1      | 0.34%   |
| TEAM T25            | 1         | 1      | 0.34%   |
| TCSUNBOW            | 1         | 1      | 0.34%   |
| Smartbuy            | 1         | 1      | 0.34%   |
| SK Hynix            | 1         | 1      | 0.34%   |
| Seagate             | 1         | 1      | 0.34%   |
| PNY USB             | 1         | 1      | 0.34%   |
| ORTIAL              | 1         | 1      | 0.34%   |
| NGFF                | 1         | 1      | 0.34%   |
| MyDigitalSSD        | 1         | 1      | 0.34%   |
| MAXTOR              | 1         | 1      | 0.34%   |
| LS                  | 1         | 1      | 0.34%   |
| LONDISK             | 1         | 1      | 0.34%   |
| Leven               | 1         | 2      | 0.34%   |
| Lenovo              | 1         | 1      | 0.34%   |
| Kston               | 1         | 2      | 0.34%   |
| KLEVV               | 1         | 1      | 0.34%   |
| KingSpec            | 1         | 11     | 0.34%   |
| JMicron             | 1         | 1      | 0.34%   |
| Integral            | 1         | 1      | 0.34%   |
| HS-SSD-E100         | 1         | 1      | 0.34%   |
| Hikvision           | 1         | 1      | 0.34%   |
| Hewlett-Packard     | 1         | 6      | 0.34%   |
| GOODRAM             | 1         | 1      | 0.34%   |
| Gigabyte Technology | 1         | 1      | 0.34%   |
| FORESEE             | 1         | 1      | 0.34%   |
| External            | 1         | 1      | 0.34%   |
| Dell                | 1         | 1      | 0.34%   |
| ASMT                | 1         | 1      | 0.34%   |
| Argon               | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 529       | 763    | 55.98%  |
| SSD     | 276       | 357    | 29.21%  |
| MMC     | 68        | 83     | 7.2%    |
| NVMe    | 61        | 84     | 6.46%   |
| Unknown | 11        | 14     | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 715       | 1086   | 81.34%  |
| MMC  | 68        | 83     | 7.74%   |
| NVMe | 61        | 84     | 6.94%   |
| SAS  | 35        | 48     | 3.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 596       | 819    | 73.49%  |
| 0.51-1.0   | 155       | 213    | 19.11%  |
| 1.01-2.0   | 35        | 47     | 4.32%   |
| 3.01-4.0   | 16        | 30     | 1.97%   |
| 2.01-3.0   | 6         | 7      | 0.74%   |
| 4.01-10.0  | 3         | 4      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 251       | 29.85%  |
| 251-500        | 196       | 23.31%  |
| 51-100         | 91        | 10.82%  |
| 501-1000       | 84        | 9.99%   |
| 1-20           | 66        | 7.85%   |
| 21-50          | 64        | 7.61%   |
| 1001-2000      | 42        | 4.99%   |
| More than 3000 | 27        | 3.21%   |
| 2001-3000      | 18        | 2.14%   |
| Unknown        | 2         | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 446       | 51.32%  |
| 21-50          | 154       | 17.72%  |
| 101-250        | 92        | 10.59%  |
| 51-100         | 65        | 7.48%   |
| 251-500        | 38        | 4.37%   |
| 501-1000       | 34        | 3.91%   |
| 1001-2000      | 20        | 2.3%    |
| More than 3000 | 11        | 1.27%   |
| 2001-3000      | 7         | 0.81%   |
| Unknown        | 2         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 3         | 3      | 3.03%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 3      | 3.03%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 2.02%   |
| Seagate ST9250315AS 250GB             | 2         | 2      | 2.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 2.02%   |
| Hitachi HTS542512K9SA00 120GB         | 2         | 2      | 2.02%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 1.01%   |
| WDC WD800BEVS-60RST0 80GB             | 1         | 1      | 1.01%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 1      | 1.01%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 1      | 1.01%   |
| WDC WD400EB-00CPF0 40GB               | 1         | 1      | 1.01%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 1.01%   |
| WDC WD3200BEKT-60PVMT0 320GB          | 1         | 1      | 1.01%   |
| WDC WD2500HHTZ-04N21V0 250GB          | 1         | 1      | 1.01%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 2      | 1.01%   |
| WDC WD2500AAJS-75M0A0 250GB           | 1         | 1      | 1.01%   |
| WDC WD1600AAJS-60B4A0 160GB           | 1         | 2      | 1.01%   |
| WDC WD1200BEVS-60UST0 120GB           | 1         | 1      | 1.01%   |
| WDC WD1200BEVS-07LAT0 120GB           | 1         | 1      | 1.01%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 1      | 1.01%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 1.01%   |
| WDC WD10EADS-65M2B0 1TB               | 1         | 1      | 1.01%   |
| Toshiba MK3276GSX 320GB               | 1         | 1      | 1.01%   |
| Toshiba MK2046GSX 200GB               | 1         | 1      | 1.01%   |
| TCSUNBOW X1 32GB SSD                  | 1         | 1      | 1.01%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 1.01%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.01%   |
| Seagate ST9250410AS 250GB             | 1         | 1      | 1.01%   |
| Seagate ST9160821AS 160GB             | 1         | 1      | 1.01%   |
| Seagate ST9160310AS 160GB             | 1         | 1      | 1.01%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 1.01%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.01%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.01%   |
| Seagate ST4000DM004-2CV104 4TB        | 1         | 1      | 1.01%   |
| Seagate ST380815AS 80GB               | 1         | 1      | 1.01%   |
| Seagate ST380011A 80GB                | 1         | 1      | 1.01%   |
| Seagate ST3360320AS 360GB             | 1         | 1      | 1.01%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.01%   |
| Seagate ST3200822AS 200GB             | 1         | 1      | 1.01%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 1.01%   |
| Seagate ST2000DX002-2DV164 2TB        | 1         | 1      | 1.01%   |
| Seagate ST1000NM0095-2DC10C 1TB       | 1         | 6      | 1.01%   |
| Seagate ST1000DX001-1CM162 1TB        | 1         | 1      | 1.01%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 1      | 1.01%   |
| Samsung Electronics HM160JI 160GB     | 1         | 1      | 1.01%   |
| Samsung Electronics HM121HI 120GB     | 1         | 3      | 1.01%   |
| Samsung Electronics HD253GJ 250GB     | 1         | 1      | 1.01%   |
| OCZ VERTEX3 120GB SSD                 | 1         | 1      | 1.01%   |
| OCZ REVODRIVE 26GB SSD                | 1         | 2      | 1.01%   |
| Mushkin MKNSSDCR60GB-7 64GB           | 1         | 1      | 1.01%   |
| MAXTOR STM3300622A 304GB              | 1         | 1      | 1.01%   |
| MAXTOR 6Y080L0 82GB                   | 1         | 1      | 1.01%   |
| MAXTOR 6B200M0 208GB                  | 1         | 1      | 1.01%   |
| LITEON IT LST-16S9G-HP 16GB SSD       | 1         | 1      | 1.01%   |
| LITEON CV8-8E128-HP 128GB SSD         | 1         | 1      | 1.01%   |
| LDLC SSD 120GB                        | 1         | 1      | 1.01%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 1.01%   |
| Kingston SHFS37A120G 120GB SSD        | 1         | 1      | 1.01%   |
| Kingston SA400S37240G 240GB SSD       | 1         | 1      | 1.01%   |
| Kingston SA400S37120G 120GB SSD       | 1         | 1      | 1.01%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 35     | 29.9%   |
| WDC                 | 16        | 18     | 16.49%  |
| Hitachi             | 12        | 13     | 12.37%  |
| Kingston            | 5         | 5      | 5.15%   |
| HGST                | 5         | 5      | 5.15%   |
| Crucial             | 5         | 5      | 5.15%   |
| Samsung Electronics | 3         | 5      | 3.09%   |
| MAXTOR              | 3         | 3      | 3.09%   |
| Intel               | 3         | 3      | 3.09%   |
| Fujitsu             | 3         | 3      | 3.09%   |
| Toshiba             | 2         | 2      | 2.06%   |
| OCZ                 | 2         | 3      | 2.06%   |
| LITEON              | 2         | 2      | 2.06%   |
| TCSUNBOW            | 1         | 1      | 1.03%   |
| SK Hynix            | 1         | 1      | 1.03%   |
| Mushkin             | 1         | 1      | 1.03%   |
| LDLC                | 1         | 1      | 1.03%   |
| KingSpec            | 1         | 11     | 1.03%   |
| Apacer              | 1         | 1      | 1.03%   |
| A-DATA Technology   | 1         | 1      | 1.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 35     | 40.28%  |
| WDC                 | 15        | 17     | 20.83%  |
| Hitachi             | 12        | 13     | 16.67%  |
| HGST                | 5         | 5      | 6.94%   |
| Samsung Electronics | 3         | 5      | 4.17%   |
| MAXTOR              | 3         | 3      | 4.17%   |
| Fujitsu             | 3         | 3      | 4.17%   |
| Toshiba             | 2         | 2      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 70        | 83     | 73.68%  |
| SSD  | 24        | 35     | 25.26%  |
| NVMe | 1         | 1      | 1.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB       | 1         | 1      | 16.67%  |
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 16.67%  |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 16.67%  |
| Samsung Electronics HM320JI 320GB | 1         | 1      | 16.67%  |
| Samsung Electronics HD080HJ 80GB  | 1         | 1      | 16.67%  |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 4      | 50%     |
| Samsung Electronics | 2         | 2      | 33.33%  |
| Intel               | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 469       | 713    | 53.54%  |
| Works    | 308       | 462    | 35.16%  |
| Malfunc  | 93        | 119    | 10.62%  |
| Failed   | 6         | 7      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 549       | 64.36%  |
| AMD                              | 142       | 16.65%  |
| Nvidia                           | 44        | 5.16%   |
| Samsung Electronics              | 16        | 1.88%   |
| JMicron Technology               | 14        | 1.64%   |
| VIA Technologies                 | 11        | 1.29%   |
| Marvell Technology Group         | 9         | 1.06%   |
| Silicon Integrated Systems [SiS] | 7         | 0.82%   |
| Sandisk                          | 7         | 0.82%   |
| Toshiba America Info Systems     | 6         | 0.7%    |
| KIOXIA                           | 6         | 0.7%    |
| ASMedia Technology               | 6         | 0.7%    |
| SK Hynix                         | 5         | 0.59%   |
| Silicon Motion                   | 5         | 0.59%   |
| LSI Logic / Symbios Logic        | 4         | 0.47%   |
| Kingston Technology Company      | 4         | 0.47%   |
| Silicon Image                    | 3         | 0.35%   |
| Phison Electronics               | 3         | 0.35%   |
| ULi Electronics                  | 2         | 0.23%   |
| Micron Technology                | 2         | 0.23%   |
| ADATA Technology                 | 2         | 0.23%   |
| Solid State Storage Technology   | 1         | 0.12%   |
| Micron/Crucial Technology        | 1         | 0.12%   |
| Hewlett-Packard                  | 1         | 0.12%   |
| Broadcom / LSI                   | 1         | 0.12%   |
| Broadcom                         | 1         | 0.12%   |
| Adaptec                          | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 79        | 7.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 43        | 3.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 37        | 3.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 34        | 3.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 30        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 30        | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 30        | 2.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 28        | 2.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 26        | 2.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 26        | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 24        | 2.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 24        | 2.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 22        | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 18        | 1.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 17        | 1.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 17        | 1.58%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 16        | 1.48%   |
| Nvidia MCP61 SATA Controller                                                            | 15        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 13        | 1.2%    |
| Nvidia MCP61 IDE                                                                        | 12        | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12        | 1.11%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 11        | 1.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11        | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 11        | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 0.93%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 10        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 0.93%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 9         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9         | 0.83%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 9         | 0.83%   |
| AMD SB600 IDE                                                                           | 9         | 0.83%   |
| AMD IXP SB4x0 IDE Controller                                                            | 9         | 0.83%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 7         | 0.65%   |
| Nvidia CK804 Serial ATA Controller                                                      | 7         | 0.65%   |
| Nvidia CK804 IDE                                                                        | 7         | 0.65%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 0.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 7         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 7         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 7         | 0.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7         | 0.65%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 7         | 0.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 7         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 0.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 0.65%   |
| KIOXIA Non-Volatile memory controller                                                   | 6         | 0.56%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6         | 0.56%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 6         | 0.56%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 0.56%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 5         | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5         | 0.46%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 5         | 0.46%   |
| Nvidia MCP67 AHCI Controller                                                            | 5         | 0.46%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 5         | 0.46%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 5         | 0.46%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 5         | 0.46%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 5         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 533       | 58.19%  |
| IDE  | 275       | 30.02%  |
| NVMe | 60        | 6.55%   |
| RAID | 44        | 4.8%    |
| SCSI | 3         | 0.33%   |
| SAS  | 1         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Intel       | 637       | 76.75%  |
| AMD         | 185       | 22.29%  |
| ARM         | 7         | 0.84%   |
| PowerMac7,2 | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 16        | 1.93%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 10        | 1.2%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.84%   |
| AMD E-450 APU with Radeon HD Graphics         | 7         | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 0.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 0.72%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 6         | 0.72%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 6         | 0.72%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 0.72%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 6         | 0.72%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 6         | 0.72%   |
| ARM Processor                                 | 6         | 0.72%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 5         | 0.6%    |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 5         | 0.6%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 5         | 0.6%    |
| Intel Pentium 4 CPU 3.00GHz                   | 5         | 0.6%    |
| Intel Pentium 4 CPU 2.80GHz                   | 5         | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.6%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 5         | 0.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 0.6%    |
| Intel Atom CPU Z3735F @ 1.33GHz               | 5         | 0.6%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 5         | 0.6%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 0.6%    |
| AMD E-350 Processor                           | 5         | 0.6%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 4         | 0.48%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 4         | 0.48%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 4         | 0.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 0.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 0.48%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.48%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 4         | 0.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.48%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.48%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.48%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.48%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.48%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 4         | 0.48%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 4         | 0.48%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 4         | 0.48%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 4         | 0.48%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 4         | 0.48%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 0.48%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 0.48%   |
| AMD E-300 APU with Radeon HD Graphics         | 4         | 0.48%   |
| AMD Athlon II X2 250 Processor                | 4         | 0.48%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+    | 4         | 0.48%   |
| AMD Athlon 64 Processor 3000+                 | 4         | 0.48%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.36%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 3         | 0.36%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 3         | 0.36%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 3         | 0.36%   |
| Intel Pentium Dual CPU T2310 @ 1.46GHz        | 3         | 0.36%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 3         | 0.36%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.36%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 3         | 0.36%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 3         | 0.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.36%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 123       | 14.82%  |
| Intel Core i7                  | 78        | 9.4%    |
| Intel Atom                     | 71        | 8.55%   |
| Intel Core 2 Duo               | 66        | 7.95%   |
| Intel Celeron                  | 65        | 7.83%   |
| Intel Core i3                  | 61        | 7.35%   |
| Intel Pentium Dual             | 25        | 3.01%   |
| Intel Pentium                  | 25        | 3.01%   |
| Intel Pentium Dual-Core        | 23        | 2.77%   |
| AMD Athlon 64 X2               | 19        | 2.29%   |
| Intel Core 2                   | 18        | 2.17%   |
| Other                          | 17        | 2.05%   |
| AMD E                          | 16        | 1.93%   |
| Intel Pentium 4                | 15        | 1.81%   |
| AMD Ryzen 5                    | 15        | 1.81%   |
| Intel Xeon                     | 14        | 1.69%   |
| AMD Ryzen 7                    | 13        | 1.57%   |
| Intel Genuine                  | 11        | 1.33%   |
| AMD E1                         | 10        | 1.2%    |
| AMD Athlon II X2               | 10        | 1.2%    |
| AMD A4                         | 10        | 1.2%    |
| Intel Core 2 Quad              | 9         | 1.08%   |
| AMD Athlon 64                  | 8         | 0.96%   |
| AMD A6                         | 8         | 0.96%   |
| AMD Ryzen 3                    | 6         | 0.72%   |
| AMD A10                        | 6         | 0.72%   |
| Intel Pentium M                | 5         | 0.6%    |
| Intel Celeron M                | 5         | 0.6%    |
| AMD E2                         | 5         | 0.6%    |
| AMD Mobile Sempron             | 4         | 0.48%   |
| AMD FX                         | 4         | 0.48%   |
| AMD Athlon                     | 4         | 0.48%   |
| Intel Pentium Silver           | 3         | 0.36%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.36%   |
| AMD GX                         | 3         | 0.36%   |
| AMD C-50                       | 3         | 0.36%   |
| AMD Athlon X2                  | 3         | 0.36%   |
| AMD A8                         | 3         | 0.36%   |
| Intel Pentium D                | 2         | 0.24%   |
| Intel Core Duo                 | 2         | 0.24%   |
| Intel Celeron Dual-Core        | 2         | 0.24%   |
| AMD Sempron                    | 2         | 0.24%   |
| AMD Ryzen 7 PRO                | 2         | 0.24%   |
| AMD Phenom II X4               | 2         | 0.24%   |
| AMD C-70                       | 2         | 0.24%   |
| AMD C-60                       | 2         | 0.24%   |
| AMD Athlon X4                  | 2         | 0.24%   |
| Intel Pentium III              | 1         | 0.12%   |
| Intel Pentium Gold             | 1         | 0.12%   |
| Intel Mobile Pentium 4         | 1         | 0.12%   |
| Intel Core m3                  | 1         | 0.12%   |
| Intel Core i9                  | 1         | 0.12%   |
| Intel Core 2 Solo              | 1         | 0.12%   |
| Intel Core 2 Extreme           | 1         | 0.12%   |
| ARM BCM                        | 1         | 0.12%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.12%   |
| AMD Turion 64 X2               | 1         | 0.12%   |
| AMD Turion 64 Mobile           | 1         | 0.12%   |
| AMD Ryzen Threadripper         | 1         | 0.12%   |
| AMD Ryzen 5 PRO                | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 494       | 59.52%  |
| 4      | 205       | 24.7%   |
| 1      | 87        | 10.48%  |
| 8      | 18        | 2.17%   |
| 6      | 16        | 1.93%   |
| 12     | 3         | 0.36%   |
| 3      | 3         | 0.36%   |
| 64     | 1         | 0.12%   |
| 40     | 1         | 0.12%   |
| 20     | 1         | 0.12%   |
| 10     | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 823       | 99.16%  |
| 2      | 6         | 0.72%   |
| 4      | 1         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 487       | 58.67%  |
| 2      | 342       | 41.2%   |
| 8      | 1         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 775       | 93.37%  |
| 32-bit         | 47        | 5.66%   |
| Unknown        | 8         | 0.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 153       | 18.11%  |
| 0x206a7    | 60        | 7.1%    |
| 0x1067a    | 43        | 5.09%   |
| 0x6fd      | 40        | 4.73%   |
| 0x306a9    | 32        | 3.79%   |
| 0x40651    | 23        | 2.72%   |
| 0x306c3    | 22        | 2.6%    |
| 0x20655    | 22        | 2.6%    |
| 0x05000119 | 21        | 2.49%   |
| 0x406c4    | 20        | 2.37%   |
| 0x30678    | 20        | 2.37%   |
| 0x106ca    | 20        | 2.37%   |
| 0x406e3    | 16        | 1.89%   |
| 0x6fb      | 15        | 1.78%   |
| 0x806ec    | 14        | 1.66%   |
| 0x106c2    | 13        | 1.54%   |
| 0x10676    | 13        | 1.54%   |
| 0x6f6      | 12        | 1.42%   |
| 0x406c3    | 12        | 1.42%   |
| 0x20652    | 10        | 1.18%   |
| 0x6e8      | 9         | 1.07%   |
| 0x306d4    | 9         | 1.07%   |
| 0x05000029 | 9         | 1.07%   |
| 0x706a1    | 8         | 0.95%   |
| 0x6d8      | 8         | 0.95%   |
| 0x0700010f | 8         | 0.95%   |
| 0x06006705 | 8         | 0.95%   |
| 0x806e9    | 7         | 0.83%   |
| 0x806ea    | 6         | 0.71%   |
| 0x706a8    | 6         | 0.71%   |
| 0x30661    | 6         | 0.71%   |
| 0x06001119 | 6         | 0.71%   |
| 0x010000c8 | 6         | 0.71%   |
| 0x906ea    | 5         | 0.59%   |
| 0x906e9    | 5         | 0.59%   |
| 0x6f2      | 5         | 0.59%   |
| 0x506c9    | 5         | 0.59%   |
| 0x10661    | 5         | 0.59%   |
| 0x08701021 | 5         | 0.59%   |
| 0x08600106 | 5         | 0.59%   |
| 0xf41      | 4         | 0.47%   |
| 0x806eb    | 4         | 0.47%   |
| 0x806c1    | 4         | 0.47%   |
| 0x706e5    | 4         | 0.47%   |
| 0x6ec      | 4         | 0.47%   |
| 0x08600103 | 4         | 0.47%   |
| 0x06006704 | 4         | 0.47%   |
| 0x06000852 | 4         | 0.47%   |
| 0xf65      | 3         | 0.36%   |
| 0xf49      | 3         | 0.36%   |
| 0xf43      | 3         | 0.36%   |
| 0xf29      | 3         | 0.36%   |
| 0x6fa      | 3         | 0.36%   |
| 0x506e3    | 3         | 0.36%   |
| 0x30673    | 3         | 0.36%   |
| 0x08108102 | 3         | 0.36%   |
| 0x0810100b | 3         | 0.36%   |
| 0x07030105 | 3         | 0.36%   |
| 0x010000db | 3         | 0.36%   |
| 0x010000c7 | 3         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Core            | 89        | 10.72%  |
| SandyBridge     | 71        | 8.55%   |
| Penryn          | 63        | 7.59%   |
| Silvermont      | 60        | 7.23%   |
| Haswell         | 57        | 6.87%   |
| KabyLake        | 48        | 5.78%   |
| IvyBridge       | 45        | 5.42%   |
| Bonnell         | 40        | 4.82%   |
| K8 Hammer       | 39        | 4.7%    |
| Westmere        | 38        | 4.58%   |
| Bobcat          | 31        | 3.73%   |
| Skylake         | 26        | 3.13%   |
| P6              | 23        | 2.77%   |
| NetBurst        | 22        | 2.65%   |
| K10             | 21        | 2.53%   |
| Zen 2           | 19        | 2.29%   |
| Excavator       | 17        | 2.05%   |
| Goldmont plus   | 15        | 1.81%   |
| Zen+            | 11        | 1.33%   |
| Piledriver      | 11        | 1.33%   |
| Broadwell       | 11        | 1.33%   |
| Jaguar          | 10        | 1.2%    |
| Puma            | 8         | 0.96%   |
| Unknown         | 8         | 0.96%   |
| Zen             | 7         | 0.84%   |
| Goldmont        | 7         | 0.84%   |
| IceLake         | 6         | 0.72%   |
| CometLake       | 6         | 0.72%   |
| TigerLake       | 5         | 0.6%    |
| Nehalem         | 5         | 0.6%    |
| K8 & K10 hybrid | 5         | 0.6%    |
| Zen 3           | 2         | 0.24%   |
| Steamroller     | 2         | 0.24%   |
| K10 Llano       | 2         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 480       | 53.1%   |
| AMD                              | 225       | 24.89%  |
| Nvidia                           | 180       | 19.91%  |
| VIA Technologies                 | 6         | 0.66%   |
| Silicon Integrated Systems [SiS] | 6         | 0.66%   |
| Matrox Electronics Systems       | 6         | 0.66%   |
| S3 Graphics                      | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 55        | 5.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 36        | 3.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 36        | 3.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 2.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 2.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25        | 2.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 2.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 23        | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 2.34%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 18        | 1.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 1.53%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 14        | 1.43%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 13        | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.02%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 10        | 1.02%   |
| AMD Renoir                                                                               | 10        | 1.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 0.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 0.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9         | 0.92%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 9         | 0.92%   |
| Nvidia GT218 [GeForce 210]                                                               | 8         | 0.82%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 8         | 0.82%   |
| Intel HD Graphics 620                                                                    | 8         | 0.82%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 8         | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 0.71%   |
| Intel HD Graphics 5500                                                                   | 7         | 0.71%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 7         | 0.71%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 0.71%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                                 | 7         | 0.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 0.71%   |
| Intel UHD Graphics 620                                                                   | 6         | 0.61%   |
| Intel HD Graphics 530                                                                    | 6         | 0.61%   |
| Intel HD Graphics 500                                                                    | 6         | 0.61%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 6         | 0.61%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.61%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 6         | 0.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6         | 0.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.51%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 0.51%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 0.51%   |
| Intel 82865G Integrated Graphics Controller                                              | 5         | 0.51%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 0.51%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.51%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5         | 0.51%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 4         | 0.41%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 0.41%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 4         | 0.41%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 4         | 0.41%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 4         | 0.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.41%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.41%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4         | 0.41%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 4         | 0.41%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 4         | 0.41%   |
| AMD RS780L [Radeon 3000]                                                                 | 4         | 0.41%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.41%   |
| AMD Kabini [Radeon HD 8210]                                                              | 4         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 406       | 48.8%   |
| 1 x AMD         | 184       | 22.12%  |
| 1 x Nvidia      | 126       | 15.14%  |
| Intel + Nvidia  | 45        | 5.41%   |
| Intel + AMD     | 23        | 2.76%   |
| 2 x AMD         | 15        | 1.8%    |
| Other           | 9         | 1.08%   |
| 1 x VIA         | 6         | 0.72%   |
| 1 x SiS         | 6         | 0.72%   |
| 1 x Matrox      | 5         | 0.6%    |
| AMD + Nvidia    | 3         | 0.36%   |
| 2 x Nvidia      | 2         | 0.24%   |
| 1 x S3 Graphics | 1         | 0.12%   |
| Nvidia + Matrox | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 723       | 86.69%  |
| Proprietary | 75        | 8.99%   |
| Unknown     | 36        | 4.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 436       | 52.03%  |
| 0.01-0.5   | 223       | 26.61%  |
| 1.01-2.0   | 76        | 9.07%   |
| 0.51-1.0   | 64        | 7.64%   |
| 3.01-4.0   | 23        | 2.74%   |
| 7.01-8.0   | 5         | 0.6%    |
| 2.01-3.0   | 5         | 0.6%    |
| 5.01-6.0   | 3         | 0.36%   |
| 8.01-16.0  | 3         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 130       | 15.99%  |
| AU Optronics            | 98        | 12.05%  |
| LG Display              | 70        | 8.61%   |
| Chimei Innolux          | 58        | 7.13%   |
| BOE                     | 54        | 6.64%   |
| Dell                    | 41        | 5.04%   |
| Goldstar                | 31        | 3.81%   |
| Chi Mei Optoelectronics | 28        | 3.44%   |
| Acer                    | 28        | 3.44%   |
| Hewlett-Packard         | 24        | 2.95%   |
| LG Philips              | 22        | 2.71%   |
| HannStar                | 17        | 2.09%   |
| AOC                     | 17        | 2.09%   |
| Philips                 | 16        | 1.97%   |
| Apple                   | 16        | 1.97%   |
| Lenovo                  | 15        | 1.85%   |
| BenQ                    | 12        | 1.48%   |
| InfoVision              | 10        | 1.23%   |
| CPT                     | 9         | 1.11%   |
| Ancor Communications    | 9         | 1.11%   |
| Vizio                   | 7         | 0.86%   |
| NEC Computers           | 7         | 0.86%   |
| Unknown                 | 6         | 0.74%   |
| Sharp                   | 6         | 0.74%   |
| Iiyama                  | 6         | 0.74%   |
| Sony                    | 5         | 0.62%   |
| Sceptre Tech            | 4         | 0.49%   |
| PANDA                   | 3         | 0.37%   |
| LG Electronics          | 3         | 0.37%   |
| Eizo                    | 3         | 0.37%   |
| ___                     | 2         | 0.25%   |
| ViewSonic               | 2         | 0.25%   |
| Positivo                | 2         | 0.25%   |
| Plain Tree Systems      | 2         | 0.25%   |
| Panasonic               | 2         | 0.25%   |
| Lenovo Group Limited    | 2         | 0.25%   |
| IOD                     | 2         | 0.25%   |
| InnoLux Display         | 2         | 0.25%   |
| IBM                     | 2         | 0.25%   |
| Fujitsu Siemens         | 2         | 0.25%   |
| FL_                     | 2         | 0.25%   |
| Elo Touch               | 2         | 0.25%   |
| CVT                     | 2         | 0.25%   |
| ASUSTek Computer        | 2         | 0.25%   |
| Videoseven              | 1         | 0.12%   |
| Vestel                  | 1         | 0.12%   |
| Unknown (ADA)           | 1         | 0.12%   |
| Toshiba                 | 1         | 0.12%   |
| STD                     | 1         | 0.12%   |
| Proview                 | 1         | 0.12%   |
| Pioneer                 | 1         | 0.12%   |
| PAR                     | 1         | 0.12%   |
| Nvidia                  | 1         | 0.12%   |
| NCS                     | 1         | 0.12%   |
| MSI                     | 1         | 0.12%   |
| MOT                     | 1         | 0.12%   |
| Lite-On                 | 1         | 0.12%   |
| KDC                     | 1         | 0.12%   |
| IPS                     | 1         | 0.12%   |
| Idek Iiyama             | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 8         | 0.97%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 8         | 0.97%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 6         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.73%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.49%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 4         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.37%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch            | 3         | 0.37%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch              | 3         | 0.37%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 3         | 0.37%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 3         | 0.37%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch                | 3         | 0.37%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 3         | 0.37%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 3         | 0.37%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                        | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 3         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 3         | 0.37%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.37%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 0.37%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                     | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.37%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 3         | 0.37%   |
| ___ LCDTV16 ___0101 1360x768                                             | 2         | 0.24%   |
| Vizio D39h-D0 VIZ1002 1366x768 853x479mm 38.5-inch                       | 2         | 0.24%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                  | 2         | 0.24%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch     | 2         | 0.24%   |
| Samsung Electronics SyncMaster SAM0119 1280x1024 352x264mm 17.3-inch     | 2         | 0.24%   |
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch        | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 2         | 0.24%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 2         | 0.24%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.24%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch              | 2         | 0.24%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.24%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 2         | 0.24%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                 | 2         | 0.24%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.24%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch              | 2         | 0.24%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch               | 2         | 0.24%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch             | 2         | 0.24%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch              | 2         | 0.24%   |
| Goldstar W1642C GSM3E89 1366x768 344x194mm 15.5-inch                     | 2         | 0.24%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                         | 2         | 0.24%   |
| Elo Touch elotouch.com ELO1925 1280x1024 376x301mm 19.0-inch             | 2         | 0.24%   |
| Dell U2711 DELA057 2560x1440 600x340mm 27.2-inch                         | 2         | 0.24%   |
| Dell ST2410 DELA05D 1920x1080 531x299mm 24.0-inch                        | 2         | 0.24%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                        | 2         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 250       | 31.17%  |
| 1920x1080 (FHD)    | 196       | 24.44%  |
| 1280x800 (WXGA)    | 77        | 9.6%    |
| 1280x1024 (SXGA)   | 57        | 7.11%   |
| 1600x900 (HD+)     | 34        | 4.24%   |
| 1680x1050 (WSXGA+) | 32        | 3.99%   |
| 1920x1200 (WUXGA)  | 24        | 2.99%   |
| 1024x600           | 24        | 2.99%   |
| 1440x900 (WXGA+)   | 21        | 2.62%   |
| 2560x1440 (QHD)    | 16        | 2%      |
| 3840x2160 (4K)     | 15        | 1.87%   |
| 1024x768 (XGA)     | 10        | 1.25%   |
| Unknown            | 8         | 1%      |
| 1360x768           | 7         | 0.87%   |
| 2560x1600          | 3         | 0.37%   |
| 1280x720 (HD)      | 3         | 0.37%   |
| 3840x2400          | 2         | 0.25%   |
| 3600x1200          | 2         | 0.25%   |
| 3440x1440          | 2         | 0.25%   |
| 2560x1080          | 2         | 0.25%   |
| 2288x1287          | 2         | 0.25%   |
| 2048x1536          | 2         | 0.25%   |
| 1280x768           | 2         | 0.25%   |
| 5760x2160          | 1         | 0.12%   |
| 3200x1800 (QHD+)   | 1         | 0.12%   |
| 3200x1080          | 1         | 0.12%   |
| 2880x1800          | 1         | 0.12%   |
| 2736x1824          | 1         | 0.12%   |
| 2160x1200          | 1         | 0.12%   |
| 2048x1152          | 1         | 0.12%   |
| 1920x540           | 1         | 0.12%   |
| 1600x1200          | 1         | 0.12%   |
| 1360x765           | 1         | 0.12%   |
| 1152x864           | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 232       | 28.61%  |
| 14      | 77        | 9.49%   |
| 13      | 77        | 9.49%   |
| 17      | 61        | 7.52%   |
| 24      | 42        | 5.18%   |
| Unknown | 36        | 4.44%   |
| 19      | 33        | 4.07%   |
| 11      | 30        | 3.7%    |
| 21      | 29        | 3.58%   |
| 23      | 27        | 3.33%   |
| 27      | 24        | 2.96%   |
| 10      | 23        | 2.84%   |
| 22      | 21        | 2.59%   |
| 20      | 18        | 2.22%   |
| 18      | 18        | 2.22%   |
| 12      | 16        | 1.97%   |
| 31      | 6         | 0.74%   |
| 72      | 5         | 0.62%   |
| 84      | 3         | 0.37%   |
| 34      | 3         | 0.37%   |
| 26      | 3         | 0.37%   |
| 8       | 3         | 0.37%   |
| 41      | 2         | 0.25%   |
| 39      | 2         | 0.25%   |
| 38      | 2         | 0.25%   |
| 32      | 2         | 0.25%   |
| 25      | 2         | 0.25%   |
| 9       | 2         | 0.25%   |
| 65      | 1         | 0.12%   |
| 63      | 1         | 0.12%   |
| 55      | 1         | 0.12%   |
| 48      | 1         | 0.12%   |
| 47      | 1         | 0.12%   |
| 43      | 1         | 0.12%   |
| 42      | 1         | 0.12%   |
| 40      | 1         | 0.12%   |
| 37      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 29      | 1         | 0.12%   |
| 7       | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 367       | 45.65%  |
| 201-300     | 107       | 13.31%  |
| 501-600     | 96        | 11.94%  |
| 401-500     | 90        | 11.19%  |
| 351-400     | 67        | 8.33%   |
| Unknown     | 36        | 4.48%   |
| 601-700     | 8         | 1%      |
| 1501-2000   | 8         | 1%      |
| 801-900     | 6         | 0.75%   |
| 701-800     | 6         | 0.75%   |
| 1001-1500   | 5         | 0.62%   |
| 101-200     | 4         | 0.5%    |
| 901-1000    | 4         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 506       | 66.14%  |
| 16/10   | 151       | 19.74%  |
| 5/4     | 53        | 6.93%   |
| Unknown | 28        | 3.66%   |
| 4/3     | 18        | 2.35%   |
| 21/9    | 4         | 0.52%   |
| 3/2     | 3         | 0.39%   |
| 6/5     | 2         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 230       | 28.47%  |
| 81-90          | 125       | 15.47%  |
| 201-250        | 99        | 12.25%  |
| 151-200        | 61        | 7.55%   |
| 141-150        | 42        | 5.2%    |
| Unknown        | 36        | 4.46%   |
| 71-80          | 30        | 3.71%   |
| 51-60          | 30        | 3.71%   |
| 301-350        | 26        | 3.22%   |
| 41-50          | 25        | 3.09%   |
| 121-130        | 22        | 2.72%   |
| 251-300        | 18        | 2.23%   |
| 61-70          | 13        | 1.61%   |
| More than 1000 | 12        | 1.49%   |
| 351-500        | 12        | 1.49%   |
| 501-1000       | 11        | 1.36%   |
| 131-140        | 8         | 0.99%   |
| 1-40           | 4         | 0.5%    |
| 111-120        | 3         | 0.37%   |
| 91-100         | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 293       | 36.86%  |
| 101-120       | 282       | 35.47%  |
| 121-160       | 143       | 17.99%  |
| Unknown       | 36        | 4.53%   |
| 161-240       | 18        | 2.26%   |
| 1-50          | 16        | 2.01%   |
| More than 240 | 7         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 733       | 87.05%  |
| 2     | 76        | 9.03%   |
| 0     | 27        | 3.21%   |
| 3     | 5         | 0.59%   |
| 4     | 1         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 435       | 33.51%  |
| Intel                             | 280       | 21.57%  |
| Qualcomm Atheros                  | 186       | 14.33%  |
| Broadcom                          | 105       | 8.09%   |
| Nvidia                            | 40        | 3.08%   |
| Ralink Technology                 | 36        | 2.77%   |
| Marvell Technology Group          | 34        | 2.62%   |
| Broadcom Limited                  | 32        | 2.47%   |
| Ralink                            | 25        | 1.93%   |
| TP-Link                           | 15        | 1.16%   |
| Samsung Electronics               | 12        | 0.92%   |
| VIA Technologies                  | 9         | 0.69%   |
| Attansic Technology               | 9         | 0.69%   |
| ASIX Electronics                  | 9         | 0.69%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.39%   |
| Xiaomi                            | 4         | 0.31%   |
| Qualcomm Atheros Communications   | 4         | 0.31%   |
| Huawei Technologies               | 4         | 0.31%   |
| D-Link System                     | 4         | 0.31%   |
| Belkin Components                 | 4         | 0.31%   |
| AMD                               | 4         | 0.31%   |
| D-Link                            | 3         | 0.23%   |
| 3Com                              | 3         | 0.23%   |
| ULi Electronics                   | 2         | 0.15%   |
| NetGear                           | 2         | 0.15%   |
| JMicron Technology                | 2         | 0.15%   |
| Intersil                          | 2         | 0.15%   |
| Hewlett-Packard                   | 2         | 0.15%   |
| Dell                              | 2         | 0.15%   |
| ZyXEL Communications              | 1         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.08%   |
| U-Blox                            | 1         | 0.08%   |
| Tenda                             | 1         | 0.08%   |
| T & A Mobile Phones               | 1         | 0.08%   |
| Sitecom Europe                    | 1         | 0.08%   |
| Seeed                             | 1         | 0.08%   |
| Research In Motion                | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.08%   |
| Motorola PCS                      | 1         | 0.08%   |
| Microchip Technology              | 1         | 0.08%   |
| MEDIATEK                          | 1         | 0.08%   |
| LSI                               | 1         | 0.08%   |
| Logitec                           | 1         | 0.08%   |
| Linksys                           | 1         | 0.08%   |
| LG Electronics                    | 1         | 0.08%   |
| Lab126                            | 1         | 0.08%   |
| FIBOCOM                           | 1         | 0.08%   |
| Ericsson Business Mobile Networks | 1         | 0.08%   |
| ASUSTek Computer                  | 1         | 0.08%   |
| Arduino SA                        | 1         | 0.08%   |
| Aquantia                          | 1         | 0.08%   |
| Apple                             | 1         | 0.08%   |
| ADMtek                            | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 241       | 16.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 95        | 6.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 36        | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 33        | 2.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 28        | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 27        | 1.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 1.76%   |
| Intel Wireless 7260                                                     | 24        | 1.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 23        | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 20        | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 1.15%   |
| Ralink MT7601U Wireless Adapter                                         | 14        | 0.95%   |
| Nvidia MCP61 Ethernet                                                   | 14        | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 12        | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 0.81%   |
| Intel Wireless 7265                                                     | 11        | 0.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 11        | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 10        | 0.68%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 9         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 9         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                                | 9         | 0.61%   |
| Attansic AR8152 v2.0 Fast Ethernet                                      | 9         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 0.54%   |
| Realtek 802.11ac NIC                                                    | 8         | 0.54%   |
| Intel Wireless 3165                                                     | 8         | 0.54%   |
| Intel Wireless 3160                                                     | 8         | 0.54%   |
| Intel Ethernet Connection I217-LM                                       | 8         | 0.54%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 7         | 0.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 7         | 0.47%   |
| Intel Wireless 8265 / 8275                                              | 7         | 0.47%   |
| Intel WiFi Link 5100                                                    | 7         | 0.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.47%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 6         | 0.41%   |
| Ralink RT5370 Wireless Adapter                                          | 6         | 0.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 6         | 0.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 6         | 0.41%   |
| Nvidia CK804 Ethernet Controller                                        | 6         | 0.41%   |
| Intel Wireless 8260                                                     | 6         | 0.41%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 0.41%   |
| Intel Ethernet Connection I218-LM                                       | 6         | 0.41%   |
| Intel 82579V Gigabit Network Connection                                 | 6         | 0.41%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 6         | 0.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 6         | 0.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 6         | 0.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 6         | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.34%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.34%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.34%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 5         | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 5         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 202       | 31.17%  |
| Qualcomm Atheros                | 155       | 23.92%  |
| Realtek Semiconductor           | 110       | 16.98%  |
| Broadcom                        | 64        | 9.88%   |
| Ralink Technology               | 36        | 5.56%   |
| Ralink                          | 25        | 3.86%   |
| Broadcom Limited                | 17        | 2.62%   |
| TP-Link                         | 15        | 2.31%   |
| Qualcomm Atheros Communications | 4         | 0.62%   |
| Belkin Components               | 4         | 0.62%   |
| NetGear                         | 2         | 0.31%   |
| D-Link System                   | 2         | 0.31%   |
| D-Link                          | 2         | 0.31%   |
| ZyXEL Communications            | 1         | 0.15%   |
| Tenda                           | 1         | 0.15%   |
| Sitecom Europe                  | 1         | 0.15%   |
| Samsung Electronics             | 1         | 0.15%   |
| MEDIATEK                        | 1         | 0.15%   |
| Marvell Technology Group        | 1         | 0.15%   |
| Logitec                         | 1         | 0.15%   |
| Linksys                         | 1         | 0.15%   |
| Dell                            | 1         | 0.15%   |
| ASUSTek Computer                | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 36        | 5.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 27        | 4.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 26        | 3.99%   |
| Intel Wireless 7260                                                           | 24        | 3.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 23        | 3.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 20        | 3.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 18        | 2.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 17        | 2.61%   |
| Ralink MT7601U Wireless Adapter                                               | 14        | 2.15%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 12        | 1.84%   |
| Intel Wireless 7265                                                           | 11        | 1.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 11        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 10        | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 10        | 1.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 10        | 1.53%   |
| Intel Wi-Fi 6 AX200                                                           | 10        | 1.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 10        | 1.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 9         | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 8         | 1.23%   |
| Realtek 802.11ac NIC                                                          | 8         | 1.23%   |
| Intel Wireless 3165                                                           | 8         | 1.23%   |
| Intel Wireless 3160                                                           | 8         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 7         | 1.07%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 7         | 1.07%   |
| Intel Wireless 8265 / 8275                                                    | 7         | 1.07%   |
| Intel WiFi Link 5100                                                          | 7         | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 7         | 1.07%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 6         | 0.92%   |
| Ralink RT5370 Wireless Adapter                                                | 6         | 0.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 6         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 6         | 0.92%   |
| Intel Wireless 8260                                                           | 6         | 0.92%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 6         | 0.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 6         | 0.92%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 6         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 5         | 0.77%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 5         | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 5         | 0.77%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 5         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 5         | 0.77%   |
| Intel Centrino Ultimate-N 6300                                                | 5         | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 5         | 0.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 4         | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 4         | 0.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 4         | 0.61%   |
| Ralink RT5572 Wireless Adapter                                                | 4         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 0.61%   |
| Intel Wireless-AC 9260                                                        | 4         | 0.61%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 0.61%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 0.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 4         | 0.61%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                   | 4         | 0.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4         | 0.61%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 4         | 0.61%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 4         | 0.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 3         | 0.46%   |
| Realtek RTL8187B Wireless Adapter                                             | 3         | 0.46%   |
| Realtek RTL8187 Wireless Adapter                                              | 3         | 0.46%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 3         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 391       | 49.18%  |
| Intel                            | 135       | 16.98%  |
| Qualcomm Atheros                 | 56        | 7.04%   |
| Broadcom                         | 52        | 6.54%   |
| Nvidia                           | 40        | 5.03%   |
| Marvell Technology Group         | 33        | 4.15%   |
| Broadcom Limited                 | 15        | 1.89%   |
| Samsung Electronics              | 10        | 1.26%   |
| VIA Technologies                 | 9         | 1.13%   |
| Attansic Technology              | 9         | 1.13%   |
| ASIX Electronics                 | 9         | 1.13%   |
| Silicon Integrated Systems [SiS] | 5         | 0.63%   |
| Xiaomi                           | 4         | 0.5%    |
| Huawei Technologies              | 3         | 0.38%   |
| 3Com                             | 3         | 0.38%   |
| ULi Electronics                  | 2         | 0.25%   |
| JMicron Technology               | 2         | 0.25%   |
| D-Link System                    | 2         | 0.25%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.13%   |
| T & A Mobile Phones              | 1         | 0.13%   |
| Research In Motion               | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.13%   |
| Motorola PCS                     | 1         | 0.13%   |
| Microchip Technology             | 1         | 0.13%   |
| LG Electronics                   | 1         | 0.13%   |
| Lab126                           | 1         | 0.13%   |
| Intersil                         | 1         | 0.13%   |
| Hewlett-Packard                  | 1         | 0.13%   |
| FIBOCOM                          | 1         | 0.13%   |
| D-Link                           | 1         | 0.13%   |
| Aquantia                         | 1         | 0.13%   |
| Apple                            | 1         | 0.13%   |
| ADMtek                           | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 241       | 29.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 95        | 11.8%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 33        | 4.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 28        | 3.48%   |
| Nvidia MCP61 Ethernet                                             | 14        | 1.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 1.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 10        | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 1.12%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 9         | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.99%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 7         | 0.87%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 7         | 0.87%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.75%   |
| Nvidia CK804 Ethernet Controller                                  | 6         | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.75%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 5         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.62%   |
| Nvidia MCP67 Ethernet                                             | 5         | 0.62%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.62%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 5         | 0.62%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 5         | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.62%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 5         | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.62%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 4         | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.5%    |
| Nvidia MCP73 Ethernet                                             | 4         | 0.5%    |
| Nvidia MCP51 Ethernet Controller                                  | 4         | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 0.5%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 4         | 0.5%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 4         | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 4         | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 4         | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.5%    |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 4         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.5%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 4         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.37%   |
| Intel PRO/100 VE Network Connection                               | 3         | 0.37%   |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.37%   |
| Intel 82573L Gigabit Ethernet Controller                          | 3         | 0.37%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 0.37%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 3         | 0.37%   |
| ASIX AX88772A Fast Ethernet                                       | 3         | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.25%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.25%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2         | 0.25%   |
| ULi ULi 1689,1573 integrated ethernet.                            | 2         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 741       | 53.7%   |
| WiFi     | 618       | 44.78%  |
| Modem    | 20        | 1.45%   |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 530       | 51.26%  |
| Ethernet | 503       | 48.65%  |
| Modem    | 1         | 0.1%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 475       | 57.23%  |
| 1     | 302       | 36.39%  |
| 0     | 36        | 4.34%   |
| 3     | 13        | 1.57%   |
| 4     | 3         | 0.36%   |
| 6     | 1         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 738       | 87.96%  |
| Yes  | 101       | 12.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 118       | 31.72%  |
| Qualcomm Atheros Communications | 33        | 8.87%   |
| Cambridge Silicon Radio         | 33        | 8.87%   |
| Broadcom                        | 32        | 8.6%    |
| Realtek Semiconductor           | 31        | 8.33%   |
| Lite-On Technology              | 15        | 4.03%   |
| IMC Networks                    | 15        | 4.03%   |
| Hewlett-Packard                 | 15        | 4.03%   |
| Apple                           | 14        | 3.76%   |
| Foxconn / Hon Hai               | 11        | 2.96%   |
| Dell                            | 11        | 2.96%   |
| Toshiba                         | 9         | 2.42%   |
| Ralink                          | 9         | 2.42%   |
| Alps Electric                   | 8         | 2.15%   |
| ASUSTek Computer                | 5         | 1.34%   |
| Ralink Technology               | 2         | 0.54%   |
| Askey Computer                  | 2         | 0.54%   |
| Qcom                            | 1         | 0.27%   |
| Micro Star International        | 1         | 0.27%   |
| MediaTek                        | 1         | 0.27%   |
| Marvell Semiconductor           | 1         | 0.27%   |
| Integrated System Solution      | 1         | 0.27%   |
| HTC (High Tech Computer)        | 1         | 0.27%   |
| Fujitsu                         | 1         | 0.27%   |
| Dynex                           | 1         | 0.27%   |
| Chicony Electronics             | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 66        | 17.69%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 33        | 8.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 17        | 4.56%   |
| Realtek Bluetooth Radio                                                             | 16        | 4.29%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 3.49%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 2.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 9         | 2.41%   |
| Intel AX200 Bluetooth                                                               | 9         | 2.41%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 2.14%   |
| Apple Bluetooth Host Controller                                                     | 8         | 2.14%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 1.88%   |
| Lite-On Bluetooth Device                                                            | 7         | 1.88%   |
| Intel Bluetooth Device                                                              | 7         | 1.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 1.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 6         | 1.61%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.61%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 1.34%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 1.34%   |
| IMC Networks Bluetooth module                                                       | 5         | 1.34%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.34%   |
| Apple Bluetooth HCI                                                                 | 5         | 1.34%   |
| Toshiba Integrated Bluetooth HCI                                                    | 4         | 1.07%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 1.07%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 1.07%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 1.07%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.07%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 1.07%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.8%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 0.8%    |
| Intel AX210 Bluetooth                                                               | 3         | 0.8%    |
| IMC Networks Bluetooth Radio                                                        | 3         | 0.8%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.8%    |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.8%    |
| Dell Wireless 350 Bluetooth                                                         | 3         | 0.8%    |
| Broadcom HP Portable Bumble Bee                                                     | 3         | 0.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.8%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.8%    |
| Broadcom BCM2045 Bluetooth                                                          | 3         | 0.8%    |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 3         | 0.8%    |
| Toshiba Bluetooth Device                                                            | 2         | 0.54%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.54%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.54%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 2         | 0.54%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 0.54%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.54%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.54%   |
| Askey Bluetooth Device                                                              | 2         | 0.54%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 2         | 0.54%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 2         | 0.54%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.27%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.27%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.27%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.27%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.27%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.27%   |
| Micro Star International Bluetooth EDR Device                                       | 1         | 0.27%   |
| MediaTek BT                                                                         | 1         | 0.27%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.27%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 558       | 58.06%  |
| AMD                                          | 194       | 20.19%  |
| Nvidia                                       | 131       | 13.63%  |
| C-Media Electronics                          | 14        | 1.46%   |
| VIA Technologies                             | 11        | 1.14%   |
| Creative Labs                                | 9         | 0.94%   |
| Silicon Integrated Systems [SiS]             | 7         | 0.73%   |
| Logitech                                     | 5         | 0.52%   |
| GN Netcom                                    | 4         | 0.42%   |
| XMOS                                         | 3         | 0.31%   |
| ULi Electronics                              | 2         | 0.21%   |
| Texas Instruments                            | 2         | 0.21%   |
| Plantronics                                  | 2         | 0.21%   |
| Generalplus Technology                       | 2         | 0.21%   |
| Creative Technology                          | 2         | 0.21%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.1%    |
| Unknown                                      | 1         | 0.1%    |
| Realtek Semiconductor                        | 1         | 0.1%    |
| Razer USA                                    | 1         | 0.1%    |
| KORG                                         | 1         | 0.1%    |
| Guillemot                                    | 1         | 0.1%    |
| Focusrite-Novation                           | 1         | 0.1%    |
| ESI                                          | 1         | 0.1%    |
| Elitegroup Computer Systems (ECS)            | 1         | 0.1%    |
| Elgato Systems                               | 1         | 0.1%    |
| Dell                                         | 1         | 0.1%    |
| Cirrus Logic                                 | 1         | 0.1%    |
| BEHRINGER International                      | 1         | 0.1%    |
| ASUSTek Computer                             | 1         | 0.1%    |
| Asahi Kasei Microsystems                     | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 75        | 6.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 55        | 4.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 54        | 4.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 52        | 4.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 47        | 4.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 43        | 3.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 38        | 3.36%   |
| AMD FCH Azalia Controller                                                                         | 37        | 3.27%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 33        | 2.92%   |
| AMD Wrestler HDMI Audio                                                                           | 28        | 2.47%   |
| Intel 8 Series HD Audio Controller                                                                | 26        | 2.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 25        | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25        | 2.21%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 24        | 2.12%   |
| Nvidia High Definition Audio Controller                                                           | 23        | 2.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 21        | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 20        | 1.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 18        | 1.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 16        | 1.41%   |
| Nvidia MCP61 High Definition Audio                                                                | 15        | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 15        | 1.33%   |
| AMD High Definition Audio Controller                                                              | 14        | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 0.97%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 0.88%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 0.88%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 10        | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 0.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 0.8%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 0.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 9         | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 8         | 0.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 0.62%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 7         | 0.62%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 7         | 0.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 0.53%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 6         | 0.53%   |
| AMD Trinity HDMI Audio Controller                                                                 | 6         | 0.53%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 5         | 0.44%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 5         | 0.44%   |
| Nvidia MCP67 High Definition Audio                                                                | 5         | 0.44%   |
| Nvidia MCP51 High Definition Audio                                                                | 5         | 0.44%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.44%   |
| Nvidia CK804 AC'97 Audio Controller                                                               | 5         | 0.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 0.44%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.44%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 5         | 0.44%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 5         | 0.44%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 0.44%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 5         | 0.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 0.44%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 4         | 0.35%   |
| Nvidia MCP73 High Definition Audio                                                                | 4         | 0.35%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 126       | 22.14%  |
| Samsung Electronics | 117       | 20.56%  |
| SK Hynix            | 86        | 15.11%  |
| Kingston            | 50        | 8.79%   |
| Micron Technology   | 41        | 7.21%   |
| Crucial             | 23        | 4.04%   |
| Corsair             | 20        | 3.51%   |
| Nanya Technology    | 15        | 2.64%   |
| A-DATA Technology   | 15        | 2.64%   |
| G.Skill             | 11        | 1.93%   |
| Elpida              | 9         | 1.58%   |
| Unknown (ABCD)      | 8         | 1.41%   |
| Smart               | 6         | 1.05%   |
| Team                | 4         | 0.7%    |
| Patriot             | 4         | 0.7%    |
| Teikon              | 3         | 0.53%   |
| Qimonda             | 3         | 0.53%   |
| Transcend           | 2         | 0.35%   |
| TIMETEC             | 2         | 0.35%   |
| Ramaxel Technology  | 2         | 0.35%   |
| ASint Technology    | 2         | 0.35%   |
| Apacer              | 2         | 0.35%   |
| Unknown (07FB)      | 1         | 0.18%   |
| Unifosa             | 1         | 0.18%   |
| Toshiba             | 1         | 0.18%   |
| SMART Brazil        | 1         | 0.18%   |
| Sesame              | 1         | 0.18%   |
| PRINCETON           | 1         | 0.18%   |
| PNY                 | 1         | 0.18%   |
| Neo Forza           | 1         | 0.18%   |
| Multilaser          | 1         | 0.18%   |
| Infineon            | 1         | 0.18%   |
| High Bridge         | 1         | 0.18%   |
| Goldkey             | 1         | 0.18%   |
| Golden Empire       | 1         | 0.18%   |
| e2e4                | 1         | 0.18%   |
| DigiBoard           | 1         | 0.18%   |
| Avant               | 1         | 0.18%   |
| 48spaces            | 1         | 0.18%   |
| Unknown             | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 12        | 1.93%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 8         | 1.29%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 7         | 1.13%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 7         | 1.13%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 6         | 0.96%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 0.96%   |
| Unknown RAM Module 1024MB SODIMM DRAM                            | 5         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 5         | 0.8%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 5         | 0.8%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 0.64%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR3 2400MT/s   | 4         | 0.64%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 4         | 0.64%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.64%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.64%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 4         | 0.64%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 4         | 0.64%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.48%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 3         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 3         | 0.48%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 3         | 0.48%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.48%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.48%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 3         | 0.48%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s         | 3         | 0.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.48%   |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s           | 3         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.32%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 2         | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                        | 2         | 0.32%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 2         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 2         | 0.32%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 2         | 0.32%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.32%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 2         | 0.32%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                       | 2         | 0.32%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 2         | 0.32%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 2         | 0.32%   |
| SK Hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.32%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.32%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.32%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 2         | 0.32%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.32%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.32%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 0.32%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 2         | 0.32%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.32%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.32%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.32%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.32%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR 2048MT/s            | 2         | 0.32%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s              | 2         | 0.32%   |
| Samsung RAM M3 78T6553EZS-CE6 512MB DIMM DDR 667MT/s             | 2         | 0.32%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 223       | 44.6%   |
| DDR4    | 105       | 21%     |
| DDR2    | 75        | 15%     |
| SDRAM   | 27        | 5.4%    |
| Unknown | 22        | 4.4%    |
| DDR     | 16        | 3.2%    |
| LPDDR4  | 14        | 2.8%    |
| LPDDR3  | 10        | 2%      |
| DRAM    | 8         | 1.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 311       | 63.47%  |
| DIMM         | 160       | 32.65%  |
| Row Of Chips | 16        | 3.27%   |
| Unknown      | 2         | 0.41%   |
| Chip         | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 173       | 30.73%  |
| 2048  | 157       | 27.89%  |
| 8192  | 113       | 20.07%  |
| 1024  | 67        | 11.9%   |
| 16384 | 28        | 4.97%   |
| 512   | 14        | 2.49%   |
| 256   | 5         | 0.89%   |
| 32768 | 3         | 0.53%   |
| 128   | 2         | 0.36%   |
| 65536 | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 123       | 22.95%  |
| 1333    | 48        | 8.96%   |
| Unknown | 39        | 7.28%   |
| 667     | 36        | 6.72%   |
| 2400    | 34        | 6.34%   |
| 1334    | 34        | 6.34%   |
| 2667    | 33        | 6.16%   |
| 3200    | 26        | 4.85%   |
| 800     | 25        | 4.66%   |
| 2133    | 21        | 3.92%   |
| 533     | 16        | 2.99%   |
| 1067    | 14        | 2.61%   |
| 1066    | 14        | 2.61%   |
| 2048    | 9         | 1.68%   |
| 1867    | 9         | 1.68%   |
| 400     | 8         | 1.49%   |
| 3266    | 6         | 1.12%   |
| 4267    | 4         | 0.75%   |
| 3600    | 4         | 0.75%   |
| 1866    | 4         | 0.75%   |
| 333     | 4         | 0.75%   |
| 49926   | 3         | 0.56%   |
| 4199    | 3         | 0.56%   |
| 3466    | 2         | 0.37%   |
| 3000    | 2         | 0.37%   |
| 975     | 2         | 0.37%   |
| 266     | 2         | 0.37%   |
| 41632   | 1         | 0.19%   |
| 8400    | 1         | 0.19%   |
| 3151    | 1         | 0.19%   |
| 2800    | 1         | 0.19%   |
| 2733    | 1         | 0.19%   |
| 2666    | 1         | 0.19%   |
| 1800    | 1         | 0.19%   |
| 1639    | 1         | 0.19%   |
| 1200    | 1         | 0.19%   |
| 2       | 1         | 0.19%   |
| 1       | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 7         | 35%     |
| Samsung Electronics   | 5         | 25%     |
| Brother Industries    | 4         | 20%     |
| Canon                 | 2         | 10%     |
| STMicroelectronics    | 1         | 5%      |
| Lexmark International | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| STMicroelectronics USB Printer P        | 1         | 5%      |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 5%      |
| Samsung SCX-4200 series                 | 1         | 5%      |
| Samsung SCX-3400 Series                 | 1         | 5%      |
| Samsung ML-1640 Series Laser Printer    | 1         | 5%      |
| Samsung M2020 Series                    | 1         | 5%      |
| Lexmark International MS610de           | 1         | 5%      |
| HP PSC 1500 series                      | 1         | 5%      |
| HP OfficeJet 4650 series                | 1         | 5%      |
| HP LaserJet 1200                        | 1         | 5%      |
| HP DeskJet D2460                        | 1         | 5%      |
| HP DeskJet 3630 series                  | 1         | 5%      |
| HP Deskjet 3520 series                  | 1         | 5%      |
| HP Deskjet 1050 J410                    | 1         | 5%      |
| Canon TS5100 series                     | 1         | 5%      |
| Canon MF3110                            | 1         | 5%      |
| Brother PTUSB Printing                  | 1         | 5%      |
| Brother PT-2450DX                       | 1         | 5%      |
| Brother Printer                         | 1         | 5%      |
| Brother DCP-7055W                       | 1         | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Canon           | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 20%     |
| HP ScanJet 2400c                                              | 1         | 20%     |
| HP HP4470C                                                    | 1         | 20%     |
| Canon CanoScan LiDE 500F                                      | 1         | 20%     |
| Canon CanoScan LiDE 220                                       | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 115       | 25.39%  |
| Realtek Semiconductor                  | 33        | 7.28%   |
| IMC Networks                           | 33        | 7.28%   |
| Suyin                                  | 27        | 5.96%   |
| Microdia                               | 27        | 5.96%   |
| Acer                                   | 26        | 5.74%   |
| Silicon Motion                         | 18        | 3.97%   |
| Apple                                  | 18        | 3.97%   |
| Alcor Micro                            | 17        | 3.75%   |
| Sunplus Innovation Technology          | 16        | 3.53%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.31%   |
| Quanta                                 | 14        | 3.09%   |
| Syntek                                 | 9         | 1.99%   |
| Ricoh                                  | 9         | 1.99%   |
| Logitech                               | 9         | 1.99%   |
| Lite-On Technology                     | 8         | 1.77%   |
| Lenovo                                 | 6         | 1.32%   |
| GEMBIRD                                | 5         | 1.1%    |
| Samsung Electronics                    | 4         | 0.88%   |
| Importek                               | 4         | 0.88%   |
| Z-Star Microelectronics                | 3         | 0.66%   |
| Microsoft                              | 3         | 0.66%   |
| Generalplus Technology                 | 3         | 0.66%   |
| USB Camera                             | 2         | 0.44%   |
| Unknown                                | 2         | 0.44%   |
| SJ-180517-N                            | 2         | 0.44%   |
| Luxvisions Innotech Limited            | 2         | 0.44%   |
| LG Electronics                         | 2         | 0.44%   |
| KYE Systems (Mouse Systems)            | 2         | 0.44%   |
| Genesys Logic                          | 2         | 0.44%   |
| ARC International                      | 2         | 0.44%   |
| ALi                                    | 2         | 0.44%   |
| Y Media                                | 1         | 0.22%   |
| Toshiba                                | 1         | 0.22%   |
| Sunplus Technology                     | 1         | 0.22%   |
| OmniVision Technologies                | 1         | 0.22%   |
| Novatek Microelectronics               | 1         | 0.22%   |
| Nintendo                               | 1         | 0.22%   |
| Huawei Technologies                    | 1         | 0.22%   |
| Guillemot                              | 1         | 0.22%   |
| GEO Semi                               | 1         | 0.22%   |
| DJEDDA19IE51V5                         | 1         | 0.22%   |
| DigiTech                               | 1         | 0.22%   |
| Creative Technology                    | 1         | 0.22%   |
| CQG-5693-201019                        | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                      | 12        | 2.63%   |
| Chicony Integrated Camera                         | 9         | 1.97%   |
| Alcor Micro USB 2.0 Web Camera                    | 9         | 1.97%   |
| Chicony HP Truevision HD                          | 7         | 1.54%   |
| IMC Networks UVC VGA Webcam                       | 6         | 1.32%   |
| Chicony TOSHIBA Web Camera - HD                   | 6         | 1.32%   |
| Chicony HP HD Webcam                              | 6         | 1.32%   |
| Apple iPhone 5/5C/5S/6/SE                         | 6         | 1.32%   |
| Silicon Motion WebCam SC-0311139N                 | 5         | 1.1%    |
| IMC Networks USB 2.0 UVC VGA WebCam               | 5         | 1.1%    |
| Chicony HP Webcam                                 | 5         | 1.1%    |
| Chicony HD WebCam                                 | 5         | 1.1%    |
| Chicony EasyCamera                                | 5         | 1.1%    |
| Apple FaceTime HD Camera                          | 5         | 1.1%    |
| Acer Lenovo EasyCamera                            | 5         | 1.1%    |
| Suyin Acer CrystalEye Webcam                      | 4         | 0.88%   |
| Sunplus HD WebCam                                 | 4         | 0.88%   |
| Samsung Galaxy A5 (MTP)                           | 4         | 0.88%   |
| Quanta HP Webcam                                  | 4         | 0.88%   |
| Lenovo Integrated Webcam [R5U877]                 | 4         | 0.88%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 4         | 0.88%   |
| Chicony USB 2.0 Camera                            | 4         | 0.88%   |
| Chicony HP HD Camera                              | 4         | 0.88%   |
| Chicony 2.0M UVC Webcam / CNF7129                 | 4         | 0.88%   |
| Apple Built-in iSight                             | 4         | 0.88%   |
| Alcor Micro Asus Integrated Webcam                | 4         | 0.88%   |
| Suyin WebCam                                      | 3         | 0.66%   |
| Suyin Acer/HP Integrated Webcam [CN0314]          | 3         | 0.66%   |
| Realtek Integrated Webcam HD                      | 3         | 0.66%   |
| Realtek Integrated Webcam                         | 3         | 0.66%   |
| Quanta HP HD Camera                               | 3         | 0.66%   |
| Microsoft LifeCam HD-3000                         | 3         | 0.66%   |
| Microdia Sonix USB 2.0 Camera                     | 3         | 0.66%   |
| Microdia Laptop_Integrated_Webcam_2M              | 3         | 0.66%   |
| Microdia 1.3 MPixel Integrated Webcam             | 3         | 0.66%   |
| Lite-On TOSHIBA Web Camera - HD                   | 3         | 0.66%   |
| Lite-On HP HD Camera                              | 3         | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 3         | 0.66%   |
| IMC Networks USB2.0 UVC HD Webcam                 | 3         | 0.66%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 0.66%   |
| IMC Networks USB 2.0 Camera                       | 3         | 0.66%   |
| IMC Networks Lenovo EasyCamera                    | 3         | 0.66%   |
| Chicony Lenovo EasyCamera                         | 3         | 0.66%   |
| Chicony Integrated HP HD Webcam                   | 3         | 0.66%   |
| Chicony HD WebCam (Acer)                          | 3         | 0.66%   |
| Chicony Camera                                    | 3         | 0.66%   |
| Acer VGA WebCam                                   | 3         | 0.66%   |
| Acer Integrated Camera                            | 3         | 0.66%   |
| Acer HD WebCam                                    | 3         | 0.66%   |
| USB Camera USB Camera                             | 2         | 0.44%   |
| Unknown 720p HD Camera                            | 2         | 0.44%   |
| Syntek Integrated Camera                          | 2         | 0.44%   |
| Syntek EasyCamera                                 | 2         | 0.44%   |
| Suyin HP TrueVision HD Integrated Webcam          | 2         | 0.44%   |
| Sunplus Laptop Integrated Webcam HD               | 2         | 0.44%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 0.44%   |
| Sunplus HP HD Webcam [Fixed]                      | 2         | 0.44%   |
| SJ-180517-N 1080P Webcam                          | 2         | 0.44%   |
| Silicon Motion WebCam SC-13HDL11939N              | 2         | 0.44%   |
| Silicon Motion WebCam SC-10HDD12636N              | 2         | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 44.07%  |
| AuthenTec                  | 11        | 18.64%  |
| Upek                       | 7         | 11.86%  |
| Synaptics                  | 4         | 6.78%   |
| STMicroelectronics         | 4         | 6.78%   |
| Shenzhen Goodix Technology | 4         | 6.78%   |
| Samsung Electronics        | 1         | 1.69%   |
| LighTuning Technology      | 1         | 1.69%   |
| Elan Microelectronics      | 1         | 1.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 6         | 10.17%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 5         | 8.47%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 4         | 6.78%   |
| STMicroelectronics Fingerprint Reader                      | 4         | 6.78%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 3         | 5.08%   |
| AuthenTec AES2810                                          | 3         | 5.08%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 3         | 5.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 3.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.39%   |
| Validity Sensors VFS491                                    | 2         | 3.39%   |
| Validity Sensors Fingerprint scanner                       | 2         | 3.39%   |
| Shenzhen Goodix FingerPrint                                | 2         | 3.39%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 2         | 3.39%   |
| AuthenTec AES1600                                          | 2         | 3.39%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 1.69%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.69%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.69%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 1.69%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 1.69%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.69%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 1.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 1.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 1.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 1.69%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 1.69%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 1.69%   |
| Samsung Fingerprint Sensor Device - 730B                   | 1         | 1.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 1.69%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.69%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 7         | 31.82%  |
| O2 Micro              | 6         | 27.27%  |
| Broadcom              | 6         | 27.27%  |
| Upek                  | 1         | 4.55%   |
| Realtek Semiconductor | 1         | 4.55%   |
| OmniKey               | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 31.82%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 13.64%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 9.09%   |
| Broadcom 5880                                                                | 2         | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.55%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 4.55%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 649       | 77.54%  |
| 1     | 154       | 18.4%   |
| 2     | 29        | 3.46%   |
| 3     | 4         | 0.48%   |
| 4     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 59        | 26.46%  |
| Graphics card            | 41        | 18.39%  |
| Net/wireless             | 32        | 14.35%  |
| Chipcard                 | 20        | 8.97%   |
| Bluetooth                | 12        | 5.38%   |
| Communication controller | 10        | 4.48%   |
| Multimedia controller    | 9         | 4.04%   |
| Modem                    | 8         | 3.59%   |
| Storage                  | 5         | 2.24%   |
| Sound                    | 5         | 2.24%   |
| Net/ethernet             | 5         | 2.24%   |
| Camera                   | 5         | 2.24%   |
| Unassigned class         | 4         | 1.79%   |
| Flash memory             | 4         | 1.79%   |
| Card reader              | 2         | 0.9%    |
| Network                  | 1         | 0.45%   |
| Dvb card                 | 1         | 0.45%   |

