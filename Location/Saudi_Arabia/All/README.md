Linux in Saudi Arabia - Tested Hardware & Statistics
----------------------------------------------------

A project to collect tested hardware configurations for Linux in Saudi Arabia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Saudi_Arabia/Desktop/README.md) and [notebooks](/Location/Saudi_Arabia/Notebook/README.md).

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

Total: 642

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [cf6fc980de](https://linux-hardware.org/?probe=cf6fc980de) | May 07, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3380a14ae9](https://linux-hardware.org/?probe=3380a14ae9) | May 02, 2024 |
| MSI           | GL75 Leopard 10SFK          | Notebook    | [2cde0c8054](https://linux-hardware.org/?probe=2cde0c8054) | Apr 28, 2024 |
| ASUSTek       | G20AJ                       | Desktop     | [bbb2ae3890](https://linux-hardware.org/?probe=bbb2ae3890) | Apr 20, 2024 |
| ASUSTek       | G20AJ                       | Desktop     | [f9741e3c18](https://linux-hardware.org/?probe=f9741e3c18) | Apr 20, 2024 |
| HP            | 2B38                        | Desktop     | [db7129fcde](https://linux-hardware.org/?probe=db7129fcde) | Apr 07, 2024 |
| HP            | 2B38                        | Desktop     | [44386f0027](https://linux-hardware.org/?probe=44386f0027) | Apr 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [8cd7c7653a](https://linux-hardware.org/?probe=8cd7c7653a) | Apr 07, 2024 |
| Lenovo        | B50-70 20384                | Notebook    | [f78c6087ac](https://linux-hardware.org/?probe=f78c6087ac) | Mar 31, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c5020d4c73](https://linux-hardware.org/?probe=c5020d4c73) | Mar 27, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1d78b76824](https://linux-hardware.org/?probe=1d78b76824) | Mar 27, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d11f38f81c](https://linux-hardware.org/?probe=d11f38f81c) | Mar 25, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f07c7e7a17](https://linux-hardware.org/?probe=f07c7e7a17) | Mar 23, 2024 |
| ASUSTek       | X541SA                      | Notebook    | [4f1901506d](https://linux-hardware.org/?probe=4f1901506d) | Mar 22, 2024 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [c55cd9fbac](https://linux-hardware.org/?probe=c55cd9fbac) | Mar 22, 2024 |
| Gigabyte      | B760 DS3H DDR4              | Desktop     | [18eb8a593e](https://linux-hardware.org/?probe=18eb8a593e) | Mar 18, 2024 |
| Dell          | 0JCTF8 A00                  | Desktop     | [eb32037afd](https://linux-hardware.org/?probe=eb32037afd) | Mar 16, 2024 |
| Dell          | 0JCTF8 A00                  | Desktop     | [ff149982e7](https://linux-hardware.org/?probe=ff149982e7) | Mar 16, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [723f208e9b](https://linux-hardware.org/?probe=723f208e9b) | Mar 14, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [a3a7dd03fc](https://linux-hardware.org/?probe=a3a7dd03fc) | Mar 14, 2024 |
| MSI           | GF63 Thin 8SC               | Notebook    | [bbc6edbc2d](https://linux-hardware.org/?probe=bbc6edbc2d) | Mar 09, 2024 |
| ASUSTek       | GL552VX                     | Notebook    | [01ea0912c3](https://linux-hardware.org/?probe=01ea0912c3) | Mar 03, 2024 |
| Lenovo        | MAHOBAY                     | Desktop     | [ea1d8e1132](https://linux-hardware.org/?probe=ea1d8e1132) | Mar 03, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [094127d440](https://linux-hardware.org/?probe=094127d440) | Feb 26, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [adace6bd02](https://linux-hardware.org/?probe=adace6bd02) | Feb 22, 2024 |
| Dell          | Inspiron 3581               | Notebook    | [62a3c2b526](https://linux-hardware.org/?probe=62a3c2b526) | Feb 11, 2024 |
| HP            | 3648h                       | Desktop     | [96e8e58699](https://linux-hardware.org/?probe=96e8e58699) | Feb 11, 2024 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [7cd906021e](https://linux-hardware.org/?probe=7cd906021e) | Feb 07, 2024 |
| Lenovo        | Unknown                     | Notebook    | [46ccd12f05](https://linux-hardware.org/?probe=46ccd12f05) | Feb 04, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [37b70e517a](https://linux-hardware.org/?probe=37b70e517a) | Feb 03, 2024 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [bbc54bcc7c](https://linux-hardware.org/?probe=bbc54bcc7c) | Jan 27, 2024 |
| Dell          | Inspiron 3581               | Notebook    | [7a5cfbd8d3](https://linux-hardware.org/?probe=7a5cfbd8d3) | Jan 25, 2024 |
| Dell          | Inspiron 3581               | Notebook    | [dbf2745f1f](https://linux-hardware.org/?probe=dbf2745f1f) | Jan 25, 2024 |
| Lenovo        | 3740 NOK                    | Desktop     | [2bfb559750](https://linux-hardware.org/?probe=2bfb559750) | Jan 25, 2024 |
| Dell          | Latitude E5540              | Notebook    | [2e1716a6aa](https://linux-hardware.org/?probe=2e1716a6aa) | Jan 22, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [4d83b8cef9](https://linux-hardware.org/?probe=4d83b8cef9) | Jan 19, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [7f0443badf](https://linux-hardware.org/?probe=7f0443badf) | Jan 18, 2024 |
| Toshiba       | Satellite C850-B820         | Notebook    | [321a8ae666](https://linux-hardware.org/?probe=321a8ae666) | Jan 17, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | Desktop     | [803c2f0bd9](https://linux-hardware.org/?probe=803c2f0bd9) | Jan 16, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [a4afc8bb1f](https://linux-hardware.org/?probe=a4afc8bb1f) | Jan 12, 2024 |
| Lenovo        | MAHOBAY                     | Desktop     | [68a882e9f2](https://linux-hardware.org/?probe=68a882e9f2) | Jan 10, 2024 |
| HP            | 2215                        | Desktop     | [cea6ba103b](https://linux-hardware.org/?probe=cea6ba103b) | Jan 07, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e4ce5a17a5](https://linux-hardware.org/?probe=e4ce5a17a5) | Jan 05, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [4c587bc867](https://linux-hardware.org/?probe=4c587bc867) | Jan 04, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [debaccaee2](https://linux-hardware.org/?probe=debaccaee2) | Jan 04, 2024 |
| Dell          | G3 3590                     | Notebook    | [681f15e9c0](https://linux-hardware.org/?probe=681f15e9c0) | Dec 27, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [e778e7923a](https://linux-hardware.org/?probe=e778e7923a) | Dec 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b601b75917](https://linux-hardware.org/?probe=b601b75917) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [d52d7379c3](https://linux-hardware.org/?probe=d52d7379c3) | Dec 06, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [1f793dc2d3](https://linux-hardware.org/?probe=1f793dc2d3) | Nov 28, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [a48bfbc481](https://linux-hardware.org/?probe=a48bfbc481) | Nov 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [f009abd381](https://linux-hardware.org/?probe=f009abd381) | Nov 25, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [78992043bf](https://linux-hardware.org/?probe=78992043bf) | Nov 20, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f4c78fb767](https://linux-hardware.org/?probe=f4c78fb767) | Nov 19, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c845b4f25f](https://linux-hardware.org/?probe=c845b4f25f) | Nov 18, 2023 |
| Valve         | Jupiter                     | Notebook    | [97695463df](https://linux-hardware.org/?probe=97695463df) | Nov 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [8734420ff1](https://linux-hardware.org/?probe=8734420ff1) | Nov 17, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [9aa2678591](https://linux-hardware.org/?probe=9aa2678591) | Nov 15, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [6c51a94d03](https://linux-hardware.org/?probe=6c51a94d03) | Nov 15, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [d0f2727a4d](https://linux-hardware.org/?probe=d0f2727a4d) | Nov 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [e45cab7f2c](https://linux-hardware.org/?probe=e45cab7f2c) | Nov 12, 2023 |
| ASUSTek       | TUF H310-PLUS GAMING        | Desktop     | [b9e39aa8c1](https://linux-hardware.org/?probe=b9e39aa8c1) | Nov 10, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [02fa7cf5bb](https://linux-hardware.org/?probe=02fa7cf5bb) | Nov 03, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [6b6da0ca4a](https://linux-hardware.org/?probe=6b6da0ca4a) | Nov 01, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [3e7da65a41](https://linux-hardware.org/?probe=3e7da65a41) | Oct 27, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [6b9e5b921c](https://linux-hardware.org/?probe=6b9e5b921c) | Oct 27, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [5236a2eca3](https://linux-hardware.org/?probe=5236a2eca3) | Oct 26, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [6f746b3af3](https://linux-hardware.org/?probe=6f746b3af3) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [a9dd51be33](https://linux-hardware.org/?probe=a9dd51be33) | Oct 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [08387f2a94](https://linux-hardware.org/?probe=08387f2a94) | Oct 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e2b8718a7d](https://linux-hardware.org/?probe=e2b8718a7d) | Oct 19, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [81c485dfbe](https://linux-hardware.org/?probe=81c485dfbe) | Oct 16, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [6b86dab25f](https://linux-hardware.org/?probe=6b86dab25f) | Oct 16, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e29f6e9ba8](https://linux-hardware.org/?probe=e29f6e9ba8) | Oct 11, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [98784d1e51](https://linux-hardware.org/?probe=98784d1e51) | Oct 08, 2023 |
| Dynabook      | PORTEGE X30W-J              | Convertible | [aa212009a2](https://linux-hardware.org/?probe=aa212009a2) | Oct 06, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e1f02c6934](https://linux-hardware.org/?probe=e1f02c6934) | Oct 03, 2023 |
| HP            | ProBook 6560b               | Notebook    | [c4710bf9c2](https://linux-hardware.org/?probe=c4710bf9c2) | Oct 01, 2023 |
| HP            | 3397                        | Desktop     | [5740126c3c](https://linux-hardware.org/?probe=5740126c3c) | Sep 25, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [683cbd037a](https://linux-hardware.org/?probe=683cbd037a) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8064cec888](https://linux-hardware.org/?probe=8064cec888) | Sep 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [7cdaac7be4](https://linux-hardware.org/?probe=7cdaac7be4) | Sep 16, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [192e02b434](https://linux-hardware.org/?probe=192e02b434) | Sep 15, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [b06966adc5](https://linux-hardware.org/?probe=b06966adc5) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [9f459c45cc](https://linux-hardware.org/?probe=9f459c45cc) | Sep 14, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [40df085797](https://linux-hardware.org/?probe=40df085797) | Sep 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [78f326afa5](https://linux-hardware.org/?probe=78f326afa5) | Sep 12, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [f913de368f](https://linux-hardware.org/?probe=f913de368f) | Sep 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [423b8d7135](https://linux-hardware.org/?probe=423b8d7135) | Sep 07, 2023 |
| HP            | 3397                        | Desktop     | [b9dabe8514](https://linux-hardware.org/?probe=b9dabe8514) | Aug 31, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [dc63902a68](https://linux-hardware.org/?probe=dc63902a68) | Aug 31, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [082e1c2cc1](https://linux-hardware.org/?probe=082e1c2cc1) | Aug 24, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [b1beaf9e38](https://linux-hardware.org/?probe=b1beaf9e38) | Aug 22, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [088582c57c](https://linux-hardware.org/?probe=088582c57c) | Aug 15, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [4587b7ff26](https://linux-hardware.org/?probe=4587b7ff26) | Aug 14, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| Lenovo        | ThinkPad X1 Yoga 20FRS02... | Convertible | [ba520853af](https://linux-hardware.org/?probe=ba520853af) | Aug 10, 2023 |
| Lenovo        | ThinkPad X1 Yoga 20FRS02... | Convertible | [534fd57945](https://linux-hardware.org/?probe=534fd57945) | Aug 10, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| HP            | 3397                        | Desktop     | [d7edc80c00](https://linux-hardware.org/?probe=d7edc80c00) | Aug 08, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [ebf45c27f4](https://linux-hardware.org/?probe=ebf45c27f4) | Aug 07, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [221f9de00a](https://linux-hardware.org/?probe=221f9de00a) | Aug 06, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ea70e92c9a](https://linux-hardware.org/?probe=ea70e92c9a) | Aug 05, 2023 |
| GIADA         | Unknown                     | Notebook    | [cd8b23468a](https://linux-hardware.org/?probe=cd8b23468a) | Aug 03, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [9dcbf7b10c](https://linux-hardware.org/?probe=9dcbf7b10c) | Aug 03, 2023 |
| Toshiba       | Satellite C850-B239         | Notebook    | [a075f60c70](https://linux-hardware.org/?probe=a075f60c70) | Aug 02, 2023 |
| Unknown       | Unknown                     | Notebook    | [570c98e6ab](https://linux-hardware.org/?probe=570c98e6ab) | Aug 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [f54f3f3a4b](https://linux-hardware.org/?probe=f54f3f3a4b) | Aug 01, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70b94de26b](https://linux-hardware.org/?probe=70b94de26b) | Jul 31, 2023 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [42b35cd473](https://linux-hardware.org/?probe=42b35cd473) | Jul 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [fc294ac015](https://linux-hardware.org/?probe=fc294ac015) | Jul 27, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [9e156dd92f](https://linux-hardware.org/?probe=9e156dd92f) | Jul 26, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [35f41c1327](https://linux-hardware.org/?probe=35f41c1327) | Jul 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [f371e0efe5](https://linux-hardware.org/?probe=f371e0efe5) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [55639a6416](https://linux-hardware.org/?probe=55639a6416) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8b2077101c](https://linux-hardware.org/?probe=8b2077101c) | Jul 21, 2023 |
| ASUSTek       | H81M-V3                     | Desktop     | [017671472c](https://linux-hardware.org/?probe=017671472c) | Jul 15, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [ac10700edb](https://linux-hardware.org/?probe=ac10700edb) | Jul 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [adf89d2bba](https://linux-hardware.org/?probe=adf89d2bba) | Jul 12, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [35f03cf89f](https://linux-hardware.org/?probe=35f03cf89f) | Jul 10, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b6c778034c](https://linux-hardware.org/?probe=b6c778034c) | Jul 06, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [4d8e159540](https://linux-hardware.org/?probe=4d8e159540) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b7222ef19f](https://linux-hardware.org/?probe=b7222ef19f) | Jul 03, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [6dbef58b31](https://linux-hardware.org/?probe=6dbef58b31) | Jul 02, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [4e2b34c387](https://linux-hardware.org/?probe=4e2b34c387) | Jul 02, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [02a31c9704](https://linux-hardware.org/?probe=02a31c9704) | Jul 01, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [45739a208c](https://linux-hardware.org/?probe=45739a208c) | Jul 01, 2023 |
| Dell          | Latitude 3520               | Notebook    | [6e996e08f9](https://linux-hardware.org/?probe=6e996e08f9) | Jul 01, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c3ae8b2d38](https://linux-hardware.org/?probe=c3ae8b2d38) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [39ec9cf6c4](https://linux-hardware.org/?probe=39ec9cf6c4) | Jun 27, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [dff301aade](https://linux-hardware.org/?probe=dff301aade) | Jun 25, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [c756e98d81](https://linux-hardware.org/?probe=c756e98d81) | Jun 24, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [874b84ce94](https://linux-hardware.org/?probe=874b84ce94) | Jun 24, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [4f0ec49165](https://linux-hardware.org/?probe=4f0ec49165) | Jun 17, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7da8691a87](https://linux-hardware.org/?probe=7da8691a87) | Jun 17, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [436b4c3ab9](https://linux-hardware.org/?probe=436b4c3ab9) | Jun 16, 2023 |
| DJI           | MANIFOLD 2-C                | Desktop     | [44edfc848e](https://linux-hardware.org/?probe=44edfc848e) | Jun 13, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [5bc14dc937](https://linux-hardware.org/?probe=5bc14dc937) | Jun 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [8c9765a31c](https://linux-hardware.org/?probe=8c9765a31c) | Jun 11, 2023 |
| Toshiba       | Satellite L635              | Notebook    | [4f124d1525](https://linux-hardware.org/?probe=4f124d1525) | Jun 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [d21eb9432c](https://linux-hardware.org/?probe=d21eb9432c) | Jun 03, 2023 |
| Gigabyte      | P75-D3                      | Desktop     | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| Dell          | XPS 15 9575                 | Convertible | [bed704ac70](https://linux-hardware.org/?probe=bed704ac70) | May 27, 2023 |
| Dell          | Latitude E6520              | Notebook    | [bb8bc9b8ae](https://linux-hardware.org/?probe=bb8bc9b8ae) | May 24, 2023 |
| Google        | Akemi                       | Notebook    | [595f8b1a24](https://linux-hardware.org/?probe=595f8b1a24) | May 20, 2023 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [0d337f6d69](https://linux-hardware.org/?probe=0d337f6d69) | May 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [93979d632e](https://linux-hardware.org/?probe=93979d632e) | May 15, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [155b921e10](https://linux-hardware.org/?probe=155b921e10) | May 13, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [de65a79bf1](https://linux-hardware.org/?probe=de65a79bf1) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [4b76463d57](https://linux-hardware.org/?probe=4b76463d57) | May 06, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [3da35d8bc2](https://linux-hardware.org/?probe=3da35d8bc2) | May 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ae500cf4af](https://linux-hardware.org/?probe=ae500cf4af) | Apr 22, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [3e9d210a94](https://linux-hardware.org/?probe=3e9d210a94) | Apr 16, 2023 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [4b338ba7f9](https://linux-hardware.org/?probe=4b338ba7f9) | Apr 15, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [84c8a107d4](https://linux-hardware.org/?probe=84c8a107d4) | Apr 06, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [39e1087c79](https://linux-hardware.org/?probe=39e1087c79) | Apr 04, 2023 |
| Dell          | Latitude 7275               | Tablet      | [c118ca04bc](https://linux-hardware.org/?probe=c118ca04bc) | Apr 01, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [46dc3b9655](https://linux-hardware.org/?probe=46dc3b9655) | Mar 31, 2023 |
| ASUSTek       | H81M-V3                     | Desktop     | [fd123bea36](https://linux-hardware.org/?probe=fd123bea36) | Mar 29, 2023 |
| ASUSTek       | H81M-V3                     | Desktop     | [ce98454e55](https://linux-hardware.org/?probe=ce98454e55) | Mar 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [70e9f673c2](https://linux-hardware.org/?probe=70e9f673c2) | Mar 23, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70a7fd895e](https://linux-hardware.org/?probe=70a7fd895e) | Mar 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ca34d8e7d4](https://linux-hardware.org/?probe=ca34d8e7d4) | Mar 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [9509c77e2b](https://linux-hardware.org/?probe=9509c77e2b) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [70e1aa9793](https://linux-hardware.org/?probe=70e1aa9793) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Sony          | VGN-FZ250E                  | Notebook    | [ca7937209b](https://linux-hardware.org/?probe=ca7937209b) | Mar 06, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [82889a28a0](https://linux-hardware.org/?probe=82889a28a0) | Feb 23, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [27f07447f7](https://linux-hardware.org/?probe=27f07447f7) | Feb 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d488fc0d9a](https://linux-hardware.org/?probe=d488fc0d9a) | Feb 22, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [76cbc7df6d](https://linux-hardware.org/?probe=76cbc7df6d) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [e70b65f78d](https://linux-hardware.org/?probe=e70b65f78d) | Feb 20, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [61befa2690](https://linux-hardware.org/?probe=61befa2690) | Feb 18, 2023 |
| Dell          | Latitude E6520              | Notebook    | [b04c6e8984](https://linux-hardware.org/?probe=b04c6e8984) | Feb 18, 2023 |
| HP            | 8053                        | Desktop     | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| HUAWEI        | MateBook E                  | Tablet      | [072689df7b](https://linux-hardware.org/?probe=072689df7b) | Feb 13, 2023 |
| HUAWEI        | MateBook E                  | Tablet      | [a31eb3e8aa](https://linux-hardware.org/?probe=a31eb3e8aa) | Feb 13, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c4eb0b2a62](https://linux-hardware.org/?probe=c4eb0b2a62) | Feb 11, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [dba0167a53](https://linux-hardware.org/?probe=dba0167a53) | Feb 09, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [ad403b2126](https://linux-hardware.org/?probe=ad403b2126) | Feb 09, 2023 |
| Medion        | MS-7797                     | Desktop     | [3421cd9be4](https://linux-hardware.org/?probe=3421cd9be4) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0e931084a7](https://linux-hardware.org/?probe=0e931084a7) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5566e6facb](https://linux-hardware.org/?probe=5566e6facb) | Feb 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6c1ee5e95d](https://linux-hardware.org/?probe=6c1ee5e95d) | Feb 04, 2023 |
| Unknown       | 1.0                         | Desktop     | [402bce9e43](https://linux-hardware.org/?probe=402bce9e43) | Feb 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bd0b1f7e94](https://linux-hardware.org/?probe=bd0b1f7e94) | Jan 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [a22071f9ec](https://linux-hardware.org/?probe=a22071f9ec) | Jan 26, 2023 |
| Unknown       | 1.0                         | Desktop     | [85d36881c1](https://linux-hardware.org/?probe=85d36881c1) | Jan 26, 2023 |
| Unknown       | 1.0                         | Desktop     | [a25e1d1008](https://linux-hardware.org/?probe=a25e1d1008) | Jan 26, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [70559c048c](https://linux-hardware.org/?probe=70559c048c) | Jan 25, 2023 |
| Unknown       | 1.0                         | Desktop     | [99201dd05a](https://linux-hardware.org/?probe=99201dd05a) | Jan 24, 2023 |
| Unknown       | 1.0                         | Desktop     | [678e6d3875](https://linux-hardware.org/?probe=678e6d3875) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [476d23dca7](https://linux-hardware.org/?probe=476d23dca7) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| HUAWEI        | MateBook E                  | Tablet      | [8298edf3bc](https://linux-hardware.org/?probe=8298edf3bc) | Jan 19, 2023 |
| HP            | Unknown                     | Notebook    | [fedf225852](https://linux-hardware.org/?probe=fedf225852) | Jan 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| HP            | Unknown                     | Notebook    | [8b89da1da5](https://linux-hardware.org/?probe=8b89da1da5) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [b927a3e937](https://linux-hardware.org/?probe=b927a3e937) | Jan 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [2b476ca470](https://linux-hardware.org/?probe=2b476ca470) | Jan 16, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [b69b2d21e9](https://linux-hardware.org/?probe=b69b2d21e9) | Jan 15, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [26379f8b8d](https://linux-hardware.org/?probe=26379f8b8d) | Jan 11, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [71d684a605](https://linux-hardware.org/?probe=71d684a605) | Jan 11, 2023 |
| Toshiba       | Satellite C850-B561         | Notebook    | [562d6cde14](https://linux-hardware.org/?probe=562d6cde14) | Jan 11, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [5ac16a435c](https://linux-hardware.org/?probe=5ac16a435c) | Jan 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [e662d0e58a](https://linux-hardware.org/?probe=e662d0e58a) | Jan 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [2c6b6c2558](https://linux-hardware.org/?probe=2c6b6c2558) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [0968211c5b](https://linux-hardware.org/?probe=0968211c5b) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [4195800fa5](https://linux-hardware.org/?probe=4195800fa5) | Jan 04, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [3a801b9e90](https://linux-hardware.org/?probe=3a801b9e90) | Jan 01, 2023 |
| Acer          | Spin SP513-54N              | Convertible | [0cb6dfa7ce](https://linux-hardware.org/?probe=0cb6dfa7ce) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [eeec310401](https://linux-hardware.org/?probe=eeec310401) | Dec 26, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [13d0daca4c](https://linux-hardware.org/?probe=13d0daca4c) | Dec 23, 2022 |
| HP            | 212B                        | Desktop     | [3df121c98b](https://linux-hardware.org/?probe=3df121c98b) | Dec 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [42584fd968](https://linux-hardware.org/?probe=42584fd968) | Dec 11, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [eb95cbbbe0](https://linux-hardware.org/?probe=eb95cbbbe0) | Dec 03, 2022 |
| Toshiba       | Satellite L635              | Notebook    | [be223c0ff1](https://linux-hardware.org/?probe=be223c0ff1) | Dec 03, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [a92a0830e9](https://linux-hardware.org/?probe=a92a0830e9) | Nov 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [45dc299d52](https://linux-hardware.org/?probe=45dc299d52) | Nov 25, 2022 |
| HP            | 212B                        | Desktop     | [d5cc313fba](https://linux-hardware.org/?probe=d5cc313fba) | Nov 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [7de2db4d3a](https://linux-hardware.org/?probe=7de2db4d3a) | Nov 18, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [5ff7cf2e42](https://linux-hardware.org/?probe=5ff7cf2e42) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4c0e49ae2b](https://linux-hardware.org/?probe=4c0e49ae2b) | Oct 23, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [3e86b56fb8](https://linux-hardware.org/?probe=3e86b56fb8) | Oct 23, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [7f90427c64](https://linux-hardware.org/?probe=7f90427c64) | Oct 15, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [8eaf391b08](https://linux-hardware.org/?probe=8eaf391b08) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f7f3439df7](https://linux-hardware.org/?probe=f7f3439df7) | Oct 11, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [61f05a7c32](https://linux-hardware.org/?probe=61f05a7c32) | Oct 10, 2022 |
| Sony          | SVF15A13SAB                 | Notebook    | [7c39add556](https://linux-hardware.org/?probe=7c39add556) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [de59de7b14](https://linux-hardware.org/?probe=de59de7b14) | Oct 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [bf7151a851](https://linux-hardware.org/?probe=bf7151a851) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| Dell          | G15 5515                    | Notebook    | [ae769dae75](https://linux-hardware.org/?probe=ae769dae75) | Sep 24, 2022 |
| Dell          | G15 5515                    | Notebook    | [893c248dec](https://linux-hardware.org/?probe=893c248dec) | Sep 24, 2022 |
| Dell          | G15 5515                    | Notebook    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [a934e23e1f](https://linux-hardware.org/?probe=a934e23e1f) | Sep 16, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c65050e714](https://linux-hardware.org/?probe=c65050e714) | Sep 09, 2022 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [8373c5268a](https://linux-hardware.org/?probe=8373c5268a) | Sep 05, 2022 |
| Dell          | Latitude 7275               | Tablet      | [fce77a6b4b](https://linux-hardware.org/?probe=fce77a6b4b) | Aug 31, 2022 |
| Dell          | Latitude 7275               | Tablet      | [896ceefe29](https://linux-hardware.org/?probe=896ceefe29) | Aug 31, 2022 |
| Notebook      | NH5xAx                      | Notebook    | [e8487cd15f](https://linux-hardware.org/?probe=e8487cd15f) | Aug 31, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [ef34b3c3aa](https://linux-hardware.org/?probe=ef34b3c3aa) | Aug 31, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [b87b0407d9](https://linux-hardware.org/?probe=b87b0407d9) | Aug 29, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [fbb579a5d6](https://linux-hardware.org/?probe=fbb579a5d6) | Aug 29, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [4ecdbb8b4b](https://linux-hardware.org/?probe=4ecdbb8b4b) | Aug 15, 2022 |
| Acer          | Aspire 4752                 | Notebook    | [9854c38629](https://linux-hardware.org/?probe=9854c38629) | Aug 14, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [154440549c](https://linux-hardware.org/?probe=154440549c) | Aug 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [4f12a5e11e](https://linux-hardware.org/?probe=4f12a5e11e) | Aug 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ed6b6ce93e](https://linux-hardware.org/?probe=ed6b6ce93e) | Aug 03, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [1364037a8f](https://linux-hardware.org/?probe=1364037a8f) | Aug 01, 2022 |
| eMachines     | Unknown                     | Notebook    | [8c6dcb08a7](https://linux-hardware.org/?probe=8c6dcb08a7) | Jul 31, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [1ff4c1d5df](https://linux-hardware.org/?probe=1ff4c1d5df) | Jul 10, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [5082bf92e9](https://linux-hardware.org/?probe=5082bf92e9) | Jun 26, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [d0edbadf25](https://linux-hardware.org/?probe=d0edbadf25) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [4f3e4e102f](https://linux-hardware.org/?probe=4f3e4e102f) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [550ed4b1c0](https://linux-hardware.org/?probe=550ed4b1c0) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [e6e0165682](https://linux-hardware.org/?probe=e6e0165682) | Jun 14, 2022 |
| Dell          | 06WXJT A02                  | Server      | [2dfd532279](https://linux-hardware.org/?probe=2dfd532279) | Jun 08, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [870c420b4b](https://linux-hardware.org/?probe=870c420b4b) | Jun 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [34a1b11f96](https://linux-hardware.org/?probe=34a1b11f96) | Jun 02, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [d7d06bf7ef](https://linux-hardware.org/?probe=d7d06bf7ef) | May 26, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [da5f6c9ba0](https://linux-hardware.org/?probe=da5f6c9ba0) | May 23, 2022 |
| MSI           | GF63 Thin 8RCS              | Notebook    | [8cd1ebfa12](https://linux-hardware.org/?probe=8cd1ebfa12) | May 22, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c34e9b0da7](https://linux-hardware.org/?probe=c34e9b0da7) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [b6dc8a3fc8](https://linux-hardware.org/?probe=b6dc8a3fc8) | May 05, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [51d4e9a2e2](https://linux-hardware.org/?probe=51d4e9a2e2) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| Dell          | 0M9KCM A01                  | Desktop     | [76d9159d32](https://linux-hardware.org/?probe=76d9159d32) | May 03, 2022 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [74e69f5610](https://linux-hardware.org/?probe=74e69f5610) | May 03, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2c6195f0b8](https://linux-hardware.org/?probe=2c6195f0b8) | May 02, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [9cab38ff4f](https://linux-hardware.org/?probe=9cab38ff4f) | May 01, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [794ab7ba41](https://linux-hardware.org/?probe=794ab7ba41) | Apr 28, 2022 |
| Dell          | Latitude 7275               | Tablet      | [b7443972f3](https://linux-hardware.org/?probe=b7443972f3) | Apr 28, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [037284e799](https://linux-hardware.org/?probe=037284e799) | Apr 23, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [8c3b142c85](https://linux-hardware.org/?probe=8c3b142c85) | Apr 23, 2022 |
| Dell          | Latitude 7275               | Tablet      | [8b373dc563](https://linux-hardware.org/?probe=8b373dc563) | Apr 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [14fa81fab9](https://linux-hardware.org/?probe=14fa81fab9) | Apr 18, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [196f849315](https://linux-hardware.org/?probe=196f849315) | Apr 18, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [1f799cdbef](https://linux-hardware.org/?probe=1f799cdbef) | Apr 09, 2022 |
| Unknown       | HX90                        | Desktop     | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [45548a6fe5](https://linux-hardware.org/?probe=45548a6fe5) | Apr 07, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [1f1a2dbacc](https://linux-hardware.org/?probe=1f1a2dbacc) | Apr 05, 2022 |
| Dell          | Latitude 7275               | Tablet      | [4e3f9ca88e](https://linux-hardware.org/?probe=4e3f9ca88e) | Apr 02, 2022 |
| Unknown       | HX90                        | Desktop     | [9cb3335bb0](https://linux-hardware.org/?probe=9cb3335bb0) | Apr 01, 2022 |
| Unknown       | HX90                        | Desktop     | [cd18483c45](https://linux-hardware.org/?probe=cd18483c45) | Apr 01, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [464e58f41f](https://linux-hardware.org/?probe=464e58f41f) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [567627010e](https://linux-hardware.org/?probe=567627010e) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [304f31d5a7](https://linux-hardware.org/?probe=304f31d5a7) | Mar 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bc999f46f9](https://linux-hardware.org/?probe=bc999f46f9) | Mar 28, 2022 |
| Dell          | Latitude 7275               | Tablet      | [1e0ad3b3cd](https://linux-hardware.org/?probe=1e0ad3b3cd) | Mar 27, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [0e1e24ffe0](https://linux-hardware.org/?probe=0e1e24ffe0) | Mar 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| Dell          | Inspiron 14-3467            | Notebook    | [50131c5da4](https://linux-hardware.org/?probe=50131c5da4) | Mar 21, 2022 |
| Acer          | AO751h                      | Notebook    | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [1f00b8ed57](https://linux-hardware.org/?probe=1f00b8ed57) | Mar 21, 2022 |
| Acer          | AO751h                      | Notebook    | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [d52410b817](https://linux-hardware.org/?probe=d52410b817) | Mar 18, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [08239c1637](https://linux-hardware.org/?probe=08239c1637) | Mar 09, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [ce709ce28f](https://linux-hardware.org/?probe=ce709ce28f) | Mar 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [8a51a8730b](https://linux-hardware.org/?probe=8a51a8730b) | Feb 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b2f7222ddb](https://linux-hardware.org/?probe=b2f7222ddb) | Feb 27, 2022 |
| Dell          | 0WWJRX A00                  | Desktop     | [bb620cc0f9](https://linux-hardware.org/?probe=bb620cc0f9) | Feb 26, 2022 |
| Gigabyte      | MJPLNAB-00                  | Desktop     | [007ec5dbf5](https://linux-hardware.org/?probe=007ec5dbf5) | Feb 24, 2022 |
| Dell          | Latitude 7275               | Tablet      | [14bcc9219c](https://linux-hardware.org/?probe=14bcc9219c) | Feb 18, 2022 |
| Dell          | Latitude 7275               | Tablet      | [143e5a0a20](https://linux-hardware.org/?probe=143e5a0a20) | Feb 16, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [43b019326c](https://linux-hardware.org/?probe=43b019326c) | Feb 12, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [70f23c3da0](https://linux-hardware.org/?probe=70f23c3da0) | Feb 12, 2022 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [fe9b9a47f1](https://linux-hardware.org/?probe=fe9b9a47f1) | Feb 11, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [73767731d9](https://linux-hardware.org/?probe=73767731d9) | Feb 11, 2022 |
| ASRock        | B365M Phantom Gaming 4      | Desktop     | [9dd59e5403](https://linux-hardware.org/?probe=9dd59e5403) | Feb 08, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e0748343d9](https://linux-hardware.org/?probe=e0748343d9) | Feb 08, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [40c74584ee](https://linux-hardware.org/?probe=40c74584ee) | Feb 03, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| HP            | 15                          | Notebook    | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [92f528e80b](https://linux-hardware.org/?probe=92f528e80b) | Jan 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [4debe87ebd](https://linux-hardware.org/?probe=4debe87ebd) | Jan 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [261fe8bda7](https://linux-hardware.org/?probe=261fe8bda7) | Jan 07, 2022 |
| Sony          | VPCCA35FA                   | Notebook    | [85f4fcc0b6](https://linux-hardware.org/?probe=85f4fcc0b6) | Jan 03, 2022 |
| Sony          | VPCCA35FA                   | Notebook    | [f69299cbfb](https://linux-hardware.org/?probe=f69299cbfb) | Jan 03, 2022 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [3fbda09d01](https://linux-hardware.org/?probe=3fbda09d01) | Jan 01, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [be19f6df45](https://linux-hardware.org/?probe=be19f6df45) | Dec 29, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Packard Be... | EasyNote TJ65               | Notebook    | [b98b9252fa](https://linux-hardware.org/?probe=b98b9252fa) | Dec 29, 2021 |
| MSI           | MS-7529                     | Desktop     | [c9b87dcf45](https://linux-hardware.org/?probe=c9b87dcf45) | Dec 27, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [938d24e76e](https://linux-hardware.org/?probe=938d24e76e) | Dec 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [046dcdd20d](https://linux-hardware.org/?probe=046dcdd20d) | Dec 25, 2021 |
| Acer          | Switch SW312-31             | Tablet      | [af71cff698](https://linux-hardware.org/?probe=af71cff698) | Dec 21, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [609baca194](https://linux-hardware.org/?probe=609baca194) | Dec 16, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [35ec8b1dbb](https://linux-hardware.org/?probe=35ec8b1dbb) | Dec 16, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f73c5829df](https://linux-hardware.org/?probe=f73c5829df) | Dec 12, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [bb9141f09c](https://linux-hardware.org/?probe=bb9141f09c) | Dec 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [b3c42ca2c2](https://linux-hardware.org/?probe=b3c42ca2c2) | Dec 09, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [2a151de62b](https://linux-hardware.org/?probe=2a151de62b) | Dec 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [830882c4e6](https://linux-hardware.org/?probe=830882c4e6) | Dec 07, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [25ca2e2c75](https://linux-hardware.org/?probe=25ca2e2c75) | Dec 04, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [5cc2fbfef5](https://linux-hardware.org/?probe=5cc2fbfef5) | Dec 04, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [e3acd70236](https://linux-hardware.org/?probe=e3acd70236) | Dec 02, 2021 |
| Lenovo        | ThinkPad E14 20RA008CAD     | Notebook    | [35fab17b69](https://linux-hardware.org/?probe=35fab17b69) | Dec 01, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [46d5208475](https://linux-hardware.org/?probe=46d5208475) | Nov 28, 2021 |
| Dell          | 0T656F A02                  | Desktop     | [a1abd4e08e](https://linux-hardware.org/?probe=a1abd4e08e) | Nov 26, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [e37587fbac](https://linux-hardware.org/?probe=e37587fbac) | Nov 23, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [b050debd0a](https://linux-hardware.org/?probe=b050debd0a) | Nov 22, 2021 |
| Dell          | G3 3590                     | Notebook    | [605f0870d0](https://linux-hardware.org/?probe=605f0870d0) | Nov 16, 2021 |
| Dell          | G3 3590                     | Notebook    | [5bfafc889c](https://linux-hardware.org/?probe=5bfafc889c) | Nov 16, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [0ff55f060f](https://linux-hardware.org/?probe=0ff55f060f) | Nov 14, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo        | V570 1066AJU                | Notebook    | [ffb36aac10](https://linux-hardware.org/?probe=ffb36aac10) | Nov 05, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [41451fb2a2](https://linux-hardware.org/?probe=41451fb2a2) | Nov 05, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [a5026c4013](https://linux-hardware.org/?probe=a5026c4013) | Oct 21, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [20ca9b4679](https://linux-hardware.org/?probe=20ca9b4679) | Oct 18, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [5233ea30c6](https://linux-hardware.org/?probe=5233ea30c6) | Oct 09, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [65c4bea87a](https://linux-hardware.org/?probe=65c4bea87a) | Oct 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [d91c23c12c](https://linux-hardware.org/?probe=d91c23c12c) | Oct 08, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b22e6dc21a](https://linux-hardware.org/?probe=b22e6dc21a) | Oct 05, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [428e41ed23](https://linux-hardware.org/?probe=428e41ed23) | Oct 05, 2021 |
| Lenovo        | ThinkPad P52s 20LBS0JC00    | Notebook    | [4c8c63da2f](https://linux-hardware.org/?probe=4c8c63da2f) | Oct 05, 2021 |
| HP            | Laptop 15-da2xxx            | Notebook    | [2e99b047ff](https://linux-hardware.org/?probe=2e99b047ff) | Oct 04, 2021 |
| Dell          | Latitude 7275               | Tablet      | [c844ef39cd](https://linux-hardware.org/?probe=c844ef39cd) | Oct 03, 2021 |
| Acer          | Switch SW312-31             | Tablet      | [85a91a83fa](https://linux-hardware.org/?probe=85a91a83fa) | Oct 01, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [de6b4e47d4](https://linux-hardware.org/?probe=de6b4e47d4) | Oct 01, 2021 |
| HP            | Laptop 15-da2xxx            | Notebook    | [28332170d1](https://linux-hardware.org/?probe=28332170d1) | Sep 28, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [8c04a9e8df](https://linux-hardware.org/?probe=8c04a9e8df) | Sep 22, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [19374f68da](https://linux-hardware.org/?probe=19374f68da) | Sep 21, 2021 |
| Dell          | 054KM3 A01                  | Desktop     | [6d277dcd36](https://linux-hardware.org/?probe=6d277dcd36) | Sep 18, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [6998aee6d0](https://linux-hardware.org/?probe=6998aee6d0) | Sep 02, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [e7a572f322](https://linux-hardware.org/?probe=e7a572f322) | Aug 29, 2021 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [ef4fb4b996](https://linux-hardware.org/?probe=ef4fb4b996) | Aug 28, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e5251674c0](https://linux-hardware.org/?probe=e5251674c0) | Aug 25, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [99dbadcdde](https://linux-hardware.org/?probe=99dbadcdde) | Aug 22, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [3d5e02e265](https://linux-hardware.org/?probe=3d5e02e265) | Aug 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [b87783b728](https://linux-hardware.org/?probe=b87783b728) | Aug 18, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [4c8282bb42](https://linux-hardware.org/?probe=4c8282bb42) | Aug 16, 2021 |
| Dell          | Latitude E5470              | Notebook    | [f91acefb07](https://linux-hardware.org/?probe=f91acefb07) | Aug 14, 2021 |
| Dell          | 03X6X0 A06                  | Server      | [d52db39eeb](https://linux-hardware.org/?probe=d52db39eeb) | Jul 26, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [162b090056](https://linux-hardware.org/?probe=162b090056) | Jul 14, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [8d7689bceb](https://linux-hardware.org/?probe=8d7689bceb) | Jul 14, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [5bcc11cd03](https://linux-hardware.org/?probe=5bcc11cd03) | Jul 08, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [9bae1ef315](https://linux-hardware.org/?probe=9bae1ef315) | Jul 07, 2021 |
| ASUSTek       | K43SJ                       | Notebook    | [f4702e95b4](https://linux-hardware.org/?probe=f4702e95b4) | Jul 05, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [08fad9a114](https://linux-hardware.org/?probe=08fad9a114) | Jul 03, 2021 |
| Dell          | 0W0CHX A01                  | Desktop     | [e0a09aa1a5](https://linux-hardware.org/?probe=e0a09aa1a5) | Jul 01, 2021 |
| Dell          | G3 3590                     | Notebook    | [06d10d0717](https://linux-hardware.org/?probe=06d10d0717) | Jun 26, 2021 |
| Dell          | 0XHGV1 A01                  | Desktop     | [4fcd4b7e98](https://linux-hardware.org/?probe=4fcd4b7e98) | Jun 22, 2021 |
| Intel         | BTC-T37                     | Desktop     | [6cd9eb4fd4](https://linux-hardware.org/?probe=6cd9eb4fd4) | Jun 19, 2021 |
| Intel         | BTC-T37                     | Desktop     | [3f0a790d81](https://linux-hardware.org/?probe=3f0a790d81) | Jun 19, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [06f25de7e3](https://linux-hardware.org/?probe=06f25de7e3) | Jun 19, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [3fcbd5cd4f](https://linux-hardware.org/?probe=3fcbd5cd4f) | Jun 18, 2021 |
| Dell          | G3 3590                     | Notebook    | [877018f0d3](https://linux-hardware.org/?probe=877018f0d3) | Jun 18, 2021 |
| Dell          | G3 3590                     | Notebook    | [adf875d64d](https://linux-hardware.org/?probe=adf875d64d) | Jun 17, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [7e5e7767c0](https://linux-hardware.org/?probe=7e5e7767c0) | Jun 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3a001e377](https://linux-hardware.org/?probe=d3a001e377) | Jun 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a4d00095a1](https://linux-hardware.org/?probe=a4d00095a1) | Jun 01, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [88e51bfd39](https://linux-hardware.org/?probe=88e51bfd39) | May 23, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [ea32add5cd](https://linux-hardware.org/?probe=ea32add5cd) | May 20, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [96e19f007a](https://linux-hardware.org/?probe=96e19f007a) | May 20, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cfcef26a52](https://linux-hardware.org/?probe=cfcef26a52) | May 20, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [0d9f5609e7](https://linux-hardware.org/?probe=0d9f5609e7) | May 20, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [ed8c410826](https://linux-hardware.org/?probe=ed8c410826) | May 18, 2021 |
| Dell          | 042P49 A00                  | Desktop     | [f146c310d6](https://linux-hardware.org/?probe=f146c310d6) | May 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1d4c05756f](https://linux-hardware.org/?probe=1d4c05756f) | May 01, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [febcf69966](https://linux-hardware.org/?probe=febcf69966) | Apr 28, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [34b2d651e1](https://linux-hardware.org/?probe=34b2d651e1) | Apr 28, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [9b03874730](https://linux-hardware.org/?probe=9b03874730) | Apr 27, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e0acc229ef](https://linux-hardware.org/?probe=e0acc229ef) | Apr 25, 2021 |
| Dell          | Latitude E7470              | Notebook    | [1058573f86](https://linux-hardware.org/?probe=1058573f86) | Apr 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [14fd40d980](https://linux-hardware.org/?probe=14fd40d980) | Apr 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0b31da2d02](https://linux-hardware.org/?probe=0b31da2d02) | Apr 16, 2021 |
| Gigabyte      | B75M-HD3                    | Desktop     | [82dd7f530a](https://linux-hardware.org/?probe=82dd7f530a) | Apr 09, 2021 |
| Gigabyte      | B75M-HD3                    | Desktop     | [f97ecb74c0](https://linux-hardware.org/?probe=f97ecb74c0) | Apr 09, 2021 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [cd64675ac7](https://linux-hardware.org/?probe=cd64675ac7) | Mar 30, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| Toshiba       | Satellite S55t-A            | Notebook    | [9ede240e19](https://linux-hardware.org/?probe=9ede240e19) | Mar 20, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [7d8acdd5b6](https://linux-hardware.org/?probe=7d8acdd5b6) | Mar 19, 2021 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [f568952b1d](https://linux-hardware.org/?probe=f568952b1d) | Mar 10, 2021 |
| Huanan        | X99-F8                      | Desktop     | [3bbee45dc4](https://linux-hardware.org/?probe=3bbee45dc4) | Mar 10, 2021 |
| Toshiba       | Satellite S55t-A            | Notebook    | [5aa53770bf](https://linux-hardware.org/?probe=5aa53770bf) | Mar 06, 2021 |
| Toshiba       | Satellite S55t-A            | Notebook    | [5ed863271a](https://linux-hardware.org/?probe=5ed863271a) | Mar 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c03aab940e](https://linux-hardware.org/?probe=c03aab940e) | Feb 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [66003aa802](https://linux-hardware.org/?probe=66003aa802) | Feb 28, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [290dbb71c2](https://linux-hardware.org/?probe=290dbb71c2) | Feb 25, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [99ee0e5718](https://linux-hardware.org/?probe=99ee0e5718) | Feb 24, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [89497c0f27](https://linux-hardware.org/?probe=89497c0f27) | Feb 23, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [260d78f7c8](https://linux-hardware.org/?probe=260d78f7c8) | Feb 20, 2021 |
| HP            | Pavilion g6                 | Notebook    | [30bcebb4be](https://linux-hardware.org/?probe=30bcebb4be) | Feb 16, 2021 |
| HP            | 8591                        | Desktop     | [b6b7f6af35](https://linux-hardware.org/?probe=b6b7f6af35) | Feb 15, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [c8b28bb334](https://linux-hardware.org/?probe=c8b28bb334) | Feb 13, 2021 |
| Lenovo        | ThinkPad E460 20ET000MAD    | Notebook    | [cd000b8e6b](https://linux-hardware.org/?probe=cd000b8e6b) | Feb 11, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [5ed908976b](https://linux-hardware.org/?probe=5ed908976b) | Feb 09, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [5407a15ab7](https://linux-hardware.org/?probe=5407a15ab7) | Feb 09, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [0802cedb25](https://linux-hardware.org/?probe=0802cedb25) | Feb 09, 2021 |
| Dell          | Latitude E4310              | Notebook    | [9c6781e592](https://linux-hardware.org/?probe=9c6781e592) | Feb 08, 2021 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [1d97b5c83d](https://linux-hardware.org/?probe=1d97b5c83d) | Jan 31, 2021 |
| ASUSTek       | ROG Strix G512LWS_G512LW... | Notebook    | [d4d3110510](https://linux-hardware.org/?probe=d4d3110510) | Jan 29, 2021 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [5911afaa7a](https://linux-hardware.org/?probe=5911afaa7a) | Jan 27, 2021 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [6bdd3b4a5d](https://linux-hardware.org/?probe=6bdd3b4a5d) | Jan 27, 2021 |
| Acer          | Spin SP111-33               | Convertible | [0a09d00b74](https://linux-hardware.org/?probe=0a09d00b74) | Jan 23, 2021 |
| Toshiba       | Satellite C855D             | Notebook    | [46d5bf62c7](https://linux-hardware.org/?probe=46d5bf62c7) | Jan 19, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [e289a86560](https://linux-hardware.org/?probe=e289a86560) | Jan 16, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [99f1a1ac09](https://linux-hardware.org/?probe=99f1a1ac09) | Jan 16, 2021 |
| Sony          | VGN-FZ250E                  | Notebook    | [d0d77ffe81](https://linux-hardware.org/?probe=d0d77ffe81) | Jan 15, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [92ea4004af](https://linux-hardware.org/?probe=92ea4004af) | Jan 15, 2021 |
| Sony          | VGN-FZ250E                  | Notebook    | [68ddc53941](https://linux-hardware.org/?probe=68ddc53941) | Jan 14, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [b21e44d0c4](https://linux-hardware.org/?probe=b21e44d0c4) | Jan 11, 2021 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [e57dfe6f39](https://linux-hardware.org/?probe=e57dfe6f39) | Dec 30, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [2249011658](https://linux-hardware.org/?probe=2249011658) | Dec 30, 2020 |
| Dell          | 0GN6JF A01                  | Desktop     | [b4ea210c79](https://linux-hardware.org/?probe=b4ea210c79) | Dec 27, 2020 |
| Dell          | Vostro 5470                 | Notebook    | [216df384d8](https://linux-hardware.org/?probe=216df384d8) | Dec 22, 2020 |
| Dell          | Vostro 5470                 | Notebook    | [bec1b16786](https://linux-hardware.org/?probe=bec1b16786) | Dec 22, 2020 |
| LG Electro... | R490-G.ARL5RE2              | Notebook    | [58f0c96534](https://linux-hardware.org/?probe=58f0c96534) | Dec 16, 2020 |
| OEM           | B250                        | Desktop     | [80af247c92](https://linux-hardware.org/?probe=80af247c92) | Dec 09, 2020 |
| HP            | 198E                        | Desktop     | [d6e4336d03](https://linux-hardware.org/?probe=d6e4336d03) | Dec 08, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [6c1033e9f9](https://linux-hardware.org/?probe=6c1033e9f9) | Dec 04, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [1e0a7199b7](https://linux-hardware.org/?probe=1e0a7199b7) | Dec 03, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [239675db8d](https://linux-hardware.org/?probe=239675db8d) | Nov 25, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [dfcc723611](https://linux-hardware.org/?probe=dfcc723611) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b164be6cfc](https://linux-hardware.org/?probe=b164be6cfc) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [a3ffdab533](https://linux-hardware.org/?probe=a3ffdab533) | Nov 16, 2020 |
| HP            | 843C                        | Desktop     | [fd8c0fa877](https://linux-hardware.org/?probe=fd8c0fa877) | Nov 10, 2020 |
| OEM           | B250                        | Desktop     | [f6bcb7135c](https://linux-hardware.org/?probe=f6bcb7135c) | Nov 10, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | Notebook    | [cce5403051](https://linux-hardware.org/?probe=cce5403051) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| I-Life Dig... | ZED Air Plus                | Notebook    | [b1a43bf9f2](https://linux-hardware.org/?probe=b1a43bf9f2) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [c0ad42acb0](https://linux-hardware.org/?probe=c0ad42acb0) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [b5e6f52433](https://linux-hardware.org/?probe=b5e6f52433) | Nov 04, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e9ca4c8d42](https://linux-hardware.org/?probe=e9ca4c8d42) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [4a2a5fd18c](https://linux-hardware.org/?probe=4a2a5fd18c) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c45580b2f3](https://linux-hardware.org/?probe=c45580b2f3) | Oct 28, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [1816b1fb29](https://linux-hardware.org/?probe=1816b1fb29) | Oct 23, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e80544ed81](https://linux-hardware.org/?probe=e80544ed81) | Oct 20, 2020 |
| MSI           | MS-1454                     | Notebook    | [0accbf6c77](https://linux-hardware.org/?probe=0accbf6c77) | Oct 14, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [1d466d105c](https://linux-hardware.org/?probe=1d466d105c) | Oct 12, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [e1c5dde63a](https://linux-hardware.org/?probe=e1c5dde63a) | Oct 12, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [a1665a6de1](https://linux-hardware.org/?probe=a1665a6de1) | Sep 26, 2020 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [3ec057ab8d](https://linux-hardware.org/?probe=3ec057ab8d) | Sep 18, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [d52f9c5bc7](https://linux-hardware.org/?probe=d52f9c5bc7) | Sep 18, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [6963343ed4](https://linux-hardware.org/?probe=6963343ed4) | Sep 17, 2020 |
| ASRock        | Z270M Pro4                  | Desktop     | [ed0a963b78](https://linux-hardware.org/?probe=ed0a963b78) | Sep 05, 2020 |
| Clevo         | P15xEMx                     | Notebook    | [83d0f6aae6](https://linux-hardware.org/?probe=83d0f6aae6) | Aug 28, 2020 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [8634132c3a](https://linux-hardware.org/?probe=8634132c3a) | Aug 24, 2020 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [54032f9ee7](https://linux-hardware.org/?probe=54032f9ee7) | Aug 19, 2020 |
| Lenovo        | ThinkPad Edge 0301FFG       | Notebook    | [60d3a68581](https://linux-hardware.org/?probe=60d3a68581) | Aug 10, 2020 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [c04081db17](https://linux-hardware.org/?probe=c04081db17) | Aug 07, 2020 |
| HP            | Pavilion g6                 | Notebook    | [98d75162cc](https://linux-hardware.org/?probe=98d75162cc) | Aug 06, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [41a4a29b16](https://linux-hardware.org/?probe=41a4a29b16) | Aug 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [9138a15fe4](https://linux-hardware.org/?probe=9138a15fe4) | Aug 01, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [fa825c1fce](https://linux-hardware.org/?probe=fa825c1fce) | Jul 26, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [3098a39bdb](https://linux-hardware.org/?probe=3098a39bdb) | Jul 26, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fe429f7077](https://linux-hardware.org/?probe=fe429f7077) | Jul 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f9c494b96b](https://linux-hardware.org/?probe=f9c494b96b) | Jul 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [1c82bd39f0](https://linux-hardware.org/?probe=1c82bd39f0) | Jul 01, 2020 |
| Microsoft     | Surface Pro 7               | Tablet      | [69744692b0](https://linux-hardware.org/?probe=69744692b0) | Jun 30, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [f6884bd3db](https://linux-hardware.org/?probe=f6884bd3db) | Jun 26, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [1a288de2c5](https://linux-hardware.org/?probe=1a288de2c5) | Jun 24, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [aa1c1587d1](https://linux-hardware.org/?probe=aa1c1587d1) | Jun 23, 2020 |
| Acer          | Aspire ES1-572              | Notebook    | [a166c179ea](https://linux-hardware.org/?probe=a166c179ea) | Jun 22, 2020 |
| ASUSTek       | L4000H                      | Notebook    | [d385784b22](https://linux-hardware.org/?probe=d385784b22) | Jun 22, 2020 |
| Dell          | 0GN6JF A01                  | Desktop     | [452e0f2712](https://linux-hardware.org/?probe=452e0f2712) | Jun 16, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [c5f91bc1ff](https://linux-hardware.org/?probe=c5f91bc1ff) | Jun 16, 2020 |
| Dell          | Inspiron N5030              | Notebook    | [5641d9b86e](https://linux-hardware.org/?probe=5641d9b86e) | Jun 14, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6c1261f611](https://linux-hardware.org/?probe=6c1261f611) | Jun 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [eb4135b12e](https://linux-hardware.org/?probe=eb4135b12e) | Jun 07, 2020 |
| Pegatron      | 2A84h                       | Desktop     | [a5884bfb13](https://linux-hardware.org/?probe=a5884bfb13) | Jun 01, 2020 |
| ASUSTek       | UX390UAK                    | Notebook    | [0857b4df77](https://linux-hardware.org/?probe=0857b4df77) | May 27, 2020 |
| Gigabyte      | H61M-S2P                    | Desktop     | [aecc9b0111](https://linux-hardware.org/?probe=aecc9b0111) | May 25, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [447ac858da](https://linux-hardware.org/?probe=447ac858da) | May 24, 2020 |
| Sony          | SVF153290X                  | Notebook    | [e19f1c716f](https://linux-hardware.org/?probe=e19f1c716f) | May 23, 2020 |
| Gigabyte      | B75M-HD3                    | Desktop     | [bedfc8fa0f](https://linux-hardware.org/?probe=bedfc8fa0f) | May 21, 2020 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [874c2cb817](https://linux-hardware.org/?probe=874c2cb817) | May 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [117bc7af0e](https://linux-hardware.org/?probe=117bc7af0e) | May 17, 2020 |
| ASRock        | 990FX Extreme9              | Desktop     | [1947ac6d52](https://linux-hardware.org/?probe=1947ac6d52) | May 16, 2020 |
| ASRock        | 990FX Extreme9              | Desktop     | [dc7f6cc9e8](https://linux-hardware.org/?probe=dc7f6cc9e8) | May 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0444dd48d1](https://linux-hardware.org/?probe=0444dd48d1) | May 09, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [b401e8b701](https://linux-hardware.org/?probe=b401e8b701) | Apr 30, 2020 |
| HP            | Pavilion dv6                | Notebook    | [8ee1846a65](https://linux-hardware.org/?probe=8ee1846a65) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [bff527c13e](https://linux-hardware.org/?probe=bff527c13e) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [8b02fac19f](https://linux-hardware.org/?probe=8b02fac19f) | Apr 26, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [48acf05b1b](https://linux-hardware.org/?probe=48acf05b1b) | Apr 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [640431a321](https://linux-hardware.org/?probe=640431a321) | Apr 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [095b8a5cdc](https://linux-hardware.org/?probe=095b8a5cdc) | Apr 16, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [874b42a4b7](https://linux-hardware.org/?probe=874b42a4b7) | Apr 16, 2020 |
| HP            | 15                          | Notebook    | [68b0d776a9](https://linux-hardware.org/?probe=68b0d776a9) | Apr 08, 2020 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [784de80b54](https://linux-hardware.org/?probe=784de80b54) | Apr 08, 2020 |
| HP            | Notebook                    | Notebook    | [f22cd145c5](https://linux-hardware.org/?probe=f22cd145c5) | Apr 07, 2020 |
| HP            | 15                          | Notebook    | [27ef1499e3](https://linux-hardware.org/?probe=27ef1499e3) | Apr 06, 2020 |
| HP            | 15                          | Notebook    | [0c2b7adf55](https://linux-hardware.org/?probe=0c2b7adf55) | Apr 06, 2020 |
| HP            | 15                          | Notebook    | [ee5fd88936](https://linux-hardware.org/?probe=ee5fd88936) | Apr 03, 2020 |
| HP            | 15                          | Notebook    | [bfd4fe41b3](https://linux-hardware.org/?probe=bfd4fe41b3) | Apr 03, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [cdce411ba5](https://linux-hardware.org/?probe=cdce411ba5) | Mar 13, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [6e7a1c3bc6](https://linux-hardware.org/?probe=6e7a1c3bc6) | Mar 13, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d3d2a3b89f](https://linux-hardware.org/?probe=d3d2a3b89f) | Mar 05, 2020 |
| ASUSTek       | X555QA                      | Notebook    | [2f0a038eaf](https://linux-hardware.org/?probe=2f0a038eaf) | Feb 11, 2020 |
| ASUSTek       | X555QA                      | Notebook    | [e8062aced5](https://linux-hardware.org/?probe=e8062aced5) | Feb 10, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [5aaf89e123](https://linux-hardware.org/?probe=5aaf89e123) | Feb 03, 2020 |
| Dell          | Vostro 1440                 | Notebook    | [203e61a7c9](https://linux-hardware.org/?probe=203e61a7c9) | Feb 01, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [fbdcd4fb9f](https://linux-hardware.org/?probe=fbdcd4fb9f) | Jan 30, 2020 |
| HP            | Notebook                    | Notebook    | [86dc2687ad](https://linux-hardware.org/?probe=86dc2687ad) | Jan 29, 2020 |
| HP            | Notebook                    | Notebook    | [d3e2e18fa2](https://linux-hardware.org/?probe=d3e2e18fa2) | Jan 29, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9c01b939ce](https://linux-hardware.org/?probe=9c01b939ce) | Jan 27, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [916d1cb7c0](https://linux-hardware.org/?probe=916d1cb7c0) | Jan 27, 2020 |
| Toshiba       | QOSMIO X875                 | Notebook    | [a20b2a7dd7](https://linux-hardware.org/?probe=a20b2a7dd7) | Jan 02, 2020 |
| Toshiba       | QOSMIO X875                 | Notebook    | [953a43ae80](https://linux-hardware.org/?probe=953a43ae80) | Jan 02, 2020 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [bb1c5e0c3a](https://linux-hardware.org/?probe=bb1c5e0c3a) | Jan 01, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [0da4e7552a](https://linux-hardware.org/?probe=0da4e7552a) | Dec 29, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [c137a7866b](https://linux-hardware.org/?probe=c137a7866b) | Dec 14, 2019 |
| Lenovo        | ThinkPad X230 2325OA3       | Notebook    | [ad8913bb6b](https://linux-hardware.org/?probe=ad8913bb6b) | Dec 09, 2019 |
| GPD           | MicroPC                     | Notebook    | [37bfeee080](https://linux-hardware.org/?probe=37bfeee080) | Dec 09, 2019 |
| MSI           | 2A78h                       | Desktop     | [83e806e50e](https://linux-hardware.org/?probe=83e806e50e) | Oct 25, 2019 |
| MSI           | 2A78h                       | Desktop     | [b5679811c8](https://linux-hardware.org/?probe=b5679811c8) | Oct 25, 2019 |
| MSI           | B360M GAMING PLUS           | Desktop     | [f54aa10fcc](https://linux-hardware.org/?probe=f54aa10fcc) | Oct 24, 2019 |
| MSI           | B360M GAMING PLUS           | Desktop     | [96ee6c9f88](https://linux-hardware.org/?probe=96ee6c9f88) | Oct 24, 2019 |
| ASUSTek       | SABERTOOTH Z97 MARK 2/US... | Desktop     | [4976e1673d](https://linux-hardware.org/?probe=4976e1673d) | Oct 01, 2019 |
| ASUSTek       | X555LDB                     | Notebook    | [fffe9c8500](https://linux-hardware.org/?probe=fffe9c8500) | Sep 04, 2019 |
| ASUSTek       | X555LDB                     | Notebook    | [60bc2f13a4](https://linux-hardware.org/?probe=60bc2f13a4) | Sep 04, 2019 |
| Dell          | 0HN7XN A01                  | Desktop     | [b9dd067151](https://linux-hardware.org/?probe=b9dd067151) | Aug 18, 2019 |
| Dell          | 0HN7XN A01                  | Desktop     | [67161826ca](https://linux-hardware.org/?probe=67161826ca) | Aug 18, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [0a1b8c3a29](https://linux-hardware.org/?probe=0a1b8c3a29) | Aug 17, 2019 |
| Acer          | Aspire 4752                 | Notebook    | [4b1cbc26db](https://linux-hardware.org/?probe=4b1cbc26db) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | Notebook    | [5670d72491](https://linux-hardware.org/?probe=5670d72491) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | Notebook    | [81bd1c9f07](https://linux-hardware.org/?probe=81bd1c9f07) | Aug 13, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | Desktop     | [bc9f90fd94](https://linux-hardware.org/?probe=bc9f90fd94) | Jul 20, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | Desktop     | [a5dd292f0e](https://linux-hardware.org/?probe=a5dd292f0e) | Jul 20, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [78b4fe060a](https://linux-hardware.org/?probe=78b4fe060a) | Jul 19, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [b3224eb5fc](https://linux-hardware.org/?probe=b3224eb5fc) | Jul 19, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [f8b4fc087b](https://linux-hardware.org/?probe=f8b4fc087b) | Jul 13, 2019 |
| Sony          | VPCEA36FA                   | Notebook    | [069db5e1d5](https://linux-hardware.org/?probe=069db5e1d5) | Jul 11, 2019 |
| HUAWEI        | MateBook D                  | Notebook    | [0c82ca3724](https://linux-hardware.org/?probe=0c82ca3724) | Jul 06, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [b66944b7d8](https://linux-hardware.org/?probe=b66944b7d8) | Jun 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [630f59eb30](https://linux-hardware.org/?probe=630f59eb30) | Jun 12, 2019 |
| Dell          | Latitude 5285               | Tablet      | [73b87c222f](https://linux-hardware.org/?probe=73b87c222f) | Jun 12, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [3d424bc8d3](https://linux-hardware.org/?probe=3d424bc8d3) | Jun 07, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [8b98fb721c](https://linux-hardware.org/?probe=8b98fb721c) | Jun 07, 2019 |
| Dell          | 0PC5F7 A02                  | Desktop     | [d5c119cb28](https://linux-hardware.org/?probe=d5c119cb28) | Jun 04, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | Desktop     | [9a655727f9](https://linux-hardware.org/?probe=9a655727f9) | Jun 02, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [5bca621b29](https://linux-hardware.org/?probe=5bca621b29) | May 31, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [ced21dc1f3](https://linux-hardware.org/?probe=ced21dc1f3) | May 21, 2019 |
| Dell          | Latitude 5285               | Tablet      | [fcedd9ded7](https://linux-hardware.org/?probe=fcedd9ded7) | Apr 25, 2019 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [14b4f17a8a](https://linux-hardware.org/?probe=14b4f17a8a) | Apr 22, 2019 |
| Sony          | SVF14N13CXB                 | Notebook    | [37e231ce84](https://linux-hardware.org/?probe=37e231ce84) | Apr 07, 2019 |
| Dell          | 0C27VV A03                  | Desktop     | [4a17c281b7](https://linux-hardware.org/?probe=4a17c281b7) | Apr 05, 2019 |
| HP            | 15                          | Notebook    | [e900ad9cfc](https://linux-hardware.org/?probe=e900ad9cfc) | Mar 15, 2019 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [8366ef739b](https://linux-hardware.org/?probe=8366ef739b) | Jan 19, 2019 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [8c5dcea151](https://linux-hardware.org/?probe=8c5dcea151) | Jan 07, 2019 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [f238cfd7d7](https://linux-hardware.org/?probe=f238cfd7d7) | Jan 07, 2019 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [d44c9b123d](https://linux-hardware.org/?probe=d44c9b123d) | Dec 19, 2018 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b0c7903cb1](https://linux-hardware.org/?probe=b0c7903cb1) | Dec 19, 2018 |
| Lenovo        | NOK                         | Desktop     | [2761f888c3](https://linux-hardware.org/?probe=2761f888c3) | Nov 16, 2018 |
| Acer          | Aspire E1-532P              | Notebook    | [26e0937896](https://linux-hardware.org/?probe=26e0937896) | Nov 01, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [3e2fa165a6](https://linux-hardware.org/?probe=3e2fa165a6) | Oct 30, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [a7272b3797](https://linux-hardware.org/?probe=a7272b3797) | Oct 30, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [9c149f8d89](https://linux-hardware.org/?probe=9c149f8d89) | Oct 28, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [5c682ba446](https://linux-hardware.org/?probe=5c682ba446) | Oct 26, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [28a72027c5](https://linux-hardware.org/?probe=28a72027c5) | Oct 25, 2018 |
| Gigabyte      | P35-DS3R                    | Desktop     | [2f8f1a592b](https://linux-hardware.org/?probe=2f8f1a592b) | Aug 14, 2018 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [d9e3df518a](https://linux-hardware.org/?probe=d9e3df518a) | Dec 08, 2017 |
| Dell          | 0VNP2H A00                  | Desktop     | [68fa7ad805](https://linux-hardware.org/?probe=68fa7ad805) | Nov 25, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Saudi_Arabia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 39        | 9.24%   |
| Ubuntu 22.04       | 36        | 8.53%   |
| Ubuntu 18.04       | 18        | 4.27%   |
| OpenMandriva 4.3   | 14        | 3.32%   |
| OpenMandriva 4.2   | 13        | 3.08%   |
| Zorin 16           | 10        | 2.37%   |
| Pop!_OS 22.04      | 9         | 2.13%   |
| Manjaro            | 7         | 1.66%   |
| Pop!_OS 21.10      | 6         | 1.42%   |
| Fedora 39          | 6         | 1.42%   |
| Fedora 35          | 6         | 1.42%   |
| Debian 11          | 6         | 1.42%   |
| Ubuntu 23.04       | 5         | 1.18%   |
| Ubuntu 20.10       | 5         | 1.18%   |
| Ubuntu 19.04       | 5         | 1.18%   |
| Pop!_OS 21.04      | 5         | 1.18%   |
| KDE neon 20.04     | 5         | 1.18%   |
| Fedora 38          | 5         | 1.18%   |
| ArcoLinux Rolling  | 5         | 1.18%   |
| Arch Rolling       | 5         | 1.18%   |
| Arch               | 5         | 1.18%   |
| Ubuntu 21.10       | 4         | 0.95%   |
| Ubuntu 21.04       | 4         | 0.95%   |
| Ubuntu 19.10       | 4         | 0.95%   |
| Nobara 37          | 4         | 0.95%   |
| Kubuntu 22.10      | 4         | 0.95%   |
| Kubuntu 20.04      | 4         | 0.95%   |
| Fedora 36          | 4         | 0.95%   |
| Debian Testing     | 4         | 0.95%   |
| Debian 10          | 4         | 0.95%   |
| Ubuntu 22.10       | 3         | 0.71%   |
| ROSA R10           | 3         | 0.71%   |
| Pop!_OS 20.10      | 3         | 0.71%   |
| Pop!_OS 20.04      | 3         | 0.71%   |
| OpenMandriva 23.08 | 3         | 0.71%   |
| OpenMandriva 23.01 | 3         | 0.71%   |
| Manjaro 20.0.3     | 3         | 0.71%   |
| Linux Mint 21.2    | 3         | 0.71%   |
| Linux Mint 21.1    | 3         | 0.71%   |
| Linux Mint 20.3    | 3         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 117       | 30.15%  |
| OpenMandriva     | 37        | 9.54%   |
| Fedora           | 26        | 6.7%    |
| Pop!_OS          | 19        | 4.9%    |
| Endless          | 18        | 4.64%   |
| Linux Mint       | 17        | 4.38%   |
| Manjaro          | 16        | 4.12%   |
| Debian           | 16        | 4.12%   |
| Zorin            | 14        | 3.61%   |
| Kali             | 11        | 2.84%   |
| Arch             | 10        | 2.58%   |
| Kubuntu          | 9         | 2.32%   |
| KDE neon         | 9         | 2.32%   |
| ROSA             | 8         | 2.06%   |
| SteamOS          | 6         | 1.55%   |
| ArcoLinux        | 6         | 1.55%   |
| Nobara           | 5         | 1.29%   |
| Xubuntu          | 4         | 1.03%   |
| Ubuntu Unity     | 3         | 0.77%   |
| Ubuntu Budgie    | 3         | 0.77%   |
| Elementary       | 3         | 0.77%   |
| Clear Linux      | 3         | 0.77%   |
| ChimeraOS        | 3         | 0.77%   |
| Ubuntu MATE      | 2         | 0.52%   |
| Solus            | 2         | 0.52%   |
| org.kde.Platform | 2         | 0.52%   |
| LMDE             | 2         | 0.52%   |
| EndeavourOS      | 2         | 0.52%   |
| Ubuntu Kylin     | 1         | 0.26%   |
| Rocky Linux      | 1         | 0.26%   |
| RHEL             | 1         | 0.26%   |
| Q4OS             | 1         | 0.26%   |
| PostmarketOS     | 1         | 0.26%   |
| Pear OS          | 1         | 0.26%   |
| Parrot           | 1         | 0.26%   |
| openSUSE         | 1         | 0.26%   |
| Lubuntu          | 1         | 0.26%   |
| Linux Lite       | 1         | 0.26%   |
| Liberty OS       | 1         | 0.26%   |
| Gentoo           | 1         | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 13        | 2.79%   |
| 5.10.14-desktop-1omv4002        | 12        | 2.58%   |
| 5.4.0-42-generic                | 6         | 1.29%   |
| 6.2.0-26-generic                | 5         | 1.07%   |
| 5.19.0-32-generic               | 5         | 1.07%   |
| 6.5.0-26-generic                | 4         | 0.86%   |
| 6.2.0-32-generic                | 4         | 0.86%   |
| 5.4.0-19-generic                | 4         | 0.86%   |
| 5.3.0-28-generic                | 4         | 0.86%   |
| 5.19.0-26-generic               | 4         | 0.86%   |
| 5.15.0-58-generic               | 4         | 0.86%   |
| 5.15.0-48-generic               | 4         | 0.86%   |
| 5.13.0-7614-generic             | 4         | 0.86%   |
| 5.11.0-43-generic               | 4         | 0.86%   |
| 4.15.0-15-generic               | 4         | 0.86%   |
| 6.5.0-14-generic                | 3         | 0.64%   |
| 6.4.11-desktop-1omv2390         | 3         | 0.64%   |
| 6.3.8-200.fc38.x86_64           | 3         | 0.64%   |
| 6.2.0-39-generic                | 3         | 0.64%   |
| 6.2.0-34-generic                | 3         | 0.64%   |
| 6.1.1-desktop-1omv2290          | 3         | 0.64%   |
| 5.8.0-14-generic                | 3         | 0.64%   |
| 5.19.0-50-generic               | 3         | 0.64%   |
| 5.16.19-76051619-generic        | 3         | 0.64%   |
| 5.15.5-76051505-generic         | 3         | 0.64%   |
| 5.15.0-76-generic               | 3         | 0.64%   |
| 5.15.0-56-generic               | 3         | 0.64%   |
| 5.15.0-46-generic               | 3         | 0.64%   |
| 5.13.0-valve36-1-neptune        | 3         | 0.64%   |
| 5.13.0-37-generic               | 3         | 0.64%   |
| 5.11.0-41-generic               | 3         | 0.64%   |
| 5.11.0-40-generic               | 3         | 0.64%   |
| 5.11.0-31-generic               | 3         | 0.64%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3         | 0.64%   |
| 4.18.0-17-generic               | 3         | 0.64%   |
| 4.15.0-29-generic               | 3         | 0.64%   |
| 6.7.9-200.fc39.x86_64           | 2         | 0.43%   |
| 6.6.6-76060606-generic          | 2         | 0.43%   |
| 6.5.6-76060506-generic          | 2         | 0.43%   |
| 6.5.3-arch1-1                   | 2         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 39        | 8.72%   |
| 5.4.0   | 37        | 8.28%   |
| 5.8.0   | 24        | 5.37%   |
| 5.19.0  | 24        | 5.37%   |
| 6.2.0   | 22        | 4.92%   |
| 5.11.0  | 21        | 4.7%    |
| 5.3.0   | 16        | 3.58%   |
| 4.15.0  | 15        | 3.36%   |
| 6.5.0   | 14        | 3.13%   |
| 5.13.0  | 14        | 3.13%   |
| 5.16.7  | 13        | 2.91%   |
| 5.10.14 | 12        | 2.68%   |
| 5.10.0  | 10        | 2.24%   |
| 4.18.0  | 10        | 2.24%   |
| 5.0.0   | 8         | 1.79%   |
| 6.1.0   | 7         | 1.57%   |
| 6.2.6   | 4         | 0.89%   |
| 6.7.9   | 3         | 0.67%   |
| 6.5.3   | 3         | 0.67%   |
| 6.4.11  | 3         | 0.67%   |
| 6.3.8   | 3         | 0.67%   |
| 6.1.1   | 3         | 0.67%   |
| 6.0.0   | 3         | 0.67%   |
| 5.16.19 | 3         | 0.67%   |
| 5.16.11 | 3         | 0.67%   |
| 5.15.5  | 3         | 0.67%   |
| 4.9.60  | 3         | 0.67%   |
| 6.6.9   | 2         | 0.45%   |
| 6.6.6   | 2         | 0.45%   |
| 6.6.10  | 2         | 0.45%   |
| 6.5.6   | 2         | 0.45%   |
| 6.4.7   | 2         | 0.45%   |
| 6.1.8   | 2         | 0.45%   |
| 6.1.52  | 2         | 0.45%   |
| 6.1.11  | 2         | 0.45%   |
| 6.0.8   | 2         | 0.45%   |
| 5.9.11  | 2         | 0.45%   |
| 5.7.9   | 2         | 0.45%   |
| 5.6.15  | 2         | 0.45%   |
| 5.5.0   | 2         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 52        | 11.9%   |
| 5.4     | 39        | 8.92%   |
| 6.2     | 28        | 6.41%   |
| 5.19    | 28        | 6.41%   |
| 5.8     | 27        | 6.18%   |
| 5.10    | 26        | 5.95%   |
| 5.16    | 24        | 5.49%   |
| 5.11    | 24        | 5.49%   |
| 6.5     | 20        | 4.58%   |
| 6.1     | 19        | 4.35%   |
| 5.13    | 17        | 3.89%   |
| 5.3     | 16        | 3.66%   |
| 4.15    | 15        | 3.43%   |
| 4.18    | 11        | 2.52%   |
| 6.6     | 9         | 2.06%   |
| 6.0     | 9         | 2.06%   |
| 6.4     | 8         | 1.83%   |
| 5.0     | 8         | 1.83%   |
| 6.3     | 6         | 1.37%   |
| 5.18    | 6         | 1.37%   |
| 4.9     | 6         | 1.37%   |
| 5.6     | 5         | 1.14%   |
| 5.17    | 5         | 1.14%   |
| 6.7     | 4         | 0.92%   |
| 5.9     | 4         | 0.92%   |
| 5.5     | 4         | 0.92%   |
| 5.14    | 4         | 0.92%   |
| 5.7     | 3         | 0.69%   |
| 6.8     | 2         | 0.46%   |
| 5.12    | 2         | 0.46%   |
| 4.19    | 2         | 0.46%   |
| 4.20    | 1         | 0.23%   |
| 4.13    | 1         | 0.23%   |
| 4.1     | 1         | 0.23%   |
| 3.10    | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 347       | 98.02%  |
| i686   | 6         | 1.69%   |
| armv7l | 1         | 0.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 185       | 48.56%  |
| KDE5       | 78        | 20.47%  |
| Unknown    | 35        | 9.19%   |
| XFCE       | 23        | 6.04%   |
| X-Cinnamon | 17        | 4.46%   |
| KDE        | 9         | 2.36%   |
| Budgie     | 7         | 1.84%   |
| KDE4       | 4         | 1.05%   |
| Cinnamon   | 4         | 1.05%   |
| Unity      | 3         | 0.79%   |
| Pantheon   | 3         | 0.79%   |
| MATE       | 3         | 0.79%   |
| Deepin     | 2         | 0.52%   |
| UKUI       | 1         | 0.26%   |
| trinity    | 1         | 0.26%   |
| openbox    | 1         | 0.26%   |
| LXQt       | 1         | 0.26%   |
| KDE6       | 1         | 0.26%   |
| i3         | 1         | 0.26%   |
| DDE        | 1         | 0.26%   |
| bspwm      | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 254       | 69.02%  |
| Wayland | 84        | 22.83%  |
| Unknown | 24        | 6.52%   |
| Tty     | 6         | 1.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 195       | 51.72%  |
| SDDM    | 58        | 15.38%  |
| GDM3    | 55        | 14.59%  |
| GDM     | 35        | 9.28%   |
| LightDM | 21        | 5.57%   |
| TDM     | 9         | 2.39%   |
| KDM     | 4         | 1.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 261       | 71.12%  |
| Unknown | 33        | 8.99%   |
| ar_SA   | 27        | 7.36%   |
| ar_EG   | 15        | 4.09%   |
| en_GB   | 11        | 3%      |
| C       | 5         | 1.36%   |
| ar_AE   | 3         | 0.82%   |
| en_AG   | 2         | 0.54%   |
| ru_RU   | 1         | 0.27%   |
| nl_BE   | 1         | 0.27%   |
| fr_FR   | 1         | 0.27%   |
| en_IN   | 1         | 0.27%   |
| en_IL   | 1         | 0.27%   |
| en_AU   | 1         | 0.27%   |
| de_DE   | 1         | 0.27%   |
| Default | 1         | 0.27%   |
| cs_CZ   | 1         | 0.27%   |
| ar_KW   | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 201       | 54.18%  |
| EFI  | 170       | 45.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 253       | 68.75%  |
| Btrfs   | 43        | 11.68%  |
| Tmpfs   | 27        | 7.34%   |
| Overlay | 24        | 6.52%   |
| Unknown | 12        | 3.26%   |
| Xfs     | 5         | 1.36%   |
| Ext2    | 3         | 0.82%   |
| Zfs     | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 209       | 55.88%  |
| GPT     | 136       | 36.36%  |
| MBR     | 29        | 7.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 307       | 84.81%  |
| Yes       | 55        | 15.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 254       | 69.02%  |
| Yes       | 114       | 30.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Dell                                 | 67        | 18.93%  |
| ASUSTek Computer                     | 56        | 15.82%  |
| Hewlett-Packard                      | 44        | 12.43%  |
| Lenovo                               | 42        | 11.86%  |
| Gigabyte Technology                  | 24        | 6.78%   |
| MSI                                  | 21        | 5.93%   |
| Acer                                 | 17        | 4.8%    |
| Apple                                | 11        | 3.11%   |
| Toshiba                              | 10        | 2.82%   |
| HUAWEI                               | 9         | 2.54%   |
| ASRock                               | 9         | 2.54%   |
| Sony                                 | 6         | 1.69%   |
| Valve                                | 5         | 1.41%   |
| Unknown                              | 5         | 1.41%   |
| Microsoft                            | 3         | 0.85%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.56%   |
| Samsung Electronics                  | 2         | 0.56%   |
| Pegatron                             | 2         | 0.56%   |
| Notebook                             | 2         | 0.56%   |
| Intel                                | 2         | 0.56%   |
| Packard Bell                         | 1         | 0.28%   |
| OEM                                  | 1         | 0.28%   |
| Medion                               | 1         | 0.28%   |
| LG Electronics                       | 1         | 0.28%   |
| I-Life Digital Technologies          | 1         | 0.28%   |
| Huanan                               | 1         | 0.28%   |
| GPD                                  | 1         | 0.28%   |
| Google                               | 1         | 0.28%   |
| GIADA                                | 1         | 0.28%   |
| Fujitsu Siemens                      | 1         | 0.28%   |
| eMachines                            | 1         | 0.28%   |
| Dynabook                             | 1         | 0.28%   |
| DJI                                  | 1         | 0.28%   |
| Clevo                                | 1         | 0.28%   |
| Biostar                              | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 9         | 2.54%   |
| Valve Jupiter                              | 5         | 1.41%   |
| Dell G3 3590                               | 5         | 1.41%   |
| ASUS All Series                            | 5         | 1.41%   |
| Dell OptiPlex 9020                         | 4         | 1.13%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 4         | 1.13%   |
| HP 15                                      | 3         | 0.85%   |
| MSI MS-7C90                                | 2         | 0.56%   |
| Microsoft Surface Pro 7                    | 2         | 0.56%   |
| Lenovo Legion T5 26IOB6 90RT00TVKS         | 2         | 0.56%   |
| HP Pavilion g6                             | 2         | 0.56%   |
| HP Notebook                                | 2         | 0.56%   |
| HP Laptop 15-da2xxx                        | 2         | 0.56%   |
| HP Laptop 15-da0xxx                        | 2         | 0.56%   |
| HP ENVY x360 Convertible 15-ed1xxx         | 2         | 0.56%   |
| HP Compaq Elite 8300 SFF                   | 2         | 0.56%   |
| Gigabyte H81M-S2PH                         | 2         | 0.56%   |
| Dell OptiPlex 9010                         | 2         | 0.56%   |
| Dell OptiPlex 790                          | 2         | 0.56%   |
| Dell OptiPlex 7050                         | 2         | 0.56%   |
| Dell OptiPlex 7010                         | 2         | 0.56%   |
| Dell OptiPlex 3010                         | 2         | 0.56%   |
| Dell Latitude 5285                         | 2         | 0.56%   |
| Dell Inspiron N5110                        | 2         | 0.56%   |
| Dell Inspiron 3581                         | 2         | 0.56%   |
| Dell Inspiron 3542                         | 2         | 0.56%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 2         | 0.56%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 2         | 0.56%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 2         | 0.56%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 0.56%   |
| Apple MacBookPro9,2                        | 2         | 0.56%   |
| Acer Aspire ES1-572                        | 2         | 0.56%   |
| Acer Aspire 4752                           | 2         | 0.56%   |
| Toshiba Satellite S55t-A                   | 1         | 0.28%   |
| Toshiba Satellite L635                     | 1         | 0.28%   |
| Toshiba Satellite L500                     | 1         | 0.28%   |
| Toshiba Satellite C855D                    | 1         | 0.28%   |
| Toshiba Satellite C850-B820                | 1         | 0.28%   |
| Toshiba Satellite C850-B561                | 1         | 0.28%   |
| Toshiba Satellite C850-B239                | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell OptiPlex      | 21        | 5.93%   |
| Dell Inspiron      | 16        | 4.52%   |
| Lenovo ThinkPad    | 12        | 3.39%   |
| HP Pavilion        | 12        | 3.39%   |
| ASUS VivoBook      | 11        | 3.11%   |
| Acer Aspire        | 11        | 3.11%   |
| Dell Latitude      | 10        | 2.82%   |
| Toshiba Satellite  | 9         | 2.54%   |
| ASUS TUF           | 9         | 2.54%   |
| Unknown            | 9         | 2.54%   |
| HP Laptop          | 8         | 2.26%   |
| Lenovo ThinkCentre | 7         | 1.98%   |
| Lenovo IdeaPad     | 7         | 1.98%   |
| ASUS ROG           | 6         | 1.69%   |
| Valve Jupiter      | 5         | 1.41%   |
| Dell Vostro        | 5         | 1.41%   |
| Dell G3            | 5         | 1.41%   |
| ASUS All           | 5         | 1.41%   |
| HP ENVY            | 4         | 1.13%   |
| Dell XPS           | 4         | 1.13%   |
| ASUS PRIME         | 4         | 1.13%   |
| MSI GF63           | 3         | 0.85%   |
| Microsoft Surface  | 3         | 0.85%   |
| Lenovo Yoga        | 3         | 0.85%   |
| Lenovo Legion      | 3         | 0.85%   |
| HP EliteDesk       | 3         | 0.85%   |
| HP Compaq          | 3         | 0.85%   |
| HP 15              | 3         | 0.85%   |
| MSI MS-7C90        | 2         | 0.56%   |
| HUAWEI MateBook    | 2         | 0.56%   |
| HP ProBook         | 2         | 0.56%   |
| HP Notebook        | 2         | 0.56%   |
| HP EliteBook       | 2         | 0.56%   |
| Gigabyte H81M-S2PH | 2         | 0.56%   |
| Dell Precision     | 2         | 0.56%   |
| Dell PowerEdge     | 2         | 0.56%   |
| ASUS ZenBook       | 2         | 0.56%   |
| ASRock X570        | 2         | 0.56%   |
| Apple MacBookPro9  | 2         | 0.56%   |
| Acer Spin          | 2         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 44        | 12.43%  |
| 2018    | 42        | 11.86%  |
| 2020    | 37        | 10.45%  |
| 2012    | 30        | 8.47%   |
| 2021    | 27        | 7.63%   |
| 2017    | 23        | 6.5%    |
| 2013    | 22        | 6.21%   |
| 2014    | 21        | 5.93%   |
| 2011    | 21        | 5.93%   |
| 2016    | 20        | 5.65%   |
| 2010    | 15        | 4.24%   |
| 2015    | 13        | 3.67%   |
| 2022    | 9         | 2.54%   |
| 2023    | 8         | 2.26%   |
| 2009    | 8         | 2.26%   |
| 2008    | 6         | 1.69%   |
| 2007    | 5         | 1.41%   |
| 2006    | 1         | 0.28%   |
| 2002    | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 188       | 53.11%  |
| Desktop     | 130       | 36.72%  |
| Convertible | 17        | 4.8%    |
| Tablet      | 10        | 2.82%   |
| Mini pc     | 4         | 1.13%   |
| All in one  | 3         | 0.85%   |
| Server      | 2         | 0.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 330       | 92.44%  |
| Enabled  | 27        | 7.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 353       | 99.72%  |
| Yes  | 1         | 0.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 89        | 24.52%  |
| 16.01-24.0  | 77        | 21.21%  |
| 3.01-4.0    | 60        | 16.53%  |
| 8.01-16.0   | 59        | 16.25%  |
| 32.01-64.0  | 37        | 10.19%  |
| 1.01-2.0    | 18        | 4.96%   |
| 24.01-32.0  | 8         | 2.2%    |
| 64.01-256.0 | 8         | 2.2%    |
| 2.01-3.0    | 6         | 1.65%   |
| 0.51-1.0    | 1         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 131       | 32.27%  |
| 2.01-3.0   | 103       | 25.37%  |
| 4.01-8.0   | 66        | 16.26%  |
| 3.01-4.0   | 66        | 16.26%  |
| 0.51-1.0   | 20        | 4.93%   |
| 8.01-16.0  | 15        | 3.69%   |
| 16.01-24.0 | 3         | 0.74%   |
| 0.01-0.5   | 1         | 0.25%   |
| Unknown    | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 218       | 58.13%  |
| 2      | 96        | 25.6%   |
| 3      | 36        | 9.6%    |
| 4      | 13        | 3.47%   |
| 6      | 5         | 1.33%   |
| 5      | 5         | 1.33%   |
| 7      | 1         | 0.27%   |
| 0      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 232       | 64.62%  |
| Yes       | 127       | 35.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 290       | 81.01%  |
| No        | 68        | 18.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 301       | 84.79%  |
| No        | 54        | 15.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 251       | 70.11%  |
| No        | 107       | 29.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Saudi Arabia | 354       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Riyadh               | 133       | 34.55%  |
| Jeddah               | 94        | 24.42%  |
| Makkah               | 40        | 10.39%  |
| Dammam               | 32        | 8.31%   |
| Medina               | 26        | 6.75%   |
| Khobar               | 11        | 2.86%   |
| Al Qatif             | 10        | 2.6%    |
| Dhahran              | 7         | 1.82%   |
| Ta'if                | 6         | 1.56%   |
| Baq`a' ash Sharqiyah | 6         | 1.56%   |
| Thuwal               | 3         | 0.78%   |
| Jubail               | 3         | 0.78%   |
| Buraidah             | 2         | 0.52%   |
| Al Faruq             | 2         | 0.52%   |
| Abha                 | 2         | 0.52%   |
| Yanbu                | 1         | 0.26%   |
| Shaqra               | 1         | 0.26%   |
| Sayhat               | 1         | 0.26%   |
| Bisha                | 1         | 0.26%   |
| At Tuwal             | 1         | 0.26%   |
| Al Majāridah        | 1         | 0.26%   |
| Al Kharj             | 1         | 0.26%   |
| Al Hufuf             | 1         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 99        | 157    | 18.27%  |
| Seagate                     | 75        | 110    | 13.84%  |
| Kingston                    | 60        | 97     | 11.07%  |
| Samsung Electronics         | 56        | 92     | 10.33%  |
| Toshiba                     | 49        | 63     | 9.04%   |
| Sandisk                     | 34        | 37     | 6.27%   |
| Unknown                     | 20        | 37     | 3.69%   |
| Crucial                     | 12        | 15     | 2.21%   |
| SK hynix                    | 11        | 26     | 2.03%   |
| Intel                       | 11        | 20     | 2.03%   |
| Hitachi                     | 9         | 10     | 1.66%   |
| Phison Electronics          | 8         | 11     | 1.48%   |
| Lexar                       | 7         | 7      | 1.29%   |
| Team                        | 6         | 6      | 1.11%   |
| Micron/Crucial Technology   | 6         | 6      | 1.11%   |
| Silicon Motion              | 5         | 6      | 0.92%   |
| Phison                      | 5         | 6      | 0.92%   |
| China                       | 5         | 5      | 0.92%   |
| Apple                       | 5         | 7      | 0.92%   |
| Kingston Technology Company | 4         | 5      | 0.74%   |
| JMicron Technology          | 4         | 4      | 0.74%   |
| Hewlett-Packard             | 4         | 5      | 0.74%   |
| PNY                         | 3         | 4      | 0.55%   |
| MAXIO Technology (Hangzhou) | 3         | 4      | 0.55%   |
| KingSpec                    | 3         | 3      | 0.55%   |
| HGST                        | 3         | 6      | 0.55%   |
| SPCC                        | 2         | 3      | 0.37%   |
| Micron Technology           | 2         | 2      | 0.37%   |
| LITEON                      | 2         | 2      | 0.37%   |
| KIOXIA                      | 2         | 2      | 0.37%   |
| HS-SSD-C100                 | 2         | 3      | 0.37%   |
| Fujitsu                     | 2         | 3      | 0.37%   |
| Unknown                     | 2         | 2      | 0.37%   |
| YS                          | 1         | 2      | 0.18%   |
| YMTC                        | 1         | 1      | 0.18%   |
| XrayDisk                    | 1         | 1      | 0.18%   |
| WD MediaMax                 | 1         | 1      | 0.18%   |
| Union Memory                | 1         | 1      | 0.18%   |
| UMIS                        | 1         | 1      | 0.18%   |
| Transcend                   | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 21        | 3.49%   |
| Toshiba MQ04ABF100 1TB                             | 14        | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB                     | 14        | 2.33%   |
| Kingston SA400S37480G 480GB SSD                    | 13        | 2.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 8         | 1.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 7         | 1.16%   |
| Seagate ST500DM002-1BD142 500GB                    | 7         | 1.16%   |
| Toshiba MQ01ABD100 1TB                             | 6         | 1%      |
| Kingston SA400S37120G 120GB SSD                    | 6         | 1%      |
| Samsung SSD 860 EVO 1TB                            | 5         | 0.83%   |
| Samsung NVMe SSD Drive 1024GB                      | 5         | 0.83%   |
| Phison PS5013 E13 NVMe Controller 512GB            | 5         | 0.83%   |
| WDC WD5000AAKX-75U6AA0 500GB                       | 4         | 0.66%   |
| WDC WD10EZEX-75WN4A1 1TB                           | 4         | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 4         | 0.66%   |
| Toshiba MQ01ABF050 500GB                           | 4         | 0.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4         | 0.66%   |
| Lexar 128GB SSD                                    | 4         | 0.66%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 3         | 0.5%    |
| Unknown MMC Card  32GB                             | 3         | 0.5%    |
| Toshiba DT01ACA050 500GB                           | 3         | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                    | 3         | 0.5%    |
| Seagate ST2000LM007-1R8174 2TB                     | 3         | 0.5%    |
| SanDisk NVMe SSD Drive 512GB                       | 3         | 0.5%    |
| SanDisk NVMe SSD Drive 128GB                       | 3         | 0.5%    |
| Samsung SSD 860 EVO 500GB                          | 3         | 0.5%    |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                | 3         | 0.5%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB | 3         | 0.5%    |
| Kingston SH103S3120G 120GB SSD                     | 3         | 0.5%    |
| Kingston SA400S37960G 960GB SSD                    | 3         | 0.5%    |
| JMicron Tech 250GB                                 | 3         | 0.5%    |
| Intel SSD 660P Series 1024GB                       | 3         | 0.5%    |
| Intel NVMe SSD Drive 1024GB                        | 3         | 0.5%    |
| Crucial CT500MX500SSD1 500GB                       | 3         | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                        | 3         | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 2         | 0.33%   |
| WDC WD5000LPCX-00VHAT0 500GB                       | 2         | 0.33%   |
| WDC WD4005FZBX-00K5WB0 4TB                         | 2         | 0.33%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 2         | 0.33%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 82        | 134    | 36.61%  |
| Seagate             | 75        | 110    | 33.48%  |
| Toshiba             | 46        | 53     | 20.54%  |
| Hitachi             | 9         | 10     | 4.02%   |
| HGST                | 3         | 6      | 1.34%   |
| Fujitsu             | 2         | 3      | 0.89%   |
| Apple               | 2         | 2      | 0.89%   |
| Unknown             | 1         | 3      | 0.45%   |
| Samsung Electronics | 1         | 2      | 0.45%   |
| Maxtor              | 1         | 1      | 0.45%   |
| KESU                | 1         | 1      | 0.45%   |
| JMicron Technology  | 1         | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 52        | 85     | 32.7%   |
| Samsung Electronics | 22        | 38     | 13.84%  |
| SanDisk             | 19        | 20     | 11.95%  |
| Crucial             | 12        | 14     | 7.55%   |
| WDC                 | 10        | 13     | 6.29%   |
| Lexar               | 6         | 6      | 3.77%   |
| China               | 5         | 5      | 3.14%   |
| Team                | 4         | 4      | 2.52%   |
| PNY                 | 3         | 4      | 1.89%   |
| KingSpec            | 3         | 3      | 1.89%   |
| Hewlett-Packard     | 3         | 4      | 1.89%   |
| SK hynix            | 2         | 3      | 1.26%   |
| LITEON              | 2         | 2      | 1.26%   |
| Apple               | 2         | 2      | 1.26%   |
| Unknown             | 2         | 2      | 1.26%   |
| YS                  | 1         | 2      | 0.63%   |
| XrayDisk            | 1         | 1      | 0.63%   |
| Transcend           | 1         | 1      | 0.63%   |
| SPCC Sol            | 1         | 1      | 0.63%   |
| SPCC                | 1         | 2      | 0.63%   |
| OYUNKEY             | 1         | 1      | 0.63%   |
| Intel               | 1         | 4      | 0.63%   |
| Hoodisk             | 1         | 1      | 0.63%   |
| G-DRIVE             | 1         | 1      | 0.63%   |
| Corsair             | 1         | 1      | 0.63%   |
| ASMT                | 1         | 1      | 0.63%   |
| A-DATA Technology   | 1         | 1      | 0.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 191       | 326    | 39.71%  |
| SSD     | 140       | 222    | 29.11%  |
| NVMe    | 124       | 197    | 25.78%  |
| MMC     | 19        | 35     | 3.95%   |
| Unknown | 7         | 8      | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 268       | 537    | 63.36%  |
| NVMe | 124       | 196    | 29.31%  |
| MMC  | 19        | 35     | 4.49%   |
| SAS  | 12        | 20     | 2.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 161       | 282    | 47.49%  |
| 0.51-1.0   | 135       | 205    | 39.82%  |
| 1.01-2.0   | 27        | 38     | 7.96%   |
| 3.01-4.0   | 11        | 14     | 3.24%   |
| 2.01-3.0   | 4         | 5      | 1.18%   |
| 4.01-10.0  | 1         | 4      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 90        | 23.14%  |
| 501-1000       | 85        | 21.85%  |
| 251-500        | 84        | 21.59%  |
| 51-100         | 29        | 7.46%   |
| 1001-2000      | 26        | 6.68%   |
| 1-20           | 23        | 5.91%   |
| More than 3000 | 16        | 4.11%   |
| 21-50          | 16        | 4.11%   |
| 2001-3000      | 14        | 3.6%    |
| Unknown        | 6         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 155       | 37.17%  |
| 21-50          | 88        | 21.1%   |
| 51-100         | 49        | 11.75%  |
| 101-250        | 47        | 11.27%  |
| 251-500        | 32        | 7.67%   |
| 501-1000       | 18        | 4.32%   |
| 1001-2000      | 11        | 2.64%   |
| Unknown        | 6         | 1.44%   |
| More than 3000 | 5         | 1.2%    |
| 2001-3000      | 5         | 1.2%    |
| 0              | 1         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Unknown                            | 2         | 2      | 7.41%   |
| YS SSD 240GB                       | 1         | 1      | 3.7%    |
| WDC WD5000AAKS-00WWPA0 500GB       | 1         | 1      | 3.7%    |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 3.7%    |
| WDC WD3200AAJS-00L7A0 320GB        | 1         | 1      | 3.7%    |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1         | 1      | 3.7%    |
| WDC WD1600AAJS-60B4A0 160GB        | 1         | 1      | 3.7%    |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 1      | 3.7%    |
| WDC WD10SPZX-08Z10 1TB             | 1         | 1      | 3.7%    |
| WDC WD10PURZ-85U8XY0 1TB           | 1         | 1      | 3.7%    |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 3.7%    |
| WDC WD10EUCX-73YZ1Y0 1TB           | 1         | 1      | 3.7%    |
| WDC WD Green 2.5 480GB SSD         | 1         | 1      | 3.7%    |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 3.7%    |
| Seagate ST9320325AS 320GB          | 1         | 1      | 3.7%    |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB    | 1         | 1      | 3.7%    |
| Seagate ST2000DM001-1CH164 2TB     | 1         | 1      | 3.7%    |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 3.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 3.7%    |
| Seagate ST1000DM003-9YN162 1TB     | 1         | 1      | 3.7%    |
| SanDisk SSD PLUS 480GB             | 1         | 1      | 3.7%    |
| OYUNKEY SSD 120GB                  | 1         | 1      | 3.7%    |
| Kingston SMS200S3240G 240GB SSD    | 1         | 1      | 3.7%    |
| Kingston SA400S37480G 480GB SSD    | 1         | 1      | 3.7%    |
| Hitachi HDS721032CLA362 320GB      | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 11        | 11     | 42.31%  |
| Seagate  | 6         | 7      | 23.08%  |
| Kingston | 2         | 2      | 7.69%   |
| Unknown  | 2         | 2      | 7.69%   |
| YS       | 1         | 1      | 3.85%   |
| Toshiba  | 1         | 1      | 3.85%   |
| SanDisk  | 1         | 1      | 3.85%   |
| OYUNKEY  | 1         | 1      | 3.85%   |
| Hitachi  | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 10     | 55.56%  |
| Seagate | 6         | 7      | 33.33%  |
| Toshiba | 1         | 1      | 5.56%   |
| Hitachi | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 19     | 72.73%  |
| SSD  | 6         | 8      | 27.27%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 249       | 539    | 64.01%  |
| Works    | 119       | 222    | 30.59%  |
| Malfunc  | 21        | 27     | 5.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 269       | 59.91%  |
| AMD                              | 38        | 8.46%   |
| Samsung Electronics              | 36        | 8.02%   |
| SanDisk                          | 20        | 4.45%   |
| Kingston Technology Company      | 13        | 2.9%    |
| Phison Electronics               | 12        | 2.67%   |
| SK hynix                         | 9         | 2%      |
| Silicon Motion                   | 7         | 1.56%   |
| Micron/Crucial Technology        | 7         | 1.56%   |
| ASMedia Technology               | 7         | 1.56%   |
| Toshiba America Info Systems     | 4         | 0.89%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.67%   |
| KIOXIA                           | 3         | 0.67%   |
| Union Memory (Shenzhen)          | 2         | 0.45%   |
| Realtek Semiconductor            | 2         | 0.45%   |
| Nvidia                           | 2         | 0.45%   |
| Micron Technology                | 2         | 0.45%   |
| Broadcom / LSI                   | 2         | 0.45%   |
| Yangtze Memory Technologies      | 1         | 0.22%   |
| VIA Technologies                 | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Marvell Technology Group         | 1         | 0.22%   |
| LSI Logic / Symbios Logic        | 1         | 0.22%   |
| Lite-On Technology               | 1         | 0.22%   |
| JMicron Technology               | 1         | 0.22%   |
| INNOGRIT                         | 1         | 0.22%   |
| Hosin Global Electronics         | 1         | 0.22%   |
| Apple                            | 1         | 0.22%   |
| ADATA Technology                 | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 27        | 5.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 24        | 4.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 3.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 3.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 14        | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 2.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 14        | 2.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 2.46%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 12        | 2.46%   |
| Intel SATA Controller [RAID mode]                                              | 12        | 2.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 2.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 1.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 1.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8         | 1.64%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 1.43%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 7         | 1.43%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 6         | 1.23%   |
| Intel SSD 660P Series                                                          | 6         | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 1.23%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 1.23%   |
| AMD 500 Series Chipset SATA Controller                                         | 6         | 1.23%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 1.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.02%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4         | 0.82%   |
| Phison E12 NVMe Controller                                                     | 4         | 0.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 0.82%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 4         | 0.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 0.82%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 4         | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 4         | 0.82%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.61%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 3         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 251       | 56.79%  |
| NVMe | 124       | 28.05%  |
| RAID | 39        | 8.82%   |
| IDE  | 27        | 6.11%   |
| SAS  | 1         | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 300       | 84.75%  |
| AMD    | 53        | 14.97%  |
| ARM    | 1         | 0.28%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 2.25%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 1.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 1.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.4%    |
| AMD Custom APU 0405                           | 5         | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.12%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 4         | 1.12%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 1.12%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.12%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 1.12%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.12%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 1.12%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.12%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.84%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.84%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 3         | 0.84%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.84%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.84%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 3         | 0.84%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.84%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.84%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.84%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 0.84%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 3         | 0.84%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 0.84%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 3         | 0.84%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 0.84%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.84%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2         | 0.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.56%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.56%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 96        | 26.97%  |
| Intel Core i5           | 88        | 24.72%  |
| Intel Core i3           | 31        | 8.71%   |
| Other                   | 28        | 7.87%   |
| AMD Ryzen 5             | 20        | 5.62%   |
| Intel Celeron           | 18        | 5.06%   |
| Intel Core 2 Duo        | 13        | 3.65%   |
| AMD Ryzen 7             | 12        | 3.37%   |
| AMD Ryzen 9             | 10        | 2.81%   |
| Intel Xeon              | 6         | 1.69%   |
| Intel Pentium Dual-Core | 5         | 1.4%    |
| Intel Atom              | 5         | 1.4%    |
| Intel Core i9           | 4         | 1.12%   |
| Intel Pentium           | 3         | 0.84%   |
| AMD FX                  | 3         | 0.84%   |
| Intel Xeon Silver       | 1         | 0.28%   |
| Intel Pentium Silver    | 1         | 0.28%   |
| Intel Pentium 4         | 1         | 0.28%   |
| Intel Mobile Pentium 4  | 1         | 0.28%   |
| Intel Genuine           | 1         | 0.28%   |
| Intel Core m5           | 1         | 0.28%   |
| Intel Core m3           | 1         | 0.28%   |
| Intel Core 2 Quad       | 1         | 0.28%   |
| Intel Core 2            | 1         | 0.28%   |
| ARM ARMv7               | 1         | 0.28%   |
| AMD Ryzen 5 PRO         | 1         | 0.28%   |
| AMD E2                  | 1         | 0.28%   |
| AMD A4                  | 1         | 0.28%   |
| AMD A12                 | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 136       | 38.31%  |
| 2      | 130       | 36.62%  |
| 6      | 40        | 11.27%  |
| 8      | 25        | 7.04%   |
| 1      | 8         | 2.25%   |
| 12     | 4         | 1.13%   |
| 16     | 3         | 0.85%   |
| 14     | 3         | 0.85%   |
| 10     | 3         | 0.85%   |
| 24     | 2         | 0.56%   |
| 20     | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 352       | 99.44%  |
| 2      | 2         | 0.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 259       | 72.75%  |
| 1      | 96        | 26.97%  |
| 8      | 1         | 0.28%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 346       | 97.46%  |
| Unknown        | 7         | 1.97%   |
| 32-bit         | 2         | 0.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 151       | 39.53%  |
| 0x306a9    | 22        | 5.76%   |
| 0x206a7    | 18        | 4.71%   |
| 0x1067a    | 15        | 3.93%   |
| 0x306c3    | 14        | 3.66%   |
| 0x40651    | 11        | 2.88%   |
| 0x906e9    | 9         | 2.36%   |
| 0x806c1    | 9         | 2.36%   |
| 0x906ea    | 8         | 2.09%   |
| 0x806e9    | 8         | 2.09%   |
| 0x406e3    | 8         | 2.09%   |
| 0x806ec    | 7         | 1.83%   |
| 0x806ea    | 7         | 1.83%   |
| 0x706e5    | 6         | 1.57%   |
| 0x706a1    | 5         | 1.31%   |
| 0xa0652    | 4         | 1.05%   |
| 0x306d4    | 4         | 1.05%   |
| 0x20655    | 4         | 1.05%   |
| 0x08108109 | 4         | 1.05%   |
| 0xa0653    | 3         | 0.79%   |
| 0x906ed    | 3         | 0.79%   |
| 0x506c9    | 3         | 0.79%   |
| 0x30673    | 3         | 0.79%   |
| 0x20652    | 3         | 0.79%   |
| 0xa0655    | 2         | 0.52%   |
| 0x906a3    | 2         | 0.52%   |
| 0x806eb    | 2         | 0.52%   |
| 0x406c4    | 2         | 0.52%   |
| 0x106e5    | 2         | 0.52%   |
| 0x0a201016 | 2         | 0.52%   |
| 0x08701021 | 2         | 0.52%   |
| 0x08701013 | 2         | 0.52%   |
| 0x08600106 | 2         | 0.52%   |
| 0x0810100b | 2         | 0.52%   |
| 0x0800820d | 2         | 0.52%   |
| 0x06000852 | 2         | 0.52%   |
| 0xf64      | 1         | 0.26%   |
| 0xf27      | 1         | 0.26%   |
| 0xb0671    | 1         | 0.26%   |
| 0x906ec    | 1         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 77        | 21.57%  |
| Haswell          | 38        | 10.64%  |
| IvyBridge        | 31        | 8.68%   |
| SandyBridge      | 26        | 7.28%   |
| Skylake          | 20        | 5.6%    |
| Unknown          | 18        | 5.04%   |
| Penryn           | 17        | 4.76%   |
| Zen 3            | 15        | 4.2%    |
| CometLake        | 13        | 3.64%   |
| Zen+             | 12        | 3.36%   |
| TigerLake        | 12        | 3.36%   |
| Zen 2            | 10        | 2.8%    |
| IceLake          | 10        | 2.8%    |
| Goldmont plus    | 9         | 2.52%   |
| Westmere         | 8         | 2.24%   |
| Silvermont       | 6         | 1.68%   |
| Broadwell        | 6         | 1.68%   |
| Core             | 5         | 1.4%    |
| Piledriver       | 4         | 1.12%   |
| Nehalem          | 4         | 1.12%   |
| Goldmont         | 4         | 1.12%   |
| Alderlake Hybrid | 4         | 1.12%   |
| Zen              | 2         | 0.56%   |
| NetBurst         | 2         | 0.56%   |
| Tremont          | 1         | 0.28%   |
| Excavator        | 1         | 0.28%   |
| Bonnell          | 1         | 0.28%   |
| Bobcat           | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 235       | 52.81%  |
| Nvidia                           | 128       | 28.76%  |
| AMD                              | 77        | 17.3%   |
| Matrox Electronics Systems       | 2         | 0.45%   |
| VIA Technologies                 | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| ATI Technologies                 | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 22        | 4.88%   |
| Intel HD Graphics 620                                                         | 16        | 3.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 16        | 3.55%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 14        | 3.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 12        | 2.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 10        | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 2.22%   |
| Intel UHD Graphics 620                                                        | 9         | 2%      |
| Intel GeminiLake [UHD Graphics 600]                                           | 9         | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 9         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 8         | 1.77%   |
| Intel HD Graphics 630                                                         | 8         | 1.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 8         | 1.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 1.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 7         | 1.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 6         | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 6         | 1.33%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 1.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 6         | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 5         | 1.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 5         | 1.11%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 5         | 1.11%   |
| AMD VanGogh [AMD Custom GPU 0405]                                             | 5         | 1.11%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 5         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 4         | 0.89%   |
| Nvidia GK208B [GeForce GT 730]                                                | 4         | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 4         | 0.89%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                | 4         | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 4         | 0.89%   |
| Intel HD Graphics 5500                                                        | 4         | 0.89%   |
| Intel HD Graphics 530                                                         | 4         | 0.89%   |
| Intel HD Graphics 500                                                         | 4         | 0.89%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 4         | 0.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 4         | 0.89%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 4         | 0.89%   |
| Nvidia TU117M [GeForce MX450]                                                 | 3         | 0.67%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                         | 3         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 3         | 0.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 3         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 154       | 42.9%   |
| 1 x Nvidia     | 60        | 16.71%  |
| Intel + Nvidia | 59        | 16.43%  |
| 1 x AMD        | 52        | 14.48%  |
| Intel + AMD    | 18        | 5.01%   |
| AMD + Nvidia   | 9         | 2.51%   |
| 1 x Matrox     | 2         | 0.56%   |
| Other          | 1         | 0.28%   |
| 2 x Intel      | 1         | 0.28%   |
| 2 x AMD        | 1         | 0.28%   |
| 1 x VIA        | 1         | 0.28%   |
| 1 x SiS        | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 285       | 78.08%  |
| Proprietary | 73        | 20%     |
| Unknown     | 7         | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 232       | 63.56%  |
| 1.01-2.0   | 42        | 11.51%  |
| 3.01-4.0   | 28        | 7.67%   |
| 7.01-8.0   | 20        | 5.48%   |
| 0.51-1.0   | 17        | 4.66%   |
| 0.01-0.5   | 14        | 3.84%   |
| 8.01-16.0  | 6         | 1.64%   |
| 2.01-3.0   | 5         | 1.37%   |
| 5.01-6.0   | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 57        | 15.12%  |
| Samsung Electronics     | 40        | 10.61%  |
| Chimei Innolux          | 34        | 9.02%   |
| LG Display              | 33        | 8.75%   |
| Dell                    | 30        | 7.96%   |
| AU Optronics            | 29        | 7.69%   |
| BenQ                    | 18        | 4.77%   |
| Lenovo                  | 13        | 3.45%   |
| Goldstar                | 13        | 3.45%   |
| Hewlett-Packard         | 10        | 2.65%   |
| Apple                   | 10        | 2.65%   |
| Sharp                   | 9         | 2.39%   |
| Unknown                 | 7         | 1.86%   |
| Valve                   | 5         | 1.33%   |
| Sony                    | 5         | 1.33%   |
| PANDA                   | 5         | 1.33%   |
| Acer                    | 5         | 1.33%   |
| InfoVision              | 4         | 1.06%   |
| Chi Mei Optoelectronics | 4         | 1.06%   |
| AOC                     | 3         | 0.8%    |
| Ancor Communications    | 3         | 0.8%    |
| ViewSonic               | 2         | 0.53%   |
| Unknown (XXX)           | 2         | 0.53%   |
| TCL                     | 2         | 0.53%   |
| SKY                     | 2         | 0.53%   |
| Gigabyte Technology     | 2         | 0.53%   |
| ASUSTek Computer        | 2         | 0.53%   |
| ___                     | 1         | 0.27%   |
| WIT                     | 1         | 0.27%   |
| UGD                     | 1         | 0.27%   |
| Toshiba                 | 1         | 0.27%   |
| Tech Concepts           | 1         | 0.27%   |
| Sun                     | 1         | 0.27%   |
| SHC                     | 1         | 0.27%   |
| RTK                     | 1         | 0.27%   |
| RGT                     | 1         | 0.27%   |
| Pioneer                 | 1         | 0.27%   |
| Philips                 | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| MStar                   | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 5         | 1.28%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 1.03%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 1.03%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                       | 4         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.77%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch    | 3         | 0.77%   |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch                 | 3         | 0.77%   |
| Lenovo LEN G34w-10 LEN66A1 3440x1440 797x334mm 34.0-inch                 | 3         | 0.77%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 3         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.77%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 3         | 0.77%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                    | 3         | 0.77%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.77%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                        | 3         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.77%   |
| Unknown SMART TV 6488 3840x2160 1209x680mm 54.6-inch                     | 2         | 0.51%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                      | 2         | 0.51%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch         | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch    | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 1210x680mm 54.6-inch   | 2         | 0.51%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 2         | 0.51%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 2         | 0.51%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.51%   |
| Dell U2413 DELF047 1920x1200 518x324mm 24.1-inch                         | 2         | 0.51%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                    | 2         | 0.51%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                        | 2         | 0.51%   |
| Dell P2312H DEL4076 1920x1080 510x287mm 23.0-inch                        | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch         | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1517 1920x1080 344x193mm 15.5-inch         | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.51%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 2         | 0.51%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 2         | 0.51%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 2         | 0.51%   |
| BOE LCD Monitor BOE06DC 1920x1280 259x173mm 12.3-inch                    | 2         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 158       | 43.29%  |
| 1366x768 (WXGA)    | 95        | 26.03%  |
| 3840x2160 (4K)     | 36        | 9.86%   |
| 2560x1440 (QHD)    | 14        | 3.84%   |
| 1280x800 (WXGA)    | 6         | 1.64%   |
| 800x1280           | 5         | 1.37%   |
| 3440x1440          | 5         | 1.37%   |
| 1920x1200 (WUXGA)  | 5         | 1.37%   |
| 2560x1080          | 4         | 1.1%    |
| 2160x1440          | 4         | 1.1%    |
| 1600x900 (HD+)     | 4         | 1.1%    |
| 1440x900 (WXGA+)   | 4         | 1.1%    |
| 2736x1824          | 3         | 0.82%   |
| 1680x1050 (WSXGA+) | 3         | 0.82%   |
| 1280x1024 (SXGA)   | 3         | 0.82%   |
| 3840x1080          | 2         | 0.55%   |
| 2880x1800          | 2         | 0.55%   |
| 2560x1600          | 2         | 0.55%   |
| 1920x1280          | 2         | 0.55%   |
| 1360x768           | 2         | 0.55%   |
| Unknown            | 2         | 0.55%   |
| 7040x1440          | 1         | 0.27%   |
| 3840x2400          | 1         | 0.27%   |
| 3840x1600          | 1         | 0.27%   |
| 2256x1504          | 1         | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 115       | 30.1%   |
| 13      | 39        | 10.21%  |
| 14      | 27        | 7.07%   |
| 24      | 25        | 6.54%   |
| 27      | 24        | 6.28%   |
| 23      | 17        | 4.45%   |
| Unknown | 14        | 3.66%   |
| 31      | 12        | 3.14%   |
| 21      | 12        | 3.14%   |
| 12      | 12        | 3.14%   |
| 54      | 11        | 2.88%   |
| 18      | 11        | 2.88%   |
| 34      | 8         | 2.09%   |
| 17      | 7         | 1.83%   |
| 84      | 6         | 1.57%   |
| 7       | 5         | 1.31%   |
| 72      | 4         | 1.05%   |
| 32      | 4         | 1.05%   |
| 19      | 4         | 1.05%   |
| 52      | 3         | 0.79%   |
| 22      | 3         | 0.79%   |
| 16      | 3         | 0.79%   |
| 11      | 3         | 0.79%   |
| 48      | 2         | 0.52%   |
| 40      | 2         | 0.52%   |
| 86      | 1         | 0.26%   |
| 65      | 1         | 0.26%   |
| 63      | 1         | 0.26%   |
| 57      | 1         | 0.26%   |
| 46      | 1         | 0.26%   |
| 37      | 1         | 0.26%   |
| 29      | 1         | 0.26%   |
| 25      | 1         | 0.26%   |
| 20      | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 163       | 43.35%  |
| 501-600     | 60        | 15.96%  |
| 201-300     | 34        | 9.04%   |
| 401-500     | 31        | 8.24%   |
| 1001-1500   | 21        | 5.59%   |
| 601-700     | 15        | 3.99%   |
| Unknown     | 14        | 3.72%   |
| 701-800     | 12        | 3.19%   |
| 1501-2000   | 10        | 2.66%   |
| 351-400     | 8         | 2.13%   |
| 1-100       | 5         | 1.33%   |
| 801-900     | 3         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 283       | 80.86%  |
| 16/10   | 23        | 6.57%   |
| Unknown | 13        | 3.71%   |
| 3/2     | 10        | 2.86%   |
| 21/9    | 10        | 2.86%   |
| 0.67    | 5         | 1.43%   |
| 5/4     | 3         | 0.86%   |
| 4/3     | 1         | 0.29%   |
| 32/9    | 1         | 0.29%   |
| 0.56    | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 115       | 30.34%  |
| 81-90          | 55        | 14.51%  |
| 201-250        | 45        | 11.87%  |
| More than 1000 | 29        | 7.65%   |
| 301-350        | 25        | 6.6%    |
| 351-500        | 24        | 6.33%   |
| 141-150        | 14        | 3.69%   |
| Unknown        | 14        | 3.69%   |
| 71-80          | 12        | 3.17%   |
| 61-70          | 10        | 2.64%   |
| 251-300        | 8         | 2.11%   |
| 151-200        | 8         | 2.11%   |
| 1-40           | 5         | 1.32%   |
| 501-1000       | 5         | 1.32%   |
| 121-130        | 4         | 1.06%   |
| 51-60          | 3         | 0.79%   |
| 111-120        | 2         | 0.53%   |
| 91-100         | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 111       | 30%     |
| 101-120       | 101       | 27.3%   |
| 121-160       | 95        | 25.68%  |
| 161-240       | 26        | 7.03%   |
| 1-50          | 17        | 4.59%   |
| Unknown       | 14        | 3.78%   |
| More than 240 | 6         | 1.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 306       | 83.84%  |
| 2     | 43        | 11.78%  |
| 0     | 9         | 2.47%   |
| 3     | 6         | 1.64%   |
| 4     | 1         | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 200       | 35.91%  |
| Intel                            | 167       | 29.98%  |
| Qualcomm Atheros                 | 64        | 11.49%  |
| Broadcom                         | 36        | 6.46%   |
| Ralink Technology                | 11        | 1.97%   |
| TP-Link                          | 10        | 1.8%    |
| Samsung Electronics              | 9         | 1.62%   |
| MediaTek                         | 9         | 1.62%   |
| Ralink                           | 8         | 1.44%   |
| Marvell Technology Group         | 5         | 0.9%    |
| Microsoft                        | 4         | 0.72%   |
| Dell                             | 3         | 0.54%   |
| Broadcom Limited                 | 3         | 0.54%   |
| Xiaomi                           | 2         | 0.36%   |
| Nvidia                           | 2         | 0.36%   |
| Novatel Wireless                 | 2         | 0.36%   |
| Linksys                          | 2         | 0.36%   |
| D-Link                           | 2         | 0.36%   |
| ASIX Electronics                 | 2         | 0.36%   |
| Apple                            | 2         | 0.36%   |
| Wilocity                         | 1         | 0.18%   |
| VIA Technologies                 | 1         | 0.18%   |
| T & A Mobile Phones              | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Qualcomm Technologies            | 1         | 0.18%   |
| Qualcomm Atheros Communications  | 1         | 0.18%   |
| Qualcomm                         | 1         | 0.18%   |
| OPPO Electronics                 | 1         | 0.18%   |
| ICS Advent                       | 1         | 0.18%   |
| Huawei Technologies              | 1         | 0.18%   |
| Edimax Technology                | 1         | 0.18%   |
| DisplayLink                      | 1         | 0.18%   |
| Conexant Systems                 | 1         | 0.18%   |
| Belkin Components                | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 112       | 17.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 35        | 5.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 19        | 2.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 2.49%   |
| Intel Wi-Fi 6 AX200                                                    | 16        | 2.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 14        | 2.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 2.02%   |
| Realtek RTL8125 2.5GbE Controller                                      | 12        | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 11        | 1.71%   |
| Intel Wireless 8265 / 8275                                             | 10        | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 9         | 1.4%    |
| Intel Wi-Fi 6 AX201                                                    | 9         | 1.4%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 8         | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 8         | 1.25%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 8         | 1.25%   |
| Intel Wireless 8260                                                    | 8         | 1.25%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 1.09%   |
| Intel Ethernet Connection (2) I219-V                                   | 7         | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7         | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 6         | 0.93%   |
| Intel Wireless 7260                                                    | 6         | 0.93%   |
| Intel Wireless 3165                                                    | 6         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 6         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 0.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 5         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 0.78%   |
| Intel Wireless 7265                                                    | 5         | 0.78%   |
| Intel Ethernet Controller I225-V                                       | 5         | 0.78%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.78%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                   | 5         | 0.78%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                        | 4         | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.62%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 4         | 0.62%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 4         | 0.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 115       | 35.49%  |
| Realtek Semiconductor           | 70        | 21.6%   |
| Qualcomm Atheros                | 58        | 17.9%   |
| Broadcom                        | 24        | 7.41%   |
| Ralink Technology               | 11        | 3.4%    |
| TP-Link                         | 10        | 3.09%   |
| MediaTek                        | 9         | 2.78%   |
| Ralink                          | 8         | 2.47%   |
| Dell                            | 3         | 0.93%   |
| Broadcom Limited                | 3         | 0.93%   |
| Microsoft                       | 2         | 0.62%   |
| Linksys                         | 2         | 0.62%   |
| D-Link                          | 2         | 0.62%   |
| Wilocity                        | 1         | 0.31%   |
| Qualcomm Technologies           | 1         | 0.31%   |
| Qualcomm Atheros Communications | 1         | 0.31%   |
| Qualcomm                        | 1         | 0.31%   |
| Marvell Technology Group        | 1         | 0.31%   |
| Edimax Technology               | 1         | 0.31%   |
| Belkin Components               | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 19        | 5.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 4.92%   |
| Intel Wi-Fi 6 AX200                                            | 16        | 4.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 14        | 4.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 3.38%   |
| Intel Wireless 8265 / 8275                                     | 10        | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 2.77%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 2.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8         | 2.46%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 8         | 2.46%   |
| Intel Wireless 8260                                            | 8         | 2.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 2.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.85%   |
| Intel Wireless 7260                                            | 6         | 1.85%   |
| Intel Wireless 3165                                            | 6         | 1.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.85%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 5         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.54%   |
| Intel Wireless 7265                                            | 5         | 1.54%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 4         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.23%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 1.23%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 0.92%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 3         | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 0.92%   |
| Dell Wireless 5570e HSPA+ (42Mbps) Mobile Broadband Card       | 3         | 0.92%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 0.92%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 0.92%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 166       | 53.9%   |
| Intel                            | 82        | 26.62%  |
| Broadcom                         | 19        | 6.17%   |
| Samsung Electronics              | 9         | 2.92%   |
| Qualcomm Atheros                 | 9         | 2.92%   |
| Marvell Technology Group         | 4         | 1.3%    |
| Xiaomi                           | 2         | 0.65%   |
| Nvidia                           | 2         | 0.65%   |
| Novatel Wireless                 | 2         | 0.65%   |
| Microsoft                        | 2         | 0.65%   |
| ASIX Electronics                 | 2         | 0.65%   |
| Apple                            | 2         | 0.65%   |
| VIA Technologies                 | 1         | 0.32%   |
| T & A Mobile Phones              | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| OPPO Electronics                 | 1         | 0.32%   |
| ICS Advent                       | 1         | 0.32%   |
| Huawei Technologies              | 1         | 0.32%   |
| DisplayLink                      | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 112       | 35.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 35        | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 4.13%   |
| Realtek RTL8125 2.5GbE Controller                                      | 12        | 3.81%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8         | 2.54%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 2.22%   |
| Intel Ethernet Connection (2) I219-V                                   | 7         | 2.22%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.59%   |
| Intel Ethernet Controller I225-V                                       | 5         | 1.59%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.59%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.59%   |
| Intel Ethernet Connection (2) I218-V                                   | 5         | 1.59%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 3         | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.95%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 0.95%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.63%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.63%   |
| Novatel Wireless M2100                                                 | 2         | 0.63%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                     | 2         | 0.63%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.63%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.63%   |
| Intel 82583V Gigabit Network Connection                                | 2         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.63%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.63%   |
| Apple iPad 4/Mini1                                                     | 2         | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.32%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.32%   |
| T & A Mobile Phones Alcatel 1S                                         | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 1         | 0.32%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 300       | 50.93%  |
| Ethernet | 287       | 48.73%  |
| Modem    | 2         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 235       | 63.86%  |
| Ethernet | 133       | 36.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 192       | 54.08%  |
| 1     | 155       | 43.66%  |
| 4     | 3         | 0.85%   |
| 0     | 3         | 0.85%   |
| 3     | 2         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 234       | 63.07%  |
| Yes  | 137       | 36.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 100       | 39.53%  |
| Qualcomm Atheros Communications | 26        | 10.28%  |
| Realtek Semiconductor           | 23        | 9.09%   |
| IMC Networks                    | 22        | 8.7%    |
| Cambridge Silicon Radio         | 19        | 7.51%   |
| Foxconn / Hon Hai               | 13        | 5.14%   |
| Apple                           | 9         | 3.56%   |
| Broadcom                        | 8         | 3.16%   |
| Lite-On Technology              | 7         | 2.77%   |
| Toshiba                         | 5         | 1.98%   |
| TP-Link                         | 3         | 1.19%   |
| Realtek                         | 3         | 1.19%   |
| Ralink                          | 3         | 1.19%   |
| Dell                            | 3         | 1.19%   |
| MediaTek                        | 2         | 0.79%   |
| ASUSTek Computer                | 2         | 0.79%   |
| SiW                             | 1         | 0.4%    |
| Ralink Technology               | 1         | 0.4%    |
| Qcom                            | 1         | 0.4%    |
| Marvell Semiconductor           | 1         | 0.4%    |
| Hewlett-Packard                 | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 22        | 8.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 19        | 7.51%   |
| Intel Bluetooth wireless interface                                                  | 18        | 7.11%   |
| Intel Bluetooth Device                                                              | 17        | 6.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 5.93%   |
| Intel AX200 Bluetooth                                                               | 15        | 5.93%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 5.53%   |
| Realtek Bluetooth Radio                                                             | 13        | 5.14%   |
| IMC Networks Bluetooth Radio                                                        | 11        | 4.35%   |
| IMC Networks Bluetooth Device                                                       | 8         | 3.16%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 1.98%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 1.98%   |
| Realtek 802.11ac WLAN Adapter                                                       | 4         | 1.58%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.58%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.58%   |
| TP-Link UB500 Adapter                                                               | 3         | 1.19%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.19%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.19%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.19%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 1.19%   |
| Toshiba RT Bluetooth Radio                                                          | 2         | 0.79%   |
| MediaTek Wireless_Device                                                            | 2         | 0.79%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.79%   |
| Intel AX211 Bluetooth                                                               | 2         | 0.79%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.79%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.79%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.79%   |
| Apple Bluetooth Host Controller                                                     | 2         | 0.79%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.4%    |
| Toshiba Askey for                                                                   | 1         | 0.4%    |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.4%    |
| SiW SiW                                                                             | 1         | 0.4%    |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.4%    |
| Ralink CSR BS8510                                                                   | 1         | 0.4%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 288       | 59.02%  |
| Nvidia                           | 88        | 18.03%  |
| AMD                              | 74        | 15.16%  |
| C-Media Electronics              | 11        | 2.25%   |
| Kingston Technology              | 3         | 0.61%   |
| Creative Labs                    | 3         | 0.61%   |
| Tenx Technology                  | 2         | 0.41%   |
| Cooler Master                    | 2         | 0.41%   |
| VIA Technologies                 | 1         | 0.2%    |
| Texas Instruments                | 1         | 0.2%    |
| Sony                             | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Samson Technologies              | 1         | 0.2%    |
| Plantronics                      | 1         | 0.2%    |
| Nreal                            | 1         | 0.2%    |
| Nordic Semiconductor ASA         | 1         | 0.2%    |
| Microsoft                        | 1         | 0.2%    |
| Micro Star International         | 1         | 0.2%    |
| Logitech                         | 1         | 0.2%    |
| JMTek                            | 1         | 0.2%    |
| GYROCOM C&C                      | 1         | 0.2%    |
| Focusrite-Novation               | 1         | 0.2%    |
| DCMT Technology                  | 1         | 0.2%    |
| Creative Technology              | 1         | 0.2%    |
| Corsair                          | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 38        | 6.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 5.36%   |
| AMD Family 17h/19h HD Audio Controller                                     | 27        | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 4.29%   |
| Intel Cannon Lake PCH cAVS                                                 | 20        | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 2.86%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 2.86%   |
| Intel 200 Series PCH HD Audio                                              | 15        | 2.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14        | 2.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 2.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 2.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 2.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 2.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 1.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 9         | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 8         | 1.43%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.43%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 1.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 1.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8         | 1.43%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.25%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 1.07%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.07%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 1.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 0.89%   |
| Nvidia Audio device                                                        | 5         | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 0.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 0.89%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 0.89%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5         | 0.89%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung Electronics                  | 39        | 20.63%  |
| SK hynix                             | 36        | 19.05%  |
| Micron Technology                    | 26        | 13.76%  |
| Kingston                             | 22        | 11.64%  |
| Unknown                              | 14        | 7.41%   |
| Crucial                              | 11        | 5.82%   |
| G.Skill                              | 9         | 4.76%   |
| Team                                 | 6         | 3.17%   |
| Corsair                              | 4         | 2.12%   |
| Hikvision                            | 3         | 1.59%   |
| Elpida                               | 3         | 1.59%   |
| Unknown (ABCD)                       | 2         | 1.06%   |
| Nanya Technology                     | 2         | 1.06%   |
| Unknown (0x00FFFFFFFFFFFFFF)         | 1         | 0.53%   |
| Toshiba                              | 1         | 0.53%   |
| Silicon Power                        | 1         | 0.53%   |
| Ramaxel Technology                   | 1         | 0.53%   |
| Patriot Memory (PDP Systems)         | 1         | 0.53%   |
| Lexar Co Limited                     | 1         | 0.53%   |
| KLEVV                                | 1         | 0.53%   |
| Kingmax Semiconductor                | 1         | 0.53%   |
| D3860000                             | 1         | 0.53%   |
| Chun Well Technology Holding Limited | 1         | 0.53%   |
| ASint Technology                     | 1         | 0.53%   |
| A-DATA Technology                    | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.51%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.51%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 3         | 1.51%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1067MT/s               | 2         | 1.01%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 1.01%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s             | 2         | 1.01%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.01%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 1.01%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.01%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 1.01%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.01%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.01%   |
| Micron RAM Module 4GB DIMM DDR3 1333MT/s                         | 2         | 1.01%   |
| Hikvision RAM HKED4162DAA1D0MA1 16GB SODIMM DDR4 2667MT/s        | 2         | 1.01%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s            | 2         | 1.01%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 1.01%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.5%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.5%    |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.5%    |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.5%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.5%    |
| Unknown (0x00FFFFFFFFFFFFFF) RAM Module 4GB SODIMM DDR2 667MT/s  | 1         | 0.5%    |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 0.5%    |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s             | 1         | 0.5%    |
| Team RAM UD5-5600 16GB DIMM DDR5 12800MT/s                       | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 74        | 48.05%  |
| DDR3    | 56        | 36.36%  |
| LPDDR4  | 7         | 4.55%   |
| DDR2    | 5         | 3.25%   |
| LPDDR3  | 4         | 2.6%    |
| Unknown | 4         | 2.6%    |
| SDRAM   | 2         | 1.3%    |
| DDR5    | 2         | 1.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 56.21%  |
| DIMM         | 53        | 34.64%  |
| Row Of Chips | 13        | 8.5%    |
| Chip         | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 61        | 36.75%  |
| 4096  | 50        | 30.12%  |
| 16384 | 26        | 15.66%  |
| 2048  | 19        | 11.45%  |
| 32768 | 6         | 3.61%   |
| 1024  | 4         | 2.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 35        | 20.11%  |
| 3200    | 29        | 16.67%  |
| 2667    | 29        | 16.67%  |
| 1333    | 12        | 6.9%    |
| 1334    | 9         | 5.17%   |
| 2400    | 8         | 4.6%    |
| 2133    | 8         | 4.6%    |
| 3600    | 5         | 2.87%   |
| 3266    | 4         | 2.3%    |
| 1867    | 4         | 2.3%    |
| 800     | 4         | 2.3%    |
| 3733    | 3         | 1.72%   |
| 1800    | 3         | 1.72%   |
| 1067    | 3         | 1.72%   |
| 4267    | 2         | 1.15%   |
| 1866    | 2         | 1.15%   |
| 667     | 2         | 1.15%   |
| 12800   | 1         | 0.57%   |
| 4800    | 1         | 0.57%   |
| 4199    | 1         | 0.57%   |
| 3866    | 1         | 0.57%   |
| 3466    | 1         | 0.57%   |
| 3400    | 1         | 0.57%   |
| 3066    | 1         | 0.57%   |
| 2933    | 1         | 0.57%   |
| 1648    | 1         | 0.57%   |
| 1066    | 1         | 0.57%   |
| 975     | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 8         | 72.73%  |
| Brother Industries     | 2         | 18.18%  |
| Panasonic (Matsushita) | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Brother HL-2130 series             | 2         | 16.67%  |
| Panasonic (Matsushita) KX-MB1500RU | 1         | 8.33%   |
| HP LaserJet P2055 series           | 1         | 8.33%   |
| HP LaserJet P2015 series           | 1         | 8.33%   |
| HP LaserJet M101-M106              | 1         | 8.33%   |
| HP LaserJet CP 1025nw              | 1         | 8.33%   |
| HP LaserJet 400 M401dne            | 1         | 8.33%   |
| HP LaserJet 1020                   | 1         | 8.33%   |
| HP DeskJet Plus 4100 series        | 1         | 8.33%   |
| HP DeskJet 2700 series             | 1         | 8.33%   |
| HP DeskJet 2130 series             | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 500F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 35        | 18.42%  |
| IMC Networks                           | 27        | 14.21%  |
| Microdia                               | 18        | 9.47%   |
| Realtek Semiconductor                  | 12        | 6.32%   |
| Apple                                  | 12        | 6.32%   |
| Sunplus Innovation Technology          | 10        | 5.26%   |
| Bison Electronics                      | 10        | 5.26%   |
| Quanta                                 | 8         | 4.21%   |
| Lite-On Technology                     | 8         | 4.21%   |
| Suyin                                  | 7         | 3.68%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.68%   |
| Microsoft                              | 6         | 3.16%   |
| Samsung Electronics                    | 4         | 2.11%   |
| Importek                               | 4         | 2.11%   |
| Luxvisions Innotech Limited            | 3         | 1.58%   |
| Acer                                   | 3         | 1.58%   |
| Syntek                                 | 2         | 1.05%   |
| Silicon Motion                         | 2         | 1.05%   |
| Ricoh                                  | 2         | 1.05%   |
| Lenovo                                 | 2         | 1.05%   |
| ARC International                      | 2         | 1.05%   |
| Alcor Micro                            | 2         | 1.05%   |
| Z-Star Microelectronics                | 1         | 0.53%   |
| OmniVision Technologies                | 1         | 0.53%   |
| Logitech                               | 1         | 0.53%   |
| Arkmicro Technologies                  | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 12        | 6.28%   |
| Chicony Integrated Camera                                      | 12        | 6.28%   |
| Microdia Integrated_Webcam_HD                                  | 9         | 4.71%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 9         | 4.71%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 6         | 3.14%   |
| Sunplus Integrated_Webcam_HD                                   | 4         | 2.09%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 4         | 2.09%   |
| Lite-On HP TrueVision HD Camera                                | 3         | 1.57%   |
| IMC Networks HD Camera                                         | 3         | 1.57%   |
| Chicony HD WebCam                                              | 3         | 1.57%   |
| Bison Integrated Camera                                        | 3         | 1.57%   |
| Apple FaceTime HD Camera                                       | 3         | 1.57%   |
| Suyin 1.3M HD WebCam                                           | 2         | 1.05%   |
| Sunplus HD WebCam                                              | 2         | 1.05%   |
| Realtek Integrated_Webcam_HD                                   | 2         | 1.05%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.05%   |
| Realtek Integrated Webcam                                      | 2         | 1.05%   |
| Realtek HP Truevision HD integrated webcam                     | 2         | 1.05%   |
| Quanta HP Wide Vision HD Camera                                | 2         | 1.05%   |
| Microsoft LifeCam HD-3000                                      | 2         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 2         | 1.05%   |
| Microdia HP Integrated Webcam                                  | 2         | 1.05%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 2         | 1.05%   |
| Lite-On TOSHIBA Web Camera - HD                                | 2         | 1.05%   |
| Importek Laptop Integrated Webcam                              | 2         | 1.05%   |
| Chicony HP Wide Vision HD Camera                               | 2         | 1.05%   |
| Chicony HD User Facing                                         | 2         | 1.05%   |
| Chicony Front Camera                                           | 2         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.05%   |
| ARC International Camera                                       | 2         | 1.05%   |
| Apple FaceTime HD Camera (Built-in)                            | 2         | 1.05%   |
| Alcor Micro Asus Integrated Webcam                             | 2         | 1.05%   |
| Acer Lenovo EasyCamera                                         | 2         | 1.05%   |
| Z-Star Integrated Camera                                       | 1         | 0.52%   |
| Syntek Integrated Camera                                       | 1         | 0.52%   |
| Syntek EasyCamera                                              | 1         | 0.52%   |
| Suyin USB 2.0 Camera                                           | 1         | 0.52%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.52%   |
| Suyin HP TrueVision HD                                         | 1         | 0.52%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 28.57%  |
| Shenzhen Goodix Technology | 8         | 22.86%  |
| Validity Sensors           | 7         | 20%     |
| Elan Microelectronics      | 5         | 14.29%  |
| Upek                       | 2         | 5.71%   |
| LighTuning Technology      | 2         | 5.71%   |
| AuthenTec                  | 1         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 14.29%  |
| Elan ELAN:ARM-M4                                                           | 3         | 8.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 5.71%   |
| Synaptics  WBDI                                                            | 2         | 5.71%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 5.71%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 5.71%   |
| Synaptics Fingerprint scanner                                              | 2         | 5.71%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 5.71%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.86%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.86%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 2.86%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.86%   |
| Synaptics WBDI                                                             | 1         | 2.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.86%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.86%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.86%   |
| AuthenTec AES2810                                                          | 1         | 2.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 66.67%  |
| O2 Micro    | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 258       | 69.92%  |
| 1     | 93        | 25.2%   |
| 2     | 15        | 4.07%   |
| 3     | 2         | 0.54%   |
| 4     | 1         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 35        | 28%     |
| Graphics card            | 31        | 24.8%   |
| Net/wireless             | 20        | 16%     |
| Multimedia controller    | 11        | 8.8%    |
| Communication controller | 7         | 5.6%    |
| Chipcard                 | 6         | 4.8%    |
| Unassigned class         | 5         | 4%      |
| Bluetooth                | 4         | 3.2%    |
| Camera                   | 3         | 2.4%    |
| Storage/raid             | 1         | 0.8%    |
| Storage                  | 1         | 0.8%    |
| Modem                    | 1         | 0.8%    |

