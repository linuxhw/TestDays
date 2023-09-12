Linux in Puerto Rico - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Puerto Rico.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Puerto_Rico/Desktop/README.md) and [notebooks](/Location/Puerto_Rico/Notebook/README.md).

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

Total: 278

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 3550                 | Notebook    | [c9431922ba](https://linux-hardware.org/?probe=c9431922ba) | Sep 01, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [53bcd4ec72](https://linux-hardware.org/?probe=53bcd4ec72) | Aug 31, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f120556c56](https://linux-hardware.org/?probe=f120556c56) | Aug 30, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [aac7eeec4e](https://linux-hardware.org/?probe=aac7eeec4e) | Aug 30, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4f3d3f12a4](https://linux-hardware.org/?probe=4f3d3f12a4) | Aug 30, 2023 |
| Gateway       | RS780                       | Desktop     | [d73767c9f7](https://linux-hardware.org/?probe=d73767c9f7) | Aug 21, 2023 |
| Dell          | Latitude 7290               | Notebook    | [eb12e0d829](https://linux-hardware.org/?probe=eb12e0d829) | Aug 17, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [df5fa32e56](https://linux-hardware.org/?probe=df5fa32e56) | Jul 25, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [9b0de4f244](https://linux-hardware.org/?probe=9b0de4f244) | Jul 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b52a9ea310](https://linux-hardware.org/?probe=b52a9ea310) | Jul 08, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [c9a8bc63d4](https://linux-hardware.org/?probe=c9a8bc63d4) | Jun 27, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [4428a36327](https://linux-hardware.org/?probe=4428a36327) | Jun 27, 2023 |
| Gateway       | H61H2-AD V1.0               | Desktop     | [9a34a9295c](https://linux-hardware.org/?probe=9a34a9295c) | Jun 15, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [58b9a1f862](https://linux-hardware.org/?probe=58b9a1f862) | Jun 13, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [318f1f4d2a](https://linux-hardware.org/?probe=318f1f4d2a) | Jun 12, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [0afa6e53d0](https://linux-hardware.org/?probe=0afa6e53d0) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ea06bd5806](https://linux-hardware.org/?probe=ea06bd5806) | May 29, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [2d42a4443c](https://linux-hardware.org/?probe=2d42a4443c) | May 23, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [b6336515aa](https://linux-hardware.org/?probe=b6336515aa) | May 19, 2023 |
| Gateway       | RS780                       | Desktop     | [e04207a390](https://linux-hardware.org/?probe=e04207a390) | May 07, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3a89155791](https://linux-hardware.org/?probe=3a89155791) | May 03, 2023 |
| Sony          | SVE11113FXW                 | Notebook    | [248c7717a4](https://linux-hardware.org/?probe=248c7717a4) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [940cbb6ef0](https://linux-hardware.org/?probe=940cbb6ef0) | Apr 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [21111146cd](https://linux-hardware.org/?probe=21111146cd) | Apr 21, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [eaade18ae0](https://linux-hardware.org/?probe=eaade18ae0) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [da0c8e23ed](https://linux-hardware.org/?probe=da0c8e23ed) | Apr 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [83132b245e](https://linux-hardware.org/?probe=83132b245e) | Apr 05, 2023 |
| ECS           | Iris8                       | Desktop     | [f86927f9ff](https://linux-hardware.org/?probe=f86927f9ff) | Apr 04, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [3c3a2da37a](https://linux-hardware.org/?probe=3c3a2da37a) | Apr 02, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [9aba047596](https://linux-hardware.org/?probe=9aba047596) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [5cf96e41e0](https://linux-hardware.org/?probe=5cf96e41e0) | Mar 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [4606b5b93d](https://linux-hardware.org/?probe=4606b5b93d) | Mar 29, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| HP            | 83E1                        | Desktop     | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| HP            | 83E1                        | Desktop     | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [40bda215a2](https://linux-hardware.org/?probe=40bda215a2) | Mar 11, 2023 |
| HP            | 83E1                        | Desktop     | [86061f121d](https://linux-hardware.org/?probe=86061f121d) | Mar 08, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [5afd8e3f42](https://linux-hardware.org/?probe=5afd8e3f42) | Mar 04, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [be9b47dc08](https://linux-hardware.org/?probe=be9b47dc08) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [3c378a3736](https://linux-hardware.org/?probe=3c378a3736) | Mar 02, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [e189c60b09](https://linux-hardware.org/?probe=e189c60b09) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3883ba28c7](https://linux-hardware.org/?probe=3883ba28c7) | Mar 01, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [5beb40c486](https://linux-hardware.org/?probe=5beb40c486) | Feb 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [593206879a](https://linux-hardware.org/?probe=593206879a) | Feb 02, 2023 |
| Dell          | Latitude E6420              | Notebook    | [68908b991a](https://linux-hardware.org/?probe=68908b991a) | Jan 30, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ea94fc4f3b](https://linux-hardware.org/?probe=ea94fc4f3b) | Jan 13, 2023 |
| HP            | 89B5 A                      | Desktop     | [4fcef21d82](https://linux-hardware.org/?probe=4fcef21d82) | Jan 07, 2023 |
| HP            | 2000                        | Notebook    | [0f801f2309](https://linux-hardware.org/?probe=0f801f2309) | Jan 07, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [0708d07cd4](https://linux-hardware.org/?probe=0708d07cd4) | Dec 28, 2022 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [b26dc749a5](https://linux-hardware.org/?probe=b26dc749a5) | Dec 23, 2022 |
| Dell          | Latitude E6420              | Notebook    | [7d592f1759](https://linux-hardware.org/?probe=7d592f1759) | Dec 20, 2022 |
| MSI           | MS-AE031                    | All in one  | [7047861d13](https://linux-hardware.org/?probe=7047861d13) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0c94171d5b](https://linux-hardware.org/?probe=0c94171d5b) | Dec 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3d516c4ca3](https://linux-hardware.org/?probe=3d516c4ca3) | Dec 06, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [267ffa24d1](https://linux-hardware.org/?probe=267ffa24d1) | Dec 04, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [7145280e9e](https://linux-hardware.org/?probe=7145280e9e) | Dec 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [251fb963fe](https://linux-hardware.org/?probe=251fb963fe) | Nov 28, 2022 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [fe69e51efe](https://linux-hardware.org/?probe=fe69e51efe) | Nov 03, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [9e63ba2bf9](https://linux-hardware.org/?probe=9e63ba2bf9) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5dbeb45ba5](https://linux-hardware.org/?probe=5dbeb45ba5) | Oct 06, 2022 |
| ASRock        | X570 Phantom Gaming 4S      | Desktop     | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
| Dell          | G5 5505                     | Notebook    | [e26e58afac](https://linux-hardware.org/?probe=e26e58afac) | Sep 08, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b667cf66e8](https://linux-hardware.org/?probe=b667cf66e8) | Sep 07, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [1c9628e804](https://linux-hardware.org/?probe=1c9628e804) | Aug 15, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [12a6ae992a](https://linux-hardware.org/?probe=12a6ae992a) | Aug 14, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [846e1d6c9f](https://linux-hardware.org/?probe=846e1d6c9f) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 20RA004WUS     | Notebook    | [b140ac0aea](https://linux-hardware.org/?probe=b140ac0aea) | Aug 07, 2022 |
| Dell          | Precision M4700             | Notebook    | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [96645b0a94](https://linux-hardware.org/?probe=96645b0a94) | Aug 04, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [3f1e6ca5cb](https://linux-hardware.org/?probe=3f1e6ca5cb) | Jul 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [012b0c7fa9](https://linux-hardware.org/?probe=012b0c7fa9) | Jul 23, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9122678102](https://linux-hardware.org/?probe=9122678102) | Jul 21, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [e45f2cd5d8](https://linux-hardware.org/?probe=e45f2cd5d8) | Jul 20, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [69d676f7be](https://linux-hardware.org/?probe=69d676f7be) | Jul 12, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9d8195a435](https://linux-hardware.org/?probe=9d8195a435) | Jul 12, 2022 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [a42903b516](https://linux-hardware.org/?probe=a42903b516) | Jul 10, 2022 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [404e81318c](https://linux-hardware.org/?probe=404e81318c) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d0cfec8d80](https://linux-hardware.org/?probe=d0cfec8d80) | Jul 04, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [9b53e39bad](https://linux-hardware.org/?probe=9b53e39bad) | Jul 04, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [ac53d2f956](https://linux-hardware.org/?probe=ac53d2f956) | Jul 02, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9fd7dc8784](https://linux-hardware.org/?probe=9fd7dc8784) | Jul 02, 2022 |
| MSI           | MS-AE031                    | All in one  | [d6f4214361](https://linux-hardware.org/?probe=d6f4214361) | Jun 30, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [9eaa432fcd](https://linux-hardware.org/?probe=9eaa432fcd) | Jun 02, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [ae5664a81f](https://linux-hardware.org/?probe=ae5664a81f) | May 12, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [83ed9adfc1](https://linux-hardware.org/?probe=83ed9adfc1) | May 04, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [860d883e5b](https://linux-hardware.org/?probe=860d883e5b) | Apr 29, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [bce1bba9ff](https://linux-hardware.org/?probe=bce1bba9ff) | Apr 29, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [32cc2a24ac](https://linux-hardware.org/?probe=32cc2a24ac) | Apr 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [074f1f75dc](https://linux-hardware.org/?probe=074f1f75dc) | Apr 20, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b4ea114ce4](https://linux-hardware.org/?probe=b4ea114ce4) | Apr 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [656e8c50dd](https://linux-hardware.org/?probe=656e8c50dd) | Apr 13, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [c32c875fc6](https://linux-hardware.org/?probe=c32c875fc6) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| Dell          | Latitude E6330              | Notebook    | [1911200c56](https://linux-hardware.org/?probe=1911200c56) | Mar 23, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [fd3185704d](https://linux-hardware.org/?probe=fd3185704d) | Mar 21, 2022 |
| HP            | 0AA8h                       | Desktop     | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| Dell          | Inspiron 17-7778            | Notebook    | [bcc52b2596](https://linux-hardware.org/?probe=bcc52b2596) | Mar 17, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [f96e26bb9a](https://linux-hardware.org/?probe=f96e26bb9a) | Mar 08, 2022 |
| Dell          | OptiPlex 7020               | Desktop     | [ba82f9d852](https://linux-hardware.org/?probe=ba82f9d852) | Mar 01, 2022 |
| HP            | 0AA8h                       | Desktop     | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a1ecd8a3cb](https://linux-hardware.org/?probe=a1ecd8a3cb) | Feb 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [832b48c46d](https://linux-hardware.org/?probe=832b48c46d) | Feb 11, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [e7ce3f2f38](https://linux-hardware.org/?probe=e7ce3f2f38) | Feb 09, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [86dbaf1d07](https://linux-hardware.org/?probe=86dbaf1d07) | Jan 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [51e8a3a34d](https://linux-hardware.org/?probe=51e8a3a34d) | Dec 31, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [1b74edca8c](https://linux-hardware.org/?probe=1b74edca8c) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [9f1e770843](https://linux-hardware.org/?probe=9f1e770843) | Dec 22, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [464d10c41d](https://linux-hardware.org/?probe=464d10c41d) | Dec 22, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [7143ced3cd](https://linux-hardware.org/?probe=7143ced3cd) | Dec 20, 2021 |
| Dell          | 0R6JMP A00                  | Desktop     | [7bc4106877](https://linux-hardware.org/?probe=7bc4106877) | Dec 12, 2021 |
| Dell          | 0R6JMP A00                  | Desktop     | [2b3e03c89b](https://linux-hardware.org/?probe=2b3e03c89b) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| HP            | 1998                        | Desktop     | [7bc6ddebf4](https://linux-hardware.org/?probe=7bc6ddebf4) | Nov 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9af646fd14](https://linux-hardware.org/?probe=9af646fd14) | Nov 10, 2021 |
| ASRock        | Q1900M                      | Desktop     | [8482ae3a2f](https://linux-hardware.org/?probe=8482ae3a2f) | Nov 09, 2021 |
| HP            | 339A                        | Desktop     | [e2ce00d1ec](https://linux-hardware.org/?probe=e2ce00d1ec) | Nov 08, 2021 |
| Alienware     | 07W25T A00                  | Desktop     | [c08c87521f](https://linux-hardware.org/?probe=c08c87521f) | Nov 08, 2021 |
| HP            | ENVY Laptop 17m-bw0xxx      | Notebook    | [9ec292c9d9](https://linux-hardware.org/?probe=9ec292c9d9) | Oct 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [8649bba9b6](https://linux-hardware.org/?probe=8649bba9b6) | Oct 22, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [fede248f75](https://linux-hardware.org/?probe=fede248f75) | Oct 19, 2021 |
| HP            | ProBook 6450b               | Notebook    | [518e694864](https://linux-hardware.org/?probe=518e694864) | Oct 19, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [29c7fa76a8](https://linux-hardware.org/?probe=29c7fa76a8) | Oct 10, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [6818ec3abc](https://linux-hardware.org/?probe=6818ec3abc) | Oct 10, 2021 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [732c00f018](https://linux-hardware.org/?probe=732c00f018) | Oct 06, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [7ecda0a147](https://linux-hardware.org/?probe=7ecda0a147) | Sep 23, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [9ed2b3cf12](https://linux-hardware.org/?probe=9ed2b3cf12) | Sep 21, 2021 |
| GPU Compan... | GWTN156-9                   | Notebook    | [a9ac79c22a](https://linux-hardware.org/?probe=a9ac79c22a) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a96d28c504](https://linux-hardware.org/?probe=a96d28c504) | Sep 16, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [686eb55129](https://linux-hardware.org/?probe=686eb55129) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [d120a0016d](https://linux-hardware.org/?probe=d120a0016d) | Aug 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [9ad69ca6ad](https://linux-hardware.org/?probe=9ad69ca6ad) | Jul 27, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [75fd544183](https://linux-hardware.org/?probe=75fd544183) | Jul 26, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a3b055840b](https://linux-hardware.org/?probe=a3b055840b) | Jul 13, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [cbcf0ae65d](https://linux-hardware.org/?probe=cbcf0ae65d) | Jul 07, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [c3b8ac12be](https://linux-hardware.org/?probe=c3b8ac12be) | Jul 07, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3a88077121](https://linux-hardware.org/?probe=3a88077121) | Jul 07, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [17a65dfb0e](https://linux-hardware.org/?probe=17a65dfb0e) | Jul 06, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [5af810dc36](https://linux-hardware.org/?probe=5af810dc36) | Jul 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [675992d5f9](https://linux-hardware.org/?probe=675992d5f9) | Jul 04, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [4782df79ce](https://linux-hardware.org/?probe=4782df79ce) | Jul 02, 2021 |
| HP            | ProBook 6560b               | Notebook    | [806dfcb6f0](https://linux-hardware.org/?probe=806dfcb6f0) | Jul 01, 2021 |
| HP            | ProBook 6450b               | Notebook    | [a8689c5d60](https://linux-hardware.org/?probe=a8689c5d60) | Jun 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [fed4ef6298](https://linux-hardware.org/?probe=fed4ef6298) | Jun 23, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [14e1d81078](https://linux-hardware.org/?probe=14e1d81078) | Jun 23, 2021 |
| HP            | ProBook 6450b               | Notebook    | [b4c7a0fd32](https://linux-hardware.org/?probe=b4c7a0fd32) | Jun 21, 2021 |
| Pegatron      | 2ACD                        | Desktop     | [fd757c14ce](https://linux-hardware.org/?probe=fd757c14ce) | Jun 13, 2021 |
| HP            | 1998                        | Desktop     | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [95fdac8e1c](https://linux-hardware.org/?probe=95fdac8e1c) | Jun 08, 2021 |
| HP            | 1998                        | Desktop     | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| HP            | 1998                        | Desktop     | [4c3248677a](https://linux-hardware.org/?probe=4c3248677a) | May 25, 2021 |
| HP            | 1998                        | Desktop     | [9239b61815](https://linux-hardware.org/?probe=9239b61815) | May 25, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [6b2ff5fb12](https://linux-hardware.org/?probe=6b2ff5fb12) | May 25, 2021 |
| HP            | 1998                        | Desktop     | [639725c8af](https://linux-hardware.org/?probe=639725c8af) | May 24, 2021 |
| HP            | ENVY dv7                    | Notebook    | [651a68adc6](https://linux-hardware.org/?probe=651a68adc6) | May 24, 2021 |
| HP            | 339A                        | Desktop     | [ac11f05a1a](https://linux-hardware.org/?probe=ac11f05a1a) | May 21, 2021 |
| Intel         | SKYBAY                      | Desktop     | [9bc7ab87d1](https://linux-hardware.org/?probe=9bc7ab87d1) | May 19, 2021 |
| ASRock        | Q1900M                      | Desktop     | [7c778b5654](https://linux-hardware.org/?probe=7c778b5654) | May 02, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| HP            | 1998                        | Desktop     | [7442c54767](https://linux-hardware.org/?probe=7442c54767) | Apr 29, 2021 |
| HP            | 1998                        | Desktop     | [ec0fdacf3a](https://linux-hardware.org/?probe=ec0fdacf3a) | Apr 12, 2021 |
| HP            | 1998                        | Desktop     | [c395021e6a](https://linux-hardware.org/?probe=c395021e6a) | Apr 12, 2021 |
| Lenovo        | ThinkPad T410 2516ADU       | Notebook    | [5feb962d24](https://linux-hardware.org/?probe=5feb962d24) | Apr 07, 2021 |
| Intel         | SKYBAY                      | Desktop     | [472818e347](https://linux-hardware.org/?probe=472818e347) | Apr 04, 2021 |
| HP            | 1998                        | Desktop     | [f515fbf660](https://linux-hardware.org/?probe=f515fbf660) | Apr 01, 2021 |
| HP            | 1998                        | Desktop     | [3bc0a0dcb6](https://linux-hardware.org/?probe=3bc0a0dcb6) | Mar 20, 2021 |
| HP            | 1998                        | Desktop     | [a10d91fc1b](https://linux-hardware.org/?probe=a10d91fc1b) | Mar 20, 2021 |
| Intel         | SKYBAY                      | Desktop     | [5ab0183bc4](https://linux-hardware.org/?probe=5ab0183bc4) | Mar 18, 2021 |
| Intel         | SKYBAY                      | Desktop     | [ecefc99ed5](https://linux-hardware.org/?probe=ecefc99ed5) | Mar 14, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [332f4238da](https://linux-hardware.org/?probe=332f4238da) | Mar 09, 2021 |
| Acer          | AAHD3.VC                    | Desktop     | [775057eb07](https://linux-hardware.org/?probe=775057eb07) | Feb 20, 2021 |
| Acer          | AAHD3.VC                    | Desktop     | [b11309575f](https://linux-hardware.org/?probe=b11309575f) | Feb 19, 2021 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [48d2054858](https://linux-hardware.org/?probe=48d2054858) | Feb 16, 2021 |
| Dell          | 0DFRFW A00                  | Desktop     | [093c47fb9c](https://linux-hardware.org/?probe=093c47fb9c) | Feb 13, 2021 |
| ASRock        | Q1900M                      | Desktop     | [d4372897b8](https://linux-hardware.org/?probe=d4372897b8) | Feb 13, 2021 |
| MSI           | H81M-P33                    | Desktop     | [190f14bae7](https://linux-hardware.org/?probe=190f14bae7) | Feb 13, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [2140e64244](https://linux-hardware.org/?probe=2140e64244) | Feb 13, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [81a3e9faea](https://linux-hardware.org/?probe=81a3e9faea) | Feb 11, 2021 |
| HP            | 18E4                        | Desktop     | [db6eb1d366](https://linux-hardware.org/?probe=db6eb1d366) | Feb 05, 2021 |
| HP            | 18E4                        | Desktop     | [bad5f5110c](https://linux-hardware.org/?probe=bad5f5110c) | Feb 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [63a2a56eda](https://linux-hardware.org/?probe=63a2a56eda) | Jan 25, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [b2513f813d](https://linux-hardware.org/?probe=b2513f813d) | Jan 16, 2021 |
| ASUSTek       | K53E                        | Notebook    | [0523ff890c](https://linux-hardware.org/?probe=0523ff890c) | Jan 15, 2021 |
| HP            | 18E4                        | Desktop     | [729391b32e](https://linux-hardware.org/?probe=729391b32e) | Jan 08, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [5780c56d1e](https://linux-hardware.org/?probe=5780c56d1e) | Jan 06, 2021 |
| Toshiba       | Satellite C55-C             | Notebook    | [ecaae6f562](https://linux-hardware.org/?probe=ecaae6f562) | Jan 05, 2021 |
| AMI           | Intel                       | Notebook    | [0ea3da73ad](https://linux-hardware.org/?probe=0ea3da73ad) | Jan 04, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| Lenovo        | ThinkCentre M58p 6136A66    | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [5e4b418568](https://linux-hardware.org/?probe=5e4b418568) | Dec 19, 2020 |
| AZW           | GT-R                        | Notebook    | [19b47cf9f6](https://linux-hardware.org/?probe=19b47cf9f6) | Dec 16, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [ba371f8d43](https://linux-hardware.org/?probe=ba371f8d43) | Dec 07, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [646f020b0d](https://linux-hardware.org/?probe=646f020b0d) | Nov 27, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [9464486b83](https://linux-hardware.org/?probe=9464486b83) | Nov 22, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [844bb428a9](https://linux-hardware.org/?probe=844bb428a9) | Nov 22, 2020 |
| MSI           | MS-B1711                    | Desktop     | [8d69ecec16](https://linux-hardware.org/?probe=8d69ecec16) | Nov 17, 2020 |
| MSI           | MS-B1711                    | Desktop     | [958741b7b6](https://linux-hardware.org/?probe=958741b7b6) | Nov 17, 2020 |
| MSI           | MS-B1711                    | Desktop     | [3c327ae485](https://linux-hardware.org/?probe=3c327ae485) | Nov 17, 2020 |
| CompuLab      | fit-PC3                     | Mini pc     | [2e92dc00d4](https://linux-hardware.org/?probe=2e92dc00d4) | Nov 12, 2020 |
| Dell          | Latitude E6410              | Notebook    | [d188c9653d](https://linux-hardware.org/?probe=d188c9653d) | Nov 07, 2020 |
| Dell          | Latitude E6410              | Notebook    | [caf34f9e21](https://linux-hardware.org/?probe=caf34f9e21) | Nov 02, 2020 |
| MSI           | MS-B1711                    | Desktop     | [26c2dcf112](https://linux-hardware.org/?probe=26c2dcf112) | Nov 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [62ebca752a](https://linux-hardware.org/?probe=62ebca752a) | Oct 31, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [362d74125d](https://linux-hardware.org/?probe=362d74125d) | Oct 31, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [f7ec0211fb](https://linux-hardware.org/?probe=f7ec0211fb) | Oct 27, 2020 |
| ASRock        | Q1900M                      | Desktop     | [72cddfd9ae](https://linux-hardware.org/?probe=72cddfd9ae) | Oct 24, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [9d734dee6e](https://linux-hardware.org/?probe=9d734dee6e) | Sep 30, 2020 |
| HP            | ENVY dv7                    | Notebook    | [e5448099f1](https://linux-hardware.org/?probe=e5448099f1) | Sep 27, 2020 |
| HP            | 339A                        | Desktop     | [47db0521b7](https://linux-hardware.org/?probe=47db0521b7) | Sep 23, 2020 |
| HP            | 339A                        | Desktop     | [51cec5b6f8](https://linux-hardware.org/?probe=51cec5b6f8) | Sep 23, 2020 |
| HP            | ENVY dv7                    | Notebook    | [a027a185e5](https://linux-hardware.org/?probe=a027a185e5) | Sep 23, 2020 |
| HP            | ENVY dv7                    | Notebook    | [ff87d18b2b](https://linux-hardware.org/?probe=ff87d18b2b) | Sep 21, 2020 |
| HP            | 339A                        | Desktop     | [37cfc48ef8](https://linux-hardware.org/?probe=37cfc48ef8) | Sep 21, 2020 |
| HP            | 339A                        | Desktop     | [254f23a364](https://linux-hardware.org/?probe=254f23a364) | Sep 21, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| HP            | 18E4                        | Desktop     | [277593bde6](https://linux-hardware.org/?probe=277593bde6) | Aug 07, 2020 |
| Acer          | Swift SF314-51              | Notebook    | [ff4068d40b](https://linux-hardware.org/?probe=ff4068d40b) | Jul 31, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [25ca74bc56](https://linux-hardware.org/?probe=25ca74bc56) | Jul 24, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [478381d890](https://linux-hardware.org/?probe=478381d890) | Jul 12, 2020 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [f9271f6dae](https://linux-hardware.org/?probe=f9271f6dae) | Jul 09, 2020 |
| MSI           | Z370-A PRO                  | Desktop     | [f8629928a6](https://linux-hardware.org/?probe=f8629928a6) | Jun 18, 2020 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9aaeabab3d](https://linux-hardware.org/?probe=9aaeabab3d) | Jun 18, 2020 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d161c397ca](https://linux-hardware.org/?probe=d161c397ca) | Jun 14, 2020 |
| HP            | ENVY dv7                    | Notebook    | [2ae56a2828](https://linux-hardware.org/?probe=2ae56a2828) | May 24, 2020 |
| HP            | Compaq nc6400 (RB516UT#A... | Notebook    | [f950094ff1](https://linux-hardware.org/?probe=f950094ff1) | May 21, 2020 |
| Sony          | VPCEA36FX                   | Notebook    | [98ba3a8ad5](https://linux-hardware.org/?probe=98ba3a8ad5) | May 17, 2020 |
| Sony          | VPCEA36FX                   | Notebook    | [572157356f](https://linux-hardware.org/?probe=572157356f) | May 13, 2020 |
| HP            | 18E4                        | Desktop     | [1fe1707854](https://linux-hardware.org/?probe=1fe1707854) | May 07, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [8805cd4168](https://linux-hardware.org/?probe=8805cd4168) | Apr 16, 2020 |
| Dell          | 0M017G A00                  | Desktop     | [e8b9eefb82](https://linux-hardware.org/?probe=e8b9eefb82) | Apr 13, 2020 |
| HP            | ENVY dv7                    | Notebook    | [e2de1ae596](https://linux-hardware.org/?probe=e2de1ae596) | Apr 04, 2020 |
| HP            | ENVY dv7                    | Notebook    | [97ae3dc919](https://linux-hardware.org/?probe=97ae3dc919) | Mar 14, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [44caca0bb1](https://linux-hardware.org/?probe=44caca0bb1) | Mar 12, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [3d3261ccc3](https://linux-hardware.org/?probe=3d3261ccc3) | Mar 09, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [c0f180f342](https://linux-hardware.org/?probe=c0f180f342) | Mar 07, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [4ac0a3b1fe](https://linux-hardware.org/?probe=4ac0a3b1fe) | Mar 06, 2020 |
| ASRock        | G31M-S                      | Desktop     | [a2582aaec1](https://linux-hardware.org/?probe=a2582aaec1) | Mar 06, 2020 |
| ASRock        | G31M-S                      | Desktop     | [a63cd159a1](https://linux-hardware.org/?probe=a63cd159a1) | Mar 06, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [aa32ea3cb7](https://linux-hardware.org/?probe=aa32ea3cb7) | Mar 05, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [efa77a90cb](https://linux-hardware.org/?probe=efa77a90cb) | Mar 01, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [aca2204df4](https://linux-hardware.org/?probe=aca2204df4) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [40a8750e54](https://linux-hardware.org/?probe=40a8750e54) | Feb 28, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [399d92cf32](https://linux-hardware.org/?probe=399d92cf32) | Feb 28, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [7c094d733b](https://linux-hardware.org/?probe=7c094d733b) | Feb 28, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [ddebe02bcd](https://linux-hardware.org/?probe=ddebe02bcd) | Feb 28, 2020 |
| HP            | Notebook                    | Notebook    | [80f2a12798](https://linux-hardware.org/?probe=80f2a12798) | Feb 28, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [132413f9bd](https://linux-hardware.org/?probe=132413f9bd) | Feb 21, 2020 |
| HP            | 18E4                        | Desktop     | [ee3dae8f72](https://linux-hardware.org/?probe=ee3dae8f72) | Feb 17, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fa684e430c](https://linux-hardware.org/?probe=fa684e430c) | Feb 13, 2020 |
| MSI           | B150 PC MATE                | Desktop     | [ed98074061](https://linux-hardware.org/?probe=ed98074061) | Oct 08, 2019 |
| ASRock        | G31M-S                      | Desktop     | [d1f69377d4](https://linux-hardware.org/?probe=d1f69377d4) | Aug 18, 2019 |
| ASRock        | G31M-S                      | Desktop     | [595867810d](https://linux-hardware.org/?probe=595867810d) | Aug 18, 2019 |
| ASRock        | G31M-S                      | Desktop     | [556d0f2ca6](https://linux-hardware.org/?probe=556d0f2ca6) | Jun 06, 2019 |
| ASRock        | 945GCM-S                    | Desktop     | [d4ea4c5cb6](https://linux-hardware.org/?probe=d4ea4c5cb6) | May 04, 2019 |
| HP            | 18E4                        | Desktop     | [36f9656af0](https://linux-hardware.org/?probe=36f9656af0) | Feb 15, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [d24fc7f682](https://linux-hardware.org/?probe=d24fc7f682) | Jan 30, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [525707b787](https://linux-hardware.org/?probe=525707b787) | Jan 21, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [a7616fb055](https://linux-hardware.org/?probe=a7616fb055) | Jan 21, 2019 |
| HP            | 18E4                        | Desktop     | [c6cf9c7817](https://linux-hardware.org/?probe=c6cf9c7817) | Jan 04, 2019 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [85398272dc](https://linux-hardware.org/?probe=85398272dc) | Dec 03, 2018 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [10a5b1559d](https://linux-hardware.org/?probe=10a5b1559d) | Dec 03, 2018 |
| Dell          | Inspiron MP061              | Notebook    | [113fc7a00d](https://linux-hardware.org/?probe=113fc7a00d) | Jul 15, 2018 |
| ASRock        | G31M-S                      | Desktop     | [82229858ec](https://linux-hardware.org/?probe=82229858ec) | Jun 15, 2018 |
| ASRock        | G31M-S                      | Desktop     | [90f397422e](https://linux-hardware.org/?probe=90f397422e) | Jun 15, 2018 |
| ASRock        | 945GCM-S                    | Desktop     | [c7cbed362d](https://linux-hardware.org/?probe=c7cbed362d) | May 27, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 22        | 12.87%  |
| Ubuntu 18.04                 | 11        | 6.43%   |
| Ubuntu 22.04                 | 10        | 5.85%   |
| OpenMandriva 4.2             | 6         | 3.51%   |
| OpenMandriva 4.3             | 5         | 2.92%   |
| Zorin 16                     | 4         | 2.34%   |
| Ubuntu 21.10                 | 4         | 2.34%   |
| Ubuntu 20.10                 | 4         | 2.34%   |
| OpenMandriva 23.03           | 4         | 2.34%   |
| Manjaro                      | 4         | 2.34%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.75%   |
| Linux Mint 20.1              | 3         | 1.75%   |
| Linux Mint 19.3              | 3         | 1.75%   |
| KDE neon 20.04               | 3         | 1.75%   |
| Fedora 38                    | 3         | 1.75%   |
| Fedora 36                    | 3         | 1.75%   |
| BlackPanther 18.1            | 3         | 1.75%   |
| Zorin 15                     | 2         | 1.17%   |
| Xubuntu 20.04                | 2         | 1.17%   |
| Ubuntu 22.10                 | 2         | 1.17%   |
| Ubuntu 19.10                 | 2         | 1.17%   |
| ROSA R11                     | 2         | 1.17%   |
| ROSA R10                     | 2         | 1.17%   |
| OpenMandriva 4.90            | 2         | 1.17%   |
| OpenMandriva 23.01           | 2         | 1.17%   |
| Lubuntu 20.04                | 2         | 1.17%   |
| LMDE 4                       | 2         | 1.17%   |
| Linux Mint 21                | 2         | 1.17%   |
| Linux Mint 20.3              | 2         | 1.17%   |
| Linux Mint 20.2              | 2         | 1.17%   |
| Linux Mint 20                | 2         | 1.17%   |
| KDE neon 22.04               | 2         | 1.17%   |
| Garuda Linux                 | 2         | 1.17%   |
| Fedora 37                    | 2         | 1.17%   |
| Debian 11                    | 2         | 1.17%   |
| ArcoLinux Rolling            | 2         | 1.17%   |
| Arch Rolling                 | 2         | 1.17%   |
| Xubuntu 20.10                | 1         | 0.58%   |
| Ubuntu Unity 20.04           | 1         | 0.58%   |
| Ubuntu MATE 20.04            | 1         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 51        | 32.08%  |
| OpenMandriva  | 19        | 11.95%  |
| Linux Mint    | 12        | 7.55%   |
| Fedora        | 9         | 5.66%   |
| Zorin         | 6         | 3.77%   |
| Pop!_OS       | 6         | 3.77%   |
| Manjaro       | 5         | 3.14%   |
| KDE neon      | 5         | 3.14%   |
| ROSA          | 4         | 2.52%   |
| openSUSE      | 4         | 2.52%   |
| Debian        | 4         | 2.52%   |
| Xubuntu       | 3         | 1.89%   |
| BlackPanther  | 3         | 1.89%   |
| Arch          | 3         | 1.89%   |
| Ubuntu Budgie | 2         | 1.26%   |
| Parrot        | 2         | 1.26%   |
| Lubuntu       | 2         | 1.26%   |
| LMDE          | 2         | 1.26%   |
| Garuda Linux  | 2         | 1.26%   |
| Endless       | 2         | 1.26%   |
| CentOS        | 2         | 1.26%   |
| ArcoLinux     | 2         | 1.26%   |
| Ubuntu Unity  | 1         | 0.63%   |
| Ubuntu MATE   | 1         | 0.63%   |
| SteamOS       | 1         | 0.63%   |
| Peppermint    | 1         | 0.63%   |
| LinuxFX       | 1         | 0.63%   |
| EndeavourOS   | 1         | 0.63%   |
| Elementary    | 1         | 0.63%   |
| Devuan        | 1         | 0.63%   |
| AlmaLinux     | 1         | 0.63%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 6         | 2.96%   |
| 5.16.7-desktop-1omv4003        | 5         | 2.46%   |
| 6.2.6-desktop-1omv2390         | 4         | 1.97%   |
| 5.4.0-58-generic               | 4         | 1.97%   |
| 5.8.0-59-generic               | 3         | 1.48%   |
| 5.11.0-38-generic              | 3         | 1.48%   |
| 4.15.0-43-generic              | 3         | 1.48%   |
| 6.3.6-200.fc38.x86_64          | 2         | 0.99%   |
| 6.2.0-31-generic               | 2         | 0.99%   |
| 6.2.0-26-generic               | 2         | 0.99%   |
| 6.1.1-desktop-1omv2290         | 2         | 0.99%   |
| 5.8.18-1-MANJARO               | 2         | 0.99%   |
| 5.8.0-55-generic               | 2         | 0.99%   |
| 5.8.0-45-generic               | 2         | 0.99%   |
| 5.4.0-73-generic               | 2         | 0.99%   |
| 5.4.0-72-generic               | 2         | 0.99%   |
| 5.4.0-52-generic               | 2         | 0.99%   |
| 5.4.0-48-generic               | 2         | 0.99%   |
| 5.4.0-47-generic               | 2         | 0.99%   |
| 5.4.0-40-generic               | 2         | 0.99%   |
| 5.4.0-109-generic              | 2         | 0.99%   |
| 5.3.0-41-generic               | 2         | 0.99%   |
| 5.3.0-28-generic               | 2         | 0.99%   |
| 5.19.0-42-generic              | 2         | 0.99%   |
| 5.19.0-38-generic              | 2         | 0.99%   |
| 5.18.15-1-default              | 2         | 0.99%   |
| 5.18.12-desktop-3omv4090       | 2         | 0.99%   |
| 5.15.0-58-generic              | 2         | 0.99%   |
| 5.15.0-46-generic              | 2         | 0.99%   |
| 5.15.0-40-generic              | 2         | 0.99%   |
| 5.15.0-25-generic              | 2         | 0.99%   |
| 5.13.0-40-generic              | 2         | 0.99%   |
| 5.13.0-39-generic              | 2         | 0.99%   |
| 5.13.0-35-generic              | 2         | 0.99%   |
| 5.13.0-30-generic              | 2         | 0.99%   |
| 5.11.0-41-generic              | 2         | 0.99%   |
| 5.11.0-27-generic              | 2         | 0.99%   |
| 5.10.0-19-amd64                | 2         | 0.99%   |
| 4.18.16-desktop-1bP            | 2         | 0.99%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2         | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 17.24%  |
| 5.8.0   | 14        | 8.05%   |
| 5.13.0  | 12        | 6.9%    |
| 4.15.0  | 10        | 5.75%   |
| 5.15.0  | 9         | 5.17%   |
| 5.11.0  | 9         | 5.17%   |
| 5.19.0  | 8         | 4.6%    |
| 5.3.0   | 6         | 3.45%   |
| 5.10.14 | 6         | 3.45%   |
| 6.2.6   | 5         | 2.87%   |
| 6.2.0   | 5         | 2.87%   |
| 5.16.7  | 5         | 2.87%   |
| 5.10.0  | 4         | 2.3%    |
| 4.19.0  | 3         | 1.72%   |
| 4.18.0  | 3         | 1.72%   |
| 6.3.6   | 2         | 1.15%   |
| 6.1.1   | 2         | 1.15%   |
| 5.9.16  | 2         | 1.15%   |
| 5.8.18  | 2         | 1.15%   |
| 5.18.15 | 2         | 1.15%   |
| 5.18.12 | 2         | 1.15%   |
| 5.14.0  | 2         | 1.15%   |
| 4.9.60  | 2         | 1.15%   |
| 4.18.16 | 2         | 1.15%   |
| 6.2.9   | 1         | 0.57%   |
| 6.2.8   | 1         | 0.57%   |
| 6.2.15  | 1         | 0.57%   |
| 6.2.12  | 1         | 0.57%   |
| 5.9.1   | 1         | 0.57%   |
| 5.8.5   | 1         | 0.57%   |
| 5.8.14  | 1         | 0.57%   |
| 5.6.14  | 1         | 0.57%   |
| 5.3.6   | 1         | 0.57%   |
| 5.3.18  | 1         | 0.57%   |
| 5.19.7  | 1         | 0.57%   |
| 5.19.12 | 1         | 0.57%   |
| 5.18.9  | 1         | 0.57%   |
| 5.18.6  | 1         | 0.57%   |
| 5.18.5  | 1         | 0.57%   |
| 5.18.0  | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 17.65%  |
| 5.8     | 18        | 10.59%  |
| 6.2     | 14        | 8.24%   |
| 5.13    | 13        | 7.65%   |
| 5.15    | 12        | 7.06%   |
| 5.19    | 10        | 5.88%   |
| 5.11    | 10        | 5.88%   |
| 5.10    | 10        | 5.88%   |
| 4.15    | 10        | 5.88%   |
| 5.3     | 8         | 4.71%   |
| 5.18    | 6         | 3.53%   |
| 5.16    | 5         | 2.94%   |
| 4.9     | 4         | 2.35%   |
| 4.18    | 4         | 2.35%   |
| 5.9     | 3         | 1.76%   |
| 5.14    | 3         | 1.76%   |
| 4.19    | 3         | 1.76%   |
| 6.3     | 2         | 1.18%   |
| 6.1     | 2         | 1.18%   |
| 5.6     | 1         | 0.59%   |
| 5.17    | 1         | 0.59%   |
| 5.12    | 1         | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 133       | 97.08%  |
| i686    | 2         | 1.46%   |
| aarch64 | 2         | 1.46%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 73        | 47.1%   |
| KDE5          | 35        | 22.58%  |
| X-Cinnamon    | 10        | 6.45%   |
| XFCE          | 7         | 4.52%   |
| MATE          | 6         | 3.87%   |
| Unknown       | 6         | 3.87%   |
| Budgie        | 3         | 1.94%   |
| LXQt          | 2         | 1.29%   |
| LXDE          | 2         | 1.29%   |
| KDE4          | 2         | 1.29%   |
| KDE           | 2         | 1.29%   |
| i3            | 2         | 1.29%   |
| Unity         | 1         | 0.65%   |
| Pantheon      | 1         | 0.65%   |
| GNOME Classic | 1         | 0.65%   |
| Deepin        | 1         | 0.65%   |
| Cinnamon      | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 117       | 82.39%  |
| Wayland | 24        | 16.9%   |
| Unknown | 1         | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 88        | 57.52%  |
| SDDM    | 24        | 15.69%  |
| GDM3    | 21        | 13.73%  |
| GDM     | 9         | 5.88%   |
| LightDM | 6         | 3.92%   |
| TDM     | 3         | 1.96%   |
| KDM     | 2         | 1.31%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 117       | 84.17%  |
| Unknown | 12        | 8.63%   |
| es_PR   | 7         | 5.04%   |
| C       | 2         | 1.44%   |
| es_ES   | 1         | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 79        | 55.24%  |
| EFI  | 64        | 44.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 102       | 68.46%  |
| Overlay | 19        | 12.75%  |
| Btrfs   | 14        | 9.4%    |
| Tmpfs   | 5         | 3.36%   |
| Unknown | 5         | 3.36%   |
| Xfs     | 3         | 2.01%   |
| Zfs     | 1         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 98        | 65.33%  |
| GPT     | 41        | 27.33%  |
| MBR     | 11        | 7.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 82.19%  |
| Yes       | 26        | 17.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 110       | 75.34%  |
| Yes       | 36        | 24.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 27        | 19.71%  |
| Dell                    | 23        | 16.79%  |
| Lenovo                  | 12        | 8.76%   |
| ASUSTek Computer        | 12        | 8.76%   |
| Gigabyte Technology     | 10        | 7.3%    |
| ASRock                  | 10        | 7.3%    |
| MSI                     | 8         | 5.84%   |
| Apple                   | 5         | 3.65%   |
| Acer                    | 5         | 3.65%   |
| Toshiba                 | 3         | 2.19%   |
| Sony                    | 3         | 2.19%   |
| Intel                   | 3         | 2.19%   |
| Raspberry Pi Foundation | 2         | 1.46%   |
| GPU Company             | 2         | 1.46%   |
| Gateway                 | 2         | 1.46%   |
| Valve                   | 1         | 0.73%   |
| TUXEDO                  | 1         | 0.73%   |
| Pegatron                | 1         | 0.73%   |
| Microsoft               | 1         | 0.73%   |
| ECS                     | 1         | 0.73%   |
| CompuLab                | 1         | 0.73%   |
| AZW                     | 1         | 0.73%   |
| AMI                     | 1         | 0.73%   |
| Alienware               | 1         | 0.73%   |
| Acidanthera             | 1         | 0.73%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel SKYBAY                             | 3         | 2.19%   |
| Dell Vostro 3550                         | 3         | 2.19%   |
| RPi Raspberry Pi                         | 2         | 1.46%   |
| MSI Cubi N 8GL (MS-B171)                 | 2         | 1.46%   |
| ASRock Q1900M                            | 2         | 1.46%   |
| ASRock 945GCM-S                          | 2         | 1.46%   |
| Valve Jupiter                            | 1         | 0.73%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.73%   |
| Toshiba Satellite P755                   | 1         | 0.73%   |
| Toshiba Satellite L655                   | 1         | 0.73%   |
| Toshiba Satellite C55-C                  | 1         | 0.73%   |
| Sony VPCEA36FX                           | 1         | 0.73%   |
| Sony VGN-CS320J                          | 1         | 0.73%   |
| Sony SVE11113FXW                         | 1         | 0.73%   |
| Pegatron QW716AA#ABA                     | 1         | 0.73%   |
| MSI US PIO PRO AP241                     | 1         | 0.73%   |
| MSI MS-7B48                              | 1         | 0.73%   |
| MSI MS-7971                              | 1         | 0.73%   |
| MSI MS-7817                              | 1         | 0.73%   |
| MSI GF65 Thin 10SDR                      | 1         | 0.73%   |
| MSI Cubi N JSL (MS-B0A1)                 | 1         | 0.73%   |
| Microsoft Surface Pro 3                  | 1         | 0.73%   |
| Lenovo Yoga 910-13IKB 80VF               | 1         | 0.73%   |
| Lenovo Yoga 900-13ISK 80MK               | 1         | 0.73%   |
| Lenovo Y50-70 Touch 20349                | 1         | 0.73%   |
| Lenovo V14-ARE 82DQ                      | 1         | 0.73%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US | 1         | 0.73%   |
| Lenovo ThinkPad T410 2516ADU             | 1         | 0.73%   |
| Lenovo ThinkPad E14 20RA004WUS           | 1         | 0.73%   |
| Lenovo ThinkCentre M91p 7033CG1          | 1         | 0.73%   |
| Lenovo ThinkCentre M58p 6136A66          | 1         | 0.73%   |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 0.73%   |
| Lenovo IdeaCentre 510A-15ARR 90J0000PUS  | 1         | 0.73%   |
| Lenovo G50-45 80E3                       | 1         | 0.73%   |
| HP Stream Laptop 14-CB1xxx               | 1         | 0.73%   |
| HP ProBook 6560b                         | 1         | 0.73%   |
| HP ProBook 6450b                         | 1         | 0.73%   |
| HP ProBook 450 G5                        | 1         | 0.73%   |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 0.73%   |
| HP Pavilion Laptop 15-cs2xxx             | 1         | 0.73%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 7         | 5.11%   |
| HP Pavilion          | 5         | 3.65%   |
| HP Compaq            | 5         | 3.65%   |
| HP Laptop            | 4         | 2.92%   |
| Dell OptiPlex        | 4         | 2.92%   |
| Dell Latitude        | 4         | 2.92%   |
| Toshiba Satellite    | 3         | 2.19%   |
| MSI Cubi             | 3         | 2.19%   |
| Lenovo ThinkPad      | 3         | 2.19%   |
| Intel SKYBAY         | 3         | 2.19%   |
| HP ProBook           | 3         | 2.19%   |
| HP ENVY              | 3         | 2.19%   |
| HP EliteDesk         | 3         | 2.19%   |
| Dell Vostro          | 3         | 2.19%   |
| ASUS ROG             | 3         | 2.19%   |
| Acer Aspire          | 3         | 2.19%   |
| RPi Raspberry        | 2         | 1.46%   |
| Lenovo Yoga          | 2         | 1.46%   |
| Lenovo ThinkCentre   | 2         | 1.46%   |
| Gigabyte X570        | 2         | 1.46%   |
| ASUS TUF             | 2         | 1.46%   |
| ASRock Q1900M        | 2         | 1.46%   |
| ASRock B450M-HDV     | 2         | 1.46%   |
| ASRock 945GCM-S      | 2         | 1.46%   |
| Acer Swift           | 2         | 1.46%   |
| Valve Jupiter        | 1         | 0.73%   |
| TUXEDO Aura          | 1         | 0.73%   |
| Sony VPCEA36FX       | 1         | 0.73%   |
| Sony VGN-CS320J      | 1         | 0.73%   |
| Sony SVE11113FXW     | 1         | 0.73%   |
| Pegatron QW716AA#ABA | 1         | 0.73%   |
| MSI US               | 1         | 0.73%   |
| MSI MS-7B48          | 1         | 0.73%   |
| MSI MS-7971          | 1         | 0.73%   |
| MSI MS-7817          | 1         | 0.73%   |
| MSI GF65             | 1         | 0.73%   |
| Microsoft Surface    | 1         | 0.73%   |
| Lenovo Y50-70        | 1         | 0.73%   |
| Lenovo V14-ARE       | 1         | 0.73%   |
| Lenovo IdeaPad       | 1         | 0.73%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 19        | 13.87%  |
| 2019    | 17        | 12.41%  |
| 2011    | 14        | 10.22%  |
| 2020    | 12        | 8.76%   |
| 2014    | 11        | 8.03%   |
| 2012    | 9         | 6.57%   |
| 2016    | 8         | 5.84%   |
| 2021    | 7         | 5.11%   |
| 2015    | 7         | 5.11%   |
| 2008    | 7         | 5.11%   |
| 2013    | 5         | 3.65%   |
| 2010    | 5         | 3.65%   |
| 2017    | 4         | 2.92%   |
| 2009    | 4         | 2.92%   |
| 2022    | 2         | 1.46%   |
| 2006    | 2         | 1.46%   |
| Unknown | 2         | 1.46%   |
| 2007    | 1         | 0.73%   |
| 2005    | 1         | 0.73%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 69        | 50.36%  |
| Desktop        | 59        | 43.07%  |
| All in one     | 4         | 2.92%   |
| System on chip | 2         | 1.46%   |
| Tablet         | 1         | 0.73%   |
| Convertible    | 1         | 0.73%   |
| Mini pc        | 1         | 0.73%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 129       | 93.48%  |
| Enabled  | 9         | 6.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 137       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 45        | 30.82%  |
| 3.01-4.0    | 28        | 19.18%  |
| 8.01-16.0   | 27        | 18.49%  |
| 16.01-24.0  | 25        | 17.12%  |
| 32.01-64.0  | 8         | 5.48%   |
| 24.01-32.0  | 5         | 3.42%   |
| 1.01-2.0    | 5         | 3.42%   |
| 64.01-256.0 | 2         | 1.37%   |
| 0.51-1.0    | 1         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 74        | 44.05%  |
| 2.01-3.0  | 36        | 21.43%  |
| 3.01-4.0  | 24        | 14.29%  |
| 4.01-8.0  | 21        | 12.5%   |
| 0.51-1.0  | 10        | 5.95%   |
| 8.01-16.0 | 3         | 1.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 87        | 59.18%  |
| 2      | 32        | 21.77%  |
| 3      | 18        | 12.24%  |
| 4      | 5         | 3.4%    |
| 5      | 2         | 1.36%   |
| 0      | 2         | 1.36%   |
| 6      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 57.55%  |
| Yes       | 59        | 42.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 84.67%  |
| No        | 21        | 15.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 78.42%  |
| No        | 30        | 21.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 61.7%   |
| No        | 54        | 38.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Puerto Rico | 137       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San Juan      | 62        | 41.06%  |
| Bayamón      | 25        | 16.56%  |
| Carolina      | 10        | 6.62%   |
| Ponce         | 5         | 3.31%   |
| Caguas        | 5         | 3.31%   |
| Cayey         | 4         | 2.65%   |
| San Sebastian | 3         | 1.99%   |
| Lares         | 3         | 1.99%   |
| Aguadilla     | 3         | 1.99%   |
| Vega Alta     | 2         | 1.32%   |
| Sabana Grande | 2         | 1.32%   |
| Rio Grande    | 2         | 1.32%   |
| Mayagüez     | 2         | 1.32%   |
| Guayama       | 2         | 1.32%   |
| Dorado        | 2         | 1.32%   |
| Arecibo       | 2         | 1.32%   |
| Yauco         | 1         | 0.66%   |
| Santa Isabel  | 1         | 0.66%   |
| Patillas      | 1         | 0.66%   |
| Morovis       | 1         | 0.66%   |
| Maunabo       | 1         | 0.66%   |
| Las Piedras   | 1         | 0.66%   |
| Humacao       | 1         | 0.66%   |
| Hatillo       | 1         | 0.66%   |
| Gurabo        | 1         | 0.66%   |
| Guaynabo      | 1         | 0.66%   |
| Garrochales   | 1         | 0.66%   |
| Fajardo       | 1         | 0.66%   |
| Ensenada      | 1         | 0.66%   |
| Coamo         | 1         | 0.66%   |
| Catano        | 1         | 0.66%   |
| Cabo Rojo     | 1         | 0.66%   |
| Barceloneta   | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 37        | 78     | 18.5%   |
| Seagate                     | 24        | 45     | 12%     |
| Toshiba                     | 18        | 23     | 9%      |
| Samsung Electronics         | 14        | 24     | 7%      |
| Hitachi                     | 12        | 30     | 6%      |
| Crucial                     | 11        | 22     | 5.5%    |
| Unknown                     | 9         | 16     | 4.5%    |
| SanDisk                     | 9         | 9      | 4.5%    |
| SK hynix                    | 7         | 9      | 3.5%    |
| China                       | 6         | 9      | 3%      |
| A-DATA Technology           | 5         | 12     | 2.5%    |
| TDAS                        | 3         | 13     | 1.5%    |
| Silicon Motion              | 3         | 3      | 1.5%    |
| Micron/Crucial Technology   | 3         | 4      | 1.5%    |
| Kingston                    | 3         | 4      | 1.5%    |
| Intel                       | 3         | 4      | 1.5%    |
| External                    | 3         | 10     | 1.5%    |
| SPCC                        | 2         | 2      | 1%      |
| SABRENT                     | 2         | 3      | 1%      |
| PNY                         | 2         | 2      | 1%      |
| Phison                      | 2         | 2      | 1%      |
| Patriot                     | 2         | 5      | 1%      |
| Micron Technology           | 2         | 6      | 1%      |
| LITEONIT                    | 2         | 2      | 1%      |
| WD MediaMax                 | 1         | 3      | 0.5%    |
| W800SH                      | 1         | 1      | 0.5%    |
| USB3.0                      | 1         | 1      | 0.5%    |
| Team                        | 1         | 1      | 0.5%    |
| OCZ                         | 1         | 1      | 0.5%    |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.5%    |
| MaxDigital                  | 1         | 1      | 0.5%    |
| KingSpec                    | 1         | 1      | 0.5%    |
| JMicron Technology          | 1         | 4      | 0.5%    |
| INTEL SS                    | 1         | 2      | 0.5%    |
| HGST                        | 1         | 1      | 0.5%    |
| Axiom                       | 1         | 6      | 0.5%    |
| Argon                       | 1         | 1      | 0.5%    |
| Apple                       | 1         | 1      | 0.5%    |
| addlink                     | 1         | 1      | 0.5%    |
| Unknown                     | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB        | 5         | 2.3%    |
| WDC WD5000LPVT-22G33T0 500GB        | 3         | 1.38%   |
| Toshiba MQ01ABD100 1TB              | 3         | 1.38%   |
| Toshiba DT01ACA100 1TB              | 3         | 1.38%   |
| TDAS TerraMaster 16TB               | 3         | 1.38%   |
| Hitachi HTS547550A9E384 500GB       | 3         | 1.38%   |
| External USB3.0 128GB               | 3         | 1.38%   |
| Crucial CT240M500SSD1 240GB         | 3         | 1.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 0.92%   |
| WDC WDBNCE2500PNC 250GB SSD         | 2         | 0.92%   |
| WDC WD5000LPLX-22ZNTT0 500GB        | 2         | 0.92%   |
| WDC WD40EZRZ-22GXCB0 4TB            | 2         | 0.92%   |
| WDC WD2500BEVS-60UST0 250GB         | 2         | 0.92%   |
| WDC WD10SPZX-60Z10T0 1TB            | 2         | 0.92%   |
| Unknown MMC Card  2GB               | 2         | 0.92%   |
| Unknown MMC Card  128GB             | 2         | 0.92%   |
| Toshiba MQ04ABF100 1TB              | 2         | 0.92%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.92%   |
| Toshiba MK3261GSYN 320GB            | 2         | 0.92%   |
| Toshiba DT01ACA050 500GB            | 2         | 0.92%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 0.92%   |
| Seagate ST3250310AS 250GB           | 2         | 0.92%   |
| Seagate ST320DM001 HD322GJ 320GB    | 2         | 0.92%   |
| Seagate ST2000VM003-1CT164 2TB      | 2         | 0.92%   |
| Seagate Expansion 2TB               | 2         | 0.92%   |
| Samsung SSD 850 EVO 500GB           | 2         | 0.92%   |
| Samsung NVMe SSD Drive 500GB        | 2         | 0.92%   |
| SABRENT Disk 1TB                    | 2         | 0.92%   |
| Patriot Burst 480GB SSD             | 2         | 0.92%   |
| Micron/Crucial NVMe SSD Drive 500GB | 2         | 0.92%   |
| Hitachi HTS543232A7A384 320GB       | 2         | 0.92%   |
| China SATA SSD 512GB                | 2         | 0.92%   |
| China SATA SSD 1024GB               | 2         | 0.92%   |
| WDC WDBNCE0010PNC 1TB SSD           | 1         | 0.46%   |
| WDC WD7500BPVX-60JC3T0 752GB        | 1         | 0.46%   |
| WDC WD5000LPCX-00VHAT0 500GB        | 1         | 0.46%   |
| WDC WD5000BPVT-75HXZT1 500GB        | 1         | 0.46%   |
| WDC WD5000BEVT-55A0RT0 500GB        | 1         | 0.46%   |
| WDC WD30EZRZ-00WN9B0 3TB            | 1         | 0.46%   |
| WDC WD2500BPVT-22ZEST0 250GB        | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 29        | 66     | 31.52%  |
| Seagate             | 24        | 45     | 26.09%  |
| Toshiba             | 17        | 22     | 18.48%  |
| Hitachi             | 12        | 30     | 13.04%  |
| External            | 3         | 10     | 3.26%   |
| SABRENT             | 2         | 3      | 2.17%   |
| USB3.0              | 1         | 1      | 1.09%   |
| Samsung Electronics | 1         | 1      | 1.09%   |
| MaxDigital          | 1         | 1      | 1.09%   |
| HGST                | 1         | 1      | 1.09%   |
| Apple               | 1         | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 11        | 22     | 20%     |
| Samsung Electronics | 7         | 12     | 12.73%  |
| China               | 6         | 9      | 10.91%  |
| WDC                 | 5         | 8      | 9.09%   |
| SanDisk             | 5         | 5      | 9.09%   |
| A-DATA Technology   | 5         | 11     | 9.09%   |
| PNY                 | 2         | 2      | 3.64%   |
| Patriot             | 2         | 5      | 3.64%   |
| LITEONIT            | 2         | 2      | 3.64%   |
| Kingston            | 2         | 3      | 3.64%   |
| W800SH              | 1         | 1      | 1.82%   |
| SPCC                | 1         | 1      | 1.82%   |
| SK hynix            | 1         | 1      | 1.82%   |
| OCZ                 | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| KingSpec            | 1         | 1      | 1.82%   |
| INTEL SS            | 1         | 2      | 1.82%   |
| Argon               | 1         | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 82        | 181    | 44.32%  |
| SSD     | 51        | 88     | 27.57%  |
| NVMe    | 36        | 52     | 19.46%  |
| MMC     | 9         | 15     | 4.86%   |
| Unknown | 7         | 28     | 3.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 257    | 65.14%  |
| NVMe | 36        | 52     | 20.57%  |
| SAS  | 16        | 40     | 9.14%   |
| MMC  | 9         | 15     | 5.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 152    | 56.2%   |
| 0.51-1.0   | 43        | 83     | 31.39%  |
| 1.01-2.0   | 11        | 23     | 8.03%   |
| 3.01-4.0   | 5         | 10     | 3.65%   |
| 2.01-3.0   | 1         | 1      | 0.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 38        | 22.62%  |
| 251-500        | 35        | 20.83%  |
| 501-1000       | 29        | 17.26%  |
| 1-20           | 18        | 10.71%  |
| 1001-2000      | 14        | 8.33%   |
| 2001-3000      | 11        | 6.55%   |
| More than 3000 | 9         | 5.36%   |
| 51-100         | 6         | 3.57%   |
| 21-50          | 4         | 2.38%   |
| Unknown        | 4         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 61        | 34.86%  |
| 21-50     | 32        | 18.29%  |
| 101-250   | 22        | 12.57%  |
| 51-100    | 20        | 11.43%  |
| 251-500   | 15        | 8.57%   |
| 501-1000  | 11        | 6.29%   |
| 1001-2000 | 7         | 4%      |
| Unknown   | 4         | 2.29%   |
| 2001-3000 | 3         | 1.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-60UST0 250GB                      | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 6.25%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 1      | 6.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 6.25%   |
| Seagate ST3320613AS 320GB                        | 1         | 2      | 6.25%   |
| Seagate ST3250310AS 250GB                        | 1         | 1      | 6.25%   |
| Seagate ST320DM001 HD322GJ 320GB                 | 1         | 1      | 6.25%   |
| Seagate ST2000VM003-1CT164 2TB                   | 1         | 1      | 6.25%   |
| Seagate ST2000LM007-1R8174 2TB                   | 1         | 2      | 6.25%   |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 6.25%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 6.25%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 6.25%   |
| Hitachi HTS545025B9A300 250GB                    | 1         | 1      | 6.25%   |
| Hitachi HTS543232L9A300 320GB                    | 1         | 1      | 6.25%   |
| A-DATA Technology SU740 500GB SSD                | 1         | 1      | 6.25%   |
| A-DATA Technology SU630 240GB SSD                | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 9      | 35.71%  |
| Hitachi             | 2         | 2      | 14.29%  |
| A-DATA Technology   | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Toshiba             | 1         | 1      | 7.14%   |
| SK hynix            | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Micron Technology   | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 9      | 55.56%  |
| Hitachi | 2         | 2      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |
| Toshiba | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 13     | 64.29%  |
| SSD  | 4         | 4      | 28.57%  |
| NVMe | 1         | 1      | 7.14%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 103       | 297    | 69.13%  |
| Works    | 32        | 49     | 21.48%  |
| Malfunc  | 14        | 18     | 9.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 97        | 59.15%  |
| AMD                          | 29        | 17.68%  |
| Samsung Electronics          | 7         | 4.27%   |
| SK hynix                     | 6         | 3.66%   |
| SanDisk                      | 6         | 3.66%   |
| Silicon Motion               | 4         | 2.44%   |
| Phison Electronics           | 4         | 2.44%   |
| Nvidia                       | 3         | 1.83%   |
| Micron/Crucial Technology    | 3         | 1.83%   |
| Toshiba America Info Systems | 1         | 0.61%   |
| Micron Technology            | 1         | 0.61%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.61%   |
| Kingston Technology Company  | 1         | 0.61%   |
| ASMedia Technology           | 1         | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 23        | 11.98%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 11        | 5.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 9         | 4.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 4.17%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 3.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 3.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 3.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 2.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 2.6%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4         | 2.08%   |
| Phison E12 NVMe Controller                                                              | 4         | 2.08%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 1.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3         | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 1.56%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3         | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.56%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 1.56%   |
| SK hynix BC511 NVMe SSD                                                                 | 2         | 1.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.04%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.04%   |
| AMD FCH IDE Controller                                                                  | 2         | 1.04%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.52%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                             | 1         | 0.52%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1         | 0.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 101       | 57.71%  |
| NVMe | 36        | 20.57%  |
| IDE  | 20        | 11.43%  |
| RAID | 18        | 10.29%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 102       | 74.45%  |
| AMD    | 33        | 24.09%  |
| ARM    | 2         | 1.46%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 3         | 2.19%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 2.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 2.19%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 3         | 2.19%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3         | 2.19%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 3         | 2.19%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3         | 2.19%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 1.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.46%   |
| Intel Core i3-4020Y CPU @ 1.50GHz           | 2         | 1.46%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.46%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.46%   |
| Intel Celeron CPU E1200 @ 1.60GHz           | 2         | 1.46%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2         | 1.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.46%   |
| ARM Processor                               | 2         | 1.46%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.46%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 2         | 1.46%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 1.46%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 2         | 1.46%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.73%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.73%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.73%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.73%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.73%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 0.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.73%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 0.73%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.73%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.73%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.73%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.73%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.73%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 0.73%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 0.73%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 0.73%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 27        | 19.71%  |
| Intel Core i7           | 20        | 14.6%   |
| Intel Core i3           | 15        | 10.95%  |
| Intel Celeron           | 15        | 10.95%  |
| Other                   | 9         | 6.57%   |
| AMD Ryzen 5             | 9         | 6.57%   |
| Intel Core 2 Duo        | 7         | 5.11%   |
| Intel Pentium Silver    | 5         | 3.65%   |
| AMD Ryzen 7             | 4         | 2.92%   |
| AMD Ryzen 3             | 4         | 2.92%   |
| AMD A8                  | 4         | 2.92%   |
| Intel Pentium           | 3         | 2.19%   |
| Intel Pentium Dual-Core | 2         | 1.46%   |
| AMD A6                  | 2         | 1.46%   |
| Intel Genuine           | 1         | 0.73%   |
| Intel Core 2            | 1         | 0.73%   |
| AMD Ryzen Threadripper  | 1         | 0.73%   |
| AMD Phenom II X4        | 1         | 0.73%   |
| AMD G                   | 1         | 0.73%   |
| AMD FX                  | 1         | 0.73%   |
| AMD E2                  | 1         | 0.73%   |
| AMD Athlon Dual Core    | 1         | 0.73%   |
| AMD Athlon 64 X2        | 1         | 0.73%   |
| AMD Athlon              | 1         | 0.73%   |
| AMD A10                 | 1         | 0.73%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 66        | 48.18%  |
| 4      | 46        | 33.58%  |
| 6      | 14        | 10.22%  |
| 8      | 6         | 4.38%   |
| 1      | 4         | 2.92%   |
| 16     | 1         | 0.73%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 137       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 79        | 57.66%  |
| 1      | 58        | 42.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 134       | 97.1%   |
| Unknown        | 3         | 2.17%   |
| 32-bit         | 1         | 0.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 31.08%  |
| 0x206a7    | 12        | 8.11%   |
| 0x306c3    | 7         | 4.73%   |
| 0x806e9    | 5         | 3.38%   |
| 0x306a9    | 5         | 3.38%   |
| 0x706a1    | 4         | 2.7%    |
| 0x20655    | 4         | 2.7%    |
| 0x1067a    | 4         | 2.7%    |
| 0xa0671    | 3         | 2.03%   |
| 0x906ea    | 3         | 2.03%   |
| 0x806ec    | 3         | 2.03%   |
| 0x806ea    | 3         | 2.03%   |
| 0x30678    | 3         | 2.03%   |
| 0x08108109 | 3         | 2.03%   |
| 0x06001119 | 3         | 2.03%   |
| 0x6fd      | 2         | 1.35%   |
| 0x406e3    | 2         | 1.35%   |
| 0x306d4    | 2         | 1.35%   |
| 0x08701021 | 2         | 1.35%   |
| 0x08701013 | 2         | 1.35%   |
| 0x08600106 | 2         | 1.35%   |
| 0x06003106 | 2         | 1.35%   |
| 0xa0652    | 1         | 0.68%   |
| 0x906ed    | 1         | 0.68%   |
| 0x906e9    | 1         | 0.68%   |
| 0x906c0    | 1         | 0.68%   |
| 0x90675    | 1         | 0.68%   |
| 0x806c1    | 1         | 0.68%   |
| 0x706e5    | 1         | 0.68%   |
| 0x6fb      | 1         | 0.68%   |
| 0x6e8      | 1         | 0.68%   |
| 0x506e3    | 1         | 0.68%   |
| 0x506c9    | 1         | 0.68%   |
| 0x406c4    | 1         | 0.68%   |
| 0x406c3    | 1         | 0.68%   |
| 0x40651    | 1         | 0.68%   |
| 0x30679    | 1         | 0.68%   |
| 0x20652    | 1         | 0.68%   |
| 0x10676    | 1         | 0.68%   |
| 0x08600104 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 16.79%  |
| SandyBridge      | 14        | 10.22%  |
| Haswell          | 10        | 7.3%    |
| Zen 2            | 8         | 5.84%   |
| Penryn           | 8         | 5.84%   |
| Zen+             | 6         | 4.38%   |
| Silvermont       | 6         | 4.38%   |
| IvyBridge        | 6         | 4.38%   |
| Goldmont plus    | 6         | 4.38%   |
| Westmere         | 5         | 3.65%   |
| Skylake          | 5         | 3.65%   |
| IceLake          | 5         | 3.65%   |
| Zen              | 4         | 2.92%   |
| Piledriver       | 4         | 2.92%   |
| Core             | 4         | 2.92%   |
| Unknown          | 4         | 2.92%   |
| TigerLake        | 2         | 1.46%   |
| Steamroller      | 2         | 1.46%   |
| K8 Hammer        | 2         | 1.46%   |
| Broadwell        | 2         | 1.46%   |
| Bobcat           | 2         | 1.46%   |
| Zen 3            | 1         | 0.73%   |
| Tremont          | 1         | 0.73%   |
| Puma             | 1         | 0.73%   |
| P6               | 1         | 0.73%   |
| K10 Llano        | 1         | 0.73%   |
| K10              | 1         | 0.73%   |
| Goldmont         | 1         | 0.73%   |
| CometLake        | 1         | 0.73%   |
| Alderlake Hybrid | 1         | 0.73%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 93        | 60.78%  |
| Nvidia | 30        | 19.61%  |
| AMD    | 30        | 19.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 8.59%   |
| Intel UHD Graphics 620                                                                   | 6         | 3.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 3.07%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.45%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 2.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.84%   |
| Intel HD Graphics 610                                                                    | 3         | 1.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 1.84%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 1.84%   |
| AMD Renoir                                                                               | 3         | 1.84%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.23%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.23%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 1.23%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 2         | 1.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.23%   |
| Intel HD Graphics 620                                                                    | 2         | 1.23%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.23%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 2         | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.23%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 1.23%   |
| AMD Trinity 2 [Radeon HD 7540D]                                                          | 2         | 1.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.23%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 1.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.61%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.61%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 78        | 55.71%  |
| 1 x AMD            | 26        | 18.57%  |
| 1 x Nvidia         | 16        | 11.43%  |
| Intel + Nvidia     | 11        | 7.86%   |
| Intel + AMD        | 3         | 2.14%   |
| Other              | 2         | 1.43%   |
| Intel + 2 x Nvidia | 2         | 1.43%   |
| 2 x Nvidia         | 1         | 0.71%   |
| 2 x AMD            | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 120       | 84.51%  |
| Proprietary | 16        | 11.27%  |
| Unknown     | 6         | 4.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 95        | 65.07%  |
| 0.01-0.5   | 14        | 9.59%   |
| 1.01-2.0   | 10        | 6.85%   |
| 0.51-1.0   | 10        | 6.85%   |
| 3.01-4.0   | 7         | 4.79%   |
| 5.01-6.0   | 4         | 2.74%   |
| 8.01-16.0  | 3         | 2.05%   |
| 7.01-8.0   | 2         | 1.37%   |
| 2.01-3.0   | 1         | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 18        | 11.61%  |
| Goldstar                | 13        | 8.39%   |
| LG Display              | 12        | 7.74%   |
| Chimei Innolux          | 12        | 7.74%   |
| BOE                     | 10        | 6.45%   |
| Dell                    | 9         | 5.81%   |
| AU Optronics            | 9         | 5.81%   |
| Acer                    | 7         | 4.52%   |
| Hewlett-Packard         | 6         | 3.87%   |
| ViewSonic               | 5         | 3.23%   |
| Sony                    | 5         | 3.23%   |
| Apple                   | 5         | 3.23%   |
| Vizio                   | 4         | 2.58%   |
| AOC                     | 4         | 2.58%   |
| Sceptre Tech            | 3         | 1.94%   |
| PANDA                   | 3         | 1.94%   |
| Gateway                 | 3         | 1.94%   |
| Element                 | 3         | 1.94%   |
| VIZ                     | 2         | 1.29%   |
| Tech Concepts           | 2         | 1.29%   |
| RTK                     | 2         | 1.29%   |
| eMachines               | 2         | 1.29%   |
| Chi Mei Optoelectronics | 2         | 1.29%   |
| Ancor Communications    | 2         | 1.29%   |
| Valve                   | 1         | 0.65%   |
| Unknown                 | 1         | 0.65%   |
| UGD                     | 1         | 0.65%   |
| Sharp                   | 1         | 0.65%   |
| Seiki                   | 1         | 0.65%   |
| ONN                     | 1         | 0.65%   |
| MTK                     | 1         | 0.65%   |
| MStar                   | 1         | 0.65%   |
| Lenovo                  | 1         | 0.65%   |
| InnoLux Display         | 1         | 0.65%   |
| ASUSTek Computer        | 1         | 0.65%   |
| Unknown                 | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 6         | 3.73%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch | 3         | 1.86%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 3         | 1.86%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch               | 3         | 1.86%   |
| Element ELCFW329 ELE1366 1366x768 700x390mm 31.5-inch                | 3         | 1.86%   |
| VIZ LCD Monitor M551d-A2R                                            | 2         | 1.24%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch        | 2         | 1.24%   |
| Sony TV SNY4502 1920x1080                                            | 2         | 1.24%   |
| Sony TV  *00 SNY4B04 3840x2160                                       | 2         | 1.24%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch    | 2         | 1.24%   |
| Hewlett-Packard L2105tm HWP2863 1920x1080 477x268mm 21.5-inch        | 2         | 1.24%   |
| Gateway LCD Monitor FHX2300                                          | 2         | 1.24%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                | 2         | 1.24%   |
| eMachines E19T6W EMA0783 1440x900 410x257mm 19.1-inch                | 2         | 1.24%   |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch              | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 2         | 1.24%   |
| Acer LCD Monitor G236HL 5760x1080                                    | 2         | 1.24%   |
| Vizio M422i-B1 VIZ1006 1920x1080 930x523mm 42.0-inch                 | 1         | 0.62%   |
| Vizio E320fi-B2 VIZ1005 1920x1080 477x268mm 21.5-inch                | 1         | 0.62%   |
| Vizio E260MV VIZ0062 1920x1080 580x320mm 26.1-inch                   | 1         | 0.62%   |
| Vizio D40f-G9 VIZ1027 1920x1080 477x268mm 21.5-inch                  | 1         | 0.62%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch        | 1         | 0.62%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch             | 1         | 0.62%   |
| ViewSonic VA1930wm VSC171F 1440x900 410x260mm 19.1-inch              | 1         | 0.62%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.62%   |
| Unknown LCD Monitor Dell S2719DGF 2560x1440                          | 1         | 0.62%   |
| UGD Artist 156 UGD1501 1920x1080 344x193mm 15.5-inch                 | 1         | 0.62%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                           | 1         | 0.62%   |
| Tech Concepts LCD Monitor 43S423 1920x1080                           | 1         | 0.62%   |
| Sony TV SNYEA01 1920x1080                                            | 1         | 0.62%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch              | 1         | 0.62%   |
| Seiki SE241TS SEK0CF0 1920x1080 520x290mm 23.4-inch                  | 1         | 0.62%   |
| Sceptre Tech Sceptre X22HG SPT2204 1920x1080 474x296mm 22.0-inch     | 1         | 0.62%   |
| Sceptre Tech Sceptre F22 SPT08E3 1920x1080 475x267mm 21.5-inch       | 1         | 0.62%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch               | 1         | 0.62%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch    | 1         | 0.62%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch    | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 64        | 45.07%  |
| 1366x768 (WXGA)    | 30        | 21.13%  |
| 3840x2160 (4K)     | 13        | 9.15%   |
| 1440x900 (WXGA+)   | 6         | 4.23%   |
| 1600x900 (HD+)     | 5         | 3.52%   |
| 1280x800 (WXGA)    | 5         | 3.52%   |
| 2560x1440 (QHD)    | 3         | 2.11%   |
| 1280x1024 (SXGA)   | 3         | 2.11%   |
| 5760x1080          | 2         | 1.41%   |
| 2560x1080          | 2         | 1.41%   |
| Unknown            | 2         | 1.41%   |
| 800x1280           | 1         | 0.7%    |
| 3840x1080          | 1         | 0.7%    |
| 3440x1440          | 1         | 0.7%    |
| 3200x1800 (QHD+)   | 1         | 0.7%    |
| 2160x1440          | 1         | 0.7%    |
| 1680x1050 (WSXGA+) | 1         | 0.7%    |
| 1280x720 (HD)      | 1         | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 36        | 24%     |
| 21      | 17        | 11.33%  |
| 23      | 12        | 8%      |
| 17      | 10        | 6.67%   |
| 72      | 9         | 6%      |
| 31      | 9         | 6%      |
| 14      | 9         | 6%      |
| 13      | 7         | 4.67%   |
| 19      | 6         | 4%      |
| Unknown | 5         | 3.33%   |
| 27      | 4         | 2.67%   |
| 20      | 4         | 2.67%   |
| 34      | 3         | 2%      |
| 24      | 3         | 2%      |
| 18      | 3         | 2%      |
| 11      | 3         | 2%      |
| 84      | 1         | 0.67%   |
| 64      | 1         | 0.67%   |
| 52      | 1         | 0.67%   |
| 49      | 1         | 0.67%   |
| 32      | 1         | 0.67%   |
| 26      | 1         | 0.67%   |
| 25      | 1         | 0.67%   |
| 22      | 1         | 0.67%   |
| 12      | 1         | 0.67%   |
| 7       | 1         | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 31.97%  |
| 401-500     | 28        | 19.05%  |
| 501-600     | 20        | 13.61%  |
| 351-400     | 11        | 7.48%   |
| 601-700     | 10        | 6.8%    |
| 201-300     | 9         | 6.12%   |
| 1501-2000   | 9         | 6.12%   |
| Unknown     | 5         | 3.4%    |
| 701-800     | 4         | 2.72%   |
| 1001-1500   | 3         | 2.04%   |
| 1-100       | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 105       | 80.15%  |
| 16/10   | 13        | 9.92%   |
| Unknown | 5         | 3.82%   |
| 5/4     | 4         | 3.05%   |
| 21/9    | 3         | 2.29%   |
| 0.67    | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 24.49%  |
| 201-250        | 27        | 18.37%  |
| 151-200        | 16        | 10.88%  |
| 81-90          | 14        | 9.52%   |
| 351-500        | 13        | 8.84%   |
| More than 1000 | 11        | 7.48%   |
| 121-130        | 7         | 4.76%   |
| Unknown        | 5         | 3.4%    |
| 301-350        | 4         | 2.72%   |
| 141-150        | 4         | 2.72%   |
| 51-60          | 3         | 2.04%   |
| 71-80          | 2         | 1.36%   |
| 251-300        | 2         | 1.36%   |
| 61-70          | 1         | 0.68%   |
| 1-40           | 1         | 0.68%   |
| 131-140        | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 49        | 33.56%  |
| 51-100        | 44        | 30.14%  |
| 121-160       | 30        | 20.55%  |
| 1-50          | 13        | 8.9%    |
| Unknown       | 5         | 3.42%   |
| 161-240       | 3         | 2.05%   |
| More than 240 | 2         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 113       | 79.02%  |
| 2     | 24        | 16.78%  |
| 0     | 4         | 2.8%    |
| 3     | 2         | 1.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 86        | 39.27%  |
| Intel                    | 70        | 31.96%  |
| Qualcomm Atheros         | 18        | 8.22%   |
| Broadcom                 | 9         | 4.11%   |
| NetGear                  | 6         | 2.74%   |
| Ralink Technology        | 5         | 2.28%   |
| Marvell Technology Group | 4         | 1.83%   |
| Nvidia                   | 3         | 1.37%   |
| Broadcom Limited         | 3         | 1.37%   |
| TP-Link                  | 2         | 0.91%   |
| Samsung Electronics      | 2         | 0.91%   |
| Ralink                   | 2         | 0.91%   |
| MediaTek                 | 2         | 0.91%   |
| ASIX Electronics         | 2         | 0.91%   |
| Microsoft                | 1         | 0.46%   |
| Gemtek                   | 1         | 0.46%   |
| Dell                     | 1         | 0.46%   |
| Belkin Components        | 1         | 0.46%   |
| Aquantia                 | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 21.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.17%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 1.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.98%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.59%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.19%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1.19%   |
| Realtek 802.11ac NIC                                              | 3         | 1.19%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.19%   |
| Intel Wireless 7265                                               | 3         | 1.19%   |
| Intel Wireless 3160                                               | 3         | 1.19%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 1.19%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.19%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.79%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 0.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2         | 0.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.79%   |
| NetGear LB1120-100NAS                                             | 2         | 0.79%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.79%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 2         | 0.79%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 2         | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 47        | 37.9%   |
| Realtek Semiconductor    | 32        | 25.81%  |
| Qualcomm Atheros         | 15        | 12.1%   |
| Broadcom                 | 8         | 6.45%   |
| Ralink Technology        | 5         | 4.03%   |
| NetGear                  | 4         | 3.23%   |
| TP-Link                  | 2         | 1.61%   |
| Ralink                   | 2         | 1.61%   |
| MediaTek                 | 2         | 1.61%   |
| Broadcom Limited         | 2         | 1.61%   |
| Microsoft                | 1         | 0.81%   |
| Marvell Technology Group | 1         | 0.81%   |
| Gemtek                   | 1         | 0.81%   |
| Dell                     | 1         | 0.81%   |
| Belkin Components        | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 7         | 5.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 5         | 3.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 5         | 3.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 5         | 3.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 4         | 3.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 4         | 3.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 3         | 2.29%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 3         | 2.29%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 3         | 2.29%   |
| Realtek 802.11ac NIC                                       | 3         | 2.29%   |
| Intel Wireless 8265 / 8275                                 | 3         | 2.29%   |
| Intel Wireless 7265                                        | 3         | 2.29%   |
| Intel Wireless 3160                                        | 3         | 2.29%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]               | 3         | 2.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 1.53%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 2         | 1.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 2         | 1.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2         | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 1.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 2         | 1.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 1.53%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 1.53%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 2         | 1.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 2         | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 1.53%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 2         | 1.53%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 2         | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 1.53%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 2         | 1.53%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 2         | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 2         | 1.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 0.76%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                 | 1         | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1         | 0.76%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 0.76%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1         | 0.76%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1         | 0.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 0.76%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                     | 1         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 68        | 56.2%   |
| Intel                    | 31        | 25.62%  |
| Qualcomm Atheros         | 4         | 3.31%   |
| Broadcom                 | 4         | 3.31%   |
| Nvidia                   | 3         | 2.48%   |
| Marvell Technology Group | 3         | 2.48%   |
| Samsung Electronics      | 2         | 1.65%   |
| NetGear                  | 2         | 1.65%   |
| ASIX Electronics         | 2         | 1.65%   |
| Broadcom Limited         | 1         | 0.83%   |
| Aquantia                 | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 55        | 45.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 7.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 6.61%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 4.13%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 3.31%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 2.48%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.65%   |
| NetGear LB1120-100NAS                                                          | 2         | 1.65%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.65%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.83%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.83%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.83%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.83%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.83%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.83%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 0.83%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.83%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.83%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.83%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.83%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.83%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.83%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.83%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 0.83%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 0.83%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.83%   |
| ASIX AX88772B                                                                  | 1         | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.83%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 116       | 51.56%  |
| WiFi     | 109       | 48.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 56.85%  |
| Ethernet | 63        | 43.15%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 51.08%  |
| 1     | 60        | 43.17%  |
| 0     | 5         | 3.6%    |
| 3     | 3         | 2.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 115       | 82.73%  |
| Yes  | 24        | 17.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 44.44%  |
| Realtek Semiconductor           | 11        | 12.22%  |
| Cambridge Silicon Radio         | 9         | 10%     |
| Qualcomm Atheros Communications | 6         | 6.67%   |
| IMC Networks                    | 4         | 4.44%   |
| Apple                           | 4         | 4.44%   |
| Lite-On Technology              | 3         | 3.33%   |
| Foxconn / Hon Hai               | 3         | 3.33%   |
| Dell                            | 2         | 2.22%   |
| Broadcom                        | 2         | 2.22%   |
| Toshiba                         | 1         | 1.11%   |
| Marvell Semiconductor           | 1         | 1.11%   |
| Hewlett-Packard                 | 1         | 1.11%   |
| Dynex                           | 1         | 1.11%   |
| Belkin Components               | 1         | 1.11%   |
| Alps Electric                   | 1         | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 12        | 13.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 8.89%   |
| Intel AX200 Bluetooth                                                               | 7         | 7.78%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 6.67%   |
| Intel AX201 Bluetooth                                                               | 5         | 5.56%   |
| Realtek Bluetooth Radio                                                             | 4         | 4.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 4.44%   |
| Intel Bluetooth Device                                                              | 4         | 4.44%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 3.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 2.22%   |
| Lite-On Bluetooth Device                                                            | 2         | 2.22%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 2.22%   |
| Broadcom Bluetooth Device                                                           | 2         | 2.22%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.22%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.11%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.11%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.11%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.11%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 1.11%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.11%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.11%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.11%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.11%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 1.11%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.11%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.11%   |
| Belkin Components Bluetooth Mini Dongle                                             | 1         | 1.11%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.11%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.11%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 101       | 59.06%  |
| AMD                                             | 33        | 19.3%   |
| Nvidia                                          | 24        | 14.04%  |
| Logitech                                        | 7         | 4.09%   |
| C-Media Electronics                             | 2         | 1.17%   |
| Nintendo                                        | 1         | 0.58%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.58%   |
| Kingston Technology                             | 1         | 0.58%   |
| Focusrite-Novation                              | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 7.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 3.83%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 2.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 2.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.39%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 2.39%   |
| Logitech EasyCall Speakerphone                                                                    | 4         | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.91%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.44%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.44%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.44%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.44%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.44%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.96%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.96%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 0.96%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.96%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.96%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.96%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.96%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 13        | 26%     |
| Samsung Electronics | 10        | 20%     |
| Unknown             | 7         | 14%     |
| Micron Technology   | 3         | 6%      |
| Kingston            | 3         | 6%      |
| PNY                 | 2         | 4%      |
| G.Skill             | 2         | 4%      |
| Crucial             | 2         | 4%      |
| Corsair             | 2         | 4%      |
| A-DATA Technology   | 2         | 4%      |
| Silicon Power       | 1         | 2%      |
| Sesame              | 1         | 2%      |
| Ramaxel Technology  | 1         | 2%      |
| Avant               | 1         | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                      | 3         | 5.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 3.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 3.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1         | 1.79%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                    | 1         | 1.79%   |
| Unknown RAM Module 1GB DIMM                               | 1         | 1.79%   |
| Unknown RAM CL18-22-22 D4-3600 16384MB DIMM DDR4 3600MT/s | 1         | 1.79%   |
| Unknown RAM CL18-20-20 D4-3600 8192MB DIMM DDR4 3600MT/s  | 1         | 1.79%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 1.79%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 1.79%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                | 1         | 1.79%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s             | 1         | 1.79%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.79%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1         | 1.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.79%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1         | 1.79%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 1         | 1.79%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 1.79%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 1         | 1.79%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 1.79%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 1.79%   |
| Silicon Power RAM Module 8GB SODIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Sesame RAM S939A2UGS-ITR 8GB DIMM 1600MT/s                | 1         | 1.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 1         | 1.79%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1         | 1.79%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1         | 1.79%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1         | 1.79%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s       | 1         | 1.79%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s       | 1         | 1.79%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 1.79%   |
| PNY RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 1.79%   |
| PNY RAM 4GBH1X04E9992 4096MB DIMM DDR3 1600MT/s           | 1         | 1.79%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 1         | 1.79%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s    | 1         | 1.79%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 1.79%   |
| Kingston RAM X2YH1K-MIE-NX 16GB DIMM DDR4 3200MT/s        | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 21        | 43.75%  |
| DDR3    | 18        | 37.5%   |
| SDRAM   | 3         | 6.25%   |
| LPDDR4  | 2         | 4.17%   |
| Unknown | 2         | 4.17%   |
| LPDDR3  | 1         | 2.08%   |
| DDR     | 1         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 48.94%  |
| DIMM         | 23        | 48.94%  |
| Row Of Chips | 1         | 2.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 23        | 46%     |
| 4096  | 14        | 28%     |
| 16384 | 7         | 14%     |
| 2048  | 5         | 10%     |
| 1024  | 1         | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 14        | 28%     |
| 2667    | 9         | 18%     |
| 3200    | 7         | 14%     |
| Unknown | 4         | 8%      |
| 1333    | 3         | 6%      |
| 3600    | 2         | 4%      |
| 2400    | 2         | 4%      |
| 667     | 2         | 4%      |
| 3533    | 1         | 2%      |
| 3266    | 1         | 2%      |
| 2133    | 1         | 2%      |
| 1867    | 1         | 2%      |
| 1866    | 1         | 2%      |
| 1067    | 1         | 2%      |
| 800     | 1         | 2%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| HP OfficeJet Pro 6960 | 1         | 50%     |
| Brother MFC-L2685DW   | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 14.47%  |
| Microdia                               | 8         | 10.53%  |
| Realtek Semiconductor                  | 6         | 7.89%   |
| Logitech                               | 6         | 7.89%   |
| Ricoh                                  | 5         | 6.58%   |
| Sunplus Innovation Technology          | 4         | 5.26%   |
| Lite-On Technology                     | 4         | 5.26%   |
| IMC Networks                           | 4         | 5.26%   |
| Apple                                  | 4         | 5.26%   |
| Quanta                                 | 3         | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.95%   |
| Bison Electronics                      | 3         | 3.95%   |
| Syntek                                 | 2         | 2.63%   |
| Suyin                                  | 2         | 2.63%   |
| Luxvisions Innotech Limited            | 2         | 2.63%   |
| Acer                                   | 2         | 2.63%   |
| Razer USA                              | 1         | 1.32%   |
| Microsoft                              | 1         | 1.32%   |
| Lenovo                                 | 1         | 1.32%   |
| Jieli Technology                       | 1         | 1.32%   |
| Goertek Electronics                    | 1         | 1.32%   |
| Cubeternet                             | 1         | 1.32%   |
| Alpha Imaging Technology               | 1         | 1.32%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Camera                                                | 4         | 5.19%   |
| Ricoh Integrated Webcam                                        | 3         | 3.9%    |
| Lite-On HP Wide Vision HD Camera                               | 3         | 3.9%    |
| Sunplus Integrated_Webcam_HD                                   | 2         | 2.6%    |
| Realtek Integrated Webcam HD                                   | 2         | 2.6%    |
| Logitech HD Pro Webcam C920                                    | 2         | 2.6%    |
| Chicony HP Truevision HD                                       | 2         | 2.6%    |
| Chicony HD WebCam                                              | 2         | 2.6%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 2.6%    |
| Apple FaceTime HD Camera                                       | 2         | 2.6%    |
| Syntek Lenovo EasyCamera                                       | 1         | 1.3%    |
| Syntek Integrated Camera                                       | 1         | 1.3%    |
| Suyin USB 2.0 Camera                                           | 1         | 1.3%    |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.3%    |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.3%    |
| Sunplus Camera                                                 | 1         | 1.3%    |
| Ricoh Sony Visual Communication Camera Integrated Webcam       | 1         | 1.3%    |
| Ricoh HD Webcam                                                | 1         | 1.3%    |
| Realtek USB2.0-Camera                                          | 1         | 1.3%    |
| Realtek MTD camera                                             | 1         | 1.3%    |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.3%    |
| Realtek Integrated Webcam                                      | 1         | 1.3%    |
| Razer USA Razer Kiyo Pro                                       | 1         | 1.3%    |
| Quanta HP Wide Vision HD Camera                                | 1         | 1.3%    |
| Quanta HP TrueVision HD Camera                                 | 1         | 1.3%    |
| Quanta HD WebCam                                               | 1         | 1.3%    |
| Microsoft LifeCam Rear                                         | 1         | 1.3%    |
| Microsoft LifeCam Front                                        | 1         | 1.3%    |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 1.3%    |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.3%    |
| Microdia GC02M2                                                | 1         | 1.3%    |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.3%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.3%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 1.3%    |
| Logitech Webcam Pro 9000                                       | 1         | 1.3%    |
| Logitech Webcam C310                                           | 1         | 1.3%    |
| Logitech Webcam C270                                           | 1         | 1.3%    |
| Logitech CrystalCam                                            | 1         | 1.3%    |
| Lite-On HP HD Webcam                                           | 1         | 1.3%    |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 1.3%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 8         | 66.67%  |
| Synaptics             | 2         | 16.67%  |
| LighTuning Technology | 2         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 3         | 25%     |
| LighTuning EgisTec Touch Fingerprint Sensor       | 2         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                   | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner              | 1         | 8.33%   |
| Synaptics UWP WBDI                                | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 4         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom 5880                                                                | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 101       | 69.18%  |
| 1     | 37        | 25.34%  |
| 2     | 8         | 5.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 18        | 36.73%  |
| Fingerprint reader       | 12        | 24.49%  |
| Graphics card            | 9         | 18.37%  |
| Chipcard                 | 4         | 8.16%   |
| Multimedia controller    | 2         | 4.08%   |
| Communication controller | 2         | 4.08%   |
| Storage                  | 1         | 2.04%   |
| Net/ethernet             | 1         | 2.04%   |

