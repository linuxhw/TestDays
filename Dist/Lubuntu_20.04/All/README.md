Lubuntu 20.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_20.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_20.04/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 527

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| MSI           | MS-AA1511                   | All in one  | [80c9ccb7c7](https://linux-hardware.org/?probe=80c9ccb7c7) | Jun 06, 2022 |
| HP            | G62                         | Notebook    | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| HP            | 3397                        | Desktop     | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| HP            | Berknip                     | Notebook    | [c81d3442c2](https://linux-hardware.org/?probe=c81d3442c2) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| ASUSTek       | X402CA                      | Notebook    | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [942f142f46](https://linux-hardware.org/?probe=942f142f46) | May 20, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | Notebook    | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [c206790d1e](https://linux-hardware.org/?probe=c206790d1e) | May 01, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Samsung       | N100SP                      | Notebook    | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Intel         | W7650                       | Notebook    | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | Desktop     | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| Haier         | U1520EM                     | Notebook    | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Google        | Celes                       | Notebook    | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| ASRock        | Q1900M                      | Desktop     | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| HP            | 3647h                       | Desktop     | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| HP            | 2AF7                        | Desktop     | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Alienware     | M17                         | Notebook    | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| Pegatron      | Narra6                      | Desktop     | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Positivo      | N600                        | Notebook    | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | Notebook    | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | Desktop     | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Toshiba       | Satellite C875              | Notebook    | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Dell          | 0FJM8V A03                  | Server      | [398f8f6326](https://linux-hardware.org/?probe=398f8f6326) | Feb 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| HP            | 3048h                       | Desktop     | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | Desktop     | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | Notebook    | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Positivo      | N600                        | Notebook    | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| Acer          | Aspire 7715Z                | Notebook    | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | Notebook    | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Sony          | VPCEJ1E1E                   | Notebook    | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| ASUSTek       | A8N5X                       | Desktop     | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ea7740294a](https://linux-hardware.org/?probe=ea7740294a) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [175dda01f6](https://linux-hardware.org/?probe=175dda01f6) | Dec 15, 2021 |
| MSI           | Katana GF76 11UC            | Notebook    | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| ASUSTek       | CM1435                      | Desktop     | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Gigabyte      | A520I AC                    | Desktop     | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Dell          | Latitude 3330               | Notebook    | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | Notebook    | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Dell          | 0T568R A00                  | Desktop     | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| Acer          | Aspire X1700                | Desktop     | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| Foxconn       | 2AA9h                       | Desktop     | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| Samsung       | R40/R41                     | Notebook    | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| HP            | Presario CQ58               | Notebook    | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | Notebook    | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [45ba0657f1](https://linux-hardware.org/?probe=45ba0657f1) | Oct 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| MSI           | MS-7309                     | Desktop     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Intel         | W7650                       | Notebook    | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | Notebook    | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| Unknown       | X79M2-Q                     | Desktop     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| Pegatron      | Acacia                      | Desktop     | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Foxconn       | Priv                        | Desktop     | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | Desktop     | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | P8C WS                      | Desktop     | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Dell          | 01V648 A03                  | Server      | [f46a021c88](https://linux-hardware.org/?probe=f46a021c88) | Sep 02, 2021 |
| Notebook      | NL40_50GU                   | Notebook    | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | 760GM-E51                   | Desktop     | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | Notebook    | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| Dell          | Latitude E5450              | Notebook    | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | 8299                        | Desktop     | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Dell          | Inspiron M5040              | Notebook    | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Dell          | 0CN7X8 A05                  | Server      | [e5766c8331](https://linux-hardware.org/?probe=e5766c8331) | Jul 22, 2021 |
| HP            | 0A1Ch E                     | Desktop     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| Gigabyte      | B450M H                     | Desktop     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| Positivo      | POS-MI945AA                 | Desktop     | [2a1eda1972](https://linux-hardware.org/?probe=2a1eda1972) | Jul 07, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| Hardkernel    | ODROID-H2                   | Desktop     | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | Notebook    | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [2383fe9425](https://linux-hardware.org/?probe=2383fe9425) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [b98c7e4685](https://linux-hardware.org/?probe=b98c7e4685) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| Notebook      | NHxxRZQ                     | Notebook    | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [5e9110ee62](https://linux-hardware.org/?probe=5e9110ee62) | Jun 18, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [51b0adff27](https://linux-hardware.org/?probe=51b0adff27) | Jun 17, 2021 |
| Samsung       | RC512                       | Notebook    | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | Notebook    | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | Notebook    | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| Dell          | Latitude D630               | Notebook    | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| ASUSTek       | K8N                         | Desktop     | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| HP            | 1905                        | Desktop     | [fd0f9e5ab1](https://linux-hardware.org/?probe=fd0f9e5ab1) | May 23, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| HP            | 09C4h                       | Desktop     | [a94946d561](https://linux-hardware.org/?probe=a94946d561) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Dell          | 0HY175 A03                  | Desktop     | [d1b6626b26](https://linux-hardware.org/?probe=d1b6626b26) | May 20, 2021 |
| HP            | 1905                        | Desktop     | [28fb3ce7e8](https://linux-hardware.org/?probe=28fb3ce7e8) | May 20, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | K8N                         | Desktop     | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| MSI           | H61M-E33                    | Desktop     | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| ASUSTek       | K8N                         | Desktop     | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8c9dd0e965](https://linux-hardware.org/?probe=8c9dd0e965) | May 06, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| HP            | Notebook                    | Notebook    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [ef051b442a](https://linux-hardware.org/?probe=ef051b442a) | Apr 28, 2021 |
| Packard Be... | IMEDIA S1350                | Desktop     | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Inspiron 7706 2n1           | Convertible | [82eb222c26](https://linux-hardware.org/?probe=82eb222c26) | Apr 23, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | Notebook    | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | Notebook    | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [2c58a29c2a](https://linux-hardware.org/?probe=2c58a29c2a) | Apr 02, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d36d3e1e58](https://linux-hardware.org/?probe=d36d3e1e58) | Apr 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | Notebook    | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [383cee85b7](https://linux-hardware.org/?probe=383cee85b7) | Mar 25, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [83716bfba8](https://linux-hardware.org/?probe=83716bfba8) | Mar 24, 2021 |
| HP            | 21D0                        | Desktop     | [ebf910609e](https://linux-hardware.org/?probe=ebf910609e) | Mar 23, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e1adceeeeb](https://linux-hardware.org/?probe=e1adceeeeb) | Mar 20, 2021 |
| Lenovo        | S10-3                       | Notebook    | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | System XPS 15Z              | Notebook    | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| HP            | 8267 A01                    | Mini pc     | [3aa09cf72a](https://linux-hardware.org/?probe=3aa09cf72a) | Mar 15, 2021 |
| ASRock        | 775Dual-VSTA                | Desktop     | [6f870bccf3](https://linux-hardware.org/?probe=6f870bccf3) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| ASUSTek       | P53E                        | Notebook    | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Toshiba       | Satellite A660              | Notebook    | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Lenovo        | S10-3                       | Notebook    | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3ed340b3ba](https://linux-hardware.org/?probe=3ed340b3ba) | Feb 28, 2021 |
| Dell          | 0RY007                      | Desktop     | [6172822ebb](https://linux-hardware.org/?probe=6172822ebb) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Itautec       | Infoway w7430               | Notebook    | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | Notebook    | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| Intel         | ChiefRiver                  | Desktop     | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9c1652cf08](https://linux-hardware.org/?probe=9c1652cf08) | Feb 10, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | Notebook    | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | Notebook    | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | Notebook    | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| Supermicro    | X8DA3                       | Server      | [039bf2c96a](https://linux-hardware.org/?probe=039bf2c96a) | Feb 04, 2021 |
| Supermicro    | X8DA3                       | Server      | [3731f93e51](https://linux-hardware.org/?probe=3731f93e51) | Feb 04, 2021 |
| HP            | 3048h                       | Desktop     | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | Notebook    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| HP            | Notebook                    | Notebook    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | Notebook    | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | Notebook    | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Lenovo        | ThinkCentre M58p 6136A66    | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Dell          | 0WG864                      | Desktop     | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | Notebook    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | Notebook    | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| ASUSTek       | K53SD                       | Notebook    | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | Notebook    | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Dell          | 0WG864                      | Desktop     | [de92f1f8e4](https://linux-hardware.org/?probe=de92f1f8e4) | Dec 11, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | Notebook    | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [ce0a64067a](https://linux-hardware.org/?probe=ce0a64067a) | Nov 29, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [d7ac62fba3](https://linux-hardware.org/?probe=d7ac62fba3) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | Desktop     | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| Panasonic     | CF-52PGNBE2M                | Notebook    | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [761ecd0a1c](https://linux-hardware.org/?probe=761ecd0a1c) | Nov 25, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| HP            | 2820h                       | Desktop     | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | Notebook    | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Pegatron      | Narra6                      | Desktop     | [7878c50c46](https://linux-hardware.org/?probe=7878c50c46) | Nov 20, 2020 |
| Positivo      | S14BW01                     | Notebook    | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| HP            | 09F8h                       | Desktop     | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| HP            | ProBook 4720s               | Notebook    | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | Notebook    | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| HP            | 0AA8h                       | Desktop     | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | Desktop     | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | Notebook    | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | Notebook    | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | Notebook    | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | Notebook    | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | Notebook    | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | Notebook    | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | Notebook    | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Dell          | 0J3C2F A02                  | Desktop     | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| Acer          | Extensa 4620                | Notebook    | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| ASRock        | G41M-GS3                    | Desktop     | [55872633b0](https://linux-hardware.org/?probe=55872633b0) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [ed8c0e270a](https://linux-hardware.org/?probe=ed8c0e270a) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [873e321107](https://linux-hardware.org/?probe=873e321107) | Oct 20, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c1a4649fc7](https://linux-hardware.org/?probe=c1a4649fc7) | Oct 20, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [003da597cd](https://linux-hardware.org/?probe=003da597cd) | Oct 19, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| Toshiba       | Satellite L840              | Notebook    | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | Notebook    | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | Notebook    | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | Notebook    | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | Notebook    | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| MSI           | H97M-E35                    | Desktop     | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion dv6                | Notebook    | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [53ecc0af0c](https://linux-hardware.org/?probe=53ecc0af0c) | Oct 07, 2020 |
| HP            | Unknown                     | Notebook    | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| MSI           | H110M ECO                   | Desktop     | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [9a5387bb3b](https://linux-hardware.org/?probe=9a5387bb3b) | Oct 04, 2020 |
| Dell          | Latitude D630               | Notebook    | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [a112988e2e](https://linux-hardware.org/?probe=a112988e2e) | Sep 28, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| Fujitsu       | FMVA05008                   | Notebook    | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| HP            | Pavilion x2 Detachable      | Tablet      | [5c305017e8](https://linux-hardware.org/?probe=5c305017e8) | Sep 13, 2020 |
| Acer          | Prespa M                    | Notebook    | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| ASRock        | A320M-DGS                   | Desktop     | [0ee0a67ae6](https://linux-hardware.org/?probe=0ee0a67ae6) | Sep 13, 2020 |
| Acer          | Prespa M                    | Notebook    | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| ASUSTek       | F7L                         | Notebook    | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | Notebook    | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | Notebook    | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [2cca042481](https://linux-hardware.org/?probe=2cca042481) | Sep 10, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [84a053df62](https://linux-hardware.org/?probe=84a053df62) | Sep 09, 2020 |
| Dell          | Latitude E5450              | Notebook    | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Google        | Gandof                      | Notebook    | [6b79edadc5](https://linux-hardware.org/?probe=6b79edadc5) | Sep 04, 2020 |
| Acer          | Aspire ES1-522              | Notebook    | [c5e6143bbd](https://linux-hardware.org/?probe=c5e6143bbd) | Sep 02, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [121fd4e00e](https://linux-hardware.org/?probe=121fd4e00e) | Aug 30, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [3a0e9bb81b](https://linux-hardware.org/?probe=3a0e9bb81b) | Aug 30, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [b5a228d9bf](https://linux-hardware.org/?probe=b5a228d9bf) | Aug 26, 2020 |
| Dell          | 0CU409                      | Desktop     | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| ASRock        | A320M-HD                    | Desktop     | [8e8b3d8d21](https://linux-hardware.org/?probe=8e8b3d8d21) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e95b44a1c2](https://linux-hardware.org/?probe=e95b44a1c2) | Aug 23, 2020 |
| ASUSTek       | K50C                        | Notebook    | [dd9986741e](https://linux-hardware.org/?probe=dd9986741e) | Aug 19, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [72e40559e9](https://linux-hardware.org/?probe=72e40559e9) | Aug 17, 2020 |
| Digibras      | NH4CU03                     | Notebook    | [3ba7006e38](https://linux-hardware.org/?probe=3ba7006e38) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [18e6bfd3b5](https://linux-hardware.org/?probe=18e6bfd3b5) | Aug 14, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [ca848be2f0](https://linux-hardware.org/?probe=ca848be2f0) | Aug 12, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [723c72f289](https://linux-hardware.org/?probe=723c72f289) | Aug 12, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [a8401cc827](https://linux-hardware.org/?probe=a8401cc827) | Aug 12, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| Lenovo        | ThinkCentre M58p 7220W21    | Desktop     | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
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
| Positivo      | H14BT58                     | Notebook    | [3cb433c2cc](https://linux-hardware.org/?probe=3cb433c2cc) | Jul 24, 2020 |
| ASUSTek       | 1015BX                      | Notebook    | [5f48c6c53b](https://linux-hardware.org/?probe=5f48c6c53b) | Jul 24, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [3d1f4e7cb8](https://linux-hardware.org/?probe=3d1f4e7cb8) | Jul 21, 2020 |
| IBM           | eServer x3105 -[434722J]... | Desktop     | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [ee73a556b1](https://linux-hardware.org/?probe=ee73a556b1) | Jul 19, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [33e46bd029](https://linux-hardware.org/?probe=33e46bd029) | Jul 19, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [09f9209cda](https://linux-hardware.org/?probe=09f9209cda) | Jul 18, 2020 |
| Dell          | Studio 1555                 | Notebook    | [0d511c045e](https://linux-hardware.org/?probe=0d511c045e) | Jul 16, 2020 |
| Dell          | Latitude D520               | Notebook    | [c41f563801](https://linux-hardware.org/?probe=c41f563801) | Jul 16, 2020 |
| ASUSTek       | Q302LA                      | Notebook    | [c453eada8f](https://linux-hardware.org/?probe=c453eada8f) | Jul 09, 2020 |
| HP            | Notebook                    | Notebook    | [10cadcd9b6](https://linux-hardware.org/?probe=10cadcd9b6) | Jul 09, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [9e35eb4bff](https://linux-hardware.org/?probe=9e35eb4bff) | Jul 08, 2020 |
| HP            | Pavilion 15                 | Notebook    | [9f54b2c875](https://linux-hardware.org/?probe=9f54b2c875) | Jul 06, 2020 |
| HP            | 3396                        | Desktop     | [820e05ee01](https://linux-hardware.org/?probe=820e05ee01) | Jul 03, 2020 |
| Acer          | Swift SF314-52G             | Notebook    | [8cd6b05831](https://linux-hardware.org/?probe=8cd6b05831) | Jul 03, 2020 |
| HP            | Pavilion dv6000 (RD870AV... | Notebook    | [921ea4c212](https://linux-hardware.org/?probe=921ea4c212) | Jul 03, 2020 |
| Acer          | Aspire ES1-331              | Notebook    | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [193cbfc862](https://linux-hardware.org/?probe=193cbfc862) | Jun 30, 2020 |
| HP            | Compaq 615                  | Notebook    | [38dc3f0f55](https://linux-hardware.org/?probe=38dc3f0f55) | Jun 29, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| HP            | Compaq 6710b (RM338UT#AB... | Notebook    | [997dd3289c](https://linux-hardware.org/?probe=997dd3289c) | Jun 25, 2020 |
| HP            | Compaq 615                  | Notebook    | [d24b727a5b](https://linux-hardware.org/?probe=d24b727a5b) | Jun 24, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [8d3308bf38](https://linux-hardware.org/?probe=8d3308bf38) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [93ced4c964](https://linux-hardware.org/?probe=93ced4c964) | Jun 18, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| MSI           | 0A48                        | Desktop     | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [a612626f7b](https://linux-hardware.org/?probe=a612626f7b) | Jun 16, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [5473d1a8e3](https://linux-hardware.org/?probe=5473d1a8e3) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [ad60c0409d](https://linux-hardware.org/?probe=ad60c0409d) | Jun 09, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [4400ee29ed](https://linux-hardware.org/?probe=4400ee29ed) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [d730ecdbd6](https://linux-hardware.org/?probe=d730ecdbd6) | Jun 08, 2020 |
| Acer          | Aspire 5734Z                | Notebook    | [6af54cea15](https://linux-hardware.org/?probe=6af54cea15) | Jun 07, 2020 |
| HP            | Pavilion 15                 | Notebook    | [131d6a40c2](https://linux-hardware.org/?probe=131d6a40c2) | Jun 03, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [ea9fb1590a](https://linux-hardware.org/?probe=ea9fb1590a) | Jun 03, 2020 |
| HUAWEI        | KPL-W0X                     | Notebook    | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| HP            | Pavilion dv5                | Notebook    | [41390482f3](https://linux-hardware.org/?probe=41390482f3) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [6e0b7c86d5](https://linux-hardware.org/?probe=6e0b7c86d5) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [9a4a664a94](https://linux-hardware.org/?probe=9a4a664a94) | May 30, 2020 |
| Positivo      | S14CT01                     | Notebook    | [027689152b](https://linux-hardware.org/?probe=027689152b) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [4a7ecd1578](https://linux-hardware.org/?probe=4a7ecd1578) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [51f3309bfb](https://linux-hardware.org/?probe=51f3309bfb) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [73d7cd6398](https://linux-hardware.org/?probe=73d7cd6398) | May 27, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [663bfb0664](https://linux-hardware.org/?probe=663bfb0664) | May 27, 2020 |
| Biostar       | GF7025-M2                   | Desktop     | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [0686c2c434](https://linux-hardware.org/?probe=0686c2c434) | May 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [78df8e8526](https://linux-hardware.org/?probe=78df8e8526) | May 21, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [4da7cc2128](https://linux-hardware.org/?probe=4da7cc2128) | May 21, 2020 |
| HP            | 21B4 A01                    | Desktop     | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a68c9e0a74](https://linux-hardware.org/?probe=a68c9e0a74) | May 18, 2020 |
| ASUSTek       | X201E                       | Notebook    | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| Packard Be... | EN Butterfly s              | Notebook    | [587286fd1b](https://linux-hardware.org/?probe=587286fd1b) | May 17, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | Desktop     | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [c0cf69cb37](https://linux-hardware.org/?probe=c0cf69cb37) | May 13, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [a8c07c11cb](https://linux-hardware.org/?probe=a8c07c11cb) | May 09, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [dd51c6c85e](https://linux-hardware.org/?probe=dd51c6c85e) | May 09, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [7ee061c41d](https://linux-hardware.org/?probe=7ee061c41d) | May 09, 2020 |
| Acer          | Aspire XC-703G              | Desktop     | [87c5ee1001](https://linux-hardware.org/?probe=87c5ee1001) | May 07, 2020 |
| HP            | Notebook                    | Notebook    | [0cab8a6d17](https://linux-hardware.org/?probe=0cab8a6d17) | May 07, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [baf1cb6830](https://linux-hardware.org/?probe=baf1cb6830) | May 06, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | Notebook    | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| HP            | 17E2                        | Mini pc     | [fe57173b3f](https://linux-hardware.org/?probe=fe57173b3f) | May 01, 2020 |
| Intel         | DN2800MT AAG23738-801       | Desktop     | [eba41acd95](https://linux-hardware.org/?probe=eba41acd95) | Apr 29, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [1a00b67e81](https://linux-hardware.org/?probe=1a00b67e81) | Apr 27, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [74edb3ce25](https://linux-hardware.org/?probe=74edb3ce25) | Apr 26, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [734c5c160a](https://linux-hardware.org/?probe=734c5c160a) | Apr 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 32        | 7.69%   |
| 5.4.0-52-generic  | 22        | 5.29%   |
| 5.4.0-48-generic  | 13        | 3.13%   |
| 5.4.0-47-generic  | 12        | 2.88%   |
| 5.4.0-26-generic  | 12        | 2.88%   |
| 5.4.0-40-generic  | 11        | 2.64%   |
| 5.13.0-28-generic | 11        | 2.64%   |
| 5.11.0-27-generic | 11        | 2.64%   |
| 5.4.0-54-generic  | 10        | 2.4%    |
| 5.4.0-29-generic  | 10        | 2.4%    |
| 5.4.0-33-generic  | 9         | 2.16%   |
| 5.8.0-50-generic  | 8         | 1.92%   |
| 5.4.0-65-generic  | 8         | 1.92%   |
| 5.11.0-38-generic | 8         | 1.92%   |
| 5.4.0-37-generic  | 7         | 1.68%   |
| 5.13.0-40-generic | 7         | 1.68%   |
| 5.13.0-30-generic | 7         | 1.68%   |
| 5.8.0-53-generic  | 6         | 1.44%   |
| 5.8.0-41-generic  | 6         | 1.44%   |
| 5.4.0-73-generic  | 6         | 1.44%   |
| 5.4.0-72-generic  | 6         | 1.44%   |
| 5.4.0-67-generic  | 6         | 1.44%   |
| 5.11.0-43-generic | 6         | 1.44%   |
| 5.8.0-55-generic  | 5         | 1.2%    |
| 5.8.0-45-generic  | 5         | 1.2%    |
| 5.4.0-89-generic  | 5         | 1.2%    |
| 5.4.0-60-generic  | 5         | 1.2%    |
| 5.4.0-59-generic  | 5         | 1.2%    |
| 5.4.0-58-generic  | 5         | 1.2%    |
| 5.4.0-51-generic  | 5         | 1.2%    |
| 5.11.0-37-generic | 5         | 1.2%    |
| 5.8.0-63-generic  | 4         | 0.96%   |
| 5.8.0-59-generic  | 4         | 0.96%   |
| 5.4.0-91-generic  | 4         | 0.96%   |
| 5.4.0-77-generic  | 4         | 0.96%   |
| 5.4.0-66-generic  | 4         | 0.96%   |
| 5.4.0-56-generic  | 4         | 0.96%   |
| 5.4.0-45-generic  | 4         | 0.96%   |
| 5.4.0-31-generic  | 4         | 0.96%   |
| 5.13.0-27-generic | 4         | 0.96%   |
| 5.11.0-41-generic | 4         | 0.96%   |
| 5.8.0-49-generic  | 3         | 0.72%   |
| 5.8.0-48-generic  | 3         | 0.72%   |
| 5.8.0-43-generic  | 3         | 0.72%   |
| 5.4.0-96-generic  | 3         | 0.72%   |
| 5.4.0-81-generic  | 3         | 0.72%   |
| 5.4.0-74-generic  | 3         | 0.72%   |
| 5.4.0-62-generic  | 3         | 0.72%   |
| 5.4.0-113-generic | 3         | 0.72%   |
| 5.4.0-107-generic | 3         | 0.72%   |
| 5.13.0-35-generic | 3         | 0.72%   |
| 5.11.0-40-generic | 3         | 0.72%   |
| 5.11.0-34-generic | 3         | 0.72%   |
| 5.11.0-25-generic | 3         | 0.72%   |
| 5.4.0-90-generic  | 2         | 0.48%   |
| 5.4.0-80-generic  | 2         | 0.48%   |
| 5.4.0-70-generic  | 2         | 0.48%   |
| 5.4.0-64-generic  | 2         | 0.48%   |
| 5.4.0-53-generic  | 2         | 0.48%   |
| 5.4.0-39-generic  | 2         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 240       | 61.7%   |
| 5.8.0   | 51        | 13.11%  |
| 5.11.0  | 47        | 12.08%  |
| 5.13.0  | 39        | 10.03%  |
| 5.6.0   | 2         | 0.51%   |
| 5.9.0   | 1         | 0.26%   |
| 5.7.9   | 1         | 0.26%   |
| 5.6.15  | 1         | 0.26%   |
| 5.5.2   | 1         | 0.26%   |
| 5.4.30  | 1         | 0.26%   |
| 5.3.18  | 1         | 0.26%   |
| 5.16.5  | 1         | 0.26%   |
| 5.15.0  | 1         | 0.26%   |
| 5.14.0  | 1         | 0.26%   |
| 5.10.0  | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 241       | 61.95%  |
| 5.8     | 51        | 13.11%  |
| 5.11    | 47        | 12.08%  |
| 5.13    | 39        | 10.03%  |
| 5.6     | 3         | 0.77%   |
| 5.9     | 1         | 0.26%   |
| 5.7     | 1         | 0.26%   |
| 5.5     | 1         | 0.26%   |
| 5.3     | 1         | 0.26%   |
| 5.16    | 1         | 0.26%   |
| 5.15    | 1         | 0.26%   |
| 5.14    | 1         | 0.26%   |
| 5.10    | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 383       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 364       | 94.55%  |
| LXDE       | 8         | 2.08%   |
| GNOME      | 5         | 1.3%    |
| Cinnamon   | 2         | 0.52%   |
| XFCE       | 1         | 0.26%   |
| X-Cinnamon | 1         | 0.26%   |
| MATE       | 1         | 0.26%   |
| KDE5       | 1         | 0.26%   |
| KDE        | 1         | 0.26%   |
| i3         | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 363       | 94.53%  |
| Tty     | 18        | 4.69%   |
| Wayland | 2         | 0.52%   |
| Unknown | 1         | 0.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 203       | 52.05%  |
| Unknown | 124       | 31.79%  |
| GDM     | 24        | 6.15%   |
| LightDM | 18        | 4.62%   |
| TDM     | 17        | 4.36%   |
| GDM3    | 3         | 0.77%   |
| LXDM    | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 118       | 30.81%  |
| fr_FR   | 47        | 12.27%  |
| pt_BR   | 33        | 8.62%   |
| de_DE   | 23        | 6.01%   |
| it_IT   | 21        | 5.48%   |
| en_GB   | 18        | 4.7%    |
| C       | 18        | 4.7%    |
| ru_RU   | 13        | 3.39%   |
| es_ES   | 9         | 2.35%   |
| en_AU   | 9         | 2.35%   |
| pl_PL   | 6         | 1.57%   |
| ja_JP   | 5         | 1.31%   |
| hu_HU   | 4         | 1.04%   |
| es_MX   | 4         | 1.04%   |
| en_CA   | 4         | 1.04%   |
| nl_NL   | 3         | 0.78%   |
| fr_CH   | 3         | 0.78%   |
| es_AR   | 3         | 0.78%   |
| en_ZA   | 3         | 0.78%   |
| en_IE   | 3         | 0.78%   |
| cs_CZ   | 3         | 0.78%   |
| fr_BE   | 2         | 0.52%   |
| fi_FI   | 2         | 0.52%   |
| es_CR   | 2         | 0.52%   |
| es_CL   | 2         | 0.52%   |
| en_SG   | 2         | 0.52%   |
| en_NZ   | 2         | 0.52%   |
| en_IN   | 2         | 0.52%   |
| el_GR   | 2         | 0.52%   |
| de_CH   | 2         | 0.52%   |
| Unknown | 2         | 0.52%   |
| tr_TR   | 1         | 0.26%   |
| sv_SE   | 1         | 0.26%   |
| ru_UA   | 1         | 0.26%   |
| pt_PT   | 1         | 0.26%   |
| nl_BE   | 1         | 0.26%   |
| lt_LT   | 1         | 0.26%   |
| fr_CA   | 1         | 0.26%   |
| es_UY   | 1         | 0.26%   |
| es_PE   | 1         | 0.26%   |
| es_CO   | 1         | 0.26%   |
| en_PH   | 1         | 0.26%   |
| en_DE   | 1         | 0.26%   |
| de_AT   | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 222       | 57.96%  |
| EFI  | 161       | 42.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 353       | 92.17%  |
| Overlay | 19        | 4.96%   |
| Btrfs   | 6         | 1.57%   |
| Xfs     | 2         | 0.52%   |
| F2fs    | 1         | 0.26%   |
| Ext2    | 1         | 0.26%   |
| Aufs    | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 153       | 39.53%  |
| GPT     | 128       | 33.07%  |
| MBR     | 106       | 27.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 340       | 88.31%  |
| Yes       | 45        | 11.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 278       | 72.02%  |
| Yes       | 108       | 27.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 68        | 17.75%  |
| Dell                        | 50        | 13.05%  |
| Lenovo                      | 49        | 12.79%  |
| ASUSTek Computer            | 44        | 11.49%  |
| Acer                        | 21        | 5.48%   |
| MSI                         | 18        | 4.7%    |
| Gigabyte Technology         | 15        | 3.92%   |
| Toshiba                     | 13        | 3.39%   |
| ASRock                      | 13        | 3.39%   |
| Samsung Electronics         | 10        | 2.61%   |
| Intel                       | 8         | 2.09%   |
| Positivo                    | 7         | 1.83%   |
| Notebook                    | 5         | 1.31%   |
| Apple                       | 5         | 1.31%   |
| Sony                        | 4         | 1.04%   |
| Pegatron                    | 4         | 1.04%   |
| Packard Bell                | 4         | 1.04%   |
| Google                      | 4         | 1.04%   |
| Fujitsu                     | 4         | 1.04%   |
| AAEON                       | 3         | 0.78%   |
| ZOTAC                       | 2         | 0.52%   |
| YASHI                       | 2         | 0.52%   |
| Foxconn                     | 2         | 0.52%   |
| Biostar                     | 2         | 0.52%   |
| AMI                         | 2         | 0.52%   |
| Unknown                     | 2         | 0.52%   |
| UNOWHY                      | 1         | 0.26%   |
| Timi                        | 1         | 0.26%   |
| Supermicro                  | 1         | 0.26%   |
| Prestigio                   | 1         | 0.26%   |
| Panasonic                   | 1         | 0.26%   |
| Mediacom                    | 1         | 0.26%   |
| Lanix                       | 1         | 0.26%   |
| LAMINA                      | 1         | 0.26%   |
| Itautec                     | 1         | 0.26%   |
| IBM                         | 1         | 0.26%   |
| I-Life Digital Technologies | 1         | 0.26%   |
| Hungaro Flotta Kft          | 1         | 0.26%   |
| HUAWEI                      | 1         | 0.26%   |
| Huanan                      | 1         | 0.26%   |
| Hardkernel                  | 1         | 0.26%   |
| Haier                       | 1         | 0.26%   |
| GTZS                        | 1         | 0.26%   |
| Gateway                     | 1         | 0.26%   |
| Fujitsu Siemens             | 1         | 0.26%   |
| Dixonsxp                    | 1         | 0.26%   |
| Digibras                    | 1         | 0.26%   |
| Alienware                   | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| HP Notebook                     | 5         | 1.31%   |
| Unknown                         | 5         | 1.31%   |
| HP Pavilion dv6                 | 3         | 0.78%   |
| Dell Latitude D630              | 3         | 0.78%   |
| AAEON MF-001                    | 3         | 0.78%   |
| YASHI MYBOOK 360                | 2         | 0.52%   |
| Positivo H14BT58                | 2         | 0.52%   |
| MSI MS-7C37                     | 2         | 0.52%   |
| MSI MS-7B89                     | 2         | 0.52%   |
| Lenovo IdeaPad 320-15AST 80XV   | 2         | 0.52%   |
| HP ProBook 440 G8 Notebook PC   | 2         | 0.52%   |
| HP ProBook 440 G7               | 2         | 0.52%   |
| HP Pavilion x2 Detachable       | 2         | 0.52%   |
| HP Pavilion g7                  | 2         | 0.52%   |
| HP Compaq 6000 Pro SFF PC       | 2         | 0.52%   |
| Dell OptiPlex 790               | 2         | 0.52%   |
| Dell Inspiron 15-3567           | 2         | 0.52%   |
| ASUS 1015BX                     | 2         | 0.52%   |
| ASRock N68-VS3 UCC              | 2         | 0.52%   |
| ASRock FM2A85X Extreme6         | 2         | 0.52%   |
| Apple MacBookPro8,1             | 2         | 0.52%   |
| ZOTAC ZBOX-CI323NANO            | 1         | 0.26%   |
| ZOTAC NM10                      | 1         | 0.26%   |
| UNOWHY Y13G010S4EI              | 1         | 0.26%   |
| Toshiba Satellite S55-B         | 1         | 0.26%   |
| Toshiba Satellite Pro U400      | 1         | 0.26%   |
| Toshiba Satellite L840          | 1         | 0.26%   |
| Toshiba Satellite L70-B         | 1         | 0.26%   |
| Toshiba Satellite L305          | 1         | 0.26%   |
| Toshiba Satellite C875          | 1         | 0.26%   |
| Toshiba Satellite C855D         | 1         | 0.26%   |
| Toshiba Satellite C70D-B        | 1         | 0.26%   |
| Toshiba Satellite C670D-12N     | 1         | 0.26%   |
| Toshiba Satellite C55D-A        | 1         | 0.26%   |
| Toshiba Satellite A660          | 1         | 0.26%   |
| Toshiba Satellite A205          | 1         | 0.26%   |
| Toshiba NB510                   | 1         | 0.26%   |
| Timi TM1612                     | 1         | 0.26%   |
| Supermicro X8DA3                | 1         | 0.26%   |
| Sony VPCSB1V9E                  | 1         | 0.26%   |
| Sony VPCEJ1E1E                  | 1         | 0.26%   |
| Sony VGN-SZ670AN                | 1         | 0.26%   |
| Sony VGN-CR11Z_R                | 1         | 0.26%   |
| Samsung RV415/RV515             | 1         | 0.26%   |
| Samsung RV410/RV510/S3510/E3510 | 1         | 0.26%   |
| Samsung RV408/RV508             | 1         | 0.26%   |
| Samsung RC512                   | 1         | 0.26%   |
| Samsung R530/R730/P530          | 1         | 0.26%   |
| Samsung R520/R522/R620          | 1         | 0.26%   |
| Samsung R40/R41                 | 1         | 0.26%   |
| Samsung N100SP                  | 1         | 0.26%   |
| Samsung 300E4M/300E4S/300E4L    | 1         | 0.26%   |
| Samsung 275E4E/275E5E           | 1         | 0.26%   |
| Prestigio PSB141C01BFH          | 1         | 0.26%   |
| Positivo S14CT01                | 1         | 0.26%   |
| Positivo S14BW01                | 1         | 0.26%   |
| Positivo POS-MI945AA            | 1         | 0.26%   |
| Positivo POS-EIH61CE            | 1         | 0.26%   |
| Positivo N600                   | 1         | 0.26%   |
| Pegatron WE216AA-ABF CQ5335FR   | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 18        | 4.7%    |
| Acer Aspire            | 17        | 4.44%   |
| Lenovo ThinkPad        | 16        | 4.18%   |
| Lenovo IdeaPad         | 15        | 3.92%   |
| HP Pavilion            | 13        | 3.39%   |
| HP Compaq              | 13        | 3.39%   |
| Toshiba Satellite      | 12        | 3.13%   |
| HP ProBook             | 12        | 3.13%   |
| Dell Latitude          | 8         | 2.09%   |
| Dell OptiPlex          | 6         | 1.57%   |
| Lenovo ThinkCentre     | 5         | 1.31%   |
| HP Notebook            | 5         | 1.31%   |
| ASUS VivoBook          | 5         | 1.31%   |
| Unknown                | 5         | 1.31%   |
| HP EliteBook           | 4         | 1.04%   |
| Dell XPS               | 4         | 1.04%   |
| Dell Vostro            | 4         | 1.04%   |
| Dell PowerEdge         | 3         | 0.78%   |
| AAEON MF-001           | 3         | 0.78%   |
| YASHI MYBOOK           | 2         | 0.52%   |
| Positivo H14BT58       | 2         | 0.52%   |
| Packard Bell EasyNote  | 2         | 0.52%   |
| Notebook W54           | 2         | 0.52%   |
| MSI MS-7C37            | 2         | 0.52%   |
| MSI MS-7B89            | 2         | 0.52%   |
| HP t620                | 2         | 0.52%   |
| HP Spectre             | 2         | 0.52%   |
| HP Presario            | 2         | 0.52%   |
| Gigabyte B450M         | 2         | 0.52%   |
| Dell Studio            | 2         | 0.52%   |
| ASUS 1015BX            | 2         | 0.52%   |
| ASRock N68-VS3         | 2         | 0.52%   |
| ASRock FM2A85X         | 2         | 0.52%   |
| Apple MacBookPro8      | 2         | 0.52%   |
| ZOTAC ZBOX-CI323NANO   | 1         | 0.26%   |
| ZOTAC NM10             | 1         | 0.26%   |
| UNOWHY Y13G010S4EI     | 1         | 0.26%   |
| Toshiba NB510          | 1         | 0.26%   |
| Timi TM1612            | 1         | 0.26%   |
| Supermicro X8DA3       | 1         | 0.26%   |
| Sony VPCSB1V9E         | 1         | 0.26%   |
| Sony VPCEJ1E1E         | 1         | 0.26%   |
| Sony VGN-SZ670AN       | 1         | 0.26%   |
| Sony VGN-CR11Z         | 1         | 0.26%   |
| Samsung RV415          | 1         | 0.26%   |
| Samsung RV410          | 1         | 0.26%   |
| Samsung RV408          | 1         | 0.26%   |
| Samsung RC512          | 1         | 0.26%   |
| Samsung R530           | 1         | 0.26%   |
| Samsung R520           | 1         | 0.26%   |
| Samsung R40            | 1         | 0.26%   |
| Samsung N100SP         | 1         | 0.26%   |
| Samsung 300E4M         | 1         | 0.26%   |
| Samsung 275E4E         | 1         | 0.26%   |
| Prestigio PSB141C01BFH | 1         | 0.26%   |
| Positivo S14CT01       | 1         | 0.26%   |
| Positivo S14BW01       | 1         | 0.26%   |
| Positivo POS-MI945AA   | 1         | 0.26%   |
| Positivo POS-EIH61CE   | 1         | 0.26%   |
| Positivo N600          | 1         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 33        | 8.62%   |
| 2019 | 32        | 8.36%   |
| 2011 | 30        | 7.83%   |
| 2014 | 28        | 7.31%   |
| 2008 | 28        | 7.31%   |
| 2013 | 27        | 7.05%   |
| 2010 | 26        | 6.79%   |
| 2009 | 24        | 6.27%   |
| 2007 | 24        | 6.27%   |
| 2017 | 23        | 6.01%   |
| 2016 | 23        | 6.01%   |
| 2020 | 22        | 5.74%   |
| 2015 | 20        | 5.22%   |
| 2018 | 17        | 4.44%   |
| 2006 | 11        | 2.87%   |
| 2021 | 10        | 2.61%   |
| 2005 | 4         | 1.04%   |
| 2004 | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 233       | 60.84%  |
| Desktop     | 132       | 34.46%  |
| Convertible | 5         | 1.31%   |
| Mini pc     | 5         | 1.31%   |
| Server      | 5         | 1.31%   |
| All in one  | 2         | 0.52%   |
| Tablet      | 1         | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 358       | 93.23%  |
| Enabled  | 26        | 6.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 378       | 98.69%  |
| Yes  | 5         | 1.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 120       | 31.09%  |
| 4.01-8.0        | 78        | 20.21%  |
| 1.01-2.0        | 63        | 16.32%  |
| 8.01-16.0       | 51        | 13.21%  |
| 16.01-24.0      | 38        | 9.84%   |
| 32.01-64.0      | 14        | 3.63%   |
| 2.01-3.0        | 10        | 2.59%   |
| 24.01-32.0      | 4         | 1.04%   |
| 64.01-256.0     | 3         | 0.78%   |
| 0.51-1.0        | 3         | 0.78%   |
| More than 256.0 | 2         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 202       | 49.75%  |
| 0.51-1.0   | 70        | 17.24%  |
| 2.01-3.0   | 59        | 14.53%  |
| 4.01-8.0   | 39        | 9.61%   |
| 3.01-4.0   | 22        | 5.42%   |
| 0.01-0.5   | 9         | 2.22%   |
| 8.01-16.0  | 4         | 0.99%   |
| 16.01-24.0 | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 254       | 65.63%  |
| 2      | 96        | 24.81%  |
| 4      | 13        | 3.36%   |
| 3      | 12        | 3.1%    |
| 5      | 6         | 1.55%   |
| 7      | 2         | 0.52%   |
| 0      | 2         | 0.52%   |
| 14     | 1         | 0.26%   |
| 6      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 52.85%  |
| No        | 182       | 47.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 341       | 88.8%   |
| No        | 43        | 11.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 285       | 74.41%  |
| No        | 98        | 25.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 214       | 55.15%  |
| Yes       | 174       | 44.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 61        | 15.84%  |
| France       | 50        | 12.99%  |
| Brazil       | 39        | 10.13%  |
| Italy        | 30        | 7.79%   |
| Germany      | 29        | 7.53%   |
| Russia       | 18        | 4.68%   |
| UK           | 11        | 2.86%   |
| Spain        | 11        | 2.86%   |
| Australia    | 10        | 2.6%    |
| Switzerland  | 9         | 2.34%   |
| Poland       | 8         | 2.08%   |
| Netherlands  | 8         | 2.08%   |
| Hungary      | 7         | 1.82%   |
| Mexico       | 6         | 1.56%   |
| Finland      | 6         | 1.56%   |
| Japan        | 5         | 1.3%    |
| Czechia      | 5         | 1.3%    |
| Canada       | 5         | 1.3%    |
| Belgium      | 5         | 1.3%    |
| Ukraine      | 4         | 1.04%   |
| South Africa | 4         | 1.04%   |
| Romania      | 3         | 0.78%   |
| New Zealand  | 3         | 0.78%   |
| Ireland      | 3         | 0.78%   |
| Greece       | 3         | 0.78%   |
| Argentina    | 3         | 0.78%   |
| Slovenia     | 2         | 0.52%   |
| Singapore    | 2         | 0.52%   |
| Puerto Rico  | 2         | 0.52%   |
| Indonesia    | 2         | 0.52%   |
| India        | 2         | 0.52%   |
| Costa Rica   | 2         | 0.52%   |
| Colombia     | 2         | 0.52%   |
| Chile        | 2         | 0.52%   |
| Vietnam      | 1         | 0.26%   |
| Uruguay      | 1         | 0.26%   |
| Turkey       | 1         | 0.26%   |
| Tunisia      | 1         | 0.26%   |
| Sweden       | 1         | 0.26%   |
| Slovakia     | 1         | 0.26%   |
| Serbia       | 1         | 0.26%   |
| Portugal     | 1         | 0.26%   |
| Philippines  | 1         | 0.26%   |
| Peru         | 1         | 0.26%   |
| Norway       | 1         | 0.26%   |
| Malaysia     | 1         | 0.26%   |
| Luxembourg   | 1         | 0.26%   |
| Lithuania    | 1         | 0.26%   |
| Lebanon      | 1         | 0.26%   |
| Israel       | 1         | 0.26%   |
| Iran         | 1         | 0.26%   |
| Honduras     | 1         | 0.26%   |
| Ecuador      | 1         | 0.26%   |
| Bulgaria     | 1         | 0.26%   |
| Belarus      | 1         | 0.26%   |
| Azerbaijan   | 1         | 0.26%   |
| Austria      | 1         | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Rome                   | 6         | 1.52%   |
| Paris                  | 6         | 1.52%   |
| Milan                  | 5         | 1.26%   |
| Melbourne              | 5         | 1.26%   |
| Helsinki               | 4         | 1.01%   |
| Wellington             | 3         | 0.76%   |
| Salvador               | 3         | 0.76%   |
| Pécs                  | 3         | 0.76%   |
| Munich                 | 3         | 0.76%   |
| Moscow                 | 3         | 0.76%   |
| Mexico City            | 3         | 0.76%   |
| Florence               | 3         | 0.76%   |
| Derry                  | 3         | 0.76%   |
| Zurich                 | 2         | 0.51%   |
| Yekaterinburg          | 2         | 0.51%   |
| Vicosa                 | 2         | 0.51%   |
| Stuttgart              | 2         | 0.51%   |
| Southampton            | 2         | 0.51%   |
| Sao Paulo              | 2         | 0.51%   |
| Poznan                 | 2         | 0.51%   |
| Porto Alegre           | 2         | 0.51%   |
| Oradea                 | 2         | 0.51%   |
| Omsk                   | 2         | 0.51%   |
| Mount Vernon           | 2         | 0.51%   |
| Krakow                 | 2         | 0.51%   |
| Jurong West            | 2         | 0.51%   |
| Houston                | 2         | 0.51%   |
| Heredia                | 2         | 0.51%   |
| Hamburg                | 2         | 0.51%   |
| Fortaleza              | 2         | 0.51%   |
| Curitiba               | 2         | 0.51%   |
| Cuernavaca             | 2         | 0.51%   |
| Cayey                  | 2         | 0.51%   |
| Cape Town              | 2         | 0.51%   |
| Budapest               | 2         | 0.51%   |
| Brooklyn               | 2         | 0.51%   |
| Brasília              | 2         | 0.51%   |
| Bern                   | 2         | 0.51%   |
| Berlin                 | 2         | 0.51%   |
| Athens                 | 2         | 0.51%   |
| Zwevegem               | 1         | 0.25%   |
| Zwanenburg             | 1         | 0.25%   |
| Wraysbury              | 1         | 0.25%   |
| Winsen                 | 1         | 0.25%   |
| Winchester             | 1         | 0.25%   |
| Williamsburg           | 1         | 0.25%   |
| Wiesbaden              | 1         | 0.25%   |
| West Chester           | 1         | 0.25%   |
| Warrington             | 1         | 0.25%   |
| Wadsworth              | 1         | 0.25%   |
| Wadi Maliz             | 1         | 0.25%   |
| Vladivostok            | 1         | 0.25%   |
| Vinhedo                | 1         | 0.25%   |
| Vilyuchinsk            | 1         | 0.25%   |
| Villeneuve-d'Ascq      | 1         | 0.25%   |
| Villejuif              | 1         | 0.25%   |
| Villars                | 1         | 0.25%   |
| Villandry              | 1         | 0.25%   |
| Villamuriel de Cerrato | 1         | 0.25%   |
| Villabon               | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 100       | 129    | 20%     |
| WDC                 | 89        | 127    | 17.8%   |
| Samsung Electronics | 52        | 71     | 10.4%   |
| Toshiba             | 35        | 37     | 7%      |
| Unknown             | 33        | 39     | 6.6%    |
| Hitachi             | 30        | 37     | 6%      |
| Kingston            | 21        | 22     | 4.2%    |
| Crucial             | 19        | 20     | 3.8%    |
| SanDisk             | 13        | 17     | 2.6%    |
| Intel               | 9         | 10     | 1.8%    |
| China               | 8         | 8      | 1.6%    |
| SK hynix            | 7         | 7      | 1.4%    |
| HGST                | 7         | 9      | 1.4%    |
| Fujitsu             | 7         | 7      | 1.4%    |
| A-DATA Technology   | 7         | 8      | 1.4%    |
| PNY                 | 4         | 4      | 0.8%    |
| Maxtor              | 4         | 4      | 0.8%    |
| Apacer              | 4         | 4      | 0.8%    |
| Micron Technology   | 3         | 3      | 0.6%    |
| LITEONIT            | 3         | 3      | 0.6%    |
| LDLC                | 3         | 3      | 0.6%    |
| KIOXIA              | 3         | 3      | 0.6%    |
| JMicron Technology  | 3         | 3      | 0.6%    |
| USB                 | 2         | 2      | 0.4%    |
| Transcend           | 2         | 2      | 0.4%    |
| Team                | 2         | 2      | 0.4%    |
| OCZ                 | 2         | 2      | 0.4%    |
| Corsair             | 2         | 2      | 0.4%    |
| Unknown             | 2         | 3      | 0.4%    |
| TO Exter            | 1         | 1      | 0.2%    |
| TCSUNBOW            | 1         | 1      | 0.2%    |
| SPCC                | 1         | 1      | 0.2%    |
| PNY USB             | 1         | 1      | 0.2%    |
| Phison Electronics  | 1         | 1      | 0.2%    |
| Patriot             | 1         | 1      | 0.2%    |
| ORTIAL              | 1         | 1      | 0.2%    |
| Londisk             | 1         | 1      | 0.2%    |
| LITEON              | 1         | 2      | 0.2%    |
| Lexar               | 1         | 1      | 0.2%    |
| Leven               | 1         | 2      | 0.2%    |
| LaCie               | 1         | 2      | 0.2%    |
| KingFast            | 1         | 1      | 0.2%    |
| KingDian            | 1         | 1      | 0.2%    |
| Intenso             | 1         | 1      | 0.2%    |
| Integral            | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 4      | 0.2%    |
| Goodram             | 1         | 1      | 0.2%    |
| Gigabyte Technology | 1         | 1      | 0.2%    |
| General             | 1         | 1      | 0.2%    |
| External            | 1         | 1      | 0.2%    |
| EMTEC               | 1         | 1      | 0.2%    |
| Dell                | 1         | 1      | 0.2%    |
| Apple               | 1         | 3      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 8         | 1.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB  | 7         | 1.31%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 1.12%   |
| Toshiba MQ01ABF050 500GB             | 5         | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 0.93%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.75%   |
| Seagate ST500LT012-1DG142 500GB      | 4         | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 0.75%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.75%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.75%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.75%   |
| A-DATA SU650 240GB SSD               | 4         | 0.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3         | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.56%   |
| Unknown SD/MMC/MS PRO 128GB          | 3         | 0.56%   |
| Seagate ST9500325AS 500GB            | 3         | 0.56%   |
| Seagate Backup+ Hub BK 8TB           | 3         | 0.56%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.56%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 0.56%   |
| WDC WD800JD-60LSA5 80GB              | 2         | 0.37%   |
| WDC WD7500BPVX-55JC3T3 752GB         | 2         | 0.37%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.37%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 0.37%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.37%   |
| WDC WD2500AAJS-75M0A0 249GB          | 2         | 0.37%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 0.37%   |
| WDC WD10EZEX-00WN4A0 1TB             | 2         | 0.37%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 2         | 0.37%   |
| USB 3.0 2TB                          | 2         | 0.37%   |
| Unknown MMC Card  64GB               | 2         | 0.37%   |
| Unknown MMC Card  16GB               | 2         | 0.37%   |
| Unknown MMC Card  128GB              | 2         | 0.37%   |
| Unknown M52516  16GB                 | 2         | 0.37%   |
| Unknown DA4064  64GB                 | 2         | 0.37%   |
| Unknown 128G32  128GB                | 2         | 0.37%   |
| Toshiba THNSFJ256GDNU A 256GB SSD    | 2         | 0.37%   |
| Toshiba MQ01ABD050 500GB             | 2         | 0.37%   |
| Seagate ST9250410AS 250GB            | 2         | 0.37%   |
| Seagate ST9160412AS 160GB            | 2         | 0.37%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 2         | 0.37%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.37%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.37%   |
| Seagate ST380815AS 80GB              | 2         | 0.37%   |
| Seagate ST3500418AS 500GB            | 2         | 0.37%   |
| Seagate ST3360320AS 360GB            | 2         | 0.37%   |
| Seagate ST3250410AS 250GB            | 2         | 0.37%   |
| Seagate ST3250310AS 250GB            | 2         | 0.37%   |
| Seagate ST320LT007-9ZV142 320GB      | 2         | 0.37%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 2         | 0.37%   |
| Seagate ST31000528AS 1TB             | 2         | 0.37%   |
| Seagate ST31000524AS 1TB             | 2         | 0.37%   |
| Seagate ST3000DM008-2DM166 3TB       | 2         | 0.37%   |
| Seagate ST2000LX001-1RG174 2TB       | 2         | 0.37%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.37%   |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB       | 2         | 0.37%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.37%   |
| Seagate ST1000DM003-9YN162 1TB       | 2         | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.37%   |
| SanDisk NVMe SSD Drive 512GB         | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 100       | 129    | 35.97%  |
| WDC                 | 76        | 109    | 27.34%  |
| Hitachi             | 30        | 37     | 10.79%  |
| Toshiba             | 28        | 30     | 10.07%  |
| Samsung Electronics | 20        | 24     | 7.19%   |
| HGST                | 7         | 9      | 2.52%   |
| Fujitsu             | 7         | 7      | 2.52%   |
| Unknown             | 3         | 3      | 1.08%   |
| Maxtor              | 3         | 3      | 1.08%   |
| USB                 | 2         | 2      | 0.72%   |
| LaCie               | 1         | 1      | 0.36%   |
| JMicron Technology  | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 29     | 16.11%  |
| Crucial             | 19        | 20     | 12.75%  |
| Kingston            | 18        | 18     | 12.08%  |
| WDC                 | 12        | 15     | 8.05%   |
| SanDisk             | 9         | 13     | 6.04%   |
| China               | 8         | 8      | 5.37%   |
| Intel               | 7         | 8      | 4.7%    |
| A-DATA Technology   | 5         | 6      | 3.36%   |
| Toshiba             | 4         | 4      | 2.68%   |
| PNY                 | 4         | 4      | 2.68%   |
| Apacer              | 4         | 4      | 2.68%   |
| LITEONIT            | 3         | 3      | 2.01%   |
| Transcend           | 2         | 2      | 1.34%   |
| Team                | 2         | 2      | 1.34%   |
| SK hynix            | 2         | 2      | 1.34%   |
| OCZ                 | 2         | 2      | 1.34%   |
| LDLC                | 2         | 2      | 1.34%   |
| Corsair             | 2         | 2      | 1.34%   |
| Unknown             | 1         | 1      | 0.67%   |
| TO Exter            | 1         | 1      | 0.67%   |
| TCSUNBOW            | 1         | 1      | 0.67%   |
| SPCC                | 1         | 1      | 0.67%   |
| PNY USB             | 1         | 1      | 0.67%   |
| Patriot             | 1         | 1      | 0.67%   |
| ORTIAL              | 1         | 1      | 0.67%   |
| Micron Technology   | 1         | 1      | 0.67%   |
| Maxtor              | 1         | 1      | 0.67%   |
| Londisk             | 1         | 1      | 0.67%   |
| LITEON              | 1         | 2      | 0.67%   |
| Lexar               | 1         | 1      | 0.67%   |
| Leven               | 1         | 2      | 0.67%   |
| KingDian            | 1         | 1      | 0.67%   |
| Intenso             | 1         | 1      | 0.67%   |
| Integral            | 1         | 1      | 0.67%   |
| Hewlett-Packard     | 1         | 4      | 0.67%   |
| Goodram             | 1         | 1      | 0.67%   |
| Dell                | 1         | 1      | 0.67%   |
| Apple               | 1         | 3      | 0.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 242       | 355    | 52.72%  |
| SSD     | 142       | 171    | 30.94%  |
| NVMe    | 36        | 47     | 7.84%   |
| MMC     | 33        | 41     | 7.19%   |
| Unknown | 6         | 6      | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 328       | 505    | 78.85%  |
| NVMe | 35        | 46     | 8.41%   |
| MMC  | 33        | 41     | 7.93%   |
| SAS  | 20        | 28     | 4.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 264       | 353    | 68.39%  |
| 0.51-1.0   | 89        | 124    | 23.06%  |
| 1.01-2.0   | 20        | 26     | 5.18%   |
| 3.01-4.0   | 5         | 13     | 1.3%    |
| 2.01-3.0   | 5         | 6      | 1.3%    |
| 4.01-10.0  | 3         | 4      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 103       | 26.41%  |
| 251-500        | 99        | 25.38%  |
| 501-1000       | 47        | 12.05%  |
| 51-100         | 35        | 8.97%   |
| 1-20           | 28        | 7.18%   |
| 1001-2000      | 25        | 6.41%   |
| 21-50          | 22        | 5.64%   |
| More than 3000 | 20        | 5.13%   |
| 2001-3000      | 9         | 2.31%   |
| Unknown        | 2         | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 177       | 44.58%  |
| 21-50          | 67        | 16.88%  |
| 101-250        | 49        | 12.34%  |
| 51-100         | 32        | 8.06%   |
| 251-500        | 25        | 6.3%    |
| 501-1000       | 22        | 5.54%   |
| More than 3000 | 9         | 2.27%   |
| 1001-2000      | 9         | 2.27%   |
| 2001-3000      | 5         | 1.26%   |
| Unknown        | 2         | 0.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB         | 2         | 2      | 3.51%   |
| Seagate ST1000DM003-9YN162 1TB             | 2         | 2      | 3.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD           | 1         | 1      | 1.75%   |
| WDC WD800BEVS-60RST0 80GB                  | 1         | 1      | 1.75%   |
| WDC WD5000LUCT-62C26Y0 500GB               | 1         | 1      | 1.75%   |
| WDC WD5000AAKX-003CA0 500GB                | 1         | 1      | 1.75%   |
| WDC WD400EB-00CPF0 40GB                    | 1         | 1      | 1.75%   |
| WDC WD3200BPVT-80ZEST0 320GB               | 1         | 1      | 1.75%   |
| WDC WD3200AAJS-00L7A0 320GB                | 1         | 1      | 1.75%   |
| WDC WD2500BEVT-80A23T0 250GB               | 1         | 2      | 1.75%   |
| WDC WD2500AAJS-75M0A0 249GB                | 1         | 1      | 1.75%   |
| WDC WD1600AAJS-60B4A0 160GB                | 1         | 2      | 1.75%   |
| WDC WD10EADS-65M2B0 1TB                    | 1         | 1      | 1.75%   |
| Toshiba MK5059GSXP 500GB                   | 1         | 1      | 1.75%   |
| TCSUNBOW X1 32GB SSD                       | 1         | 1      | 1.75%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD      | 1         | 1      | 1.75%   |
| SK hynix HFS128G39TND-N210A 128GB SSD      | 1         | 1      | 1.75%   |
| Seagate ST9320325AS 320GB                  | 1         | 1      | 1.75%   |
| Seagate ST9250410AS 250GB                  | 1         | 1      | 1.75%   |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 1.75%   |
| Seagate ST500DM002-1BD142 500GB            | 1         | 1      | 1.75%   |
| Seagate ST380815AS 80GB                    | 1         | 1      | 1.75%   |
| Seagate ST3360320AS 360GB                  | 1         | 1      | 1.75%   |
| Seagate ST320LT007-9ZV142 320GB            | 1         | 1      | 1.75%   |
| Seagate ST3200822AS 200GB                  | 1         | 1      | 1.75%   |
| Seagate ST3160318AS 160GB                  | 1         | 1      | 1.75%   |
| Seagate ST2000DX002-2DV164 2TB             | 1         | 1      | 1.75%   |
| Seagate ST1000NM0095-2DC10C 1TB            | 1         | 6      | 1.75%   |
| Seagate ST1000DX001-1CM162 1TB             | 1         | 1      | 1.75%   |
| Seagate ST1000DM003-1ER162 1TB             | 1         | 1      | 1.75%   |
| Samsung Electronics HM160JI 160GB          | 1         | 1      | 1.75%   |
| Samsung Electronics HM121HI 120GB          | 1         | 2      | 1.75%   |
| Maxtor STM3300622A 304GB                   | 1         | 1      | 1.75%   |
| Maxtor 6Y080L0 82GB                        | 1         | 1      | 1.75%   |
| Maxtor 6B200M0 208GB                       | 1         | 1      | 1.75%   |
| LDLC SSD 120GB                             | 1         | 1      | 1.75%   |
| Kingston SHFS37A120G 120GB SSD             | 1         | 1      | 1.75%   |
| Kingston SA400S37120G 120GB SSD            | 1         | 1      | 1.75%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD    | 1         | 1      | 1.75%   |
| Hitachi HTS723232A7A364 320GB              | 1         | 1      | 1.75%   |
| Hitachi HTS722012K9SA00 120GB              | 1         | 1      | 1.75%   |
| Hitachi HTS542512K9SA00 120GB              | 1         | 1      | 1.75%   |
| Hitachi HTS541616J9SA00 160GB              | 1         | 1      | 1.75%   |
| Hitachi HDS721075CLA332 752GB              | 1         | 1      | 1.75%   |
| Hitachi HDP725050GLA360 500GB              | 1         | 1      | 1.75%   |
| Hitachi HCP725050GLAT80 500GB              | 1         | 1      | 1.75%   |
| HGST HTS545050A7E680 500GB                 | 1         | 1      | 1.75%   |
| HGST HTS541075A9E680 752GB                 | 1         | 1      | 1.75%   |
| HGST HTS541010A9E680 1TB                   | 1         | 1      | 1.75%   |
| Fujitsu MHZ2160BH G2 160GB                 | 1         | 1      | 1.75%   |
| Crucial CT960M500SSD1 960GB                | 1         | 1      | 1.75%   |
| Crucial CT120M500SSD3 120GB                | 1         | 1      | 1.75%   |
| Crucial CT120M500SSD1 120GB                | 1         | 1      | 1.75%   |
| Apacer 16GB SATA Flash Drive SSD           | 1         | 1      | 1.75%   |
| A-DATA Technology IM2S3334-256GD 256GB SSD | 1         | 1      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 22     | 30.36%  |
| WDC                 | 11        | 13     | 19.64%  |
| Hitachi             | 6         | 7      | 10.71%  |
| Maxtor              | 3         | 3      | 5.36%   |
| Kingston            | 3         | 3      | 5.36%   |
| HGST                | 3         | 3      | 5.36%   |
| Crucial             | 3         | 3      | 5.36%   |
| SK hynix            | 2         | 2      | 3.57%   |
| Samsung Electronics | 2         | 3      | 3.57%   |
| Toshiba             | 1         | 1      | 1.79%   |
| TCSUNBOW            | 1         | 1      | 1.79%   |
| LDLC                | 1         | 1      | 1.79%   |
| Fujitsu             | 1         | 1      | 1.79%   |
| Apacer              | 1         | 1      | 1.79%   |
| A-DATA Technology   | 1         | 1      | 1.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 22     | 39.53%  |
| WDC                 | 10        | 12     | 23.26%  |
| Hitachi             | 6         | 7      | 13.95%  |
| Maxtor              | 3         | 3      | 6.98%   |
| HGST                | 3         | 3      | 6.98%   |
| Samsung Electronics | 2         | 3      | 4.65%   |
| Toshiba             | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 52     | 75.93%  |
| SSD  | 13        | 13     | 24.07%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 33.33%  |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 33.33%  |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 3      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 183       | 286    | 43.78%  |
| Works    | 179       | 265    | 42.82%  |
| Malfunc  | 53        | 65     | 12.68%  |
| Failed   | 3         | 4      | 0.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 259       | 64.27%  |
| AMD                              | 70        | 17.37%  |
| Nvidia                           | 19        | 4.71%   |
| Samsung Electronics              | 9         | 2.23%   |
| JMicron Technology               | 6         | 1.49%   |
| SanDisk                          | 5         | 1.24%   |
| Marvell Technology Group         | 4         | 0.99%   |
| LSI Logic / Symbios Logic        | 4         | 0.99%   |
| Toshiba America Info Systems     | 3         | 0.74%   |
| SK hynix                         | 3         | 0.74%   |
| KIOXIA                           | 3         | 0.74%   |
| Kingston Technology Company      | 3         | 0.74%   |
| ASMedia Technology               | 3         | 0.74%   |
| VIA Technologies                 | 2         | 0.5%    |
| Micron Technology                | 2         | 0.5%    |
| ADATA Technology                 | 2         | 0.5%    |
| Solid State Storage Technology   | 1         | 0.25%   |
| Silicon Motion                   | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Phison Electronics               | 1         | 0.25%   |
| Hewlett-Packard                  | 1         | 0.25%   |
| Broadcom / LSI                   | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 45        | 9.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 19        | 3.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 19        | 3.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 17        | 3.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 16        | 3.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15        | 3.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 2.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13        | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 2.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 2.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10        | 2.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 10        | 2.01%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 9         | 1.81%   |
| Nvidia MCP61 SATA Controller                                                            | 8         | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8         | 1.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 1.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 1.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 1.41%   |
| Nvidia MCP61 IDE                                                                        | 6         | 1.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.2%    |
| Intel SATA Controller [RAID mode]                                                       | 6         | 1.2%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 6         | 1.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 1%      |
| JMicron JMB363 SATA/IDE Controller                                                      | 5         | 1%      |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 1%      |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5         | 1%      |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5         | 1%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 1%      |
| Intel 4 Series Chipset PT IDER Controller                                               | 5         | 1%      |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1%      |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 0.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 0.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 0.8%    |
| AMD IXP SB4x0 IDE Controller                                                            | 4         | 0.8%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 0.6%    |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.6%    |
| Nvidia MCP51 Serial ATA Controller                                                      | 3         | 0.6%    |
| Nvidia CK804 Serial ATA Controller                                                      | 3         | 0.6%    |
| Nvidia CK804 IDE                                                                        | 3         | 0.6%    |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.6%    |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 0.6%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.6%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 3         | 0.6%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 3         | 0.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 0.6%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.6%    |
| AMD SB600 Non-Raid-5 SATA                                                               | 3         | 0.6%    |
| AMD SB600 IDE                                                                           | 3         | 0.6%    |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 3         | 0.6%    |
| AMD FCH SATA Controller D                                                               | 3         | 0.6%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 271       | 63.02%  |
| IDE  | 98        | 22.79%  |
| NVMe | 34        | 7.91%   |
| RAID | 25        | 5.81%   |
| SCSI | 2         | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 292       | 76.24%  |
| AMD    | 91        | 23.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 7         | 1.83%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 6         | 1.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 5         | 1.31%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 5         | 1.31%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 5         | 1.31%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 4         | 1.04%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4         | 1.04%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 1.04%   |
| AMD E-300 APU with Radeon HD Graphics       | 4         | 1.04%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 0.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 0.78%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3         | 0.78%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 0.78%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 3         | 0.78%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3         | 0.78%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3         | 0.78%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 3         | 0.78%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 2         | 0.52%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 2         | 0.52%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 0.52%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2         | 0.52%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 2         | 0.52%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 2         | 0.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 0.52%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 0.52%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 0.52%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 2         | 0.52%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 0.52%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 0.52%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 2         | 0.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 0.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 0.52%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 0.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 0.52%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2         | 0.52%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 0.52%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 0.52%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 0.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2         | 0.52%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 2         | 0.52%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 2         | 0.52%   |
| Intel Celeron Dual-Core CPU T3500 @ 2.10GHz | 2         | 0.52%   |
| Intel Celeron CPU N2807 @ 1.58GHz           | 2         | 0.52%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 2         | 0.52%   |
| Intel Celeron CPU B820 @ 1.70GHz            | 2         | 0.52%   |
| Intel Atom x5-Z8500 CPU @ 1.44GHz           | 2         | 0.52%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 0.52%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 0.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 0.52%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 2         | 0.52%   |
| AMD E-450 APU with Radeon HD Graphics       | 2         | 0.52%   |
| AMD Athlon II X2 250 Processor              | 2         | 0.52%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 2         | 0.52%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 61        | 15.93%  |
| Intel Core i7                  | 35        | 9.14%   |
| Intel Core i3                  | 34        | 8.88%   |
| Intel Celeron                  | 34        | 8.88%   |
| Intel Core 2 Duo               | 32        | 8.36%   |
| Intel Atom                     | 29        | 7.57%   |
| Intel Pentium Dual-Core        | 11        | 2.87%   |
| Intel Xeon                     | 10        | 2.61%   |
| Intel Pentium                  | 9         | 2.35%   |
| Intel Core 2                   | 9         | 2.35%   |
| Other                          | 8         | 2.09%   |
| AMD Ryzen 7                    | 8         | 2.09%   |
| AMD Ryzen 5                    | 8         | 2.09%   |
| AMD Athlon 64 X2               | 7         | 1.83%   |
| Intel Pentium Dual             | 6         | 1.57%   |
| AMD E                          | 6         | 1.57%   |
| AMD Athlon II X2               | 6         | 1.57%   |
| Intel Core 2 Quad              | 5         | 1.31%   |
| AMD A10                        | 5         | 1.31%   |
| AMD Ryzen 3                    | 4         | 1.04%   |
| AMD E1                         | 4         | 1.04%   |
| AMD A6                         | 4         | 1.04%   |
| Intel Celeron Dual-Core        | 3         | 0.78%   |
| AMD Athlon 64                  | 3         | 0.78%   |
| AMD A4                         | 3         | 0.78%   |
| Intel Pentium Silver           | 2         | 0.52%   |
| Intel Pentium 4                | 2         | 0.52%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.52%   |
| AMD Sempron                    | 2         | 0.52%   |
| AMD Ryzen 7 PRO                | 2         | 0.52%   |
| AMD Phenom II                  | 2         | 0.52%   |
| AMD GX                         | 2         | 0.52%   |
| AMD FX                         | 2         | 0.52%   |
| AMD Athlon X2                  | 2         | 0.52%   |
| Intel Pentium Gold             | 1         | 0.26%   |
| Intel Genuine                  | 1         | 0.26%   |
| Intel Core m3                  | 1         | 0.26%   |
| Intel Core 2 Solo              | 1         | 0.26%   |
| Intel Core 2 Extreme           | 1         | 0.26%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.26%   |
| AMD Ryzen Threadripper         | 1         | 0.26%   |
| AMD Ryzen 5 PRO                | 1         | 0.26%   |
| AMD Quad-Core Opteron          | 1         | 0.26%   |
| AMD Phenom II X3               | 1         | 0.26%   |
| AMD Opteron                    | 1         | 0.26%   |
| AMD Mobile Sempron             | 1         | 0.26%   |
| AMD G                          | 1         | 0.26%   |
| AMD Embedded                   | 1         | 0.26%   |
| AMD E2                         | 1         | 0.26%   |
| AMD C-60                       | 1         | 0.26%   |
| AMD C-50                       | 1         | 0.26%   |
| AMD C-30                       | 1         | 0.26%   |
| AMD Athlon X4                  | 1         | 0.26%   |
| AMD Athlon II X4               | 1         | 0.26%   |
| AMD A8                         | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 233       | 60.84%  |
| 4      | 101       | 26.37%  |
| 1      | 17        | 4.44%   |
| 8      | 13        | 3.39%   |
| 6      | 12        | 3.13%   |
| 12     | 2         | 0.52%   |
| 3      | 2         | 0.52%   |
| 64     | 1         | 0.26%   |
| 40     | 1         | 0.26%   |
| 20     | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 377       | 98.43%  |
| 2      | 5         | 1.31%   |
| 4      | 1         | 0.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 217       | 56.66%  |
| 2      | 166       | 43.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 383       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 10.1%   |
| 0x206a7    | 33        | 8.55%   |
| 0x1067a    | 22        | 5.7%    |
| 0x6fd      | 17        | 4.4%    |
| 0x306c3    | 16        | 4.15%   |
| 0x306a9    | 14        | 3.63%   |
| 0x406e3    | 12        | 3.11%   |
| 0x406c4    | 12        | 3.11%   |
| 0x40651    | 11        | 2.85%   |
| 0x30678    | 11        | 2.85%   |
| 0x10676    | 10        | 2.59%   |
| 0x806ec    | 9         | 2.33%   |
| 0x406c3    | 9         | 2.33%   |
| 0x05000119 | 9         | 2.33%   |
| 0x20655    | 8         | 2.07%   |
| 0x06006705 | 8         | 2.07%   |
| 0x6fb      | 6         | 1.55%   |
| 0x6f6      | 6         | 1.55%   |
| 0x306d4    | 6         | 1.55%   |
| 0x106ca    | 6         | 1.55%   |
| 0x706a1    | 5         | 1.3%    |
| 0x20652    | 5         | 1.3%    |
| 0x06001119 | 5         | 1.3%    |
| 0x010000c8 | 5         | 1.3%    |
| 0x906e9    | 4         | 1.04%   |
| 0x806e9    | 4         | 1.04%   |
| 0x30661    | 4         | 1.04%   |
| 0x906ea    | 3         | 0.78%   |
| 0x806eb    | 3         | 0.78%   |
| 0x806c1    | 3         | 0.78%   |
| 0x706a8    | 3         | 0.78%   |
| 0x08701021 | 3         | 0.78%   |
| 0x08600106 | 3         | 0.78%   |
| 0x07030105 | 3         | 0.78%   |
| 0x0700010f | 3         | 0.78%   |
| 0x906ed    | 2         | 0.52%   |
| 0x706e5    | 2         | 0.52%   |
| 0x6fa      | 2         | 0.52%   |
| 0x6f2      | 2         | 0.52%   |
| 0x506e3    | 2         | 0.52%   |
| 0x506c9    | 2         | 0.52%   |
| 0x306e4    | 2         | 0.52%   |
| 0x30673    | 2         | 0.52%   |
| 0x206d7    | 2         | 0.52%   |
| 0x10661    | 2         | 0.52%   |
| 0x08701013 | 2         | 0.52%   |
| 0x08600103 | 2         | 0.52%   |
| 0x08108102 | 2         | 0.52%   |
| 0x0800820d | 2         | 0.52%   |
| 0x07030106 | 2         | 0.52%   |
| 0x06000852 | 2         | 0.52%   |
| 0x05000029 | 2         | 0.52%   |
| 0x02000057 | 2         | 0.52%   |
| 0x010000c7 | 2         | 0.52%   |
| 0xf65      | 1         | 0.26%   |
| 0xf4a      | 1         | 0.26%   |
| 0xa0655    | 1         | 0.26%   |
| 0xa0653    | 1         | 0.26%   |
| 0x806ea    | 1         | 0.26%   |
| 0x806d1    | 1         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Core            | 37        | 9.66%   |
| SandyBridge     | 36        | 9.4%    |
| Silvermont      | 35        | 9.14%   |
| Penryn          | 34        | 8.88%   |
| Haswell         | 32        | 8.36%   |
| KabyLake        | 27        | 7.05%   |
| Westmere        | 17        | 4.44%   |
| Skylake         | 17        | 4.44%   |
| IvyBridge       | 16        | 4.18%   |
| K8 Hammer       | 15        | 3.92%   |
| Zen 2           | 13        | 3.39%   |
| K10             | 12        | 3.13%   |
| Bobcat          | 11        | 2.87%   |
| Bonnell         | 10        | 2.61%   |
| Excavator       | 9         | 2.35%   |
| Zen+            | 8         | 2.09%   |
| Goldmont plus   | 8         | 2.09%   |
| Piledriver      | 7         | 1.83%   |
| Broadwell       | 7         | 1.83%   |
| Puma            | 6         | 1.57%   |
| TigerLake       | 4         | 1.04%   |
| K8 & K10 hybrid | 3         | 0.78%   |
| Jaguar          | 3         | 0.78%   |
| IceLake         | 3         | 0.78%   |
| Goldmont        | 3         | 0.78%   |
| CometLake       | 3         | 0.78%   |
| Zen             | 2         | 0.52%   |
| NetBurst        | 2         | 0.52%   |
| Zen 3           | 1         | 0.26%   |
| Steamroller     | 1         | 0.26%   |
| Nehalem         | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 230       | 54.63%  |
| AMD                              | 102       | 24.23%  |
| Nvidia                           | 84        | 19.95%  |
| Matrox Electronics Systems       | 4         | 0.95%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 6.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 4.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 3.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 3.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 3.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 3.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 2.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 2.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 2.02%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.57%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 1.35%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.35%   |
| AMD Renoir                                                                               | 6         | 1.35%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 5         | 1.12%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.12%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 1.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 0.9%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 0.9%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.9%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.9%    |
| AMD Richland [Radeon HD 8670D]                                                           | 4         | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.67%   |
| Intel HD Graphics 620                                                                    | 3         | 0.67%   |
| Intel HD Graphics 530                                                                    | 3         | 0.67%   |
| Intel HD Graphics 500                                                                    | 3         | 0.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.67%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.67%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 0.67%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.67%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 3         | 0.67%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.67%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.45%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.45%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.45%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.45%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.45%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.45%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 0.45%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.45%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.45%   |
| Intel HD Graphics 520                                                                    | 2         | 0.45%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.45%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.45%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 2         | 0.45%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2         | 0.45%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 197       | 51.3%   |
| 1 x AMD         | 85        | 22.14%  |
| 1 x Nvidia      | 58        | 15.1%   |
| Intel + Nvidia  | 21        | 5.47%   |
| Intel + AMD     | 10        | 2.6%    |
| 2 x AMD         | 5         | 1.3%    |
| 1 x Matrox      | 3         | 0.78%   |
| AMD + Nvidia    | 2         | 0.52%   |
| 2 x Nvidia      | 1         | 0.26%   |
| 1 x SiS         | 1         | 0.26%   |
| Nvidia + Matrox | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 340       | 88.54%  |
| Proprietary | 40        | 10.42%  |
| Unknown     | 4         | 1.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 217       | 56.36%  |
| 0.01-0.5   | 86        | 22.34%  |
| 0.51-1.0   | 34        | 8.83%   |
| 1.01-2.0   | 29        | 7.53%   |
| 3.01-4.0   | 10        | 2.6%    |
| 7.01-8.0   | 3         | 0.78%   |
| 2.01-3.0   | 3         | 0.78%   |
| 8.01-16.0  | 2         | 0.52%   |
| 5.01-6.0   | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 50        | 12.76%  |
| AU Optronics            | 49        | 12.5%   |
| LG Display              | 38        | 9.69%   |
| BOE                     | 33        | 8.42%   |
| Chimei Innolux          | 30        | 7.65%   |
| Dell                    | 24        | 6.12%   |
| Goldstar                | 20        | 5.1%    |
| Acer                    | 17        | 4.34%   |
| Hewlett-Packard         | 15        | 3.83%   |
| Lenovo                  | 11        | 2.81%   |
| Chi Mei Optoelectronics | 8         | 2.04%   |
| Philips                 | 6         | 1.53%   |
| BenQ                    | 6         | 1.53%   |
| Apple                   | 6         | 1.53%   |
| Vizio                   | 5         | 1.28%   |
| LG Philips              | 5         | 1.28%   |
| Iiyama                  | 5         | 1.28%   |
| Sharp                   | 4         | 1.02%   |
| InfoVision              | 4         | 1.02%   |
| AOC                     | 4         | 1.02%   |
| Ancor Communications    | 4         | 1.02%   |
| Unknown                 | 3         | 0.77%   |
| Sony                    | 3         | 0.77%   |
| NEC Computers           | 3         | 0.77%   |
| HannStar                | 3         | 0.77%   |
| PANDA                   | 2         | 0.51%   |
| LG Electronics          | 2         | 0.51%   |
| Lenovo Group Limited    | 2         | 0.51%   |
| IOD                     | 2         | 0.51%   |
| InnoLux Display         | 2         | 0.51%   |
| FL_                     | 2         | 0.51%   |
| CVT                     | 2         | 0.51%   |
| CPT                     | 2         | 0.51%   |
| ___                     | 1         | 0.26%   |
| ViewSonic               | 1         | 0.26%   |
| Videoseven              | 1         | 0.26%   |
| Unknown (ADA)           | 1         | 0.26%   |
| Sceptre Tech            | 1         | 0.26%   |
| Proview                 | 1         | 0.26%   |
| Plain Tree Systems      | 1         | 0.26%   |
| MSI                     | 1         | 0.26%   |
| MOT                     | 1         | 0.26%   |
| Lite-On                 | 1         | 0.26%   |
| KDC                     | 1         | 0.26%   |
| IBM                     | 1         | 0.26%   |
| Hitachi                 | 1         | 0.26%   |
| GDH                     | 1         | 0.26%   |
| Fujitsu Siemens         | 1         | 0.26%   |
| Element                 | 1         | 0.26%   |
| Eizo                    | 1         | 0.26%   |
| DENON                   | 1         | 0.26%   |
| Compaq Computer         | 1         | 0.26%   |
| Arnos Instruments       | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 1.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 3         | 0.75%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 3         | 0.75%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 0.75%   |
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch  | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3245 1280x800 261x163mm 12.1-inch  | 2         | 0.5%    |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch           | 2         | 0.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.5%    |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2         | 0.5%    |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 2         | 0.5%    |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 2         | 0.5%    |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch           | 2         | 0.5%    |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch             | 2         | 0.5%    |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                 | 2         | 0.5%    |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                      | 2         | 0.5%    |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2         | 0.5%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.5%    |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 2         | 0.5%    |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 0.5%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 0.5%    |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                  | 2         | 0.5%    |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                  | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch         | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 0.5%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 2         | 0.5%    |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 410x260mm 19.1-inch | 2         | 0.5%    |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.25%   |
| ___ LCD TV ___0101 1360x768                                           | 1         | 0.25%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1         | 0.25%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1         | 0.25%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                    | 1         | 0.25%   |
| Vizio E371VL VIZ0090 1920x1080 820x460mm 37.0-inch                    | 1         | 0.25%   |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                    | 1         | 0.25%   |
| ViewSonic VX2035wm VSCAF1E 1680x1050 433x271mm 20.1-inch              | 1         | 0.25%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.25%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                | 1         | 0.25%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1         | 0.25%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                 | 1         | 0.25%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1         | 0.25%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                            | 1         | 0.25%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1         | 0.25%   |
| Sony TV SNYAA01 1360x768                                              | 1         | 0.25%   |
| Sony TV SNYA401 1920x1080 1600x900mm 72.3-inch                        | 1         | 0.25%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                     | 1         | 0.25%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch               | 1         | 0.25%   |
| Sharp LCD Monitor SHP14AD 3840x2160 290x170mm 13.2-inch               | 1         | 0.25%   |
| Sharp LCD Monitor SHP146A 1920x1080 294x165mm 13.3-inch               | 1         | 0.25%   |
| Sharp HDMI SHP0FFD 1920x1080 820x460mm 37.0-inch                      | 1         | 0.25%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1         | 0.25%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.25%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch     | 1         | 0.25%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 110       | 28.57%  |
| 1920x1080 (FHD)    | 103       | 26.75%  |
| 1280x1024 (SXGA)   | 30        | 7.79%   |
| 1280x800 (WXGA)    | 25        | 6.49%   |
| 1600x900 (HD+)     | 24        | 6.23%   |
| 1680x1050 (WSXGA+) | 20        | 5.19%   |
| 1440x900 (WXGA+)   | 14        | 3.64%   |
| 3840x2160 (4K)     | 10        | 2.6%    |
| 2560x1440 (QHD)    | 10        | 2.6%    |
| 1920x1200 (WUXGA)  | 10        | 2.6%    |
| 1024x768 (XGA)     | 7         | 1.82%   |
| 1024x600           | 4         | 1.04%   |
| 2560x1600          | 3         | 0.78%   |
| 3440x1440          | 2         | 0.52%   |
| 2560x1080          | 2         | 0.52%   |
| 1360x768           | 2         | 0.52%   |
| 3840x2400          | 1         | 0.26%   |
| 3600x1200          | 1         | 0.26%   |
| 2288x1287          | 1         | 0.26%   |
| 2048x1152          | 1         | 0.26%   |
| 1920x540           | 1         | 0.26%   |
| 1600x1200          | 1         | 0.26%   |
| 1280x768           | 1         | 0.26%   |
| 1280x720 (HD)      | 1         | 0.26%   |
| Unknown            | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 103       | 26.21%  |
| 13      | 42        | 10.69%  |
| 17      | 39        | 9.92%   |
| 14      | 37        | 9.41%   |
| 27      | 17        | 4.33%   |
| 23      | 17        | 4.33%   |
| 21      | 17        | 4.33%   |
| 19      | 17        | 4.33%   |
| 24      | 16        | 4.07%   |
| 22      | 13        | 3.31%   |
| 11      | 12        | 3.05%   |
| Unknown | 12        | 3.05%   |
| 20      | 10        | 2.54%   |
| 18      | 8         | 2.04%   |
| 10      | 7         | 1.78%   |
| 12      | 5         | 1.27%   |
| 72      | 3         | 0.76%   |
| 34      | 3         | 0.76%   |
| 41      | 2         | 0.51%   |
| 39      | 2         | 0.51%   |
| 31      | 2         | 0.51%   |
| 84      | 1         | 0.25%   |
| 52      | 1         | 0.25%   |
| 47      | 1         | 0.25%   |
| 38      | 1         | 0.25%   |
| 37      | 1         | 0.25%   |
| 33      | 1         | 0.25%   |
| 29      | 1         | 0.25%   |
| 26      | 1         | 0.25%   |
| 7       | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 177       | 45.5%   |
| 401-500     | 53        | 13.62%  |
| 501-600     | 49        | 12.6%   |
| 201-300     | 41        | 10.54%  |
| 351-400     | 36        | 9.25%   |
| Unknown     | 12        | 3.08%   |
| 801-900     | 4         | 1.03%   |
| 701-800     | 4         | 1.03%   |
| 601-700     | 4         | 1.03%   |
| 1501-2000   | 4         | 1.03%   |
| 1001-1500   | 2         | 0.51%   |
| 901-1000    | 2         | 0.51%   |
| 101-200     | 1         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 249       | 68.41%  |
| 16/10   | 63        | 17.31%  |
| 5/4     | 27        | 7.42%   |
| Unknown | 10        | 2.75%   |
| 4/3     | 8         | 2.2%    |
| 21/9    | 4         | 1.1%    |
| 6/5     | 2         | 0.55%   |
| 3/2     | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 101       | 25.83%  |
| 81-90          | 66        | 16.88%  |
| 201-250        | 53        | 13.55%  |
| 151-200        | 32        | 8.18%   |
| 141-150        | 23        | 5.88%   |
| 301-350        | 18        | 4.6%    |
| 121-130        | 16        | 4.09%   |
| 71-80          | 14        | 3.58%   |
| 51-60          | 12        | 3.07%   |
| Unknown        | 12        | 3.07%   |
| 41-50          | 7         | 1.79%   |
| 251-300        | 7         | 1.79%   |
| 501-1000       | 7         | 1.79%   |
| 351-500        | 6         | 1.53%   |
| More than 1000 | 5         | 1.28%   |
| 131-140        | 5         | 1.28%   |
| 61-70          | 4         | 1.02%   |
| 1-40           | 1         | 0.26%   |
| 111-120        | 1         | 0.26%   |
| 91-100         | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 139       | 36.39%  |
| 101-120       | 136       | 35.6%   |
| 121-160       | 76        | 19.9%   |
| Unknown       | 12        | 3.14%   |
| 161-240       | 10        | 2.62%   |
| 1-50          | 6         | 1.57%   |
| More than 240 | 3         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 332       | 85.79%  |
| 2     | 44        | 11.37%  |
| 0     | 7         | 1.81%   |
| 3     | 3         | 0.78%   |
| 4     | 1         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 209       | 36.03%  |
| Intel                             | 148       | 25.52%  |
| Qualcomm Atheros                  | 78        | 13.45%  |
| Broadcom                          | 42        | 7.24%   |
| Ralink Technology                 | 16        | 2.76%   |
| Nvidia                            | 16        | 2.76%   |
| Marvell Technology Group          | 16        | 2.76%   |
| Broadcom Limited                  | 11        | 1.9%    |
| Ralink                            | 8         | 1.38%   |
| TP-Link                           | 5         | 0.86%   |
| Samsung Electronics               | 4         | 0.69%   |
| ASIX Electronics                  | 4         | 0.69%   |
| NetGear                           | 2         | 0.34%   |
| Fibocom                           | 2         | 0.34%   |
| Dell                              | 2         | 0.34%   |
| Belkin Components                 | 2         | 0.34%   |
| Attansic Technology               | 2         | 0.34%   |
| ZyXEL Communications              | 1         | 0.17%   |
| Xiaomi                            | 1         | 0.17%   |
| VIA Technologies                  | 1         | 0.17%   |
| U-Blox                            | 1         | 0.17%   |
| Tenda                             | 1         | 0.17%   |
| Sitecom Europe                    | 1         | 0.17%   |
| Seeed                             | 1         | 0.17%   |
| Logitec                           | 1         | 0.17%   |
| Huawei Technologies               | 1         | 0.17%   |
| Hewlett-Packard                   | 1         | 0.17%   |
| Ericsson Business Mobile Networks | 1         | 0.17%   |
| Aquantia                          | 1         | 0.17%   |
| ADMtek                            | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 123       | 18.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 42        | 6.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 16        | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 1.95%   |
| Intel Wireless 7260                                                     | 13        | 1.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 1.5%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.2%    |
| Nvidia MCP61 Ethernet                                                   | 8         | 1.2%    |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 1.05%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.9%    |
| Intel Wireless 7265                                                     | 6         | 0.9%    |
| Intel Wireless 3160                                                     | 6         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.75%   |
| Intel Wireless 8260                                                     | 5         | 0.75%   |
| Intel Wireless 3165                                                     | 5         | 0.75%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.75%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 5         | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.6%    |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.6%    |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.6%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                           | 4         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.45%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.45%   |
| Ralink RT5572 Wireless Adapter                                          | 3         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.45%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 3         | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 3         | 0.45%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.45%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 0.45%   |
| Intel Ethernet Connection I219-V                                        | 3         | 0.45%   |
| Intel Ethernet Connection I217-V                                        | 3         | 0.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.45%   |
| Intel Centrino Wireless-N 100                                           | 3         | 0.45%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 0.45%   |
| Intel 82574L Gigabit Network Connection                                 | 3         | 0.45%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 0.45%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 3         | 0.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 3         | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 112       | 37.58%  |
| Qualcomm Atheros      | 67        | 22.48%  |
| Realtek Semiconductor | 53        | 17.79%  |
| Broadcom              | 24        | 8.05%   |
| Ralink Technology     | 16        | 5.37%   |
| Ralink                | 8         | 2.68%   |
| TP-Link               | 5         | 1.68%   |
| Broadcom Limited      | 4         | 1.34%   |
| NetGear               | 2         | 0.67%   |
| Belkin Components     | 2         | 0.67%   |
| ZyXEL Communications  | 1         | 0.34%   |
| Tenda                 | 1         | 0.34%   |
| Sitecom Europe        | 1         | 0.34%   |
| Logitec               | 1         | 0.34%   |
| Dell                  | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 16        | 5.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 4.35%   |
| Intel Wireless 7260                                                     | 13        | 4.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 3.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 3.34%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 3.34%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 3.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.68%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 2.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 2.34%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 2.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 2.01%   |
| Intel Wireless 7265                                                     | 6         | 2.01%   |
| Intel Wireless 3160                                                     | 6         | 2.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.67%   |
| Intel Wireless 8260                                                     | 5         | 1.67%   |
| Intel Wireless 3165                                                     | 5         | 1.67%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.67%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.34%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.34%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.34%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1%      |
| Realtek 802.11ac NIC                                                    | 3         | 1%      |
| Ralink RT5572 Wireless Adapter                                          | 3         | 1%      |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 3         | 1%      |
| Intel Wireless-AC 9260                                                  | 3         | 1%      |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1%      |
| Intel Centrino Wireless-N 100                                           | 3         | 1%      |
| Intel Centrino Advanced-N 6200                                          | 3         | 1%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.67%   |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.67%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 2         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.67%   |
| Intel Wireless 8265 / 8275                                              | 2         | 0.67%   |
| Intel WiFi Link 5100                                                    | 2         | 0.67%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.67%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.67%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.67%   |
| Broadcom Limited BCM4311 802.11a/b/g                                    | 2         | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.67%   |
| ZyXEL ZyAIR G-202 802.11bg                                              | 1         | 0.33%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 1         | 0.33%   |
| Tenda U12                                                               | 1         | 0.33%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                         | 1         | 0.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 188       | 52.96%  |
| Intel                    | 64        | 18.03%  |
| Broadcom                 | 26        | 7.32%   |
| Qualcomm Atheros         | 21        | 5.92%   |
| Nvidia                   | 16        | 4.51%   |
| Marvell Technology Group | 16        | 4.51%   |
| Broadcom Limited         | 7         | 1.97%   |
| Samsung Electronics      | 4         | 1.13%   |
| ASIX Electronics         | 4         | 1.13%   |
| Fibocom                  | 2         | 0.56%   |
| Attansic Technology      | 2         | 0.56%   |
| Xiaomi                   | 1         | 0.28%   |
| VIA Technologies         | 1         | 0.28%   |
| Huawei Technologies      | 1         | 0.28%   |
| Aquantia                 | 1         | 0.28%   |
| ADMtek                   | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 123       | 33.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 42        | 11.54%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 3.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 3.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 2.47%   |
| Nvidia MCP61 Ethernet                                                          | 8         | 2.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 1.65%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.37%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 5         | 1.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.1%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 4         | 1.1%    |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.1%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 0.82%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 0.82%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.82%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.82%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.82%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3         | 0.82%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 3         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.82%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 3         | 0.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.55%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 2         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.55%   |
| Nvidia MCP51 Ethernet Controller                                               | 2         | 0.55%   |
| Nvidia CK804 Ethernet Controller                                               | 2         | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2         | 0.55%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 2         | 0.55%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 2         | 0.55%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.55%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.55%   |
| Intel 82562V-2 10/100 Network Connection                                       | 2         | 0.55%   |
| Fibocom L831-EAU-00                                                            | 2         | 0.55%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.55%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.55%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.27%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.27%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.27%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.27%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.27%   |
| Nvidia MCP73 Ethernet                                                          | 1         | 0.27%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.27%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.27%   |
| Nvidia CK8S Ethernet Controller                                                | 1         | 0.27%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.27%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 341       | 53.96%  |
| WiFi     | 286       | 45.25%  |
| Modem    | 5         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 226       | 56.93%  |
| Ethernet | 171       | 43.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 212       | 55.35%  |
| 1     | 145       | 37.86%  |
| 0     | 16        | 4.18%   |
| 3     | 7         | 1.83%   |
| 4     | 3         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 330       | 84.83%  |
| Yes  | 59        | 15.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 44.07%  |
| Qualcomm Atheros Communications | 17        | 9.6%    |
| Cambridge Silicon Radio         | 16        | 9.04%   |
| Broadcom                        | 16        | 9.04%   |
| Realtek Semiconductor           | 11        | 6.21%   |
| Lite-On Technology              | 10        | 5.65%   |
| IMC Networks                    | 6         | 3.39%   |
| Apple                           | 5         | 2.82%   |
| Hewlett-Packard                 | 4         | 2.26%   |
| Dell                            | 4         | 2.26%   |
| Ralink Technology               | 2         | 1.13%   |
| ASUSTek Computer                | 2         | 1.13%   |
| Alps Electric                   | 2         | 1.13%   |
| Toshiba                         | 1         | 0.56%   |
| Ralink                          | 1         | 0.56%   |
| Foxconn / Hon Hai               | 1         | 0.56%   |
| Chicony Electronics             | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 40        | 22.6%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 16        | 9.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 7.34%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 10        | 5.65%   |
| Realtek Bluetooth Radio                                                             | 7         | 3.95%   |
| Intel AX200 Bluetooth                                                               | 7         | 3.95%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 2.26%   |
| Intel Bluetooth Device                                                              | 4         | 2.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.69%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.69%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.69%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.69%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.69%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.69%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.13%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 1.13%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 1.13%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.13%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.13%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.13%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.13%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.13%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.56%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.56%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.56%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.56%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.56%   |
| IMC Networks Bluetooth module                                                       | 1         | 0.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.56%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.56%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.56%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.56%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.56%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 1         | 0.56%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.56%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.56%   |
| Broadcom Bluetooth Device                                                           | 1         | 0.56%   |
| Broadcom Bluetooth                                                                  | 1         | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.56%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.56%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.56%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 0.56%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.56%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.56%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.56%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 262       | 58.22%  |
| AMD                               | 96        | 21.33%  |
| Nvidia                            | 67        | 14.89%  |
| C-Media Electronics               | 6         | 1.33%   |
| Creative Labs                     | 4         | 0.89%   |
| GN Netcom                         | 3         | 0.67%   |
| XMOS                              | 2         | 0.44%   |
| Logitech                          | 2         | 0.44%   |
| VIA Technologies                  | 1         | 0.22%   |
| Unknown                           | 1         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.22%   |
| Focusrite-Novation                | 1         | 0.22%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.22%   |
| Creative Technology               | 1         | 0.22%   |
| ASUSTek Computer                  | 1         | 0.22%   |
| Asahi Kasei Microsystems          | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 4.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 24        | 4.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 24        | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 4.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 21        | 3.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 20        | 3.72%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 3.53%   |
| AMD FCH Azalia Controller                                                                         | 18        | 3.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 2.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 2.79%   |
| Nvidia High Definition Audio Controller                                                           | 13        | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.42%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 2.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.23%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 1.86%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.67%   |
| AMD High Definition Audio Controller                                                              | 9         | 1.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 1.67%   |
| Nvidia MCP61 High Definition Audio                                                                | 8         | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.49%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.12%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.12%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 5         | 0.93%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.93%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 5         | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 0.74%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 0.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.74%   |
| Nvidia MCP51 High Definition Audio                                                                | 3         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.56%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.56%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.56%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.56%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 3         | 0.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.56%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.56%   |
| XMOS Mayfield Audio                                                                               | 2         | 0.37%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.37%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.37%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.37%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.37%   |
| Nvidia CK804 AC'97 Audio Controller                                                               | 2         | 0.37%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.37%   |
| C-Media Electronics Audio Adapter                                                                 | 2         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 67        | 22.95%  |
| SK hynix            | 53        | 18.15%  |
| Unknown             | 46        | 15.75%  |
| Micron Technology   | 24        | 8.22%   |
| Kingston            | 19        | 6.51%   |
| Crucial             | 12        | 4.11%   |
| Nanya Technology    | 10        | 3.42%   |
| Corsair             | 9         | 3.08%   |
| G.Skill             | 7         | 2.4%    |
| A-DATA Technology   | 7         | 2.4%    |
| Elpida              | 5         | 1.71%   |
| Unknown (ABCD)      | 4         | 1.37%   |
| Smart               | 4         | 1.37%   |
| Patriot             | 4         | 1.37%   |
| Team                | 3         | 1.03%   |
| Timetec             | 2         | 0.68%   |
| Qimonda             | 2         | 0.68%   |
| Unifosa             | 1         | 0.34%   |
| Transcend           | 1         | 0.34%   |
| Teikon              | 1         | 0.34%   |
| Sesame              | 1         | 0.34%   |
| Ramaxel Technology  | 1         | 0.34%   |
| PNY                 | 1         | 0.34%   |
| Multilaser          | 1         | 0.34%   |
| Goldkey             | 1         | 0.34%   |
| e2e4                | 1         | 0.34%   |
| Digiboard           | 1         | 0.34%   |
| Avant               | 1         | 0.34%   |
| ASint Technology    | 1         | 0.34%   |
| Apacer              | 1         | 0.34%   |
| 48spaces            | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 5         | 1.59%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 5         | 1.59%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                       | 4         | 1.27%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 4         | 1.27%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 3         | 0.96%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.96%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 0.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 0.96%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                      | 2         | 0.64%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                        | 2         | 0.64%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 2         | 0.64%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 2         | 0.64%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                              | 2         | 0.64%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 2         | 0.64%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 2         | 0.64%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 0.64%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                     | 2         | 0.64%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.64%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 2         | 0.64%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 2         | 0.64%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 0.64%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 2         | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 0.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.64%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.64%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s              | 2         | 0.64%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                 | 2         | 0.64%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s             | 2         | 0.64%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR 2048MT/s                   | 2         | 0.64%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                       | 2         | 0.64%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.64%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 2         | 0.64%   |
| Corsair RAM CMSO8GX3M1C1600C11 8192MB SODIMM DDR3 1600MT/s          | 2         | 0.64%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1333MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.32%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                        | 1         | 0.32%   |
| Unknown RAM Module 512MB DIMM 400MT/s                               | 1         | 0.32%   |
| Unknown RAM Module 512MB DIMM 333MT/s                               | 1         | 0.32%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1067MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.32%   |
| Unknown RAM Module 4096MB DIMM SDRAM                                | 1         | 0.32%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                        | 1         | 0.32%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                        | 1         | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                          | 1         | 0.32%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 1         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM LPDDR4 2400MT/s                    | 1         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 2048MB DIMM LPDDR4 1600MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 2048MB DIMM DDR2                                 | 1         | 0.32%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                              | 1         | 0.32%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 117       | 45.88%  |
| DDR4    | 67        | 26.27%  |
| DDR2    | 33        | 12.94%  |
| SDRAM   | 15        | 5.88%   |
| Unknown | 8         | 3.14%   |
| LPDDR4  | 6         | 2.35%   |
| LPDDR3  | 6         | 2.35%   |
| DDR     | 3         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 158       | 63.45%  |
| DIMM         | 82        | 32.93%  |
| Row Of Chips | 7         | 2.81%   |
| Chip         | 1         | 0.4%    |
| Unknown      | 1         | 0.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 94        | 33.45%  |
| 2048  | 74        | 26.33%  |
| 8192  | 68        | 24.2%   |
| 1024  | 22        | 7.83%   |
| 16384 | 16        | 5.69%   |
| 32768 | 3         | 1.07%   |
| 512   | 3         | 1.07%   |
| 65536 | 1         | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 68        | 24.2%   |
| 1333    | 26        | 9.25%   |
| 2400    | 23        | 8.19%   |
| 2667    | 21        | 7.47%   |
| 1334    | 21        | 7.47%   |
| 3200    | 16        | 5.69%   |
| 667     | 16        | 5.69%   |
| 800     | 14        | 4.98%   |
| 2133    | 12        | 4.27%   |
| 2048    | 8         | 2.85%   |
| 1867    | 8         | 2.85%   |
| 1066    | 8         | 2.85%   |
| Unknown | 7         | 2.49%   |
| 400     | 5         | 1.78%   |
| 1866    | 4         | 1.42%   |
| 3266    | 3         | 1.07%   |
| 533     | 3         | 1.07%   |
| 3600    | 2         | 0.71%   |
| 3000    | 2         | 0.71%   |
| 1639    | 2         | 0.71%   |
| 1067    | 2         | 0.71%   |
| 49926   | 1         | 0.36%   |
| 8400    | 1         | 0.36%   |
| 4267    | 1         | 0.36%   |
| 3466    | 1         | 0.36%   |
| 3066    | 1         | 0.36%   |
| 2733    | 1         | 0.36%   |
| 1200    | 1         | 0.36%   |
| 333     | 1         | 0.36%   |
| 2       | 1         | 0.36%   |
| 1       | 1         | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 50%     |
| Brother Industries  | 2         | 33.33%  |
| Samsung Electronics | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 16.67%  |
| HP DeskJet 3630 series  | 1         | 16.67%  |
| HP Deskjet 3520 series  | 1         | 16.67%  |
| HP Deskjet 1050 J410    | 1         | 16.67%  |
| Brother PTUSB Printing  | 1         | 16.67%  |
| Brother DCP-7055W       | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 56        | 25.45%  |
| Acer                                   | 20        | 9.09%   |
| Realtek Semiconductor                  | 19        | 8.64%   |
| IMC Networks                           | 15        | 6.82%   |
| Microdia                               | 13        | 5.91%   |
| Sunplus Innovation Technology          | 10        | 4.55%   |
| Suyin                                  | 9         | 4.09%   |
| Quanta                                 | 8         | 3.64%   |
| Alcor Micro                            | 8         | 3.64%   |
| Silicon Motion                         | 6         | 2.73%   |
| Apple                                  | 5         | 2.27%   |
| Ricoh                                  | 4         | 1.82%   |
| Logitech                               | 4         | 1.82%   |
| Lite-On Technology                     | 4         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 1.82%   |
| Z-Star Microelectronics                | 3         | 1.36%   |
| Syntek                                 | 3         | 1.36%   |
| Samsung Electronics                    | 3         | 1.36%   |
| Luxvisions Innotech Limited            | 3         | 1.36%   |
| Lenovo                                 | 3         | 1.36%   |
| Importek                               | 3         | 1.36%   |
| Generalplus Technology                 | 3         | 1.36%   |
| SunplusIT                              | 2         | 0.91%   |
| Y Media                                | 1         | 0.45%   |
| OmniVision Technologies                | 1         | 0.45%   |
| Nintendo                               | 1         | 0.45%   |
| Microsoft                              | 1         | 0.45%   |
| LG Electronics                         | 1         | 0.45%   |
| KYE Systems (Mouse Systems)            | 1         | 0.45%   |
| Guillemot                              | 1         | 0.45%   |
| Genesys Logic                          | 1         | 0.45%   |
| GEMBIRD                                | 1         | 0.45%   |
| DigiTech                               | 1         | 0.45%   |
| ARC International                      | 1         | 0.45%   |
| ALi                                    | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 8         | 3.62%   |
| Realtek Integrated_Webcam_HD             | 7         | 3.17%   |
| Chicony TOSHIBA Web Camera - HD          | 5         | 2.26%   |
| Alcor Micro USB 2.0 Camera               | 5         | 2.26%   |
| Acer Lenovo EasyCamera                   | 5         | 2.26%   |
| Chicony HP HD Camera                     | 4         | 1.81%   |
| Samsung Galaxy series, misc. (MTP mode)  | 3         | 1.36%   |
| Realtek USB Camera                       | 3         | 1.36%   |
| Realtek Integrated Webcam                | 3         | 1.36%   |
| Luxvisions Innotech Limited HP HD Camera | 3         | 1.36%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 3         | 1.36%   |
| IMC Networks USB2.0 UVC HD Webcam        | 3         | 1.36%   |
| IMC Networks USB2.0 HD UVC WebCam        | 3         | 1.36%   |
| Chicony HD WebCam                        | 3         | 1.36%   |
| Chicony EasyCamera                       | 3         | 1.36%   |
| Apple FaceTime HD Camera                 | 3         | 1.36%   |
| Alcor Micro Asus Integrated Webcam       | 3         | 1.36%   |
| Acer VGA WebCam                          | 3         | 1.36%   |
| Acer HD WebCam                           | 3         | 1.36%   |
| SunplusIT USB 2.0 Camera                 | 2         | 0.9%    |
| Sunplus Laptop Integrated Webcam HD      | 2         | 0.9%    |
| Sunplus Integrated_Webcam_HD             | 2         | 0.9%    |
| Sunplus HD WebCam                        | 2         | 0.9%    |
| Realtek Lenovo EasyCamera                | 2         | 0.9%    |
| Quanta VGA WebCam                        | 2         | 0.9%    |
| Quanta HP Webcam                         | 2         | 0.9%    |
| Quanta HP HD Camera                      | 2         | 0.9%    |
| Microdia Sonix USB 2.0 Camera            | 2         | 0.9%    |
| Microdia Laptop_Integrated_Webcam_2M     | 2         | 0.9%    |
| Microdia Integrated Webcam               | 2         | 0.9%    |
| Logitech Webcam C270                     | 2         | 0.9%    |
| Lite-On HP HD Camera                     | 2         | 0.9%    |
| Importek TOSHIBA Web Camera - HD         | 2         | 0.9%    |
| IMC Networks USB 2.0 UVC VGA WebCam      | 2         | 0.9%    |
| IMC Networks Integrated Camera           | 2         | 0.9%    |
| Generalplus GENERAL WEBCAM               | 2         | 0.9%    |
| Chicony USB 2.0 Camera                   | 2         | 0.9%    |
| Chicony HP Webcam                        | 2         | 0.9%    |
| Chicony HD WebCam (Acer)                 | 2         | 0.9%    |
| Chicony 720p HD Camera                   | 2         | 0.9%    |
| Acer Integrated Camera                   | 2         | 0.9%    |
| Acer BisonCam,NB Pro                     | 2         | 0.9%    |
| Acer BisonCam, NB Pro                    | 2         | 0.9%    |
| Z-Star Webcam                            | 1         | 0.45%   |
| Z-Star Sirius USB2.0 Camera              | 1         | 0.45%   |
| Z-Star Namuga 1.3M Webcam                | 1         | 0.45%   |
| Y Media USB Camera                       | 1         | 0.45%   |
| Syntek Integrated Webcam                 | 1         | 0.45%   |
| Syntek Integrated Camera                 | 1         | 0.45%   |
| Syntek EasyCamera                        | 1         | 0.45%   |
| Suyin WebCam                             | 1         | 0.45%   |
| Suyin Sony Visual Communication Camera   | 1         | 0.45%   |
| Suyin Lenovo Integrated Webcam           | 1         | 0.45%   |
| Suyin Integrated_Webcam_HD               | 1         | 0.45%   |
| Suyin HP Webcam-101                      | 1         | 0.45%   |
| Suyin HP Webcam                          | 1         | 0.45%   |
| Suyin HP TrueVision Full HD              | 1         | 0.45%   |
| Suyin Asus Integrated Webcam             | 1         | 0.45%   |
| Suyin Acer CrystalEye Webcam             | 1         | 0.45%   |
| Sunplus HP Truevision Full HD            | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 42.86%  |
| AuthenTec                  | 7         | 25%     |
| Shenzhen Goodix Technology | 3         | 10.71%  |
| Upek                       | 2         | 7.14%   |
| Synaptics                  | 2         | 7.14%   |
| STMicroelectronics         | 1         | 3.57%   |
| LighTuning Technology      | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 7.14%   |
| AuthenTec AES2810                                          | 2         | 7.14%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 7.14%   |
| AuthenTec AES1600                                          | 2         | 7.14%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 3.57%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 3.57%   |
| Validity Sensors VFS491                                    | 1         | 3.57%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 3.57%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 3.57%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 3.57%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 3.57%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 3.57%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 3.57%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 3.57%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 3.57%   |
| Shenzhen Goodix FingerPrint                                | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.57%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 3         | 33.33%  |
| Alcor Micro | 3         | 33.33%  |
| Broadcom    | 2         | 22.22%  |
| Upek        | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 311       | 80.57%  |
| 1     | 62        | 16.06%  |
| 2     | 13        | 3.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 28        | 33.33%  |
| Graphics card            | 14        | 16.67%  |
| Net/wireless             | 11        | 13.1%   |
| Chipcard                 | 9         | 10.71%  |
| Communication controller | 4         | 4.76%   |
| Unassigned class         | 3         | 3.57%   |
| Multimedia controller    | 3         | 3.57%   |
| Camera                   | 3         | 3.57%   |
| Storage                  | 2         | 2.38%   |
| Sound                    | 2         | 2.38%   |
| Net/ethernet             | 2         | 2.38%   |
| Flash memory             | 1         | 1.19%   |
| Dvb card                 | 1         | 1.19%   |
| Bluetooth                | 1         | 1.19%   |

